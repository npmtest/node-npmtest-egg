# test coverage for  [egg (v1.1.0)](https://github.com/eggjs/egg)  [![npm package](https://img.shields.io/npm/v/npmtest-egg.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-egg) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-egg.svg)](https://travis-ci.org/npmtest/node-npmtest-egg)
#### A web framework's framework for Node.js

[![NPM](https://nodei.co/npm/egg.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/egg)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-egg/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-egg/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-egg/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-egg/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-egg/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-egg/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-egg/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-egg/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-egg/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-egg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-egg/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-egg/build/test-report.html](https://npmtest.github.io/node-npmtest-egg/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-egg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-egg/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-egg/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-egg/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-egg/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-egg/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-egg/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-egg/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/eggjs/egg/issues"
    },
    "dependencies": {
        "accepts": "^1.3.3",
        "agentkeepalive": "^3.1.0",
        "cluster-client": "^1.5.3",
        "co": "^4.6.0",
        "debug": "^2.6.3",
        "delegates": "^1.0.0",
        "egg-cluster": "^1.6.2",
        "egg-cookies": "^2.2.1",
        "egg-core": "^3.2.0",
        "egg-development": "^1.2.0",
        "egg-i18n": "^1.1.0",
        "egg-jsonp": "^1.0.0",
        "egg-logger": "^1.5.0",
        "egg-logrotator": "^2.2.2",
        "egg-multipart": "^1.2.0",
        "egg-onerror": "^1.3.0",
        "egg-schedule": "^2.3.0",
        "egg-security": "^1.9.0",
        "egg-session": "^2.1.0",
        "egg-static": "^1.3.0",
        "egg-view": "^1.1.0",
        "egg-watcher": "^2.1.0",
        "extend2": "^1.0.0",
        "graceful": "^1.0.1",
        "is-type-of": "^1.0.0",
        "koa-bodyparser": "^2.5.0",
        "koa-is-json": "^1.0.0",
        "mime-types": "^2.1.15",
        "sendmessage": "^1.1.0",
        "urllib": "^2.22.0",
        "utility": "^1.11.0"
    },
    "description": "A web framework's framework for Node.js",
    "devDependencies": {
        "autod": "^2.8.0",
        "autod-egg": "^1.0.0",
        "coffee": "^3.3.0",
        "egg-alinode": "^1.0.3",
        "egg-bin": "^3.2.1",
        "egg-mock": "^3.2.0",
        "egg-plugin-puml": "^2.0.0",
        "egg-view-nunjucks": "^2.0.0",
        "eslint": "^3.19.0",
        "eslint-config-egg": "^3.2.0",
        "formstream": "^1.1.0",
        "gh-pages": "^0.12.0",
        "glob": "^7.1.1",
        "jsdoc": "^3.4.3",
        "merge-descriptors": "^1.0.1",
        "moment": "^2.17.1",
        "mz": "^2.6.0",
        "mz-modules": "^1.0.0",
        "once": "^1.3.3",
        "pedding": "^1.1.0",
        "rds": "^0.1.0",
        "rimraf": "^2.6.1",
        "runscript": "^1.2.1",
        "should": "^11.2.1",
        "spy": "^1.0.0",
        "supertest": "^3.0.0",
        "taffydb": "^2.7.3",
        "webstorm-disable-index": "^1.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "42f00992b8df452a02d53cd37c68f076e79e54a1",
        "tarball": "https://registry.npmjs.org/egg/-/egg-1.1.0.tgz"
    },
    "engines": {
        "node": ">= 6.0.0"
    },
    "files": [
        "app",
        "config",
        "bin",
        "lib",
        "index.js"
    ],
    "gitHead": "39b2d8d868267b9ae9ffb2185235df598d2df9d7",
    "homepage": "https://github.com/eggjs/egg",
    "keywords": [
        "web",
        "app",
        "http",
        "application",
        "framework",
        "middleware",
        "koa",
        "egg"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "atian25"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "eggjs"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "popomore"
        },
        {
            "name": "shaoshuai0102"
        }
    ],
    "name": "egg",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eggjs/egg.git"
    },
    "scripts": {
        "autod": "autod",
        "ci": "npm run lint && npm run cov",
        "commits": "./scripts/commits.sh",
        "cov": "egg-bin cov",
        "doc-build": "./scripts/doc.js build",
        "doc-deploy": "./scripts/doc.js deploy",
        "doc-server": "./scripts/doc.js server",
        "lint": "eslint app config lib test *.js",
        "puml": "puml . --dest ./docs",
        "test": "npm run lint -- --fix && npm run test-local",
        "test-local": "egg-bin test"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
