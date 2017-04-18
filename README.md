# npmtest-parse-dashboard

#### test coverage for  [parse-dashboard (v1.0.25)](https://github.com/ParsePlatform/parse-dashboard)  [![npm package](https://img.shields.io/npm/v/npmtest-parse-dashboard.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-parse-dashboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-parse-dashboard.svg)](https://travis-ci.org/npmtest/node-npmtest-parse-dashboard)

#### The Parse Dashboard

[![NPM](https://nodei.co/npm/parse-dashboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/parse-dashboard)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-parse-dashboard/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse-dashboard/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-parse-dashboard/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-parse-dashboard/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-parse-dashboard/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-parse-dashboard/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-parse-dashboard/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-parse-dashboard/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-parse-dashboard/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-parse-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-parse-dashboard/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-parse-dashboard/build/test-report.html](https://npmtest.github.io/node-npmtest-parse-dashboard/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-parse-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-parse-dashboard/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-parse-dashboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-parse-dashboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-parse-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-parse-dashboard/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-parse-dashboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-parse-dashboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "parse-dashboard": "./bin/parse-dashboard"
    },
    "bugs": {
        "url": "https://github.com/ParsePlatform/parse-dashboard/issues"
    },
    "dependencies": {
        "bcryptjs": "^2.3.0",
        "body-parser": "^1.15.2",
        "commander": "^2.9.0",
        "connect-flash": "^0.1.1",
        "cookie-session": "^2.0.0-alpha.1",
        "csurf": "^1.9.0",
        "express": "^4.13.4",
        "json-file-plus": "^3.2.0",
        "package-json": "^2.3.1",
        "passport": "^0.3.2",
        "passport-local": "^1.0.0"
    },
    "description": "The Parse Dashboard",
    "devDependencies": {
        "babel-core": "~5.8.12",
        "babel-loader": "~5.3.0",
        "babel-plugin-remove-proptypes": "~1.0.0",
        "babel-polyfill": "^6.7.2",
        "babel-runtime": "~5.8.25",
        "css-loader": "~0.18.0",
        "file-loader": "^0.8.5",
        "history": "^2.1.2",
        "http-server": "~0.8.5",
        "immutable": "~3.7.5",
        "immutable-devtools": "~0.0.4",
        "jest-cli": "^12.0.2",
        "js-beautify": "~1.5.0",
        "marked": "^0.3.5",
        "node-sass": "^3.7.0",
        "parse": "1.6.14",
        "prismjs": "~1.2.0",
        "react": "^15.0.1",
        "react-addons-test-utils": "^15.0.1",
        "react-dnd": "~2.1.4",
        "react-dnd-html5-backend": "~2.0.0",
        "react-dom": "^15.0.1",
        "react-router": "^2.6.0",
        "request-promise": "^4.1.1",
        "sass-loader": "~3.1.2",
        "style-loader": "~0.12.3",
        "svg-prep": "~1.0.0",
        "transform-jest-deps": "^2.1.0",
        "webpack": "~1.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2a0ea7e10f15d6af96b82e17585f5ca9e7e98dec",
        "tarball": "https://registry.npmjs.org/parse-dashboard/-/parse-dashboard-1.0.25.tgz"
    },
    "engines": {
        "node": ">=4.3"
    },
    "files": [
        "Parse-Dashboard",
        "bin",
        "README.md",
        "LICENSE"
    ],
    "gitHead": "46260a6892ff4e63ef4e118085725204d9820319",
    "homepage": "https://github.com/ParsePlatform/parse-dashboard",
    "jest": {
        "testPathDirs": [
            "src/lib"
        ],
        "scriptPreprocessor": "<rootDir>/testing/preprocessor.js",
        "testDirectoryName": "tests",
        "testFileExtensions": [
            "test.js"
        ],
        "unmockedModulePathPatterns": [
            "react",
            "react-dom",
            "react-addons-test-utils",
            "fbjs"
        ]
    },
    "keywords": [
        "parse",
        "dashboard"
    ],
    "license": "SEE LICENSE IN LICENSE",
    "main": "Parse-Dashboard/app.js",
    "maintainers": [
        {
            "name": "boinged"
        },
        {
            "name": "drewgross"
        },
        {
            "name": "flovilmart"
        },
        {
            "name": "tylerbrock"
        }
    ],
    "name": "parse-dashboard",
    "optionalDependencies": {},
    "parseDashboardFeatures": [
        "Data Browser",
        "Cloud Code Viewer",
        "Cloud Code Jobs Viewer and Runner",
        "Parse Config",
        "API Console",
        "Class Level Permissions Editor",
        "Pointer Permissions Editor",
        "Send Push Notifications",
        "Logs Viewer",
        "Push Status Page",
        "Relation Editor"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ParsePlatform/parse-dashboard.git"
    },
    "scripts": {
        "build": "NODE_ENV=production webpack --config webpack/production.config.js && webpack --config webpack/PIG.config.js",
        "dashboard": "node ./Parse-Dashboard/index.js & webpack --config webpack/build.config.js --progress --watch",
        "dev": "node ./Parse-Dashboard/index.js & webpack --config webpack/build.config.js --devtool eval-source-map --progress --watch",
        "generate": "node scripts/generate.js",
        "pig": "http-server ./PIG -p 4041 -s & webpack --config webpack/PIG.config.js --progress --watch",
        "prepublish": "webpack --config webpack/publish.config.js",
        "start": "node ./Parse-Dashboard/index.js",
        "test": "NODE_PATH=./node_modules jest"
    },
    "version": "1.0.25"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
