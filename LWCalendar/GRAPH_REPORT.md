# Graph Report - /Users/luowei/projects/My_App/LWCalendar  (2026-05-04)

## Corpus Check
- Large corpus: 656 files · ~882,084 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 1223 nodes · 1556 edges · 71 communities detected
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 47 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]
- [[_COMMUNITY_Community 49|Community 49]]
- [[_COMMUNITY_Community 50|Community 50]]
- [[_COMMUNITY_Community 51|Community 51]]
- [[_COMMUNITY_Community 52|Community 52]]
- [[_COMMUNITY_Community 53|Community 53]]
- [[_COMMUNITY_Community 54|Community 54]]
- [[_COMMUNITY_Community 55|Community 55]]
- [[_COMMUNITY_Community 56|Community 56]]
- [[_COMMUNITY_Community 57|Community 57]]
- [[_COMMUNITY_Community 58|Community 58]]
- [[_COMMUNITY_Community 59|Community 59]]
- [[_COMMUNITY_Community 60|Community 60]]
- [[_COMMUNITY_Community 61|Community 61]]
- [[_COMMUNITY_Community 62|Community 62]]
- [[_COMMUNITY_Community 63|Community 63]]
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 66|Community 66]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 68|Community 68]]
- [[_COMMUNITY_Community 71|Community 71]]
- [[_COMMUNITY_Community 72|Community 72]]
- [[_COMMUNITY_Community 85|Community 85]]

## God Nodes (most connected - your core abstractions)
1. `LWAddTodoViewController` - 49 edges
2. `DateUtils` - 46 edges
3. `LWTodoListViewController` - 31 edges
4. `TimeTools` - 29 edges
5. `NotificationManager` - 24 edges
6. `LWSqliteManager` - 23 edges
7. `CloudKitManager` - 23 edges
8. `LWHelper` - 22 edges
9. `DateFormatter` - 22 edges
10. `TimeService` - 21 edges

## Surprising Connections (you probably didn't know these)
- `generateFilename()` --calls--> `DateFormatter`  [INFERRED]
  SwiftUI/LWCalendarSwiftUI/Views/Settings/DataExportView_backup.swift → SwiftUI/LWCalendarSwiftUI/Views/Templates/MyTemplatesView.swift
- `NotificationSettings()` --calls--> `useNotifications()`  [INFERRED]
  Web/client/src/components/Settings/NotificationSettings.tsx → Web/client/src/hooks/useNotifications.ts
- `exportTodos()` --calls--> `TodoItemCodable`  [INFERRED]
  SwiftUI/LWCalendarSwiftUI/Services/DatabaseManager.swift → SwiftUI/LWCalendarSwiftUI/Models/TodoItem.swift
- `performExportWithDocumentPicker()` --calls--> `ExportResult`  [INFERRED]
  SwiftUI/LWCalendarSwiftUI/Views/Settings/DataExportView_backup.swift → SwiftUI/LWCalendarSwiftUI/Services/DataImportExportManager.swift
- `performExport()` --calls--> `ExportResult`  [INFERRED]
  SwiftUI/LWCalendarSwiftUI/Views/Settings/DataExportView_backup.swift → SwiftUI/LWCalendarSwiftUI/Services/DataImportExportManager.swift

## Communities (118 total, 20 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.04
Nodes (49): LWAddTodoViewController, -addBtnAction, -alertViewPanGestureAction, -backBtnAction, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewnumberOfItemsInSection, -datePickerQueue (+41 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (31): Codable, Comparable, Int, TemplateCategory, TemplateTodoItem, TodoItem, TodoItemCodable, TodoStatus (+23 more)

### Community 3 - "Community 3"
Cohesion: 0.08
Nodes (25): ContentView, CalendarTabView, TopToolBar, AboutView, FeatureRow, SettingsTabView, ThemeSettingsView, TodoListContentView (+17 more)

### Community 4 - "Community 4"
Cohesion: 0.08
Nodes (15): AppDelegate, -applicationDidBecomeActive, -applicationDidEnterBackground, -applicationdidFinishLaunchingWithOptions, -applicationdidReceiveRemoteNotificationfetchCompletionHandler, -applicationdidRegisterForRemoteNotificationsWithDeviceToken, -applicationWillEnterForeground, -applicationWillResignActive (+7 more)

### Community 6 - "Community 6"
Cohesion: 0.07
Nodes (13): ReminderEditView, EnhancedChineseCalendarService, DateFormatter, EditTodoView, Color, EmptyReminderView, FilterChip, ReminderCardView (+5 more)

### Community 7 - "Community 7"
Cohesion: 0.06
Nodes (31): LWTodoListViewController, -addBtnAction, -alertViewPanGestureAction, -backBtnTouchDown, -dealloc, -gestureRecognizerShouldBegin, -getSortedDaysWithDayItemsDict, -getSortedMonths (+23 more)

### Community 8 - "Community 8"
Cohesion: 0.09
Nodes (3): EnhancedTodoListView, TodoListView, TodoListViewModel

### Community 9 - "Community 9"
Cohesion: 0.07
Nodes (29): TimeTools, -getAllDays, -getAllMonths, -getAllWeeks, -getChineseDateDetailFromDate, -getChineseDateFromDatedayNumOfMonth, -getChineseDayNumFromDate, -getChineseDayString (+21 more)

### Community 10 - "Community 10"
Cohesion: 0.07
Nodes (29): LWHelper, -addReminderWithTitlealarmDateString, -getDateEndingByDate, -getDateStaringByDate, -init, -isFutureTime, -isZh, -jiaziWithYear (+21 more)

### Community 11 - "Community 11"
Cohesion: 0.09
Nodes (10): FileDocument, ExportResult, ExportDocument, generateFilename(), performExport(), performExportWithDocumentPicker(), TextExportView, DataExportView (+2 more)

### Community 12 - "Community 12"
Cohesion: 0.12
Nodes (7): Equatable, CloudKitManager, SyncStatus, error, idle, success, syncing

### Community 13 - "Community 13"
Cohesion: 0.1
Nodes (3): ApiClient, handleTodoSubmit(), handleTodoSubmit()

### Community 14 - "Community 14"
Cohesion: 0.07
Nodes (14): PreferenceKey, EnhancedSettingsView, GenerateFromTemplateViewIntegrated, InlineThemeSelectorView, MyTemplatesViewIntegrated, ScrollOffsetPreferenceKeySettings, ScrollToTopButtonSettings, SettingsView (+6 more)

### Community 15 - "Community 15"
Cohesion: 0.14
Nodes (6): Hashable, Identifiable, CalendarDate, CalendarMonth, ChineseCalendarInfo, CalendarViewModel

### Community 16 - "Community 16"
Cohesion: 0.19
Nodes (6): GenerationConfig, SimpleTemplateCategory, SimpleTodoItem, TemplateCategory, TemplateDataManager, UserTemplate

### Community 17 - "Community 17"
Cohesion: 0.15
Nodes (3): useNotifications(), NotificationService, NotificationSettings()

### Community 18 - "Community 18"
Cohesion: 0.08
Nodes (23): LWSqliteManager, -copydb2docdata, -copySourceDBFilePathwithTargetDBFileNameoverride, -dayColorWithDate, -dealloc, -deleteTodoItemById, -execSql, -getItem (+15 more)

### Community 19 - "Community 19"
Cohesion: 0.12
Nodes (6): DataImportSheet, ImportResult, DataImportView, DataPreviewView, RequirementRow, TextImportView

### Community 20 - "Community 20"
Cohesion: 0.1
Nodes (11): ContentView, EnhancedCalendarDayCell, EnhancedCalendarView, ReminderDateHeader, ReminderEmptyStateView, ReminderTimelineItem, ReminderTimelineView, SimpleReminderListView (+3 more)

### Community 21 - "Community 21"
Cohesion: 0.1
Nodes (16): ColorCategory, ColorHelper, ColorTheme, creamDream, japaneseHeal, lowSatGradient, morandi, naturalWood (+8 more)

### Community 23 - "Community 23"
Cohesion: 0.23
Nodes (3): DataImportExportManager, FileFormatValidationResult, String

### Community 24 - "Community 24"
Cohesion: 0.14
Nodes (12): Animation, App, Calendar, CloudKit, ColorCategory, Constants, Database, DateFormat (+4 more)

### Community 25 - "Community 25"
Cohesion: 0.12
Nodes (16): LWHomeViewController, -handlerDatedateStringselectedDate, -iCloudSyncBtnAction, -listBtnAction, -purchaseBtnAction, -reloadCalendar, -restoreiCloudAction, -save2iCloudAction (+8 more)

### Community 26 - "Community 26"
Cohesion: 0.12
Nodes (16): LWColorItemCell, -awakeFromNib, LWItemTableViewCell, -awakeFromNib, -bellBtnAction, -doneAction, -itemStatusBtnAction, -nextAction (+8 more)

### Community 27 - "Community 27"
Cohesion: 0.12
Nodes (16): UIColor, -adjustByPercentage, -adjustColorWithPercentage, -colorComponentFromstartlength, -colorWithHexalpha, -colorWithHexString, -colorWithRGBAString, -darkerByPercentage (+8 more)

### Community 29 - "Community 29"
Cohesion: 0.15
Nodes (5): Animation, CardStyle, PressableModifier, View, ViewModifier

### Community 30 - "Community 30"
Cohesion: 0.12
Nodes (15): LWCalendarView, -addNextDataFromDateStr, -addPreviousDataFromDateStr, -collectionViewcellForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -getDataFromDate, -initData, -initWithCoder (+7 more)

### Community 32 - "Community 32"
Cohesion: 0.14
Nodes (13): LWCalendarPageCell, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewlayoutsizeForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -initWithCoder, -lineNum, -refreshCell (+5 more)

### Community 33 - "Community 33"
Cohesion: 0.14
Nodes (7): ShareSheet, ContentView, FeatureRowTemp, PurchaseViewTemp, SettingsViewTemp, ShareSheet, UIViewControllerRepresentable

### Community 34 - "Community 34"
Cohesion: 0.14
Nodes (8): LoadingAnimationView, LoadingStyle, bounce, pulse, rotation, shimmer, wave, StateTransitionView

### Community 36 - "Community 36"
Cohesion: 0.17
Nodes (11): LWCalendarCell, -awakeFromNib, -cancelTap, -labelWithItem, -setDateString, -setHasChineseCalendar, -setIsToday, -setIsWeekend (+3 more)

### Community 37 - "Community 37"
Cohesion: 0.2
Nodes (6): CalendarTabView, ContentView, SimpleReminderCardView, SimpleReminderEmptyStateView, SimpleReminderListView, SimpleReminderTimelineView

### Community 38 - "Community 38"
Cohesion: 0.17
Nodes (11): Error, LocalizedError, DataFileFormat, csv, yaml, DataImportExportError, emptyFile, invalidFileEncoding (+3 more)

### Community 39 - "Community 39"
Cohesion: 0.18
Nodes (9): ColorButton, ColorPickerView, ColorPickerView_Previews, ColorSubTheme, PreviewWrapper, RecentColorsSection, SubThemeSection, ThemeCategorySelector (+1 more)

### Community 40 - "Community 40"
Cohesion: 0.2
Nodes (3): UserColorPreferences, ObservableObject, ThemeManager

### Community 42 - "Community 42"
Cohesion: 0.24
Nodes (6): EnvironmentKey, EnvironmentValues, Notification.Name, ThemeAppliedView, ThemeManagerKey, View

### Community 43 - "Community 43"
Cohesion: 0.22
Nodes (8): LWListItemView, -awakeFromNib, -bellBtnAction, -listItemView, -remindTimeBtnAction, -setItem, -statusBtnAction, -traitCollectionDidChange

### Community 44 - "Community 44"
Cohesion: 0.22
Nodes (8): LWICloudHelper, -checkICloudAccount, -init, -restoreDBFileRecord, -saveDBFileRecord, -seqByTableNamedbPath, -shareInstance, -topMostController

### Community 45 - "Community 45"
Cohesion: 0.22
Nodes (7): CategoryPreviewView, CreateUserTemplateView, SearchBar, TemplateCategoryDetailView, TemplateCategoryRow, TemplateDataView, TemplateTodoRow

### Community 46 - "Community 46"
Cohesion: 0.25
Nodes (6): App, LWCalendarApp, AppTheme, dark, light, system

### Community 47 - "Community 47"
Cohesion: 0.25
Nodes (5): CalendarDayCell, CalendarGrid, CustomCalendarView, MonthNavigationHeader, WeekdayHeaderRow

### Community 48 - "Community 48"
Cohesion: 0.25
Nodes (3): CompactThemeSelectorView, ThemeOptionView, ThemeSelectorView

### Community 50 - "Community 50"
Cohesion: 0.29
Nodes (5): EditUserTemplateView, EmptyTemplatesView, MyTemplatesView, UserTemplateDetailView, UserTemplateRow

### Community 51 - "Community 51"
Cohesion: 0.29
Nodes (3): CalendarDayView, MonthCalendarView, SwipeableCalendarView

### Community 53 - "Community 53"
Cohesion: 0.29
Nodes (7): PurchasePlan, monthly, yearly, CaseIterable, PurchasePlan, monthly, yearly

### Community 54 - "Community 54"
Cohesion: 0.29
Nodes (7): ColorThemeCategory, cream, gradient, japanese, morandi, natural, nordic

### Community 56 - "Community 56"
Cohesion: 0.33
Nodes (5): LWListItemCell, -awakeFromNib, -dayBtnAction, -listItemViewById, -updateWithItemsdate

### Community 57 - "Community 57"
Cohesion: 0.33
Nodes (3): FeatureRow, PurchasePlanCard, PurchaseView

### Community 62 - "Community 62"
Cohesion: 0.33
Nodes (5): TodoPriority, high, low, normal, urgent

### Community 65 - "Community 65"
Cohesion: 0.5
Nodes (3): LWHomeTopView, -iCloudSyncBtnAction, -purchaseBtnAction

### Community 66 - "Community 66"
Cohesion: 0.5
Nodes (3): UIImage, -gradientWithSizecolor1color2isVerticel, -imageWithOverlayColor

## Knowledge Gaps
- **337 isolated node(s):** `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground`, `-applicationWillEnterForeground`, `-applicationDidBecomeActive` (+332 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **20 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ColorTheme` connect `Community 21` to `Community 15`, `Community 53`, `Community 23`?**
  _High betweenness centrality (0.058) - this node is a cross-community bridge._
- **Why does `UserColorPreferences` connect `Community 40` to `Community 39`?**
  _High betweenness centrality (0.050) - this node is a cross-community bridge._
- **Why does `DateFormatter` connect `Community 6` to `Community 3`, `Community 37`, `Community 8`, `Community 41`, `Community 11`, `Community 50`, `Community 22`?**
  _High betweenness centrality (0.041) - this node is a cross-community bridge._
- **What connects `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground` to the rest of the system?**
  _337 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.04 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._