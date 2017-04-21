# npmdoc-enchilada

#### api documentation for  enchilada (v0.13.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-enchilada.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-enchilada) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-enchilada.svg)](https://travis-ci.org/npmdoc/node-npmdoc-enchilada)

#### middleware for automatic javascript bundles

[![NPM](https://nodei.co/npm/enchilada.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/enchilada)

- [https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-enchilada/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-enchilada/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-enchilada/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-enchilada/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "enchilada",
    "version": "0.13.0",
    "description": "middleware for automatic javascript bundles",
    "main": "index.js",
    "scripts": {
        "test": "mocha test/*.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shtylman/node-enchilada.git"
    },
    "keywords": [
        "browserify",
        "express",
        "script",
        "bundle",
        "compile",
        "minify"
    ],
    "author": "Roman Shtylman <shtylman@gmail.com>",
    "license": "MIT",
    "dependencies": {
        "browserify": "4.1.9",
        "convert-source-map": "1.1.1",
        "debug": "2.2.0",
        "filewatcher": "3.0.0",
        "mime": "1.2.11",
        "ready-signal": "1.3.0",
        "uglify-js": "2.5.0"
    },
    "devDependencies": {
        "through": "2.3.4",
        "connect": "2.12.0",
        "mocha": "1.17.0",
        "after": "0.8.1",
        "supertest": "0.9.0",
        "express": "3.4.8"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
