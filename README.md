# npmtest-excel4node

#### test coverage for  [excel4node (v1.2.1)](https://github.com/natergj/excel4node#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-excel4node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-excel4node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-excel4node.svg)](https://travis-ci.org/npmtest/node-npmtest-excel4node)

#### Library to create Formatted Excel Files.

[![NPM](https://nodei.co/npm/excel4node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/excel4node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-excel4node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel4node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-excel4node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-excel4node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-excel4node/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-excel4node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-excel4node/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-excel4node/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-excel4node/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-excel4node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-excel4node/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-excel4node/build/test-report.html](https://npmtest.github.io/node-npmtest-excel4node/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-excel4node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-excel4node/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-excel4node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-excel4node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-excel4node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-excel4node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-excel4node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-excel4node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nater"
    },
    "bugs": {
        "url": "https://github.com/natergj/excel4node/labels/bug"
    },
    "dependencies": {
        "babel-register": "^6.9.0",
        "colors": "^1.1.2",
        "image-size": "0.5.0",
        "jszip": "^3.0.0",
        "lodash": "4.13.1",
        "mime": "^1.3.4",
        "sloth-logger": "^1.0.3",
        "xmlbuilder": "8.2.2"
    },
    "description": "Library to create Formatted Excel Files.",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-polyfill": "^6.9.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-es2015-node4": "^2.1.0",
        "jsdoc-babel": "^0.2.1",
        "source-map-support": "^0.4.1",
        "tape": "^4.6.0",
        "tape-promise": "^1.1.0",
        "xmldom": "^0.1.22",
        "xpath.js": "^1.0.6"
    },
    "directories": {},
    "dist": {
        "shasum": "94ee13a004e9af2191d2cf0fae76d3dbf5ff3e5e",
        "tarball": "https://registry.npmjs.org/excel4node/-/excel4node-1.2.1.tgz"
    },
    "engines": {
        "node": ">4.0.0"
    },
    "gitHead": "03e65713f036a6e47775f2e56a9bf99219a7e27a",
    "homepage": "https://github.com/natergj/excel4node#readme",
    "keywords": [
        "excel",
        "spreadsheet",
        "xlsx",
        "formatted",
        "styled",
        "report",
        "workbook",
        "ooxml"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://opensource.org/licenses/mit-license.php"
        }
    ],
    "main": "./distribution/index.js",
    "maintainers": [
        {
            "name": "amekkawi"
        },
        {
            "name": "natergj"
        }
    ],
    "name": "excel4node",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/natergj/excel4node.git"
    },
    "scripts": {
        "build": "./node_modules/babel-cli/bin/babel.js source --presets babel-preset-es2015 -s --out-dir distribution",
        "document": "jsdoc ./source -r -d docs",
        "prepublish": "npm run build; npm run test",
        "test": "NODE_ENV=test ./node_modules/tape/bin/tape -r babel-register ./tests/*.test.js",
        "watch": "./node_modules/babel-cli/bin/babel.js source -w --presets babel-preset-es2015 -s --out-dir distribution"
    },
    "version": "1.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
