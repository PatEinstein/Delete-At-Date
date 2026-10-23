# 🗑️ Delete At Date

Delete At Date is a Windows utility that schedules individual files for automatic removal on a date you choose.


**Professional File Deletion & Shredding Utility**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue)](../../releases)
[![License](https://img.shields.io/badge/License-Freeware-green)](../../license.txt)
[![Version](https://img.shields.io/badge/Version-v1.0.5-blue)](../../releases/latest)

**Delete At Date** is a high-performance Windows utility designed by **Gremsoft** to help you maintain a clean and organized digital workspace. Whether it's temporary downloads, old installers, or sensitive logs, this tool ensures they are removed exactly when you want them to be.

**Delete At Date is Freeware** — free of charge for personal and commercial use. No license fee, no subscription, no registration and no nag screens.

---

## ✨ Key Features

- 📅 **Precision Scheduling** – Pick any future date for automatic file removal.
- 🔒 **Secure Shredding** – Optional random-data overwriting for sensitive data (single-pass random overwrite).
- 🖱️ **Modern UI/UX** – Full drag-and-drop support and a clean, responsive interface.
- 🔍 **Live Filtering** – Instantly find scheduled items using real-time search.
- 📊 **Advanced Dashboard** – View total space to free, lifetime deletions, activity history, and live statistics.
- ⚙️ **Background Resilience** – Integrated with Task Scheduler to handle runs missed while the PC was off.
- 🛡️ **System Guard** – Intelligent protection against accidental deletion of critical system files.
- 🧩 **Integrity Check** – Validates file CRC32 hashes before deletion to prevent erasing modified data.
- 🔐 **Obfuscated Configuration** – Your schedule is stored using AES-256-CBC with a per-save random key embedded in the file. This protects against casual reading (e.g. Notepad) but not against anyone who has the file. Do not put secrets in scheduled file paths.

---


## 🖥️ System Requirements

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **Permissions:** Standard User (Administrator required for Task Scheduler integration)
- **Footprint:** Extremely lightweight, self-contained executable (no runtime required)

---

## 📦 Installation & Setup

1. Download the latest release package (`DeleteAtDate-v1.0.5-Setup.zip`) and extract and run the installer.
2. Follow the installation wizard to configure your preferred background processing method.
3. Launch **Delete At Date** and start organizing your workspace.

---

## 🚀 Quick Start Guide

### 1. Schedule a File
Simply **drag and drop** a file onto the application window, or use the **"Schedule a File..."** button. Select your desired deletion date from the calendar.

### 2. Configure Deletion Type
Right-click any item in the list to toggle between **Standard Delete** (moves to Recycle Bin) and **Secure Shred** (permanent erasure).

### 3. Monitor Activity
Use the **Dashboard** (`File > Dashboard`) to track completed operations and see how much disk space you've reclaimed over time.

---

## ❓ Frequently Asked Questions

**Q: Does the app need to stay open?**
> No. Once configured with Task Scheduler or Registry startup, the background service handles all tasks silently.

**Q: What if my computer is off on the deletion date?**
> The application is designed to be resilient. It will process all expired schedules immediately upon the next system startup.

**Q: Is it safe to use?**
> Yes. Built-in safeguards prevent the selection of system folders and critical operating system files.

**Q: What is the difference between Standard Delete and Secure Shredding?**
> Standard Delete safely moves your files to the Windows Recycle Bin, allowing you to restore them if needed. Secure Shredding overwrites the file's data before permanent deletion, making it impossible to recover even with forensic software.

**Q: Will it delete files I have recently modified?**
> No. Delete At Date uses CRC32 Integrity Checks. If a file's content has changed since the moment you scheduled it, the application will skip deletion to protect your updated work.

**Q: Can I schedule entire folders?**
> No. For maximum safety and granular control, the application strictly focuses on per-file scheduling. Deleting entire folders is not supported by design to prevent accidental mass data loss.

---

## ⚖️ Legal Disclaimer
**IMPORTANT: PLEASE READ CAREFULLY**

By using **Delete At Date**, you acknowledge and agree to the following:
- **No Liability:** Gremsoft (the developer) shall not be held responsible or liable for any direct, indirect, incidental, or consequential damages, including but not limited to: permanent loss of data, accidental deletion of important files, hardware failure, or financial loss resulting from the use or misuse of this software.
- **Use at Own Risk:** This utility is designed to delete files. Use it with extreme caution. Always verify your selection before scheduling.
- **No Warranties:** The software is provided "AS IS", without warranty of any kind, express or implied.
- **Irreversible Actions:** The "Secure Shredding" feature permanently overwrites data. Once shredded, files cannot be recovered by any known means.

---

## 📄 License & Legal

**Delete At Date** is **Freeware**: free to use for personal and commercial purposes, at no cost. There is no purchase price, license key, trial period or feature limitation.

- **License type:** Freeware (see `license.txt` for the full End-User License Agreement)
- **Developer:** Gremsoft — *Innovation. Pure Power. High Intelligence.*
- **Copyright:** © 2026 Gremsoft. All rights reserved.
- **Redistribution:** Permitted only via the original, unmodified installer.

---

*Made with passion by Gremsoft.*
