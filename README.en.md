# CodexMiniBar

<p align="right"><a href="README.md">简体中文</a> · <strong>English</strong></p>

### Your quota at a glance. AI news within reach.

A lightweight Windows toolbar attached to Codex or VS Code. Keep **quota, reset credits, Token activity, reset announcements and AI hot topics** in one compact panel. Collapse it while working; expand it for a single-screen overview.

**[Download Windows x64 v1.3.3 — full portable package](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/download/v1.3.3/CodexMiniBar-Windows-x64-v1.3.3.zip)** · [Release notes](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/latest) · [macOS and platform differences](#download-and-update)

## New look: refined geometry, one-screen overview

Centered compact metrics, clear numeric hierarchy, rounded cards and restrained accents. The expanded home fits quota, expiry, reset credits, a Token calendar and feature shortcuts without a vertical scrollbar. It adapts to smaller work areas and high display scaling.

<p align="center"><img src="assets/v1.3.3/collapsed.png" width="400" alt="Redesigned compact toolbar"></p>
<p align="center"><img src="assets/v1.3.3/quota-theme.gif" width="320" alt="Dark and light quota overview"></p>

> New GIFs are slideshows of native application screenshots, not cursor recordings. Quota, Token and email forms use sample data; news and announcements are historical public snapshots, not live claims. Screenshots show the Chinese UI; the app also supports English. Appearance follows Codex theme settings.

### Monthly Token activity

- Monthly total and a full-month heatmap, with hover details for each day.
- Color intensity indicates usage; today is outlined and future dates are subdued.
- Uses source dates without inventing a local-day conversion. Missing days are hatched, not reported as zero.

<p align="center"><img src="assets/v1.3.3/token-calendar.png" width="360" alt="Monthly Token activity and color legend"></p>

## New capabilities, inside the same panel

### AI hot topics: list, detail, sources

Open from home or the tray. Browse ranked titles, source counts and activity times; open details and expand sources only when needed. Returning preserves the list position. Original links and aggregated reports open in your system browser.

<p align="center"><img src="assets/v1.3.3/hot-topics.gif" width="320" alt="Hot-topic list, details and collapsible sources"></p>

Loads on demand and refreshes independently. On failure, cached content remains available with a status indication. No news emails or rotating headlines in the compact toolbar.

### Global reset announcements

- Distinguishes pending announcements, confirmed direct resets and **issued reset credits**.
- Newer credit issuance appears before older pending notices, with the source date, latest post time and scope.
- Unread indicators, refresh, cache messages, original X links and a return to quota.
- Issuing a credit does not mean your personal quota has automatically reset; check your Codex account.

<p align="center"><img src="assets/v1.3.3/reset-credit.png" width="320" alt="Issued reset credit above an older pending notice; historical September 23 snapshot"></p>

### Optional email subscription

Enter and verify an email address for cloud-hosted announcement reminders. Your computer does not need to stay on. Includes verification status, pause/resume, change email, test mail and unsubscribe controls.

<details>
<summary>Show the email subscription form</summary>

<p align="center"><img src="assets/v1.3.3/email-form.png" width="320" alt="Optional email subscription form"></p>

</details>

> Desktop announcements and cloud subscriptions are independent. Disabling the desktop feature does not unsubscribe email. Delivery depends on the cloud service; displaying an issued credit does not imply an email is triggered for that event.

## New tray: consistent dark and light styling

Rounded edges, grouped actions, clear checkmarks and unread indicators, following the Codex appearance.

<p align="center"><img src="assets/v1.3.3/tray-theme.gif" width="234" alt="Dark and light tray menu"></p>

| Group | Commands |
| --- | --- |
| Startup and display | Start with Windows; expand/collapse |
| Quota and subscription | Refresh now; refresh interval; quota alerts; subscription expiry |
| Information | Global reset announcements; AI hot topics |
| Attachment | Attach to Codex; attach to VS Code; reset current position |
| Maintenance | Check for updates; Chinese/English; exit |

### Minute-precision expiry picker

Open the calendar, change month, select a date and set the hour/minute. Clear, cancel and save are supported. Expiry is **entered manually**, not supplied by the Codex API; the countdown uses your local time zone.

<p align="center"><img src="assets/v1.3.3/date-picker.gif" width="340" alt="Date field and expanded minute-precision calendar"></p>

## Complete feature inventory — Windows v1.3.3

| Area | Included |
| --- | --- |
| Attachment | Codex/VS Code hosts; movement, minimization and DPI tracking; drag positioning; separate host positions; reset position |
| Quota | Plan, applicable 5-hour quota, weekly quota, progress bars, reset time/countdown and last refresh |
| Alerts | Optional quota alerts with navigation to the relevant quota area |
| Reset credits | Available count and nearest expiry when supplied |
| Subscription expiry | Manual minute-precision calendar, countdown, save and clear |
| Token activity | Monthly total, daily calendar heatmap, hover details, source dates and missing-data states |
| Announcements | Toggle, unread state, pending notices, confirmed direct resets, issued credits, source links, retained history and cache indicators |
| Hot topics | On-demand list, detail, collapsed sources, original/aggregate links, preserved return position and independent refresh |
| Email | Optional cloud subscription, verification, pause/resume, address change, test email and unsubscribe |
| Appearance | Refined geometry, centered compact metrics, single-screen home, theme-aware tray, redesigned app/tray icons and language switching |
| Refresh | Manual refresh, configurable 10–1800-second interval and slower retries after network errors |
| Installation/update | Portable app, first-run desktop shortcut, optional startup, update checks and notices, opt-in upgrade, restart and configuration preservation |

### Window attachment in action

<p align="center"><img src="assets/codex-attachment.gif" width="720" alt="Recorded Codex window attachment demonstration"></p>

> This earlier-version recording demonstrates attachment behavior only. See the images above for the new visual style. Attachment is Windows-only.

## Download and update

| Platform | Download | Coverage |
| --- | --- | --- |
| Windows x64 v1.3.3 | [Full portable ZIP](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/download/v1.3.3/CodexMiniBar-Windows-x64-v1.3.3.zip) · [SHA-256](https://github.com/JesseFei87/CodexMiniBar-showcase/releases/download/v1.3.3/SHA256SUMS.txt) | New UI and features described above |
| macOS Apple Silicon v1.1.0 | [DMG](https://github.com/JesseFei87/CodexMiniBar-showcase/raw/refs/heads/main/downloads/CodexMiniBar-macOS-Apple-Silicon.dmg) · [SHA-256](downloads/CodexMiniBar-macOS-Apple-Silicon.dmg.sha256) | Existing release; no attachment and not all new Windows features |

**New Windows users:** download the full package, extract everything and run `CodexMiniBar.exe`. Keep `CodexMiniBar.exe.config` alongside it. No Node.js or Python installation is needed.

**Existing update-capable clients:** tray → Check for updates → choose whether to install. Successful upgrades restart the app and preserve configuration/settings.

**v1.1/v1.2:** exit the old app and extract the full new package manually. Check shortcut and startup targets if you change folders.

`CodexMiniBar-Windows-x64-portable.zip` is the in-app updater payload, **not the full first-install package**. On macOS, open the DMG and drag the app into Applications.

## Requirements and data

- Windows 11 x64 / .NET Framework 4.8 and a signed-in Codex desktop app. VS Code can host the toolbar but does not replace Codex sign-in.
- macOS 13+ on Apple Silicon (M1 or newer); features depend on the platform release.
- Quota and Token availability depend on your account and official API responses. Missing values are not fabricated.
- AIHot provides third-party reset/news data, not an official OpenAI announcement service. Titles and statuses remain source-provided.
- Reads quota and Token usage, not conversation content. The Token fallback uses existing credentials only in local memory for the official Profile endpoint; credentials are not persisted or sent to third parties.
- Opting into email sends your chosen address to the subscription service, with unsubscribe available. Desktop and cloud mail availability are independent.

## Copyright

Copyright © 2026 JesseFei87. All rights reserved. Unauthorized copying, redistribution, modification, sale, or resale is prohibited.

CodexMiniBar is an independent third-party utility and is not affiliated with or endorsed by OpenAI or Microsoft. Product names and trademarks belong to their respective owners.
