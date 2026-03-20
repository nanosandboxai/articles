---
title: "Linux Runtime Hardening"
type: coming-soon
description: "Reaching production-grade parity on Linux with comprehensive KVM runtime testing and optimization."
tags: [linux, kvm, runtime]
author: "Nanosandbox Team"
---

# Linux Runtime Hardening

The KVM runtime is functional but still in active development. Our top priority is reaching production-grade parity with the macOS runtime.

## What's Working

- VM creation and lifecycle management via libkrun + KVM
- OCI image pulling and layer extraction
- Basic command execution and output streaming
- TSI networking for outbound connections

## What's In Progress

- Comprehensive E2E test coverage on multiple distributions (Ubuntu 22.04+, Fedora 38+, Debian 12+)
- gvproxy networking integration for bridge mode
- Performance optimization for syscall-heavy workloads
- Installation scripts and dependency management for major distributions

## Target

Stable Linux support with full feature parity with the macOS runtime. This means the same `nanosb` CLI, TUI, and SDK will work identically on both platforms.

---

*Nanosandbox is open source. Find us at [github.com/nanosandboxai](https://github.com/nanosandboxai).*
