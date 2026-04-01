# AGENTS.md — Awesome ResearchClaw 维护指南

## 项目定位

这是一个 **Awesome 聚合站仓库**，核心目标是：**获取流量 → 引流 → 建立生态影响力 → 获得 Star 和社区贡献**。

参考标杆仓库：
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) — ⭐ 49.5k，Skills 聚合 + 商业引流（Composio 平台）
- [ai-agents-2030/awesome-deep-research-agent](https://github.com/ai-agents-2030/awesome-deep-research-agent) — ⭐ 581，学术论文聚合 + ArXiv survey 引流
- [chchenhui/awesome-research-agents](https://github.com/chchenhui/awesome-research-agents) — ⭐ 7，论文+项目聚合，纯学术列表

---

## 核心策略：从三个标杆仓库学到的增长方法论

### 策略 1：Composio 模式（49.5k Stars）— 实用工具引流

**核心做法：**
- README 顶部放 **Quickstart** — 让用户 30 秒内就能跑起来
- 每个条目都是一个**可直接使用的 Skill 目录**（不只是链接）
- 仓库本身就包含实际可运行代码，不仅仅是链接聚合
- 通过 `connect-apps-plugin` 引流到自家商业平台 `platform.composio.dev`
- 大量社区 PR（352 open PRs）— 让社区为你生产内容

**我们应学习的：**
- [ ] README 顶部放一个 **"30 秒体验 ResearchClaw"** 的 Quickstart 区块
- [ ] 在仓库内放一些可直接 `git clone && 使用` 的模板/配置/示例
- [ ] 引导用户去 ResearchClaw 主仓库、Discord、文档站
- [ ] 降低 PR 门槛，鼓励社区贡献（`CONTRIBUTING.md` + PR 模板 + Good First Issue）

### 策略 2：Deep Research Agent 模式（581 Stars）— 学术权威引流

**核心做法：**
- 绑定一篇 **ArXiv Survey 论文**，仓库是论文的 "活文档"
- 用专业的学术分类法组织（Search Engine / Tool Use / Architecture / Tuning / Benchmarks）
- 每个条目都有 **论文链接 + GitHub 代码链接**（双链结构）
- 提供 BibTeX Citation — 让学术引用反哺仓库流量
- 在论文和仓库之间形成**双向引流闭环**

**我们应学习的：**
- [ ] 增加 **📖 Papers** 分区，按研究阶段分类（Idea → Literature → Experiment → Writing → Review）
- [ ] 每篇论文条目格式：`[时间] 标题 + 作者 + 代码链接`
- [ ] 如果团队有能力，写一篇 Survey 论文绑定此仓库
- [ ] 添加 Citation 区块，方便学术引用

### 策略 3：Awesome Research Agents 模式（7 Stars）— 反面教材

**问题诊断：**
- 纯论文列表，没有社区互动
- 没有 Quickstart、没有可运行代码
- 只有 1 个贡献者
- 没有 Topics 标签优化（只有 `awesome-list ai-assistants llm-agents deep-research`）
- 没有引流闭环

**我们应避免的：**
- ❌ 不要做纯静态论文列表
- ❌ 不要只有一个人维护
- ❌ 不要忽视 GitHub SEO（Topics、Description、Social Preview）

---

## README.md 维护规范

### 结构规范（从上到下的注意力漏斗）

```
1. 标题 + Awesome Badge + Star Badge + PR Badge
2. 一句话描述（中英双语）
3. ⭐ Quickstart 区块（30 秒体验）     ← 参考 Composio
4. 目录（Contents）
5. 核心项目（带 Star 徽章）
6. 📖 论文区（按研究阶段分类）        ← 参考 Deep Research Agent
7. 🔧 工具/项目区（带描述和标签）
8. 数据源/API 表格
9. 社区 & 学习资源
10. Citation（BibTeX）                  ← 参考 Deep Research Agent
11. Contributing + License
```

### 条目格式规范

**项目条目：**
```markdown
- [项目名](链接) — 一句话描述。 ![Stars](shield badge) ![Last Commit](shield badge)
```

**论文条目：**
```markdown
- [时间] [论文标题](ArXiv链接)
  - 作者1, 作者2, ...
  - [代码](GitHub链接) ![Stars](shield badge)
```

### Badge 使用规范

```markdown
<!-- Awesome Badge -->
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- Star Badge（动态）-->
![GitHub Stars](https://img.shields.io/github/stars/用户/仓库?style=flat-square)

<!-- Last Commit Badge -->
![Last Commit](https://img.shields.io/github/last-commit/用户/仓库?style=flat-square)

<!-- PR Welcome Badge -->
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

<!-- License Badge -->
[![CC0](https://img.shields.io/badge/license-CC0-blue.svg)](LICENSE)
```

---

## GitHub SEO 清单

### 必须设置的仓库元数据

- **Description**：`🦞 A curated list of ResearchClaw ecosystem projects, AI research agents, autonomous paper-writing tools, and scientific workflow resources.`
- **Website**：填写文档站或主项目链接
- **Topics**（关键，影响搜索排名）：
  ```
  awesome-list
  researchclaw
  research-agents
  ai-research
  autonomous-research
  paper-writing
  scientific-discovery
  llm-agents
  deep-research
  openclaw
  academic-writing
  literature-review
  ```
- **Social Preview Image**：制作一张 1280×640 的封面图（深色背景 + 🦞 + 标题）

### 提升搜索可见性

- README 中自然使用高频搜索词：`research agent`, `AI paper writing`, `autonomous research`, `deep research`, `literature review AI`, `scientific discovery agent`
- 文件名本身就是 SEO：`awesome-researchclaw` 包含 `awesome` + `research` 关键词

---

## 内容更新策略

### 新增条目的标准

1. **开源或 source-available**（必须有公开仓库）
2. **活跃维护**（最近 3 个月内有 commit）
3. **与 ResearchClaw / 科研自动化 / AI 论文写作相关**
4. **实际可用**（有安装文档、可运行代码、或截图演示）
5. **优先收录有 Star 增长势头的项目**

### 内容更新节奏

- **每周**：检查是否有新的热门项目/论文需要收录
- **每月**：清理失效链接、移除不再维护的项目
- **每季度**：重新审视分类结构，是否需要新增/合并分类

### 追踪信息源

- GitHub Trending（`research agent`, `AI scientist`, `paper writing`）
- ArXiv 每日更新（cs.AI, cs.CL, cs.LG）
- Twitter/X 上的 #ResearchAgent #AIResearch 话题
- OpenClaw / AutoResearchClaw 的 Release 和 Changelog
- Hacker News 和 Reddit r/MachineLearning

---

## 流量增长 Playbook

### Phase 1：基础建设（Week 1-2）

- [x] 创建 README.md 基本结构
- [x] 创建 CONTRIBUTING.md
- [x] 创建 LICENSE (CC0)
- [ ] 添加 Quickstart 区块到 README 顶部
- [ ] 添加 📖 Papers 分区（从 awesome-research-agents 和 awesome-deep-research-agent 搜集论文）
- [ ] 添加 Star/Commit 动态 Badge 到每个项目条目
- [ ] 设置仓库 Topics、Description、Social Preview
- [ ] 创建 PR Template 和 Issue Template
- [ ] 创建 README_zh.md（中文版）

### Phase 2：内容扩充（Week 3-4）

- [ ] 收录 50+ 相关论文（按 Idea / Literature / Experiment / Writing / Review 分类）
- [ ] 收录 30+ 开源项目（每个带 Badge）
- [ ] 添加对比表格（功能矩阵：各项目支持哪些能力）
- [ ] 创建 `examples/` 目录放一些快速上手示例配置
- [ ] 写一篇 Blog Post 介绍这个列表，发布到 Medium / 知乎 / CSDN

### Phase 3：社区驱动（Month 2+）

- [ ] 在 AutoResearchClaw Discord 和 OpenClaw 社区推广
- [ ] 提交到 [sindresorhus/awesome](https://github.com/sindresorhus/awesome) 主列表申请收录
- [ ] 在 Twitter/X 发布，@ 相关项目作者
- [ ] 在 Reddit r/MachineLearning 发帖
- [ ] 在 Hacker News 发 Show HN
- [ ] 给收录的项目发 PR/Issue 请求互链（在他们的 README 中添加本列表的链接）
- [ ] 征集社区 PR（设置 Good First Issue 标签）

### Phase 4：权威建设（Month 3+）

- [ ] 考虑写一篇 Survey 论文绑定此仓库（参考 awesome-deep-research-agent 模式）
- [ ] 创建项目对比网站（GitHub Pages / Vercel）
- [ ] 定期发布 Newsletter（"本周 AI 科研工具动态"）
- [ ] 建立独立的 Star History 追踪页面

---

## 文件结构

```
awesome-researchclaw/
├── README.md                    # 英文主列表
├── README_zh.md                 # 中文版（待创建）
├── CONTRIBUTING.md              # 贡献指南
├── LICENSE                      # CC0 1.0
├── AGENTS.md                    # 本文件：维护指南
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── suggest-resource.md  # 建议新资源的 Issue 模板
│   └── PULL_REQUEST_TEMPLATE.md # PR 模板
└── examples/                    # 快速上手示例（待创建）
    ├── quickstart-researchclaw/ # ResearchClaw 快速配置
    └── quickstart-auto/         # AutoResearchClaw 快速配置
```

---

## 核心差异化定位

与竞品的差异化：

| 维度 | Awesome Claws | Awesome Research Agents | Awesome Deep Research | **Awesome ResearchClaw（我们）** |
|------|--------------|------------------------|----------------------|-------------------------------|
| 定位 | 泛 OpenClaw 生态 | 纯论文列表 | 学术 Survey 配套 | **科研自动化一站式聚合** |
| 内容 | 产品/工具 | 论文 | 论文+产品 | **论文+工具+教程+API+社区** |
| 引流 | OpenClaw 平台 | ArXiv 论文 | ArXiv 论文 | **ResearchClaw 生态全链路** |
| 可运行 | ❌ | ❌ | ❌ | **✅ 含示例配置和 Quickstart** |
| 更新频率 | 低 | 高 | 中 | **持续（每周）** |
| 社区参与 | 低 | 中 | 低 | **高（PR 驱动）** |
| 中英双语 | ✅ | ❌ | ❌ | **✅** |

**一句话定位**：面向科研工作者的 AI 研究工具聚合站——不只是链接列表，是可跑的、有社区的、持续更新的科研自动化指南。
