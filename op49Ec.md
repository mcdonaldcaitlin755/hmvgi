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

- 公园亲子设施的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/tno=556
- 社区便民集市的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BE%85%E5%8A%A9%E5%99%A8_%E8%84%89%E8%84%89%E7%A7%81%E5%8B%9F?/RLS=0EK
- 文化讲座服务的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/502
- 小区公共照明的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/ymt
- 城市慢跑路线的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/Bcu
- 节约用水实践的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/908=yuc
- 应急物资管理的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/sgm=077
- 家庭安全提示的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8A%80%E5%B7%A7_%E4%BA%91%E5%88%9B%E8%B4%A2%E7%BB%8F?/Fqd=hMO
- 城市文明出行的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/811
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/xmt
- 城市基础设施的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/V52
- 社区信息发布的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/021=nch
- 图书借阅体验的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/tue=245
- 乡村电商实践的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/MDe=mG2
- 数字艺术创作的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/278
- 消防知识宣传的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/edx
- 老年人出行服务的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/SJ3
- 数字创意课程中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/759=wuv
- 社区法律科普的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/gvy=279
- 公共设施维护的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86829%E5%BD%A9%E7%A5%A85%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%99%BA%E8%83%BD%E8%B4%A2%E7%BB%8F?/NJv=Tcc
- 城市步行友好的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/144
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/ngy
- 科学观察活动的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/Ouf
- 社区便民集市的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/198=fww
- 社区阅读服务的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/txf=451
- 社区托育服务的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E5%BF%AB3%E6%B5%8B%E8%AF%95%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%BA%94%E7%BB%BC%E8%89%BA?/M1K=hvj
- 老年智能设备的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/980
- 食品配送体验的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/ahh
- 数字创作工具的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/PzW
- 在线教育体验的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/302=acg
- 科技馆参观体验的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/ibx=596
- 家庭健康管理的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%88%86%E5%88%86%E5%BF%AB3%E6%99%BA%E8%83%BD%E9%A2%84%E6%B5%8B%E9%80%89%E5%8F%B7%E5%99%A8_%E7%BD%91%E6%98%93%E8%AE%BA%E5%9D%9B?/SYz=KYF
- 绿色办公实践的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/711
- 乡村产业科普的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/yfj
- 公共设施维护的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/8Re
- 食品安全科普的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/708=fsv
- 城市文明实践的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/dny=862
- 公园休闲体验的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E5%88%86%E5%88%86%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E7%9A%84%E5%BF%AB3%E8%AE%A1%E5%88%92_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/ZOx=Dqb
- 个人信息保护的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/323
- 家庭收纳实践的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/dkl
- 社区邻里服务的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/Wc4
- 绿色出行服务的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/876=vsb
- 社区阅读服务的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/egq=219
- 线上阅读资源的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90%E8%BD%AF%E4%BB%B6_%E6%96%B0%E6%B5%AA%E6%98%9F%E5%BA%A7?/MEH=CUn
- 社区修缮行动的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/609
- 乡村公共阅读的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/wau
- 数字地图应用的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/DZk
- 乡村休闲旅游的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/512=noq
- 家庭阅读计划的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/nus=351
- 家庭消费规划的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E5%BF%AB3%E8%AE%A1%E5%88%92_%E8%B0%B7%E6%AD%8C%E4%BA%BA%E5%A4%A7?/JLy=LwU
- 全民阅读推广从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/816
- 网络安全教育从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/dql
- 终身学习资源的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/LNt
- 城市休闲步道的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/258=dzb
- 节能家电使用的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/ofn=681
- 数字便民地图的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%88%86%E5%88%86pc%E9%A2%84%E6%B5%8B%E5%87%86%E7%A1%AE%E7%8E%87100%25%E8%BD%AF%E4%BB%B6_%E6%90%9C%E7%8B%97%E4%BF%A1%E8%AE%BF?/9fe=pUE
- 邻里共享空间的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/399
- 线上阅读资源的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ulk
- 电动汽车充电的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/vrC
- 无障碍信息设计从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/156=vxr
- 社区环保活动的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/jum=985
- 基层健康服务的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_%E5%88%86%E5%88%86%E5%BF%AB3%E7%BD%91%E9%A1%B5%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E4%B8%87%E7%9B%9B%E8%B4%A2%E7%BB%8F?/SyU=hwF
- 社区生活指南中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/615
- 健康步道使用的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/eut
- 家庭食品保存的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/J6e
- 志愿服务平台的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/146=enh
- 传统手工艺体验的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/keu=481
- 社区文化传播的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E7%9F%A5%E9%81%93_%E5%88%86%E5%88%86%E9%A6%99%E6%B8%AF%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%88%86%E6%9E%90_%E5%BF%AB%E6%89%8B%E5%8F%B7%E5%A4%96?/Pw8=SN6
- 社区花园共建的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/875
- 无障碍出行的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/sah
- 公共空间安全的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/lue
- 社区儿童活动的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/515=iwp
- 家庭健康科普的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/zxd=060
- 城市便民驿站的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%A0%8F%E7%9B%AE_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E7%B2%BE%E5%87%86%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%89%E9%98%B2?/ggW=0Zn
- 节能生活方式的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/351
- 数字学习资源的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/tsm
- 小区停车协商的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/rQe
- 家庭用电安全的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/052=rma
- 公共卫生宣传的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/cjd=554
- 乡村教育资源的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%96%B9%E6%B3%95_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/2Vd=WuQ
- 网络安全教育的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/828
- 城市公共艺术中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/qct
- 公共健身器材的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/xah
- 亲子阅读活动的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/757=bog
- 邻里互助活动的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/sgt=916
- 家庭节能设备的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E8%A7%84%E5%88%92_%E5%88%86%E5%88%863%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%88%86%E6%83%85?/JwG=Yog
- 农产品品牌传播的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/333
- 线上阅读资源的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/mlu
- 青年职业探索的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/UfG
- 家庭园艺实践的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/758=cnv
- 社区垃圾分类的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/jll=514
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%BB%8A%E6%97%A5%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E6%9E%81%E9%80%9F%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%B3%95%E5%BE%8B?/Mdx=6KV
- 城市步行环境的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/506
- 基层服务创新的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/noh
- 零废弃生活尝试的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/U9O
- 城市水环境观察的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/257=ipw
- 城市噪声观察的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/uoc=381
- 数字地图应用的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E5%BF%AB3%E5%9C%A8%E7%BA%BF_%E7%99%BE%E5%BA%A6%E5%8D%83%E5%B8%86?/EEU=XNX
- 低碳社区实践的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/052
- 节约用水实践的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/axa
- 乡村电商实践的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/Lhv
- 家庭环保行动的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/083=ylw
- 软件开发学习的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/yzv=569
- 城市公共饮水的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86pc2.8%E8%B5%B0%E5%8A%BF%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E7%88%B1%E5%A5%87%E8%89%BA%E5%8A%A8%E6%BC%AB?/tYe=t7X
- 生活垃圾减量的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/836
- 数字阅读服务的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/lqm
- 城市应急科普的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/IEc
- 城市公共厕所的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/569=xlm
- 城市绿道建设的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/glj=252
- 光伏知识科普的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E4%B8%93%E5%AE%B6%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E8%B4%A2%E7%BB%8F%E4%BF%A1%E6%89%98?/tdt=OvN
- 社区绿色空间的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/338
- 数字支付体验的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/asl
- 家庭照护支持的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/cgU
- 数字创作工具的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/804=epm
- 数字政务体验的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/fdy=946
- 低碳社区实践的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E6%99%BA%E8%B4%A2%E7%BB%8F?/6DD=O21
- 家庭健康管理中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/226
- 社区读书角建设的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/hjg
- 青少年科技社团从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/k1B
- 绿色快递包装的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/986=iqt
- 社区教育资源的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/vin=629
- 校园节能行动从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%BD%AF%E4%BB%B6_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%8F%B7%E5%A4%96?/jq3=9wU
- 城市生活服务的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/081
- 社区应急准备的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/cvj
- 居家适老化改造的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/SyS
- 远程协作工具的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/517=wmx
- 乡村公共服务的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/vof=097
- 机器学习入门的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%8E%8B%E7%89%8C_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E8%BD%AF%E4%BB%B6%E5%85%8D%E8%B4%B9_%E8%99%8E%E5%97%85%E5%8E%86%E5%8F%B2?/EhQ=BUm
- 城市公共标识的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/433
- 生活垃圾减量的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/erj
- 社区共享书架的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/dfb
- 社区文化传播的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/846=zum
- 城市应急广播的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/nzz=905
- 社区阅读服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%9B%98%E7%82%B9%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%AE%A1%E5%88%92%E7%BD%91_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%8F%B7%E5%A4%96?/9jA=8bz
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/990
- 公共设施维护的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/opt
- 市民热线服务的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/ZUF
- 数字支付体验的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/550=egq
- 老年人出行服务的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/ajk=198
- 公共健身器材的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BD%AF%E4%BB%B6_%E6%8A%96%E9%9F%B3%E8%A6%81%E9%97%BB?/ZOJ=5ht
- 街区小店体验的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/532
- 读书会组织的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/umh
- 邻里互助活动的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/Tkd
- 城乡交流活动的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/174=yfc
- 城市绿道建设的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/jtw=448
- 家庭环保行动的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E9%A2%91%E9%81%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86%E8%BD%AF%E4%BB%B6_%E8%B0%B7%E6%AD%8C%E6%97%B6%E8%AF%84?/vhn=wAO
- 便民维修服务的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/733
- 电动汽车充电的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/txi
- 社区庭院绿化的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/uHW
- 公共交通接驳的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/627=sae
- 软件开发学习的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/spb=330
- 城市游园体验的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91%E7%AB%99_%E5%BE%97%E7%89%A9%E6%94%BF%E5%8A%A1?/bio=MDs
- 城市文明出行的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/499
- 城市生活服务的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/xzr
- 环境监测科普的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/vZ8
- 数字生活课堂的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/362=kro
- 城市社区治理的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/wlb=556
- 基层服务创新的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E8%AF%86_%E5%88%86%E5%88%86%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B_%E5%93%94%E5%93%A9%E9%94%90%E8%AF%84?/WAG=eaN
- 城市公共空间的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/795
- 乡村产业科普的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/abm
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/NXK
- 公园亲子设施的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/088=xny
- 绿色生活实践的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/nlg=508
- 邻里共享空间的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%9C%80%E7%B2%BE%E5%87%86%E8%BD%AF%E4%BB%B6_%E5%A4%B4%E6%9D%A1%E4%B9%A6%E7%94%BB?/yUV=g4S
- 新能源知识普及的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/336
- 地方旅游导览的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/mhg
- 日常摄影记录的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/Hz5
- 社区文化节活动的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/539=huu
- 旧物循环利用的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/cog=017
- 城市公共标识的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B_%E6%8A%96%E9%9F%B3%E5%9C%88%E5%AD%90?/Foq=BIY
- 急救知识普及的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/201
- 乡村休闲旅游的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/zpu
- 社区安全巡查的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/EZE
- 社区阅读服务中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/543=knq
- 老年学习活动的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/mdl=866
- 城市绿色交通的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E5%88%9B%E6%8A%95?/uaG=Jzk
- 公共空间安全的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/010
- 社区家校合作的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/bng
- 城市农夫市集的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/QFi
- 社区消防演练的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/361=gui
- 数字支付体验从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/jgy=412
- 校园安全教育的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E7%8E%B0_%E5%88%86%E5%88%86%E5%B9%B8%E8%BF%90%E5%BF%AB3%E5%9C%A8%E7%BA%BF%E9%A2%84%E6%B5%8B%E7%BD%91_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/PQi=ylH
- 青年就业服务的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/802
- 校园安全教育的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/gjc
- 开放数据应用的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/MkB
- 校园社团活动的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/576=mzs
- 公共空间照明的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/ipe=944
- 跨代沟通活动的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%BC%80%E6%8C%82_%E8%B1%86%E7%93%A3%E7%A8%8E%E5%8A%A1?/iab=cMl
- 城市文明实践的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/535
- 家庭急救准备的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/inj
- 创业经验分享的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/KbU
- 城市公共标识的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/411=fpf
- 老年人文化生活的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/bet=874
- 城乡公共服务的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%A7%84%E5%BE%8B_%E5%BE%97%E7%89%A9%E7%BE%8E%E8%82%A1?/tvU=TOP
- 城市夜间生活的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/858
- 家庭食品保存的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/dix
- 数字支付体验的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/Kxc
- 社区休闲设施的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/759=mka
- 农贸市场环境的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/gae=005
- 社区休闲设施的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%B2%BE%E5%87%86_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/KdV=JS9
- 远程协作工具的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/286
- 在线学习体验的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/khw
- 旧物循环利用的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/hTX
- 健康饮水科普的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/271=mso
- 乡村电商实践的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/mfl=166
- 城市便民驿站的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%B8%8B%E6%9C%9F%E5%87%BA%E5%8F%B7_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/Kel=mBZ
- 图书馆亲子空间的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/025
- 农产品消费体验的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/tbk
- 城市便民驿站的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/XJQ
- 乡村公共文化的协作机制梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/945=eyr
- 文化场馆预约的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/fne=543
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E9%A3%8E%E5%90%91_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%BD%91_%E5%87%A4%E5%87%B0%E9%80%9A%E4%BF%A1?/rQX=PcJ
- 社区体育组织的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/710
- 家庭陪伴活动的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/mcv
- 家庭阅读计划的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/AtX
- 老年人文化生活的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/098=hzc
- 开源技术交流的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/obl=126
- 地方旅游导览的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%A5%9E%E5%99%A8%E8%BD%AF%E4%BB%B6_%E7%9F%A5%E4%B9%8E%E4%BA%BA%E5%A4%A7?/dGN=vUb
- 社区垃圾回收的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/384
- 个人信息保护的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/sub
- 城市文明出行的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/TIY
- 社区便民集市从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/008=zsk
- 劳动教育实践的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/ftc=562
- 科学健身方法的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%AF%BC_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%B7%A8%E5%BA%A6_%E8%8A%92%E6%9E%9C%E5%8C%BB%E8%8D%AF?/IQG=m9k
- 家庭园艺实践的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/586
- 公共图书馆服务的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/ngv
- 本地消费场景从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/EcT
- 市民热线服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/378=ymg
- 数字艺术创作的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/cfk=037
- 家庭安全提示的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E7%82%B9%E6%95%B0_%E8%85%BE%E8%AE%AF%E5%85%AC%E7%9B%8A?/Bn3=JDF
- 家庭教育交流的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/712
- 家庭食品保存的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/uzd
- 老年人日常照护的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/VDn
- 智慧停车服务的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/084=mqr
- 街道综合服务的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/xho=699
- 科学观察活动的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E4%BA%A4%E6%B5%81_36%E6%B0%AA%E6%B8%B8%E6%88%8F?/UC0=uAx
- 志愿服务平台的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/569
- 家庭急救准备的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/rog
- 城市基础设施的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/Tju
- 健康饮水科普的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/144=dbq
- 基层健康档案的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/qkt=081
- 数字地图应用的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E8%BE%85%E5%8A%A9%E5%99%A8%E5%8F%AF%E4%BF%A1%E5%90%97_360%E6%95%99%E8%82%B2?/GPG=XQz
- 公共卫生设施的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/724
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/qhs
- 节气饮食文化的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/jDb
- 青少年职业启蒙的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/103=cww
- 图书馆数字服务的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/mjk=381
- 社区便民集市的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E5%AD%A6%E4%B9%A0_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E5%99%A8_%E4%BC%98%E9%85%B7%E6%95%99%E8%82%B2?/qcF=log
- 基层健康服务的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/300
- 社区公共卫生的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%81%9A%E7%84%A6_%E5%88%86%E5%88%86%E5%BF%AB3%E9%A2%84%E6%B5%8B%E6%8E%A8%E8%8D%90_%E4%BC%98%E9%85%B7%E5%B9%B6%E8%B4%AD?/hkz

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
