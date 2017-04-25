# npmtest-command-line-args

#### basic test coverage for  [command-line-args (v4.0.3)](https://github.com/75lb/command-line-args#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-command-line-args.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-command-line-args) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-command-line-args.svg)](https://travis-ci.org/npmtest/node-npmtest-command-line-args)

#### A mature, feature-complete library to parse command-line options.

[![NPM](https://nodei.co/npm/command-line-args.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/command-line-args)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-command-line-args/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-command-line-args/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-command-line-args/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-command-line-args/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-command-line-args/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-command-line-args/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-command-line-args/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-command-line-args/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-command-line-args/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-command-line-args/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-command-line-args/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-command-line-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-command-line-args/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-command-line-args/build/test-report.html](https://npmtest.github.io/node-npmtest-command-line-args/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-command-line-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-command-line-args/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-command-line-args/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-command-line-args/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-command-line-args/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-command-line-args/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-command-line-args/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-command-line-args/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lloyd Brookes"
    },
    "bin": {
        "command-line-args": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/75lb/command-line-args/issues"
    },
    "dependencies": {
        "array-back": "^1.0.4",
        "find-replace": "^1.0.3",
        "typical": "^2.6.0"
    },
    "description": "A mature, feature-complete library to parse command-line options.",
    "devDependencies": {
        "coveralls": "^2.13.0",
        "jsdoc-to-markdown": "^3.0.0",
        "test-runner": "^0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aefb061f107f0fd8d72b3c5e0ba042b319891bae",
        "tarball": "https://registry.npmjs.org/command-line-args/-/command-line-args-4.0.3.tgz"
    },
    "gitHead": "f2c3d06ab7b782c6656e8dba827b0455f8f5f1ca",
    "homepage": "https://github.com/75lb/command-line-args#readme",
    "keywords": [
        "argv",
        "parse",
        "argument",
        "args",
        "option",
        "options",
        "parser",
        "parsing",
        "cli",
        "command",
        "line"
    ],
    "license": "MIT",
    "main": "lib/command-line-args.js",
    "maintainers": [
        {
            "name": "75lb"
        }
    ],
    "name": "command-line-args",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/75lb/command-line-args.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/.bin/test-runner test/*.js && cat coverage/lcov.info | ./node_modules/.bin/coveralls && rm -rf coverage; echo",
        "docs": "jsdoc2md -l off -t jsdoc2md/README.hbs lib/*.js > README.md; echo",
        "test": "test-runner test/*.js"
    },
    "version": "4.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
