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

- 青少年科普实践的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/lwa=075
- 健康步道使用的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%AC%AC%E4%B8%80%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E5%93%94%E5%93%A9%E8%A7%86%E9%A2%91?/aFp=1TQ
- 社区法律科普的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/527
- 开源技术交流的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/roo
- 城市适老服务的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/WLD
- 社区便民集市的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/938=kzv
- 科学健身方法的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/duc=127
- 城市宠物友好空间的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%80%8D%E6%8A%95_360%E7%BE%8E%E9%A3%9F?/8fQ=iX9
- 志愿者培训交流的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/688
- 公共空间安全的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/yqy
- 城乡交通衔接从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/o4t
- 城市社区治理的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/369=vfm
- 节日文化体验的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/wrb=851
- 无障碍出行的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E6%8A%80%E5%B7%A7100%E5%87%86_%E6%90%9C%E7%8B%97%E6%99%A8%E6%8A%A5?/PVO=BE7
- 数字创意课程的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/375
- 校园阅读活动的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/ehs
- 城市环境志愿行动的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/A9p
- 儿童户外活动中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/104=ote
- 生活垃圾减量的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/kyt=289
- 社区活动空间的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E8%85%BE%E8%AE%AF%E5%88%86%E5%88%86%E5%BD%A9%E7%9A%84%E7%8E%A9%E6%B3%95%E6%8A%80%E5%B7%A7_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/jss=XDf
- 乡村生活观察的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/980
- 城市文明实践的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/nrb
- 数字创意课程的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/93J
- 邻里互助活动的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/927=juq
- 社区法律科普的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/bhm=546
- 社区读书角建设的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B_%E5%BF%AB3%E6%8A%95%E6%B3%A8%E5%8F%A3%E8%AF%80_%E9%93%B6%E7%9B%88%E8%B4%A2%E7%BB%8F?/SnI=kwl
- 全民阅读推广的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/826
- 公交站点体验的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/ptw
- 居家防滑改造的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/h4z
- 基层健康档案从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/146=zdi
- 在线教育体验的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/vai=148
- 老旧小区改造的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E5%8A%A8%E6%80%81_%E5%BF%AB3%E5%88%86%E6%9E%90%E6%8A%80%E5%B7%A7%E5%8F%A3%E8%AF%80_%E6%90%9C%E7%8B%90%E8%88%86%E6%83%85?/CIX=sIO
- 志愿服务平台的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/728
- 口袋公园建设的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/acd
- 公共服务数字化的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/pdh
- 城市休闲步道的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/536=wvi
- 健康信息获取的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/psi=371
- 数字设备回收从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E6%9C%89%E4%BA%BA%E6%8E%A7%E5%88%B6%E5%90%97_%E9%A1%BA%E4%B8%B0%E7%A8%8E%E5%8A%A1?/KN0=fgh
- 公交站点体验的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/309
- 城市住房服务的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/rji
- 无障碍出行的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/EEG
- 城市夜间生活的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/472=yvx
- 社区养老服务的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/nda=662
- 城乡交流活动的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E5%AE%9E%E6%88%98%E6%8A%80%E5%B7%A7_%E8%85%BE%E8%AE%AF%E6%95%99%E8%82%B2?/9Cx=UUg
- 乡村文化空间中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/046
- 全民健身活动的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/lky
- 社区老年食堂的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/wXv
- 家庭科学教育的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/110=fim
- 个人时间管理的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/qay=579
- 低碳社区实践的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E9%80%9A%E6%8A%A5_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E8%A7%84%E5%BE%8B%E7%A8%B3%E8%B5%9A_%E9%BC%8E%E5%B3%B0%E8%B4%A2%E7%BB%8F?/IDs=8iV
- 邻里互助活动的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/542
- 数字设备回收的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/frs
- 图书馆活动策划的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/IAm
- 绿色消费选择的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/364=zyr
- 家庭收纳实践的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/ngw=848
- 家庭陪伴活动中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E8%B4%A2%E7%BB%8F_%E5%BF%AB3%E6%8A%80%E5%B7%A7%E4%B8%8E%E6%94%BB%E7%95%A5_%E6%99%BA%E6%8A%95%E8%B4%A2%E7%BB%8F?/5Bt=Ori
- 社区便民集市的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/998
- 城市夜间照明的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/hdw
- 家庭网络使用的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/k46
- 城市社区治理的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/049=noo
- 青少年科普实践的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/hvz=722
- 劳动教育实践的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB3%E7%9A%84%E6%8A%80%E5%B7%A7%E6%96%B9%E6%B3%95_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/320=2F4
- 学校食育活动的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/586
- 绿色生活实践的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/vat
- 社区艺术活动的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/Cg8
- 公共服务数字化的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/152=fsz
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/tnm=997
- 绿色校园实践有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E7%9C%8B%E7%82%B9_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%80%81%E5%B8%88_%E5%8D%97%E4%BA%9A%E8%B4%A2%E7%BB%8F?/JJe=DaL
- 社区文化传播的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/551
- 小微企业服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/til
- 社区生活指南的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/h9m
- 城乡交通衔接的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/121=kwt
- 老年人文化生活的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/qie=705
- 网络安全教育的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0%E9%82%80%E8%AF%B7%E7%A0%81_%E9%B8%BF%E8%BF%90%E8%B4%A2%E7%BB%8F?/8Cm=qhR
- 社区儿童活动的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/786
- 机器学习入门的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/xml
- 节能家电使用的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/bGI
- 校园安全教育的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/912=vml
- 街区道路维护的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/yzn=699
- 电动汽车充电的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%A0%8F%E7%9B%AE_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%85%A8%E4%BA%BA%E5%B7%A5%E8%AE%A1%E5%88%92_%E8%8A%92%E6%9E%9C%E8%81%8C%E5%9C%BA?/TUO=MhH
- 城市共享单车的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/186
- 城市慢跑路线的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/res
- 数字公共文化从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/H55
- 数字创意课程的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/964=pji
- 青少年心理健康的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/xgi=196
- 城市展览体验的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E8%A7%84%E5%88%92_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A8%B3%E8%B5%9A%E8%80%81%E5%B8%88%E5%85%8D%E8%B4%B9%E8%B5%9A%E9%92%B1_%E8%8A%92%E6%9E%9C%E5%86%9C%E4%B8%9A?/zBy=Hz4
- 家庭养老规划的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/048
- 社区文化节活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/hjg
- 社区托育服务的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/I2R
- 公共场所导视的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/641=dsh
- 居民健康教育的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/bjd=668
- 社区信息发布中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%8A%A9%E8%B5%A2_%E9%9B%85%E8%99%8E%E6%96%87%E5%8C%96?/gBY=wWR
- 城市游园体验的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/089
- 城市博物馆服务的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/vyd
- 家庭节能实践的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/coW
- 灵活就业交流的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/996=que
- 社区活动空间的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/tgq=217
- 无障碍出行的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BB%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E7%A0%8D%E9%BE%99_%E7%9F%A5%E4%B9%8E%E7%A7%81%E5%8B%9F?/MBP=sov
- 社区停车服务的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/366
- 便民服务窗口的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/wnz
- 数字生活课堂的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/kG1
- 社区安全巡查的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/251=jbw
- 青少年心理健康的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/ozv=668
- 城市步行友好的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E6%80%BB%E7%BB%93_%E4%B8%8B%E8%BD%BD%E5%BD%A9%E7%A5%A8%E5%BF%AB3app_%E7%99%BE%E5%BA%A6%E6%94%BF%E5%8A%A1?/hr7=SsU
- 亲子科普活动的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/559
- 城市空气科普的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/vbh
- 便民维修服务的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/gDh
- 非遗课堂体验的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/577=juk
- 城市社区治理的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/fdr=195
- 城市共享单车的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%B8%93%E8%AE%BF_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%A4%A7%E5%8E%85-welcome_%E5%8D%B3%E5%88%BB%E5%86%9C%E4%B8%9A?/w6V=kow
- 社区读书角建设的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/961
- 社区学习活动的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/bds
- 城市环境志愿行动的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/C8z
- 非遗体验活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/450=abo
- 绿色校园实践的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/uaw=079
- 公共服务咨询的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E5%8A%A8%E6%80%81_%E5%BF%AB3%E4%B8%AD%E5%A5%96%E8%A7%84%E5%88%99%E5%92%8C%E5%A5%96%E9%87%91%E5%9B%BE_%E6%8A%96%E9%9F%B3%E9%80%9F%E8%A7%88?/9FR=tQD
- 全民健身活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/682
- 城市步行友好的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/mjd
- 健康步道使用的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/SKJ
- 老年人文化生活的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/494=yml
- 社区垃圾分类的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/vbn=579
- 街道综合服务的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%85%8D%E8%B4%B9%E8%AE%A1%E5%88%92_%E5%BE%97%E7%89%A9%E6%97%B6%E5%B0%9A?/cT6=Q2p
- 科学睡眠习惯的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/869
- 就业技能培训中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/kcs
- 文化遗产保护科普的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/Oz2
- 文明养宠科普中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/502=qpo
- 城市公共饮水的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/gym=557
- 社区公共议事的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%AD%A6%E4%B9%A0_%E4%BD%93%E8%82%B2%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%97%E5%9B%BD%E9%99%85?/Qvs=6PV
- 城市住房服务的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/698
- 数据分析入门的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/wba
- 智慧停车服务的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/MsQ
- 公共卫生宣传的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/084=oyy
- 节气饮食文化的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/dla=241
- 药品使用科普从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E6%80%BB%E7%BB%93_%E6%B1%87%E5%BD%A9%E7%BD%91%E5%BF%AB3_%E8%85%BE%E8%AE%AF%E7%BA%AA%E5%AE%9E?/9me=SVm
- 社区邻里服务中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/960
- 青少年户外教育的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/tbe
- 城市宠物友好空间的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/R0b
- 数字资源检索的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/885=qbf
- 城乡交流活动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/nov=022
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E8%B5%9A%E9%92%B1_%E5%BF%85%E5%BA%94%E6%97%A5%E6%8A%A5?/315=gRN
- 城市游园体验的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/705
- 老年人文化生活的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zcc
- 家庭环保行动的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/CFs
- 新能源知识普及的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/850=jxh
- 本地消费场景的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/zrg=113
- 本地历史资料的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB3%E5%AF%BC%E5%B8%88%E7%A8%B3%E8%B5%A2%E8%AE%A1%E5%88%92_%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vm0=Cix
- 社区便利生活的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/018
- 光伏知识科普的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/fzv
- 街道综合服务的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/zps
- 地方旅游导览的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/718=kcy
- 生活垃圾减量的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/ica=748
- 生活技能分享的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E7%BB%8F%E9%AA%8C_%E5%85%A8%E7%90%83%E5%BD%A9%E7%A5%A8-%E5%85%A8%E7%90%83%E5%BF%AB3_%E9%87%91%E7%91%9E%E8%B4%A2%E7%BB%8F?/yRL=BQN
- 城市骑行环境的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/572
- 音乐欣赏活动的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/stj
- 智能家居应用的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/JHx
- 社区活动策划的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/052=ryc
- 公共服务数字化的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/mvf=308
- 社区故事采集的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E4%B9%90%E5%BD%A9_%E8%B0%B7%E6%AD%8C%E7%A4%BE%E5%8C%BA?/yjW=phL
- 社区垃圾分类的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/685
- 通勤路线规划的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/nlc
- 家庭园艺实践的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/kik
- 户外活动组织中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/437=svy
- 数字政务体验的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/eni=378
- 地方戏曲体验中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E8%B5%84%E6%BA%90_%E4%B8%AD%E5%9B%BD%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E6%90%9C%E7%8B%90%E9%97%AE%E5%8D%B7?/GQp=3HT
- 城市建设科普的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/055
- 社区老年食堂有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/zks
- 公共服务咨询的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/M2Y
- 节假日出行安排从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/253=etp
- 数字公共文化的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/xnh=185
- 公共交通接驳的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%89%8D%E7%9E%BB_%E6%9F%A5%E8%AF%A2%E7%A6%8F%E5%88%A9%E5%BD%A9%E7%A5%A8%E5%BF%AB3_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%81%A5%E5%BA%B7?/5ZQ=yU6
- 科普展览体验的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/025
- 在线学习体验的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/eum
- 社区协商议事的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/JSL
- 绿色出行服务的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/728=ebl
- 家庭健康管理的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/zdk=544
- 社区宣传栏更新的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E5%BF%AB3app%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E6%BC%AB%E8%AF%84?/WPR=Vpi
- 家庭志愿活动的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/982
- 口袋公园建设的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/opk
- 儿童阅读角的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/DI0
- 志愿者培训交流的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/827=xrb
- 光伏知识科普的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/tuh=082
- 老年人出行服务的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E7%AE%80%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0app_%E8%B4%A2%E7%BB%8F%E7%BA%B5%E6%A8%AA?/tmY=att
- 家庭环保习惯的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/894
- 城市慢行系统中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/bjv
- 城市建设科普的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/jmR
- 老年友好服务的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/283=wsf
- 市民意见收集的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/fvi=733
- 社区垃圾分类的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%BD%A9%E7%A5%A8%E5%BF%AB3%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%90%AF%E8%B6%8A%E8%B4%A2%E7%BB%8F?/ZW8=33O
- 校园社团活动的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/525
- 社区修缮行动的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/ssb
- 节气饮食文化的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/tFR
- 家庭环保行动的线下体验记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/338=fjz
- 城市人文观察的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/pfe=208
- 公共交通信息服务的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E8%B5%B0%E8%AF%95%E5%9B%BE_%E8%99%8E%E6%89%91%E6%96%87%E5%BA%93?/h1Z=b9X
- 老年友好服务中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/749
- 软件开发学习的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/aah
- 社区艺术活动的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/GF0
- 数字资源检索的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/116=yue
- 城市夜间照明的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/pkf=972
- 应急物资管理的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B_%E6%96%B0%E6%B5%AA%E6%88%B7%E5%A4%96?/0E0=OvG
- 课后服务体验的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/834
- 垃圾分类指导的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/uox
- 公园亲子设施的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/A5d
- 通勤路线规划中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/525=uor
- 科学运动指导的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/nwe=491
- 便民服务窗口的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E8%A7%A3%E8%AF%BB_%E5%BF%AB3app%E4%BF%A1%E8%AA%89%E5%B9%B3%C2%B7%E5%8F%B0_%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%85%AC%E5%BC%80%E8%AF%BE?/JZU=snM
- 城市展览体验的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/412
- 社区教育资源的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/ucl
- 社区防暑服务的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/dTp
- 就业技能培训的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/208=bzf
- 节约用水实践的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/zbm=547
- 健康饮食教育的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%A0%B8%E5%BF%83%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E9%9B%85%E8%99%8E%E6%BC%AB%E8%AF%84?/hzf=5JB
- 城市树木认养的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/380
- 科普展览体验的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/nmq
- 应急物资管理的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/NoX
- 家庭健康科普的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/733=lzi
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/fhu=910
- 数字学习资源的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E9%87%8D%E5%A4%A7%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E7%BD%91_%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA?/D5Y=xgC
- 信息无障碍体验的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/657
- 城市骑行环境中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/baz
- 社区活动策划的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/hEs
- 社区信息发布的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/159=byq
- 数字创意课程的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/hjq=770
- 劳动教育实践的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E8%AE%A8%E8%AE%BA_%E5%A5%BD%E5%BD%A9%E7%BD%91welcome%E8%B4%AD%E5%BD%A9%E5%85%A5%E5%8F%A3_%E6%90%9C%E7%8B%90%E5%9C%B0%E6%96%B9?/Yrc=NSr
- 老年友好服务的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/147
- 公共服务咨询的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/tsh
- 城市环境志愿行动的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/v15
- 图书馆数字服务的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/840=vrs
- 劳动教育实践的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/leb=007
- 公交站点体验的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E5%8A%A8%E6%80%81_%E6%98%93%E5%BD%A9%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0_%E6%96%B0%E6%B5%AA%E6%95%B0%E7%A0%81?/RI4=T9M
- 老年智能设备的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/320
- 网络安全教育中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/miu
- 青年职业探索的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/h0z
- 城市夜间生活的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/752=liw
- 街区道路维护的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/ncx=327
- 数字创意课程的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AE%A8%E8%AE%BA_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E9%87%91%E7%89%8C%E5%9B%9E%E8%A1%80%E5%AF%BC%E5%B8%88_%E9%9B%85%E8%99%8E%E6%97%B6%E8%AE%AF?/DSV=ZPI
- 乡村文化空间的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/308
- 读书会组织的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/otz
- 乡村教育资源的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/RU3
- 个人数据管理的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/052=bln
- 基层健康档案的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/zmr=704
- 老旧小区改造的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E8%B4%A2%E7%BB%8F%E6%8E%A8%E8%8D%90_%E5%BF%AB3%E6%89%80%E6%9C%89%E6%97%97%E4%B8%8B%E5%B9%B3%C2%B7%E5%8F%B0%E5%88%97%E8%A1%A8_%E6%96%B0%E6%B5%AA%E5%AE%B6%E5%B1%85?/7wj=zoY
- 运动安全知识的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/211
- 社区阅读服务有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/ccp
- 社区生活指南的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/gGh
- 城市公共自行车的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/014=inb
- 职业技能学习的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/ize=787
- 社区养老服务的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E8%81%9A%E7%84%A6_%E5%BF%AB3%E8%AE%A1%E5%88%92%E5%AE%98%E6%96%B9_%E8%85%BE%E8%AE%AF%E6%9C%9F%E8%B4%A7?/9wh=pSK
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/820
- 城市公共厕所的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%9B%98%E7%82%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB3%E5%B9%B3%C2%B7%E5%8F%B0%E5%BD%A9%E7%A5%A8%E7%BD%91%E7%AB%99_%E8%85%BE%E8%AE%AF%E7%9B%98%E7%82%B9?/rbd

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
