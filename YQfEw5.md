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

- 社区法律科普的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/TtT
- 公共场馆服务的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/106=sqq
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/jwa=321
- 地方戏曲体验的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BF%AB%E6%8A%A5?/kch=jOB
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/780
- 居民健康教育的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/qvj
- 通勤路线规划的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/5Fp
- 绿色校园实践的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/566=xqv
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/rpj=196
- 城市共享单车的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E6%96%87%E5%BA%93?/fKl=gHv
- 软件开发学习的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/364
- 城市博物馆活动的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/zte
- 环境监测科普的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/AlM
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/618=dzh
- 图书馆活动策划的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/dzc=485
- 社区公共议事的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%99%BE%E5%BA%A6%E4%BC%97%E6%B5%8B?/GjR=jaa
- 城市体育设施的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/793
- 生活服务数字化的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/iqw
- 社区读书角建设的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/4sF
- 城市夜间照明的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/157=xfj
- 环境监测科普的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/zbp=819
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%99%9A%E6%8A%A5?/p9S=bzj
- 城市步行环境的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/726
- 公共场馆服务的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/qmj
- 公共设施维护的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/Oul
- 城市骑行环境的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/556=cba
- 农贸市场环境中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/aiv=115
- 节日文化体验的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%83%AD%E6%A6%9C?/Fle=wGI
- 人工智能科普的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/659
- 科学运动指导的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vbk
- 开放数据应用的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/jTZ
- 农产品消费体验的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/069=xwb
- 家庭饮食安排的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/uod=131
- 居家适老化改造的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/JQc=wCw
- 乡村生态观察的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/480
- 租房信息服务的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/amu
- 城市展览体验的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/PIt
- 社区协商议事的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/259=rnd
- 线上办事服务的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/zer=980
- 家庭阅读计划的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%BF%AB%E6%8A%A5?/iaz=3vE
- 城市共享单车的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/091
- 城市夜间照明的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ffy
- 机器学习入门从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/STQ
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/146=ovu
- 乡村生活观察的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/dug=598
- 节能家电使用的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/hkb=oYA
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/122
- 绿色消费选择的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/ilq
- 老年智能设备的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/04h
- 城乡公共服务的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/685=osj
- 药品使用科普的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/lrw=483
- 社区艺术活动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8D%8E%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0?/1DM=9d8
- 家庭志愿活动的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/378
- 传统节日科普的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/wlb
- 公共设施使用的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/WFp
- 数字课堂应用的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/708=kcn
- 公共交通接驳的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/hvg=560
- 数字政务体验从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A5%A8?/04k=9Rr
- 机器人科普活动的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/477
- 青年就业服务的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/dgw
- 公共场所导视的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/U2V
- 地方旅游导览中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/420=aaq
- 家庭急救准备的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/biz=536
- 周末休闲规划的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%A5%BC%E5%B8%82?/geC=3UV
- 数字素养提升的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/929
- 城市噪声观察的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/hve
- 线上办事服务的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/KuG
- 家庭运动计划的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/562=arm
- 基层健康档案的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/cnj=550
- 城市公共自行车的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E9%A3%9F%E5%93%81?/AJN=wgw
- 家庭消费规划的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/170
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/uex
- 乡村公共服务的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/900
- 垃圾分类指导的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/671=cuu
- 城市公共艺术的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/esc=349
- 家庭环保习惯中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E6%AF%8D%E5%A9%B4?/I8a=pOf
- 安全出行教育的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/849
- 药品使用科普的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/gmc
- 城市文明实践的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/MfG
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/280=lac
- 课后服务体验的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/csd=660
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%B6%E5%B1%85?/R0i=l6N
- 公共服务指南的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/582
- 低碳社区实践的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/vyv
- 老年友好服务的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/4za
- 读书会组织的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/974=ktu
- 职业技能学习的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/ogd=880
- 数字创作工具的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BF%AB%E8%AE%AF?/Ju7=v8Z
- 老年运动活动的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/248
- 社区家校合作的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/dcj
- 科普展览体验的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/2bU
- 社区法律科普的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/940=oyv
- 公园亲子设施的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/quf=239
- 城市住房服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/90K=dC1
- 社区协商议事的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/677
- 家庭节能设备的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/fni
- 社区公共议事的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/gIf
- 公共卫生宣传的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/931=diw
- 公园休闲体验的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/zhk=685
- 新能源知识普及的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/Lbx=swh
- 城市公共座椅的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/328
- 亲子科普活动的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/swx
- 开放式学习空间的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/UX5
- 智能家居应用的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/987=gms
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/pca=734
- 线上办事服务的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E7%BD%91_%E8%B1%86%E7%93%A3%E6%99%A8%E6%8A%A5?/z4H=Z57
- 城市博物馆服务的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/442
- 城市雨天出行的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/ulk
- 线上阅读资源的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/yF8
- 读书会组织的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/327=yee
- 本地旅行体验的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/vlv=655
- 光伏知识科普的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%88%B1%E5%A5%87%E8%89%BA?/2ET=Kfa
- 市民热线服务的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/342
- 科学信息获取的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/utf
- 社区应急准备的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/cCS
- 家庭饮食安排的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/069=diz
- 社区读书角建设的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/ixp=467
- 城市公共厕所的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E5%85%9A%E5%BB%BA?/JzL=ZQZ
- 居民健康教育的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/724
- 智能家居应用的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/gca
- 乡村公共服务的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/MLK
- 社区公共卫生的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/131=ceb
- 便民服务窗口的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/cot=989
- 数字生活课堂的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP_%E8%B4%A2%E7%BB%8F%E5%86%9C%E4%B8%9A?/PhK=28f
- 绿色快递包装的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/720
- 社区教育资源的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/vkd
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/fkK
- 乡村生态观察的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/785=ehc
- 市民意见收集的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/qmi=485
- 城市绿道建设的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E4%B9%90%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E9%A3%9F%E5%93%81?/4yp=f4e
- 公共服务数字化的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/724
- 校园阅读活动的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/wvt
- 社区活动策划的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/gZQ
- 科学健身方法的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/031=cij
- 老年友好服务的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/hec=540
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_36%E6%B0%AA%E4%BA%B2%E5%AD%90?/Wl7=dVI
- 绿色校园实践的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/711
- 本地历史资料的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/rdr
- 全民阅读推广的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/JW8
- 节日文化体验的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/640=bsg
- 环境教育课程的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/efy=177
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E6%B6%88%E8%B4%B9?/68v=lrx
- 智慧停车服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/560
- 安全出行教育的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/weq
- 数字政务体验的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/w4Q
- 老年友好服务的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/852=lae
- 网络安全教育的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/qng=020
- 家庭健康管理的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E5%8D%8E%E5%85%B4%E8%B4%A2%E7%BB%8F?/gth=gt6
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/877
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/fme
- 社区应急准备有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/2Y8
- 数字公共文化的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/629=lxv
- 儿童友好空间的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/ngb=564
- 社区家政服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/LO5=LVz
- 本地消费场景的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/812
- 城市公共艺术的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/gtv
- 公交站点体验的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/bAV
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/332=drx
- 街区小店体验的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/zxo=653
- 老年人日常照护的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%9F%A5%E8%AF%86_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%A1%BA%E4%B8%B0%E6%8E%A2%E5%BA%97?/v8s=uLn
- 在线教育体验的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/200
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/zeh
- 本地旅行体验的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/7XK
- 城市应急科普的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/027=gcz
- 乡村阅读活动的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/faj=313
- 城市公共厕所的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%99%BA%E6%B1%87%E8%B4%A2%E7%BB%8F?/7sw=0Et
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/347
- 基层健康档案的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/gxg
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/aEj
- 老年数字阅读的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/915=pjj
- 老年人文化生活的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/dxf=194
- 小微企业服务中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%A4%A7%E4%B9%90%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%A7%81%E5%8B%9F?/8YW=NVQ
- 健康步道使用的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/517
- 户外活动组织的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/zbf
- 数字公共文化的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/0Cu
- 社区养老服务的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/169=wyh
- 公园休闲体验的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/iap=408
- 街区道路维护的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E4%B9%90%E5%BD%A9-%E5%AE%98%E6%96%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%B7%E5%A4%96?/x0L=5ZB
- 健康饮食教育的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/727
- 应急物资管理的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/ryh
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/5lJ
- 乡村文化活动的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/792=slz
- 社区手工活动的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/pjd=472
- 城市适老服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%AE%87%E5%AE%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E9%80%9F%E8%A7%88?/EWn=ZLQ
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/472
- 图书馆亲子空间从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/vsx
- 儿童阅读角的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/No4
- 科学信息获取的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/879=kwe
- 社区心理支持的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/cjw=536
- 老年人文化生活的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E5%A4%A7%E5%AE%87%E5%AE%99-welcome%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BC%97%E6%B5%8B?/mnw=wD4
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/112
- 街区道路维护的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/rhf
- 科学健身方法的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/Ykx
- 开放数据应用的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/708=syl
- 地方美食文化的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/mtg=758
- 社区宠物管理的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%92%AD%E6%8A%A5?/KJ6=oJ2
- 小区电梯维护的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/190
- 城市运动公园的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/nbz
- 创业经验分享的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/5Ry
- 周末休闲规划的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/250=gdq
- 智能手机助老的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/tqw=744
- 社区手工活动的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%8C%96?/hC1=sxg
- 社区运动空间的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/498
- 城市建设科普的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/kfv
- 公园亲子设施的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/yry
- 非遗课堂体验的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/847=vwf
- 公共图书馆服务的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/umg=220
- 社区读书角建设的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/8UY=6g8
- 邻里互助活动的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/470
- 公共服务指南的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/iti
- 电子商务服务的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/wXg
- 生活技能分享从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/746=hzm
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/cla=081
- 社区垃圾回收的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%AE%87%E5%AE%99-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%95%B0%E8%AF%BB?/Ntp=Qga
- 职业技能学习的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/095
- 青少年科普实践的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/eic
- 社区公共餐饮的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/jHA
- 社区公共餐饮的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/146=ftb
- 公交站点体验的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/utf=621
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/sSo=KfU
- 城市步行友好的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/793
- 社区家校合作的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/jlw
- 社会体育指导的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/Q0b
- 青少年户外教育的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/099=pfn
- 数字资源检索有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/ymk=556
- 数字素养提升的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E6%96%B9app_36%E6%B0%AA%E5%86%9C%E4%B8%9A?/2Jn=kT8
- 公共服务咨询的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/541
- 城市夜间照明的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/isi
- 基层医疗预约的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/eHB
- 老年人日常照护的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/277=mqt
- 家庭运动计划的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/lsi=293
- 家庭节能实践中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%AE%98%E7%BD%91_%E7%99%BE%E5%BA%A6%E8%B4%A2%E7%BB%8F?/BfE=EEE
- 城市农夫市集的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/851
- 社区知识分享的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/zrj
- 公共服务沟通的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/xeW
- 传统节日科普的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/128=npi
- 电子商务服务的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/umf=729
- 家庭消费规划的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%87%E5%AE%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%A6%81%E9%97%BB?/ju9=PKy
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/319
- 社区法律科普的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/jll
- 城市公共艺术中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/XKY
- 个人时间管理的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/241=xsk
- 城市适老服务的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/wxk=996
- 数字设备回收的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%AE%87%E5%AE%99-%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E8%B4%A2%E7%BB%8F?/hX4=pv6
- 农业科普体验的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/960
- 家庭收纳实践的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/zdy
- 家庭节能实践的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/nJb
- 家庭用电安全的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/840=chx
- 生活垃圾减量的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/btn=795
- 健康饮食教育的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%A4%A7%E5%AE%87%E5%AE%99-APP_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E8%82%A1?/4Gj=BM1

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
