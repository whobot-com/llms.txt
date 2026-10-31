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

也可以直接引用本仓库中的文件。本仓库的 `llms.txt` 与官网 <https://www.whobot.com/llms.txt> 内容同步（中文），并额外收录 Agent 接入信息。

## 关于 WhoBot

WhoBot（呼波特）是一个 AI电话数字员工平台，为企业提供拟人化电话沟通能力，覆盖销售拨打、客户服务和业务运营。服务 300+ 企业客户，覆盖 30+ 行业，累计通话 3 亿+通，中大型客户续约率 100%。

---

<div align="center">

**[whobot.com](https://www.whobot.com)**

</div>
