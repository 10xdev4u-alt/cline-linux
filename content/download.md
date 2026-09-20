---
title: "Download Cline for Linux"
description: "Download Cline AI coding agent for Linux x86_64: AppImage (universal) or .deb (Debian/Ubuntu). Free, auto-built from source."
---

All Linux packages are built in the open by GitHub Actions from the [fork source](https://github.com/10xdev4u-alt/cline) and published on the releases page.

## Latest release — v0.0.32

**[.deb for Ubuntu/Debian/Mint (x86_64, 109 MB) →](https://github.com/10xdev4u-alt/cline/releases/download/desktop-linux-v0.0.32/Cline_0.0.32_amd64.deb)**

```bash
sudo apt install ./Cline_0.0.32_amd64.deb
```

**[AppImage, any distro (x86_64, 182 MB) →](https://github.com/10xdev4u-alt/cline/releases/download/desktop-linux-v0.0.32/Cline_0.0.32_amd64.AppImage)**

```bash
chmod +x Cline_0.0.32_amd64.AppImage
./Cline_0.0.32_amd64.AppImage
```

Verify either file against [SHA256SUMS](https://github.com/10xdev4u-alt/cline/releases/download/desktop-linux-v0.0.32/SHA256SUMS):

```bash
sha256sum -c SHA256SUMS --ignore-missing
```

Older and future versions: [all releases →](https://github.com/10xdev4u-alt/cline/releases) · [latest release →](https://github.com/10xdev4u-alt/cline/releases/latest) · [version history →](/cline-linux/releases/)

| Package | Best for | Install |
|---|---|---|
| `.AppImage` | Any distro, no install | `chmod +x Cline_*.AppImage && ./Cline_*.AppImage` |
| `.deb` | Debian / Ubuntu / Mint | `sudo dpkg -i cline_*.deb` or `sudo apt install ./cline_*.deb` |

## Verify your download

Releases carry SHA256 checksums next to each artifact. Compare before running:

```bash
sha256sum -c SHA256SUMS --ignore-missing
```

## Auto-updates

Linux bundles currently do **not** auto-update (the updater feed covers macOS/Windows). Re-download on new releases — watch the repo or check back here. Feed support is tracked upstream in the fork.
