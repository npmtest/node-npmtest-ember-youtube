# npmtest-ember-youtube

#### basic test coverage for  ember-youtube (v0.8.0)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-youtube.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-youtube) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-youtube.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-youtube)

#### A simple Ember.js component to play and control single YouTube videos using the iframe API.

[![NPM](https://nodei.co/npm/ember-youtube.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-youtube)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-youtube/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-youtube/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-youtube/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-youtube/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-youtube/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-youtube/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-youtube/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-youtube/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-youtube/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-youtube/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-youtube/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-youtube/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-youtube/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-youtube/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-youtube/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-youtube/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-youtube/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-youtube/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-youtube/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-youtube",
    "version": "0.8.0",
    "description": "A simple Ember.js component to play and control single YouTube videos using the iframe API.",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "deploy-demo": "ember build --envrionment=production; mv dist/index.html dist/200.html; surge dist ember-youtube.surge.sh",
        "test": "ember try:testall"
    },
    "repository": "https://github.com/oskarrough/ember-youtube",
    "engines": {
        "node": ">= 0.10.0"
    },
    "author": "",
    "license": "MIT",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-ajax": "^2.0.1",
        "ember-cli": "2.8.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "loader.js": "^4.0.1"
    },
    "keywords": [
        "ember-addon",
        "youtube",
        "video",
        "player"
    ],
    "dependencies": {
        "ember-cli-babel": "^5.1.6"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "http://ember-youtube.surge.sh"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
