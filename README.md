<div align="center">

# 📻 All India Radio • Live Web Tuner
### *Suno. Feel India.*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS_3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![HLS.js](https://img.shields.io/badge/HLS.js-Audio_Stream-ff4757?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

A single-file web tuner built with pure Neomorphism (Soft UI), smooth 60fps micro-interactions, HLS `.m3u8` live stream playback, offline caching, and 6 aesthetic themes.

[Live Demo](#-quick-start) • [Features](#-features) • [Themes](#-6-curated-themes) • [Shortcuts](#-keyboard-shortcuts)

---

</div>

## 📑 Overview

**All India Radio Live Tuner** brings together official Akashvani (AIR) broadcasts, national private FM channels (Red FM, Radio Mirchi, Big FM, Radio City), and local regional stations across India.

Packaged as a **zero-dependency, single-file HTML app (`Indian-Radio.html`)**, it delivers a native desktop app feel right in the browser with no build step required.

---

## ✨ Features

### 🎧 Seamless Audio Streaming
- **Native HLS Playback**: Powered by `HLS.js` for `.m3u8` streams and standard Icecast/Shoutcast radio channels.
- **Failover & Auto-Recovery**: Automatic retries on transient network drops and round-robin fallback for public radio directories (`de1`, `nl1`, `at1`).
- **Media Session API**: Native system notifications, lock-screen controls, and real-time metadata display.

### 🎨 Physics-Based Soft UI (Neomorphism)
- **Dual Light Physics**: Directional highlights and ambient occlusion shadows for realistic tactile depth.
- **Interactive Equalizer**: Real-time multi-bar wave visualizer when streaming.
- **Card Glow Elevation**: Active stations highlight with a dynamic pulse indicator.

### ⚡ Blazing Fast & Memory-Efficient
- **DocumentFragment & Event Delegation**: Instant DOM rendering without performance lag during fast station scrolling.
- **Debounced Instant Search**: Sub-millisecond local filtering with remote search lookup.
- **Safe History Deletion**: Option to clear your listening history without deleting saved Favourites.

---

## 🎨 6 Curated Themes

All themes feature custom shadow calculations, surface gradients, and distinct accent colors:

| Theme | Colorway | Accent | Description |
|---|---|---|---|
| **Obsidian Onyx** *(Default)* | `#131418` | `#ff4757` | Deep carbon matte with specular edge highlights |
| **Pearl Ceramic** | `#e5ebf3` | `#ff4757` | Soft tactile clay with clean ceramic highlights |
| **Midnight Cyber** | `#0b1220` | `#00f2fe` | Oceanic twilight with electric cyan neon accents |
| **Warm Sahara** | `#e6dfd1` | `#e65100` | Vintage radio aesthetic with warm clay and amber tones |
| **Nordic Slate** | `#1e242d` | `#10b981` | Industrial titanium with mint/emerald glow |
| **Royal Velvet** | `#171126` | `#c084fc` | Deep imperial purple with neon magenta highlights |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| <kbd>Space</kbd> | Toggle Play / Pause |
| <kbd>M</kbd> | Toggle Mute / Restore Volume |
| <kbd>→</kbd> *(Right Arrow)* | Next Station |
| <kbd>←</kbd> *(Left Arrow)* | Previous Station |
| <kbd>Esc</kbd> | Close Preferences & Settings Modal |

---

## 📁 File Architecture

The entire application is completely self-contained in a single file:
