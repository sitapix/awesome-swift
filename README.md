# Awesome Swift

A curated list of awesome Swift frameworks, libraries, and software.
- [Awesome Swift](#awesome-swift)
  - [🌐 API / Networking](#-api--networking)
  - [🧭 App Routing](#-app-routing)
  - [🛒 App Store / In-App Purchases](#-app-store--in-app-purchases)
  - [🏗️ Architecture Patterns](#️-architecture-patterns)
  - [🥽 AR / VR](#-ar--vr)
  - [🔊 Audio](#-audio)
  - [🔐 Authentication / Security](#-authentication--security)
  - [💾 Caching](#-caching)
  - [📅 Calendar / Date](#-calendar--date)
  - [📊 Charts / Graphs](#-charts--graphs)
  - [💬 Chat / Messaging](#-chat--messaging)
  - [⌨️ CLI / Command Line](#️-cli--command-line)
  - [✨ Code Quality](#-code-quality)
  - [⚡ Concurrency / Async](#-concurrency--async)
  - [🔒 Cryptography](#-cryptography)
  - [🧮 Data Structures / Algorithms](#-data-structures--algorithms)
  - [🗄️ Database](#️-database)
  - [💉 Dependency Injection](#-dependency-injection)
  - [📖 Documentation](#-documentation)
  - [🧰 Extensions / Utilities](#-extensions--utilities)
  - [📁 File Management](#-file-management)
  - [📝 Forms](#-forms)
  - [🎮 Games](#-games)
  - [🔌 Hardware](#-hardware)
  - [🖼️ Images](#️-images)
    - [Image Loading](#image-loading)
    - [Image Picking](#image-picking)
    - [Image Processing](#image-processing)
    - [Image Viewing](#image-viewing)
    - [GIF](#gif)
    - [QR Code](#qr-code)
  - [📋 JSON / Parsing](#-json--parsing)
    - [XML / HTML](#xml--html)
    - [YAML](#yaml)
    - [CSV](#csv)
    - [RSS / Feed](#rss--feed)
  - [⌨️ Keyboard](#️-keyboard)
  - [📐 Layout](#-layout)
  - [🌍 Localization](#-localization)
  - [📜 Logging](#-logging)
  - [🤖 Machine Learning / AI](#-machine-learning--ai)
  - [🖥️ macOS Apps](#️-macos-apps)
  - [⚠️ Malicious](#️-malicious)
  - [📝 Markdown](#-markdown)
  - [➗ Math](#-math)
  - [▶️ Media Player](#️-media-player)
  - [🧭 Menu / Navigation](#-menu--navigation)
  - [👋 Onboarding](#-onboarding)
  - [📱 Open Source iOS Apps](#-open-source-ios-apps)
  - [📄 PDF / Documents](#-pdf--documents)
  - [🔑 Permissions](#-permissions)
  - [⏳ Progress / Loading](#-progress--loading)
  - [⚛️ Reactive Programming](#️-reactive-programming)
  - [📚 Resources / Learning](#-resources--learning)
  - [🖥️ Server-Side Swift](#️-server-side-swift)
  - [💽 Storage](#-storage)
  - [🎨 SwiftUI](#-swiftui)
  - [📑 Tab Bar](#-tab-bar)
  - [🧪 Testing](#-testing)
  - [🔤 Text / Labels](#-text--labels)
    - [TextField](#textfield)
  - [🎭 Transitions / Presentations](#-transitions--presentations)
  - [🎨 UI Components](#-ui-components)
    - [Styling / Theming](#styling--theming)
    - [Alerts / Popups](#alerts--popups)
    - [Buttons](#buttons)
    - [Cards](#cards)
    - [CollectionView](#collectionview)
    - [Colors](#colors)
    - [Paging / Page Control](#paging--page-control)
    - [Pull to Refresh](#pull-to-refresh)
    - [Segmented Control](#segmented-control)
    - [Sliders](#sliders)
    - [Switches](#switches)
    - [TableView](#tableview)
    - [Other UI](#other-ui)
  - [🎥 Video](#-video)
  - [🌐 Web](#-web)
  - [🛠️ Xcode Tools](#️-xcode-tools)


## 🌐 API / Networking

- **[Alamofire](https://github.com/Alamofire/Alamofire)** - Elegant HTTP Networking in Swift.
- **[Moya](https://github.com/Moya/Moya)** - Network abstraction layer written in Swift.
- **[Starscream](https://github.com/daltoniam/Starscream)** - Websockets in swift for iOS and MacOS.
- **[swift-nio](https://github.com/apple/swift-nio)** - Event-driven network application framework for high performance protocol servers & clients, non-blocking.
- **[Reachability.swift](https://github.com/ashleymills/Reachability.swift)** - Replacement for Apple's Reachability re-written in Swift with closures.
- **[Pulse](https://github.com/kean/Pulse)** - Network logger for Apple platforms.
- **[apollo-ios](https://github.com/apollographql/apollo-ios)** - A strongly-typed, caching GraphQL client for iOS, written in Swift.
- **[AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper)** - An Alamofire extension which converts JSON response data into swift objects using ObjectMapper.
- **[SwiftHTTP](https://github.com/daltoniam/SwiftHTTP)** - Thin wrapper around NSURLSession in swift. Simplifies HTTP requests.
- **[SwiftWebSocket](https://github.com/tidwall/SwiftWebSocket)** - Fast Websockets in Swift for iOS and MacOS.
- **[Just](https://github.com/dduan/Just)** - Swift HTTP for Humans.
- **[Networking](https://github.com/3lvis/Networking)** - Swift HTTP Networking with stubbing and caching support.
- **[Connectivity](https://github.com/rwbutler/Connectivity)** - Makes Internet connectivity detection more robust by detecting Wi-Fi networks without Internet access.
- **[RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire)** - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire.
- **[SwiftLinkPreview](https://github.com/LeonardoCardoso/SwiftLinkPreview)** - It makes a preview from an URL, grabbing all the information such as title, relevant texts and images.
- **[ResponseDetective](https://github.com/netguru/ResponseDetective)** - Sherlock Holmes of the networking layer.
- **[SwiftSocket](https://github.com/swiftsocket/SwiftSocket)** - The easy way to use sockets on Apple platforms.
- **[netfox](https://github.com/kasketis/netfox)** - A lightweight, one line setup, iOS / MacOS network debugging library!.
- **[Bagel](https://github.com/yagiz/Bagel)** - a little native network debugging tool for iOS.
- **[Networking](https://github.com/freshOS/Networking)** - Concise networking code leveraging async-await, Decodable & Generics.
- **[grpc-swift](https://github.com/grpc/grpc-swift)** - The Swift language implementation of gRPC.
- **[siesta](https://github.com/bustoutsolutions/siesta)** - The civilized way to write REST API clients for iOS / macOS.
- **[CocoaMQTT](https://github.com/emqx/CocoaMQTT)** - MQTT 5.0 client library for iOS and macOS written in Swift.
- **[swift-http-types](https://github.com/apple/swift-http-types)** - Version-independent HTTP currency types for Swift.
- **[swift-protobuf](https://github.com/apple/swift-protobuf)** - Plugin and runtime library for using protobuf with Swift.
- **[protobuf-swift](https://github.com/alexeyxo/protobuf-swift)** - Google ProtocolBuffers for Apple Swift.
- **[Alamofire-SwiftyJSON](https://github.com/SwiftyJSON/Alamofire-SwiftyJSON)** - Alamofire extension for serialize NSData to SwiftyJSON.
- **[Tiercel](https://github.com/Danie1s/Tiercel)** - 简单易用、功能丰富的纯 Swift 下载框架.
- **[Pitaya](https://github.com/johnlui/Pitaya)** - A Swift HTTP / HTTPS networking library.

*[↑ Back to top](#contents)*

## 🧭 App Routing

- **[URLNavigator](https://github.com/devxoul/URLNavigator)** - Elegant URL Routing for Swift.
- **[Compass](https://github.com/hyperoslo/Compass)** - Compass helps you setup a central navigation system for your application.
- **[Appz](https://github.com/SwiftKitz/Appz)** - Launch external apps, and deeplink, with ease using Swift!.
- **[knil](https://github.com/ethanhuang13/knil)** - Universal Links testing made easy.

*[↑ Back to top](#contents)*

## 🛒 App Store / In-App Purchases

- **[SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)** - Lightweight In App Purchases Swift framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+.
- **[purchases-ios](https://github.com/RevenueCat/purchases-ios)** - In-app purchases and subscriptions made easy. Support for iOS, watchOS, tvOS, macOS, and visionOS.
- **[merchantkit](https://github.com/benjaminmayo/merchantkit)** - A modern In-App Purchases management framework for iOS.
- **[appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk)** - The Swift SDK to work with the App Store Connect API from Apple.
- **[Siren](https://github.com/ArtSabintsev/Siren)** - Notify users when a new version of your app is available and prompt them to upgrade.

*[↑ Back to top](#contents)*

## 🏗️ Architecture Patterns

- **[swift-composable-architecture](https://github.com/pointfreeco/swift-composable-architecture)** - A library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind.
- **[ReSwift](https://github.com/ReSwift/ReSwift)** - Unidirectional Data Flow in Swift - Inspired by Redux.
- **[ReactorKit](https://github.com/ReactorKit/ReactorKit)** - A library for reactive and unidirectional Swift applications.
- **[clean-architecture-swiftui](https://github.com/nalexn/clean-architecture-swiftui)** - SwiftUI sample app using Clean Architecture. Examples of working with SwiftData persistence, networking, dependency injection, unit testing, and more.
- **[ModernCleanArchitectureSwiftUI](https://github.com/sergdort/ModernCleanArchitectureSwiftUI)** - Example of Modern Domain Driven modularisation of iOS apps.
- **[XCoordinator](https://github.com/QuickBirdEng/XCoordinator)** - Powerful navigation library for iOS based on the coordinator pattern.
- **[ios-architecture](https://github.com/tailec/ios-architecture)** - A collection of iOS architectures - MVC, MVVM, MVVM+RxSwift, VIPER, RIBs and many others.
- **[CleanStore](https://github.com/Clean-Swift/CleanStore)** - A sample iOS app built using the Clean Swift architecture.
- **[RxFlow](https://github.com/RxSwiftCommunity/RxFlow)** - RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.
- **[SwiftHub](https://github.com/khoren93/SwiftHub)** - GitHub iOS client in RxSwift and MVVM-C clean architecture.
- **[ApplicationCoordinator](https://github.com/AndreyPanov/ApplicationCoordinator)** - Coordinators Essential tutorial.
- **[stinsen](https://github.com/rundfunk47/stinsen)** - Coordinators in SwiftUI. Simple, powerful and elegant.
- **[route-composer](https://github.com/ekazaev/route-composer)** - Protocol oriented, Cocoa UI abstractions based library that helps to handle view controllers composition, navigation and deep linking tasks.
- **[iOSSampleApp](https://github.com/igorkulman/iOSSampleApp)** - Sample iOS app demonstrating Coordinators, Dependency Injection, MVVM, Binding.
- **[ios-mvp-clean-architecture](https://github.com/FortechRomania/ios-mvp-clean-architecture)** - Demo iOS application built to highlight MVP (Model View Presenter) and Clean Architecture concepts.

*[↑ Back to top](#contents)*

## 🥽 AR / VR

- **[Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit)** - A curated list of awesome ARKit projects and resources.
- **[ARTetris](https://github.com/exyte/ARTetris)** - Augmented Reality Tetris made with ARKit and SceneKit.
- **[ARKit-Sampler](https://github.com/shu223/ARKit-Sampler)** - Code examples for ARKit.
- **[ARuler](https://github.com/duzexu/ARuler)** - Measure distance using apple ARKit.
- **[ARShooter](https://github.com/farice/ARShooter)** - A demo Augmented Reality shooter made with ARKit in Swift (iOS 11).
- **[Fisheye](https://github.com/hanton/Fisheye)** - iOS 360 panorama video player with Metal rendering support.

*[↑ Back to top](#contents)*

## 🔊 Audio

- **[AudioKit](https://github.com/AudioKit/AudioKit)** - Audio synthesis, processing, & analysis platform for iOS, macOS and tvOS.
- **[SwiftySound](https://github.com/adamcichy/SwiftySound)** - SwiftySound is a simple library that lets you play sounds with a single line of code.
- **[FDWaveformView](https://github.com/fulldecent/FDWaveformView)** - Reads an audio file and displays the waveform.
- **[DSWaveformImage](https://github.com/dmrschmidt/DSWaveformImage)** - Generate waveform images from audio files on iOS, macOS & visionOS in Swift. Native SwiftUI & UIKit views.
- **[FluidAudio](https://github.com/FluidInference/FluidAudio)** - Frontier CoreML audio models in your apps - text-to-speech, speech-to-text, voice activity detection, and speaker diarization.
- **[WhisperKit](https://github.com/argmaxinc/WhisperKit)** - On-device Speech Recognition for Apple Silicon.

*[↑ Back to top](#contents)*

## 🔐 Authentication / Security

- **[KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess)** - Simple Swift wrapper for Keychain that works on iOS, watchOS, tvOS and macOS.
- **[keychain-swift](https://github.com/evgenyneu/keychain-swift)** - Helper functions for saving text in Keychain securely for iOS, OS X, tvOS and watchOS.
- **[Locksmith](https://github.com/matthewpalmer/Locksmith)** - A powerful, protocol-oriented library for working with the keychain in Swift.
- **[SwiftKeychainWrapper](https://github.com/jrendel/SwiftKeychainWrapper)** - A simple wrapper for the iOS Keychain to allow you to use it in a similar fashion to User Defaults.
- **[OAuthSwift](https://github.com/OAuthSwift/OAuthSwift)** - Swift based OAuth library for iOS.
- **[OAuth2](https://github.com/p2/OAuth2)** - OAuth2 framework for macOS and iOS, written in Swift.
- **[facebook-ios-sdk](https://github.com/facebook/facebook-ios-sdk)** - Used to integrate the Facebook Platform with your iOS & tvOS apps.
- **[IOSSecuritySuite](https://github.com/securing/IOSSecuritySuite)** - iOS platform security & anti-tampering Swift library.
- **[SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA)** - RSA public/private key encryption in Swift.
- **[Authenticator](https://github.com/mattrubin/Authenticator)** - Two-Factor Authentication Client for iOS.
- **[ios-application](https://github.com/raivo-otp/ios-application)** - A native, lightweight and secure one-time-password (OTP) client built for iOS; Raivo OTP!.
- **[passforios](https://github.com/mssun/passforios)** - Pass for iOS - an iOS client compatible with Pass command line application.

*[↑ Back to top](#contents)*

## 💾 Caching

- **[Cache](https://github.com/hyperoslo/Cache)** - Nothing but Cache.
- **[HanekeSwift](https://github.com/Haneke/HanekeSwift)** - A lightweight generic cache for iOS written in Swift with extra love for images.
- **[AwesomeCache](https://github.com/aschuch/AwesomeCache)** - Delightful on-disk cache (written in Swift).

*[↑ Back to top](#contents)*

## 📅 Calendar / Date

- **[JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar)** - The Unofficial Apple iOS Swift Calendar View. Swift calendar Library. iOS calendar Control. 100% Customizable.
- **[SwiftDate](https://github.com/malcommac/SwiftDate)** - Toolkit to parse, validate, manipulate, compare and display dates, time & timezones in Swift.
- **[CVCalendar](https://github.com/CVCalendar/CVCalendar)** - A custom visual calendar for iOS 8+ written in Swift (>= 4.0).
- **[CalendarKit](https://github.com/richardtop/CalendarKit)** - Calendar for Apple platforms in Swift.
- **[Koyomi](https://github.com/shoheiyokoyama/Koyomi)** - Simple customizable calendar component in Swift.
- **[Timepiece](https://github.com/naoty/Timepiece)** - Intuitive date handling in Swift.
- **[time](https://github.com/davedelong/time)** - Robust and type-safe date and time calculations for Swift.
- **[DateHelper](https://github.com/melvitax/DateHelper)** - A Swift Date extension helper.
- **[SwiftMoment](https://github.com/akosma/SwiftMoment)** - A time and calendar manipulation library for iOS 9+, macOS 10.11+, tvOS 9+, watchOS 2+ written in Swift 4.
- **[Time](https://github.com/dreymonde/Time)** - Type-safe time calculations in Swift.

*[↑ Back to top](#contents)*

## 📊 Charts / Graphs

- **[ChartView](https://github.com/AppPear/ChartView)** - ChartView made in SwiftUI.
- **[ScrollableGraphView](https://github.com/philackm/ScrollableGraphView)** - An adaptive scrollable graph view for iOS to visualise simple discrete datasets. Written in Swift.
- **[AAChartKit-Swift](https://github.com/AAChartModel/AAChartKit-Swift)** - An elegant modern declarative data visualization chart framework for iOS, iPadOS and macOS.
- **[SwiftCharts](https://github.com/ivnsch/SwiftCharts)** - Easy to use and highly customizable charts library for iOS.
- **[Swift-Charts-Examples](https://github.com/jordibruin/Swift-Charts-Examples)** - An overview of the different types of charts you can make with Swift Charts.
- **[SwiftUICharts](https://github.com/mecid/SwiftUICharts)** - A simple line and bar charting library that supports accessibility written using SwiftUI.
- **[SwiftUICharts](https://github.com/willdale/SwiftUICharts)** - A charts / plotting library for SwiftUI. Works on macOS, iOS, watchOS, and tvOS.
- **[SwiftChart](https://github.com/gpbl/SwiftChart)** - Line and area chart library for iOS.
- **[PNChart-Swift](https://github.com/kevinzhow/PNChart-Swift)** - A simple and beautiful chart lib used in Piner and CoinsMan for iOS.
- **[Graphs](https://github.com/recruit-mtl/Graphs)** - Light weight charts view generator for iOS. Written in Swift.
-**[KSChart](https://github.com/sevtin/KSChart)** - k line chart with MA/EMA/MACD/KDJ/BOLL/RSI/WR/AVG indicators. Swift5, 60FPS stable.
- **[Cosmos](https://github.com/evgenyneu/Cosmos)** - A star rating control for iOS/tvOS written in Swift.

*[↑ Back to top](#contents)*

## 💬 Chat / Messaging

- ****[MessageKit](https://github.com/MessageKit/MessageKit)**** - A community-driven replacement for JSQMessagesViewController
- **[Chatto](https://github.com/badoo/Chatto)** - A lightweight framework to build chat applications, made in Swift.
- **[NMessenger](https://github.com/eBay/NMessenger)** - A fast, lightweight messenger component built on AsyncDisplaykit and written in Swift.
- **[Chat](https://github.com/exyte/Chat)** - A SwiftUI Chat UI framework with fully customizable message cells and a built-in media picker.
- **[MessageViewController](https://github.com/GitHawkApp/MessageViewController)** - A SlackTextViewController replacement written in Swift for the iPhone X.
- **[MessengerKit](https://github.com/steve228uk/MessengerKit)** - A UI framework for building messenger interfaces on iOS.
- **[TSWeChat](https://github.com/hilen/TSWeChat)** - A WeChat alternative. Written in Swift 5.
- **[InputBarAccessoryView](https://github.com/nathantannar4/InputBarAccessoryView)** - A simple and easily customizable InputAccessoryView for making powerful input bars with autocomplete and attachments.
- **[ChatLayout](https://github.com/ekazaev/ChatLayout)** - ChatLayout is an alternative solution to MessageKit. It uses custom UICollectionViewLayout.

*[↑ Back to top](#contents)*

## ⌨️ CLI / Command Line

- **[swift-argument-parser](https://github.com/apple/swift-argument-parser)** - Straightforward, type-safe argument parsing for Swift.
- **[Commander](https://github.com/kylef/Commander)** - Compose beautiful command line interfaces in Swift.
- **[SwiftCLI](https://github.com/jakeheis/SwiftCLI)** - A powerful framework for developing CLIs in Swift.
- **[Swiftline](https://github.com/nsomar/Swiftline)** - Swiftline is a set of tools to help you create command line applications.
- **[Guaka](https://github.com/nsomar/Guaka)** - The smartest and most beautiful (POSIX compliant) Command line framework for Swift.
- **[CommandLine](https://github.com/jatoben/CommandLine)** - A pure Swift library for creating command-line interfaces.
- **[Rainbow](https://github.com/onevcat/Rainbow)** - Delightful console output for Swift developers.
- **[SwiftShell](https://github.com/kareman/SwiftShell)** - A Swift framework for shell scripting.
- **[ShellOut](https://github.com/JohnSundell/ShellOut)** - Easily run shell commands from a Swift script or command line tool.
- **[swift-sh](https://github.com/mxcl/swift-sh)** - Easily script with third-party Swift dependencies.

*[↑ Back to top](#contents)*

## ✨ Code Quality

- **[SwiftLint](https://github.com/realm/SwiftLint)** - A tool to enforce Swift style and conventions.
- **[SwiftFormat](https://github.com/nicklockwood/SwiftFormat)** - A command-line tool and Xcode Extension for formatting Swift code.
- **[swift-format](https://github.com/swiftlang/swift-format)** - Formatting technology for Swift source code.
- **[periphery](https://github.com/peripheryapp/periphery)** - A tool to identify unused code in Swift projects.
- **[FengNiao](https://github.com/onevcat/FengNiao)** - A command line tool for cleaning unused resources in Xcode.
- **[Pecker](https://github.com/woshiccm/Pecker)** - CodePecker is a tool to detect unused Swift code.
- **[Swimat](https://github.com/Jintin/Swimat)** - An Xcode formatter plug-in to format your swift code.
- **[SwiftRewriter](https://github.com/inamiy/SwiftRewriter)** - Swift code formatter using SwiftSyntax.
- **[swiftshield](https://github.com/rockbruno/swiftshield)** - Swift Obfuscator that protects iOS apps against reverse engineering attacks.

*[↑ Back to top](#contents)*

## ⚡ Concurrency / Async

- **[PromiseKit](https://github.com/mxcl/PromiseKit)** - Promises for Swift & ObjC.
- **[swift-async-algorithms](https://github.com/apple/swift-async-algorithms)** - Async Algorithms for Swift.
- **[Async](https://github.com/duemunk/Async)** - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch.
- **[Hydra](https://github.com/malcommac/Hydra)** - Lightweight full-featured Promises, Async & Await Library in Swift.
- **[BrightFutures](https://github.com/Thomvis/BrightFutures)** - Write great asynchronous code in Swift using futures and promises.
- **[SwiftTask](https://github.com/ReactKit/SwiftTask)** - Promise + progress + pause + cancel + retry for Swift.
- **[Then](https://github.com/freshOS/Then)** - Tame async code with battle-tested promises.
- **[Schedule](https://github.com/luoxiu/Schedule)** - Schedule timing task in Swift using a fluent API. (A friendly alternative to Timer).
- **[Repeat](https://github.com/malcommac/Repeat)** - Modern Timer in Swift, Debouncer and Throttler (alternative to NSTimer) made with GCD.
- **[SwiftyTimer](https://github.com/radex/SwiftyTimer)** - Swifty API for NSTimer.
- **[Queuer](https://github.com/FabrizioBrancati/Queuer)** - Queuer is a queue manager, built on top of OperationQueue and Dispatch (aka GCD).
- **[Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift)** - Bolts is a collection of low-level libraries designed to make developing mobile apps easier.
- **[SwiftCoroutine](https://github.com/belozierov/SwiftCoroutine)** - Swift coroutines for iOS, macOS and Linux.
- **[Venice](https://github.com/Zewo/Venice)** - Coroutines, structured concurrency and CSP for Swift on macOS and Linux.
- **[ConcurrencyRecipes](https://github.com/mattmassicotte/ConcurrencyRecipes)** - Practical solutions to problems with Swift Concurrency.
- **[Watchdog](https://github.com/wojteklu/Watchdog)** - Class for logging excessive blocking on the main thread.
- **[ProcedureKit](https://github.com/ProcedureKit/ProcedureKit)** - Advanced Operations in Swift.
- **[FutureKit](https://github.com/FutureKit/FutureKit)** - A Swift based Future/Promises Library for iOS and OS X.
- **[AwaitKit](https://github.com/yannickl/AwaitKit)** - The ES8 Async/Await control flow for Swift.
- **[Overdrive](https://github.com/saidsikira/Overdrive)** - Fast async task based Swift framework with focus on type safety, concurrency and multi threading.

*[↑ Back to top](#contents)*

## 🔒 Cryptography

- **[CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift)** - CryptoSwift is a growing collection of standard and secure cryptographic algorithms implemented in Swift.
- **[RNCryptor](https://github.com/RNCryptor/RNCryptor)** - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift.

*[↑ Back to top](#contents)*

## 🧮 Data Structures / Algorithms

- **[swift-algorithm-club](https://github.com/kodecocodes/swift-algorithm-club)** - Algorithms and data structures in Swift, with explanations!.
- **[swift-algorithms](https://github.com/apple/swift-algorithms)** - Commonly used sequence and collection algorithms for Swift.
- **[swift-collections](https://github.com/apple/swift-collections)** - Commonly used data structures for Swift.
- **[bishop-algorithms-swift](https://github.com/waynewbishop/bishop-algorithms-swift)** - Examples of commonly used data structures and algorithms in Swift.
- **[BTree](https://github.com/attaswift/BTree)** - Fast sorted collections for Swift using in-memory B-trees.
- **[LeetCode-Swift](https://github.com/soapyigu/LeetCode-Swift)** - Solutions to LeetCode by Swift.
- **[LeetCode-Solutions-in-Swift](https://github.com/diwu/LeetCode-Solutions-in-Swift)** - LeetCode Solutions in Swift 5.

*[↑ Back to top](#contents)*

## 🗄️ Database

- **[SQLite.swift](https://github.com/stephencelis/SQLite.swift)** - A type-safe, Swift-language layer over SQLite3.
- **[GRDB.swift](https://github.com/groue/GRDB.swift)** - A toolkit for SQLite databases, with a focus on application development.
- **[SQLiteData](https://github.com/pointfreeco/sqlite-data)** - A fast, lightweight replacement for SwiftData, powered by SQL and supporting CloudKit synchronization.
- **[CoreStore](https://github.com/JohnEstropia/CoreStore)** - Unleashing the real power of Core Data with the elegance and safety of Swift.
- **[IceCream](https://github.com/caiyue1993/IceCream)** - Sync Realm Database with CloudKit.
- **[Sync](https://github.com/3lvis/Sync)** - JSON to Core Data and back. Swift Core Data Sync.
- **[SugarRecord](https://github.com/modo-studio/SugarRecord)** - CoreData/Realm sweet wrapper written in Swift.
- **[QueryKit](https://github.com/QueryKit/QueryKit)** - A simple CoreData query language for Swift and Objective-C.
- **[fluent](https://github.com/vapor/fluent)** - Vapor ORM (queries, models, and relations) for NoSQL and SQL databases.
- **[AlecrimCoreData](https://github.com/Alecrim/AlecrimCoreData)** - Core Data made simple.
- **[Graph](https://github.com/CosmicMind/Graph)** - Graph is a semantic database that is used to create data-driven applications.

*[↑ Back to top](#contents)*

## 💉 Dependency Injection

- **[Swinject](https://github.com/Swinject/Swinject)** - Dependency injection framework for Swift with iOS/macOS/Linux.
- **[Factory](https://github.com/hmlongco/Factory)** - A modern approach to Container-Based Dependency Injection for Swift and SwiftUI.
- **[Resolver](https://github.com/hmlongco/Resolver)** - Swift Ultralight Dependency Injection / Service Locator framework.
- **[needle](https://github.com/uber/needle)** - Compile-time safe Swift dependency injection framework.
- **[Cleanse](https://github.com/square/Cleanse)** - Lightweight Swift Dependency Injection Framework.
- **[Dip](https://github.com/AliSoftware/Dip)** - Simple Swift Dependency container. Use protocols to resolve your dependencies and avoid singletons / sharedInstances!.
- **[swift-dependencies](https://github.com/pointfreeco/swift-dependencies)** - A dependency management library inspired by SwiftUI's "environment.".

*[↑ Back to top](#contents)*

## 📖 Documentation

- **[swift-docc](https://github.com/swiftlang/swift-docc)** - Documentation compiler that produces rich API reference documentation and interactive tutorials for your Swift framework or package.
- **[swift-doc](https://github.com/SwiftDocOrg/swift-doc)** - A documentation generator for Swift projects.

*[↑ Back to top](#contents)*

## 🧰 Extensions / Utilities

- **[SwifterSwift](https://github.com/SwifterSwift/SwifterSwift)** - A handy collection of more than 500 native Swift extensions to boost your productivity.
- **[ExSwift](https://github.com/pNre/ExSwift)** - A set of Swift extensions for standard types and classes.
- **[EZSwiftExtensions](https://github.com/Esqarrouth/EZSwiftExtensions)** - How Swift standard types and classes were supposed to work.
- **[Then](https://github.com/devxoul/Then)** - Super sweet syntactic sugar for Swift initializers.
- **[Dollar](https://github.com/ankurp/Dollar)** - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript.
- **[Swiftz](https://github.com/typelift/Swiftz)** - Functional programming in Swift.
- **[swift-overture](https://github.com/pointfreeco/swift-overture)** - A library for function composition.
- **[DeviceKit](https://github.com/devicekit/DeviceKit)** - DeviceKit is a value-type replacement of UIDevice.
- **[Device](https://github.com/Ekhoo/Device)** - Light weight tool for detecting the current device and screen size written in swift.
- **[Result](https://github.com/antitypical/Result)** - Swift type modelling the success/failure of arbitrary operations.
- **[swift-tagged](https://github.com/pointfreeco/swift-tagged)** - A wrapper type for safer, expressive code.
- **[swift-case-paths](https://github.com/pointfreeco/swift-case-paths)** - Case paths extends the key path hierarchy to enum cases.
- **[Runtime](https://github.com/wickwirew/Runtime)** - A Swift Runtime library for viewing type info, and the dynamic getting and setting of properties.
- **[Closures](https://github.com/vhesener/Closures)** - Swifty closures for UIKit and Foundation.
- **[Sugar](https://github.com/hyperoslo/Sugar)** - Something sweet that goes great with your Cocoa.
- **[ObjectiveKit](https://github.com/marmelroy/ObjectiveKit)** - Swift-friendly API for a set of powerful Objective C runtime functions.
- **[BFKit-Swift](https://github.com/FabrizioBrancati/BFKit-Swift)** - BFKit-Swift is a collection of useful classes, structs and extensions to develop Apps faster.
- **[ValidatedPropertyKit](https://github.com/SvenTiigi/ValidatedPropertyKit)** - Easily validate your Properties with Property Wrappers.
- **[Burritos](https://github.com/guillermomuntaner/Burritos)** - A collection of Swift Property Wrappers (formerly "Property Delegates").

*[↑ Back to top](#contents)*

## 📁 File Management

- **[Files](https://github.com/JohnSundell/Files)** - A nicer way to handle files & folders in Swift.
- **[Disk](https://github.com/saoudrizwan/Disk)** - Easily persist structs, images, and data on iOS.
- **[FileKit](https://github.com/nvzqz/FileKit)** - Simple and expressive file management in Swift.
- **[PathKit](https://github.com/kylef/PathKit)** - Effortless path operations in Swift.
- **[Zip](https://github.com/marmelroy/Zip)** - Swift framework for zipping and unzipping files.
- **[ZIPFoundation](https://github.com/weichsel/ZIPFoundation)** - Effortless ZIP Handling in Swift.
- **[FileBrowser](https://github.com/marmelroy/FileBrowser)** - Finder-style iOS file browser written in Swift.
- **[FileProvider](https://github.com/amosavian/FileProvider)** - FileManager replacement for Local, iCloud and Remote (WebDAV/FTP/Dropbox/OneDrive) files.
- **[Path.swift](https://github.com/mxcl/Path.swift)** - Delightful, robust, cross-platform and chainable file-pathing functions.
- **[AppFolder](https://github.com/dreymonde/AppFolder)** - Never use NSSearchPathForDirectoriesInDomains again.
- **[swift-system](https://github.com/apple/swift-system)** - Low-level system calls and types for Swift.

*[↑ Back to top](#contents)*

## 📝 Forms

- **[Eureka](https://github.com/xmartlabs/Eureka)** - Elegant iOS form builder in Swift.
- **[SwiftForms](https://github.com/ortuman/SwiftForms)** - A small and lightweight library written in Swift that allows you to easily create forms.
- **[SwiftyFORM](https://github.com/neoneye/SwiftyFORM)** - iOS framework for creating forms.
- **[Former](https://github.com/ra1028/Former)** - Former is a fully customizable Swift library for easy creating UITableView based form.
- **[Flix](https://github.com/DianQK/Flix)** - iOS reusable form library in Swift.

*[↑ Back to top](#contents)*

## 🎮 Games

- **[FlappySwift](https://github.com/newlinedotco/FlappySwift)** - swift implementation of flappy bird.
- **[swift-2048](https://github.com/austinzheng/swift-2048)** - 2048 for Swift.
- **[ImagineEngine](https://github.com/JohnSundell/ImagineEngine)** - A project to create a blazingly fast Swift game engine that is a joy to use.
- **[RetroRampage](https://github.com/nicklockwood/RetroRampage)** - Tutorial series demonstrating how to build a retro first-person shooter from scratch in Swift.
- **[SaveTheDot](https://github.com/JakeLin/SaveTheDot)** - A game developed using UIViewPropertyAnimator.
- **[SwiftGodot](https://github.com/migueldeicaza/SwiftGodot)** - New Godot bindings for Swift.

*[↑ Back to top](#contents)*

## 🔌 Hardware

- **[BluetoothKit](https://github.com/rhummelmose/BluetoothKit)** - Easily communicate between iOS/MacOS devices using BLE.
- **[RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit)** - iOS & MacOS Bluetooth library for RxSwift.
- **[bluejay](https://github.com/steamclock/bluejay)** - A simple Swift framework for building reliable Bluetooth LE apps.
- **[SwiftLocation](https://github.com/malcommac/SwiftLocation)** - Async/Await CLLocationManager Wrapper for Apple Platforms.
- **[LocationManager](https://github.com/jimmyjose-dev/LocationManager)** - CLLocationManager wrapper in Swift, performs location update, geocoding and reverse geocoding.
- **[PeerKit](https://github.com/jpsim/PeerKit)** - An open-source Swift framework for building event-driven, zero-config Multipeer Connectivity apps.
- **[HeadGazeLib](https://github.com/eBay/HeadGazeLib)** - A library to empower iOS app control through head gaze without a finger touch.
- **[LocoKit](https://github.com/sobri909/LocoKit)** - Location, motion, and activity recording framework for iOS.
- **[SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO)** - A Swift library for hardware projects on Linux/ARM boards with support for GPIOs/SPI/I2C/PWM/UART/1Wire.
- **[HiBeacons](https://github.com/nicktoumpelis/HiBeacons)** - An iBeacons example app for iOS 10, with Apple Watch (watchOS 3.0) support.
- **[BeaconEmitter](https://github.com/lgaches/BeaconEmitter)** - Turn your Mac as an iBeacon.
- **[BLEUnlock](https://github.com/ts1/BLEUnlock)** - Lock/unlock your Mac with your iPhone, Apple Watch, or any other Bluetooth LE devices.
- **[WebRTC-iOS](https://github.com/stasel/WebRTC-iOS)** - A simple native WebRTC demo iOS app using swift.

*[↑ Back to top](#contents)*

## 🖼️ Images

### Image Loading

- **[Kingfisher](https://github.com/onevcat/Kingfisher)** - A lightweight, pure-Swift library for downloading and caching images from the web.
- **[Nuke](https://github.com/kean/Nuke)** - Image loading system.
- **[SDWebImageSwiftUI](https://github.com/SDWebImage/SDWebImageSwiftUI)** - SwiftUI Image loading and Animation framework powered by SDWebImage.
- **[url-image](https://github.com/dmytro-anokhin/url-image)** - AsyncImage before iOS 15. Lightweight, pure SwiftUI Image view.

### Image Picking

- **[ImagePicker](https://github.com/hyperoslo/ImagePicker)** - Reinventing the way ImagePicker works.
- **[YPImagePicker](https://github.com/Yummypets/YPImagePicker)** - Instagram-like image picker & filters for iOS.
- **[DKImagePickerController](https://github.com/zhangao0086/DKImagePickerController)** - Image Picker Controller for iOS written in Swift 4 & 5.
- **[BSImagePicker](https://github.com/mikaoj/BSImagePicker)** - A multiple image picker for iOS.
- **[ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser)** - Wechat-like image picker. Support select photos, videos, gif and livePhoto.
- **[HXPhotoPicker](https://github.com/SilenceLove/HXPhotoPicker)** - Photo/video picker - supports LivePhoto, GIF, 3DTouch preview, editing.
- **[Fusuma](https://github.com/ytakzk/Fusuma)** - Instagram-like photo browser and a camera feature with a few line of code in Swift.
- **[Gallery](https://github.com/hyperoslo/Gallery)** - Your next favorite image and video picker.
- **[ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController)** - A camera view controller with custom image picker and image cropping.
- **[Paparazzo](https://github.com/avito-tech/Paparazzo)** - Custom iOS camera and photo picker with editing capabilities.
- **[photo-editor](https://github.com/bevy/photo-editor)** - Photo editor with a lot of cool features.
- **[Sharaku](https://github.com/makomori/Sharaku)** - Image filtering UI library like Instagram.
- **[WeScan](https://github.com/WeTransferArchive/WeScan)** - Document Scanning Made Easy for iOS.

### Image Processing

- **[GPUImage2](https://github.com/BradLarson/GPUImage2)** - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing.
- **[GPUImage3](https://github.com/BradLarson/GPUImage3)** - GPUImage 3 is a BSD-licensed Swift framework for GPU-accelerated video and image processing using Metal.
- **[Macaw](https://github.com/exyte/Macaw)** - Powerful and easy-to-use vector graphics Swift library with SVG support.
- **[SwiftSVG](https://github.com/mchoe/SwiftSVG)** - A simple, performant, and lightweight SVG parser.
- **[Toucan](https://github.com/gavinbunney/Toucan)** - Fabulous Image Processing in Swift.
- **[BBMetalImage](https://github.com/Silence-GitHub/BBMetalImage)** - A high performance Swift library for GPU-accelerated image/video processing based on Metal.
- **[Mantis](https://github.com/guoyingtao/Mantis)** - An iOS Image cropping library, which mimics the Photo App written in Swift.
- **[PixelKit](https://github.com/heestand-xyz/PixelKit)** - Live Graphics in Swift & Metal.
- **[FlexibleImage](https://github.com/kawoou/FlexibleImage)** - A simple way to play with the image!.
- **[FaceAware](https://github.com/BeauNouvelle/FaceAware)** - An extension that gives UIImageView the ability to focus on faces within an image.
- **[MaLiang](https://github.com/Harley-xk/MaLiang)** - iOS painting and drawing library based on Metal.
- **[EPSignature](https://github.com/ipraba/EPSignature)** - Signature component for iOS in Swift.

### Image Viewing

- **[SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser)** - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift.
- **[Lightbox](https://github.com/hyperoslo/Lightbox)** - A convenient and easy to use image viewer for your iOS app.
- **[PhotoBrowser](https://github.com/JiongXing/PhotoBrowser)** - Elegant photo browser in Swift.
- **[ImageSlideshow](https://github.com/zvonicek/ImageSlideshow)** - Swift image slideshow with circular scrolling, timer and full screen viewer.
- **[ImageViewer.swift](https://github.com/michaelhenry/ImageViewer.swift)** - An easy to use Image Viewer that is inspired by Facebook.

### GIF

- **[Gifu](https://github.com/kaishin/Gifu)** - High-performance animated GIF support for iOS in Swift.
- **[ImageScout](https://github.com/kaishin/ImageScout)** - A Swift implementation of fastimage. Supports PNG, GIF, and JPEG.
- **[SwiftyGif](https://github.com/alexiscreuzot/SwiftyGif)** - High performance GIF engine.
- **[AImage](https://github.com/wangjwchn/AImage)** - An animated gif & apng engine for iOS in Swift.
- **[APNGKit](https://github.com/onevcat/APNGKit)** - High performance and delightful way to play with APNG format in iOS.

### QR Code

- **[EFQRCode](https://github.com/EFPrefix/EFQRCode)** - A better way to operate QRCode in Swift, support iOS, macOS, watchOS, tvOS, and/or visionOS.
- **[QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift)** - Simple QRCode reader in Swift.
- **[QRCode](https://github.com/aschuch/QRCode)** - A QRCode generator written in Swift.
- **[BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner)** - A simple and beautiful barcode scanner.
- **[swiftScan](https://github.com/MxABC/swiftScan)** - A barcode and qr code scanner.

*[↑ Back to top](#contents)*

## 📋 JSON / Parsing

- **[SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)** - The better way to deal with JSON data in Swift.
- **[ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper)** - Simple JSON Object mapping written in Swift.
- **[HandyJSON](https://github.com/alibaba/HandyJSON)** - A handy swift json-object serialization/deserialization library.
- **[KakaJSON](https://github.com/kakaopensource/KakaJSON)** - Fast conversion between JSON and model in Swift.
- **[AnyCodable](https://github.com/Flight-School/AnyCodable)** - Type-erased wrappers for Encodable, Decodable, and Codable values.
- **[Codextended](https://github.com/JohnSundell/Codextended)** - Extensions giving Swift's Codable API type inference super powers.
- **[Argo](https://github.com/thoughtbot/Argo)** - Functional JSON parsing library for Swift.
- **[Runes](https://github.com/thoughtbot/Runes)** - Infix operators for monadic functions in Swift.
- **[Genome](https://github.com/loganwright/Genome)** - A simple, type safe, failure driven mapping library for serializing JSON to models in Swift 3.0.
- **[mapper](https://github.com/lyft/mapper)** - A JSON deserialization library for Swift.
- **[JASON](https://github.com/delba/JASON)** - Fast JSON parsing for Swift.
- **[Marshal](https://github.com/utahiosmac/Marshal)** - Marshaling the typeless wild west of [String: Any].
- **[Himotoki](https://github.com/ikesyo/Himotoki)** - A type-safe JSON decoding library purely written in Swift.
- **[JSONHelper](https://github.com/isair/JSONHelper)** - Convert anything into anything in one operation.
- **[DynamicJSON](https://github.com/saoudrizwan/DynamicJSON)** - Access JSON properties dynamically like JavaScript using Swift 4.2's @dynamicMemberLookup.
- **[SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator)** - macOS app to generate Swift 5 code for models from JSON (with Codeable).
- **[JSONConverter](https://github.com/vvkeep/JSONConverter)** - Powerful JSON-to-model MacOS app, supports multiple development languages.

### XML / HTML

- **[SwiftSoup](https://github.com/scinfu/SwiftSoup)** - SwiftSoup: Pure Swift HTML Parser, with best of DOM, CSS, and jquery.
- **[Kanna](https://github.com/tid-kijyun/Kanna)** - Kanna is an XML/HTML parser for Swift.
- **[SWXMLHash](https://github.com/drmohundro/SWXMLHash)** - Simple XML parsing in Swift.
- **[AEXML](https://github.com/tadija/AEXML)** - Swift minion for simple and lightweight XML parsing.
- **[Fuzi](https://github.com/cezheng/Fuzi)** - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support.
- **[Ji](https://github.com/honghaoz/Ji)** - Ji is an XML/HTML parser for Swift.

### YAML

- **[Yams](https://github.com/jpsim/Yams)** - A Sweet and Swifty YAML parser.

### CSV

- **[SwiftCSV](https://github.com/swiftcsv/SwiftCSV)** - CSV parser for Swift.

### RSS / Feed

- **[FeedKit](https://github.com/nmdias/FeedKit)** - FeedKit is a Swift library for Reading and Generating RSS, Atom, and JSON feeds.

*[↑ Back to top](#contents)*

## ⌨️ Keyboard

- **[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager)** - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
- **[RxKeyboard](https://github.com/RxSwiftCommunity/RxKeyboard)** - Reactive Keyboard in iOS.
- **[KeyboardLayoutGuide](https://github.com/freshOS/KeyboardLayoutGuide)** - KeyboardLayoutGuide, back from when it didn't exist.
- **[Typist](https://github.com/totocaster/Typist)** - Swift UIKit keyboard manager for iOS apps.
- **[KeyboardKit](https://github.com/KeyboardKit/KeyboardKit)** - Create amazing custom iOS keyboards with Swift & SwiftUI.
- **[tasty-imitation-keyboard](https://github.com/archagon/tasty-imitation-keyboard)** - A custom keyboard for iOS8 that serves as a tasty imitation of the default Apple keyboard.

*[↑ Back to top](#contents)*

## 📐 Layout

- **[SnapKit](https://github.com/SnapKit/SnapKit)** - A Swift Autolayout DSL for iOS & OS X.
- **[Cartography](https://github.com/robb/Cartography)** - A declarative Auto Layout DSL for Swift.
- **[TinyConstraints](https://github.com/roberthein/TinyConstraints)** - Nothing but sugar.
- **[Neon](https://github.com/mamaral/Neon)** - A powerful Swift programmatic UI layout framework.
- **[Stevia](https://github.com/freshOS/Stevia)** - Concise Autolayout code.
- **[EasyPeasy](https://github.com/nakiostudio/EasyPeasy)** - Auto Layout made easy.
- **[PinLayout](https://github.com/layoutBox/PinLayout)** - Fast Swift Views layouting without auto layout. No magic, pure code, full control and blazing fast.
- **[FlexLayout](https://github.com/layoutBox/FlexLayout)** - FlexLayout adds a nice Swift interface to the highly optimized facebook/yoga flexbox implementation.
- **[LayoutKit](https://github.com/LinkedInAttic/LayoutKit)** - LayoutKit is a fast view layout library for iOS, macOS, and tvOS.
- **[TangramKit](https://github.com/youngsoft/TangramKit)** - TangramKit is a powerful iOS UI framework implemented by Swift.
- **[SwiftBox](https://github.com/joshaber/SwiftBox)** - Flexbox in Swift, using Facebook's css-layout.
- **[Paralayout](https://github.com/square/Paralayout)** - Paralayout is a set of simple, useful, and straightforward utilities that enable pixel-perfect layout in iOS.
- **[wtfautolayout](https://github.com/johnpatrickmorgan/wtfautolayout)** - The source code for Why The Failure, Auto Layout?.
- **[AutoLayout](https://github.com/johnlui/AutoLayout)** - Auto Layout secrets.

*[↑ Back to top](#contents)*

## 🌍 Localization

- **[Localize-Swift](https://github.com/marmelroy/Localize-Swift)** - Swift friendly localization and i18n with in-app language switching.
- **[BartyCrouch](https://github.com/FlineDev/BartyCrouch)** - Localization/I18n: Incrementally update/translate your Strings files from .swift, .h, .m(m), .storyboard or .xib files.
- **[iOSLocalizationEditor](https://github.com/igorkulman/iOSLocalizationEditor)** - Simple macOS editor app to help you manage iOS and macOS app localizations.
- **[LocalizationKit_iOS](https://github.com/willpowell8/LocalizationKit_iOS)** - Realtime Dynamic localization translation delivery system for iOS and Mac MacOS in Swift.
- **[Laurine](https://github.com/JiriTrecak/Laurine)** - Laurine - Localization code generator written in Swift. Sweet!.

*[↑ Back to top](#contents)*

## 📜 Logging

- **[SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver)** - Convenient & secure logging during development & release in Swift 4 & 5.
- **[swift-log](https://github.com/apple/swift-log)** - A Logging API for Swift.
- **[XCGLogger](https://github.com/DaveWoodCom/XCGLogger)** - A debug log framework for use in Swift projects.
- **[Willow](https://github.com/Nike-Inc/Willow)** - Willow is a powerful, yet lightweight logging library written in Swift.
- **[CleanroomLogger](https://github.com/emaloney/CleanroomLogger)** - CleanroomLogger provides an extensible Swift-based logging API that is simple, lightweight and performant.
- **[Log](https://github.com/delba/Log)** - An extensible logging framework for Swift.
- **[QorumLogs](https://github.com/Esqarrouth/QorumLogs)** - Swift Logging Utility for Xcode & Google Docs.

*[↑ Back to top](#contents)*

## 🤖 Machine Learning / AI

- **[Swift-AI](https://github.com/Swift-AI/Swift-AI)** - The Swift machine learning library.
- **[SwiftOCR](https://github.com/NMAC427/SwiftOCR)** - Fast and simple OCR library written in Swift.
- **[CoreMLHelpers](https://github.com/hollance/CoreMLHelpers)** - Types and functions that make it a little easier to work with Core ML in Swift.
- **[Forge](https://github.com/hollance/Forge)** - A neural network toolkit for Metal.
- **[YOLO-CoreML-MPSNNGraph](https://github.com/hollance/YOLO-CoreML-MPSNNGraph)** - Tiny YOLO for iOS implemented using CoreML but also using the new MPS graph API.
- **[Bender](https://github.com/xmartlabs/Bender)** - Easily craft fast Neural Networks on iOS! Use TensorFlow models. Metal under the hood.
- **[swift-coreml-diffusers](https://github.com/huggingface/swift-coreml-diffusers)** - Swift app demonstrating Core ML Stable Diffusion.
- **[swift-coreml-transformers](https://github.com/huggingface/swift-coreml-transformers)** - Swift Core ML 3 implementations of GPT-2, DistilGPT-2, BERT, and DistilBERT.
- **[swift-transformers](https://github.com/huggingface/swift-transformers)** - Swift Package to implement a transformers-like API in Swift.
- **[mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples)** - Examples using MLX Swift.
- **[swift-apis](https://github.com/tensorflow/swift-apis)** - Swift for TensorFlow Deep Learning Library.
- **[EmojiIntelligence](https://github.com/BilalReffas/EmojiIntelligence)** - Neural Network built in Apple Playground using Swift.
- **[AIToolbox](https://github.com/KevinCoble/AIToolbox)** - A toolbox of AI modules written in Swift: Graphs/Trees, Support Vector Machines, Neural Networks, PCA, K-Means, Genetic Algorithms.
- **[Surge](https://github.com/Jounce/Surge)** - A Swift library that uses the Accelerate framework to provide high-performance functions for matrix math, digital signal processing, and image manipulation.
- **[Algorithm](https://github.com/CosmicMind/Algorithm)** - Algorithm is a library of tools that is used to create intelligent applications.
- **[OpenAI](https://github.com/MacPaw/OpenAI)** - Swift community driven package for OpenAI public API.
- **[OpenAISwift](https://github.com/adamrushy/OpenAISwift)** - This is a wrapper library around the ChatGPT and OpenAI HTTP API.
- **[LLMFarm](https://github.com/guinmoon/LLMFarm)** - llama and other large language models on iOS and MacOS offline using GGML library.
- **[LlamaChat](https://github.com/alexrozanski/LlamaChat)** - Chat with your favourite LLaMA models in a native macOS app.
- **[Sidekick](https://github.com/johnbean393/Sidekick)** - A native macOS app that allows users to chat with a local LLM.

*[↑ Back to top](#contents)*

## 🖥️ macOS Apps

- **[iina](https://github.com/iina/iina)** - The modern video player for macOS.
- **[MonitorControl](https://github.com/MonitorControl/MonitorControl)** - Control your display's brightness & volume on your Mac as if it was a native Apple Display.
- **[Ice](https://github.com/jordanbaird/Ice)** - Powerful menu bar manager for macOS.
- **[CodeEdit](https://github.com/CodeEditApp/CodeEdit)** - CodeEdit App for macOS - Elevate your code editing experience. Open source, free forever.
- **[Mos](https://github.com/Caldis/Mos)** - A lightweight tool used to smooth scrolling and set scroll direction independently for your mouse on macOS.
- **[AeroSpace](https://github.com/nikitabobko/AeroSpace)** - AeroSpace is an i3-like tiling window manager for macOS.
- **[hidden](https://github.com/dwarvesf/hidden)** - An ultra-light MacOS utility that helps hide menu bar icons.
- **[CotEditor](https://github.com/coteditor/CotEditor)** - Lightweight Plain-Text Editor for macOS.
- **[MiaoYan](https://github.com/tw93/MiaoYan)** - Lightweight Markdown app to help you write great sentences.
- **[vimr](https://github.com/qvacua/vimr)** - VimR - Neovim GUI for macOS in Swift.
- **[fsnotes](https://github.com/glushchenko/fsnotes)** - Notes manager for macOS/iOS.
- **[Clipy](https://github.com/Clipy/Clipy)** - Clipboard extension app for macOS.
- **[Gifski](https://github.com/sindresorhus/Gifski)** - Convert videos to high-quality GIFs on your Mac.
- **[XcodesApp](https://github.com/XcodesOrg/XcodesApp)** - The easiest way to install and switch between multiple versions of Xcode - with a mouse click.
- **[MochiDiffusion](https://github.com/MochiDiffusion/MochiDiffusion)** - Run Stable Diffusion on Mac natively.
- **[Loop](https://github.com/MrKai77/Loop)** - Window management made elegant.
- **[WWDC](https://github.com/insidegui/WWDC)** - The unofficial WWDC app for macOS.
- **[ControlRoom](https://github.com/twostraws/ControlRoom)** - A macOS app to control the Xcode Simulator.
- **[MeetingBar](https://github.com/leits/MeetingBar)** - Your meetings at your fingertips in the macOS menu bar.
- **[eqMac](https://github.com/bitgapp/eqMac)** - macOS System-wide Audio Equalizer & Volume Mixer.
- **[noTunes](https://github.com/tombonez/noTunes)** - A simple macOS application that will prevent iTunes or Apple Music from launching.
- **[Lunar](https://github.com/alin23/Lunar)** - Intelligent adaptive brightness for your external monitors.
- **[uPic](https://github.com/gee1k/uPic)** - uPic is a native, powerful, beautiful and simple picture and file upload tool for macOS.
- **[Applite](https://github.com/milanvarady/Applite)** - User-friendly GUI macOS application for Homebrew Casks.
- **[Latest](https://github.com/mangerlahn/Latest)** - A small utility app for macOS that makes sure you know about all the latest updates to the apps you use.
- **[SwiftBar](https://github.com/swiftbar/SwiftBar)** - Powerful macOS menu bar customization tool.
- **[Cork](https://github.com/buresdv/Cork)** - A fast GUI for Homebrew written in SwiftUI.
- **[MarkEdit](https://github.com/MarkEdit-app/MarkEdit)** - Just like TextEdit on Mac but dedicated to Markdown.
- **[Pine](https://github.com/lukakerr/Pine)** - A modern, native macOS markdown editor.
- **[TRex](https://github.com/amebalabs/TRex)** - Copy any text on your screen, stop retyping.
- **[wallpapper](https://github.com/mczachurski/wallpapper)** - Console application for creating dynamic wallpapers for macOS Mojave and newer.
- **[reminders-menubar](https://github.com/DamascenoRafael/reminders-menubar)** - Simple macOS menu bar application to view and interact with reminders.
- **[SpotMenu](https://github.com/kmikiy/SpotMenu)** - Spotify & Apple Music in your macOS menu bar.
- **[phpmon](https://github.com/nicoverbruggen/phpmon)** - Lightweight, native Mac menu bar app that helps you manage multiple PHP installations.
- **[TomatoBar](https://github.com/ivoronin/TomatoBar)** - World's neatest Pomodoro timer for macOS menu bar.
- **[pika](https://github.com/superhighfives/pika)** - An open-source colour picker app for macOS.
- **[FlashSpace](https://github.com/wojciech-kulik/FlashSpace)** - FlashSpace is a blazingly fast virtual workspace manager for macOS.
- **[LocationSimulator](https://github.com/Schlaubischlump/LocationSimulator)** - MacOS application to spoof / fake / mock your iOS device location.
- **[AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer)** - An app that lets you open .car files and browse/extract their images.
- **[OpenSim](https://github.com/luosheng/OpenSim)** - OpenSim is an open source alternative to SimPholders, written in Swift.
- **[MiniSim](https://github.com/okwasniewski/MiniSim)** - MacOS menu bar app for launching iOS and Android emulators.
- **[Countdown](https://github.com/soffes/Countdown)** - Mac screensaver for counting down to a date.
- **[Clock.saver](https://github.com/soffes/Clock.saver)** - Simple clock screensaver written in Swift.
- **[Equinox](https://github.com/rlxone/Equinox)** - Create dynamic wallpapers for macOS.
- **[rem](https://github.com/jasonjmcghee/rem)** - An open source approach to locally record and enable searching everything you view on your Mac.
- **[LunarBar](https://github.com/LunarBar-app/LunarBar)** - A compact lunar calendar for your macOS menu bar.
- **[RsyncMacOS](https://github.com/rsyncMacOS/RsyncMacOS)** - A macOS GUI for rsync.
- **[XcodeCleaner-SwiftUI](https://github.com/waylybaye/XcodeCleaner-SwiftUI)** - Make Xcode Clean Again.
- **[kawa](https://github.com/hatashiro/kawa)** - A macOS input source switcher with user-defined shortcuts.
- **[touch-bar-simulator](https://github.com/sindresorhus/touch-bar-simulator)** - Use the Touch Bar on any Mac.
- **[Fanny](https://github.com/DanielStormApps/Fanny)** - Monitor your Mac's fan speed and CPU/GPU temperature from your Notification Center.
- **[HSTracker](https://github.com/HearthSim/HSTracker)** - A deck tracker and deck manager for Hearthstone on macOS.
- **[YouTube-Music](https://github.com/steve228uk/YouTube-Music)** - A Mac app wrapper for music.youtube.com.
- **[DevToysMac](https://github.com/DevToys-app/DevToysMac)** - DevToys For mac.
- **[AuroraEditor](https://github.com/AuroraEditor/AuroraEditor)** - Aurora Editor is a IDE built by the community, for the community, and written in Swift for the best native performance and feel for macOS.
- **[multi](https://github.com/kofigumbs/multi)** - Create custom, lightweight macOS apps from websites.
- **[later](https://github.com/alyssaxuu/later)** - Save all your Mac apps for later with one click.
- **[ChangeMenuBarColor](https://github.com/igorkulman/ChangeMenuBarColor)** - Simple utility to change macOS Big Sur and Monterey menu bar color.
- **[Plash](https://github.com/sindresorhus/Plash)** - Make any website your Mac desktop wallpaper.
- **[System-Color-Picker](https://github.com/sindresorhus/System-Color-Picker)** - The macOS color picker as an app with more features.
- **[LaunchAtLogin-Legacy](https://github.com/sindresorhus/LaunchAtLogin-Legacy)** - Add "Launch at Login" functionality to your macOS app in seconds.
- **[Actions](https://github.com/sindresorhus/Actions)** - Supercharge your shortcuts.
- **[DockProgress](https://github.com/sindresorhus/DockProgress)** - Show progress in your app's Dock icon.
- **[HotKey](https://github.com/soffes/HotKey)** - Simple global shortcuts in macOS.
- **[DevHub](https://github.com/jaywcjlove/DevHub)** - A feature-rich offline application, is meticulously crafted to support developers in their daily tasks.
- **[copybook-generator](https://github.com/jaywcjlove/copybook-generator)** - "Copybook Generator" is a powerful copybook generation tool.
- **[CodexBar](https://github.com/steipete/CodexBar)** - Show usage stats for OpenAI Codex and Claude Code, without having to login.
- **[port-killer](https://github.com/productdevbook/port-killer)** - A powerful cross-platform port management tool for developers.
- **[FineTune](https://github.com/ronitsingh10/FineTune)** - FineTune, a macOS menu bar app to control volume for each app independently.
- **[VoiceInk](https://github.com/Beingpax/VoiceInk)** - Voice-to-text app for macOS to transcribe what you say to text almost instantly.
- **[osaurus](https://github.com/dinoki-ai/osaurus)** - AI edge infrastructure for macOS. Run local or cloud models, share tools across apps via MCP.
- **[Dayflow](https://github.com/JerryZLiu/Dayflow)** - Generate a timeline of your day, automatically.
- **[aural-player](https://github.com/kartik-venugopal/aural-player)** - An audio file player for macOS, inspired by Winamp.
- **[Sentinel](https://github.com/alienator88/Sentinel)** - Configure Gatekeeper, remove apps from quarantine and self-sign apps.
- **[Cilicon](https://github.com/traderepublic/Cilicon)** - Self-Hosted ephemeral macOS CI on Apple Silicon.
- **[cua](https://github.com/trycua/cua)** - A lightweight CLI and local API server to create, run and manage macOS and Linux virtual machines on Apple Silicon.
- **[finicky](https://github.com/johnste/finicky)** - A macOS app for customizing which browser to start.
- **[MacAssistant](https://github.com/vanshg/MacAssistant)** - Google Assistant for macOS!.
- **[mac2imgur](https://github.com/mileswd/mac2imgur)** - A simple Mac app designed to make uploading images and screenshots to Imgur quick and effortless.
- **[Conferences.digital](https://github.com/zagahr/Conferences.digital)** - Watch the latest and greatest conference videos on your Mac.
- **[Clippy](https://github.com/Cosmo/Clippy)** - Clippy from Microsoft Office is back and runs on macOS! Written in Swift.
- **[SwiftDefaultApps](https://github.com/Lord-Kamina/SwiftDefaultApps)** - Replacement for RCDefaultApps, written in Swift.
- **[NSWindowStyles](https://github.com/lukakerr/NSWindowStyles)** - A showcase of the many different styles of windows possible with NSWindow on macOS.
- **[ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)** - Next Generation of ShadowsocksX.
- **[PandoraPlayer](https://github.com/ApplikeySolutions/PandoraPlayer)** - PandoraPlayer is a lightweight music player for iOS, based on AudioKit.

*[↑ Back to top](#contents)*

## ⚠️ Malicious

- **[Swift-Keylogger](https://github.com/SkrewEverything/Swift-Keylogger)** - Keylogger for mac written in Swift using HID.
- **[WHC_ConfuseSoftware](https://github.com/netyouli/WHC_ConfuseSoftware)** - iOS代码混淆工具，Uniapp代码混淆工具，react-native代码混淆, iOS代码混淆助手，Android代码混淆助手，Uniapp代码混淆助手，过机器审核，辅助过4.3, other审核，android、ios、uniapp、u3d、cocos2dx、flutter、代码翻新(WHC_ConfuseSoftware)是一款运行在MAC OS平台的App、完美支持Objc和Swift、U3D、Flutter、Cocos2dx项目代码的自动翻新(混淆)、支持文件夹名称、文件名、修改资源文件hash值、类名、方法名、属性名、添加混淆函数方法体、添加混淆属性、自动调用生成的混淆方法、字符串混淆加密等...功能强大而稳定。.
  
- **[confuse-9live](https://github.com/outtable/confuse-9live)** - 🔥🔥🔥 专业版iOS混淆工具，马甲工具包、ipa静态分析工具（相似度对比、敏感词检测），提供试用版本，100%过机器审核，解决 AppStore 4.3，2.3.1问题，支持语言 c、c++、objc、dart、swift 并支持各种资源改名，混淆、傻瓜化操作、一键出包，提供良好的UI界面，支持多包管理一包一特征、支持Unity3d、cocos2d全家桶、swiftUI、flutter、虚幻等各种引擎。支持混淆.a/.framework/.xcframework，混淆比例95%，支持dSYM文件混淆和恢复功能，不影响bugly等各种在线崩溃收集，可持续迭代原工程。.

*[↑ Back to top](#contents)*

## 📝 Markdown

- **[swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui)** - Render Markdown text in SwiftUI.
- **[swift-markdown](https://github.com/swiftlang/swift-markdown)** - A Swift package for parsing, building, editing, and analyzing Markdown documents.
- **[Ink](https://github.com/JohnSundell/Ink)** - A fast and flexible Markdown parser written in Swift.
- **[SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown)** - Converts Markdown files and strings into NSAttributedStrings with lots of customisation options.
- **[MarkdownView](https://github.com/keitaoouchi/MarkdownView)** - Markdown View for iOS.
- **[Parma](https://github.com/dasautoooo/Parma)** - A SwiftUI view for displaying Markdown with customizable appearances.

*[↑ Back to top](#contents)*

## ➗ Math

- **[swift-numerics](https://github.com/apple/swift-numerics)** - Advanced mathematical types and functions for Swift.
- **[Euler](https://github.com/mattt/Euler)** - Swift Custom Operators for Mathematical Notation.
- **[Expression](https://github.com/nicklockwood/Expression)** - A cross-platform Swift library for evaluating mathematical expressions at runtime.
- **[DDMathParser](https://github.com/davedelong/DDMathParser)** - String to Number.
- **[SoulverCore](https://github.com/soulverteam/SoulverCore)** - A powerful Swift framework for evaluating natural language math expressions.
- **[Metron](https://github.com/toineheuvelmans/Metron)** - Geometry, simplified.
- **[GEOSwift](https://github.com/GEOSwift/GEOSwift)** - The Swift Geometry Engine.

*[↑ Back to top](#contents)*

## ▶️ Media Player

- **[Player](https://github.com/piemonte/Player)** - Play and stream media in Swift.
- **[mobileplayer-ios](https://github.com/sahin/mobileplayer-ios)** - A powerful and completely customizable media player for iOS.
- **[BMPlayer](https://github.com/BrikerMan/BMPlayer)** - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles.
- **[KSPlayer](https://github.com/kingslay/KSPlayer)** - A video player for iOS, macOS, tvOS, visionOS, based on AVPlayer and FFmpeg, support SwiftUI, subtitles.
- **[HaishinKit.swift](https://github.com/HaishinKit/HaishinKit.swift)** - Camera and Microphone streaming library via RTMP and SRT for iOS, macOS, tvOS and visionOS.
- **[Live](https://github.com/ltebean/Live)** - Demonstrates how to build a live broadcast app (Swift 3).
- **[NextLevel](https://github.com/NextLevel/NextLevel)** - Media Capture in Swift.
- **[SwiftyCam](https://github.com/Awalz/SwiftyCam)** - A Snapchat Inspired iOS Camera Framework written in Swift.
- **[CameraManager](https://github.com/imaginary-cloud/CameraManager)** - Simple Swift class to provide all the configurations you need to create custom camera view in your app.
- **[Lumina](https://github.com/dokun1/Lumina)** - A camera designed in Swift for easily integrating CoreML models.
- **[Aperture](https://github.com/wulkano/Aperture)** - Record the screen on macOS.

*[↑ Back to top](#contents)*

## 🧭 Menu / Navigation

- **[SideMenu](https://github.com/jonkykong/SideMenu)** - Simple side/slide menu control for iOS, no code necessary! Lots of customization.
- **[SlideMenuControllerSwift](https://github.com/dekatotoro/SlideMenuControllerSwift)** - iOS Slide Menu View based on Google+, iQON, Feedly, Ameba iOS app.
- **[ENSwiftSideMenu](https://github.com/evnaz/ENSwiftSideMenu)** - A simple side menu for iOS written in Swift.
- **[Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS)** - Animated side menu with customizable UI.
- **[GuillotineMenu](https://github.com/Yalantis/GuillotineMenu)** - Our Guillotine Menu Transitioning Animation implemented in Swift.
- **[SideMenuController](https://github.com/teodorpatras/SideMenuController)** - A side menu controller written in Swift for iOS.
- **[SwiftSideslipLikeQQ](https://github.com/johnlui/SwiftSideslipLikeQQ)** - 再造 "手机QQ" 侧滑菜单.
- **[FAPanels](https://github.com/fahidattique55/FAPanels)** - FAPanels - Swift.
- **[InteractiveSideMenu](https://github.com/handsomecode/InteractiveSideMenu)** - iOS Interactive Side Menu written in Swift.
- **[circle-menu](https://github.com/Ramotion/circle-menu)** - CircleMenu is a simple, elegant UI menu with a circular layout and material design animations.
- **[PopMenu](https://github.com/CaliCastle/PopMenu)** - A fully customizable popup style menu for iOS.
- **[BTNavigationDropdownMenu](https://github.com/PhamBaTho/BTNavigationDropdownMenu)** - The elegant yet functional dropdown menu appears underneath the navigation bar.
- **[YNDropDownMenu](https://github.com/younatics/YNDropDownMenu)** - Awesome Dropdown menu for iOS with Swift 5.0.

*[↑ Back to top](#contents)*

## 👋 Onboarding

- **[Instructions](https://github.com/ephread/Instructions)** - Create walkthroughs and guided tours (coach marks) in a simple way, with Swift.
- **[WhatsNewKit](https://github.com/SvenTiigi/WhatsNewKit)** - Showcase your awesome new app features.
- **[paper-onboarding](https://github.com/Ramotion/paper-onboarding)** - PaperOnboarding is a material design UI slider. Swift UI library by @Ramotion.
- **[ConcentricOnboarding](https://github.com/exyte/ConcentricOnboarding)** - SwiftUI library for a walkthrough or onboarding flow with tap actions.
- **[SwiftyOnboard](https://github.com/juanpablofernandez/SwiftyOnboard)** - A swifty iOS framework that allows developers to create beautiful onboarding experiences.
- **[WhatsNew](https://github.com/BalestraPatrick/WhatsNew)** - Showcase new features after an app update similar to Pages, Numbers and Keynote.
- **[Gecco](https://github.com/bannzai/Gecco)** - Simply highlight items for your tutorial walkthrough, written in Swift.
- **[AlertOnboarding](https://github.com/PhilippeBoisney/AlertOnboarding)** - A simple and attractive AlertView to onboard your users in your amazing world.
- **[OnboardingKit](https://github.com/danielsaidi/OnboardingKit)** - Create amazing onboarding experiences in SwiftUI.

*[↑ Back to top](#contents)*

## 📱 Open Source iOS Apps

- **[ios-oss](https://github.com/kickstarter/ios-oss)** - Kickstarter for iOS. Bring new ideas to life, anywhere.
- **[firefox-ios](https://github.com/mozilla-mobile/firefox-ios)** - Firefox for iOS.
- **[brave-ios](https://github.com/brave/brave-ios)** - Brave iOS Browser.
- **[WordPress-iOS](https://github.com/wordpress-mobile/WordPress-iOS)** - WordPress for iOS - Official repository.
- **[wikipedia-ios](https://github.com/wikimedia/wikipedia-ios)** - The official Wikipedia iOS app.
- **[IceCubesApp](https://github.com/Dimillian/IceCubesApp)** - A SwiftUI Mastodon client.
- **[MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI)** - SwiftUI & Combine app using MovieDB API. With a custom Flux (Redux) implementation.
- **[RedditOS](https://github.com/Dimillian/RedditOS)** - The product name is Curiosity, a SwiftUI Reddit client for macOS Big Sur.
- **[ACHNBrowserUI](https://github.com/Dimillian/ACHNBrowserUI)** - Animal Crossing New Horizon companion app in SwiftUI.
- **[blink](https://github.com/blinksh/blink)** - Blink Mobile Shell for iOS (Mosh based).
- **[TelegramSwift](https://github.com/overtake/TelegramSwift)** - Source code of Telegram for macos on Swift 5.0.
- **[enchanted](https://github.com/gluonfield/enchanted)** - Enchanted is iOS and macOS app for chatting with private self hosted language models using Ollama.
- **[Swiftfin](https://github.com/jellyfin/Swiftfin)** - Native Jellyfin Client for iOS and tvOS.
- **[Aidoku](https://github.com/Aidoku/Aidoku)** - Free and open source manga reader for iOS and iPadOS.
- **[userscripts](https://github.com/quoid/userscripts)** - An open-source userscript manager for Safari.
- **[GitHawk](https://github.com/GitHawkApp/GitHawk)** - The (second) best iOS app for GitHub.
- **[eidolon](https://github.com/artsy/eidolon)** - The Artsy Auction Kiosk App.
- **[yattee](https://github.com/yattee/yattee)** - Privacy oriented video player for iOS, tvOS and macOS.
- **[iOS](https://github.com/home-assistant/iOS)** - Home Assistant for Apple platforms.
- **[Swiftcord](https://github.com/SwiftcordApp/Swiftcord)** - A fully native Discord client for macOS built 100% in Swift!.
- **[trailer](https://github.com/ptsochantaris/trailer)** - Managing Pull Requests and Issues For GitHub & GitHub Enterprise.
- **[BookPlayer](https://github.com/TortugaPower/BookPlayer)** - Player for your DRM-free audiobooks.
- **[amperfy](https://github.com/BLeeEZ/amperfy)** - Amperfy is an iOS/iPadOS/macOS app to play songs from an Ampache or Subsonic server.
- **[vlc-ios](https://github.com/videolan/vlc-ios)** - VLC for iOS/iPadOS and tvOS official mirror.
- **[wire-ios](https://github.com/wireapp/wire-ios)** - Wire for iOS (iPhone and iPad).
- **[trust-wallet-ios](https://github.com/trustwallet/trust-wallet-ios)** - Trust - Ethereum Wallet and Web3 DApp Browser for iOS.
- **[reddit-swiftui](https://github.com/carson-katri/reddit-swiftui)** - A cross-platform Reddit client built in SwiftUI.
- **[winston](https://github.com/lo-cafe/winston)** - A beautiful and native Reddit client for iOS.
- **[CoronaTracker](https://github.com/mhdhejazi/CoronaTracker)** - Coronavirus tracker app for iOS & macOS with maps & charts.
- **[OpenScanner](https://github.com/pencilresearch/OpenScanner)** - Fast, reliable, and free document scanner app for iPhone.
- **[12306ForMac](https://github.com/fancymax/12306ForMac)** - An unofficial 12306 Client for Mac.
- **[V2ex-Swift](https://github.com/Finb/V2ex-Swift)** - An iOS client written in Swift for V2EX.
- **[Messenger](https://github.com/relatedcode/Messenger)** - Open source alternative communication platform.
- **[Quick-Chat](https://github.com/aslanyanhaik/Quick-Chat)** - Real time chat app written in Swift 5 using Firebase.
- **[HackerNews](https://github.com/amitburst/HackerNews)** - A Hacker News reader iOS app written in Swift.
- **[SwiftHN](https://github.com/Dimillian/SwiftHN)** - A Hacker News reader in Swift.
- **[Tropos](https://github.com/thoughtbot/Tropos)** - Weather and Forecasts for Humans.
- **[SwiftLanguageWeather](https://github.com/JakeLin/SwiftLanguageWeather)** - Swift Language Weather is an iOS weather app developed in Swift 4.
- **[Swift-Radio-Pro](https://github.com/analogcode/Swift-Radio-Pro)** - Professional Radio Station App for iOS!.
- **[Papr](https://github.com/jdisho/Papr)** - An Unsplash app for iOS.
- **[edhita](https://github.com/tnantoka/edhita)** - Fully open source text editor for iOS written in SwiftUI.
- **[youtube-iOS](https://github.com/aslanyanhaik/youtube-iOS)** - youtube iOS app template written in swift 5.
- **[HealthGPT](https://github.com/StanfordBDHG/HealthGPT)** - Query your Apple Health data with natural language.
- **[open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps)** - Collaborative List of Open-Source iOS Apps.
- **[open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps)** - Awesome list of open source applications for macOS.
- **[example-ios-apps](https://github.com/jogendra/example-ios-apps)** - A curated list of Open Source example iOS apps developed in Swift.
- **[Cowabunga](https://github.com/leminlimez/Cowabunga)** - iOS 14.0-15.7.1 & 16.0-16.1.2 MacDirtyCow ToolBox.
- **[focus-ios](https://github.com/mozilla-mobile/focus-ios)** - Firefox Focus (iOS).
- **[Rocket.Chat.iOS](https://github.com/RocketChat/Rocket.Chat.iOS)** - Legacy mobile Rocket.Chat client in Swift for iOS.
- **[U17](https://github.com/spicyShrimp/U17)** - 精仿有妖气漫画(Swift5).
- **[LBXMLYFM-Swift](https://github.com/lb2281075105/LBXMLYFM-Swift)** - Swift5项目仿写喜马拉雅App.
- **[cheetah](https://github.com/leetcode-mafia/cheetah)** - Mac app for crushing tech interviews with AI.

*[↑ Back to top](#contents)*

## 📄 PDF / Documents

- **[FolioReaderKit](https://github.com/FolioReader/FolioReaderKit)** - A Swift ePub reader and parser framework for iOS.
- **[ReadabilityKit](https://github.com/exyte/ReadabilityKit)** - Preview extractor for news, articles and full-texts in Swift.

*[↑ Back to top](#contents)*

## 🔑 Permissions

- **[PermissionsSwiftUI](https://github.com/jevonmao/PermissionsSwiftUI)** - A SwiftUI package to beautifully display and handle permissions.

*[↑ Back to top](#contents)*

## ⏳ Progress / Loading

- **[NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)** - A collection of awesome loading animations.
- **[SkeletonView](https://github.com/Juanpe/SkeletonView)** - An elegant way to show users that something is happening and also prepare them to which contents they are awaiting.
- **[ProgressHUD](https://github.com/relatedcode/ProgressHUD)** - ProgressHUD is a lightweight and easy-to-use HUD for iOS.
- **[PKHUD](https://github.com/pkluz/PKHUD)** - A Swift based reimplementation of the Apple HUD (Volume, Ringer, Rotation,…) for iOS 8.
- **[SwiftSpinner](https://github.com/icanzilb/SwiftSpinner)** - A beautiful activity indicator and modal alert written in Swift.
- **[FillableLoaders](https://github.com/polqf/FillableLoaders)** - Completely customizable progress based loaders drawn using custom CGPaths written in Swift.
- **[UICircularProgressRing](https://github.com/luispadron/UICircularProgressRing)** - A circular progress bar for iOS written in Swift.
- **[MKRingProgressView](https://github.com/maxkonovalov/MKRingProgressView)** - Ring progress view similar to Activity app on Apple Watch.
- **[KDCircularProgress](https://github.com/kaandedeoglu/KDCircularProgress)** - A circular progress view with gradients written in Swift.
- **[KYCircularProgress](https://github.com/kentya6/KYCircularProgress)** - Flexible progress bar written in Swift.
- **[MultiProgressView](https://github.com/mac-gallagher/MultiProgressView)** - An animatable view that depicts multiple progresses over time.
- **[LoadingShimmer](https://github.com/jogendra/LoadingShimmer)** - An easy way to add a shimmering effect to any view with just one line of code.
- **[SwiftUI-Shimmer](https://github.com/markiv/SwiftUI-Shimmer)** - Shimmer is a super-light modifier that adds a shimmering effect to any SwiftUI View.
- **[SkeletonUI](https://github.com/CSolanaM/SkeletonUI)** - Elegant skeleton loading animation in lightweight SwiftUI.
- **[Windless](https://github.com/ParkGwangBeom/Windless)** - Windless makes it easy to implement invisible layout loading view.
- **[GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar)** - A customizable animated gradient loading bar.
- **[HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider)** - A custom reusable circular / progress slider control for iOS application.

*[↑ Back to top](#contents)*

## ⚛️ Reactive Programming

- **[RxSwift](https://github.com/ReactiveX/RxSwift)** - Reactive Programming in Swift.
- **[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)** - Cocoa framework and Obj-C dynamism bindings for ReactiveSwift.
- **[ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)** - Streams of values over time.
- **[OpenCombine](https://github.com/OpenCombine/OpenCombine)** - Open source implementation of Apple's Combine framework for processing values over time.
- **[CombineExt](https://github.com/CombineCommunity/CombineExt)** - CombineExt provides a collection of operators, publishers and utilities for Combine.
- **[Bond](https://github.com/DeclarativeHub/Bond)** - A Swift binding framework.
- **[ReactiveKit](https://github.com/DeclarativeHub/ReactiveKit)** - A Swift Reactive Programming Kit.
- **[RxSwiftExt](https://github.com/RxSwiftCommunity/RxSwiftExt)** - A collection of Rx operators & tools not found in the core RxSwift distribution.
- **[RxCombine](https://github.com/CombineCommunity/RxCombine)** - Bi-directional type bridging between RxSwift and Apple's Combine framework.
- **[ReactKit](https://github.com/ReactKit/ReactKit)** - Swift Reactive Programming.
- **[Observable-Swift](https://github.com/slazyk/Observable-Swift)** - KVO for Swift - Value Observing and Events.
- **[katana-swift](https://github.com/BendingSpoons/katana-swift)** - Swift Apps in a Swoosh! A modern framework for creating iOS apps, inspired by Redux.
- **[RxFeedback.swift](https://github.com/NoTests/RxFeedback.swift)** - The universal system operator and architecture for RxSwift.
- **[Interstellar](https://github.com/JensRavens/Interstellar)** - Simple and lightweight Functional Reactive Coding in Swift for the rest of us.
- **[RxAutomaton](https://github.com/inamiy/RxAutomaton)** - RxSwift + State Machine, inspired by Redux and Elm.

*[↑ Back to top](#contents)*

## 📚 Resources / Learning

- **[awesome-ios](https://github.com/vsouza/awesome-ios)** - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects.
- **[awesome-swift](https://github.com/matteocrippa/awesome-swift)** - A collaborative list of awesome Swift libraries and resources.
- **[SwiftGuide](https://github.com/ipader/SwiftGuide)** - Swift Featured Projects in brain Mapping.
- **[Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift)** - Design Patterns implemented in Swift 5.0.
- **[OOD-Principles-In-Swift](https://github.com/ochococo/OOD-Principles-In-Swift)** - The Principles of OOD (SOLID) based on Uncle Bob articles.
- **[30DaysofSwift](https://github.com/allenwong/30DaysofSwift)** - A self-taught project to learn Swift.
- **[Swift-30-Projects](https://github.com/soapyigu/Swift-30-Projects)** - 30 mini Swift Apps for self-study.
- **[HackingWithSwift](https://github.com/twostraws/HackingWithSwift)** - The project source code for Hacking with iOS.
- **[Unwrap](https://github.com/twostraws/Unwrap)** - Learn Swift interactively on your iPhone.
- **[iOS-Developer-Roadmap](https://github.com/BohdanOrlov/iOS-Developer-Roadmap)** - Roadmap to becoming an iOS developer in 2018.
- **[About-SwiftUI](https://github.com/Juanpe/About-SwiftUI)** - Gathering all info published, both by Apple and by others, about new framework SwiftUI.
- **[awesome-swiftui-libraries](https://github.com/Toni77777/awesome-swiftui-libraries)** - Awesome SwiftUI Libraries.
- **[Awesome-Swift-Playgrounds](https://github.com/uraimo/Awesome-Swift-Playgrounds)** - A List of Awesome Swift Playgrounds.
- **[ios-learning-materials](https://github.com/eleev/ios-learning-materials)** - Curated list of articles, tutorials and repos that may help you dig a little bit deeper into iOS.
- **[Learn-iOS-Swift-by-Examples](https://github.com/Lax/Learn-iOS-Swift-by-Examples)** - 精心收集并分类整理的Swift开发学习资源.
- **[SwiftPamphletApp](https://github.com/ming1016/SwiftPamphletApp)** - 戴铭的小册子，一本活的知识手册。使用 SwiftUI + SwiftData + Swift Concurrency.
- **[awesome-swift-korean-lecture](https://github.com/ClintJang/awesome-swift-korean-lecture)** - 훌륭한 Swift 세션 동영상(강좌), 한글 자막있는 혹은 한국어 강의 정보 링크 모음.
- **[aprenda-swift](https://github.com/CodandoApple/aprenda-swift)** - Uma lista de conteúdos para você aprender Swift.
- **[Swift-Daily-Tips](https://github.com/emreozdil/Swift-Daily-Tips)** - Daily Tips from Swift World.
- **[swift-tips](https://github.com/vincent-pradeilles/swift-tips)** - A collection useful tips for the Swift language.
- **[SwiftEchoes-Tips](https://github.com/Luur/SwiftEchoes-Tips)** - Swift tips and tricks.
- **[swiftui-notes](https://github.com/heckj/swiftui-notes)** - content for Using Combine - notes on learning Combine with UIKit and SwiftUI.
- **[CombineSwiftPlayground](https://github.com/AvdLee/CombineSwiftPlayground)** - A Swift playground explaining the concepts of the new Combine framework.
- **[whats-new-in-swift-4](https://github.com/ole/whats-new-in-swift-4)** - An Xcode playground showcasing the new features in Swift 4.0.
- **[whats-new-in-swift-4-2](https://github.com/ole/whats-new-in-swift-4-2)** - An Xcode playground demonstrating the new features in in Swift 4.2.
- **[whats-new-in-swift-5-0](https://github.com/twostraws/whats-new-in-swift-5-0)** - An Xcode playground that demonstrates the new features introduced in Swift 5.0.
- **[iOS-11-by-Examples](https://github.com/artemnovichkov/iOS-11-by-Examples)** - Examples of new iOS 11 APIs.
- **[Programming-iOS-Book-Examples](https://github.com/mattneub/Programming-iOS-Book-Examples)** - Downloadable code examples for my books, "iOS 14 Programming Fundamentals With Swift" (bk1) and "Programming iOS 14" (bk2).
- **[iOS-8-Swift-Programming-Cookbook](https://github.com/vandadnp/iOS-8-Swift-Programming-Cookbook)** - This is the GitHub repository of O'Reilly's iOS 8 Swift Programming Cookbook.
- **[swift-weekly](https://github.com/vandadnp/swift-weekly)** - Weekly Swift Language Gems, Tips and Tricks.
- **[swift-summary](https://github.com/jakarmy/swift-summary)** - A summary of Apple's Swift language written on Playgrounds.
- **[learn-swift](https://github.com/nettlep/learn-swift)** - Learn Apple's Swift programming language interactively through these playgrounds.
- **[magic](https://github.com/nettlep/magic)** - Scanner for decks of cards with bar codes printed on card edges.
- **[MTSwift-Learning](https://github.com/MartinRGB/MTSwift-Learning)** - Begin to learn swift, try to make some simple project here.
- **[LLVMSwift](https://github.com/llvm-swift/LLVMSwift)** - A Swift wrapper for the LLVM C API (version 11.0).
- **[Cacao](https://github.com/PureSwift/Cacao)** - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux).
- **[Swift-Macros](https://github.com/krzysztofzablocki/Swift-Macros)** - A curated list of awesome Swift Macros.
- **[Developing-iOS-11-Apps-with-Swift](https://github.com/Apollonyan/Developing-iOS-11-Apps-with-Swift)** - Stanford 公开课，Developing iOS 11 Apps with Swift 字幕翻译.
- **[swift-arcade](https://github.com/jrasmusson/swift-arcade)** - Collection of demos from the Swift Arcade YouTube channel.
- **[iowncode](https://github.com/anupamchugh/iowncode)** - A curated collection of iOS, ML, AR resources sprinkled with some UI additions.
- **[swift-ui-animation-components-and-libraries](https://github.com/Ramotion/swift-ui-animation-components-and-libraries)** - Swift UI libraries, iOS components and animations by @Ramotion.
- **[awesome-swift-macos-apps](https://github.com/jaywcjlove/awesome-swift-macos-apps)** - A curated collection of open-source macOS applications built with Swift.
- **[top](https://github.com/app-developers/top)** - Top App Developers - September 2022.
- **[ios-developer-tools](https://github.com/LeoMobileDeveloper/ios-developer-tools)** - Tools that every iOS developer should know.
- **[Axiom](https://github.com/CharlesWiltgen/Axiom)** - Battle-tested Claude Code skills, commands, and references for modern Apple-platform development.
- **[zen](https://github.com/100mango/zen)** - iOS, macOS, Swift, Objective-C thoughts.
- **[functional-swift](https://github.com/objcio/functional-swift)** - Issue repository for the Functional Swift book.
- **[pointfreeco](https://github.com/pointfreeco/pointfreeco)** - The source for <www.pointfree.co>, a video series on advanced programming topics in Swift.
- **[Mu](https://github.com/marciok/Mu)** - It's a Swift playground explaining how to create a tiny programming language named Mu.
- **[VisualProgrammingLanguage](https://github.com/NathanFlurry/VisualProgrammingLanguage)** - Visual programming language written in Swift that assembles to executable Swift code.

*[↑ Back to top](#contents)*

## 🖥️ Server-Side Swift

- **[vapor](https://github.com/vapor/vapor)** - A server-side Swift HTTP web framework.
- **[Perfect](https://github.com/PerfectlySoft/Perfect)** - Server-side Swift. The Perfect core toolset and framework for Swift Developers.
- **[Kitura](https://github.com/Kitura/Kitura)** - A Swift web framework and HTTP server.
- **[hummingbird](https://github.com/hummingbird-project/hummingbird)** - Lightweight, flexible HTTP server framework written in Swift.
- **[swifter](https://github.com/httpswift/swifter)** - Tiny http server engine written in Swift programming language.
- **[Zewo](https://github.com/Zewo/Zewo)** - Lightweight library for web server applications in Swift on macOS and Linux powered by coroutines.
- **[smoke-framework](https://github.com/amzn/smoke-framework)** - A light-weight server-side service framework written in the Swift programming language.
- **[Swifton](https://github.com/sauliusgrigaitis/Swifton)** - A Ruby on Rails inspired Web Framework for Swift that runs on Linux and OS X.
- **[Express](https://github.com/crossroadlabs/Express)** - Swift Express is a simple, yet unopinionated web application server written in Swift.
- **[Taylor](https://github.com/izqui/Taylor)** - A lightweight library for writing HTTP web servers with Swift.
- **[blackfire](https://github.com/elliottminns/blackfire)** - A minimal, fast and unopinionated web framework for Swift.
- **[BlueSocket](https://github.com/Kitura/BlueSocket)** - Socket framework for Swift using the Swift Package Manager.
- **[swift-aws-lambda-runtime](https://github.com/awslabs/swift-aws-lambda-runtime)** - Swift implementation of AWS Lambda Runtime.
- **[TheList](https://github.com/Awesome-Server-Side-Swift/TheList)** - A list of Awesome Server Side Swift 3 projects.

*[↑ Back to top](#contents)*

## 💽 Storage

- **[SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults)** - Modern Swift API for NSUserDefaults.
- **[DefaultsKit](https://github.com/nmdias/DefaultsKit)** - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS.
- **[Zephyr](https://github.com/ArtSabintsev/Zephyr)** - Effortlessly synchronize UserDefaults over iCloud.
- **[Pantry](https://github.com/nickoneill/Pantry)** - The missing light persistence layer for Swift.
- **[Boutique](https://github.com/mergesort/Boutique)** - A magical persistence library (and so much more) for state-driven iOS and Mac apps.

*[↑ Back to top](#contents)*

## 🎨 SwiftUI

- **[SwiftUIX](https://github.com/SwiftUIX/SwiftUIX)** - An exhaustive expansion of the standard SwiftUI library.
- **[swiftui-introspect](https://github.com/siteline/swiftui-introspect)** - Introspect underlying UIKit/AppKit components from SwiftUI.
- **[OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI)** - Open source implementation of Apple's SwiftUI.
- **[SwiftUI](https://github.com/Jinxiansen/SwiftUI)** - SwiftUI Framework Learning and Usage Guide.
- **[SwiftUI](https://github.com/ivanvorobei/SwiftUI)** - Examples projects using SwiftUI released by WWDC2019.
- **[SwiftUI-Tutorials](https://github.com/WillieWangWei/SwiftUI-Tutorials)** - A code example and translation project of SwiftUI.
- **[SwiftUI-Kit](https://github.com/jordansinger/SwiftUI-Kit)** - A SwiftUI system components and interactions demo app.
- **[SwiftWebUI](https://github.com/SwiftWebUI/SwiftWebUI)** - A demo implementation of SwiftUI for the Web.
- **[SwiftUIKit](https://github.com/danielsaidi/SwiftUIKit)** - Extra functionality for Swift & SwiftUI.
- **[SwiftUIBackports](https://github.com/shaps80/SwiftUIBackports)** - A collection of SwiftUI backports for iOS, macOS, tvOS and watchOS.
- **[ViewInspector](https://github.com/nalexn/ViewInspector)** - Runtime introspection and unit testing of SwiftUI views.
- **[swift-navigation](https://github.com/pointfreeco/swift-navigation)** - Bringing simple and powerful navigation tools to all Swift platforms, inspired by SwiftUI.
- **[swiftui-navigation-transitions](https://github.com/davdroman/swiftui-navigation-transitions)** - Pure SwiftUI Navigation transitions.
- **[swiftui-navigation-stack](https://github.com/matteopuc/swiftui-navigation-stack)** - An alternative SwiftUI NavigationView implementing classic stack-based navigation.
- **[swiftui-router](https://github.com/frzi/swiftui-router)** - Path-based routing in SwiftUI.
- **[SwiftTUI](https://github.com/rensbreur/SwiftTUI)** - SwiftUI for terminal applications.
- **[Tokamak](https://github.com/TokamakUI/Tokamak)** - SwiftUI-compatible framework for building browser apps with WebAssembly.
- **[SwiftUI-experiments](https://github.com/mikelikesdesign/SwiftUI-experiments)** - Examples with SwiftUI and other Apple frameworks.
- **[ConfettiSwiftUI](https://github.com/simibac/ConfettiSwiftUI)** - SwiftUI Package for Configurable Confetti Animation.
- **[Popovers](https://github.com/aheze/Popovers)** - A library to present popovers. Simple, modern, and highly customizable.
- **[Setting](https://github.com/aheze/Setting)** - Compose beautiful preference panels.
- **[Prism](https://github.com/aheze/Prism)** - A lightweight 3D renderer for SwiftUI.
- **[SwipeActions](https://github.com/aheze/SwipeActions)** - Add customizable swipe actions to any view.
- **[OpenFind](https://github.com/aheze/OpenFind)** - An app to find text in real life.
- **[WaterfallGrid](https://github.com/paololeonardi/WaterfallGrid)** - A waterfall grid layout view for SwiftUI.
- **[QGrid](https://github.com/Q-Mobile/QGrid)** - QGrid: The missing SwiftUI collection view.
- **[swiftui-grid](https://github.com/spacenation/swiftui-grid)** - SwiftUI Grid layout with custom styles.
- **[ASCollectionView](https://github.com/apptekstudios/ASCollectionView)** - A SwiftUI collection view with support for custom layouts, preloading, and more.
- **[GridView](https://github.com/KyoheiG3/GridView)** - Reusable GridView with excellent performance and customization that can be time table, spreadsheet, paging and more.
- **[Hedwig](https://github.com/onevcat/Hedwig)** - Send email to any SMTP server like a boss, in Swift and cross-platform.
- **[SwiftUIPager](https://github.com/fermoya/SwiftUIPager)** - Native Pager in SwiftUI.
- **[ScalingHeaderScrollView](https://github.com/exyte/ScalingHeaderScrollView)** - A scroll view with a sticky header which shrinks as you scroll. Written with SwiftUI.
- **[BottomSheet](https://github.com/lucaszischka/BottomSheet)** - A sliding Sheet from the bottom of the Screen with 3 States build with SwiftUI.
- **[SlideOverCard](https://github.com/joogps/SlideOverCard)** - A SwiftUI card view, made great for setup interactions.
- **[swiftui-drawer](https://github.com/maustinstar/swiftui-drawer)** - A SwiftUI bottom-up controller, like in the Maps app.
- **[shiny](https://github.com/maustinstar/shiny)** - Shiny uses your gyroscope to simulate lighting and motion effects on colors.
- **[neumorphic](https://github.com/costachung/neumorphic)** - Neumorphic is a SwiftUI utility to build Neumorphism Soft UI.
- **[StepperView](https://github.com/badrinathvm/StepperView)** - SwiftUI iOS component for Step Indications.
- **[WidgetExamples](https://github.com/pawello2222/WidgetExamples)** - A demo project showing different types of Widgets created with SwiftUI and WidgetKit.
- **[Popups](https://github.com/Mijick/Popups)** - Popups, popovers, sheets, alerts, toasts, banners presentation made simple. Written for SwiftUI.
- **[SwiftUI-WeChat](https://github.com/wxxsw/SwiftUI-WeChat)** - Learn how to make WeChat with SwiftUI.
- **[sample-food-truck](https://github.com/apple/sample-food-truck)** - SwiftUI sample code from WWDC22.
- **[skip](https://github.com/skiptools/skip)** - Skip enables the creation of native SwiftUI apps for iOS and Android.
- **[swift-cross-ui](https://github.com/moreSwift/swift-cross-ui)** - A cross-platform declarative UI framework, inspired by SwiftUI.
- **[divkit](https://github.com/divkit/divkit)** - DivKit is an open source Server-Driven UI (SDUI) framework.
- **[OpenSwiftUI](https://github.com/Cosmo/OpenSwiftUI)** - WIP - OpenSwiftUI is an OpenSource implementation of Apple's SwiftUI DSL.
- **[Few.swift](https://github.com/joshaber/Few.swift)** - Views as functions of their state.

*[↑ Back to top](#contents)*

## 📑 Tab Bar

- **[ESTabBarController](https://github.com/eggswift/ESTabBarController)** - ESTabBarController is a Swift model for customize UI, badge and adding animation to tabbar items.
- **[CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController)** - 【中国特色 TabBar】一行代码实现 Lottie 动画TabBar.
- **[Tabman](https://github.com/uias/Tabman)** - A powerful paging view controller with interactive indicator bars.
- **[CircleBar](https://github.com/softhausHQ/CircleBar)** - A fun, easy-to-use tab bar navigation controller for iOS.
- **[SwipeableTabBarController](https://github.com/marcosgriselli/SwipeableTabBarController)** - UITabBarController with swipe interaction between its tabs.
- **[TransitionableTab](https://github.com/ParkGwangBeom/TransitionableTab)** - TransitionableTab makes it easy to animate when switching between tab.

*[↑ Back to top](#contents)*

## 🧪 Testing

- **[Quick](https://github.com/Quick/Quick)** - The Swift (and Objective-C) testing framework.
- **[Nimble](https://github.com/Quick/Nimble)** - A Matcher Framework for Swift and Objective-C.
- **[swift-testing](https://github.com/swiftlang/swift-testing)** - A modern, expressive testing package for Swift.
- **[swift-corelibs-xctest](https://github.com/swiftlang/swift-corelibs-xctest)** - The XCTest Project, A Swift core library for providing unit test support.
- **[swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing)** - Delightful Swift snapshot testing.
- **[Cuckoo](https://github.com/Brightify/Cuckoo)** - Boilerplate-free mocking framework for Swift!.
- **[SwiftyMocky](https://github.com/MakeAWishFoundation/SwiftyMocky)** - Framework for automatic mock generation. Adds a set of handy methods, simplifying testing.
- **[SwiftCheck](https://github.com/typelift/SwiftCheck)** - QuickCheck for Swift.
- **[Mockingjay](https://github.com/kylef/Mockingjay)** - An elegant library for stubbing HTTP requests with ease in Swift.
- **[SwiftMonkey](https://github.com/zalando/SwiftMonkey)** - A framework for doing randomised UI testing of iOS apps.
- **[swift](https://github.com/danger/swift)** - Stop saying "you forgot to …" in code review.
- **[Difference](https://github.com/krzysztofzablocki/Difference)** - Simple way to identify what is different between 2 instances of any type. Must have for TDD.
- **[UI-Testing-Cheat-Sheet](https://github.com/joemasilotti/UI-Testing-Cheat-Sheet)** - How do I test this with UI Testing?.
- **[Kakapo](https://github.com/devlucky/Kakapo)** - Dynamically Mock server behaviors and responses in Swift.
- **[playbook-ios](https://github.com/playbook-ui/playbook-ios)** - A library for isolated developing UI components and automatically taking snapshots of them.
- **[swift-benchmark](https://github.com/google/swift-benchmark)** - A swift library to benchmark code snippets.
- **[Attabench](https://github.com/attaswift/Attabench)** - Microbenchmarking app for Swift with nice log-log plots.
- **[Sleipnir](https://github.com/railsware/Sleipnir)** - BDD-style framework for Swift.
- **[Parsimmon](https://github.com/ayanonagon/Parsimmon)** - Parsimmon is a wee linguistics toolkit for iOS written in Swift.
- **[NSFWDetector](https://github.com/lovoo/NSFWDetector)** - A NSFW (aka porn) detector with CoreML.

*[↑ Back to top](#contents)*

## 🔤 Text / Labels

- **[LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)** - Graceful morphing effects for UILabel written in Swift.
- **[ActiveLabel.swift](https://github.com/optonaut/ActiveLabel.swift)** - UILabel drop-in replacement supporting Hashtags (#), Mentions (@) and URLs (http://).
- **[MarqueeLabel](https://github.com/cbpowell/MarqueeLabel)** - A drop-in replacement for UILabel, which automatically adds a scrolling marquee effect.
- **[BonMot](https://github.com/Rightpoint/BonMot)** - Beautiful, easy attributed strings in Swift.
- **[SwiftRichString](https://github.com/malcommac/SwiftRichString)** - Elegant Attributed String composition in Swift sauce.
- **[SwiftyAttributes](https://github.com/eddiekaiger/SwiftyAttributes)** - A Swifty API for attributed strings.
- **[Atributika](https://github.com/psharanda/Atributika)** - Convert text with HTML tags, links, hashtags, mentions into NSAttributedString. Make them clickable with UILabel drop-in replacement.
- **[Nantes](https://github.com/instacart/Nantes)** - Swift TTTAttributedLabel replacement.
- **[StyledTextKit](https://github.com/GitHawkApp/StyledTextKit)** - Declarative building and fast rendering attributed string library.
- **[GlitchLabel](https://github.com/kciter/GlitchLabel)** - Glitching UILabel for iOS.
- **[CountdownLabel](https://github.com/suzuki-0000/CountdownLabel)** - Simple countdown UILabel with morphing animation, and some useful function.
- **[Splitflap](https://github.com/yannickl/Splitflap)** - A simple split-flap display for your Swift applications.

### TextField

- **[TextFieldEffects](https://github.com/raulriera/TextFieldEffects)** - Custom UITextFields effects inspired by Codrops, built using Swift.
- **[SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField)** - A beautiful and flexible text field control implementation of "Float Label Pattern".
- **[GrowingTextView](https://github.com/KennethTsang/GrowingTextView)** - An UITextView in Swift. Support auto growing, placeholder and length limit.
- **[KMPlaceholderTextView](https://github.com/MoZhouqi/KMPlaceholderTextView)** - A UITextView subclass that adds support for multiline placeholder written in Swift.
- **[RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView)** - A light-weight UITextView subclass that automatically grows and shrinks.
- **[SearchTextField](https://github.com/apasccon/SearchTextField)** - UITextField subclass with autocompletion suggestions list.
- **[TwitterTextEditor](https://github.com/twitter/TwitterTextEditor)** - A standalone, flexible API that provides a full-featured rich text editor for iOS applications.
- **[Runestone](https://github.com/simonbs/Runestone)** - Performant plain text editor for iOS with syntax highlighting, line numbers, invisible characters and much more.
- **[STTextView](https://github.com/krzyzanowskim/STTextView)** - Performant and reusable text view component (TextKit 2), with line numbers and more.
- **[proton](https://github.com/rajdeep/proton)** - Purely native and extensible rich text editor for iOS and macOS Catalyst apps.
- **[RichTextKit](https://github.com/danielsaidi/RichTextKit)** - View and edit rich text in Swift & SwiftUI.
- **[WSTagsField](https://github.com/whitesmith/WSTagsField)** - An iOS text field that represents tags, hashtags, tokens in general.
- **[TagListView](https://github.com/ElaWorkshop/TagListView)** - Simple and highly customizable iOS tag list view, in Swift.

*[↑ Back to top](#contents)*

## 🎭 Transitions / Presentations

- **[ElasticTransition](https://github.com/lkzhao/ElasticTransition)** - A UIKit custom transition that simulates an elastic drag.
- **[Transition](https://github.com/Touchwonders/Transition)** - Easy interactive interruptible custom ViewController transitions.
- **[EasyTransitions](https://github.com/marcosgriselli/EasyTransitions)** - A simple way to create custom interactive UIViewController transitions.
- **[Presentr](https://github.com/IcaliaLabs/Presentr)** - Swift wrapper for custom ViewController presentations on iOS.
- **[Jelly](https://github.com/SebastianBoldt/Jelly)** - Jelly is a library for animated, non-interactive & interactive viewcontroller transitions and presentations.
- **[Presentation](https://github.com/hyperoslo/Presentation)** - Presentation helps you to make tutorials, release notes and animated pages.
- **[TKSubmitTransition](https://github.com/takuoka/TKSubmitTransition)** - Animated UIButton of Loading Animation and Transition Animation.
- **[TransitionButton](https://github.com/AladinWay/TransitionButton)** - UIButton subclass for loading and transition animation.
- **[ImageOpenTransition](https://github.com/mcmatan/ImageOpenTransition)** - Beautiful and precise transitions between ViewControllers images written in Swift.
- **[PinterestSwift](https://github.com/demonnico/PinterestSwift)** - This is a Swift based demo project to show how to make the transition Pinterest liked.
- **[Parade](https://github.com/HelloElephant/Parade)** - Parallax Scroll-Jacking Effects Engine for iOS / tvOS.
- **[SPStorkController](https://github.com/ivanvorobei/SPStorkController)** - Now playing controller from Apple Music, Mail & Podcasts Apple's apps.
- **[SPLarkController](https://github.com/ivanvorobei/SPLarkController)** - Custom transition between controllers. Settings controller for your iOS app.
- **[preview-transition](https://github.com/Ramotion/preview-transition)** - PreviewTransition is a simple preview gallery UI controller with animated transitions.
- **[elongation-preview](https://github.com/Ramotion/elongation-preview)** - ElongationPreview is an elegant UI push-pop style view controller.
- **[FlowingMenu](https://github.com/yannickl/FlowingMenu)** - Interactive view transition to display menus with flowing and bouncing effects in Swift.
- **[JTMaterialTransition](https://github.com/johnvuko/JTMaterialTransition)** - An iOS transition for controllers based on material design.
- **[StarWars.iOS](https://github.com/Yalantis/StarWars.iOS)** - This component implements transition animation to crumble view-controller into tiny pieces.
- **[FlippingNotch](https://github.com/QuickBirdEng/FlippingNotch)** - FlippingNotch - Dribble inspired animation for Pull-To-Refresh.

*[↑ Back to top](#contents)*

## 🎨 UI Components

### Styling / Theming

- **[StyleKit](https://github.com/146BC/StyleKit)** - A powerful & easy to use styling framework written in Swift.
- **[SwiftTheme](https://github.com/wxxsw/SwiftTheme)** - Powerful theme/skin manager for iOS 9+ 主题/换肤, 暗色模式.
- **[NightNight](https://github.com/draveness/NightNight)** - Elegant way to integrate night mode to swift projects.
- **[FluentDarkModeKit](https://github.com/microsoft/FluentDarkModeKit)** - A library for backporting Dark Mode in iOS.

### Alerts / Popups

- **[SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages)** - A very flexible message bar for UIKit and SwiftUI.
- **[SwiftEntryKit](https://github.com/huri000/SwiftEntryKit)** - SwiftEntryKit is a presentation library for iOS. It can be used to easily display overlays within your iOS apps.
- **[SCLAlertView-Swift](https://github.com/vikmeup/SCLAlertView-Swift)** - Beautiful animated Alert View. Written in Swift.
- **[PopupDialog](https://github.com/Orderella/PopupDialog)** - A simple, customizable popup dialog for iOS written in Swift.
- **[NotificationBanner](https://github.com/Daltron/NotificationBanner)** - The easiest way to display highly customizable in app notification banners in iOS.
- **[alerts-and-pickers](https://github.com/dillidon/alerts-and-pickers)** - Advanced usage of UIAlertController and pickers based on it.
- **[BulletinBoard](https://github.com/alexaubry/BulletinBoard)** - General-purpose contextual cards for iOS.
- **[Toast-Swift](https://github.com/scalessec/Toast-Swift)** - A Swift extension that adds toast notifications to the UIView object class.
- **[Toaster](https://github.com/devxoul/Toaster)** - Toast for Swift.
- **[Whisper](https://github.com/hyperoslo/Whisper)** - Whisper is a component that will make the task of display messages and in-app notifications simple.
- **[PMAlertController](https://github.com/pmusolino/PMAlertController)** - PMAlertController is a great and customizable alert that can substitute UIAlertController.
- **[CDAlertView](https://github.com/candostdagdeviren/CDAlertView)** - Highly customizable alertview and alert/notification/success/error/alarm popup written in Swift.
- **[SweetAlert-iOS](https://github.com/codestergit/SweetAlert-iOS)** - Live animated Alert View for iOS written in Swift.
- **[AlertKit](https://github.com/sparrowcode/AlertKit)** - Native alert from Apple Music & Feedback. Contains Done, Heart & Message and other presets.
- **[AlertToast](https://github.com/elai950/AlertToast)** - Create Apple-like alerts & toasts using SwiftUI.
- **[Drops](https://github.com/omaralbeik/Drops)** - A µFramework for showing alerts like the one used when copying from pasteboard.
- **[BRYXBanner](https://github.com/bryx-inc/BRYXBanner)** - A lightweight dropdown notification for iOS 7+, in Swift.
- **[StatusAlert](https://github.com/LowKostKustomz/StatusAlert)** - Display Apple system-like self-hiding status alerts.
- **[JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification)** - Highly customizable & feature rich notifications. SwiftUI compatible.
- **[Dodo](https://github.com/evgenyneu/Dodo)** - A message bar for iOS written in Swift.
- **[JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications)** - An iOS UIView for presenting a minimalistic notification that doesn't block the UI.
- **[SwiftNotice](https://github.com/johnlui/SwiftNotice)** - GUI library for displaying various popups (HUD), written in pure Swift.
- **[Swift-Prompts](https://github.com/GabrielAlva/Swift-Prompts)** - A Swift library to design custom prompts with a great scope of options to choose from.

### Buttons

- **[DOFavoriteButton](https://github.com/okmr-d/DOFavoriteButton)** - Cute Animated Button written in Swift.
- **[fave-button](https://github.com/janselv/fave-button)** - FaveButton is an iOS cute animated like button written in Swift.
- **[LoginCritter](https://github.com/cgoldsby/LoginCritter)** - An animated avatar that responds to text field interactions.
- **[DynamicButton](https://github.com/yannickl/DynamicButton)** - Yet another animated flat buttons in Swift.
- **[LGButton](https://github.com/loregr/LGButton)** - A fully customisable subclass of the native UIControl which allows you to create beautiful buttons.
- **[Floaty](https://github.com/kciter/Floaty)** - Floating Action Button for iOS.
- **[TVButton](https://github.com/marmelroy/TVButton)** - Recreating the cool parallax icons from Apple TV as iOS UIButtons.

### Cards

- **[Cards](https://github.com/PaoloCuscela/Cards)** - Awesome iOS 11 appstore cards in swift 5.
- **[expanding-collection](https://github.com/Ramotion/expanding-collection)** - ExpandingCollection is an animated material design UI card peek/pop controller.
- **[cardslider](https://github.com/Ramotion/cardslider)** - Cardslider is a design UI controller that allows you to swipe through cards with pictures and accompanying descriptions.
- **[CardSlider](https://github.com/saoudrizwan/CardSlider)** - Tinder cards with a twist.
- **[CardsLayout](https://github.com/filletofish/CardsLayout)** - Custom card-designed CollectionView layout.
- **[CardParts](https://github.com/intuit/CardParts)** - A reactive, card-based UI framework built on UIKit for iOS developers.

### CollectionView

- **[CollectionKit](https://github.com/SoySauceLab/CollectionKit)** - Reimagining UICollectionView.
- **[AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout)** - A UICollectionViewLayout subclass that adds custom transitions/animations to the UICollectionView.
- **[BouncyLayout](https://github.com/roberthein/BouncyLayout)** - Make. It. Bounce.
- **[CollectionViewPagingLayout](https://github.com/amirdew/CollectionViewPagingLayout)** - A simple but highly customizable UICollectionViewLayout for UICollectionView.
- **[VegaScroll](https://github.com/ApplikeySolutions/VegaScroll)** - VegaScroll is a lightweight animation flowlayout for UICollectionView.
- **[CollectionViewSlantedLayout](https://github.com/yacir/CollectionViewSlantedLayout)** - A CollectionView Layout displaying a slanted cells.
- **[CenteredCollectionView](https://github.com/BenEmdon/CenteredCollectionView)** - A lightweight UICollectionViewLayout that 'pages' and centers its cells.
- **[gliding-collection](https://github.com/Ramotion/gliding-collection)** - Gliding Collection is a smooth, flowing, customizable decision for a UICollectionView Swift Controller.
- **[SFFocusViewLayout](https://github.com/fdzsergio/SFFocusViewLayout)** - UICollectionViewLayout with focused content.
- **[AlignedCollectionViewFlowLayout](https://github.com/mischa-hildebrand/AlignedCollectionViewFlowLayout)** - A collection view layout that gives you control over the horizontal and vertical alignment of the cells.
- **[VerticalCardSwiper](https://github.com/JoniVR/VerticalCardSwiper)** - A marriage between the Shazam Discover UI and Tinder.
- **[ChainPageCollectionView](https://github.com/jindulys/ChainPageCollectionView)** - A custom View with fancy collectionView animation.
- **[GravitySlider](https://github.com/ApplikeySolutions/GravitySlider)** - GravitySlider is a beautiful alternative to the standard UICollectionView flow layout.
- **[ReplaceAnimation](https://github.com/fruitcoder/ReplaceAnimation)** - Pull-to-refresh animation in UICollectionView with a sticky header flow layout.

### Colors

- **[DynamicColor](https://github.com/yannickl/DynamicColor)** - Yet another extension to manipulate colors easily in Swift and SwiftUI.
- **[Gradients](https://github.com/Gradients/Gradients)** - A curated collection of splendid 180+ gradients made in swift.
- **[Pastel](https://github.com/cruisediary/Pastel)** - Gradient animation effect like Instagram.
- **[UIColor-Hex-Swift](https://github.com/yeahdongcn/UIColor-Hex-Swift)** - Convenience methods for creating color using RGBA hex string.
- **[Color-Picker-for-iOS](https://github.com/hayashi311/Color-Picker-for-iOS)** - Colorful: iOS color picker built with Swift.

### Paging / Page Control

- **[FSPagerView](https://github.com/WenchaoD/FSPagerView)** - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner View, Product Show, Welcome/Guide Pages.
- **[Parchment](https://github.com/rechsteiner/Parchment)** - A paging view with a highly customizable menu.
- **[XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip)** - Android PagerTabStrip for iOS.
- **[Pageboy](https://github.com/uias/Pageboy)** - A simple, highly informative page view controller.
- **[CHIPageControl](https://github.com/ChiliLabs/CHIPageControl)** - A set of cool animated page controls written in Swift to replace boring UIPageControl.
- **[TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator)** - A rubber animation pagecontrol.
- **[JXSegmentedView](https://github.com/pujiaxin33/JXSegmentedView)** - A powerful and easy to use segmented view.
- **[Segmentio](https://github.com/Yalantis/Segmentio)** - Animated top/bottom segmented control written in Swift.
- **[PagingKit](https://github.com/kazuhiro4949/PagingKit)** - PagingKit provides customizable menu UI.
- **[PagingMenuController](https://github.com/kitasuke/PagingMenuController)** - Paging view controller with customizable menu in Swift.
- **[SGPagingView](https://github.com/kingsic/SGPagingView)** - A powerful and easy to use segment view.
- **[SwipeMenuViewController](https://github.com/yysskk/SwipeMenuViewController)** - Swipable tab and menu View and ViewController.
- **[FlexiblePageControl](https://github.com/shima11/FlexiblePageControl)** - A flexible UIPageControl like Instagram.

### Pull to Refresh

- **[PullToRefresh](https://github.com/Yalantis/PullToRefresh)** - This component implements pure pull-to-refresh logic and you can use it for developing your own pull-to-refresh animations.
- **[DGElasticPullToRefresh](https://github.com/gontovnik/DGElasticPullToRefresh)** - Elastic pull to refresh for iOS developed in Swift.
- **[pull-to-refresh](https://github.com/eggswift/pull-to-refresh)** - An easy way to use pull to refresh and infinite scrolling in Swift. Pod 'ESPullToRefresh'.
- **[BreakOutToRefresh](https://github.com/dasdom/BreakOutToRefresh)** - Play BreakOut while loading - A playable pull to refresh view using SpriteKit.

### Segmented Control

- **[BetterSegmentedControl](https://github.com/gmarm/BetterSegmentedControl)** - An easy to use, customizable replacement for UISegmentedControl & UISwitch.
- **[TwicketSegmentedControl](https://github.com/polqf/TwicketSegmentedControl)** - Custom UISegmentedControl replacement for iOS, written in Swift.
- **[SJFluidSegmentedControl](https://github.com/sasojadrovski/SJFluidSegmentedControl)** - A segmented control with custom appearance and interactive animations.

### Sliders

- **[fluid-slider](https://github.com/Ramotion/fluid-slider)** - A slider widget with a popup bubble displaying the precise value selected.
- **[Koloda](https://github.com/Yalantis/Koloda)** - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS.
- **[ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift)** - A simple view for building card like interface inspired by Tinder and Potluck.
- **[Magnetic](https://github.com/efremidze/Magnetic)** - SpriteKit Floating Bubble Picker (inspired by Apple Music).
- **[Cluster](https://github.com/efremidze/Cluster)** - Easy Map Annotation Clustering.

### Switches

- **[paper-switch](https://github.com/Ramotion/paper-switch)** - RAMPaperSwitch is a Swift material design UI module which paints over the parent view when the switch is turned on.
- **[TKSwitcherCollection](https://github.com/TBXark/TKSwitcherCollection)** - An animation switch collection.
- **[AIFlatSwitch](https://github.com/cocoatoucher/AIFlatSwitch)** - Nicely animated flat design switch alternative to UISwitch.

### TableView

- **[SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit)** - Swipeable UITableViewCell/UICollectionViewCell based on the stock Mail.app, implemented in Swift.
- **[DifferenceKit](https://github.com/ra1028/DifferenceKit)** - A fast and flexible O(n) difference algorithm framework for Swift collection.
- **[DeepDiff](https://github.com/onmyway133/DeepDiff)** - Amazingly incredible extraordinary lightning fast diffing in Swift.
- **[Carbon](https://github.com/ra1028/Carbon)** - A declarative library for building component-based user interfaces in UITableView and UICollectionView.
- **[Static](https://github.com/venmo/Static)** - Simple static table views for iOS in Swift.
- **[Reusable](https://github.com/AliSoftware/Reusable)** - A Swift mixin for reusing views easily and in a type-safe way.
- **[Persei](https://github.com/Yalantis/Persei)** - Animated top menu for UITableView / UICollectionView / UIScrollView written in Swift.
- **[DisplaySwitcher](https://github.com/Yalantis/DisplaySwitcher)** - Custom transition between two collection view layouts.
- **[TimelineTableViewCell](https://github.com/kf99916/TimelineTableViewCell)** - Simple timeline view implemented by UITableViewCell.
- **[TDBadgedCell](https://github.com/tmdvs/TDBadgedCell)** - TDBadgedCell is a table view cell class that adds a badge, similar to the badges in Apple's own apps.
- **[ios-swift-collapsible-table-section](https://github.com/jeantimex/ios-swift-collapsible-table-section)** - A simple iOS Swift project demonstrates how to implement collapsible table section.
- **[CascadingTableDelegate](https://github.com/edopelawi/CascadingTableDelegate)** - A no-nonsense way to write cleaner UITableViewDelegate and UITableViewDataSource in Swift.
- **[GLTableCollectionView](https://github.com/giulio92/GLTableCollectionView)** - Netflix and App Store like UITableView with UICollectionView.
- **[LTScrollView](https://github.com/glthello/LTScrollView)** - ScrollView嵌套ScrolloView（UITableView 、UICollectionView）解决方案.
- **[TableViewCellWithAutoLayoutiOS8](https://github.com/smileyborg/TableViewCellWithAutoLayoutiOS8)** - Sample project demonstrating self-sizing table view cells in iOS 8.
- **[YNSearch](https://github.com/younatics/YNSearch)** - Awesome fully customize search view like Pinterest written in Swift 5.0.
- **[Highlighter](https://github.com/younatics/Highlighter)** - Highlight whatever you want!.
- **[Dwifft](https://github.com/jflinter/Dwifft)** - Swift Diff.
- **[Diff.swift](https://github.com/wokalski/Diff.swift)** - The fastest Diff and patch library in Swift.
- **[ParallaxHeader](https://github.com/romansorochak/ParallaxHeader)** - Simple way to add parallax header to UIScrollView/UITableView written in Swift.
- **[ISTimeline](https://github.com/instant-solutions/ISTimeline)** - Simple timeline view written in Swift 3.

### Other UI

- **[Material](https://github.com/CosmicMind/Material)** - A UI/UX framework for creating beautiful applications.
- **[StatefulViewController](https://github.com/aschuch/StatefulViewController)** - Placeholder views based on content, loading, error or empty states.
- **[ComplimentaryGradientView](https://github.com/gkye/ComplimentaryGradientView)** - Create complementary gradients generated from dominant and prominent colors in supplied image.
- **[fluid-interfaces](https://github.com/nathangitter/fluid-interfaces)** - Natural gestures and animations inspired by Apple's WWDC18 talk "Designing Fluid Interfaces".
- **[ClassicKit](https://github.com/Baddaboo/ClassicKit)** - A collection of classic-style UI components for iOS.
- **[MaterialKit](https://github.com/nghialv/MaterialKit)** - Material design components for iOS written in Swift.
- **[GaugeKit](https://github.com/skywinder/GaugeKit)** - Kit for building custom gauges + easy reproducible Apple's style ring gauges.
- **[Gemini](https://github.com/shoheiyokoyama/Gemini)** - Gemini is rich scroll based animation framework for iOS, written in Swift.
- **[MPParallaxView](https://github.com/DroidsOnRoids/MPParallaxView)** - Apple TV Parallax effect in Swift.
- **[navigation-stack](https://github.com/Ramotion/navigation-stack)** - NavigationStack is a stack-modeled UI navigation controller.
- **[reel-search](https://github.com/Ramotion/reel-search)** - RAMReel is a UI controller that allows you to choose options from a list.
- **[adaptive-tab-bar](https://github.com/Ramotion/adaptive-tab-bar)** - AdaptiveController is a 'Progressive Reduction' Swift UI module for adding custom states to Native or Custom iOS UI elements.
- **[LeeGo](https://github.com/wangshengjia/LeeGo)** - Declarative, configurable & highly reusable UI development as making Lego bricks.
- **[Blueprints](https://github.com/zenangst/Blueprints)** - Blueprints - A framework that is meant to make your life easier when working with collection view flow layouts.
- **[Aiolos](https://github.com/IdeasOnCanvas/Aiolos)** - A floating panel for your iOS Apps.
- **[Pulley](https://github.com/52inc/Pulley)** - A library to imitate the iOS 10 Maps UI.
- **[panelkit](https://github.com/louisdh/panelkit)** - A UI framework that enables panels on iOS.
- **[VisualEffectView](https://github.com/efremidze/VisualEffectView)** - Dynamic blur background view with tint color (UIVisualEffectView subclass).
- **[Blurable](https://github.com/FlexMonkey/Blurable)** - Apply a Gaussian Blur to any UIView with Swift Protocol Extensions.
- **[DynamicBlurView](https://github.com/KyoheiG3/DynamicBlurView)** - DynamicBlurView is a dynamic and high performance UIView subclass for Blur.
- **[Popover](https://github.com/corin8823/Popover)** - Popover is a balloon library like Facebook app.
- **[EasyTipView](https://github.com/teodorpatras/EasyTipView)** - Fully customisable tooltip view in Swift for iOS.
- **[SAHistoryNavigationViewController](https://github.com/marty-suzuki/SAHistoryNavigationViewController)** - SAHistoryNavigationViewController realizes iOS task manager like UI in UINavigationController.
- **[ColorMatchTabs](https://github.com/Yalantis/ColorMatchTabs)** - This is a Review posting app that let user find interesting places near them.
- **[PixPic](https://github.com/Yalantis/PixPic)** - PixPic, a Photo Editing App.
- **[Shiny](https://github.com/efremidze/Shiny)** - Iridescent Effect View (inspired by Apple Pay Cash).
- **[Sheeeeeeeeet](https://github.com/danielsaidi/Sheeeeeeeeet)** - Sheeeeeeeeet is a Swift library for creating menus, custom action sheets, context menus etc.
- **[XLActionController](https://github.com/xmartlabs/XLActionController)** - Fully customizable and extensible action sheet controller written in Swift.
- **[ParticlesLoadingView](https://github.com/BalestraPatrick/ParticlesLoadingView)** - A customizable SpriteKit particles animation on the border of a view.
- **[ShadowImageView](https://github.com/olddonkey/ShadowImageView)** - A apple music cover picture shadow style image library.
- **[ContextMenu](https://github.com/GitHawkApp/ContextMenu)** - An iOS context menu UI inspired by Things 3.
- **[RoughSwift](https://github.com/onmyway133/RoughSwift)** - Create hand-drawn, sketchy, comic shape in Swift.
- **[Snowflake](https://github.com/onmyway133/Snowflake)** - SVG in Swift.
- **[PPBadgeView](https://github.com/jkpang/PPBadgeView)** - iOS Custom Badge, Support UIView, UITabBarItem, UIBarButtonItem.
- **[BadgeHub](https://github.com/jogendra/BadgeHub)** - A way to quickly add a notification badge icon to any view.

*[↑ Back to top](#contents)*

## 🎥 Video

- **[lottie-ios](https://github.com/airbnb/lottie-ios)** - An iOS library to natively render After Effects vector animations.
- **[epoxy-ios](https://github.com/airbnb/epoxy-ios)** - Epoxy is a suite of declarative UI APIs for building UIKit applications in Swift.

*[↑ Back to top](#contents)*

## 🌐 Web

- **[gitignore.io](https://github.com/toptal/gitignore.io)** - Create useful .gitignore files for your project.
- **[Publish](https://github.com/JohnSundell/Publish)** - A static site generator for Swift developers.
- **[Ignite](https://github.com/twostraws/Ignite)** - A static site generator for Swift developers.
- **[Plot](https://github.com/JohnSundell/Plot)** - A DSL for writing type-safe HTML, XML and RSS in Swift.
- **[Stencil](https://github.com/stencilproject/Stencil)** - Stencil is a simple and powerful template language for Swift.
- **[WKZombie](https://github.com/mkoehnke/WKZombie)** - WKZombie is a Swift framework for iOS/MacOS to navigate within websites and collect data without the need of User Interface or API.
- **[WKWebViewJavascriptBridge](https://github.com/Lision/WKWebViewJavascriptBridge)** - A Bridge for Sending Messages between Swift and JavaScript in WKWebViews.
- **[Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player)** - Swift library for embedding and controlling YouTube videos in your iOS applications via WKWebView!.
- **[WebShell](https://github.com/djyde/WebShell)** - Bundle web apps to native OS X app.
- **[ios-universal-webview-boilerplate](https://github.com/nabilfreeman/ios-universal-webview-boilerplate)** - Universal Swift-based boilerplate for a web app.

*[↑ Back to top](#contents)*

## 🛠️ Xcode Tools

- **[Sourcery](https://github.com/krzysztofzablocki/Sourcery)** - Meta-programming for Swift, stop writing boilerplate code.
- **[SwiftGen](https://github.com/SwiftGen/SwiftGen)** - The Swift code generator for your assets, storyboards, Localizable.strings, - Get rid of all String-based APIs!.
- **[R.swift](https://github.com/mac-cain13/R.swift)** - Strong typed, autocompleted resources like images, fonts and segues in Swift projects.
- **[XcodeGen](https://github.com/yonaskolb/XcodeGen)** - A Swift command line tool for generating your Xcode project.
- **[tuist](https://github.com/tuist/tuist)** - A virtual platform team for mobile devs who ship.
- **[XcodeProj](https://github.com/tuist/XcodeProj)** - Read, update and write your Xcode projects.
- **[Mint](https://github.com/yonaskolb/Mint)** - A package manager that installs and runs executable Swift packages.
- **[Carthage](https://github.com/Carthage/Carthage)** - A simple, decentralized dependency manager for Cocoa.
- **[swift-package-manager](https://github.com/swiftlang/swift-package-manager)** - The Package Manager for the Swift Programming Language.
- **[swift-syntax](https://github.com/swiftlang/swift-syntax)** - A set of Swift libraries for parsing, inspecting, generating, and transforming Swift source code.
- **[sourcekit-lsp](https://github.com/swiftlang/sourcekit-lsp)** - Language Server Protocol implementation for Swift and C-based languages.
- **[swift-foundation](https://github.com/swiftlang/swift-foundation)** - The Foundation project.
- **[swift-corelibs-foundation](https://github.com/swiftlang/swift-corelibs-foundation)** - The Foundation Project, providing core utilities, internationalization, and OS independence.
- **[BuildTimeAnalyzer-for-Xcode](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)** - Build Time Analyzer for Swift.
- **[XcodeBenchmark](https://github.com/devMEremenko/XcodeBenchmark)** - XcodeBenchmark measures the compilation time of a large codebase on iMac, MacBook, and Mac Pro.
- **[Optimizing-Swift-Build-Times](https://github.com/fastred/Optimizing-Swift-Build-Times)** - Collection of advice on optimizing compile times of Swift projects.
- **[SwiftInfo](https://github.com/rockbruno/SwiftInfo)** - Extract and analyze the evolution of an iOS app's code.
- **[Sitrep](https://github.com/twostraws/Sitrep)** - A source code analyzer for Swift projects.
- **[json2swift](https://github.com/ijoshsmith/json2swift)** - A macOS command line tool that generates excellent Swift data models based on JSON data.
- **[savannakit](https://github.com/louisdh/savannakit)** - A high-performance, protocol oriented, framework for creating native IDEs for iOS and macOS, written in Swift.
- **[source-editor](https://github.com/louisdh/source-editor)** - A native source editor for iOS and macOS, written in Swift.
- **[wwdc-downloader](https://github.com/ohoachuck/wwdc-downloader)** - WWDC 2019 video downloader script written in Swift - no external dependency.
- **[XCLogParser](https://github.com/MobileNativeFoundation/XCLogParser)** - Tool to parse Xcode and xcodebuild logs stored in the xcactivitylog format.
- **[XCMetrics](https://github.com/spotify/XCMetrics)** - XCMetrics is the easiest way to collect Xcode build metrics and improve developer productivity.
- **[xcbeautify](https://github.com/cpisciotta/xcbeautify)** - A little beautifier tool for xcodebuild.
- **[xcodes](https://github.com/XcodesOrg/xcodes)** - The best command-line tool to install and switch between multiple versions of Xcode.
- **[SwiftKit](https://github.com/SvenTiigi/SwiftKit)** - Start your next Open-Source Swift Framework.
- **[SwiftPlate](https://github.com/JohnSundell/SwiftPlate)** - Easily generate cross platform Swift framework projects from the command line.
- **[Natalie](https://github.com/krzyzanowskim/Natalie)** - Natalie - Storyboard Code Generator (for Swift).
- **[SwiftInitializerGenerator](https://github.com/Bouke/SwiftInitializerGenerator)** - Xcode Source Code Extension to Generate Swift Initializers.
- **[Refactorator](https://github.com/johnno1962/Refactorator)** - Xcode Plugin that Refactors Swift & Objective-C.
- **[InAppViewDebugger](https://github.com/indragiek/InAppViewDebugger)** - A UIView debugger (like Reveal or Xcode) that can be embedded in an app for on-device view debugging.
- **[TouchVisualizer](https://github.com/morizotter/TouchVisualizer)** - Lightweight touch visualization library in Swift. A single line of code and visualize your touches!.
- **[Peek](https://github.com/shaps80/Peek)** - All new design. Inspect your iOS application at runtime.
- **[GodEye](https://github.com/zixun/GodEye)** - Automatically display Log, Crash, Network, ANR, Leak, CPU, RAM, FPS, NetFlow, Folder and etc with one line of code based on Swift.
- **[CocoaDebug](https://github.com/CocoaDebug/CocoaDebug)** - iOS Debugging Tool.
- **[Dotzu](https://github.com/remirobert/Dotzu)** - In-App iOS Debugging Tool With Enhanced Logging, Networking Info, Crash reporting And More.
- **[DebugSwift](https://github.com/DebugSwift/DebugSwift)** - A toolkit to make debugging iOS applications easier.
- **[Inject](https://github.com/krzysztofzablocki/Inject)** - Hot Reloading for Swift applications!.
- **[LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker)** - Find retain cycles / memory leaks sooner.
- **[PinpointKit](https://github.com/Lickability/PinpointKit)** - Send better feedback.
- **[Diagnostics](https://github.com/AvdLee/Diagnostics)** - Allow users to easily share Diagnostics with your support team to improve the flow of fixing bugs.
- **[Sizes](https://github.com/marcosgriselli/Sizes)** - View your app on different device and font sizes.
- **[iconizer](https://github.com/raphaelhanneken/iconizer)** - Create Xcode asset catalogs swift and painless.
- **[TestDrive](https://github.com/JohnSundell/TestDrive)** - Quickly try out any Swift pod or framework in a playground.
- **[GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift)** - Shows FPS, CPU and memory usage, device model, app and iOS versions above the status bar.
- **[xcdiff](https://github.com/bloomberg/xcdiff)** - A tool which helps you diff xcodeproj files.
- **[CopilotForXcode](https://github.com/github/CopilotForXcode)** - AI coding assistant for Xcode.
- **[xtool](https://github.com/xtool-org/xtool)** - Cross-platform Xcode replacement. Build and deploy iOS apps with SwiftPM on Linux, Windows, macOS.
- **[AXe](https://github.com/cameroncooke/AXe)** - AXe is a CLI tool for interacting with Simulators using Apple's Private Accessibility APIs.
- **[Peekaboo](https://github.com/steipete/Peekaboo)** - Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots of applications.
- **[InterposeKit](https://github.com/steipete/InterposeKit)** - A modern library to swizzle elegantly in Swift.
- **[ipatool](https://github.com/majd/ipatool)** - Command-line tool that allows searching and downloading app packages (known as ipa files) from the iOS App Store.
- **[DVIA-v2](https://github.com/prateek147/DVIA-v2)** - Damn Vulnerable iOS App (DVIA) is an iOS application that is damn vulnerable for penetration testing.
- **[mac-monitor](https://github.com/Brandon7CC/mac-monitor)** - "The missing ProcMon for macOS": Mac Monitor records Endpoint Security events and displays them graphically.
- **[Crescendo](https://github.com/SuprHackerSteve/Crescendo)** - Crescendo is a swift based, real time event viewer for macOS utilizing Apple's Endpoint Security Framework.
- **[swift-embedded-examples](https://github.com/swiftlang/swift-embedded-examples)** - A collection of example projects using Embedded Swift.
- **[swift-java](https://github.com/swiftlang/swift-java)** - Java interopability support for Swift.
- **[swift-build](https://github.com/swiftlang/swift-build)** - A high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package Manager.
- **[swift-openapi-generator](https://github.com/apple/swift-openapi-generator)** - Generate Swift client and server code from an OpenAPI document.
- **[swift-atomics](https://github.com/apple/swift-atomics)** - Low-level atomic operations for Swift.
- **[containerization](https://github.com/apple/containerization)** - Containerization is a Swift package for running Linux containers on macOS.
- **[container](https://github.com/apple/container)** - A tool for creating and running Linux containers using lightweight virtual machines on a Mac.
- **[PythonKit](https://github.com/pvieito/PythonKit)** - Swift framework to interact with Python.
- **[SwiftKotlin](https://github.com/angelolloqui/SwiftKotlin)** - A tool to convert Swift code to Kotlin.
- **[swift-win32](https://github.com/compnerd/swift-win32)** - A Windows application framework for Swift.
- **[supabase-swift](https://github.com/supabase/supabase-swift)** - A Swift SDK for Supabase.
- **[sentry-cocoa](https://github.com/getsentry/sentry-cocoa)** - The official Sentry SDK for iOS, tvOS, macOS, watchOS, iPadOS and visionOS.
- **[swift-sdk](https://github.com/modelcontextprotocol/swift-sdk)** - The official Swift SDK for Model Context Protocol servers and clients.
- **[soto](https://github.com/soto-project/soto)** - Swift SDK for AWS that works on Linux, macOS and iOS.
- **[swift-sdk](https://github.com/watson-developer-cloud/swift-sdk)** - The Watson Swift SDK enables developers to quickly add Watson Cognitive Computing services to their Swift applications.
- **[line-sdk-ios-swift](https://github.com/line/line-sdk-ios-swift)** - Provides a modern way of implementing LINE APIs.
- **[BitcoinKit](https://github.com/yenom/BitcoinKit)** - Bitcoin protocol toolkit for Swift.
- **[mapbox-navigation-ios](https://github.com/mapbox/mapbox-navigation-ios)** - Turn-by-turn navigation logic and UI in Swift on iOS.
- **[iOS-URL-Schemes](https://github.com/phynet/iOS-URL-Schemes)** - iOS URL list schemes.
- **[StateMachine](https://github.com/Tinder/StateMachine)** - A Kotlin and Swift DSL for finite state machine.
- **[SwiftState](https://github.com/ReactKit/SwiftState)** - Elegant state machine for Swift.
- **[SFSafeSymbols](https://github.com/SFSafeSymbols/SFSafeSymbols)** - Safely access Apple's SF Symbols using static typing.
- **[Iconic](https://github.com/home-assistant/Iconic)** - Auto-generated icon font library for iOS, watchOS and tvOS.
- **[SwiftIconFont](https://github.com/segecey/SwiftIconFont)** - Icons fonts for iOS (Font Awesome 5, Iconic, Ionicon, etc.).
- **[Font-Awesome](https://github.com/FortAwesome/Font-Awesome)** -  The iconic SVG, font, and CSS toolkit.
- **[SwiftIcons](https://github.com/ranesr/SwiftIcons)** - Swift Library for Font Icons.
- **[UIFontComplete](https://github.com/Nirma/UIFontComplete)** - Font management (System & Custom) for iOS and tvOS.
- **[FontBlaster](https://github.com/ArtSabintsev/FontBlaster)** - Programmatically load custom fonts into your iOS, macOS and tvOS app.
- **[Splash](https://github.com/JohnSundell/Splash)** - A fast, lightweight and flexible Swift syntax highlighter for blogs, tools and fun!.
- **[SwiftEventBus](https://github.com/cesarferreira/SwiftEventBus)** - A publish/subscribe EventBus optimized for iOS.
- **[fuse-swift](https://github.com/krisk/fuse-swift)** - A lightweight fuzzy-search library, with zero dependencies.
- **[SwiftValidator](https://github.com/SwiftValidatorCommunity/SwiftValidator)** - A rule-based validation library for Swift.
- **[JSONWebToken.swift](https://github.com/kylef/JSONWebToken.swift)** - Swift implementation of JSON Web Token (JWT).
- **[SwiftTweaks](https://github.com/bryanjclark/SwiftTweaks)** - Tweak your iOS app without recompiling!.
- **[swift-parsing](https://github.com/pointfreeco/swift-parsing)** - A library for turning nebulous data into well-structured data.
- **[SwiftTerm](https://github.com/migueldeicaza/SwiftTerm)** - Xterm/VT100 Terminal emulator in Swift.
- **[C4iOS](https://github.com/C4Labs/C4iOS)** - C4 is an open-source creative coding framework that harnesses the power of native iOS programming.
- **[Format](https://github.com/marmelroy/Format)** - A Swift Formatter Kit.
- **[PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit)** - A Swift framework for parsing, formatting and validating international phone numbers.
- **[Money](https://github.com/Flight-School/Money)** - A precise, type-safe representation of a monetary amount in a given currency.
- **[Money](https://github.com/danthorpe/Money)** - Swift value types for working with money & currency.
- **[SlackKit](https://github.com/pvzig/SlackKit)** - Build Slack apps, in Swift.
- **[Armchair](https://github.com/UrbanApps/Armchair)** - A simple yet powerful App Review Manager for iOS and MacOS in Swift.
- **[Fakery](https://github.com/vadymmarkov/Fakery)** - Swift fake data generator.
- **[RandomKit](https://github.com/nvzqz/RandomKit)** - Random data generation in Swift.
- **[RateLimit](https://github.com/soffes/RateLimit)** - Simple utility for only executing code every so often.
- **[Each](https://github.com/dalu93/Each)** - Elegant interface for Swift apps.
- **[SwiftString](https://github.com/amayne/SwiftString)** - A comprehensive, lightweight string extension for Swift.
- **[SwiftyImage](https://github.com/devxoul/SwiftyImage)** - Generate image resources in Swift.
- **[SwiftSingleton](https://github.com/hpique/SwiftSingleton)** - An exploration of the Singleton pattern in Swift.
- **[EVReflection](https://github.com/evermeer/EVReflection)** - Reflection based (Dictionary, CKRecord, NSManagedObject, Realm, JSON and XML) object mapping.
- **[GraphQL](https://github.com/GraphQLSwift/GraphQL)** - The Swift GraphQL implementation for macOS and Linux.
- **[RxSwiftExamples](https://github.com/DroidsOnRoids/RxSwiftExamples)** - Examples and resources for RxSwift.
- **[RxTodo](https://github.com/devxoul/RxTodo)** - iOS Todo Application using RxSwift and ReactorKit.

*[↑ Back to top](#contents)*
