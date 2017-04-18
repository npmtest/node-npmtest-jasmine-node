# npmtest-jasmine-node

#### test coverage for  [jasmine-node (v1.14.5)](https://github.com/mhevery/jasmine-node)  [![npm package](https://img.shields.io/npm/v/npmtest-jasmine-node.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jasmine-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jasmine-node.svg)](https://travis-ci.org/npmtest/node-npmtest-jasmine-node)

#### DOM-less simple JavaScript BDD testing framework for Node

[![NPM](https://nodei.co/npm/jasmine-node.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jasmine-node)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jasmine-node/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jasmine-node/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jasmine-node/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jasmine-node/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jasmine-node/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jasmine-node/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jasmine-node/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jasmine-node/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jasmine-node/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jasmine-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jasmine-node/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jasmine-node/build/test-report.html](https://npmtest.github.io/node-npmtest-jasmine-node/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jasmine-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jasmine-node/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jasmine-node/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jasmine-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jasmine-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Misko Hevery"
    },
    "bin": {
        "jasmine-node": "bin/jasmine-node"
    },
    "bugs": {
        "url": "https://github.com/mhevery/jasmine-node/issues"
    },
    "contributors": [
        {
            "name": "Chris Moultrie"
        }
    ],
    "dependencies": {
        "coffee-script": ">=1.0.1",
        "gaze": "~0.3.2",
        "jasmine-growl-reporter": "~0.0.2",
        "jasmine-reporters": "~1.0.0",
        "mkdirp": "~0.3.5",
        "requirejs": ">=0.27.1",
        "underscore": ">= 1.3.1",
        "walkdir": ">= 0.0.1"
    },
    "description": "DOM-less simple JavaScript BDD testing framework for Node",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "18e8397b856924ee77003666c3731b5aea50c39d",
        "tarball": "https://registry.npmjs.org/jasmine-node/-/jasmine-node-1.14.5.tgz"
    },
    "homepage": "https://github.com/mhevery/jasmine-node",
    "keywords": [
        "testing",
        "bdd"
    ],
    "licenses": [
        "MIT"
    ],
    "main": "lib/jasmine-node",
    "maintainers": [
        {
            "name": "mhevery"
        },
        {
            "name": "tebriel"
        }
    ],
    "name": "jasmine-node",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mhevery/jasmine-node.git"
    },
    "scripts": {
        "test": "node lib/jasmine-node/cli.js spec"
    },
    "version": "1.14.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
