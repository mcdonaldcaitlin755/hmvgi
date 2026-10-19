# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:15**

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

- 低碳社区实践中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%AD%85%E5%BD%B1%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E8%81%8A_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/b08
- 城市适老服务的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%AD%85%E5%BD%B1%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E8%81%8A_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/654=msy
- 家庭理财科普的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%AD%85%E5%BD%B1%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E8%81%8A_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/zeg=604
- 便民信息查询的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E9%AD%85%E5%BD%B1%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E8%81%8A_%E7%BA%B5%E8%A7%88%E8%B4%A2%E7%BB%8F?/Jlg=kPQ
- 城市文明实践的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/694
- 垃圾分类指导中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/jeb
- 数字创意课程的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/o1X
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/141=cev
- 数字设备回收中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/hdx=031
- 城市共享单车的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E8%8B%B9%E6%9E%9C_%E9%87%91%E7%89%8C%E8%B4%A2%E7%BB%8F?/MHW=HBq
- 居家适老化改造的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/055
- 农业科普体验的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/nkf
- 智能家居应用的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/O5H
- 地方戏曲体验的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/651=bxr
- 职业技能学习的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/mlc=118
- 儿童阅读角的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%99%BB%E5%BD%95%E4%B8%8D%E4%BA%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/kAY=NI0
- 图书借阅体验的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/512
- 休闲运动入门的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/uei
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/A57
- 光伏知识科普的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/555=wja
- 公共空间照明的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/zjz=908
- 城市公共厕所的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/u74=hPQ
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/266
- 乡村生态旅游的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/lpm
- 数字课堂应用的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/QSE
- 人工智能科普的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/830=cof
- 运动安全知识的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/yml=922
- 市民热线服务有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E5%AE%89%E8%A3%85_%E9%93%B6%E7%9B%9B%E8%B4%A2%E7%BB%8F?/njR=7Qn
- 公共设施维护的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/168
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/bzq
- 社区养老服务的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/sEE
- 公园休闲体验的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/134=grz
- 城市展览体验的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/zoj=108
- 城市夜间照明的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E7%9E%AD%E6%9C%9B?/xKb=7cN
- 城市可持续生活中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/427
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/zqn
- 社区活动策划的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/0eH
- 地方文化传播的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/934=xde
- 街道综合服务的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/adt=984
- 地方旅游导览中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%A4%A7%E5%85%A8%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E7%BA%AA%E5%AE%9E?/FSF=Yql
- 物业服务沟通的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/891
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/dch
- 周末休闲规划的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/H2I
- 节约用水实践的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/328=sdt
- 家庭防灾准备的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/oeg=228
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%80%E6%96%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B6%88%E8%B4%B9?/0dv=DjZ
- 社区家政服务有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/570
- 邻里互助活动的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/bqj
- 公益活动组织的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/V6r
- 生成式工具使用的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/881=uan
- 机器学习入门的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/vea=764
- 日常摄影记录的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/xH8=LKb
- 老年友好服务的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/927
- 社区互助网络的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/dee
- 城市生活服务有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/dLD
- 家庭健康管理的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/329=glx
- 便民服务地图的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/dns=873
- 数字便民地图的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%AE%B2%E5%9D%9B?/AAD=T9v
- 通勤路线规划中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/145
- 青年就业服务的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/mqf
- 城市微更新实践的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/5O0
- 社区读书角建设的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/981=rct
- 家庭健康科普的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/euh=857
- 便民信息查询的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E8%85%BE%E8%AE%AF%E8%BD%AC%E8%BD%BD?/UBg=gUa
- 城市微更新实践的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/847
- 市民意见收集的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/vjr
- 本地消费场景的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/eQe
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/249=zfd
- 乡村公共服务的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/zus=980
- 在线学习体验的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%A6%8F%E5%BD%A9%E5%BF%AB3%E5%BC%80%E5%A5%96%E5%8A%A9%E6%89%8B%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%AB%E6%89%8B%E6%B3%95%E5%BE%8B?/4UT=WN7
- 儿童友好街区的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/855
- 城市应急广播的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/xdc
- 城市社区治理的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/8I1
- 社区养老服务的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/392=zto
- 社会体育指导的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/sud=759
- 公共图书馆服务的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%91%E7%AB%AF%E8%B4%A2%E7%BB%8F?/vSQ=Q5G
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/042
- 社区消防演练的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/kpt
- 数字创作工具的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/BAD
- 老年学习活动的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/609=xwm
- 节日文化体验的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/xhe=874
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E5%A4%A7%E5%85%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_360%E7%9B%98%E7%82%B9?/2sB=bRT
- 社区环保活动的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/005
- 无障碍出行的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/qfw
- 数据分析入门的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/gOS
- 绿色快递包装的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/513=noh
- 就业技能培训的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/eux=169
- 运动安全知识中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E7%BD%91%E6%98%93%E5%9C%B0%E4%BA%A7?/EB9=w4Y
- 社区活动策划的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/131
- 城市步行友好的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/byj
- 街道综合服务的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/tTb
- 小区电梯维护的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/342=jkw
- 新能源出行中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/sqx=906
- 数字政务体验的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/FLX=WMZ
- 社区志愿服务的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/211
- 城市公共空间的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/ibt
- 社区菜市场服务从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/mUz
- 社区快递服务的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/043=xbz
- 社区生活指南的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/paf=098
- 便民服务窗口的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93_%E5%93%94%E5%93%A9%E5%9B%BE%E9%9B%86?/V4u=tGU
- 城市共享单车的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/791
- 家庭急救准备的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/mev
- 智慧停车服务的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/yDj
- 乡村公共文化的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/762=unp
- 便民维修服务的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/ahl=957
- 便民维修服务的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E6%A6%9C?/H8e=dv1
- 节气饮食文化的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/224
- 社区商业活力的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/uhs
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/R7b
- 城市展览体验的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/021=zde
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/wxt=188
- 社区便民服务的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E6%9C%80%E6%96%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E8%B4%A2%E7%BB%8F%E8%AE%B2%E5%9D%9B?/glL=7YN
- 数字艺术创作的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/324
- 城市步行环境的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/bfo
- 农贸市场环境从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/pDP
- 数字资源检索的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/831=rph
- 消防知识宣传的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/drd=477
- 城市建设科普的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/s6d=OD9
- 城市绿色交通的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/336
- 非遗体验活动的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/rea
- 城市文明出行的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/ONd
- 公交站点体验的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/127=ypu
- 家庭饮食安排的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/aev=849
- 社区学习活动的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%87%A4%E5%87%B0%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9C%AD%E8%AE%B0?/k9Y=VFs
- 社区故事采集的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/844
- 社区停车服务的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/yrg
- 校园安全教育的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/i0c
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/912=yuv
- 城乡交流活动的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/stz=795
- 健康饮水科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%BF%AB%E5%BD%A9_%E5%A4%B4%E6%9D%A1%E7%90%86%E8%B4%A2?/qa3=J0m
- 城乡公共服务的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/987
- 城市文明出行的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/vnt
- 社区互助网络的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/A4C
- 垃圾分类指导的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/171=yav
- 绿色快递包装的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/lpo=999
- 家庭节能实践的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E5%AE%89%E8%A3%85_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/Sn2=pKD
- 旧物循环利用的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/787
- 社区安全巡查的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/dty
- 家庭陪伴活动的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/k0y
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/829=imz
- 绿色快递包装的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/jjt=579
- 乡村电商实践的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/RJ8=T83
- 儿童安全出行的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/903
- 科学运动指导的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/haw
- 食品配送体验的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/Qr3
- 家庭食品保存的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/991=yoo
- 图书馆数字服务的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/smy=891
- 周末休闲规划的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BD%93%E8%82%B2?/pxs=I7j
- 农贸市场环境中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/992
- 社区垃圾回收的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/cvu
- 公共服务指南的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/fbz
- 家庭安全提示的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/095=npt
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/fei=268
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/O6X=Hlz
- 城市步行环境中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/883
- 家庭环保行动的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/fvo
- 街区道路维护的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/76Y
- 城市骑行环境的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/328=uhv
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/huj=466
- 校园社团活动的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%AE%BF%E8%B0%88?/843=zQY
- 个人数据管理的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/529
- 老年学习活动的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/beg
- 数字学习资源的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/yRR
- 儿童运动体验的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/996=xys
- 非遗体验活动的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/zci=170
- 城市骑行环境的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA_%E7%99%BE%E5%BA%A6%E6%BC%AB%E8%AF%84?/osE=a61
- 个人信息保护的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/344
- 公园休闲体验的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/jhr
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/A4z
- 青少年心理健康的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/315=won
- 科学睡眠习惯的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/fnn=854
- 公园亲子设施的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9C_%E7%99%BE%E5%BA%A6%E6%B3%95%E6%B2%BB?/T0r=ke5
- 家庭急救准备的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/762
- 人工智能科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/hke
- 传统节日科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/8RS
- 社区防暑服务的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/839=jna
- 社区宠物管理的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/juv=705
- 开放式学习空间的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/UmR=1ju
- 社区志愿服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/164
- 城市应急广播的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/aai
- 城乡交通衔接的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/fhP
- 地方美食文化的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/343=wlo
- 休闲运动入门的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/qka=519
- 创业经验分享的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0_%E6%90%9C%E7%8B%90%E6%B8%AF%E8%82%A1?/uQg=e7v
- 城市生活记录的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/848
- 节约用水实践的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/ssd
- 公共服务沟通的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/ZJn
- 节约用水实践的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/097=sob
- 数字创意课程的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/anc=134
- 社区公共议事的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%9B%B2%E8%89%BA?/SQ3=y26
- 数字阅读服务的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/894
- 安全出行教育的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/lbg
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/Qyq
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/283=pio
- 社区防暑服务的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/liu=644
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%B0%8F%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C_%E4%B8%B0%E7%9B%88%E8%B4%A2%E7%BB%8F?/KjV=JNM
- 日常摄影记录的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/102
- 药品使用科普的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/gnz
- 个人信息保护的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/QPi
- 课后服务体验中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/988=ucc
- 家庭养老规划的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/gfe=701
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E6%AD%A3%E8%A7%84%E7%A6%8F%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E6%BE%8E%E6%B9%83%E5%AE%B6%E5%B1%85?/bvA=Ohb
- 城市公共自行车的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/097
- 科学教育活动的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/iqw
- 家庭志愿活动的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/Xli
- 城市骑行环境中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/690=wgi
- 口袋公园建设的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/imv=140
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E8%8B%B9%E6%9E%9C%E7%89%88%E5%AE%89%E8%A3%85_%E4%BC%98%E9%85%B7%E6%BC%AB%E8%AF%84?/ESN=aN1
- 社区故事采集的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/229
- 口袋公园建设的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/ocj
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/2PK
- 终身学习资源的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/333=uye
- 城市人文观察的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/npn=258
- 社区活动策划的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E4%B8%8B%E8%BD%BD%E6%BE%9A%E5%BD%A9%E5%BD%A9%E7%A5%A8_%E9%93%B6%E6%B1%87%E8%B4%A2%E7%BB%8F?/uTH=dE6
- 城市应急广播的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/166
- 家庭防灾准备的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/zsc
- 青少年户外教育的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/ZBA
- 节气饮食文化的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/558=vqf
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/vdk=807
- 社区科普课堂的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%8B%E8%BD%BD%E4%B8%80%E5%88%86%E9%92%B1%E5%BD%A9%E7%A5%A8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E7%A8%BF?/o4d=5Pm
- 数字资源检索的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/436
- 本地历史资料的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/rkq
- 城市夜间照明的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/h2F
- 数字支付体验的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/036=btd
- 音乐欣赏活动从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/aet=963
- 小微企业服务的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E4%B8%8B%E4%B8%8B%E8%BD%BD_%E7%95%8C%E9%9D%A2%E7%9E%AD%E6%9C%9B?/rst=qI6
- 小区公共照明的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/835
- 社区阅读服务的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/qcg
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/nfN
- 农贸市场环境的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/411=ijs
- 公共服务评价的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/rmn=349
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A86%E5%9C%A8%E7%BA%BF%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E5%8F%B7%E5%A4%96?/umN=Kco
- 青少年科普实践中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/367
- 文化讲座服务中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/snv
- 亲子阅读活动的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/b4U
- 开源技术交流的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/357=yzm
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/rni=906
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E6%85%A7%E7%9C%BC?/4Rt=htb
- 家庭网络使用的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/313
- 读书会组织的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/qjw
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/KHD
- 居家适老化改造的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/052=ipu
- 城市微更新实践的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/nvd=240
- 生活技能分享的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A95%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/7qD=rRb
- 儿童运动体验的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/570
- 社区便利生活的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/tul
- 电子商务服务的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/5rU
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/802=yzg
- 健康饮食教育的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/fdj=138
- 社区设施共享的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%A7%91%E6%8A%80?/1Ov=8av

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
