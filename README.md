# CodexMiniBar

<p align="right">
  <a href="README.en.md">English</a> | <strong>简体中文</strong>
</p>

**把 Codex 额度放在眼前，不打断当前工作。**

适用于 Codex 和 VS Code 的轻量 Windows 工具栏，显示额度使用情况、重置倒计时、订阅状态和重置卡。

## 功能亮点

- 吸附在 Codex 或 VS Code 主窗口顶部，跟随窗口移动、最小化和 DPI 变化。
- 折叠状态快速查看账户等级、5 小时额度、每周额度、重置倒计时和重置卡。
- 展开后显示额度进度、重置时间、订阅到期时间和最近更新时间。
- 支持简体中文与 English，并跟随 Codex 的深色、浅色和自定义主题。
- 可分别保存 Codex 与 VS Code 的吸附位置和刷新频率。
- 网络异常时显示明确提示，并自动降低刷新频率。
- Windows 原生 WPF 程序，不需要额外安装 Node.js 或 Python。

## 核心功能演示

### 吸附跟随 Codex 移动

<p align="center">
  <img src="assets/codex-attachment.gif" width="720" alt="CodexMiniBar follows the Codex window while it moves">
</p>

### 外观同步与折叠交互

| 深色 / 浅色外观 | 折叠 / 展开 |
|---|---|
| <img src="assets/theme-switch.gif" width="360" alt="CodexMiniBar switches between dark and light appearance"> | <img src="assets/collapse-expand.gif" width="360" alt="CodexMiniBar collapses and expands"> |

## 产品预览

### 折叠态

| Plus 状态 | Pro 状态 |
|---|---|
| <img src="assets/plus-light-collapsed.png" width="360" alt="Plus light collapsed preview"> | <img src="assets/pro-dark-collapsed.png" width="360" alt="Pro dark collapsed preview"> |

### 展开态

<p align="center">
  <img src="assets/plus-dark-expanded.png" width="480" alt="CodexMiniBar expanded dark preview">
</p>

> 截图使用固定示例数据，不包含真实账户信息。

## 下载

- [Windows x64 免安装版 v1.1.0](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-Windows-x64-v1.1.0.zip) — 下载并解压后，直接运行 `CodexMiniBar.exe`。
- [macOS Apple Silicon v1.1.0](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-macOS-Apple-Silicon.dmg) — 打开 DMG，将 CodexMiniBar 拖入 Applications。

安装包校验文件：[Windows SHA-256](downloads/CodexMiniBar-Windows-x64-v1.1.0.zip.sha256) · [macOS SHA-256](downloads/CodexMiniBar-macOS-Apple-Silicon.dmg.sha256)

## 隐私说明

CodexMiniBar 通过本机 Codex 自带接口只读获取额度信息，不保存 Codex 登录令牌、聊天内容或账户邮箱。

## 系统要求

- Windows 11 x64；已安装并登录 Codex 桌面版，或使用受支持的 VS Code 桌面版作为吸附宿主
- Apple Silicon Mac（M1 或更新），macOS 13 或更高版本

## Copyright

Copyright © 2026 JesseFei87. All rights reserved. Unauthorized copying, redistribution, modification, sale, or resale is prohibited.

CodexMiniBar is an independent third-party utility and is not affiliated with or endorsed by OpenAI or Microsoft. Product names and trademarks belong to their respective owners.
