# Tuanbot 2026.4.27 Release Notes

## Scope

- Previous public release: `2026.4.7-a`
- Current version: `2026.4.27`
- Platforms: Windows x64, macOS x64/arm64, Linux arm64
- Build date: `2026-05-01`

## Highlights

### 1. Unified release versioning across platforms

- Windows, macOS, and Linux packages now share the same version number: `2026.4.27`.
- Platform differences are kept in the asset filename, not in the version string.
- Current release assets:
  - `tuanbot_win_2026.4.27.exe`
  - `Tuanbot-2026.4.27-mac-arm64.dmg`
  - `Tuanbot-2026.4.27-mac-x64.dmg`
  - `Tuanbot-2026.4.27-arm64.AppImage`
- Update metadata:
  - Windows: `latest.yml`
  - macOS: `latest-mac.yml`
  - Linux: `latest-linux-arm64.yml`

### 2. Runtime chat and session handling stabilized

- Runtime chat IPC handlers were extracted and simplified.
- Direct chat history preservation was fixed.
- Chat window session, runtime, and path handling received another cleanup pass.

### 3. Bundled runtime packaging refreshed

- The bundled runtime packaging was updated so packaged builds keep using the in-app OpenCode bundle.
- Provider-safe OpenCode tool names were aligned at the runtime boundary.
- This keeps packaged builds closer to the real release path instead of relying on host tooling.

### 4. Desktop shell refactors continued

- App-level props builders and UI bridge props were further extracted.
- The user-facing behavior stays the same, but the shell and controller boundaries are cleaner for future release work.

## Downloads

- Windows x64: `tuanbot_win_2026.4.27.exe`
- Windows latest direct link: `tuanbot_win_latest.exe`
- macOS Apple Silicon: `Tuanbot-2026.4.27-mac-arm64.dmg`
- macOS Intel: `Tuanbot-2026.4.27-mac-x64.dmg`
- Linux arm64: `Tuanbot-2026.4.27-arm64.AppImage`
