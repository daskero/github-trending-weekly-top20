# GitHub Trending 周榜监测报告

> **监测周期**：2026-08-25 ~ 2026-08-31（周榜）
> **数据来源**：GitHub Trending 官方页面（全语言周榜，共采集 20 个条目，已满足 Top 20 需求，无需语言榜补量；Python/Go 语言榜作为附录补充观察）
> **采集方式**：WebFetch 抓取官方页面两次交叉验证，数据一致

---

## 一、本周 Top 20 榜单（按本周新增 Star 降序）

| 排名 | 仓库 | 总 Star | 本周新增 | 语言 | 简介 |
|:---:|:---|---:|---:|:---:|:---|
| 1 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 37,171 | **+18,103** | JavaScript | Agent skill：生成架构图/工作流/时序图/数据流图，自包含 HTML + 动效 + 高清导出 |
| 2 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | 26,215 | **+13,413** | JavaScript | Prompt as Code \| GPT-Image2 工业级提示词引擎与模板库，530+ 案例逆向工程，20+ 工业级模板 |
| 3 | [omacom/omarchy](https://github.com/omacom/omarchy) | 35,918 | +6,692 | Shell | Beautiful, Modern & Opinionated Linux（极简现代 Arch Linux 发行版） |
| 4 | [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search) | 38,893 | +5,348 | Python | 本地运行的 AI 求职框架（基于 Claude Code）：评估 JD、定制简历、写求职信、面试准备 |
| 5 | [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 40,415 | +4,309 | Python | 把任意 AI Agent 变成 AI 科学家：165 个验证过的科学 Skills + 100+ 科研数据库，19 万科研人员在用 |
| 6 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | 51,508 | +3,720 | Python | AI 工程从零学起：Learn it. Build it. Ship it for others. |
| 7 | [AprilNEA/OpenLogi](https://github.com/AprilNEA/OpenLogi) | 18,062 | +3,406 | Rust | Logitech Options+ 的原生本地替代品：按键重映射/DPI/SmartShift，无账号无遥测 |
| 8 | [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) | 23,209 | +3,037 | TypeScript | 34 个免费 LLM 供应商、635 个免费模型端点统一到一个 /v1 端点，智能路由 + 自动故障转移 |
| 9 | [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | 39,148 | +2,526 | Rust | 个人 AI 超级智能：本地优先的生活记忆库 + agent 舰队编排器 + 深度研究器 |
| 10 | [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) | 3,001 | +2,162 | Python | Claude Cowork / Claude Code 社区插件市场（官方只读镜像） |
| 11 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 25,979 | +2,085 | TypeScript | 清华开源多 Agent 互动课堂：一键获得沉浸式多 Agent 学习体验 |
| 12 | [apache/maka](https://github.com/apache/maka) | 4,286 | +1,973 | TypeScript | Apache Maka（孵化中）：本地优先 AI Agent 工作区，消息/工具调用/权限决策以 append-only 日志记录 |
| 13 | [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) | 35,702 | +1,940 | Python | Anthropic 官方维护的高质量 Claude Code 插件目录 |
| 14 | [abi/screenshot-to-code](https://github.com/abi/screenshot-to-code) | 76,612 | +1,909 | Python | 截图转代码（HTML/Tailwind/React/Vue） |
| 15 | [every-app/open-seo](https://github.com/every-app/open-seo) | 15,534 | +1,881 | TypeScript | Semrush / Ahrefs 的开源替代品 |
| 16 | [cursor/plugins](https://github.com/cursor/plugins) | 6,335 | +1,503 | TypeScript | Cursor 插件规范与官方插件 |
| 17 | [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | 11,873 | +1,222 | CSS | ConardLi 开源 Skills 集合：网页设计、知识检索、图像生成等 |
| 18 | [asciimoo/hister](https://github.com/asciimoo/hister) | 3,386 | +1,006 | Go | 你自己的搜索引擎 |
| 19 | [p-e-w/heretic](https://github.com/p-e-w/heretic) | 29,465 | +992 | Python | 全自动移除语言模型审查（uncensor） |
| 20 | [google/googletest](https://github.com/google/googletest) | 39,401 | +441 | C++ | GoogleTest - Google 测试与 Mock 框架 |

**语言分布**：Python 7 ｜ TypeScript 5 ｜ JavaScript 2 ｜ Rust 2 ｜ Shell / C++ / CSS / Go 各 1

---

## 二、本周技术趋势解读

### 主题一：AI Agent 生态全面接管榜单（13/20 与 AI/Agent 直接相关）

本周最显著的事实：**20 个上榜项目中 13 个与 AI Agent / LLM 直接相关，其中 9 个紧密围绕 AI 编程工具生态**——Claude 官方插件目录（#10、#13）、社区插件市场、Cursor 插件规范（#16）、Agent Skills 库（#1、#5、#17）、Agent 工作区（#12）、基于 Claude Code 的求职框架（#4）。编程工具的"插件化 + Skills 化"已从概念验证走向生态爆发，头部厂商（Anthropic、Cursor、Apache 基金会）均在抢建分发入口。

### 主题二："Skills / Prompt as Code" 成为新范式

冠军 archify（周增 18,103）本质是一个 Agent Skill——让 AI 编程助手学会画专业架构图；亚军 awesome-gpt-image-2 直接打出 "Prompt as Code" 旗号，把提示词当代码工程化管理（逆向工程 530+ 案例）。**"可复用、可版本化、可分发的提示词资产"正在成为独立的技术品类**，而非散落在 README 里的技巧。

### 主题三：local-first 与数据主权回归

maka（append-only 日志记录一切 Agent 行为）、openhuman（本地记忆库）、OpenLogi（无账号无遥测）、ai-job-search（数据不出本机）、hister（自建搜索引擎）——用户对"AI 便利 vs 数据外流"的权衡开始反向发酵，**"本地优先 + 隐私优先"成为 AI 应用的新卖点**。

### 主题四：开源替代商业软件浪潮持续

open-seo（替代 Semrush/Ahrefs，周增 1,881）、OpenLogi（替代罗技 Options+）、hister（替代谷歌式搜索）。AI 降低了复杂软件的开发门槛，垂直领域"平替"项目将持续涌现。

### 风向小结

- **风向 1**：Agent Skills 生态位 = 早期的 npm / VS Code 插件市场，先发者享受红利窗口
- **风向 2**：TypeScript 占全语言榜 25%，仍是 AI 应用层默认语言；Python 靠 AI 工程/科研保持存在感；Rust 在系统级 AI 工具（本地推理、外设管理）稳步渗透
- **风向 3**：Go 的热点集中在 AI 网关/模型路由（见附录），Go + LLM 基础设施是明确赛道

---

## 三、亮点项目点评

### 1. tt-a1i/archify —— 周增 18,103 星登顶，"给 AI 编程助手装上画图技能"

一个 Agent Skill 就拿下全站周榜第一，信号意义极强：它验证了 **Skills 作为独立发布单元的商业/传播价值**。功能上，它生成架构图、工作流、时序图、数据流图和生命周期图，输出自包含 HTML（带动效）并支持高清导出。对于需要频繁输出系统设计文档的团队，这类 Skill 可直接嵌入 Claude Code / Cursor 工作流，替代 draw.io 的手工绘图环节。**周增 18k 相当于第二名的 1.35 倍，是本周毫无争议的现象级项目。**

### 2. freestylefly/awesome-gpt-image-2 —— 周增 13,413 星，国产"提示词工程化"代表作

国内开发者作品，方法论清晰：对 GPT-Image2 的 530+ 个生成案例做逆向工程，提炼出 20+ 套工业级模板和可复用 Skills，持续更新。它的价值不在单个提示词，而在**把"文生图调优"从玄学变成可版本管理的工程资产**——这正是国内落地页/营销素材生产链条最缺的一环。对做图片批量生成、营销视觉标准化的团队，这是一个现成的方法论库。

### 3. asciimoo/hister —— 周增 1,006 星，增速比最高的"潜伏者"

Go 语言项目，定位"你自己的搜索引擎"。值得注意两点：其一，作者 asciimoo 是老牌元搜索引擎 **searx 的原作者**，在隐私搜索领域有深厚积累；其二，总 Star 仅 3,386 而周增 1,006——**"本周新增/总量"高达 29.7%，是全榜单早期爆发力最强的项目**（对比：archify 该比值为 48.7% 但体量已大，hister 属于刚起飞阶段）。对于需要多源数据聚合检索的场景，这个项目值得在早期就跟踪其架构演进。

---

## 四、技术选型建议（结合 Python / Go / Vue3 / PHP 技术栈）

### Python（爬虫 / FastAPI / Flask 场景）

- **直接可借鉴**：Python 周榜被 Claude Code 生态刷屏（约 9/20 相关）。`ai-engineering-from-scratch`（51.5k 总星）适合作为 AI 工程体系化学习主线；`scientific-agent-skills` 的 165 个验证过的 Skills 结构（兼容 Cursor / Claude Code / Codex / 开放 Agent Skills 标准）可作为自建 Skill 库的参考蓝本。
- **落地建议**：现有爬虫项目（小红书/抖音/拍卖）可演进为"爬取 + LLM 分析"两段式 agent workflow——爬虫产出结构化数据，LLM 层做摘要/分类/监控告警；文章处理 API（Flask）同理，叠加 LLM 管线成本低、收益直接。

### Go（企业微信会话存档 / 后端服务场景）

- **风向明确**：Go 周榜 Top3 中的 `workweave/router`（智能体模型路由器，50ms 内路由请求、宣称降本 40-70%，周增 2,053）与 `QuantumNous/new-api`（46.9k 星，LLM 聚合网关）、`Tencent/WeKnora`（21k 星，RAG 知识平台）共同指向 **"Go + LLM 基础设施"赛道**。
- **落地建议**：会话存档项目积累的聊天数据 + RAG 是天然组合——会话存档（数据采集层）→ 知识库构建（RAG 层）→ 智能问答/销售辅助（应用层），这正是简化 SCRM 项目的差异化方向；模型路由/网关层则适合统一管理多 LLM 调用、控制成本。

### Vue3（落地页编辑器 / 前端场景）

- **直接相关**：`abi/screenshot-to-code`（76.6k 总星，本周仍在涨 1,909）支持输出 **Vue** 代码。落地页编辑器（LandingPageEditView / CustomPage / 名片板块）可评估集成其能力，实现"参考截图 → 生成初版页面 → 人工微调"的制作流，显著降低模板制作成本。
- **观察参考**：`THU-MAIC/OpenMAIC`（清华，多 Agent 互动课堂）的交互式 Agent UI 值得拆解——多角色对话流、流式渲染、状态编排这些组件模式可迁移到聊天式落地页（QAFormView）的增强上。

### PHP（CRM / Layui 场景）

- **需要正视**：本周全语言 Top 20 中 **PHP 项目为零**（语言榜亦未见踪影），PHP 在新兴 AI Agent 生态中缺席明显。
- **落地建议**：CRM 的智能化不必强求 PHP 生态内闭环，走 **"PHP 业务层 + Python/Go AI 服务"混合架构**更务实——PHP 继续承担订单/退款/签约等强事务逻辑，AI 能力（智能客服、会话质检、线索评分）以独立微服务输出，通过 MQ/Webhook 解耦（现有 RabbitMQ 基础可直接复用）。文章处理 API（Flask）实际上已是这个模式的雏形。

---

## 附录：语言榜补充观察（Python / Go 周榜精选）

> 全语言页面已采集满 20 条，以下为补充抓取的语言周榜数据节选，用于趋势交叉验证。

**Python 周榜值得关注的补充项目**：calesthio/OpenMontage（开源 agentic 视频生产系统，周增 4,974）、Alishahryar1/free-claude-code（免费 Claude Code/Codex 接入，周增 4,324）、AgriciDaniel/claude-obsidian（Obsidian + Claude 自组织第二大脑，周增 3,156）、jingyaogong/minimind（2 小时从零训练 64M 参数 LLM，总星 55.8k）、pipecat-ai/pipecat（语音 Agent 框架）。

**Go 周榜值得关注的补充项目**：workweave/router（智能体模型路由器，周增 2,053，全周增第一）、QuantumNous/new-api（LLM 聚合网关，周增 862）、Tencent/WeKnora（RAG 知识平台，周增 553）、MHSanaei/3x-ui（多协议代理面板，周增 493）。Go 榜国产项目活跃：WeKnora、1Panel、new-api、higress、certimate 等。

---

*数据来源：GitHub Trending 官方页面 · 抓取时间：2026-08-31 22:27*

历史记录：

[2026年8月17日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-8%E6%9C%8817%E6%97%A5.md) |

[2026年8月24日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-8%E6%9C%8824%E6%97%A5.md) |
