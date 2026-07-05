---
slug: mockingbird
name: Mockingbird
tagline: Select text anywhere on your Mac and hear it read aloud — with natural, on-device voices.
icon: icon.png
download: https://github.com/awsleiman171/mockingbird-releases/releases/download/v1.1.1/Mockingbird-1.1.1.dmg
version: 1.1.1
platforms: [macOS 14+ (Apple Silicon)]
repo: https://github.com/awsleiman-lab/mockingbird
order: 2
---

Mockingbird is a lightweight menu-bar app that reads your selected text out
loud. Select something in any app, press **Ctrl+Option+S**, and listen —
pause and resume any time with **Ctrl+Option+P**. Speech is generated
entirely on your Mac with high-quality neural voices.
Mockingbird is **open source** (MIT) — read every line before you trust it.

![Mockingbird's menu-bar panel reading a text selection aloud](/apps/mockingbird/menu-bar.png)

## Features

- **Read anything, anywhere** — articles, emails, documents, code comments:
  if you can select it, Mockingbird can read it.
- **Natural neural voices** — choose between Kokoro (best quality), Piper
  (fast and lightweight), or the built-in Apple system voices.
- **Global hotkeys** — read, pause, and resume without touching the mouse.
  Hotkeys are editable from the menu bar.
- **Light on your Mac** — no background daemon while idle; the speech engine
  only runs when you ask for it.
- **Guided setup** — a first-run onboarding downloads the voice engine of
  your choice. No Python, Homebrew, or developer tools needed.

## Requirements

- macOS 14 (Sonoma) or later, Apple Silicon
- ~0.5–1.3 GB of disk space for the voice engine of your choice
  (Apple system voices work with no download at all)

## Privacy

Mockingbird never listens to your microphone and generates all speech on
device. After the one-time voice engine download, it works fully offline —
no analytics, no accounts.

## Installation & updates

Click Download, open the file, and drag **Mockingbird** into your
**Applications** folder — that's it. The app is verified by Apple, so it
opens without any warnings, and it keeps itself up to date: when a new
version comes out, Mockingbird offers it to you automatically.
