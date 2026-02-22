# using the application

Usage:

`./niri-window-switcher`

Requirements: niri, jq, and fzf must be installed.
You can bind this to a hotkey in your niri config, for example:
binds {
    Mod+W { spawn "sh" "-c" "/home/sleep/niri-window-switcher.sh"; }
}
