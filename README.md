# fzf-kill

Fast, interactive process killer for Linux. No UI fluff. No bs.

## What it does
- Live `ps` output piped into `fzf`
- Fuzzy search + multi-select
- SIGTERM first, SIGKILL if needed

## Requirements
bash, fzf, ps, awk, kill

## Install
```bash
pull this epic repo
chmod +x pzz
sudo mv pzz /usr/local/bin/
```

## Usage
```bash
pzz # can also pass the search string as an argument
```
