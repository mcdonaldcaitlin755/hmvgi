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

- 基层健康服务的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/Um2
- 传统节日科普的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/581=ihn
- 绿色生活实践的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/ebj=235
- 社区共享书架的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A64%E7%A0%81%E5%80%8D%E6%8A%95%E6%9C%80%E7%AE%80%E5%8D%95%E6%96%B9%E6%B3%95_%E5%A5%A5%E5%9C%B0%E8%B4%A2%E7%BB%8F?/GXH=iZC
- 安全出行教育的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/210
- 绿色生活实践的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/exz
- 家庭园艺实践的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/rpG
- 社区教育资源的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/417=dvs
- 数字便民地图的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/pwd=791
- 老年运动活动的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E4%BA%86%E8%A7%A3_%E8%B5%9B%E8%BD%A67%E7%A0%81%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8%E5%9B%BE%E7%89%87_36%E6%B0%AA%E7%A4%BE%E8%AE%BA?/bRc=Bvz
- 绿色建筑理念的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/654
- 城市绿道建设的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/pqm
- 安全出行教育中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/Wan
- 家庭安全提示的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/222=jrm
- 社区公共议事中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/bje=405
- 农产品消费体验的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E5%B8%83_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A6%E7%A8%B3%E8%B5%A2%E6%8A%80%E5%B7%A7%E5%9B%BE%E7%89%87_%E4%BA%9A%E9%A9%AC%E9%80%8A%E8%A7%82%E5%AF%9F?/vaq=4xy
- 社区应急准备的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/412
- 社区教育资源的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/fpn
- 食品安全科普的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/uan
- 数字资源检索的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/763=iug
- 城市环境志愿行动的服务反馈渠道 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/spp=722
- 志愿服务平台的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5_pk10%E6%9C%80%E5%A5%BD%E7%9A%84%E6%89%93%E6%B3%95_%E6%96%B0%E6%B5%AA%E5%8D%83%E5%B8%86?/NO2=WXF
- 医院导诊服务的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/242
- 城市便民驿站的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/rqd
- 地方文化传播的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/kng
- 城市噪声观察的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/919=sfd
- 城市适老服务的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/wzh=315
- 城市博物馆服务有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E7%99%BE%E7%A7%91_%E6%9E%81%E9%80%9F%E8%B5%9B%E8%BD%A65%E7%A0%818%E6%9C%9F%E8%AE%A1%E5%88%92%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E7%88%B1%E5%A5%87%E8%89%BA%E6%96%87%E6%91%98?/DNd=NRL
- 乡村休闲旅游的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/270
- 数字艺术创作的学习资源整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/dsh
- 科学信息获取的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/gPI
- 社区庭院绿化的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/791=vlu
- 校园节能行动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/rzn=776
- 城市建设科普的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E6%88%98%E6%8C%87%E5%8D%97_%E8%B5%9B%E8%BD%A63%E7%A0%81%E6%80%8E%E4%B9%88%E5%80%8D%E6%8A%95_%E5%BE%97%E7%89%A9%E5%AE%B6%E5%B1%85?/oAz=Mk2
- 青少年户外教育的社区参与观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/696
- 乡村阅读活动的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/fjd
- 职业技能学习中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/AyM
- 图书馆亲子空间有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/701=lcd
- 家庭节能实践的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/tbz=703
- 家庭防灾准备的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%A0%B8%E5%BF%83%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7_%E5%87%A4%E5%87%B0%E9%9F%B3%E4%B9%90?/PwV=Avf
- 网络信息辨识的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/566
- 街区道路维护的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/cbf
- 家庭安全提示的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/TBa
- 城市慢行系统的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/409=gyy
- 社区心理支持从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/gcj=892
- 文化讲座服务中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95_%E7%95%8C%E9%9D%A2%E5%9B%BE%E9%9B%86?/2yY=yYA
- 家庭安全提示的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/592
- 科学信息获取的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/dqq
- 社区消防演练的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/Lr3
- 家庭收纳实践的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/571=nrt
- 家庭园艺实践的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/jhb=488
- 城市人文观察的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E7%88%86%E6%96%99_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E5%88%92%E8%A1%A8_%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%8E%A2%E5%BA%97?/jdE=jPa
- 个人信息保护的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/962
- 家庭健康管理的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/wou
- 家庭健康科普的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/Ccu
- 农贸市场环境的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/889=jxz
- 城市噪声观察的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/mlk=093
- 科学健身方法的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E5%89%8D%E7%9E%BB_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%8E%A8%E8%8D%90_36%E6%B0%AA%E6%96%B0%E9%97%BB?/tAb=uKy
- 城市休闲步道的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/858
- 农业科普体验的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/tke
- 家庭饮食安排的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/LZH
- 个人时间管理的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/555=oos
- 公共服务预约的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/eun=964
- 社区心理支持的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%B2%BE%E9%80%89%E9%A2%91%E9%81%93_%E5%BF%AB%E4%B9%908%E5%A4%9A%E5%80%8D%E6%8A%95%E6%B3%A8_%E4%BA%AC%E4%B8%9C%E7%9B%B4%E6%92%AD?/5KZ=djn
- 公共设施使用的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/260
- 社区环保活动的活动体验回顾 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/rcg
- 城市步行环境的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/IMF
- 青少年户外教育的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/261=jdw
- 社区法律科普的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/ybl=913
- 职业技能学习的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E8%B4%A2%E7%BB%8F%E4%B8%80%E5%88%86%E9%92%9F%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E4%B8%AD%E5%A5%96_%E9%9B%85%E8%99%8E%E5%9F%8E%E4%BA%8B?/ZQ9=x5s
- 科技馆参观体验的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/425
- 社区慢性病防控的数字工具使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/vdv
- 乡村文化空间的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/Vxv
- 社区交通安全的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/235=aot
- 旧物循环利用的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/gig=565
- 城市可持续生活的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E8%81%9A%E7%84%A6_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E7%8E%A9%E6%B3%95%E8%AE%A1%E7%AE%97_%E4%BA%AC%E4%B8%9C%E5%9B%AD%E8%89%BA?/PDr=all
- 城市基础设施的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/570
- 音乐欣赏活动的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/oyw
- 城市休闲步道的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/lZ4
- 创业经验分享的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/356=ywy
- 节能生活方式的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/ypg=563
- 公共场馆服务的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908-%E5%80%8D%E6%8A%95_%E7%BD%91%E6%98%93%E5%8F%B8%E6%B3%95?/gRL=yB2
- 社区便利生活的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/124
- 农村环境治理的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/aff
- 城市公共艺术从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/QtO
- 城市体育设施的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/549=moh
- 城市地名文化有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/ogh=258
- 数字创意课程中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%BD%A9%E6%B0%91%E8%AE%A8%E8%AE%BA_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E8%AE%A1%E7%AE%97_%E5%A4%B4%E6%9D%A1%E6%99%9A%E6%8A%A5?/2C0=jtS
- 本地消费场景的空间设计要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/029
- 公交站点体验的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/jke
- 社区活动空间的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/LlC
- 老年学习活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/249=adk
- 节能家电使用的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/bvz=321
- 节能生活方式的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E6%A0%8F%E7%9B%AE_%E5%BF%AB%E4%B9%908%E5%8D%95%E5%8F%B7%E5%80%8D%E6%8A%95_%E5%86%85%E9%99%86%E8%B4%A2%E7%BB%8F?/dRu=XO9
- 社区心理支持的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/688
- 城市公共饮水的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/wtj
- 数字创意课程的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/EAX
- 跨代沟通活动的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/949=ohm
- 公园休闲体验的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/rde=834
- 科普展览体验的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E5%8F%91%E7%8E%B0_%E7%A6%8F%E5%BD%A9%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95_%E8%84%89%E8%84%89%E5%AE%B6%E7%94%B5?/nX8=iiX
- 社区邻里服务的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/963
- 绿色消费选择的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/iub
- 数字地图应用的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/Um6
- 课后服务体验的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/400=vui
- 社区儿童活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/kjg=594
- 科学观察活动的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E5%8A%A8%E6%80%81_%E5%BF%AB%E4%B9%908%E6%9C%80%E7%A8%B3%E7%9A%84%E8%B5%9A%E9%92%B1%E6%96%B9%E6%B3%95_%E8%B1%86%E7%93%A3%E5%8C%BB%E8%8D%AF?/wcU=4sI
- 信息无障碍体验的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/021
- 文化场馆预约的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/bob
- 安全出行教育的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/I3V
- 绿色生活实践的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/521=inx
- 智慧停车服务有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/low=081
- 公共交通接驳的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%99%AE%E5%8F%8A%E5%8F%91%E7%8E%B0_%E5%BF%AB%E4%B9%908%E6%8A%80%E5%B7%A7%E5%87%86%E7%A1%AE%E7%8E%87100%25_%E7%88%B1%E5%A5%87%E8%89%BA%E6%AF%8D%E5%A9%B4?/LgA=IxL
- 城市微更新实践中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/558
- 节假日出行安排的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/jnm
- 亲子阅读活动的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/nRb
- 软件开发学习的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/287=rbq
- 地方戏曲体验中的沟通与协作 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/fce=782
- 社区艺术活动的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E8%AE%A8%E8%AE%BA_%E7%A6%8F%E5%BD%A9%E5%BF%AB8%E7%9C%9F%E5%AE%83%E5%A6%88%E4%B8%AA%E5%9D%91%E4%BA%BA_%E9%9B%85%E8%99%8E%E5%9B%BD%E5%86%85?/Ye6=hgs
- 市民意见收集的社区行动案例 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/681
- 开源技术交流的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/tup
- 健康步道使用的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/kMZ
- 社区读书角建设从使用体验看服务改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/911=wwb
- 节假日出行安排的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/cst=250
- 旧物循环利用的常见问题梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E7%99%BE%E7%A7%91_%E5%BF%AB%E4%B9%908%E9%80%892%E7%A8%B3%E8%B5%9A%E4%B8%8D%E8%B5%94%E8%AE%A1%E5%88%92_%E5%93%94%E5%93%A9%E5%9B%9E%E6%94%BE?/D6k=bUP
- 网络安全教育有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/901
- 网络信息辨识的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/btr
- 开放数据应用的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/v9r
- 社区便民服务从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/226=mib
- 社区花园共建的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/ocb=513
- 基层服务创新的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E9%87%8D%E5%A4%A7%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E5%BF%AB%E4%B9%908%E5%BF%85%E8%B5%9A%E6%96%B9%E6%B3%95_%E8%8A%92%E6%9E%9C%E7%88%86%E6%96%99?/KYe=EhV
- 乡村生态观察的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/183
- 家庭运动计划的入门知识整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/ihg
- 节能家电使用的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/ZxH
- 城市公共座椅的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/715=qml
- 小区电梯维护的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/vck=124
- 城市适老服务中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%AC%AC%E4%B8%80%E5%8A%A8%E6%80%81_%E5%85%AB%E7%A0%81%E4%BA%8C%E6%9C%9F%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E5%93%94%E5%93%A9%E8%82%A1%E7%A5%A8?/66p=Jwv
- 社区运动空间的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/702
- 环境教育课程的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/xvv
- 数字阅读服务的基础知识问答 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/Vx4
- 家庭健康科普的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/573=qfc
- 乡村电商实践的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/kdn=123
- 家庭健康管理的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%99%AE%E5%8F%8A%E7%9F%A5%E9%81%93_%E5%BF%AB%E4%B9%908%E5%8D%81%E6%8B%BF%E4%B9%9D%E7%A8%B3%E9%A2%84%E6%B5%8B%E6%9C%80%E5%87%86_%E5%87%A4%E5%87%B0%E5%86%9C%E4%B8%9A?/ezP=AbX
- 城市应急科普的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/515
- 社区慢性病防控的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/jjk
- 科技馆参观体验的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/2pw
- 智慧停车服务的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/193=okx
- 城市游园体验的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/whd=265
- 乡村公共文化从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E7%9C%8B%E7%82%B9_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E7%9A%84%E5%82%BB%E5%8F%BC_%E6%96%B0%E6%B5%AA%E5%BD%B1%E8%A7%86?/PP5=Tne
- 城市夜间照明的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/254
- 口袋公园建设的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/itp
- 社区文化传播的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/iDQ
- 数字地图应用的线下体验记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/685=pqu
- 城市生活服务的安全使用提示 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/ezm=459
- 城乡交通衔接的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E7%8E%8B%E7%89%8C_%E5%BF%AB%E4%B9%908%E9%80%89%E4%BA%94%E9%80%89%E5%85%AD%E5%93%AA%E4%B8%AA%E5%AE%B9%E6%98%93%E4%B8%AD_%E7%9F%A5%E4%B9%8E%E4%BF%A1%E8%AE%BF?/nhG=dfU
- 社区活动策划的日常记录与分享 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/185
- 绿色快递包装有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/poi
- 城市游园体验的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/xee
- 社区知识分享的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/928=mxj
- 科技馆参观体验的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/brs=962
- 口袋公园建设的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91_%E5%BD%A9%E7%A5%A8%E5%BF%AB%E4%B9%908%E7%8E%84%E5%AD%A6%E7%AE%97%E6%B3%95_%E6%90%9C%E7%8B%90%E6%96%87%E5%8C%96?/8G0=LdP
- 老年人日常照护的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/520
- 终身学习资源的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/swr
- 志愿服务平台的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/tQt
- 个人信息保护的阅读与学习资源 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/923=zwo
- 电子商务服务的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/mdu=172
- 家庭园艺实践的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E5%AE%98%E6%96%B9%E7%AE%80%E6%8A%A5_%E5%BF%AB%E4%B9%908%E9%80%89%E4%B8%89%E6%9C%80%E4%BD%B3%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E9%87%91%E8%AF%9A%E8%B4%A2%E7%BB%8F?/r5I=gEV
- 市民意见收集的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/161
- 青少年户外教育的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/uik
- 气象科普传播的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/Bov
- 数字素养提升的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/373=ipn
- 城市文明出行的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/jgc=474
- 社区垃圾分类的便捷程度观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E9%87%8D%E5%A4%A7%E6%8E%A2%E8%AE%A8_%E5%BF%AB%E4%B9%908%E4%B8%80%E7%A0%81%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88%E8%A1%A8_%E5%A4%B4%E6%9D%A1%E7%88%86%E6%96%99?/LFL=AR6
- 地方民俗记录的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/630
- 健康饮水科普的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/etp
- 日常摄影记录的参与方式与路径 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/42H
- 社区儿童活动的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/390=swo
- 生活技能分享的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/rdn=774
- 城乡交通衔接的设施维护观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E6%95%B0%E6%8D%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%90%E5%85%AB%E9%80%89%E4%BA%8C%E5%80%8D%E6%8A%95%E6%96%B9%E6%A1%88_%E5%BF%AB%E6%89%8B%E6%AF%8D%E5%A9%B4?/Bn1=ISg
- 公交无障碍服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/549
- 绿色消费选择的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/sek
- 社区养老服务的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/cF8
- 人工智能科普的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/123=npr
- 社区运动空间的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/zaf=004
- 老年友好服务的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E9%A3%8E%E5%90%91_%E5%BF%AB%E4%B9%908%E9%80%82%E5%90%88%E5%80%8D%E6%8A%95%E7%9A%84%E7%8E%A9%E6%B3%95_%E4%BA%AC%E4%B8%9C%E5%9B%BD%E5%86%85?/R3w=aKd
- 公园休闲体验的线上线下服务衔接 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/719
- 家庭阅读计划中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/xsk
- 学校食育活动的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/pM4
- 家庭消费规划的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/381=lav
- 应急物资管理的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/jho=342
- 城市应急广播的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%A7%91%E6%99%AE%E7%BB%8F%E9%AA%8C_%E5%BF%AB%E4%B9%908%E5%80%8D%E6%8A%95%E5%AE%88%E5%8F%B7%E6%9C%80%E7%A8%B3%E7%9A%84%E6%89%93%E6%B3%95_%E6%BE%8E%E6%B9%83%E6%8A%95%E7%A8%BF?/rfm=4cL
- 社区手工活动的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/162
- 城市社区治理的资源整合思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/fln
- 老年友好服务的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/5tp
- 运动安全知识的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/823=jox
- 数字创作工具的服务体验观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/hqz=738
- 绿色生活实践的服务细节记录 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E7%AE%80%E6%8A%A5_%E5%80%8D%E6%8A%95%E6%8A%80%E5%B7%A7%E8%AE%A9%E4%BD%A0%E4%B8%8D%E5%86%8D%E8%BE%93%E9%92%B1%E7%9A%84%E5%8E%9F%E5%9B%A0_%E4%B8%96%E7%95%8C%E8%B4%A2%E7%BB%8F?/2w3=XZC
- 社区菜市场服务的服务质量观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/809
- 绿色校园实践的基础设施观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/fbc
- 线上阅读资源的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/00b
- 公共服务指南有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/195=gjq
- 急救知识普及的活动策划思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/ezc=337
- 节假日出行安排中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%9B%98%E7%82%B9%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%B3%95_%E8%85%BE%E8%AE%AF%E6%89%8B%E8%AE%B0?/KY8=URf
- 小区电梯维护的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/487
- 个人时间管理的流程优化思路 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/amk
- 绿色出行服务的便利性观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/u6j
- 本地历史资料的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/438=jel
- 城市可持续生活的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/mti=532
- 家庭照护支持有哪些值得关注的细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E5%BD%A9%E6%B0%91%E4%BC%98%E9%80%89%E6%8E%A8%E8%8D%90_%E5%80%8D%E6%8A%95%E7%9A%84%E6%96%B9%E6%B3%95%E5%8F%AF%E8%A1%8C%E5%90%97_%E5%A4%AE%E8%A7%86%E7%83%AD%E6%A6%9C?/xfM=Owe
- 社区便民服务的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/676
- 社区便利生活的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/ckd
- 乡村文化活动的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/zbF
- 本地历史资料的实际需求与回应 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/322=arq
- 公园无障碍服务的日常使用指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/sxw=239
- 信息无障碍体验的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%A7%92%E6%87%82%E8%AE%A8%E8%AE%BA_%E5%80%8D%E6%8A%95%E6%9C%80%E6%9C%89%E6%95%88%E6%9C%80%E7%9B%B4%E6%8E%A5%E7%9A%84%E6%96%B9%E6%B3%95_%E5%90%AF%E7%91%9E%E8%B4%A2%E7%BB%8F?/ExP=ufx
- 公共卫生设施的儿童友好细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/555
- 街头绿植养护的组织方法与经验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/jvp
- 儿童友好空间的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/wXY
- 农产品品牌传播的居民参与机会 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/372=ddj
- 城市文化路线的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/hqq=527
- 文明养宠科普的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%A0%B8%E5%BF%83%E9%A2%91%E9%81%93_%E5%80%8D%E6%8A%956%E7%A7%8D%E6%96%B9%E6%B3%95_%E6%BE%8E%E6%B9%83%E5%9C%88%E5%AD%90?/rE2=0Ly
- 非遗体验活动的协商参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/686
- 社区公共卫生的空间使用体验 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/shb
- 科学观察活动的日常实践笔记 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/kG4
- 青少年编程学习中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/161=rbl
- 社区运动空间的绿色实践方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/aeg=560
- 公共场馆服务的长期维护要点 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E7%8E%A9%E5%AE%B6%E8%A7%84%E5%88%92_%E5%80%8D%E6%8A%95%E6%96%B9%E5%BC%8F%E5%A4%A7%E5%85%A8_%E8%99%8E%E5%97%85%E6%B0%91%E7%94%9F?/idI=Zny
- 志愿服务平台的行动步骤参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/663
- 公共空间照明的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/jzf
- 城市公共厕所的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/HQu
- 公共交通信息服务的家庭参与方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/665=acy
- 智慧城市体验的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/myn=071
- 家庭收纳实践的公共参与指南 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%8E%A9%E5%AE%B6%E4%BA%86%E8%A7%A3_%E5%80%8D%E6%8A%95%E6%9C%80%E7%A7%91%E5%AD%A6%E7%9A%84%E6%96%B9%E6%B3%95_%E5%A4%B4%E6%9D%A1%E5%81%A5%E8%BA%AB?/ueg=XFZ
- 居民健康教育的实用信息清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/584
- 社区设施共享的持续改进方向 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/fmm
- 城市绿色交通的使用门槛与改进 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/2U6
- 公共健身器材的协作机制梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/714=hal
- 在线学习体验的服务范围梳理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/gaf=973
- 社会体育指导的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E4%B8%93%E6%A0%8F%E6%A0%8F%E7%9B%AE_%E5%87%A0%E7%A7%8D%E5%B8%B8%E8%A7%81%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95%2C%E4%B8%80%E4%B8%AA%E6%96%B9%E6%B3%95%E8%AE%A9%E5%80%8D%E6%8A%95%E5%8F%98%E5%BE%97%E5%AE%89%E5%85%A8_%E7%9F%A5%E4%B9%8E%E5%88%9B%E6%8A%95?/lwA=nOH
- 社区花园共建的常见误区提醒 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/092
- 家庭环保行动的活动组织技巧 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/cin
- 社区消防演练的资源利用方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/Awf
- 校园阅读活动的服务信息整理 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/952=wle
- 志愿者培训交流的日常管理方法 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/zge=590
- 儿童友好空间从需求出发看服务设计 |来源：https://github.com/tannernancy4533/crsu/wiki/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97_%E6%9C%80%E5%A5%BD%E7%9A%84%E5%80%8D%E6%8A%95%E6%96%B9%E6%B3%95_%E8%84%89%E8%84%89%E6%B3%95%E5%BE%8B?/R7H=2NS
- 城市骑行环境的适老服务细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/234
- 社区宣传栏更新的数字化应用观察 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/sxo
- 城市慢行系统中的几个关键细节 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/v2t
- 城市应急科普的公共信息获取方式 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/889=nlj
- 社区便利生活的家庭实践清单 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/oea=961
- 智慧停车服务的执行流程参考 |来源：https://github.com/tannernancy4533/crsu/wiki/2027%E6%95%B0%E6%8D%AE%E8%81%9A%E7%84%A6_3000%E6%9C%AC%E9%87%91%E5%80%8D%E6%8A%95_%E5%93%94%E5%93%A9%E6%94%BF%E7%AD%96?/apU=kSC

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
