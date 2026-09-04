# Odysseus AI — Android
> Free, open-source, and self-hosted AI workspace.
A professional guide and automation suite to run **Odysseus** (the private, local-first AI workspace by PewDiePie) inside a sandboxed Linux environment directly on your Android device.
---
## 📋 Features & Overview

| Feature | Description |
| :--- | :--- |
| **Local-First & Private** | Keep chats, files, and workflows strictly on your device. |
| **One-Line Installer** | Sets up Ubuntu, configures Python virtual environments, builds libraries, and handles setup automatically. |
| **Custom Quick-Launch** | Start the server instantly with a single `./run.sh` execution. |
| **Android Optimizations** | Standardized build flags and dependencies configured for `aarch64` architectures inside Termux PRoot. |

---
## ⚙️ Prerequisites
Ensure your device meets these base specs before running the installer:
* **RAM:** Minimum 4GB (8GB+ recommended if loading local LLMs).
* **Storage:** 4GB to 6GB free internal space.
* **Termux (F-Droid):** Download from [F-Droid](https://f-droid.org/packages/com.termux/). Do **not** use the outdated Google Play Store release.
* **Internet:** High-speed connection for downloading rootfs layers, packages, and wheel builds.
---
## 🚀 Installation
### Method 1: Automated Setup (Recommended)
This automates package provisioning, PRoot setup, compilation flags, dependencies, and environment bootstrapping.
Open Termux and execute:
```
curl -sSL https://raw.githubusercontent.com/cloudaii/Odysseus/main/install.sh | bash
```
## start server 
```
./run-sh

```
## Default Credentials
Use these details to log in to the dashboard at http://localhost:7000:

Username: admin
Password: 71807180
