---
title: "Install Cline on Linux"
description: "Install the Cline AI coding agent on Linux in 2 minutes: AppImage or deb, system requirements, first run with free models."
---

## Option A — AppImage (any distro)

```bash
chmod +x Cline_*_amd64.AppImage
./Cline_*_amd64.AppImage
```

## Option B — deb (Debian/Ubuntu/Mint)

```bash
sudo apt install ./cline_*_amd64.deb
```

## First run

1. Launch **Cline** from your app menu (or the AppImage directly).
2. Sign in with **ClinePass** (`cline auth cline` works too).
3. Pick a free model — e.g. DeepSeek V4 Flash, GLM, Qwen (`:free` suffix), or Kimi K3 on the ClinePass tier.
4. Open a folder and start building.

## Requirements

x86_64 CPU, GTK 3 + WebKit2GTK 4.1 (preinstalled on Ubuntu 22.04+; `sudo apt install libwebkit2gtk-4.1-0` if the AppImage complains).
