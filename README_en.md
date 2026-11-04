[简体中文](README.md) | [English](README_en.md)

<div align="center">

# llms.txt

**Machine-readable company profile for WhoBot AI (呼波特)**

[![llms.txt spec](https://img.shields.io/badge/llms.txt-spec_compliant-0066ff?style=for-the-badge)](https://llmstxt.org)
[![WhoBot](https://img.shields.io/badge/WhoBot-whobot.com-00c853?style=for-the-badge)](https://www.whobot.com)

</div>

---

## What is llms.txt?

[llms.txt](https://llmstxt.org) is a proposed standard for providing LLM-friendly information about websites and organizations. It helps AI models quickly understand what a company does, its products, and capabilities.

## Agent Integrations

The "开发者与 Agent 接入" (Developer & Agent Integrations) section of `llms.txt` covers three official integrations:

- **Agent Skill** `whobot-phonecall-skill`: find benchmark agents, try calls, create and tune phone digital employees, and run lead outreach from Claude Code, Codex, OpenClaw, WorkBuddy, Cursor and more. Docs: <https://whobot-com.github.io/openclaw-whobot-skill/>
- **DeepSeek Harness plugin** `@whobot/dsh-agent-whobot`: card-based agent marketplace, test calls, lead import and tuning.
- **Official CLI** `@whobot/cli`: the command-line tool behind the Skill.

```bash
npx skills add whobot-ai/skills --skill whobot-phonecall-skill -g -y
```

## Usage

Place the file at your website root:

```
https://www.whobot.com/llms.txt
```

Or reference it directly from this repository. This repository maintains the Chinese fact sheet and agent integration information. Website deployment is a separate step: compare the live file after publishing rather than assuming automatic synchronization. This auxiliary format does not guarantee search indexing or AI recommendations.

## About WhoBot

WhoBot (呼波特) is an AI-powered phone digital employee platform delivering human-like phone conversations for enterprise sales, customer service, and business operations. The [official homepage](https://www.whobot.com/) reports 1,730+ businesses served, 30+ industries, 740M+ cumulative calls, and a 100% mid-to-large client renewal rate, with a statistics cutoff of August 31, 2026 (checked November 3, 2026). These are company-reported historical figures, not a guarantee of future results.

---

<div align="center">

**[whobot.com](https://www.whobot.com)**

</div>
