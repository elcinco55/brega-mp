# Brega releases

Brega is a mod platform for the game **My Winter Car**: the **Brega Launcher** installs and updates the Brega Loader
and the mods **BregaMP** (multiplayer) and **BregaFPS** (performance), backs up your saves and starts the game.

## Download

New players: download [BregaSetup.exe](https://github.com/elcinco55/brega-mp/raw/main/BregaSetup.exe), run it and press INSTALL. It installs the Brega Launcher for your Windows user only
(no administrator rights) and adds a Start menu shortcut. Open the launcher, back up your save, then press INSTALL in
the launcher. Uninstall it from Windows' Installed apps (use RESTORE ORIGINAL in the launcher first if Brega is
installed in the game).

## What is in this repository

Built binaries only, no source code:

- `BregaSetup.exe`: the installer (it carries the launcher).
- `channels/stable/manifest.json` + `manifest.json.sig`: the release list, signed with the team's ed25519 key.
  The launcher refuses any release whose signature does not match the key built into it.
- `files/<sha256>`: the release files, named by their SHA-256; the launcher checks every hash before installing.

Release 0.7.2 (launcher 0.7.1).

## Credits and notice

Made by **elcinco5** and **rickchurrasco**. Contains AI-generated code (Claude, Anthropic).
My Winter Car is made by Amistech Games; this project is not affiliated with them.
