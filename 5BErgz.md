# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:21**

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

- 文化讲座服务的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/792
- 家庭教育交流的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/mzw
- 城市共享单车的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/Ikp
- 乡村电商实践的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/736=vrs
- 低碳社区实践有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/njl=011
- 乡村公共服务的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/5fN=zEC
- 校园社团活动的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/747
- 农业科普体验的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/cuu
- 青年就业服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/50J
- 机器人科普活动有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/520=fex
- 城市慢行系统的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/vgc=346
- 家庭节能设备的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9app_%E4%BA%AC%E4%B8%9C?/4q9=goM
- 数字素养提升的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/635
- 安全出行教育的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/xpg
- 数字生活课堂的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/ETe
- 健康信息获取的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/286=qjz
- 便民维修服务的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/tva=914
- 绿色快递包装的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E7%BD%91_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%97%85%E6%B8%B8?/Cdq=kIV
- 乡村电商实践的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/278
- 智慧城市体验的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/ubg
- 绿色校园实践的组织方法与经验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/CYy
- 社区宣传栏更新的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/096=vhj
- 居家防滑改造的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/qlv=904
- 社区交通安全的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B6%8A%E5%8D%97%E8%B4%A2%E7%BB%8F?/AMy=Aw9
- 绿色生活实践的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/197
- 小区停车协商的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/mvx
- 医院导诊服务的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/7gR
- 社区设施共享的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/561=rcq
- 本地历史资料的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/stx=675
- 老年人文化生活的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E9%A2%91%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E7%BB%8F%E6%B5%8E?/drV=e0z
- 城市共享单车的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/648
- 社区消防演练的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/ldn
- 城乡交流活动的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/n2p
- 公共服务评价的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/109=nhk
- 地方文化传播的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/pfv=866
- 社区共享书架的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E8%AF%86_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP_%E7%99%BE%E5%BA%A6%E4%BF%A1%E8%B4%B7?/6rv=RcR
- 全民健身活动的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/566
- 社区消防演练的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/sxl
- 社区教育资源的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/wiu
- 乡村产业科普的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/972=oag
- 乡村文化空间的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/hpx=288
- 节能家电使用的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E8%B0%B7%E6%AD%8C%E5%86%9C%E4%B8%9A?/Gwr=PGH
- 家庭收纳实践的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/793
- 社区手工活动中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/nzh
- 儿童阅读角的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/BYq
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/856=zif
- 街道综合服务的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/uoq=157
- 社区垃圾分类的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%95%8C%E9%9D%A2%E5%88%8A%E7%99%BB?/gYY=67z
- 乡村教育资源的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/590
- 家庭用电安全从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/dtb
- 公共服务指南的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/T1x
- 环境教育课程有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/747=rrt
- 公共场馆服务的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/xkp=935
- 城市应急广播的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/Va8=QFB
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/721
- 城市慢行系统的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/wkj
- 农贸市场环境的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/5Te
- 家庭科学教育中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/071=wzp
- 老年人文化生活的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/klo=457
- 数字公共文化的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E8%A7%86%E9%A2%91?/e4P=i2s
- 居家适老化改造的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/089
- 健康步道使用的绿色实践方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/rqx
- 骑行路线规划的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/hhB
- 城市公共空间的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/758=ypi
- 老年友好服务的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/slc=448
- 创业经验分享的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E6%90%9C%E7%8B%90%E5%8E%BF%E5%9F%9F?/igD=R74
- 市民热线服务的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/805
- 乡村电商实践的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/cbx
- 生活服务数字化的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/nfk
- 公共设施使用的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/088=rcs
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/msv=307
- 社区休闲设施的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E5%BF%85%E5%BA%94%E4%BD%93%E8%82%B2?/GAF=SVT
- 租房信息服务的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/130
- 社区共享书架的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/qlu
- 社区公共议事的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/Yjg
- 创业经验分享的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/579=llf
- 电子商务服务的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/drq=271
- 社区共享书架的数字工具使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E4%B9%A6%E7%94%BB?/su2=mVI
- 城市便民驿站的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/732
- 城市休闲步道的空间设计要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/gmt
- 旧物循环利用的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/epH
- 家庭园艺实践有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/422=gkn
- 校园节能行动的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/wjw=037
- 创业经验分享的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E8%99%8E%E5%97%85%E7%95%85%E6%B8%B8?/tvH=KsZ
- 健康步道使用中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/072
- 城市噪声观察的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/hvc
- 劳动教育实践的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/1HN
- 社区便利生活的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/723=vkz
- 城市展览体验的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/iyt=482
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%BF%AA%E6%8B%9C%E8%B4%A2%E7%BB%8F?/eK4=pF7
- 节能家电使用的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/058
- 科学观察活动的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/hui
- 家庭食品保存从使用体验看服务改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/wtt
- 城市适老服务的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/247=wcs
- 环境监测科普的活动策划思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/mir=150
- 基层服务创新的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%9B%98%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E6%81%92%E5%BD%A9%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9_%E7%99%BE%E5%BA%A6%E6%8A%95%E8%B5%84?/e1K=dqv
- 环境教育课程的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/547
- 科学健身方法的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/roc
- 科学观察活动的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/ldy
- 基层健康档案的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/380=lza
- 个人时间管理的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/lhd=990
- 科学教育活动的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%8E%8B%E7%89%8C_%E7%BA%A2%E5%BD%A9-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%93%94%E5%93%A9%E6%85%A7%E7%9C%BC?/fCT=87x
- 社区修缮行动的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/940
- 信息无障碍体验的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/qjt
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/LHB
- 口袋公园建设中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/597=qyg
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/jyg=080
- 城市夜间生活的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E4%BA%86%E8%A7%A3_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85_%E8%85%BE%E8%AE%AF%E7%A4%BE%E5%8C%BA?/Y4v=Gjq
- 智慧城市体验的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/322
- 街头绿植养护的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/zry
- 乡村阅读活动的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/nZ6
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/293=kuq
- 乡村阅读空间的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/nze=907
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85%E6%9C%8D%E9%A5%B0?/7es=0QQ
- 非遗体验活动的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/951
- 图书馆数字服务的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/gza
- 文明养宠科普的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/Li0
- 城市社区治理的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/201=vuj
- 家庭节能设备的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/rtz=317
- 社区学习活动的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E5%8D%8E%E5%B0%94%E8%B4%A2%E7%BB%8F?/pYx=mhp
- 乡村生态观察的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/917
- 数字资源检索中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/wgc
- 便民维修服务的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/oDx
- 地方戏曲体验的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/459=luv
- 城市地名文化的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/tco=620
- 数字学习资源的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E7%89%B9%E7%A8%BF?/Chi=J43
- 药品使用科普的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/506
- 家庭网络使用的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/jtl
- 居家防滑改造的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/q3J
- 老年人出行服务的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/562=lll
- 绿色快递包装的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/gub=943
- 传统节日科普的居民参与机会 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%A0%B8%E5%BF%83%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95welcome_360%E6%94%B6%E8%97%8F?/2EM=m2G
- 社区知识分享的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/247
- 老年人日常照护的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/xje
- 课后服务体验的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/xq4
- 数字生活课堂的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/655=vso
- 光伏知识科普的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/szx=102
- 城市文明出行的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%8E%A2%E5%BA%97?/DiY=LPF
- 城市应急广播的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/732
- 公共空间照明的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/ljc
- 社会体育指导的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/GUz
- 社区停车服务的协作机制梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/628=tco
- 个人时间管理的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/uet=425
- 开源技术交流的服务质量观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9app_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/qrE=kht
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/838
- 医院导诊服务的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/rfh
- 青年志愿活动的活动体验回顾 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/WJ3
- 社区宠物管理的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/533=hfj
- 数字设备回收的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/gue=350
- 社区互助网络的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E7%BD%91_%E4%BA%AC%E4%B8%9C%E6%8E%A2%E6%BA%90?/7Rm=bSA
- 城市运动公园的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/203
- 食品配送体验的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/oyn
- 城市慢行系统的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/095
- 科学运动指导的服务反馈渠道 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/680=zpe
- 家庭志愿活动的社区参与观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/kgx=241
- 邻里共享空间的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E7%BA%A2%E5%BD%A9-%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E8%83%BD%E6%BA%90?/1PT=C2O
- 街区小店体验的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/778
- 终身学习资源的实际需求与回应 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/pec
- 城市微更新实践的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/ikA
- 乡村公共服务的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/110=gop
- 数字创意课程的便民做法梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/duz=685
- 家庭健康管理的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E7%BA%A2%E5%BD%A9-%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E5%8F%B8%E6%B3%95?/bzX=z2a
- 公共交通接驳的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/016
- 消防知识宣传的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/adr
- 社区活动空间的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/7l4
- 公共服务预约的便利性观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/776=jli
- 全民阅读推广的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/kvx=493
- 乡村阅读活动的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%84%E6%B5%8B_%E7%BA%A2%E5%BD%A9-APP_%E8%99%8E%E5%97%85%E8%AF%BB%E6%8A%A5?/C7z=rJP
- 公园亲子设施的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/033
- 软件开发学习的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/ofn
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/bLW
- 城市环境志愿行动的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/494=pei
- 食品配送体验中的沟通与协作 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/pwu=891
- 乡村教育资源的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E7%BA%A2%E5%BD%A9-welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5_%E5%93%94%E5%93%A9%E5%BD%A9%E7%A5%A8?/GkU=mmd
- 数字公共文化的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/334
- 城市休闲步道的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/fes
- 社区教育资源的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/wo7
- 家庭安全提示的常见误区提醒 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/362=wxx
- 骑行路线规划的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/yqp=572
- 城市运动公园的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E5%8A%A8%E6%80%81_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E7%9F%A5%E4%B9%8E%E6%8A%95%E7%A5%A8?/uoG=UoR
- 家庭教育交流的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/582
- 绿色生活实践的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/rvr
- 城市人文观察的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/cyM
- 日常摄影记录的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/222=qle
- 软件开发学习的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/rfe=697
- 城市环境志愿行动的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%91%E6%99%AE%E8%A7%A3%E8%AF%BB_%E7%BA%A2%E5%BD%A9-%E7%99%BB%E5%BD%95_%E6%8A%96%E9%9F%B3%E5%8C%BB%E8%8D%AF?/7uv=K85
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/609
- 城市水环境观察的家庭实践清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/oim
- 社区庭院绿化的使用门槛与改进 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/5TD
- 通勤路线规划的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/622=wmh
- 环境教育课程的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/vyd=929
- 公共设施维护的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%99%AE%E5%8F%8A%E6%94%BB%E7%95%A5_%E7%BA%A2%E5%BD%A9-%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%9B%BE%E9%9B%86?/aPu=Gda
- 科学睡眠习惯的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/447
- 家庭运动计划的公共参与指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/myp
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/P0T
- 科学健身方法有哪些值得关注的细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/233=iuh
- 绿色生活实践的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/gjd=846
- 家庭节能实践的资源利用方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%91%E6%99%AE%E6%8E%A2%E8%AE%A8_%E7%BA%A2%E5%BD%A9-%E6%AD%A3%E8%A7%84%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83_%E8%B4%A2%E7%BB%8F%E5%A4%A9%E4%B8%8B?/Kj3=cWV
- 城市公共饮水的便捷程度观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/124
- 乡村产业科普的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/gjc
- 图书馆活动策划的日常管理方法 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/6Sf
- 本地消费场景的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/830=zkl
- 社区快递服务的阅读与学习资源 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/kjo=649
- 城市步行环境的日常记录与分享 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E5%AE%89%E5%85%A8%E8%B4%AD%E5%BD%A9_%E9%9B%85%E8%99%8E%E6%B1%BD%E8%BD%A6?/wdq=M1I
- 数字学习资源的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/293
- 智能手机助老的流程优化思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/tsm
- 便民服务窗口的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/ul6
- 文明养宠科普的协商参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/013=hur
- 公园亲子设施的基础设施观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/tqs=842
- 街区更新实践的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E7%BA%A2%E5%BD%A9-%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_360%E4%B8%93%E6%A0%8F?/XQI=nMI
- 数字地图应用的行动步骤参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/416
- 社区环保活动的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/zjj
- 新能源知识普及的入门知识整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/ooQ
- 校园社团活动的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/187=zyd
- 环境教育课程从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/bhr=078
- 垃圾分类指导的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E9%87%8D%E5%A4%A7%E6%8E%A8%E8%8D%90_%E7%BA%A2%E5%BD%A9-APP%E7%9A%84%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%A6%9C%E5%8D%95?/F8H=Ffm
- 数字政务体验的服务体验观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/163
- 家庭用电安全的空间使用体验 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/jvb
- 公共场所导视的资源整合思路 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/COY
- 乡村阅读空间的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/970=xub
- 老年友好服务中的几个关键细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/jbc=576
- 科学健身方法的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E7%BA%A2%E5%BD%A9-%E9%A6%96%E9%A1%B5_%E7%99%BE%E5%BA%A6%E8%A7%82%E7%82%B9?/qRC=lXn
- 青年职业探索的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/035
- 地方戏曲体验的持续改进方向 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/cfp
- 社区交通安全的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/BKg
- 安全出行教育的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/350=ptp
- 社区学习活动的服务细节记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/fiq=027
- 社区共享书架的公共信息获取方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E4%BB%8A%E6%97%A5%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E7%BA%A2%E5%BD%A9-%E5%AE%98%E6%96%B9_%E6%BE%8E%E6%B9%83%E6%A1%A3%E6%A1%88?/cgJ=eMt
- 气象科普传播的线下体验记录 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/542
- 绿色生活实践的参与方式与路径 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/hue
- 全民健身活动的日常使用指南 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/1br
- 社区宠物管理的数字化应用观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/575=ztp
- 数字档案服务的服务范围梳理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/uyz=680
- 读书会组织的设施维护观察 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-welcome%E5%A4%A7%E5%8E%85_%E6%96%B0%E6%B5%AA%E5%8A%A8%E6%BC%AB?/rsf=wI2
- 家庭园艺实践的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/037
- 老年人出行服务的服务信息整理 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/tbx
- 社区绿色空间的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/TQl
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/467=kmp
- 青少年科普实践的长期维护要点 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/fau=957
- 家庭环保习惯的线上线下服务衔接 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2027%E7%A7%92%E6%87%82%E8%81%9A%E7%84%A6_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_360%E6%A5%BC%E5%B8%82?/PGE=4g4
- 市民热线服务的执行流程参考 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/581
- 家庭急救准备的社区行动案例 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/vmg
- 城市便民驿站的基础知识问答 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/HOh
- 开放数据应用的安全使用提示 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/944=jwj
- 城乡公共服务的实用信息清单 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/tse=078
- 社区学习活动的家庭参与方式 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E6%8E%A2%E8%AE%A8_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E5%AE%98%E6%96%B9%E5%85%A5%E5%8F%A3_%E9%9B%85%E8%99%8E%E9%97%AE%E5%8D%B7?/iCr=5vA
- 全民阅读推广的适老服务细节 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/316
- 老旧小区改造的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/cpy
- 社区快递服务的日常实践笔记 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/gj2
- 公共服务沟通从需求出发看服务设计 |来源：https://github.com/blanchardmatthew7/cdmz/wiki/2026%E7%A7%92%E6%87%82%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AE%8F%E6%96%B0%E5%BD%A9%E7%A5%A8-%E7%99%BB%E5%BD%95welcome%E9%A6%96%E9%A1%B5_%E6%90%9C%E7%8B%97%E5%91%A8%E6%8A%A5?/925=mwy

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
