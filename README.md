# eSim Tool Manager – Cross-Platform Package Manager

**Developed by Nu Htoo Wai**  

---

## 📥 Download Links

Due to GitHub file size limits, the installation packages are hosted on Google Drive:

[![Windows Standalone](https://img.shields.io/badge/Windows-Standalone-blue)](https://drive.google.com/drive/folders/1rJwD9MbCODEguAiY71DrJtYa-D-hUB68)

[![Windows Integrated](https://img.shields.io/badge/Windows-Integrated-blue)](https://drive.google.com/drive/folders/13GMW7EUhtYXDYDmdurjwR4Z8DWw-9wfS)

[![Ubuntu Standalone](https://img.shields.io/badge/Ubuntu-Standalone-orange)](https://drive.google.com/drive/folders/13CSONADwHme5IfLP7VnwVSlGlJBGD1-r)

[![Ubuntu Integrated](https://img.shields.io/badge/Ubuntu-Integrated-red)](https://drive.google.com/drive/folders/1uGchbRja0PgBr7O4V6lgfNofK4uR1QW) 

---

## 📌 Overview

**eSim Tool Manager** is a graphical tool that simplifies installing, updating, and managing all dependencies required by the eSim EDA platform.

**Supported OS:** Windows 10 / Ubuntu 22.04 LTS

**Goal:** One interface. Zero manual installers. No version hunting.

---

## 🛠️ Managed Tools

| Tool | Windows | Ubuntu |
|------|---------|--------|
| KiCad | Chocolatey / Direct | APT (PPA) |
| Ngspice | Chocolatey | Source build |
| GHDL | GitHub release | Source build |
| Verilator | .7z / MSYS2 | Source build |
| LLVM | Chocolatey | APT |
| eSim | FOSSEE server | Script installer |

---

## 📦 Available Versions

| Tool | Versions |
|------|----------|
| KiCad | 6, 7, 8, 9, latest |
| Ngspice | 35, 36, 37, 38, 39, 40, 41, 42, 43 |
| GHDL | 4.0.0, 4.1.0, 5.0.0, 5.1.1, latest |
| Verilator | 5.006, 5.018, 5.026, 5.032, latest |
| LLVM | 13, 14, 15, 16, 17, 18, 19, latest |
| eSim | 2.2, 2.3, 2.4, 2.5 |

---

## 🚀 Features

- **Version Selection** – Dropdown menus, no commands to remember
- **Real-Time Progress** – Live output, no frozen screens
- **Button Locking** – One click = one operation
- **One-Click Uninstall** – Select, confirm, done
- **Two Installation Modes** – Analog (~1.5 GB) or Digital (~3.0 GB)
- **Lightweight Launcher** – Opens instantly from toolbar
- **Smart Progress Bar** (Ubuntu) – Updates based on keywords
- **Smart Detection** (Windows) – No GUI launch or shell popups
- **KiCad Preservation** (Ubuntu) – Ngspice update no longer removes KiCad

---

## 🔧 Installation

### Windows (Run as Administrator)
```bash
python main.py
```

---

### Ubuntu
```bash
python3 main.py
```

---

## 🔗 Links

- eSim: https://esim.fossee.in
- FOSSEE: https://fossee.in

---
