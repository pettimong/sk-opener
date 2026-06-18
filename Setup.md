# Setup Instructions

## 1. Installation
Copy the `sk-open` script to your local bin directory:
```bash
mkdir -p ~/.local/bin
cp sk-open ~/.local/bin/

Make sure ~/.local/bin is in your $PATH.
2. Shell Alias (Optional)

Add this to your ~/.bashrc or ~/.zshrc:
Bash

alias sf='sk-open'

3. Hyprland Keybind (Optional)

To launch it globally with SUPER + SHIFT + F, add the following to your hyprland.conf:
Ini, TOML

bind = $mainMod SHIFT, F, exec, kitty --class "kitty-search" -e bash -ci "sk-open"

