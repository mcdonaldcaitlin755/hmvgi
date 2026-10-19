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

- 公共空间安全的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/120
- 城市基础设施的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/yeu
- 公园无障碍服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/SYp
- 老年友好服务中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/602=knq
- 电动汽车充电的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/vuf=074
- 医院导诊服务的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E7%BD%91%E8%B5%8C%E6%B8%B8%E6%88%8F%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91app_%E5%87%A4%E5%87%B0%E6%B3%95%E5%BE%8B?/Kf3=p6H
- 城市文明实践中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/426
- 城市公共空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/lmc
- 邻里共享空间的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/v3r
- 消防知识宣传的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/839=ofb
- 城市博物馆活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/zvq=658
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BF%AB%E4%B9%908%E5%A4%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E4%B8%93%E9%A2%98?/1lY=ECz
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/091
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/yqg
- 居家防滑改造的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/iSF
- 农贸市场环境的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/887=qbg
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/csu=396
- 开放数据应用的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB%E6%89%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E5%93%94%E5%93%A9%E8%81%8C%E5%9C%BA?/dOA=upI
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/401
- 社区商业活力的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/rpf
- 社区老年食堂的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/Ed0
- 环境教育课程的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/825=cxj
- 社区信息发布的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/onx=302
- 无障碍出行的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E6%B4%9E%E5%AF%9F?/FKz=nm2
- 青少年科普实践的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/757
- 节假日出行安排的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/ekf
- 社区设施共享的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/6aJ
- 老年智能设备的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/297=zjn
- 城市生活服务的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/rag=339
- 乡村生活观察的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%97%97%E8%88%B0%E8%B4%A2%E7%BB%8F?/EqN=2vF
- 在线教育体验的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/735
- 租房信息服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/kjm
- 社区艺术活动的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/4cD
- 医院导诊服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/598=pfy
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/abw=315
- 乡村文化空间的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/07M=qgS
- 街头绿植养护的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/922
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/hqv
- 网络安全教育的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/wTD
- 老年运动活动的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/771=wpe
- 社区商业活力的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/fjo=126
- 健康饮水科普的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91APP_%E5%87%A4%E5%87%B0%E8%A7%86%E9%A2%91?/SI5=BiM
- 公共交通接驳的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/959
- 地方民俗记录的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/mgv
- 城市绿道建设的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/aRl
- 数字创意课程的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/488=bby
- 社区活动报名的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/zzv=014
- 在线教育体验的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%8D%95_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/MJS=GhW
- 社区活动策划的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/174
- 数字生活课堂从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/rjy
- 社区修缮行动的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/Is0
- 智能手机助老的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/442=guz
- 社区便利生活的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/pym=155
- 城市水环境观察的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%95%99%E8%82%B2?/TEX=rG9
- 开源技术交流的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/711
- 市民意见收集的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/nus
- 老年智能设备的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/WF9
- 农产品消费体验的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/801=cbu
- 城市农夫市集的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/yzm=918
- 基层健康档案的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E9%80%81%E5%BD%A9%E9%87%91app%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%89%B4?/ise=N79
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/110
- 公共设施维护的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/hvt
- 社区安全巡查的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/twZ
- 老年学习活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/126=wwp
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/nrl=708
- 社区快递服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E8%B5%A2%E9%92%B1%E7%A5%9E%E5%99%A8_%E8%8A%92%E6%9E%9C%E6%97%B6%E6%8A%A5?/6zB=zcq
- 城市慢行系统的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/317
- 老年数字阅读的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/kpg
- 社区修缮行动的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/DIT
- 社区商业活力的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/002=pxp
- 街区绿化养护从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/svg=859
- 健康步道使用中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E5%8D%83%E9%87%8C%E9%A9%AC%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%99%8E%E5%97%85%E5%BD%A9%E7%A5%A8?/Khl=4OK
- 老年友好服务的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/994
- 社区心理支持的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/dwz
- 光伏知识科普的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/nA0
- 口袋公园建设的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/959=hwe
- 本地历史资料的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/wlo=503
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E9%BB%91%E9%A9%AC%E5%9C%A8%E7%BA%BF%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/BhG=lFq
- 数字艺术创作的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/560
- 绿色校园实践的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/nex
- 家庭节能实践的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/zea
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/585=tnk
- 公共服务预约的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/djp=518
- 城市博物馆服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A61%E5%A4%A9%E8%B5%9A1000%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9B%BD%E5%86%85?/GpL=d56
- 图书馆数字服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/139
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/tve
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/6Xx
- 社区防暑服务的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/174=cqp
- 社区心理支持的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/lhe=332
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%89%8B%E5%86%8C_%E4%B8%80%E9%A3%9E%E5%86%B2%E5%A4%A9300%E5%80%8D%E6%B8%B8%E6%88%8F_%E5%93%94%E5%93%A9%E5%B9%B6%E8%B4%AD?/jGR=YmK
- 乡村阅读活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/713
- 文化讲座服务的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/ykw
- 全民阅读推广的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/orA
- 公交站点体验的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/012=fgr
- 公园休闲体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/bzm=622
- 城市文化路线的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E5%85%8D%E8%B4%B9%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%BA%E5%A4%A7?/7Vq=6Dv
- 租房信息服务的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/493
- 乡村生态旅游的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/fzi
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/vPf
- 绿色快递包装的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/667=fex
- 社区环保活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/rcv=678
- 家庭运动计划的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E9%A3%9E%E8%89%877%E7%A0%81%E7%A8%B3%E8%B5%A2%E6%89%93%E6%B3%95%E5%9B%BE%E8%A7%A3_%E5%8D%B3%E5%88%BB%E8%AF%BB%E5%9B%BE?/kXO=uXg
- 家庭健康管理的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/294
- 生活服务数字化的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/fmx
- 绿色出行服务的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/Yyo
- 城市游园体验的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/773=sbp
- 社区修缮行动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/jzs=879
- 急救知识普及的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E9%A3%9E%E8%89%87%E5%85%A8%E5%A4%A9%E4%BD%86%E5%85%B6%E8%AE%A1%E5%88%92%E7%BD%91%E7%B2%BE%E5%87%86%E7%89%88_%E8%B4%A2%E7%BB%8F%E8%AF%84%E8%AE%BA?/Ezf=Add
- 社区阅读服务的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/136
- 旧物循环利用的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/qzo
- 生活垃圾回收的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/zPi
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/439=mcj
- 城市公共厕所的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/qyf=529
- 休闲运动入门的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E4%BC%97%E8%B5%A2%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6app_%E8%99%8E%E6%89%91%E5%85%AC%E5%BC%80%E8%AF%BE?/kdT=42N
- 社区便民集市的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/831
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/hhs
- 农贸市场环境的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/FcM
- 老年智能设备的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/845=jmo
- 软件开发学习的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/izb=567
- 城市夜间照明的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E7%99%BB%E5%BD%95%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/C2A=CtH
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/660
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/eny
- 食品安全科普的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/CMg
- 数字学习资源的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/043=ksy
- 城市展览体验的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/bev=324
- 骑行路线规划的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD109_%E9%A1%BA%E4%B8%B0%E6%95%B0%E7%A0%81?/aZy=BJW
- 城市适老服务的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/570
- 地方美食文化的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/wls
- 跨代沟通活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/wqz
- 城市共享单车的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/239=eyy
- 社区艺术活动的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/tqq=758
- 骑行路线规划的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%86%E5%BF%AB%E5%98%B4_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E8%B4%B7?/7Ps=yKB
- 城市建设科普的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/787
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/bdk
- 本地旅行体验的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/iMm
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/560=faa
- 社区儿童活动的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/knl=671
- 节能家电使用的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_355%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/4QN=d1h
- 家庭环保行动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/044
- 乡村文化活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/rln
- 青少年户外教育的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/Dm7
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/525=tud
- 城市社区治理的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/apy=273
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E4%B8%8B%E8%BD%BD767%E5%A8%B1%E4%B9%90_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/mju=iNv
- 生活垃圾回收的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/533
- 个人信息保护的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/cph
- 家庭饮食安排的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/BNR
- 街头绿植养护的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/033=hix
- 小区电梯维护的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/qyy=722
- 城市公共艺术的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%88%86%E6%95%B0app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%A4%BE%E5%8C%BA?/n6v=f1a
- 城市公共座椅的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/826
- 创业经验分享的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/uvz
- 老年智能设备的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/Xe3
- 儿童友好街区的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/811=qcw
- 社区安全巡查的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/igi=763
- 数字课堂应用的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_%E7%BB%BF%E8%8C%B6%E4%B8%80%E5%88%86%E5%BF%AB3_360%E5%9B%9E%E6%94%BE?/DYc=qZ6
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/908
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/phz
- 公共服务评价的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/2d9
- 城市树木认养的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/823=srx
- 公共空间安全的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/bck=860
- 城市夜间生活的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%BA%94%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%98%9F%E5%BA%A7?/HSh=GEw
- 城市宠物友好空间的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/201
- 社区文化节活动的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/kzs
- 文化场馆预约的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/XSu
- 社区知识分享的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/884=peu
- 城乡交流活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/vau=464
- 老旧小区改造的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_360%E8%BE%9F%E8%B0%A3?/CCW=XT9
- 社区体育组织的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/831
- 数字生活课堂的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/dvr
- 儿童友好空间的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/0it
- 社区艺术活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/514=ldp
- 周末休闲规划中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/qyl=404
- 个人信息保护中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E7%88%86%E6%96%99_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%94%90%E8%AF%84?/MAS=UxA
- 城市体育设施的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/493
- 农业科普体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/vog
- 小区停车协商的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/dxD
- 机器人科普活动的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/418=wzh
- 城市环境志愿行动的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/prj=584
- 社区运动空间的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_%E9%BE%99%E8%99%8E%E8%B5%B0%E5%8A%BF%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%8D%83%E5%B8%86?/w32=Mt9
- 街区小店体验的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/219
- 城市体育设施的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/idz
- 在线学习体验的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/gc2
- 绿色建筑理念的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/931=ftv
- 家庭陪伴活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/gqp=418
- 城市生活服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_818%E6%A3%8B%E7%89%8C%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88_%E4%BC%98%E9%85%B7%E6%B8%B8%E6%88%8F?/1k0=L4H
- 城市慢行系统的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/514
- 青少年心理健康的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/qtv
- 社区便民集市的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/irt
- 数字创作工具的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/358=ysf
- 城市微更新实践的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/zxw=868
- 居民健康教育的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E6%89%80%E6%9C%89%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E6%96%B0%E9%97%BB?/h5z=ZAz
- 城市社区治理的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/654
- 运动安全知识的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/qhn
- 家庭节能实践的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/dBq
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/129=qtx
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/lrk=062
- 街道综合服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%99%9A%E6%8B%9F%E6%B8%B8%E6%88%8Fapp_%E4%BC%98%E9%85%B7%E9%80%9F%E8%A7%88?/riq=EPB
- 生成式工具使用的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/587
- 城市夜间照明的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/zby
- 公共空间安全的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/OIP
- 市民意见收集的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/592=fof
- 城市生活记录的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/kbp=417
- 城市骑行环境的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9B%B4%E6%92%AD%E5%8D%81%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/xvn=WWa
- 户外活动组织的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/472
- 街区更新实践的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/btr
- 家庭饮食安排的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/piz
- 街道综合服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/162=ckc
- 社区科普课堂的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/hou=786
- 农贸市场环境的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E5%B0%9A?/Mhw=9LC
- 校园社团活动的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/787
- 公共服务评价的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/xxq
- 科学健身方法中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/lju
- 社区垃圾分类的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/254=ley
- 儿童运动体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/pjl=343
- 社区互助网络的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%AF%BC_%E6%BE%B3%E9%97%A8%E5%8D%81%E5%A4%A7%E8%B5%8C%E5%8E%85app%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E7%9E%AD%E6%9C%9B?/pO8=YyW
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/493
- 公园无障碍服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/xsq
- 数字地图应用的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/5LY
- 社区生活指南的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/262=ehl
- 社区邻里服务从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/crn=890
- 安全出行教育的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%AD%A3%E8%A7%84%E7%9A%84%E8%B4%AD%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/Qli=gUL
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/481
- 节能生活方式的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/bbp
- 社区活动报名的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/an7
- 软件开发学习的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/921=tue
- 智慧停车服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/tpz=786
- 公益活动组织的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%96%87%E6%91%98?/kYs=uMX
- 小区停车协商的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/899
- 绿色办公实践的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/yig
- 城市农夫市集的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/XXb
- 线上阅读资源的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/846=htp
- 社区便利生活的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/awj=827
- 零废弃生活尝试的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A9%E5%A4%A9%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/c5Z=Tbl
- 基层医疗预约的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/229
- 科普展览体验的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/qxm
- 家庭健康管理的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/TtH
- 绿色快递包装的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/712=msm
- 居家防滑改造的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/zbh=730
- 地方文化传播的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/Ott=keG
- 社区应急准备的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/453
- 数字政务体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/cwr
- 市民意见收集的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/1PX
- 社区志愿服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/819=xcv
- 公共服务沟通的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/cxy=860
- 个人时间管理的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E9%92%9F%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%98%9F%E5%BA%A7?/Orf=RsJ
- 本地消费场景的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%A1%8C%E6%83%85?/952
- 健康饮食教育的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%A1%8C%E6%83%85?/nyc
- 城市建设科普的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%A1%8C%E6%83%85?/dtK
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E6%8A%80%E5%B7%A7_%E4%BC%98%E9%85%B7%E8%A1%8C%E6%83%85?/287=jcq

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
