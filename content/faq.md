---
title: "FAQ — Cline on Linux"
description: "FAQ: is Cline free on Linux, which free AI models work, AppImage vs deb, auto-updates, support."
---

## Is Cline free on Linux?

The app is free and open-source (Apache 2.0). Model usage goes through providers — the Cline gateway offers 20+ `:free` models (DeepSeek, GLM, Qwen, Nemotron, Gemma) plus a ClinePass free tier that includes Kimi K3.

## AppImage or deb?

AppImage runs anywhere with one file; deb integrates with your system (menu entry, updates via apt once a repo exists). Same app inside.

## Do Linux builds auto-update?

Not yet — the updater feed currently serves macOS/Windows. Re-download new releases until feed support lands.

## Which models are free right now?

Any gateway id ending in `:free` (e.g. `deepseek/deepseek-v4-flash-0731:free`), subject to upstream availability — free tiers rate-limit (429) and rotate ids occasionally.

## Where do I report Linux bugs?

Open an issue on the [fork](https://github.com/10xdev4u-alt/cline/issues) — mention AppImage vs deb and your distro/version.
