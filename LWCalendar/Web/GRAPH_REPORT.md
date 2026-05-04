# Graph Report - /Users/luowei/projects/My_App/LWCalendar/Web  (2026-05-05)

## Corpus Check
- Corpus is ~25,246 words - fits in a single context window. You may not need a graph.

## Summary
- 173 nodes · 190 edges · 8 communities detected
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 10 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 8|Community 8]]

## God Nodes (most connected - your core abstractions)
1. `DateUtils` - 46 edges
2. `NotificationService` - 20 edges
3. `ApiClient` - 12 edges
4. `ChineseCalendarUtils` - 12 edges
5. `useNotifications()` - 4 edges
6. `initSettingsStore()` - 3 edges
7. `useTemplates()` - 3 edges
8. `handleTodoSubmit()` - 3 edges
9. `handleTodoSubmit()` - 3 edges
10. `checkDatabaseHealth()` - 2 edges

## Surprising Connections (you probably didn't know these)
- `NotificationSettings()` --calls--> `useNotifications()`  [INFERRED]
  client/src/components/Settings/NotificationSettings.tsx → client/src/hooks/useNotifications.ts

## Communities (32 total, 6 thin omitted)

### Community 1 - "Community 1"
Cohesion: 0.12
Nodes (7): ApiClient, handleTodoDelete(), handleTodoSubmit(), handleTodoUpdate(), handleTodoDelete(), handleTodoSubmit(), handleTodoUpdate()

### Community 2 - "Community 2"
Cohesion: 0.15
Nodes (3): useNotifications(), NotificationService, NotificationSettings()

## Knowledge Gaps
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `DateUtils` connect `Community 0` to `Community 1`, `Community 2`, `Community 3`, `Community 9`, `Community 14`, `Community 15`, `Community 16`, `Community 17`, `Community 18`?**
  _High betweenness centrality (0.381) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `useNotifications()` (e.g. with `NotificationSettings()` and `.isSupported()`) actually correct?**
  _`useNotifications()` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._