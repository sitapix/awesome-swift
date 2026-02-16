# Awesome Swift

A curated list of awesome Swift frameworks, libraries, and software.

I didn't want to click every link to check if a project was still alive, so I scripted a cleanup using the GitHub API. Projects that haven't been updated in 2+ years have been removed. This isn't a perfect signal, some stable libraries don't need frequent updates, but the goal is to make every click more likely to lead to a project that still works.

> ⏳ = Not updated in 1-2 years. May be removed in a future cleanup.
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
    - [Alerts / Popups](#alerts--popups)
    - [CollectionView](#collectionview)
    - [Paging / Page Control](#paging--page-control)
    - [Sliders](#sliders)
    - [Switches](#switches)
    - [TableView](#tableview)
    - [Other UI](#other-ui)
  - [🎥 Video](#-video)
  - [🌐 Web](#-web)
  - [🛠️ Xcode Tools](#️-xcode-tools)

## 🌐 API / Networking

- **[Alamofire](https://github.com/Alamofire/Alamofire)** - Elegant HTTP Networking in Swift. (42k ⭐)
- **[Moya](https://github.com/Moya/Moya)** - Network abstraction layer written in Swift. (15k ⭐) ⏳
- **[Starscream](https://github.com/daltoniam/Starscream)** - Websockets in swift for iOS and MacOS. (8.6k ⭐) ⏳
- **[swift-nio](https://github.com/apple/swift-nio)** - Event-driven network application framework for high performance protocol servers & clients, non-blocking. (8.4k ⭐)
- **[Reachability.swift](https://github.com/ashleymills/Reachability.swift)** - Replacement for Apple's Reachability re-written in Swift with closures. (8.0k ⭐) ⏳
- **[Pulse](https://github.com/kean/Pulse)** - Network logger for Apple platforms. (6.9k ⭐)
- **[swift-protobuf](https://github.com/apple/swift-protobuf)** - Plugin and runtime library for using protobuf with Swift. (4.9k ⭐)
- **[Bagel](https://github.com/yagiz/Bagel)** - a little native network debugging tool for iOS. (4.4k ⭐) ⏳
- **[apollo-ios](https://github.com/apollographql/apollo-ios)** - A strongly-typed, caching GraphQL client for iOS, written in Swift. (4.0k ⭐)
- **[netfox](https://github.com/kasketis/netfox)** - A lightweight, one line setup, iOS / MacOS network debugging library!. (3.7k ⭐) ⏳
- **[Tiercel](https://github.com/Danie1s/Tiercel)** - 简单易用、功能丰富的纯 Swift 下载框架. (2.8k ⭐)
- **[grpc-swift](https://github.com/grpc/grpc-swift)** - The Swift language implementation of gRPC. (2.2k ⭐)
- **[CocoaMQTT](https://github.com/emqx/CocoaMQTT)** - MQTT 5.0 client library for iOS and macOS written in Swift. (1.7k ⭐)
- **[Connectivity](https://github.com/rwbutler/Connectivity)** - Makes Internet connectivity detection more robust by detecting Wi-Fi networks without Internet access. (1.7k ⭐) ⏳
- **[RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire)** - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire. (1.6k ⭐) ⏳
- **[Networking](https://github.com/3lvis/Networking)** - Swift HTTP Networking with stubbing and caching support. (1.4k ⭐)
- **[swift-http-types](https://github.com/apple/swift-http-types)** - Version-independent HTTP currency types for Swift. (1.0k ⭐)
- **[protobuf-swift](https://github.com/alexeyxo/protobuf-swift)** - Google ProtocolBuffers for Apple Swift. (942 ⭐) ⏳
- **[Networking](https://github.com/freshOS/Networking)** - Concise networking code leveraging async-await, Decodable & Generics. (889 ⭐)

*[↑ Back to top](#contents)*

## 🧭 App Routing

- **[URLNavigator](https://github.com/devxoul/URLNavigator)** - Elegant URL Routing for Swift. (3.3k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🛒 App Store / In-App Purchases

- **[SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)** - Lightweight In App Purchases Swift framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. (6.7k ⭐) ⏳
- **[purchases-ios](https://github.com/RevenueCat/purchases-ios)** - In-app purchases and subscriptions made easy. Support for iOS, watchOS, tvOS, macOS, and visionOS. (2.9k ⭐)
- **[appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk)** - The Swift SDK to work with the App Store Connect API from Apple. (1.6k ⭐)
- **[merchantkit](https://github.com/benjaminmayo/merchantkit)** - A modern In-App Purchases management framework for iOS. (1.1k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🏗️ Architecture Patterns

- **[swift-composable-architecture](https://github.com/pointfreeco/swift-composable-architecture)** - A library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind. (14k ⭐)
- **[ReSwift](https://github.com/ReSwift/ReSwift)** - Unidirectional Data Flow in Swift - Inspired by Redux. (7.6k ⭐) ⏳
- **[clean-architecture-swiftui](https://github.com/nalexn/clean-architecture-swiftui)** - SwiftUI sample app using Clean Architecture. Examples of working with SwiftData persistence, networking, dependency injection, unit testing, and more. (6.5k ⭐)
- **[ModernCleanArchitectureSwiftUI](https://github.com/sergdort/ModernCleanArchitectureSwiftUI)** - Example of Modern Domain Driven modularisation of iOS apps. (4.1k ⭐) ⏳
- **[SwiftHub](https://github.com/khoren93/SwiftHub)** - GitHub iOS client in RxSwift and MVVM-C clean architecture. (3.1k ⭐)
- **[ReactorKit](https://github.com/ReactorKit/ReactorKit)** - A library for reactive and unidirectional Swift applications. (2.8k ⭐)
- **[XCoordinator](https://github.com/QuickBirdEng/XCoordinator)** - Powerful navigation library for iOS based on the coordinator pattern. (2.4k ⭐)
- **[RxFlow](https://github.com/RxSwiftCommunity/RxFlow)** - RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern. (1.9k ⭐)
- **[stinsen](https://github.com/rundfunk47/stinsen)** - Coordinators in SwiftUI. Simple, powerful and elegant. (960 ⭐) ⏳
- **[route-composer](https://github.com/ekazaev/route-composer)** - Protocol oriented, Cocoa UI abstractions based library that helps to handle view controllers composition, navigation and deep linking tasks. (926 ⭐)
- **[iOSSampleApp](https://github.com/igorkulman/iOSSampleApp)** - Sample iOS app demonstrating Coordinators, Dependency Injection, MVVM, Binding. (902 ⭐)

*[↑ Back to top](#contents)*

## 🥽 AR / VR

- **[Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit)** - A curated list of awesome ARKit projects and resources. (8.0k ⭐) ⏳
- **[Fisheye](https://github.com/hanton/Fisheye)** - iOS 360 panorama video player with Metal rendering support. (2.2k ⭐)
- **[ARuler](https://github.com/duzexu/ARuler)** - Measure distance using apple ARKit. (1.3k ⭐)
- **[ARShooter](https://github.com/farice/ARShooter)** - A demo Augmented Reality shooter made with ARKit in Swift (iOS 11). (810 ⭐)

*[↑ Back to top](#contents)*

## 🔊 Audio

- **[AudioKit](https://github.com/AudioKit/AudioKit)** - Audio synthesis, processing, & analysis platform for iOS, macOS and tvOS. (11k ⭐)
- **[WhisperKit](https://github.com/argmaxinc/WhisperKit)** - On-device Speech Recognition for Apple Silicon. (5.6k ⭐)
- **[FluidAudio](https://github.com/FluidInference/FluidAudio)** - Frontier CoreML audio models in your apps - text-to-speech, speech-to-text, voice activity detection, and speaker diarization. (1.5k ⭐)
- **[FDWaveformView](https://github.com/fulldecent/FDWaveformView)** - Reads an audio file and displays the waveform. (1.3k ⭐)
- **[SwiftySound](https://github.com/adamcichy/SwiftySound)** - SwiftySound is a simple library that lets you play sounds with a single line of code. (1.3k ⭐) ⏳
- **[DSWaveformImage](https://github.com/dmrschmidt/DSWaveformImage)** - Generate waveform images from audio files on iOS, macOS & visionOS in Swift. Native SwiftUI & UIKit views. (1.2k ⭐)

*[↑ Back to top](#contents)*

## 🔐 Authentication / Security

- **[KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess)** - Simple Swift wrapper for Keychain that works on iOS, watchOS, tvOS and macOS. (8.2k ⭐) ⏳
- **[facebook-ios-sdk](https://github.com/facebook/facebook-ios-sdk)** - Used to integrate the Facebook Platform with your iOS & tvOS apps. (8.0k ⭐)
- **[OAuthSwift](https://github.com/OAuthSwift/OAuthSwift)** - Swift based OAuth library for iOS. (3.3k ⭐) ⏳
- **[keychain-swift](https://github.com/evgenyneu/keychain-swift)** - Helper functions for saving text in Keychain securely for iOS, OS X, tvOS and watchOS. (3.0k ⭐) ⏳
- **[Locksmith](https://github.com/matthewpalmer/Locksmith)** - A powerful, protocol-oriented library for working with the keychain in Swift. (2.9k ⭐) ⏳
- **[IOSSecuritySuite](https://github.com/securing/IOSSecuritySuite)** - iOS platform security & anti-tampering Swift library. (2.6k ⭐)
- **[passforios](https://github.com/mssun/passforios)** - Pass for iOS - an iOS client compatible with Pass command line application. (1.6k ⭐)
- **[SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA)** - RSA public/private key encryption in Swift. (1.3k ⭐) ⏳
- **[OAuth2](https://github.com/p2/OAuth2)** - OAuth2 framework for macOS and iOS, written in Swift. (1.2k ⭐) ⏳
- **[ios-application](https://github.com/raivo-otp/ios-application)** - A native, lightweight and secure one-time-password (OTP) client built for iOS; Raivo OTP!. (940 ⭐)
- **[Authenticator](https://github.com/mattrubin/Authenticator)** - Two-Factor Authentication Client for iOS. (867 ⭐)

*[↑ Back to top](#contents)*

## 💾 Caching

- **[Cache](https://github.com/hyperoslo/Cache)** - Nothing but Cache. (3.1k ⭐)

*[↑ Back to top](#contents)*

## 📅 Calendar / Date

- **[JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar)** - The Unofficial Apple iOS Swift Calendar View. Swift calendar Library. iOS calendar Control. 100% Customizable. (7.7k ⭐) ⏳
- **[CalendarKit](https://github.com/richardtop/CalendarKit)** - Calendar for Apple platforms in Swift. (2.7k ⭐)
- **[time](https://github.com/davedelong/time)** - Robust and type-safe date and time calculations for Swift. (2.3k ⭐) ⏳
- **[DateHelper](https://github.com/melvitax/DateHelper)** - A Swift Date extension helper. (1.5k ⭐) ⏳

*[↑ Back to top](#contents)*

## 📊 Charts / Graphs
-**[KSChart](https://github.com/sevtin/KSChart)** - k line chart with MA/EMA/MACD/KDJ/BOLL/RSI/WR/AVG indicators. Swift5, 60FPS stable.
*[↑ Back to top](#contents)*

- **[AAChartKit-Swift](https://github.com/AAChartModel/AAChartKit-Swift)** - An elegant modern declarative data visualization chart framework for iOS, iPadOS and macOS. (2.5k ⭐)
- **[Swift-Charts-Examples](https://github.com/jordibruin/Swift-Charts-Examples)** - An overview of the different types of charts you can make with Swift Charts. (2.4k ⭐)
- **[Cosmos](https://github.com/evgenyneu/Cosmos)** - A star rating control for iOS/tvOS written in Swift. (2.2k ⭐) ⏳
- **[SwiftUICharts](https://github.com/willdale/SwiftUICharts)** - A charts / plotting library for SwiftUI. Works on macOS, iOS, watchOS, and tvOS. (952 ⭐)

## 💬 Chat / Messaging
- ****[MessageKit](https://github.com/MessageKit/MessageKit)**** - A community-driven replacement for JSQMessagesViewController
*[↑ Back to top](#contents)*

- **[Chatto](https://github.com/badoo/Chatto)** - A lightweight framework to build chat applications, made in Swift. (4.5k ⭐)
- **[Chat](https://github.com/exyte/Chat)** - A SwiftUI Chat UI framework with fully customizable message cells and a built-in media picker. (1.7k ⭐)
- **[InputBarAccessoryView](https://github.com/nathantannar4/InputBarAccessoryView)** - A simple and easily customizable InputAccessoryView for making powerful input bars with autocomplete and attachments. (1.3k ⭐)
- **[ChatLayout](https://github.com/ekazaev/ChatLayout)** - ChatLayout is an alternative solution to MessageKit. It uses custom UICollectionViewLayout. (994 ⭐)

## ⌨️ CLI / Command Line

- **[swift-argument-parser](https://github.com/apple/swift-argument-parser)** - Straightforward, type-safe argument parsing for Swift. (3.7k ⭐)
- **[Rainbow](https://github.com/onevcat/Rainbow)** - Delightful console output for Swift developers. (1.9k ⭐)
- **[swift-sh](https://github.com/mxcl/swift-sh)** - Easily script with third-party Swift dependencies. (1.9k ⭐)
- **[SwiftShell](https://github.com/kareman/SwiftShell)** - A Swift framework for shell scripting. (1.1k ⭐)
- **[ShellOut](https://github.com/JohnSundell/ShellOut)** - Easily run shell commands from a Swift script or command line tool. (886 ⭐) ⏳

*[↑ Back to top](#contents)*

## ✨ Code Quality

- **[SwiftLint](https://github.com/realm/SwiftLint)** - A tool to enforce Swift style and conventions. (19k ⭐)
- **[SwiftFormat](https://github.com/nicklockwood/SwiftFormat)** - A command-line tool and Xcode Extension for formatting Swift code. (8.7k ⭐)
- **[periphery](https://github.com/peripheryapp/periphery)** - A tool to identify unused code in Swift projects. (6.0k ⭐)
- **[FengNiao](https://github.com/onevcat/FengNiao)** - A command line tool for cleaning unused resources in Xcode. (3.6k ⭐)
- **[swift-format](https://github.com/swiftlang/swift-format)** - Formatting technology for Swift source code. (2.9k ⭐)

*[↑ Back to top](#contents)*

## ⚡ Concurrency / Async

- **[PromiseKit](https://github.com/mxcl/PromiseKit)** - Promises for Swift & ObjC. (14k ⭐)
- **[Async](https://github.com/duemunk/Async)** - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch. (4.6k ⭐) ⏳
- **[swift-async-algorithms](https://github.com/apple/swift-async-algorithms)** - Async Algorithms for Swift. (3.6k ⭐)
- **[Watchdog](https://github.com/wojteklu/Watchdog)** - Class for logging excessive blocking on the main thread. (1.9k ⭐) ⏳
- **[Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift)** - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. (1.3k ⭐) ⏳
- **[ConcurrencyRecipes](https://github.com/mattmassicotte/ConcurrencyRecipes)** - Practical solutions to problems with Swift Concurrency. (1.3k ⭐)
- **[Queuer](https://github.com/FabrizioBrancati/Queuer)** - Queuer is a queue manager, built on top of OperationQueue and Dispatch (aka GCD). (1.2k ⭐)
- **[Then](https://github.com/freshOS/Then)** - Tame async code with battle-tested promises. (999 ⭐) ⏳

*[↑ Back to top](#contents)*

## 🔒 Cryptography

- **[CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift)** - CryptoSwift is a growing collection of standard and secure cryptographic algorithms implemented in Swift. (11k ⭐)
- **[RNCryptor](https://github.com/RNCryptor/RNCryptor)** - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift. (3.4k ⭐)

*[↑ Back to top](#contents)*

## 🧮 Data Structures / Algorithms

- **[swift-algorithm-club](https://github.com/kodecocodes/swift-algorithm-club)** - Algorithms and data structures in Swift, with explanations!. (29k ⭐) ⏳
- **[swift-algorithms](https://github.com/apple/swift-algorithms)** - Commonly used sequence and collection algorithms for Swift. (6.3k ⭐)
- **[LeetCode-Swift](https://github.com/soapyigu/LeetCode-Swift)** - Solutions to LeetCode by Swift. (5.0k ⭐) ⏳
- **[swift-collections](https://github.com/apple/swift-collections)** - Commonly used data structures for Swift. (4.4k ⭐)

*[↑ Back to top](#contents)*

## 🗄️ Database

- **[SQLite.swift](https://github.com/stephencelis/SQLite.swift)** - A type-safe, Swift-language layer over SQLite3. (10k ⭐)
- **[GRDB.swift](https://github.com/groue/GRDB.swift)** - A toolkit for SQLite databases, with a focus on application development. (8.2k ⭐)
- **[CoreStore](https://github.com/JohnEstropia/CoreStore)** - Unleashing the real power of Core Data with the elegance and safety of Swift. (4.1k ⭐) ⏳
- **[Sync](https://github.com/3lvis/Sync)** - JSON to Core Data and back. Swift Core Data Sync. (2.5k ⭐) ⏳
- **[IceCream](https://github.com/caiyue1993/IceCream)** - Sync Realm Database with CloudKit. (2.0k ⭐)
- **[SQLiteData](https://github.com/pointfreeco/sqlite-data)** - A fast, lightweight replacement for SwiftData, powered by SQL and supporting CloudKit synchronization. (1.6k ⭐)
- **[fluent](https://github.com/vapor/fluent)** - Vapor ORM (queries, models, and relations) for NoSQL and SQL databases. (1.4k ⭐)

*[↑ Back to top](#contents)*

## 💉 Dependency Injection

- **[Swinject](https://github.com/Swinject/Swinject)** - Dependency injection framework for Swift with iOS/macOS/Linux. (6.7k ⭐)
- **[Factory](https://github.com/hmlongco/Factory)** - A modern approach to Container-Based Dependency Injection for Swift and SwiftUI. (2.7k ⭐)
- **[Resolver](https://github.com/hmlongco/Resolver)** - Swift Ultralight Dependency Injection / Service Locator framework. (2.2k ⭐) ⏳
- **[swift-dependencies](https://github.com/pointfreeco/swift-dependencies)** - A dependency management library inspired by SwiftUI's "environment.". (2.1k ⭐)
- **[needle](https://github.com/uber/needle)** - Compile-time safe Swift dependency injection framework. (2.0k ⭐)
- **[Dip](https://github.com/AliSoftware/Dip)** - Simple Swift Dependency container. Use protocols to resolve your dependencies and avoid singletons / sharedInstances!. (982 ⭐) ⏳

*[↑ Back to top](#contents)*

## 📖 Documentation

- **[swift-docc](https://github.com/swiftlang/swift-docc)** - Documentation compiler that produces rich API reference documentation and interactive tutorials for your Swift framework or package. (1.3k ⭐)

*[↑ Back to top](#contents)*

## 🧰 Extensions / Utilities

- **[SwifterSwift](https://github.com/SwifterSwift/SwifterSwift)** - A handy collection of more than 500 native Swift extensions to boost your productivity. (15k ⭐)
- **[DeviceKit](https://github.com/devicekit/DeviceKit)** - DeviceKit is a value-type replacement of UIDevice. (4.7k ⭐)
- **[Then](https://github.com/devxoul/Then)** - Super sweet syntactic sugar for Swift initializers. (4.4k ⭐)
- **[Dollar](https://github.com/ankurp/Dollar)** - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript. (4.3k ⭐) ⏳
- **[EZSwiftExtensions](https://github.com/Esqarrouth/EZSwiftExtensions)** - How Swift standard types and classes were supposed to work. (3.0k ⭐) ⏳
- **[Device](https://github.com/Ekhoo/Device)** - Light weight tool for detecting the current device and screen size written in swift. (1.7k ⭐)
- **[swift-tagged](https://github.com/pointfreeco/swift-tagged)** - A wrapper type for safer, expressive code. (1.6k ⭐)
- **[Runtime](https://github.com/wickwirew/Runtime)** - A Swift Runtime library for viewing type info, and the dynamic getting and setting of properties. (1.2k ⭐) ⏳
- **[swift-overture](https://github.com/pointfreeco/swift-overture)** - A library for function composition. (1.2k ⭐) ⏳
- **[swift-case-paths](https://github.com/pointfreeco/swift-case-paths)** - Case paths extends the key path hierarchy to enum cases. (1.0k ⭐)

*[↑ Back to top](#contents)*

## 📁 File Management

- **[Disk](https://github.com/saoudrizwan/Disk)** - Easily persist structs, images, and data on iOS. (3.1k ⭐) ⏳
- **[ZIPFoundation](https://github.com/weichsel/ZIPFoundation)** - Effortless ZIP Handling in Swift. (2.6k ⭐)
- **[Files](https://github.com/JohnSundell/Files)** - A nicer way to handle files & folders in Swift. (2.6k ⭐)
- **[Zip](https://github.com/marmelroy/Zip)** - Swift framework for zipping and unzipping files. (2.6k ⭐) ⏳
- **[FileKit](https://github.com/nvzqz/FileKit)** - Simple and expressive file management in Swift. (2.4k ⭐) ⏳
- **[PathKit](https://github.com/kylef/PathKit)** - Effortless path operations in Swift. (1.5k ⭐) ⏳
- **[swift-system](https://github.com/apple/swift-system)** - Low-level system calls and types for Swift. (1.4k ⭐)
- **[Path.swift](https://github.com/mxcl/Path.swift)** - Delightful, robust, cross-platform and chainable file-pathing functions. (954 ⭐)

*[↑ Back to top](#contents)*

## 📝 Forms

- **[Eureka](https://github.com/xmartlabs/Eureka)** - Elegant iOS form builder in Swift. (12k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🎮 Games

- **[SwiftGodot](https://github.com/migueldeicaza/SwiftGodot)** - New Godot bindings for Swift. (1.6k ⭐)

*[↑ Back to top](#contents)*

## 🔌 Hardware

- **[BLEUnlock](https://github.com/ts1/BLEUnlock)** - Lock/unlock your Mac with your iPhone, Apple Watch, or any other Bluetooth LE devices. (3.6k ⭐) ⏳
- **[SwiftLocation](https://github.com/malcommac/SwiftLocation)** - Async/Await CLLocationManager Wrapper for Apple Platforms. (3.4k ⭐) ⏳
- **[LocoKit](https://github.com/sobri909/LocoKit)** - Location, motion, and activity recording framework for iOS. (1.5k ⭐)
- **[RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit)** - iOS & MacOS Bluetooth library for RxSwift. (1.4k ⭐) ⏳
- **[SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO)** - A Swift library for hardware projects on Linux/ARM boards with support for GPIOs/SPI/I2C/PWM/UART/1Wire. (1.4k ⭐) ⏳
- **[WebRTC-iOS](https://github.com/stasel/WebRTC-iOS)** - A simple native WebRTC demo iOS app using swift. (1.3k ⭐)
- **[BeaconEmitter](https://github.com/lgaches/BeaconEmitter)** - Turn your Mac as an iBeacon. (997 ⭐) ⏳

*[↑ Back to top](#contents)*

## 🖼️ Images

### Image Loading

- **[Kingfisher](https://github.com/onevcat/Kingfisher)** - A lightweight, pure-Swift library for downloading and caching images from the web. (24k ⭐)
- **[Nuke](https://github.com/kean/Nuke)** - Image loading system. (8.5k ⭐)
- **[SDWebImageSwiftUI](https://github.com/SDWebImage/SDWebImageSwiftUI)** - SwiftUI Image loading and Animation framework powered by SDWebImage. (2.5k ⭐)

### Image Picking

- **[ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser)** - Wechat-like image picker. Support select photos, videos, gif and livePhoto. (5.0k ⭐)
- **[ImagePicker](https://github.com/hyperoslo/ImagePicker)** - Reinventing the way ImagePicker works. (4.9k ⭐) ⏳
- **[YPImagePicker](https://github.com/Yummypets/YPImagePicker)** - Instagram-like image picker & filters for iOS. (4.5k ⭐)
- **[HXPhotoPicker](https://github.com/SilenceLove/HXPhotoPicker)** - Photo/video picker - supports LivePhoto, GIF, 3DTouch preview, editing. (3.4k ⭐)
- **[DKImagePickerController](https://github.com/zhangao0086/DKImagePickerController)** - Image Picker Controller for iOS written in Swift 4 & 5. (1.5k ⭐) ⏳
- **[BSImagePicker](https://github.com/mikaoj/BSImagePicker)** - A multiple image picker for iOS. (1.4k ⭐) ⏳
- **[Paparazzo](https://github.com/avito-tech/Paparazzo)** - Custom iOS camera and photo picker with editing capabilities. (790 ⭐)

### Image Processing

- **[GPUImage2](https://github.com/BradLarson/GPUImage2)** - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. (4.9k ⭐) ⏳
- **[GPUImage3](https://github.com/BradLarson/GPUImage3)** - GPUImage 3 is a BSD-licensed Swift framework for GPU-accelerated video and image processing using Metal. (2.9k ⭐) ⏳
- **[Mantis](https://github.com/guoyingtao/Mantis)** - An iOS Image cropping library, which mimics the Photo App written in Swift. (1.1k ⭐)

### Image Viewing

- **[SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser)** - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift. (2.7k ⭐)
- **[ImageSlideshow](https://github.com/zvonicek/ImageSlideshow)** - Swift image slideshow with circular scrolling, timer and full screen viewer. (1.8k ⭐) ⏳
- **[Lightbox](https://github.com/hyperoslo/Lightbox)** - A convenient and easy to use image viewer for your iOS app. (1.7k ⭐) ⏳
- **[ImageViewer.swift](https://github.com/michaelhenry/ImageViewer.swift)** - An easy to use Image Viewer that is inspired by Facebook. (1.6k ⭐) ⏳
- **[PhotoBrowser](https://github.com/JiongXing/PhotoBrowser)** - Elegant photo browser in Swift. (1.4k ⭐)

### GIF

- **[Gifu](https://github.com/kaishin/Gifu)** - High-performance animated GIF support for iOS in Swift. (3.2k ⭐)
- **[SwiftyGif](https://github.com/alexiscreuzot/SwiftyGif)** - High performance GIF engine. (2.3k ⭐) ⏳
- **[APNGKit](https://github.com/onevcat/APNGKit)** - High performance and delightful way to play with APNG format in iOS. (2.3k ⭐) ⏳

### QR Code

- **[EFQRCode](https://github.com/EFPrefix/EFQRCode)** - A better way to operate QRCode in Swift, support iOS, macOS, watchOS, tvOS, and/or visionOS. (4.7k ⭐)
- **[BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner)** - A simple and beautiful barcode scanner. (1.7k ⭐) ⏳
- **[QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift)** - Simple QRCode reader in Swift. (1.3k ⭐) ⏳

*[↑ Back to top](#contents)*

## 📋 JSON / Parsing

- **[SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)** - The better way to deal with JSON data in Swift. (23k ⭐)
- **[ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper)** - Simple JSON Object mapping written in Swift. (9.2k ⭐) ⏳
- **[HandyJSON](https://github.com/alibaba/HandyJSON)** - A handy swift json-object serialization/deserialization library. (4.3k ⭐) ⏳
- **[SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator)** - macOS app to generate Swift 5 code for models from JSON (with Codeable). (949 ⭐)

### XML / HTML

- **[SwiftSoup](https://github.com/scinfu/SwiftSoup)** - SwiftSoup: Pure Swift HTML Parser, with best of DOM, CSS, and jquery. (5.0k ⭐)
- **[Kanna](https://github.com/tid-kijyun/Kanna)** - Kanna is an XML/HTML parser for Swift. (2.5k ⭐)
- **[SWXMLHash](https://github.com/drmohundro/SWXMLHash)** - Simple XML parsing in Swift. (1.5k ⭐)
- **[Fuzi](https://github.com/cezheng/Fuzi)** - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support. (1.1k ⭐) ⏳

### YAML

- **[Yams](https://github.com/jpsim/Yams)** - A Sweet and Swifty YAML parser. (1.2k ⭐)

### CSV

- **[SwiftCSV](https://github.com/swiftcsv/SwiftCSV)** - CSV parser for Swift. (1.1k ⭐)

### RSS / Feed

- **[FeedKit](https://github.com/nmdias/FeedKit)** - FeedKit is a Swift library for Reading and Generating RSS, Atom, and JSON feeds. (1.3k ⭐)

*[↑ Back to top](#contents)*

## ⌨️ Keyboard

- **[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager)** - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView. (17k ⭐)
- **[KeyboardKit](https://github.com/KeyboardKit/KeyboardKit)** - Create amazing custom iOS keyboards with Swift & SwiftUI. (1.8k ⭐)
- **[KeyboardLayoutGuide](https://github.com/freshOS/KeyboardLayoutGuide)** - KeyboardLayoutGuide, back from when it didn't exist. (1.2k ⭐) ⏳

*[↑ Back to top](#contents)*

## 📐 Layout

- **[SnapKit](https://github.com/SnapKit/SnapKit)** - A Swift Autolayout DSL for iOS & OS X. (20k ⭐)
- **[Cartography](https://github.com/robb/Cartography)** - A declarative Auto Layout DSL for Swift. (7.3k ⭐)
- **[TinyConstraints](https://github.com/roberthein/TinyConstraints)** - Nothing but sugar. (4.1k ⭐) ⏳
- **[Stevia](https://github.com/freshOS/Stevia)** - Concise Autolayout code. (3.4k ⭐)
- **[PinLayout](https://github.com/layoutBox/PinLayout)** - Fast Swift Views layouting without auto layout. No magic, pure code, full control and blazing fast. (2.4k ⭐)
- **[FlexLayout](https://github.com/layoutBox/FlexLayout)** - FlexLayout adds a nice Swift interface to the highly optimized facebook/yoga flexbox implementation. (2.1k ⭐)
- **[wtfautolayout](https://github.com/johnpatrickmorgan/wtfautolayout)** - The source code for Why The Failure, Auto Layout?. (1.1k ⭐) ⏳
- **[Paralayout](https://github.com/square/Paralayout)** - Paralayout is a set of simple, useful, and straightforward utilities that enable pixel-perfect layout in iOS. (793 ⭐)

*[↑ Back to top](#contents)*

## 🌍 Localization

- **[iOSLocalizationEditor](https://github.com/igorkulman/iOSLocalizationEditor)** - Simple macOS editor app to help you manage iOS and macOS app localizations. (1.5k ⭐) ⏳
- **[BartyCrouch](https://github.com/FlineDev/BartyCrouch)** - Localization/I18n: Incrementally update/translate your Strings files from .swift, .h, .m(m), .storyboard or .xib files. (1.4k ⭐) ⏳

*[↑ Back to top](#contents)*

## 📜 Logging

- **[SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver)** - Convenient & secure logging during development & release in Swift 4 & 5. (6.1k ⭐) ⏳
- **[XCGLogger](https://github.com/DaveWoodCom/XCGLogger)** - A debug log framework for use in Swift projects. (4.0k ⭐) ⏳
- **[swift-log](https://github.com/apple/swift-log)** - A Logging API for Swift. (3.9k ⭐)
- **[Willow](https://github.com/Nike-Inc/Willow)** - Willow is a powerful, yet lightweight logging library written in Swift. (1.4k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🤖 Machine Learning / AI

- **[Sidekick](https://github.com/johnbean393/Sidekick)** - A native macOS app that allows users to chat with a local LLM. (3.2k ⭐)
- **[OpenAI](https://github.com/MacPaw/OpenAI)** - Swift community driven package for OpenAI public API. (2.9k ⭐)
- **[swift-coreml-diffusers](https://github.com/huggingface/swift-coreml-diffusers)** - Swift app demonstrating Core ML Stable Diffusion. (2.7k ⭐)
- **[mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples)** - Examples using MLX Swift. (2.4k ⭐)
- **[LLMFarm](https://github.com/guinmoon/LLMFarm)** - llama and other large language models on iOS and MacOS offline using GGML library. (2.0k ⭐)
- **[OpenAISwift](https://github.com/adamrushy/OpenAISwift)** - This is a wrapper library around the ChatGPT and OpenAI HTTP API. (1.7k ⭐) ⏳
- **[swift-transformers](https://github.com/huggingface/swift-transformers)** - Swift Package to implement a transformers-like API in Swift. (1.3k ⭐)

*[↑ Back to top](#contents)*

## 🖥️ macOS Apps

- **[iina](https://github.com/iina/iina)** - The modern video player for macOS. (44k ⭐)
- **[ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)** - Next Generation of ShadowsocksX. (33k ⭐) ⏳
- **[MonitorControl](https://github.com/MonitorControl/MonitorControl)** - Control your display's brightness & volume on your Mac as if it was a native Apple Display. (32k ⭐)
- **[Ice](https://github.com/jordanbaird/Ice)** - Powerful menu bar manager for macOS. (26k ⭐)
- **[CodeEdit](https://github.com/CodeEditApp/CodeEdit)** - CodeEdit App for macOS - Elevate your code editing experience. Open source, free forever. (23k ⭐)
- **[AeroSpace](https://github.com/nikitabobko/AeroSpace)** - AeroSpace is an i3-like tiling window manager for macOS. (19k ⭐)
- **[Mos](https://github.com/Caldis/Mos)** - A lightweight tool used to smooth scrolling and set scroll direction independently for your mouse on macOS. (19k ⭐)
- **[hidden](https://github.com/dwarvesf/hidden)** - An ultra-light MacOS utility that helps hide menu bar icons. (13k ⭐)
- **[cua](https://github.com/trycua/cua)** - A lightweight CLI and local API server to create, run and manage macOS and Linux virtual machines on Apple Silicon. (13k ⭐)
- **[Loop](https://github.com/MrKai77/Loop)** - Window management made elegant. (10k ⭐)
- **[WWDC](https://github.com/insidegui/WWDC)** - The unofficial WWDC app for macOS. (8.7k ⭐)
- **[Clipy](https://github.com/Clipy/Clipy)** - Clipboard extension app for macOS. (8.4k ⭐) ⏳
- **[Gifski](https://github.com/sindresorhus/Gifski)** - Convert videos to high-quality GIFs on your Mac. (8.3k ⭐)
- **[XcodesApp](https://github.com/XcodesOrg/XcodesApp)** - The easiest way to install and switch between multiple versions of Xcode - with a mouse click. (8.2k ⭐)
- **[MochiDiffusion](https://github.com/MochiDiffusion/MochiDiffusion)** - Run Stable Diffusion on Mac natively. (7.8k ⭐)
- **[CotEditor](https://github.com/coteditor/CotEditor)** - Lightweight Plain-Text Editor for macOS. (7.6k ⭐)
- **[MiaoYan](https://github.com/tw93/MiaoYan)** - Lightweight Markdown app to help you write great sentences. (7.6k ⭐)
- **[fsnotes](https://github.com/glushchenko/fsnotes)** - Notes manager for macOS/iOS. (7.2k ⭐)
- **[vimr](https://github.com/qvacua/vimr)** - VimR - Neovim GUI for macOS in Swift. (6.9k ⭐)
- **[eqMac](https://github.com/bitgapp/eqMac)** - macOS System-wide Audio Equalizer & Volume Mixer. (6.5k ⭐)
- **[Applite](https://github.com/milanvarady/Applite)** - User-friendly GUI macOS application for Homebrew Casks. (6.4k ⭐)
- **[ControlRoom](https://github.com/twostraws/ControlRoom)** - A macOS app to control the Xcode Simulator. (6.0k ⭐)
- **[CodexBar](https://github.com/steipete/CodexBar)** - Show usage stats for OpenAI Codex and Claude Code, without having to login. (5.9k ⭐)
- **[Dayflow](https://github.com/JerryZLiu/Dayflow)** - Generate a timeline of your day, automatically. (5.7k ⭐)
- **[Lunar](https://github.com/alin23/Lunar)** - Intelligent adaptive brightness for your external monitors. (5.4k ⭐)
- **[noTunes](https://github.com/tombonez/noTunes)** - A simple macOS application that will prevent iTunes or Apple Music from launching. (5.4k ⭐) ⏳
- **[MeetingBar](https://github.com/leits/MeetingBar)** - Your meetings at your fingertips in the macOS menu bar. (5.1k ⭐)
- **[finicky](https://github.com/johnste/finicky)** - A macOS app for customizing which browser to start. (4.6k ⭐)
- **[Latest](https://github.com/mangerlahn/Latest)** - A small utility app for macOS that makes sure you know about all the latest updates to the apps you use. (4.4k ⭐)
- **[Cork](https://github.com/buresdv/Cork)** - A fast GUI for Homebrew written in SwiftUI. (4.1k ⭐)
- **[port-killer](https://github.com/productdevbook/port-killer)** - A powerful cross-platform port management tool for developers. (4.1k ⭐)
- **[Plash](https://github.com/sindresorhus/Plash)** - Make any website your Mac desktop wallpaper. (3.9k ⭐)
- **[VoiceInk](https://github.com/Beingpax/VoiceInk)** - Voice-to-text app for macOS to transcribe what you say to text almost instantly. (3.8k ⭐)
- **[SwiftBar](https://github.com/swiftbar/SwiftBar)** - Powerful macOS menu bar customization tool. (3.7k ⭐)
- **[uPic](https://github.com/gee1k/uPic)** - uPic is a native, powerful, beautiful and simple picture and file upload tool for macOS. (3.7k ⭐)
- **[reminders-menubar](https://github.com/DamascenoRafael/reminders-menubar)** - Simple macOS menu bar application to view and interact with reminders. (3.7k ⭐)
- **[MarkEdit](https://github.com/MarkEdit-app/MarkEdit)** - Just like TextEdit on Mac but dedicated to Markdown. (3.7k ⭐)
- **[osaurus](https://github.com/dinoki-ai/osaurus)** - AI edge infrastructure for macOS. Run local or cloud models, share tools across apps via MCP. (3.5k ⭐)
- **[wallpapper](https://github.com/mczachurski/wallpapper)** - Console application for creating dynamic wallpapers for macOS Mojave and newer. (3.4k ⭐) ⏳
- **[phpmon](https://github.com/nicoverbruggen/phpmon)** - Lightweight, native Mac menu bar app that helps you manage multiple PHP installations. (3.2k ⭐)
- **[TomatoBar](https://github.com/ivoronin/TomatoBar)** - World's neatest Pomodoro timer for macOS menu bar. (3.1k ⭐)
- **[SpotMenu](https://github.com/kmikiy/SpotMenu)** - Spotify & Apple Music in your macOS menu bar. (3.1k ⭐)
- **[FlashSpace](https://github.com/wojciech-kulik/FlashSpace)** - FlashSpace is a blazingly fast virtual workspace manager for macOS. (3.0k ⭐)
- **[Actions](https://github.com/sindresorhus/Actions)** - Supercharge your shortcuts. (3.0k ⭐)
- **[LocationSimulator](https://github.com/Schlaubischlump/LocationSimulator)** - MacOS application to spoof / fake / mock your iOS device location. (2.9k ⭐) ⏳
- **[AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer)** - An app that lets you open .car files and browse/extract their images. (2.8k ⭐)
- **[FineTune](https://github.com/ronitsingh10/FineTune)** - FineTune, a macOS menu bar app to control volume for each app independently. (2.6k ⭐)
- **[rem](https://github.com/jasonjmcghee/rem)** - An open source approach to locally record and enable searching everything you view on your Mac. (2.5k ⭐) ⏳
- **[MiniSim](https://github.com/okwasniewski/MiniSim)** - MacOS menu bar app for launching iOS and Android emulators. (2.3k ⭐)
- **[pika](https://github.com/superhighfives/pika)** - An open-source colour picker app for macOS. (2.3k ⭐)
- **[DevHub](https://github.com/jaywcjlove/DevHub)** - A feature-rich offline application, is meticulously crafted to support developers in their daily tasks. (2.0k ⭐)
- **[Equinox](https://github.com/rlxone/Equinox)** - Create dynamic wallpapers for macOS. (1.8k ⭐)
- **[SwiftDefaultApps](https://github.com/Lord-Kamina/SwiftDefaultApps)** - Replacement for RCDefaultApps, written in Swift. (1.7k ⭐) ⏳
- **[TRex](https://github.com/amebalabs/TRex)** - Copy any text on your screen, stop retyping. (1.7k ⭐)
- **[Sentinel](https://github.com/alienator88/Sentinel)** - Configure Gatekeeper, remove apps from quarantine and self-sign apps. (1.4k ⭐)
- **[XcodeCleaner-SwiftUI](https://github.com/waylybaye/XcodeCleaner-SwiftUI)** - Make Xcode Clean Again. (1.4k ⭐)
- **[multi](https://github.com/kofigumbs/multi)** - Create custom, lightweight macOS apps from websites. (1.4k ⭐)
- **[System-Color-Picker](https://github.com/sindresorhus/System-Color-Picker)** - The macOS color picker as an app with more features. (1.4k ⭐)
- **[DockProgress](https://github.com/sindresorhus/DockProgress)** - Show progress in your app's Dock icon. (1.3k ⭐)
- **[LunarBar](https://github.com/LunarBar-app/LunarBar)** - A compact lunar calendar for your macOS menu bar. (1.3k ⭐)
- **[HSTracker](https://github.com/HearthSim/HSTracker)** - A deck tracker and deck manager for Hearthstone on macOS. (1.2k ⭐)
- **[Cilicon](https://github.com/traderepublic/Cilicon)** - Self-Hosted ephemeral macOS CI on Apple Silicon. (1.1k ⭐)
- **[HotKey](https://github.com/soffes/HotKey)** - Simple global shortcuts in macOS. (1.1k ⭐) ⏳
- **[copybook-generator](https://github.com/jaywcjlove/copybook-generator)** - "Copybook Generator" is a powerful copybook generation tool. (1.0k ⭐)
- **[ChangeMenuBarColor](https://github.com/igorkulman/ChangeMenuBarColor)** - Simple utility to change macOS Big Sur and Monterey menu bar color. (986 ⭐)

*[↑ Back to top](#contents)*

## ⚠️ Malicious

- **[WHC_ConfuseSoftware](https://github.com/netyouli/WHC_ConfuseSoftware)** - iOS代码混淆工具，Uniapp代码混淆工具，react-native代码混淆, iOS代码混淆助手，Android代码混淆助手，Uniapp代码混淆助手，过机器审核，辅助过4.3, other审核，android、ios、uniapp、u3d、cocos2dx、flutter、代码翻新(WHC_ConfuseSoftware)是一款运行在MAC OS平台的App、完美支持Objc和Swift、U3D、Flutter、Cocos2dx项目代码的自动翻新(混淆)、支持文件夹名称、文件名、修改资源文件hash值、类名、方法名、属性名、添加混淆函数方法体、添加混淆属性、自动调用生成的混淆方法、字符串混淆加密等...功能强大而稳定。. (1.8k ⭐)
- **[confuse-9live](https://github.com/outtable/confuse-9live)** - 🔥🔥🔥 专业版iOS混淆工具，马甲工具包、ipa静态分析工具（相似度对比、敏感词检测），提供试用版本，100%过机器审核，解决 AppStore 4.3，2.3.1问题，支持语言 c、c++、objc、dart、swift 并支持各种资源改名，混淆、傻瓜化操作、一键出包，提供良好的UI界面，支持多包管理一包一特征、支持Unity3d、cocos2d全家桶、swiftUI、flutter、虚幻等各种引擎。支持混淆.a/.framework/.xcframework，混淆比例95%，支持dSYM文件混淆和恢复功能，不影响bugly等各种在线崩溃收集，可持续迭代原工程。. (1.6k ⭐)

*[↑ Back to top](#contents)*

## 📝 Markdown

- **[swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui)** - Render Markdown text in SwiftUI. (3.7k ⭐)
- **[swift-markdown](https://github.com/swiftlang/swift-markdown)** - A Swift package for parsing, building, editing, and analyzing Markdown documents. (3.2k ⭐)
- **[Ink](https://github.com/JohnSundell/Ink)** - A fast and flexible Markdown parser written in Swift. (2.5k ⭐) ⏳
- **[MarkdownView](https://github.com/keitaoouchi/MarkdownView)** - Markdown View for iOS. (2.1k ⭐)
- **[SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown)** - Converts Markdown files and strings into NSAttributedStrings with lots of customisation options. (1.7k ⭐) ⏳

*[↑ Back to top](#contents)*

## ➗ Math

- **[swift-numerics](https://github.com/apple/swift-numerics)** - Advanced mathematical types and functions for Swift. (1.8k ⭐)
- **[GEOSwift](https://github.com/GEOSwift/GEOSwift)** - The Swift Geometry Engine. (1.5k ⭐)
- **[SoulverCore](https://github.com/soulverteam/SoulverCore)** - A powerful Swift framework for evaluating natural language math expressions. (1.0k ⭐)
- **[DDMathParser](https://github.com/davedelong/DDMathParser)** - String to Number. (865 ⭐) ⏳
- **[Expression](https://github.com/nicklockwood/Expression)** - A cross-platform Swift library for evaluating mathematical expressions at runtime. (850 ⭐)

*[↑ Back to top](#contents)*

## ▶️ Media Player

- **[HaishinKit.swift](https://github.com/HaishinKit/HaishinKit.swift)** - Camera and Microphone streaming library via RTMP and SRT for iOS, macOS, tvOS and visionOS. (3.0k ⭐)
- **[NextLevel](https://github.com/NextLevel/NextLevel)** - Media Capture in Swift. (2.3k ⭐)
- **[Player](https://github.com/piemonte/Player)** - Play and stream media in Swift. (2.2k ⭐)
- **[BMPlayer](https://github.com/BrikerMan/BMPlayer)** - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles. (2.0k ⭐) ⏳
- **[KSPlayer](https://github.com/kingslay/KSPlayer)** - A video player for iOS, macOS, tvOS, visionOS, based on AVPlayer and FFmpeg, support SwiftUI, subtitles. (1.5k ⭐)
- **[CameraManager](https://github.com/imaginary-cloud/CameraManager)** - Simple Swift class to provide all the configurations you need to create custom camera view in your app. (1.4k ⭐) ⏳
- **[Aperture](https://github.com/wulkano/Aperture)** - Record the screen on macOS. (1.3k ⭐) ⏳
- **[Lumina](https://github.com/dokun1/Lumina)** - A camera designed in Swift for easily integrating CoreML models. (907 ⭐)

*[↑ Back to top](#contents)*

## 🧭 Menu / Navigation

- **[PopMenu](https://github.com/CaliCastle/PopMenu)** - A fully customizable popup style menu for iOS. (1.7k ⭐) ⏳

*[↑ Back to top](#contents)*

## 👋 Onboarding

- **[Instructions](https://github.com/ephread/Instructions)** - Create walkthroughs and guided tours (coach marks) in a simple way, with Swift. (5.2k ⭐) ⏳
- **[WhatsNewKit](https://github.com/SvenTiigi/WhatsNewKit)** - Showcase your awesome new app features. (4.3k ⭐) ⏳
- **[Gecco](https://github.com/bannzai/Gecco)** - Simply highlight items for your tutorial walkthrough, written in Swift. (1.9k ⭐) ⏳
- **[ConcentricOnboarding](https://github.com/exyte/ConcentricOnboarding)** - SwiftUI library for a walkthrough or onboarding flow with tap actions. (1.5k ⭐)
- **[OnboardingKit](https://github.com/danielsaidi/OnboardingKit)** - Create amazing onboarding experiences in SwiftUI. (1.2k ⭐)

*[↑ Back to top](#contents)*

## 📱 Open Source iOS Apps

- **[open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps)** - Collaborative List of Open-Source iOS Apps. (49k ⭐)
- **[open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps)** - Awesome list of open source applications for macOS. (47k ⭐)
- **[firefox-ios](https://github.com/mozilla-mobile/firefox-ios)** - Firefox for iOS. (13k ⭐)
- **[ios-oss](https://github.com/kickstarter/ios-oss)** - Kickstarter for iOS. Bring new ideas to life, anywhere. (8.6k ⭐)
- **[IceCubesApp](https://github.com/Dimillian/IceCubesApp)** - A SwiftUI Mastodon client. (6.9k ⭐)
- **[blink](https://github.com/blinksh/blink)** - Blink Mobile Shell for iOS (Mosh based). (6.6k ⭐)
- **[enchanted](https://github.com/gluonfield/enchanted)** - Enchanted is iOS and macOS app for chatting with private self hosted language models using Ollama. (5.8k ⭐)
- **[TelegramSwift](https://github.com/overtake/TelegramSwift)** - Source code of Telegram for macos on Swift 5.0. (5.5k ⭐)
- **[Messenger](https://github.com/relatedcode/Messenger)** - Open source alternative communication platform. (4.8k ⭐)
- **[userscripts](https://github.com/quoid/userscripts)** - An open-source userscript manager for Safari. (4.3k ⭐)
- **[cheetah](https://github.com/leetcode-mafia/cheetah)** - Mac app for crushing tech interviews with AI. (4.3k ⭐) ⏳
- **[Aidoku](https://github.com/Aidoku/Aidoku)** - Free and open source manga reader for iOS and iPadOS. (3.9k ⭐)
- **[WordPress-iOS](https://github.com/wordpress-mobile/WordPress-iOS)** - WordPress for iOS - Official repository. (3.8k ⭐)
- **[Swiftfin](https://github.com/jellyfin/Swiftfin)** - Native Jellyfin Client for iOS and tvOS. (3.7k ⭐)
- **[wikipedia-ios](https://github.com/wikimedia/wikipedia-ios)** - The official Wikipedia iOS app. (3.3k ⭐)
- **[yattee](https://github.com/yattee/yattee)** - Privacy oriented video player for iOS, tvOS and macOS. (3.3k ⭐)
- **[Swift-Radio-Pro](https://github.com/analogcode/Swift-Radio-Pro)** - Professional Radio Station App for iOS!. (2.9k ⭐)
- **[Swiftcord](https://github.com/SwiftcordApp/Swiftcord)** - A fully native Discord client for macOS built 100% in Swift!. (2.2k ⭐) ⏳
- **[iOS](https://github.com/home-assistant/iOS)** - Home Assistant for Apple platforms. (2.1k ⭐)
- **[BookPlayer](https://github.com/TortugaPower/BookPlayer)** - Player for your DRM-free audiobooks. (2.0k ⭐)
- **[HealthGPT](https://github.com/StanfordBDHG/HealthGPT)** - Query your Apple Health data with natural language. (1.9k ⭐)
- **[V2ex-Swift](https://github.com/Finb/V2ex-Swift)** - An iOS client written in Swift for V2EX. (1.6k ⭐)
- **[edhita](https://github.com/tnantoka/edhita)** - Fully open source text editor for iOS written in SwiftUI. (1.4k ⭐)
- **[amperfy](https://github.com/BLeeEZ/amperfy)** - Amperfy is an iOS/iPadOS/macOS app to play songs from an Ampache or Subsonic server. (1.4k ⭐)
- **[example-ios-apps](https://github.com/jogendra/example-ios-apps)** - A curated list of Open Source example iOS apps developed in Swift. (1.3k ⭐) ⏳
- **[winston](https://github.com/lo-cafe/winston)** - A beautiful and native Reddit client for iOS. (1.2k ⭐)
- **[vlc-ios](https://github.com/videolan/vlc-ios)** - VLC for iOS/iPadOS and tvOS official mirror. (1.2k ⭐)
- **[trailer](https://github.com/ptsochantaris/trailer)** - Managing Pull Requests and Issues For GitHub & GitHub Enterprise. (1.2k ⭐)
- **[OpenScanner](https://github.com/pencilresearch/OpenScanner)** - Fast, reliable, and free document scanner app for iPhone. (1.1k ⭐) ⏳
- **[wire-ios](https://github.com/wireapp/wire-ios)** - Wire for iOS (iPhone and iPad). (110 ⭐)

*[↑ Back to top](#contents)*

## 🔑 Permissions

- **[PermissionsSwiftUI](https://github.com/jevonmao/PermissionsSwiftUI)** - A SwiftUI package to beautifully display and handle permissions. (1.6k ⭐) ⏳

*[↑ Back to top](#contents)*

## ⏳ Progress / Loading

- **[SkeletonView](https://github.com/Juanpe/SkeletonView)** - An elegant way to show users that something is happening and also prepare them to which contents they are awaiting. (13k ⭐) ⏳
- **[NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)** - A collection of awesome loading animations. (11k ⭐) ⏳
- **[ProgressHUD](https://github.com/relatedcode/ProgressHUD)** - ProgressHUD is a lightweight and easy-to-use HUD for iOS. (3.0k ⭐)
- **[HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider)** - A custom reusable circular / progress slider control for iOS application. (2.7k ⭐) ⏳
- **[SwiftUI-Shimmer](https://github.com/markiv/SwiftUI-Shimmer)** - Shimmer is a super-light modifier that adds a shimmering effect to any SwiftUI View. (1.6k ⭐) ⏳
- **[SkeletonUI](https://github.com/CSolanaM/SkeletonUI)** - Elegant skeleton loading animation in lightweight SwiftUI. (960 ⭐) ⏳
- **[GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar)** - A customizable animated gradient loading bar. (893 ⭐)

*[↑ Back to top](#contents)*

## ⚛️ Reactive Programming

- **[RxSwift](https://github.com/ReactiveX/RxSwift)** - Reactive Programming in Swift. (25k ⭐)
- **[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)** - Cocoa framework and Obj-C dynamism bindings for ReactiveSwift. (20k ⭐)
- **[ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)** - Streams of values over time. (3.0k ⭐)
- **[CombineExt](https://github.com/CombineCommunity/CombineExt)** - CombineExt provides a collection of operators, publishers and utilities for Combine. (1.8k ⭐)
- **[ReactiveKit](https://github.com/DeclarativeHub/ReactiveKit)** - A Swift Reactive Programming Kit. (1.2k ⭐)
- **[RxCombine](https://github.com/CombineCommunity/RxCombine)** - Bi-directional type bridging between RxSwift and Apple's Combine framework. (1.1k ⭐) ⏳

*[↑ Back to top](#contents)*

## 📚 Resources / Learning

- **[awesome-ios](https://github.com/vsouza/awesome-ios)** - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects. (51k ⭐)
- **[awesome-swift](https://github.com/matteocrippa/awesome-swift)** - A collaborative list of awesome Swift libraries and resources. (26k ⭐)
- **[SwiftGuide](https://github.com/ipader/SwiftGuide)** - Swift Featured Projects in brain Mapping. (16k ⭐) ⏳
- **[Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift)** - Design Patterns implemented in Swift 5.0. (15k ⭐) ⏳
- **[HackingWithSwift](https://github.com/twostraws/HackingWithSwift)** - The project source code for Hacking with iOS. (6.3k ⭐)
- **[ios-learning-materials](https://github.com/eleev/ios-learning-materials)** - Curated list of articles, tutorials and repos that may help you dig a little bit deeper into iOS. (3.0k ⭐) ⏳
- **[SwiftPamphletApp](https://github.com/ming1016/SwiftPamphletApp)** - 戴铭的小册子，一本活的知识手册。使用 SwiftUI + SwiftData + Swift Concurrency. (2.6k ⭐)
- **[Swift-Macros](https://github.com/krzysztofzablocki/Swift-Macros)** - A curated list of awesome Swift Macros. (2.4k ⭐)
- **[swiftui-notes](https://github.com/heckj/swiftui-notes)** - content for Using Combine - notes on learning Combine with UIKit and SwiftUI. (2.0k ⭐) ⏳
- **[OOD-Principles-In-Swift](https://github.com/ochococo/OOD-Principles-In-Swift)** - The Principles of OOD (SOLID) based on Uncle Bob articles. (1.9k ⭐)
- **[ios-developer-tools](https://github.com/LeoMobileDeveloper/ios-developer-tools)** - Tools that every iOS developer should know. (1.8k ⭐) ⏳
- **[awesome-swiftui-libraries](https://github.com/Toni77777/awesome-swiftui-libraries)** - Awesome SwiftUI Libraries. (1.5k ⭐)
- **[awesome-swift-macos-apps](https://github.com/jaywcjlove/awesome-swift-macos-apps)** - A curated collection of open-source macOS applications built with Swift. (1.2k ⭐)
- **[VisualProgrammingLanguage](https://github.com/NathanFlurry/VisualProgrammingLanguage)** - Visual programming language written in Swift that assembles to executable Swift code. (1.2k ⭐)
- **[pointfreeco](https://github.com/pointfreeco/pointfreeco)** - The source for <www.pointfree.co>, a video series on advanced programming topics in Swift. (1.2k ⭐)
- **[Cacao](https://github.com/PureSwift/Cacao)** - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux). (1.1k ⭐) ⏳
- **[aprenda-swift](https://github.com/CodandoApple/aprenda-swift)** - Uma lista de conteúdos para você aprender Swift. (1.0k ⭐)
- **[functional-swift](https://github.com/objcio/functional-swift)** - Issue repository for the Functional Swift book. (917 ⭐) ⏳
- **[iowncode](https://github.com/anupamchugh/iowncode)** - A curated collection of iOS, ML, AR resources sprinkled with some UI additions. (910 ⭐)
- **[LLVMSwift](https://github.com/llvm-swift/LLVMSwift)** - A Swift wrapper for the LLVM C API (version 11.0). (760 ⭐) ⏳
- **[Axiom](https://github.com/CharlesWiltgen/Axiom)** - Battle-tested Claude Code skills, commands, and references for modern Apple-platform development. (471 ⭐)

*[↑ Back to top](#contents)*

## 🖥️ Server-Side Swift

- **[vapor](https://github.com/vapor/vapor)** - A server-side Swift HTTP web framework. (26k ⭐)
- **[swifter](https://github.com/httpswift/swifter)** - Tiny http server engine written in Swift programming language. (4.0k ⭐) ⏳
- **[hummingbird](https://github.com/hummingbird-project/hummingbird)** - Lightweight, flexible HTTP server framework written in Swift. (1.7k ⭐)
- **[smoke-framework](https://github.com/amzn/smoke-framework)** - A light-weight server-side service framework written in the Swift programming language. (1.5k ⭐) ⏳
- **[swift-aws-lambda-runtime](https://github.com/awslabs/swift-aws-lambda-runtime)** - Swift implementation of AWS Lambda Runtime. (1.2k ⭐)

*[↑ Back to top](#contents)*

## 💽 Storage

- **[SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults)** - Modern Swift API for NSUserDefaults. (4.9k ⭐) ⏳
- **[DefaultsKit](https://github.com/nmdias/DefaultsKit)** - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS. (1.4k ⭐) ⏳
- **[Boutique](https://github.com/mergesort/Boutique)** - A magical persistence library (and so much more) for state-driven iOS and Mac apps. (1.1k ⭐)

*[↑ Back to top](#contents)*

## 🎨 SwiftUI

- **[SwiftUIX](https://github.com/SwiftUIX/SwiftUIX)** - An exhaustive expansion of the standard SwiftUI library. (8.0k ⭐)
- **[swiftui-introspect](https://github.com/siteline/swiftui-introspect)** - Introspect underlying UIKit/AppKit components from SwiftUI. (6.4k ⭐)
- **[SwiftUI](https://github.com/Jinxiansen/SwiftUI)** - SwiftUI Framework Learning and Usage Guide. (5.4k ⭐) ⏳
- **[SwiftWebUI](https://github.com/SwiftWebUI/SwiftWebUI)** - A demo implementation of SwiftUI for the Web. (4.3k ⭐) ⏳
- **[skip](https://github.com/skiptools/skip)** - Skip enables the creation of native SwiftUI apps for iOS and Android. (2.8k ⭐)
- **[WaterfallGrid](https://github.com/paololeonardi/WaterfallGrid)** - A waterfall grid layout view for SwiftUI. (2.6k ⭐) ⏳
- **[ViewInspector](https://github.com/nalexn/ViewInspector)** - Runtime introspection and unit testing of SwiftUI views. (2.6k ⭐)
- **[divkit](https://github.com/divkit/divkit)** - DivKit is an open source Server-Driven UI (SDUI) framework. (2.5k ⭐)
- **[ConfettiSwiftUI](https://github.com/simibac/ConfettiSwiftUI)** - SwiftUI Package for Configurable Confetti Animation. (2.3k ⭐)
- **[swift-navigation](https://github.com/pointfreeco/swift-navigation)** - Bringing simple and powerful navigation tools to all Swift platforms, inspired by SwiftUI. (2.2k ⭐)
- **[Popovers](https://github.com/aheze/Popovers)** - A library to present popovers. Simple, modern, and highly customizable. (2.2k ⭐)
- **[OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI)** - Open source implementation of Apple's SwiftUI. (2.0k ⭐)
- **[SwiftUI-experiments](https://github.com/mikelikesdesign/SwiftUI-experiments)** - Examples with SwiftUI and other Apple frameworks. (1.9k ⭐)
- **[Popups](https://github.com/Mijick/Popups)** - Popups, popovers, sheets, alerts, toasts, banners presentation made simple. Written for SwiftUI. (1.8k ⭐)
- **[SwiftUIKit](https://github.com/danielsaidi/SwiftUIKit)** - Extra functionality for Swift & SwiftUI. (1.7k ⭐)
- **[Setting](https://github.com/aheze/Setting)** - Compose beautiful preference panels. (1.6k ⭐) ⏳
- **[ScalingHeaderScrollView](https://github.com/exyte/ScalingHeaderScrollView)** - A scroll view with a sticky header which shrinks as you scroll. Written with SwiftUI. (1.5k ⭐)
- **[SwiftTUI](https://github.com/rensbreur/SwiftTUI)** - SwiftUI for terminal applications. (1.5k ⭐) ⏳
- **[SwiftUIPager](https://github.com/fermoya/SwiftUIPager)** - Native Pager in SwiftUI. (1.4k ⭐) ⏳
- **[swift-cross-ui](https://github.com/moreSwift/swift-cross-ui)** - A cross-platform declarative UI framework, inspired by SwiftUI. (1.4k ⭐)
- **[StepperView](https://github.com/badrinathvm/StepperView)** - SwiftUI iOS component for Step Indications. (1.3k ⭐)
- **[SwipeActions](https://github.com/aheze/SwipeActions)** - Add customizable swipe actions to any view. (1.3k ⭐)
- **[BottomSheet](https://github.com/lucaszischka/BottomSheet)** - A sliding Sheet from the bottom of the Screen with 3 States build with SwiftUI. (1.2k ⭐)
- **[SlideOverCard](https://github.com/joogps/SlideOverCard)** - A SwiftUI card view, made great for setup interactions. (1.2k ⭐) ⏳
- **[WidgetExamples](https://github.com/pawello2222/WidgetExamples)** - A demo project showing different types of Widgets created with SwiftUI and WidgetKit. (1.1k ⭐) ⏳
- **[shiny](https://github.com/maustinstar/shiny)** - Shiny uses your gyroscope to simulate lighting and motion effects on colors. (1.1k ⭐) ⏳
- **[SwiftUIBackports](https://github.com/shaps80/SwiftUIBackports)** - A collection of SwiftUI backports for iOS, macOS, tvOS and watchOS. (1.1k ⭐)
- **[swiftui-navigation-transitions](https://github.com/davdroman/swiftui-navigation-transitions)** - Pure SwiftUI Navigation transitions. (1.1k ⭐)
- **[swiftui-router](https://github.com/frzi/swiftui-router)** - Path-based routing in SwiftUI. (960 ⭐) ⏳
- **[neumorphic](https://github.com/costachung/neumorphic)** - Neumorphic is a SwiftUI utility to build Neumorphism Soft UI. (960 ⭐) ⏳

*[↑ Back to top](#contents)*

## 📑 Tab Bar

- **[CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController)** - 【中国特色 TabBar】一行代码实现 Lottie 动画TabBar. (7.0k ⭐)
- **[Tabman](https://github.com/uias/Tabman)** - A powerful paging view controller with interactive indicator bars. (2.9k ⭐)
- **[CircleBar](https://github.com/softhausHQ/CircleBar)** - A fun, easy-to-use tab bar navigation controller for iOS. (872 ⭐) ⏳

*[↑ Back to top](#contents)*

## 🧪 Testing

- **[Quick](https://github.com/Quick/Quick)** - The Swift (and Objective-C) testing framework. (9.8k ⭐)
- **[Nimble](https://github.com/Quick/Nimble)** - A Matcher Framework for Swift and Objective-C. (4.8k ⭐)
- **[swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing)** - Delightful Swift snapshot testing. (4.1k ⭐)
- **[swift-testing](https://github.com/swiftlang/swift-testing)** - A modern, expressive testing package for Swift. (2.1k ⭐)
- **[Cuckoo](https://github.com/Brightify/Cuckoo)** - Boilerplate-free mocking framework for Swift!. (1.7k ⭐)
- **[NSFWDetector](https://github.com/lovoo/NSFWDetector)** - A NSFW (aka porn) detector with CoreML. (1.6k ⭐) ⏳
- **[Difference](https://github.com/krzysztofzablocki/Difference)** - Simple way to identify what is different between 2 instances of any type. Must have for TDD. (1.2k ⭐)
- **[playbook-ios](https://github.com/playbook-ui/playbook-ios)** - A library for isolated developing UI components and automatically taking snapshots of them. (1.2k ⭐) ⏳
- **[swift-corelibs-xctest](https://github.com/swiftlang/swift-corelibs-xctest)** - The XCTest Project, A Swift core library for providing unit test support. (1.2k ⭐)
- **[swift](https://github.com/danger/swift)** - Stop saying "you forgot to …" in code review. (1.1k ⭐)
- **[SwiftyMocky](https://github.com/MakeAWishFoundation/SwiftyMocky)** - Framework for automatic mock generation. Adds a set of handy methods, simplifying testing. (1.1k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🔤 Text / Labels

- **[LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)** - Graceful morphing effects for UILabel written in Swift. (8.1k ⭐)
- **[MarqueeLabel](https://github.com/cbpowell/MarqueeLabel)** - A drop-in replacement for UILabel, which automatically adds a scrolling marquee effect. (4.3k ⭐)
- **[BonMot](https://github.com/Rightpoint/BonMot)** - Beautiful, easy attributed strings in Swift. (3.6k ⭐) ⏳
- **[Atributika](https://github.com/psharanda/Atributika)** - Convert text with HTML tags, links, hashtags, mentions into NSAttributedString. Make them clickable with UILabel drop-in replacement. (1.5k ⭐) ⏳

### TextField

- **[Runestone](https://github.com/simonbs/Runestone)** - Performant plain text editor for iOS with syntax highlighting, line numbers, invisible characters and much more. (3.0k ⭐)
- **[STTextView](https://github.com/krzyzanowskim/STTextView)** - Performant and reusable text view component (TextKit 2), with line numbers and more. (1.5k ⭐)
- **[proton](https://github.com/rajdeep/proton)** - Purely native and extensible rich text editor for iOS and macOS Catalyst apps. (1.4k ⭐)
- **[RichTextKit](https://github.com/danielsaidi/RichTextKit)** - View and edit rich text in Swift & SwiftUI. (1.2k ⭐)
- **[RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView)** - A light-weight UITextView subclass that automatically grows and shrinks. (1.1k ⭐) ⏳

*[↑ Back to top](#contents)*

## 🎭 Transitions / Presentations

- **[Jelly](https://github.com/SebastianBoldt/Jelly)** - Jelly is a library for animated, non-interactive & interactive viewcontroller transitions and presentations. (2.5k ⭐)

*[↑ Back to top](#contents)*

## 🎨 UI Components

### Alerts / Popups

- **[SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages)** - A very flexible message bar for UIKit and SwiftUI. (7.6k ⭐)
- **[SwiftEntryKit](https://github.com/huri000/SwiftEntryKit)** - SwiftEntryKit is a presentation library for iOS. It can be used to easily display overlays within your iOS apps. (6.8k ⭐) ⏳
- **[alerts-and-pickers](https://github.com/dillidon/alerts-and-pickers)** - Advanced usage of UIAlertController and pickers based on it. (5.8k ⭐) ⏳
- **[NotificationBanner](https://github.com/Daltron/NotificationBanner)** - The easiest way to display highly customizable in app notification banners in iOS. (4.9k ⭐) ⏳
- **[JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification)** - Highly customizable & feature rich notifications. SwiftUI compatible. (4.3k ⭐) ⏳
- **[Toast-Swift](https://github.com/scalessec/Toast-Swift)** - A Swift extension that adds toast notifications to the UIView object class. (3.8k ⭐) ⏳
- **[AlertKit](https://github.com/sparrowcode/AlertKit)** - Native alert from Apple Music & Feedback. Contains Done, Heart & Message and other presets. (2.6k ⭐) ⏳
- **[AlertToast](https://github.com/elai950/AlertToast)** - Create Apple-like alerts & toasts using SwiftUI. (2.4k ⭐) ⏳
- **[Toaster](https://github.com/devxoul/Toaster)** - Toast for Swift. (1.9k ⭐) ⏳
- **[Drops](https://github.com/omaralbeik/Drops)** - A µFramework for showing alerts like the one used when copying from pasteboard. (1.0k ⭐) ⏳
- **[JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications)** - An iOS UIView for presenting a minimalistic notification that doesn't block the UI. (937 ⭐) ⏳

### CollectionView

- **[AlignedCollectionViewFlowLayout](https://github.com/mischa-hildebrand/AlignedCollectionViewFlowLayout)** - A collection view layout that gives you control over the horizontal and vertical alignment of the cells. (1.4k ⭐)

### Paging / Page Control

- **[FSPagerView](https://github.com/WenchaoD/FSPagerView)** - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner View, Product Show, Welcome/Guide Pages. (7.4k ⭐) ⏳
- **[Parchment](https://github.com/rechsteiner/Parchment)** - A paging view with a highly customizable menu. (3.5k ⭐) ⏳
- **[JXSegmentedView](https://github.com/pujiaxin33/JXSegmentedView)** - A powerful and easy to use segmented view. (2.9k ⭐)
- **[Segmentio](https://github.com/Yalantis/Segmentio)** - Animated top/bottom segmented control written in Swift. (2.5k ⭐) ⏳
- **[Pageboy](https://github.com/uias/Pageboy)** - A simple, highly informative page view controller. (2.0k ⭐)
- **[TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator)** - A rubber animation pagecontrol. (1.5k ⭐) ⏳

### Sliders

- **[Koloda](https://github.com/Yalantis/Koloda)** - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. (5.4k ⭐) ⏳
- **[Magnetic](https://github.com/efremidze/Magnetic)** - SpriteKit Floating Bubble Picker (inspired by Apple Music). (1.6k ⭐)
- **[Cluster](https://github.com/efremidze/Cluster)** - Easy Map Annotation Clustering. (1.3k ⭐)

### Switches

- **[TKSwitcherCollection](https://github.com/TBXark/TKSwitcherCollection)** - An animation switch collection. (924 ⭐) ⏳

### TableView

- **[SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit)** - Swipeable UITableViewCell/UICollectionViewCell based on the stock Mail.app, implemented in Swift. (6.3k ⭐) ⏳
- **[TDBadgedCell](https://github.com/tmdvs/TDBadgedCell)** - TDBadgedCell is a table view cell class that adds a badge, similar to the badges in Apple's own apps. (1.4k ⭐) ⏳
- **[Carbon](https://github.com/ra1028/Carbon)** - A declarative library for building component-based user interfaces in UITableView and UICollectionView. (1.4k ⭐) ⏳
- **[TimelineTableViewCell](https://github.com/kf99916/TimelineTableViewCell)** - Simple timeline view implemented by UITableViewCell. (1.3k ⭐)

### Other UI

- **[Gemini](https://github.com/shoheiyokoyama/Gemini)** - Gemini is rich scroll based animation framework for iOS, written in Swift. (3.3k ⭐)
- **[Popover](https://github.com/corin8823/Popover)** - Popover is a balloon library like Facebook app. (2.1k ⭐) ⏳
- **[Pulley](https://github.com/52inc/Pulley)** - A library to imitate the iOS 10 Maps UI. (2.0k ⭐) ⏳
- **[Aiolos](https://github.com/IdeasOnCanvas/Aiolos)** - A floating panel for your iOS Apps. (1.6k ⭐)
- **[VisualEffectView](https://github.com/efremidze/VisualEffectView)** - Dynamic blur background view with tint color (UIVisualEffectView subclass). (1.4k ⭐)
- **[Shiny](https://github.com/efremidze/Shiny)** - Iridescent Effect View (inspired by Apple Pay Cash). (839 ⭐)

*[↑ Back to top](#contents)*

## 🎥 Video

- **[lottie-ios](https://github.com/airbnb/lottie-ios)** - An iOS library to natively render After Effects vector animations. (27k ⭐)
- **[epoxy-ios](https://github.com/airbnb/epoxy-ios)** - Epoxy is a suite of declarative UI APIs for building UIKit applications in Swift. (1.3k ⭐)

*[↑ Back to top](#contents)*

## 🌐 Web

- **[gitignore.io](https://github.com/toptal/gitignore.io)** - Create useful .gitignore files for your project. (8.7k ⭐) ⏳
- **[Publish](https://github.com/JohnSundell/Publish)** - A static site generator for Swift developers. (5.0k ⭐) ⏳
- **[Stencil](https://github.com/stencilproject/Stencil)** - Stencil is a simple and powerful template language for Swift. (2.4k ⭐) ⏳
- **[Ignite](https://github.com/twostraws/Ignite)** - A static site generator for Swift developers. (2.1k ⭐)
- **[Plot](https://github.com/JohnSundell/Plot)** - A DSL for writing type-safe HTML, XML and RSS in Swift. (2.0k ⭐) ⏳
- **[Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player)** - Swift library for embedding and controlling YouTube videos in your iOS applications via WKWebView!. (881 ⭐) ⏳

*[↑ Back to top](#contents)*

## 🛠️ Xcode Tools

- **[Font-Awesome](https://github.com/FortAwesome/Font-Awesome)** -  The iconic SVG, font, and CSS toolkit. (76k ⭐)
- **[container](https://github.com/apple/container)** - A tool for creating and running Linux containers using lightweight virtual machines on a Mac. (25k ⭐)
- **[Carthage](https://github.com/Carthage/Carthage)** - A simple, decentralized dependency manager for Cocoa. (15k ⭐)
- **[swift-package-manager](https://github.com/swiftlang/swift-package-manager)** - The Package Manager for the Swift Programming Language. (10k ⭐)
- **[R.swift](https://github.com/mac-cain13/R.swift)** - Strong typed, autocompleted resources like images, fonts and segues in Swift projects. (9.6k ⭐)
- **[SwiftGen](https://github.com/SwiftGen/SwiftGen)** - The Swift code generator for your assets, storyboards, Localizable.strings, - Get rid of all String-based APIs!. (9.5k ⭐) ⏳
- **[ipatool](https://github.com/majd/ipatool)** - Command-line tool that allows searching and downloading app packages (known as ipa files) from the iOS App Store. (8.6k ⭐)
- **[containerization](https://github.com/apple/containerization)** - Containerization is a Swift package for running Linux containers on macOS. (8.3k ⭐)
- **[XcodeGen](https://github.com/yonaskolb/XcodeGen)** - A Swift command line tool for generating your Xcode project. (8.1k ⭐)
- **[Sourcery](https://github.com/krzysztofzablocki/Sourcery)** - Meta-programming for Swift, stop writing boilerplate code. (8.0k ⭐)
- **[CopilotForXcode](https://github.com/github/CopilotForXcode)** - AI coding assistant for Xcode. (5.7k ⭐)
- **[tuist](https://github.com/tuist/tuist)** - A virtual platform team for mobile devs who ship. (5.5k ⭐)
- **[swift-corelibs-foundation](https://github.com/swiftlang/swift-corelibs-foundation)** - The Foundation Project, providing core utilities, internationalization, and OS independence. (5.4k ⭐)
- **[PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit)** - A Swift framework for parsing, formatting and validating international phone numbers. (5.3k ⭐)
- **[xtool](https://github.com/xtool-org/xtool)** - Cross-platform Xcode replacement. Build and deploy iOS apps with SwiftPM on Linux, Windows, macOS. (4.6k ⭐)
- **[xcodes](https://github.com/XcodesOrg/xcodes)** - The best command-line tool to install and switch between multiple versions of Xcode. (4.5k ⭐)
- **[GodEye](https://github.com/zixun/GodEye)** - Automatically display Log, Crash, Network, ANR, Leak, CPU, RAM, FPS, NetFlow, Folder and etc with one line of code based on Swift. (3.9k ⭐) ⏳
- **[sourcekit-lsp](https://github.com/swiftlang/sourcekit-lsp)** - Language Server Protocol implementation for Swift and C-based languages. (3.8k ⭐)
- **[swift-syntax](https://github.com/swiftlang/swift-syntax)** - A set of Swift libraries for parsing, inspecting, generating, and transforming Swift source code. (3.6k ⭐)
- **[XcodeBenchmark](https://github.com/devMEremenko/XcodeBenchmark)** - XcodeBenchmark measures the compilation time of a large codebase on iMac, MacBook, and Mac Pro. (3.6k ⭐)
- **[LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker)** - Find retain cycles / memory leaks sooner. (3.3k ⭐)
- **[Inject](https://github.com/krzysztofzablocki/Inject)** - Hot Reloading for Swift applications!. (3.3k ⭐)
- **[swift-foundation](https://github.com/swiftlang/swift-foundation)** - The Foundation project. (2.6k ⭐)
- **[Mint](https://github.com/yonaskolb/Mint)** - A package manager that installs and runs executable Swift packages. (2.5k ⭐)
- **[GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift)** - Shows FPS, CPU and memory usage, device model, app and iOS versions above the status bar. (2.3k ⭐)
- **[XcodeProj](https://github.com/tuist/XcodeProj)** - Read, update and write your Xcode projects. (2.2k ⭐)
- **[swift-build](https://github.com/swiftlang/swift-build)** - A high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package Manager. (2.2k ⭐)
- **[PythonKit](https://github.com/pvieito/PythonKit)** - Swift framework to interact with Python. (2.2k ⭐)
- **[Peekaboo](https://github.com/steipete/Peekaboo)** - Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots of applications. (2.1k ⭐)
- **[StateMachine](https://github.com/Tinder/StateMachine)** - A Kotlin and Swift DSL for finite state machine. (2.1k ⭐) ⏳
- **[SFSafeSymbols](https://github.com/SFSafeSymbols/SFSafeSymbols)** - Safely access Apple's SF Symbols using static typing. (1.9k ⭐)
- **[Splash](https://github.com/JohnSundell/Splash)** - A fast, lightweight and flexible Swift syntax highlighter for blogs, tools and fun!. (1.9k ⭐) ⏳
- **[swift-openapi-generator](https://github.com/apple/swift-openapi-generator)** - Generate Swift client and server code from an OpenAPI document. (1.8k ⭐)
- **[XCLogParser](https://github.com/MobileNativeFoundation/XCLogParser)** - Tool to parse Xcode and xcodebuild logs stored in the xcactivitylog format. (1.8k ⭐)
- **[DebugSwift](https://github.com/DebugSwift/DebugSwift)** - A toolkit to make debugging iOS applications easier. (1.6k ⭐)
- **[xcbeautify](https://github.com/cpisciotta/xcbeautify)** - A little beautifier tool for xcodebuild. (1.4k ⭐)
- **[Sitrep](https://github.com/twostraws/Sitrep)** - A source code analyzer for Swift projects. (1.3k ⭐)
- **[SwiftTerm](https://github.com/migueldeicaza/SwiftTerm)** - Xterm/VT100 Terminal emulator in Swift. (1.3k ⭐)
- **[mac-monitor](https://github.com/Brandon7CC/mac-monitor)** - "The missing ProcMon for macOS": Mac Monitor records Endpoint Security events and displays them graphically. (1.3k ⭐)
- **[swift-sdk](https://github.com/modelcontextprotocol/swift-sdk)** - The official Swift SDK for Model Context Protocol servers and clients. (1.2k ⭐)
- **[AXe](https://github.com/cameroncooke/AXe)** - AXe is a CLI tool for interacting with Simulators using Apple's Private Accessibility APIs. (1.2k ⭐)
- **[swift-atomics](https://github.com/apple/swift-atomics)** - Low-level atomic operations for Swift. (1.2k ⭐)
- **[supabase-swift](https://github.com/supabase/supabase-swift)** - A Swift SDK for Supabase. (1.2k ⭐)
- **[swift-win32](https://github.com/compnerd/swift-win32)** - A Windows application framework for Swift. (1.2k ⭐)
- **[Diagnostics](https://github.com/AvdLee/Diagnostics)** - Allow users to easily share Diagnostics with your support team to improve the flow of fixing bugs. (1.2k ⭐)
- **[swift-java](https://github.com/swiftlang/swift-java)** - Java interopability support for Swift. (1.2k ⭐)
- **[SwiftInfo](https://github.com/rockbruno/SwiftInfo)** - Extract and analyze the evolution of an iOS app's code. (1.2k ⭐)
- **[XCMetrics](https://github.com/spotify/XCMetrics)** - XCMetrics is the easiest way to collect Xcode build metrics and improve developer productivity. (1.2k ⭐) ⏳
- **[DVIA-v2](https://github.com/prateek147/DVIA-v2)** - Damn Vulnerable iOS App (DVIA) is an iOS application that is damn vulnerable for penetration testing. (1.1k ⭐) ⏳
- **[sentry-cocoa](https://github.com/getsentry/sentry-cocoa)** - The official Sentry SDK for iOS, tvOS, macOS, watchOS, iPadOS and visionOS. (1.0k ⭐)
- **[swift-embedded-examples](https://github.com/swiftlang/swift-embedded-examples)** - A collection of example projects using Embedded Swift. (1.0k ⭐)
- **[swift-parsing](https://github.com/pointfreeco/swift-parsing)** - A library for turning nebulous data into well-structured data. (974 ⭐)
- **[soto](https://github.com/soto-project/soto)** - Swift SDK for AWS that works on Linux, macOS and iOS. (970 ⭐)
- **[EVReflection](https://github.com/evermeer/EVReflection)** - Reflection based (Dictionary, CKRecord, NSManagedObject, Realm, JSON and XML) object mapping. (963 ⭐)
- **[GraphQL](https://github.com/GraphQLSwift/GraphQL)** - The Swift GraphQL implementation for macOS and Linux. (962 ⭐)
- **[xcdiff](https://github.com/bloomberg/xcdiff)** - A tool which helps you diff xcodeproj files. (954 ⭐)
- **[mapbox-navigation-ios](https://github.com/mapbox/mapbox-navigation-ios)** - Turn-by-turn navigation logic and UI in Swift on iOS. (915 ⭐)
- **[line-sdk-ios-swift](https://github.com/line/line-sdk-ios-swift)** - Provides a modern way of implementing LINE APIs. (874 ⭐)
- **[swift-sdk](https://github.com/watson-developer-cloud/swift-sdk)** - The Watson Swift SDK enables developers to quickly add Watson Cognitive Computing services to their Swift applications. (873 ⭐)
- **[BitcoinKit](https://github.com/yenom/BitcoinKit)** - Bitcoin protocol toolkit for Swift. (869 ⭐) ⏳
- **[json2swift](https://github.com/ijoshsmith/json2swift)** - A macOS command line tool that generates excellent Swift data models based on JSON data. (696 ⭐) ⏳

*[↑ Back to top](#contents)*
