<div align="center">

# 📋 meeting-notes-to-tickets

**Meeting notes into de-duplicated GitHub, Linear or Jira tickets. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/meeting-notes-to-tickets)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/meeting-notes-to-tickets?style=social)](https://github.com/milad-ahmd/meeting-notes-to-tickets)
![Category](https://img.shields.io/badge/category-Git%20&%20Workflow-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/meeting-notes-to-tickets/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- meeting-notes-to-tickets
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/meeting-notes-to-tickets /tmp/meeting-notes-to-tickets
mkdir -p ~/.claude/skills && cp -r /tmp/meeting-notes-to-tickets/skills/meeting-notes-to-tickets ~/.claude/skills/
```

**Per project:** copy `skills/meeting-notes-to-tickets` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/meeting-notes-to-tickets/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Turn these meeting notes into GitHub issues
Create tickets from this transcript
```

The full workflow, rules and output format are in [`SKILL.md`](skills/meeting-notes-to-tickets/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
