---
title: "Ownkube"
description: "Lets a coding agent deploy and run apps on Ownkube: web services, workers, scheduled jobs, managed Postgres and Valkey, each app on its own HTTPS hostname, through a hosted MCP server with OAuth sign-in."
category: "Dev Tools"
publisher: "Ownkube"
website: "https://ownkube.io/agents"
install: "Remote endpoint https://app.ownkube.io/api/mcp (Claude Code: claude mcp add --transport http ownkube https://app.ownkube.io/api/mcp)"
tags: ["cloud", "deployment", "postgres"]
weight: 220
---

Ownkube's hosted MCP server connects an agent to an Ownkube account. Sign-in happens in the browser over OAuth, so there is no API key to paste into a config file. The agent can deploy a repo from GitHub, add managed Postgres or a Valkey cache, set environment variables, attach domains, and read build logs, runtime logs and metrics. It is listed in the official MCP Registry as `io.ownkube/ownkube`.

## Why it matters

The app an agent writes can go live from the same session, with its database wired in and a public HTTPS URL, without leaving the editor for a dashboard.

## Good for

Shipping side projects and small apps from Claude Code, Cursor, Codex or any client with remote MCP support, then debugging them from the deploy and runtime logs.
