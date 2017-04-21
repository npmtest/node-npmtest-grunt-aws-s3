# npmtest-grunt-aws-s3

#### basic test coverage for  [grunt-aws-s3 (v0.14.5)](https://github.com/MathieuLoutre/grunt-aws-s3)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-aws-s3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-aws-s3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-aws-s3.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-aws-s3)

#### Interact with AWS S3 using the AWS SDK

[![NPM](https://nodei.co/npm/grunt-aws-s3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-aws-s3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-aws-s3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-aws-s3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-aws-s3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-aws-s3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-aws-s3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-aws-s3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-aws-s3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-aws-s3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-aws-s3",
    "description": "Interact with AWS S3 using the AWS SDK",
    "version": "0.14.5",
    "homepage": "https://github.com/MathieuLoutre/grunt-aws-s3",
    "author": {
        "name": "Mathieu Triay"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/MathieuLoutre/grunt-aws-s3.git"
    },
    "bugs": {
        "url": "https://github.com/MathieuLoutre/grunt-aws-s3/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/MathieuLoutre/grunt-aws-s3/blob/master/LICENSE"
        }
    ],
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "pretest": "./scripts/create_fixtures.sh",
        "test": "grunt"
    },
    "dependencies": {
        "aws-sdk": "2.0.x",
        "mime-types": "2.0.x",
        "lodash": "2.4.x",
        "async": "0.9.x",
        "progress": "1.1.x"
    },
    "devDependencies": {
        "grunt-contrib-jshint": "~0.2.0",
        "grunt": "~0.4.0",
        "chai": "~1.7.2",
        "mocha": "~1.12.1",
        "grunt-mocha-test": "~0.10.2",
        "grunt-contrib-copy": "~0.4.1",
        "grunt-contrib-clean": "~0.5.0",
        "mock-aws-s3": "0.2.7"
    },
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "keywords": [
        "gruntplugin",
        "aws",
        "s3",
        "sdk"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
