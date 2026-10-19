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

- 社区活动策划的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/C1a
- 社区防暑服务的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/593=ozf
- 家庭运动计划的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/rpj=694
- 老年学习活动的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/xRn=M36
- 城市地名文化的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/336
- 城市公共艺术的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/sbi
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/bM0
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/666=iqm
- 城市便民驿站的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/lls=346
- 图书馆数字服务的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%BE%8E%E6%B9%83%E7%89%B9%E7%A8%BF?/9PL=Y0e
- 小区电梯维护的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/491
- 数字便民地图的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/dyt
- 通勤路线规划的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/h0x
- 家庭健康管理的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/067=atr
- 文化讲座服务的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/zwg=657
- 乡村产业科普的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E6%B3%95%E5%BE%8B?/Sc6=mwA
- 邻里互助活动的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/794
- 社区互助网络的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/hqe
- 本地旅行体验的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/72M
- 公共空间导览的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/267=urj
- 社区故事采集的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/nyc=219
- 社区养老服务的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP_%E6%82%89%E5%B0%BC%E8%B4%A2%E7%BB%8F?/MAK=K3f
- 校园阅读活动的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/610
- 社区体育组织的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/djj
- 物业服务沟通的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/667
- 图书馆亲子空间的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/370=ztb
- 城市慢行系统的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/iwy=949
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6%E5%88%86%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%A7%91%E6%8A%80%E8%B4%A2%E7%BB%8F?/ZkE=VIK
- 线上阅读资源的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/549
- 社区艺术活动的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/fmd
- 社区便利生活的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/90s
- 公共设施维护的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/544=vdi
- 安全出行教育的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/cmk=602
- 老年友好服务的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/Lhi=xpP
- 数字支付体验的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/612
- 数据分析入门的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/gqh
- 城市适老服务的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/PRj
- 城市运动公园的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/653=xum
- 环境教育课程中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/htz=882
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E9%9F%B3%E4%B9%90?/BKY=c7J
- 便民维修服务的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/466
- 家庭节能实践的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/dzv
- 乡村产业科普的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/1q9
- 学校食育活动的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/061=osx
- 光伏知识科普的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/hdz=743
- 科学信息获取的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/Uit=bgM
- 非遗体验活动中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/993
- 读书会组织的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/qme
- 城市地名文化的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/wtM
- 科普展览体验的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/228=ceh
- 城市绿道建设的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/czc=406
- 线上办事服务的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E7%BA%AA%E5%AE%9E?/gKK=rwm
- 劳动教育实践的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/688
- 青少年科技社团的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/ozw
- 城市水环境观察的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/WvD
- 个人数据管理的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/949=xwh
- 社区修缮行动的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/sgq=178
- 乡村阅读空间的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%85%AC%E7%9B%8A?/824=1yp
- 学校体育活动的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/419
- 社区邻里服务的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/omk
- 城市夜间照明的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/ULR
- 机器人科普活动的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/122=ode
- 周末休闲规划的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/hwc=741
- 家庭照护支持的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%B5%B7%E6%B9%BE%E8%B4%A2%E7%BB%8F?/lpU=IwI
- 家庭环保行动的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/662
- 家庭饮食安排的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/hen
- 社区知识分享的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/0g8
- 社区交通安全的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/924=oba
- 本地消费场景的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/ofa=352
- 城市可持续生活的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_6%E5%88%86%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89?/q1T=pmw
- 城市应急科普的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/086
- 数字阅读服务的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/kpp
- 街区更新实践的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/euL
- 公共场所导视的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/947=suk
- 校园节能行动的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/cky=612
- 老年智能设备的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%A3%E8%AF%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/aIq=eHz
- 公共交通接驳的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/293
- 城市绿道建设的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/kea
- 社区老年食堂的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/7t1
- 儿童运动体验的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/045=cgm
- 个人数据管理的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/kep=498
- 家庭园艺实践的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%89%8D%E7%9E%BB_6%E5%88%86%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/JNm=MOg
- 个人时间管理的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/356
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/eko
- 城乡公共服务的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/dE1
- 社区共享书架的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/684=rrm
- 本地历史资料的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/onj=232
- 音乐欣赏活动的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/c7S=06x
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/382
- 数字创意课程的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/rsg
- 社区庭院绿化的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/4X7
- 公共服务评价的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/801=sys
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/oys=313
- 租房信息服务的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/5KI=tDT
- 数字艺术创作的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/191
- 安全出行教育的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/jez
- 地方旅游导览的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/8Bk
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/067=ufh
- 城市住房服务的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/vhf=391
- 亲子科普活动的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/sar=MxP
- 图书借阅体验的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/388
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/cff
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/TFM
- 网络安全教育的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/451=ane
- 远程协作工具的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/hun=977
- 智能手机助老的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/lVp=WnM
- 社区花园共建的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/730
- 运动安全知识的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/ver
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/N69
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/215=vbu
- 街区更新实践的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/qtd=531
- 安全出行教育的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A?/Dbi=1az
- 节假日出行安排的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/207
- 基层健康服务从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/taz
- 乡村公共阅读的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/djL
- 科学健身方法的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/417=zaa
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/skn=524
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/oad=11k
- 社区托育服务的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/959
- 休闲运动入门的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/odj
- 乡村电商实践的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/Vpw
- 运动安全知识的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/677=cuz
- 社区家政服务的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/cql=602
- 家庭急救准备的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/8Cv=Tzp
- 儿童友好街区的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/154
- 社区慢性病防控的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/clk
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/nN2
- 公共服务预约的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/279=xab
- 小微企业服务的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/zju=805
- 公共设施使用的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_36%E6%B0%AA%E6%9C%8D%E9%A5%B0?/psR=ISe
- 租房信息服务的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/503
- 社区便利生活的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/ykh
- 公共设施维护的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/vFC
- 城市人文观察的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/060=qpn
- 网络信息辨识的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/brv=904
- 社区学习活动的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E9%97%AE%E5%8D%B7?/qQS=OiA
- 生活技能分享的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/807
- 农产品品牌传播的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/dzk
- 街区更新实践的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/CZ5
- 社区文化传播的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/585=adl
- 非遗课堂体验的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/loa=661
- 图书馆亲子空间的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_7033%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A4%BE%E5%8C%BA?/bUQ=RHm
- 在线学习体验的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/782
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/eqe
- 应急物资管理的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/Nj6
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/656=djv
- 城市绿色交通的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/uwt=813
- 社区花园共建的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_7033%E5%BD%A9%E7%A5%A8-APP_%E9%9B%85%E8%99%8E%E5%9B%9E%E6%9C%9B?/ge2=VRx
- 城市噪声观察的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/129
- 公共场所导视的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/ggl
- 老年人文化生活的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/9tw
- 机器人科普活动中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/468=uia
- 社区交通安全的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/vsm=221
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_7033%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E7%9B%B4%E6%92%AD?/zgN=x6q
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/556
- 社区协商议事的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/zkv
- 社区家校合作的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/IzJ
- 节气饮食文化从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/872=aah
- 绿色生活实践的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/csp=090
- 城市夜间生活的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2?/nHt=sNH
- 个人信息保护的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/737
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/kto
- 社区便民集市的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/FB3
- 城市人文观察的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/273=fnf
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/ejq=333
- 家庭网络使用的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_7033%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/lOv=bVj
- 城市文化路线的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/913
- 数字公共文化的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/him
- 公共服务沟通的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/0YO
- 开放数据应用的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/715=hmp
- 校园安全教育的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/sag=749
- 城市步行环境的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E8%AF%BB%E6%8A%A5?/LPg=h17
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/640
- 城市休闲步道的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/hwc
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/omo
- 家庭健康管理的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/627=qvn
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/xtw=334
- 乡村公共文化的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_7033%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%BF%E4%BA%A7?/6nM=cOi
- 公共交通信息服务的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/548
- 城市文明出行的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/utv
- 周末休闲规划的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/XQM
- 城市公共饮水的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/930=fvn
- 课后服务体验的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/opv=238
- 家庭理财科普的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_7033%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E8%A7%82%E5%AF%9F?/Bs9=ZMY
- 亲子科普活动的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/184
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/qrw
- 科学运动指导的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/n7h
- 社区公共卫生的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/644=sjp
- 社区法律科普的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/rtq=489
- 家庭教育交流的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E6%A6%9C%E5%8D%95?/NDk=JE3
- 社区宠物管理的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/870
- 口袋公园建设的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/zad
- 家庭用电安全的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/Bs0
- 数字素养提升的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/301=rru
- 城市运动公园的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/zot=708
- 文明养宠科普的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_7033%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/Eek=uev
- 青少年职业启蒙的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/016
- 非遗课堂体验的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/zex
- 小区停车协商的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/i65
- 就业技能培训的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/376=fvg
- 城乡交流活动的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/rbn=674
- 绿色办公实践的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_7033%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/Tp7=e2Z
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/016
- 社区读书角建设的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/tgn
- 家庭志愿活动的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/uPk
- 小区电梯维护的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/761=dyw
- 街区道路维护的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/puc=958
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_7033%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E8%B4%A2%E7%BB%8F?/HA4=KCA
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/109
- 个人时间管理的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/brs
- 小区公共照明的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/vFf
- 公共场所导视的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/046=wnp
- 家庭环保习惯的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/mpf=350
- 数字设备回收的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_707%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%B8%AF%E8%82%A1%E8%B4%A2%E7%BB%8F?/tWr=ZFB
- 家庭科学教育的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/448
- 邻里共享空间的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/vua
- 城市文明出行的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/oGm
- 儿童阅读角的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/555=tpd
- 环境教育课程的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/bhi=070
- 家庭饮食安排的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_707%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%AE%BA%E5%9D%9B?/2Dl=qct
- 租房信息服务中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/410
- 城市公共艺术中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/jlx
- 日常摄影记录的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/6ts
- 无障碍出行的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/956=fzs
- 社区协商议事的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/gzz=291
- 小微企业服务的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA?/le6=vbI
- 公共服务预约的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/959
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/lir
- 校园节能行动的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/uMt
- 社区绿色空间的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/136=qgj
- 城市慢跑路线的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/can=168
- 电子商务服务的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_707%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E5%91%A8%E6%8A%A5?/eKr=1nA
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/657
- 公共交通接驳的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/pfb
- 城市空气科普的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/qf2
- 绿色出行服务的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/725=qmt
- 城市应急广播的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/zwc=274
- 科技馆参观体验的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/87d=Cw3
- 新能源出行从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/422
- 社会体育指导的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/aye
- 开放数据应用的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/cx1
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/034=rhw
- 文化遗产保护科普中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/qam=919
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E7%AE%80%E6%8A%A5_707%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E4%BC%97%E6%B5%8B?/lg1=PZC
- 社区信息发布的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/149
- 数字支付体验的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/ncy
- 老年人日常照护的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/E9W
- 个人时间管理的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/377=ocn
- 在线教育体验的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/pxh=971
- 校园安全教育的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%91%E6%99%AE%E5%85%AC%E5%91%8A_707%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/Mu1=ICV

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
