# Desk

A private portfolio app that runs on your own computer. No account, no cloud: your data stays on your machine. Desk updates itself once installed.

## Download

Go to **[Latest release](https://github.com/yannalbrecht/desk-releases/releases/latest)** and, under **Assets**, download the one file for your computer:

| Your computer | Download | |
|---|---|---|
| **Mac with Apple Silicon** (M1, M2, M3, M4 …) | `Desk-<version>-arm64.dmg` | Most Macs from late 2020 on |
| **Mac with Intel** | `Desk-<version>.dmg` (no "arm64" in the name) | Older Macs |
| **Windows 10 / 11** | `Desk-Setup-<version>.exe` | |

You don't need the `.zip`, `.blockmap` or `.yml` files; Desk uses those to update itself.

**Which Mac do I have?** Apple menu  → **About This Mac**. If it says **Chip: Apple M…**, take the `arm64` file. If it says **Processor: … Intel …**, take the other `.dmg`.

## Install

**Mac:** open the `.dmg`, drag **Desk** into **Applications**, open it. Desk is signed and notarised by Apple, so it opens like any other app.

**Windows:** run the `.exe`. If Windows shows "Windows protected your PC", click **More info → Run anyway** (the Windows installer isn't certificate-signed yet; this happens once).

## First start

Choose **Import from Trade Republic** — Desk shows step by step how to export your transactions in the Trade Republic app (Profile → Account statements → Transaction export) — or set it up by hand with any broker, or restore a Desk backup.

## Updates

Automatic: Desk checks on start and every few hours, and shows **Restart to update** in Settings → Updates. Your data is never touched by an update.
