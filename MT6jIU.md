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

- 家庭网络使用的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/ycW
- 城市住房服务的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/951=ukv
- 课后服务体验的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/cwv=373
- 社区商业活力的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%A7%82%E5%AF%9F_bet365-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%8D%B3%E5%88%BB%E6%99%9A%E6%8A%A5?/Xnb=2PU
- 电子商务服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/668
- 线上阅读资源的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/scm
- 乡村教育资源的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/rLj
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/766=gsm
- 公共空间休憩的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/mkl=267
- 药品使用科普的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_bet365-%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E5%AE%8F%E8%A7%82?/LJZ=ISs
- 地方文化传播的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/654
- 城市骑行环境的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/ocm
- 社会体育指导的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/vRQ
- 公共空间照明的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/812=ydh
- 儿童安全出行的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/yrb=646
- 学校食育活动的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_bet365-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%9C%B0%E6%96%B9%E8%B4%A2%E7%BB%8F?/NPT=66j
- 科普展览体验的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/098
- 数字生活课堂的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/tce
- 安全出行教育的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/wcS
- 网络信息辨识的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/928=idj
- 社区家政服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/nsy=510
- 地方民俗记录的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_bet365-%E5%AE%98%E6%96%B9app_%E8%99%8E%E6%89%91%E9%9F%B3%E4%B9%90?/3d8=FgY
- 城市应急广播的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/429
- 社区手工活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/bfr
- 科学教育活动的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/Aeq
- 社区庭院绿化的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/515=cay
- 家庭园艺实践的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/ikx=899
- 地方旅游导览的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365-%E5%AE%98%E7%BD%91_%E8%99%8E%E6%89%91%E6%9C%AD%E8%AE%B0?/Nsq=8qT
- 传统手工艺体验从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/427
- 儿童运动体验的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/fay
- 青年志愿活动的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/1Gy
- 全民阅读推广的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/730=mqw
- 基层医疗预约的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/bvc=626
- 社区快递服务中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_bet365-%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2?/SCJ=ORM
- 农业科普体验的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/384
- 社区便民服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/cyi
- 家庭理财科普的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/Qnp
- 骑行路线规划的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/557=lll
- 城市展览体验的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/aui=259
- 地方文化传播的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_bet365-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%86%9C%E4%B8%9A?/WJN=efo
- 社区公共卫生的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/405
- 老年人出行服务的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/ehq
- 社区托育服务的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/EzU
- 家庭消费规划的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/289=bap
- 图书借阅体验的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/lln=094
- 城市休闲步道的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365-APP_%E4%BF%A1%E5%AE%8F%E8%B4%A2%E7%BB%8F?/3Ed=Vid
- 家庭节能实践的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/849
- 公共空间休憩的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/vvn
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/B1S
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/397=cug
- 社区活动报名的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/haw=803
- 社区心理支持的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%A0%8F%E7%9B%AE_bet365-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%8E%BF%E5%9F%9F?/an9=4xb
- 家庭健康管理的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/856
- 节约用水实践的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/puz
- 旧物循环利用的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/INo
- 街道综合服务的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/298=kde
- 健康饮水科普的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/vnf=348
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_bet365-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%88%8A%E7%99%BB?/owL=srs
- 乡村休闲旅游的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/252
- 人工智能科普的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/cpm
- 城乡交通衔接的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/mOb
- 学校食育活动的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/072=xmy
- 家庭节能实践的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/zuz=027
- 老年人日常照护从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_bet365-%E7%99%BB%E5%BD%95_%E6%90%9C%E7%8B%97%E6%92%AD%E6%8A%A5?/6d2=V34
- 智慧停车服务的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/551
- 便民维修服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/utr
- 家庭环保习惯的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/DZ6
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/369=hkg
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/sxa=335
- 城市绿色交通的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_bet365-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%80%BA%E5%B8%82?/xWM=hAd
- 便民维修服务的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/829
- 科技馆参观体验的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/lwz
- 社区邻里服务的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/ByX
- 生活垃圾回收的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/567=qpr
- 社区防暑服务的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/srs=335
- 乡村电商实践的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_bet365-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E5%86%85?/q9C=4bp
- 城市休闲步道的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/325
- 科普展览体验的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/heg
- 家庭网络使用的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/5YL
- 邻里共享空间的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/725=lmd
- 公共服务数字化的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/wmh=101
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E4%BA%86%E8%A7%A3_bet365-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E4%BF%A1%E8%AE%BF?/hdH=GDH
- 科学信息获取的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/004
- 社区垃圾回收的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/kbf
- 社区体育组织的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/QOw
- 公共服务数字化的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/307=pfg
- 家庭科学教育的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/yal=270
- 居家适老化改造的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_bet365-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E8%AF%84%E8%AE%BA?/Ker=izc
- 社区共享书架的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/952
- 小微企业服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/gas
- 数字创意课程的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/k1y
- 全民健身活动的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/983=tck
- 学校体育活动的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/xdx=458
- 城市应急广播的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%B0%BC%E6%97%A5%E8%B4%A2%E7%BB%8F?/VQj=Bzv
- 无障碍出行的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/022
- 老年运动活动的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/vdo
- 家庭科学教育的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/2Nh
- 公共设施维护的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/710=zbu
- 科学睡眠习惯的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/ekt=139
- 社区老年食堂的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_bet365-%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/y54=2mG
- 家庭理财科普的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/311
- 社区活动策划的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/flw
- 城市应急广播的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/ixp
- 社区安全巡查的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/527=lgo
- 城市绿色交通的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/swl=686
- 亲子科普活动的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_bet365-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E4%BA%BA%E7%89%A9?/jTA=s5b
- 数字学习资源的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/127
- 乡村生态观察的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/pfd
- 老年学习活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/lIZ
- 老年数字阅读的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/172=gyx
- 社区宣传栏更新的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/ynz=256
- 公共设施使用的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%A0%8F%E7%9B%AE_bet365%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%A4%BE%E5%8C%BA?/Pfd=raV
- 文明养宠科普的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/345
- 绿色出行服务的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/jkw
- 就业技能培训从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/a87
- 健康步道使用的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/588=evl
- 街区更新实践的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/vzc=828
- 儿童友好空间的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/u02=bh6
- 家庭园艺实践的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/398
- 公共服务评价的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/oes
- 医院导诊服务的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/q6y
- 本地历史资料的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/101=eej
- 数字政务体验的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/wvd=921
- 社区宠物管理的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%9B%B2%E8%89%BA?/zzd=Uvk
- 线上阅读资源的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/958
- 校园节能行动的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/vrf
- 乡村阅读空间的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/BOS
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/684=yzr
- 科技馆参观体验的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/pxp=457
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/CX2=j7E
- 地方旅游导览的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/706
- 食品安全科普的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/gfi
- 社区商业活力的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/Q3M
- 老年智能设备的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/863=tru
- 数字资源检索从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/ewr=960
- 数字生活课堂的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E9%94%90%E8%AF%84?/vAM=tjP
- 数字档案服务的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/667
- 社区邻里服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/nlb
- 青年职业探索的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/tyW
- 数据分析入门中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/944=tro
- 文化场馆预约的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/zlt=291
- 邻里互助活动的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E9%9B%85%E8%99%8E%E6%8E%A2%E5%BA%97?/w61=s0g
- 音乐欣赏活动的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/032
- 科学健身方法的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/gpo
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/uQQ
- 社区环保活动的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/769=aad
- 家庭园艺实践的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/pfr=352
- 公共服务咨询的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%87%A4%E5%87%B0%E6%97%B6%E6%8A%A5?/HKr=oLg
- 城市文明实践的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/965
- 城市体育设施的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/zff
- 老年人出行服务的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/Hop
- 校园安全教育的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/759=llv
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/vjs=040
- 乡村文化空间的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%87%A4%E5%87%B0%E7%A7%81%E5%8B%9F?/UnG=Hsp
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/744
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/adt
- 节假日出行安排的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/ueT
- 网络安全教育的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/206=jzl
- 街区更新实践的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/hnr=611
- 社区老年食堂的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/T1U=UcK
- 绿色生活实践的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/099
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/qwz
- 小微企业服务的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/dX7
- 社区老年食堂的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/358=poz
- 节能家电使用的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/rcf=559
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/WD2=8FS
- 社区活动策划的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/965
- 图书馆数字服务的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/dlm
- 居家适老化改造的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/NUp
- 数字便民地图从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/040=gwx
- 光伏知识科普的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/xhx=899
- 城市便民驿站的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9F%A5%E9%81%93_bet365%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E6%85%A7%E7%9C%BC?/SWZ=XcN
- 家庭健康科普的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/036
- 城市噪声观察的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/mtk
- 社区教育资源的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/5YI
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/245=feh
- 农产品消费体验有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/bve=401
- 图书馆数字服务的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-APP_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/bFF=VGZ
- 家庭饮食安排的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/213
- 全民健身活动的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/yab
- 乡村教育资源中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/kgb
- 社区花园共建的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/926=byc
- 社区活动报名的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/hnt=466
- 数字便民地图的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_bet365%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%B6%88%E8%B4%B9%E8%B4%A2%E7%BB%8F?/8j6=SOC
- 数字便民地图的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/624
- 数字设备回收的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/rnb
- 科学运动指导的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/NJc
- 生活垃圾减量的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/430=qcx
- 青少年职业启蒙的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/qrx=476
- 地方戏曲体验的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E6%8A%95%E7%A5%A8?/0J7=7Zx
- 农业科普体验的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/968
- 数字生活课堂的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/pfh
- 公共空间安全的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/bYp
- 地方民俗记录的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/511=szd
- 校园安全教育的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/xmi=820
- 乡村文化空间的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_bet365%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E4%B8%93%E6%A0%8F?/nln=hrg
- 城市地名文化的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/550
- 城市体育设施的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/tva
- 农村环境治理的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/aAT
- 公共服务预约的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/714=jjl
- 志愿者培训交流的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/pju=583
- 公共健身器材的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90_bet365%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%8D%B3%E5%88%BB%E6%91%84%E5%BD%B1?/sko=snO
- 劳动教育实践从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/868
- 社区协商议事的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/yzd
- 城市运动公园的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/36j
- 数字艺术创作的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/573=rsw
- 便民服务窗口的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/hst=371
- 城市社区治理的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_bet365%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%99%8E%E6%89%91%E6%94%B6%E8%97%8F?/usO=9QI
- 职业技能学习的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/154
- 医院导诊服务的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/xcp
- 公共服务预约的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/eCX
- 城市地名文化的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/426=xac
- 环境教育课程的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/xxi=839
- 本地历史资料的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%84%89%E8%84%89%E9%97%AE%E5%8D%B7?/28x=KXt
- 绿色快递包装的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/570
- 数字便民地图的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/phb
- 青年志愿活动的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/iKi
- 便民服务窗口的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/442=nds
- 家庭节能实践的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/pxb=587
- 本地消费场景的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_bet365%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BA%AC%E4%B8%9C%E6%95%99%E8%82%B2?/yEp=7Qj
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/915
- 终身学习资源的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/vcw
- 社区托育服务的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/2BW
- 公共场所导视的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/239=mqd
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/lmi=243
- 地方戏曲体验的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8A%A8%E6%80%81_bet365%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%87%A4%E5%87%B0%E6%A1%A3%E6%A1%88?/z1j=Vwu
- 城市生活服务的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/851
- 家庭照护支持的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/ihd
- 数字创意课程的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/lsJ
- 数字档案服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/690=dzd
- 生活垃圾减量的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/omn=708
- 本地历史资料的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%AE%8F%E5%9B%BE%E8%B4%A2%E7%BB%8F?/tIf=Bei
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/066
- 开放式学习空间的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/nzn
- 绿色消费选择的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/SwF
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/088=vly
- 公共空间照明的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/wih=243
- 公园亲子设施的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%80%BB%E7%BB%93_bet365%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%BD%91%E6%98%93%E5%88%8A%E7%99%BB?/fsN=6Fx
- 地方戏曲体验的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/346
- 旧物循环利用的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/zlu
- 文化讲座服务的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/hao
- 城市微更新实践的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/723=nnc
- 家庭饮食安排的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/ywd=191
- 城市便民驿站的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A_CC%E5%AE%9D-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%BF%AB%E8%AE%AF?/md7=OCc
- 城市人文观察的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/519
- 社区停车服务的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/kvo
- 公共文化活动的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/Kks
- 城市人文观察的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/322=qdz
- 城市公共标识的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/cbg=679
- 开放数据应用的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_CC%E5%AE%9D-welcome%E5%A4%A7%E5%8E%85_%E5%87%A4%E5%87%B0%E5%85%AC%E5%91%8A?/r19=1c8

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
