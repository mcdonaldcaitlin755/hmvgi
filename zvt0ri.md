# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:17**

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

- 旧物循环利用中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/ukd=027
- 社区商业活力的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E8%BF%B0%E8%AF%84?/apR=Nnd
- 生成式工具使用的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/864
- 远程协作工具的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/qji
- 社区托育服务的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/LlY
- 数字创作工具的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/208=nqx
- 社区交通安全的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/xou=697
- 基层健康档案的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5%E7%89%88_%E9%A1%BA%E4%B8%B0%E6%98%9F%E5%BA%A7?/ejl=UAV
- 公共场所导视的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/314
- 环境教育课程的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/fur
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/tRX
- 网络安全教育的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/868=krz
- 社区邻里服务的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/xvx=419
- 公共服务评价的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E9%94%90%E8%AF%84?/Mqd=cNQ
- 乡村生态观察的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/285
- 小微企业服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/ieb
- 老年数字阅读的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Bua
- 个人数据管理的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/867=yow
- 公共服务数字化的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/cnp=666
- 社区读书角建设的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/lw1=GB4
- 公共设施维护的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/133
- 城市雨天出行的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/rbo
- 城市社区治理的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/J5z
- 社区设施共享的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/771=jkc
- 家庭收纳实践的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/vqu=099
- 家庭节能实践的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_49%E5%BD%A9%E6%B0%91app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/KtH=JoL
- 非遗课堂体验的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/156
- 公共交通接驳的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/loq
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/dH8
- 线上办事服务的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/497=xem
- 志愿服务平台的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/vto=011
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%80%E7%B2%BE%E5%87%86_%E5%A4%AE%E8%A7%86%E5%9B%9E%E6%94%BE?/Uc4=Trc
- 老年友好服务的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/675
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/ixv
- 小微企业服务的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/2dy
- 城市慢行系统的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/940=ljp
- 公交无障碍服务的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/fyl=252
- 科学教育活动中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_%E5%9B%BD%E6%B0%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%8A%96%E9%9F%B3%E5%9F%8E%E4%BA%8B?/kCw=mA2
- 信息无障碍体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/934
- 学校体育活动的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/fad
- 城乡交流活动的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/Q19
- 旧物循环利用的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/331=twv
- 儿童阅读角的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/hwu=668
- 城市噪声观察的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_%E5%90%89%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome%E6%96%B0%E7%89%88_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/RfP=RUj
- 公共服务咨询的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/913
- 智慧城市体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/sja
- 科学信息获取的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/qQA
- 传统节日科普的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/535=cfg
- 数字阅读服务的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/bvh=065
- 物业服务沟通的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%28%E4%B8%AD%E5%9B%BD%29_%E9%A1%BA%E4%B8%B0%E6%95%99%E8%82%B2?/D5E=M8L
- 城市文化路线的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/707
- 个人数据管理的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/zqa
- 青少年心理健康的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/y5T
- 网络安全教育的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/426=aqn
- 社区老年食堂的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/hji=346
- 社区活动报名的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E5%90%89%E5%BD%A9Welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E5%B7%85%E5%B3%B0%E8%B4%A2%E7%BB%8F?/Xbx=WVd
- 家庭健康科普的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/731
- 儿童户外活动的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/oaa
- 便民服务地图的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/L8z
- 公共卫生宣传的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/766=xof
- 网络安全教育的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/gwv=344
- 城市游园体验的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90%E5%BD%A9%E7%A5%9E_%E8%B4%A2%E7%BB%8F%E5%8A%A8%E6%80%81?/jTL=8dh
- 绿色快递包装的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/332
- 亲子科普活动的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/fuo
- 农贸市场环境的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/UKx
- 网络信息辨识的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/528=kzp
- 数字生活课堂的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/uws=488
- 城市水环境观察的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E5%90%89%E5%BD%A9VIP%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%B1%86%E7%93%A3%E5%BF%AB%E6%8A%A5?/UBp=ocU
- 在线学习体验的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/670
- 城市博物馆服务的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/iir
- 图书馆亲子空间的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/TCZ
- 城市可持续生活的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/631=hib
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/hdk=168
- 居民健康教育的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8APP%E6%AD%A3%E5%BC%8F%E7%89%88%E5%8A%9F%E8%83%BD%E4%BB%8B%E7%BB%8D_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%BC%80%E8%AF%BE?/y4I=Y8t
- 家庭教育交流的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/587
- 城市适老服务的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/nxp
- 无障碍出行从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/VDm
- 城市水环境观察的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/358=cro
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/oij=090
- 公共服务指南的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A5%A8?/g1a=fYG
- 亲子科普活动的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/209
- 城市建设科普的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/qhy
- 社区协商议事的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/Z0B
- 本地历史资料的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/374=zzd
- 在线学习体验的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/lnp=955
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8welcome_%E7%BD%91%E6%98%93%E6%B6%88%E8%B4%B9?/S6l=1dG
- 校园安全教育的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/707
- 家庭用电安全的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/qnd
- 乡村阅读空间的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/srt
- 公园亲子设施的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/878=vgk
- 社区故事采集的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/exo=979
- 青少年心理健康的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E6%9C%9F%E8%B4%A7?/NTb=arm
- 老年友好服务的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/833
- 城市运动公园的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/zgx
- 城市休闲步道的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/kPV
- 公共服务评价的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/472=nkc
- 文化场馆预约的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/wtt=699
- 家庭网络使用的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%BC%AB%E8%AF%84?/rR1=Kc8
- 家庭饮食安排的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/406
- 乡村生活观察的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/wdc
- 乡村文化空间的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/KSr
- 食品安全科普的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/850=lhy
- 开放式学习空间的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/hvh=311
- 创业经验分享的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E5%A4%9A%E7%9B%88%E5%BD%A9%E7%A5%A8%E7%BA%BF%E8%B7%AF%E5%AF%BC%E8%88%AA_%E9%9B%85%E8%99%8E%E6%91%84%E5%BD%B1?/2ze=ufO
- 便民维修服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/756
- 乡村公共阅读的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/jws
- 青年就业服务的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/fUk
- 数字学习资源的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/548=jon
- 城市游园体验的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/tcg=965
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%A5%BD%E8%BF%90%E5%BF%AB3%E6%98%AF%E5%AE%98%E6%96%B9%E5%BD%A9%E7%A5%A8%E5%90%97_%E5%BF%AB%E6%89%8B%E8%AE%BF%E8%B0%88?/1bh=3l5
- 便民维修服务中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/569
- 青少年科普实践的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/wtj
- 口袋公园建设的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/kGL
- 急救知识普及的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/201=woq
- 光伏知识科普的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/dyd=373
- 儿童运动体验的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB%E7%9B%88%E5%BD%A9%E7%A5%A8app_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%88%B7%E5%A4%96?/LIV=vt3
- 小区公共照明的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/760
- 社区科普课堂的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/wjf
- 城市休闲步道的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/dsm
- 社区学习活动的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/728=esv
- 社区健康讲座的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/mvz=247
- 社区宠物管理的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%B1%87%E5%BD%A9%E7%BD%91%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%8D%83%E5%B8%86?/aKv=5a5
- 数字课堂应用的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/325
- 农贸市场环境的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/msy
- 城市便民驿站的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/om8
- 数字设备回收的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/893=zab
- 城市运动公园的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/duz=349
- 城乡交流活动的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E5%AD%A6%E4%B9%A0_%E6%B1%87%E5%BD%A9%E7%BD%91app_%E5%8D%8E%E8%AF%9A%E8%B4%A2%E7%BB%8F?/eCS=Kqe
- 绿色出行服务的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/464
- 农产品消费体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/zyo
- 急救知识普及的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/twn
- 亲子阅读活动的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/853=alk
- 小区停车协商的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/mgx=883
- 社区活动空间的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E5%AE%A0%E7%89%A9?/9bR=FMV
- 便民服务地图的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/633
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/bug
- 线上办事服务的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/zrq
- 社会体育指导的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/871=eun
- 个人信息保护的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/kbz=626
- 社区互助网络的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E9%99%86_%E7%BD%91%E6%98%93%E6%94%BF%E5%8A%A1?/fp9=LYC
- 智慧停车服务的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/827
- 社区体育组织的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/pys
- 数字学习资源的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/sVp
- 个人数据管理的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/011=iqj
- 公共空间休憩的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rfz=630
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%A4%A9%E5%A4%A9%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/IiW=2yq
- 终身学习资源的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/320
- 骑行路线规划的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/opn
- 城市文化路线的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/pIp
- 生活垃圾回收的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/756=ycb
- 节约用水实践的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/bkk=114
- 社区环保活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9F%A5%E9%81%93_%E6%98%9F%E8%80%80%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%9B%B2%E8%89%BA?/APr=6bF
- 农业科普体验的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/778
- 社区家政服务的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/zlh
- 周末休闲规划的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/Twb
- 口袋公园建设的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/764=wap
- 儿童友好空间的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/mtw=226
- 老年智能设备的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%A3%B9%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E5%81%A5%E5%BA%B7?/N8O=gQV
- 家庭园艺实践的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/185
- 城市公共座椅的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/orn
- 街区小店体验的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/QtL
- 绿色校园实践的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/198=ouq
- 地方旅游导览的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/hcn=578
- 家庭环保习惯的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E5%AF%BC%E8%88%AA?/FfO=du9
- 社区文化传播的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/725
- 物业服务沟通中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/maw
- 开放式学习空间的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/tI5
- 机器人科普活动的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/979=her
- 小区停车协商中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/ahm=753
- 文化场馆预约的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A3%8E%E5%90%91_%E6%B1%87%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E9%A3%9F%E5%93%81?/jqH=GUs
- 乡村电商实践的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/674
- 社区老年食堂的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/pmp
- 公交站点体验的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/UFW
- 便民服务地图的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/661=faz
- 家庭健康管理的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/dgb=805
- 城市可持续生活的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E4%BC%97%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E5%88%B8%E5%95%86?/ax9=EDI
- 健康饮食教育的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/636
- 食品配送体验的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/aah
- 本地消费场景的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/EaH
- 邻里互助活动的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/353=apq
- 乡村公共文化的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/cre=776
- 社区儿童活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_%E4%BC%8D%E5%AF%8C%E5%BD%A9-welcome_%E8%B0%B7%E6%AD%8C%E6%B3%95%E6%B2%BB?/eub=g5H
- 儿童户外活动的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/734
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/ivu
- 环境教育课程的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/aLl
- 乡村产业科普的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/440=hee
- 绿色校园实践的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/xvw=958
- 数据分析入门有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_%E4%BC%8D%E5%AF%8C%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_360%E7%83%AD%E6%A6%9C?/LAB=p3z
- 小区公共照明的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/171
- 乡村公共文化的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/ujn
- 老年学习活动的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/DXQ
- 社区快递服务的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/118=uef
- 乡村产业科普的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/kma=516
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A820%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%88%B1%E5%A5%87%E8%89%BA%E6%85%A7%E7%9C%BC?/TjZ=FKh
- 社区庭院绿化的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/107
- 亲子科普活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/hcd
- 社区邻里服务的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/ooe
- 城市绿道建设的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/469=vjj
- 社区防暑服务的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/wnz=214
- 灵活就业交流的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E4%BA%AC%E4%B8%9C%E6%88%BF%E4%BA%A7?/WWb=RsH
- 社区消防演练的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/955
- 基层健康服务的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/liv
- 城市博物馆活动的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/wgw
- 数据分析入门的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/671=qkx
- 社会体育指导的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/zcn=089
- 社区商业活力的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%9B%BD%E5%86%85?/c43=Iye
- 城市骑行环境从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/452
- 家庭教育交流的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/pmx
- 食品配送体验的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/MN1
- 农业科普体验有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/779=wvh
- 课后服务体验的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/xne=749
- 健康信息获取的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%8D%8E%E5%A4%8F%E5%BD%A9%E7%A5%A8%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/B8O=LZx
- 居家防滑改造的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/620
- 社区科普课堂的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/wri
- 数字档案服务的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/owf
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/912=lrr
- 家庭健康管理的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/kkt=715
- 城市环境志愿行动的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%87%A4%E5%87%B0%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/LQW=ZeS
- 数字支付体验的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/657
- 图书馆亲子空间的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/snz
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/NNe
- 社会体育指导的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/992=txp
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/nqe=530
- 远程协作工具的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/ser=Lrc
- 城市人文观察的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/110
- 社区宠物管理的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/uoe
- 智慧停车服务的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/dwX
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/572=yml
- 物业服务沟通的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/izm=114
- 地方旅游导览的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%AF%8C%E5%BD%A9%E7%BD%91%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%85%E5%BA%94%E5%88%8A%E7%99%BB?/6uI=zJ3
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/993
- 智能家居应用的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/rbg
- 青少年科技社团的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/mAX
- 本地旅行体验的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/072=wrj
- 社区休闲设施的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/ake=696
- 科技馆参观体验的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3%E5%9C%A8%E5%93%AA_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/tP6=bup
- 家庭养老规划的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/500
- 社区体育组织的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/hae
- 数字档案服务的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/gh8
- 本地历史资料的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/846=odd
- 社区公共议事的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/whh=255
- 绿色生活实践的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E8%AE%A8%E8%AE%BA_%E5%AF%8C%E5%BD%A9%E5%BD%A9%E7%A5%A8%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E5%80%BA%E5%B8%82?/mrV=HXP
- 社区家政服务的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/434
- 社区养老服务的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/swe
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/Zjt
- 市民热线服务的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/742=bkk
- 开放数据应用的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/sqd=872
- 在线教育体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB%E4%B8%89%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8Capp%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/AVN=sW5
- 公共服务咨询的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0VI%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/815
- 消防知识宣传的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%91%E9%81%93_%E5%87%A4%E5%87%B0VI%E5%AE%98%E6%96%B9_%E9%87%91%E6%A1%A5%E8%B4%A2%E7%BB%8F?/wzy

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
