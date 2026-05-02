# Tuanbot 2026.5.2 更新说明 / Release Notes

## 中文

### 范围

- 上一个公开版本：`2026.4.27`
- 当前版本：`2026.5.2`
- 平台：Windows x64、macOS x64/arm64、Linux arm64
- 构建日期：`2026-05-02`

### 亮点

#### 1. 跨平台版本统一

- Windows、macOS、Linux 包现在共用同一个版本号：`2026.5.2`
- 平台差异保留在文件名中，不再体现在版本号里
- 本次发布资产：
  - `tuanbot_win_2026.5.2.exe`
  - `Tuanbot-2026.5.2-mac-arm64.dmg`
  - `Tuanbot-2026.5.2-mac-x64.dmg`
  - `Tuanbot-2026.5.2-arm64.AppImage`
- 更新元数据：
  - Windows：`latest.yml`
  - macOS：`latest-mac.yml`
  - Linux：`latest-linux-arm64.yml`

#### 2. 聊天与会话处理更稳定

- 聊天窗口的会话切换和查看逻辑做了整理，行为更可预测
- 直接聊天历史保留已修复
- 多会话同时打开时，交互一致性更好

#### 3. 打包运行时接线刷新

- 打包后的应用会更稳定地走随包发布的运行时路径
- 工具命名和运行时边界做了对齐，提升发布可靠性
- 这能让安装包更接近预期的发布路径，而不是依赖宿主环境

#### 4. 桌面壳层继续优化

- App 级 props builder 和 UI bridge props 继续拆分整理
- 用户可见行为保持一致，但壳层和控制层边界更清晰，便于后续发布工作

#### 5. 用户可见提醒更明确

- 未读回复提示在会话列表里更醒目
- 机器人头顶可以直接显示未读面包屑，方便注意新回复
- 休息区可拖拽物件的位置会保留到下次打开

### 下载

- Windows x64：`tuanbot_win_2026.5.2.exe`
- Windows 稳定直链：`tuanbot_win_latest.exe`
- macOS Apple Silicon：`Tuanbot-2026.5.2-mac-arm64.dmg`
- macOS Intel：`Tuanbot-2026.5.2-mac-x64.dmg`
- Linux arm64：`Tuanbot-2026.5.2-arm64.AppImage`

## English

### Scope

- Previous public release: `2026.4.27`
- Current version: `2026.5.2`
- Platforms: Windows x64, macOS x64/arm64, Linux arm64
- Build date: `2026-05-02`

### Highlights

#### 1. Unified release versioning across platforms

- Windows, macOS, and Linux packages now share the same version number: `2026.5.2`
- Platform differences are kept in the asset filename, not in the version string
- Current release assets:
  - `tuanbot_win_2026.5.2.exe`
  - `Tuanbot-2026.5.2-mac-arm64.dmg`
  - `Tuanbot-2026.5.2-mac-x64.dmg`
  - `Tuanbot-2026.5.2-arm64.AppImage`
- Update metadata:
  - Windows: `latest.yml`
  - macOS: `latest-mac.yml`
  - Linux: `latest-linux-arm64.yml`

#### 2. Chat and session handling is more stable

- Chat window session switching and viewing behavior has been cleaned up for more predictable interactions
- Direct chat history preservation has been fixed
- Multi-session behavior is more consistent when several conversations stay open at once

#### 3. Packaged runtime wiring refreshed

- Packaged builds now follow the shipped runtime path more consistently
- Tool naming and runtime boundaries were aligned for release reliability
- This keeps packaged builds closer to the intended release path instead of relying on host tooling

#### 4. Desktop shell refinements

- App-level props builders and UI bridge props were further extracted
- The user-facing behavior stays the same, but the shell and controller boundaries are cleaner for future release work

#### 5. More visible user-facing attention cues

- Unread reply indicators are now more visible in the session list
- Robot heads can surface a clear unread breadcrumb so new replies are easier to notice
- Rest-area placement persistence keeps draggable items where you left them after restart

### Downloads

- Windows x64: `tuanbot_win_2026.5.2.exe`
- Windows stable direct link: `tuanbot_win_latest.exe`
- macOS Apple Silicon: `Tuanbot-2026.5.2-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.5.2-mac-x64.dmg`
- Linux arm64: `Tuanbot-2026.5.2-arm64.AppImage`
