<p align="center">
  <img src="assets/icon.svg" alt="Arctic Downloader" width="160">
</p>

# 🧊 Arctic Downloader
[![Flatpak](https://img.shields.io/badge/Flatpak-App%20Bundle-4895EF?logo=flatpak&logoColor=white)](#-%F0%9F%9B%A0-requirements)
[![ComfyUI Helper](https://img.shields.io/badge/ComfyUI-Asset%20Catalog-9B59B6)](https://github.com/comfyanonymous/ComfyUI)
[![Status](https://img.shields.io/badge/Status-Active-success)](#-need-help)

A **curated asset companion** for ComfyUI users who want to grab the right models, VAEs, and LoRAs without hunting through endless links. Tell the app your GPU VRAM and system RAM tiers and it highlights the builds that match my YouTube tutorial setups—then downloads everything into the correct ComfyUI folders with live progress.

---

## 📚 Overview

Arctic Downloader mirrors the exact builds I showcase in videos so you can follow along with zero guesswork. Think of it as a catalog plus a giant “download” button that keeps your ComfyUI directory organized.

---

## 🧩 Core Features

- 🧠 **Tier-aware catalog** that presents only the models and LoRAs that fit your VRAM and RAM.
- 📦 **Auto-dependency downloads** for text encoders, CLIPs, upscalers, and other must-haves.
- 🗂️ **Smart placement** that drops files into the right ComfyUI subfolders immediately.
- 📈 **Live progress + completion summary** with buttons to open the downloaded files.
- 🔐 **Optional Civitai token support** for creators who require authenticated downloads.

---

## 🚀 Getting Started

1. **Install ComfyUI** and note its directory. Need a distro-aware installer? Use <https://github.com/ArcticLatent/linux-comfy-installer>.
2. **Download the latest `.flatpak`** from this repo’s Releases page.
3. Install it:
   ```bash
   flatpak install --user ./ArcticDownloader.flatpak
   ```
4. Launch Arctic Downloader and point it at your ComfyUI folder when asked.

Browse, click download, and the app handles the rest.

---

## 🛠 Requirements

- Active internet connection (for pulling assets).
- Flatpak runtime on your system:

  ```bash
  # Ubuntu / Debian / Linux Mint
  sudo apt install flatpak

  # Fedora (already included on Workstation editions)
  sudo dnf install flatpak

  # Arch / Manjaro
  sudo pacman -S flatpak
  ```

- If you previously ran <https://github.com/ArcticLatent/post-linux>, you already have the required runtimes and codecs.

---

## 💡 Usage Tips

- VRAM tiers (S, A, B, C) map directly to GPU size—pick the lowest tier that fits to avoid OOM errors.
- Use the in-app legend for a refresher on quantization terms like `fp16`, `fp8`, and `GGUF`.
- Upgraded your hardware later? Just change your tier and the catalog refreshes automatically.

---

## 🔐 Optional Civitai Access

- Some LoRAs require you to be logged in on Civitai.
- Generate a free API key on the Civitai website, paste it into the LoRA section in-app, and click **Save**.
- Keys never leave your machine—they’re stored locally and used only for authenticated download requests.

---

## 🆘 Need Help?

Open an issue in this repository if you hit a bug, need troubleshooting, or want to request new asset packs.

Enjoy smoother ComfyUI setups!

---

## 🧊 Author

Burce Boran 🎥 Asset Supervisor / VFX Artist | 🐧 Arctic Latent

[![YouTube – Arctic Latent](https://img.shields.io/badge/YouTube-%40ArcticLatent-FF0000?logo=youtube&logoColor=white)](https://youtube.com/@ArcticLatent)
[![Patreon – Arctic Latent](https://img.shields.io/badge/Patreon-Arctic%20Latent-FF424D?logo=patreon&logoColor=white)](https://patreon.com/ArcticLatent)

---

Copyright (c) 2025 Arctic Downloader. All Rights Reserved.

This software is proprietary and closed-source.

You may download and use the compiled Flatpak package for personal use only. Redistribution, modification, reverse engineering, or commercial use of this software or any included assets is prohibited without written permission from the copyright holder.

The software is provided “as is” without warranty of any kind.
