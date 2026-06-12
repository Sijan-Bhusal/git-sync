# git-sync

Interactive git sync script for Obsidian vaults. Auto-commits local changes with a timestamp, then presents a contextual menu (upload/download/overwrite) based on divergence from remote.

## Dependencies

Requires [gum](https://github.com/charmbracelet/gum) for the interactive UI.

- **Arch:** `sudo pacman -S gum`
- **Ubuntu:** Download the latest `.deb` from the [releases page](https://github.com/charmbracelet/gum/releases) or use the Go install: `go install github.com/charmbracelet/gum@latest`

## Usage

```
./git-sync
```

Runs from any git repo. Detects ahead/behind state and shows only relevant options. Destructive operations (force push, hard reset) require confirmation.
