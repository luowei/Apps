# Graph Report - /Users/luowei/projects/My_App/LWCalendar/SwiftUI  (2026-05-05)

## Corpus Check
- 70 files · ~77,387 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 722 nodes · 1097 edges · 45 communities detected
- Extraction: 95% EXTRACTED · 5% INFERRED · 0% AMBIGUOUS · INFERRED: 59 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 37|Community 37]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 41|Community 41]]
- [[_COMMUNITY_Community 42|Community 42]]
- [[_COMMUNITY_Community 43|Community 43]]
- [[_COMMUNITY_Community 44|Community 44]]

## God Nodes (most connected - your core abstractions)
1. `NotificationManager` - 24 edges
2. `CloudKitManager` - 23 edges
3. `DateFormatter` - 22 edges
4. `TimeService` - 21 edges
5. `TodoListViewModel` - 20 edges
6. `DataImportExportManager` - 19 edges
7. `CalendarViewModel` - 18 edges
8. `Date` - 18 edges
9. `TodoItem` - 18 edges
10. `TimeService` - 16 edges

## Surprising Connections (you probably didn't know these)
- `generateFilename()` --calls--> `DateFormatter`  [INFERRED]
  LWCalendarSwiftUI/Views/Settings/DataExportView_backup.swift → LWCalendarSwiftUI/Views/Templates/MyTemplatesView.swift
- `insertSampleData()` --calls--> `TodoItem`  [INFERRED]
  LWCalendarSwiftUI/Services/DatabaseManager.swift → LWCalendarSwiftUI/Models/TodoItem.swift
- `createSampleData()` --calls--> `TodoItem`  [INFERRED]
  LWCalendarSwiftUI/Services/DatabaseManager.swift → LWCalendarSwiftUI/Models/TodoItem.swift
- `exportTodos()` --calls--> `TodoItemCodable`  [INFERRED]
  LWCalendarSwiftUI/Services/DatabaseManager.swift → LWCalendarSwiftUI/Models/TodoItem.swift
- `performExportWithDocumentPicker()` --calls--> `ExportResult`  [INFERRED]
  LWCalendarSwiftUI/Views/Settings/DataExportView_backup.swift → LWCalendarSwiftUI/Services/DataImportExportManager.swift

## Communities (48 total, 15 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.05
Nodes (40): PurchasePlan, monthly, yearly, CaseIterable, ColorThemeCategory, cream, gradient, japanese (+32 more)

### Community 1 - "Community 1"
Cohesion: 0.05
Nodes (13): DataImportSheet, SimpleReminderListView, TodoItem, ImportResult, DataImportView, DataPreviewView, RequirementRow, TextImportView (+5 more)

### Community 2 - "Community 2"
Cohesion: 0.06
Nodes (30): Codable, Comparable, Int, TemplateCategory, TemplateTodoItem, TodoItemCodable, TodoStatus, done (+22 more)

### Community 4 - "Community 4"
Cohesion: 0.09
Nodes (3): EnhancedTodoListView, TodoListView, TodoListViewModel

### Community 5 - "Community 5"
Cohesion: 0.09
Nodes (10): FileDocument, ExportResult, ExportDocument, generateFilename(), performExport(), performExportWithDocumentPicker(), TextExportView, DataExportView (+2 more)

### Community 6 - "Community 6"
Cohesion: 0.12
Nodes (7): Equatable, CloudKitManager, SyncStatus, error, idle, success, syncing

### Community 7 - "Community 7"
Cohesion: 0.09
Nodes (17): Color, ColorCategory, ColorHelper, ColorTheme, creamDream, japaneseHeal, lowSatGradient, morandi (+9 more)

### Community 8 - "Community 8"
Cohesion: 0.14
Nodes (6): Hashable, Identifiable, CalendarDate, CalendarMonth, ChineseCalendarInfo, CalendarViewModel

### Community 9 - "Community 9"
Cohesion: 0.19
Nodes (6): GenerationConfig, SimpleTemplateCategory, SimpleTodoItem, TemplateCategory, TemplateDataManager, UserTemplate

### Community 10 - "Community 10"
Cohesion: 0.14
Nodes (3): NSObject, NotificationManager, UNUserNotificationCenterDelegate

### Community 11 - "Community 11"
Cohesion: 0.15
Nodes (19): AboutView, FeatureRow, SettingsTabView, ThemeSettingsView, TodoListContentView, ActionButton, CompactTimelineItemView, DateSectionHeader (+11 more)

### Community 12 - "Community 12"
Cohesion: 0.11
Nodes (6): ReminderEditView, EnhancedChineseCalendarService, DateFormatter, EditTodoView, ReminderEditView, SimpleEditTodoView

### Community 14 - "Community 14"
Cohesion: 0.11
Nodes (10): EnhancedSettingsView, InlineThemeSelectorView, MyTemplatesViewIntegrated, ScrollToTopButtonSettings, SettingsView, SimpleTemplateCategory, TemplateCategoryRowIntegrated, TemplateDataViewIntegrated (+2 more)

### Community 15 - "Community 15"
Cohesion: 0.14
Nodes (12): Animation, App, Calendar, CloudKit, ColorCategory, Constants, Database, DateFormat (+4 more)

### Community 16 - "Community 16"
Cohesion: 0.11
Nodes (10): ContentView, EnhancedCalendarDayCell, EnhancedCalendarView, ReminderDateHeader, ReminderEmptyStateView, ReminderTimelineItem, ReminderTimelineView, SimpleSettingsView (+2 more)

### Community 18 - "Community 18"
Cohesion: 0.15
Nodes (5): Animation, CardStyle, PressableModifier, View, ViewModifier

### Community 19 - "Community 19"
Cohesion: 0.14
Nodes (8): LoadingAnimationView, LoadingStyle, bounce, pulse, rotation, shimmer, wave, StateTransitionView

### Community 20 - "Community 20"
Cohesion: 0.2
Nodes (6): CalendarTabView, ContentView, SimpleReminderCardView, SimpleReminderEmptyStateView, SimpleReminderListView, SimpleReminderTimelineView

### Community 21 - "Community 21"
Cohesion: 0.18
Nodes (7): Color, EmptyReminderView, FilterChip, ReminderCardView, ReminderEmptyStateView, ReminderRowView, ReminderTimelineView

### Community 22 - "Community 22"
Cohesion: 0.18
Nodes (9): ColorButton, ColorPickerView, ColorPickerView_Previews, ColorSubTheme, PreviewWrapper, RecentColorsSection, SubThemeSection, ThemeCategorySelector (+1 more)

### Community 23 - "Community 23"
Cohesion: 0.24
Nodes (6): EnvironmentKey, EnvironmentValues, Notification.Name, ThemeAppliedView, ThemeManagerKey, View

### Community 25 - "Community 25"
Cohesion: 0.22
Nodes (7): CategoryPreviewView, CreateUserTemplateView, SearchBar, TemplateCategoryDetailView, TemplateCategoryRow, TemplateDataView, TemplateTodoRow

### Community 26 - "Community 26"
Cohesion: 0.25
Nodes (5): CalendarDayCell, CalendarGrid, CustomCalendarView, MonthNavigationHeader, WeekdayHeaderRow

### Community 27 - "Community 27"
Cohesion: 0.25
Nodes (3): CompactThemeSelectorView, ThemeOptionView, ThemeSelectorView

### Community 28 - "Community 28"
Cohesion: 0.29
Nodes (3): ShareSheet, ShareSheet, UIViewControllerRepresentable

### Community 29 - "Community 29"
Cohesion: 0.29
Nodes (5): EditUserTemplateView, EmptyTemplatesView, MyTemplatesView, UserTemplateDetailView, UserTemplateRow

### Community 30 - "Community 30"
Cohesion: 0.29
Nodes (4): ContentView, FeatureRowTemp, PurchaseViewTemp, SettingsViewTemp

### Community 31 - "Community 31"
Cohesion: 0.29
Nodes (3): CalendarDayView, MonthCalendarView, SwipeableCalendarView

### Community 35 - "Community 35"
Cohesion: 0.33
Nodes (3): FeatureRow, PurchasePlanCard, PurchaseView

### Community 38 - "Community 38"
Cohesion: 0.4
Nodes (3): PreferenceKey, ScrollOffsetPreferenceKeySettings, ScrollOffsetPreferenceKey

## Knowledge Gaps
- **68 isolated node(s):** `pending`, `done`, `expired`, `DateFormat`, `NotificationConfig` (+63 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **15 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ColorTheme` connect `Community 7` to `Community 0`, `Community 8`?**
  _High betweenness centrality (0.163) - this node is a cross-community bridge._
- **Why does `TodoItem` connect `Community 1` to `Community 0`, `Community 2`, `Community 4`, `Community 6`?**
  _High betweenness centrality (0.162) - this node is a cross-community bridge._
- **Why does `DateFormatter` connect `Community 12` to `Community 4`, `Community 5`, `Community 13`, `Community 20`, `Community 21`, `Community 24`, `Community 29`?**
  _High betweenness centrality (0.092) - this node is a cross-community bridge._
- **Are the 21 inferred relationships involving `DateFormatter` (e.g. with `.groupTodosByDate()` and `.setupInitialValues()`) actually correct?**
  _`DateFormatter` has 21 INFERRED edges - model-reasoned connections that need verification._
- **What connects `pending`, `done`, `expired` to the rest of the system?**
  _68 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._