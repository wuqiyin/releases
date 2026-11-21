# Vloam Releases Hub

<p align="center">
  <b>Vloam 官方应用矩阵公共分发与更新中心</b><br>
  Official release and distribution hub for Vloam cross-platform desktop products.
</p>

<p align="center">
  <a href="https://dl.vloam.com"><img src="https://img.shields.io/badge/Download_Hub-dl.vloam.com-0284c7?style=flat-square&logo=googlechrome&logoColor=white" alt="Download Portal"></a>
  <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-1e293b?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-818cf8?style=flat-square" alt="License">
</p>

---

本仓库是 **Vloam** 软件矩阵的官方发布载体。所有产品的最新安装包（`.dmg`、`.exe`）与版本更新元数据（`version.json`）均通过自动化 CI 流水线在此归档与分发。

访问在线下载门户：**[https://dl.vloam.com](https://dl.vloam.com)**

---

## 📦 产品矩阵与极速下载

### 1. 📋 VloamClip
> **手不离键盘的极速跨平台剪贴板利器**
> 专为程序员与效率探索者打造。全键盘流穿梭漫游、Vim 级浏览、FIFO/LIFO 连续粘贴队列与本地纯净 AES-256 安全加密，守护击键心流。

- **官方网站**：[https://clip.vloam.com](https://clip.vloam.com)
- **最新版本**：`v1.1.8`
- **版本配置**：[`clip/version.json`](./clip/version.json)
- **下载通道**：
  - 🍏 [macOS 下载 (Universal .dmg)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8.dmg) · *(原始直链: [GitHub](https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8.dmg))*
  - 🪟 [Windows 下载 (NSIS .exe)](https://ghfast.top/https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8-amd64-installer.exe) · *(原始直链: [GitHub](https://github.com/wuqiyin/releases/releases/download/clip-v1.1.8/VloamClip-1.1.8-amd64-installer.exe))*

---

### 2. 🗄️ VloamDB
> **现代高效跨平台数据库开发与管理工作台**
> 直观、敏捷、极速响应。专为现代研发流程设计，支持多数据库引擎、智能 SQL 补全、可视化表结构设计与海量数据毫秒级导出。

- **官方网站**：[https://db.vloam.com](https://db.vloam.com)
- **版本配置**：`db/version.json`
- **下载通道**：
  - 🍏 [macOS 下载 (.dmg)](https://github.com/wuqiyin/releases/releases?q=db-)
  - 🪟 [Windows 下载 (.exe)](https://github.com/wuqiyin/releases/releases?q=db-)

---

## 🌐 目录结构说明

```text
.
├── CNAME                  # 绑定 dl.vloam.com 域名
├── .nojekyll              # 禁用 Jekyll 保证静态资源直出
├── index.html             # dl.vloam.com 在线下载中心首页
├── clip/
│   └── version.json       # VloamClip 客户端检测更新索引
└── db/
    └── version.json       # VloamDB 客户端检测更新索引
```

---

## 🔒 隐私与安全性

- **100% 官方原版构建**：所有 Releases 附件均由 GitHub Actions 官方运行器编译与打包，无任何人工二次篡改。
- **本地优先原则**：Vloam 旗下应用均贯彻 Local-First 理念，敏感数据（剪贴板内容、数据库密码）仅在本机安全加密保存，严禁任何形式的私自上云。

---

© 2026 [Vloam](https://vloam.com). All rights reserved.
