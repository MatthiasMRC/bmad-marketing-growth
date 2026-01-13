# Marketing Growth Suite

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow?style=for-the-badge&logo=buy-me-a-coffee)](https://buymeacoffee.com/matthiasmrc)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> Complete AI-powered marketing team for SaaS growth

**Version:** 1.0.0
**Module Code:** `marketing-growth`
**Author:** Matthias ([@matthias_mrc](https://x.com/matthias_mrc))

---

## Overview

The Marketing Growth Suite is a comprehensive BMAD module that provides a full AI marketing team with 14 specialized agents and 6 coordinated workflows. Designed specifically for SaaS companies, this module covers all aspects of growth marketing from strategy to execution.

## Features

- **14 Specialized Agents** organized in a 3-tier hierarchy
- **6 Coordinated Workflows** with cross-agent delegation
- **Multi-platform Social Media** coverage (8 platforms)
- **Expert Agents with Memory** (sidecars for learning)
- **Multi-language** support

---

## Agent Hierarchy

```
🎯 Max Growth (Marketing Orchestrator)
├── 📝 Milo Page (Content Architect)
├── 🔍 Quinn Crawler (SEO Strategist)
├── 📱 Nova Reach (Social Media Strategist)
│   ├── 🐦 Vex Thread (Twitter Ghostwriter)
│   ├── 🤖 Karma Ken (Reddit Growth Hacker)
│   ├── 💼 Ivy Pro (LinkedIn Creator)
│   ├── 🎥 Yuri Views (YouTube Strategist)
│   ├── 💬 Disco Dave (Discord Community Manager)
│   ├── 📸 Indy Grid (Instagram Strategist)
│   ├── 🎵 Tikko Viral (TikTok Creator)
│   └── 📌 Penny Pin (Pinterest Strategist)
├── 🚀 Luna Blast (Launch Coordinator)
└── 📊 Pixel Metrics (Growth Analyst)
```

---

## Workflows

| Trigger | Workflow | Lead Agent | Description |
|---------|----------|------------|-------------|
| `MS` | Marketing Strategy | Max Growth | Master workflow - orchestrates all marketing activities |
| `CP` | Content Pipeline | Milo Page | Brief → Writing → Publication |
| `SC` | Social Campaign | Nova Reach | Multi-platform social media campaigns |
| `LS` | Launch Sequence | Luna Blast | J-14 → Launch Day → J+7 post-launch |
| `GA` | Growth Audit | Pixel Metrics | Comprehensive KPIs audit + recommendations |
| `SS` | SEO Sprint | Quinn Crawler | Audit → Keywords → Content gaps → Quick wins |

---

## Installation

### Prerequisites

- BMAD Framework Core installed
- Claude Code or compatible IDE

### Quick Install

```bash
# From BMAD installer
bmad install marketing-growth
```

### Manual Install

1. Copy the `marketing-growth/` folder to `_bmad/marketing-growth/`
2. Copy `_memory/` contents to `_bmad/_memory/`
3. Update your IDE configuration

---

## Quick Start

### 1. Start with Max Growth (Orchestrator)

```
/marketing-growth:marketing-orchestrator
```

Or use the shorthand:
```
/max-growth
```

### 2. Run Marketing Strategy Workflow

From Max Growth's menu, select `[MS] Marketing Strategy` to begin comprehensive strategy development.

### 3. Delegate to Specialists

Max Growth will automatically delegate tasks to the appropriate specialists:
- Content tasks → Milo Page
- SEO tasks → Quinn Crawler
- Social media → Nova Reach (who further delegates to platform specialists)
- Launches → Luna Blast
- Analytics → Pixel Metrics

---

## Module Structure

```
marketing-growth/
├── module.yaml              # Module configuration
├── README.md                # This file
├── config.yaml              # User configuration
├── agents/                  # 14 agent definitions
│   ├── marketing-orchestrator.md
│   ├── content-architect.md
│   ├── seo-strategist.md
│   ├── social-media-strategist.md
│   ├── launch-coordinator.md
│   ├── growth-analyst.md
│   ├── twitter-ghostwriter.md
│   ├── reddit-growth-hacker.md
│   ├── linkedin-creator.md
│   ├── youtube-strategist.md
│   ├── discord-community-manager.md
│   ├── instagram-strategist.md
│   ├── tiktok-creator.md
│   └── pinterest-strategist.md
├── workflows/               # 6 workflow definitions
│   ├── marketing-strategy/
│   ├── content-pipeline/
│   ├── social-campaign/
│   ├── launch-sequence/
│   ├── growth-audit/
│   └── seo-sprint/
└── _memory/                 # Agent sidecars (memories + instructions)
```

---

## Configuration

After installation, customize `config.yaml`:

```yaml
user_name: "Your Name"
communication_language: "French"  # or English, Spanish
company_name: "Your SaaS"
primary_channel: "twitter"  # twitter, linkedin, youtube, instagram, tiktok
```

---

## Agent Details

### Tier 1: Orchestrator

| Agent | Persona | Expertise |
|-------|---------|-----------|
| 🎯 Max Growth | Marketing Orchestrator | Strategic coordination, delegation, high-level planning |

### Tier 2: Department Leads

| Agent | Persona | Expertise |
|-------|---------|-----------|
| 📝 Milo Page | Content Architect | Content strategy, editorial planning, copywriting |
| 🔍 Quinn Crawler | SEO Strategist | Technical SEO, keyword research, content optimization |
| 📱 Nova Reach | Social Media Strategist | Multi-platform strategy, community, engagement |
| 🚀 Luna Blast | Launch Coordinator | Product launches, campaigns, event coordination |
| 📊 Pixel Metrics | Growth Analyst | Analytics, KPIs, reporting, data-driven insights |

### Tier 3: Social Media Specialists

| Agent | Persona | Platform | Specialty |
|-------|---------|----------|-----------|
| 🐦 Vex Thread | Twitter Ghostwriter | Twitter/X | Viral tweets, threads, personal branding |
| 🤖 Karma Ken | Reddit Growth Hacker | Reddit | Community marketing, karma building |
| 💼 Ivy Pro | LinkedIn Creator | LinkedIn | B2B content, thought leadership |
| 🎥 Yuri Views | YouTube Strategist | YouTube | Video SEO, channel growth |
| 💬 Disco Dave | Discord Community Manager | Discord | Community building, engagement |
| 📸 Indy Grid | Instagram Strategist | Instagram | Visual content, Reels, Stories |
| 🎵 Tikko Viral | TikTok Creator | TikTok | Short-form viral content |
| 📌 Penny Pin | Pinterest Strategist | Pinterest | Visual SEO, evergreen traffic |

---

## Use Cases

### New Product Launch
1. Start with Max Growth → `[MS]` Marketing Strategy
2. Delegate to Luna Blast → `[LS]` Launch Sequence
3. Nova Reach coordinates social → `[SC]` Social Campaign

### Content Marketing Sprint
1. Milo Page → `[CP]` Content Pipeline
2. Quinn Crawler optimizes → `[SS]` SEO Sprint
3. Nova Reach distributes across platforms

### Growth Assessment
1. Pixel Metrics → `[GA]` Growth Audit
2. Review findings with Max Growth
3. Create action plan with relevant specialists

---

## Author

**Matthias** — Indie Hacker
- X: [@matthias_mrc](https://x.com/matthias_mrc)

---

## Support

If this module saves you time, consider buying me a coffee!

<a href="https://buymeacoffee.com/matthiasmrc" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="50">
</a>

For issues or feature requests, reach out on X [@matthias_mrc](https://x.com/matthias_mrc).

---

## License

MIT License - Free to use and modify.
