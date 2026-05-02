# ListenLabs / Listen · 轻量初拆

> 底稿类型：轻量初拆，非 `core/product-teardown-template.md` 标准 10 维度深拆  
> 版本：v0.2  
> 生成日期：2026-05-02  
> 建议保存路径：`cases/2026/深度底稿/ListenLabs-轻量初拆.md`  
> 生成角色：SK-产品对标初拆 GPTS  
> 审核角色：Claude / SK 工作台  
> 入库状态：待审核，不代表已完成标准产品拆解  
> 重要边界：本稿不宣布仓库已更新，不宣布案例已入库，不替代深度研究员做完整外部研究，不替代 Claude / SK 工作台做最终判断。  
> 过程定位：本文为轻量初拆与闸门稿；在完成审核与证据补全前，不作为入库或结案依据。

---

## 0. 本稿边界

本稿是对 ListenLabs / Listen 的「轻量初拆」，用于判断它是否值得进入后续标准深拆或深度研究补证据流程。

本稿不是：

- 公众号终稿；
- 标准 10 维度深拆；
- 投资建议；
- 入库确认；
- 中国复制押注结论；
- 对 ListenLabs 产品效果的最终证明。

本稿采用证据分级：

- **A-claim**：官网 / 官方文档 / 公司新闻稿 / 官方客户案例，只证明官方声称；
- **B**：独立行业媒体 / 权威媒体 / 第三方客户案例 / 第三方访谈；
- **B-investor**：投资方文章 / 投资方披露，存在立场偏差，需独立来源交叉验证；
- **C**：逻辑推断 / 类比 / 估算；
- **X**：无 URL / 无可核对来源 / 未验证断言；
- **Internal-status**：SK 仓库内部状态，只证明内部记录，不证明外部市场事实。

---

## 1. Step 0 状态校准

### 1.1 已读文件

| 文件 | 文件头日期 / 最近更新时间 | 结论 |
|---|---|---|
| `README.md` | 最后更新：2026-05-02 | 已读。README 指向 `core/product-teardown-template.md`、`cases/2026/case-cards.md`、`cases/2026/产品对标库-38个AI产品复制价值排名.md`、`cases/2026/深度底稿/`、`ops/执行状态总表.md` 等关键入口。 |
| `ops/执行状态总表.md` | 更新日期：2026-05-02 | 已读。公开页面内查找 `ListenLabs`、`listenlabs`、`Listen Labs` 未命中。未发现「深推完成」或「底稿完成」记录。 |
| `cases/2026/产品对标库-38个AI产品复制价值排名.md` | 2026-04-26 降级为档案；最后更新：2026-04-12 | 已读。ListenLabs 位于 A级 #5，原始一句话定位为「AI用户访谈平台，30分钟访谈100个用户」，中国空白判断为「中国UX研究工具严重缺乏」，四路决策初判为「复制」，分析状态为「待分析」。该文件已降级为档案，只能作为原始排序与早期线索。 |
| `cases/2026/case-cards.md` | 最后更新：2026-04-17；另有 2026-04-28 待补齐提示 | 已读。公开页面内查找 `ListenLabs` 未命中。未发现 ListenLabs 案例卡。 |
| `cases/2026/case-index.md` | 最后更新：2026-04-28 | 已读。公开页面内查找 `ListenLabs` 未命中。已列深度底稿中不含 ListenLabs。 |
| `cases/2026/深度底稿/` | 目录公开页面，当前可见文件列表读取于 2026-05-02 | 已查目录。目录列出 `001-重新定义问题-拆解底稿.md`、`004-Gamma-拆解底稿.md`、`005-Lovable-拆解底稿.md`、`006-Yoodli-中国机会扫描-研究报告.md`、`006-Yoodli-拆解底稿.md`、`007-Paid-拆解底稿.md`、`011-MYHAIRAI-拆解底稿.md`、`11x-对标分析.md`、`360-维度跨越-提炼.md`、`Cactus-拆解底稿.md`、`FRAMEWORK-AI产品复制推演过程记录-11x案例.md`、`Spangle-拆解底稿.md`、`Tesla-素材底稿.md`、`充电宝讨论-KIMI流水账-20260418.md`，未见 ListenLabs 相关文件。 |

### 1.2 深度底稿 / 案例卡 / 索引命中

| 检查项 | 结果 | 备注 |
|---|---|---|
| `cases/2026/深度底稿/` 下是否已有 ListenLabs 相关文件 | 公开目录未命中 | 只代表公开目录页可见范围未命中，不代表 authenticated GitHub code search 或本地 grep 已闭环。 |
| `ops/执行状态总表.md` 是否出现 `ListenLabs` | 未命中 | 公开页面查找未命中。 |
| `ops/执行状态总表.md` 是否出现 `listenlabs` | 未命中 | 公开页面查找未命中。 |
| `ops/执行状态总表.md` 是否出现 `Listen Labs` | 未命中 | 公开页面查找未命中。 |
| `case-cards.md` 是否已有 ListenLabs 案例卡 | 未命中 | 公开页面查找 `ListenLabs` 未命中。 |
| `case-index.md` 是否已有 ListenLabs 条目 | 未命中 | 公开页面查找 `ListenLabs` 未命中。 |
| 产品对标库是否包含 ListenLabs | 命中 | A级 #5，初判「复制」，分析状态「待分析」。该文件为档案，不作为当前状态单一依据。 |

### 1.3 已做关键词搜索

已在 GitHub 公开页面和仓库关键文件中查找：

- `ListenLabs`
- `listenlabs`
- `Listen Labs`
- `AI user interview`
- `AI research platform`
- `AI用户访谈`
- `AI调研平台`

已打开 GitHub code search 页面：

- `https://github.com/search?q=repo%3AMRYGP%2FSK+ListenLabs&type=code`
- `https://github.com/search?q=repo%3AMRYGP%2FSK+listenlabs&type=code`
- `https://github.com/search?q=repo%3AMRYGP%2FSK+%22Listen+Labs%22&type=code`
- `https://github.com/search?q=repo%3AMRYGP%2FSK+%22AI+user+interview%22&type=code`
- `https://github.com/search?q=repo%3AMRYGP%2FSK+%22AI+research+platform%22&type=code`

限制：GitHub 页面显示「Sign in to search code on GitHub」，当前无法完成 authenticated GitHub code search。

> 全仓库搜索未完全闭环，需要 Claude / SK 工作台用本地 grep 或 GitHub API 复核。

### 1.4 状态冲突

ListenLabs 本身未发现完成状态冲突：

- 执行状态总表未命中；
- case-cards 未命中；
- case-index 未命中；
- 深度底稿公开目录未命中；
- 产品对标库仍显示 ListenLabs 为 A级 #5，状态「待分析」。

发现的仓库内部一般性状态问题（**仓库一般性漂移 / 状态不同步**）：

- 产品对标库已降级为档案，但其中 A级进度表仍显示若干产品为「待分析」；
- 深度底稿目录已经存在 `11x-对标分析.md`、`Spangle-拆解底稿.md`、`Cactus-拆解底稿.md`，而产品对标库进度表与 case-index 不完全同步；
- **对标库与索引不能单独当作当前状态来源**；需与深度底稿目录、`ops/执行状态总表.md` 交叉；
- 因此不能只凭产品对标库判断当前状态，必须以后续本地 grep / GitHub API 复核为准。

### 1.5 是否允许进入轻量初拆

结论：**允许进入轻量初拆。**

理由：

1. 未发现执行状态总表写「深推完成」或「底稿完成」；
2. 未发现 case-cards 已有案例卡；
3. 未发现深度底稿目录已有 ListenLabs 相关文件；
4. ListenLabs 在产品对标库中属于 A级 #5，原始状态为「待分析」；
5. 但 authenticated GitHub code search 未闭环，需要 Claude / SK 工作台复核。

---

## 2. 项目概况

| 维度 | 初判内容（证据等级与 URL 见「## 12. 外部证据账本」） |
|------|------------------------------------------------------|
| 产品名称 | ListenLabs / Listen / Listen Labs |
| 官网 | `https://listenlabs.ai/` |
| 官网定位（A-claim） | Listen 自称是 end-to-end research platform；客户可用 AI-moderated interviews 替代或压缩 surveys、focus groups、in-depth interviews；场景叙事含 brand tracker、usability testing、multi-market segmentation、concept testing、consumer journey map 等。 |
| 一句话理解 | 把「招募—主持访谈—追问—转录—聚类—生成报告」用户研究链路，压缩成由 AI researcher / AI moderator 与 AI 分析层驱动的小时级流程（官网叙事，**A-claim**）。 |
| 所属赛道 | AI 用户研究、AI 市场研究、AI qualitative research、UX research ops、customer intelligence |
| SK 原始对标库（Internal-status） | A级 #5；一句话定位「AI用户访谈平台，30分钟访谈100个用户」；中国空白判断「中国UX研究工具严重缺乏」；四路初判「复制」；状态「待分析」。**该对标库已降级为档案，仅作原始线索，不作为当前拆解完成状态或外部市场事实的单一依据。** |

**注意**：`cases/2026/产品对标库-38个AI产品复制价值排名.md` 已降级为档案；本稿只把它作为原始排序和早期线索，不把它作为当前拆解状态的单一依据。

---

## 3. 用户痛点：那个卡住的人

> 合成画像，非真实访谈对象。

她是一家 B2B SaaS 公司的 32 岁产品经理，兼任一部分用户研究工作。她每周都被老板、销售、客户成功、设计团队追问同一个问题：

> 「这个功能客户到底要不要？」

她知道应该做用户访谈，但实际卡在五个环节：

1. **招募慢**：要找对客户、约时间、确认身份，往往一拖就是一两周；
2. **访谈慢**：真正做 10 场深访就要消耗大量日历时间；
3. **追问质量不稳定**：不同主持人能否抓住关键回答继续追问，差异很大；
4. **整理慢**：录音、转写、摘 quote、聚类主题、写报告都很重；
5. **决策跟不上**：产品 sprint、营销活动、销售打法都在往前跑，研究结论经常来得太晚。

她现在的解决方式通常是：

- 用问卷星、腾讯问卷、飞书问卷发问卷；
- 找销售或客户成功转述客户声音；
- 临时约 5 到 8 个客户电话；
- 请实习生或研究员手动整理录音；
- 外包给市场调研公司或用户研究供应商。

这不是「不知道要听用户说话」的问题，而是「研究速度跟不上业务决策速度」的问题。ListenLabs 的核心机会在于：把传统「深但慢」的访谈，包装成「接近问卷速度的访谈深度」。

---

## 4. 产品机制轻量图

### 4.1 核心流程

```text
用户输入研究问题、目标人群、样本条件、刺激物、追问目标
        ↓
Listen 招募或接入受访者，并由 AI moderator 做视频 / 音频 / 文本访谈
        ↓
AI 根据回答自适应追问、记录、转写、聚类主题、抽取 quote
        ↓
系统输出 takeaways、personas、themes、highlight reels、deck、memos 或 executive-ready report
        ↓
产品 / 研究 / 品牌 / 管理团队用这些证据做功能、品牌、市场、创意或客户旅程决策
```

### 4.2 用户输入什么

用户通常输入：

业务问题，例如「用户为什么不购买这个新套餐」；
目标人群，例如「使用过竞品的企业采购负责人」；
样本条件，例如地区、行业、职位、购买行为、使用场景；
刺激物，例如 Figma 原型、图片、视频、广告文案、网站、产品概念；
研究目标，例如要验证概念、测试品牌感知、理解客户旅程、做可用性测试。

官网称 Listen 支持 videos、images、Figma prototypes，支持 video、audio、text 访谈，也支持 100+ languages 的翻译与转录。

### 4.3 AI / 产品做什么

Listen 的 AI moderator 官方描述为：

可以 probes、adapts、follows the conversation；
会追问 why；
会根据条件指令追问；
每个 probe、quote、theme 可以回链到 interview；
用户可以检查 AI reasoning，并在不同意时编辑 coding。

这说明产品核心不是单纯「AI 总结录音」，而是把访谈主持、证据追溯、主题分析和报告生成放进一个工作流里。

### 4.4 输出什么

公开资料中可确认的输出包括：

key takeaways；
personas；
top themes；
quotes；
highlight reels；
slide decks；
executive-ready reports；
stakeholder-ready memos；
可复用的研究知识库或跨研究分析能力。

### 4.5 用户为什么觉得有价值

对研究团队：减少招募、排期、主持、转录、聚类和汇报的重活。
对产品团队：在功能上线前更快拿到「用户为什么这么想」的证据。
对品牌 / 市场团队：在创意、概念、品牌感知变化上更快做测试。
对管理层：不是只看问卷数字，而是能看到用户原话、视频片段和结构化结论。

### 4.6 哪些地方仍未验证

AI moderator 的访谈质量是否稳定超过人类研究员；
样本身份和质量是否可长期保证；
客户是否持续续约，而不只是尝鲜项目；
研究结果是否真正影响企业决策；
中国客户是否愿意为 AI 深访支付企业级价格；
中国现有问卷 / 样本 / 协作平台是否能快速复制核心功能。

## 5. 商业模式假设

### 5.1 官方披露

官方已披露的商业模式线索：

官网主路径包含 Book a Demo；
官网提供 Try It 或 AI Personality Test 入口；
官网强调 end-to-end research platform、participant pool、AI-moderated interviews、instant results；
founders letter 称最新融资后总融资达到 100 million dollars，且自 launch 九个月以来 annualized revenue 增长 15x、interviewed more than one million people；
官网未在本次检索中发现透明公开的标准价格页；
Trust Center 显示 Listen Labs 维护 SOC 2 Type II、GDPR、ISO 42001 等合规状态，但证书细节需要申请访问或进一步核验。

初步判断：官方更像 enterprise demo / sales-led，而不是完全自助 PLG。

### 5.2 第三方 / 投资方披露

第三方与投资方线索：

VentureBeat 2026-01-16 报道 Listen Labs 完成 6900 万美元 Series B，估值 5 亿美元，总融资 1 亿美元，年化收入 9 个月增长 15x 至 eight figures，并进行了超过 100 万次 AI-powered interviews；
VentureBeat 报道其流程包括 create a study、recruit participants from a global network of 30 million people、AI moderator conducts interviews、results packaged into executive-ready reports；
Sequoia 2025-04-23 文章称 Listen 由 Alfred Wahlforss 和 Florian Juengermann 创立，并称 Sequoia 领投 seed 和 Series A；
Fortune 2025-04-23 报道 Listen Labs 当时宣布融资 2700 万美元，称其可同时运行数千个 voice interviews；
Greenbook 目录称 Listen Labs 是 AI-powered qualitative research platform，pricing details 包含 annual subscription 和 monthly subscription，并列出 SOC2 Type II Secure、Fraud-Screened Participants 等卖点。

其中 Sequoia、Pear、Ribbit 等投资方或投资相关披露存在立场偏差；独立媒体报道也需要继续交叉核对。融资、ARR、估值、样本规模、访谈数可以作为线索，不能直接当成产品效果证明。

### 5.3 本次逻辑推断

本次商业模式假设：

更可能是 企业级年度订阅 + 研究项目使用量 + 样本 / panel 成本 + 高价值报告交付；
客户预算可能来自 consumer insights、UX research、product research、brand research、market research、customer experience 等部门；
样本成本、AI 访谈成本、报告生成成本、企业销售成本会共同决定毛利；
如果研究库能沉淀在企业内部，可能形成续约和扩张；
如果只是单次项目制报告，则更接近传统市场研究外包的 AI 化，增长飞轮会弱。

中国版的关键不是「AI 能不能访谈」，而是：

中国企业是否愿意为「AI 深访 + 样本质量 + 可追溯证据链 + 可进决策会的报告」支付显著高于普通问卷工具的价格。

该付费意愿目前未确认 / 待深度研究员补证据。

## 6. 增长与分发

### 6.1 初判

ListenLabs 更像：

企业销售：强；
案例驱动：强；
投资方背书：强；
产出物分发：中；
PLG：弱到中；
渠道销售：未确认。

### 6.2 企业销售

官网核心 CTA 包含 Book a Demo，Greenbook 目录也提供 REQUEST A DEMO。这更像企业客户销售流程，而不是低价自助工具。

### 6.3 案例驱动

官网展示 Microsoft、Chubbies、Simple Modern 等客户 quote。VentureBeat 报道也引用 Microsoft、Emeritus 等使用故事。

风险是：客户 quote 只能证明官方或媒体报道中的客户声称，不证明普遍 ROI，不证明续约，不证明产品长期有效。

### 6.4 投资方背书

Sequoia、Pear、Ribbit、Conviction 等投资方背书，对企业客户建立信任有帮助。
但投资方文章最多标为 B-investor，必须备注「存在立场偏差，需独立来源交叉验证」。

### 6.5 产出物分发

Listen 的报告、deck、highlight reel 可能在企业内部传播，帮助更多部门接触产品。
但这不是 Gamma 式公开产出物分发，更像企业内部证据传播。是否能转化为跨部门扩张，需要续约、席位扩张、部门扩张数据验证。

### 6.6 PLG

官网有 Try It 或 AI Personality Test 入口，但核心商业化看起来仍偏 enterprise demo / sales-led。PLG 入口可能承担体验展示和线索收集，不宜误判为低 CAC 自助增长飞轮。

## 7. 护城河初判

### 7.1 数据壁垒

初判：可能存在，但未验证为强壁垒。

如果 Listen 已经在客户企业中沉淀大量访谈记录、主题、quote、customer intelligence，并能持续被跨团队查询和复用，则数据壁垒来自客户自己的研究库，而不是通用模型本身。

但当前公开资料主要来自官网、投资方和媒体报道。尚缺：

客户研究库沉淀量；
续约率；
同一企业跨部门扩张率；
研究结果复用频率；
客户迁移成本案例。

因此数据壁垒暂标 C。

### 7.2 样本 / panel 壁垒

初判：可能是关键壁垒之一，但需重点核验。

VentureBeat 报道称 Listen 从 3000 万人的 global network 招募 participants。官网称可使用 B2B / B2C participant pool，也可接入客户自有 provider 或客户自有用户。

样本 / panel 壁垒成立需要满足：

样本身份可验证；
B2B 受访者质量可靠；
反作弊有效；
成本可控；
跨国家 / 语言 / 行业可扩展；
企业客户信任样本来源。

如果这些成立，ListenLabs 的壁垒会强于单纯 AI moderator。如果样本质量无法稳定，产品会退化成「AI 包装的调研外包」。

### 7.3 研究方法论壁垒

初判：中等。

Listen 的差异点在于 AI moderator 的自适应追问、访谈证据可追溯、主题分析、报告生成。
但 UserTesting、Maze、Great Question、Outset、Strella、Marvin、Qualtrics 等平台均可能加入 AI moderation 和 AI analysis。方法论壁垒如果只停留在「AI 会追问」，很容易被复制；如果结合研究工作流、企业内研究库、样本质量和审计能力，壁垒才会增强。

### 7.4 企业信任 / 合规壁垒

初判：重要。

ListenLabs Trust Center 显示 SOC 2 Type II、GDPR、ISO 42001 等合规状态。对于 Microsoft、金融、医疗、消费品牌等客户，数据安全和隐私合规会影响采购。

但合规不是独占壁垒。成熟 SaaS 公司也可以补齐。它更像进入企业客户的门槛，而不是长期不可复制护城河。

### 7.5 是否容易被现有平台复制

UserTesting / Maze / Qualtrics / Great Question 等海外平台

复制风险：中高。

这些平台已有研究用户、企业客户、研究流程、样本或 repository 基础。它们补 AI interviewer、自动报告、研究库搜索，比从零建立企业信任更容易。

问卷星 / 腾讯问卷 / 飞书 / 腾讯问卷等中国平台

复制风险：功能层高，完整体验层中。

公开资料显示：

问卷星已有 AI 创建、AI 追问、AI 报告等能力；
腾讯问卷定位为 AI 调研平台，并有问卷设计、数据收集、统计分析和样本服务；
腾讯云页面披露腾讯问卷样本库超 300 万真实样本、100+ 用户画像标签；
飞书有产品调研问卷模板、问卷收集和数据分析能力。

因此中国机会不应被描述为「完全空白」。更准确的说法是：

中国已有问卷、样本和协作基础设施，但「AI 深访 + 可验证样本 + 企业级证据链 + 可进决策会的报告」是否已有成熟玩家，仍需深度研究员专项扫描。

## 8. 失败模式初判

### 8.1 FM008｜竞品快速复制

FM 编号 / 名称：FM008，竞品快速复制
为什么可能命中：Listen 可见功能包括 AI moderator、自动分析、报告生成、样本招募、研究库。已有 UX research、问卷、样本、协作平台可以补这些功能。尤其中国的问卷星已经公开 AI 创建、AI 追问、AI 报告，腾讯问卷也公开 AI 调研平台与样本服务。
触发条件：
UserTesting、Maze、Qualtrics、问卷星、腾讯问卷、飞书等在 3 到 6 个月内推出可用 AI 深访与自动报告；
新进入者没有样本、研究方法、合规、客户信任差异；
客户认为现有工具「够用」，无需迁移到独立 AI 深访平台。
如何验证：
做竞品表，逐项检查 AI moderator、video / audio / text、panel、反作弊、报告生成、研究库、合规、企业客户案例；
在中国至少访谈 10 位产品 / 用户研究 / 品牌负责人，问他们是否已经使用问卷星 / 腾讯问卷 / 飞书的 AI 能力；
检查国内是否已有「AI 深访」「AI 用户访谈」「AI 调研平台」创业公司。

### 8.2 FM015｜无飞轮增长依赖

FM 编号 / 名称：FM015，无飞轮增长依赖
为什么可能命中：如果 Listen 只是每次重新销售项目、重新招募样本、重新生成报告，那么它是企业销售漏斗，不是自增强飞轮。真正飞轮需要研究库越用越有价值、同一客户更多团队加入、访谈数据降低下一次研究成本。
触发条件：
客户按项目使用，不续约年度订阅；
报告看完即走，研究库没有复用；
停止销售投入后新增客户停滞；
同一企业内没有跨部门扩张；
样本成本随使用量线性增长，规模没有带来明显成本下降或质量提升。
如何验证：
追问 annual retention、net revenue retention、同客户季度研究次数；
追问 Mission Control 或 research library 的查询频率；
找客户访谈确认报告是否进入决策会；
对比是否存在「一次研究让下一次研究更便宜、更准、更快」的机制。

### 8.3 FM014｜市场规模误判

FM 编号 / 名称：FM014，市场规模误判
为什么可能命中：美国市场研究、UX research、consumer insights 预算不等于中国企业愿意为 AI 深访支付企业级价格。中国可能有需求，但被低价问卷、微信群访谈、销售转述、外包调研、老板直觉替代。
触发条件：
中国企业认可「有用」，但只愿意低价试用；
预算归属不清，产品、市场、品牌、用户研究、数据部门互相推；
企业对 AI 访谈质量不信任；
样本质量和隐私合规成为采购阻力；
高客单价无法覆盖销售与样本成本。
如何验证：
访谈 15 到 20 个中国潜在客户，包括 B2B SaaS、消费品牌、电商、出海团队；
问过去 12 个月做过几次用户访谈、每次花多少钱、预算在哪个部门；
给出明确报价，验证是否愿意预付；
找 3 个愿意付费的最小客户，而不是只收集「感兴趣」反馈。

## 9. 中国机会初判

### 9.1 中国有没有类似需求

有类似需求，但强度和付费能力未确认。

中国的产品团队、消费品牌、电商商家、教育公司、企业服务公司、出海团队都需要更快知道：

用户为什么买；
用户为什么不买；
客户为什么流失；
新功能是否值得做；
广告创意是否有效；
新市场用户和原市场用户有何差异。

但「有需求」不等于「愿意为 AI 深访高价付费」。当前需要深度研究员补中国付费证据。

### 9.2 中国用户现在怎么解决

公开可确认的替代路径包括：

问卷星：问卷、考试、满意度、AI 创建、AI 追问、AI 报告、样本服务；
腾讯问卷：AI 调研平台、问卷设计、数据收集、统计分析、样本服务；
飞书问卷 / 飞书多维表格：问卷收集、产品调研模板、数据协作与分析；
微信群 / 社群 / 私域访谈；
销售、客服、客户成功转述；
人工深访；
传统市场调研公司；
用户研究外包；
产品经理直接约客户电话。

因此，中国不是「调研工具空白」，而可能是「定性深访速度、样本质量、研究证据链、AI 分析报告」这几个环节存在升级机会。**更准确地说：ListenLabs 中国版更像「问卷速度 + 访谈深度 + 可审计报告」的升级战，而不是「完全空白市场」；「问卷工具多」也不等于「无机会」。**

### 9.3 可能的第一切口

不建议第一步做「所有企业的 AI 用户研究平台」。更合理的切口可能是：

切口 A：B2B SaaS 功能验证与流失访谈
目标用户：产品经理、用户研究负责人、客户成功负责人；
场景：新功能上线前验证、流失客户访谈、销售异议归因；
优点：问题高频，离收入近；
风险：B2B 样本招募难，客户身份验证难。
切口 B：消费品牌新品概念 / 广告创意测试
目标用户：品牌市场部、消费者洞察团队、电商运营；
场景：新品概念、广告素材、包装、定价、购买动机；
优点：预算更接近市场研究；
风险：样本质量、低价问卷替代、品牌方信任门槛。
切口 C：出海团队多语言用户访谈
目标用户：跨境电商、出海 SaaS、游戏、教育、消费硬件；
场景：进入新市场前做多语言用户访谈；
优点：国内现有工具在跨语言深访和海外样本上可能不足；
风险：海外样本、隐私合规、支付和交付复杂。

### 9.4 最容易误判的地方

把「AI 可以访谈」误判成「客户愿意付高价」；
把「美国融资和 ARR」误判成「中国也能复制」；
把官网客户 quote 当成 ROI 证明；
把问卷星 / 腾讯问卷 / 飞书只看成问卷工具，低估它们补 AI 深访的速度；
低估样本质量、B2B 身份验证、反作弊、隐私合规；
低估中国企业研究预算弱、老板直觉强、销售转述替代用户研究的现实。

### 9.5 是否需要先交给深度研究员 GPTS

结论：需要。

原因：

中国直接竞品未系统扫描；
中国付费意愿没有访谈证据；
官方价格和商业模式细节不充分；
独立客户效果证据不足；
失败反例和用户投诉证据不足。

## 10. 四路决策初判

### 10.1 初判

**观察 + 工具**；**复制**作为待验证选项，**暂不押注**。**代理暂不建议。**

（说明：不进入最终押注结论；复制路径须先完成中国与付费证据验证。）

### 10.2 复制

暂不直接判定「复制」。
复制的前提是验证中国客户愿意为 AI 深访付费，并确认现有问卷 / 样本 / 协作平台没有快速补齐这个能力。

触发复制条件：

中国直接竞品少，且未形成强势平台；
至少 3 个潜在客户愿意为 MVP 预付；
样本招募和反作弊有可执行方案；
企业合规和数据安全门槛能过；
MVP 能在一个垂直场景中比问卷星 / 腾讯问卷 / 飞书明显更好。

### 10.3 工具

适合作为 SK 自用工具或方法论参考：

用 AI 快速做用户访谈；
用 AI 把访谈证据转成可给决策者看的报告；
用「用户原话 + 视频片段 + 主题聚类」增强产品构思可信度；
做 MTP 招募时，用小规模访谈验证「那个卡住的人」。

### 10.4 代理

暂不建议优先走代理。
原因是该类产品涉及样本、数据、隐私、企业采购、本地调研习惯。代理销售本身不能解决本地样本和合规问题。

### 10.5 观察

应持续观察：

ListenLabs 是否继续增长；
是否公布更多客户案例和续约数据；
UserTesting / Maze / Qualtrics / 问卷星 / 腾讯问卷是否推出同类 AI 深访；
中国是否出现 AI 深访创业公司；
企业研究预算是否从问卷 / 外包迁移到 AI 深访平台。

## 11. 资料充分性闸门

| 资料类别 | 当前状态 | 是否充分 | 备注 |
|----------|----------|----------|------|
| 1. 官网定位与功能说明 | 已找到官网、AI moderator 页面、founders letter | 基本充分 | 官网功能说明较完整，但属于 A-claim。 |
| 2. 创始人 / 团队信息 | 已找到 Sequoia、VentureBeat、Research Live 等线索 | 部分充分 | 需要 LinkedIn、公司注册、团队规模进一步核验。 |
| 3. 融资或收入线索 | 已找到官方 founders letter、VentureBeat、Pear、FinSMEs 等线索 | 部分充分 | Series B、总融资、ARR 增长、访谈量等仍需独立交叉验证。 |
| 4. 客户案例或使用场景 | 官网、VentureBeat、Greenbook 有 Microsoft、Chubbies、Sweetgreen、Emeritus 等线索 | 部分充分 | 目前仍多为官方或媒体引用，缺独立 ROI / 续约证据。 |
| 5. 定价 / 商业模式线索 | Greenbook 显示 annual / monthly subscription，官网 demo 导向 | 不充分 | 未找到官方透明价格页、合同结构、客单价、样本成本。 |
| 6. 竞品或替代方案 | 已初步识别海外与中国替代路径 | 部分充分 | 需要系统竞品表。 |
| 7. 失败风险 / 反例 | 仅有逻辑推断、Reddit 问价和 AI moderator 讨论线索 | 不充分 | 缺客户流失、退款、不续约、研究员抵触证据。 |
| 8. 中国竞品或中国替代路径 | 已找到问卷星、腾讯问卷、飞书等替代路径 | 不充分 | 缺中国 AI 深访直接竞品扫描和真实客户访谈。 |

**结论：**

**暂不允许进入标准 10 维度初拆。**

缺失至少 3 类关键资料：定价 / 商业模式线索不充分；失败风险 / 反例不充分；中国直接竞品与付费意愿不充分；独立客户效果证据仍不充分。

本稿只能作为轻量初拆和深度研究任务输入。**当前仅宜轻量初拆 + 深度研究指令**；在完成证据补全与 Claude / SK 工作台审核前，不启动标准 10 维深拆流水线。

---

## 12. 外部证据账本

| 断言 | 来源名称 | URL / 文件路径 | 证据等级 | 备注 |
|------|----------|------------------|----------|------|
| SK README 最后更新为 2026-05-02，并将深度底稿、case-cards、产品对标库、执行状态总表列为关键入口 | SK README.md | `MRYGP/SK/README.md` | Internal-status | 只证明仓库内部索引状态。 |
| 执行状态总表更新日期为 2026-05-02 | SK 执行状态总表 | `MRYGP/SK/ops/执行状态总表.md` | Internal-status | 只证明仓库内部状态。 |
| 执行状态总表公开页面内查找 ListenLabs、listenlabs、Listen Labs 未命中 | SK 执行状态总表 | `MRYGP/SK/ops/执行状态总表.md` | Internal-status | 公开页面查找未命中，不等于全仓库 grep 闭环。 |
| 产品对标库已于 2026-04-26 降级为档案，最后更新 2026-04-12 | SK 产品对标库 | `MRYGP/SK/cases/2026/产品对标库-38个AI产品复制价值排名.md` | Internal-status | 该文件只能作原始线索。 |
| ListenLabs 在产品对标库中为 A级 #5，初判复制，状态待分析 | SK 产品对标库 | `MRYGP/SK/cases/2026/产品对标库-38个AI产品复制价值排名.md` | Internal-status | 只证明 SK 内部早期判断，不证明外部市场事实。 |
| case-cards 未发现 ListenLabs 案例卡 | SK case-cards | `MRYGP/SK/cases/2026/case-cards.md` | Internal-status | 公开页面查找未命中。 |
| case-index 未发现 ListenLabs 条目，已列深度底稿中不含 ListenLabs | SK case-index | `MRYGP/SK/cases/2026/case-index.md` | Internal-status | 公开页面查找未命中。 |
| 深度底稿公开目录未列出 ListenLabs 相关文件 | SK 深度底稿目录 | `MRYGP/SK/cases/2026/深度底稿/` | Internal-status | 公开目录页未命中。 |
| GitHub code search 未登录不可访问，无法完成 authenticated code search | GitHub Code Search | `https://github.com/search?q=repo%3AMRYGP%2FSK+ListenLabs&type=code` | Internal-status | 需要 Claude / SK 工作台用本地 grep 或 GitHub API 复核。 |
| Listen 自称是 end-to-end research platform，客户用 AI-moderated interviews 替代 surveys、focus groups、in-depth interviews | Listen Labs 官网 | `https://listenlabs.ai/` | A-claim | 官网宣传，只证明官方声称。 |
| Listen 官网列出 Brand Tracker、Usability Testing、Multi-Market Segmentation、Concept Testing、Consumer Journey Map、Creative Testing 等 use cases | Listen Labs 官网 | `https://listenlabs.ai/` | A-claim | 官网宣传。 |
| Listen 官网称可生成 key takeaways、personas、top themes，可招募 B2B / B2C participants，可支持 100+ languages、videos、images、Figma prototypes、video / audio / text | Listen Labs 官网 | `https://listenlabs.ai/` | A-claim | 官网功能声明。 |
| Listen AI Moderator 页面称 AI moderator 可 probes、adapts、follows the conversation，并支持 smart adaptive probes 与 fully traceable 回链 | Listen AI Moderator 页面 | `https://listenlabs.ai/features/ai-moderator` | A-claim | 官网功能声明。 |
| Listen founders letter 称 launch 九个月以来 annualized revenue 增长 15x，interviewed more than one million people，总融资达到 100 million dollars | Listen founders letter | `https://listenlabs.ai/founders-letter` | A-claim | 官方声明，需独立交叉验证。 |
| Listen founders letter 称最新轮由 Ribbit Capital 领投，Evantic、Sequoia、Conviction、Pear VC 参与 | Listen founders letter | `https://listenlabs.ai/founders-letter` | A-claim | 官方声明。 |
| VentureBeat 报道 Listen Labs 于 2026-01-16 完成 6900 万美元 Series B，估值 5 亿美元，总融资 1 亿美元 | VentureBeat | `https://venturebeat.com/technology/listen-labs-raises-usd69m-after-viral-billboard-hiring-stunt-to-scale-ai` | B | 独立媒体报道，需与官方和投资方交叉核对。 |
| VentureBeat 报道 Listen 的流程包括创建 study、从 3000 万 global network 招募 participants、AI moderator 访谈、输出 executive-ready reports | VentureBeat | `https://venturebeat.com/technology/listen-labs-raises-usd69m-after-viral-billboard-hiring-stunt-to-scale-ai` | B | 对产品机制的第三方报道。 |
| VentureBeat 报道 Microsoft 使用 Listen 收集全球用户故事，传统流程需 6 到 8 周，Listen 可在一天内收集用户视频故事 | VentureBeat | `https://venturebeat.com/technology/listen-labs-raises-usd69m-after-viral-billboard-hiring-stunt-to-scale-ai` | B | 媒体引用客户说法，不等于普遍 ROI。 |
| Sequoia 文章称 Listen 由 Alfred Wahlforss 和 Florian Juengermann 创立，Sequoia 领投 seed 和 Series A | Sequoia | `https://sequoiacap.com/article/partnering-with-listen-labs-next-level-customer-obsession/` | B-investor | 投资方文章，存在立场偏差，需独立来源交叉验证。 |
| Pear VC 称 Listen Labs 2026 年完成 Series B，总融资达到 1 亿美元，9 个月 annualized revenue 增长 15x | Pear VC | `https://pear.vc/listen-labs-series-b/` | B-investor | 投资方披露，存在立场偏差，需独立来源交叉验证。 |
| Fortune 2025-04-23 报道 Listen Labs 宣布融资 2700 万美元，可同时运行数千个 voice interviews | Fortune | `https://fortune.com/article/ai-startup-listen-labs-sequoia-27-million-funding/` | B | 独立媒体报道，但需核对全文可访问性。 |
| Greenbook 将 Listen Labs 描述为 AI-powered qualitative research platform，并列出 annual subscription 与 monthly subscription | Greenbook | `https://www.greenbook.org/company/Listen-Labs` | B | 行业目录，可作商业模式线索，不足以确认价格。 |
| Greenbook 称 Listen Labs trusted by Google & Microsoft，SOC2 Type II Secure，Fraud-Screened Participants，50+ Languages | Greenbook | `https://www.greenbook.org/company/Listen-Labs` | B | 行业目录声明，需进一步验证。 |
| Listen Labs Trust Center 显示 SOC 2 Type II、GDPR、ISO 42001 等合规状态 | Listen Labs Trust Center | `https://trust.listenlabs.ai/` | A-claim | Trust Center 声明，证书细节需申请访问或进一步核验。 |
| User Intuition 竞品对比文称 Listen Labs 偏 consultant-led enterprise motion，并给出 base + session cost 等价格估算 | User Intuition | `https://www.userintuition.ai/reference-guides/listen-labs-pricing-vs-user-intuition-2026-comparison/` | C | 竞品来源，强偏置；非定价事实，须独立验证。 |
| 问卷星 AI 助手支持 AI 创建、AI 追问、AI 交互、AI 分享文案、AI 报告等能力 | 问卷星 AI 助手 | `https://www.wjx.cn/app/themehtml/wjxai.aspx` | A-claim | 中国替代路径线索。 |
| 腾讯问卷定位为 AI 调研平台，提供问卷设计、数据收集、统计分析能力 | 腾讯问卷官网 | `https://wj.qq.com/` | A-claim | 中国替代路径线索。 |
| 腾讯云页面称腾讯问卷样本库超 300 万真实样本、100+ 用户画像标签，回收 1000 份问卷最快 1 天内完成 | 腾讯云腾讯问卷产品页 | `https://cloud.tencent.com/product/survey` | A-claim | 中国样本服务线索。 |
| 飞书产品调研问卷模板可用于产品市场调研、收集市场信息、指导产品开发和改进 | 飞书产品调研问卷模板 | `https://www.feishu.cn/template/product-research-survey` | A-claim | 中国替代路径线索。 |
| 中国可能存在 AI 深访机会，但不能直接说「可以做」 | 本稿逻辑推断 | 无单一外部 URL | C | 中国可复制默认 C，必须访谈验证。 |
| 中国客户愿意为 AI 深访支付高价 | 本稿未确认断言 | 无可核对外部 URL | X | 当前不能作为决策依据，需深度研究员补证据。 |
| ListenLabs 产品真实有效并能稳定带来 ROI | 本稿未确认断言 | 无可核对独立 ROI 来源 | X | 不能把官网宣传、投资方披露或客户 quote 当作效果证明。 |

## 13. 发现的 SK 内部状态问题

- `cases/2026/产品对标库-38个AI产品复制价值排名.md` 已降级为档案，但仍保留早期进度表；**产品对标库不能单独判断当前状态**；该表对 ListenLabs 的「待分析」可以作为线索，不能作为当前状态最终依据。
- **深度底稿目录**已出现 `11x-对标分析.md`、`Spangle-拆解底稿.md`、`Cactus-拆解底稿.md` 等文件，但**产品对标库与 case-index 同步不完全**；须与 `ops/执行状态总表.md`、深度底稿目录交叉。
- **本次 GitHub authenticated code search 未闭环**；不能宣称全仓库无 ListenLabs 命中。
- ListenLabs 是否真的未拆，需要 Claude / SK 工作台用本地 grep 或 GitHub API 搜索以下关键词复核：

```
ListenLabs
listenlabs
Listen Labs
Listen
AI user interview
AI research platform
AI用户访谈
AI调研平台
```

## 14. 深度研究员补齐清单

请深度研究员 GPTS 不做最终判断，只补证据：

### 14.1 官方资料

官网首页、产品页、AI moderator 页面、founders letter、Trust Center；
是否有 pricing 页面；
是否有 security whitepaper；
是否有 docs、API、workflow、case study；
是否有正式客户案例全文。

### 14.2 创始人 / 团队

Alfred Wahlforss 的 LinkedIn、访谈、过往创业经历；
Florian Juengermann 的 LinkedIn、访谈、技术背景；
公司成立时间、团队规模、招聘岗位；
是否确实源自 Harvard 期间 consumer app 与早期用户研究需求。

### 14.3 融资 / 收入

核对以下说法：

2025 年融资 2700 万美元；
2026 年 Series B 融资 6900 万美元；
总融资 1 亿美元；
估值 5 亿美元；
9 个月 annualized revenue 增长 15x；
eight-figure ARR；
interviewed more than one million people；
global network / panel 3000 万人。

要求至少找到官方声明、独立媒体、投资方披露三类来源，并标注冲突。

### 14.4 客户案例

优先核验：

Microsoft；
Sweetgreen；
Chubbies；
Simple Modern；
Emeritus；
Google；
Nestlé；
SKIMS；
Canva；
Perplexity。

要找：

非官网、非投资方证据；
客户具体使用场景；
ROI、节省时间、续约、扩张、采购评价；
负面反馈或限制。

### 14.5 定价 / 商业模式

要找：

官方定价；
客户采购讨论；
G2 / Reddit / UXResearch 社群价格讨论；
年费区间；
每场访谈 / 每份样本 / 每项目是否另收费；
是否按 seats、studies、minutes、participants、enterprise contract 计费。

### 14.6 竞品

海外竞品：

UserTesting；
Maze；
Qualtrics；
Great Question；
Outset；
Strella；
Conveo；
Marvin；
Dscout；
Voxpopme；
Userology；
User Interviews；
User Intuition。

中国竞品 / 替代路径：

问卷星；
腾讯问卷；
飞书问卷；
问卷网；
倍市得；
传统市场调研公司；
UX research 外包团队；
AI 深访 / AI 调研创业公司。

### 14.7 失败风险 / 反例

要找：

AI moderator 访谈质量争议；
受访者欺诈；
样本质量问题；
客户不续约；
研究员抵触；
隐私合规风险；
企业数据不能外发；
研究结果误导决策；
AI 访谈对敏感话题的偏差。

### 14.8 中国付费验证

至少访谈或找到公开证据回答：

中国产品 / 品牌 / 用户研究团队过去一年做过几次深访；
每次预算多少；
当前用什么工具；
是否愿意为 AI 深访付费；
可接受价格；
谁是采购决策人；
数据安全要求；
是否愿意让 AI 访问用户视频 / 音频 / 文本；
哪个垂直切口最可能先付费。

## 15. Claude / SK 工作台审核提示词

请审核这份 ListenLabs / Listen 轻量初拆，不要把它当成公众号稿，也不要直接宣布入库。请重点挑事实错误、状态错误、证据等级错误和中国机会误判。

产品：ListenLabs / Listen  
初拆版本 / 日期：v0.2 · 2026-05-02  
建议保存路径：cases/2026/深度底稿/ListenLabs-轻量初拆.md

请按以下顺序审核：

1. Step 0 状态复核
   - 用本地 grep 或 GitHub API 搜索 MRYGP/SK 全仓库：
     ListenLabs
     listenlabs
     Listen Labs
     Listen
     AI user interview
     AI research platform
     AI用户访谈
     AI调研平台
   - 重点检查：
     ops/执行状态总表.md
     cases/2026/case-cards.md
     cases/2026/case-index.md
     cases/2026/深度底稿/
   - 判断 ListenLabs 是否真的未拆。
   - 如果已有底稿或案例卡，请停止入库，不要重复拆。

2. 内部状态一致性
   - 产品对标库已降级为档案，不能单独作为当前状态来源。
   - 检查本稿是否错误使用产品对标库来判断当前状态。
   - 检查 case-index、case-cards、深度底稿目录之间是否有冲突。

3. 外部证据可靠性
   - 检查每条外部事实是否有 URL。
   - 检查官网宣传是否只标 A-claim。
   - 检查 Sequoia、Pear、Ribbit 等投资方披露是否只标 B-investor，并备注立场偏差。
   - 检查 VentureBeat、Fortune、Greenbook、FinSMEs 等第三方报道是否准确。
   - 检查融资、ARR、估值、访谈量、panel 规模是否被过度当成产品效果证明。
   - Series B 领投与轮次口径以 **A-claim**（如 founders letter / 官方新闻稿）为优先；Pear、Sequoia 等投资方材料仅标 **B-investor**，勿与独立 **B** 媒体混标；勿将 Sequoia 误写为 Series B 领投（本稿证据账本已采 Ribbit 领投 B 口径）。

4. 官网宣传误读
   - 特别检查本稿是否把 Microsoft、Chubbies、Sweetgreen、Emeritus 等客户 quote 当作 ROI 证明。
   - 客户 quote 最多证明客户声称，不证明普遍有效、不证明续约、不证明可复制。

5. 产品机制判断
   - ListenLabs 的核心是否真是 AI moderator + 样本 + 分析 + 报告 + 研究库。
   - 是否遗漏了 Research Agent、Mission Control、fraud detection、synthetic users 等关键能力。
   - 这些能力哪些有官方证据，哪些只有媒体或投资方证据。

6. 中国机会校准
   - 检查本稿是否过度乐观。
   - 中国不是调研工具空白，问卷星、腾讯问卷、飞书已有问卷、样本、AI 创建、AI 追问、AI 报告等能力。
   - 需要判断真正空白是否是「AI 深访 + 可验证样本 + 企业级证据链 + 可进决策会的报告」。
   - 检查中国客户愿意付费是否仍是 X / C，不允许当成已验证事实。

7. 失败模式
   - 审核 FM008、FM015、FM014 是否选择合理。
   - 如认为 FM003 伪需求、FM007 API依赖、FM009 合规政策风险更关键，请指出替换建议。
   - 每个 FM 是否写了为什么可能命中、触发条件、如何验证。

8. 资料充分性闸门
   - 当前是否缺少 3 类以上资料。
   - 是否应维持「暂不允许进入标准 10 维度初拆」。
   - 如允许进入标准 10 维，请列出已经补齐的证据。

9. 输出审核结论
   - ListenLabs 是否真的未拆；
   - 本稿哪些断言证据不足；
   - 哪些判断过度乐观；
   - 是否需要先交给深度研究员 GPTS；
   - 是否允许进入标准 10 维深拆；
   - 是否允许保留为轻量初拆底稿。

请不要宣布入库，不要宣布仓库已更新。只输出审核意见和需要修改的地方。

## 16. 下一步最小动作

Claude / SK 工作台先用本地 grep 或 GitHub API 复核 ListenLabs 是否真的未拆；
若确认未拆，将本文件保存为 cases/2026/深度底稿/ListenLabs-轻量初拆.md；
不要立刻进入标准 10 维度深拆；
先交给深度研究员 GPTS 补齐五类证据：
官方定价 / 商业模式；
独立客户效果；
中国直接竞品；
中国付费意愿；
失败反例 / 用户投诉 / 研究员抵触；
补证据后再由 Claude / SK 工作台判断是否进入标准 10 维度初拆。
