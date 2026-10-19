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

- 城市慢跑路线的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/rai=395
- 社区家校合作的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%AE%80%E6%8A%A5_%E6%BB%A1%E5%BD%A9%E5%A0%82-%E9%A6%96%E9%A1%B5_%E5%BF%AB%E6%89%8B%E7%A4%BE%E8%AE%BA?/iWZ=UrF
- 地方戏曲体验的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/788
- 安全出行教育的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/bfc
- 线上阅读资源的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/mDw
- 社区快递服务的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/636=umv
- 城市微更新实践的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/wiz=336
- 便民信息查询的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%99%AE%E5%8F%8A%E6%80%BB%E7%BB%93_%E6%BB%A1%E5%BD%A9%E5%A0%82%E8%B5%9A%E9%92%B1%E6%98%AF%E6%80%8E%E4%B9%88%E5%9B%9E%E4%BA%8B_%E9%A1%BA%E4%B8%B0%E4%B9%A6%E7%94%BB?/tnZ=aVj
- 城市噪声观察的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/121
- 家庭陪伴活动的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/ijf
- 科技馆参观体验的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/edF
- 家庭养老规划的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/587=sab
- 社区生活指南的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/nrw=453
- 城市文化路线的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%99%BE%E7%A7%91_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E5%A4%B4%E6%9D%A1%E8%AE%B2%E5%9D%9B?/VXT=0Y1
- 城市公共标识的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/007
- 公园亲子设施的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/hpx
- 读书会组织的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/45v
- 运动安全知识的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/243=gyl
- 社区读书角建设的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/mpi=897
- 社区教育资源的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E5%90%8D%E8%B4%AF%E5%BF%AB3_%E6%BE%8E%E6%B9%83%E5%8A%A8%E6%BC%AB?/1FU=4RN
- 节日文化体验的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/054
- 街区更新实践的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/wqv
- 乡村生态观察的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/FkZ
- 在线教育体验的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/377=taf
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/dcj=653
- 数字生活课堂的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_%E8%85%BE%E8%AE%AF%E6%94%B6%E8%97%8F?/RAH=VYj
- 药品使用科普的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/871
- 网络信息辨识的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/fae
- 家庭食品保存的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/ZYb
- 社区花园共建的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/492=oem
- 生成式工具使用的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/poo=100
- 数字政务体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A2%E8%AE%A8_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9%E7%BD%91%E7%AB%99_%E5%87%A4%E5%87%B0%E6%95%B0%E8%AF%BB?/2Kp=p3b
- 城市可持续生活的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/305
- 开源技术交流的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/all
- 社区体育组织中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/PRL
- 个人数据管理的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/259=kty
- 科学观察活动的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/ptu=324
- 城市绿道建设的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E4%B8%93%E8%AE%BF_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E9%9B%85%E8%99%8E%E7%83%AD%E6%A6%9C?/QKR=qcM
- 青少年户外教育的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/889
- 城市博物馆活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/yoy
- 软件开发学习的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/zIv
- 社区艺术活动的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/708=hff
- 城市公共艺术的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/swd=084
- 家庭阅读计划的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_%E5%90%8D%E8%B4%AF%E5%BD%A9%E7%A5%A8%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E7%95%8C%E9%9D%A2%E6%8A%95%E7%A8%BF?/lAs=gXU
- 公共服务数字化的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/442
- 乡村休闲旅游的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/euh
- 绿色快递包装的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/MFi
- 智能手机助老的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/081=uhf
- 全民阅读推广的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/hbh=659
- 家庭食品保存的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80%5B_%E5%A4%B4%E6%9D%A1%E9%97%AE%E5%8D%B7?/AT5=8lz
- 数字艺术创作的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/378
- 本地消费场景的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/ncf
- 图书借阅体验的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/8Fz
- 户外活动组织的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/032=mry
- 家庭阅读计划的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/pnm=299
- 城市可持续生活的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%90%8D%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%9D%80_%E7%99%BE%E5%BA%A6%E7%95%85%E6%B8%B8?/thT=fQ4
- 数字设备回收的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/494
- 青少年编程学习的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/uoy
- 电动汽车充电的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/SCz
- 社区协商议事的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/064=nyw
- 青年志愿活动的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/ito=676
- 青少年心理健康的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E5%90%8D%E7%99%BC%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%B4%A2%E7%BB%8F%E8%A7%82%E5%AF%9F%E5%AE%A4?/zFC=fVy
- 科学运动指导的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/566
- 垃圾分类指导的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/eyc
- 乡村阅读活动的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/FE4
- 地方美食文化的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/785=kfg
- 乡村公共服务的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/msk=974
- 城市环境志愿行动从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E7%99%BE%E7%A7%91_%E7%89%9B%E7%89%9B%E7%BD%91%E7%AB%99%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%94%BF%E5%8D%8F?/1jX=EKD
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/046
- 邻里共享空间的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/gsa
- 老年智能设备的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/DLF
- 城市基础设施的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/364=pbt
- 医院导诊服务的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/zse=166
- 个人信息保护的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app_%E8%8A%92%E6%9E%9C%E6%B3%95%E6%B2%BB?/o4G=oBR
- 社区协商议事的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/077
- 家庭饮食安排的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/gdo
- 家庭节能设备的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/baa
- 租房信息服务的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/461=tsg
- 本地消费场景的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/lzt=608
- 亲子阅读活动的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%80%8E%E4%B9%88%E6%A0%B7_%E5%A4%B4%E6%9D%A1%E6%95%B0%E8%AF%BB?/XEg=7Lt
- 社区活动空间的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/770
- 文明养宠科普的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/uxp
- 公交站点体验的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/QhP
- 社区宣传栏更新从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/114=kkf
- 小微企业服务的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/pei=451
- 家庭志愿活动有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E7%89%9B%E7%89%9B%E7%BD%91_%E8%B1%86%E7%93%A3%E8%81%8C%E5%9C%BA?/04M=ki5
- 城市骑行环境的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/219
- 城市噪声观察的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/lqd
- 智慧停车服务的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/VCa
- 周末休闲规划的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/733=tnk
- 节气饮食文化的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/ygw=984
- 市民热线服务的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%5B_%E5%BF%85%E5%BA%94%E4%BA%BA%E5%A4%A7?/oo2=FzD
- 课后服务体验的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/240
- 绿色出行服务的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/ohx
- 急救知识普及从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/Iah
- 社区共享书架的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/392=her
- 城市宠物友好空间的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/hds=018
- 医院导诊服务的绿色实践方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83_%E7%89%9B%E7%89%9B%E7%BD%91%E5%BD%A9%E7%A5%A8%E7%A6%8F%E5%BD%A9%E9%A2%84%E6%B5%8B_%E8%B4%A2%E7%BB%8F%E8%BE%9F%E8%B0%A3?/56U=3Vj
- 亲子科普活动的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/145
- 城市共享单车的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/zxk
- 乡村休闲旅游的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/GDw
- 社区健康讲座的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/348=cue
- 低碳社区实践的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/sja=098
- 家庭环保习惯的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E7%89%9B%E7%89%9B%E7%BD%91%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E5%BD%B1%E8%A7%86?/vBv=oIb
- 城市公共空间的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/057
- 传统节日科普的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/zig
- 基层健康服务的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/eUS
- 传统手工艺体验有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/770=xhu
- 运动安全知识的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/mlq=848
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%A3%E8%AF%BB_%E8%B6%A3%E8%B4%AD%E5%BD%A9APP%E6%96%B0%E7%89%88%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E6%B3%95%E6%B2%BB?/6OK=fNW
- 乡村公共阅读的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/469
- 骑行路线规划的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/gfa
- 城市慢行系统的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/Q09
- 老年人日常照护的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/945=yio
- 社区教育资源的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/dhw=585
- 社区慢性病防控的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E8%A7%82%E5%AF%9F_%E8%B6%A3%E8%B4%AD%E5%BD%A9-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E8%83%BD%E6%BA%90?/ARk=Lrv
- 环境教育课程的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/980
- 数字课堂应用的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/vbr
- 职业技能学习的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/OQL
- 社区共享书架的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/391=dnp
- 社区文化传播的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/bpm=066
- 乡村生活观察的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E9%A3%8E%E5%90%91_%E8%B6%A3%E8%B4%AD%E5%BD%A9app%E7%BD%91%E9%A1%B5%E7%89%88_%E8%B1%86%E7%93%A3%E6%AF%8D%E5%A9%B4?/7pC=IMI
- 社区信息发布中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/056
- 生成式工具使用的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/xln
- 城市博物馆活动的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/Bym
- 城市运动公园的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/742=uog
- 城市雨天出行中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/nfd=403
- 社区读书角建设中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%8F%91%E7%8E%B0_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9_%E9%87%91%E8%9E%8D%E8%B4%A2%E7%BB%8F?/5g8=OWh
- 零废弃生活尝试的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/946
- 城市树木认养的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/jwa
- 公共空间照明的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/6Zw
- 社区公共餐饮的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/113=fql
- 节假日出行安排的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/psq=573
- 社区体育组织的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E7%9C%8B%E7%82%B9_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%BF%AB%E4%B8%89_%E4%B8%AD%E7%9B%88%E8%B4%A2%E7%BB%8F?/KHb=fxI
- 个人数据管理的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/237
- 公共设施使用的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/sit
- 城市共享单车的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/vqg
- 电动汽车充电的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/892=ixy
- 药品使用科普的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/zrd=066
- 青少年科普实践的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%91%E6%99%AE%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%8A%95%E6%B3%A8%E7%99%BB%E5%BD%95%E9%A6%96%E9%A1%B5_%E4%BC%98%E5%93%81%E8%B4%A2%E7%BB%8F?/WMS=YmZ
- 公共服务指南的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/173
- 城市住房服务的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/oom
- 城市微更新实践中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/H1e
- 城市人文观察的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/145=jhi
- 社区停车服务的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/glv=783
- 绿色消费选择中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%89%E5%8D%93%E7%89%88_%E5%8D%8E%E5%95%86%E8%B4%A2%E7%BB%8F?/eGE=4Vj
- 社区养老服务的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/968
- 城乡交流活动的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/eib
- 公交无障碍服务的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/sIt
- 家庭志愿活动的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/252=fqu
- 食品配送体验的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/tml=253
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E8%B6%A3%E8%B4%AD%E5%BD%A9-welcome%E9%A6%96%E9%A1%B5_%E5%A4%AE%E8%A7%86%E5%8C%BB%E8%8D%AF?/aIu=8R3
- 社区手工活动的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/005
- 读书会组织的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/fii
- 青少年户外教育中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/b9I
- 数字政务体验中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/571=upy
- 社区教育资源的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/dlt=769
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E8%B6%A3%E8%B4%AD%E5%BD%A9%28%E7%BD%91%E9%A1%B5%E7%89%88%29_%E6%90%9C%E7%8B%97%E8%A6%81%E9%97%BB?/f0l=qgv
- 创业经验分享的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/180
- 老年学习活动的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/lfw
- 城乡公共服务的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/EwR
- 社区宠物管理的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/357=end
- 软件开发学习的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/ijw=105
- 家庭用电安全的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95_%E5%93%94%E5%93%A9%E4%BF%A1%E6%89%98?/vHC=wjc
- 家庭用电安全的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/993
- 家庭食品保存的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/tko
- 亲子科普活动的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/0gX
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/781=utc
- 智慧城市体验的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/yiv=075
- 农产品消费体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E6%89%8B%E5%86%8C_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E5%AE%98%E6%96%B9%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E4%BA%91%E6%B5%B7%E8%B4%A2%E7%BB%8F?/1IB=Lcs
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/849
- 气象科普传播的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/grx
- 城市地名文化从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/pdf
- 公共卫生宣传的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/446=hvz
- 科技馆参观体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/npg=839
- 城市农夫市集的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E6%89%8B%E6%9C%BA%E7%BD%91%E9%A1%B5%E7%89%88%E7%9B%B4%E6%8E%A5%E7%99%BB%E5%BD%95_%E5%BF%AB%E6%89%8B%E5%A4%B4%E6%9D%A1?/qTs=bwF
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/131
- 儿童安全出行中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/tcc
- 社区消防演练的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/3O1
- 药品使用科普的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/721=kyo
- 志愿服务平台的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/osv=113
- 城市展览体验的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%8D%97_%E8%B6%A3%E8%B4%AD%E5%BD%A9%E7%99%BB%E5%BD%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/48y=n3Q
- 科技馆参观体验的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/079
- 城市微更新实践的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/shj
- 周末休闲规划的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/IXc
- 城市人文观察的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/411=maz
- 非遗课堂体验的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/dxw=902
- 数字公共文化的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%88%86%E6%96%99_%E8%80%81%E7%89%88%E5%85%A8%E6%B0%91%E5%BD%A9%E7%A5%A8_%E5%93%94%E5%93%A9%E6%97%B6%E6%8A%A5?/VZ3=PfY
- 公共卫生宣传的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/292
- 数字支付体验的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/nry
- 社区商业活力的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/IPj
- 社区文化传播的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/705=ivy
- 青少年科普实践的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/tls=708
- 非遗体验活动的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_767%E6%97%A7%E5%BD%A9%E5%BD%A9%E7%A5%A89767._%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%9A%E4%BF%A1?/8TB=rxK
- 城市公共标识的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/652
- 基层健康档案的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/ugk
- 公共服务咨询的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/i31
- 城乡公共服务的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/171=nac
- 公共服务沟通的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/beh=860
- 城市噪声观察的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3-_%E6%96%B0%E6%B5%AA%E5%8E%BF%E5%9F%9F?/5yQ=Qfy
- 老年学习活动从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/701
- 儿童户外活动的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/fei
- 公共健身器材的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/hp2
- 社区托育服务的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/293=dor
- 小微企业服务的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/tbb=536
- 科技馆参观体验的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E9%A1%BA%E4%B8%B0%E6%96%87%E5%8C%96?/4DU=c1b
- 亲子科普活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/981
- 公交站点体验的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/ciy
- 儿童安全出行的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/Kdt
- 数字课堂应用的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/688=lgz
- 志愿者培训交流的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/qis=694
- 社区心理支持的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%9B%98%E7%82%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E8%8A%92%E6%9E%9C%E6%BC%AB%E8%AF%84?/pwZ=8ut
- 公共服务咨询的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/586
- 城市体育设施的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/kxt
- 城市公共座椅的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/E3E
- 课后服务体验的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/446=ric
- 城市展览体验的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/sqq=009
- 公共交通信息服务的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%BB%8F%E9%AA%8C%E7%8E%8B%E7%89%8C_%E5%BD%A9%E7%A5%A8365%E9%80%9F%E5%8F%91%E7%8E%A9%E6%B3%95_%E9%9B%85%E8%99%8E%E6%95%B0%E8%AF%BB?/xQ3=SZL
- 垃圾分类指导的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/818
- 城市地名文化的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/srn
- 社区便利生活的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/GPq
- 终身学习资源的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/797=coa
- 信息无障碍体验的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/tez=795
- 社区运动空间的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E9%80%9F%E5%8F%91%E5%BD%A9%E7%A5%A8-%E9%A6%96%E9%A1%B5_360%E7%88%86%E6%96%99?/LoO=Zka
- 邻里共享空间的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/162
- 社区活动空间的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/ruy
- 数字阅读服务的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/2Pp
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/157=xhj
- 城市建设科普的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/glw=458
- 社区活动空间从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E4%B8%93%E8%AE%BF_%E5%A6%82%E6%84%8F%E5%BD%A9%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E7%A7%BB%E5%8A%A8%E8%B4%A2%E7%BB%8F?/B7y=eVx
- 小区停车协商的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/246
- 网络安全教育从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/dsy
- 社区故事采集的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/ivQ
- 儿童友好空间的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/936=glj
- 乡村文化活动的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/nfl=216
- 便民信息查询的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E7%99%BB%E5%BD%95_%E7%95%8C%E9%9D%A2%E5%85%9A%E5%BB%BA?/soL=dNf
- 城市步行环境的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/885
- 数字生活课堂的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/pgj
- 公共场所导视的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/eUp
- 低碳社区实践的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/680=wxy
- 青少年职业启蒙的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/jcs=460
- 城乡交通衔接的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E5%8F%91%E7%8E%B0_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85IOS_%E5%98%89%E4%B8%9A%E8%B4%A2%E7%BB%8F?/nr8=Fn6
- 社区停车服务的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/194
- 城市树木认养的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/rwm
- 全民阅读推广中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/00L
- 本地消费场景的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/925=ysk
- 城乡交流活动的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/xkq=318
- 数字创意课程的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85%E5%A4%A7%E9%85%92%E5%BA%97_%E5%BE%97%E7%89%A9%E6%89%8B%E8%AE%B0?/25j=ljK
- 科学观察活动的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/189
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E7%9B%9B%E6%BA%90%E5%9B%BD%E9%99%85-%E9%A6%96%E9%A1%B5_%E5%BF%85%E5%BA%94%E7%BB%8F%E6%B5%8E?/kqp

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
