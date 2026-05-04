# Graph Report - /Users/luowei/projects/My_App/MyWallPaper/Web  (2026-05-05)

## Corpus Check
- Corpus is ~29,072 words - fits in a single context window. You may not need a graph.

## Summary
- 146 nodes · 197 edges · 9 communities detected
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 11 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 9|Community 9]]

## God Nodes (most connected - your core abstractions)
1. `cn()` - 17 edges
2. `QuickStart` - 16 edges
3. `UnsplashAPI` - 11 edges
4. `useToast()` - 9 edges
5. `getDatabaseConfig()` - 8 edges
6. `PhotoGridSkeleton()` - 5 edges
7. `useFavorites()` - 5 edges
8. `toast()` - 5 edges
9. `testDatabaseConnection()` - 5 edges
10. `downloadPhoto()` - 5 edges

## Surprising Connections (you probably didn't know these)
- `checkDatabase()` --calls--> `getDatabaseConfig()`  [INFERRED]
  scripts/check-database.js → src/lib/db/config.ts
- `checkDatabase()` --calls--> `testDatabaseConnection()`  [INFERRED]
  scripts/check-database.js → src/lib/db/config.ts
- `handleDownload()` --calls--> `toast()`  [INFERRED]
  src/components/features/photos/photo-viewer.tsx → src/hooks/use-toast.ts
- `handleShare()` --calls--> `toast()`  [INFERRED]
  src/components/features/photos/photo-viewer.tsx → src/hooks/use-toast.ts
- `GET()` --calls--> `getDatabaseConfig()`  [INFERRED]
  src/app/api/health/route.ts → src/lib/db/config.ts

## Communities (26 total, 5 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.1
Nodes (5): useFavorites(), useToast(), cn(), PhotoCard(), PhotoGridSkeleton()

### Community 3 - "Community 3"
Cohesion: 0.21
Nodes (7): downloadPhoto(), getPhotoAttributionUrl(), getPhotographerAttribution(), UnsplashAPIError, formatNumber(), handleDownload(), handleShare()

### Community 4 - "Community 4"
Cohesion: 0.35
Nodes (8): createPrismaClient(), ensureDataDirectory(), getDatabaseConfig(), runMigrations(), testDatabaseConnection(), GET(), POST(), checkDatabase()

### Community 7 - "Community 7"
Cohesion: 0.6
Nodes (5): addToRemoveQueue(), dispatch(), genId(), reducer(), toast()

## Knowledge Gaps
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `cn()` connect `Community 0` to `Community 2`, `Community 3`, `Community 6`?**
  _High betweenness centrality (0.180) - this node is a cross-community bridge._
- **Why does `UnsplashAPI` connect `Community 5` to `Community 0`, `Community 3`?**
  _High betweenness centrality (0.063) - this node is a cross-community bridge._
- **Why does `useToast()` connect `Community 0` to `Community 3`, `Community 7`?**
  _High betweenness centrality (0.044) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `getDatabaseConfig()` (e.g. with `checkDatabase()` and `GET()`) actually correct?**
  _`getDatabaseConfig()` has 3 INFERRED edges - model-reasoned connections that need verification._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.1 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._