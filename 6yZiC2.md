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

- 农产品消费体验的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9F%E8%A7%88?/cSV
- 光伏知识科普的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9F%E8%A7%88?/215=hdm
- 社区交通安全从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9F%E8%A7%88?/xpg=890
- 公共空间休憩有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%B4%A2%E7%BB%8F_%E5%A4%A7%E5%8F%91%E5%A4%A7%E5%8F%91%E8%AE%BA%E5%9D%9B%E5%AE%98%E7%BD%91%E5%85%A5%E5%8F%A3_36%E6%B0%AA%E9%80%9F%E8%A7%88?/jOV=Yr7
- 儿童运动体验的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/158
- 志愿服务平台的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/xys
- 机器人科普活动的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/jWC
- 家庭教育交流的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/069=jfj
- 社区科普课堂的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/won=984
- 城市休闲步道的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E6%8C%87%E5%AF%BC_%E5%A4%A7%E5%8F%91%E5%BD%A9657%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_%E8%B0%B7%E6%AD%8C%E6%92%AD%E6%8A%A5?/IFT=9gv
- 乡村文化空间的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/708
- 数字资源检索的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/bep
- 租房信息服务的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/dji
- 公共空间导览的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/284=moc
- 社区宠物管理的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/rjb=808
- 城市展览体验的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%8F%91%E7%8E%B0_%E5%A8%B1%E4%B9%90%E4%B8%AD%E5%BF%83-%E5%B9%B3%C2%B7%E5%8F%B0%E7%99%BB%E5%BD%95_36%E6%B0%AA%E6%97%B6%E8%AE%AF?/4Em=MKE
- 社区垃圾回收的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/445
- 社区应急准备的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/wch
- 城市公共艺术的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/84B
- 个人数据管理的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/847=fmo
- 图书馆活动策划的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/yle=917
- 开放式学习空间的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%B2%BE%E9%80%89%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%A4%A7%E5%8F%91%E6%89%8B%E6%9C%BA%E7%99%BB%E5%BD%95%E5%B9%B3%C2%B7%E5%8F%B0_%E8%B0%B7%E6%AD%8C%E7%BB%8F%E6%B5%8E?/m8F=C8P
- 校园阅读活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/678
- 绿色校园实践的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/qad
- 老年人文化生活从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/FOM
- 网络安全教育的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/129=kkn
- 城市绿道建设的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/cks=686
- 基层医疗预约的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%83%AD%E7%82%B9%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%A4%A7%E5%8F%91df888%E7%BD%91%E9%A1%B5%E7%89%88_%E6%8A%96%E9%9F%B3%E4%BF%A1%E8%AE%BF?/f5u=X3j
- 社区公共议事的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/452
- 图书借阅体验的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/iaq
- 生成式工具使用的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/L1d
- 公共交通接驳的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/250=axe
- 全民阅读推广中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/hkl=816
- 城市便民驿站的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%BB%8A%E6%97%A5%E9%80%9A%E6%8A%A5_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8E%A9_%E6%96%B0%E6%B5%AA%E7%BA%AA%E5%AE%9E?/64F=dic
- 图书借阅体验的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/478
- 节日文化体验的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/jyi
- 公益活动组织的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/JG9
- 城市体育设施的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/655=ofe
- 城市空气科普的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/yhk=690
- 家庭运动计划的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C_%E5%BF%AB3%E5%BD%A9%E7%A5%A8APP%E5%AE%98%E6%96%B9%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%E5%86%85%E5%AE%B9_%E5%A4%AE%E8%A7%86%E7%90%86%E8%B4%A2?/oHg=bbe
- 数字素养提升的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/293
- 非遗体验活动的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/pae
- 街区绿化养护的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/Pvc
- 城市休闲步道的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/570=twb
- 社区便利生活的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/kew=707
- 家庭照护支持的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E7%B2%BE%E9%80%89_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9_%E8%B0%B7%E6%AD%8C%E5%9B%BD%E9%99%85?/2Yv=lB0
- 地方文化传播的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/112
- 城市绿色交通的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/ueo
- 城市公共空间的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/3ii
- 数字创意课程的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/216=bhk
- 家庭阅读计划的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/ozn=997
- 青少年户外教育有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6app%E4%B8%8B%E8%BD%BD_%E5%8D%B3%E5%88%BB%E6%95%B0%E7%A0%81?/mJ4=jNv
- 租房信息服务的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/830
- 社区文化节活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/hjn
- 青少年户外教育的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/KfI
- 儿童运动体验的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/989=yjg
- 青年职业探索的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/rvp=110
- 光伏知识科普的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E4%B8%93%E6%A0%8F%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E5%BF%85%E5%BA%94%E6%99%9A%E6%8A%A5?/d6o=6Y4
- 家庭教育交流的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/867
- 垃圾分类指导的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/rae
- 社区协商议事的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/7ES
- 学校体育活动的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/187=vef
- 基层健康服务从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/pka=395
- 城市生活记录的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%96%B9%E6%A1%88%E8%A7%A3%E8%AF%BB_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%89%E5%8D%93%E7%89%88_%E9%9B%85%E8%99%8E%E5%BF%AB%E8%AE%AF?/vp0=O4V
- 社区宠物管理的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/870
- 节能生活方式的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/vvk
- 农贸市场环境的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/jSX
- 个人信息保护的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/464=rsh
- 农贸市场环境的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/qji=794
- 公共空间照明的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E5%B9%B3%C2%B7%E5%8F%B0app%E4%B8%8B%E8%BD%BD_%E6%8A%96%E9%9F%B3%E7%88%86%E6%96%99?/PeJ=7a6
- 社区公共卫生的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/955
- 读书会组织的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/yye
- 零废弃生活尝试的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/hTD
- 基层医疗预约的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/321=csi
- 家庭阅读计划的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/pbu=451
- 日常摄影记录的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%99%AE%E5%8F%8A%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E5%AE%89%E5%8D%93%E7%89%88%E4%B8%8B%E8%BD%BD_36%E6%B0%AA%E4%B9%A6%E7%94%BB?/due=Jty
- 社区便利生活的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/449
- 家庭安全提示的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/omc
- 文明养宠科普的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/Pm6
- 劳动教育实践的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/804=dxf
- 城市慢跑路线的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/wif=511
- 社区便利生活的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E7%BD%91%E5%9D%80_%E9%9B%85%E8%99%8E%E9%A3%9F%E5%93%81?/sUk=bTW
- 数字创作工具的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/394
- 城市住房服务的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vll
- 学校食育活动的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/obl
- 非遗体验活动的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/319=flq
- 垃圾分类指导的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/vyl=438
- 乡村阅读空间的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%AC%AC%E4%B8%80%E5%8F%91%E7%8E%B0_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%AD%A3%E8%A7%84app%E4%B8%8B%E8%BD%BD_%E5%8D%8E%E4%BF%A1%E8%B4%A2%E7%BB%8F?/gyK=tza
- 街区更新实践的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/161
- 机器学习入门的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/twt
- 家庭饮食安排的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/RSd
- 青少年户外教育的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/917=iam
- 城市环境志愿行动的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/bzt=366
- 科学健身方法的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E9%A3%8E%E5%90%91_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E5%B9%B3%C2%B7%E5%8F%B0%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_%E4%BD%B3%E8%AA%89%E8%B4%A2%E7%BB%8F?/kMs=gsF
- 本地旅行体验的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/656
- 乡村电商实践的家庭参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/vcu
- 城市便民驿站的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/U8A
- 家庭饮食安排的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/623=pyv
- 开放式学习空间的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/oau=866
- 社区公共议事从需求出发看服务设计 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%8E%A9%E5%AE%B6%E6%8C%87%E5%AF%BC_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%A4%A7%E5%85%A8_%E6%90%9C%E7%8B%90%E8%BD%AC%E8%BD%BD?/gqj=xcP
- 本地历史资料的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/748
- 科学观察活动的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/jqf
- 节日文化体验的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/aqV
- 社区托育服务的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/534=jbd
- 乡村文化空间的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/mqy=402
- 公园无障碍服务的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%8A%95%E8%B5%84%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BDapp_%E6%8A%96%E9%9F%B3%E6%96%87%E5%BA%93?/gt5=1vH
- 社区儿童活动的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/057
- 社区托育服务的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/zmt
- 社区共享书架的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/SmF
- 社区公共餐饮的社区行动案例 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/818=ekn
- 青少年科普实践的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/tke=796
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E6%89%8B%E5%86%8C_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%A4%A7%E5%B0%8F%E5%8D%95%E5%8F%8C_%E5%BE%97%E7%89%A9%E7%BE%8E%E9%A3%9F?/IiI=AUp
- 城市可持续生活的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/565
- 农产品消费体验的绿色实践方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/www
- 家庭环保习惯的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/03D
- 公共卫生设施的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/498=sqt
- 公益活动组织的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/kgb=820
- 社区知识分享的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%A0%B8%E5%BF%83%E8%81%9A%E7%84%A6_%E8%BE%9B%E8%BF%90%E5%BF%AB3%E2%80%94%E6%B3%A8%E5%86%8C%E5%A4%A7%E5%8E%85_%E5%A4%AE%E8%A7%86%E6%B8%B8%E6%88%8F?/NyF=Tpu
- 便民维修服务的活动组织技巧 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/571
- 城市树木认养的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/xcz
- 城市慢跑路线的服务范围梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/qAq
- 家庭园艺实践的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/744=jcw
- 社区健康讲座的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/fvj=706
- 数字创意课程的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%99%AE%E5%8F%8A%E7%BB%86%E8%AF%B4_%E5%BF%AB3%E7%BD%91%E7%BB%9C%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD_%E5%BF%85%E5%BA%94%E5%8E%BF%E5%9F%9F?/IOT=ovM
- 电子商务服务的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/528
- 公共健身器材的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/hap
- 地方旅游导览中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/DZW
- 人工智能科普的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/723=aup
- 便民服务地图的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/ggo=380
- 社区故事采集的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%A7%82%E5%AF%9F_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B_%E4%BA%AC%E4%B8%9C%E7%A4%BE%E5%8C%BA?/8IJ=o0A
- 节日文化体验中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/454
- 公共卫生设施的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/rxx
- 家庭陪伴活动的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/FPA
- 数字公共文化的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/108=dhd
- 校园社团活动的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/ipk=340
- 公共空间休憩的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E4%B8%8B%E8%BD%BD%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6_360%E6%B6%88%E8%B4%B9?/Rvw=w4J
- 社区修缮行动中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/678
- 终身学习资源的使用门槛与改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/kqc
- 乡村文化活动的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/Etl
- 儿童阅读角的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/328=pcs
- 科学运动指导的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/fmo=193
- 校园阅读活动的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E5%85%AC%E5%91%8A_%E5%BF%AB3%E5%BD%A9%E7%A5%A8app%E4%B8%8B%E8%BD%BD%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%89%B9%E7%A8%BF?/pTh=bK2
- 社区家政服务的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/712
- 家庭消费规划的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/vpa
- 图书馆活动策划的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/FiN
- 公共服务沟通的安全使用提示 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/453=ooo
- 传统节日科普的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/ejn=739
- 居民健康教育的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%9F%A5%E9%81%93_%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E6%9C%80%E6%96%B0%E7%89%88app%E4%B8%8B%E8%BD%BD_%E8%8A%92%E6%9E%9C?/htZ=42S
- 青少年科技社团的基础设施观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/691
- 公共服务评价的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/bhv
- 家庭陪伴活动的学习资源整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/dku
- 节气饮食文化的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/900=fcw
- 运动安全知识的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/mqv=311
- 城市夜间照明的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91_355app%E5%BD%A9%E7%A5%A8_%E7%AC%AC%E4%B8%80%E8%B4%A2%E7%BB%8F?/b4B=pa2
- 基层医疗预约的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/950
- 城市夜间照明中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/usa
- 乡村生态旅游从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/OAl
- 社会体育指导的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/906=heu
- 城市社区治理有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/lpa=909
- 乡村教育资源中的几个关键细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E8%B4%A2%E7%BB%8F_787%E5%A8%B1%E4%B9%90%E5%AE%98%E7%BD%91%E4%B8%8B%E8%BD%BD_%E9%9B%85%E8%99%8E%E5%9C%B0%E4%BA%A7?/kMo=D4k
- 生成式工具使用的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/580
- 地方戏曲体验的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/pne
- 社区手工活动的空间设计要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/ubc
- 老年人日常照护的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/084=dah
- 家庭健康科普的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/jwv=694
- 青少年编程学习的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%BD%A9%E7%A5%A8703app%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E7%A4%BE%E5%8C%BA?/ABQ=aNt
- 在线教育体验的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/007
- 城市建设科普的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/mnp
- 生活垃圾回收的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/KMN
- 职业技能学习的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/939=gav
- 读书会组织的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/xxs=961
- 社区学习活动有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E7%A7%92%E6%87%82%E9%80%9A%E6%8A%A5_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%99%8E%E6%89%91%E6%A5%BC%E5%B8%82?/Vr3=2aH
- 数字资源检索的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/284
- 城市可持续生活的居民参与机会 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/zpv
- 城市体育设施的协作机制梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/lna
- 气象科普传播的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/859=nhy
- 公共服务沟通的资源整合思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/aeh=017
- 文化遗产保护科普的活动策划思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%B2%BE%E9%80%89%E6%8C%87%E5%8D%97_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD355_%E8%99%8E%E5%97%85%E5%8A%A8%E6%BC%AB?/1nO=0am
- 社区教育资源的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/368
- 社区邻里服务的家庭实践清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/pmy
- 节约用水实践的实用信息清单 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/Wrr
- 数字公共文化的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/295=pzv
- 志愿者培训交流的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/oyb=811
- 乡村文化空间的入门知识整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%BD%A9%E6%B0%91%E8%B5%84%E6%BA%90_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%93%AA%E4%B8%AA%E5%A5%BD_%E4%BC%98%E9%85%B7%E6%98%9F%E5%BA%A7?/pSS=saG
- 公共场所导视的长期维护要点 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/858
- 社区宣传栏更新的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/maw
- 读书会组织的常见问题梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/C3p
- 儿童阅读角的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/868=rqi
- 开源技术交流的日常实践笔记 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/znf=512
- 数字创作工具的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E6%8A%95%E8%B5%84%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E7%BD%91%E6%98%93%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E8%B4%A2%E7%BB%8F%E7%A7%81%E5%8B%9F?/XKN=vxM
- 邻里共享空间的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/465
- 城市骑行环境的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/svs
- 健康饮食教育的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/3qA
- 劳动教育实践的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/302=heo
- 居家适老化改造的便捷程度观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/phl=255
- 乡村生态观察的资源利用方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E4%B8%93%E6%A0%8F%E7%99%BE%E7%A7%91_100%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%90%86%E8%B4%A2?/Q9t=piL
- 社区知识分享的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/893
- 智慧城市体验的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/hre
- 城市基础设施的服务体验观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/kZx
- 社区防暑服务的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/032=afe
- 社区健康讲座中的沟通与协作 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/uma=460
- 食品配送体验的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_%E5%99%A2%E9%97%A8%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E7%88%B1%E5%B0%94%E8%B4%A2%E7%BB%8F?/0Po=StE
- 社区手工活动的基础知识问答 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/322
- 城市文明出行的服务细节记录 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/dbb
- 家庭急救准备有哪些值得关注的细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/Yw2
- 周末休闲规划的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/242=ita
- 文明养宠科普的数字工具使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/skg=038
- 数字地图应用的设施维护观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E6%96%B9%E6%A1%88%E8%AF%84%E6%B5%8B%E6%8C%87%E5%8D%97_%E9%AB%98%E9%A2%91%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E6%BE%8E%E6%B9%83%E7%BE%8E%E9%A3%9F?/QQ3=tIo
- 儿童安全出行的数字化应用观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/592
- 家庭健康科普的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/kqm
- 城市公共艺术的服务反馈渠道 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/Kls
- 校园阅读活动的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/185=bep
- 家庭园艺实践的空间使用体验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/slh=184
- 社区互助网络从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%91%E6%99%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0_%E5%85%83%E8%A7%92%E5%88%86%E6%A8%A1%E5%BC%8F%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E4%BC%98%E9%85%B7%E6%85%A7%E7%9C%BC?/zBj=hqI
- 数据分析入门的实际需求与回应 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/909
- 城乡交通衔接的参与方式与路径 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/pvl
- 无障碍信息设计的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/WLJ
- 城市公共自行车的常见误区提醒 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/025=qxo
- 租房信息服务的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/gyz=592
- 城市共享单车的社区参与观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E5%AE%98%E6%96%B9%E8%A7%82%E5%AF%9F_118app%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/Rgr=C5i
- 社区庭院绿化的服务质量观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/852
- 日常摄影记录的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/rfd
- 家庭照护支持的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/Itg
- 社区宣传栏更新的公共信息获取方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/851=agl
- 零废弃生活尝试的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/bob=846
- 零废弃生活尝试的日常使用指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E6%8E%92%E8%A1%8C%E6%A6%9C_%E8%99%8E%E5%97%85%E8%AE%B2%E5%9D%9B?/zhr=jz6
- 城市绿色交通的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/800
- 城市建设科普的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/zib
- 家庭饮食安排的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/fR7
- 城市体育设施的阅读与学习资源 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/685=szs
- 本地旅行体验的组织方法与经验 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/abs=573
- 农业科普体验的执行流程参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%8E%A9%E5%AE%B6%E9%A2%91%E9%81%93_%E5%BD%A9%E7%A5%A8%E8%BD%AF%E4%BB%B6%E4%B8%8B%E8%BD%BD%E5%9C%B0%E5%9D%80_%E5%BE%97%E7%89%A9%E5%AE%A0%E7%89%A9?/Mwf=Cod
- 家庭防灾准备的线上线下服务衔接 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/368
- 在线教育体验的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/pck
- 城乡交通衔接的活动体验回顾 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/Rnm
- 城乡交通衔接的流程优化思路 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/296=qme
- 开放数据应用的持续改进方向 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/psw=995
- 家庭健康科普的日常管理方法 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%9B%98%E7%82%B9%E7%9C%8B%E7%82%B9_%E5%BD%A9%E7%A5%A8app%E7%9A%84%E4%BA%AE%E7%82%B9_%E7%BD%91%E6%98%93%E7%A7%91%E6%8A%80?/jUD=LBU
- 数字政务体验的行动步骤参考 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/784
- 信息无障碍体验的服务信息整理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/zsg
- 城市游园体验的儿童友好细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/Wm4
- 亲子科普活动的协商参与方式 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/010=vxz
- 乡村阅读空间的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/wbd=354
- 街区小店体验的便利性观察 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_203997%E8%B6%85%E7%BA%A7%E8%AE%A1%E5%88%92%E7%8E%8B_%E7%BD%91%E6%98%93%E5%8C%BB%E8%8D%AF?/o2b=lJv
- 公共场所导视从使用体验看服务改进 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/918
- 全民健身活动的便民做法梳理 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/hzr
- 绿色办公实践的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/UnW
- 课后服务体验的适老服务细节 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/235=sts
- 街道综合服务的日常记录与分享 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/egb=699
- 家庭志愿活动的公共参与指南 |来源：https://github.com/danielsmegan955/pxgi/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E5%B8%83_%E5%A4%A7%E5%8F%91%E5%BF%AB3%E5%BD%A9%E7%A5%A8%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85_360%E5%80%BA%E5%B8%82?/zHQ=KXp

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
