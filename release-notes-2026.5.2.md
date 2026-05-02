# Tuanbot 2026.5.2 Release Notes

## Scope

- Previous public release: `2026.4.27`
- Current version: `2026.5.2`
- Platforms: Windows x64, macOS x64/arm64, Linux arm64
- Build date: `2026-05-02`

## Highlights

### 1. Unified release versioning across platforms

- Windows, macOS, and Linux packages now share the same version number: `2026.5.2`.
- Platform differences are kept in the asset filename, not in the version string.
- Current release assets:
  - `tuanbot_win_2026.5.2.exe`
  - `Tuanbot-2026.5.2-mac-arm64.dmg`
  - `Tuanbot-2026.5.2-mac-x64.dmg`
  - `Tuanbot-2026.5.2-arm64.AppImage`
- Update metadata:
  - Windows: `latest.yml`
  - macOS: `latest-mac.yml`
  - Linux: `latest-linux-arm64.yml`

### 2. Chat and session handling stabilized

- Chat window session handling was cleaned up for more predictable switching and viewing behavior.
- Direct chat history preservation was fixed.
- Multi-session behavior is now more consistent when several conversations stay open at once.

### 3. Packaged runtime packaging refreshed

- Packaged builds now follow the shipped assistant runtime path more consistently.
- Tool naming and runtime boundaries were aligned for release reliability.
- This keeps packaged builds closer to the intended release path instead of relying on host tooling.

### 4. Desktop shell refinements

- App-level props builders and UI bridge props were further extracted.
- The user-facing behavior stays the same, but the shell and controller boundaries are cleaner for future release work.

### 5. User-facing attention cues improved

- Unread reply indicators are now more visible in the session list.
- Robot heads can surface a clear unread breadcrumb so new replies are easier to notice.
- Rest-area placement persistence keeps draggable items where you left them after restart.

## Downloads

- Windows x64: `tuanbot_win_2026.5.2.exe`
- Windows latest direct link: `tuanbot_win_latest.exe`
- macOS Apple Silicon: `Tuanbot-2026.5.2-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.5.2-mac-x64.dmg`
- Linux arm64: `Tuanbot-2026.5.2-arm64.AppImage`
