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

- 社区互助网络的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/453
- 数字便民地图的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/pgh
- 社区公共卫生的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/scf
- 街区道路维护的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/491=hay
- 社区活动空间的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/oom=322
- 传统节日科普的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%AF%B9%E5%88%B7%E7%AE%97%E6%B3%95_%E8%B4%A2%E7%BB%8F%E6%85%A7%E7%9C%BC?/G14=mEg
- 社区托育服务的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/849
- 老年学习活动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/lqd
- 城市应急科普的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/OAk
- 科学健身方法的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/241=nqg
- 市民意见收集的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/inw=891
- 城乡公共服务的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%A4%A7%E5%B0%8F%E5%AF%B9%E5%88%B7%E5%A5%97%E5%88%A9%E6%96%B9%E6%B3%95_%E7%9F%A5%E4%B9%8E%E7%9B%B4%E6%92%AD?/MQy=LC5
- 旧物循环利用的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/260
- 家庭网络使用的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/sph
- 社区宠物管理的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/nv0
- 邻里共享空间的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/455=ugp
- 数字支付体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/kxy=548
- 地方旅游导览从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E8%B7%9F%E6%B3%95_360%E5%8D%83%E5%B8%86?/xwF=Hw1
- 志愿服务平台的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/260
- 社区健康讲座的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/ekw
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/jcz
- 科学观察活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/186=gwh
- 户外活动组织的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/naw=839
- 便民信息查询的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC3%2C4%2C18%2C19%E6%80%8E%E4%B9%88%E8%AE%A1%E7%AE%97_%E7%99%BE%E5%BA%A6%E6%8E%A2%E5%BA%97?/78U=tsm
- 社区老年食堂的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/243
- 数字艺术创作的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/lfe
- 线上阅读资源的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/5a5
- 邻里共享空间的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/652=rom
- 旧物循环利用的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/smv=314
- 在线学习体验的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%B0%8F%E5%8D%9518%E5%A5%97%E5%88%A9_%E7%95%8C%E9%9D%A2%E5%AE%B6%E7%94%B5?/xBi=wla
- 街区道路维护的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/340
- 健康饮水科普的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/cme
- 信息无障碍体验的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/B7q
- 青少年科技社团的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/652=ppx
- 消防知识宣传的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/tyf=172
- 农产品品牌传播的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%BC%8011%E7%AE%97%E6%89%93%E5%92%8C%E8%83%BD%E5%88%B7%E5%90%97_%E6%8A%96%E9%9F%B3%E6%9C%9F%E8%B4%A7?/elQ=XiT
- 亲子阅读活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/545
- 社区志愿服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/fqv
- 公共服务咨询的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/h9o
- 家庭网络使用的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/814=emr
- 城市步行友好的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/yfn=129
- 节约用水实践的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E5%80%BC%E5%A4%A7%E6%A6%82%E7%8E%87%E5%A4%9A%E5%B0%91_%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F?/VOc=eCx
- 地方戏曲体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/459
- 城市公共艺术的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/ltz
- 城市社区治理的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/B93
- 公共服务评价的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/547=rho
- 城市骑行环境的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/gve=858
- 社区绿色空间的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E5%86%A0%E4%BA%9A%E5%92%8C11%E7%AE%97%E5%B0%8F_%E7%95%8C%E9%9D%A2%E7%9B%B4%E6%92%AD?/jPR=qJH
- 儿童运动体验的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/589
- 乡村文化空间的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/rno
- 社区家政服务的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/8V7
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/794=hza
- 公共设施使用的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/bji=796
- 急救知识普及的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%81%9A%E7%84%A6_pk10%E5%86%A0%E4%BA%9A%E5%92%8C%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E6%AF%8F%E6%97%A5%E8%B4%A2%E7%BB%8F?/G1Q=akc
- 儿童友好空间的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/187
- 数字素养提升的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/idg
- 城乡公共服务的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/xsA
- 社区休闲设施的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/157=opx
- 社区托育服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/fwz=589
- 科学睡眠习惯的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%82%E5%AF%9F_pk10%E5%86%A0%E4%BA%9A%E7%BB%84%E5%90%88%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%84%89%E8%84%89%E8%A6%81%E9%97%BB?/qTh=6GC
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/343
- 社区生活指南的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/jjp
- 老年人出行服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/oR5
- 城市社区治理的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/599=rvz
- 城乡交流活动的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/ajz=315
- 社区文化节活动的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905_%E7%88%B1%E5%A5%87%E8%89%BA%E7%99%BE%E7%A7%91?/Iyo=IXZ
- 社区垃圾分类的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/543
- 社区故事采集的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/cal
- 社区垃圾回收的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/TmO
- 城市文化路线的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/827=exq
- 城乡公共服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/liq=734
- 城市步行环境的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/3Tp=lgV
- 基层服务创新的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/570
- 农贸市场环境的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/rff
- 社区志愿服务的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/JSD
- 农业科普体验的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/351=hnf
- 城市基础设施的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/jyo=522
- 家庭志愿活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E9%9B%85%E8%99%8E%E5%8D%9A%E5%AE%A2?/7cW=lDi
- 家庭防灾准备的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/374
- 便民维修服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/mrc
- 城市体育设施的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/zcp
- 音乐欣赏活动的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/608=xpy
- 城乡交通衔接的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/ylw=901
- 租房信息服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/DuG=gqp
- 家庭节能设备的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/695
- 老年运动活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/wkb
- 城市公共艺术的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/ZVS
- 市民意见收集的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/964=ewu
- 城市公共饮水的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/rln=078
- 公益活动组织的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E8%AE%A1%E5%88%92%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E5%B9%B6%E8%B4%AD?/Soq=qzn
- 公共空间休憩从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/403
- 骑行路线规划的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/vyj
- 城市应急广播的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/UHB
- 公共卫生设施从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/579=pqd
- 绿色办公实践的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/txt=642
- 社区休闲设施的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_%E5%8D%B3%E5%88%BB%E5%BD%B1%E8%A7%86?/VOG=158
- 社区读书角建设的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/393
- 电子商务服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/nij
- 城市适老服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/POO
- 农村环境治理的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/328=mzj
- 城市夜间生活的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/zpr=235
- 居家防滑改造中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%99%BE%E5%88%86%E7%99%BE_%E8%B0%B7%E6%AD%8C%E6%99%9A%E6%8A%A5?/kTE=1kp
- 城市人文观察的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/703
- 数字档案服务的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/fls
- 城市公共艺术的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/ROt
- 创业经验分享的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/862=gqu
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/msj=210
- 机器学习入门的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_%E5%AE%8F%E5%AF%8C%E8%B4%A2%E7%BB%8F?/7on=JdS
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/139
- 城市慢行系统从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/ejn
- 地方美食文化的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/eoY
- 城市公共艺术的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/980=rwg
- 安全出行教育的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/ygf=671
- 社区商业活力的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%AD%E5%A5%96_%E8%84%89%E8%84%89%E6%AF%8D%E5%A9%B4?/JEg=sAI
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/463
- 传统节日科普的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/wal
- 科技馆参观体验的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/o3R
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/388=vbn
- 课后服务体验的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/uig=821
- 亲子科普活动的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%E5%BD%A9%E7%A7%8D_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/cBW=t6f
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/500
- 乡村公共服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/vho
- 社区手工活动的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/ycX
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/030=vie
- 公共设施使用的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/yqc=288
- 家庭健康科普的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E8%85%BE%E8%AE%AF%E5%85%9A%E5%BB%BA?/avj=4Bk
- 急救知识普及的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/489
- 亲子阅读活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/qsr
- 便民信息查询的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/YxC
- 城市地名文化的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/736=bdw
- 家庭节能实践的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/srg=446
- 数字资源检索的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E9%83%BD%E5%B8%82%E8%B4%A2%E7%BB%8F?/4uC=3Hl
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/096
- 本地历史资料的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/kny
- 社区消防演练的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/ckZ
- 本地旅行体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/285=ndt
- 青年志愿活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/cee=596
- 社区环保活动的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E7%BE%8E%E5%A6%86?/ST0=T7A
- 城市建设科普的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/071
- 公共场所导视的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/vph
- 便民信息查询中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/wyJ
- 机器人科普活动的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/031=cwe
- 公共场所导视的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/kqy=276
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E7%BD%91_%E7%95%8C%E9%9D%A2%E7%BB%BC%E8%89%BA?/LPk=VAg
- 健康信息获取的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/786
- 公共服务沟通的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/skp
- 社区便民服务的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/Yra
- 社区环保活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/879=pbj
- 城市雨天出行的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/cni=511
- 社区教育资源的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E7%A0%81%E8%AE%A1%E5%88%92_36%E6%B0%AA%E6%BC%AB%E8%AF%84?/P7Z=mx7
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/876
- 新能源出行的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/oat
- 城市公共饮水的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/9F6
- 居民健康教育的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/292=hod
- 在线教育体验的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/xnp=791
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E5%8E%86%E5%8F%B2_36%E6%B0%AA%E6%8E%A2%E5%BA%97?/ujx=lcL
- 城市噪声观察的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/005
- 社区垃圾回收的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/qrd
- 无障碍出行的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/XWO
- 城市树木认养的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/056=nnn
- 科普展览体验的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/opm=481
- 传统手工艺体验的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E9%81%93_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%95%AA%E6%91%8A1234%E5%88%86%E6%9E%90%E4%BB%AA_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/hyE=7e9
- 公交站点体验的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/854
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/uwp
- 城市住房服务的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/XZv
- 数字生活课堂的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/055=lmu
- 科技馆参观体验的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/sds=637
- 公共场所导视的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E4%BD%93%E5%BD%A9%E5%AE%98%E7%BD%91_%E8%99%8E%E5%97%85%E4%BA%B2%E5%AD%90?/A53=9YM
- 社区阅读服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/753
- 社区托育服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/cjl
- 乡村教育资源的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/tXT
- 城市可持续生活的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/374=wpf
- 公共空间安全的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/ivv=428
- 城市公共艺术的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97%E3%80%82_360%E6%99%9A%E6%8A%A5?/GBQ=WrE
- 智慧城市体验的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/408
- 城市公共标识的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/hqm
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/VYS
- 公园亲子设施的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/746=cin
- 社区生活指南的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/vcd=529
- 农贸市场环境的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E6%95%B0%E6%8D%AE%E7%BD%91_%E6%90%9C%E7%8B%90%E6%96%B0%E9%97%BB?/0KF=T6a
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/323
- 新能源知识普及的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/dtd
- 公园休闲体验有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/uhx
- 乡村教育资源的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/830=ivp
- 网络安全教育的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/mel=711
- 智慧停车服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9_%E5%8D%B3%E5%88%BB%E6%8E%A2%E6%BA%90?/pOV=au8
- 绿色消费选择的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/560
- 校园社团活动的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/lff
- 儿童安全出行的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/VlF
- 城市环境志愿行动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/275=akz
- 绿色校园实践中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/wof=529
- 公共场所导视的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_168%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E7%BD%91%E7%BB%93%E6%9E%9C%E8%AE%B0%E5%BD%95%E4%BD%93%E5%BD%A9-%E5%BC%80%E5%A5%96%E7%BB%93_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/0Jd=awk
- 新能源出行的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/038
- 城市骑行环境的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/zrl
- 文明养宠科普的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/J0m
- 家庭节能实践中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/421=mjt
- 社区交通安全的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/eeu=623
- 数字素养提升的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96%E5%8F%B7%E7%A0%81%E6%9F%A5%E8%AF%A2_%E6%99%BA%E6%85%A7%E8%B4%A2%E7%BB%8F?/sET=Rtq
- 农产品品牌传播的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/712
- 数字艺术创作的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/paz
- 社区防暑服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/tII
- 科学睡眠习惯的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/286=epu
- 灵活就业交流的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/pyk=683
- 家庭网络使用的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_168%E7%BD%91%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908_%E5%90%8C%E7%9B%9B%E8%B4%A2%E7%BB%8F?/eqY=Lsw
- 社区志愿服务的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/441
- 社会体育指导的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/pzr
- 乡村阅读空间的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/lGy
- 家庭陪伴活动的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/522=kxc
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/hra=806
- 健康步道使用的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E7%B2%BE%E5%87%86100%25%E5%85%8D%E8%B4%B9%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BA%B2%E5%AD%90?/dO2=RC2
- 绿色校园实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/707
- 城市树木认养的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/ayf
- 乡村阅读活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/PVw
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/965=ayi
- 街头绿植养护的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/ssq=620
- 家庭志愿活动的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%905%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E7%BD%91-168%E5%B9%B8%E8%BF%90_%E6%90%9C%E7%8B%90%E8%B5%84%E8%AE%AF?/gjB=KUD
- 社区共享书架的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/227
- 劳动教育实践的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/qpi
- 街头绿植养护的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/m1L
- 城市骑行环境的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/037=lhe
- 家庭环保行动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/cwj=072
- 农产品品牌传播从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%908%E5%BC%80%E5%A5%96_%E6%8A%96%E9%9F%B3%E6%8E%A2%E5%BA%97?/tUN=kpl
- 市民意见收集的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/126
- 社区文化节活动的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/ilj
- 数字创作工具的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/MKi
- 社区休闲设施的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/741=ffr
- 人工智能科普的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/cak=067
- 城市噪声观察的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_%E5%B9%B8%E8%BF%90168%E5%AE%98%E6%96%B9%E9%A3%9E%E8%89%87%E7%BB%93%E6%9E%9C%E4%BD%93%E5%BD%A9%E6%9F%A5%E8%AF%A2%E7%BD%91%E5%8E%86%E5%8F%B2_%E8%8A%92%E6%9E%9C%E8%83%BD%E6%BA%90?/Jge=mR0
- 儿童友好街区的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/165
- 开放式学习空间的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/wmm
- 绿色消费选择的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/feb
- 户外活动组织的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/733=crn
- 城市适老服务的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/gjl=248
- 社区读书角建设的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%908%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E4%BC%97%E6%B5%8B?/hJq=Uxy
- 城市文明实践的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/263
- 科学观察活动的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/kyz
- 社区共享书架的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/dGy
- 公共场所导视的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/065=gew
- 公共服务数字化从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/npr=815
- 灵活就业交流的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%9F%E8%B4%A7?/c3F=N4L
- 青少年编程学习的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/644
- 老年友好服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/pyk
- 节日文化体验的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/JKi
- 街头绿植养护的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/213=hns
- 远程协作工具的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/enf=966
- 家庭急救准备的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_168%E6%BE%B3%E6%B4%B210%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91%E5%BC%80%E5%A5%96%E7%9B%B4%E6%92%AD_%E6%90%9C%E7%8B%90%E5%AE%A0%E7%89%A9?/1BL=k8U
- 城市应急科普的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/501
- 社区商业活力的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/ogv
- 骑行路线规划的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/f0Z
- 老年智能设备的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E6%BE%B3%E6%B4%B2%E5%B9%B8%E8%BF%9010%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E5%87%A4%E5%87%B0%E5%85%AC%E7%9B%8A?/355=ptl

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
