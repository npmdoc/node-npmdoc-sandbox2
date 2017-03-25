# api documentation for  [sandbox2 (v0.0.34)](https://github.com/kaizhu256/node-sandbox2/blob/alpha/README.md)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sandbox2.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sandbox2)
#### api-documentation for [mysql (v2.13.0)](https://github.com/mysqljs/mysql#readme)

[![NPM](https://nodei.co/npm/sandbox2.png?downloads=true)](https://www.npmjs.com/package/sandbox2)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sandbox2_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sandbox2/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-sandbox2/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "kai zhu",
        "email": "kaizhu256@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/kaizhu256/node-sandbox2/issues"
    },
    "buildNpmdoc": "mysql",
    "dependencies": {},
    "description": "api-documentation for [mysql (v2.13.0)](https://github.com/mysqljs/mysql#readme)",
    "devDependencies": {
        "electron-lite": "github:kaizhu256/node-electron-lite#alpha",
        "mysql": "*",
        "utility2": "github:kaizhu256/node-utility2#alpha"
    },
    "directories": {},
    "dist": {
        "shasum": "5d64c9d550cb56993999b6c250c8e03f4a76f376",
        "tarball": "https://registry.npmjs.org/sandbox2/-/sandbox2-0.0.34.tgz"
    },
    "engines": {
        "node": ">=4.0"
    },
    "homepage": "https://github.com/kaizhu256/node-sandbox2/blob/alpha/README.md",
    "keywords": [
        "documentation",
        "mysql"
    ],
    "license": "MIT",
    "main": "lib.sandbox2.js",
    "maintainers": [
        {
            "name": "kaizhu",
            "email": "kaizhu256@gmail.com"
        }
    ],
    "name": "sandbox2",
    "nameAlias": "sandbox2",
    "nameAliasDeprecate": "sandbox3",
    "nameAliasPublish": "sandbox3",
    "nameOriginal": "sandbox2",
    "optionalDependencies": {},
    "os": [
        "darwin",
        "linux"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kaizhu256/node-sandbox2.git"
    },
    "scripts": {
        "build-ci": "utility2 shBuildCi",
        "env": "env",
        "heroku-postbuild": "(set -e; npm install 'kaizhu256/node-utility2#alpha'; utility2 shDeployHeroku)",
        "postinstall": "if [ -f lib.sandbox2.npm_scripts.sh ]; then ./lib.sandbox2.npm_scripts.sh postinstall; fi",
        "start": "(set -e; export PORT=${PORT:-8080}; utility2 start test.js)",
        "test": "(set -e; export PORT=47220; utility2 test test.js)"
    },
    "version": "0.0.34"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sandbox2](#apidoc.module.sandbox2)
1.  object <span class="apidocSignatureSpan"></span>sandbox2
1.  object <span class="apidocSignatureSpan">sandbox2.</span>local
1.  string <span class="apidocSignatureSpan">sandbox2.</span>__dirname
1.  string <span class="apidocSignatureSpan">sandbox2.</span>modeJs



# <a name="apidoc.module.sandbox2"></a>[module sandbox2](#apidoc.module.sandbox2)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
