# 兩週理解礦業

這是一個為期 14 天的公開產業研究練習。研究範圍以西澳礦業為起點，優先比較鐵礦、黃金與鋰，並從 Product／Software／AI 的角度理解產業。

這個計畫追求的不是在兩週內「精通」礦業，而是建立一套 **Mining Industry Operating Model**：知道產業如何運作、誰與誰交易、資料和決策出現在哪裡、自己還缺少哪些知識，以及應該去哪裡找答案。

## 14 天後要做到什麼

- 能用自己的話說明礦業生命週期與價值鏈
- 能比較鐵礦、黃金與鋰的流程、經濟性和商業模式
- 能快速閱讀礦業公司的年報、營運報告與職缺
- 能與礦業 PM、營運人員、工程師或創業者進行 30–60 分鐘的有效對話
- 能把一個 Software／AI 機會定位到具體 commodity、場域、workflow、使用者和決策者
- 能提出有證據支持的觀點，同時清楚標示未知與假設

## 執行規則

每天約 60 分鐘：

1. **5 分鐘：**回顧昨天的問題與未解項目
2. **35 分鐘：**閱讀官方資料、公司文件或產業職缺
3. **15 分鐘：**用自己的話整理當日產出
4. **5 分鐘：**提交到 GitHub，並寫下一個最重要的問題

每則筆記至少記錄：

- 資料來源與日期
- 三個關鍵發現
- 一個仍不確定的地方
- 一個值得詢問產業人士的問題
- 內容屬於事實、推論還是假設

## 核心產業模型

研究任何公司或技術時，都先定位它位於哪個環節：

```text
Exploration → Resource definition → Feasibility → Mine development
→ Drill & Blast → Load & Haul → Crushing → Processing
→ Quality control → Transport → Port → Customer
```

每個環節都回答五個問題：

1. 有哪些人參與？
2. 有哪些公司與設備？
3. 使用哪些軟體與資料？
4. 誰付錢給誰，為什麼？
5. 最大的成本、風險與瓶頸是什麼？

先用下列簡化模型理解礦業公司的經濟性：

```text
Revenue ≈ Volume × Commodity price × Quality

Cost drivers ≈ Mining + Processing + Labour + Energy
             + Maintenance + Transport + Royalties + Capex
```

## 14 天學習計畫

### 第一週：建立知識地圖與檢索能力

#### Day 1 — 定義範圍與問題

- [ ] 說明為什麼以西澳、鐵礦、黃金與鋰為研究範圍
- [ ] 寫出目前對礦業的認知、假設與盲點
- [ ] 建立 10 個希望在第 14 天回答的問題
- **產出：**[`DAY_1.md`](DAY_1.md)

#### Day 2 — 礦業生命週期

- [ ] 畫出從勘探到客戶的完整流程
- [ ] 為每個環節補上 People／Company／Equipment／Software／Data
- [ ] 區分礦山開發階段與日常生產階段
- **產出：**`maps/mining-lifecycle.md`

#### Day 3 — 比較三種 Commodity

- [ ] 比較鐵礦、黃金與鋰的產品、客戶、定價和主要流程
- [ ] 記錄 grade、recovery、product quality 對三者的不同意義
- [ ] 說明為何不能把「礦業」視為單一商業模式
- **產出：**`notes/day-03-commodities.md`

#### Day 4 — 產業上下游與金流

- [ ] 畫出礦業公司、承包商、設備商、實驗室、物流、軟體商與客戶
- [ ] 對每一類參與者回答「它向誰收費、解決什麼問題」
- [ ] 選一條鐵礦供應鏈追蹤到鋼鐵客戶
- **產出：**`maps/value-chain.md`

#### Day 5 — 公司拆解

- [ ] 選擇 BHP、Rio Tinto、Fortescue，再加入一家黃金或鋰公司
- [ ] 每家公司只回答：挖什麼、在哪裡、產量、成本、客戶、風險、投資方向
- [ ] 區分公司陳述、可驗證數據與自己的推論
- **產出：**`companies/company-comparison.md`

#### Day 6 — 人、工作與購買決策

- [ ] 閱讀至少 10 個礦業營運、技術、產品或數位轉型職缺
- [ ] 整理常見職責、KPI、工具、痛點與術語
- [ ] 找出使用者、影響者、預算擁有者和最終決策者可能分別是誰
- **產出：**`notes/day-06-jobs-and-buyers.md`

#### Day 7 — 第一週整合與知識缺口

- [ ] 不看資料，重新畫一次產業地圖
- [ ] 對各領域進行 0–10 分自評，並為分數寫證據
- [ ] 選出三個最低分且最影響目標的領域
- [ ] 根據缺口調整 Day 8–12 的研究比重
- **產出：**`reviews/week-01-review.md`

知識缺口評分表：

| 領域 | 分數（0–10） | 我能證明什麼 | 下一個問題 |
| --- | ---: | --- | --- |
| Mining lifecycle |  |  |  |
| Iron ore／Gold／Lithium |  |  |  |
| Exploration |  |  |  |
| Drill & blast |  |  |  |
| Processing |  |  |  |
| Logistics |  |  |  |
| Mine economics |  |  |  |
| Mining software |  |  |  |
| Automation／AI |  |  |  |

### 第二週：理解營運並形成觀點

#### Day 8 — Mine Economics

- [ ] 解釋 CAPEX、OPEX、cash cost、AISC、grade、recovery 與 strip ratio
- [ ] 說明這些指標如何影響鐵礦、黃金與鋰項目
- [ ] 用一家公司公開資料做簡化的營收與成本驅動分析
- **產出：**`notes/day-08-mine-economics.md`

#### Day 9 — Mining Operations

- [ ] 理解 Drill → Blast → Load → Haul → Crusher 的輸入、輸出與交接
- [ ] 找出安全、等待、設備利用率、燃料與維護方面的瓶頸
- [ ] 記錄每個環節產生的資料與關鍵決策
- **產出：**`workflows/mining-operations.md`

#### Day 10 — Mineral Processing

- [ ] 理解 crushing、grinding、flotation、leaching 與 gravity separation 的用途
- [ ] 不追求計算，重點描述每一步的輸入、處理、輸出與品質指標
- [ ] 比較三種 commodity 為何需要不同處理流程
- **產出：**`workflows/mineral-processing.md`

#### Day 11 — Mining Technology

- [ ] 研究 fleet management、autonomous haulage、remote operations 與 predictive maintenance
- [ ] 為每項技術記錄使用者、資料、決策、效益、限制與導入條件
- [ ] 找出「展示看起來有效」與「現場能穩定使用」之間的差距
- **產出：**`technology/mining-technology.md`

#### Day 12 — Mining Software Landscape

- [ ] 研究 geological modelling、mine planning、fleet、laboratory、ERP、maintenance 與 safety systems
- [ ] 為每類系統記錄工作流程位置、主要使用者和可能供應商
- [ ] 找出系統間的資料交接、重複輸入與資訊孤島
- **產出：**`technology/software-landscape.md`

#### Day 13 — Software／AI 機會判斷

- [ ] 從前 12 天的具體問題出發，而不是搜尋泛稱的「AI in Mining」
- [ ] 產生至少 10 個問題機會，並篩選出最值得驗證的 3 個
- [ ] 對前三名完成 Opportunity Card
- **產出：**`opportunities/opportunity-shortlist.md`

Opportunity Card 必須回答：

| 問題 | 說明 |
| --- | --- |
| Commodity／場域 | 哪種礦？露天、地下、選礦廠或物流？ |
| Workflow | 問題發生在哪一個具體步驟？ |
| 使用者／決策者 | 誰每天使用？誰批准採購？ |
| 現行方法 | 現在如何處理，已有什麼軟體？ |
| 問題代價 | 對停機、安全、產量、成本或品質有何影響？ |
| 所需資料 | 資料在哪裡、品質如何、能否取得？ |
| 解決方案 | AI 為何比規則、流程改善或既有工具更適合？ |
| 導入風險 | 安全、整合、信任、法規與現場限制是什麼？ |
| 驗證方式 | 下一步要訪談誰，或取得什麼證據？ |

#### Day 14 — Mining Industry Thesis

- [ ] 完成一份約 5 頁的產業觀點
- [ ] 回答 Day 1 的 10 個問題，未能回答者清楚標記
- [ ] 更新知識缺口評分，與 Day 7 比較
- [ ] 寫出下一個 30 天應繼續驗證的三件事
- **產出：**`thesis/mining-industry-thesis.md`

最終報告至少包含：

1. Mining Industry Map
2. Value Chain 與金流
3. Key Players 與商業模式
4. 主要營運問題與證據
5. Technology／Software Landscape
6. 三個 Software／AI 機會
7. 未知、反證與下一步

## 建議資料來源

優先閱讀一手資料，媒體或顧問文章只用來發現線索：

- [Geoscience Australia — Australia's Identified Mineral Resources](https://www.ga.gov.au/aimr)
- [Australian Government — Resources and Energy Quarterly](https://www.industry.gov.au/publications/resources-and-energy-quarterly)
- [WA Government — Economic indicators](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/economic-indicators)
- [WA Government — Major commodities](https://www.wa.gov.au/organisation/department-of-mines-petroleum-and-exploration/major-commodities)
- [data.wa.gov.au — Operating Mines](https://catalogue.data.wa.gov.au/dataset/operating-mines)
- BHP、Rio Tinto、Fortescue 等公司的年報與營運報告
- 礦業公司、承包商、設備商與軟體商的職缺說明

公司報告不要從頭讀到尾。先固定回答：

> 它挖什麼？礦在哪裡？產量與成本如何？賣給誰？最大風險是什麼？目前投資什麼？

## 完成標準

這個練習完成的標誌不是讀完多少文章，而是能夠：

- 不看資料畫出產業鏈，並解釋每個主要環節
- 對重要主張附上一手來源，並區分事實、推論和假設
- 指出至少三個自己的知識缺口及補強方法
- 用具體 workflow 說明三個值得驗證的 Software／AI 機會
- 提出至少 10 個能與產業人士深入討論、而非只問名詞的問題
- 完成 Mining Industry Thesis，並能在 10 分鐘內說明核心觀點
