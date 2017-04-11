# test coverage for  [swig (v1.4.2)](https://github.com/paularmstrong/swig)  [![npm package](https://img.shields.io/npm/v/npmtest-swig.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swig) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swig.svg)](https://travis-ci.org/npmtest/node-npmtest-swig)
#### A simple, powerful, and extendable templating engine for node.js and browsers, similar to Django, Jinja2, and Twig.

[![NPM](https://nodei.co/npm/swig.png?downloads=true)](https://www.npmjs.com/package/swig)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swig/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swig/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swig/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swig/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swig/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swig/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swig/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swig/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-swig/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-swig/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-swig%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swig/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swig/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-swig%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swig/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swig/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swig/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Paul Armstrong",
        "email": "paul@paularmstrongdesigns.com"
    },
    "bin": {
        "swig": "./bin/swig.js"
    },
    "bugs": {
        "url": "https://github.com/paularmstrong/swig/issues"
    },
    "dependencies": {
        "optimist": "~0.6",
        "uglify-js": "~2.4"
    },
    "deprecated": "This package is no longer maintained",
    "description": "A simple, powerful, and extendable templating engine for node.js and browsers, similar to Django, Jinja2, and Twig.",
    "devDependencies": {
        "blanket": "~1.1",
        "browserify": "~2",
        "expect.js": "~0.2",
        "express": "~3",
        "file": "~0.2",
        "jsdoc": "~3.2",
        "less": "~1.4",
        "lodash": "~1.3.1",
        "mocha": "1.12.0",
        "mocha-phantomjs": "~3.1",
        "nodelint": "~0.6",
        "phantomjs": "~1.9.1",
        "still": "0.0.7",
        "travis-cov": "~0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4085ca0453369104b5d483e2841b39b7ae1aaba5",
        "tarball": "https://registry.npmjs.org/swig/-/swig-1.4.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "homepage": "https://github.com/paularmstrong/swig",
    "keywords": [
        "template",
        "templating",
        "html",
        "django",
        "jinja",
        "twig",
        "express",
        "block"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "paularmstrong",
            "email": "paul@paularmstrongdesigns.com"
        }
    ],
    "name": "swig",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/paularmstrong/swig.git"
    },
    "scripts": {
        "prepublish": "npm prune && make build",
        "test": "make lint && make test reporter=spec && make test-browser && make coverage cov-reporter=travis-cov"
    },
    "version": "1.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
