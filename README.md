# Vloam Releases Hub

<p align="center">
  <b>Official Release & Distribution Hub for the Vloam Desktop Application Suite</b><br>
  Vloam 官方应用矩阵公共分发与更新中心
</p>

<p align="center">
  <a href="https://dl.vloam.com"><img src="https://img.shields.io/badge/Download_Portal-dl.vloam.com-0284c7?style=flat-square&logo=googlechrome&logoColor=white" alt="Download Portal"></a>
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-1e293b?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-818cf8?style=flat-square" alt="License">
</p>

<p align="center">
  <b>English</b> | <a href="./README.zh-CN.md">简体中文</a> | <a href="https://dl.vloam.com">Online Download Portal (dl.vloam.com)</a>
</p>

---

This repository serves as the official distribution and update center for all desktop applications under the **Vloam** ecosystem. All production installers (`.dmg`, `.exe`) and automated version manifests (`version.json`) are continuously deployed here via automated CI/CD pipelines.

👉 **Visit the Online Download Portal: [https://dl.vloam.com](https://dl.vloam.com)**

---

## 📦 Products & Fast Direct Downloads

### 1. 📋 VloamClip
> **Keyboard-driven cross-platform clipboard manager designed for peak focus**  
> Built for developers, writers, and productivity power-users. Features full keyboard roaming, Vim-style navigation (`j`/`k`), sequential FIFO/LIFO paste queue, and local-first AES-256-GCM encrypted security.

- **Official Website**: [https://clip.vloam.com](https://clip.vloam.com)
- **Version Manifest**: [`clip/version.json`](./clip/version.json)
- **Direct Downloads**:
  - 🍏 **macOS (Universal .dmg)**:  
    [Fast CDN Mirror (Global/CN)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8.dmg) · *[GitHub Direct](https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8.dmg)*
  - 🪟 **Windows (NSIS .exe)**:  
    [Fast CDN Mirror (Global/CN)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8-amd64-installer.exe) · *[GitHub Direct](https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8-amd64-installer.exe)*

---

### 2. 🗄️ VloamDB
> **Modern, agile cross-platform database management workspace**  
> Intuitive, lightweight, and lightning-fast. Designed for modern engineering workflows with multi-engine support, intelligent SQL completion, visual schema designer, and sub-millisecond data exports.

- **Official Website**: [https://db.vloam.com](https://db.vloam.com)
- **Version Manifest**: [`db/version.json`](./db/version.json)
- **Direct Downloads**:
  - 🍏 **macOS (.dmg)**:  
    [Fast CDN Mirror (Global/CN)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/db-v3.5.1/VloamDB-3.5.1.dmg) · *[GitHub Direct](https://github.com/wuqiyin/releases/releases/download/db-v3.5.1/VloamDB-3.5.1.dmg)*
  - 🪟 **Windows (.exe)**:  
    [Fast CDN Mirror (Global/CN)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/db-v3.5.1/VloamDB-3.5.1-amd64-installer.exe) · *[GitHub Direct](https://github.com/wuqiyin/releases/releases/download/db-v3.5.1/VloamDB-3.5.1-amd64-installer.exe)*

---

## 🌐 Repository Architecture

```text
.
├── CNAME                  # Custom domain binding for dl.vloam.com
├── .nojekyll              # Bypasses Jekyll for raw static asset delivery
├── index.html             # Responsive online download center with auto-sync
├── README.md              # English documentation
├── README.zh-CN.md        # 简体中文说明文档
├── clip/
│   └── version.json       # Auto-update manifest for VloamClip
└── db/
    └── version.json       # Auto-update manifest for VloamDB
```

---

## 🔒 Security & Privacy

- **100% Genuine CI Artifacts**: Every released binary is automatically built and packaged inside GitHub Actions virtual machines from source code, free from manual tampering.
- **Strict Local-First Philosophy**: All Vloam applications follow a strict Local-First architecture. Sensitive user data (such as clipboard history and database credentials) is encrypted exclusively on your local device and is never uploaded to any cloud server.

---

© 2026 [Vloam](https://vloam.com). All rights reserved.
