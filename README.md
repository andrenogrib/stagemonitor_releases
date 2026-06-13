# Stage Monitor — Releases

**Stage display, reimagined for live production.**

A cross-platform (Windows + macOS) **ProPresenter-style stage display** with a
**GrandMA2-style cue list**: design layouts in a WYSIWYG editor, drive multiple
screens and NDI outputs, and fire them live from MIDI, OSC, Art-Net, sACN or
SMPTE timecode — then mirror any screen to a browser on the LAN.

[![Latest release](https://img.shields.io/github/v/release/andrenogrib/studiomonitor_releases?label=latest&color=3b82f6)](../../releases/latest)
[![Downloads](https://img.shields.io/github/downloads/andrenogrib/studiomonitor_releases/total?color=22c55e)](../../releases)
[![Platforms](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-0b0d11)](#download)
[![Website](https://img.shields.io/badge/website-stagemonitor.stagerig.com.br-3b82f6)](https://stagemonitor.stagerig.com.br)

> This repository is the **public download host** for Stage Monitor. The
> application source is maintained privately; only the installable builds are
> published here.

---

## Download

➡️ **Grab the latest version from the [Releases](../../releases/latest) page.**

| Platform | File | Notes |
| --- | --- | --- |
| **Windows** | `Stage Monitor-Setup-<version>.exe` | NSIS installer |
| **macOS (Apple Silicon)** | `Stage Monitor-<version>-arm64.dmg` | arm64 / Apple Silicon |

Website, full guide and screenshots: **[stagemonitor.stagerig.com.br](https://stagemonitor.stagerig.com.br)**

---

## Features

- **WYSIWYG editor** — design every screen on a live per-screen canvas; what you
  see is exactly what goes out.
- **GrandMA2-style cue list** — program the show as named cue lists with decimal
  numbering, crossfades, trigger modes and per-cue settings. Store a look as a
  cue and dissolve it in; insert decimal cues, renumber, chase with Follow / Time
  triggers.
- **Multiple independent screens** — each screen is its own output with its own
  layout and content.
- **NDI & physical outputs** — send each screen to a fullscreen/windowed display
  and to multiple NDI® sources, with per-output control.
- **Clean crossfades** — smooth dissolves between looks with no black dip, even
  over NDI.
- **Big readable timers** — countdown, countdown-to-time, count-up / elapsed,
  time-of-day and SMPTE, with play / pause / reset and overrun.
- **Stage messages** — flash messages to the stage straight from the cue list.
- **Protocol I/O** — map **MIDI**, **OSC**, **Art-Net** and **sACN** signals to a
  command or cue.
- **SMPTE timecode** — chase LTC & MTC, record per-song timecode shows, or be the
  master and send MTC/LTC to other gear. Includes real SMPTE bars, ramps, an
  academy-leader countdown, an AV-sync test and an adjustable test card.
- **LAN web-viewer** — mirror any screen to any browser on the network: an exact,
  live, read-only pixel mirror over **MJPEG**, with an optional PIN.

---

## Tech stack

### Application

- [Electron](https://www.electronjs.org/) — cross-platform desktop shell
- [React](https://react.dev/) — UI
- [TypeScript](https://www.typescriptlang.org/) — language
- [electron-builder](https://www.electron.build/) — packaging (NSIS for Windows,
  DMG for macOS)
- **NDI** for video output, **MJPEG over HTTP** for the LAN web-viewer
- Live control via **MIDI**, **OSC**, **Art-Net**, **sACN** and **SMPTE timecode (LTC/MTC)**

### Website ([stagemonitor.stagerig.com.br](https://stagemonitor.stagerig.com.br))

- [Astro](https://astro.build/) — static site
- [Tailwind CSS](https://tailwindcss.com/) — styling

---

## Links

- 🌐 **Website & guide** — [stagemonitor.stagerig.com.br](https://stagemonitor.stagerig.com.br)
- ⬇️ **Download** — [stagemonitor.stagerig.com.br/download](https://stagemonitor.stagerig.com.br/download)
- 📖 **Guide** — [stagemonitor.stagerig.com.br/guide](https://stagemonitor.stagerig.com.br/guide)
- 📦 **All releases** — [Releases](../../releases)

---

## Trademarks

NDI® is a registered trademark of Vizrt NDI AB. ProPresenter, GrandMA2 and
Resolume are trademarks of their respective owners and are referenced here only
to describe Stage Monitor's design and compatibility. Stage Monitor is not
affiliated with or endorsed by any of them.

---

© André Nogueira · [@andrenogrib](https://instagram.com/andrenogrib) · StageRig [@stagerigbr](https://instagram.com/stagerigbr)
