# Graph Report - /private/tmp/second-brain-module-graphs/wodedata-site  (2026-05-05)

## Corpus Check
- Corpus is ~14,031 words - fits in a single context window. You may not need a graph.

## Summary
- 189 nodes · 235 edges · 14 communities detected
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
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
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 17|Community 17]]

## God Nodes (most connected - your core abstractions)
1. `buildImportData()` - 11 edges
2. `replaceLegacyVariables()` - 9 edges
3. `main()` - 6 edges
4. `writeValue()` - 5 edges
5. `walkFiles()` - 4 edges
6. `buildInventory()` - 4 edges
7. `encode()` - 4 edges
8. `buildActivityCalendarIndex()` - 4 edges
9. `loadExportData()` - 4 edges
10. `renderMarkdownLite()` - 4 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (24 total, 4 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.17
Nodes (19): buildImportData(), buildInventory(), classify(), main(), normalizeRoutePath(), normalizeWonderkibodLegacyUrl(), nowUnix(), parseArgs() (+11 more)

### Community 1 - "Community 1"
Cohesion: 0.15
Nodes (16): decodeHtml(), escapeHtml(), excerptMarkdown(), extractLegacyContactItems(), extractLegacyMediaItems(), extractLegacyParagraphs(), extractLegacyPortfolioItems(), extractLegacySectionSummary() (+8 more)

### Community 2 - "Community 2"
Cohesion: 0.13
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 3 - "Community 3"
Cohesion: 0.15
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 4 - "Community 4"
Cohesion: 0.15
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 5 - "Community 5"
Cohesion: 0.16
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 6 - "Community 6"
Cohesion: 0.3
Nodes (9): buildActivityCalendarIndex(), buildSearchIndex(), encode(), normalizeString(), truncateTitle(), writeArray(), writeInteger(), writeString() (+1 more)

### Community 8 - "Community 8"
Cohesion: 0.42
Nodes (8): loadExportData(), loadFromD1(), loadFromFallbackJson(), main(), mapSiteConfig(), queryRemote(), runPnpmExec(), writeJson()

### Community 10 - "Community 10"
Cohesion: 0.48
Nodes (5): retry(), sleep(), syncOne(), worker(), writeState()

### Community 14 - "Community 14"
Cohesion: 0.83
Nodes (3): buildWodedataAppleAppArgument(), buildWodedataAppleItunesAppContent(), resolveWodedataAppleAppId()

## Knowledge Gaps
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._