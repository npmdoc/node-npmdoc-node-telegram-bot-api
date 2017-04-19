# npmdoc-node-telegram-bot-api

#### api documentation for  [node-telegram-bot-api (v0.27.0)](https://github.com/yagop/node-telegram-bot-api)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-telegram-bot-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-telegram-bot-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-telegram-bot-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-telegram-bot-api)

#### Telegram Bot API

[![NPM](https://nodei.co/npm/node-telegram-bot-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-telegram-bot-api)

- [https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-telegram-bot-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yago Pérez"
    },
    "bugs": {
        "url": "https://github.com/yagop/node-telegram-bot-api/issues"
    },
    "contributors": [
        {
            "name": "Anton Mironov",
            "url": "https://github.com/mironov"
        },
        {
            "name": "Daniil Yastremskiy",
            "url": "https://github.com/TheBeastOfCaerbannog"
        },
        {
            "url": "https://github.com/Ni2c2k"
        },
        {
            "name": "Alexander Tarmolov",
            "url": "https://github.com/tarmolov"
        },
        {
            "name": "Plusb Preco",
            "url": "https://github.com/preco21"
        },
        {
            "name": "Ola Flisbäck",
            "url": "https://github.com/oflisback"
        },
        {
            "url": "https://github.com/GingerPlusPlus"
        },
        {
            "name": "Sergey Bogdanov",
            "url": "https://github.com/desunit"
        },
        {
            "name": "Mikhail Burshteyn",
            "url": "https://github.com/m-burst"
        },
        {
            "name": "Horus Lugo",
            "url": "https://github.com/HorusGoul"
        },
        {
            "name": "Serhii Dmytruk",
            "url": "https://github.com/serhiidmytruk"
        },
        {
            "name": "Conor Fennell",
            "url": "https://github.com/conorfennell"
        },
        {
            "name": "Aleksandr L.",
            "url": "https://github.com/w-site"
        },
        {
            "name": "Matthew Brandly",
            "url": "https://github.com/brandly"
        },
        {
            "name": "Anton",
            "url": "https://github.com/Feverqwe"
        },
        {
            "name": "Patricio López Juri",
            "url": "https://github.com/mrpatiwi"
        },
        {
            "name": "Guido García",
            "url": "https://github.com/palmerabollo"
        },
        {
            "name": "Sebastian Troć",
            "url": "https://github.com/SebastianTroc"
        },
        {
            "name": "Mohammed Sohail",
            "url": "https://github.com/kamikazechaser"
        },
        {
            "name": "Jishnu Mohan",
            "url": "https://github.com/jishnu7"
        },
        {
            "name": "Jérémy Gotteland",
            "url": "https://github.com/Tketa"
        },
        {
            "name": "Alex Godko",
            "url": "https://github.com/koloboid"
        },
        {
            "name": "Dardan Neziri",
            "url": "https://github.com/knock-in"
        },
        {
            "name": "Cristian Baldi",
            "url": "https://github.com/crisbal"
        },
        {
            "name": "Vitaly Aminev",
            "url": "https://github.com/AVVS"
        },
        {
            "url": "https://github.com/evolun"
        },
        {
            "name": "Iiro Jäppinen",
            "url": "https://github.com/iiroj"
        },
        {
            "name": "TJ Horner",
            "url": "https://github.com/tjhorner"
        },
        {
            "name": "Rafael Kr",
            "url": "https://github.com/RafaelKr"
        },
        {
            "name": "Vítor Augusto da Silva Vasconcellos",
            "url": "https://github.com/HeavenVolkoff"
        },
        {
            "name": "Rey",
            "url": "https://github.com/reyy"
        },
        {
            "name": "Ivan Skorokhodov",
            "url": "https://github.com/universome"
        },
        {
            "name": "Riddler",
            "url": "https://github.com/Waterloo"
        },
        {
            "url": "https://github.com/EXL"
        },
        {
            "name": "Yago",
            "url": "https://github.com/yagop"
        },
        {
            "name": "Ilias Ismanalijev",
            "url": "https://github.com/Illyism"
        },
        {
            "name": "Chris54721",
            "url": "https://github.com/chris54721"
        },
        {
            "name": "Gocho Mugo",
            "url": "https://github.com/GochoMugo"
        }
    ],
    "dependencies": {
        "array.prototype.findindex": "^2.0.0",
        "bl": "^1.1.2",
        "bluebird": "^3.3.4",
        "debug": "^2.2.0",
        "depd": "^1.1.0",
        "eventemitter3": "^2.0.2",
        "file-type": "^3.9.0",
        "mime": "^1.3.4",
        "pump": "^1.0.1",
        "request": "^2.69.0",
        "request-promise": "^4.1.1"
    },
    "description": "Telegram Bot API",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-eslint": "^6.1.2",
        "babel-plugin-transform-class-properties": "^6.6.0",
        "babel-plugin-transform-es2015-destructuring": "^6.6.5",
        "babel-plugin-transform-es2015-parameters": "^6.7.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.5.0",
        "babel-plugin-transform-es2015-spread": "^6.6.5",
        "babel-plugin-transform-object-rest-spread": "^6.6.5",
        "babel-plugin-transform-strict-mode": "^6.6.5",
        "babel-preset-es2015": "^6.6.0",
        "babel-register": "^6.7.2",
        "contributor": "^0.1.25",
        "eslint": "^2.13.1",
        "eslint-config-airbnb": "^6.2.0",
        "eslint-plugin-mocha": "^4.8.0",
        "is": "^3.1.0",
        "istanbul": "^1.1.0-alpha.1",
        "jsdoc-to-markdown": "^2.0.1",
        "mocha": "^3.2.0",
        "mocha-lcov-reporter": "^1.2.0",
        "node-static": "^0.7.9"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "948db76f3291e1138cccf9e5b7da38c0e3aae1dc",
        "tarball": "https://registry.npmjs.org/node-telegram-bot-api/-/node-telegram-bot-api-0.27.0.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "b2afdeb6a88b35aa0e0c15e214d45cbff052596d",
    "homepage": "https://github.com/yagop/node-telegram-bot-api",
    "keywords": [
        "telegram",
        "telegram bot",
        "telegram bot api",
        "bot"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "yagop"
        }
    ],
    "name": "node-telegram-bot-api",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yagop/node-telegram-bot-api.git"
    },
    "scripts": {
        "build": "babel -d ./lib src",
        "eslint": "eslint ./src ./test ./examples",
        "gen-doc": "jsdoc2md --files src/telegram.js --template doc/api.hbs > doc/api.md",
        "mocha": "mocha",
        "prepublish": "npm run build && npm run gen-doc",
        "pretest": "npm run build",
        "test": "npm run eslint && istanbul cover ./node_modules/mocha/bin/_mocha"
    },
    "version": "0.27.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
