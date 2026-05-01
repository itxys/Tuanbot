# Tuanbot Releases / 发行版

<p align="center">
  <img src="./loading.png" alt="Tuanbot Logo" width="720" />
</p>

<p align="center">
  <b>Desktop Pet + AI Assistant</b><br/>
  <sub>Windows / macOS / Linux releases available</sub>
</p>

<p align="center">
  <a href="#-中文">中文</a> · <a href="#-english">English</a> ·
  <a href="https://github.com/itxys/Tuanbot/releases">Releases</a> ·
  <a href="https://github.com/itxys/Tuanbot/issues">Issues</a>
</p>

---

## ⬇️ Latest Downloads

<p align="center">
  <a href="https://github.com/itxys/Tuanbot/releases/latest/download/tuanbot_win_latest.exe">
    <img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows%20x64-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  </a>
</p>

### Current release

- Version: `2026.4.27`
- Release notes: [release-notes-2026.4.27.md](./release-notes-2026.4.27.md)

### Download assets

| Platform | Asset |
| --- | --- |
| Windows x64 | `tuanbot_win_2026.4.27.exe` |
| Windows direct latest link | `tuanbot_win_latest.exe` |
| macOS Apple Silicon | `Tuanbot-2026.4.27-mac-arm64.dmg` |
| macOS Intel | `Tuanbot-2026.4.27-mac-x64.dmg` |
| Linux arm64 | `Tuanbot-2026.4.27-arm64.AppImage` |

### Auto-update metadata

| Platform | Metadata |
| --- | --- |
| Windows | `latest.yml`, `tuanbot_win_2026.4.27.exe.blockmap` |
| macOS | `latest-mac.yml`, `Tuanbot-2026.4.27-mac-arm64.dmg.blockmap`, `Tuanbot-2026.4.27-mac-x64.dmg.blockmap` |
| Linux | `latest-linux-arm64.yml` |

---

## 📌 中文

### 这是什么仓库？
这是 **Tuanbot 的发行版仓库**，用于存放安装包与自动更新所需文件（例如 `latest.yml`、`.blockmap`）。

- Releases：`https://github.com/itxys/Tuanbot/releases`
- 反馈问题：`https://github.com/itxys/Tuanbot/issues`

### ✅ 下载安装
当前提供 Windows、macOS、Linux 安装包：

- Windows（稳定直链）：`tuanbot_win_latest.exe`
- Windows（版本化安装包）：`tuanbot_win_2026.4.27.exe`
- macOS Apple Silicon：`Tuanbot-2026.4.27-mac-arm64.dmg`
- macOS Intel：`Tuanbot-2026.4.27-mac-x64.dmg`
- Linux arm64：`Tuanbot-2026.4.27-arm64.AppImage`

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
| `latest-linux-arm64.yml` | Linux arm64 更新元数据 |

> 普通安装只需要下载对应平台的安装包；`latest.yml` 与 `.blockmap` 主要服务于应用内自动更新。

### 🗺️ 平台支持
- Windows：已支持
- macOS：已支持
- Linux：已支持（arm64 AppImage）

---

## 🌍 English

### What is this repository?
This is the **release-only repository** for Tuanbot. It hosts installers and auto-update metadata (e.g. `latest.yml`, `.blockmap`).

- Releases: `https://github.com/itxys/Tuanbot/releases`
- Issues: `https://github.com/itxys/Tuanbot/issues`

### ✅ Download & Install
Windows, macOS, and Linux installers are available:

- Windows (stable direct link): `tuanbot_win_latest.exe`
- Windows (versioned installer): `tuanbot_win_2026.4.27.exe`
- macOS Apple Silicon: `Tuanbot-2026.4.27-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.4.27-mac-x64.dmg`
- Linux arm64: `Tuanbot-2026.4.27-arm64.AppImage`

Use the download button above to get the latest build.

### 🧩 Files in this repo (Auto-update)
| File | Purpose |
|---|---|
| `tuanbot_win_<version>.exe` | Versioned Windows installer (useful for rollback) |
| `tuanbot_win_latest.exe` | Stable direct link to the latest Windows installer |
| `latest.yml` | Update manifest used by electron-updater |
| `*.blockmap` | Differential update mapping files |
| `latest-mac.yml` | macOS update metadata |
| `latest-linux-arm64.yml` | Linux arm64 update metadata |

> For manual install, you only need the installer for your platform. `latest.yml` and `.blockmap` are primarily for in-app auto updates.

### 🗺️ Platform Support
- Windows: supported now
- macOS: supported now
- Linux: supported now (arm64 AppImage)
