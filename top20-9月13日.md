# GitHub Trending 周榜报告（2026-09-07 ~ 2026-09-13）

> 抓取方式：GitHub Trending 官方 weekly 页面（WebFetch + curl/HTML 解析交叉验证，23 个条目全部采集，去重后按本周新增 star 降序取 Top 20）

## 一、本周 Top 20 榜单

| 排名 | 仓库 | 总 Star | 本周新增 | 语言 | 简介 |
|---|---|---|---|---|---|
| 1 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | 43,840 | +15,924 | Python | 防止编码智能体"把答案埋起来"的 Skill，ADHD 友好输出 |
| 2 | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) | 31,031 | +10,510 | JavaScript | 浏览器里的间谍卫星模拟器，数据真实，照片级 3D 地球上的开源空间情报 |
| 3 | [tt-a1i/archify](https://github.com/tt-a1i/archify) | 60,218 | +10,442 | JavaScript | 生成美观可验证的架构/流程/时序/数据流/生命周期图的 Agent Skill，自包含 HTML + 动效导出 |
| 4 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 136,971 | +9,272 | JavaScript | 让 AI 智能体像"最懒的资深工程师"一样思考——最好的代码是你没写的代码 |
| 5 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 257,434 | +8,086 | JavaScript | 智能体 Harness 性能优化系统：Skills、直觉、记忆、安全与研究优先开发，适配 Claude Code/Codex/Cursor |
| 6 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | 39,042 | +7,409 | HTML | 38 种编辑级图表样式，自包含 HTML + SVG，拒绝"Mermaid 垃圾感" |
| 7 | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | 49,338 | +5,124 | TypeScript | 写 HTML 渲染视频，为智能体而生 |
| 8 | [microsoft/markitdown](https://github.com/microsoft/markitdown) | 183,436 | +4,823 | Python | 微软出品的文件/Office 文档转 Markdown 工具 |
| 9 | [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | 36,343 | +4,417 | TypeScript | 清华开源多智能体互动课堂，一键沉浸式多 Agent 学习体验 |
| 10 | [blader/humanizer](https://github.com/blader/humanizer) | 47,505 | +4,069 | Python | 去除文本中 AI 生成痕迹的 Agent Skill |
| 11 | [obra/superpowers](https://github.com/obra/superpowers) | 286,013 | +3,938 | Shell | 智能体 Skills 框架与软件开发方法论 |
| 12 | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 49,898 | +2,822 | JavaScript | 面向 Claude Code 的营销 Skills：CRO、文案、SEO、分析、增长工程 |
| 13 | [github/spec-kit](https://github.com/github/spec-kit) | 136,174 | +2,501 | Python | GitHub 官方规格驱动开发（Spec-Driven Development）工具包 |
| 14 | [mksglu/context-mode](https://github.com/mksglu/context-mode) | 22,513 | +1,936 | TypeScript | AI 编码智能体的上下文窗口优化：沙箱化工具输出（降噪 98%）、会话记忆持久化、跨 17 平台路由（MCP + hooks） |
| 15 | [openai/skills](https://github.com/openai/skills) | 27,054 | +1,579 | Python | OpenAI Codex 官方 Skills 目录 |
| 16 | [humanlayer/skills](https://github.com/humanlayer/skills) | 3,951 | +1,380 | TypeScript | Humanlayer 的智能体 Skills 集合（官方未提供描述） |
| 17 | [petergyang/no-ai-slop](https://github.com/petergyang/no-ai-slop) | 8,965 | +1,307 | Python | 清除写作中 20+ 种"AI 味"模式 |
| 18 | [Tencent/WeKnora](https://github.com/Tencent/WeKnora) | 22,776 | +1,168 | Go | 腾讯开源 LLM 知识平台：原始文档 → 可查询 RAG、自主推理 Agent、自维护 Wiki |
| 19 | [openai/plugins](https://github.com/openai/plugins) | 6,577 | +1,120 | JavaScript | OpenAI 官方 Plugins |
| 20 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | 15,507 | +1,011 | Python | 面向 CAD/CAE/CAM 的智能体 Skills 库 |

（未进 Top 20：ChromeDevTools/chrome-devtools-mcp +783、kunchenguid/firstmate +763、max-sixty/worktrunk +257）

**语言分布（Top 20）**：Python 7 席 · JavaScript 5 席 · TypeScript 4 席 · Shell 1 席 · Go 1 席 · HTML 1 席

## 二、本周技术趋势解读

**1. "Agent Skills" 已从概念变成一个完整的赛道。** Top 20 中至少 11 个项目直接是 Agent Skill / Skills 框架（i-have-adhd、archify、ponytail、ECC、diagram-design、superpowers、marketingskills、humanizer、humanlayer/skills、no-ai-slop、text-to-cad、openai/skills）。Skill 的形态高度统一：给 Claude Code / Codex / Cursor 等编码智能体注入"领域方法论"，而不是写一个传统应用。这说明智能体生态的竞争焦点已从"更强的模型"转移到"更好的工程化配套"。

**2. OpenAI 官方下场，Skills/Plugins 生态标准化。** openai/skills（Codex Skills 目录）和 openai/plugins 同时上榜，标志着 Skills 这种"给智能体外挂方法论"的形态获得了头部厂商的官方背书，预计会催生类似"App Store"的分发生态。

**3. 反 AI 味 / 输出质量控制成为独立需求。** i-have-adhd（+15.9k 居首）、humanizer、no-ai-slop、diagram-design（"No Mermaid slop"）都在解决同一个问题：AI 输出太多、太啰嗦、太模板化。用户开始为"让 AI 说人话"付费 star。

**4. 智能体工程方法论持续升温。** github/spec-kit（规格驱动开发）、ECC（研究优先开发）、obra/superpowers（开发方法论框架）表明"如何与智能体协作开发"本身正在被工具化、制度化。

**5. 多智能体与垂直应用落地。** 清华 OpenMAIC 把多智能体用于课堂教育；gods-eye-view 把卫星影像 + 3D 地球做成浏览器可用的空间情报工具——AI 应用开始向教育、地理空间等垂直场景纵深发展。

## 三、亮点项目点评

**① ayghri/i-have-adhd（周增 +15,924，本周冠军）**
一个只有几十行的 Prompt 级 Skill，却拿下周增 15.9k star——它解决的问题极其精准：编码智能体习惯把结论埋在长篇过程叙述里，逼用户读三屏才看到答案。它的爆火证明当前智能体生态的"低垂果实"不再是技术难题，而是体验细节。任何在做智能体产品的人都值得读一遍它的 SKILL.md。

**② Tencent/WeKnora（周增 +1,168，Go 语言）**
腾讯开源的 LLM 知识平台，一条龙解决"文档 → RAG → 推理 Agent → 自维护 Wiki"。对需要企业内知识库的团队来说是目前少有的 Go 技术栈选择（多数竞品是 Python），部署友好、资源占用低，且 Wiki 自维护（自动根据文档变化更新知识条目）是差异化亮点。

**③ tt-a1i/archify（周增 +10,442，连续多周上榜）**
让智能体直接产出"自包含 HTML + 动效、可验证"的架构图/时序图/数据流图，替代手工画图和 Mermaid。对于需要在设计评审、技术方案文档中大量输出图的团队，这几乎是即插即用的生产力工具。

## 四、技术选型建议（结合你的技术栈：Python / Go / Vue3 / PHP）

1. **Go → WeKnora 值得深挖。** 你正在做的 wecom-chat-archive / 简化 SCRM 是 Go + Vue3 栈，WeKnora 同为 Go 后端，其 RAG 管道、文档解析、WebSocket 实时交互的工程实现可以直接参考；如果你的 CRM 要加"知识库/客服问答"能力，WeKnora 是最贴近你栈的选型。

2. **Python → markitdown 可直接集成。** 发票系统、文章处理 API（scinsoft.com/tools/）都有"文档 → 结构化文本"的需求，markitdown 一个函数调用即可把 PDF/Office 转 Markdown，比自写解析器省大量维护成本。

3. **Vue3/HTML → archify 与 diagram-design 的产物形态。** 这两个项目的共同思路是"自包含单文件 HTML 交付物"——与你偏好的纯 HTML 单文件交付完全一致。可以考虑给团队做一个内部 Skill：让智能体按你们的设计规范输出 CRM 统计页/落地页的可视化图表 HTML。

4. **立刻可用的效率提升 → 装 2~3 个 Skill。** ponytail（让智能体少写代码）、i-have-adhd（输出直给结论）、spec-kit（规格驱动开发）零成本接入现有编码工作流，对你这种多项目并行、频繁上下文切换的开发节奏收益明显。

5. **PHP 生态本周无热门项目上榜**，但 OpenAI Plugins 的标准化思路值得借鉴：把你的表单构建器/落地页编辑器的常用操作封装成"可复用方法论文档"，让 AI 编码智能体在 PHP 项目里也能稳定复现你的套路。

---

数据来源：GitHub Trending 官方页面 · 抓取时间：2026-09-13 21:02

历史记录：

[2026年9月7日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-9%E6%9C%887%E6%97%A5.md) |

[2026年8月31日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-8%E6%9C%8831%E6%97%A5.md) |

[2026年8月24日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-8%E6%9C%8824%E6%97%A5.md) |

[2026年8月17日](https://github.com/daskero/github-trending-weekly-top20/blob/main/top20-8%E6%9C%8817%E6%97%A5.md) |
