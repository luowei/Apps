# Graph Report - /private/tmp/second-brain-module-graphs/members-app  (2026-05-05)

## Corpus Check
- 36 files · ~54,808 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 309 nodes · 651 edges · 21 communities detected
- Extraction: 91% EXTRACTED · 9% INFERRED · 0% AMBIGUOUS · INFERRED: 61 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]

## God Nodes (most connected - your core abstractions)
1. `PostsRepository` - 50 edges
2. `requireEditor()` - 29 edges
3. `WodedataRepository` - 26 edges
4. `getWodedataRepo()` - 24 edges
5. `layoutHtml()` - 22 edges
6. `renderWodedataMissingDbPage()` - 18 edges
7. `renderWodedataNav()` - 17 edges
8. `renderWodedataPodcastEditPage()` - 13 edges
9. `buildWodedataPostSaveRedirectSuffix()` - 11 edges
10. `renderWodedataMobileEmbedPage()` - 11 edges

## Surprising Connections (you probably didn't know these)
- `renderAgentKnowledgePage()` --calls--> `layoutHtml()`  [INFERRED]
  apps/members-app/src/index.ts → apps/members-app/src/lib/html.ts
- `renderWikiSiteSettingsPage()` --calls--> `requireEditor()`  [INFERRED]
  apps/members-app/src/index.ts → apps/members-app/src/lib/auth.ts
- `renderWikiSiteSettingsPage()` --calls--> `layoutHtml()`  [INFERRED]
  apps/members-app/src/index.ts → apps/members-app/src/lib/html.ts
- `sanitizeOssFileName()` --calls--> `slugify()`  [INFERRED]
  apps/members-app/src/index.ts → apps/members-app/src/lib/format-utils.ts
- `formatWodedataAppNodeTooltip()` --calls--> `formatUnixTimestamp()`  [INFERRED]
  apps/members-app/src/index.ts → apps/members-app/src/lib/html.ts

## Communities (30 total, 2 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (4): buildSafeFtsQuery(), getNormalizedSearchTerms(), normalizeSearchInput(), PostsRepository

### Community 1 - "Community 1"
Cohesion: 0.26
Nodes (29): layoutHtml(), formatWodedataDatetimeLocal(), getWodedataRepo(), parseWodedataObjectJson(), renderEditToast(), renderWodedataAppEditPage(), renderWodedataAppPage(), renderWodedataDashboard() (+21 more)

### Community 2 - "Community 2"
Cohesion: 0.08
Nodes (12): buildWodedataPodcastUploadField(), formatWodedataAppNodeTooltip(), formatWodedataNavigationTextarea(), formatWodedataRevisionType(), getWodedataAppNodeLabel(), getWodedataHomeSourceContent(), loadWodedataHomeSourceFile(), renderWodedataAppTree() (+4 more)

### Community 4 - "Community 4"
Cohesion: 0.13
Nodes (12): buildAssetObjectKey(), buildAssetPublicUrl(), buildMembersAssetUrl(), getAssetPublicBaseUrl(), getMembersAssetBaseUrl(), hasSharedSecret(), requireEditorOrSecret(), requireMember() (+4 more)

### Community 5 - "Community 5"
Cohesion: 0.13
Nodes (23): requireEditor(), buildWikiSiteSaveRedirectSuffix(), buildWodedataPodcastGuid(), buildWodedataPostSaveRedirectSuffix(), dispatchGitHubWorkflow(), dispatchWodedataDeploy(), loadWodedataPodcastAudioInfo(), normalizeAnalyticsSnippet() (+15 more)

### Community 6 - "Community 6"
Cohesion: 0.14
Nodes (19): buildAssetProbeRequest(), buildAssetProbeResult(), buildAssetProbeUrl(), escapeRegExp(), fetchLatestMirrorRun(), findMembersAssetSamples(), findPublicAssetSamples(), formatIsoTimestamp() (+11 more)

### Community 7 - "Community 7"
Cohesion: 0.18
Nodes (17): base64Encode(), getOssConfig(), hmacSha1Base64(), trimSlash(), uploadToAliyunOss(), encodePath(), formatAmzDate(), getS3Config() (+9 more)

### Community 8 - "Community 8"
Cohesion: 0.15
Nodes (14): digestHex(), formatBytes(), formatProviderMode(), inferExtension(), manageScopeToSourceSite(), maskEmail(), normalizeManageScope(), parsePositiveInt() (+6 more)

### Community 9 - "Community 9"
Cohesion: 0.32
Nodes (8): renderManageFeedback(), renderPageToast(), renderWikiPublishHint(), renderWikiSaveActions(), renderWikiSaveAndPublishToast(), renderWikiSaveToast(), renderWikiSiteSettingsPage(), renderWodedataDeployToast()

### Community 10 - "Community 10"
Cohesion: 0.32
Nodes (5): canonicalizeRoutePath(), extractEmbedRoutePath(), findWodedataMobileEmbedItemByRoutePath(), listWodedataMobileEmbedSources(), buildWodedataMobileEmbedMatches()

### Community 11 - "Community 11"
Cohesion: 0.29
Nodes (7): fetchAgentKnowledgeManifest(), maskAgentKnowledgeManifestUrl(), normalizeAgentKnowledgeSection(), renderAgentKnowledgePage(), renderAgentKnowledgeTable(), renderAgentKnowledgeTabs(), sumAgentKnowledgeMetric()

### Community 12 - "Community 12"
Cohesion: 0.4
Nodes (3): extractHeadings(), renderMarkdown(), slugifyHeading()

### Community 13 - "Community 13"
Cohesion: 0.4
Nodes (5): highlightSearchText(), renderHighlightedPostTitleLink(), renderLockIcon(), renderPostHeadingTitle(), renderPostTitleLink()

### Community 14 - "Community 14"
Cohesion: 0.4
Nodes (5): renderAsyncPager(), renderHomePostsPanel(), renderManageAssetsPanel(), renderManagePostsPanel(), renderMemberPostItems()

### Community 15 - "Community 15"
Cohesion: 0.83
Nodes (3): basenameFromUrl(), extractPostAssets(), isImageUrl()

### Community 16 - "Community 16"
Cohesion: 0.5
Nodes (4): formatUnixTimestampForExport(), renderPostMarkdownExport(), yamlArray(), yamlQuote()

### Community 17 - "Community 17"
Cohesion: 0.67
Nodes (4): createMemoId(), formatDatetimeLocalInput(), normalizeFormPublishedAt(), renderPostForm()

### Community 19 - "Community 19"
Cohesion: 1.0
Nodes (3): getWodedataAppSourceContent(), loadWodedataAppSourceFile(), normalizeWodedataAppRoutePath()

### Community 20 - "Community 20"
Cohesion: 0.67
Nodes (3): renderWodedataAppTreeStateScript(), renderWodedataMobileEmbedTreeStateScript(), renderWodedataTreeStateScript()

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `PostsRepository` connect `Community 0` to `Community 2`, `Community 4`?**
  _High betweenness centrality (0.279) - this node is a cross-community bridge._
- **Why does `WodedataRepository` connect `Community 3` to `Community 2`?**
  _High betweenness centrality (0.148) - this node is a cross-community bridge._
- **Why does `uploadToWodedataS3()` connect `Community 7` to `Community 2`?**
  _High betweenness centrality (0.055) - this node is a cross-community bridge._
- **Are the 24 inferred relationships involving `requireEditor()` (e.g. with `renderWikiSiteSettingsPage()` and `loadWodedataHomeSourceFile()`) actually correct?**
  _`requireEditor()` has 24 INFERRED edges - model-reasoned connections that need verification._
- **Are the 20 inferred relationships involving `layoutHtml()` (e.g. with `renderAgentKnowledgePage()` and `renderWikiSiteSettingsPage()`) actually correct?**
  _`layoutHtml()` has 20 INFERRED edges - model-reasoned connections that need verification._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._