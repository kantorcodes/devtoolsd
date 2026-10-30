---
name: HOL Guard
slug: hol-guard
website: https://hol.org/guard
description: Local-first open-source security controls for AI coding agents, MCP tools, plugins, and package installs.
tool_type: cli
pricing: free
open_source: true
license: Apache-2.0
github: hashgraph-online/hol-guard
logo: https://hol.org/brand/Logo_Whole_Dark.png
docs_url: https://github.com/hashgraph-online/hol-guard/blob/main/docs/guard/get-started.md
categories:
  - cli-tools
  - terminal-tools
tags:
  - security
  - ai-agents
  - mcp
  - supply-chain
platforms:
  - macos
  - linux
  - windows
languages:
  - python
language: python
features:
  - Reviews supported agent shell commands, file-access events, and package installs
  - Inspects supported MCP tool calls and local agent configurations
  - Provides local approvals, policy decisions, and receipt history
install: |
  pipx install hol-guard
  hol-guard init
company: HOL
featured: false
---

HOL Guard reviews supported AI-agent actions before execution through native hooks and managed proxies. Coverage varies by agent integration; see the [support matrix](https://github.com/hashgraph-online/hol-guard/blob/main/docs/guard/harness-support.md) for the exact enforcement and approval paths. The CLI and local dashboard work without an account; optional cloud features are separate.
