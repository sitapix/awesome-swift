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

- **[Alamofire](https://github.com/Alamofire/Alamofire)** - Elegant HTTP Networking in Swift.
- **[Moya](https://github.com/Moya/Moya)** - Network abstraction layer written in Swift. ⏳
- **[Starscream](https://github.com/daltoniam/Starscream)** - Websockets in swift for iOS and MacOS. ⏳
- **[swift-nio](https://github.com/apple/swift-nio)** - Event-driven network application framework for high performance protocol servers & clients, non-blocking.
- **[Reachability.swift](https://github.com/ashleymills/Reachability.swift)** - Replacement for Apple's Reachability re-written in Swift with closures. ⏳
- **[Pulse](https://github.com/kean/Pulse)** - Network logger for Apple platforms.
- **[apollo-ios](https://github.com/apollographql/apollo-ios)** - A strongly-typed, caching GraphQL client for iOS, written in Swift.
- **[Just](https://github.com/dduan/Just)** - Swift HTTP for Humans. ⏳
- **[Networking](https://github.com/3lvis/Networking)** - Swift HTTP Networking with stubbing and caching support.
- **[Connectivity](https://github.com/rwbutler/Connectivity)** - Makes Internet connectivity detection more robust by detecting Wi-Fi networks without Internet access. ⏳
- **[RxAlamofire](https://github.com/RxSwiftCommunity/RxAlamofire)** - RxSwift wrapper around the elegant HTTP networking in Swift Alamofire. ⏳
- **[SwiftLinkPreview](https://github.com/LeonardoCardoso/SwiftLinkPreview)** - It makes a preview from an URL, grabbing all the information such as title, relevant texts and images. ⏳
- **[netfox](https://github.com/kasketis/netfox)** - A lightweight, one line setup, iOS / MacOS network debugging library!. ⏳
- **[Bagel](https://github.com/yagiz/Bagel)** - a little native network debugging tool for iOS. ⏳
- **[Networking](https://github.com/freshOS/Networking)** - Concise networking code leveraging async-await, Decodable & Generics.
- **[grpc-swift](https://github.com/grpc/grpc-swift)** - The Swift language implementation of gRPC.
- **[CocoaMQTT](https://github.com/emqx/CocoaMQTT)** - MQTT 5.0 client library for iOS and macOS written in Swift.
- **[swift-http-types](https://github.com/apple/swift-http-types)** - Version-independent HTTP currency types for Swift.
- **[swift-protobuf](https://github.com/apple/swift-protobuf)** - Plugin and runtime library for using protobuf with Swift.
- **[protobuf-swift](https://github.com/alexeyxo/protobuf-swift)** - Google ProtocolBuffers for Apple Swift. ⏳
- **[Tiercel](https://github.com/Danie1s/Tiercel)** - 简单易用、功能丰富的纯 Swift 下载框架.

*[↑ Back to top](#contents)*

## 🧭 App Routing

- **[URLNavigator](https://github.com/devxoul/URLNavigator)** - Elegant URL Routing for Swift. ⏳

*[↑ Back to top](#contents)*

## 🛒 App Store / In-App Purchases

- **[SwiftyStoreKit](https://github.com/bizz84/SwiftyStoreKit)** - Lightweight In App Purchases Swift framework for iOS 8.0+, tvOS 9.0+ and macOS 10.10+. ⏳
- **[purchases-ios](https://github.com/RevenueCat/purchases-ios)** - In-app purchases and subscriptions made easy. Support for iOS, watchOS, tvOS, macOS, and visionOS.
- **[merchantkit](https://github.com/benjaminmayo/merchantkit)** - A modern In-App Purchases management framework for iOS. ⏳
- **[appstoreconnect-swift-sdk](https://github.com/AvdLee/appstoreconnect-swift-sdk)** - The Swift SDK to work with the App Store Connect API from Apple.
- **[Siren](https://github.com/ArtSabintsev/Siren)** - Notify users when a new version of your app is available and prompt them to upgrade. ⏳

*[↑ Back to top](#contents)*

## 🏗️ Architecture Patterns

- **[swift-composable-architecture](https://github.com/pointfreeco/swift-composable-architecture)** - A library for building applications in a consistent and understandable way, with composition, testing, and ergonomics in mind.
- **[ReSwift](https://github.com/ReSwift/ReSwift)** - Unidirectional Data Flow in Swift - Inspired by Redux. ⏳
- **[ReactorKit](https://github.com/ReactorKit/ReactorKit)** - A library for reactive and unidirectional Swift applications.
- **[clean-architecture-swiftui](https://github.com/nalexn/clean-architecture-swiftui)** - SwiftUI sample app using Clean Architecture. Examples of working with SwiftData persistence, networking, dependency injection, unit testing, and more.
- **[ModernCleanArchitectureSwiftUI](https://github.com/sergdort/ModernCleanArchitectureSwiftUI)** - Example of Modern Domain Driven modularisation of iOS apps. ⏳
- **[XCoordinator](https://github.com/QuickBirdEng/XCoordinator)** - Powerful navigation library for iOS based on the coordinator pattern.
- **[RxFlow](https://github.com/RxSwiftCommunity/RxFlow)** - RxFlow is a navigation framework for iOS applications based on a Reactive Flow Coordinator pattern.
- **[SwiftHub](https://github.com/khoren93/SwiftHub)** - GitHub iOS client in RxSwift and MVVM-C clean architecture.
- **[stinsen](https://github.com/rundfunk47/stinsen)** - Coordinators in SwiftUI. Simple, powerful and elegant. ⏳
- **[route-composer](https://github.com/ekazaev/route-composer)** - Protocol oriented, Cocoa UI abstractions based library that helps to handle view controllers composition, navigation and deep linking tasks.
- **[iOSSampleApp](https://github.com/igorkulman/iOSSampleApp)** - Sample iOS app demonstrating Coordinators, Dependency Injection, MVVM, Binding.

*[↑ Back to top](#contents)*

## 🥽 AR / VR

- **[Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit)** - A curated list of awesome ARKit projects and resources. ⏳
- **[ARuler](https://github.com/duzexu/ARuler)** - Measure distance using apple ARKit.
- **[ARShooter](https://github.com/farice/ARShooter)** - A demo Augmented Reality shooter made with ARKit in Swift (iOS 11).
- **[Fisheye](https://github.com/hanton/Fisheye)** - iOS 360 panorama video player with Metal rendering support.

*[↑ Back to top](#contents)*

## 🔊 Audio

- **[AudioKit](https://github.com/AudioKit/AudioKit)** - Audio synthesis, processing, & analysis platform for iOS, macOS and tvOS.
- **[SwiftySound](https://github.com/adamcichy/SwiftySound)** - SwiftySound is a simple library that lets you play sounds with a single line of code. ⏳
- **[FDWaveformView](https://github.com/fulldecent/FDWaveformView)** - Reads an audio file and displays the waveform.
- **[DSWaveformImage](https://github.com/dmrschmidt/DSWaveformImage)** - Generate waveform images from audio files on iOS, macOS & visionOS in Swift. Native SwiftUI & UIKit views.
- **[FluidAudio](https://github.com/FluidInference/FluidAudio)** - Frontier CoreML audio models in your apps - text-to-speech, speech-to-text, voice activity detection, and speaker diarization.
- **[WhisperKit](https://github.com/argmaxinc/WhisperKit)** - On-device Speech Recognition for Apple Silicon.

*[↑ Back to top](#contents)*

## 🔐 Authentication / Security

- **[KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess)** - Simple Swift wrapper for Keychain that works on iOS, watchOS, tvOS and macOS. ⏳
- **[keychain-swift](https://github.com/evgenyneu/keychain-swift)** - Helper functions for saving text in Keychain securely for iOS, OS X, tvOS and watchOS. ⏳
- **[Locksmith](https://github.com/matthewpalmer/Locksmith)** - A powerful, protocol-oriented library for working with the keychain in Swift. ⏳
- **[OAuthSwift](https://github.com/OAuthSwift/OAuthSwift)** - Swift based OAuth library for iOS. ⏳
- **[OAuth2](https://github.com/p2/OAuth2)** - OAuth2 framework for macOS and iOS, written in Swift. ⏳
- **[facebook-ios-sdk](https://github.com/facebook/facebook-ios-sdk)** - Used to integrate the Facebook Platform with your iOS & tvOS apps.
- **[IOSSecuritySuite](https://github.com/securing/IOSSecuritySuite)** - iOS platform security & anti-tampering Swift library.
- **[SwiftyRSA](https://github.com/TakeScoop/SwiftyRSA)** - RSA public/private key encryption in Swift. ⏳
- **[Authenticator](https://github.com/mattrubin/Authenticator)** - Two-Factor Authentication Client for iOS.
- **[ios-application](https://github.com/raivo-otp/ios-application)** - A native, lightweight and secure one-time-password (OTP) client built for iOS; Raivo OTP!.
- **[passforios](https://github.com/mssun/passforios)** - Pass for iOS - an iOS client compatible with Pass command line application.

*[↑ Back to top](#contents)*

## 💾 Caching

- **[Cache](https://github.com/hyperoslo/Cache)** - Nothing but Cache.

*[↑ Back to top](#contents)*

## 📅 Calendar / Date

- **[JTAppleCalendar](https://github.com/patchthecode/JTAppleCalendar)** - The Unofficial Apple iOS Swift Calendar View. Swift calendar Library. iOS calendar Control. 100% Customizable. ⏳
- **[CalendarKit](https://github.com/richardtop/CalendarKit)** - Calendar for Apple platforms in Swift.
- **[time](https://github.com/davedelong/time)** - Robust and type-safe date and time calculations for Swift. ⏳
- **[DateHelper](https://github.com/melvitax/DateHelper)** - A Swift Date extension helper. ⏳

*[↑ Back to top](#contents)*

## 📊 Charts / Graphs

- **[AAChartKit-Swift](https://github.com/AAChartModel/AAChartKit-Swift)** - An elegant modern declarative data visualization chart framework for iOS, iPadOS and macOS.
- **[Swift-Charts-Examples](https://github.com/jordibruin/Swift-Charts-Examples)** - An overview of the different types of charts you can make with Swift Charts.
- **[SwiftUICharts](https://github.com/willdale/SwiftUICharts)** - A charts / plotting library for SwiftUI. Works on macOS, iOS, watchOS, and tvOS.
-**[KSChart](https://github.com/sevtin/KSChart)** - k line chart with MA/EMA/MACD/KDJ/BOLL/RSI/WR/AVG indicators. Swift5, 60FPS stable.
- **[Cosmos](https://github.com/evgenyneu/Cosmos)** - A star rating control for iOS/tvOS written in Swift. ⏳

*[↑ Back to top](#contents)*

## 💬 Chat / Messaging

- ****[MessageKit](https://github.com/MessageKit/MessageKit)**** - A community-driven replacement for JSQMessagesViewController
- **[Chatto](https://github.com/badoo/Chatto)** - A lightweight framework to build chat applications, made in Swift.
- **[Chat](https://github.com/exyte/Chat)** - A SwiftUI Chat UI framework with fully customizable message cells and a built-in media picker.
- **[InputBarAccessoryView](https://github.com/nathantannar4/InputBarAccessoryView)** - A simple and easily customizable InputAccessoryView for making powerful input bars with autocomplete and attachments.
- **[ChatLayout](https://github.com/ekazaev/ChatLayout)** - ChatLayout is an alternative solution to MessageKit. It uses custom UICollectionViewLayout.

*[↑ Back to top](#contents)*

## ⌨️ CLI / Command Line

- **[swift-argument-parser](https://github.com/apple/swift-argument-parser)** - Straightforward, type-safe argument parsing for Swift.
- **[Rainbow](https://github.com/onevcat/Rainbow)** - Delightful console output for Swift developers.
- **[SwiftShell](https://github.com/kareman/SwiftShell)** - A Swift framework for shell scripting.
- **[ShellOut](https://github.com/JohnSundell/ShellOut)** - Easily run shell commands from a Swift script or command line tool. ⏳
- **[swift-sh](https://github.com/mxcl/swift-sh)** - Easily script with third-party Swift dependencies.

*[↑ Back to top](#contents)*

## ✨ Code Quality

- **[SwiftLint](https://github.com/realm/SwiftLint)** - A tool to enforce Swift style and conventions.
- **[SwiftFormat](https://github.com/nicklockwood/SwiftFormat)** - A command-line tool and Xcode Extension for formatting Swift code.
- **[swift-format](https://github.com/swiftlang/swift-format)** - Formatting technology for Swift source code.
- **[periphery](https://github.com/peripheryapp/periphery)** - A tool to identify unused code in Swift projects.
- **[FengNiao](https://github.com/onevcat/FengNiao)** - A command line tool for cleaning unused resources in Xcode.

*[↑ Back to top](#contents)*

## ⚡ Concurrency / Async

- **[PromiseKit](https://github.com/mxcl/PromiseKit)** - Promises for Swift & ObjC.
- **[swift-async-algorithms](https://github.com/apple/swift-async-algorithms)** - Async Algorithms for Swift.
- **[Async](https://github.com/duemunk/Async)** - Syntactic sugar in Swift for asynchronous dispatches in Grand Central Dispatch. ⏳
- **[Then](https://github.com/freshOS/Then)** - Tame async code with battle-tested promises. ⏳
- **[Queuer](https://github.com/FabrizioBrancati/Queuer)** - Queuer is a queue manager, built on top of OperationQueue and Dispatch (aka GCD).
- **[Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift)** - Bolts is a collection of low-level libraries designed to make developing mobile apps easier. ⏳
- **[ConcurrencyRecipes](https://github.com/mattmassicotte/ConcurrencyRecipes)** - Practical solutions to problems with Swift Concurrency.
- **[Watchdog](https://github.com/wojteklu/Watchdog)** - Class for logging excessive blocking on the main thread. ⏳

*[↑ Back to top](#contents)*

## 🔒 Cryptography

- **[CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift)** - CryptoSwift is a growing collection of standard and secure cryptographic algorithms implemented in Swift.
- **[RNCryptor](https://github.com/RNCryptor/RNCryptor)** - CCCryptor (AES encryption) wrappers for iOS and Mac in Swift.

*[↑ Back to top](#contents)*

## 🧮 Data Structures / Algorithms

- **[swift-algorithm-club](https://github.com/kodecocodes/swift-algorithm-club)** - Algorithms and data structures in Swift, with explanations!. ⏳
- **[swift-algorithms](https://github.com/apple/swift-algorithms)** - Commonly used sequence and collection algorithms for Swift.
- **[swift-collections](https://github.com/apple/swift-collections)** - Commonly used data structures for Swift.
- **[LeetCode-Swift](https://github.com/soapyigu/LeetCode-Swift)** - Solutions to LeetCode by Swift. ⏳

*[↑ Back to top](#contents)*

## 🗄️ Database

- **[SQLite.swift](https://github.com/stephencelis/SQLite.swift)** - A type-safe, Swift-language layer over SQLite3.
- **[GRDB.swift](https://github.com/groue/GRDB.swift)** - A toolkit for SQLite databases, with a focus on application development.
- **[SQLiteData](https://github.com/pointfreeco/sqlite-data)** - A fast, lightweight replacement for SwiftData, powered by SQL and supporting CloudKit synchronization.
- **[CoreStore](https://github.com/JohnEstropia/CoreStore)** - Unleashing the real power of Core Data with the elegance and safety of Swift. ⏳
- **[IceCream](https://github.com/caiyue1993/IceCream)** - Sync Realm Database with CloudKit.
- **[Sync](https://github.com/3lvis/Sync)** - JSON to Core Data and back. Swift Core Data Sync. ⏳
- **[fluent](https://github.com/vapor/fluent)** - Vapor ORM (queries, models, and relations) for NoSQL and SQL databases.

*[↑ Back to top](#contents)*

## 💉 Dependency Injection

- **[Swinject](https://github.com/Swinject/Swinject)** - Dependency injection framework for Swift with iOS/macOS/Linux.
- **[Factory](https://github.com/hmlongco/Factory)** - A modern approach to Container-Based Dependency Injection for Swift and SwiftUI.
- **[Resolver](https://github.com/hmlongco/Resolver)** - Swift Ultralight Dependency Injection / Service Locator framework. ⏳
- **[needle](https://github.com/uber/needle)** - Compile-time safe Swift dependency injection framework.
- **[Cleanse](https://github.com/square/Cleanse)** - Lightweight Swift Dependency Injection Framework. ⏳
- **[Dip](https://github.com/AliSoftware/Dip)** - Simple Swift Dependency container. Use protocols to resolve your dependencies and avoid singletons / sharedInstances!. ⏳
- **[swift-dependencies](https://github.com/pointfreeco/swift-dependencies)** - A dependency management library inspired by SwiftUI's "environment.".

*[↑ Back to top](#contents)*

## 📖 Documentation

- **[swift-docc](https://github.com/swiftlang/swift-docc)** - Documentation compiler that produces rich API reference documentation and interactive tutorials for your Swift framework or package.

*[↑ Back to top](#contents)*

## 🧰 Extensions / Utilities

- **[SwifterSwift](https://github.com/SwifterSwift/SwifterSwift)** - A handy collection of more than 500 native Swift extensions to boost your productivity.
- **[EZSwiftExtensions](https://github.com/Esqarrouth/EZSwiftExtensions)** - How Swift standard types and classes were supposed to work. ⏳
- **[Then](https://github.com/devxoul/Then)** - Super sweet syntactic sugar for Swift initializers.
- **[Dollar](https://github.com/ankurp/Dollar)** - A functional tool-belt for Swift Language similar to Lo-Dash or Underscore.js in Javascript. ⏳
- **[swift-overture](https://github.com/pointfreeco/swift-overture)** - A library for function composition. ⏳
- **[DeviceKit](https://github.com/devicekit/DeviceKit)** - DeviceKit is a value-type replacement of UIDevice.
- **[Device](https://github.com/Ekhoo/Device)** - Light weight tool for detecting the current device and screen size written in swift.
- **[swift-tagged](https://github.com/pointfreeco/swift-tagged)** - A wrapper type for safer, expressive code.
- **[swift-case-paths](https://github.com/pointfreeco/swift-case-paths)** - Case paths extends the key path hierarchy to enum cases.
- **[Runtime](https://github.com/wickwirew/Runtime)** - A Swift Runtime library for viewing type info, and the dynamic getting and setting of properties. ⏳

*[↑ Back to top](#contents)*

## 📁 File Management

- **[Files](https://github.com/JohnSundell/Files)** - A nicer way to handle files & folders in Swift.
- **[Disk](https://github.com/saoudrizwan/Disk)** - Easily persist structs, images, and data on iOS. ⏳
- **[FileKit](https://github.com/nvzqz/FileKit)** - Simple and expressive file management in Swift. ⏳
- **[PathKit](https://github.com/kylef/PathKit)** - Effortless path operations in Swift. ⏳
- **[Zip](https://github.com/marmelroy/Zip)** - Swift framework for zipping and unzipping files. ⏳
- **[ZIPFoundation](https://github.com/weichsel/ZIPFoundation)** - Effortless ZIP Handling in Swift.
- **[Path.swift](https://github.com/mxcl/Path.swift)** - Delightful, robust, cross-platform and chainable file-pathing functions.
- **[swift-system](https://github.com/apple/swift-system)** - Low-level system calls and types for Swift.

*[↑ Back to top](#contents)*

## 📝 Forms

- **[Eureka](https://github.com/xmartlabs/Eureka)** - Elegant iOS form builder in Swift. ⏳

*[↑ Back to top](#contents)*

## 🎮 Games

- **[SwiftGodot](https://github.com/migueldeicaza/SwiftGodot)** - New Godot bindings for Swift.

*[↑ Back to top](#contents)*

## 🔌 Hardware

- **[RxBluetoothKit](https://github.com/Polidea/RxBluetoothKit)** - iOS & MacOS Bluetooth library for RxSwift. ⏳
- **[SwiftLocation](https://github.com/malcommac/SwiftLocation)** - Async/Await CLLocationManager Wrapper for Apple Platforms. ⏳
- **[LocoKit](https://github.com/sobri909/LocoKit)** - Location, motion, and activity recording framework for iOS.
- **[SwiftyGPIO](https://github.com/uraimo/SwiftyGPIO)** - A Swift library for hardware projects on Linux/ARM boards with support for GPIOs/SPI/I2C/PWM/UART/1Wire. ⏳
- **[BeaconEmitter](https://github.com/lgaches/BeaconEmitter)** - Turn your Mac as an iBeacon. ⏳
- **[BLEUnlock](https://github.com/ts1/BLEUnlock)** - Lock/unlock your Mac with your iPhone, Apple Watch, or any other Bluetooth LE devices. ⏳
- **[WebRTC-iOS](https://github.com/stasel/WebRTC-iOS)** - A simple native WebRTC demo iOS app using swift.

*[↑ Back to top](#contents)*

## 🖼️ Images

### Image Loading

- **[Kingfisher](https://github.com/onevcat/Kingfisher)** - A lightweight, pure-Swift library for downloading and caching images from the web.
- **[Nuke](https://github.com/kean/Nuke)** - Image loading system.
- **[SDWebImageSwiftUI](https://github.com/SDWebImage/SDWebImageSwiftUI)** - SwiftUI Image loading and Animation framework powered by SDWebImage.
- **[url-image](https://github.com/dmytro-anokhin/url-image)** - AsyncImage before iOS 15. Lightweight, pure SwiftUI Image view. ⏳

### Image Picking

- **[ImagePicker](https://github.com/hyperoslo/ImagePicker)** - Reinventing the way ImagePicker works. ⏳
- **[YPImagePicker](https://github.com/Yummypets/YPImagePicker)** - Instagram-like image picker & filters for iOS.
- **[DKImagePickerController](https://github.com/zhangao0086/DKImagePickerController)** - Image Picker Controller for iOS written in Swift 4 & 5. ⏳
- **[BSImagePicker](https://github.com/mikaoj/BSImagePicker)** - A multiple image picker for iOS. ⏳
- **[ZLPhotoBrowser](https://github.com/longitachi/ZLPhotoBrowser)** - Wechat-like image picker. Support select photos, videos, gif and livePhoto.
- **[HXPhotoPicker](https://github.com/SilenceLove/HXPhotoPicker)** - Photo/video picker - supports LivePhoto, GIF, 3DTouch preview, editing.
- **[Paparazzo](https://github.com/avito-tech/Paparazzo)** - Custom iOS camera and photo picker with editing capabilities.
- **[WeScan](https://github.com/WeTransferArchive/WeScan)** - Document Scanning Made Easy for iOS. ⏳

### Image Processing

- **[GPUImage2](https://github.com/BradLarson/GPUImage2)** - GPUImage 2 is a BSD-licensed Swift framework for GPU-accelerated video and image processing. ⏳
- **[GPUImage3](https://github.com/BradLarson/GPUImage3)** - GPUImage 3 is a BSD-licensed Swift framework for GPU-accelerated video and image processing using Metal. ⏳
- **[Mantis](https://github.com/guoyingtao/Mantis)** - An iOS Image cropping library, which mimics the Photo App written in Swift.

### Image Viewing

- **[SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser)** - Simple PhotoBrowser/Viewer inspired by facebook, twitter photo browsers written by swift.
- **[Lightbox](https://github.com/hyperoslo/Lightbox)** - A convenient and easy to use image viewer for your iOS app. ⏳
- **[PhotoBrowser](https://github.com/JiongXing/PhotoBrowser)** - Elegant photo browser in Swift.
- **[ImageSlideshow](https://github.com/zvonicek/ImageSlideshow)** - Swift image slideshow with circular scrolling, timer and full screen viewer. ⏳
- **[ImageViewer.swift](https://github.com/michaelhenry/ImageViewer.swift)** - An easy to use Image Viewer that is inspired by Facebook. ⏳

### GIF

- **[Gifu](https://github.com/kaishin/Gifu)** - High-performance animated GIF support for iOS in Swift.
- **[SwiftyGif](https://github.com/alexiscreuzot/SwiftyGif)** - High performance GIF engine. ⏳
- **[APNGKit](https://github.com/onevcat/APNGKit)** - High performance and delightful way to play with APNG format in iOS. ⏳

### QR Code

- **[EFQRCode](https://github.com/EFPrefix/EFQRCode)** - A better way to operate QRCode in Swift, support iOS, macOS, watchOS, tvOS, and/or visionOS.
- **[QRCodeReader.swift](https://github.com/yannickl/QRCodeReader.swift)** - Simple QRCode reader in Swift. ⏳
- **[BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner)** - A simple and beautiful barcode scanner. ⏳

*[↑ Back to top](#contents)*

## 📋 JSON / Parsing

- **[SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)** - The better way to deal with JSON data in Swift.
- **[ObjectMapper](https://github.com/tristanhimmelman/ObjectMapper)** - Simple JSON Object mapping written in Swift. ⏳
- **[HandyJSON](https://github.com/alibaba/HandyJSON)** - A handy swift json-object serialization/deserialization library. ⏳
- **[AnyCodable](https://github.com/Flight-School/AnyCodable)** - Type-erased wrappers for Encodable, Decodable, and Codable values. ⏳
- **[mapper](https://github.com/lyft/mapper)** - A JSON deserialization library for Swift. ⏳
- **[SwiftyJSONAccelerator](https://github.com/insanoid/SwiftyJSONAccelerator)** - macOS app to generate Swift 5 code for models from JSON (with Codeable).

### XML / HTML

- **[SwiftSoup](https://github.com/scinfu/SwiftSoup)** - SwiftSoup: Pure Swift HTML Parser, with best of DOM, CSS, and jquery.
- **[Kanna](https://github.com/tid-kijyun/Kanna)** - Kanna is an XML/HTML parser for Swift.
- **[SWXMLHash](https://github.com/drmohundro/SWXMLHash)** - Simple XML parsing in Swift.
- **[Fuzi](https://github.com/cezheng/Fuzi)** - A fast & lightweight XML & HTML parser in Swift with XPath & CSS support. ⏳

### YAML

- **[Yams](https://github.com/jpsim/Yams)** - A Sweet and Swifty YAML parser.

### CSV

- **[SwiftCSV](https://github.com/swiftcsv/SwiftCSV)** - CSV parser for Swift.

### RSS / Feed

- **[FeedKit](https://github.com/nmdias/FeedKit)** - FeedKit is a Swift library for Reading and Generating RSS, Atom, and JSON feeds.

*[↑ Back to top](#contents)*

## ⌨️ Keyboard

- **[IQKeyboardManager](https://github.com/hackiftekhar/IQKeyboardManager)** - Codeless drop-in universal library allows to prevent issues of keyboard sliding up and cover UITextField/UITextView.
- **[KeyboardLayoutGuide](https://github.com/freshOS/KeyboardLayoutGuide)** - KeyboardLayoutGuide, back from when it didn't exist. ⏳
- **[KeyboardKit](https://github.com/KeyboardKit/KeyboardKit)** - Create amazing custom iOS keyboards with Swift & SwiftUI.

*[↑ Back to top](#contents)*

## 📐 Layout

- **[SnapKit](https://github.com/SnapKit/SnapKit)** - A Swift Autolayout DSL for iOS & OS X.
- **[Cartography](https://github.com/robb/Cartography)** - A declarative Auto Layout DSL for Swift.
- **[TinyConstraints](https://github.com/roberthein/TinyConstraints)** - Nothing but sugar. ⏳
- **[Stevia](https://github.com/freshOS/Stevia)** - Concise Autolayout code.
- **[PinLayout](https://github.com/layoutBox/PinLayout)** - Fast Swift Views layouting without auto layout. No magic, pure code, full control and blazing fast.
- **[FlexLayout](https://github.com/layoutBox/FlexLayout)** - FlexLayout adds a nice Swift interface to the highly optimized facebook/yoga flexbox implementation.
- **[Paralayout](https://github.com/square/Paralayout)** - Paralayout is a set of simple, useful, and straightforward utilities that enable pixel-perfect layout in iOS.
- **[wtfautolayout](https://github.com/johnpatrickmorgan/wtfautolayout)** - The source code for Why The Failure, Auto Layout?. ⏳

*[↑ Back to top](#contents)*

## 🌍 Localization

- **[BartyCrouch](https://github.com/FlineDev/BartyCrouch)** - Localization/I18n: Incrementally update/translate your Strings files from .swift, .h, .m(m), .storyboard or .xib files. ⏳
- **[iOSLocalizationEditor](https://github.com/igorkulman/iOSLocalizationEditor)** - Simple macOS editor app to help you manage iOS and macOS app localizations. ⏳

*[↑ Back to top](#contents)*

## 📜 Logging

- **[SwiftyBeaver](https://github.com/SwiftyBeaver/SwiftyBeaver)** - Convenient & secure logging during development & release in Swift 4 & 5. ⏳
- **[swift-log](https://github.com/apple/swift-log)** - A Logging API for Swift.
- **[XCGLogger](https://github.com/DaveWoodCom/XCGLogger)** - A debug log framework for use in Swift projects. ⏳
- **[Willow](https://github.com/Nike-Inc/Willow)** - Willow is a powerful, yet lightweight logging library written in Swift. ⏳

*[↑ Back to top](#contents)*

## 🤖 Machine Learning / AI

- **[swift-coreml-diffusers](https://github.com/huggingface/swift-coreml-diffusers)** - Swift app demonstrating Core ML Stable Diffusion.
- **[swift-transformers](https://github.com/huggingface/swift-transformers)** - Swift Package to implement a transformers-like API in Swift.
- **[mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples)** - Examples using MLX Swift.
- **[OpenAI](https://github.com/MacPaw/OpenAI)** - Swift community driven package for OpenAI public API.
- **[OpenAISwift](https://github.com/adamrushy/OpenAISwift)** - This is a wrapper library around the ChatGPT and OpenAI HTTP API. ⏳
- **[LLMFarm](https://github.com/guinmoon/LLMFarm)** - llama and other large language models on iOS and MacOS offline using GGML library.
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
- **[Clipy](https://github.com/Clipy/Clipy)** - Clipboard extension app for macOS. ⏳
- **[Gifski](https://github.com/sindresorhus/Gifski)** - Convert videos to high-quality GIFs on your Mac.
- **[XcodesApp](https://github.com/XcodesOrg/XcodesApp)** - The easiest way to install and switch between multiple versions of Xcode - with a mouse click.
- **[MochiDiffusion](https://github.com/MochiDiffusion/MochiDiffusion)** - Run Stable Diffusion on Mac natively.
- **[Loop](https://github.com/MrKai77/Loop)** - Window management made elegant.
- **[WWDC](https://github.com/insidegui/WWDC)** - The unofficial WWDC app for macOS.
- **[ControlRoom](https://github.com/twostraws/ControlRoom)** - A macOS app to control the Xcode Simulator.
- **[MeetingBar](https://github.com/leits/MeetingBar)** - Your meetings at your fingertips in the macOS menu bar.
- **[eqMac](https://github.com/bitgapp/eqMac)** - macOS System-wide Audio Equalizer & Volume Mixer.
- **[noTunes](https://github.com/tombonez/noTunes)** - A simple macOS application that will prevent iTunes or Apple Music from launching. ⏳
- **[Lunar](https://github.com/alin23/Lunar)** - Intelligent adaptive brightness for your external monitors.
- **[uPic](https://github.com/gee1k/uPic)** - uPic is a native, powerful, beautiful and simple picture and file upload tool for macOS.
- **[Applite](https://github.com/milanvarady/Applite)** - User-friendly GUI macOS application for Homebrew Casks.
- **[Latest](https://github.com/mangerlahn/Latest)** - A small utility app for macOS that makes sure you know about all the latest updates to the apps you use.
- **[SwiftBar](https://github.com/swiftbar/SwiftBar)** - Powerful macOS menu bar customization tool.
- **[Cork](https://github.com/buresdv/Cork)** - A fast GUI for Homebrew written in SwiftUI.
- **[MarkEdit](https://github.com/MarkEdit-app/MarkEdit)** - Just like TextEdit on Mac but dedicated to Markdown.
- **[TRex](https://github.com/amebalabs/TRex)** - Copy any text on your screen, stop retyping.
- **[wallpapper](https://github.com/mczachurski/wallpapper)** - Console application for creating dynamic wallpapers for macOS Mojave and newer. ⏳
- **[reminders-menubar](https://github.com/DamascenoRafael/reminders-menubar)** - Simple macOS menu bar application to view and interact with reminders.
- **[SpotMenu](https://github.com/kmikiy/SpotMenu)** - Spotify & Apple Music in your macOS menu bar.
- **[phpmon](https://github.com/nicoverbruggen/phpmon)** - Lightweight, native Mac menu bar app that helps you manage multiple PHP installations.
- **[TomatoBar](https://github.com/ivoronin/TomatoBar)** - World's neatest Pomodoro timer for macOS menu bar.
- **[pika](https://github.com/superhighfives/pika)** - An open-source colour picker app for macOS.
- **[FlashSpace](https://github.com/wojciech-kulik/FlashSpace)** - FlashSpace is a blazingly fast virtual workspace manager for macOS.
- **[LocationSimulator](https://github.com/Schlaubischlump/LocationSimulator)** - MacOS application to spoof / fake / mock your iOS device location. ⏳
- **[AssetCatalogTinkerer](https://github.com/insidegui/AssetCatalogTinkerer)** - An app that lets you open .car files and browse/extract their images.
- **[MiniSim](https://github.com/okwasniewski/MiniSim)** - MacOS menu bar app for launching iOS and Android emulators.
- **[Equinox](https://github.com/rlxone/Equinox)** - Create dynamic wallpapers for macOS.
- **[rem](https://github.com/jasonjmcghee/rem)** - An open source approach to locally record and enable searching everything you view on your Mac. ⏳
- **[LunarBar](https://github.com/LunarBar-app/LunarBar)** - A compact lunar calendar for your macOS menu bar.
- **[RsyncMacOS](https://github.com/rsyncMacOS/RsyncMacOS)** - A macOS GUI for rsync.
- **[XcodeCleaner-SwiftUI](https://github.com/waylybaye/XcodeCleaner-SwiftUI)** - Make Xcode Clean Again.
- **[touch-bar-simulator](https://github.com/sindresorhus/touch-bar-simulator)** - Use the Touch Bar on any Mac. ⏳
- **[HSTracker](https://github.com/HearthSim/HSTracker)** - A deck tracker and deck manager for Hearthstone on macOS.
- **[DevToysMac](https://github.com/DevToys-app/DevToysMac)** - DevToys For mac. ⏳
- **[AuroraEditor](https://github.com/AuroraEditor/AuroraEditor)** - Aurora Editor is a IDE built by the community, for the community, and written in Swift for the best native performance and feel for macOS.
- **[multi](https://github.com/kofigumbs/multi)** - Create custom, lightweight macOS apps from websites.
- **[ChangeMenuBarColor](https://github.com/igorkulman/ChangeMenuBarColor)** - Simple utility to change macOS Big Sur and Monterey menu bar color.
- **[Plash](https://github.com/sindresorhus/Plash)** - Make any website your Mac desktop wallpaper.
- **[System-Color-Picker](https://github.com/sindresorhus/System-Color-Picker)** - The macOS color picker as an app with more features.
- **[LaunchAtLogin-Legacy](https://github.com/sindresorhus/LaunchAtLogin-Legacy)** - Add "Launch at Login" functionality to your macOS app in seconds. ⏳
- **[Actions](https://github.com/sindresorhus/Actions)** - Supercharge your shortcuts.
- **[DockProgress](https://github.com/sindresorhus/DockProgress)** - Show progress in your app's Dock icon.
- **[HotKey](https://github.com/soffes/HotKey)** - Simple global shortcuts in macOS. ⏳
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
- **[SwiftDefaultApps](https://github.com/Lord-Kamina/SwiftDefaultApps)** - Replacement for RCDefaultApps, written in Swift. ⏳
- **[ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG)** - Next Generation of ShadowsocksX. ⏳

*[↑ Back to top](#contents)*

## ⚠️ Malicious

- **[WHC_ConfuseSoftware](https://github.com/netyouli/WHC_ConfuseSoftware)** - iOS代码混淆工具，Uniapp代码混淆工具，react-native代码混淆, iOS代码混淆助手，Android代码混淆助手，Uniapp代码混淆助手，过机器审核，辅助过4.3, other审核，android、ios、uniapp、u3d、cocos2dx、flutter、代码翻新(WHC_ConfuseSoftware)是一款运行在MAC OS平台的App、完美支持Objc和Swift、U3D、Flutter、Cocos2dx项目代码的自动翻新(混淆)、支持文件夹名称、文件名、修改资源文件hash值、类名、方法名、属性名、添加混淆函数方法体、添加混淆属性、自动调用生成的混淆方法、字符串混淆加密等...功能强大而稳定。.
  
- **[confuse-9live](https://github.com/outtable/confuse-9live)** - 🔥🔥🔥 专业版iOS混淆工具，马甲工具包、ipa静态分析工具（相似度对比、敏感词检测），提供试用版本，100%过机器审核，解决 AppStore 4.3，2.3.1问题，支持语言 c、c++、objc、dart、swift 并支持各种资源改名，混淆、傻瓜化操作、一键出包，提供良好的UI界面，支持多包管理一包一特征、支持Unity3d、cocos2d全家桶、swiftUI、flutter、虚幻等各种引擎。支持混淆.a/.framework/.xcframework，混淆比例95%，支持dSYM文件混淆和恢复功能，不影响bugly等各种在线崩溃收集，可持续迭代原工程。.

*[↑ Back to top](#contents)*

## 📝 Markdown

- **[swift-markdown-ui](https://github.com/gonzalezreal/swift-markdown-ui)** - Render Markdown text in SwiftUI.
- **[swift-markdown](https://github.com/swiftlang/swift-markdown)** - A Swift package for parsing, building, editing, and analyzing Markdown documents.
- **[Ink](https://github.com/JohnSundell/Ink)** - A fast and flexible Markdown parser written in Swift. ⏳
- **[SwiftyMarkdown](https://github.com/SimonFairbairn/SwiftyMarkdown)** - Converts Markdown files and strings into NSAttributedStrings with lots of customisation options. ⏳
- **[MarkdownView](https://github.com/keitaoouchi/MarkdownView)** - Markdown View for iOS.

*[↑ Back to top](#contents)*

## ➗ Math

- **[swift-numerics](https://github.com/apple/swift-numerics)** - Advanced mathematical types and functions for Swift.
- **[Expression](https://github.com/nicklockwood/Expression)** - A cross-platform Swift library for evaluating mathematical expressions at runtime.
- **[DDMathParser](https://github.com/davedelong/DDMathParser)** - String to Number. ⏳
- **[SoulverCore](https://github.com/soulverteam/SoulverCore)** - A powerful Swift framework for evaluating natural language math expressions.
- **[GEOSwift](https://github.com/GEOSwift/GEOSwift)** - The Swift Geometry Engine.

*[↑ Back to top](#contents)*

## ▶️ Media Player

- **[Player](https://github.com/piemonte/Player)** - Play and stream media in Swift.
- **[BMPlayer](https://github.com/BrikerMan/BMPlayer)** - A video player for iOS, based on AVPlayer, support the horizontal, vertical screen. support adjust volume, brightness and seek by slide, support subtitles. ⏳
- **[KSPlayer](https://github.com/kingslay/KSPlayer)** - A video player for iOS, macOS, tvOS, visionOS, based on AVPlayer and FFmpeg, support SwiftUI, subtitles.
- **[HaishinKit.swift](https://github.com/HaishinKit/HaishinKit.swift)** - Camera and Microphone streaming library via RTMP and SRT for iOS, macOS, tvOS and visionOS.
- **[NextLevel](https://github.com/NextLevel/NextLevel)** - Media Capture in Swift.
- **[CameraManager](https://github.com/imaginary-cloud/CameraManager)** - Simple Swift class to provide all the configurations you need to create custom camera view in your app. ⏳
- **[Lumina](https://github.com/dokun1/Lumina)** - A camera designed in Swift for easily integrating CoreML models.
- **[Aperture](https://github.com/wulkano/Aperture)** - Record the screen on macOS. ⏳

*[↑ Back to top](#contents)*

## 🧭 Menu / Navigation

- **[PopMenu](https://github.com/CaliCastle/PopMenu)** - A fully customizable popup style menu for iOS. ⏳

*[↑ Back to top](#contents)*

## 👋 Onboarding

- **[Instructions](https://github.com/ephread/Instructions)** - Create walkthroughs and guided tours (coach marks) in a simple way, with Swift. ⏳
- **[WhatsNewKit](https://github.com/SvenTiigi/WhatsNewKit)** - Showcase your awesome new app features. ⏳
- **[ConcentricOnboarding](https://github.com/exyte/ConcentricOnboarding)** - SwiftUI library for a walkthrough or onboarding flow with tap actions.
- **[Gecco](https://github.com/bannzai/Gecco)** - Simply highlight items for your tutorial walkthrough, written in Swift. ⏳
- **[OnboardingKit](https://github.com/danielsaidi/OnboardingKit)** - Create amazing onboarding experiences in SwiftUI.

*[↑ Back to top](#contents)*

## 📱 Open Source iOS Apps

- **[ios-oss](https://github.com/kickstarter/ios-oss)** - Kickstarter for iOS. Bring new ideas to life, anywhere.
- **[firefox-ios](https://github.com/mozilla-mobile/firefox-ios)** - Firefox for iOS.
- **[brave-ios](https://github.com/brave/brave-ios)** - Brave iOS Browser. ⏳
- **[WordPress-iOS](https://github.com/wordpress-mobile/WordPress-iOS)** - WordPress for iOS - Official repository.
- **[wikipedia-ios](https://github.com/wikimedia/wikipedia-ios)** - The official Wikipedia iOS app.
- **[IceCubesApp](https://github.com/Dimillian/IceCubesApp)** - A SwiftUI Mastodon client.
- **[blink](https://github.com/blinksh/blink)** - Blink Mobile Shell for iOS (Mosh based).
- **[TelegramSwift](https://github.com/overtake/TelegramSwift)** - Source code of Telegram for macos on Swift 5.0.
- **[enchanted](https://github.com/gluonfield/enchanted)** - Enchanted is iOS and macOS app for chatting with private self hosted language models using Ollama.
- **[Swiftfin](https://github.com/jellyfin/Swiftfin)** - Native Jellyfin Client for iOS and tvOS.
- **[Aidoku](https://github.com/Aidoku/Aidoku)** - Free and open source manga reader for iOS and iPadOS.
- **[userscripts](https://github.com/quoid/userscripts)** - An open-source userscript manager for Safari.
- **[yattee](https://github.com/yattee/yattee)** - Privacy oriented video player for iOS, tvOS and macOS.
- **[iOS](https://github.com/home-assistant/iOS)** - Home Assistant for Apple platforms.
- **[Swiftcord](https://github.com/SwiftcordApp/Swiftcord)** - A fully native Discord client for macOS built 100% in Swift!. ⏳
- **[trailer](https://github.com/ptsochantaris/trailer)** - Managing Pull Requests and Issues For GitHub & GitHub Enterprise.
- **[BookPlayer](https://github.com/TortugaPower/BookPlayer)** - Player for your DRM-free audiobooks.
- **[amperfy](https://github.com/BLeeEZ/amperfy)** - Amperfy is an iOS/iPadOS/macOS app to play songs from an Ampache or Subsonic server.
- **[vlc-ios](https://github.com/videolan/vlc-ios)** - VLC for iOS/iPadOS and tvOS official mirror.
- **[wire-ios](https://github.com/wireapp/wire-ios)** - Wire for iOS (iPhone and iPad).
- **[winston](https://github.com/lo-cafe/winston)** - A beautiful and native Reddit client for iOS.
- **[OpenScanner](https://github.com/pencilresearch/OpenScanner)** - Fast, reliable, and free document scanner app for iPhone. ⏳
- **[V2ex-Swift](https://github.com/Finb/V2ex-Swift)** - An iOS client written in Swift for V2EX.
- **[Messenger](https://github.com/relatedcode/Messenger)** - Open source alternative communication platform.
- **[Swift-Radio-Pro](https://github.com/analogcode/Swift-Radio-Pro)** - Professional Radio Station App for iOS!.
- **[edhita](https://github.com/tnantoka/edhita)** - Fully open source text editor for iOS written in SwiftUI.
- **[HealthGPT](https://github.com/StanfordBDHG/HealthGPT)** - Query your Apple Health data with natural language.
- **[open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps)** - Collaborative List of Open-Source iOS Apps.
- **[open-source-mac-os-apps](https://github.com/serhii-londar/open-source-mac-os-apps)** - Awesome list of open source applications for macOS.
- **[example-ios-apps](https://github.com/jogendra/example-ios-apps)** - A curated list of Open Source example iOS apps developed in Swift. ⏳
- **[focus-ios](https://github.com/mozilla-mobile/focus-ios)** - Firefox Focus (iOS). ⏳
- **[cheetah](https://github.com/leetcode-mafia/cheetah)** - Mac app for crushing tech interviews with AI. ⏳

*[↑ Back to top](#contents)*

## 🔑 Permissions

- **[PermissionsSwiftUI](https://github.com/jevonmao/PermissionsSwiftUI)** - A SwiftUI package to beautifully display and handle permissions. ⏳

*[↑ Back to top](#contents)*

## ⏳ Progress / Loading

- **[NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView)** - A collection of awesome loading animations. ⏳
- **[SkeletonView](https://github.com/Juanpe/SkeletonView)** - An elegant way to show users that something is happening and also prepare them to which contents they are awaiting. ⏳
- **[ProgressHUD](https://github.com/relatedcode/ProgressHUD)** - ProgressHUD is a lightweight and easy-to-use HUD for iOS.
- **[SwiftUI-Shimmer](https://github.com/markiv/SwiftUI-Shimmer)** - Shimmer is a super-light modifier that adds a shimmering effect to any SwiftUI View. ⏳
- **[SkeletonUI](https://github.com/CSolanaM/SkeletonUI)** - Elegant skeleton loading animation in lightweight SwiftUI. ⏳
- **[GradientLoadingBar](https://github.com/fxm90/GradientLoadingBar)** - A customizable animated gradient loading bar.
- **[HGCircularSlider](https://github.com/HamzaGhazouani/HGCircularSlider)** - A custom reusable circular / progress slider control for iOS application. ⏳

*[↑ Back to top](#contents)*

## ⚛️ Reactive Programming

- **[RxSwift](https://github.com/ReactiveX/RxSwift)** - Reactive Programming in Swift.
- **[ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)** - Cocoa framework and Obj-C dynamism bindings for ReactiveSwift.
- **[ReactiveSwift](https://github.com/ReactiveCocoa/ReactiveSwift)** - Streams of values over time.
- **[CombineExt](https://github.com/CombineCommunity/CombineExt)** - CombineExt provides a collection of operators, publishers and utilities for Combine.
- **[ReactiveKit](https://github.com/DeclarativeHub/ReactiveKit)** - A Swift Reactive Programming Kit.
- **[RxCombine](https://github.com/CombineCommunity/RxCombine)** - Bi-directional type bridging between RxSwift and Apple's Combine framework. ⏳

*[↑ Back to top](#contents)*

## 📚 Resources / Learning

- **[awesome-ios](https://github.com/vsouza/awesome-ios)** - A curated list of awesome iOS ecosystem, including Objective-C and Swift Projects.
- **[awesome-swift](https://github.com/matteocrippa/awesome-swift)** - A collaborative list of awesome Swift libraries and resources.
- **[SwiftGuide](https://github.com/ipader/SwiftGuide)** - Swift Featured Projects in brain Mapping. ⏳
- **[Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift)** - Design Patterns implemented in Swift 5.0. ⏳
- **[OOD-Principles-In-Swift](https://github.com/ochococo/OOD-Principles-In-Swift)** - The Principles of OOD (SOLID) based on Uncle Bob articles.
- **[HackingWithSwift](https://github.com/twostraws/HackingWithSwift)** - The project source code for Hacking with iOS.
- **[awesome-swiftui-libraries](https://github.com/Toni77777/awesome-swiftui-libraries)** - Awesome SwiftUI Libraries.
- **[ios-learning-materials](https://github.com/eleev/ios-learning-materials)** - Curated list of articles, tutorials and repos that may help you dig a little bit deeper into iOS. ⏳
- **[SwiftPamphletApp](https://github.com/ming1016/SwiftPamphletApp)** - 戴铭的小册子，一本活的知识手册。使用 SwiftUI + SwiftData + Swift Concurrency.
- **[aprenda-swift](https://github.com/CodandoApple/aprenda-swift)** - Uma lista de conteúdos para você aprender Swift.
- **[swiftui-notes](https://github.com/heckj/swiftui-notes)** - content for Using Combine - notes on learning Combine with UIKit and SwiftUI. ⏳
- **[LLVMSwift](https://github.com/llvm-swift/LLVMSwift)** - A Swift wrapper for the LLVM C API (version 11.0). ⏳
- **[Cacao](https://github.com/PureSwift/Cacao)** - Pure Swift Cross-platform UIKit (Cocoa Touch) implementation (Supports Linux). ⏳
- **[Swift-Macros](https://github.com/krzysztofzablocki/Swift-Macros)** - A curated list of awesome Swift Macros.
- **[iowncode](https://github.com/anupamchugh/iowncode)** - A curated collection of iOS, ML, AR resources sprinkled with some UI additions.
- **[awesome-swift-macos-apps](https://github.com/jaywcjlove/awesome-swift-macos-apps)** - A curated collection of open-source macOS applications built with Swift.
- **[ios-developer-tools](https://github.com/LeoMobileDeveloper/ios-developer-tools)** - Tools that every iOS developer should know. ⏳
- **[Axiom](https://github.com/CharlesWiltgen/Axiom)** - Battle-tested Claude Code skills, commands, and references for modern Apple-platform development.
- **[functional-swift](https://github.com/objcio/functional-swift)** - Issue repository for the Functional Swift book. ⏳
- **[pointfreeco](https://github.com/pointfreeco/pointfreeco)** - The source for <www.pointfree.co>, a video series on advanced programming topics in Swift.
- **[VisualProgrammingLanguage](https://github.com/NathanFlurry/VisualProgrammingLanguage)** - Visual programming language written in Swift that assembles to executable Swift code.

*[↑ Back to top](#contents)*

## 🖥️ Server-Side Swift

- **[vapor](https://github.com/vapor/vapor)** - A server-side Swift HTTP web framework.
- **[hummingbird](https://github.com/hummingbird-project/hummingbird)** - Lightweight, flexible HTTP server framework written in Swift.
- **[swifter](https://github.com/httpswift/swifter)** - Tiny http server engine written in Swift programming language. ⏳
- **[smoke-framework](https://github.com/amzn/smoke-framework)** - A light-weight server-side service framework written in the Swift programming language. ⏳
- **[swift-aws-lambda-runtime](https://github.com/awslabs/swift-aws-lambda-runtime)** - Swift implementation of AWS Lambda Runtime.

*[↑ Back to top](#contents)*

## 💽 Storage

- **[SwiftyUserDefaults](https://github.com/sunshinejr/SwiftyUserDefaults)** - Modern Swift API for NSUserDefaults. ⏳
- **[DefaultsKit](https://github.com/nmdias/DefaultsKit)** - Simple, Strongly Typed UserDefaults for iOS, macOS and tvOS. ⏳
- **[Zephyr](https://github.com/ArtSabintsev/Zephyr)** - Effortlessly synchronize UserDefaults over iCloud. ⏳
- **[Boutique](https://github.com/mergesort/Boutique)** - A magical persistence library (and so much more) for state-driven iOS and Mac apps.

*[↑ Back to top](#contents)*

## 🎨 SwiftUI

- **[SwiftUIX](https://github.com/SwiftUIX/SwiftUIX)** - An exhaustive expansion of the standard SwiftUI library.
- **[swiftui-introspect](https://github.com/siteline/swiftui-introspect)** - Introspect underlying UIKit/AppKit components from SwiftUI.
- **[OpenSwiftUI](https://github.com/OpenSwiftUIProject/OpenSwiftUI)** - Open source implementation of Apple's SwiftUI.
- **[SwiftUI](https://github.com/Jinxiansen/SwiftUI)** - SwiftUI Framework Learning and Usage Guide. ⏳
- **[SwiftWebUI](https://github.com/SwiftWebUI/SwiftWebUI)** - A demo implementation of SwiftUI for the Web. ⏳
- **[SwiftUIKit](https://github.com/danielsaidi/SwiftUIKit)** - Extra functionality for Swift & SwiftUI.
- **[SwiftUIBackports](https://github.com/shaps80/SwiftUIBackports)** - A collection of SwiftUI backports for iOS, macOS, tvOS and watchOS.
- **[ViewInspector](https://github.com/nalexn/ViewInspector)** - Runtime introspection and unit testing of SwiftUI views.
- **[swift-navigation](https://github.com/pointfreeco/swift-navigation)** - Bringing simple and powerful navigation tools to all Swift platforms, inspired by SwiftUI.
- **[swiftui-navigation-transitions](https://github.com/davdroman/swiftui-navigation-transitions)** - Pure SwiftUI Navigation transitions.
- **[swiftui-router](https://github.com/frzi/swiftui-router)** - Path-based routing in SwiftUI. ⏳
- **[SwiftTUI](https://github.com/rensbreur/SwiftTUI)** - SwiftUI for terminal applications. ⏳
- **[Tokamak](https://github.com/TokamakUI/Tokamak)** - SwiftUI-compatible framework for building browser apps with WebAssembly. ⏳
- **[SwiftUI-experiments](https://github.com/mikelikesdesign/SwiftUI-experiments)** - Examples with SwiftUI and other Apple frameworks.
- **[ConfettiSwiftUI](https://github.com/simibac/ConfettiSwiftUI)** - SwiftUI Package for Configurable Confetti Animation.
- **[Popovers](https://github.com/aheze/Popovers)** - A library to present popovers. Simple, modern, and highly customizable.
- **[Setting](https://github.com/aheze/Setting)** - Compose beautiful preference panels. ⏳
- **[SwipeActions](https://github.com/aheze/SwipeActions)** - Add customizable swipe actions to any view.
- **[WaterfallGrid](https://github.com/paololeonardi/WaterfallGrid)** - A waterfall grid layout view for SwiftUI. ⏳
- **[SwiftUIPager](https://github.com/fermoya/SwiftUIPager)** - Native Pager in SwiftUI. ⏳
- **[ScalingHeaderScrollView](https://github.com/exyte/ScalingHeaderScrollView)** - A scroll view with a sticky header which shrinks as you scroll. Written with SwiftUI.
- **[BottomSheet](https://github.com/lucaszischka/BottomSheet)** - A sliding Sheet from the bottom of the Screen with 3 States build with SwiftUI.
- **[SlideOverCard](https://github.com/joogps/SlideOverCard)** - A SwiftUI card view, made great for setup interactions. ⏳
- **[shiny](https://github.com/maustinstar/shiny)** - Shiny uses your gyroscope to simulate lighting and motion effects on colors. ⏳
- **[neumorphic](https://github.com/costachung/neumorphic)** - Neumorphic is a SwiftUI utility to build Neumorphism Soft UI. ⏳
- **[StepperView](https://github.com/badrinathvm/StepperView)** - SwiftUI iOS component for Step Indications.
- **[WidgetExamples](https://github.com/pawello2222/WidgetExamples)** - A demo project showing different types of Widgets created with SwiftUI and WidgetKit. ⏳
- **[Popups](https://github.com/Mijick/Popups)** - Popups, popovers, sheets, alerts, toasts, banners presentation made simple. Written for SwiftUI.
- **[skip](https://github.com/skiptools/skip)** - Skip enables the creation of native SwiftUI apps for iOS and Android.
- **[swift-cross-ui](https://github.com/moreSwift/swift-cross-ui)** - A cross-platform declarative UI framework, inspired by SwiftUI.
- **[divkit](https://github.com/divkit/divkit)** - DivKit is an open source Server-Driven UI (SDUI) framework.

*[↑ Back to top](#contents)*

## 📑 Tab Bar

- **[CYLTabBarController](https://github.com/ChenYilong/CYLTabBarController)** - 【中国特色 TabBar】一行代码实现 Lottie 动画TabBar.
- **[Tabman](https://github.com/uias/Tabman)** - A powerful paging view controller with interactive indicator bars.
- **[CircleBar](https://github.com/softhausHQ/CircleBar)** - A fun, easy-to-use tab bar navigation controller for iOS. ⏳

*[↑ Back to top](#contents)*

## 🧪 Testing

- **[Quick](https://github.com/Quick/Quick)** - The Swift (and Objective-C) testing framework.
- **[Nimble](https://github.com/Quick/Nimble)** - A Matcher Framework for Swift and Objective-C.
- **[swift-testing](https://github.com/swiftlang/swift-testing)** - A modern, expressive testing package for Swift.
- **[swift-corelibs-xctest](https://github.com/swiftlang/swift-corelibs-xctest)** - The XCTest Project, A Swift core library for providing unit test support.
- **[swift-snapshot-testing](https://github.com/pointfreeco/swift-snapshot-testing)** - Delightful Swift snapshot testing.
- **[Cuckoo](https://github.com/Brightify/Cuckoo)** - Boilerplate-free mocking framework for Swift!.
- **[SwiftyMocky](https://github.com/MakeAWishFoundation/SwiftyMocky)** - Framework for automatic mock generation. Adds a set of handy methods, simplifying testing. ⏳
- **[swift](https://github.com/danger/swift)** - Stop saying "you forgot to …" in code review.
- **[Difference](https://github.com/krzysztofzablocki/Difference)** - Simple way to identify what is different between 2 instances of any type. Must have for TDD.
- **[playbook-ios](https://github.com/playbook-ui/playbook-ios)** - A library for isolated developing UI components and automatically taking snapshots of them. ⏳
- **[NSFWDetector](https://github.com/lovoo/NSFWDetector)** - A NSFW (aka porn) detector with CoreML. ⏳

*[↑ Back to top](#contents)*

## 🔤 Text / Labels

- **[LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel)** - Graceful morphing effects for UILabel written in Swift.
- **[MarqueeLabel](https://github.com/cbpowell/MarqueeLabel)** - A drop-in replacement for UILabel, which automatically adds a scrolling marquee effect.
- **[BonMot](https://github.com/Rightpoint/BonMot)** - Beautiful, easy attributed strings in Swift. ⏳
- **[Atributika](https://github.com/psharanda/Atributika)** - Convert text with HTML tags, links, hashtags, mentions into NSAttributedString. Make them clickable with UILabel drop-in replacement. ⏳

### TextField

- **[SkyFloatingLabelTextField](https://github.com/Skyscanner/SkyFloatingLabelTextField)** - A beautiful and flexible text field control implementation of "Float Label Pattern".
- **[RSKGrowingTextView](https://github.com/ruslanskorb/RSKGrowingTextView)** - A light-weight UITextView subclass that automatically grows and shrinks. ⏳
- **[Runestone](https://github.com/simonbs/Runestone)** - Performant plain text editor for iOS with syntax highlighting, line numbers, invisible characters and much more.
- **[STTextView](https://github.com/krzyzanowskim/STTextView)** - Performant and reusable text view component (TextKit 2), with line numbers and more.
- **[proton](https://github.com/rajdeep/proton)** - Purely native and extensible rich text editor for iOS and macOS Catalyst apps.
- **[RichTextKit](https://github.com/danielsaidi/RichTextKit)** - View and edit rich text in Swift & SwiftUI.

*[↑ Back to top](#contents)*

## 🎭 Transitions / Presentations

- **[Jelly](https://github.com/SebastianBoldt/Jelly)** - Jelly is a library for animated, non-interactive & interactive viewcontroller transitions and presentations.

*[↑ Back to top](#contents)*

## 🎨 UI Components

### Alerts / Popups

- **[SwiftMessages](https://github.com/SwiftKickMobile/SwiftMessages)** - A very flexible message bar for UIKit and SwiftUI.
- **[SwiftEntryKit](https://github.com/huri000/SwiftEntryKit)** - SwiftEntryKit is a presentation library for iOS. It can be used to easily display overlays within your iOS apps. ⏳
- **[NotificationBanner](https://github.com/Daltron/NotificationBanner)** - The easiest way to display highly customizable in app notification banners in iOS. ⏳
- **[alerts-and-pickers](https://github.com/dillidon/alerts-and-pickers)** - Advanced usage of UIAlertController and pickers based on it. ⏳
- **[Toast-Swift](https://github.com/scalessec/Toast-Swift)** - A Swift extension that adds toast notifications to the UIView object class. ⏳
- **[Toaster](https://github.com/devxoul/Toaster)** - Toast for Swift. ⏳
- **[AlertKit](https://github.com/sparrowcode/AlertKit)** - Native alert from Apple Music & Feedback. Contains Done, Heart & Message and other presets. ⏳
- **[AlertToast](https://github.com/elai950/AlertToast)** - Create Apple-like alerts & toasts using SwiftUI. ⏳
- **[Drops](https://github.com/omaralbeik/Drops)** - A µFramework for showing alerts like the one used when copying from pasteboard. ⏳
- **[JDStatusBarNotification](https://github.com/calimarkus/JDStatusBarNotification)** - Highly customizable & feature rich notifications. SwiftUI compatible. ⏳
- **[JFMinimalNotifications](https://github.com/atljeremy/JFMinimalNotifications)** - An iOS UIView for presenting a minimalistic notification that doesn't block the UI. ⏳

### CollectionView

- **[AlignedCollectionViewFlowLayout](https://github.com/mischa-hildebrand/AlignedCollectionViewFlowLayout)** - A collection view layout that gives you control over the horizontal and vertical alignment of the cells.

### Paging / Page Control

- **[FSPagerView](https://github.com/WenchaoD/FSPagerView)** - FSPagerView is an elegant Screen Slide Library. It is extremely helpful for making Banner View, Product Show, Welcome/Guide Pages. ⏳
- **[Parchment](https://github.com/rechsteiner/Parchment)** - A paging view with a highly customizable menu. ⏳
- **[Pageboy](https://github.com/uias/Pageboy)** - A simple, highly informative page view controller.
- **[TKRubberIndicator](https://github.com/TBXark/TKRubberIndicator)** - A rubber animation pagecontrol. ⏳
- **[JXSegmentedView](https://github.com/pujiaxin33/JXSegmentedView)** - A powerful and easy to use segmented view.
- **[Segmentio](https://github.com/Yalantis/Segmentio)** - Animated top/bottom segmented control written in Swift. ⏳

### Sliders

- **[Koloda](https://github.com/Yalantis/Koloda)** - KolodaView is a class designed to simplify the implementation of Tinder like cards on iOS. ⏳
- **[Magnetic](https://github.com/efremidze/Magnetic)** - SpriteKit Floating Bubble Picker (inspired by Apple Music).
- **[Cluster](https://github.com/efremidze/Cluster)** - Easy Map Annotation Clustering.

### Switches

- **[TKSwitcherCollection](https://github.com/TBXark/TKSwitcherCollection)** - An animation switch collection. ⏳

### TableView

- **[SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit)** - Swipeable UITableViewCell/UICollectionViewCell based on the stock Mail.app, implemented in Swift. ⏳
- **[Carbon](https://github.com/ra1028/Carbon)** - A declarative library for building component-based user interfaces in UITableView and UICollectionView. ⏳
- **[TimelineTableViewCell](https://github.com/kf99916/TimelineTableViewCell)** - Simple timeline view implemented by UITableViewCell.
- **[TDBadgedCell](https://github.com/tmdvs/TDBadgedCell)** - TDBadgedCell is a table view cell class that adds a badge, similar to the badges in Apple's own apps. ⏳

### Other UI

- **[Gemini](https://github.com/shoheiyokoyama/Gemini)** - Gemini is rich scroll based animation framework for iOS, written in Swift.
- **[Aiolos](https://github.com/IdeasOnCanvas/Aiolos)** - A floating panel for your iOS Apps.
- **[Pulley](https://github.com/52inc/Pulley)** - A library to imitate the iOS 10 Maps UI. ⏳
- **[VisualEffectView](https://github.com/efremidze/VisualEffectView)** - Dynamic blur background view with tint color (UIVisualEffectView subclass).
- **[Popover](https://github.com/corin8823/Popover)** - Popover is a balloon library like Facebook app. ⏳
- **[Shiny](https://github.com/efremidze/Shiny)** - Iridescent Effect View (inspired by Apple Pay Cash).

*[↑ Back to top](#contents)*

## 🎥 Video

- **[lottie-ios](https://github.com/airbnb/lottie-ios)** - An iOS library to natively render After Effects vector animations.
- **[epoxy-ios](https://github.com/airbnb/epoxy-ios)** - Epoxy is a suite of declarative UI APIs for building UIKit applications in Swift.

*[↑ Back to top](#contents)*

## 🌐 Web

- **[gitignore.io](https://github.com/toptal/gitignore.io)** - Create useful .gitignore files for your project. ⏳
- **[Publish](https://github.com/JohnSundell/Publish)** - A static site generator for Swift developers. ⏳
- **[Ignite](https://github.com/twostraws/Ignite)** - A static site generator for Swift developers.
- **[Plot](https://github.com/JohnSundell/Plot)** - A DSL for writing type-safe HTML, XML and RSS in Swift. ⏳
- **[Stencil](https://github.com/stencilproject/Stencil)** - Stencil is a simple and powerful template language for Swift. ⏳
- **[Swift-YouTube-Player](https://github.com/gilesvangruisen/Swift-YouTube-Player)** - Swift library for embedding and controlling YouTube videos in your iOS applications via WKWebView!. ⏳

*[↑ Back to top](#contents)*

## 🛠️ Xcode Tools

- **[Sourcery](https://github.com/krzysztofzablocki/Sourcery)** - Meta-programming for Swift, stop writing boilerplate code.
- **[SwiftGen](https://github.com/SwiftGen/SwiftGen)** - The Swift code generator for your assets, storyboards, Localizable.strings, - Get rid of all String-based APIs!. ⏳
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
- **[XcodeBenchmark](https://github.com/devMEremenko/XcodeBenchmark)** - XcodeBenchmark measures the compilation time of a large codebase on iMac, MacBook, and Mac Pro.
- **[SwiftInfo](https://github.com/rockbruno/SwiftInfo)** - Extract and analyze the evolution of an iOS app's code.
- **[Sitrep](https://github.com/twostraws/Sitrep)** - A source code analyzer for Swift projects.
- **[json2swift](https://github.com/ijoshsmith/json2swift)** - A macOS command line tool that generates excellent Swift data models based on JSON data. ⏳
- **[XCLogParser](https://github.com/MobileNativeFoundation/XCLogParser)** - Tool to parse Xcode and xcodebuild logs stored in the xcactivitylog format.
- **[XCMetrics](https://github.com/spotify/XCMetrics)** - XCMetrics is the easiest way to collect Xcode build metrics and improve developer productivity. ⏳
- **[xcbeautify](https://github.com/cpisciotta/xcbeautify)** - A little beautifier tool for xcodebuild.
- **[xcodes](https://github.com/XcodesOrg/xcodes)** - The best command-line tool to install and switch between multiple versions of Xcode.
- **[GodEye](https://github.com/zixun/GodEye)** - Automatically display Log, Crash, Network, ANR, Leak, CPU, RAM, FPS, NetFlow, Folder and etc with one line of code based on Swift. ⏳
- **[DebugSwift](https://github.com/DebugSwift/DebugSwift)** - A toolkit to make debugging iOS applications easier.
- **[Inject](https://github.com/krzysztofzablocki/Inject)** - Hot Reloading for Swift applications!.
- **[LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker)** - Find retain cycles / memory leaks sooner.
- **[Diagnostics](https://github.com/AvdLee/Diagnostics)** - Allow users to easily share Diagnostics with your support team to improve the flow of fixing bugs.
- **[GDPerformanceView-Swift](https://github.com/dani-gavrilov/GDPerformanceView-Swift)** - Shows FPS, CPU and memory usage, device model, app and iOS versions above the status bar.
- **[xcdiff](https://github.com/bloomberg/xcdiff)** - A tool which helps you diff xcodeproj files.
- **[CopilotForXcode](https://github.com/github/CopilotForXcode)** - AI coding assistant for Xcode.
- **[xtool](https://github.com/xtool-org/xtool)** - Cross-platform Xcode replacement. Build and deploy iOS apps with SwiftPM on Linux, Windows, macOS.
- **[AXe](https://github.com/cameroncooke/AXe)** - AXe is a CLI tool for interacting with Simulators using Apple's Private Accessibility APIs.
- **[Peekaboo](https://github.com/steipete/Peekaboo)** - Peekaboo is a macOS CLI & optional MCP server that enables AI agents to capture screenshots of applications.
- **[InterposeKit](https://github.com/steipete/InterposeKit)** - A modern library to swizzle elegantly in Swift.
- **[ipatool](https://github.com/majd/ipatool)** - Command-line tool that allows searching and downloading app packages (known as ipa files) from the iOS App Store.
- **[DVIA-v2](https://github.com/prateek147/DVIA-v2)** - Damn Vulnerable iOS App (DVIA) is an iOS application that is damn vulnerable for penetration testing. ⏳
- **[mac-monitor](https://github.com/Brandon7CC/mac-monitor)** - "The missing ProcMon for macOS": Mac Monitor records Endpoint Security events and displays them graphically.
- **[swift-embedded-examples](https://github.com/swiftlang/swift-embedded-examples)** - A collection of example projects using Embedded Swift.
- **[swift-java](https://github.com/swiftlang/swift-java)** - Java interopability support for Swift.
- **[swift-build](https://github.com/swiftlang/swift-build)** - A high-level build system based on llbuild, used by Xcode, Swift Playground, and the Swift Package Manager.
- **[swift-openapi-generator](https://github.com/apple/swift-openapi-generator)** - Generate Swift client and server code from an OpenAPI document.
- **[swift-atomics](https://github.com/apple/swift-atomics)** - Low-level atomic operations for Swift.
- **[containerization](https://github.com/apple/containerization)** - Containerization is a Swift package for running Linux containers on macOS.
- **[container](https://github.com/apple/container)** - A tool for creating and running Linux containers using lightweight virtual machines on a Mac.
- **[PythonKit](https://github.com/pvieito/PythonKit)** - Swift framework to interact with Python.
- **[swift-win32](https://github.com/compnerd/swift-win32)** - A Windows application framework for Swift.
- **[supabase-swift](https://github.com/supabase/supabase-swift)** - A Swift SDK for Supabase.
- **[sentry-cocoa](https://github.com/getsentry/sentry-cocoa)** - The official Sentry SDK for iOS, tvOS, macOS, watchOS, iPadOS and visionOS.
- **[swift-sdk](https://github.com/modelcontextprotocol/swift-sdk)** - The official Swift SDK for Model Context Protocol servers and clients.
- **[soto](https://github.com/soto-project/soto)** - Swift SDK for AWS that works on Linux, macOS and iOS.
- **[swift-sdk](https://github.com/watson-developer-cloud/swift-sdk)** - The Watson Swift SDK enables developers to quickly add Watson Cognitive Computing services to their Swift applications.
- **[line-sdk-ios-swift](https://github.com/line/line-sdk-ios-swift)** - Provides a modern way of implementing LINE APIs.
- **[BitcoinKit](https://github.com/yenom/BitcoinKit)** - Bitcoin protocol toolkit for Swift. ⏳
- **[mapbox-navigation-ios](https://github.com/mapbox/mapbox-navigation-ios)** - Turn-by-turn navigation logic and UI in Swift on iOS.
- **[StateMachine](https://github.com/Tinder/StateMachine)** - A Kotlin and Swift DSL for finite state machine. ⏳
- **[SFSafeSymbols](https://github.com/SFSafeSymbols/SFSafeSymbols)** - Safely access Apple's SF Symbols using static typing.
- **[Font-Awesome](https://github.com/FortAwesome/Font-Awesome)** -  The iconic SVG, font, and CSS toolkit.
- **[FontBlaster](https://github.com/ArtSabintsev/FontBlaster)** - Programmatically load custom fonts into your iOS, macOS and tvOS app. ⏳
- **[Splash](https://github.com/JohnSundell/Splash)** - A fast, lightweight and flexible Swift syntax highlighter for blogs, tools and fun!. ⏳
- **[swift-parsing](https://github.com/pointfreeco/swift-parsing)** - A library for turning nebulous data into well-structured data.
- **[SwiftTerm](https://github.com/migueldeicaza/SwiftTerm)** - Xterm/VT100 Terminal emulator in Swift.
- **[PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit)** - A Swift framework for parsing, formatting and validating international phone numbers.
- **[EVReflection](https://github.com/evermeer/EVReflection)** - Reflection based (Dictionary, CKRecord, NSManagedObject, Realm, JSON and XML) object mapping.
- **[GraphQL](https://github.com/GraphQLSwift/GraphQL)** - The Swift GraphQL implementation for macOS and Linux.

*[↑ Back to top](#contents)*
