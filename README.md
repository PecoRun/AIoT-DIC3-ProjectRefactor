# DIC3

## TransitSense: Three Core Innovations

本研究提出 **TransitSense**：一套結合自然語言互動、證據導向推薦與公共運輸情境感知的智慧餐廳推薦系統，旨在突破傳統餐廳推薦系統的三項限制：

- 過度依賴評分與熱門程度
- 缺乏使用者情境理解
- 未充分考量實際交通可行性

本系統具備三大核心創新：

---

### 1. Contextual Natural Language Understanding — 情境式自然語言理解

透過大型語言模型（LLM）理解使用者以自然語言描述的餐廳需求，將約會、家庭聚餐、多人聚餐、安靜用餐及預算等資訊轉換為結構化情境條件，並結合餐廳評論語意檢索（Semantic Retrieval），分析餐廳特性與使用者需求之間的關聯性，提升推薦結果的情境符合度。

### 2. Evidence-Grounded Recommendation — 證據導向推薦與可信任判斷

整合餐廳評論、語意檢索與 **T/F/U（True、False、Unknown）** 三值判斷機制，針對各項推薦條件進行證據查核，區分：

| 判斷結果 | 意義 |
| :---: | --- |
| **True** | 條件成立 |
| **False** | 條件不成立 |
| **Unknown** | 資訊不足 |

透過推薦條件與來源證據的對應關係，降低大型語言模型產生缺乏依據之推薦內容的風險，提升推薦結果的透明度與可追溯性。

### 3. Public Transit–Aware Contextual Recommendation — 公共運輸情境感知推薦

整合 **TDX 公共運輸資料**，將公車路線、站點、班次及可取得的交通資訊納入推薦決策流程，依據使用者指定的出發地、目的地與時間條件，分析餐廳的交通可行性。

不同於僅提供餐廳附近的公車資訊，本研究進一步將公共運輸條件作為推薦篩選與排序依據，使推薦結果兼顧情境需求與實際抵達條件。

---

## 核心研究價值

從傳統評分導向的餐廳推薦（**Rating-Based Restaurant Recommendation**），
邁向結合情境理解、證據查核與公共運輸可行性分析的可信任智慧推薦
（**Trustworthy, Evidence-Grounded, and Transit-Aware Recommendation**）。
