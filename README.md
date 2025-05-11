# FreezeActive.sh
## Simple script for HyprLand to freeze windows ( process ) in focus
## You can add a hotkey to your HyprLand config:
### bind = Super+Ctrl+Shift, Z, exec, /path/to/script.sh
## Do you want to use it not in HyprLand?
### Add a command to get the processor ID in line 3
#### PID="$(hyprctl -j activewindow | jq .pid)"
