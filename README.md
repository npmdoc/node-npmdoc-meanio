# npmdoc-meanio

#### api documentation for  [meanio (v0.9.4)](https://github.com/linnovate/meanio#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-meanio.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-meanio) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-meanio.svg)](https://travis-ci.org/npmdoc/node-npmdoc-meanio)

#### Extracted functionality for MEAN.io

[![NPM](https://nodei.co/npm/meanio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/meanio)

- [https://npmdoc.github.io/node-npmdoc-meanio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-meanio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-meanio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-meanio/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-meanio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-meanio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "linnovate"
    },
    "bugs": {
        "url": "https://github.com/linnovate/meanio/issues"
    },
    "contributors": "https://github.com/linnovate/meanio/graphs/contributors",
    "dependencies": {
        "assetmanager": "^1.2.2",
        "complex-list": "latest",
        "config": "^1.19.0",
        "dependable-list": "latest",
        "errorhandler": "latest",
        "eventemitter2": "1.0.0",
        "express-jwt": "latest",
        "glob": "5.0.15",
        "lazy-dependable": "latest",
        "lodash": "latest",
        "md5": "latest",
        "mongoose": "^4.3.6",
        "morgan": "1.5.3",
        "q": "^1.0.1",
        "querystring": "latest",
        "request": "^2.47.0",
        "rtlcss": "^2.0.5",
        "shelljs": "^0.7.0",
        "snyk": "^1.17.5",
        "socketio-sticky-session": "^0.4.1",
        "swig": "^1.3.2",
        "uglify-js": "^2.7.0"
    },
    "description": "Extracted functionality for MEAN.io",
    "devDependencies": {
        "chai": "^3.5.0",
        "gulp": "^3.9.0",
        "gulp-mocha": "^2.2.0",
        "mocha": "^1.18.2",
        "mocha-sinon": "^1.1.5",
        "should": "^3.2.0",
        "sinon": "^1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "de0f27e7fe35e4abd4062d742c32947fb694b7b2",
        "tarball": "https://registry.npmjs.org/meanio/-/meanio-0.9.4.tgz"
    },
    "gitHead": "b606087d70e586e7143af1eea2c2ad442f722c14",
    "homepage": "https://github.com/linnovate/meanio#readme",
    "keywords": [
        "mean",
        "meanio",
        "mean.io",
        "mean-cli"
    ],
    "license": "MIT",
    "main": "lib/mean.js",
    "maintainers": [
        {
            "name": "andrija-hers"
        },
        {
            "name": "ellman"
        },
        {
            "name": "fyockm"
        },
        {
            "name": "linnovate"
        },
        {
            "name": "oritpersik"
        },
        {
            "name": "vapes"
        }
    ],
    "name": "meanio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/linnovate/meanio.git"
    },
    "scripts": {
        "postinstall": "cd ./lib/core_modules/server && npm install && cd ../../..",
        "prepublish": "npm run snyk-protect",
        "snyk-protect": "snyk protect",
        "test": "gulp test"
    },
    "snyk": true,
    "version": "0.9.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
