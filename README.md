# npmtest-marked-toc

#### basic test coverage for  [marked-toc (v0.3.0)](https://github.com/jonschlinkert/marked-toc)  [![npm package](https://img.shields.io/npm/v/npmtest-marked-toc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-marked-toc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-marked-toc.svg)](https://travis-ci.org/npmtest/node-npmtest-marked-toc)

#### Generate a markdown TOC (table of contents).

[![NPM](https://nodei.co/npm/marked-toc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/marked-toc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-marked-toc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-marked-toc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-marked-toc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-marked-toc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-marked-toc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-marked-toc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-marked-toc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-marked-toc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-marked-toc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-marked-toc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-marked-toc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-marked-toc/build/test-report.html](https://npmtest.github.io/node-npmtest-marked-toc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-marked-toc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-marked-toc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-marked-toc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-marked-toc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-marked-toc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-marked-toc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-marked-toc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-marked-toc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jon Schlinkert",
        "url": "https://github.com/jonschlinkert"
    },
    "bin": {
        "toc": "./cli.js"
    },
    "bugs": {
        "url": "https://github.com/jonschlinkert/marked-toc/issues"
    },
    "dependencies": {
        "fs-utils": "^0.5.0",
        "gray-matter": "^0.5.1",
        "lodash": "~2.4.1",
        "marked": "0.3.0",
        "template": "~0.1.6",
        "uslug": "~1.0.3"
    },
    "description": "Generate a markdown TOC (table of contents).",
    "devDependencies": {
        "chai": "~1.9.0",
        "mocha": "~1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "079a8a8da4bf76c62eff9bfabbf53fb33443837a",
        "tarball": "https://registry.npmjs.org/marked-toc/-/marked-toc-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "homepage": "https://github.com/jonschlinkert/marked-toc",
    "keywords": [
        "readme",
        "markdown",
        "toc",
        "table of contents"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/jonschlinkert/marked-toc/blob/master/LICENSE-MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonschlinkert"
        },
        {
            "name": "doowb"
        }
    ],
    "name": "marked-toc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonschlinkert/marked-toc.git"
    },
    "scripts": {
        "test": "mocha -R spec"
    },
    "version": "0.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
