# Graph Report - /Users/luowei/projects/My_App/MyBrowser/MyBrowser_Swift  (2026-05-05)

## Corpus Check
- Corpus is ~33,819 words - fits in a single context window. You may not need a graph.

## Summary
- 179 nodes · 235 edges · 9 communities detected
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 13 edges (avg confidence: 0.8)
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

## God Nodes (most connected - your core abstractions)
1. `WebViewManager` - 22 edges
2. `BookmarkService` - 21 edges
3. `MyBrowserUITests` - 15 edges
4. `BrowserEngine` - 15 edges
5. `MyBrowserTests` - 14 edges
6. `DIContainer` - 12 edges
7. `Bookmark` - 11 edges
8. `BookmarksView` - 7 edges
9. `MyBrowserApp` - 6 edges
10. `BrowserView` - 6 edges

## Surprising Connections (you probably didn't know these)
- `MyBrowserTests` --inherits--> `XCTestCase`  [EXTRACTED]
  MyBrowserTests/MyBrowserTests.swift →   _Bridges community 5 → community 3_
- `BrowserView` --inherits--> `View`  [EXTRACTED]
  MyBrowser/Views/BrowserView.swift →   _Bridges community 0 → community 8_
- `BookmarksView` --inherits--> `View`  [EXTRACTED]
  MyBrowser/Views/BookmarksView.swift →   _Bridges community 0 → community 6_
- `Bookmark` --inherits--> `Identifiable`  [EXTRACTED]
  MyBrowserKit/DataService/BookmarkService.swift →   _Bridges community 0 → community 2_
- `BookmarkService` --inherits--> `ObservableObject`  [EXTRACTED]
  MyBrowserKit/DataService/BookmarkService.swift →   _Bridges community 1 → community 2_

## Communities (11 total, 2 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.1
Nodes (19): Identifiable, ContentView, View, FeatureCard, HistoryItem, HistoryView, HomeView, QuickAccessCard (+11 more)

### Community 1 - "Community 1"
Cohesion: 0.09
Nodes (9): NSObject, ObservableObject, UIViewRepresentable, WebView, WebViewManager, WebViewManagerProtocol, WKNavigationDelegate, WKScriptMessageHandler (+1 more)

### Community 2 - "Community 2"
Cohesion: 0.11
Nodes (7): Codable, Bookmark, BookmarkService, BookmarkServiceProtocol, CoreDataManager, CoreDataManagerProtocol, Equatable

### Community 3 - "Community 3"
Cohesion: 0.11
Nodes (4): MockService, MockServiceProtocol, MyBrowserTests, DIContainer

### Community 4 - "Community 4"
Cohesion: 0.11
Nodes (12): BrowserEngine, BrowserEngineProtocol, BrowserError, invalidURL, loadingFailed, networkError, BrowserState, error (+4 more)

### Community 5 - "Community 5"
Cohesion: 0.1
Nodes (3): MyBrowserUITests, MyBrowserUITestsLaunchTests, XCTestCase

### Community 6 - "Community 6"
Cohesion: 0.22
Nodes (3): AddBookmarkView, BookmarkRow, BookmarksView

## Knowledge Gaps
- **7 isolated node(s):** `idle`, `loading`, `loaded`, `error`, `invalidURL` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `MyBrowserTests` connect `Community 3` to `Community 2`, `Community 5`?**
  _High betweenness centrality (0.419) - this node is a cross-community bridge._
- **Why does `Bookmark` connect `Community 2` to `Community 0`, `Community 6`?**
  _High betweenness centrality (0.399) - this node is a cross-community bridge._
- **Why does `BookmarkService` connect `Community 2` to `Community 1`, `Community 3`?**
  _High betweenness centrality (0.307) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `BookmarkService` (e.g. with `.testBookmarkServiceFetch()` and `.testBookmarkServiceAdd()`) actually correct?**
  _`BookmarkService` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `BrowserEngine` (e.g. with `.testBrowserEngineInitialization()` and `.testBrowserEngineLoadURL()`) actually correct?**
  _`BrowserEngine` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `idle`, `loading`, `loaded` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.1 - nodes in this community are weakly interconnected._