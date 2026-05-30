# 🏢 中国保障性租赁住房公募REITs 深度研究方法论

<h3 align="center"><em>7只REITs全覆盖 · 资产成本拆解 · ROI杜邦分解 · 土地折价量化 · 现金流追溯</em></h3>

<p align="center">
  <img src="https://img.shields.io/github/stars/erichuangshuo/reits-research?style=social" alt="Stars">
  <img src="https://img.shields.io/github/license/erichuangshuo/reits-research?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/version-4.0.0-orange?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/Data-2025年报-red?style=flat-square" alt="Data 2025">
  <br>
  <img src="https://img.shields.io/badge/兼容-Claude%20Code-blue?style=flat-square" alt="Claude Code">
  <img src="https://img.shields.io/badge/兼容-OpenClaw-purple?style=flat-square" alt="OpenClaw">
  <img src="https://img.shields.io/badge/兼容-Hermes-darkgreen?style=flat-square" alt="Hermes">
  <img src="https://img.shields.io/badge/兼容-Codex-gray?style=flat-square" alt="Codex">
  <img src="https://img.shields.io/badge/兼容-任意AI%20Agent-lightgrey?style=flat-square" alt="AI Agent">
</p>

---

## 🔥 如果你正在看这个项目，大概率你遇到了这些问题

> "7只REITs的年报加起来上千页，每次对比数据都要翻到崩溃……"

> "城投宽庭ROI高是因为R4地价便宜，但到底便宜了多少？怎么量化？"

> "想做REITs研究，但不知道从哪下手——资产成本、折旧率、分派率，这么多指标到底怎么串起来？"

> "老板要我出一份行业分析报告，3天时间，能搞定吗？"

> "我想系统学习中国REITs的分析方法，但网上找不到完整的教程……"

**如果上面任何一句话让你点头了——继续往下看。** 👇

---

## ✨ 一句话说清楚

**一套面向中国保租房公募REITs的系统研究方法论——从年报数据提取、资产成本拆解、土地折价量化，到ROI杜邦分解、现金流追溯、经济学归因，全流程覆盖。**

支持 **Claude Code · OpenClaw · Hermes · Codex** 等所有支持 Skill/Markdown 格式的 AI Agent 平台。

---

## 🎯 它不是一个"帮你跑数据"的工具，它是一套"研究思维"

你拿到的不只是一份报告——你拿到的是：

| 你会获得的 | 具体是什么 |
|------|------|
| 🔬 **一份数据提取清单** | 8项必获取的定量数据 + 每项在年报中的位置 |
| 📐 **一套量化方法** | 折价率、折旧率、压缩倍数——把"直觉"变成"数字" |
| 💰 **一个归因框架** | ROI=EBITDA率×周转率——分清"运营问题"还是"资产问题" |
| 🌍 **一种分层逻辑** | 不动产的地域属性——上海同城首选，全国异地参照 |
| 🎓 **一个学术视角** | 地租理论+委托代理+规模经济——让你的分析上深度 |

---

## 👥 谁在用 / 谁能用？

### 🏢 按角色

| 角色 | 使用场景 |
|------|------|
| 📊 **REITs分析师 / 研究员** | 快速完成7只REITs横向对标，量化行业定位 |
| 💰 **基金经理 / 投资人** | 评估投资标的，识别被低估或高估的资产 |
| 🏗️ **开发商 / 运营商** | 将自有品牌与上市REITs进行横向经营对标 |
| 🏛️ **保障房运营机构** | 评估旗下保租房资产的运营效率和资本回报 |
| 🎓 **金融/地产专业学生** | 系统学习中国公募REITs的完整分析体系 |
| 💼 **咨询顾问 / 审计师** | 为客户提供有数据支撑的行业洞察报告 |
| 🏢 **政府/行业协会** | 了解保租房REITs市场的整体运营状况 |

### 🏠 按应用场景

| 场景 | 如何使用 |
|------|------|
| **REITs持有者** | 评估持仓REITs的ROI驱动因素——是靠运营还是靠政策红利？ |
| **REITs经营者** | 对标同业，识别自身在行业中的效率位置，找到改进方向 |
| **REITs投资者** | 筛选标的：哪些REITs的ROI有持续性？哪些依赖一次性红利？ |
| **保租房行业研究** | 了解保障性租赁住房REITs的整体市场格局和趋势 |
| **资产证券化咨询** | 为拟发行REITs的资产包提供估值参照和效率基准 |

---

## ⚡ 3步快速开始

### 第1步：安装

```bash
# Claude Code
npx skills add erichuangshuo/reits-research

# OpenClaw / Hermes / Codex — 直接使用 SKILL.md
# 将本仓库的 SKILL.md 放入你的 Agent skills 目录即可
```

### 第2步：使用

在 AI Agent 中输入任意一句：

```
"帮我分析当前保租房REITs市场情况"
"对比7只REITs的ROI和现金流分派率"
"为什么华润有巢的净利润ROI只有0.97%？深度分析"
"给我一份完整的REITs深度研究报告"
```

### 第3步：获得结果

Agent 自动联网搜索最新年报 → 提取数据 → 按方法论框架 → 输出完整分析 🚀

---

## 📖 完整分析框架

```yaml
Step 0: 时效性检查
  - 判断当前可获取的最新报告（年报/季报/半年报）
  - 联网搜索最新市场地价基准

Step 1: 资产成本拆解
  - 土地成本 + 建安成本分项，精确到招股书页码
  - 土地折价率 = 项目地价 ÷ 同区域商品住宅市场楼面价

Step 2: ROI 杜邦分解
  - ROI = EBITDA ÷ 资产成本
  - ROI = EBITDA率(运营) × 资产周转率(成本)
  - 同一ROI→不同路径→精准归因

Step 3: 现金流追溯
  - 净利润 → +折旧摊销 → -资本性支出 = 可供分配金额
  - 折旧率 × 资产成本 → 量化"多出来的钱从哪来"

Step 4: 地域分层对标
  - 上海同城（首选）→ 全国异地（参照）
  - 不动产的地域属性不可忽视

Step 5: 综合论述
  - 金融层面：资本结构、经营杠杆、估值参考
  - 经营层面：规模经济、收入质量、成本改善
  - 经济学视角：地租理论、委托代理、规模经济
```

---

## 📊 覆盖的7只REITs（以2025年年报为基准）

| 品牌 | 代码 | 区域 | 底层项目数 | 上市时间 | 拿地方式 |
|------|------|:---:|:---:|------|------|
| 城投宽庭 | 508031 | 上海杨浦 | 2 | 2023.12 | R4协议出让 |
| 华润有巢 | 508077 | 上海松江/闵行 | 3 | 2022.12 | 招拍挂租赁 |
| 上海城方 | 508055 | 上海闵行 | 2 | 2025.03 | R4+商改保 |
| 恒泰租住 | 508085 | 苏州工业园 | 1 | 2025.05 | 协议出让(2010) |
| 中金厦门安居 | 508058 | 厦门集美 | 2 | 2022.08 | 招拍挂 |
| 红土深圳安居 | 180401 | 深圳四区 | 4 | 2022.08 | 混合划拨 |
| 北京保障房中心 | 508068 | 北京六区 | 6 | 2022.08 | 划拨地 |

> 💡 覆盖2025年中国全部已上市的保障性租赁住房公募REITs。

---

## 🛠️ 多平台兼容

| 平台 | 使用方式 |
|------|------|
| **Claude Code** | `npx skills add erichuangshuo/reits-research` |
| **OpenClaw** | 将 `SKILL.md` 放入 `~/.openclaw/skills/` |
| **Hermes** | 将 `SKILL.md` 放入 skills 目录 |
| **Codex** | 直接导入 `SKILL.md` 作为系统提示词 |
| **任意 AI Agent** | `SKILL.md` 为标准 Markdown 格式，任何支持 Skill 的系统均可使用 |

> 💡 **核心文件只有 `SKILL.md`** — 一份标准的 Markdown 文档，不依赖任何特定平台。只要你的 AI Agent 支持 Skill/知识库注入，就能用。

---

## 📁 项目结构

```
reits-research/
├── README.md          ← 你在这里
├── SKILL.md           ← 核心方法论（v4.0，2400+行）
├── skill.json         ← Claude Code 插件配置
└── LICENSE            ← MIT
```

---

## ❓ 常见问题

<details>
<summary><b>Q: 数据靠谱吗？来源是什么？</b></summary>
每个数字标注了精确来源：年报页码、招股书页码、交易所公告。Skill运行时联网搜索最新披露数据，不固化静态数字。框架永恒，数据动态。
</details>

<details>
<summary><b>Q: 为什么用EBITDA而不是净利润？</b></summary>
不同REITs的折旧政策差异巨大（年折旧率1.35-4.18%），净利润口径不可比。统一用EBITDA（都不考虑折旧）才能公平横向对标。
</details>

<details>
<summary><b>Q: 我是新手，能看懂吗？</b></summary>
SKILL.md第一部分就是"核心指标定义与计算方法论"，从ROI、折旧率到压缩倍数，每个概念都有公式+说明。从头到尾读一遍，你就能掌握REITs分析的基本框架。
</details>

<details>
<summary><b>Q: 怎么更新到最新数据？</b></summary>
Skill内置时间敏感逻辑——运行时会自动判断当前可获取的最新报告（4月年报/8月半年报/10月季报），联网搜索最新市场地价。你不需要手动更新任何数据。
</details>

<details>
<summary><b>Q: 能用于投资决策吗？</b></summary>
提供分析框架和方法论，不构成投资建议。数据请自行核实，投资前咨询专业顾问。
</details>

---

## 🌟 如果觉得有用

- ⭐ **Star** 这个项目 — 让更多REITs从业者发现它
- 🍴 **Fork** 并适配到你自己的分析场景
- 💬 **提 Issue** 分享使用体验或改进建议
- 📢 **分享** 给做REITs研究/投资的同事朋友

<p align="center">
  <b>📌 建议收藏 · 💬 欢迎交流 · ⭐ 随手点赞 · 🔄 转发给需要的人</b>
</p>

---

## 📜 License

MIT © [erichuangshuo](https://github.com/erichuangshuo)

<p align="center">
  <sub>Built with ❤️ and AI · 2026 · 让REITs研究更简单</sub>
</p>
