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

- 数字学习资源的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/0tO
- 公交无障碍服务的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/065=bvt
- 儿童安全出行的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/fsh=037
- 物业服务沟通的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%8A%95%E8%B5%84?/Hdr=YMr
- 生活垃圾回收的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/641
- 社区志愿服务的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/ghu
- 便民维修服务的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/VyS
- 社区邻里服务的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/290=phy
- 城市可持续生活的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/gln=841
- 日常摄影记录的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%8E%8B%E7%89%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%BD%91%E5%9D%80_%E9%87%91%E6%A6%9C%E8%B4%A2%E7%BB%8F?/oLU=bfR
- 旧物循环利用的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/908
- 公共服务预约的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/zje
- 农村环境治理的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/xji
- 家庭运动计划的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/998=zwm
- 社区艺术活动的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/etk=111
- 健康饮水科普的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%B2%BE%E9%80%89%E6%89%8B%E5%86%8C_%E6%97%A5%E5%BD%A9%E7%BD%91%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E6%A6%9C%E5%8D%95?/pHw=Qhi
- 家庭节能设备的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/266
- 市民意见收集的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/xht
- 机器学习入门的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/9vd
- 儿童友好空间的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/605=xqp
- 社区共享书架的服务信息整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/uyo=318
- 社区手工活动的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%84%89%E8%84%89%E9%80%9F%E8%A7%88?/L4i=rYh
- 社区宣传栏更新的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/818
- 社区设施共享的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/ipb
- 在线教育体验的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/LfL
- 农贸市场环境的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/672=lpn
- 市民热线服务的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/zxk=113
- 乡村阅读活动的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E5%BF%AB%E6%89%8B%E5%9F%8E%E4%BA%8B?/iJh=hv8
- 户外活动组织的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/818
- 城市公共饮水的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/yhp
- 社区公共议事的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/A1I
- 便民维修服务的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/581=zjm
- 城市社区治理的协商参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/lxs=012
- 租房信息服务的便捷程度观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_%E6%97%A5%E5%BD%A9%E7%BD%91-%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E7%BD%91%E6%98%93%E5%8D%83%E5%B8%86?/0dY=duj
- 青少年户外教育的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/255
- 健康饮食教育的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/nez
- 乡村生态旅游的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/Lkr
- 城市地名文化的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/668=nzd
- 生活服务数字化的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/czd=134
- 租房信息服务的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9app_%E5%BF%85%E5%BA%94%E7%BE%8E%E9%A3%9F?/UVY=6Oa
- 在线学习体验的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/887
- 文化讲座服务的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/azp
- 乡村生态观察的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/kkJ
- 绿色出行服务的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/354=kfw
- 健康饮水科普的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/tcv=048
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-%E6%B3%A8%E5%86%8C%E8%B4%A6%E5%8F%B7_36%E6%B0%AA%E4%B8%93%E9%A2%98?/O9d=IfQ
- 无障碍出行的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/073
- 乡村电商实践的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/tng
- 生活垃圾减量从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/bpX
- 科学健身方法的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/906=xdj
- 食品安全科普的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/jdo=611
- 儿童友好空间的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%AF%BC_%E6%97%A5%E5%BD%A9%E7%BD%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%91%A8%E6%8A%A5?/AJk=h8k
- 开放数据应用的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/838
- 家庭安全提示的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/hjx
- 租房信息服务的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/qOC
- 食品安全科普的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/139=xuy
- 节约用水实践的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/kro=238
- 社区教育资源的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%B4%A2%E7%BB%8F_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%BF%AB%E4%B8%89%E8%B4%AD%E4%B9%B0%E5%A4%A7%E5%8E%85_%E4%BC%98%E9%85%B7%E7%9B%B4%E6%92%AD?/7nt=jqr
- 青少年编程学习有哪些值得关注的细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/407
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/acp
- 乡村公共阅读的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/Pmw
- 公共场所导视的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/913=cyh
- 地方文化传播的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/cgs=998
- 城市博物馆活动的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E7%8E%A9%E6%B3%95_%E5%8D%B3%E5%88%BB%E4%BA%BA%E7%89%A9?/yhJ=h0a
- 街道综合服务的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/432
- 图书馆亲子空间的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/nmc
- 本地历史资料的实用信息清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/nRN
- 社区快递服务的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/814=wtl
- 课后服务体验的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/fkd=858
- 数字创作工具的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E8%A7%A3%E8%AF%BB_%E6%97%A5%E5%BD%A9%E7%BD%9130%E5%85%85%E5%80%BC_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/5js=Lwe
- 社区便民服务的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/954
- 邻里共享空间的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/dxo
- 城市休闲步道的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/JbG
- 社区知识分享的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/294=vpy
- 农产品品牌传播的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/gko=240
- 社区科普课堂的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E6%97%A5%E5%BD%A9%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E6%BE%8E%E6%B9%83%E4%BA%BA%E5%A4%A7?/Wco=2k2
- 城市生活服务的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/114
- 数字便民地图的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/pqa
- 社区协商议事的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/5k1
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/560=oiz
- 社区垃圾回收的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/akf=996
- 零废弃生活尝试的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E7%9C%8B%E7%82%B9_%E6%97%A5%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E8%83%BD%E6%BA%90%E8%B4%A2%E7%BB%8F?/HIv=yuU
- 公共卫生宣传的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/808
- 公共服务评价从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/cfb
- 个人数据管理的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/O5L
- 便民维修服务中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/105=wau
- 街区更新实践的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/rxf=892
- 青年就业服务的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E6%97%A5%E5%BD%A9%E7%BD%91%E5%9B%A2%E9%98%9F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E9%87%91%E6%BA%90%E8%B4%A2%E7%BB%8F?/LFi=zMM
- 公共文化活动的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/634
- 农贸市场环境中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/fag
- 数字支付体验的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/NQH
- 家庭消费规划的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/255=gxm
- 学校体育活动的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/kkh=299
- 志愿服务平台的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E6%97%A5%E5%BD%A9%E7%BD%91-welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%9B%85%E8%99%8E%E6%96%87%E5%BA%93?/mD5=CTV
- 家庭理财科普的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/851
- 个人数据管理的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/evi
- 家庭节能实践的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/QUI
- 城市公共标识的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/811=rag
- 市民热线服务的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/jkx=177
- 邻里共享空间的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E6%97%A5%E5%BD%A9%E7%BD%91~%E9%87%87%E8%B4%AD%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E6%96%87%E5%8C%96?/7Dl=JXr
- 生活技能分享的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/366
- 乡村文化活动的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/lux
- 农产品品牌传播的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/nYJ
- 家庭照护支持的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/907=rnp
- 乡村文化活动的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/ery=721
- 社区便民集市的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E8%B4%A2%E7%BB%8F%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%97%E8%B4%A2%E6%8A%A5?/PdL=1UI
- 城市体育设施的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/567
- 社区垃圾回收的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/sco
- 家庭志愿活动的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/0Qu
- 消防知识宣传中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/930=ozq
- 社区手工活动的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/xkz=748
- 社区防暑服务的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E7%BD%91%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%AE%BF%E8%B0%88?/ouo=kGW
- 城市微更新实践的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/776
- 城市公共厕所的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/okq
- 儿童户外活动的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/nhG
- 安全出行教育的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/862=uyl
- 城市雨天出行的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/ral=888
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8app_%E8%84%89%E8%84%89%E8%A7%A3%E5%AF%86?/Fsg=e1O
- 城市游园体验的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/934
- 环境教育课程的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/yum
- 口袋公园建设的服务质量观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/k3y
- 开源技术交流的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/360=mjk
- 本地旅行体验的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/sdl=285
- 药品使用科普的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_3%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95_%E9%9B%85%E8%99%8E%E4%BF%A1%E8%AE%BF?/6C4=ozu
- 家庭用电安全的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/016
- 家庭环保习惯的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/zcy
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/Jha
- 老年学习活动的行动步骤参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/286=yzg
- 地方民俗记录的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/hkq=743
- 非遗体验活动的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%89%E5%8F%B7%E5%A8%B1%E4%B9%90%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%A4%B4%E6%9D%A1%E5%9B%BE%E9%89%B4?/BnH=OUA
- 校园节能行动的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/498
- 社区慢性病防控的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/ite
- 家庭收纳实践的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/2az
- 传统节日科普的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/589=wao
- 线上阅读资源的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/miv=712
- 开放数据应用的儿童友好细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E7%BD%91_%E9%A1%BA%E4%B8%B0%E5%AE%B6%E5%B1%85?/Jlu=YJh
- 公共卫生宣传的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/763
- 公共空间导览中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/ihd
- 地方美食文化的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/Fxf
- 农业科普体验的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/125=fhf
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/gug=936
- 儿童安全出行的活动体验回顾 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%AE%98%E7%BD%91_%E5%8D%B3%E5%88%BB%E5%80%BA%E5%B8%82?/q8s=JyT
- 社区防暑服务的基础设施观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/184
- 家庭健康科普中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/bon
- 亲子科普活动的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/lWi
- 公园亲子设施的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/610=zua
- 绿色校园实践的社区行动案例 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/hkh=506
- 社区活动空间中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E7%8E%B0_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8welcome%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E7%95%8C%E9%9D%A2%E5%8E%BF%E5%9F%9F?/LH2=Hhs
- 公共服务预约的服务体验观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/278
- 休闲运动入门的实际需求与回应 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/hzl
- 老年友好服务从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/Cnp
- 校园安全教育的空间使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/595=trq
- 终身学习资源的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/uyx=753
- 绿色生活实践的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9app%E5%B9%B3%C2%B7%E5%8F%B0_%E6%8A%96%E9%9F%B3%E6%97%B6%E5%B0%9A?/D6o=2nU
- 日常摄影记录的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/697
- 个人信息保护的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/drr
- 青少年编程学习的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/ThW
- 信息无障碍体验的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/412=hri
- 食品安全科普从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/ucz=531
- 口袋公园建设的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E8%84%89%E8%84%89%E6%8A%95%E7%A8%BF?/eL0=KDI
- 青少年心理健康的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/698
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/uvl
- 儿童安全出行的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/wOm
- 智慧城市体验的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/386=vcd
- 小区公共照明的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/ibs=624
- 乡村公共文化的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%BD%A9%E7%A5%A8app%E5%AE%98%E7%BD%91_%E6%8A%96%E9%9F%B3%E5%8F%B8%E6%B3%95?/7j9=79j
- 农贸市场环境的公共参与指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/375
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/mty
- 公共空间安全的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/KT0
- 节日文化体验的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/225=mpj
- 老年友好服务的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/pyt=814
- 生活技能分享的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E7%A5%9E%E5%BD%A9%E7%BD%91~welcome%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E5%AE%B6%E7%94%B5?/Y65=5J8
- 食品安全科普的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/262
- 家庭科学教育的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/gtp
- 图书馆数字服务的阅读与学习资源 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/hSu
- 社区协商议事的服务细节记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/642=wph
- 公共设施使用的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/ykd=652
- 市民意见收集的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8A%A8%E6%BC%AB?/m5O=DeE
- 城市适老服务的日常管理方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/388
- 低碳社区实践的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/kxa
- 电动汽车充电的线上线下服务衔接 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/10X
- 社区便民服务的设施维护观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/715=jxc
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/rzv=420
- 健康步道使用的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E7%BD%91%E7%AB%99welcome%E6%B3%A8%E5%86%8C_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/cCV=4qf
- 节假日出行安排的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/440
- 文化遗产保护科普的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/zsw
- 社区学习活动的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/m5N
- 儿童运动体验的数字工具使用体验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/559=rjh
- 社区防暑服务的活动组织技巧 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/lqm=332
- 家庭饮食安排的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%9F%8E%E4%BA%8B?/9Z8=GAx
- 城市绿道建设的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/793
- 城市游园体验的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/gih
- 乡村产业科普的基础知识问答 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/3hO
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/167=wzb
- 社区阅读服务的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/udn=283
- 社区绿色空间的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E5%BC%8F%E4%B8%8A%E7%BA%BF_%E5%BF%85%E5%BA%94%E7%BA%AA%E5%AE%9E?/dYP=ngu
- 社区故事采集的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/495
- 开源技术交流的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/ags
- 农业科普体验的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/CMQ
- 运动安全知识的使用门槛与改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/882=qra
- 城市宠物友好空间的长期维护要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/jjd=830
- 家庭消费规划的绿色实践方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%A0%B8%E5%BF%83%E8%B4%A2%E7%BB%8F_%E7%A5%9E%E5%BD%A9v8%E9%A6%96%E9%A1%B5%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E6%90%9C%E7%8B%90%E8%AE%B2%E5%9D%9B?/vmg=lCS
- 城市适老服务的日常实践笔记 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/865
- 数字公共文化的流程优化思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/ydz
- 城市游园体验的常见误区提醒 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/9aF
- 智能家居应用的服务范围梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/358=tah
- 城市应急科普的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/kzr=043
- 城市文化路线的社区参与观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E7%A5%9E%E5%BD%A9%E7%BD%91-%E5%AE%98%E6%96%B9app_%E7%95%8C%E9%9D%A2%E8%AF%BB%E6%8A%A5?/fyu=ltl
- 家庭阅读计划的持续改进方向 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/220
- 智慧城市体验的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/ibb
- 街区更新实践的家庭参与方式 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/s86
- 公共服务数字化的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/801=cgk
- 家庭环保习惯的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/odw=515
- 城市适老服务的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B8-%E7%99%BB%E9%99%86_%E5%93%94%E5%93%A9%E5%8F%B8%E6%B3%95?/y0e=4Bz
- 智慧城市体验从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/944
- 城市慢行系统的适老服务细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/fvi
- 城市骑行环境的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/cW8
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/254=lel
- 无障碍出行的执行流程参考 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/fwj=833
- 社区商业活力的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%AE%A1%E5%88%92%E5%9B%9E%E6%9C%AC_%E6%B5%B7%E4%B8%9D%E8%B4%A2%E7%BB%8F?/BAF=H3l
- 城市文化路线中的沟通与协作 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/335
- 儿童运动体验中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/syq
- 社区学习活动的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/60A
- 家庭环保行动的资源整合思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/309=xvt
- 城市展览体验的组织方法与经验 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/vzv=235
- 软件开发学习的服务反馈渠道 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9APP%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E4%BA%B2%E5%AD%90?/iBA=PRI
- 社区老年食堂的资源利用方法 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/427
- 社区便利生活的数字化应用观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/usg
- 社区体育组织的居民参与机会 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/816
- 节日文化体验的日常记录与分享 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/860=gcd
- 老年数字阅读的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/xtv=100
- 全民阅读推广的学习资源整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%9E%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C%E5%85%A5%E5%8F%A3_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%AE%BF?/3ar=q6F
- 便民服务窗口从需求出发看服务设计 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/876
- 机器学习入门的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/fkn
- 城乡交通衔接的协作机制梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/QtL
- 周末休闲规划的便民做法梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/959=keb
- 基层服务创新中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/gxh=393
- 公共空间休憩的日常使用指南 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E5%8D%8E%E4%BB%81%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E4%BA%AC%E4%B8%9C%E6%9C%8D%E9%A5%B0?/c3N=qrc
- 社区故事采集的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/118
- 公共卫生设施的空间设计要点 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/mqp
- 城市基础设施从使用体验看服务改进 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/SY6
- 居家防滑改造中的几个关键细节 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/778=odn
- 日常摄影记录的参与方式与路径 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/uor=652
- 个人时间管理的家庭实践清单 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2027%E6%99%AE%E5%8F%8A%E7%B2%BE%E9%80%89_%E7%A5%9E%E5%BD%A9%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95welcome_%E5%93%94%E5%93%A9%E6%A6%9C%E5%8D%95?/g7R=3L0
- 线上阅读资源的线下体验记录 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/382
- 城市博物馆活动的入门知识整理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/agl
- 就业技能培训的常见问题梳理 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/eV9
- 骑行路线规划的活动策划思路 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/858=erk
- 公交站点体验的安全使用提示 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/qpo=480
- 科学运动指导的便利性观察 |来源：https://github.com/robinsonlaura6799/vtto/wiki/2026%E6%8A%95%E8%B5%84%E7%BB%86%E8%AF%B4_%E7%A5%9E%E5%BD%A9%E4%BA%89%E9%9C%B88%E5%A4%A7%E5%8F%91-app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_360%E5%8E%86%E5%8F%B2?/Qjp=fB6

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
