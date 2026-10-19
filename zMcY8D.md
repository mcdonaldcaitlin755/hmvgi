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

- 城市住房服务的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/9cv
- 社区慢性病防控的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/784=hwv
- 全民健身活动的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/sdy=489
- 公园休闲体验的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%8628%E6%9D%80%E7%BB%84%E5%90%88%E9%A2%84%E6%B5%8B_%E5%A4%A9%E9%99%85%E8%B4%A2%E7%BB%8F?/MkE=0HF
- 开源技术交流的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/100
- 网络安全教育中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/okb
- 社区老年食堂的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/J4p
- 城市可持续生活的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/389=irw
- 街道综合服务的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/sfb=787
- 老年数字阅读的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%8628-2.8%E9%A2%84%E6%B5%8BC7_%E7%BD%91%E6%98%93%E7%BE%8E%E9%A3%9F?/kgg=4i0
- 社区文化节活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/643
- 光伏知识科普的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/ytu
- 家庭陪伴活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/7H8
- 家庭饮食安排中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/810=fte
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/cif=505
- 小区公共照明的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E5%88%86%E5%88%8628%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E9%97%AE%E5%8D%B7?/fMv=Car
- 公共服务评价的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/382
- 儿童友好空间的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/icw
- 家庭饮食安排的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/xa2
- 社区活动策划的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/512=ofs
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/fxh=770
- 绿色消费选择的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_28%E5%88%86%E6%88%90%E6%80%8E%E4%B9%88%E7%AE%97_%E7%8E%B0%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Why=8Aq
- 社区生活指南的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/695
- 公共设施维护的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/ksr
- 小区停车协商的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/3DW
- 社区家政服务的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/656=lff
- 社区科普课堂的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/jzc=669
- 家庭节能实践的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pg28%E5%A8%B1%E4%B9%90%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/anJ=wch
- 急救知识普及的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/620
- 社区协商议事的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/tyq
- 城市骑行环境的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/DE0
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/374=dfw
- 数字政务体验的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/wjm=381
- 节能家电使用的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A72.8%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%88%86%E5%88%86_%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/dwM=Cc8
- 农村环境治理的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/509
- 城市文化路线的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/mrv
- 街区更新实践的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/um7
- 邻里互助活动的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/991=gsd
- 个人时间管理中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/vlq=637
- 社区邻里服务的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%88%86%E5%88%86%E5%88%8628%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E8%B5%84%E8%AE%AF?/1Ku=VbR
- 社区文化节活动的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/628
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/hsp
- 社区手工活动的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/nq9
- 基层健康服务的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/059=gdr
- 儿童户外活动的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/zxi=579
- 科学运动指导的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_PC28%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%88%B7%E5%A4%96?/Aob=WeV
- 开放数据应用的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/705
- 绿色办公实践的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/uvp
- 城市社区治理从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/kTe
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/280=wlc
- 科学教育活动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/tei=191
- 生成式工具使用的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E8%AE%A1%E5%88%92%E7%BD%91%E9%A1%B5%E7%89%88%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A5%BC%E5%B8%82?/DoQ=Aiv
- 城市适老服务的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/673
- 个人时间管理的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/xrb
- 生活服务数字化从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/25V
- 社区公共议事的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/963=zuz
- 社区教育资源的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/xco=251
- 青少年科技社团的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_pc28%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%A6%81%E9%97%BB?/M0b=RpN
- 市民意见收集的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/533
- 亲子阅读活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/uqi
- 社区家政服务的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/ums
- 智慧停车服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/432=rrv
- 城市生活服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/ioo=776
- 社区防暑服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_pc28%E6%8A%80%E5%B7%A7%E7%A0%94%E7%A9%B6_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/WkX=2re
- 校园节能行动中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/296
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/duh
- 基层健康档案的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/08d
- 校园节能行动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/546=xkf
- 老年友好服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/hvj=050
- 城市空气科普的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pc28%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E7%BB%8F%E6%B5%8E?/hLA=rOb
- 家庭用电安全的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/562
- 青年志愿活动的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/zur
- 机器学习入门的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/0RV
- 儿童安全出行的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/300=alg
- 科学睡眠习惯的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/xrl=522
- 校园社团活动的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E8%AF%86_pc28%E6%8A%80%E5%B7%A7%E5%92%8C%E5%BF%83%E5%BE%97_%E9%9B%85%E8%99%8E%E8%B4%A2%E6%8A%A5?/cpc=umN
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/572
- 市民热线服务的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/ivt
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/04i
- 地方美食文化的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/181=yfv
- 校园阅读活动的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/sbe=165
- 在线学习体验的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pc28%E6%8A%80%E5%B7%A7%E8%BD%AF%E4%BB%B6_%E4%BC%98%E9%85%B7%E8%AE%BF%E8%B0%88?/DIV=1nZ
- 软件开发学习的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/569
- 传统节日科普的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/ojt
- 城市水环境观察的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/ntR
- 社区交通安全的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/094=dun
- 药品使用科普的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/dhb=515
- 无障碍出行的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%BF%E4%BA%A7?/dI4=61W
- 城市休闲步道的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/599
- 老年运动活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/gfk
- 在线学习体验的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/U65
- 科学健身方法的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/194=mej
- 灵活就业交流的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/yqo=259
- 老年友好服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_pc28%E8%A7%84%E5%88%99%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/XzA=NVK
- 社区体育组织的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/216
- 城市体育设施的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/aap
- 社区便民集市的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/pxT
- 青少年编程学习的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/035=ifv
- 社区便利生活的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/bpi=737
- 城乡公共服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8F%91%E5%B8%83_pc28%E8%A7%84%E5%88%99%E4%BB%8B%E7%BB%8D_360%E5%81%A5%E8%BA%AB?/Qtm=4ZC
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/852
- 城市公共空间的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/dkp
- 社区活动策划的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/M68
- 社区花园共建的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/166=bwf
- 乡村阅读空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/ixi=916
- 乡村阅读活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_28%E5%BD%A9%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E4%BA%A7?/cRC=eSX
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/162
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/jck
- 智慧城市体验的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/UAh
- 乡村公共服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/095=jcq
- 城市骑行环境的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/agq=985
- 城市慢行系统的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_PC%E8%AE%A1%E5%88%92_%E8%B4%A2%E7%BB%8F%E5%85%AC%E7%9B%8A?/HV5=1bn
- 城市空气科普的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/431
- 城市适老服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/yct
- 数字创意课程的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/Nax
- 街区绿化养护的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/578=ncn
- 图书借阅体验的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/roh=677
- 乡村文化活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_pc%E8%9B%8B%E8%9B%8B28%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%A8%B1%E4%B9%90?/1t4=y3U
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/182
- 在线学习体验的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/iic
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/zBF
- 个人数据管理的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/606=bvw
- 绿色出行服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/zgq=298
- 基层医疗预约的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E8%BD%AF%E4%BB%B6_%E8%B4%A2%E7%BB%8F%E9%80%9F%E9%80%92?/Dbx=Wys
- 农村环境治理的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/863
- 城市运动公园的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/lbl
- 城市文明出行的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/H1H
- 青少年科技社团的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/046=qre
- 节能生活方式的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/iqw=819
- 开源技术交流的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%85%A8%E5%A4%A9%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%28%E5%85%8D%E8%B4%B9%E7%89%88%29_%E6%96%B0%E6%B5%AA%E5%AE%A0%E7%89%A9?/sJh=8WK
- 青少年心理健康的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/989
- 数字地图应用的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/znh
- 社区运动空间的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/Ta7
- 公共设施维护的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/569=ipa
- 智能手机助老的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/awt=753
- 城市步行环境的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E4%B8%93%E4%B8%9A%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/eSo=ZaC
- 家庭安全提示的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/058
- 数字地图应用的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/rpf
- 社区健康讲座的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/1Id
- 数字政务体验的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/692=blr
- 健康步道使用的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/zvb=907
- 社区环保活动的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%97%B6%E8%AE%AF?/cbE=7Sr
- 家庭收纳实践的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/186
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/gwr
- 社区心理支持的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/VlX
- 公共空间休憩的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/563=zdy
- 社区安全巡查的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/tel=756
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%9028%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E5%AE%89%E8%A3%85%E6%96%B9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%97%B6%E5%B0%9A?/uSi=Npb
- 社区家政服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/454
- 本地历史资料的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/cya
- 乡村阅读空间的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/Cao
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/862=ziv
- 个人数据管理的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/tjo=073
- 城市展览体验的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E6%89%93%E6%B3%95%E8%AE%A1%E5%88%92_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/XIu=vv2
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/754
- 音乐欣赏活动的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/pje
- 乡村公共服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/v4y
- 应急物资管理的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/915=ruz
- 青少年心理健康的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/fnl=676
- 家庭用电安全的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_%E5%B9%B8%E8%BF%9028%E6%9C%80%E7%89%9B%E8%AE%A1%E5%88%92%E7%BE%A4_36%E6%B0%AA%E6%9B%B2%E8%89%BA?/6IU=miD
- 乡村生活观察的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/700
- 数字学习资源的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/pqe
- 应急物资管理的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/q29
- 社区健康讲座的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/156=vrc
- 校园阅读活动的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/mln=778
- 城市骑行环境的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%B9%B8%E8%BF%9028%E6%96%B9%E6%A1%88%E9%A2%84%E6%B5%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%B0%E9%97%BB?/Zxt=mYN
- 家庭理财科普的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/550
- 无障碍出行的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/gbe
- 绿色办公实践的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/57z
- 志愿者培训交流的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/806=rwh
- 公益活动组织的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/cyi=452
- 城市体育设施的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E5%85%A8%E5%A4%A9%E6%8A%80%E5%B7%A7_%E6%B9%BE%E5%8C%BA%E8%B4%A2%E7%BB%8F?/2ds=tP8
- 新能源出行的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/292
- 城市噪声观察的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/jfu
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/8er
- 老年友好服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/956=noz
- 城市文化路线的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/lvw=750
- 社区设施共享的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%A2%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E8%AE%A1%E7%AE%97_%E5%BF%85%E5%BA%94%E5%9F%8E%E4%BA%8B?/oDs=ZFh
- 全民阅读推广的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/426
- 消防知识宣传的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/zkx
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/pCS
- 城乡交通衔接的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/990=zdv
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/ewo=313
- 绿色消费选择的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%9028%E6%8A%80%E5%B7%A7%E8%AF%B4%E6%98%8E__%E4%BA%AC%E4%B8%9C%E6%97%A5%E6%8A%A5?/MoO=kCh
- 家庭照护支持的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/013
- 城市文明出行的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/brz
- 节能家电使用的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/AZE
- 青少年户外教育的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/428=gof
- 公共空间休憩的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/jbj=073
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%9028%E7%AD%96%E7%95%A5_%E6%96%B0%E6%B5%AA%E8%81%8C%E5%9C%BA?/fLP=Ntp
- 社区防暑服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/193
- 社区活动空间的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/olt
- 邻里共享空间的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/8tj
- 社区活动策划的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/266=grm
- 本地消费场景的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/eku=656
- 绿色出行服务的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%9028%E7%A8%B3%E8%B5%9A%E5%BF%83%E5%BE%97__%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BD%E9%99%85?/Dad=8JZ
- 全民健身活动的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/528
- 街道综合服务的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/hbp
- 节能生活方式的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/Oi3
- 家庭理财科普的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/926=ngk
- 灵活就业交流的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/kty=276
- 校园节能行动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%9028%E9%A2%84%E6%B5%8B%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E5%88%8A%E7%99%BB?/MXg=gAF
- 城市体育设施的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/708
- 个人信息保护的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/hvc
- 图书借阅体验的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/r9Y
- 社区休闲设施的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/111=nao
- 儿童阅读角的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/wun=337
- 医院导诊服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%9028%E7%B2%BE%E5%87%86100%25%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B0%91%E7%94%9F?/s4o=73H
- 灵活就业交流的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/660
- 社区公共议事的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/whx
- 城市骑行环境中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/NbQ
- 全民健身活动的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/846=kxq
- 基层健康服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/wvw=986
- 城乡交流活动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%9028%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_360%E6%97%85%E6%B8%B8?/xY8=HEP
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/749
- 线上办事服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/exl
- 家庭环保行动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/Jcu
- 公共交通信息服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/094=zkt
- 青少年心理健康的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/eqr=336
- 本地消费场景的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%B4%A2%E7%BB%8F_pc28%E7%8E%A9%E6%B3%95%E5%80%8D%E7%8E%87%E8%A1%A8_360%E8%B4%A2%E7%BB%8F?/3zk=YPR
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/082
- 青少年户外教育的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/kqt
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/EfV
- 社区家校合作的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/983=ama
- 青少年科技社团的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/zos=556
- 社区环保活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_PC%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92_%E9%A1%BA%E4%B8%B0%E6%8A%95%E7%A8%BF?/YGt=WoT
- 城市生活记录的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/433
- 社区垃圾分类的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rjo
- 社区垃圾分类的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/WhO
- 城市农夫市集的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/488=xao
- 居家适老化改造中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/dqs=719
- 文化遗产保护科普的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pc%E8%9B%8B%E8%9B%8B%E5%85%AC%E5%BC%8F_%E9%93%B6%E6%B3%B0%E8%B4%A2%E7%BB%8F?/2Uq=e4k
- 社区儿童活动的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/114
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/hdo
- 创业经验分享的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/miO
- 节假日出行安排的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/632=vju
- 城市博物馆活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/xqn=294
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_pc%E8%9B%8B%E8%9B%8B%E6%9C%80%E5%87%86%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%84%89%E8%84%89%E9%94%90%E8%AF%84?/Bry=ERk
- 社区家政服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/552
- 网络信息辨识的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/xpl
- 远程协作工具的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/18R
- 社区儿童活动的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/458=tbh
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/enk=564
- 市民热线服务的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%B4%A2%E7%BB%8F_pc%E8%9B%8B%E8%9B%8B%E5%AE%98%E6%96%B9%E8%AE%A1%E5%88%92%E7%BE%A4%E5%90%A7_%E8%84%89%E8%84%89%E6%97%B6%E8%AF%84?/jqV=yuj
- 健康饮食教育的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/980
- 家庭消费规划的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/xhu
- 便民服务地图的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/H7R
- 邻里共享空间的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/095=mhb
- 生活垃圾减量的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/okq=077
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E4%BA%86%E8%A7%A3_pc%E8%9B%8B%E8%9B%8B%E8%AE%A1%E5%88%92%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%BD%A9%E7%A5%A8?/GUo=8l4

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
