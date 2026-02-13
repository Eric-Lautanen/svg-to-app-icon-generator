# SVG to App Icon Generator 🎨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web%20%7C%20PWA-blue)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Privacy: Local](https://img.shields.io/badge/Privacy-100%25%20Client--Side-green)]()

**The fastest way to generate multi-platform app icons without leaving your browser.** ### 🚀 [Launch Live Demo](https://eric-lautanen.github.io/svg-to-app-icon-generator/)

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

### 🖥️ Desktop Apps
* **Tauri (Rust):** Includes `icon.icns`, `icon.ico`, and all png sizes for `src-tauri/icons/`.
* **Electron.js:** Standard build/assets for macOS and Windows.
* **Flutter Desktop:** Windows, macOS, and Linux specific assets.
* **Wails (Go) & Neutralino.js**.

### 🌐 Web & PWA
* **Modern Web:** Favicons (`.ico`, `-16x16.png`, `-32x32.png`) and Open Graph images.
* **PWA:** Complete manifest icons (48px to 512px).
* **Browser Extensions:** Icons for Chrome and Firefox manifests.

### 📲 Mobile Development
* **Android:** Full `mipmap` folder generation (mdpi to xxxhdpi) + Play Store assets.
* **iOS / iPadOS:** `AppIcon.appiconset` structure including @2x and @3x scales.
* **React Native, Expo, & Capacitor**.

## 🚀 How to use

Since this is a single-file application, you don't need Node.js or a local server.
1. Download the index.html file and load it from your device.

## 🛠️ Tech Stack
* **HTML5/CSS3:** Responsive dark-mode UI with Syne & JetBrains Mono fonts.
* **JSZip:** Handles client-side ZIP generation.
* **Canvas API:** Handles high-fidelity image rendering and resizing.

## 📄 License
MIT License. Free to use for personal and commercial projects.
