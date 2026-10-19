# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:16**

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

- 基层健康档案的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/103
- 城市社区治理的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/ejq
- 城乡交流活动的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/LGD
- 科学运动指导的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/145=ypp
- 社区家政服务的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/aad=062
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E7%9B%8A?/XSr=MRm
- 消防知识宣传的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/122
- 科学教育活动的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/spc
- 公共空间导览的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/rHU
- 家庭急救准备的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/347=ixn
- 户外活动组织的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/xag=492
- 科普展览体验的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E9%80%89%E5%8F%B7%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%97%AE%E5%8D%B7?/8WS=nsY
- 社区商业活力的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/316
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/kvb
- 地方文化传播的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/piE
- 日常摄影记录的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/610=qog
- 便民信息查询的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/ilf=279
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%B4%B7?/0LV=ELK
- 本地消费场景的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/566
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/hyb
- 数据分析入门的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/GfV
- 城市社区治理的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/117=xqg
- 家庭理财科普的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/hjz=865
- 文化讲座服务的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E8%A7%84%E5%88%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/Xsj=pNv
- 乡村教育资源的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/035
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/xcb
- 老年人出行服务的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/tFS
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/732=fqn
- 便民维修服务的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/rvs=028
- 基层健康档案的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/m8h=XTX
- 城市基础设施的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/015
- 骑行路线规划的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/vfs
- 节日文化体验的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/ygf
- 通勤路线规划的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/288=oxg
- 低碳社区实践的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/khm=904
- 社区停车服务有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8D%81%E5%A4%A7%E9%80%89%E5%8F%B7%E6%8A%80%E5%B7%A7_%E7%99%BE%E5%BA%A6%E6%97%B6%E6%8A%A5?/FWG=hsx
- 公共服务数字化的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/527
- 城市可持续生活的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/qwk
- 医院导诊服务的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/p75
- 青年志愿活动的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/835=rex
- 个人数据管理的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/xla=129
- 地方旅游导览的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BF%AB3%E8%B4%AD%E4%B9%B0%E5%85%AC%E5%BC%8F_%E6%99%A8%E6%8A%A5%E8%B4%A2%E7%BB%8F?/xhn=Imv
- 个人时间管理的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/621
- 城市文明实践的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/isz
- 个人信息保护的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/rDY
- 乡村文化活动的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/766=xmg
- 乡村阅读空间的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/tqi=751
- 健康信息获取的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%80%8E%E4%B9%88%E9%80%89%E5%8F%B7%E6%AF%94%E8%BE%83%E5%AE%B9%E6%98%93%E4%B8%AD_%E5%BF%85%E5%BA%94%E6%9C%8D%E9%A5%B0?/Gah=S5p
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/543
- 数字创作工具的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/khw
- 基层健康档案的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/yaW
- 图书馆亲子空间的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/821=kdv
- 光伏知识科普的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/yhg=771
- 节能家电使用从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E9%80%89%E6%8B%A9%E6%8A%80%E5%B7%A7_%E8%8A%92%E6%9E%9C%E8%B5%84%E8%AE%AF?/P1o=tOA
- 机器人科普活动的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/779
- 消防知识宣传的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/gwz
- 老年数字阅读的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/zon
- 乡村阅读空间的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/495=vno
- 老年人文化生活的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/ybo=218
- 公共场所导视的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7_%E5%BF%85%E5%BA%94%E5%85%AC%E7%9B%8A?/J98=ohp
- 地方美食文化的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/986
- 生成式工具使用的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/zbs
- 日常摄影记录的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/c4L
- 社区家校合作的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/530=uus
- 校园阅读活动的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/dpy=010
- 公共空间安全的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E5%BF%AB3%E9%80%89%E5%8F%B7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/799=9YE
- 公园亲子设施的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/278
- 数字生活课堂的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/utq
- 社区慢性病防控的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/Bwg
- 运动安全知识的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/517=vcc
- 生活垃圾回收的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/ffa=371
- 城市公共自行车的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%A5%87%E4%B9%9D%E8%BD%AC%E5%9B%BE%E8%A7%A3_%E9%A1%BA%E4%B8%B0%E6%B3%95%E6%B2%BB?/bKO=T9t
- 数字创意课程的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/385
- 家庭照护支持的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/eet
- 城市生活服务的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/3in
- 课后服务体验的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/242=iwk
- 社区文化节活动的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/ual=421
- 智能家居应用的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E6%80%8E%E6%A0%B7%E9%80%89%E5%8F%B7%E6%89%8D%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E?/ODw=Ctx
- 城市适老服务的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/265
- 数字学习资源的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/jmj
- 城市休闲步道的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/LPR
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/907=pzs
- 街区绿化养护的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/wqj=621
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E7%9F%A5%E9%81%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F--KOM-G_36%E6%B0%AA%E8%82%A1%E7%A5%A8?/WMe=4Xn
- 家庭志愿活动的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/406
- 城市水环境观察的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/buc
- 消防知识宣传的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/VV6
- 城乡公共服务的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/611=rhg
- 城市体育设施的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/kos=698
- 乡村教育资源的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E4%BD%93%E8%82%B2?/MDC=7w2
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/361
- 节约用水实践的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/lfw
- 食品配送体验的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/gpl
- 传统手工艺体验的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/081=zgu
- 应急物资管理的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/nat=317
- 街区更新实践的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E7%8E%87%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BA%AA%E5%AE%9E?/tCd=m3M
- 城市体育设施的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/965
- 租房信息服务的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/hhy
- 户外活动组织的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/spy
- 城市步行友好的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/618=amb
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/zdc=182
- 社区阅读服务的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E6%94%BB%E7%95%A5_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/hm4=A5C
- 社区教育资源的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/192
- 城市体育设施的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/wwv
- 城市建设科普的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/99a
- 在线学习体验的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/628=shl
- 志愿服务平台的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/sjg=626
- 家庭消费规划的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E7%BE%8E%E5%A6%86?/Y8u=4f6
- 周末休闲规划的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/711
- 公共文化活动的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/mny
- 居家适老化改造的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/HYu
- 社区儿童活动的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/591=oex
- 城乡公共服务的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/drh=122
- 乡村休闲旅游的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%8E%A9%E4%B8%AD%E5%A5%96%E8%B5%94%E5%A4%9A%E5%B0%91_%E8%84%89%E8%84%89%E8%BE%9F%E8%B0%A3?/2na=9QJ
- 老年人文化生活的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/918
- 无障碍信息设计的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/pxy
- 户外活动组织的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/xMg
- 城市社区治理的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/553=khy
- 社区公共议事的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/jbn=241
- 社区活动报名的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB3%E6%B8%B8%E6%88%8F%E8%A7%84%E5%88%99%E4%B8%AD%E5%A5%96_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/NMG=LvA
- 智能手机助老的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/440
- 智慧城市体验的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/mih
- 数字生活课堂的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/u5y
- 数字公共文化的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/127=ayw
- 居民健康教育的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/khw=240
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E4%BB%8B%E7%BB%8D%E5%9B%BE_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/7uY=I9P
- 青少年科普实践的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/640
- 乡村阅读活动的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/yzq
- 健康信息获取的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/GYH
- 就业技能培训的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/081=dir
- 公共服务评价的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/arm=291
- 志愿者培训交流的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E5%8F%8A%E4%B8%AD%E5%A5%96%E9%87%91%E9%A2%9D_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8A%A1?/eSB=CqU
- 社区文化传播的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/429
- 邻里共享空间的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/nxo
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/Fle
- 城市便民驿站的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/607=xfx
- 乡村文化活动的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/oqr=588
- 家庭节能实践的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E6%A6%82%E7%8E%87%E8%A1%A8%E5%9B%BE_%E5%A4%B4%E6%9D%A1%E9%9F%B3%E4%B9%90?/jLg=kgR
- 数字学习资源的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/765
- 社区活动空间的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/ygx
- 老年智能设备的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/ss4
- 社区信息发布的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/761=vaz
- 运动安全知识的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/kxh=031
- 青年职业探索的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E7%8E%A9%E7%9A%84_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/AQd=Am6
- 生成式工具使用的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/467
- 乡村文化空间的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/xeu
- 城市噪声观察的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/Hp6
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/455=gxt
- 基层健康档案的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/rfz=232
- 社区垃圾分类的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB3%E6%80%8E%E4%B9%88%E4%B9%B0%E5%AE%B9%E6%98%93%E4%B8%AD%E5%A5%96_%E6%96%B0%E6%B5%AA%E5%8C%BB%E8%8D%AF?/usy=47m
- 社区艺术活动的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/537
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/yzb
- 数字资源检索的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/kG0
- 社区宣传栏更新中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/915=pls
- 青年志愿活动的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/oal=203
- 地方旅游导览中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB3%E7%9A%84%E7%8E%A9%E6%B3%95%E4%B8%AD%E5%A5%96%E8%A7%84%E5%BE%8B_%E5%98%89%E6%B1%87%E8%B4%A2%E7%BB%8F?/fp2=bMs
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/350
- 公园休闲体验的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/guw
- 城市公共自行车的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/W80
- 便民信息查询的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/389=jdx
- 社区儿童活动的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/nze=015
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%8A%E6%9C%9F%E5%BC%80%E4%BB%80%E4%B9%88%E4%B8%8B%E6%9C%9F%E5%BF%85%E5%87%BA%E8%A7%84%E5%BE%8B_%E5%A4%AE%E8%A7%86%E6%92%AD%E6%8A%A5?/5mN=f9K
- 儿童户外活动的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/352
- 数字支付体验中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dkb
- 城市生活服务的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/Mo5
- 城市公共空间的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/459=qwk
- 周末休闲规划的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/vxg=738
- 数字创意课程的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_%E5%BF%AB3%E5%AE%98%E7%BD%91%E6%8A%80%E5%B7%A7_%E5%8D%8E%E6%B3%B0%E8%B4%A2%E7%BB%8F?/RFQ=SKK
- 全民阅读推广的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/473
- 地方戏曲体验的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/rpv
- 城市便民驿站的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/Z9s
- 社区家校合作的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/366=eki
- 城市展览体验的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/kiy=933
- 社区手工活动中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E5%9C%A8%E7%BA%BF%E5%BF%AB3%E6%8A%80%E5%B7%A7_%E7%9F%A5%E4%B9%8E%E6%94%BF%E5%8D%8F?/VO9=a3D
- 城市社区治理的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/433
- 城市农夫市集的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/vzm
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/0YG
- 地方戏曲体验的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/809=bjn
- 公共服务预约的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/xud=051
- 社区老年食堂的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E4%B8%87%E8%83%BD%E5%85%AC%E5%BC%8F_%E8%B0%B7%E6%AD%8C%E5%81%A5%E8%BA%AB?/4GD=Kcs
- 地方文化传播的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/300
- 街区小店体验的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/kpd
- 街头绿植养护的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/3X1
- 志愿服务平台的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/775=ysj
- 社区健康讲座的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/lcm=784
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%B5%B0%E5%8A%BF%E8%AF%80%E7%AA%8D_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/48o=cVY
- 老年人出行服务的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/149
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/buf
- 农村环境治理的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/1Ya
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/857=yhe
- 数字公共文化的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/hpb=740
- 社区生活指南的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_345678%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/8L1=USH
- 社区垃圾分类的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/845
- 城市应急广播的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/rvk
- 儿童户外活动的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/df9
- 数字公共文化的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/226=vnw
- 城市骑行环境的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/yfh=074
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_13458-02679%E4%B8%80%E5%8F%8D%E4%B8%80%E9%A1%BA%E4%B9%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%B6%E8%AF%84?/wLR=K1E
- 数字课堂应用的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/939
- 开放式学习空间的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/fxm
- 社区教育资源的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/UFL
- 社区防暑服务的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/655=sfl
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/yji=117
- 智慧城市体验的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E8%AF%80%E7%AA%8D_%E5%8C%97%E6%AC%A7%E8%B4%A2%E7%BB%8F?/oa5=os2
- 校园安全教育的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/494
- 社区志愿服务的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/uqk
- 儿童友好空间的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/fKI
- 社区健康讲座的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/170=ccl
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/hqb=351
- 家庭消费规划的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%88%86%E6%9E%90%E8%B5%B0%E5%8A%BF%E5%88%A4%E6%96%AD%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E8%82%A1%E7%A5%A8?/Gsf=JZW
- 青少年科普实践的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/021
- 城市绿色交通的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/cud
- 社区停车服务的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/x8e
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/653=jxc
- 基层健康服务的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/asp=531
- 终身学习资源的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%8F%A3%E8%AF%80%E5%92%8C%E6%8A%80%E5%B7%A7_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/sdH=czH
- 家庭陪伴活动的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/178
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/dle
- 社区艺术活动的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/9vn
- 网络信息辨识有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/442=hfd
- 街区更新实践的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/mqo=858
- 社区安全巡查的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E7%8E%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A?/YTp=Ajq
- 基层医疗预约的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/619
- 城市运动公园从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/xlr
- 老年人出行服务的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/rO7
- 健康步道使用的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/515=suf
- 家庭饮食安排的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/iht=688
- 数据分析入门的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%9C%80%E5%90%8E%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E8%BE%93_%E6%90%9C%E7%8B%97%E5%BF%AB%E6%8A%A5?/2UE=zqt
- 健康饮水科普的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/460
- 全民健身活动的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/swe
- 家庭健康管理的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/wgf
- 数字便民地图的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/858=ymd
- 急救知识普及从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/oto=655
- 食品配送体验的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD_%E5%A4%AE%E8%A7%86%E7%A7%91%E6%8A%80?/RVZ=Nyr
- 数字档案服务的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/091
- 家庭消费规划的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/htk
- 地方美食文化的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/cwf
- 城市建设科普中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/505=dyp
- 城市夜间照明的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/yqm=358
- 城市游园体验的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%BF%AB3_%E7%A0%8D%E9%BE%99%E7%9A%84%E5%85%AC%E5%BC%8F_36%E6%B0%AA%E6%88%BF%E4%BA%A7?/gHR=QFP
- 老旧小区改造的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/179
- 食品配送体验的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/gtx
- 城市宠物友好空间的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/9bm
- 社区学习活动的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/984=eir
- 校园安全教育的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/guo=074
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E4%B8%89%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E8%A7%84%E5%BE%8B_%E7%BD%91%E6%98%93%E9%97%AE%E5%8D%B7?/OXi=wP2
- 药品使用科普的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E8%BA%AB?/424
- 社区慢性病防控的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E8%BA%AB?/zdn
- 环境监测科普的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E8%BA%AB?/StZ
- 新能源知识普及的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E9%A1%BA%E5%8F%A3%E6%BA%9C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%81%A5%E8%BA%AB?/366=xhr

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
