# npmtest-gulp-bless

#### basic test coverage for  [gulp-bless (v3.2.1)](http://github.com/BlessCSS/gulp-bless)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-bless.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-bless) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-bless.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-bless)

#### CSS post-processor which splits CSS files suitably for Internet Explorer < 10. Bless + Gulp = gulp-bless.

[![NPM](https://nodei.co/npm/gulp-bless.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-bless)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-bless/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-bless/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-bless/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-bless/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-bless/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-bless/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-bless/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-bless/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-bless/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-bless/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-bless/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-bless/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-bless/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-bless/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-bless/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-bless/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-bless/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-bless/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-bless/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-bless/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-bless/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Lynch"
    },
    "bugs": {
        "url": "http://github.com/BlessCSS/gulp-bless/issues"
    },
    "dependencies": {
        "bless": "^4.0.0",
        "gulp-util": "*",
        "lodash.isfunction": "^3.0.8",
        "lodash.isstring": "^4.0.1",
        "lodash.isundefined": "^3.0.1",
        "merge": "~1.2.0",
        "through2": "~0.5.1",
        "vinyl-sourcemaps-apply": "^0.2.1"
    },
    "description": "CSS post-processor which splits CSS files suitably for Internet Explorer < 10. Bless + Gulp = gulp-bless.",
    "devDependencies": {
        "gulp": "*",
        "gulp-clean-css": "^2.3.2",
        "gulp-concat": "^2.6.1",
        "gulp-coverage": "~0.1.24",
        "gulp-each": "^0.2.0",
        "gulp-load-plugins": "^1.2.0",
        "gulp-mocha": "*",
        "gulp-rename": "^1.2.2",
        "gulp-sourcemaps": "^1.6.0",
        "proxyquire": "~1.0.1",
        "should": "*",
        "stream-assert": "^2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "c779e164ef9e196ee7f4732321139d4e805778d6",
        "tarball": "https://registry.npmjs.org/gulp-bless/-/gulp-bless-3.2.1.tgz"
    },
    "engines": {
        "node": ">=0.9"
    },
    "gitHead": "5a20168c6e35c75f05928f09eceb2d82de2e91b3",
    "homepage": "http://github.com/BlessCSS/gulp-bless",
    "keywords": [
        "gulpplugin",
        "css",
        "postprocessor",
        "preprocessor",
        "split",
        "internet explorer",
        "bless"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "adam-lynch"
        },
        {
            "name": "alvinlin123"
        }
    ],
    "name": "gulp-bless",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/BlessCSS/gulp-bless.git"
    },
    "scripts": {
        "test": "gulp test"
    },
    "version": "3.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
