alexmux will be built on following principles:
- fuzzy finding. fuzzy find over existing terminals, commands that you don't memorize shortcut 
- small feature list, no bloat, build over time
- be able to scroll back by default, tmux scrollback is painful
- sane copy paste, just like vscode
- sane default config and stuff works out of the box

so, tmux but better. kind of how like how ghostty is iterm but more fluid

design:
- terminals are memory, and we build views into them
- terminals will be persisted using some backend like gnu screen
- can build windows by selecting terminals, a shape, etc. a window will be a view into panes

open to other ideas, such as a global windows view
