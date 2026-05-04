# Graph Report - /Users/luowei/projects/My_App/MyInputMethod/MyInputMethod_Swift  (2026-05-05)

## Corpus Check
- Large corpus: 664 files · ~651,364 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 751 nodes · 1728 edges · 28 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 42 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 9|Community 9]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]

## God Nodes (most connected - your core abstractions)
1. `KeyboardViewController` - 235 edges
2. `LegacyDrawBoardViewController` - 23 edges
3. `LegacyQRCodeViewController` - 23 edges
4. `LegacyEditorViewController` - 22 edges
5. `LegacySymbolStore` - 21 edges
6. `HomeViewController` - 20 edges
7. `LegacyKeyboardTheme` - 18 edges
8. `LegacyPurchaseViewController` - 16 edges
9. `LegacyWordService` - 16 edges
10. `LegacyConversionService` - 16 edges

## Surprising Connections (you probably didn't know these)
- `HomeViewController` --inherits--> `UIViewController`  [EXTRACTED]
  Sources/App/HomeViewController.swift →   _Bridges community 6 → community 13_
- `LegacyConvertViewController` --inherits--> `UIViewController`  [EXTRACTED]
  Sources/App/LegacyRouteViewControllers.swift →   _Bridges community 13 → community 25_
- `LegacyEditorViewController` --inherits--> `UIViewController`  [EXTRACTED]
  Sources/App/LegacyRouteViewControllers.swift →   _Bridges community 13 → community 0_
- `LegacyDrawBoardViewController` --inherits--> `UIViewController`  [EXTRACTED]
  Sources/App/LegacyRouteViewControllers.swift →   _Bridges community 13 → community 19_
- `LegacyQRCodeViewController` --inherits--> `UIViewController`  [EXTRACTED]
  Sources/App/LegacyRouteViewControllers.swift →   _Bridges community 13 → community 16_

## Communities (35 total, 12 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.05
Nodes (42): Command, javascript, promptLink, showSource, LegacyDrawColorTarget, background, pen, LegacyEditorViewController (+34 more)

### Community 2 - "Community 2"
Cohesion: 0.07
Nodes (37): A(), bb(), D(), db(), Ea(), eb(), fa(), fb() (+29 more)

### Community 4 - "Community 4"
Cohesion: 0.11
Nodes (7): Equatable, LegacySearchResult, LegacySearchService, Array, LegacyWordCandidate, LegacyWordService, String

### Community 6 - "Community 6"
Cohesion: 0.1
Nodes (10): HomeViewController, LegacyCatalogCell, LegacyCatalogSectionHeader, LegacyCatalogTableMetrics, UITableViewCell, UITableViewDataSource, UITableViewDelegate, UITableViewHeaderFooterView (+2 more)

### Community 7 - "Community 7"
Cohesion: 0.09
Nodes (9): AppDelegate, LWTabBarController, OtherViewController, SceneDelegate, UIApplicationDelegate, UIResponder, UITabBarController, UITableViewController (+1 more)

### Community 10 - "Community 10"
Cohesion: 0.12
Nodes (15): LegacyKeyboardDisplay, LegacyKeyboardDisplay.Role, LegacyKeyboardMetrics, LegacyKeyboardResources, Role, delete, handwritingLanguage, nextKeyboard (+7 more)

### Community 11 - "Community 11"
Cohesion: 0.21
Nodes (27): assertSwiftCandidateState(), assertSwiftEmojiToolbarState(), assertSwiftPanel(), assertSwiftSkinPanelControls(), assertSwiftToolbarNormalState(), captureKeyboardSurface(), captureSwiftEmojiEncryptPanel(), captureSwiftLogoPopup() (+19 more)

### Community 12 - "Community 12"
Cohesion: 0.1
Nodes (5): KeyboardSketchView, LegacyKeyboardType, SkinColorWheelControl, LegacyKeyboardButton, UIControl

### Community 13 - "Community 13"
Cohesion: 0.12
Nodes (7): LegacyImageViewController, LegacyRouteFactory, LegacyToolPlaceholderViewController, LegacyTranslateViewController, LegacyWebViewController, UIViewController, WKNavigationDelegate

### Community 16 - "Community 16"
Cohesion: 0.14
Nodes (4): LegacyQRCodeViewController, AVCaptureMetadataOutputObjectsDelegate, UIImagePickerControllerDelegate, UINavigationControllerDelegate

### Community 18 - "Community 18"
Cohesion: 0.18
Nodes (3): LegacyCodeConversion, LegacyConversionService, LegacySearchServiceUserAgent

### Community 20 - "Community 20"
Cohesion: 0.16
Nodes (10): ConvertType, mars, pinyin, traditional, LegacyEditorToolbarItem, LegacyRoutePresentation, modal, push (+2 more)

### Community 28 - "Community 28"
Cohesion: 0.29
Nodes (3): Key, LegacyKeyboardSettings, LegacyKeyboardType

### Community 29 - "Community 29"
Cohesion: 0.4
Nodes (3): LegacyRoute, LegacyRouteCenter, Notification.Name

### Community 30 - "Community 30"
Cohesion: 0.47
Nodes (3): LegacyCatalog, LegacyCatalogRow, LegacyCatalogSection

### Community 32 - "Community 32"
Cohesion: 0.5
Nodes (3): AccessibilityID, App, Keyboard

## Knowledge Gaps
- **56 isolated node(s):** `LegacyCatalogTableMetrics`, `Notification.Name`, `push`, `modal`, `pinyin` (+51 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **12 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `KeyboardViewController` connect `Community 1` to `Community 0`, `Community 3`, `Community 5`, `Community 8`, `Community 9`, `Community 12`, `Community 17`, `Community 24`, `Community 26`?**
  _High betweenness centrality (0.338) - this node is a cross-community bridge._
- **Why does `HomeViewController` connect `Community 6` to `Community 13`, `Community 7`?**
  _High betweenness centrality (0.086) - this node is a cross-community bridge._
- **Why does `UIColor` connect `Community 15` to `Community 0`, `Community 1`, `Community 5`, `Community 8`, `Community 9`, `Community 12`, `Community 19`, `Community 25`?**
  _High betweenness centrality (0.081) - this node is a cross-community bridge._
- **Are the 5 inferred relationships involving `UIView` (e.g. with `.makeTopHeader()` and `.configureSearchBar()`) actually correct?**
  _`UIView` has 5 INFERRED edges - model-reasoned connections that need verification._
- **What connects `LegacyCatalogTableMetrics`, `Notification.Name`, `push` to the rest of the system?**
  _56 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._