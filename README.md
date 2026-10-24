# Mimir releases

Installers for **Mimir**, a background app that takes notes on your calls entirely on your own computer (whisper.cpp + Ollama, notes in Obsidian). Built by Aperture Labs.

This repository only holds the installers; installed copies of Mimir check it for updates.

## Install

Download from the [latest release](https://github.com/aperture-labs-hq/mimir-releases/releases/latest):

- **Mac (Apple Silicon):** `Mimir-<version>-mac-arm64.dmg`. Open it and drag Mimir to Applications. The app isn't notarized by Apple yet: the first time, go to **System Settings › Privacy & Security › Open Anyway**, or run `xattr -dr com.apple.quarantine /Applications/Mimir.app`.
- **Windows:** `Mimir-Setup-<version>.exe`. If SmartScreen warns, click **More info › Run anyway**.

Then install [Ollama](https://ollama.com/download), and in Mimir download a Whisper model and a summary model, and pick your Obsidian vault.

## Updates

Mimir checks this repository every few hours, downloads new versions in the background, and installs them when you click **Restart to update** (tray menu or Settings › General) or the next time it quits.
