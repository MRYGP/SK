# 案例卡库

> 所有案例的结构化摘要，用于跨案例检索和规律发现 格式说明：见 `content/case-card-format-v1.0.md` 每完成一次拆解，同时在这里新增一张卡 每10个案例做一次"规律发现" 最后更新：2026-04-17（CASE-002-Gamma重拆升级：补深度底稿+更新那一刀+P1框架升级为完整版+数据更新）

> ⚠️ **2026-04-28 待补齐**——本文件最后更新于 2026-04-17，011/012/013 案例卡待补；014 发布后补卡。补卡优先级：011 → 012 → 013 → 014。

------

## CASE-002-Gamma

```yaml
case_id: "CASE-002-Gamma"
name: "Gamma"
status: "active"
sector: "AI工具"
sub_sector: "AI演示文稿/内容创作"

team_size: 52
total_funding: "$80M（含$68M B轮）"
latest_round: "B轮 $68M，a16z领投，2025年11月"

one_line: "输入一段文字，60秒生成专业PPT"
target_user: "知识工作者、内容创作者、企业用户"
pricing_model: "freemium+信用额度（Plus $8/Pro $18/Ultra $100）"
arr: "$102M（Sacra，2026年3月）"
growth_signal: "52人做到$102M ARR，连续盈利超过两年；70M用户，600K付费"

core_tech: "AI生成+新格式（非传统PPT）"
moat_type: "分发壁垒（Made with Gamma品牌露出）"
acquisition_channel: "用户产出物自带分发（每天100万+文档）"

redefine: "把'做PPT'重新定义为'帮98%不会视觉翻译的人把想法传达出去'——竞争对手不是PowerPoint，是空白页本身"
redefine_dimensions: 5
rule: "成立"
flywheel: "飞轮成立"
flywheel_diagram: "用户产出文档→自然露出品牌→看到者注册→产出更多文档"
rrr_verdict: "RRF三项全中"

core_insight_v1: "最大壁垒不是AI技术，是用户替它打广告（裂变≠分发：分发长在产品里，裂变是加上去的）"
core_insight_v2: "98%的人打开PowerPoint看到空白页就关掉了——不是没有想法，是不会做视觉翻译。Gamma解决的是翻译问题，不是排版问题（Grant Lee原话+2%/98%数据，2023，B级）"
stuck_person: "32岁咨询顾问，有想法，卡在视觉翻译门槛——不知道第一张幻灯片写什么、几页、什么配色；98%的人都是他"
three_decisions:
  - "濒死时押注AI（2022年底推倒重写，3个月用户6万→300万）"
  - "不追用户数追付费率（credit-based freemium）"
  - "不融资当壁垒（盈利换决策自由）"

failure_modes: ["Tome（$81M融资，$3.5M ARR，2025年8月被AngelList收购——只解决了生成，没有解决分发；用户规模优先导致付费率<2%）"]
china_opportunity: "有但难复制"
china_status: "国内PPT玩家卷功能，没有人设计用户产出物分发机制"
china_window: "12-18个月"

four_path: "工具（个人用）+ 观察（产出物分发能否在中国场景跑通）"
counterintuitive: "最大壁垒不是AI，是每个用户帮它打广告"
transferable_pattern: |
  P1产出物即分发（完整版，2026-04-17升级）
  一句话：当用户完成核心任务时，产出物必然被别人看到——在那个时刻嵌入品牌，就是永续增长引擎
  适用：用户核心任务=把东西发给别人（文档/报告/设计/诊断结果）；看到产出物的人有同样需求；Freemium可行
  不适用：产出物是私密的/自己消费的；品牌露出妨碍收件人使用；产品没有免费层
  典型适用：演示工具/问卷工具/设计工具/AI诊断报告/AI分析报告
  典型不适用：个人健康追踪/密码管理/个人财务/内部工具
  对下一个案例（Cactus）：P1可能不适用（学术规范不接受AI标注），更可能是P3（帮用户练）
theory_match: "RRF（F-飞轮）DOC-D022"
comparable_cases: ["CASE-REF-Lovable", "CASE-006-Yoodli"]

source_quality: "A"
teardown_date: "2026-03"
reteardown_date: "2026-04-17"
article_file: "cases/2026/004-Gamma-产出自然分享.md"
article_published: "已发布 ✅"
article_file_b: "cases/2026/004B-Gamma-空白页沉默的人.md"
article_b_status: "⏳ 骨架草稿，待走写作工坊"
depth_draft: "注：Gamma重拆分析以004B文章形式产出，无单独底稿文件"
```

------

## CASE-REF-Lovable

```yaml
case_id: "CASE-REF-Lovable"
name: "Lovable"
status: "active"
sector: "AI工具"
sub_sector: "AI代码生成/低代码"

team_size: 45
total_funding: "少量"
latest_round: "种子"

one_line: "帮非技术人员用自然语言生成完整Web应用"
target_user: "非技术创始人、设计师、产品经理"
pricing_model: "订阅"
arr: "$100M+（2026年2月冲到$400M）"
growth_signal: "45人8个月做到$100M ARR"

core_tech: "GPT/Claude API + 代码生成"
moat_type: "切换成本"
acquisition_channel: "社区/口碑/SEO"

redefine: "把'写代码'重新定义为'描述你想要什么'——服务过去根本进不来的人"
redefine_dimensions: 2
rule: "过渡中"
flywheel: "半飞轮"
flywheel_diagram: "用户生成应用→分享→新用户看到→试用→生成自己的应用"
rrr_verdict: "有R无RF"

core_insight: "不是让高手更快，是让门外汉第一次上场（市场创新不是功能创新）"
failure_modes: ["Builder.ai（宣称降门槛但实际是手工劳动包装成AI，2025年破产）"]
china_opportunity: "有"
china_status: "法律文书/财务报告等高门槛场景有机会"
china_window: "6-12个月"

four_path: "观察"
counterintuitive: "不融资也能做到$100M ARR"
transferable_pattern: "P2门外汉上场——专业门槛把大多数有需求的人挡在门外，去掉门槛服务他们"
theory_match: "DOC-S037-从0到1；DOC-S032-破坏式创新"
comparable_cases: ["CASE-002-Gamma", "CASE-006-Yoodli"]

source_quality: "B"
teardown_date: "2026-02"
article_file: "cases/2026/005-Lovable-找到还没服务的大众.md"
article_published: "已发布 ✅"
```

------

## CASE-006-Yoodli

> 重拆日期：2026-04-17（完整重拆：新建深度底稿+stuck_person从群体升级为具体人+B端两面洞察补入+P3框架升级为完整版含适用边界）

```yaml
case_id: "CASE-006-Yoodli"
name: "Yoodli"
status: "active"
sector: "AI工具"
sub_sector: "AI沟通训练/企业L&D"

team_size: 40
total_funding: "$60M（含$40M B轮，WestBridge领投，2025年12月）"
latest_round: "B轮 $40M，2025年12月"

one_line: "AI扮演对面的人，帮你练真实对话——销售电话/面试/绩效反馈"
target_user: "企业销售团队、HR、管理培训"
pricing_model: "企业订阅+渠道合作"
arr: "未披露，12个月增长900%"
growth_signal: "40人，12个月ARR增长900%，估值从$100M到$300M+（6个月翻3倍）"

core_tech: "GPT/Gemini API + 角色扮演引擎 + 实时反馈分析"
moat_type: "方法论壁垒（客户将自身方法论灌入系统，切换成本极高）+ 渠道壁垒"
acquisition_channel: "渠道合作（Franklin Covey/Korn Ferry/LHH）+ 直销大企业"

redefine: "把'企业培训'从'让员工接触知识'重新定义为'让员工真正能用出来'"
redefine_dimensions: 6
rule: "成立（人需要开口说话这件事不可被AI替代）"
flywheel: "半飞轮（方法论壁垒随时间加深，但不是自动传播）"
rrr_verdict: "RR成立，F是方法论壁垒而非传播飞轮"

stuck_person: "林浩，35岁外企销售经理，认真学完了Franklin Covey课程，但真实通话里客户说'太贵了'时还是卡住了——不是没学，是没练过；不知道自己在真实对话里的弱点在哪"

core_insight_1: "卖设备效率的产品用户永远在比价；卖人的成长，用户的沉没成本是他自己练出来的能力"
core_insight_2: "小团队不自建信任，借别人的信任——Franklin Covey是Yoodli进入企业的信任通道"
core_insight_3: "最深的壁垒不是锁住客户，是让客户在你这里建了家（方法论壁垒>数据壁垒）"
core_insight_4: "C端用户的不确定感（我不知道自己哪里不行）= B端培训部门的痛点（培训完了员工还是不行），是同一道鸿沟两面——练习机会本身不存在才是根本问题"
cet_seed: "关掉它之后，你比用它之前更强了，还是更弱了——这是评估任何AI工具的终极问题（CET概念弧第一步）"

three_decisions:
  - "跟着用户信号转B端（从公开演讲→企业培训，用户自己发现的场景）"
  - "借Franklin Covey渠道（160国/大量Fortune 500客户，嵌入其销售培训课程）"
  - "让客户方法论长进系统（Franklin Covey/Korn Ferry/LHH将方法论灌入）"

failure_modes:
  - "传统企业培训（视频+打勾，完课率极低，知道≠会做）"
  - "Gong/Chorus（事后分析，不是事前练习，不同战场）"

china_opportunity: "有，几乎空白"
china_status: "考公面试/企业销售培训/职场面试三个场景均为空白"
china_window: "12-18个月（百度/猿辅导有能力但未入场，C级）"
china_key_scenario: "考公面试：200万+/年备考，结构化面试有标准答题框架但无练习，高频焦虑+评分标准公开+备考期3-6个月高频"

four_path: "工具（当下用Yoodli练自己）+ 观察（中国考公面试/企业销售培训场景有无人进入）"
counterینtuitive: "不是让AI替你说，而是让AI帮你练——关掉AI你更强了"
transferable_pattern: |
  P3练习室原则（完整版，2026-04-17重拆升级）
  框架名称：「练习室原则」
  一句话：任何「知道了但用不出来」的技能场景，都存在一个被忽视的练习室空白——填上这个空白的产品，卖的不是内容，是用户自己练出来的能力。
  核心机制：Yoodli护城河不是AI技术，是用户积累的练习历史和企业方法论——带得走（能力在身上），但不愿走（从零重建练习对手）。P3壁垒是对用户的尊重，而非锁死。
  适用：「知道理论」但「用不出来」的鸿沟真实存在；练习场景可被模拟（有角色/场景可还原）；月频以上使用；进步可被量化。
  不适用：用户只需要信息（知道就够用）；技能依赖物理存在（外科手术）；一次性任务；进步无法量化。
  P3 vs P1：P1用户走了产品损失（裂变链断）；P3用户走了用户自己损失（成长记录放弃）——P3壁垒质量更高。
  对Cactus提示：追问「学生是知道结构用不出来（P3）还是根本不知道怎么写（P2）」；学术规范不接受AI标注可能让P1不适用；Cactus是低压迭代型练习，与Yoodli高压即时型不同，评分维度能否建立是关键。
  可迁移场景：考公面试练习（强适用）/ 外语口语（强适用）/ 运动技术训练（部分适用）/ 护肤执行（弱适用）。
  附加洞察：借渠道原则（找已解决信任问题的中间人）+ 方法论壁垒（让客户方法论长进系统）+ 约束条件逼出唯一解（40人→借渠道→反而筛出Fortune 500）。

theory_match: "DOC-D022 RRF（重新定义问题，6维度）；DOC-P002 推演公式（约束条件→唯一解）；DOC-S032 破坏式创新（服务被忽视的练习需求）"
comparable_cases: ["CASE-002-Gamma（分发壁垒vs方法论壁垒对比）", "CASE-REF-Lovable（服务门外汉逻辑相通）"]
series_connection: "001（重新定义需求）002（财富公式三验）003（约束条件→借渠道）004（分发壁垒对照）005（用户信号驱动转型）"

source_quality: "A"
teardown_date: "2026-04"
reteardown_date: "2026-04-17"
article_file: "cases/2026/006-Yoodli-让人变得更强.md"
article_published: "已发布 ✅"
depth_draft: "cases/2026/深度底稿/006-Yoodli-拆解底稿.md"
```

------

## CASE-007-Paid

```yaml
case_id: "CASE-007-Paid"
name: "Paid"
status: "active"
sector: "AI基础设施"
sub_sector: "AI代理计费/价值度量"

team_size: "未披露（小团队）"
total_funding: "$33.3M"
latest_round: "种子轮 $21.6M，Lightspeed领投，2025年9月"

one_line: "帮AI代理公司追踪成本、度量价值、出具价值收据"
target_user: "AI代理/AI SaaS公司（ToB）"
pricing_model: "未披露"
arr: "未披露"
growth_signal: "估值超$100M，尚未到A轮；创始人前Outreach创始人（$4.4B估值）"

core_tech: "成本追踪+价值度量+账单生成"
moat_type: "数据壁垒（客户成本结构积累）+ 标准制定潜力"
acquisition_channel: "直销+创始人人脉"

redefine: "把"怎么收钱"重新定义为"怎么证明值多少钱""
redefine_dimensions: 3
rule: "过渡中（正在定义AI代理的价值度量标准）"
flywheel: "半飞轮"
flywheel_diagram: "更多AI公司接入→更多定价数据→行业基准形成→成为定价标准参考→更多公司接入"
rrr_verdict: "R✅ R→过渡 F→半飞轮"

core_insight: "定价不是商业策略问题，是激励结构问题——按席收费让产品改进和收入增长对抗，按结果收费让两者同向"
three_decisions:
  - "不做支付，做价值度量（避开Stripe绝对优势）"
  - "帮客户按结果计费而不是按调用量（复杂但直击价值鸿沟）"
  - "44亿估值公司创始人再次创业（本身是最强信号）"

failure_modes:
  - "Zendesk（定义之争带来信任损耗）"
  - "Leena AI（按用量收费导致客户不敢用）"
  - "Intercom旧模式（按席收费与AI能力自我矛盾）"

china_opportunity: "有，几乎空白"
china_status: "ToB AI工具按结果收费基本空白，难点在结果定义标准化"
china_window: "12-18个月"

four_path: "工具（从垂直场景切入，如AI客服的结果追踪+价值收据）"
counterintuitive: "你的产品越好，按席收费你越亏——因为客户需要的人越少"
transferable_pattern: "价值可见性原则——任何做得越好赚得越少的定价结构，说明价值计量层缺失"
theory_match: "DOC-D021维度跨越（从怎么收钱跳到怎么证明值多少）；DOC-P001财富公式·被留住"
comparable_cases: ["Intercom/Fin（按结果收费的先行者）", "Sierra（从DayOne按结果收费）"]
series_connection: "002（财富公式·被留住的新解读）004（分发壁垒vs标准制定壁垒）006（激励结构对比）"

source_quality: "A"
teardown_date: "2026-04"
article_file: "cases/2026/007-Paid-按结果收费.md"
article_published: "已发布 ✅"
```

------

## CASE-REF-WHF（文和友 · 失败案例参考卡）

```yaml
case_id: "CASE-REF-WHF"
name: "文和友（超级文和友）"
status: "shrinking"
sector: "线下餐饮/沉浸式商业体"
sub_sector: "复古主题餐饮综合体"

team_size: "未披露"
total_funding: "B轮5亿元（2021年）+早期融资"
latest_round: "B轮 5亿元，红杉/IDG/华平/碧桂园/GIC，2021年8月"
peak_valuation: "100亿元+（2021年峰值）"
current_state: "广州2025年2月闭店；深圳空铺率约70%；仅长沙独旺；2024年港股上市无进展"

one_line: "用复古沉浸式场景重塑线下餐饮，'餐饮界迪士尼'"
target_user: "本想做本地居民+游客；实际只服务一次性打卡游客"
pricing_model: "餐饮收入+商户租金"

redefine: "把'吃饭'重新定义为'体验老长沙'"
redefine_dimensions: 1
rule: "不成立（一次性消费，无规则可言）"
flywheel: "无飞轮（漏斗模式：买量→打卡→流失，靠新游客补充）"
rrr_verdict: "R有但浅，无R无F"

core_insight: "卖场景的产品必须问：拍完照之后，用户为什么要再来？文和友答不出这个问题"

failure_modes:
  - "FM003 伪需求（本地人不需要'证明我来过广州'）"
  - "FM015 无飞轮（增长靠外力推动而非自我强化）"
  - "FM002 留存崩塌（场景拍过一次=消费完成）"

three_failures:
  - "把游客打卡误认成本地复购（一次性社交货币消费）"
  - "单一卖点（只有'好'/场景体验，没有'快'没有'省'没有食物本身的'好'）"
  - "用快速扩张证明叙事（广州/深圳/南京三线齐开，遮盖单店模型问题）"

key_quote: "广州人不需要向朋友证明我来过广州。游客发现排队3小时吃到的虾饺，还不如街边老字号"

china_opportunity: "无（这是失败案例，对照用）"

four_path: "观察（作为'卖一次性社交货币'的失败标本）"
counterintuitive: "排队3000桌不是飞轮，是用从众心理制造的虚假信号；潮水退去就裸泳"

transferable_pattern:
  - "场景消费的致命问题：拍照打卡=任务完成=消费终结"
  - "单一卖点脆弱性：必须至少在'多/快/好/省'两个维度上立足"
  - "排队≠飞轮：从众驱动的增长是借来的时间"

theory_match:
  - "DOC-D022 RRF·F缺失（无飞轮）"
  - "Jobs-to-be-Done：文和友只承接了'证明我来过'这一次性任务"
  - "破坏式创新的反例：破坏了传统餐饮的体验，但没建立可持续的新模式"

comparable_cases:
  - "CASE-REF-PandaCake（熊猫不走，同样是一次性表演消费）"
  - "008-Humane（同样是一次性新鲜感消费）"
  - "对比CASE-002-Gamma（真飞轮：用户产出物自动带来下一个用户）"

source_quality: "B"
teardown_date: "2026-04（参考卡，未做完整10维度拆解）"
article_file: "未单独写"
article_published: "可在未来文章中作为对照案例引用"
notes: "适合用在'什么是真飞轮'或'多维价值锚点'类方法论文章中作为反面案例"
```

------

## CASE-REF-PandaCake（熊猫不走蛋糕 · 失败案例参考卡）

```yaml
case_id: "CASE-REF-PandaCake"
name: "熊猫不走蛋糕"
status: "dead"
sector: "线下餐饮/烘焙配送"
sub_sector: "情感体验型生日蛋糕"

team_size: "巅峰期数千人（含全国24城配送+表演团队）"
total_funding: "B轮1亿元+，头头是道/IDG等"
latest_round: "B轮 2021年"
death_date: "2024年3月16日（员工讨薪，创始人失联，全国停工）"
total_debt: "近1亿元（欠薪+供应商货款+用户预付卡约6000多万）"

one_line: "买蛋糕送'熊猫人偶上门跳舞'，烘焙界海底捞"
target_user: "过生日的家庭/年轻人（一年一次的低频用户）"
pricing_model: "蛋糕零售+表演溢价"

redefine: "把'买蛋糕'重新定义为'买生日仪式感'"
redefine_dimensions: 1
rule: "不成立（仪式感无法标准化复制）"
flywheel: "无飞轮（生日是年度低频，表演成本随规模线性增长）"
rrr_verdict: "R有，无R无F"

core_insight: "单位经济从未跑通——单次配送成本约80元（人偶服装+表演时间+培训+配送），客单价约200元，边际成本率40%（仅配送，不含原材料），消费频次年均1次。低频×高成本=数学上必死"

failure_modes:
  - "FM003 伪需求（用户不需要每年'再来一次熊猫'，新鲜感只能消费一次）"
  - "FM015 无飞轮（表演成本随规模线性增长，无规模效应）"
  - "FM012 现金流断裂（最终用预付卡资金维持运营，类Ponzi）"

three_failures:
  - "低频生意硬做高频规模（生日一年一次，但按高频烧钱扩张）"
  - "表演成本随规模线性增长（人偶服装+培训+配送，永远无法摊薄）"
  - "用预付储值卡维持现金流（变相把客户变债主）"

key_quote: "创始人杨振华事后承认'盲目乐观、决策失误'，称个人借债2000多万仍无力回天"

china_opportunity: "无（失败案例对照）"

four_path: "观察（作为'低频高成本表演式商业'的失败标本）"
counterintuitive: "差异化≠护城河。当差异化的成本本身就是不可摊薄的，规模越大死得越快"

transferable_pattern:
  - "单位经济测试（Unit Economics）：假设客户只来一次，这门生意能不能赚钱？"
  - "频次×边际成本=生死线：低频高成本生意永远跑不出规模效应"
  - "预付储值卡是危险信号：当公司开始用客户的钱维持运营，离暴雷不远了"

theory_match:
  - "DOC-D022 RRF·F缺失"
  - "Jobs-to-be-Done：用户雇佣它完成'一次性的生日惊喜'，无复购需求"
  - "破坏式创新的反例：差异化成功了，但差异化的成本结构是不可持续的"

comparable_cases:
  - "CASE-REF-WHF（文和友，同样的一次性体验消费）"
  - "对比007-Paid（按结果收费要求单位经济必须健康）"
  - "对比008-Humane（同样是表演式商业的硬件版）"

source_quality: "B"
teardown_date: "2026-04（参考卡）"
article_file: "未单独写"
article_published: "可在'单位经济'或'多维价值锚点'类文章中作为反面案例"
notes: "比文和友更典型的'数学上必死'案例。任何按结果付费/单位经济类文章都可以引用这个例子"
```

------

------

## CASE-011-MYHAIRAI

```yaml
case_id: "CASE-011-MYHAIRAI"
name: "MyHair AI"
status: "active"
sector: "AI健康"
sub_sector: "脱发诊断/头发健康"

team_size: "<5人（初始），后扩张"
total_funding: "未公开，推测自资"
latest_round: "无公开融资"

one_line: "用手机照片+AI，告诉你头发真实状况——不骗你说你在脱发，也不让你盲目花冤枉钱"
target_user: "脱发焦虑者（不确定自己是否需要干预的人），非脱发患者（已确定要治的人）"
pricing_model: "Freemium：免费基础自测 + $3.99/周、$9.99/月、$149.99/年订阅"
arr: "未披露（1000付费×$9.99/月≈$10K/月，C级推算）"
growth_signal: "2025年夏上线，数月内20万用户，无融资，vibe coding起步"

core_tech: "专用计算机视觉模型（非通用LLM），30万+头皮图像训练，95%准确率（官称）"
moat_type: "数据壁垒（30万+图像）+ 用户追踪历史切换成本"
acquisition_channel: "自然搜索+社媒（具体未披露）"

redefine: "把'脱发怎么治'重新定义为'我到底有没有在脱发、需不需要治'"
redefine_dimensions: 2
rule: "成立（脱发焦虑是持续的，追踪需求是真实的）"
flywheel: "轻飞轮（用户追踪历史积累=切换成本；数据积累=模型更准）"
flywheel_diagram: "用户持续上传照片→追踪历史积累→舍不得走→更多数据→模型更准→更多人来"
rrr_verdict: "R成立（重新定义问题），R弱（追踪有留存但弱），F轻飞轮"

core_insight: "脱发市场最大的生意不是帮你长头发，是告诉你'你到底有没有在掉'——信息不对称才是用户的真实痛点"
aha_moment: "用户不确定感=植发医院无效获客=同一个问题两面；解决用户不确定=自动帮医院筛精准客"

three_decisions:
  - "不用通用LLM，自建专用视觉模型（诊断可信度核心）"
  - "Freemium定价（免费钩子+订阅留存）"
  - "同步开放B端（医生用AI加速患者评估）"

failure_modes:
  - "轻问诊App死法：用一次就走（DAU/MAU极低）——MYHAIR用追踪功能对冲"
  - "健康AI付费转化低：0.5%转化率说明C端难撑，B端才是关键"

china_opportunity: "强烈推荐——中国空白"
china_status: "无直接对标（纯软件+手机拍照+消费级定价）；现有方案均为B端硬件或植发机构内部工具"
china_window: "12-18个月"
china_window_close_signal: "雍禾/碧莲盛推出独立AI自测App"
china_key_insight: "植发医院获客成本数千元/人（销售费用率50%），AI预筛可将有效获客成本降低60%以上，这是B端愿意付钱的核心理由"
china_target_user: "26-30岁男性，脱发焦虑但未行动的人（2.99亿，渗透率仅0.4%）"

four_path: "工具（写011文章招募有医美背景的合伙人/资源伙伴）"
four_path_reason: "我们不做：医美是陌生领域，B端打通需要行业资源；当前主线是内容证明判断力，38产品还没跑完"
counterituitive: "0.5%付费转化不是失败，是商业模型设计问题——C端是钩子，B端植发导流才是真钱"
transferrable_pattern:
  - "决策工具>导流工具：帮用户做出正确决定，比帮品牌找用户更有信任度和粘性"
  - "B端在C端MVP期就要推进，不是等用户大了再找"
  - "前3个B端客户免费试点，用转化率数据说话，再谈钱"
  - "以合作方而非竞争方身份接近行业龙头"

three_ironlaws:
  - "B端合作在MVP期同时推进，不是等C端做大了再找"
  - "前3个B端客户用结果说话，不用关系说话"
  - "尽早以合作方身份接触行业龙头（雍禾/碧莲盛），别等他们自己动手"

theory_match: "DOC-S032破坏式创新（服务被忽视的用户：焦虑但未行动者）；DOC-D021维度跨越（从治疗市场跳到诊断市场）"
comparable_cases: ["CASE-006-Yoodli（B端渠道借力）", "CASE-REF-春雨医生（轻问诊死法对照）"]

source_quality: "A+B"
teardown_date: "2026-04-14"
teardown_depth: "完整10维度+推演流水账"
depth_draft: "cases/2026/深度底稿/011-MYHAIRAI-拆解底稿.md"
inference_log: "cases/2026/推演流水账-MYHAIRAI中国版-2026-04-14.md"
article_file: "cases/2026/011-MYHAIRAI-脱发诊断市场最大的生意.md"
article_published: "待写"
```

------

（下一个案例卡在这里追加）

------

## CASE-012-Cactus

```yaml
case_id: "CASE-012-Cactus"
name: "Cactus"
status: "active"
sector: "AI工具"
sub_sector: "AI语音接待/home services垂直SaaS"

team_size: "2-9人（冲突数据）"
total_funding: "$7.5M+（$7M Seed，Wellington+YC，2025-11）"
latest_round: "Seed $7M，Wellington Management领投，2025-11"

one_line: "帮美国HVAC/水管/电气等上门服务商家24/7接听来电、筛选线索、安排预约"
target_user: "1-20人 home services 商家（HVAC/水管/电气/屋顶/景观/承包），年收入$100万-$2000万"
pricing_model: "月费订阅（$49-$500多版本冲突，全部X级，不做决策依据）"
arr: "未找到（数据空白）"
growth_signal: "YC X25，$7M融资，Wellington参与种子轮（罕见），无独立用户增长数据"

core_tech: "AI语音（ASR+TTS）+ lead qualification + CRM集成（ServiceTitan/Jobber）+ aftercare自动化"
moat_type: "垂直脚本数据（中等）+ CRM集成沉没成本（中等）；无飞轮"
acquisition_channel: "Demo驱动+直销+YC网络"

founder_original_observation: |
  行为模式型（A级，Ajith LinkedIn 2025-12）：
  运营Cravd时看到私厨和承包商反复出现「the same pattern」——干活时没法接电话，客户流失。
  跨行业验证（私厨→承包商）触发pivot。
  数字型（B级）：每100个inquiry只有5-10%是真正qualified leads。
  场景型（A级）：owner「stays up until three in the morning answering phones」。
  核心重新定义：问题不是营销不足，而是「首触点效率」——正在服务时无法销售。

stuck_person: "Mike，42岁，德克萨斯HVAC修理工。七月正午在屋顶换压缩机，电话响无法接，40分钟后爬下来，客户已找别家。每周2-3次，每次$350-500工单。卡住的不是不想接，是物理上不可能同时在屋顶和在电话里。"

aha_moment: "客户Erin Smith：'Our customers often don't realize they're not speaking with a real person.'（B级）——aha不是'AI接电话'，是'接起来了，而且客户没察觉是AI'"

those_a_刀: "问题不是个体服务商找不到客户。是当客户打来电话时，老板正在屋顶上、管道里、或者开车去下一个工地——那通电话会打给接起来的下一个人。Cactus是他们从来没钱雇的第一个员工。"

redefine: "从'客服质量提升/呼叫中心升级'重新定义为'干活时没人接→每通来电都是钱'；真正竞争对手是语音信箱和工作现实，不是其他AI工具"
redefine_dimensions: 5
rule: "套利者（无规则制定动作，依赖第三方语音AI API，无开放生态）"
flywheel: "无飞轮/纯漏斗（①多边参与❌；②核心价值随规模稀释❌；③退出成本中等✓；④单圈正收益假设✓）"
rrr_verdict: "R✅（5维度）/ R套利者 / F无飞轮 → 有R无RF，一次性爆款风险"

pivot: "Cravd（私厨撮合平台，2024年6月）→ Cactus泛solopreneur AI copilot → Cactus home services AI call center（当前）。定位从'帮所有个体户管后台'收缩为'帮美国上门服务商家接电话+接单'"

three_success_mechanisms:
  - "ROI极清晰：漏接1通电话=$350-500工单，$49/月订阅vs月均减少5-10通漏接，即刻正向"
  - "垂直脚本信任门槛：HVAC专业术语训练，通用AI答不了'你们处理Lennox还是Carrier'，Cactus能"
  - "aftercare automation：不只接inbound，还主动联系老客做维保提醒/复购，是'进攻型'而非纯'防守型'工具"

failure_risks:
  - "FM001平台内置：ServiceTitan有能力内置AI接听功能，Cactus可能从'独立产品'变成'应该有的功能'"
  - "FM015无飞轮：增长靠销售投入，竞品建立飞轮后差距将拉大"
  - "FM003 Pre-PMF：Step 0找不到任何独立用户评价，PMF尚未证明"

china_opportunity: "比初判要中性——平台已接管城市新客户首触点，微信私域多是老客户不构成零等待；真实机会在老人陪诊/宠物急诊个体诊所/餐饮设备急修/婚庆当日应急这几个平台还没覆盖的垂直场景"
china_status: "平台已接管大部分城市新客户首触点；尚无聚焦老人陪诊/宠物急诊等场景的独立品牌"
china_window: "12-18个月"
china_close_signal: "美团上门把老人陪诊/宠物急诊/餐饮设备急修纳入平台派单体系"
china_note: "微信私域大多数场景是老客户，不构成P5。真正的中国P5窗口：等待时间短+平台化低+新客户打电话逻辑的垂直领域"

four_path: "观察（提炼P5模式+识别中国真正的零等待垂直场景）"
four_path_note: "中国版需要首先确认：老人陪诊/宠物急诊/餐饮设备急修这几个垂直里，是否有人在做且没被平台覆盖"
next_action: "把012文章主题定为P5新客户零等待，结尾问题：上个月因为没接电话，少了多少钱？吸引服务型行业资源的人来接触"
china_status: "电话接单渠道不适用；真正机会是'AI接微信询盘+自动报价+预约'，针对装修/家政/维修个体户"
china_window: "18-24个月"
china_close_signal: "腾讯企微推出'智能接单助手'免费给服务商家"
china_note: "中国版不是直接复制Cactus，是把P5洞察（首触点鸿沟）迁移到微信渠道+国内服务型个体户"

four_path: "观察（提炼P5模式+等待有企微/平台资源合伙人）"
four_path_note: "中国版需要换题（电话→微信），团队适配度3/10，当前不直接推进"
next_action: "把首触点鸿沟概念写入012拆解文章，测试读者反应，看是否有服务型行业资源的人来接触"

counterituitive: "服务商的问题不是营销不够好，是正在干活时没人帮他接那通最关键的电话——找客户的问题早已解决，留住打来的客户才是真正的漏斗"
transferrable_pattern: |
  P5新客户零等待原则（v1.1修正，2026-04-18）
  原名「首触点鸿沟」不够精确，核心变量是「新客户」而非「老板没空」。
  框架名称：「P5新客户零等待原则」
  一句话：新客户+紧急需求+零替代成本三条件叠加时，首触点接不到=永久失去无补救机会。老客户会等，不构成零等待鸿沟。
  三条件分述：
    1、新客户（无关系基础）：老客户有粘性会等，漏接可回拨补救
    2、紧急需求（今天就要解决）：计划性服务可预约，首触点不是瓶颈
    3、零替代成本（客户有多个备选）：稀缺供给时客户没得选，不构成等待问题
  Pivot逻辑：私厨/摄影师来电主要是老客户（缺条件1），Home Services来电主要是Google搜索的陌生新客户（三条件全满足）。这才是Cactus收缩垂直的真正逻辑。
  中国机会修正：微信私域大多数场景是老客户，不构成P5。真正的中国机会在：老人陪诊/宠物急诊个体诊所/餐饮设备急修/婚庆当日应急——平台还没覆盖的纯电话新客户紧急场景。
  适用：来联系者是陌生新客户；需求紧急；竞争充分客户有多个备选；服务提供者身兼销售。
  不适用：老客户/熟人介绍；计划性预约服务；已平台化的首触点（美团已接管）。
  快速判断三问：来联系的是新客户还是老客户？需求紧急还是可等？平台有没有已接管这个首触点？

theory_match:
  - "DOC-S074换题思维（从获客问题换成首触点效率问题，是本案最核心的思维动作）"
  - "DOC-S032破坏式创新（服务被忽视的1-10人小团队，买不起$3000/月呼叫中心）"
  - "DOC-P002推演公式（约束条件2人团队→唯一解垂直聚焦→意外收获行业脚本更好）"
comparable_cases: ["CASE-006-Yoodli（同样无飞轮但有方法论壁垒；Cactus缺乏等效防御）", "CASE-002-Gamma（P1产出物分发 vs P5首触点鸿沟，两种换题模式对比）"]

data_quality_note: "Step 0数据最严重缺口：付费用户数/ARR/MAU全部未找到；定价三版本冲突全部X级；无独立第三方用户评价——整体经营面透明度极低，分析结论限于产品逻辑层，不做商业规模判断"

source_quality: "A+B（创始人洞察清晰；经营数据全空白）"
teardown_date: "2026-04-18"
article_file: "cases/2026/待发布-Cactus-首触点鸿沟.md（待写）"
article_published: "待写"
depth_draft: "cases/2026/深度底稿/Cactus-拆解底稿.md"
```
