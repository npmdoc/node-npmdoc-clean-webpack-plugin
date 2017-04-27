# npmdoc-clean-webpack-plugin

#### basic api documentation for  [clean-webpack-plugin (v0.1.16)](https://github.com/johnagan/clean-webpack-plugin)  [![npm package](https://img.shields.io/npm/v/npmdoc-clean-webpack-plugin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-clean-webpack-plugin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-clean-webpack-plugin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-clean-webpack-plugin)

#### A webpack plugin to remove your build folder(s) before building

[![NPM](https://nodei.co/npm/clean-webpack-plugin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/clean-webpack-plugin)

- [https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-clean-webpack-plugin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Agan"
    },
    "bugs": {
        "url": "https://github.com/johnagan/clean-webpack-plugin/issues"
    },
    "dependencies": {
        "rimraf": "~2.5.1"
    },
    "description": "A webpack plugin to remove your build folder(s) before building",
    "devDependencies": {
        "chai": "^3.4.1",
        "coveralls": "^2.11.6",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.2",
        "rewire": "^2.5.1"
    },
    "directories": {},
    "dist": {
        "shasum": "422a8e150bf3d5abfd3d14bfacb070e80fb2e23f",
        "tarball": "https://registry.npmjs.org/clean-webpack-plugin/-/clean-webpack-plugin-0.1.16.tgz"
    },
    "gitHead": "a30bfb1dc0832724ab25b5fa2c993330856fdc0e",
    "homepage": "https://github.com/johnagan/clean-webpack-plugin",
    "keywords": [
        "webpack",
        "plugin",
        "clean",
        "node"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "johnagan"
        }
    ],
    "name": "clean-webpack-plugin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/johnagan/clean-webpack-plugin.git"
    },
    "scripts": {
        "test": "mocha --recursive ./test/*_spec.js",
        "test-travis": "istanbul cover _mocha -- -R spec ./test/*_spec.js",
        "test:watch": "npm run test -- --watch"
    },
    "version": "0.1.16",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
