# npmdoc-kbpgp

#### api documentation for  [kbpgp (v2.0.69)](http://github.com/keybase/kbpgp)  [![npm package](https://img.shields.io/npm/v/npmdoc-kbpgp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-kbpgp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-kbpgp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-kbpgp)

#### Keybase's PGP Implementation

[![NPM](https://nodei.co/npm/kbpgp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/kbpgp)

- [https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-kbpgp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-kbpgp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-kbpgp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-kbpgp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "kbpgp",
    "description": "Keybase's PGP Implementation",
    "keywords": [
        "crypto",
        "pgp",
        "keybase"
    ],
    "author": "Maxwell Krohn",
    "version": "2.0.69",
    "license": "BSD-3-Clause",
    "main": "./lib/main.js",
    "directories": {
        "lib": "lib/"
    },
    "homepage": "http://github.com/keybase/kbpgp",
    "bugs": "https://github.com/keybase/kbpgp/issues",
    "repository": {
        "type": "git",
        "url": "git://github.com/keybase/kbpgp.git"
    },
    "dependencies": {
        "bn": "^1.0.0",
        "bzip-deflate": "^1.0.0",
        "deep-equal": ">=0.2.1",
        "iced-error": ">=0.0.10",
        "iced-lock": "^1.0.2",
        "iced-runtime": "^1.0.3",
        "keybase-ecurve": "^1.0.0",
        "keybase-nacl": "^1.0.0",
        "minimist": "^1.2.0",
        "pgp-utils": ">=0.0.32",
        "purepack": ">=1.0.4",
        "triplesec": ">=3.0.19",
        "tweetnacl": "^0.13.1"
    },
    "devDependencies": {
        "browserify": "^5.9.1",
        "colors": "0.6.2",
        "iced-coffee-script": "108.0.11",
        "iced-test": ">=0.0.21",
        "icsify": "^0.7.0",
        "minimist": "0.0.8",
        "optimist": "0.6.1",
        "uglify-js": "^2.4.13"
    },
    "scripts": {
        "test": "make test"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
