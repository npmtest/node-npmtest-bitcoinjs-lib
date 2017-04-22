# npmtest-bitcoinjs-lib

#### basic test coverage for  [bitcoinjs-lib (v3.0.2)](https://github.com/bitcoinjs/bitcoinjs-lib#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bitcoinjs-lib.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bitcoinjs-lib) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bitcoinjs-lib.svg)](https://travis-ci.org/npmtest/node-npmtest-bitcoinjs-lib)

#### Client-side Bitcoin JavaScript library

[![NPM](https://nodei.co/npm/bitcoinjs-lib.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bitcoinjs-lib)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bitcoinjs-lib/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bitcoinjs-lib/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/test-report.html](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bitcoinjs-lib/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bitcoinjs-lib/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bitcoinjs-lib/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bitcoinjs-lib/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bitcoinjs-lib/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/bitcoinjs/bitcoinjs-lib/issues"
    },
    "contributors": [
        {
            "name": "Daniel Cousens",
            "url": "http://dcousens.com"
        },
        {
            "name": "Kyle Drake",
            "url": "http://kyledrake.net/"
        },
        {
            "name": "Wei Lu",
            "url": "http://weilu.github.io/"
        },
        {
            "name": "Stefan Thomas",
            "url": "http://www.justmoon.net"
        }
    ],
    "dependencies": {
        "bigi": "^1.4.0",
        "bip66": "^1.1.0",
        "bitcoin-ops": "^1.3.0",
        "bs58check": "^2.0.0",
        "create-hash": "^1.1.0",
        "create-hmac": "^1.1.3",
        "ecurve": "^1.0.0",
        "merkle-lib": "^2.0.10",
        "pushdata-bitcoin": "^1.0.1",
        "randombytes": "^2.0.1",
        "typeforce": "^1.8.7",
        "varuint-bitcoin": "^1.0.4",
        "wif": "^2.0.1"
    },
    "description": "Client-side Bitcoin JavaScript library",
    "devDependencies": {
        "async": "^2.0.1",
        "bip39": "^2.3.0",
        "bs58": "^4.0.0",
        "cb-http-client": "^0.2.0",
        "coinselect": "^3.1.1",
        "minimaldata": "^1.0.2",
        "mocha": "^3.1.0",
        "nyc": "^10.2.0",
        "proxyquire": "^1.4.0",
        "sinon": "^1.12.2",
        "standard": "^9.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "89e91a64784efd2cfd59ccf75c657c3c85103d99",
        "tarball": "https://registry.npmjs.org/bitcoinjs-lib/-/bitcoinjs-lib-3.0.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "src"
    ],
    "gitHead": "5305d9b9b8c95de82af84152702f86746f90f6ef",
    "homepage": "https://github.com/bitcoinjs/bitcoinjs-lib#readme",
    "keywords": [
        "bitcoin",
        "browser",
        "client",
        "library"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "dcousens"
        }
    ],
    "name": "bitcoinjs-lib",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bitcoinjs/bitcoinjs-lib.git"
    },
    "scripts": {
        "coverage": "nyc --check-coverage --branches 90 --functions 90 mocha",
        "coverage-html": "nyc report --reporter=html",
        "coverage-report": "nyc report --reporter=lcov",
        "integration": "mocha test/integration/",
        "standard": "standard",
        "test": "npm run standard && npm run coverage",
        "unit": "mocha"
    },
    "version": "3.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
