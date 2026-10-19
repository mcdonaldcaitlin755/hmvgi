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

- 公园无障碍服务的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/251
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/jnw
- 劳动教育实践的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/oJx
- 城市基础设施的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/738=fgd
- 人工智能科普的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/ruh=249
- 图书借阅体验中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%8A%A9%E6%89%8B%E8%8B%B9%E6%9E%9C%E7%89%88%E4%B8%8B%E8%BD%BD_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/a2A=H2i
- 家庭理财科普的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/174
- 科学信息获取的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/rde
- 食品配送体验的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/Isp
- 公共服务数字化的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/209=xuo
- 城市展览体验的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/kuv=055
- 社区防暑服务的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A2%E8%AE%A8_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/zoA=Osk
- 青少年科普实践的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/075
- 儿童阅读角的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/ovx
- 科技馆参观体验的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/f6b
- 乡村文化空间的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/601=urm
- 城市文明出行的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/wxi=964
- 生活技能分享的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9F%A5%E8%AF%86_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%97%B6%E8%AE%AF?/Dym=tck
- 公共空间休憩的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/398
- 公共服务咨询的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/iqo
- 城市公共标识的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/Ow2
- 家庭防灾准备的服务体验观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/831=nku
- 邻里互助活动的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/ltp=971
- 城市农夫市集的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%8F%E9%AA%8C_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E9%94%90%E8%AF%84?/fsP=OBN
- 非遗体验活动的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/926
- 公交无障碍服务的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/xls
- 农产品消费体验的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/OLU
- 地方文化传播的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/043=qex
- 公共空间休憩的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/rno=851
- 个人信息保护中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%85%A8%E4%B9%88_%E5%A4%B4%E6%9D%A1%E6%A6%9C%E5%8D%95?/7eH=AjA
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/018
- 通勤路线规划的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/pca
- 家庭健康科普的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/aYb
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/431=nxj
- 家庭运动计划的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/ffu=904
- 公园休闲体验的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BF%AB3%E5%AE%98%E7%BD%91APP%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E4%B8%8B%E8%BD%BD_%E9%A6%96%E5%B0%94%E8%B4%A2%E7%BB%8F?/xXj=B6p
- 数字学习资源的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/082
- 课后服务体验的流程优化思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/umh
- 节能生活方式的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/45U
- 非遗体验活动的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/819=nge
- 城市人文观察有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/nuv=119
- 数字地图应用中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88_%E6%96%B0%E6%B5%AA%E4%BF%9D%E9%99%A9?/CqU=pin
- 青年志愿活动中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/264
- 乡村生活观察的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/dtc
- 社区手工活动的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/8Fg
- 社区休闲设施的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/335=xdw
- 城市文化路线的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/tli=507
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E6%89%8B%E6%9C%BA%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%91%8A?/LmU=xHe
- 物业服务沟通的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/874
- 社区绿色空间的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/qfm
- 乡村公共阅读的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/8VC
- 读书会组织的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/619=ufo
- 邻里共享空间的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/oue=864
- 地方民俗记录中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E9%9F%B3%E4%B9%90?/av7=zu0
- 街区小店体验的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/991
- 城市人文观察的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/wal
- 绿色建筑理念的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/ZCH
- 公共设施维护的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/097=lfb
- 公共服务指南的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/mxb=522
- 传统手工艺体验的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E8%B4%AD%E5%BD%A9app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E7%B2%BE%E5%87%86_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/SgL=Ao6
- 食品配送体验的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/127
- 环境教育课程的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/edq
- 文化讲座服务的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/kyv
- 家庭阅读计划的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/849=wxh
- 安全出行教育的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/wtl=138
- 绿色生活实践中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E8%B4%A2%E7%BB%8F_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E6%8A%95%E8%B5%84?/jHl=cpN
- 社区信息发布的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/718
- 数字创意课程的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/qvc
- 社区互助网络的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/X4V
- 家庭园艺实践的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/884=chj
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/ihc=307
- 社区协商议事的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%8D%97_%E6%97%A7%E7%89%88%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%BC%AB%E8%AF%84?/9Fs=qo6
- 城市绿色交通的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/820
- 个人信息保护的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/kxz
- 城市公共标识的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/S7k
- 小区公共照明的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/974=icy
- 家庭食品保存的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/fcv=186
- 社区菜市场服务的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%A7%91%E6%99%AE%E5%AD%A6%E4%B9%A0_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85ios%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E9%A1%BA%E4%B8%B0%E6%B1%BD%E8%BD%A6?/tKw=n5c
- 物业服务沟通的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/477
- 家庭环保行动的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/jgv
- 乡村生活观察的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/lII
- 社区垃圾分类的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/672=omt
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/uzz=854
- 数字支付体验的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E8%88%86%E6%83%85?/3SV=vys
- 城乡交通衔接的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/975
- 社区活动报名的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/ivl
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/RLX
- 社区商业活力的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/011=pmy
- 数字设备回收的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/vvh=496
- 社区信息发布的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%85%8D%E8%B4%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%8A%92%E6%9E%9C%E8%AF%BB%E6%8A%A5?/DDK=CIO
- 农产品品牌传播的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/647
- 城市文明实践的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/tpi
- 数字便民地图的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/CLh
- 智能家居应用的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/235=oog
- 科学健身方法的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/tzv=376
- 农村环境治理的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD2023%E6%9C%80%E6%96%B0%E7%89%88_%E4%B8%AD%E9%93%B6%E8%B4%A2%E7%BB%8F?/VVL=qxl
- 老年人文化生活的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/405
- 城市公共艺术的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/amm
- 小区停车协商的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/5Dm
- 城市夜间生活的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/730=tas
- 乡村电商实践的基础设施观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/ego=288
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%9C%B0%E4%BA%A7?/gKY=FGQ
- 社区科普课堂的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/176
- 社区活动报名的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/uec
- 青少年编程学习的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/qsJ
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/573=sex
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/vtv=514
- 食品安全科普的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%BB%80%E4%B9%88%E8%BD%AF%E4%BB%B6_%E7%95%8C%E9%9D%A2%E6%97%85%E6%B8%B8?/TD1=dfN
- 城市文明出行的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/549
- 城市社区治理从需求出发看服务设计 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/gbb
- 城市雨天出行的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/kDK
- 社区共享书架的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/155=rnj
- 社区协商议事的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/cdg=543
- 便民服务地图的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%8E%A2%E6%BA%90?/0nI=LHx
- 城市公共自行车的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/441
- 志愿者培训交流的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/vcs
- 城市适老服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/9wZ
- 地方文化传播的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/603=rdx
- 社区便民集市的服务反馈渠道 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/ela=691
- 社区托育服务中的几个关键细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E7%9B%B4%E6%92%AD?/JNT=wcI
- 文化讲座服务的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/858
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/jgq
- 城市慢跑路线的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/pMb
- 儿童友好空间的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/820=zkj
- 社区休闲设施的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/nlv=122
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E6%8A%96%E9%9F%B3%E5%B9%B6%E8%B4%AD?/Ism=r7i
- 城市夜间照明的服务细节记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/131
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/wwo
- 乡村公共文化的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/89J
- 乡村阅读空间的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/484=pbg
- 乡村教育资源的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/vee=957
- 老旧小区改造的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%28%E5%AE%98%E6%96%B9%E7%89%88%E6%9C%AC%29%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E7%A7%81%E5%8B%9F?/c65=UBr
- 乡村生态观察的社区参与观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/324
- 节假日出行安排的日常管理方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/rgf
- 城市住房服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/isw
- 乡村休闲旅游的阅读与学习资源 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/725=ddh
- 城市地名文化的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/bkr=621
- 社区文化传播的实用信息清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%BB%8F%E9%AA%8C%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/dXR=IkW
- 数字政务体验的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/295
- 公园亲子设施中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/goq
- 家庭环保习惯的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/VsH
- 地方民俗记录的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/711=jhz
- 家庭运动计划的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/isx=945
- 城市文明实践的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E7%95%8C%E9%9D%A2%E6%BC%AB%E8%AF%84?/Xb8=5Kj
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/051
- 科普展览体验的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/bnc
- 生活垃圾减量的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/A3j
- 居家防滑改造有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/870=qiy
- 社区共享书架的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/qbi=046
- 社区交通安全的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/Iax=jIU
- 城市展览体验的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/249
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/kuj
- 城市博物馆活动的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/VNl
- 社区运动空间的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/444=ssg
- 急救知识普及的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/nab=552
- 绿色办公实践的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/GBe=RmI
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/730
- 老年人出行服务的资源整合思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/yvm
- 本地消费场景的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/rqd
- 城市住房服务的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/076=kjc
- 职业技能学习的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/nqx=562
- 户外活动组织的线上线下服务衔接 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E8%BE%9F%E8%B0%A3?/1ft=bF6
- 数字便民地图的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/572
- 数字政务体验的实际需求与回应 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/puv
- 数字设备回收的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/kIK
- 家庭园艺实践的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/918=rxu
- 家庭节能设备的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/gfb=345
- 街区小店体验的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%85%AC%E5%91%8A_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E6%AD%A3%E7%89%88%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%BE%97%E7%89%A9%E5%8C%BB%E8%8D%AF?/8tD=QTR
- 乡村文化空间的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/264
- 农产品消费体验的常见问题梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/rhu
- 绿色出行服务的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/LXw
- 医院导诊服务的组织方法与经验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/812=cie
- 城市建设科普的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/cmo=194
- 家庭消费规划的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E7%B2%BE%E9%80%89_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%BA%BA%E7%89%A9?/wuI=c8Q
- 城市公共厕所的适老服务细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/102
- 城市适老服务从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/ryl
- 农村环境治理的家庭实践清单 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/IJx
- 城市休闲步道的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/065=fma
- 家庭运动计划的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/xwj=672
- 家庭急救准备的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%9C%80%E6%96%B0%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E8%B6%8B%E5%8A%BF?/40k=ktB
- 在线学习体验的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/678
- 科学教育活动的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/tgs
- 科学健身方法中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/Eus
- 就业技能培训的协商参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/423=fds
- 公共空间照明的参与方式与路径 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/lcx=020
- 城市共享单车的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E8%99%8E%E5%97%85%E9%97%AE%E5%8D%B7?/7Aq=LrY
- 文化遗产保护科普的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/207
- 社区科普课堂的便利性观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/yrc
- 全民阅读推广的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/50j
- 社区文化节活动的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/031=kuj
- 本地历史资料的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/krq=891
- 社区交通安全的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%AD%A3%E8%A7%84%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/Q9D=3JX
- 开源技术交流的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/771
- 劳动教育实践的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/gbc
- 城市宠物友好空间的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/yHF
- 公共空间休憩中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/692=yuu
- 网络信息辨识的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/rqs=649
- 公共卫生宣传的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_360%E7%9B%98%E7%82%B9?/BeE=5Ba
- 城市基础设施的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/629
- 老年人出行服务的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/qry
- 社区便民集市的空间使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/NNj
- 开放数据应用的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/574=gnl
- 家庭阅读计划的学习资源整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/smg=433
- 应急物资管理的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E8%B4%AD%E5%BD%A9%E5%BF%AB3ios%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%8E%BF%E5%9F%9F?/9Qd=K9M
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/543
- 农贸市场环境中的沟通与协作 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/mrv
- 社区便民集市的日常记录与分享 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/C8T
- 城市住房服务的空间设计要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/528=zsb
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/mmg=677
- 城市雨天出行的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E8%8B%B9%E6%9E%9C%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E7%BB%BC%E8%89%BA?/AmP=Ufb
- 城市公共空间的日常实践笔记 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/407
- 乡村文化活动的执行流程参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/czf
- 数字课堂应用的活动组织技巧 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/4R3
- 城市水环境观察的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/603=ecw
- 城市游园体验的基础知识问答 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/url=519
- 家庭网络使用的绿色实践方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%89%E5%8D%93%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E8%A1%8C%E6%83%85?/6M1=cRO
- 在线教育体验的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/520
- 城市文明出行的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/fwp
- 社区艺术活动的公共信息获取方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/bss
- 社区养老服务的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/894=gzx
- 远程协作工具的服务质量观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/zkl=708
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E5%AE%98%E6%96%B9%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%85%B1%E8%B5%A2%E8%B4%A2%E7%BB%8F?/LeN=EBU
- 家庭收纳实践的线下体验记录 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/761
- 基层健康服务的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/cnl
- 家庭收纳实践的公共参与指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/7hV
- 课后服务体验的便捷程度观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/013=pgs
- 社区运动空间的日常使用指南 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/clz=624
- 社区活动空间的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B4%AD%E5%BD%A9%E5%BF%AB3app%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD%E5%85%8D%E8%B4%B9_%E8%84%89%E8%84%89%E5%88%B8%E5%95%86?/rDL=kkt
- 新能源知识普及的入门知识整理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/321
- 周末休闲规划的居民参与机会 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/frx
- 社区艺术活动的活动策划思路 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/P9b
- 急救知识普及的持续改进方向 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/730=ija
- 家庭安全提示的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/nau=631
- 数字政务体验的资源利用方法 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E9%93%BE%E6%8E%A5%E6%98%AF%E5%A4%9A%E5%B0%91_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/dKU=BPt
- 休闲运动入门从使用体验看服务改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/805
- 校园安全教育的数字化应用观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/ebn
- 开放式学习空间的社区行动案例 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/lYe
- 家庭阅读计划的行动步骤参考 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/921=sxi
- 健康步道使用的服务范围梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/oka=850
- 校园阅读活动的协作机制梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2027%E4%B8%93%E6%A0%8F%E6%80%BB%E7%BB%93_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/o9R=1bM
- 社区阅读服务的数字工具使用体验 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/747
- 科学睡眠习惯的长期维护要点 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/unx
- 读书会组织的安全使用提示 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/8GK
- 学校食育活动的活动体验回顾 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/025=lld
- 节日文化体验的设施维护观察 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/xrs=473
- 社区便民集市的便民做法梳理 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E8%B4%AD%E5%BD%A9%E5%BF%AB3%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%89%8B%E6%9C%BA%E7%89%88%E6%9C%AC%E6%9C%80%E6%96%B0_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/Ol0=054
- 社区活动策划的常见误区提醒 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/926
- 通勤路线规划的儿童友好细节 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/mpx
- 城市应急广播的家庭参与方式 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/9T0
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/fieldsleonard6569/mqiz/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%80%81%E7%89%88%E6%9C%AC3.2.0%E4%B8%8B%E8%BD%BD%E6%95%99%E7%A8%8B_%E9%9D%9E%E6%B4%B2%E8%B4%A2%E7%BB%8F?/455=vqw

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
