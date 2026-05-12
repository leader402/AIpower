# 如何加入与贡献 / How to Join & Contribute

> AIpower 完全运行在 GitHub 上。加入即"提交一个 Pull Request"。
> AIpower runs entirely on GitHub. Joining means "open a Pull Request."

---

## 中文

### 一、四级成员，按你愿意投入的程度

| 级别 | 你需要做什么 | 你将获得 |
|---|---|---|
| **Tier 0 · 支持者 Supporter** | Star 本仓库；Watch 公告 | 第一时间看到最新行动 |
| **Tier 1 · 贡献者 Contributor** | 提交 1 个有效 Issue 或 PR（翻译、文档修订、议题讨论都算） | 可在工作组发言 |
| **Tier 2 · 正式成员 Member** | 完成下方"入会 PR" | 投票权、被选举权 |
| **Tier 3 · 维护者 Maintainer** | 持续贡献 6 个月以上 + 指导委员会提名 | 仓库写入权限 |

### 二、加入步骤（Tier 2 · 正式成员）

下面这套流程，是 AIpower 唯一的入会方式。**全程公开、可审计、不收钱。**

#### 步骤 1：阅读三份文件
- [README.md](README.md)
- [MANIFESTO.md](MANIFESTO.md)
- [CHARTER.md](CHARTER.md)

#### 步骤 2：Fork 本仓库

```bash
# 在 GitHub 网页点 Fork，然后：
git clone https://github.com/<你的用户名>/AIpower.git
cd AIpower
git checkout -b join/<你的用户名>
```

#### 步骤 3：把自己加进 [MEMBERS.md](MEMBERS.md)

在 `MEMBERS.md` 的 *Pending Applications* 表里追加一行：

```markdown
| @你的GitHubID | 显示名 | 国家/地区 | 想加入的工作组 | 申请日期 |
```

#### 步骤 4：在仓库根目录写下你的"承诺书"

新建文件 `pledges/<你的GitHubID>.md`，内容模板：

```markdown
# Membership Pledge / 入会承诺

I, @<your-github-id>, voluntarily apply to become a Member of AIpower.

I have read MANIFESTO.md and CHARTER.md. I agree to:
- uphold the five core principles;
- abide by the Code of Conduct;
- recuse myself when conflicts of interest arise.

我自愿申请成为 AIpower 正式成员。我已阅读《宣言》与《章程》，承诺：
- 遵守五项基本原则；
- 遵守《行为准则》；
- 在出现利益冲突时主动回避。

Signed: <your real or stable pseudonym>
Date: YYYY-MM-DD
```

#### 步骤 5：提交 PR

```bash
git add MEMBERS.md pledges/<你的GitHubID>.md
git commit -s -m "join: <你的GitHubID> applies for membership"
git push origin join/<你的GitHubID>
```

然后在 GitHub 上开 Pull Request，标题为 `join: <你的GitHubID> applies for membership`。

> **`-s` 是必须的**：表示你以 [DCO（Developer Certificate of Origin）](https://developercertificate.org/) 形式签署提交。这是我们目前唯一的"身份签署"机制，足够轻量，又能留下可审计的链路。

#### 步骤 6：等待审核（≤ 14 天）

- 秘书处会在 14 天内审查：你是否同一账号在多个组织有恶意活动、是否填写完整。
- 任何现有 Member 可在 PR 下提出反对，反对需说明具体理由（不接受身份偏见类反对）。
- PR 在以下情况通过：
  - 无任何 Member 提出实质性反对；**或**
  - 反对存在但被 2/3 现有 Member 投票否决。
- 合并 PR 即成为正式成员。

### 三、其他贡献方式（不需要先入会）

- **翻译**：把任意文件翻译为第三种语言，提交 PR 到 `i18n/<lang>/`
- **议题报告**：发现 AI 垄断风险、地区封锁案例，开一个 Issue（使用"议题/Proposal"模板）
- **代码**：未来工作组会发布工具仓库（如低价 API 路由、镜像保护、开源模型评测），届时欢迎 PR
- **资金支持**：在 [ROADMAP.md](ROADMAP.md) 找到"Fund-a-Mile"清单，资助一项具体行动
- **传播**：把本仓库分享给你身边因为价格/地域用不上先进 AI 的人

### 四、需要避免的事

- **不要** 在 PR 里附加 AI 公司的推广链接、邀请码、推荐返利码。
- **不要** 替别人签承诺书；每个 GitHub ID 自己开 PR。
- **不要** 用一次性匿名账号申请（注册不足 30 天的账号将被自动暂缓）。
- **不要** 把组织活动转成针对某个具体个人的攻击。

详见 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。

---

## English

### 1. Four tiers, by how much you want to put in

| Tier | What you do | What you get |
|---|---|---|
| **Tier 0 · Supporter** | Star this repo; Watch for announcements | First-look at every action |
| **Tier 1 · Contributor** | Submit at least one valid Issue or PR (translation, doc edit, discussion all count) | Voice in working groups |
| **Tier 2 · Member** | Complete the *Membership PR* below | Voting rights, eligible for office |
| **Tier 3 · Maintainer** | 6+ months of contribution + Council nomination | Repo write access |

### 2. How to join (Tier 2 · Member)

This is the **only** way to become a member. It is **public, auditable, and free**.

#### Step 1. Read three documents
- [README.md](README.md)
- [MANIFESTO.md](MANIFESTO.md)
- [CHARTER.md](CHARTER.md)

#### Step 2. Fork this repository

```bash
# Fork on GitHub, then:
git clone https://github.com/<your-username>/AIpower.git
cd AIpower
git checkout -b join/<your-username>
```

#### Step 3. Add yourself to [MEMBERS.md](MEMBERS.md)

Append one row to the *Pending Applications* table:

```markdown
| @your-github-id | Display Name | Country/Region | Working Group(s) | Application Date |
```

#### Step 4. Write your pledge

Create `pledges/<your-github-id>.md` using the template in step 4 of the Chinese section above (the file content is bilingual).

#### Step 5. Open the Pull Request

```bash
git add MEMBERS.md pledges/<your-github-id>.md
git commit -s -m "join: <your-github-id> applies for membership"
git push origin join/<your-github-id>
```

Open a PR titled `join: <your-github-id> applies for membership`.

> The `-s` flag is **required** — it signs your commit under the [Developer Certificate of Origin](https://developercertificate.org/). It is the lightest auditable identity mechanism we use.

#### Step 6. Review (≤ 14 days)

- The Secretariat checks for completeness and obvious bad-faith signals within 14 days.
- Any existing Member may raise a substantive objection on the PR. Identity-based objections are not accepted.
- The PR passes if:
  - no Member raises a substantive objection; **or**
  - existing objections are overruled by a **two-thirds** member vote.
- Merge = membership granted.

### 3. Other ways to contribute (no membership required)

- **Translate** any document into a third language; PR into `i18n/<lang>/`.
- **Report** AI monopoly risks or regional access blocks via an Issue (use the *Proposal* template).
- **Code** — future working groups will publish tool repos (low-cost API routers, mirror preservation, open-model evals); PRs welcome.
- **Fund** a specific action listed in [ROADMAP.md](ROADMAP.md) under *Fund-a-Mile*.
- **Spread** — share this repo with people who can't use frontier AI because of price or geography.

### 4. What to avoid

- Do **not** attach promotional links, referral codes, or affiliate IDs of AI companies in PRs.
- Do **not** sign pledges on behalf of others. One PR per GitHub ID, by that ID.
- Do **not** apply using throwaway accounts (accounts younger than 30 days are auto-deferred).
- Do **not** turn organizational debate into attacks on specific individuals.

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
