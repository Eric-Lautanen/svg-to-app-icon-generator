# SVG to App Icon Generator 🎨
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web%20%7C%20PWA-blue)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Privacy: Local](https://img.shields.io/badge/Privacy-100%25%20Client--Side-green)]()

**The fastest way to generate multi-platform app icons without leaving your browser.**

### 🚀 [Launch Live Demo](https://eric-lautanen.github.io/svg-to-app-icon-generator/)

---

A powerful, **single-file** tool to instantly convert SVG files into perfectly sized app icons, favicons, and launch images for every major platform. 

## ✨ Why use this converter?

Most icon generators require you to upload your files to a server, process them slowly, or pay for premium formats. 

**SVG to App Icon Generator** runs entirely in your browser. 

* **🔒 100% Private:** Your SVG never leaves your device. No server uploads.
* **⚡ Instant:** Powered by modern Canvas APIs and client-side processing.
* **📦 All-in-One:** Generates `.ico`, `.icns`, and `.png` formats automatically.
* **📁 Zero Config:** Downloads a structured ZIP file ready to drop into your project folders.

## 📱 Supported Platforms & Frameworks

This tool generates the exact folder structures and file names required by:

### 🖥️ Desktop Frameworks
* **Rust/egui:** Complete cross-platform icon set including `.ico` (Windows), `.icns` (macOS), and Linux PNG icons in proper `assets/` structure.
* **Tauri (Rust):** Full `src-tauri/icons/` suite including `.icns`, `.ico`, and PNGs.
* **Electron.js:** Standard `build/` or `assets/` directory icons.
* **Wails (Go):** Specialized `appicon.png` and desktop formats.
* **Neutralino.js, NW.js, and Flutter Desktop.**

### 🌐 Web & Browser Extensions
* **Web / PWA:** Favicons, Apple Touch Icons, and Open Graph (OG) images.
* **PWA Manifest:** Complete icon set from 48px up to 512px for `manifest.json`.
* **Extensions:** Formatted specifically for **Chrome**, **Firefox**, and **Safari** extension resources.

### 📲 Mobile & Wearables
* **iOS / iPadOS:** Full `Assets.xcassets` structure with all @2x and @3x scales.
* **Android:** Complete `mipmap` folder generation (mdpi to xxxhdpi).
* **watchOS:** Apple Watch specific sizes and companion icons.
* **Cross-Platform:** Native support for **React Native**, **Expo**, **Capacitor (Ionic)**, **Tauri Mobile (v2)**, and **Flutter Mobile**.

### 🛠️ Developer Tools & Plugins
* **VS Code Extensions:** `icon.png` and `@2x` retina variants.
* **Raycast:** Extension icons optimized for light and dark modes.
* **Figma Plugins:** Manifest-ready icons and high-resolution cover art.

### 🎮 Game Engines & Stores
* **Unity:** Multi-platform icon suite (16px to 1024px).
* **Godot & Unreal Engine:** Boot splashes, desktop icons, and store assets.
* **Steam Store:** Essential capsule images (Header, Main, Small) and Library assets.

### 🤖 Bots & Social Apps
* **Discord & Slack:** App/Bot profile icons and cover images.
* **Telegram:** Mini App and Bot profile headers and pictures.

## 🚀 How to use

Since this is a single-file application, you don't need Node.js or a local server.

1. Download the `index.html` file.
2. Open it in any modern web browser.
3. Paste your SVG code or upload your file.
4. Select your target platform and click **Generate**.

### ⚠️ Windows 11 ZIP Extraction Note

If you're on **Windows 11** and encounter issues extracting ZIP files containing `.ico` files:

* **Recommended:** Use [7-Zip](https://www.7-zip.org/) (free) for extraction - it handles all formats perfectly
* **Alternative:** Download files individually using the Download button next to each file
* **Why?** Windows 11's built-in ZIP extractor has a known bug with ICO files from browser-generated ZIPs

The generated ZIP files are perfectly valid and work on all other platforms and third-party extraction tools.

## 🛠️ Tech Stack

* **HTML5/CSS3:** Responsive dark-mode UI with Syne & JetBrains Mono fonts.
* **JSZip:** Handles client-side ZIP generation and folder structuring.
* **Canvas API:** High-fidelity image rendering and resizing.
* **Blob API:** Client-side binary file generation for `.ico` and `.icns`.

## 📄 License

MIT License. Free to use for personal and commercial projects.
