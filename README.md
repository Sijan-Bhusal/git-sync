# git-sync

Interactive git sync script for Obsidian vaults. Auto-commits local changes with a timestamp, then presents a contextual menu (upload/download/overwrite) based on divergence from remote.

## Usage

```
./git-sync
```

Runs from any git repo. Detects ahead/behind state and shows only relevant options. Destructive operations (force push, hard reset) require typing `yes` to confirm.
