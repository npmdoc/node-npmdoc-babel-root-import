# npmdoc-babel-root-import

#### basic api documentation for  [babel-root-import (v4.1.8)](https://github.com/entwicklerstube/babel-root-import#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-root-import.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-root-import) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-root-import.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-root-import)

#### Babel Plugin to enable relative root-import

[![NPM](https://nodei.co/npm/babel-root-import.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-root-import)

- [https://npmdoc.github.io/node-npmdoc-babel-root-import/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-root-import/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-root-import/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-root-import/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-root-import/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-root-import/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael J. Zoidl"
    },
    "bugs": {
        "url": "https://github.com/entwicklerstube/babel-root-import/issues"
    },
    "dependencies": {
        "slash": "^1.0.0"
    },
    "description": "Babel Plugin to enable relative root-import",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-core": "^6.2.1",
        "babel-eslint": "^5.0.0",
        "babel-preset-es2015": "^6.1.18",
        "babel-preset-stage-1": "^6.1.18",
        "chai": "^3.2.0",
        "eslint": "~2.1.0",
        "mocha": "^2.2.5",
        "sinon": "^1.15.4"
    },
    "directories": {},
    "dist": {
        "shasum": "135bb83986d57d6f75ba9b7772b31633e22fbdac",
        "tarball": "https://registry.npmjs.org/babel-root-import/-/babel-root-import-4.1.8.tgz"
    },
    "files": [
        "index.js",
        "build"
    ],
    "gitHead": "c2cbd540eb227faf73c124dcc3ca3e9b9a5b920c",
    "homepage": "https://github.com/entwicklerstube/babel-root-import#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "michaelzoidl"
        }
    ],
    "name": "babel-root-import",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/entwicklerstube/babel-root-import.git"
    },
    "scripts": {
        "compile": "babel -d build/ plugin/",
        "lint-js": "eslint plugin",
        "test": "mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register",
        "test-watch": "mocha test/*.spec.js --require config/mocha.js --compilers js:babel-core/register --watch"
    },
    "version": "4.1.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
