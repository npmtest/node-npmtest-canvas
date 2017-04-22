# npmtest-canvas

#### basic test coverage for  [canvas (v1.6.5)](https://github.com/Automattic/node-canvas)  [![npm package](https://img.shields.io/npm/v/npmtest-canvas.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-canvas) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-canvas.svg)](https://travis-ci.org/npmtest/node-npmtest-canvas)

#### Canvas graphics API backed by Cairo

[![NPM](https://nodei.co/npm/canvas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/canvas)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-canvas/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-canvas/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-canvas/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-canvas/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-canvas/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-canvas/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-canvas/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-canvas/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-canvas/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-canvas/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-canvas/build/test-report.html](https://npmtest.github.io/node-npmtest-canvas/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-canvas/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-canvas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-canvas/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-canvas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-canvas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "canvas",
    "description": "Canvas graphics API backed by Cairo",
    "version": "1.6.5",
    "author": "TJ Holowaychuk <tj@learnboost.com>",
    "contributors": [
        "Nathan Rajlich <nathan@tootallnate.net>",
        "Rod Vagg <r@va.gg>",
        "Juriy Zaytsev <kangax@gmail.com>"
    ],
    "keywords": [
        "canvas",
        "graphic",
        "graphics",
        "pixman",
        "cairo",
        "image",
        "images",
        "pdf"
    ],
    "homepage": "https://github.com/Automattic/node-canvas",
    "repository": "git://github.com/Automattic/node-canvas.git",
    "scripts": {
        "prebenchmark": "node-gyp build",
        "benchmark": "node benchmarks/run.js",
        "pretest": "node-gyp build",
        "test": "standard examples/*.js && mocha test/*.test.js",
        "pretest-server": "node-gyp build",
        "test-server": "node test/server.js"
    },
    "dependencies": {
        "nan": "^2.4.0",
        "parse-css-font": "^2.0.2",
        "units-css": "^0.4.0"
    },
    "devDependencies": {
        "body-parser": "^1.13.3",
        "express": "^4.13.2",
        "pug": "^2.0.0-beta3",
        "mocha": "*",
        "standard": "^7.1.1"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "main": "./lib/canvas.js",
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
