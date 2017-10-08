# npmdoc-sandbox2

#### basic api documentation for  [sandbox2 (v2017.9.16)](https://github.com/kaizhu256/node-utility2)  [![npm package](https://img.shields.io/npm/v/npmdoc-sandbox2.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sandbox2) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sandbox2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sandbox2)

#### the zero-dependency, swiss-army-knife utility for building, testing, and deploying webapps

[![NPM](https://nodei.co/npm/sandbox2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sandbox2)

- [https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sandbox2/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "kai zhu"
    },
    "bin": {
        "utility2": "lib.utility2.sh",
        "utility2-apidoc": "lib.apidoc.js",
        "utility2-db": "lib.db.js",
        "utility2-github-crud": "lib.github_crud.js",
        "utility2-istanbul": "lib.istanbul.js",
        "utility2-jslint": "lib.jslint.js",
        "utility2-uglifyjs": "lib.uglifyjs.js"
    },
    "bugs": {
        "url": "https://github.com/kaizhu256/node-utility2/issues"
    },
    "dependencies": {},
    "description": "the zero-dependency, swiss-army-knife utility for building, testing, and deploying webapps",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-6RZBX0IIQNJ+VZiwQbjd22VJIOV+ChhSgY1LHb98iGbI2g9kjLAxys8V9pK3h/EY+2KI8yJf6eGKM04nPr7g5A==",
        "shasum": "a75aa0062c536c4262e3bc09ffc332cb2e387a80",
        "tarball": "https://registry.npmjs.org/sandbox2/-/sandbox2-2017.9.16.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "homepage": "https://github.com/kaizhu256/node-utility2",
    "keywords": [
        "continuous-integration",
        "istanbul",
        "jslint",
        "npmdoc",
        "npmtest",
        "test",
        "test-coverage",
        "travis-ci"
    ],
    "license": "MIT",
    "main": "lib.utility2.js",
    "maintainers": [
        {
            "name": "kaizhu"
        }
    ],
    "name": "sandbox2",
    "nameAlias": "utility2",
    "nameAliasPublish": "npmtest-lite npmtest4 test-lite",
    "nameOriginal": "utility2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kaizhu256/node-utility2.git"
    },
    "scripts": {
        "build-ci": "./lib.utility2.sh shReadmeTest build_ci.sh",
        "env": "env",
        "heroku-postbuild": "./lib.utility2.sh shDeployHeroku",
        "postinstall": "[ ! -f npm_scripts.sh ] || ./npm_scripts.sh postinstall",
        "start": "set -e; export PORT=${PORT:-8080}; if [ -f assets.app.js ]; then node assets.app.js; else npm_config_mode_auto_restart=1 ./lib.utility2.sh shRun shIstanbulCover test.js; fi",
        "test": "PORT=$(./lib.utility2.sh shServerPortRandom) PORT_REPL=$(./lib.utility2.sh shServerPortRandom) npm_config_mode_auto_restart=1 npm_config_timeout_default=60000 ./lib.utility2.sh test test.js"
    },
    "version": "2017.9.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
