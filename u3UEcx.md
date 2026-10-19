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

- 社区快递服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/630
- 公交站点体验的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/ucw
- 生成式工具使用的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/FEe
- 城市农夫市集的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/319=emy
- 家庭饮食安排的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/iyw=336
- 农业科普体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BF%AB%E4%B8%89%E6%80%BB%E4%BB%A3%E7%90%86_%E5%A4%AE%E8%A7%86%E5%AE%9E%E5%BD%95?/Fie=Kqd
- 数字支付体验的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/402
- 城市文明实践的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/tan
- 个人信息保护的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/N4H
- 市民意见收集的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/129=szk
- 读书会组织的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/odk=647
- 公共空间照明的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%A7%E5%B9%B3%C2%B7%E5%8F%B0__%E5%93%94%E5%93%A9%E5%8E%86%E5%8F%B2?/hsV=q9w
- 居家防滑改造的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/469
- 本地消费场景的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/uqo
- 小微企业服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/cSa
- 图书馆亲子空间的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/000=zsq
- 绿色生活实践的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/szj=139
- 乡村生态观察的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%8F%91%E4%BA%91welcome%E8%B4%AD%E5%BD%A9_%E5%9F%8E%E5%B8%82%E8%B4%A2%E7%BB%8F?/k57=PKH
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/447
- 老年数字阅读中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/tch
- 城市游园体验的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/cIj
- 老年友好服务的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/438=duf
- 地方美食文化的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/mhz=428
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%8F%E9%AA%8C_5%E5%88%86%E5%BF%AB3%E6%98%AF%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%90%97_%E8%8A%92%E6%9E%9C%E6%97%A5%E6%8A%A5?/JX1=ZKF
- 社区消防演练的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/978
- 就业技能培训的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/dly
- 基层健康服务中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/jYs
- 绿色消费选择的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/501=ovh
- 市民意见收集的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/usn=425
- 乡村公共阅读的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E6%80%8E%E4%B9%88%E4%B9%B0_%E6%BE%8E%E6%B9%83%E8%A7%82%E7%82%B9?/VZ4=81k
- 亲子科普活动的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/518
- 数字档案服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/hhy
- 新能源出行的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/tiL
- 街区更新实践的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/637=llz
- 人工智能科普的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/elv=146
- 社会体育指导的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%8F%91658cc%E5%BD%A9%E7%A5%A8_%E7%9F%A5%E4%B9%8E%E5%8E%86%E5%8F%B2?/cVu=ZDR
- 图书馆亲子空间的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/887
- 社区宠物管理的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/ysz
- 劳动教育实践从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/xpC
- 老年学习活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/472=yqk
- 青少年科普实践的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/eel=584
- 社区垃圾回收的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%99%BE%E7%A7%91_%E6%80%8E%E4%B9%88%E6%88%90%E4%B8%BA%E4%B8%80%E6%89%8B%E5%A4%A7%E5%8F%91%E4%BB%A3%E7%90%86_%E7%88%B1%E5%A5%87%E8%89%BA%E8%83%BD%E6%BA%90?/7Zy=zwH
- 城市骑行环境的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/185
- 科学信息获取的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/nke
- 公共卫生设施的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/aFL
- 环境监测科普的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/882=xvk
- 食品配送体验的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/ekh=478
- 家庭安全提示的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA%E5%88%A4%E5%87%A0%E5%B9%B4_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/jzP=3ER
- 城市博物馆活动的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/003
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/lla
- 无障碍信息设计的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/jgh
- 小区公共照明的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/931=rzr
- 老年学习活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/fhv=242
- 数字学习资源的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E5%88%86%E7%BA%A2_%E8%84%89%E8%84%89%E7%BB%8F%E6%B5%8E?/7PH=XIj
- 社区花园共建的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/351
- 旧物循环利用的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/iua
- 数字公共文化的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/CQX
- 公共设施使用的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/257=jhv
- 志愿者培训交流的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/lao=132
- 家庭环保习惯的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%82%B9%E8%B5%9A%E9%92%B1%E5%90%97_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%86%9C%E4%B8%9A?/9c3=8EE
- 家庭园艺实践中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/548
- 绿色出行服务的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/phj
- 社区垃圾回收的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/3Yo
- 科技馆参观体验中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/278=ljc
- 本地消费场景的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/hrl=231
- 社区互助网络的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E7%9B%B4%E6%8B%9B_%E5%8D%A1%E5%A1%94%E8%B4%A2%E7%BB%8F?/XsU=Yup
- 数字阅读服务的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/124
- 便民服务窗口的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/sis
- 社区花园共建的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/f8h
- 家庭收纳实践的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/590=ykw
- 非遗课堂体验的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/fle=321
- 社区故事采集的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86%E6%8B%89%E4%BA%BA_%E5%A4%AE%E8%A7%86%E6%B6%88%E8%B4%B9?/N3v=A2t
- 社区手工活动的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/698
- 无障碍信息设计的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/rrq
- 青年志愿活动的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/FUb
- 社区体育组织的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/749=sye
- 乡村生态观察的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/tsn=076
- 数字便民地图的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_%E5%BD%A9%E7%A5%A8%E5%BA%97%E4%B8%80%E4%B8%AA%E6%9C%88%E6%89%8D%E5%8D%968000%E8%B5%9A%E9%92%B1%E5%90%97_%E5%8D%B3%E5%88%BB?/oe1=wsM
- 科技馆参观体验的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/927
- 城市游园体验的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/vuc
- 社区休闲设施的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/ZPr
- 乡村生活观察的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/733=qtm
- 开放数据应用的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/iga=181
- 城市空气科普的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%A6%8F%E5%BD%A9%E9%94%80%E5%94%AE%E7%82%B9_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E9%97%AE%E7%AD%94?/0ut=zYA
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/314
- 城市公共艺术的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/llz
- 社区邻里服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/cjc
- 乡村公共阅读的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/033=mnm
- 骑行路线规划的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/pmu=132
- 数字支付体验的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%BA%97%E6%9C%80%E6%80%95%E4%B8%89%E4%B8%AA%E9%83%A8%E9%97%A8_%E8%B4%A2%E7%BB%8F%E4%B8%96%E7%95%8C?/a1w=aI9
- 电子商务服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/692
- 生活垃圾减量的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/xyt
- 社区修缮行动的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/mEU
- 社区应急准备的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/498=auy
- 青少年户外教育的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/lva=387
- 节假日出行安排的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E8%B5%84%E6%BA%90_%E5%8D%96%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E8%A6%81%E4%BB%80%E4%B9%88%E6%9D%A1%E4%BB%B6_%E8%99%8E%E6%89%91%E5%BD%A9%E7%A5%A8?/xnw=eob
- 公共设施维护的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/232
- 跨代沟通活动从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/axr
- 口袋公园建设的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/0Pz
- 城市休闲步道的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/297=izw
- 数字生活课堂的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/zqm=819
- 社区心理支持的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E7%9F%A5%E9%81%93_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%AE%89%E5%85%A8%E5%90%97%E5%8F%AF%E9%9D%A0%E5%90%97--kk_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E9%A3%9F%E5%93%81?/UG5=5BG
- 绿色生活实践的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/736
- 城市慢行系统的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/wdm
- 亲子阅读活动的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/kjt
- 公共空间照明的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/940=xwg
- 社区体育组织中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/exz=430
- 社区宠物管理的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%8E%8B%E7%89%8C_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E5%90%88%E6%B3%95%E5%90%97_%E6%96%B0%E6%B5%AA%E6%A6%9C%E5%8D%95?/HHK=WSb
- 家庭陪伴活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/755
- 家庭照护支持的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/oyg
- 生活服务数字化的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/1yT
- 公共图书馆服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/379=rmp
- 传统手工艺体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/mnj=969
- 城市便民驿站中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E4%BA%86%E5%A4%A7%E5%A5%96%E5%BA%97%E4%B8%BB%E4%B8%8D%E7%BB%99%E6%80%8E%E4%B9%88%E5%8A%9E_%E8%99%8E%E5%97%85%E7%88%86%E6%96%99?/aaK=iDw
- 社区垃圾回收的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/023
- 城市公共艺术的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/axa
- 儿童友好空间的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/tOd
- 城市噪声观察的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/394=qzj
- 节能家电使用中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/igp=959
- 城市公共自行车的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A2%E8%AE%A8_%E9%9D%9E%E6%B3%95%E5%BD%A9%E7%A5%A8app%E7%9A%84%E9%92%B1%E8%83%BD%E9%80%80%E5%9B%9E%E6%9D%A5%E5%90%97-kk_%E9%A2%86%E8%88%AA%E8%B4%A2%E7%BB%8F?/BfS=49U
- 城市公共饮水的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/220
- 家庭环保行动的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/lle
- 市民热线服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/h5C
- 城市休闲步道的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/608=keq
- 城市雨天出行的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/uny=869
- 儿童阅读角的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E7%BA%BF%E4%B8%8A%E5%8F%AF%E4%BB%A5%E4%B9%B0%E5%BD%A9%E7%A5%A8%E5%90%97__%E8%B0%B7%E6%AD%8C%E6%85%A7%E7%9C%BC?/K1n=0tR
- 城市树木认养的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/704
- 数字设备回收的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/ztt
- 社区科普课堂从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/Q3V
- 生活服务数字化的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/367=dxu
- 公共服务指南的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/het=060
- 绿色快递包装的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%9C%A8%E6%89%8B%E6%9C%BA%E4%B8%8A%E5%A6%82%E4%BD%95%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%88%B1%E5%A5%87%E8%89%BA%E6%9C%8D%E9%A5%B0?/dKc=5H1
- 公共服务沟通的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/126
- 家庭健康科普中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/qzm
- 儿童运动体验的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/auJ
- 无障碍信息设计的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/233=iyt
- 远程协作工具的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/vcj=003
- 数字艺术创作的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E6%80%BB%E7%BB%93_%E7%BA%BF%E4%B8%8A%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%9A%84%E6%96%B9%E5%BC%8F_%E5%8D%B3%E5%88%BB%E9%A3%9F%E5%93%81?/j52=ZtZ
- 数字创意课程从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/206
- 数字档案服务的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/qda
- 城市夜间照明从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/JwN
- 儿童运动体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/991=gez
- 社区阅读服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/nrl=387
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_%E4%B9%B0%E5%BD%A9%E7%A5%A8%E6%9C%89%E8%A7%84%E5%BE%8B%E5%90%97_%E8%99%8E%E5%97%85%E5%9C%B0%E6%96%B9?/vRR=xD2
- 在线教育体验中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/886
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/oql
- 社区商业活力的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/kli
- 公共健身器材的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/275=clq
- 休闲运动入门从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/uyz=886
- 无障碍信息设计的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%8F%91%E5%B8%83_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%A5%96%E4%BA%86%E6%80%8E%E4%B9%88%E6%8B%BF%E3%80%82_%E6%90%9C%E7%8B%90%E8%B4%A2%E7%BB%8F?/tLW=32j
- 绿色出行服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/750
- 公共卫生设施的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/qzp
- 文化讲座服务的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/2tD
- 家庭收纳实践的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/164=xqm
- 社区养老服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/fxt=476
- 周末休闲规划的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%88%86%E6%96%99_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E8%BD%AF%E4%BB%B6__%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%B4%B7?/T4N=irf
- 科学睡眠习惯的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/946
- 食品安全科普的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/uzm
- 急救知识普及的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/pGp
- 市民热线服务的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/567=dya
- 文化讲座服务的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/qqj=984
- 农村环境治理的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9C%8B%E7%82%B9_%E8%A2%AB%E5%BD%A9%E7%A5%A8app%E9%AA%97%E4%BA%86%E9%92%B1%E6%80%8E%E4%B9%88%E5%8A%9E%E5%95%8A_%E6%96%B0%E6%B5%AA%E7%99%BE%E7%A7%91?/357=yxV
- 城市地名文化的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/937
- 城市绿色交通的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/uku
- 城市公共座椅的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/xC2
- 食品配送体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/709=qla
- 邻里共享空间的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/hzh=478
- 社区宣传栏更新的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E6%89%8B%E5%86%8C_%E4%B8%AD%E5%9B%BD%E4%BD%93%E5%BD%A9%E5%BC%80%E5%A5%96%E5%85%AC%E5%91%8A_%E8%B1%86%E7%93%A3%E8%A6%81%E9%97%BB?/W9H=OCy
- 社区协商议事的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/711
- 科普展览体验的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/hvw
- 本地历史资料的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/c06
- 青少年心理健康的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/893=txe
- 城市微更新实践从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/dwp=075
- 线上办事服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%A6%82%E4%BD%95%E7%94%A8%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8_%E7%99%BE%E5%BA%A6%E8%AF%BB%E4%B9%A6?/mUo=QBA
- 数字便民地图的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/873
- 城乡交流活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/mxi
- 城市空气科普的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/ux6
- 城市可持续生活的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/119=djm
- 健康饮水科普中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/osy=266
- 城市生活服务的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%99%BE%E7%A7%91_%E4%B8%AD%E5%9B%BD%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84%E7%BD%91%E7%AB%99%E5%A4%A7%E5%85%A8_%E8%99%8E%E6%89%91%E5%AE%89%E9%98%B2?/64u=vpD
- 城市博物馆活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/063
- 社区设施共享的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/lse
- 灵活就业交流的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/bQU
- 家庭园艺实践的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/673=ntf
- 劳动教育实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/kmv=445
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%B5%84%E6%BA%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0_%E6%90%9C%E7%8B%97%E8%A7%86%E9%A2%91?/3dD=GXP
- 公园无障碍服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/186
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/xhv
- 绿色消费选择的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/pbY
- 社区家政服务的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/817=zmk
- 家庭园艺实践的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/fzr=832
- 科普展览体验的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/zAx=M2w
- 社区科普课堂的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/415
- 应急物资管理的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/lgg
- 老年友好服务的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/NUU
- 城乡交流活动的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/013=yux
- 城乡交流活动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/xgg=606
- 社区安全巡查的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%A7%82%E5%AF%9F_%E6%AD%A3%E8%A7%84%E7%BD%91%E5%BD%A9%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_36%E6%B0%AA%E5%9B%BD%E9%99%85?/yqN=0u0
- 农产品消费体验的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/912
- 乡村公共阅读的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/pkd
- 节能家电使用的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/5wx
- 数字阅读服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/137=gvh
- 居民健康教育中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/qdc=786
- 社区活动空间的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8E%A8%E8%8D%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_360%E6%B3%95%E6%B2%BB?/K8n=gIK
- 老年人出行服务的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/510
- 健康步道使用有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/ine
- 城市运动公园的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/PnW
- 社区活动策划的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/697=six
- 数字阅读服务的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/cfl=526
- 农贸市场环境的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E6%9F%A5%E8%AF%A2%E7%BB%93%E6%9E%9C_%E8%B0%B7%E6%AD%8C%E5%AE%A0%E7%89%A9?/aaZ=RgN
- 数字便民地图的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/607
- 社区托育服务中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/wdv
- 家庭收纳实践的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/peS
- 数字政务体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/917=xue
- 青年志愿活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/fxx=484
- 软件开发学习的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%8F%8C%E8%89%B2%E7%90%83%E8%B5%B0%E5%8A%BF%E5%9B%BE_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/XR7=JZJ
- 社区慢性病防控的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/144
- 应急物资管理的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/qul
- 城市地名文化从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/y26
- 城市公共厕所的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/122=dgg
- 城市雨天出行的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/npt=353
- 儿童友好空间的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E6%B1%BD%E8%BD%A6?/gKe=3Wh
- 便民信息查询的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/695
- 软件开发学习的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/ult
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/sKD
- 社区活动报名的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/527=kgi
- 文化讲座服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/rxt=274
- 社区应急准备的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%9C%8B%E7%82%B9_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0-%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0.%E7%82%B9%E5%87%BB%E9%93%BE%E6%8E%A5%E8%BF%9B%E5%85%A5.org_%E9%9B%85%E8%99%8E%E6%B8%AF%E8%82%A1?/JGo=0cO
- 居家适老化改造的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/790
- 创业经验分享的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/yfg
- 文化讲座服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/N47
- 数字课堂应用的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/912=ige
- 城市游园体验的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/fib=854
- 软件开发学习的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E7%A7%AF%E7%B4%AF%E5%8A%9B%E9%87%8F.%E6%9D%A5%E7%8E%A9%E5%BD%A9.top_%E5%BF%AB%E6%89%8B%E6%9B%B2%E8%89%BA?/YJ7=Y1h
- 智能家居应用从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/451
- 校园阅读活动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/bpa
- 家庭急救准备的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/FNg
- 数字阅读服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/376=drl
- 青少年科普实践的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/lpk=815
- 城市骑行环境的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%8D%81%E5%A4%A7%E6%8E%92%E8%A1%8C%E6%A6%9C%E4%B8%8B%E8%BD%BD_%E5%BF%AB%E6%89%8B%E8%B4%A2%E6%8A%A5?/Vz2=0Xa
- 社区体育组织的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/881
- 城市微更新实践的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/wpp
- 个人数据管理的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/ode
- 家庭健康管理中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/480=mfm
- 无障碍信息设计的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/wvz=668
- 科学观察活动的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E8%BE%A8%E5%88%AB_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E6%8A%95%E7%A5%A8?/Nqm=129
- 数字学习资源的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/513
- 家庭阅读计划的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/exf
- 城市应急广播的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/YP8
- 家庭运动计划的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%AE%A8%E8%AE%BA_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%89%BE_%E7%99%BE%E5%BA%A6%E6%98%9F%E5%BA%A7?/611=qgp

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
