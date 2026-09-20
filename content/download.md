---
title: "Download Cline for Linux"
description: "Download Cline AI coding agent for Linux x86_64: AppImage (universal) or .deb (Debian/Ubuntu). Free, auto-built from source."
---

All Linux packages are built in the open by GitHub Actions from the [fork source](https://github.com/10xdev4u-alt/cline) and published on the releases page.

## Latest release

**[Download from GitHub Releases →](https://github.com/10xdev4u-alt/cline/releases)**

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
