# npmtest-iconv-lite

#### basic test-coverage for  [iconv-lite (v0.4.15)](https://github.com/ashtuchkin/iconv-lite)  [![npm package](https://img.shields.io/npm/v/npmtest-iconv-lite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-iconv-lite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-iconv-lite.svg)](https://travis-ci.org/npmtest/node-npmtest-iconv-lite)

#### Convert character encodings in pure javascript.

[![NPM](https://nodei.co/npm/iconv-lite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/iconv-lite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-iconv-lite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-iconv-lite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-iconv-lite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-iconv-lite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-iconv-lite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-iconv-lite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-iconv-lite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-iconv-lite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-iconv-lite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-iconv-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-iconv-lite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-iconv-lite/build/test-report.html](https://npmtest.github.io/node-npmtest-iconv-lite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-iconv-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-iconv-lite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-iconv-lite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-iconv-lite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-iconv-lite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-iconv-lite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-iconv-lite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-iconv-lite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexander Shtuchkin"
    },
    "browser": {
        "./extend-node": false,
        "./streams": false
    },
    "bugs": {
        "url": "https://github.com/ashtuchkin/iconv-lite/issues"
    },
    "contributors": [
        {
            "name": "Jinwu Zhan",
            "url": "https://github.com/jenkinv"
        },
        {
            "name": "Adamansky Anton",
            "url": "https://github.com/adamansky"
        },
        {
            "name": "George Stagas",
            "url": "https://github.com/stagas"
        },
        {
            "name": "Mike D Pilsbury",
            "url": "https://github.com/pekim"
        },
        {
            "name": "Niggler",
            "url": "https://github.com/Niggler"
        },
        {
            "name": "wychi",
            "url": "https://github.com/wychi"
        },
        {
            "name": "David Kuo",
            "url": "https://github.com/david50407"
        },
        {
            "name": "ChangZhuo Chen",
            "url": "https://github.com/czchen"
        },
        {
            "name": "Lee Treveil",
            "url": "https://github.com/leetreveil"
        },
        {
            "name": "Brian White",
            "url": "https://github.com/mscdex"
        },
        {
            "name": "Mithgol",
            "url": "https://github.com/Mithgol"
        },
        {
            "name": "Nazar Leush",
            "url": "https://github.com/nleush"
        }
    ],
    "dependencies": {},
    "description": "Convert character encodings in pure javascript.",
    "devDependencies": {
        "async": "*",
        "errto": "*",
        "iconv": "*",
        "istanbul": "*",
        "mocha": "*",
        "request": "*",
        "unorm": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "fe265a218ac6a57cfe854927e9d04c19825eddeb",
        "tarball": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.15.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "c3bcedcd6a5025c25e39ed1782347acaed1d290f",
    "homepage": "https://github.com/ashtuchkin/iconv-lite",
    "keywords": [
        "iconv",
        "convert",
        "charset",
        "icu"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "ashtuchkin"
        }
    ],
    "name": "iconv-lite",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ashtuchkin/iconv-lite.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- --grep .",
        "coverage-open": "open coverage/lcov-report/index.html",
        "test": "mocha --reporter spec --grep ."
    },
    "typings": "./lib/index.d.ts",
    "version": "0.4.15",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
