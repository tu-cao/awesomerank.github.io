---
layout: default
title: Awesome Rank for RyanZim/awesome-npm-scripts
---

<p align="center">
	This list is a copy of <a href="https://github.com/RyanZim/awesome-npm-scripts">RyanZim/awesome-npm-scripts</a> with ranks
</p>
---
# Awesome npm scripts [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★67308](https://github.com/sindresorhus/awesome)

[<img src="npm-logo.png" align="right" width="150">](https://www.npmjs.com)

> Everything awesome for using npm as a build tool.

You might also like [awesome-npm ★2614](https://github.com/sindresorhus/awesome-npm).

**Notice: I'm currently too busy to actively expand this list; therefore, I've decided to make this an [OPEN Open Source Project](http://openopensource.org). Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit.**

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Articles](#articles)
- [Videos/Talks](#videostalks)
- [Task Runners](#task-runners)
- [File Watchers](#file-watchers)
- [Dev Servers](#dev-servers)
- [Cross-platform Utilities](#cross-platform-utilities)
  - [Utility Packs](#utility-packs)
- [Other Utilities](#other-utilities)
- [Miscellaneous](#miscellaneous)
- [Cross-platform Shell Reference](#cross-platform-shell-reference)
- [`npm run` Reference](#npm-run-reference)
- [Contributing](#contributing)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Articles

- [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/) - Blog post by Keith Cirkel.
- [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) - Sequel to [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/).
- [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8) -  Article by Cory House.

## Videos/Talks

- [Advanced front-end automation with npm scripts](https://www.youtube.com/watch?v=0RYETb9YVrk) - Talk at Nordic.js 2015 by Kate Hudson
- [How to create a build system with npm scripts](http://www.penta-code.com/how-to-create-a-build-system-with-npm-scripts/) - Video tutorial series on setting up a front-end build system.

## Task Runners

Tools for running multiple commands or npm scripts in parallel or sequentially.

- [script-runner ★14](https://github.com/paulpflug/script-runner) - Simple task runner with a terse syntax.
- [npm-run-all ★1294](https://github.com/mysticatea/npm-run-all) - Fully featured task runner.
- [redrun ★51](https://github.com/coderaiser/redrun) - Expand scripts from package.json to improve execution speed.

## File Watchers

Tools to watch your source files and run a build command whenever any of the files change.

- [onchange ★280](https://github.com/Qard/onchange) - `onchange <glob> -- <command>`.
- [watch ★976](https://github.com/mikeal/watch) - `watch <command> <directory>`.

## Dev Servers

- [http-server ★5733](https://github.com/indexzero/http-server) - Simple zero-configuration command-line http server.
- [live-server ★1648](https://github.com/tapio/live-server) - Simple development http server with live reload capability.

## Cross-platform Utilities

Utilities to perform common command-line tasks without worrying about cross-platform compatibility.

- [rimraf ★1978](https://github.com/isaacs/rimraf) - Delete files or directories; like `rm -rf`.
- [del-cli ★72](https://github.com/sindresorhus/del-cli) - Safer file and folder deletion.
- [mkdirp ★1523](https://github.com/substack/node-mkdirp) - Create a directory, creating parent directories if needed; like `mkdir -p`.
- [cpy-cli ★58 ⏳1Y](https://github.com/sindresorhus/cpy-cli) - File/directory copying/renaming.
- [copyfiles ★57](https://github.com/calvinmetcalf/copyfiles) - Copy a list of files into a directory.
- [sync-files ★17](https://github.com/byteclubfr/node-sync-files) - `rsync`-like directory syncing with watch mode.
- [echo-cli ★3 ⏳1Y](https://github.com/iamakulov/echo-cli) - Cross-platform `echo` with JS escape sequence support.
- [clear-cli ★32 ⏳1Y](https://github.com/sindresorhus/clear-cli) - Clear the terminal.
- [cross-env ★1750](https://github.com/kentcdodds/cross-env) - Set environment variables for scripts, unix-style.
- [cross-os ★3](https://github.com/milewski/cross-os) - Run platform-specific npm scripts.
- [ntee ★16](https://github.com/stefanmaric/ntee) - Utility that reads from standard input and writes to standard output and files; like Unix `tee`.
- [catw ★107 ⏳2Y](https://github.com/substack/catw) - Print a file to stdout, with optional watch mode; sorta like Unix `cat`.

### Utility Packs

- [shx ★328](https://github.com/shelljs/shx) - Collection of common Unix utilities implemented in Node.js; example usage: `shx rm somefile`.

## Other Utilities

- [hashmark ★172](https://github.com/keithamus/hashmark) -  Take contents of a file and output as new file with a hash in the name.
- [gzip-size-cli ★80](https://github.com/sindresorhus/gzip-size-cli) - Get the gzipped size of a file or stdin.
- [opn-cli ★105 ⏳1Y](https://github.com/sindresorhus/opn-cli) - Open websites, files, executables, etc. with the user's preferred application.
- [headr ★0 ⏳1Y](https://github.com/heldr/headr) - Add header / banner info to a file.
- [Bower files CLI ★3](https://github.com/thompsonemerson/bower-files-cli) - Get main bower files on the command line

## Miscellaneous

- [screwy ★81](https://github.com/samueleaton/screwy) - The npm scripts GUI.
- [Forrest ★203 ⏳1Y](https://github.com/stefanjudis/forrest) - npm scripts desktop client.
- [run-npm ★156](https://github.com/timoxley/npm-run) - Run locally-installed node module executables. Useful for debugging npm scripts.
- [npm-quick-run ★61](https://github.com/bahmutov/npm-quick-run) - Quickly run npm scripts by prefix without typing the full name.
- [edit-script ★2](https://github.com/RyanZim/edit-script) - Edit npm scripts from the command line without worrying about JSON escaping.

## Cross-platform Shell Reference

A quick reference of the shell operators & commands that work the same on Unix and Windows.

- `&&` runs commands in sequence. If a command fails, the script exits.
- `|` pipes the stdout of one command into the stdin of the next. (`do-something | something else`)
- `>` writes the stdout of a command to a file. (`do-something > file`)
- `<` sends the contents of a file to a command's stdin. (`command < file`)
- `cd <dir>` changes the current working directory to `<dir>`. Note that `cd` alone prints the current working directory on windows, but changes the working directory to `~` on \*nix.

## `npm run` Reference

You can use `npm run-script` or `npm run`; they both do the same thing, but `npm run` is shorter.

- Run just `npm run` to print a list of scripts.
- Running `npm run script` (where `script` is the name of your script) will run `prescript`, `script`, and `postscript`; in that order.
  - You can't nest `pre` and `post` hooks (i.e. `preprescript` won't work).
- You can pass arguments to your scripts by passing `--` to `npm run`, followed by the arguments. Example: Given the script `"mocha": "mocha"`, you can run `npm run mocha -- --reporter xunit`. This effectively runs `mocha --reporter xunit`.
- Running `npm test` is the same as running `npm run test`. The same applies to `npm start` and `npm stop`.
- You can run `npm run <script> -s` to silence the default npm output (useful for calling a script within another script).

## Contributing

See [CONTRIBUTING.md](https://github.com/RyanZim/awesome-npm-scripts/blob/master/CONTRIBUTING.md).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="https://github.com/RyanZim/awesome-npm-scripts">RyanZim/awesome-npm-scripts</a> with ranks
</p>
