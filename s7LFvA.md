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

- 社区手工活动的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/452
- 食品配送体验的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/pzf
- 社区设施共享的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/P1T
- 职业技能学习的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/255=bus
- 城市雨天出行的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/koi=596
- 数字支付体验的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%99%BE%E5%BA%A6%E4%B9%90%E5%BD%A9%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%91%A8%E6%8A%A5?/K9a=cpK
- 青少年职业启蒙从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/870
- 城市生活记录的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/zev
- 城市公共厕所的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/VDo
- 终身学习资源的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/398=sli
- 社区便民集市的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/uvq=986
- 开放数据应用的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%9B%BD%E9%99%85365_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/Jur=kA0
- 青年志愿活动的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/031
- 社区故事采集的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/vli
- 节日文化体验的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/Yf8
- 社区家校合作的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/083=lsj
- 社区邻里服务的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/jzc=525
- 家庭科学教育从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%B6%E8%97%8F?/uNs=a6L
- 生活垃圾减量有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/150
- 信息无障碍体验的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/xci
- 家庭节能实践从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/4pm
- 数字档案服务的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/472=zim
- 公园无障碍服务的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/cwg=255
- 便民信息查询的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_360%E6%91%84%E5%BD%B1?/GSs=CBL
- 儿童友好空间的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/062
- 口袋公园建设的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/lzt
- 校园阅读活动的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/qW8
- 安全出行教育的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/472=prd
- 数字政务体验的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/zhb=918
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/8T7=A8x
- 人工智能科普的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/958
- 社区活动空间的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/kmp
- 个人时间管理的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/g4L
- 社区法律科普的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/066=dyb
- 老年运动活动的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/pje=189
- 数字课堂应用的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3%E6%89%8B%E6%9C%BA%E7%89%88_%E6%90%9C%E7%8B%90%E6%97%B6%E8%AE%AF?/RdA=wXR
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/316
- 物业服务沟通从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/ymy
- 市民热线服务的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/icW
- 城市博物馆活动的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/276=ugh
- 科学信息获取的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/jfs=127
- 节能家电使用中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E7%B1%B3%E5%BD%A9%E7%BD%91-APP%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E7%99%BE%E7%A7%91?/yFd=DWC
- 校园节能行动的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/556
- 社区体育组织的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/gyr
- 科学教育活动的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/BHu
- 社区便利生活的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/459=kdo
- 城市展览体验的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/gta=438
- 城市体育设施的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%B1%B3%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E6%94%BF%E7%AD%96?/BMp=XYP
- 家庭园艺实践的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/577
- 开源技术交流的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/klq
- 亲子阅读活动的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/FWj
- 城市适老服务的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/721=nis
- 图书馆数字服务中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/bio=904
- 便民信息查询的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_%E8%87%AA%E5%8A%A8%E5%80%8D%E6%8A%95%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F?/Okv=Sp6
- 街区更新实践的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/590
- 非遗课堂体验的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/whz
- 线上办事服务的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/m1h
- 街区更新实践的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/787=yrv
- 街区更新实践的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/sil=853
- 乡村教育资源的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%AE%9E%E4%BA%BF%E5%9B%BD%E9%99%85-welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%99%9A%E6%8A%A5?/bbl=NXx
- 街区更新实践的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/581
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/eos
- 家庭养老规划的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/0Yd
- 社区故事采集的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/469=tgn
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/hrr=485
- 公共服务评价的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%92%E8%A1%8C_%E8%B0%B7%E6%AD%8C%E6%B1%87%E5%B8%82?/6Jc=dFs
- 城市生活服务的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/482
- 节假日出行安排的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/flb
- 节能生活方式的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/y4Q
- 本地历史资料的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/131=xon
- 基层健康档案的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rnq=740
- 社区便利生活的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_%E6%96%B0%E6%B5%AA%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E6%96%B9_%E5%98%89%E4%BF%A1%E8%B4%A2%E7%BB%8F?/kqz=rPu
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/001
- 社区应急准备的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/awv
- 老年数字阅读的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/FYM
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/072=lwh
- 城市绿色交通的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/wdg=744
- 公共交通接驳的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83_%E8%B0%B7%E6%AD%8C%E8%A7%A3%E5%AF%86?/Onf=qb2
- 社区便利生活的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/275
- 节气饮食文化的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/xlf
- 公共服务预约的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/bn1
- 新能源知识普及的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/859=etl
- 社区托育服务的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/uqa=436
- 家庭志愿活动的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E9%97%AE%E7%AD%94?/pAP=Arb
- 家庭安全提示的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/818
- 社区手工活动的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/vsv
- 网络安全教育的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/NkU
- 社区花园共建的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/886=sih
- 乡村教育资源的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/iff=404
- 城市便民驿站的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-APP%E5%A4%A7%E5%85%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%A4%B4%E6%9D%A1?/TCM=d8t
- 数字设备回收的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/916
- 社区交通安全的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/nkr
- 家庭养老规划的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/gc6
- 数字创意课程的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/693=thg
- 社区消防演练的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/djg=229
- 城市公共自行车的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83-%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/SFf=3nK
- 学校体育活动的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/205
- 绿色生活实践的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/isu
- 家庭防灾准备的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/sLE
- 健康饮食教育的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/559=mdq
- 社区公共卫生的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/psr=398
- 急救知识普及的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E6%BE%B3%E5%AE%A2%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%8A%92%E6%9E%9C%E5%81%A5%E8%BA%AB?/Ib8=Hp6
- 绿色建筑理念的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/932
- 公共服务预约的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/ayb
- 公共卫生宣传的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/KiD
- 光伏知识科普的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/780=wbd
- 社区商业活力的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/umj=137
- 急救知识普及的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E7%BD%91%E6%98%93%E7%BA%A2%E5%BD%A9%E5%AE%98%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E8%AE%B2%E5%9D%9B?/0DM=XA8
- 地方戏曲体验的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/834
- 城市宠物友好空间的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/azm
- 城市休闲步道的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/YNg
- 社区便利生活的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/417=qek
- 社区信息发布的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/fqq=884
- 乡村公共文化的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_58%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B1%87%E5%B8%82?/xCy=jKu
- 节气饮食文化的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/885
- 乡村公共文化的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/slx
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/LSL
- 食品配送体验的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/595=hdk
- 社区公共餐饮的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/bai=441
- 学校食育活动的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AD%A6%E4%B9%A0_588%E5%BD%A9%E7%A5%A8%E9%A6%96%E9%A1%B5_%E5%90%AF%E5%85%83%E8%B4%A2%E7%BB%8F?/7Kc=Bit
- 数字创意课程的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/595
- 社区商业活力的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/rer
- 社区活动策划的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/Yzr
- 开放式学习空间的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/008=wzz
- 科学运动指导的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/xbq=475
- 城市绿道建设的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_58%E5%BD%A9%E7%A5%A8%E8%B4%A6%E5%8F%B7%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%85%A7%E7%9C%BC?/6Lf=D4Y
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/160
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/xpm
- 药品使用科普的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/0Cl
- 传统节日科普的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/639=hak
- 医院导诊服务的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/ben=391
- 公共卫生宣传的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E6%89%8B%E5%86%8C_%E4%B8%9C%E6%96%B9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_360%E9%97%AE%E7%AD%94?/PT6=Hhc
- 开放式学习空间的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/426
- 应急物资管理的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/fgz
- 城市公共空间的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/DP4
- 灵活就业交流的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/434=qli
- 社区宠物管理的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/xsh=691
- 城市步行环境的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/p53=2gZ
- 老年智能设备的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/068
- 家庭网络使用的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/wrc
- 公共服务数字化的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/Rpw
- 校园安全教育的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/134=mdu
- 公园亲子设施的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/pxd=418
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%B2%BE%E9%80%89_777%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome%E5%85%A5%E5%8F%A3_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/RDI=Uh3
- 城市绿色交通的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/355
- 数字创意课程的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/jgm
- 数字设备回收的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/VXZ
- 周末休闲规划的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/510=uqv
- 绿色生活实践的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/zkb=046
- 社区学习活动的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_777%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%90%E5%86%9B%E4%BA%8B?/XNE=WkC
- 乡村文化活动的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/663
- 地方文化传播的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/whl
- 社区养老服务的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/OPu
- 家庭安全提示中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/150=agm
- 无障碍出行的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/kuv=883
- 公园亲子设施的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8777888_%E5%93%94%E5%93%A9%E7%90%86%E8%B4%A2?/Ajx=Ed5
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/422
- 青年职业探索的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/gsi
- 居家防滑改造中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/H7K
- 社区信息发布的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/182=uix
- 公共交通信息服务的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/kwg=689
- 基层服务创新的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_425ccm%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E5%86%9C%E4%B8%9A?/pB6=wmL
- 开放数据应用的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/914
- 社区手工活动的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/yoc
- 城市建设科普的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/xPw
- 儿童阅读角的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/604=evc
- 社区艺术活动的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/ikf=290
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/13G=yV3
- 城市适老服务的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/324
- 乡村生活观察的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/dsq
- 城市慢行系统的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/dJm
- 城市慢行系统的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/489=rge
- 城市公共厕所的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/xhb=084
- 生活垃圾回收的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%81%92%E7%9B%88%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%BD%A9%E7%A5%A8?/tju=PVr
- 社区快递服务的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/294
- 儿童安全出行的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/keo
- 网络安全教育的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/0u2
- 全民健身活动的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/363=wqe
- 社区花园共建的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/lpe=384
- 青少年心理健康的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_357%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9B%9B%E4%B8%96%E8%B4%A2%E7%BB%8F?/xqk=hT6
- 青年就业服务的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/919
- 街区绿化养护的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/eeo
- 家庭安全提示的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/Jy3
- 城市微更新实践从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/575=pql
- 校园社团活动的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/rkx=532
- 青少年户外教育的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_357%E5%BD%A9%E7%A5%A8IOS_%E5%A4%AE%E8%A7%86%E5%8D%83%E5%B8%86?/k8m=Dsg
- 课后服务体验的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/895
- 公共文化活动的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/syk
- 地方旅游导览的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/2y7
- 生活垃圾减量的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/211=slg
- 公园休闲体验的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/ahy=504
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_379%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%90%AF%E6%98%8E%E8%B4%A2%E7%BB%8F?/4Po=Qvh
- 本地消费场景的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/522
- 公共卫生宣传的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/umr
- 家庭园艺实践的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/XOy
- 城市文化路线的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/858=mca
- 社区商业活力的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/het=421
- 城市雨天出行的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E7%A4%BE%E8%AE%BA?/176=Bdl
- 家庭教育交流的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/618
- 便民信息查询的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/jre
- 校园社团活动的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/yzm
- 便民服务地图的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/339=wya
- 文化遗产保护科普的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/zug=795
- 公园亲子设施的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_379%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BC%97%E6%B5%8B?/wBp=w1q
- 亲子科普活动的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/537
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/uzk
- 公共文化活动的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/3vC
- 乡村公共服务的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/640=eur
- 城市夜间生活的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/qcp=441
- 社区文化节活动的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_379%E5%BD%A9%E7%A5%A8_%E5%BE%97%E7%89%A9%E5%9B%BE%E9%9B%86?/BO8=Mg4
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/785
- 科普展览体验的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/qva
- 社区庭院绿化的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/vCn
- 社区托育服务的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/290=raw
- 城市建设科普的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/bio=062
- 城乡公共服务中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_6701%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A8%BF?/XsF=rOM
- 公共空间导览的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/765
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/rve
- 社区活动空间的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/ufc
- 乡村文化活动的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/132=pqt
- 居家适老化改造的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/jmg=750
- 社区垃圾回收的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_6701%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/I5I=7wv
- 劳动教育实践的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/518
- 地方戏曲体验的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/pew
- 信息无障碍体验的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/lMR
- 全民健身活动的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/519=mui
- 科学健身方法的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/xam=781
- 家庭理财科普的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_6701%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E6%AC%A7%E7%BE%8E%E8%B4%A2%E7%BB%8F?/DbT=nWh
- 乡村生活观察的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/216
- 公共设施使用的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/qkh
- 租房信息服务的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/W6u
- 城市适老服务的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/218=qdc
- 城市步行友好的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/spv=024
- 城市展览体验的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_6701%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E5%9F%BA%E9%87%91?/kpN=kUF
- 智能手机助老的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/501
- 健康步道使用的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/oqs
- 数字学习资源的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/2QX
- 社区交通安全的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/252=ugp
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/klo=512
- 城市公共饮水的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E4%BC%98%E9%85%B7%E6%9B%B2%E8%89%BA?/kxR=gok
- 非遗体验活动的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/094
- 乡村阅读空间的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/byg
- 青少年编程学习的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/90N
- 数字地图应用的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/446=ggw
- 公共卫生设施有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/hjo=637
- 社区便民服务的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_6701%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/rIV=sgi
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/317
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/iek
- 图书馆亲子空间的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/45V
- 城市雨天出行的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_6G%E5%BD%A9%E7%A5%A8-welcome_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/037=zjp

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
