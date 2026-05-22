---
title: "Announce Linux Hardened, Windows Live Article"
type: post
date: 2026-05-02
platforms: [linkedin, x]
tags: [linux, windows, sandboxing, microvm, launch, article]
author: "Nanosandbox Team"
---

<!-- linkedin -->
Two rows in our roadmap just flipped.

Linux is hardened. Windows is live. The same `nanosb` CLI, the same OCI images, and the same hardware-isolated microVM boundary now run natively on macOS, Linux, and Windows.

v0.2.0 also ships an encrypted secret pipeline for env workflows: X25519 ECDH + AES-256-GCM with one-shot keys. No plaintext on the wire. No `.env` files left behind in the guest.

In the same window, Docker shipped `sbx`, their own microVM sandbox for AI agents. We wrote about both — what's the same, what's different, and why microVM isolation is becoming the baseline for autonomous code execution.

Read the full article: https://nanosandbox.ai/articles/docker-sbx-linux-windows-shipped

#sandboxing #security #AIagents #microVM #linux #windows #nanosandbox

<!-- x -->
v0.2.0 is here.

Linux: hardened across Ubuntu, Debian, Fedora, Arch, openSUSE.
Windows: live on Win 11 via WHPX.
Secrets: encrypted X25519 + AES-256-GCM pipeline, one-shot keys.

Plus a deep comparison with Docker's new `sbx`.

https://nanosandbox.ai/articles/docker-sbx-linux-windows-shipped
