# 事实与数据来源 / Facts & Sources

> 本文件支撑公开信中的关键论断。所有数据均可被独立复核。如发现错误或更新，请通过 PR 修订。
> This appendix backs every quantitative claim in the letter. All figures are independently verifiable. Corrections and updates welcome via PR.

---

## 1. 价格负担对比 / Price burden comparison

**主张 / Claim**：USD 20/月的前沿订阅，在美国约占中位月收入 0.4%，在印度约 7–10%，在尼日利亚 >15%。

| 国家 / Country | 中位月收入 (USD) · Median monthly income | USD 20 占比 · As share | 来源 · Source |
|---|---|---|---|
| United States | ~5,000 | ~0.4% | US Census Bureau · Current Population Survey |
| India | ~250 | ~8% | World Inequality Database · India 2023 |
| Nigeria | ~120 | ~17% | National Bureau of Statistics Nigeria · 2023 |
| Indonesia | ~330 | ~6% | BPS Statistics Indonesia · 2023 |
| Brazil | ~520 | ~3.8% | IBGE PNAD Continua · 2023 |

> 待补充：在 PR 中协助补全更多国家、引用具体报告页码。

---

## 2. 世界银行收入分组 / World Bank income classification

**主张 / Claim**：以 GNI 人均 USD 4,500 作为"中低收入国家"阈值。

- 来源：World Bank, *World Bank Country and Lending Groups*, FY2025 thresholds.
  - Low income: ≤ USD 1,145
  - Lower-middle income: USD 1,146 – 4,515
  - Upper-middle income: USD 4,516 – 14,005
  - High income: > USD 14,005

公开信中使用的 **USD 4,500** 是 lower-middle-income 上限的近似取整。

---

## 3. 其他行业的 PPP 定价先例 / PPP pricing precedents

| 行业 / Industry | 案例 / Example | 备注 / Note |
|---|---|---|
| Streaming | Netflix India ~USD 2 vs US ~USD 15 | ~7× lower |
| Music | Spotify India ~USD 1.5 vs US ~USD 11 | ~7× lower |
| Software | Microsoft 365 Family in lower-income markets discounted 30–50% | varies |
| Software | JetBrains: free for students/teachers worldwide | identity-based, not geo |
| Pharma | HIV ARV via PPP/generic licensing: from ~USD 10,000/yr (2000) to ~USD 75/yr (2010s) | landmark global-health precedent |
| Education | Coursera Financial Aid: full subsidy in low-income contexts | application-based |

待补充：电商（Steam regional pricing）、Adobe、YouTube Premium 各市场具体价格。

---

## 4. 前沿模型能力代差 / Capability gap between frontier and prior generations

**主张 / Claim**：前沿模型与上一代在编程、研究、推理任务上的差距已从"略好"扩大到"另一档"。

支撑材料候选（待 Working Group · Watch 补充与版本对齐）：

- SWE-bench Verified：前沿模型与上一代模型解题率差距（quote latest published numbers）。
- GPQA Diamond：前沿模型逼近 expert 水平，上一代远低于。
- ARC-AGI、AIME 等推理基准上的代际跳跃。

---

## 5. 地域封锁现状 / Geographic restrictions snapshot

待 Working Group · Access 在 2026-Q3 发布的 *Global AI Access Barrier Map v0.1* 中系统化呈现。粗略已知：

- OpenAI/Anthropic 等的服务条款列出明确禁用国家清单（受制裁国家及部分国家）；
- 大量国家虽不在禁用清单内，但因支付/电话验证不支持而事实上无法注册；
- 部分服务对企业账户开放，对个人账户区域关闭。

具体表格待 Access 工作组在 2026-Q3 发布的 *Global AI Access Barrier Map v0.1* 中提供。

---

## 6. "为全人类受益"的使命宣言 / "For the benefit of humanity" mission statements

**主张 / Claim**：多家前沿实验室在创立文件中写入"为全人类受益"类表述。

- OpenAI Charter (2018): "ensure that artificial general intelligence (AGI) … benefits all of humanity."
- Anthropic mission statement: "research and develop AI systems that are safe and beneficial."
- DeepMind mission: "solve intelligence … to benefit humanity."
- xAI mission: "understand the universe."

公开信引用此类宣言，仅作为公开记录在案的自我承诺，不就其执行情况下定论。

---

## 7. 修订与争议 / Revisions & disputes

任何数据如有出入，请：

1. 在本仓库 Issue 区开"数据更正"议题（使用 *Proposal* 模板，类型选 *Risk report*）；
2. 提供原始来源链接 / 页码；
3. 通过 PR 修订本文件，并保留旧值的删除记录（diff 即记录）。

我们更愿意公开承认一个数字算错了，也不愿在错的数字上构建论证。
