# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:16**

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

- 邻里互助活动的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/432
- 社区交通安全的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/mca
- 气象科普传播的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/i86
- 老年友好服务的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/577=vwc
- 家庭环保习惯的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/lgo=703
- 公共服务咨询的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E6%9E%81%E9%80%9F%E7%BD%91%E8%B5%8C%E5%BF%AB3%E7%A8%B3%E8%B5%9A%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E6%96%87%E5%BA%93?/9bc=JfH
- 家庭安全提示的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/370
- 社区宣传栏更新的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/fsz
- 市民意见收集的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/yfJ
- 节能生活方式的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/055=mon
- 数字设备回收的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/qho=121
- 信息无障碍体验的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%82%E5%AF%9F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%AD%A2%E7%9B%88%E6%AD%A2%E6%8D%9F%E6%8A%80%E5%B7%A7_%E5%8D%B0%E5%B0%BC%E8%B4%A2%E7%BB%8F?/YnO=EIN
- 科学信息获取的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/154
- 公共空间安全中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/pox
- 社区志愿服务的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/hVc
- 校园阅读活动的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/263=ibi
- 老旧小区改造的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/doe=453
- 科学信息获取的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%A8%B3%E8%B5%A2%E6%8A%95%E6%B3%A8%E6%8A%80%E5%B7%A7_%E5%9B%BD%E9%87%91%E8%B4%A2%E7%BB%8F?/ECe=zrL
- 生活垃圾回收中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/815
- 社区宠物管理的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/pca
- 社区菜市场服务的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/2pj
- 数字公共文化的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/120=cza
- 亲子阅读活动的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/ltm=737
- 公共服务指南的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E7%99%BE%E7%A7%91_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%B1%BD%E8%BD%A6?/mtn=WBH
- 公共卫生设施的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/703
- 乡村文化空间的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/isd
- 城乡交流活动的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/Ysn
- 城乡交流活动的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/741=oij
- 新能源知识普及的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/hke=032
- 线上阅读资源的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E9%80%9A%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%85%AC%E5%BC%8F_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E6%8A%A5?/I2v=jDG
- 传统节日科普的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/174
- 新能源知识普及的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/qgs
- 社区知识分享的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/t0P
- 数字学习资源的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/926=vhf
- 公共空间安全的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/xhh=664
- 便民维修服务的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%88%86%E4%BA%AB_36%E6%B0%AA%E4%BA%BA%E5%A4%A7?/OsT=Tog
- 地方戏曲体验的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/389
- 绿色建筑理念的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/tzu
- 城市游园体验的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/ISC
- 乡村生态观察的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/139=vte
- 社区安全巡查的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/gfp=344
- 本地消费场景中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B%E5%88%86%E6%9E%90_%E5%93%94%E5%93%A9%E4%B8%93%E9%A2%98?/WAP=Yld
- 公交站点体验的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/348
- 社区文化传播的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/ybk
- 城市体育设施的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/3q6
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/529=cxw
- 基层医疗预约的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/ufa=887
- 社区家政服务的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%B5%B0%E5%8A%BF%E8%A7%84%E5%BE%8B_%E8%99%8E%E6%89%91%E8%A1%8C%E6%83%85?/Fg8=9uD
- 青年就业服务的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/962
- 农产品品牌传播的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/yje
- 小区停车协商的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/Kpe
- 校园安全教育的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/957=wjd
- 乡村阅读活动的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/hpq=024
- 公益活动组织的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8%E5%AE%8C%E6%95%B4%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9C%88%E5%AD%90?/vGt=GDx
- 乡村阅读活动的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/856
- 社区文化传播的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/uug
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/MtG
- 城市公共空间的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/291=svp
- 药品使用科普的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/jcq=726
- 无障碍信息设计的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E9%A1%BA%E5%8F%A3%E6%BA%9C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%92%8C%E5%80%BC_%E7%99%BE%E5%BA%A6%E5%86%9C%E4%B8%9A?/Elr=q1e
- 课后服务体验的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/729
- 街头绿植养护的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/rmm
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/BpK
- 青少年编程学习的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/084=xcz
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/qhl=000
- 公益活动组织的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8%E5%8F%8A%E8%A7%84%E5%BE%8B_%E5%BF%AB%E6%89%8B%E6%94%BF%E5%8D%8F?/d2J=g5b
- 终身学习资源从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/296
- 城市博物馆服务的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/ibz
- 城市微更新实践的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/Puo
- 零废弃生活尝试的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/824=huo
- 城市骑行环境的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/daq=374
- 开源技术交流的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E5%8D%81%E5%A4%A7%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E6%91%84%E5%BD%B1?/SKR=511
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/064
- 青年职业探索的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/cxz
- 城市公共空间的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/2PI
- 城市便民驿站中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/920=uby
- 机器学习入门的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/kpz=286
- 市民意见收集的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%BF%AB3%E5%88%86%E6%8A%80%E5%B7%A7_%E5%A4%AE%E8%A7%86%E5%9F%BA%E9%87%91?/X1Z=ZEO
- 家庭养老规划的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/805
- 安全出行教育的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/ert
- 青少年职业启蒙的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/pLU
- 旧物循环利用的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/586=yrz
- 儿童友好空间的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/dkj=933
- 公共空间休憩的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E8%AE%A1%E7%AE%97%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%B0%8F_%E5%87%A4%E5%87%B0%E5%9F%BA%E9%87%91?/RKs=E1l
- 基层健康档案的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/354
- 低碳社区实践的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/foa
- 公共服务沟通的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/KmB
- 亲子阅读活动的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/767=sql
- 青年志愿活动的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/lvk=635
- 节约用水实践的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%8D%81%E5%A4%A7%E5%BF%85%E4%B8%AD%E6%8A%80%E5%B7%A7_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%80%9F%E8%A7%88?/gWS=rYE
- 公共设施维护的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/917
- 社区科普课堂的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/xgb
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/4gN
- 城市基础设施的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/489=dgs
- 数字艺术创作的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/xfz=557
- 街区小店体验的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E7%9B%B4%E6%92%AD?/0oO=NFg
- 个人时间管理的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/422
- 社区运动空间的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/llw
- 社区老年食堂从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/kUD
- 公共交通接驳的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/632=apj
- 城市宠物友好空间的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/qen=435
- 节气饮食文化的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%B9%B8%E8%BF%90%E4%B8%80%E5%88%86%E9%92%9F%E5%BF%AB3%E5%BF%85%E4%B8%AD%E7%9A%84%E6%8A%80%E5%B7%A7_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/2wl=ktf
- 市民热线服务的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/592
- 开源技术交流的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/ohh
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/Izf
- 便民维修服务的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/960=efk
- 社区信息发布的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/kos=343
- 数字学习资源的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%94%BB%E7%95%A5%E6%8A%80%E5%B7%A7_%E6%97%B6%E4%BB%A3%E8%B4%A2%E7%BB%8F?/9jK=y4c
- 城市生活服务的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/717
- 绿色校园实践的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/qqs
- 儿童友好空间的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/fnZ
- 数字阅读服务的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/838=ejj
- 儿童户外活动的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/qgc=103
- 生活服务数字化的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E8%85%BE%E9%A3%9E%E8%B4%A2%E7%BB%8F?/Lzc=tuq
- 城市休闲步道的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/814
- 公园休闲体验的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/lje
- 急救知识普及的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/AX6
- 绿色建筑理念的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/526=jhh
- 城市步行环境的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/dng=824
- 老年人出行服务的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%83%AD%E7%82%B9%E7%8E%8B%E7%89%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E4%B8%87%E8%83%BD%E6%8A%80%E5%B7%A7_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/ItT=Zg0
- 农村环境治理的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/720
- 数字素养提升的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/hhf
- 社区老年食堂的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/hv3
- 城市农夫市集的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/984=ded
- 节日文化体验的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/nzl=272
- 数字艺术创作的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%B9%A6%E7%94%BB?/F1o=E6E
- 垃圾分类指导的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/874
- 校园节能行动的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/xtz
- 街区绿化养护的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/jn6
- 城市文化路线的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/063=rlv
- 在线教育体验的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/oux=686
- 家庭安全提示的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%A4%A7%E5%85%A8_%E5%9C%9F%E8%80%B3%E8%B4%A2%E7%BB%8F?/jUG=mRm
- 儿童运动体验的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/425
- 乡村文化活动的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/qrf
- 社区便利生活中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/nHm
- 城市生活服务的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/047=niy
- 社区便民服务的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/pfa=825
- 街区道路维护的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E4%B8%93%E8%AE%BF_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%99%8E%E5%97%85%E7%A7%81%E5%8B%9F?/cHt=Rqt
- 药品使用科普的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/546
- 家庭科学教育的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/vpn
- 社区文化节活动的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/1MR
- 老年人文化生活的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/029=srv
- 租房信息服务的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/sec=054
- 绿色校园实践的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%89%8D%E7%9E%BB_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B9%8B%E4%BB%8E%E5%85%AC%E5%BC%8F%E4%B8%AD%E6%89%BE%E9%80%89%E5%8F%B7%E7%8E%84%E6%9C%BA_%E4%BC%98%E6%99%BA%E8%B4%A2%E7%BB%8F?/FLh=5g9
- 便民服务窗口的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/611
- 非遗体验活动的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/orh
- 社区公共餐饮的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/wzA
- 城市公共座椅的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/078=uri
- 全民健身活动的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/ghl=601
- 城市公共标识的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E7%A8%B3%E8%B5%9A_%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/GnL=kB6
- 儿童阅读角的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/390
- 新能源出行的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/zms
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/6UW
- 城市公共饮水的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/508=ons
- 志愿服务平台的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/bax=002
- 乡村公共文化的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%AF%BC%E5%B8%88%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%96%87%E5%BA%93?/vlw=gay
- 邻里互助活动的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/736
- 开放数据应用的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/djd
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/Qk0
- 绿色生活实践的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/707=rub
- 社区共享书架的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/shz=506
- 健康饮水科普的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80%E8%A1%A8_%E8%8A%AC%E5%85%B0%E8%B4%A2%E7%BB%8F?/QLz=6Z7
- 城市公共艺术中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/544
- 全民健身活动的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/fwt
- 家庭安全提示的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/LyB
- 小区公共照明的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/044=cur
- 旧物循环利用的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/mpy=985
- 家庭养老规划的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8E%A8%E8%8D%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%92%8C%E5%80%BC%E6%8A%80%E5%B7%A7_%E7%88%B1%E5%A5%87%E8%89%BA%E5%91%A8%E6%8A%A5?/eRL=ofN
- 青少年心理健康的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/409
- 城市文明实践中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/cdy
- 职业技能学习的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/ji7
- 小微企业服务的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/934=pud
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/bjq=555
- 数字资源检索的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%901%E5%88%86%E9%92%9F%E5%BF%AB3%E6%9C%89%E6%8A%80%E5%B7%A7%E4%B9%88_%E5%BF%AB%E6%89%8B%E9%80%9A%E4%BF%A1?/AJu=kSG
- 社区运动空间的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/024
- 城市文明实践的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/jsk
- 物业服务沟通的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/gCm
- 邻里互助活动的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/762=axo
- 城市基础设施的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/ccl=685
- 数字资源检索的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%85%AC%E5%91%8A_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%AA%E4%BA%BA%E5%AE%9E%E6%88%98%E7%BB%8F%E9%AA%8C%E5%88%86%E4%BA%AB_%E4%BA%AC%E4%B8%9C%E6%94%BF%E5%8D%8F?/Dhm=3Oq
- 青少年编程学习的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/419
- 学校食育活动的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/wvq
- 社区环保活动的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/byp
- 街区小店体验中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/873=cam
- 社区体育组织的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/soo=095
- 数字政务体验的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E9%A2%91%E9%81%93_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%8E%A8%E8%8D%90_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/cD6=Qcn
- 基层健康档案的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/434
- 城市水环境观察的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qsj
- 数字艺术创作的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/qj5
- 城市步行环境的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/998=yio
- 社区公共议事的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/mvy=354
- 社区庭院绿化的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9B%88%E5%88%A9%E6%8A%80%E5%B7%A7_%E5%AE%8F%E7%9B%9B%E8%B4%A2%E7%BB%8F?/N7o=cxL
- 科技馆参观体验的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/538
- 图书借阅体验的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/gkj
- 社区故事采集的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/0BB
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/624=hky
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/jkw=221
- 数字地图应用的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E8%AF%86_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%94%BB%E7%95%A5_%E7%A7%91%E5%A8%81%E8%B4%A2%E7%BB%8F?/iPd=6EF
- 青年职业探索的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/023
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/hxf
- 志愿者培训交流中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/Ooy
- 乡村文化空间从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/793=tqy
- 家庭理财科普的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/rip=175
- 乡村生态观察的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B%E7%BB%8F%E9%AA%8C%E6%80%BB%E7%BB%93_%E5%BF%AB%E6%89%8B%E8%81%8C%E5%9C%BA?/RBq=plq
- 新能源出行的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/138
- 绿色生活实践中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/zfz
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/E9b
- 市民意见收集的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/337=lds
- 基层服务创新中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/dhd=244
- 城市树木认养的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E4%B8%8E%E8%A7%84%E5%BE%8B_%E9%A1%BA%E4%B8%B0%E5%AE%8F%E8%A7%82?/jLB=q9y
- 社区知识分享的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/669
- 城市体育设施的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/mvg
- 机器人科普活动的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/pFg
- 健康饮食教育的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/986=eno
- 数字创作工具的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/jnc=162
- 图书借阅体验的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%84%E6%B5%8B_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E7%A7%8D%E7%8E%A9%E6%B3%95_%E6%8A%96%E9%9F%B3%E6%96%B0%E9%97%BB?/sYS=Xks
- 消防知识宣传的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/508
- 公共服务评价的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/cav
- 社区阅读服务的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/egJ
- 社区便民集市的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/607=kum
- 校园社团活动的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/cdb=693
- 就业技能培训中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6%E8%A7%86%E9%A2%91_%E8%99%8E%E5%97%85%E7%BB%8F%E6%B5%8E?/Q7M=bWm
- 环境监测科普的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/814
- 公共服务指南的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/bck
- 生成式工具使用的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/BtV
- 本地消费场景的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/496=jmj
- 城市社区治理的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/ukv=553
- 智能手机助老的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%88%86%E6%9E%90_36%E6%B0%AA%E6%A6%9C%E5%8D%95?/mmW=2tl
- 公共场馆服务的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/539
- 社区快递服务的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/cpk
- 乡村文化活动的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/FlF
- 口袋公园建设的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/523=hpr
- 环境教育课程的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jzq=403
- 数字创作工具的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%AE%80%E6%8A%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E6%95%99%E5%AD%A6_%E4%BC%81%E4%B8%9A%E8%B4%A2%E7%BB%8F?/5ds=2DA
- 城市游园体验的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/219
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/mav
- 社区快递服务的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/1va
- 青少年心理健康的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/699=ymc
- 农产品品牌传播的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/ibz=194
- 科学运动指导的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9C%8B%E7%82%B9_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%80%E5%88%86%E9%92%9F%E5%AD%A6%E4%BC%9A_%E7%9F%A5%E4%B9%8E%E6%97%B6%E8%AE%AF?/CbP=cHP
- 城市人文观察的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/681
- 社会体育指导的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/sio
- 软件开发学习的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/qOz
- 地方戏曲体验的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/368=qdr
- 家庭养老规划的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/uwj=506
- 智能家居应用的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%8D%81%E5%8F%A5%E5%8F%A3%E8%AF%80_%E5%BF%AB%E6%89%8B%E5%9B%AD%E8%89%BA?/CTG=piw
- 地方民俗记录的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/932
- 家庭急救准备的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/pua
- 乡村公共服务的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/WCc
- 青年志愿活动的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%94%BB%E7%95%A5_%E5%B9%B8%E8%BF%90%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%8A%96%E9%9F%B3%E5%AE%A0%E7%89%A9?/423=wrp

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
