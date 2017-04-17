# api documentation for  [nativefier (v7.1.0)](https://github.com/jiahaog/nativefier#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-nativefier.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-nativefier) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-nativefier.svg)](https://travis-ci.org/npmdoc/node-npmdoc-nativefier)
#### Wrap web apps natively

[![NPM](https://nodei.co/npm/nativefier.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nativefier)

- [https://npmdoc.github.io/node-npmdoc-nativefier/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nativefier/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nativefier/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nativefier/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-nativefier/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-nativefier/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "babel": {
        "presets": [
            "es2015"
        ]
    },
    "bin": {
        "nativefier": "lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/jiahaog/nativefier/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "axios": "^0.11.1",
        "babel-polyfill": "^6.7.2",
        "cheerio": "^0.20.0",
        "commander": "^2.9.0",
        "electron-packager": "^7.0.1",
        "gitcloud": "^0.1.0",
        "hasbin": "^1.2.0",
        "lodash": "^4.0.0",
        "loglevel": "^1.4.0",
        "ncp": "^2.0.0",
        "page-icon": "^0.3.0",
        "progress": "^1.1.8",
        "request": "^2.67.0",
        "sanitize-filename": "^1.5.3",
        "shelljs": "^0.7.0",
        "source-map-support": "^0.4.0",
        "tmp": "0.0.28",
        "validator": "^5.2.0"
    },
    "description": "Wrap web apps natively",
    "devDependencies": {
        "async": "^1.5.2",
        "babel-core": "^6.4.5",
        "babel-loader": "^6.2.1",
        "babel-preset-es2015": "^6.6.0",
        "babel-register": "^6.6.0",
        "chai": "^3.4.1",
        "del": "^2.2.0",
        "eslint": "^2.10.2",
        "eslint-config-google": "^0.5.0",
        "gulp": "^3.9.0",
        "gulp-babel": "^6.1.1",
        "gulp-istanbul": "^0.10.3",
        "gulp-mocha": "^2.2.0",
        "gulp-sourcemaps": "^1.6.0",
        "lodash": "^4.0.0",
        "require-dir": "^0.3.0",
        "run-sequence": "^1.1.5",
        "shelljs": "^0.7.0",
        "tmp": "0.0.28",
        "webpack-stream": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8bc6d62cc3e900177b165c0d58ea6935e02f79c6",
        "tarball": "https://registry.npmjs.org/nativefier/-/nativefier-7.1.0.tgz"
    },
    "gitHead": "a540326237ca884f10c34c5f0c9bea1010b02a97",
    "homepage": "https://github.com/jiahaog/nativefier#readme",
    "keywords": [
        "desktop",
        "electron",
        "app",
        "native",
        "wrapper"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "jiahaog"
        },
        {
            "name": "skewedlines"
        }
    ],
    "name": "nativefier",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jiahaog/nativefier.git"
    },
    "scripts": {
        "build": "gulp build",
        "ci": "gulp test && npm run lint",
        "clean": "gulp clean",
        "dev-up": "npm install && (cd app && npm install) && npm run build",
        "lint": "eslint .",
        "package-placeholder": "npm run build && node lib/cli.js http://www.bennish.net/web-notifications.html ~/Desktop --overwrite --name notification-test --icon ./test-resources/iconSampleGrey.png --inject ./test-resources/test-injection.js --inject ./test-resources/test-injection.css && open ~/Desktop/notification-test-darwin-x64/notification-test.app",
        "release": "gulp release",
        "start-placeholder": "npm run build && electron app",
        "test": "gulp test",
        "watch": "while true ; do gulp watch ; done"
    },
    "version": "7.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
