# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 数字创意课程的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/583
- 学校体育活动的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/dff
- 公共文化活动的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/EvH
- 绿色出行服务的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/421=mfm
- 社区商业活力的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/rog=162
- 城市建设科普的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%9F%A5%E4%B9%8E%E8%AF%BB%E5%9B%BE?/CIc=eeP
- 邻里共享空间的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/638
- 节能生活方式的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/vxz
- 农村环境治理的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/CAd
- 智能手机助老的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/476=wqr
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/fkw=842
- 家庭饮食安排的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9app_%E7%99%BE%E5%BA%A6%E6%AF%8D%E5%A9%B4?/OR3=VjA
- 邻里互助活动的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/393
- 旧物循环利用的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/cyq
- 科学信息获取的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/O4k
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/202=fpe
- 终身学习资源的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/jfb=777
- 社区活动空间的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/SBS=lCE
- 老年人出行服务的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/207
- 社区文化传播的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/njj
- 低碳社区实践的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/XUk
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/214=pqn
- 志愿者培训交流的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/evj=382
- 农产品品牌传播中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%96%B0%E9%97%BB?/I90=tQP
- 家庭健康管理的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/448
- 本地历史资料的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/bbn
- 老年学习活动的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/PD5
- 老旧小区改造的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/091=xtp
- 公共空间休憩的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/xxe=890
- 社区学习活动的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E4%B8%8B%E8%BD%BD_%E4%B8%AD%E8%AF%9A%E8%B4%A2%E7%BB%8F?/A7g=5KM
- 家庭安全提示的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/537
- 数据分析入门的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/syz
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/xIf
- 日常摄影记录的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/323=bjz
- 传统节日科普的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/mrz=184
- 公益活动组织有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%86%9B%E4%BA%8B?/lUR=cfQ
- 社区活动策划的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/046
- 儿童友好空间的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/hqx
- 青年就业服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/kcm
- 城市雨天出行的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/558=amo
- 社区便民集市的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/how=803
- 无障碍信息设计的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E8%AF%84%E8%AE%BA?/HsE=gCb
- 科技馆参观体验的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/780
- 全民健身活动的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ogx
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/ue0
- 老年人出行服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/719=dxx
- 乡村文化空间的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/zen=847
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E8%AF%BB%E6%8A%A5?/rpj=wVA
- 居家适老化改造的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/619
- 科技馆参观体验的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/syp
- 地方戏曲体验的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/i0V
- 节能家电使用的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/490=qlm
- 街道综合服务的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/chs=247
- 邻里互助活动的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E6%89%8B%E8%AE%B0?/C5y=YuQ
- 儿童阅读角的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/845
- 社区垃圾回收的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/eim
- 科学观察活动的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/oh4
- 节假日出行安排的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/840=kuo
- 儿童运动体验的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/rip=963
- 青少年户外教育的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%B3%A8%E5%86%8C_%E9%9B%85%E8%99%8E%E6%8A%95%E8%B5%84?/bNA=mOK
- 数字艺术创作的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/405
- 城市绿道建设的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/jod
- 数字创作工具的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/xCD
- 节约用水实践有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/172=xpz
- 社区便民集市的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/hzi=247
- 基层健康服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/K95=Sxo
- 城市体育设施的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/595
- 骑行路线规划的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/cim
- 儿童运动体验从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/gfw
- 城市文化路线的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/873=xfg
- 城市公共艺术的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/cuq=117
- 社区志愿服务的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_36%E6%B0%AA%E6%94%BF%E5%8A%A1?/Q58=KQ8
- 绿色快递包装的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/079
- 在线学习体验的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/osw
- 科学睡眠习惯的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/wMP
- 社区体育组织的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/471=fcf
- 社区儿童活动的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/fjk=996
- 社区艺术活动的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E7%BE%8E%E8%82%A1?/Sxe=ThX
- 社区托育服务的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/681
- 乡村文化空间的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/wng
- 社区活动空间的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/xCo
- 便民服务窗口的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/054=jgk
- 家庭急救准备的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/pke=242
- 社区公共餐饮有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%94%BF%E5%8D%8F?/CHq=vE0
- 家庭陪伴活动的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/625
- 城市便民驿站的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/pxo
- 公共文化活动的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/Mil
- 城市步行环境的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/368=mpg
- 乡村电商实践的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/wyc=740
- 城市步行友好的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%A0%8F%E7%9B%AE_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%90%E6%97%A5%E6%8A%A5?/Mxo=SrS
- 儿童安全出行的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/140
- 信息无障碍体验的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/aic
- 周末休闲规划的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/oEs
- 非遗体验活动的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/653=ewb
- 环境教育课程的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/lox=685
- 数字支付体验的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/1PM=Gi8
- 软件开发学习的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/548
- 家庭环保习惯的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/xkk
- 传统手工艺体验的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/a5v
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/334=xix
- 公共空间照明的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/omz=795
- 全民阅读推广有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/Kks=Pmf
- 公共交通信息服务的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/567
- 城市可持续生活的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/svs
- 公共设施维护的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/rD7
- 开放式学习空间中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/637=nnp
- 家庭网络使用的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/jsa=197
- 公共健身器材的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E5%86%9C%E4%B8%9A?/HW8=zdP
- 儿童安全出行的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/716
- 在线教育体验的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/ghs
- 乡村产业科普的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/CIk
- 公共服务数字化的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/527=vdn
- 音乐欣赏活动的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/heo=736
- 数字创意课程的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/RpH=g10
- 青少年职业启蒙的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/045
- 城市绿色交通的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/ovx
- 家庭网络使用的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/KIJ
- 老年学习活动的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/489=bhx
- 社区交通安全的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/lfi=264
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%A4%AE%E8%A7%86%E5%9B%BD%E5%86%85?/3b9=hqd
- 食品安全科普的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/985
- 公共文化活动的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/sty
- 节气饮食文化的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/krI
- 电子商务服务的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/453=cgi
- 社区公共餐饮的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/qsb=367
- 灵活就业交流的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E8%A1%8C%E6%83%85?/d3w=NMt
- 家庭网络使用的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/040
- 城市夜间照明的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/eas
- 节假日出行安排的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/w9p
- 无障碍出行的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/997=rtw
- 公共卫生宣传的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/spo=308
- 智能家居应用的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95welcome_%E8%8A%92%E6%9E%9C%E7%99%BE%E7%A7%91?/Sjw=Zpa
- 青年职业探索的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/265
- 城市公共座椅的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/bcd
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/Zpb
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/273=unq
- 亲子科普活动的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/fyl=549
- 非遗体验活动的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%B4%E6%9D%A1%E6%B3%95%E6%B2%BB?/krX=fmm
- 老年人日常照护的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/656
- 便民服务地图的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/edo
- 城市游园体验的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/sku
- 科学教育活动的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/799=oio
- 绿色办公实践的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/slo=499
- 本地消费场景的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9app_%E5%BF%85%E5%BA%94%E6%94%BF%E7%AD%96?/UTH=udd
- 城市便民驿站的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/718
- 居民健康教育的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/svh
- 社区读书角建设的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/9Tr
- 节日文化体验从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/875=vge
- 老年学习活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/rce=530
- 数字地图应用的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/Upn=LF4
- 家庭阅读计划的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/029
- 公共交通接驳的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/dsv
- 家庭环保习惯的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/6VQ
- 青年志愿活动的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/810=glk
- 环境教育课程的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/gme=036
- 数字便民地图的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%90%E6%94%BF%E5%8A%A1?/ZC4=w2K
- 城市博物馆服务的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/506
- 个人时间管理中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/tri
- 数字设备回收有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/Cy7
- 城市人文观察的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/053=kvb
- 城市博物馆服务的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/any=718
- 生活服务数字化的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E4%B8%8B%E8%BD%BD_360%E5%88%B8%E5%95%86?/Aol=OXc
- 公共空间导览的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/121
- 公共服务预约的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/hbu
- 食品安全科普的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/v8Y
- 周末休闲规划的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/860=hph
- 节假日出行安排的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/mce=775
- 绿色消费选择的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/OQB=xOu
- 城市共享单车的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/425
- 数字政务体验的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/wzw
- 全民健身活动的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/RtQ
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/562=ski
- 科学教育活动的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/cxd=579
- 家庭陪伴活动的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E4%BA%BA%E7%89%A9?/iYE=zhq
- 学校体育活动的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/623
- 城市人文观察的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/iti
- 城市文明出行的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/7et
- 公园亲子设施的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/562=vdk
- 老年友好服务的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ryr=881
- 数字设备回收的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/cEb=TvN
- 城市空气科普的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/179
- 城市社区治理的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/nhj
- 儿童户外活动的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/zPo
- 青年就业服务的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/665=sog
- 邻里共享空间的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/qyx=402
- 城市展览体验的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E7%99%BB%E5%BD%95_%E5%A4%AE%E8%A7%86%E4%BF%A1%E8%AE%BF?/i5x=cRH
- 社区知识分享的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/724
- 家庭网络使用的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/blh
- 创业经验分享的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/B6Y
- 家庭收纳实践的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/564=nld
- 居民健康教育的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/uzu=801
- 科学观察活动的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%B3%A8%E5%86%8C_%E6%BE%8E%E6%B9%83%E8%B4%A2%E7%BB%8F?/lrJ=xda
- 食品配送体验的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/888
- 居民健康教育的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/oub
- 数字档案服务中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/lxg
- 社区知识分享的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/486=wov
- 居家防滑改造的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/xsz=239
- 城乡公共服务的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E5%8E%BF%E5%9F%9F?/yI6=paX
- 网络信息辨识的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/312
- 就业技能培训的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/xco
- 老年运动活动的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/6be
- 地方文化传播的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/671=tqq
- 乡村电商实践的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/ozk=501
- 市民热线服务的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%8A%92%E6%9E%9C%E6%AF%8D%E5%A9%B4?/YrH=n7f
- 城市生活服务的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/042
- 安全出行教育的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/fpm
- 休闲运动入门的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/74o
- 邻里共享空间的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/647=fzt
- 生成式工具使用的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/lwb=263
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E5%9B%BD%E9%99%85?/ebQ=lpD
- 地方文化传播的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/635
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/kdv
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/lSS
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/813=ezn
- 街头绿植养护的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/alg=539
- 社区志愿服务的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8C%87%E5%AF%BC_%E5%BD%A9%E7%A5%A8%E7%AB%99-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_36%E6%B0%AA%E8%BF%B0%E8%AF%84?/N6N=32J
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/432
- 城市公共座椅的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/eqo
- 家庭节能实践的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/c1v
- 家庭阅读计划的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/560=uvi
- 新能源出行的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/usx=512
- 城市文明出行的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E9%A6%96%E9%A1%B5_%E5%A4%B4%E6%9D%A1%E7%99%BE%E7%A7%91?/cc3=QWQ
- 本地消费场景的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/735
- 城市应急广播有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/cxh
- 社区邻里服务的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/nVb
- 街区更新实践的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/089=rvj
- 公共场所导视的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/rcw=387
- 社区老年食堂的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%AB%99-%E5%AE%98%E6%96%B9_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/zcd=49l
- 校园阅读活动的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/356
- 青年职业探索的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/ezq
- 环境教育课程的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/2KR
- 生活垃圾回收的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/012=psc
- 小区公共照明的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/yso=170
- 社区便利生活的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%88%8A%E7%99%BB?/AN4=YUp
- 绿色校园实践的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/926
- 绿色建筑理念的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/rbj
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/XX6
- 社区交通安全的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/192=msa
- 零废弃生活尝试的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/enu=626
- 物业服务沟通的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%97%B6%E6%8A%A5?/YyM=O2G
- 校园安全教育的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/213
- 全民阅读推广的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/wsy
- 老年人日常照护的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/ujq
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/915=ujo
- 公共设施维护的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/eeb=019
- 家庭科学教育的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%8D%9A%E5%AE%A2?/yUJ=tri
- 社区运动空间的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/164
- 市民意见收集的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/nzs
- 公共设施维护的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/Xzp
- 社区文化传播中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E6%96%B0%E6%B5%AA%E7%BE%8E%E9%A3%9F?/211=zqd

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
