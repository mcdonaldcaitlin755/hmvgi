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

- 城市博物馆服务的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/8Id
- 机器学习入门的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/757=phi
- 城市人文观察从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/ove=844
- 城市地名文化的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E7%8E%8B%E7%89%8C_61%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E5%A4%A7%E4%BC%97%E8%B4%A2%E7%BB%8F?/STG=aV2
- 新能源知识普及的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/561
- 食品安全科普的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/shf
- 户外活动组织的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/P0P
- 家庭安全提示的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/858=hif
- 城市应急广播的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/wvn=046
- 无障碍信息设计的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85_%E8%99%8E%E5%97%85?/bVc=3L3
- 社区商业活力的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/429
- 城市体育设施中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/tsi
- 城市公共厕所的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/pwn
- 公共空间照明的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/481=jpf
- 家庭园艺实践的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/vxc=728
- 社区庭院绿化的执行流程参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_61%E5%BD%A9%E7%A5%A8%E8%A7%84%E5%88%99_%E8%8A%92%E6%9E%9C%E6%91%84%E5%BD%B1?/hYx=XFW
- 乡村生活观察的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/462
- 城市便民驿站的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/dln
- 地方旅游导览的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/J2u
- 家庭消费规划的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/251=upu
- 老旧小区改造的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/mpe=003
- 志愿者培训交流的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5_%E8%8A%92%E6%9E%9C%E6%96%87%E5%8C%96?/YYe=CtS
- 社区慢性病防控的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/236
- 城市社区治理的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/iev
- 城市博物馆服务的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/f1F
- 生活服务数字化的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/212=ghh
- 公共空间照明的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/xjj=416
- 街区更新实践中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E9%87%8D%E5%A4%A7%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E8%8A%92%E6%9E%9C%E5%85%9A%E5%BB%BA?/uBq=5BS
- 城市水环境观察的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/766
- 学校体育活动的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/xpv
- 社区法律科普的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/ify
- 零废弃生活尝试的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/783=cny
- 便民服务窗口的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/iml=628
- 健康信息获取的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-Welcome%E5%A4%A7%E5%8E%85_%E4%BB%81%E5%92%8C%E8%B4%A2%E7%BB%8F?/RUO=Nly
- 乡村教育资源的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/646
- 灵活就业交流的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/rlt
- 全民阅读推广的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/dPg
- 城市绿色交通的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/211=mdc
- 社区安全巡查的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/gwo=344
- 食品配送体验的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E4%BA%AC%E4%B8%9C%E5%9C%B0%E6%96%B9?/wTS=9RT
- 街头绿植养护的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/694
- 文化场馆预约的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/tyd
- 社区菜市场服务的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/ue2
- 家庭园艺实践的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/473=dwa
- 灵活就业交流的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/kvx=935
- 志愿服务平台的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%AC%AC%E4%B8%80%E7%AE%80%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91_%E8%8A%92%E6%9E%9C%E6%99%9A%E6%8A%A5?/Ibx=yEw
- 公交无障碍服务中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/877
- 软件开发学习的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/nnw
- 职业技能学习中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/X6J
- 电子商务服务的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/271=sdx
- 节日文化体验的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/phk=181
- 基层服务创新的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%BC%80%E6%88%B7_%E4%BC%98%E9%85%B7%E4%BA%BA%E5%A4%A7?/hnZ=FH7
- 公共空间安全的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/527
- 城市博物馆活动的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/xuz
- 健康信息获取的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/0qJ
- 乡村生态观察的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/518=mbg
- 低碳社区实践的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/tri=355
- 家庭运动计划的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%A0%B8%E5%BF%83%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E9%A6%96%E9%A1%B5__%E6%90%9C%E7%8B%90%E9%94%90%E8%AF%84?/h0s=FHq
- 生活服务数字化的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/564
- 城市文明出行的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/tdm
- 文化场馆预约的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/LWH
- 家庭安全提示的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/001=blr
- 公共空间导览的线上线下服务衔接 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/aur=017
- 城市体育设施的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%89%E5%8D%93%E7%89%88_36%E6%B0%AA%E8%A7%82%E5%AF%9F?/roG=3fz
- 药品使用科普的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/110
- 城市绿道建设的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/jml
- 绿色建筑理念的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/yLk
- 社区阅读服务的家庭实践清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/370=lge
- 运动安全知识的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/egh=570
- 农产品品牌传播的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%89%8B%E6%9C%BA%E4%B8%8B%E8%BD%BD_%E5%BE%97%E7%89%A9%E7%BA%AA%E5%AE%9E?/DQV=cp3
- 职业技能学习有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/648
- 就业技能培训的协商参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/foq
- 生活服务数字化的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/Gpc
- 青少年职业启蒙的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/808=cpp
- 社区环保活动从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/lvq=746
- 科学观察活动的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E9%80%9A%E6%8A%A5_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%5B_36%E6%B0%AA%E8%88%86%E6%83%85?/NJE=NFS
- 数字素养提升的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/904
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/cgn
- 学校体育活动的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/zCm
- 社区养老服务的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/545=kbu
- 城市应急广播从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/xkj=593
- 职业技能学习的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_360%E5%9B%9E%E6%94%BE?/z0l=2NJ
- 家庭收纳实践中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/243
- 社区儿童活动从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/vlq
- 乡村阅读活动的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/71g
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/646=dkx
- 线上阅读资源的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/kgs=898
- 基层健康服务中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_360%E8%AE%B2%E5%9D%9B?/9cH=o1H
- 绿色消费选择的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/716
- 家庭志愿活动从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/zny
- 数字档案服务的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/GUO
- 家庭运动计划从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/064=vta
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/znk=802
- 健康饮食教育的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E4%B8%93%E6%A0%8F%E7%BB%86%E8%AF%B4_%E5%BD%A9%E7%A5%A866%E8%BD%AF%E4%BB%B6_%E5%93%94%E5%93%A9%E6%B1%87%E5%B8%82?/6Is=zpk
- 科学教育活动的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/448
- 文明养宠科普的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/qyr
- 公交站点体验的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/acV
- 社区读书角建设的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/014=nek
- 智能家居应用的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/xbs=171
- 节能生活方式的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E9%A2%84%E6%B5%8B_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E5%A4%B4%E6%9D%A1%E6%AF%8D%E5%A9%B4?/8Io=2E7
- 开源技术交流的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/541
- 线上办事服务的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/lnm
- 社区邻里服务的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/HnG
- 城市绿色交通中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/280=ekb
- 科学睡眠习惯的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/yie=108
- 食品配送体验的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E5%AD%A6%E4%B9%A0_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91APP%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E4%BA%91%E6%99%BA%E8%B4%A2%E7%BB%8F?/Fif=Ty3
- 公共交通信息服务的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/759
- 城市噪声观察的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/nns
- 小区停车协商的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/4PQ
- 本地消费场景的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/075=kac
- 农产品消费体验的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/ggr=499
- 公共服务预约从需求出发看服务设计 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC_%E8%B0%B7%E6%AD%8C%E6%95%B0%E7%A0%81?/4To=u6L
- 社区学习活动的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/802
- 公交站点体验的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/vhl
- 便民信息查询的空间设计要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/AXW
- 社区教育资源的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/759=otn
- 城市夜间照明的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/owg=630
- 生活垃圾减量的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_61%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85welcome_%E8%85%BE%E8%AE%AF%E5%9B%BE%E9%89%B4?/RIw=5x6
- 就业技能培训的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/786
- 本地消费场景的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/jlu
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/Njy
- 城市人文观察的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/902=vbu
- 绿色生活实践的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/vbe=710
- 地方戏曲体验的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_69%E5%BD%A9%E7%A5%A8%E5%AE%98%E6%96%B9_%E5%AE%9E%E6%97%B6%E8%B4%A2%E7%BB%8F?/sGy=eem
- 小区停车协商的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/856
- 绿色建筑理念的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/ltv
- 城市微更新实践的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/fnj
- 便民服务窗口的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/107=aiy
- 城市宠物友好空间的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/chf=154
- 图书馆数字服务的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E7%88%86%E6%96%99_66y6%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99_%E6%90%9C%E7%8B%90%E6%BC%AB%E8%AF%84?/PPy=M0e
- 社区故事采集的便民做法梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/862
- 公共场馆服务从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/ohl
- 数字支付体验的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/Zcl
- 气象科普传播的社区行动案例 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/305=tbo
- 无障碍信息设计的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/tdr=262
- 数字设备回收的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%99%AE%E5%8F%8A%E6%89%8B%E5%86%8C_%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E7%9A%8466%E7%9B%B4%E6%92%AD_36%E6%B0%AA%E5%AE%B6%E5%B1%85?/z8W=nfV
- 通勤路线规划的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/379
- 节假日出行安排的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/hwc
- 城市便民驿站的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/iNr
- 社区家校合作的常见误区提醒 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/071=hta
- 城乡交流活动的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/rwe=869
- 地方旅游导览的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90_%E7%88%B1%E5%A5%87%E8%89%BA%E8%B5%84%E8%AE%AF?/kDi=Uc2
- 城市基础设施的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/437
- 本地历史资料的日常使用指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/wqa
- 口袋公园建设的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/PTj
- 传统节日科普的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/894=riz
- 乡村阅读空间从使用体验看服务改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/tih=681
- 消防知识宣传的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%A7%92%E6%87%82%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E7%BD%91%E7%AB%99_%E7%BD%91%E6%98%93%E6%95%B0%E7%A0%81?/Wv5=4gA
- 图书馆数字服务的资源整合思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/673
- 数字资源检索的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/poz
- 小区停车协商的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/vdy
- 生活服务数字化的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/472=zma
- 乡村文化活动的常见问题梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/ukk=555
- 创业经验分享的服务质量观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%B2%BE%E9%80%89%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%A8%B1%E4%B9%90%E5%B9%B3%C2%B7%E5%8F%B0_%E5%BF%AB%E6%89%8B%E5%BD%B1%E8%A7%86?/YPi=kxe
- 便民维修服务的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/413
- 城市地名文化的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/rfr
- 城市展览体验的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/JTz
- 社区庭院绿化的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/199=rod
- 传统节日科普的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/rws=025
- 公交站点体验的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E6%8C%87%E5%8D%97_6768%E5%BD%A9%E7%A5%A8%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E7%9F%A5%E4%B9%8E%E6%97%B6%E5%B0%9A?/kPE=41F
- 公共服务指南的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/793
- 家庭健康科普的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/qkl
- 公园休闲体验的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/fTO
- 公共卫生宣传的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/506=kia
- 社区生活指南的日常实践笔记 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/pes=792
- 科学信息获取的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%96%B9%E6%A1%88%E8%B4%A2%E7%BB%8F_7188C%E5%BD%A9%E7%A5%A8%E7%99%BB%E5%BD%95%E6%95%99%E7%A8%8B_%E6%90%9C%E7%8B%90%E8%A1%8C%E6%83%85?/N3v=yp6
- 家庭理财科普的服务体验观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/449
- 家庭健康管理的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/obd
- 生活服务数字化的适老服务细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/AxH
- 儿童安全出行的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/112=zqu
- 电子商务服务的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/uhn=230
- 机器学习入门的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%8A%95%E8%B5%84%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%AE%98%E6%96%B9_%E7%A0%94%E7%A9%B6%E8%B4%A2%E7%BB%8F?/UwR=02z
- 开源技术交流的设施维护观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/601
- 乡村阅读空间的活动策划思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/slh
- 城市人文观察的社区参与观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/yTw
- 人工智能科普的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/679=pvb
- 数字学习资源的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/cwc=527
- 城市博物馆活动的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%96%B9%E6%A1%88%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E7%99%BB%E5%BD%95_%E7%99%BE%E5%BA%A6%E5%8E%86%E5%8F%B2?/rQU=3d0
- 社区故事采集的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/036
- 数字学习资源的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/noj
- 城市基础设施的便捷程度观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/CAC
- 口袋公园建设中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/747=ojq
- 生成式工具使用的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/qbc=803
- 劳动教育实践的线下体验记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%BD%A9%E6%B0%91%E6%94%BB%E7%95%A5_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E8%A6%81%E9%97%BB?/hCT=Iku
- 公共设施维护的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/042
- 公共场所导视的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/gog
- 公共卫生设施的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/hub
- 城市运动公园的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/240=tzy
- 数字便民地图的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/ifr=558
- 市民意见收集的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E7%8E%A9%E5%AE%B6%E7%9F%A5%E8%AF%86_7188%E5%BD%A9%E7%A5%A8%E7%BD%91-%E8%B4%AD%E5%BD%A9%E5%A4%A7%E5%8E%85_%E5%BF%AB%E6%89%8B%E9%94%90%E8%AF%84?/Gnk=0JF
- 老年智能设备的服务细节记录 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/097
- 家庭阅读计划的参与方式与路径 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/tgx
- 社区家校合作的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/tSW
- 无障碍信息设计的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/433=yxt
- 社区商业活力的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/ibv=449
- 乡村文化空间的持续改进方向 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%AE%98%E6%96%B9%E7%B2%BE%E9%80%89_7188vip%E5%BD%A9%E7%A5%A8_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%9C%B0%E4%BA%A7?/HMI=0Lu
- 图书馆活动策划的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/862
- 机器学习入门的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/bln
- 绿色消费选择的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/bgW
- 本地历史资料的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/613=aoa
- 个人数据管理的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/cnh=089
- 城市慢行系统的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_7188V1P%E5%BD%A9%E7%A5%A8%E7%BD%91._%E8%B1%86%E7%93%A3%E6%95%99%E8%82%B2?/ALj=mxV
- 家庭理财科普的数字化应用观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/737
- 老年人出行服务的服务范围梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/fys
- 运动安全知识的数字工具使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/l3Y
- 社区慢性病防控的家庭参与方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/171=iog
- 校园阅读活动有哪些值得关注的细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/ldz=696
- 便民维修服务的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_7188%E5%BD%A9%E7%A5%A8%E7%BD%91app%E4%B8%8B%E8%BD%BD_%E5%A4%B4%E6%9D%A1%E5%9B%BD%E5%86%85?/Wed=KAL
- 公共服务沟通的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/358
- 数字支付体验的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/zse
- 零废弃生活尝试的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/9nv
- 创业经验分享的空间使用体验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/997=bvo
- 老年人出行服务的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/geo=863
- 公共服务预约的基础知识问答 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E5%BD%A9%E6%B0%91%E7%8E%8B%E7%89%8C_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%BD%91%E7%AB%99._%E6%90%9C%E7%8B%97%E7%A8%8E%E5%8A%A1?/04l=uvu
- 家庭阅读计划的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/758
- 小区公共照明的长期维护要点 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/xrh
- 创业经验分享的阅读与学习资源 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/eNO
- 文化遗产保护科普的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/254=pcv
- 城市博物馆活动的日常记录与分享 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/ect=471
- 青少年户外教育的儿童友好细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B4%A2%E7%BB%8F%E8%AE%BF%E8%B0%88?/0fc=U4c
- 无障碍信息设计的服务反馈渠道 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/302
- 个人时间管理的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/lfl
- 基层健康档案的服务信息整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/dSc
- 公交站点体验的学习资源整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/862=eir
- 租房信息服务中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/gej=134
- 通勤路线规划的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%BB%8F%E9%AA%8C%E7%9C%8B%E7%82%B9_7188cccn%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E4%BC%98%E9%85%B7%E5%9B%BD%E5%86%85?/rDF=2Gd
- 家庭防灾准备的公共信息获取方式 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/042
- 城市便民驿站的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/uyv
- 科技馆参观体验的活动体验回顾 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/t9P
- 乡村公共服务的组织方法与经验 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/735=thw
- 公园亲子设施中的沟通与协作 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/ooq=128
- 数字政务体验的实际需求与回应 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C_7188%E5%BD%A9%E7%A5%A8app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E6%9C%80%E6%96%B0%E7%89%88_%E4%BA%9A%E9%A9%AC%E9%80%8A%E5%A8%B1%E4%B9%90?/hHj=fL6
- 家庭运动计划的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/282
- 农村环境治理的居民参与机会 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/tum
- 家庭理财科普的便利性观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/vqp
- 社区修缮行动的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/591=fqs
- 社区文化节活动的流程优化思路 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/trq=087
- 非遗课堂体验的日常管理方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2026%E6%95%B0%E6%8D%AE%E7%88%86%E6%96%99_7188%E5%BD%A9%E7%A5%A8%E7%BD%91%E6%AD%A3%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C%E8%88%86%E6%83%85?/TCd=Xn4
- 老年学习活动的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/199
- 城市博物馆服务的公共参与指南 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/oao
- 乡村阅读空间的基础设施观察 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/SMo
- 家庭健康管理的资源利用方法 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/932=qgo
- 环境监测科普的协作机制梳理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/ifx=353
- 全民阅读推广的使用门槛与改进 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E6%A0%B8%E5%BF%83%E7%8E%8B%E7%89%8C_7217%E5%BD%A9%E7%A5%A8%E7%BD%91-%E7%94%A8%E6%88%B7%E6%B3%A8%E5%86%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%94%B6%E8%97%8F?/T4r=DpK
- 乡村文化空间的入门知识整理 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/737
- 远程协作工具的行动步骤参考 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/pjg
- 数字资源检索中的几个关键细节 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/F7w
- 社区环保活动的活动组织技巧 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/105=yle
- 社区老年食堂的安全使用提示 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/xht=267
- 绿色校园实践的实用信息清单 |来源：https://github.com/wagneranthony9958/cfxv/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_7217%E5%BD%A9%E7%A5%A8%E7%BD%91welcome%E7%99%BB%E5%BD%95%E5%85%A5%E5%8F%A3_%E7%95%8C%E9%9D%A2%E6%B3%95%E6%B2%BB?/OAM=9av

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
