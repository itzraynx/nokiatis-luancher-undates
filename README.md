# Nokiatis Launcher — Update Channel

Public update channel for the [Nokiatis Launcher](https://github.com/itzraynx/nokiatis-luancher-beta-modtint).

**This repository contains no source code.** It only hosts:

| File | Purpose |
|---|---|
| `policy.json` | Force-update policy (kill switch + minimum forced version) |
| `updates.json` | Signed Tauri updater manifest (published by CI on every release) |

Update artifacts are signed with minisign (Tauri updater). Launchers verify signatures against the public key embedded at build time.

- Source code: private (`nokiatis-luancher-beta-modtint`)
- This channel: public, so every player can receive updates
