# SK知识库 · 三湘问道

> 最后更新：2026-04-15
> 维护者：changshayang
> 路径：D:\sk
> 身份：个人判断系统的操作系统 + AI可调用知识库

---

## 三条核心链路

> 仓库按链路使用，不按目录浏览。找文件先看这里。

### 链路一：产品雷达（发现机会）

```
信号源 → 初筛5问 → 产品库 → 待拆解队列
```

| 步骤 | 文件 |
|------|------|
| 信号源清单 | `radar/signals.md` |
| 扫描指令 | `radar/产品雷达-AI-Studio扫描指令.md` |
| 产品库（唯一入口） | `radar/product-radar.md` |
| 雷达周报 | `radar/weekly/` |

### 链路二：内容生产（释放信号）

```
选题 → 底稿 → 改写 → 第一读者检测 → 发布
```

| 步骤 | 文件 |
|------|------|
| 选题 | `北极星文档.md` + `content/公众号内容大纲-30篇规划.md` |
| 拆解底稿 | `core/product-teardown-template-v4.0.md`（10维度） |
| 写文章 | `content/article_template.md`（5种结构） + `content/公众号写作指南.md` |
| 避坑 | `content/公众号内容生产经验手册.md`（30条教训） |
| 改写 | GPTs写作工坊：`meta/写作工坊-系统指令.md` |
| 检测 | GPTs第一读者：`meta/第一读者-系统指令.md` |
| 发布 | `content/文章发布SOP.md` |

### 链路三：AI拆解（积累判断力）

```
10维度分析 → 那一刀 → 理论映射 → 四路决策 → 沉淀案例卡
```

| 步骤 | 文件 |
|------|------|
| 拆解模板 | `core/product-teardown-template-v4.0.md` |
| 推演SOP | `core/SKILL-推演SOP-v1.3.md` |
| 评估引擎 | `core/评估引擎速查版.md` |
| **产品评估决策清单** | `core/产品评估决策清单-v1.0.md` ★ 新增 |
| 理论库 | `theory/` 目录下23个DOC文件 |
| 失败模式 | `core/failure_modes.yml` |
| 铁律 | `core/三湘问道铁律.md` |
| 案例卡 | `cases/2026/case-cards.md` + `content/case-card-format-v1.0.md` |
| RRF验证库 | `cases/2026/RRF案例验证库.md` |

---

## AI快速调用入口

> 系统指令的搜索关键词表。收到任务先搜这里。

| 要做什么 | 搜什么 |
|---------|--------|
| **拆解产品** | `core/product-teardown-template-v4.0` `content/aichajie-案例模板` |
| **写文章** | `content/article_template` `content/公众号写作指南` `content/公众号内容生产经验手册`（30条教训+22条检查清单+Phase 0） |
| **选题** | `北极星文档` `content/公众号内容大纲-30篇规划` |
| **做评估** | `core/评估引擎速查版` `core/failure_modes` |
| **新产品方向过必要条件检查** | `core/产品评估决策清单-v1.0`（6必须条件+复制三层次+换题模式P1-P4） |
| **找理论** | `theory/` 目录下所有DOC文件（23个） |
| **评估商业模式是否服务真实需求/识别伪需求** | `theory/DOC-D023-伪需求陷阱`（Goodhart定律+眼镜蛇效应+三问：指标能否被单独操控/时间是期友还是敌人/消失后用户是否更好） |
| **做排除判断/入场前校准** | `core/三湘问道铁律` `theory/DOC-S079-创业者十个默认假设` |
| **推演新方向** | `core/SKILL-推演SOP-v1.3` `core/failure_modes` |
| **产品雷达** | `radar/product-radar.md`（产品库）`radar/signals.md`（信号源）`radar/产品雷达-AI-Studio扫描指令.md`（扫描指令） |
| **雷达周报** | `radar/weekly/` |
| **红队压测** | `meta/SK知识库使用方法-框架红队法.md` |
| **案例找规律** | `cases/2026/case-cards.md` `content/case-card-format-v1.0.md` |
| **变现/角色定位** | `cases/2026/角色定位与变现路径.md` |
| **产品对标/复制排名** | `cases/2026/产品对标库-38个AI产品复制价值排名.md` |
| **AI产品复制推演框架** | `core/SKILL-AI产品复制推演框架-v0.1.md` |
| **回顾底稿** | `cases/2026/深度底稿/` |
| **看进度** | `ops/执行状态总表.md`（每次开对话先看） |
| **仓库维护** | `ops/执行状态总表.md` 第一节维护触发器 |
| **实习生工作安排** | `ops/_temp-people/实习生前期.md` |

---

## 工具矩阵

| 角色 | 平台 | 指令文件 |
|------|------|---------|
| **思考Project** | Claude | `meta/CLAUDE系统指令.md` |
| **写作工坊** | GPTs | `meta/写作工坊-系统指令.md` |
| **第一读者** | GPTs | `meta/第一读者-系统指令.md` |
| **深度研究员** | 多AI轮换 | `meta/gpts-deep-researcher-design.md` |
| **产品雷达扫描** | Google AI Studio | `radar/产品雷达-AI-Studio扫描指令.md` |

日常工作流：思考Project出底稿 → 写作工坊改写 → 第一读者检测 → 发布

---

## 发布状态

```
001 ✅ 已发布    002 ✅ 已发布    003 ✅ 已发布
004 ✅ 已发布    005 ✅ 已发布    006 ✅ 已发布
007 ✅ 已发布    008 ✅ 已发布
009 ⏳ 初稿完成  010 ⏳ 初稿完成
```

---

## 仓库结构

```
D:\sk\
├── README.md                    ← 本文件（链路导航 + 总索引）
├── 北极星文档.md                ← 战略锚点
│
├── core/                        ← 稳定层：规则/模板/判断框架（10个文件）
├── theory/                      ← 稳定层：理论输入（23个文件）
├── content/                     ← 稳定层：内容模板与发布规则（10个文件）
├── meta/                        ← 稳定层：系统指令/架构设计（11个文件）
│
├── radar/                       ← 产品发现流水线（独立链路）
├── cases/2026/                  ← 案例/文章/项目/研究
├── ops/                         ← 当前运行状态
└── _archive/                    ← 已归档旧版文件
```

---

## 各文件夹详细内容

### core/（10个文件）
```
product-teardown-template-v4.0.md  10维度拆解模板
SKILL-推演SOP-v1.3.md             推演八步法
SKILL-产品设计方法论-v1.0.md       十步产品设计法
SKILL-AI产品复制推演框架-v0.1.md  ★ 海外AI产品复制/对标分析7步法
产品评估决策清单-v1.0.md           ★ 新增。6必须条件+复制三层次+换题模式P1-P4
三湘问道铁律.md                   15条排除规则
评估引擎速查版.md                 7+3步拆解法
研究员输出模板.md                 深度研究员输出结构
failure_modes.yml                 15种失败模式
evidence_levels.yml               A/B/C/X证据等级
```

### theory/（23个文件）
```
DOC-D014-财富创造的范式转移.md    DOC-D018-种树型vs种菜型.md
DOC-D021-维度跨越.md              DOC-D022-重新定义问题与飞轮构建.md ★RRF
DOC-D023-伪需求陷阱.md            ★ 拆解时校正：这个产品是否服务真实需求？
DOC-P001-财富公式.md              DOC-P002-AlphaFold推演公式.md
DOC-S003-初创企业生存法则.md      DOC-S032-破坏式创新.md
DOC-S036-规则制定者.md            DOC-S037-从0到1.md
DOC-S047-三大标杆方法论.md        DOC-S048-创业项目评估方法论.md
DOC-S061-网络效应与学习效应.md    DOC-S065-深度用户护城河.md
DOC-S070-B端杠杆.md               DOC-S071-白标SaaS与生态链杠杆.md
DOC-S074-换题思维.md              DOC-S075-精益创业.md
DOC-S076-透过现象看本质.md        DOC-S077-合理化行为分析框架.md
DOC-S078-高频业务的战略价值.md    DOC-S079-创业者十个默认假设.md
```

### content/（10个文件）
```
article_template.md                ★ 文章模板v2.0（5种结构）
case-card-format-v1.0.md           ★ 案例卡格式
公众号内容生产经验手册.md           ★ 30条教训+22条检查清单+Phase 0
公众号写作指南.md                  语言规范/禁用词/证据规则
公众号内容大纲-30篇规划.md         六拳结构
公众号与理论融合方案.md            RRF暗线设计
aichajie-案例模板-v1.0.md          案例六维度存储
案例拆解输出标准.md                三输出体系
agent3a_article.md                 讲稿改写prompt
文章发布SOP.md                     发布流程
```

### radar/（3个文件 + weekly/）
```
product-radar.md                   ★ 产品库（唯一入口，含待拆解+观察池+已拆解）
signals.md                         ★ 信号源清单（L1四入口+L2梯队/垂直/中文）
产品雷达-AI-Studio扫描指令.md      ★ 扫描Prompt×3 + URL速查表（v1.3）
weekly/                            雷达周报存档
```

### ops/（1个文件 + _temp-people/）
```
执行状态总表.md                    ★ 全局进度（含维护触发器，每次开对话先看）
_temp-people/                      实习生前期.md + 三人工作方案.md + 实习生A/B手册
```

### meta/（11个文件）
```
CLAUDE系统指令.md                    ★ 思考Project指令（无版本号，始终是最新版）
写作工坊-系统指令.md               ★ 写作GPTs指令
第一读者-系统指令.md               ★ 第一读者GPTs指令
gpts-deep-researcher-design.md     深度研究员v1.1
SK知识库使用方法-框架红队法.md     ★ 框架红队法（含实战记录）
AI拆解系统架构-v0.1.md             系统架构蓝图（含远期dimensions/patterns规划）
产品雷达-自动化方案.md             雷达自动化方案（待实现）
RRF理论发展路径.md                 理论发展6阶段
RRF理论评估指令.md                 红队攻击指令
理论库优先级清单.md                理论补充排序
changelog.md                       更新日志
```

### cases/2026/
```
文章终稿：001-008 + 自我介绍稿 + 009/010初稿
case-cards.md / case-index.md       案例卡库（6张）+ 索引
RRF案例验证库.md                   34个案例RRF验证
角色定位与变现路径.md               判断力合伙人定义
诊断问题库.md                      场景F积累
写作计划-CET内共生概念弧-30篇布局.md
产品对标库-38个AI产品复制价值排名.md  ★ 含换题模式分类（P1-P4）
产品构思-通用任务代理与副业AI助手.md
research-wechat-visibility.md       冷启动策略研究
深度底稿/                          文章底稿
深度研究报告/                      RRF红队报告（8份）
老年AI管家/                        产品设计v0.5（暂停）
```

---

## 文件命名规范

**理念型（001-003）**：`NNN-核心概念.md`
**案例拆解型（004起）**：`NNN-公司名-核心洞察.md`

三条规则：不加"终稿"、洞察写文章真正在说什么、公司名在前洞察在后。

---

## 远期演进方向

> 详见 `meta/AI拆解系统架构-v0.1.md`

当案例卡积累到5-8张时，启动：
- `dimensions/dimension-registry.yml`（维度注册表，从理论中提取结构化判断维度）
- `patterns/patterns.yml`（跨案例模式库，从案例中涌现规律）

触发条件见架构文档Phase 0。当前不建，等案例积累。

**注：P1-P4换题模式是 patterns.yml 的前身**——当前用自然语言存在 `core/产品评估决策清单-v1.0.md` 第四节，积累到10个模式后迁入结构化 YAML。

---

## 与其他仓库的关系

| 名称 | 位置 | 角色 |
|------|------|------|
| **SK知识库** | D:\sk | 操作系统（本仓库） |
| **三湘问道理论库** | E:\sanxiangwendao | 弹药库（90+篇理论文档） |
| **CET理论库** | E:\CEET | 认知内共生理论（与30篇规划关联） |
| **GitHub同步** | github.com/MRYGP/SK | 远程备份（实习生通过此访问全部文件） |

---

## 维护规则

详见 `ops/执行状态总表.md` 第一节「维护触发器」。

简要原则：每次开新对话先看执行状态总表 → 每次对话结束前过一遍维护触发器 → 过时文件移到_archive/ → 更新日志写meta/changelog.md
