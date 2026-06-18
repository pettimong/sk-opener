# sk-opener

A blazing fast, minimalist terminal file launcher combining `fd` and `skim` (`sk`). It automatically detects file MIME types and opens them with your preferred applications, matching the behavior of modern file managers like Yazi.

## Features
- Fully compliant with the UNIX philosophy (Do one thing and do it well).
- Fast fuzzy-finding with `fd` and `skim`.
- Automatic media dispatching (`mpv`, `imv`, `zathura`, `vim`, etc.).

## Dependencies
Make sure you have the following tools installed:
- [fd](https://github.com/sharkdp/fd)
- [skim](https://github.com/lotabout/skim)
- `file` (for MIME-type detection)
