# Graph Report - /Users/luowei/projects/My_App/ChildrenEnglish/Web  (2026-05-05)

## Corpus Check
- Corpus is ~14,897 words - fits in a single context window. You may not need a graph.

## Summary
- 105 nodes · 74 edges · 2 communities detected
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 1 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]

## God Nodes (most connected - your core abstractions)
1. `main()` - 8 edges
2. `initializeDatabase()` - 3 edges
3. `startServer()` - 2 edges
4. `errorHandler()` - 2 edges
5. `createDefaultAdmin()` - 2 edges
6. `createDemoUser()` - 2 edges
7. `createCategories()` - 2 edges
8. `createBanners()` - 2 edges
9. `createSampleVideos()` - 2 edges
10. `createSampleFavorites()` - 2 edges

## Surprising Connections (you probably didn't know these)
- `startServer()` --calls--> `initializeDatabase()`  [INFERRED]
  server/src/index.ts → server/src/config/database.ts

## Communities (39 total, 0 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.22
Nodes (3): initializeDatabase(), errorHandler(), startServer()

### Community 1 - "Community 1"
Cohesion: 0.42
Nodes (8): createBanners(), createCategories(), createDefaultAdmin(), createDemoUser(), createSampleFavorites(), createSamplePlaybackRecords(), createSampleVideos(), main()

## Suggested Questions
_Not enough signal to generate questions. This usually means the corpus has no AMBIGUOUS edges, no bridge nodes, no INFERRED relationships, and all communities are tightly cohesive. Add more files or run with --mode deep to extract richer edges._