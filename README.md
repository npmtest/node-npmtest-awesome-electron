# npmtest-awesome-electron

#### basic test coverage for  [awesome-electron (v2.5.0)](https://github.com/sindresorhus/awesome-electron#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-awesome-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-awesome-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-awesome-electron.svg)](https://travis-ci.org/npmtest/node-npmtest-awesome-electron)

#### Useful resources for creating apps with Electron

[![NPM](https://nodei.co/npm/awesome-electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/awesome-electron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-awesome-electron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-awesome-electron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-awesome-electron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-awesome-electron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-awesome-electron/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-awesome-electron/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-awesome-electron/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-awesome-electron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-awesome-electron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-awesome-electron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-awesome-electron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-awesome-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-awesome-electron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-awesome-electron/build/test-report.html](https://npmtest.github.io/node-npmtest-awesome-electron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-awesome-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-awesome-electron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-awesome-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-awesome-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-awesome-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-awesome-electron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-awesome-electron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-awesome-electron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zeke Sikelianos",
        "url": "http://zeke.sikelianos.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/awesome-electron/issues"
    },
    "dependencies": {},
    "description": "Useful resources for creating apps with Electron",
    "devDependencies": {
        "tap-spec": "^4.1.1",
        "tape": "^4.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "042e804715568722edbb6e66e262aea015c438a4",
        "tarball": "https://registry.npmjs.org/awesome-electron/-/awesome-electron-2.5.0.tgz"
    },
    "gitHead": "c9942b6f6a9ab83727a753ed8001ca0578852337",
    "homepage": "https://github.com/sindresorhus/awesome-electron#readme",
    "keywords": [
        "electron",
        "documentation",
        "reference",
        "guide",
        "awesome"
    ],
    "license": "CC0",
    "main": "awesome.json",
    "maintainers": [
        {
            "name": "jlord"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "sindresorhus"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "awesome-electron",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/awesome-electron.git"
    },
    "scripts": {
        "build": "node build.js > awesome.json",
        "prepublish": "npm test",
        "pretest": "npm run build",
        "test": "node test.js | tap-spec"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
