# Awesome ResearchClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🦞 A curated list of ResearchClaw ecosystem projects, tools, integrations, and resources for AI-powered academic research.

ResearchClaw is an emerging ecosystem of AI-powered research assistants, autonomous paper-writing pipelines, and scientific workflow tools. This list covers the core projects, extensions, related tools, and learning resources.

👉 For hands-on experience reports and evaluation scores, check out the [Research Claw Arena](https://sustech-genai.github.io/research-claw-arena/).

[中文](README_zh.md)

## Contents

- [OpenClaw Ecosystem & Research Tools](#openclaw-ecosystem--research-tools)
- [Research Agents & AI Scientists](#research-agents--ai-scientists)
- [Deep Research & Frameworks](#deep-research--frameworks)
- [Community & Learning](#community--learning)

---

> **Capability columns:** I = Idea generation · Fig = Figure / visualization · Write = Writing / drafting · Exp = Experiment / execution · R = Review / rebuttal
> ✓ = Explicitly supported · △ = Indirect / framework capability · — = Not mentioned

## OpenClaw Ecosystem & Research Tools

Projects directly related to the OpenClaw ecosystem — core platforms, skill libraries, plugins, and curated lists.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) ![Stars](https://img.shields.io/github/stars/aiming-lab/AutoResearchClaw?style=flat-square) | aiming-lab | △ | ✓ | ✓ | ✓ | ✓ | 23-stage idea → paper pipeline with auto LaTeX, citation verification, experiments, figures, and multi-agent peer review. |
| [ResearchClaw](https://github.com/ymx10086/ResearchClaw) ![Stars](https://img.shields.io/github/stars/ymx10086/ResearchClaw?style=flat-square) | ymx10086 | — | △ | ✓ | ✓ | — | Local-first Research OS with claims/evidence graph, experiment tracking, paper management, skills, and multi-channel access. |
| [Research Claw](https://github.com/nanoAgentTeam/research-claw) ![Stars](https://img.shields.io/github/stars/nanoAgentTeam/research-claw?style=flat-square) | nanoAgentTeam | — | — | ✓ | — | — | Self-hosted academic assistant — paper management, literature search, deadline tracking, and LaTeX/Overleaf sync. |
| [Prismer](https://github.com/Prismer-AI/Prismer) ![Stars](https://img.shields.io/github/stars/Prismer-AI/Prismer?style=flat-square) | Prismer-AI | — | △ | ✓ | ✓ | △ | End-to-end research platform with PDF reading, Jupyter, LaTeX, code execution, and citation verification. |
| [LabClaw](https://github.com/wu-yc/LabClaw) ![Stars](https://img.shields.io/github/stars/wu-yc/LabClaw?style=flat-square) | wu-yc | — | ✓ | ✓ | ✓ | — | 240 OpenClaw skills for biology, pharmacology, medicine, literature, and visualization. |
| [PaperClaw](https://github.com/meowscles69/PaperClaw) ![Stars](https://img.shields.io/github/stars/meowscles69/PaperClaw?style=flat-square) | meowscles69 | △ | — | ✓ | — | — | 27 skills for academic teams — literature reviews, hypothesis versioning, grant writing, and knowledge handoffs. |
| [scholar-skill](https://github.com/EESJGong/scholar-skill) ![Stars](https://img.shields.io/github/stars/EESJGong/scholar-skill?style=flat-square) | EESJGong | — | — | — | — | — | OpenClaw skill for academic reading, knowledge linking, reflection, and Obsidian knowledge evolution. |
| [openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) ![Stars](https://img.shields.io/github/stars/henry-y/openclaw-paper-tools?style=flat-square) | henry-y | — | — | — | — | — | Auto-fetches HF Daily Papers and one-click deep reading via SwiftScholar. |
| [Scientify](https://github.com/tsingyuai/scientify) ![Stars](https://img.shields.io/github/stars/tsingyuai/scientify?style=flat-square) | tsingyuai | ✓ | △ | ✓ | ✓ | — | "Continuous metabolism" research system — tracks papers, evolves hypotheses, runs validation, and pushes updates proactively. |
| [OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) ![Stars](https://img.shields.io/github/stars/Gen-Verse/OpenClaw-RL?style=flat-square) | Gen-Verse | — | — | — | ✓ | — | Turns daily conversations into training signal; async reinforcement learning to personalize OpenClaw or any agent. |
| [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) ![Stars](https://img.shields.io/github/stars/win4r/ClawTeam-OpenClaw?style=flat-square) | win4r | — | — | — | △ | — | ClawTeam's deep-adapted OpenClaw fork — swarm coordination, worktree isolation, and tmux multi-agent management. |
| [x-research-skill](https://github.com/rohunvora/x-research-skill) ![Stars](https://img.shields.io/github/stars/rohunvora/x-research-skill?style=flat-square) | rohunvora | — | — | △ | — | — | Wraps X/Twitter as a terminal research tool — search, thread following, monitoring, and sourced briefings. |
| [openclaw-agents](https://github.com/shenhao-stu/openclaw-agents) ![Stars](https://img.shields.io/github/stars/shenhao-stu/openclaw-agents?style=flat-square) | shenhao-stu | ✓ | — | ✓ | △ | ✓ | One-command setup for 9 specialized agents with Paper Pipeline, Brainstorm, Daily Digest, and Rebuttal built in. |
| [MemOS-Cloud-OpenClaw-Plugin](https://github.com/MemTensor/MemOS-Cloud-OpenClaw-Plugin) ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS-Cloud-OpenClaw-Plugin?style=flat-square) | MemTensor | — | — | — | — | — | Official MemOS Cloud lifecycle plugin — recall before run, write back to long-term memory after run. |
| [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) ![Stars](https://img.shields.io/github/stars/joshuaswarren/openclaw-engram?style=flat-square) | joshuaswarren | — | — | — | — | — | Local-first long-term memory layer for agents — markdown storage, hybrid retrieval, cross-session research context. |
| [SkillNet](https://github.com/zjunlp/SkillNet) ![Stars](https://img.shields.io/github/stars/zjunlp/SkillNet?style=flat-square) | ZJUNLP | — | — | — | — | — | Skill creation, evaluation, connection, and discovery infrastructure — searches 300k+ community skills. |
| [OpenClaw-Medical-Skills](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) ![Stars](https://img.shields.io/github/stars/FreedomIntelligence/OpenClaw-Medical-Skills?style=flat-square) | FreedomIntelligence | — | △ | △ | △ | — | 869 medical/biomedical skills spanning clinical, genomics, and drug discovery domains. |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=flat-square) | wanshuiyin | ✓ | △ | ✓ | ✓ | ✓ | Lightweight Markdown-only research workflow — cross-model review loops, idea discovery, and experiment automation. |
| [Dr. Claw](https://github.com/OpenLAIR/dr-claw) ![Stars](https://img.shields.io/github/stars/OpenLAIR/dr-claw?style=flat-square) | OpenLAIR | ✓ | △ | ✓ | ✓ | △ | AI research IDE with 100+ skills, structured dashboard (Survey → Ideation → Experiment → Publication), auto-research one-click execution, and multi-agent support (Claude Code / Gemini / Codex). |
| [sciClaw](https://github.com/drpedapati/sciclaw) ![Stars](https://img.shields.io/github/stars/drpedapati/sciclaw?style=flat-square) | drpedapati | △ | — | ✓ | ✓ | △ | Paired-scientist agent built on PicoClaw runtime — hypothesis-driven loops, literature search, document tools, shell execution, and auditable evidence trail; accessible via Telegram, Discord, or terminal. |

## Research Agents & AI Scientists

General-purpose autonomous research agents, AI scientist systems, and research benchmarks.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [AgentLaboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=flat-square) | SamuelSchmidgall | △ | — | ✓ | ✓ | — | End-to-end autonomous research workflow — turns your research ideas into complete experiments and papers. |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=flat-square) | HKUDS | ✓ | — | ✓ | ✓ | — | Autonomous Scientific Innovation with dedicated `research_agent` and `paper_agent` modules. |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=flat-square) | SakanaAI | ✓ | — | △ | ✓ | — | Workshop-level automated scientific discovery via agentic tree search. |
| [OmniScientist](https://github.com/tsinghua-fib-lab/OmniScientist) ![Stars](https://img.shields.io/github/stars/tsinghua-fib-lab/OmniScientist?style=flat-square) | Tsinghua FIB Lab | ✓ | — | ✓ | ✓ | — | AI Scientist ecosystem covering idea generation, experiment design, and paper writing as a holistic blueprint. |
| [LLM-MM-Agent](https://github.com/usail-hkust/LLM-MM-Agent) ![Stars](https://img.shields.io/github/stars/usail-hkust/LLM-MM-Agent?style=flat-square) | HKUST | — | ✓ | ✓ | ✓ | — | Mathematical modeling agent — problem analysis, modeling, code solving, visualization, and report generation. |
| [Virtual-Scientists](https://github.com/InternScience/Virtual-Scientists) ![Stars](https://img.shields.io/github/stars/InternScience/Virtual-Scientists?style=flat-square) | InternScience | ✓ | — | — | — | — | ACL 2025 project — many-heads multi-agent scientific idea generation. |
| [MLGym](https://github.com/facebookresearch/MLGym) ![Stars](https://img.shields.io/github/stars/facebookresearch/MLGym?style=flat-square) | Meta FAIR | — | — | — | — | — | Unified framework and benchmark for AI research agents. |
| [aira-dojo](https://github.com/facebookresearch/aira-dojo) ![Stars](https://img.shields.io/github/stars/facebookresearch/aira-dojo?style=flat-square) | Meta FAIR | — | — | — | △ | — | Extensible AI research agent development and evaluation framework with isolated code execution. |
| [AIRS-Bench](https://github.com/facebookresearch/airs-bench) ![Stars](https://img.shields.io/github/stars/facebookresearch/airs-bench?style=flat-square) | Meta FAIR | — | — | — | — | — | Benchmark for quantifying end-to-end AI research abilities of LLM agents. |
| [DeepResearch Bench](https://github.com/Ayanami0730/deep_research_bench) ![Stars](https://img.shields.io/github/stars/Ayanami0730/deep_research_bench?style=flat-square) | Ayanami0730 | — | — | — | — | — | Comprehensive benchmark and leaderboard for deep research agents. |

## Deep Research & Frameworks

Deep research agents and foundational frameworks for agent-driven scientific exploration.

| Project | Owner | I | Fig | Write | Exp | R | Description |
|---------|-------|---|-----|-------|-----|---|-------------|
| [open_deep_research](https://github.com/langchain-ai/open_deep_research) ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=flat-square) | LangChain | — | — | ✓ | — | — | Fully open-source deep research agent — multi-model, multi-search API, MCP support, and built-in report generation. |
| [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=flat-square) | Alibaba-NLP | — | — | △ | — | — | Tongyi Deep Research — the highest-starred open-source deep research agent in this list. |
| [MiroThinker](https://github.com/MiroMindAI/MiroThinker) ![Stars](https://img.shields.io/github/stars/MiroMindAI/MiroThinker?style=flat-square) | MiroMindAI | — | — | △ | — | — | Deep research agent for complex research and prediction tasks; top BrowseComp scores (74.0 / 88.2). |
| [MiroFlow](https://github.com/MiroMindAI/miroflow) ![Stars](https://img.shields.io/github/stars/MiroMindAI/miroflow?style=flat-square) | MiroMindAI | — | — | — | — | — | Performance-first open-source agent framework — #1 on 5+ benchmarks, supports MiroThinker, Claude, Kimi, OpenAI. |
| [CognitiveKernel-Pro](https://github.com/Tencent/CognitiveKernel-Pro) ![Stars](https://img.shields.io/github/stars/Tencent/CognitiveKernel-Pro?style=flat-square) | Tencent AI Lab | — | — | — | △ | — | Tencent's deep research agent framework with agent foundation model training. |
| [Simply](https://github.com/google-deepmind/simply) ![Stars](https://img.shields.io/github/stars/google-deepmind/simply?style=flat-square) | Google DeepMind | ✓ | — | — | ✓ | — | Minimal JAX research codebase — designed for agents to read code, propose ideas, run experiments, and iterate. |

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
