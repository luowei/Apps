# Graph Report - /Users/luowei/projects/My_App/MyWallPaper/Swift  (2026-05-05)

## Corpus Check
- Corpus is ~35,790 words - fits in a single context window. You may not need a graph.

## Summary
- 340 nodes · 481 edges · 19 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.8)
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

## God Nodes (most connected - your core abstractions)
1. `CodingKeys` - 32 edges
2. `FavoritesManager` - 14 edges
3. `HomeViewModel` - 13 edges
4. `PhotoEditorView` - 11 edges
5. `MyWallPaperTests` - 10 edges
6. `APIClient` - 10 edges
7. `MockFavoriteRepository` - 10 edges
8. `FavoriteCategory` - 10 edges
9. `ImageCache` - 9 edges
10. `NetworkError` - 9 edges

## Surprising Connections (you probably didn't know these)
- `MyWallPaperTests` --inherits--> `XCTestCase`  [EXTRACTED]
  MyWallPaperTests/MyWallPaperTests.swift →   _Bridges community 6 → community 14_
- `FavoritePhotoGridItem` --inherits--> `View`  [EXTRACTED]
  MyWallPaper/Features/Favorites/FavoritesView.swift →   _Bridges community 0 → community 1_
- `PhotoDetailView` --inherits--> `View`  [EXTRACTED]
  MyWallPaper/Features/PhotoDetail/PhotoDetailView.swift →   _Bridges community 0 → community 4_
- `PhotoEditorView` --inherits--> `View`  [EXTRACTED]
  MyWallPaper/Features/PhotoEditor/PhotoEditorView.swift →   _Bridges community 0 → community 13_
- `ImageCache` --inherits--> `ObservableObject`  [EXTRACTED]
  MyWallPaper/Core/Cache/ImageCache.swift →   _Bridges community 1 → community 8_

## Communities (19 total, 8 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.08
Nodes (28): CategoryFilterButton, CategoryFilterView, CategorySelectionSheet, EmptyCategoryView, EmptyFavoritesView, FavoritesGridView, FavoritesManagementSheet, FavoritesView (+20 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (29): CaseIterable, FavoriteCategory, abstract, landscape, nature, portrait, uncategorized, urban (+21 more)

### Community 2 - "Community 2"
Cohesion: 0.06
Nodes (31): CodingKey, CodingKeys, bio, color, createdAt, description, download, downloadLocation (+23 more)

### Community 3 - "Community 3"
Cohesion: 0.1
Nodes (16): MockProduct, MockPurchaseManager, PurchaseError, failedVerification, productNotFound, purchaseFailed, PurchaseManager, LocalizedError (+8 more)

### Community 4 - "Community 4"
Cohesion: 0.09
Nodes (15): FullScreenPhotoView, ImageLoadingState, failed, fullImageLoaded, loading, thumbnailLoaded, PhotoDetailView, ShareSheet (+7 more)

### Community 5 - "Community 5"
Cohesion: 0.14
Nodes (16): Codable, Equatable, FavoriteItem, Identifiable, Endpoint, photo, photos, search (+8 more)

### Community 6 - "Community 6"
Cohesion: 0.13
Nodes (4): MyWallPaperTests, APIClient, APIClientProtocol, MockAPIClient

### Community 7 - "Community 7"
Cohesion: 0.18
Nodes (8): AboutView, FavoritesDetailSheet, FeatureRow, SettingRow, SettingsView, ThemeOptionRow, ThemeSelectionView, View

### Community 9 - "Community 9"
Cohesion: 0.14
Nodes (4): FavoritePhoto, FavoriteRepository, FavoriteRepositoryProtocol, MockFavoriteRepository

### Community 10 - "Community 10"
Cohesion: 0.13
Nodes (14): HomeViewAction, clearSearch, loadMorePhotos, loadPhotos, refresh, searchPhotos, HomeViewState, empty (+6 more)

### Community 16 - "Community 16"
Cohesion: 0.4
Nodes (5): ImageLoadState, failed, fullImageLoaded, loading, thumbnailLoaded

## Knowledge Gaps
- **80 isolated node(s):** `id`, `createdAt`, `width`, `height`, `color` (+75 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **8 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `FavoritesManager` connect `Community 11` to `Community 0`, `Community 1`?**
  _High betweenness centrality (0.234) - this node is a cross-community bridge._
- **Why does `HomeViewModel` connect `Community 12` to `Community 1`, `Community 10`, `Community 6`?**
  _High betweenness centrality (0.207) - this node is a cross-community bridge._
- **Why does `CodingKeys` connect `Community 2` to `Community 1`, `Community 5`?**
  _High betweenness centrality (0.206) - this node is a cross-community bridge._
- **What connects `id`, `createdAt`, `width` to the rest of the system?**
  _80 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._