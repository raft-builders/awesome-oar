# Awesome OAR [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of projects built on OAR (Open Agent Runtime) — one programming interface for all agent harnesses, to control and observe Claude Code, Codex, Pi, Gemini and more.

## Contents

- [Official](#official)
- [Apps and workspaces](#apps-and-workspaces)
- [Agents and bridges](#agents-and-bridges)
- [Plugins and integrations](#plugins-and-integrations)
- [Related lists](#related-lists)

## Official

- [oar](https://github.com/botiverse/oar) ⭐ 796 - Open Agent Runtime: one programming interface for all agent harnesses.
- [`@botiverse/oar`](https://www.npmjs.com/package/@botiverse/oar) - The library: sessions, events, control, host tools and subagents across every runtime.
- [`@botiverse/oar-cli`](https://www.npmjs.com/package/@botiverse/oar-cli) - The `oar` CLI to install, sign in, check usage and models, and run turns against any runtime.

## Apps and workspaces

- [raft-source](https://github.com/botiverse/raft-source) ⭐ 820 - Source of [Raft](https://raft.build), the workspace for humans and agents, whose daemon runs agent runtimes through OAR.
- [eta](https://github.com/0xfe-project/eta) ⭐ 360 - Open-source workbench for always-on agents on your own machines, with external runtimes through OAR.
- [Kaze](https://github.com/jackwener/Kaze) ⭐ 255 - Calm, quick browser for macOS and Windows with a built-in agent that works in tabs of its own, next to yours.
- [ducter](https://github.com/wey-gu/ducter) ⭐ 88 - Personal AI that runs your coding agents on your own computers or servers, with one adapter for four agents through OAR.
- [tmux-agent-deck](https://github.com/RayzPub/tmux-agent-deck) ⭐ 6 - Web terminal control deck for tmux sessions running Claude Code, Antigravity or Codex (Chinese).
- [Kanso](https://kanso.botiverse.build/) - Disk usage analysis and cleanup for Mac, where fixed rules and a coding agent scan together and only what you confirm is deleted.

## Agents and bridges

- [repo-harness](https://github.com/aimpact-inc/repo-harness) ⭐ 436 - CLI, hooks and skills that let Claude, Codex and Pi turn a GitHub issue into a reviewable pull request.
- [agent-bridge](https://github.com/zhoukuncheng/agent-bridge) ⭐ 0 - Self-hosted Slack and Telegram bridge for local coding agents, with OAR as a native runtime adapter.
- [call-cli](https://github.com/Loveacup/call-cli) ⭐ 0 - Delegate work from one coding CLI to others (OMP, Codex, Pi, AGY) locally or over SSH, with an experimental OAR backend.
- [relaydeck](https://github.com/x6nux-oss/relaydeck) ⭐ 0 - Always-on super agent that takes requests from code hosts and chat tools and runs each in its own OAR session (Chinese).
- [sandboxed-agent-builder](https://github.com/AkaraChen/sandboxed-agent-builder) ⭐ 0 - Service that builds Docker images of runnable agents driven by OAR, with build state, logs and retries (Chinese).
- [loom](https://github.com/sun-rs/loom) ⭐ 0 - Resident daemon per project that organises local agent sessions, with headless ones started through OAR (Chinese).
- [`@rien7/agent-center-host`](https://www.npmjs.com/package/@rien7/agent-center-host) - Agent host for Agent Center that claims queued turns and answers them through an OAR runtime.

## Plugins and integrations

- [dsh-agent-team](https://github.com/Contexera/dsh-agent-team) ⭐ 115 - Agent teams for DeepSeek Harness.
- [dudu](https://github.com/weiwenhao/dudu) ⭐ 52 - DeepSeek Harness plugin that runs Claude Code, Codex, Pi and more through OAR, managed with an issue board and phone apps (Chinese and English).
- [dsh-orchestration](https://github.com/myth929/dsh-roles) ⭐ 4 - DeepSeek Harness plugin for role-layered subagents, with per-role model and OAR runtime routing.
- [DSH-Subagent-OAR-AGY](https://github.com/jiezhengj/DSH-Subagent-OAR-AGY) ⭐ 1 - Unofficial DeepSeek Harness plugin that delegates tasks to the local Antigravity CLI with the OAR tool shape.
- [dsh-engine-switch](https://github.com/Goodfun-Studio/dsh-engine-switch) ⭐ 0 - DeepSeek Harness plugin that hands the main session to another agent runtime, such as Pi, through OAR (Chinese).
- [deepseek-ai/deepseek-harness: subagent-oar](https://github.com/deepseek-ai/deepseek-harness/tree/master/packages/experimental/subagent-oar) - Experimental DeepSeek Harness provider that delegates one-shot tasks to Codex and Claude Code through OAR.
- [deepseek-ai/deepseek-harness: tool-subagent-oar](https://github.com/deepseek-ai/deepseek-harness/tree/master/packages/experimental/tool-subagent-oar) - DeepSeek Harness `subagent_oar` tool that picks a configured OAR runtime for each task.

## Related lists

- [awesome-raft-build](https://github.com/raft-builders/awesome-raft-build) ⭐ 9 - Projects for and with Raft, where OAR is built.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
