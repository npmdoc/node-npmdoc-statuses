# npmdoc-statuses

#### api documentation for  [statuses (v1.3.1)](https://github.com/jshttp/statuses)  [![npm package](https://img.shields.io/npm/v/npmdoc-statuses.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-statuses) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-statuses.svg)](https://travis-ci.org/npmdoc/node-npmdoc-statuses)

#### HTTP status utility

[![NPM](https://nodei.co/npm/statuses.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/statuses)

- [https://npmdoc.github.io/node-npmdoc-statuses/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-statuses/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-statuses/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-statuses/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-statuses/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-statuses/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/statuses/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {},
    "description": "HTTP status utility",
    "devDependencies": {
        "csv-parse": "1.1.7",
        "eslint": "3.10.0",
        "eslint-config-standard": "6.2.1",
        "eslint-plugin-promise": "3.3.2",
        "eslint-plugin-standard": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "1.21.5",
        "stream-to-array": "2.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "faf51b9eb74aaef3b3acf4ad5f61abf24cb7b93e",
        "tarball": "https://registry.npmjs.org/statuses/-/statuses-1.3.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "HISTORY.md",
        "index.js",
        "codes.json",
        "LICENSE"
    ],
    "gitHead": "28a619be77f5b4741e6578a5764c5b06ec6d4aea",
    "homepage": "https://github.com/jshttp/statuses",
    "keywords": [
        "http",
        "status",
        "code"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jongleberry"
        },
        {
            "name": "mscdex"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "statuses",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/statuses.git"
    },
    "scripts": {
        "build": "node scripts/build.js",
        "fetch": "node scripts/fetch.js",
        "lint": "eslint .",
        "test": "mocha --reporter spec --check-leaks --bail test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "update": "npm run fetch && npm run build"
    },
    "version": "1.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
