---
app_name: "Kollab"
date: "2026-05-21"
sector: "AI Agent / AI Native Workspace / 团队协作"
stage: "公测期 / 早期商业化"
status: "active"
对三湘问道的价值: "用于观察 AI Agent 从个人工具进入团队协作后，工作空间、组织记忆、Skill 复用与 IM 入口如何重写协作软件。"
优先级评分: 7
---

# Kollab 轻量初拆

> 文档类型：产品对标轻量初拆  
> 版本：v0.1  
> 生成日期：2026-05-21  
> 生成者：SK-产品对标初拆 GPTS  
> 审核方：Claude / SK 工作台  
> 边界说明：本稿是前哨型初拆，不是标准 10 维深拆，不宣布入库，不替代 Claude / SK 工作台的最终判断。

## 0. 本稿边界

Kollab 是一个面向团队的 AI-native workspace。它把项目、文档、任务、知识库、Bots、Connectors、Skills、Memory 放进同一个协作空间，让 AI Agent 不再只是个人对话框，而是出现在团队项目、IM、任务与产物旁边的执行者。

本稿只做轻量初拆，目标是回答四个问题：

1. Kollab 真正在解什么协作断裂问题。
2. 它的关键机制是不是比「给 Slack / 飞书加一个 AI Bot」更深。
3. 对中国市场而言，应该直接复制、工具使用、代理分发，还是继续观察。
4. 哪些证据不足，必须交给深度研究员补齐。

本稿不做以下动作：

1. 不判断 Kollab 已经商业成功。
2. 不把官方表述当作市场验证。
3. 不写公众号终稿。
4. 不宣布进入 SK 案例库。
5. 不进入标准 10 维深拆。

## 1. Step 0 状态校准

### 1.1 已读 canonical files

| 文件 | 现读结果 | 文件头日期或更新时间 | 备注 |
|---|---|---|---|
| `README.md` | 已读 | 2026-05-12 | README 显示 SK 主仓库按链路使用，AI 拆解链路包括拆解模板、案例卡、失败模式、铁律等。 |
| `ops/执行状态总表.md` | 已读 | 2026-05-19 | 页面内搜索 `Kollab`、`kollab`、`FlowUs` 未命中。 |
| `cases/2026/产品对标库-38个AI产品复制价值排名.md` | 已读 | 2026-05-11 | 38 产品档案表内搜索 `Kollab`、`kollab` 未命中。 |
| `cases/2026/case-cards.md` | 已读 | 2026-05-04 | case-cards 页面内搜索 `Kollab`、`kollab`、`FlowUs` 未命中。 |
| `cases/2026/case-index.md` | 已读 | 未单独标文件更新时间，页面展示文章索引 | case-index 页面内搜索 `Kollab`、`kollab` 未命中。 |
| `cases/2026/产品对标库-扩容候选池.md` | 已读 | v0.3 · 2026-05-09 | 扩容候选池页面内搜索 `Kollab`、`kollab` 未命中。 |

### 1.2 已查目录

已查目录：`cases/2026/深度底稿/`

公开目录列表可见文件包括：

- `001-重新定义问题-拆解底稿.md`
- `004-Gamma-拆解底稿.md`
- `005-Lovable-拆解底稿.md`
- `006-Yoodli-中国机会扫描-研究报告.md`
- `006-Yoodli-拆解底稿.md`
- `007-Paid-拆解底稿.md`
- `011-MYHAIRAI-拆解底稿.md`
- `11x-对标分析.md`
- `Cactus-拆解底稿.md`
- `Hippocratic AI-10维深度拆解.md`
- `ListenLabs-轻量初拆.md`
- `Spangle-拆解底稿.md`
- `Supermemory-轻量初拆.md`
- `岚时AMAA-10维深度拆解.md`
- `暖哇阿拉莫斯-10维深度拆解.md`

目录公开页面未见 `Kollab`、`kollab`、`FlowUs` 相关底稿。

### 1.3 已做关键词搜索

已做页面内搜索：

- `Kollab`
- `kollab`
- `FlowUs`

已做公开 Web 搜索：

- `site:github.com/MRYGP/SK Kollab`
- `site:github.com/MRYGP/SK kollab.im`
- `site:github.com/MRYGP/SK "FlowUs" "Kollab"`
- `site:github.com/MRYGP/SK "Kollab" "轻量初拆"`

公开搜索未命中相关结果。

全仓库搜索未完全闭环，需要 Claude / SK 工作台用本地 grep 或 GitHub API 复核。

### 1.4 状态冲突

发现一个状态问题：

用户提供素材标题为 `207 Kollab`，但现读 SK 扩容候选池没有命中 `Kollab` 或编号 `207`。这说明该素材可能来自仓库外部信号源、未同步的私有队列、截图队列或用户手工补充列表。

当前未发现以下冲突：

- 执行状态总表没有显示 Kollab 已完成。
- case-cards 没有 Kollab 案例卡。
- case-index 没有 Kollab 文章或案例索引。
- 深度底稿公开目录没有 Kollab 文件。
- 38 产品档案表没有 Kollab 条目。

### 1.5 是否允许进入初拆

允许进入轻量初拆。

理由：现读仓库公开页面未发现 Kollab 已有底稿、案例卡或完成状态；但全仓库搜索未完全闭环，所以本稿需在审核提示中要求 Claude / SK 工作台再用本地 grep 或 GitHub API 复核一次。

## 2. 项目概况

### 2.1 一句话定位

Kollab 是一个让团队成员与 AI Agent 在同一个项目空间里协作的 AI-native workspace。

更白话地说，它不是「另开一个 AI 聊天窗口」，而是把 Agent 放回团队真实工作流里：项目、文档、任务、知识库、Slack / Telegram Bot、Connectors、Skills、Memory 都围绕同一个 workspace 运转。

### 2.2 产品形态

官网把 Kollab 定位为 AI-native workspace，核心组件包括：

- Shared Workspace：把项目、任务、文档、上下文和 AI 产物放在一个空间。
- Bots：把 Agent 接进 Slack、Telegram 等团队聊天入口。
- Connectors：连接 GitHub、Notion、Slack、Telegram、Buildin、Gmail、Figma、Linear 等工具，让 Agent 能读取、写入、协调和执行。
- Skills：把 prompt、多步流程、分析套路和工作标准封装成团队可复用能力。
- Knowledge Base / Memory：让 AI 访问团队文档、会议记录、历史决策与项目上下文。
- Scheduled Tasks：让 Agent 定时执行日报、周报、竞品扫描、错误日志分析等任务。
- CLI：让团队从命令行触发 Kollab workspace 任务，适合开发者和自动化场景。

### 2.3 团队与阶段

外部公开信息存在两套口径，需要深度研究员核对：

- Product Hunt 上，Gavin Wang 以 Kollab CEO and founder 身份发言，并称自己在做上一款 SaaS 产品 Buildin 时意识到多数产品仍是 SaaS + AI 逻辑。
- Memo 文章称 Kollab 由 FlowUs 创始人汪兆飞创立，并提到 FlowUs 已经盈亏平衡、海外版积累几十万用户，这些用户正在成为 Kollab 的早期种子用户。
- 用户提供素材称团队包括 FlowUs 创始人、前 Coze / 豆包手机负责人、锤子科技核心开发者。此项暂未找到独立 URL 交叉验证，证据等级记为 X。

阶段判断：产品已公开上线并有官网、Pricing、Product Hunt、LinkedIn、比较页、用例页，但 Memo 称其仍处于公测中。当前更适合视为早期产品，而不是已验证规模化商业产品。

## 3. 用户痛点：那个卡住的人

### 3.1 合成画像

合成画像，非真实访谈对象。

张宁，32 岁，10 人 AI 应用创业团队的产品负责人。

他每天至少三次遇到同一个问题：团队每个人都在用 AI，但 AI 能力停留在个人电脑和个人聊天记录里。工程师有自己的 Claude Code 配置，运营有自己的 ChatGPT prompt，创始人有自己的研究流程，产品有自己的周报模板。每个人都很强，但组织没有变强。

他卡住的不是「不会用 AI」，而是「会用 AI 的人无法把方法变成团队资产」。

具体表现：

1. 好 prompt 散落在个人聊天历史里。
2. 每周重复写周报、竞品扫描、用户反馈总结。
3. Slack / 飞书里产生的讨论没有沉淀成可复用的任务和知识。
4. 新人入职要重新问一遍团队怎么做事。
5. AI 的输出经常丢在聊天窗口里，没有成为项目产物。
6. 一个强 PM 的工作套路很难复制给全队。

### 3.2 旧解法为什么不够

- Slack / 飞书解决沟通，不解决 Agent 的长期记忆与产物沉淀。
- Notion / FlowUs 解决文档组织，不天然解决 Agent 执行和跨工具动作。
- ChatGPT / Claude 解决个人问答与执行，不天然解决团队级 Skill 复用。
- Zapier / Make / n8n 解决自动化流程，但对普通团队而言设置成本、维护成本和上下文理解门槛较高。
- 现有 SaaS 加 AI 功能，多数是给既有模块加助手，不是从 Agent 参与协作重新设计工作空间。

### 3.3 真问题

Kollab 要解决的问题不是「让个人多省 30 分钟」，而是：

团队里 AI 能力无法沉淀、复用、追踪、继承和跨工具执行。

如果这个判断成立，Kollab 的价值不在于 AI 回答更聪明，而在于把个人 AI 能力产品化为团队组织能力。

## 4. 产品机制轻量图

### 4.1 机制图

用户入口：
Slack / Telegram / Kollab Workspace / CLI
→

上下文层：
Project + Docs + Knowledge Base + Memory + Connectors
→

执行层：
Agent + Bots + Scheduled Tasks + Multi-step Skills
→

产物层：
Reports + Summaries + Docs + Tasks + Artifacts + Notifications
→

组织复利层：
一个人的工作流沉淀为 Skill
→ 团队复用
→ 产出格式更稳定
→ 新人更快继承
→ 项目记忆更完整
→ 下一次 Agent 执行成本更低

### 4.2 关键设计判断

Kollab 的核心不是单个 Agent，而是「Agent 的团队操作系统」。

它把四件过去分散的东西揉在一起：

1. 工作上下文：项目、文档、任务、历史决策。
2. 工作入口：聊天软件、workspace、CLI。
3. 工作能力：Skills、Connectors、Bots、Scheduled Tasks。
4. 工作记忆：团队长期知识、项目状态、流程标准。

如果只看表层，它像 Slack Bot + Notion + Zapier + Agent。  
如果看底层，它更像在回答一个新问题：AI 时代的组织记忆应该放在哪里。

### 4.3 一个值得注意的口径冲突

Kollab 产品页展示 Bots 可在 Feishu、Slack、Discord、Telegram 中工作；Bots 专页 FAQ 则写当前支持 Slack 和 Telegram，更多平台即将支持。两者可能代表不同页面更新时间或不同层级支持，需深度研究员核实当前可用平台。

## 5. 商业模式假设

### 5.1 已公开定价

Kollab 公开 Pricing 显示三个 self-serve 计划：

| 计划 | 价格 | 核心额度 |
|---|---:|---|
| Free | 0 美元 | 每日 200 refresh credits，每月免费上限 2,000 credits，1 GB 存储，团队席位不限，5 个 scheduled tasks |
| Pro | 20 美元 / 月 | 每日 200 refresh credits，6,000 subscription credits，1 TB 存储，团队席位不限，30 个 scheduled tasks |
| Max | 200 美元 / 月 | 每日 200 refresh credits，80,000 subscription credits，不限存储，团队席位不限，30 个 scheduled tasks |

另有一次性 top-up credits：1,500 credits 为 5 美元，3,000 credits 为 10 美元，15,000 credits 为 50 美元。

### 5.2 商业模式初判

Kollab 当前更像「workspace subscription + AI usage credits」混合模型。

这比传统 SaaS seat-based pricing 更适合 AI Agent 类产品，因为使用成本与模型调用、工具调用、长任务执行相关。它没有按团队人数强收费，而是把收费重心放在 credit consumption 上。

### 5.3 商业化风险

风险一：团队席位不限会降低早期扩散阻力，但也可能让收入与团队规模脱钩，必须依赖 credit 消耗拉开付费层级。

风险二：Agent workspace 的价值需要持续使用后才显现。Free 用户如果只试一次 Bot 或 Skill，可能无法感知 Memory 与组织复利。

风险三：使用量收费容易触发成本敏感。Product Hunt 评论里已有用户关心模型、BYOK 和 MCP 工具限制，说明重度用户会在成本、模型可控性、工具上限上做细算。

风险四：如果未来 Slack、Notion、飞书、钉钉、企业微信直接把 Agent + Memory + Workflow 做进底层，Kollab 必须证明自己不是可被平台吞掉的中间层。

## 6. 增长与分发

### 6.1 已观察到的分发信号

- Product Hunt 已有公开产品页，定位为 shared workspace where teams work with agents together。
- 官方 LinkedIn 发布了 Kollab 介绍，强调 real-time collaboration、scheduled tasks、memory、custom bots、Telegram 和 Slack。
- 官网通过大量 compare 页面截获搜索需求，包括 Kollab vs Manus、Kollab vs OpenClaw、Kollab vs NotebookLM、Kollab vs Claude Cowork。
- Memo 文章以「FlowUs 创始人创立 Kollab，要为 AI 构建团队大脑」为题进行中文创投圈传播。
- 官方用例页覆盖内容复用、周报自动化、竞品分析、bug reports to GitHub 等场景。

### 6.2 增长飞轮假设

Kollab 可能存在一个轻量组织复利飞轮：

一个人创建 Skill
→ 团队成员复用
→ 团队产出格式更一致
→ 更多流程被 Skill 化
→ Agent 记住更多组织上下文
→ 新任务执行质量提升
→ 团队更依赖 workspace
→ 迁移成本增加

### 6.3 分发瓶颈

最大瓶颈不是功能认知，而是迁移心理。

团队已经有 Slack、飞书、Notion、GitHub、Figma、Linear、Google Drive。Kollab 如果被理解成「又一个 workspace」，采用成本很高；如果被理解成「不用搬家，先在 Slack / Telegram 里装一个团队 Agent」，进入门槛会低很多。

所以 Bots 和 Connectors 不是附属功能，而是降低迁移阻力的入场协议。

## 7. 护城河初判

### 7.1 潜在护城河

第一层：组织记忆。  
如果 Kollab 真能沉淀团队决策、项目上下文、隐性标准和复用技能，时间越长，迁移成本越高。

第二层：Skill library。  
一个团队积累的 Skills 越多，Kollab 越像团队内部方法论仓库，而不只是工具入口。

第三层：跨工具连接。  
Connectors 让 Agent 接触 GitHub、Notion、Slack、Telegram、Buildin、Gmail、Figma、Linear 等工具，工作流越多，越难迁出。

第四层：工作产物闭环。  
Bot 生成的内容如果能回流 workspace，而不是留在聊天历史里，Kollab 就能把碎片对话变成可追踪产物。

### 7.2 护城河不足

护城河目前多是未来时，仍需验证。

需要重点核查：

1. 用户是否真的持续沉淀 Skills。
2. Skills 被复用的频率是多少。
3. Memory 是否能显著提升任务质量。
4. 团队是否愿意把核心数据授权给 Kollab。
5. 现有协作平台原生 Agent 是否会快速复制。
6. 迁移成本是不是强到用户不愿离开。

当前护城河更像「有可能形成」，不是已经证明。

## 8. 失败模式初判

### 8.1 FM008 快速复制风险

Kollab 可能被 Slack、Notion、飞书、钉钉、企业微信、Microsoft Teams、Google Workspace 等平台从底层复制。尤其当 Agent 入口、Memory、workflow、scheduled tasks 成为协作软件标配时，独立 workspace 的空间会被挤压。

风险等级：中高。

### 8.2 FM006 平台依赖风险

Kollab 的低阻力入口依赖 Slack、Telegram、Feishu、Discord 等 IM 平台和各类 Connector。平台政策、API 权限、企业安全要求都可能影响可用性。

风险等级：中。

### 8.3 FM014 交付复杂度风险

团队级 Agent 不是个人 chatbot。它要处理权限、上下文、工具调用、任务状态、产物版本、多人协作和审计。任何一环不稳定，都会导致团队不敢把关键流程交给它。

风险等级：中高。

### 8.4 FM003 伪需求风险

很多团队口头上说想要 AI 组织记忆，但真实付费可能只愿意为具体任务买单，例如周报、客服、营销内容、代码分析。如果 Kollab 过早讲「团队大脑」，但没有绑定高频刚需任务，可能变成高级概念产品。

风险等级：中。

### 8.5 FM015 无飞轮风险

Kollab 的飞轮依赖团队持续创建 Skills、接入 Connectors、积累 Memory。如果用户只把它当一次性 Bot 或内容生成工具，组织复利不会启动。

风险等级：中。

## 9. 中国机会初判

### 9.1 不能简单做「中国版 Kollab」

Kollab 本身就是华人团队面向全球市场的产品。中国机会不应被表述成「复制一个中文版」，而应拆成三个更窄的切口：

1. 国内团队在飞书、企业微信、钉钉、微信群、Notion-like 工具之间的 Agent 协作断裂。
2. 出海小团队在 Slack、Telegram、Notion、GitHub、Google Workspace 之间的 Agent 执行断裂。
3. 内容团队从 YouTube、TikTok、播客、长视频素材到多平台内容发布的流水线断裂。

### 9.2 更适合 SK 观察的中国切口

优先观察「内容创作团队的素材到发布工作台」。

理由：

- 用户痛点更具体：素材采集、字幕转写、选题提炼、脚本生成、图文改写、审核、排期发布。
- 高频更强：内容团队每周甚至每天都要处理素材。
- ROI 更容易讲清：节省剪辑、运营、编辑、研究时间。
- 相比泛团队协作，更容易做垂直 wedge。
- 用户提供素材提到 Kollab 已支持 YouTube、TikTok、播客字幕和文字稿采集，官网 compare 页面也强调外部媒体材料转成 transcript-based working context。

### 9.3 中国市场的反直觉点

国内大部分 AI 协作机会不是再做一个工作空间，而是找到一个高频入口，把 Agent 融进现有协作软件。

对中国团队而言，飞书、企业微信、钉钉、微信群已经是事实工作入口。让用户「搬家」很难，让 Agent 先进入已有群聊和文档系统，阻力更低。

因此，中国机会可能不是 workspace-first，而是 bot-first、workflow-first、vertical-first。

## 10. 四路决策初判

### 10.1 初判结论

四路决策初判：观察 + 工具使用，暂不直接复制。

### 10.2 路径拆解

| 路径 | 判断 | 理由 |
|---|---|---|
| 复制 | 暂不建议 | Kollab 本身是华人团队全球化产品，且底层竞争对手会包括大型协作平台，正面复制容易变成红海。 |
| 工具使用 | 建议 | SK 可把 Kollab 当成 AI 团队协作样本，测试「Skills + Bots + Memory」对工作台生产效率是否真实有效。 |
| 代理 | 可小范围探索 | 如果 Kollab 对内容团队、出海团队、AI 应用团队有效，SK 可观察是否有私域顾问式代理机会。 |
| 观察 | 建议 | 当前缺客户留存、收入、团队规模、真实案例、权限安全、平台支持等关键证据。 |

### 10.3 对 SK 的最小启发

Kollab 最值得 SK 学的不是功能，而是一个判断：

AI 时代真正可沉淀的资产，可能不是 prompt，而是团队反复执行的 Skills、项目 Memory 和跨工具工作流。

这对 SK 自己也有启发：SK 的方法论如果只在 Markdown 里，是知识库；如果能被 Agent 调用、复用、执行、回流产物，就可能变成团队级操作系统。

## 11. 资料充分性闸门

| 资料类别 | 当前状态 | 证据等级 | 是否足够进入标准 10 维 |
|---|---|---|---|
| 官网定位与功能说明 | 已找到官网 product、pricing、bots、connectors、skills、compare、use cases | A-claim | 是 |
| 创始人 / 团队信息 | Product Hunt 和 Memo 有创始人口径，但中英文身份、Buildin / FlowUs 关系需核对 | B / A-claim / X | 不足 |
| 融资或收入线索 | 未找到融资、ARR、MRR、付费客户规模 | X | 不足 |
| 客户案例或使用场景 | Product Hunt 有 HeyForm 用户评论与官方自用案例，官网有用例页，但缺独立客户案例 | A-claim / B弱 | 不足 |
| 定价 / 商业模式线索 | 官网 Pricing 已公开 | A-claim | 是 |
| 竞品或替代方案 | 官网 compare 页面覆盖 Manus、OpenClaw、NotebookLM、Claude Cowork；缺独立竞品研究 | A-claim | 半足够 |
| 失败风险 / 反例 | 需补用户吐槽、低分评论、流失原因、企业安全顾虑 | X | 不足 |
| 中国竞品或中国替代路径 | 未系统补齐飞书、钉钉、企业微信、FlowUs、Coze、Dify、扣子空间等对照 | X | 不足 |

闸门结论：缺 4 类以上关键资料，不进入标准 10 维深拆，只能保留轻量初拆，并交给深度研究员补证据。

## 12. 外部证据账本

| 断言 | 来源名称 | URL / 文件路径 | 证据等级 | 备注 |
|---|---|---|---|---|
| SK README 已现读，主仓库使用 main 分支，README 最后更新为 2026-05-12 | GitHub · MRYGP/SK README | https://github.com/MRYGP/SK/blob/main/README.md | Internal-status | 只证明仓库内部状态。 |
| 执行状态总表已现读，更新日期为 2026-05-19 | GitHub · ops/执行状态总表.md | https://github.com/MRYGP/SK/blob/main/ops/%E6%89%A7%E8%A1%8C%E7%8A%B6%E6%80%81%E6%80%BB%E8%A1%A8.md | Internal-status | 页面内搜索 Kollab 未命中。 |
| 38 产品档案表已现读，2026-05-11 新增焦虑解决器标记说明 | GitHub · 产品对标库-38个AI产品复制价值排名.md | https://github.com/MRYGP/SK/blob/main/cases/2026/%E4%BA%A7%E5%93%81%E5%AF%B9%E6%A0%87%E5%BA%93-38%E4%B8%AAAI%E4%BA%A7%E5%93%81%E5%A4%8D%E5%88%B6%E4%BB%B7%E5%80%BC%E6%8E%92%E5%90%8D.md | Internal-status | 页面内搜索 Kollab 未命中。 |
| case-cards 已现读，最后更新为 2026-05-04 | GitHub · case-cards.md | https://github.com/MRYGP/SK/blob/main/cases/2026/case-cards.md | Internal-status | 页面内搜索 Kollab 未命中。 |
| case-index 已现读，当前文章索引中未命中 Kollab | GitHub · case-index.md | https://github.com/MRYGP/SK/blob/main/cases/2026/case-index.md | Internal-status | 只证明公开页面未命中。 |
| 扩容候选池已现读，版本为 v0.3 · 2026-05-09 | GitHub · 产品对标库-扩容候选池.md | https://github.com/MRYGP/SK/blob/main/cases/2026/%E4%BA%A7%E5%93%81%E5%AF%B9%E6%A0%87%E5%BA%93-%E6%89%A9%E5%AE%B9%E5%80%99%E9%80%89%E6%B1%A0.md | Internal-status | 页面内搜索 Kollab 和编号 207 未命中。 |
| 深度底稿公开目录没有列出 Kollab 文件 | GitHub · 深度底稿目录 | https://github.com/MRYGP/SK/tree/main/cases/2026/%E6%B7%B1%E5%BA%A6%E5%BA%95%E7%A8%BF | Internal-status | 公开目录未命中不等于全仓库闭环。 |
| Kollab 自称 AI-native workspace，让团队和 AI Agents 在同一 shared space 中协作 | Kollab 官网 Product 页 | https://kollab.im/product | A-claim | 官网主张，只证明官方定位。 |
| Kollab 产品页称支持 Skills 和 Bots | Kollab 官网 Product 页 | https://kollab.im/product | A-claim | 官网主张。 |
| Kollab 产品页称可连接 Notion、Linear、Figma 等工具 | Kollab 官网 Product 页 | https://kollab.im/product | A-claim | 官网主张。 |
| Kollab 产品页展示 Bots 可在 Feishu、Slack、Discord、Telegram 中工作 | Kollab 官网 Product 页 | https://kollab.im/product | A-claim | 与 Bots FAQ 当前支持口径存在差异，需核对。 |
| Kollab Bots 专页称当前支持 Slack 和 Telegram，并可同步产物回 workspace | Kollab 官网 Bots 页 | https://kollab.im/product/bots | A-claim | 官网主张，需实测。 |
| Kollab Connectors 页称可连接 GitHub、Notion、Slack、Telegram、Buildin 等，让 Agent 读写和执行 | Kollab 官网 Connectors 页 | https://kollab.im/product/connectors | A-claim | 官网主张。 |
| Kollab Skills 页称可用自然语言创建可复用 Skill，并保存到团队库 | Kollab 官网 Skills 页 | https://kollab.im/product/skills | A-claim | 官网主张。 |
| Kollab Pricing 显示 Free、Pro 20 美元/月、Max 200 美元/月三档 | Kollab Pricing | https://kollab.im/pricing | A-claim | 公开定价。 |
| Kollab Pricing 显示按 credits 模式计费，并有 top-up credits | Kollab Pricing | https://kollab.im/pricing | A-claim | 公开定价。 |
| Product Hunt 页面称 Kollab 是 shared workspace where AI agents become part of your team | Product Hunt · Kollab | https://www.producthunt.com/products/kollab-2 | B | 第三方平台页面，但主体内容含官方提交与用户评论。 |
| Product Hunt 上 Gavin Wang 自称 Kollab CEO and founder，并称上一款 SaaS 产品为 Buildin | Product Hunt · Kollab | https://www.producthunt.com/products/kollab-2 | A-claim | 创始人口径，仍需核对身份与公司关系。 |
| Product Hunt maker 评论称 Kollab 内部产品、工程、运营团队已有 20 多个 active skills | Product Hunt · Kollab | https://www.producthunt.com/products/kollab-2 | A-claim | 官方自述，不证明外部客户留存。 |
| Product Hunt 用户 Luo 称 HeyForm 团队内部使用 Kollab 几周，最大收益是 Skills 可复用 | Product Hunt · Kollab | https://www.producthunt.com/products/kollab-2 | B弱 | 公开用户评论，样本小，需核实用户身份与使用深度。 |
| Memo 文章称 Kollab 解决 Team-level AI 的协作断裂，而不是单任务效率 | Memo · FlowUs 创始人创立 Kollab | https://vcsmemo.com/article/a17def5d-54da-43bc-80a6-8577a72c9564 | B | 中文创投媒体分析。 |
| Memo 文章称 Kollab 包含 Shared workspace、Bots、Skills、Memory 四层 | Memo · FlowUs 创始人创立 Kollab | https://vcsmemo.com/article/a17def5d-54da-43bc-80a6-8577a72c9564 | B | 第三方归纳，需与官网交叉。 |
| Memo 文章称汪兆飞是 FlowUs 创始人，并称 Kollab 一开始面向全球市场 | Memo · FlowUs 创始人创立 Kollab | https://vcsmemo.com/article/a17def5d-54da-43bc-80a6-8577a72c9564 | B | 需核对工商、LinkedIn、官网团队页。 |
| Memo 文章称 FlowUs 已经盈亏平衡、海外产品积累几十万用户，并成为 Kollab 早期种子用户 | Memo · FlowUs 创始人创立 Kollab | https://vcsmemo.com/article/a17def5d-54da-43bc-80a6-8577a72c9564 | B | 关键商业断言，需独立来源交叉验证。 |
| Kollab LinkedIn 帖子称产品包括 real-time collaboration、scheduled tasks、memory、custom bots，可连接 Telegram 和 Slack | LinkedIn · Kollab company post | https://www.linkedin.com/posts/kollabhq_we-built-kollab-an-ai-workspace-for-teams-activity-7453611885830230016-xPwe | A-claim | 官方社媒主张。 |
| Kollab compare 页面称可从 YouTube、TikTok、podcast、web sources 抽取 transcripts 并转成工作上下文 | Kollab vs Claude Cowork | https://kollab.im/compare/kollab-vs-claude-cowork | A-claim | 官网比较页主张。 |
| Kollab use case 页称可围绕 Notion / Buildin 数据库做内容复用 workflow，把 YouTube、blog、podcast、newsletter 转成多平台内容包 | Kollab content repurposing use case | https://kollab.im/use-cases/content-repurposing-workflow | A-claim | 官网用例，不证明用户实际采用。 |
| 用户提供素材称团队包括前 Coze / 豆包手机负责人、锤子科技核心开发者 | 用户本轮提供素材 | 当前对话用户粘贴内容 | X | 无可核对 URL，需深度研究员补证据。 |
| 中国可复制机会初判为 bot-first、workflow-first、vertical-first | 本稿逻辑推断 | cases/2026/深度底稿/Kollab-轻量初拆.md | C | 不是市场事实，需访谈验证。 |
| Kollab 护城河可能来自组织记忆、Skill library、跨工具连接、产物闭环 | 本稿逻辑推断 | cases/2026/深度底稿/Kollab-轻量初拆.md | C | 需要真实留存和迁移成本证据。 |

## 13. 发现的 SK 内部状态问题

### 13.1 用户素材编号与仓库状态不一致

用户提供的标题是 `207 Kollab`，但现读扩容候选池没有编号 207，也没有 Kollab 条目。

可能原因：

1. 该编号来自仓库外的信号源队列。
2. 该条目尚未同步到 `产品对标库-扩容候选池.md`。
3. 该条目来自截图或私有工作台，不属于 SK 主仓库公开状态。
4. GitHub 公开页面滞后于本地仓库。

处理建议：Claude / SK 工作台应确认 `207 Kollab` 的来源。如果这是新信号，应考虑是否追加到扩容候选池，而不是直接进入正式 38 产品档案。

### 13.2 全仓库搜索未闭环

本次只完成 GitHub 公开页面打开、页面内查找和公开搜索引擎检索。未完成 authenticated GitHub code search 或本地 grep。

需要 Claude / SK 工作台执行：

- `grep -R "Kollab" D:\sk`
- `grep -R "kollab" D:\sk`
- `grep -R "kollab.im" D:\sk`
- `grep -R "FlowUs" D:\sk`
- `grep -R "汪兆飞" D:\sk`

如果本地命中已有草稿，应暂停保存本稿或改为补证据稿。

## 14. 深度研究员补齐清单

### 14.1 团队与主体核查

1. Kollab 的法律主体是什么。
2. Gavin Wang 与汪兆飞是否为同一人，或分别是什么角色。
3. Buildin、FlowUs、Kollab 三者的公司关系、产品关系、团队关系。
4. 用户提供的前 Coze / 豆包手机负责人、锤子科技核心开发者是否有公开来源。
5. 团队当前人数、所在地、融资状态。

### 14.2 商业与增长核查

1. 是否有真实付费用户。
2. Pro / Max 付费转化情况。
3. 当前 MRR / ARR 是否有公开或可访谈线索。
4. Product Hunt 转化是否带来真实活跃。
5. LinkedIn、X、Discord、社区的真实互动质量。
6. 是否有公开客户案例，而非官方自用案例。

### 14.3 产品实测

1. 注册 Kollab 并创建 workspace。
2. 创建一个 Skill，看是否能稳定复用。
3. 连接 Slack 或 Telegram，测试 Bot 结果是否回流 workspace。
4. 连接 GitHub / Notion / Buildin / Google Drive，测试权限和执行稳定性。
5. 运行 scheduled task，观察失败率、日志、可追踪性。
6. 测试 YouTube / TikTok / podcast transcript 到内容产物链路。
7. 测试中文语境下的效果，尤其是飞书、企业微信、钉钉入口是否可用。

### 14.4 竞品与替代路径

1. Slack Agentforce / Slack AI Agents。
2. Microsoft Teams + Copilot + Agent。
3. Notion AI 与 Notion workspace automation。
4. Google Workspace Gemini。
5. 飞书多维表 / 飞书智能伙伴。
6. 钉钉 AI 助理。
7. 企业微信智能体生态。
8. Coze / 扣子、Dify、n8n、Zapier、Make。
9. Manus、OpenClaw、Claude Code、NotebookLM、Claude Projects。
10. 国内内容团队工具：剪映、即梦、扣子、飞书、影刀、RPA 工具。

### 14.5 失败证据

1. 搜索用户吐槽：setup 复杂、权限担忧、成本过高、执行不稳定。
2. 搜索低分评论和替代产品迁移评论。
3. 找出「团队 AI workspace」类产品是否已有失败案例。
4. 判断用户是否真的愿意维护 Skills，还是只想临时问答。
5. 判断中小团队是否愿意把组织记忆交给第三方早期产品。

## 15. Claude / SK 工作台审核提示词

请你作为 SK 工作台审核员，审核 `cases/2026/深度底稿/Kollab-轻量初拆.md`。不要宣布入库，不要写公众号终稿。请按以下顺序处理：

1. 先用本地 grep 或 GitHub API 复核 SK 仓库内是否已有 Kollab、kollab、kollab.im、FlowUs、汪兆飞相关文件或草稿。
2. 若已有底稿或案例卡，判定为重复拆，停止保存或改为补证据。
3. 若没有重复，检查本稿是否满足轻量初拆结构：0 到 16 节、Step 0、资料充分性闸门、外部证据账本、补齐清单、下一步最小动作。
4. 逐条检查外部证据账本：官网主张是否被误用成市场事实，Memo 是否被误用成独立财务证据，用户提供素材中无 URL 的团队信息是否已标 X。
5. 重点红队攻击三个问题：
   - Kollab 是不是会被 Slack / 飞书 / Notion / Microsoft Teams 平台快速复制。
   - 团队是否真的会维护 Skills 和 Memory，还是只会用一次性 Bot。
   - 对中国市场而言，机会是否应从泛 workspace 改成内容团队或出海团队的垂直 workflow。
6. 给出审核结论：保留为轻量初拆、退回补证据、升为深度研究任务、或不建议继续。
7. 不要宣布本产品已入库，不要生成 case-card，除非 SK 主负责人明确要求。

## 16. 下一步最小动作

最小动作不是继续写长文，而是做一次 90 分钟实测。

建议动作：

1. 用 SK 自己的工作流注册 Kollab。
2. 创建一个 workspace，命名为 `SK Kollab Test`。
3. 做一个 Skill：输入一条 AI 产品素材，生成 SK 轻量初拆骨架。
4. 把一个 Slack 或 Telegram 群接入 Kollab Bot。
5. 让 Bot 每天定时抓取 3 条 AI 产品新闻，并同步为 workspace 文档。
6. 观察三件事：
   - 产物是否真的回流到同一个上下文。
   - Skill 是否能被重复调用并保持输出质量。
   - 团队是否觉得它比 ChatGPT + 飞书 + Notion 的组合更省心。
7. 只要第 6 步不成立，本项目不进入标准 10 维深拆，只保留为 AI Agent 协作方向观察样本。

一句话收束：

Kollab 值得看，不是因为它又做了一个协作软件，而是因为它把「个人会用 AI」这个能力，试图变成「团队能继承 AI 工作流」的组织资产。
