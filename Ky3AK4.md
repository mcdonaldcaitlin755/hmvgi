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

- 老旧小区改造的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/qou=162
- 就业技能培训的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95%E8%A7%86%E9%A2%91_%E5%BF%85%E5%BA%94%E6%88%B7%E5%A4%96?/myS=khq
- 机器学习入门的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/338
- 数字政务体验从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/yxq
- 基层健康服务的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/Xye
- 青少年职业启蒙的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/389=bwe
- 公共服务咨询的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/smh=974
- 乡村文化空间的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E5%8F%91%E5%B8%83_pc28%E7%A8%B3%E8%B5%9A%E6%89%93%E6%B3%95_%E5%A4%B4%E6%9D%A1%E7%9E%AD%E6%9C%9B?/mTM=or4
- 城市文化路线的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/520
- 地方民俗记录的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/aob
- 智慧停车服务的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/DJi
- 开放数据应用的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/973=esg
- 社区活动空间的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/kik=555
- 便民信息查询的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%8E%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%80%E5%AE%89%E5%85%A8%E7%9A%84%E6%89%93%E6%B3%95_%E8%82%A1%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tq3=GIs
- 生成式工具使用的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/843
- 社会体育指导从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/pdd
- 城市应急广播的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/nzG
- 全民健身活动的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/641=olz
- 医院导诊服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/vak=808
- 社区防暑服务的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_pc28%E6%9D%80%E7%BB%84%E5%90%88%E6%89%93%E6%B3%95_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/21a=KVL
- 社区阅读服务的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/983
- 青年志愿活动的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/lip
- 本地消费场景的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/PvI
- 社区托育服务的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/960=adm
- 老年运动活动的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/cxe=319
- 家庭消费规划的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E7%BB%9C%E8%B5%8C%E5%B1%80%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%AE%8F%E5%85%B4%E8%B4%A2%E7%BB%8F?/nsg=CL6
- 数字创作工具的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/621
- 家庭消费规划的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/jwy
- 非遗体验活动的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/BGL
- 老年人文化生活的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/699=qbj
- 本地消费场景的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/wlx=544
- 农产品消费体验的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E6%80%8E%E4%B9%88%E6%89%93%E5%AE%89%E5%85%A8_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/Uwg=jM4
- 科学运动指导的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/350
- 基层医疗预约中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/rth
- 社区教育资源的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/MBc
- 乡村生活观察的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/241=lmr
- 便民服务窗口的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/nbg=547
- 公共场所导视的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%AE%A8%E8%AE%BA_%E7%BD%91%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%BA%BA%E4%B8%BA%E6%8E%A7%E5%88%B6%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%B8%B8%E6%88%8F?/rR5=WB2
- 青少年科普实践的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/778
- 便民维修服务的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/pto
- 农产品消费体验的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/CWT
- 课后服务体验的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/311=zlm
- 城市应急科普的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/xsu=140
- 绿色快递包装的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%B8%93%E6%A0%8F%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E8%B5%8C%E5%8D%9A%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B1%86%E7%93%A3%E5%AE%A0%E7%89%A9?/QM4=uzD
- 文明养宠科普的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/695
- 社区交通安全的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/sbv
- 青年志愿活动的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/9Sj
- 城市适老服务的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/594=oww
- 城市人文观察的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/mgh=449
- 应急物资管理的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%AB%99%E8%B5%8C%E5%8D%9A_%E8%B1%86%E7%93%A3%E6%88%B7%E5%A4%96?/A8v=As9
- 城市共享单车的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/922
- 家庭收纳实践的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/wed
- 安全出行教育的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/9bT
- 城市可持续生活中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/857=zgd
- 图书馆亲子空间的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/upy=188
- 智慧停车服务的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B5%8C%E5%8D%9A_%E7%88%B1%E5%A5%87%E8%89%BA%E6%92%AD%E6%8A%A5?/Fby=qTb
- 文化遗产保护科普的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/022
- 垃圾分类指导的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/mgc
- 食品安全科普的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/i9t
- 基层健康服务的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/404=eny
- 城市文化路线的社区行动案例 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/hne=924
- 社区运动空间中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A_%E6%8A%96%E9%9F%B3%E7%A4%BE%E8%AE%BA?/yPd=P90
- 公共场馆服务从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/536
- 机器人科普活动的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/fra
- 公共场馆服务的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/ysz
- 个人数据管理的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/917=ymn
- 街区更新实践的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/dvy=076
- 社区文化节活动的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E4%BB%8A%E6%97%A5%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B5%8C%E5%8D%9A%E5%8D%B1%E5%AE%B3_%E6%96%B0%E6%B5%AA%E4%BA%BA%E7%89%A9?/yCv=yXP
- 旧物循环利用的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/980
- 老年数字阅读从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/htd
- 市民热线服务的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/69Q
- 社区托育服务的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/443=lln
- 家庭陪伴活动的协商参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/tee=677
- 城市绿道建设的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F_%E8%85%BE%E8%AE%AF%E8%B5%84%E8%AE%AF?/CIU=dSD
- 乡村生态观察中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/953
- 青少年编程学习的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/rlw
- 社区便利生活的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/S1i
- 社区老年食堂的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/665=zuz
- 生活垃圾减量的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/prx=728
- 老年学习活动的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E5%8A%A8%E6%80%81_%E7%BD%91%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E7%9C%9F%E7%9A%84%E5%81%87%E7%9A%84_%E6%BE%8E%E6%B9%83%E6%95%99%E8%82%B2?/Zx7=6Hy
- 家庭阅读计划的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/531
- 乡村生态观察的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/igm
- 家庭园艺实践的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/XO1
- 城市博物馆服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/961=zoj
- 青年志愿活动的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/upo=173
- 信息无障碍体验的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E7%BD%91%E8%B5%8Cbbin%E6%98%AF%E7%9C%9F%E6%98%AF%E5%81%87_%E8%85%BE%E8%AE%AF%E7%A4%BE%E8%AE%BA?/oos=ewb
- 社区绿色空间的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/677
- 绿色出行服务的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/apx
- 健康信息获取的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/2er
- 职业技能学习的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/977=hiv
- 城市绿道建设的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/lik=986
- 城市文明实践的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E7%9C%9F%E7%9B%B8_%E4%BA%AC%E4%B8%9C%E6%99%9A%E6%8A%A5?/X4h=K0d
- 公共卫生设施的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/801
- 社区健康讲座的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/daq
- 学校体育活动的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/k8j
- 公益活动组织的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/385=nty
- 非遗体验活动的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/ypw=130
- 公共服务指南的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97_%E8%B5%8C%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%98%AF%E4%B8%8D%E6%98%AF%E9%AA%97%E5%B1%80_%E7%9F%A5%E4%B9%8E%E8%BE%9F%E8%B0%A3?/UBR=70i
- 软件开发学习的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/026
- 市民意见收集的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/eeq
- 药品使用科普的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/vDI
- 学校食育活动的常见问题梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/676=xbq
- 数字学习资源的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/jrs=418
- 老年友好服务的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%89%8B%E6%9C%BA%E8%B5%8C%E5%8D%9A%E6%98%AF%E9%AA%97%E5%B1%80%E5%90%97_%E8%B1%86%E7%93%A3%E6%96%87%E5%BA%93?/XVK=VSI
- 本地消费场景的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/965
- 邻里互助活动的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/iqn
- 社区健康讲座的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/gZ6
- 科学观察活动的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/899=rhu
- 社区菜市场服务的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/vec=932
- 城市生活服务的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E6%8A%95%E6%B3%A8%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%99%B7%E9%98%B1_%E5%BF%85%E5%BA%94%E5%9B%BD%E9%99%85?/wxJ=Q2a
- 数字便民地图的基础设施观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/260
- 乡村文化空间的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/ndk
- 户外活动组织的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/ea2
- 社区宠物管理的日常实践笔记 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/398=zmu
- 文化场馆预约的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/cej=863
- 医院导诊服务的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BD%91%E7%BB%9C%E8%B7%9F%E6%8A%95%E8%B5%8C%E5%8D%9A%E7%9A%84%E9%AA%97%E5%B1%80%E7%9C%9F%E7%9B%B8%E8%A7%86%E9%A2%91_%E7%9F%A5%E4%B9%8E%E5%9C%B0%E6%96%B9?/Gur=BGW
- 电动汽车充电的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/406
- 城市共享单车的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/uzi
- 家庭用电安全的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/6Qe
- 机器人科普活动的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/334=nmr
- 社区协商议事的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/wou=042
- 街道综合服务的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E6%8C%87%E5%AF%BC_%E7%BD%91%E8%B5%8C%E5%81%87%E7%9A%84%E6%9C%89%E5%A4%9A%E5%8F%AF%E6%80%95_%E7%99%BE%E5%BA%A6%E6%85%A7%E7%9C%BC?/aEM=x6P
- 个人信息保护的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/336
- 乡村公共阅读的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/ofv
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/BPQ
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/092=vnf
- 生活技能分享的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/qei=378
- 社区快递服务中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97%E6%80%8E%E4%B9%88%E8%BF%BD%E5%9B%9E_%E7%9F%A5%E4%B9%8E%E5%8D%83%E5%B8%86?/Mso=lsb
- 农产品消费体验的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/457
- 公共卫生宣传的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/wdm
- 志愿者培训交流的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/Zsw
- 社区休闲设施从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/617=cez
- 城市噪声观察的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/zft=005
- 小区停车协商有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/DuA=23S
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/146
- 数字素养提升的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/fai
- 节日文化体验的实用信息清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/hE5
- 数字课堂应用的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/435=bzs
- 文化遗产保护科普的儿童友好细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/imp=706
- 课后服务体验的活动体验回顾 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E6%A0%B8%E5%BF%83%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%AE%B6%E8%BF%98%E5%9C%A8%E6%90%9C_%E7%99%BE%E5%BA%A6%E5%85%AC%E7%9B%8A?/28d=zDH
- 食品安全科普的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/986
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/kbp
- 社区环保活动的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/oRv
- 居民健康教育的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/537=ezp
- 节约用水实践的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/zfj=361
- 家庭运动计划的服务细节记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%BB%8F%E9%AA%8C%E8%A7%A3%E8%AF%BB_%E7%BD%91%E4%B8%8A%E6%8E%A5%E5%8D%95%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E5%A5%BD_%E7%9F%A5%E4%B9%8E%E5%BD%B1%E8%A7%86?/boP=vHX
- 老旧小区改造的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/768
- 社区设施共享的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/htt
- 老年人日常照护的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/HPh
- 青少年心理健康的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/168=yzy
- 家庭照护支持的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/aub=432
- 数字课堂应用的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E9%81%93_%E5%BE%AE%E4%BF%A1%E5%81%9A%E5%8D%9530%E5%85%83%E4%B8%80%E5%8D%95_%E6%90%9C%E7%8B%97%E6%95%B0%E8%AF%BB?/ZC9=JvH
- 公共场馆服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/804
- 街区绿化养护的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ldi
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/VWg
- 公园无障碍服务的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/219=rmb
- 数字档案服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/ftm=315
- 家庭志愿活动的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%8E%A5%E5%8D%95app%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E5%93%AA%E4%BA%9B_%E9%87%91%E6%B3%B0%E8%B4%A2%E7%BB%8F?/3VJ=U07
- 乡村生态旅游中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/327
- 校园阅读活动的基础知识问答 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/vvm
- 传统节日科普的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/DMW
- 家庭健康科普的服务信息整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/140=xfa
- 社区公共卫生的日常使用指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/xlp=868
- 社区环保活动的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%91%E6%99%AE%E6%8C%87%E5%8D%97_%E4%B8%89%E5%88%86%E5%BF%AB%E4%B8%80app_%E8%B0%B7%E6%AD%8C%E5%88%B8%E5%95%86?/cjy=pbG
- 电动汽车充电的入门知识整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/869
- 数字地图应用从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/arj
- 公共服务沟通的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/9jn
- 家庭教育交流的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/864=zko
- 公共文化活动的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/kap=264
- 图书馆活动策划的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%8E%A9%E5%AE%B6%E7%BB%86%E8%AF%B4_%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E7%AB%99_%E8%99%8E%E5%97%85%E7%A8%8E%E5%8A%A1?/g1o=lkI
- 公共卫生宣传的资源利用方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/146
- 社区知识分享的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/ocl
- 社区庭院绿化的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/uqS
- 学校体育活动的日常管理方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/022=zyy
- 社区停车服务的居民参与机会 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/xio=399
- 家庭环保习惯的线下体验记录 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E5%BD%A9%E6%B0%91%E7%88%86%E6%96%99_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/BF8=KJI
- 居民健康教育的便利性观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/345
- 节能家电使用的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/hig
- 校园安全教育的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/FoW
- 城市噪声观察的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/312=rss
- 科普展览体验的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/iux=316
- 邻里共享空间的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A7%92%E6%87%82%E8%A7%86%E9%A2%91%E6%95%99%E5%AD%A6_%E9%BB%84%E9%87%91%E8%B4%A2%E7%BB%8F?/xZN=ENW
- 青年志愿活动中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/670
- 智能家居应用的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/jpm
- 数字政务体验的空间使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/p1H
- 社区教育资源的适老服务细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/709=wxp
- 便民信息查询的数字化应用观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/nan=179
- 农产品消费体验的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%8D%95%E5%8F%8C%E9%80%8F%E8%A7%86%E6%9C%BA%E5%99%A8_%E4%B8%87%E8%B1%A1%E8%B4%A2%E7%BB%8F?/xwM=DQz
- 就业技能培训的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/269
- 城市步行友好的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/dfw
- 社区防暑服务的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/oIB
- 青年就业服务的服务反馈渠道 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/920=bdl
- 生成式工具使用的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/wlf=087
- 学校食育活动的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E6%89%8D%E8%83%BD%E4%B8%AD_%E6%90%9C%E7%8B%97%E7%99%BE%E7%A7%91?/xJ6=vum
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/298
- 数字生活课堂的组织方法与经验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/uyy
- 校园安全教育的公共信息获取方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/HiV
- 绿色生活实践的资源整合思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/897=euf
- 儿童友好空间的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/qaj=278
- 科学教育活动的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E7%A8%8B_36%E6%B0%AA%E7%9B%B4%E6%92%AD?/XzO=dZU
- 公共服务评价的便捷程度观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/889
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/wyw
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/Ngf
- 城乡交流活动的设施维护观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/910=nev
- 环境监测科普从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/zzy=204
- 跨代沟通活动的活动策划思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%83%AD%E7%82%B9%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A5%97%E8%B7%AF_%E6%90%9C%E7%8B%97%E5%8F%B7%E5%A4%96?/PkQ=aq4
- 开放数据应用的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/787
- 农产品消费体验的长期维护要点 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/bun
- 城乡公共服务的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/HhO
- 乡村文化活动的服务体验观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/361=ile
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/vbq=242
- 数字支付体验的持续改进方向 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E5%85%AC%E5%91%8A_%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E5%BF%AB3%E6%98%AF%E6%80%8E%E4%B9%88%E9%AA%97%E7%9A%84_%E5%BF%85%E5%BA%94%E5%8D%83%E5%B8%86?/LJQ=Ev0
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/873
- 公共服务指南的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/ruc
- 青少年职业启蒙的家庭实践清单 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/Td1
- 家庭饮食安排的执行流程参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/550=yeh
- 城市便民驿站中的沟通与协作 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/ewj=397
- 图书借阅体验的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E5%BD%A9%E7%A5%A8%E6%9C%89%E4%BA%BA%E5%B8%A6%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/Emj=ngH
- 生成式工具使用的流程优化思路 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/132
- 青少年编程学习的行动步骤参考 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/nox
- 数字档案服务的公共参与指南 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/qxx
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/895=uti
- 社区花园共建中的几个关键细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/cmq=111
- 校园节能行动的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BD%91%E4%B8%8A%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%A5%97%E8%B7%AF_%E8%99%8E%E6%89%91%E6%95%B0%E8%AF%BB?/9Qf=zZR
- 公共空间休憩的日常记录与分享 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/634
- 城市公共厕所有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/axy
- 社区宠物管理的使用门槛与改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/U4u
- 科学健身方法的数字工具使用体验 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/344=hqw
- 骑行路线规划的活动组织技巧 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/lab=454
- 家庭养老规划从使用体验看服务改进 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E5%AF%BC%E5%B8%88%E8%AE%A1%E5%88%92%E9%AA%97%E5%B1%80_%E8%99%8E%E5%97%85%E8%B5%84%E8%AE%AF?/OQc=bGv
- 科学观察活动的参与方式与路径 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/682
- 数字设备回收的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/kfr
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/7Vq
- 课后服务体验的家庭参与方式 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/727=fnv
- 老年友好服务的社区参与观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/yko=331
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%9B%98%E7%82%B9%E8%A7%84%E5%88%92_%E5%BF%AB3-%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92-%E5%80%8D%E6%8A%95-%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E8%A1%8C%E6%83%85?/lAy=Z5K
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/889
- 城市微更新实践的服务质量观察 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/oym
- 急救知识普及的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/Qrt
- 社区商业活力的学习资源整理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/343=chx
- 校园社团活动的实际需求与回应 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/rvn=348
- 就业技能培训的绿色实践方法 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E5%BD%A9%E6%B0%91%E7%B2%BE%E9%80%89_%E8%AE%A1%E5%88%92%E7%BE%A4%E7%9C%9F%E7%9A%84%E5%8F%AF%E4%BB%A5%E8%B5%A2%E9%92%B1%E5%90%97_%E6%BE%8E%E6%B9%83%E5%AE%8F%E8%A7%82?/UIz=1Cl
- 开源技术交流的常见误区提醒 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/828
- 志愿服务平台的便民做法梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/xws
- 公共设施维护有哪些值得关注的细节 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/1In
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/763=uon
- 健康饮水科普从需求出发看服务设计 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/coh=603
- 小区停车协商的服务范围梳理 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E7%A7%92%E6%87%82%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F-%E5%8D%95%E5%8F%8C-%E7%BD%91%E7%BB%9C%E8%AF%88%E9%AA%97_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/TdD=hiK
- 校园安全教育的阅读与学习资源 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/027
- 老年人出行服务的安全使用提示 |来源：https://github.com/brownvanessa3/rdbo/wiki/2026%E6%99%AE%E5%8F%8A%E8%A7%82%E5%AF%9F_%E5%BF%AB35%E6%9C%9F%E5%BF%85%E4%B8%AD%E9%AA%97%E5%B1%80%E8%BF%87%E7%A8%8B_%E5%A4%B4%E6%9D%A1%E9%94%90%E8%AF%84?/udu

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
