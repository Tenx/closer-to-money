# closer-to-money

A Claude Code skill that diagnoses the fastest path to revenue for any business, product, or side project. YC-advisor style: direct verdict, no fluff.

## What it does

Given a product description or project context, it:

1. Classifies the business vertical (SaaS, content, ecommerce, consulting, side project) and revenue stage (pre-revenue / zero-to-one / stalled)
2. Identifies the single most critical blocker from a library of 10 blocker types
3. Recommends one revenue model from a library of 12, with fit conditions checked against your specific situation
4. Outputs a concrete action plan — specific enough to execute today, not "talk to customers"

## Trigger phrases

```
/closer-to-money
怎么变现
找商业模式
第一个付费用户
收入上不去
怎么找客户
没有收入
```

## Usage

**Inside a project directory** — the skill silently reads README, package.json, docs, and any context files. No input needed.

**Outside a project** — it asks one question: describe your product and current revenue state in 2–3 sentences.

## Example output

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

## File structure

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

## Reference libraries

### Revenue models (`references/revenue-models.md`)

12 models with fit conditions, anti-patterns, reference companies, and cold-start paths:

| # | Model | Best for |
|---|-------|----------|
| 1 | SaaS Subscription | Recurring software problems |
| 2 | Usage-Based | Value scales with usage |
| 3 | One-Time Purchase | Finite deliverables, templates |
| 4 | Done-For-You | Expert services, fixed scope |
| 5 | Marketplace | Connecting buyers and sellers |
| 6 | Lead Generation | Niche audience with commercial intent |
| 7 | Freemium → Paid | Viral/SEO distribution with clear upgrade triggers |
| 8 | Community / Membership | Existing audience > 500 engaged |
| 9 | Sponsorships | Niche content, 5K+ audience |
| 10 | White Label / Licensing | B2B tech embedding |
| 11 | Consulting / Advisory | Rare expertise, episodic need |
| 12 | Data / API as Product | Proprietary data, developer buyers |

### Blocker types (`references/blockers.md`)

10 blocker types with diagnostic signals and specific unlock actions:

| Code | Blocker | Signal |
|------|---------|--------|
| B1 | Pricing Fog | No price on site, "we'll see" |
| B2 | Wrong Buyer | Free users love it, no one pays |
| B3 | No Urgency | "Interesting, I'll check later" |
| B4 | No Distribution | Zero traffic outside friends/family |
| B5 | Solution-First | Built features, no customer validation |
| B6 | Trust Deficit | "How big is your company?" |
| B7 | Feature Completeness Trap | "Almost ready to launch" for 3+ months |
| B8 | Price Too Low | Customers treat product as disposable |
| B9 | Wrong Stage for Model | Freemium with no distribution |
| B10 | Conversion Gap | Traffic fine, trial-to-paid < 1% |

### First customer playbook (`references/first-customer-playbook.md`)

Vertical-specific 0→1 acquisition guides for: SaaS/dev tools, content/newsletter/course, ecommerce, consulting/freelance, and indie/side projects. Includes outreach scripts, pricing guidance, and common mistakes to avoid.

## License

MIT
