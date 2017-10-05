# Awesome Crystal
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/veelenga/awesome-crystal.svg)](https://travis-ci.org/veelenga/awesome-crystal)

A curated list of awesome Crystal code and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).
The goal is to have projects mostly stable and useful for the community.

Search [Crystal Shards](https://crystalshards.xyz) or follow announcements [Crystal [ANN]](https://crystal-ann.com) for more.

Contributions are welcome. Please take a quick look at the [contribution guidelines](https://github.com/veelenga/awesome-crystal/blob/master/.github/CONTRIBUTING.md) first.

* [Awesome Crystal](#awesome-crystal)
  * [Algorithms and Data structures](#algorithms-and-data-structures)
  * [Api Builders](#api-builders)
  * [C Bindings](#c-bindings)
  * [Caching](#caching)
  * [Cli Builders](#cli-builders)
  * [Cli Utils](#cli-utils)
  * [Configuration](#configuration)
  * [Converters](#converters)
  * [Data Generators](#data-generators)
  * [Database Drivers/Clients](#database-driversclients)
  * [Database Tools](#database-tools)
  * [Development Tools](#development-tools)
  * [Email](#email)
  * [Environment Management](#environment-management)
  * [Examples and funny stuff](#examples-and-funny-stuff)
  * [Feature Flipping](#feature-flipping)
  * [Framework Components](#framework-components)
  * [Game Development](#game-development)
  * [HTML/XML parsing](#htmlxml-parsing)
  * [HTTP](#http)
  * [Image Processing](#image-processing)
  * [Implementations/Compilers](#implementationscompilers)
  * [Logging and monitoring](#logging-and-monitoring)
  * [Machine Learning](#machine-learning)
  * [Markdown/Text Processors](#markdowntext-processors)
  * [Misc](#misc)
  * [Networking](#networking)
  * [ORM/ODM Extensions](#ormodm-extensions)
  * [Package Management](#package-management)
  * [Processes and Threads](#processes-and-threads)
  * [Project Generators](#project-generators)
  * [Queue](#queue)
  * [Routing](#routing)
  * [Scheduling](#scheduling)
  * [Science and Data analysis](#science-and-data-analysis)
  * [Search](#search)
  * [Task management](#task-management)
  * [Template Engine](#template-engine)
  * [Testing](#testing)
  * [Third-party APIs](#third-party-apis)
  * [Virtualization](#virtualization)
  * [Web Frameworks](#web-frameworks)
  * [Web Servers](#web-servers)
* [Community](#community)
* [Resources](#resources)
  * [Official Documentation Translations](#official-documentation-translations)
* [Services and Apps](#services-and-apps)
* [Tools](#tools)
  * [DevOps](#devops)
  * [Editor Plugins](#editor-plugins)
  * [Shell Plugins](#shell-plugins)

## Algorithms and Data structures
 * [aho_corasick](https://github.com/chenkovsky/aho_corasick) - AhoCorasick algorithm ![](https://img.shields.io/github/last-commit/chenkovsky/aho_corasick.svg)
 * [crystal-diff](https://github.com/MakeNowJust/crystal-diff) - A Crystal sequence differencing implementation ![](https://img.shields.io/github/last-commit/MakeNowJust/crystal-diff.svg)
 * [crystal-linked-list](https://github.com/abvdasker/crystal-linked-list) - Implementation of Linked List ![](https://img.shields.io/github/last-commit/abvdasker/crystal-linked-list.svg)
 * [crystaledge](https://github.com/unn4m3d/crystaledge) - A pure Vector Math library ![](https://img.shields.io/github/last-commit/unn4m3d/crystaledge.svg)
 * [crystalg](https://github.com/TobiasGSmollett/crystalg) - A Generic Algorithm Library ![](https://img.shields.io/github/last-commit/TobiasGSmollett/crystalg.svg)
 * [crystalline](https://github.com/jtomschroeder/crystalline) - A collection of containers and algorithms ![](https://img.shields.io/github/last-commit/jtomschroeder/crystalline.svg)
 * [delimiter_tree](https://github.com/drujensen/delimiter_tree) - A tree structure that is built using a delimiter ![](https://img.shields.io/github/last-commit/drujensen/delimiter_tree.svg)
 * [edits.cr](https://github.com/tcrouch/edits.cr) - Collection of edit distance algorithms ![](https://img.shields.io/github/last-commit/tcrouch/edits.cr.svg)
 * [hash_ring](https://github.com/TobiasGSmollett/hash_ring) - An Implementation of Consistent Hash Ring ![](https://img.shields.io/github/last-commit/TobiasGSmollett/hash_ring.svg)
 * [miller_rabin](https://github.com/kuende/miller_rabin) - Implements [Miller-Rabin](https://en.wikibooks.org/wiki/Algorithm_Implementation/Mathematics/Primality_Testing) algorithm to check if a number is prime ![](https://img.shields.io/github/last-commit/kuende/miller_rabin.svg)
 * [multiset.cr](https://github.com/tcrouch/multiset.cr) - Implementation of a multiset ![](https://img.shields.io/github/last-commit/tcrouch/multiset.cr.svg)
 * [murmur3](https://github.com/kuende/murmur3) - Implementation of Murmur3 hash algorithm used by Cassandra ![](https://img.shields.io/github/last-commit/kuende/murmur3.svg)
 * [radix](https://github.com/luislavena/radix) - Radix Tree implementation ![](https://img.shields.io/github/last-commit/luislavena/radix.svg)
 * [ranger](https://github.com/akwiatkowski/ranger) - Range object operation library ![](https://img.shields.io/github/last-commit/akwiatkowski/ranger.svg)
 * [ternary_search_tree](https://github.com/johnjansen/ternary_search_tree) - Ternary Search Tree ![](https://img.shields.io/github/last-commit/johnjansen/ternary_search_tree.svg)
 * [text](https://github.com/johnjansen/text) - A collection of text algorithms ![](https://img.shields.io/github/last-commit/johnjansen/text.svg)

## Api Builders
 * [crystal_api](https://github.com/akwiatkowski/crystal_api) - Simple PostgreSQL REST API with Rails devise-like auth ![](https://img.shields.io/github/last-commit/akwiatkowski/crystal_api.svg)
 * [kemal-rest-api](https://github.com/blocknotes/kemal-rest-api) - A library to create RESTful API with Kemal ![](https://img.shields.io/github/last-commit/blocknotes/kemal-rest-api.svg)

## C bindings
 * [asound-cr](https://github.com/TamasSzekeres/asound-cr) - Bindings for ALSA/libasound ![](https://img.shields.io/github/last-commit/TamasSzekeres/asound-cr.svg)
 * [cairo-cr](https://github.com/TamasSzekeres/cairo-cr) - Bindings for [Cairo](https://cairographics.org/) graphics library ![](https://img.shields.io/github/last-commit/TamasSzekeres/cairo-cr.svg)
 * [clang.cr](https://github.com/ysbaddaden/clang.cr) - Libclang bindings ![](https://img.shields.io/github/last-commit/ysbaddaden/clang.cr.svg)
 * [crass](https://github.com/vonKingsley/crass) - Bindings for libsass ![](https://img.shields.io/github/last-commit/vonKingsley/crass.svg)
 * [crt.cr](https://github.com/maiha/crt.cr) - Bindings for libncursesw and crt ![](https://img.shields.io/github/last-commit/maiha/crt.cr.svg)
 * [crystal-gsl](https://github.com/ruivieira/crystal-gsl) - GNU Scientific Library bindings ![](https://img.shields.io/github/last-commit/ruivieira/crystal-gsl.svg)
 * [curl-crystal](https://github.com/blocknotes/curl-crystal) - Bindings for [libcurl](https://curl.haxx.se/libcurl/) ![](https://img.shields.io/github/last-commit/blocknotes/curl-crystal.svg)
 * [duktape.cr](https://github.com/jessedoyle/duktape.cr) - Bindings for the [Duktape](https://github.com/svaarala/duktape) javascript engine ![](https://img.shields.io/github/last-commit/jessedoyle/duktape.cr.svg)
 * [glfw](https://github.com/lirith-engine/glfw) - GLFW bindings ![](https://img.shields.io/github/last-commit/lirith-engine/glfw.svg)
 * [gphoto2.cr](https://github.com/Sija/gphoto2.cr) - Bindings for the [libgphoto2](http://www.gphoto.org/) library ![](https://img.shields.io/github/last-commit/Sija/gphoto2.cr.svg)
 * [icu.cr](https://github.com/olbat/icu.cr) - Bindings for the [ICU](http://site.icu-project.org/) library ![](https://img.shields.io/github/last-commit/olbat/icu.cr.svg)
 * [java.cr](https://github.com/ysbaddaden/java.cr) - Java Native Interface (JNI) bindings (and generator) ![](https://img.shields.io/github/last-commit/ysbaddaden/java.cr.svg)
 * [libnotify.cr](https://github.com/splattael/libnotify.cr) - Bindings for Libnotify ![](https://img.shields.io/github/last-commit/splattael/libnotify.cr.svg)
 * [libui.cr](https://github.com/Fusion/libui.cr) - Bindings for [libui](https://github.com/andlabs/libui) ![](https://img.shields.io/github/last-commit/Fusion/libui.cr.svg)
 * [pcap.cr](https://github.com/maiha/pcap.cr) - Bindings for libpcap ![](https://img.shields.io/github/last-commit/maiha/pcap.cr.svg)
 * [posix](https://github.com/ysbaddaden/posix) - POSIX/C bindings ![](https://img.shields.io/github/last-commit/ysbaddaden/posix.svg)
 * [soundfile](https://github.com/mjago/soundfile) - Bindings for [libsndfile](http://www.mega-nerd.com/libsndfile/) library ![](https://img.shields.io/github/last-commit/mjago/soundfile.svg)
 * [ssh2.cr](https://github.com/datanoise/ssh2.cr) - Bindings for libssh2 library ![](https://img.shields.io/github/last-commit/datanoise/ssh2.cr.svg)
 * [termbox-crystal](https://github.com/andrewsuzuki/termbox-crystal) - Bindings and extension library for [termbox](https://github.com/nsf/termbox) (terminal UI library) ![](https://img.shields.io/github/last-commit/andrewsuzuki/termbox-crystal.svg)
 * [x11-cr](https://github.com/TamasSzekeres/x11-cr) - X11 bindings ![](https://img.shields.io/github/last-commit/TamasSzekeres/x11-cr.svg)

## Caching
 * [bloom_filter](https://github.com/crystal-community/bloom_filter) - Implementation of Bloom filter ![](https://img.shields.io/github/last-commit/crystal-community/bloom_filter.svg)
 * [bojack](https://github.com/marceloboeira/bojack) - A non-reliable in-memory key-value store ![](https://img.shields.io/github/last-commit/marceloboeira/bojack.svg)
 * [cache-hash](https://github.com/samueleaton/cache-hash) - A key/value store where entries expire after a specified interval ![](https://img.shields.io/github/last-commit/samueleaton/cache-hash.svg)
 * [crystal-memcached](https://github.com/comandeo/crystal-memcached) - Implementation of a memcached client ![](https://img.shields.io/github/last-commit/comandeo/crystal-memcached.svg)
 * [Nuummite](https://github.com/CodeSteak/Nuummite) - A tiny persistent embedded key-value store ![](https://img.shields.io/github/last-commit/CodeSteak/Nuummite.svg)

## Cli Builders
 * [admiral](https://github.com/jwaldrip/admiral.cr) - A robust DSL for writing command line interfaces ![](https://img.shields.io/github/last-commit/jwaldrip/admiral.cr.svg)
 * [cli](https://github.com/mosop/cli) - Library for building command-line interface applications ![](https://img.shields.io/github/last-commit/mosop/cli.svg)
 * [clim](https://github.com/at-grandpa/clim) - Slim command line interface builder ![](https://img.shields.io/github/last-commit/at-grandpa/clim.svg)
 * [commander](https://github.com/mrrooijen/commander) - Command-line interface builder ![](https://img.shields.io/github/last-commit/mrrooijen/commander.svg)
 * [completion](https://github.com/f/completion) - Easy command line completion engine ![](https://img.shields.io/github/last-commit/f/completion.svg)
 * [optarg](https://github.com/mosop/optarg) - Yet another library for parsing command-line options and arguments ![](https://img.shields.io/github/last-commit/mosop/optarg.svg)

## Cli Utils
 * [dl](https://github.com/creadone/dl) - Simple utility for download files by URLs from list ![](https://img.shields.io/github/last-commit/creadone/dl.svg)
 * [progress](https://github.com/askn/progress) - [==..] Progress bar ![](https://img.shields.io/github/last-commit/askn/progress.svg)
 * [progress_bar.cr](https://github.com/TPei/progress_bar.cr) - A simple and customizable progress bar ![](https://img.shields.io/github/last-commit/TPei/progress_bar.cr.svg)
 * [spinner](https://github.com/askn/spinner) - Terminal Spinner ![](https://img.shields.io/github/last-commit/askn/spinner.svg)
 * [terminal_table.cr](https://github.com/benoist/terminal_table.cr) - Simple ASCII table generator ![](https://img.shields.io/github/last-commit/benoist/terminal_table.cr.svg)
 * [todo](https://github.com/Nephos/todo) - Todo list working in command line ![](https://img.shields.io/github/last-commit/Nephos/todo.svg)

## Configuration
 * [cr-dotenv](https://github.com/gdotdesign/cr-dotenv) - Loads .env file ![](https://img.shields.io/github/last-commit/gdotdesign/cr-dotenv.svg)
 * [crystal-toml](https://github.com/manastech/crystal-toml) - TOML parser ![](https://img.shields.io/github/last-commit/manastech/crystal-toml.svg)
 * [dockerfile.cr](https://github.com/keplersj/dockerfile.cr) - Dockerfile Parsing Library ![](https://img.shields.io/github/last-commit/keplersj/dockerfile.cr.svg)
 * [zq](https://github.com/colstrom/zq) - Command-line ZPL processor ![](https://img.shields.io/github/last-commit/colstrom/zq.svg)

## Converters
 * [human_file_size.cr](https://github.com/johnjansen/human_file_size.cr) - JSON & YAML mapping converter for human file sizes in serialized data ![](https://img.shields.io/github/last-commit/johnjansen/human_file_size.cr.svg)
 * [moola](https://github.com/dorkrawk/moola) - Library for dealing with money and conversion (inspired by [RubyMoney](https://github.com/RubyMoney/money)) ![](https://img.shields.io/github/last-commit/dorkrawk/moola.svg)
 * [ms](https://github.com/SuperPaintman/ms) - Library to easily convert various time formats to milliseconds and milliseconds to human readable format ![](https://img.shields.io/github/last-commit/SuperPaintman/ms.svg)
 * [sass.cr](https://github.com/straight-shoota/sass.cr) - Compile SASS/SCSS to CSS ([libsass](https://github.com/sass/libsass/) binding) ![](https://img.shields.io/github/last-commit/straight-shoota/sass.cr.svg)
 * [time_format.cr](https://github.com/vladfaust/time_format.cr) - Convert time in human readable format with ease ![](https://img.shields.io/github/last-commit/vladfaust/time_format.cr.svg)
 * [turkish-number](https://github.com/izniburak/turkish-number) - Turn integers into the Turkish words ![](https://img.shields.io/github/last-commit/izniburak/turkish-number.svg)
 * [wkhtmltopdf-crystal](https://github.com/blocknotes/wkhtmltopdf-crystal) - Bindings / wrapper for libwkhtmltox (HTML to PDF / image converter) ![](https://img.shields.io/github/last-commit/blocknotes/wkhtmltopdf-crystal.svg)

## Data Generators
 * [faker](https://github.com/askn/faker) - A library for generating fake data ![](https://img.shields.io/github/last-commit/askn/faker.svg)
 * [hashids.cr](https://github.com/splattael/hashids.cr) - A library to generate YouTube-like ids from one or many numbers ![](https://img.shields.io/github/last-commit/splattael/hashids.cr.svg)

## Database Drivers/Clients
 * [arangocr](https://github.com/solisoft/arangocr) - ArangoDB client ![](https://img.shields.io/github/last-commit/solisoft/arangocr.svg)
 * [crystal-db](https://github.com/crystal-lang/crystal-db) - Common db api ![](https://img.shields.io/github/last-commit/crystal-lang/crystal-db.svg)
 * [crystal-monetdb-libmapi](https://github.com/puppetpies/crystal-monetdb-libmapi) - Bindings for MonetDB ![](https://img.shields.io/github/last-commit/puppetpies/crystal-monetdb-libmapi.svg)
 * [crystal-mysql](https://github.com/crystal-lang/crystal-mysql) - MySQL connector for Crystal ![](https://img.shields.io/github/last-commit/crystal-lang/crystal-mysql.svg)
 * [crystal-pg](https://github.com/will/crystal-pg) - A Postgres driver ![](https://img.shields.io/github/last-commit/will/crystal-pg.svg)
 * [crystal-redis](https://github.com/stefanwille/crystal-redis) - Full featured Redis client ![](https://img.shields.io/github/last-commit/stefanwille/crystal-redis.svg)
 * [crystal-sqlite3](https://github.com/crystal-lang/crystal-sqlite3) - SQLite3 bindings ![](https://img.shields.io/github/last-commit/crystal-lang/crystal-sqlite3.svg)
 * [eventql-crystal](https://github.com/measurechina/eventql-crystal) - EventQL driver ![](https://img.shields.io/github/last-commit/measurechina/eventql-crystal.svg)
 * [influxdb.cr](https://github.com/jeromegn/influxdb.cr) - InfluxDB driver ![](https://img.shields.io/github/last-commit/jeromegn/influxdb.cr.svg)
 * [leveldb](https://github.com/crystal-community/leveldb) - Crystal bindings for LevelDB ![](https://img.shields.io/github/last-commit/crystal-community/leveldb.svg)
 * [mongo.cr](https://github.com/datanoise/mongo.cr) - Binding for MongoDB C driver ![](https://img.shields.io/github/last-commit/datanoise/mongo.cr.svg)
 * [rethinkdb.cr](https://github.com/CubosTecnologia/rethinkdb.cr) - RethinkDB Driver ![](https://img.shields.io/github/last-commit/CubosTecnologia/rethinkdb.cr.svg)
 * [rocksdb.cr](https://github.com/maiha/rocksdb.cr) - RocksDB client ![](https://img.shields.io/github/last-commit/maiha/rocksdb.cr.svg)

## Database Tools
 * [crecto-admin](https://github.com/Crecto/crecto-admin) - Admin dashboard for Crecto and your database ![](https://img.shields.io/github/last-commit/Crecto/crecto-admin.svg)
 * [micrate](https://github.com/juanedi/micrate) - Database migration tool ![](https://img.shields.io/github/last-commit/juanedi/micrate.svg)

## Development Tools
 * [guardian](https://github.com/f/guardian) - File change watcher for Crystal and Non-Crystal libs ![](https://img.shields.io/github/last-commit/f/guardian.svg)
 * [kemal-watcher](https://github.com/faustinoaq/kemal-watcher) - Kemal plugin to watch files and live-reload the browser ![](https://img.shields.io/github/last-commit/faustinoaq/kemal-watcher.svg)
 * [sentry](https://github.com/samueleaton/sentry) - Watches src files, rebuilds/reruns application on file changes ![](https://img.shields.io/github/last-commit/samueleaton/sentry.svg)
 * [sentry-run](https://github.com/faustinoaq/sentry-run) - Reload code changes using Sentry.run ![](https://img.shields.io/github/last-commit/faustinoaq/sentry-run.svg)
 * [Warden](https://github.com/diggersheep/warden) - Watches files, run command and a git command if succeed on file changes ![](https://img.shields.io/github/last-commit/diggersheep/warden.svg)
 * [watcher](https://github.com/faustinoaq/watcher) - Watch file changes using File.stat ![](https://img.shields.io/github/last-commit/faustinoaq/watcher.svg)

## Email
 * [crystal-email](https://github.com/arcage/crystal-email) - Simple e-mail sending library ![](https://img.shields.io/github/last-commit/arcage/crystal-email.svg)
 * [CrystalEmail](https://github.com/Nephos/CrystalEmail) - A RFC compliant Email validator ![](https://img.shields.io/github/last-commit/Nephos/CrystalEmail.svg)
 * [devmail](https://github.com/tijn/devmail) - A combined SMTP/POP3-server with volatile mail storage ![](https://img.shields.io/github/last-commit/tijn/devmail.svg)
 * [sendgrid.cr](https://github.com/dlanileonardo/sendgrid.cr) - Simple Sendgrid Client ![](https://img.shields.io/github/last-commit/dlanileonardo/sendgrid.cr.svg)

## Environment Management
 * [asdf-crystal](https://github.com/marciogm/asdf-crystal) - Plugin for asdf version manager ![](https://img.shields.io/github/last-commit/marciogm/asdf-crystal.svg)
 * [crenv](https://github.com/pine/crenv) - Crystal version manager ![](https://img.shields.io/github/last-commit/pine/crenv.svg)
 * [rcm.cr](https://github.com/maiha/rcm.cr) - Redis Cluster Manager ![](https://img.shields.io/github/last-commit/maiha/rcm.cr.svg)

## Examples and funny stuff
 * [breakout.cr](https://github.com/petoem/breakout.cr) - Breakout game written using crsfml ![](https://img.shields.io/github/last-commit/petoem/breakout.cr.svg)
 * [chuck-norris-holy-quotes](https://github.com/codenoid/chuck-norris-holy-quotes) - Chuck Norris holy quotes ![](https://img.shields.io/github/last-commit/codenoid/chuck-norris-holy-quotes.svg)
 * [clamp](https://github.com/johnjansen/clamp) - Clamp any Comparable ![](https://img.shields.io/github/last-commit/johnjansen/clamp.svg)
 * [crsfml-examples](https://github.com/oprypin/crsfml-examples) - Simple games made with CrSFML ![](https://img.shields.io/github/last-commit/oprypin/crsfml-examples.svg)
 * [crystal-benchmarks-game](https://github.com/kostya/crystal-benchmarks-game) - The Computer Language Benchmarks Game ![](https://img.shields.io/github/last-commit/kostya/crystal-benchmarks-game.svg)
 * [crystal-by-example](https://github.com/askn/crystal-by-example) - Crystal By Example ![](https://img.shields.io/github/last-commit/askn/crystal-by-example.svg)
 * [Crystal-Maze](https://github.com/Demonstrandum/Crystal-Maze) - A* Path finding for PNG mazes ![](https://img.shields.io/github/last-commit/Demonstrandum/Crystal-Maze.svg)
 * [crystal-mysql-crud-example](https://github.com/codenoid/crystal-mysql-crud-example) - Crystal MySQL CRUD example ![](https://img.shields.io/github/last-commit/codenoid/crystal-mysql-crud-example.svg)
 * [crystal-patterns](https://github.com/crystal-community/crystal-patterns) - Examples of GOF patters ![](https://img.shields.io/github/last-commit/crystal-community/crystal-patterns.svg)
 * [crystal_samples](https://github.com/tbpgr/crystal_samples) - Variety of Crystal samples ![](https://img.shields.io/github/last-commit/tbpgr/crystal_samples.svg)
 * [crystalized_ruby](https://github.com/phoffer/crystalized_ruby) - Native Ruby extensions written in Crystal ![](https://img.shields.io/github/last-commit/phoffer/crystalized_ruby.svg)
 * [docker-kemal](https://github.com/ianblenke/docker-kemal) - An example Dockerized Crystal Kemal project ![](https://img.shields.io/github/last-commit/ianblenke/docker-kemal.svg)
 * [exercism-crystal](https://github.com/exercism/crystal) - Exercism exercises ![](https://img.shields.io/github/last-commit/exercism/crystal.svg)
 * [jihantoro-cr-mysql](https://github.com/codenoid/jihantoro-cr-mysql) - Crystal MySQL from scratch sample app ![](https://img.shields.io/github/last-commit/codenoid/jihantoro-cr-mysql.svg)
 * [jihantoro.sd](https://github.com/codenoid/jihantoro.sd) - Crystal & Kemal version of Serdar Dogruyol blog ![](https://img.shields.io/github/last-commit/codenoid/jihantoro.sd.svg)
 * [kemal-chat](https://github.com/sdogruyol/kemal-chat) - Build realtime applications with Kemal and WebSocket ![](https://img.shields.io/github/last-commit/sdogruyol/kemal-chat.svg)
 * [kemal-heroku-example](https://github.com/cagataycali/kemal-heroku-example) - This repository shows, how you can publish your open source apps which powered kemal framework publish as heroku app in seconds ![](https://img.shields.io/github/last-commit/cagataycali/kemal-heroku-example.svg)
 * [kemal-mysql-blog](https://github.com/codenoid/kemal-mysql-blog) - Blog written with Crystal, Kemal and MySQL ![](https://img.shields.io/github/last-commit/codenoid/kemal-mysql-blog.svg)
 * [kemal-react-chat](https://github.com/f/kemal-react-chat) - Build Realtime Web applications with Kemal and React ![](https://img.shields.io/github/last-commit/f/kemal-react-chat.svg)
 * [kemal-react-pg-chat](https://github.com/Angarsk8/chat-app-demo) - Chat application developed with Kemal, React, ES2015 and PostgreSQL ![](https://img.shields.io/github/last-commit/Angarsk8/chat-app-demo.svg)
 * [kemal-ws-pg-todo-app](https://github.com/Angarsk8/kemal-ws-pg-todo-app) - Realtime Todo application developed with Kemal, Websockets, ES2015 and PostgreSQL ![](https://img.shields.io/github/last-commit/Angarsk8/kemal-ws-pg-todo-app.svg)
 * [kemal_elm_chat](https://github.com/kofno/kemal_elm_chat) - Simple chat server written with Kemal and Elm ![](https://img.shields.io/github/last-commit/kofno/kemal_elm_chat.svg)
 * [lattice-core-card-game](https://github.com/jasonl99/card_game) - A demo web app for (WebSocket-based) lattice-core ![](https://img.shields.io/github/last-commit/jasonl99/card_game.svg)
 * [medley](https://github.com/jwoertink/medley) - A mixture of music related methods ![](https://img.shields.io/github/last-commit/jwoertink/medley.svg)
 * [os-crystal](https://github.com/lbguilherme/os-crystal) - x86 Kernel implemented in Crystal ![](https://img.shields.io/github/last-commit/lbguilherme/os-crystal.svg)
 * [realtime-todo-app](https://github.com/Angarsk8/realtime-todo-app) - Realtime Todo application developed with Kemal, Websockets, React, ES2015 and PostgreSQL ![](https://img.shields.io/github/last-commit/Angarsk8/realtime-todo-app.svg)
 * [rocky](https://github.com/codingphasedotcom/rocky) - React Over Crystal Kemal and Yarn ![](https://img.shields.io/github/last-commit/codingphasedotcom/rocky.svg)
 * [try.cr](https://github.com/maiha/try.cr) - Try monad ![](https://img.shields.io/github/last-commit/maiha/try.cr.svg)

## Feature Flipping
 * [flipper](https://github.com/metaware/flipper) - Feature flipping/flags/rollouts. Supports multiple backends ![](https://img.shields.io/github/last-commit/metaware/flipper.svg)

## Framework Components
 * [artanis](https://github.com/ysbaddaden/artanis) - Sinatra-like DSL (abusing macros) ![](https://img.shields.io/github/last-commit/ysbaddaden/artanis.svg)
 * [cr-melon](https://github.com/gdotdesign/cr-melon) - Class based Http APIs ![](https://img.shields.io/github/last-commit/gdotdesign/cr-melon.svg)
 * [Crystal-DI](https://github.com/funk-yourself/crystal-di) - Lightweight DI Container ![](https://img.shields.io/github/last-commit/funk-yourself/crystal-di.svg)
 * [crystal-mime](https://github.com/spalger/crystal-mime) - Mimetypes for Crystal ![](https://img.shields.io/github/last-commit/spalger/crystal-mime.svg)
 * [graphql-crystal](https://github.com/ziprandom/graphql-crystal) - [Graphql](http://graphql.org) implementation ![](https://img.shields.io/github/last-commit/ziprandom/graphql-crystal.svg)
 * [kave](https://github.com/jwoertink/kave) - Kemal API Version Extension ![](https://img.shields.io/github/last-commit/jwoertink/kave.svg)
 * [kemal-auth-token](https://github.com/akwiatkowski/kemal-auth-token) - Kemal middleware to authentication via HTTP header token using JWT ![](https://img.shields.io/github/last-commit/akwiatkowski/kemal-auth-token.svg)
 * [kemal-flash](https://github.com/neovintage/kemal-flash) - Temporary storage between actions in Kemal ![](https://img.shields.io/github/last-commit/neovintage/kemal-flash.svg)
 * [kemal-monetdb](https://github.com/puppetpies/kemal-monetdb) - MonetDB Data connection for Kemal ![](https://img.shields.io/github/last-commit/puppetpies/kemal-monetdb.svg)
 * [kemal-redis](https://github.com/sdogruyol/kemal-redis) - Easily add Redis to Kemal ![](https://img.shields.io/github/last-commit/sdogruyol/kemal-redis.svg)
 * [kemal-session](https://github.com/kemalcr/kemal-session) - Session handler for Kemal ![](https://img.shields.io/github/last-commit/kemalcr/kemal-session.svg)
 * [kemalyst-i18n](https://github.com/TechMagister/kemalyst-i18n) - i18n support for Kemalyst ![](https://img.shields.io/github/last-commit/TechMagister/kemalyst-i18n.svg)
 * [mime-types.cr](https://github.com/jwaldrip/mime-types.cr) - A port of the Ruby MIME-types library ![](https://img.shields.io/github/last-commit/jwaldrip/mime-types.cr.svg)
 * [multi-auth](https://github.com/msa7/multi_auth) - Standardized multi-provider OAuth2 authentication (inspired by omniauth) ![](https://img.shields.io/github/last-commit/msa7/multi_auth.svg)
 * [phoenix.cr](https://github.com/dtcristo/phoenix.cr) - Phoenix Channels client ![](https://img.shields.io/github/last-commit/dtcristo/phoenix.cr.svg)
 * [request_id](https://github.com/SuperPaintman/request-id) - Middleware for generates / pick up a unique request ID for Crystal servers ![](https://img.shields.io/github/last-commit/SuperPaintman/request-id.svg)
 * [response_time](https://github.com/SuperPaintman/response-time) - Response time for Crystal servers (pure http server, kemal, etc.) ![](https://img.shields.io/github/last-commit/SuperPaintman/response-time.svg)
 * [spec-kemal](https://github.com/kemalcr/spec-kemal) - Easy testing for Kemal ![](https://img.shields.io/github/last-commit/kemalcr/spec-kemal.svg)
 * [tele-broadcast.cr](https://github.com/vladfaust/tele-broadcast.cr) - Broadcasting module for tele.cr ![](https://img.shields.io/github/last-commit/vladfaust/tele-broadcast.cr.svg)

## Game Development
 * [CrSFML](https://github.com/oprypin/crsfml) - Bindings to [SFML](https://www.sfml-dev.org/) multimedia/game library ![](https://img.shields.io/github/last-commit/oprypin/crsfml.svg)
 * [crystal-chipmunk](https://github.com/oprypin/crystal-chipmunk) - Bindings for [Chipmunk](http://chipmunk-physics.net/), a fast and lightweight 2D game physics library ![](https://img.shields.io/github/last-commit/oprypin/crystal-chipmunk.svg)
 * [flight-crusader](https://github.com/umurgdk/flight-crusader) - POC top down flight game ![](https://img.shields.io/github/last-commit/umurgdk/flight-crusader.svg)
 * [glove](https://github.com/ddfreyne/glove) - A library for gaming development ![](https://img.shields.io/github/last-commit/ddfreyne/glove.svg)
 * [inari](https://github.com/ddfreyne/inari) - A collection of games using Glove as the game engine ![](https://img.shields.io/github/last-commit/ddfreyne/inari.svg)
 * [medico](https://github.com/konovod/medico) - Game about a medieval doctor ![](https://img.shields.io/github/last-commit/konovod/medico.svg)
 * [mos_game](https://github.com/bararchy/mos_game) - Mini Offline Singleplayer game ![](https://img.shields.io/github/last-commit/bararchy/mos_game.svg)

## HTML/XML Parsing
 * [crystagiri](https://github.com/madeindjs/Crystagiri) - An Html Reader / parser like [Nokogiri](https://github.com/sparklemotion/nokogiri) Ruby gem ![](https://img.shields.io/github/last-commit/madeindjs/Crystagiri.svg)
 * [gumbo-crystal](https://github.com/blocknotes/gumbo-crystal) - Bindings for [Gumbo](https://github.com/google/gumbo-parser), an HTML5 parsing library made by Google ![](https://img.shields.io/github/last-commit/blocknotes/gumbo-crystal.svg)
 * [hq.cr](https://github.com/maiha/hq.cr) - Simple wrapper for crystal-xml ![](https://img.shields.io/github/last-commit/maiha/hq.cr.svg)
 * [modest](https://github.com/kostya/modest) - CSS selectors for HTML5 Parser myhtml ![](https://img.shields.io/github/last-commit/kostya/modest.svg)
 * [myhtml](https://github.com/kostya/myhtml) - Fast HTML5 Parser ![](https://img.shields.io/github/last-commit/kostya/myhtml.svg)

## HTTP
 * [cossack](https://github.com/crystal-community/cossack) - Simple flexible HTTP client ![](https://img.shields.io/github/last-commit/crystal-community/cossack.svg)
 * [crul](https://github.com/porras/crul) - Command line HTTP client ![](https://img.shields.io/github/last-commit/porras/crul.svg)
 * [cryload](https://github.com/sdogruyol/cryload) - HTTP benchmarking tool ![](https://img.shields.io/github/last-commit/sdogruyol/cryload.svg)
 * [halite](https://github.com/icyleaf/halite) - Yet another simple HTTP and REST client with a chainable API, built-in sessions and timeouts ![](https://img.shields.io/github/last-commit/icyleaf/halite.svg)
 * [helmet](https://github.com/EvanHahn/crystal-helmet) - Set security-related HTTP headers ![](https://img.shields.io/github/last-commit/EvanHahn/crystal-helmet.svg)
 * [http-multiserver.cr](https://github.com/vladfaust/http-multiserver.cr) - Mounting multiple servers via routes (a.k.a. URL mapping) ![](https://img.shields.io/github/last-commit/vladfaust/http-multiserver.cr.svg)
 * [http-protection](https://github.com/rogeriozambon/http-protection) - Protection against typical web attacks ![](https://img.shields.io/github/last-commit/rogeriozambon/http-protection.svg)
 * [http2](https://github.com/ysbaddaden/http2) - HTTP/2 Protocol Implementation ![](https://img.shields.io/github/last-commit/ysbaddaden/http2.svg)
 * [http_distributor](https://github.com/Nephos/http_distributor) - HTTP server which allows sneaky http requests ![](https://img.shields.io/github/last-commit/Nephos/http_distributor.svg)
 * [http_parser.cr](https://github.com/kostya/http_parser.cr) - Wrapper for [Http Parser lib](https://github.com/nodejs/http-parser) ![](https://img.shields.io/github/last-commit/kostya/http_parser.cr.svg)
 * [keyer_cr](https://github.com/danielpclark/keyer_cr) - Adds HTTP GET/POST parameter parsing as a Hash-like object ![](https://img.shields.io/github/last-commit/danielpclark/keyer_cr.svg)
 * [multipart.cr](https://github.com/RX14/multipart.cr) - Adds multipart and multipart/form-data support to the crystal standard library ![](https://img.shields.io/github/last-commit/RX14/multipart.cr.svg)
 * [resp-crystal](https://github.com/soveran/resp-crystal) - Lightweight RESP client ![](https://img.shields.io/github/last-commit/soveran/resp-crystal.svg)
 * [session](https://github.com/porras/session) - Cookie based sessions in Crystal HTTP applications ![](https://img.shields.io/github/last-commit/porras/session.svg)

## Image processing
 * [magickwand-crystal](https://github.com/blocknotes/magickwand-crystal) - Bindings for [MagickWand](https://www.imagemagick.org/script/magick-wand.php), the C interface for ImageMagick processing libraries ![](https://img.shields.io/github/last-commit/blocknotes/magickwand-crystal.svg)
 * [stumpy_gif](https://github.com/stumpycr/stumpy_gif) - Write (animated) GIF images ![](https://img.shields.io/github/last-commit/stumpycr/stumpy_gif.svg)
 * [stumpy_png](https://github.com/stumpycr/stumpy_png) - Read and write PNG images ![](https://img.shields.io/github/last-commit/stumpycr/stumpy_png.svg)

## Implementations/Compilers
 * [charly](https://github.com/charly-lang) - Charly Programming Language
 * [cltk](https://github.com/ziprandom/cltk) - A crystal port of the Ruby Language Toolkit ![](https://img.shields.io/github/last-commit/ziprandom/cltk.svg)
 * [cppize](https://github.com/unn4m3d/cppize) - Crystal-to-C++ transpiler ![](https://img.shields.io/github/last-commit/unn4m3d/cppize.svg)
 * [crisp](https://github.com/rhysd/Crisp) - Lisp dialect implemented with Crystal ![](https://img.shields.io/github/last-commit/rhysd/Crisp.svg)
 * [crow](https://github.com/geppetto-apps/crow) - Transpile/compile Crystal to [Flow](https://flow.org/) ![](https://img.shields.io/github/last-commit/geppetto-apps/crow.svg)
 * [myst-lang](https://github.com/myst-lang) - A practical, dynamic language designed to be written and understood as easily and efficiently as possible
 * [NuummiteOS](https://github.com/TheKernelCorp/NuummiteOS) - An OS written in Crystal as a Proof of Concept ![](https://img.shields.io/github/last-commit/TheKernelCorp/NuummiteOS.svg)
 * [onix](https://github.com/ozra/onyx-lang) - ONYX Programming Language ![](https://img.shields.io/github/last-commit/ozra/onyx-lang.svg)
 * [zir](https://github.com/tbrand/zir) - Realizes to write macros in any scripts into any languages ![](https://img.shields.io/github/last-commit/tbrand/zir.svg)

## Logging and monitoring
 * [crometheus](https://gitlab.com/ezrast/crometheus) - A [Prometheus](https://prometheus.io/) client library
 * [crystal-logreader](https://github.com/arcage/crystal-logreader) - Tailing log file ![](https://img.shields.io/github/last-commit/arcage/crystal-logreader.svg)
 * [fluent-logger-crystal](https://github.com/TobiasGSmollett/fluent-logger-crystal) - A structured logger for [Fluentd](https://www.fluentd.org/) ![](https://img.shields.io/github/last-commit/TobiasGSmollett/fluent-logger-crystal.svg)
 * [katip](https://github.com/guvencenanguvenal/katip) - JSONbase logger ![](https://img.shields.io/github/last-commit/guvencenanguvenal/katip.svg)
 * [statsd.cr](https://github.com/miketheman/statsd.cr) - [Statsd](https://github.com/etsy/statsd) client library ![](https://img.shields.io/github/last-commit/miketheman/statsd.cr.svg)
 * [syslog.cr](https://github.com/comandeo/syslog.cr) - Implementation of Syslog client ![](https://img.shields.io/github/last-commit/comandeo/syslog.cr.svg)

## Machine Learning
 * [ai4cr](https://github.com/drhuffman12/ai4cr) - Artificial Intelligence (based on https://github.com/SergioFierens/ai4r) ![](https://img.shields.io/github/last-commit/drhuffman12/ai4cr.svg)
 * [crystal-fann](https://github.com/NeuraLegion/crystal-fann) - FANN (Fast Artifical Neural Network) binding ![](https://img.shields.io/github/last-commit/NeuraLegion/crystal-fann.svg)
 * [crystal-learn](https://github.com/pbrusco/crystal-learn) - Sklearn-like machine-learning library ![](https://img.shields.io/github/last-commit/pbrusco/crystal-learn.svg)
 * [grey_matter](https://github.com/dorkrawk/grey_matter) - A basic artificial neural network library ![](https://img.shields.io/github/last-commit/dorkrawk/grey_matter.svg)
 * [machine](https://github.com/mathieulaporte/machine) - Simple machine learning algorithm ![](https://img.shields.io/github/last-commit/mathieulaporte/machine.svg)
 * [tensorflow.cr](https://github.com/fazibear/tensorflow.cr) - Bindings for [TensorFlow](https://github.com/tensorflow/tensorflow) ![](https://img.shields.io/github/last-commit/fazibear/tensorflow.cr.svg)

## Markdown/Text Processors
 * [html-pipeline](https://github.com/huacnlee/html-pipeline) - HTML processing filters and utilities ![](https://img.shields.io/github/last-commit/huacnlee/html-pipeline.svg)
 * [markd](https://github.com/icyleaf/markd) - Yet another markdown parser built for speed, Compliant to CommonMark specification ![](https://img.shields.io/github/last-commit/icyleaf/markd.svg)
 * [remarkdown](https://github.com/huacnlee/remarkdown) - GFM for Crystal ![](https://img.shields.io/github/last-commit/huacnlee/remarkdown.svg)

## Misc
 * [aasm.cr](https://github.com/veelenga/aasm.cr) - Easy to use finite state machine for Crystal classes ![](https://img.shields.io/github/last-commit/veelenga/aasm.cr.svg)
 * [accord](https://github.com/neovintage/accord) - Sharable validations for Crystal objects ![](https://img.shields.io/github/last-commit/neovintage/accord.svg)
 * [acorn](https://github.com/rmosolgo/acorn) - State Machine Compiler for Crystal ![](https://img.shields.io/github/last-commit/rmosolgo/acorn.svg)
 * [any_hash.cr](https://github.com/Sija/any_hash.cr) - Recursive Hash with better JSON::Any included ![](https://img.shields.io/github/last-commit/Sija/any_hash.cr.svg)
 * [circuit_breaker](https://github.com/TPei/circuit_breaker) - Implementation of the circuit breaker pattern ![](https://img.shields.io/github/last-commit/TPei/circuit_breaker.svg)
 * [clamd.cr](https://github.com/RX14/clamd.cr) - Client for the clamd antivirus server ![](https://img.shields.io/github/last-commit/RX14/clamd.cr.svg)
 * [crystal-binary_parser](https://github.com/DanSnow/crystal-binary_parser) - Binary parser ![](https://img.shields.io/github/last-commit/DanSnow/crystal-binary_parser.svg)
 * [crystal-futures](https://github.com/dhruvrajvanshi/crystal-futures) - Future type implementation ![](https://img.shields.io/github/last-commit/dhruvrajvanshi/crystal-futures.svg)
 * [crz](https://github.com/dhruvrajvanshi/crz) - Functional programming library ![](https://img.shields.io/github/last-commit/dhruvrajvanshi/crz.svg)
 * [denetmen](https://github.com/izniburak/denetmen) - Useful micro validator / check library ![](https://img.shields.io/github/last-commit/izniburak/denetmen.svg)
 * [emoji.cr](https://github.com/veelenga/emoji.cr) - Emoji library ![](https://img.shields.io/github/last-commit/veelenga/emoji.cr.svg)
 * [hoop](https://github.com/0x73/hoop) - Building native OSX apps ![](https://img.shields.io/github/last-commit/0x73/hoop.svg)
 * [html_builder](https://github.com/crystal-lang/html_builder) - DSL for creating HTML ![](https://img.shields.io/github/last-commit/crystal-lang/html_builder.svg)
 * [i18n.cr](https://github.com/vladfaust/i18n.cr) - Internationalization shard ![](https://img.shields.io/github/last-commit/vladfaust/i18n.cr.svg)
 * [immutable](https://github.com/lucaong/immutable) - Implementation of thread-safe, persistent, immutable collections ![](https://img.shields.io/github/last-commit/lucaong/immutable.svg)
 * [inflector.cr](https://github.com/phoffer/inflector.cr) - Singularize, pluralize, camelize, etc (port from ActiveSupport) ![](https://img.shields.io/github/last-commit/phoffer/inflector.cr.svg)
 * [kreal](https://github.com/f/kreal) - Model sharing & RPC library built on and works with Kemal seamlessly ![](https://img.shields.io/github/last-commit/f/kreal.svg)
 * [lirith](https://github.com/lirith-engine/lirith) - Graphics engine ![](https://img.shields.io/github/last-commit/lirith-engine/lirith.svg)
 * [manual-generator](https://github.com/blocknotes/manual-generator) - Tool to generate PDF manuals from documentation sites ![](https://img.shields.io/github/last-commit/blocknotes/manual-generator.svg)
 * [ramlrenderer](https://github.com/beno/ramlrenderer) - HTML doc builder for RAML 1.0 ![](https://img.shields.io/github/last-commit/beno/ramlrenderer.svg)
 * [raytracer](https://github.com/l3kn/raytracer) - CPU Raytracer with examples ![](https://img.shields.io/github/last-commit/l3kn/raytracer.svg)
 * [shell.cr](https://github.com/dmytro/shell.cr) - Small simplistic helper class for executing shell commands ![](https://img.shields.io/github/last-commit/dmytro/shell.cr.svg)
 * [syscall.cr](https://github.com/kubo39/syscall.cr) - Raw syscall interface ![](https://img.shields.io/github/last-commit/kubo39/syscall.cr.svg)
 * [tren](https://github.com/sdogruyol/tren) - Give your SQL some love ![](https://img.shields.io/github/last-commit/sdogruyol/tren.svg)
 * [ulid](https://github.com/SuperPaintman/ulid) - Universally Unique Lexicographically Sortable Identifier (ULID) ![](https://img.shields.io/github/last-commit/SuperPaintman/ulid.svg)
 * [wikicr](https://github.com/Nephos/wikicr) - Wiki using git to manage revisions ![](https://img.shields.io/github/last-commit/Nephos/wikicr.svg)

## Networking
 * [amqp.cr](https://github.com/datanoise/amqp.cr) - AMQP 0.9.1 client with RabbitMQ extensions ![](https://img.shields.io/github/last-commit/datanoise/amqp.cr.svg)
 * [bson.cr](https://github.com/jeromegn/bson.cr) - Native BSON implementation ![](https://img.shields.io/github/last-commit/jeromegn/bson.cr.svg)
 * [CrystalIrc](https://github.com/Meoowww/CrystalIrc) - IRC implementation (Client, Server, Bots) ![](https://img.shields.io/github/last-commit/Meoowww/CrystalIrc.svg)
 * [fast_irc.cr](https://github.com/RX14/fast_irc.cr) - Fast IRC parser/generator ![](https://img.shields.io/github/last-commit/RX14/fast_irc.cr.svg)
 * [ipaddress.cr](https://github.com/Sija/ipaddress.cr) - Library to handle IPv4 and IPv6 addresses ![](https://img.shields.io/github/last-commit/Sija/ipaddress.cr.svg)
 * [jwt](https://github.com/crystal-community/jwt) - Implementation of JWT (JSON Web Token) ![](https://img.shields.io/github/last-commit/crystal-community/jwt.svg)
 * [msgpack-crystal](https://github.com/crystal-community/msgpack-crystal) - MessagePack library ![](https://img.shields.io/github/last-commit/crystal-community/msgpack-crystal.svg)
 * [transfer_more](https://github.com/Nephos/transfer_more) - Clone of transfer.sh to uploads files ![](https://img.shields.io/github/last-commit/Nephos/transfer_more.svg)

## ORM/ODM Extensions
 * [active_record.cr](https://github.com/waterlink/active_record.cr) - Active Record pattern implementation ![](https://img.shields.io/github/last-commit/waterlink/active_record.cr.svg)
 * [core](https://github.com/vladfaust/core.cr) - Pure, transparent and efficient ORM ![](https://img.shields.io/github/last-commit/vladfaust/core.cr.svg)
 * [crecto](https://github.com/Crecto/crecto) - Database wrapper, based on Ecto ![](https://img.shields.io/github/last-commit/Crecto/crecto.svg)
 * [granite-orm](https://github.com/amberframework/granite-orm) - ORM for Postgres, Mysql, Sqlite ![](https://img.shields.io/github/last-commit/amberframework/granite-orm.svg)
 * [jennifer.cr](https://github.com/imdrasil/jennifer.cr) - Active Record pattern implementation with flexible query chainable builder and migration system ![](https://img.shields.io/github/last-commit/imdrasil/jennifer.cr.svg)
 * [ohm-crystal](https://github.com/soveran/ohm-crystal) - Object-hash mapping library for Redis ![](https://img.shields.io/github/last-commit/soveran/ohm-crystal.svg)
 * [redis-tsv.cr](https://github.com/maiha/redis-tsv.cr) - Import and export data from Redis in TSV format ![](https://img.shields.io/github/last-commit/maiha/redis-tsv.cr.svg)
 * [selenite-db](https://github.com/xdougx/selenite-db) - A simple persistency-model based library ![](https://img.shields.io/github/last-commit/xdougx/selenite-db.svg)
 * [stal-crystal](https://github.com/soveran/stal-crystal) - Set algebra solver for Redis ![](https://img.shields.io/github/last-commit/soveran/stal-crystal.svg)
 * [topaz](https://github.com/topaz-crystal/topaz) - A simple and useful db wrapper ![](https://img.shields.io/github/last-commit/topaz-crystal/topaz.svg)

## Package Management
 * [CRelease](https://github.com/elorest/crelease) - Version and git tag manager that makes shard releases easy ![](https://img.shields.io/github/last-commit/elorest/crelease.svg)
 * [shards](https://github.com/crystal-lang/shards) - Dependency manager for the Crystal ![](https://img.shields.io/github/last-commit/crystal-lang/shards.svg)

## Processes and Threads
 * [neph](https://github.com/tbrand/neph) - A modern command line job processor that can execute jobs concurrently ![](https://img.shields.io/github/last-commit/tbrand/neph.svg)
 * [promise](https://github.com/jwaldrip/promise.cr) - A Promise Implementation ![](https://img.shields.io/github/last-commit/jwaldrip/promise.cr.svg)

## Project Generators
 * [bindgencr](https://github.com/TechMagister/bindgencr) - Generator of bindings based on castxml output ![](https://img.shields.io/github/last-commit/TechMagister/bindgencr.svg)
 * [crystal_lib](https://github.com/crystal-lang/crystal_lib) - Automatic binding generator for native libraries ![](https://img.shields.io/github/last-commit/crystal-lang/crystal_lib.svg)
 * [fez](https://github.com/jwoertink/fez) - A Kemal application generator ![](https://img.shields.io/github/last-commit/jwoertink/fez.svg)
 * [kgen](https://github.com/kemalyst/kemalyst-generator) - Kemalyst command line tool for console, init, generate (scaffolding), and watch ![](https://img.shields.io/github/last-commit/kemalyst/kemalyst-generator.svg)
 * [libgen](https://github.com/olbat/libgen) - Automatic bindings generator configured using JSON/YAML files ![](https://img.shields.io/github/last-commit/olbat/libgen.svg)
 * [skaf](https://github.com/elorest/skaf) - Scaffolding for Kemal ![](https://img.shields.io/github/last-commit/elorest/skaf.svg)
 * [wasp](https://github.com/icyleaf/wasp) - Static Site Generator ![](https://img.shields.io/github/last-commit/icyleaf/wasp.svg)

## Queue
 * [dispatch](https://github.com/bmulvihill/dispatch) - In memory asynchronous job processing ![](https://img.shields.io/github/last-commit/bmulvihill/dispatch.svg)
 * [disque-cr](https://github.com/foca/disque-cr) - Client for [Disque](https://github.com/antirez/disque) queueing system ![](https://img.shields.io/github/last-commit/foca/disque-cr.svg)
 * [sidekiq.cr](https://github.com/mperham/sidekiq.cr) - Simple, efficient job processing ![](https://img.shields.io/github/last-commit/mperham/sidekiq.cr.svg)

## Routing
 * [beryl](https://github.com/luislavena/beryl) - Action-focused HTTP routing library ![](https://img.shields.io/github/last-commit/luislavena/beryl.svg)
 * [crouter](https://github.com/jreinert/crouter) - A standalone router ![](https://img.shields.io/github/last-commit/jreinert/crouter.svg)
 * [router.cr](https://github.com/tbrand/router.cr) - Minimum but powerful http router for HTTP::Server ![](https://img.shields.io/github/last-commit/tbrand/router.cr.svg)
 * [toro](https://github.com/soveran/toro) - Tree Oriented Routing ![](https://img.shields.io/github/last-commit/soveran/toro.svg)

## Scheduling
 * [cron_scheduler](https://github.com/kostya/cron_scheduler) - Job scheduler with crontab patterns ![](https://img.shields.io/github/last-commit/kostya/cron_scheduler.svg)
 * [quartz](https://github.com/andrewhamon/quartz) - Crystal clear timers ![](https://img.shields.io/github/last-commit/andrewhamon/quartz.svg)
 * [schedule.cr](https://github.com/hugoabonizio/schedule.cr) - Run periodic tasks ![](https://img.shields.io/github/last-commit/hugoabonizio/schedule.cr.svg)

## Science and Data analysis
 * [linalg](https://github.com/konovod/linalg) - Linear algebra library inspired by MATLAB and SciPy.linalg ![](https://img.shields.io/github/last-commit/konovod/linalg.svg)
 * [predict.cr](https://github.com/RX14/predict.cr) - Satellite prediction library using the sgp4 model ![](https://img.shields.io/github/last-commit/RX14/predict.cr.svg)
 * [scorystal](https://github.com/asafschers/scorystal) - Scoring API for PMML - supports RF and GBM ![](https://img.shields.io/github/last-commit/asafschers/scorystal.svg)
 * [stats](https://github.com/Nephos/stats) - An expressive implementation of statistical distributions ![](https://img.shields.io/github/last-commit/Nephos/stats.svg)

## Search
 * [hermes](https://github.com/imdrasil/hermes.cr) - Data Mapper pattern implementation for ElastiSearch ![](https://img.shields.io/github/last-commit/imdrasil/hermes.cr.svg)
 * [query-builder](https://github.com/izniburak/query-builder) - Sql Query Builder library ![](https://img.shields.io/github/last-commit/izniburak/query-builder.svg)
 * [query.cr](https://github.com/waterlink/query.cr) - Query abstraction ![](https://img.shields.io/github/last-commit/waterlink/query.cr.svg)
 * [soegen](https://github.com/Ragmaanir/soegen) - Elasticsearch client for Crystal similar to the stretcher gem for ruby ![](https://img.shields.io/github/last-commit/Ragmaanir/soegen.svg)

## Task management
 * [cake](https://github.com/axvm/cake) - Production-ready Make-like utility tool ![](https://img.shields.io/github/last-commit/axvm/cake.svg)
 * [sam](https://github.com/imdrasil/sam.cr) - Another one Rake-like task manager with namespacing and arguments system ![](https://img.shields.io/github/last-commit/imdrasil/sam.cr.svg)

## Template Engine
 * [crikey](https://github.com/domgetter/crikey) - Templating engine inspired by [Hiccup](https://github.com/weavejester/hiccup) ![](https://img.shields.io/github/last-commit/domgetter/crikey.svg)
 * [crinja](https://github.com/straight-shoota/crinja) - An implementation of the [Jinja2 template engine](http://jinja.pocoo.org/) ![](https://img.shields.io/github/last-commit/straight-shoota/crinja.svg)
 * [crustache](https://github.com/MakeNowJust/crustache) - [{{Mustache}}](https://mustache.github.io) for Crystal ![](https://img.shields.io/github/last-commit/MakeNowJust/crustache.svg)
 * [Kilt](https://github.com/jeromegn/kilt) - Abstraction layer for template engines ![](https://img.shields.io/github/last-commit/jeromegn/kilt.svg)
 * [Slang](https://github.com/jeromegn/slang) - Lightweight, terse, templating language inspired by Ruby's Slim ![](https://img.shields.io/github/last-commit/jeromegn/slang.svg)
 * [teeplate](https://github.com/mosop/teeplate) - A library for rendering multiple template files ![](https://img.shields.io/github/last-commit/mosop/teeplate.svg)
 * [temel](https://github.com/f/temel) - Extensible HTML::Builder alternative for Crystal, supports custom tag definitions ![](https://img.shields.io/github/last-commit/f/temel.svg)

## Testing
 * [crotest](https://github.com/emancu/crotest) - A tiny and simple test framework ![](https://img.shields.io/github/last-commit/emancu/crotest.svg)
 * [microtest](https://github.com/Ragmaanir/microtest) - Small opinionated testing library focusing on power asserts ![](https://img.shields.io/github/last-commit/Ragmaanir/microtest.svg)
 * [minitest.cr](https://github.com/ysbaddaden/minitest.cr) - Library for unit tests and assertions ![](https://img.shields.io/github/last-commit/ysbaddaden/minitest.cr.svg)
 * [mocks.cr](https://github.com/waterlink/mocks.cr) - Mocking library for Crystal ![](https://img.shields.io/github/last-commit/waterlink/mocks.cr.svg)
 * [spec2-mocks](https://github.com/waterlink/spec2-mocks.cr) - An adapter of mocks.cr for spec2.cr ![](https://img.shields.io/github/last-commit/waterlink/spec2-mocks.cr.svg)
 * [spec2.cr](https://github.com/waterlink/spec2.cr) - Enhanced testing library ![](https://img.shields.io/github/last-commit/waterlink/spec2.cr.svg)
 * [timecop.cr](https://github.com/TobiasGSmollett/timecop.cr) - Library for mocking with `Time.now`. Inspired by [timecop ruby gem](https://github.com/travisjeffery/timecop) ![](https://img.shields.io/github/last-commit/TobiasGSmollett/timecop.cr.svg)
 * [webmock.cr](https://github.com/manastech/webmock.cr) - Library for stubbing `HTTP::Client` requests ![](https://img.shields.io/github/last-commit/manastech/webmock.cr.svg)

## Third-party APIs
 * [aws-signer.cr](https://github.com/beanieboi/aws-signer.cr) - This library signs your HTTP requests using AWS v4 ![](https://img.shields.io/github/last-commit/beanieboi/aws-signer.cr.svg)
 * [awscr-s3](https://github.com/taylorfinnell/awscr-s3) - AWS S3 interface ![](https://img.shields.io/github/last-commit/taylorfinnell/awscr-s3.svg)
 * [awscr-signer](https://github.com/taylorfinnell/awscr-signer) - Sign HTTP::Request objects and generate presigned post forms ![](https://img.shields.io/github/last-commit/taylorfinnell/awscr-signer.svg)
 * [bugsnag.cr](https://github.com/gewo/bugsnag.cr) - Bugsnag exception notifier and sidekiq middleware ![](https://img.shields.io/github/last-commit/gewo/bugsnag.cr.svg)
 * [crystal-darksky](https://github.com/sb89/crystal-darksky) - Wrapper for the [Dark Sky](https://darksky.net) API ![](https://img.shields.io/github/last-commit/sb89/crystal-darksky.svg)
 * [crystal-github](https://github.com/felipeelias/crystal-github) - Wrapper for the [Github](https://github.com/) API ![](https://img.shields.io/github/last-commit/felipeelias/crystal-github.svg)
 * [crystal-monzo](https://github.com/barisbalic/crystal-monzo) - A client for the [Monzo API](https://monzo.com/docs/) ![](https://img.shields.io/github/last-commit/barisbalic/crystal-monzo.svg)
 * [crystal-ovh](https://github.com/ovh/crystal-ovh) - Lightweight Crystal wrapper around [OVH](https://eu.api.ovh.com/)'s API ![](https://img.shields.io/github/last-commit/ovh/crystal-ovh.svg)
 * [crystal-swapi](https://github.com/sb89/crystal-swapi) - Star Wars API (SWAPI) wrapper ![](https://img.shields.io/github/last-commit/sb89/crystal-swapi.svg)
 * [crystal_slack](https://github.com/manastech/crystal_slack) - A tool that parses Slack slash commands or send incoming web hooks ![](https://img.shields.io/github/last-commit/manastech/crystal_slack.svg)
 * [dotacr](https://github.com/azah/dotacr) - Wrapper for Valve's DotA API ![](https://img.shields.io/github/last-commit/azah/dotacr.svg)
 * [gitlab.cr](https://github.com/icyleaf/gitlab.cr) - GitLab API wrapper ![](https://img.shields.io/github/last-commit/icyleaf/gitlab.cr.svg)
 * [google_maps_api](https://github.com/fridgerator/google_maps_api) - Google Maps API ![](https://img.shields.io/github/last-commit/fridgerator/google_maps_api.svg)
 * [hncr](https://github.com/Gangwolf/hncr) - A Hacker News API wrapper ![](https://img.shields.io/github/last-commit/Gangwolf/hncr.svg)
 * [nexmo-crystal](https://github.com/timcraft/nexmo-crystal) - [Nexmo REST API](https://developer.nexmo.com/) client ![](https://img.shields.io/github/last-commit/timcraft/nexmo-crystal.svg)
 * [ocean_kit](https://github.com/osfx/ocean_kit) - [Digital Ocean v2 API](https://developers.digitalocean.com/documentation/v2) client ![](https://img.shields.io/github/last-commit/osfx/ocean_kit.svg)
 * [open_exchange_rates](https://github.com/osfx/open_exchange_rates) - A library to access [Open Exchange Rates](https://openexchangerates.org/) API ![](https://img.shields.io/github/last-commit/osfx/open_exchange_rates.svg)
 * [pinboard.cr](https://github.com/oz/pinboard.cr) - [Pinboard](https://pinboard.in) API ![](https://img.shields.io/github/last-commit/oz/pinboard.cr.svg)
 * [raven.cr](https://github.com/sija/raven.cr) - Raven is a client for [Sentry](https://github.com/getsentry/sentry) ![](https://img.shields.io/github/last-commit/sija/raven.cr.svg)
 * [slack.cr](https://github.com/DougEverly/slack.cr) - A Slack [Real Time Messaging API](https://api.slack.com/rtm) WebSocket client library ![](https://img.shields.io/github/last-commit/DougEverly/slack.cr.svg)
 * [spotify.cr](https://github.com/marceloboeira/spotify.cr) - A library to access the Spotify API ![](https://img.shields.io/github/last-commit/marceloboeira/spotify.cr.svg)
 * [tele.cr](https://github.com/vladfaust/tele.cr) - A *convenient* wrapper for the Telegram Bot API ![](https://img.shields.io/github/last-commit/vladfaust/tele.cr.svg)
 * [telegram_bot](https://github.com/hangyas/telegram_bot) - A wrapper for the Telegram Bot API ![](https://img.shields.io/github/last-commit/hangyas/telegram_bot.svg)

## Virtualization
 * [baked_file_system](https://github.com/schovi/baked_file_system) - Virtual file system implementation ![](https://img.shields.io/github/last-commit/schovi/baked_file_system.svg)
 * [rcpu](https://github.com/ddfreyne/rcpu) - A virtual machine emulator and assembler ![](https://img.shields.io/github/last-commit/ddfreyne/rcpu.svg)

## Web Frameworks
 * [amber](https://github.com/amberframework/amber) - Open source efficient and cohesive web application framework ![](https://img.shields.io/github/last-commit/amberframework/amber.svg)
 * [amethyst](https://github.com/Codcore/Amethyst) - A Rails inspired web-framework ![](https://img.shields.io/github/last-commit/Codcore/Amethyst.svg)
 * [kemal](https://github.com/kemalcr/kemal) - Lightning Fast, Super Simple web framework. Inspired by Sinatra ![](https://img.shields.io/github/last-commit/kemalcr/kemal.svg)
 * [lattice-core](https://github.com/jasonl99/lattice-core) - A WebSocket-first object-oriented framework (based on Kemal) ![](https://img.shields.io/github/last-commit/jasonl99/lattice-core.svg)
 * [luckyframework](https://github.com/luckyframework) - Fast, maintainable and confidence boosting web framework
 * [mustafa](https://github.com/guvencenanguvenal/mustafa) - Simple MVC framework ![](https://img.shields.io/github/last-commit/guvencenanguvenal/mustafa.svg)
 * [raze](https://github.com/samueleaton/raze) - Modular, light web framework ![](https://img.shields.io/github/last-commit/samueleaton/raze.svg)

## Web Servers
 * [fast-http-server](https://github.com/sdogruyol/fast-http-server) - Super fast, zero configuration command line HTTP Server ![](https://img.shields.io/github/last-commit/sdogruyol/fast-http-server.svg)
 * [kamber](https://github.com/f/kamber) - Blog server based on Kemal ![](https://img.shields.io/github/last-commit/f/kamber.svg)
 * [prax.cr](https://github.com/ysbaddaden/prax.cr) - Rack proxy server for development ![](https://img.shields.io/github/last-commit/ysbaddaden/prax.cr.svg)
 * [serve](https://github.com/SuperPaintman/serve) - Command line static HTTP server ![](https://img.shields.io/github/last-commit/SuperPaintman/serve.svg)

# Community
 * [Crystal weekly newsletters](http://crystalweekly.com/)
 * [Gitter](https://gitter.im/crystal-lang/crystal)
 * [Google Group](https://groups.google.com/forum/?fromgroups#!forum/crystal-lang)
 * [IRC](http://irc.lc/freenode/crystal-lang) - #crystal-lang on Freenode
 * [Metaruby](https://metaruby.com/c/crystal-forum) - Crystal Forum on Metaruby
 * [Reddit](https://www.reddit.com/r/crystal_programming/)
 * [Slack Group](http://crystal.pine.moe/en/)
 * [Stackoverflow](https://stackoverflow.com/tags/crystal-lang/info)

# Resources
 * [Crystal for Rubyists](http://www.crystalforrubyists.com/) - free book to bootstrap your Crystal journey
 * [crystal-lang.org](https://crystal-lang.org) - Official language site

## Official Documentation Translations
 * [br.crystal-lang.org](http://br.crystal-lang.org/) - Brazilian
 * [ja.crystal-lang.org](http://ja.crystal-lang.org/) - Japanese
 * [kr.crystal-lang.org](https://kr.crystal-lang.org/) - Korean
 * [ru.crystal-lang.org](http://ru.crystal-lang.org/) - Russian
 * [tw.crystal-lang.org](http://tw.crystal-lang.org/) - Chinese Traditional

# Services and Apps
 * [carc.in](https://carc.in/) - A web service that runs your code and displays the result
 * [Crank](https://github.com/arktisklada/crank) - A Procfile-based application manager (like Foreman) ![](https://img.shields.io/github/last-commit/arktisklada/crank.svg)
 * [Crystal [ANN]](https://crystal-ann.com) - Announce new project, blog post, version update or any other Crystal work
 * [crystalshards.herokuapp.com](https://crystalshards.herokuapp.com/), [crystalshards.xyz](http://crystalshards.xyz/) - Web services that list all available Crystal shards
 * [DeBot](https://github.com/jhass/DeBot) - IRC bot written in Crystal ![](https://img.shields.io/github/last-commit/jhass/DeBot.svg)
 * [Ficha](https://github.com/codenoid/ficha) - A super secret chat app, for any body who needs privacy ![](https://img.shields.io/github/last-commit/codenoid/ficha.svg)
 * [icr](https://github.com/crystal-community/icr) - Interactive console for Crystal (like IRB for Ruby) ![](https://img.shields.io/github/last-commit/crystal-community/icr.svg)
 * [nes](https://github.com/romeroadrian/nes.cr) - A NES emulator ![](https://img.shields.io/github/last-commit/romeroadrian/nes.cr.svg)
 * [shards.rocks](https://shards.rocks/) - Service that manages dependencies inspired by [Gemnasium](https://gemnasium.com/) and [David](https://david-dm.org/)
 * [soundmemes.cr](https://github.com/vladfaust/soundmemes.cr) - Telegram Bot built on top of tele.cr ![](https://img.shields.io/github/last-commit/vladfaust/soundmemes.cr.svg)
 * [torrent](https://github.com/Papierkorb/torrent) - A BitTorrent client ![](https://img.shields.io/github/last-commit/Papierkorb/torrent.svg)

# Tools
 * [crystal-base](https://github.com/ruivieira/crystal-base) - CentOS base docker image for Crystal development ![](https://img.shields.io/github/last-commit/ruivieira/crystal-base.svg)
 * [crystal-ctags](https://github.com/SuperPaintman/crystal-ctags) - Ctags generator for Crystal ![](https://img.shields.io/github/last-commit/SuperPaintman/crystal-ctags.svg)
 * [crystal-dash-docset](https://github.com/Sija/crystal-dash-docset) - [Dash](https://kapeli.com/dash) docset generator ![](https://img.shields.io/github/last-commit/Sija/crystal-dash-docset.svg)
 * [helptransl8](https://github.com/papilip/helptransl8) - Tool for document translators ![](https://img.shields.io/github/last-commit/papilip/helptransl8.svg)

## DevOps
 * [crystal-cookbook](https://github.com/vjdhama/crystal-cookbook) - Chef cookbook for installing crystal ![](https://img.shields.io/github/last-commit/vjdhama/crystal-cookbook.svg)

## Editor Plugins
 * Atom
   * [crystal-tools](https://atom.io/packages/crystal-tools) - Enables built in tools in Crystal compiler
   * [language-crystal-actual](https://atom.io/packages/language-crystal-actual) - Crystal language support in Atom
   * [linter-crystal](https://atom.io/packages/linter-crystal) - Lint Crystal using the Crystal compiler in Atom
 * Emacs
   * [emacs-crystal-mode](https://github.com/dotmilk/emacs-crystal-mode) - Crystal language support for Emacs ![](https://img.shields.io/github/last-commit/dotmilk/emacs-crystal-mode.svg)
   * [play-crystal.el](https://github.com/veelenga/play-crystal.el) - [play.crystal-lang.org](https://play.crystal-lang.org/#/cr) integration in Emacs ![](https://img.shields.io/github/last-commit/veelenga/play-crystal.el.svg)
 * Spacemacs
   * [crystal-spacemacs-layer](https://github.com/juanedi/crystal-spacemacs-layer) - Spacemacs contribution layer for Crystal ![](https://img.shields.io/github/last-commit/juanedi/crystal-spacemacs-layer.svg)
 * Sublime
   * [sublime-crystal](https://github.com/crystal-lang-tools/sublime-crystal) - Crystal syntax highlighting for sublime Text ![](https://img.shields.io/github/last-commit/crystal-lang-tools/sublime-crystal.svg)
 * TextMate
   * [Crystal.tmbundle](https://github.com/crystal-lang-tools/Crystal.tmbundle) - Crystal syntax highlighting, compile, format command, snippets ![](https://img.shields.io/github/last-commit/crystal-lang-tools/Crystal.tmbundle.svg)
 * Vim
   * [carcin.vim](https://github.com/MakeNowJust/carcin.vim) - Vim plugin to provide utility functions for carc.in ![](https://img.shields.io/github/last-commit/MakeNowJust/carcin.vim.svg)
   * [vim-crystal](https://github.com/rhysd/vim-crystal) - Vim filetype support for Crystal ![](https://img.shields.io/github/last-commit/rhysd/vim-crystal.svg)
   * [vim-slang](https://github.com/elorest/vim-slang) - Vim filetype support for Slang Templating Engine ![](https://img.shields.io/github/last-commit/elorest/vim-slang.svg)
 * Visual Studio Code
   * [vscode-crystal](https://github.com/g3ortega/vscode-crystal) - Crystal language support in VSCode
   * [vscode-crystal-ide](https://github.com/crystal-lang-tools/crystal-ide) - Crystal IDE powered by [Language Server Protocol](https://code.visualstudio.com/blogs/2016/06/27/common-language-protocol) ![](https://img.shields.io/github/last-commit/crystal-lang-tools/crystal-ide.svg)
   * [vscode-crystal-lang](https://github.com/crystal-lang-tools/vscode-crystal-lang) - Formatter, linter and syntax highlighting for `cr` and `ecr` files ![](https://img.shields.io/github/last-commit/crystal-lang-tools/vscode-crystal-lang.svg)

## Shell plugins
 * [crystal-zsh](https://github.com/veelenga/crystal-zsh) - .oh-my-zsh plugin ![](https://img.shields.io/github/last-commit/veelenga/crystal-zsh.svg)
