# npmtest-findup-sync

#### basic test coverage for  [findup-sync (v1.0.0)](https://github.com/cowboy/node-findup-sync)  [![npm package](https://img.shields.io/npm/v/npmtest-findup-sync.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-findup-sync) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-findup-sync.svg)](https://travis-ci.org/npmtest/node-npmtest-findup-sync)

#### Find the first file matching a given pattern in the current directory or the nearest ancestor directory.

[![NPM](https://nodei.co/npm/findup-sync.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/findup-sync)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-findup-sync/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-findup-sync/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-findup-sync/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-findup-sync/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-findup-sync/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-findup-sync/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-findup-sync/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-findup-sync/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-findup-sync/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-findup-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-findup-sync/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-findup-sync/build/test-report.html](https://npmtest.github.io/node-npmtest-findup-sync/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-findup-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-findup-sync/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-findup-sync/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-findup-sync/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-findup-sync/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-findup-sync/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-findup-sync/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-findup-sync/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "\"Cowboy\" Ben Alman",
        "url": "http://benalman.com"
    },
    "bugs": {
        "url": "https://github.com/cowboy/node-findup-sync/issues"
    },
    "dependencies": {
        "detect-file": "^0.1.0",
        "is-glob": "^2.0.1",
        "micromatch": "^2.3.7",
        "resolve-dir": "^0.1.0"
    },
    "description": "Find the first file matching a given pattern in the current directory or the nearest ancestor directory.",
    "devDependencies": {
        "fs-exists-sync": "^0.1.0",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^0.12.0",
        "is-absolute": "^0.2.3",
        "minimist": "^1.2.0",
        "mocha": "^2.4.5",
        "normalize-path": "^2.0.1",
        "os-homedir": "^1.0.1",
        "resolve": "^1.1.7"
    },
    "directories": {},
    "dist": {
        "shasum": "6f7e4b57b6ee3a4037b4414eaedea3f58f71e0ec",
        "tarball": "https://registry.npmjs.org/findup-sync/-/findup-sync-1.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "c19ee365c78410950e5acff7608bd62290d2fb89",
    "homepage": "https://github.com/cowboy/node-findup-sync",
    "keywords": [
        "file",
        "find",
        "find-up",
        "findup",
        "glob",
        "match",
        "pattern",
        "resolve",
        "search"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "cowboy"
        },
        {
            "name": "jonschlinkert"
        },
        {
            "name": "phated"
        },
        {
            "name": "tkellen"
        }
    ],
    "name": "findup-sync",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cowboy/node-findup-sync.git"
    },
    "scripts": {
        "test": "grunt && mocha"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
