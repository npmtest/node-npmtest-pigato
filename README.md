# npmtest-pigato

#### basic test coverage for  [pigato (v0.0.46)](https://github.com/prdn/pigato)  [![npm package](https://img.shields.io/npm/v/npmtest-pigato.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pigato) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pigato.svg)](https://travis-ci.org/npmtest/node-npmtest-pigato)

#### An high-performance Node.js microservices framework based on ZeroMQ

[![NPM](https://nodei.co/npm/pigato.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pigato)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pigato/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pigato/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pigato/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pigato/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pigato/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pigato/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pigato/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pigato/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pigato/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pigato/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pigato/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pigato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pigato/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pigato/build/test-report.html](https://npmtest.github.io/node-npmtest-pigato/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pigato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pigato/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pigato/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pigato/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pigato/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pigato/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pigato",
    "version": "0.0.46",
    "private": false,
    "description": "An high-performance Node.js microservices framework based on ZeroMQ",
    "author": "prdn <paolo.ardoino@gmail.com> (http://ardoino.com/)",
    "keywords": [
        "pigato",
        "nodejs",
        "zmq",
        "zeromq",
        "0mq",
        "request-reply",
        "amqp",
        "mdp",
        "micro-services"
    ],
    "dependencies": {
        "async": "~1.5.2",
        "debug": "~2.2.0",
        "es6-shim": "^0.33.13",
        "lodash": "~4.2.1",
        "node-uuid": "~1.4.7",
        "readable-stream": "2.0.4",
        "semver": "^5.0.3",
        "zmq": "~2.15.2"
    },
    "engine": {
        "node": ">=0.10"
    },
    "main": "index.js",
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "devDependencies": {
        "chai": "~3.2.0",
        "mocha": "~2.2.5"
    },
    "scripts": {
        "test": "make test",
        "lint": "eslint --config .eslintrc --fix index.js lib/ test/"
    },
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/prdn/pigato.git"
    },
    "bugs": {
        "url": "https://github.com/prdn/pigato/issues"
    },
    "homepage": "https://github.com/prdn/pigato",
    "optionalDependencies": {
        "eslint": "~1.6.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
