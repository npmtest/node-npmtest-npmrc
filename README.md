# npmtest-npmrc

#### basic test coverage for  npmrc (v1.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-npmrc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npmrc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npmrc.svg)](https://travis-ci.org/npmtest/node-npmtest-npmrc)

#### Switch between different .npmrc files with ease and grace

[![NPM](https://nodei.co/npm/npmrc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npmrc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npmrc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmrc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npmrc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npmrc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npmrc/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npmrc/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npmrc/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npmrc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npmrc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npmrc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npmrc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npmrc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npmrc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npmrc/build/test-report.html](https://npmtest.github.io/node-npmtest-npmrc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npmrc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npmrc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npmrc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npmrc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npmrc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npmrc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npmrc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npmrc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npmrc",
    "version": "1.1.1",
    "description": "Switch between different .npmrc files with ease and grace",
    "preferGlobal": true,
    "bin": {
        "npmrc": "./npmrc.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/deoxxa/npmrc.git"
    },
    "keywords": [
        "npmrc",
        "utility",
        "shell",
        "npm"
    ],
    "author": "Conrad Pankoff <deoxxa@fknsrs.biz> (http://www.fknsrs.biz/)",
    "license": "BSD",
    "devDependencies": {
        "rimraf": "*",
        "mkdirp": "*",
        "tape": "*",
        "xtend": "*"
    },
    "scripts": {
        "test": "tape test.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
