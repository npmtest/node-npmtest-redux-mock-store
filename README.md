# npmtest-redux-mock-store

#### test coverage for  [redux-mock-store (v1.2.3)](https://github.com/arnaudbenard/redux-mock-store#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-mock-store.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-mock-store) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-mock-store.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-mock-store)

#### A mock store for testing your redux async action creators and middleware

[![NPM](https://nodei.co/npm/redux-mock-store.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-mock-store)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-mock-store/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-mock-store/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-mock-store/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-mock-store/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-mock-store/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-mock-store/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-mock-store/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-mock-store/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-mock-store/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-mock-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-mock-store/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-mock-store/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-mock-store/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-mock-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-mock-store/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-mock-store/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-mock-store/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-mock-store/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnaud Benard"
    },
    "bugs": {
        "url": "https://github.com/arnaudbenard/redux-mock-store/issues"
    },
    "dependencies": {},
    "description": "A mock store for testing your redux async action creators and middleware",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-preset-es2015": "^6.13.2",
        "expect": "^1.12.2",
        "mocha": "^2.3.3",
        "redux": "^3.0.4",
        "redux-thunk": "^2.0.1",
        "rimraf": "^2.4.3",
        "sinon": "^1.17.2",
        "standard": "^7.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "1b3ad299da91cb41ba30d68e3b6f024475fb9e1b",
        "tarball": "https://registry.npmjs.org/redux-mock-store/-/redux-mock-store-1.2.3.tgz"
    },
    "gitHead": "65d143a6a3a3b882c57731731adfdcc0e9cac86a",
    "homepage": "https://github.com/arnaudbenard/redux-mock-store#readme",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "arnaudbenard"
        },
        {
            "name": "dmitry-zaets"
        }
    ],
    "name": "redux-mock-store",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/arnaudbenard/redux-mock-store.git"
    },
    "scripts": {
        "lint": "standard src/*.js test/*.js",
        "prepublish": "rimraf lib && babel src --out-dir lib",
        "pretest": "npm run lint",
        "test": "mocha --compilers js:babel-core/register --reporter spec test/*.js"
    },
    "version": "1.2.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
