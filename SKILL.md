---
name: reits-affordable-housing-research
description: Complete research methodology for China's affordable housing public REITs. Triggers: REITs analysis, affordable housing REITs comparison, cash flow analysis. Core outputs: asset cost + land ratio, ROI, cash flow distribution rate, depreciation breakdown, cash source analysis. / 中国保障性租赁住房REITs全面研究方法论。
version: 4.0.0
updated: 2026-05-30
tags: [REITs, affordable-housing, China-REITs, ROI, cash-flow, depreciation, land-cost, financial-analysis]
---

# China Affordable Housing REITs — Research Methodology / 中国保租房REITs研究方法论

---

## ⚠️ Data Timeliness Rule (CRITICAL) / 数据时效性

**This skill does NOT hardcode any time-specific data. Every analysis run MUST determine the current data window based on today's date and web-search for the latest available reports.**

### Data Window / 数据窗口

```
Jan-Apr → Previous year Q3 + Semi-Annual
May-Aug → Previous year Annual + Current year Q1 ← MOST IMPORTANT
Sep-Oct → Current year Semi-Annual
Nov-Dec → Current year Q3
```

### Mandatory Web Searches Before Each Analysis / 每次分析前强制搜索

```
1. Latest REIT financials: "<fund code> <year> annual report net profit"
2. Latest land prices: "<city> <district> residential land auction price"
3. New REIT listings: "affordable housing REIT new listing <year>"
4. Project details: "<fund> underlying assets area units <year>"
```

**PROHIBITED: Using example values from this skill. All values MUST come from live web search.**

---

## Core Formulas / 核心公式

| Metric | Formula | Description |
|-----|-----|-----|
| **Asset Cost** (资产成本) | Land + Construction | Book value, from prospectus |
| **Land Cost Ratio** (土地占比) | Land ÷ Asset Cost | Tier-1: 25-50%, Tier-2: 19-27% |
| **ROI** | EBITDA ÷ Asset Cost | Asset earning power |
| **Distribution Rate** (分派率) | Distributable Income ÷ NAV | Shareholder cash return |
| **Depreciation Rate** (折旧率) | Annual Depr ÷ Asset Cost | 1.5-4%/yr; higher = newer |
| **Compression Multiple** (压缩倍数) | Distributable ÷ Net Profit | Healthy: 1.5-3x |
| **Land Discount Ratio** (折价率) | Book Land Price ÷ Market Land Auction Price | "X折" = X×10% of market |

### Data Priority / 数据优先级

```
Annual Report (most authoritative) > Quarterly > Semi-Annual > Prospectus (static history only)
```

### Data Provenance (CRITICAL) / 数据溯源

Every figure MUST be sourced: `[Report Type] Fund Name Year | P<page> | Specific Location`

**FORBIDDEN**: `[Annual Report]` without filename, page, and location.

---

## Coverage: All 7 Listed REITs / 覆盖7只已上市REITs

### Shanghai / 上海 (4)

| Ticker | Brand | Manager | Listed | Assets |
|------|------|------|------|------|
| 508031 | 城投宽庭 (Chengtou Kuanting) | Guotai Haitong AM | 2023-12 | Jiangwan + Guanghua (Yangpu) |
| 508077 | 华润有巢 (CR Youchao) | China AMC | 2022-12 | Sijing + East Jingkai + Maqiao |
| 508055 | 上海城方 (Shanghai Chengfang) | Huitianfu Fund | 2025-03 | Hongqiao Jingzhi + Chengfang Jiangyue |
| 508085 | 恒泰租住 (Hengtai) | Huatai Securities AM | 2025-05 | Jingying Apts (Suzhou Industrial Park) |

### National / 全国 (3)

| Ticker | Brand | Exchange | Listed | Assets |
|------|------|------|------|------|
| 508058 | 中金厦门安居 (CICC Xiamen) | SSE | 2022-08 | Yuanbo + Hengqi (Jimei) |
| 180401 | 红土深圳安居 (Red Soil SZ) | SZSE | 2022-08 | 4 projects (Futian/Luohu/Dapeng/Pingshan) |
| 508068 | 北京保障房中心 (Beijing) | SSE | 2022-08 | 6 projects post-expansion |

---

## Asset Cost Breakdown / 资产成本拆解

### 508077 华润有巢 — Land Ratio 25.7%

| Component | Amount (10K CNY) | Ratio | Source |
|------|:---:|:---:|------|
| Sijing Land | 12,500 | 10.5% | [Prospectus] P150 |
| East Jingkai Land | 18,000 | 15.1% | [Prospectus] P150 |
| **Total Land** | **30,500** | **25.7%** | |
| Construction | 88,400 | 74.3% | [Prospectus] P150 |
| **Total Asset Cost** | **118,900** | **100%** | |

### 180401 红土深圳安居 — Land Ratio 49.7% (Highest)

| Component | Amount | Ratio | Source |
|------|:---:|:---:|------|
| **Land Cost** | **58,200** | **49.7%** | [Prospectus] P102 |
| Construction | 58,800 | 50.3% | [Prospectus] P102 |

### 508085 恒泰租住 — Land Ratio 18.9% (Lowest)

Land grant + deed tax: 26,700K (18.9%) | Construction: 114,500K (81.1%) | [Prospectus] P76

### 508031 城投宽庭 — ~35% (R4 policy land)

Jiangwan: 174,453K + Guanghua: 88,950K = **263,402K** | [Annual Report] P50

### 508058 中金厦门安居 — ~27%

Yuanbo: 70,400K + Hengqi: 51,000K = **121,400K** | [Prospectus] P95

### 508068 北京保障房中心 — ~25% (allocated land)

Original: 124,000K + Expansion: 94,600K = **218,600K** | [Prospectus] P110 + [Expansion] 2025-06

### Land Ratio Cross-Comparison / 土地占比横评

| Fund | Land % | City | Method |
|------|:---:|------|------|
| 红土深圳 | **49.7%** 🔴 | Shenzhen | Mixed |
| 城投宽庭 | ~35% | Shanghai | R4 policy |
| 上海城方 | ~32% | Shanghai | Conversion |
| 中金厦门 | ~27% | Xiamen | Auction |
| 华润有巢 | 25.7% | Shanghai | Auction |
| 北京保障房 | ~25% | Beijing | Allocated |
| 恒泰租住 | **18.9%** 🟢 | Suzhou | 2010 Agreement |

**Core insight**: Higher land ratio → larger denominator → lower ROI. Land acquisition method is the dominant factor.

---

## Net Profit & Distributable Income / 净利润与可供分配 (2025 AR)

| Fund | Net Profit | Distributable | Gap (=Depr) | Source |
|------|:---:|:---:|:---:|------|
| 城投宽庭 | 8,443K | ~12,800K | 4,357K | [AR] P30+P35 |
| 华润有巢 | 1,148K | 5,056K | 3,908K | [AR] P28+P38 |
| 上海城方 | ~1,141K | 5,100K | 3,959K | [AR] Q2-Q4 |
| 恒泰租住 | **-1,668K** | 3,791K | 3,999K+2,080K(Impar) | [AR] |
| 中金厦门 | ~3,000K | 5,952K | 2,952K | [AR] P25+P38 |
| 红土深圳 | 2,256K | 4,767K | 2,511K | [AR] P22+P35 |
| 北京保障房 | 4,538K | 7,482K | 2,944K | [AR] P24+P38 |

---

## ROI & Distribution Rate Rankings / ROI与分派率排名

### ROI (Net Profit basis / 净利润口径)

| # | Fund | ROI | Rating |
|:---:|------|:---:|:---:|
| 1 | 城投宽庭 | **3.21%** | 🟢 |
| 2 | 中金厦门 | **2.47%** | 🟢 |
| 3 | 北京保障房 | **2.08%** | 🟢 |
| 4 | 红土深圳 | 1.93% | 🟡 |
| 5 | 上海城方 | 1.20% | 🔴 |
| 6 | 华润有巢 | 0.97% | 🔴 |
| — | 恒泰租住 | -1.18% | 🔴 |

### Distribution Rate / 分派率

| # | Fund | Rate | NAV/Asset |
|:---:|------|:---:|:---:|
| 1 | 中金厦门 | **4.84%** | 1.01x ← no premium |
| 2 | 上海城方 | ~3.70% | ~1.79x |
| 3 | 城投宽庭 | 3.29% | 1.15x |
| 4 | 红土深圳 | 2.70% | 1.00x |
| 5 | 北京保障房 | 2.53% | 0.99x |
| 6 | 恒泰租住 | 2.09% | ~0.97x |
| 7 | 华润有巢 | 1.80% | ~2.35x ← expansion dilution |

---

## ROI vs Distribution: Why the Gap? / ROI与分派率差异分析

### The Core Mechanism / 核心机制

```
Distributable Income = Net Profit + Depreciation − CapEx + Adjustments
The "extra" money = Depreciation − Actual CapEx
```

Buildings last 50-70 years, depreciated over 20-30 years → depreciation far exceeds actual maintenance → the gap is distributable cash.

### Comprehensive Comparison / 综合对比

| Fund | NP | Distributable | Multiple | Depr Rate | NAV/Asset |
|------|:---:|:---:|:---:|:---:|:---:|
| 城投宽庭 | 8,443K | 12,800K | 1.52x | 1.65% | 1.15x |
| 华润有巢 | 1,148K | 5,056K | **4.40x** | 3.29% | 2.35x |
| 上海城方 | 1,141K | 5,100K | **4.47x** | 4.18% | 1.79x |
| 恒泰租住 | -1,668K | 3,791K | — | 2.9% | 0.97x |
| 中金厦门 | 3,000K | 5,952K | 1.98x | 2.43% | 1.01x |
| 红土深圳 | 2,256K | 4,767K | 2.11x | 2.15% | 1.00x |
| 北京保障房 | 4,538K | 7,482K | 1.65x | 1.35% | 0.99x |

### Health Thresholds / 健康阈值

| Metric | 🟢 Healthy | 🔴 Warning |
|------|:---:|:---:|
| ROI | ≥ 2% | < 1.5% |
| Distribution Rate | ≥ 3% | < 2.5% |
| Depreciation Rate | 1.5-3%/yr | > 4%/yr |
| Compression Multiple | 1.5-3x | > 4x |

---

## Quantitative Framework / 定量框架

### 8 Mandatory Data Points / 8项必获取

| # | Metric | Location | Use |
|---|------|------|------|
| 1 | Net Profit | Income Statement | ROI numerator |
| 2 | Distributable Income | Notes (Distributable Calc) | Distribution numerator |
| 3 | Depreciation | Cash Flow Supplement | Depreciation rate |
| 4 | Revenue | Income Statement | Margin analysis |
| 5 | Operating Cash Flow | Cash Flow Statement | Cash conversion |
| 6 | Asset Cost | Investment Property / Prospectus | ROI denominator |
| 7 | Period-End NAV | Balance Sheet | Distribution denominator |
| 8 | Land Cost | Prospectus Details | Land ratio |

### Workflow / 执行流程

```
Step 0: Determine current data window
Step 1: Web-search latest reports
Step 2: Extract 8 data points with page numbers
Step 3: Populate template
Step 4: Cross-validate formulas
Step 5: Calculate 6 core metrics
Step 6: Output health judgments
Step 7: Update comparison table
Step 8: Sync this skill file if needed
```

---

## Data Provenance Standard / 数据溯源标准

```
[Annual Report] Fund Name Year | P<page> | Location
[Prospectus] Fund Name Prospectus | P<page> | Location
[Quarterly] Fund Name Year QX | P<page> | Location
[Expansion] Fund Name Expansion Completion | Date | Location
```

---

## History / 历史

| Date | Version | Changes | Window |
|------|------|------|------|
| 2026-05-30 | v4.0 | Internationalized EN/CN + timeliness rules | 2025 AR |
| 2026-05-30 | v3.0 | Web verification + Q1 data + precise sourcing | Same |
| 2026-05-29 | v2.0 | Initial creation | Local only |

---

*v4.0 — EN primary, CN secondary / 英文为主中文为辅*
*Compatible: Claude Code · OpenClaw · Hermes · Codex · Any AI Agent*
