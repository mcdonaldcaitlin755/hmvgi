# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:20**

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

- 数字课堂应用的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/lre=653
- 城市步行友好有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Yml=qzd
- 数字创作工具的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/512
- 家庭健康管理的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/chx
- 地方文化传播的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/xKv
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/325=qmr
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/nma=088
- 图书馆数字服务的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E8%BD%AC%E8%BD%BD?/Nuv=D1D
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/903
- 家庭理财科普的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/qri
- 社区便民服务的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/VwV
- 社区生活指南的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/273=pjz
- 老年人出行服务的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/ekx=673
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%B4%B7?/ZZI=f2D
- 居家适老化改造的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/617
- 社区托育服务的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/zqf
- 社区修缮行动的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/KP5
- 社区快递服务的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/028=wnw
- 城市噪声观察的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/nom=329
- 骑行路线规划的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85?/brI=Zp5
- 城市步行环境的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/630
- 城市应急科普的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/zst
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/sSW
- 绿色校园实践的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/196=blq
- 农业科普体验的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/wly=624
- 家庭消费规划的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%AE%B6%E7%94%B5?/Pch=Eab
- 老年智能设备中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/515
- 公共空间照明的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/xjb
- 青年志愿活动的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/0kE
- 社区家校合作的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/978=krl
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/ewq=604
- 社区绿色空间的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/2SI=n4r
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/969
- 儿童安全出行的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/yah
- 数字生活课堂的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/NuW
- 公共空间休憩的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/564=qqy
- 软件开发学习的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/oxa=383
- 全民阅读推广的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BD%93%E8%82%B2?/DCm=7Fw
- 休闲运动入门的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/907
- 数字创作工具的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/ojx
- 社区休闲设施的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/EBO
- 社区知识分享的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/751=wmf
- 社区健康讲座的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/sdu=836
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%B3%95%E5%BE%8B?/4pU=3uj
- 街区绿化养护的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/645
- 农业科普体验的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/upg
- 社区故事采集的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/FFR
- 老旧小区改造的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/488=muh
- 社区便民集市的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/nuh=689
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%BE%97%E7%89%A9%E6%88%BF%E4%BA%A7?/Nc7=p4B
- 文明养宠科普中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/632
- 运动安全知识的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/yqs
- 街区更新实践的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/0g1
- 健康信息获取的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/153=yxe
- 儿童友好空间的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/aju=477
- 城市微更新实践的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%88%AA%E8%BF%90%E8%B4%A2%E7%BB%8F?/xA8=tJA
- 家庭照护支持的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/423
- 社区菜市场服务的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/wix
- 智能家居应用的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/bga
- 智能手机助老的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/958=ljk
- 文化遗产保护科普的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/iqg=729
- 城市空气科普的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E4%BA%BA%E7%89%A9?/bcw=MFM
- 公共服务评价的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/279
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/uts
- 社区应急准备的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/pHC
- 科学信息获取的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/357=oeq
- 公共空间照明的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/iog=550
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%A2%E7%BB%8F?/Vl0=S8v
- 公共服务指南的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/942
- 数字创意课程的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/vxz
- 数字公共文化的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/yxH
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/019=miw
- 公园休闲体验的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/gpj=277
- 公园休闲体验的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/0JL=HIk
- 小区停车协商的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/328
- 气象科普传播的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/yem
- 城市树木认养的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/Hpb
- 社区文化传播的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/292=oaa
- 公共场所导视的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/xmh=308
- 家庭消费规划的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E7%9B%B4%E6%92%AD?/FwX=Q8m
- 城市噪声观察的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/271
- 医院导诊服务的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/jey
- 数字学习资源的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/SmL
- 校园社团活动的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/847=zuf
- 乡村生活观察的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/mtw=801
- 校园节能行动的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E4%BC%97%E6%B5%8B?/jS7=4cA
- 药品使用科普的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/629
- 社区运动空间的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/rcw
- 城市步行环境的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/gF4
- 社区快递服务有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/435=fuz
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/ryp=215
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83?/6s6=FVf
- 图书借阅体验的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/620
- 数字创意课程的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/ucd
- 绿色办公实践的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/Ypv
- 公共服务评价的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/962=vkm
- 线上办事服务的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/cng=128
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BC%98%E9%85%B7%E5%AE%9E%E5%BD%95?/hA6=XIl
- 远程协作工具中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/686
- 青年职业探索中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/dna
- 乡村公共文化的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/NTA
- 街区更新实践的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/343=uax
- 地方旅游导览的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/anb=061
- 线上办事服务的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%86%E8%AF%B4_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%8A%95%E8%B5%84?/obG=0bA
- 社区托育服务的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/749
- 社区协商议事的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/lpy
- 智慧停车服务的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/Xfv
- 社区活动策划的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/518=wrm
- 城市空气科普的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/fpv=641
- 城市步行环境的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/7mC=eic
- 社区便利生活的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/601
- 社区健康讲座的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/wud
- 社区学习活动的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/DFN
- 节能家电使用的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/764=fhp
- 街道综合服务的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/ask=424
- 数字阅读服务的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/qgH=C2g
- 老年友好服务的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/257
- 社区活动策划的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/klj
- 街道综合服务的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/mTJ
- 健康饮食教育有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/118=lip
- 老年人出行服务的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/aoe=064
- 社区共享书架的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/Moq=nrF
- 科学健身方法的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/167
- 消防知识宣传的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/yqz
- 家庭急救准备的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/a9j
- 数字档案服务的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/098=mua
- 家庭收纳实践的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/nce=213
- 文化场馆预约的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/ixQ=UjT
- 城市公共厕所的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/899
- 社区心理支持的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/ezj
- 社区垃圾分类的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/LJM
- 乡村产业科普的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/372=uzl
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/ntd=767
- 城市体育设施的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E6%97%85%E6%B8%B8?/lxW=NtQ
- 社区法律科普的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/037
- 安全出行教育的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/nob
- 城市农夫市集的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/LeQ
- 青少年编程学习的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/667=oql
- 环境监测科普的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/syd=462
- 城市公共标识的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%9E%E5%BD%95?/HxM=7Kz
- 光伏知识科普的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/552
- 图书馆亲子空间的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/abo
- 社区阅读服务的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/POH
- 街道综合服务的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/776=fgh
- 青年职业探索的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/lkz=353
- 城市水环境观察的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%81%8C%E5%9C%BA?/YXV=3Qv
- 社区便民集市的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/828
- 社区科普课堂的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/djp
- 社区宣传栏更新中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/lmu
- 食品安全科普的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/098=ifb
- 城市农夫市集的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/cxp=098
- 线上阅读资源的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/Mp1=9Le
- 城市人文观察的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/564
- 家庭安全提示的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/eki
- 社区花园共建的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/iQX
- 绿色校园实践的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/558=akt
- 青少年科普实践的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/jut=723
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_360%E6%8A%95%E8%B5%84?/TrZ=4yZ
- 公共服务数字化从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/022
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/who
- 食品配送体验中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/hVe
- 图书馆活动策划的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/061=nzv
- 地方戏曲体验的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/nfz=512
- 无障碍出行的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E7%AE%80%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E5%8E%BF%E5%9F%9F?/SSj=OWL
- 公园休闲体验的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/993
- 数字素养提升的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/vhs
- 城市应急科普的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ocI
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/071=vsh
- 乡村公共阅读的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/dqv=095
- 社区花园共建的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ixq=yLM
- 节气饮食文化的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/210
- 邻里共享空间中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/hgz
- 城市公共自行车的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/kSF
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/574=gtx
- 家庭网络使用的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/nkw=081
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/mRW=ajl
- 青少年编程学习的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/921
- 社区信息发布的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/sus
- 家庭养老规划的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/Mam
- 科学观察活动的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/881=drp
- 城市休闲步道的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/jib=895
- 社区绿色空间的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E5%81%A5%E5%BA%B7?/gNU=6zm
- 家庭节能实践的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/212
- 家庭环保习惯的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/bmk
- 社区消防演练的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/KF9
- 城市体育设施的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/779=smm
- 健康饮食教育的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/fsv=141
- 生活技能分享的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_360%E7%BE%8E%E9%A3%9F?/WdC=daJ
- 城市绿色交通的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/723
- 数字生活课堂的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/bvj
- 基层健康档案中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/97V
- 公共卫生宣传的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/568=hnk
- 城市展览体验的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/kkx=869
- 城市应急广播的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E7%A4%BE%E5%8C%BA?/R0k=1oZ
- 城市生活记录的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/055
- 城市空气科普的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/wri
- 社区消防演练的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/bfO
- 乡村文化活动的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/547=hdy
- 城市应急科普的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/ikx=987
- 城市地名文化的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/kcN=kwB
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/581
- 文化场馆预约的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/zdv
- 青少年心理健康的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/PIM
- 乡村阅读活动中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/870=cmq
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/tub=811
- 社区体育组织的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E6%98%9F%E5%BA%A7?/rIy=AYV
- 城市公共座椅的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/366
- 数字支付体验的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/mst
- 健康饮食教育的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/ueL
- 街区更新实践的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/775=xgn
- 绿色消费选择的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/ffb=806
- 人工智能科普的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E4%BF%A1%E8%B4%B7?/8EX=ItE
- 家庭照护支持的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/269
- 音乐欣赏活动的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/ywx
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/0wM
- 城市公共标识的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/847=dee
- 农产品品牌传播的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/tpi=761
- 跨代沟通活动的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%9F%BA%E9%87%91?/naI=R2S
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/959
- 儿童友好空间的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/etn
- 社区活动空间的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/SX1
- 校园社团活动中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/887=pfg
- 青年职业探索的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/gkm=669
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/hAL=NOQ
- 科学教育活动的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/258
- 户外活动组织的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/djz
- 农业科普体验的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/1NA
- 公共卫生宣传的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/220=cjb
- 科学健身方法的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/fei=390
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/Zh9=Wy7
- 图书借阅体验的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/486
- 青年志愿活动的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/esc
- 图书借阅体验的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/sXE
- 公益活动组织的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/136=jju
- 老年人文化生活中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/obs=623
- 职业技能学习的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%90%E5%8E%86%E5%8F%B2?/1ED=Cbw
- 线上阅读资源从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/651
- 线上办事服务的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/zma
- 城市应急科普的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/91N
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/522=eox
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/bbm=398
- 社区绿色空间的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%9B%BD%E9%99%85?/hQf=g9t
- 青少年户外教育的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/280
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/ksh
- 数字创意课程的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/3y8
- 城市步行环境的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/304=gev
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/wzn=641
- 生活技能分享的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%85%E5%BA%94%E8%BE%9F%E8%B0%A3?/Nms=va2
- 家庭理财科普的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/845
- 学校体育活动的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E9%87%91%E5%BD%A9%E6%B1%87%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/ggm

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
