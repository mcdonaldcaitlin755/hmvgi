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

- 城市应急广播的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/zwh=241
- 公园无障碍服务的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3_U8%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E7%95%85%E6%B8%B8?/tmD=mmQ
- 户外活动组织的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/306
- 家庭健康科普的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/ozz
- 社区读书角建设的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/dqt
- 数据分析入门的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/649=nvw
- 消防知识宣传的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/ppo=988
- 科学运动指导的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_U8%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%B1%86%E7%93%A3%E5%9B%BD%E5%86%85?/ZGn=OlU
- 环境教育课程的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/525
- 家庭志愿活动的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/kld
- 终身学习资源的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/TIO
- 地方民俗记录的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/123=qaj
- 社区活动策划的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/ofh=166
- 家庭科学教育的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_U8%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E7%BB%8F%E6%B5%8E?/PFU=cNF
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/810
- 个人时间管理的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/svz
- 城市树木认养的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/1KV
- 基层健康档案的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/805=vwg
- 城乡公共服务的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/byz=463
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_U8%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/9jg=85j
- 公共交通接驳的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/178
- 图书借阅体验的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/zuz
- 城市应急科普的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/RFR
- 职业技能学习的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/922=tec
- 社区便民集市的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/ans=784
- 绿色校园实践的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_U8%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E4%BA%BA%E7%89%A9?/h0X=vUP
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/516
- 社区便民服务的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/kdv
- 社区法律科普的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/PJI
- 公共空间安全的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/001=lht
- 社区应急准备的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/juk=765
- 城市骑行环境的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E6%8E%A8%E8%8D%90_U8%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E6%89%91%E6%B1%87%E5%B8%82?/g8W=Cek
- 公共健身器材的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/627
- 老旧小区改造的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/ffz
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/9da
- 校园安全教育的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/207=rha
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/cap=209
- 电动汽车充电的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_U8%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E4%BF%A1%E8%B4%B7?/39h=mQo
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/138
- 老年人文化生活的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/ixj
- 食品安全科普的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/oNs
- 社区停车服务的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/381=jix
- 绿色出行服务的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/wrx=832
- 邻里互助活动的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_U8%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E9%A3%9F%E5%93%81?/s0I=olg
- 社区知识分享的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/759
- 居民健康教育的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/cqz
- 家庭食品保存的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/SSH
- 开放式学习空间的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/132=ifm
- 电子商务服务中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/wex=030
- 科普展览体验的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%9C%9F%E8%B4%A7?/J6a=ujO
- 社区菜市场服务的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/149
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/dlt
- 城市文明出行的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/y3C
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/487=dex
- 数字设备回收的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/qkn=641
- 本地消费场景的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/AAj=cir
- 社区共享书架的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/176
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/tge
- 社区绿色空间的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/cio
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/165=osj
- 校园阅读活动的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/pez=848
- 旧物循环利用的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E4%BA%BA%E5%A4%A7?/X1i=xQV
- 周末休闲规划的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/097
- 青年就业服务的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/uoi
- 公共空间照明的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/7Hj
- 节能家电使用的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/700=gno
- 城市夜间照明中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/eff=251
- 乡村生活观察中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360%E7%A8%8E%E5%8A%A1?/WQ1=Pk8
- 城市噪声观察的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/972
- 无障碍信息设计的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/iww
- 儿童友好街区的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/GVj
- 新能源知识普及的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/943=zoj
- 城乡交流活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/pgn=885
- 社区交通安全的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/tsb=khJ
- 公共设施使用的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/230
- 气象科普传播的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/mkg
- 绿色快递包装的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/Hfm
- 食品安全科普的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/807=aef
- 读书会组织的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/cbm=810
- 环境监测科普的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8C%BB%E8%8D%AF?/5IN=ZYp
- 家庭志愿活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/990
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/aav
- 创业经验分享的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/r0u
- 城市人文观察的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/003=dge
- 家庭科学教育的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/jxa=994
- 城市共享单车的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B1%87%E5%B8%82?/jwM=KyC
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/261
- 儿童户外活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/zdh
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/sGb
- 社区教育资源的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/675=hbn
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/zov=148
- 校园社团活动的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%93%94%E5%93%A9%E8%A7%82%E5%AF%9F?/37Y=6cn
- 无障碍出行的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/907
- 城市运动公园的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/rij
- 日常摄影记录的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/oCL
- 家庭照护支持的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/639=xmr
- 非遗体验活动的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/rxz=976
- 社区故事采集的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/HCJ=K9C
- 数字设备回收的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/206
- 线上办事服务的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/xih
- 居民健康教育的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/nZb
- 校园节能行动的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/765=wgi
- 音乐欣赏活动的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/soz=308
- 数字资源检索的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%A7%86%E9%A2%91?/t05=EcY
- 社区教育资源的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/208
- 乡村生态观察的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/mby
- 公共场馆服务的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/Xqt
- 公共场所导视的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/124=lhm
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/ult=994
- 公共场馆服务有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E4%BA%B2%E5%AD%90?/6bE=a2H
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/088
- 邻里共享空间的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/qkt
- 日常摄影记录的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/09u
- 全民健身活动的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/242=nqn
- 乡村生态观察的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/hkp=256
- 老年友好服务的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-APP_%E8%8A%92%E6%9E%9C%E6%A1%A3%E6%A1%88?/8yG=MFb
- 乡村阅读空间的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/249
- 就业技能培训的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/env
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/ZZ8
- 社区防暑服务的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/945=psv
- 社区家校合作的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/eme=552
- 社区故事采集的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_VIP%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/U7S=s4u
- 租房信息服务的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/852
- 运动安全知识的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/clt
- 电动汽车充电的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/mJM
- 志愿者培训交流的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/360=bor
- 社区生活指南的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/ukj=842
- 乡村教育资源的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%BD%91%E6%98%93%E5%AE%B6%E5%B1%85?/r2D=u93
- 城乡公共服务的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/197
- 城乡交流活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/crh
- 便民服务窗口的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/mPj
- 节约用水实践的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/820=ole
- 休闲运动入门的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/ioz=652
- 城市游园体验的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_VIP%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E6%96%B9?/fB9=nmm
- 文化场馆预约的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/905
- 青少年户外教育的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/ykh
- 节约用水实践的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/zf7
- 科普展览体验的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/118=dll
- 药品使用科普的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/zcr=326
- 城市公共空间的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%A0%8F%E7%9B%AE_VIP%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E4%BA%AC%E4%B8%9C%E5%AE%A0%E7%89%A9?/gbP=lrB
- 便民维修服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/782
- 节假日出行安排中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/imn
- 节假日出行安排的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/Gwu
- 绿色快递包装的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/131=dbt
- 青年职业探索的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/fdv=023
- 城市住房服务的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/E0x=QI9
- 家庭理财科普的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/953
- 社区公共议事有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/qdf
- 电子商务服务的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/EtA
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/552=ekb
- 老年人出行服务的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/cjr=559
- 城市游园体验的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/7XH=z3i
- 校园节能行动的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/420
- 青年职业探索的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/vsc
- 跨代沟通活动的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/lUi
- 乡村教育资源的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/148=sob
- 基层医疗预约的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/tys=762
- 社区知识分享的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_VIP%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1?/jfG=xf8
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/007
- 节能家电使用中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/rgf
- 数字档案服务从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/PMX
- 乡村阅读空间中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/744=xnx
- 城市步行友好的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/das=537
- 公共场馆服务的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_VIP%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%90%8C%E7%9B%88%E8%B4%A2%E7%BB%8F?/j6b=cGI
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/031
- 家庭用电安全的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/tzj
- 农产品品牌传播有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/eZh
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/601=hpr
- 社区垃圾回收的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/cli=225
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_VIP%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E7%89%B9%E7%A8%BF?/XWZ=oKd
- 老年友好服务的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/813
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/kcr
- 城市基础设施的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/Xgl
- 数字阅读服务的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/941=zjk
- 乡村文化空间的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/gtp=181
- 城市文明实践的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%91%E9%81%93_VIP%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E6%97%B6%E6%8A%A5?/WI3=You
- 文明养宠科普的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/834
- 急救知识普及的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/vdt
- 青年就业服务的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ojP
- 节气饮食文化的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/999=upo
- 物业服务沟通的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/hrm=668
- 数字生活课堂的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_tt%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Xla=L38
- 青年职业探索的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/952
- 家庭健康管理中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/ueg
- 科学信息获取的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/ff0
- 数字艺术创作的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/618=ehl
- 城市适老服务的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/llt=282
- 数据分析入门的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/SMr=RU0
- 开源技术交流的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/611
- 个人信息保护的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/jan
- 社区安全巡查的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/ZPt
- 农村环境治理的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/436=kbh
- 居民健康教育的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/jsz=815
- 城市公共厕所的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/bT7=Zh9
- 农产品消费体验的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/746
- 休闲运动入门的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/ine
- 青年职业探索的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/qP6
- 文化场馆预约的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/697=qof
- 数字支付体验的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/mau=668
- 公共空间照明的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/tjX=CRT
- 公益活动组织的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/849
- 乡村休闲旅游的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/dni
- 城乡公共服务的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/ZEW
- 乡村电商实践的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/503=ayl
- 数字支付体验的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/xhj=756
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E8%B4%A2%E7%BB%8F_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E5%9B%BE%E9%9B%86?/rGc=Hmt
- 城市文化路线的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/566
- 公交无障碍服务的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/rgl
- 科学观察活动的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/vcY
- 社区应急准备的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/417=sjt
- 社区托育服务的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/zjr=551
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_tt%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%87%A4%E5%87%B0%E8%AF%BB%E6%8A%A5?/yIJ=amN
- 健康信息获取的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/598
- 社区阅读服务的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/rph
- 家庭志愿活动的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/CYS
- 数字资源检索的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/544=nmn
- 农贸市场环境的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/dig=788
- 社区阅读服务的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%B8%AF%E5%8F%A3%E8%B4%A2%E7%BB%8F?/w0o=vo4
- 老旧小区改造的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/926
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/aof
- 城市雨天出行的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/Cn9
- 城市体育设施的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/599=wwz
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/yzr=611
- 市民热线服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/ydB=A2J
- 城市文明出行的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/970
- 休闲运动入门的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/dur
- 新能源出行的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/hez
- 周末休闲规划的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/879=nje
- 开放数据应用的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/jgs=577
- 口袋公园建设的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_tt%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E7%A4%BE%E8%AE%BA?/8CA=nfH
- 小区公共照明的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/278
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/aep
- 线上办事服务的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/3Ff
- 市民意见收集的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/184=iss
- 农产品品牌传播的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/hva=959
- 社区学习活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_tt%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E7%BB%BC%E8%89%BA?/uo1=6Bh
- 小微企业服务的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/719
- 家庭用电安全的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/acq
- 环境监测科普的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/01y
- 城市农夫市集的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/963=nff
- 乡村文化活动的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/dgr=042
- 老旧小区改造的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_tt%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/gmP=L1h
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/564
- 线上办事服务的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/wnt
- 全民健身活动的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/i7P
- 城市游园体验的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/084=wpk
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/byf=004
- 数字政务体验的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%B5%84%E6%BA%90_tt%E5%BD%A9%E7%A5%A8-APP_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/JZR=QdV
- 健康饮水科普的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/384
- 开放式学习空间从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_tt%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BA%AC%E4%B8%9C%E9%97%AE%E5%8D%B7?/rdc

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
