# npmtest-module-generator

#### basic test coverage for  [module-generator (v2.1.0)](https://github.com/mattdesl/module-generator)  [![npm package](https://img.shields.io/npm/v/npmtest-module-generator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-module-generator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-module-generator.svg)](https://travis-ci.org/npmtest/node-npmtest-module-generator)

#### The generator script I use for fresh modules

[![NPM](https://nodei.co/npm/module-generator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/module-generator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-module-generator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-generator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-module-generator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-module-generator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-module-generator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-module-generator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-module-generator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-module-generator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-module-generator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-module-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-module-generator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-module-generator/build/test-report.html](https://npmtest.github.io/node-npmtest-module-generator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-module-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-module-generator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-module-generator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-module-generator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-module-generator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-module-generator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Hugh Kennedy",
        "url": "http://hughsk.io/"
    },
    "bin": {
        "module-generator": "index.js"
    },
    "bugs": {
        "url": "https://github.com/mattdesl/module-generator/issues"
    },
    "contributors": [
        {
            "name": "Matt DesLauriers"
        }
    ],
    "dependencies": {
        "chalk": "^0.5.1",
        "dotty": "0.0.2",
        "inquirer": "^0.5.1",
        "js-string-escape": "^1.0.0",
        "npm": "^2.1.2",
        "npmconf": "^1.0.1",
        "readdirp": "^1.0.1",
        "semver": "^4.0.3",
        "variable-name": "0.0.1",
        "xtend": "^3.0.0",
        "yargs": "^1.3.1"
    },
    "description": "The generator script I use for fresh modules",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "baa76cff753ac375a631bfd4061641a8fec52574",
        "tarball": "https://registry.npmjs.org/module-generator/-/module-generator-2.1.0.tgz"
    },
    "gitHead": "2acc8160028b86b94565baa490482c796715af97",
    "homepage": "https://github.com/mattdesl/module-generator",
    "keywords": [
        "generator",
        "not-yeoman",
        "template",
        "module",
        "author",
        "npm"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mattdesl"
        },
        {
            "name": "hughsk"
        }
    ],
    "name": "module-generator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mattdesl/module-generator.git"
    },
    "scripts": {},
    "version": "2.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
