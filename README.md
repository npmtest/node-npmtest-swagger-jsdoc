# npmtest-swagger-jsdoc

#### basic test coverage for  [swagger-jsdoc (v1.9.2)](https://github.com/Surnet/swagger-jsdoc)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger-jsdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger-jsdoc)

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
    "name": "swagger-jsdoc",
    "version": "1.9.2",
    "description": "Generates swagger doc based on JSDoc",
    "main": "index.js",
    "scripts": {
        "coverage": "istanbul cover _mocha --report html && istanbul check-coverage --statement 95",
        "jsdoc": "jsdoc --configure .jsdocconf",
        "start": "node example/app.js",
        "test": "mocha"
    },
    "bin": {
        "swagger-jsdoc": "./bin/swagger-jsdoc.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Surnet/swagger-jsdoc.git"
    },
    "keywords": [
        "jsdoc",
        "restful",
        "api",
        "express",
        "swagger"
    ],
    "author": "https://github.com/Surnet/swagger-jsdoc/graphs/contributors",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Surnet/swagger-jsdoc/issues"
    },
    "homepage": "https://github.com/Surnet/swagger-jsdoc",
    "dependencies": {
        "chokidar": "^1.6.1",
        "commander": "^2.9.0",
        "doctrine": "^2.0.0",
        "glob": "^7.0.3",
        "js-yaml": "^3.5.3",
        "recursive-iterator": "^2.0.3",
        "swagger-parser": "^3.4.0"
    },
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
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
