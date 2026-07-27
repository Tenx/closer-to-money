<div align="center">

# 💰 closer-to-money

**YC-style revenue advisor, built as a Claude Code skill.**
Drop it into any project. Get a verdict in seconds. No fluff, no encouragement, no alternatives.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://github.com/anthropics/claude-code)
[![Language](https://img.shields.io/badge/language-EN%20%7C%20ZH-blue)](#)

**[English](#english) · [中文](#中文)**

</div>

---

<a name="english"></a>

## 🇺🇸 English

### What it does

`closer-to-money` reads your project context and delivers a revenue diagnosis — no questions asked, no hedging. It classifies your business vertical and stage, identifies your single biggest blocker, picks one revenue model, and gives you a concrete action plan to execute this week.

Think of it as a YC office hours session that starts immediately.

### Trigger phrases

```
/closer-to-money
```

Or naturally in conversation:
> "怎么变现" · "找商业模式" · "第一个付费用户" · "收入上不去" · "怎么找客户" · "没有收入"

### Usage

**Inside a project directory** — the skill silently reads README, `package.json`, docs, ADRs, and any context files. No input required.

**Without project context** — it asks one question, then proceeds immediately:
> *Describe your product and current revenue state in 2–3 sentences (no revenue yet / have users but no paying customers / revenue stuck).*

### Example output

```
## 诊断结论

**业务类型：** saas · **阶段：** zero-to-one

---

### 核心卡点

> B5 产品找问题 — 产品已有用户但无人付费，原因是从未明确定义"谁的预算批这笔钱"。

---

### 推荐收入模式

**Done-For-You / 固定价服务包**

| 维度 | 说明 |
|------|------|
| 适合你的原因 | 你有技术但没有销售渠道。服务包让你先收钱、后产品化，同时积累真实客户案例。 |
| 参考公司 | Design Joy — $4,995/mo 无限设计请求，Ryan 独立运营。先做服务，再卖工具。 |
| 反面警示 | 如果你不愿意做手动交付的脏活，这个模式会失败。 |

---

### 本周行动计划

**Day 1**
→ 写一条 LinkedIn 帖子：「我帮 [目标行业] 公司做 [具体交付物]，固定价 ¥X，7 天交付。
  前 3 名客户半价。私信我。」

**Day 2–5**
→ 直接 DM 20 个 Title 含 "Operations" 或 "Growth" 的目标公司联系人，发同一句话。
```

### Reference libraries

<details>
<summary>📊 12 Revenue Models</summary>

| # | Model | Best for |
|---|-------|----------|
| 1 | SaaS Subscription | Recurring software problems |
| 2 | Usage-Based | Value scales with usage |
| 3 | One-Time Purchase | Finite deliverables, templates |
| 4 | Done-For-You | Expert services, fixed scope |
| 5 | Marketplace | Connecting buyers and sellers |
| 6 | Lead Generation | Niche audience with commercial intent |
| 7 | Freemium → Paid | Viral/SEO distribution + clear upgrade triggers |
| 8 | Community / Membership | Existing audience > 500 engaged |
| 9 | Sponsorships | Niche content, 5K+ audience |
| 10 | White Label / Licensing | B2B tech embedding |
| 11 | Consulting / Advisory | Rare expertise, episodic need |
| 12 | Data / API as Product | Proprietary data, developer buyers |

</details>

<details>
<summary>🚧 10 Blocker Types</summary>

| Code | Blocker | Key Signal |
|------|---------|------------|
| B1 | Pricing Fog | No price on site, "we'll see" |
| B2 | Wrong Buyer | Free users love it, no one pays |
| B3 | No Urgency | "Interesting, I'll check later" |
| B4 | No Distribution | Zero traffic outside friends/family |
| B5 | Solution-First | Built features, no customer validation |
| B6 | Trust Deficit | "How big is your company?" |
| B7 | Feature Completeness Trap | "Almost ready" for 3+ months |
| B8 | Price Too Low | Customers treat product as disposable |
| B9 | Wrong Stage for Model | Freemium with no distribution |
| B10 | Conversion Gap | Traffic fine, trial-to-paid < 1% |

</details>

<details>
<summary>🗺️ First Customer Playbooks</summary>

Vertical-specific 0→1 acquisition guides with outreach scripts, pricing guidance, and common mistakes to avoid:

- **SaaS / Dev Tools** — LinkedIn + Twitter search, DM with setup offer
- **Content / Newsletter / Course** — 1-1-1 launch, sell outline before building
- **Ecommerce** — Community posting, first-sale photos for reviews
- **Consulting / Freelance** — 20-person warm list, verbal confirm before proposal
- **Indie / Side Project** — Product Hunt, HN Show HN, community pre-warm

</details>

### File structure

```
closer-to-money/
├── SKILL.md                           # Skill definition and workflow
├── README.md                          # This file
├── references/
│   ├── revenue-models.md              # 12 revenue model profiles
│   ├── blockers.md                    # 10 blocker types with unlock actions
│   └── first-customer-playbook.md     # 0→1 acquisition playbook by vertical
└── templates/
    └── verdict.template.md            # Structured output format
```

### License

MIT

---

<a name="中文"></a>

## 🇨🇳 中文

### 这是什么

`closer-to-money` 是一个 Claude Code Skill，风格类似 YC 的 office hours：读取你的项目上下文，直接输出变现诊断结论，不问多余问题，不给模糊建议，不列备选方案。

它会自动判断你的业务垂直方向和当前阶段，找出最关键的卡点，推荐一个最适合你现在的收入模式，并给出本周可以立刻执行的行动计划。

### 触发方式

```
/closer-to-money
```

或在对话中自然触发：
> "怎么变现" · "找商业模式" · "第一个付费用户" · "收入上不去" · "怎么找客户" · "没有收入"

### 使用方法

**在项目目录内运行** — Skill 会自动静默读取 README、`package.json`、文档、ADR 等上下文文件，无需额外输入。

**无项目上下文时** — 只问一个问题，然后直接出结论：
> *用 2–3 句话描述你的产品和目前的收入状态（还没有收入 / 有用户但没有付费 / 有付费但增长卡住了）。*

### 输出示例

```
## 诊断结论

**业务类型：** sideproject · **阶段：** pre-revenue

---

### 核心卡点

> B4 没有分发渠道 — 产品上线了但流量只来自朋友圈，目标买家从未看到过它。

---

### 推荐收入模式

**一次性买断**

| 维度 | 说明 |
|------|------|
| 适合你的原因 | 你做的是独立工具，功能边界清晰，用户一次性获得完整价值，不依赖持续更新。买断模式启动成本最低，今天就能上线收款。 |
| 参考公司 | Gumroad 上的独立开发者模板、插件、主题；Sketch 在 Adobe 订阅制大行其道时以 $99 买断抢占市场。 |
| 反面警示 | 如果产品需要持续托管或重度客服支持，买断模式会让你赔钱。 |

---

### 本周行动计划

**今天**
→ 在 Gumroad 上架，定价 ¥69，写一段 100 字的产品描述，重点写"解决什么问题"不是"有什么功能"。

**Day 2–5**
→ 找 3 个目标用户聚集的社群（微信群/即刻/小红书），发帖："我做了个工具，解决了 [问题]，¥69，买断。"
  监控 48 小时，逐一回复每条评论。
```

### 参考知识库

<details>
<summary>📊 12 种收入模式</summary>

| # | 模式 | 适合场景 |
|---|------|---------|
| 1 | SaaS 订阅 | 问题每月反复出现 |
| 2 | 按量计费 | 价值随用量扩展 |
| 3 | 一次性买断 | 有限交付物、模板工具 |
| 4 | 固定价服务包 | 专业服务、有限范围 |
| 5 | 平台抽佣 | 连接买家与卖家 |
| 6 | 卖线索 | 有商业意图的垂直受众 |
| 7 | 免费增值 | 有自然流量 + 清晰升级触发点 |
| 8 | 社群会员 | 已有 500+ 活跃关注者 |
| 9 | 广告赞助 | 垂直内容，5000+ 受众 |
| 10 | 白牌授权 | 给其他 B2B 产品嵌入 |
| 11 | 顾问咨询 | 稀缺专业知识，按需付费 |
| 12 | 数据/API 变现 | 独家数据，开发者买家 |

</details>

<details>
<summary>🚧 10 类变现卡点</summary>

| 编号 | 卡点 | 核心信号 |
|------|------|---------|
| B1 | 定价混乱 | 网站没有价格，"看情况定" |
| B2 | 目标客户错误 | 免费用户喜欢，没人付钱 |
| B3 | 没有紧迫感 | "有意思，改天看看" |
| B4 | 找不到客户 | 流量全来自朋友和家人 |
| B5 | 产品找问题 | 先做功能，后找买家 |
| B6 | 信任不足 | "你们公司多大？" |
| B7 | 等功能再卖 | "再做几个功能就去找客户"持续 3 个月 |
| B8 | 定价太低 | 客户把产品当消耗品 |
| B9 | 模式与阶段不匹配 | 没有分发就做免费增值 |
| B10 | 有流量没转化 | 试用转付费 < 1% |

</details>

<details>
<summary>🗺️ 首个客户获取剧本</summary>

按垂直方向分类的 0→1 获客指南，包含外联话术、定价建议、常见错误：

- **SaaS / 开发工具** — LinkedIn + Twitter 搜索，DM 提供免费安装
- **内容 / 知识付费 / 课程** — 1-1-1 冷启动，先卖大纲再做内容
- **电商** — 社群发帖，用首批买家评价建立信任
- **咨询 / 自由职业** — 20 人熟人名单，口头确认后再写方案
- **独立应用 / 副业工具** — Product Hunt、即刻、小红书垂直社群预热

</details>

### 文件结构

```
closer-to-money/
├── SKILL.md                           # Skill 定义与工作流
├── README.md                          # 本文件
├── references/
│   ├── revenue-models.md              # 12 种收入模式详情
│   ├── blockers.md                    # 10 类卡点与解锁动作
│   └── first-customer-playbook.md     # 按垂直分类的首客获取剧本
└── templates/
    └── verdict.template.md            # 结构化输出模板
```

### 开源协议

MIT

---

<div align="center">

Made with 💰 by [Teng](https://github.com/Tenx) · Powered by [Claude Code](https://github.com/anthropics/claude-code)

</div>
