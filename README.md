# 📊 行业研究方法论 / Industry Research Methodology

<div align="center">

**AI 行业研究框架：从零散信息建立结构化认知体系，L1-L5 数据可信度分层 + 10 个分析模型 + 认知偏差检测**

**A practical industry research framework with L1-L5 data credibility system, 10 analysis models, and cognitive bias detection**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.3-green.svg)]()
[![SKILL.md](https://img.shields.io/badge/Agent%20Skill-SKILL.md-green)](SKILL.md)
[![Platform](https://img.shields.io/badge/Platform-Claude%20Code-orange)]()
[![Platform](https://img.shields.io/badge/Platform-Cursor-brightgreen)]()
[![Language](https://img.shields.io/badge/Language-Chinese--first-red)]()
[![GitHub Stars](https://img.shields.io/github/stars/hyt315/industry-research?style=social)](https://github.com/hyt315/industry-research/stargazers)

[English](#user-content-english) | [中文](#user-content-中文)

</div>

---

<a name="中文"></a>

## 📖 这是什么？

当你需要了解一个新行业时，最大的障碍不是"找不到信息"，而是**不知道应该看哪些维度、如何组织这些信息、怎么判断哪些数据可靠**。

这套方法论解决的就是这个问题——提供一套完整的行业研究框架，让你从零散信息快速建立结构化的行业认知体系。

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🔄 **5 阶段研究流程** | 需求确认 → 素材处理 → 骨架生成 → 分层填充 → 输出交付 |
| 📊 **数据可信度分层（L1-L5）** | 从 AI 生成（L1）到待用户补充（L5），每个数据点都有可信度标签 |
| 🧠 **10 个分析框架精准调用** | PEST、波特五力、护城河、跨越鸿沟……按模块按需匹配 |
| 🛡️ **认知防护机制** | 12 种认知偏差自动检测 + 红队自挑战 |
| 🎯 **3 种执行模式** | 全自动、分步引导、整理已有资料 |
| 📝 **可迭代输出** | 生成 Obsidian 兼容的 Markdown 知识库，能持续更新 |

---

## 🚀 快速开始

### 方式一：AI Agent 直接加载（推荐）

本仓库提供 `SKILL.md`，兼容主流 AI Agent 平台。

**一行命令安装**：

| 平台 | 安装命令 |
|------|----------|
| **Claude Code** | `git clone https://github.com/hyt315/industry-research.git ~/.claude/skills/industry-research` |
| **Codex** | `git clone https://github.com/hyt315/industry-research.git ~/.codex/skills/industry-research` |
| **Cursor** | `git clone https://github.com/hyt315/industry-research.git .cursor/skills/industry-research` |

**手动安装**：
1. 下载本仓库
2. 将 `SKILL.md` 和 `references/` 目录放入你的 AI Agent 的 skills 目录
3. 配置 Obsidian MCP（可选）

详见 [附录 A：环境配置](SKILL.md#附录-a环境配置)。

### 方式二：手动执行

1. 阅读 [SKILL.md](SKILL.md) 了解完整流程
2. 按 Phase 1-5 逐步执行
3. 在 Obsidian（或任意 Markdown 编辑器）中手动创建笔记
4. 参考 [references/](references/) 中的分析框架和输出标准

---

## 📥 下载 / Download

| 方式 | 命令 / 链接 |
|------|------------|
| **HTTPS** | `git clone https://github.com/hyt315/industry-research.git` |
| **SSH** | `git clone git@github.com:hyt315/industry-research.git` |
| **GitHub CLI** | `gh repo clone hyt315/industry-research` |
| **ZIP 源码** | [下载 ZIP](https://github.com/hyt315/industry-research/archive/refs/heads/main.zip) |
| **Tar 源码** | [下载 Tar](https://github.com/hyt315/industry-research/archive/refs/heads/main.tar.gz) |

---

## 💡 核心理念

1. **不假装全能**：精确数据由用户逐步补充，AI 负责框架搭建
2. **价值在结构**："研究一个行业该看哪些维度"本身就是知识
3. **来源可追溯**：每个数据点标注采集日期、来源类型、可信度等级

---

## 📊 数据可信度分层

这是本方法论最核心的创新点：

| 层级 | 标记 | 含义 | 示例 |
|------|------|------|------|
| L1 | `✅ L1-骨架` | 行业结构、分类体系 | "减肥补充剂分为燃脂类、食欲抑制类、GLP-1辅助类" |
| L2 | `✅ L2-公开` | 品牌名、官网、公开报道 | "Goli 官网 https://goligummies.com" |
| L3 | `⚠️ L3-社区` | 用户痛点、社区讨论 | "Reddit 用户反馈：'吃了3个月没效果'" |
| L4 | `⚠️ L4-推断` | AI 基于已有信息的判断 | "市场规模约 15 亿美元（综合估算，需验证）" |
| L5 | `🔲 L5-待填` | 需用户补充的精确数据 | "品牌营收（建议来源：Crunchbase）" |

---

## 📁 文件结构

```
industry-research/
├── SKILL.md                       # 核心方法论（可直接作为 AI Agent Skill 加载）
├── README.md                      # 本文件
├── LICENSE                        # MIT 协议
├── CHANGELOG.md                   # 版本变更记录
├── CONTRIBUTING.md                # 贡献指南
├── CODE_OF_CONDUCT.md             # 行为准则（Contributor Covenant 2.1）
├── SECURITY.md                    # 安全政策
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml         # Bug 报告模板（YAML 表单）
│   │   ├── feature_request.yml    # 功能建议模板（YAML 表单）
│   │   └── config.yml             # 模板选择器配置
│   └── pull_request_template.md   # PR 模板
└── references/                    # 参考文件
    ├── frameworks.md              # 10 个分析框架详解
    ├── cognitive-traps.md         # 认知偏差检测清单
    ├── output-standards.md        # 输出质量标准 + 端到端示例
    └── mcp-setup.md               # Obsidian MCP 配置指南
```

---

## 📚 端到端示例

以**美国减肥补充剂行业**为例，`references/output-standards.md` 中提供了完整的研究产物示意：

- 🏢 品牌文件（Goli Nutrition 示例）
- 📦 产品分类（Fat Burner 分析）
- 👥 用户痛点（Reddit 高频反馈汇总）
- 📺 内容生态（头部创作者地图）
- 🔍 关键词库（按平台和意图双维分类）

详见：[references/output-standards.md](references/output-standards.md)

---

## 🤝 贡献

欢迎贡献新的分析框架、行业模板、改进建议。

详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

---

## 📄 许可

[MIT](LICENSE)

---

<a name="english"></a>

## 📖 What is this?

When you need to understand a new industry, the biggest obstacle isn't "finding information" — it's **not knowing which dimensions to examine, how to organize the information, and how to judge which data is reliable**.

This methodology solves that problem by providing a complete industry research framework that helps you quickly build a structured industry knowledge system from scattered information.

---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🔄 **5-Phase Research Workflow** | Requirements → Material Processing → Skeleton Generation → Layered Filling → Output Delivery |
| 📊 **Data Credibility Tiers (L1-L5)** | From AI-generated (L1) to user-supplied (L5), every data point has a credibility label |
| 🧠 **10 Analysis Frameworks** | PEST, Porter's Five Forces, Moat Theory, Crossing the Chasm... matched by module as needed |
| 🛡️ **Cognitive Defense Mechanism** | 12 cognitive bias auto-detection + red team self-challenge |
| 🎯 **3 Execution Modes** | Fully automatic, step-by-step guided, organize existing materials |
| 📝 **Iterative Output** | Generates Obsidian-compatible Markdown knowledge base that can be continuously updated |

---

## 🚀 Quick Start

### Option 1: AI Agent Direct Loading (Recommended)

This repository provides `SKILL.md`, compatible with mainstream AI Agent platforms.

**One-line install**:

| Platform | Install Command |
|----------|-----------------|
| **Claude Code** | `git clone https://github.com/hyt315/industry-research.git ~/.claude/skills/industry-research` |
| **Codex** | `git clone https://github.com/hyt315/industry-research.git ~/.codex/skills/industry-research` |
| **Cursor** | `git clone https://github.com/hyt315/industry-research.git .cursor/skills/industry-research` |

**Manual install**:
1. Download this repository
2. Place `SKILL.md` and `references/` directory into your AI Agent's skills directory
3. Configure Obsidian MCP (optional)

### Option 2: Manual Execution

1. Read [SKILL.md](SKILL.md) to understand the complete workflow
2. Execute step by step following Phase 1-5
3. Manually create notes in Obsidian (or any Markdown editor)
4. Refer to analysis frameworks and output standards in [references/](references/)

---

## 📁 File Structure

```
industry-research/
├── SKILL.md                       # Core methodology (can be loaded directly as AI Agent Skill)
├── README.md                      # This file
├── LICENSE                        # MIT License
├── CHANGELOG.md                   # Version change log
├── CONTRIBUTING.md                # Contributing guide
├── CODE_OF_CONDUCT.md             # Code of Conduct (Contributor Covenant 2.1)
├── SECURITY.md                    # Security policy
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml         # Bug report template (YAML form)
│   │   ├── feature_request.yml    # Feature request template (YAML form)
│   │   └── config.yml             # Template selector configuration
│   └── pull_request_template.md   # PR template
└── references/                    # Reference files
    ├── frameworks.md              # 10 analysis frameworks detailed
    ├── cognitive-traps.md         # Cognitive bias detection checklist
    ├── output-standards.md        # Output quality standards + end-to-end examples
    └── mcp-setup.md               # Obsidian MCP configuration guide
```

---

## 📚 End-to-End Example

Using the **US Weight Loss Supplement Industry** as an example, `references/output-standards.md` provides complete research output samples:

- 🏢 Brand files (Goli Nutrition example)
- 📦 Product classification (Fat Burner analysis)
- 👥 User pain points (Reddit high-frequency feedback summary)
- 📺 Content ecosystem (top creator map)
- 🔍 Keyword library (dual-dimensional classification by platform and intent)

See: [references/output-standards.md](references/output-standards.md)

---

## 🤝 Contributing

Welcome to contribute new analysis frameworks, industry templates, and improvement suggestions.

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📄 License

[MIT](LICENSE)
