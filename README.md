# api documentation for  [sails-postgresql (v0.11.4)](https://github.com/balderdashy/sails-postgresql#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-sails-postgresql.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sails-postgresql) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails-postgresql.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails-postgresql)
#### a postgreSQL adapter for Waterline and Sails.js

[![NPM](https://nodei.co/npm/sails-postgresql.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-postgresql)

- [https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sails-postgresql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Cody Stoltman"
    },
    "bugs": {
        "url": "https://github.com/balderdashy/sails-postgresql/issues"
    },
    "dependencies": {
        "async": "1.5.2",
        "lodash": "3.10.1",
        "pg": "4.5.5",
        "waterline-cursor": "0.0.6",
        "waterline-errors": "0.10.1",
        "waterline-sequel": "0.5.7"
    },
    "description": "a postgreSQL adapter for Waterline and Sails.js",
    "devDependencies": {
        "captains-log": "0.11.11",
        "mocha": "2.4.5",
        "should": "8.2.1",
        "waterline-adapter-tests": "0.11.1"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "35b98e225fedaeb7c8af7da3cc5cdfc3f0fd688d",
        "tarball": "https://registry.npmjs.org/sails-postgresql/-/sails-postgresql-0.11.4.tgz"
    },
    "gitHead": "ee8b10d48d04d2abd98b037a865d5842a239be71",
    "homepage": "https://github.com/balderdashy/sails-postgresql#readme",
    "keywords": [
        "postgresql",
        "orm",
        "waterline",
        "sails"
    ],
    "license": "MIT",
    "main": "lib/adapter",
    "maintainers": [
        {
            "name": "balderdashy"
        },
        {
            "name": "particlebanana"
        },
        {
            "name": "sgress454"
        },
        {
            "name": "tjwebb"
        }
    ],
    "name": "sails-postgresql",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/sails-postgresql.git"
    },
    "scripts": {
        "docker": "docker-compose run adapter bash",
        "test": "make test"
    },
    "url": "http://github.com/balderdashy/sails-postgresql",
    "version": "0.11.4",
    "waterlineAdapter": {
        "waterlineVersion": "~0.10.0",
        "interfaces": [
            "semantic",
            "queryable",
            "migratable",
            "associations",
            "sql"
        ],
        "features": [
            "crossAdapter",
            "unique",
            "autoIncrement",
            "schemas"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
