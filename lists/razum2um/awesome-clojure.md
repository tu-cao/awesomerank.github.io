---
layout: default
title: Awesome Rank for razum2um/awesome-clojure
---

<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
---
# Awesome Clojure [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★67308](https://github.com/sindresorhus/awesome)

- [Awesome products in Clojure](#awesome-products-in-clojure)
  - [LightTable (IDE)](http://lighttable.com/)
  - [Nightcode (IDE)](https://sekao.net/nightcode/)
  - [Riemann (Monitoring)](http://riemann.io/)
  - [Puppet Server](https://github.com/puppetlabs/puppet-server)
  - [PuppetDB ★220](https://github.com/puppetlabs/puppetdb)
  - [Metabase ★6887](https://github.com/metabase/metabase)
  - [Avi (vim rewrite) ★191](https://github.com/maitria/avi)
  - [Liquid (Text Editor) ★130](https://github.com/mogenslund/liquid)
- [Languages written with Clojure](#languages-written-with-clojure)
  - [jank ★55](https://github.com/jeaye/jank)
  - [lux ★826](https://github.com/LuxLang/lux)
  - [mal](https://github.com/kanaka/mal/tree/master/clojure)
  - [scheje](https://github.com/turbopape/scheje)
- [Awesome tools in Clojure](#awesome-tools-in-clojure)
  - [Web Framework](#web-framework)
  - [Dependency injection](#dependency-injection)
  - [Build Automation and Package management](#build-automation-and-package-management)
  - [Version Control Management](#version-control-management)
  - [Date and Time](#date-and-time)
  - [GUI](#gui)
  - [Audio](#audio)
  - [HTTP](#http)
  - [Database](#database)
  - [Connection pools](#connection-pools)
  - [Structural Migrations](#structural-migrations)
  - [Redis](#redis)
  - [JSON](#json)
  - [ORM and SQL generation](#orm-and-sql-generation)
  - [Security](#security)
  - [RESTful API](#restful-api)
  - [Emails](#emails)
  - [HTML Manipulation](#html-manipulation)
  - [Data Validation](#data-validation)
  - [Type System](#type-system)
  - [Pattern Matching](#pattern-matching)
  - [Async processing](#async-processing)
  - [Monads](#monads)
  - [WebSocket](#websocket)
  - [Testing](#testing)
  - [Webdriver automation](#webdriver-automation)
  - [Code Analysis and Linter](#code-analysis-and-linter)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Machine Learning](#machine-learning)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Parsing](#parsing)
  - [Reflection](#reflection)
  - [Editor Plugins](#editor-plugins)
  - [Documentation](#documentation)
  - [Literate Programming](#literate-programming)
  - [Archives and Compression](#archives-and-compression)
  - [Miscellaneous](#miscellaneous)
  - [Debugging tools](#debugging)
  - [CI](#ci)
  - [Project Management](#project-management)

- [Resources](#resources)
  - [Guides](#guides)
  - [Websites](#websites)
  - [Twitter](#twitter)
  - [Exercises](#exercises)


## Web Framework

*Actually don't search rails/django here, but compose them by yourself*

  * [Web Non-Framework ★17](https://github.com/webnf/webnf)
  * [Luminus](http://www.luminusweb.net/)
  * [Joodo ★3 ⏳3Y](https://github.com/slagyr/joodoweb)
  * [Coils](https://github.com/zubairq/AppShare)
  * [Duct](https://github.com/weavejester/duct)
  * [Pedestal ★1817](https://github.com/pedestal/pedestal)
  * [Datsys ★153](https://github.com/metasoarous/datsys)
  * [yada ★489](https://github.com/juxt/yada)
  * [Hoplon](http://hoplon.io/)

## Dependency injection

*Managed lifecycle of stateful objects*

  * [Component ★1438](https://github.com/stuartsierra/component)
  * [System ★488](https://github.com/danielsz/system)
  * [mount ★661](https://github.com/tolitius/mount)

## Build Automation and Package management

*Libraries for project build automation and package/dependency management.*

  * [Leiningen ★5604](https://github.com/technomancy/leiningen)
  * [Boot ★1322](https://github.com/boot-clj/boot)
  * [lucid.distribute](http://docs.caudate.me/lucidity/lucid-distribute.html)
  * [lucid.package](http://docs.caudate.me/lucidity/lucid-package.html)

## Version Control Management

*Code utilities for interacting with VCS software*

  * [lucid.git](http://docs.caudate.me/lucidity/lucid-git.html)

## Date and Time

*Libraries for working with dates and times.*

  * [clj-time ★586](https://github.com/clj-time/clj-time)

## GUI

  * [fx-clj ★84 ⏳1Y](https://github.com/aaronc/fx-clj)
  * [seesaw ★1143](https://github.com/daveray/seesaw)

## Audio

  * [Overtone](http://overtone.github.io/)
  * [Alda ★2733](https://github.com/alda-lang/alda)

## HTTP

*Libraries for working with HTTP.*

  * [clj-http ★1113](https://github.com/dakrone/clj-http)
  * [http-kit](http://www.http-kit.org/)
  * [ring ★2342](https://github.com/ring-clojure/ring)
  * [kvlt ★45](https://github.com/nervous-systems/kvlt)

## Database

*Databases and database client libraries*

  * [Datomic](http://www.datomic.com/)
  * [clojure.jdbc ★87](https://github.com/funcool/clojure.jdbc)
  * [cravendb ★51 ⏳3Y](https://github.com/robashton/cravendb)
  * [Mongo](http://clojuremongodb.info/)
  * [Monglorious](https://baumandm.github.io/monglorious/)
  * [RethinkDB ★174](https://github.com/apa512/clj-rethinkdb)
  * [ElasticSearch](http://clojureelasticsearch.info/)
  * [Neo4j](http://clojureneo4j.info/)

## Connection pools

*Database connection pools*

  * [hikari-cp ★183](https://github.com/tomekw/hikari-cp)

## Structural Migrations

*Keeps database and others in sync*

  * [Lobos ★264](https://github.com/budu/lobos)
  * [Ragtime ★370](https://github.com/weavejester/ragtime)
  * [Joplin ★253](https://github.com/juxt/joplin)
  * [Migratus ★241](https://github.com/yogthos/migratus)
  * [Drift ★113](https://github.com/macourtney/drift)

## Redis

  * [carmine ★737](https://github.com/ptaoussanis/carmine)

## JSON

  * [cheshire ★970](https://github.com/dakrone/cheshire)

## Database Cli

## ORM and SQL generation

*DSL for SQL generation.*

  * [Korma](http://sqlkorma.com/)
  * [stch-library/sql ★23 ⏳1Y](https://github.com/stch-library/sql)
  * [sqlingvo ★147](https://github.com/r0man/sqlingvo)
  * [honeysql ★730](https://github.com/jkk/honeysql)
  * [Toucan ★136](https://github.com/metabase/toucan)

## Security

*Authentication, authorization and other security related libraries.*

  * [Buddy ★562](https://github.com/funcool/buddy)
  * [Friend ★1093](https://github.com/cemerick/friend)
  * [bolt ★125 ⏳2Y](https://github.com/juxt/bolt)

## RESTful API

*Libraries for developing RESTful APIs.*

  * [Liberator](http://clojure-liberator.github.io/liberator/)
  * [compojure-api ★712](https://github.com/metosin/compojure-api)
  * [Friboo ★107](https://github.com/zalando/friboo)
  * [yada ★489](https://github.com/juxt/yada)
  * [router ★73](https://github.com/darkleaf/router)

## Emails

  * [postal ★399](https://github.com/drewr/postal)

## HTML Manipulation

*Libraries for working with HTML.*

  * [Enlive](https://github.com/cgrand/enlive/wiki)
  * [hiccup ★1623](https://github.com/weavejester/hiccup)
  * [clostache ★268 ⏳1Y](https://github.com/fhd/clostache)
  * [selmer ★541](https://github.com/yogthos/Selmer)

## Data Validation

*Libraries for validating data.*

  * [Validateur](http://clojurevalidations.info/)
  * [Prismatic's schema ★1780](https://github.com/plumatic/schema)
  * [domaintypes ★5 ⏳2Y](https://github.com/friemen/domaintypes)
  * [Bouncer ★309](https://github.com/leonardoborges/bouncer)
  * [clova ★9 ⏳1Y](https://github.com/markwoodhall/clova)
  * [Orchestra ★139](https://github.com/jeaye/orchestra)

## Type System
*Optional type system for Clojure*

  * [core.typed ★950](https://github.com/clojure/core.typed)

## Pattern Matching

  * [core.match ★790](https://github.com/clojure/core.match)
  * [Verbal-Exprejon ★90 ⏳1Y](https://github.com/GuillaumeBadi/Verbal-Exprejon)
  * [defun ★336 ⏳1Y](https://github.com/killme2008/defun)
  * [cats.match ★30](https://github.com/zalando/cats.match)
  * [Akar ★152](https://github.com/missingfaktor/akar)

## Async processing

  * [core.async ★1421](https://github.com/clojure/core.async)
  * [pulsar ★777](https://github.com/puniverse/pulsar)
  * [lamina ★735 ⏳2Y](https://github.com/ztellman/lamina)
  * [aleph ★1880](https://github.com/ztellman/aleph)

## Monads

  * [cats ★583](https://github.com/funcool/cats)
  * [algo.monads ★341](https://github.com/clojure/algo.monads)

## WebSocket

  * [Sente ★1248](https://github.com/ptaoussanis/sente)

## Testing

  * [Expectations](http://jayfields.com/expectations/)
  * [Midje ★1311](https://github.com/marick/Midje)
  * [lucid.unit](http://docs.caudate.me/lucidity/lucid-unit.html)

## Webdriver automation

  * [Etaoin ★54](https://github.com/igrishaev/etaoin)

## Code Analysis and Linter

  * [Slamhound ★366](https://github.com/technomancy/slamhound)
  * [eastwood ★720](https://github.com/jonase/eastwood)
  * [kibit ★1312](https://github.com/jonase/kibit)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)
  * [yagni ★149 ⏳1Y](https://github.com/venantius/yagni)
  * [lein-bikeshed ★130](https://github.com/dakrone/lein-bikeshed)
  * [spectrum ★334](https://github.com/arohner/spectrum)
  * [cloverage ★266](https://github.com/cloverage/cloverage)

## Science and Data Analysis

*Libraries, extended REPLs, and other tools for scientific and statistical data
anylysis and visualization.*

  * [Incanter ★1922](https://github.com/incanter/incanter)
  * [Cascalog](http://cascalog.org/)
  * [Onyx ★1578](https://github.com/onyx-platform/onyx)
  * [sparklling ★308](https://github.com/gorillalabs/sparkling)
  * [flambo ★522](https://github.com/yieldbot/flambo)
  * [Neanderthal ★417](https://github.com/uncomplicate/neanderthal)
  * [lucid.graph](http://docs.caudate.me/lucidity/lucid-graph.html)
  * [Streaming Histograms ★131 ⏳1Y](https://github.com/bigmlcom/histogram)
  * [Gorilla REPL](http://gorilla-repl.org/)  

## Machine Learning

  * [clj-ml ★138 ⏳1Y](https://github.com/antoniogarrote/clj-ml)
  * [cortex ★810](https://github.com/thinktopic/cortex)
  * [clj-bigml ★48](https://github.com/bigmlcom/clj-bigml)
  * [Clatern ★66 ⏳2Y](https://github.com/rinuboney/clatern)
  * [Deeplearning4j ★7294](https://github.com/deeplearning4j/deeplearning4j)
  * [Enclog ★136 ⏳1Y](https://github.com/jimpil/enclog)
  * [Infer ★161 ⏳1Y](https://github.com/aria42/infer)
  * [k9 ★92 ⏳2Y](https://github.com/gigasquid/k9)
  * [lambda-ml ★24](https://github.com/cloudkj/lambda-ml)
  * [Statistiker ★52 ⏳2Y](https://github.com/clojurewerkz/statistiker)
  * [Synaptic ★87 ⏳1Y](https://github.com/japonophile/synaptic)

## Computer Vision

  * [clj-tesseract ★44 ⏳1Y](https://github.com/antoniogarrote/clj-tesseract)
  * [vision](http://nakkaya.com/vision.html)

## Natural Language Processing

  * [clojure-opennlp ★632](https://github.com/dakrone/clojure-opennlp)
  * [postagga](https://github.com/turbopape/postagga)

## Parsing

  * [Instaparse ★1833](https://github.com/Engelberg/instaparse)
  * [duckling](https://github.com/wit-ai/duckling)
  
## Exceptions and Error Handling
  * [Perseverance ★84](https://github.com/grammarly/perseverance)
  * [Dire ★472 ⏳1Y](https://github.com/MichaelDrogalis/dire)
  
## Reflection
*Libraries for improved code reflection and object introspection

  * [hara.reflect](docs.caudate.me/hara/hara-reflect.html)
  * [lucid.mind](http://docs.caudate.me/lucidity/lucid-mind.html)
  * [lucid.query](http://docs.caudate.me/lucidity/lucid-query.html)

## Editor Plugins

  * [CIDER (Emacs) ★2210](https://github.com/clojure-emacs/cider)
  * [smartparens (Emacs) ★888](https://github.com/Fuco1/smartparens)
  * [rainbow-delimiters (Emacs) ★202](https://github.com/Fanael/rainbow-delimiters)
  * [aggressive-indent (Emacs) ★350](https://github.com/Malabarba/aggressive-indent-mode)
  * [vim-fireplace (Vim) ★1269](https://github.com/tpope/vim-fireplace)
  * [vim-redl (Vim) ★106 ⏳2Y](https://github.com/dgrnbrg/vim-redl)
  * [vim-leiningen (Vim) ★135](https://github.com/tpope/vim-salve)
  * [rainbow_parentheses.vim (Vim) ★159](https://github.com/junegunn/rainbow_parentheses.vim)
  * [Cursive (IntelliJ)](https://cursive-ide.com/)
  * [Parinfer (multiple editors)](http://shaunlebron.github.io/parinfer/)

## Documentation

*Utilities and libraries for (non-LP) code and project documentation*

 * [lucid.publish](http://docs.caudate.me/lucidity/lucid-publish.html)

## Literate Programming

  * [marginalia ★628](https://github.com/gdeer81/marginalia)
  * [klipse ★1363](https://github.com/viebel/klipse)

## Archives and Compression

  * [swindon (java.util.zip wrapper) ★2 ⏳3Y](https://github.com/AeroNotix/swindon)

## Miscellaneous

 * [clj-tuple ★172 ⏳2Y](https://github.com/ztellman/clj-tuple)
 * [slingshot ★488 ⏳1Y](https://github.com/scgilardi/slingshot)
 * [lucid.system](http://docs.caudate.me/lucidity/lucid-system.html)

## Debugging

  * [debugger ★192 ⏳1Y](https://github.com/razum2um/clj-debugger)
  * [debug-repl ★138 ⏳4Y](https://github.com/GeorgeJahad/debug-repl)
  * [ritz ★329 ⏳4Y](https://github.com/pallet/ritz)
  * [redl ★30 ⏳3Y](https://github.com/dgrnbrg/redl)
  * [limit-break ★16 ⏳5Y](https://github.com/technomancy/limit-break)
  * [spyscope ★385](https://github.com/dgrnbrg/spyscope)
  * [aprint ★111 ⏳2Y](https://github.com/razum2um/aprint)
  * [pretty ★355](https://github.com/AvisoNovate/pretty)
  * [prone ★446](https://github.com/magnars/prone)
  * [figwheel ★2260](https://github.com/bhauman/lein-figwheel)

## CI

  * [lambdacd ★490](https://github.com/flosell/lambdacd)

## Guides

  * [The Clojure Style Guide ★2636](https://github.com/bbatsov/clojure-style-guide)
  * [Clojure Distilled](http://yogthos.github.io/ClojureDistilled.html)
  * [clojure-cookbook ★1835](https://github.com/clojure-cookbook/clojure-cookbook)
  * [A Brief Beginner's Guide To Clojure](http://www.unexpected-vortices.com/clojure/brief-beginners-guide/index.html)
  * [Clojure for the Brave and True](http://www.braveclojure.com/)
  * [Clojure from the ground up](https://aphyr.com/tags/Clojure-from-the-ground-up)
  * [Clojure by Example](https://kimh.github.io/clojure-by-example/)

## Websites

  * [Clojure](http://clojure.org/)
  * [Clojure Slack](http://clojurians.net/)
  * [clojuredocs](http://clojuredocs.org)
  * [crossclj](https://crossclj.info/)
  * [clojure-doc](http://clojure-doc.org/)
  * [Grimoire](http://conj.io/)
  * [The Clojure Toolbox](http://www.clojure-toolbox.com/)
  * [InstaREPL Online](http://web.clojurerepl.com/)
  * [ZEEF/Clojure](https://clojure.zeef.com/vlad.bokov)
  * [Try Clojure](http://www.tryclj.com/)

## Twitter

  * [oss_clj](https://twitter.com/oss_clj)

## Exercises

  * [Clojure Koans](http://clojurekoans.com)
  * [Wonderland Clojure Katas ★536](https://github.com/gigasquid/wonderland-clojure-katas)
  * [Clojure Katas](http://clojurekatas.org)
  * [4clojure](http://www.4clojure.com/)
  * [exercism.io](http://exercism.io/languages/clojure)
  * [Clojurecademy](https://clojurecademy.com)

## Project Management
  
  * [milestones](https://github.com/turbopape/milestones)
---
<p align="center">
	This list is a copy of <a href="https://github.com/razum2um/awesome-clojure">razum2um/awesome-clojure</a> with ranks
</p>
