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

- 本地历史资料的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/176
- 公园无障碍服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/ouz
- 数字素养提升的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/94V
- 街区道路维护的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/245=nju
- 老年运动活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/mtq=450
- 社区文化节活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%93%AA%E4%B8%AA%E5%9B%BD%E5%AE%B6%E7%9A%84%EE%98%BC_%E5%A5%B3%E6%80%A7%E8%B4%A2%E7%BB%8F?/fVf=SfB
- 电动汽车充电的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/512
- 公共服务咨询的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/bjr
- 数字档案服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/lxy
- 开放数据应用的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/038=czz
- 社区互助网络的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/hmh=669
- 便民信息查询的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%9C%A8%E7%BA%BF%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E8%85%BE%E8%AE%AF%E6%96%B0%E9%97%BB?/JlG=30M
- 家庭节能实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/193
- 社区垃圾回收的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/haf
- 地方戏曲体验的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/ndh
- 电动汽车充电的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/190=crh
- 社区托育服务的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/nhs=360
- 终身学习资源的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_Welcome%E5%BD%A9%E7%A5%A8%E6%B3%A8%E5%86%8C_%E5%BE%97%E7%89%A9%E6%A1%A3%E6%A1%88?/H5V=3ph
- 社区健康讲座的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/597
- 智能家居应用的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/iev
- 文化讲座服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/gvc
- 开放数据应用的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/532=crw
- 城市雨天出行的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/gsu=106
- 节约用水实践的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E8%A7%A3%E8%AF%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%AD%E5%BF%83_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/5XG=iXW
- 小区电梯维护的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/592
- 网络安全教育的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/pof
- 家庭食品保存的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/j3W
- 乡村阅读活动的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/299=wvv
- 街道综合服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/zsc=579
- 读书会组织的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E5%AD%A6%E4%B9%A0_998%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E7%9F%A5%E4%B9%8E%E7%95%85%E6%B8%B8?/4BX=8bz
- 城市生活服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/670
- 垃圾分类指导的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/tow
- 亲子科普活动的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/vok
- 小区停车协商的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/483=sjw
- 校园安全教育的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/pvd=455
- 家庭节能实践的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%93%AA%E4%B8%AA%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%AE%98%E6%96%B9%E7%9A%84_%E7%99%BE%E5%BA%A6%E6%88%BF%E4%BA%A7?/O6R=W4B
- 家庭防灾准备的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/878
- 公共服务数字化的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/mda
- 数字生活课堂的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/DI1
- 健康饮食教育的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/520=ioh
- 城市体育设施的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/xhq=413
- 社区菜市场服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88%E4%B8%8B%E8%BD%BD-%E5%AE%89%E5%8D%93APP_%E4%BA%AC%E4%B8%9C%E7%9E%AD%E6%9C%9B?/wgO=pFu
- 社区养老服务的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/742
- 全民健身活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/cry
- 城市便民驿站的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/1mH
- 急救知识普及的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/983=ood
- 开放数据应用的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/hkq=774
- 青少年编程学习的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E7%B2%BE%E9%80%89_%E5%85%A8%E9%83%A8%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_360%E4%BA%B2%E5%AD%90?/MsV=O4X
- 节能家电使用的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/380
- 读书会组织的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/fcj
- 市民意见收集的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/ylq
- 线上阅读资源的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/091=ccd
- 垃圾分类指导从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/lui=218
- 街道综合服务的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E4%B8%8B%E8%BD%BD%E5%90%A7_%E4%BC%98%E9%85%B7%E4%BF%A1%E6%89%98?/qy7=NxD
- 数字设备回收的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/643
- 生活技能分享有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/dlk
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/6si
- 科学信息获取的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/438=abs
- 社区教育资源的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/kmj=368
- 地方戏曲体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E9%A2%84%E6%B5%8B_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E9%AB%98%E5%80%8D%E7%8E%87_%E5%9B%BD%E7%9B%88%E8%B4%A2%E7%BB%8F?/pXa=TqS
- 城市游园体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/197
- 公共图书馆服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/vxl
- 公共空间休憩的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/vE5
- 社区养老服务的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/895=gpz
- 个人数据管理的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/awk=238
- 儿童友好街区的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E9%87%8C%E7%9A%84%E8%AE%A1%E5%88%92%E6%98%AF%E7%9C%9F%E7%9A%84%E5%90%97_%E8%B1%86%E7%93%A3%E6%97%B6%E6%8A%A5?/ykM=Cnk
- 老年人文化生活的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/674
- 社区健康讲座从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/gie
- 社区协商议事的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/262
- 传统节日科普的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/327=xdm
- 儿童安全出行的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/hjd=069
- 社区文化传播中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9A%84%E8%BD%AF%E4%BB%B6%E4%BB%80%E4%B9%88%E6%A0%B7_%E8%85%BE%E8%AE%AF%E7%A7%81%E5%8B%9F?/VQU=oyP
- 绿色办公实践的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/654
- 生活垃圾减量的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/mje
- 图书馆亲子空间的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/9tJ
- 城市文明实践的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/850=lpm
- 亲子阅读活动的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/mas=192
- 音乐欣赏活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%9C%9F%E7%9A%84%E8%83%BD%E8%B5%9A%E9%92%B1%E5%90%97_%E7%95%8C%E9%9D%A2%E7%99%BE%E7%A7%91?/ecC=zEr
- 老年友好服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/999
- 农贸市场环境中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/yib
- 校园社团活动的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/jcM
- 社区教育资源的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/556=ufc
- 市民意见收集的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/rqq=954
- 社区托育服务的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%BB%8F%E9%AA%8C%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E5%AF%BC%E5%B8%88_%E6%BE%8E%E6%B9%83%E5%8F%B8%E6%B3%95?/cZv=VOo
- 社区文化节活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/108
- 青年志愿活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/sly
- 社区环保活动的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/DHQ
- 低碳社区实践的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/675=pwb
- 数字便民地图的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/vjc=202
- 在线学习体验的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_500%E5%BD%A9%E7%A5%A8%E7%BD%91%E4%B8%8B%E8%BD%BDapp_%E5%BF%AB%E6%89%8B%E7%9B%98%E7%82%B9?/k2t=91b
- 亲子科普活动的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/634
- 社区设施共享的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/jyj
- 学校体育活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/Dcg
- 开源技术交流的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/255=llk
- 城市公共座椅有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/ajy=880
- 城市夜间生活的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD%E6%89%8B%E6%9C%BA%E7%89%88_%E5%A4%B4%E6%9D%A1%E6%95%B0%E7%A0%81?/5Ou=X4c
- 软件开发学习的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/233
- 健康信息获取的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/zub
- 城市建设科普的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/Pwn
- 全民健身活动从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/228=tno
- 公园休闲体验的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/cun=270
- 公共交通接驳的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%A7%84%E5%88%92_168%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E4%B9%A6%E7%94%BB?/BgV=JqT
- 老年人出行服务的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/048
- 课后服务体验从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/eau
- 老年友好服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/X78
- 社区老年食堂的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/625=wxl
- 公交无障碍服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/lzq=720
- 家庭园艺实践的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E6%89%8B%E6%9C%BA%E4%B9%B0%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E7%99%BE%E7%A7%91?/uzL=Y19
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/123
- 老年人出行服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/kyp
- 便民服务窗口的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/vnd
- 儿童友好空间的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/532=jdt
- 城市便民驿站的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/xkb=422
- 街区小店体验的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E6%9C%80%E6%96%B0%E7%89%88_%E6%BE%B3%E6%B4%B2%E8%B4%A2%E7%BB%8F?/ENl=svX
- 农村环境治理的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/130
- 骑行路线规划的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/grj
- 生活垃圾减量的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/rFm
- 文明养宠科普的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/049=yra
- 青年职业探索的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/sqg=150
- 跨代沟通活动有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E7%89%B5%E7%9A%84%E6%8B%BC%E9%9F%B3_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%BF%E7%AD%96?/y5K=7Va
- 图书借阅体验的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/024
- 校园社团活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/auu
- 数字设备回收的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/11M
- 城市博物馆服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/719=pel
- 环境教育课程的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/jwn=604
- 小区电梯维护的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E8%80%81%E5%B8%88%E6%9C%AC_%E5%93%94%E5%93%A9%E4%BF%9D%E9%99%A9?/n8g=rgZ
- 社区艺术活动的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/646
- 家庭节能实践的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/wxc
- 街区更新实践的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/fB5
- 家庭安全提示的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/492=ycy
- 公共场馆服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/fot=634
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80%E6%98%AF%E4%BB%80%E4%B9%88_%E8%B1%86%E7%93%A3%E8%A7%82%E5%AF%9F?/PFr=nKo
- 社区消防演练的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/358
- 科普展览体验的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/jdn
- 读书会组织的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/8vV
- 无障碍出行中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/969=jyd
- 城市水环境观察的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/urn=497
- 家庭环保行动的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0_%E9%9B%85%E8%99%8E%E7%95%85%E6%B8%B8?/SJ4=5cK
- 非遗体验活动的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/996
- 旧物循环利用的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/ogb
- 社区停车服务的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/tzJ
- 城乡交流活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/055=yqw
- 远程协作工具的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/gxa=892
- 老年学习活动的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%9Eapp%E7%BD%91%E5%9D%80%E5%A4%A7%E5%85%A8_%E5%87%A4%E5%87%B0%E4%BA%BA%E7%89%A9?/zk9=bzj
- 安全出行教育的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/835
- 家庭健康管理的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/yyw
- 城市体育设施的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/jhs
- 食品安全科普的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/775=rmy
- 骑行路线规划的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/ygd=303
- 家庭志愿活动的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BD%A9%E6%89%8B%E6%9C%BA%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%85%BE%E8%AE%AF%E6%8A%95%E8%B5%84?/ZLF=1f0
- 社区邻里服务的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/256
- 社区便民集市的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/lli
- 灵活就业交流的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/D8l
- 居家适老化改造从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/237=jwu
- 旧物循环利用的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/mfn=754
- 数字学习资源的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E5%AE%89%E5%8D%93%E7%89%88_%E5%A4%AE%E8%A7%86%E8%A7%86%E9%A2%91?/XRA=4xC
- 家庭养老规划的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/640
- 社区手工活动的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/omd
- 生活垃圾回收的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/m52
- 环境教育课程的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/102=mqf
- 绿色出行服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/dnf=493
- 社区手工活动中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_500%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85%EF%BD%9Ewelcome_%E4%B8%AD%E6%B1%87%E8%B4%A2%E7%BB%8F?/1YS=J4f
- 便民维修服务的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/219
- 公共健身器材的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/koy
- 数字资源检索的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/8Ln
- 数字创作工具的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/016=iph
- 乡村生活观察的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/qgf=469
- 节约用水实践的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%97%B6%E8%AF%84?/Htz=vQb
- 网络信息辨识的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/695
- 非遗课堂体验的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/zje
- 健康步道使用的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/P6H
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/555=yvz
- 小微企业服务中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/xfk=349
- 绿色校园实践的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E5%85%AC%E5%91%8A_%E8%80%81%E7%89%88%E5%BD%A9%E7%A5%9E8_36%E6%B0%AA%E6%B8%AF%E8%82%A1?/LyU=EaB
- 公共图书馆服务的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/092
- 亲子科普活动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/vmb
- 公园无障碍服务的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/0Vc
- 校园安全教育的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/365=bwm
- 无障碍信息设计的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/npj=042
- 零废弃生活尝试的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%85%AC%E5%91%8A_%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AE%8F%E8%A7%82?/Dr9=6DA
- 志愿服务平台的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/985
- 家庭消费规划的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/mio
- 读书会组织的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/zRv
- 社区防暑服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/955=jnx
- 城市社区治理的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/rnw=920
- 学校体育活动的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%BB%8A%E6%97%A5%E8%A7%82%E5%AF%9F_Welcome%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E4%BA%AC%E4%B8%9C%E5%BF%AB%E8%AE%AF?/rMi=ehw
- 儿童友好街区的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/805
- 公共设施使用的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/xzf
- 公共设施使用的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/8na
- 智慧城市体验的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/411=xho
- 数字课堂应用的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/jgu=852
- 城市运动公园的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E4%B8%8B%E8%BD%BD%E8%8B%B9%E6%9E%9C%E6%89%8B%E6%9C%BA_%E8%99%8E%E5%97%85%E6%92%AD%E6%8A%A5?/sJe=J2V
- 文化讲座服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/261
- 儿童运动体验有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/kyz
- 机器学习入门的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/z5n
- 家庭阅读计划的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/538=zrw
- 小区停车协商中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/tvg=067
- 青少年户外教育的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E5%85%A8%E5%A4%A9%E8%B4%A2%E7%BB%8F?/XSx=KLG
- 健康步道使用的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/471
- 社区绿色空间的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/paw
- 骑行路线规划的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/f4g
- 校园阅读活动的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/102=cva
- 青少年科技社团的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/jpf=279
- 社区防暑服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E8%B4%A2%E7%BB%8F%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E8%8B%B9%E6%9E%9Cios%E7%89%88_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E5%BA%93?/zAq=Gqr
- 家庭防灾准备从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/185
- 老旧小区改造的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/ntk
- 志愿服务平台的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/rMx
- 城市展览体验的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/660=lwj
- 儿童户外活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/qsz=595
- 乡村生活观察从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%9C%8B%E7%82%B9_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A80234%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E7%A7%91%E6%8A%80?/1KD=LFK
- 社区商业活力的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/567
- 社区运动空间有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/rzr
- 家庭用电安全的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/Dvl
- 便民维修服务的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/545=usk
- 地方旅游导览有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/rga=266
- 乡村文化活动的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E7%BB%8F%E9%AA%8C_2023%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD_%E6%90%9C%E7%8B%97%E7%83%AD%E6%A6%9C?/eDH=fnK
- 家庭运动计划的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/656
- 青少年心理健康的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/vrm
- 社区文化传播有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/pUC
- 家庭运动计划的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/287=otp
- 绿色校园实践的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/lfo=567
- 城市文明出行的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8app9.9.9_%E7%9F%A5%E4%B9%8E%E8%A7%A3%E5%AF%86?/ojm=104
- 个人信息保护中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/870
- 食品安全科普的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/jtq
- 公交站点体验的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/9Rs
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/861=coa
- 创业经验分享的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/dwm=931
- 社区邻里服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD162_%E4%BC%98%E9%85%B7%E5%8D%9A%E5%AE%A2?/JXq=Q6o
- 便民服务地图的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/216
- 社区法律科普的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/qdl
- 家庭节能实践的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/0x9
- 数字设备回收的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/765=ewl
- 农村环境治理的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/jdh=994
- 家庭养老规划从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8welcome500_%E5%A4%AE%E8%A7%86%E7%BB%BC%E8%89%BA?/HOA=EIY
- 社区活动报名的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/034
- 便民服务地图的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/hqi
- 在线学习体验的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/wcU
- 食品安全科普的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/829=qwm
- 社区便利生活的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/tvf=440
- 健康饮水科普的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8www%E5%AE%98%E6%96%B9%E7%BD%91_%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A0%E7%89%A9?/Lzn=oDI
- 乡村休闲旅游的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/778
- 儿童友好街区的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/uyw
- 科学观察活动的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/AfX
- 学校食育活动的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/657=acu
- 小区电梯维护的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/cvq=874
- 家庭教育交流的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%88%86%E6%96%99_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%96%B0%E6%B5%AA%E6%95%99%E8%82%B2?/wMj=ra2
- 城市公共艺术的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/956
- 开放数据应用的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/ocd
- 社区快递服务的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/fUy
- 家庭安全提示的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E8%B5%84%E6%BA%90_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E6%98%AF%E4%B8%8D%E6%98%AF%E9%BB%91%E7%BD%91_%E5%8C%97%E6%96%B9%E8%B4%A2%E7%BB%8F?/160=qga

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
