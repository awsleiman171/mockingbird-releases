---
slug: mockingbird
name: Mockingbird
tagline: Select text anywhere and hear it read aloud — with natural, on-device voices.
icon: icon.png
download: https://github.com/awsleiman171/mockingbird-releases/releases/download/v1.0.2/Mockingbird-1.0.2.dmg
version: 1.0.2
platforms: [macOS 14+ (Apple Silicon)]
repo: https://github.com/awsleiman171/mockingbird-releases
order: 2
---

Mockingbird is a lightweight menu-bar app that reads your selected text out
loud. Select something in any app, press **Ctrl+Option+S**, and listen —
pause and resume any time with **Ctrl+Option+P**. Speech is generated
entirely on your Mac with high-quality neural voices.

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

Download the DMG, drag **Mockingbird** to Applications, and launch it. The
app is signed and notarized by Apple, and updates itself automatically via
Sparkle.
