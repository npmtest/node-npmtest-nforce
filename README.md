# npmtest-nforce

#### basic test coverage for  [nforce (v1.7.0)](https://github.com/kevinohara80/nforce#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-nforce.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nforce) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nforce.svg)](https://travis-ci.org/npmtest/node-npmtest-nforce)

#### nforce is a REST API wrapper for force.com, database.com, and salesforce.com

[![NPM](https://nodei.co/npm/nforce.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nforce)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nforce/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nforce/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nforce/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nforce/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nforce/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-nforce/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-nforce/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nforce/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nforce/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nforce/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nforce/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nforce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nforce/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nforce/build/test-report.html](https://npmtest.github.io/node-npmtest-nforce/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nforce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nforce/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nforce/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nforce/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nforce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nforce/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nforce/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nforce/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kevin O'Hara",
        "url": "http://kevinmohara.com"
    },
    "bugs": {
        "url": "http://github.com/kevinohara80/nforce/issues"
    },
    "dependencies": {
        "bluebird": "^2.3.11",
        "faye": "1.2.3",
        "lodash": "^3.10.1",
        "mime": "1.2.11",
        "request": "^2.49.0"
    },
    "description": "nforce is a REST API wrapper for force.com, database.com, and salesforce.com",
    "devDependencies": {
        "body-parser": "1.0.2",
        "cookie-parser": "1.0.1",
        "express": "4.1.1",
        "express-session": "1.0.4",
        "gulp": "^3.9.0",
        "gulp-jshint": "^1.9.0",
        "jade": "1.3.1",
        "jshint-stylish": "^2.1.0",
        "mocha": "^2.2.5",
        "run-sequence": "^1.0.2",
        "should": "3.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "cd93cb188d7833f88d6d7552bccc7a2de2833a87",
        "tarball": "https://registry.npmjs.org/nforce/-/nforce-1.7.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "ba9e8020551726fb7d9984a4dc872fc182b43e5d",
    "homepage": "https://github.com/kevinohara80/nforce#readme",
    "keywords": [
        "salesforce",
        "salesforce.com",
        "force.com",
        "database.com",
        "sfdc",
        "forcedotcom",
        "rest",
        "api"
    ],
    "license": {
        "type": "MIT",
        "url": "http://opensource.org/licenses/MIT"
    },
    "main": "index.js",
    "maintainers": [
        {
            "name": "kevinohara80"
        }
    ],
    "name": "nforce",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/kevinohara80/nforce.git"
    },
    "scripts": {
        "postversion": "git push && git push --tags",
        "preversion": "npm test",
        "test": "./node_modules/mocha/bin/mocha ./test --reporter spec"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
