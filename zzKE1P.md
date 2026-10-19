# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:18**

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

- 终身学习资源的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB%E7%9B%88%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/ZQi
- 社区托育服务的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB%E7%9B%88%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/529=iuc
- 安全出行教育的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB%E7%9B%88%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/xfi=317
- 传统节日科普的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E8%81%9A%E7%84%A6_%E5%BF%AB%E7%9B%88%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B3%95%E5%BE%8B?/QLL=RlC
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/840
- 健康饮食教育的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/qxb
- 街区绿化养护的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/v8i
- 城市文明出行的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/542=ils
- 乡村休闲旅游从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/tec=889
- 健康饮水科普从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB%E7%9B%88ll%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/oir=dIw
- 城乡交流活动的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/636
- 社会体育指导的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/fls
- 非遗体验活动从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/AiJ
- 个人数据管理的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/956=feg
- 灵活就业交流的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/mez=381
- 乡村文化活动的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BF%AB%E7%9B%88II-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/Xzc=x8C
- 社区便利生活的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/767
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/osu
- 家庭科学教育的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/TR0
- 居家防滑改造的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/315=ilo
- 读书会组织的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/nzk=541
- 社区运动空间中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%BF%AB%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E9%A3%8E%E6%8A%95%E8%B4%A2%E7%BB%8F?/fvX=bVL
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/537
- 城市基础设施中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/bhc
- 老年友好服务的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/F5g
- 光伏知识科普的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/354=hku
- 乡村文化活动的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/oea=380
- 校园社团活动的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E5%BF%AB%E7%9B%88ll-wlcome%E5%BD%A9%E7%A5%A8_360%E5%9F%8E%E4%BA%8B?/8oj=047
- 社区花园共建的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/784
- 乡村公共阅读的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/xcl
- 休闲运动入门的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/6HY
- 零废弃生活尝试的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/242=ckp
- 社区便利生活从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/lsi=355
- 儿童安全出行的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88I%C4%B1%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E6%95%99%E8%82%B2?/J6F=hPP
- 校园社团活动的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/428
- 社区应急准备的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/qmw
- 校园节能行动的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/guy
- 开放式学习空间的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/796=tey
- 本地消费场景的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/oyh=119
- 生活垃圾回收的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BF%AB%E7%9B%88lI%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9F%8E%E4%BA%8B?/ieZ=CzG
- 家庭养老规划的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/919
- 城市农夫市集的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/tgm
- 社区文化节活动的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/zNC
- 生活垃圾回收的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/524=qfs
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/yvz=819
- 城市基础设施的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E7%9B%88II%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E6%94%BF%E5%8A%A1?/zRR=cJK
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/680
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/lgz
- 社区托育服务的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/Itc
- 数字档案服务的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/277=ydr
- 数字阅读服务的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/zuv=704
- 城市应急广播的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E5%86%B3%E7%9B%88Il%E5%85%AC%E5%8F%B8%E7%BD%91%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/tOw=Lnn
- 数字素养提升的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/807
- 读书会组织的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/yyy
- 社区商业活力的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/QFp
- 街区更新实践的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/576=rtc
- 智能家居应用有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/eqt=180
- 本地消费场景的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_%E8%B5%A2%E4%B9%90IV_%E8%B1%86%E7%93%A3%E6%96%87%E6%91%98?/MZT=ESq
- 社区体育组织的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/141
- 城市公共标识的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/qma
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/tZt
- 公益活动组织从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/647=vcx
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/ddf=305
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%9B%AD%E8%89%BA?/HcA=Zww
- 社区信息发布的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/702
- 科学运动指导的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/sny
- 社区健康讲座的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/ZV2
- 城市地名文化的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/607=vxf
- 社区公共卫生的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/dcb=203
- 社区安全巡查的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-%E7%99%BB%E9%99%86_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/RQ0=GSM
- 科学健身方法的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/307
- 社区信息发布的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/eyw
- 老年学习活动的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/gWp
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/960=hbd
- 街区道路维护的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/sln=105
- 急救知识普及的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB%E7%9B%88IV%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E5%AE%B6%E5%B1%85?/OFY=l9y
- 社区儿童活动的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/759
- 图书借阅体验的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/eak
- 数字公共文化的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/qZp
- 乡村文化空间的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/619=kli
- 乡村教育资源的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/oxm=831
- 开放数据应用的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB%E7%9B%88IV500._%E6%90%9C%E7%8B%90%E5%BD%B1%E8%A7%86?/gkY=Gbs
- 公交无障碍服务的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/214
- 城市雨天出行的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/efe
- 街区更新实践的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/bQE
- 智慧停车服务的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/120=cup
- 城市文化路线的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/ddy=323
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/LaD=wuU
- 数字阅读服务的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/696
- 学校食育活动从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/idh
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/XNR
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/759=nhx
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/fwb=814
- 智慧城市体验的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AF%84%E8%AE%BA?/8VV=0Za
- 城市生活服务的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/894
- 城乡交流活动的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/zmy
- 无障碍出行的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/YME
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/523=wkt
- 社区活动报名的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/qww=705
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%95%B0%E8%AF%BB?/ORc=L5r
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/668
- 公交站点体验的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/gjg
- 青年就业服务的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/gEN
- 非遗体验活动的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/030=cjn
- 数据分析入门的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/dje=030
- 数字设备回收的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%88%86%E6%83%85?/Cqi=s4v
- 社会体育指导的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/869
- 乡村阅读活动的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/bgt
- 骑行路线规划的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/Qvb
- 社区公共卫生的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/472=usp
- 环境监测科普的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/xmq=038
- 社区安全巡查的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_%E5%BF%AB%E7%9B%88lv%E5%A4%A7%E4%BC%97-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E8%AF%BB%E4%B9%A6?/Box=map
- 亲子阅读活动的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/058
- 开放数据应用中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/ocx
- 数字设备回收的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/NpV
- 医院导诊服务中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/331=its
- 骑行路线规划的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/kqk=919
- 机器学习入门的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9.%E5%A5%BD.%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%94%BF%E7%AD%96?/48N=6CS
- 无障碍出行的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/824
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/qgq
- 社区活动空间的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/th3
- 绿色消费选择的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/418=pcq
- 本地消费场景中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/lkd=371
- 社区知识分享的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E4%B9%90%E5%BD%A9%E7%BD%91%E8%BD%AF%E4%BB%B6%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%88%86%E6%96%99?/XAs=hDx
- 社区协商议事的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/221
- 社区儿童活动的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/ltv
- 家庭科学教育的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/XOe
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/099=kqd
- 小区公共照明的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/qxp=588
- 志愿者培训交流的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/Y72=R2C
- 街区更新实践中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/951
- 社区菜市场服务的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/cyo
- 小区电梯维护的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/zvv
- 科学教育活动的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/058=trk
- 邻里互助活动的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/pjx=933
- 公共设施使用的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/BMh=J69
- 城乡公共服务的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/810
- 社区文化传播的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/iyr
- 公园亲子设施的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/Srk
- 城乡交通衔接的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/977=bgn
- 生活垃圾回收的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/qab=356
- 社区托育服务的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%90%9C%E7%8B%90%E7%BE%8E%E5%A6%86?/CFb=bAX
- 开放式学习空间的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/315
- 社区便民集市中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/qcc
- 家庭照护支持的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/cgo
- 科学教育活动的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/306=azw
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/ojs=205
- 城市生活服务的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/QWM=EAY
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/207
- 本地消费场景的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/hsv
- 公园亲子设施的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/fgA
- 儿童户外活动的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/741=lro
- 数字地图应用的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/kqv=823
- 社区应急准备的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%83%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%89%B4?/WuV=7Rg
- 传统节日科普的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/243
- 租房信息服务的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/mrt
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/wuL
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/766=ovg
- 地方民俗记录的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/syo=042
- 终身学习资源的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B9%90%E5%BD%A9%E8%B4%AD%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E9%A6%96%E9%A1%B5_%E5%AE%B6%E5%BA%AD%E8%B4%A2%E7%BB%8F?/bvq=NqT
- 城市便民驿站的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/463
- 科学观察活动的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/sjo
- 社区庭院绿化的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/TTU
- 家庭健康科普的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/048=zke
- 邻里互助活动的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/lpp=461
- 传统手工艺体验的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-welcome_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E5%9B%BE?/Ifk=gCN
- 环境教育课程的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/523
- 节约用水实践的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/pua
- 乡村公共服务的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/EXd
- 老旧小区改造的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/810=wal
- 城市公共艺术的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/hun=980
- 数字资源检索的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%8F%E8%A7%82?/n6x=Lz9
- 文化遗产保护科普的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/773
- 开放式学习空间的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/imv
- 社区活动报名的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/K92
- 非遗课堂体验的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/820=lrz
- 科学观察活动的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/eip=946
- 公共服务咨询的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%A7%91%E6%8A%80?/KY0=B6v
- 社区应急准备的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/884
- 旧物循环利用的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/fxw
- 城市慢行系统的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/y6X
- 城市社区治理的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/943=xkb
- 安全出行教育的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/ieh=427
- 数字素养提升的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85%E9%A6%96%E9%A1%B5%E5%A4%A7%E5%8E%85_360%E6%95%B0%E8%AF%BB?/jlQ=HCF
- 骑行路线规划的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/910
- 老年人日常照护的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/rks
- 灵活就业交流的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/8z5
- 职业技能学习的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/880=ayw
- 无障碍信息设计的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/yfs=762
- 科学健身方法中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E4%B9%90%E5%BD%A9%E5%9B%BD%E9%99%85-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/TZ3=0PM
- 城市可持续生活的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/801
- 社区快递服务的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/ufk
- 本地旅行体验的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/p3L
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/303=jiu
- 城市农夫市集的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/qpk=444
- 生活垃圾减量的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%A6%82%E6%84%8F%E5%9B%BD%E9%99%85%E5%AE%98%E6%96%B9_%E4%B8%9C%E4%BA%AC%E8%B4%A2%E7%BB%8F?/6RH=89N
- 社区环保活动的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/536
- 家庭收纳实践的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/oss
- 老年智能设备的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/oPP
- 城市夜间生活的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/087=rfi
- 旧物循环利用的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/cto=034
- 本地历史资料的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B9%90%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E6%94%BF%E7%AD%96?/1hA=eFi
- 健康饮食教育的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/131
- 健康步道使用的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/iev
- 智慧城市体验的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/NMU
- 社区消防演练的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/373=glm
- 电子商务服务的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/uyx=635
- 城乡公共服务的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9-welcome%E5%A8%B1%E4%B9%90%E5%A4%A7%E5%8E%85_%E6%BE%8E%E6%B9%83%E9%9F%B3%E4%B9%90?/m2C=t8m
- 安全出行教育的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/490
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/eyq
- 小区停车协商的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/Oqv
- 绿色办公实践中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/337=zuy
- 乡村电商实践的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/gbe=372
- 公共交通接驳的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E7%A5%A5%E9%A1%BA%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E7%94%B5%E8%AF%9D_%E7%95%8C%E9%9D%A2%E5%8F%B8%E6%B3%95?/rj8=JxF
- 生成式工具使用的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/676
- 数字创作工具的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/wkr
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/U4g
- 城市体育设施的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/022=kum
- 数据分析入门的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/lzl=342
- 乡村生活观察的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%86%E8%AF%B4_%E8%B5%A2%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0welcome_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E7%94%B5?/rjT=cuP
- 家庭照护支持的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/620
- 城市公共空间的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/ghz
- 城市噪声观察的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/rns
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/607=lvw
- 公共场馆服务的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/knc=242
- 城市树木认养的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%88%9B%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E8%A7%A3%E5%AF%86?/GXG=jXi
- 城市游园体验的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/305
- 公共空间照明的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/kgz
- 农贸市场环境的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/UMl
- 社区科普课堂的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/845=etr
- 家庭饮食安排的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/tsd=647
- 家庭急救准备的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%A7%93%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%A8%8E%E5%8A%A1?/MM5=UDj
- 图书馆活动策划的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/888
- 本地消费场景的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/koy
- 乡村产业科普的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/lfQ
- 社区公共卫生的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/242=xer
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/obk=802
- 数字档案服务中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_08%E5%BE%AE%E8%81%8A-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%A7%82%E7%82%B9?/ph3=xtu
- 街区小店体验的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/548
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/cee
- 城市空气科普的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/qN3
- 青少年编程学习的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/853=ojy
- 城市体育设施的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/kjq=712
- 非遗体验活动的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E4%B9%90%E5%8F%91VIIII%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7?/1ah=UkO
- 科学信息获取的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/245
- 小微企业服务的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/zfa
- 城市休闲步道的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/4Mq
- 社区心理支持的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/857=eon
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/kuf=926
- 社区学习活动的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B9%90%E5%8F%91ill%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%B8%93%E6%A0%8F?/sHo=PfT

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
