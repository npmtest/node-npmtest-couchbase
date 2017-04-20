# npmtest-couchbase

#### basic test coverage for  [couchbase (v2.3.2)](http://www.couchbase.com/communities/nodejs)  [![npm package](https://img.shields.io/npm/v/npmtest-couchbase.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-couchbase) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-couchbase.svg)](https://travis-ci.org/npmtest/node-npmtest-couchbase)

#### The official Couchbase Node.js Client Library.

[![NPM](https://nodei.co/npm/couchbase.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/couchbase)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-couchbase/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-couchbase/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-couchbase/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-couchbase/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-couchbase/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-couchbase/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-couchbase/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-couchbase/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-couchbase/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-couchbase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-couchbase/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-couchbase/build/test-report.html](https://npmtest.github.io/node-npmtest-couchbase/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-couchbase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-couchbase/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-couchbase/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-couchbase/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-couchbase/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-couchbase/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-couchbase/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-couchbase/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "http://www.couchbase.com/issues/browse/JSCBC"
    },
    "description": "The official Couchbase Node.js Client Library.",
    "engines": {
        "node": ">=0.8.8"
    },
    "homepage": "http://www.couchbase.com/communities/nodejs",
    "keywords": [
        "couchbase",
        "libcouchbase",
        "memcached",
        "nosql",
        "json",
        "document"
    ],
    "main": "./lib/couchbase",
    "license": "Apache-2.0",
    "name": "couchbase",
    "dependencies": {
        "bindings": "~1.2.1",
        "mocha": "~3.2.0",
        "nan": "~2.5.1",
        "prebuild": "~6.1.0",
        "request": "~2.80.0"
    },
    "devDependencies": {
        "ink-docstrap": "git+https://github.com/brett19/docstrap.git#master",
        "istanbul": "~0.4.3",
        "jsdoc": "~3.4.0",
        "jsdoc-stability-tag": "~1.0.0",
        "jshint": "~2.9.2",
        "mocha": "~3.2.0"
    },
    "repository": {
        "type": "git",
        "url": "http://github.com/couchbase/couchnode.git"
    },
    "version": "2.3.2",
    "config": {
        "native": false
    },
    "scripts": {
        "install": "prebuild --install",
        "test": "mocha",
        "rebuild": "prebuild --compile",
        "prebuild": "prebuild --verbose --strip"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
