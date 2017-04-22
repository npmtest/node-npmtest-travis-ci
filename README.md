# npmtest-travis-ci

#### basic test coverage for  [travis-ci (v2.1.1)](https://github.com/pwmckenna/node-travis-ci)  [![npm package](https://img.shields.io/npm/v/npmtest-travis-ci.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-travis-ci) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-travis-ci.svg)](https://travis-ci.org/npmtest/node-npmtest-travis-ci)

#### node library to access the Travis-CI API

[![NPM](https://nodei.co/npm/travis-ci.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/travis-ci)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-travis-ci/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-travis-ci/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-travis-ci/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-travis-ci/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-travis-ci/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-travis-ci/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-travis-ci/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-travis-ci/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-travis-ci/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-travis-ci/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-travis-ci/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-travis-ci/build/test-report.html](https://npmtest.github.io/node-npmtest-travis-ci/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-travis-ci/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-travis-ci/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-travis-ci/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-travis-ci/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-travis-ci/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-travis-ci/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-travis-ci/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-travis-ci/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Williams"
    },
    "bin": {
        "travis-ci": "./bin/travis-ci.js"
    },
    "bugs": {
        "url": "https://github.com/pwmckenna/node-travis-ci/issues"
    },
    "dependencies": {
        "github": "~0.1.10",
        "lodash": "~1.3.1",
        "request": "~2.74.0",
        "underscore.string": "~2.2.0rc"
    },
    "description": "node library to access the Travis-CI API",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.9",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-env": "~0.4.0",
        "grunt-mocha-test": "~0.5.0",
        "grunt-release": "~0.7.0",
        "matchdep": "~0.1.2",
        "mocha": "~1.12.0",
        "q": "~1.0.0",
        "should": "~1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "98696265af827ae3576f31aa06d876e74b4b082e",
        "tarball": "https://registry.npmjs.org/travis-ci/-/travis-ci-2.1.1.tgz"
    },
    "gitHead": "490b3b041b399733600c715d8f6d931694e42a29",
    "homepage": "https://github.com/pwmckenna/node-travis-ci",
    "keywords": [
        "travis-ci",
        "travis",
        "travisci",
        "ci",
        "continuous",
        "integration",
        "api"
    ],
    "license": "BSD",
    "main": "lib/travis-ci",
    "maintainers": [
        {
            "name": "ljharb"
        },
        {
            "name": "pwmckenna"
        }
    ],
    "name": "travis-ci",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/pwmckenna/node-travis-ci.git"
    },
    "scripts": {
        "test": "mocha --recursive test"
    },
    "version": "2.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
