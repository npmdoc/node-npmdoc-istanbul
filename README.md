# api documentation for  [istanbul (v0.4.5)](https://github.com/gotwarlost/istanbul#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-istanbul.svg)](https://travis-ci.org/npmdoc/node-npmdoc-istanbul)
#### Yet another JS code coverage tool that computes statement, line, function and branch coverage with module loader hooks to transparently add coverage when running tests. Supports all JS coverage use cases including unit tests, server side functional tests

[![NPM](https://nodei.co/npm/istanbul.png?downloads=true)](https://www.npmjs.com/package/istanbul)

[![apidoc](https://npmdoc.github.io/node-npmdoc-istanbul/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-istanbul_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-istanbul/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-istanbul/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Krishnan Anantheswaran",
        "email": "kananthmail-github@yahoo.com"
    },
    "bin": {
        "istanbul": "./lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/gotwarlost/istanbul/issues"
    },
    "contributors": [
        {
            "name": "Reid Burke",
            "email": "me@reidburke.com"
        },
        {
            "name": "Martin Cooper",
            "email": "mfncooper@gmail.com"
        },
        {
            "name": "Dav Glass",
            "email": "davglass@gmail.com"
        },
        {
            "name": "nowamasa",
            "email": "nowamasa@gmail.com"
        },
        {
            "name": "Miller Medeiros @millermedeiros",
            "email": "contact@millermedeiros.com"
        },
        {
            "name": "Daniel Perez Alvarez @unindented",
            "email": "unindented@gmail.com"
        },
        {
            "name": "Mathias Bynens @mathiasbynens",
            "email": "mathias@qiwi.be"
        },
        {
            "name": "Nathan Brown @nbrownus",
            "email": "nate@betable.com"
        },
        {
            "name": "Brian Ng @existentialism",
            "email": "bng412@gmail.com"
        },
        {
            "name": "John Morrison @jrgm"
        },
        {
            "name": "Tomaz Muraus @kami",
            "email": "tomaz+github@tomaz.me"
        },
        {
            "name": "Joe @jhansche",
            "email": "jhansche@meetme.com"
        },
        {
            "name": "Vojta Jina @vojtajina",
            "email": "vojta.jina@gmail.com"
        },
        {
            "name": "Dmitry Shirokov @runk",
            "email": "deadrunk@gmail.com"
        },
        {
            "name": "Chris Gladd @chrisgladd"
        },
        {
            "name": "Sergey Belov",
            "email": "peimei@ya.ru"
        },
        {
            "name": "porneL @pornel",
            "email": "pornel@pornel.net"
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
            "name": "Arpad Borsos @Swatinem",
            "email": "arpad.borsos@googlemail.com"
        },
        {
            "name": "Ariya Hidayat @ariya"
        },
        {
            "name": "@markyen"
        },
        {
            "name": "Sam Saccone @samccone",
            "email": "sam@samx.it"
        },
        {
            "name": "Jason Cheatham @jason0x43"
        },
        {
            "name": "@smikes"
        },
        {
            "name": "Yasyf Mohamedali @yasyf",
            "email": "yasyfm@gmail.com"
        },
        {
            "name": "Fabio Crisci @piuccio",
            "email": "piuccio@gmail.com"
        },
        {
            "name": "Ryan Roemer @ryan-roemer",
            "email": "ryan@loose-bits.com"
        },
        {
            "name": "Douglas Christopher Wilson @dougwilson"
        },
        {
            "name": "Gustav Nikolaj @gustavnikolaj",
            "email": "gustavnikolaj@gmail.com"
        },
        {
            "name": "Denis Sokolov @denis-sokolov",
            "email": "denis@sokolov.cc"
        },
        {
            "name": "Yann Mainier @ymainier"
        },
        {
            "name": "Yiyu He @dead-horse",
            "email": "heyiyu.deadhorse@gmail.com"
        },
        {
            "name": "Andrew Kelley @andrewrk",
            "email": "superjoe30@gmail.com"
        },
        {
            "name": "Will LaBranche @wlabranche",
            "email": "will@labranche.io"
        },
        {
            "name": "Mathieu Naouache @math-nao",
            "email": "math.nao@outlook.com"
        },
        {
            "name": "Ron Korving @ronkorving"
        },
        {
            "name": "Rob McGuire-Dale @robatron",
            "email": "rob.mcguiredale@gmail.com"
        },
        {
            "name": "Justin Johnson @booleangate"
        },
        {
            "name": "Juan Gabriel Jiménez @juangabreil",
            "email": "juangabreil@gmail.com"
        },
        {
            "name": "Daniel Sabelnikov @dragn",
            "email": "dsabelnikov@gmail.com"
        },
        {
            "name": "Tony Lukasavage @tonylukasavage",
            "email": "anthony.lukasavage@gmail.com"
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
            "name": "Benjamin E. Coe @bcoe",
            "email": "ben@npmjs.com"
        },
        {
            "name": "Yuren Ju",
            "email": "yurenju@gmail.com"
        },
        {
            "name": "Aleksey Verkholantsev",
            "email": "alex-vee@yandex-team.ru"
        },
        {
            "name": "Ed S",
            "email": "ejsanders@gmail.com"
        },
        {
            "name": "Mordy Tikotzky",
            "email": "mordytk@gmail.com"
        },
        {
            "name": "Haoliang Gao @popomore",
            "email": "sakura9515@gmail.com"
        },
        {
            "name": "Roderick Hsiao @roderickhsiao"
        },
        {
            "name": "Nikita Gusakov @nkt"
        },
        {
            "name": "Alex Dunphy @alexdunphy",
            "email": "alexanderdunphy@gmail.com"
        },
        {
            "name": "Artemy Tregubenko @arty-name",
            "email": "me@arty.name"
        },
        {
            "name": "Arye Lukashevski @aryelu"
        },
        {
            "name": "@sterlinghw"
        },
        {
            "name": "Gord Tanner",
            "email": "gord@bithound.io"
        },
        {
            "name": "Tom MacWright @tmcw",
            "email": "tom@macwright.org"
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
            "name": "Ian Page Hands @iphands",
            "email": "iphands@gmail.com"
        },
        {
            "name": "Eddie Gurnee @pegurnee"
        },
        {
            "name": "Kevin Decker @kpdecker",
            "email": "kpdecker@gmail.com"
        },
        {
            "name": "isaacs @isaacs",
            "email": "i@izs.me"
        },
        {
            "name": "Steve Gray @steve-gray"
        },
        {
            "name": "Prayag Verma @pra85",
            "email": "prayag.verma@gmail.com"
        },
        {
            "name": "Abe Fehr @abejfehr",
            "email": "abe.fehr@gmail.com"
        },
        {
            "name": "Brian Woodward @doowb",
            "email": "brian.woodward@gmail.com"
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
            "name": "gotwarlost",
            "email": "kananthmail-github@yahoo.com"
        },
        {
            "name": "davglass",
            "email": "davglass@gmail.com"
        }
    ],
    "name": "istanbul",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module istanbul](#apidoc.module.istanbul)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Collector (options)](#apidoc.element.istanbul.Collector)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>ContentWriter ()](#apidoc.element.istanbul.ContentWriter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>FileWriter (sync)](#apidoc.element.istanbul.FileWriter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Instrumenter (options)](#apidoc.element.istanbul.Instrumenter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Report ()](#apidoc.element.istanbul.Report)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Reporter (cfg, dir)](#apidoc.element.istanbul.Reporter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Store ()](#apidoc.element.istanbul.Store)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>TreeSummarizer ()](#apidoc.element.istanbul.TreeSummarizer)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Writer ()](#apidoc.element.istanbul.Writer)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>_yuiLoadHook (matchFn, transformFn, verbose)](#apidoc.element.istanbul._yuiLoadHook)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>command ()](#apidoc.element.istanbul.command)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>matcherFor (options, callback)](#apidoc.element.istanbul.matcherFor)
1.  object <span class="apidocSignatureSpan">istanbul.</span>Collector.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>ContentWriter.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>FileWriter.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>Instrumenter.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>Report.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>Reporter.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>Store.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>TreeSummarizer.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>Writer.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>cli
1.  object <span class="apidocSignatureSpan">istanbul.</span>command.prototype
1.  object <span class="apidocSignatureSpan">istanbul.</span>config
1.  object <span class="apidocSignatureSpan">istanbul.</span>hook
1.  object <span class="apidocSignatureSpan">istanbul.</span>utils
1.  string <span class="apidocSignatureSpan">istanbul.</span>VERSION
1.  string <span class="apidocSignatureSpan">istanbul.</span>assetsDir

#### [module istanbul.Collector](#apidoc.module.istanbul.Collector)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Collector (options)](#apidoc.element.istanbul.Collector.Collector)

#### [module istanbul.Collector.prototype](#apidoc.module.istanbul.Collector.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>add (coverage)](#apidoc.element.istanbul.Collector.prototype.add)
1.  [function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>dispose ()](#apidoc.element.istanbul.Collector.prototype.dispose)
1.  [function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>fileCoverageFor (fileName)](#apidoc.element.istanbul.Collector.prototype.fileCoverageFor)
1.  [function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>files ()](#apidoc.element.istanbul.Collector.prototype.files)
1.  [function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>getFinalCoverage ()](#apidoc.element.istanbul.Collector.prototype.getFinalCoverage)

#### [module istanbul.ContentWriter](#apidoc.module.istanbul.ContentWriter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>ContentWriter ()](#apidoc.element.istanbul.ContentWriter.ContentWriter)

#### [module istanbul.ContentWriter.prototype](#apidoc.module.istanbul.ContentWriter.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.ContentWriter.prototype.</span>println (str)](#apidoc.element.istanbul.ContentWriter.prototype.println)
1.  [function <span class="apidocSignatureSpan">istanbul.ContentWriter.prototype.</span>write ()](#apidoc.element.istanbul.ContentWriter.prototype.write)

#### [module istanbul.FileWriter](#apidoc.module.istanbul.FileWriter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>FileWriter (sync)](#apidoc.element.istanbul.FileWriter.FileWriter)
1.  [function <span class="apidocSignatureSpan">istanbul.FileWriter.</span>super_ ()](#apidoc.element.istanbul.FileWriter.super_)

#### [module istanbul.FileWriter.prototype](#apidoc.module.istanbul.FileWriter.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>copyFile (source, dest)](#apidoc.element.istanbul.FileWriter.prototype.copyFile)
1.  [function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>done ()](#apidoc.element.istanbul.FileWriter.prototype.done)
1.  [function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>writeFile (file, callback)](#apidoc.element.istanbul.FileWriter.prototype.writeFile)

#### [module istanbul.Instrumenter](#apidoc.module.istanbul.Instrumenter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Instrumenter (options)](#apidoc.element.istanbul.Instrumenter.Instrumenter)

#### [module istanbul.Instrumenter.prototype](#apidoc.module.istanbul.Instrumenter.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>arrowBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.arrowBlockConverter)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchIncrementExprAst (varName, branchIndex, down)](#apidoc.element.istanbul.Instrumenter.prototype.branchIncrementExprAst)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchLocationFor (name, index)](#apidoc.element.istanbul.Instrumenter.prototype.branchLocationFor)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchName (type, startLine, pathLocations)](#apidoc.element.istanbul.Instrumenter.prototype.branchName)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>conditionalBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.conditionalBranchInjector)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>convertToBlock (node)](#apidoc.element.istanbul.Instrumenter.prototype.convertToBlock)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverExport (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverExport)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverFunction (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverFunction)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverMetaProperty (node)](#apidoc.element.istanbul.Instrumenter.prototype.coverMetaProperty)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverStatement (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverStatement)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>endIgnore ()](#apidoc.element.istanbul.Instrumenter.prototype.endIgnore)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>extractCurrentHint (node)](#apidoc.element.istanbul.Instrumenter.prototype.extractCurrentHint)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>filterHints (comments)](#apidoc.element.istanbul.Instrumenter.prototype.filterHints)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>findLeaves (node, accumulator, parent, property)](#apidoc.element.istanbul.Instrumenter.prototype.findLeaves)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>fixColumnPositions (coverState)](#apidoc.element.istanbul.Instrumenter.prototype.fixColumnPositions)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>functionName (node, line, location)](#apidoc.element.istanbul.Instrumenter.prototype.functionName)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>getPreamble (sourceCode, emitUseStrict)](#apidoc.element.istanbul.Instrumenter.prototype.getPreamble)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>ifBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.ifBlockConverter)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>ifBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.ifBranchInjector)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrument (code, filename, callback)](#apidoc.element.istanbul.Instrumenter.prototype.instrument)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrumentASTSync (program, filename, originalCode)](#apidoc.element.istanbul.Instrumenter.prototype.instrumentASTSync)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrumentSync (code, filename)](#apidoc.element.istanbul.Instrumenter.prototype.instrumentSync)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>isUseStrictExpression (node)](#apidoc.element.istanbul.Instrumenter.prototype.isUseStrictExpression)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>lastFileCoverage ()](#apidoc.element.istanbul.Instrumenter.prototype.lastFileCoverage)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>lastSourceMap ()](#apidoc.element.istanbul.Instrumenter.prototype.lastSourceMap)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>locationsForNodes (nodes)](#apidoc.element.istanbul.Instrumenter.prototype.locationsForNodes)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>logicalExpressionBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>loopBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.loopBlockConverter)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeAddSkip (branchLocation)](#apidoc.element.istanbul.Instrumenter.prototype.maybeAddSkip)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeAddType (node)](#apidoc.element.istanbul.Instrumenter.prototype.maybeAddType)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeSkipNode (node, type)](#apidoc.element.istanbul.Instrumenter.prototype.maybeSkipNode)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>paranoidHandlerCheck (node)](#apidoc.element.istanbul.Instrumenter.prototype.paranoidHandlerCheck)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>skipInit (node)](#apidoc.element.istanbul.Instrumenter.prototype.skipInit)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>skipLeft (node)](#apidoc.element.istanbul.Instrumenter.prototype.skipLeft)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>splice (statements, node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.splice)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>startIgnore ()](#apidoc.element.istanbul.Instrumenter.prototype.startIgnore)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>statementName (location, initValue)](#apidoc.element.istanbul.Instrumenter.prototype.statementName)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>switchBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.switchBranchInjector)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>switchCaseInjector (node)](#apidoc.element.istanbul.Instrumenter.prototype.switchCaseInjector)
1.  [function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>withBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.withBlockConverter)

#### [module istanbul.Report](#apidoc.module.istanbul.Report)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Report ()](#apidoc.element.istanbul.Report.Report)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>create ()](#apidoc.element.istanbul.Report.create)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>getReportList ()](#apidoc.element.istanbul.Report.getReportList)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>loadAll ()](#apidoc.element.istanbul.Report.loadAll)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>mix (cons, proto)](#apidoc.element.istanbul.Report.mix)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>register ()](#apidoc.element.istanbul.Report.register)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.</span>super_ ()](#apidoc.element.istanbul.Report.super_)

#### [module istanbul.Report.prototype](#apidoc.module.istanbul.Report.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>getDefaultConfig ()](#apidoc.element.istanbul.Report.prototype.getDefaultConfig)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>synopsis ()](#apidoc.element.istanbul.Report.prototype.synopsis)
1.  [function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>writeReport ()](#apidoc.element.istanbul.Report.prototype.writeReport)

#### [module istanbul.Reporter](#apidoc.module.istanbul.Reporter)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Reporter (cfg, dir)](#apidoc.element.istanbul.Reporter.Reporter)

#### [module istanbul.Reporter.prototype](#apidoc.module.istanbul.Reporter.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>add (fmt)](#apidoc.element.istanbul.Reporter.prototype.add)
1.  [function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>addAll (fmts)](#apidoc.element.istanbul.Reporter.prototype.addAll)
1.  [function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>handleDone (callback)](#apidoc.element.istanbul.Reporter.prototype.handleDone)
1.  [function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>write (collector, sync, callback)](#apidoc.element.istanbul.Reporter.prototype.write)

#### [module istanbul.Store](#apidoc.module.istanbul.Store)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Store ()](#apidoc.element.istanbul.Store.Store)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.</span>create ()](#apidoc.element.istanbul.Store.create)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.</span>getStoreList ()](#apidoc.element.istanbul.Store.getStoreList)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.</span>loadAll ()](#apidoc.element.istanbul.Store.loadAll)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.</span>mix (cons, proto)](#apidoc.element.istanbul.Store.mix)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.</span>register ()](#apidoc.element.istanbul.Store.register)

#### [module istanbul.Store.prototype](#apidoc.module.istanbul.Store.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>dispose ()](#apidoc.element.istanbul.Store.prototype.dispose)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>get ()](#apidoc.element.istanbul.Store.prototype.get)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>getObject (key)](#apidoc.element.istanbul.Store.prototype.getObject)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>hasKey ()](#apidoc.element.istanbul.Store.prototype.hasKey)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>keys ()](#apidoc.element.istanbul.Store.prototype.keys)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>set ()](#apidoc.element.istanbul.Store.prototype.set)
1.  [function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>setObject (key, object)](#apidoc.element.istanbul.Store.prototype.setObject)

#### [module istanbul.TreeSummarizer](#apidoc.module.istanbul.TreeSummarizer)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>TreeSummarizer ()](#apidoc.element.istanbul.TreeSummarizer.TreeSummarizer)

#### [module istanbul.TreeSummarizer.prototype](#apidoc.module.istanbul.TreeSummarizer.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.TreeSummarizer.prototype.</span>addFileCoverageSummary (filePath, metrics)](#apidoc.element.istanbul.TreeSummarizer.prototype.addFileCoverageSummary)
1.  [function <span class="apidocSignatureSpan">istanbul.TreeSummarizer.prototype.</span>getTreeSummary ()](#apidoc.element.istanbul.TreeSummarizer.prototype.getTreeSummary)

#### [module istanbul.Writer](#apidoc.module.istanbul.Writer)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>Writer ()](#apidoc.element.istanbul.Writer.Writer)
1.  [function <span class="apidocSignatureSpan">istanbul.Writer.</span>super_ ()](#apidoc.element.istanbul.Writer.super_)

#### [module istanbul.Writer.prototype](#apidoc.module.istanbul.Writer.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>copyFile ()](#apidoc.element.istanbul.Writer.prototype.copyFile)
1.  [function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>done ()](#apidoc.element.istanbul.Writer.prototype.done)
1.  [function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>writeFile ()](#apidoc.element.istanbul.Writer.prototype.writeFile)

#### [module istanbul.cli](#apidoc.module.istanbul.cli)
1.  [function <span class="apidocSignatureSpan">istanbul.cli.</span>runToCompletion (args)](#apidoc.element.istanbul.cli.runToCompletion)

#### [module istanbul.command](#apidoc.module.istanbul.command)
1.  [function <span class="apidocSignatureSpan">istanbul.</span>command ()](#apidoc.element.istanbul.command.command)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>create ()](#apidoc.element.istanbul.command.create)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>getCommandList ()](#apidoc.element.istanbul.command.getCommandList)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>loadAll ()](#apidoc.element.istanbul.command.loadAll)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>mix (cons, proto)](#apidoc.element.istanbul.command.mix)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>register ()](#apidoc.element.istanbul.command.register)
1.  [function <span class="apidocSignatureSpan">istanbul.command.</span>resolveCommandName ()](#apidoc.element.istanbul.command.resolveCommandName)

#### [module istanbul.command.prototype](#apidoc.module.istanbul.command.prototype)
1.  [function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>run (args, callback)](#apidoc.element.istanbul.command.prototype.run)
1.  [function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>synopsis ()](#apidoc.element.istanbul.command.prototype.synopsis)
1.  [function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>toolName ()](#apidoc.element.istanbul.command.prototype.toolName)
1.  [function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>type ()](#apidoc.element.istanbul.command.prototype.type)
1.  [function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>usage ()](#apidoc.element.istanbul.command.prototype.usage)

#### [module istanbul.config](#apidoc.module.istanbul.config)
1.  [function <span class="apidocSignatureSpan">istanbul.config.</span>defaultConfig (includeBackCompatAttrs)](#apidoc.element.istanbul.config.defaultConfig)
1.  [function <span class="apidocSignatureSpan">istanbul.config.</span>loadFile (file, overrides)](#apidoc.element.istanbul.config.loadFile)
1.  [function <span class="apidocSignatureSpan">istanbul.config.</span>loadObject (obj, overrides)](#apidoc.element.istanbul.config.loadObject)

#### [module istanbul.hook](#apidoc.module.istanbul.hook)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>hookCreateScript (matcher, transformer, opts)](#apidoc.element.istanbul.hook.hookCreateScript)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>hookRequire (matcher, transformer, options)](#apidoc.element.istanbul.hook.hookRequire)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>hookRunInThisContext (matcher, transformer, opts)](#apidoc.element.istanbul.hook.hookRunInThisContext)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookCreateScript ()](#apidoc.element.istanbul.hook.unhookCreateScript)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookRequire ()](#apidoc.element.istanbul.hook.unhookRequire)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookRunInThisContext ()](#apidoc.element.istanbul.hook.unhookRunInThisContext)
1.  [function <span class="apidocSignatureSpan">istanbul.hook.</span>unloadRequireCache (matcher)](#apidoc.element.istanbul.hook.unloadRequireCache)

#### [module istanbul.utils](#apidoc.module.istanbul.utils)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>addDerivedInfo (coverage)](#apidoc.element.istanbul.utils.addDerivedInfo)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>addDerivedInfoForFile (fileCoverage)](#apidoc.element.istanbul.utils.addDerivedInfoForFile)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>blankSummary ()](#apidoc.element.istanbul.utils.blankSummary)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>incrementIgnoredTotals (cov)](#apidoc.element.istanbul.utils.incrementIgnoredTotals)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>mergeFileCoverage (first, second)](#apidoc.element.istanbul.utils.mergeFileCoverage)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>mergeSummaryObjects ()](#apidoc.element.istanbul.utils.mergeSummaryObjects)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>removeDerivedInfo (coverage)](#apidoc.element.istanbul.utils.removeDerivedInfo)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>summarizeCoverage (coverage)](#apidoc.element.istanbul.utils.summarizeCoverage)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>summarizeFileCoverage (fileCoverage)](#apidoc.element.istanbul.utils.summarizeFileCoverage)
1.  [function <span class="apidocSignatureSpan">istanbul.utils.</span>toYUICoverage (coverage)](#apidoc.element.istanbul.utils.toYUICoverage)



# <a name="apidoc.module.istanbul"></a>[module istanbul](#apidoc.module.istanbul)

#### <a name="apidoc.element.istanbul.Collector"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Collector (options)](#apidoc.element.istanbul.Collector)
- description and source-code
```javascript
function Collector(options) {
    options = options || {};
    this.store = options.store || new MemoryStore();
}
```
- example usage
```shell
...
    'filename.js');
'''

#### Generate reports given a bunch of coverage JSON objects

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
...
```

#### <a name="apidoc.element.istanbul.ContentWriter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>ContentWriter ()](#apidoc.element.istanbul.ContentWriter)
- description and source-code
```javascript
function ContentWriter() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.FileWriter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>FileWriter (sync)](#apidoc.element.istanbul.FileWriter)
- description and source-code
```javascript
function FileWriter(sync) {
    Writer.call(this);
    var that = this;
    this.delegate = sync ? new SyncFileWriter() : new AsyncFileWriter();
    this.delegate.on('error', function (err) { that.emit('error', err); });
    this.delegate.on('done', function () { that.emit('done'); });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Instrumenter (options)](#apidoc.element.istanbul.Instrumenter)
- description and source-code
```javascript
function Instrumenter(options) {
    this.opts = options || {
        debug: false,
        walkDebug: false,
        coverageVariable: '__coverage__',
        codeGenerationOptions: undefined,
        noAutoWrap: false,
        noCompact: false,
        embedSource: false,
        preserveComments: false,
        esModules: false
    };

    if (this.opts.esModules && !this.opts.noAutoWrap) {
        this.opts.noAutoWrap = true;
        if (this.opts.debug) {
            console.log('Setting noAutoWrap to true as required by esModules');
        }
    }

    this.walker = new Walker({
        ArrowFunctionExpression: [ this.arrowBlockConverter ],
        ExpressionStatement: this.coverStatement,
        ExportNamedDeclaration: this.coverExport,
        BreakStatement: this.coverStatement,
        ContinueStatement: this.coverStatement,
        DebuggerStatement: this.coverStatement,
        ReturnStatement: this.coverStatement,
        ThrowStatement: this.coverStatement,
        TryStatement: [ this.paranoidHandlerCheck, this.coverStatement],
        VariableDeclaration: this.coverStatement,
        IfStatement: [ this.ifBlockConverter, this.coverStatement, this.ifBranchInjector ],
        ForStatement: [ this.skipInit, this.loopBlockConverter, this.coverStatement ],
        ForInStatement: [ this.skipLeft, this.loopBlockConverter, this.coverStatement ],
        ForOfStatement: [ this.skipLeft, this.loopBlockConverter, this.coverStatement ],
        WhileStatement: [ this.loopBlockConverter, this.coverStatement ],
        DoWhileStatement: [ this.loopBlockConverter, this.coverStatement ],
        SwitchStatement: [ this.coverStatement, this.switchBranchInjector ],
        SwitchCase: [ this.switchCaseInjector ],
        WithStatement: [ this.withBlockConverter, this.coverStatement ],
        FunctionDeclaration: [ this.coverFunction, this.coverStatement ],
        FunctionExpression: this.coverFunction,
        LabeledStatement: this.coverStatement,
        ConditionalExpression: this.conditionalBranchInjector,
        LogicalExpression: this.logicalExpressionBranchInjector,
        ObjectExpression: this.maybeAddType,
        MetaProperty: this.coverMetaProperty,
    }, this.extractCurrentHint, this, this.opts.walkDebug);

    //unit testing purposes only
    if (this.opts.backdoor && this.opts.backdoor.omitTrackerSuffix) {
        this.omitTrackerSuffix = true;
    }
}
```
- example usage
```shell
...

All the features of istanbul can be accessed as a library.

#### Instrument code

'''javascript
    var istanbul = require('istanbul');
    var instrumenter = new istanbul.Instrumenter();

    var generatedCode = instrumenter.instrumentSync('function meaningOfLife() { return 42; }',
        'filename.js');
'''

#### Generate reports given a bunch of coverage JSON objects
...
```

#### <a name="apidoc.element.istanbul.Report"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Report ()](#apidoc.element.istanbul.Report)
- description and source-code
```javascript
function Report() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Reporter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Reporter (cfg, dir)](#apidoc.element.istanbul.Reporter)
- description and source-code
```javascript
function Reporter(cfg, dir) {
    this.config = cfg || configuration.loadFile();
    this.dir = dir || this.config.reporting.dir();
    this.reports = {};
}
```
- example usage
```shell
...
'''

#### Generate reports given a bunch of coverage JSON objects

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
reporter.addAll([ 'lcov', 'clover' ]);
...
```

#### <a name="apidoc.element.istanbul.Store"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Store ()](#apidoc.element.istanbul.Store)
- description and source-code
```javascript
function Store() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.TreeSummarizer"></a>[function <span class="apidocSignatureSpan">istanbul.</span>TreeSummarizer ()](#apidoc.element.istanbul.TreeSummarizer)
- description and source-code
```javascript
function TreeSummarizer() {
    this.summaryMap = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Writer"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Writer ()](#apidoc.element.istanbul.Writer)
- description and source-code
```javascript
function Writer() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul._yuiLoadHook"></a>[function <span class="apidocSignatureSpan">istanbul.</span>_yuiLoadHook (matchFn, transformFn, verbose)](#apidoc.element.istanbul._yuiLoadHook)
- description and source-code
```javascript
_yuiLoadHook = function (matchFn, transformFn, verbose) {
    return function (file) {
        if (!file.match(yuiRegexp)) {
            return;
        }
        var YMain = require(file),
            YUI,
            loaderFn,
            origGet;

        if (YMain.YUI) {
            YUI = YMain.YUI;
            loaderFn = YUI.Env && YUI.Env.mods && YUI.Env.mods['loader-base'] ? YUI.Env.mods['loader-base'].fn : null;
            if (!loaderFn) { return; }
            if (verbose) { console.log('Applying YUI load post-hook'); }
            YUI.Env.mods['loader-base'].fn = function (Y) {
                loaderFn.call(null, Y);
                origGet = Y.Get._exec;
                Y.Get._exec = function (data, url, cb) {
                    if (matchFn(url) || matchFn(path.resolve(url))) { //allow for relative paths as well
                        if (verbose) {
                            console.log('Transforming [' + url + ']');
                        }
                        try {
                            data = transformFn(data, url);
                        } catch (ex) {
                            console.error('Error transforming: ' + url + ' return original code');
                            console.error(ex.message || ex);
                            if (ex.stack) { console.error(ex.stack); }
                        }
                    }
                    return origGet.call(Y, data, url, cb);
                };
                return Y;
            };
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command"></a>[function <span class="apidocSignatureSpan">istanbul.</span>command ()](#apidoc.element.istanbul.command)
- description and source-code
```javascript
function Command() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.matcherFor"></a>[function <span class="apidocSignatureSpan">istanbul.</span>matcherFor (options, callback)](#apidoc.element.istanbul.matcherFor)
- description and source-code
```javascript
function matcherFor(options, callback) {

    if (!callback && typeof options === 'function') {
        callback = options;
        options = null;
    }
    options = options || {};
    options.relative = false; //force absolute paths
    options.realpath = true; //force real paths (to match Node.js module paths)

    filesFor(options, function (err, files) {
        var fileMap = {},
            matchFn;
        if (err) { return callback(err); }
        files.forEach(function (file) { fileMap[file] = true; });

        matchFn = function (file) { return fileMap[file]; };
        matchFn.files = Object.keys(fileMap);
        return callback(null, matchFn);
    });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Collector"></a>[module istanbul.Collector](#apidoc.module.istanbul.Collector)

#### <a name="apidoc.element.istanbul.Collector.Collector"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Collector (options)](#apidoc.element.istanbul.Collector.Collector)
- description and source-code
```javascript
function Collector(options) {
    options = options || {};
    this.store = options.store || new MemoryStore();
}
```
- example usage
```shell
...
    'filename.js');
'''

#### Generate reports given a bunch of coverage JSON objects

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
...
```



# <a name="apidoc.module.istanbul.Collector.prototype"></a>[module istanbul.Collector.prototype](#apidoc.module.istanbul.Collector.prototype)

#### <a name="apidoc.element.istanbul.Collector.prototype.add"></a>[function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>add (coverage)](#apidoc.element.istanbul.Collector.prototype.add)
- description and source-code
```javascript
add = function (coverage) {
    var store = this.store;
    Object.keys(coverage).forEach(function (key) {
        var fileCoverage = coverage[key];
        if (store.hasKey(key)) {
            store.setObject(key, utils.mergeFileCoverage(fileCoverage, store.getObject(key)));
        } else {
            store.setObject(key, fileCoverage);
        }
    });
}
```
- example usage
```shell
...

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
reporter.addAll([ 'lcov', 'clover' ]);
reporter.write(collector, sync, function () {
    console.log('All reports generated');
});
...
```

#### <a name="apidoc.element.istanbul.Collector.prototype.dispose"></a>[function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>dispose ()](#apidoc.element.istanbul.Collector.prototype.dispose)
- description and source-code
```javascript
dispose = function () {
    this.store.dispose();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Collector.prototype.fileCoverageFor"></a>[function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>fileCoverageFor (fileName)](#apidoc.element.istanbul.Collector.prototype.fileCoverageFor)
- description and source-code
```javascript
fileCoverageFor = function (fileName) {
    var ret = this.store.getObject(fileName);
    utils.addDerivedInfoForFile(ret);
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Collector.prototype.files"></a>[function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>files ()](#apidoc.element.istanbul.Collector.prototype.files)
- description and source-code
```javascript
files = function () {
    return this.store.keys();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Collector.prototype.getFinalCoverage"></a>[function <span class="apidocSignatureSpan">istanbul.Collector.prototype.</span>getFinalCoverage ()](#apidoc.element.istanbul.Collector.prototype.getFinalCoverage)
- description and source-code
```javascript
getFinalCoverage = function () {
    var ret = {},
        that = this;
    this.files().forEach(function (file) {
        ret[file] = that.fileCoverageFor(file);
    });
    return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.ContentWriter"></a>[module istanbul.ContentWriter](#apidoc.module.istanbul.ContentWriter)

#### <a name="apidoc.element.istanbul.ContentWriter.ContentWriter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>ContentWriter ()](#apidoc.element.istanbul.ContentWriter.ContentWriter)
- description and source-code
```javascript
function ContentWriter() {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.ContentWriter.prototype"></a>[module istanbul.ContentWriter.prototype](#apidoc.module.istanbul.ContentWriter.prototype)

#### <a name="apidoc.element.istanbul.ContentWriter.prototype.println"></a>[function <span class="apidocSignatureSpan">istanbul.ContentWriter.prototype.</span>println (str)](#apidoc.element.istanbul.ContentWriter.prototype.println)
- description and source-code
```javascript
println = function (str) { this.write(str + '\n'); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.ContentWriter.prototype.write"></a>[function <span class="apidocSignatureSpan">istanbul.ContentWriter.prototype.</span>write ()](#apidoc.element.istanbul.ContentWriter.prototype.write)
- description and source-code
```javascript
write = function () {
    throw new Error('write: must be overridden');
}
```
- example usage
```shell
...
        sync = false;

    collector.add(obj1);
    collector.add(obj2); //etc.

    reporter.add('text');
    reporter.addAll([ 'lcov', 'clover' ]);
    reporter.write(collector, sync, function () {
        console.log('All reports generated');
    });
'''

For the gory details consult the [public API](http://gotwarlost.github.com/istanbul/public/apidocs/index.html)
...
```



# <a name="apidoc.module.istanbul.FileWriter"></a>[module istanbul.FileWriter](#apidoc.module.istanbul.FileWriter)

#### <a name="apidoc.element.istanbul.FileWriter.FileWriter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>FileWriter (sync)](#apidoc.element.istanbul.FileWriter.FileWriter)
- description and source-code
```javascript
function FileWriter(sync) {
    Writer.call(this);
    var that = this;
    this.delegate = sync ? new SyncFileWriter() : new AsyncFileWriter();
    this.delegate.on('error', function (err) { that.emit('error', err); });
    this.delegate.on('done', function () { that.emit('done'); });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.FileWriter.super_"></a>[function <span class="apidocSignatureSpan">istanbul.FileWriter.</span>super_ ()](#apidoc.element.istanbul.FileWriter.super_)
- description and source-code
```javascript
function Writer() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.FileWriter.prototype"></a>[module istanbul.FileWriter.prototype](#apidoc.module.istanbul.FileWriter.prototype)

#### <a name="apidoc.element.istanbul.FileWriter.prototype.copyFile"></a>[function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>copyFile (source, dest)](#apidoc.element.istanbul.FileWriter.prototype.copyFile)
- description and source-code
```javascript
copyFile = function (source, dest) {
    mkdirp.sync(path.dirname(dest));
    fs.writeFileSync(dest, fs.readFileSync(source));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.FileWriter.prototype.done"></a>[function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>done ()](#apidoc.element.istanbul.FileWriter.prototype.done)
- description and source-code
```javascript
done = function () {
    this.delegate.done();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.FileWriter.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">istanbul.FileWriter.prototype.</span>writeFile (file, callback)](#apidoc.element.istanbul.FileWriter.prototype.writeFile)
- description and source-code
```javascript
writeFile = function (file, callback) {
    this.delegate.writeFile(file, callback);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Instrumenter"></a>[module istanbul.Instrumenter](#apidoc.module.istanbul.Instrumenter)

#### <a name="apidoc.element.istanbul.Instrumenter.Instrumenter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Instrumenter (options)](#apidoc.element.istanbul.Instrumenter.Instrumenter)
- description and source-code
```javascript
function Instrumenter(options) {
    this.opts = options || {
        debug: false,
        walkDebug: false,
        coverageVariable: '__coverage__',
        codeGenerationOptions: undefined,
        noAutoWrap: false,
        noCompact: false,
        embedSource: false,
        preserveComments: false,
        esModules: false
    };

    if (this.opts.esModules && !this.opts.noAutoWrap) {
        this.opts.noAutoWrap = true;
        if (this.opts.debug) {
            console.log('Setting noAutoWrap to true as required by esModules');
        }
    }

    this.walker = new Walker({
        ArrowFunctionExpression: [ this.arrowBlockConverter ],
        ExpressionStatement: this.coverStatement,
        ExportNamedDeclaration: this.coverExport,
        BreakStatement: this.coverStatement,
        ContinueStatement: this.coverStatement,
        DebuggerStatement: this.coverStatement,
        ReturnStatement: this.coverStatement,
        ThrowStatement: this.coverStatement,
        TryStatement: [ this.paranoidHandlerCheck, this.coverStatement],
        VariableDeclaration: this.coverStatement,
        IfStatement: [ this.ifBlockConverter, this.coverStatement, this.ifBranchInjector ],
        ForStatement: [ this.skipInit, this.loopBlockConverter, this.coverStatement ],
        ForInStatement: [ this.skipLeft, this.loopBlockConverter, this.coverStatement ],
        ForOfStatement: [ this.skipLeft, this.loopBlockConverter, this.coverStatement ],
        WhileStatement: [ this.loopBlockConverter, this.coverStatement ],
        DoWhileStatement: [ this.loopBlockConverter, this.coverStatement ],
        SwitchStatement: [ this.coverStatement, this.switchBranchInjector ],
        SwitchCase: [ this.switchCaseInjector ],
        WithStatement: [ this.withBlockConverter, this.coverStatement ],
        FunctionDeclaration: [ this.coverFunction, this.coverStatement ],
        FunctionExpression: this.coverFunction,
        LabeledStatement: this.coverStatement,
        ConditionalExpression: this.conditionalBranchInjector,
        LogicalExpression: this.logicalExpressionBranchInjector,
        ObjectExpression: this.maybeAddType,
        MetaProperty: this.coverMetaProperty,
    }, this.extractCurrentHint, this, this.opts.walkDebug);

    //unit testing purposes only
    if (this.opts.backdoor && this.opts.backdoor.omitTrackerSuffix) {
        this.omitTrackerSuffix = true;
    }
}
```
- example usage
```shell
...

All the features of istanbul can be accessed as a library.

#### Instrument code

'''javascript
    var istanbul = require('istanbul');
    var instrumenter = new istanbul.Instrumenter();

    var generatedCode = instrumenter.instrumentSync('function meaningOfLife() { return 42; }',
        'filename.js');
'''

#### Generate reports given a bunch of coverage JSON objects
...
```



# <a name="apidoc.module.istanbul.Instrumenter.prototype"></a>[module istanbul.Instrumenter.prototype](#apidoc.module.istanbul.Instrumenter.prototype)

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.arrowBlockConverter"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>arrowBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.arrowBlockConverter)
- description and source-code
```javascript
arrowBlockConverter = function (node) {
    var retStatement;
    if (node.expression) { // turn expression nodes into a block with a return statement
        retStatement = astgen.returnStatement(node.body);
        // ensure the generated return statement is covered
        retStatement.loc = node.body.loc;
        node.body = this.convertToBlock(retStatement);
        node.expression = false;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.branchIncrementExprAst"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchIncrementExprAst (varName, branchIndex, down)](#apidoc.element.istanbul.Instrumenter.prototype.branchIncrementExprAst)
- description and source-code
```javascript
branchIncrementExprAst = function (varName, branchIndex, down) {
    var ret = astgen.postIncrement(
        astgen.subscript(
            astgen.subscript(
                astgen.dot(astgen.variable(this.currentState.trackerVar), astgen.variable('b')),
                astgen.stringLiteral(varName)
            ),
            astgen.numericLiteral(branchIndex)
        ),
        down
    );
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.branchLocationFor"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchLocationFor (name, index)](#apidoc.element.istanbul.Instrumenter.prototype.branchLocationFor)
- description and source-code
```javascript
branchLocationFor = function (name, index) {
    return this.coverState.branchMap[name].locations[index];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.branchName"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>branchName (type, startLine, pathLocations)](#apidoc.element.istanbul.Instrumenter.prototype.branchName)
- description and source-code
```javascript
branchName = function (type, startLine, pathLocations) {
    var bName,
        paths = [],
        locations = [],
        i,
        ignoring = !!this.currentState.ignoring;
    this.currentState.branch += 1;
    bName = this.currentState.branch;
    for (i = 0; i < pathLocations.length; i += 1) {
        pathLocations[i].skip = pathLocations[i].skip || ignoring || undefined;
        locations.push(pathLocations[i]);
        paths.push(0);
    }
    this.coverState.b[bName] = paths;
    this.coverState.branchMap[bName] = { line: startLine, type: type, locations: locations };
    return bName;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.conditionalBranchInjector"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>conditionalBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.conditionalBranchInjector)
- description and source-code
```javascript
conditionalBranchInjector = function (node, walker) {
    var bName = this.branchName('cond-expr', walker.startLineForNode(node), this.locationsForNodes([ node.consequent, node.alternate
 ])),
        ast1 = this.branchIncrementExprAst(bName, 0),
        ast2 = this.branchIncrementExprAst(bName, 1);

    node.consequent.preprocessor = this.maybeAddSkip(this.branchLocationFor(bName, 0));
    node.alternate.preprocessor = this.maybeAddSkip(this.branchLocationFor(bName, 1));
    node.consequent = astgen.sequence(ast1, node.consequent);
    node.alternate = astgen.sequence(ast2, node.alternate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.convertToBlock"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>convertToBlock (node)](#apidoc.element.istanbul.Instrumenter.prototype.convertToBlock)
- description and source-code
```javascript
convertToBlock = function (node) {
    if (!node) {
        return { type: 'BlockStatement', body: [] };
    } else if (node.type === 'BlockStatement') {
        return node;
    } else {
        return { type: 'BlockStatement', body: [ node ] };
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.coverExport"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverExport (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverExport)
- description and source-code
```javascript
coverExport = function (node, walker) {
    var sName, incrStatementCount;

    if ( !node.declaration || !node.declaration.declarations ) { return; }

    this.maybeSkipNode(node, 'next');

    sName = this.statementName(node.declaration.loc);
    incrStatementCount = astgen.statement(
        astgen.postIncrement(
            astgen.subscript(
                astgen.dot(astgen.variable(this.currentState.trackerVar), astgen.variable('s')),
                astgen.stringLiteral(sName)
            )
        )
    );

    this.splice(incrStatementCount, node, walker);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.coverFunction"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverFunction (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverFunction)
- description and source-code
```javascript
coverFunction = function (node, walker) {
    var id,
        body = node.body,
        blockBody = body.body,
        popped;

    this.maybeSkipNode(node, 'next');

    id = this.functionName(node, walker.startLineForNode(node), {
        start: node.loc.start,
        end: { line: node.body.loc.start.line, column: node.body.loc.start.column }
    });

    if (blockBody.length > 0 && this.isUseStrictExpression(blockBody[0])) {
        popped = blockBody.shift();
    }
    blockBody.unshift(
        astgen.statement(
            astgen.postIncrement(
                astgen.subscript(
                    astgen.dot(astgen.variable(this.currentState.trackerVar), astgen.variable('f')),
                    astgen.stringLiteral(id)
                )
            )
        )
    );
    if (popped) {
        blockBody.unshift(popped);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.coverMetaProperty"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverMetaProperty (node)](#apidoc.element.istanbul.Instrumenter.prototype.coverMetaProperty)
- description and source-code
```javascript
coverMetaProperty = function (node) {
   node.skipSelf = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.coverStatement"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>coverStatement (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.coverStatement)
- description and source-code
```javascript
coverStatement = function (node, walker) {
    var sName,
        incrStatementCount,
        parent,
        grandParent;

    this.maybeSkipNode(node, 'next');

    if (this.isUseStrictExpression(node)) {
        grandParent = walker.ancestor(2);
<span class="apidocCodeCommentSpan">        /* istanbul ignore else: difficult to test */
</span>        if (grandParent) {
            if ((grandParent.node.type === SYNTAX.FunctionExpression.name ||
                grandParent.node.type === SYNTAX.FunctionDeclaration.name)  &&
                walker.parent().node.body[0] === node) {
                return;
            }
        }
    }

    if (node.type === SYNTAX.FunctionDeclaration.name) {
        // Called for the side-effect of setting the function's statement count to 1.
        this.statementName(node.loc, 1);
    } else {
        // We let 'coverExport' handle ExportNamedDeclarations.
        parent = walker.parent();
        if (parent && parent.node.type === SYNTAX.ExportNamedDeclaration.name) {
            return;
        }

        sName = this.statementName(node.loc);

        incrStatementCount = astgen.statement(
            astgen.postIncrement(
                astgen.subscript(
                    astgen.dot(astgen.variable(this.currentState.trackerVar), astgen.variable('s')),
                    astgen.stringLiteral(sName)
                )
            )
        );

        this.splice(incrStatementCount, node, walker);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.endIgnore"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>endIgnore ()](#apidoc.element.istanbul.Instrumenter.prototype.endIgnore)
- description and source-code
```javascript
endIgnore = function () {
    this.currentState.ignoring -= 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.extractCurrentHint"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>extractCurrentHint (node)](#apidoc.element.istanbul.Instrumenter.prototype.extractCurrentHint)
- description and source-code
```javascript
extractCurrentHint = function (node) {
    if (!node.range) { return; }
    var i = this.currentState.lastHintPosition + 1,
        hints = this.currentState.hints,
        nodeStart = node.range[0],
        hint;
    this.currentState.currentHint = null;
    while (i < hints.length) {
        hint = hints[i];
        if (hint.end < nodeStart) {
            this.currentState.currentHint = hint;
            this.currentState.lastHintPosition = i;
            i += 1;
        } else {
            break;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.filterHints"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>filterHints (comments)](#apidoc.element.istanbul.Instrumenter.prototype.filterHints)
- description and source-code
```javascript
filterHints = function (comments) {
    var ret = [],
        i,
        comment,
        groups;
    if (!(comments && isArray(comments))) {
        return ret;
    }
    for (i = 0; i < comments.length; i += 1) {
        comment = comments[i];
<span class="apidocCodeCommentSpan">        /* istanbul ignore else: paranoid check */
</span>        if (comment && comment.value && comment.range && isArray(comment.range)) {
            groups = String(comment.value).match(COMMENT_RE);
            if (groups) {
                ret.push({ type: groups[1], start: comment.range[0], end: comment.range[1] });
            }
        }
    }
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.findLeaves"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>findLeaves (node, accumulator, parent, property)](#apidoc.element.istanbul.Instrumenter.prototype.findLeaves)
- description and source-code
```javascript
findLeaves = function (node, accumulator, parent, property) {
    if (node.type === SYNTAX.LogicalExpression.name) {
        this.findLeaves(node.left, accumulator, node, 'left');
        this.findLeaves(node.right, accumulator, node, 'right');
    } else {
        accumulator.push({ node: node, parent: parent, property: property });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.fixColumnPositions"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>fixColumnPositions (coverState)](#apidoc.element.istanbul.Instrumenter.prototype.fixColumnPositions)
- description and source-code
```javascript
fixColumnPositions = function (coverState) {
    var offset = LEADER_WRAP.length,
        fixer = function (loc) {
            if (loc.start.line === 1) {
                loc.start.column -= offset;
            }
            if (loc.end.line === 1) {
                loc.end.column -= offset;
            }
        },
        k,
        obj,
        i,
        locations;

    obj = coverState.statementMap;
    for (k in obj) {
<span class="apidocCodeCommentSpan">        /* istanbul ignore else: has own property */
</span>        if (obj.hasOwnProperty(k)) { fixer(obj[k]); }
    }
    obj = coverState.fnMap;
    for (k in obj) {
        /* istanbul ignore else: has own property */
        if (obj.hasOwnProperty(k)) { fixer(obj[k].loc); }
    }
    obj = coverState.branchMap;
    for (k in obj) {
        /* istanbul ignore else: has own property */
        if (obj.hasOwnProperty(k)) {
            locations = obj[k].locations;
            for (i = 0; i < locations.length; i += 1) {
                fixer(locations[i]);
            }
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.functionName"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>functionName (node, line, location)](#apidoc.element.istanbul.Instrumenter.prototype.functionName)
- description and source-code
```javascript
functionName = function (node, line, location) {
    this.currentState.func += 1;
    var id = this.currentState.func,
        ignoring = !!this.currentState.ignoring,
        name = node.id ? node.id.name : '(anonymous_' + id + ')',
        clone = function (attr) {
            var obj = location[attr] || /* istanbul ignore next */ {};
            return { line: obj.line, column: obj.column };
        };
    this.coverState.fnMap[id] = {
        name: name, line: line,
        loc: {
            start: clone('start'),
            end: clone('end')
        },
        skip: ignoring || undefined
    };
    this.coverState.f[id] = 0;
    return id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.getPreamble"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>getPreamble (sourceCode, emitUseStrict)](#apidoc.element.istanbul.Instrumenter.prototype.getPreamble)
- description and source-code
```javascript
getPreamble = function (sourceCode, emitUseStrict) {
    var varName = this.opts.coverageVariable || '__coverage__',
        file = this.coverState.path.replace(/\\/g, '\\\\'),
        tracker = this.currentState.trackerVar,
        coverState,
        strictLine = emitUseStrict ? '"use strict";' : '',
        // return replacements using the function to ensure that the replacement is
        // treated like a dumb string and not as a string with RE replacement patterns
        replacer = function (s) {
            return function () { return s; };
        },
        code;
    if (!this.opts.noAutoWrap) {
        this.fixColumnPositions(this.coverState);
    }
    if (this.opts.embedSource) {
        this.coverState.code = sourceCode.split(/(?:\r?\n)|\r/);
    }
    coverState = this.opts.debug ? JSON.stringify(this.coverState, undefined, 4) : JSON.stringify(this.coverState);
    code = [
        "%STRICT%",
        "var %VAR% = (Function('return this'))();",
        "if (!%VAR%.%GLOBAL%) { %VAR%.%GLOBAL% = {}; }",
        "%VAR% = %VAR%.%GLOBAL%;",
        "if (!(%VAR%['%FILE%'])) {",
        "   %VAR%['%FILE%'] = %OBJECT%;",
        "}",
        "%VAR% = %VAR%['%FILE%'];"
    ].join("\n")
        .replace(/%STRICT%/g, replacer(strictLine))
        .replace(/%VAR%/g, replacer(tracker))
        .replace(/%GLOBAL%/g, replacer(varName))
        .replace(/%FILE%/g, replacer(file))
        .replace(/%OBJECT%/g, replacer(coverState));
    return code;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.ifBlockConverter"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>ifBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.ifBlockConverter)
- description and source-code
```javascript
ifBlockConverter = function (node) {
    node.consequent = this.convertToBlock(node.consequent);
    node.alternate = this.convertToBlock(node.alternate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.ifBranchInjector"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>ifBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.ifBranchInjector)
- description and source-code
```javascript
ifBranchInjector = function (node, walker) {
    var alreadyIgnoring = !!this.currentState.ignoring,
        hint = this.currentState.currentHint,
        ignoreThen = !alreadyIgnoring && hint && hint.type === 'if',
        ignoreElse = !alreadyIgnoring && hint && hint.type === 'else',
        line = node.loc.start.line,
        col = node.loc.start.column,
        makeLoc = function () { return  { line: line, column: col }; },
        bName = this.branchName('if', walker.startLineForNode(node), [
            { start: makeLoc(), end: makeLoc(), skip: ignoreThen || undefined },
            { start: makeLoc(), end: makeLoc(), skip: ignoreElse || undefined }
        ]),
        thenBody = node.consequent.body,
        elseBody = node.alternate.body,
        child;
    thenBody.unshift(astgen.statement(this.branchIncrementExprAst(bName, 0)));
    elseBody.unshift(astgen.statement(this.branchIncrementExprAst(bName, 1)));
    if (ignoreThen) { child = node.consequent; child.preprocessor = this.startIgnore; child.postprocessor = this.endIgnore; }
    if (ignoreElse) { child = node.alternate; child.preprocessor = this.startIgnore; child.postprocessor = this.endIgnore; }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.instrument"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrument (code, filename, callback)](#apidoc.element.istanbul.Instrumenter.prototype.instrument)
- description and source-code
```javascript
instrument = function (code, filename, callback) {

    if (!callback && typeof filename === 'function') {
        callback = filename;
        filename = null;
    }
    try {
        callback(null, this.instrumentSync(code, filename));
    } catch (ex) {
        callback(ex);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.instrumentASTSync"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrumentASTSync (program, filename, originalCode)](#apidoc.element.istanbul.Instrumenter.prototype.instrumentASTSync)
- description and source-code
```javascript
instrumentASTSync = function (program, filename, originalCode) {
    var usingStrict = false,
        codegenOptions,
        generated,
        preamble,
        lineCount,
        i;
    filename = filename || String(new Date().getTime()) + '.js';
    this.sourceMap = null;
    this.coverState = {
        path: filename,
        s: {},
        b: {},
        f: {},
        fnMap: {},
        statementMap: {},
        branchMap: {}
    };
    this.currentState = {
        trackerVar: generateTrackerVar(filename, this.omitTrackerSuffix),
        func: 0,
        branch: 0,
        variable: 0,
        statement: 0,
        hints: this.filterHints(program.comments),
        currentHint: null,
        lastHintPosition: -1,
        ignoring: 0
    };
    if (program.body && program.body.length > 0 && this.isUseStrictExpression(program.body[0])) {
        //nuke it
        program.body.shift();
        //and add it back at code generation time
        usingStrict = true;
    }
    this.walker.startWalk(program);
    codegenOptions = this.opts.codeGenerationOptions || { format: { compact: !this.opts.noCompact }};
    codegenOptions.comment = this.opts.preserveComments;
    //console.log(JSON.stringify(program, undefined, 2));

    generated = ESPGEN.generate(program, codegenOptions);
    preamble = this.getPreamble(originalCode || '', usingStrict);

    if (generated.map && generated.code) {
        lineCount = preamble.split(/\r\n|\r|\n/).length;
        // offset all the generated line numbers by the number of lines in the preamble
        for (i = 0; i < generated.map._mappings._array.length; i += 1) {
            generated.map._mappings._array[i].generatedLine += lineCount;
        }
        this.sourceMap = generated.map;
        generated = generated.code;
    }

    return preamble + '\n' + generated + '\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.instrumentSync"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>instrumentSync (code, filename)](#apidoc.element.istanbul.Instrumenter.prototype.instrumentSync)
- description and source-code
```javascript
instrumentSync = function (code, filename) {
    var program;

    //protect from users accidentally passing in a Buffer object instead
    if (typeof code !== 'string') { throw new Error('Code must be string'); }
    if (code.charAt(0) === '#') { //shebang, 'comment' it out, won't affect syntax tree locations for things we care about
        code = '//' + code;
    }
    if (!this.opts.noAutoWrap) {
        code = LEADER_WRAP + code + TRAILER_WRAP;
    }
    try {
        program = ESP.parse(code, {
            loc: true,
            range: true,
            tokens: this.opts.preserveComments,
            comment: true,
            sourceType: this.opts.esModules ? 'module' : 'script'
        });
    } catch (e) {
        console.log('Failed to parse file: ' + filename);
        throw e;
    }
    if (this.opts.preserveComments) {
        program = ESPGEN.attachComments(program, program.comments, program.tokens);
    }
    if (!this.opts.noAutoWrap) {
        program = {
            type: SYNTAX.Program.name,
            body: program.body[0].expression.callee.body.body,
            comments: program.comments
        };
    }
    return this.instrumentASTSync(program, filename, code);
}
```
- example usage
```shell
...

#### Instrument code

'''javascript
var istanbul = require('istanbul');
var instrumenter = new istanbul.Instrumenter();

var generatedCode = instrumenter.instrumentSync('function meaningOfLife() { return 42; }',
    'filename.js');
'''

#### Generate reports given a bunch of coverage JSON objects

'''javascript
var istanbul = require('istanbul'),
...
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.isUseStrictExpression"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>isUseStrictExpression (node)](#apidoc.element.istanbul.Instrumenter.prototype.isUseStrictExpression)
- description and source-code
```javascript
isUseStrictExpression = function (node) {
    return node && node.type === SYNTAX.ExpressionStatement.name &&
        node.expression  && node.expression.type === SYNTAX.Literal.name &&
        node.expression.value === 'use strict';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.lastFileCoverage"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>lastFileCoverage ()](#apidoc.element.istanbul.Instrumenter.prototype.lastFileCoverage)
- description and source-code
```javascript
lastFileCoverage = function () {
    return this.coverState;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.lastSourceMap"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>lastSourceMap ()](#apidoc.element.istanbul.Instrumenter.prototype.lastSourceMap)
- description and source-code
```javascript
lastSourceMap = function () {
    return this.sourceMap;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.locationsForNodes"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>locationsForNodes (nodes)](#apidoc.element.istanbul.Instrumenter.prototype.locationsForNodes)
- description and source-code
```javascript
locationsForNodes = function (nodes) {
    var ret = [],
        i;
    for (i = 0; i < nodes.length; i += 1) {
        ret.push(nodes[i].loc);
    }
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>logicalExpressionBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.logicalExpressionBranchInjector)
- description and source-code
```javascript
logicalExpressionBranchInjector = function (node, walker) {
    var parent = walker.parent(),
        leaves = [],
        bName,
        tuple,
        i;

    this.maybeSkipNode(node, 'next');

    if (parent && parent.node.type === SYNTAX.LogicalExpression.name) {
        //already covered
        return;
    }

    this.findLeaves(node, leaves);
    bName = this.branchName('binary-expr',
        walker.startLineForNode(node),
        this.locationsForNodes(leaves.map(function (item) { return item.node; }))
    );
    for (i = 0; i < leaves.length; i += 1) {
        tuple = leaves[i];
        tuple.parent[tuple.property] = astgen.sequence(this.branchIncrementExprAst(bName, i), tuple.node);
        tuple.node.preprocessor = this.maybeAddSkip(this.branchLocationFor(bName, i));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.loopBlockConverter"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>loopBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.loopBlockConverter)
- description and source-code
```javascript
loopBlockConverter = function (node) {
    node.body = this.convertToBlock(node.body);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.maybeAddSkip"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeAddSkip (branchLocation)](#apidoc.element.istanbul.Instrumenter.prototype.maybeAddSkip)
- description and source-code
```javascript
maybeAddSkip = function (branchLocation) {
    return function (node) {
        var alreadyIgnoring = !!this.currentState.ignoring,
            hint = this.currentState.currentHint,
            ignoreThis = !alreadyIgnoring && hint && hint.type === 'next';
        if (ignoreThis) {
            this.startIgnore();
            node.postprocessor = this.endIgnore;
        }
        if (ignoreThis || alreadyIgnoring) {
            branchLocation.skip = true;
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.maybeAddType"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeAddType (node)](#apidoc.element.istanbul.Instrumenter.prototype.maybeAddType)
- description and source-code
```javascript
maybeAddType = function (node) {
    var props = node.properties,
        i,
        child;
    for (i = 0; i < props.length; i += 1) {
        child = props[i];
        if (!child.type) {
            child.type = SYNTAX.Property.name;
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.maybeSkipNode"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>maybeSkipNode (node, type)](#apidoc.element.istanbul.Instrumenter.prototype.maybeSkipNode)
- description and source-code
```javascript
maybeSkipNode = function (node, type) {
    var alreadyIgnoring = !!this.currentState.ignoring,
        hint = this.currentState.currentHint,
        ignoreThis = !alreadyIgnoring && hint && hint.type === type;

    if (ignoreThis) {
        this.startIgnore();
        node.postprocessor = this.endIgnore;
        return true;
    }
    return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.paranoidHandlerCheck"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>paranoidHandlerCheck (node)](#apidoc.element.istanbul.Instrumenter.prototype.paranoidHandlerCheck)
- description and source-code
```javascript
paranoidHandlerCheck = function (node) {
    // if someone is using an older esprima on the browser
    // convert handlers array to single handler attribute
    // containing its first element
<span class="apidocCodeCommentSpan">    /* istanbul ignore next */
</span>    if (!node.handler && node.handlers) {
        node.handler = node.handlers[0];
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.skipInit"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>skipInit (node)](#apidoc.element.istanbul.Instrumenter.prototype.skipInit)
- description and source-code
```javascript
skipInit = function (node) {
    if (node.init) {
        node.init.skipWalk = true;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.skipLeft"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>skipLeft (node)](#apidoc.element.istanbul.Instrumenter.prototype.skipLeft)
- description and source-code
```javascript
skipLeft = function (node) {
    node.left.skipWalk = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.splice"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>splice (statements, node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.splice)
- description and source-code
```javascript
splice = function (statements, node, walker) {
    var targetNode = walker.isLabeled() ? walker.parent().node : node;
    targetNode.prepend = targetNode.prepend || [];
    pushAll(targetNode.prepend, statements);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.startIgnore"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>startIgnore ()](#apidoc.element.istanbul.Instrumenter.prototype.startIgnore)
- description and source-code
```javascript
startIgnore = function () {
    this.currentState.ignoring += 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.statementName"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>statementName (location, initValue)](#apidoc.element.istanbul.Instrumenter.prototype.statementName)
- description and source-code
```javascript
statementName = function (location, initValue) {
    var sName,
        ignoring = !!this.currentState.ignoring;

    location.skip = ignoring || undefined;
    initValue = initValue || 0;
    this.currentState.statement += 1;
    sName = this.currentState.statement;
    this.coverState.statementMap[sName] = location;
    this.coverState.s[sName] = initValue;
    return sName;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.switchBranchInjector"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>switchBranchInjector (node, walker)](#apidoc.element.istanbul.Instrumenter.prototype.switchBranchInjector)
- description and source-code
```javascript
switchBranchInjector = function (node, walker) {
    var cases = node.cases,
        bName,
        i;

    if (!(cases && cases.length > 0)) {
        return;
    }
    bName = this.branchName('switch', walker.startLineForNode(node), this.locationsForNodes(cases));
    for (i = 0; i < cases.length; i += 1) {
        cases[i].branchLocation = this.branchLocationFor(bName, i);
        cases[i].consequent.unshift(astgen.statement(this.branchIncrementExprAst(bName, i)));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.switchCaseInjector"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>switchCaseInjector (node)](#apidoc.element.istanbul.Instrumenter.prototype.switchCaseInjector)
- description and source-code
```javascript
switchCaseInjector = function (node) {
    var location = node.branchLocation;
    delete node.branchLocation;
    if (this.maybeSkipNode(node, 'next')) {
        location.skip = true;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Instrumenter.prototype.withBlockConverter"></a>[function <span class="apidocSignatureSpan">istanbul.Instrumenter.prototype.</span>withBlockConverter (node)](#apidoc.element.istanbul.Instrumenter.prototype.withBlockConverter)
- description and source-code
```javascript
withBlockConverter = function (node) {
    node.body = this.convertToBlock(node.body);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Report"></a>[module istanbul.Report](#apidoc.module.istanbul.Report)

#### <a name="apidoc.element.istanbul.Report.Report"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Report ()](#apidoc.element.istanbul.Report.Report)
- description and source-code
```javascript
function Report() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.create"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>create ()](#apidoc.element.istanbul.Report.create)
- description and source-code
```javascript
create = function () { [native code] }
```
- example usage
```shell
...
function runCommand(args, callback) {
var pos = findCommandPosition(args),
    command,
    commandArgs,
    commandObject;

if (pos < 0) {
    return callback(inputError.create('Need a command to run'));
}

commandArgs = args.slice(0, pos);
command = args[pos];
commandArgs.push.apply(commandArgs, args.slice(pos + 1));

try {
...
```

#### <a name="apidoc.element.istanbul.Report.getReportList"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>getReportList ()](#apidoc.element.istanbul.Report.getReportList)
- description and source-code
```javascript
getReportList = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.loadAll"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>loadAll ()](#apidoc.element.istanbul.Report.loadAll)
- description and source-code
```javascript
loadAll = function () { [native code] }
```
- example usage
```shell
...
 Copyright (c) 2012, Yahoo! Inc.  All rights reserved.
 Copyrights licensed under the New BSD License. See the accompanying LICENSE file for terms.
 */
var Store = require('./store'),
    Report = require('./report'),
    Command = require('./command');

Store.loadAll();
Report.loadAll();
Command.loadAll();
...
```

#### <a name="apidoc.element.istanbul.Report.mix"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>mix (cons, proto)](#apidoc.element.istanbul.Report.mix)
- description and source-code
```javascript
mix = function (cons, proto) {
    Object.keys(proto).forEach(function (key) {
        cons.prototype[key] = proto[key];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.register"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>register ()](#apidoc.element.istanbul.Report.register)
- description and source-code
```javascript
register = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.super_"></a>[function <span class="apidocSignatureSpan">istanbul.Report.</span>super_ ()](#apidoc.element.istanbul.Report.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Report.prototype"></a>[module istanbul.Report.prototype](#apidoc.module.istanbul.Report.prototype)

#### <a name="apidoc.element.istanbul.Report.prototype.getDefaultConfig"></a>[function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>getDefaultConfig ()](#apidoc.element.istanbul.Report.prototype.getDefaultConfig)
- description and source-code
```javascript
getDefaultConfig = function () {
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.prototype.synopsis"></a>[function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>synopsis ()](#apidoc.element.istanbul.Report.prototype.synopsis)
- description and source-code
```javascript
synopsis = function () {
    throw new Error('synopsis must be overridden');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Report.prototype.writeReport"></a>[function <span class="apidocSignatureSpan">istanbul.Report.prototype.</span>writeReport ()](#apidoc.element.istanbul.Report.prototype.writeReport)
- description and source-code
```javascript
writeReport = function () {
    throw new Error('writeReport: must be overridden');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Reporter"></a>[module istanbul.Reporter](#apidoc.module.istanbul.Reporter)

#### <a name="apidoc.element.istanbul.Reporter.Reporter"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Reporter (cfg, dir)](#apidoc.element.istanbul.Reporter.Reporter)
- description and source-code
```javascript
function Reporter(cfg, dir) {
    this.config = cfg || configuration.loadFile();
    this.dir = dir || this.config.reporting.dir();
    this.reports = {};
}
```
- example usage
```shell
...
'''

#### Generate reports given a bunch of coverage JSON objects

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
reporter.addAll([ 'lcov', 'clover' ]);
...
```



# <a name="apidoc.module.istanbul.Reporter.prototype"></a>[module istanbul.Reporter.prototype](#apidoc.module.istanbul.Reporter.prototype)

#### <a name="apidoc.element.istanbul.Reporter.prototype.add"></a>[function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>add (fmt)](#apidoc.element.istanbul.Reporter.prototype.add)
- description and source-code
```javascript
add = function (fmt) {
    if (this.reports[fmt]) { // already added
        return;
    }
    var config = this.config,
        rptConfig = config.reporting.reportConfig()[fmt] || {};
    rptConfig.verbose = config.verbose;
    rptConfig.dir = this.dir;
    rptConfig.watermarks = config.reporting.watermarks();
    try {
        this.reports[fmt] = Report.create(fmt, rptConfig);
    } catch (ex) {
        throw inputError.create('Invalid report format [' + fmt + ']');
    }
}
```
- example usage
```shell
...

'''javascript
var istanbul = require('istanbul'),
    collector = new istanbul.Collector(),
    reporter = new istanbul.Reporter(),
    sync = false;

collector.add(obj1);
collector.add(obj2); //etc.

reporter.add('text');
reporter.addAll([ 'lcov', 'clover' ]);
reporter.write(collector, sync, function () {
    console.log('All reports generated');
});
...
```

#### <a name="apidoc.element.istanbul.Reporter.prototype.addAll"></a>[function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>addAll (fmts)](#apidoc.element.istanbul.Reporter.prototype.addAll)
- description and source-code
```javascript
addAll = function (fmts) {
    var that = this;
    fmts.forEach(function (f) {
        that.add(f);
    });
}
```
- example usage
```shell
...
        reporter = new istanbul.Reporter(),
        sync = false;

    collector.add(obj1);
    collector.add(obj2); //etc.

    reporter.add('text');
    reporter.addAll([ 'lcov', 'clover' ]);
    reporter.write(collector, sync, function () {
        console.log('All reports generated');
    });
'''

For the gory details consult the [public API](http://gotwarlost.github.com/istanbul/public/apidocs/index.html)
...
```

#### <a name="apidoc.element.istanbul.Reporter.prototype.handleDone"></a>[function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>handleDone (callback)](#apidoc.element.istanbul.Reporter.prototype.handleDone)
- description and source-code
```javascript
handleDone = function (callback) {
    this.inProgress -= 1;
    if (this.inProgress === 0) {
        return callback();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Reporter.prototype.write"></a>[function <span class="apidocSignatureSpan">istanbul.Reporter.prototype.</span>write (collector, sync, callback)](#apidoc.element.istanbul.Reporter.prototype.write)
- description and source-code
```javascript
write = function (collector, sync, callback) {
    var reports = this.reports,
        verbose = this.config.verbose,
        handler = this.handleDone.bind(this, callback);

    this.inProgress = Object.keys(reports).length;

    Object.keys(reports).forEach(function (name) {
        var report = reports[name];
        if (verbose) {
            console.error('Write report: ' + name);
        }
        report.on('done', handler);
        report.writeReport(collector, sync);
    });
}
```
- example usage
```shell
...
        sync = false;

    collector.add(obj1);
    collector.add(obj2); //etc.

    reporter.add('text');
    reporter.addAll([ 'lcov', 'clover' ]);
    reporter.write(collector, sync, function () {
        console.log('All reports generated');
    });
'''

For the gory details consult the [public API](http://gotwarlost.github.com/istanbul/public/apidocs/index.html)
...
```



# <a name="apidoc.module.istanbul.Store"></a>[module istanbul.Store](#apidoc.module.istanbul.Store)

#### <a name="apidoc.element.istanbul.Store.Store"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Store ()](#apidoc.element.istanbul.Store.Store)
- description and source-code
```javascript
function Store() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.create"></a>[function <span class="apidocSignatureSpan">istanbul.Store.</span>create ()](#apidoc.element.istanbul.Store.create)
- description and source-code
```javascript
create = function () { [native code] }
```
- example usage
```shell
...
function runCommand(args, callback) {
var pos = findCommandPosition(args),
    command,
    commandArgs,
    commandObject;

if (pos < 0) {
    return callback(inputError.create('Need a command to run'));
}

commandArgs = args.slice(0, pos);
command = args[pos];
commandArgs.push.apply(commandArgs, args.slice(pos + 1));

try {
...
```

#### <a name="apidoc.element.istanbul.Store.getStoreList"></a>[function <span class="apidocSignatureSpan">istanbul.Store.</span>getStoreList ()](#apidoc.element.istanbul.Store.getStoreList)
- description and source-code
```javascript
getStoreList = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.loadAll"></a>[function <span class="apidocSignatureSpan">istanbul.Store.</span>loadAll ()](#apidoc.element.istanbul.Store.loadAll)
- description and source-code
```javascript
loadAll = function () { [native code] }
```
- example usage
```shell
...
 Copyright (c) 2012, Yahoo! Inc.  All rights reserved.
 Copyrights licensed under the New BSD License. See the accompanying LICENSE file for terms.
 */
var Store = require('./store'),
    Report = require('./report'),
    Command = require('./command');

Store.loadAll();
Report.loadAll();
Command.loadAll();
...
```

#### <a name="apidoc.element.istanbul.Store.mix"></a>[function <span class="apidocSignatureSpan">istanbul.Store.</span>mix (cons, proto)](#apidoc.element.istanbul.Store.mix)
- description and source-code
```javascript
mix = function (cons, proto) {
    Object.keys(proto).forEach(function (key) {
        cons.prototype[key] = proto[key];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.register"></a>[function <span class="apidocSignatureSpan">istanbul.Store.</span>register ()](#apidoc.element.istanbul.Store.register)
- description and source-code
```javascript
register = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Store.prototype"></a>[module istanbul.Store.prototype](#apidoc.module.istanbul.Store.prototype)

#### <a name="apidoc.element.istanbul.Store.prototype.dispose"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>dispose ()](#apidoc.element.istanbul.Store.prototype.dispose)
- description and source-code
```javascript
dispose = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.get"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>get ()](#apidoc.element.istanbul.Store.prototype.get)
- description and source-code
```javascript
get = function () { throw new Error("get: must be overridden"); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.getObject"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>getObject (key)](#apidoc.element.istanbul.Store.prototype.getObject)
- description and source-code
```javascript
getObject = function (key) {
    return JSON.parse(this.get(key));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.hasKey"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>hasKey ()](#apidoc.element.istanbul.Store.prototype.hasKey)
- description and source-code
```javascript
hasKey = function () { throw new Error("hasKey: must be overridden"); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.keys"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>keys ()](#apidoc.element.istanbul.Store.prototype.keys)
- description and source-code
```javascript
keys = function () { throw new Error("keys: must be overridden"); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.set"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>set ()](#apidoc.element.istanbul.Store.prototype.set)
- description and source-code
```javascript
set = function () { throw new Error("set: must be overridden"); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Store.prototype.setObject"></a>[function <span class="apidocSignatureSpan">istanbul.Store.prototype.</span>setObject (key, object)](#apidoc.element.istanbul.Store.prototype.setObject)
- description and source-code
```javascript
setObject = function (key, object) {
    return this.set(key, JSON.stringify(object));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.TreeSummarizer"></a>[module istanbul.TreeSummarizer](#apidoc.module.istanbul.TreeSummarizer)

#### <a name="apidoc.element.istanbul.TreeSummarizer.TreeSummarizer"></a>[function <span class="apidocSignatureSpan">istanbul.</span>TreeSummarizer ()](#apidoc.element.istanbul.TreeSummarizer.TreeSummarizer)
- description and source-code
```javascript
function TreeSummarizer() {
    this.summaryMap = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.TreeSummarizer.prototype"></a>[module istanbul.TreeSummarizer.prototype](#apidoc.module.istanbul.TreeSummarizer.prototype)

#### <a name="apidoc.element.istanbul.TreeSummarizer.prototype.addFileCoverageSummary"></a>[function <span class="apidocSignatureSpan">istanbul.TreeSummarizer.prototype.</span>addFileCoverageSummary (filePath, metrics)](#apidoc.element.istanbul.TreeSummarizer.prototype.addFileCoverageSummary)
- description and source-code
```javascript
addFileCoverageSummary = function (filePath, metrics) {
    this.summaryMap[filePath] = metrics;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.TreeSummarizer.prototype.getTreeSummary"></a>[function <span class="apidocSignatureSpan">istanbul.TreeSummarizer.prototype.</span>getTreeSummary ()](#apidoc.element.istanbul.TreeSummarizer.prototype.getTreeSummary)
- description and source-code
```javascript
getTreeSummary = function () {
    var commonArrayPrefix = findCommonArrayPrefix(Object.keys(this.summaryMap));
    return new TreeSummary(this.summaryMap, commonArrayPrefix);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Writer"></a>[module istanbul.Writer](#apidoc.module.istanbul.Writer)

#### <a name="apidoc.element.istanbul.Writer.Writer"></a>[function <span class="apidocSignatureSpan">istanbul.</span>Writer ()](#apidoc.element.istanbul.Writer.Writer)
- description and source-code
```javascript
function Writer() {
    EventEmitter.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Writer.super_"></a>[function <span class="apidocSignatureSpan">istanbul.Writer.</span>super_ ()](#apidoc.element.istanbul.Writer.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.Writer.prototype"></a>[module istanbul.Writer.prototype](#apidoc.module.istanbul.Writer.prototype)

#### <a name="apidoc.element.istanbul.Writer.prototype.copyFile"></a>[function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>copyFile ()](#apidoc.element.istanbul.Writer.prototype.copyFile)
- description and source-code
```javascript
copyFile = function () {
    throw new Error('copyFile: must be overridden');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Writer.prototype.done"></a>[function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>done ()](#apidoc.element.istanbul.Writer.prototype.done)
- description and source-code
```javascript
done = function () {
    throw new Error('done: must be overridden');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.Writer.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">istanbul.Writer.prototype.</span>writeFile ()](#apidoc.element.istanbul.Writer.prototype.writeFile)
- description and source-code
```javascript
writeFile = function () {
    throw new Error('writeFile: must be overridden');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.cli"></a>[module istanbul.cli](#apidoc.module.istanbul.cli)

#### <a name="apidoc.element.istanbul.cli.runToCompletion"></a>[function <span class="apidocSignatureSpan">istanbul.cli.</span>runToCompletion (args)](#apidoc.element.istanbul.cli.runToCompletion)
- description and source-code
```javascript
function runToCompletion(args) {
    runCommand(args, errHandler);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.command"></a>[module istanbul.command](#apidoc.module.istanbul.command)

#### <a name="apidoc.element.istanbul.command.command"></a>[function <span class="apidocSignatureSpan">istanbul.</span>command ()](#apidoc.element.istanbul.command.command)
- description and source-code
```javascript
function Command() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.create"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>create ()](#apidoc.element.istanbul.command.create)
- description and source-code
```javascript
create = function () { [native code] }
```
- example usage
```shell
...
function runCommand(args, callback) {
var pos = findCommandPosition(args),
    command,
    commandArgs,
    commandObject;

if (pos < 0) {
    return callback(inputError.create('Need a command to run'));
}

commandArgs = args.slice(0, pos);
command = args[pos];
commandArgs.push.apply(commandArgs, args.slice(pos + 1));

try {
...
```

#### <a name="apidoc.element.istanbul.command.getCommandList"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>getCommandList ()](#apidoc.element.istanbul.command.getCommandList)
- description and source-code
```javascript
getCommandList = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.loadAll"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>loadAll ()](#apidoc.element.istanbul.command.loadAll)
- description and source-code
```javascript
loadAll = function () { [native code] }
```
- example usage
```shell
...
 Copyright (c) 2012, Yahoo! Inc.  All rights reserved.
 Copyrights licensed under the New BSD License. See the accompanying LICENSE file for terms.
 */
var Store = require('./store'),
    Report = require('./report'),
    Command = require('./command');

Store.loadAll();
Report.loadAll();
Command.loadAll();
...
```

#### <a name="apidoc.element.istanbul.command.mix"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>mix (cons, proto)](#apidoc.element.istanbul.command.mix)
- description and source-code
```javascript
mix = function (cons, proto) {
    Object.keys(proto).forEach(function (key) {
        cons.prototype[key] = proto[key];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.register"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>register ()](#apidoc.element.istanbul.command.register)
- description and source-code
```javascript
register = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.resolveCommandName"></a>[function <span class="apidocSignatureSpan">istanbul.command.</span>resolveCommandName ()](#apidoc.element.istanbul.command.resolveCommandName)
- description and source-code
```javascript
resolveCommandName = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.command.prototype"></a>[module istanbul.command.prototype](#apidoc.module.istanbul.command.prototype)

#### <a name="apidoc.element.istanbul.command.prototype.run"></a>[function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>run (args, callback)](#apidoc.element.istanbul.command.prototype.run)
- description and source-code
```javascript
run = function (args, callback) {
    return callback(new Error("run: must be overridden for the " + this.type() + " command"));
}
```
- example usage
```shell
...

    try {
        commandObject = Command.create(command);
    } catch (ex) {
        errHandler(inputError.create(ex.message));
        return;
    }
    commandObject.run(commandArgs, errHandler);
}

function runToCompletion(args) {
    runCommand(args, errHandler);
}

/* istanbul ignore if: untestable */
...
```

#### <a name="apidoc.element.istanbul.command.prototype.synopsis"></a>[function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>synopsis ()](#apidoc.element.istanbul.command.prototype.synopsis)
- description and source-code
```javascript
synopsis = function () {
    return "the developer has not written a one-line summary of the " + this.type() + " command";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.prototype.toolName"></a>[function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>toolName ()](#apidoc.element.istanbul.command.prototype.toolName)
- description and source-code
```javascript
toolName = function () {
    return require('../util/meta').NAME;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.prototype.type"></a>[function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>type ()](#apidoc.element.istanbul.command.prototype.type)
- description and source-code
```javascript
type = function () {
    return this.constructor.TYPE;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.command.prototype.usage"></a>[function <span class="apidocSignatureSpan">istanbul.command.prototype.</span>usage ()](#apidoc.element.istanbul.command.prototype.usage)
- description and source-code
```javascript
usage = function () {
    console.error("the developer has not provided a usage for the " + this.type() + " command");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.config"></a>[module istanbul.config](#apidoc.module.istanbul.config)

#### <a name="apidoc.element.istanbul.config.defaultConfig"></a>[function <span class="apidocSignatureSpan">istanbul.config.</span>defaultConfig (includeBackCompatAttrs)](#apidoc.element.istanbul.config.defaultConfig)
- description and source-code
```javascript
function defaultConfig(includeBackCompatAttrs) {
    var ret = {
        verbose: false,
        instrumentation: {
            root: '.',
            extensions: ['.js'],
            'default-excludes': true,
            excludes: [],
            'embed-source': false,
            variable: '__coverage__',
            compact: true,
            'preserve-comments': false,
            'complete-copy': false,
            'save-baseline': false,
            'baseline-file': './coverage/coverage-baseline.json',
            'include-all-sources': false,
            'include-pid': false,
            'es-modules': false
        },
        reporting: {
            print: 'summary',
            reports: [ 'lcov' ],
            dir: './coverage'
        },
        hooks: {
            'hook-run-in-context': false,
            'post-require-hook': null,
            'handle-sigint': false
        },
        check: {
            global: {
                statements: 0,
                lines: 0,
                branches: 0,
                functions: 0,
                excludes: [] // Currently list of files (root + path). For future, extend to patterns.
            },
            each: {
                statements: 0,
                lines: 0,
                branches: 0,
                functions: 0,
                excludes: []
            }
        }
    };
    ret.reporting.watermarks = defaults.watermarks();
    ret.reporting['report-config'] = defaults.defaultReportConfig();

    if (includeBackCompatAttrs) {
        ret.instrumentation['preload-sources'] = false;
    }

    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.config.loadFile"></a>[function <span class="apidocSignatureSpan">istanbul.config.</span>loadFile (file, overrides)](#apidoc.element.istanbul.config.loadFile)
- description and source-code
```javascript
function loadFile(file, overrides) {
    var defaultConfigFile = path.resolve('.istanbul.yml'),
        configObject;

    if (file) {
        if (!existsSync(file)) {
            throw new Error('Invalid configuration file specified:' + file);
        }
    } else {
        if (existsSync(defaultConfigFile)) {
            file = defaultConfigFile;
        }
    }

    if (file) {
        if (overrides && overrides.verbose === true) {
            console.error('Loading config: ' + file);
        }
        configObject = file.match(YML_PATTERN) ?
            yaml.safeLoad(fs.readFileSync(file, 'utf8'), { filename: file }) :
            require(path.resolve(file));
    }

    return new Configuration(configObject, overrides);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.config.loadObject"></a>[function <span class="apidocSignatureSpan">istanbul.config.</span>loadObject (obj, overrides)](#apidoc.element.istanbul.config.loadObject)
- description and source-code
```javascript
function loadObject(obj, overrides) {
    return new Configuration(obj, overrides);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.hook"></a>[module istanbul.hook](#apidoc.module.istanbul.hook)

#### <a name="apidoc.element.istanbul.hook.hookCreateScript"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>hookCreateScript (matcher, transformer, opts)](#apidoc.element.istanbul.hook.hookCreateScript)
- description and source-code
```javascript
function hookCreateScript(matcher, transformer, opts) {
    opts = opts || {};
    var fn = transformFn(matcher, transformer, opts.verbose);
    vm.createScript = function (code, file) {
        var ret = fn(code, file);
        return originalCreateScript(ret.code, file);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.hookRequire"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>hookRequire (matcher, transformer, options)](#apidoc.element.istanbul.hook.hookRequire)
- description and source-code
```javascript
function hookRequire(matcher, transformer, options) {
    options = options || {};
    var extensions,
        fn = transformFn(matcher, transformer, options.verbose),
        postLoadHook = options.postLoadHook &&
            typeof options.postLoadHook === 'function' ? options.postLoadHook : null;

    extensions = options.extensions || ['.js'];

    extensions.forEach(function(ext){
        if (!(ext in originalLoaders)) {
            originalLoaders[ext] = Module._extensions[ext] || Module._extensions['.js'];
        }
        Module._extensions[ext] = function (module, filename) {
            var ret = fn(fs.readFileSync(filename, 'utf8'), filename);
            if (ret.changed) {
                module._compile(ret.code, filename);
            } else {
                originalLoaders[ext](module, filename);
            }
            if (postLoadHook) {
                postLoadHook(filename);
            }
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.hookRunInThisContext"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>hookRunInThisContext (matcher, transformer, opts)](#apidoc.element.istanbul.hook.hookRunInThisContext)
- description and source-code
```javascript
function hookRunInThisContext(matcher, transformer, opts) {
    opts = opts || {};
    var fn = transformFn(matcher, transformer, opts.verbose);
    vm.runInThisContext = function (code, file) {
        var ret = fn(code, file);
        return originalRunInThisContext(ret.code, file);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.unhookCreateScript"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookCreateScript ()](#apidoc.element.istanbul.hook.unhookCreateScript)
- description and source-code
```javascript
function unhookCreateScript() {
    vm.createScript = originalCreateScript;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.unhookRequire"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookRequire ()](#apidoc.element.istanbul.hook.unhookRequire)
- description and source-code
```javascript
function unhookRequire() {
    Object.keys(originalLoaders).forEach(function(ext) {
        Module._extensions[ext] = originalLoaders[ext];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.unhookRunInThisContext"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>unhookRunInThisContext ()](#apidoc.element.istanbul.hook.unhookRunInThisContext)
- description and source-code
```javascript
function unhookRunInThisContext() {
    vm.runInThisContext = originalRunInThisContext;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.hook.unloadRequireCache"></a>[function <span class="apidocSignatureSpan">istanbul.hook.</span>unloadRequireCache (matcher)](#apidoc.element.istanbul.hook.unloadRequireCache)
- description and source-code
```javascript
function unloadRequireCache(matcher) {
    if (matcher && typeof require !== 'undefined' && require && require.cache) {
        Object.keys(require.cache).forEach(function (filename) {
            if (matcher(filename)) {
                delete require.cache[filename];
            }
        });
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.istanbul.utils"></a>[module istanbul.utils](#apidoc.module.istanbul.utils)

#### <a name="apidoc.element.istanbul.utils.addDerivedInfo"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>addDerivedInfo (coverage)](#apidoc.element.istanbul.utils.addDerivedInfo)
- description and source-code
```javascript
function addDerivedInfo(coverage) {
    Object.keys(coverage).forEach(function (k) {
        addDerivedInfoForFile(coverage[k]);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.addDerivedInfoForFile"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>addDerivedInfoForFile (fileCoverage)](#apidoc.element.istanbul.utils.addDerivedInfoForFile)
- description and source-code
```javascript
function addDerivedInfoForFile(fileCoverage) {
    var statementMap = fileCoverage.statementMap,
        statements = fileCoverage.s,
        lineMap;

    if (!fileCoverage.l) {
        fileCoverage.l = lineMap = {};
        Object.keys(statements).forEach(function (st) {
            var line = statementMap[st].start.line,
                count = statements[st],
                prevVal = lineMap[line];
            if (count === 0 && statementMap[st].skip) { count = 1; }
            if (typeof prevVal === 'undefined' || prevVal < count) {
                lineMap[line] = count;
            }
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.blankSummary"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>blankSummary ()](#apidoc.element.istanbul.utils.blankSummary)
- description and source-code
```javascript
function blankSummary() {
    return {
        lines: {
            total: 0,
            covered: 0,
            skipped: 0,
            pct: 'Unknown'
        },
        statements: {
            total: 0,
            covered: 0,
            skipped: 0,
            pct: 'Unknown'
        },
        functions: {
            total: 0,
            covered: 0,
            skipped: 0,
            pct: 'Unknown'
        },
        branches: {
            total: 0,
            covered: 0,
            skipped: 0,
            pct: 'Unknown'
        },
        linesCovered: {}
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.incrementIgnoredTotals"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>incrementIgnoredTotals (cov)](#apidoc.element.istanbul.utils.incrementIgnoredTotals)
- description and source-code
```javascript
function incrementIgnoredTotals(cov) {
    //TODO: This may be slow in the browser and may break in older browsers
    //      Look into using a library that works in Node and the browser
    var fileCoverage = JSON.parse(JSON.stringify(cov));

    [
        {mapKey: 'statementMap', hitsKey: 's'},
        {mapKey: 'branchMap', hitsKey: 'b'},
        {mapKey: 'fnMap', hitsKey: 'f'}
    ].forEach(function (keys) {
        Object.keys(fileCoverage[keys.mapKey])
            .forEach(function (key) {
                var map = fileCoverage[keys.mapKey][key];
                var hits = fileCoverage[keys.hitsKey];

                if (keys.mapKey === 'branchMap') {
                    var locations = map.locations;

                    locations.forEach(function (location, index) {
                        if (hits[key][index] === 0 && location.skip) {
                            hits[key][index] = 1;
                        }
                    });

                    return;
                }

                if (hits[key] === 0 && map.skip) {
                    hits[key] = 1;
                }
            });
        });

    return fileCoverage;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.mergeFileCoverage"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>mergeFileCoverage (first, second)](#apidoc.element.istanbul.utils.mergeFileCoverage)
- description and source-code
```javascript
function mergeFileCoverage(first, second) {
    var ret = JSON.parse(JSON.stringify(first)),
        i;

    delete ret.l; //remove derived info

    Object.keys(second.s).forEach(function (k) {
        ret.s[k] += second.s[k];
    });
    Object.keys(second.f).forEach(function (k) {
        ret.f[k] += second.f[k];
    });
    Object.keys(second.b).forEach(function (k) {
        var retArray = ret.b[k],
            secondArray = second.b[k];
        for (i = 0; i < retArray.length; i += 1) {
            retArray[i] += secondArray[i];
        }
    });

    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.mergeSummaryObjects"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>mergeSummaryObjects ()](#apidoc.element.istanbul.utils.mergeSummaryObjects)
- description and source-code
```javascript
function mergeSummaryObjects() {
    var ret = blankSummary(),
        args = Array.prototype.slice.call(arguments),
        keys = ['lines', 'statements', 'branches', 'functions'],
        increment = function (obj) {
            if (obj) {
                keys.forEach(function (key) {
                    ret[key].total += obj[key].total;
                    ret[key].covered += obj[key].covered;
                    ret[key].skipped += obj[key].skipped;
                });

                // keep track of all lines we have coverage for.
                Object.keys(obj.linesCovered).forEach(function (key) {
                    if (!ret.linesCovered[key]) {
                        ret.linesCovered[key] = obj.linesCovered[key];
                    } else {
                        ret.linesCovered[key] += obj.linesCovered[key];
                    }
                });
            }
        };
    args.forEach(function (arg) {
        increment(arg);
    });
    keys.forEach(function (key) {
        ret[key].pct = percent(ret[key].covered, ret[key].total);
    });

    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.removeDerivedInfo"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>removeDerivedInfo (coverage)](#apidoc.element.istanbul.utils.removeDerivedInfo)
- description and source-code
```javascript
function removeDerivedInfo(coverage) {
    Object.keys(coverage).forEach(function (k) {
        delete coverage[k].l;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.summarizeCoverage"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>summarizeCoverage (coverage)](#apidoc.element.istanbul.utils.summarizeCoverage)
- description and source-code
```javascript
function summarizeCoverage(coverage) {
    var fileSummary = [];
    Object.keys(coverage).forEach(function (key) {
        fileSummary.push(summarizeFileCoverage(coverage[key]));
    });
    return mergeSummaryObjects.apply(null, fileSummary);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.summarizeFileCoverage"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>summarizeFileCoverage (fileCoverage)](#apidoc.element.istanbul.utils.summarizeFileCoverage)
- description and source-code
```javascript
function summarizeFileCoverage(fileCoverage) {
    var ret = blankSummary();
    addDerivedInfoForFile(fileCoverage);
    ret.lines = computeSimpleTotals(fileCoverage, 'l');
    ret.functions = computeSimpleTotals(fileCoverage, 'f', 'fnMap');
    ret.statements = computeSimpleTotals(fileCoverage, 's', 'statementMap');
    ret.branches = computeBranchTotals(fileCoverage);
    ret.linesCovered = fileCoverage.l;
    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.istanbul.utils.toYUICoverage"></a>[function <span class="apidocSignatureSpan">istanbul.utils.</span>toYUICoverage (coverage)](#apidoc.element.istanbul.utils.toYUICoverage)
- description and source-code
```javascript
function toYUICoverage(coverage) {
    var ret = {};

    addDerivedInfo(coverage);

    Object.keys(coverage).forEach(function (k) {
        var fileCoverage = coverage[k],
            lines = fileCoverage.l,
            functions = fileCoverage.f,
            fnMap = fileCoverage.fnMap,
            o;

        o = ret[k] = {
            lines: {},
            calledLines: 0,
            coveredLines: 0,
            functions: {},
            calledFunctions: 0,
            coveredFunctions: 0
        };
        Object.keys(lines).forEach(function (k) {
            o.lines[k] = lines[k];
            o.coveredLines += 1;
            if (lines[k] > 0) {
                o.calledLines += 1;
            }
        });
        Object.keys(functions).forEach(function (k) {
            var name = fnMap[k].name + ':' + fnMap[k].line;
            o.functions[name] = functions[k];
            o.coveredFunctions += 1;
            if (functions[k] > 0) {
                o.calledFunctions += 1;
            }
        });
    });
    return ret;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
