# SK知识库 · 三湘问道

> 最后更新：2026-03-22
> 维护者：changshayang

---

## 仓库结构

```
E:\sk\
│
├── README.md                    ← 本文件（仓库总导航）
├── 北极星文档.md                ← 战略锚点（v3.2）
│
├── core/                        ← 核心方法论 + 规则（8个文件）
├── theory/                      ← 理论文件（11个文件）
├── content/                     ← 内容生产（8个文件）
├── ops/                         ← 团队运营（5个文件）
├── meta/                        ← 系统指令 + 工具设计（8个文件）
├── cases/2026/                  ← 案例 + 项目 + 研究报告
└── _archive/                    ← 已归档旧版文件
```

---

## 核心理论体系：RRF判断链

> 2026-03-22重构。所有拆解、评估、产品判断的底层逻辑。

```
            判断一个产品能不能活
                    |
        ┌──────────┼──────────┐
        |          |          |
     问题1       问题2       问题3
  它改了什么？  它消失了    它有没有
             谁痛苦？   自转的轮子？
        |          |          |
   破坏式创新   规则制定    飞轮效应
   维度跨越     生存法则    网络效应
   换题思维               飞轮基因论
                          财务约束
```

**工具层（贯穿始终）：**
- 财富公式（DOC-P001）—— 被看见×被信任×被留住
- 推演公式（DOC-P002）—— 历史数据×约束条件×迭代深度
- 失败模式库（FM001-FM015）—— 15种死法识别

详见：`theory/DOC-D022-重新定义问题与飞轮构建.md`（v2.0）

---

## 工具矩阵（1个总指挥 + 5个专业工具）

| 角色 | 平台 | 指令/设计文件 |
|------|------|-------------|
| **思考Project** | Claude | `meta/系统指令-v1.3.md` |
| **写作工坊** ×2 | Claude + GPTs | `meta/写作工坊-系统指令-v1.0.md` |
| **第一读者** ×2 | Claude + GPTs | `meta/gpts-first-reader-design.md` |
| **深度研究员** ×1 | GPTs | `meta/gpts-deep-researcher-design.md` |

日常工作流：思考Project拆解→写作工坊润色→第一读者测试→发布

---

## 发布序列（30篇六拳结构 + RRF暗线）

```
第一拳（001-003）：立判断力 + 亮武器          ✅ 已完成
第二拳（004-008）：拆真实产品（RRF暗线渗透）
第三拳（009-010）：收网（010正式亮出"三个问题"）  ← RRF公开亮相
第四拳（011-016）：深水区（每篇显式回答三问）
第五拳（017-022）：三个问题的深度展开
第六拳（023-030）：开放（读者用三问做拆解）
```

详见：`content/公众号内容大纲-30篇规划.md` + `content/公众号与理论融合方案.md`

---

## 知识库搜索关键词速查

| 要做什么 | 搜什么 |
|---------|--------|
| 拆解产品 | `core/product-teardown-template-v4.0` `content/aichajie-案例模板` |
| 做RRF检验 | `theory/DOC-D022` `cases/2026/RRF案例验证库` |
| 写文章 | `content/公众号写作指南` `content/公众号内容生产经验手册` |
| 理论融合 | `content/公众号与理论融合方案` |
| 做评估 | `core/评估引擎速查版` `core/failure_modes` |
| 选题 | `北极星文档` `content/公众号内容大纲` |
| 找理论 | `theory/` 目录下所有DOC文件 |
| 做排除判断 | `core/三湘问道铁律` |
| 推演新方向 | `core/SKILL-推演SOP-v1.3` `core/failure_modes` |
| 安排实习生 | `ops/实习生工作安排总表` |
| RRF理论发展 | `meta/RRF理论发展路径` `meta/RRF理论评估指令` |

---

## 与其他仓库的关系

| 名称 | 位置 | 角色 |
|------|------|------|
| **SK知识库** | E:\sk | 操作系统（本仓库） |
| **三湘问道理论库** | E:\sanxiangwendao | 弹药库（90+篇理论文档） |
| **GitHub同步** | github.com/MRYGP/SK | 远程备份 |

---

## 维护规则

- 系统指令修改 → 同步更新 `meta/` 对应文件
- 理论文件新增 → 更新 `meta/理论库优先级清单.md`
- 每5个案例 → 更新 `cases/2026/case-index.md`
- 每次RRF拆解 → 更新 `cases/2026/RRF案例验证库.md`
- 过时文件 → 移到 `_archive/` 并在changelog记录
- 更新日志 → `meta/changelog.md`

---

## 附录：各文件夹详细内容

### core/（8个文件）
```
product-teardown-template-v4.0.md  10维度拆解模板（含RRF检验+飞轮四条件）
SKILL-推演SOP-v1.3.md             推演八步法
SKILL-产品设计方法论-v1.0.md       十步产品设计法
三湘问道铁律.md                   15条排除规则
评估引擎速查版.md                 7+3步拆解法（含FM015）
研究员输出模板.md                 深度研究员专用输出结构
failure_modes.yml                 15种失败模式（含FM015无飞轮增长依赖）
evidence_levels.yml               A/B/C/X证据等级
```

### theory/（11个文件）
```
DOC-D022-重新定义问题与飞轮构建.md  ★ RRF判断链（v2.0，核心理论）
DOC-D021-维度跨越.md               四个竞争维度
DOC-P001-财富公式.md               被看见×被信任×被留住
DOC-P002-AlphaFold推演公式.md       历史数据×约束条件×迭代深度
DOC-S003-初创企业生存法则.md        手电筒APP/Loom壁垒
DOC-S032-破坏式创新.md             克里斯坦森（与D022配套：S032=入场，D022=活下去）
DOC-S037-从0到1.md                 彼得·蒂尔
DOC-S047-三大标杆方法论.md          CEO思维对标
DOC-S061-网络效应与学习效应.md      数据飞轮
DOC-S065-深度用户护城河.md          LTV/CAC/留存
DOC-S074-换题思维.md               问题升维
```

### content/（8个文件）
```
公众号与理论融合方案.md            ★ RRF暗线设计（30篇怎么带理论）
公众号内容大纲-30篇规划.md         六拳结构
公众号写作指南.md                  语言规范/禁用词/证据规则
公众号内容生产经验手册.md           9条教训+检查清单
article_template.md                文章骨架模板
agent3a_article.md                 讲稿改写prompt
aichajie-案例模板-v1.0.md          案例六维度存储
案例拆解输出标准.md                三输出体系
```

### ops/（5个文件）
```
实习生工作安排总表.md              ★ 两人具体周计划+交叉协作+卡点自救协议
三人工作方案.md                    杨+实习生A+实习生B总方案
实习生A-第一周入职须知.md           内容运营
实习生B-第一周入职须知.md           产品开发
本周执行清单-2人版-v2.md            当前执行清单
```

### meta/（8个文件）
```
系统指令-v1.3.md                   思考Project指令
写作工坊-系统指令-v1.0.md          写作Project指令
gpts-first-reader-design.md        第一读者指令
gpts-deep-researcher-design.md     深度研究员指令
RRF理论发展路径.md                 ★ 从框架到可发表理论的6阶段路径
RRF理论评估指令.md                 发给外部AI的红队攻击指令
理论库优先级清单.md                理论补充排序
changelog.md                       更新日志
```

### cases/2026/（主要文件）
```
001-所有人都在做照顾老人的AI产品-v2.md  ★ 001正式版（待发布）
002-财富公式.md                         待润色
003-推演公式.md                         待润色
001-launch-plan.md                      冷启动方案
RRF案例验证库.md                        ★ 19个案例的RRF分析
case-index.md                           案例库索引
拆解顺序表.md                           6个待拆案例
诊断问题库.md                           场景F积累

深度研究报告/
  让已设计的AI协作系统跑起来.md          编排层研究
  RRF框架评估报告CLAUDE.md              红队报告
  RRF框架深度评估报告GEMINI.md          红队报告
  RRF深度研究GPT.md                     红队报告
  RRF修正清单-三报告交叉比对.md          修正清单
```

### _archive/（归档文件）
```
README.md                                    存档说明
系统指令补丁-深度研究触发-已合并.md            旧补丁
product-teardown-template-v3.0.md             被v4.0替代
本周执行清单-1人版-已替代.md                   被2人版替代
gpt-deep-research-prompt-已用过.md             旧研究指令
gpt-deep-research-elderly-scenarios-已用过.md   旧研究指令
```
