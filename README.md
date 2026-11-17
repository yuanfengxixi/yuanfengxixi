# Yuanfeng Xixi

开源贡献方向：浏览器自动化、AI Agent 工作流、Go 服务端，以及微信小程序 / CloudBase 工具。

## Merged contributions

- **TencentCloudBase/CloudBase-AI-Toolkit** — [#1355](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit/pull/1355), [#1356](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit/pull/1356), [#1357](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit/pull/1357): clarified signed storage URL behavior, retained function handlers on ZIP updates, and documented signed-download cache headers. All three PRs were merged.

## Open pull requests

- **chenhg5/cc-connect #2260** — preserves Telegram topic and Feishu thread scope when routing relay workspaces. Maintainer-approved; six CI checks passed; awaiting merge.
- **Tencent/BrowserSkill #739** — reports partial success when the OS constrains a requested window size; CodeCC passed and review is pending.
- **Tencent/BrowserSkill #740, #750, #751, #752** — blank-tab recovery guidance, opt-in native-input clock fallback, explicit idle extension reload, and wheel input recovery when OOPIF visibility measurement stalls. CodeCC passed; review is pending.
- **Tencent/BrowserSkill #760** — bounds Chrome debugger attach waits and fences late completions; CodeCC passed, while GitHub Actions shows `action_required` with no jobs. The PR is open and review is pending; Vivaldi was not available for a live repro.

## Open-source projects

- [knowknow-mini-program](https://github.com/yuanfengxixi/knowknow-mini-program) — sanitized WeChat Mini Program and Tencent CloudBase source, with Node 20/22 CI.
- [obsidian-work-templates](https://github.com/yuanfengxixi/obsidian-work-templates) — nine reusable Obsidian templates; MIT licensed; [v0.1.0](https://github.com/yuanfengxixi/obsidian-work-templates/releases/tag/v0.1.0).
- [wxml-markdown-blocks](https://github.com/yuanfengxixi/wxml-markdown-blocks) — dependency-free Markdown subset parser that produces WeChat Mini Program WXML-friendly blocks.
- [cloudbase-seo-audit](https://github.com/yuanfengxixi/cloudbase-seo-audit) — MIT-licensed CloudBase functions for SSRF-safe public-site checks, shared rate limiting, and cleanup; 12 tests and Node 20/22 CI pass; [v0.1.0](https://github.com/yuanfengxixi/cloudbase-seo-audit/releases/tag/v0.1.0).
- [feishu-paperclip-bridge](https://github.com/yuanfengxixi/feishu-paperclip-bridge) — MIT-licensed Windows/WSL2 networking and process bridge for Feishu bots, cc-connect, and Paperclip; the secret-safe JWT launch fix was merged in [PR #1](https://github.com/yuanfengxixi/feishu-paperclip-bridge/pull/1), with validation and Windows route parsing checks passing.
- [xiaogou](https://github.com/yuanfengxixi/xiaogou) — MIT-licensed Godot 4.6 cultivation roguelike; 352 headless assertions cover player, talent, task, hex, and reincarnation mechanics. CI runs unit tests and Android APK export for code PRs.
- [xhs-video-transcribe](https://github.com/yuanfengxixi/xhs-video-transcribe) — MIT-licensed local video/audio transcription CLI using faster-whisper; 10 tests, Python 3.11/3.12 CI; [v0.1.0](https://github.com/yuanfengxixi/xhs-video-transcribe/releases/tag/v0.1.0).
- [demo_claude](https://github.com/yuanfengxixi/demo_claude) — MIT-licensed `local-media-transcribe` Claude Code plugin for the local CLI; official plugin validation passed with only an optional icon notice, Python 3.11/3.12 CI; [v0.1.1](https://github.com/yuanfengxixi/demo_claude/releases/tag/v0.1.1).
- [yuanfengxixi-website-source](https://github.com/yuanfengxixi/yuanfengxixi-website-source) — MIT-licensed public static website source with an allowlisted build that excludes internal operations data; Node 20/22 CI; [v0.1.0](https://github.com/yuanfengxixi/yuanfengxixi-website-source/releases/tag/v0.1.0).

## Tech

TypeScript · Rust · Go · Python · Node.js · Claude Code · WeChat Mini Program · Tencent CloudBase · Chrome Extensions · JSON Schema
