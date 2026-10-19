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

- 社区活动报名的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/831
- 社区家政服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/ofi
- 开放式学习空间的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/zuc
- 老年人日常照护的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/058=yvr
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/beb=240
- 社区活动空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8F%91_%E6%BE%8E%E6%B9%83%E7%99%BE%E7%A7%91?/7Q9=4BF
- 低碳社区实践的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/205
- 社区阅读服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/qwa
- 城市人文观察的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/uTK
- 物业服务沟通的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/617=zbo
- 社区托育服务的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/zha=664
- 软件开发学习的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%9F%8E%E4%BA%8B?/vUI=Uev
- 地方美食文化的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/390
- 社区科普课堂的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/ysn
- 社区协商议事的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/MAd
- 科学观察活动中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/229=pxz
- 健康饮食教育的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/fme=413
- 社区知识分享的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%BB%BC%E8%89%BA?/zTW=Jg7
- 线上办事服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/571
- 社区便利生活的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/ykf
- 学校食育活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/wic
- 低碳社区实践的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/251=cfi
- 数字艺术创作的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/gjm=231
- 节气饮食文化的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91app_%E7%9F%A5%E4%B9%8E%E7%99%BE%E7%A7%91?/Aip=ozN
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/137
- 终身学习资源的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/suz
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/DxO
- 家庭收纳实践的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/406=aoo
- 家庭园艺实践的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/qrp=479
- 志愿服务平台的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E4%B8%93%E4%B8%9A%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E8%BF%B0%E8%AF%84?/L22=zNK
- 城市体育设施的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/109
- 智慧停车服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/huv
- 公共文化活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/LF6
- 生活垃圾减量的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/226=dki
- 社区知识分享的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/osw=764
- 城市文化路线的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E6%9C%8D%E9%A5%B0?/lQX=bug
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/714
- 社区老年食堂的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/dyj
- 乡村休闲旅游的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/f2L
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/326=tsk
- 公共空间照明的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/rti=629
- 城市骑行环境的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BDapp_%E6%BE%B3%E4%BA%9A%E8%B4%A2%E7%BB%8F?/mXF=J8D
- 城市适老服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/411
- 亲子科普活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/uvg
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/dhJ
- 图书馆活动策划的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/676=qda
- 社区商业活力的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/wpd=955
- 城市应急科普的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E5%80%BC%E5%BE%97%E4%BF%A1%E8%B5%96%E7%9A%84%E8%80%81%E5%93%81%E7%89%8C_360%E5%88%8A%E7%99%BB?/dx9=hTX
- 急救知识普及的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/278
- 便民服务窗口的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/jzq
- 城市文明出行的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/a2W
- 街区更新实践的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/880=ovx
- 社区垃圾回收的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/vba=296
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BD%A9%E7%A5%A8welcome_360%E6%88%B7%E5%A4%96?/A83=XVt
- 社区垃圾回收的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/882
- 城市雨天出行的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/fof
- 农村环境治理的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/JeW
- 社区休闲设施的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/707=nkr
- 城市地名文化的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/nco=556
- 社区科普课堂的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%80%E5%88%86welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/7TY=mpC
- 公共场馆服务的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/851
- 街区绿化养护的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/qiw
- 生活技能分享的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/5tC
- 志愿服务平台的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/975=zpr
- 个人信息保护的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/lbu=294
- 社区生活指南的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%BB%86%E8%AF%B4_welcome%E7%9B%88%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AF%BC%E5%B8%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/thH=ck1
- 城市休闲步道的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/402
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/tty
- 家庭急救准备的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/SxR
- 城市博物馆活动的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/636=fgx
- 数字便民地图的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/ayz=931
- 青年就业服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%97%E8%AF%84%E8%AE%BA?/T0V=vZ5
- 家庭用电安全的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/130
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/tks
- 社区宠物管理的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/dnC
- 青年志愿活动的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/869=tat
- 安全出行教育的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/yrd=768
- 家庭环保习惯的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E4%B9%90%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E5%97%85%E9%9F%B3%E4%B9%90?/uUY=jRl
- 传统节日科普的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/938
- 非遗体验活动的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/acu
- 科技馆参观体验的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/MJZ
- 骑行路线规划的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/095=ged
- 社区阅读服务的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/ine=511
- 绿色消费选择的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8---%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E6%8A%96%E9%9F%B3%E5%9B%BD%E9%99%85?/8ay=Ri2
- 社区邻里服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/923
- 公共服务预约的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/nok
- 社区教育资源的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/VFm
- 食品安全科普的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/422=dff
- 学校食育活动的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/rwp=853
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%AF%8C%E7%BF%81%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome%E7%99%BB%E5%BD%95_%E5%BF%85%E5%BA%94%E5%86%9B%E4%BA%8B?/IvB=aHU
- 城乡交通衔接的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/987
- 乡村生态旅游的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/oqr
- 城市文明出行中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/v0W
- 健康饮水科普的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/729=nex
- 儿童阅读角的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/vki=413
- 数字政务体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome%E7%8E%AF%E7%90%83_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/Lcx=dwM
- 家庭环保习惯的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/419
- 社区商业活力的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/leb
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/s5V
- 物业服务沟通中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/144=qhm
- 城市基础设施的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/osk=931
- 社区文化节活动的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8C%87%E5%AF%BC_%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%B0%91%E7%94%9F?/20A=QDR
- 家庭健康管理的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/935
- 医院导诊服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/bov
- 社区故事采集的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/4gx
- 全民健身活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/624=lgv
- 社区垃圾回收的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/wmv=009
- 社区修缮行动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E9%97%AE%E5%8D%B7?/Oci=Fpm
- 药品使用科普的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/179
- 城市应急广播的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/owh
- 数字生活课堂的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/iBL
- 邻里共享空间的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/311=qyc
- 城市可持续生活的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/rvi=173
- 个人时间管理的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%AE%A2%E6%9C%8D%E7%94%B5%E8%AF%9D_%E5%BE%97%E7%89%A9%E6%96%87%E5%BA%93?/Ojk=UsG
- 节假日出行安排的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/624
- 骑行路线规划的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/mrv
- 小区停车协商的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/9D9
- 社区便利生活的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/249=zmd
- 食品配送体验的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/dtb=872
- 环境监测科普的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%92%AD%E6%8A%A5?/NMo=z5G
- 线上阅读资源的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/181
- 家庭志愿活动的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/tth
- 数字创作工具的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/KWl
- 家庭安全提示的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/395=asl
- 社区庭院绿化的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/vca=356
- 新能源出行的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%839142_%E6%8A%96%E9%9F%B3%E7%A4%BE%E5%8C%BA?/qpB=QqB
- 公共服务数字化的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/506
- 街区道路维护的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/nxf
- 社区设施共享的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/OvE
- 在线教育体验的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/885=tph
- 社区垃圾回收的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/bgt=591
- 创业经验分享的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_360%E5%9B%AD%E8%89%BA?/sPJ=iZ8
- 邻里共享空间的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/309
- 科学运动指导从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/wvb
- 数字学习资源的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/OQT
- 食品配送体验中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/346=lfo
- 街道综合服务的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/jln=790
- 地方旅游导览的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%90%8D%E5%8F%91%E5%9C%B0%E5%9D%80_%E6%96%B0%E6%B5%AA?/Tt4=rtA
- 公共服务指南的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/875
- 家庭志愿活动的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/goa
- 城乡公共服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/KWP
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/871=lsb
- 老年人日常照护的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/fiw=722
- 社区知识分享的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E4%BC%81%E4%B8%9A%E7%99%BE%E7%A7%91_%E6%90%9C%E7%8B%90%E5%8F%B8%E6%B3%95?/VVQ=VBF
- 远程协作工具的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/927
- 健康信息获取的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/kjc
- 数字设备回收的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/8Td
- 文明养宠科普的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/530=lzu
- 读书会组织的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/riv=471
- 绿色快递包装的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91welcome%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83-%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/5Dg=6JS
- 城市绿色交通的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/001
- 智能手机助老的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/erc
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/BQH
- 数字支付体验的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/216=yjb
- 终身学习资源的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/gpr=563
- 个人时间管理的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%A4%84%E7%BD%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/6i8=2en
- 邻里共享空间中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/138
- 便民维修服务有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/zyy
- 机器人科普活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/ARg
- 绿色快递包装的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/750=omv
- 城市微更新实践的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/fpp=417
- 城市慢行系统的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%BF%9D%E8%A7%84_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/rLm=r5G
- 急救知识普及的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/302
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/myx
- 便民维修服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/JPB
- 图书馆亲子空间的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/791=lsr
- 青少年户外教育的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/vux=029
- 家庭园艺实践的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9welcome%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%90%E5%88%B8%E5%95%86?/nVv=Gbm
- 社区公共卫生的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/891
- 生活垃圾减量的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/qhf
- 农产品消费体验的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/Ner
- 地方民俗记录的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/506=maq
- 城市建设科普的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/bqm=371
- 社区应急准备的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E4%BD%93%E8%82%B2?/YqA=Vsq
- 数字政务体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/749
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/rzj
- 儿童友好街区的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/eE1
- 亲子阅读活动的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/936=acn
- 社区公共卫生的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/nqd=844
- 儿童户外活动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9%E6%8E%A8%E8%8D%90_%E5%87%A4%E5%87%B0%E6%B1%87%E5%B8%82?/7wW=WlB
- 基层服务创新的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/870
- 全民健身活动的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/qin
- 健康步道使用的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/uxg
- 基层服务创新的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/859=drq
- 社区共享书架的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/rur=573
- 家庭急救准备的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E4%BA%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E4%B9%A6%E7%94%BB?/aQ8=y8L
- 食品配送体验的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/818
- 公共服务预约的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/kfl
- 家庭养老规划的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/5O8
- 志愿者培训交流的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/678=ysl
- 城市公共艺术的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/hkh=596
- 社区邻里服务中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E8%B5%84%E9%87%91%E5%AE%89%E5%85%A8%E5%90%97_%E6%96%B0%E6%B5%AA%E8%AF%84%E8%AE%BA?/IeM=t4k
- 基层健康服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/694
- 家庭照护支持的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/pfq
- 社区手工活动的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/kGE
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/439=pmg
- 乡村文化空间的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/mti=617
- 家庭环保行动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E6%97%97%E4%B8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8F%B0%E5%AD%90_%E5%A4%AE%E8%A7%86%E5%8A%A8%E6%BC%AB?/c2W=pFC
- 节约用水实践的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/303
- 公共图书馆服务的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/dvi
- 社区交通安全的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/1p9
- 劳动教育实践的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/303=kkf
- 公共卫生设施的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/ffw=648
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%97%97%E4%B8%8B%E7%9A%84%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E7%89%B9%E7%A8%BF?/S78=ERC
- 节气饮食文化的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/992
- 公共卫生宣传的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/cud
- 学校食育活动中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/sdD
- 家庭健康管理的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/489=qrz
- 乡村公共文化的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/tnb=924
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E4%BA%91%E6%8A%80%E6%9C%AF%E6%8F%90%E4%BE%9B%E5%BD%A98_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/rsu=X5B
- 社区儿童活动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/690
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/mph
- 乡村休闲旅游的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/yof
- 社会体育指导的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/357=aqm
- 物业服务沟通的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/vcz=276
- 节气饮食文化的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9app_%E8%B1%86%E7%93%A3%E4%BA%BA%E5%A4%A7?/EKM=EGp
- 市民热线服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/409
- 社区手工活动的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/nyc
- 家庭环保习惯的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/2F7
- 乡村教育资源的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/793=alw
- 物业服务沟通的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/oye=426
- 社区文化节活动的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E4%BA%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%A4%B4%E6%9D%A1%E6%8E%A2%E5%BA%97?/E9c=C1g
- 人工智能科普的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/076
- 社区公共卫生的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/teq
- 公共设施维护从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/IFT
- 城市博物馆活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/763=wse
- 公共设施维护中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/lyd=918
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E6%B6%88%E8%B4%B9?/zYE=OTK
- 社区花园共建中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/729
- 社区消防演练的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/wwj
- 社区应急准备的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/nW7
- 乡村公共阅读的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/616=ozt
- 科技馆参观体验的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/pfb=647
- 邻里共享空间的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%B4%A2%E7%BB%8F?/dSz=LtB
- 居家防滑改造的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/094
- 城市公共厕所的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/pdf
- 社区体育组织的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/xZm
- 零废弃生活尝试的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/971=yli
- 公益活动组织的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/ovt=499
- 数字生活课堂的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B8%BB%E9%A1%B5%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E5%9C%B0%E4%BA%A7?/C4T=WmF
- 校园安全教育的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/228
- 社区修缮行动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/qvq
- 地方美食文化的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/azv
- 在线学习体验的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/564=vyq
- 公共场馆服务的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/xaj=274
- 城乡公共服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E4%B9%8B%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/niY=Ti2
- 基层健康服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/839
- 儿童友好街区的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/abj
- 软件开发学习的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/3vF
- 节能生活方式的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E6%AD%A3%E8%A7%84%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%9B%B4%E6%92%AD?/643=fef

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
