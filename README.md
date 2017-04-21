# npmtest-node-mongo-seeds

#### basic test coverage for  node-mongo-seeds (v2.3.1)  [![npm package](https://img.shields.io/npm/v/npmtest-node-mongo-seeds.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-mongo-seeds) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-mongo-seeds.svg)](https://travis-ci.org/npmtest/node-npmtest-node-mongo-seeds)

#### A tool to populate a mongo db from json files

[![NPM](https://nodei.co/npm/node-mongo-seeds.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-mongo-seeds)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-mongo-seeds/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-mongo-seeds/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-mongo-seeds/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/test-report.html](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-mongo-seeds/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-mongo-seeds/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-mongo-seeds/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-mongo-seeds/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-mongo-seeds/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-mongo-seeds",
    "version": "2.3.1",
    "description": "A tool to populate a mongo db from json files",
    "repository": {
        "type": "git",
        "url": "https://github.com/toymachiner62/node-mongo-seeds"
    },
    "keywords": [
        "node",
        "mongo",
        "seed"
    ],
    "author": "Tom Caflisch <tomcaflisch@gmail.com> (http://allthingswebdesign.com)",
    "main": "./lib/seed.js",
    "bin": {
        "seed": "./bin/seed",
        "seed-setup": "./bin/setup"
    },
    "scripts": {
        "test": "mocha --timeout 5000",
        "setup": "node ./bin/setup",
        "seed": "node ./bin/seed"
    },
    "directories": {
        "bin": "./bin"
    },
    "preferGlobal": "true",
    "license": "MIT",
    "dependencies": {
        "errno": "^0.1.4",
        "json2mongo": "^1.1.0",
        "lodash": "^3.1.0",
        "mongodb": "~2.2.23",
        "optimist": "^0.6.1",
        "q": "^1.4.1"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "chai-fs": "^1.0.0",
        "mocha": "^3.2.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
