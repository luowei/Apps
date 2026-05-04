# Graph Report - /Users/luowei/projects/My_App/ChildrenEnglish  (2026-05-04)

## Corpus Check
- Large corpus: 1440 files · ~1,048,527 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 688 nodes · 728 edges · 38 communities detected
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 29 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 25|Community 25]]
- [[_COMMUNITY_Community 26|Community 26]]
- [[_COMMUNITY_Community 27|Community 27]]
- [[_COMMUNITY_Community 29|Community 29]]
- [[_COMMUNITY_Community 30|Community 30]]
- [[_COMMUNITY_Community 35|Community 35]]
- [[_COMMUNITY_Community 38|Community 38]]
- [[_COMMUNITY_Community 39|Community 39]]
- [[_COMMUNITY_Community 40|Community 40]]
- [[_COMMUNITY_Community 44|Community 44]]
- [[_COMMUNITY_Community 45|Community 45]]
- [[_COMMUNITY_Community 46|Community 46]]
- [[_COMMUNITY_Community 47|Community 47]]
- [[_COMMUNITY_Community 48|Community 48]]

## God Nodes (most connected - your core abstractions)
1. `VideoViewController` - 37 edges
2. `ContainerTransitionContext` - 27 edges
3. `VideoPlayerViewModel` - 19 edges
4. `ZFDouYinCell` - 18 edges
5. `HomeViewController` - 15 edges
6. `ZFDouYinControlView` - 15 edges
7. `SDETabBarViewController` - 15 edges
8. `CETool` - 15 edges
9. `DefaultVideoService` - 14 edges
10. `AppDelegate` - 12 edges

## Surprising Connections (you probably didn't know these)
- `startServer()` --calls--> `initializeDatabase()`  [INFERRED]
  Web/server/src/index.ts → Web/server/src/config/database.ts

## Communities (112 total, 5 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.08
Nodes (20): CaseIterable, Codable, Equatable, Identifiable, Banner, PlaybackRecord, User, UserSettings (+12 more)

### Community 1 - "Community 1"
Cohesion: 0.05
Nodes (37): VideoViewController, -addGADBanner, -adViewDidReceiveAd, -createAndLoadInterstitial, -dataSource, -interstitialDidDismissScreen, -loadAndPlayWithPrefixautoPlay, -playTheIndex (+29 more)

### Community 2 - "Community 2"
Cohesion: 0.09
Nodes (7): BaseViewModel, ViewModel, BaseViewModel, ObservableObject, UserService, HomeViewModel, VideoListViewModel

### Community 3 - "Community 3"
Cohesion: 0.06
Nodes (31): NSObject, -swizzleClassMethodwithMethod, -swizzleMethodwithMethod, NSString, -leadingTrim, -tailingTrim, -trim, -vaildatePassword (+23 more)

### Community 4 - "Community 4"
Cohesion: 0.13
Nodes (8): AppCoordinator, SettingsCoordinator, TabBarCoordinator, BaseCoordinator, HomeCoordinator, PurchaseCoordinator, PurchaseView, VideoCoordinator

### Community 5 - "Community 5"
Cohesion: 0.07
Nodes (28): SDEContainerViewControllerDelegate, -containerControlleranimationControllerForTransitionFromViewControllertoViewController, -containerControllerinteractionControllerForAnimation, -init, SDEPercentDrivenInteractiveTransition, -cancelInteractiveTransition, -finishInteractiveTransition, -startInteractiveTransition (+20 more)

### Community 6 - "Community 6"
Cohesion: 0.07
Nodes (27): ContainerTransitionContext, -activateInteractiveTransition, -activateNonInteractiveTransition, -cancelInteractiveTransition, -completeTransition, -containerView, -finalFrameForViewController, -finishChangeButtonAppear (+19 more)

### Community 7 - "Community 7"
Cohesion: 0.12
Nodes (12): LocalizedError, OSSConfig, OSSError, invalidResponse, requestFailed, signatureError, xmlParsingError, OSSListResponse (+4 more)

### Community 8 - "Community 8"
Cohesion: 0.15
Nodes (3): DefaultFavoriteService, FavoriteServiceProtocol, VideoPlayerViewModel

### Community 9 - "Community 9"
Cohesion: 0.08
Nodes (23): CETool, -addSortedKey, -hideLoading, -isModalViewController, -likeDict, -removeSortedKey, -setLikeDictValuewithKey, -shareImagevc (+15 more)

### Community 10 - "Community 10"
Cohesion: 0.12
Nodes (15): ContentView, FavoritesView, SimpleSettingsView, View, BannerItemView, BannerView, CategoryGridView, CategoryItemView (+7 more)

### Community 11 - "Community 11"
Cohesion: 0.11
Nodes (18): ZFDouYinCell, -backBtn, -backBtnAction, -bgImgView, -commentBtn, -coverImageView, -effectView, -initWithStylereuseIdentifier (+10 more)

### Community 12 - "Community 12"
Cohesion: 0.14
Nodes (5): NSObject, UIViewControllerRepresentable, AVPlayerView, Coordinator, CustomVideoPlayer

### Community 13 - "Community 13"
Cohesion: 0.12
Nodes (15): HomeViewController, -addGADBanner, -dealloc, -favoriteBtnAction, -favoriteContainerView, -homeBtnAction, -homeContainerView, -leftItemAction (+7 more)

### Community 14 - "Community 14"
Cohesion: 0.12
Nodes (15): ZFDouYinControlView, -activity, -bgImgView, -coverImageView, -effectView, -gestureSingleTapped, -init, -layoutSubviews (+7 more)

### Community 15 - "Community 15"
Cohesion: 0.12
Nodes (15): Checkpoint, -copyWithZone, DownloadRequest, DownloadService, -cancel, -downloadServiceWithRequest, -fileSizeAtPath, -getFileInfo (+7 more)

### Community 16 - "Community 16"
Cohesion: 0.15
Nodes (12): AppDelegate, -applicationDidBecomeActive, -applicationDidEnterBackground, -applicationdidFinishLaunchingWithOptions, -applicationdidReceiveRemoteNotificationfetchCompletionHandler, -applicationdidRegisterForRemoteNotificationsWithDeviceToken, -applicationWillEnterForeground, -applicationWillResignActive (+4 more)

### Community 17 - "Community 17"
Cohesion: 0.15
Nodes (12): CEHomeContainerView, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewlayoutreferenceSizeForFooterInSection, -collectionViewlayoutreferenceSizeForHeaderInSection, -collectionViewlayoutsizeForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -collectionViewviewForSupplementaryElementOfKindatIndexPath (+4 more)

### Community 18 - "Community 18"
Cohesion: 0.17
Nodes (11): CEFavoriteContainerView, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewlayoutsizeForItemAtIndexPath, -collectionViewnumberOfItemsInSection, -dealloc, -initWithFrame, -jpgURLStringFromKey (+3 more)

### Community 19 - "Community 19"
Cohesion: 0.22
Nodes (3): initializeDatabase(), errorHandler(), startServer()

### Community 20 - "Community 20"
Cohesion: 0.42
Nodes (8): createBanners(), createCategories(), createDefaultAdmin(), createDemoUser(), createSampleFavorites(), createSamplePlaybackRecords(), createSampleVideos(), main()

### Community 21 - "Community 21"
Cohesion: 0.22
Nodes (8): OSSWrapper, -asyncGetImagesuccessfailure, -asyncPutImagelocalFilePathsuccessfailure, -multipartUploadWithSuccessfailure, -normalRequestCancel, -reSizepicWidthpicHeightsuccessfailure, -textWaterMarkwaterTextobjectSizesuccessfailure, -triggerCallbackWithObjectKeysuccessfailure

### Community 22 - "Community 22"
Cohesion: 0.25
Nodes (7): OSSManager, -checkObjectExistWithKey, -downloadRecourceWithKeydownloadProgresssuccessBlockerrorBlock, -listObjectWithPrefixmarkermaxKeyscompleteBlock, -objectMetaWithKeycompleteBlock, -sharedManager, -singPrivateResourceWithKeyexpirationInterval

### Community 23 - "Community 23"
Cohesion: 0.25
Nodes (7): API, AppConstants, NotificationNames, OSS, URLSchemes, UserDefaultsKeys, VideoCategories

### Community 25 - "Community 25"
Cohesion: 0.29
Nodes (6): CENavigationBar, -initWithFrame, -leftItemAction, -rightItemAction, -traitCollectionDidChange, -updateBackgroundColor

### Community 26 - "Community 26"
Cohesion: 0.29
Nodes (6): CETitleBar, -initWithFrame, -leftBtnAction, -rightBtnAction, -traitCollectionDidChange, -updateTitleStatusWithIndex

### Community 27 - "Community 27"
Cohesion: 0.33
Nodes (3): AnyObject, BaseCoordinator, Coordinator

### Community 29 - "Community 29"
Cohesion: 0.33
Nodes (5): LSLDouYinLikeAnimation, -animationToTop, -createAnimationWithTap, -createAnimationWithTouchwithEvent, -shareInstance

### Community 30 - "Community 30"
Cohesion: 0.33
Nodes (4): BaseRepository, LocalDataSource, NetworkDataSource, Repository

### Community 35 - "Community 35"
Cohesion: 0.4
Nodes (4): UIDevice, -ce_deviceDescription, -ce_deviceType, -ntnu_deviceTypeLookupTable

### Community 38 - "Community 38"
Cohesion: 0.5
Nodes (3): CEHomeBannerView, -initWithFrame, -touchesBeganwithEvent

### Community 39 - "Community 39"
Cohesion: 0.5
Nodes (3): ZFTableData, -initWithKeyvideo, -setValueforUndefinedKey

### Community 40 - "Community 40"
Cohesion: 0.5
Nodes (3): SettingViewController, -navigationViewController, -viewDidLoad

## Knowledge Gaps
- **278 isolated node(s):** `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground`, `-applicationWillEnterForeground`, `-applicationDidBecomeActive` (+273 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **5 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `CustomVideoPlayer` connect `Community 12` to `Community 10`?**
  _High betweenness centrality (0.017) - this node is a cross-community bridge._
- **Why does `VideoListViewModel` connect `Community 2` to `Community 10`?**
  _High betweenness centrality (0.017) - this node is a cross-community bridge._
- **What connects `-applicationdidFinishLaunchingWithOptions`, `-applicationWillResignActive`, `-applicationDidEnterBackground` to the rest of the system?**
  _278 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.08 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.09 - nodes in this community are weakly interconnected._
- **Should `Community 3` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._