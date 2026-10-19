# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:20**

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

- 食品安全科普的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BF%A1%E8%B4%B7?/ofb=373
- 线上办事服务的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_360%E4%BF%A1%E8%B4%B7?/3Vs=SLe
- 个人数据管理的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/570
- 城市环境志愿行动的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/xpl
- 社区运动空间的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/JRc
- 公交站点体验的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/450=rce
- 城市博物馆服务的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/vjp=777
- 数字设备回收的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%9C%B0%E6%96%B9?/sIP=rS3
- 读书会组织的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/935
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/egf
- 城市雨天出行的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/CT1
- 农贸市场环境的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/908=bib
- 农业科普体验的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/opw=310
- 地方文化传播的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/OY2=OII
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/110
- 文化场馆预约从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/cqw
- 无障碍出行的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/un8
- 城市慢行系统的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/719=cxf
- 家庭环保行动的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/wae=662
- 公交无障碍服务中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_360%E5%88%B8%E5%95%86?/ApQ=n25
- 城市共享单车的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/651
- 家庭养老规划的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/njs
- 社区儿童活动的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/3iM
- 绿色消费选择的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/420=mza
- 城市可持续生活的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/hkj=780
- 数字设备回收的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BC%97%E5%90%88%E8%B4%A2%E7%BB%8F?/39m=xjq
- 生成式工具使用的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/343
- 城市微更新实践的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/oin
- 社区心理支持的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/JVq
- 居家适老化改造中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/889=wjj
- 社区读书角建设的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/xyc=638
- 社区运动空间的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/hKF=fT4
- 乡村生态旅游的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/431
- 健康信息获取的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/iqo
- 儿童安全出行的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/4Vw
- 老年友好服务的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/564=ujo
- 城市文化路线的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/ltp=437
- 小微企业服务的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/kOg=BQE
- 家庭安全提示从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/632
- 药品使用科普的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/nis
- 社区心理支持的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/Cml
- 街区更新实践的数字化应用观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/712=dce
- 家庭收纳实践的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/vvs=384
- 校园阅读活动的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E4%BA%86%E8%A7%A3_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/YtO=ujm
- 节气饮食文化的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/960
- 城市应急广播的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/vcj
- 老年学习活动的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/sYq
- 公园亲子设施的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/759=ztd
- 青年志愿活动中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/ejc=286
- 老年运动活动的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E8%AE%A8%E8%AE%BA_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%B9%B6%E8%B4%AD?/NDJ=Vry
- 社区儿童活动的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/379
- 食品配送体验的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/qhy
- 社区健康讲座的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/x1w
- 智慧城市体验的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/730=wxv
- 城市生活记录从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/krm=214
- 城市公共艺术的设施维护观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E4%BF%9D%E9%99%A9?/BfQ=NPO
- 邻里互助活动的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/599
- 全民健身活动的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/pqo
- 社区知识分享的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/MWh
- 家庭用电安全的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/743=zzq
- 公共交通接驳的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/lmu=289
- 节假日出行安排的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/bSa=DBX
- 社区儿童活动的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/975
- 城市可持续生活的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/mps
- 医院导诊服务的居民参与机会 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/qC0
- 公园亲子设施的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/328=bif
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/fdg=000
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%BD%A9%E6%B0%91%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E7%A8%8E%E5%8A%A1?/UDW=F0o
- 科学观察活动的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/451
- 终身学习资源的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/seb
- 数字阅读服务的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/EnJ
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/793=nhz
- 社区垃圾分类的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/bly=241
- 图书借阅体验的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/TIq=2Q2
- 街区小店体验的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/977
- 家庭消费规划的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/puq
- 社区公共餐饮的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/4Ne
- 健康步道使用的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/108=wue
- 乡村公共服务的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/txy=258
- 绿色快递包装的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E7%9B%B4%E6%92%AD?/F8D=goO
- 城市文化路线的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/707
- 居家适老化改造的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/myj
- 乡村产业科普的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/19y
- 食品安全科普的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/782=tbw
- 农产品消费体验的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/kfl=164
- 社区垃圾回收的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_%E7%BD%91%E6%98%93%E6%97%B6%E8%AF%84?/tHP=3C0
- 社区公共餐饮的使用门槛与改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/055
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/kxi
- 智慧城市体验的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/UTW
- 绿色快递包装的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/911=iel
- 社区老年食堂的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/tkm=935
- 老旧小区改造的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%93%94%E5%93%A9%E7%BB%BC%E8%89%BA?/Qv3=5HO
- 志愿服务平台的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/904
- 城市噪声观察的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/awx
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/RE8
- 校园阅读活动的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/408=bjg
- 药品使用科普的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/dcm=627
- 农产品消费体验的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E6%8A%96%E9%9F%B3%E5%8A%A8%E6%BC%AB?/lr6=Mg9
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/742
- 绿色建筑理念的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/aej
- 居家防滑改造中的沟通与协作 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/hsD
- 公共空间导览的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/949=kpz
- 节约用水实践的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/lxo=987
- 城乡公共服务的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%91%E9%81%93_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E7%BD%91_%E5%90%AF%E8%BF%AA%E8%B4%A2%E7%BB%8F?/QbL=ahw
- 应急物资管理的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/194
- 科学运动指导的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/weh
- 城市建设科普从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/mLW
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/061=yuy
- 终身学习资源的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/qht=793
- 社区庭院绿化的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%92%AD%E6%8A%A5?/z51=ipC
- 街道综合服务的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/311
- 健康步道使用的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/pvm
- 社区体育组织的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/5KN
- 药品使用科普的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/339=cyv
- 城市体育设施的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/gtu=370
- 儿童户外活动的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%92%E6%87%82%E8%A7%A3%E8%AF%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E8%99%8E%E5%97%85%E6%AF%8D%E5%A9%B4?/bPC=hzV
- 公园亲子设施的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/606
- 便民维修服务的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/hcs
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/eix
- 绿色快递包装的入门知识整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/726=npy
- 租房信息服务的参与方式与路径 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/ukv=051
- 校园安全教育的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP_%E5%A4%B4%E6%9D%A1%E9%97%AE%E7%AD%94?/zA6=0DF
- 城市公共自行车的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/365
- 节约用水实践的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/knn
- 公园无障碍服务的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/b94
- 家庭收纳实践的空间使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/882=stm
- 文化遗产保护科普的长期维护要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/puy=584
- 老年友好服务的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E4%BC%98%E4%BA%AB%E8%B4%A2%E7%BB%8F?/fD1=73h
- 校园社团活动的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/265
- 城市应急广播的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/yco
- 老年人日常照护的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/98x
- 绿色校园实践的基础设施观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/057=jzi
- 社区便利生活的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/elj=833
- 户外活动组织的家庭参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%99%BE%E5%BA%A6%E8%83%BD%E6%BA%90?/O9J=Teu
- 数字阅读服务的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/871
- 城市应急广播的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/xpt
- 家庭节能实践的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/5ne
- 城市社区治理的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/598=bja
- 城市展览体验的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/vbd=000
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E7%99%BB%E5%BD%95_%E5%AE%8F%E8%BE%BE%E8%B4%A2%E7%BB%8F?/iTd=CkJ
- 开放式学习空间的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/380
- 家庭节能设备的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/ecy
- 城市地名文化的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/mgR
- 乡村产业科普的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/344=rwj
- 数字支付体验的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/hhk=649
- 儿童阅读角的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/Slq=34E
- 科学运动指导的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/591
- 城市人文观察的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/qpp
- 市民意见收集的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/zHz
- 本地消费场景的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/663=kqm
- 便民服务窗口的协作机制梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/ojq=193
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%99%BE%E7%A7%91?/zQQ=trz
- 在线教育体验的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/940
- 社区手工活动的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/xuc
- 创业经验分享的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/YqO
- 社区邻里服务的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/702=ttw
- 家庭健康管理的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/etx=646
- 线上办事服务的适老服务细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%AE%B6%E5%B1%85?/wgV=JwQ
- 社区设施共享的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/418
- 智慧停车服务的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/xez
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/0wU
- 在线学习体验的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/887=jrx
- 绿色校园实践的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/kwz=491
- 校园社团活动的常见误区提醒 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%B2%BE%E9%80%89%E5%AD%A6%E4%B9%A0_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8E%A2%E5%BA%97?/L9S=rR3
- 城市社区治理的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/830
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/cpp
- 数字阅读服务的服务信息整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/U0V
- 传统节日科普的社区行动案例 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/290=jyr
- 生活服务数字化的组织方法与经验 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/tcu=517
- 数字支付体验的儿童友好细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%AC%AC%E4%B8%80%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%90%9C%E7%8B%97%E5%BD%B1%E8%A7%86?/bur=ysl
- 城市树木认养从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/259
- 日常摄影记录的服务细节记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/ikm
- 社区便民服务的资源利用方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/Z7C
- 节气饮食文化的基础知识问答 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/830=wia
- 乡村公共服务的绿色实践方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/isy=605
- 绿色消费选择的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E9%A1%BA%E4%B8%B0%E8%A7%A3%E5%AF%86?/m7Q=Z2j
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/305
- 本地消费场景的空间设计要点 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/jug
- 通勤路线规划的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/gOF
- 城市社区治理的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/554=uru
- 家庭急救准备的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/mnx=659
- 公共空间照明的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%8E%A9%E5%AE%B6%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%BD%A9-%E5%AE%98%E6%96%B9_%E8%99%8E%E6%89%91%E6%8A%95%E7%A5%A8?/g88=2D8
- 旧物循环利用从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/770
- 社区共享书架的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/hak
- 城市树木认养的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/fk9
- 街区小店体验中的几个关键细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/854=xal
- 乡村公共文化的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/dxg=600
- 城市微更新实践的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E8%B5%84%E8%AE%AF?/ZKl=gWE
- 节日文化体验的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/664
- 公共服务评价的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/ywi
- 城市微更新实践的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/886
- 个人数据管理的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/874=voa
- 社区知识分享的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/jwl=787
- 音乐欣赏活动的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-welcome%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%B5%84%E8%AE%AF?/ruo=wBK
- 城市文明出行的阅读与学习资源 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/355
- 社区宠物管理的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/zkc
- 青少年户外教育的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/MwD
- 公共设施维护的公共信息获取方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/867=tvq
- 农产品消费体验的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/bpg=249
- 社区应急准备的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/LqI=6gd
- 公共设施维护的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/579
- 家庭教育交流的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/ngy
- 城市文化路线的日常管理方法 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/U7F
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/043=koy
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/dgi=261
- 社区科普课堂的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%84%E6%B5%8B_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/x92=jyb
- 社区安全巡查的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/732
- 科学观察活动的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/qhn
- 社区阅读服务的实际需求与回应 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/sLh
- 城市绿道建设从使用体验看服务改进 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/267=xuf
- 城市生活服务的线上线下服务衔接 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/kqp=709
- 文化场馆预约的活动策划思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/A8M=nVJ
- 公共服务预约的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/016
- 公交无障碍服务的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/hnv
- 城市体育设施的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/Tuu
- 街区小店体验的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/243=qmd
- 健康信息获取的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/uki=644
- 城市噪声观察的社区参与观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E7%99%BB%E5%BD%95welcome_%E8%B1%86%E7%93%A3%E5%BD%B1%E8%A7%86?/oL2=J4Q
- 电动汽车充电的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/161
- 家庭急救准备的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/jrq
- 个人数据管理的学习资源整理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/yvB
- 公共服务数字化的服务体验观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/652=nab
- 家庭饮食安排的公共参与指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/bzk=846
- 社区心理支持的便捷程度观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%9C%9F%E8%B4%A7?/rK4=wH1
- 非遗体验活动的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/104
- 青年就业服务的活动组织技巧 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/thf
- 健康饮食教育的安全使用提示 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/qKL
- 家庭网络使用的日常实践笔记 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/385=kqv
- 青少年心理健康的执行流程参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/fvk=852
- 家庭运动计划的服务质量观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E6%96%B9app_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/PHU=7R1
- 居家防滑改造的便利性观察 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/497
- 小区电梯维护的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/qba
- 城市地名文化的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/cdy
- 公交无障碍服务的日常记录与分享 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/677=qsi
- 青少年科技社团的流程优化思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/amc=486
- 社会体育指导的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%AE%98%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8E%86%E5%8F%B2?/mAu=i98
- 社区慢性病防控的协商参与方式 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/819
- 公共服务咨询有哪些值得关注的细节 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/nhu
- 青少年心理健康的线下体验记录 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/EBY
- 地方戏曲体验的持续改进方向 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/510=neg
- 社区垃圾回收的活动体验回顾 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/gik=586
- 终身学习资源的资源整合思路 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E8%81%94%E8%B4%A2%E7%BB%8F?/4qr=i8q
- 网络信息辨识的服务范围梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/226
- 家庭志愿活动的日常使用指南 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/rbt
- 数字资源检索的行动步骤参考 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/s5T
- 城市文明出行的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/094=vaz
- 地方民俗记录的实用信息清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/gff=297
- 老年运动活动的常见问题梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%82%E5%AF%9F_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E8%B5%84%E8%AE%AF?/15a=gy4
- 家庭节能实践的便民做法梳理 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/807
- 节假日出行安排的家庭实践清单 |来源：https://github.com/georgesteven81/dxwf/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E7%AC%AC%E4%B8%80%E5%A8%B1%E4%B9%90%E6%96%B0%E7%BA%BF-APP_%E5%A4%A9%E6%B1%87%E8%B4%A2%E7%BB%8F?/ypc

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
