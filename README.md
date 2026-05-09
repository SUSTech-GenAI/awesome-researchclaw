# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 A curated list of ResearchClaw ecosystem projects, tools, integrations, and resources for AI-powered academic research.

ResearchClaw is an emerging ecosystem of AI-powered research assistants, autonomous paper-writing pipelines, and scientific workflow tools. This list covers the core projects, extensions, related tools, and learning resources.

👉 For hands-on experience reports and evaluation scores, check out the [Research Claw Arena](https://sustech-genai.github.io/research-claw-arena/).

[中文](README_zh.md)

## Contents

- [OpenClaw Ecosystem & Research Tools](#openclaw-ecosystem--research-tools)
- [Research Agents & AI Scientists](#research-agents--ai-scientists)
- [Deep Research & Frameworks](#deep-research--frameworks)
- [📖 Papers](#-papers)
  - [A. Core Papers — End-to-End Research / Experiments / Benchmarks](#a-core-papers--end-to-end-research--experiments--benchmarks)
  - [B. Adjacent Papers — Literature Agents / Surveys / Reproduction](#b-adjacent-papers--literature-agents--surveys--reproduction)
  - [C. Preprints / Workshops / Under Review](#c-preprints--workshops--under-review)
- [Community & Learning](#community--learning)

---

> **Capability columns:** I = Idea generation · Fig = Figure / visualization · Write = Writing / drafting · Exp = Experiment / execution · R = Review / rebuttal
> ✓ = Explicitly supported · △ = Indirect / framework capability · — = Not mentioned

## OpenClaw Ecosystem & Research Tools

Projects directly related to the OpenClaw ecosystem — core platforms, skill libraries, plugins, and curated lists.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [Suppr](https://suppr.wilddata.cn/) | WildDataX | — | △ | ✓ | ✓ | △ | AI literature search, document translation, and deep-research platform with PubMed/OpenAlex search and Zotero plugin workflow. |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) ![Stars](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw?style=flat-square) | aiming-lab | △ | ✓ | ✓ | ✓ | ✓ | 23-stage idea → paper pipeline with auto LaTeX, citation verification, experiments, figures, and multi-agent peer review. |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) ![Stars](https://img.shields.io/github/stars/ymx10086/ResearchClaw?style=flat-square) | ymx10086 | — | △ | ✓ | ✓ | — | Local-first Research OS with claims/evidence graph, experiment tracking, paper management, skills, and multi-channel access. |
| [Research Claw](https://github.com/nanoAgentTeam/research-claw) ![Stars](https://img.shields.io/github/stars/nanoAgentTeam/research-claw?style=flat-square) | nanoAgentTeam | — | — | ✓ | — | — | Self-hosted academic assistant — paper management, literature search, deadline tracking, and LaTeX/Overleaf sync. |
| [InnoClaw](https://github.com/SpectrAI-Initiative/InnoClaw) ![Stars](https://img.shields.io/github/stars/SpectrAI-Initiative/InnoClaw?style=flat-square) | SpectrAI-Initiative | ✓ | △ | △ | ✓ | △ | Self-hostable AI research workspace — RAG-grounded chat over local files, multimodal paper study (ArXiv/PubMed/bioRxiv/Semantic Scholar), reusable scientific skills, deep research pipeline with multi-role deliberation, and remote HPC/SLURM execution via SSH. |
| [Prismer](https://github.com/Prismer-AI/Prismer) ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | Prismer-AI | — | △ | ✓ | ✓ | △ | End-to-end research platform with PDF reading, Jupyter, LaTeX, code execution, and citation verification. |
| [LabClaw](https://github.com/wu-yc/LabClaw) ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | wu-yc | — | ✓ | ✓ | ✓ | — | 240 OpenClaw skills for biology, pharmacology, medicine, literature, and visualization. |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | meowscles69 | △ | — | ✓ | — | — | 27 skills for academic teams — literature reviews, hypothesis versioning, grant writing, and knowledge handoffs. |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | EESJGong | — | — | — | — | — | OpenClaw skill for academic reading, knowledge linking, reflection, and Obsidian knowledge evolution. |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | henry-y | — | — | — | — | — | Auto-fetches HF Daily Papers and one-click deep reading via SwiftScholar. |
| [Scientify](https://github.com/tsingyuai/scientify) ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | tsingyuai | ✓ | △ | ✓ | ✓ | — | "Continuous metabolism" research system — tracks papers, evolves hypotheses, runs validation, and pushes updates proactively. |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | Gen-Verse | — | — | — | ✓ | — | Turns daily conversations into training signal; async reinforcement learning to personalize OpenClaw or any agent. |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) ![Stars](https://img.shields.io/github/stars/HKUDS/ClawTeam?style=flat-square) | HKUDS | — | — | — | △ | — | Agent Swarm Intelligence — multi-agent coordination; OpenClaw adapted fork: [win4r/ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw). |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | rohunvora | — | — | △ | — | — | Wraps X/Twitter as a terminal research tool — search, thread following, monitoring, and sourced briefings. |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | shenhao-stu | ✓ | — | ✓ | △ | ✓ | One-command setup for 9 specialized agents with Paper Pipeline, Brainstorm, Daily Digest, and Rebuttal built in. |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | MemTensor | — | — | — | — | — | Official MemOS Cloud lifecycle plugin — recall before run, write back to long-term memory after run. |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | joshuaswarren | — | — | — | — | — | Local-first long-term memory layer for agents — markdown storage, hybrid retrieval, cross-session research context. |
| [SkillNet](https://github.com/zjunlp/SkillNet) ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | zjunlp | — | — | — | — | — | Skill creation, evaluation, connection, and discovery infrastructure — searches 300k+ community skills. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | FreedomIntelligence | — | △ | △ | △ | — | 869 medical/biomedical skills spanning clinical, genomics, and drug discovery domains. |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=flat-square) | wanshuiyin | ✓ | △ | ✓ | ✓ | ✓ | Lightweight Markdown-only research workflow — cross-model review loops, idea discovery, and experiment automation. |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) ![Stars](https://img.shields.io/github/stars/OpenLAIR/dr-claw?style=flat-square) | OpenLAIR | ✓ | △ | ✓ | ✓ | △ | AI research IDE with 100+ skills, structured dashboard (Survey → Ideation → Experiment → Publication), auto-research one-click execution, and multi-agent support (Claude Code / Gemini / Codex). |
| [sciClaw](https://github.com/drpedapati/sciclaw) ![Stars](https://img.shields.io/github/stars/drpedapati/sciclaw?style=flat-square) | drpedapati | △ | — | ✓ | ✓ | △ | Paired-scientist agent built on PicoClaw runtime — hypothesis-driven loops, literature search, document tools, shell execution, and auditable evidence trail; accessible via Telegram, Discord, or terminal. |
| [AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs) ![Stars](https://img.shields.io/github/stars/Orchestra-Research/AI-Research-SKILLs?style=flat-square) | Orchestra-Research | ✓ | △ | ✓ | ✓ | △ | 90+ skills for autonomous AI research — two-loop autoresearch orchestration (inner experiment loop + outer synthesis loop), research ideation, ML paper writing with LaTeX templates (NeurIPS/ICML/ICLR/ACL/AAAI/COLM), plus domain skills for training, fine-tuning, evaluation, inference, interpretability, and more; installable via `npx @orchestra-research/ai-research-skills`. |

## Research Agents & AI Scientists

General-purpose autonomous research agents, AI scientist systems, and research benchmarks.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [DeepScientist](https://github.com/ResearAI/DeepScientist) ![Stars](https://img.shields.io/github/stars/ResearAI/DeepScientist?style=flat-square) | ResearAI | ✓ | ✓ | ✓ | ✓ | ✓ | Local-first, git-backed autonomous research system — self-evolving loop with branched experiments, paper drafts, figure generation, and rebuttal workflows; accessible via TUI, web, mobile (Weixin/QQ), and Rokid Glasses. |
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | SamuelSchmidgall | △ | — | ✓ | ✓ | — | End-to-end autonomous research workflow — turns your research ideas into complete experiments and papers. |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | HKUDS | ✓ | — | ✓ | ✓ | — | [NeurIPS 2025] Full-cycle autonomous scientific discovery — literature review, idea generation, experiment execution, and paper writing via dedicated `research_agent` and `paper_agent` modules; production demo at [novix.science](https://novix.science/chat). |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | SakanaAI | ✓ | — | △ | ✓ | — | Workshop-level automated scientific discovery via agentic tree search. |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | tsinghua-fib-lab | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem covering idea generation, experiment design, and paper writing as a holistic blueprint. |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | usail-hkust | — | ✓ | ✓ | ✓ | — | Mathematical modeling agent — problem analysis, modeling, code solving, visualization, and report generation. |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | InternScience | ✓ | — | — | — | — | ACL 2025 project — many-heads multi-agent scientific idea generation. |
| [MLGym](https://github.com/facebookresearch/MLGym) ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | facebookresearch | — | — | — | — | — | Unified framework and benchmark for AI research agents. |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | facebookresearch | — | — | — | △ | — | Extensible AI research agent development and evaluation framework with isolated code execution. |
| [AIRS-Bench](https://github.com/facebookresearch/airs-bench) ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | facebookresearch | — | — | — | — | — | Benchmark for quantifying end-to-end AI research abilities of LLM agents. |
| [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | Ayanami0730 | — | — | — | — | — | Comprehensive benchmark and leaderboard for deep research agents. |

## Deep Research & Frameworks

Deep research agents and foundational frameworks for agent-driven scientific exploration.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | LangChain | — | — | ✓ | — | — | Fully open-source deep research agent — multi-model, multi-search API, MCP support, and built-in report generation. |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | Alibaba-NLP | — | — | △ | — | — | Tongyi Deep Research — the highest-starred open-source deep research agent in this list. |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | MiroMindAI | — | — | △ | — | — | Deep research agent for complex research and prediction tasks; top BrowseComp scores (74.0 / 88.2). |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | MiroMindAI | — | — | — | — | — | Performance-first open-source agent framework — #1 on 5+ benchmarks, supports MiroThinker, Claude, Kimi, OpenAI. |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | Tencent | — | — | — | △ | — | Tencent's deep research agent framework with agent foundation model training. |
| [Simply](https://github.com/google-deepmind/simply) ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | google-deepmind | ✓ | — | — | ✓ | — | Minimal JAX research codebase — designed for agents to read code, propose ideas, run experiments, and iterate. |

## 📖 Papers

### A. Core Papers — End-to-End Research / Experiments / Benchmarks

| Paper | Venue | Year | Authors | Description | Tags | Links |
|-------|-------|------|---------|-------------|------|-------|
| SciMON: Scientific Inspiration Machines Optimized for Novelty | ACL Long | 2024 | Qingyun Wang, Doug Downey, et al. | Formulates research idea generation as literature-grounded novelty optimization. | `idea` `benchmark` | [Paper](https://aclanthology.org/2024.acl-long.18/) |
| MLAgentBench: Evaluating Language Agents on ML Experimentation | ICML | 2024 | Qian Huang, Jian Vora, et al. | Real terminal tasks testing agents on file I/O, code execution, and iterative analysis. | `exp` `benchmark` | [Paper](https://proceedings.mlr.press/v235/huang24y.html) |
| SciCode: A Research Coding Benchmark Curated by Scientists | NeurIPS D&B | 2024 | Minyang Tian, Luyu Gao, et al. | Benchmark for real scientific coding problems emphasizing domain understanding. | `exp` `benchmark` | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/36850592258c8c41cecdaa3dea5ff7de-Abstract-Datasets_and_Benchmarks_Track.html) |
| Can LLMs Generate Novel Research Ideas? | ICLR Poster | 2025 | Chenglei Si, Diyi Yang, Tatsunori Hashimoto | Large-scale human evaluation of LLM-generated research ideas with 100+ NLP researchers. | `idea` `benchmark` | [Paper](https://openreview.net/forum?id=M23dTGWCZy) |
| BioDiscoveryAgent | ICLR Poster | 2025 | Yusuf H. Roohani, Andrew H. Lee, et al. | AI agent for designing genetic perturbation experiments with tool-assisted search and analysis. | `idea` `exp` `review` | [Paper](https://openreview.net/forum?id=HAwZGLcye3) |
| CycleResearcher: Improving Automated Research via Automated Review | ICLR Poster | 2025 | Yixuan Weng, Minjun Zhu, et al. | Closed-loop research–review–revision cycle using reviewer agents. | `writing` `review` | [Paper](https://openreview.net/forum?id=bjcsVLoHYs) |
| ResearchAgent: Iterative Research Idea Generation over Scientific Literature | NAACL Long | 2025 | Jinheon Baek, Sujay Kumar Jauhar, et al. | Iterative idea generation from core papers with ReviewingAgents feedback. | `idea` `exp` `review` | [Paper](https://aclanthology.org/2025.naacl-long.342/) |
| Many Heads Are Better Than One | ACL Long | 2025 | Haoyang Su, Renqi Chen, et al. | Multi-agent collaborative scientific idea generation outperforming single agents. | `idea` | [Paper](https://aclanthology.org/2025.acl-long.1368/) |
| Agent Laboratory: Using LLM Agents as Research Assistants | Findings of EMNLP | 2025 | Samuel Schmidgall, Yusheng Su, et al. | End-to-end: literature review → experimentation → report writing with code repos. | `exp` `writing` | [Paper](https://aclanthology.org/2025.findings-emnlp.320/) · [Code](https://github.com/SamuelSchmidgall/AgentLaboratory) |
| PaperBench: Evaluating AI's Ability to Replicate AI Research | ICML | 2025 | Giulio Starace, Oliver Jaffe, et al. | Agents replicate 20 ICML 2024 papers from scratch with fine-grained rubrics. | `exp` `benchmark` | [Paper](https://proceedings.mlr.press/v267/starace25a.html) |
| MM-Agent: LLM as Agents for Real-world Mathematical Modeling | NeurIPS Poster | 2025 | Fan Liu, Zherui Yang, et al. | Four-stage real mathematical modeling: analysis → modeling → solving → reporting. | `exp` `writing` `benchmark` | [Paper](https://neurips.cc/virtual/2025/poster/116075) · [Code](https://github.com/usail-hkust/LLM-MM-Agent) |
| AI-Researcher: Autonomous Scientific Innovation | NeurIPS Spotlight | 2025 | Jiabin Tang, Lianghao Xia, et al. | Full-cycle autonomous research — survey, hypothesis, implementation, experiments, writing. | `idea` `exp` `writing` `benchmark` | [Paper](https://neurips.cc/virtual/2025/poster/116385) · [Code](https://github.com/HKUDS/AI-Researcher) |
| SciGym: Measuring Scientific Capabilities with a Systems Biology Dry Lab | NeurIPS Poster | 2025 | Haonan Duan, Stephen Lu, et al. | Systems biology dry lab environment evaluating experiment design and result interpretation. | `exp` `benchmark` | [Paper](https://neurips.cc/virtual/2025/poster/121779) |
| MLR-Bench: Evaluating AI Agents on Open-Ended ML Research | NeurIPS | 2025 | Hui Chen, Miao Xiong, et al. | Open-ended ML research: idea → proposal → experiment → paper with automated judging. | `idea` `exp` `writing` `review` `benchmark` | [Paper](https://neurips.cc/virtual/2025/poster/121719) |
| MOOSE-Chem2: Fine-Grained Scientific Hypothesis Discovery via Hierarchical Search | NeurIPS Poster | 2025 | Zonglin Yang, Wanhao Liu, et al. | Refines coarse research directions into executable, method-level hypotheses. | `idea` `benchmark` | [Paper](https://neurips.cc/virtual/2025/poster/118171) |
| SciToolAgent: Knowledge-Graph-Driven Scientific Agent for Multitool Integration | Nature Computational Science | 2025 | Keyan Ding, Jing Yu, et al. | Scientific tool KG for tool selection and orchestration across bio/chem/materials. | `exp` | [Paper](https://doi.org/10.1038/s43588-025-00849-y) |
| Evaluating LLM Agents for Automation of Atomic Force Microscopy | Nature Communications | 2025 | Indrajeet Mandal, Jitendra Soni, et al. | AILA & AFMBench — evaluating LLM agents on real AFM experiment design and instrument operation. | `exp` `benchmark` | [Paper](https://www.nature.com/articles/s41467-025-64105-7) |
| AI Mirrors Experimental Science to Uncover Gene Transfer Mechanism | Cell | 2025 | José R. Penadés, Juraj Gottweis, et al. | AI co-scientist proposes and helps verify biological mechanisms with wet-lab validation. | `idea` `exp` | [Paper](https://doi.org/10.1016/j.cell.2025.08.018) |
| Towards End-to-End Automation of AI Research | Nature | 2026 | Chris Lu, Cong Lu, et al. | Peer-reviewed version of The AI Scientist — full closed-loop automated research. | `idea` `exp` `writing` `review` | [Paper](https://www.nature.com/articles/s41586-026-10265-5) |
| AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite | ICLR Oral | 2026 | Jonathan Bragg, Mike D'Arcy, et al. | 2400+ scientific research questions with controlled tool environments and cost comparability. | `benchmark` | [Paper](https://openreview.net/forum?id=M7TNf5J26u) |
| The Ideation-Execution Gap | ICLR Poster | 2026 | Chenglei Si, Tatsunori Hashimoto, Diyi Yang | LLM ideation advantages shrink significantly after real execution. | `idea` `benchmark` | [Paper](https://openreview.net/forum?id=Fllp8l6Puy) |
| Eigen-Agent: Adaptive Multi-Agent Scientific Reasoning with Monitor-Based RAG | ICLR Poster | 2026 | Xiangru Tang, Wanghan Xu, et al. | Implicit retrieval + structured repair for bio/chem scientific reasoning. | `exp` | [Paper](https://openreview.net/forum?id=bGtmGTbmaz) |
| MoSciBench: Towards Multimodal Data-Driven Scientific Discovery | ICLR Poster | 2026 | Fan Liu, Xiaozhao Zeng, Hao Liu | Multimodal, data-driven, hypothesis-verification scientific discovery benchmark. | `exp` `benchmark` | [Paper](https://openreview.net/forum?id=kZHSvETWdi) |
| IR-Agent: Expert-Inspired LLM Agents for Structure Elucidation from IR Spectra | ICLR Poster | 2026 | Heewoong Noh, Namkyeong Lee, et al. | Multi-agent infrared spectral analysis for unknown molecular structure elucidation. | `exp` | [Paper](https://openreview.net/forum?id=6bthH14pD8) · [Code](https://github.com/HeewoongNoh/IR-Agent) |
| CLADD: RAG-Enhanced Collaborative LLM Agents for Drug Discovery | AAAI | 2026 | Namkyeong Lee, Edward De Brouwer, et al. | Multi-agent + RAG for drug discovery Q&A and evidence synthesis without retraining. | `exp` | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37020) · [Code](https://github.com/Genentech/CLADD) |

### B. Adjacent Papers — Literature Agents / Surveys / Reproduction

| Paper | Venue | Year | Authors | Description | Tags | Links |
|-------|-------|------|---------|-------------|------|-------|
| ArxivDIGESTables: Synthesizing Scientific Literature into Tables | EMNLP | 2024 | Benjamin Newman, Yoonjoo Lee, et al. | Automatically organizes papers into structured literature review tables. | `writing` | [Paper](https://aclanthology.org/2024.emnlp-main.538/) |
| MicroVQA: Multimodal Reasoning Benchmark for Microscopy Research | CVPR | 2025 | James Burgess, Jeffrey J. Nirschl, et al. | Microscopy-based multimodal benchmark testing image understanding and experiment proposals. | `idea` `benchmark` | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Burgess_MicroVQA_A_Multimodal_Reasoning_Benchmark_for_Microscopy-Based_Scientific_Research_CVPR_2025_paper.html) |
| SurveyGen: Quality-Aware Scientific Survey Generation | EMNLP | 2025 | Tong Bao, Mir Tafseer Nayeem, et al. | Quality-aware retrieval for survey generation; finds automated surveys still lag behind humans. | `writing` | [Paper](https://aclanthology.org/2025.emnlp-main.136/) |
| ResearchArena: Benchmarking LLMs as Research Agents | Findings of EMNLP | 2025 | Hao Kang, Chenyan Xiong | Tests LLMs on information discovery, selection, and organization for academic surveys. | `benchmark` | [Paper](https://aclanthology.org/2025.findings-emnlp.303/) |
| LMR-BENCH: Evaluating LLM Agents on Reproducing Language Modeling Research | EMNLP | 2025 | Shuo Yan, Ruochen Li, et al. | Evaluates agents' ability to reproduce LM research code with paper parsing and environment restoration. | `exp` `benchmark` | [Paper](https://aclanthology.org/2025.emnlp-main.314/) |
| SurveyGen-I: Consistent Survey Generation with Evolving Plans | IJCNLP-AACL | 2025 | Jing Chen, Zhiheng Yang, et al. | Evolving plan + memory-guided writing for survey long-text consistency and citation coverage. | `writing` | [Paper](https://aclanthology.org/2025.ijcnlp-long.193/) |
| Reliable Hypothesis Generation: Evaluating Truthfulness and Hallucination | IJCAI Main | 2025 | Guangzhi Xiong, Eric Xie, et al. | Evaluates whether LLM-generated hypotheses are truthful or hallucinated. | `idea` `benchmark` | [Paper](https://www.ijcai.org/proceedings/2025/873) |
| Automating Intervention Discovery from Scientific Literature | IJCAI AI & Social Good | 2025 | Yuting Hu, Dancheng Liu, et al. | Ontology prompting + dual-agent framework for extracting interventions from literature. | `idea` | [Paper](https://www.ijcai.org/proceedings/2025/1078) |
| LitChat: Conversational Exploration of Literature Landscape | IJCAI Demo | 2025 | Mingyu Huang, Shasha Zhou, et al. | Conversational agent for transparent, traceable literature exploration in systematic reviews. | `writing` | [Paper](https://www.ijcai.org/proceedings/2025/1262) |
| Intent-aware Schema Generation for Literature Review Tables | Findings of EMNLP | 2025 | Vishakh Padmakumar, Joseph Chee Chang, et al. | Intent-aware schema generation and refinement for literature review tables. | `writing` | [Paper](https://aclanthology.org/2025.findings-emnlp.1274/) |

### C. Preprints / Workshops / Under Review

| Paper | Status | Year | Authors | Description | Tags | Links |
|-------|--------|------|---------|-------------|------|-------|
| The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery | arXiv preprint | 2024 | Chris Lu, Cong Lu, et al. | Landmark preprint articulating the full automated research vision; peer-reviewed version in Nature 2026. | `idea` `exp` `writing` `review` | [Paper](https://arxiv.org/abs/2408.06292) |
| Towards an AI Co-Scientist | arXiv preprint | 2025 | Juraj Gottweis, Wei-Hung Weng, et al. | Google's Gemini multi-agent co-scientist — generate–debate–evolve hypothesis discovery. | `idea` `exp` | [Paper](https://arxiv.org/abs/2502.18864) |
| BioVerge: Self-Evaluating Agents for Biomedical Hypothesis Generation | NeurIPS 2025 LAW Workshop | 2025 | Fuyi Yang, Chenchen Ye, et al. | Benchmark and self-evaluating agent framework for biomedical hypothesis generation. | `idea` `benchmark` | [Paper](https://neurips.cc/virtual/2025/137205) |
| FIRE-Bench: Evaluating Research Agents on Rediscovery of Scientific Insights | ICLR 2026 submission | 2026 | Zhen Wang, Fan Bai, et al. | Agents must rediscover insights from high-impact papers given only high-level research questions. | `exp` `benchmark` | [Paper](https://openreview.net/forum?id=454tA4k8yJ) |
| PiFlow: Principle-aware Scientific Discovery with Multi-Agent Collaboration | ICLR 2026 submission | 2026 | Yingming Pu, Tao Lin, Hongyu Chen | Principle-aware exploration and evidence linkage for automated scientific discovery. | `idea` `exp` | [Paper](https://openreview.net/forum?id=Is2oXblRtP) |
| From What to Why: Multi-Agent Evidence-based Chemical Reaction Condition Reasoning | ICLR 2026 submission | 2026 | Cheng Yang, Jiaxuan Lu, et al. | Upgrades reaction condition recommendation with evidence and mechanistic explanations. | `exp` | [Paper](https://openreview.net/forum?id=Rh72R0VXPS) |
| SurGE: Benchmark for Scientific Survey Generation | ICLR 2026 submission (withdrawn) | 2026 | Weihang Su, Anzhe Xie, et al. | Benchmark and evaluation protocol for scientific survey generation. | `writing` `benchmark` | [Paper](https://openreview.net/forum?id=hXz1myTe4X) |

---

## Community & Learning

Resources for learning about AI-powered research and the ResearchClaw ecosystem.

### Communities

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — Official community for AutoResearchClaw users and contributors.
- [OpenClaw Community](https://github.com/openclaw/openclaw/discussions) — Discussions around the OpenClaw ecosystem.

### Guides & Tutorials

- [AutoResearchClaw Testing Guide](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — Try the pipeline with your own research idea.
- [ResearchClaw Quick Start](https://ymx10086.github.io/ResearchClaw/) — Official docs for ResearchClaw setup and usage.
- [AutoResearchClaw Integration Guide](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — Integrating with OpenClaw, Claude Code, ACP agents.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
