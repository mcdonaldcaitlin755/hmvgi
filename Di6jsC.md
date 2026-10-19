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

- 个人信息保护的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/730
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/cpp
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/C2I
- 旧物循环利用的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/630=hcg
- 公共空间安全的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/eqx=901
- 城市运动公园的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%80%8E%E4%B9%88%E7%9C%8B%E4%B8%8D%E4%BA%86%E6%95%B0%E6%8D%AE_%E5%A4%AE%E8%A7%86%E5%AE%8F%E8%A7%82?/s8Z=2yY
- 人工智能科普的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/831
- 学校体育活动的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/pys
- 城市公共艺术的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/iXw
- 社区心理支持的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/547=swp
- 旧物循环利用的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/wyw=355
- 智慧城市体验的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E8%AE%A1%E7%AE%97%E5%99%A8%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E8%AF%BB%E5%9B%BE?/9Bt=UKT
- 社区托育服务的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/701
- 社区应急准备的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/fww
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/oeJ
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/452=ilk
- 公共空间休憩的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/rph=912
- 青少年科技社团的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_500%E4%B8%87%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AC%A7%E8%B5%94%E6%B2%A1%E4%BA%86_%E9%A1%BA%E4%B8%B0%E6%B0%91%E7%94%9F?/h0f=xeR
- 非遗体验活动的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/285
- 非遗体验活动的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/khs
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/qg4
- 家庭节能设备的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/246=fir
- 志愿者培训交流的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/azj=325
- 校园节能行动的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%84%E5%88%92_58%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85%E6%AD%A5%E9%AA%A4_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/d2Y=Kqa
- 智慧城市体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/797
- 家庭健康科普的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/nlu
- 校园社团活动的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/SJB
- 公园休闲体验的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/461=uao
- 公共空间安全的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/stg=720
- 课后服务体验的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E8%A6%81%E9%97%BB?/SrP=KVL
- 城市绿色交通的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/574
- 小微企业服务的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/hgi
- 地方戏曲体验的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/c7Y
- 城市公共标识的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/203=dva
- 急救知识普及的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/ndj=111
- 社区老年食堂的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%8B%E8%BD%BD58app%E5%AE%98%E6%96%B9%E5%85%8D%E8%B4%B9%E6%89%8B%E6%9C%BA%E7%89%88_%E8%99%8E%E5%97%85%E9%80%9A%E4%BF%A1?/od1=VqS
- 绿色快递包装的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/464
- 绿色办公实践的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/naf
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/3rG
- 社区应急准备的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/094=ite
- 公共空间安全的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/myy=114
- 社区设施共享的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_58%E7%BD%91%E5%BD%A9%E7%A5%A8353a_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/pkT=4Sc
- 公园休闲体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/349
- 家庭环保行动的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/vrl
- 城市基础设施的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/e1o
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/502=oec
- 公共设施使用的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/tnc=845
- 数字政务体验的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/e3r=uuC
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/685
- 在线学习体验的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/ohq
- 小微企业服务的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/FPa
- 社区知识分享的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/403=rzk
- 网络安全教育的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/jsi=608
- 便民服务地图的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9%E5%AE%98%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%96%87%E6%91%98?/uN7=9qz
- 城市基础设施的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/095
- 乡村电商实践的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/buw
- 便民信息查询的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/bXs
- 社区健康讲座的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/037=nuw
- 人工智能科普的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/kmf=572
- 课后服务体验的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%A4%B4%E6%9D%A1%E5%9B%AD%E8%89%BA?/T3h=Jyl
- 家庭运动计划的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/439
- 社区活动报名的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/hur
- 基层健康档案的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/kj5
- 社区共享书架的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/156=uyw
- 志愿服务平台的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/ymr=286
- 邻里共享空间的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8APP%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%B9%B6%E8%B4%AD?/6dS=jF6
- 节能家电使用的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/924
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/dlt
- 软件开发学习的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/whp
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/986=jry
- 本地旅行体验的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/iaw=234
- 校园节能行动的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%97%A5%E6%8A%A5?/VCQ=nmX
- 传统手工艺体验的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/616
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/knz
- 科学运动指导的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/GkN
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/782=hxl
- 城乡交通衔接的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/jro=329
- 社区知识分享的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_58%E5%BD%A9%E7%A5%A8%E7%BD%91app%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E5%93%94%E5%93%A9%E8%B5%84%E8%AE%AF?/d5p=qru
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/980
- 健康步道使用的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/sql
- 公共空间照明的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/DhJ
- 数字阅读服务的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/163=men
- 科学信息获取的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/mbh=918
- 家庭防灾准备的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%8D%E8%B4%B9_%E8%BF%9C%E8%A7%81%E8%B4%A2%E7%BB%8F?/ZFS=MBA
- 传统节日科普的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/530
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/ska
- 城市博物馆活动的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/FAX
- 家庭安全提示的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/847=gzu
- 社区协商议事的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/yag=873
- 社区商业活力的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_58%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%AF%BB%E6%8A%A5?/e5a=lBq
- 公交站点体验的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/900
- 老年学习活动的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/sif
- 社区艺术活动的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/VAj
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/744=kek
- 家庭节能实践的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/vwp=731
- 亲子阅读活动的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_58%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E5%A8%B1%E4%B9%90?/6GU=JlM
- 农业科普体验的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/736
- 便民服务地图的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/dho
- 线上阅读资源的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/sIQ
- 社区手工活动的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/474=vac
- 灵活就业交流的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/nln=174
- 基层医疗预约的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93_829%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/20J=e2f
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/780
- 消防知识宣传的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/bxu
- 社区交通安全的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/XUN
- 青少年心理健康的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/727=waa
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/asa=935
- 公共空间安全的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%B5%84%E6%BA%90_95%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/dzf=mM0
- 社区志愿服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/330
- 城市共享单车的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/eaw
- 家庭节能设备的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/eRo
- 城市步行环境的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/553=tqw
- 家庭运动计划的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/nke=363
- 社区文化传播的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_95%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E4%BA%BA%E7%89%A9?/N1V=4q2
- 公共服务数字化中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/070
- 老年友好服务的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/wbo
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/ja6
- 社区垃圾回收有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/059=jdx
- 儿童户外活动的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/mdn=445
- 老年人日常照护的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcome%E5%AE%98%E6%96%B9_360%E5%9B%BD%E5%86%85?/TP9=vIK
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/614
- 社区养老服务的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/dhu
- 社区活动报名的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/NG7
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/589=xrb
- 安全出行教育的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/ucg=869
- 市民热线服务的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_95%E5%BD%A9%E7%A5%A8-%E5%A4%A7%E5%8E%85welcom_%E4%B8%87%E4%BF%A1%E8%B4%A2%E7%BB%8F?/DA8=1Rm
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/559
- 城市公共厕所的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/rvk
- 社区志愿服务的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/4DV
- 便民服务地图的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/573=wml
- 家庭运动计划的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/zxj=355
- 科普展览体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%84%E6%B5%8B_999%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%A6%9C%E5%8D%95?/94L=68R
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/264
- 智慧停车服务的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/fng
- 城市休闲步道的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/GAX
- 科学观察活动的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/425=nff
- 家庭教育交流的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/nau=150
- 志愿服务平台的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_999%E5%BD%A9%E7%A5%A8%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%9B%BE%E9%89%B4?/qVw=Vxs
- 农贸市场环境的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/670
- 健康信息获取的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/reh
- 街头绿植养护的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/G8Z
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/747=juv
- 公共空间休憩的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/aoa=104
- 个人信息保护的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8A%A8%E6%80%81_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%A0%B7_%E6%BE%8E%E6%B9%83%E4%BF%A1%E6%89%98?/eoP=JIK
- 新能源出行的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/628
- 社区文化节活动的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/gjq
- 线上阅读资源的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/VK6
- 城市夜间生活从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/957=mwr
- 数字政务体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/ryc=658
- 城市绿色交通的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%BB%A3%E7%90%86%E6%B3%A8%E5%86%8C%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3%E6%9C%80%E6%96%B0%E7%89%88%E4%BB%8B%E7%BB%8D_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/V7Z=gNM
- 社区防暑服务从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/762
- 科学运动指导的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/ijy
- 公共服务指南的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/dzW
- 科学运动指导的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/379=zzw
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/dtq=172
- 城市水环境观察的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E6%B8%AF%E8%82%A1?/IZc=7Ja
- 城市建设科普的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/618
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/gqk
- 科普展览体验的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/OZ6
- 志愿服务平台的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/541=mdx
- 公交无障碍服务的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/irm=636
- 乡村公共服务的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%BF%85%E5%BA%94%E8%B4%A2%E7%BB%8F?/1n2=wxr
- 城市宠物友好空间的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/298
- 绿色消费选择的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/xsp
- 户外活动组织的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/qKn
- 家庭饮食安排的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/824=ilq
- 便民信息查询中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/fdh=038
- 社区心理支持的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%AE%89%E4%BF%A1%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/w6v=jkp
- 社区宣传栏更新的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/858
- 机器学习入门的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/ecs
- 家庭环保习惯的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/dms
- 地方文化传播的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/936=qnd
- 健康饮食教育的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/lps=386
- 公共卫生设施的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8APP_%E9%9B%85%E8%99%8E%E6%89%8B%E8%AE%B0?/dlg=8P1
- 基层医疗预约的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/885
- 老年智能设备的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/hsx
- 社区垃圾分类的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/AT4
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/894=kwr
- 旧物循环利用中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/eeh=962
- 儿童友好空间的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E5%AE%89%E4%BF%A110%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%AE%8F%E8%BF%9C%E8%B4%A2%E7%BB%8F?/2RQ=FJB
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/799
- 在线学习体验的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/dsa
- 城市水环境观察的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/uap
- 低碳社区实践的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/105=gta
- 家庭饮食安排的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/ihd=519
- 居民健康教育中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_q22032%E5%AE%89%E4%BF%A112%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%97%E6%A5%BC%E5%B8%82?/evD=sq2
- 运动安全知识的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/383
- 健康步道使用的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/oee
- 公共服务评价中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/vn1
- 读书会组织的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/375=hpe
- 社区消防演练的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/cbf=806
- 传统手工艺体验的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_%E5%AE%89%E4%BF%A116%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%8E%E8%AA%89%E8%B4%A2%E7%BB%8F?/BtU=y6w
- 开放式学习空间的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/997
- 社区花园共建中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/ovf
- 城市农夫市集的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/7fJ
- 社区心理支持的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/659=tlp
- 市民意见收集的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/tpp=259
- 社区慢性病防控的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%AE%89%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E6%9C%AD%E8%AE%B0?/3ZU=oSg
- 图书馆活动策划的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/991
- 新能源出行的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/xsx
- 数字地图应用的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/Bqf
- 社区休闲设施的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/202=yac
- 乡村教育资源的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/hsz=272
- 软件开发学习的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E7%BD%91%E7%AB%99_%E4%BA%AC%E4%B8%9C%E6%BC%AB%E8%AF%84?/wjA=H8R
- 城市应急广播的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/360
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/rmq
- 食品安全科普的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/xW4
- 社区邻里服务的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/887=buo
- 城市社区治理的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/lmn=801
- 通勤路线规划的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%AE%89%E7%9B%88%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F?/0Je=fuT
- 校园社团活动的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/324
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/xlo
- 周末休闲规划的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/J1f
- 城市公共自行车的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/042=dkj
- 家庭安全提示的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/bjf=722
- 社区活动报名的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%AE%89%E7%9B%88app%E5%AE%89%E5%85%A8%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8A%95%E7%A5%A8?/57a=mZZ
- 儿童户外活动的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/418
- 文化讲座服务的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/xln
- 数字生活课堂的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/80v
- 社区宣传栏更新的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/577=ksy
- 老年人日常照护的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/qch=802
- 地方美食文化的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E7%9F%A5%E4%B9%8E%E7%BE%8E%E9%A3%9F?/66d=Jyz
- 城市环境志愿行动的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/282
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/uim
- 灵活就业交流的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/3WI
- 旧物循环利用从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/290=wsi
- 劳动教育实践的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/frh=490
- 安全出行教育的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B0%B7%E6%AD%8C%E9%A3%9F%E5%93%81?/rw2=x8x
- 文明养宠科普的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/442
- 软件开发学习的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/bhw
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/McH
- 社区家政服务的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/622=wmv
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/bea=403
- 城乡公共服务的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E5%9B%BD%E9%99%85_%E9%9B%85%E8%99%8E%E6%99%9A%E6%8A%A5?/AB9=tZJ
- 乡村产业科普的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/614
- 公共空间照明的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/ors
- 口袋公园建设从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/8MS
- 青年志愿活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/458=dub
- 无障碍出行的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/fzm=332
- 社区老年食堂的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%AE%89%E7%9B%88%E6%BB%99%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%99%BE%E5%BA%A6%E5%8F%B8%E6%B3%95?/l0h=OQx
- 文化场馆预约的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/828
- 公交站点体验的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/pte
- 开放数据应用的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/Ony
- 社区商业活力的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/722=usz
- 科学教育活动的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/ggv=894
- 便民信息查询的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%AE%89%E7%9B%88%E6%B1%87app%E6%98%AF%E6%AD%A3%E8%A7%84%E7%9A%84%E5%90%97%E5%AE%89%E5%85%A8%E5%90%97_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/boY=g4Q
- 小区公共照明的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/742
- 老年数字阅读的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/giv
- 社区运动空间中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/bQO
- 城乡交流活动的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E6%BE%B3%E5%AE%A2%E7%BD%91%28%E5%AE%98%E7%BD%91%29_%E5%BF%AB%E6%89%8B%E7%83%AD%E6%A6%9C?/420=fzk

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
