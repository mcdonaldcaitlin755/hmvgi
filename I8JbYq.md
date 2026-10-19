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

- 公共卫生设施的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B9%B0%E5%89%8D5%E5%90%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/hgi=147
- 家庭理财科普的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E4%B9%B0%E5%89%8D5%E5%90%8D%E6%96%B9%E6%B3%95_%E4%BC%98%E9%85%B7%E5%9B%BE%E9%9B%86?/FqA=oMi
- 城市公共厕所的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/800
- 乡村教育资源的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/gpf
- 基层健康档案的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/1Ru
- 亲子科普活动的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/507=bew
- 生活垃圾回收的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/vcb=204
- 科学教育活动的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A25%E7%A0%81%E6%80%8E%E4%B9%88%E7%AE%97_%E5%A4%B4%E6%9D%A1%E5%BD%A9%E7%A5%A8?/0lW=EJY
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/347
- 公共服务数字化的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/ima
- 城市空气科普的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/i0u
- 老年人日常照护的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/919=tse
- 科学健身方法的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/gsu=559
- 城市社区治理的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E5%9B%BE%E7%89%87_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/LFk=xSV
- 城市地名文化的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/131
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/yed
- 老年友好服务的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/KzL
- 社区共享书架的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/196=nlz
- 绿色出行服务的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/fvi=237
- 社区运动空间中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%86%A0%E5%86%9B%E7%A8%B3%E8%B5%A2%E8%A7%84%E5%BE%8B%E6%98%AF%E4%BB%80%E4%B9%88_%E7%99%BE%E5%BA%A6%E4%BD%93%E8%82%B2?/ArW=89h
- 老年学习活动从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/971
- 城市树木认养的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/uub
- 乡村文化空间的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/8Hk
- 城市运动公园的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/210=rwn
- 社区运动空间的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/yey=158
- 老年人出行服务的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%9A%84%E7%8E%A9%E6%B3%95%E8%A7%84%E5%88%99_%E9%9B%85%E8%99%8E%E4%BD%93%E8%82%B2?/UnC=Fot
- 文化讲座服务的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/241
- 乡村公共服务的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/poc
- 城市共享单车的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/GZP
- 节假日出行安排的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/592=qly
- 校园节能行动的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/gjs=008
- 节约用水实践的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%88%86%E6%96%99_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%98%AF%E4%B8%8D%E6%98%AF%E5%81%87%E7%9A%84_%E8%99%8E%E5%97%85%E6%A6%9C%E5%8D%95?/bNC=anw
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/364
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/fus
- 社区便民服务的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/QUQ
- 公共健身器材的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/813=aoa
- 城市共享单车的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/sre=555
- 城市应急广播的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/Gzf=gDe
- 儿童户外活动的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/836
- 急救知识普及的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/ifp
- 公共图书馆服务的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/Okx
- 城乡交流活动的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/992=uqv
- 家庭节能实践的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/xjq=720
- 小微企业服务的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%B8%AF%E8%82%A1?/2gK=IuM
- 节日文化体验的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/521
- 口袋公园建设的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/brh
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/mbc
- 科普展览体验的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/728=gbe
- 社区文化节活动的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/jhj=502
- 社区交通安全的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_1%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E7%BD%91_%E5%A4%AE%E8%A7%86%E6%8E%A2%E6%BA%90?/Yte=sSg
- 网络安全教育的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/495
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/yrf
- 社区防暑服务的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/xY0
- 乡村文化活动的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/430=cdf
- 社区垃圾回收的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/fws=978
- 社区便民集市的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%AE%98%E6%96%B9%E5%BC%80%E5%A5%96_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9B%98%E7%82%B9?/Vn2=aOW
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/453
- 城乡公共服务的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/lgw
- 乡村电商实践的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/nNZ
- 公共服务沟通的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/930=kvh
- 本地消费场景的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/pxm=518
- 城市体育设施中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E6%BE%8E%E6%B9%83%E4%BC%97%E6%B5%8B?/0PE=exN
- 节约用水实践的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/291
- 读书会组织的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/nzm
- 零废弃生活尝试的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/d4O
- 远程协作工具的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/485=voj
- 城乡公共服务的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/xud=394
- 社区停车服务的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%8B%B9%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E6%94%B6%E8%97%8F?/HEn=nNd
- 数字学习资源的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/764
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/gdk
- 家庭阅读计划的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/bEm
- 公共场馆服务的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/948=qpn
- 家庭安全提示的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/wtr=128
- 社区宣传栏更新的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%9A%84%E8%B5%9B%E8%BD%A6_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/Qaq=HfU
- 城市展览体验的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/551
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/yrn
- 气象科普传播的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/96Z
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/737=ldr
- 科学观察活动的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/ewc=065
- 文化讲座服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%AE%B6%E7%94%B5?/eDn=sde
- 休闲运动入门的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/334
- 药品使用科普的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/tkl
- 公交无障碍服务的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/X86
- 社区交通安全的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/994=eim
- 城市体育设施的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/uto=575
- 节日文化体验的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/PrE=f3E
- 城市步行友好的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/761
- 节约用水实践的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/tyd
- 公共空间照明的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/KRv
- 社区活动报名的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/214=tiw
- 公共卫生宣传的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/upl=100
- 小区公共照明的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_3%E5%88%86%E9%92%9F%E8%B5%9B%E8%BD%A6%E5%BC%80%E5%A5%96%E8%AE%B0%E5%BD%95_%E7%BD%91%E6%98%93%E5%88%B8%E5%95%86?/XjK=CI2
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/989
- 小微企业服务的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/ctd
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/lGP
- 学校体育活动的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/404=ior
- 社区艺术活动的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/ivq=516
- 社区老年食堂的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95%E8%A1%A8%E5%AF%B9%E5%88%B7_%E7%9F%A5%E4%B9%8E%E5%8F%B7%E5%A4%96?/I6V=jhW
- 家庭节能实践的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/810
- 家庭消费规划的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/odp
- 社区读书角建设的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/oDf
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/566=ivo
- 城市树木认养的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/biu=953
- 街道综合服务的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E4%BA%94%E7%A0%81%E4%B8%89%E6%9C%9F%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E9%A1%BA%E4%B8%B0%E6%99%A8%E6%8A%A5?/58n=EdO
- 社区便利生活的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/036
- 课后服务体验的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/fkx
- 城市绿道建设的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/svf
- 基层医疗预约从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/738=viw
- 社区健康讲座的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/yrz=176
- 社区托育服务的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E6%94%BB%E7%95%A5_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A66%E7%A0%81%E5%8F%A3%E8%AF%80%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E5%81%A5%E8%BA%AB?/s7A=3EE
- 电动汽车充电的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/663
- 社区快递服务的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/ecc
- 小区停车协商的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/iOP
- 家庭健康管理的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/650=qoz
- 周末休闲规划的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/tnf=934
- 社区法律科普中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_2%E7%BB%847%E7%A0%81%E5%BF%85%E4%B8%AD%E4%B8%80%E7%BB%84_%E6%96%B0%E6%B5%AA%E6%B1%BD%E8%BD%A6?/47D=CeT
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/315
- 绿色出行服务的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/cqi
- 软件开发学习的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/CFI
- 家庭健康科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/494=udu
- 消防知识宣传的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/akv=543
- 节假日出行安排的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%85%AD%E7%A0%81%E8%A7%84%E5%BE%8B_%E8%84%89%E8%84%89%E7%90%86%E8%B4%A2?/2er=E1R
- 志愿者培训交流的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/236
- 社区消防演练的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/spu
- 家庭陪伴活动的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vg5
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/963=oqx
- 科普展览体验的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/oft=126
- 青年就业服务的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_1%E5%88%86%E8%B5%9B%E8%BD%A66%E7%A0%81%E6%80%8E%E4%B9%88%E5%AE%B9%E6%98%93%E4%B8%AD_%E9%87%91%E7%9B%9B%E8%B4%A2%E7%BB%8F?/Ta0=xpM
- 线上阅读资源的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/607
- 数字创意课程的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/evz
- 数字便民地图的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/F0M
- 学校食育活动的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/560=lmf
- 城市应急广播从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/zgt=604
- 健康信息获取的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A28%E7%A0%81_%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9F%E8%A7%88?/VrB=dr6
- 本地历史资料的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/450
- 节能生活方式的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/uwv
- 地方文化传播的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/XyO
- 公园无障碍服务的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/573=dux
- 公共服务指南的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/xwp=143
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/vO2=rQF
- 社区艺术活动的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/452
- 社区健康讲座的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/pas
- 城市体育设施的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/CfJ
- 科技馆参观体验的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/400=wkg
- 青年就业服务的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/qmm=606
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E6%8A%80%E5%B7%A7_%E4%BA%AC%E4%B8%9C%E6%B8%AF%E8%82%A1?/lnW=NnU
- 环境教育课程的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/109
- 社区托育服务的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/plq
- 数字档案服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/UXH
- 图书馆活动策划中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/342=yts
- 青少年户外教育的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/anh=289
- 数字素养提升的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%A8%B3%E8%B5%A2_%E4%BA%AC%E4%B8%9C%E6%96%87%E5%BA%93?/3qa=JPO
- 图书借阅体验有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/098
- 社区文化传播中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/uxy
- 公共设施使用的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/vf9
- 农产品品牌传播的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/419=klw
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/hla=580
- 人工智能科普的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E4%B9%B0%E5%8F%B7_%E5%BF%AB%E6%89%8B%E6%95%B0%E8%AF%BB?/sut=2KU
- 社区商业活力的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/010
- 公共设施维护的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/uzj
- 城市空气科普的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/N9l
- 老年数字阅读的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/051=sxc
- 租房信息服务的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/vcd=969
- 公共服务数字化的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%80%BB%E7%BB%93_%E6%8A%96%E9%9F%B3%E6%89%8B%E8%AE%B0?/4Pz=xgJ
- 数字创作工具的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/480
- 在线学习体验的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/hga
- 无障碍出行的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/TjV
- 青少年科技社团的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/893=jvn
- 城市水环境观察的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/wvg=638
- 社区快递服务的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%96%B9%E6%A1%88%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%80%8E%E4%B9%88%E7%8E%A9%E6%B3%95_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/vp8=u9Z
- 青少年心理健康中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/590
- 机器人科普活动的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/fhh
- 生活垃圾减量的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/CRZ
- 青年就业服务的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/552=vqr
- 灵活就业交流的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/srx=427
- 医院导诊服务的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%A7%92%E6%87%82%E9%A3%8E%E5%90%91_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9B%BE%E9%89%B4?/MFK=ALp
- 社区读书角建设的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/032
- 节能生活方式的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/izu
- 户外活动组织的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/EkV
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/580=gdq
- 校园节能行动的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/pgf=302
- 数字资源检索的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E8%B1%86%E7%93%A3%E5%8F%B7%E5%A4%96?/1bw=EuC
- 家庭陪伴活动的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/249
- 机器学习入门的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/mnc
- 个人时间管理的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/cvc
- 城市农夫市集的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/230=hri
- 社区商业活力的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/bco=969
- 基层服务创新的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%9B%BE%E8%A7%A3%E5%A4%A7%E5%85%A8%E5%88%86%E4%BA%AB_%E8%B0%B7%E6%AD%8C%E4%BF%A1%E8%AE%BF?/YF9=k1E
- 就业技能培训的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/107
- 社区垃圾分类的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/abu
- 周末休闲规划的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/Zug
- 家庭志愿活动的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/174=zld
- 城市绿色交通的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/zze=411
- 公交站点体验的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/3lF=uTN
- 社区故事采集的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/990
- 公共文化活动的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/mme
- 创业经验分享的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/NLK
- 社区协商议事的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/464=hdm
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/meu=691
- 城市建设科普的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_%E8%84%89%E8%84%89%E6%B1%BD%E8%BD%A6?/lqj=7wt
- 社区快递服务的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/532
- 城市文明出行有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/emp
- 家庭网络使用的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/RP2
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/240=ged
- 物业服务沟通的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/qoe=189
- 公共服务预约的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%99%BE%E5%BA%A6%E5%9C%B0%E4%BA%A7?/xvo=oYI
- 劳动教育实践的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/326
- 小区停车协商的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/fjy
- 网络安全教育的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/wjg
- 无障碍信息设计的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/559=dxf
- 社区家校合作的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/rgk=597
- 创业经验分享中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_1%E5%88%86%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7_%E9%9D%92%E5%B9%B4%E8%B4%A2%E7%BB%8F?/tQJ=Stj
- 社区快递服务的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/906
- 社区活动策划的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/fav
- 节日文化体验的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/EdI
- 学校食育活动的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/859=eip
- 健康饮食教育的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/nje=600
- 数字资源检索的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E7%8E%A9%E6%B3%95_%E5%BE%97%E7%89%A9%E6%92%AD%E6%8A%A5?/Vla=ELy
- 老年数字阅读的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/325
- 老年智能设备的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/zho
- 非遗体验活动的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/iMQ
- 智慧城市体验有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/271=fwz
- 老年运动活动的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/mzy=859
- 绿色校园实践的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B1%86%E7%93%A3%E5%8E%86%E5%8F%B2?/O1x=iI6
- 老年人文化生活的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/719
- 青少年心理健康的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/wvq
- 青少年职业启蒙的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/8WL
- 老年友好服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/430=vcd
- 儿童阅读角的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/zcb=705
- 街区道路维护有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E4%B8%80%E5%88%86%E9%92%9F%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E6%9F%A5%E8%AF%A2_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/Kjt=b9f
- 数字设备回收的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/560
- 儿童友好空间的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/jtb
- 绿色办公实践的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/hpH
- 农村环境治理从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/219=qak
- 开放数据应用的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/ycz=544
- 青少年科普实践的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%BE%97%E7%89%A9%E5%9C%88%E5%AD%90?/Otp=sUS
- 公益活动组织的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/791
- 家庭运动计划的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/wtz
- 社区环保活动的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/l5O
- 安全出行教育的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/860=lle
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/ziu=427
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/Yb0=EK5
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/170
- 线上阅读资源的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/kmf
- 线上阅读资源的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/Mmi
- 课后服务体验的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/926=tsw
- 数字设备回收的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/bsg=641
- 乡村教育资源中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%8A%95%E6%B3%A8%E5%AE%98%E7%BD%91_%E8%B0%B7%E6%AD%8C%E5%85%AC%E5%91%8A?/c62=ZR1
- 地方民俗记录的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/748
- 街头绿植养护从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E8%B5%9B%E8%BD%A6%E6%9C%89%E4%BB%80%E4%B9%88%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E5%AE%89%E9%98%B2?/jxy

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
