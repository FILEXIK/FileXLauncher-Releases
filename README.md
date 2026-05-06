# FileXLauncher (In Development) 🚀

A modern, customizable Minecraft launcher with plans for future features like shared settings across instances, advanced instance manager, themes, and much more! 🌟

# 🚀 Advanced Minecraft Launcher Features

## 🏗️ Core Architecture & System
* **Full Portability:** No installation required. All data, configurations, and game files are stored within a single directory.
* **Admin-Free Operation:** Uses standard file copying instead of symbolic links (symlinks), eliminating the need for Administrator privileges or UAC prompts.
* **Relative Pathing System:** The launcher is location-independent; run it from a USB drive, external disk, or cloud folder without breaking file links.
* **Embedded JRE (Java Runtime Environment):** Includes isolated Java versions tailored for specific Minecraft releases, removing the need for system-wide Java installations.
* **Kotlin Compose Multiplatform:** Built on a modern tech stack for native UI performance and smooth cross-platform compatibility.

## ⚡ Performance & Resource Management
* **Extreme RAM Optimization (Hibernation Mode):** While the game is running, the launcher aggressively offloads resources, reducing its memory footprint to **~5 MB**.
* **Dynamic UI Scaling:** In browsing mode, the launcher utilizes the full power of the Skia engine (400 MB – 1 GB RAM) for fluid animations and high-speed asset loading.
* **Instance Resource Sharing:** Intelligent file copying between instances in the same category to save disk space without the stability risks of symlinks.
* **Auto-Repair System:** Automatically verifies instance integrity and restores corrupted or missing files from official repositories.
* **Multi-Instance Support:** Run and manage multiple game instances simultaneously through a built-in task manager.

## 📦 Modding & Content Ecosystem
* **Integrated Content Catalog:** Browse and install mods, packs, and shaders directly from **Modrinth** and **CurseForge** within the app.
* **Automatic Dependency Handling:** Detects and installs required libraries (e.g., Fabric API, Architectury) automatically during mod installation.
* **Full Loader Support:** Native support for Forge, Fabric, Quilt, and NeoForge.
* **Advanced Modpack Management:** Full compatibility with Modrinth and CurseForge modpacks, including specialized server-side packs.
* **Custom Version Support:** Support for experimental versions (e.g., Combat Updates) via manual JSON configuration imports.
* **Load Order Manager:** Manage the priority of resource packs, mods, and shaders directly in the launcher without launching the game.

## 📥 Advanced Download Manager
* **Parallel Downloading (Multi-threading):** Significantly speeds up modpack installations by downloading multiple files simultaneously.
* **Download Queue Management:** Real-time monitoring and control of all active background tasks.
* **Thread Customization:** Allows users to manually adjust the number of concurrent download threads based on their network capacity.

## 🔐 Security & Account Management
* **Encrypted Account Vault:** Sensitive account data is protected by industry-standard encryption, accessible only via a user-defined **Master Password**.
* **Unified Account Manager:** Seamlessly switch between multiple Microsoft (Premium) and Local (Offline) accounts.

## 🎨 Customization & UX
* **Modern Aesthetic:** High-fidelity animations and a responsive, state-driven interface.
* **User-Defined Categories:** Organize instances into custom groups (e.g., "Survival," "Technical," "Server Tests").
* **Advanced Theming Engine:**
    * Built-in interactive themes.
    * An integrated **Theme Creator** for full visual personalization.
* **Detailed Playtime Tracking:** Monitor hours spent in each individual instance and across the entire launcher.


## Installation 🛠️

### Requirements:
- Windows 10, 11 / Linux
- Minecraft (of course!)

## Planned Features 🔮
## 🔗 Fast Modpack Sharing (Social Feature)
* **One-Click Configuration Export:** Automatically scans the `.mods` folder, matches files to the Modrinth database, and generates a lightweight `.json` "recipe" for sharing.
* **"Missing Link" Detection:** If a mod is not found in public databases, the launcher flags it and notifies the recipient to add it manually, maintaining a status alert until the pack is complete.
* **Instant Import:** Recipients can download entire 300+ mod setups by importing a file weighing only a few kilobytes.

Stay tuned for future updates! 🚀

THIS LAUNCHER IS AN INDEPENDENT PROJECT AND IS NOT AFFILIATED WITH, ENDORSED BY, OR IN ANY WAY CONNECTED TO MOJANG STUDIOS OR MICROSOFT. ALL TRADEMARKS, LOGOS, AND ASSETS RELATED TO MINECRAFT ARE THE PROPERTY OF THEIR RESPECTIVE OWNERS.
