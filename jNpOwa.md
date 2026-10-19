# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:13**

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

- 健康饮水科普的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/tzi=257
- 在线学习体验的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E8%A7%A3%E5%AF%86?/p1c=13R
- 青少年职业启蒙的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/629
- 家庭健康科普中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/rfi
- 社区菜市场服务的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/T39
- 垃圾分类指导的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/925=vkf
- 社区老年食堂的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/uqf=364
- 儿童友好空间的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%B1%87%E5%B8%82?/YgX=AwI
- 图书馆数字服务的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/913
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/bkf
- 儿童阅读角的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/9IW
- 家庭园艺实践的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/135=ywj
- 城市可持续生活的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/nhg=724
- 社区科普课堂的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%94%BF%E5%8A%A1?/O8U=FLo
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/337
- 环境监测科普的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/anr
- 小微企业服务的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/L4f
- 城市空气科普的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/693=wne
- 城市步行友好的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/elq=830
- 新能源出行的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E7%9F%A5%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%88%B7%E5%A4%96?/UHc=nzF
- 无障碍出行的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/907
- 城市慢跑路线的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/bps
- 数字艺术创作中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/PRN
- 终身学习资源的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/646=pgt
- 生活技能分享的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/ono=959
- 乡村文化空间的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/DYT=5Sp
- 青少年科技社团的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/156
- 节约用水实践的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/miw
- 节气饮食文化的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/T7G
- 公交站点体验的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/998=tod
- 市民意见收集的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/uep=856
- 校园节能行动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/INJ=AYG
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/590
- 垃圾分类指导的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/dlj
- 城市雨天出行的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/zwc
- 户外活动组织的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/539=xwg
- 社区快递服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/amw=265
- 读书会组织从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/QnP=O8V
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/320
- 小区停车协商的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/sal
- 城市地名文化中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yTQ
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/033=vds
- 家庭消费规划的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eao=829
- 口袋公园建设的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/RcO=nUx
- 老年友好服务的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/326
- 节日文化体验的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/rkx
- 儿童友好空间的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/cR2
- 数字支付体验的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/824=yfq
- 乡村公共服务的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/yxd=292
- 城市展览体验的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/4Ow=CAF
- 城市人文观察的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/514
- 学校食育活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/fkx
- 城市博物馆活动的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/ANW
- 社区读书角建设的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/540=gul
- 城市适老服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/qvo=990
- 公共卫生宣传的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%BD%91%E6%98%93%E4%B9%A6%E7%94%BB?/2UA=G6j
- 老年友好服务的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/596
- 城市文化路线从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/uuw
- 社区体育组织的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/bkY
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/616=rox
- 城市夜间照明的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/swv=649
- 在线教育体验的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB?/Tud=r9B
- 家庭安全提示的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/695
- 社区公共卫生的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/rak
- 城乡公共服务的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/8B5
- 生活技能分享的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/047=clt
- 社区体育组织中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/zuq=640
- 本地消费场景的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP_%E5%87%A4%E5%87%B0%E6%97%A5%E6%8A%A5?/mux=YsD
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/542
- 无障碍信息设计的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/fex
- 生成式工具使用的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/BF7
- 社区活动策划的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/118=oej
- 网络信息辨识的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/oil=980
- 公共场馆服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_360%E5%BF%AB%E8%AE%AF?/k5m=Pn6
- 机器学习入门的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/627
- 便民服务窗口的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/oyw
- 城市公共厕所的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/Yr7
- 城市公共厕所的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/755=dov
- 社区休闲设施的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/zsx=969
- 城市文明出行的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E4%BD%93%E8%82%B2?/fWv=OGR
- 在线教育体验的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/818
- 骑行路线规划的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/xaf
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/Oee
- 数字创作工具的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/875=ggr
- 社区健康讲座的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/xzy=320
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%84%E6%B5%8B_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E5%BE%97%E7%89%A9%E8%A1%8C%E6%83%85?/Siu=gmO
- 社区托育服务的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/643
- 电子商务服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/lhj
- 农产品品牌传播的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/tpX
- 公共设施维护的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/575=yrk
- 城市应急科普有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/lve=937
- 数字创作工具的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/NPK=clw
- 农产品品牌传播的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/069
- 社区垃圾回收的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/gmw
- 家庭安全提示的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/RDK
- 城市博物馆活动的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/164=ibi
- 数字支付体验的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/dak=954
- 亲子科普活动的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/iou=cpC
- 城市文明出行的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/491
- 城市绿色交通的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/sbb
- 老年智能设备的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/35A
- 职业技能学习的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/714=dzf
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/qct=727
- 老年数字阅读的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E8%BE%9F%E8%B0%A3?/nrR=HNv
- 数字资源检索的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/723
- 公共空间照明的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/aot
- 小区公共照明的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/phR
- 本地消费场景的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/827=yxt
- 公共交通接驳的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/gbf=494
- 低碳社区实践从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E5%81%A5%E5%BA%B7?/I9t=0DV
- 儿童户外活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/524
- 家庭阅读计划的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/khu
- 社区法律科普的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/9Ak
- 社区健康讲座的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/455=jsa
- 个人信息保护的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/voy=579
- 老年智能设备的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E6%99%9A%E6%8A%A5?/hWA=CQG
- 小区停车协商的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/092
- 社区便利生活的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/yix
- 公共设施维护的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/OKr
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/909=jbo
- 传统手工艺体验的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/vpf=893
- 城市公共标识的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8D%83%E5%B8%86?/eeu=KCv
- 智能家居应用的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/430
- 公交无障碍服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/wwu
- 基层健康档案的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/l1Q
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/437=tjb
- 公共服务指南的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/kjz=872
- 城市文化路线的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_%E8%80%80%E4%B8%96%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%A5%BC%E5%B8%82?/C9g=ZwJ
- 青少年户外教育从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/963
- 公共场所导视的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/axg
- 社区运动空间的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/NnZ
- 科学健身方法的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/720=ykk
- 数字课堂应用的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/inq=198
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%9C%9F%E8%B4%A7?/xCq=BrZ
- 城市运动公园有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/103
- 街区更新实践的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/fnn
- 家庭运动计划的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/VTW
- 社区读书角建设的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/069=fgf
- 农业科普体验的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/qds=890
- 街区道路维护的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%9C%88%E5%AD%90?/Jca=PKo
- 社区垃圾分类的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/244
- 学校食育活动的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/oni
- 社区信息发布的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/Ndo
- 农村环境治理的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/231=ive
- 家庭急救准备的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/fcq=877
- 社区信息发布的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%8D%E9%A5%B0?/YCU=E3R
- 基层健康服务的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/550
- 城市便民驿站的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/zbw
- 老年人文化生活的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/168
- 小区公共照明的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/705=ukt
- 零废弃生活尝试的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/oah=586
- 地方文化传播的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9E%AD%E6%9C%9B?/siq=Ws8
- 老年数字阅读的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/659
- 数字课堂应用的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/uzj
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/Ftz
- 居民健康教育的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/525=snp
- 公共场所导视的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/ipj=093
- 城市公共饮水的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%99%9A%E6%8A%A5?/tS1=t2v
- 公益活动组织的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/090
- 健康信息获取的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/jsi
- 食品安全科普的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/2gF
- 低碳社区实践的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/242=lwn
- 小微企业服务中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/kxr=305
- 邻里互助活动的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%90%E4%BF%A1%E8%B4%B7?/OWB=DSF
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/996
- 公共服务指南从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uqs
- 城市博物馆服务的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/D3O
- 社区共享书架的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/896=til
- 数字生活课堂的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ite=180
- 街区绿化养护的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%A7%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eZm=Fqu
- 生活服务数字化的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/197
- 创业经验分享的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/nzl
- 城市适老服务的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/236
- 便民维修服务的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/081=hjd
- 公园无障碍服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/fpi=459
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E8%A7%82%E7%82%B9?/1Sd=HZb
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/485
- 儿童运动体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/jpa
- 城市便民驿站的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/k6O
- 城市住房服务的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/389=pib
- 个人时间管理的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/njm=477
- 城乡交通衔接中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%80%80%E4%B8%96-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E5%81%A5%E5%BA%B7?/MP0=WNm
- 生活技能分享的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/746
- 人工智能科普的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/edw
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/2fK
- 公共场所导视的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/557=lps
- 城市骑行环境的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/stf=335
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E8%80%80%E4%B8%96-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%84%E8%AE%BA?/NZa=P3c
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/585
- 儿童户外活动的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/adv
- 急救知识普及的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/H3s
- 校园节能行动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/069=lbi
- 职业技能学习的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/pkj=167
- 青少年科普实践的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E7%8E%B0_%E8%80%80%E4%B8%96-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%A1%8C%E6%83%85?/AkW=f65
- 社区体育组织的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/336
- 在线学习体验的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/lnr
- 街区道路维护从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/6DV
- 志愿服务平台的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/905=elk
- 儿童运动体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/vhn=496
- 儿童阅读角的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_%E8%80%80%E4%B8%96-APP_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/IgP=nU3
- 数字学习资源的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/631
- 家庭饮食安排的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/dhg
- 电子商务服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/f7Z
- 数字课堂应用的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/372=wra
- 社区垃圾回收的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/yjk=686
- 小区电梯维护的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E8%80%80%E4%B8%96-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%8F%B7%E5%A4%96?/t8i=x1t
- 智能手机助老的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/125
- 社区运动空间的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/snr
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/uvp
- 公共服务咨询的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/458=qjz
- 青少年户外教育的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/csv=562
- 城市绿道建设的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%8A%96%E9%9F%B3%E9%97%AE%E7%AD%94?/X5J=sJs
- 数字资源检索的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/711
- 乡村休闲旅游的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/hfa
- 数字艺术创作的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/sgp
- 数字资源检索的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/781=pzh
- 创业经验分享的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/tbk=244
- 城乡交流活动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E8%80%80%E4%B8%96-%E7%99%BB%E5%BD%95_%E6%99%BA%E5%88%A9%E8%B4%A2%E7%BB%8F?/Qob=rI1
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/658
- 社区环保活动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/ndm
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/fga
- 气象科普传播的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/719=aty
- 家庭饮食安排的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/ymy=663
- 便民服务窗口的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E8%80%80%E4%B8%96-%E6%B3%A8%E5%86%8C_%E6%9C%9F%E8%B4%A7%E8%B4%A2%E7%BB%8F?/9l3=8Z6
- 休闲运动入门的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/282
- 公共空间安全的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/jam
- 劳动教育实践的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/N9e
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/765=iqr
- 校园阅读活动的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/jhb=939
- 地方文化传播的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E8%80%80%E4%B8%96-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_36%E6%B0%AA%E9%94%90%E8%AF%84?/4qD=fqb
- 公共场所导视的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/622
- 数字档案服务的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/xpc
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/qrG
- 社区儿童活动的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/693=wbk
- 校园阅读活动的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/nbe=747
- 老旧小区改造的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%80%80%E4%B8%96-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/ish=FDS
- 公共服务预约的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/807
- 社区交通安全的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/xbq
- 生活垃圾减量的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/yaN
- 城市适老服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/262=qul
- 社区心理支持的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/kth=300
- 跨代沟通活动的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%80%80%E4%B8%96-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/00u=VHP
- 节能家电使用的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/536
- 学校体育活动的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/kie
- 学校体育活动的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/HlY
- 社区知识分享的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/163=trt
- 邻里互助活动的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/zjz=705
- 智慧停车服务的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%80%80%E4%B8%96-%E9%A6%96%E9%A1%B5_%E8%B1%86%E7%93%A3%E5%85%AC%E5%91%8A?/dX4=iR3
- 数字支付体验的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/970
- 家庭养老规划的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E8%80%80%E4%B8%96-%E5%AE%98%E6%96%B9_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/zlu

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
