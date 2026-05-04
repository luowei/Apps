# Graph Report - /Users/luowei/projects/My_App/MarkDownEditer/Swift  (2026-05-05)

## Corpus Check
- Large corpus: 688 files · ~783,567 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 293 nodes · 386 edges · 18 communities detected
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 5 edges (avg confidence: 0.8)
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

## God Nodes (most connected - your core abstractions)
1. `MarkdownSymbol` - 16 edges
2. `AppState` - 15 edges
3. `Document` - 11 edges
4. `DocumentCategory` - 9 edges
5. `MarkdownRenderer` - 9 edges
6. `ThemeManager` - 8 edges
7. `FontSize` - 8 edges
8. `BackupFrequency` - 8 edges
9. `ExportFormat` - 8 edges
10. `Coordinator` - 8 edges

## Surprising Connections (you probably didn't know these)
- `CategoryListView` --inherits--> `View`  [EXTRACTED]
  Sources/Features/DocumentList/CategoryListView.swift →   _Bridges community 3 → community 0_
- `ExportView` --inherits--> `View`  [EXTRACTED]
  Sources/Features/Export/ExportView.swift →   _Bridges community 0 → community 6_
- `ModernDocumentCreationView` --inherits--> `View`  [EXTRACTED]
  Sources/Features/DocumentList/ModernDocumentCreationView.swift →   _Bridges community 0 → community 4_
- `ModernDocumentListView` --inherits--> `View`  [EXTRACTED]
  Sources/Features/DocumentList/ModernDocumentListView.swift →   _Bridges community 0 → community 13_
- `DocumentCreationView` --inherits--> `View`  [EXTRACTED]
  Sources/Features/DocumentList/DocumentCreationView.swift →   _Bridges community 0 → community 8_

## Communities (18 total, 5 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (36): DocumentContextMenu, DocumentRowView, FilterMenuContent, TagView, FeatureCard, ModernWelcomeView, QuickTipRow, WelcomeView (+28 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (33): CaseIterable, ExportFormat, html, markdown, pdf, txt, DocumentSortOrder, createdDate (+25 more)

### Community 2 - "Community 2"
Cohesion: 0.1
Nodes (17): ButtonStyle, Color, ColorPalette, Colors, CornerRadius, DesignSystem, ModernButtonStyle, destructive (+9 more)

### Community 3 - "Community 3"
Cohesion: 0.13
Nodes (12): CategoryDocumentRow, CategoryListView, DocumentCategory, all, archived, byTag, favorites, recent (+4 more)

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (10): FlowLayout, ModernDocumentCreationView, ModernDocumentTemplate, article, blank, meeting, note, readme (+2 more)

### Community 5 - "Community 5"
Cohesion: 0.12
Nodes (8): ModernActionButton, ModernCard, ModernEmptyState, ModernListRow, ModernSearchBar, ModernSectionHeader, ModernTagView, ThemeModePicker

### Community 6 - "Community 6"
Cohesion: 0.18
Nodes (5): ExportFormatRow, ExportService, ExportView, ShareSheet, UIViewControllerRepresentable

### Community 7 - "Community 7"
Cohesion: 0.18
Nodes (6): Coordinator, LanguageDetector, SyntaxHighlightedEditor, NSObject, UITextViewDelegate, UIViewRepresentable

### Community 8 - "Community 8"
Cohesion: 0.13
Nodes (4): DocumentCreationView, TemplateRowView, TemplateSelectionView, Document

### Community 10 - "Community 10"
Cohesion: 0.14
Nodes (14): MarkdownSymbol, bold, bulletList, code, codeBlock, heading1, heading2, heading3 (+6 more)

### Community 11 - "Community 11"
Cohesion: 0.29
Nodes (8): DocumentTemplate, Equatable, Identifiable, CodableColor, SyntaxHighlighting, Theme, ThemeColors, ThemeTypography

### Community 13 - "Community 13"
Cohesion: 0.22
Nodes (4): ModernDocumentContextMenu, ModernDocumentListView, ModernDocumentRow, ModernDocumentRowContent

### Community 16 - "Community 16"
Cohesion: 0.5
Nodes (4): EditorMode, edit, preview, split

## Knowledge Gaps
- **60 isolated node(s):** `all`, `favorites`, `archived`, `recent`, `byTag` (+55 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `MarkdownSymbol` connect `Community 10` to `Community 1`, `Community 3`, `Community 5`?**
  _High betweenness centrality (0.128) - this node is a cross-community bridge._
- **Why does `ExportFormat` connect `Community 1` to `Community 6`?**
  _High betweenness centrality (0.118) - this node is a cross-community bridge._
- **Why does `AppState` connect `Community 9` to `Community 1`?**
  _High betweenness centrality (0.074) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Document` (e.g. with `.createDocument()` and `.createDocument()`) actually correct?**
  _`Document` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `all`, `favorites`, `archived` to the rest of the system?**
  _60 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._