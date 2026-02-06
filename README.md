<h1>
  <img src="https://github.com/user-attachments/assets/e6a52de3-bd82-4685-bfeb-acb638b0e150" alt="Logo" width="35" height="35" style="vertical-align: middle;">
  TV Hub
</h1>

**Turn your old laptop and non-smart TV into a dedicated smart TV Hub for streaming content.**

![Home Page Screenshot](https://github.com/user-attachments/assets/668f74b2-2975-449f-9fa7-1d3f1e7e6a08)

TV Hub is a cross-platform Electron app that transforms an old laptop + HDMI-connected TV into a simple, full-screen, TV-style interface for streaming apps. It’s designed for **non-technical users** (family, friends) with a one-time setup and daily use via a remote mouse app on Android.

## 📺 Overview

TV-Hub solves a simple problem: **making non-smart TVs smart** using hardware you already have.

Once set up, it behaves like a lightweight smart TV interface with:
- Fullscreen, TV-friendly UI  
- Built-in streaming apps  
- Simple navigation with back button  
- In-app sound control  
- Minimal interaction needed after setup  

It’s currently used daily by my family and works reliably, though the internal architecture can still be polished further.

## ✨ Features

- Fullscreen smart TV–style interface  
- Built-in apps:
  - YouTube  
  - YouTube Music  
  - MX Player  
  - HiAnime  
  - News  
  - FMovies  
- In-app volume control (via system volume)  
- Back button for navigation between UI pages  
- Scalable design to add more apps  
- Future-ready for gaming support with a controller  

## 🖥️ Supported Platforms

- **Windows** (`.exe`)  
- **Linux** (`.AppImage`)  

## 🧰 Tech Stack

- Electron.js  
- HTML, CSS, Vanilla JavaScript  
- Vite  
- Node.js  
- `loudness` Node library (for system volume control)  

## 📦 Installation

### For Users

1. Go to the [GitHub Releases](https://github.com/lightRajat/tv-hub/releases) page of this repository.
2. Download the installer for your platform:
   - Windows: `.exe`
   - Linux: `.AppImage`
3. Install and run the app.
4. One-time setup:
   - Connect your laptop to the TV via HDMI
   - Set the app to launch on startup (recommended)
   - Use a **remote mouse app on Android** to control it from your phone (recommended: [Remote Mouse](https://www.remotemouse.net/))

That’s it—your TV-Hub is ready.

### For Developers

```bash
git clone git@github.com:lightRajat/tv-hub.git
cd tv-hub
npm install
npm run start
```

## 🤝 Contributing

This is a personal project created out of necessity, but improvements and ideas are welcome.
Feel free to open issues or pull requests for:

* Bug fixes
* UI improvements
* Architecture refactors
* New app integrations

## 📄 License

This project is licensed under the [MIT License](https://github.com/lightRajat/tv-hub?tab=MIT-1-ov-file).
