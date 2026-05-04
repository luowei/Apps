# Graph Report - /Users/luowei/projects/My_App/LWCalendar/OC  (2026-05-05)

## Corpus Check
- Large corpus: 523 files · ~769,484 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 328 nodes · 290 edges · 20 communities detected
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
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]

## God Nodes (most connected - your core abstractions)
1. `LWAddTodoViewController` - 49 edges
2. `LWTodoListViewController` - 31 edges
3. `TimeTools` - 29 edges
4. `LWSqliteManager` - 23 edges
5. `LWHelper` - 22 edges
6. `LWHomeViewController` - 16 edges
7. `UIColor` - 16 edges
8. `LWCalendarView` - 15 edges
9. `LWItemTableViewCell` - 14 edges
10. `LWCalendarPageCell` - 13 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (40 total, 2 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.04
Nodes (49): LWAddTodoViewController, -addBtnAction, -alertViewPanGestureAction, -backBtnAction, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewnumberOfItemsInSection, -datePickerQueue (+41 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (31): LWTodoListViewController, -addBtnAction, -alertViewPanGestureAction, -backBtnTouchDown, -dealloc, -gestureRecognizerShouldBegin, -getSortedDaysWithDayItemsDict, -getSortedMonths (+23 more)

### Community 2 - "Community 2"
Cohesion: 0.07
Nodes (29): TimeTools, -getAllDays, -getAllMonths, -getAllWeeks, -getChineseDateDetailFromDate, -getChineseDateFromDatedayNumOfMonth, -getChineseDayNumFromDate, -getChineseDayString (+21 more)

### Community 3 - "Community 3"
Cohesion: 0.08
Nodes (23): LWSqliteManager, -copydb2docdata, -copySourceDBFilePathwithTargetDBFileNameoverride, -dayColorWithDate, -dealloc, -deleteTodoItemById, -execSql, -getItem (+15 more)

### Community 4 - "Community 4"
Cohesion: 0.09
Nodes (22): LWHelper, -addReminderWithTitlealarmDateString, -getDateEndingByDate, -getDateStaringByDate, -init, -isFutureTime, -isZh, -jiaziWithYear (+14 more)

### Community 5 - "Community 5"
Cohesion: 0.12
Nodes (16): LWHomeViewController, -handlerDatedateStringselectedDate, -iCloudSyncBtnAction, -listBtnAction, -purchaseBtnAction, -reloadCalendar, -restoreiCloudAction, -save2iCloudAction (+8 more)

### Community 6 - "Community 6"
Cohesion: 0.12
Nodes (16): LWColorItemCell, -awakeFromNib, LWItemTableViewCell, -awakeFromNib, -bellBtnAction, -doneAction, -itemStatusBtnAction, -nextAction (+8 more)

### Community 7 - "Community 7"
Cohesion: 0.12
Nodes (16): UIColor, -adjustByPercentage, -adjustColorWithPercentage, -colorComponentFromstartlength, -colorWithHexalpha, -colorWithHexString, -colorWithRGBAString, -darkerByPercentage (+8 more)

### Community 8 - "Community 8"
Cohesion: 0.12
Nodes (15): LWCalendarView, -addNextDataFromDateStr, -addPreviousDataFromDateStr, -collectionViewcellForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -getDataFromDate, -initData, -initWithCoder (+7 more)

### Community 9 - "Community 9"
Cohesion: 0.14
Nodes (13): LWCalendarPageCell, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewlayoutsizeForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -initWithCoder, -lineNum, -refreshCell (+5 more)

### Community 10 - "Community 10"
Cohesion: 0.15
Nodes (12): AppDelegate, -applicationDidBecomeActive, -applicationDidEnterBackground, -applicationdidFinishLaunchingWithOptions, -applicationdidReceiveRemoteNotificationfetchCompletionHandler, -applicationdidRegisterForRemoteNotificationsWithDeviceToken, -applicationWillEnterForeground, -applicationWillResignActive (+4 more)

### Community 11 - "Community 11"
Cohesion: 0.17
Nodes (11): LWCalendarCell, -awakeFromNib, -cancelTap, -labelWithItem, -setDateString, -setHasChineseCalendar, -setIsToday, -setIsWeekend (+3 more)

### Community 12 - "Community 12"
Cohesion: 0.22
Nodes (8): LWListItemView, -awakeFromNib, -bellBtnAction, -listItemView, -remindTimeBtnAction, -setItem, -statusBtnAction, -traitCollectionDidChange

### Community 13 - "Community 13"
Cohesion: 0.22
Nodes (8): LWICloudHelper, -checkICloudAccount, -init, -restoreDBFileRecord, -saveDBFileRecord, -seqByTableNamedbPath, -shareInstance, -topMostController

### Community 14 - "Community 14"
Cohesion: 0.25
Nodes (7): NSDate, -lunar_isLeapMonth, -lunar_lastMonthSameDay, -lunar_month, UIView, -screenshot, -screenshotForCroppingRect

### Community 15 - "Community 15"
Cohesion: 0.33
Nodes (5): LWListItemCell, -awakeFromNib, -dayBtnAction, -listItemViewById, -updateWithItemsdate

### Community 16 - "Community 16"
Cohesion: 0.5
Nodes (3): LWHomeTopView, -iCloudSyncBtnAction, -purchaseBtnAction

### Community 17 - "Community 17"
Cohesion: 0.5
Nodes (3): UIImage, -gradientWithSizecolor1color2isVerticel, -imageWithOverlayColor

## Knowledge Gaps
- **269 isolated node(s):** `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground`, `-applicationWillEnterForeground`, `-applicationDidBecomeActive` (+264 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `LWAddTodoViewController` connect `Community 0` to `Community 6`?**
  _High betweenness centrality (0.036) - this node is a cross-community bridge._
- **What connects `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground` to the rest of the system?**
  _269 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.04 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.07 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.09 - nodes in this community are weakly interconnected._