<div align="center">

<br>
<h3> Config for fish </h3>

<h6> Config for fish on my MacBook. You mustn't use it on linux because it has several features for mac only </h6>

[![License](https://img.shields.io/github/license/S0LYER/fish?color=orange&style=flat-square)](LICENSE)
<br>
[![Fish](https://img.shields.io/badge/Fish-3.7_|_4.0-34C534?style=flat-square&logo=fishshell&logoColor=white)](https://fishshell.com)
[![macOS](https://img.shields.io/badge/macOS-tahoe-000000?style=flat-square&logo=apple&logoColor=white)](https://apple.com/macos)

</div>

<br>

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
git clone https://github.com/S0LYER/fish
cd fish
cp config.fish ~/.config/fish
```

---

> [!NOTE]
> You can use my [starship config](https://github.com/S0LYER/starship) for best view
