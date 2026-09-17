<div align="center">

<img src="bacapi-logo.svg" width="96" alt="Bacapi logo">

# Bacapi Sources — Kernel V5.6 Open Source

> Dapat kodingannya, bukan AI-nya: engine AI dilepas di build ini (lihat `config.js`). V5.7 dalam pengembangan privat.

Kode sumber Bacapi AI desktop (Bacium V5.6) — Chat/Work, plugins Word/Excel/PDF/gambar, mindmap, deep search, streaming, PWA + aplikasi Electron.

![LICENSE](https://img.shields.io/badge/LICENSE-MIT-yellow) ![JS](https://img.shields.io/badge/JAVASCRIPT-ES2023-blue) ![ELECTRON](https://img.shields.io/badge/ELECTRON-28-47848f) ![PWA](https://img.shields.io/badge/PWA-ready-purple) ![TESTING](https://img.shields.io/badge/TESTING-node-blue)

[Quick Start](#quick-start) • [Modes](#modes) • [Plugins](#plugins) • [Install](#install) • [Manage](#manage)

*Independent open-source project. Bacapi is an original work — logo huruf B, kernel Bacium, dan semua kode di sini milik project ini.*

## What You Get

- **Work mode** — PR, cerita natural, planning, PRD, mindmap jadi gambar, kode runnable multi-file.
- **Deep Search** — riset mendalam + animasi otak; **Deep** — jawaban panjang.
- **Plugins** — Word (.doc), Excel (.csv), PDF, generate gambar (gratis via Pollinations), pratinjau akurat HTML+CSS+JS.
- **Streaming** jawaban real-time + riwayat ingatan 12 pesan + ingat nama + notifikasi selesai.
- **Desktop + Web** — `Bacapi.exe` (Electron) dan PWA installable dari browser.

## Quick Start

```bat
InstallBacapi.bat
```

Butuh Node.js + runtime Electron (lihat [Install](#install)). API key OpenRouter diisi sekali di aplikasi, tidak ikut di repo.

## Modes

| Mode | Fungsi |
|---|---|
| Chat | Tanya jawab umum |
| Work | PR, cerita, PRD, mindmap, kode |
| Codev | (digabung ke Work di versi ini) |

## Plugins

Aktif/nonaktif dari sidebar: Word, Excel, PDF, Gambar, Pratinjau Akurat. Auto-jalan sesuai prompt (misal minta cerita + Word → file `.doc` terunduh).

## Install

1. Install Node.js LTS.
2. Siapkan runtime Electron 28 di folder `BitBrowser/node_modules/electron/dist` (atau `npm i electron@28.3.3` lalu sesuaikan `ELEC_DIR`).
3. Jalankan `InstallBacapi.bat` → `Bacapi.exe` + shortcut Desktop.
4. Buka → setup nama + API key sekali → jadi.

Versi web: buka `bacapi.html` / hosting via GitHub Pages (`install.html` = halaman download).

## Manage

- `tools/make-icon.js` — regenerate ikon B.
- `tools/MakeShortcut.ps1` — helper shortcut Windows.
- `sw.js` + `manifest.json` — PWA.
