# Tuanbot 2026.5.11 更新说明 / Release Notes

## 中文

### 范围

- 上一个公开版本：`2026.5.6`
- 当前版本：`2026.5.11`
- 平台：Windows x64、macOS x64/arm64
- 构建日期：`2026-05-11`

### 亮点

#### 1. Skill 与 MCP 链路优化

- 优化了 Skills 的调用与执行链路，常用操作的响应更稳定
- MCP 工具接入和启动流程做了稳定性整理，减少了工具编排时的卡顿和失败
- 底层 OpenCode 相关执行链路也做了整理，提升工具调度时的整体顺滑度

#### 2. 一批 bug 修复与稳定性改进

- 修复了若干界面与运行时问题，降低长时间运行后的卡顿与显示异常
- 优化了全局输入、拖拽和更新相关流程的稳定性
- 提升了整体运行时的顺滑度和可用性

#### 3. 发行版版本号与今天日期对齐

- 本次发布使用 `2026.5.11`
- Windows、macOS 安装包和自动更新元数据均已同步到新版本号

#### 4. Windows / macOS 安装包已重新打包

- Windows x64 安装包已重新生成
- macOS Apple Silicon 与 Intel 版本均已重新生成
- 对应的 blockmap 和更新清单也已一并刷新

### 下载

- Windows x64：`tuanbot_win_2026.5.11.exe`
- Windows 稳定直链：`tuanbot_win_latest.exe`
- macOS Apple Silicon：`Tuanbot-2026.5.11-mac-arm64.dmg`
- macOS Intel：`Tuanbot-2026.5.11-mac-x64.dmg`

## English

### Scope

- Previous public release: `2026.5.6`
- Current version: `2026.5.11`
- Platforms: Windows x64, macOS x64/arm64
- Build date: `2026-05-11`

### Highlights

#### 1. Skill and MCP pipelines were improved

- Skill invocation and execution paths were made more stable
- MCP tool onboarding and startup flows were cleaned up to reduce stalls and failed orchestration
- The underlying OpenCode execution path was also tidied up to make tool scheduling feel smoother

#### 2. Bug fixes and stability improvements

- Several UI and runtime issues were fixed to reduce long-session stalls and display glitches
- Global input, drag handling, and update-related flows were made more reliable
- Overall runtime smoothness and stability were improved

#### 3. Release version now matches today’s date

- This release uses version `2026.5.11`
- Windows, macOS installers, and update metadata were refreshed to the new version line

#### 4. Windows and macOS installers were repackaged

- The Windows x64 installer was rebuilt
- macOS Apple Silicon and Intel installers were rebuilt
- Matching blockmaps and update manifests were refreshed as well

### Downloads

- Windows x64: `tuanbot_win_2026.5.11.exe`
- Windows stable direct link: `tuanbot_win_latest.exe`
- macOS Apple Silicon: `Tuanbot-2026.5.11-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.5.11-mac-x64.dmg`
