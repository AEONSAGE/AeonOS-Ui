<p align="center">
  <img src="https://raw.githubusercontent.com/AEONSAGE/AeonOs/main/web/website/public/logos/AeonSage_letter_logo.svg" alt="AeonSage" width="320" />
</p>

<p align="center">
  <a href="https://github.com/AEONSAGE/AeonOS-Ui/releases/latest"><img src="https://img.shields.io/github/v/release/AEONSAGE/AeonOS-Ui?style=flat-square&color=7C6FE0&label=Release" alt="Release" /></a>&nbsp;
  <img src="https://img.shields.io/badge/Platform-Windows_%7C_macOS_%7C_Linux-2D3748?style=flat-square" alt="Platform" />&nbsp;
  <img src="https://img.shields.io/badge/Tauri-2-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri" />&nbsp;
  <a href="https://github.com/AEONSAGE/AeonOs/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Proprietary-6050C0?style=flat-square" alt="License" /></a>
</p>

<p align="center">
  <strong>AeonSage desktop application for Windows, macOS, and Linux.</strong><br/>
  Built with Tauri 2 — native performance, automatic updates, local-first privacy.
</p>

---

## Download

| Platform | Installer | Notes |
|----------|-----------|-------|
| **macOS** (Universal) | [AeonSage\_macos\_universal.dmg](https://github.com/AEONSAGE/AeonOS-Ui/releases/latest) | Apple Silicon + Intel, notarized |
| **Windows** x64 | [AeonSage\_windows\_x64\_en-US.exe](https://github.com/AEONSAGE/AeonOS-Ui/releases/latest) | NSIS installer, code-signed |
| **Linux** x86\_64 | [AeonSage\_linux\_x86\_64.AppImage](https://github.com/AEONSAGE/AeonOS-Ui/releases/latest) | No install required |

All releases are code-signed, notarized, and auto-update enabled.

---

## What is AeonSage Desktop

AeonSage Desktop wraps the AeonSage backend engine in a native application — giving you full access to the AI agent platform without running a server manually.

**What you get:**

- Connect to a local or remote AeonSage gateway in one click
- System tray integration with persistent agent access
- Automatic update delivery via the built-in updater
- Native notifications, file drag-and-drop, and OS-level integrations
- Works fully offline with a local model (Ollama)

The desktop app is a thin native shell. The full engine lives in the open-source backend: [AEONSAGE/AeonOs](https://github.com/AEONSAGE/AeonOs).

---

## Getting Started

1. Download the installer for your platform above
2. Install and launch AeonSage
3. Enter your gateway URL (default: `http://localhost:7777`) or use the bundled local mode
4. Add your AI provider API key in Settings
5. Start chatting — or explore Skills, Channels, and the Finance Agent

Full documentation: **[docs.aeonsage.com](https://docs.aeonsage.com)**

---

## Auto-Updates

AeonSage Desktop checks for updates automatically on launch. Updates are signed with the project's release key — no unsigned updates are accepted.

To update manually: open **Settings → About → Check for Updates**.

---

## Source Code & Backend

The backend engine, open-source components, and full architecture documentation are in the main repository:

**[AEONSAGE/AeonOs](https://github.com/AEONSAGE/AeonOs)** — Apache 2.0 / AGPL-3.0 / Proprietary

---

## License

The compiled binaries distributed from this repository are **Proprietary**.

No license is granted to redistribute, reverse-engineer, or modify these binaries without explicit written permission from AEONSAGE.

Copyright © 2024-2025 AEONSAGE. All rights reserved.

---

<sub>
AeonSage is a <a href="https://velon.one">Velon.one</a> product &nbsp;·&nbsp;
Special technical support by <a href="https://github.com/velonone">@VelonLabs</a>
</sub>