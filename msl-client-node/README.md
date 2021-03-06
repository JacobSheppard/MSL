MSL [![Build Status](https://secure.travis-ci.org/FINRAOS/MSL.png?branch=master)](http://travis-ci.org/FINRAOS/MSL)
===
[MSL](http://finraos.github.io/MSL/) (pronounced 'Missile') stands for Mock Service Layer. Our tools enable quick local deployment of your UI code on Node and mocking of your service layer for fast, targeted testing.

Here is the link to [getting started](http://finraos.github.io/MSL/gettingstarted.html)

Prerequisite
=============
Install [msl-server](https://www.npmjs.org/package/msl-server) first before using msl-client

Installation
=============
Use the following command to install MSL Client
```bash
npm install msl-client
```

Using MSL Client
===================
```js
var msl = require('msl-client');
```

API Doc
========
Go to [this page](http://finraos.github.io/MSL/apidoc.html) and refer to 'NodeJS Client'

Contributing
=============
We encourage contribution from the open source community to help make MSL better. Please refer to the [development](http://finraos.github.io/MSL/contribute.html) page for more information on how to contribute to this project including sign off and the [DCO](https://github.com/FINRAOS/MSL/blob/master/DCO) agreement.

If you have any questions or discussion topics, please post them on [Google Groups](https://groups.google.com/forum/#!forum/msl_os).

Building
=========
Our project is built automatically on [Travis-CI](https://travis-ci.org/FINRAOS/MSL) for all pull requests and merge requests.

Running Tests
==============
After you checkout the code, execute E2E tests by running [test/e2e-run.sh](https://github.com/FINRAOS/MSL/blob/master/test/e2e-run.sh) from the root folder.  This script will:

1. Install msl-server
2. Start sample app using msl-server
3. Build client
4. Run unit tests

License Type
=============
MSL project is licensed under [Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)


