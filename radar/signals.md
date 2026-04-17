# AI产品雷达 · 信号源清单（v1 · 合并完整版）

> 首版纯清单：2026-03-26  
> 合并升级：2026-04-16 — 在原有三梯队 + 垂直源之上，**显式合并「L1 四入口自动雷达」与「L2 广谱人工/半自动信号」**  
> **本文件 `radar/signals.md` 为唯一正式版**；旧版仅含三梯队的那份清单已停用，临时文件名 `signalsV1` 已弃用，全文以本文件为准。

---

## 架构说明：雷达引擎 + 机会放大器

**一句话**：「四入口」适合做**雷达引擎**（feed / RSS 类、结构稳定、适合长期自动化）；**原信号源体系**（下文的梯队 + 中文平台 + 垂直源）适合做**机会放大器**（覆盖更广、中文与行业更深、维护成本更高）。**合并后效果最好。**

| 层级 | 角色 | 内容 |
|------|------|------|
| **L1** | 自动雷达底盘 | 本节「第零层」四入口：定时拉取 → 去重 → 初筛 → 写入 `radar/product-radar.md` |
| **L2** | 机会放大器 | 第一 / 第二 / 第三梯队 + 垂直方向专用源：人工刷、豆包转写、Studio 深度扫 |

执行顺序建议：**先跑 L1 不漏底盘**，再用 L2 做**周度补捞**；强信号仍适用文末「多源交叉验证」规则。

---

## 第零层（L1）· 自动雷达引擎：四入口

> ⚠️ **当前状态**：自动化管线尚未启动（见 `meta/产品雷达-自动化方案.md`、`ops/执行状态总表.md`）。  
> L1 四个入口目前仍由实习生 A/B **手动扫描**（或 Studio 粘贴 URL）；下表「机器订阅」列为 **待接入** 的目标形态，避免误以为已有脚本在跑、可不再盯 PH。

> 主口径：**Product Hunt AI**、**Product Hunt Developer Tools**、**HN Launches** 为主；**HN Show** 为补充观察源（社区作品多、噪声更大）。

| 入口 | 人类 / AI Studio 入口 | 机器订阅（RSS，自动化推荐） | 口径 |
|------|------------------------|-----------------------------|------|
| Product Hunt AI | https://www.producthunt.com/topics/artificial-intelligence | 以你们管线实际绑定的 **feed / API** 为准（Product Hunt 对匿名抓取常有限制，勿在未验证环境下写死易 403 的 URL） | **主源** |
| Product Hunt Developer Tools | https://www.producthunt.com/topics/developer-tools | 同上 | **主源** |
| HN Launches（Launch HN） | https://news.ycombinator.com/launches | https://hnrss.org/launches | **主源** |
| HN Show（Show HN） | https://news.ycombinator.com/show | https://hnrss.org/show | **补充观察** |

**说明**：HN 两行 RSS 来自 [hnrss.org](https://hnrss.github.io/) 公开文档；刷新频率请保守，避免给聚合服务过大压力。Product Hunt 的机器路径见设计稿 `meta/产品雷达-自动化方案.md`。初筛口径统一用 `radar/产品雷达-AI-Studio扫描指令.md` **v1.3**（含 AI 硬过滤 + Q3「痛点够硬」）。

---

## 第一梯队（每天看，5分钟）

| 信号源 | 平台 | 语言 | 看什么 |
|--------|------|------|--------|
| Ben's Bites | Newsletter | 英 | 每天精选新AI产品、融资、案例 |
| @bentossell | Twitter/X | 英 | 每天盘点新AI产品和融资 |
| @levelsio | Twitter/X | 英 | 独立开发者视角，用AI做产品 |
| Product Hunt AI分类 | 网站/Twitter | 英 | 每天新发布的AI产品 |
| @heyBarsee | Twitter/X | 英 | "今天的N个AI工具"合集 |
| 猫不白 | 抖音 | 中 | 亲测AI产品后推荐，有自己判断 |

**每天操作**：看Ben's Bites邮件（2分钟）→ 刷Twitter列表（2分钟）→ 猫不白+PH扫一眼（1分钟）

> 与 L1 重叠说明：表中 **Product Hunt AI** 与「第零层」为同一源头的人类侧；L1 自动化跑的是同一批新品的机器侧，**不重复维护两套名单**，只区分「自动定时」与「人眼扫一眼」。

---

## 第二梯队（每周看，15分钟）

### 海外

| 信号源 | 平台 | 语言 | 看什么 |
|--------|------|------|--------|
| Matt Wolfe | YouTube | 英 | 系统测试新AI工具 |
| The AI Advantage | YouTube | 英 | AI工具提升效率+副业 |
| Jeff Su | YouTube | 英 | 办公效率+AI工具实战 |
| Silicon Valley Girl | YouTube | 英 | 创业+AI工具评测 |
| The Rundown AI | Newsletter | 英 | 新闻+工具推荐+实战 |
| TLDR AI | Newsletter | 英 | TL;DR格式新闻+工具 |
| @dair_ai | Twitter/X | 英 | LLM工具链，模型→工具→应用 |
| r/automation | Reddit | 英 | 自动化+AI工具实测 |
| r/artificial | Reddit | 英 | 综合AI进展+新产品 |
| r/Solopreneur | Reddit | 英 | 小团队用AI做产品的真实案例 |

### 中文平台——抖音

| 账号 | 风格 | 值得跟吗 |
|------|------|---------|
| @猫不白 | 亲测AI产品后推荐，有自己判断，质量稳定 | **值得（已进第一梯队）** |
| @Topbook | 效率工具+AI工具推荐，制作精良 | 值得 |
| @林亦LYi | AI应用实战，偏商业场景 | 值得 |
| @技术爬爬虾 | AI工具测评+教程，技术+实用结合 | 值得 |
| @Nenly同学 | AIGC工作流+新产品介绍，适合小白 | 值得 |
| @痕继痕迹 | AI工具推荐，更新稳定 | 观望 |
| @公与山河 | AI工具+效率提升 | 观望 |
| @Git源宝 | 开源+AI工具推荐 | 观望 |
| @秋芝2046 | AI工具推荐 | 观望 |

### 中文平台——小红书

| 账号 | 风格 | 值得跟吗 |
|------|------|---------|
| @AI工具库 | AI工具推荐+测评，覆盖绘画/写作/设计 | 值得 |
| @科技阿宅 | 热门+小众AI工具，通俗易懂+操作演示 | 值得 |
| @AI研究社 | 工具横向对比+进阶技巧 | 值得 |

### 中文平台——B站

| 账号 | 风格 | 值得跟吗 |
|------|------|---------|
| @AI工具研究所 | AI办公+创意工具推荐，结合实际案例 | 值得 |
| @科技猎手 | 筛选严格，只推荐验证过的AI工具 | 值得 |
| @AI干货星球 | AI工具推荐+使用教程，覆盖面广 | 值得 |

---

## 第三梯队（每月看，30分钟）

| 信号源 | 平台 | 语言 | 看什么 |
|--------|------|------|--------|
| Latent Space | Podcast | 英 | 深度访谈AI创业者和产品团队 |
| Practical AI | Podcast | 英 | AI产品落地、工具链 |
| AI Explained | YouTube | 英 | 深度解析最新AI进展 |
| Two Minute Papers | YouTube | 英 | 前沿科研/算法 |
| Crunchbase AI筛选 | 网站 | 英 | 全球AI融资事件 |
| IT桔子 | 网站 | 中 | 国内AI融资事件 |

---

## 垂直方向专用源

### AI + 银发经济

| 信号源 | 平台 | 语言 | 频率 | 一句话 |
|--------|------|------|------|--------|
| AgeClub | 微信公众号 | 中 | 每周3-5篇 | 国内银发科技垂直媒体 |
| SilverEco.org | 网站 | 英/法 | 每周 | 全球银发经济新闻，欧洲视角 |
| AgeTech Collaborative (AARP) | 网站 | 英 | 每周 | 美国AgeTech创新，AI护理/智能家居 |
| Aging and Health Technology Watch | 博客 | 英 | 每周 | 居家养老技术，点名具体产品 |
| AARP Research: Tech Trends 50+ | 研究栏目 | 英 | 每月+ | 老年人使用科技的行为数据 |
| Intralink: AgeTech Japan & Korea | 专栏 | 英 | 每月 | 日韩银发科技深度分析 |

### AI + 金融科技

| 信号源 | 平台 | 语言 | 频率 | 一句话 |
|--------|------|------|------|--------|
| FinTech Weekly | Newsletter | 英 | 每周 | 全球金融科技，AI风控和贷款 |
| FinTech Takes | Newsletter | 英 | 每周 | 深度拆解银行与FinTech，insider视角 |
| The Financial Brand | 网站 | 英 | 每周多篇 | 银行业AI专栏，一线实践 |
| FinTech Observer | Newsletter | 英 | 每周 | 数字金融+银发金融交叉 |

### AI Agent

| 信号源 | 平台 | 语言 | 频率 | 一句话 |
|--------|------|------|------|--------|
| ByteByteGo – AI GitHub Repos | Newsletter | 英 | 每周 | 最火Agent框架和GitHub仓库 |
| Agentic AI News Round-up | DEV社区 | 英 | 每周 | Agent领域论文+产品+工具汇总 |
| State of AI Agents (Pucek) | Substack | 英 | 每周 | 产品和商业视角分析Agent |
| 500-AI-Agents-Projects | GitHub | 英 | 持续 | Agent项目黄页 |

### AI + 内容创作

| 信号源 | 平台 | 语言 | 频率 | 一句话 |
|--------|------|------|------|--------|
| Buffer – AI Content Creation | 博客 | 英 | 每周 | 评测AI文案/社媒工具 |
| GetBlend – Best AI Tools | 博客 | 英 | 每月 | 内容工具横评 |

### 小团队做大产品

| 信号源 | 平台 | 语言 | 频率 | 一句话 |
|--------|------|------|------|--------|
| Indie Hackers | 网站/社区 | 英 | 每日 | 独立开发者上线/复盘/营收 |
| Pete Codes – Indie Founders | 博客/Twitter | 英 | 不定期 | 自举创始人导航 |
| Seth Rose | Twitter/X | 英 | 日更 | indie AI产品结构性观察 |
| @mixailflash | Twitter/X | 英 | 日更 | 12个月做12个产品 |

---

## 信号交叉验证规则

**被2个以上信号源同时提到的产品 → 强信号，直接进product-radar待拆解区。**

（L1 与 L2 可互相计数：例如同一产品既出现在 PH AI，又出现在 Ben's Bites，即强信号。）

---

## 操作备忘

- 订阅Ben's Bites：https://bensbites.com
- 订阅The Rundown AI：https://therundown.ai
- 订阅TLDR AI：https://tldr.tech/ai
- 订阅FinTech Weekly：https://www.fintechweekly.com
- Twitter创建"AI信号源"列表，加入第一梯队账号
- Reddit收藏r/automation、r/artificial、r/Solopreneur
- GitHub watch: 500-AI-Agents-Projects
