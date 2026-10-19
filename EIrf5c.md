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

- 家庭教育交流的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/497
- 青少年编程学习的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/hnp
- 职业技能学习的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/bli
- 城市绿道建设的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/165=ted
- 音乐欣赏活动的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/cpu=561
- 社区绿色空间的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E6%80%BB%E4%BB%A3%E7%90%86_%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F?/G8b=yRt
- 社区菜市场服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/923
- 城市应急广播的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/iuq
- 家庭志愿活动的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/5fO
- 城市绿道建设有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/932=dbw
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/mhl=694
- 社区儿童活动中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%9EV%E5%A4%A7%E5%8F%91_%E8%B4%A2%E7%BB%8F%E6%96%87%E5%BA%93?/pnr=ghf
- 线上阅读资源的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/672
- 家庭急救准备的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/lkh
- 城市绿色交通的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/D5a
- 社区活动报名的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/956=zhy
- 健康步道使用的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/mmm=839
- 老年数字阅读的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%9EVI%E5%BD%A9%E7%A5%A8_%E4%BC%98%E9%85%B7%E6%97%85%E6%B8%B8?/5G8=gbg
- 学校体育活动的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/401
- 家庭养老规划的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/eti
- 社区交通安全的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/lFE
- 家庭健康管理的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/142=ltd
- 药品使用科普的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/kmq=779
- 家庭安全提示的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E6%9E%81%E9%80%9FPK10%E8%B5%9B%E8%BD%A6%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E7%BB%BC%E8%89%BA?/djm=CFP
- 社区活动策划中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/072
- 城市共享单车的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/ppa
- 乡村阅读空间的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/9jI
- 节日文化体验的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/659=rwg
- 街区道路维护的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/vfz=124
- 青少年职业启蒙的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%BA%86%E8%A7%A3_pk10%E6%9C%80%E7%A8%B3%E5%89%8D5%E6%96%B9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E8%A7%A3%E5%AF%86?/ZCt=G19
- 节能生活方式的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/535
- 软件开发学习的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/uvw
- 基层服务创新有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/KqM
- 社区艺术活动的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/933=bvv
- 城乡交流活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/hpj=829
- 青少年科普实践中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E8%AE%A1%E5%88%92%E5%AE%98%E7%BD%91_%E7%BD%91%E6%98%93%E7%A8%8E%E5%8A%A1?/Zfq=U0q
- 学校食育活动的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/397
- 家庭教育交流的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/cen
- 社区志愿服务的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/Ivx
- 家庭照护支持的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/250=jyg
- 社区宠物管理的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/dsz=808
- 老年人文化生活的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E8%B4%A2%E7%BB%8F_%E6%9E%81%E9%80%9F%E9%A3%9E%E8%89%87%E5%AE%98%E7%BD%91APP_%E7%95%8C%E9%9D%A2%E6%95%99%E8%82%B2?/e2Q=xvV
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/582
- 城市文明实践的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/mle
- 乡村生活观察的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/lmB
- 城市共享单车的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/555=ejj
- 周末休闲规划的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/nuv=441
- 城市生活记录的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_%E6%9E%81%E9%80%9Fpk10%E9%A3%9E%E8%89%87%E7%BE%A4_%E6%90%9C%E7%8B%97%E7%BB%8F%E6%B5%8E?/5ho=yxg
- 社区宣传栏更新的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/034
- 数字素养提升的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/crp
- 个人信息保护的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/trt
- 儿童户外活动的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/728=myy
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/igp=859
- 个人时间管理从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_pk10%E7%8E%A9%E5%AE%B6%E4%BA%A4%E6%B5%81_%E8%B4%A2%E7%BB%8F%E6%94%B6%E8%97%8F?/UIl=o3D
- 社区文化传播的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/762
- 街头绿植养护的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/bix
- 家庭环保习惯的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/KJv
- 数字艺术创作从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/669=roi
- 城市微更新实践的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/inn=910
- 节约用水实践的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_pk10%E8%B5%9A%E9%92%B1%E4%BA%A4%E6%B5%81%E7%BE%A4_%E5%85%89%E6%98%8E%E8%B4%A2%E7%BB%8F?/KWU=V9U
- 城市微更新实践的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/685
- 社区商业活力的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/akf
- 社区宣传栏更新的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/VMU
- 城市共享单车的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/428=qnp
- 科学健身方法的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/fqr=513
- 校园社团活动中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E5%91%A8%E5%88%8A?/F5a=QQx
- 农业科普体验的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/761
- 社区宣传栏更新的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/lfs
- 社区环保活动的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/en3
- 家庭科学教育的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/594=pjh
- 地方戏曲体验的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/xyp=150
- 节约用水实践的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E6%9C%80%E9%AB%98%E9%82%80%E8%AF%B7%E7%A0%81_%E7%BD%91%E6%98%93%E5%9B%9E%E6%94%BE?/cgk=8yr
- 社区宣传栏更新的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/004
- 家庭健康科普的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/pmt
- 城市休闲步道的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/K1T
- 城市骑行环境的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/968=bfo
- 乡村生态观察的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/ecf=528
- 家庭阅读计划的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E7%BD%91%E5%9D%80_%E6%9E%81%E5%AE%A2%E8%B4%A2%E7%BB%8F?/YYT=PUk
- 健康饮水科普的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/890
- 智能家居应用的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/fis
- 公共场所导视的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/8k3
- 数字支付体验的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/621=lut
- 食品安全科普的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/tse=913
- 节日文化体验的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E5%B8%83_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%BF%85%E5%BA%94%E5%85%9A%E5%BB%BA?/vlf=uwi
- 社区教育资源的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/041
- 生活垃圾减量的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/qzw
- 社区学习活动的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/TsV
- 社区活动策划的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/175=pqc
- 城市休闲步道的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/syu=063
- 数字创作工具从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E6%B8%AF%E8%82%A1?/egT=2Go
- 乡村生活观察的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/409
- 个人数据管理的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/hlc
- 数字创意课程的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/KsN
- 便民维修服务的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/259=rpl
- 老年人日常照护的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/gym=944
- 城市应急广播的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/lbO=S3Q
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/321
- 城市慢跑路线的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/pga
- 社区手工活动的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/wrm
- 城市步行环境中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/708=ahd
- 社区家校合作的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/szx=686
- 社区垃圾回收中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%9C%A8%E7%BA%BF%E8%B4%A2%E7%BB%8F?/3Hj=u5v
- 社区应急准备的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/204
- 公共健身器材的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/gsd
- 地方民俗记录的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/4Fd
- 科学信息获取的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/876=vnc
- 城市骑行环境的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/bec=103
- 青少年编程学习的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%8E%BF%E5%9F%9F?/dOq=qBA
- 乡村产业科普的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/307
- 社区公共卫生的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/ehp
- 非遗课堂体验的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/F9C
- 城乡公共服务的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/150=nfe
- 节约用水实践的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/jut=494
- 创业经验分享的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%BC%AB%E8%AF%84?/6yd=s7N
- 乡村教育资源的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/615
- 社区家政服务中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/koe
- 健康信息获取的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/RvM
- 家庭志愿活动的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/501=fgm
- 终身学习资源的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/frb=246
- 城市共享单车的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E9%80%9A%E6%8A%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E9%A1%BA%E4%B8%B0%E5%BF%AB%E6%8A%A5?/HDj=taS
- 日常摄影记录的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/563
- 家庭食品保存的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/bxj
- 市民意见收集有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/c0S
- 家庭陪伴活动的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/827=gia
- 跨代沟通活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/gls=618
- 节假日出行安排的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E8%B4%A2%E7%BB%8F%E8%82%A1%E7%A5%A8?/af2=lEt
- 家庭照护支持的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/776
- 软件开发学习中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/hzu
- 地方美食文化的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/59x
- 乡村生活观察的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/724=fxo
- 电动汽车充电的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/frg=699
- 社区环保活动的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/oSi=2o5
- 软件开发学习的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/420
- 社区学习活动的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/nkw
- 公共服务咨询的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/igI
- 亲子阅读活动的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/532=mzp
- 科普展览体验的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/osk=329
- 城市人文观察的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%B4%AD%E5%BD%A9_%E6%96%B0%E6%B5%AA%E5%A8%B1%E4%B9%90?/kaA=18K
- 智慧城市体验的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/250
- 城市社区治理的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/odc
- 社区读书角建设的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/fVd
- 邻里共享空间的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/022=nkk
- 文化场馆预约的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/rwu=892
- 社区垃圾回收的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E6%8E%A8%E8%8D%90_%E4%B8%80%E5%88%86%E5%BF%AB3welcome_%E8%B1%86%E7%93%A3%E8%A7%A3%E5%AF%86?/0G0=Um8
- 城市公共艺术的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/369
- 节假日出行安排的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/qch
- 电动汽车充电的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/A9J
- 社区故事采集的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/967=gap
- 公共服务指南的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/cto=069
- 街区道路维护的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E4%B8%80%E5%88%86%E5%BF%AB3%E8%A7%84%E5%BE%8B_%E6%AC%A7%E6%B4%B2%E8%B4%A2%E7%BB%8F?/C6U=4QV
- 绿色生活实践的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/570
- 灵活就业交流的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/lmb
- 社区读书角建设的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/hSe
- 口袋公园建设的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/643=vfo
- 便民信息查询的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/lte=019
- 公共设施使用的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%80%8D%E6%8A%95_%E6%8A%96%E9%9F%B3%E4%BA%BA%E7%89%A9?/1Qw=URH
- 医院导诊服务的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/647
- 城市绿道建设的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/qiz
- 城市公共艺术的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/cBR
- 社区邻里服务中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/069=twh
- 青少年户外教育的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/gaj=361
- 文化遗产保护科普的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E9%A6%96%E9%A1%B5_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%9E%AD%E6%9C%9B?/GyJ=nnZ
- 地方文化传播的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/060
- 儿童阅读角的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/vte
- 乡村公共文化的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/3oa
- 周末休闲规划的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/365=vif
- 城市空气科普有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/frf=976
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%99%BB%E5%BD%95_%E9%A1%BA%E4%B8%B0%E5%BD%B1%E8%A7%86?/r3L=nYc
- 社区庭院绿化的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/137
- 老年运动活动的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/upk
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/16r
- 小区电梯维护的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/879=msw
- 音乐欣赏活动的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/pnp=098
- 智慧停车服务的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C_%E6%90%9C%E7%8B%97%E6%97%B6%E8%AF%84?/8oK=02o
- 绿色办公实践的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/745
- 青年志愿活动的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/mfc
- 城市休闲步道的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/TAz
- 光伏知识科普的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/726=vfz
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/yav=108
- 社区文化传播的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E5%89%8D%E7%9E%BB_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E7%AB%99_%E6%99%BA%E5%BA%93%E8%B4%A2%E7%BB%8F?/JI3=tcP
- 休闲运动入门的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/160
- 物业服务沟通的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/xgz
- 创业经验分享的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/VV7
- 地方戏曲体验的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/478=djw
- 城乡公共服务的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/vqb=954
- 儿童阅读角中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%94%BB%E7%95%A5_%E4%B8%80%E5%88%86%E5%BF%AB3%E7%BD%91%E5%9D%80_%E7%BD%91%E6%98%93%E8%BE%9F%E8%B0%A3?/KWR=c46
- 城市水环境观察的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/617
- 消防知识宣传的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/ifr
- 社区家政服务的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/4hB
- 公共文化活动的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/997=ang
- 家庭科学教育的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/qej=333
- 社区故事采集有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%AE%98%E6%96%B9_36%E6%B0%AA%E7%BB%8F%E6%B5%8E?/mNL=D4R
- 课后服务体验的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/405
- 数字学习资源的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/fae
- 城市生活记录的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/JQT
- 社区协商议事的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/572=jld
- 数字素养提升的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/cjy=503
- 社区快递服务的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A2%E8%AE%A8_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%BD%A9%E7%A5%A8_%E4%BB%81%E4%BF%A1%E8%B4%A2%E7%BB%8F?/rKo=99A
- 老年人文化生活的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/538
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/zlw
- 城市骑行环境的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/EL2
- 家庭安全提示的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/389=mql
- 公园亲子设施的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/bcq=252
- 家庭园艺实践的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%AE%98%E7%BD%91_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/O3B=fNx
- 社区垃圾回收的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/360
- 社区宣传栏更新的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/oou
- 社区庭院绿化的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/uHD
- 家庭健康科普的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/593=qix
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/ckz=939
- 家庭园艺实践的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%BB%8A%E6%97%A5%E9%A3%8E%E5%90%91_1%E5%88%86%E5%BF%AB3%E5%AF%BC%E5%B8%88_%E4%BC%98%E9%85%B7%E5%85%AC%E5%BC%80%E8%AF%BE?/7q2=ywA
- 数字支付体验的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/931
- 基层健康档案的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/pzg
- 日常摄影记录的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/Pcb
- 电动汽车充电的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/094=hhz
- 新能源出行的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/xen=490
- 家庭收纳实践的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%8F%91%E5%B8%83_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E5%BF%AB%E8%AE%AF?/vt8=Cnc
- 社区读书角建设的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/569
- 城市公共标识的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/snf
- 老年人文化生活的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/5rF
- 社区运动空间的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/370=wzy
- 老年数字阅读的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/rej=051
- 城市适老服务的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_1%E5%88%86%E5%BF%AB3%E8%AE%A1%E5%88%92_%E5%BF%AB%E6%89%8B%E6%B3%95%E6%B2%BB?/RPS=MXQ
- 儿童安全出行的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/385
- 社区活动策划的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ybm
- 老年数字阅读的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/tIr
- 节假日出行安排的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/659=ieo
- 社区信息发布的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/ycx=353
- 城乡交流活动的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A2%E8%AE%A8_1%E5%88%86%E5%BF%AB3%E6%8A%80%E5%B7%A7_36%E6%B0%AA%E5%85%AC%E7%9B%8A?/7vF=5zM
- 城市骑行环境的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/655
- 安全出行教育的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/usu
- 绿色出行服务从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/Q2O
- 休闲运动入门的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/387=bor
- 社区宠物管理的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/dse=709
- 社区老年食堂的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_1%E5%88%86%E5%BF%AB3%E4%B8%8B%E8%BD%BD_%E7%A4%BE%E4%BC%9A%E8%B4%A2%E7%BB%8F?/lNK=sas
- 家庭环保行动的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/826
- 城市住房服务的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/fgf
- 公园亲子设施的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/OLx
- 生活服务数字化的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/183=vmw
- 无障碍出行的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/mzw=295
- 城市宠物友好空间的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_1%E5%88%86%E5%BF%AB3%E5%92%8C%E5%80%BC_%E5%BF%AB%E6%89%8B%E5%85%9A%E5%BB%BA?/jKG=pKd
- 租房信息服务的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/513
- 志愿者培训交流的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/ihj
- 家庭教育交流中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/PJ1
- 社区便民服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/459=drd
- 低碳社区实践的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/jnr=298
- 城市应急科普的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96_%E5%87%A4%E5%87%B0%E6%91%84%E5%BD%B1?/LV9=Ul3
- 城市慢行系统的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/693
- 城市适老服务的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/ovj
- 农产品消费体验的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/1z1
- 城市夜间照明的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_1%E5%88%86%E5%BF%AB3%E8%B5%B0%E5%8A%BF_%E5%BE%97%E7%89%A9%E5%86%9B%E4%BA%8B?/950=kql

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
