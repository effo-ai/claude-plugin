# Effo plugins

Connect Effo apps, agents, and workflow runs to ChatGPT, Codex, and Claude.
Sign in with your Effo account and choose your organization. Your existing access
permissions apply. The MCP endpoint is `https://mcp.effo.ai` and uses native HTTP
and OAuth; no local bridge or API key is required.

## Install

In Claude Code, use `/plugin marketplace add OWNER/REPO` with this repository’s GitHub name, then `/plugin install effo@effo`. Complete OAuth with `/mcp`. The plugin for Cowork/Claude Code directory submission is under `plugins/effo`.

Public directory publication requires separate review. Presence in this repository
does not imply approval by either platform.

## Updates

The ChatGPT/Codex and Claude repositories share one release version.
`release.json` identifies this repository’s client and version. Refresh your marketplace
and update the plugin to receive a release; installed clients may require a new
conversation or plugin reload. Claude's official directory can mirror updates
following initial acceptance. OpenAI reviewed snapshots have a separate review
and publish step, so directory rollout dates can differ.

## Included workflows

- Find accessible Effo apps, agents, and workflows.
- Configure an Effo agent draft.
- Investigate execution status and failure logs.

Tool availability depends on your Effo deployment and permissions. The package
contains instructions and connection metadata; the remote service executes tools.

## Privacy and terms

- Website: https://effo.ai
- Privacy: https://effo.ai/legal/privacy
- Terms: https://effo.ai/legal/terms

This repository is generated. Changes must be made in Effo's client-plugins
source package and released together. `release.json` records SHA-256 hashes of
the distributed files for integrity checks.
