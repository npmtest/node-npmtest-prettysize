# npmtest-prettysize

#### basic test coverage for  prettysize (v0.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-prettysize.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prettysize) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prettysize.svg)](https://travis-ci.org/npmtest/node-npmtest-prettysize)

#### Convert bytes to other sizes for prettier logging

[![NPM](https://nodei.co/npm/prettysize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prettysize)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prettysize/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prettysize/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prettysize/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prettysize/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prettysize/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prettysize/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prettysize/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prettysize/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prettysize/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prettysize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prettysize/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prettysize/build/test-report.html](https://npmtest.github.io/node-npmtest-prettysize/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prettysize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prettysize/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prettysize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prettysize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prettysize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prettysize/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prettysize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prettysize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "prettysize",
    "description": "Convert bytes to other sizes for prettier logging",
    "version": "0.1.0",
    "main": "./index.js",
    "devDependencies": {
        "vows": "*",
        "yui-lint": "~0.1.1",
        "jshint": "~0.9.0",
        "istanbul": "~0.1.8"
    },
    "keywords": [
        "size",
        "bytes",
        "MB",
        "megs"
    ],
    "scripts": {
        "pretest": "jshint --config ./node_modules/yui-lint/jshint.json ./index.js",
        "test": "istanbul cover --print both vows -- --spec ./tests/*.js"
    },
    "bugs": {
        "url": "http://github.com/davglass/prettysize/issues"
    },
    "licenses": [
        {
            "type": "BSD",
            "url": "https://github.com/davglass/prettysize/blob/master/LICENSE"
        }
    ],
    "repository": {
        "type": "git",
        "url": "http://github.com/davglass/prettysize.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
