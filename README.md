# npmtest-webpack-dev-middleware

#### test coverage for  [webpack-dev-middleware (v1.10.1)](http://github.com/webpack/webpack-dev-middleware)  [![npm package](https://img.shields.io/npm/v/npmtest-webpack-dev-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webpack-dev-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webpack-dev-middleware.svg)](https://travis-ci.org/npmtest/node-npmtest-webpack-dev-middleware)

#### Offers a dev middleware for webpack, which arguments a live bundle to a directory

[![NPM](https://nodei.co/npm/webpack-dev-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webpack-dev-middleware)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webpack-dev-middleware/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webpack-dev-middleware/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/test-report.html](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webpack-dev-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webpack-dev-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webpack-dev-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webpack-dev-middleware/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webpack-dev-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tobias Koppers @sokra"
    },
    "bugs": {
        "url": "https://github.com/webpack/webpack-dev-middleware/issues"
    },
    "dependencies": {
        "memory-fs": "~0.4.1",
        "mime": "^1.3.4",
        "path-is-absolute": "^1.0.0",
        "range-parser": "^1.0.3"
    },
    "description": "Offers a dev middleware for webpack, which arguments a live bundle to a directory",
    "devDependencies": {
        "codecov.io": "^0.1.6",
        "eslint": "^3.4.0",
        "express": "^4.14.0",
        "file-loader": "^0.9.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.0.2",
        "mocha-sinon": "^1.1.6",
        "should": "^11.1.0",
        "sinon": "^1.17.5",
        "supertest": "^2.0.0",
        "webpack": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c6b4cf428139cf1aefbe06a0c00fdb4f8da2f893",
        "tarball": "https://registry.npmjs.org/webpack-dev-middleware/-/webpack-dev-middleware-1.10.1.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "files": [
        "middleware.js",
        "lib/"
    ],
    "gitHead": "8e870fdb313e83bf2562e4fd4d5735035074903f",
    "homepage": "http://github.com/webpack/webpack-dev-middleware",
    "license": "MIT",
    "main": "middleware.js",
    "maintainers": [
        {
            "name": "jhnns"
        },
        {
            "name": "peerigon"
        },
        {
            "name": "sokra"
        },
        {
            "name": "spacek33z"
        }
    ],
    "name": "webpack-dev-middleware",
    "optionalDependencies": {},
    "peerDependencies": {
        "webpack": "1 || ^2.1.0-beta || ^2.2.0-rc.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/webpack/webpack-dev-middleware.git"
    },
    "scripts": {
        "beautify": "npm run lint -- --fix",
        "cover": "istanbul cover node_modules/mocha/bin/_mocha",
        "lint": "eslint *.js lib test",
        "posttest": "npm run -s lint",
        "test": "mocha --full-trace --check-leaks",
        "travis": "npm run cover -- --report lcovonly && npm run lint"
    },
    "version": "1.10.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
