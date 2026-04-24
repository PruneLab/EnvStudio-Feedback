# EnvStudio Feedback

<p align="right">
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## About EnvStudio

**EnvStudio** is a modern Windows environment variable manager built on WinUI 3. It replaces the 20-year-old "System Properties → Environment Variables" dialog with a native Windows 11 experience.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/en/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/en/cover2.png" width="48%" />
</p>

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## Core Features

- **Intuitive Visual Editor** — Add, edit, delete, and reorder environment variables with a modern WinUI 3 interface.
- **PATH List Management** — Drag-and-drop reordering, deduplication, and dead-link detection for PATH entries.
- **EXE Override Detection** — Scans all directories in PATH for executables and shows which ones are overridden by earlier entries, with one-click jump to the competing entry.
- **Scope Conflict Detection** — When a user variable shadows a system variable with the same name, shows a strikethrough with a warning icon so you always know which value is actually in effect.
- **Non-Destructive Toggle** — Disable a variable without deleting it. Silently renames the registry value, preserving the original data. Re-enable anytime with one click.
- **Delete Safety Checks** — Before deleting a variable, scans all other variables for `%VARNAME%` references and warns about potential breakage.
- **Variable Expansion Preview** — Hover over any value containing `%VAR%` references to see the fully resolved path in a tooltip.
- **External Change Detection** — Monitors the registry in real time. If another program modifies environment variables while EnvStudio is open, you get an immediate notification to refresh.
- **Profile System** — Save, switch, and apply variable profiles for different development environments (e.g., "Java 8", "Node.js", "AI/ML").
- **Snapshot & Rollback** — Automatic snapshots before every change, with Git-style diff view and one-click rollback.
- **Search & Filter** — Quickly find variables across User and System scopes with regex support. Matching PATH sub-entries are automatically expanded with a match count badge.
- **Export** — Export variables to PowerShell, Batch, or .env file formats for team sharing or system recovery.
- **UAC Elevation** — Seamless administrator elevation for editing System variables.
- **Instant Broadcast** — Changes are immediately broadcast to the system via `WM_SETTINGCHANGE`.

## 100% Offline · Completely Free

EnvStudio operates **entirely offline with no telemetry or data collection.** Your environment configuration stays strictly on your own machine.

All features are **completely free** with no ads or paywalls. A donation option may be added in the future, but no features will ever be restricted.

See our [Privacy Policy](https://prunelab.net/products/envstudio/privacy) for details.

---

## Feedback

> **Note:** This repository does **not** contain EnvStudio's source code. It is dedicated to collecting user feedback and issue tracking.

| Action | Link |
|------|------|
| Report a Bug | [Create Bug Report](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| Suggest a Feature | [Submit Feature Request](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| View All Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## Before Reporting

Please search [existing issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) first to avoid duplicates.

When reporting a bug, please include:
- **EnvStudio version** (found in Settings → About)
- **Windows version** (e.g., Windows 11 23H2)
- **Steps to reproduce** the problem
- **Expected behavior** vs **actual behavior**
- Screenshots (if applicable)

## Feature Ideas

We love hearing your ideas! Before submitting:
- Check if someone has already suggested it
- Describe the use case — what problem would this solve?
- Mockups or references are always welcome
