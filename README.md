# Tuanbot Releases / 发行版

<p align="center">
  <img src="./loading.png" alt="Tuanbot Logo" width="720" />
</p>

<p align="center">
  <b>Desktop Pet + AI Assistant</b><br/>
  <sub>One version line, cross-platform installers, and a smoother release experience.</sub>
</p>

<p align="center">
  <a href="#-中文">中文</a> · <a href="#-english">English</a> ·
  <a href="https://github.com/itxys/Tuanbot/releases">Releases</a> ·
  <a href="https://github.com/itxys/Tuanbot/issues">Issues</a>
</p>

---

## ✨ Latest Release

<table>
  <tr>
    <td><strong>Version</strong><br/><code>2026.5.5</code></td>
    <td><strong>Build date</strong><br/><code>2026-05-05</code></td>
    <td><strong>Platforms</strong><br/>Windows x64 / macOS arm64 & x64</td>
  </tr>
</table>

- Release notes: [release-notes-2026.5.5.md](./release-notes-2026.5.5.md)
- GitHub Releases: [https://github.com/itxys/Tuanbot/releases/tag/v2026.5.5](https://github.com/itxys/Tuanbot/releases/tag/v2026.5.5)

<p align="center">
  <a href="https://github.com/itxys/Tuanbot/releases/latest/download/tuanbot_win_latest.exe">
    <img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows%20x64-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  </a>
</p>

### What makes this release better

- Built-in skills are available out of the box.
- Chat, settings, inventory, and key surfaces now follow a unified localization layer.
- Release assets, versioning, and README copy are aligned so downloads are easier to understand.

### Download assets

| Platform | Asset |
| --- | --- |
| Windows x64 | `tuanbot_win_2026.5.5.exe` |
| Windows direct latest link | `tuanbot_win_latest.exe` |
| macOS Apple Silicon | `Tuanbot-2026.5.5-mac-arm64.dmg` |
| macOS Intel | `Tuanbot-2026.5.5-mac-x64.dmg` |

### Auto-update metadata

| Platform | Metadata |
| --- | --- |
| Windows | `latest.yml`, `tuanbot_win_2026.5.5.exe.blockmap` |
| macOS | `latest-mac.yml`, `Tuanbot-2026.5.5-mac-arm64.dmg.blockmap`, `Tuanbot-2026.5.5-mac-x64.dmg.blockmap` |

---

## 📌 中文

### 这是什么仓库？
这是 **Tuanbot 的发行版仓库**，用于存放安装包与自动更新所需文件（例如 `latest.yml`、`.blockmap`）。

- Releases：`https://github.com/itxys/Tuanbot/releases`
- 反馈问题：`https://github.com/itxys/Tuanbot/issues`

### ✅ 当前版本

- 版本：`2026.5.5`
- 构建日期：`2026-05-05`
- 覆盖平台：Windows x64、macOS x64/arm64

### ✨ 这次更新的重点

- 内置 Skills 开箱即用，无需用户手动安装
- 聊天、设置、背包等核心界面已接入统一多语言层
- 默认语言会跟随系统语言，用户也可以手动切换
- 发行版 README、release notes 和安装包命名已统一到同一版本号

### ✅ 下载安装

当前提供 Windows、macOS 安装包：

- Windows（稳定直链）：`tuanbot_win_latest.exe`
- Windows（版本化安装包）：`tuanbot_win_2026.5.5.exe`
- macOS Apple Silicon：`Tuanbot-2026.5.5-mac-arm64.dmg`
- macOS Intel：`Tuanbot-2026.5.5-mac-x64.dmg`

点击页面上方按钮即可下载最新版本。

### 🧩 文件说明（自动更新相关）

本仓库可能包含以下文件：

| 文件 | 用途 |
|---|---|
| `tuanbot_win_<version>.exe` | 带版本号的 Windows 安装包（可用于回滚） |
| `tuanbot_win_latest.exe` | 永久固定的最新 Windows 安装包直链 |
| `latest.yml` | electron-updater 用于检测最新版本 |
| `*.blockmap` | 增量更新/差分更新映射文件 |
| `latest-mac.yml` | macOS 更新元数据 |

> 普通安装只需要下载对应平台的安装包；`latest.yml` 与 `.blockmap` 主要服务于应用内自动更新。

### 🗺️ 平台支持

- Windows：已支持
- macOS：已支持

---

## 🌍 English

### What is this repository?
This is the **release-only repository** for Tuanbot. It hosts installers and auto-update metadata (e.g. `latest.yml`, `.blockmap`).

- Releases: `https://github.com/itxys/Tuanbot/releases`
- Issues: `https://github.com/itxys/Tuanbot/issues`

### ✅ Current release

- Version: `2026.5.5`
- Build date: `2026-05-05`
- Platforms: Windows x64, macOS x64/arm64

### ✨ What changed in this release

- Built-in Skills now work out of the box with no manual installation.
- Chat, settings, inventory, and core surfaces now use the same localization layer.
- Default language follows the user's system locale, while manual switching remains available.
- Release notes, README, and package naming are aligned to the same version line.

### ✅ Download & Install

Windows and macOS installers are available:

- Windows (stable direct link): `tuanbot_win_latest.exe`
- Windows (versioned installer): `tuanbot_win_2026.5.5.exe`
- macOS Apple Silicon: `Tuanbot-2026.5.5-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.5.5-mac-x64.dmg`

Use the download button above to get the latest build.

### 🧩 Files in this repo (Auto-update)

| File | Purpose |
|---|---|
| `tuanbot_win_<version>.exe` | Versioned Windows installer (useful for rollback) |
| `tuanbot_win_latest.exe` | Stable direct link to the latest Windows installer |
| `latest.yml` | Update manifest used by electron-updater |
| `*.blockmap` | Differential update mapping files |
| `latest-mac.yml` | macOS update metadata |

> For manual install, you only need the installer for your platform. `latest.yml` and `.blockmap` are primarily for in-app auto updates.

### 🗺️ Platform Support

- Windows: supported now
- macOS: supported now
