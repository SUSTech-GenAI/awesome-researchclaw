# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 A curated list of ResearchClaw ecosystem projects, tools, integrations, and resources for AI-powered academic research.

ResearchClaw is an emerging ecosystem of AI-powered research assistants, autonomous paper-writing pipelines, and scientific workflow tools. This list covers the core projects, extensions, related tools, and learning resources.

[中文](README_zh.md)

## Contents

- [OpenClaw Ecosystem & Research Tools](#openclaw-ecosystem--research-tools)
- [Research Agents & AI Scientists](#research-agents--ai-scientists)
- [Deep Research & Frameworks](#deep-research--frameworks)
- [Skills & Plugins](#skills--plugins)
- [Community & Learning](#community--learning)
- [Related Awesome Lists](#related-awesome-lists)

---

> **Capability columns:** I = Idea generation · Fig = Figure / visualization · Write = Writing / drafting · Exp = Experiment / execution · R = Review / rebuttal
> ✓ = Explicitly supported · △ = Indirect / framework capability · — = Not mentioned

## OpenClaw Ecosystem & Research Tools

Projects directly related to the OpenClaw ecosystem — core platforms, skill libraries, plugins, and curated lists.

| # | Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---|---------|-------|---------|---|-----|-------|-----|---|-------------|
| 1 | [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | aiming-lab | 9.7k | △ | ✓ | ✓ | ✓ | ✓ | 23-stage idea → paper pipeline with auto LaTeX, citation verification, experiments, figures, and multi-agent peer review. |
| 2 | [ResearchClaw](https://github.com/ymx10086/ResearchClaw) | ymx10086 | 230 | — | △ | ✓ | ✓ | — | Local-first Research OS with claims/evidence graph, experiment tracking, paper management, skills, and multi-channel access. |
| 3 | [Research Claw](https://github.com/nanoAgentTeam/research-claw) | nanoAgentTeam | 61 | — | — | ✓ | — | — | Self-hosted academic assistant — paper management, literature search, deadline tracking, and LaTeX/Overleaf sync. |
| 4 | [Prismer](https://github.com/Prismer-AI/Prismer) | Prismer-AI | 1k | — | △ | ✓ | ✓ | △ | End-to-end research platform with PDF reading, Jupyter, LaTeX, code execution, and citation verification. |
| 5 | [LabClaw](https://github.com/wu-yc/LabClaw) | wu-yc | 900 | — | ✓ | ✓ | ✓ | — | 240 OpenClaw skills for biology, pharmacology, medicine, literature, and visualization. |
| 6 | [PaperClaw](https://github.com/meowscles69/PaperClaw) | meowscles69 | 152 | △ | — | ✓ | — | — | 27 skills for academic teams — literature reviews, hypothesis versioning, grant writing, and knowledge handoffs. |
| 7 | [scholar-skill](https://github.com/EESJGong/scholar-skill) | EESJGong | 114 | — | — | — | — | — | OpenClaw skill for academic reading, knowledge linking, reflection, and Obsidian knowledge evolution. |
| 8 | [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | henry-y | 83 | — | — | — | — | — | Auto-fetches HF Daily Papers and one-click deep reading via SwiftScholar. |
| 9 | [Awesome Claws](https://github.com/LHL3341/awesome-claws) | LHL3341 | 32 | — | — | — | — | — | Curated index of OpenClaw-related products, skills, communities, and ecosystem resources. |
| 10 | [awesome-autoresearch](https://github.com/alvinunreal/awesome-autoresearch) | alvinunreal | 1.1k | — | — | — | — | — | High-signal index of Karpathy autoresearch forks, research agents, and benchmarks. |
| 11 | [Scientify](https://github.com/tsingyuai/scientify) | tsingyuai | 138 | ✓ | △ | ✓ | ✓ | — | "Continuous metabolism" research system — tracks papers, evolves hypotheses, runs validation, and pushes updates proactively. |
| 12 | [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) | Gen-Verse | 4.4k | — | — | — | ✓ | — | Turns daily conversations into training signal; async reinforcement learning to personalize OpenClaw or any agent. |
| 13 | [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) | win4r | 928 | — | — | — | △ | — | ClawTeam's deep-adapted OpenClaw fork — swarm coordination, worktree isolation, and tmux multi-agent management. |
| 14 | [x-research-skill](https://github.com/rohunvora/x-research-skill) | rohunvora | 1k | — | — | △ | — | — | Wraps X/Twitter as a terminal research tool — search, thread following, monitoring, and sourced briefings. |
| 15 | [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) | shenhao-stu | 351 | ✓ | — | ✓ | △ | ✓ | One-command setup for 9 specialized agents with Paper Pipeline, Brainstorm, Daily Digest, and Rebuttal built in. |
| 16 | [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) | MemTensor | 337 | — | — | — | — | — | Official MemOS Cloud lifecycle plugin — recall before run, write back to long-term memory after run. |
| 17 | [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) | joshuaswarren | 37 | — | — | — | — | — | Local-first long-term memory layer for agents — markdown storage, hybrid retrieval, cross-session research context. |
| 18 | [SkillNet](https://github.com/zjunlp/SkillNet) | ZJUNLP | 625 | — | — | — | — | — | Skill creation, evaluation, connection, and discovery infrastructure — searches 300k+ community skills. |
| 19 | [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | FreedomIntelligence | 1.8k | — | △ | △ | △ | — | 869 medical/biomedical skills spanning clinical, genomics, and drug discovery domains. |
| 20 | [ARIS](https://github.com/zhangchenhaobest/Auto-claude-code-research-in-sleep) | zhangchenhaobest | 0 | ✓ | △ | ✓ | ✓ | ✓ | Lightweight Markdown-only research workflow — cross-model review loops, idea discovery, and experiment automation. |

## Research Agents & AI Scientists

General-purpose autonomous research agents, AI scientist systems, and research benchmarks.

| # | Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---|---------|-------|---------|---|-----|-------|-----|---|-------------|
| 21 | [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | SamuelSchmidgall | 5.5k | △ | — | ✓ | ✓ | — | End-to-end autonomous research workflow — turns your research ideas into complete experiments and papers. |
| 22 | [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | HKUDS | 5k | ✓ | — | ✓ | ✓ | — | Autonomous Scientific Innovation with dedicated `research_agent` and `paper_agent` modules. |
| 23 | [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | SakanaAI | 4.1k | ✓ | — | △ | ✓ | — | Workshop-level automated scientific discovery via agentic tree search. |
| 24 | [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) | Tsinghua FIB Lab | 102 | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem covering idea generation, experiment design, and paper writing as a holistic blueprint. |
| 25 | [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) | HKUST | 499 | — | ✓ | ✓ | ✓ | — | Mathematical modeling agent — problem analysis, modeling, code solving, visualization, and report generation. |
| 26 | [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) | InternScience | 129 | ✓ | — | — | — | — | ACL 2025 project — many-heads multi-agent scientific idea generation. |
| 27 | [MLGym](https://github.com/facebookresearch/MLGym) | Meta FAIR | 593 | — | — | — | — | — | Unified framework and benchmark for AI research agents. |
| 28 | [aira-dojo](https://github.com/facebookresearch/aira-dojo) | Meta FAIR | 136 | — | — | — | △ | — | Extensible AI research agent development and evaluation framework with isolated code execution. |
| 29 | [AIRS-Bench](https://github.com/facebookresearch/airs-bench) | Meta FAIR | 71 | — | — | — | — | — | Benchmark for quantifying end-to-end AI research abilities of LLM agents. |
| 30 | [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) | Ayanami0730 | 651 | — | — | — | — | — | Comprehensive benchmark and leaderboard for deep research agents. |

## Deep Research & Frameworks

Deep research agents and foundational frameworks for agent-driven scientific exploration.

| # | Project | Owner | ⭐ Stars | I | Fig | Write | Exp | R | Description |
|---|---------|-------|---------|---|-----|-------|-----|---|-------------|
| 31 | [open_deep_research](https://github.com/langchain-ai/open_deep_research) | LangChain | 11k | — | — | ✓ | — | — | Fully open-source deep research agent — multi-model, multi-search API, MCP support, and built-in report generation. |
| 32 | [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | Alibaba-NLP | 18.6k | — | — | △ | — | — | Tongyi Deep Research — the highest-starred open-source deep research agent in this list. |
| 33 | [MiroThinker](https://github.com/MiroMindAI/MiroThinker) | MiroMindAI | 8.4k | — | — | △ | — | — | Deep research agent for complex research and prediction tasks; top BrowseComp scores (74.0 / 88.2). |
| 34 | [MiroFlow](https://github.com/MiroMindAI/miroflow) | MiroMindAI | 2.9k | — | — | — | — | — | Performance-first open-source agent framework — #1 on 5+ benchmarks, supports MiroThinker, Claude, Kimi, OpenAI. |
| 35 | [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) | Tencent AI Lab | 505 | — | — | — | △ | — | Tencent's deep research agent framework with agent foundation model training. |
| 36 | [Simply](https://github.com/google-deepmind/simply) | Google DeepMind | 511 | ✓ | — | — | ✓ | — | Minimal JAX research codebase — designed for agents to read code, propose ideas, run experiments, and iterate. |

## Skills & Plugins

Reusable skills and plugins that extend ResearchClaw capabilities.

### Built-in Skills (ResearchClaw)

- `arxiv` — arXiv paper search and download
- `citation_network` — Citation network exploration and visualization
- `experiment_tracker` — Experiment lifecycle management
- `figure_generator` — Academic figure generation
- `literature_review` — Automated literature review workflow
- `paper_summarizer` — Paper summarization and key insight extraction
- `research_notes` — Structured note-taking (paper notes, idea notes, experiment notes)
- `research_workflows` — Multi-stage research workflow management
- `pdf` / `docx` / `pptx` / `xlsx` — Document format support

### AutoResearchClaw Multi-Agent Subsystems

- **CodeAgent** — Multi-phase code generation for experiments
- **BenchmarkAgent** — Automatic dataset discovery and baseline comparison
- **FigureAgent** — 5-agent pipeline: Planner → CodeGen → Renderer → Critic → Integrator
- **Sentinel Watchdog** — Background quality monitor: NaN/Inf detection, citation scoring, anti-fabrication

## Community & Learning

Resources for learning about AI-powered research and the ResearchClaw ecosystem.

### Communities

- [AutoResearchClaw Discord](https://discord.gg/u4ksqW5P) — Official community for AutoResearchClaw users and contributors.
- [OpenClaw Community](https://github.com/openclaw/openclaw/discussions) — Discussions around the OpenClaw ecosystem.

### Guides & Tutorials

- [AutoResearchClaw Testing Guide](https://github.com/aiming-lab/AutoResearchClaw#-were-looking-for-testers) — Try the pipeline with your own research idea.
- [ResearchClaw Quick Start](https://ymx10086.github.io/ResearchClaw/) — Official docs for ResearchClaw setup and usage.
- [AutoResearchClaw Integration Guide](https://github.com/aiming-lab/AutoResearchClaw/blob/main/docs/integration-guide.md) — Integrating with OpenClaw, Claude Code, ACP agents.

### Curated Lists

- [Awesome AI Research Writing](https://github.com/Leey21/awesome-ai-research-writing) — Curated AI research writing resources and tools.
- [Awesome Research](https://github.com/emptymalei/awesome-research) — Research tools covering note-taking, writing, presentation, and more.

## Related Awesome Lists

- [Awesome Claws](https://github.com/LHL3341/awesome-claws) — OpenClaw-related products, skills, communities.
- [Awesome Research](https://github.com/emptymalei/awesome-research) — General research tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.
