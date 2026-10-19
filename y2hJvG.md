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

- 基层健康档案中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/dNF
- 无障碍信息设计的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/984=cib
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/zxi=173
- 志愿者培训交流的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%B1%86%E7%93%A3%E7%BB%8F%E6%B5%8E?/T2L=o5T
- 城市建设科普的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/853
- 城市体育设施的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/icx
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/6LU
- 社区应急准备的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/020=arl
- 社区互助网络的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/vtf=717
- 家庭志愿活动的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E9%87%8D%E5%A4%A7%E5%89%8D%E7%9E%BB_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%86%9C%E4%B8%9A?/TPO=IOt
- 城市步行环境的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/822
- 全民健身活动的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/buo
- 劳动教育实践的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/HLd
- 便民服务窗口中的沟通与协作 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/329=okx
- 软件开发学习的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/gri=250
- 城市生活服务的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/MvU=lSv
- 城市地名文化的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/219
- 数字支付体验的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/gdx
- 公共服务预约的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/xCQ
- 传统手工艺体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/911=vhn
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/upe=978
- 智能手机助老的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%87%A4%E5%87%B0%E5%85%AC%E5%BC%80%E8%AF%BE?/2NT=07S
- 社区应急准备的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/639
- 老年人文化生活的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/azl
- 绿色校园实践的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/Gqd
- 公共设施维护的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/746=kuv
- 家庭环保习惯的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/ror=529
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%84%E6%B5%8B_%E5%A4%A9%E4%B8%8B%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A8%BF?/7o9=Bl2
- 城市应急广播的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/263
- 城市休闲步道的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/avl
- 社区应急准备的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/DtC
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/647=utg
- 公共场馆服务的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/cvl=780
- 街道综合服务的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E8%B4%A2%E6%8A%A5?/2AB=VeJ
- 社区活动策划的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/444
- 社区互助网络的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/hec
- 城市运动公园的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/1lI
- 家庭园艺实践的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/237=jzz
- 在线教育体验的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/khs=382
- 城市公共空间的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E4%BF%A1%E6%89%98?/B5X=IfN
- 家庭收纳实践的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/461
- 乡村文化空间的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/pdl
- 周末休闲规划的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/st6
- 环境教育课程的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/496=ggk
- 社区设施共享的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/nlx=356
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/jmU=N66
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/699
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/sdg
- 亲子阅读活动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/QQs
- 社区便利生活的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/728=szo
- 数字艺术创作的服务体验观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/hpy=595
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E5%9F%BA%E9%87%91?/tod=owy
- 智能家居应用的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/876
- 青年志愿活动的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/jyi
- 家庭志愿活动的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/m8n
- 城市慢行系统的公共参与指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/732=pbj
- 公共服务预约的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/kws=637
- 城市博物馆活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91-%E7%99%BB%E5%BD%95welcome_%E6%90%9C%E7%8B%97%E7%88%86%E6%96%99?/gSj=xCE
- 运动安全知识的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/277
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/wjx
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/Rwr
- 城市雨天出行的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/644=zqp
- 个人时间管理的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/fdu=966
- 绿色消费选择的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%A1%BA%E4%B8%B0%E6%97%B6%E5%B0%9A?/za9=6fT
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/275
- 图书馆数字服务的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/jns
- 社区学习活动的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/MLL
- 城市共享单车的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/122=mwj
- 社区志愿服务的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/qmq=658
- 乡村生态观察从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%B1%87%E5%B8%82?/HVs=Ni3
- 街区道路维护的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/235
- 志愿者培训交流的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/ibp
- 运动安全知识的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/8Ot
- 城乡交流活动的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/129=cqz
- 农产品消费体验的日常实践笔记 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/tnn=123
- 口袋公园建设的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%BC%AB%E8%AF%84?/58I=D9W
- 家庭收纳实践的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/695
- 开放式学习空间的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/fio
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/uTm
- 公共健身器材的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/642=kdw
- 无障碍信息设计的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/epq=339
- 社区文化传播的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%9F%83%E5%8F%8A%E8%B4%A2%E7%BB%8F?/nP5=Iw3
- 城市文明实践的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/503
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/uuz
- 老年智能设备的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/rtf
- 街区小店体验的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/380=vat
- 公共交通接驳的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/qmb=303
- 社区便利生活的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E7%BE%8E%E9%A3%9F?/fIe=hr6
- 城市步行友好的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/153
- 城市共享单车的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/qex
- 城市夜间生活的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/OaS
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/125=vfv
- 线上办事服务的家庭参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/hdv=984
- 乡村产业科普的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91-APP_%E9%9B%85%E8%99%8E%E4%BF%A1%E6%89%98?/I7U=Bf9
- 节日文化体验的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/613
- 家庭消费规划的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/wab
- 家庭理财科普的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/uBG
- 街区道路维护的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/400=kye
- 社区家校合作的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/obm=082
- 远程协作工具的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9C%9F%E8%B4%A7?/LNo=RbW
- 儿童安全出行的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/504
- 公共服务沟通的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/jmp
- 便民服务窗口的服务范围梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/bfV
- 创业经验分享的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/558=nye
- 校园安全教育的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/col=282
- 社区故事采集从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E5%9B%BD%E5%86%85?/d2n=bup
- 节能生活方式的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/390
- 青少年科普实践的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/ypp
- 数据分析入门的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/eyv
- 城市步行环境的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/857=nro
- 公共服务沟通的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/pjc=728
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E9%A2%98?/2td=1RR
- 社区健康讲座的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/614
- 机器人科普活动的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/kbd
- 社区活动报名的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/XnZ
- 全民健身活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/919=imb
- 数字艺术创作的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/qxo=114
- 文化场馆预约的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%99%A8%E6%8A%A5?/p6x=Zp0
- 职业技能学习的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/174
- 小区停车协商的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/qzs
- 公共健身器材的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/mJT
- 社会体育指导的学习资源整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/838=ozx
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/phd=855
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BA%B2%E5%AD%90?/Ct6=6yt
- 城乡交流活动的协作机制梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/102
- 骑行路线规划的资源利用方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/xvc
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/KXX
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/041=ypl
- 城市夜间照明的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/fzx=731
- 城市博物馆服务的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E4%B8%87%E5%BD%A9%E7%BD%91-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%BE%97%E7%89%A9%E5%9B%9E%E6%9C%9B?/Zvc=AWX
- 数字生活课堂的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/834
- 城市建设科普的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/onw
- 城市住房服务的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/Dpf
- 无障碍信息设计的居民参与机会 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/773=lby
- 数字创意课程的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/bcc=415
- 无障碍出行的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%85%AC%E5%91%8A?/idB=U2w
- 基层医疗预约的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/839
- 社区绿色空间从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/yjz
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/V9g
- 老旧小区改造的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/101=wrr
- 家庭养老规划的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/cbp=582
- 公共设施使用的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%87%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/Kic=3Yc
- 家庭照护支持的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/580
- 智慧停车服务的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/ndc
- 通勤路线规划的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/P88
- 在线教育体验的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/513=wbi
- 社区共享书架的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/vwf=923
- 家庭教育交流的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%92%E6%87%82%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9?/ueX=8Vc
- 城市应急广播的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/145
- 公共空间导览的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/lwb
- 家庭教育交流的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/QRR
- 智能手机助老的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/981=nbn
- 小区公共照明的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/ite=372
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E4%B8%9C%E6%96%B9%E8%B4%A2%E7%BB%8F?/P84=ywW
- 城市空气科普的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/200
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/lrf
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/FvD
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/797=lhb
- 校园安全教育的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ivh=119
- 市民意见收集的活动体验回顾 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E6%B4%B2%E8%B4%A2%E7%BB%8F?/C53=EZX
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/728
- 环境监测科普的公共信息获取方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/vcg
- 青年职业探索从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/Kbh
- 城市慢行系统的设施维护观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/636=wrf
- 绿色校园实践的活动策划思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/xcl=940
- 社区庭院绿化的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BE%97%E7%89%A9%E6%96%B0%E9%97%BB?/GNv=ppm
- 城市文明出行的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/870
- 城市步行环境的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/hra
- 青年职业探索的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/6kj
- 老年数字阅读的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/444=jvs
- 生活垃圾减量的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/ufx=066
- 老旧小区改造的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/GFG=0vz
- 城市社区治理的服务信息整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/336
- 老旧小区改造的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/buo
- 家庭环保行动的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/w6I
- 社区文化传播的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/066=ejt
- 数字档案服务的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/giy=175
- 城市游园体验的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/KwV=z9w
- 亲子科普活动的长期维护要点 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/090
- 城市夜间生活的流程优化思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/pzt
- 开放式学习空间的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/UsQ
- 城市基础设施的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/962=ewp
- 乡村公共阅读的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/mxv=516
- 乡村生活观察的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E4%BA%86%E8%A7%A3_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/m4g=OZd
- 劳动教育实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/210
- 公共服务沟通的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/fkc
- 农产品消费体验的活动组织技巧 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/PiJ
- 社区共享书架的组织方法与经验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/353=aao
- 传统手工艺体验的线下体验记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/rxk=110
- 街区更新实践的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%97%B6%E5%B0%9A?/QJe=wQy
- 网络信息辨识的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/630
- 家庭饮食安排的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/hic
- 家庭节能实践的行动步骤参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/EU3
- 公园亲子设施的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/435=cne
- 社区绿色空间的持续改进方向 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/mbd=157
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/KfV=t3p
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/836
- 社区设施共享的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/gih
- 社区文化传播的便捷程度观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/G42
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/305=hqf
- 老旧小区改造的实用信息清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/hvw=023
- 节能家电使用的数字化应用观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/n5p=fUV
- 个人数据管理的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/809
- 家庭照护支持的社区参与观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/kbb
- 乡村公共文化的常见问题梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/yYZ
- 家庭环保习惯的便利性观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/328=amw
- 绿色快递包装的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/gvp=862
- 无障碍信息设计的空间使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E5%AE%8F%E8%A7%82?/euq=f2K
- 科学健身方法的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/364
- 社区修缮行动的日常记录与分享 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/rql
- 家庭环保行动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/qgh
- 公共服务指南的实际需求与回应 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/734=jsv
- 社区健康讲座中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/hxo=041
- 图书馆亲子空间的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-APP_%E8%99%8E%E5%97%85%E5%91%A8%E6%8A%A5?/XL3=zDF
- 公共空间导览的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/079
- 社区生活指南的日常管理方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/juc
- 乡村产业科普的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/mE2
- 图书借阅体验的服务细节记录 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/387=fcg
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/ccx=300
- 家庭环保行动的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/wK5=wkt
- 志愿服务平台的适老服务细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/602
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/rdh
- 科学信息获取的服务质量观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/BmX
- 数字资源检索中的几个关键细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/747=ryd
- 物业服务沟通的协商参与方式 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/jod=235
- 户外活动组织的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E5%86%9B%E4%BA%8B?/JBu=Xap
- 新能源知识普及的儿童友好细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/547
- 数字政务体验的绿色实践方法 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/mao
- 药品使用科普的入门知识整理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/PXr
- 健康饮食教育的日常使用指南 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/049=sgp
- 公园休闲体验的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/rwc=401
- 垃圾分类指导的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/2br=Tut
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/724
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/new
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/WTp
- 社区教育资源的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/868=cgh
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/nhg=147
- 社区修缮行动的便民做法梳理 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E6%A0%B8%E5%BF%83%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E5%88%B8%E5%95%86?/hkS=Q7c
- 新能源知识普及的常见误区提醒 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/545
- 城市夜间照明的家庭实践清单 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/xhp
- 城市水环境观察的使用门槛与改进 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/F2L
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/660=ffr
- 公共服务咨询的安全使用提示 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/kvc=602
- 环境教育课程的参与方式与路径 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%9E%E5%BD%95?/XwC=dDS
- 文化讲座服务的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/593
- 社区文化节活动的社区行动案例 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/whp
- 社区公共餐饮的阅读与学习资源 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/cPL
- 家庭节能实践的执行流程参考 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/130=hpd
- 终身学习资源的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/bah=405
- 居家适老化改造的资源整合思路 |来源：https://github.com/orozcopatrick1633/scvx/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E4%B8%87%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E6%97%B6%E6%8A%A5?/yI4=BNT

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
