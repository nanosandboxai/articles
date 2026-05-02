# Nanosandbox Articles

Technical articles exploring sandboxing, isolation, and secure execution environments for AI coding agents.

All content uses YAML frontmatter with `type: article`, `type: coming-soon`, or `type: post` for categorization.

## Articles

- [How We See Sandboxing Today](articles/how-we-see-sandboxing-today.md) — A deep dive into why containers aren't enough for autonomous AI agents, what the sandboxing landscape looks like today, and how microVM-based isolation with a dedicated kernel changes the game.
- [Linux Is Hardened. Windows Is Live. The Sandbox Runs Everywhere.](articles/docker-sbx-linux-windows-shipped.md) — Linux KVM is production-grade across major distros. Windows runs via WHPX on Windows 11. And Docker just shipped their own microVM sandbox — here's how the two compare.

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