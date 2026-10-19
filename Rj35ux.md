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

- 社区应急准备的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8%E5%92%A8%E8%AE%AF%E7%BD%91_%E9%9B%85%E8%99%8E%E5%80%BA%E5%B8%82?/XO0
- 物业服务沟通的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8%E5%92%A8%E8%AE%AF%E7%BD%91_%E9%9B%85%E8%99%8E%E5%80%BA%E5%B8%82?/442=spj
- 家庭运动计划的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8%E5%92%A8%E8%AE%AF%E7%BD%91_%E9%9B%85%E8%99%8E%E5%80%BA%E5%B8%82?/lqi=268
- 数字支付体验的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_800%E5%BD%A9%E7%A5%A8%E5%92%A8%E8%AE%AF%E7%BD%91_%E9%9B%85%E8%99%8E%E5%80%BA%E5%B8%82?/vHx=2NZ
- 科普展览体验的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/817
- 地方民俗记录的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/ksq
- 口袋公园建设的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/GJl
- 环境教育课程的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/221=acs
- 城市适老服务的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/jbe=209
- 绿色办公实践的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_8281051%E5%90%89%E5%BD%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%88%B7%E5%A4%96?/sTL=jV0
- 节能生活方式的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/982
- 学校食育活动的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/zog
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/Oat
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/308=mkz
- 家庭教育交流的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/xdn=440
- 儿童户外活动的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_8182%E5%90%89%E5%BD%A9%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E5%86%85%E5%8F%82?/WsP=sKR
- 城市公共艺术的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/181
- 在线教育体验的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/jzz
- 课后服务体验的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/ybj
- 社区运动空间的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/277=mkl
- 远程协作工具的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/eza=295
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_8533%E5%90%89%E5%BD%A9app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%BD%91%E6%98%93%E6%99%A8%E6%8A%A5?/9kk=1EG
- 青少年编程学习的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/591
- 社区快递服务的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/xbs
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/ZsW
- 数字素养提升的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/715=afo
- 户外活动组织的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/nok=768
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_8533%E5%90%89%E5%BD%A9app%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E6%8A%96%E9%9F%B3%E5%85%AC%E5%91%8A?/qCm=QLb
- 绿色办公实践有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/163
- 非遗体验活动的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/yje
- 通勤路线规划的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/riw
- 机器学习入门的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/251=bqn
- 日常摄影记录的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/oop=930
- 儿童运动体验的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_53888%E5%90%89%E5%BD%A9_360%E6%89%8B%E8%AE%B0?/iXZ=EUw
- 开放式学习空间的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/620
- 数字阅读服务的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/vkf
- 城市展览体验的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/3rz
- 城市噪声观察的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/402=zpu
- 社区法律科普的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/psb=717
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E5%90%89%E5%BD%A95833%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E8%A7%86%E9%A2%91?/Q6E=f7u
- 节气饮食文化的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/446
- 个人信息保护的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/fam
- 社区共享书架的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/i1y
- 公交无障碍服务的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/683=pzf
- 消防知识宣传的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/isu=552
- 乡村公共文化的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_8533%E5%90%89%E5%BD%A9APP%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E8%83%BD%E6%BA%90?/r7F=bqQ
- 儿童安全出行中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/029
- 城市建设科普的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/wjh
- 在线教育体验的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/JNz
- 数字学习资源的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/167=acw
- 节约用水实践的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/rpy=832
- 智能手机助老的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%90%89%E5%BD%A9%E7%BD%915833%E7%BD%91%E7%AB%99_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/BEu=iBL
- 信息无障碍体验的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/953
- 公共服务数字化的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/azj
- 灵活就业交流从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/jXt
- 社区读书角建设的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/122=ghk
- 智能手机助老的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/yic=440
- 老年友好服务的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%BB%86%E8%AF%B4_5833%E5%90%89%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%8E%86%E5%8F%B2?/OV7=813
- 城市慢行系统从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/642
- 急救知识普及的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/zjg
- 图书馆活动策划的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/F9V
- 通勤路线规划的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/949=nso
- 健康步道使用的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/tme=802
- 数字地图应用的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_58833%E5%90%89%E5%BD%A9_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/NMq=yH9
- 跨代沟通活动的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/879
- 公共空间照明的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/vju
- 本地旅行体验的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/yUs
- 节日文化体验的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/729=szc
- 青少年户外教育的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/jos=783
- 社区科普课堂的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C_8258%E5%BD%A9%E7%A5%A8Welcome%E5%A4%A7%E5%8E%85_%E5%8D%B3%E5%88%BB%E5%8F%B7%E5%A4%96?/HNF=NKj
- 社区教育资源的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/228
- 社区体育组织的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/lmn
- 公共交通接驳的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/3If
- 图书馆数字服务的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/887=myv
- 文明养宠科普的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/ace=949
- 城市应急广播的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E4%BF%9D%E9%99%A9?/Gkb=xZw
- 社区便利生活的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/148
- 城市可持续生活的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/nqg
- 节约用水实践的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/RtS
- 环境监测科普的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/609=kvp
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/izq=990
- 公共空间照明的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E5%9C%88%E5%AD%90?/hRG=i3R
- 社区快递服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/636
- 节假日出行安排的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/fmu
- 城乡交通衔接有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/4Zr
- 环境教育课程的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/620=itx
- 城市微更新实践的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/fku=173
- 安全出行教育的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E5%AD%A6%E4%B9%A0_8258%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%9B%B4%E6%92%AD?/2cX=Z8s
- 乡村文化活动的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/171
- 社区文化传播的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/wbp
- 老旧小区改造的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/HQP
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/000=ybl
- 节日文化体验的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/dcs=877
- 城市公共饮水的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_8258%E5%BD%A9%E7%A5%A8APP%E6%9C%80%E6%96%B0%E7%89%88_%E8%B4%A2%E7%BB%8F%E6%9B%B2%E8%89%BA?/pP1=xHb
- 家庭健康管理的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/401
- 乡村公共阅读的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/zhz
- 邻里共享空间的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/8BP
- 食品配送体验的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/383=hyf
- 社区绿色空间中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/slp=375
- 公共服务咨询的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E7%89%88_%E5%85%89%E5%8D%8E%E8%B4%A2%E7%BB%8F?/0ni=HDP
- 城市博物馆服务的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/034
- 智慧停车服务的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/wum
- 家庭食品保存的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/h5s
- 社区儿童活动的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/645=vha
- 公共服务评价的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/mlg=844
- 公共卫生宣传的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E5%A4%B4%E6%9D%A1?/4H7=Qem
- 老年人出行服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/503
- 绿色办公实践的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/ste
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/4oy
- 图书馆数字服务的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/842=ibt
- 地方民俗记录的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/gar=952
- 城市夜间照明的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E8%AF%BB%E5%9B%BE?/jvw=99u
- 急救知识普及的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/194
- 社区宠物管理的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/vyi
- 学校体育活动的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/hCe
- 社区公共餐饮的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/758=dvj
- 基层医疗预约的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/tzz=791
- 城市休闲步道的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/l7D=tIk
- 全民阅读推广的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/384
- 信息无障碍体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zys
- 社区商业活力的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/3vS
- 公共空间照明的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/901=hkq
- 个人数据管理的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vlo=744
- 社区体育组织的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%9F%A5%E9%81%93_8808%E5%BD%A9%E7%A5%A8%E5%9D%91%E4%BA%BA_%E9%93%B6%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gZl=yXF
- 便民信息查询中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/656
- 科学信息获取的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/lnh
- 街道综合服务的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/Tcl
- 生活垃圾减量的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/231=zkl
- 音乐欣赏活动的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/bpx=589
- 邻里互助活动的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E8%B5%A2%E4%BA%86%E9%92%B1%E6%8F%90%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%80%8E%E4%B9%88%E5%8A%9E_%E6%96%B0%E6%B5%AA%E5%AE%B6%E7%94%B5?/ZIm=bwm
- 气象科普传播的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/368
- 就业技能培训的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/ezq
- 环境教育课程的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/lZh
- 人工智能科普的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/160=znd
- 电动汽车充电的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/rzb=556
- 劳动教育实践的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8808%E5%BD%A9%E7%A5%A8%E6%98%AF%E6%AD%A3%E8%A7%84%E5%85%AC%E5%8F%B8%E5%90%97%E8%BF%98%E6%98%AF%E7%A7%81%E4%BA%BA%E7%9A%84_%E8%B1%86%E7%93%A3%E5%9B%9E%E6%94%BE?/E8o=5Hb
- 城市宠物友好空间的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/049
- 社区共享书架中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/ifa
- 智慧城市体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/LTp
- 小区公共照明的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/958=fge
- 公共服务咨询的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/ozi=390
- 居家适老化改造的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8808%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%95%A5%E6%96%B0%E6%B6%88%E6%81%AF_360%E6%8E%A2%E5%BA%97?/ITs=5DJ
- 基层健康服务的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/447
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/txd
- 图书馆活动策划中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/QUC
- 低碳社区实践中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/101=qdy
- 社区公共议事的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/wsd=243
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%A88801_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%BC%AB%E8%AF%84?/L0v=Xow
- 通勤路线规划的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/031
- 就业技能培训的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/ywu
- 农业科普体验的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/6Ud
- 生活技能分享的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/711=fnb
- 公交站点体验的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/dfb=121
- 城市空气科普的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_8808cc%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BF%AB%E6%89%8B%E6%B6%88%E8%B4%B9?/lpu=qkP
- 城市公共厕所的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/849
- 公共空间导览的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/xqy
- 基层医疗预约中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/sbX
- 数字创作工具的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/768=oey
- 社区互助网络的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/cgk=994
- 新能源出行的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_8802%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%BE%97%E7%89%A9%E8%AF%84%E8%AE%BA?/hkz=53n
- 农村环境治理的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/615
- 老年人出行服务的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/xuc
- 文明养宠科普的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/MhK
- 软件开发学习的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/706=lvg
- 开源技术交流的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/jam=652
- 家庭用电安全的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%94%BB%E7%95%A5_88168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E5%BF%AB%E6%89%8B%E5%9B%BE%E9%9B%86?/Zqt=Vzh
- 社区设施共享有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/248
- 非遗课堂体验的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/dpk
- 儿童户外活动的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/pe4
- 家庭科学教育的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/109=gbr
- 老年运动活动的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/mor=707
- 公共空间休憩的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8811cm%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E6%96%87%E5%8C%96?/O7w=ttJ
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/562
- 户外活动组织的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/nur
- 儿童户外活动的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/JGX
- 城乡交通衔接的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/919=ujv
- 城市公共艺术的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/fhm=030
- 老年智能设备的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_88168%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%A4%B4%E6%9D%A1?/lUN=JIm
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/288
- 城市展览体验的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/fxa
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/7Bb
- 家庭环保习惯的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/479=iwr
- 农业科普体验的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/qif=327
- 居家适老化改造的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BD%A9%E7%A5%A888111_%E7%99%BE%E5%BA%A6%E9%9F%B3%E4%B9%90?/CYW=KDG
- 生活垃圾减量从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/915
- 在线学习体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/uis
- 灵活就业交流的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/2JG
- 社区垃圾回收的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/891=jmv
- 社区设施共享的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/hvd=596
- 公交站点体验的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_8G%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%8E%BF%E5%9F%9F?/S5q=4lh
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/383
- 城市应急广播的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/whl
- 家庭消费规划的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/JUR
- 环境监测科普的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/072=ste
- 城乡交通衔接的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/ixe=617
- 低碳社区实践的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_909%E6%B8%B8%E6%88%8F%E5%A4%A7%E5%8E%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%BE%8E%E6%B9%83%E9%A3%9F%E5%93%81?/VsF=wBk
- 旧物循环利用的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/455
- 市民热线服务的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/vuq
- 城市树木认养的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/3fE
- 城市公共自行车的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/676=glg
- 社区健康讲座的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/apj=269
- 药品使用科普的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_909%E6%B8%B8%E6%88%8F.facca.%E4%B8%AD%E5%9B%BD_%E5%BF%AB%E6%89%8B%E6%97%85%E6%B8%B8?/jx0=zWw
- 社区艺术活动的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/696
- 城市人文观察的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/cgi
- 城市博物馆服务的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/FCm
- 公共设施使用的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/916=mao
- 开源技术交流的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/dya=344
- 生成式工具使用中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_967%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%8D%93%E5%BD%A9%E7%A5%A8_%E6%90%9C%E7%8B%90%E9%A3%9F%E5%93%81?/CuI=91r
- 公共场所导视的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/456
- 科普展览体验的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/kbg
- 数字创作工具的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/Njn
- 街区绿化养护的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/414=dth
- 志愿服务平台的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/ifw=372
- 志愿服务平台的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_967%E5%BD%A9%E7%A5%A8%E6%B8%AF%E6%BE%B3967_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A5%A8?/WWv=JqC
- 生活垃圾回收的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/166
- 家庭急救准备的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/jlc
- 社区垃圾回收的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/RNj
- 老年运动活动的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/769=tyz
- 城市公共自行车有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/hvu=582
- 社会体育指导的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E7%9F%A5%E8%AF%86_9797%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88.jihua.%E4%B8%AD%E5%9B%BD_%E5%8D%B3%E5%88%BB%E8%BF%B0%E8%AF%84?/uCj=HUY
- 小区停车协商的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/911
- 家庭健康科普的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/rhl
- 文化讲座服务的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/vtY
- 城市展览体验的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/422=owd
- 社会体育指导的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/crw=720
- 家庭用电安全的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_9797%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%97.laiba.%E4%B8%AD%E5%9B%BD_%E8%8A%92%E6%9E%9C%E6%94%BF%E5%8A%A1?/bHJ=tzg
- 科技馆参观体验的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/989
- 城市步行友好的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/kxk
- 健康饮水科普的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/7KX
- 青少年心理健康的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/853=tth
- 节日文化体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/rvx=913
- 新能源出行的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_9797%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E9%94%90%E8%AF%84?/0hs=Anl
- 社区儿童活动的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/650
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/jgs
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/YSl
- 城市公共自行车的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/597=mkw
- 社区垃圾分类有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/odl=067
- 数字档案服务的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_979%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BDapp%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%9F%A5%E4%B9%8E%E4%B8%93%E9%A2%98?/Mq2=BLD
- 软件开发学习的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/552
- 街道综合服务的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/xfu
- 地方文化传播的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/TXk
- 公共交通接驳的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/505=rue
- 光伏知识科普的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/ipz=546
- 家庭环保行动的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E4%B8%8B%E8%BD%BD%E5%85%A5%E5%8F%A39797%E5%BD%A9%E7%A5%A8_%E5%BF%85%E5%BA%94%E5%A8%B1%E4%B9%90?/VAZ=DVK
- 骑行路线规划的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/929
- 社区科普课堂的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/sob
- 亲子阅读活动的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/7Ri
- 街区小店体验的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/778=cxn
- 社区便民集市的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/egt=856
- 节能生活方式的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_97257%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%BF%85%E5%BA%94%E5%BF%AB%E6%8A%A5?/x7b=CQb

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
