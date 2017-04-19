# npmdoc-istanbul

#### api documentation for  [istanbul (v0.4.5)](https://github.com/gotwarlost/istanbul#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-istanbul.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-istanbul) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-istanbul.svg)](https://travis-ci.org/npmdoc/node-npmdoc-istanbul)

#### Yet another JS code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests. Supports all JS coverage use cases including unit tests, server side functional tests

[![NPM](https://nodei.co/npm/istanbul.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/istanbul)

- [https://npmdoc.github.io/node-npmdoc-istanbul/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-istanbul/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-istanbul/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-istanbul/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-istanbul/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-istanbul/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Krishnan Anantheswaran"
    },
    "bin": {
        "istanbul": "./lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/gotwarlost/istanbul/issues"
    },
    "contributors": [
        {
            "name": "Reid Burke"
        },
        {
            "name": "Martin Cooper"
        },
        {
            "name": "Dav Glass"
        },
        {
            "name": "nowamasa"
        },
        {
            "name": "Miller Medeiros @millermedeiros"
        },
        {
            "name": "Daniel Perez Alvarez @unindented"
        },
        {
            "name": "Mathias Bynens @mathiasbynens"
        },
        {
            "name": "Nathan Brown @nbrownus"
        },
        {
            "name": "Brian Ng @existentialism"
        },
        {
            "name": "John Morrison @jrgm"
        },
        {
            "name": "Tomaz Muraus @kami"
        },
        {
            "name": "Joe @jhansche"
        },
        {
            "name": "Vojta Jina @vojtajina"
        },
        {
            "name": "Dmitry Shirokov @runk"
        },
        {
            "name": "Chris Gladd @chrisgladd"
        },
        {
            "name": "Sergey Belov"
        },
        {
            "name": "porneL @pornel"
        },
        {
            "name": "@asifrc"
        },
        {
            "name": "Gergely Nemeth @gergelyke"
        },
        {
            "name": "@bixdeng"
        },
        {
            "name": "@mpderbec"
        },
        {
            "name": "@jxiaodev"
        },
        {
            "name": "Arpad Borsos @Swatinem"
        },
        {
            "name": "Ariya Hidayat @ariya"
        },
        {
            "name": "@markyen"
        },
        {
            "name": "Sam Saccone @samccone"
        },
        {
            "name": "Jason Cheatham @jason0x43"
        },
        {
            "name": "@smikes"
        },
        {
            "name": "Yasyf Mohamedali @yasyf"
        },
        {
            "name": "Fabio Crisci @piuccio"
        },
        {
            "name": "Ryan Roemer @ryan-roemer"
        },
        {
            "name": "Douglas Christopher Wilson @dougwilson"
        },
        {
            "name": "Gustav Nikolaj @gustavnikolaj"
        },
        {
            "name": "Denis Sokolov @denis-sokolov"
        },
        {
            "name": "Yann Mainier @ymainier"
        },
        {
            "name": "Yiyu He @dead-horse"
        },
        {
            "name": "Andrew Kelley @andrewrk"
        },
        {
            "name": "Will LaBranche @wlabranche"
        },
        {
            "name": "Mathieu Naouache @math-nao"
        },
        {
            "name": "Ron Korving @ronkorving"
        },
        {
            "name": "Rob McGuire-Dale @robatron"
        },
        {
            "name": "Justin Johnson @booleangate"
        },
        {
            "name": "Juan Gabriel Jiménez @juangabreil"
        },
        {
            "name": "Daniel Sabelnikov @dragn"
        },
        {
            "name": "Tony Lukasavage @tonylukasavage"
        },
        {
            "name": "Simon Ramsay @nexus-uw"
        },
        {
            "name": "Dominykas Blyžė @dominykas"
        },
        {
            "name": "Seth Pollack @sethpollack"
        },
        {
            "name": "Benjamin E. Coe @bcoe"
        },
        {
            "name": "Yuren Ju"
        },
        {
            "name": "Aleksey Verkholantsev"
        },
        {
            "name": "Ed S"
        },
        {
            "name": "Mordy Tikotzky"
        },
        {
            "name": "Haoliang Gao @popomore"
        },
        {
            "name": "Roderick Hsiao @roderickhsiao"
        },
        {
            "name": "Nikita Gusakov @nkt"
        },
        {
            "name": "Alex Dunphy @alexdunphy"
        },
        {
            "name": "Artemy Tregubenko @arty-name"
        },
        {
            "name": "Arye Lukashevski @aryelu"
        },
        {
            "name": "@sterlinghw"
        },
        {
            "name": "Gord Tanner"
        },
        {
            "name": "Tom MacWright @tmcw"
        },
        {
            "name": "Kitson Kelly @kitsonk"
        },
        {
            "name": "@asa-git"
        },
        {
            "name": "@RoCat"
        },
        {
            "name": "Ian Page Hands @iphands"
        },
        {
            "name": "Eddie Gurnee @pegurnee"
        },
        {
            "name": "Kevin Decker @kpdecker"
        },
        {
            "name": "isaacs @isaacs"
        },
        {
            "name": "Steve Gray @steve-gray"
        },
        {
            "name": "Prayag Verma @pra85"
        },
        {
            "name": "Abe Fehr @abejfehr"
        },
        {
            "name": "Brian Woodward @doowb"
        },
        {
            "name": "@Victorystick"
        },
        {
            "name": "@inversion"
        },
        {
            "name": "@JamesMGreene"
        },
        {
            "name": "@ChALkeR"
        },
        {
            "name": "@graingert"
        }
    ],
    "dependencies": {
        "abbrev": "1.0.x",
        "async": "1.x",
        "escodegen": "1.8.x",
        "esprima": "2.7.x",
        "glob": "^5.0.15",
        "handlebars": "^4.0.1",
        "js-yaml": "3.x",
        "mkdirp": "0.5.x",
        "nopt": "3.x",
        "once": "1.x",
        "resolve": "1.1.x",
        "supports-color": "^3.1.0",
        "which": "^1.1.1",
        "wordwrap": "^1.0.0"
    },
    "description": "Yet another JS code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests. Supports all JS coverage use cases including unit tests, server side functional tests ",
    "devDependencies": {
        "coveralls": "2.x",
        "jshint": "^2.8.0",
        "nodeunit": "0.9.x",
        "requirejs": "2.x",
        "rimraf": "^2.4.3"
    },
    "directories": {},
    "dist": {
        "shasum": "65c7d73d4c4da84d4f3ac310b918fb0b8033733b",
        "tarball": "https://registry.npmjs.org/istanbul/-/istanbul-0.4.5.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "89e338fcb1c8a7dea3b9e8f851aa55de2bc3abee",
    "homepage": "https://github.com/gotwarlost/istanbul#readme",
    "keywords": [
        "coverage",
        "code coverage",
        "JS code coverage",
        "JS coverage"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "gotwarlost"
        },
        {
            "name": "davglass"
        }
    ],
    "name": "istanbul",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/gotwarlost/istanbul.git"
    },
    "scripts": {
        "docs": "npm install yuidocjs && node node_modules/yuidocjs/lib/cli.js .",
        "posttest": "node ./lib/cli.js check-coverage --statements 95 --branches 80",
        "pretest": "jshint index.js lib/ test/ && ./download-escodegen-browser.sh",
        "test": "node --harmony test/run.js"
    },
    "version": "0.4.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
