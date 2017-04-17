# test coverage for  [generator-ng-poly (v0.13.0)](https://github.com/dustinspecker/generator-ng-poly#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-ng-poly.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-ng-poly) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-ng-poly.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-ng-poly)
#### Yeoman generator for modular AngularJS apps with Gulp and optional Polymer support

[![NPM](https://nodei.co/npm/generator-ng-poly.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-ng-poly)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-ng-poly/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-ng-poly/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-ng-poly/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-ng-poly/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-ng-poly/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-ng-poly/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-ng-poly/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-ng-poly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-ng-poly/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-ng-poly/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dustin Specker",
        "url": "https://github.com/dustinspecker"
    },
    "bugs": {
        "url": "https://github.com/dustinspecker/generator-ng-poly/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "dependencies": {
        "babel-polyfill": "^6.1.19",
        "babel-runtime": "^6.1.18",
        "chalk": "^1.0.0",
        "count-spaces": "^1.0.1",
        "find-up": "^1.0.0",
        "func-has-param": "^1.1.1",
        "get-yo-rc-path": "^1.0.1",
        "indent-string": "^2.0.0",
        "lodash": "^4.0.0",
        "mkdirp": "^0.5.0",
        "newline-regex": "^0.2.0",
        "ng-add-dep": "^0.3.0",
        "ng-mod-get-names": "^1.0.0",
        "path-exists": "^3.0.0",
        "pify": "^2.2.0",
        "recursive-readdir": "^2.0.0",
        "remove-trailing-slash": "^0.1.0",
        "underscore.string": "^3.0.1",
        "update-notifier": "^0.7.0",
        "yeoman-generator": "^0.23.1",
        "yosay": "^1.0.0"
    },
    "description": "Yeoman generator for modular AngularJS apps with Gulp and optional Polymer support",
    "devDependencies": {
        "a": "^1.0.1",
        "babel-core": "^6.1.19",
        "babel-eslint": "^6.0.0",
        "babel-plugin-syntax-async-functions": "^6.1.18",
        "babel-plugin-transform-regenerator": "^6.1.18",
        "babel-preset-es2015": "^6.1.18",
        "chai": "^3.2.0",
        "coveralls": "^2.11.1",
        "cz-conventional-changelog": "^1.1.5",
        "del": "^2.0.0",
        "eslint-config-dustinspecker": "^1.0.0",
        "eslint-formatter-pretty": "^0.2.0",
        "eslint-plugin-new-with-error": "^1.1.0",
        "eslint-plugin-no-use-extend-native": "^0.3.1",
        "eslint-plugin-xo": "^0.4.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.0",
        "gulp-eslint": "^2.0.0",
        "gulp-istanbul": "^0.10.0",
        "gulp-mocha": "^2.0.0",
        "proxyquire": "^1.0.1",
        "semantic-release": "^4.3.5",
        "sinon": "^1.10.3",
        "yeoman-assert": "^2.1.1",
        "yeoman-test": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "dfce37c8028da8994d6d944db096052c646a4ade",
        "tarball": "https://registry.npmjs.org/generator-ng-poly/-/generator-ng-poly-0.13.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "generators"
    ],
    "gitHead": "5c6cba6f94dd6ff2f02817db971f6902fc0c431b",
    "homepage": "https://github.com/dustinspecker/generator-ng-poly#readme",
    "keywords": [
        "yeoman-generator",
        "angular",
        "gulp",
        "jasmine",
        "mocha",
        "protractor",
        "polymer"
    ],
    "license": "MIT",
    "main": "generators/app/index.js",
    "maintainers": [
        {
            "name": "dustinspecker"
        }
    ],
    "name": "generator-ng-poly",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dustinspecker/generator-ng-poly.git"
    },
    "scripts": {
        "coveralls": "cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "gulp test"
    },
    "version": "0.13.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
