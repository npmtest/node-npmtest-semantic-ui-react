# npmtest-semantic-ui-react

#### basic test coverage for  [semantic-ui-react (v0.68.0)](https://github.com/Semantic-Org/Semantic-UI-React#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-semantic-ui-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-semantic-ui-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-semantic-ui-react.svg)](https://travis-ci.org/npmtest/node-npmtest-semantic-ui-react)

#### The official Semantic-UI-React integration.

[![NPM](https://nodei.co/npm/semantic-ui-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/semantic-ui-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-semantic-ui-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-semantic-ui-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-semantic-ui-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-semantic-ui-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-semantic-ui-react/build/test-report.html](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-semantic-ui-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-semantic-ui-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-semantic-ui-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-semantic-ui-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-semantic-ui-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Technology Advice"
    },
    "bugs": {
        "url": "https://github.com/Semantic-Org/Semantic-UI-React/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.22.0",
        "classnames": "^2.1.5",
        "debug": "^2.6.3",
        "lodash": "^4.17.2",
        "prop-types": "15.5.8"
    },
    "description": "The official Semantic-UI-React integration.",
    "devDependencies": {
        "@types/react": "^15.0.14",
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.0.0",
        "babel-loader": "^6.2.8",
        "babel-plugin-__coverage__": "^11.0.0",
        "babel-plugin-lodash": "^3.2.10",
        "babel-plugin-react-transform": "^2.0.2",
        "babel-plugin-transform-react-handled-props": "^0.2.3",
        "babel-plugin-transform-react-remove-prop-types": "^0.3.2",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "babel-standalone": "^6.24.0",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.6.1",
        "connect-history-api-fallback": "^1.2.0",
        "copy-to-clipboard": "^3.0.5",
        "cross-env": "^4.0.0",
        "del": "^2.2.2",
        "dirty-chai": "^1.2.2",
        "doctoc": "^1.2.0",
        "doctrine": "^2.0.0",
        "empty": "^0.10.1",
        "enzyme": "^2.7.1",
        "eslint-config-ta": "^5.2.0",
        "eslint-plugin-jsx-a11y": "^4.0.0",
        "express": "^4.13.4",
        "faker": "^4.1.0",
        "gh-pages": "^0.12.0",
        "gulp": "github:gulpjs/gulp#4.0",
        "gulp-html-replace": "^1.6.2",
        "gulp-load-plugins": "^1.2.2",
        "gulp-plumber": "^1.0.1",
        "gulp-util": "^3.0.6",
        "html-webpack-plugin": "^2.24.0",
        "imports-loader": "^0.7.1",
        "js-beautify": "^1.6.8",
        "json-loader": "^0.5.3",
        "karma": "^1.4.0",
        "karma-cli": "^1.0.0",
        "karma-coverage": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-mocha-reporter": "^2.2.1",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-phantomjs-shim": "^1.4.0",
        "karma-webpack-with-fast-source-maps": "^1.9.2",
        "mocha": "^3.2.0",
        "node-sass": "^4.1.1",
        "phantomjs-prebuilt": "^2.1.7",
        "raw-loader": "^0.5.1",
        "react": "15.5.4",
        "react-ace": "^4.1.1",
        "react-addons-test-utils": "15.5.1",
        "react-docgen": "^2.13.0",
        "react-document-title": "^2.0.2",
        "react-dom": "15.5.4",
        "react-router": "^4.0.0",
        "react-router-dom": "^4.0.0",
        "require-dir": "^0.3.0",
        "rimraf": "^2.5.2",
        "satisfied": "^1.0.0",
        "semantic-ui-css": "^2.2.2",
        "simulant": "^0.2.2",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.9.0",
        "ta-scripts": "^2.5.2",
        "through2": "^2.0.2",
        "tslint": "^5.0.0",
        "tslint-config-typings": "^0.3.1",
        "typescript": "^2.1.5",
        "webpack": "^2.3.2",
        "webpack-dev-middleware": "^1.10.1",
        "webpack-hot-middleware": "^2.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "249e3701650fa811e6ec1c0ad69720f69a6f62fd",
        "tarball": "https://registry.npmjs.org/semantic-ui-react/-/semantic-ui-react-0.68.0.tgz"
    },
    "files": [
        "src",
        "dist",
        "index.d.ts"
    ],
    "gitHead": "82e777fbfd590efcfcb102e8c11840bbdc8c102a",
    "homepage": "https://github.com/Semantic-Org/Semantic-UI-React#readme",
    "jsnext:main": "dist/es/index.js",
    "license": "MIT",
    "main": "dist/commonjs/index.js",
    "maintainers": [
        {
            "name": "athurman"
        },
        {
            "name": "davezuko"
        },
        {
            "name": "deweybot"
        },
        {
            "name": "fluidbyte"
        },
        {
            "name": "kyleturco"
        },
        {
            "name": "levithomason"
        },
        {
            "name": "psvet"
        },
        {
            "name": "stephen_ta"
        },
        {
            "name": "tadeploy"
        },
        {
            "name": "thomasruns"
        },
        {
            "name": "tomfrost"
        }
    ],
    "module": "dist/es/index.js",
    "name": "semantic-ui-react",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.14.0 <= 15",
        "react-dom": ">=0.14.0 <= 15"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/Semantic-Org/Semantic-UI-React.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:es && npm run build:umd && npm run build:docs",
        "build:commonjs": "babel src -d dist/commonjs && npm run tsd",
        "build:dll": "gulp dll",
        "build:docs": "gulp build:docs",
        "build:docs-cname": "echo react.semantic-ui.com > docs/build/CNAME",
        "build:docs-toc": "doctoc ./.github/CONTRIBUTING.md --github --maxlevel 4",
        "build:es": "cross-env BABEL_ENV=es babel src -d dist/es",
        "build:umd": "gulp umd",
        "deploy:docs": "gh-pages -d docs/build -m 'deploy docs [ci skip]'",
        "docs": "gulp docs",
        "lint": "cross-env NODE_ENV=production eslint .",
        "lint:fix": "npm run lint -- --fix",
        "postrelease": "NODE_ENV=production npm run deploy:docs",
        "prebuild:commonjs": "rimraf dist/commonjs",
        "prebuild:docs": "npm run build:docs-toc",
        "prebuild:es": "rimraf dist/es",
        "predeploy:docs": "cross-env NODE_ENV=production npm run build:docs && npm run build:docs-cname",
        "prerelease": "npm run lint -s && npm run tsd:lint -s && npm test -s && cross-env NODE_ENV=production npm run build",
        "prestart": "npm run satisfied -s -- --fix",
        "pretest": "npm run satisfied -s && npm run build:dll",
        "release:major": "npm run prerelease && ta-script npm/release.sh major",
        "release:minor": "npm run prerelease && ta-script npm/release.sh minor",
        "release:patch": "npm run prerelease && ta-script npm/release.sh patch",
        "satisfied": "satisfied --skip-invalid",
        "start": "npm run docs",
        "test": "cross-env NODE_ENV=test karma start",
        "test:watch": "npm run test --silent -- --no-single-run",
        "tsd": "gulp tsd",
        "tsd:lint": "tslint './src/**/*.d.ts'",
        "tsd:lint:fix": "npm run -s tsd:lint -- --fix"
    },
    "version": "0.68.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
