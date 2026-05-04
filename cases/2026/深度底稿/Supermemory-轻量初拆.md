---
app_name: "Supermemory"
date: "2026-05-04"
sector: "AI Agent Memory / Context Infrastructure"
stage: "Seed / early commercialization"
status: "active"
对三湘问道的价值: "帮助判断 AI 应用长期记忆层是否值得中国复制，以及是否能转化为场景记忆型 MTP"
优先级评分: 7
---

> **状态更新（2026-05-04）**：多AI交叉验证已完成。
> 综合得分 27/40，四路决策：观察，置信度：中。
> 汇总报告：`cases/2026/深度研究报告/SuperMemory多AI汇总报告.md`
> 案例卡：`cases/2026/case-cards.md`（CASE-Supermemory 已入）
> 关键新发现：Mem0 在 2026-04 将 LongMemEval 从 49% 提升至 93%，基准护城河动摇，为当前最高风险信号。
> 下一步：补竞品压强表（P0）+ 产品实测（P1）+ 中国访谈（P2，等P0结果）

# Supermemory 轻量初拆

> 文档性质：SK 产品对标轻量初拆底稿  
> 生成日期：2026-05-04  
> 建议保存路径：`cases/2026/深度底稿/Supermemory-轻量初拆.md`  
> 本稿用途：供 Claude / SK 工作台审核、挑错、补证据、决定是否进入标准深拆或 MTP。  
> 本稿边界：不是公众号终稿，不宣布入库，不宣布仓库已更新，不替代 Claude / SK 工作台最终判断。

---

## 0. 本稿边界

本稿是 Supermemory 的轻量初拆底稿，目标不是写出最终判断，而是把已有 5 份深度研究报告、公开资料和 SK 当前方法论收束成一个可审核的初稿。

本稿只做四件事：

1. 校准 SK 仓库当前状态，避免重复拆。
2. 把 Supermemory 的第一层价值压成可判断的问题。
3. 初步判断中国能否复制，以及复制时应该换成什么场景。
4. 列出继续研究和写稿前必须补齐的证据。

本稿不做以下事项：

1. 不进入标准 10 维深拆。
2. 不写公众号终稿。
3. 不宣布 Supermemory 已入库。
4. 不把创始人自述、官网客户 logo、社媒热度当作 PMF 证据。
5. 不把中国可复制判断写成已经验证的事实。

本稿的核心初判：

> Supermemory 值得拆，但不宜直接复制成“中国版通用 Memory API”。更稳的路径是：先作为 SK / Hermes / AI 工作台的工具使用对象，再把它抽象成“中国场景记忆”的 MTP 候选方向。

---

## 1. Step 0 状态校准

### 1.1 已校准的仓库文件

本次轻量初拆前，已按要求读取或复核以下 SK 仓库入口：

| 文件 | 本次状态 |
|---|---|
| `README.md` | 已作为仓库总入口读取，用于确认当前 SK 对 AI 产品拆解、案例卡、深度底稿的定位。 |
| `ops/执行状态总表.md` | 已读取，公开页面显示更新日期为 2026-05-04。 |
| `cases/2026/产品对标库-38个AI产品复制价值排名.md` | 已在此前状态校准中读取，Supermemory 位于 38 产品队列，早期排序为 A 级 #2，状态为待分析。该表只作档案线索，不单独作为当前状态来源。 |
| `cases/2026/case-cards.md` | 公开页面检索未发现 Supermemory / SuperMemory / supermemory 相关案例卡。 |
| `cases/2026/case-index.md` | 公开页面检索未发现 Supermemory / SuperMemory / supermemory 相关索引项。 |
| `cases/2026/深度底稿/` | 公开目录检索未发现 Supermemory 同名底稿。 |

### 1.2 同名与别名搜索口径

本次需要搜索的关键词包括：

- `Supermemory`
- `SuperMemory`
- `supermemory`
- `Supermemory AI`
- `AnyContext`
- `Any Context`
- `AI memory`
- `memory API`
- `长期记忆`
- `记忆层`

当前公开页面和可访问搜索未发现 Supermemory 已有底稿或案例卡，但这不是全仓库闭环结论。

> 全仓库搜索未完全闭环，需要 Claude / SK 工作台用本地 grep 或 GitHub API 复核。

### 1.3 是否触发禁止重复拆

| 禁止重复拆条件 | 本次判断 |
|---|---|
| 执行状态总表写“深推完成” | 未发现 |
| 执行状态总表写“底稿完成” | 未发现 |
| case-cards 已有案例卡 | 未发现 |
| 深度底稿目录已有同产品底稿 | 公开目录未发现 |
| 产品已降为 D 级且只适合产品构思 | 未发现 |
| 产品为 C 级参考品且用户未明确要求模式提炼 | 不适用 |

本次判断：可以生成轻量初拆底稿，但需要在文末明确要求 Claude / SK 工作台复核全仓库 grep。

### 1.4 已发现的状态漂移

在此前状态校准中发现：38 产品表仍有若干产品显示待分析，但深度底稿目录已经出现对应底稿。这说明 38 产品表已经降级为档案，不可作为当前状态唯一来源。

对 Supermemory 的当前处理原则：

> 先交付轻量初拆，不宣称仓库无重复文件，不宣称已入库。

---

## 2. 项目概况

### 2.1 一句话定位

Supermemory 是一个面向 AI agents 和 AI 应用的长期记忆与上下文基础设施。它试图把用户的聊天、文件、网页、PDF、邮件、代码、项目背景和历史偏好，转成可以被 AI 跨会话、跨工具调用的长期上下文。

更短的表达：

> Supermemory 帮 AI 应用记住用户是谁、以前说过什么、现在正在做什么。

### 2.2 产品形态

Supermemory 当前呈现为双轨产品：

| 产品形态 | 面向对象 | 作用 |
|---|---|---|
| Memory API / Context Infrastructure | 开发者、Agent 产品团队、企业 | 给 AI 应用接入长期记忆、用户画像、文档检索和上下文召回能力 |
| Personal Supermemory / App / 插件 / MCP | 高强度 AI 工具用户 | 让个人在 Claude Code、Cursor、OpenCode、OpenClaw、Codex 等工具之间复用一份长期记忆 |

这说明 Supermemory 不是单一的“第二大脑”工具，而是从 C 端个人记忆工具转向 B2D / B2B 基础设施，同时保留个人入口作为试用和展示场。

### 2.3 创始人与融资

公开资料中，Supermemory 创始人为 Dhravya Shah。TechCrunch 报道其为来自孟买的年轻创始人，曾做过 consumer bots 和 Twitter 截图相关工具，后转向为 AI apps 做记忆层。

融资口径存在冲突：

| 口径 | 来源 | 本稿处理 |
|---|---|---|
| 2025-10-06 首轮融资 $2.6-3M（TechCrunch报$2.6M，官方博客报$3M，精确金额待核实） | Supermemory 官方博客、创始人相关公开传播 | 作为 A-claim，说明公司自称 |
| 2025-10-06 seed funding $2.6-3M（TechCrunch报$2.6M，官方博客报$3M，精确金额待核实） | TechCrunch 等媒体报道 | 作为 B 级独立媒体口径 |
| $40M 估值 | LinkedIn / Analytics India Magazine 等二手传播 | 标为 X 或 B-investor 线索，不进入核心判断 |
| $29M 总融资 | 个别异常来源 | 标为 X，不采信 |

本稿采用保守表述：

> Supermemory 于 2025 年 10 月宣布完成约 $2.6M–$3M 的早期融资，精确金额存在公开口径差异，需要人工核实最终法律文件。

### 2.4 用户与收入信号

当前能确认的是：Supermemory 有官网、文档、GitHub 仓库、定价页、API 控制台、个人 app、插件、MCP、研究页和早期客户 logo 展示。

不能确认的是：

- ARR
- MRR
- 付费客户数
- 续费率
- NDR
- DAU / MAU
- 真实生产环境使用深度
- 客户是否长期续约
- 企业客户合同金额

因此，本稿不把“用户数”“客户 logo”“社媒好评”当作强 PMF 证据，只把它们作为早期 traction 线索。

---

## 3. 用户痛点：那个卡住的人

### 3.1 合成用户画像

> 合成画像，非真实访谈对象。  
> 该画像用于理解产品机制，不作为真实用户证据。

林远，31 岁，B2B SaaS 创业公司技术负责人。他正在给公司客户做一个客服 Agent，希望这个 Agent 能记住每个客户的产品版本、合同限制、历史工单、偏好语气、上次投诉、承诺过的解决方案和当前跟进状态。

他试过三种方法：

1. 把全部聊天历史塞进 prompt。
2. 用 PostgreSQL + pgvector + 对话摘要自建记忆层。
3. 让客服人员在 CRM 或飞书里手动写备注，再由 Agent 临时检索。

三种方法都卡住了。

### 3.2 他具体卡在哪

第一，他不能每次都把完整历史塞给模型。token 成本高，延迟高，旧信息和新信息冲突时还会让 AI 混乱。

第二，自建记忆层看起来简单，实际很麻烦。要做分块、向量化、摘要、召回、重排、时效判断、冲突处理、权限隔离和数据同步。这个工作不是一个普通 SaaS 团队愿意长期维护的核心业务。

第三，人工备注无法稳定复用。客户偏好和历史承诺散落在企业微信、飞书、CRM、工单系统、销售私聊和文档里。AI 每次回答时不知道哪些信息该记住，哪些已经过期，哪些是最新事实。

### 3.3 第一层价值

Supermemory 的第一层价值不是“保存信息”，而是：

> 帮 AI 产品团队在不自建复杂记忆管道的情况下，让 Agent 能跨会话记住用户、项目和历史上下文。

更贴近用户痛点的表达：

> 它解决的是 AI 应用的“上下文断裂”问题，不是普通搜索问题。

### 3.4 消失测试

如果 Supermemory 消失，最痛的用户不是偶尔试用个人 AI 工具的人，而是已经把它接入生产环境的 AI 应用团队。

这些团队会损失：

- 用户长期偏好
- 项目历史上下文
- 记忆抽取逻辑
- 客户画像
- 插件和 API 集成
- 历史数据迁移路径

但当前没有独立证据证明有大量客户已经形成这种迁移痛苦。因此，消失测试目前只能判为“理论上成立，实证不足”。

---

## 4. 产品机制轻量图

### 4.1 机制图

```text
用户 / 应用 / Agent 产生内容
        ↓
聊天、文件、网页、PDF、图片、视频、代码、邮件、项目资料
        ↓
Supermemory 进行抽取、索引、分块、语义理解
        ↓
形成 Memories、User Profiles、Memory Graph、Documents
        ↓
查询时进行 hybrid search、profile recall、context injection
        ↓
只把相关上下文喂给模型
        ↓
AI 回答更连续、更个性化、更少重复解释
        ↓
新交互继续进入记忆层，更新旧事实或形成新关系
4.2 它和普通 RAG 的差异

普通 RAG 更像“把资料存起来，用户问的时候搜一段”。

Supermemory 试图做的是：

从内容中抽取记忆，而不是只存原文。
维护用户画像，而不是每次靠用户手动说明自己是谁。
处理时间变化和事实更新，而不是把所有历史信息同等对待。
把记忆和文档检索合并到一个 context stack。
通过 API、插件、MCP、连接器，让记忆跨工具复用。
4.3 当前最可信的能力层

从外部证据看，当前最可信的是：

官方已经提供 API、定价页、文档和 GitHub 仓库。
产品支持 Memory API、User Profiles、RAG、Connectors、file processing 等上下文栈能力。
官方研究页提供 LongMemEval-S 等 benchmark 结果。
GitHub README 和官网展示了插件、MCP 和常见 AI 工具集成路径。

需要谨慎的能力层是：

benchmark 是否可独立复现。
企业客户是否长期生产使用。
“记忆图谱”在真实复杂业务中的准确率。
免费多模态抽取是否能在大规模下保持单位经济健康。
5. 商业模式假设
5.1 收费方式

Supermemory 官网定价显示为四档：

套餐	价格	主要能力
Free	$0	1M tokens/month，10K search queries/month
Pro	$19/month	3M tokens/month，100K search queries/month，插件能力
Scale	$399/month	80M tokens/month，20M search queries/month，Gmail、S3、Web Crawler connectors
Enterprise	Custom	unlimited tokens/search queries、forward-deployed engineer、custom integrations、SSO

Pro / Scale 超额收费为：

$0.01 / 1,000 tokens
$0.10 / 1,000 queries
5.2 谁付钱

可能付钱的人分三类：

付费者	付费理由	不确定性
AI 应用开发者	不想自建记忆、RAG、profile、connector 和检索逻辑	是否愿意为 memory 单独付费未确认
Agent 产品团队	需要生产环境下的用户长期记忆和个性化上下文	是否能替代自建方案未确认
高强度个人 AI 用户	希望 Claude Code、Cursor、OpenCode 等工具共享长期上下文	个人用户持续付费意愿未确认
5.3 为什么付钱

理论付费理由有四个：

节省工程时间：不用自己搭向量库、摘要、重排、profile 和记忆更新。
降低上下文成本：不必每次把完整历史塞进 prompt。
提升用户体验：Agent 能记住历史偏好和项目背景。
降低试错门槛：用 API、插件、MCP 快速接入。

但这些理由仍需要用户访谈验证。尤其要确认：客户是不是真的愿意为“记忆层”单独付费，而不是期待大模型平台默认提供。

5.4 单位经济假设

当前无法精算 Supermemory 单位经济，因为缺少：

真实付费用户数
tokens 与 query 使用分布
抽取模型成本
存储和检索成本
免费用户滥用率
企业合同金额
毛利率
客户生命周期价值

轻量推断：

如果记忆抽取、图谱维护和多模态处理大量依赖第三方模型，FM004 推理成本失控风险会上升；如果 Supermemory 能通过缓存、批处理、轻量模型、自研检索和分层存储压低成本，订阅型基础设施仍可能形成健康毛利。

证据等级：C。

6. 增长与分发
6.1 当前增长入口

Supermemory 目前能看到的增长入口包括：

入口	作用
GitHub 开源仓库	开发者认知与试用入口
官网和文档	API 和插件转化入口
个人 app	让非开发者体验跨工具记忆
MCP 与插件	嵌入 Claude Code、Cursor、OpenCode、OpenClaw、Codex 等工具场景
社媒与创始人叙事	强化年轻 solo founder、AI memory、基础设施窗口的传播
客户 logo / testimonial	提供早期可信度，但不能证明 ROI
6.2 分发楔子

最强的分发楔子是：

你已经每天在用 AI 工具，但每个工具都不记得你。装一个 Supermemory，让它们共享一份记忆。

这比“开发者接一个 memory API”更容易被理解。

6.3 留存机制

理论留存来自数据沉淀：

记忆越多，用户越不愿迁移。
项目越多，跨项目上下文越重要。
企业客户越多，权限、合规、连接器和历史数据迁移成本越高。

但当前缺少 D30 / D90 留存、续费率和真实迁移成本证据。

6.4 增长风险

Supermemory 的增长不是天然自传播。用户的记忆不会像 Gamma 的文档或演示稿那样自然展示给其他人。因此，它更像开发者工具和基础设施产品，需要依赖：

开源社区
开发者口碑
集成生态
企业销售
插件分发
benchmark 和技术声誉

这意味着它有产品内数据沉淀飞轮，但外部分发飞轮仍需验证。

7. 护城河初判
7.1 可能存在的护城河
护城河来源	初判	证据等级
技术架构	有一定差异，但需要第三方复测	A-claim / C
记忆数据沉淀	理论上成立，实证不足	C
开发者生态	有开源、插件、MCP 和文档入口	A-claim
连接器生态	有 Google Drive、Gmail、Notion、OneDrive、GitHub、S3、Web Crawler 等方向	A-claim
个人 app + API 双轨	对品牌和试用有帮助	C
benchmark 声誉	官方研究页声称 LongMemEval-S overall 81.6%	A-claim
7.2 不宜高估的护城河

第一，不宜把“记忆”本身当护城河。Memory API、RAG、用户画像、向量检索和连接器都不是不可复制能力。

第二，不宜把开源 star 和社媒热度当 PMF。它们说明开发者兴趣，但不能证明付费留存。

第三，不宜把客户 logo 当 ROI 证明。官网 logo 只能证明官方声称存在客户关系，不能证明部署深度、续费、合同金额或效果。

第四，不宜把 benchmark 当真实生产质量。官方 benchmark 有价值，但需要第三方复现和真实业务场景测试。

7.3 关键护城河假设

如果 Supermemory 最终能守住，它守住的不是“向量检索”，而是：

成为跨模型、跨工具、跨 Agent 的中立长期上下文层。

这个假设成立需要三个条件：

大模型厂商的记忆能力仍然相互割裂。
开发者和企业愿意把记忆层交给中立第三方。
Supermemory 的记忆质量、延迟、成本和合规能力优于自建与云厂商内置方案。

目前这三个条件都未完全验证。

8. 失败模式初判
8.1 FM008 竞品快速复制：高风险

风险描述：

AI 记忆层会被大模型平台、Agent 框架、云厂商、RAG 工具、开源项目和企业知识库同时挤压。OpenAI、Google、Microsoft、Anthropic、阿里、腾讯、火山、LangChain、Mem0、Zep、Letta 都可能在不同层面提供记忆能力。

为什么危险：

用户可能不愿额外采购一个 memory API。
开发者可能选择 LangGraph / LangMem / Mem0 / Zep / 自建。
企业可能选择云厂商内置能力，降低合规和采购阻力。
大模型厂商可能把 memory 做成默认功能。

早期信号：

竞品推出同类插件、MCP、profile、connector。
云厂商把长期记忆作为 Agent 平台标配。
用户反馈“内置记忆够用”。
Supermemory 必须靠降价或免费额度竞争。
8.2 FM003 伪需求陷阱：中高风险

风险描述：

AI memory 的想象空间很强，但用户是否愿意持续付费未被公开数据证明。

为什么危险：

开发者觉得记忆重要，但生产环境未必需要第三方。
个人用户觉得很酷，但可能只试用不续费。
企业客户担心隐私和合规，不敢接入全量用户数据。
记忆质量不稳定时，用户宁愿手动复制上下文。

早期信号：

免费用户多，Pro / Scale 转化弱。
客户只做 demo，不进 production。
社区反馈集中在“记错”“召回差”“隐私担忧”“vendor lock-in”。
没有第三方续费和留存证据。
8.3 FM004 推理成本失控：中风险

风险描述：

长期记忆不只是存储。它涉及抽取、嵌入、检索、重排、图谱更新、时间推理、多模态处理和上下文注入。若成本随用户使用快速上升，低价订阅可能压缩毛利。

早期信号：

免费层缩水。
超额计费规则频繁变化。
用户吐槽延迟和账单。
团队大量招聘 infra / inference optimization。
企业客户重度使用导致边际成本高于合同收入。
8.4 FM009 监管与隐私风险：中高风险

风险描述：

记忆层处理的是长期用户数据、聊天内容、文件、邮件、偏好、客户历史和可能的企业敏感信息。在中国复制时，企业微信、飞书、钉钉、CRM、客户隐私、行业数据留存和模型调用都涉及合规问题。

早期信号：

企业要求私有化部署。
客户拒绝连接邮件、聊天和 CRM。
法务要求数据不出域。
行业客户要求审计、权限隔离、数据删除和可追溯。
8.5 FM015 无飞轮增长依赖：中风险

风险描述：

Supermemory 有“记忆越用越多”的产品内飞轮，但不一定有“用户越多，获客越便宜”的分发飞轮。

早期信号：

增长主要依赖创始人社媒、融资故事和开发者热度。
新用户进入不来自老用户产出物传播。
需要持续做内容、benchmark、集成和开发者关系才能保持增长。
社区热度与付费转化脱节。
9. 中国机会初判
9.1 不建议直接复制的形态

不建议直接做：

中国版通用 Supermemory API。

原因有四个：

通用 memory API 容易被云厂商、Agent 平台和大模型厂商内置。
中国开发者工具基础设施付费不一定强。
企业客户对长期记忆涉及的数据权限和合规更谨慎。
纯 API 产品对 2-5 人小团队的销售、交付和生态要求较高。
9.2 更值得验证的中国切口

更适合中国复制的方向不是“通用记忆”，而是“场景记忆”。

切口 A：AI 编程项目上下文保险箱

目标用户：

高频使用 Cursor、Claude Code、Trae、MarsCode、通义灵码、CodeBuddy 的开发者和小团队。

痛点：

AI 不记得项目架构。
AI 不记得历史 bug。
AI 不记得团队代码规范。
AI 不记得上次为什么做某个技术决策。
不同 AI 工具之间上下文不能共享。

可能产品形态：

Repo 级记忆层。
项目规则自动沉淀。
历史决策卡片。
技术债和 bug 记忆。
跨 AI 编程工具的 context provider。

初判：

最适合 SK / Hermes 自己先做工具使用实验。

切口 B：私域销售与客户成功记忆层

目标用户：

中小 B2B 服务公司
私域运营团队
客户成功团队
教培与咨询团队

痛点：

客户偏好、历史承诺、合同限制、投诉记录散落在企微、飞书、CRM、表格和人工备注里。
新员工接手客户时不了解历史。
AI 客服不知道客户之前经历过什么。
销售跟进时容易忘记禁忌、承诺和转化阶段。

可能产品形态：

客户长期记忆卡。
下一次跟进前自动召回。
历史承诺与风险提醒。
企微 / 飞书 / CRM 连接器。
客户进展时间线。

初判：

最适合做 MTP 招募验证，因为记忆错误会影响转化、续费和客户体验，更容易讨论付费。

切口 C：教培与咨询长期学员记忆

目标用户：

教培机构
职业咨询
留学咨询
企业培训
教练型服务

痛点：

学员进度、作业、反馈、薄弱点和目标经常断档。
老师、顾问、助教之间交接成本高。
AI 辅助教学无法稳定知道学员历史状态。

初判：

有付费可能，但涉及未成年人、教育合规和机构工作流，需要谨慎。

9.3 中国复制最大障碍
障碍	解释
数据合规	记忆层会接触长期个人信息、企业聊天记录和客户资料
平台依赖	企业微信、飞书、钉钉、CRM 的数据接口和权限限制会决定产品可用性
云厂商竞争	阿里、腾讯、火山等可以把长期记忆做成 Agent 平台内置能力
付费意愿	用户可能愿意试用，但不愿为“记忆层”单独付费
交付复杂度	企业场景需要权限、审计、删除、私有化、连接器和数据隔离
记忆错误代价	记忆一旦错，可能比不记更危险
9.4 中国机会一句话

中国机会不是“复制一个 Supermemory”，而是找到那些“AI 忘一次就会造成真实损失”的高频业务场景，把长期记忆做成客户、项目或代码的上下文保险箱。

10. 四路决策初判
10.1 总结判断
路径	初判	理由
复制 / 对标	条件复制	通用 API 不宜直接复制，必须换成高频垂直场景
工具使用	强建议	对 SK / Hermes / AI 编程工作台有直接启发，可先用作自身基础设施实验
代理 / 分销	暂不优先	企业私有化和合规服务重，不适合早期直接做代理
观察	保留	重点观察其是否从开发者 API 走向企业标准件，以及竞品平台化速度
10.2 为什么不是直接复制

直接复制需要回答四个问题：

谁第一天付钱？
他们为什么不用云厂商或开源方案？
他们愿意把长期客户数据交给我们吗？
记忆错一次的代价是否可控？

目前这些问题没有被公开资料回答，也没有中国访谈验证。因此不能判为强复制。

10.3 为什么工具使用价值高

Supermemory 对 SK 的直接启发很强：

SK 自身就是长期上下文工作流。
Hermes / Claude / Cursor / SK 工作台都存在跨会话记忆断裂。
产品拆解、案例库、证据账本、失败模式和写稿流程都需要可迁移记忆。
用 Supermemory 或同类架构做内部实验，可以验证“项目上下文保险箱”是否真实省时间。
10.4 MTP 候选表达

可转成 MTP 的一句话：

我们想验证一个“AI 项目上下文保险箱”：让 AI 永远记得一个项目的背景、规则、历史决策、客户偏好和踩坑记录。我们要找 10 个每天被 AI 失忆折磨的人，看看这件事是否真的值得做。

11. 资料充分性闸门
11.1 八类资料检查
资料项	当前状态	判断
官网定位与功能说明	已有官网、文档、GitHub、定价页	足够做轻量初拆
创始人 / 团队信息	有 TechCrunch、官方博客、二手报道	基本够用，但团队规模需补
融资或收入线索	融资有冲突口径，收入缺独立证据	融资可保守写，收入不可强写
客户案例或使用场景	有官网 logo、TechCrunch 客户线索、testimonial	不足以证明 ROI 和续费
定价 / 商业模式线索	官网定价清晰	足够做商业假设
竞品或替代方案	Mem0、Zep、Letta、LangMem、Graphlit、云厂商路径有线索	需补系统竞品表
失败风险 / 反例	有逻辑推断和少量社区担忧	缺真实流失、退款、差评
中国竞品或中国替代路径	有阿里、腾讯、火山、Dify / RAGFlow 等路径线索	需补最新竞品实测和访谈
11.2 是否进入标准 10 维深拆

不建议立刻进入标准 10 维深拆。

原因：

真实续费和留存证据不足。
中国客户付费意愿未验证。
竞品平台化压强未系统拆完。
产品实测不足。
客户案例不能证明 ROI。

当前适合停留在轻量初拆，并进入三项补证据：

竞品与平台化压强报告。
中国垂直场景访谈。
Supermemory / Mem0 / Zep / 国内 Agent Memory 的实测对比。
12. 外部证据账本
断言	来源名称	URL / 文件路径	证据等级	备注
Supermemory 官网主域名为 supermemory.ai	Supermemory 官网	https://supermemory.ai/
	A-claim	官方来源，只证明官方展示
Supermemory 定位为 AI agents 的 memory / context infrastructure	Supermemory Docs Overview	https://supermemory.ai/docs/intro
	A-claim	官方文档说明
Supermemory 面向开发者和团队提供 Memory API，同时有个人 app / plugins 等入口	Supermemory 官网首页	https://supermemory.ai/
	A-claim	官方页面说明
Supermemory 支持文本、对话、文件、PDF、图片、视频等输入	Supermemory Docs Overview	https://supermemory.ai/docs/intro
	A-claim	官方文档说明
Supermemory 会构建 semantic understanding graph，并在查询时提取相关上下文	Supermemory Docs Overview	https://supermemory.ai/docs/intro
	A-claim	官方文档说明
Supermemory 将 documents 与 memories 区分，称 memories 是可连接、可更新的智能知识单元	Supermemory How It Works	https://supermemory.ai/docs/concepts/how-it-works
	A-claim	官方文档说明
Supermemory 支持 update / extends / derives 等 memory relationships	Supermemory How It Works	https://supermemory.ai/docs/concepts/how-it-works
	A-claim	官方文档说明
Supermemory GitHub README 称其可自动抽取 memories、构建 user profiles、处理 contradictions、forget expired information	Supermemory GitHub	https://github.com/supermemoryai/supermemory
	A-claim	官方开源仓库说明
Supermemory 支持 Claude Code、Cursor、OpenCode、OpenClaw、Codex、MCP 等个人工具入口	Supermemory 官网与 GitHub	https://supermemory.ai/
 ; https://github.com/supermemoryai/supermemory
	A-claim	官方说明
Supermemory 定价为 Free $0、Pro $19/month、Scale $399/month、Enterprise custom	Supermemory Pricing	https://supermemory.ai/pricing/
	A-claim	官方定价页
Supermemory Pro / Scale 超额计费为 $0.01 / 1,000 tokens 与 $0.10 / 1,000 queries	Supermemory Pricing	https://supermemory.ai/pricing/
	A-claim	官方定价页
Supermemory 官方研究页声称 LongMemEval-S overall 81.6%，高于 Zep 与 Full context	Supermemory Research	https://supermemory.ai/research/
	A-claim	官方 benchmark，需第三方复现
Supermemory 官方博客称 2025-10-06 宣布首轮融资 $2.6-3M（TechCrunch报$2.6M，官方博客报$3M，精确金额待核实）	Supermemory Blog	https://supermemory.ai/blog/supermemory-raises-3-million-and-building-the-best-memory-engine-for-llms/
	A-claim	官方博客，存在公司立场
TechCrunch 报道 Dhravya Shah 是 19 岁创始人，Supermemory 是面向 AI apps 的 memory layer	TechCrunch	https://techcrunch.com/2025/10/06/a-19-year-old-nabs-backing-from-google-execs-for-his-ai-memory-startup-supermemory/
	B	独立媒体报道
TechCrunch 报道融资为 $2.6-3M（TechCrunch报$2.6M，官方博客报$3M，精确金额待核实） seed funding	TechCrunch	https://techcrunch.com/2025/10/06/a-19-year-old-nabs-backing-from-google-execs-for-his-ai-memory-startup-supermemory/
	B	与官方 $2.6-3M（TechCrunch报$2.6M，官方博客报$3M，精确金额待核实）口径冲突，采用 $2.6M–$3M 区间
TechCrunch 报道 Shah 曾出售 Twitter 截图 bot 给 Hypefury	TechCrunch	https://techcrunch.com/2025/10/06/a-19-year-old-nabs-backing-from-google-execs-for-his-ai-memory-startup-supermemory/
	B	创始人背景线索
官网展示 Cluely、Nissan、OpenNote、Composio 等客户 logo	Supermemory 官网	https://supermemory.ai/
	A-claim	只证明官方展示，不证明 ROI、合同金额或续费
官网显示 10,000+ power users、10+ integrations、<300ms recall 等指标	Supermemory 官网	https://supermemory.ai/
	A-claim	官方自称运营指标，需独立验证
公开研究报告之间对融资金额、估值、团队规模、用户与收入信号存在冲突	上传研究包	/mnt/data/SuperMemory深度研究1.md 至 /mnt/data/SuperMemory深度研究5.md	X	内部研究输入，不作为外部市场事实
已上传研究包建议把 $29M 总融资口径判为异常线索，不采信	SuperMemory 深度研究5	/mnt/data/SuperMemory深度研究5.md	X	研究员判断，需人工复核原始来源
已上传研究包均未找到可靠第三方续费或留存数据	SuperMemory 深度研究2、3	/mnt/data/SuperMemory深度研究2.md ; /mnt/data/SuperMemory深度研究3.md	X	内部研究结论，需继续做用户访谈
中国存在阿里云百炼、腾讯云 Agent Memory、火山引擎 Mem0 等长期记忆或近似路径线索	SuperMemory 深度研究3	/mnt/data/SuperMemory深度研究3.md	X	研究包线索，需补官方 URL 与实测
中国机会更适合从“场景记忆”而非“通用 Memory API”切入	本稿推演	本文件	C	逻辑推断，待访谈验证
AI 编程项目上下文保险箱、私域销售客户记忆层、教培咨询长期学员记忆是三个候选切口	本稿推演	本文件	C	逻辑推断，需做 MTP 和访谈
Supermemory 在 SK 38 产品队列中早期被列为 A 级 #2、待分析	SK 38 产品对标库	cases/2026/产品对标库-38个AI产品复制价值排名.md	Internal-status	只证明内部早期记录，不证明当前状态
case-cards / case-index 公开页面未发现 Supermemory 命中	SK 仓库公开页面	cases/2026/case-cards.md ; cases/2026/case-index.md	Internal-status	全仓库搜索未完全闭环
深度底稿目录公开页面未发现 Supermemory 同名底稿	SK 仓库公开页面	cases/2026/深度底稿/	Internal-status	需本地 grep 或 GitHub API 复核
