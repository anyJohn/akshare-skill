# AKShare Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A [skills.sh](https://skills.sh) compatible skill for getting Chinese financial data via [AKShare](https://github.com/akfamily/akshare).

## What is AKShare?

AKShare is a Python library for fetching financial data from Chinese financial websites (East Money, Sina Finance, SSE, SZSE, etc.). It covers stocks, futures, options, funds, bonds, forex, indices, crypto, and macro economic data.

## Install

### As a Claude Code / Agent Skill

```bash
# Clone into your skills directory
git clone https://github.com/anyJohn/akshare-skill.git ~/.claude/skills/akshare

# Or install via skills.sh CLI
npx skills install anyJohn/akshare-skill
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

## Categories

- Stocks (A-share, HK, US, Taiwan)
- Futures (CFFEX, CZCE, DCE, GFEX, INE, SGX)
- Options (50ETF, 300ETF, commodity)
- Funds (open-end, closed-end, ETF, LOF, money market)
- Bonds (treasury, corporate, convertible, US treasury)
- Forex (CNY pairs)
- Indices (domestic, global)
- Crypto
- Macro economy (GDP, CPI, PMI)

## License

MIT
