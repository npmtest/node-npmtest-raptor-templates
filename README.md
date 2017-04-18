# npmtest-raptor-templates

#### test coverage for  [raptor-templates (v1.1.27)](https://github.com/raptorjs3/raptor-templates)  [![npm package](https://img.shields.io/npm/v/npmtest-raptor-templates.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-raptor-templates) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-raptor-templates.svg)](https://travis-ci.org/npmtest/node-npmtest-raptor-templates)

#### Raptor Templates

[![NPM](https://nodei.co/npm/raptor-templates.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raptor-templates)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-raptor-templates/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-raptor-templates/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-raptor-templates/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-raptor-templates/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-raptor-templates/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-raptor-templates/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-raptor-templates/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-raptor-templates/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-raptor-templates/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-raptor-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-raptor-templates/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-raptor-templates/build/test-report.html](https://npmtest.github.io/node-npmtest-raptor-templates/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-raptor-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-raptor-templates/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-raptor-templates/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raptor-templates/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raptor-templates/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raptor-templates/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-raptor-templates/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-raptor-templates/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Steele-Idem"
    },
    "bin": {
        "rhtmlc": "bin/rhtmlc"
    },
    "bugs": {
        "url": "https://github.com/raptorjs3/raptor-templates/issues"
    },
    "dependencies": {
        "char-props": "~0.1.5",
        "events": "^1.0.2",
        "htmlparser2": "^3.7.2",
        "minimatch": "^0.2.14",
        "property-handlers": "^0.2.1-beta",
        "raptor-args": "^1.0.0-beta",
        "raptor-json": "^1.0.0-beta",
        "raptor-logging": "^1.0.0-beta",
        "raptor-modules": "^1.0.0-beta",
        "raptor-polyfill": "^1.0.0-beta",
        "raptor-promises": "^1.0.0-beta",
        "raptor-regexp": "^1.0.0-beta",
        "raptor-render-context": "^1.0.0-beta",
        "raptor-strings": "^1.0.0-beta",
        "raptor-taglib-async": "^1.0.0-beta",
        "raptor-taglib-layout": "^1.0.0-beta",
        "raptor-util": "^1.0.0-beta",
        "sax": "^0.6.0"
    },
    "deprecated": "Use 'marko' instead",
    "description": "Raptor Templates",
    "devDependencies": {
        "chai": "~1.8.1",
        "dustjs-linkedin": "^2.3.4",
        "jshint": "^2.5.0",
        "mocha": "~1.15.1",
        "raptor-cache": "^1.0.0-beta",
        "raptor-data-providers": "^1.0.0-beta",
        "through": "^2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a9809671a45a0604efd24557e5780f5cbc055d78",
        "tarball": "https://registry.npmjs.org/raptor-templates/-/raptor-templates-1.1.27.tgz"
    },
    "ebay": {},
    "gitHead": "8fdeb4c286398a3ef7f599ceefca51b73a6e0b41",
    "homepage": "https://github.com/raptorjs3/raptor-templates",
    "keywords": [
        "templating",
        "template",
        "async",
        "streaming"
    ],
    "license": "Apache License v2.0",
    "main": "runtime/raptor-templates-runtime.js",
    "maintainers": [
        {
            "name": "pnidem"
        },
        {
            "name": "philidem"
        }
    ],
    "name": "raptor-templates",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/raptorjs3/raptor-templates.git"
    },
    "scripts": {
        "test": "mocha --ui bdd --reporter spec ./test && node_modules/.bin/jshint compiler/ runtime/ taglibs/"
    },
    "version": "1.1.27"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
