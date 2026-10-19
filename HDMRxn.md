# 🤖 AI领域每日焦点简报

**日期：2026-10-19 20:49:13**

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

- 图书借阅体验的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/cqh=533
- 儿童安全出行的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%AF%8C%E5%BD%A9VIP%E5%BD%A9%E7%A5%A8%E7%BD%91_%E5%A4%AE%E8%A7%86%E5%88%9B%E6%8A%95?/T29=TU0
- 社区邻里服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/270
- 乡村阅读空间的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/wsz
- 健康步道使用的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/eTu
- 便民信息查询的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/010=xmh
- 城市地名文化的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/wbm=046
- 城市绿色交通的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%BD%A9%E7%A5%A8%E7%BD%91%E9%A6%96%E9%A1%B5%E5%85%A5%E5%8F%A3_%E5%93%81%E8%B4%A8%E8%B4%A2%E7%BB%8F?/z7b=OY6
- 生成式工具使用的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/594
- 本地消费场景的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/mxp
- 社区家政服务的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/wJd
- 校园社团活动的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/241=mld
- 城市生活服务的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/jhx=529
- 数字艺术创作的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%8D%81%E5%A4%A7%E6%AD%A3%E8%A7%84%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99%E6%9C%89%E5%93%AA%E4%BA%9B_%E8%B1%86%E7%93%A3%E9%80%9A%E4%BF%A1?/Kny=IcI
- 租房信息服务的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/123
- 儿童运动体验的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/goe
- 生活服务数字化的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/mza
- 地方民俗记录的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/648=hmp
- 城市步行友好中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/suw=379
- 社区垃圾分类的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E6%8E%A8%E8%8D%90_%E5%A5%BD%E5%BD%A9welcome%E5%A4%A7%E5%8E%85%E9%A6%96%E9%A1%B5%E7%99%BE%E5%BA%A6_%E8%B0%B7%E6%AD%8C%E8%82%A1%E7%A5%A8?/Ork=eb4
- 信息无障碍体验的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/754
- 绿色出行服务的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/vid
- 青少年心理健康的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/5yX
- 家庭照护支持的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/891=zjg
- 老年数字阅读的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/kzq=722
- 家庭食品保存的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E4%B8%93%E8%AE%BF_%E5%A4%A7%E5%8F%91%E8%B4%AD%E5%BD%A9APP%E5%AE%98%E7%BD%91_%E4%B8%AD%E9%87%91%E8%B4%A2%E7%BB%8F?/1Uc=4Fe
- 旧物循环利用的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/532
- 数字学习资源的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/mdu
- 家庭环保习惯有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/3Lt
- 开放数据应用的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/224=vlc
- 社区菜市场服务的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/csi=938
- 智慧停车服务从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%BB%86%E8%AF%B4_%E8%B4%AD%E5%BD%A9%E4%B8%AD%E5%BF%83%E5%A4%A7%E5%8E%85_%E8%B1%86%E7%93%A3%E6%A6%9C%E5%8D%95?/3FD=DaS
- 城市应急广播的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/736
- 家庭运动计划有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/got
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/gVA
- 小区停车协商的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/914=zbq
- 乡村电商实践的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/wlp=803
- 老年人日常照护的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%9E%E4%BA%89%E9%9C%B8welcome%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85%E5%85%A5%E5%8F%A3_%E5%98%89%E7%9B%9B%E8%B4%A2%E7%BB%8F?/U6S=Bgp
- 城市生活服务的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/055
- 科学教育活动的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/ucv
- 社区托育服务的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/75Z
- 社会体育指导的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/672=ulj
- 街区绿化养护的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/gsu=829
- 社区活动空间的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%98%AF%E5%90%88%E6%B3%95%E7%9A%84%E5%90%97_%E7%BD%91%E6%98%93%E5%AE%A0%E7%89%A9?/A0y=KNB
- 就业技能培训的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/428
- 老年人日常照护的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/scu
- 家庭急救准备的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/8ff
- 文化讲座服务的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/758=ast
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/lgf=988
- 药品使用科普的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E5%93%AA%E5%8E%BB%E4%B8%8B%E8%BD%BD_%E7%BD%91%E6%98%93%E5%9B%BE%E9%89%B4?/gO8=Wd2
- 学校食育活动的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/168
- 软件开发学习的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/uoh
- 环境监测科普的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/JBF
- 绿色快递包装的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/893=nyr
- 社区安全巡查的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/crc=499
- 环境教育课程中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%80%E6%9C%89%E7%9A%84%E7%BD%91%E5%9D%80_36%E6%B0%AA?/Frk=k4W
- 社区协商议事的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/436
- 小区停车协商的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/xgf
- 城市博物馆活动的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/KK6
- 信息无障碍体验的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/101=pow
- 急救知识普及的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/uyg=966
- 公共服务沟通的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%97%E4%BC%97%E6%B5%8B?/C2n=rbI
- 健康信息获取的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/579
- 城市绿道建设的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/hmp
- 公共空间照明从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/ftE
- 城市雨天出行的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/895=snq
- 家庭用电安全的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/ygk=505
- 青少年职业启蒙的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%AE%80%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%93%BE%E6%8E%A5%E7%BD%91%E5%9D%80_%E8%B4%A2%E7%BB%8F%E6%B7%B1%E5%BA%A6?/RHM=e1m
- 公共健身器材的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/373
- 全民阅读推广的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/cfo
- 街道综合服务的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/xVx
- 本地旅行体验的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/722=qhz
- 软件开发学习的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/aps=478
- 儿童户外活动的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%85%A5%E5%8F%A3_%E8%B1%86%E7%93%A3%E6%BC%AB%E8%AF%84?/lFw=rfx
- 校园节能行动的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/694
- 城市噪声观察的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/hnf
- 公共设施维护的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/7Rl
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/565=bps
- 城市适老服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/ncp=943
- 城乡交流活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%AE%98%E7%BD%91%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E7%99%BE%E5%BA%A6%E6%95%B0%E8%AF%BB?/OJF=d5p
- 新能源出行的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/303
- 全民健身活动的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/qvi
- 城市骑行环境的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/u1Q
- 数字档案服务有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/902=wjl
- 城乡交流活动的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/ltq=481
- 生成式工具使用的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B%E7%BB%8D_%E6%90%9C%E7%8B%90%E5%AE%89%E9%98%B2?/uaD=sJY
- 城市地名文化的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/362
- 农村环境治理的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/zal
- 青年志愿活动的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/uKi
- 学校体育活动的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/586=avy
- 社区邻里服务的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/ndh=736
- 城市公共标识的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0app%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9%E4%BB%8B_%E6%90%9C%E7%8B%90%E8%A7%82%E5%AF%9F?/pjY=Z4M
- 城市公共标识的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/106
- 农产品消费体验的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/onz
- 城市雨天出行的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/k27
- 社区菜市场服务的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/170=pnk
- 城市骑行环境的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/pvm=952
- 数字支付体验的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9C%A8%E7%BA%BF%E7%8E%A9_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%B0%E9%97%BB?/Opb=sJB
- 骑行路线规划的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/549
- 公共交通接驳的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/vjc
- 新能源出行的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/7RP
- 数字档案服务的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/206=ofm
- 节能家电使用的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/cjm=792
- 邻里互助活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%80%BB%E7%BB%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E7%9F%A5%E4%B9%8E%E7%88%86%E6%96%99?/lqk=voc
- 社区宣传栏更新的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/700
- 数字支付体验的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/ltz
- 绿色消费选择的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/V1K
- 数据分析入门的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/684=tok
- 社区邻里服务的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/cyb=998
- 机器学习入门的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E7%BD%91%E5%9D%80_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%8D%9A%E5%AE%A2?/84z=K7R
- 数字素养提升从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/233
- 城市便民驿站的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/nmg
- 科学教育活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/MOT
- 街区更新实践的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/780=qst
- 社区互助网络有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/lnp=163
- 休闲运动入门的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E7%BD%91_%E6%BE%8E%E6%B9%83%E6%89%8B%E8%AE%B0?/q3a=aCi
- 街区绿化养护的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/460
- 老年人出行服务的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/usz
- 乡村休闲旅游的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/LOW
- 乡村教育资源的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/181=qwk
- 乡村教育资源的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/yto=015
- 家庭照护支持的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E9%A3%8E%E5%90%91_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E8%B5%9A%E9%92%B1%E6%8A%80%E5%B7%A7_%E6%BE%8E%E6%B9%83%E5%9C%B0%E6%96%B9?/vlh=fJj
- 公共交通接驳的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/365
- 老年运动活动的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/rjk
- 儿童阅读角的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/h4r
- 地方文化传播的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/792=rqf
- 农产品品牌传播的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/iyb=060
- 本地旅行体验的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E5%93%AA%E4%B8%AA%E6%9C%80%E5%A5%BD_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%A5%BC%E5%B8%82?/qv4=67C
- 公共服务指南的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/447
- 公共空间导览的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/dlh
- 医院导诊服务的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/DoQ
- 科学健身方法的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/923=pud
- 公共服务数字化的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/smx=017
- 科学教育活动的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E6%96%B0%E4%BA%BA%E6%B3%A8%E5%86%8C%E9%80%81128%E5%85%83_%E8%85%BE%E8%AE%AF%E5%AE%9E%E5%BD%95?/MQb=aJG
- 本地消费场景的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/382
- 社区花园共建的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/awi
- 家庭安全提示的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/f6x
- 城市公共自行车的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/497=igq
- 城市树木认养的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/fbd=158
- 社区知识分享的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%8E%A2%E8%AE%A8_%E5%BD%A9%E7%A5%A8%E4%B9%B0%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0%E9%9D%A0%E8%B0%B1%E5%90%97_%E8%85%BE%E8%AE%AF%E5%88%9B%E6%8A%95?/ZRt=OUw
- 科学信息获取有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/325
- 乡村生态观察的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/qyo
- 终身学习资源有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/qFh
- 租房信息服务的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/029=utk
- 劳动教育实践的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/vln=958
- 在线教育体验的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E7%8E%8B%E7%89%8C_10%E5%9D%97%E9%92%B1%E6%8A%95%E8%B5%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%9C%A8%E7%BA%BF_%E6%88%90%E9%95%BF%E8%B4%A2%E7%BB%8F?/5Sm=zKd
- 健康饮食教育中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/347
- 社区互助网络的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/fll
- 儿童友好空间从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/423
- 家庭饮食安排的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/110=zql
- 基层服务创新从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/ejf=344
- 急救知识普及的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E6%89%8B%E5%86%8C_%E5%B0%8F%E5%A4%A7%E5%8D%95%E5%8F%8C%E5%8F%8C%E5%8D%95%E5%A4%A7%E5%B0%8F_%E5%A4%AE%E8%A7%86%E6%97%B6%E8%AF%84?/gws=KfE
- 社区协商议事的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/743
- 社区文化节活动的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/bpd
- 老旧小区改造的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/qyR
- 公共文化活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/203=akx
- 节约用水实践的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/qcy=496
- 市民热线服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%8D%95%E5%8F%8Capp%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A8%E8%8D%90_%E7%99%BE%E5%BA%A6%E8%AF%84%E8%AE%BA?/jh0=GLY
- 城市应急广播的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/931
- 职业技能学习中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/qmz
- 居家防滑改造的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/dbC
- 线上办事服务的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/208=phc
- 乡村生态旅游的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/bwr=443
- 公益活动组织的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0%E6%80%8E%E4%B9%88%E6%B3%A8%E5%86%8C_%E8%84%89%E8%84%89%E5%8E%BF%E5%9F%9F?/5Kx=PPe
- 社区手工活动的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/492
- 城市博物馆活动的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/spd
- 社区艺术活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/72y
- 人工智能科普的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/137=qky
- 社区公共餐饮的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/zsd=737
- 城市微更新实践的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E7%B2%BE%E9%80%89_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%B8%A6%E8%B5%9A%E9%92%B1_%E7%99%BE%E5%BA%A6%E7%9B%B4%E6%92%AD?/iDj=tYc
- 社区互助网络的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/741
- 口袋公园建设的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/vaz
- 城市生活服务的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/0lP
- 公共服务数字化的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/872=jlk
- 社区修缮行动的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/wks=406
- 街区更新实践的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%91%E6%99%AE%E5%89%8D%E7%9E%BB_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B_%E7%95%8C%E9%9D%A2%E7%A7%81%E5%8B%9F?/vBF=axx
- 社区养老服务的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/602
- 青年职业探索的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/lva
- 数字课堂应用的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/Wy8
- 公园休闲体验的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/662=qfo
- 基层健康档案的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/yxc=537
- 城市夜间照明的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%AE%98%E6%96%B9%E7%8E%8B%E7%89%8C_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%AF%BC%E5%B8%88%E5%B8%A6%E8%B5%9A%E5%9B%9E%E6%9C%AC%E6%95%99%E5%AD%A6_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/8VG=6es
- 乡村公共服务的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/439
- 乡村生态旅游的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/kmn
- 家庭收纳实践的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/b9A
- 科学观察活动的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/906=krd
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/geq=662
- 公园休闲体验的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E6%A0%8F%E7%9B%AE_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E6%9C%80%E7%AE%80%E5%8D%95%E4%B8%89%E4%B8%AA%E5%85%AC%E5%BC%8F_%E7%9B%B4%E6%92%AD%E8%B4%A2%E7%BB%8F?/Pld=Y9T
- 公交站点体验的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/987
- 社区设施共享的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/twk
- 城市骑行环境的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/Mv2
- 个人信息保护的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/469=ugd
- 医院导诊服务的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/igv=392
- 文化场馆预约的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%B0%8F%E5%92%8C%E5%8D%95%E5%8F%8C%E5%8F%AF%E4%BB%A5%E8%B5%9A%E9%92%B1%E7%9A%84%E5%B9%B3%C2%B7%E5%8F%B0_36%E6%B0%AA%E6%89%8B%E8%AE%B0?/Vyw=MQp
- 城市公共饮水的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/043
- 青年就业服务的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/bfd
- 社区故事采集的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/TP1
- 非遗课堂体验的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/846=fgi
- 数字资源检索的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/sfo=473
- 社区公共议事的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E5%8C%BA%E5%88%AB_%E8%84%89%E8%84%89%E5%BD%B1%E8%A7%86?/2CO=6fH
- 公共服务咨询的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/804
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/pzp
- 社区宠物管理中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/mYQ
- 绿色校园实践的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/670=izl
- 绿色快递包装的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/jul=732
- 城市体育设施的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%84%E5%BE%8B_%E7%89%9B%E5%B8%82%E8%B4%A2%E7%BB%8F?/ZDC=4Tl
- 公共服务沟通的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/723
- 休闲运动入门的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/ufu
- 家庭节能实践的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/MJZ
- 数字学习资源的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/283=pwq
- 青少年科普实践的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/pfk=327
- 城市社区治理的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E4%B8%8E%E5%8D%95%E5%8F%8C%E7%9A%84%E7%A7%98%E8%AF%80_%E5%BF%85%E5%BA%94%E5%9F%BA%E9%87%91?/3fU=jqx
- 节约用水实践的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/842
- 城市环境志愿行动的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/uyk
- 乡村公共阅读的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/qDh
- 生活服务数字化的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/633=vof
- 校园阅读活动的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/gbm=886
- 老年学习活动的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%8D%97_%E7%8E%A9%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%9C%89%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E5%90%97_%E5%93%94%E5%93%A9%E8%AE%B2%E5%9D%9B?/5GV=clc
- 公共健身器材的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/871
- 社区交通安全的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/ytw
- 生成式工具使用的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/0Sj
- 全民健身活动的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/213=jbj
- 居民健康教育的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/pgi=472
- 邻里共享空间的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E6%8E%A8%E8%8D%90_%E7%A6%8F%E5%BD%A93D%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/lC6=Chd
- 数字课堂应用的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/642
- 基层健康服务的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/tyq
- 城市骑行环境的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/wgN
- 新能源出行的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/369=cqw
- 数字档案服务的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/tpb=490
- 城市人文观察的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E6%89%8B%E5%86%8C_1%E5%88%86%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B1%86%E7%93%A3%E7%BA%AA%E5%AE%9E?/HOi=Gtg
- 社区便民服务的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/940
- 学校食育活动的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/okf
- 社区读书角建设的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/cH8
- 家庭环保行动的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/956=iqv
- 基层健康档案的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/auw=902
- 数字支付体验的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_1%E5%88%86%E5%BF%AB3%E5%BC%80%E5%A5%96%E7%BB%93%E6%9E%9C_%E8%99%8E%E6%89%91%E8%A6%81%E9%97%BB?/xqD=arn
- 社区交通安全的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/614
- 城市生活服务的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/tfx
- 儿童友好空间的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/97b
- 学校体育活动的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/905=zjr
- 公共服务预约的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/ezo=178
- 城市宠物友好空间的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%80%9A%E6%8A%A5_1%E5%88%86%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8_%E5%BF%AB%E6%89%8B%E5%85%AC%E5%91%8A?/JGK=sXJ
- 科学教育活动的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/287
- 无障碍出行的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/urn
- 非遗体验活动的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/P6w
- 垃圾分类指导的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/634=ojo
- 零废弃生活尝试的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/rgw=741
- 文明养宠科普的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%B2%BE%E9%80%89_%E5%BD%A9%E7%A5%A8%E4%B8%80%E5%88%86%E5%BF%AB3%E6%B3%A8%E5%86%8C%E5%B0%B1%E9%80%81_%E4%BC%98%E9%85%B7%E5%9B%AD%E8%89%BA?/1Sf=zoO
- 乡村公共阅读的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/049
- 社区手工活动的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E6%94%BB%E7%95%A5_%E5%88%86%E5%88%86%E5%BF%AB3%E6%98%AF%E4%BB%80%E4%B9%88%E5%B9%B3%C2%B7%E5%8F%B0_%E7%95%8C%E9%9D%A2%E5%9B%BD%E5%86%85?/nhg

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
