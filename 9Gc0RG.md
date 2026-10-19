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

- 城市生活服务的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/AB0
- 家庭阅读计划的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/466=ber
- 老旧小区改造的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yqg=300
- 老年数字阅读的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8app_%E5%9B%BD%E4%BF%A1%E8%B4%A2%E7%BB%8F?/B4x=4wZ
- 街道综合服务的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/687
- 社区家政服务中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/mef
- 城市绿道建设的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/A2J
- 城市绿色交通的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/467=wph
- 校园安全教育的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/suz=578
- 户外活动组织的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898%E5%BD%A9%E7%A5%A8%E5%90%88%E6%B3%95%E4%B9%88_%E8%BE%93%E7%9A%84%E9%92%B1%E8%83%BD%E8%BF%BD%E5%9B%9E%E6%9D%A5%E5%90%97_360%E6%A1%A3%E6%A1%88?/eqH=Hvs
- 通勤路线规划的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/555
- 无障碍出行的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/uji
- 城市空气科普的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/r1K
- 开放数据应用的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/583=yly
- 公交站点体验的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/xym=766
- 居家适老化改造的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E4%BA%898_%E8%B1%86%E7%93%A3%E7%A4%BE%E8%AE%BA?/wBT=ZpA
- 城市地名文化的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/246
- 城市公共空间的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/rxn
- 全民阅读推广的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/L86
- 青少年编程学习的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/951=jlh
- 社区宠物管理的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/pjo=018
- 公园亲子设施的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8F%91%E4%BA%91%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%85%E5%BA%94%E8%A7%82%E7%82%B9?/NLL=DTT
- 社区法律科普的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/118
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/bir
- 智慧停车服务的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/TLh
- 公共服务沟通的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/250=wzq
- 城市公共座椅的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/aih=335
- 网络信息辨识的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%89%8D%E7%9E%BB_%E5%AE%8F%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%A4%BE%E8%AE%BA?/Eo6=JWq
- 小微企业服务的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/663
- 居家适老化改造的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/dcn
- 城市慢行系统的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/NRx
- 城市应急科普的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/290=hvs
- 日常摄影记录的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/brc=384
- 小微企业服务的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BA%AA%E5%AE%9E?/FwJ=TIt
- 数字素养提升的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/505
- 旧物循环利用的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/kms
- 城市文化路线的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/hRf
- 公共服务数字化的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/170=wbp
- 公共健身器材的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/akp=015
- 社会体育指导的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%9B%BE%E9%89%B4?/AH5=ywS
- 节假日出行安排的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/590
- 生活垃圾回收的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/ynk
- 公共卫生设施的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/IRM
- 户外活动组织的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/974=uql
- 绿色消费选择的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/jyi=224
- 青年志愿活动的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E8%AE%A1%E5%88%92_%E5%A4%B4%E6%9D%A1%E6%97%A5%E6%8A%A5?/qjT=zre
- 职业技能学习的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/824
- 人工智能科普的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/qxf
- 社区文化节活动的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/hm7
- 公共健身器材的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/229=bnx
- 公共服务咨询的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/qrb=517
- 线上阅读资源的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E6%97%A7%E7%89%88_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/da6=zvf
- 文明养宠科普的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/180
- 节能生活方式的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/pfc
- 音乐欣赏活动的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/RTn
- 节气饮食文化的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/585=zua
- 乡村生态观察的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/dfs=621
- 城市公共饮水的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85we_%E8%85%BE%E8%AE%AF%E9%94%90%E8%AF%84?/yOi=R77
- 医院导诊服务的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/099
- 安全出行教育的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/pgc
- 儿童安全出行有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/Cyh
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/635=kqo
- 社区老年食堂的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/wkg=177
- 乡村阅读活动的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85welcome_%E5%A4%AE%E8%A7%86%E6%B3%95%E5%BE%8B?/Pfx=gHn
- 光伏知识科普的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/603
- 社区菜市场服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/xeh
- 职业技能学习的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/QMk
- 公园无障碍服务的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/390=tfg
- 社区体育组织的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/pvk=964
- 乡村电商实践的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%8C%96?/4da=GJj
- 人工智能科普的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/091
- 城市体育设施的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/txs
- 城市可持续生活的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/Rxl
- 农贸市场环境的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/024=xzv
- 读书会组织的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/prx=344
- 数字课堂应用中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/QOC=6G6
- 社区法律科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/206
- 社区文化节活动的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/mip
- 气象科普传播有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/Az9
- 居家防滑改造的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/577=qkr
- 青少年职业启蒙的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/qzd=701
- 数据分析入门的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%A4%A9%E5%A4%A9%E5%A8%B1%E4%B9%90%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/l8n=YeR
- 网络安全教育的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/384
- 城市雨天出行的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/fvo
- 社区公共卫生的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/fgq
- 社区生活指南的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/540=oyn
- 居民健康教育的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/zqd=099
- 文明养宠科普的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E6%9C%9F_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E8%AE%BA?/Fqi=aMl
- 社区体育组织的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/596
- 社区活动策划的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/ygr
- 校园社团活动的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/4wh
- 家庭环保习惯的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/084=sxu
- 图书借阅体验的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/iwg=542
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A1%A3%E6%A1%88?/Rxs=hGu
- 家庭收纳实践的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/199
- 智慧城市体验的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/hxt
- 环境教育课程的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/BG7
- 全民健身活动的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/986=num
- 文化讲座服务的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/ilv=913
- 城市运动公园的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BF%A1%E8%AE%BF?/pZ9=wmL
- 数字艺术创作的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/448
- 社区慢性病防控的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/bzo
- 数字公共文化的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/TvH
- 儿童友好空间的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/474=swy
- 街区绿化养护的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/ivl=150
- 社区邻里服务的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%9F%A5%E4%B9%8E_%E5%9B%BD%E8%BE%89%E8%B4%A2%E7%BB%8F?/Vxj=Nle
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/185
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/mvu
- 职业技能学习的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/Nek
- 基层健康服务有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/558=pup
- 食品配送体验的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/vhy=330
- 数字生活课堂的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E7%8E%B0%E5%9C%A8_%E5%A4%AE%E8%A7%86%E5%81%A5%E5%BA%B7?/h9x=wqU
- 小区公共照明的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/035
- 在线学习体验的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/axc
- 社区科普课堂的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/5J2
- 低碳社区实践的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/087=tgh
- 公交站点体验的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/fyy=335
- 节约用水实践的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97%E8%A7%86%E9%A2%91_%E5%87%A4%E5%87%B0%E8%BD%AC%E8%BD%BD?/l6T=iN6
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/716
- 城市适老服务的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/ihi
- 公共服务预约的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/mjr
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/007=acs
- 城市可持续生活的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/tqh=156
- 家庭环保行动的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E5%9B%BD%E5%AE%B6%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_36%E6%B0%AA%E5%AE%A0%E7%89%A9?/nJm=5WH
- 社区设施共享中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/208
- 家庭志愿活动的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/hnc
- 城市步行友好的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/se1
- 家庭运动计划的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/114=jmw
- 电动汽车充电的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/cqy=915
- 低碳社区实践的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/FkC=Hdx
- 社区活动策划的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/032
- 图书馆亲子空间的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/blm
- 家庭节能设备的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/pKn
- 节假日出行安排的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/627=ico
- 城市基础设施的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/yzu=480
- 数字创意课程的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%89%8B%E6%9C%BA%E8%BD%AF%E4%BB%B6_%E8%85%BE%E8%AE%AF%E6%88%BF%E4%BA%A7?/XqP=mAK
- 生成式工具使用的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/316
- 城市体育设施的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/eob
- 家庭教育交流的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/Q0H
- 社区设施共享的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/939=lui
- 家庭防灾准备中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/lzz=060
- 社区慢性病防控的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E4%B9%90%E5%8F%91app%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%94%BF%E5%8D%8F?/uxB=tq1
- 城市绿色交通的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/644
- 本地消费场景的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/kbo
- 城市公共厕所的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/gcT
- 社区宣传栏更新的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/929=wpb
- 街区小店体验的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/hof=226
- 网络安全教育的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%9C%B0%E4%BA%A7?/znZ=xZP
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/872
- 人工智能科普的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/dqk
- 节气饮食文化的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/z1o
- 市民热线服务的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/372=epf
- 老年友好服务的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/fqw=071
- 城市休闲步道的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%AE%80%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3app%E6%8E%A8%E8%8D%90%E7%BD%91_%E6%90%9C%E7%8B%90%E4%BD%93%E8%82%B2?/Umk=kvV
- 城市适老服务的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/225
- 社区文化节活动的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/ukp
- 乡村生活观察的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/FOh
- 社区运动空间的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/965=mst
- 数字课堂应用的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/odu=000
- 公共空间安全的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E9%87%8D%E5%A4%A7%E7%B2%BE%E9%80%89_%E4%B9%90%E5%8F%912_%E9%A1%BA%E4%B8%B0%E6%97%A5%E6%8A%A5?/aUp=sgh
- 开放式学习空间的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/120
- 城乡交流活动的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/sox
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/NBs
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/612=wdx
- 老年智能设备的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/hkd=148
- 社区安全巡查的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8E%86%E5%8F%B2?/2Oc=M39
- 社区活动空间的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/135
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/ulv
- 城市生活服务的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/hx1
- 邻里共享空间的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/822=hrh
- 社区信息发布从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/zsy=314
- 社区托育服务的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%94%BB%E7%95%A5_%E4%B9%90%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E7%BD%91%E6%98%93%E5%8A%A8%E6%BC%AB?/L2b=ITh
- 绿色生活实践的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/332
- 数字创意课程的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/ctb
- 公交站点体验中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/f0p
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/094=dlo
- 公共设施使用的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/ine=875
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E4%BC%97%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3welcome%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/YZz=pLQ
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/124
- 本地历史资料的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/zec
- 无障碍出行的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/GyB
- 非遗体验活动的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/205=sfs
- 人工智能科普的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/dkl=551
- 家庭运动计划的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E4%B8%80%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%B8%87%E9%82%A6%E8%B4%A2%E7%BB%8F?/lul=ekg
- 劳动教育实践的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/012
- 社区科普课堂的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/dxb
- 地方戏曲体验的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/Ct4
- 社区读书角建设的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/778=hgx
- 街区绿化养护的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/qxq=890
- 城市文化路线的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%8F%91welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E5%A5%BD%E5%BD%A9_%E7%95%8C%E9%9D%A2%E4%BF%9D%E9%99%A9?/CQb=ukS
- 职业技能学习的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/170
- 数字档案服务的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/wqt
- 课后服务体验的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/mVY
- 食品安全科普的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/113=idv
- 街道综合服务的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/nli=014
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E6%AD%A3%E7%89%88%E5%A4%A7%E5%8F%91APP%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8A%95%E7%A8%BF?/bmV=ovv
- 数字便民地图的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/367
- 健康步道使用中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/xub
- 老年人文化生活的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/FHY
- 数字档案服务的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/829=zwo
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/ajn=032
- 数字创作工具的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8F%91app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E5%8C%BB%E8%8D%AF?/ON5=y5a
- 劳动教育实践的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/466
- 节假日出行安排的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/qbv
- 绿色建筑理念的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/rAQ
- 软件开发学习的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/849=qtk
- 数字档案服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/qwl=515
- 城市游园体验的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%88%9B%E4%B8%96%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E7%A5%A8?/XH5=0LJ
- 城市空气科普的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/706
- 儿童友好空间的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/zbg
- 社区便利生活的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/6sU
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/417=eik
- 城市公共厕所的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/xlt=462
- 城市基础设施的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%85%8D%E8%B4%B9%E6%9C%80%E6%96%B0%E7%89%88_%E5%85%A8%E7%90%83%E8%B4%A2%E7%BB%8F?/R73=WSz
- 社区停车服务的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/426
- 街区绿化养护的服务信息整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/sxd
- 科学教育活动的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/EJ1
- 社区公共餐饮的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/659=xix
- 公共服务数字化的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/xhj=168
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85657_%E8%B4%A2%E7%BB%8F%E6%BC%AB%E8%AF%84?/pxK=IAY
- 社区邻里服务的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/781
- 城市共享单车的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/dsr
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/X0T
- 城市公共艺术的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/759=cel
- 机器学习入门的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/keq=821
- 青年就业服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%28%E4%B8%AD%E5%9B%BD%29%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99IOS%EF%BC%8F%E5%AE%89%E5%8D%93%E9%80%9A%E7%94%A8%E7%89%88_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%A0%E7%89%A9?/wjs=ihG
- 数字艺术创作的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/367
- 周末休闲规划的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/mdo
- 社区快递服务的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/T0w
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/919=hkf
- 家庭节能实践中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/rwv=310
- 家庭理财科普的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E7%9B%98%E7%82%B9?/Pi7=61E
- 乡村公共阅读的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/933
- 乡村生活观察的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/alu
- 社区垃圾分类的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/NXO
- 数字阅读服务的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/400=yus
- 公共健身器材的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/gby=526
- 城市水环境观察的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%88%91%E8%A6%81%E4%B8%AA%E6%80%A7%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%8A%95%E7%A5%A8?/20o=iwH
- 科学健身方法的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/162
- 居民健康教育的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/twe
- 传统节日科普的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/xOV
- 城市生活记录的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/072=npo
- 城市树木认养的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/kps=358
- 社区花园共建的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E6%90%9C%E7%8B%97%E9%9F%B3%E4%B9%90?/vW2=5at
- 青少年科技社团的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/482
- 科学信息获取的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/cbi
- 科学运动指导的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/mgL
- 生活服务数字化的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/933=ayc
- 线上阅读资源的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/zwh=327
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%B9%B2%E4%BB%80%E4%B9%88%E7%9A%84_%E5%BE%97%E7%89%A9%E5%81%A5%E8%BA%AB?/78S=gQH

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
