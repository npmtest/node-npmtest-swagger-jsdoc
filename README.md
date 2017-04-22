# npmtest-swagger-jsdoc

#### basic test-coverage for  [swagger-jsdoc (v1.9.2)](https://github.com/Surnet/swagger-jsdoc)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger-jsdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger-jsdoc)

#### Generates swagger doc based on JSDoc

[![NPM](https://nodei.co/npm/swagger-jsdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-jsdoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swagger-jsdoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swagger-jsdoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swagger-jsdoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/test-report.html](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swagger-jsdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-jsdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swagger-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "https://github.com/Surnet/swagger-jsdoc/graphs/contributors"
    },
    "bin": {
        "swagger-jsdoc": "./bin/swagger-jsdoc.js"
    },
    "bugs": {
        "url": "https://github.com/Surnet/swagger-jsdoc/issues"
    },
    "dependencies": {
        "chokidar": "^1.6.1",
        "commander": "^2.9.0",
        "doctrine": "^2.0.0",
        "glob": "^7.0.3",
        "js-yaml": "^3.5.3",
        "recursive-iterator": "^2.0.3",
        "swagger-parser": "^3.4.0"
    },
    "description": "Generates swagger doc based on JSDoc",
    "devDependencies": {
        "body-parser": "^1.15.0",
        "chai": "^3.5.0",
        "express": "^4.13.4",
        "istanbul": "^0.4.2",
        "jscs": "^3.0.0",
        "mocha": "^3.2.0",
        "mocha-jscs": "^5.0.0",
        "mocha-jshint": "^2.3.1",
        "supertest": "^2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b62116057dc1ff52304aa5c8bcb7738b17e8daa9",
        "tarball": "https://registry.npmjs.org/swagger-jsdoc/-/swagger-jsdoc-1.9.2.tgz"
    },
    "gitHead": "b871d6f60b389ded6ea7becd5e7150fd42fbcc64",
    "homepage": "https://github.com/Surnet/swagger-jsdoc",
    "keywords": [
        "jsdoc",
        "restful",
        "api",
        "express",
        "swagger"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chdanielmueller"
        },
        {
            "name": "drgrove"
        },
        {
            "name": "kalin.chernev"
        }
    ],
    "name": "swagger-jsdoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Surnet/swagger-jsdoc.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha --report html && istanbul check-coverage --statement 95",
        "jsdoc": "jsdoc --configure .jsdocconf",
        "start": "node example/app.js",
        "test": "mocha"
    },
    "version": "1.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
