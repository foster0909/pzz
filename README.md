# fzf-kill

Fast, interactive process killer for Linux. No UI fluff. No mercy.

## What it does
- Live `ps` output piped into `fzf`
- Fuzzy search + multi-select
- SIGTERM first, SIGKILL if needed
- Filters out itself and helper junk

## Requirements
bash, fzf, ps, awk, kill

## Install
```bash
chmod +x pzz
sudo mv pzz /usr/local/bin/
