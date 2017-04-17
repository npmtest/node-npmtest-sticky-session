# test coverage for  sticky-session (v1.1.2)  [![npm package](https://img.shields.io/npm/v/npmtest-sticky-session.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sticky-session) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sticky-session.svg)](https://travis-ci.org/npmtest/node-npmtest-sticky-session)
#### Sticky session balancer based on a `cluster` module

[![NPM](https://nodei.co/npm/sticky-session.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sticky-session)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sticky-session/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sticky-session/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sticky-session/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sticky-session/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sticky-session/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sticky-session/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sticky-session/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sticky-session/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sticky-session/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sticky-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sticky-session/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sticky-session/build/test-report.html](https://npmtest.github.io/node-npmtest-sticky-session/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sticky-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sticky-session/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sticky-session/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sticky-session/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sticky-session/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sticky-session/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sticky-session/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sticky-session/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fedor Indutny"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "ip": "^1.0.0"
    },
    "description": "Sticky session balancer based on a 'cluster' module",
    "devDependencies": {
        "jscs": "^2.1.1",
        "jshint": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "716ce738452bbe9eedec506311895a3d64803de1",
        "tarball": "https://registry.npmjs.org/sticky-session/-/sticky-session-1.1.2.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "gitHead": "e0de9b7786255bf5d4c23f9714699b8d12e9882a",
    "license": "MIT",
    "main": "./lib/sticky-session",
    "maintainers": [
        {
            "name": "fedor.indutny"
        },
        {
            "name": "indutny"
        },
        {
            "name": "tlhunter"
        }
    ],
    "name": "sticky-session",
    "optionalDependencies": {},
    "scripts": {
        "lint": "jscs lib/*.js lib/**/*.js && jshint lib/*.js lib/**/*.js",
        "test": "npm run lint && (echo test/*-test.js | xargs node)"
    },
    "version": "1.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
