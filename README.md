# Config for fish
Config for fish on my MacBook. You mustn't use it on linux because it has several features for mac only

## Features
* Set NeoVim by default
* Added HomeBrew in path
* Added LLVM, QT5, QT6, .NET Tools
* Autojump
* Missclick protection in aliases
* EZA, BAT, FZF integration
* Starship initialization and neofetch in startup
* Ranger integration (When working with ranger, a file is created.temp, which saves the current directory where the user is located. When exiting ranger the user ends up in exactly the directory from which he exited while in ranger. After that the file .temp is automatically deleted)

> [!IMPORTANT]
> You should install LLVM, QT5, QT6, .NET Tools or comment lines in config.fish to use this config comfortable

## Installation
```
git clone https://github.com/GadzhievAleksandr/fish
cd fish
cp config.fish ~/.config/fish
```
