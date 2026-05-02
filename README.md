# Nanosandbox Articles

Technical articles exploring sandboxing, isolation, and secure execution environments for AI coding agents.

All content uses YAML frontmatter with `type: article`, `type: coming-soon`, or `type: post` for categorization.

## Articles

- [How We See Sandboxing Today](articles/how-we-see-sandboxing-today.md) — A deep dive into why containers aren't enough for autonomous AI agents, what the sandboxing landscape looks like today, and how microVM-based isolation with a dedicated kernel changes the game.
- [Docker Just Proved Containers Aren't Enough — And We Agree](articles/docker-sbx-linux-windows-shipped.md) — Docker shipped sbx, a microVM sandbox for AI agents. Linux is hardened. Windows is live. Here's what that means and where the two approaches diverge.

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