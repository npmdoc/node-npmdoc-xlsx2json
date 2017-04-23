# npmdoc-xlsx2json

#### api documentation for  [xlsx2json (v1.0.0)](https://github.com/daikiueda/xlsx2json)  [![npm package](https://img.shields.io/npm/v/npmdoc-xlsx2json.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-xlsx2json) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-xlsx2json.svg)](https://travis-ci.org/npmdoc/node-npmdoc-xlsx2json)

#### Convert xlsx to JSON.

[![NPM](https://nodei.co/npm/xlsx2json.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xlsx2json)

- [https://npmdoc.github.io/node-npmdoc-xlsx2json/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xlsx2json/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xlsx2json/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xlsx2json/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-xlsx2json/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-xlsx2json/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "daikiueda"
    },
    "bugs": {
        "url": "https://github.com/daikiueda/xlsx2json/issues"
    },
    "dependencies": {
        "csv-parse": "^1.1.7",
        "memoizee": "^0.4.1",
        "xlsx": "^0.8.0"
    },
    "description": "Convert xlsx to JSON.",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "intelli-espower-loader": "^1.0.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "power-assert": "^1.4.2",
        "rewire": "^2.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "484bf860e36751a5b0ab0e0aaad239e268174a6d",
        "tarball": "https://registry.npmjs.org/xlsx2json/-/xlsx2json-1.0.0.tgz"
    },
    "engines": {
        "node": ">=6.9.1"
    },
    "gitHead": "6d3a221a766c4ccb00ffc80036751e223b998e20",
    "homepage": "https://github.com/daikiueda/xlsx2json",
    "keywords": [
        "excel",
        "xlsx",
        "json"
    ],
    "license": "MIT",
    "main": "lib/xlsx2json.js",
    "maintainers": [
        {
            "name": "daikiueda"
        }
    ],
    "name": "xlsx2json",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/daikiueda/xlsx2json.git"
    },
    "scripts": {
        "test": "node ./node_modules/.bin/mocha test/xlsx2json.test.js",
        "test-cov": "node ./node_modules/istanbul/lib/cli.js cover ./node_modules/mocha/bin/_mocha -- --recursive -R spec"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
