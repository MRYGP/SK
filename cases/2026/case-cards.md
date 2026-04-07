# 案例卡库

> 所有案例的结构化摘要，用于跨案例检索和规律发现
> 格式说明：见 `content/case-card-format-v1.0.md`
> 每完成一次拆解，同时在这里新增一张卡
> 每10个案例做一次"规律发现"
> 最后更新：2026-04-06（新增文和友/熊猫不走两张失败案例参考卡）

---

## CASE-002-Gamma

```yaml
case_id: "CASE-002-Gamma"
name: "Gamma"
status: "active"
sector: "AI工具"
sub_sector: "AI演示文稿/内容创作"

team_size: 50
total_funding: "$90M（含$68M B轮）"
latest_round: "B轮 $68M，a16z领投，2025年11月"

one_line: "输入一段文字，60秒生成专业PPT"
target_user: "知识工作者、内容创作者、企业用户"
pricing_model: "freemium+信用额度"
arr: "$100M（2025年11月）"
growth_signal: "50人做到$100M ARR，连续盈利超过两年"

core_tech: "AI生成+新格式（非传统PPT）"
moat_type: "分发壁垒（Made with Gamma品牌露出）"
acquisition_channel: "用户产出物自带分发（每天100万+文档）"

redefine: "把'做PPT'重新定义为'表达想法'，格式问题交给AI"
redefine_dimensions: 2
rule: "成立"
flywheel: "飞轮成立"
flywheel_diagram: "用户产出文档→自然露出品牌→看到者注册→产出更多文档"
rrr_verdict: "RRF三项全中"

core_insight: "最大壁垒不是AI技术，是用户替它打广告（裂变≠分发：分发长在产品里，裂变是加上去的）"
three_decisions:
  - "濒死时押注AI（2022年底推倒重写，3个月用户6万→300万）"
  - "不追用户数追付费率（credit-based freemium）"
  - "不融资当壁垒（盈利换决策自由）"

failure_modes: ["Tome（8100万融资，350万ARR——裂变没做成飞轮）"]
china_opportunity: "有但难复制"
china_status: "国内PPT玩家卷功能，没有人设计用户产出物分发机制"
china_window: "12-18个月"

four_path: "工具（个人用）+ 观察（产出物分发能否在中国场景跑通）"
counterintuitive: "最大壁垒不是AI，是每个用户帮它打广告"
transferable_pattern: "用户的核心动作天然需要把产出物发给别人→永续增长引擎"
theory_match: "RRF（F-飞轮）DOC-D022"
comparable_cases: ["CASE-REF-Lovable", "CASE-006-Yoodli"]

source_quality: "A"
teardown_date: "2026-03"
article_file: "cases/2026/004-Gamma-50个人怎么做出21亿美金终稿.md"
article_published: "终稿完成，待发布"
```

---

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
transferable_pattern: "极小团队+极高人效=不需要大量融资；服务门外汉比服务高手天花板更高"
theory_match: "DOC-S037-从0到1；DOC-S032-破坏式创新"
comparable_cases: ["CASE-002-Gamma", "CASE-006-Yoodli"]

source_quality: "B"
teardown_date: "2026-02"
article_file: "cases/2026/005Lovable拆解-终稿.md"
article_published: "终稿完成，待发布"
```

---

## CASE-006-Yoodli

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
redefine_dimensions: 2
rule: "成立（人需要开口说话这件事不可被AI替代）"
flywheel: "半飞轮（方法论壁垒随时间加深，但不是自动传播）"
rrr_verdict: "RR成立，F是方法论壁垒而非传播飞轮"

core_insight_1: "卖设备效率的产品用户永远在比价；卖人的成长，用户的沉没成本是他自己练出来的能力"
core_insight_2: "小团队不自建信任，借别人的信任——Franklin Covey是Yoodli进入企业的信任通道"
core_insight_3: "最深的壁垒不是锁住客户，是让客户在你这里建了家（方法论壁垒>数据壁垒）"
cet_seed: "关掉它之后，你比用它之前更强了，还是更弱了——这是评估任何AI工具的终极问题（CET概念弧第一步）"

three_decisions:
  - "跟着用户信号转B端（从公开演讲→企业培训，用户自己发现的场景）"
  - "借Franklin Covey渠道（160国/大量Fortune 500客户，嵌入其销售培训课程）"
  - "让客户方法论长进系统（Franklin Covey/Korn Ferry/LHH将方法论灌入）"

failure_modes:
  - "传统企业培训（视频+打勾，完课率极低，知道≠会做）"
  - "Gong/Chorus（事后分析，不是事前练习，不同战场）"

china_opportunity: "有，几乎空白"
china_status: "笔试有无数APP，面试几乎没有；考公面试/企业内训是切入点"
china_window: "12-18个月（Yoodli短期不做中文本地化）"

four_path: "观察（关注考公面试/企业培训场景有无人做）"
counterintuitive: "不是让AI替你说，而是让AI帮你练——关掉AI你更强了"
transferable_pattern:
  - "借渠道：找已解决信任问题的中间人，让你的产品让他的产品更值钱"
  - "方法论壁垒：让客户把自己的方法论放进系统，他的离开成本是重建整套体系"
  - "重新定义问题：企业真正要的不是培训内容，是员工真正能用出来"

theory_match: "DOC-D022 RRF（重新定义问题）；DOC-P002 推演公式（约束条件→唯一解）"
comparable_cases: ["CASE-002-Gamma（分发壁垒vs方法论壁垒对比）", "CASE-REF-Lovable（服务门外汉逻辑相通）"]
series_connection: "001（重新定义需求）002（财富公式三验）003（约束条件→借渠道）004（分发壁垒对照）005（用户信号驱动转型）"

source_quality: "A"
teardown_date: "2026-04"
article_file: "cases/2026/006-YOODLI-终稿v4.md"
article_published: "终稿完成，待发布"
```

---

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
transferable_pattern:
  - "激励结构检查：你的定价模式让你有动力做好产品吗？"
  - "先定义结果，再谈收费——定义模糊的地方就是信任崩塌的地方"
  - "价值可见性是定价的前提：看不见价值=定价无依据"
theory_match: "DOC-D021维度跨越（从怎么收钱跳到怎么证明值多少）；DOC-P001财富公式·被留住"
comparable_cases: ["Intercom/Fin（按结果收费的先行者）", "Sierra（从DayOne按结果收费）"]
series_connection: "002（财富公式·被留住的新解读）004（分发壁垒vs标准制定壁垒）006（激励结构对比）"

source_quality: "A"
teardown_date: "2026-04"
article_file: "cases/2026/007-Paid-按结果收费.md"
article_published: "终稿完成，待发布"
```

---

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

---

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

---

（下一个案例卡在这里追加）
