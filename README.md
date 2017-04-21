# npmdoc-foundation-cli

#### api documentation for  [foundation-cli (v2.2.1)](http://foundation.zurb.com)  [![npm package](https://img.shields.io/npm/v/npmdoc-foundation-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-foundation-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-foundation-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-foundation-cli)

#### Command-line interface for the Foundation family of frameworks.

[![NPM](https://nodei.co/npm/foundation-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/foundation-cli)

- [https://npmdoc.github.io/node-npmdoc-foundation-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-foundation-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-foundation-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-foundation-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-foundation-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-foundation-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "foundation-cli",
    "version": "2.2.1",
    "description": "Command-line interface for the Foundation family of frameworks.",
    "keywords": [
        "foundation",
        "cli",
        "scaffold"
    ],
    "author": "ZURB <foundation@zurb.com> (http://zurb.com)",
    "main": "lib/index.js",
    "bin": {
        "foundation": "./bin/foundation.js"
    },
    "dependencies": {
        "async": "^2.3.0",
        "bower": "^1.6.8",
        "colors": "^1.0.3",
        "inquirer": "^0.8.3",
        "is-root": "^1.0.0",
        "js-yaml": "^3.8.2",
        "lodash": "^4.17.4",
        "multiline": "^1.0.2",
        "nopt": "^3.0.1",
        "npm": "^2.1.12",
        "paint-by-number": "1.0.0",
        "rimraf": "^2.2.8",
        "semver": "^4.3.0",
        "string-length": "^1.0.0",
        "update-notifier": "^0.2.2",
        "which": "^1.0.8"
    },
    "homepage": "http://foundation.zurb.com",
    "repository": {
        "type": "git",
        "url": "https://github.com/zurb/foundation-cli"
    },
    "bugs": {
        "url": "https://github.com/zurb/foundation-cli/issues"
    },
    "scripts": {
        "test": "node bin/foundation.js new"
    },
    "preferGlobal": true,
    "engines": {
        "node": ">=0.10.33"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
