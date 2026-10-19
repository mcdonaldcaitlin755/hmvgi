# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:14**

---

## 🔥 今日头条

**1️⃣ Meta 发布首个前沿模型系列 Muse Wonder，全球前沿竞赛进一步多极化。** 10月12日，Meta 超级智能实验室（Meta Superintelligence Labs，AI 负责人 Alexandr Wang）正式发布 Muse Wonder 与 Muse Wonder Full 两款模型（开发代号"Watermelon"），称其在个人与专业智能体（Agentic）任务、记忆与编程场景达到业界前沿水平。Meta 公布的基准显示其性能与 Anthropic 的 Claude Fable 5.1、OpenAI 的 GPT-6 Astra 相当；在 Artificial Analysis 智能指数 v4.3 中，Wonder Full 得分 56（标准版 52），仅次于 Claude Opus 5.5（58 分）、高于 OpenAI 与 Google 的最强模型（各 53 分）；中文媒体转述称其编程智能体表现与 Claude 并列第一。定价 $4/$20 每百万 token（输入/输出），与 Opus 5.5 同价位；已通过 Meta Model API 与 Muse Code 提供（Full 版限高级订阅，新增 Active Memory / Active Focus 能力）。发布当日 Meta 股价上涨约 3.4%–4.1%（约报 $748）。[来源：TechCrunch/WIRED/NYT/The Verge/新浪科技]

**2️⃣ 微软发布第三代自研 AI 芯片 Maia 300：从"最大押注"到百万颗级部署。** 10月12日于 OCP 全球峰会（圣何塞）亮相：288GB HBM4 显存、18TB/s 带宽；微软称其每兆瓦可产出比"领先 GPU 系统"多 40% 的 token，机架级吞吐为 Maia 200 的 7 倍。微软计划 2027 年起以"多吉瓦级"规模部署超 100 万颗 Maia 300，使其成为自家 AI 服务的主要推理硬件；公司预计今年资本开支超 1,750 亿美元。纳德拉称其为"对自研芯片的最大一笔押注"；当日微软股价涨约 2.4%，英伟达、AMD 承压。[来源：GeekWire/CNBC/Reuters/HPCwire]

---

## ☝ Headlines

- **Meta·Muse Wonder**：Meta 首个前沿模型发布，对标 Claude Opus 5.5/Fable 5.1 与 GPT-6 Astra，$4/$20 定价、发布日股价涨约 3-4%
- **微软·Maia 300**：第三代自研 AI 芯片亮相，2027 年部署超百万颗、能效 +40%/MW
- **亚马逊·Decart**：洽谈约 70 亿美元收购 AI 芯片软件公司 Decart（Anthropic 尽调后退出、亚马逊接手）
- **英国 AI 安全**：白宫解除 17 天冻结，UK AISI 恢复 OpenAI/Anthropic/DeepMind 预发布模型访问；同日英国公布 AI 风险防御包
- **DeepMind·AlphaProof Nexus**：解出 9 个 Erdős 开放数学问题（2 个悬置 56 年）+ 44 个数列猜想，并通过同行评审
- **中国 AI**：大模型周调用量 86.74 万亿 Token（环比 +50.96%）连续 24 周全球第一、前五全为中国模型；美国头部两家厂商则占近九成收入

---

## 📊 分类详报

### 🧠 模型与技术

- **Meta Muse Wonder 更多细节**：该系列由 Meta 超级智能实验室开发（2025 年 6 月招入 Scale AI 创始人 Alexandr Wang 后启动 AI 重构，历时约 14 个月），定位"面向个人与专业智能体任务的前沿模型"，较前代 Muse Spark 明显升级（Artificial Analysis 智能指数 48 → 52/56）。WIRED 评价其"让 Meta 重回 AI 前沿"。社区侧：开发者对比指出 Wonder 定价与 Opus 5.5 完全持平，但在 Meta 自家 14 项基准中有 9 项落后（dev.to 分析）；Full 版目前仅限 Meta 高级 AI 编码订阅用户。[来源：TechCrunch/WIRED/NYT/Artificial Analysis/dev.to]

- **Claude Opus 5.5 Max 首次登顶 Arena 智能体榜**：Anthropic 新模型首次入榜即夺得智能体榜第一，工具幻觉率仅 0.37%；综合榜由 Google gemini-4-argon-high 居首；国产模型 kimi-k3-max 稳居综合榜前 20，qwen3.8-max 等多款保持中上游。[来源：Arena AI 周榜（网易/搜狐转载）]

- **OpenRouter 周度调用数据（10月5日-11日）**：全球总调用量 172 万亿 Token（环比 +3.61%）；中国大模型 86.74 万亿（+50.96%），连续 24 周超过美国（18.97 万亿，+17.1%），约为其 4.6 倍；全球前五全为中国模型——DeepSeek V4.1 Flash（41 万亿、+60%）、智谱 GLM 5.3 Flash（12.2 万亿）、小米 MiMo-V2.6-Flash（11.5 万亿）、阶跃星辰 Step 5 Preview（8.84 万亿）、腾讯 Hy4 preview（8.28 万亿）；Claude Opus 5.5 居第八（5.02 万亿）。[来源：每日经济新闻/OpenRouter 测算]

### 📋 政策与监管

- **英国恢复前沿模型预发布访问权（10月12日）**：白宫逆转此前"企业须先获美国批准才能向英方共享模型"的政策，为期 17 天的冻结解除。英国 AI 部长 Kanishka Narayan 确认：UK AISI 将继续对 OpenAI、Anthropic、Google DeepMind 的最强模型进行发布前安全评估（正评估 Gemini 4 Argon 等系统）；其称目标是让英国"成为全球最难被 AI 攻击的国家之一"。[来源：Quartz/Bloomberg/Firstpost/TheNextWeb]

- **英国公布 AI 风险防御包（10月12日）**：追加系列国家级防御措施——延长"用前沿 AI 审计政府代码"试点（既有两轮试点已发现 1,000+ 潜在漏洞；其中已公布一轮以约 £13,000 的 token 成本发现 407 处弱点）；政府表示或立法保护关键基础设施免受 AI 网络威胁，并着手准备"自主系统脱离人类控制"类事件的应急机制（有专家呼吁"终止开关"）。[来源：Unite.AI/TheNextWeb/bankinfosecurity/resiliencemedia]

- **美国 CAISI 拟"并入"白宫**：路透报道，特朗普政府计划将商务部 AI 标准与创新中心（CAISI）的三名高级官员转入白宫编制、直接向白宫汇报（重组仍在敲定中）；CAISI 此前负责与 OpenAI、Google、微软等开展自愿性模型评估。[来源：Reuters/US News/cryptobriefing]

- **Brad Smith："牛奶受到的监管都比 AI 多"**：微软副董事长兼总裁 Brad Smith 呼吁建立全球统一的 AI 安全规则，包括独立评估机构与面向开发者的"紧急刹车"机制——并称当前 AI 的安全要求比一盒牛奶还少。[来源：Reuters/Fox Business]

- **比尔·盖茨警告（10月11-12日）**：在 CNN 采访中称 AI 是"人类发明过的最危险的技术"，最紧迫威胁是"未来一年内 AI 驱动的网络攻击"；强调不能让企业"自我监管"，并提到社会需讨论如何对 AI 与机器人的使用征税。[来源：CNN/Yahoo Finance]

- **中国：《关于发展新质生产力的意见》持续发酵**：中共中央、国务院 10 月 9 日印发该文件，明确"全面实施'人工智能+'行动"、加快推进 AI 手机/电脑等新一代智能终端应用，并建立技术监测、风险预警与应急响应体系、确保 AI"安全、可靠、可控"；本周进入配套落实期（如工信部"AI 应用服务商培育专项行动"）。[来源：国家发改委/财新/VOA]

- **布鲁金斯学会：AI 智能体（Agent）的全球治理**：发文探讨 AI 智能体跨境运行带来的治理缺口（责任归属、跨国部署合规）。[来源：Brookings]

### 💰 产业与商业

- **亚马逊洽购 Decart（约 70 亿美元）**：WSJ 首发（10月11日晚）——Decart 开发让 AI 模型跨不同芯片高效运行的软件，并研发"世界模型"（模拟 3D 环境）；公司 2023 年成立，今年 5 月估值近 40 亿美元（若按 70 亿成交，较该估值高出约 75%）。此前 Anthropic 8 月曾洽谈约 60 亿美元收购、9 月尽调后放弃；亚马逊为其战略客户并给予 Trainium 芯片早期访问。交易若落地将强化 AWS 自研芯片生态、进一步对冲英伟达依赖。[来源：WSJ/Bloomberg/Calcalist/Quartz]

- **微软 Maia 300 详细规格与部署计划**：288GB HBM4、18TB/s 带宽；每兆瓦 token 数 +40% vs 领先 GPU 系统、机架吞吐 7× vs Maia 200；2027 年"多吉瓦"部署、逾 100 万颗；年内资本开支预期超 1,750 亿美元。市场解读：微软推理算力从"英伟达为主"转向"自研为主"的转折点。[来源：The Verge/Notebookcheck/The Tech Portal/Reuters]

- **英伟达联合 AMD、Google、Meta 发布"开放数据中心规范 v0.7"**：在 OCP 全球峰会上联合发布统一 AI 工厂设施蓝图（覆盖电力架构、冷却、物理布局）；Google、Meta、微软、英伟达另发布"OCP 电网韧性规范"（应对公用事业扰动、快速恢复）；英伟达同时通过 MGX 1.2 开放 Vera Rubin NVL72 机架设计（支持 250kW 级机架），并宣布 ConnectX-10 / BlueField 支持 Google Falcon 传输协议（开放互联再进一步）。[来源：NVIDIA博客/StorageReview/Yahoo Finance]

- **Salesforce 收购以色列 AI 分析公司 Loops（约 3,000 万美元）**：并入 Tableau，主打"agentic analytics"（解释业务指标变动并给出行动建议）；预计 11 月初交割；消息后 CRM 涨约 3%。[来源：CTech/Globes/Proactive Investors]

- **中美 AI 商业化分化（分析）**：Menlo Ventures 数据显示，2025 年 OpenAI + Anthropic 合计占企业 LLM API 支出 67%；其 5 月报告显示两家在追踪的 34 家头部 AI 初创中占 89% 收入；Ramp 数据称首次采购 AI 的企业中 Anthropic 占逾 73% 支出。对照中国侧"调用量份额领先、收入份额有限"的结构——模型能力差距正快速转化为商业收入差距。[来源：新浪科技（投资者内参）]

### 🚀 应用与产品

- **Apple "Welcome Home" 发布会（今日 10月13日，9:00 ET 纽约）**：预计推出智能家居中枢（HomePad 类新品）、新一代 Apple TV 4K、HomePod mini 等；以"新闻稿 + 媒体体验"形式发布，AI 家庭中枢为核心看点。[来源：The Verge/9to5Mac/MacRumors]

- **阶跃星辰 STEPX Neo 智能体手机（今日上海发布）**：阶跃终端"Ready Builder One"发布会推出首款"大模型原生智能体手机"；同日，千问新一代 AI 眼镜现货发售；阶跃星辰将于 10月15日 正式开源 Step 5 Preview（该模型已上线腾讯 WorkBuddy）。[来源：智东西/华尔街见闻/东方财富/IT之家]

- **富士胶片 Synapse Pathology v3.0**（10月12日）：数字病理平台扩展 AI 能力。[来源：BioSpace]

### 🔬 研究前沿

- **DeepMind "AlphaProof Nexus" 解出 9 个 Erdős 开放问题（10月12日集中报道）**：从 353 个未解 Erdős 问题中解出 9 个（其中 2 个自 1970 年起悬置 56 年），另证明 44 个 OEIS 数列猜想；解法先行在线公开、成果通过同行评审——AI 数学推理从"竞赛题"走向真实开放问题的标志性一步。[来源：the-decoder/Reddit/The Daily Star]

- **TikTok CEO 周受资（Shou Zi Chew）：AI 将在 3 年内带来"重大科学突破"**（CNBC，10月12日）——认为 AI 对科学的推动（药物研发、材料等）将在三年内集中兑现。[来源：CNBC]

---

## ⚡ 明日关注

- **10月14日：Anthropic 上市前投资者日（Investor Day）**——已向机构投资者发出邀请（Bloomberg）；正式 IPO 营销或于 11月9日当周启动、目标感恩节前挂牌。市场关注其 ARR 指引与算力承诺兑现节奏（22V Research 视其为"市场内部结构与 AI 前景的重要节点"）。
- **10月15日：台积电 Q3 财报**（14:00 台北时间）——营收预计 NT$1.49 万亿（约 $467 亿、同比 +51%，创纪录）、净利润预计同比 +65%；AI 需求风向标；同周还有 ASML 财报。
- **10月15日：阶跃星辰正式开源 Step 5 Preview**（600B 稀疏 MoE，面向 Agentic 任务）。
- **10月13-16日：TechCrunch Disrupt 2026（旧金山）与 OCP 全球峰会持续**——更多 AI 基础设施/芯片发布与创业公司动向。
- **持续跟踪**：① 英伟达-Reflection AI 谈判进展；② Anthropic IPO 流程（投资者日 → 路演）；③ 英国 AI 立法动向（关键基础设施保护）。

---

## ⚡ 其他新闻

- 志愿服务平台的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/jrp=671
- 周末休闲规划的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/r3X=FAs
- 公共空间照明的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/736
- 个人时间管理的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/lfl
- 居民健康教育的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/m7c
- 城市树木认养的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/123=rdy
- 青年志愿活动的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/deg=713
- 家庭养老规划的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_3d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E7%89%B9%E7%A8%BF?/lfM=a1p
- 无障碍信息设计的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/785
- 公共空间休憩的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/aoc
- 家庭运动计划的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/VWB
- 社区家政服务的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/406=snc
- 便民服务窗口的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/iya=332
- 基层医疗预约的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E5%BD%B1%E8%A7%86?/Bh1=07B
- 电动汽车充电的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/827
- 社区生活指南的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/wxz
- 城市生活记录的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/Vip
- 社区菜市场服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/138=ker
- 数字公共文化的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/aib=361
- 校园节能行动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9E%AD%E6%9C%9B?/Dlh=dPt
- 社区设施共享的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/784
- 无障碍出行的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/ksd
- 社区商业活力的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/JAs
- 科技馆参观体验的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/113=dfe
- 消防知识宣传的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/zgw=054
- 非遗体验活动的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%B0%91%E7%94%9F?/8lx=tS7
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/480
- 农产品消费体验的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/qwk
- 家庭用电安全的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/p07
- 街区更新实践的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/215=fel
- 社区活动报名的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/dtv=591
- 社区体育组织的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E7%BD%91%E6%98%93%E4%BF%9D%E9%99%A9?/FGh=REX
- 农业科普体验的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/123
- 儿童阅读角的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/xnm
- 智慧城市体验的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/MDT
- 社区共享书架中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/246=wbd
- 城市骑行环境的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/jal=966
- 公共空间休憩的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/MWF=tkl
- 城市博物馆服务的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/584
- 城市建设科普的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/nzm
- 居家适老化改造中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/yqT
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/298=qvh
- 城市便民驿站的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/vti=810
- 社区心理支持的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E7%9F%A5%E4%B9%8E%E8%88%86%E6%83%85?/dKy=SLW
- 青少年心理健康的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/340
- 志愿服务平台的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/kde
- 社区公共卫生的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/62F
- 开放式学习空间的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/260=zmp
- 节假日出行安排的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/dod=622
- 城市步行友好的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/hOi=iVB
- 公共服务咨询的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/789
- 城市树木认养的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/jjj
- 环境教育课程的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/w76
- 社区宠物管理的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/855=ial
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/brm=992
- 社区菜市场服务的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%88%9B%E6%8A%95%E8%B4%A2%E7%BB%8F?/UIS=xvQ
- 老年学习活动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/668
- 家庭运动计划的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/mzf
- 地方美食文化的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/kXA
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/272=lsj
- 数字阅读服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/ywm=559
- 数字创意课程的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%BF%E4%BA%A7?/mI4=Opq
- 儿童友好空间的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/759
- 城市公共艺术的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/kpo
- 社区协商议事的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/dvz
- 数字阅读服务的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/421=ggc
- 科学健身方法的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/kmn=304
- 社区消防演练的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E5%A8%B1%E4%B9%90?/iyK=THw
- 城市应急广播的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/747
- 社区运动空间的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/pyk
- 家庭理财科普的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/UrY
- 家庭安全提示的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/969=mwp
- 社区体育组织的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/aog=664
- 社区互助网络的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%8F%A3%E8%AF%80_%E4%BD%B3%E4%BF%A1%E8%B4%A2%E7%BB%8F?/tkt=vPX
- 基层医疗预约中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/956
- 城市树木认养的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/urx
- 公园休闲体验的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/txm
- 新能源出行的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/828=isx
- 运动安全知识的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/gdn=254
- 城市住房服务的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88-%E7%A8%B3%E8%B5%9A_%E7%BD%91%E6%98%93%E6%89%8B%E8%AE%B0?/xAY=XqM
- 青少年编程学习的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/400
- 城市地名文化的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/ppn
- 社区故事采集的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/YfP
- 公共设施维护的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/896=sms
- 地方美食文化的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/xcx=206
- 科学信息获取的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F99%25_%E8%A5%BF%E7%8F%AD%E8%B4%A2%E7%BB%8F?/IEK=0oJ
- 社区活动报名的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/456
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/zil
- 健康信息获取的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/rq7
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/782=jnx
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/ahx=311
- 生活垃圾回收的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%9A%E4%B9%B0%E6%B3%95_%E5%87%A4%E5%87%B0%E5%BD%B1%E8%A7%86?/tgB=8cp
- 家庭阅读计划的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/231
- 青少年科技社团的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/lzb
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/LSU
- 社区活动报名的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/588=pks
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/pka=807
- 开放数据应用的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E7%BD%91%E8%B5%8C%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A?/1bl=Zfq
- 城市展览体验的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/752
- 基层健康档案的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/pqe
- 儿童友好空间的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/44D
- 绿色生活实践的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/021=slf
- 家庭饮食安排的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/mgl=928
- 机器学习入门的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/WSP=2fs
- 安全出行教育的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/144
- 城市博物馆服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/aqo
- 城市公共空间的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/f0u
- 儿童安全出行的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/179=jxe
- 智能手机助老的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/nob=832
- 非遗课堂体验的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E5%BF%AB3%E6%8A%95%E8%B5%8410%E5%85%83%E4%B8%80%E5%B0%8F%E6%97%B6%E8%B5%9A%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6?/SsS=cim
- 科学教育活动的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/637
- 数字创作工具的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/scq
- 开放数据应用的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/kOo
- 校园安全教育的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/487=sby
- 租房信息服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/lij=698
- 城市步行环境的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%A7%84%E5%BE%8B%E4%B8%80%E5%8F%A5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A7%81%E5%8B%9F?/fef=XNf
- 创业经验分享的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/492
- 老年人文化生活的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/uvq
- 数字学习资源的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/dOj
- 城市人文观察的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/896=tsh
- 街区小店体验从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/gji=223
- 社区托育服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E5%88%86%E6%9E%90%E7%9A%84_%E8%B1%86%E7%93%A3%E5%BD%A9%E7%A5%A8?/E4y=Dku
- 老年智能设备的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/051
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/muf
- 基层服务创新的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/GGo
- 读书会组织的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/653=bec
- 老年智能设备的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/ygx=152
- 劳动教育实践的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%88%99_%E5%A4%AE%E8%A7%86%E6%95%99%E8%82%B2?/1e8=LUT
- 老旧小区改造的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/493
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/lxn
- 农业科普体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/74P
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/400=pez
- 数字创作工具的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/bbc=317
- 读书会组织的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E9%A1%BA%E8%A7%84%E5%BE%8B_%E4%B8%AD%E8%AA%89%E8%B4%A2%E7%BB%8F?/zOW=SlD
- 绿色办公实践的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/638
- 公共交通信息服务的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/vcw
- 社区休闲设施中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/QYm
- 社区志愿服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/450=hbn
- 家庭消费规划的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/ena=752
- 在线学习体验的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E7%8E%A9%E6%B3%95_%E5%BF%AB%E6%89%8B%E6%A5%BC%E5%B8%82?/1iR=xfe
- 绿色校园实践的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/082
- 街头绿植养护的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/gsc
- 城乡交通衔接的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/YwD
- 邻里互助活动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/583=aqe
- 家庭养老规划的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/gct=369
- 居家适老化改造的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%A1%BA%E5%BA%8F_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/sXL=saV
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/745
- 地方戏曲体验的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/cna
- 个人时间管理的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/L4I
- 城市住房服务的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/532=jje
- 社区教育资源的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/mbv=657
- 家庭食品保存的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C-%E5%8F%A3%E8%AF%80_%E7%BD%91%E6%98%93%E9%80%9F%E8%A7%88?/hnd=D3b
- 儿童运动体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/224
- 城市住房服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/pli
- 开放式学习空间的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/k3T
- 公共设施使用的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/940=pds
- 社区活动报名的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/rlg=440
- 线上办事服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_36%E6%B0%AA%E7%99%BE%E7%A7%91?/SAo=8H4
- 家庭理财科普的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/935
- 个人数据管理的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/xcu
- 乡村休闲旅游中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/EIO
- 科学教育活动的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/240=qwy
- 社区体育组织的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/fua=766
- 户外活动组织中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E9%95%BF%E6%9C%9F%E6%9C%80%E7%A8%B3%E5%85%AC%E5%BC%8F_%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91?/Hl6=7pR
- 农村环境治理的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/319
- 社区文化节活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/esj
- 公共交通接驳的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/IDN
- 非遗体验活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/263=ykq
- 绿色生活实践的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/nkp=671
- 乡村教育资源的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E5%9B%BD%E7%91%9E%E8%B4%A2%E7%BB%8F?/NIS=bVH
- 青年职业探索的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/497
- 社区教育资源的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/xnn
- 科学运动指导的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/WHk
- 家庭健康管理的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/638=bez
- 社区垃圾回收的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/neo=902
- 街区小店体验的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C6%E6%9C%9F%E5%BF%85%E4%B8%AD%E7%9A%84%E6%96%B9%E6%B3%95_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%B4%A2%E7%BB%8F?/c7g=Rsh
- 老年人出行服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/581
- 在线教育体验的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/kwk
- 街道综合服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/bmp
- 青年职业探索的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/937=yjk
- 校园阅读活动的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/fli=823
- 数字公共文化的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%85%E8%B5%A2%E7%9A%84%E6%96%B9%E6%B3%95_%E8%B4%A2%E7%BB%8F%E7%A7%91%E6%8A%80?/9Vy=5Nw
- 公共服务沟通的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/912
- 个人数据管理的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/ewa
- 绿色生活实践的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/Wva
- 公共文化活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/070=opl
- 家庭环保行动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/ipz=824
- 健康饮食教育的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/A4f=f9R
- 城市便民驿站的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/123
- 社会体育指导的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/fhv
- 生活垃圾回收的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/NMt
- 医院导诊服务的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/598=uyp
- 数字创作工具的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/bzi=091
- 乡村文化活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/l8R=N8A
- 环境教育课程的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/103
- 社区共享书架的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/msm
- 社区邻里服务的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/UEj
- 社区邻里服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/092=hxq
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/eml=006
- 科技馆参观体验的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%92%8C%E5%80%BC%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E5%8D%B3%E5%88%BB%E5%BD%A9%E7%A5%A8?/ly8=6Hw
- 城市体育设施的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/492
- 青少年科技社团的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/qht
- 社区防暑服务的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/KON
- 无障碍出行的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/197=tnt
- 健康步道使用的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/tjh=656
- 城市地名文化的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E5%BF%AB33d%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E8%B1%86%E7%93%A3%E4%BF%A1%E6%89%98?/FVY=5bZ
- 校园安全教育的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/077
- 数字资源检索的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/dns
- 社区公共议事中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/AHV
- 基层服务创新的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/818=obf
- 科学教育活动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/rdb=935
- 数字政务体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E8%88%86%E6%83%85?/xw4=M8f
- 数字地图应用的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/109
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/kub
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/kro
- 城市应急广播的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/369=jmu
- 数字素养提升的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/liq=771
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E5%BF%AB3%E5%A4%A7%E5%8F%91%E5%BF%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E7%BD%91%E6%98%93%E8%AF%BB%E6%8A%A5?/wtW=fiC
- 校园节能行动的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/252
- 数字设备回收的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/aje
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/O3x
- 城市应急广播的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/449=gyi
- 城市公共空间的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/hck=806
- 文化讲座服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%80%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/8kh=LfM
- 城市社区治理的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/847
- 城市体育设施的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/rln
- 公交站点体验的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/0cZ
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/445=drh
- 低碳社区实践的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/rwc=082
- 城市游园体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E6%AD%BB%E8%A7%84%E5%BE%8B_360%E4%BA%B2%E5%AD%90?/7uI=y1a
- 儿童友好空间的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/717
- 城市雨天出行的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/zqi
- 家庭养老规划的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/oJ8
- 科学运动指导的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/465=lfh
- 社区家政服务的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/ivj=213
- 运动安全知识的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%93%94%E5%93%A9%E6%B3%95%E6%B2%BB?/DQF=4lU
- 乡村生态旅游的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/767
- 社区防暑服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/yly
- 安全出行教育的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/EW9
- 小区公共照明的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/828=qgo
- 社区应急准备的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/ewl=909
- 科学教育活动的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E5%95%A5_%E5%BF%AB%E6%89%8B%E4%BA%B2%E5%AD%90?/EBn=p2z
- 城市绿色交通的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/409
- 城乡交流活动的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/xvl
- 绿色校园实践的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/WgC
- 数字公共文化的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/445=wzo
- 青少年科普实践的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/llj=466
- 科普展览体验的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BE%AE%E4%BF%A1%E7%BE%A4%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%99%BE%E7%A7%91?/PCI=Sxg
- 公共卫生宣传的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/481
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/yjq

---

## 📈 关键数据（10月11-13日）

| 指标 | 数值 | 变化/说明 |
|------|------|------|
| 全球大模型周调用量（10/5-11） | 172 万亿 Token | 环比 +3.61%（OpenRouter 测算） |
| 中国大模型周调用量 | 86.74 万亿 Token | 环比 +50.96%；连续 24 周全球第一 |
| 美国大模型周调用量 | 18.97 万亿 Token | 环比 +17.1% |
| Meta Muse Wonder 定价 | $4 / $20（每百万 Token 入/出） | 与 Claude Opus 5.5 同价位 |
| Meta / 微软股价（10/12） | Meta 约 $748（+3.4%–4.1%）；MSFT +2.4% | 模型与自研芯片发布驱动 |
| 微软 Maia 300 | 288GB HBM4；18TB/s；+40% tokens/MW | 2027 年部署超 100 万颗；资本开支预期 >$1750 亿（今年） |
| 亚马逊洽购 Decart | 约 $70 亿 | 较 5 月估值（近 $40 亿）高约 75% |
| AlphaProof Nexus 成果 | 9 个 Erdős 问题 + 44 个数列猜想 | 其中 2 题悬置 56 年；已通过同行评审 |
| 英国网络防御试点 | 累计发现 1,000+ 潜在漏洞 | 单轮试点：407 处弱点/£13,000 token 成本 |

---

*本简报由 Hermes Agent 自动生成*  
*数据来源：Google News、Reuters、Bloomberg、TechCrunch、The Verge、WIRED、NYT、CNBC、GeekWire、每日经济新闻、财联社、智东西、华尔街见闻、the-decoder  @PHWT7等*  
*仅供参考，不构成投资建议*
