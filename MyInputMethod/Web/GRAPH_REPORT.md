# Graph Report - /Users/luowei/projects/My_App/MyInputMethod/Web  (2026-05-05)

## Corpus Check
- 61 files · ~55,474 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 215 nodes · 284 edges · 12 communities detected
- Extraction: 85% EXTRACTED · 15% INFERRED · 0% AMBIGUOUS · INFERRED: 44 edges (avg confidence: 0.64)
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
- [[_COMMUNITY_Community 18|Community 18]]

## God Nodes (most connected - your core abstractions)
1. `InputMethodService` - 37 edges
2. `InputEngineService` - 14 edges
3. `CandidateWord` - 10 edges
4. `PinyinEngine` - 10 edges
5. `WubiEngine` - 10 edges
6. `ExternalApiService` - 8 edges
7. `errorHandler()` - 8 edges
8. `InputMethodType` - 6 edges
9. `UserSelectionCreate` - 6 edges
10. `Word` - 5 edges

## Surprising Connections (you probably didn't know these)
- `InputMethodService` --uses--> `InputMethodType`  [INFERRED]
  backend/app/services/inputmethod_service.py → backend/app/schemas/inputmethod.py
- `InputMethodService` --uses--> `Word`  [INFERRED]
  backend/app/services/inputmethod_service.py → backend/app/schemas/inputmethod.py
- `PinyinEngine` --uses--> `CandidateWord`  [INFERRED]
  backend/app/services/inputmethod_service.py → backend/app/schemas/inputmethod.py
- `WubiEngine` --uses--> `CandidateWord`  [INFERRED]
  backend/app/services/inputmethod_service.py → backend/app/schemas/inputmethod.py
- `InputMethodService` --uses--> `UserPhraseCreate`  [INFERRED]
  backend/app/services/inputmethod_service.py → backend/app/schemas/inputmethod.py

## Communities (39 total, 4 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.09
Nodes (21): create_user_phrase(), delete_user_phrase(), export_dictionary(), get_candidates(), get_input_statistics(), get_user_phrases(), import_dictionary(), 搜索词库     支持按词汇、编码、拼音搜索 (+13 more)

### Community 1 - "Community 1"
Cohesion: 0.25
Nodes (16): Enum, InputMethodSettings, InputMethodSettingsBase, InputMethodSettingsCreate, InputMethodType, UserPhrase, UserPhraseBase, UserPhraseCreate (+8 more)

### Community 3 - "Community 3"
Cohesion: 0.23
Nodes (13): BaseModel, CandidateRequest, InputMethodSettingsUpdate, WordUpdate, Token, TokenData, User, UserBase (+5 more)

### Community 4 - "Community 4"
Cohesion: 0.15
Nodes (4): connectDatabase(), setupSwagger(), startServer(), setupWebSocket()

### Community 5 - "Community 5"
Cohesion: 0.23
Nodes (10): Base, InputMethodSettings, UserPhrase, UserSelection, Word, Theme, ThemeRating, UserTheme (+2 more)

### Community 6 - "Community 6"
Cohesion: 0.26
Nodes (8): CustomError, errorHandler(), handleJWTError(), handleJWTExpiredError(), handlePrismaError(), handleValidationError(), sendErrorDev(), sendErrorProd()

### Community 8 - "Community 8"
Cohesion: 0.25
Nodes (4): add_process_time_header(), global_exception_handler(), MyInputMethod Web Backend FastAPI主应用程序入口点, str

### Community 10 - "Community 10"
Cohesion: 0.33
Nodes (3): BaseSettings, Config, Settings

## Knowledge Gaps
- **5 isolated node(s):** `MyInputMethod Web Backend FastAPI主应用程序入口点`, `Config`, `获取候选词     支持多种输入法：拼音全键、九键、五笔、笔画等`, `搜索词库     支持按词汇、编码、拼音搜索`, `输入法核心服务 实现候选词生成、用户学习、词库管理等功能`
  These have ≤1 connection - possible missing edges or undocumented components.
- **4 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `InputMethodService` connect `Community 0` to `Community 8`, `Community 1`?**
  _High betweenness centrality (0.078) - this node is a cross-community bridge._
- **Why does `InputMethodType` connect `Community 1` to `Community 8`, `Community 0`?**
  _High betweenness centrality (0.021) - this node is a cross-community bridge._
- **Why does `CandidateWord` connect `Community 0` to `Community 1`, `Community 3`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Are the 18 inferred relationships involving `InputMethodService` (e.g. with `CandidateWord` and `InputMethodType`) actually correct?**
  _`InputMethodService` has 18 INFERRED edges - model-reasoned connections that need verification._
- **Are the 8 inferred relationships involving `CandidateWord` (e.g. with `PinyinEngine` and `WubiEngine`) actually correct?**
  _`CandidateWord` has 8 INFERRED edges - model-reasoned connections that need verification._
- **Are the 8 inferred relationships involving `PinyinEngine` (e.g. with `CandidateWord` and `InputMethodType`) actually correct?**
  _`PinyinEngine` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `MyInputMethod Web Backend FastAPI主应用程序入口点`, `Config`, `获取候选词     支持多种输入法：拼音全键、九键、五笔、笔画等` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._