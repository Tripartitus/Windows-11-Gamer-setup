# 🚀 Win11GS — Windows 11 Ultimate Gamer Setup

**The ultimate fully automated optimization script for Windows 11 gamers.**  
**Now with a modern graphical interface!**

One script. Zero hassle. Maximum performance.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Windows 11](https://img.shields.io/badge/Windows-11-blue?logo=windows)](https://www.microsoft.com/windows/windows-11)
[![PowerShell](https://img.shields.io/badge/PowerShell-7+-blue?logo=powershell)](https://github.com/PowerShell/PowerShell)
[![GUI](https://img.shields.io/badge/GUI-Windows%20Forms-green)](https://learn.microsoft.com/en-us/powershell/scripting/windows-powershell/creating-gui-applications)

---
<a href="https://cdn.corenexis.com/files/c/2946456720.png"><img src="https://cdn.corenexis.com/files/c/2946456720.png" alt="2946456720" border="0"></a>
## ✨ What It Does

This script transforms a fresh or bloated Windows 11 installation into a **high-performance gaming machine** with a single click — now featuring a beautiful, interactive GUI!

### Key Features

#### 🖥️ Features
- **Modern Windows Forms GUI** — No more command-line! Interactive phase selection with checkboxes
- **Real-time Progress Tracking** — Live status updates and progress bar as phases run
- **Color-coded Logging** — Green for success, Yellow for info, Red for warnings — all visible in-app
- **Confirmation Gate** — Safety dialog before any changes are made
- **Smart UAC Elevation** — Automatically requests admin rights (manifest + fallback)
- **Detailed Logging** — Everything is logged to `C:\GamerSetup_YYYYMMDD_HHMMSS.log`

#### ⚙️ Optimization Engine (All Selectable)
- **System Repair** — Full DISM + SFC + disk health check
- **Deep Cleanup** — Removes temp files, prefetch, Windows Update cache, thumbnail cache, recent files, jump lists, icon cache, and error reports
- **Smart Disk Optimization** — Automatically runs TRIM on SSDs or Defragmentation on HDDs
- **Update Management** — Checks for and automatically installs available application updates via winget
- **Gaming Optimizations**
  - Ultimate Performance power plan
  - Hardware-accelerated GPU Scheduling enabled
  - Visual effects set to "Best Performance"
- **Low Latency Network**
  - DNS + Winsock + IP stack reset
  - **Nagle’s Algorithm disabled** on all active adapters (reduces ping & input lag)
- **Aggressive Debloat**
  - Removes 20+ bloatware apps (Bing, Cortana, Solitaire, etc.)
  - Completely removes OneDrive
  - Disables telemetry services and scheduled tasks
- **Privacy Hardening**
  - Disables Recall, Copilot AI features, activity tracking, and fingerprinting vectors
  - Extensive registry tweaks for maximum privacy
- **Automatic Software Installation**
  - All Visual C++ Redistributables (2005 → 2022, x86 + x64)
  - All .NET Runtimes (Framework 4.8 + Desktop Runtime 6, 7, 8)
  - DirectX End-User Runtime
  - **7-Zip**
  - **Mozilla Firefox**
  - **WinRAR**

- **Fully Automated** — No prompts, no decisions, just run it and walk away (or fine-tune via GUI)
- **Self-contained single EXE** — No PowerShell execution policy issues, no dependencies

---

## 🚀 Quick Start (Recommended)

1. Download the latest version from the [Releases](https://github.com/Tripartitus/Windows11-Gamer-Setup/releases) page
2. Double-click **`Win11GS.exe`**
3. Accept the UAC prompt
4. **Select the phases** you want to run (all recommended for fresh setups)
5. Click **"Run Selected Phases"**
6. Review the confirmation dialog and click **Yes**
7. Watch the live progress, colored logs, and enjoy!

**Everything runs automatically after confirmation.** No further input needed.

---

## 📋 Requirements

- Windows 11 (22H2 or newer recommended, 23H2/24H2 ideal)
- Administrator rights (script handles elevation)
- Internet connection (for updates and installations)
- ~5-10 minutes for full run (longer if installing many updates)

---

## ⚠️ Important Notes

- A **restart is strongly recommended** after running the script for all optimizations to take full effect
- The script is safe and reversible in most cases (full log provided for review)
- **Backup important files** before running the Debloat + Privacy phases
- Some phases (DISM, winget updates, dependency installs) can take **15–40 minutes** depending on your system and internet
- Full log is always saved at `C:\GamerSetup_*.log` — perfect for troubleshooting or sharing
- The GUI provides granular control — you can run individual phases or the full suite

---

## ❤️ Credits

Created by **Tripartitus**  
Official Gaming Channel: **TripartitusGaming**

---

**Star this repo if it helped you!** ⭐

*Questions, feature requests, or bug reports? Open an issue on GitHub — feedback is always welcome!*

**Ready to supercharge your Windows 11 gaming rig?**  
Download • Launch • Select • Optimize • Game! 🎮
