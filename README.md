# npmtest-homebridge-server

#### basic test coverage for  homebridge-server (v1.0.24)  [![npm package](https://img.shields.io/npm/v/npmtest-homebridge-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-homebridge-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-homebridge-server.svg)](https://travis-ci.org/npmtest/node-npmtest-homebridge-server)

#### Server plugin for homebridge: https://github.com/nfarina/homebridge

[![NPM](https://nodei.co/npm/homebridge-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/homebridge-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-homebridge-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-homebridge-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-homebridge-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-homebridge-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-homebridge-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-homebridge-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-homebridge-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-homebridge-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-homebridge-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-homebridge-server/build/test-report.html](https://npmtest.github.io/node-npmtest-homebridge-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-homebridge-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-homebridge-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-homebridge-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-homebridge-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-homebridge-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "homebridge-server",
    "version": "1.0.24",
    "description": "Server plugin for homebridge: https://github.com/nfarina/homebridge",
    "license": "ISC",
    "keywords": [
        "homebridge-plugin"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/gismo141/homebridge-server.git"
    },
    "bugs": {
        "url": "http://github.com/gismo141/homebridge-server/issues"
    },
    "engines": {
        "node": ">=0.12.0",
        "homebridge": ">=0.2.0"
    },
    "dependencies": {
        "homebridge": ">=0.4.9"
    },
    "scripts": {
        "test": "homebridge -U ~/.homebridge -P . > /dev/null 2>&1 & sleep 10; ( curl -Is http://127.0.0.1:8765/remove | head -1 ); kill $!"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
