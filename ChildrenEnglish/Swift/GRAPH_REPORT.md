# Graph Report - /Users/luowei/projects/My_App/ChildrenEnglish/Swift  (2026-05-05)

## Corpus Check
- Corpus is ~8,420 words - fits in a single context window. You may not need a graph.

## Summary
- 234 nodes · 357 edges · 15 communities detected
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 28 edges (avg confidence: 0.8)
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

## God Nodes (most connected - your core abstractions)
1. `VideoPlayerViewModel` - 19 edges
2. `DefaultVideoService` - 14 edges
3. `OSSService` - 11 edges
4. `HomeViewModel` - 11 edges
5. `DefaultFavoriteService` - 10 edges
6. `OSSXMLParser` - 8 edges
7. `HomeCoordinator` - 8 edges
8. `Coordinator` - 8 edges
9. `VideoListViewModel` - 8 edges
10. `Video` - 8 edges

## Surprising Connections (you probably didn't know these)
- `PurchaseView` --inherits--> `View`  [EXTRACTED]
  Features/Home/Coordinators/HomeCoordinator.swift →   _Bridges community 6 → community 0_
- `CustomVideoPlayer` --inherits--> `View`  [EXTRACTED]
  Features/Video/Views/AVPlayerView.swift →   _Bridges community 6 → community 7_
- `VideoListView` --inherits--> `View`  [EXTRACTED]
  Features/Video/Views/VideoListView.swift →   _Bridges community 6 → community 5_
- `UserService` --inherits--> `ObservableObject`  [EXTRACTED]
  Core/Services/UserService.swift →   _Bridges community 5 → community 11_
- `OSSObject` --inherits--> `Codable`  [EXTRACTED]
  Core/Services/OSSService.swift →   _Bridges community 4 → community 3_

## Communities (25 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.13
Nodes (8): AppCoordinator, SettingsCoordinator, TabBarCoordinator, BaseCoordinator, HomeCoordinator, PurchaseCoordinator, PurchaseView, VideoCoordinator

### Community 1 - "Community 1"
Cohesion: 0.15
Nodes (3): DefaultFavoriteService, FavoriteServiceProtocol, VideoPlayerViewModel

### Community 2 - "Community 2"
Cohesion: 0.15
Nodes (5): DefaultVideoService, MockVideoService, VideoListResponse, VideoServiceProtocol, String

### Community 3 - "Community 3"
Cohesion: 0.14
Nodes (14): CaseIterable, Codable, Equatable, Identifiable, Banner, PlaybackRecord, User, UserSettings (+6 more)

### Community 4 - "Community 4"
Cohesion: 0.16
Nodes (7): OSSConfig, OSSListResponse, OSSObject, OSSService, OSSServiceProtocol, OSSXMLParser, XMLParserDelegate

### Community 5 - "Community 5"
Cohesion: 0.13
Nodes (6): BaseViewModel, ViewModel, ObservableObject, VideoListItemView, VideoListView, VideoListViewModel

### Community 6 - "Community 6"
Cohesion: 0.16
Nodes (13): ContentView, FavoritesView, SimpleSettingsView, View, BannerItemView, BannerView, CategoryGridView, CategoryItemView (+5 more)

### Community 7 - "Community 7"
Cohesion: 0.15
Nodes (5): NSObject, UIViewControllerRepresentable, AVPlayerView, Coordinator, CustomVideoPlayer

### Community 9 - "Community 9"
Cohesion: 0.25
Nodes (7): API, AppConstants, NotificationNames, OSS, URLSchemes, UserDefaultsKeys, VideoCategories

### Community 10 - "Community 10"
Cohesion: 0.33
Nodes (3): AnyObject, BaseCoordinator, Coordinator

### Community 12 - "Community 12"
Cohesion: 0.33
Nodes (4): BaseRepository, LocalDataSource, NetworkDataSource, Repository

### Community 13 - "Community 13"
Cohesion: 0.33
Nodes (6): LocalizedError, OSSError, invalidResponse, requestFailed, signatureError, xmlParsingError

## Knowledge Gaps
- **18 isolated node(s):** `AppConstants`, `API`, `OSS`, `VideoCategories`, `UserDefaultsKeys` (+13 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `VideoListItemView` connect `Community 5` to `Community 6`?**
  _High betweenness centrality (0.173) - this node is a cross-community bridge._
- **Why does `CustomVideoPlayer` connect `Community 7` to `Community 2`, `Community 6`?**
  _High betweenness centrality (0.151) - this node is a cross-community bridge._
- **Why does `VideoListViewModel` connect `Community 5` to `Community 8`?**
  _High betweenness centrality (0.148) - this node is a cross-community bridge._
- **What connects `AppConstants`, `API`, `OSS` to the rest of the system?**
  _18 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.14 - nodes in this community are weakly interconnected._
- **Should `Community 5` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._