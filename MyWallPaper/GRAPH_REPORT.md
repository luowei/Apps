# Graph Report - /Users/luowei/projects/My_App/MyWallPaper  (2026-05-04)

## Corpus Check
- Large corpus: 1421 files · ~2,137,426 words. Semantic extraction will be expensive (many Claude tokens). Consider running on a subfolder, or use --no-semantic to run AST-only.

## Summary
- 1098 nodes · 1208 edges · 68 communities detected
- Extraction: 98% EXTRACTED · 2% INFERRED · 0% AMBIGUOUS · INFERRED: 20 edges (avg confidence: 0.8)
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
- [[_COMMUNITY_Community 65|Community 65]]
- [[_COMMUNITY_Community 66|Community 66]]
- [[_COMMUNITY_Community 67|Community 67]]
- [[_COMMUNITY_Community 68|Community 68]]
- [[_COMMUNITY_Community 69|Community 69]]
- [[_COMMUNITY_Community 76|Community 76]]

## God Nodes (most connected - your core abstractions)
1. `JTSImageViewController` - 80 edges
2. `LWHomeViewController` - 33 edges
3. `UIImage` - 33 edges
4. `CodingKeys` - 32 edges
5. `MyWKWebView` - 28 edges
6. `UIView` - 22 edges
7. `LWSqliteManager` - 19 edges
8. `LWSettingViewController` - 19 edges
9. `StoreObserver` - 18 edges
10. `cn()` - 17 edges

## Surprising Connections (you probably didn't know these)
- `checkDatabase()` --calls--> `getDatabaseConfig()`  [INFERRED]
  Web/scripts/check-database.js → Web/src/lib/db/config.ts
- `checkDatabase()` --calls--> `testDatabaseConnection()`  [INFERRED]
  Web/scripts/check-database.js → Web/src/lib/db/config.ts
- `GET()` --calls--> `getDatabaseConfig()`  [INFERRED]
  Web/src/app/api/health/route.ts → Web/src/lib/db/config.ts
- `GET()` --calls--> `testDatabaseConnection()`  [INFERRED]
  Web/src/app/api/health/route.ts → Web/src/lib/db/config.ts
- `POST()` --calls--> `getDatabaseConfig()`  [INFERRED]
  Web/src/app/api/health/route.ts → Web/src/lib/db/config.ts

## Communities (125 total, 18 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.02
Nodes (80): JTSImageViewController, -accessibilityHintZoomedIn, -accessibilityHintZoomedOut, -adaptivePresentationStyleForPresentationController, -addMotionEffectsToSnapshotView, -addPhotoByBtn, -addSaveButton, -alphaForBackgroundDimmingOverlay (+72 more)

### Community 1 - "Community 1"
Cohesion: 0.06
Nodes (18): downloadPhoto(), getPhotoAttributionUrl(), getPhotographerAttribution(), UnsplashAPI, UnsplashAPIError, useFavorites(), addToRemoveQueue(), dispatch() (+10 more)

### Community 2 - "Community 2"
Cohesion: 0.05
Nodes (36): CaseIterable, FavoriteCategory, abstract, landscape, nature, portrait, uncategorized, urban (+28 more)

### Community 3 - "Community 3"
Cohesion: 0.05
Nodes (10): MyWallPaperTests, MyWallPaperUITests, APIClient, APIClientProtocol, MockAPIClient, FavoritePhoto, FavoriteRepository, FavoriteRepositoryProtocol (+2 more)

### Community 4 - "Community 4"
Cohesion: 0.06
Nodes (34): MyWKUserContentController, -addScriptMessageHandlername, -init, -shareInstance, MyWKWebView, -actionSheetclickedButtonAtIndex, -addUserScriptsToWeb, -connected (+26 more)

### Community 5 - "Community 5"
Cohesion: 0.06
Nodes (33): LWHomeViewController, -addGADBanner, -adViewDidReceiveAd, -cacheAndSaveImageWithURLwithImageHandleBlock, -collectionViewcellForItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewlayoutreferenceSizeForFooterInSection, -collectionViewlayoutreferenceSizeForHeaderInSection (+25 more)

### Community 6 - "Community 6"
Cohesion: 0.06
Nodes (33): UIImage, -addImageToImagewithImage2andRectwithImageSize, -averageColor, -blurImageWithRadius, -blurWithRectradius, -calculatedSize, -combineBGImagewithImageandSizeinSize, -compressLessThan (+25 more)

### Community 7 - "Community 7"
Cohesion: 0.06
Nodes (31): CodingKey, CodingKeys, bio, color, createdAt, description, download, downloadLocation (+23 more)

### Community 8 - "Community 8"
Cohesion: 0.07
Nodes (27): LWPDFPrintActivity, -activityCategory, -activityImage, -activityTitle, -activityType, -canPerformWithActivityItems, -initWithiphoneImageipadImage, -performActivity (+19 more)

### Community 9 - "Community 9"
Cohesion: 0.1
Nodes (16): MockProduct, MockPurchaseManager, PurchaseError, failedVerification, productNotFound, purchaseFailed, PurchaseManager, LocalizedError (+8 more)

### Community 10 - "Community 10"
Cohesion: 0.11
Nodes (15): HomeViewAction, clearSearch, loadMorePhotos, loadPhotos, refresh, searchPhotos, HomeViewModel, HomeViewState (+7 more)

### Community 11 - "Community 11"
Cohesion: 0.08
Nodes (25): LWFavoriteCell, -awakeFromNib, -delBtnAction, -updateWithItem, LWFavoriteModel, LWFavoriteViewController, -addGADBanner, -collectionViewcellForItemAtIndexPath (+17 more)

### Community 12 - "Community 12"
Cohesion: 0.08
Nodes (25): LWLogoView, -initWithFrame, LWSettingViewController, -dataList, -dealloc, -fetchProductInformation, -handleProductRequestNotification, -handlePurchasesNotification (+17 more)

### Community 13 - "Community 13"
Cohesion: 0.14
Nodes (16): Codable, Equatable, FavoriteItem, Identifiable, Endpoint, photo, photos, search (+8 more)

### Community 15 - "Community 15"
Cohesion: 0.09
Nodes (22): UIView, -applicationDidBecomeActive, -applicationDidEnterBackground, -applicationWillEnterForeground, -applicationWillResignActive, -applicationWillTerminate, -copyView, -getSubviewsFirstResponder (+14 more)

### Community 16 - "Community 16"
Cohesion: 0.1
Nodes (19): LWSqliteManager, -copydb2docdata, -copySourceDBFilePathwithTargetDBFileNameoverride, -dealloc, -deleteItemByPhotoId, -execSql, -existItemWithPhotoId, -getItem (+11 more)

### Community 17 - "Community 17"
Cohesion: 0.11
Nodes (18): StoreObserver, -buy, -completeTransactionforStatus, -dealloc, -finishDownloadTransaction, -hasPurchasedProducts, -hasRestoredProducts, -init (+10 more)

### Community 18 - "Community 18"
Cohesion: 0.11
Nodes (13): PreferenceKey, Color, EmptyStateView, ErrorView, GridItemSkeleton, HomeView, LoadingView, PhotoGridItem (+5 more)

### Community 20 - "Community 20"
Cohesion: 0.12
Nodes (16): UIColor, -adjustByPercentage, -adjustColorWithPercentage, -colorComponentFromstartlength, -colorWithHexalpha, -colorWithHexString, -colorWithRGBAString, -darkerByPercentage (+8 more)

### Community 22 - "Community 22"
Cohesion: 0.12
Nodes (15): LWSavePopoverViewController, -cacheAndSaveImageWithURLwithImageHandleBlock, -createAndLoadInterstitial, -dataList, -hudSingleTap, -photoSaveddidFinishSavingWithErrorcontextInfo, -popoverViewControllerWithDelegatesizesourceView, -resizeImageToWallPaper (+7 more)

### Community 23 - "Community 23"
Cohesion: 0.22
Nodes (12): CategoryFilterButton, CategoryFilterView, CategorySelectionSheet, EmptyCategoryView, EmptyFavoritesView, FavoritePhotoGridItem, FavoritesGridView, FavoritesManagementSheet (+4 more)

### Community 24 - "Community 24"
Cohesion: 0.14
Nodes (13): AppDelegate, -applicationDidBecomeActive, -applicationDidEnterBackground, -applicationdidFinishLaunchingWithOptions, -applicationdidReceiveRemoteNotificationfetchCompletionHandler, -applicationdidRegisterForRemoteNotificationsWithDeviceToken, -applicationperformActionForShortcutItemcompletionHandler, -applicationWillEnterForeground (+5 more)

### Community 26 - "Community 26"
Cohesion: 0.15
Nodes (12): LWContentView, -awakeFromNib, -imagedidFinishSavingWithErrorcontextInfo, -loadPhoto, -processImageWithCompletionBlock, -recovery, -reloadImage, -saveImage (+4 more)

### Community 27 - "Community 27"
Cohesion: 0.15
Nodes (12): LWFilterCollectionCell, -awakeFromNib, LWFilterCollectionView, -awakeFromNib, -collectionViewcellForItemAtIndexPath, -collectionViewdidDeselectItemAtIndexPath, -collectionViewdidSelectItemAtIndexPath, -collectionViewnumberOfItemsInSection (+4 more)

### Community 28 - "Community 28"
Cohesion: 0.2
Nodes (7): FullScreenPhotoView, PhotoDetailView, ShimmerModifier, SkeletonContentView, SkeletonView, View, ViewModifier

### Community 29 - "Community 29"
Cohesion: 0.17
Nodes (11): MyModel, -init, -initWithNameelements, StoreManager, -fetchProductInformationForIds, -init, -productsRequestdidReceiveResponse, -requestdidFailWithError (+3 more)

### Community 30 - "Community 30"
Cohesion: 0.17
Nodes (11): LWImageEditerViewController, -createAndLoadInterstitial, -dismissSelf, -hideLoading, -navigationControllerWithImage, -saveAction, -shareAction, -showAd (+3 more)

### Community 31 - "Community 31"
Cohesion: 0.35
Nodes (8): createPrismaClient(), ensureDataDirectory(), getDatabaseConfig(), runMigrations(), testDatabaseConnection(), GET(), POST(), checkDatabase()

### Community 32 - "Community 32"
Cohesion: 0.18
Nodes (10): Reachability, -connectionRequired, -currentReachabilityStatus, -dealloc, -networkStatusForFlags, -reachabilityForInternetConnection, -reachabilityWithAddress, -reachabilityWithHostName (+2 more)

### Community 33 - "Community 33"
Cohesion: 0.18
Nodes (10): LWLinksModel, -modelCustomPropertyMapper, LWPhotoModel, -imageURLString, -modelCustomPropertyMapper, LWPhotoPageModel, -modelContainerPropertyGenericClass, LWProfileImageModel (+2 more)

### Community 35 - "Community 35"
Cohesion: 0.2
Nodes (9): LWHelper, -daysBetweenDateandDate, -excuteOnMainThread, -isAfterDate, -isPurchased, -showHUDWithDetailMessage, -showHUDWithMessage, -showHUDWithMessagemode (+1 more)

### Community 36 - "Community 36"
Cohesion: 0.2
Nodes (9): LWActivityIndicatorView, -initWithFramewithPullDownBlock, -layoutSubviews, -scrollViewDidEndDragging, -scrollViewDidScroll, -scrollViewWillBeginDecelerating, -scrollViewWillEndDragging, -startActivitingWithScrollViewloadingBlock (+1 more)

### Community 37 - "Community 37"
Cohesion: 0.2
Nodes (9): LWFilterImageView, -awakeFromNib, -fileTypeWithKey, -loadImage2GPUImagePicture, -reloadGPUImagePicture, -renderWithFilter, -renderWithFilterKey, -setupSlider (+1 more)

### Community 38 - "Community 38"
Cohesion: 0.2
Nodes (8): GPUImageBeautifyFilter(), -init, -newFrameReadyAtTimeatIndex, -setDistanceNormalizationFactor, -setInputFramebufferatIndex, GPUImageCombinationFilter, -init, -setIntensity

### Community 40 - "Community 40"
Cohesion: 0.22
Nodes (8): LWICloudHelper, -checkICloudAccount, -init, -restoreDBFileRecord, -saveDBFileRecord, -seqByTableNamedbPath, -shareInstance, -topMostController

### Community 41 - "Community 41"
Cohesion: 0.29
Nodes (6): JTSImageInfo, -combinedTitleAndAltText, -description, -displayableTitleAltTextSummary, -referenceRectCenter, -userInfo

### Community 42 - "Community 42"
Cohesion: 0.29
Nodes (6): UIImage, -JTS_applyBlurWithRadiustintColorsaturationDeltaFactormaskImage, -JTS_applyDarkEffect, -JTS_applyExtraLightEffect, -JTS_applyLightEffect, -JTS_applyTintEffectWithColor

### Community 43 - "Community 43"
Cohesion: 0.29
Nodes (6): LWCollectionViewCell, -awakeFromNib, -editBtnTouchUpInside, -likeBtnTouchUpInside, -photographerBtnTouchUpInside, -updateFavoriteStatus

### Community 45 - "Community 45"
Cohesion: 0.33
Nodes (4): LWDataManager, -filterImageName, -filters, -sharedInstance

### Community 47 - "Community 47"
Cohesion: 0.4
Nodes (4): JTSAnimatedGIFUtility, -animatedImageWithAnimatedGIFData, -animatedImageWithAnimatedGIFURL, -imageURLIsAGIF

### Community 48 - "Community 48"
Cohesion: 0.4
Nodes (5): ImageLoadState, failed, fullImageLoaded, loading, thumbnailLoaded

### Community 49 - "Community 49"
Cohesion: 0.4
Nodes (5): ImageLoadingState, failed, fullImageLoaded, loading, thumbnailLoaded

### Community 51 - "Community 51"
Cohesion: 0.4
Nodes (4): LWCollectionViewHeader, -awakeFromNib, -searchFieldEditingChanged, -textFieldShouldReturn

### Community 52 - "Community 52"
Cohesion: 0.4
Nodes (4): UIResponder, -canOpenURLWithString, -openURLWithString, -openURLWithUrl

### Community 53 - "Community 53"
Cohesion: 0.4
Nodes (4): UIButton, -hitTestEdgeInsets, -pointInsidewithEvent, -setHitTestEdgeInsets

### Community 55 - "Community 55"
Cohesion: 0.5
Nodes (3): JTSSimpleImageDownloader, -downloadImageForURLcanonicalURLcompletion, -imageFromDataforURLcanonicalURL

### Community 57 - "Community 57"
Cohesion: 0.5
Nodes (3): ContentView, HomeViewWrapper, TabBarVisibilityManager

### Community 59 - "Community 59"
Cohesion: 0.5
Nodes (3): LWCollectionViewFooter, -awakeFromNib, -textButtonTouchUpInside

### Community 60 - "Community 60"
Cohesion: 0.5
Nodes (3): LWHalfWaySpringAnimator, -animateTransition, -transitionDuration

### Community 61 - "Community 61"
Cohesion: 0.5
Nodes (3): LWNavigationController, -panGestureRecognized, -viewDidLoad

## Knowledge Gaps
- **554 isolated node(s):** `-gotoURL`, `-shareInstance`, `-init`, `-addScriptMessageHandlername`, `-pool` (+549 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **18 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `FavoritesManager` connect `Community 25` to `Community 2`, `Community 23`?**
  _High betweenness centrality (0.029) - this node is a cross-community bridge._
- **Why does `HomeViewModel` connect `Community 10` to `Community 2`, `Community 3`?**
  _High betweenness centrality (0.023) - this node is a cross-community bridge._
- **Why does `CodingKeys` connect `Community 7` to `Community 2`, `Community 13`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **What connects `-gotoURL`, `-shareInstance`, `-init` to the rest of the system?**
  _554 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.02 - nodes in this community are weakly interconnected._
- **Should `Community 1` be split into smaller, more focused modules?**
  _Cohesion score 0.06 - nodes in this community are weakly interconnected._
- **Should `Community 2` be split into smaller, more focused modules?**
  _Cohesion score 0.05 - nodes in this community are weakly interconnected._