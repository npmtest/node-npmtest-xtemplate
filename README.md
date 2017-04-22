# npmtest-xtemplate

#### basic test coverage for  [xtemplate (v4.6.0)](https://github.com/xtemplate/xtemplate#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-xtemplate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xtemplate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xtemplate.svg)](https://travis-ci.org/npmtest/node-npmtest-xtemplate)

#### High Speed, eXtensible Template Engine lib on browser and nodejs

[![NPM](https://nodei.co/npm/xtemplate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xtemplate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xtemplate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xtemplate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xtemplate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xtemplate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xtemplate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xtemplate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xtemplate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xtemplate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xtemplate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xtemplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xtemplate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xtemplate/build/test-report.html](https://npmtest.github.io/node-npmtest-xtemplate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xtemplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xtemplate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xtemplate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xtemplate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xtemplate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xtemplate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xtemplate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xtemplate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "yiminghe"
    },
    "bugs": {
        "url": "https://github.com/xtemplate/xtemplate/issues"
    },
    "config": {
        "port": 8002
    },
    "dependencies": {
        "escape-html": "~1.0.3"
    },
    "description": "High Speed, eXtensible Template Engine lib on browser and nodejs",
    "devDependencies": {
        "expect.js": "^0.3.1",
        "gulp": "^3.8.7",
        "gulp-xtemplate": "^1.2.2",
        "highlight.js": "~8.9.1",
        "jquery": "~1.11.3",
        "js-beautify": "~1.5.10",
        "kison": "^0.3.3",
        "koa": "~1.1.2",
        "koa-router": "~5.3.0",
        "modulex": "^1.7.4",
        "modulex-promise": "^1.1.3",
        "modulex-util": "^1.1.5",
        "pre-commit": "1.x",
        "rc-tools": "5.x",
        "react": "15.x",
        "react-dom": "15.x",
        "uuid": "~2.0.1",
        "webpack": "~1.12.9",
        "xtpl": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ba13a44bfca2161d35dbb06873b36f7795c9f5cf",
        "tarball": "https://registry.npmjs.org/xtemplate/-/xtemplate-4.6.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "files": [
        "lib",
        "dist"
    ],
    "gitHead": "149b02bb73f8def23810472461168c078ce58ddd",
    "homepage": "https://github.com/xtemplate/xtemplate#readme",
    "keywords": [
        "template",
        "template engine",
        "browser",
        "nodejs"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "dead_horse"
        },
        {
            "name": "taojie"
        },
        {
            "name": "yiminghe"
        }
    ],
    "name": "xtemplate",
    "optionalDependencies": {},
    "pre-commit": [
        "lint"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/xtemplate/xtemplate.git"
    },
    "scripts": {
        "build": "rc-tools run build",
        "chrome-test": "rc-tools run chrome-test",
        "coverage": "rc-tools run coverage",
        "gh-pages": "rc-tools run gh-pages",
        "karma": "rc-tools run karma",
        "lint": "rc-tools run lint",
        "pub": "rm -rf dist && webpack --config scripts/webpack.runtime.config.js && webpack --config scripts/webpack.xtemplate.config.js && rc-tools run pub",
        "saucelabs": "rc-tools run saucelabs",
        "start": "rc-tools run server",
        "test": "rc-tools run test",
        "watch": "rc-tools run watch"
    },
    "version": "4.6.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
