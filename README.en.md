# 📊 Industry Research Methodology

> 🌏 **中文版: [README.md](./README.md)**

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/version-1.0.0-green.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Agent%20Skill-SKILL.md-green.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Claude%20Code-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Cursor-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Language-Chinese--first-red?style=flat-square" />
  <img src="https://img.shields.io/github/stars/hyt315/industry-research?style=flat-square&color=yellow" />
</p>

---

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

See [Appendix A: Environment Configuration](SKILL.md#appendix-a-environment-configuration).

### Option 2: Manual Execution

1. Read [SKILL.md](SKILL.md) to understand the complete workflow
2. Execute step by step following Phase 1-5
3. Manually create notes in Obsidian (or any Markdown editor)
4. Refer to analysis frameworks and output standards in [references/](references/)

---

## 💡 Core Philosophy

1. **Don't pretend to know everything**: Precise data is gradually supplemented by users, AI handles framework construction
2. **Value lies in structure**: "Which dimensions to examine when researching an industry" is itself knowledge
3. **Traceable sources**: Every data point is labeled with collection date, source type, and credibility level

---

## 📊 Data Credibility Tiers

This is the core innovation of this methodology:

| Tier | Label | Meaning | Example |
|------|-------|---------|---------|
| L1 | `✅ L1-Skeleton` | Industry structure, classification system | "Weight loss supplements are divided into fat burners, appetite suppressants, and GLP-1 support" |
| L2 | `✅ L2-Public` | Brand names, official websites, public reports | "Goli website https://goligummies.com" |
| L3 | `⚠️ L3-Community` | User pain points, community discussions | "Reddit user feedback: 'Took it for 3 months, zero change'" |
| L4 | `⚠️ L4-Inference` | AI judgment based on available information | "Market size approximately $1.5 billion (comprehensive estimate, needs verification)" |
| L5 | `🔲 L5-Pending` | Precise data to be supplemented by users | "Brand revenue (suggested source: Crunchbase)" |

---

## 📁 File Structure

```
industry-research/
├── SKILL.md                       # Core methodology (can be loaded directly as AI Agent Skill)
├── README.md                      # Chinese version
├── README.en.md                   # This file (English)
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
