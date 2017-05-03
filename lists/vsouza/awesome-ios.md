<img src="https://raw.githubusercontent.com/vsouza/awesome-ios/master/awesome_logo.png">

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)
[![Join the chat at https://gitter.im/norio-nomura/SwiftTalkInJapanese](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vsouza/awesome-ios?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://api.travis-ci.org/vsouza/awesome-ios.svg?branch=master)](https://travis-ci.org/vsouza/awesome-ios)
[![Language](https://awesomelinkcounter.herokuapp.com/swift)]()
[![Language](https://awesomelinkcounter.herokuapp.com/objc)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## We've launched our Newsletter!! ✅🚀📰
* [Check out our new website 🗞](http://weekly.awesomeios.com/)

# About
A curated list of awesome iOS frameworks, libraries, tutorials, Xcode plugins, components and much more.
The list is divided into categories such as Frameworks, Components, Testing and others, open source projects, free and paid services. There is no pre-established order of items in each category, the order is for contribution. If you want to contribute, please read the [guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md).

Projects in Swift will be marked with :large_orange_diamond:, Swift Extensions will be marked with 🔶[e] and ⌚ for Apple Watch projects. Feel free to add your project.

# How to Use
Awesome-iOS is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Ask for help on our [Twitter](https://twitter.com/awesome_ios) or [Gitter Channel](https://gitter.im/vsouza/awesome-ios)
- Simply press <kbd>command</kbd> + <kbd>F</kbd> to search for a keyword
- Go through our *Content Menu*

## Content
- [About](#about)
- [How to Use](#how-to-use)
- [Getting Started](#getting-started)
- [Library and Frameworks](#libraries-and-frameworks)
    - [Analytics](#analytics)
    - [Apple TV](#apple-tv)
    - [Authentication](#authentication)
    - [Bridging](#bridging)
    - [Cache](#cache)
    - [Charts](#charts)
    - [Code Quality](#code-quality)
        - [Linter](#linter)
    - [Color](#color)
    - [Command Line](#command-line)
    - [Concurrency](#concurrency)
    - [Core Data](#core-data)
    - [Database](#database)
    - [Data Structures / Algorithms](#data-structures--algorithms)
    - [Date & Time](#date--time)
    - [EventBus](#eventbus)
    - [Files](#files)
    - [Functional Programming](#functional-programming)
    - [Games](#games)
    - [Gesture](#gesture)
    - [Graphics](#graphics)
    - [Hardware](#hardware)
        - [Bluetooth](#bluetooth)
        - [Camera](#camera)
        - [Force Touch](#force-touch)
        - [iBeacon](#ibeacon)
        - [Location](#location)
        - [Other Hardware](#other-hardware)
    - [Layout](#layout)
    - [Logging](#logging)
    - [Localization](#localization)
    - [Machine Learning](#machine-learning)
    - [Maps](#maps)
    - [Math](#math)
    - [Media](#media)
        - [Audio](#audio)
        - [GIF](#gif)
        - [Image](#image)
        - [Media Processing](#media-processing)
        - [PDF](#pdf)
        - [Streaming](#streaming)
        - [Video](#video)
    - [Messaging](#messaging)
    - [Networking](#networking)
    - [Notifications](#notifications)
        - [Push Notifications](#push-notifications)
            - [Push Notification Providers](#push-notification-providers)
        - [Local Notifications](#local-notifications)
    - [Parsing](#parsing)
        - [CSV](#csv)
        - [JSON](#json)
        - [XML & HTML](#xml--html)
        - [Other Parsing](#other-parsing)
    - [Passbook](#passbook)
    - [Payments](#payments)
    - [Permissions](#permissions)
    - [Products](#products)
    - [Reactive Programming](#reactive-programming)
    - [Reflection](#reflection)
    - [Regex](#regex)
    - [SDK](#sdk)
        - [Official](#official)
        - [Unofficial](#unofficial)
    - [Security](#security)
        - [Encryption](#encryption)
        - [Keychain](#keychain)
    - [Server](#server)
    - [Testing](#testing)
        - [TDD / BDD](#tdd--bdd)
        - [A/B Testing](#ab-testing)
        - [UI Testing](#ui-testing)
        - [Other Testing](#other-testing)
    - [Text](#text)
        - [Font](#font)
    - [UI](#ui)
        - [Activity Indicator](#activity-indicator)
        - [Alert & Action Sheet](#alert--action-sheet)
        - [Animation](#animation)
          - [Transition](#transition)
        - [Badge](#badge)
        - [Button](#button)
        - [Calendar](#calendar)
        - [Form & Settings](#form--settings)
        - [Keyboard](#keyboard)
        - [Label](#label)
        - [Menu](#menu)
        - [Navigation Bar](#navigation-bar)
        - [PickerView](#pickerview)
        - [Popup](#popup)
        - [Pull to Refresh](#pull-to-refresh)
        - [Rating Stars](#rating-stars)
        - [ScrollView](#scrollview)
        - [Slider](#slider)
        - [Splash View](#splash-view)
        - [Stepper](#stepper)
        - [Switch](#switch)
        - [Tab Bar](#tab-bar)
        - [Table View / Collection View](#table-view--collection-view)
        - [Tag](#tag)
        - [TextField & TextView](#textfield--textview)
        - [Web View](#web--view)
    - [URL Scheme](#url-scheme)
    - [Utility](#utility)
    - [VR](#vr)
    - [Walkthrough / Intro / Tutorial](#walkthrough--intro--tutorial)
    - [Websocket](#websocket)
- [Project setup](#project-setup)
- [Dependency / Package Manager](#dependency--package-manager)
- [Tools](#tools)
- [Rapid Development](#rapid-development)
  - [Injection](#injection)
- [Deployment / Distribution](#deployment--distribution)
- [App Store](#app-store)
- [SDK](#sdk)
    - [Official](#official)
    - [Unofficial](#unofficial)
- [Xcode](#xcode)
    - [Plugins](#plugins)
    - [Themes](#themes)
    - [Other Xcode](#other-xcode)
- [Reference](#reference)
- [Style Guides](#style-guides)
- [Good Websites](#good-websites)
    - [News, Blogs and more](#news-blogs-and-more)
    - [UIKit references](#uikit-references)
    - [Forums and discuss lists](#forums-and-discuss-lists)
    - [Tutorials and Keynotes](#tutorials-and-keynotes)
    - [Prototyping](#prototyping)
    - [Newsletters](#newsletters)
    - [Medium](#medium)
- [Social Media](#social-media)
  - [Twitter](#twitter)
  - [Facebook Groups](#facebook-groups)
- [Podcasts](#podcasts)
- [Books](#books)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing-and-license)

***
# Getting Started
* [Start Developing with iOS](https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/) - Apple Guide. :large_orange_diamond:
* [Lifehacker](http://lifehacker.com/i-want-to-write-ios-apps-where-do-i-start-1644802175) - I Want to Write iOS Apps. Where Do I Start?
* [CodeProject](https://www.codeproject.com/articles/88929/getting-started-with-iphone-and-ios-development) - Getting Started with iPhone and iOS Development.
* [Ray Wenderlich](https://www.raywenderlich.com/38557/learn-to-code-ios-apps-1-welcome-to-programming) - Learn to code iOS Apps.
* [Stanford - Developing iOS 7 Apps for iPhone and iPad](https://itunes.apple.com/us/course/developing-ios-7-apps-for-iphone-and-ipad/id733644550)
* [Stanford - Developing iOS 10 Apps with Swift](https://itunes.apple.com/in/course/developing-ios-10-apps-swift/id1198467120) - Stanford's 2017 iTunes U course. :large_orange_diamond:
* [Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [Object-Oriented Programming with Objective-C by Apple](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html)
* [Udacity: Start A Career Developing iOS Apps](https://www.udacity.com/course/ios-developer-nanodegree--nd003?v=ios1) - Udacity's intro course on writing iOS apps [Paid Resource] :large_orange_diamond:

# Libraries And Frameworks

## Analytics
* [Mixpanel](https://mixpanel.com/) - Advanced analytics platform.
* [Localytics](https://www.localytics.com/) - Brings app marketing and analytics together.
* [Answers by Fabric](https://answers.io/) - Answers gives you real-time insight into people’s experience in your app.
* [Liquid Analytics](https://onliquid.com) - Identify behaviours through Analytics and react with real-time Personalization.
* [GTrack ★85](https://github.com/gemr/GTrack) - Lightweight Objective-C wrapper around the Google Analytics for iOS SDK with some extra goodies.
* [ARAnalytics ★1617](https://github.com/orta/ARAnalytics) - Analytics abstraction library offering a sane API for tracking events and user data.
* [Segment ★238](https://github.com/segmentio/analytics-ios) - The hassle-free way to integrate analytics into any iOS application.
* [MOCA Analytics](https://mocaplatform.com/features) - Paid cross-platform analytics backend.
* [Countly](https://count.ly) - Open source, mobile & web analytics, crash reports and push notifications platform for iOS & Android.
* [Abbi ★1](https://github.com/abbiio/iosdk) - A Simple SDK for developers to manage and maximise conversions of all in-app promotions.
* [devtodev](https://www.devtodev.com/) - Comprehensive analytics service that improves your project and saves time for product development.

## Apple TV
* [Voucher ★477](https://github.com/rsattar/Voucher) - A simple library to make authenticating tvOS apps easy via their iOS counterparts.
* [XCDYouTubeKit ★2063](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and OS X
* [TVMLKitchen ★53](https://github.com/toshi0383/TVMLKitchen) - Swifty TVML template manager with or without client-server :large_orange_diamond:
* [BrowserTV ★201](https://github.com/zats/BrowserTV) - Turn your TV into a dashboard displaying any webpage! :large_orange_diamond:
* [Swift-GA-Tracker-for-Apple-tvOS ★62](https://github.com/analytics-pros/Swift-GA-Tracker-for-Apple-tvOS) - Google Analytics tracker for Apple tvOS provides an easy integration of Google Analytics’ measurement protocol for Apple TV. :large_orange_diamond:
* [ParallaxView ★296](https://github.com/PGSSoft/ParallaxView) - iOS controls and extensions that add parallax effect to your application. :large_orange_diamond:
* [TvOSTextViewer ★4](https://github.com/dcordero/TvOSTextViewer) - Light and scrollable view controller for tvOS to present blocks of text :large_orange_diamond:
* [FocusTvButton ★11](https://github.com/dcordero/FocusTvButton) - Light wrapper of UIButton that allows extra customization for tvOS :large_orange_diamond:
* [TvOSMoreButton ★7](https://github.com/cgoldsby/TvOSMoreButton) - A basic tvOS button which truncates long text with '... More'. :large_orange_diamong:

## Authentication
* [Heimdallr.swift ★231](https://github.com/trivago/Heimdallr.swift) - Easy to use OAuth 2 library for iOS, written in Swift. :large_orange_diamond:
* [OhMyAuth ★38](https://github.com/hyperoslo/OhMyAuth) - Simple OAuth2 library with a support of multiple services. :large_orange_diamond:
* [AuthenticationViewController ★231](https://github.com/raulriera/AuthenticationViewController) - A simple to use, standard interface for authenticating to oauth 2.0 protected endpoints via SFSafariViewController. :large_orange_diamond:
* [OAuth2 ★530](https://github.com/p2/OAuth2) - OAuth2 framework for OS X and iOS, written in Swift. :large_orange_diamond:
* [OAuthSwift ★1630](https://github.com/OAuthSwift/OAuthSwift) - Swift based OAuth library for iOS :large_orange_diamond:
* [SimpleAuth ★1143](https://github.com/calebd/SimpleAuth) - Simple social authentication for iOS.
* [AlamofireOauth2 ★67](https://github.com/evermeer/AlamofireOauth2) - A swift implementation of OAuth2 :large_orange_diamond:
* [SwiftyOAuth ★449](https://github.com/delba/SwiftyOAuth) - A simple OAuth library for iOS with a built-in set of providers :large_orange_diamond:
* [Simplicity ★599](https://github.com/SimplicityMobile/Simplicity) - A simple way to implement Facebook and Google login in your iOS and OS X apps. :large_orange_diamond:
* [InstagramAuthViewController ★32](https://github.com/Isuru-Nanayakkara/InstagramAuthViewController) - A ViewController for Instagram authentication. :large_orange_diamond:
* [Cely ★61](https://github.com/chaione/Cely) - Plug-n-Play login framework written in Swift. :large_orange_diamond:

## Bridging
* [RubyMotion](http://www.rubymotion.com/) - RubyMotion is a revolutionary toolchain that lets you quickly develop and test native iOS and OS X applications for iPhone, iPad and Mac, all using the Ruby language.
* [JSPatch ★9767](https://github.com/bang590/JSPatch) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [WebViewJavascriptBridge ★8536](https://github.com/marcuswestin/WebViewJavascriptBridge) - An iOS/OSX bridge for sending messages between Obj-C and JavaScript in UIWebViews/WebViews
* [MAIKit ★130](https://github.com/MichaelBuckley/MAIKit) - A framework for sharing code between iOS and OS X

## Cache
* [Awesome Cache](https://github.com/aschuch/AwesomeCache) - Delightful on-disk cache (written in Swift) :large_orange_diamond:
* [mattress ★422](https://github.com/buzzfeed/mattress) - iOS Offline Caching for Web Content :large_orange_diamond:
* [Carlos ★416](https://github.com/WeltN24/Carlos) - A simple but flexible cache :large_orange_diamond:
* [HanekeSwift ★4254](https://github.com/Haneke/HanekeSwift) - A lightweight generic cache for iOS written in Swift with extra love for images. :large_orange_diamond:
* [YYCache ★1326](https://github.com/ibireme/YYCache) - High performance cache framework for iOS.
* [Cache ★638](https://github.com/hyperoslo/Cache) - Nothing but Cache. :large_orange_diamond:
* [MGCacheManager ★7](https://github.com/Mortgy/MGCacheManager) - A delightful iOS Networking Cache Managing Class.
* [SPTPersistentCache ★1112](https://github.com/spotify/SPTPersistentCache) - Everyone tries to implement a cache at some point in their iOS app’s lifecycle, and this is ours. By Spotify
* [Track ★179](https://github.com/maquannene/Track) - Track is a thread safe cache write by Swift. Composed of DiskCache and MemoryCache which support LRU. :large_orange_diamond:
* [UITableView Cache ★55](https://github.com/Kilograpp/UITableView-Cache) - UITableView cell cache that cures scroll-lags on a cell instantiating.
* [RocketData ★488](https://github.com/linkedin/RocketData) - A caching and consistency solution for immutable models. :large_orange_diamond:
* [PINCache ★1594](https://github.com/pinterest/PINCache) - Fast, non-deadlocking parallel object cache for iOS and OS X
* [Johnny ★25](https://github.com/zolomatok/Johnny) - Melodic Caching for Swift :large_orange_diamond:

## Charts
* [Charts](https://github.com/danielgindi/Charts) - A powerful chart / graph framework, the iOS equivalent to [MPAndroidChart ★15275](https://github.com/PhilJay/MPAndroidChart). :large_orange_diamond:
* [JTChartView ★109](https://github.com/kubatruhlar/JTChartView) - JTChartView is the new lightweight and fully customizable solution to draw a chart.
* [PNChart ★8368](https://github.com/kevinzhow/PNChart) - A simple and beautiful chart lib used in Piner and CoinsMan for iOS
* [XJYChart ★111](https://github.com/JunyiXie/XJYChart) - A Beautiful chart for iOS. Support animation, click, slide, area highlight.
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) - Elegant Line Graphs for iOS (charting library).
* [JBChartView ★3641](https://github.com/Jawbone/JBChartView) - iOS-based charting library for both line and bar graphs.
* [XYPieChart ★1717](https://github.com/xyfeng/XYPieChart) - A simple and animated Pie Chart for your iOS app.
* [TEAChart ★1117](https://github.com/xhacker/TEAChart) - Simple and intuitive iOS chart library. Contribution graph, clock chart, and bar chart.
* [EChart ★611](https://github.com/zhuhuihuihui/EChart) - iOS/iPhone/iPad Chart, Graph. Event handling and animation supported.
* [FSLineChart ★777](https://github.com/ArthurGuibert/FSLineChart) - A line chart library for iOS.
* [chartee ★819](https://github.com/zhiyu/chartee) - a charting library for mobile platforms.
* [ANDLineChartView ★396](https://github.com/anaglik/ANDLineChartView) - ANDLineChartView is easy to use view-based class for displaying animated line chart.
* [TWRCharts ★360](https://github.com/chasseurmic/TWRCharts) - An iOS wrapper for ChartJS. Easily build animated charts by leveraging the power of native Obj-C code.
* [SwiftCharts ★1296](https://github.com/i-schuetz/SwiftCharts) - Easy to use and highly customizable charts library for iOS. :large_orange_diamond:
* [FlowerChart ★7](https://github.com/drinkius/flowerchart) - Flower-shaped chart with custom appearance animation, fully vector. :large_orange_diamond:
* [Scrollable-GraphView ★3701](https://github.com/philackm/Scrollable-GraphView) - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift. :large_orange_diamond:
* [Dr-Charts ★48](https://github.com/Zomato/DR-charts) - Dr-Charts is a highly customisable, easy to use and interactive chart / graph framework in Objective-C.
* [Graphs ★803](https://github.com/recruit-mtl/Graphs) - Light weight charts view generater for iOS. :large_orange_diamond:
* [FSInteractiveMap ★430](https://github.com/ArthurGuibert/FSInteractiveMap) - A charting library to visualize and interact with a vector map on iOS. It's like Geochart but for iOS!
* [JYRadarChart ★383](https://github.com/johnnywjy/JYRadarChart) - An iOS open source Radar Chart implementation.
* [TKRadarChart ★119](https://github.com/TBXark/TKRadarChart) - A customizable radar chart in Swift :large_orange_diamond:
* [MagicPie ★517](https://github.com/AlexandrGraschenkov/MagicPie) - Awesome layer based pie chart. Fantasticly fast and fully customizable. Amazing animations available with MagicPie!!1 :large_orange_diamond: 🎉 ✨✨✨✨✨
* [PieCharts ★262](https://github.com/i-schuetz/PieCharts) - Easy to use and highly customizable pie charts library for iOS. :large_orange_diamond:
* [CSPieChart ★22](https://github.com/youkchansim/CSPieChart) - iOS PieChart Opensource. This is very easy to use and customizable. :large_orange_diamond:

## Code Quality
* [KZBootstrap ★1773](https://github.com/krzysztofzablocki/KZBootstrap) - iOS project bootstrap aimed at high quality coding.
* [KZAsserts ★104](https://github.com/krzysztofzablocki/KZAsserts) - Set of custom assertions that automatically generate NSError's, allow for both Assertions in Debug and Error handling in Release builds, with beautiful DSL.
* [PSPDFUIKitMainThreadGuard](https://gist.github.com/steipete/5664345) - Simple snippet generating assertions when UIKit is used on background threads.
* [Flex ★7678](https://github.com/Flipboard/FLEX) - An in-app debugging and exploration tool for iOS.
* [chisel ★5852](https://github.com/facebook/chisel) - Collection of LLDB commands to assist debugging iOS apps.
* [ocstyle ★242](https://github.com/Cue/ocstyle) - Objective-C style checker.
* [spacecommander ★757](https://github.com/square/spacecommander) - Commit fully-formatted Objective-C code as a team without even trying.
* [DWURecyclingAlert ★551](https://github.com/diwu/DWURecyclingAlert) - Optimizing UITableViewCell For Fast Scrolling.
* [Tailor ★999](https://github.com/sleekbyte/tailor) - Cross-platform static analyzer for Swift that helps you to write cleaner code and avoid bugs.
* [SwiftCop ★485](https://github.com/andresinaka/SwiftCop) -  SwiftCop is a validation library fully written in Swift and inspired by the clarity of Ruby On Rails Active Record validations. :large_orange_diamond:
* [Trackable ★118](https://github.com/VojtaStavik/Trackable) - Trackable is a simple analytics integration helper library. It’s especially designed for easy and comfortable integration with existing projects. :large_orange_diamond:
* [MLeaksFinder ★1979](https://github.com/Zepo/MLeaksFinder) - Find memory leaks in your iOS app at develop time.
* [HeapInspector-for-iOS ★1559](https://github.com/tapwork/HeapInspector-for-iOS) - Find memory issues & leaks in your iOS app without instruments
* [FBMemoryProfiler ★2445](https://github.com/facebook/FBMemoryProfiler) - iOS tool that helps with profiling iOS Memory usage.
* [FBRetainCycleDetector ★2353](https://github.com/facebook/FBRetainCycleDetector) - iOS library to help detecting retain cycles in runtime.
* [Buglife ★241](https://github.com/Buglife/Buglife-iOS) - Awesome bug reporting for iOS apps
* [Warnings-xcconfig](https://github.com/boredzo/Warnings-xcconfig) - An xcconfig (Xcode configuration) file for easily turning on a boatload of warnings in your project or its targets.
* [Aardvark ★174](https://github.com/square/Aardvark) - Aardvark is a library that makes it dead simple to create actionable bug reports.
* [Stats ★136](https://github.com/shu223/Stats) - In-app memory usage monitoring.
* [Alpha ★618](https://github.com/Legoless/Alpha) - Next generation debugging framework for iOS.
* [GlueKit ★321](https://github.com/lorentey/GlueKit) - A type-safe observer framework for Swift. :large_orange_diamond:
* [SwiftFormat ★1317](https://github.com/nicklockwood/SwiftFormat) - A code library and command-line formatting tool for reformatting Swift code. :large_orange_diamond:
* [PSTModernizer ★210](https://github.com/PSPDFKit-labs/PSTModernizer) - Makes it easier to support older versions of iOS by fixing things and adding missing methods.
* [SwiftyVIPER ★38](https://github.com/codytwinton/SwiftyVIPER) - Makes implementing VIPER architecture much easier and cleaner.  :large_orange_diamond:
* [Bugsee](https://www.bugsee.com) - In-app bug and crash reporting with video, logs, network traffic and traces.
* [Fallback ★32](https://github.com/devxoul/Fallback) - Syntactic sugar for nested do-try-catch. :large_orange_diamond:
* [ODUIThreadGuard ★612](https://github.com/olddonkey/ODUIThreadGuard) - A guard to help you check if you make UI changes not in main thread. :large_orange_diamond:
* [IBAnalyzer ★774](https://github.com/fastred/IBAnalyzer) - Find common xib and storyboard-related problems without running your app or writing unit tests. :large_orange_diamond:
* [Dotzu ★1021](https://github.com/remirobert/Dotzu) - iOS app debugger while using the app. Crash report, logs, network.
* [CleanArchitectureRxSwift ★516](https://github.com/sergdort/CleanArchitectureRxSwift) - Example of Clean Architecture of iOS app using RxSwift. :large_orange_diamond:
* [PIDOR ★254](https://github.com/applepride/pidor) - Simple design pattern with the best iOS dev experience.
* [DecouplingKit ★94](https://github.com/coderyi/DecouplingKit) - decoupling between modules in your iOS Project.
* [Clue ★87](https://github.com/Geek-1001/Clue) - Flexible bug report framework for iOS with screencast, networking, interactions and view structure.
* [Viperit ★133](https://github.com/ferranabello/Viperit) - Viper Framework for iOS. Develop an app following VIPER architecture in an easy way. Written and tested in Swift. :large_orange_diamond:

#### Linter
* [OCLint](http://oclint.org/) - Static code analysis tool for improving quality and reducing defects.
* [Taylor ★148](https://github.com/yopeso/Taylor) - Measure Swift code metrics and get reports in Xcode, Jenkins and other CI platforms. :large_orange_diamond:
* [Swiftlint ★6638](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions. :large_orange_diamond:

## Color
* [Chameleon](https://github.com/ViccAlexander/Chameleon) - A lightweight, yet powerful, flat color framework for iOS (ObjC & Swift). :large_orange_diamond:
* [SDevFlatColors ★57](https://github.com/0x73/SDevFlatColors) - Flat Colors on Swift :large_orange_diamond:
* [ColorArt ★131](https://github.com/vinhnx/ColorArt) - extract dominant colors from image like iTunes 11.
* [DynamicColor ★1596](https://github.com/yannickl/DynamicColor) - Yet another extension to manipulate colors easily in Swift. :large_orange_diamond:[e]
* [SwiftHEXColors ★468](https://github.com/thii/SwiftHEXColors) - HEX color handling as an extension for UIColor. :large_orange_diamond:[e]
* [Colours ★2838](https://github.com/bennyguitar/Colours) - A beautiful set of predefined colors and a set of color methods to make your iOS/OSX development life easier.
* [UIColor-Hex-Swift ★743](https://github.com/yeahdongcn/UIColor-Hex-Swift) - Convenience method for creating autoreleased color using RGBA hex string. :large_orange_diamond:
* [Crayons ★490](https://github.com/Sephiroth87/Crayons) - An Xcode plugin to improve dealing with colors in your project
* [Hue ★1980](https://github.com/hyperoslo/Hue) - Hue is the all-in-one coloring utility that you'll ever need.
* [FlatUIColors ★125](https://github.com/brynbellomy/FlatUIColors) - Flat UI color palette helpers written in Swift. :large_orange_diamond:
* [RandomColorSwift ★420](https://github.com/onevcat/RandomColorSwift) - An attractive color generator for Swift. Ported from randomColor.js. :large_orange_diamond:
* [PFColorHash ★16](https://github.com/PerfectFreeze/PFColorHash) - Generate color based on the given string. :large_orange_diamond:
* [BCColor](https://github.com/boycechang/BCColor) - A lightweight but powerful color kit (Swift) :large_orange_diamond:
* [XcodeColorSense ★76](https://github.com/onmyway133/XcodeColorSense) - :balloon: An Xcode plugin that makes working with color easier :large_orange_diamond:
* [DKNightVersion ★2594](https://github.com/Draveness/DKNightVersion) - Manage Colors, Integrate Night/Multiple Themes
* [PrettyColors ★145](https://github.com/jdhealy/PrettyColors) - PrettyColors is a Swift library for styling and coloring text in the Terminal. The library outputs [ANSI escape codes](https://en.wikipedia.org/wiki/ANSI_escape_code) and conforms to [ECMA Standard 48](http://www.ecma-international.org/publications/standards/Ecma-048.htm). :large_orange_diamond:
* [TFTColor](https://github.com/burhanuddin353/TFTColor) - Simple Extension for RGB and CMKY Hex Strings and Hex Values (ObjC & Swift). :large_orange_diamond:
* [CostumeKit ★271](https://github.com/jakemarsh/CostumeKit) - Base types for theming an app. :large_orange_diamond:
* [CSS3ColorsSwift ★45](https://github.com/WorldDownTown/CSS3ColorsSwift) - A UIColor extension with CSS3 Colors name. :large_orange_diamond:

## Command Line
* [Swiftline ★951](https://github.com/oarrabi/Swiftline) - Swiftline is a set of tools to help you create command line applications. :large_orange_diamond:
* [CommandLine ★861](https://github.com/jatoben/CommandLine) - A pure Swift library for creating command-line interfaces :large_orange_diamond:
* [Colors ★83](https://github.com/paulot/Colors) - Terminal Colors for Swift :large_orange_diamond:
* [Commander ★749](https://github.com/kylef/Commander) - Compose beautiful command line interfaces in Swift :large_orange_diamond:
* [ColorizeSwift ★161](https://github.com/mtynior/ColorizeSwift) - Terminal string styling for Swift. :large_orange_diamond:
* [Guaka](https://github.com/oarrabi/Guaka) - The smartest and most beautiful (POSIX compliant) Command line framework for Swift :large_orange_diamond:
* [Marathon ★744](https://github.com/JohnSundell/Marathon) - Marathon makes it easy to write, run and manage your Swift scripts :large_orange_diamond:

## Concurrency
* [Venice](https://github.com/Zewo/Venice) - CSP (Coroutines, Channels, Select) for Swift :large_orange_diamond:
* [Safe ★394](https://github.com/tidwall/Safe) - Modern Concurrency and Synchronization for Swift. :large_orange_diamond:
* [Concurrent ★128](https://github.com/typelift/Concurrent) - Functional Concurrency Primitives :large_orange_diamond:
* [Flow ★185](https://github.com/JohnSundell/Flow) - Operation Oriented Programming in Swift :large_orange_diamond:
* [Brisk ★19](https://github.com/jmfieldman/Brisk) - A Swift DSL that allows concise and effective concurrency manipulation. :large_orange_diamond:
* [Aojet ★9](https://github.com/aojet/Aojet) - An actor model library for swift.
* [Overdrive ★793](https://github.com/arikis/Overdrive) - Fast async task based Swift framework with focus on type safety, concurrency and multi threading. :large_orange_diamond:
* [NSLock+Synchronized ★2](https://github.com/Jon-Schneider/NSLock-Synchronized) - Do you miss @synchronized in Swift? NSLock+Synchronized gives you back @synchronized in Swift via a global function and NSLock class and instance methods, conveniently usable via Cocoapod and Carthage Framework. :large_orange_diamond:[e]
* [AsyncNinja ★35](https://github.com/AsyncNinja/AsyncNinja) - A complete set of concurrency and reactive programming primitives. :large_orange_diamond:

## Core Data
* [CWCoreData ★72](https://github.com/jayway/CWCoreData) - Additions and utilities to make it concurrency easier with the Core Data framework.
* [ObjectiveRecord ★1316](https://github.com/supermarin/ObjectiveRecord) - ActiveRecord for Objective-C.
* [SSDataKit ★465](https://github.com/soffes/SSDataKit) - Eliminate your Core Data boilerplate code.
* [ios-queryable ★236](https://github.com/martydill/ios-queryable) - ios-queryable is an implementation of IQueryable/IEnumerable for Core Data.
* [Ensembles ★1452](https://github.com/drewmccormack/ensembles) - A synchronization framework for Core Data.
* [SLRESTfulCoreData ★186](https://github.com/OliverLetterer/SLRESTfulCoreData) - Objc naming conventions, autogenerated accessors at runtime, URL substitutions and intelligent attribute mapping.
* [Mogenerator ★2923](https://github.com/rentzsch/mogenerator) - Automatic Core Data code generation.
* [HardCoreData ★202](https://github.com/Krivoblotsky/HardCoreData) - CoreData stack and controller that will never block UI thread.
* [encrypted-core-data ★621](https://github.com/project-imas/encrypted-core-data) - Core Data encrypted SQLite store using SQLCipher.
* [MagicalRecord ★10271](https://github.com/magicalpanda/MagicalRecord) - Super Awesome Easy Fetching for Core Data.
* [QueryKit ★1245](https://github.com/QueryKit/QueryKit) - A simple type-safe Core Data query language. :large_orange_diamond:
* [CoreStore ★1418](https://github.com/JohnEstropia/CoreStore) - Powerful Core Data framework for Incremental Migrations, Fetching, Observering, etc. :large_orange_diamond:
* [Core Data Query Interface ★19](https://github.com/prosumma/CoreDataQueryInterface) A type-safe, fluent query framework for Core Data. :large_orange_diamond:
* [Graph ★689](https://github.com/CosmicMind/Graph) - An elegant data-driven framework for CoreData in Swift. :large_orange_diamond:
* [CoreDataDandy ★33](https://github.com/fuzz-productions/CoreDataDandy) - A feature-light wrapper around Core Data that simplifies common database operations. :large_orange_diamond:
* [Sync ★1877](https://github.com/SyncDB/Sync) - :arrows_counterclockwise: Modern Swift JSON synchronization to Core Data :large_orange_diamond:
* [AlecrimCoreData ★716](https://github.com/Alecrim/AlecrimCoreData) - A powerful and simple Core Data wrapper framework written in Swift. :large_orange_diamond:
* [AERecord ★278](https://github.com/tadija/AERecord) - Super awesome Core Data wrapper in Swift. :large_orange_diamond:
* [CoreDataStack ★496](https://github.com/bignerdranch/CoreDataStack) - The Big Nerd Ranch Core Data Stack :large_orange_diamond:
* [JSQCoreDataKit ★406](https://github.com/jessesquires/JSQCoreDataKit) - A swifter Core Data stack :large_orange_diamond:
* [Skopelos ★172](https://github.com/albertodebortoli/Skopelos) - A minimalistic, thread safe, non-boilerplate and super easy to use version of Active Record on Core Data. Simply all you need for doing Core Data. Swift flavour. :large_orange_diamond:
* [Cadmium ★86](https://github.com/jmfieldman/cadmium) - A complete swift framework that wraps CoreData and helps facilitate best practices. :large_orange_diamond:
* [DataKernel ★4](https://github.com/mrdekk/DataKernel) - Simple CoreData wrapper to ease operations. :large_orange_diamond:
* [DATAStack ★153](https://github.com/SyncDB/DATAStack) - 100% Swift Simple Boilerplate Free Core Data Stack. NSPersistentContainer. :large_orange_diamond:
* [JustPersist ★82](https://github.com/justeat/JustPersist) - JustPersist is the easiest and safest way to do persistence on iOS with Core Data support out of the box.

## Database
* [Realm ★10556](https://github.com/realm/realm-cocoa) - The alternative to CoreData and SQLite: Simple, modern and fast.
* [YapDatabase ★2815](https://github.com/yapstudios/YapDatabase) - YapDatabase is an extensible database for iOS & Mac.
* [Couchbase Mobile](https://developer.couchbase.com/mobile/) - Couchbase document store for mobile with cloud sync.
* [FMDB ★11450](https://github.com/ccgus/fmdb) - A Cocoa / Objective-C wrapper around SQLite.
* [Akaibu-NSUserDefaults ★13](https://github.com/roytang121/Akaibu-NSUserDefaults) - a Swifty Key-value store for archiving NSObject in only one line of code. Class properties are automatically mapped and archived under the hood.
* [FCModel ★1616](https://github.com/marcoarment/FCModel) - An alternative to Core Data for people who like having direct SQL access.
* [Zephyr ★354](https://github.com/ArtSabintsev/Zephyr) - Effortlessly synchronize NSUserDefaults over iCloud. :large_orange_diamond:
* [Prephirences ★423](https://github.com/phimage/Prephirences) - Prephirences is a Swift library that provides useful protocols and convenience methods to manage application preferences, configurations and app-state. :large_orange_diamond:
* [Storez](https://github.com/SwiftKitz/Storez) - Safe, statically-typed, store-agnostic key-value storage (with namespace support). :large_orange_diamond:
* [SwiftyUserDefaults ★2406](https://github.com/radex/SwiftyUserDefaults) - Statically-typed NSUserDefaults. :large_orange_diamond:
* [swiftydb ★434](https://github.com/Oyvindkg/swiftydb) - Making SQLite databases a blast :large_orange_diamond:
* [SugarRecord ★1858](https://github.com/carambalabs/SugarRecord) - Data persistence management library written in Swift 2.0 :large_orange_diamond:
* [SQLite.swift ★4058](https://github.com/stephencelis/SQLite.swift) - A type-safe, Swift-language layer over SQLite3. :large_orange_diamond:
* [GRDB.swift ★749](https://github.com/groue/GRDB.swift) - A versatile SQLite toolkit for Swift, with WAL mode support :large_orange_diamond:
* [SwiftData ★517](https://github.com/ryanfowler/SwiftData) - Simple and Effective SQLite Handling in Swift :large_orange_diamond:
* [Fluent ★675](https://github.com/vapor/fluent) - Simple ActiveRecord implementation for working with your database in Swift. :large_orange_diamond:
* [RealmIncrementalStore ★206](https://github.com/eure/RealmIncrementalStore) - Realm-powered Core Data persistent store. :large_orange_diamond:
* [Palau ★386](https://github.com/symentis/Palau) - NSUserDefaults with Wings! Custom Validation, Swift Generics.  :large_orange_diamond:
* [ParseAlternatives ★2520](https://github.com/relatedcode/ParseAlternatives) - A collaborative list of Parse alternative backend service providers.
* [TypedDefaults ★106](https://github.com/tasanobu/TypedDefaults) - TypedDefaults is a utility library to type-safely use NSUserDefaults. :large_orange_diamond:
* [realm-cocoa-converter ★115](https://github.com/realm/realm-cocoa-converter) - A library that provides the ability to import/export Realm files from a variety of data container formats. :large_orange_diamond:
* [YapDatabaseExtensions ★79](https://github.com/danthorpe/YapDatabaseExtensions) - YapDatabase extensions for use with Swift :large_orange_diamond:
* [RealmGeoQueries ★74](https://github.com/mhergon/RealmGeoQueries) - RealmGeoQueries simplifies spatial queries with Realm Cocoa. In the absence of and official functions, this library provide the possibility to do proximity search.  :large_orange_diamond:[e]
* [SwiftMongoDB ★254](https://github.com/Danappelxx/SwiftMongoDB) - A MongoDB interface for Swift :large_orange_diamond:
* [ObjectiveRocks ★29](https://github.com/iabudiab/ObjectiveRocks) - An Objective-C wrapper of Facebook's RocksDB - A Persistent Key-Value Store for Flash and RAM Storage.
* [OHMySQL ★22](https://github.com/oleghnidets/OHMySQL) - An Objective-C wrapper of MySQL C API.
* [SwiftStore ★47](https://github.com/hemantasapkota/SwiftStore) - Key-Value store for Swift backed by LevelDB :large_orange_diamond:
* [PredicateEditor ★349](https://github.com/arvindhsukumar/PredicateEditor) - A visual editor for dynamically creating NSPredicates to query data in your iOS app. :large_orange_diamond:
* [OneStore ★10](https://github.com/muukii/OneStore) - A single value proxy for NSUserDefaults, with clean API. :large_orange_diamond:
* [MongoDB](https://github.com/PerfectlySoft/Perfect-MongoDB) - A Swift wrapper around the mongo-c client library, enabling access to MongoDB servers. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [SQLite](https://github.com/PerfectlySoft/Perfect-SQLite) - A Swift wrapper around the SQLite 3 client library, enabling access to SQLite servers. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [MySQL](https://github.com/PerfectlySoft/Perfect-MySQL) - A Swift wrapper around the MySQL client library, enabling access to MySQL servers. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Redis](https://github.com/PerfectlySoft/Perfect-Redis) - A Swift wrapper around the Redis client library, enabling access to Redis. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [PostgreSQL](https://github.com/PerfectlySoft/Perfect-PostgreSQL) - A Swift wrapper around the libpq client library, enabling access to PostgreSQL servers. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [FileMaker](https://github.com/PerfectlySoft/Perfect-FileMaker) - A Swift wrapper around the FileMaker XML Web publishing interface, enabling access to FileMaker servers. Part of the [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) project, but stand-alone. SPM and Swift 3 support.
* [Nora ★164](https://github.com/SD10/Nora) - Nora is a Firebase abstraction layer for working with FirebaseDatabase and FirebaseStorage. :large_orange_diamond:
* [PersistentStorageSerializable](https://github.com/IvanRublev/PersistentStorageSerializable) - Swift library that makes easier to serialize the user's preferences (app's settings) with system User Defaults or Property List file on disk. :large_orange_diamond:

## Data Structures / Algorithms
* [SwiftSortedList ★3](https://github.com/bemindinteractive/SwiftSortedList) - A sorted list implementation written in Swift :large_orange_diamond:
* [Changeset ★636](https://github.com/osteslag/Changeset) - Minimal edits from one collection to another :large_orange_diamond:
* [BTree ★853](https://github.com/lorentey/BTree) - Fast ordered collections for Swift using in-memory B-trees :large_orange_diamond:
* [SwiftStructures ★1678](https://github.com/waynewbishop/SwiftStructures) - Examples of commonly used data structures and algorithms in Swift. :large_orange_diamond:
* [diff ★74](https://github.com/soffes/diff) - Simple diff library in pure Swift :large_orange_diamond:
* [Brick ★46](https://github.com/hyperoslo/Brick) - :droplet: A generic view model for both basic and complex scenarios :large_orange_diamond:
* [Algorithm ★505](https://github.com/CosmicMind/Algorithm) - Algorithm is a collection of data structures that are empowered by a probability toolset. :large_orange_diamond:
* [AnyObjectConvertible ★52](https://github.com/tarunon/AnyObjectConvertible) - Convert your own struct/enum to AnyObject easily. :large_orange_diamond:
* [Dollar ★3612](https://github.com/ankurp/Dollar) - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript https://www.dollarswift.org/. :large_orange_diamond:
* [Result ★1568](https://github.com/antitypical/Result) - Swift type modelling the success/failure of arbitrary operations. :large_orange_diamond:
* [EKAlgorithms ★2192](https://github.com/EvgenyKarkan/EKAlgorithms) - Some well known CS algorithms & data structures in Objective-C.
* [Monaka ★22](https://github.com/naru-jpn/Monaka) - Convert custom struct and fundamental values to NSData.
* [Buffer ★297](https://github.com/alexdrone/Buffer) - Swift μ-framework for efficient array diffs, collection observation and cell configuration. :large_orange_diamond:
* [SwiftGraph ★271](https://github.com/davecom/SwiftGraph) - Graph data structure and utility functions in pure Swift. :large_orange_diamond:
* [SwiftPriorityQueue ★212](https://github.com/davecom/SwiftPriorityQueue) - A priority queue with a classic binary heap implementation in pure Swift. :large_orange_diamond:
* [Pencil ★62](https://github.com/naru-jpn/pencil) - Write values to file and read it more easily. :large_orange_diamond:
* [HeckelDiff ★18](https://github.com/mcudich/HeckelDiff) - A fast Swift diffing library. :large_orange_diamond:
* [Dekoter ★16](https://github.com/artemstepanenko/Dekoter) - `NSCoding`'s counterpart for Swift structs. :large_orange_diamond:

## Date & Time

* [Every.swift ★276](https://github.com/samhann/Every.swift) - A swift wrapper for NSTimer  :large_orange_diamond:
* [Timepiece ★2010](https://github.com/naoty/Timepiece) - Intuitive NSDate extensions in Swift :large_orange_diamond:
* [SwiftDate ★2880](https://github.com/malcommac/SwiftDate) - Easy NSDate Management in Swift 2.0 :large_orange_diamond:
* [SwiftMoment ★1435](https://github.com/akosma/SwiftMoment) - A time and calendar manipulation library written in Swift 2 :large_orange_diamond:
* [DateTools ★5375](https://github.com/MatthewYork/DateTools) - Dates and times made easy in Objective-C
* [Punctual.swift ★317](https://github.com/harlanhaskins/Punctual.swift) - Swift dates, more fun. :large_orange_diamond:
* [SwiftyTimer ★831](https://github.com/radex/SwiftyTimer) - Swifty API for NSTimer :large_orange_diamond:
* [DateHelper ★766](https://github.com/melvitax/DateHelper) - Convenience extension for NSDate in Swift :large_orange_diamond:
* [Tempo ★154](https://github.com/remirobert/Tempo) - :watch: Date and time manager for iOS/OSX written in Swift :large_orange_diamond:
* [iso-8601-date-formatter ★587](https://github.com/boredzo/iso-8601-date-formatter) - A Cocoa NSFormatter subclass to convert dates to and from ISO-8601-formatted strings. Supports calendar, week, and ordinal formats.
* [EmojiTimeFormatter ★75](https://github.com/thomaspaulmann/EmojiTimeFormatter) - Format your dates/times as emojis. :large_orange_diamond:
* [Kronos ★199](https://github.com/lyft/Kronos) - Elegant NTP date library in Swift :large_orange_diamond:
* [TrueTime](https://github.com/instacart/TrueTime.swift) - Get the true current time impervious to device clock time changes. (NTP library for Swift) . :large_orange_diamond:
* [10Clock ★409](https://github.com/joedaniels29/10Clock) - This Control is a beautiful time-of-day picker heavily inspired by the iOS 10 "Bedtime" timer. :large_orange_diamond:
* [NSDate-TimeAgo ★1635](https://github.com/kevinlawler/NSDate-TimeAgo) - A "time ago", "time since", "relative date", or "fuzzy date" category for NSDate and iOS, Objective-C, Cocoa Touch, iPhone, iPad.
* [ServerSync ★4](https://github.com/skylovely/ServerSync-iOS) - Synchronize server's UTC time and app's UTC time :large_orange_diamond:[e]

## EventBus
* [SwiftEventBus ★524](https://github.com/cesarferreira/SwiftEventBus) - A publish/subscribe event bus optimized for iOS8. :large_orange_diamond:
* [PromiseKit ★7515](https://github.com/mxcl/PromiseKit) - Promises for iOS and OS X.
* [Bolts](https://github.com/BoltsFramework/Bolts-ObjC) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier, including tasks (promises) and app links (deep links).
* [SwiftTask ★1671](https://github.com/ReactKit/SwiftTask) - Promise + progress + pause + cancel + retry for Swift.  :large_orange_diamond:
* [When ★66](https://github.com/vadymmarkov/When) - A lightweight implementation of Promises in Swift. :large_orange_diamond:
* [then🎬 ★499](https://github.com/freshOS/then) - Elegant Async code in Swift. :large_orange_diamond:
* [Bolts-Swift ★951](https://github.com/BoltsFramework/Bolts-Swift) - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. :large_orange_diamond:
* [RWPromiseKit ★91](https://github.com/deput/RWPromiseKit) - A light-weighted Promise library for Objective-C
* [FutureLib ★40](https://github.com/couchdeveloper/FutureLib) - FutureLib is a pure Swift 2 library implementing Futures & Promises inspired by Scala. :large_orange_diamond:
* [SwiftNotificationCenter ★409](https://github.com/100mango/SwiftNotificationCenter) - A Protocol-Oriented NotificationCenter which is type safe, thread safe and with memory safety :large_orange_diamond:
* [FutureKit ★624](https://github.com/FutureKit/FutureKit) - A Swift based Future/Promises Library for IOS and OS X. :large_orange_diamond:
* [signals-ios ★451](https://github.com/uber/signals-ios) - Typeful eventing
* [BrightFutures ★1412](https://github.com/Thomvis/BrightFutures) - Write great asynchronous code in Swift using futures and promises. :large_orange_diamond:
* [NoticeObserveKit ★102](https://github.com/marty-suzuki/NoticeObserveKit) - NoticeObserveKit is type-safe NotificationCenter wrapper that associates notice type with info type. :large_orange_diamond:
* [Hydra ★954](https://github.com/malcommac/Hydra) - Promises & Await - Write better async code in Swift :large_orange_diamond:

## Files
* [FileKit ★1340](https://github.com/nvzqz/FileKit) - Simple and expressive file management in Swift. :large_orange_diamond:
* [Zip ★931](https://github.com/marmelroy/Zip) - Swift framework for zipping and unzipping files. :large_orange_diamond:
* [FileBrowser ★1010](https://github.com/marmelroy/FileBrowser) - Powerful Swift file browser for iOS. :large_orange_diamond:
* [Ares ★112](https://github.com/indragiek/Ares) - Zero-setup P2P file transfer between Macs and iOS devices :large_orange_diamond:
* [FileProvider ★101](https://github.com/amosavian/FileProvider) - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive/SMB2) files on iOS/tvOS and macOS. :large_orange_diamond:
* [KZFileWatchers ★754](https://github.com/krzysztofzablocki/KZFileWatchers) - A micro-framework for observing file changes, both local and remote. Helpful in building developer tools. :large_orange_diamond:
* [ZipArchive ★2723](https://github.com/ZipArchive/ZipArchive) - ZipArchive is a simple utility class for zipping and unzipping files on iOS and Mac.
* [FileExplorer ★467](https://github.com/Augustyniak/FileExplorer) - Powerful file browser for iOS that allows its users to choose and remove files and/or directories. :large_orange_diamond:

## Functional Programming
* [Forbind ★42](https://github.com/ulrikdamm/Forbind) - Functional chaining and promises in Swift. :large_orange_diamond:
* [Funky ★11](https://github.com/brynbellomy/Funky) - Functional programming tools and experiments in Swift. :large_orange_diamond:
* [LlamaKit ★635](https://github.com/LlamaKit/LlamaKit) - Collection of must-have functional Swift tools. :large_orange_diamond:
* [Oriole ★11](https://github.com/tptee/Oriole) - A functional utility belt implemented as Swift 2.0 protocol extensions. :large_orange_diamond:[e]
* [Prelude ★292](https://github.com/robrix/Prelude) - Swift µframework of simple functional programming tools. :large_orange_diamond:
* [Swiftx ★172](https://github.com/typelift/Swiftx) - Functional data types and functions for any project. :large_orange_diamond:
* [Swiftz ★2902](https://github.com/typelift/Swiftz) -  Functional programming in Swift. :large_orange_diamond:
* [OptionalExtensions ★165](https://github.com/RuiAAPeres/OptionalExtensions) - Swift µframework with extensions for the  Optional Type. :large_orange_diamond:[e]
* [Hookah ★58](https://github.com/HookahSwift/Hookah) - Hookah is a functional library for Swift. It's inspired by LoDash, Underscore project. :large_orange_diamond:
* [Argo ★3035](https://github.com/thoughtbot/Argo) - Functional JSON parsing library for Swift :large_orange_diamond:

## Games
* [Sage ★317](https://github.com/nvzqz/Sage) - A cross-platform chess library for Swift. :large_orange_diamond:
* [ShogibanKit](https://github.com/codelynx/ShogibanKit) - ShogibanKit is a framework for implementing complex Japanese Chess (Shogii) in Swift. No UI, nor AI. :large_orange_diamond:
* [SKTiled ★68](https://github.com/mfessenden/SKTiled) - Swift framework for working with Tiled assets in SpriteKit :large_orange_diamond:

## Gesture
* [Tactile ★596](https://github.com/delba/Tactile) - A better way to handle gestures on iOS :large_orange_diamond:
* [SwiftyGestureRecognition ★142](https://github.com/b3ll/SwiftyGestureRecognition) - Aids with prototyping UIGestureRecognizers in Xcode Playgrounds :large_orange_diamond:
* [DBPathRecognizer ★1040](https://github.com/didierbrun/DBPathRecognizer) - Gesture recognizer tool [Swift / iOS] :large_orange_diamond:
* [Sensitive ★426](https://github.com/igormatyushkin014/Sensitive) - Fresh look at work with gestures in Swift. :large_orange_diamond:

## Graphics
* [Graphicz ★22](https://github.com/SwiftKitz/Graphicz) - Light-weight, operator-overloading-free complements to CoreGraphics! :large_orange_diamond:
* [PKCoreTechniques ★141](https://github.com/pkluz/PKCoreTechniques) - The code for my CoreGraphics+CoreAnimation talk, held during the 2012 iOS Game Design Seminar at the Technical University Munich.
* [MPWDrawingContext ★89](https://github.com/mpw/MPWDrawingContext) - An Objective-C wrapper for CoreGraphics CGContext
* [DePict ★22](https://github.com/davidcairns/DePict) - A simple, declarative, functional drawing framework, in Swift! :large_orange_diamond:
* [SwiftSVG ★756](https://github.com/mchoe/SwiftSVG) -  A single pass SVG parser with multiple interface options (String, NS/UIBezierPath, CAShapeLayer, and NS/UIView). :large_orange_diamond:
* [InkKit ★327](https://github.com/shaps80/InkKit) - Write-Once, Draw-Everywhere for iOS and OSX -- Now in Swift! :large_orange_diamond:
* [YYAsyncLayer ★301](https://github.com/ibireme/YYAsyncLayer) - iOS utility classes for asynchronous rendering and display.
* [NXDrawKit ★930](https://github.com/Nicejinux/NXDrawKit) - NXDrawKit is a simple and easy but useful drawing kit for iPhone :large_orange_diamond:
* [jot ★1569](https://github.com/IFTTT/jot) - An iOS framework for easily adding drawings and text to images.
* [SVGKit ★2704](https://github.com/SVGKit/SVGKit) - Display and interact with SVG Images on iOS / OS X, using native rendering (CoreAnimation) (currently only supported for iOS - OS X code needs updating).
* [Snowflake ★771](https://github.com/onmyway133/Snowflake) - ❄️ SVG in Swift. :large_orange_diamond:

## Hardware
#### Bluetooth
* [Discovery](https://github.com/omergul123/Discovery) - A very simple library to discover and retrieve data from nearby devices (even if the peer app works at background).
* [LGBluetooth ★133](https://github.com/LGBluetooth/LGBluetooth) - Simple, block-based, lightweight library over CoreBluetooth. Will clean up your Core Bluetooth related code.
* [PeerKit ★669](https://github.com/jpsim/PeerKit) An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps. :large_orange_diamond:
* [simple-share ★124](https://github.com/lauraskelton/simple-share) - Easy Proximity-based Bluetooth LE Sharing for iOS.
* [BluetoothKit ★1461](https://github.com/rhummelmose/BluetoothKit) - Easily communicate between iOS/OSX devices using BLE. :large_orange_diamond:
* [CocoaMultipeer](https://github.com/manavgabhawala/CocoaMultipeer) - This repository is a peer to peer framework for OS X, iOS and watchOS 2 that presents a similar interface to the MultipeerConnectivity framework (which is iOS only) that lets you connect any 2 devices from any platform. :large_orange_diamond:
* [Bluetonium ★109](https://github.com/e-sites/Bluetonium) - Bluetooth mapping in Swift :large_orange_diamond:
* [BlueCap ★360](https://github.com/troystribling/BlueCap) - iOS Bluetooth LE framework :large_orange_diamond:
* [Apple Family ★18](https://github.com/kirankunigiri/Apple-Family) - Quickly connect Apple devices together with bluetooth, wifi, and USB.  :large_orange_diamond:
* [Bleu](https://github.com/1amageek/Bleu) - BLE (Bluetooth LE) for U  :large_orange_diamond:

#### Camera
* [TGCameraViewController ★1330](https://github.com/tdginternet/TGCameraViewController) - Custom camera with AVFoundation. Beautiful, light and easy to integrate with iOS projects.
* [PBJVision ★1661](https://github.com/piemonte/PBJVision) - iOS camera engine, features touch-to-record video, slow motion video, and photo capture.
* [Cool-iOS-Camera ★1137](https://github.com/GabrielAlva/Cool-iOS-Camera) - A fully customisable and modern camera implementation for iOS made with AVFoundation.
* [SCRecorder ★2500](https://github.com/rFlex/SCRecorder) - Camera engine with Vine-like tap to record, animatable filters, slow motion, segments editing.
* [ALCameraViewController ★1314](https://github.com/AlexLittlejohn/ALCameraViewController) - A camera view controller with custom image picker and image cropping. Written in Swift. :large_orange_diamond:
* [ImagePicker ★2731](https://github.com/hyperoslo/ImagePicker) - Reinventing the way ImagePicker works. :large_orange_diamond:
* [CameraManager ★566](https://github.com/imaginary-cloud/CameraManager) - Simple Swift class to provide all the configurations you need to create custom camera view in your app. :large_orange_diamond:
* [RSBarcodes_Swift ★518](https://github.com/yeahdongcn/RSBarcodes_Swift) - 1D and 2D barcodes reader and generators for iOS 8 with delightful controls. Now Swift. :large_orange_diamond:
* [LLSimpleCamera ★1028](https://github.com/omergul123/LLSimpleCamera) - A simple, customizable camera control - video recorder for iOS.
* [Fusuma ★1609](https://github.com/ytakzk/Fusuma) - Instagram-like photo browser and a camera feature with a few line of code in Swift. :large_orange_diamond:
* [BarcodeScanner ★598](https://github.com/hyperoslo/BarcodeScanner) - 🔎 Simple and beautiful barcode scanner. :large_orange_diamond:
* [JVTImageFilePicker ★41](https://github.com/mcmatan/JVTImageFilePicker) - Easy and beautiful way for a user to pick content, files or images. Written in Objective C.
* [HorizonSDK-iOS ★154](https://github.com/HorizonCamera/HorizonSDK-iOS) - State of the art real-time video recording / photo shooting iOS library.
* [FastttCamera ★1649](https://github.com/IFTTT/FastttCamera) - Fasttt and easy camera framework for iOS with customizable filters
* [DKCamera ★25](https://github.com/zhangao0086/DKCamera) - A lightweight & simple camera framework for iOS. Written in Swift. 🔶
* [NextLevel ★776](https://github.com/NextLevel/NextLevel) - Next Level is a media capture camera library for iOS. :large_orange_diamond:
* [CameraEngine ★370](https://github.com/remirobert/CameraEngine) - 🐒📷 Camera engine for iOS, written in Swift, above AVFoundation. 🐒 :large_orange_diamond:
* [SwiftyCam ★706](https://github.com/Awalz/SwiftyCam) -  A Snapchat Inspired iOS Camera Framework written in Swift. :large_orange_diamond:

#### Force Touch
* [QuickActions](https://github.com/ricardopereira/QuickActions) - Swift wrapper for iOS Home Screen Quick Actions (App Icon Shortcuts) :large_orange_diamond:
* [JustPeek ★45](https://github.com/justeat/JustPeek) - JustPeek is an iOS Library that adds support for Force Touch-like Peek and Pop interactions on devices that do not natively support this kind of interaction. :large_orange_diamond:

#### iBeacon
* [Proxitee ★14](https://github.com/Proxitee/iOS-SDK) - Allows developers to create proximity aware applications utilizing iBeacons & geo fences.
* [OWUProximityManager ★358](https://github.com/ohayon/OWUProximityManager) - iBeacons + CoreBluetooth.
* [Vicinity](https://github.com/Instrument/Vicinity) - Vicinity replicates iBeacons (by analyzing RSSI) and supports broadcasting and detecting low-energy bluetooth devices in the background.
* [BeaconEmitter ★795](https://github.com/lgaches/BeaconEmitter) - Turn your Mac as an iBeacon.
* [MOCA Proximity](https://mocaplatform.com/features) - Paid proximity marketing platform that lets you add amazing proximity  experiences to your app.
* [JMCBeaconManager ★132](https://github.com/izotx/JMCBeaconManager) - An iBeacon Manager class that is responsible for detecting beacons nearby. 🔶

## Layout
* [FlexboxLayout ★280](https://github.com/alexdrone/FlexboxLayout) - Port of Facebook's css-layout to Swift :large_orange_diamond:
* [Masonry ★14729](https://github.com/SnapKit/Masonry) - Harness the power of AutoLayout NSLayoutConstraints with a simplified, chainable and expressive syntax.
* [FLKAutoLayout ★1489](https://github.com/floriankugler/FLKAutoLayout) - UIView category which makes it easy to create layout constraints in code.
* [Façade ★708](https://github.com/mamaral/Facade) - Programmatic view layout for the rest of us - an autolayout alternative.
* [PureLayout ★6364](https://github.com/PureLayout/PureLayout) - The ultimate API for iOS & OS X Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible.
* [SnapKit ★9591](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X. :large_orange_diamond:
* [Cartography ★5472](https://github.com/robb/Cartography) - A declarative Auto Layout DSL for Swift :iphone::triangular_ruler: :large_orange_diamond:
* [AutoLayoutPlus ★25](https://github.com/ruipfcosta/AutoLayoutPlus) - A bit of steroids for AutoLayout, powered by Swift. :large_orange_diamond:
* [Neon ★3892](https://github.com/mamaral/Neon) - A powerful Swift programmatic UI layout framework. :large_orange_diamond:
* [MisterFusion ★250](https://github.com/marty-suzuki/MisterFusion) - A Swift DSL for AutoLayout. It is the extremely clear, but concise syntax, in addition, can be used in both Swift and Objective-C. :large_orange_diamond:
* [SwiftBox ★776](https://github.com/joshaber/SwiftBox) - Flexbox in Swift, using Facebook's css-layout. :large_orange_diamond:
* [ManualLayout ★258](https://github.com/isair/ManualLayout) - Easy to use and flexible library for manually laying out views and layers for iOS and tvOS. Supports AsyncDisplayKit. :large_orange_diamond:[e]
* [Stevia ★2013](https://github.com/freshOS/Stevia) - Elegant view layout for iOS. :large_orange_diamond:
* [Manuscript ★78](https://github.com/floriankrueger/Manuscript) - AutoLayoutKit in pure Swift. :large_orange_diamond:
* [FDTemplateLayoutCell ★7492](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) - Template auto layout cell for automatically UITableViewCell height calculating
* [SwiftAutoLayout ★644](https://github.com/indragiek/SwiftAutoLayout) - Tiny Swift DSL for Autolayout :large_orange_diamond:
* [FormationLayout ★52](https://github.com/evan-liu/FormationLayout) - Work with auto layout and size classes easily. :large_orange_diamond:
* [SwiftyLayout ★13](https://github.com/fhisa/SwiftyLayout) - Lightweight declarative auto-layout framework for Swift :large_orange_diamond:
* [Swiftstraints ★92](https://github.com/Skyvive/Swiftstraints) - Auto Layout In Swift Made Easy :large_orange_diamond:
* [SwiftBond ★3096](https://github.com/ReactiveKit/Bond) - Bond is a Swift binding framework that takes binding concepts to a whole new level. It's simple, powerful, type-safe and multi-paradigm. :large_orange_diamond:
* [Restraint ★71](https://github.com/puffinsupply/Restraint) - Minimal Auto Layout in Swift :large_orange_diamond:
* [EasyPeasy ★1470](https://github.com/nakiostudio/EasyPeasy) - Auto Layout made easy  :large_orange_diamond:
* [Auto Layout Magic](http://akordadev.github.io/AutoLayoutMagic/) - Build 1 scene, let Auto Layout Magic generate the  constraints for you!  Scenes look great across all devices! :large_orange_diamond:
* [Anchorman ★47](https://github.com/mergesort/Anchorman) - An autolayout library for the damn fine citizens of San Diego. :large_orange_diamond:
* [LayoutKit ★1961](https://github.com/linkedin/LayoutKit) - LayoutKit is a fast view layout library for iOS. :large_orange_diamond:
* [MarkupKit ★380](https://github.com/gk-brown/MarkupKit) - Declarative UI for iOS applications
* [Relayout ★579](https://github.com/stevestreza/Relayout) - Swift microframework for declaring Auto Layout constraints functionally :large_orange_diamond:
* [Anchorage ★242](https://github.com/Raizlabs/Anchorage) - A collection of operators and utilities that simplify iOS layout code. :large_orange_diamond:
* [Compose ★123](https://github.com/VivaReal/Compose) - Compose is a library that helps you compose complex and dynamic views. :large_orange_diamond:
* [BrickKit ★512](https://github.com/wayfair/brickkit-ios) - With BrickKit, you can create complex and responsive layouts in a simple way. It's easy to use and easy to extend. Create your own reusable bricks and behaviors. :large_orange_diamond:
* [Framezilla ★57](https://github.com/Otbivnoe/Framezilla) - Elegant library which wraps working with frames with a nice chaining syntax. :large_orange_diamond:
* [TinyConstraints ★1530](https://github.com/roberthein/TinyConstraints) -  The syntactic sugar that makes Auto Layout sweeter for human use. :large_orange_diamond:
* [MyLinearLayout ★1975](https://github.com/youngsoft/MyLinearLayout) - MyLayout is a powerful iOS UI framework implemented by Objective-C. It integrates the functions with Android Layout,iOS AutoLayout,SizeClass, HTML CSS float and flexbox and bootstrap.

#### Location
* [IngeoSDK ★85](https://github.com/IngeoSDK/ingeo-ios-sdk) - Always-On Location monitoring framework for iOS.
* [LocationManager ★2023](https://github.com/intuit/LocationManager) - Provides a block-based asynchronous API to request the current location, either once or continuously.
* [SwiftLocation ★1204](https://github.com/malcommac/SwiftLocation) - Location & Beacon Monitoring in Swift :large_orange_diamond:
* [SOMotionDetector ★969](https://github.com/SocialObjects-Software/SOMotionDetector) - Simple library to detect motion. Based on location updates and acceleration.
* [LocationPicker ★253](https://github.com/JeromeTan1997/LocationPicker) - A ready for use and fully customizable location picker for your app :large_orange_diamond:
* [LocationKit](https://locationkit.io) - Advanced location SDK - highly accurate location data with very low battery drain and contextual location information :large_orange_diamond:
* [BBLocationManager ★50](https://github.com/benzamin/BBLocationManager) - A Location Manager for easily implementing location services & geofencing in iOS.
* [set-simulator-location ★153](https://github.com/lyft/set-simulator-location) - CLI for setting location in the iOS simulator. :large_orange_diamond:

#### Other Hardware
* [MotionKit ★920](https://github.com/MHaroonBaig/MotionKit) - Get the data from Accelerometer, Gyroscope and Magnetometer in only Two or a few lines of code. CoreMotion now made insanely simple.
* [DarkLightning ★151](https://github.com/jensmeder/DarkLightning) - Simply the fastest way to transmit data between iOS/tvOS and OSX.
* [Deviice](https://github.com/andrealufino/Deviice) - Simply library to detect the device on which the app is running (and some properties) 🔶
* [DeviceKit ★1165](https://github.com/dennisweissmann/DeviceKit) - DeviceKit is a value-type replacement of UIDevice. :large_orange_diamond:
* [Luminous](https://github.com/andrealufino/Luminous) - Luminous is a big framework which can give you a lot of information (more than 50) about the current system. :large_orange_diamond:
* [Device ★866](https://github.com/Ekhoo/Device) - Light weight tool for detecting the current device and screen size written in swift. :large_orange_diamond:
* [WatchShaker ★133](https://github.com/ezefranca/WatchShaker) - WatchShaker is a watchOS helper to get your ⌚️ shake movement written in swift. :large_orange_diamond:
* [WatchCon ★23](https://github.com/abdullahselek/WatchCon) - WatchCon is a tool which enables creating easy connectivity between iOS and WatchOS. ⌚️
* [TapticEngine ★128](https://github.com/WorldDownTown/TapticEngine) - TapticEngine generates iOS Device vibrations. :large_orange_diamond:

## Localization
* [Hodor ★463](https://github.com/Aufree/Hodor) - Simple solution to localize your iOS App.
* [Swifternalization ★480](https://github.com/tomkowz/Swifternalization) - Localize iOS apps in a smarter way using JSON files. Swift framework. :large_orange_diamond:
* [Rubustrings ★40](https://github.com/dcordero/Rubustrings) - Check the format and consistency of Localizable.strings files
* [BartyCrouch ★200](https://github.com/Flinesoft/BartyCrouch) - Incrementally update/translate your Strings files from Code and Storyboards/XIBs. :large_orange_diamond:
* [Lin ★1224](https://github.com/questbeat/Lin) - Xcode plugin that provides auto-completion for NSLocalizedString.
* [LocalizationKit ★814](https://github.com/willpowell8/LocalizationKit_iOS) - Localization management in realtime from a web portal. Easily manage your texts and translations without redeploy and resubmission.
* [Localize-Swift ★1263](https://github.com/marmelroy/Localize-Swift) - Swift 2.0 friendly localization and i18n with in-app language switching :large_orange_diamond:
* [LocalizedView ★7](https://github.com/darkcl/LocalizedView) - Setting up application specific localized string within Xib file.
* [transai ★38](https://github.com/Jintin/transai) - command line tool help you manage localization string files.
* [lokalise](https://lokalise.co/en ) - Translation platform for software developers. Free for open source projects
* [Strsync ★94](https://github.com/metasmile/strsync) - Automatically translate and synchronize .strings files from base language.
* [IBLocalizable ★379](https://github.com/PiXeL16/IBLocalizable) - Localize your views directly in Interface Builder with IBLocalizable :large_orange_diamond:
* [extract-localizable-string-plugin-xcode ★216](https://github.com/viniciusmo/extract-localizable-string-plugin-xcode) - Xcode plugin for quickly creating localized strings
* [nslocalizer ★112](https://github.com/samdmarshall/nslocalizer) - A tool for finding missing and unused NSLocalizedStrings

## Logging
* [CleanroomLogger ★991](https://github.com/emaloney/CleanroomLogger) - A configurable and extensible Swift-based logging API that is simple, lightweight and performant. :large_orange_diamond:
* [CocoaLumberjack ★8999](https://github.com/CocoaLumberjack/CocoaLumberjack) - A fast & simple, yet powerful & flexible logging framework for Mac and iOS.
* [NSLogger ★3856](https://github.com/fpillet/NSLogger) - a high perfomance logging utility which displays traces emitted by client applications running on Mac OS X, iOS and Android.
* [QorumLogs ★683](https://github.com/goktugyil/QorumLogs) — Swift Logging Utility for Xcode & Google Docs. :large_orange_diamond:
* [Log ★618](https://github.com/delba/Log) - A logging tool with built-in themes, formatters, and a nice API to define your owns. :large_orange_diamond:
* [Rainbow ★826](https://github.com/onevcat/Rainbow) - Delightful console output for Swift developers. :large_orange_diamond:
* [KZLinkedConsole ★888](https://github.com/krzysztofzablocki/KZLinkedConsole) - Clickable links in your Xcode console, so you never wonder which class logged the message. http://merowing.info :large_orange_diamond:
* [SwiftyBeaver ★2633](https://github.com/SwiftyBeaver/SwiftyBeaver) - Convenient logging during development & release in Swift 2 & 3 :large_orange_diamond:
* [SwiftyTextTable ★84](https://github.com/scottrhoyt/SwiftyTextTable) - A lightweight tool for generating text tables. :large_orange_diamond:
* [Watchdog ★1359](https://github.com/wojteklu/Watchdog) - Class for logging excessive blocking on the main thread :large_orange_diamond:
* [XCGLogger](https://github.com/DaveWoodCom/XCGLogger) - A debug log framework for use in Swift projects. Allows you to log details to the console (and optionally a file), just like you would have with NSLog or println, but with additional information, such as the date, function name, filename and line number. :large_orange_diamond:
* [puree ★134](https://github.com/cookpad/puree-ios) - A log collector for iOS
* [AFNetworkActivityLogger ★470](https://github.com/AFNetworking/AFNetworkActivityLogger) - AFNetworking 2.0 Extension for Network Request Logging
* [Colors ★21](https://github.com/icodeforlove/Colors) - A pure Swift library for using ANSI codes. Basically makes command-line coloring and styling very easy! :large_orange_diamond:[e]
* [Loggerithm ★263](https://github.com/honghaoz/Loggerithm) - A lightweight Swift logger, uses `print` in development and `NSLog` in production. Support colourful and formatted output. :large_orange_diamond:
* [AELog ★7](https://github.com/tadija/AELog) - Simple, lightweight and flexible debug logging framework written in Swift. :large_orange_diamond:
* [AEConsole ★64](https://github.com/tadija/AEConsole) - Customizable Console UI overlay with debug log on top of your iOS App. :large_orange_diamond:
* [ReflectedStringConvertible ★48](https://github.com/mattcomi/ReflectedStringConvertible) - A protocol that allows any class to be printed as if it were a struct. :large_orange_diamond:
* [Evergreen ★62](https://github.com/knly/Evergreen) - Most natural Swift logging :large_orange_diamond:
* [Logkit ★120](https://github.com/logkit/logkit) - An efficient logging library for OS X, iOS, watchOS, and tvOS – written in Swift. Log to console, file, HTTP service, or your own endpoint. Simple to get started, but smartly customizable :large_orange_diamond:
* [SwiftTrace ★118](https://github.com/johnno1962/SwiftTrace) - Trace Swift and Objective-C method invocations :large_orange_diamond:
* [Willow ★970](https://github.com/Nike-Inc/Willow) - Willow is a powerful, yet lightweight logging library written in Swift. :large_orange_diamond:
* [Bugfender ★33](https://github.com/bugfender/BugfenderSDK-iOS) - Cloud storage for your app logs. Track user behaviour to find problems in your mobile apps.
* [LxDBAnything ★415](https://github.com/DeveloperLx/LxDBAnything) - Automate box any value! Print log without any format control symbol! Change debug habit thoroughly!
* [XLTestLog ★57](https://github.com/xareelee/XLTestLog) - Styling and coloring your XCTest logs on Xcode Console
* [XLFacility](https://github.com/swisspol/XLFacility) - Elegant and extensive logging facility for OS X & iOS (includes database, Telnet and HTTP servers)
* [Atlantis ★203](https://github.com/DrewKiino/Atlantis) - A powerful input-agnostic swift logging framework made to speed up development with maximum readability. :large_orange_diamond:
* [StoryTeller ★8](https://github.com/drekka/StoryTeller) - Taking a completely different approach to logging, Story Teller replacing fixed logging levels in It then uses dynamic expressions to control the logging so you only see what is important.
* [LumberMill ★2](https://github.com/ubclaunchpad/LumberMill) - Stupidly simple logging for iOS 10 and Swift 3.0
* [TinyConsole ★1651](https://github.com/Cosmo/TinyConsole) - A tiny log console to display information while using your iOS app. Written in Swift 3. :large_orange_diamond:
* [Lighty ★32](https://github.com/abdullahselek/Lighty) - Easy to use and lightweight logger for iOS, macOS, tvOS, watchOS and Linux with Swift 3. :large_orange_diamond:
* [JustLog ★152](https://github.com/justeat/JustLog) - Console, file and remote Logstash logging via TCP socket. :large_orange_diamond:
* [Twitter Logging Service ★156](https://github.com/twitter/ios-twitter-logging-service) - Twitter Logging Service is a robust and performant logging framework for iOS clients.
* [Reqres ★12](https://github.com/AckeeCZ/Reqres) - Network request and response body logger with Alamofire support :large_orange_diamond:
* [GodEye ★2397](https://github.com/zixun/GodEye) - Automaticly display Log,Crash,Network,ANR,Leak,CPU,RAM,FPS,NetFlow,Folder and etc with one line of code based on Swift. :large_orange_diamond:

## Machine Learning
* [Swift-AI ★4603](https://github.com/Swift-AI/Swift-AI) - Highly optimized Artificial Intelligence and Machine Learning library written in Swift. :large_orange_diamond:
* [Swift-Brain ★281](https://github.com/vlall/Swift-Brain) - Artificial Intelligence/Machine Learning data structures and Swift algorithms for future iOS development. Bayes theorem, Neural Networks, and more AI. :large_orange_diamond:
* [AIToolbox ★567](https://github.com/KevinCoble/AIToolbox) - A toolbox of AI modules written in Swift: Graphs/Trees, Linear Regression, Support Vector Machines, Neural Networks, PCA, KMeans, Genetic Algorithms, MDP, Mixture of Gaussians. :large_orange_diamond:
* [Tensorflow-iOS](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/ios_examples/) - The official Google-built powerful neural network library port for iOS.

## Maps
* [Route-me ★1290](https://github.com/route-me/route-me) - Open source map library for iOS.
* [NAMapKit ★253](https://github.com/neilang/NAMapKit) - Allows you to use custom maps in iphone applications and attempts to mimics some of the behaviour of the MapKit framework.
* [Mapbox GL ★1837](https://github.com/mapbox/mapbox-gl-native) - An OpenGL renderer for Mapbox Vector Tiles with SDK bindings for iOS.
* [CMMapLauncher ★183](https://github.com/citymapper/CMMapLauncher) - iOS library that makes it quick and easy to show directions in various mapping applications.
* [GEOSwift ★776](https://github.com/andreacremaschi/GEOSwift) - The Swift Geographic Engine. :large_orange_diamond:
* [PXGoogleDirections ★168](https://github.com/poulpix/PXGoogleDirections) - Google Directions API helper for iOS, written in Swift :large_orange_diamond:
* [Cluster ★416](https://github.com/efremidze/Cluster) - Easy Map Annotation Clustering. :large_orange_diamond:

## Math
* [Euler ★834](https://github.com/mattt/Euler) - Swift Custom Operators for Mathematical Notation :large_orange_diamond:
* [SwiftMath ★137](https://github.com/madbat/SwiftMath) - :triangular_ruler: A math framework for Swift. Includes: vectors, matrices, complex numbers, quaternions and polynomials. :large_orange_diamond:
* [Arithmosophi ★47](https://github.com/phimage/Arithmosophi) - A set of protocols for Arithmetic and Logical operations :large_orange_diamond:
* [Surge ★3589](https://github.com/mattt/Surge) - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation. :large_orange_diamond:
* [Upsurge ★81](https://github.com/aleph7/Upsurge) - Swift math :large_orange_diamond:
* [Swift-MathEagle ★21](https://github.com/rugheid/Swift-MathEagle) - A general math framework to make using math easy. Currently supports function solving and optimisation, matrix and vector algebra, complex numbers, big int and big frac and general handy extensions and functions. :large_orange_diamond:
* [iosMath ★590](https://github.com/kostub/iosMath) - A library for displaying beautifully rendered math equations. Enables typesetting LaTeX math formulae in iOS.
* [swift-pons ★209](https://github.com/dankogai/swift2-pons) - Protocol-Oriented Number System in Pure Swift :large_orange_diamond:
* [BigInt ★126](https://github.com/lorentey/BigInt) - Arbitrary-precision arithmetic in pure Swift :large_orange_diamond:
* [SigmaSwiftStatistics ★451](https://github.com/evgenyneu/SigmaSwiftStatistics) - A collection of functions for statistical calculation. :large_orange_diamond:
* [VectorMath ★133](https://github.com/nicklockwood/VectorMath) - A Swift library for Mac and iOS that implements common 2D and 3D vector and matrix functions, useful for games or vector-based graphics :large_orange_diamond:
* [Expression ★169](https://github.com/nicklockwood/Expression) - A Mac and iOS library for evaluating numeric expressions at runtime :large_orange_diamond:

## Media
#### Audio
* [AudioBus](https://developer.audiob.us/) - Add Next Generation Live App-to-App Audio Routing.
* [AudioKit ★3436](https://github.com/audiokit/AudioKit) - A powerful toolkit for synthesizing, processing, and analyzing sounds. :large_orange_diamond:
* [EZAudio ★3857](https://github.com/syedhali/EZAudio) - An iOS/OSX audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations.
* [novocaine ★2032](https://github.com/alexbw/novocaine) - Painless high-performance audio on iOS and Mac OS X.
* [QHSpeechSynthesizerQueue](https://github.com/quentinhayot/QHSpeechSynthesizerQueue) - Queue management system for AVSpeechSynthesizer (iOS Text to Speech).
* [Cephalopod ★74](https://github.com/evgenyneu/Cephalopod) - A sound fader for AVAudioPlayer written in Swift. :large_orange_diamond:
* [Chirp ★302](https://github.com/trifl/Chirp) - The easiest way to prepare, play, and remove sounds in your Swift app! :large_orange_diamond:
* [Beethoven ★227](https://github.com/vadymmarkov/Beethoven) - An audio processing Swift library for pitch detection of musical signals. :large_orange_diamond:
* [AudioPlayerSwift]( https://github.com/tbaranes/AudioPlayerSwift) - AudioPlayer is a simple class for playing audio in iOS, macOS and tvOS apps. :large_orange_diamond:
* [AudioPlayer](https://github.com/delannoyk/AudioPlayer) - AudioPlayer is syntax and feature sugar over AVPlayer. It plays your audio files (local & remote). :large_orange_diamond:
* [TuningFork ★333](https://github.com/comyar/TuningFork) - :musical_keyboard: Simple Tuner for iOS :large_orange_diamond:
* [MusicKit ★425](https://github.com/benzguo/MusicKit) - A framework for composing and transforming music in Swift :large_orange_diamond:
* [SubtleVolume ★561](https://github.com/andreamazz/SubtleVolume) - Replace the system volume popup with a more subtle indicator. :large_orange_diamond:
* [NVDSP ★320](https://github.com/bartolsthoorn/NVDSP) - iOS/OSX DSP for audio (with Novocaine)
* [SRGMediaPlayer-iOS ★58](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [IQAudioRecorderController ★373](https://github.com/hackiftekhar/IQAudioRecorderController) - A drop-in universal library allows to record audio within the app with a nice User Interface.
* [TheAmazingAudioEngine2 ★319](https://github.com/TheAmazingAudioEngine/TheAmazingAudioEngine2) - The Amazing Audio Engine is a sophisticated framework for iOS audio applications, built so you don't have to.
* [InteractivePlayerView ★212](https://github.com/AhmettKeskin/InteractivePlayerView) - Custom iOS music player view :large_orange_diamond:
* [ESTMusicIndicator ★330](https://github.com/Aufree/ESTMusicIndicator) - Cool Animated music indicator view written in Swift :large_orange_diamond:
* [QuietModemKit](https://github.com/quiet/QuietModemKit) - iOS framework for the Quiet Modem (data over sound)
* [SwiftySound](https://github.com/adamcichy/SwiftySound) - Super simple library that lets you play sounds with a single line of code (and much more). Written in Swift 3, supports iOS, macOS and tvOS. Cocoapods and Carthage compatible. :large_orange_diamond:
* [BPMAnalyser ★5](https://github.com/Luccifer/BPM-Analyser) - Fast and simple instrument to get the BPM rate from your audio-files. :large_orange_diamond:

#### GIF
* [YLGIFImage ★1595](https://github.com/liyong03/YLGIFImage) - Async GIF image decoder and Image viewer supporting play GIF images. It just use very less memory.
* [FLAnimatedImage ★5550](https://github.com/Flipboard/FLAnimatedImage) - Performant animated GIF engine for iOS
* [gifu ★1682](https://github.com/kaishin/gifu) - Highly performant animated GIF support for iOS in Swift :large_orange_diamond:
* [AnimatedGIFImageSerialization](https://github.com/mattt/AnimatedGIFImageSerialization) - Complete Animated GIF Support for iOS, with Functions, NSJSONSerialization-style Class, and (Optional) UIImage Swizzling
* [XAnimatedImage ★577](https://github.com/khaledmtaha/XAnimatedImage) - XAnimatedImage is a performant animated GIF engine for iOS written in Swift based on FLAnimatedImage :large_orange_diamond:
* [SwiftGif ★582](https://github.com/bahlo/SwiftGif) - :sparkles: A small UIImage extension with gif support :large_orange_diamond:
* [APNGKit ★1156](https://github.com/onevcat/APNGKit) - High performance and delightful way to play with APNG format in iOS. :large_orange_diamond:
* [YYImage ★872](https://github.com/ibireme/YYImage) - Image framework for iOS to display/encode/decode animated WebP, APNG, GIF, and more.
* [AImage ★705](https://github.com/wangjwchn/AImage) - A animated GIF&APNG engine for iOS in Swift with low memory & cpu usage.Optimized for Multi-Image case.:large_orange_diamond:
* [NSGIF2 ★48](https://github.com/metasmile/NSGIF2) - Simplify creation of a GIF from the provided video file url.
* [SwiftyGif ★617](https://github.com/kirualex/SwiftyGif) - High performance GIF engine :large_orange_diamond:

#### Image
* [GPU Image ★15517](https://github.com/BradLarson/GPUImage) - An open source iOS framework for GPU-based image and video processing.
* [UIImage DSP ★373](https://github.com/gdawg/uiimage-dsp) - IOS UIImage processing functions using the vDSP/Accelerate framework for speed.
* [AsyncImageView ★937](https://github.com/nicklockwood/AsyncImageView) - Simple extension of UIImageView for loading and displaying images asynchronously without lock up the UI.
* [SDWebImage ★17584](https://github.com/rs/SDWebImage) - Asynchronous image downloader with cache support with an UIImageView category.
* [DFImageManager ★1209](https://github.com/kean/DFImageManager) - Modern framework for fetching images from various sources. Zero config yet immense customization and extensibility. Uses NSURLSession.
* [MapleBacon ★183](https://github.com/zalando-incubator/MapleBacon) - An image download and caching library for iOS written in Swift. :large_orange_diamond:
* [NYTPhotoViewer ★2019](https://github.com/NYTimes/NYTPhotoViewer) - Slideshow and image viewer.
* [IDMPhotoBrowser ★2289](https://github.com/thiagoperes/IDMPhotoBrowser) - Photo Browser / Viewer.
* [JTSImageViewController ★2201](https://github.com/jaredsinclair/JTSImageViewController) - Interactive iOS image viewer.
* [Concorde ★1215](https://github.com/contentful-labs/Concorde) - Download and decode progressive JPEGs.
* [TOCropViewController ★1498](https://github.com/TimOliver/TOCropViewController) - A view controller that allows users to crop UIImage objects.
* [YXTMotionView ★77](https://github.com/hanton/YXTMotionView) - A custom image view that implements device motion scrolling.
* [PINRemoteImage ★2907](https://github.com/pinterest/PINRemoteImage) - A thread safe, performant, feature rich image fetcher.
* [SABlurImageView ★440](https://github.com/marty-suzuki/SABlurImageView) - Easily Adding Animated Blur/Unblur Effects To An Image. :large_orange_diamond:
* [FastImageCache ★7370](https://github.com/path/FastImageCache) - iOS library for quickly displaying images while scrolling.
* [BKAsciiImage ★396](https://github.com/bkoc/BKAsciiImage) - Convert UIImage to ASCII art
* [AlamofireImage ★2396](https://github.com/Alamofire/AlamofireImage) - An image component library for Alamofire. :large_orange_diamond:
* [Nuke ★2168](https://github.com/kean/Nuke) - Image loading, processing, caching and preheating :large_orange_diamond:
* [FlagKit ★1383](https://github.com/madebybowtie/FlagKit) - Beautiful flag icons for usage in apps and on the web. :large_orange_diamond:
* [YYWebImage](https://github.com/ibireme/YYWebImage) - Asynchronous image loading framework (supports WebP, APNG, GIF).
* [RSKImageCropper ★1626](https://github.com/ruslanskorb/RSKImageCropper) - An image cropper for iOS like in the Contacts app with support for landscape orientation.
* [Silo ★11](https://github.com/josejuanqm/Silo) - Image loading framework with loaders. :large_orange_diamond:
* [Ody ★39](https://github.com/josejuanqm/Ody) - Ody is an easy to use random image generator built with Swift, Perfect for placeholders. :large_orange_diamond:
* [Banana ★16](https://github.com/gauravkatoch007/banana) - Image slider with very simple interface. :large_orange_diamond:
* [JDSwiftAvatarProgress ★78](https://github.com/JellyDevelopment/JDSwiftAvatarProgress) - Easy customizable avatar image asynchronously with progress bar animated :large_orange_diamond:
* [Kingfisher ★8223](https://github.com/onevcat/Kingfisher) - A lightweight and pure Swift implemented library for downloading and caching image from the web. :large_orange_diamond:
* [EBPhotoPages ★1571](https://github.com/EddyBorja/EBPhotoPages) - A photo gallery for iOS with a modern feature set. Similar features as the Facebook photo browser.
* [UIImageView-BetterFace-Swift ★427](https://github.com/croath/UIImageView-BetterFace-Swift) - The Swift version of https://github.com/croath/UIImageView-BetterFace :large_orange_diamond:
* [KFSwiftImageLoader ★332](https://github.com/kiavashfaisali/KFSwiftImageLoader) - An extremely high-performance, lightweight, and energy-efficient pure Swift async web image loader with memory and disk caching for iOS and  Watch. :large_orange_diamond:
* [Toucan ★1927](https://github.com/gavinbunney/Toucan) - Fabulous Image Processing in Swift :large_orange_diamond:
* [ImageLoaderSwift ★258](https://github.com/hirohisa/ImageLoaderSwift) - A lightweight and fast image loader for iOS written in Swift. :large_orange_diamond:
* [ImageScout ★843](https://github.com/kaishin/ImageScout) - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG. :large_orange_diamond:
* [JLStickerTextView](https://github.com/luiyezheng/JLStickerTextView) - A UIImageView allow you to add multiple Label (multiple line text support) on it, you can edit, rotate, resize the Label as you want with one finger ,then render the text on Image. :large_orange_diamond:
* [Agrume ★174](https://github.com/JanGorman/Agrume) - A lemony fresh iOS image viewer written in Swift. :large_orange_diamond:
* [PASImageView ★164](https://github.com/abiaad/PASImageView) - Rounded async imageview downloader lightly cached and written in Swift :large_orange_diamond:
* [Navi ★111](https://github.com/nixzhu/Navi) - Focus on avatar caching. :large_orange_diamond:
* [SwiftPhotoGallery ★58](https://github.com/Inspirato/SwiftPhotoGallery) - Simple, fullscreen image gallery with tap, swipe, and pinch gestures. :large_orange_diamond:
* [MetalAcc ★177](https://github.com/wangjwchn/MetalAcc) - GPU-based Media processing library using Metal written in Swift.:large_orange_diamond:
* [MWPhotoBrowser ★7279](https://github.com/mwaterfall/MWPhotoBrowser) - A simple iOS photo and video browser with grid view, captions and selections.
* [UIImageColors ★1575](https://github.com/jathu/UIImageColors) - iTunes style color fetcher for UIImage. :large_orange_diamond:[e]
* [CDFlipView ★93](https://github.com/jibeex/CDFlipView) - A view that takes a set of images, make transition from one to another by using flipping effects.
* [GPUImage2 ★3063](https://github.com/BradLarson/GPUImage2) - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. :large_orange_diamond:
* [TGLParallaxCarousel ★379](https://github.com/taglia3/TGLParallaxCarousel) - A lightweight 3D Linear Carousel with parallax effect :large_orange_diamond:
* [ImageButter ★380](https://github.com/dollarshaveclub/ImageButter) - Makes dealing with images buttery smooth
* [SKPhotoBrowser ★1167](https://github.com/suzuki-0000/SKPhotoBrowser) - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift :large_orange_diamond:
* [YUCIHighPassSkinSmoothing ★635](https://github.com/YuAo/YUCIHighPassSkinSmoothing) - An implementation of High Pass Skin Smoothing using Apple's Core Image Framework
* [CLImageViewPopup ★19](https://github.com/vinbhai4u/CLImageViewPopup) - A simple Image full screen pop up :large_orange_diamond:
* [APKenBurnsView ★35](https://github.com/Alterplay/APKenBurnsView) - Ken Burns effect with face recognition! :large_orange_diamond:
* [Moa ★248](https://github.com/evgenyneu/moa) - An image download extension of the image view for iOS, tvOS and macOS. :large_orange_diamond:[e]
* [JMCMarchingAnts](https://github.com/izotx/JMCMarchingAnts) - Library that lets you add marching ants (animated) selection to the edges of the images. :large_orange_diamond:
* [ImageViewer ★1129](https://github.com/MailOnline/ImageViewer) - An image viewer à la Twitter :large_orange_diamond:
* [FaceAware ★1902](https://github.com/BeauNouvelle/FaceAware) - An extension that gives UIImageView the ability to focus on faces within an image when using AspectFill. :large_orange_diamond:
* [SwiftyAvatar ★146](https://github.com/dkalaitzidis/SwiftyAvatar) - A UiimageView class for creating circular avatar images, IBDesignable to make all changes via storyboard
* [ShinpuruImage ★58](https://github.com/FlexMonkey/ShinpuruImage) - Syntactic Sugar for Accelerate/vImage and Core Image Filters :large_orange_diamond:
* [ImagePickerSheetController ★1287](https://github.com/lbrndnr/ImagePickerSheetController) - ImagePickerSheetController is like the custom photo action sheet in iMessage just without the glitches. :large_orange_diamond:
* [ComplimentaryGradientView ★489](https://github.com/gkye/ComplimentaryGradientView) - Create complementary gradients generated from dominant and prominent colors in supplied image. Inspired by Grade.js. :large_orange_diamond:
* [ImageSlideshow ★532](https://github.com/zvonicek/ImageSlideshow) - Swift image slideshow with circular scrolling, timer and full screen viewer. :large_orange_diamond:
* [Imaginary ★62](https://github.com/hyperoslo/Imaginary) - 🦄 Remote images, as easy as one, two, three. :large_orange_diamond:
* [PPAssetsActionController ★45](https://github.com/pantuspavel/PPAssetsActionController) - Highly customizable Action Sheet Controller with Assets Preview. :large_orange_diamond:
* [Vulcan ★271](https://github.com/jinSasaki/Vulcan) - Multi image downloader with priority in Swift. :large_orange_diamond:
* [FacebookImagePicker ★61](https://github.com/terflogag/FacebookImagePicker) - Facebook album photo picker written in Swift. :large_orange_diamond:
* [Lightbox ★85](https://github.com/hyperoslo/Lightbox) - A convenient and easy to use image viewer for your iOS app. :large_orange_diamond:
* [AvatarImageView ★178](https://github.com/ayushn21/AvatarImageView) - AvatarImageView is a UIImageView subclass designed to show a user's profile picture, falling back to their initials when a picture is unavailable. :large_orange_diamond:
* [Ebblink ★3](https://github.com/ebbapp/ebblinkSDK) - An iOS SDK for sharing photos that automatically expire and can be deleted at any time.
* [Sharaku ★1115](https://github.com/makomori/Sharaku) - Instagram-like image filter ViewController. :large_orange_diamond:
* [CTPanoramaView ★662](https://github.com/scihant/CTPanoramaView) - Displays spherical or cylindrical panoramas or 360-photos with touch or motion based control options. :large_orange_diamond:
* [Twitter Image Pipline ★1342](https://github.com/twitter/ios-twitter-image-pipeline) - streamlined framework for fetching and storing images in an application.
* [TinyCrayon ★84](https://github.com/TinyCrayon/TinyCrayon-iOS-SDK) - A smart and easy-to-use image masking and cutout SDK for mobile apps. :large_orange_diamond:

#### Media Processing
* [SwiftOCR ★2396](https://github.com/garnele007/SwiftOCR) - Fast and simple OCR library written in Swift :large_orange_diamond:
* [QR Code Scanner](http://www.appcoda.com/qr-code-ios-programming-tutorial/) - QR Code implementation.
* [QRCode ★375](https://github.com/aschuch/QRCode) - A QRCode generator written in Swift. :large_orange_diamond:
* [EFQRCode ★1326](https://github.com/EyreFree/EFQRCode) - A better way to operate two-dimensional code in Swift. :large_orange_diamond:

#### PDF
* [Reader ★3730](https://github.com/vfr/Reader) - PDF Reader Core for iOS.
* [UIView 2 PDF ★24](https://github.com/RobertAPhillips/UIView_2_PDF) - PDF generator using UIViews or UIViews with an associated XIB
* [FolioReaderKit ★1294](https://github.com/FolioReader/FolioReaderKit) - A Swift ePub reader and parser framework for iOS. :large_orange_diamond:
* [PDFGenerator](https://github.com/sgr-ksmt/PDFGenerator) - A simple Generator of PDF in Swift. Generate PDF from view(s) or image(s). :large_orange_diamond:
* [SimplePDF ★77](https://github.com/nRewik/SimplePDF) - Create a simple PDF effortlessly. :large_orange_diamond:
* [SwiftPDFGenerator ★11](https://github.com/kayoslab/SwiftPDFGenerator) - PDF generator using UIViews; Swift Version of 'UIView 2 PDF'. :large_orange_diamond:
* [PSPDFKit](https://pspdfkit.com/) - Render PDF, add/edit annotations, fill forms, add/edit pages, view/create digital signatures.
* [TPPDF ★130](https://github.com/Techprimate/TPPDF) - Generate PDF using commands and automatic layout. :large_orange_diamond:

#### Streaming
* [lf.swift ★609](https://github.com/shogo4405/lf.swift) - Camera and Microphone streaming library via RTMP, HLS for iOS, macOS. :large_orange_diamond:
* [StreamingKit ★1506](https://github.com/tumtumtum/StreamingKit) - A fast and extensible gapless AudioPlayer/AudioStreamer for OSX and iOS.
* [Jukebox ★337](https://github.com/teodorpatras/Jukebox) - Player for streaming local and remote audio files. Written in Swift. :large_orange_diamond:
* [LFLiveKit ★2213](https://github.com/LaiFengiOS/LFLiveKit) - H264 and AAC Hard coding，support GPUImage Beauty， rtmp transmission，weak network lost frame，Dynamic switching rate
* [Airstream ★302](https://github.com/qasim/Airstream) - A framework for streaming audio between Apple devices using AirPlay.
* [OTAcceleratorCore ★14](https://github.com/opentok/accelerator-core-ios) - A painless way to integrate audio/video(screen sharing) to any iOS applications via Tokbox.

#### Video
* [VIMVideoPlayer ★250](https://github.com/vimeo/VIMVideoPlayer) - A simple wrapper around the AVPlayer and AVPlayerLayer classes.
* [MobilePlayer ★2049](https://github.com/mobileplayer/mobileplayer-ios) - A powerful and completely customizable media player for iOS.
* [XCDYouTubeKit ★2063](https://github.com/0xced/XCDYouTubeKit) - YouTube video player for iOS, tvOS and OS X
* [AVAnimator](http://www.modejong.com/AVAnimator/) - An open source iOS native library that makes it easy to implement non-trivial video/audio enabled apps.
* [Periscope VideoViewController ★460](https://github.com/gontovnik/Periscope-VideoViewController) - Video view controller with Periscope fast rewind control :large_orange_diamond:
* [SSVideoPlayer ★176](https://github.com/immrss/SSVideoPlayer) - A video player that support both local and network resource.
* [MHVideoPhotoGallery ★1937](https://github.com/mariohahn/MHVideoPhotoGallery) - A Photo and Video Gallery
* [PlayerView ★79](https://github.com/davidlondono/PlayerView) - Player View is a delegated view using AVPlayer of Swift :large_orange_diamond:
* [SRGMediaPlayer-iOS ★58](https://github.com/SRGSSR/SRGMediaPlayer-iOS) - The SRG Media Player library for iOS provides a simple way to add a universal audio / video player to any iOS application.
* [AVPlayerViewController-Subtitles ★53](https://github.com/mhergon/AVPlayerViewController-Subtitles) - AVPlayerViewController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [MPMoviePlayerController-Subtitles ★164](https://github.com/mhergon/MPMoviePlayerController-Subtitles) - MPMoviePlayerController-Subtitles is a library to display subtitles on iOS. It's built as a Swift extension and it's very easy to integrate. :large_orange_diamond:[e]
* [ZFPlayer](https://github.com/renzifeng/ZFPlayer) - Based on AVPlayer, support for the horizontal screen, vertical screen (full screen playback can also lock the screen direction), the upper and lower slide to adjust the volume, the screen brightness, or so slide to adjust the playback progress.
* [Player ★745](https://github.com/piemonte/Player) - ▶️ video player in Swift, simple way to play and stream media in your iOS or tvOS app :large_orange_diamond:
* [BMPlayer ★515](https://github.com/BrikerMan/BMPlayer) - video player in swift3 and swift2 for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brigtness and seek by slide. :large_orange_diamond:
* [VideoPager ★25](https://github.com/entotsu/VideoPager) - Paging Video UI, and some control components is available. :large_orange_diamond:
* [ios-360-videos ★129](https://github.com/NYTimes/ios-360-videos) - NYT360Video plays 360-degree video streamed from an AVPlayer.
* [swift-360-videos](https://github.com/team-pie/DDDKit) - Pure swift (no SceneKit) 3D library with focus on video and 360.
* [ABMediaView ★17](https://github.com/andrewboryk/ABMediaView) - UIImageView subclass for drop-in image, video, GIF, and audio display, with functionality for fullscreen and minimization to the bottom-right corner.

## Messaging

Also see [push notifications](#push-notifications)

* [LayerKit](https://github.com/layerhq/releases-ios) - iOS SDK for Layer, the easiest way to add in-app messaging (text, photos, videos, data) to any mobile or web application.
* [Twilio](https://www.twilio.com/) - Power modern communications. Build the next generation of voice and SMS applications.
* [Plivo](https://www.plivo.com/) - SMS API, Voice API, & Global Carrier Provider.
* [XMPPFramework ★5058](https://github.com/robbiehanson/XMPPFramework) - An XMPP Framework in Objective-C for Mac and iOS.
* [Chatto ★2681](https://github.com/badoo/Chatto) - A lightweight framework to build chat applications, made in Swift :large_orange_diamond:
* [JSQMessagesViewController ★10284](https://github.com/jessesquires/JSQMessagesViewController) - An elegant messages UI library for iOS.
* [Smooch](https://smooch.io) - Simple, lightweight SDKs and interfaces that enable customer messaging inside your apps and websites.
* [SlackTextViewController ★7629](https://github.com/slackhq/SlackTextViewController) - A drop-in UIViewController subclass with a growing text input view and other useful messaging features.
* [MessageKit ★656](https://github.com/MessageKit/MessageKit-iOS) - Eventually, a Swift re-write of JSQMessagesViewController :large_orange_diamond:
* [NoChat ★430](https://github.com/little2s/NoChat) - A lightweight chat UI framework for iOS. :large_orange_diamond:
* [NMessenger ★1836](https://github.com/eBay/NMessenger) - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift :large_orange_diamond:
* [Atlas ★3555](https://github.com/layerhq/Atlas-iOS) - A library of native iOS messaging user interface components for Layer.
* [Messenger ★2623](https://github.com/relatedcode/Messenger) - This is a native iOS Messenger app, making realtime chat conversations and audio calls with full offline support.
* [OTTextChatAccelerator ★7](https://github.com/opentok/accelerator-textchat-ios) - OpenTok Text Chat Accelerator Pack enables text messages between mobile or browser-based devices.

## Networking
* [AFNetworking ★29046](https://github.com/AFNetworking/AFNetworking) - A delightful iOS and OS X networking framework.
* [RestKit ★10025](https://github.com/RestKit/RestKit) - RestKit is an Objective-C framework for iOS that aims to make interacting with RESTful web services simple, fast and fun.
* [FSNetworking ★404](https://github.com/foursquare/FSNetworking) - Foursquare iOS networking library.
* [ASIHTTPRequest ★5783](https://github.com/pokeb/asi-http-request) - Easy to use CFNetwork wrapper for HTTP requests, Objective-C, Mac OS X and iPhone.
* [Overcoat ★1127](https://github.com/Overcoat/Overcoat) - Small but powerful library that makes creating REST clients simple and fun.
* [ROADFramework ★50](https://github.com/epam/road-ios-framework) - Attributed-oriented approach for interacting with web services. The framework has built-in json and xml serialization for requests and responses and can be easily extensible.
* [Alamofire ★23211](https://github.com/Alamofire/Alamofire) - Alamofire is an HTTP networking library written in Swift, from the creator of AFNetworking. :large_orange_diamond:
* [Transporter ★421](https://github.com/nghialv/Transporter) - A tiny library makes uploading and downloading easier. :large_orange_diamond:
* [CDZPinger ★43](https://github.com/cdzombak/CDZPinger) - Easy-to-use ICMP Ping.
* [NSRails ★528](https://github.com/dingbat/nsrails) - iOS/Mac OS framework for Rails.
* [NKMultipeer ★12](https://github.com/nathankot/NKMultipeer) - A testable abstraction over multipeer connectivity. :large_orange_diamond:
* [CocoaAsyncSocket ★8529](https://github.com/robbiehanson/CocoaAsyncSocket) - Asynchronous socket networking library for Mac and iOS.
* [Siesta](https://bustoutsolutions.github.io/siesta/) - Elegant abstraction for RESTful resources that untangles stateful messes. An alternative to callback- and delegate-based networking. :large_orange_diamond:
* [Reachability.swift ★3670](https://github.com/ashleymills/Reachability.swift) - Replacement for Apple's Reachability re-written in Swift with closures :large_orange_diamond:
* [NetworkEye ★914](https://github.com/coderyi/NetworkEye) - a iOS network debug library, It can monitor HTTP requests within the App and displays information related to the request.
* [Netfox ★1923](https://github.com/kasketis/netfox) - A lightweight, one line setup, iOS / OSX network debugging library! :large_orange_diamond:
* [OctopusKit ★1](https://github.com/icoco/OctopusKit) - A simplicity but graceful solution for invoke RESTful web service APIs.
* [Moya ★5624](https://github.com/Moya/Moya) - Network abstraction layer written in Swift. :large_orange_diamond:
* [TWRDownloadManager ★311](https://github.com/chasseurmic/TWRDownloadManager) - A modern download manager based on NSURLSession to deal with asynchronous downloading, management and persistence of multiple files.
* [HappyDns ★274](https://github.com/qiniu/happy-dns-objc) - A Dns library, support custom dns server, dnspod httpdns. Only support A record.
* [Bridge ★93](https://github.com/BridgeNetworking/Bridge) - A simple extensible typed networking library. Intercept and process/alter requests and responses easily. :large_orange_diamond:
* [TRON ★333](https://github.com/MLSDev/TRON) - Lightweight network abstraction layer, written on top of Alamofire :large_orange_diamond:
* [EVCloudKitDao ★477](https://github.com/evermeer/EVCloudKitDao) - Simplified access to Apple's CloudKit :large_orange_diamond:
* [EVURLCache ★236](https://github.com/evermeer/EVURLCache) - a NSURLCache subclass for handling all web requests that use NSURLRequest :large_orange_diamond:
* [ResponseDetective ★1451](https://github.com/netguru/ResponseDetective) - Sherlock Holmes of the networking layer. :large_orange_diamond:
* [Pitaya ★838](https://github.com/johnlui/Pitaya) - A Swift HTTP / HTTPS networking library just incidentally execute on machines :large_orange_diamond:
* [Just ★959](https://github.com/JustHTTP/Just) - Swift HTTP for Humans :large_orange_diamond:
* [agent ★618](https://github.com/hallas/agent) - Minimalistic Swift HTTP request agent for iOS and OS X :large_orange_diamond:
* [Reach ★399](https://github.com/Isuru-Nanayakkara/Reach) - A simple class to check for internet connection availability in Swift. :large_orange_diamond:
* [SwiftHTTP ★1651](https://github.com/daltoniam/SwiftHTTP) - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests. :large_orange_diamond:
* [Netdiag ★51](https://github.com/qiniu/iOS-netdiag) - A network diagnosis library. Support Ping/TcpPing/Rtmp/TraceRoute/DNS/external IP/external DNS.
* [AFNetworkingHelper ★17](https://github.com/betacraft/AFNetworkingHelper) - A custom wrapper over AFNetworking library that we use inside RC extensively
* [NetKit ★4](https://github.com/azizuysal/NetKit) - A Concise HTTP Framework in Swift. :large_orange_diamond:
* [RealReachability ★2248](https://github.com/dustturtle/RealReachability) - We need to observe the REAL reachability of network. That's what RealReachability do.
* [MonkeyKing ★1694](https://github.com/nixzhu/MonkeyKing) - MonkeyKing helps you post messages to Chinese Social Networks. :large_orange_diamond:
* [NetworkKit ★27](https://github.com/imex94/NetworkKit) - Lightweight Networking and Parsing framework made for iOS, Mac, WatchOS and tvOS. :large_orange_diamond:
* [APIKit ★1166](https://github.com/ishkawa/APIKit) - A networking library for building type safe web API client in Swift. :large_orange_diamond:
* [ws ☁️](https://github.com/freshOS/ws) - Elegant JSON WebService in Swift.:large_orange_diamond:
* [SPTDataLoader ★571](https://github.com/spotify/SPTDataLoader) - The HTTP library used by the Spotify iOS client.
* [SWNetworking ★22](https://github.com/skywite/SWNetworking) - Powerful high-level iOS, OS X and tvOS networking library.
* [Networking ★1002](https://github.com/3lvis/Networking) - Simple HTTP Networking in Swift a NSURLSession wrapper with image caching support :large_orange_diamond:
* [SOAPEngine ★399](https://github.com/priore/SOAPEngine) - This generic SOAP client allows you to access web services using a your iOS app, Mac OS X app and AppleTV app.
* [Swish](https://github.com/thoughtbot/Swish) - Nothing but Net(working) :large_orange_diamond:
* [Malibu ★246](https://github.com/hyperoslo/Malibu) - :surfer: Malibu is a networking library built on promises :large_orange_diamond:
* [YTKNetwork ★4265](https://github.com/yuantiku/YTKNetwork) - YTKNetwork is a high level request util based on AFNetworking.
* [UnboxedAlamofire ★46](https://github.com/serejahh/UnboxedAlamofire) - Alamofire + Unbox: the easiest way to download and decode JSON into swift objects. :large_orange_diamond:
* [MMLanScan ★153](https://github.com/mavris/MMLanScan) - An iOS LAN Network Scanner library
* [Domainer ★5](https://github.com/FelixLinBH/Domainer) - Manage multi-domain url auto mapping ip address table
* [Restofire ★136](https://github.com/Restofire/Restofire) - Restofire is a protocol oriented network abstraction layer in swift that is built on top of Alamofire to use services in a declartive way :large_orange_diamond:
* [AFNetworking+RetryPolicy ★120](https://github.com/kubatruhlar/AFNetworking-RetryPolicy) - An objective-c category that adds the ability to set the retry logic for requests made with AFNetworking.
* [SwiftyZeroMQ ★15](https://github.com/azawawi/SwiftyZeroMQ) - ZeroMQ Swift Bindings for iOS, macOS, tvOS and watchOS. :large_orange_diamond: ⌚
* [Nikka ★11](https://github.com/JustaLab/Nikka) - A super simple Networking wrapper that supports many JSON libraries, Futures and Rx :large_orange_diamond: ⌚
* [XMNetworking ★656](https://github.com/kangzubin/XMNetworking) - A lightweight but powerful network library with simplified and expressive syntax based on AFNetworking.
* [Merhaba ★26](https://github.com/abdullahselek/Merhaba) - Bonjour networking for discovery and connection between iOS, macOS and tvOS devices.
* [DBNetworkStack ★15](https://github.com/dbsystel/DBNetworkStack) - Resource-oritented networking which is typesafe, extendable, composeable and makes testing a lot easier. :large_orange_diamond:
* [EFInternetIndicator ★80](https://github.com/ezefranca/EFInternetIndicator) - A little swift Internet error status indicator using ReachabilitySwift. :large_orange_diamond:
* [AFNetworking-Synchronous ★122](https://github.com/paulmelnikow/AFNetworking-Synchronous) - Synchronous requests for AFNetworking 1.x, 2.x, and 3.x.
* [QwikHttp ★1](https://github.com/logansease/QwikHttp) - a robust, yet lightweight and simple to use HTTP networking library designed for RESTful APIs. 🔶 

#### Email

* [Mail Core 2 ★1508](https://github.com/MailCore/mailcore2) - MailCore 2 provide a simple and asynchronous API to work with e-mail protocols IMAP, POP and SMTP.
* [Postal ★413](https://github.com/snipsco/Postal) - A swift framework providing simple access to common email providers. :large_orange_diamond:

#### Representations

 * [apollo-ios ★428](https://github.com/apollographql/apollo-ios) - A GraphQL client for iOS, written in Swift :large_orange_diamond:
 * [JSONRPCKit ★61](https://github.com/bricklife/JSONRPCKit) - A JSON-RPC 2.0 library purely written in Swift :large_orange_diamond:
 * [protobuf-swift ★708](https://github.com/alexeyxo/protobuf-swift) - Google ProtocolBuffers for Apple Swift http://protobuf.io/#swift :large_orange_diamond:

## Notifications

#### Push Notifications
* [Orbiter ★694](https://github.com/mattt/Orbiter) - Push Notification Registration for iOS.
* [PEM](https://github.com/fastlane/fastlane/tree/master/pem) - Automatically generate and renew your push notification profiles.
* [Knuff](https://github.com/KnuffApp/Knuff) - The debug application for Apple Push Notification Service (APNS).
* [FBNotifications ★437](https://github.com/facebook/FBNotifications) - Facebook Analytics In-App Notifications Framework.
* [NWPusher](https://github.com/noodlewerk/NWPusher) - OS X and iOS application and framework to play with the Apple Push Notification service (APNs)
* [SimulatorRemoteNotifications ★1155](https://github.com/acoomans/SimulatorRemoteNotifications) - Library to send mock remote notifications to the iOS simulator

##### Push Notification Providers

Most of these are paid services, some have free tiers.

* [Urban Airship](https://www.urbanairship.com/products/mobile-app-engagement )
* [Growth Push](https://growthpush.com) - Popular in Japan.
* [Appboy](https://www.appboy.com)
* [Batch](https://batch.com)
* [Boxcar](https://boxcar.io)
* [Carnival](http://www.carnival.io)
* [Catapush](http://www.catapush.com/)
* [Netmera](http://www.netmera.com)
* [OneSignal](https://onesignal.com) - Free.
* [PushBots](https://pushbots.com/)
* [Pushwoosh](https://www.pushwoosh.com)
* [Pushkin ★132](https://github.com/Nordeus/pushkin) - Free and open-source.
* [Pusher](https://pusher.com/push-notifications) - Free and unlimited.

#### Local Notifications
* [DLLocalNotifications ★37](https://github.com/d7laungani/DLLocalNotifications) -  Easily create Local Notifications in swift - Wrapper of UserNotifications Framework. :large_orange_diamond:

## Parsing

#### CSV
* [CSwiftV ★114](https://github.com/Daniel1of1/CSwiftV) - A csv parser written in swift conforming to rfc4180 :large_orange_diamond:
* [SwiftCSV ★264](https://github.com/naoty/SwiftCSV) - CSV parser for Swift :large_orange_diamond:

#### JSON
* [JSON-Framework ★3787](https://github.com/stig/json-framework) -  This framework implements a strict JSON parser and generator in Objective-C.
* [Mantle ★10516](https://github.com/Mantle/Mantle) - Model framework for Cocoa and Cocoa Touch.
* [Groot ★458](https://github.com/gonzalezreal/Groot) - Convert JSON dictionaries and arrays to and from Core Data managed objects.
* [KZPropertyMapper ★1116](https://github.com/krzysztofzablocki/KZPropertyMapper) - Data mapping and validation with minimal amount of code.
* [JSONModel ★6095](https://github.com/JSONModel/JSONModel) - Magical Data Modelling Framework for JSON. Create rapidly powerful, atomic and smart data model classes.
* [SwiftyJSON ★14286](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift. :large_orange_diamond:
* [FastEasyMapping ★498](https://github.com/Yalantis/FastEasyMapping) - Serialize & deserialize JSON fast.
* [OCMapper ★344](https://github.com/aryaxt/OCMapper) - Objective-C & Swift library to easily map NSDictionary to model objects. :large_orange_diamond:
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - A framework written in Swift that makes it easy for you to convert your Model objects (Classes and Structs) to and from JSON. :large_orange_diamond:
* [JASON ★976](https://github.com/delba/JASON) - JSON parsing with outstanding performances and convenient operators. :large_orange_diamond:
* [Gloss ★1438](https://github.com/hkellaway/Gloss) - A shiny JSON parsing library in Swift. :large_orange_diamond:
* [Cereal ★363](https://github.com/Weebly/Cereal) - Swift object serialization :large_orange_diamond:
* [SwiftyJSONAccelerator ★465](https://github.com/insanoid/SwiftyJSONAccelerator) - Generate Swift model files from JSON using either SwiftyJSON or ObjectMapper. Supports NSCoding and provides method for JSON string representation of the model. :large_orange_diamond:
* [JSONCodable ★597](https://github.com/matthewcheok/JSONCodable) - Hassle-free JSON encoding and decoding in Swift :large_orange_diamond:
* [Coolie](https://github.com/nixzhu/Coolie) - Coolie helps you to create models (& their constructors) from JSON file. :large_orange_diamond:
* [Tailor ★229](https://github.com/zenangst/Tailor) - A super fast & convenient object mapper tailored for your needs. :large_orange_diamond:
* [alexander ★34](https://github.com/hodinkee/alexander) - An extremely simple JSON helper written in Swift. :large_orange_diamond:
* [Freddy ★1080](https://github.com/bignerdranch/Freddy) - A reusable framework for parsing JSON in Swift. :large_orange_diamond:
* [mapper ★901](https://github.com/lyft/mapper) - A JSON deserialization library for Swift :large_orange_diamond:
* [AlamofireJsonToObjects ★139](https://github.com/evermeer/AlamofireJsonToObjects) - An Alamofire extension which converts JSON response data into swift objects using EVReflection :large_orange_diamond:
* [Jay ★123](https://github.com/DanToml/Jay) - Pure-Swift JSON parser & formatter. Linux & OS X ready. :large_orange_diamond:
* [YYModel ★2729](https://github.com/ibireme/YYModel) - High performance model framework for iOS/OSX.
* [Alembic ★93](https://github.com/ra1028/Alembic) - Functional JSON parsing, mapping to objects, and serialize to JSON :large_orange_diamond:
* [Wrap ★468](https://github.com/JohnSundell/Wrap) - The easy to use Swift JSON encoder :large_orange_diamond:
* [Arrow 🏹 ★233](https://github.com/freshOS/Arrow) - Elegant JSON Parsing in Swift. :large_orange_diamond:
* [Decodable ★1042](https://github.com/Anviking/Decodable) - Swift 2/3 JSON parsing done (more) right :large_orange_diamond:
* [Genome](https://github.com/LoganWright/Genome) - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0 (Supports Linux) :large_orange_diamond:
* [Tyro ★48](https://github.com/typelift/Tyro) - Functional JSON parsing and encoding :large_orange_diamond:
* [Unbox ★1516](https://github.com/JohnSundell/Unbox) - The easy to use Swift JSON decoder :large_orange_diamond:
* [JSONJoy-Swift ★341](https://github.com/daltoniam/JSONJoy-Swift) - Convert JSON to Swift objects. :large_orange_diamond:
* [LazyObject ★8](https://github.com/iwasrobbed/LazyObject) - Lazily deserialize JSON into strongly typed Swift objects :large_orange_diamond:
* [JSONExport ★2513](https://github.com/Ahmed-Ali/JSONExport) - JSONExport is a desktop application for Mac OS X which enables you to export JSON objects as model classes with their associated constructors, utility methods, setters and getters in your favorite language. :large_orange_diamond:
* [Elevate ★598](https://github.com/Nike-Inc/Elevate) - Elevate is a JSON parsing framework that leverages Swift to make parsing simple, reliable and composable. :large_orange_diamond:
* [MJExtension ★6835](https://github.com/CoderMJLee/MJExtension) - A fast, convenient and nonintrusive conversion between JSON and model. Your model class don't need to extend another base class. You don't need to modify any model file.
* [AlamofireObjectMapper ★1728](https://github.com/tristanhimmelman/AlamofireObjectMapper) - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper :large_orange_diamond:
* [GuardedSwiftyJSON ★4](https://github.com/wiggzz/GuardedSwiftyJSON) - An add-on to SwiftyJSON to make it easier to create failable initalizers for data models. :large_orange_diamond:
* [JAYSON ★222](https://github.com/muukii/JAYSON) - Strict and Scalable JSON library. :large_orange_diamond:
* [HandyJSON ★851](https://github.com/alibaba/handyjson) - A handy swift JSON-object serialization/deserialization library for swift 2.x/3.x. :large_orange_diamond:
* [Marshal](https://github.com/utahiosmac/Marshal) - Marshaling the typeless wild west of [String: Any] (Protocol based).
* [Motis](https://github.com/mobilejazz/Motis) - Easy JSON to NSObject mapping using Cocoa's key value coding (KVC).
* [NSTEasyJSON](https://github.com/bernikowich/NSTEasyJSON) - The easiest way to deal with JSON data in Objective-C (similar to SwiftyJSON).
* [Serpent ★258](https://github.com/nodes-ios/Serpent) - A protocol to serialize Swift structs and classes for encoding and decoding. :large_orange_diamond:
* [MagicMapper ★24](https://github.com/adrianitech/magic-mapper-swift) - :star2: Super light and easy automatic JSON to model mapper. :large_orange_diamond:

#### XML & HTML
* [AEXML ★635](https://github.com/tadija/AEXML) - Simple and lightweight XML parser written in Swift. :large_orange_diamond:
* [Ji ★688](https://github.com/honghaoz/Ji) - XML/HTML parser for Swift. :large_orange_diamond:
* [Ono ★2111](https://github.com/mattt/Ono) - A sensible way to deal with XML & HTML for iOS & OS X
* [AlamofireXmlToObjects ★57](https://github.com/evermeer/AlamofireXmlToObjects) - Fetch a XML feed and parse it into objects :large_orange_diamond:
* [Fuzi ★519](https://github.com/cezheng/Fuzi) - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support :large_orange_diamond:
* [Kanna](https://github.com/tid-kijyun/Kanna)  - Kanna(鉋) is an XML/HTML parser for MacOSX/iOS. :large_orange_diamond:
* [SwiftyXMLParser ★106](https://github.com/yahoojapan/SwiftyXMLParser) - Simple XML Parser implemented in Swift :large_orange_diamond:
* [HTMLKit ★62](https://github.com/iabudiab/HTMLKit) - An Objective-C framework for your everyday HTML needs.
* [SWXMLHash ★745](https://github.com/drmohundro/SWXMLHash) - Simple XML parsing in Swift :large_orange_diamond:
* [SwiftyXML ★13](https://github.com/chenyunguiMilook/SwiftyXML) - The most swifty way to deal with XML data in swift 3 :large_orange_diamond:

#### Other Parsing
* [WKZombie ★786](https://github.com/mkoehnke/WKZombie) - WKZombie is a Swift framework for iOS/OSX to navigate within websites and collect data without the need of User Interface or API, also known as Headless browser. It can be used to run automated tests or manipulate websites using Javascript. :large_orange_diamond:
* [URLPreview ★179](https://github.com/itsmeichigo/URLPreview) - An NSURL extension for showing preview info of webpages :large_orange_diamond:
* [FeedKit ★93](https://github.com/nmdias/FeedKit) - An RSS and Atom feed parser written in Swift :large_orange_diamond:
* [Erik ★217](https://github.com/phimage/Erik) - Erik is an headless browser based on WebKit. An headless browser allow to run functional tests, to access and manipulate webpages using javascript. :large_orange_diamond:
* [URLEmbeddedView ★382](https://github.com/marty-suzuki/URLEmbeddedView) - Automatically caches the object that is confirmed the Open Graph Protocol, and displays it as URL embedded card. :large_orange_diamond:
* [SwiftyConfiguration ★101](https://github.com/ykyouhei/SwiftyConfiguration) - Modern Swift API for Plist. :large_orange_diamond:

## Passbook
* [passbook ★212](https://github.com/frozon/passbook) - Passbook gem let's you create pkpass for passbook iOS 6+.
* [Dubai ★313](https://github.com/nomad/dubai) - Generate and Preview Passbook Passes.
* [Passkit](https://passkit.com) - Design, Create and validate Passbook Passes.

## Payments
* [Caishen ★626](https://github.com/prolificinteractive/Caishen) - A Payment Card UI & Validator for iOS. :large_orange_diamond:
* [Stripe](https://stripe.com) - Payment integration on your app with PAY. Suitable for people with low knowlege on Backend.
* [Braintree](https://www.braintreepayments.com) - Free payment processing on your first $50k. Requires Backend.
* [Venmo ★128](https://github.com/venmo/venmo-ios-sdk) Make and accept payments in your iOS app via Venmo.
* [Moltin](https://www.moltin.com/ios-ecommerce-sdk/) - Add eCommerce to your app with a simple SDK, so you can create a store and sell physical products, no backend required.
* [PatronKit ★348](https://github.com/MosheBerman/PatronKit) - A framework to add patronage to your apps. :large_orange_diamond:
* [SwiftyStoreKit ★1883](https://github.com/bizz84/SwiftyStoreKit) - Lightweight In App Purchases Swift framework for iOS 8.0+ and OSX 9.0+ :large_orange_diamond:
* [InAppFramework ★33](https://github.com/sandorgyulai/InAppFramework) - In App Purchase Manager framework for iOS :large_orange_diamond:
* [SwiftInAppPurchase ★15](https://github.com/rpzzzzzz/SwiftInAppPurchase) - Simply code In App Purchases with this Swift Framework :large_orange_diamond:
* [monza ★81](https://github.com/gabrielgarza/monza) - Ruby Gem for Rails - Easy iTunes In-App Purchase Receipt validation, including auto-renewable subscriptions
* [EasyIAPs ★5](https://github.com/aaalveee/EasyIAPs) - An easy way to manage In App Purchases
* [PayPal ★810](https://github.com/paypal/PayPal-iOS-SDK) - Accept payments in your iOS app via PayPal.
* [card.io-iOS-SDK ★1720](https://github.com/card-io/card.io-iOS-SDK) - card.io provides fast, easy credit card scanning in mobile apps
* [SwiftLuhn ★92](https://github.com/MaxKramer/SwiftLuhn) - Debit/Credit card validation port of the Luhn Algorithm in Swift :large_orange_diamond:
* [ObjectiveLuhn ★116](https://github.com/MaxKramer/ObjectiveLuhn) - Luhn Credit Card Validation Algorithm
* [RMStore ★1935](https://github.com/robotmedia/RMStore) - A lightweight iOS library for In-App Purchases
* [MFCard ★237](https://github.com/mobilefirstinc/MFCard) - Easily integrate Credit Card payments in iOS App / Customisable Card UI
* [TPInAppReceipt ★12](https://github.com/tikhop/TPInAppReceipt) - Reading and Validating In App Store Receipt :large_orange_diamond:

## Permissions
* [PermissionScope](https://github.com/nickoneill/PermissionScope) - Intelligent iOS permissions UI and unified API (Supports Location, Notifications, Camera, Contacts, Calendar, Photos, Microphone, BT, Activity Monitoring, HealthKit and CloudKit). :large_orange_diamond:
* [Proposer](https://github.com/nixzhu/Proposer) - Make permission request easier (Supports Camera, Photos, Microphone, Contacts, Location). :large_orange_diamond:
* [ICanHas](https://github.com/wircho/ICanHas) - Simplifies iOS user permission requests (Supports location, push notifications, camera, contacts, calendar, photos). :large_orange_diamond:
* [VWWPermissionKit ★131](https://github.com/zakkhoyt/VWWPermissionKit) - A visual permission manager for iOS.
* [ISHPermissionKit ★558](https://github.com/iosphere/ISHPermissionKit) - A unified way for iOS apps to request user permissions.
* [JLPermissions ★392](https://github.com/jlaws/JLPermissions) - An iOS pre-permissions utility that lets developers ask users on their own dialog for calendar, contacts, location, photos, reminders, twitter, push notifications and more, before making the system-based permission request.
* [ClusterPrePermissions ★1162](https://github.com/clusterinc/ClusterPrePermissions) - Reusable pre-permissions utility that lets developers ask users for access in their own dialog, before making the system-based request.
* [Permission ★2108](https://github.com/delba/Permission) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [STLocationRequest ★522](https://github.com/SvenTiigi/STLocationRequest) - A simple and elegant 3D-Flyover location request screen written Swift. :large_orange_diamond:
* [PAPermissions ★641](https://github.com/pascalbros/PAPermissions) - A unified API to ask for permissions on iOS :large_orange_diamond:
* [AREK ★727](https://github.com/ennioma/arek) - AREK is a clean and easy to use wrapper over any kind of iOS permission. :large_orange_diamond:
* [RequestPermission ★1327](https://github.com/IvanVorobei/RequestPermission) - simple permission request with beautiful UI :large_orange_diamond:

## Products
* [Import.io](https://www.import.io/) - Instantly Turn Web Pages into Data.
* [Tapglue](https://www.tapglue.com/) - Build social products and a activity feed with a few lines of code.
* [OpenShop.io ★250](https://github.com/openshopio/openshop.io-ios) - mobile e-commerce solution connected to Facebook Ads and Google.

## Reactive Programming
* [RxSwift ★9027](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift :large_orange_diamond:
* [RxOptional ★7](https://github.com/thanegill/RxOptional) - RxSwift extentions for Swift optionals and "Occupiable" types :large_orange_diamond:
* [ReactiveTask ★117](https://github.com/Carthage/ReactiveTask) - Flexible, stream-based abstraction for launching processes :large_orange_diamond:
* [ReactiveCocoa ★17141](https://github.com/ReactiveCocoa/ReactiveCocoa) - Streams of values over time.
* [RxMediaPicker ★74](https://github.com/RxSwiftCommunity/RxMediaPicker) - A reactive wrapper built around UIImagePickerController. :large_orange_diamond:
* [ReactiveCoreData](https://github.com/apparentsoft/ReactiveCoreData) - ReactiveCoreData (RCD) is an attempt to bring Core Data into the ReactiveCocoa (RAC) world.
* [ReSwift ★3547](https://github.com/ReSwift/ReSwift) - Unidirectional Data Flow in Swift - Inspired by Redux :large_orange_diamond:
* [ReactiveKit ★843](https://github.com/ReactiveKit/ReactiveKit) - ReactiveKit is a collection of Swift frameworks for reactive and functional reactive programming. :large_orange_diamond:
* [RxPermission ★142](https://github.com/sunshinejr/RxPermission) - RxSwift bindings for Permissions API in iOS. :large_orange_diamond:
* [RxAlamofire ★632](https://github.com/RxSwiftCommunity/RxAlamofire) - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire :large_orange_diamond:
* [RxRealm ★379](https://github.com/RxSwiftCommunity/RxRealm) - Rx wrapper for Realm's collection types :large_orange_diamond:
* [RxMultipeer ★43](https://github.com/RxSwiftCommunity/RxMultipeer) - A testable RxSwift wrapper around MultipeerConnectivity :large_orange_diamond:
* [RxBluetoothKit ★531](https://github.com/Polidea/RxBluetoothKit) - iOS & OSX Bluetooth library for RxSwift :large_orange_diamond:
* [RxGesture ★318](https://github.com/RxSwiftCommunity/RxGesture) - RxSwift reactive wrapper for view gestures :large_orange_diamond:
* [NSObject-Rx ★181](https://github.com/RxSwiftCommunity/NSObject-Rx) - Handy RxSwift extensions on NSObject, including rx_disposeBag. :large_orange_diamond:
* [RxCoreData ★62](https://github.com/RxSwiftCommunity/RxCoreData) - RxSwift extensions for Core Data :large_orange_diamond:
* [Render ★1438](https://github.com/alexdrone/Render) - Swift and UIKit a la React. :large_orange_diamond:
* [RxAutomaton ★547](https://github.com/inamiy/RxAutomaton) - RxSwift + State Machine, inspired by Redux and Elm. :large_orange_diamond:
* [ReactiveArray ★55](https://github.com/Wolox/ReactiveArray) - An array class implemented in Swift that can be observed using ReactiveCocoa's Signals. :large_orange_diamond:
* [Interstellar ★928](https://github.com/JensRavens/Interstellar) - Simple and lightweight Functional Reactive Coding in Swift for the rest of us. :large_orange_diamond:
* [ReduxSwift ★30](https://github.com/lsunsi/ReduxSwift) - Predictable state container for Swift apps too. :large_orange_diamond:
* [Aftermath ★48](https://github.com/hyperoslo/Aftermath) - Stateless message-driven micro-framework in Swift. :large_orange_diamond:
* [RxKeyboard ★430](https://github.com/RxSwiftCommunity/RxKeyboard) - Reactive Keyboard in iOS. :large_orange_diamond:
* [JASONETTE-iOS ★4432](https://github.com/Jasonette/JASONETTE-iOS) - Native App over HTTP. Create your own native iOS app with nothing but JSON.
* [Katana ★1521](https://github.com/BendingSpoons/katana-swift) - Swift apps a la React and Redux. :large_orange_diamond:
* [TemplateKit ★93](https://github.com/mcudich/TemplateKit) - React-inspired framework for building component-based user interfaces in Swift. :large_orange_diamond:
* [ReactiveSwift ★1169](https://github.com/ReactiveCocoa/ReactiveSwift) - Streams of values over time by ReactiveCocoa group
* [Listenable ★2](https://github.com/msaps/Listenable) - Swift object that provides an observable platform. :large_orange_diamond:
* [Reactor ★110](https://github.com/ReactorSwift/Reactor) - :arrows_counterclockwise: Unidirectional Data Flow using idiomatic Swift—inspired by Elm and Redux . :large_orange_diamond:
* [Snail ★42](https://github.com/UrbanCompass/Snail) - An observables framework for Swift :large_orange_diamond:
* [RxWebSocket ★28](https://github.com/fjcaetano/RxWebSocket) - Reactive extension over Starscream for websockets :large_orange_diamond:
* [ACKReactiveExtensions ★5](https://github.com/AckeeCZ/ACKReactiveExtensions) - Useful extensions for ReactiveCocoa :large_orange_diamond:
* [ReactiveLocation ★9](https://github.com/AckeeCZ/ReactiveLocation) - CoreLocation made reactive :large_orange_diamond:

## Reflection
* [Reflection ★280](https://github.com/Zewo/Reflection) - Reflection provides an API for advanced reflection at runtime including dynamic construction of types. :large_orange_diamond:
* [Reflect ★286](https://github.com/CharlinFeng/Reflect) - Reflection, Dict2Model, Model2Dict, Archive :large_orange_diamond:
* [EVReflection ★638](https://github.com/evermeer/EVReflection) - Reflection based JSON encoding and decoding. Including support for NSDictionary, NSCoding, Printable, Hashable and Equatable :large_orange_diamond:
* [JSONNeverDie ★456](https://github.com/johnlui/JSONNeverDie) - Auto reflection tool from JSON to Model, user friendly JSON encoder / decoder, aims to never die :large_orange_diamond:
* [SwiftKVC](https://github.com/bradhilton/SwiftKVC) - Key-Value Coding (KVC) for native Swift classes and structs :large_orange_diamond:

## Regex
* [Regex ★388](https://github.com/sharplet/Regex) - A Swift µframework providing an NSRegularExpression-backed Regex type :large_orange_diamond:
* [SwiftRegex ★116](https://github.com/kasei/SwiftRegex) - Perl-like regex =~ operator for Swift :large_orange_diamond:
* [PySwiftyRegex ★197](https://github.com/cezheng/PySwiftyRegex) - Easily deal with Regex in Swift in a Pythonic way :large_orange_diamond:
* [Regex ★173](https://github.com/crossroadlabs/Regex) - Regular expressions for swift :large_orange_diamond:
* [Regex ★57](https://github.com/brynbellomy/Regex) - Regex class for Swift. Wraps NSRegularExpression. :large_orange_diamond:

## SDK

#### Official

* [Spotify ★722](https://github.com/spotify/ios-sdk) Spotify iOS SDK.
* [Facebook ★5739](https://github.com/facebook/facebook-ios-sdk) Facebook iOS SDK.
* [Facebook Swift ★1071](https://github.com/facebook/facebook-sdk-swift) Integrate your iOS apps in Swift with Facebook Platform.
* [Google Analytics](https://developers.google.com/analytics/devguides/collection/ios/v3/) Google Analytics SDK for iOS
* [Paypal iOS SDK ★810](https://github.com/paypal/PayPal-iOS-SDK) The PayPal Mobile SDKs enable native apps to easily accept PayPal and credit card payments.
* [Pocket ★192](https://github.com/Pocket/Pocket-ObjC-SDK) SDK for saving stuff to Pocket.
* [Tumblr ★357](https://github.com/tumblr/TMTumblrSDK) Library for easily integrating Tumblr data into your iOS or OS X application.
* [Evernote ★202](https://github.com/evernote/evernote-cloud-sdk-ios) Evernote SDK for iOS.
* [Box ★43](https://github.com/box/box-ios-sdk) iOS + OS X SDK for the Box API.
* [OneDrive ★52](https://github.com/OneDrive/onedrive-sdk-ios) Live SDK for iOS.
* [Stripe ★786](https://github.com/stripe/stripe-ios) Stripe bindings for iOS and OS X.
* [Venmo](#payments)
* [AWS ★799](https://github.com/aws/aws-sdk-ios) Amazon Web Services Mobile SDK for iOS.
* [Zendesk ★58](https://github.com/zendesk/zendesk_sdk_ios) Zendesk Mobile SDK for iOS.
* [Adobe Creative SDK](https://creativesdk.adobe.com/) Adobe creative tools and Creative Cloud SDK.
* [Dropbox](https://www.dropbox.com/developers) SDKs for Drop-ins and Dropbox Core API.
* [Fabric by Twitter](https://docs.fabric.io/apple/fabric/overview.html) Fabric Twitter Kit for iOS.
* [Liquid Analytics ★24](https://github.com/lqd-io/liquid-sdk-ios) Identify behaviours through Analytics and react with real-time Personalization.
* [ResearchKit ★4823](https://github.com/ResearchKit/ResearchKit) ResearchKit is an open source software framework that makes it easy to create apps for medical research or for other research projects.
* [PacketZoom](https://packetzoom.com) PacketZoom SDK for iOS.
* [Primer](https://www.goprimer.com) - Easy SDK for creating personalized landing screens, signup, and login flows on a visual editor with built in a/b/n testing and analytics.
* [Azure ★49](https://github.com/Azure/azure-storage-ios) - Client library for accessing Azure Storage on an iOS device
* [1Password ★2283](https://github.com/AgileBits/onepassword-app-extension) - 1Password Extension for iOS Apps
* [CareKit ★1327](https://github.com/carekit-apple/CareKit) - CareKit is an open source software framework for creating apps that help people better understand and manage their health. By Apple :large_orange_diamond:
* [Shopify ★130](https://github.com/Shopify/mobile-buy-sdk-ios) - Shopify’s Mobile Buy SDK makes it simple to sell physical products inside your mobile app.
* [Pinterest ★89](https://github.com/pinterest/ios-pdk) - Pinterest iOS SDK

#### Unofficial

* [STTwitter ★1009](https://github.com/nst/STTwitter) A stable, mature and comprehensive Objective-C library for Twitter REST API 1.1
* [FHSTwitterEngine ★219](https://github.com/natesymer/FHSTwitterEngine) Twitter API for Cocoa developers.
* [Giphy ★46](https://github.com/heyalexchoi/Giphy-iOS) Giphy API client for iOS in Objective-C.
* [UberKit ★95](https://github.com/sachinkesiraju/UberKit) - A simple, easy-to-use Objective-C wrapper for the Uber API.
* [InstagramKit ★864](https://github.com/shyambhat/InstagramKit) - Instagram iOS SDK.
* [DribbbleSDK ★69](https://github.com/agilie/dribbble-ios-sdk) - Dribbble iOS SDK.
* [objectiveflickr ★731](https://github.com/lukhnos/objectiveflickr) - ObjectiveFlickr, a Flickr API framework for Objective-C.
* [Easy Social ★129](https://github.com/pjebs/EasySocial) - Twitter & Facebook Integration.
* [das-quadrat ★158](https://github.com/Constantine-Fry/das-quadrat) - A Swift wrapper for Foursquare API. iOS and OSX. :large_orange_diamond:
* [SocialLib ★10](https://github.com/darkcl/SocialLib) - SocialLib handles sharing message to multiple social media.
* [PokemonKit ★62](https://github.com/ContinuousLearning/PokemonKit) - Pokeapi wrapper, written in Swift :large_orange_diamond:
* [TJDropbox ★45](https://github.com/timonus/TJDropbox) - A Dropbox v2 client library written in Objective-C
* [Lyft ★57](https://github.com/genadyo/Lyft) - Some pink mustache company forgot to build that SDK. :large_orange_diamond:
* [Github.swift ★141](https://github.com/onmyway133/github.swift) - :octocat: Unofficial GitHub API client in Swift :large_orange_diamond:
* [CloudRail SI ★189](https://github.com/CloudRail/cloudrail-si-ios-sdk) - Abstraction layer / unified API for multiple API providers. Interfaces eg for Cloud Storage (Dropbox, Google, ...), Social Networks (Facebook, Twitter, ...) and more.
* [Medium SDK - Swift ★6](https://github.com/96-problems/medium-sdk-swift) - Unofficial Medium API SDK in Swift with sample project :large_orange_diamond:
* [Swifter ★1787](https://github.com/mattdonnelly/Swifter) - :bird: A Twitter framework for iOS & OS X written in Swift :large_orange_diamond:
* [SlackKit ★342](https://github.com/SlackKit/SlackKit) - a Slack client library for iOS and OS X written in Swift :large_orange_diamond:
* [RandomUserSwift ★76](https://github.com/dingwilson/RandomUserSwift) - Swift 3 Framework to Generate Random Users - An Unofficial SDK for randomuser.me :large_orange_diamond:
* [PPEventRegistryAPI ★8](https://github.com/pantuspavel/PPEventRegistryAPI) - Swift 3 Framework for Event Registry API (eventregistry.org). :large_orange_diamond:
* [UnsplashKit ★130](https://github.com/carambalabs/UnsplashKit) - Swift client for Unsplash. :large_orange_diamond:
* [Swiftly Salesforce ★47](https://github.com/mike4aday/SwiftlySalesforce) - An easy-to-use framework for building iOS apps that integrate with Salesforce, using Swift and promises. :large_orange_diamond:
* [Spartan ★7](https://github.com/Daltron/Spartan) - An Elegant Spotify Web API Library Written in Swift for iOS and macOS. :large_orange_diamond:
* [BigBoard ★28](https://github.com/Daltron/BigBoard) - An Elegant Financial Markets Library Written in Swift that makes requests to Yahoo Finance API's under the hood. :large_orange_diamond:

## Security
* [cocoapods-keys ★836](https://github.com/orta/cocoapods-keys) - A key value store for storing environment and application keys.
* [simple-touch](https://github.com/simple-machines/simple-touch) - Very simple swift wrapper for Biometric Authentication Services (Touch ID) on iOS.
* [SwiftPasscodeLock ★490](https://github.com/yankodimitrov/SwiftPasscodeLock) - An iOS passcode lock with TouchID authentication written in Swift. :large_orange_diamond:
* [Smile-Lock ★417](https://github.com/recruit-lifestyle/Smile-Lock) - A library for make a beautiful Passcode Lock View.
* [zxcvbn-ios ★132](https://github.com/dropbox/zxcvbn-ios) - A realistic password strength estimator.
* [TPObfuscatedString ★11](https://github.com/Techprimate/TPObfuscatedString) - Simple String obfuscation using core Swift. :large_orange_diamond:
* [LTHPasscodeViewController](https://github.com/rolandleth/LTHPasscodeViewController) - An iOS passcode lockscreen replica (from Settings), with TouchID and simple (variable length) / complex support.
* [iOS-App-Security-Class ★24](https://github.com/karek314/iOS-App-Security-Class) - Simple class to check if iOS app has been cracked, being debugged or enriched with custom dylib and as well detect jailbroken environment.
* [BiometricAuth](https://github.com/vasilenkoigor/BiometricAuth) - Simple framework for biometric authentication (via TouchID) in your application 🔶

#### Encryption
* [AESCrypt-ObjC ★649](https://github.com/Gurpartap/AESCrypt-ObjC) - A simple and opinionated AES encrypt / decrypt Objective-C class that just works.
* [IDZSwiftCommonCrypto ★306](https://github.com/iosdevzone/IDZSwiftCommonCrypto) - A wrapper for Apple's Common Crypto library written in Swift. :large_orange_diamond:
* [Arcane ★61](https://github.com/onmyway133/Arcane) - 🔱 Lightweight wrapper around CommonCrypto in Swift :large_orange_diamond:
* [SwiftMD5 ★6](https://github.com/mpurland/SwiftMD5) - A pure Swift implementation of MD5 :large_orange_diamond:
* [SwiftHash ★14](https://github.com/onmyway133/SwiftHash) - 🍕 Hash in Swift :large_orange_diamond:
* [SweetHMAC ★28](https://github.com/jancassio/SweetHMAC) - A tiny and easy to use Swift class to encrypt strings using HMAC algorithms. :large_orange_diamond:
* [SwCrypt ★391](https://github.com/soyersoyer/SwCrypt) - RSA public/private key generation, RSA, AES encryption/decryption, RSA sign/verify in Swift with CommonCrypto in iOS and OS X :large_orange_diamond:
* [SwiftSSL ★180](https://github.com/SwiftP2P/SwiftSSL) - An Elegant crypto toolkit in Swift. :large_orange_diamond:
* [SwiftyRSA ★287](https://github.com/TakeScoop/SwiftyRSA) - RSA public/private key encryption in Swift :large_orange_diamond:
* [EnigmaKit ★97](https://github.com/mikaoj/EnigmaKit) - Enigma encryption in Swift :large_orange_diamond:
* [Themis ★358](https://github.com/cossacklabs/themis) - High-level crypto library, providing basic asymmetric encryption, secure messaging with forward secrecy and secure data storage, supports iOS/OS X, Android and different server side platforms.
* [Obfuscator-iOS ★315](https://github.com/pjebs/Obfuscator-iOS) - Secure your app by obfuscating all the hard-coded security-sensitive strings.
* [swift-sodium ★136](https://github.com/jedisct1/swift-sodium) - Safe and easy to use crypto for iOS :large_orange_diamond:
* [CryptoSwift ★3652](https://github.com/krzyzanowskim/CryptoSwift) - Crypto related functions and helpers for Swift implemented in Swift programming language :large_orange_diamond:
* [SCrypto ★13](https://github.com/sgl0v/SCrypto) - Elegant Swift interface to access the CommonCrypto routines :large_orange_diamond:
* [SipHash ★165](https://github.com/lorentey/SipHash) - Simple and secure hashing in Swift with the SipHash algorithm. :large_orange_diamond:

#### Keychain
* [UICKeyChainStore ★2314](https://github.com/kishikawakatsumi/UICKeyChainStore) - UICKeyChainStore is a simple wrapper for Keychain on iOS.
* [Valet ★2387](https://github.com/square/Valet) - Securely store data in the iOS or OS X Keychain without knowing a thing about how the Keychain works.
* [Locksmith ★2172](https://github.com/matthewpalmer/Locksmith) - A powerful, protocol-oriented library for working with the keychain in Swift. :large_orange_diamond:
* [KeychainAccess ★2793](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS and OS X :large_orange_diamond:
* [Keychain ★38](https://github.com/hyperoslo/Keychain) - Because you should care... about the security... of your shit. :large_orange_diamond:
* [Lockbox ★829](https://github.com/granoff/Lockbox) - Objective-C utility class for storing data securely in the key chain.
* [SAMKeychain ★4333](https://github.com/soffes/SAMKeychain) - Simple Objective-C wrapper for the keychain that works on Mac and iOS.
* [SwiftKeychainWrapper ★481](https://github.com/jrendel/SwiftKeychainWrapper) - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults. Written in Swift. :large_orange_diamond:

## Server
* [Perfect ★11305](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect library, application server, connectors and example apps. :large_orange_diamond:
* [Swifter ★1980](https://github.com/httpswift/swifter) - Tiny http server engine written in Swift programming language. :large_orange_diamond:
* [CocoaHTTPServer ★4089](https://github.com/robbiehanson/CocoaHTTPServer) - A small, lightweight, embeddable HTTP server for Mac OS X or iOS applications.
* [Curassow ★385](https://github.com/kylef/Curassow) - Swift HTTP server using the pre-fork worker model. :large_orange_diamond:
* [Zewo ★1636](https://github.com/Zewo/Zewo) - Venice based HTTP server for Swift 2.2 on Linux :large_orange_diamond:
* [Vapor ★9351](https://github.com/vapor/vapor) - Elegant web framework for Swift that works on iOS, OS X, and Ubuntu. :large_orange_diamond:
* [swiftra ★275](https://github.com/takebayashi/swiftra) - Sinatra-like DSL for developing web apps in Swift :large_orange_diamond:
* [blackfire ★948](https://github.com/elliottminns/blackfire) - A fast HTTP web server based on Node.js and Express written in Swift :large_orange_diamond:
* [swift-http ★462](https://github.com/huytd/swift-http) - HTTP Implementation for Swift on Linux and Mac OS X :large_orange_diamond:
* [Trevi ★47](https://github.com/Yoseob/Trevi) - libuv base Swift web HTTP server framework :large_orange_diamond:
* [Express ★852](https://github.com/crossroadlabs/Express) - Swift Express is a simple, yet unopinionated web application server written in Swift :large_orange_diamond:
* [Taylor ★913](https://github.com/izqui/Taylor) - A lightweight library for writing HTTP web servers with Swift :large_orange_diamond:
* [Frank ★337](https://github.com/kylef/Frank) - Frank is a DSL for quickly writing web applications in Swift :large_orange_diamond:
* [Kitura ★5636](https://github.com/IBM-Swift/Kitura) - A Swift Web Framework and HTTP Server :large_orange_diamond:
* [Swifton ★2055](https://github.com/necolt/Swifton) - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and OS X :large_orange_diamond:
* [Dynamo](https://github.com/johnno1962/Dynamo) - High Performance (nearly)100% Swift Web server supporting dynamic content. :large_orange_diamond:
* [Redis ★331](https://github.com/vapor/redis) - Pure-Swift Redis client implemented from the original protocol spec. OS X + Linux compatible. :large_orange_diamond:
* [NetworkObjects ★267](https://github.com/colemancda/NetworkObjects) - Swift backend / server framework (Pure Swift, Supports Linux) :large_orange_diamond:
* [Noze.io](http://noze.io) - Evented I/O streams a.k.a. Node.js for Swift. :large_orange_diamond:
* [Edge ★280](https://github.com/SwiftOnEdge/Edge) - A Swift Multiplatform Web and Networking Framework. :large_orange_diamond:
* [SwiftGD ★143](https://github.com/twostraws/swiftgd) - A simple Swift wrapper for libgd. :large_orange_diamond:
* [Jobs ★98](https://github.com/BrettRToomey/Jobs) - A job system for Swift backends. :large_orange_diamond:
* [mod_swift ★162](https://github.com/AlwaysRightInstitute/mod_swift) - Write Apache Modules in Swift! :large_orange_diamond:

## Text
* [Twitter Text Obj ★1576](https://github.com/twitter/twitter-text) - An Objective-C implementation of Twitter's text processing library.
* [Nimbus ★6262](https://github.com/jverkoey/nimbus) - Nimbus is a toolkit for experienced iOS software designers.
* [NSStringEmojize ★572](https://github.com/diy/nsstringemojize) - A category on NSString to convert Emoji Cheat Sheet codes to their equivalent Unicode characters.
* [MMMarkdown ★1027](https://github.com/mdiep/MMMarkdown) - An Objective-C static library for converting Markdown to HTML.
* [DTCoreText ★4896](https://github.com/Cocoanetics/DTCoreText) - Methods to allow using HTML code with CoreText.
* [DTRichTextEditor ★280](https://github.com/Cocoanetics/DTRichTextEditor) - A rich-text editor for iOS.
* [NBEmojiSearchView ★74](https://github.com/neerajbaid/NBEmojiSearchView) - A searchable emoji dropdown view.
* [Pluralize.swift ★126](https://github.com/joshualat/Pluralize.swift) - Great Swift String Pluralize Extension :large_orange_diamond:
* [RichEditorView ★826](https://github.com/cjwirth/RichEditorView) - RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing. :large_orange_diamond:
* [Money ★727](https://github.com/danthorpe/Money) - Swift value types for working with money & currency :large_orange_diamond:
* [PhoneNumberKit ★1720](https://github.com/marmelroy/PhoneNumberKit) - A Swift framework for parsing, formatting and validating international phone numbers. Inspired by Google's libphonenumber. :large_orange_diamond:
* [YYText ★6197](https://github.com/ibireme/YYText) - Powerful text framework for iOS to display and edit rich text.
* [Format ★1121](https://github.com/marmelroy/Format) - A Swift Formatter Kit. :large_orange_diamond:
* [Tribute ★53](https://github.com/zats/Tribute) - Programmatic creation of NSAttributedString doesn't have to be a pain :large_orange_diamond:
* [EmojiKit ★82](https://github.com/dasmer/EmojiKit) - Effortless emoji-querying in Swift :large_orange_diamond:
* [Roman ★28](https://github.com/nvzqz/Roman) - Seamless Roman numeral conversion in Swift. :large_orange_diamond:
* [ZSSRichTextEditor ★2341](https://github.com/nnhubbard/ZSSRichTextEditor) - A beautiful rich text WYSIWYG editor for iOS with a syntax highlighted source view.
* [pangu.Objective-C ★104](https://github.com/Cee/pangu.objective-c) - Paranoid text spacing in Objective-C.
* [SwiftString ★1366](https://github.com/amayne/SwiftString) - A comprehensive, lightweight string extension for Swift :large_orange_diamond:
* [Marklight ★322](https://github.com/macteo/Marklight) - Markdown syntax highlighter for iOS :large_orange_diamond:
* [MarkdownTextView ★498](https://github.com/indragiek/MarkdownTextView) - Rich Markdown editing control for iOS :large_orange_diamond:
* [TextAttributes ★1862](https://github.com/delba/TextAttributes) - An easier way to compose attributed strings. :large_orange_diamond:[e]
* [Reductio ★329](https://github.com/fdzsergio/Reductio) - Automatic summarizer text in Swift :large_orange_diamond:
* [SmarkDown ★52](https://github.com/SwiftStudies/SmarkDown) - A Pure Swift implementation of the markdown mark-up language :large_orange_diamond:
* [SwiftyMarkdown ★684](https://github.com/SimonFairbairn/SwiftyMarkdown) - Converts Markdown files and strings into NSAttributedString :large_orange_diamond:
* [SZMentions ★6](https://github.com/szweier/SZMentions) - Library to help handle mentions
* [SZMentionsSwift ★21](https://github.com/szweier/SZMentionsSwift) - Library to help handle mentions.
* [Heimdall ★261](https://github.com/henrinormak/Heimdall) - Heimdall is a wrapper around the Security framework for simple encryption/decryption operations. :large_orange_diamond:
* [NoOptionalInterpolation](https://github.com/T-Pham/NoOptionalInterpolation) - Get rid of "Optional(...)" and "nil" in string interpolation. Easy pluralization.🔶[e]
* [Smile ★216](https://github.com/onmyway133/Smile) 😄 Emoji in Swift
* [ISO8601 ★11](https://github.com/onmyway133/iso8601) Super lightweight ISO8601 Date Formatter in Swift 🔶[e]
* [Translucid ★501](https://github.com/Ekhoo/Translucid) - Lightweight library to set an Image as text background. Written in swift. :large_orange_diamond:
* [FormatterKit ★3958](https://github.com/mattt/FormatterKit) - `stringWithFormat:` for the sophisticated hacker set
* [BonMot ★1647](https://github.com/Raizlabs/BonMot) - Beautiful, easy attributed strings in Swift :large_orange_diamond:
* [SwiftValidators ★105](https://github.com/gkaimakas/SwiftValidators) - String validation for iOS developed in Swift. Inspired by [validator.js](https://www.npmjs.com/package/validator).
* [StringStylizer ★29](https://github.com/kazuhiro4949/StringStylizer) - Type strict builder class for NSAttributedString. :large_orange_diamond:
* [SwiftyAttributes ★770](https://github.com/eddiekaiger/SwiftyAttributes) - Swift extensions that make it a breeze to work with attributed strings. :large_orange_diamond:
* [MarkdownKit ★64](https://github.com/ivanbruel/MarkdownKit) - A simple and customizable Markdown Parser for Swift. :large_orange_diamond:
* [CocoaMarkdown ★883](https://github.com/indragiek/CocoaMarkdown) - Markdown parsing and rendering for iOS and OS X. :large_orange_diamond:
* [Apodimark ★428](https://github.com/loiclec/Apodimark) - Fast, flexible markdown parser written in Swift. :large_orange_diamond:
* [Notepad ★244](https://github.com/ruddfawcett/Notepad) - A fully themeable markdown editor with live syntax highlighting. :large_orange_diamond:
* [KKStringValidator ★13](https://github.com/krizhanovskii/KKStringValidator) - Fast and simple string validation for IOS. With UITextField extension. :large_orange_diamond:
* [ISO8859 ★10](https://github.com/Cosmo/ISO8859) - 📄⚙ Convert ISO8859 1-16 Encoded Text to String in Swift. Supports iOS, tvOS, watchOS and macOS. :large_orange_diamond:
* [Emojica](https://github.com/xoudini/emojica) - Replace standard emoji in strings with a custom emoji set, such as [Twemoji](https://github.com/twitter/twemoji) or [EmojiOne ★3321](https://github.com/Ranks/emojione). :large_orange_diamond:
* [SwiftRichString ★918](https://github.com/malcommac/SwiftRichString) - Elegant & Painless Attributed Strings Management Library in Swift. :large_orange_diamond:
* [libPhoneNumber-iOS](https://github.com/iziz/libPhoneNumber-iOS) - iOS port from libphonenumber (Google's phone number handling library).
* [AttributedTextView](https://github.com/evermeer/AttributedTextView) - Easiest way to create an attributed UITextView with support for multiple links (including hashtags and mentions).
* [StyleDecorator ★9](https://github.com/dimpiax/StyleDecorator) - Design string simply by linking attributes to needed parts
* [Mustard ★649](https://github.com/mathewsanders/Mustard) - Mustard is a Swift library for tokenizing strings when splitting by whitespace doesn't cut it. :large_orange_diamond:
* [Input Mask ★43](https://github.com/RedMadRobot/input-mask-ios) - Pattern-based user input formatter, parser and validator for iOS. :large_orange_diamond:
* [Attributed ★465](https://github.com/Nirma/Attributed) - Modern Swift µframework for attributed strings. :large_orange_diamond:
* [Atributika ★94](https://github.com/psharanda/Atributika) - Easily build NSAttributedString by detecting and styling HTML-like tags, hashtags, mentions, RegExp or NSDataDetector patterns. :large_orange_diamond:
* [Guitar ★496](https://github.com/ArtSabintsev/Guitar) - A Cross-Platform String Library Written in Swift. :large_orange_diamond:
* [RealTimeCurrencyFormatter ★10](https://github.com/kaiomedau/realtime-currency-formatter-objc) - An ObjC international currency formatting utility.
* [Down ★335](https://github.com/iwasrobbed/Down) - Blazing fast Markdown rendering in Swift, built upon cmark. 🔶

## Testing

#### TDD / BDD
* [Kiwi ★3560](https://github.com/kiwi-bdd/Kiwi) - A behavior-driven development library for iOS development.
* [Specta ★1960](https://github.com/specta/specta) - A light-weight TDD / BDD framework for Objective-C & Cocoa.
* [Quick ★6349](https://github.com/Quick/Quick) - A behavior-driven development framework for Swift and Objective-C.
* [XcodeCoverage ★669](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects.
* [OHHTTPStubs ★3098](https://github.com/AliSoftware/OHHTTPStubs) - Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!
* [Dixie ★202](https://github.com/Skyscanner/Dixie) - Dixie is an open source Objective-C testing framework for altering object behaviours.
* [gh-unit ★1911](https://github.com/gh-unit/gh-unit) - Test Framework for Objective-C.
* [Nimble ★2063](https://github.com/Quick/Nimble) - A Matcher Framework for Swift and Objective-C :large_orange_diamond:
* [Sleipnir ★839](https://github.com/railsware/Sleipnir) - BDD-style framework for Swift :large_orange_diamond:
* [SwiftCheck ★689](https://github.com/typelift/SwiftCheck) - QuickCheck for Swift :large_orange_diamond:

#### A/B Testing
* [Switchboard ★250](https://github.com/KeepSafe/Switchboard) - Switchboard - easy and super light weight A/B testing for your mobile iPhone or android app. This mobile A/B testing framework allows you with minimal servers to run large amounts of mobile users.
* [SkyLab ★676](https://github.com/mattt/SkyLab) - Multivariate & A/B Testing for iOS and Mac
* [MSActiveConfig ★79](https://github.com/mindsnacks/MSActiveConfig) - Remote configuration and A/B Testing framework for iOS
* [ABKit ★93](https://github.com/recruit-mp/ABKit) - AB testing framework for iOS :large_orange_diamond:

#### UI Testing
* [CrashMonkey ★173](https://github.com/mokemokechicken/CrashMonkey) - Monkey Test Tool For iOS.
* [appium](http://appium.io/) - Appium is an open source test automation framework for use with native and hybrid mobile apps.
* [robotframework-appiumlibrary ★121](https://github.com/serhatbolsu/robotframework-appiumlibrary) - AppiumLibrary is an appium testing library for RobotFramework.
* [Cucumber](https://cucumber.io/) - Behavior driver development for iOS.
* [Kif ★4817](https://github.com/kif-framework/KIF) - An iOS Functional Testing Framework.
* [Subliminal ★787](https://github.com/inkling/Subliminal) - An understated approach to iOS integration testing.
* [ios-driver](http://ios-driver.github.io/ios-driver/index.html) - Test any IOS native, hybrid, or mobile web application using Selenium / WebDriver.
* [Zucchini ★162](https://github.com/zucchini-src/zucchini) - A visual iOS testing framework that loves your apps.
* [Remote ★625](https://github.com/johnno1962/Remote) - Control your iPhone from inside Xcode for end-to-end testing.
* [LayoutTest-iOS ★458](https://github.com/linkedin/LayoutTest-iOS) - Write unit tests which test the layout of a view in multiple configurations.
* [EarlGrey ★3597](https://github.com/google/EarlGrey) - :tea: iOS UI Automation Test Framework.
* [UI Testing Cheat Sheet ★981](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet) - How do I test this with UI Testing? :large_orange_diamond:
* [Floater_ ★231](https://github.com/Buglife/Floater_) - Add a floating fingertip to your app demo :large_orange_diamond:
* [Bluepill ★2226](https://github.com/linkedin/bluepill) - Bluepill is a reliable iOS testing tool that runs UI tests using multiple simulators on a single machine

#### Other Testing
* [NaughtyKeyboard ★568](https://github.com/Palleas/NaughtyKeyboard) - The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data. This is a keyboard to help you test your app from your iOS device.
* [PonyDebugger ★5351](https://github.com/square/PonyDebugger) - Remote network and data debugging for your native iOS app using Chrome Developer Tools
* [ios-snapshot-test-case ★2394](https://github.com/facebook/ios-snapshot-test-case) - Snapshot view unit tests for iOS.
* [Fakery ★649](https://github.com/vadymmarkov/Fakery) - Swift fake data generator. :large_orange_diamond:
* [DVR ★490](https://github.com/venmo/DVR) - Network testing for Swift :large_orange_diamond:
* [Cuckoo ★498](https://github.com/Brightify/Cuckoo) - First boilerplate-free mocking framework for Swift :large_orange_diamond:
* [Parallel iOS Tests ★0](https://github.com/plu/parallel_ios_tests) - Run iOS tests on multiple simulators in parallel at the same time :large_orange_diamond:
* [Vinyl ★198](https://github.com/Velhotes/Vinyl) - Network testing à la VCR in Swift :large_orange_diamond:
* [Mockit ★46](https://github.com/sabirvirtuoso/Mockit) - A simple mocking framework for Swift, inspired by the famous Mockito for Java :large_orange_diamond:
* [Cribble ★268](https://github.com/maxsokolov/Cribble) - Swifty tool for visual testing iPhone and iPad apps :large_orange_diamond:
* [second_curtain ★108](https://github.com/ashfurrow/second_curtain) - Upload failing iOS snapshot tests cases to S3
* [trainer ★81](https://github.com/KrauseFx/trainer) - Convert xcodebuild plist files to JUnit reports
* [Buildasaur ★693](https://github.com/buildasaurs/Buildasaur) - Automatic testing of your Pull Requests on GitHub and BitBucket using Xcode Server. Keep your team productive and safe. Get up and running in minutes. @buildasaur :large_orange_diamond:
* [Kakapo ★699](https://github.com/devlucky/Kakapo) - 🐤Dynamically Mock server behaviors and responses in Swift :large_orange_diamond:
* [AcceptanceMark ★43](https://github.com/bizz84/AcceptanceMark) Tool to auto-generate Xcode tests classes from Markdown tables
* [MetovaTestKit ★18](https://github.com/metova/MetovaTestKit) - A collection of testing utilities to turn crashing test suites into failing test suites. :large_orange_diamond:
* [MirrorDiffKit ★58](https://github.com/Kuniwak/MirrorDiffKit) - Pretty diff between any structs or classes :large_orange_diamond:

#### Font
* [FontBlaster ★812](https://github.com/ArtSabintsev/FontBlaster) - Programmatically load custom fonts into your iOS app. :large_orange_diamond:
* [GoogleMaterialIconFont ★131](https://github.com/kitasuke/GoogleMaterialIconFont) - Google Material Design Icons for Swift and ObjC project :large_orange_diamond:
* [ios-fontawesome ★1711](https://github.com/alexdrone/ios-fontawesome) - NSString+FontAwesome.
* [FontAwesome.swift ★787](https://github.com/thii/FontAwesome.swift) - Use FontAwesome in your Swift projects. :large_orange_diamond:
* [SwiftFontName ★88](https://github.com/morizotter/SwiftFontName) - OS font complements library. Localized font supported :large_orange_diamond:
* [SwiftIconFont](https://github.com/0x73/SwiftIconFont) - Icons fonts for iOS (FontAwesome, Iconic, Ionicon, Octicon, Themify, MapIcon, MaterialIcon) :large_orange_diamond:
* [FontAwesomeKit ★2398](https://github.com/PrideChung/FontAwesomeKit) - Icon font library for iOS. Currently supports Font-Awesome, Foundation icons, Zocial, and ionicons.
* [Iconic ★1306](https://github.com/dzenbot/Iconic) - Auto-generated icon font library for iOS, watchOS and tvOS  :large_orange_diamond:
* [GoogleMaterialDesignIcons ★359](https://github.com/dekatotoro/GoogleMaterialDesignIcons) - Google Material Design Icons Font for iOS. :large_orange_diamond:
* [OcticonsKit ★32](https://github.com/keitaoouchi/OcticonsKit) - Use Octicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [IoniconsKit ★278](https://github.com/keitaoouchi/IoniconsKit) - Use Ionicons as UIImage / UIFont in your projects with Swifty manners. :large_orange_diamond:
* [FontAwesomeKit.Swift ★142](https://github.com/qiuncheng/FontAwesomeKit.Swift) - A better choice for iOS Developer to use FontAwesome Icon. :large_orange_diamond:
* [UIFontComplete ★440](https://github.com/Nirma/UIFontComplete) - Make working with UIFont faster and less error-prone. :large_orange_diamond:
* [Swicon](https://github.com/UglyTroLL/Swicon) - Use 1600+ icons (and more!) from FontAwesome and Google Material Icons in your swift/iOS project in an easy and space-efficient way! :large_orange_diamond:
* [SwiftIcons ★211](https://github.com/ranesr/SwiftIcons) - A library for using different font icons: dripicons, emoji, font awesome, icofont, ionicons, linear icons, map icons, material icons, open iconic, state, weather. It supports UIImage, UIImageView, UILabel, UIButton, UISegmentedControl, UITabBarItem, UISlider, UIBarButtonItem, UIViewController, UITextfield, UIStepper. :large_orange_diamond:

## UI
* [FlatUIKit ★7513](https://github.com/Grouper/FlatUIKit) - A collection of awesome flat UI components for iOS.
* [BetweenKit ★258](https://github.com/ice3-software/between-kit) - A robust drag-and-drop framework for iOS.
* [MDCSwipeToChoose ★2375](https://github.com/modocache/MDCSwipeToChoose) - Swipe to "like" or "dislike" any view, just like Tinder.app. Build a flashcard app, a photo viewer, and more, in minutes, not hours!
* [BLKFlexibleHeightBar ★2823](https://github.com/bryankeller/BLKFlexibleHeightBar) - Create condensing header bars like those seen in the Facebook, Square Cash, and Safari iOS apps.
* [Motif ★762](https://github.com/erichoracek/Motif) - A lightweight and customizable JSON stylesheet framework for iOS.
* [AsyncDisplayKit ★11384](https://github.com/facebook/AsyncDisplayKit) - AsyncDisplayKit is an iOS framework that keeps even the most complex user interfaces smooth and responsive.
* [GaugeKit ★868](https://github.com/skywinder/GaugeKit) - Customizable gauges. Easy reproduce Apple's style gauges. :large_orange_diamond:
* [MVMaterialView ★65](https://github.com/TheMrugraj/MVMaterialView) - Subclass of UIControls and UIButton to mimic Ripple effect of Material Design concept.
* [TisprCardStack ★597](https://github.com/tispr/tispr-card-stack) - Library that allows to have cards UI. :large_orange_diamond:
* [SAHistoryNavigationViewController ★1424](https://github.com/marty-suzuki/SAHistoryNavigationViewController) - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationContoller,3D Touch Compatible. :large_orange_diamond:
* [SAInboxViewController ★265](https://github.com/marty-suzuki/SAInboxViewController) - UIViewController subclass inspired by "Inbox by google" animated transitioning. :large_orange_diamond:
* [iCarousel ★9234](https://github.com/nicklockwood/iCarousel) - A simple, highly customisable, data-driven 3D carousel for iOS and Mac OS.
* [Cocoa Controls](https://www.cocoacontrols.com/) - Open source UI components for iOS and OS X.
* [HoneycombView ★184](https://github.com/suzuki-0000/HoneycombView) - HoneycombView is the iOS UIView for displaying like Honyecomb layout written by swift. :large_orange_diamond:
* [tapkulibrary ★4012](https://github.com/devinross/tapkulibrary) - tap + haiku = tapku, a well crafted open source iOS framework.
* [KCHorizontalDial ★86](https://github.com/kciter/HorizontalDial) - A horizontal scroll dial like Instagram. :large_orange_diamond:
* [ComponentKit](http://componentkit.org/) - A React-Inspired View Framework for iOS, by Facebook.
* [PMTween ★336](https://github.com/poetmountain/PMTween) - An elegant and flexible tweening library for iOS.
* [WobbleView ★2140](https://github.com/inFullMobile/WobbleView) - WobbleView is an implementation of a recently popular wobble effect for any view in your app. It can be used to easily add dynamics to user interactions and transitions. :large_orange_diamond:
* [RKNotificationHub ★2597](https://github.com/cwRichardKim/RKNotificationHub) - Make any UIView a full fledged notification center.
* [EatFit ★555](https://github.com/Yalantis/EatFit) - Eat fit is a component for attractive data representation inspired by Google Fit :large_orange_diamond:
* [phone-number-picker ★101](https://github.com/hughbe/phone-number-picker) - A simple and easy to use view controller enabling you to enter a phone number with a country code similar to WhatsApp written in Swift :large_orange_diamond:
* [DLWBouncyView ★49](https://github.com/cute/DLWBouncyView) - BouncyView is an implementation of a recently popular bouncy effect for any view.
* [EXTView ★144](https://github.com/recruit-mtl/EXTView) - Extended UIView for Interface Builder by using IB_DESIGNABLE and IBInspectable.
* [SFFocusViewLayout ★1498](https://github.com/fdzsergio/SFFocusViewLayout) - UICollectionViewLayout with focused content.
* [CardAnimation ★917](https://github.com/seedante/CardAnimation) - Card flip animation by pan gesture. :large_orange_diamond:
* [BEMCheckBox ★1635](https://github.com/Boris-Em/BEMCheckBox#sample-app) - Tasteful Checkbox for iOS. (Check box)
* [HorizontalProgress ★146](https://github.com/AliThink/HorizontalProgress) - Simple horizontal progress bar with animation
* [JRSplitVC ★24](https://github.com/tommypeps/JRSplitVC) - UISplitViewController with adaptative layouts
* [MPParallaxView ★1447](https://github.com/DroidsOnRoids/MPParallaxView) - Apple TV Parallax effect in Swift. :large_orange_diamond:
* [Splitflap ★714](https://github.com/yannickl/Splitflap) - A simple split-flap display for your Swift applications :large_orange_diamond:
* [EZSwipeController ★647](https://github.com/goktugyil/EZSwipeController) - :point_up_2: UIPageViewController like Snapchat/Tinder/iOS Main Pages :large_orange_diamond:
* [SWRevealViewController ★4078](https://github.com/John-Lluch/SWRevealViewController) - A UIViewController subclass for presenting side view controllers inspired on the FaceBook and Wunderlist apps, done right.
* [Koloda ★3057](https://github.com/Yalantis/Koloda) - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. :large_orange_diamond:
* [XLActionController ★1858](https://github.com/xmartlabs/XLActionController) - Fully customizable and extensible action sheet controller written in Swift. :large_orange_diamond:
* [StackPageView ★30](https://github.com/noppefoxwolf/StackPageView) - Vertical page view with UIViewControllers stacked on the top of each other :large_orange_diamond:
* [PageControl ★85](https://github.com/kasper-lahti/PageControl) - ● ○ ○ ○ A nice, animated UIPageControl alternative. :large_orange_diamond:
* [Curry ★27](https://github.com/devinross/curry) - Curry is a framework built to enhance and compliment Foundation and UIKit.
* [Pages ★329](https://github.com/hyperoslo/Pages) - :page_facing_up: UIPageViewController made simple :large_orange_diamond:
* [BothamUI ★329](https://github.com/Karumi/BothamUI) - Model View Presenter Framework written in Swift. :large_orange_diamond:
* [RainbowNavigation ★575](https://github.com/DanisFabric/RainbowNavigation) - An easy way to change backgroundColor of UINavigationBar when Push & Pop :large_orange_diamond:
* [ALTextInputBar ★148](https://github.com/AlexLittlejohn/ALTextInputBar) - An auto growing text input bar for messaging apps. :large_orange_diamond:
* [APCustomBlurView ★127](https://github.com/collinhundley/APCustomBlurView) - A subclass of UIVisualEffectView with customizable blur radius. :large_orange_diamond:
* [BAFluidView ★1227](https://github.com/antiguab/BAFluidView) - UIView that simulates a 2D view of a fluid in motion
* [WZDraggableSwitchHeaderView ★484](https://github.com/wongzigii/WZDraggableSwitchHeaderView) - :hammer: Showing status for switching between viewControllers
* [MICountryPicker ★57](https://github.com/mustafaibrahim989/MICountryPicker) - Swift country picker with search option. :large_orange_diamond:
* [SCNavigationControlCenter ★391](https://github.com/SergioChan/SCNavigationControlCenter) - This is an advanced navigation control center on iOS that can allow you to navigate to whichever view controller you want
* [SCTrelloNavigation ★760](https://github.com/SergioChan/SCTrelloNavigation) - :clipboard: An iOS native implementation of a Trello Animated Navagation.
* [FXBlurView ★4870](https://github.com/nicklockwood/FXBlurView) - UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above.
* [NGAParallaxMotion ★677](https://github.com/michaeljbishop/NGAParallaxMotion) - A tiny category on UIView that allows you to set one property: "parallaxIntensity" to achieve a parallax effect with UIMotionEffect
* [EPShapes ★352](https://github.com/ipraba/EPShapes) - Design shapes in Interface Builder. :large_orange_diamond:
* [CRParticleEffect ★349](https://github.com/Cleveroad/CRParticleEffect) - A CocoaPod that simplifies creation of the particle effects.
* [Spots ★1053](https://github.com/hyperoslo/Spots) - Spots is a view controller framework that makes your setup and future development blazingly fast. :large_orange_diamond:
* [APAddressBook ★1336](https://github.com/Alterplay/APAddressBook) - Easy access to iOS address book
* [AZExpandableIconListView ★161](https://github.com/Azuritul/AZExpandableIconListView) - An expandable/collapsible view component written in Swift. :large_orange_diamond:
* [greedo-layout-for-ios ★773](https://github.com/500px/greedo-layout-for-ios) - Full aspect ratio grid layout for iOS
* [FlourishUI ★192](https://github.com/thinkclay/FlourishUI) - A highly configurable and out-of-the-box-pretty UI library :large_orange_diamond:
* [GranadaLayout ★38](https://github.com/gskbyte/GranadaLayout) - Alternative layout system for iOS, inspired on the Android layout system, that includes linear and relative layouts, as well as an extensible JSON-based layout inflater.
* [Navigation Stack ★1776](https://github.com/Ramotion/navigation-stack) - Navigation Stack is a stack-modeled navigation controller. :large_orange_diamond:
* [UIView-draggable ★358](https://github.com/andreamazz/UIView-draggable) - UIView category that adds dragging capabilities.
* [PeekPop ★1800](https://github.com/marmelroy/PeekPop) - Backwards-compatible Peek and Pop.
* [MKGradientView](https://github.com/maxkonovalov/MKGradientView) - Core Graphics based gradient view capable of producing Linear (Axial), Radial (Circular), Conical (Angular), Bilinear (Four Point) gradients, written in Swift. 🔶
* [EPSignature ★596](https://github.com/ipraba/EPSignature) - Signature component for iOS in Swift :large_orange_diamond:
* [CoreDragon ★687](https://github.com/nevyn/CoreDragon)  - [iOS] Stop using context menus. Drag and drop instead, even between apps!
* [AEConicalGradient](https://github.com/tadija/AEConicalGradient) - Conical (angular) gradient layer written in Swift. :large_orange_diamond:
* [EVFaceTracker ★209](https://github.com/evermeer/EVFaceTracker) - Calculate the distance and angle of your device with regards to your face.
* [Fashion ★65](https://github.com/vadymmarkov/Fashion) - Fashion accessories and beauty tools to share and reuse UI styles in a Swifty way. :large_orange_diamond:
* [LeeGo ★875](https://github.com/wangshengjia/LeeGo) - Declarative, configurable & highly reusable UI development as making Lego bricks. :large_orange_diamond:
* [MEVHorizontalContacts ★275](https://github.com/manuelescrig/MEVHorizontalContacts) - An iOS UICollectionViewLayout subclass to show a list of contacts with configurable expandable menu items.
* [Ripple ★35](https://github.com/RamonGilabert/Ripple) - Remember there's no such thing as a small act of kindness. Every act creates a ripple with no logical end. :large_orange_diamond:
* [ScalePicker ★128](https://github.com/kronik/ScalePicker) - Generic scale and a handy float-value picker for any iOS app.
* [VisualEffectView ★384](https://github.com/efremidze/VisualEffectView) - UIVisualEffectView subclass with tint color. :large_orange_diamond:
* [NumPad](https://github.com/efremidze/NumPad) - Number Pad (inspired by Square's design). :large_orange_diamond:
* [expanding-collection ★3387](https://github.com/Ramotion/expanding-collection) - ExpandingCollection is a card peek/pop controller :large_orange_diamond:
* [Cacao](https://github.com/PureSwift/Cacao) - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux) :large_orange_diamond:
* [LFTimePicker ★23](https://github.com/awesome-labs/LFTimePicker) - Custom Time Picker ViewController with Selection of start and end times in Swift :large_orange_diamond:
* [StateView ★477](https://github.com/sahandnayebaziz/StateView) - Views that automatically update themselves. :large_orange_diamond:
* [JDFlipNumberView ★701](https://github.com/calimarkus/JDFlipNumberView) - Representing analog flip numbers like airport/trainstation displays.
* [JQSwiftIcon ★5](https://github.com/josejuanqm/JQSwiftIcon) - Icon Fonts on iOS using string interpolation written in Swift. :large_orange_diamond:
* [FlickToDismiss ★196](https://github.com/jakelawson1/FlickToDismiss) - A basic UIViewController class that presents a UIView which can be dismissed by flicking it off the screen. :large_orange_diamond:
* [ISTimeline ★845](https://github.com/instant-solutions/ISTimeline) - Simple timeline view written in Swift 2.2 :large_orange_diamond:
* [JFCardSelectionViewController ★361](https://github.com/atljeremy/JFCardSelectionViewController) - A fancy collection style view controller :large_orange_diamond:
* [DCKit ★72](https://github.com/agordeev/DCKit) - Set of iOS controls, which have useful IBInspectable properties. Written on Swift. :large_orange_diamond:
* [BackgroundVideoiOS ★467](https://github.com/Guzlan/BackgroundVideoiOS) - A swift and objective-C object that lets you add a background video to iOS views.
* [NightNight ★538](https://github.com/Draveness/NightNight) - Elegant way to integrate night mode to swift projects :large_orange_diamond:
* [SwiftTheme ★750](https://github.com/jiecao-fm/SwiftTheme) - Powerful theme/skin manager for iOS 7+ :large_orange_diamond:
* [PinpointKit ★894](https://github.com/Lickability/PinpointKit) - Let your testers and users send feedback with annotated screenshots and logs using a simple gesture. :large_orange_diamond:
* [FDStackView ★2219](https://github.com/forkingdog/FDStackView) - Use UIStackView directly in iOS6+
* [Popover ★1114](https://github.com/corin8823/Popover) - Popover is a balloon library like Facebook app. It is written in pure swift. :large_orange_diamond:
* [YangMingShan ★574](https://github.com/yahoo/YangMingShan) - YangMingShan is a collection of iOS UI components that we created while building Yahoo apps.
* [TOActionSheet ★148](https://github.com/TimOliver/TOActionSheet) - A custom-designed reimplementation of the UIActionSheet control for iOS
* [LFLoginController ★62](https://github.com/awesome-labs/LFLoginController) - Customizable login screen, written in Swift :large_orange_diamond:
* [nui ★3696](https://github.com/tombenner/nui) - Style iOS apps with a stylesheet, similar to CSS
* [RedBeard](http://www.redbeard.io/) - It's a complete framework that takes away much of the pain of getting a beautiful, powerful iOS App crafted.
* [Material ★7726](https://github.com/CosmicMind/Material) - Material is an animation and graphics framework that allows developers to easily create beautiful applications. :large_orange_diamond:
* [Blurable ★782](https://github.com/FlexMonkey/Blurable) - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions :large_orange_diamond:
* [EZYGradientView ★268](https://github.com/shashankpali/EZYGradientView) - Create gradients and blur gradients without a single line of code :large_orange_diamond:
* [DistancePicker ★79](https://github.com/qmathe/DistancePicker) - Custom control to select a distance with a pan gesture, written in Swift. :large_orange_diamond:
* [OAStackView ★2112](https://github.com/oarrabi/OAStackView) - OAStackView tries to port back the stackview to iOS 7+. OAStackView aims at replicating all the features in UIStackView.
* [StyleKit ★1095](https://github.com/146BC/StyleKit) - StyleKit is a microframework that enables you to style your applications using a simple JSON file. Behind the scenes, StyleKit uses UIAppearance and some selector magic to apply the styles. You can also customize the parser for greater flexibility. :large_orange_diamond:
* [planet ★41](https://github.com/kwallet/planet) - A country picker :large_orange_diamond:
* [PageController ★193](https://github.com/hirohisa/PageController) - Infinite paging controller, scrolling through contents and title bar scrolls with a delay. :large_orange_diamond:
* [StatusProvider ★752](https://github.com/mariohahn/StatusProvider) - Protocol to handle initial Loadings, Empty Views and Error Handling in a ViewController & views :large_orange_diamond:
* [ASBubbleDrag](https://github.com/scamps88/ASBubbleDrag) - round icon drag control (made in swift) dock style :large_orange_diamond:
* [StackLayout ★70](https://github.com/bridger/StackLayout) - An alternative to UIStackView for common Auto Layout patterns.
* [NightView ★156](https://github.com/Boris-Em/NightView) - Dazzling Nights on iOS. :large_orange_diamond:
* [VENTokenField ★720](https://github.com/venmo/VENTokenField) - Easy-to-use token field that is used in the Venmo app.
* [SwiftVideoBackground ★53](https://github.com/dingwilson/SwiftVideoBackground) - Easy to Use UIView subclass for implementating a video background in Swift 3 :large_orange_diamond:
* [MRArticleViewController ★93](https://github.com/mrigdon/MRArticleViewController) - Easily create UIViewControllers for news articles similar to those in the News app. :large_orange_diamond:
* [iCheckbox ★25](https://github.com/mancunianetz/iCheckbox) - A checkbox like component for iOS apps. :large_orange_diamond:
* [Macaw ★2314](https://github.com/exyte/macaw) - Powerful and easy-to-use vector graphics library with SVG support written in Swift. :large_orange_diamond:
* [HubFramework ★1626](https://github.com/spotify/HubFramework) - Spotify’s component-driven UI framework for iOS.
* [ConfettiView ★203](https://github.com/OrRon/ConfettiView) - Confetti View lets you create a magnificent confetti view in your app :large_orange_diamond:
* [BouncyPageViewController ★552](https://github.com/BohdanOrlov/BouncyPageViewController) - Page view controller with bounce effect :large_orange_diamond:
* [LTHRadioButton ★179](https://github.com/rolandleth/LTHRadioButton) - A radio button with a pretty fill animation. :large_orange_diamond:
* [CRRulerControl ★87](https://github.com/Cleveroad/CRRulerControl) - Customizable component is aimed at turning a simple ruler into a handy and smart instrument.
* [Macaw-Examples ★80](https://github.com/exyte/Macaw-Examples) - Various usages of the Macaw library. :large_orange_diamond:
* [KVCardSelectionVC ★11](https://github.com/kunalverma25/KVCardSelectionVC) - Awesome looking Dial like card selection ViewController. :large_orange_diamond:
* [Reactions ★381](https://github.com/yannickl/Reactions) - Fully customizable Facebook reactions control :large_orange_diamond:
* [Newly ★157](https://github.com/dhirajjadhao/Newly) - Newly is a drop in solution to add Twitter/Facebook/Linkedin-style new updates/tweets/posts available button :large_orange_diamond:
* [CardStackController ★262](https://github.com/jobandtalent/CardStackController) - iOS custom controller used in Jobandtalent app to present new view controllers as cards :large_orange_diamond:
* [Material Components ★947](https://github.com/material-components/material-components-ios) - Google developed UI components that help developers execute Material Design.
* [DMSwipeCards ★184](https://github.com/D-32/DMSwipeCards) - Tinder like card stack that supports lazy loading and generics :large_orange_diamond:
* [RKMultiUnitRuler ★14](https://github.com/farshidce/RKMultiUnitRuler) - Simple customizable ruler control that supports multiple units. 🔶
* [FAQView ★324](https://github.com/mukeshthawani/FAQView) - An easy to use FAQ view for iOS written in Swift. :large_orange_diamond:
* [CRPageViewController ★327](https://github.com/Cleveroad/CRPageViewController) - While a standard page view allows you to navigate between pages by using simple gestures, our component goes further.
* [OXPatternLock ★13](https://github.com/oxozle/OXPatternLock) - An iOS pattern lock like Android authentication written in Swift. :large_orange_diamond:
* [LMArticleViewController ★3](https://github.com/lucamozza/LMArticleViewController) - UIViewController subclass to beautifully present news articles and blog posts
* [FSPagerView ★1466](https://github.com/WenchaoD/FSPagerView) - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner、Product Show、Welcome/Guide Pages、Screen/ViewController Sliders. :large_orange_diamond:
* [PanelKit ★2658](https://github.com/louisdh/panelkit) - A UI framework that enables panels on iOS. :large_orange_diamond:
* [ElongationPreview ★437](https://github.com/Ramotion/elongation-preview) - ElongationPreview is an elegant push-pop style view controller with 3D-Touch support and gestures. :large_orange_diamond:
* [Pageboy ★702](https://github.com/uias/Pageboy) - A simple, highly informative page view controller. :large_orange_diamond:
* [IGColorPicker ★45](https://github.com/iGenius-Srl/IGColorPicker) - 🎨 A customizable color picker for iOS in Swift 🔶
* [KPActionSheet ★4](https://github.com/khuong291/KPActionSheet) - 🔶 A replacement of default action sheet, but has very simple usage. 🔶
* [SegmentedProgressBar ★102](https://github.com/D-32/SegmentedProgressBar) - Snapchat / Instagram Stories style animated indicator :large_orange_diamond:
* [CHIPageControl ★1284](https://github.com/ChiliLabs/CHIPageControl) - A set of cool animated page controls to replace boring UIPageControl. :large_orange_diamond:
* [Magnetic](https://github.com/efremidze/Magnetic) - SpriteKit Floating Bubble Picker (inspired by Apple Music). 🔶
* [AmazingBubbles ★32](https://github.com/GlebRadchenko/AmazingBubbles) - Apple Music like Bubble Picker using Dynamic Animation. 🔶
* [LoginKit ★304](https://github.com/IcaliaLabs/LoginKit) - LoginKit is a quick and easy way to add a Login/Signup UX to your iOS app.  🔶
* [Haptica ★143](https://github.com/efremidze/Haptica) - Easy Haptic Feedback Generator. :large_orange_diamond:

#### Activity Indicator

* [NVActivityIndicatorView ★4919](https://github.com/ninjaprox/NVActivityIndicatorView) - Collection of nice loading animations. :large_orange_diamond:
* [TKRubberIndicator ★955](https://github.com/TBXark/TKRubberIndicator) - Rubber Indicator in Swift :large_orange_diamond:
* [RPLoadingAnimation ★162](https://github.com/naoyashiga/RPLoadingAnimation) - Loading animations :cyclone: by using Swift CALayer :large_orange_diamond:
* [LiquidLoader ★894](https://github.com/yoavlt/LiquidLoader) - Spinner loader components with liquid animation :large_orange_diamond:
* [iOS-CircleProgressView ★356](https://github.com/CardinalNow/iOS-CircleProgressView) - This control will allow a user to use code instantiated or interface builder to create and render a circle progress view. :large_orange_diamond:
* [iOS Circle Progress Bar ★304](https://github.com/Eclair/CircleProgressBar) - iOS Circle Progress Bar
* [LinearProgressBar](https://github.com/PhilippeBoisney/LinearProgressBar) - Linear Progress Bar (inspired by Google Material Design) for iOS written in Swift 2.0. :large_orange_diamond:
* [STLoadingGroup ★263](https://github.com/saitjr/STLoadingGroup) - loading views :large_orange_diamond:
* [ALThreeCircleSpinner ★30](https://github.com/AlexLittlejohn/ALThreeCircleSpinner) - A pulsing spinner view written in swift :large_orange_diamond:
* [MHRadialProgressView ★74](https://github.com/mehfuzh/MHRadialProgressView) - iOS 7 radial animated progress view.
* [Loader ★79](https://github.com/Ekhoo/Loader) - Amazing animated switch activity indicator written in swift :large_orange_diamond:
* [MBProgressHUD ★13149](https://github.com/jdg/MBProgressHUD) - Drop-in class for displays a translucent HUD with an indicator and/or labels while work is being done in a background thread.
* [SVProgressHUD ★9631](https://github.com/SVProgressHUD/SVProgressHUD) - A clean and lightweight progress HUD for your iOS app.
* [ProgressHUD ★887](https://github.com/relatedcode/ProgressHUD) - ProgressHUD is a lightweight and easy-to-use HUD.
* [M13ProgressSuite ★3405](https://github.com/Marxon13/M13ProgressSuite) - A suite containing many tools to display progress information on iOS.
* [JHProgressHUD ★76](https://github.com/harikrishnant1991/JHProgressHUD) - An easy and lightweight Swift library to show HUD in IOS applications. :large_orange_diamond:
* [PKHUD](https://github.com/pkluz/PKHUD) - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8 and above. :large_orange_diamond:
* [EZLoadingActivity ★484](https://github.com/goktugyil/EZLoadingActivity) - Lightweight loading activity HUD.  :large_orange_diamond:
* [FFCircularProgressView ★992](https://github.com/elbryan/FFCircularProgressView) - FFCircularProgressView - An iOS 7-inspired blue circular progress view
* [MRProgress ★2532](https://github.com/mrackwitz/MRProgress) - Collection of iOS drop-in components to visualize progress
* [BigBrother ★445](https://github.com/marcelofabri/BigBrother) - Automatically sets the network activity indicator for any performed request. :large_orange_diamond:
* [AlamofireNetworkActivityIndicator ★354](https://github.com/Alamofire/AlamofireNetworkActivityIndicator) - Controls the visibility of the network activity indicator on iOS using Alamofire. :large_orange_diamond:
* [KDCircularProgress ★562](https://github.com/kaandedeoglu/KDCircularProgress) - A circular progress view with gradients written in Swift :large_orange_diamond:
* [DACircularProgress ★2106](https://github.com/danielamitay/DACircularProgress) - DACircularProgress is a UIView subclass with circular UIProgressView properties.
* [KYNavigationProgress ★175](https://github.com/ykyouhei/KYNavigationProgress) - Simple extension of UINavigationController to display progress on the UINavigationBar. :large_orange_diamond:[e]
* [GearRefreshControl ★513](https://github.com/andreamazz/GearRefreshControl) - A custom animation for the UIRefreshControl :large_orange_diamond:
* [NJKWebViewProgress ★3541](https://github.com/ninjinkun/NJKWebViewProgress) - A progress interface library for UIWebView. You can implement progress bar for your in-app browser using this module.
* [MKRingProgressView ★542](https://github.com/maxkonovalov/MKRingProgressView) - A beautiful ring/circular progress view similar to Activity app on Apple Watch, written in Swift. 🔶
* [Hexacon ★233](https://github.com/gautier-gdx/Hexacon) - A new way to display content in your app like the Apple Watch SpringBoard, written in Swift. 🔶
* [StackViewController ★585](https://github.com/seedco/StackViewController) - A controller that uses a UIStackView and view controller composition to display content in a list :large_orange_diamond:
* [ParticlesLoadingView ★729](https://github.com/BalestraPatrick/ParticlesLoadingView) - A customizable SpriteKit particles animation on the border of a view. :large_orange_diamond:
* [RPCircularProgress](https://github.com/iwasrobbed/RPCircularProgress) - (Swift) Circular progress UIView subclass with UIProgressView properties :large_orange_diamond:
* [MBCircularProgressBar ★593](https://github.com/MatiBot/MBCircularProgressBar) -  A circular, animatable & highly customizable progress bar, editable from the Interface Builder using IBDesignable.
* [WSProgressHUD ★500](https://github.com/devSC/WSProgressHUD) - This is a beauful hud view for iPhone & iPad
* [DBMetaballLoading ★45](https://github.com/dabing1022/DBMetaballLoading) - A metaball loading written in Swift. :large_orange_diamond:
* [FillableLoaders ★1618](https://github.com/poolqf/FillableLoaders) - Completely customizable progress based loaders drawn using custom CGPaths written in Swift :large_orange_diamond:
* [PageControls ★574](https://github.com/popwarsweet/PageControls) - This is a selection of custom page controls to replace UIPageControl, inspired by a dribbble found here :large_orange_diamond:
* [VHUD ★115](https://github.com/xxxAIRINxxx/VHUD) Simple HUD. :large_orange_diamond:
* [SwiftSpinner ★1495](https://github.com/icanzilb/SwiftSpinner) - A beautiful activity indicator and modal alert written in Swift using blur effects, translucency, flat and bold design :large_orange_diamond:
* [SnapTimer ★237](https://github.com/andresinaka/SnapTimer) - Implementation of Snapchat's stories timer. :large_orange_diamond:
* [AudioIndicatorBars ★145](https://github.com/LeonardoCardoso/AudioIndicatorBars) - AIB indicates for your app users which audio is playing. Just like the Podcasts app. :large_orange_diamond:
* [LLSpinner ★10](https://github.com/alaphao/LLSpinner) - An easy way to create a full screen activity indicator. :large_orange_diamond:
* [SVUploader ★13](https://github.com/kirankunigiri/SVUploader) - A beautiful uploader progress view that makes things simple and easy.  :large_orange_diamond:
* [YLProgressBar ★885](https://github.com/yannickl/YLProgressBar) - UIProgressView replacement with an highly and fully customizable animated progress bar in pure Core Graphics.
* [FlexibleSteppedProgressBar ★63](https://github.com/amratab/FlexibleSteppedProgressBar) - A beautiful easily customisable stepped progress bar.  :large_orange_diamond:
* [GradientLoadingBar ★26](https://github.com/fxm90/GradientLoadingBar) - An animated gradient loading bar. :large_orange_diamond:
* [DSGradientProgressView ★206](https://github.com/DholStudio/DSGradientProgressView) - A simple and customizable animated progress bar written in Swift. :large_orange_diamond:
* [GradientProgressBar](https://github.com/fxm90/GradientProgressBar) - A gradient progress bar (UIProgressView). :large_orange_diamond:
* [BPCircleActivityIndicator ★22](https://github.com/ppth0608/BPCircleActivityIndicator) - A lightweight and awesome Loading Activity Indicator for your iOS app. :large_orange_diamond:

#### Animation
* [Pop ★17582](https://github.com/facebook/pop) - An extensible iOS and OS X animation library, useful for physics-based interactions.
* [AnimationEngine ★1005](https://github.com/intuit/AnimationEngine) - Easily build advanced custom animations on iOS.
* [Awesome-iOS-Animation ★750](https://github.com/jackyzh/awesome-ios-animation) - Collection of Animation projects
* [RZTransitions ★1672](https://github.com/Raizlabs/RZTransitions) - A library of custom iOS View Controller Animations and Interactions.
* [DCAnimationKit ★699](https://github.com/daltoniam/DCAnimationKit) - A collection of animations for iOS. Simple, just add water animations.
* [Spring ★10574](https://github.com/MengTo/Spring) - A library to simplify iOS animations in Swift. :large_orange_diamond:
* [Canvas ★5149](https://github.com/CanvasPod/Canvas) - Animate in Xcode without code http://canvaspod.io
* [Fluent ★297](https://github.com/matthewcheok/Fluent) - Swift animation made easy :large_orange_diamond:
* [Cheetah ★535](https://github.com/suguru/Cheetah) - Easy animation library on iOS with Swift2. :large_orange_diamond:
* [RadialLayer](https://github.com/soheil/RadialLayer) - Animation for clickable elements (similar to Youtube Music). :large_orange_diamond:
* [Pop By Example ★160](https://github.com/hossamghareeb/Facebook-POP-Tutorial) - A project tutorial in how to use Pop animation framework by example.
* [AppAnimations](http://www.appanimations.com) - Collection of iOS animations to inspire your next project
* [EasyAnimation](https://github.com/icanzilb/EasyAnimation) - A Swift library to take the power of UIView.animateWithDuration() to a whole new level - layers, springs, chain-able animations, and mixing view/layer animations together. :large_orange_diamond:
* [Animo ★159](https://github.com/eure/Animo) - SpriteKit-like animation builders for CALayers. :large_orange_diamond:
* [CurryFire ★75](https://github.com/devinross/curry-fire) - A framework for creating unique animations.
* [IBAnimatable ★6206](https://github.com/IBAnimatable/IBAnimatable) - Design and prototype UI, interaction, navigation, transition and animation for App Store ready Apps in Interface Builder with IBAnimatable. :large_orange_diamond:
* [CKWaveCollectionViewTransition ★1499](https://github.com/CezaryKopacz/CKWaveCollectionViewTransition) - Cool wave like transition between two or more UICollectionView :large_orange_diamond:
* [DaisyChain ★19](https://github.com/alikaragoz/DaisyChain) - :link: Easy animation chaining :large_orange_diamond:
* [SYBlinkAnimationKit ★83](https://github.com/shoheiyokoyama/SYBlinkAnimationKit) - A blink effect animation framework for iOS, written in Swift. :large_orange_diamond:
* [PulsingHalo ★1523](https://github.com/shu223/PulsingHalo) - iOS Component for creating a pulsing animation.
* [DKChainableAnimationKit ★1737](https://github.com/Draveness/DKChainableAnimationKit) - Chainable animations in Swift :large_orange_diamond:
* [JDAnimationKit ★496](https://github.com/JellyDevelopment/JDAnimationKit) - Animate easy and with less code with Swift :large_orange_diamond:
* [Advance ★3921](https://github.com/storehouse/Advance) - A powerful animation framework for iOS. :large_orange_diamond:
* [UIView-Shake ★444](https://github.com/andreamazz/UIView-Shake) - UIView category that adds shake animation
* [Walker ★122](https://github.com/RamonGilabert/Walker) - A new animation engine for your app. :large_orange_diamond:
* [Morgan ★84](https://github.com/RamonGilabert/Morgan) - An animation set for your app. :large_orange_diamond:
* [MagicMove ★10](https://github.com/patrickreynolds/MagicMove) - Keynote-style Magic Move transition animations :large_orange_diamond:
* [Shimmer ★7731](https://github.com/facebook/Shimmer) - An easy way to add a simple, shimmering effect to any view in an iOS app.
* [SAConfettiView ★910](https://github.com/sudeepag/SAConfettiView) - Confetti! Who doesn't like confetti? :large_orange_diamond:
* [CCMRadarView ★177](https://github.com/cacmartinez/CCMRadarView) - CCMRadarView uses the IBDesignable tools to make an easy customizable radar view with animation :large_orange_diamond:
* [Pulsator ★688](https://github.com/shu223/Pulsator) - Pulse animation for iOS :large_orange_diamond:
* [Interpolate ★1470](https://github.com/marmelroy/Interpolate) - Swift interpolation for gesture-driven animations :large_orange_diamond:
* [ADPuzzleAnimation ★106](https://github.com/Antondomashnev/ADPuzzleAnimation) - Custom animation for UIView inspired by Fabric - Answers animation. :large_orange_diamond:
* [Wave ★59](https://github.com/onmyway133/Wave) - :ocean: Declarative chainable animations in Swift :large_orange_diamond:
* [Stellar ★2251](https://github.com/AugustRush/Stellar) - A fantastic Physical animation library for swift :large_orange_diamond:
* [MotionMachine ★315](https://github.com/poetmountain/MotionMachine) - A powerful, elegant, and modular animation library for Swift. :large_orange_diamond:
* [JRMFloatingAnimation ★145](https://github.com/carleihar/JRMFloatingAnimation) - An Objective-C animation library used to create floating image views.
* [AHKBendableView ★592](https://github.com/fastred/AHKBendableView) - UIView subclass that bends its edges when its position changes. :large_orange_diamond:
* [FlightAnimator ★544](https://github.com/AntonTheDev/FlightAnimator) - Advanced Natural Motion Animations, Simple Blocks Based Syntax :large_orange_diamond:
* [ZoomTransitioning ★506](https://github.com/WorldDownTown/ZoomTransitioning) - A custom transition with image zooming animation. :large_orange_diamond:
* [Ubergang ★38](https://github.com/RobinFalko/Ubergang) - A tweening engine for iOS written in Swift. :large_orange_diamond:
* [JHChainableAnimations ★2849](https://github.com/jhurray/JHChainableAnimations) - Easy to read and write chainable animations in Objective-C
* [Popsicle ★1124](https://github.com/DavdRoman/Popsicle) - Delightful, extensible Swift value interpolation framework :large_orange_diamond:
* [WXWaveView ★258](https://github.com/WelkinXie/WXWaveView) - Add a pretty water wave to your view.
* [Twinkle ★411](https://github.com/piemonte/Twinkle) - :sparkles: Swift and easy way to make elements in your iOS and tvOS app twinkle :large_orange_diamond:
* [MotionBlur ★1448](https://github.com/fastred/MotionBlur) - MotionBlur allows you to add motion blur effect to iOS animations.
* [RippleEffectView ★273](https://github.com/alsedi/RippleEffectView) - RippleEffectView - A Neat Rippling View Effect :large_orange_diamond:
* [Keyframes ★4343](https://github.com/facebookincubator/Keyframes) - A library for converting Adobe AE shape based animations to a data format and play it back on Android and iOS devices.
* [SwiftyAnimate ★122](https://github.com/rchatham/SwiftyAnimate) - Composable animations in Swift. :large_orange_diamond:
* [SamuraiTransition ★187](https://github.com/hachinobu/SamuraiTransition) - Swift based library providing a collection of ViewController transitions featuring a number of neat “cutting” animations. :large_orange_diamond:
* [Lottie ★8046](https://github.com/airbnb/lottie-ios) - An iOS library for a real time rendering of native vector animations from Adobe After Effects.
* [Overlap ★104](https://github.com/ML-Works/Overlap) - Tiny iOS library to achieve overlap visual effect. :large_orange_diamond:
* [anim ★17](https://github.com/onurersel/anim) - An animation library for iOS with custom easings and easy to follow API. :large_orange_diamond:
* [AnimatedCollectionViewLayout ★2319](https://github.com/KelvinJin/AnimatedCollectionViewLayout) - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView. :large_orange_diamond:
* [Dance ★565](https://github.com/saoudrizwan/Dance) - A radical & elegant animation library built for iOS. :large_orange_diamond:
* [AKVideoImageView ★107](https://github.com/numen31337/AKVideoImageView) - UIImageView subclass which allows you to display a looped video as a background.
* [Spruce iOS Animation Library ★1917](https://github.com/willowtreeapps/spruce-ios) - Swift library for choreographing animations on the screen.:large_orange_diamond:
* [CircularRevealKit ★6](https://github.com/T-Pro/CircularRevealKit) - UI framework that implements the material design's reveal effect. 🔶
* [TweenKit ★371](https://github.com/SteveBarnegren/TweenKit) - Animation library for iOS in Swift. 🔶
* [Water ★230](https://github.com/KrisYu/Water) - Simple calculation to render cheap water effects. 🔶

##### Transition
* [BlurryModalSegue ★917](https://github.com/Citrrus/BlurryModalSegue) - A custom modal segue for providing a blurred overlay effect.
* [DAExpandAnimation ★504](https://github.com/ifitdoesntwork/DAExpandAnimation) - A custom modal transition that presents a controller with an expanding effect while sliding out the presenter remnants. :large_orange_diamond:
* [BubbleTransition ★2374](https://github.com/andreamazz/BubbleTransition) - A custom modal transition that presents and dismiss a controller with an expanding bubble effect. :large_orange_diamond:
* [RPModalGestureTransition ★78](https://github.com/naoyashiga/RPModalGestureTransition) - You can dismiss modal by using gesture :point_up_2: :iphone: :large_orange_diamond:
* [RMPZoomTransitionAnimator ★1461](https://github.com/recruit-mp/RMPZoomTransitionAnimator) - A custom zooming transition animation for UIViewController
* [ElasticTransition ★1629](https://github.com/lkzhao/ElasticTransition) - A UIKit custom transition that simulates an elastic drag. Written in Swift. :large_orange_diamond:
* [ElasticTransition-ObjC ★341](https://github.com/taglia3/ElasticTransition-ObjC) - A UIKit custom transition that simulates an elastic drag.This is the Objective-C Version of Elastic Transition written in Swift by lkzhao
* [ZFDragableModalTransition ★2181](https://github.com/zoonooz/ZFDragableModalTransition) - Custom animation transition for present modal view controller
* [ImageOpenTransition ★762](https://github.com/mcmatan/ImageOpenTransition) - Beautiful and precise transitions between ViewControllers images written in Swift. :large_orange_diamond:
* [ZOZolaZoomTransition ★839](https://github.com/NewAmsterdamLabs/ZOZolaZoomTransition) - Zoom transition that animates the entire view heirarchy. Used extensively in the Zola iOS application.
* [JTMaterialTransition ★832](https://github.com/jonathantribouharet/JTMaterialTransition) - An iOS transition for controllers based on material design.
* [AnimatedTransitionGallery ★2106](https://github.com/shu223/AnimatedTransitionGallery) - Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol.
* [TransitionTreasury ★1783](https://github.com/DianQK/TransitionTreasury) - Easier way to push your viewController. :large_orange_diamond:
* [Presenter ★8](https://github.com/muukii/Presenter) - Screen transition with safe and clean code.  :large_orange_diamond:
* [Kaeru ★401](https://github.com/bannzai/Kaeru) - Switch viewcontroller like ios task manager :large_orange_diamond:
* [View2ViewTransition ★753](https://github.com/naru-jpn/View2ViewTransition) - Custom interactive view controller transition from one view to another view. :large_orange_diamond:
* [AZTransitions ★348](https://github.com/azimin/AZTransitions) - API to make great custom transitions in one method. :large_orange_diamond:
* [Hero ★8433](https://github.com/lkzhao/Hero) - Supercharged transition engine for iOS. Build your custom view transitions with no code at all. Inspired by Keynote's Magic Move. :large_orange_diamond:
* [Motion ★499](https://github.com/CosmicMind/Motion) - Seamless animations and transitions in Swift. :large_orange_diamond:
* [PresenterKit ★364](https://github.com/jessesquires/PresenterKit) - Swifty view controller presentation for iOS :large_orange_diamond:
* [Transition ★1529](https://github.com/Touchwonders/Transition) - Easy interactive interruptible custom ViewController transitions. :large_orange_diamond:

#### Alert & Action Sheet

* [NZAlertView ★712](https://github.com/NZN/NZAlertView) - Simple and intuitive alert view. Similar to push notification effect.
* [AMSmoothAlert ★1284](https://github.com/mtonio91/AMSmoothAlert) - A cool AlertView.
* [SweetAlert ★1653](https://github.com/codestergit/SweetAlert-iOS) - Live animated Alert View for iOS written in Swift. :large_orange_diamond:
* [NYAlertViewController ★478](https://github.com/nealyoung/NYAlertViewController) - Highly configurable iOS Alert Views with custom content views.
* [SCLAlertView-Swift ★3705](https://github.com/vikmeup/SCLAlertView-Swift) - Beautiful animated Alert View, written in Swift. :large_orange_diamond:
* [TTGSnackbar ★291](https://github.com/zekunyan/TTGSnackbar) - Show simple message and action button on the bottom of the screen with multi kinds of animation. :large_orange_diamond:
* [TSMessages ★4802](https://github.com/KrauseFx/TSMessages) - Show notification views on top of screen such as success, error, warning or messages for iOS.
* [PJAlertView ★6](https://github.com/PrajeetShrestha/PJAlertView) - Apple has deprecated beloved alert view but this library will add revamped alert view with far more customization possibility.
* [Swift-Prompts ★701](https://github.com/GabrielAlva/Swift-Prompts) - A Swift library to design custom prompts with a great scope of options to choose from. :large_orange_diamond:
* [BRYXBanner ★747](https://github.com/bryx-inc/BRYXBanner) - A lightweight dropdown notification for iOS 7+, in Swift. :large_orange_diamond:
* [LNRSimpleNotifications ★161](https://github.com/LISNR/LNRSimpleNotifications) - Simple Swift in-app notifications. LNRSimpleNotifications is a simplified Swift port of TSMessages :large_orange_diamond:
* [HDNotificationView ★232](https://github.com/nhdang103/HDNotificationView) - Emulates the native Notification Banner UI for any alert.
* [JDStatusBarNotification ★3094](https://github.com/calimarkus/JDStatusBarNotification) - Easy, customizable notifications displayed on top of the statusbar.
* [Notie ★71](https://github.com/thii/Notie) - In-app notification in Swift, with customizable buttons and input text field. :large_orange_diamond:
* [EZAlertController ★265](https://github.com/thellimist/EZAlertController) - Easy Swift UIAlertController :large_orange_diamond:
* [SnowGlobeFramework ★59](https://github.com/stringcode86/SnowGlobeFramework) - Delightful / slightly cheese easter egg for christmas season. Turns your awesome app into a snow globe, when user shake the device. :large_orange_diamond:
* [GSMessages ★190](https://github.com/wxxsw/GSMessages) - A simple style messages/notifications for iOS 7+. :large_orange_diamond:
* [OEANotification ★17](https://github.com/OEA/OEANotification) - In-app customizable notification views on top of screen for iOS which is written in Swift 2.1. :large_orange_diamond:
* [GSAlert ★25](https://github.com/wxxsw/GSAlert) - If you want to use UIAlertController, but still need to support iOS 7 this project is for you. :large_orange_diamond:
* [RKDropdownAlert ★1356](https://github.com/cwRichardKim/RKDropdownAlert) - Extremely simple UIAlertView alternative.
* [TKSwarmAlert ★410](https://github.com/entotsu/TKSwarmAlert) - Animated alert library like Swarm app. :large_orange_diamond:
* [Whisper ★2707](https://github.com/hyperoslo/Whisper) - Whisper is a component that will make the task of display messages and in-app notifications simple. It has three different views inside :large_orange_diamond:
* [SimpleAlert ★272](https://github.com/KyoheiG3/SimpleAlert) - Customizable simple Alert and simple ActionSheet for Swift :large_orange_diamond:
* [Hokusai ★355](https://github.com/ytakzk/Hokusai) - A Swift library to provide a bouncy action sheet :large_orange_diamond:
* [SwiftNotice](https://github.com/johnlui/SwiftNotice) - SwiftNotice is a GUI library for displaying various popups (HUD) written in pure Swift, fits any scrollview. :large_orange_diamond:
* [SwiftOverlays ★424](https://github.com/peterprokop/SwiftOverlays) - SwiftOverlays is a Swift GUI library for displaying various popups and notifications :large_orange_diamond:
* [SwiftyDrop ★513](https://github.com/morizotter/SwiftyDrop) - SwiftyDrop is a lightweight pure Swift simple and beautiful dropdown message. :large_orange_diamond:
* [LKAlertController ★53](https://github.com/Lightningkite/LKAlertController) - An easy to use UIAlertController builder for swift. :large_orange_diamond:
* [DOAlertController ★306](https://github.com/okmr-d/DOAlertController) - Simple Alert View written in Swift, which can be used as a UIAlertController. (AlertController/AlertView/ActionSheet) :large_orange_diamond:
* [CustomizableActionSheet ★118](https://github.com/beryu/CustomizableActionSheet) - Action sheet allows including your custom views and buttons. :large_orange_diamond:
* [Toast-Swift ★685](https://github.com/scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class. :large_orange_diamond:
* [PMAlertController ★1552](https://github.com/Codeido/PMAlertController) - PMAlertController is a great and customizable substitute to UIAlertController. 🔶
* [PopupViewController ★15](https://github.com/dimillian/PopupViewController) - UIAlertController drop in replacement with much more customization. 🔶
* [AlertViewLoveNotification ★21](https://github.com/PhilippeBoisney/AlertViewLoveNotification) - A simple and attractive AlertView to ask permission to your users for Push Notification. 🔶
* [CRToast ★3774](https://github.com/cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs
* [JLToast ★711](https://github.com/devxoul/Toaster) - Toast for iOS with very simple interface. :large_orange_diamond:
* [CuckooAlert ★5](https://github.com/singcodes/CuckooAlert) - Multiple use of presentViewController for UIAlertController. 🔶
* [KRAlertController ★31](https://github.com/krimpedance/KRAlertController) - A colored alert view for your iOS. :large_orange_diamond:
* [Dodo ★724](https://github.com/marketplacer/Dodo) - A message bar for iOS written in Swift. :large_orange_diamond:
* [MaterialActionSheetController ★79](https://github.com/ntnhon/MaterialActionSheetController) - A Google like action sheet for iOS written in Swift. :large_orange_diamond:
* [SwiftMessages ★2011](https://github.com/SwiftKickMobile/SwiftMessages) - A very flexible message bar for iOS written in Swift. :large_orange_diamond:
* [FCAlertView](https://github.com/krispenney/FCAlertView) - A Flat Customizable AlertView for iOS. (Swift) :large_orange_diamond:
* [FCAlertView](https://github.com/nimati/FCAlertView) - A Flat Customizable AlertView for iOS. (Objective-C)
* [CDAlertView ★639](https://github.com/candostdagdeviren/CDAlertView) - Highly customizable alert/notification/success/error/alarm popup 🔶
* [RMActionController ★208](https://github.com/CooperRS/RMActionController) - Present any UIView in an UIAlertController like manner.
* [RMDateSelectionViewController ★978](https://github.com/CooperRS/RMDateSelectionViewController) - Select a date using UIDatePicker in a UIAlertController like fashion.
* [RMPickerViewController ★310](https://github.com/CooperRS/RMPickerViewController) - Select something using UIPickerView in a UIAlertController like fashion.
* [Hedwig ★15](https://github.com/Lab111/Hedwig) - Interactive notification :large_orange_diamond:
* [Jelly ★1290](https://github.com/SebastianBoldt/Jelly) - Jelly provides custom view controller transitions with just a few lines of code. :large_orange_diamond:
* [Malert ★146](https://github.com/vitormesquita/Malert) - Malert is a simple, easy and custom iOS UIAlertView written in Swift 🔶
* [RAlertView ★29](https://github.com/roycms/AlertView) - AlertView, Ios popup window, A pop-up framework, Can be simple and convenient to join your project.
* [NoticeBar ★211](https://github.com/qiuncheng/NoticeBar) - 😍A simple NoticeBar written by Swift 3, similar with QQ notice view. :large_orange_diamond:
* [LIHAlert ★18](https://github.com/Lasithih/LIHAlert) - Advance animated banner alerts for iOS :large_orange_diamond:
* [BPStatusBarAlert](https://github.com/ppth0608/BPStatusBarAlert) - A simple alerts that appear on the status bar and below navigation bar(like Facebook).🔶
* [CFAlertViewController ★691](https://github.com/Codigami/CFAlertViewController) -  A library that helps you display and customise alerts and action sheets on iPad and iPhone.🔶
* [NotificationBanner ★30](https://github.com/Daltron/NotificationBanner) - The easiest way to display highly customizable in app notification banners in iOS. 🔶

#### Badge
* [MIBadgeButton ★246](https://github.com/mustafaibrahim989/MIBadgeButton-Swift) - Notification badge for UIButtons. :large_orange_diamond:
* [EasyNotificationBadge ★19](https://github.com/Minitour/EasyNotificationBadge) - UIView extension that adds a notification badge. :large_orange_diamond:[e]
* [Sheriff ★217](https://github.com/gemr/Sheriff) - Add badges to anything.
* [swift-badge ★179](https://github.com/marketplacer/swift-badge) - Badge view for iOS written in swift :large_orange_diamond:

#### Button
* [SSBouncyButton ★291](https://github.com/StyleShare/SSBouncyButton) - iOS7-style bouncy button UI component.
* [DOFavoriteButton ★2740](https://github.com/okmr-d/DOFavoriteButton) - Cute Animated Button written in Swift. :large_orange_diamond:
* [SDevBootstrapButton ★38](https://github.com/0x73/SDevBootstrapButton) - Twitter Bootstrap buttons for Swift :large_orange_diamond:
* [SDevCircleButton ★23](https://github.com/0x73/SDevCircleButton) - Flat circle button :large_orange_diamond:
* [VBFPopFlatButton ★2756](https://github.com/victorBaro/VBFPopFlatButton) - Flat button with 9 different states animated using Facebook POP.
* [HTPressableButton ★803](https://github.com/Famolus/HTPressableButton) - Flat design pressable button.
* [LiquidFloatingActionButton ★2917](https://github.com/yoavlt/LiquidFloatingActionButton) - Material Design Floating Action Button in liquid state :large_orange_diamond:
* [JTFadingInfoView ★122](https://github.com/JunichiT/JTFadingInfoView) - An UIButton-based view with fade in/out animation features.
* [KCFloatingActionButton ★410](https://github.com/kciter/Floaty) - :heart: Floating Action Button for iOS :large_orange_diamond:
* [Hamburger-Menu-Button ★115](https://github.com/toannt/Hamburger-Menu-Button) - A hamburger menu button with full customization. :large_orange_diamond:
* [TVButton](https://github.com/marmelroy/TVButton) - Recreating the cool parallax icons from Apple TV as iOS UIButtons (in Swift). :large_orange_diamond:
* [SwiftyButton ★203](https://github.com/TakeScoop/SwiftyButton) - Simple and customizable button in Swift :large_orange_diamond:
* [AnimatablePlayButton ★61](https://github.com/suzuki-0000/AnimatablePlayButton) - Animated Play and Pause Button using CALayer, CAKeyframeAnimation. :large_orange_diamond:
* [VCFloatingActionButton ★274](https://github.com/gizmoboy7/VCFloatingActionButton) - A Floating Action Button just like Google inbox for iOS
* [FlowBarButtonItem ★147](https://github.com/noppefoxwolf/FlowBarButtonItem) - Bar Button Item that can be moved anywhere in the screen, like Android's stickers button. :large_orange_diamond:
* [gbkui-button-progress-view ★498](https://github.com/Guidebook/gbkui-button-progress-view) - Inspired by Apple’s download progress buttons in the App Store.
* [ZFRippleButton ★1234](https://github.com/zoonooz/ZFRippleButton) - Custom UIButton effect inspired by Google Material Design :large_orange_diamond:
* [ProgressButton ★107](https://github.com/sprint84/ProgressButton) - Custom button class that displays a progress bar around it to gauge :large_orange_diamond:
* [JOEmojiableBtn ★199](https://github.com/lojals/JOEmojiableBtn) - Emoji selector like Facebook Reactions.
* [EMEmojiableBtn ★66](https://github.com/Eke/EMEmojiableBtn) - Option selector that works similar to Reactions by fb. Objective-c version.
* [WYMaterialButton ★40](https://github.com/Yu-w/WYMaterialButton) - Interactive and fully animated Material Design button for iOS developers.
* [DynamicButton ★803](https://github.com/yannickl/DynamicButton) - Yet another animated flat buttons in Swift :large_orange_diamond:
* [OnOffButton ★390](https://github.com/rakaramos/OnOffButton) - Custom On/Off Animated UIButton, written in Swift. By Creativedash :large_orange_diamond:
* [CRNetworkButton ★555](https://github.com/Cleveroad/CRNetworkButton) - Send Button for iOS :large_orange_diamond:
* [WCLShineButton ★801](https://github.com/imwcl/WCLShineButton) - This is a UI lib for iOS. Effects like shining. :large_orange_diamond:
* [EasySocialButton ★111](https://github.com/Minitour/EasySocialButton) - An easy way to create beautiful social authentication buttons. :large_orange_diamond:

#### Calendar
* [CVCalendar](https://github.com/CVCalendar/CVCalendar) - A custom visual calendar for iOS 8+ written in Swift (2.0). :large_orange_diamond:
* [RSDayFlow ★731](https://github.com/ruslanskorb/RSDayFlow) - iOS 7+ Calendar with Infinite Scrolling.
* [NWCalendarView ★54](https://github.com/nbwar/NWCalendarView) - An availability calendar implementation for iOS :large_orange_diamond:
* [FSCalendar ★4034](https://github.com/WenchaoD/FSCalendar) - A superiorly awesome iOS7+ calendar control, compatible with both Objective-C and Swift2.
* [GLCalendarView ★790](https://github.com/Glow-Inc/GLCalendarView) - A fully customizable calendar view acting as a date range picker
* [JTCalendar ★2298](https://github.com/jonathantribouharet/JTCalendar) - A customizable calendar view for iOS.
* [JTAppleCalendar ★2858](https://github.com/patchthecode/JTAppleCalendar) - The Unofficial Swift Apple Calendar Library. View. Control. for iOS & tvOS :large_orange_diamond:
* [Daysquare ★545](https://github.com/unixzii/Daysquare) - An elegant calendar control for iOS.
* [ASCalendar ★182](https://github.com/scamps88/ASCalendar) - A calendar control for iOS written in swift with mvvm pattern :large_orange_diamond:
* [Calendar ★466](https://github.com/jumartin/Calendar) - A set of views and controllers for displaying and scheduling events on iOS
* [Koyomi ★380](https://github.com/shoheiyokoyama/Koyomi) - Simple customizable calendar component in Swift :large_orange_diamond:
* [DateTimePicker ★1073](https://github.com/itsmeichigo/DateTimePicker) - A nicer iOS UI component for picking date and time :large_orange_diamond:
* [RCalendarPicker ★32](https://github.com/roycms/RCalendarPicker) - RCalendarPicker A date picker control.
* [CalendarKit ★679](https://github.com/richardtop/CalendarKit) - Fully customizable calendar day view. :large_orange_diamond:

#### Form & Settings
* [Form ★1538](https://github.com/hyperoslo/Form) - The most flexible and powerful way to build a form on iOS
* [XLForm ★4411](https://github.com/xmartlabs/XLForm) - XLForm is the most flexible and powerful iOS library to create dynamic table-view forms. Fully compatible with Swift & Obj-C.
* [Eureka ★5863](https://github.com/xmartlabs/Eureka) - Elegant iOS form builder in pure Swift. :large_orange_diamond:
* [YALField ★434](https://github.com/Yalantis/YALField) - Custom Field component with validation for creating easier form-like UI from interface builder.
* [Former ★892](https://github.com/ra1028/Former) - Former is a fully customizable Swift2 library for easy creating UITableView based form. :large_orange_diamond:
* [SwiftForms ★1056](https://github.com/ortuman/SwiftForms) - A small and lightweight library written in Swift that allows you to easily create forms. :large_orange_diamond:
* [APValidators ★103](https://github.com/Alterplay/APValidators) - Codeless solution for form validation in iOS!
* [Formalist ★115](https://github.com/seedco/Formalist) - Declarative form building framework for iOS :large_orange_diamond:
* [SwiftyFORM ★655](https://github.com/neoneye/SwiftyFORM) - SwiftyFORM is a form framework for iOS written in Swift :large_orange_diamond:
* [FXForms ★2977](https://github.com/nicklockwood/FXForms) - FXForms is an Objective-C library for easily creating table-based forms on iOS. It is ideal for settings pages, or user data entry tasks.
* [SwiftValidator ★860](https://github.com/jpotts18/SwiftValidator) - A rule-based validation library for Swift :large_orange_diamond:
* [MZFormSheetPresentationController ★794](https://github.com/m1entus/MZFormSheetPresentationController) - MZFormSheetPresentationController provides an alternative to the native iOS UIModalPresentationFormSheet, adding support for iPhone and additional opportunities to setup controller size and feel form sheet.
* [GenericPasswordRow ★117](https://github.com/EurekaCommunity/GenericPasswordRow) - A row for Eureka to implement password validations. :large_orange_diamond:
* [SuggestionsBox ★98](https://github.com/manuelescrig/SuggestionsBox) - SuggestionsBox helps you build better a product trough your user suggestions. :large_orange_diamond:
* [formvalidator-swift ★445](https://github.com/ustwo/formvalidator-swift) - A framework to validate inputs of text fields and text views in a convenient way. :large_orange_diamond:
* [LightForm ★2](https://github.com/farshidce/LightForm) - A Simple interactive and customizable library to handle form input and validations

#### Keyboard
* [RSKKeyboardAnimationObserver ★29](https://github.com/ruslanskorb/RSKKeyboardAnimationObserver) - Showing / dismissing keyboard animation in simple UIViewController category.
* [RFKeyboardToolbar ★390](https://github.com/ruddfawcett/RFKeyboardToolbar) - This is a flexible UIView and UIButton subclass to add customized buttons and toolbars to your UITextFields/UITextViews.
* [IQKeyboardManager ★8837](https://github.com/hackiftekhar/IQKeyboardManager) - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
* [NgKeyboardTracker ★756](https://github.com/meiwin/NgKeyboardTracker) - Objective-C library for tracking keyboard in iOS apps.
* [MMNumberKeyboard ★820](https://github.com/matmartinez/MMNumberKeyboard) - A simple keyboard to use with numbers and, optionally, a decimal point.
* [KeyboardObserver ★84](https://github.com/morizotter/KeyboardObserver) - For less complicated keyboard event handling. :large_orange_diamond:
* [TPKeyboardAvoiding ★5163](https://github.com/michaeltyson/TPKeyboardAvoiding) - A drop-in universal solution for moving text fields out of the way of the keyboard in iOS
* [YYKeyboardManager ★347](https://github.com/ibireme/YYKeyboardManager) - iOS utility class allows you to access keyboard view and track keyboard animation.
* [KeyboardMan ★320](https://github.com/nixzhu/KeyboardMan) - KeyboardMan helps you make keyboard animation. :large_orange_diamond:
* [MakemojiSDK](https://github.com/makemoji/MakemojiSDK) - Emoji Keyboard SDK (iOS)
* [Typist ★772](https://github.com/totocaster/Typist) - Small, drop-in Swift UIKit keyboard manager for iOS apps-helps manage keyboard's screen presence and behavior without notification center. :large_orange_diamond:
* [KeyboardHideManager ★37](https://github.com/bonyadmitr/KeyboardHideManager) - Codeless manager to hide keyboard by tapping on views for iOS written in Swift :large_orange_diamond:

#### Label
* [LTMorphingLabel ★5516](https://github.com/lexrus/LTMorphingLabel) - Graceful morphing effects for UILabel written in Swift. :large_orange_diamond:
* [ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift) - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://) written in Swift :large_orange_diamond:
* [MZTimerLabel ★1238](https://github.com/mineschan/MZTimerLabel) - A handy class for iOS to use UILabel as a countdown timer or stopwatch just like in Apple Clock App.
* [CountdownLabel ★252](https://github.com/suzuki-0000/CountdownLabel) - Simple countdown UILabel with morphing animation, and some useful function. :large_orange_diamond:
* [IncrementableLabel ★30](https://github.com/tbaranes/IncrementableLabel) - Incrementable label for iOS, OS X, and tvOS. :large_orange_diamond:
* [TTTAttributedLabel ★7416](https://github.com/TTTAttributedLabel/TTTAttributedLabel) - A drop-in replacement for UILabel that supports attributes, data detectors, links, and more
* [NumberMorphView ★1240](https://github.com/me-abhinav/NumberMorphView) - A label view for displaying numbers which can transition or animate using a technique called number tweening or number morphing. :large_orange_diamond:
* [GlitchLabel ★630](https://github.com/kciter/GlitchLabel) - Glitching UILabel for iOS. :large_orange_diamond:
* [TOMSMorphingLabel ★1822](https://github.com/tomknig/TOMSMorphingLabel) - Configurable morphing transitions between text values of a label.
* [THLabel ★518](https://github.com/tobihagemann/THLabel) - UILabel subclass, which additionally allows shadow blur, inner shadow, stroke text and fill gradient.
* [RQShineLabel ★1579](https://github.com/zipme/RQShineLabel) - Secret app like text animation
* [ZCAnimatedLabel ★1690](https://github.com/overboming/ZCAnimatedLabel) - UILabel replacement with fine-grain appear/disappear animation
* [TriLabelView ★95](https://github.com/mukeshthawani/TriLabelView) - A triangle shaped corner label view for iOS written in Swift. :large_orange_diamond:
* [Preloader.Ophiuchus ★798](https://github.com/Yalantis/Preloader.Ophiuchus) - Custom Label to apply animations on whole text or letters.
* [MTLLinkLabel ★65](https://github.com/recruit-mtl/MTLLinkLabel) - MTLLinkLabel is linkable UILabel. Written in Swift. :large_orange_diamond:
* [UICountingLabel ★1083](https://github.com/dataxpress/UICountingLabel) - Adds animated counting support to UILabel.
* [SlidingText ★27](https://github.com/dnKaratzas/SlidingText) -  Swift UIView for sliding text with page indicator. :large_orange_diamond:

#### Menu
* [ENSwiftSideMenu ★1677](https://github.com/evnaz/ENSwiftSideMenu) - A simple side menu for iOS 7/8 written in Swift. :large_orange_diamond:
* [RESideMenu ★6885](https://github.com/romaonthego/RESideMenu) - iOS 7/8 style side menu with parallax effect inspired by Dribbble shots.
* [SSASideMenu ★549](https://github.com/SSA111/SSASideMenu) - A Swift implementation of RESideMenu. A iOS 7/8 style side menu with parallax effect. :large_orange_diamond:
* [PagingMenuController ★1758](https://github.com/kitasuke/PagingMenuController) - Paging view controller with customizable menu in Swift. :large_orange_diamond:
* [RadialMenu](https://github.com/bradjasper/radialmenu) - RadialMenu is a custom control for providing a touch context menu (like iMessage recording in iOS 8) built with Swift & POP :large_orange_diamond:
* [cariocamenu ★527](https://github.com/arn00s/cariocamenu) - The fastest zero-tap iOS menu. :large_orange_diamond:
* [VLDContextSheet ★163](https://github.com/vangelov/VLDContextSheet) - Context menu similar to the one in the Pinterest iOS app
* [GuillotineMenu ★2408](https://github.com/Yalantis/GuillotineMenu) - Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine. :large_orange_diamond:
* [MediumMenu ★283](https://github.com/pixyzehn/MediumMenu) - A menu based on Medium iOS app. :large_orange_diamond:
* [SwiftySideMenu ★77](https://github.com/hossamghareeb/SwiftySideMenu) - SwiftySideMenu is a lightweight and easy to use side menu controller to add left menu and center view controllers with scale animation based on Pop framework.
* [LLSlideMenu ★510](https://github.com/lilei644/LLSlideMenu) - This is a spring slide menu for iOS apps
* [Swift-Slide-Menu ★53](https://github.com/PhilippeBoisney/Swift-Slide-Menu) - A Slide Menu, written in Swift, inspired by Slide Menu Material Design. :large_orange_diamond:
* [MenuItemKit](https://github.com/cxa/MenuItemKit) - UIMenuItem with image and block(closure) :large_orange_diamond:
* [BTNavigationDropdownMenu ★1961](https://github.com/PhamBaTho/BTNavigationDropdownMenu) - The elegant dropdown menu, written in Swift, appears underneath navigation bar to display a list of related items when a user click on the navigation title. :large_orange_diamond:
* [ALRadialMenu ★29](https://github.com/AlexLittlejohn/ALRadialMenu) - A radial/circular menu featuring spring animations. Written in swift :large_orange_diamond:
* [AZDropdownMenu ★137](https://github.com/Azuritul/AZDropdownMenu) - An easy to use dropdown menu that supports images. :large_orange_diamond:
* [CircleMenu ★2104](https://github.com/Ramotion/circle-menu) - An animated, multi-option menu button. :large_orange_diamond:
* [SlideMenuControllerSwift ★2387](https://github.com/dekatotoro/SlideMenuControllerSwift) - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app. It is written in pure Swift. :large_orange_diamond:
* [SideMenu ★1133](https://github.com/jonkykong/SideMenu) - Simple side menu control in Swift inspired by Facebook. Right and Left sides. Lots of customization and animation options. Can be implemented in Storyboard with no code. :large_orange_diamond:
* [CategorySliderView ★348](https://github.com/cemolcay/CategorySliderView) - slider view for choosing categories. add any UIView type as category item view. Fully customisable
* [MKDropdownMenu ★236](https://github.com/maxkonovalov/MKDropdownMenu) - A Dropdown Menu for iOS with many customizable parameters to suit any needs.
* [ExpandingMenu ★242](https://github.com/monoqlo/ExpandingMenu) - ExpandingMenu is menu button for iOS written in Swift. :large_orange_diamond:
* [PageMenu](https://github.com/uacaps/PageMenu) - A paging menu controller built from other view controllers placed inside a scroll view (like Spotify, Windows Phone, Instagram) :large_orange_diamond:
* [XXXRoundMenuButton ★265](https://github.com/zsy78191/XXXRoundMenuButton) - A simple circle style menu.
* [IGCMenu ★67](https://github.com/sunilsharma08/IGCMenu) - Grid and Circular menu with animation.Easy to customise.
* [EEJSelectMenu ★13](https://github.com/eejahromi/EEJSelectMenu) - Single selection menu with cool animations, responsive with all screen sizes.
* [IGLDropDownMenu ★1002](https://github.com/bestwnh/IGLDropDownMenu) - An iOS drop down menu with pretty animation and easy to customize.
* [Side-Menu.iOS ★2224](https://github.com/Yalantis/Side-Menu.iOS) - Animated side menu with customizable UI :large_orange_diamond:
* [PopMenu ★746](https://github.com/xhzengAIB/PopMenu) - PopMenu is pop animation menu inspired by Sina weibo / NetEase app.
* [FlowingMenu ★667](https://github.com/yannickl/FlowingMenu) - Interactive view transition to display menus with flowing and bouncing effects in Swift :large_orange_diamond:
* [Persei ★2614](https://github.com/Yalantis/Persei) - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift :large_orange_diamond:
* [DropDown ★755](https://github.com/AssistoLab/DropDown) - A Material Design drop down for iOS :large_orange_diamond:
* [KYGooeyMenu ★1649](https://github.com/KittenYang/KYGooeyMenu) - A not bad gooey effects menu.
* [SideMenuController ★820](https://github.com/teodorpatras/SideMenuController) - A side menu controller written in Swift :large_orange_diamond:
* [Context-Menu.iOS ★1679](https://github.com/Yalantis/Context-Menu.iOS) - You can easily add awesome animated context menu to your app.
* [ViewDeck ★5076](https://github.com/ViewDeck/ViewDeck) - An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps.
* [FrostedSidebar ★421](https://github.com/edekhayser/FrostedSidebar) - Hamburger Menu using Swift and iOS 8 API's :large_orange_diamond:
* [VHBoomMenuButton ★223](https://github.com/Nightonke/VHBoomMenuButton) - A menu which can ... BOOM!
* [DropDownMenuKit ★104](https://github.com/qmathe/DropDownMenuKit) - A simple, modular and highly customizable UIKit menu, that can be attached to the navigation bar or toolbar, written in Swift. :large_orange_diamond:
* [RevealMenuController ★13](https://github.com/anatoliyv/RevealMenuController) - Expandable item groups, custom position and appearance animation. Similar to ActionSheet style. :large_orange_diamond:
* [RHSideButtons](https://github.com/robertherdzik/RHSideButtons) - Library provides easy to implement variation of Android (Material Design) Floating Action Button for iOS. You can use it as your app small side menu. :large_orange_diamond:
* [Swift-CircleMenu ★96](https://github.com/Sufi-Al-Hussaini/Swift-CircleMenu) - Rotating circle menu written in Swift 3. :large_orange_diamond:
* [AKSideMenu ★77](https://github.com/dogo/AKSideMenu) - Beautiful iOS side menu library with parallax effect. :large_orange_diamond:
* [InteractiveSideMenu ★167](https://github.com/handsomecode/InteractiveSideMenu) - Customizable iOS Interactive Side Menu written in Swift 3. :large_orange_diamond:
* [YNDropDownMenu ★520](https://github.com/younatics/YNDropDownMenu) - Adorable iOS drop down menu with Swift3. :large_orange_diamond:
* [KWDrawerController ★24](https://github.com/Kawoou/KWDrawerController) - Drawer view controller that easy to use! large_orange_diamond:


#### Navigation Bar
* [HidingNavigationBar](https://github.com/tristanhimmelman/HidingNavigationBar) - Easily hide and show a view controller's navigation bar (and tab bar) as a user scrolls :large_orange_diamond:
* [TLYShyNavBar ★3131](https://github.com/telly/TLYShyNavBar) - Unlike all those arrogant UINavigationBar, this one is shy and humble! Easily create auto-scrolling navigation bars!
* [KMNavigationBarTransition ★1774](https://github.com/MoZhouqi/KMNavigationBarTransition) - A drop-in universal library helps you to manage the navigation bar styles and makes transition animations smooth between different navigation bar styles while pushing or popping a view controller for all orientations.
* [LTNavigationBar ★3917](https://github.com/ltebean/LTNavigationBar) - UINavigationBar Category which allows you to change its appearance dynamically
* [BusyNavigationBar ★802](https://github.com/gmertk/BusyNavigationBar) - A UINavigationBar extension to show loading effects :large_orange_diamond:
* [KDInteractiveNavigationController ★95](https://github.com/kingiol/KDInteractiveNavigationController) - A UINavigationController subclass that support pop interactive UINavigationbar with hidden or show. :large_orange_diamond:
* [AMScrollingNavbar ★4643](https://github.com/andreamazz/AMScrollingNavbar) - Scrollable UINavigationBar that follows the scrolling of a UIScrollView :large_orange_diamond:
* [NavKit ★15](https://github.com/wilbertliu/NavKit) - Simple and integrated way to customize navigation bar experience on iOS app. :large_orange_diamond:

#### PickerView
* [ActionSheetPicker-3.0 ★2546](https://github.com/skywinder/ActionSheetPicker-3.0) - Quickly reproduce the dropdown UIPickerView / ActionSheet functionality on iOS.
* [PickerView ★221](https://github.com/filipealva/PickerView) - A customizable alternative to UIPickerView in Swift. :large_orange_diamond:
* [DatePickerDialog ★258](https://github.com/squimer/DatePickerDialog-iOS-Swift) - Date picker dialog for iOS :large_orange_diamond:
* [CZPicker ★437](https://github.com/chenzeyu/CZPicker) - A picker view shown as a popup for iOS.
* [AIDatePickerController ★72](https://github.com/alikaragoz/AIDatePickerController) - :date: UIDatePicker modally presented with iOS 7 custom transitions.
* [CountryPicker ★26](https://github.com/4taras4/CountryCode) - :date: UIPickerView with Country names flags and phoneCodes 🔶

#### Popup
* [PopupKit](https://github.com/rynecheow/PopupKit) - A simple and flexible class for presenting custom views as a popup in iOS and tvOS, maintained from [KLCPopup ★1596](https://github.com/jmascia/KLCPopup).
* [MMPopupView](https://github.com/adad184/MMPopupView) - Pop-up based view(e.g. alert sheet), can easily customize.
* [STPopup ★1872](https://github.com/kevin0571/STPopup) - STPopup provides a UINavigationController in popup style, for both iPhone and iPad.
* [NMPopUpView ★166](https://github.com/psy2k/NMPopUpView) - Simple iOS class for showing nice popup windows. Swift and Objective-C versions available. :large_orange_diamond:
* [CNPPopupController ★1495](https://github.com/carsonperrotti/CNPPopupController) - Simple and versatile class for presenting a custom popup in a variety of fashions. It includes a many options for controlling how your popup appears and behaves.
* [PopupController ★195](https://github.com/daisuke310vvv/PopupController) - A customizable controller for showing temporary popup view.
* [SubscriptionPrompt ★187](https://github.com/binchik/SubscriptionPrompt) - Subscription View Controller like the Tinder uses :large_orange_diamond:
* [Presentr ★1279](https://github.com/IcaliaLabs/Presentr) - Wrapper for custom ViewController presentations in iOS 8+ :large_orange_diamond:
* [PopupDialog ★1683](https://github.com/Orderella/PopupDialog) - A simple, customizable popup dialog for iOS written in Swift. Replaces UIAlertControllers alert style. :large_orange_diamond:
* [KCSelectionDialog ★60](https://github.com/kciter/SelectionDialog) - Simple selection dialog. :large_orange_diamond:
* [AZDialogViewController ★15](https://github.com/Minitour/AZDialogViewController) - A highly customizable alert dialog controller that mimics Snapchat's alert dialog. :large_orange_diamond:

#### Pull to Refresh
* [DGElasticPullToRefresh ★2692](https://github.com/gontovnik/DGElasticPullToRefresh) - Elastic pull to refresh for iOS developed in Swift :large_orange_diamond:
* [PullToBounce ★1541](https://github.com/entotsu/PullToBounce) - Animated "Pull To Refresh" Library for UIScrollView. :large_orange_diamond:
* [SVPullToRefresh ★4699](https://github.com/samvermette/SVPullToRefresh) - Give pull-to-refresh & infinite scrolling to any UIScrollView with 1 line of code. http://samvermette.com/314
* [UzysAnimatedGifPullToRefresh ★1385](https://github.com/uzysjung/UzysAnimatedGifPullToRefresh) - Add PullToRefresh using animated GIF to any scrollView with just simple code
* [PullToRefreshCoreText ★310](https://github.com/cemolcay/PullToRefreshCoreText) - PullToRefresh extension for all UIScrollView type classes with animated text drawing style
* [BOZPongRefreshControl ★889](https://github.com/boztalay/BOZPongRefreshControl) - A pull-down-to-refresh control for iOS that plays pong, originally created for the MHacks III iOS app
* [CBStoreHouseRefreshControl ★3893](https://github.com/coolbeet/CBStoreHouseRefreshControl) - Fully customizable pull-to-refresh control inspired by Storehouse iOS app
* [SurfingRefreshControl ★44](https://github.com/peiweichen/SurfingRefreshControl) - Inspired by CBStoreHouseRefreshControl.Customizable pull-to-refresh control,written in pure Swift :large_orange_diamond:
* [mntpulltoreact ★770](https://github.com/mentionapp/mntpulltoreact) - One gesture, many actions. An evolution of Pull to Refresh.
* [ADChromePullToRefresh ★220](https://github.com/Antondomashnev/ADChromePullToRefresh) - Chrome iOS app style pull to refresh with multiple actions.
* [BreakOutToRefresh ★2072](https://github.com/dasdom/BreakOutToRefresh) - A playable pull to refresh view using SpriteKit. :large_orange_diamond:
* [MJRefresh ★10283](https://github.com/CoderMJLee/MJRefresh) An easy way to use pull-to-refresh.
* [HTPullToRefresh ★23](https://github.com/hoang-tran/HTPullToRefresh) - Easily add vertical and horizontal pull to refresh to any UIScrollView. Can also add multiple pull-to-refesh views at once.
* [PullToRefreshSwift ★454](https://github.com/dekatotoro/PullToRefreshSwift) - iOS Simple Cool PullToRefresh Library. It is written in pure swift. :large_orange_diamond:
* [GIFRefreshControl ★123](https://github.com/delannoyk/GIFRefreshControl) - GIFRefreshControl is a pull to refresh that supports GIF images as track animations. :large_orange_diamond:
* [ReplaceAnimation ★761](https://github.com/fruitcoder/ReplaceAnimation) - Pull-to-refresh animation in UICollectionView with a sticky header flow layout, written in Swift :large_orange_diamond: :large_orange_diamond:
* [PullToMakeSoup ★1584](https://github.com/Yalantis/PullToMakeSoup) - Custom animated pull-to-refresh that can be easily added to UIScrollView :large_orange_diamond:
* [RainyRefreshControl ★553](https://github.com/Onix-Systems/RainyRefreshControl) - Simple refresh control for iOS inspired by [concept](https://dribbble.com/shots/2242263--1-Pull-to-refresh-Freebie-Weather-Concept). :large_orange_diamond:
* [ESPullToRefresh ★478](https://github.com/eggswift/pull-to-refresh) - Customisable pull-to-refresh, including nice animation on the top :large_orange_diamond:

#### Rating Stars
* [FloatRatingView ★348](https://github.com/glenyi/FloatRatingView) - Whole, half or floating point ratings control written in Swift :large_orange_diamond:
* [TTGEmojiRate ★196](https://github.com/zekunyan/TTGEmojiRate) - An emoji-liked rating view for iOS, implemented in Swift. :large_orange_diamond:
* [StarryStars ★125](https://github.com/peterprokop/StarryStars) - StarryStars is iOS GUI library for displaying and editing ratings :large_orange_diamond:
* [Cosmos ★553](https://github.com/marketplacer/Cosmos) - A star rating control for iOS / Swift :large_orange_diamond:
* [HCSStarRatingView ★901](https://github.com/hsousa/HCSStarRatingView) - Simple star rating view for iOS written in Objective-C
* [MBRateApp ★47](https://github.com/MatiBot/MBRateApp) - A groovy app rate stars screen for iOS written in Swift :large_orange_diamond:

#### ScrollView
* [ScrollingFollowView ★127](https://github.com/ktanaka117/ScrollingFollowView) - ScrollingFollowView is a simple view which follows UIScrollView scrolling.
* [UIScrollView-InfiniteScroll ★662](https://github.com/pronebird/UIScrollView-InfiniteScroll) - UIScrollView infinite scroll category.
* [GoAutoSlideView ★39](https://github.com/zjmdp/GoAutoSlideView) - GoAutoSlideView extends UIScrollView by featuring infinitely and automatically slide.
* [AppStoreStyleHorizontalScrollView ★514](https://github.com/terenceLuffy/AppStoreStyleHorizontalScrollView) - App store style horizontal scroll view. :large_orange_diamond:
* [PullToDismiss ★126](https://github.com/sgr-ksmt/PullToDismiss) - You can dismiss modal viewcontroller by pulling scrollview or navigationbar in Swift. :large_orange_diamond:

#### Slider
* [VolumeControl ★54](https://github.com/12Rockets/VolumeControl) - Custom volume control for iPhone featuring a well-designed round slider.
* [WESlider ★75](https://github.com/Ekhoo/WESlider) - Simple and light weight slider with chapter management
* [IntervalSlider ★48](https://github.com/shushutochako/IntervalSlider) - IntervalSlider is a slider library like ReutersTV app. written in pure swift. :large_orange_diamond:
* [RangeSlider ★127](https://github.com/warchimede/RangeSlider) - A simple range slider made in Swift :large_orange_diamond:
* [CircleSlider ★103](https://github.com/shushutochako/CircleSlider) - CircleSlider is a Circular slider library. written in pure Swift. :large_orange_diamond:
* [MARKRangeSlider](https://github.com/vadymmarkov/MARKRangeSlider) - A custom reusable slider control with 2 thumbs (range slider).
* [ASValueTrackingSlider ★1667](https://github.com/alskipp/ASValueTrackingSlider) - A UISlider subclass that displays the slider value in a popup view
* [TTRangeSlider ★564](https://github.com/TomThorpe/TTRangeSlider) - A slider, similar in style to UISlider, but which allows you to pick a minimum and maximum range.
* [MMSegmentSlider ★21](https://github.com/MedvedevMax/MMSegmentSlider) - Customizable animated slider for iOS.
* [StepSlider ★91](https://github.com/spromicky/StepSlider) - StepSlider its custom implementation of slider such as UISlider for preset integer values.
* [JDSlider ★65](https://github.com/JellyDevelopment/JDSlider) - An iOS Slider written in Swift. :large_orange_diamond:
* [SnappingSlider ★519](https://github.com/rehatkathuria/SnappingSlider) - A beautiful slider control for iOS built purely upon Swift :large_orange_diamond:
* [MTCircularSlider ★12](https://github.com/EranBoudjnah/MTCircularSlider) - A feature-rich circular slider control. :large_orange_diamond:
* [VerticalSlider ★16](https://github.com/jonkykong/VerticalSlider) - VerticalSlider is a vertical implementation of the UISlider slider control. :large_orange_diamond:
* [CircularSlider ★136](https://github.com/taglia3/CircularSlider) - A powerful Circular Slider. It's written in Swift, it's 100% IBDesignable and all parameters are IBInspectable. :large_orange_diamond:
* [HGCircularSlider ★709](https://github.com/HamzaGhazouani/HGCircularSlider) - A custom reusable circular slider control for iOS application. :large_orange_diamond:
* [PivotSlider ★20](https://github.com/lab111/pivot-slider) - Slider that pivots :large_orange_diamond:
* [RangeSeekSlider ★84](https://github.com/WorldDownTown/RangeSeekSlider) - A customizable range slider for iOS. :large_orange_diamond:

#### Splash View
* [CBZSplashView ★1356](https://github.com/callumboddy/CBZSplashView) - Twitter style Splash Screen View. Grows to reveal the Initial view behind.
* [SKSplashView ★436](https://github.com/sachinkesiraju/SKSplashView) - Create custom animated splash views similar to the ones in the Twitter, Uber and Ping iOS app.
* [RevealingSplashView ★673](https://github.com/PiXeL16/RevealingSplashView) - A Splash view that animates and reveals its content, inspired by Twitter splash :large_orange_diamond:

#### Stepper
* [PFStepper ★24](https://github.com/PerfectFreeze/PFStepper) - May be the most elegant stepper you have ever had! :large_orange_diamond:
* [ValueStepper ★186](https://github.com/BalestraPatrick/ValueStepper) - A Stepper object that displays its value. :large_orange_diamond:
* [GMStepper ★514](https://github.com/gmertk/GMStepper) - A stepper with a sliding label in the middle. :large_orange_diamond:
* [barceloneta ★30](https://github.com/arn00s/barceloneta) - The right way to increment/decrement values with a simple gesture on iOS. :large_orange_diamond:
* [SnappingStepper ★313](https://github.com/yannickl/SnappingStepper) - An elegant alternative to the UIStepper written in Swift :large_orange_diamond:
* [SMNumberWheel] (https://github.com/SinaMoetakef/SMNumberWheel) - A custom control written in Swift, which is ideal for picking numbers very fast but yet very accurate using a rotating wheel :large_orange_diamond:

#### Switch
* [AnimatedSwitch ★142](https://github.com/alsedi/AnimatedSwitch) - UISwitch which paints over the parent view with the color in Swift. :large_orange_diamond:
* [ViralSwitch ★310](https://github.com/andreamazz/ViralSwitch) - A UISwitch that infects its superview with its tint color.
* [JTMaterialSwitch ★202](https://github.com/JunichiT/JTMaterialSwitch) - A customizable switch UI with ripple effect and bounce animations, inspired from Google's Material Design.
* [TKSwitcherCollection ★444](https://github.com/TBXark/TKSwitcherCollection) - An animate switch collection :large_orange_diamond:
* [SevenSwitch ★724](https://github.com/bvogelzang/SevenSwitch) - iOS7 style drop in replacement for UISwitch. :large_orange_diamond:
* [DGRunkeeperSwitch](https://github.com/gontovnik/DGRunkeeperSwitch) - Runkeeper design switch control (two part segment control) :large_orange_diamond:
* [PMZSwitch ★44](https://github.com/kovpas/PMZSwitch) - Yet another animated toggle :large_orange_diamond:
* [Switcher ★150](https://github.com/knn90/Switcher) - Swift - Custom UISwitcher with animation when change status :large_orange_diamond:
* [BetterSegmentedControl ★786](https://github.com/gmarm/BetterSegmentedControl) - An easy to use, customizable replacement for UISegmentedControl & UISwitch. :large_orange_diamond:
* [RAMPaperSwitch ★2167](https://github.com/Ramotion/paper-switch) - RAMPaperSwitch is a Swift module which paints over the parent view when the switch is turned on. :large_orange_diamond:
* [DynamicMaskSegmentSwitch ★285](https://github.com/KittenYang/DynamicMaskSegmentSwitch) - A segment switcher with dynamic text mask effect :large_orange_diamond:
* [LUNSegmentedControl ★164](https://github.com/Stormotion-Mobile/LUNSegmentedControl) - Customizable segmented control with interactive animation.
* [AKASegmentedControl ★402](https://github.com/alikaragoz/AKASegmentedControl) - :chocolate_bar: Fully customizable Segmented Control for iOS
* [AIFlatSwitch ★569](https://github.com/cocoatoucher/AIFlatSwitch) - A flat component alternative to UISwitch on iOS :large_orange_diamond:
* [Switch ★63](https://github.com/T-Pham/Switch) - An iOS switch control implemented in Swift with full Interface Builder support.🔶
* [TwicketSegmentedControl ★1022](https://github.com/twicketapp/TwicketSegmentedControl) - Custom UISegmentedControl replacement for iOS, written in Swift. :large_orange_diamond:
* [SJFluidSegmentedControl ★615](https://github.com/sasojadrovski/SJFluidSegmentedControl) - A segmented control with custom appearance and interactive animations. Written in Swift 3.0. :large_orange_diamond:
* [HMSegmentedControl ★2919](https://github.com/HeshamMegid/HMSegmentedControl) - A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products.
* [PinterestSegment ★254](https://github.com/TBXark/PinterestSegment) - A Pinterest-like segment control with masking animation. :large_orange_diamond:
* [YUSegment ★83](https://github.com/afishhhhh/YUSegment) - A customizable segmented control for iOS. Supports both text and image.

#### Tab Bar
* [ESTabBarController ★93](https://github.com/ezescaruli/ESTabBarController) - A tab bar controller for iOS that allows highlighting buttons and setting custom actions to them.
* [GooeyTabbar ★628](https://github.com/KittenYang/GooeyTabbar) -A gooey effect tabbar :large_orange_diamond:
* [animated-tab-bar ★7131](https://github.com/Ramotion/animated-tab-bar) - RAMAnimatedTabBarController is a Swift module for adding animation to tabbar items. :large_orange_diamond:
* [FoldingTabBar.iOS ★3103](https://github.com/Yalantis/FoldingTabBar.iOS) - Folding Tab Bar and Tab Bar Controller
* [GGTabBar](https://github.com/Goles/GGTabBar) - Another UITabBar & UITabBarController (iOS Tab Bar) replacement, but uses Auto Layout for arranging it's views hierarchy.
* [adaptive-tab-bar ★1699](https://github.com/Ramotion/adaptive-tab-bar) - AdaptiveController is a 'Progressive Reduction' Swift module for adding custom states to Native or Custom iOS UI elements :large_orange_diamond:
* [Pager ★190](https://github.com/lucoceano/Pager) - Easily create sliding tabs with Pager :large_orange_diamond:
* [XLPagerTabStrip ★3787](https://github.com/xmartlabs/XLPagerTabStrip) - Android PagerTabStrip for iOS. :large_orange_diamond:
* [TabPageViewController ★607](https://github.com/EndouMari/TabPageViewController) - Paging view controller and scroll tab view. 🔶
* [TabDrawer ★498](https://github.com/winslowdibona/TabDrawer) - Customizable TabBar UI element that allows you to run a block of code upon TabBarItem selection, written in Swift 🔶
* [SwipeViewController ★420](https://github.com/fortmarek/SwipeViewController) - SwipeViewController is a Swift modification of RKSwipeBetweenViewControllers - navigate between pages / ViewControllers :large_orange_diamond:
* [ColorMatchTabs ★866](https://github.com/Yalantis/ColorMatchTabs) - Interesting way to display tabs :large_orange_diamond:
* [BATabBarController ★581](https://github.com/antiguab/BATabBarController) - A TabBarController with a unique animation for selection
* [ScrollPager](https://github.com/aryaxt/ScrollPager) - A scroll pager that displays a list of tabs (segments) and manages paging between given views :large_orange_diamond:
* [Segmentio ★1216](https://github.com/Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift. :large_orange_diamond:
* [KYWheelTabController ★81](https://github.com/ykyouhei/KYWheelTabController) - KYWheelTabController is a subclass of UITabBarController.It displays the circular menu instead of UITabBar. :large_orange_diamond:
* [SuperBadges ★13](https://github.com/odedharth/SuperBadges) - Add emojis and colored dots as badges for your Tab Bar buttons 🔶
* [AZTabBarController ★58](https://github.com/Minitour/AZTabBarController) - A custom tab bar controller for iOS written in Swift 3.0 🔶
* [MiniTabBar ★42](https://github.com/D-32/MiniTabBar) - A clean simple alternative to the UITabBar 🔶
* [SwipeableTabBarController ★64](https://github.com/marcosgriselli/SwipeableTabBarController) - UITabBarController with swipe interaction between its tabs. 🔶
* [SMSwipeableTabView](https://github.com/smahajan28/SMSwipeableTabView) - Swipeable Views with Tabs (Like Android SwipeView With Tabs Layout) 🔶
* [Tabman ★246](https://github.com/uias/Tabman) - A powerful paging view controller with indicator bar for iOS. 🔶

#### Table View / Collection View
* [MGSwipeTableCell ★5226](https://github.com/MortimerGoro/MGSwipeTableCell) - UITableViewCell subclass that allows to display swippable buttons with a variety of transitions.
* [ParallaxTableViewHeader ★1199](https://github.com/Vinodh-G/ParallaxTableViewHeader) - Parallax scrolling effect on UITableView header view when a tableView is scrolled.
* [YXTPageView ★56](https://github.com/hanton/YXTPageView) - A PageView, which supporting scrolling to transition between a UIView and a UITableView.
* [DZNEmptyDataSet ★8332](https://github.com/dzenbot/DZNEmptyDataSet) - A drop-in UITableView/UICollectionView superclass category for showing empty datasets whenever the view has no content to display.
* [ConfigurableTableViewController ★235](https://github.com/fastred/ConfigurableTableViewController) - Typed, yet Flexible Table View Controller http://holko.pl/2016/01/05/typed-table-view-controller/ :large_orange_diamond:
* [CSStickyHeaderFlowLayout ★4571](https://github.com/CSStickyHeaderFlowLayout/CSStickyHeaderFlowLayout) - UICollectionView replacement of UITableView. Do even more like Parallax Header, Sticky Section Header. :large_orange_diamond:
* [folding-cell ★5590](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell inspired by folding paper material :large_orange_diamond:
* [Lightning-Table ★20](https://github.com/electrickangaroo/Lightning-Table) - A declarative api for working with UITableView.
* [Static ★903](https://github.com/venmo/Static) - Simple static table views for iOS in Swift. :large_orange_diamond:
* [GSKStretchyHeaderView ★845](https://github.com/gskbyte/GSKStretchyHeaderView) - Configurable yet easy to use stretchy header view for UITableView and UICollectionView.
* [MEVFloatingButton ★264](https://github.com/manuelescrig/MEVFloatingButton) - An iOS drop-in UITableView, UICollectionView and UIScrollView superclass category for showing a customizable floating button on top of it.
* [AMWaveTransition ★2279](https://github.com/andreamazz/AMWaveTransition) - Custom transition between viewcontrollers holding tableviews.
* [Dwifft ★1177](https://github.com/jflinter/Dwifft) - Swift Diff :large_orange_diamond:
* [CollapsableTable ★184](https://github.com/rob-nash/CollapsableTable) - A kit for building tableviews with a collapsable animation, for each section.
* [AEAccordion ★146](https://github.com/tadija/AEAccordion) - UITableViewController with accordion effect (expand / collapse cells). :large_orange_diamond:
* [SWTableViewCell](https://github.com/CEWendel/SWTableViewCell) - An easy-to-use UITableViewCell subclass that implements a swippable content view which exposes utility buttons (similar to iOS 7 Mail Application)
* [ZYThumbnailTableView ★865](https://github.com/liuzhiyi1992/ZYThumbnailTableView) - a TableView have thumbnail cell only, and you can use gesture let it expands other expansionView, all diy :large_orange_diamond:
* [BWSwipeRevealCell ★43](https://github.com/bitwit/BWSwipeRevealCell) - A Swift library for swipeable table cells :large_orange_diamond:
* [preview-transition ★1435](https://github.com/Ramotion/preview-transition) - PreviewTransition is a simple preview gallery controller :large_orange_diamond:
* [QuickTableViewController ★70](https://github.com/bcylin/QuickTableViewController) - A simple way to create a UITableView for settings in Swift. :large_orange_diamond:
* [TableKit ★205](https://github.com/maxsokolov/TableKit) - Type-safe declarative table views with Swift :large_orange_diamond:
* [Preheat ★557](https://github.com/kean/Preheat) - Automates prefetching of content in UITableView and UICollectionView :large_orange_diamond:
* [VBPiledView ★112](https://github.com/v-braun/VBPiledView) - Simple and beautiful stacked UIView to use as a replacement for an UITableView, UIImageView or as a menu :large_orange_diamond:
* [DisplaySwitcher ★1443](https://github.com/Yalantis/DisplaySwitcher) - Custom transition between two collection view layouts :large_orange_diamond:
* [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) - The waterfall (i.e., Pinterest-like) layout for UICollectionView.
* [FMMosaicLayout ★539](https://github.com/fmitech/FMMosaicLayout) - A drop-in mosaic collection view layout with a focus on simple customizations.
* [TRMosaicLayout ★125](https://github.com/vinnyoodles/TRMosaicLayout) - A mosaic collection view layout inspired by Lightbox's Algorithm, written in Swift 🔶
* [Reusable ★999](https://github.com/AliSoftware/Reusable) - A Swift mixin for UITableViewCells and UICollectionViewCells :large_orange_diamond:
* [VTMagic ★1313](https://github.com/tianzhuo112/VTMagic) - VTMagic is a page container library for iOS.
* [MCSwipeTableViewCell](https://github.com/alikaragoz/MCSwipeTableViewCell) - :point_up_2: Convenient UITableViewCell subclass that implements a swippable content to trigger actions (similar to the Mailbox app).
* [Sapporo ★225](https://github.com/nghialv/Sapporo) - Cellmodel-driven collectionview manager :large_orange_diamond:
* [MYTableViewIndex ★268](https://github.com/mindz-eye/MYTableViewIndex) - A pixel perfect replacement for UITableView section index, written in Swift :large_orange_diamond:
* [RAReorderableLayout ★722](https://github.com/ra1028/RAReorderableLayout) - A UICollectionView layout whitch can move item with drag and drop.
* [PageFeedControl ★26](https://github.com/rob-nash/PageFeedControl) - Add paging to your table views with a cool animation.
* [StickyCollectionView-Swift ★159](https://github.com/matbeich/StickyCollectionView-Swift) - UICollectionView layout for presenting of the overlapping cells. :large_orange_diamond:
* [ios-dragable-table-cells ★33](https://github.com/palmin/ios-dragable-table-cells) - Support for drag-n-drop of UITableViewCells in a navigation hierarchy of view controllers. You drag cells by tapping and holding them.
* [TLLayoutTransitioning ★318](https://github.com/SwiftKickMobile/TLLayoutTransitioning) - Enhanced transitioning between UICollectionView layouts in iOS.
* [Bohr ★1146](https://github.com/DavdRoman/Bohr) - Bohr allows you to set up a settings screen for your app with three principles in mind: ease, customization and extensibility.
* [SwiftReorder ★26](https://github.com/adamshin/SwiftReorder) - Add drag-and-drop reordering to any table view with just a few lines of code. Robust, lightweight, and completely customizable. :large_orange_diamond:[e]
* [TLIndexPathTools ★327](https://github.com/SwiftKickMobile/TLIndexPathTools) - TLIndexPathTools is a small set of classes that can greatly simplify your table and collection views.
* [HoverConversion ★157](https://github.com/marty-suzuki/HoverConversion) - HoverConversion realized vertical paging with UITableView. UIViewController will be paging when reaching top or bottom of UITableView contentOffset. :large_orange_diamond:
* [TableViewDragger ★296](https://github.com/KyoheiG3/TableViewDragger) - A cells of UITableView can be rearranged by drag and drop. :large_orange_diamond:
* [IGListKit ★5273](https://github.com/Instagram/IGListKit) - A data-driven UICollectionView framework for building fast and flexible lists.
* [MMCardView ★368](https://github.com/MillmanY/MMCardView) - Custom CollectionView like Wallet App :large_orange_diamond:
* [FlexibleTableViewController ★7](https://github.com/dimpiax/FlexibleTableViewController) - Swift library of generic table view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler
* [FlexibleCollectionViewController ★0](https://github.com/dimpiax/FlexibleCollectionViewController) - Swift library of generic collection view controller with external data processing of functionality, like determine cell's reuseIdentifier related to indexPath, configuration of requested cell for display and cell selection handler etc
* [CascadingTableDelegate ★729](https://github.com/edopelawi/CascadingTableDelegate) - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.:large_orange_diamond:
* [TimelineTableViewCell ★715](https://github.com/kf99916/TimelineTableViewCell) - Simple timeline view implemented by UITableViewCell written in Swift 3.0.:large_orange_diamond:
* [RHPreviewCell ★316](https://github.com/robertherdzik/RHPreviewCell) - I envied so much Spotify iOS app this great playlist preview cell. Now you can give your users ability to quick check "what content is hidden under your UITableViewCell". :large_orange_diamond:
* [ThreeLevelAccordian ★19](https://github.com/amratab/ThreeLevelAccordian) - This is a customisable three level accordian with options for adding images and accessories images. :large_orange_diamond:
* [TORoundedTableView ★38](https://github.com/TimOliver/TORoundedTableView) - A subclass of UITableView that styles it like Settings.app on iPad
* [ASCollectionView ★98](https://github.com/abdullahselek/ASCollectionView) - A Swift collection view inspired by Airbnb. :large_orange_diamond:
* [TableFlip ★303](https://github.com/mergesort/TableFlip) - A simpler way to do cool UITableView animations! (╯°□°）╯︵ ┻━┻ :large_orange_diamond:
* [DTTableViewManager ★290](https://github.com/DenHeadless/DTTableViewManager) - Protocol-oriented UITableView management, powered by generics and associated types. :large_orange_diamond:
* [GLTableCollectionView ★363](https://github.com/giulio92/GLTableCollectionView) - Netflix and App Store like UITableView with UICollectionView :large_orange_diamond:
* [SwipeCellKit ★1939](https://github.com/jerkoch/SwipeCellKit) - Swipeable UITableViewCell based on the stock Mail.app, implemented in Swift. :large_orange_diamond:
* [EditDistance ★39](https://github.com/kazuhiro4949/EditDistance) - Incremental update tool for UITableView and UICollectionView :large_orange_diamond:
* [CenteredCollectionView ★41](https://github.com/BenEmdon/CenteredCollectionView) - A lightweight CollectionView that _'pages'_ and _centers_ it's cells 🎡 written in Swift. :large_orange_diamond:
* [YBSlantedCollectionViewLayout ★106](https://github.com/yacir/YBSlantedCollectionViewLayout) - UICollectionViewLayout with slanted content.
* [ReverseExtension ★1024](https://github.com/marty-suzuki/ReverseExtension) - A UITableView extension that enables cell insertion from the bottom of a table view.
* [YNExpandableCell ★197](https://github.com/younatics/YNExpandableCell) - Awesome expandable, collapsible tableview cell for iOS written in Swift 3 🔶
* [SquareMosaicLayout ★26](https://github.com/iwheelbuy/SquareMosaicLayout) - An extandable mosaic UICollectionViewLayout with a focus on extremely flexible customizations 🔶
* [SwiftSpreadSheet ★368](https://github.com/stuffrabbit/SwiftSpreadsheet) - Spreadsheet CollectionViewLayout in Swift. Fully customizable. 🔶
* [GenericDataSource ★25](https://github.com/GenericDataSource/GenericDataSource) - A generic small reusable components for data source implementation for UITableView/UICollectionView in Swift. 🔶
* [BouncyLayout ★1231](https://github.com/roberthein/BouncyLayout) - BouncyLayout is a collection view layout that makes your cells bounce. 🔶

#### Tag
* [PARTagPicker ★239](https://github.com/paulrolfe/PARTagPicker) - This pod provides a view controller for choosing and creating tags in the style of wordpress or tumblr.
* [AMTagListView ★675](https://github.com/andreamazz/AMTagListView) - UIScrollView subclass that allows to add a list of highly customizable tags.
* [TagCellLayout ★90](https://github.com/riteshhgupta/TagCellLayout) - UICollectionView layout for Tags with Left, Center & Right alignments. :large_orange_diamond:
* [TTGTagCollectionView ★490](https://github.com/zekunyan/TTGTagCollectionView) - Show simple text tags or custom tag views in a vertical scrollable view.
* [TagListView ★957](https://github.com/ElaWorkshop/TagListView) - Simple and highly customizable iOS tag list view, in Swift. :large_orange_diamond:
* [RKTagsView](https://github.com/kuler90/RKTagsView) - Highly customizable iOS tags view (like NSTokenField). Supports editing, multiple selection, Auto Layout and much more.
* [WSTagsField ★570](https://github.com/whitesmith/WSTagsField) - An iOS text field that represents different Tags :large_orange_diamond:
* [AKMaskField ★161](https://github.com/artemkrachulov/AKMaskField) - AKMaskField is UITextField subclass which allows enter data in the fixed quantity and in the certain format. :large_orange_diamond:
* [YNSearch ★422](https://github.com/younatics/YNSearch) - Awesome fully customizable search view like Pinterest written in Swift 3 🔶

#### TextField & TextView
* [JVFloatLabeledTextField ★6214](https://github.com/jverdi/JVFloatLabeledTextField) - UITextField subclass with floating labels.
* [ARAutocompleteTextView ★256](https://github.com/alexruperez/ARAutocompleteTextView) - subclass of UITextView that automatically displays text suggestions in real-time. Perfect for email Textviews.
* [IQDropDownTextField ★209](https://github.com/hackiftekhar/IQDropDownTextField) - TextField with DropDown support using UIPickerView
* [UITextField-Shake](https://github.com/andreamazz/UITextField-Shake) - UITextField category that adds shake animation. [Also with Swift version ★12](https://github.com/King-Wizard/UITextField-Shake-Swift) :large_orange_diamond:
* [HTYTextField ★210](https://github.com/hanton/HTYTextField) - A UITextField with bouncy placeholder. :large_orange_diamond:
* [MVAutocompletePlaceSearchTextField ★64](https://github.com/TheMrugraj/MVAutocompletePlaceSearchTextField) - A drop-in Autocompletion control for Place Search like Google Places, Uber, etc.
* [AutocompleteField ★639](https://github.com/filipstefansson/AutocompleteField) - Add word completion to your UITextFields. :large_orange_diamond:
* [RSKGrowingTextView ★463](https://github.com/ruslanskorb/RSKGrowingTextView) - A light-weight UITextView subclass that automatically grows and shrinks. :large_orange_diamond:
* [RSKPlaceholderTextView ★37](https://github.com/ruslanskorb/RSKPlaceholderTextView) - A light-weight UITextView subclass that adds support for placeholder. :large_orange_diamond:
* [StatefulViewController ★1559](https://github.com/aschuch/StatefulViewController) - Placeholder views based on content, loading, error or empty states :large_orange_diamond:
* [MBAutoGrowingTextView ★114](https://github.com/MatejBalantic/MBAutoGrowingTextView) - An auto-layout base UITextView subclass which automatically grows with user input and can be constrained by maximal and minimal height - all without a single line of code
* [TextFieldEffects ★3858](https://github.com/raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift :large_orange_diamond:
* [Reel Search ★1715](https://github.com/Ramotion/reel-search) - RAMReel is a controller that allows you to choose options from a list. :large_orange_diamond:
* [MLPAutoCompleteTextField ★1094](https://github.com/EddyBorja/MLPAutoCompleteTextField) - a subclass of UITextField that behaves like a typical UITextField with one notable exception: it manages a drop down table of autocomplete suggestions that update as the user types.
* [SkyFloatingLabelTextField ★1787](https://github.com/Skyscanner/SkyFloatingLabelTextField) - A beautiful and flexible text field control implementation of "Float Label Pattern". Written in Swift.:large_orange_diamond:
* [VMaskTextField ★342](https://github.com/viniciusmo/VMaskTextField) - VMaskTextField is a library which create an input mask for iOS.
* [TJTextField ★31](https://github.com/tejas-ardeshna/TJTextField) - UITextField with underline and left image :large_orange_diamond:
* [NextGrowingTextView ★763](https://github.com/muukii/NextGrowingTextView) - The next in the generations of 'growing textviews' optimized for iOS 7 and above.
* [RPFloatingPlaceholders ★1081](https://github.com/iwasrobbed/RPFloatingPlaceholders) - UITextField and UITextView subclasses with placeholders that change into floating labels when the fields are populated with text.
* [CurrencyTextField ★16](https://github.com/richa008/CurrencyTextField) - UITextField that automatically formats text to display in the currency format. :large_orange_diamond:
* [UITextField-Navigation ★313](https://github.com/T-Pham/UITextField-Navigation) - UITextField-Navigation adds next, previous and done buttons to the keyboard for your UITextFields.🔶[e]
* [AutoCompleteTextField ★16](https://github.com/nferocious76/AutoCompleteTextField) - Auto complete with suggestion textfield :large_orange_diamond:
* [EmojiTextView ★337](https://github.com/fastred/EmojiTextView) - Tap to swap out words with emojis. Inspired by Messages.app on iOS 10. :large_orange_diamond:
* [PLCurrencyTextField ★79](https://github.com/nonameplum/PLCurrencyTextField) - UITextField that support currency in the right way. :large_orange_diamond:
* [PasswordTextField ★116](https://github.com/PiXeL16/PasswordTextField) - A custom TextField with a switchable icon which shows or hides the password and enforce good password policies :large_orange_diamond:
* [AnimatedTextInput ★414](https://github.com/jobandtalent/AnimatedTextInput) - Animated UITextField and UITextView replacement for iOS :large_orange_diamond:
* [KMPlaceholderTextView ★406](https://github.com/MoZhouqi/KMPlaceholderTextView) - A UITextView subclass that adds support for multiline placeholder written in Swift. :large_orange_diamond:
* [NxEnabled](https://github.com/Otbivnoe/NxEnabled) - Library which allows you binding `enabled` property of button with textable elements (TextView, TextField) :large_orange_diamond:
* [AwesomeTextField ★70](https://github.com/aleksandrshoshiashvili/AwesomeTextFieldSwift) - Awesome TextField is a nice and simple libriary for iOS. It's highly customisable and easy-to-use tool. Works perfectly for any registration or login forms in your app. :large_orange_diamond:
* [ModernSearchBar ★33](https://github.com/PhilippeBoisney/ModernSearchBar) - The famous iOS search bar with auto completion feature implemented. :large_orange_diamond:
* [SelectableTextView ★522](https://github.com/jhurray/SelectableTextView) - A text view that supports selection and expansion :large_orange_diamond:
* [CBPinEntryView ★12](https://github.com/Fawxy/CBPinEntryView) - A customisable view written in Swift 3.0 for any numerical pin or code entry. :large_orange_diamond:
* [GrowingTextView ★83](https://github.com/KennethTsang/GrowingTextView) - An UITextView in Swift3 and Swift2.3. Support auto growing, placeholder and length limit. :large_orange_diamond:
* [DTTextField ★39](https://github.com/iDhaval/DTTextField) - DTTextField is a custom textfield with floating placeholder and error label in Swift3.0.🔶
* [TextFieldCounter ★12](https://github.com/serralvo/TextFieldCounter) - UITextField character counter with lovable UX. 🔶

#### Web View
* [Otafuku ★43](https://github.com/tasanobu/Otafuku) - Otafuku provides utility classes to use WKWebView in Swift. :large_orange_diamond:
* [SwiftWebVC ★131](https://github.com/meismyles/SwiftWebVC) - A drop-in inline browser for your Swift iOS app. :large_orange_diamond:
* [SVWebViewController ★2482](https://github.com/TransitApp/SVWebViewController) - A drop-in inline browser for your iOS app.
* [PTPopupWebView ★50](https://github.com/pjocprac/PTPopupWebView) - PTPopupWebView is a simple and useful WebView for iOS, which can be popup and has many of the customized item. :large_orange_diamond:

## URL Scheme
* [WAAppRouting ★535](https://github.com/Wasappli/WAAppRouting) - iOS routing done right. Handles both URL recognition and controller displaying with parsed parameters. All in one line, controller stack preserved automatically!
* [DeepLinkKit ★2850](https://github.com/button/DeepLinkKit) - A splendid route-matching, block-based way to handle your deep links.
* [IntentKit ★1780](https://github.com/intentkit/IntentKit) - An easier way to handle third-party URL schemes in iOS apps.
* [JLRoutes ★3462](https://github.com/joeldev/JLRoutes) - URL routing library for iOS with a simple block-based API.
* [IKRouter ★91](https://github.com/IanKeen/IKRouter) - URLScheme router than supports auto creation of UIViewControllers for associated url parameters to allow creation of navigation stacks :large_orange_diamond:
* [Compass ★486](https://github.com/hyperoslo/Compass) - :earth_africa: Compass helps you setup a central navigation system for your application :large_orange_diamond:
* [Appz ★793](https://github.com/SwiftKitz/Appz) - Easily launch and deeplink into external applications, falling back to web if not installed. :large_orange_diamond:
* [URLNavigator ★1056](https://github.com/devxoul/URLNavigator) - ⛵️ Elegant URL Routing for Swift :large_orange_diamond:

## Utility
 * [Underscore.m ★1504](https://github.com/robb/Underscore.m) - A DSL for Data Manipulation.
 * [XExtensionItem ★78](https://github.com/tumblr/XExtensionItem) - Easier sharing of structured data between iOS applications and share extensions.
 * [ReflectableEnum ★325](https://github.com/fastred/ReflectableEnum) - Reflection for enumerations in Objective-C.
 * [ObjectiveSugar ★2179](https://github.com/supermarin/ObjectiveSugar) - ObjectiveC additions for humans. Ruby style.
 * [GroundControl ★1941](https://github.com/mattt/GroundControl) - Remote configuration for iOS.
 * [OpinionatedC ★44](https://github.com/leoschweizer/OpinionatedC) - Because Objective-C should have inherited more from Smalltalk.
 * [SwiftRandom ★439](https://github.com/thellimist/SwiftRandom) - Generator for random data. :large_orange_diamond:
 * [RandomKit ★1037](https://github.com/nvzqz/RandomKit) - Random data generation in Swift. :large_orange_diamond:
 * [YOLOKit ★615](https://github.com/mxcl/YOLOKit) - Getting square objects down round holes.
 * [EZSwiftExtensions ★2012](https://github.com/goktugyil/EZSwiftExtensions) - :smirk: How Swift standard types and classes were supposed to work. :large_orange_diamond:[e]
 * [Pantry ★804](https://github.com/nickoneill/Pantry) - The missing light persistence layer for Swift :large_orange_diamond:
 * [SwiftParsec ★105](https://github.com/davedufresne/SwiftParsec) - A parser combinator library written in the Swift programming language. :large_orange_diamond:
 * [OrderedSet ★94](https://github.com/Weebly/OrderedSet) - A Swift collection of unique, ordered objects :large_orange_diamond:
 * [Datez ★191](https://github.com/SwiftKitz/Datez) - Swift library for dealing with `NSDate`, `NSCalendar`, and `NSDateComponents`. :large_orange_diamond:
 * [BFKit ★726](https://github.com/FabrizioBrancati/BFKit) - An Objective-C collection of useful classes to develop Apps faster.
 * [BFKit-Swift ★561](https://github.com/FabrizioBrancati/BFKit-Swift) - A Swift collection of useful classes to develop Apps faster. :large_orange_diamond:
 * [Scale](https://github.com/onmyway133/scale) - Unit converter in Swift (available via CocoaPods) :large_orange_diamond:
 * [Standard Template Protocols ★376](https://github.com/cconeil/Standard-Template-Protocols) - Protocols for your every day iOS needs :large_orange_diamond:
 * [TimeLord](https://github.com/JonFir/TimeLord) - Easly DateTime (NSDate) managment in Swift :large_orange_diamond:
 * [AppVersionMonitor ★206](https://github.com/eure/AppVersionMonitor) - Monitor iOS app version easily.
 * [Sugar ★815](https://github.com/hyperoslo/Sugar) - Something sweet that goes great with your Cocoa. :large_orange_diamond:[e]
 * [Then ★1564](https://github.com/devxoul/Then) - ✨ Super sweet syntactic sugar for Swift initializers. :large_orange_diamond:[e]
 * [Kvitto ★177](https://github.com/Cocoanetics/Kvitto) - App Store Receipt Validation :large_orange_diamond:
 * [Notificationz ★51](https://github.com/SwiftKitz/Notificationz) - Helping you own NSNotificationCenter in Swift :large_orange_diamond:
 * [SwiftFoundation](https://github.com/PureSwift/SwiftFoundation) - Cross-Platform, Protocol-Oriented Programming base library to complement the Swift Standard Library. (Pure Swift, Supports Linux) :large_orange_diamond:[e]
 * [libextobjc ★3504](https://github.com/jspahrsummers/libextobjc) - A Cocoa library to extend the Objective-C programming language.
 * [VersionTrackerSwift ★49](https://github.com/tbaranes/VersionTrackerSwift) - Track which versions of your app a user has previously installed. :large_orange_diamond:
 * [DeviceGuru ★179](https://github.com/InderKumarRathore/DeviceGuru) - DeviceGuru is a simple lib (Swift) to know the exact type of the device, e.g. iPhone 6 or iPhone 6s. :large_orange_diamond:
 * [swift-algorithm-club ★12286](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift, with explanations! :large_orange_diamond:
 * [AEAppVersion ★5](https://github.com/tadija/AEAppVersion) - Simple and Lightweight App Version Tracking for iOS written in Swift :large_orange_diamond:
 * [BlocksKit ★6101](https://github.com/zwaldowski/BlocksKit) - The Objective-C block utilities you always wish you had.
 * [SwiftyUtils ★122](https://github.com/tbaranes/swiftyutils) - All the reusable code that we need in each project. :large_orange_diamond:[e]
 * [RateLimit ★827](https://github.com/soffes/RateLimit) - Simple utility for only executing code every so often. :large_orange_diamond:
 * [Outlets ★126](https://github.com/phatblat/Outlets) - Utility functions for validating IBOutlet and IBAction connections :large_orange_diamond:
 * [EasyAbout ★41](https://github.com/JARMourato/EasyAbout) - A way to easily add Cocoapod licenses and App Version to your iOS App using the Settings Bundle
 * [Validated ★562](https://github.com/Ben-G/Validated) - A Swift μ-Library for Somewhat Dependent Types :large_orange_diamond:
 * [Cent ★146](https://github.com/ankurp/Cent) - Extensions for Swift Standard Types and Classes :large_orange_diamond:
 * [AssistantKit ★390](https://github.com/anatoliyv/AssistantKit) - Easy way to detect iOS device properties, OS versions and work with screen sizes. Powered by Swift. :large_orange_diamond:
 * [SwiftLinkPreview ★651](https://github.com/LeonardoCardoso/SwiftLinkPreview) - It makes a preview from an url, grabbing all the information such as title, relevant texts and images. 🔶
 * [BundleInfos ★0](https://github.com/singcodes/BundleInfos) - Simple getter for Bundle informations. like short version from bundle. 🔶
 * [YAML.framework ★176](https://github.com/mirek/YAML.framework) - Proper YAML support for Objective-C based on `LibYAML`.
 * [ReadabilityKit ★563](https://github.com/exyte/ReadabilityKit) - Metadata extractor for news, articles and full-texts in Swift. 🔶
 * [MissionControl-iOS](https://github.com/appculture/MissionControl-iOS) - Super powerful remote config utility written in Swift (iOS, watchOS, tvOS, OSX) :large_orange_diamond:
 * [SwiftTweaks ★919](https://github.com/Khan/SwiftTweaks) - Tweak your iOS app without recompiling! :large_orange_diamond:
 * [UnsupportedOSVersionAlert](https://github.com/caloon/UnsupportedOSVersionAlert) - Alerts users with a popup if they use an app with an unsupported version of iOS (e.g. iOS betas) :large_orange_diamond:
 * [SwiftRouter ★126](https://github.com/skyline75489/SwiftRouter) - A URL Router for iOS, written in Swift 2.2 :large_orange_diamond:
 * [SwiftSortUtils ★57](https://github.com/dsmatter/SwiftSortUtils) - This library takes a shot at making sorting in Swift more pleasant. It also allows you to reuse your old NSSortDescriptor instances in Swift. :large_orange_diamond:
 * [Retry ★410](https://github.com/icanzilb/Retry) - Haven't you wished for `try` to sometimes try a little harder? Meet `retry` . :large_orange_diamond:
 * [ObjectiveKit ★622](https://github.com/marmelroy/ObjectiveKit) - Swift-friendly API for Objective C runtime functions. :large_orange_diamond:
 * [MoyaSugar ★41](https://github.com/devxoul/MoyaSugar) -  Syntactic sugar for Moya. :large_orange_diamond:
 * [SwifterSwift ★3215](https://github.com/SwifterSwift/SwifterSwift) -  A handy collection of more than 400 native Swift 3 extensions to boost your productivity. :large_orange_diamond:
 * [Eject ★494](https://github.com/Raizlabs/Eject) - An eject button for Interface Builder to generate swift code. :large_orange_diamond:
 * [ContactsWrapper ★16](https://github.com/abdullahselek/ContactsWrapper) - Easy to use wrapper for both contacts and contacts group with Objective-C.
 * [XestiMonitors ★235](https://github.com/eBardX/XestiMonitors) - An extensible monitoring framework written in Swift :large_orange_diamond:
 * [OpenSourceController ★25](https://github.com/terflogag/OpenSourceController) - The simplest way to display the librarie's licences used in your application. :large_orange_diamond:

## VR
* [VR Toolkit iOS ★69](https://github.com/Aralekk/VR_Toolkit_iOS) - A sample project that provides the basics to create an interactive VR experience on iOS :large_orange_diamond:
* [360 VR Player ★1571](https://github.com/hanton/HTY360Player) - A open source, ad-free, native and universal 360 degree panorama video player for iOS.
* [simple360player ★114](https://github.com/Aralekk/simple360player_iOS) - Free & ad-free 360 VR Video Player. Flat or Stereoscopic. In Swift 2. :large_orange_diamond:

## Walkthrough / Intro / Tutorial
* [Onboard ★5176](https://github.com/mamaral/Onboard) - Easily create a beautiful and engaging onboarding experience with only a few lines of code.
* [EAIntroView ★3341](https://github.com/ealeksandrov/EAIntroView) - Highly customizable drop-in solution for introduction views.
* [MYBlurIntroductionView ★1509](https://github.com/MatthewYork/MYBlurIntroductionView) - A super-charged version of MYIntroductionView for building custom app introductions and tutorials.
* [BWWalkthrough ★2366](https://github.com/ariok/BWWalkthrough) - A class to build custom walkthroughs for your iOS App. :large_orange_diamond:
* [GHWalkThrough ★733](https://github.com/GnosisHub/GHWalkThrough) - A UICollectionView backed drop-in component for introduction views.
* [ICETutorial ★824](https://github.com/icepat/ICETutorial) - A nice tutorial like the one introduced in the Path 3.X App.
* [JazzHands ★6137](https://github.com/IFTTT/JazzHands) - Jazz Hands is a simple keyframe-based animation framework for UIKit. Animations can be controlled via gestures, scroll views, KVO, or ReactiveCocoa.
* [RazzleDazzle ★2667](https://github.com/IFTTT/RazzleDazzle) - A simple keyframe-based animation framework for iOS, written in Swift. Perfect for scrolling app intros. :large_orange_diamond:
* [Instructions ★2664](https://github.com/ephread/Instructions) - Easily add customizable coach marks into you iOS project. :large_orange_diamond:
* [SwiftyWalkthrough ★187](https://github.com/ruipfcosta/SwiftyWalkthrough) - The easiest way to create a great walkthrough experience in your apps, powered by Swift. :large_orange_diamond:
* [Gecco ★1469](https://github.com/yukiasai/Gecco) - Spotlight view for iOS. :large_orange_diamond:
* [VideoSplashKit ★1052](https://github.com/mojilala/VideoSplashKit) - VideoSplashKit - UIViewController library for creating easy intro pages with background videos :large_orange_diamond:
* [Presentation ★2066](https://github.com/hyperoslo/Presentation) - Presentation helps you to make tutorials, release notes and animated pages. :large_orange_diamond:
* [AMPopTip ★1743](https://github.com/andreamazz/AMPopTip) - An animated popover that pops out a given frame, great for subtle UI tips and onboarding.
* [AlertOnboarding ★230](https://github.com/PhilippeBoisney/AlertOnboarding) - A simple and handsome AlertView for onboard your users in your amazing world. :large_orange_diamond:
* [EasyTipView ★1469](https://github.com/teodorpatras/EasyTipView) - Fully customisable tooltip view in Swift. :large_orange_diamond:
* [paper-onboarding ★1777](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design slider :large_orange_diamond:
* [InfoView ★30](https://github.com/anatoliyv/InfoView) - Swift based simple information view with pointed arrow. :large_orange_diamond:
* [Intro ★22](https://github.com/nbolatov/Intro) - An iOS framework to easily create simple animated walkthrough, written in Swift. :large_orange_diamond:
* [AwesomeSpotlightView ★16](https://github.com/aleksandrshoshiashvili/AwesomeSpotlightView) - Tool to create awesome tutorials or educate user to use application. Or just highlight something on screen. Written in Swift. :large_orange_diamond:
* [SwiftyOnboard ★467](https://github.com/juanpablofernandez/SwiftyOnboard) - A simple way to add onboarding to your project. :large_orange_diamond:
* [WVWalkthroughView ★18](https://github.com/praagyajoshi/WVWalkthroughView) - Utility to easily create walkthroughs to help with user onboarding.

## WebSocket
* [SocketRocket ★6734](https://github.com/facebook/SocketRocket) - A conforming Objective-C WebSocket client library.
* [socket.io-client-swift ★2245](https://github.com/socketio/socket.io-client-swift) - Socket.IO-client for iOS/OS X. :large_orange_diamond:
* [SwiftWebSocket ★775](https://github.com/tidwall/SwiftWebSocket) - High performance WebSocket client library for Swift, iOS and OSX. :large_orange_diamond:
* [Starscream ★2691](https://github.com/daltoniam/Starscream) - Websockets in swift for iOS and OSX :large_orange_diamond:
* [SwiftSocket ★510](https://github.com/swiftsocket/SwiftSocket) - simple socket library for apple swift lang. :large_orange_diamond:
* [Socks ★418](https://github.com/vapor/sockets) - Pure-Swift Sockets: TCP, UDP; Client, Server; Linux, OS X :large_orange_diamond:
* [SwifterSockets ★55](https://github.com/Balancingrock/SwifterSockets) - A collection of socket utilities in Swift for OS-X and iOS :large_orange_diamond:
* [Swift-ActionCableClient ★80](https://github.com/danielrhodes/Swift-ActionCableClient) - ActionCable is a new WebSocket server being released with Rails 5 which makes it easy to add real-time features to your app. :large_orange_diamond:

#### GCD
 * [GCDKit ★275](https://github.com/JohnEstropia/GCDKit) - Grand Central Dispatch simplified with Swift. :large_orange_diamond:
 * [Async ★3957](https://github.com/duemunk/Async) - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch :large_orange_diamond:
 * [SwiftSafe ★153](https://github.com/nodes-ios/SwiftSafe) - Thread synchronization made easy :large_orange_diamond:
 * [YYDispatchQueuePool ★243](https://github.com/ibireme/YYDispatchQueuePool) - iOS utility class to manage global dispatch queue.
 * [AlecrimAsyncKit ★67](https://github.com/Alecrim/AlecrimAsyncKit) - Bringing async and await to Swift world with some flavouring. :large_orange_diamond:
 * [GrandSugarDispatch](https://github.com/jessesquires/GrandSugarDispatch) - Syntactic sugar for Grand Central Dispatch (GCD) :large_orange_diamond:
 * [Threader ★41](https://github.com/mitchtreece/Threader) - Pretty GCD calls and easier code execution.
 * [Dispatch ★168](https://github.com/Swiftification/Dispatch) - Just a tiny library to make using GCD easier and intuitive :large_orange_diamond:
 * [GCDTimer](https://github.com/hemantasapkota/GCDTimer) - Well tested Grand Central Dispatch (GCD) Timer in Swift. :large_orange_diamond:
 * [Chronos-Swift ★246](https://github.com/comyar/Chronos-Swift) - :hourglass: Grand Central Dispatch Utilities :large_orange_diamond:
 * [Me ★195](https://github.com/pascalbros/Me) - A super slim solution to the nested asynchronous computations. :large_orange_diamond:
 * [SwiftyTask ★9](https://github.com/CR-Creations/SwiftyTask) - An extreme queuing system with high performance for managing all task in app with closure. :large_orange_diamond:

# Project setup
* [crafter ★529](https://github.com/krzysztofzablocki/crafter) - CLI that allows you to configure iOS project's template using custom DSL syntax, simple to use and quite powerful.
* [liftoff ★1526](https://github.com/liftoffcli/liftoff) - Another CLI for creating iOS projects.
* [amaro ★370](https://github.com/crushlovely/Amaro) - iOS Boilerplate full of delights.
* [chairs ★235](https://github.com/orta/chairs) - Swap around your iOS Simulator Documents
* [SwiftPlate ★1065](https://github.com/JohnSundell/SwiftPlate) - Easily generate cross platform Swift framework projects from the command line. :large_orange_diamond:

# Dependency / Package Manager
* [CocoaPods](https://cocoapods.org/) - CocoaPods is the dependency manager for Objective-C projects. It has thousands of libraries and can help you scale your projects elegantly.
* [Xcode Maven](http://sap-production.github.io/xcode-maven-plugin/site/) - The Xcode Maven Plugin can be used in order to run Xcode builds embedded in a Maven lifecycle.
* [Carthage ★9312](https://github.com/Carthage/Carthage) - A simple, decentralized dependency manager for Cocoa. :large_orange_diamond:
* [SWM (Swift Modules) ★55](https://github.com/jankuca/swm) - A package/dependency manager for Swift projects similar to npm (node.js package manager) or bower (browser package manager from Twitter). Does not require the use of Xcode. :large_orange_diamond:
* [Alcatraz](http://alcatraz.io/) - The package manager for Xcode.
* [CocoaSeeds ★310](https://github.com/devxoul/CocoaSeeds) - Git Submodule Alternative for Cocoa.
* [Podage ★8](https://github.com/jensmeder/Podage) - A simple tool to bundle any Cocoapod and its dependencies into frameworks.
* [swift-package-manager ★5441](https://github.com/apple/swift-package-manager) - The Package Manager for the Swift Programming Language :large_orange_diamond:
* [punic ★214](https://github.com/schwa/punic) - Clean room reimplementation of Carthage tool

# Tools
* [Shark ★272](https://github.com/kaandedeoglu/Shark) - Swift Script that transforms the .xcassets folder into a type safe enum. :large_orange_diamond:
* [SBConstants ★304](https://github.com/paulsamuels/SBConstants) - Generate a constants file by grabbing identifiers from storyboards in a project.
* [R.swift ★3521](https://github.com/mac-cain13/R.swift) - Tool to get strong typed, autocompleted resources like images, cells and segues in your Swift project. :large_orange_diamond:
* [SwiftGen](https://github.com/SwiftGen/SwiftGen) - A collection of Swift tools to generate Swift code (enums for your assets, storyboards, Localizable.strings and UIColors). :large_orange_diamond:
* [Blade ★763](https://github.com/jondot/blade) - Generate Xcode image catalogs for iOS / OSX app icons, universal images, and more.
* [Retini](https://github.com/terwanerik/Retini) - A super simple retina (2x, 3x) image converter.
* [Provisioning ★1325](https://github.com/chockenberry/Provisioning) - A Quick Look plug-in to preview .mobileprovision files.
* [Jazzy ★4313](https://github.com/realm/jazzy) - Soulful docs for Swift & Objective-C. :large_orange_diamond:
* [appledoc ★3635](https://github.com/tomaz/appledoc) - ObjectiveC code Apple style documentation set generator.
* [Azkaban ★66](https://github.com/neonichu/Azkaban) - A CLI to Alcatraz, the Xcode package manager. :large_orange_diamond:
* [Laurine ★981](https://github.com/JiriTrecak/Laurine) - Laurine - Localization code generator written in Swift. Sweet! :large_orange_diamond:
* [Chocolat ★186](https://github.com/pepibumur/Chocolat) - :chocolate_bar: Generate podspecs from Swift packages. :large_orange_diamond:
* [StoryboardMerge ★195](https://github.com/marcinolawski/StoryboardMerge) - Xcode storyboards diff and merge tool.
* [ai2app](https://github.com/metasmile/ai2appiconset) - Creating AppIcon sets from Adobe Illustrator (all supported formats).
* [ViewMonitor ★701](https://github.com/daisuke0131/ViewMonitor) - ViewMonitor can measure view positions with accuracy. :large_orange_diamond:
* [abandoned-strings ★60](https://github.com/ijoshsmith/abandoned-strings) - Command line program that detects unused resource strings in an iOS or OS X application. :large_orange_diamond:
* [swiftenv ★1240](https://github.com/kylef/swiftenv) - swiftenv allows you to easily install, and switch between multiple versions of Swift. :large_orange_diamond:
* [ThisCouldBeUsButYouPlaying](https://github.com/segiddins/ThisCouldBeUsButYouPlaying) - :black_joker: Generate Swift Playgrounds for any library. :large_orange_diamond:
* [Misen ★115](https://github.com/tasanobu/Misen) - Script to support easily using Xcode Asset Catalog in Swift. :large_orange_diamond:[e]
* [git-xcp ★14](https://github.com/metasmile/git-xcp) - A Git plugin for versioning workflow of real-world Xcode project. fastlane's best friend.
* [WatchdogInspector](https://github.com/tapwork/WatchdogInspector) - Shows your current framerate (fps) in the status bar of your iOS app
* [Cichlid ★254](https://github.com/dealforest/Cichlid) - automatically delete the current project's DerivedData directories :large_orange_diamond:
* [Delta ★238](https://github.com/thoughtbot/Delta) - Managing state is hard. Delta aims to make it simple. :large_orange_diamond:
* [SwiftLintXcode ★232](https://github.com/ypresto/SwiftLintXcode) - An Xcode plug-in to format your code using SwiftLint. :large_orange_diamond:
* [XCSwiftr ★299](https://github.com/dzenbot/XCSwiftr) - An Xcode Plugin to convert Objective-C to Swift :large_orange_diamond:
* [SwiftKitten ★121](https://github.com/johncsnyder/SwiftKitten) - Swift autocompleter for Sublime Text, via the adorable SourceKitten framework :large_orange_diamond:
* [Kin ★86](https://github.com/Karumi/Kin) - Have you ever found yourself undoing a merge due to a broken Xcode build? Then Kin is your tool. It will parse your project configuration file and detect errors. :large_orange_diamond:
* [AVXCAssets-Generator ★273](https://github.com/angelvasa/AVXCAssets-Generator) - AVXCAssets Generator takes path for your assets images and creates appiconset and imageset for you in just one click :large_orange_diamond:
* [Peek ★1148](https://github.com/shaps80/Peek) - Take a Peek at your application. :large_orange_diamond:
* [SourceKitten ★993](https://github.com/jpsim/SourceKitten) - An adorable little framework and command line tool for interacting with SourceKit. :large_orange_diamond:
* [Localizations ★95](https://github.com/athiercelin/localizations) - OS X app that manages localizations of Xcode projects. :large_orange_diamond:
* [xcbuild ★1272](https://github.com/facebook/xcbuild) - Xcode-compatible build tool.
* [XcodeIssueGenerator ★141](https://github.com/doubleencore/XcodeIssueGenerator) - An executable that can be placed in a Run Script Build Phase that marks comments like // TODO: or // SERIOUS: as warnings or errors so they display in the Xcode Issue Navigator. :large_orange_diamond:
* [SwiftCompilationPerformanceReporter ★146](https://github.com/tumblr/SwiftCompilationPerformanceReporter) - Generate automated reports for slow Swift compilation paths in specific targets :large_orange_diamond:
* [BuildTimeAnalyzer ★1635](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode) - Build Time Analyzer for Swift :large_orange_diamond:
* [Duration ★282](https://github.com/SwiftStudies/Duration) - A simple Swift package for measuring and reporting the time taken for operations :large_orange_diamond:
* [Benchmark ★50](https://github.com/WorldDownTown/Benchmark) - The Benchmark⏲ module provides methods to measure and report the time used to execute Swift code. :large_orange_diamond:
* [MBAssetsImporter](https://github.com/MatiBot/MBAssetsImporter) - Import assets from Panoramio or from your OS X file system with their metadata to your iOS simulator (Swift 2.0) :large_orange_diamond:
* [Realm Browser ★382](https://github.com/realm/realm-browser-osx) - Realm Browser is a Mac OS X utility to open and modify realm database files.
* [SuperDelegate ★367](https://github.com/square/SuperDelegate) – SuperDelegate provides a clean application delegate interface and protects you from bugs in the application lifecycle.
* [fastlane-plugin-appicon ★115](https://github.com/KrauseFx/fastlane-plugin-appicon) - Generate required icon sizes and iconset from a master application icon.
* [infer ★6629](https://github.com/facebook/infer) - A static analyzer for Java, C and Objective-C.
* [PlayNow ★92](https://github.com/marcboquet/PlayNow) - Small app that creates empty Swift playground files and opens them with Xcode. :large_orange_diamond:
* [Xtrace ★1631](https://github.com/johnno1962/Xtrace) - Trace Objective-C method calls by class or instance
* [xcenv ★195](https://github.com/xcenv/xcenv) - Groom your Xcode environment.
* [playgroundbook ★192](https://github.com/playgroundbooks/playgroundbook) - Tool for Swift Playground books
* [Ecno ★48](https://github.com/xmartlabs/Ecno) - Ecno is a task state manager built on top of UserDefaults in pure Swift 3. :large_orange_diamond:
* [ipanema ★3](https://github.com/toshi0383/ipanema) - ipanema analyzes and prints useful information from *.ipa file.
* [pxctest ★697](https://github.com/plu/pxctest) - Parallel XCTest - Execute XCTest suites in parallel on multiple iOS Simulators.
* [IBM Swift Sandbox](https://swift.sandbox.bluemix.net/verify) - The IBM Swift Sandbox is an interactive website that lets you write Swift code and execute it in a server environment – on top of Linux! :large_orange_diamond:
* [FBSimulatorControl ★1921](https://github.com/facebook/FBSimulatorControl) - A Mac OS X library for managing and manipulating iOS Simulators
* [IconResizer](https://iconresizer.com/) - A simple web application to resize iPhone and iPad app icons for the App Store
* [Nomad](http://nomad-cli.com) - Suite of command line utilities & libraries for sending APNs, create & distribute *.ipa*, verify In-App-Purchase receipt and more.
* [Cookiecutter ★371](https://github.com/JetpackSwift/FrameworkTemplate) - A template for new Swift iOS / tvOS / watchOS / macOS Framework project ready with travis-ci, cocoapods, Carthage, SwiftPM and a Readme file :large_orange_diamond:
* [Sourcery ★2020](https://github.com/krzysztofzablocki/Sourcery) - A tool that brings meta-programming to Swift, allowing you to code generate Swift code. :large_orange_diamond:
* [AssetChecker 👮 ★31](https://github.com/freshOS/AssetChecker) - Keeps your Assets.xcassets files clean and emits warnings when something is suspicious. :large_orange_diamond:
* [PlayAlways ★370](https://github.com/insidegui/PlayAlways) - Create Xcode playgrounds from your menu bar :large_orange_diamond:
* [GDPerformanceView-Swift ★1303](https://github.com/dani-gavrilov/GDPerformanceView-Swift) - Shows FPS, CPU usage, app and iOS versions above the status bar and report FPS and CPU usage via delegate. :large_orange_diamond:
* [Traits](https://github.com/krzysztofzablocki/Traits) - Library for a real-time design and behavior modification of native iOS apps without recompiling (code and interface builder changes are supported). :large_orange_diamond:
* [Struct](https://www.get-struct.tools) - A tool for iOS and Mac developers to automate the creation and management of Xcode projects.
* [Nori ★277](https://github.com/yukiasai/Nori) - Easier to apply code based style guide to storyboard. :large_orange_diamond:
* [DBDebugToolkit ★389](https://github.com/dbukowski/DBDebugToolkit) - Set of easy to use debugging tools for iOS developers & QA engineers.
* [Attabench ★471](https://github.com/lorentey/Attabench) - Microbenchmarking app for Swift with nice log-log plots :large_orange_diamond:
* [Gluten ★5](https://github.com/wilbertliu/Gluten) - Nano library to unify XIB and it's code. :large_orange_diamond:

# Rapid Development
* [KZPlayground ★2247](https://github.com/krzysztofzablocki/KZPlayground) - Playgrounds for Objective-C for extremely fast prototyping / learning.
* [MMBarricade ★343](https://github.com/mutualmobile/MMBarricade) - Runtime configurable local server for iOS apps.
* [STV Framework](http://www.sensiblecocoa.com) - Native visual iOS development.

# Injection
* [dyci ★1036](https://github.com/DyCI/dyci-main) - Code injection tool.
* [injectionforxcode ★4580](https://github.com/johnno1962/injectionforxcode) - Code injection including Swift.
* [Swinject ★1497](https://github.com/Swinject/Swinject) - Dependency injection framework for Swift
* [Reliant ★51](https://github.com/appfoundry/Reliant) - Nonintrusive Objective-C dependency injection.
* [Kraken ★17](https://github.com/sabirvirtuoso/Kraken) - A Dependency Injection Container for Swift with easy-to-use syntax.
* [Cleanse ★849](https://github.com/square/Cleanse) - Lightweight Swift Dependency Injection Framework by Square. :large_orange_diamond:
* [Typhoon](https://github.com/appsquickly/Typhoon) - Powerful dependency injection (Objective-C & Swift).
* [Perform ★223](https://github.com/thoughtbot/Perform) - Easy dependency injection for storyboard segues. :large_orange_diamond:
* [Alchemic ★10](https://github.com/drekka/Alchemic) - Advanced, yet simple to use DI framework for Objective-C.
* [Guise ★14](https://github.com/prosumma/Guise) - An elegant, flexible, type-safe dependency resolution framework for Swift :large_orange_diamond:

# Deployment / Distribution
* [fastlane ★15525](https://github.com/fastlane/fastlane) - Connect all iOS deployment tools into one streamlined workflow.
* [deliver](https://github.com/fastlane/fastlane/tree/master/deliver) - Upload screenshots, metadata and your app to the App Store using a single command.
* [snapshot](https://github.com/fastlane/fastlane/tree/master/snapshot) Automate taking localized screenshots of your iOS app on every device.
* [buddybuild](https://www.buddybuild.com/) - A mobile iteration platform - build, deploy, and collaborate.
* [Bitrise](https://www.bitrise.io) Mobile Continuous Integration & Delivery with dozens of integrations to build, test, deploy and collaborate.
* [watchbuild ★19](https://github.com/fastlane/watchbuild) - Get a notification once your iTunes Connect build is finished processing.
* [Crashlytics](https://try.crashlytics.com/) - A crash reporting and beta testing service.
* [TestFlight Beta Testing](https://developer.apple.com/testflight/) - The beta testing service hosted on iTunes Connect (requires iOS 8 or later).
* [HockeyApp](https://www.hockeyapp.net) - With HockeyApp, you can distribute beta versions of your app, collect live crash reports, get feedback from users, and analyze test coverage.
* [boarding ★510](https://github.com/fastlane/boarding) - Instantly create a simple signup page for TestFlight beta testers.
* [HockeyKit ★2195](https://github.com/bitstadium/HockeyKit) - A software update kit.
* [Boombox.io](https://boombox.io/) - Sign up TestFlight beta testers on your website. Embeddable and hosted TestFlight beta sign-up forms
* [Rollout.io](https://rollout.io/) - SDK to patch, fix bugs, modify and manipulate native apps (Obj-c & Swift) in real-time.
* [AppLaunchpad](https://theapplaunchpad.com/) - Free App Store screenshot builder.
* [LaunchKit ★1562](https://github.com/LaunchKit/LaunchKit) - A set of web-based tools for mobile app developers, now open source!

# App Store
* [Average App Store Review Times](http://appreviewtimes.com) This site tracks the average App Store review times for both the iOS and the Mac App Store using data crowdsourced from iOS and Mac developers.
* [Apple's Common App Rejections Styleguide](https://developer.apple.com/app-store/review/rejections/)  Highlighted some of the most common issues that cause apps to get rejected.
* [Free App Store Optimization Tool](https://www.mobileaction.co) Lets you track your App Store visibility in terms of keywords and competitors.
* [App Release Checklist](https://github.com/oisin/app-release-checklist/blob/master/checklist.md) - A checklist to pore over before you ship that amazing app that has taken ages to complete, but you don't want to rush out in case you commit a schoolboy error that will end up making you look dumber than you are.
* [Harpy ★2274](https://github.com/ArtSabintsev/Harpy) - Notify users when a new version of your iOS app is available, and prompt them with the App Store link.
* [iRate ★4140](https://github.com/nicklockwood/iRate) - A handy class that prompts users of your iPhone or Mac App Store app to rate your application after using it for a while. Similar to Appirater, but with a simpler, cleaner interface and automatic support for iOS fast application switching.
* [appirater ★4368](https://github.com/arashpayan/appirater) - A utility that reminds your iPhone app's users to review the app.
* [Siren ★1797](https://github.com/ArtSabintsev/Siren) - Notify users when a new version of your app is available and prompt them to upgrade. :large_orange_diamond:
* [Appstore Review Guidelines ★2](https://github.com/aashishtamsya/Appstore-Review-Guidelines) - A curated list of points which a developer has to keep in mind before submitting his/her application on appstore for review.

# Xcode

#### Plugins
* [FuzzyAutocompletePlugin ★3410](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin) - A Xcode 5+ plugin that adds more flexible autocompletion rather than just prefix-matching.
* [SCXcodeMiniMap ★1046](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap is a plugin that adds a source editor MiniMap to Xcode.
* [Show in Github ★242](https://github.com/larsxschneider/ShowInGitHub) - Xcode plugin to open the GitHub page of the commit of the currently selected line in the editor window.
* [BBUFullIssueNavigator ★248](https://github.com/neonichu/BBUFullIssueNavigator) - Xcode plugin for showing all issue content in the issue navigator.
* [BBUDebuggerTuckAway ★703](https://github.com/neonichu/BBUDebuggerTuckAway) - Xcode plugin for auto-hiding the debugger once you start typing in the source code editor.
* [SCXcodeSwitchExpander ★667](https://github.com/stefanceriu/SCXcodeSwitchExpander) - SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases.
* [VVDocumenter-Xcode ★8333](https://github.com/onevcat/VVDocumenter-Xcode) - Xcode plug-in which helps you write Javadoc style documents easier.
* [XAlign ★2628](https://github.com/qfish/XAlign) - An amazing Xcode plugin to align regular code. It can align anything by using custom alignment patterns.
* [CocoaPods Xcode Plugin ★2392](https://github.com/kattrali/cocoapods-xcode-plugin) - Dependency management helper for your CocoaPods, right in Xcode.
* [KSImageNamed-Xcode ★4293](https://github.com/ksuther/KSImageNamed-Xcode) - Xcode plug-in that provides autocomplete for imageNamed: calls.
* [ColorSense-for-Xcode ★2917](https://github.com/omz/ColorSense-for-Xcode) - Plugin for Xcode to make working with colors more visual.
* [Backlight-for-XCode ★442](https://github.com/limejelly/Backlight-for-XCode) - Highlights the current editing line in Xcode
* [KPRunEverywhereXcodePlugin ★329](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) - An Xcode plugin to build and run an app across multiple iOS devices with one click.
* [RevealPlugin ★236](https://github.com/shjborage/Reveal-Plugin-for-Xcode) - Plugin for Xcode to integrate the Reveal App to your project automatic.
* [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin)- Xcode plugin to generate new Realm models.
* [AdjustFontSize ★285](https://github.com/zats/AdjustFontSize-Xcode-Plugin) - Instant font size adjustment with `⌘ +` / `⌘ -`.
* [Rephrase](https://www.rephrase.io) - Localise from Xcode.
* [XCActionBar ★1226](https://github.com/pdcgomes/XCActionBar) - "Alfred for Xcode" plugin.
* [QuickJump ★27](https://github.com/wiruzx/QuickJump) - Quick code navigation for Xcode.
* [CATweaker ★703](https://github.com/keefo/CATweaker) - Plugin for creating beautiful CAMediaTimingFunction curve.
* [XcodeWay](https://github.com/onmyway133/XcodeWay) - An Xcode plugin that makes navigating to many places easier (available via Alcatraz).
* [GitDiff ★836](https://github.com/johnno1962/GitDiff) - Highlights deltas against git repo in Xcode.
* [MCLog ★609](https://github.com/yuhua-chen/MCLog) - Xcode plugin for filtering the console area.
* [XToDo ★1592](https://github.com/trawor/XToDo) - Dialog with list of all TODO, FIXME, ??? and !!! in the project.
* [CopyIssue ★179](https://github.com/hanton/CopyIssue-Xcode-Plugin) - Makes Copy Xcode Issue Description Easy.
* [RTImageAssets ★2377](https://github.com/rickytan/RTImageAssets) - A Xcode plugin to automatically generate all the App icons needed.
* [BBUncrustifyPlugin-Xcode ★1210](https://github.com/benoitsan/BBUncrustifyPlugin-Xcode) - Xcode plugin to format source code using ClangFormat or Uncrustify.
* [Aviator ★29](https://github.com/marksands/Aviator) - Xcode plugin that brings ⇧⌘T (source/test toggle) from AppCode over to Xcode.
* [JumpMarks ★50](https://github.com/merrickp/JumpMarks) - Navigate your code files with numbered bookmarks.
* [XCSnippetr ★95](https://github.com/dzenbot/XCSnippetr) - An Xcode Plugin to upload code snippets directly into Slack and Gist.
* [Peckham ★735](https://github.com/markohlebar/Peckham) - Add #import-s from anywhere in the code.
* [MLAutoReplace ★241](https://github.com/molon/MLAutoReplace) - Xcode plugin, Re-Intent, make you write code more quickly.
* [AutoHighlightSymbol ★73](https://github.com/chiahsien/AutoHighlightSymbol) - A Xcode plugin to add highlight to the instances of selected symbol.
* [Reveal-In-GitHub ★274](https://github.com/lzwjava/Reveal-In-Github) - Xcode plugin to let you jump to GitHub History, Blame, PRs, Issues, Notifications of any GitHub repo with one shortcut.
* [CleanHeaders-Xcode ★68](https://github.com/insanoid/CleanHeaders-Xcode) - A simple iSort like header sorting and duplicate removal plugin for Xcode, makes your headers look more organized.
* [Luft ★182](https://github.com/k0nserv/luft) - The Xcode Plugin that helps you write lighter view controllers
* [You-Can-Do-It ★233](https://github.com/orta/You-Can-Do-It) - Is learning a new language getting you down? Worry not, this Xcode plugin will keep you motivated.
* [PreciseCoverage ★172](https://github.com/zats/PreciseCoverage) - Make Xcode code coverage more informative
* [AutoIndentWithSave ★52](https://github.com/ThilinaHewagama/AutoIndentWithSave) Xcode plugin which indent the source code when save
* [Refactorator ★969](https://github.com/johnno1962/Refactorator) - Xcode Plugin that Refactors Swift & Objective-C :large_orange_diamond:
* [VWInstantRun ★1065](https://github.com/wangshengjia/VWInstantRun) - An Xcode plugin let you build & run your selected lines of code in Xcode without running the whole project, you'll have the output instantly in your Xcode console. :large_orange_diamond:
* [TTPasteHistory ★30](https://github.com/tutumagi/TTPasteHistory) - A Xcode plugin. Recording you copy-and-paste history easily to write the code
* [xSendIssue ★4](https://github.com/hungri-yeti/xSendIssue) - Plugin for Xcode to submit github issues directly from within Xcode.
* [Swimat ★650](https://github.com/Jintin/Swimat) - An Xcode formatter plug-in to format your swift code.
* [Fastlane-Plugin ★34](https://github.com/RishabhTayal/Fastlane-Plugin) - The awesome Fastlane tools brought into your Xcode.
* [Gradle Xcode plugin](https://openbakery.org/gxp/) - Build iOS or Mac OS X Projects using Gradle.
* [SYXcodeIconVersion ★95](https://github.com/dvkch/SYXcodeIconVersion) - This Xcode plugin shows Xcode app version in the Dock and App Switcher icon.
* [Gradle ★351](https://github.com/openbakery/gradle-xcodePlugin) - gradle xcodePlugin to build iOS and Mac projects.
* [HOStringSense-for-Xcode ★723](https://github.com/holtwick/HOStringSense-for-Xcode) - Plugin for Xcode to make perfect editing regular expressions, multi line texts, inline HTML and many more use cases. Also provides quick feedback on string length.
* [CleanClosureXcode ★133](https://github.com/BalestraPatrick/CleanClosureXcode) - An Xcode Source Editor extension to clean the closure syntax. :large_orange_diamond:
* [xTextHandler](https://github.com/cyanzhong/xTextHandler) - Xcode Source Editor Extension Toolset (Plugins for Xcode 8) :large_orange_diamond:
* [FastStub-Xcode ★487](https://github.com/music4kid/FastStub-Xcode) - Xcode Plugin helps you find missing methods in your class header, protocols, and super class, also makes fast inserting.
* [JSPatchX ★736](https://github.com/bang590/JSPatchX) - JSPatch bridge Objective-C and Javascript using the Objective-C runtime. You can call any Objective-C class and method in JavaScript by just including a small engine. JSPatch is generally use for hotfix iOS App.
* [Dash](https://kapeli.com/dash) - Dash is a great documentation browser which integrates closely into Xcode with its plugin.
* [SFJumpToLine ★10](https://github.com/sferrini/SFJumpToLine) - Xcode plugin that moves the instruction pointer to the selected line
* [ClangFormat-Xcode ★2492](https://github.com/travisjeffery/ClangFormat-Xcode) - An Xcode plug-in to format your code using Clang's format tools.
* [update_xcode_plugins ★854](https://github.com/inket/update_xcode_plugins) - No more messing with plugin UUIDs; Plugins on Xcode 8!
* [MakeXcodeGr8Again ★677](https://github.com/fpg1503/MakeXcodeGr8Again) - Xcode + Plugins = :blue_heart: :large_orange_diamond:
* [SwiftInitializerGenerator ★489](https://github.com/Bouke/SwiftInitializerGenerator) - Xcode 8 Source Code Extension to Generate Swift Initializers. :large_orange_diamond:
* [XcodeEquatableGenerator ★133](https://github.com/sergdort/XcodeEquatableGenerator) - Xcode 8 Source Code Extension will generate conformance to Swift Equatable protocol based on type and fields selection. :large_orange_diamond:
* [Import ★647](https://github.com/markohlebar/Import) - Xcode extension for adding imports from anywhere in the code. :large_orange_diamond:
* [Mark ★88](https://github.com/velyan/Mark) - Xcode extension for generating MARK comments. :large_orange_diamond:
* [XShared](https://github.com/Otbivnoe/XShared) - Xcode extension which allows you copying the code with special formatting quotes for social (Slack, Telegram). :large_orange_diamond:
* [XGist ★43](https://github.com/Bunn/Xgist) - Xcode extension which allows you to send your text selection or entire file to Github's Gist and automatically copy the Gist URL into your Clipboard. :large_orange_diamond:

#### Themes
* [Dracula Theme ★11](https://github.com/zenorocha/dracula-theme) - A dark theme for Xcode.
* [Xcode themes list ★1569](https://github.com/hdoria/xcode-themes) - Color themes for Xcode.
* [Solarized-Dark-for-Xcode ★245](https://github.com/ArtSabintsev/Solarized-Dark-for-Xcode) - Solarized Dark Theme for Xcode 5.
* [WWDC2016 Xcode Color Scheme ★330](https://github.com/cargath/WWDC2016-Xcode-Color-Scheme) - A color scheme for Xcode based on the WWDC 2016 invitation.

#### Other Xcode

* [awesome-xcode-scripts ★20](https://github.com/aashishtamsya/awesome-xcode-scripts) - A curated list of useful xcode scripts 📝.
* [Synx ★5347](https://github.com/venmo/synx) - A command-line tool that reorganizes your Xcode project folder to match your Xcode groups.
* [dsnip](https://github.com/Tintenklecks/IBDelegateCodesippets) - Tool to generate (native) Xcode code snippets from all protocols/delegate methods of UIKit (UITableView, ...)
* [SBShortcutMenuSimulator ★1757](https://github.com/DeskConnect/SBShortcutMenuSimulator) - 3D Touch shortcuts in the Simulator
* [awesome-gitignore-templates ★6](https://github.com/aashishtamsya/awesome-gitignore-templates) - A collection of swift, objective-c, android and many more langugages .gitignore templates 📝.
* [swift-project-template ★13](https://github.com/artemnovichkov/swift-project-template) - Template for iOS Swift project generation.
* [Swift-VIPER-Module ★152](https://github.com/Juanpe/Swift-VIPER-Module) - Xcode template for create modules with VIPER Architecture written in Swift 3 :large_orange_diamond:
* [ViperC ★23](https://github.com/abdullahselek/ViperC) - Xcode template for VIPER Architecture written in Objective-C

# Reference
* [Swift Cheat Sheet ★627](https://github.com/iwasrobbed/Swift-CheatSheet) - A quick reference cheat sheet for common, high level topics in Swift. :large_orange_diamond:
* [Objective-C Cheat Sheet ★906](https://github.com/iwasrobbed/Objective-C-CheatSheet) - A quick reference cheat sheet for common, high level topics in Objective-C.
* [SwiftSnippets ★86](https://github.com/hyperoslo/SwiftSnippets) - A collection of Swift snippets to be used in Xcode
* [App Store Checklist ★12](https://github.com/whitef0x0/app-store-checklist) - A checklist of what to look for before submitting your app to the App Store.

# Style Guides
* [NY Times - Objective C Style Guide ★4388](https://github.com/NYTimes/objective-c-style-guide) - The Objective-C Style Guide used by The New York Times.
* [raywenderlich Style Guide ★2507](https://github.com/raywenderlich/objective-c-style-guide) - A style guide that outlines the coding conventions for raywenderlich.com.
* [Github Objective-C Style Guide ★1630](https://github.com/github/objective-c-style-guide) - Style guide & coding conventions for Objective-C projects.
* [Objective-C Coding Convention and Best Practices](https://gist.github.com/soffes/812796) - Gist with coding conventions.
* [Swift Style Guide by @raywenderlich ★6994](https://github.com/raywenderlich/swift-style-guide) - The official Swift style guide for raywenderlich.com. :large_orange_diamond:
* [Spotify Objective-C Coding Style ★194](https://github.com/spotify/ios-style) - Guidelines for iOS development in use at Spotify.
* [Github - Style guide & coding conventions for Swift projects ★4027](https://github.com/github/swift-style-guide) - A guide to our Swift style and conventions by @github. :large_orange_diamond:
* [Futurice iOS Good Practices ★6010](https://github.com/futurice/ios-good-practices) - iOS starting guide and good practices suggestions by [@futurice](https://github.com/futurice).
* [Swift-Community-Best-Practices ★1869](https://github.com/schwa/Swift-Community-Best-Practices) - Best practices for software development with Swift :large_orange_diamond:
* [SlideShare Swift Style Guide](https://github.com/SlideShareInc/swift-style-guide/blob/master/swift_style_guide.md) - SlideShare Swift Style Guide we are using for our upcoming iOS 8 only app written in Swift :large_orange_diamond:
* [Prolific Interactive Style Guide ★136](https://github.com/prolificinteractive/swift-style-guide) - A style guide for Swift.

# Good Websites

#### News, Blogs and more
* [BGR](http://bgr.com/ios-7/)
* [iMore](http://www.imore.com/)
* [Lifehacker](http://lifehacker.com/tag/ios)
* [NSHipster](http://nshipster.com)
* [Objc.io](https://www.objc.io/)
* [ASCIIwwdc](http://asciiwwdc.com)
* [Natasha The Robot](https://www.natashatherobot.com/)
* [Apple's Swift Blog](https://developer.apple.com/swift/blog/) :large_orange_diamond:
* [iOS Programming Subreddit](https://www.reddit.com/r/iOSProgramming/)
* [iOS8-day-by-day ★2678](https://github.com/shinobicontrols/iOS8-day-by-day) :large_orange_diamond:
* [iOScreator](https://www.ioscreator.com/) :large_orange_diamond:
* [Mathew Sanders](http://mathewsanders.com/) :large_orange_diamond:
* [Little Bites of Cocoa](https://littlebitesofcocoa.com/) :large_orange_diamond:
* [iOS Dev Nuggets](http://hboon.com/iosdevnuggets/) :large_orange_diamond:
* [This Week in Swift](http://swiftnews.curated.co) :large_orange_diamond:
* [iOS Developer and Designer interview ★1281](https://github.com/9magnets/iOS-Developer-and-Designer-Interview-Questions) - A small guide to help those looking to hire a developer or designer for iOS work.
* [iOS9-day-by-day ★1426](https://github.com/shinobicontrols/iOS9-day-by-day) :large_orange_diamond:
* [Code Facebook](https://code.facebook.com/ios/)
* [iOS Cookies](http://www.ioscookies.com/) - A hand curated collection of iOS libraries written in Swift :large_orange_diamond:
* [Feeds for iOS Developer ★45](https://github.com/rgnlax/Feeds-for-iOS-Developer) - The list of RSS feeds for iOS developers.
* [iOS10 day-by-day](https://www.shinobicontrols.com/blog/ios-10-day-by-day-index) :large_orange_diamond:

#### UIKit references
* [iOS Fonts](http://iosfonts.com/)
* [UIAppearance list](https://gist.github.com/mattt/5135521)

#### Forums and discuss lists
* [iPhone Dev SDK Forum](http://iphonedevsdk.com/)
* ["iOS" on Stackoverflow](http://stackoverflow.com/questions/tagged/ios)

#### Tutorials and Keynotes
* [AppCoda](http://www.appcoda.com)
* [Tutorials Point](http://www.tutorialspoint.com/ios/)
* [Code with Chris](http://codewithchris.com/)
* [Cocoa with Love](http://www.cocoawithlove.com/)
* [Code School - Try Objective-C](http://tryobjectivec.codeschool.com/)
* [Brian Advent youtube channel](https://www.youtube.com/channel/UCysEngjfeIYapEER9K8aikw/videos) - Swift tutorials Youtube Channel. :large_orange_diamond:
* [RAYWENDERLICH](https://www.raywenderlich.com/tutorials) - Tutorials for developers and gamers
* [Ry’s Objective-C Tutorial](http://rypress.com/tutorials/objective-c/index)
* [Mike Ash](https://www.mikeash.com/pyblog/)
* [Big Nerd Ranch](https://www.bignerdranch.com/blog/categories/ios/) :large_orange_diamond:
* [Tuts+](https://code.tutsplus.com/categories/ios-sdk) :large_orange_diamond:
* [iOS-Blog](http://www.ios-blog.co.uk/) :large_orange_diamond:
* [Thinkster](https://thinkster.io/a-better-way-to-learn-swift) :large_orange_diamond:
* [Swift Education](https://github.com/swifteducation) - A community of educators sharing materials for teaching Swift and app development. :large_orange_diamond:
* [Cocoa Dev Central](http://cocoadevcentral.com)
* [Use Your Loaf](https://useyourloaf.com/)
* [Swift Tutorials by Jameson Quave](http://jamesonquave.com/blog/tutorials/) :large_orange_diamond:
* [Awesome-Swift-Education ★5154](https://github.com/hsavit1/Awesome-Swift-Education) - :fire: All of the resources for Learning About Swift :large_orange_diamond:
* [Awesome-Swift-Playgrounds ★1487](https://github.com/uraimo/Awesome-Swift-Playgrounds) - ⭐ A List of Awesome Swift Playgrounds! :large_orange_diamond:
* [learn-swift ★749](https://github.com/nettlep/learn-swift) - Learn Apple's Swift programming language interactively through these playgrounds. :large_orange_diamond:
* [Treehouse's iOS Courses and Workshops](https://teamtreehouse.com/library/topic:ios) - Topics for beginner and advanced developers in both Objective-C and Swift.
* [The Swift Summary Book ★1624](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language written on Playgrounds. :large_orange_diamond:
* [Hacking With Swift](https://www.hackingwithswift.com) - Learn to code iPhone and iPad apps with 3 Swift tutorials. :large_orange_diamond:

#### iOS UI Template
* [iOS UI Design Kit](https://www.invisionapp.com/tethr)
* [iOS Design Guidelines](http://ivomynttinen.com/blog/ios-design-guidelines)
* [iOS GUI by Facebook Design Resources](http://facebook.design/)

#### Prototyping
* [FluidUI](https://www.fluidui.com)
* [Proto.io](https://proto.io/)
* [Framer](https://framer.com/)
* [Pixate](http://www.pixate.com/)
* [Principle](http://principleformac.com)

#### Newsletters
* [iOS Goodies](http://ios-goodies.com) - Weekly iOS newsletter
* [This Week in Swift](https://swiftnews.curated.co) - I'm @NatashaTheRobot and I'm programmed to love #Swift! Every week, I put together a list of the best Swift resources for you. Happy Learning!
* [The iOS Times](http://theiostimes.com) - A weekly publication with news and trending projects in the open source iOS ecosystem.
* [Swift Sandbox](http://swiftsandbox.io) - Swift developer newsletter, curated collection of Swift open source news, projects & resources. :large_orange_diamond:
* [raywenderlich.com Weekly](https://www.raywenderlich.com/newsletter) - sign up to receive the latest tutorials from raywenderlich.com each week
* [iOS Dev Tools Weekly](https://iosdev.tools) - The greatest iOS development tools, including websites, desktop and mobile apps, and back-end services.
* [iOS Trivia Weekly](http://wanderbit.us4.list-manage.com/subscribe?u=4e20cd8ea3a0ce09ff4619a52&id=5898a5992b) - Three challenging questions about iOS development every Wednesday
* [Indie iOS Focus Weekly](https://indieiosfocus.curated.co) - Looking for the best iOS dev links, tutorials, & tips beyond the usual news? Curated by Chris Beshore. Published every Thursday.
* [iOS Dev Weekly](https://iosdevweekly.com/) - Subscribe to a hand-picked round up of the best iOS development links every week. Free.
* [Swift Weekly Brief](http://swiftweekly.github.io/) - A community-driven weekly newsletter about Swift.org. Curated by Jesse Squires and published for free every Thursday
* [Server-Side Swift Weekly](https://www.serverswift.tech) - A weekly newsletter with the best links related to server-side Swift and cross-platform developer tools. Curated by [@maxdesiatov](https://twitter.com/maxdesiatov)

#### Medium
* [iOS App Development](https://medium.com/ios-os-x-development) - Stories and technical tips about building apps for iOS, Apple Watch, and iPad/iPhone
* [Swift Programming](https://medium.com/swift-programming) - The Swift Programming Language

# Social Media

#### Twitter
* [@objcio](https://twitter.com/objcio)
* [@nshipster](https://twitter.com/NSHipster)
* [@CocoaPods](https://twitter.com/CocoaPods)
* [@CocoaPodsFeed](https://twitter.com/CocoaPodsFeed)
* [@RubyMotion](https://twitter.com/RubyMotion)
* [@SwiftSandbox](https://twitter.com/SwiftSandbox) - Swift open source news, projects and resources.


#### Facebook Groups
* [HH iOS](https://www.facebook.com/groups/hhios/)
* [Sketch - Official group](https://www.facebook.com/groups/sketchformac/)
* [Design-Code](https://www.facebook.com/groups/designcode/)
* [Sketch-Design.io](https://www.facebook.com/groups/sketchdesignio)
* [Origami Community](https://www.facebook.com/groups/origami.community/)
* [Framer JS](https://www.facebook.com/groups/framerjs/)

# Podcasts
* [The Ray Wenderlich Podcast](https://www.raywenderlich.com/rwpodcast)
* [Debug](http://www.imore.com/debug)
* [iDeveloper](http://blog.ideveloper.co/)
* [App Story](http://www.appstorypodcast.com)
* [Mobile Couch](http://mobilecouch.co/)
* [iPhreaks](https://devchat.tv/iphreaks)
* [Under the Radar](https://www.relay.fm/radar)
* [Core Intuition](http://www.coreint.org/)
* [Swift Playhouse](http://www.swiftplayhouse.com/)
* [Release Notes](https://releasenotes.tv/)
* [More Than Just Code](http://mtjc.fm/)
* [Runtime](https://spec.fm/podcasts/runtime)
* [Consult](http://consultpodcast.com/)

# Books
* [The Swift Programming Language by Apple](https://itunes.apple.com/us/book/swift-programming-language/id881256329?mt=11) :large_orange_diamond:
* [Using Swift with Cocoa and Objective C by Apple](https://itunes.apple.com/us/book/using-swift-cocoa-objective/id888894773?mt=11) :large_orange_diamond:
* [iOS Programming: The Big Nerd Ranch Guide by Christian Keur, Aaron Hillegass, Joe Conway](https://www.bignerdranch.com/books/ios-programming/)
* [Programming in Objective-C by Stephen G. Kochan](https://www.amazon.com/Programming-Objective-C-6th-Developers-Library/dp/0321967607)
* [The Complete Friday Q & A: Volume 1](https://www.mikeash.com/book.html)
* [Core Data for iOS: Developing Data-Driven Applications for the iPad, iPhone, and iPod touch](https://www.amazon.com/Core-Data-iOS-Data-Driven-Applications/dp/0321670426)
* [Cocoa Design Patterns](https://www.amazon.com/Cocoa-Design-Patterns-Erik-Buck/dp/0321535022)
* [Hello Swift! by Tanmay Bakshi with Lynn Beighley](https://www.manning.com/books/hello-swift) :large_orange_diamond:
* [OS Development with Swift by Craig Grummitt](https://www.manning.com/books/ios-development-with-swift) :large_orange_diamond:
* [Anyone Can Create an App by Wendy L. Wise](https://www.manning.com/books/anyone-can-create-an-app) :large_orange_diamond:
* [Advanced Swift by Chris Eidhof, Ole Begemann, and Airspeed Velocity](https://www.objc.io/books/advanced-swift/) :large_orange_diamond:
* [Functional Swift by Chris Eidhof, Florian Kugler, and Wouter Swierstra](https://www.objc.io/books/functional-swift/) :large_orange_diamond:
* [Core Data by Florian Kugler and Daniel Eggert](https://www.objc.io/books/core-data/) :large_orange_diamond:

# Other Awesome Lists
Other amazingly awesome lists can be found in the
* [awesome-awesomeness ★18656](https://github.com/bayandin/awesome-awesomeness) list.
* [Open Source apps ★13062](https://github.com/dkhamsing/open-source-ios-apps) list of open source ios apps
* Awesome-swift
  * [@matteocrippa ★11918](https://github.com/matteocrippa/awesome-swift) - A collaborative list of awesome swift resources.
  * [@Wolg ★3850](https://github.com/Wolg/awesome-swift) - A curated list of awesome Swift frameworks, libraries and software.
  * [Awesome-Swift-Education ★5154](https://github.com/hsavit1/Awesome-Swift-Education) - All of the resources for Learning About Swift :large_orange_diamond:
* [awesome watchkit apps ★187](https://github.com/sanketfirodiya/sample-watchkit-apps) curated list of sample watchkit apps and tutorials. :watch:
* [iOS Learning Resources ★211](https://github.com/sanketfirodiya/iOS-learning-resources) Comprehensive collection of high quality, frequently updated and well maintained iOS tutorial sites.
* [awesome-ios-animation ★2465](https://github.com/ameizi/awesome-ios-animation) - A curated list of awesome iOS animation, including Objective-C and Swift libraries.
* [awesome-ios-chart ★890](https://github.com/ameizi/awesome-ios-chart) - A curated list of awesome iOS chart libraries, including Objective-C and Swift.
* [awesome-gists ★149](https://github.com/vsouza/awesome-gists#ios) - A list of amazing gists (iOS section).
* [awesome-ios-ui ★9361](https://github.com/cjwirth/awesome-ios-ui) - A curated list of awesome iOS UI/UX libraries.
* [Awesome Reactive Programming in Swift ★84](https://github.com/SideEffects-xyz/Awesome-Reactive-Programming-Swift) - A collection of frameworks, talks and resources about reactive programming in Swift.
* [Awesome-Server-Side-Swift/TheList ★445](https://github.com/Awesome-Server-Side-Swift/TheList) - A list of Awesome Server Side Swift 3 projects
* [awesome-interview-questions ★14644](https://github.com/MaximAbramchuck/awesome-interview-questions#ios) - A curated awesome list of lists of interview questions including iOS.
* [Awesome-iOS-Companies](https://ioscompanies.info/about/welcome) - A curated geographical directory of companies doing iOS development.
* [iOS-Playbook ★48](https://github.com/bakkenbaeck/iOS-playbook) - Guidelines and best practices for excellent iOS apps

# Contributing and License
 * [See the guide](https://github.com/vsouza/awesome-ios/blob/master/.github/CONTRIBUTING.md)
 * Distributed under the MIT license. See LICENSE for more information.