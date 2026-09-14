# CodexMiniBar

<p align="right">
  <strong>English</strong> | <a href="README.md">简体中文</a>
</p>

**Keep your Codex quota in view, without interrupting your work.**

A lightweight Windows toolbar for Codex and VS Code that displays usage limits, reset timers, subscription status, and reset cards.

## Highlights

- Attaches to the top of the Codex or VS Code main window and follows movement, minimization, and DPI changes.
- The collapsed view provides account plan, five-hour quota, weekly quota, reset countdown, and reset-card information at a glance.
- The expanded view shows quota progress, reset times, subscription expiry, and the latest update time.
- Supports Simplified Chinese and English, and follows Codex dark, light, and custom themes.
- Stores attachment position and refresh interval separately for Codex and VS Code.
- Shows clear network-error guidance and automatically backs off refreshes.
- A native Windows WPF application with no extra Node.js or Python installation required.

## Feature demos

### Follows the Codex window

<p align="center">
  <img src="assets/codex-attachment.gif" width="720" alt="CodexMiniBar follows the Codex window while it moves">
</p>

### Theme sync and collapse interaction

| Dark / light appearance | Collapse / expand |
|---|---|
| <img src="assets/theme-switch.gif" width="360" alt="CodexMiniBar switches between dark and light appearance"> | <img src="assets/collapse-expand.gif" width="360" alt="CodexMiniBar collapses and expands"> |

## Product previews

### Collapsed view

| Plus | Pro |
|---|---|
| <img src="assets/plus-light-collapsed.png" width="360" alt="Plus light collapsed preview"> | <img src="assets/pro-dark-collapsed.png" width="360" alt="Pro dark collapsed preview"> |

### Expanded view

<p align="center">
  <img src="assets/plus-dark-expanded.png" width="480" alt="CodexMiniBar expanded dark preview">
</p>

> Screenshots use fixed sample data and contain no real account information.

## Downloads

- [Windows x64 portable v1.1.0](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-Windows-x64-v1.1.0.zip) — Download, extract, and run `CodexMiniBar.exe`.
- [macOS Apple Silicon v1.1.0](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-macOS-Apple-Silicon.dmg) — Open the DMG and drag CodexMiniBar to Applications.

Package checksums: [Windows SHA-256](downloads/CodexMiniBar-Windows-x64-v1.1.0.zip.sha256) · [macOS SHA-256](downloads/CodexMiniBar-macOS-Apple-Silicon.dmg.sha256)

## Privacy

CodexMiniBar reads quota information through a local, built-in Codex interface. It does not store Codex sign-in tokens, conversation content, or account email addresses.

## System requirements

- Windows 11 x64 with Codex desktop signed in, or a supported VS Code desktop installation as the attachment host
- Apple Silicon Mac (M1 or later) running macOS 13 or later

## Copyright

Copyright © 2026 JesseFei87. All rights reserved. Unauthorized copying, redistribution, modification, sale, or resale is prohibited.

CodexMiniBar is an independent third-party utility and is not affiliated with or endorsed by OpenAI or Microsoft. Product names and trademarks belong to their respective owners.
