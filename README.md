# SK知识库 · 三湘问道

> 最后更新：2026-03-20
> 维护者：changshayang

---

## 仓库结构

```
E:\sk\
│
├── README.md                    ← 本文件（仓库总导航）
├── 北极星文档.md                ← 战略锚点（整个Project的出发点）
│
├── core/                        ← 核心方法论 + 规则（7个文件）
│   ├── SKILL-推演SOP-v1.3.md        推演八步法（"做不做"）
│   ├── SKILL-产品设计方法论-v1.0.md  十步产品设计法（"怎么做"）
│   ├── product-teardown-template-v3.0.md  AI产品拆解10维度模板
│   ├── 三湘问道铁律.md              15条排除不可能的判断规则
│   ├── 评估引擎速查版.md            7+3步拆解法、三种模式、四路决策树
│   ├── failure_modes.yml            14种失败模式定义
│   └── evidence_levels.yml          A/B/C/X证据等级定义
│
├── theory/                      ← 理论文件（10个文件）
│   ├── DOC-P001-财富公式.md         被看见×被信任×被留住
│   ├── DOC-P002-AlphaFold推演公式.md 历史数据×约束条件×迭代深度
│   ├── DOC-D021-维度跨越.md         四个竞争维度
│   ├── DOC-S003-初创企业生存法则.md   手电筒APP困境/Loom壁垒
│   ├── DOC-S032-破坏式创新.md       克里斯坦森破坏式创新
│   ├── DOC-S037-从0到1.md           彼得·蒂尔垄断与秘密
│   ├── DOC-S047-三大标杆方法论.md    CEO思维对标素材
│   ├── DOC-S061-网络效应与学习效应.md 网络效应/数据飞轮判断
│   ├── DOC-S065-深度用户护城河.md    LTV/CAC/留存/护城河类型
│   └── DOC-S074-换题思维.md         问题升维/从忍受描述找空白
│
├── content/                     ← 内容生产（7个文件）
│   ├── 公众号写作指南.md            语言规范、禁用词、证据规则
│   ├── 公众号内容大纲-30篇规划.md    六拳结构，30篇骨架
│   ├── 公众号内容生产经验手册.md      8条教训 + 写作检查清单
│   ├── article_template.md          讲稿结构骨架
│   ├── agent3a_article.md           讲稿改写prompt
│   ├── aichajie-案例模板-v1.0.md    案例六维度存储模板
│   └── 案例拆解输出标准.md          三输出体系、工作流、质量检查
│
├── ops/                         ← 团队运营（3个文件）
│   ├── 三人工作方案.md              杨+实习生A+实习生B分工
│   ├── 实习生A-第一周入职须知.md     内容运营岗位说明
│   └── 实习生B-第一周入职须知.md     产品开发岗位说明
│
├── meta/                        ← 系统 + 工具（8个文件）
│   ├── 系统指令-v1.3.md            思考Project的系统指令
│   ├── 写作工坊-系统指令-v1.0.md    写作Project的系统指令
│   ├── gpts-first-reader-design.md  GPTs第一读者设计方案
│   ├── gpts-deep-researcher-design.md GPTs深度研究员设计方案
│   ├── gpt-deep-research-prompt.md  分发策略深度研究指令（定制版）
│   ├── gpt-deep-research-elderly-scenarios.md 场景验证研究指令（定制版）
│   ├── 理论库优先级清单.md          理论补充的优先级排序
│   └── changelog.md               更新日志
│
├── cases/2026/                  ← 案例 + 项目 + 文章
│   ├── case-index.md                案例库总索引
│   ├── 拆解顺序表.md               待拆解产品队列
│   ├── 诊断问题库.md               场景F积累的问题
│   │
│   ├── 【公众号文章】
│   │   ├── 001-所有人都在做照顾老人的AI产品.md  ✅ 可发布
│   │   ├── 002-财富公式.md                       ✅ 可发布
│   │   ├── 003-推演公式.md                       ✅ 可发布
│   │   ├── 50岁，和AI深聊三年后，我决定重新出发.md  📦 第009篇发
│   │   └── 001-launch-plan.md                    发布执行方案
│   │
│   ├── 【老年AI管家项目】
│   │   ├── product-design-draft-v0.2.md          产品设计v0.2.1
│   │   ├── north-star-elderly-ai.md              项目北极星
│   │   ├── ai-elderly-product-discussion-log.md  Claude推演29章
│   │   ├── kimi-discussion-log.md                KIMI讨论9章
│   │   ├── research-report-elderly-growth.md     5个亿级老年产品研究
│   │   └── tech-eval-checklist-digital-human.md  数字人技术评估
│   │
│   ├── 【研究报告】
│   │   ├── research-wechat-visibility.md         公众号冷启动研究
│   │   └── deep-research-distribution-strategy.md 多平台分发研究
│   │
│   ├── 【参考案例】
│   │   ├── CASE-REF-Lovable.md
│   │   └── lovable-拆解文章-v2.md
│   │
│   └── _archive/                旧版文件（可移到仓库外部）
│
└── _archive/                    ← 存档说明（详见内部README）
    └── README.md                记录什么被移走了、为什么
```

> 注：cases/2026/ 内的文件暂时保持平铺，不建子文件夹——因为多个文档交叉引用这些路径。
> 上面的【】分组只是README里的逻辑分类，不是实际文件夹。等积累到30+文件时再物理分组。

---

## 工具索引

### Claude Projects（两个，分工明确）

| Project | 系统指令 | 知识库 | 职责 |
|---------|---------|--------|------|
| **思考Project**（本仓库主体） | `meta/系统指令-v1.3.md` | 整个SK仓库 | 拆解、推演、判断、评估、知识库管理 → 输出**底稿** |
| **写作Project** | `meta/写作工坊-系统指令-v1.0.md` | ① `content/公众号写作指南.md` ② `content/公众号内容生产经验手册.md` ③ `content/公众号内容大纲-30篇规划.md` ④ 读者反馈（累积） | 把底稿变成让陌生人停下来的文章 → 输出**可发布文章** |

> **为什么分两个**：思考的本能是"加"（更完整、更严谨），写作的本能是"砍"（只留那一刀）。放在一个Project里会互相打架。

```
工作流：
思考Project（拆解/推演）→ 底稿 → 写作Project（找那一刀/砍/控节奏）→ 文章 → GPTs第一读者（测试）→ 修改 → 发布
```

### GPTs工具（ChatGPT侧）

| 工具 | 设计文件 | 知识库文件 | 用途 |
|------|---------|------------|------|
| **GPTs第一读者** | `meta/gpts-first-reader-design.md` | ① `content/公众号写作指南.md` ② `北极星文档.md` ③ `cases/2026/research-wechat-visibility.md` | 文章发布前的读者模拟测试 |
| **GPTs深度研究员** | `meta/gpts-deep-researcher-design.md` | ① `core/研究员输出模板.md` ② `core/failure_modes.yml` ③ `core/evidence_levels.yml` ④ `content/公众号写作指南.md` | 数据收集和假设验证 |
| GPT深度研究-分发策略 | `meta/gpt-deep-research-prompt.md` | — | 定制版 |
| GPT深度研究-场景验证 | `meta/gpt-deep-research-elderly-scenarios.md` | — | 定制版 |

---

## 两个核心Skill的关系

```
推演SOP v1.3 → "做不做？" → 结论："做" → 确立北极星
                                              ↓
                          产品设计方法论 v1.0 → "怎么做？"
```

---

## 发布序列（30篇六拳结构）

```
第一拳（001-003）：立判断力 + 亮武器          ✅ 已完成
第二拳（004-008）：拆真实产品（Gamma/Lovable/YOODLI/Paid/失败专题）
第三拳（009-010）：收网（50岁出发 + 规律提炼）
第四拳（011-016）：深水区（中国机会/Tesla/活书/押注宣言）
第五拳（017-022）：方法论进阶（破坏式创新/从0到1/维度跨越）
第六拳（023-030）：开放（读者共创/年度复盘）
```

详见：`content/公众号内容大纲-30篇规划.md`

---

## 与其他仓库/工具的关系

| 名称 | 位置/平台 | 角色 |
|------|----------|------|
| **SK知识库** | E:\sk | 操作系统（本仓库） |
| **三湘问道理论库** | E:\sanxiangwendao | 弹药库（92篇理论文档） |
| **宝山方舟科技** | E:\宝山方舟科技 | 支线项目（参谋角色） |
| **思考Project** | Claude Project | 大脑（拆解/推演/判断） |
| **写作Project** | Claude Project | 写手（底稿→文章） |
| **GPTs第一读者** | ChatGPT GPTs | 测试员（模拟陌生读者） |
| **GPTs深度研究员** | ChatGPT GPTs | 研究员（数据/竞品/验证） |

---

## 知识库搜索关键词速查

| 要做什么 | 搜什么 |
|---------|--------|
| 拆解产品 | `core/product-teardown-template` `content/aichajie-案例模板` `content/公众号写作指南` |
| 写文章 | `content/article_template` `content/公众号写作指南` `content/公众号内容生产经验手册` |
| 做评估 | `core/评估引擎速查版` `core/failure_modes` |
| 选题 | `北极星文档` `content/公众号内容大纲` |
| 找理论 | `theory/DOC-S032` `theory/DOC-S037` `theory/DOC-S047` |
| 找框架 | `core/product-teardown-template` `core/evidence_levels` |
| 做排除判断 | `core/三湘问道铁律` |
| 找不到竞争对手 | `theory/DOC-D021` `theory/DOC-S074` |
| 推演新方向 | `core/SKILL-推演SOP-v1.3` `core/failure_modes` `core/评估引擎速查版` |

---

## 维护规则

- 系统指令修改时，同步更新 `meta/` 里对应文件（版本号递增）
- 理论文件新增时，同步更新 `meta/理论库优先级清单.md`
- 每5个案例更新 `cases/2026/case-index.md`
- 每写完5篇文章回顾 `content/公众号内容生产经验手册.md`
- 过时文件移到 `_archive/` 并更新 `_archive/README.md`
- 实际存档文件可移到仓库外部（如 `E:\sk-archive\`），保持仓库干净
