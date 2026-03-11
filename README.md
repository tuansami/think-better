<div align="center">

<img src="docs/images/banner.png" alt="Think Better" width="100%">

# Think Better — CEO/Founder Edition

**Your AI writes code fast but makes terrible decisions.**<br>
Think Better injects structured decision frameworks directly into your AI prompts — now enhanced for **CEO/Founder decision-making**, **AI-First projects**, and **personal life planning**.

[![Go 1.25](https://img.shields.io/badge/Go-1.25-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![2 AI Skills](https://img.shields.io/badge/AI_Skills-2-blueviolet?style=flat-square)](.)
[![10+ Frameworks](https://img.shields.io/badge/Frameworks-10+-orange?style=flat-square)](.)  
[![15 Decomposition](https://img.shields.io/badge/Decomposition-15-teal?style=flat-square)](.)
[![16 Biases](https://img.shields.io/badge/Biases-16-red?style=flat-square)](.)
[![18 Mental Models](https://img.shields.io/badge/Mental_Models-18-purple?style=flat-square)](.)
[![4 Depth Levels](https://img.shields.io/badge/Depth-4_Levels-ff69b4?style=flat-square)](.)

[Website](https://thinkbetter.dev/) · [Documentation](USER-GUIDE.md) · [Quick Reference](QUICK-REFERENCE.md) · [Contributing](CONTRIBUTING.md)

**Works with** Claude · GitHub Copilot · Antigravity

</div>

> **Fork Notice:** This is a fork of [HoangTheQuyen/think-better](https://github.com/HoangTheQuyen/think-better) — an excellent open-source project by [@HoangTheQuyen](https://github.com/HoangTheQuyen). This edition extends the original with CEO/Founder-specific frameworks, AI-First project evaluation, founder cognitive biases, and personal life planning support. All original code and data remain under the [MIT License](LICENSE). Full credit to the original author for the core architecture, BM25 search engine, and foundational knowledge base.

<br>

## What's New in This Fork

### 🚀 CEO/Founder-Specific Enhancements

This fork extends Think Better for **founders, CEOs, and builders** who need structured thinking for:

| Category | What's Added |
|----------|-------------|
| **AI-First Projects** | Criteria for evaluating vibe-coded apps, agentic AI tools, AI-native marketing/operations/media products |
| **Startup Evaluation** | Founder-market fit, AI technical feasibility, speed-to-MVP (vibe-codeable), competitive moat |
| **Personal Life** | Career transitions, health investments, work-life balance, travel, relationship priorities |
| **Investment** | Portfolio allocation, angel investing, real estate, crypto — with circle-of-competence check |
| **Pricing & Fundraising** | Freemium vs subscription, bootstrap vs raise, dilution trade-offs |
| **Exit Decisions** | Sell, merge, IPO, wind down — addressing founder identity fusion and IKEA Effect |

### 📊 New Knowledge Records (+25)

| Component | Original | This Fork | Added |
|-----------|----------|-----------|-------|
| Criteria Templates | 8 | **15** | Startup/AI Project, Pricing, Fundraising, Personal Life, Investment, AI Product/Tool |
| Decision Types | 8 | **12** | Personal Life, Innovation Bet/AI-First, Exit/Continuation, Portfolio/Investment |
| Cognitive Biases | 12 | **16** | Shiny Object Syndrome, IKEA Effect, Optimism Bias, FOMO |
| Mental Models | 12 | **18** | Network Effects, Power Law, Compounding, Antifragility, Optionality, Lindy Effect |
| **Total Records** | **~160** | **~185** | **+25** |

### 🧠 Founder-Specific Bias Detection

| Bias | Why It Matters |
|------|---------------|
| **Shiny Object Syndrome** | Jumping between AI projects without finishing any — the #1 founder killer |
| **IKEA Effect** | Overvaluing your own product vs market reality |
| **Optimism Bias** | Projecting 1000 users when base rate is 50-100 |
| **FOMO** | Building AI agents because of LinkedIn hype, not customer demand |

### 💡 New Mental Models for AI/Startup Context

| Model | Application |
|-------|------------|
| **Network Effects** | Understanding platform dynamics, AI ecosystem flywheels |
| **Power Law (Pareto)** | Focus on vital few projects — 1% create 90% of value |
| **Compounding** | Daily 1% improvement = 37x/year. Content, skills, relationships |
| **Antifragility** | Build businesses/portfolios that benefit from uncertainty |
| **Optionality** | Vibe-code 5 cheap MVPs instead of 1 expensive bet |
| **Lindy Effect** | Email marketing (30yr Lindy) > latest social platform (2yr Lindy) |

<br>

---

## The Problem

You ask your AI *"Should we migrate to microservices?"* and get a generic pros/cons list. No framework. No bias detection. No structured analysis. Just vibes.

**Think Better fixes this.** It gives your AI access to 10 decision frameworks, 15 decomposition methods, 16 cognitive bias detectors, 18 mental models, and 185 knowledge records — turning surface-level responses into structured, rigorous analysis.

<br>

## Quick Start

```bash
# macOS / Linux
curl -sSL https://raw.githubusercontent.com/HoangTheQuyen/think-better/main/install.sh | bash

# Windows (PowerShell)
irm https://raw.githubusercontent.com/HoangTheQuyen/think-better/main/install.ps1 | iex
```

Then install skills for your AI:

```bash
think-better init --ai claude        # Claude Code
think-better init --ai copilot       # GitHub Copilot
think-better init --ai antigravity   # Antigravity
```

> **Other install methods:** `go install github.com/HoangTheQuyen/think-better/cmd/make-decision@latest` or clone & `make build`

<br>

## How It Works

Just talk to your AI naturally. Think Better auto-activates when it detects a decision or problem:

```
You: "Should I build an AI marketing agent for SMBs using vibe coding?"

AI:  → Detects: Innovation Bet / AI-First Project
     → Framework: Reversibility Filter
     → Criteria: Startup / AI Project Evaluation
       (founder-market fit, AI feasibility, speed-to-MVP, competitive moat)
     → Warns: Shiny Object Syndrome, FOMO, Optimism Bias
     → Generates: Weighted evaluation + action plan
```

```
You: "Revenue dropped 20% despite market growth"

AI:  → Detects: Opportunity Gap
     → Decomposition: Profitability Tree (MECE)
     → Analysis: Root Cause (5 Whys) + Fermi Estimation
     → Warns: Anchoring Bias, Confirmation Bias
```

```
You: "Should I take a sabbatical or keep grinding?"

AI:  → Detects: Personal Life Decision
     → Criteria: Personal Life Planning
       (fulfillment, relationships, health, financial sustainability, growth, time freedom)
     → Warns: Loss Aversion, Optimism Bias
     → Generates: Life design framework + decision journal
```

<br>

## Two Skills

### `/decide` — For Choices

> *"choose", "compare", "should I", "pros and cons", "nên chon cai nao", "phan van"*

| | |
|---|---|
| **10 Frameworks** | Reversibility Filter, Weighted Matrix, Hypothesis-Driven, Pre-Mortem, Pros-Cons-Fixes... |
| **16 Bias Warnings** | Overconfidence, Anchoring, Sunk Cost, Shiny Object Syndrome, IKEA Effect, FOMO... |
| **15 Criteria Templates** | Technology, Hiring, Startup/AI Project, Pricing, Fundraising, Personal Life, Investment... |
| **Comparison Matrix** | `--matrix "A vs B vs C"` with weighted scoring |
| **Decision Journal** | Track -> Review -> Improve calibration |

### `/solve` — For Problems

> *"solve", "debug", "root cause", "I'm stuck", "tai sao bi vay", "khong biet lam sao"*

| | |
|---|---|
| **7-Step Method** | Define -> Decompose -> Prioritize -> Analyze -> Synthesize -> Communicate |
| **15 Decomposition Frameworks** | Issue Tree, MECE, Hypothesis Tree, Profitability Tree, Systems Map... |
| **18 Mental Models** | First Principles, Inversion, Bayesian Updating, Network Effects, Compounding, Antifragility... |
| **10 Communication Patterns** | Pyramid Principle, BLUF, SCR, Action Titles... |

<br>

## Depth Levels

Control analysis depth with slash commands:

| Command | Depth | Records | Best For |
|---------|-------|---------|----------|
| `/solve.quick` · `/decide.quick` | Quick | 0.5x | Fast scan, simple problems |
| `/solve` · `/decide` | Standard | 1.0x | Default for most situations |
| `/solve.deep` · `/decide.deep` | Deep | 1.7x | Complex, high-stakes decisions |
| `/solve.exec` · `/decide.exec` | Executive | 2.5x | Board reports, stakeholder briefings |

**Examples:**
```
/solve.quick API latency spiked after deploy
/decide.deep Should I build an AI agent or focus on core marketing services?
/solve.exec Revenue declined 20% quarter over quarter
/decide work-life balance as CEO — more income or more time freedom?
```

<br>

## Architecture

```
YOU --- "Should I build an AI marketing agent?" ----------------┐
                                                                │
  ┌─────────────────────────────────────────────────────────────▼──┐
  │  AI ASSISTANT (Claude / Copilot / Antigravity)                 │
  │                                                                │
  │  ┌─ Auto-detect ──────────┐    ┌─ Slash Command ────────────┐ │
  │  │ SKILL.md triggers      │ OR │ /solve.deep -> deep mode   │ │
  │  │ "solve" -> problem-pro │    │ /decide.quick -> quick mode│ │
  │  └────────────┬───────────┘    └────────────┬───────────────┘ │
  │               └───────────┬────────────────┘                  │
  │                           ▼                                    │
  │  ┌────────────────────────────────────────────────────────┐   │
  │  │  🐍 BM25 Search Engine                                 │   │
  │  │  185 records x depth multiplier (0.5x -> 2.5x)        │   │
  │  └────────────────────────┬───────────────────────────────┘   │
  │                           ▼                                    │
  │  ┌────────────────────────────────────────────────────────┐   │
  │  │  📋 Advisor Engine                                      │   │
  │  │  Classify -> Framework -> Bias Detection -> Plan        │   │
  │  └────────────────────────┬───────────────────────────────┘   │
  │                           ▼                                    │
  │  📄 Structured Output + Next-step suggestions                 │
  └───────────────────────────────────────────────────────────────┘
```

<br>

## Step-by-Step Workspace

Add *"save step-by-step"* to any prompt to generate a full markdown workspace:

```
solving-plans/project/               decision-plans/project/
├── 00-OVERVIEW.md                   ├── 00-OVERVIEW.md
├── 01-PROBLEM-DEFINITION.md         ├── 01-DECISION-TYPE.md
├── 02-DECOMPOSITION.md              ├── 02-FRAMEWORK.md
├── 03-PRIORITIZATION.md             ├── 03-CRITERIA.md
├── 04-ANALYSIS-PLAN.md              ├── 04-ANALYSIS.md
├── 05-FINDINGS.md                   ├── 05-OPTIONS.md
├── 06-SYNTHESIS.md                  ├── 06-DECISION.md
├── 07-RECOMMENDATION.md             ├── BIAS-WARNINGS.md
├── BIAS-WARNINGS.md                 └── DECISION-LOG.md
└── DECISION-LOG.md
```

<br>

## CLI Commands

```bash
think-better init             # Install skills for your AI
think-better list             # Show installed skills
think-better check            # Verify prerequisites (Python 3)
think-better uninstall        # Remove skills
think-better version          # Show version
```

<br>

## Project Structure

```
think-better/
├── cmd/make-decision/           # CLI entry point (Go)
├── internal/                    # Core logic
│   ├── skills/                  # Skill registry + embedded data
│   ├── targets/                 # AI platform definitions
│   ├── installer/               # Install/uninstall logic
│   └── cli/                     # Command handlers
├── .agents/
│   ├── skills/
│   │   ├── make-decision/       # Decision skill (SKILL.md, scripts, CSVs)
│   │   └── problem-solving-pro/ # Problem-solving skill
│   └── workflows/               # Slash command definitions
└── specs/                       # Specifications
```

**Stats:** 13 Go files · 7 Python scripts · 16 CSVs (**185 records**) · 8 workflows

<br>

## Requirements

| Method | Requirements |
|--------|-------------|
| Binary download | None -- just run |
| `go install` | Go 1.25+ |
| Build from source | Go 1.25+ |
| Running skills | Python 3 |

<br>

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

<br>

---

<div align="center">

# 🇻🇳 Tiếng Việt

**Ngừng Đoán Mò. Bắt Đầu Tư Duy Có Cấu Trúc.**

AI viết code nhanh nhưng ra quyết định tệ.<br>
Think Better tiêm framework tư duy vào prompt — biến AI thành Staff Engineer.<br>
**Bản CEO/Founder Edition** bổ sung framework cho startup, AI-First, và cuộc sống cá nhân.

</div>

### Cài Đặt

```bash
# macOS / Linux
curl -sSL https://raw.githubusercontent.com/HoangTheQuyen/think-better/main/install.sh | bash

# Windows
irm https://raw.githubusercontent.com/HoangTheQuyen/think-better/main/install.ps1 | iex

# Cài skill
think-better init --ai claude
```

### Cách Dùng

Nói chuyện với AI bình thường — Think Better tự kích hoạt:

| Bạn Nói | AI Làm |
|---------|--------|
| *"Nên chọn công ty lớn hay startup?"* | `make-decision` → Weighted Matrix, cảnh báo Status Quo Bias |
| *"Nên build AI agent hay focus marketing?"* | `make-decision` → Innovation Bet, cảnh báo Shiny Object Syndrome |
| *"So sánh React vs Vue vs Angular"* | Bảng so sánh với tiêu chí có trọng số |
| *"Tại sao doanh thu giảm?"* | `problem-solving-pro` → Issue Tree, Root Cause Analysis |
| *"Bị kẹt, không biết làm sao"* | 7 bước: Định nghĩa → Phân tách → Ưu tiên → Phân tích |
| *"Work-life balance — nên làm gì?"* | Personal Life Decision → Criteria: fulfillment, health, time freedom |

### Tính Năng Mới (CEO/Founder Edition)

- **15 criteria templates** (thêm: Startup/AI, Pricing, Fundraising, Personal Life, Investment, AI Tool)
- **12 decision types** (thêm: Personal Life, Innovation Bet/AI-First, Exit, Portfolio)
- **16 cognitive biases** (thêm: Shiny Object, IKEA Effect, Optimism, FOMO)
- **18 mental models** (thêm: Network Effects, Power Law, Compounding, Antifragility, Optionality, Lindy)

### 2 Skill

**`/decide`** — Chọn lựa
- 10 framework · 16 bias · 15 criteria templates · So sánh đa tiêu chí · Nhật ký quyết định

**`/solve`** — Giải quyết vấn đề
- 7 bước McKinsey · 15 framework phân tách · 18 mô hình tư duy

### Slash Commands

| Lệnh | Khi Nào |
|------|---------|
| `/solve.quick` · `/decide.quick` | Scan nhanh |
| `/solve` · `/decide` | Phân tích chuẩn |
| `/solve.deep` · `/decide.deep` | Phức tạp, high-stakes |
| `/solve.exec` · `/decide.exec` | Báo cáo cho leadership |

```
/solve.quick API chậm sau deploy
/decide.deep Nên build AI agent hay focus core marketing?
/decide work-life balance CEO — more income or more time?
```

### Lưu Ý

- Knowledge base tiếng Anh — AI tự dịch keyword trước khi search
- Cần **Python 3** cho script phân tích
- Hỗ trợ **Claude, Copilot, Antigravity**

---

<div align="center">

**MIT License** · Dự án gốc bởi [@HoangTheQuyen](https://github.com/HoangTheQuyen) · Bản CEO/Founder Edition bởi [@tuansami](https://github.com/tuansami)

**[⭐ Star dự án gốc](https://github.com/HoangTheQuyen/think-better)** · **[⭐ Star bản fork này](https://github.com/tuansami/think-better)**

</div>
