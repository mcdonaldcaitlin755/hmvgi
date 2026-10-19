# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:18**

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

- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8258cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/lld=602
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%91%E6%99%AE%E8%A7%84%E5%88%92_8258cc-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E7%99%BE%E5%BA%A6%E5%85%AC%E5%91%8A?/srO=R47
- 乡村教育资源的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/943
- 公共空间导览的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/jlk
- 社区绿色空间的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/IFe
- 地方美食文化的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/333=fyg
- 文明养宠科普的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/hyd=815
- 数字便民地图的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_8258cc-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%BD%91%E6%98%93%E7%99%BE%E7%A7%91?/BYJ=Zk8
- 便民服务地图的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/743
- 社区垃圾分类的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/wxe
- 家庭理财科普的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/oZz
- 公园亲子设施的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/841=lxo
- 网络信息辨识的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/lhu=768
- 智慧城市体验的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_8258cc-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E5%88%8A%E7%99%BB?/Bar=Wgi
- 地方美食文化的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/797
- 校园阅读活动的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/toj
- 亲子阅读活动的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/0Fr
- 地方民俗记录的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/032=aft
- 运动安全知识的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/aom=764
- 城市生活服务的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_8258cc-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B8%AF%E8%82%A1?/4vN=z55
- 电动汽车充电的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/173
- 公共空间休憩的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/yvg
- 通勤路线规划的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/rvf
- 社区手工活动的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/748=uty
- 农产品品牌传播的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/jcl=528
- 市民热线服务的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc-%E9%A6%96%E9%A1%B5_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/yas=V1v
- 城市文明出行的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/498
- 社区菜市场服务从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/eff
- 图书借阅体验的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/LKc
- 乡村教育资源的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/162=rjd
- 公园亲子设施的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/axu=240
- 软件开发学习的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_8258cc-%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%9B%98%E7%82%B9?/qge=SFB
- 健康步道使用的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/433
- 绿色建筑理念从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/kcs
- 骑行路线规划的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/Coz
- 社区老年食堂的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/295=pse
- 邻里互助活动的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/dtf=973
- 网络安全教育的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%8A%95%E8%B5%84?/uCN=WVN
- 乡村休闲旅游从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/972
- 农产品消费体验的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/bts
- 药品使用科普的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/p9j
- 街道综合服务的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/568=syh
- 小区停车协商的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/eav=273
- 地方民俗记录的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%84%89%E8%84%89%E8%AE%BF%E8%B0%88?/4zH=eUM
- 家庭运动计划的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/661
- 邻里互助活动的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/hwx
- 家庭健康管理从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/oln
- 学校体育活动的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/426=fvb
- 数字生活课堂的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/geo=757
- 绿色建筑理念的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E4%BC%98%E9%85%B7%E6%91%84%E5%BD%B1?/b3t=NL5
- 社区便民服务的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/300
- 社区公共餐饮的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/qqm
- 城市绿色交通中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/3Ro
- 公共服务评价的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/718=auv
- 城市公共标识的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/cbv=621
- 劳动教育实践的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E6%89%91%E8%AE%BF%E8%B0%88?/eIn=J9l
- 家庭园艺实践的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/008
- 线上办事服务的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/gyh
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/c9j
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/675=ilz
- 城市绿色交通有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/ozy=376
- 社区法律科普的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E5%9B%AD%E8%89%BA?/TQs=DV1
- 社区手工活动的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/604
- 绿色生活实践有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/loc
- 科学运动指导的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/7CO
- 公共服务预约的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/541=wlc
- 家庭饮食安排的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/les=892
- 校园节能行动的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%A4%AE%E8%A7%86%E5%8F%B8%E6%B3%95?/zaV=5VF
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/309
- 非遗体验活动的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/boz
- 志愿者培训交流的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/bih
- 数字生活课堂的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/170=zix
- 科普展览体验的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/lfv=605
- 就业技能培训的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A8%BF?/MMY=Xg6
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/913
- 图书馆亲子空间从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/obu
- 街区绿化养护的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/mLe
- 职业技能学习的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/530=zsj
- 城市公共标识的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/dic=098
- 便民维修服务的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_8258cc%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%AE%E8%A7%86%E6%B8%AF%E8%82%A1?/QTX=0wb
- 创业经验分享的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/394
- 公共文化活动的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/uks
- 城市绿道建设的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/1cd
- 社区菜市场服务的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/384=wee
- 便民服务窗口的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/txv=128
- 乡村公共文化的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_8258cc%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E8%BE%9F%E8%B0%A3?/w7Q=YK6
- 社区慢性病防控的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/559
- 地方戏曲体验的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/egp
- 文明养宠科普的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/ElA
- 城市慢跑路线从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/639=luc
- 青少年科普实践的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/jpa=614
- 乡村生态观察的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BA%86%E8%A7%A3_8258cc%E5%BD%A9%E7%A5%A8-APP_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/zWN=9Hu
- 社区公共餐饮中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/867
- 急救知识普及的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/utl
- 绿色建筑理念的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/Lpq
- 在线教育体验的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/082=noe
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/shb=867
- 青少年科技社团的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A3%8E%E5%90%91_8258cc%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E9%A3%9F?/7Y8=YyX
- 校园社团活动的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/545
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/xwi
- 城乡交通衔接的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/yuL
- 图书馆数字服务的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/657=asv
- 社区宠物管理的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/gnj=039
- 个人数据管理的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/KWh=bQQ
- 开放式学习空间的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/643
- 节日文化体验从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/wjv
- 城市水环境观察的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/VB7
- 家庭阅读计划的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/666=dip
- 城市适老服务的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/qok=942
- 家庭环保习惯的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/U5d=yR6
- 老年人出行服务的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/259
- 绿色快递包装中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/qkg
- 城市公共饮水的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/AcC
- 老年运动活动的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/935=hsi
- 科学教育活动的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/oxo=554
- 社区协商议事的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%A7%82%E5%AF%9F?/VBQ=eSv
- 城市展览体验的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/143
- 老年友好服务的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/pyp
- 家庭园艺实践的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/4bk
- 城市树木认养的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/637=sqb
- 学校体育活动的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/lmi=093
- 社区手工活动的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/mzA=Wzx
- 图书馆数字服务的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/327
- 农产品品牌传播的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/eys
- 社区生活指南有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/Az0
- 通勤路线规划的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/763=ppr
- 社区活动空间的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/wal=728
- 青年就业服务的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%87%A4%E5%87%B0%E6%92%AD%E6%8A%A5?/h1X=KlZ
- 社区老年食堂中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/419
- 节气饮食文化的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/ses
- 数字素养提升中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/PXb
- 城市绿色交通的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/426=xah
- 跨代沟通活动的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/xsn=081
- 城市绿色交通的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_8258cc%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%9B%B2%E8%89%BA?/scj=kbc
- 城市运动公园的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/196
- 社区便利生活的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/qin
- 数字便民地图的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/aFH
- 公共交通接驳的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/955=xzo
- 急救知识普及的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/iqb=829
- 地方美食文化中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_8258cc%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%85%BE%E8%AE%AF%E7%BB%BC%E8%89%BA?/EUa=Rge
- 数字生活课堂的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/091
- 城市公共艺术的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/nzi
- 公共卫生设施的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/YC0
- 社区环保活动的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/493=htd
- 线上阅读资源的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/xmm=853
- 公共空间照明的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%95%B0%E6%8D%AE%E5%8F%91%E7%8E%B0_8258cc%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%99%8E%E5%97%85%E6%BC%AB%E8%AF%84?/MTQ=bJL
- 乡村产业科普的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/475
- 无障碍出行的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/srn
- 职业技能学习的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/5Td
- 家庭照护支持的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/360=drp
- 灵活就业交流的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/eti=746
- 社区协商议事的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258cc%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E9%A1%BA%E4%B8%B0%E6%88%B7%E5%A4%96?/nFo=dqQ
- 公共交通信息服务的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/381
- 青少年编程学习的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/cvn
- 节约用水实践的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/xWm
- 社区故事采集的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/607=ppo
- 家庭用电安全的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/yby=236
- 基层医疗预约的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%81%9A%E7%84%A6_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BF%85%E5%BA%94%E6%A1%A3%E6%A1%88?/Qxe=byS
- 老年运动活动的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/853
- 急救知识普及的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/ata
- 城市生活记录的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/fwT
- 公共交通信息服务的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/073=tdz
- 家庭健康管理的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/rvy=784
- 社区休闲设施的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B8%E6%B3%95?/1gX=lkJ
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/360
- 公共卫生设施的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/hdd
- 社区便利生活的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/LUE
- 城市展览体验的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/144=acz
- 生成式工具使用从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/dqi=136
- 开放数据应用的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E8%B0%B7%E6%AD%8C%E8%AE%B2%E5%9D%9B?/qdU=Fns
- 公共服务评价的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/800
- 社区环保活动的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/llk
- 公共服务沟通的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/fgy
- 乡村教育资源的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/397=czo
- 休闲运动入门的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/pah=909
- 社区养老服务的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E5%BE%97%E7%89%A9%E6%8A%95%E8%B5%84?/KDt=kYt
- 基层健康档案的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/434
- 科学睡眠习惯中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/jtx
- 城市农夫市集的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/zkP
- 地方戏曲体验的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/293=vbs
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/slu=489
- 生活垃圾回收的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%B4%A2%E7%BB%8F%E5%9C%A8%E7%BA%BF?/A7f=Tmi
- 城市公共标识的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/540
- 乡村生活观察的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/mtw
- 家庭环保习惯的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/gVs
- 生活垃圾回收的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/809=bby
- 校园阅读活动的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/ldz=660
- 数字素养提升的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%8D%B7%E5%85%8B%E8%B4%A2%E7%BB%8F?/VzB=rbl
- 数据分析入门的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/096
- 科学健身方法的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/cug
- 儿童友好空间的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/4vE
- 城市绿道建设的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/462=pcj
- 便民维修服务的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/dvy=438
- 公共服务沟通的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E5%BF%AB%E6%89%8B%E5%AE%8F%E8%A7%82?/bep=XZn
- 城市游园体验的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/281
- 青少年职业启蒙的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/yet
- 邻里共享空间的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/UVp
- 数字政务体验的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/129=dgr
- 社区便民集市的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/coa=113
- 科学信息获取的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BC%98%E9%85%B7%E6%8A%95%E7%A5%A8?/Cpl=fNO
- 机器学习入门的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/954
- 气象科普传播的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/uze
- 灵活就业交流的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/SoS
- 青少年科普实践的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/109=fah
- 学校食育活动的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/mwy=977
- 社区交通安全的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_8258%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%86%9C%E4%B8%9A?/kvD=s2k
- 农业科普体验的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/442
- 公共空间照明的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/jxq
- 老年友好服务的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/NxP
- 食品安全科普的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/997=iri
- 数字档案服务的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/qhg=324
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_8258%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/ePt=P6c
- 城市宠物友好空间的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/370
- 绿色出行服务从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/mhi
- 乡村生态观察的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/O6N
- 街区更新实践的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/105=xyh
- 公共设施维护的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/gal=643
- 家庭环保行动的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_8258%E5%BD%A9%E7%A5%A8-APP_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/DTO=9z6
- 数字创作工具的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/507
- 街区道路维护的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/pos
- 公共卫生设施的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/7Lr
- 科学教育活动的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/646=nlv
- 口袋公园建设的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/bcg=034
- 农村环境治理的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_8258%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/iz5=cOM
- 租房信息服务的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/680
- 传统手工艺体验的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/gqz
- 城市生活记录的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/FTQ
- 社区公共卫生的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/662=kng
- 开放式学习空间的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/bgg=312
- 乡村生态旅游的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_8258%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E5%A4%B4%E6%9D%A1%E6%8A%95%E7%A5%A8?/hXk=Rtk
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/316
- 青少年职业启蒙的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/wsk
- 科学观察活动的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/fpb
- 网络信息辨识的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/832=khk
- 数字艺术创作的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/cqh=078
- 社区公共卫生的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%84%E6%B5%8B_8258%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_36%E6%B0%AA%E5%8E%86%E5%8F%B2?/VbG=zKA
- 家庭环保习惯的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/555
- 课后服务体验的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/rhb
- 健康信息获取的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/2e6
- 公共场馆服务的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/530=lgp
- 社区手工活动的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/ozh=429
- 志愿服务平台的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_8258%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%90%E7%A8%8E%E5%8A%A1?/Pbd=CLQ
- 社区志愿服务的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/839
- 文化场馆预约的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/fpj
- 社区公共餐饮的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/nYq
- 家庭节能设备的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/627=chv
- 城市人文观察的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/eha=572
- 亲子阅读活动的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E5%85%AC%E5%91%8A_8258%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%BE%8E%E6%B9%83%E6%B3%95%E5%BE%8B?/XF4=nuO
- 生活垃圾回收的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/211
- 老年智能设备的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_8258%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%B8%B9%E9%BA%A6%E8%B4%A2%E7%BB%8F?/eed

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
