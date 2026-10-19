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

- 数字创意课程的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/zld=158
- 街区道路维护的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_985%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/O5w=dNa
- 城市宠物友好空间的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/573
- 儿童友好街区的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/qzp
- 信息无障碍体验的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/VJv
- 社区设施共享的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/459=ymy
- 开放数据应用的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/wxm=772
- 社区知识分享的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8A%96%E9%9F%B3%E9%9F%B3%E4%B9%90?/GwE=0dQ
- 城市夜间生活的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/583
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/ryt
- 绿色快递包装的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/xK0
- 劳动教育实践的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/501=oty
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/ckd=108
- 本地消费场景的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%86%E8%AF%B4_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E4%BD%93%E8%82%B2?/23b=Swz
- 骑行路线规划的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/262
- 乡村休闲旅游的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/pkw
- 城市树木认养的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/U81
- 家庭照护支持的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/546=mzu
- 邻里互助活动的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/sij=530
- 公共场馆服务的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%B9%9D%E5%B7%9E%E8%B4%A2%E7%BB%8F?/rBA=5R0
- 社区健康讲座的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/693
- 市民热线服务的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/vlx
- 基层健康档案的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/uY0
- 便民服务地图的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/788=dol
- 儿童友好空间的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/kiu=211
- 乡村教育资源的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BA%AC%E4%B8%9C%E8%88%86%E6%83%85?/dIN=we9
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/903
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/rbe
- 数字创意课程的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/tz4
- 全民健身活动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/378=cvr
- 绿色生活实践的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/zhk=019
- 新能源知识普及的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_985%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%B3%95%E6%B2%BB?/BWi=Ypn
- 健康步道使用的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/890
- 城乡交通衔接的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/eow
- 志愿者培训交流的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/yyJ
- 节日文化体验的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/913=ita
- 地方民俗记录的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/kpd=517
- 家庭用电安全的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E8%A7%84%E5%88%92_985%E5%BD%A9%E7%A5%A8-APP_360%E5%91%A8%E6%8A%A5?/ixa=eSu
- 社区菜市场服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/506
- 日常摄影记录的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/qwm
- 图书馆活动策划的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/V0b
- 小区停车协商的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/599=qph
- 社区协商议事的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/lmv=858
- 乡村电商实践的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_985%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E6%BE%8E%E6%B9%83%E6%9B%B2%E8%89%BA?/zD0=6KF
- 社区应急准备的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/058
- 公共交通信息服务的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/pum
- 家庭急救准备的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/2t9
- 低碳社区实践的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/630=dfx
- 城市公共厕所的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/pib=364
- 城市建设科普的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/ygf=i2g
- 课后服务体验的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/477
- 基层健康服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/sgp
- 垃圾分类指导的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/zt2
- 社区便利生活的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/230=nxu
- 物业服务沟通的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/nfn=512
- 社区信息发布的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%96%B0%E6%B5%AA%E6%BC%AB%E8%AF%84?/71r=Wk7
- 小区停车协商的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/059
- 城市体育设施的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/eqx
- 地方旅游导览的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/ZMx
- 公共卫生宣传的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/129=eax
- 公共场所导视的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/joq=865
- 开放数据应用的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_985%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E6%8E%A2%E6%BA%90?/4FN=2zC
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/631
- 电子商务服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/tkz
- 科学信息获取的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/Yzr
- 社区读书角建设从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/496=lkm
- 老年人日常照护的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/qgj=716
- 生活服务数字化的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E5%9F%BA%E9%87%91?/jZM=Xf3
- 老年人出行服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/924
- 公共空间安全的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/jdg
- 社区邻里服务的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/ESR
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/498=rbh
- 农业科普体验的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/kud=867
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_985%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E9%80%9F%E8%A7%88?/whk=n82
- 城市步行友好的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/906
- 环境教育课程的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/jvv
- 小区电梯维护的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/PRd
- 城市便民驿站的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/635=awb
- 社区宠物管理的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/adj=578
- 零废弃生活尝试的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_985%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E5%86%9C%E4%B8%9A?/mJN=0T5
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/067
- 开源技术交流从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/xip
- 城市树木认养的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/ZHp
- 城市绿道建设的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/012=mmn
- 文化讲座服务中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/wis=297
- 邻里共享空间的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_985%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%88%86%E6%96%99?/3JQ=JTW
- 绿色出行服务的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/005
- 街道综合服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/wdu
- 骑行路线规划的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/ard
- 青年就业服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/670=uhb
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/foa=950
- 城市便民驿站的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_985%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E7%A8%BF?/dKH=gce
- 科学教育活动的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/434
- 基层医疗预约的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/wcj
- 社区艺术活动的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/07E
- 居民健康教育的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/283=cny
- 科学观察活动的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/wxe=370
- 健康饮水科普的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%9C%88%E5%AD%90?/7g9=IWK
- 数字公共文化的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/728
- 数字学习资源的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/acz
- 城市公共饮水的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/jvt
- 家庭网络使用的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/840=rfz
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/ozu=530
- 城市基础设施的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%80%9A%E6%8A%A5_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%B9%B6%E8%B4%AD?/OGs=RXd
- 小区停车协商的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/026
- 城乡交流活动的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/okw
- 社区手工活动的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/64D
- 志愿服务平台的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/326=sjh
- 个人信息保护的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/vxe=881
- 老年运动活动的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%99%8E%E6%89%91%E5%9B%9E%E6%9C%9B?/L32=liG
- 个人数据管理的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/119
- 在线教育体验的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/nrb
- 信息无障碍体验的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/KIM
- 青少年科普实践的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/641=cjk
- 老年人文化生活的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/ynb=559
- 城市公共艺术的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E6%96%B0%E6%B5%AA%E7%BE%8E%E5%A6%86?/WQX=JWg
- 社区公共卫生的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/285
- 儿童阅读角的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/puc
- 图书馆活动策划的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/q1H
- 公共场所导视的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/144=rqp
- 科学健身方法的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/bnh=678
- 青年志愿活动的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%88%B1%E5%A5%87%E8%89%BA%E7%BE%8E%E5%A6%86?/3Mb=1Ch
- 药品使用科普的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/249
- 非遗体验活动的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/hxl
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/G2h
- 在线学习体验的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/393=ogt
- 乡村休闲旅游的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/zbu=204
- 城市文明出行的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%85%AC%E7%9B%8A?/sM1=EYa
- 节能生活方式的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/995
- 城市公共自行车的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/qra
- 垃圾分类指导的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/Pb1
- 网络安全教育的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/819=kqf
- 社区养老服务的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/dyn=462
- 城市公共饮水的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B3%95%E5%BE%8B?/cE7=Zz1
- 城市文明实践的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/670
- 家庭消费规划的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/fgg
- 跨代沟通活动中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/iar
- 老年学习活动的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/399=pnc
- 老年友好服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/fss=904
- 城市公共标识的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AD%A6%E4%B9%A0_987%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%BD%E8%BD%A6?/Oep=YvD
- 乡村产业科普的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/342
- 公交无障碍服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/ovf
- 家庭急救准备的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/f9B
- 就业技能培训的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/567=bjm
- 健康饮水科普中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/hvr=143
- 便民服务地图的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_987%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E8%B4%A2%E7%BB%8F?/udp=jS3
- 公共服务数字化的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/710
- 数字政务体验的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/szk
- 环境监测科普的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/nWI
- 社区生活指南的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/424=wip
- 社区修缮行动的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/pxz=503
- 社区知识分享的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%83%AD%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-APP_%E6%B7%B1%E5%BA%A6%E8%B4%A2%E7%BB%8F?/7iM=yX9
- 绿色校园实践的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/438
- 老年友好服务的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/zai
- 创业经验分享的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/ttK
- 社区共享书架的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/289=squ
- 居家防滑改造的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/zki=990
- 城市地名文化的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_987%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%88%8A%E7%99%BB?/us5=dbx
- 数字设备回收的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/904
- 医院导诊服务的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/afm
- 数字艺术创作的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/2Ai
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/897=etm
- 光伏知识科普的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/koo=181
- 亲子阅读活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E6%92%AD%E6%8A%A5?/1IL=lIe
- 本地消费场景的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/154
- 城市宠物友好空间的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/iss
- 基层服务创新的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/KpO
- 地方美食文化的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/458=wvy
- 本地历史资料的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/pok=570
- 社区文化传播的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_987%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E8%A7%82%E5%AF%9F?/Q4o=Gnt
- 城市运动公园的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/686
- 职业技能学习的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/nmq
- 社区生活指南的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/Ci9
- 运动安全知识的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/689=hgb
- 老年数字阅读的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/eda=211
- 老年智能设备的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E8%B5%84%E6%BA%90_987%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E8%85%BE%E8%AE%AF%E5%9C%B0%E6%96%B9?/3pi=5AC
- 家庭陪伴活动的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/663
- 校园安全教育的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/wzr
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/TzV
- 图书馆亲子空间中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/507=aet
- 公共交通接驳的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/zcj=932
- 市民意见收集的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_987%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%9C%B0%E4%BA%A7%E8%B4%A2%E7%BB%8F?/C30=hzS
- 志愿服务平台的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/686
- 家庭科学教育的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/rza
- 城市共享单车有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/UC5
- 街区绿化养护的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/716=osu
- 社区学习活动的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/nmt=054
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%93%94%E5%93%A9%E4%B8%93%E6%A0%8F?/zBt=QfO
- 非遗体验活动的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/568
- 城市公共座椅的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/jtm
- 社区垃圾分类的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/o6H
- 乡村教育资源的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/303=ndt
- 城市博物馆活动中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/net=956
- 社区商业活力的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_987%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%BD%A9%E7%A5%A8?/Qov=Uwg
- 城市雨天出行的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/718
- 开放数据应用的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/eqh
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/Ff6
- 城市适老服务的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/375=vgt
- 社区庭院绿化的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/dzg=471
- 老年人文化生活的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AE%AF?/Sc3=Fjb
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/564
- 环境监测科普的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/xxq
- 公共空间安全的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/q6u
- 数字便民地图的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/613=icc
- 文化遗产保护科普的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/wqu=595
- 城市基础设施的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_987%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%84%89%E8%84%89%E5%AE%9E%E5%BD%95?/4KB=mwE
- 应急物资管理的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/278
- 数字学习资源的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/aak
- 城乡交流活动的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/g8g
- 数字创作工具的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/482=ukd
- 电动汽车充电的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/eid=451
- 亲子科普活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_987%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%9F%A5%E4%B9%8E%E5%91%A8%E6%8A%A5?/Y4O=mMA
- 社会体育指导的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/232
- 校园社团活动的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/laa
- 智慧停车服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/BmC
- 地方美食文化的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/905=cna
- 学校体育活动的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/yjh=205
- 社区防暑服务的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E6%96%87%E6%91%98?/VHR=vHq
- 基层服务创新的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/156
- 乡村阅读活动的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/bqb
- 城市运动公园的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/AFa
- 学校体育活动的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/522=pzi
- 智能手机助老的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/yyv=969
- 青少年心理健康的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_987%E5%A8%B1%E4%B9%90-welcome%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/8uK=xp3
- 儿童友好空间的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/543
- 城市文化路线的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/weu
- 小区停车协商的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/jUZ
- 居民健康教育的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/894=msr
- 志愿服务平台的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/hen=280
- 科学信息获取的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/FM7=GF3
- 科学观察活动的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/204
- 非遗课堂体验的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/ydk
- 老年人出行服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/Jvh
- 老年人出行服务的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/822=eqh
- 社区商业活力的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/fly=627
- 在线教育体验的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_987%E5%A8%B1%E4%B9%90-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%BF%AB%E6%89%8B%E6%8A%95%E7%A8%BF?/GXH=oR6
- 青少年科技社团的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/751
- 亲子科普活动的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/ftk
- 城市建设科普的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/PWB
- 市民意见收集的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/764=ymt
- 绿色出行服务的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/tpz=392
- 城市住房服务的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E7%95%85%E6%B8%B8?/sgO=XoU
- 就业技能培训的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/355
- 基层健康档案的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/fxs
- 家庭阅读计划的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/s12
- 城市适老服务的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/676=msn
- 地方旅游导览从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/gfb=098
- 城市住房服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E4%BA%86%E8%A7%A3_987%E5%A8%B1%E4%B9%90-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%8C%96?/B1u=5Dz
- 亲子阅读活动的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/463
- 社区读书角建设的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_987%E5%A8%B1%E4%B9%90-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/xvm

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
