# npmtest-decompress

#### basic test coverage for  decompress (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-decompress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-decompress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-decompress.svg)](https://travis-ci.org/npmtest/node-npmtest-decompress)

#### Extracting archives made easy

[![NPM](https://nodei.co/npm/decompress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/decompress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-decompress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-decompress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-decompress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-decompress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-decompress/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-decompress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-decompress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-decompress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-decompress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-decompress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-decompress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-decompress/build/test-report.html](https://npmtest.github.io/node-npmtest-decompress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-decompress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-decompress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-decompress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-decompress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-decompress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-decompress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-decompress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-decompress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "decompress",
    "version": "4.0.0",
    "description": "Extracting archives made easy",
    "license": "MIT",
    "repository": "kevva/decompress",
    "author": {
        "name": "Kevin Mårtensson",
        "url": "https://github.com/kevva"
    },
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava"
    },
    "files": [
        "index.js"
    ],
    "keywords": [
        "bz2",
        "bzip2",
        "decompress",
        "extract",
        "tar",
        "tar.bz",
        "tar.gz",
        "zip",
        "unzip"
    ],
    "dependencies": {
        "decompress-tar": "^4.0.0",
        "decompress-tarbz2": "^4.0.0",
        "decompress-targz": "^4.0.0",
        "decompress-unzip": "^4.0.1",
        "mkdirp": "^0.5.1",
        "pify": "^2.3.0",
        "strip-dirs": "^1.1.1"
    },
    "devDependencies": {
        "ava": "*",
        "is-jpg": "^1.0.0",
        "path-exists": "^3.0.0",
        "pify": "^2.3.0",
        "xo": "*"
    },
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
