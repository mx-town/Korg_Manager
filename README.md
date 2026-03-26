# 🎹 Korg Manager

[![Electron](https://img.shields.io/badge/Electron-Desktop-47848F?logo=electron&logoColor=white)](https://electronjs.org)
[![Tests](https://img.shields.io/badge/Tests-240%20passed-brightgreen)](https://vitest.dev)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)]()

Desktop application for managing Korg Electribe synthesizers. Supports the **ESX-1**, **E2S**, and **EMX-1** — read, edit, and organize samples and patterns across multiple devices from a single interface.

> ⚠️ **Source code is private.** This repository serves as a project overview. A public release is planned for later.

---

## Screenshots

*Coming soon*

---

## Features

### Sample Management
- Import, export, and organize samples across Electribe devices
- Audition samples directly in the app using **Web Audio API** playback
- Apply any of **18 built-in DSP effects** (delay, reverb, filter, etc.)

### Pattern Viewer
- Visual pattern editor styled after the original Electribe hardware panels
- View and browse patterns with per-step parameter display

### Multi-Device Support
- Manage **ESX-1**, **E2S**, and **EMX-1** simultaneously
- Read and write device-specific file formats
- The only tool that supports all three Electribe models in one application

### Quality
- **240 automated tests** covering file parsing, DSP processing, and UI logic
- Test suite built with Vitest

---

## Supported Devices

| Device | Samples | Patterns | File Format |
|--------|---------|----------|-------------|
| Korg ESX-1 | ✅ | ✅ | `.esx` |
| Korg E2S | ✅ | ✅ | `.e2sallpat` |
| Korg EMX-1 | ✅ | ✅ | `.emx` |

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Electron | Cross-platform desktop app |
| JavaScript | Application logic |
| Web Audio API | Sample playback & DSP effects |
| Vitest | Test framework (240 tests) |

---

## Why?

Existing tools for managing Electribe devices are outdated, single-device only, and lack basic features like audio preview or batch operations. Korg Manager was built to fill that gap — one app for all three Electribe models, with proper testing and a UI that feels like the hardware it manages.

---

## Status

🔧 Actively in development. Public release planned for a later date.

---

## Author

Built by [Niklas Martinek](https://cv-martinek.vercel.app) · [@mx-town](https://github.com/mx-town)

## License

Proprietary — all rights reserved.
