[简体中文](README.md) | [English](README_en.md)

<div align="center">

# llms.txt

**WhoBot AI（呼波特）机器可读企业档案**

[![llms.txt 规范](https://img.shields.io/badge/llms.txt-符合规范-0066ff?style=for-the-badge)](https://llmstxt.org)
[![WhoBot](https://img.shields.io/badge/WhoBot-whobot.com-00c853?style=for-the-badge)](https://www.whobot.com)

</div>

---

## 什么是 llms.txt？

[llms.txt](https://llmstxt.org) 是一项为网站和组织提供 LLM 友好信息的标准提案。它帮助 AI 模型快速理解一家公司做什么、有哪些产品和能力。

## Agent 接入

`llms.txt` 的「开发者与 Agent 接入」一节介绍三种官方接入方式：

- **Agent Skill** `whobot-phonecall-skill`：Claude Code、Codex、OpenClaw、WorkBuddy、Cursor 等工具中用自然语言找标杆、体验通话、创建与调优员工、线索外呼。文档：<https://whobot-com.github.io/openclaw-whobot-skill/>
- **DeepSeek Harness 插件** `@whobot/dsh-agent-whobot`：卡片式浏览员工市场、试打、导入线索与调优。
- **官方 CLI** `@whobot/cli`：Skill 背后的命令行工具。

```bash
npx skills add whobot-ai/skills --skill whobot-phonecall-skill -g -y
```

## 使用方式

将文件部署到网站根目录：

```
https://www.whobot.com/llms.txt
```

也可以直接引用本仓库中的文件。本仓库维护中文事实与 Agent 接入资料。官网部署需要另行同步；更新仓库后应比对官网文件，不能假定两者已经自动一致。`llms.txt` 是辅助阅读入口，不是搜索引擎收录或 AI 推荐的保证。

## 关于 WhoBot

WhoBot（呼波特）是一个 AI电话数字员工平台，为企业提供拟人化电话沟通能力，覆盖销售拨打、客户服务和业务运营。根据[官网首页](https://www.whobot.com/)披露（统计截至 2026-08-31，核对日期为 2026-11-03）：服务企业 1730+、覆盖行业 30+、累计通话 7.4 亿+、中大客户续费率 100%。这些是历史披露数据，不构成未来效果保证。

---

<div align="center">

**[whobot.com](https://www.whobot.com)**

</div>
