# npmtest-gulp-sprite

#### basic test coverage for  [gulp-sprite (v0.0.4)](https://github.com/aslansky/gulp-sprite)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-sprite.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-sprite) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-sprite.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-sprite)

#### gulp task for creating image sprites and the corresponding stylesheets

[![NPM](https://nodei.co/npm/gulp-sprite.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-sprite)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-sprite/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-sprite/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-sprite/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-sprite/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-sprite/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-sprite/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-sprite/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-sprite/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-sprite/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-sprite/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-sprite/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-sprite/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-sprite/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-sprite/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-sprite/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-sprite/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-sprite/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-sprite/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-sprite/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-sprite",
    "version": "0.0.4",
    "description": "gulp task for creating image sprites and the corresponding stylesheets",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "https://github.com/aslansky/gulp-sprite.git"
    },
    "homepage": "https://github.com/aslansky/gulp-sprite",
    "bugs": {
        "url": "https://github.com/aslansky/gulp-sprite/issues"
    },
    "author": {
        "name": "Alexander Slansky",
        "url": "http://slansky.net"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "mocha"
    },
    "main": "./index.js",
    "files": [
        "index.js"
    ],
    "keywords": [
        "gulpplugin",
        "sprites",
        "coordinates",
        "css",
        "scss",
        "less",
        "sass"
    ],
    "dependencies": {
        "gulp-util": "~2.2.0",
        "through": "~2.3.4",
        "canvas": "~1.1.1",
        "json2css": "~4.2.1",
        "lodash": "~2.4.1"
    },
    "devDependencies": {
        "mocha": "*"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
