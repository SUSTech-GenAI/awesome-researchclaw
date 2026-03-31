# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 ResearchClaw 生态项目、工具、集成和资源的精选列表——面向 AI 驱动的学术科研。

ResearchClaw 是一个新兴的 AI 科研助手生态系统，涵盖自主论文写作流水线和科研工作流工具。本列表收录了核心项目、扩展、相关工具和学习资源。

[English](README.md)

## 目录

- [项目对比矩阵](#项目对比矩阵)
  - [OpenClaw 生态与科研工具](#openclaw-生态与科研工具)
  - [通用 Research Agent / AI Scientist](#通用-research-agent--ai-scientist)
  - [Deep Research 与框架](#deep-research-与框架)
- [技能与插件](#技能与插件)
- [社区与学习](#社区与学习)
- [相关 Awesome 列表](#相关-awesome-列表)

---

## 项目对比矩阵

> **能力列说明：** I = 想法生成 · 图 = 绘图/可视化 · 写 = 写作/成稿 · 实验 = 自动实验/执行 · R = 审稿/rebuttal
> ✓ = README 明确支持 · △ = 间接支持/框架能力 · — = 未见明确说明

### OpenClaw 生态与科研工具

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | aiming-lab | 9.7k | △ | ✓ | ✓ | ✓ | ✓ | 23 阶段 idea→paper，自动出 LaTeX、引用校验、实验结果和图表，还有多 agent 审稿。 |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | ymx10086 | 230 | — | △ | ✓ | ✓ | — | 本地优先的科研操作系统，带 claims/evidence、experiment tracking、papers、skills、channels。 |
| [research-claw](https://github.com/nanoAgentTeam/research-claw) | nanoAgentTeam | 61 | — | — | ✓ | — | — | 自托管学术助手，管论文、搜文献、跟 deadline、维护 LaTeX/Overleaf。 |
| [Prismer](https://github.com/Prismer-AI/Prismer) | Prismer-AI | 1k | — | △ | ✓ | ✓ | △ | 从读论文到发论文的研究平台，带 PDF 阅读、Jupyter、LaTeX、代码执行和 citation verification。 |
| [LabClaw](https://github.com/wu-yc/LabClaw) | wu-yc | 900 | — | ✓ | ✓ | ✓ | — | 240 个面向生物、药物、医学、文献和可视化的 OpenClaw 技能包。 |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) | meowscles69 | 152 | △ | — | ✓ | — | — | 面向学术团队的 27 个技能，偏综述、假设版本管理、grant writing 和知识交接。 |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) | EESJGong | 114 | — | — | — | — | — | 面向学术阅读、知识链接、反思与 Obsidian 知识演化的 OpenClaw skill。 |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | henry-y | 83 | — | — | — | — | — | 自动抓 HF Daily Papers，并一键送去 SwiftScholar 做深读。 |
| [awesome-claws](https://github.com/LHL3341/awesome-claws) | LHL3341 | 32 | — | — | — | — | — | OpenClaw 相关产品、skills、社区和生态资源的导航索引。 |
| [awesome-autoresearch](https://github.com/alvinunreal/awesome-autoresearch) | alvinunreal | 1.1k | — | — | — | — | — | Karpathy autoresearch 系分支、research agents、benchmarks 的高信号索引。 |
| [scientify](https://github.com/tsingyuai/scientify) | tsingyuai | 138 | ✓ | △ | ✓ | ✓ | — | 强调"持续新陈代谢"的科研系统，持续跟论文、进化假设、跑验证并主动推送。 |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) | Gen-Verse | 4.4k | — | — | — | ✓ | — | 把日常对话变成训练信号，异步强化学习个性化 OpenClaw 或通用 agent。 |
| [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) | win4r | 928 | — | — | — | △ | — | ClawTeam 的 OpenClaw 深度适配 fork，主打 swarm 协作、worktree 和 tmux 隔离。 |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) | rohunvora | 1k | — | — | △ | — | — | 把 X/Twitter 包成终端研究工具，支持 search、thread follow、monitor 和 briefings。 |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) | shenhao-stu | 351 | ✓ | — | ✓ | △ | ✓ | 一键起 9 个专职 agent，内置 Paper Pipeline、Brainstorm、Daily Digest、Rebuttal。 |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) | MemTensor | 337 | — | — | — | — | — | 官方 MemOS Cloud 生命周期插件，run 前 recall，run 后写回长期记忆。 |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) | joshuaswarren | 37 | — | — | — | — | — | 本地优先的 agent 长期记忆层，markdown 存储，混合检索，跨会话保留研究上下文。 |
| [SkillNet](https://github.com/zjunlp/SkillNet) | ZJUNLP | 625 | — | — | — | — | — | 做 skill 的创建、评估、连接和发现，号称可搜 30 万+ community skills。 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | FreedomIntelligence | 1.8k | — | △ | △ | △ | — | 869 个医学/生物医药技能，把通用 agent 往 clinical、genomics、drug discovery 拉。 |
| [Auto-claude-code-research-in-sleep](https://github.com/zhangchenhaobest/Auto-claude-code-research-in-sleep) | zhangchenhaobest | 0 | ✓ | △ | ✓ | ✓ | ✓ | ARIS：纯 Markdown 的轻量研究工作流，主打 cross-model review、idea discovery、experiment automation。 |

### 通用 Research Agent / AI Scientist

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | SamuelSchmidgall | 5.5k | △ | — | ✓ | ✓ | — | 端到端 autonomous research workflow，目标是把你的研究想法落成完整实验与论文。 |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | HKUDS | 5k | ✓ | — | ✓ | ✓ | — | "Autonomous Scientific Innovation"，仓库里明确分了 `research_agent` 和 `paper_agent`。 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | SakanaAI | 4.1k | ✓ | — | △ | ✓ | — | 主打 "Workshop-Level Automated Scientific Discovery via Agentic Tree Search"。 |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) | 清华 FIB Lab | 102 | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem，覆盖 idea generation、experiment design、paper writing 的整体蓝图。 |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) | HKUST | 499 | — | ✓ | ✓ | ✓ | — | 数学建模 agent，做问题分析、建模、代码求解、可视化和报告生成。 |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) | InternScience | 129 | ✓ | — | — | — | — | ACL 2025 项目，核心卖点是 many-heads 的 scientific idea generation。 |
| [MLGym](https://github.com/facebookresearch/MLGym) | Meta FAIR | 593 | — | — | — | — | — | 面向 AI research agents 的统一框架和 benchmark。 |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) | Meta FAIR | 136 | — | — | — | △ | — | 可扩展的 AI research agent 开发/评测框架，带隔离代码执行环境，直指 fully automated AI research scientist。 |
| [airs-bench](https://github.com/facebookresearch/airs-bench) | Meta FAIR | 71 | — | — | — | — | — | 用来量化 LLM agents 端到端 AI research 能力的基准。 |
| [deep_research_bench](https://github.com/Ayanami0730/deep_research_bench) | Ayanami0730 | 651 | — | — | — | — | — | 面向 deep research agents 的综合 benchmark 和 leaderboard。 |

### Deep Research 与框架

| 项目 | 所有者 | ⭐ Stars | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---------|---|---|---|-----|---|------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) | LangChain | 11k | — | — | ✓ | — | — | 全开源 deep research agent，跨多模型、多搜索 API、多 MCP，内置 final report 生成。 |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | Alibaba-NLP | 18.6k | — | — | △ | — | — | Tongyi Deep Research，当前这批里 star 最高，主打 open-source deep research agent。 |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | MiroMindAI | 8.4k | — | — | △ | — | — | 面向复杂 research 与 prediction 任务的 deep research agent，BrowseComp 分数很高。 |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) | MiroMindAI | 2.9k | — | — | — | — | — | 强调 performance-first 的开源 agent 框架，同环境下尽量把不同模型的 agent 表现做满。 |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) | Tencent AI Lab | 505 | — | — | — | △ | — | 腾讯的 Deep Research Agent 框架，同时谈 agent foundation models training。 |
| [simply](https://github.com/google-deepmind/simply) | Google DeepMind | 511 | ✓ | — | — | ✓ | — | 极简 JAX 研究底座，README 明写可让 agent 读代码、提想法、跑实验、反复迭代。 |

---

## 技能与插件

扩展 ResearchClaw 能力的可复用技能和插件。

### 内置技能（ResearchClaw）

- `arxiv` — arXiv 论文搜索与下载
- `citation_network` — 引用网络探索与可视化
- `experiment_tracker` — 实验生命周期管理
- `figure_generator` — 学术图表生成
- `literature_review` — 自动化文献综述工作流
- `paper_summarizer` — 论文总结与关键洞察提取
- `research_notes` — 结构化笔记（论文笔记、想法笔记、实验笔记）
- `research_workflows` — 多阶段科研工作流管理
- `pdf` / `docx` / `pptx` / `xlsx` — 文档格式支持

### AutoResearchClaw 多 Agent 子系统

- **CodeAgent** — 多阶段实验代码生成
- **BenchmarkAgent** — 自动数据集发现与基线对比
- **FigureAgent** — 5-Agent 流水线：规划 → 代码生成 → 渲染 → 评审 → 集成
- **Sentinel Watchdog** — 后台质量监控：NaN/Inf 检测、引用评分、反造假

## 社区与学习

关于 AI 驱动科研和 ResearchClaw 生态的学习资源。

### 社区

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — AutoResearchClaw 用户和贡献者的官方社区。
- [OpenClaw 社区](https://github.com/openclaw/openclaw/discussions) — OpenClaw 生态相关讨论。

### 指南与教程

- [AutoResearchClaw 测试指南](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — 用你自己的研究想法试用流水线。
- [ResearchClaw 快速上手](https://ymx10086.github.io/ResearchClaw/) — ResearchClaw 安装和使用的官方文档。
- [AutoResearchClaw 集成指南](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — 与 OpenClaw、Claude Code、ACP 代理的集成。

### 精选列表

- [Awesome AI Research Writing](https://github.com/Leey21/awesome-ai-research-writing) — AI 科研写作资源和工具精选。
- [Awesome Research](https://github.com/emptymalei/awesome-research) — 涵盖笔记、写作、演示等的研究工具。

## 相关 Awesome 列表

- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw 相关产品、技能、社区。
- [Awesome Research](https://github.com/emptymalei/awesome-research) — 通用研究工具。

---

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃本作品的所有版权及相关权利。
