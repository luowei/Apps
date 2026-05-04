# Graph Report - /private/tmp/second-brain-module-graphs/hugo-public-site  (2026-05-05)

## Corpus Check
- Large corpus: 1056 files · ~278,550 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 232 nodes · 347 edges · 16 communities detected
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
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 16|Community 16]]

## God Nodes (most connected - your core abstractions)
1. `importSingleMarkdown()` - 14 edges
2. `main()` - 13 edges
3. `buildImportData()` - 11 edges
4. `renderCalendar()` - 10 edges
5. `renderResults()` - 8 edges
6. `main()` - 6 edges
7. `renderFrontMatter()` - 6 edges
8. `rewriteRelativeAssets()` - 6 edges
9. `escapeHtml()` - 6 edges
10. `applySearch()` - 6 edges

## Surprising Connections (you probably didn't know these)
- `main()` --calls--> `emptyContentDirectory()`  [EXTRACTED]
  packages/content-importer/src/index.ts → packages/public-exporter/src/index.ts
- `main()` --calls--> `emptyGeneratedArchiveMonthDirectories()`  [EXTRACTED]
  packages/content-importer/src/index.ts → packages/public-exporter/src/index.ts
- `main()` --calls--> `assertPublishedDates()`  [EXTRACTED]
  packages/content-importer/src/index.ts → packages/public-exporter/src/index.ts
- `main()` --calls--> `writeActivityCalendarData()`  [EXTRACTED]
  packages/content-importer/src/index.ts → packages/public-exporter/src/index.ts
- `main()` --calls--> `writeSiteSettingsData()`  [EXTRACTED]
  packages/content-importer/src/index.ts → packages/public-exporter/src/index.ts

## Communities (22 total, 2 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.17
Nodes (19): buildImportData(), buildInventory(), classify(), main(), normalizeRoutePath(), normalizeWonderkibodLegacyUrl(), nowUnix(), parseArgs() (+11 more)

### Community 1 - "Community 1"
Cohesion: 0.2
Nodes (21): buildApiUrl(), buildHeaders(), deriveMemoId(), derivePublishedAt(), deriveSlug(), deriveStatus(), deriveTags(), deriveVisibility() (+13 more)

### Community 2 - "Community 2"
Cohesion: 0.18
Nodes (18): assertPublishedDates(), emptyContentDirectory(), emptyGeneratedArchiveMonthDirectories(), formatTomlArray(), formatTomlString(), main(), parseGlobPatterns(), parseOptionalLimit() (+10 more)

### Community 3 - "Community 3"
Cohesion: 0.24
Nodes (14): applySearch(), buildFilterTags(), buildResultsHtml(), buildSnippet(), escapeHtml(), fetchIndex(), highlightText(), renderNextPage() (+6 more)

### Community 4 - "Community 4"
Cohesion: 0.13
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 5 - "Community 5"
Cohesion: 0.26
Nodes (15): addMonths(), buildArchiveHref(), buildMonthOptions(), buildYearOptions(), clampMonth(), escapeHtml(), escapeSelectorValue(), getLevel() (+7 more)

### Community 6 - "Community 6"
Cohesion: 0.15
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 7 - "Community 7"
Cohesion: 0.15
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 8 - "Community 8"
Cohesion: 0.16
Nodes (4): deriveSummary(), parseFileName(), sanitizeSlug(), stripMarkdownToText()

### Community 9 - "Community 9"
Cohesion: 0.3
Nodes (9): buildActivityCalendarIndex(), buildSearchIndex(), encode(), normalizeString(), truncateTitle(), writeArray(), writeInteger(), writeString() (+1 more)

### Community 12 - "Community 12"
Cohesion: 0.48
Nodes (5): retry(), sleep(), syncOne(), worker(), writeState()

### Community 13 - "Community 13"
Cohesion: 0.52
Nodes (5): collapseItem(), extractListHtml(), loadItem(), setToggle(), toggleItem()

### Community 14 - "Community 14"
Cohesion: 0.67
Nodes (5): getGiscusTheme(), getSiteConfig(), init(), mountGiscus(), syncGiscusTheme()

### Community 16 - "Community 16"
Cohesion: 0.6
Nodes (3): createReader(), fetchMessagePackGzip(), gunzip()

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `main()` connect `Community 2` to `Community 1`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Why does `importSingleMarkdown()` connect `Community 1` to `Community 2`?**
  _High betweenness centrality (0.005) - this node is a cross-community bridge._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._