# npmtest-jsxstyle

#### basic test coverage for  jsxstyle (v1.0.2)  [![npm package](https://img.shields.io/npm/v/npmtest-jsxstyle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsxstyle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsxstyle.svg)](https://travis-ci.org/npmtest/node-npmtest-jsxstyle)

#### React component styler

[![NPM](https://nodei.co/npm/jsxstyle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsxstyle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsxstyle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsxstyle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsxstyle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsxstyle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsxstyle/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsxstyle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsxstyle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsxstyle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsxstyle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsxstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsxstyle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsxstyle/build/test-report.html](https://npmtest.github.io/node-npmtest-jsxstyle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsxstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsxstyle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsxstyle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsxstyle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsxstyle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "dependencies": {
        "invariant": "^2.2.1",
        "loader-utils": "^0.2.15",
        "object-assign": "^4.1.0",
        "react-css-property-operations": "^15.4.1",
        "recast": "^0.11.11",
        "style-loader": "^0.13.1"
    },
    "description": "React component styler",
    "devDependencies": {
        "babel-cli": "^6.11.4",
        "babel-core": "^6.13.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-react": "^6.11.1",
        "bluebird": "^3.4.1",
        "css-loader": "^0.25.0",
        "eslint": "^3.3.0",
        "extract-text-webpack-plugin": "^1.0.1",
        "jasmine-node": "^1.14.5",
        "jasmine-pit": "^2.0.2",
        "node-jsdom": "^3.1.5",
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0",
        "webpack": "1.13.1"
    },
    "directories": {},
    "dist": {
        "shasum": "10ccc3a229a89f6b04c581200ba7c699f76a3344",
        "tarball": "https://registry.npmjs.org/jsxstyle/-/jsxstyle-1.0.2.tgz"
    },
    "gitHead": "23b2033047b83ea63c6c88f2d69d82d21633b7b7",
    "license": "Apache 2",
    "main": "index.js",
    "maintainers": [
        {
            "name": "floydophone"
        },
        {
            "name": "meyer"
        }
    ],
    "name": "jsxstyle",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0"
    },
    "scripts": {
        "babel": "babel ./src --out-dir ./lib",
        "example": "cd example; webpack",
        "lint": "eslint lib/",
        "prepublish": "npm run babel",
        "test": "jasmine-node tests/",
        "watch": "babel --watch ./src --out-dir ./lib"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
