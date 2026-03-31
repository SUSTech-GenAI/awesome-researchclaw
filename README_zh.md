# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 ResearchClaw 生态项目、工具、集成和资源的精选列表——面向 AI 驱动的学术科研。

ResearchClaw 是一个新兴的 AI 科研助手生态系统，涵盖自主论文写作流水线和科研工作流工具。本列表收录了核心项目、扩展、相关工具和学习资源。

👉 如果想看具体的体验，可参考该项目的[开源项目体验报告以及评测打分](https://sustech-genai.github.io/research-claw-arena/)。

[English](README.md)

## 目录

- [项目对比矩阵](#项目对比矩阵)
  - [OpenClaw 生态与科研工具](#openclaw-生态与科研工具)
  - [通用 Research Agent / AI Scientist](#通用-research-agent--ai-scientist)
  - [Deep Research 与框架](#deep-research-与框架)
- [社区与学习](#社区与学习)

---

## 项目对比矩阵

> **能力列说明：** I = 想法生成 · 图 = 绘图/可视化 · 写 = 写作/成稿 · 实验 = 自动实验/执行 · R = 审稿/rebuttal
> ✓ = README 明确支持 · △ = 间接支持/框架能力 · — = 未见明确说明

### OpenClaw 生态与科研工具

| 项目 | 所有者 | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---|---|---|-----|---|------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) ![Stars](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw?style=flat-square) | aiming-lab | △ | ✓ | ✓ | ✓ | ✓ | 23 阶段 idea→paper，自动出 LaTeX、引用校验、实验结果和图表，还有多 agent 审稿。 |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) ![Stars](https://img.shields.io/github/stars/ymx10086/ResearchClaw?style=flat-square) | ymx10086 | — | △ | ✓ | ✓ | — | 本地优先的科研操作系统，带 claims/evidence、experiment tracking、papers、skills、channels。 |
| [research-claw](https://github.com/nanoAgentTeam/research-claw) ![Stars](https://img.shields.io/github/stars/nanoAgentTeam/research-claw?style=flat-square) | nanoAgentTeam | — | — | ✓ | — | — | 自托管学术助手，管论文、搜文献、跟 deadline、维护 LaTeX/Overleaf。 |
| [Prismer](https://github.com/Prismer-AI/Prismer) ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | Prismer-AI | — | △ | ✓ | ✓ | △ | 从读论文到发论文的研究平台，带 PDF 阅读、Jupyter、LaTeX、代码执行和 citation verification。 |
| [LabClaw](https://github.com/wu-yc/LabClaw) ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | wu-yc | — | ✓ | ✓ | ✓ | — | 240 个面向生物、药物、医学、文献和可视化的 OpenClaw 技能包。 |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | meowscles69 | △ | — | ✓ | — | — | 面向学术团队的 27 个技能，偏综述、假设版本管理、grant writing 和知识交接。 |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | EESJGong | — | — | — | — | — | 面向学术阅读、知识链接、反思与 Obsidian 知识演化的 OpenClaw skill。 |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | henry-y | — | — | — | — | — | 自动抓 HF Daily Papers，并一键送去 SwiftScholar 做深读。 |
| [scientify](https://github.com/tsingyuai/scientify) ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | tsingyuai | ✓ | △ | ✓ | ✓ | — | 强调"持续新陈代谢"的科研系统，持续跟论文、进化假设、跑验证并主动推送。 |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | Gen-Verse | — | — | — | ✓ | — | 把日常对话变成训练信号，异步强化学习个性化 OpenClaw 或通用 agent。 |
| [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) ![Stars](https://img.shields.io/github/stars/win4r/ClawTeam-OpenClaw?style=flat-square) | win4r | — | — | — | △ | — | ClawTeam 的 OpenClaw 深度适配 fork，主打 swarm 协作、worktree 和 tmux 隔离。 |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | rohunvora | — | — | △ | — | — | 把 X/Twitter 包成终端研究工具，支持 search、thread follow、monitor 和 briefings。 |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | shenhao-stu | ✓ | — | ✓ | △ | ✓ | 一键起 9 个专职 agent，内置 Paper Pipeline、Brainstorm、Daily Digest、Rebuttal。 |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | MemTensor | — | — | — | — | — | 官方 MemOS Cloud 生命周期插件，run 前 recall，run 后写回长期记忆。 |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | joshuaswarren | — | — | — | — | — | 本地优先的 agent 长期记忆层，markdown 存储，混合检索，跨会话保留研究上下文。 |
| [SkillNet](https://github.com/zjunlp/SkillNet) ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | ZJUNLP | — | — | — | — | — | 做 skill 的创建、评估、连接和发现，号称可搜 30 万+ community skills。 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | FreedomIntelligence | — | △ | △ | △ | — | 869 个医学/生物医药技能，把通用 agent 往 clinical、genomics、drug discovery 拉。 |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=flat-square) | wanshuiyin | ✓ | △ | ✓ | ✓ | ✓ | ARIS：纯 Markdown 的轻量研究工作流，主打 cross-model review、idea discovery、experiment automation。 |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) ![Stars](https://img.shields.io/github/stars/OpenLAIR/dr-claw?style=flat-square) | OpenLAIR | ✓ | △ | ✓ | ✓ | △ | AI 科研 IDE，内置 100+ 技能，结构化仪表板（Survey → Ideation → Experiment → Publication），一键自动科研，支持多 Agent（Claude Code / Gemini / Codex）。 |
| [sciClaw](https://github.com/drpedapati/sciclaw) ![Stars](https://img.shields.io/github/stars/drpedapati/sciclaw?style=flat-square) | drpedapati | △ | — | ✓ | ✓ | △ | 基于 PicoClaw 运行时的"配对科学家"agent，支持假设驱动循环、文献检索、文档处理、Shell 执行和可审计的证据轨迹；可通过 Telegram、Discord 或终端访问。 |

### 通用 Research Agent / AI Scientist

| 项目 | 所有者 | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---|---|---|-----|---|------|
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | SamuelSchmidgall | △ | — | ✓ | ✓ | — | 端到端 autonomous research workflow，目标是把你的研究想法落成完整实验与论文。 |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | HKUDS | ✓ | — | ✓ | ✓ | — | "Autonomous Scientific Innovation"，仓库里明确分了 `research_agent` 和 `paper_agent`。 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | SakanaAI | ✓ | — | △ | ✓ | — | 主打 "Workshop-Level Automated Scientific Discovery via Agentic Tree Search"。 |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | 清华 FIB Lab | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem，覆盖 idea generation、experiment design、paper writing 的整体蓝图。 |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | HKUST | — | ✓ | ✓ | ✓ | — | 数学建模 agent，做问题分析、建模、代码求解、可视化和报告生成。 |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | InternScience | ✓ | — | — | — | — | ACL 2025 项目，核心卖点是 many-heads 的 scientific idea generation。 |
| [MLGym](https://github.com/facebookresearch/MLGym) ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | Meta FAIR | — | — | — | — | — | 面向 AI research agents 的统一框架和 benchmark。 |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | Meta FAIR | — | — | — | △ | — | 可扩展的 AI research agent 开发/评测框架，带隔离代码执行环境，直指 fully automated AI research scientist。 |
| [airs-bench](https://github.com/facebookresearch/airs-bench) ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | Meta FAIR | — | — | — | — | — | 用来量化 LLM agents 端到端 AI research 能力的基准。 |
| [deep_research_bench](https://github.com/Ayanami0730/deep_research_bench) ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | Ayanami0730 | — | — | — | — | — | 面向 deep research agents 的综合 benchmark 和 leaderboard。 |

### Deep Research 与框架

| 项目 | 所有者 | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---|---|---|-----|---|------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | LangChain | — | — | ✓ | — | — | 全开源 deep research agent，跨多模型、多搜索 API、多 MCP，内置 final report 生成。 |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | Alibaba-NLP | — | — | △ | — | — | Tongyi Deep Research，当前这批里 star 最高，主打 open-source deep research agent。 |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | MiroMindAI | — | — | △ | — | — | 面向复杂 research 与 prediction 任务的 deep research agent，BrowseComp 分数很高。 |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | MiroMindAI | — | — | — | — | — | 强调 performance-first 的开源 agent 框架，同环境下尽量把不同模型的 agent 表现做满。 |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | Tencent AI Lab | — | — | — | △ | — | 腾讯的 Deep Research Agent 框架，同时谈 agent foundation models training。 |
| [simply](https://github.com/google-deepmind/simply) ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | Google DeepMind | ✓ | — | — | ✓ | — | 极简 JAX 研究底座，README 明写可让 agent 读代码、提想法、跑实验、反复迭代。 |

---

## 社区与学习

关于 AI 驱动科研和 ResearchClaw 生态的学习资源。

### 社区

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — AutoResearchClaw 用户和贡献者的官方社区。
- [OpenClaw 社区](https://github.com/openclaw/openclaw/discussions) — OpenClaw 生态相关讨论。

### 指南与教程

- [AutoResearchClaw 测试指南](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — 用你自己的研究想法试用流水线。
- [ResearchClaw 快速上手](https://ymx10086.github.io/ResearchClaw/) — ResearchClaw 安装和使用的官方文档。
- [AutoResearchClaw 集成指南](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — 与 OpenClaw、Claude Code、ACP 代理的集成。

---

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，作者已放弃本作品的所有版权及相关权利。
