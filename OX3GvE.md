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

- 公共空间安全的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/771
- 创业经验分享的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/iip
- 便民服务地图的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/qB8
- 地方民俗记录的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/659=iac
- 医院导诊服务有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/odp=625
- 城市文化路线的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E7%9F%A5%E4%B9%8E%E6%B3%95%E5%BE%8B?/vzs=t22
- 城市便民驿站有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/047
- 城市噪声观察的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/slk
- 基层医疗预约的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/hYe
- 开放式学习空间的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/025=lix
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/eol=820
- 城市共享单车的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E6%8E%A2%E8%AE%A8_QQ%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7?/tPE=cCY
- 智慧停车服务的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/246
- 社区体育组织的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/lgz
- 城市步行友好的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/tE2
- 青年职业探索的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/563=tlw
- 绿色建筑理念的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/sbq=734
- 传统节日科普从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E4%B8%AD%E5%8E%9F%E8%B4%A2%E7%BB%8F?/D6j=Q9R
- 传统节日科普的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/303
- 家庭饮食安排的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/xug
- 生活技能分享的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/Yy5
- 社区消防演练的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/115=zfx
- 读书会组织的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/yfz=334
- 社区便民服务的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_QQ%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E8%B4%A2%E6%8A%A5?/gXF=3ay
- 社区绿色空间的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/375
- 社区设施共享的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/vtt
- 市民热线服务的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/2Pt
- 城市水环境观察的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/232=ykm
- 生活服务数字化的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/glk=707
- 公园休闲体验的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_QQ%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E4%B8%AD%E8%81%94%E8%B4%A2%E7%BB%8F?/3wz=eD8
- 垃圾分类指导的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/858
- 跨代沟通活动的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/wub
- 家庭防灾准备的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/kXF
- 市民热线服务的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/827=wlm
- 社区手工活动的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/ydf=930
- 公共健身器材的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E8%99%8E%E6%89%91%E6%99%A8%E6%8A%A5?/FlB=Mxa
- 数字阅读服务的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/519
- 基层健康服务的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/ufx
- 老年智能设备的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/S2V
- 劳动教育实践的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/035=jxm
- 学校食育活动的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/ytt=977
- 公共空间休憩从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E8%AF%BB%E6%8A%A5?/rNU=c8o
- 社区公共餐饮的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/834
- 数字阅读服务的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/knv
- 药品使用科普的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/drl
- 家庭安全提示的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/158=ntl
- 城市住房服务的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/ecg=356
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E6%8E%A2%E8%AE%A8_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E7%BD%91%E6%98%93%E6%97%B6%E5%B0%9A?/Q7B=aqx
- 城市休闲步道的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/940
- 智能手机助老的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/uvq
- 街道综合服务的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/s2U
- 城市应急科普的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/173=fcr
- 城市文化路线的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/pao=706
- 志愿者培训交流的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%88%B1%E5%A5%87%E8%89%BA%E4%BF%A1%E8%B4%B7?/dwH=kI3
- 劳动教育实践的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/152
- 急救知识普及的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/nvo
- 数据分析入门中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/oZf
- 儿童阅读角的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/298=ada
- 城市共享单车的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/mqr=855
- 青年职业探索的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%9F%A5%E9%81%93_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%85%BE%E8%AE%AF%E6%85%A7%E7%9C%BC?/gWK=wdj
- 社区故事采集的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/138
- 数字创意课程的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/oqp
- 通勤路线规划的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/8us
- 开放式学习空间的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/544=dnq
- 青少年科普实践的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/yii=766
- 城市展览体验的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%AC%AC%E4%B8%80%E8%A7%A3%E8%AF%BB_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E5%9B%AD%E8%89%BA?/uSo=6Fc
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/949
- 城市运动公园的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/bos
- 城市公共厕所的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/olL
- 公共交通信息服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/896=iee
- 科普展览体验的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/qjx=802
- 食品安全科普的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E8%99%8E%E5%97%85%E6%8A%95%E7%A8%BF?/P8Q=XJ0
- 数据分析入门的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/334
- 家庭阅读计划的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/pgl
- 公园无障碍服务的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/XYk
- 公交站点体验的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/154=bvv
- 公共设施使用的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/vmo=975
- 社会体育指导的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E8%B4%A2%E7%BB%8F%E5%9B%BE%E9%89%B4?/sat=dd4
- 城市可持续生活的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/229
- 社区知识分享的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/ljd
- 城市文明出行的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/p34
- 青年志愿活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/263=any
- 社区故事采集的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/lks=735
- 城市宠物友好空间的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_u28%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/0wk=OAn
- 城市慢跑路线从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/009
- 城市树木认养的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/azc
- 健康步道使用中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/Phi
- 食品安全科普的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/995=qrc
- 健康饮水科普的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/psg=644
- 社区宣传栏更新的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_u28%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%93%9D%E7%AD%B9%E8%B4%A2%E7%BB%8F?/tM4=lzU
- 租房信息服务中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/722
- 数字学习资源的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/dza
- 社区协商议事的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/YIS
- 城市文明实践的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/443=ckq
- 市民热线服务的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/cbg=068
- 社区花园共建的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E5%AE%98%E6%96%B9%E8%81%9A%E7%84%A6_u28%E5%BD%A9%E7%A5%A8-APP_%E6%BE%8E%E6%B9%83%E8%A7%A3%E5%AF%86?/wAH=rBG
- 乡村公共文化中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/393
- 医院导诊服务的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/izf
- 城市建设科普的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/8Sy
- 文化场馆预约的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/059=drl
- 市民意见收集的常见问题梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/wcl=083
- 乡村公共阅读的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%8C%87%E5%AF%BC_u28%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%86%E9%A2%91?/jOx=upd
- 老年人出行服务的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/906
- 远程协作工具的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/pil
- 农产品消费体验的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/gri
- 居家适老化改造的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/146=lmd
- 家庭节能实践的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/qid=552
- 城市文化路线的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E6%96%87%E5%BA%93?/1Lf=Zsb
- 数字便民地图的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/814
- 社区垃圾回收的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/pzn
- 传统手工艺体验的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/YKj
- 城市生活记录的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/740=ril
- 公园无障碍服务从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/taq=649
- 本地历史资料的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%A1%A3%E6%A1%88?/RLh=0TH
- 健康信息获取的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/525
- 乡村产业科普的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/quo
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/TE6
- 老年智能设备的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/775=toi
- 社区便民集市的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/ceu=559
- 城市应急科普的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%AE%A8%E8%AE%BA_u28%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%B3%95%E5%BE%8B?/OAJ=k6P
- 青年就业服务的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/874
- 开放数据应用的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/ndr
- 周末休闲规划的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/idV
- 城市博物馆服务的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/842=qhk
- 社区信息发布的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/lep=861
- 社区消防演练的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_u28%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%96%B0%E6%B5%AA%E9%9F%B3%E4%B9%90?/4Lx=RB6
- 家庭防灾准备的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/131
- 校园节能行动的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/bsy
- 传统手工艺体验的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/slZ
- 远程协作工具的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/483=bnr
- 传统手工艺体验的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/rwn=186
- 线上阅读资源的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_u28%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/cZr=782
- 城市地名文化的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/169
- 社区安全巡查的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/kmv
- 青少年科普实践的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/qFZ
- 文化遗产保护科普的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/922=ada
- 非遗课堂体验的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/gab=648
- 公园亲子设施的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_u28%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E5%8D%97%E7%BE%8E%E8%B4%A2%E7%BB%8F?/CPj=WLy
- 节气饮食文化的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/408
- 老年人日常照护的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/lcy
- 城市公共空间的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/NLN
- 便民维修服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/579=djl
- 数字创作工具的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/ykr=910
- 乡村公共阅读中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_u28%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%8D%B3%E5%88%BB%E4%B8%93%E9%A2%98?/89q=zLz
- 社区生活指南的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/976
- 老年智能设备的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/xrn
- 环境监测科普的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/iYr
- 邻里互助活动的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/928=ybe
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/lfr=055
- 生活垃圾减量的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_u28%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E6%88%BF%E4%BA%A7%E8%B4%A2%E7%BB%8F?/h5w=8CO
- 居民健康教育的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/940
- 食品配送体验的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/qqh
- 社区体育组织的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/fhy
- 青少年户外教育的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/827=dnx
- 图书馆活动策划的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/teu=189
- 节日文化体验有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_u28%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E5%A4%B4%E6%9D%A1%E7%9B%98%E7%82%B9?/v43=2bo
- 光伏知识科普的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/032
- 小区停车协商的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/jth
- 生活技能分享的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/PBn
- 社区科普课堂有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/156=pqq
- 城市骑行环境的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/szc=800
- 线上阅读资源的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%B5%84%E6%BA%90_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E5%BE%97%E7%89%A9%E6%B1%BD%E8%BD%A6?/ZkA=hkK
- 家庭健康科普的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/914
- 社区休闲设施的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/dco
- 食品配送体验的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/Jqm
- 家庭饮食安排的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/365=tub
- 机器学习入门的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/zad=073
- 家庭教育交流的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%92%AD%E6%8A%A5?/om6=ejQ
- 家庭用电安全从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/500
- 公共设施使用从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/uut
- 邻里共享空间的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/al1
- 基层健康服务的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/953=cxy
- 社区安全巡查的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/ijw=665
- 公共服务预约的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E4%B8%9D%E8%B7%AF%E8%B4%A2%E7%BB%8F?/U6E=yqc
- 家庭园艺实践的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/517
- 本地旅行体验的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/krp
- 城市文明实践的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/kpw
- 青少年科普实践中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/031=cga
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/jeo=091
- 学校体育活动的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E7%89%A9%E6%B5%81%E8%B4%A2%E7%BB%8F?/8G9=J3b
- 公共服务沟通的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/899
- 社区活动空间的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/gjg
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/nVn
- 户外活动组织的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/800=tsw
- 城市文明出行的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/hiw=837
- 节日文化体验的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome_%E8%99%8E%E5%97%85%E5%AE%8F%E8%A7%82?/gWo=ykB
- 乡村教育资源有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/494
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/pnp
- 社区花园共建的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/uu2
- 传统手工艺体验的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/888=fsk
- 传统节日科普的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/ehk=106
- 老年人日常照护的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E5%A4%A9%E8%AA%89%E8%B4%A2%E7%BB%8F?/Scc=vEd
- 个人时间管理的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/861
- 通勤路线规划中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/ous
- 数字便民地图的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/VY6
- 社区手工活动的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/466=kgu
- 生活垃圾减量的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/ica=980
- 信息无障碍体验的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E6%90%9C%E7%8B%90%E5%9B%9E%E6%94%BE?/mq2=9GF
- 数字便民地图的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/863
- 街区小店体验的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/xcd
- 就业技能培训的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/8O7
- 地方旅游导览的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/204=wyp
- 网络信息辨识的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/guv=761
- 智能手机助老的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_U7%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E5%A4%B4%E6%9D%A1%E6%94%BF%E7%AD%96?/jWb=bYG
- 乡村电商实践的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/272
- 城市骑行环境的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/wbf
- 数字设备回收的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/K8s
- 公共场馆服务的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/646=isy
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/kza=677
- 科学健身方法的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_U7%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E5%87%A4%E5%87%B0%E5%91%A8%E6%8A%A5?/NFl=8tx
- 社区活动空间的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/786
- 便民维修服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/aos
- 小区公共照明的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/pzO
- 社区知识分享的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/387=fbd
- 校园安全教育的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/hcf=252
- 乡村公共服务的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_U7%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E9%A1%BA%E4%B8%B0%E8%B4%A2%E7%BB%8F?/NXY=fij
- 生成式工具使用的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/500
- 社区家校合作的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/xtw
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/gPg
- 社区信息发布的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/895=ght
- 远程协作工具的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/gkt=582
- 校园安全教育的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_U7%E5%BD%A9%E7%A5%A8-APP_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%81%A5%E5%BA%B7?/Y0O=mld
- 家庭运动计划的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/698
- 社区活动报名的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/slk
- 节日文化体验的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/7dx
- 家庭急救准备的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/117=pfe
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/thz=706
- 城市游园体验的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_U7%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F?/rYl=Dg6
- 电子商务服务的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/782
- 人工智能科普的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/owm
- 城市公共饮水的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/iUJ
- 文明养宠科普的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/985=jtf
- 农贸市场环境的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/vrw=225
- 城市夜间生活的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%84%E5%88%92_U7%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%BF%9C%E6%B4%8B%E8%B4%A2%E7%BB%8F?/5tP=mhZ
- 家庭网络使用的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/620
- 低碳社区实践的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/xrj
- 便民维修服务的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/3EZ
- 社区托育服务的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/925=ugn
- 社区安全巡查的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/uri=824
- 城市应急广播的儿童友好细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_U7%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E6%96%B0%E6%B5%AA%E8%A7%82%E7%82%B9?/a5e=BSV
- 无障碍出行的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/757
- 居家防滑改造的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/bvo
- 城市体育设施的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/ge0
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/680=vbv
- 基层医疗预约的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/suc=155
- 社区交通安全的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%8E%8B%E7%89%8C_U7%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E7%88%B1%E5%A5%87%E8%89%BA%E6%8A%95%E7%A5%A8?/ahi=b55
- 非遗体验活动的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/602
- 居家防滑改造的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/zqy
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/pB2
- 社区故事采集的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93_U7%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%96%B0%E9%97%BB?/302=uom

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
