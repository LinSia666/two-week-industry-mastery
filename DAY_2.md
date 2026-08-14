#### Day 2 — 礦業生命週期

- [x] 畫出金礦從勘探到客戶的完整流程
- [x] 理解黃金集中成礦及五種主要金礦類型
- [x] 為探勘環節補上 People／Company／Equipment／Software／Data
- [x] 區分礦山開發階段與日常生產階段
- [ ] 後續隨研究進度補齊其他環節的 People／Company／Equipment／Software／Data
- **產出：**[`DAY_2.md`](DAY_2.md)

1. 畫出從勘探到客戶的完整流程 - 我們從金礦開始
                             🟡 GOLD INDUSTRY
                              金礦產業
                                 │
                                 ▼
┌─────────────────────────────────────────────────────────────┐
│  ① EXPLORATION 探勘                                         │
│                                                             │
│  找哪裡有金 → 地質調查 → 地球物理/地球化學 → 鑽探 → Assay      │
│                                                             │
│  Geological Survey                                          │
│        ↓                                                    │
│  Target Generation                                          │
│        ↓                                                    │
│  Drilling                                                   │
│        ↓                                                    │
│  Core / RC Samples                                          │
│        ↓                                                    │
│  Sample Preparation → Assay                                 │
│        ↓                                                    │
│  「地下到底有多少金？」                                       │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ② RESOURCE & RESERVE 礦產资源 / 儲量                         │
│                                                             │
│  鑽探資料 → 地質模型 → 品位模型 → Resource Estimate            │
│                                                             │
│  噸數 × Grade (g/t)                                         │
│        ↓                                                    │
│  經濟性評估                                                  │
│        ↓                                                    │
│  「這個礦到底值不值得挖？」                                    │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ③ MINE DEVELOPMENT 礦山開發                                │
│                                                             │
│  Feasibility Study                                          │
│        ↓                                                    │
│  Mining Lease / Approvals                                   │
│        ↓                                                    │
│  Financing                                                  │
│        ↓                                                    │
│  Mine Design                                                │
│        ↓                                                    │
│  建道路、電力、Camp、Processing Plant                         │
│                                                             │
│  💰 這裡開始需要大量 CAPEX                                    │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ④ MINING 採礦                                              │
│                                                             │
│       Open Pit                    Underground                │
│        露天礦                        地下礦                    │
│          │                            │                       │
│  Drill → Blast → Load       Drill → Blast → Load            │
│          │                            │                       │
│          └────────────┬───────────────┘                       │
│                       ▼                                     │
│                  Gold Ore 礦石                               │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ⑤ PROCESSING 選礦 / 提金                                    │
│                                                             │
│  Ore                                                        │
│   ↓                                                         │
│  Crushing 破碎                                               │
│   ↓                                                         │
│  Grinding 研磨                                               │
│   ↓                                                         │
│  Gold Recovery                                              │
│   ↓                                                         │
│  Gravity / Flotation / Cyanidation                          │
│                    ↓                                        │
│                Gold loaded solution/carbon                   │
│                    ↓                                        │
│              Recovery / Electrowinning                       │
│                    ↓                                        │
│                 Smelting                                    │
│                    ↓                                        │
│               🟨 Doré Bar                                   │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ⑥ REFINING 精煉                                            │
│                                                             │
│  Doré                                                       │
│    ↓                                                        │
│  Gold Refinery                                              │
│    ↓                                                        │
│  99.5% / 99.99% Gold                                        │
│    ↓                                                        │
│  Bullion / Investment-grade gold                            │
└─────────────────────────┬───────────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────────┐
│  ⑦ GOLD MARKET 黃金市場                                     │
│                                                             │
│                   Refined Gold                              │
│                        │                                    │
│       ┌────────────────┼───────────────┐                    │
│       ▼                ▼               ▼                    │
│   Jewellery         Investment       Industry               │
│     珠寶               投資             工業                 │
│                       │                                     │
│                 Bar / Coin / ETF                             │
│                                                             │
│                       +                                     │
│                 Central Banks                               │
│                     央行                                     │
└─────────────────────────────────────────────────────────────┘

2. 探勘 - 那金礦從何而來？
    ### 金礦在世界上如何分佈？
    金礦在全世界的分佈，其實金礦全世界都有，但是「集中」與否決定是否值得開採
    | 地區 | 代表區域 | 特徵 |
    |---|---|---|
    | 🇦🇺 澳洲 | **Western Australia / Yilgarn Craton** | 古老綠岩帶、造山型金礦 |
    | 🇿🇦 南非 | **Witwatersrand** | 世界最著名的古老沉積型金礦 |
    | 🇨🇦 加拿大 | Abitibi Greenstone Belt | 古老綠岩帶＋造山型金礦 |
    | 🇺🇸 美國 | Nevada | Carlin-type 金礦非常重要 |
    | 🇨🇳 中國 | Jiaodong 等 | 大型熱液金礦系統 |
    | 🇷🇺 俄羅斯 | Siberia / Far East | 古老克拉通與造山帶 |
    | 🇺🇿 中亞 | Muruntau | 世界級超大型金礦 |
    | 🇵🇬🇮🇩 西太平洋 | PNG / Indonesia | 火山弧、斑岩與淺成熱液系統 |
    | 🇵🇪🇨🇱 南美 | Andes | 板塊隱沒＋火山活動 |
    若先用最簡單的地質背景理解，許多大型金礦常見於以下兩種環境，但這不是完整的礦床分類：
    - 古老地塊：澳洲、南非、加拿大、美國（阿拉斯加金礦賭注）、（中國、中亞、俄羅斯）
    - 火山活動：印尼、智利、秘魯

    ### 黃金從何而來？
    黃金不是在地球內部生成的；形成黃金這類重元素需要中子星合併等高能宇宙事件
    所以這些黃金本來散佈在太陽系，大約 45–46 億年前形成地球時，黃金也一起進來。

    ### 黃金去哪裡了？
    黃金屬於具有 **siderophile（親鐵）**特性的元素。
    在地球早期還是一團熱糊糊的時候，黃金就跟鐵、鎳一起下沉到地心了，所以地球上的多數黃金我們無法開採。
    所以問題來了，大部分的黃金都在地心，地殼剩下這一點點的黃金如何「集中」成值得開採的金礦呢？

    ### 地殼剩下這一點點的黃金如何「集中」成值得開採的金礦呢？
    岩石 -> 高溫、高壓 -> 產生／循環熱液 -> 熱液可以攜帶溶解的 Au -> 沿著 fault / fracture 移動 -> 溫度、壓力、化學條件改變 -> Au 沉澱 -> 累積 -> 形成金礦
    **可以想像是金礦被溶解後，從地層的縫縫被擠上地殼，某些地質條件，就會讓這些含有黃金的液體沉澱，形成金礦**
    這是其中一種形成金礦的方式，也是西澳卡爾古利（Kalgoorlie）地區常見的造山型金礦成因。金礦仍有其他形成方式，以下先整理五種主要類型：
        | 類型 | 代表 | 主要機制 |
    |---|---|---|
    | **Orogenic Gold** | 🇦🇺 WA、🇨🇦 Canada | 造山＋斷層＋熱液 |
    | **Carlin-type** | 🇺🇸 Nevada | 熱液進入碳酸鹽岩等特定地層，形成細粒／不可見金 |
    | **Epithermal** | 🇮🇩 🇵🇭 🇯🇵 | 淺部火山熱液系統 |
    | **Porphyry-related Au** | 🇨🇱 🇵🇬 🇮🇩 | 岩漿系統，常與 Cu 一起 |
    | **Paleoplacer / Placer** | 🇿🇦 South Africa | 搬運＋沉積造成物理集中 |

    ### 五種金礦類型的簡單形成流程

    1. **Orogenic Gold（造山型金礦）** 西澳 Yilgarn Craton／Kalgoorlie
       板塊擠壓與造山作用 → 岩石受高溫、高壓影響並釋放含金熱液 → 熱液沿斷層與裂隙流動 → 溫度、壓力或化學條件改變 → 黃金在石英脈或周圍岩石中沉澱。

    2. **Carlin-type（卡林型金礦）**  美國西部內華達州
       深部熱液攜帶黃金上升 → 熱液進入容易發生化學反應的碳酸鹽岩 → 岩石被溶解、改造 → 極細小、肉眼看不見的黃金分散沉澱在岩石中。

    3. **Epithermal（淺成熱液型金礦）**  印尼
       淺部岩漿加熱地下水 → 含金熱液往接近地表的位置上升 → 熱液因降溫、降壓或沸騰而改變 → 黃金與銀在裂隙及礦脈中沉澱。

    4. **Porphyry-related Au（斑岩相關金礦）**  智利、秘魯
       岩漿在地下冷卻 → 釋放富含金屬的高溫流體 → 流體穿過岩體與周圍裂隙 → 銅、金等金屬形成大量細小、分散的礦化，通常規模大但品位較低。

    5. **Paleoplacer / Placer（古砂礦／砂礦）**  南非
       原生金礦風化崩解 → 河水搬運岩屑與金粒 → 密度較高的黃金沉積在河床、礫石層或古河道 → 長時間累積並形成可開採的砂金層。

    ### 知識總結題：如何成為黃金獵人！！
    1. 確認哪些區域可以合法的探勘（不合法有黃金去也沒用）
    2. 確認這邊可能有黃金
        - 先把過去的金礦點標出來，可以參考過去開採的資料
        - 確認地質結構方向，應用剛剛學到的，縫隙、綠岩帶，可能這個地質結構有繼續延伸，但某些部分沒有開採紀錄，但機率上，有黃金的可能性
    3. 再來用天氣、河流等地表侵蝕判斷，黃金如果被侵蝕，可能被帶到哪，堆積在哪？

   ### People／Company／Equipment／Software／Data
   - People：地質學家（Geologist）、Field Technician、鑽探工＋鑽機維護人員、製樣員＋分析員
   - Company：
      - 礦業／探勘公司（通常有自己的 Exploration Team）:
         - ERM／CSA Global — 綜合型礦業顧問：CSA Global 現為 ERM 的一部分，業務涵蓋 Exploration、Resource Estimation 到礦業開發。
         - Southern Geoscience Consultants (SGC) — 地球物理專家：用磁力、重力、EM、IP 等方法「看地下」，協助產生 drilling targets。SGC
         - RSC Geological Consultants — 地質探勘顧問／外包 Exploration Team：可提供地質學家、field crew、mapping、target generation 到 drilling management。礦產資源開發專家
      - Drilling Contractor
         - Perenti — 大型礦業服務集團：旗下涵蓋 drilling、underground mining 等服務；鑽探業務包含 DDH1、Ausdrill 等品牌。
            - DDH1 Drilling（Perenti）— 深孔／Diamond Drilling 專家：偏高技術、高難度的深部探勘鑽探。
            - Ausdrill（Perenti）— 大型綜合鑽探服務：Exploration、Grade Control 到 Production / Drill & Blast 都有涉及。
         - Topdrill — Kalgoorlie Exploration Drilling 專家：以 RC + Diamond drilling 為主，很貼近 Goldfields 探勘市場。
      - 商業 Assay Laboratory（探勘階段通常外包）
         - ALS — 全球大型分析實驗室集團：礦業從 Sample Preparation、Fire Assay 到各種 geochemistry 分析都做，是理解全球商業 assay lab 很好的代表。
         - Intertek Minerals — 大型礦業檢測／分析服務商：在西澳礦業很重要，提供 exploration、mine-site laboratory、metallurgical testing 等服務。
         - Bureau Veritas Minerals — 全球檢測集團的 Minerals 業務：提供 sample preparation、geochemical analysis、mine-site laboratory 等完整礦業分析服務。
   - Equipment：4WD、GPS、地表採樣工具、地球物理探測設備、RC／Diamond Drill Rig、Sample Prep＋Assay 設備
   - Software：GIS、3D Geological Modelling Software（如 Leapfrog）
   - Data：哪個位置、哪個 Drill Hole、哪個深度、是什麼岩石／構造、Au 品位多少（g/t）

### Day 2 總結

今天建立了金礦從探勘、資源與儲量評估、礦山開發、採礦、選礦、精煉到市場的整體流程，並進一步理解黃金如何透過熱液、岩漿、構造活動或沉積作用形成可開採的礦床。

目前已能簡單比較造山型、卡林型、淺成熱液型、斑岩相關型及砂礦型金礦，也開始把探勘環節拆解成實際的人員、公司、設備、軟體與資料。其他生命週期環節的五欄資料將在後續研究公司、營運與軟體時逐步補齊。

### 仍待回答

- Resource 與 Reserve 的正式差異是什麼？
- 不同金礦類型會如何改變探勘方法、開採方式與加工流程？
- 從發現礦化到確認具有經濟開採價值，中間最容易失敗在哪一步？

### 參考資料

- [Geoscience Australia — Gold](https://www.ga.gov.au/education/minerals-energy/australian-mineral-facts/gold)
- [USGS — Mines and mineral occurrences in the Carlin area, Nevada](https://www.usgs.gov/data/mines-mineral-occurrences-and-mining-districts-carlin-area-nevada)
- [ERM announces acquisition of CSA Global](https://www.erm.com/about/news/erm-announces-acquisition-of-csa-global/)
