# npmtest-rpi-gpio

#### basic test coverage for  [rpi-gpio (v0.8.1)](https://github.com/JamesBarwell/rpi-gpio.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rpi-gpio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rpi-gpio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rpi-gpio.svg)](https://travis-ci.org/npmtest/node-npmtest-rpi-gpio)

#### Control Raspberry Pi GPIO pins with node.js

[![NPM](https://nodei.co/npm/rpi-gpio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rpi-gpio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rpi-gpio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rpi-gpio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rpi-gpio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rpi-gpio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rpi-gpio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rpi-gpio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rpi-gpio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rpi-gpio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rpi-gpio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rpi-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rpi-gpio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rpi-gpio/build/test-report.html](https://npmtest.github.io/node-npmtest-rpi-gpio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rpi-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rpi-gpio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rpi-gpio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rpi-gpio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rpi-gpio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rpi-gpio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rpi-gpio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rpi-gpio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Barwell"
    },
    "bugs": {
        "url": "https://github.com/JamesBarwell/rpi-gpio.js/issues"
    },
    "dependencies": {
        "async": "1.x",
        "debug": "2.x",
        "epoll": "0.1.x"
    },
    "description": "Control Raspberry Pi GPIO pins with node.js",
    "devDependencies": {
        "istanbul": "~0.2.7",
        "mocha": "~1.18.2",
        "sinon": "~1.9.0"
    },
    "directories": {
        "test": "test",
        "integration": "integration"
    },
    "dist": {
        "shasum": "8d51d41ec0ece02ec7cba26e988b60ede72890a7",
        "tarball": "https://registry.npmjs.org/rpi-gpio/-/rpi-gpio-0.8.1.tgz"
    },
    "gitHead": "ae815a590c95450cc127d5edb5c8d4292e97e62b",
    "homepage": "https://github.com/JamesBarwell/rpi-gpio.js#readme",
    "keywords:": [
        "raspberry",
        "pi",
        "gpio"
    ],
    "license": "MIT",
    "main": "rpi-gpio.js",
    "maintainers": [
        {
            "name": "jamesbarwell"
        }
    ],
    "name": "rpi-gpio",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/JamesBarwell/rpi-gpio.js.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "int": "mocha test/integration",
        "spec": "mocha --reporter spec",
        "test": "mocha"
    },
    "version": "0.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
