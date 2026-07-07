<div align="center">
  <img src="https://raw.githubusercontent.com/BrijeshGhori/LiveScape/main/assets/icon.png" width="128" alt="LiveScape Logo"/>

  <h1>🌌 LiveScape</h1>
  
  <p>
    <b>Breathe life into your macOS desktop with dynamic, interactive video wallpapers.</b>
  </p>

  <p>
    <a href="#-features">Features</a> • 
    <a href="#-installation--setup">Installation</a> • 
    <a href="#%EF%B8%8F-usage-guide">Usage Guide</a>
  </p>
</div>

---

LiveScape is a premium, lightweight macOS application that lives entirely in your menu bar. It completely reimagines your desktop experience by seamlessly playing high-quality video wallpapers behind your windows, while remaining virtually invisible to your system's resources.

---

## ✨ Features

### 🎯 Unobtrusive Menu Bar Experience
LiveScape is designed to be felt, not seen. 
- **No Dock Icon:** It runs silently in the background without cluttering your macOS Dock.
- **No App Switcher Clutter:** It does not appear when you press `Cmd + Tab`.
- **Global Quick Access:** Control everything directly from the beautiful dropdown menu in your top-right macOS menu bar.
- **Launch on Login:** Automatically starts up with your Mac so your dynamic desktop is always ready.
### 🖼️ High-Fidelity Video Engine
- **True Desktop Integration:** Renders video layers *behind* your desktop icons and active windows by utilizing custom macOS `NSWindow` level management. It feels identically to a native static wallpaper.
- **Multi-Monitor Support:** Automatically detects multiple displays and flawlessly applies video loops across all your connected screens.
- **Hardware Acceleration:** Heavily optimized AVFoundation decoding ensures your CPU and GPU aren't drained, keeping your Mac cool and fast while rendering 4K loops.
- **Smart Pause & Performance Mode:** Automatically pauses video playback when full-screen apps or heavy games are launched, ensuring zero performance drops during intensive tasks.
### 🛍️ Creator Studio Marketplace
Why settle for one wallpaper? LiveScape features a built-in cloud marketplace.
- **Cloud Library:** Browse a curated collection of live wallpapers seamlessly fetched from our remote CDN.
- **One-Click Download:** Download and instantly apply new wallpapers without ever leaving the app.
- **Local Caching:** Downloaded wallpapers are securely cached on your machine so you never have to download them twice.
- **Storage Management:** Easily view downloaded files and delete old wallpapers to free up disk space directly from the settings menu.

---

## 📥 Installation & Setup

Because LiveScape is an independent open-source project, macOS's built-in security (Gatekeeper) requires a one-time manual approval to run it.

### 1. Download the App
1. Navigate to the [Releases](../../releases) tab on this repository.
2. Download the latest `LiveScape.zip` asset.
3. Double-click `LiveScape.zip` in your Downloads folder to extract `LiveScape.app`.

### 2. Install
**Crucial Step:** Drag and drop `LiveScape.app` from your Downloads folder directly into your **Applications** folder.

### 3. The "Open Anyway" Bypass (First Time Only)
When you double-click LiveScape for the first time, macOS will show a warning: *"LiveScape cannot be opened because the developer cannot be verified."*

1. Click **Cancel** on the warning box.
2. Open your Mac's **System Settings** ( > System Settings).
3. Click on **Privacy & Security** in the left sidebar.
4. Scroll down to the **Security** section. You will see a message: *"LiveScape was blocked from use because it is not from an identified developer."*
5. Click **Open Anyway**. Enter your Mac password or use TouchID.
6. A final popup will ask if you are sure. Click **Open**.

*🎉 Success! You will only ever have to do this once. LiveScape is now running securely.*

---

## 🖱️ Usage Guide

Once installed, LiveScape operates entirely from your top Menu Bar. Look for the 🌌 icon near your WiFi and Battery indicators.

### Applying a Wallpaper
1. Click the LiveScape menu bar icon.
2. Click **Open Creator Studio**.
3. Browse the cloud library, select a wallpaper, and click **Download**.
4. Once downloaded, click **Set Wallpaper** to immediately apply it to your desktop.

### Managing Playback
- **Pause/Play:** If you need to temporarily stop the animation (e.g., during a heavy rendering task or a Zoom call), simply click the menu bar icon and select **Pause Wallpaper**.
- **Change Display:** If you have multiple monitors, use the built-in display selector in the Settings menu to assign different wallpapers to different screens.

### Quitting the App
Because LiveScape is a background utility, you cannot quit it using `Cmd + Q` or via the Dock. 
- **To exit:** Click the menu bar icon and select **Quit LiveScape** at the bottom of the list.
---
## 📝 License
This project is proprietary and intended for personal use. All rights reserved. Do not distribute without permission.
<p align="center">
  <i>Built with ❤️ for macOS</i>
</p>
