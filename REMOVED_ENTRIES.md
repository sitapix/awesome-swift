# Removed/Deduplicated Entries

This document explains every entry from the original file that is not in the reorganized version.

## Summary

| Category | Count |
|----------|-------|
| Org/repo renamed (duplicates) | 40 |
| Case sensitivity (same repo) | 1 |
| Explicitly deprecated/archived | 6 |
| Superseded by newer version | 2 |
| Old/unmaintained (no replacement) | 2 |
| **Total** | **51** |

---

## 1. Repository Moved to Different Organization (40 entries)

These repos were moved/transferred to new GitHub organizations. **All replacements are in the README.**

| Removed Entry | Reason | Now Listed As | In README |
|---------------|--------|---------------|-----------|
| `apple/sourcekit-lsp` | Moved to swiftlang org | `swiftlang/sourcekit-lsp` | ✓ |
| `apple/swift-corelibs-xctest` | Moved to swiftlang org | `swiftlang/swift-corelibs-xctest` | ✓ |
| `apple/swift-docc` | Moved to swiftlang org | `swiftlang/swift-docc` | ✓ |
| `apple/swift-format` | Moved to swiftlang org | `swiftlang/swift-format` | ✓ |
| `apple/swift-foundation` | Moved to swiftlang org | `swiftlang/swift-foundation` | ✓ |
| `apple/swift-markdown` | Moved to swiftlang org | `swiftlang/swift-markdown` | ✓ |
| `apple/swift-package-manager` | Moved to swiftlang org | `swiftlang/swift-package-manager` | ✓ |
| `apple/swift-syntax` | Moved to swiftlang org | `swiftlang/swift-syntax` | ✓ |
| `apple/swift-testing` | Moved to swiftlang org | `swiftlang/swift-testing` | ✓ |
| `RobotsAndPencils/xcodes` | Moved to XcodesOrg | `XcodesOrg/xcodes` | ✓ |
| `RobotsAndPencils/XcodesApp` | Moved to XcodesOrg | `XcodesOrg/XcodesApp` | ✓ |
| `godly-devotion/MochiDiffusion` | Moved to dedicated org | `MochiDiffusion/MochiDiffusion` | ✓ |
| `KwaiAppTeam/SwiftPamphletApp` | Original author's repo | `ming1016/SwiftPamphletApp` | ✓ |
| `AugustDev/enchanted` | Moved | `gluonfield/enchanted` | ✓ |
| `swift-server/swift-aws-lambda-runtime` | Moved to awslabs | `awslabs/swift-aws-lambda-runtime` | ✓ |
| `redcanaryco/mac-monitor` | Forked/moved | `Brandon7CC/mac-monitor` | ✓ |
| `0x73/SwiftIconFont` | Author changed username | `segecey/SwiftIconFont` | ✓ |
| `alexisakers/BulletinBoard` | Different maintainer | `alexaubry/BulletinBoard` | ✓ |
| `eventtus/photo-editor` | Forked | `bevy/photo-editor` | ✓ |
| `ivanschuetz/SwiftCharts` | Author changed username | `ivnsch/SwiftCharts` | ✓ |
| `owlmafia/SwiftCharts` | Same as above | `ivnsch/SwiftCharts` | ✓ |
| `kirualex/SwiftyGif` | Different maintainer | `alexiscreuzot/SwiftyGif` | ✓ |
| `raywenderlich/swift-algorithm-club` | Rebranded to Kodeco | `kodecocodes/swift-algorithm-club` | ✓ |
| `Khan/SwiftTweaks` | Forked | `bryanjclark/SwiftTweaks` | ✓ |
| `WeTransfer/Diagnostics` | Moved to author's personal | `AvdLee/Diagnostics` | ✓ |
| `jonathantribouharet/JTMaterialTransition` | Forked | `johnvuko/JTMaterialTransition` | ✓ |
| `quickbirdstudios/XCoordinator` | Org renamed | `QuickBirdEng/XCoordinator` | ✓ |
| `quickbirdstudios/FlippingNotch` | Org renamed | `QuickBirdEng/FlippingNotch` | ✓ |
| `gltwy/LTScrollView` | Author changed username | `glthello/LTScrollView` | ✓ |
| `tbxark/TKRubberIndicator` | Case change | `TBXark/TKRubberIndicator` | ✓ |
| `Flinesoft/BartyCrouch` | Org renamed | `FlineDev/BartyCrouch` | ✓ |
| `movingparts-io/Pow` | Acquired/moved | `EmergeTools/Pow` | ✓ |
| `sparrowcode/SwiftUI` | Different maintainer | `ivanvorobei/SwiftUI` | ✓ |
| `ObuchiYuki/DevToysMac` | Moved to org | `DevToys-app/DevToysMac` | ✓ |
| `saeipi/KSChart` | Forked | `sevtin/KSChart` | ✓ |
| `fullstackio/FlappySwift` | Company renamed | `newlinedotco/FlappySwift` | ✓ |
| `goktugyil/EZSwiftExtensions` | Forked | `Esqarrouth/EZSwiftExtensions` | ✓ |
| `goktugyil/QorumLogs` | Forked | `Esqarrouth/QorumLogs` | ✓ |
| `stackotter/swift-cross-ui` | Moved | `moreSwift/swift-cross-ui` | ✓ |
| `swift-server/http` | Superseded | `apple/swift-http-types` | ✓ |

## 2. Case Sensitivity / Same Repository (1 entry)

| Removed Entry | Now Listed As | In README |
|---------------|---------------|-----------|
| `siteline/SwiftUI-Introspect` | `siteline/swiftui-introspect` | ✓ |

## 3. Explicitly Deprecated or Archived (6 entries)

These entries have "deprecated", "archived", or "legacy" in their name or description.

| Removed Entry | Reason | Replacement | In README |
|---------------|--------|-------------|-----------|
| `facebookarchive/facebook-swift-sdk` | Archived | `facebook/facebook-ios-sdk` | ✓ |
| `google-gemini/deprecated-generative-ai-swift` | Explicitly deprecated | `google-gemini/generative-ai-swift` | ✓ |
| `rsyncOSX/RsyncOSX_archived` | Archived (has "_archived" suffix) | `rsyncOSX/RsyncOSX` | ✓ |
| `sindresorhus/LaunchAtLogin-Legacy` | Legacy version | `sindresorhus/LaunchAtLogin` | ✓ |
| `jcavar/refresher` | Marked "DEPRECATED:" in description | None | ✗ |
| `gonzalezreal/MarkdownUI` | Superseded | `gonzalezreal/swift-markdown-ui` | ✓ |

## 5. Superseded by Newer API (3 entries)

| Removed Entry | Reason | Replacement | In README |
|---------------|--------|-------------|-----------|
| `pointfreeco/swiftui-navigation` | Renamed/superseded | `pointfreeco/swift-navigation` | ✓ |
| `WeTransferArchive/WeScan` | Duplicate/old org | `WeTransfer/WeScan` | ✓ |

## 6. Old/Unmaintained with No Clear Replacement (2 entries)

| Removed Entry | Description | Replacement | In README |
|---------------|-------------|-------------|-----------|
| `owensd/json-swift` | Basic JSON library | None (use Codable) | ✗ |
| `Vaberer/Font-Awesome-Swift` | Font Awesome for iOS | `FortAwesome/Font-Awesome` | ✓ |

---

## Summary of Replacements

- **52 entries** have replacements that ARE in the README ✓
- **2 entries** have no replacement (truly removed) ✗
  - `jcavar/refresher` - deprecated with no replacement
  - `owensd/json-swift` - obsolete (use Swift's Codable)
