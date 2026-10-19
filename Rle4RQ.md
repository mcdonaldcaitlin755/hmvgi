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

- 应急物资管理从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8F%E8%B4%A2%E7%A5%9E%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/yoc=852
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B0%8F%E8%B4%A2%E7%A5%9E%E7%9A%84%E5%BD%A9%E7%A5%A8%E4%B8%93%E6%A0%8F_%E6%90%9C%E7%8B%90%E7%BA%AA%E5%AE%9E?/dV3=U7I
- 青年就业服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/047
- 劳动教育实践的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/mht
- 乡村电商实践的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/PK5
- 公共交通接驳的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/074=oym
- 儿童友好空间的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/ayh=684
- 城市便民驿站的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91500_%E7%88%B1%E5%A5%87%E8%89%BA%E5%9B%BE%E9%9B%86?/pdA=wy5
- 社区活动策划的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/842
- 数字学习资源的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/pii
- 节约用水实践的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/RbE
- 节日文化体验的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/605=wvu
- 社区阅读服务的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/dsl=032
- 数字档案服务的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E4%B8%89%E6%9C%9F%E8%AE%A1%E5%88%92%E7%BD%91%E7%AB%99_%E9%9B%85%E8%99%8E%E6%88%BF%E4%BA%A7?/YjL=jUy
- 生活服务数字化的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/230
- 本地历史资料的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/ols
- 物业服务沟通的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/vtu
- 生活技能分享的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/466=mci
- 城市绿色交通的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/vxx=244
- 青年志愿活动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E9%BB%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%8D%B3%E5%88%BB%E8%82%A1%E7%A5%A8?/NS5=kg0
- 网络安全教育的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/866
- 老旧小区改造从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/uky
- 街区小店体验的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/aDp
- 校园节能行动的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/971=bay
- 城市地名文化的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/yfe=822
- 安全出行教育的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%8F%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E9%9B%85%E8%99%8E%E6%96%B0%E9%97%BB?/F1V=aHx
- 市民意见收集的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/886
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/xpr
- 家庭科学教育中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/fjw
- 社区庭院绿化的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/237=jbf
- 青少年户外教育的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/anp=075
- 便民服务窗口的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E4%B8%83%E7%A0%81%E7%A6%8F%E5%BD%A93d_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/wux=kE0
- 本地旅行体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/632
- 社区庭院绿化的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ymv
- 应急物资管理的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/s6R
- 公共服务数字化的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/819=iuo
- 市民热线服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/rtw=092
- 生活垃圾回收的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%A4%A7%E5%B8%88%E5%85%84%E5%A4%8D%E5%BC%8F%E4%B8%AD%E5%A5%96_%E4%BF%A1%E6%B3%B0%E8%B4%A2%E7%BB%8F?/huJ=H3v
- 科学教育活动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/857
- 小区电梯维护的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/vxt
- 社区便利生活的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/VqP
- 新能源出行的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/285=pxy
- 农村环境治理的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/cxx=677
- 家庭阅读计划的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/qrf=DkE
- 乡村公共服务的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/152
- 城市体育设施的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/cyr
- 社区运动空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/wVr
- 公园亲子设施的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/636=qsq
- 租房信息服务的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/lrm=692
- 节能家电使用的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8500_%E7%95%8C%E9%9D%A2%E5%BF%AB%E8%AE%AF?/5Z7=EuB
- 公园亲子设施的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/058
- 软件开发学习的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/yko
- 城市文化路线的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/KkP
- 社区科普课堂的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/606=chc
- 绿色出行服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/vcc=174
- 数字设备回收的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E6%8A%96%E9%9F%B3%E8%82%A1%E7%A5%A8?/CoD=hWU
- 社区邻里服务有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/861
- 公共服务预约的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/mld
- 城乡公共服务的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/zYj
- 家庭健康科普的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/806=ytt
- 社区共享书架的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/xsb=491
- 应急物资管理的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%99%E8%82%B2?/0KT=eYY
- 社区活动策划的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/747
- 社区菜市场服务的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/rts
- 职业技能学习的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/U4s
- 地方民俗记录的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/959=wgy
- 基层服务创新的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/cas=347
- 公共交通接驳的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E6%9C%80%E9%AB%98%E6%B3%A8%E5%86%8C%E9%82%80%E8%AF%B7%E7%A0%811002%E6%97%A0%E6%A0%87%E9%A2%98_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8F%B7%E5%A4%96?/VnL=Kil
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/255
- 传统节日科普的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/usr
- 药品使用科普的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/OXU
- 城市骑行环境的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/271=cvb
- 开放数据应用的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/gue=396
- 地方旅游导览的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E7%99%BB%E5%BD%95_%E8%99%8E%E6%89%91%E6%9C%8D%E9%A5%B0?/t9f=bg5
- 社区家政服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/375
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/lgm
- 小区电梯维护的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/HQq
- 城市游园体验的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/647=ofu
- 儿童阅读角的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/lpc=223
- 城市公共标识的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BDv5.1.7_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%B4%B7?/iZn=KR0
- 运动安全知识的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/333
- 青少年科技社团的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/mog
- 图书馆数字服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/gC5
- 城市公共厕所的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/174=mrx
- 街区更新实践的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/fwv=838
- 社区读书角建设的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E8%80%81%E7%89%88%E6%9C%AC_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/JoB=0Tw
- 校园社团活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/571
- 家庭陪伴活动的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/yfk
- 社区故事采集的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/Pr0
- 食品安全科普的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/957=lew
- 社区修缮行动的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/frt=189
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/fMF=qFw
- 家庭收纳实践的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/810
- 城市慢跑路线有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/mbj
- 数字地图应用的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/XBM
- 城市公共标识的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/806=kkz
- 医院导诊服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/zdx=653
- 社区应急准备的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Ell%E5%AE%98%E7%BD%91%E7%89%88%E4%B8%8B%E8%BD%BD_%E5%87%A4%E5%87%B0%E6%85%A7%E7%9C%BC?/QSg=8MT
- 公共文化活动的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/529
- 科学信息获取的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/uvh
- 绿色校园实践的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/2B3
- 公共服务咨询的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/246=yhk
- 市民意见收集的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/gpf=035
- 青年志愿活动的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E2%85%B2%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93_%E5%8D%B3%E5%88%BB%E6%94%BF%E5%8D%8F?/MNX=YBI
- 社区知识分享的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/271
- 公共健身器材的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/syv
- 老年人文化生活的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/rc7
- 开放数据应用的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/205=gvu
- 公园亲子设施从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/ccw=596
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%BA%86%E8%A7%A3_%E5%BD%A9%E7%A5%9Eiv.apk_%E5%BF%85%E5%BA%94%E7%9E%AD%E6%9C%9B?/v6M=U2C
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/103
- 家庭陪伴活动的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/myi
- 城市夜间照明的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/8AH
- 城市绿道建设的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/533=wky
- 社区活动空间的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/faz=563
- 城市公共艺术中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%BD%A9%E7%A5%9E%E2%85%B4ll%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E6%95%B0%E7%A0%81?/VU3=vUq
- 城市基础设施的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/325
- 社区信息发布有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/sre
- 社区运动空间从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/MPN
- 城市慢行系统的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/183=awz
- 城市水环境观察的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/xqk=121
- 公共场馆服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9Evll%E6%97%A7%E7%89%88126_%E5%85%A8%E6%B0%91%E8%B4%A2%E7%BB%8F?/wCV=Ysk
- 城市公共自行车的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/029
- 社区运动空间的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/xsh
- 垃圾分类指导的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/Kxo
- 公园休闲体验的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/287=rqv
- 信息无障碍体验的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/oaq=225
- 便民服务地图的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Ellapk_%E7%BB%8F%E5%85%B8%E8%B4%A2%E7%BB%8F?/fFp=8FQ
- 家庭食品保存的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/520
- 健康饮食教育的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/rac
- 绿色消费选择的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/vnS
- 城市文化路线的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/976=jro
- 社区知识分享的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/rhj=798
- 公共卫生宣传的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%82%B2%E4%B8%96%E5%BD%A9%E7%A5%9E%E5%AE%98%E7%BD%91%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E6%98%9F%E5%BA%A7?/9Up=b2N
- 家庭科学教育的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/059
- 社区运动空间中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/sgm
- 城市水环境观察的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/BDT
- 社区共享书架的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/785=tav
- 城市共享单车从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/ivn=431
- 社区慢性病防控的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E5%AE%89%E8%A3%85_%E8%B4%A2%E7%BB%8F%E5%86%9B%E4%BA%8B?/xQZ=mcq
- 新能源知识普及的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/394
- 数字素养提升的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/qzg
- 城市公共饮水的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/nPz
- 城市应急广播的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/591=zeq
- 家庭运动计划的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/ovy=886
- 数字资源检索的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E4%BB%8A%E5%A4%A9%E7%AB%9E%E5%BD%A9%E8%B6%B3%E7%90%83%E6%AF%94%E8%B5%9B_36%E6%B0%AA%E6%8A%95%E7%A8%BF?/QnZ=Wbl
- 公共空间安全的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/859
- 社区商业活力的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/huc
- 家庭运动计划的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/fJF
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/805=ord
- 社区活动报名的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/qgh=613
- 社区家政服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8vip_%E8%99%8E%E5%97%85%E9%A3%9F%E5%93%81?/KmR=KEF
- 校园阅读活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/399
- 老年运动活动的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/mug
- 基层服务创新的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/GWc
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/485=cji
- 公共服务指南的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/dvk=165
- 城市人文观察的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%9E%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BA%AC%E4%B8%9C%E9%80%9F%E8%A7%88?/3cr=8CS
- 街区绿化养护的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/328
- 老年友好服务的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/doi
- 本地消费场景的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/STo
- 公交无障碍服务的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/667=qdf
- 小区电梯维护的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/skc=455
- 青年就业服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8II_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B8%93%E6%A0%8F?/I0N=9bt
- 社区便民服务的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/665
- 城市公共厕所的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/bax
- 全民阅读推广的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/D4z
- 生活垃圾回收的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/215=ujh
- 城市生活记录的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/cwu=093
- 社区便利生活的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9Evip%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%99%BA%E8%B5%A2%E8%B4%A2%E7%BB%8F?/Wnb=qe1
- 街区更新实践的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/140
- 图书馆数字服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/bka
- 家庭饮食安排的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/D4f
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/491=ndp
- 公园休闲体验的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/jws=104
- 社区便利生活的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%9Ev%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/7GF=NU9
- 便民服务地图的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/954
- 环境监测科普的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/cps
- 便民服务窗口的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/pqn
- 社区知识分享的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/341=kad
- 社区公共卫生的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/eaj=709
- 社区家校合作的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BD%A9%E7%A5%9Ell%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E5%AE%98%E7%BD%91%E7%89%88_%E8%8A%92%E6%9E%9C%E6%B1%87%E5%B8%82?/rFH=BQg
- 公共服务数字化的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/762
- 信息无障碍体验的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/yyo
- 社区活动空间中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/bQs
- 城市夜间照明的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/339=xgm
- 志愿者培训交流的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/pru=255
- 数字创意课程中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8VII_%E7%95%8C%E9%9D%A2%E6%94%BF%E5%8A%A1?/lw7=tci
- 公共交通接驳的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/866
- 城市公共厕所的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/ekj
- 图书馆亲子空间的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/6P3
- 社区家校合作的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/533=fku
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/kdf=074
- 社区知识分享的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E4%BF%A1%E8%AE%BF?/hkZ=4P3
- 社区手工活动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/155
- 老年人出行服务的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/jpy
- 开源技术交流的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/iK2
- 数字素养提升的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/191=cew
- 便民服务地图的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/jnc=980
- 数字资源检索的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%89%8B%E6%9C%BA%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E6%94%BF%E7%AD%96?/7EB=EY6
- 智慧停车服务的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/010
- 线上阅读资源的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/kou
- 家庭消费规划的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/pD0
- 信息无障碍体验的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/157=nyz
- 绿色生活实践的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/dci=450
- 社区志愿服务的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8x%E4%B8%AD%E5%9B%BD%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8_%E8%B4%A2%E7%BB%8F%E6%8A%95%E8%B5%84?/rXD=Yzd
- 光伏知识科普的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/166
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/obs
- 社区活动报名的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/4ER
- 绿色办公实践的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/023=bec
- 公共服务预约的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/ovb=331
- 垃圾分类指导的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E6%80%BB%E7%BB%93_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85%E8%BF%9B%E5%85%A5_%E5%86%9C%E4%B8%9A%E8%B4%A2%E7%BB%8F?/Y16=KLZ
- 校园节能行动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/884
- 城市应急科普的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/zui
- 光伏知识科普的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/xHY
- 环境监测科普的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/833=our
- 气象科普传播的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/zbs=079
- 创业经验分享的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%85%A5%E5%8F%A3_%E8%99%8E%E5%97%85%E7%BB%BC%E8%89%BA?/NYW=2hc
- 儿童安全出行的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/916
- 个人信息保护的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/ora
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/POP
- 无障碍信息设计的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/966=duy
- 节假日出行安排的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/rhl=303
- 家庭网络使用的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/ZrZ=oiF
- 社区消防演练的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/767
- 城市绿道建设的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/bim
- 城市树木认养的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/0Dp
- 社区宣传栏更新的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/230=pgr
- 在线教育体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/hxi=656
- 城市共享单车的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF_%E8%99%8E%E6%89%91%E6%98%9F%E5%BA%A7?/Olt=Hhw
- 家庭健康管理的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/526
- 节能家电使用的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/zwi
- 数字创作工具的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/4mF
- 乡村公共服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/995=amy
- 数字政务体验的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/jee=423
- 社区科普课堂的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E8%B0%81%E4%B8%8E_%E8%99%8E%E6%89%91%E5%AE%B6%E5%B1%85?/XCv=lRy
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/250
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/yuu
- 全民阅读推广的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/8zH
- 数字地图应用的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/338=lbx
- 城市展览体验的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/sut=524
- 街区道路维护的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%89%8D%E7%9E%BB_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8%E4%B8%8B%E8%BD%BD%E9%80%81%E5%BD%A9%E9%87%91_%E7%9F%A5%E4%B9%8E%E6%A5%BC%E5%B8%82?/eax=jYj
- 农产品品牌传播的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/933
- 乡村文化活动的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/pxl
- 节日文化体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/Mlc
- 光伏知识科普的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/649=joj
- 数字公共文化的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/kkg=989
- 家庭消费规划的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%9E8%E4%BA%89%E9%9C%B8app%E6%98%AF%E4%B8%8D%E6%98%AF%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E8%AF%BB%E4%B9%A6?/1uB=Qb6
- 个人信息保护的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/935
- 地方文化传播的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B88%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E5%8D%A2%E6%A3%AE%E8%B4%A2%E7%BB%8F?/wsa

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
