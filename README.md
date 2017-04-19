# npmtest-slug

#### basic test coverage for  [slug (v0.9.1)](https://github.com/dodo/node-slug)  [![npm package](https://img.shields.io/npm/v/npmtest-slug.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slug) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slug.svg)](https://travis-ci.org/npmtest/node-npmtest-slug)

#### slugifies even utf-8 chars!

[![NPM](https://nodei.co/npm/slug.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slug)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slug/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slug/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slug/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slug/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slug/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slug/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slug/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slug/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slug/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slug/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slug/build/test-report.html](https://npmtest.github.io/node-npmtest-slug/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slug/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slug/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slug/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slug/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slug/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slug/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slug/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dodo",
        "url": "https://github.com/dodo"
    },
    "bin": {
        "slug": "bin/slug.js"
    },
    "bugs": {
        "url": "https://github.com/dodo/node-slug/issues"
    },
    "dependencies": {
        "unicode": ">= 0.3.1"
    },
    "description": "slugifies even utf-8 chars!",
    "devDependencies": {
        "coffee-script": "~1.7.1",
        "mocha": "~1.17.1",
        "should": "~3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "af08f608a7c11516b61778aa800dce84c518cfda",
        "tarball": "https://registry.npmjs.org/slug/-/slug-0.9.1.tgz"
    },
    "engines": {
        "node": ">= 0.4.x"
    },
    "gitHead": "ff7426b2fdc084df4ac1ba058ad1ddda62ea2030",
    "homepage": "https://github.com/dodo/node-slug",
    "keywords": [
        "slugify",
        "slug",
        "string",
        "utf8",
        "utf-8",
        "unicode",
        "url"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/dodo/node-slug/raw/master/LICENSE"
        }
    ],
    "main": "slug.js",
    "maintainers": [
        {
            "name": "dodo"
        }
    ],
    "name": "slug",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dodo/node-slug.git"
    },
    "scripts": {
        "test": "mocha ./test/*.test.* --require should --reporter spec --colors --compilers coffee:coffee-script/register"
    },
    "version": "0.9.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
