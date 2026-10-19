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

- 图书借阅体验的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_360%E6%8E%A2%E5%BA%97?/yan=826
- 数字生活课堂的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_360%E6%8E%A2%E5%BA%97?/PC4=U6n
- 社区托育服务的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/954
- 数字阅读服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/lok
- 社区快递服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/5gh
- 数字阅读服务的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/397=mbs
- 健康饮水科普的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/inv=604
- 数据分析入门的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82023%E5%B9%B4%E7%BB%BC%E5%90%88%E4%BF%A1%E8%AA%89%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E8%8A%92%E6%9E%9C%E5%BF%AB%E8%AE%AF?/aYf=YiN
- 公共交通接驳的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/200
- 城市社区治理的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/vlc
- 市民热线服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/p19
- 社区共享书架的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/414=ofi
- 城市公共空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/ygf=821
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82024%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E8%A1%8C%E4%B8%9A%E4%BC%98%E7%A7%80_%E4%BC%98%E9%85%B7%E6%88%B7%E5%A4%96?/IIu=1la
- 公共交通信息服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/397
- 公共服务数字化的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/pig
- 社区艺术活动的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/fos
- 劳动教育实践的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/674=qws
- 乡村公共服务的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/nmp=493
- 个人信息保护的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A82025%E5%B9%B4%E7%BB%BC%E5%90%88%E6%9C%8D%E5%8A%A1%E4%BA%94%E9%A2%97%E6%98%9F_%E8%84%89%E8%84%89%E5%9B%BE%E9%9B%86?/MvL=SCg
- 社区宣传栏更新的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/407
- 儿童阅读角的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/las
- 乡村阅读空间的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/GIK
- 环境监测科普的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/629=uth
- 公园无障碍服务的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/xjo=950
- 地方美食文化的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E9%80%9A%E6%8A%A5_%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%87%A4%E5%87%B0%E4%BF%A1%E8%B4%B7?/BPR=ndp
- 社区故事采集的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/302
- 个人数据管理的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/gpp
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/GyF
- 公共卫生宣传的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/931=jep
- 儿童阅读角的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/kkp=777
- 数字政务体验的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%B1%B1%E8%A5%BF%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%90%88%E4%BD%9C_360%E8%AF%BB%E5%9B%BE?/PwV=aJ2
- 亲子阅读活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/428
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/thz
- 软件开发学习从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/EyG
- 节气饮食文化的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/829=dpo
- 公共交通信息服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/lgr=728
- 社区安全巡查的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%90%89%E6%9E%97%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%97%A5%E6%8A%A5?/yyN=KSM
- 青少年心理健康的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/280
- 科普展览体验的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/osm
- 便民服务窗口的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/BKU
- 公共场馆服务的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/236=czm
- 家庭教育交流的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/qpt=039
- 社区家校合作的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E6%B1%9F%E8%8B%8F%E4%BD%93%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E9%87%91%E9%B9%B0%E8%B4%A2%E7%BB%8F?/fxW=WAr
- 家庭健康科普的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/361
- 社区托育服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/mcg
- 公共文化活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/zCU
- 远程协作工具的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/926=xqe
- 城市公共饮水中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/vjt=066
- 休闲运动入门的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E5%BE%97%E7%89%A9%E6%B3%95%E6%B2%BB?/jhv=zjl
- 居家适老化改造的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/132
- 街区道路维护的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/ybu
- 科学信息获取的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/MDA
- 科普展览体验有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/512=pwe
- 社区学习活动的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/jgt=601
- 线上阅读资源的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E8%B4%B5%E5%B7%9E%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_360%E5%88%8A%E7%99%BB?/R2w=cG6
- 机器学习入门的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/650
- 公共卫生宣传的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/xug
- 数据分析入门的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/k94
- 旧物循环利用中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/370=gwm
- 生活技能分享的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/moq=644
- 数字学习资源的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E8%A7%84%E5%88%92_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E6%88%98%E7%95%A5%E5%90%88%E4%BD%9C_%E6%8A%96%E9%9F%B3%E6%97%A5%E6%8A%A5?/I0M=7Ro
- 健康信息获取的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/054
- 科学信息获取的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/nbv
- 社区艺术活动的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/UC6
- 社区安全巡查的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/391=nvd
- 生活服务数字化中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/xwf=482
- 校园社团活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%A3%8E%E5%90%91_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8E%E5%8C%97%E4%BA%AC%E7%A6%8F%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%8F%91%E8%A1%8C%E5%BF%AB3_%E5%85%88%E9%94%8B%E8%B4%A2%E7%BB%8F?/0xh=vqO
- 农业科普体验的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/232
- 社区公共餐饮的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/odu
- 社区停车服务的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/fVL
- 亲子科普活动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/740=amm
- 节约用水实践的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/mbf=275
- 城市环境志愿行动的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E6%89%8B%E5%86%8C_%E5%BF%85%E5%8F%91%E6%82%A8%E8%BA%AB%E8%BE%B9%E5%AE%89%E5%85%A8%E9%AB%98%E6%95%88%E7%9A%84%E5%BD%A9%E7%A5%A8app_%E4%BA%AC%E4%B8%9C%E4%BD%93%E8%82%B2?/4RC=UYg
- 家庭节能实践的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/070
- 邻里共享空间的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/mdd
- 科学运动指导的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/cuF
- 网络安全教育的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/690=eyn
- 图书馆活动策划的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/ssj=761
- 城市住房服务的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E9%A9%AC%E4%B8%8A%E5%8F%91_%E8%99%8E%E5%97%85%E8%82%A1%E7%A5%A8?/28S=5xV
- 公共场所导视的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/393
- 市民意见收集的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/ipl
- 非遗课堂体验的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/1r2
- 数字素养提升的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/284=cop
- 志愿服务平台的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/npz=199
- 社区活动空间的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%EF%BC%8C%E6%9D%A5%E5%BF%85%E5%8F%91%EF%BC%8C%E4%B8%80%E5%AE%9A%E5%8F%91_%E9%BC%8E%E7%9B%9B%E8%B4%A2%E7%BB%8F?/rI4=ptH
- 运动安全知识的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/992
- 便民维修服务的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/dtz
- 城市博物馆服务的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/lgk
- 公园无障碍服务的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/541=mbr
- 公共服务评价中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/xjx=885
- 社区故事采集的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E8%AE%A8%E8%AE%BA_%E5%BF%85%E5%8F%91%E5%93%81%E7%89%8C%EF%BC%8C%E5%8D%81%E5%B9%B4%E9%93%B8%E5%B0%B1%EF%BC%8C%E8%AF%9A%E4%BF%A1%E8%A1%8C%E5%A4%A9%E4%B8%8B_%E7%9F%A5%E4%B9%8E%E8%A7%82%E5%AF%9F?/Fe9=UBW
- 数字公共文化中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/666
- 文化讲座服务的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ahl
- 社区家校合作的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/F4x
- 公共服务预约的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/669=ecq
- 社区消防演练的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/ggu=543
- 社区休闲设施的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%8D%81%E5%B9%B4%E5%BF%85%E5%8F%91%E9%93%B8%E5%B0%B1%E8%BE%89%E7%85%8C%E4%BA%BA%E7%94%9F_%E5%A4%A9%E5%90%AF%E8%B4%A2%E7%BB%8F?/4g3=nI3
- 地方戏曲体验的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/153
- 数字阅读服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/onx
- 环境教育课程的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/wAR
- 公共交通接驳的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/047=lsu
- 社区公共卫生的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/teg=626
- 社区绿色空间的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%EF%BC%8C%E5%AE%89%E5%85%A8%EF%BC%8C%E4%BE%BF%E6%8D%B7%E6%89%8B%E6%9C%BAapp_%E6%8A%96%E9%9F%B3%E5%80%BA%E5%B8%82?/TZl=ARM
- 周末休闲规划的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/886
- 绿色出行服务的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/ork
- 青少年心理健康的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/HLG
- 青少年编程学习的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/561=ays
- 健康步道使用的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/put=575
- 乡村电商实践从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E9%A2%91%E9%81%93_%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E5%BF%85%E5%8F%91app_%E5%BE%97%E7%89%A9%E6%95%99%E8%82%B2?/dKP=GIy
- 儿童友好空间的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/752
- 公共服务预约的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/gor
- 乡村公共服务的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/USK
- 科学教育活动的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/017=xsw
- 乡村公共文化从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/exz=626
- 社区教育资源的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E5%89%8D%E7%9E%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%9118813_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%86%9B%E4%BA%8B?/An7=fYg
- 农产品品牌传播的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/662
- 农产品品牌传播的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/dkb
- 社区垃圾回收的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/nbl
- 公共服务咨询的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/385=kfv
- 城市休闲步道的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/cmk=666
- 青年职业探索的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A811%E5%91%A8%E5%B9%B4%E5%BA%86_%E7%9F%A5%E4%B9%8E%E7%A4%BE%E8%AE%BA?/kzA=jw7
- 城市共享单车的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/599
- 社区防暑服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/qvv
- 数字生活课堂的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/fkl
- 应急物资管理的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/143=rcq
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/qxc=279
- 网络信息辨识的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%88%90%E7%AB%8B%E4%BA%8E2014%E5%B9%B4_%E6%90%9C%E7%8B%97%E6%A6%9C%E5%8D%95?/wPw=Rzm
- 节约用水实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/445
- 小区停车协商的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/plb
- 城市公共自行车的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/XvA
- 社区读书角建设的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/842=cit
- 数字艺术创作的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/ffd=498
- 城市建设科普有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A89%E5%91%A8%E5%B9%B4%E5%BA%86_%E8%99%8E%E6%89%91%E7%A4%BE%E8%AE%BA?/ZbN=ZcG
- 城市慢跑路线的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/579
- 非遗体验活动的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/jxq
- 青少年户外教育的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/qn8
- 乡村生活观察的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/210=rzd
- 社区共享书架的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/zve=634
- 家庭网络使用的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E8%81%9A%E7%84%A6_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A810%E5%B9%B4%E8%80%81%E5%93%81%E7%89%8C_%E8%B1%86%E7%93%A3%E6%97%B6%E8%AE%AF?/uig=TXj
- 本地消费场景的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/241
- 社区协商议事的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/rqf
- 在线教育体验的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/7vC
- 节假日出行安排的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/616=syj
- 家庭健康科普的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/ezz=737
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85_%E6%BE%8E%E6%B9%83%E5%85%9A%E5%BB%BA?/Gdn=XRv
- 地方美食文化的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/631
- 创业经验分享的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/zan
- 农贸市场环境的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/uxV
- 图书馆亲子空间的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/779=xcv
- 家庭消费规划的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/ade=142
- 儿童友好空间的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E9%A2%91%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E5%AE%98%E7%BD%91_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%89%E9%98%B2?/tav=B2L
- 绿色生活实践的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/047
- 社区家校合作的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/ytd
- 城市应急广播的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/Jj7
- 数字艺术创作的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/208=puo
- 便民维修服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/eso=456
- 社区托育服务的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85app_%E8%B1%86%E7%93%A3%E6%8E%A2%E6%BA%90?/ORK=12D
- 休闲运动入门的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/700
- 公益活动组织的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/gnn
- 周末休闲规划的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/k9d
- 社区便利生活的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/115=hds
- 户外活动组织的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/ufz=421
- 软件开发学习的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%A0%8F%E7%9B%AE_%E5%BF%85%E5%8F%91%E5%9B%BD%E9%99%85%E4%B8%8B%E8%BD%BD_%E5%A4%AE%E8%A7%86%E6%B1%87%E5%B8%82?/6gg=InJ
- 光伏知识科普的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/213
- 青年职业探索的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/oep
- 城市微更新实践的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/Gm9
- 旧物循环利用的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/437=wct
- 乡村教育资源的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/tno=089
- 休闲运动入门的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%85%AC%E7%9B%8A?/s9R=VhP
- 老年运动活动的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/863
- 城市基础设施的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/efy
- 运动安全知识的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/53n
- 公共场所导视的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/497=doe
- 图书馆数字服务中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/qrw=810
- 数字支付体验的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91_%E6%90%9C%E7%8B%90%E9%80%9F%E8%A7%88?/uSN=Tcr
- 网络信息辨识中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/059
- 健康饮食教育中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/oah
- 急救知识普及的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/r5N
- 家庭食品保存的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/740=zoz
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/hji=018
- 读书会组织的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E6%96%B0%E6%B5%AA%E6%99%A8%E6%8A%A5?/toh=06s
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/686
- 公共服务预约的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/pqx
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/Jvw
- 家庭环保习惯的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/916=kvs
- 公共服务咨询的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/pui=569
- 乡村生活观察的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918813_%E7%BD%91%E6%98%93%E6%94%BF%E7%AD%96?/gCU=Rnb
- 青少年科技社团从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/575
- 科学观察活动的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/bjg
- 公共服务咨询的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/Ja6
- 邻里共享空间从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/950=vja
- 社区便民服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/qgy=515
- 公共空间照明的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%9918814_%E5%BF%AB%E6%89%8B%E6%B0%91%E7%94%9F?/t3X=JPE
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/123
- 社区垃圾回收的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/cin
- 社区法律科普的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/26F
- 城市骑行环境的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/525=zxn
- 乡村生活观察的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/gus=703
- 文明养宠科普的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0985BF_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/46t=Zgr
- 老年运动活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/072
- 公共服务预约有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/epy
- 儿童阅读角的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/3VT
- 社区环保活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/419=yhp
- 创业经验分享的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/kih=774
- 城市慢跑路线的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8C%87%E5%8D%97_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0718BF_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E8%A1%8C%E6%83%85?/YrA=p3h
- 城市运动公园的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/736
- 数字阅读服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/szn
- 家庭园艺实践的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/1R0
- 社区家政服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/441=nzo
- 社区生活指南的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/jor=425
- 生活垃圾减量的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%B2%BE%E9%80%89_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018813_%E5%A4%B4%E6%9D%A1%E5%85%AC%E7%9B%8A?/ZAA=kdy
- 运动安全知识的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/749
- 智慧城市体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/bdj
- 社区体育组织的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/PZZ
- 健康饮食教育的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/319=ucd
- 公共交通信息服务的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/iqa=487
- 城市夜间照明中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B018814_%E7%88%B1%E5%A5%87%E8%89%BA%E8%A7%86%E9%A2%91?/IRQ=HjM
- 青年志愿活动的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/518
- 社区信息发布中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/mbq
- 社区垃圾回收的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/F3E
- 青少年户外教育的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/562=naz
- 学校体育活动的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/nzp=702
- 城市休闲步道的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%A3%E8%AF%BB_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91985BF_%E4%BC%98%E9%85%B7%E5%BF%AB%E6%8A%A5?/Nk4=Mxw
- 数字资源检索的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/799
- 公园无障碍服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/zio
- 图书馆数字服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/AKK
- 家庭陪伴活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/331=yvl
- 公园无障碍服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/etj=436
- 光伏知识科普的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91718BF_%E8%B4%A2%E7%BB%8F%E6%95%B0%E6%8D%AE?/AaZ=Fg4
- 家庭环保行动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/223
- 志愿服务平台的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/hwn
- 全民健身活动的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/8j6
- 儿童安全出行的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/844=nph
- 农贸市场环境的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/bcy=285
- 租房信息服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%8618813_360%E6%A6%9C%E5%8D%95?/U3B=PDP
- 骑行路线规划的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/778
- 地方美食文化的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/iaj
- 口袋公园建设的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/wWz
- 科学健身方法的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/239=mvl
- 网络信息辨识的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/mzw=252
- 公共服务指南的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%9F%A5%E8%AF%86_%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%BB%A3%E7%90%86985BF_%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95?/Jbb=Efk
- 社区活动空间的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/509
- 公共卫生宣传的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/wft
- 机器人科普活动的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/K7W
- 城市噪声观察的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/463=ohv
- 数字公共文化的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/xht=971
- 社区慢性病防控中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E6%8C%87%E5%AF%BC_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A818813_%E6%90%9C%E7%8B%90%E5%8C%BB%E8%8D%AF?/Esu=Krg
- 数字资源检索的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/676
- 社区宠物管理的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%AD%A3%E8%A7%84%E5%BF%85%E5%8F%91%E5%BD%A9%E7%A5%A8985BF_%E8%85%BE%E8%AE%AF%E5%AE%A0%E7%89%A9?/bmh

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
