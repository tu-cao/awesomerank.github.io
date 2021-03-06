---
layout: default
title: Awesome Rank for sindresorhus/awesome-tap
---

<p align="center">
	This list is a copy of <a href="https://github.com/sindresorhus/awesome-tap">sindresorhus/awesome-tap</a> with ranks
</p>
---
# Awesome TAP [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★67308](https://github.com/sindresorhus/awesome) [<img src="https://testanything.org/images/tap.png" width="67" align="right">](https://testanything.org)


> Useful resources for the [Test Anything Protocol](https://testanything.org)<br>
> A simple text-based interface between testing modules in a test harness

*The list is very JavaScript focused right now. That's just because I'm only familiar with TAP stuff in the JS world. Contributions welcome for any language.*


## Contents

- [Reporters](#reporters)
- [Producers](#producers)
- [Consumers](#consumers)
- [Tools](#tools)
- [Articles](#articles)
- [Tutorials](#tutorials)
- [Documentation](#documentation)
- [Community](#community)


## Reporters

### JavaScript

- [tap-dot ★21](https://github.com/scottcorgan/tap-dot) - Dotted output.
- [tap-spec ★223](https://github.com/scottcorgan/tap-spec) - Mocha-like spec reporter.
- [tap-nyan ★102](https://github.com/calvinmetcalf/tap-nyan) - Nyan cat.
- [tap-min ★29](https://github.com/gummesson/tap-min) - Minimal output.
- [tap-difflet ★40 ⏳1Y](https://github.com/namuol/tap-difflet) - Minimal output with diffing.
- [tap-diff ★62](https://github.com/axross/tap-diff) - Human-friendly output with diffing.
- [tap-simple ★6 ⏳2Y](https://github.com/joeybaker/tap-simple) - Simple output.
- [faucet ★474](https://github.com/substack/faucet) - Human-readable summarizer.
- [tap-mocha-reporter](https://github.com/isaacs/tap-mocha-reporter) - Use any of the [Mocha reporters](https://github.com/isaacs/tap-mocha-reporter/tree/master/lib/reporters).
- [tap-summary ★25](https://github.com/zoubin/tap-summary) - Summarized output.
- [tap-pessimist ★13](https://github.com/clux/tap-pessimist) - Only shows failed tests.
- [tap-prettify ★30 ⏳4Y](https://github.com/toolness/tap-prettify) - Nice readable output with diffing.
- [tap-colorize ★27 ⏳2Y](https://github.com/substack/tap-colorize) - Colorize the output while preserving machine-readability.
- [tap-bail ★19](https://github.com/juliangruber/tap-bail) - Bail out when the first test fails.
- [tap-notify ★48](https://github.com/axross/tap-notify) - Notifier for macOS, Linux and Windows.
- [tap-json ★18 ⏳1Y](https://github.com/gummesson/tap-json) - JSON output.
- [tap-xunit ★25](https://github.com/aghassemi/tap-xunit) - xUnit output.
- [tap-teamcity ★6](https://github.com/smockle/tap-teamcity) - Output for TeamCity.


## Producers

Things that produce TAP output.

### JavaScript

- [AVA](https://github.com/sindresorhus/ava) - Futuristic test runner. `$ ava --tap`
- [tap](https://github.com/isaacs/node-tap) - TAP test framework for Node.js.
- [tape ★4180](https://github.com/substack/tape) - TAP-producing test harness for Node.js and browsers.
- [ESLint](http://eslint.org/docs/user-guide/formatters/#tap) - Pluggable JavaScript linter. `$ eslint --format=tap`
- [Mocha](https://mochajs.org) - Feature-rich test framework for Node.js and browsers. `$ mocha reporter=tap`
- [qunit-tap ★73](https://github.com/twada/qunit-tap) - TAP output for QUnit.
- [jasmine-reporters ★375](https://github.com/larrymyers/jasmine-reporters) - TAP output for Jasmine.
- [karma-tap-reporter ★7 ⏳1Y](https://github.com/fumiakiy/karma-tap-reporter) - TAP output for Karma.
- [mos](https://github.com/zkochan/mos) - Markdown file generator and tester. `$ mos test --tap`

### Fish

- [Fishtape ★210](https://github.com/fisherman/fishtape) - TAP producer and test harness for fish.

### Bash

- [bats ★4102](https://github.com/sstephenson/bats) - Bash Automated Testing System.

[More...](https://testanything.org/producers.html)


## Consumers

Things that consume TAP output.

### JavaScript

- [tap-parser](https://github.com/substack/tap-parser) - TAP parser.
- [tap-out ★16](https://github.com/scottcorgan/tap-out) - TAP parser.
- [yamlish ★19 ⏳2Y](https://github.com/isaacs/yamlish) - YAML-block parser.

[More...](https://testanything.org/consumers.html)


## Tools

### JavaScript

- [tap-dev-tool ★26 ⏳2Y](https://github.com/Jam3/tap-dev-tool) - Prettify TAP in the browser console.
- [tap-merge ★4](https://github.com/anko/tap-merge) - Merge multiple TAP streams.
- [smokestack ★219 ⏳2Y](https://github.com/hughsk/smokestack) - Run TAP tests in a browser and write the output to `stdout`.
- [chutney](https://github.com/derhuerst/chutney) - Run TAP tests at Sauce Labs. Lightweight [smokestack ★219 ⏳2Y](https://github.com/hughsk/smokestack) alternative.

### Python

- [tappy](https://github.com/mblayman/tappy) - Tools for working with TAP.


## Articles

- [Understand the Test Anything Protocol](http://www.effectiveperlprogramming.com/2011/05/understand-the-test-anything-protocol/)


## Tutorials

- [test-anything ★115](https://github.com/finnp/test-anything) - Learn to test anything with TAP through an interactive workshop.


## Documentation

- [Specification](https://testanything.org/tap-version-13-specification.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Test_Anything_Protocol)


## Community

- [Discuss](https://github.com/TestAnything/Specification/issues)
- [Reddit](https://www.reddit.com/r/testanythingprotocol)
- [Stack Overflow](http://stackoverflow.com/questions/tagged/tap)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="https://github.com/sindresorhus/awesome-tap">sindresorhus/awesome-tap</a> with ranks
</p>
