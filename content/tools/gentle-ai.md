---
title: "Gentle-AI"
description: "A configuration layer that adds persistent memory, a deterministic development workflow, and change-bound review to the coding agent you already use, across 16 supported clients."
category: "Terminal Agent"
website: "https://github.com/Gentleman-Programming/gentle-ai"
pricing: "Free (MIT)"
tags: ["agent", "workflow", "memory", "review", "harness"]
weight: 100
rank: 2
---

A configuration layer for coding agents: it does not install or replace one, it writes a development workflow, skills and a memory layer into the native config of the client you already run.

## Why it stands out

- **Layers onto the agent you already use** across 16 supported clients instead of bundling its own.
- **Review binds to the exact changed bytes.** The candidate is frozen and bound to immutable
  lineage and revision tokens before review, so depth derives from the diff rather than a model's
  judgment about it. Results stay informational and never authorize a commit.
- **Memory stays local.** A single SQLite file with FTS5 search, shareable across a team through
  git, with no hosted service in the loop.

## Good for

Teams that want a repeatable, auditable workflow on the agent they already run.
