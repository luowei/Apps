# Graph Report - /Users/luowei/projects/My_App/WBInputMethod/web  (2026-05-05)

## Corpus Check
- Corpus is ~16,327 words - fits in a single context window. You may not need a graph.

## Summary
- 95 nodes · 85 edges · 9 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.8)
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
1. `WubiService` - 5 edges
2. `executeConfirmAction()` - 4 edges
3. `optionalAuthMiddleware()` - 3 edges
4. `register()` - 3 edges
5. `login()` - 3 edges
6. `handleSubmit()` - 3 edges
7. `loadStatistics()` - 3 edges
8. `handleSearch()` - 3 edges
9. `errorHandler()` - 2 edges
10. `notFoundHandler()` - 2 edges

## Surprising Connections (you probably didn't know these)
- `handleSubmit()` --calls--> `register()`  [INFERRED]
  client/src/pages/RegisterPage.tsx → server/src/controllers/authController.ts
- `handleSubmit()` --calls--> `login()`  [INFERRED]
  client/src/pages/LoginPage.tsx → server/src/controllers/authController.ts

## Communities (27 total, 2 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.19
Nodes (4): clearAllData(), executeConfirmAction(), exportData(), resetSettings()

### Community 1 - "Community 1"
Cohesion: 0.22
Nodes (5): login(), logout(), register(), handleSubmit(), handleSubmit()

### Community 2 - "Community 2"
Cohesion: 0.28
Nodes (3): handleSearch(), saveSearchHistory(), searchWubi()

### Community 3 - "Community 3"
Cohesion: 0.25
Nodes (3): authMiddleware(), errorHandler(), notFoundHandler()

### Community 4 - "Community 4"
Cohesion: 0.39
Nodes (5): getCharacter(), getCode(), getRandomCharacters(), search(), optionalAuthMiddleware()

### Community 5 - "Community 5"
Cohesion: 0.36
Nodes (5): generatePracticeContent(), handleInputChange(), handleKeyPress(), handleSubmit(), startPractice()

### Community 6 - "Community 6"
Cohesion: 0.32
Nodes (3): analyzeData(), generateMockData(), loadStatistics()

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `authMiddleware()` connect `Community 3` to `Community 4`?**
  _High betweenness centrality (0.013) - this node is a cross-community bridge._