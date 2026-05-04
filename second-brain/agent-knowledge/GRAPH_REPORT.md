# Graph Report - /private/tmp/second-brain-module-graphs/agent-knowledge  (2026-05-05)

## Corpus Check
- Corpus is ~19,627 words - fits in a single context window. You may not need a graph.

## Summary
- 129 nodes · 305 edges · 15 communities detected
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

## God Nodes (most connected - your core abstractions)
1. `getWodedataRepo()` - 24 edges
2. `renderWodedataNav()` - 17 edges
3. `renderWodedataMissingDbPage()` - 17 edges
4. `buildWodedataPostSaveRedirectSuffix()` - 11 edges
5. `renderWodedataPodcastEditPage()` - 11 edges
6. `renderWodedataSaveAndPublishToast()` - 10 edges
7. `renderWodedataMobileEmbedPage()` - 10 edges
8. `renderWodedataEditToast()` - 10 edges
9. `renderWodedataSettingsPage()` - 9 edges
10. `renderWodedataAppEditPage()` - 9 edges

## Surprising Connections (you probably didn't know these)
- `renderWodedataDashboard()` --calls--> `renderWodedataNav()`  [EXTRACTED]
  index.ts → index.ts  _Bridges community 1 → community 2_
- `renderWodedataSettingsPage()` --calls--> `formatWodedataNavigationTextarea()`  [EXTRACTED]
  index.ts → index.ts  _Bridges community 0 → community 1_
- `renderWodedataPodcastEditPage()` --calls--> `buildWodedataPodcastGuid()`  [EXTRACTED]
  index.ts → index.ts  _Bridges community 3 → community 1_
- `buildWodedataPostSaveRedirectSuffix()` --calls--> `dispatchWodedataDeploy()`  [EXTRACTED]
  index.ts → index.ts  _Bridges community 4 → community 3_
- `renderWodedataAppPage()` --calls--> `renderWodedataAppTreeStateScript()`  [EXTRACTED]
  index.ts → index.ts  _Bridges community 11 → community 1_

## Communities (16 total, 1 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.08
Nodes (9): buildWodedataMobileEmbedMatches(), deriveSlugFromTitle(), formatWodedataNavigationTextarea(), formatWodedataRevisionType(), getWodedataHomeSourceContent(), loadWodedataHomeSourceFile(), renderWodedataAppTree(), renderWodedataMobileEmbedTree() (+1 more)

### Community 1 - "Community 1"
Cohesion: 0.25
Nodes (26): buildWodedataPodcastUploadField(), formatWodedataDatetimeLocal(), getWodedataRepo(), parseWodedataObjectJson(), renderWodedataAppEditPage(), renderWodedataAppPage(), renderWodedataEditToast(), renderWodedataHomeEditPage() (+18 more)

### Community 2 - "Community 2"
Cohesion: 0.21
Nodes (13): renderEditToast(), renderManageFeedback(), renderPageToast(), renderWikiPublishHint(), renderWikiSaveActions(), renderWikiSaveAndPublishToast(), renderWikiSaveToast(), renderWikiSiteSettingsPage() (+5 more)

### Community 3 - "Community 3"
Cohesion: 0.18
Nodes (12): buildWodedataPodcastGuid(), buildWodedataPostSaveRedirectSuffix(), parseWodedataModuleData(), parseWodedataPublishedAt(), rollbackWodedataRevision(), saveWodedataAppPage(), saveWodedataHomeModule(), saveWodedataMobileEmbedPage() (+4 more)

### Community 4 - "Community 4"
Cohesion: 0.22
Nodes (9): buildWikiSiteSaveRedirectSuffix(), dispatchGitHubWorkflow(), dispatchWodedataDeploy(), normalizeAnalyticsSnippet(), parseWodedataNavigationTextarea(), saveWikiSiteSettings(), saveWodedataSettings(), shouldPublishWikiAfterSave() (+1 more)

### Community 5 - "Community 5"
Cohesion: 0.29
Nodes (7): fetchAgentKnowledgeManifest(), maskAgentKnowledgeManifestUrl(), normalizeAgentKnowledgeSection(), renderAgentKnowledgePage(), renderAgentKnowledgeTable(), renderAgentKnowledgeTabs(), sumAgentKnowledgeMetric()

### Community 6 - "Community 6"
Cohesion: 0.4
Nodes (5): highlightSearchText(), renderHighlightedPostTitleLink(), renderLockIcon(), renderPostHeadingTitle(), renderPostTitleLink()

### Community 7 - "Community 7"
Cohesion: 0.4
Nodes (5): renderAsyncPager(), renderHomePostsPanel(), renderManageAssetsPanel(), renderManagePostsPanel(), renderMemberPostItems()

### Community 8 - "Community 8"
Cohesion: 0.5
Nodes (4): formatUnixTimestampForExport(), renderPostMarkdownExport(), yamlArray(), yamlQuote()

### Community 9 - "Community 9"
Cohesion: 0.67
Nodes (4): createMemoId(), formatDatetimeLocalInput(), normalizeFormPublishedAt(), renderPostForm()

### Community 11 - "Community 11"
Cohesion: 0.67
Nodes (3): renderWodedataAppTreeStateScript(), renderWodedataMobileEmbedTreeStateScript(), renderWodedataTreeStateScript()

### Community 12 - "Community 12"
Cohesion: 0.67
Nodes (3): formatWodedataAppNodeTooltip(), getWodedataAppNodeLabel(), renderWodedataAppTreeNode()

### Community 13 - "Community 13"
Cohesion: 0.67
Nodes (3): inferWodedataPodcastExtension(), sanitizeOssFileName(), uploadWodedataPodcastAsset()

### Community 14 - "Community 14"
Cohesion: 1.0
Nodes (3): getWodedataAppSourceContent(), loadWodedataAppSourceFile(), normalizeWodedataAppRoutePath()

## Knowledge Gaps
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `getWodedataRepo()` connect `Community 1` to `Community 0`, `Community 2`, `Community 3`, `Community 4`?**
  _High betweenness centrality (0.011) - this node is a cross-community bridge._
- **Why does `renderWodedataNav()` connect `Community 1` to `Community 0`, `Community 2`?**
  _High betweenness centrality (0.003) - this node is a cross-community bridge._
- **Why does `renderWodedataMissingDbPage()` connect `Community 1` to `Community 0`, `Community 2`?**
  _High betweenness centrality (0.003) - this node is a cross-community bridge._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._