# npmdoc-pad

#### api documentation for  [pad (v1.1.0)](https://github.com/adaltas/node-pad)  [![npm package](https://img.shields.io/npm/v/npmdoc-pad.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pad) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pad.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pad)

#### Left and right string padding

[![NPM](https://nodei.co/npm/pad.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pad)

- [https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pad/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pad/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pad/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pad/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pad",
    "description": "Left and right string padding",
    "version": "1.1.0",
    "author": "David Worms <david@adaltas.com>",
    "contributors": [
        {
            "name": "David Worms"
        }
    ],
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "mocha": "^3.2.0",
        "should": "^11.2.0"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "homepage": "https://github.com/adaltas/node-pad",
    "keywords": [
        "pad",
        "string"
    ],
    "license": "BSD-3-Clause",
    "main": "./lib",
    "repository": {
        "type": "git",
        "url": "https://github.com/adaltas/node-pad.git"
    },
    "scripts": {
        "coffee": "coffee -b -o lib src",
        "pretest": "coffee -b -o lib src",
        "test": "mocha --compilers coffee:coffee-script/register --reporter dot"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
