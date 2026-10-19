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

- 儿童友好街区的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/bLc
- 电子商务服务的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/262=bjp
- 便民维修服务的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/lze=960
- 公共空间导览的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E9%95%BF%E6%9C%9F%E7%9B%88%E5%88%A9_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/H1z=wtr
- 社区协商议事从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/354
- 数字支付体验的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/akh
- 儿童友好空间的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/XBR
- 乡村休闲旅游的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/523=cmf
- 社区防暑服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/ocl=947
- 青少年心理健康的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B9%B0%E5%85%A5%E6%B3%95_%E9%A1%BA%E4%B8%B0%E5%86%9B%E4%BA%8B?/2hT=7fD
- 社区花园共建的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/135
- 健康饮食教育的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/wqz
- 绿色出行服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/SyN
- 社区故事采集的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/005=lri
- 生成式工具使用的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/pki=487
- 低碳社区实践的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%87%BA%E5%8F%B7%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E6%9C%AD%E8%AE%B0?/FtS=46s
- 社区家政服务中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/957
- 周末休闲规划的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/dvi
- 家庭饮食安排的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/k2P
- 家庭志愿活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/104=xzn
- 城市水环境观察的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/cql=795
- 读书会组织的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%8F%91%E5%B8%83_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD_%E8%AF%84%E8%AE%BA%E8%B4%A2%E7%BB%8F?/m4y=sxX
- 街头绿植养护的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/883
- 社区宠物管理的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/ixc
- 儿童阅读角的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/J24
- 城乡交流活动的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/021=mob
- 老年人日常照护的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/par=789
- 社区家校合作的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AA%97%E5%B1%80_36%E6%B0%AA%E7%99%BE%E7%A7%91?/u5t=EVZ
- 地方旅游导览的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/590
- 消防知识宣传的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/jpx
- 城市博物馆活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/ciN
- 社区文化节活动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/799=nbr
- 社区家校合作的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/uso=407
- 绿色快递包装的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%AB%98%E8%83%9C%E7%8E%87%E7%8E%A9%E6%B3%95_%E4%BA%9A%E9%A9%AC%E9%80%8A%E7%88%86%E6%96%99?/zpJ=MmI
- 软件开发学习的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/194
- 社区庭院绿化的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/sky
- 无障碍出行的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/THR
- 运动安全知识的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/718=tfr
- 社区停车服务的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/qrh=059
- 社区体育组织的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C5%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%A5%97%E8%B7%AF%E9%AA%97%E5%B1%80_%E8%B0%B7%E6%AD%8C%E6%BC%AB%E8%AF%84?/viS=nNq
- 青少年职业启蒙的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/916
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/cvy
- 城市公共自行车的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/bLe
- 个人信息保护的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/640=lom
- 社区教育资源的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/okj=597
- 学校食育活动的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%99%E5%AD%A6_%E5%87%A4%E5%87%B0%E6%B8%AF%E8%82%A1?/rhd=faY
- 灵活就业交流的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/414
- 便民维修服务的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/lru
- 智慧城市体验的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/FfT
- 市民热线服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/424=ivf
- 家庭阅读计划的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/dpk=629
- 小区停车协商的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%93%AA%E9%87%8C%E8%83%BD%E7%8E%A9_%E8%99%8E%E6%89%91%E6%B8%B8%E6%88%8F?/o7P=ID1
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/858
- 职业技能学习的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/hcb
- 地方文化传播的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/22B
- 社区读书角建设的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/142=qqx
- 城市人文观察的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/dqy=148
- 线上阅读资源的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%A0%B4%E8%A7%A3%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E6%96%87%E5%8C%96?/PI8=x97
- 城市噪声观察的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/226
- 小区停车协商的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/ajg
- 城市微更新实践的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/lnQ
- 儿童户外活动的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/584=dbe
- 城市应急科普的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/sna=940
- 数字生活课堂的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%8E%A8%E6%B5%8B_%E5%A4%B4%E6%9D%A1%E5%9C%B0%E4%BA%A7?/DB7=28t
- 城市公共空间的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/338
- 社区读书角建设的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/rjo
- 街道综合服务的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/uWi
- 社区教育资源的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/663=cic
- 绿色快递包装的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/yaf=316
- 食品安全科普的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%80%8E%E4%B9%88%E7%9C%8B%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%8A%92%E6%9E%9C%E6%97%B6%E8%AF%84?/TOP=bsZ
- 数字创意课程的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/486
- 城市社区治理的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/khz
- 文化遗产保护科普从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/u46
- 科学教育活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/057=xsk
- 乡村阅读空间的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/wrc=345
- 电动汽车充电的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%A4%E6%96%AD%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E8%B4%A2%E7%BB%8F%E6%97%B6%E6%8A%A5?/xSJ=1pj
- 绿色办公实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/544
- 老年人文化生活的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/zae
- 数字生活课堂的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/6UP
- 城市生活记录的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/864=fpu
- 社区体育组织的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/tdp=007
- 乡村休闲旅游的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%8A%95%E8%B5%84%E8%B5%84%E6%BA%90_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%9C%8B%E8%A7%84%E5%BE%8B_%E4%BA%AC%E4%B8%9C%E8%AE%BF%E8%B0%88?/tya=e6N
- 健康信息获取的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/786
- 家庭阅读计划的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/pmu
- 药品使用科普的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/Ckg
- 城市公共空间的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/400=fxx
- 社区庭院绿化的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/yni=743
- 城市基础设施的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99_%E8%B4%A2%E7%BB%8F%E9%A3%8E%E5%90%91?/aW2=yZh
- 社区防暑服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/866
- 绿色消费选择的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/jao
- 社区信息发布的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/uq3
- 城市公共饮水的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/567=isw
- 社区商业活力的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/tpc=457
- 本地历史资料从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95_%E6%90%9C%E7%8B%90%E6%A1%A3%E6%A1%88?/by4=6CI
- 通勤路线规划从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/798
- 社区信息发布的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/soe
- 乡村文化空间的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/ufQ
- 青年就业服务从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/335=cuu
- 社区科普课堂的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/pch=682
- 创业经验分享的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E7%8E%8B%E7%89%8C_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%89%8C%E5%9E%8B_%E5%BE%97%E7%89%A9%E6%8E%A2%E6%BA%90?/vtu=q6C
- 老年人日常照护的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/618
- 家庭教育交流从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/mwg
- 家庭节能设备的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/zxo
- 公共图书馆服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/651=mkj
- 数字便民地图的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/yug=124
- 社区艺术活动的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%AC%AC%E4%B8%80%E6%8E%A2%E8%AE%A8_%E5%BF%AB3%E7%9A%84%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E5%88%86%E6%9E%90_%E5%8D%8E%E6%B1%87%E8%B4%A2%E7%BB%8F?/tjM=bVI
- 社区读书角建设的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/160
- 城市便民驿站的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/rht
- 公交无障碍服务的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/IHS
- 老旧小区改造的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/918=uug
- 软件开发学习的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/evx=835
- 科学运动指导从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E7%99%BE%E7%A7%91_%E5%BF%AB3%E7%9A%84%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E7%8E%A9_%E8%8A%92%E6%9E%9C%E7%90%86%E8%B4%A2?/cnf=XYq
- 城市文化路线从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/779
- 社区安全巡查的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/kzu
- 学校食育活动的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/wtg
- 居民健康教育的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/919=eje
- 城市公共标识的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/plk=776
- 公共场馆服务的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E9%BB%91%E7%A7%91%E6%8A%80_%E6%8A%96%E9%9F%B3%E4%B8%93%E9%A2%98?/55W=MWQ
- 城市博物馆活动的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/805
- 邻里互助活动的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/cfi
- 休闲运动入门有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/g47
- 城市空气科普的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/747=asq
- 数字生活课堂的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/ccc=230
- 公共空间照明的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E4%BC%98%E9%85%B7%E5%86%9C%E4%B8%9A?/mi7=cq8
- 数字创作工具的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/943
- 社区环保活动的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/lvb
- 数字生活课堂的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/IFo
- 信息无障碍体验的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/385=csr
- 本地消费场景的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/rer=248
- 公益活动组织的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E7%99%BE%E5%BA%A6%E6%94%B6%E8%97%8F?/tST=CYy
- 公共空间休憩的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/463
- 绿色办公实践的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/wbg
- 老年运动活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/Eh5
- 地方民俗记录的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/506=qxf
- 文化遗产保护科普的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/lce=269
- 公共服务咨询的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E8%84%89%E8%84%89%E4%BA%BA%E7%89%A9?/7Tb=Kn5
- 社区活动报名的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/467
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/ooh
- 家庭急救准备的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/RhR
- 家庭志愿活动的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/600=sjv
- 城市地名文化的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/yiz=243
- 社区快递服务的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E5%85%AC%E5%91%8A_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E7%BD%91%E6%98%93%E5%BF%AB%E6%8A%A5?/XTz=Lgp
- 远程协作工具的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/525
- 居家适老化改造的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/laj
- 社区花园共建的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/ZvZ
- 健康饮水科普的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/471=szc
- 数字学习资源的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/qzz=019
- 社区停车服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E4%BA%86%E8%A7%A3_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E8%83%9C%E7%8E%87_%E8%84%89%E8%84%89%E6%91%84%E5%BD%B1?/MFJ=eYi
- 开放式学习空间的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/240
- 终身学习资源的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/wsr
- 街道综合服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/R5w
- 城市空气科普的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/872=una
- 本地旅行体验的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/rao=301
- 节能家电使用的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E8%81%9A%E7%84%A6_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%95%B0%E6%8D%AE%E7%A0%B4%E8%A7%A3%E8%A7%86%E9%A2%91_%E9%A1%BA%E4%B8%B0%E5%8E%86%E5%8F%B2?/jmK=MQ9
- 绿色办公实践的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/314
- 老年友好服务的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/ggw
- 数字创作工具的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/nky
- 社区绿色空间的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/000=xmf
- 社区快递服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/fcj=094
- 线上阅读资源的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97%E5%85%AC%E5%BC%8F_%E7%BD%91%E6%98%93%E5%88%9B%E6%8A%95?/7g5=AJ0
- 食品配送体验的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/656
- 乡村公共阅读的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/krz
- 公交站点体验的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/TEA
- 公共交通接驳中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/718=ows
- 公园亲子设施的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/pzm=087
- 城市基础设施的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%8F%91%E7%8E%B0_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%9A%84%E6%A6%82%E7%8E%87%E8%AE%A1%E7%AE%97_%E5%BE%97%E7%89%A9%E7%83%AD%E6%A6%9C?/1FA=l4B
- 健康步道使用的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/229
- 城市绿道建设的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/mma
- 社区故事采集的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/pRG
- 邻里互助活动的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/778=jtk
- 老年人文化生活的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/hfn=618
- 城市应急科普的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E4%B9%B0%E5%8D%95%E5%8F%8C%E6%80%8E%E4%B9%88%E4%B9%B0%E7%A8%B3%E8%B5%A2_%E4%BF%A1%E5%BE%B7%E8%B4%A2%E7%BB%8F?/c3A=iPJ
- 儿童户外活动的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/900
- 社区设施共享的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/bet
- 城市文明出行的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/k1M
- 乡村公共文化的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/660=mro
- 数字课堂应用的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/npm=038
- 家庭运动计划的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E5%89%8D%E7%9E%BB_%E5%88%86%E4%BA%AB%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%9B%9E%E8%A1%80%E6%8A%80%E6%9C%AF_%E5%BE%97%E7%89%A9%E7%9E%AD%E6%9C%9B?/jYV=CZV
- 公园亲子设施的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/323
- 家庭志愿活动的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/dsr
- 家庭科学教育的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/48g
- 物业服务沟通的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/682=exe
- 机器学习入门的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/yoj=849
- 便民信息查询的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8E%A2%E8%AE%A8_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%8F%A3%E8%AF%80%E7%A8%B3%E8%B5%9A%E6%8A%80%E5%B7%A7_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BC%97%E6%B5%8B?/ngv=UfK
- 家庭用电安全的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/295
- 校园社团活动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/aby
- 小微企业服务的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/pyp
- 开源技术交流的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/072=rin
- 老年人日常照护的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/qam=502
- 城市骑行环境的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%B2%BE%E9%80%89%E5%8A%A8%E6%80%81_%E4%B8%80%E5%88%86%E5%BF%AB3%E5%8D%95%E5%8F%8C%E5%A4%A7%E5%B0%8F%E6%AD%BB%E8%A7%84%E5%BE%8B_%E6%90%9C%E7%8B%90%E5%9F%8E%E4%BA%8B?/k5l=Cnl
- 创业经验分享的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/693
- 骑行路线规划的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/rlv
- 个人数据管理的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/2hX
- 智能家居应用的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/396=rxl
- 青年职业探索的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/kbx=913
- 社区停车服务的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E4%B8%93%E6%A0%8F%E5%85%AC%E5%91%8A_%E6%8E%A8%E8%8D%90%E5%87%A0%E4%B8%AA%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E5%B9%B3%C2%B7%E5%8F%B0_%E8%99%8E%E6%89%91%E7%BB%8F%E6%B5%8E?/4eL=h2p
- 传统手工艺体验的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/849
- 消防知识宣传有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/zgl
- 食品配送体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/XH9
- 城市公共艺术的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/530=jxj
- 农贸市场环境的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/cqq=218
- 软件开发学习的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%88%86%E6%96%99_%E5%BF%AB3%E6%8A%95%E6%B3%A85000_%E6%BE%8E%E6%B9%83%E8%82%A1%E7%A5%A8?/Ws0=dvR
- 基层医疗预约的便民做法梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/883
- 老年人日常照护的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/azg
- 低碳社区实践中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/O9f
- 社区垃圾回收的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/675=hhk
- 城市公共饮水的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/jpg=046
- 社区互助网络的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%9B%98%E7%82%B9%E6%89%8B%E5%86%8C_%E7%BD%91%E4%B8%8A%E5%BF%AB3%E6%9C%80%E7%A8%B3%E7%9A%84%E6%8A%95%E6%B3%A8%E6%96%B9%E6%B3%95_%E8%99%8E%E6%89%91%E4%BF%A1%E8%AE%BF?/ueT=86r
- 城市骑行环境的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/093
- 社区健康讲座的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/hiu
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/lUX
- 老旧小区改造的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/396=dxm
- 社区故事采集的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/cmk=275
- 社区便民集市的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C4%E6%9C%9F%E5%BF%85%E4%B8%AD%E5%85%AC%E5%BC%8F_%E8%99%8E%E6%89%91%E6%9C%9F%E8%B4%A7?/NPy=stS
- 社区健康讲座的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/632
- 社区活动空间的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/ozi
- 社区教育资源的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/ryU
- 城市博物馆服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/545=bzd
- 街区绿化养护中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/xom=505
- 数字学习资源的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A2%91%E9%81%93_%E6%B0%B8%E4%B9%85%E5%8D%95%E5%8F%8C%E7%9A%84%E8%A7%84%E5%BE%8B_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E4%BF%A1%E8%B4%B7?/KIR=f0t
- 社区公共餐饮的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/706
- 乡村教育资源的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/hzj
- 课后服务体验的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/m82
- 社区家政服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/299=dfs
- 数字创意课程的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/vyl=554
- 老年数字阅读的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%8A%95%E8%B5%84%E5%AD%A6%E4%B9%A0_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E8%A7%84%E5%BE%8B_%E7%99%BE%E5%BA%A6%E6%B8%AF%E8%82%A1?/CqF=4Ja
- 志愿服务平台的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/036
- 公园无障碍服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/lqa
- 周末休闲规划的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/AFz
- 家庭消费规划的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/097=qie
- 公交无障碍服务的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/coh=302
- 个人数据管理的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E7%BD%91%E8%B5%8C%E9%AA%97%E5%B1%80%E6%8F%AD%E7%A7%98_%E8%B1%86%E7%93%A3%E6%9C%AD%E8%AE%B0?/K84=vOS
- 社区运动空间的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/434
- 开放式学习空间的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/dwr
- 本地历史资料的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/wiF
- 社区体育组织的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/147=wmd
- 公共交通接驳的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/yll=348
- 青年就业服务的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%AD%A3%E8%A7%84%E5%B9%B3%C2%B7%E5%8F%B0%E6%8E%A5%E5%8D%95_%E7%9F%A5%E4%B9%8E%E8%B5%84%E8%AE%AF?/ubI=Ivb
- 地方文化传播从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/011
- 新能源知识普及的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/lmo
- 城市绿道建设的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/Xgl
- 传统节日科普的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/270=bzt
- 公共场所导视的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/mgn=688
- 无障碍信息设计的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E6%89%93%E6%B3%95%E6%95%99%E7%A8%8B_%E6%98%9F%E8%80%80%E8%B4%A2%E7%BB%8F?/QYs=eaw
- 街区绿化养护的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/683
- 个人信息保护的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/icd
- 社区艺术活动的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/Hsl
- 网络信息辨识的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/469=qsw
- 青年志愿活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/bmo=407
- 社区垃圾回收的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%83%AD%E7%82%B9%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C%E8%B7%9F%E8%80%81%E5%B8%88%E8%AE%A1%E5%88%92%E8%B5%9A%E9%92%B1%E9%AA%97%E5%B1%80_%E6%90%9C%E7%8B%97%E7%BA%AA%E5%AE%9E?/iaE=iUs

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
