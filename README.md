# npmtest-level-js

#### basic test coverage for  level-js (v2.2.4)  [![npm package](https://img.shields.io/npm/v/npmtest-level-js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-level-js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-level-js.svg)](https://travis-ci.org/npmtest/node-npmtest-level-js)

#### leveldown/leveldb library for browsers using IndexedDB

[![NPM](https://nodei.co/npm/level-js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/level-js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-level-js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-level-js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-level-js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-level-js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-level-js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-level-js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-level-js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-level-js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-level-js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-level-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-level-js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-level-js/build/test-report.html](https://npmtest.github.io/node-npmtest-level-js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-level-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-level-js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-level-js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-level-js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-level-js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-level-js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-level-js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-level-js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "level-js",
    "version": "2.2.4",
    "description": "leveldown/leveldb library for browsers using IndexedDB",
    "main": "index.js",
    "scripts": {
        "test": "beefy test/test.js:test.js test/test-levelup.js:test-levelup.js"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:maxogden/level.js.git"
    },
    "keywords": [
        "level",
        "leveldb"
    ],
    "author": "max ogden",
    "license": "BSD-2-Clause",
    "devDependencies": {
        "beefy": "~0.3.0",
        "browserify": "^4.1.2",
        "levelup": "~0.18.2",
        "tape": "^4.0.0"
    },
    "dependencies": {
        "abstract-leveldown": "~0.12.0",
        "idb-wrapper": "^1.5.0",
        "isbuffer": "~0.0.0",
        "ltgt": "^2.1.2",
        "typedarray-to-buffer": "~1.0.0",
        "xtend": "~2.1.2"
    },
    "testling": {
        "files": "test/test.js",
        "browsers": [
            "ie/10..latest",
            "firefox/17..latest",
            "chrome/25..latest",
            "opera/15..latest",
            "safari/6.0..latest"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
