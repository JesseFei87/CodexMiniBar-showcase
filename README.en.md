# CodexMiniBar

<p align="right">
  <strong>English</strong> | <a href="README.md">简体中文</a>
</p>

**Keep your Codex quota in view, without interrupting your work.**

A lightweight Windows toolbar for Codex and VS Code that displays usage limits, reset timers, subscription status, and reset cards.

## Highlights

- Attaches to the top of the Codex or VS Code main window and follows movement, minimization, and DPI changes.
- The collapsed view provides account plan, five-hour quota, weekly quota, reset countdown, and reset-card information at a glance.
- The expanded home fits quota, subscription, reset cards and monthly Token activity on one screen, with daily usage tooltips.
- Reset announcements and AI hot topics share the same panel, with sources collapsed by default and optional email notifications.
- Tray controls include startup and update checks; the subscription expiry picker supports minute precision.
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

- [Windows x64 portable v1.3.1 (full package)](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/download/v1.3.1/CodexMiniBar-Windows-x64-v1.3.1.zip) — Extract all files and run `CodexMiniBar.exe`. Keep the `.exe.config` file beside the EXE.
- [macOS Apple Silicon v1.1.0](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-macOS-Apple-Silicon.dmg) — Open the DMG and drag CodexMiniBar to Applications.

Package checksums: [Windows SHA-256](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/download/v1.3.1/SHA256SUMS.txt) · [macOS SHA-256](downloads/CodexMiniBar-macOS-Apple-Silicon.dmg.sha256)

[Latest release and release notes](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/latest)

Clients with **Check for updates** can opt into newer versions from the tray. Successful installation restarts the new client and preserves settings. Users of v1.1/v1.2 should exit the old version and manually download and extract the full package above. The fixed-name `CodexMiniBar-Windows-x64-portable.zip` asset is reserved for the built-in updater.

These new features apply to Windows v1.3.1 only. The macOS package is unchanged and does not support window attachment. The demos above may show earlier versions; see the release notes for current changes.

## Privacy

CodexMiniBar reads quota and Token usage without reading conversation content. Its Token fallback uses existing sign-in credentials only in local memory to access the official Profile endpoint; it does not persist them or send them to third parties. AI topics and reset announcements use third-party data sources. Optional email subscriptions send the recipient address you provide to the subscription service, with an unsubscribe option.

## System requirements

- Windows 11 x64 with Codex desktop signed in, or a supported VS Code desktop installation as the attachment host
- Apple Silicon Mac (M1 or later) running macOS 13 or later

## Copyright

Copyright © 2026 JesseFei87. All rights reserved. Unauthorized copying, redistribution, modification, sale, or resale is prohibited.

CodexMiniBar is an independent third-party utility and is not affiliated with or endorsed by OpenAI or Microsoft. Product names and trademarks belong to their respective owners.
