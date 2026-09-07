# Nokiatis Launcher — Update Channel

Public update channel for the Nokiatis Launcher.

**This repository contains no source code.** It only hosts:

| File | Purpose |
|---|---|
| `policy.json` | Force-update policy (kill switch + minimum forced version) |
| `updates.json` | Signed Tauri updater manifest (published by CI on every release) |

Update artifacts are signed with minisign (Tauri updater). Launchers verify signatures against the public key embedded at build time.

- This channel: public, so every player can receive updates
