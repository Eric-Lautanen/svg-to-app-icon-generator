# SVG to App Icon Generator 🎨

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web%20%7C%20PWA-blue)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Privacy: Local](https://img.shields.io/badge/Privacy-100%25%20Client--Side-green)]()

A powerful, **single-file** tool to instantly convert SVG files into perfectly sized app icons, favicons, and launch images for every major platform. 

**[🚀 Live Demo](#) (Put your Netlify/GitHub Pages link here)**

## ✨ Why use this converter?

Most icon generators require you to upload your files to a server, process them slowly, or pay for premium formats. 
**SVG to App Icon Generator** runs entirely in your browser. 

* **🔒 100% Private:** Your SVG never leaves your device. No server uploads.
* **⚡ Instant:** Powered by Web Assembly and modern Canvas APIs.
* **📦 All-in-One:** Generates `.ico`, `.icns`, and `.png` formats automatically.
* **📁 Zero Config:** Downloads a structured ZIP file ready to drop into your project folders.

## 📱 Supported Platforms & Frameworks

This tool generates the exact folder structures and file names required by:

### 🖥️ Desktop Apps
* **Tauri** (Rust) - Includes `icon.icns`, `icon.ico`, and all png sizes.
* **Electron.js** - Standard build assets.
* **Flutter Desktop** - Windows, macOS, and Linux specific assets.
* **Wails** (Go) & **Neutralino.js**.
* **Windows Store / MSIX** - Scaled assets for app packages.
* **macOS App Bundle** - Full `.icns` generation.

### 🌐 Web & PWA
* **Modern Web** - Favicons (`.ico`, `.png`) and Open Graph images.
* **PWA (Progressive Web Apps)** - Complete manifest icons (maskable/standard).
* **Browser Extensions** - Ready-made manifests for Chrome & Firefox extensions.

### 📲 Mobile Development
* **Android** - Full `mipmap` folder generation (mdpi through xxxhdpi) + Play Store asset.
* **iOS / iPadOS** - `Assets.xcassets` structure.
* **React Native** & **Expo**.
* **Flutter Mobile** & **Capacitor (Ionic)**.

### 🎮 Game Engines
* **Unity** - Icons for Player Settings.
* **Godot Engine** - Boot splash and icon assets.
* **Unreal Engine** - Build directory icons.

## 🚀 Quick Start

### Option 1: Use Online
Simply open the `index.html` file in any modern browser. 
1. Drag and drop your **SVG** file.
2. Select your target platform (e.g., "Tauri" or "iOS").
3. Click **Download All as ZIP**.

### Option 2: Run Locally
Since this is a single-file application, you don't need Node.js, Python, or a local server.

1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/svg-to-app-icon-generator.git](https://github.com/your-username/svg-to-app-icon-generator.git)
