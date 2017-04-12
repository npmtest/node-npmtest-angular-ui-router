# test coverage for  [angular-ui-router (v0.4.2)](http://angular-ui.github.com/)  [![npm package](https://img.shields.io/npm/v/npmtest-angular-ui-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular-ui-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular-ui-router.svg)](https://travis-ci.org/npmtest/node-npmtest-angular-ui-router)
#### State-based routing for AngularJS

[![NPM](https://nodei.co/npm/angular-ui-router.png?downloads=true)](https://www.npmjs.com/package/angular-ui-router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular-ui-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-ui-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular-ui-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular-ui-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular-ui-router/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular-ui-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular-ui-router/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-ui-router/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-angular-ui-router/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular-ui-router/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-angular-ui-router%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular-ui-router/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-ui-router/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-angular-ui-router%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-ui-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular-ui-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular-ui-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/angular-ui/ui-router/issues"
    },
    "contributors": [
        {
            "name": "Nate Abele",
            "email": "nate@radify.io",
            "url": "https://github.com/nateabele"
        },
        {
            "name": "Chris Thielen",
            "email": "christhielen@gmail.com",
            "url": "https://github.com/christopherthielen"
        },
        {
            "name": "Tim Kindberg",
            "url": "https://github.com/timkindberg"
        },
        {
            "name": "Karsten Sperling",
            "url": "https://github.com/ksperling"
        }
    ],
    "dependencies": {
        "angular": "^1.0.8"
    },
    "description": "State-based routing for AngularJS",
    "devDependencies": {
        "faithful-exec": "~0.1.0",
        "grunt": "~0.4.1",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-concat": "~0.3.0",
        "grunt-contrib-connect": "~0.7.1",
        "grunt-contrib-jshint": "~0.8.0",
        "grunt-contrib-uglify": "~0.4.0",
        "grunt-contrib-watch": "~0.5.3",
        "grunt-conventional-changelog": "~1.1.0",
        "grunt-karma": "^1.0.0",
        "grunt-ngdocs": "~0.2.5",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "~0.1.0",
        "karma-coffee-preprocessor": "~0.1.0",
        "karma-firefox-launcher": "~0.1.0",
        "karma-html2js-preprocessor": "~0.1.0",
        "karma-jasmine": "~0.1.3",
        "karma-phantomjs-launcher": "~1.0.0",
        "karma-requirejs": "~0.2.0",
        "karma-script-launcher": "~0.1.0",
        "load-grunt-tasks": "~0.4.0",
        "phantomjs-polyfill": "0.0.1",
        "requirejs": "^2.1.22",
        "shelljs": "~0.2.6"
    },
    "directories": {},
    "dist": {
        "shasum": "b6aed1ca69a683c82e3992898eabd4ba15868608",
        "tarball": "https://registry.npmjs.org/angular-ui-router/-/angular-ui-router-0.4.2.tgz"
    },
    "gitHead": "a944c62007fe04a99c84a247036d13d23b6e4e7d",
    "homepage": "http://angular-ui.github.com/",
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/angular-ui/ui-router/blob/master/LICENSE"
        }
    ],
    "main": "release/angular-ui-router.js",
    "maintainers": [
        {
            "name": "nateabele",
            "email": "nate.abele@gmail.com"
        },
        {
            "name": "ProLoser",
            "email": "proloser@hotmail.com"
        },
        {
            "name": "christopherthielen",
            "email": "christopherthielen@sandgnat.com"
        }
    ],
    "name": "angular-ui-router",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/angular-ui/ui-router.git"
    },
    "scripts": {
        "build": "grunt dist",
        "prepublish": "grunt prepublish dist",
        "test": "grunt integrate"
    },
    "version": "0.4.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
