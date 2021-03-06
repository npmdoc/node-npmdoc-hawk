# npmdoc-hawk

#### basic api documentation for  [hawk (v6.0.1)](https://github.com/hueniverse/hawk#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-hawk.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hawk) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hawk.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hawk)

#### HTTP Hawk Authentication Scheme

[![NPM](https://nodei.co/npm/hawk.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hawk)

- [https://npmdoc.github.io/node-npmdoc-hawk/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hawk/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hawk/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hawk/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hawk/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hawk/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eran Hammer",
        "url": "http://hueniverse.com"
    },
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "browser": "dist/browser.js",
    "bugs": {
        "url": "https://github.com/hueniverse/hawk/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "cryptiles": "3.x.x",
        "hoek": "4.x.x",
        "sntp": "2.x.x"
    },
    "description": "HTTP Hawk Authentication Scheme",
    "devDependencies": {
        "babel-cli": "^6.1.2",
        "babel-preset-es2015": "^6.1.2",
        "code": "4.x.x",
        "lab": "11.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "a78a656d1ef297cf4c313c1d4418c23630065e4d",
        "tarball": "https://registry.npmjs.org/hawk/-/hawk-6.0.1.tgz"
    },
    "engines": {
        "node": ">=4.5.0"
    },
    "gitHead": "2c0012f9a9ee2799d1a704cb494ea7d63ba3902f",
    "homepage": "https://github.com/hueniverse/hawk#readme",
    "keywords": [
        "http",
        "authentication",
        "scheme",
        "hawk"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "hueniverse"
        }
    ],
    "name": "hawk",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hueniverse/hawk.git"
    },
    "scripts": {
        "build-client": "mkdir -p dist; babel lib/browser.js --out-file dist/browser.js",
        "prepublish": "npm run-script build-client",
        "test": "lab -a code -t 100 -L",
        "test-cov-html": "lab -a code -r html -o coverage.html"
    },
    "version": "6.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
