# npmdoc-querystring

#### api documentation for  [querystring (v0.2.0)](https://github.com/Gozala/querystring#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-querystring.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-querystring) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-querystring.svg)](https://travis-ci.org/npmdoc/node-npmdoc-querystring)

#### Node's querystring module for all engines.

[![NPM](https://nodei.co/npm/querystring.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/querystring)

- [https://npmdoc.github.io/node-npmdoc-querystring/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-querystring/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-querystring/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-querystring/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-querystring/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-querystring/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Irakli Gozalishvili"
    },
    "bugs": {
        "url": "http://github.com/Gozala/querystring/issues/"
    },
    "dependencies": {},
    "description": "Node's querystring module for all engines.",
    "devDependencies": {
        "phantomify": "~0.x.0",
        "retape": "~0.x.0",
        "tape": "~0.1.5",
        "test": "~0.x.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b209849203bb25df820da756e747005878521620",
        "tarball": "https://registry.npmjs.org/querystring/-/querystring-0.2.0.tgz"
    },
    "engines": {
        "node": ">=0.4.x"
    },
    "homepage": "https://github.com/Gozala/querystring#readme",
    "id": "querystring",
    "keywords": [
        "commonjs",
        "query",
        "querystring"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/Gozala/enchain/License.md"
        }
    ],
    "maintainers": [
        {
            "name": "gozala"
        }
    ],
    "name": "querystring",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Gozala/querystring.git",
        "web": "https://github.com/Gozala/querystring"
    },
    "scripts": {
        "test": "npm run test-node && npm run test-browser && npm run test-tap",
        "test-browser": "node ./node_modules/phantomify/bin/cmd.js ./test/common-index.js",
        "test-node": "node ./test/common-index.js",
        "test-tap": "node ./test/tap-index.js"
    },
    "testling": {
        "files": "test/tap-index.js",
        "browsers": {
            "iexplore": [
                9,
                10
            ],
            "chrome": [
                16,
                20,
                25,
                "canary"
            ],
            "firefox": [
                10,
                15,
                16,
                17,
                18,
                "nightly"
            ],
            "safari": [
                5,
                6
            ],
            "opera": [
                12
            ]
        }
    },
    "version": "0.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
