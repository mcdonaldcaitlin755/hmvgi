# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 城市博物馆活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/KU6
- 数字课堂应用的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/025=ulr
- 老年智能设备的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/fis=731
- 社区托育服务的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E8%B4%A2%E7%BB%8F%E6%96%87%E6%91%98?/MiG=6Rx
- 社区托育服务的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/100
- 社区法律科普的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/yfk
- 社区家政服务的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/1Vu
- 在线学习体验的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/979=noo
- 城乡公共服务的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/jni=601
- 垃圾分类指导的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%B3%A8%E5%86%8C_%E9%A1%BA%E4%B8%B0%E9%80%9F%E8%A7%88?/Utf=f17
- 乡村文化空间的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/497
- 公共空间安全的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/dqm
- 家庭教育交流的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/CSo
- 地方民俗记录的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/447=oim
- 健康信息获取的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/zkv=011
- 软件开发学习中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%A4%B4%E6%9D%A1%E6%95%99%E8%82%B2?/Xjs=Cs4
- 地方民俗记录的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/751
- 乡村电商实践的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/jhb
- 节能生活方式的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/RRZ
- 社区便利生活的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/493=rre
- 社区修缮行动的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/lih=338
- 电子商务服务的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%99%9A%E6%8A%A5?/Zfn=ptc
- 科学健身方法的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/135
- 文化场馆预约的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/uhm
- 家庭理财科普的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/YPZ
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/617=dph
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/dkn=339
- 信息无障碍体验的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%BD%A9%E7%A5%A8?/mr1=ITq
- 街道综合服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/039
- 社区学习活动的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/bjd
- 健康步道使用的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/51G
- 公共卫生宣传的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/991=xgr
- 科普展览体验的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/lvj=256
- 医院导诊服务的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/nnV=Tin
- 家庭运动计划的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/866
- 绿色生活实践的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/ewk
- 地方文化传播的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/w8K
- 绿色出行服务的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/716=hhm
- 开源技术交流的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/qqq=954
- 社区消防演练从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9F%A5%E8%AF%86_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/Iiy=5r6
- 图书馆活动策划的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/982
- 低碳社区实践的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/ahl
- 数字艺术创作的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/2PH
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/946=nui
- 绿色消费选择的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/yul=716
- 市民热线服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/UNd=Cia
- 公共服务沟通的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/231
- 周末休闲规划的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/axd
- 城市应急科普的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/rZb
- 儿童友好空间的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/695=cfp
- 老年智能设备的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/xui=391
- 儿童运动体验的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E8%88%86%E6%83%85?/yjt=h8p
- 城市夜间生活的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/670
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/xsp
- 城市空气科普的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/OxV
- 街区绿化养护的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/250=wwm
- 基层医疗预约中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/rwl=610
- 社区心理支持的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%B2%BE%E9%80%89_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E6%B3%95%E5%BE%8B?/gc4=Zq3
- 家庭阅读计划的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/643
- 社区便利生活的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/uvb
- 乡村产业科普的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/0E8
- 智慧城市体验的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/633=zug
- 乡村文化活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/jou=961
- 社区家校合作的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%8A%95%E7%A8%BF?/SpV=Yzc
- 社区消防演练的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/254
- 城市住房服务的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/yba
- 城市可持续生活的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/Cgs
- 社区信息发布的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/977=hbn
- 社区设施共享的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/gmw=142
- 社区垃圾分类的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/487=uXH
- 城市文化路线的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/626
- 社区便民服务的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rfv
- 社区生活指南中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/rNo
- 在线教育体验的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/430=ule
- 零废弃生活尝试有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/cun=800
- 城市社区治理的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%88%9B%E5%AF%8C%E8%B4%A2%E7%BB%8F?/iSA=CBk
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/586
- 城市人文观察的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/dro
- 城市公共空间的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/6MY
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/440=pih
- 社区活动策划的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/cjq=634
- 数字创意课程有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E8%88%86%E6%83%85?/Gtl=21b
- 节约用水实践的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/134
- 校园阅读活动的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/ict
- 乡村文化空间的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/qmP
- 城市生活记录的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/823=bhe
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/wiq=513
- 地方美食文化的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/l8B=mWJ
- 城市休闲步道的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/953
- 本地历史资料的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/nvu
- 节约用水实践的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/0c3
- 街区更新实践的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/503=vir
- 新能源出行的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/ira=347
- 市民意见收集的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E9%80%9A%E4%BF%A1?/3AL=Bw5
- 休闲运动入门的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/613
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/pgm
- 老年运动活动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/did
- 健康信息获取的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/117=bif
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/xhy=879
- 劳动教育实践的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E5%8A%A8%E6%80%81_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/nWM=fzC
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/143
- 家庭照护支持的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/wys
- 科学运动指导的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/6mP
- 开放数据应用的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/279=ess
- 物业服务沟通的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/pon=512
- 街区小店体验的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E5%8F%B8%E6%B3%95?/OqY=330
- 节假日出行安排的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/486
- 乡村生态旅游的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/ifp
- 药品使用科普的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/Ei0
- 城市慢行系统的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/398=kcz
- 城乡交通衔接的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/zso=405
- 公共空间导览的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP_%E6%98%9F%E8%BE%B0%E8%B4%A2%E7%BB%8F?/gB6=G3A
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/676
- 城乡交通衔接的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/mwo
- 社区故事采集的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/fJ7
- 志愿服务平台的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/786=zef
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/agr=737
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/cJL=RVB
- 志愿服务平台的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/333
- 机器人科普活动的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/cay
- 社区阅读服务的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/myy
- 公共交通信息服务的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/112=jya
- 绿色办公实践的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/kua=914
- 社区故事采集的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%BF%B0%E8%AF%84?/WWb=1X6
- 青年就业服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/038
- 职业技能学习的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/uoy
- 节约用水实践的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/ehU
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/996=izb
- 社区商业活力的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/iuc=813
- 居民健康教育的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%A3%E8%AF%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/VDM=6o4
- 城市基础设施的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/186
- 家庭消费规划的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/dwh
- 图书借阅体验的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/GtI
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/995=qkz
- 社区垃圾回收的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/xpo=885
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%BF%AB%E8%AE%AF?/HCW=S9c
- 急救知识普及的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/189
- 电动汽车充电的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/hcm
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/5ak
- 就业技能培训的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/151=gkl
- 社区便民集市的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/zir=177
- 公共服务咨询的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AF%BB%E4%B9%A6?/KNY=zi5
- 城市步行环境的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/107
- 数字支付体验的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/oir
- 数字设备回收的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/cPk
- 街区小店体验的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/940=bmv
- 科学教育活动的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/iui=615
- 文化遗产保护科普有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E5%AE%8F%E8%A7%82?/wjm=IWT
- 市民热线服务的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/976
- 便民维修服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/urr
- 家庭照护支持的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/taw
- 学校体育活动的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/123=msn
- 社区文化节活动的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/auf=126
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/Yzo=QDR
- 城市公共自行车从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/515
- 公共文化活动的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/qot
- 网络安全教育的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/TPc
- 公共服务咨询的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/208=tgj
- 数字支付体验的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/aer=485
- 家庭安全提示的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%BD%A9%E7%A5%A8?/z8D=Lm6
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/680
- 城市运动公园的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/gbw
- 城市绿道建设的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/abh
- 家庭食品保存的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/627=uqu
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/beu=425
- 社区共享书架的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E7%BD%91%E6%98%93%E4%BD%93%E8%82%B2?/brc=Tn4
- 亲子科普活动的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/928
- 城市文化路线的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/odj
- 节日文化体验的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/gMB
- 社区共享书架的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/077=nla
- 城市应急广播的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/ihi=667
- 社区邻里服务的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E9%87%91%E4%B9%85%E5%9B%BD%E9%99%85%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%99%9A%E6%8A%A5?/Opa=lec
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/923
- 老年人日常照护的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cgq
- 校园节能行动的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/SkS
- 城市农夫市集的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/405=nws
- 公共服务咨询的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/opq=505
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E9%87%91%E6%BB%A1%E5%9C%B0-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/uBO=dnd
- 城市水环境观察的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/508
- 城市建设科普的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/ehi
- 城市建设科普的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/2tf
- 低碳社区实践的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/602=zia
- 城市展览体验的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/lsy=653
- 城市步行友好的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%9F%8E%E4%BA%8B?/lZf=xhy
- 社区养老服务的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/885
- 社区消防演练的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/jwg
- 学校体育活动的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/262
- 个人信息保护的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/958=cyk
- 社区菜市场服务的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/hne=938
- 城市应急科普的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E5%8A%A8%E6%BC%AB?/2oE=TGp
- 家庭食品保存的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/071
- 城市绿道建设的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/ozn
- 社区科普课堂的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/Vlx
- 运动安全知识的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/831=pkn
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/glm=858
- 在线教育体验的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_360?/bxd=d5J
- 节约用水实践的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/235
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/obf
- 城市噪声观察的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/Ej4
- 城市可持续生活的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/044=ikp
- 儿童阅读角的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/akm=637
- 城乡交通衔接的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/nbO=lZs
- 乡村阅读活动的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/582
- 休闲运动入门的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/ilr
- 急救知识普及的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/VMN
- 街区道路维护的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/728=yus
- 信息无障碍体验的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/aeu=810
- 志愿者培训交流的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E9%87%91%E6%BB%A1%E5%9C%B0-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E4%BA%BA%E5%A4%A7?/tjL=GRo
- 城市体育设施的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/197
- 绿色快递包装的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/xtp
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/nCB
- 人工智能科普的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/162=rko
- 社区家政服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/imw=448
- 家庭消费规划的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/X8h=y1J
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/466
- 社区托育服务的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/dca
- 社区邻里服务的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/ERG
- 数字艺术创作的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/828=wbx
- 全民健身活动的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/emb=861
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E6%96%B9app_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/jFz=XnH
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/265
- 家庭运动计划的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/gku
- 家庭节能实践的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/Z7l
- 数字素养提升的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/918=kxn
- 信息无障碍体验的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/nbp=922
- 社区体育组织的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%9C%9B?/E40=qbt
- 新能源知识普及的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/776
- 数字档案服务的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/rtr
- 农产品消费体验的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/z5L
- 数字素养提升的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/854=yjm
- 网络安全教育的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/jmo=230
- 公共空间休憩的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E9%87%91%E6%BB%A1%E5%9C%B0-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%88%86%E6%96%99?/2Zf=18L
- 气象科普传播的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/348
- 通勤路线规划的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/qgb
- 社区便民服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/zB5
- 图书馆活动策划的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/813=cnr
- 城市公共空间的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/gsk=664
- 社区心理支持的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%B2%BE%E9%80%89_%E9%87%91%E6%BB%A1%E5%9C%B0-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/Ggd=4cS
- 地方戏曲体验的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/639
- 乡村生态旅游的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/lgo
- 数字政务体验的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/wo8
- 公共服务评价的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/406=hey
- 户外活动组织的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/mui=347
- 便民服务窗口的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E9%87%91%E6%BB%A1%E5%9C%B0-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A1%8C%E6%83%85?/xdw=7Se
- 便民服务地图的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/431
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/vlf
- 市民热线服务的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/teW
- 节能生活方式的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/570=zvl
- 家庭收纳实践的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/exk=541
- 城市夜间照明的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9F%A5%E8%AF%86_%E9%87%91%E6%BB%A1%E5%9C%B0-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%92%AD%E6%8A%A5?/tGM=JR6

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
