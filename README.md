# npmtest-uuid

#### basic test coverage for  [uuid (v3.0.1)](https://github.com/kelektiv/node-uuid#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-uuid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-uuid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-uuid.svg)](https://travis-ci.org/npmtest/node-npmtest-uuid)

#### RFC4122 (v1 and v4) generator

[![NPM](https://nodei.co/npm/uuid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/uuid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-uuid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-uuid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-uuid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-uuid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-uuid/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-uuid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-uuid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-uuid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-uuid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-uuid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-uuid/build/test-report.html](https://npmtest.github.io/node-npmtest-uuid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-uuid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-uuid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-uuid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-uuid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-uuid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-uuid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-uuid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "uuid": "./bin/uuid"
    },
    "browser": {
        "./lib/rng.js": "./lib/rng-browser.js"
    },
    "bugs": {
        "url": "https://github.com/kelektiv/node-uuid/issues"
    },
    "contributors": [
        {
            "name": "Robert Kieffer"
        },
        {
            "name": "Christoph Tavan"
        },
        {
            "name": "AJ ONeal"
        },
        {
            "name": "Vincent Voyer"
        },
        {
            "name": "Roman Shtylman"
        }
    ],
    "dependencies": {},
    "description": "RFC4122 (v1 and v4) generator",
    "devDependencies": {
        "mocha": "3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "6544bba2dfda8c1cf17e629a3a305e2bb1fee6c1",
        "tarball": "https://registry.npmjs.org/uuid/-/uuid-3.0.1.tgz"
    },
    "gitHead": "374de826de71d8997f71b4641f65552e48956ced",
    "homepage": "https://github.com/kelektiv/node-uuid#readme",
    "keywords": [
        "uuid",
        "guid",
        "rfc4122"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "broofa"
        },
        {
            "name": "defunctzombie"
        },
        {
            "name": "vvo"
        }
    ],
    "name": "uuid",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kelektiv/node-uuid.git"
    },
    "scripts": {
        "test": "mocha test/test.js"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
