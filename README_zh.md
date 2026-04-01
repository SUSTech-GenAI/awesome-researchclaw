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
- [📖 论文](#-论文)
  - [A. 核心论文——全自动科研 / 自动实验 / Benchmark](#a-核心论文全自动科研--自动实验--benchmark)
  - [B. 相邻论文——文献综述 / Survey / 复现](#b-相邻论文文献综述--survey--复现)
  - [C. 预印本 / Workshop / 投稿中](#c-预印本--workshop--投稿中)
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
| [InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) ![Stars](https://img.shields.io/github/stars/SpectrAI-Initiative/InnoClaw?style=flat-square) | SpectrAI-Initiative | ✓ | △ | △ | ✓ | △ | 自托管 AI 科研工作区——基于 RAG 的本地文件问答、多模态论文研读（ArXiv/PubMed/bioRxiv/Semantic Scholar）、可复用科研技能、多角色深度研究 pipeline，以及 SSH 远程 HPC/SLURM 执行。 |
| [Prismer](https://github.com/Prismer-AI/Prismer) ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | Prismer-AI | — | △ | ✓ | ✓ | △ | 从读论文到发论文的研究平台，带 PDF 阅读、Jupyter、LaTeX、代码执行和 citation verification。 |
| [LabClaw](https://github.com/wu-yc/LabClaw) ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | wu-yc | — | ✓ | ✓ | ✓ | — | 240 个面向生物、药物、医学、文献和可视化的 OpenClaw 技能包。 |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | meowscles69 | △ | — | ✓ | — | — | 面向学术团队的 27 个技能，偏综述、假设版本管理、grant writing 和知识交接。 |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | EESJGong | — | — | — | — | — | 面向学术阅读、知识链接、反思与 Obsidian 知识演化的 OpenClaw skill。 |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | henry-y | — | — | — | — | — | 自动抓 HF Daily Papers，并一键送去 SwiftScholar 做深读。 |
| [scientify](https://github.com/tsingyuai/scientify) ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | tsingyuai | ✓ | △ | ✓ | ✓ | — | 强调"持续新陈代谢"的科研系统，持续跟论文、进化假设、跑验证并主动推送。 |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | Gen-Verse | — | — | — | ✓ | — | 把日常对话变成训练信号，异步强化学习个性化 OpenClaw 或通用 agent。 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) ![Stars](https://img.shields.io/github/stars/HKUDS/ClawTeam?style=flat-square) | HKUDS | — | — | — | △ | — | Agent Swarm Intelligence——多 agent 协作；OpenClaw 适配 fork：[win4r/ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw)。 |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | rohunvora | — | — | △ | — | — | 把 X/Twitter 包成终端研究工具，支持 search、thread follow、monitor 和 briefings。 |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | shenhao-stu | ✓ | — | ✓ | △ | ✓ | 一键起 9 个专职 agent，内置 Paper Pipeline、Brainstorm、Daily Digest、Rebuttal。 |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | MemTensor | — | — | — | — | — | 官方 MemOS Cloud 生命周期插件，run 前 recall，run 后写回长期记忆。 |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | joshuaswarren | — | — | — | — | — | 本地优先的 agent 长期记忆层，markdown 存储，混合检索，跨会话保留研究上下文。 |
| [SkillNet](https://github.com/zjunlp/SkillNet) ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | zjunlp | — | — | — | — | — | 做 skill 的创建、评估、连接和发现，号称可搜 30 万+ community skills。 |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | FreedomIntelligence | — | △ | △ | △ | — | 869 个医学/生物医药技能，把通用 agent 往 clinical、genomics、drug discovery 拉。 |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=flat-square) | wanshuiyin | ✓ | △ | ✓ | ✓ | ✓ | ARIS：纯 Markdown 的轻量研究工作流，主打 cross-model review、idea discovery、experiment automation。 |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) ![Stars](https://img.shields.io/github/stars/OpenLAIR/dr-claw?style=flat-square) | OpenLAIR | ✓ | △ | ✓ | ✓ | △ | AI 科研 IDE，内置 100+ 技能，结构化仪表板（Survey → Ideation → Experiment → Publication），一键自动科研，支持多 Agent（Claude Code / Gemini / Codex）。 |
| [sciClaw](https://github.com/drpedapati/sciclaw) ![Stars](https://img.shields.io/github/stars/drpedapati/sciclaw?style=flat-square) | drpedapati | △ | — | ✓ | ✓ | △ | 基于 PicoClaw 运行时的"配对科学家"agent，支持假设驱动循环、文献检索、文档处理、Shell 执行和可审计的证据轨迹；可通过 Telegram、Discord 或终端访问。 |

### 通用 Research Agent / AI Scientist

| 项目 | 所有者 | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---|---|---|-----|---|------|
| [DeepScientist](https://github.com/ResearAI/DeepScientist) ![Stars](https://img.shields.io/github/stars/ResearAI/DeepScientist?style=flat-square) | ResearAI | ✓ | ✓ | ✓ | ✓ | ✓ | 本地优先、git 备份的自主科研系统——自进化实验分支循环，支持论文草稿、图表生成、rebuttal 工作流，可通过 TUI、Web、微信/QQ 及 Rokid 眼镜多端访问。 |
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | SamuelSchmidgall | △ | — | ✓ | ✓ | — | 端到端 autonomous research workflow，目标是把你的研究想法落成完整实验与论文。 |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | HKUDS | ✓ | — | ✓ | ✓ | — | [NeurIPS 2025] 全流程自主科学发现——文献综述、idea 生成、实验执行、论文撰写，通过独立的 `research_agent` 与 `paper_agent` 模块驱动；生产级 demo 见 [novix.science](https://novix.science/chat)。 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | SakanaAI | ✓ | — | △ | ✓ | — | 主打 "Workshop-Level Automated Scientific Discovery via Agentic Tree Search"。 |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | tsinghua-fib-lab | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem，覆盖 idea generation、experiment design、paper writing 的整体蓝图。 |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | usail-hkust | — | ✓ | ✓ | ✓ | — | 数学建模 agent，做问题分析、建模、代码求解、可视化和报告生成。 |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | InternScience | ✓ | — | — | — | — | ACL 2025 项目，核心卖点是 many-heads 的 scientific idea generation。 |
| [MLGym](https://github.com/facebookresearch/MLGym) ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | facebookresearch | — | — | — | — | — | 面向 AI research agents 的统一框架和 benchmark。 |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | facebookresearch | — | — | — | △ | — | 可扩展的 AI research agent 开发/评测框架，带隔离代码执行环境，直指 fully automated AI research scientist。 |
| [airs-bench](https://github.com/facebookresearch/airs-bench) ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | facebookresearch | — | — | — | — | — | 用来量化 LLM agents 端到端 AI research 能力的基准。 |
| [deep_research_bench](https://github.com/Ayanami0730/deep_research_bench) ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | Ayanami0730 | — | — | — | — | — | 面向 deep research agents 的综合 benchmark 和 leaderboard。 |

### Deep Research 与框架

| 项目 | 所有者 | I | 图 | 写 | 实验 | R | 简述 |
|------|-------|---|---|---|-----|---|------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | LangChain | — | — | ✓ | — | — | 全开源 deep research agent，跨多模型、多搜索 API、多 MCP，内置 final report 生成。 |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | Alibaba-NLP | — | — | △ | — | — | Tongyi Deep Research，当前这批里 star 最高，主打 open-source deep research agent。 |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | MiroMindAI | — | — | △ | — | — | 面向复杂 research 与 prediction 任务的 deep research agent，BrowseComp 分数很高。 |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | MiroMindAI | — | — | — | — | — | 强调 performance-first 的开源 agent 框架，同环境下尽量把不同模型的 agent 表现做满。 |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | Tencent | — | — | — | △ | — | 腾讯的 Deep Research Agent 框架，同时谈 agent foundation models training。 |
| [simply](https://github.com/google-deepmind/simply) ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | google-deepmind | ✓ | — | — | ✓ | — | 极简 JAX 研究底座，README 明写可让 agent 读代码、提想法、跑实验、反复迭代。 |

## 📖 论文

### A. 核心论文——全自动科研 / 自动实验 / Benchmark

| 论文名 | 会议/期刊 | 年份 | 作者 | 一句话描述 | 能力标签 | 链接 |
|--------|----------|------|------|-----------|---------|------|
| SciMON: Scientific Inspiration Machines Optimized for Novelty | ACL Long | 2024 | Qingyun Wang, Doug Downey, et al. | 把科研想法生成做成"文献 grounding + 新颖性优化"问题。 | `idea` `benchmark` | [论文](https://aclanthology.org/2024.acl-long.18/) |
| MLAgentBench: Evaluating Language Agents on ML Experimentation | ICML | 2024 | Qian Huang, Jian Vora, et al. | 把 ML 研究实验拆成真实 terminal 任务，测 agent 读写文件、跑代码、迭代分析。 | `exp` `benchmark` | [论文](https://proceedings.mlr.press/v235/huang24y.html) |
| SciCode: A Research Coding Benchmark Curated by Scientists | NeurIPS D&B | 2024 | Minyang Tian, Luyu Gao, et al. | 面向真实科研编程的 benchmark，强调科学背景理解与代码实现。 | `exp` `benchmark` | [论文](https://proceedings.neurips.cc/paper_files/paper/2024/hash/36850592258c8c41cecdaa3dea5ff7de-Abstract-Datasets_and_Benchmarks_Track.html) |
| Can LLMs Generate Novel Research Ideas? | ICLR Poster | 2025 | Chenglei Si, Diyi Yang, Tatsunori Hashimoto | 100+ NLP 研究者大规模人评 LLM 研究想法。 | `idea` `benchmark` | [论文](https://openreview.net/forum?id=M23dTGWCZy) |
| BioDiscoveryAgent | ICLR Poster | 2025 | Yusuf H. Roohani, Andrew H. Lee, et al. | 面向生物实验设计的 AI agent，提出基因扰动实验并完成搜索、自查和分析。 | `idea` `exp` `review` | [论文](https://openreview.net/forum?id=HAwZGLcye3) |
| CycleResearcher: Improving Automated Research via Automated Review | ICLR Poster | 2025 | Yixuan Weng, Minjun Zhu, et al. | 把"研究—评审—修订"做成闭环，用 reviewer agent 迭代提升质量。 | `writing` `review` | [论文](https://openreview.net/forum?id=bjcsVLoHYs) |
| ResearchAgent: Iterative Research Idea Generation over Scientific Literature | NAACL Long | 2025 | Jinheon Baek, Sujay Kumar Jauhar, et al. | 从核心论文出发，自动定义问题、提方法、设实验，并让 ReviewingAgents 反复打磨。 | `idea` `exp` `review` | [论文](https://aclanthology.org/2025.naacl-long.342/) |
| Many Heads Are Better Than One | ACL Long | 2025 | Haoyang Su, Renqi Chen, et al. | 多 agent 协作生成、评估、细化科研想法，证明多人讨论式结构优于单 agent。 | `idea` | [论文](https://aclanthology.org/2025.acl-long.1368/) |
| Agent Laboratory: Using LLM Agents as Research Assistants | Findings of EMNLP | 2025 | Samuel Schmidgall, Yusheng Su, et al. | 给定人类想法后，自动完成 literature review、实验、写报告并产出代码仓库。 | `exp` `writing` | [论文](https://aclanthology.org/2025.findings-emnlp.320/) · [代码](https://github.com/SamuelSchmidgall/AgentLaboratory) |
| PaperBench: Evaluating AI's Ability to Replicate AI Research | ICML | 2025 | Giulio Starace, Oliver Jaffe, et al. | 要求 agent 从零复现 20 篇 ICML 2024 论文，用细粒度 rubric 和 judge 衡量。 | `exp` `benchmark` | [论文](https://proceedings.mlr.press/v267/starace25a.html) |
| MM-Agent: LLM as Agents for Real-world Mathematical Modeling | NeurIPS Poster | 2025 | Fan Liu, Zherui Yang, et al. | 真实数学建模四阶段：问题分析→建模→求解→报告生成。 | `exp` `writing` `benchmark` | [论文](https://neurips.cc/virtual/2025/poster/116075) · [代码](https://github.com/usail-hkust/LLM-MM-Agent) |
| AI-Researcher: Autonomous Scientific Innovation | NeurIPS Spotlight | 2025 | Jiabin Tang, Lianghao Xia, et al. | 最完整的自动科研系统之一，从综述到写作给出统一框架。 | `idea` `exp` `writing` `benchmark` | [论文](https://neurips.cc/virtual/2025/poster/116385) · [代码](https://github.com/HKUDS/AI-Researcher) |
| SciGym: Measuring Scientific Capabilities with a Systems Biology Dry Lab | NeurIPS Poster | 2025 | Haonan Duan, Stephen Lu, et al. | 用系统生物学 dry lab 环境评测实验设计和结果解释能力。 | `exp` `benchmark` | [论文](https://neurips.cc/virtual/2025/poster/121779) |
| MLR-Bench: Evaluating AI Agents on Open-Ended ML Research | NeurIPS | 2025 | Hui Chen, Miao Xiong, et al. | Open-ended ML research 四阶段评测：idea→proposal→experiment→paper。 | `idea` `exp` `writing` `review` `benchmark` | [论文](https://neurips.cc/virtual/2025/poster/121719) |
| MOOSE-Chem2: Fine-Grained Hypothesis Discovery via Hierarchical Search | NeurIPS Poster | 2025 | Zonglin Yang, Wanhao Liu, et al. | 把粗粒度方向细化成可执行、方法级的假设发现任务。 | `idea` `benchmark` | [论文](https://neurips.cc/virtual/2025/poster/118171) |
| SciToolAgent: Knowledge-Graph-Driven Scientific Agent | Nature Computational Science | 2025 | Keyan Ding, Jing Yu, et al. | 用科学工具知识图谱做 tool selection 与 orchestration。 | `exp` | [论文](https://doi.org/10.1038/s43588-025-00849-y) |
| LLM Agents for Automation of Atomic Force Microscopy | Nature Communications | 2025 | Indrajeet Mandal, Jitendra Soni, et al. | AILA 和 AFMBench——评估 LLM agents 自主完成 AFM 实验。 | `exp` `benchmark` | [论文](https://www.nature.com/articles/s41467-025-64105-7) |
| AI Mirrors Experimental Science (Cell) | Cell | 2025 | José R. Penadés, Juraj Gottweis, et al. | AI co-scientist 提出假设 + 湿实验验证的标志性案例。 | `idea` `exp` | [论文](https://doi.org/10.1016/j.cell.2025.08.018) |
| Towards End-to-End Automation of AI Research | Nature | 2026 | Chris Lu, Cong Lu, et al. | The AI Scientist 同行评审版，真正串成 idea→code→exp→paper→review 闭环。 | `idea` `exp` `writing` `review` | [论文](https://www.nature.com/articles/s41586-026-10265-5) |
| AstaBench: Rigorous Benchmarking of AI Agents | ICLR Oral | 2026 | Jonathan Bragg, Mike D'Arcy, et al. | 2400+ 科研问题，首个"产品化"科研 agent 综合基准。 | `benchmark` | [论文](https://openreview.net/forum?id=M7TNf5J26u) |
| The Ideation-Execution Gap | ICLR Poster | 2026 | Chenglei Si, Tatsunori Hashimoto, Diyi Yang | LLM idea 优势在真实执行后明显缩水。 | `idea` `benchmark` | [论文](https://openreview.net/forum?id=Fllp8l6Puy) |
| Eigen-Agent: Adaptive Multi-Agent Scientific Reasoning | ICLR Poster | 2026 | Xiangru Tang, Wanghan Xu, et al. | 隐式检索 + 结构化修复，面向生物/化学科学推理。 | `exp` | [论文](https://openreview.net/forum?id=bGtmGTbmaz) |
| MoSciBench: Multimodal Data-Driven Scientific Discovery | ICLR Poster | 2026 | Fan Liu, Xiaozhao Zeng, Hao Liu | 多模态、数据驱动、假设验证式的科学发现 benchmark。 | `exp` `benchmark` | [论文](https://openreview.net/forum?id=kZHSvETWdi) |
| IR-Agent: Expert-Inspired LLM Agents for IR Spectra Structure Elucidation | ICLR Poster | 2026 | Heewoong Noh, Namkyeong Lee, et al. | 多 agent 模拟专家式红外光谱分析，做未知分子结构解析。 | `exp` | [论文](https://openreview.net/forum?id=6bthH14pD8) · [代码](https://github.com/HeewoongNoh/IR-Agent) |
| CLADD: RAG-Enhanced Collaborative LLM Agents for Drug Discovery | AAAI | 2026 | Namkyeong Lee, Edward De Brouwer, et al. | 多 agent + RAG 做药物发现问答和证据整合，不靠重训练。 | `exp` | [论文](https://ojs.aaai.org/index.php/AAAI/article/view/37020) · [代码](https://github.com/Genentech/CLADD) |

### B. 相邻论文——文献综述 / Survey / 复现

| 论文名 | 会议/期刊 | 年份 | 作者 | 一句话描述 | 能力标签 | 链接 |
|--------|----------|------|------|-----------|---------|------|
| ArxivDIGESTables: Synthesizing Scientific Literature into Tables | EMNLP | 2024 | Benjamin Newman, Yoonjoo Lee, et al. | 自动把一组论文整理成 literature review table。 | `writing` | [论文](https://aclanthology.org/2024.emnlp-main.538/) |
| MicroVQA: Multimodal Reasoning Benchmark for Microscopy Research | CVPR | 2025 | James Burgess, Jeffrey J. Nirschl, et al. | 面向显微科学研究的多模态 benchmark，测图像理解和实验提案。 | `idea` `benchmark` | [论文](https://openaccess.thecvf.com/content/CVPR2025/html/Burgess_MicroVQA_A_Multimodal_Reasoning_Benchmark_for_Microscopy-Based_Scientific_Research_CVPR_2025_paper.html) |
| SurveyGen: Quality-Aware Scientific Survey Generation | EMNLP | 2025 | Tong Bao, Mir Tafseer Nayeem, et al. | 给自动 survey 引入质量感知检索，结论：全自动 survey 仍落后于人。 | `writing` | [论文](https://aclanthology.org/2025.emnlp-main.136/) |
| ResearchArena: Benchmarking LLMs as Research Agents | Findings of EMNLP | 2025 | Hao Kang, Chenyan Xiong | 把 survey 过程拆成信息发现、选择、组织，测 LLM 整理文献能力。 | `benchmark` | [论文](https://aclanthology.org/2025.findings-emnlp.303/) |
| LMR-BENCH: Evaluating LLM Agents on Reproducing LM Research | EMNLP | 2025 | Shuo Yan, Ruochen Li, et al. | 专门评估 agent 复现语言模型研究代码的能力。 | `exp` `benchmark` | [论文](https://aclanthology.org/2025.emnlp-main.314/) |
| SurveyGen-I: Consistent Survey Generation with Evolving Plans | IJCNLP-AACL | 2025 | Jing Chen, Zhiheng Yang, et al. | Evolving plan + memory-guided writing 改善 survey 长文一致性。 | `writing` | [论文](https://aclanthology.org/2025.ijcnlp-long.193/) |
| Reliable Hypothesis Generation: Evaluating Truthfulness and Hallucination | IJCAI Main | 2025 | Guangzhi Xiong, Eric Xie, et al. | 不只关心"能不能生 hypothesis"，直接测是否真实、是否幻觉。 | `idea` `benchmark` | [论文](https://www.ijcai.org/proceedings/2025/873) |
| Automating Intervention Discovery from Scientific Literature | IJCAI AI & Social Good | 2025 | Yuting Hu, Dancheng Liu, et al. | Ontology prompting + 双 agent 从科学文献里自动抽 intervention。 | `idea` | [论文](https://www.ijcai.org/proceedings/2025/1078) |
| LitChat: Conversational Exploration of Literature Landscape | IJCAI Demo | 2025 | Mingyu Huang, Shasha Zhou, et al. | 对话式文献探索 agent，强调系统综述场景下的透明可追溯。 | `writing` | [论文](https://www.ijcai.org/proceedings/2025/1262) |
| Intent-aware Schema Generation for Literature Review Tables | Findings of EMNLP | 2025 | Vishakh Padmakumar, Joseph Chee Chang, et al. | Intent-aware 的 literature review table schema 生成与 refine。 | `writing` | [论文](https://aclanthology.org/2025.findings-emnlp.1274/) |

### C. 预印本 / Workshop / 投稿中

| 论文名 | 状态 | 年份 | 作者 | 一句话描述 | 能力标签 | 链接 |
|--------|------|------|------|-----------|---------|------|
| The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery | arXiv 预印本 | 2024 | Chris Lu, Cong Lu, et al. | 第一个把全流程自动科研讲清楚的标志性 preprint；Nature 2026 有同行评审版。 | `idea` `exp` `writing` `review` | [论文](https://arxiv.org/abs/2408.06292) |
| Towards an AI Co-Scientist | arXiv 预印本 | 2025 | Juraj Gottweis, Wei-Hung Weng, et al. | Google Gemini 多 agent co-scientist，generate–debate–evolve 假设发现。 | `idea` `exp` | [论文](https://arxiv.org/abs/2502.18864) |
| BioVerge: Self-Evaluating Agents for Biomedical Hypothesis Generation | NeurIPS 2025 LAW Workshop | 2025 | Fuyi Yang, Chenchen Ye, et al. | 生物医学 hypothesis generation 的 benchmark 和自评式 agent 框架。 | `idea` `benchmark` | [论文](https://neurips.cc/virtual/2025/137205) |
| FIRE-Bench: Evaluating Research Agents on Rediscovery of Insights | ICLR 2026 投稿中 | 2026 | Zhen Wang, Fan Bai, et al. | 只给高层研究问题，要求 agent 重新发现高影响论文的 insight。 | `exp` `benchmark` | [论文](https://openreview.net/forum?id=454tA4k8yJ) |
| PiFlow: Principle-aware Scientific Discovery | ICLR 2026 投稿中 | 2026 | Yingming Pu, Tao Lin, Hongyu Chen | 强调 principle-aware exploration 和 evidence linkage。 | `idea` `exp` | [论文](https://openreview.net/forum?id=Is2oXblRtP) |
| From What to Why: Multi-Agent Chemical Reaction Condition Reasoning | ICLR 2026 投稿中 | 2026 | Cheng Yang, Jiaxuan Lu, et al. | 反应条件推荐升级：给答案 + 给证据 + 给机理解释。 | `exp` | [论文](https://openreview.net/forum?id=Rh72R0VXPS) |
| SurGE: Benchmark for Scientific Survey Generation | ICLR 2026 投稿中 (withdrawn) | 2026 | Weihang Su, Anzhe Xie, et al. | 面向 scientific survey generation 的 benchmark 和评测协议。 | `writing` `benchmark` | [论文](https://openreview.net/forum?id=hXz1myTe4X) |

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
