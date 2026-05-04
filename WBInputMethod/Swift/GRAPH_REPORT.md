# Graph Report - /Users/luowei/projects/My_App/WBInputMethod/WBInputMethod_Swift  (2026-05-05)

## Corpus Check
- Large corpus: 189 files · ~2,132,437 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 737 nodes · 1400 edges · 32 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 32 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
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
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]

## God Nodes (most connected - your core abstractions)
1. `WBPracticeSessionViewController` - 51 edges
2. `WBKeyboardPanelView` - 31 edges
3. `WBHomeViewController` - 27 edges
4. `KeyboardViewController` - 26 edges
5. `WBSymbolDataStore` - 20 edges
6. `WBSearchViewController` - 19 edges
7. `WBKeyboardKeyButton` - 19 edges
8. `main()` - 19 edges
9. `WBPracticeListViewController` - 18 edges
10. `WBWebViewController` - 17 edges

## Surprising Connections (you probably didn't know these)
- `commit()` --calls--> `WBKeyboardCandidate`  [INFERRED]
  Sources/Keyboard/KeyboardViewController.swift → Sources/Keyboard/InputEngine/WBKeyboardCandidateEngine.swift

## Communities (36 total, 6 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.07
Nodes (10): Mode, stems, words, UIView, WBCodeBadgeLabel, WBPracticeQueueCell, WBPracticeSessionViewController, WBStemBreakdownCell (+2 more)

### Community 1 - "Community 1"
Cohesion: 0.07
Nodes (35): appiumCommandTokenFromDefaults(), applyAppearance(), clearComposing(), commit(), commitComposingIfNeeded(), consumeAppiumCommandIfNeeded(), consumeAppiumPasteboardCommandIfNeeded(), deleteOnce() (+27 more)

### Community 2 - "Community 2"
Cohesion: 0.07
Nodes (25): UIButton, UIView, LogoItemButton, PanelItem, WBKeyboardPanelAction, addPhrase, addPhraseCategory, commitCandidate (+17 more)

### Community 3 - "Community 3"
Cohesion: 0.06
Nodes (10): WBPlaceholderViewController, WBLearningViewController, WBSearchDetailViewController, WBKeyboardSmokeViewController, UIActivity, UITableViewController, UIViewController, WBOpenInSafariActivity (+2 more)

### Community 4 - "Community 4"
Cohesion: 0.05
Nodes (11): AnyObject, UIControl, WBCandidateRowView, WBCandidateRowViewDelegate, WBKeyboardKeyButton, WBKeyboardKeyButtonDelegate, WBKeyboardPanelViewDelegate, WBKeyboardToolbarViewDelegate (+3 more)

### Community 5 - "Community 5"
Cohesion: 0.07
Nodes (19): WBArticleCell, WBArticleItem, WBArticleListViewController, WBPracticeWord, Kind, book, fourWord, log (+11 more)

### Community 6 - "Community 6"
Cohesion: 0.09
Nodes (12): PracticeKind, fourWord, multiWord, one, single, three, threeWord, two (+4 more)

### Community 7 - "Community 7"
Cohesion: 0.1
Nodes (8): Result, WBHomeCollectionCell, WBHomeHeaderView, WBHomeViewController, UICollectionViewCell, UICollectionViewDataSource, UICollectionViewDelegateFlowLayout, UISearchBarDelegate

### Community 8 - "Community 8"
Cohesion: 0.12
Nodes (9): Equatable, WBMenuItem, WBMenuResourceParser, WBMenuSection, WBSymbolCategory, WBSymbolDataStore, WBSymbolItem, WBSymbolPanelSnapshot (+1 more)

### Community 9 - "Community 9"
Cohesion: 0.22
Nodes (30): acceptOpenPromptIfPresent(), capture(), clickElement(), dragExtensionElement(), elementId(), ensureSwiftKeyboard(), extensionElementCenter(), findElement() (+22 more)

### Community 10 - "Community 10"
Cohesion: 0.1
Nodes (15): handleCursorPan(), handleLogoLongPress(), handlePhraseLongPress(), init(), makeButton(), setupView(), WBKeyboardToolbarAction, appiumOpenSymbols (+7 more)

### Community 11 - "Community 11"
Cohesion: 0.12
Nodes (16): WBKey, WBKeyboardAction, character, delete, nextKeyboard, paste, `return`, shift (+8 more)

### Community 12 - "Community 12"
Cohesion: 0.16
Nodes (3): WBSearchCodeBadgeLabel, WBSearchResultCell, WBSearchViewController

### Community 13 - "Community 13"
Cohesion: 0.16
Nodes (5): WBKeyboardCandidate, WBKeyboardCandidateEngine, WBKeyboardCandidateEngineFactory, WBLWWubiCandidateEngine, WBPlaceholderCandidateEngine

### Community 14 - "Community 14"
Cohesion: 0.29
Nodes (18): capture(), clickAccessibilityIdIfPresent(), clickElement(), elementId(), focusInput(), getWindowRect(), keyboardTopFromSource(), main() (+10 more)

### Community 15 - "Community 15"
Cohesion: 0.32
Nodes (18): acceptOpenPromptIfPresent(), capture(), clickElement(), elementId(), ensureSwiftKeyboard(), findElement(), getTextValue(), getWindowRect() (+10 more)

### Community 16 - "Community 16"
Cohesion: 0.17
Nodes (6): AppDelegate, WBHostTabBarController, UIApplicationDelegate, UIResponder, UITabBarController, UITabBarControllerDelegate

### Community 17 - "Community 17"
Cohesion: 0.42
Nodes (14): capture(), clickElement(), elementId(), ensureHome(), findElement(), main(), maybeFindElement(), pressBack() (+6 more)

### Community 18 - "Community 18"
Cohesion: 0.45
Nodes (13): capture(), clickElement(), elementId(), ensureHome(), findElement(), main(), maybeFindElement(), pressBack() (+5 more)

### Community 19 - "Community 19"
Cohesion: 0.15
Nodes (12): WBLWWubiCandidateRecord, -initWithTextcodeindex, WBLWWubiEngineBridge, -backspace, -candidates, -commitTextcodeindex, -composingText, -inputText (+4 more)

### Community 21 - "Community 21"
Cohesion: 0.18
Nodes (7): SyncError, copyFailed, iCloudUnavailable, missingAsset, missingLocalDatabase, WBICloudPracticeSync, LocalizedError

### Community 23 - "Community 23"
Cohesion: 0.47
Nodes (10): capture(), clickElement(), findElement(), getSource(), main(), request(), returnHome(), routeSlug() (+2 more)

### Community 25 - "Community 25"
Cohesion: 0.56
Nodes (8): capture(), clickElement(), elementId(), findElement(), main(), request(), setElementValue(), sleep()

### Community 26 - "Community 26"
Cohesion: 0.61
Nodes (7): capture(), clickElement(), elementId(), findElement(), main(), request(), sleep()

### Community 27 - "Community 27"
Cohesion: 0.53
Nodes (4): add_objc_sources(), add_resource(), add_swift_sources(), ensure_group()

### Community 29 - "Community 29"
Cohesion: 0.6
Nodes (3): comparePair(), parseAveragePsnr(), run()

## Knowledge Gaps
- **70 isolated node(s):** `stems`, `one`, `two`, `three`, `single` (+65 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `WBPracticeSessionViewController` connect `Community 0` to `Community 3`, `Community 5`, `Community 7`?**
  _High betweenness centrality (0.156) - this node is a cross-community bridge._
- **Why does `WBPracticeWord` connect `Community 5` to `Community 8`, `Community 6`, `Community 7`?**
  _High betweenness centrality (0.144) - this node is a cross-community bridge._
- **Why does `WBLogoPanelState` connect `Community 8` to `Community 1`, `Community 2`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `WBPracticeSessionViewController` (e.g. with `.collectionView()` and `.showRandomArticlePractice()`) actually correct?**
  _`WBPracticeSessionViewController` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `stems`, `one`, `two` to the rest of the system?**
  _70 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._