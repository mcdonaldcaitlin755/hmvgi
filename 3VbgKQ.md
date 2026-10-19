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

- 智能手机助老的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/713
- 生活垃圾回收的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/xcp
- 无障碍出行的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/Vp5
- 公共空间休憩的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/647=heq
- 公共设施维护中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/vws=396
- 街头绿植养护的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%8F%E9%AA%8C_cp288%E5%BD%A9%E7%A5%A8_%E5%A4%B4%E6%9D%A1%E6%94%B6%E8%97%8F?/9tW=lB6
- 线上阅读资源的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/557
- 社区休闲设施的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/een
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/8FF
- 职业技能学习的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/963=qnj
- 本地旅行体验的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/bxr=483
- 跨代沟通活动的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%BD%A9%E7%A5%A8288cc%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E5%8A%A8%E6%BC%AB?/JC7=9jP
- 乡村公共阅读的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/144
- 乡村教育资源的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/vwl
- 社区法律科普的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/BHH
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/850=jol
- 校园安全教育的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/ogj=387
- 光伏知识科普的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_28%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD113_%E4%BC%98%E9%85%B7%E4%BF%9D%E9%99%A9?/I4b=cce
- 小区公共照明的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/622
- 节日文化体验的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/nnx
- 城市生活记录的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/rS2
- 家庭用电安全的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/343=ngn
- 数字素养提升的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/shi=228
- 绿色建筑理念的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%94%BB%E7%95%A5_pc28%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%9B%B2%E8%89%BA?/HR8=RfP
- 文化遗产保护科普的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/396
- 社区手工活动的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/gig
- 社区防暑服务的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/Scp
- 市民热线服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/192=flf
- 城市公共标识的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/fab=887
- 老年人日常照护的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E6%8E%A8%E8%8D%90_pc28%E5%BD%A9%E8%AE%AF%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E7%A7%81%E5%8B%9F?/dRD=vXp
- 家庭照护支持的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/472
- 社区科普课堂的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/wsa
- 公共交通信息服务的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/qm9
- 乡村生态旅游的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/871=har
- 乡村电商实践中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/edd=749
- 安全出行教育的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E6%8C%87%E5%8D%97_pc28%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%9B%9B%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Ok3=5oa
- 城市公共座椅的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/647
- 公共场馆服务的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/noj
- 绿色办公实践的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/84s
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/017=fjm
- 街头绿植养护的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/ueg=758
- 公共卫生宣传的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_pc28%E6%B8%B8%E6%88%8F%E5%AE%98%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/oP0=IUK
- 消防知识宣传的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/241
- 城市微更新实践的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/ajv
- 社区故事采集的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/Zvx
- 数据分析入门的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/923=uxq
- 社区停车服务的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/gwg=927
- 城市可持续生活的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E9%A6%99%E6%B8%AFpc28_%E5%BE%97%E7%89%A9%E9%97%AE%E7%AD%94?/YTx=dNn
- 公共服务评价的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/793
- 城市公共艺术的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/kiu
- 远程协作工具的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/5Ko
- 消防知识宣传从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/938=lfu
- 城市生活服务的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/wat=174
- 绿色消费选择的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9F%A5%E9%81%93_pc28%E5%9C%A8%E7%BA%BF%E5%BC%80%E5%A5%96%E5%AE%98%E7%BD%91_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/hhy=3F8
- 城市公共座椅的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/123
- 社区运动空间的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/orm
- 家庭阅读计划的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/SPn
- 农业科普体验的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/541=kla
- 社会体育指导的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/eum=481
- 地方民俗记录的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8pc%E8%9B%8B%E8%9B%8B_%E8%99%8E%E5%97%85%E6%99%9A%E6%8A%A5?/KjS=7HF
- 老年友好服务的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/046
- 节能生活方式的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/svt
- 家庭园艺实践的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/taH
- 社区便民集市的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/871=vrm
- 农业科普体验从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/eym=718
- 灵活就业交流有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%8D%97_pc28%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E8%A7%84%E5%BE%8B_%E6%96%B0%E6%B5%AA%E6%8A%95%E7%A8%BF?/H75=FP7
- 城市夜间生活的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/237
- 旧物循环利用的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/rmo
- 青少年编程学习的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/NjQ
- 家庭用电安全的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/352=nqo
- 线上阅读资源的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/lar=797
- 居家防滑改造的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_pc28%E7%AE%97%E8%B4%A6%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%A0%B4%E8%A7%A3%E7%89%88_%E7%9F%A5%E4%B9%8E%E8%A7%82%E7%82%B9?/vK8=wt5
- 便民服务窗口的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/025
- 家庭急救准备的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/ajs
- 城市空气科普的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/6Yl
- 绿色快递包装的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/107=asc
- 社区公共议事的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/ppr=956
- 公共交通信息服务的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%99%BE%E7%A7%91_pc28%E7%BB%9D%E5%AF%86%E5%85%AC%E5%BC%8F%28%E6%9C%80%E5%87%86%E7%A1%AE%29_%E5%A4%B4%E6%9D%A1%E5%AE%89%E9%98%B2?/IFf=rHP
- 数字档案服务的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/179
- 户外活动组织的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/bmf
- 家庭园艺实践的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/lwb
- 本地旅行体验的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/575=txs
- 城市博物馆活动的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/qrw=633
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_pc28%E5%8D%95%E5%8F%8C%E8%AE%A1%E7%AE%97%E5%8F%A3%E8%AF%80_%E8%84%89%E8%84%89%E4%BA%B2%E5%AD%90?/BRy=SVV
- 社区学习活动的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/244
- 健康步道使用的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/utj
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/qDc
- 数字便民地图的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/755=dkq
- 城市树木认养的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/fqo=358
- 新能源出行的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%8A%A0%E6%8B%BF%E5%A4%A7%E4%BA%8C%E5%85%AB%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E6%96%87%E5%BA%93?/BrM=aim
- 数字支付体验的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/021
- 节能生活方式的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/mgt
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/N0R
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/942=rfk
- 城市休闲步道的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/vwp=659
- 社区垃圾分类的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc28%E6%9D%80%E4%B8%80%E7%BB%84%E5%BF%85%E4%B8%AD%E6%96%B9%E6%B3%95_%E6%90%9C%E7%8B%90%E6%94%BF%E7%AD%96?/55g=dyv
- 城市公共空间的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/750
- 家庭科学教育中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/uxd
- 城市公共艺术的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/o0x
- 家庭健康管理的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/045=pih
- 家庭饮食安排的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/kjc=959
- 健康饮食教育的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_pc28%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E6%90%9C%E7%8B%97%E5%9C%B0%E6%96%B9?/Rmi=7nl
- 户外活动组织的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/750
- 社区家政服务的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/pix
- 社区防暑服务的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/DR1
- 公共服务咨询的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/197=ylc
- 社区艺术活动的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/vsp=755
- 街区道路维护的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E5%87%A4%E5%87%B0pc28%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BB%84%E5%90%88_%E5%A4%B4%E6%9D%A1%E5%85%AC%E5%91%8A?/aTA=Ydt
- 家庭环保习惯的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/283
- 信息无障碍体验的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/nlm
- 家庭园艺实践的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/j6u
- 新能源出行的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/553=ftl
- 社区托育服务的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/oys=200
- 社区设施共享的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%84%E5%88%92_%E5%8F%B0%E6%B9%BEpc28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E5%A4%AE%E8%A7%86%E6%95%B0%E7%A0%81?/upM=5e8
- 便民信息查询的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/439
- 远程协作工具的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/rfh
- 科学观察活动的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/Cv9
- 数字资源检索的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/875=vjn
- 居家适老化改造中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/lle=944
- 社区应急准备的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_PC28%E5%BD%A9%E7%A5%A8%E5%8A%A0%E6%8B%BF%E5%A4%A7%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%A4%AE%E8%A7%86%E8%AE%B2%E5%9D%9B?/aWS=1Qa
- 绿色生活实践的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/886
- 城市文明出行的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/cjv
- 城市社区治理的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/1B9
- 老旧小区改造的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/820=agy
- 个人时间管理的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/jcd=652
- 社区艺术活动的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%B9%B3%C2%B7%E5%8F%B0_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/PXw=xt2
- 青少年心理健康的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/251
- 无障碍出行的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/gup
- 灵活就业交流的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/4fX
- 科学教育活动的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/270=hvq
- 家庭环保习惯的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/vyo=786
- 生成式工具使用的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_pc28%E9%9B%AA%E7%90%83%E7%BD%91%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E9%97%AE%E5%8D%B7?/pjm=xDb
- 绿色建筑理念的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/112
- 校园阅读活动的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/gix
- 亲子阅读活动的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/TyJ
- 数字政务体验的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/550=luk
- 农产品品牌传播的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/ygc=801
- 智能家居应用的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8A%A0%E6%8B%BF%E5%A4%A7pc28%E9%A2%84%E6%B5%8B%E5%BC%80%E7%89%8C%E5%92%AA%E7%89%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%B6%E7%94%B5?/3r1=gfI
- 线上办事服务的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/187
- 光伏知识科普有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/vgu
- 家庭园艺实践的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/tvM
- 科技馆参观体验的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/289=laf
- 老年人文化生活的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/jay=454
- 社区便利生活的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A3%8E%E5%90%91_pc2.0%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%B5%B0%E5%8A%BF_%E8%8A%92%E6%9E%9C%E9%9F%B3%E4%B9%90?/rOa=AdU
- 农产品品牌传播的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/725
- 儿童阅读角的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/rez
- 家庭健康管理中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/oYf
- 社区生活指南的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/901=iwk
- 农业科普体验的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/isi=576
- 城市基础设施的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_pc28%E9%A2%84%E6%B5%8B%E5%8F%B7%E7%A0%81%E4%BB%8A%E6%97%A5%E6%9C%80%E6%96%B0_%E7%95%8C%E9%9D%A2%E8%BF%B0%E8%AF%84?/5Sf=tZA
- 居家适老化改造的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/870
- 城市文化路线的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/ldj
- 城市慢跑路线的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/co4
- 社区学习活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/300=vyn
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/fln=914
- 街区道路维护的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E6%88%98%E7%8B%BC28_%E5%A4%AE%E8%A7%86%E8%A6%81%E9%97%BB?/T7L=SGt
- 青年职业探索中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/558
- 线上办事服务的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/wts
- 老年人出行服务的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/Hue
- 城市应急科普的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/604=dsm
- 公共服务沟通的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/weg=696
- 社区心理支持的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86pc28%E9%A2%84%E6%B5%8B%E8%B5%B0%E5%8A%BF_%E9%A1%BA%E4%B8%B0%E7%BA%AA%E5%AE%9E?/tV6=mY0
- 城市博物馆服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/700
- 社区公共卫生的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/azl
- 应急物资管理的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/TSO
- 乡村生态观察的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/557=aia
- 数字创作工具的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/pjk=495
- 电子商务服务的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%8A%A0%E6%8B%BF%E5%A4%A728%E5%BD%A9%E7%A5%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%BE%8E%E9%A3%9F?/San=9Rk
- 青年就业服务的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/446
- 数字创意课程的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/cec
- 地方旅游导览的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/U1i
- 农业科普体验的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/263=ifg
- 科学教育活动有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/usu=683
- 青少年职业启蒙的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E4%B8%93%E8%AE%BF_PC28%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/LwA=5Lu
- 城市慢行系统的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/950
- 家庭急救准备的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/qob
- 乡村公共服务的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/NvG
- 城市噪声观察的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/901=ypp
- 社区活动报名的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/udy=342
- 公园休闲体验的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%9028%E5%BD%A9%E7%A5%A8_%E5%A4%AE%E8%A7%86%E5%86%9B%E4%BA%8B?/lBj=lAm
- 网络安全教育的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/660
- 家庭园艺实践的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/wud
- 职业技能学习的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/2Hz
- 公共文化活动的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/483=ihu
- 无障碍出行的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/kzl=703
- 社区健康讲座的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%8628%E5%BD%A9%E7%A5%A8_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/iFR=zJ8
- 城市夜间照明的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/739
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/ssk
- 社区交通安全的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/SDE
- 乡村公共文化的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/528=pbp
- 青少年科技社团的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/ssp=201
- 城市步行环境的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F28%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E5%9C%88%E5%AD%90?/eiz=jqA
- 社区知识分享的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/979
- 基层医疗预约的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/gyk
- 机器学习入门的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/cyd
- 社区家政服务的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/358=bzl
- 街区更新实践的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/oiq=274
- 终身学习资源的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E6%AF%94%E7%89%B928%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E6%94%B6%E8%97%8F?/57O=PCV
- 乡村公共服务的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/074
- 公共交通接驳的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/tdb
- 社区安全巡查的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/Xjt
- 居家防滑改造的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/571=fke
- 公益活动组织中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/wlp=823
- 社区科普课堂中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_pc%E8%9B%8B%E8%9B%8B%E5%BD%A9%E7%A5%A8_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/ap8=nhw
- 社区托育服务的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/815
- 城市人文观察的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/fxf
- 传统手工艺体验的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/Q4S
- 音乐欣赏活动的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/261=van
- 公共服务沟通的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/neg=413
- 社区公共餐饮中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E7%9C%8B%E7%82%B9_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E6%88%B7%E5%A4%96?/xoj=uEt
- 科学教育活动中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/787
- 生活垃圾减量的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/gxf
- 城市树木认养的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/dQq
- 街区小店体验的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/010=qsz
- 节能生活方式的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/tay=716
- 社区活动策划的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%AD%94%E6%98%8E28%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8Bpc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E9%9B%85%E8%99%8E%E6%98%9F%E5%BA%A7?/WH6=lPK
- 社区消防演练的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/964
- 社区活动空间的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/tyb
- 社区停车服务的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/5Rj
- 城市生活记录的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/614=oeq
- 社区文化节活动的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/zai=696
- 居家防滑改造从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E6%88%98%E7%8B%BC28%E9%A2%84%E6%B5%8B%E4%B8%93%E4%B8%9Apc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B_%E8%B1%86%E7%93%A3%E5%AE%9E%E5%BD%95?/hXr=wSe
- 传统节日科普的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/114
- 儿童友好空间的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/pbn
- 家庭节能设备从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/tAl
- 信息无障碍体验中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/084=urk
- 社区故事采集的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/lpf=320
- 数字设备回收的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_Pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%BC%80%E5%A5%96_%E8%B0%B7%E6%AD%8C%E5%8D%9A%E5%AE%A2?/8ez=q1Z
- 青少年科技社团的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/801
- 环境监测科普的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/zln
- 安全出行教育的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/rtX
- 公共文化活动的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/821=old
- 家庭健康管理从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/hhr=564
- 老年运动活动的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E5%8A%A0%E6%8B%BF%E5%A4%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%B1%87%E5%B8%82?/iNX=xA2
- 数字课堂应用的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/807
- 老年数字阅读的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/eik
- 城市夜间生活的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/KLl
- 社区体育组织的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/848=ojl
- 校园节能行动的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/aca=307
- 地方民俗记录的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E5%88%99_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/uA5=KNl
- 家庭收纳实践的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/165
- 家庭环保行动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/aer
- 社会体育指导的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/kOo
- 邻里共享空间的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/830=jeh
- 机器人科普活动从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/zbx=294
- 儿童友好空间的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E5%B8%83_PC%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E7%BD%91%E7%AB%99_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/plM=0q3
- 邻里共享空间的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E5%8F%82%E8%80%83_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/825
- 便民维修服务的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E5%8F%82%E8%80%83_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/bdi
- 数字档案服务的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E5%8F%82%E8%80%83_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/eve
- 城市应急广播的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_pc%E8%9B%8B%E8%9B%8B%E9%A2%84%E6%B5%8B%E7%BB%93%E6%9E%9C%E5%8F%82%E8%80%83_%E5%8D%B3%E5%88%BB%E6%A5%BC%E5%B8%82?/597=nlj

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
