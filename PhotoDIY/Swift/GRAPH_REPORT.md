# Graph Report - /Users/luowei/projects/My_App/PhotoDIY/Swift  (2026-05-05)

## Corpus Check
- Corpus is ~27,376 words - fits in a single context window. You may not need a graph.

## Summary
- 669 nodes · 997 edges · 37 communities detected
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 26 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 28|Community 28]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 31|Community 31]]
- [[_COMMUNITY_Community 32|Community 32]]
- [[_COMMUNITY_Community 33|Community 33]]
- [[_COMMUNITY_Community 34|Community 34]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 36|Community 36]]

## God Nodes (most connected - your core abstractions)
1. `AIEnhancedImageProcessor` - 52 edges
2. `FilterType` - 33 edges
3. `CoreImageProcessor` - 30 edges
4. `FilterType` - 23 edges
5. `EditingMode` - 20 edges
6. `ContentViewModel` - 19 edges
7. `UIImage` - 18 edges
8. `AdvancedStyleProcessor` - 18 edges
9. `AIImageProcessor` - 12 edges
10. `ImageFilterManager` - 12 edges

## Surprising Connections (you probably didn't know these)
- `createEmojiImage()` --calls--> `UIImage`  [INFERRED]
  Placeholders.swift → Core/Services/FilterService.swift

## Communities (37 total, 3 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.06
Nodes (12): AIEnhancedImageProcessor, AIProcessingResult, EcommerceSettings, FoodAnalysis, FoodSettings, IDPhotoSettings, LandscapeSettings, PersonSegmentationResult (+4 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (32): FilterType, blackAndWhite, bloom, blur, cartoon, colorInvert, comicEffect, crystallize (+24 more)

### Community 2 - "Community 2"
Cohesion: 0.06
Nodes (6): AppState, EditingHistoryManager, EditingHistory, ObservableObject, AppState, ContentViewModel

### Community 3 - "Community 3"
Cohesion: 0.06
Nodes (13): CameraPickerView, Coordinator, NSObject, UIImagePickerControllerDelegate, UINavigationControllerDelegate, UIScrollViewDelegate, UIViewControllerRepresentable, UIViewRepresentable (+5 more)

### Community 4 - "Community 4"
Cohesion: 0.08
Nodes (5): AIImageProcessor, UIImage, CropSuggestion, ImageCropManager, AIFeaturesGrid

### Community 5 - "Community 5"
Cohesion: 0.07
Nodes (26): createEmojiImage(), DIContainer, EditingMode, adjust, artistic, comic, crop, draw (+18 more)

### Community 7 - "Community 7"
Cohesion: 0.09
Nodes (17): Hashable, LocalizedError, PhotoAsset, PhotoKitService, PhotoLibraryError, assetNotFound, createAlbumFailed, loadImageFailed (+9 more)

### Community 8 - "Community 8"
Cohesion: 0.15
Nodes (7): AdvancedStyleProcessor, EcommerceSettings, IDPhotoSettings, LandscapeSettings, PortraitSettings, ProcessingResult, StyleProcessingPanel

### Community 9 - "Community 9"
Cohesion: 0.11
Nodes (14): Codable, EditingProject, ExportQuality, high, low, medium, original, FilterSetting (+6 more)

### Community 10 - "Community 10"
Cohesion: 0.1
Nodes (13): CornerType, bottomEdge, bottomLeft, bottomRight, leftEdge, rightEdge, topEdge, topLeft (+5 more)

### Community 11 - "Community 11"
Cohesion: 0.09
Nodes (15): EnvironmentKey, AppTheme, blue, dark, green, light, orange, purple (+7 more)

### Community 12 - "Community 12"
Cohesion: 0.13
Nodes (17): CacheSize, large, medium, small, EditingHistoryItem, EditingMode, ImageQuality, high (+9 more)

### Community 13 - "Community 13"
Cohesion: 0.13
Nodes (7): DIContainer, DIContainerProtocol, Injected, InstagramStoryActivity, NativeSharingService, SharingService, UIActivity

### Community 14 - "Community 14"
Cohesion: 0.1
Nodes (20): FilterType, beauty, blackAndWhite, brightness, contrast, dramatic, gaussianBlur, highlights (+12 more)

### Community 15 - "Community 15"
Cohesion: 0.16
Nodes (5): FilterComposer, FilterConfiguration, FilterManager, FilterPreset, FilterService

### Community 16 - "Community 16"
Cohesion: 0.15
Nodes (10): ContentView, ContentView_Previews, EmptyStateView, NavigationBarView, PreviewProvider, EditingHistoryView_Previews, AboutView, FeatureRow (+2 more)

### Community 17 - "Community 17"
Cohesion: 0.18
Nodes (7): AsyncImageView, BeforeAfterView, EditingHistoryView, EmptyHistoryView, HistoryDetailView, HistoryItemRow, InfoRow

### Community 18 - "Community 18"
Cohesion: 0.29
Nodes (11): View, CategorySelector, EcommerceParametersView, FoodParametersView, IDPhotoParametersView, LandscapeParametersView, ParameterSlider, PortraitParametersView (+3 more)

### Community 19 - "Community 19"
Cohesion: 0.18
Nodes (9): CropGridView, CropHandleView, DraggableStickerView, DraggableTextView, EditingOverlayView, StickerOverlayView, TextEditorView, TextElement (+1 more)

### Community 20 - "Community 20"
Cohesion: 0.18
Nodes (9): EditingMode, crop, draw, filter, sticker, text, view, EditingStep (+1 more)

### Community 21 - "Community 21"
Cohesion: 0.2
Nodes (8): CategorySelectorView, CropControlPanel, CropRatioButton, EditingToolsPanel, StickerToolsView, StyleProcessingView, TextToolsView, ToolButton

### Community 22 - "Community 22"
Cohesion: 0.22
Nodes (9): CaseIterable, FilterCategory, artistic, basic, beauty, blur, ToolCategory, regular (+1 more)

### Community 23 - "Community 23"
Cohesion: 0.25
Nodes (8): EditingStepType, crop, draw, filter, original, sticker, text, transform

### Community 24 - "Community 24"
Cohesion: 0.25
Nodes (8): DrawingTool, blur, brush, eraser, marker, mosaic, pen, pencil

### Community 25 - "Community 25"
Cohesion: 0.25
Nodes (8): SceneType, beach, mountain, nature, sunset, unknown, urban, water

### Community 26 - "Community 26"
Cohesion: 0.25
Nodes (8): FoodType, beverage, dessert, fruit, grain, meat, unknown, vegetable

### Community 27 - "Community 27"
Cohesion: 0.29
Nodes (7): CropAspectRatio, free, ratio16x9, ratio3x4, ratio4x3, ratio9x16, square

### Community 28 - "Community 28"
Cohesion: 0.29
Nodes (7): Identifiable, StickerType, decorations, emoji, frames, shapes, StickerElement

### Community 29 - "Community 29"
Cohesion: 0.29
Nodes (5): AIFeatureButton, AIFeaturesView, DetectionResultsSection, ImagePreviewSection, ProcessingOverlay

### Community 31 - "Community 31"
Cohesion: 0.29
Nodes (7): ProductType, accessories, clothing, cosmetics, electronics, furniture, unknown

### Community 32 - "Community 32"
Cohesion: 0.33
Nodes (6): IDPhotoBackgroundColor, blue, green, office, red, white

### Community 33 - "Community 33"
Cohesion: 0.33
Nodes (6): IDPhotoBackgroundColor, blue, green, office, red, white

### Community 35 - "Community 35"
Cohesion: 0.33
Nodes (4): AdjustmentSlider, ColorAdjustmentView, FilterPreviewCell, FilterSelectorView

### Community 36 - "Community 36"
Cohesion: 0.33
Nodes (6): CropHandle, bottomLeft, bottomRight, center, topLeft, topRight

## Knowledge Gaps
- **180 isolated node(s):** `regular`, `style`, `none`, `adjust`, `crop` (+175 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `UIImage` connect `Community 4` to `Community 0`, `Community 1`, `Community 2`, `Community 5`, `Community 6`, `Community 8`, `Community 15`, `Community 17`?**
  _High betweenness centrality (0.253) - this node is a cross-community bridge._
- **Why does `AIEnhancedImageProcessor` connect `Community 0` to `Community 2`?**
  _High betweenness centrality (0.168) - this node is a cross-community bridge._
- **Why does `SettingsView` connect `Community 5` to `Community 18`?**
  _High betweenness centrality (0.125) - this node is a cross-community bridge._
- **What connects `regular`, `style`, `none` to the rest of the system?**
  _180 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._