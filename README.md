# 🏢 中国保障性租赁住房公募REITs 深度研究方法论

> **China Affordable Housing Public REITs — Complete Research Framework**

[![Stars](https://img.shields.io/badge/⭐-Give%20a%20Star-brightgreen)](https://github.com/erichuangshuo/reits-research)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)
[![Version](https://img.shields.io/badge/version-4.0.0-orange)](.)
[![Data](https://img.shields.io/badge/Data-2025%20Annual%20Reports-red)](.)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)

---

## 📊 一句话说清楚

**一套方法论，让你在 5 分钟内完成 7 只保租房 REITs 的完整横向对标分析——从资产成本拆解、土地折价量化，到 ROI 杜邦分解、现金流来源追溯。**

---

## 🔥 为什么你需要这个 Skill？

如果你正在做以下任何一件事：

- 📈 研究中国公募 REITs，但不知道从哪里下手
- 🏠 分析保租房资产，需要一套系统的估值框架
- 📊 做行业横向对标，想要有据可查的数据来源
- 💼 撰写研报，需要专业的论证结构和经济学视角
- 🎓 学习 REITs 分析，想看一个完整的实战案例

**这个 Skill 就是为你准备的。**

---

## 📸 产出预览

运行这个 Skill，你会得到一份**包含以下所有维度的完整研报**：

| 分析维度 | 产出内容 |
|---------|---------|
| 🔬 资产成本 | 7只REITs的土地成本+建安成本分项，精确到招股书页码 |
| 📐 土地折价 | 每项目地价 vs 同区域商品住宅市场楼面价 → 量化折让程度 |
| 💰 ROI分析 | 统一EBITDA口径 + 杜邦分解（EBITDA率 × 资产周转率） |
| 💸 现金流 | 净利润→折旧加回→可供分配金额的完整链路 |
| 🏗️ 折旧拆解 | 每只REIT的折旧率 + 压缩倍数 + 现金流转化率 |
| 🌍 地域分层 | 上海REITs（同城首选）→ 全国REITs（异地参照） |
| 📈 项目级对标 | 23个底层项目逐一定量对比 + 成本vs运营贡献度归因 |

---

## 🚀 快速开始

### 安装

```bash
# 方式一：Claude Code 内置安装
/plugin marketplace add erichuangshuo/reits-research

# 方式二：npx 安装
npx skills add erichuangshuo/reits-research

# 方式三：手动克隆
git clone https://github.com/erichuangshuo/reits-research.git
cp reits-research/SKILL.md ~/.claude/skills/reits-research/
```

### 使用

```
在 Claude Code 中说：
"帮我分析当前的保租房REITs市场情况"
"对比7只REITs的ROI和分派率"
"给我一份REITs深度研究报告"
```

---

## 🧠 核心分析框架

### 1. ROI 杜邦分解

```
ROI = EBITDA ÷ 资产成本
    = (EBITDA ÷ 营收) × (营收 ÷ 资产成本)
    = EBITDA率(运营效率) × 资产周转率(成本杠杆)
```

**同一个ROI，路径可能完全不同：**

| | 大华享寓·联2 | 城投·江湾 |
|------|:---:|:---:|
| ROI | 3.16% | 3.15% |
| EBITDA率 | **82.7%** 🏆 | 45.9% |
| 资产周转率 | 3.82% | **6.99%** 🏆 |
| 路径 | 极致运营效率 | 极致成本杠杆 |

### 2. 土地折价量化

```
折价率 = 项目账面地价 ÷ 同区域商品住宅市场楼面价
```

| 拿地方式 | 折价率 | 代表 |
|------|:---:|------|
| 划拨地 | 0.4-2.2折 | 华夏北京 |
| R4协议地 | 0.5-1.7折 | 城投宽庭 |
| 开发商自有地 | 1.8-3.9折 | 大华享寓 |

### 3. 四层分析架构

```
① 品牌主体层 → 大华 vs 7家REIT公司（四维排名）
② 股东分公司层 → 睿华/顾华/华行 杜邦分解
③ 项目层 → 全23标的统一排名（含折价归因）
④ 综合论述 → 金融+经营深度分析 + 经济学视角
```

---

## 📈 真实数据（2025年年报）

### 覆盖的7只REITs

| 品牌 | 代码 | 区域 | 底层项目数 |
|------|------|:---:|:---:|
| 城投宽庭 | 508031 | 上海 | 2 |
| 华润有巢 | 508077 | 上海 | 3 |
| 上海城方 | 508055 | 上海 | 2 |
| 恒泰租住 | 508085 | 苏州 | 1 |
| 中金厦门安居 | 508058 | 厦门 | 2 |
| 红土深圳安居 | 180401 | 深圳 | 4 |
| 北京保障房中心 | 508068 | 北京 | 6 |

### 公司级ROI排名（统一EBITDA口径）

| # | 品牌 | ROI | EBITDA率 | 周转率 |
|:---:|------|:---:|:---:|:---:|
| 1 | 中金厦门安居 | 4.90% | 73.3% | 6.69% |
| 2 | 城投宽庭 | 4.86% | 69.6% | 6.99% |
| 3 | 华润有巢 | 4.25% | 64.0% | 6.65% |
| 4 | 大华享寓 | 2.39% | 77.4% | 3.09% |

---

## 📁 文件结构

```
reits-research/
├── README.md              ← 你在这里
├── LICENSE                ← MIT
├── SKILL.md               ← 核心方法论（v4.0，含完整分析框架）
├── skill.json             ← Claude Code 插件配置
└── examples/
    └── report-sample.md   ← 示例报告输出
```

---

## 🎯 特色

- ✅ **数据溯源到页码**：每个数字标注到年报/招股书的精确页码
- ✅ **时间敏感型**：支持任意时点的动态数据分析（自动判断年报/季报窗口）
- ✅ **联网搜索集成**：内置搜索关键词模板，自动获取最新市场地价
- ✅ **成本vs运营归因**：杜邦分解量化"低ROI是资产贵还是运营差"
- ✅ **经济学视角**：地租理论 + 委托代理理论 + 规模经济的学术级分析
- ✅ **全中文**：面向中国市场的专业研究报告

---

## 🤝 贡献

欢迎提 Issue 和 PR！特别需要：

- 🔧 新增 REITs 的资产成本数据
- 📊 更新最新季报/年报数据
- 🏗️ 优化分析维度或归因逻辑
- 🐛 报告任何数据错误

---

## ⭐ Star History

如果这个项目对你有帮助，请点一个 ⭐ Star！

你的支持是我持续更新的动力。

---

## 📜 License

MIT © [erichuangshuo](https://github.com/erichuangshuo)

---

*Made with ❤️ and Claude Code • 2026*
