# Nanosandbox Articles

Technical articles exploring sandboxing, isolation, and secure execution environments for AI coding agents.

All content uses YAML frontmatter with `type: article`, `type: coming-soon`, or `type: post` for categorization. Coming-soon entries can include `order` for roadmap sequencing.

## Articles

- [How We See Sandboxing Today](articles/how-we-see-sandboxing-today.md) — A deep dive into why containers aren't enough for autonomous AI agents, what the sandboxing landscape looks like today, and how microVM-based isolation with a dedicated kernel changes the game.
- [Linux Is Hardened. Windows Is Live. The Sandbox Runs Everywhere.](articles/docker-sbx-linux-windows-shipped.md) — Linux KVM is production-grade across major distros, and Windows now has a reliable day-to-day workspace path through WHPX on Windows 11. The article also compares this approach with Docker sbx.

## Coming Soon

- [CLI Desktop App (Tauri Wrapper)](coming-soon/cli-desktop-tauri.md) — Terminal-first desktop wrapper around the nanosb CLI.
- [Multi-language SDKs](coming-soon/multi-language-sdks.md) — First-class SDKs for Python, TypeScript, Go, Rust, Java, and C#.
- [More Code Agents and Continuous Improvements](coming-soon/more-code-agents-and-improvements.md) — Expanded compatibility (Gemini CLI, Grok CLI) and ongoing quality improvements.
- [Code Agent Caging Tournament](coming-soon/code-agent-caging-tournament.md) — Public containment testing with controlled escape challenges.
- [Custom Deep Agent Support](coming-soon/custom-deep-agents.md) — Bring your own deep agents into the sandbox lifecycle.

## Posts

Social media posts published automatically via CI/CD to LinkedIn and X. Each post is a markdown file with platform-specific content sections. Posts are published exactly once — tracked via `posts/.published.json`.

**Format:**

```yaml
---
title: "Post Title"
type: post
date: 2026-03-23
platforms: [linkedin, x]
tags: [tag1, tag2]
author: "Nanosandbox Team"
---

<!-- linkedin -->
LinkedIn content here (up to 3000 chars)...

<!-- x -->
X content here (up to 280 chars)...
```

- [Announce Sandboxing Article](posts/announce-sandboxing-article.md)
