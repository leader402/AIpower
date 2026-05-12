# 章程 / Charter

> 本文件是 AIpower 的根本性文件，规定组织的宗旨、原则、结构、决策与修订方式。
> This document is the foundational charter of AIpower: purpose, principles, structure, decisions, and amendments.

---

## 中文

### 第一章 总则

**第 1 条（名称）**
本组织中文名"AI 平权倡议"，英文名"AIpower — AI Equity Initiative"，简称 AIpower。

**第 2 条（性质）**
AIpower 是一个非营利、志愿者驱动、跨国界的公民倡议组织。本组织不是公司、不是党派、不依附于任何政府或商业 AI 实验室。

**第 3 条（宗旨）**
保障普通人在 AI 时代平等地获取、使用、理解、监督先进 AI 的权利。

**第 4 条（语言）**
本组织所有正式文件采用 **中文 + 英文** 双语，两种版本具有同等效力。其他语言译本由社区贡献，仅供参考。

### 第二章 基本原则

1. **普惠（Universal Access）**：任何反对 AI 普惠的设计、政策或商业策略，都是我们要审视的对象。
2. **开放（Openness）**：默认公开、默认开源、默认可审计。
3. **去中心（Decentralization）**：不允许单一节点控制本组织决策、资金或代言权。
4. **透明（Transparency）**：财务、合作、决策全程上链于公开仓库（即本 GitHub 仓库）。
5. **非暴力、非对抗（Non-violence）**：不进行人身攻击、不煽动对立。
6. **行动优先（Action First）**：每一条立场，都应对应一项可被检验的行动。

### 第三章 工作支柱（五大支柱）

| 支柱 | 中文 | English | 典型行动 |
|---|---|---|---|
| Pillar 1 | 倡导 | Advocacy | 政策研究、公开信、立法意见、媒体发声 |
| Pillar 2 | 开放 | Openness | 贡献开源模型、开放数据集、开放评测、镜像保护 |
| Pillar 3 | 教育 | Education | AI 扫盲课程、本地语言教程、面向弱势群体的培训 |
| Pillar 4 | 接入 | Access | 共享订阅、众筹算力、低价 API 计划、IP/支付通道协助 |
| Pillar 5 | 监督 | Watch | 年度《AI 垄断风险报告》、合规观察、举报支持 |

### 第四章 组织结构

AIpower 采用 **轻量级、扁平化、可审计** 结构。

```
                ┌──────────────────────────────┐
                │   全体成员大会 / General Assembly │
                │  （所有 Member 在 GitHub Issue 投票）│
                └──────────────┬───────────────┘
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
 ┌──────▼──────┐       ┌──────▼──────┐       ┌──────▼──────┐
 │  指导委员会  │       │   支柱工作组  │       │   秘书处     │
 │  Council    │       │  Working    │       │  Secretariat│
 │ (5-9 人)   │       │  Groups (5)│       │  (轮值)      │
 └─────────────┘       └─────────────┘       └─────────────┘
```

#### 4.1 全体成员大会 / General Assembly

- 由所有 **正式成员（Member）** 组成。
- 行使最高权力：通过/修订章程，选举指导委员会，弹劾成员。
- 决策形式：公开 GitHub Issue 提案 + 公开投票（至少 7 天讨论期）。

#### 4.2 指导委员会 / Council

- 5–9 名成员，任期 1 年，可连任 1 次。
- 来自不同国家/地区，单一国籍占比不得超过 1/3。
- 职责：日常路线判断、对外发言、紧急情况处置。
- 任何 Council 成员均可被全体成员大会以 2/3 多数罢免。

#### 4.3 支柱工作组 / Working Groups

按五大支柱设立，每组设 1–2 名召集人（Coordinator）。任何成员可加入任意工作组。

#### 4.4 秘书处 / Secretariat

负责仓库维护、文档归档、会议记录、新成员入会审核。轮值产生，每届 6 个月。

### 第五章 成员制度

成员分为四级：

| 级别 | 中文 | English | 资格 | 权利 |
|---|---|---|---|---|
| Tier 0 | 支持者 | Supporter | Star 仓库 / 关注公告 | 阅读、评论 |
| Tier 1 | 贡献者 | Contributor | 提交过 1 次有效 Issue/PR | 提案讨论、加入工作组 |
| Tier 2 | 正式成员 | Member | 通过入会 PR + 签署承诺书 | 投票权、被选举权 |
| Tier 3 | 维护者 | Maintainer | 6 个月持续贡献 + Council 提名 | 仓库写入权限 |

**入会流程见 [CONTRIBUTING.md](CONTRIBUTING.md)。**

### 第六章 资金与利益冲突

- 本组织接受 **个人捐赠、基金会资助、众筹**。
- **不接受** 来自前沿 AI 实验室（即任何被本组织年度报告认定为"前沿模型供应商"的实体）的、附带方向性条件的资金。
- 单笔超过 USD 1000 的捐赠必须在 30 天内公开披露。
- 所有收支记录在仓库 `finance/` 目录下，年度审计。
- 成员若与议题存在利益关联（雇佣、持股、咨询关系等），必须在相关投票前 **声明回避**。

### 第七章 反垄断、反俘获条款

- 任何单一公司、政府或基金会的累计资金占比，不得超过本组织年度总收入的 **20%**。
- 指导委员会成员中，**当期受雇于同一公司的人数不得超过 1 人**。
- 当本组织的立场与某个主要捐赠人的商业利益发生冲突时，**立场优先**；必要时拒绝该笔资金。

### 第八章 章程修订

- 任何正式成员均可在仓库提交 PR 修订本章程。
- PR 必须保留中英文双语版本同步修改。
- 讨论期不少于 14 天。
- 通过条件：全体成员大会 **2/3 多数赞成**，且至少 3 个不同国家/地区的成员投赞成票。

### 第九章 解散

如本组织不再具备运行条件，由全体成员大会以 3/4 多数表决解散。剩余资金须捐赠给同样致力于"开源 AI / AI 普惠"的非营利组织。

---

## English

### Chapter I. General Provisions

**Article 1 (Name).**
The organization is officially named *AIpower — AI Equity Initiative* (中文名："AI 平权倡议"). Short form: AIpower.

**Article 2 (Nature).**
AIpower is a non-profit, volunteer-driven, transnational civic initiative. It is not a company, not a political party, and is not affiliated with any government or commercial AI lab.

**Article 3 (Purpose).**
To safeguard ordinary people's right to equally access, use, understand, and oversee advanced AI in the age of AI.

**Article 4 (Language).**
All formal documents of this organization are issued in **Chinese and English**, both versions carrying equal authority. Translations into other languages are community contributions and are advisory only.

### Chapter II. Core Principles

1. **Universal Access** — any design, policy, or business practice that obstructs equal AI access is subject to our scrutiny.
2. **Openness** — open by default, open-source by default, auditable by default.
3. **Decentralization** — no single node may control the organization's decisions, funding, or public voice.
4. **Transparency** — finances, partnerships, and decisions are committed to a public repository (this GitHub repo).
5. **Non-violence** — no personal attacks, no agitation of conflict.
6. **Action First** — every position must correspond to a verifiable action.

### Chapter III. Five Pillars of Work

| Pillar | Theme | Typical Actions |
|---|---|---|
| 1 | Advocacy | Policy research, open letters, legislative submissions, media |
| 2 | Openness | Open-source model contribution, open datasets, open evals, mirror preservation |
| 3 | Education | AI literacy, local-language tutorials, training for underserved groups |
| 4 | Access | Shared subscriptions, crowdfunded compute, low-cost API programs, payment/IP assistance |
| 5 | Watch | Annual *AI Monopoly Risk Report*, compliance watch, whistleblower support |

### Chapter IV. Organizational Structure

AIpower uses a **lightweight, flat, auditable** structure.

```
                ┌──────────────────────────────┐
                │      General Assembly         │
                │  (all Members vote via Issue) │
                └──────────────┬───────────────┘
                               │
        ┌──────────────────────┼──────────────────────┐
        │                      │                      │
 ┌──────▼──────┐       ┌──────▼──────┐       ┌──────▼──────┐
 │   Council    │      │   Working    │      │ Secretariat │
 │ (5–9 people) │      │   Groups (5) │      │  (rotating) │
 └─────────────┘       └─────────────┘       └─────────────┘
```

#### 4.1 General Assembly

- Composed of all **Members** (Tier 2).
- Holds ultimate authority: ratifies/amends the charter, elects the Council, impeaches members.
- Decision mechanism: public GitHub Issue proposals + public votes, with a minimum 7-day discussion window.

#### 4.2 Council

- 5–9 members, 1-year term, re-electable once.
- Drawn from diverse nationalities; **no more than one-third** may share a single nationality.
- Responsibilities: routine direction-setting, external statements, emergency response.
- Any Council member may be recalled by a **two-thirds** vote of the General Assembly.

#### 4.3 Working Groups

One per pillar, each with 1–2 Coordinators. Any member may join any group.

#### 4.4 Secretariat

Maintains the repository, archives documents, takes minutes, vets new membership applications. Rotates every 6 months.

### Chapter V. Membership

Four tiers:

| Tier | Name | Eligibility | Rights |
|---|---|---|---|
| 0 | Supporter | Star the repo / subscribe to announcements | Read, comment |
| 1 | Contributor | At least one merged Issue/PR | Propose, join working groups |
| 2 | Member | Passing membership PR + signed pledge | Vote, eligible for office |
| 3 | Maintainer | 6 months of contribution + Council nomination | Repo write access |

**See [CONTRIBUTING.md](CONTRIBUTING.md) for the membership process.**

### Chapter VI. Funding & Conflicts of Interest

- The organization accepts **individual donations, foundation grants, and crowdfunding**.
- It does **not** accept funding from any "frontier AI lab" (as identified in the latest annual report) that is conditioned on directional commitments.
- Donations exceeding **USD 1,000** must be publicly disclosed within 30 days.
- All financial records live in `finance/` and are audited annually.
- Members with personal stakes in a topic (employment, equity, advisory) must **recuse** themselves before related votes.

### Chapter VII. Anti-Monopoly & Anti-Capture Clauses

- No single company, government, or foundation may account for more than **20%** of annual revenue.
- No more than **one** sitting Council member may be currently employed by the same company.
- When the organization's position conflicts with the commercial interests of a major donor, **the position takes precedence** — funding will be refused if necessary.

### Chapter VIII. Charter Amendments

- Any Member may submit a PR amending this charter.
- PRs must update Chinese and English versions in sync.
- Discussion period: at least 14 days.
- Passing threshold: **two-thirds** of the General Assembly, with affirmative votes from members of at least **three different countries/regions**.

### Chapter IX. Dissolution

If continued operation is no longer feasible, dissolution requires a **three-quarters** majority vote of the General Assembly. Remaining funds must be donated to other non-profits dedicated to open-source AI or AI equity.
