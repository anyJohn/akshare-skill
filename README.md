# AKShare Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ClawHub Downloads](https://img.shields.io/badge/downloads-1.8k-blue?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmIiBkPSJNOCAwTDAgOGw4IDggOC04TDggMHoiLz48L3N2Zz4=)](https://clawhub.ai/anyjohn/skills/akshare-zh)
[![Security Audit](https://img.shields.io/badge/security-Pass-green)](https://clawhub.ai/anyjohn/skills/akshare-zh)

🚀 **1,800+ downloads on ClawHub!** Thanks for the support.

A [skills.sh](https://skills.sh) compatible skill for getting Chinese financial data via [AKShare](https://github.com/akfamily/akshare).

## What is AKShare?

AKShare is a Python library for fetching financial data from Chinese financial websites (East Money, Sina Finance, SSE, SZSE, etc.). It covers stocks, futures, options, funds, bonds, forex, indices, crypto, and macro economic data.

## Install

### As a Claude Code / Agent Skill

```bash
# Install via skills.sh CLI
npx skills add anyJohn/akshare-skill

# Or clone manually
git clone https://github.com/anyJohn/akshare-skill.git ~/.claude/skills/akshare
```

### Dependencies

```bash
pip install akshare pandas
```

## Usage

Once installed, just ask your AI agent:

```
帮我查一下 A 股 000001 的日 K 线数据
获取中金所期货每日交易数据
查中国国债收益率
```

The agent will use the AKShare skill to fetch the right data.

## Structure

```
akshare-skill/
├── skills/
│   └── akshare/
│       ├── SKILL.md          # Frontmatter + common APIs + usage
│       └── references/
│           └── api-list.md   # 100+ interfaces grouped by category
├── skills.sh.json           # Category metadata
├── README.md
└── LICENSE
```

## License

MIT

[![skills.sh](https://skills.sh/b/anyJohn/akshare-skill)](https://skills.sh/anyJohn/akshare-skill)
