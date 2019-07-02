# METU COMPUTER ENGINEERING MASTER THESIS

## Setting up the Environment

I heavily use vim and any other tools that support vim key shortcuts. For LaTeX
editing I prefer [vimtex](https://github.com/lervag/vimtex/) vim plugin and
[zathura](https://git.pwmt.org/pwmt/zathura) pdf viewer that has great vim key
bindings. You may want to checkout my
[dotfiles](http://github.com/gokhanettin/dotfiles) for further configuration
details. This repo uses TeX Live 2017 that comes with Ubuntu 18.04. For other
Ubuntu versions or for any other operating systems, you may consider installing
Tex Live 2017 from [historical
releases](https://www.tug.org/texlive/acquire-netinstall.html).

Download dependencies on Ubuntu 18.04.

```bash
$ sudo apt-get update
$ sudo apt-get install zathura xdotool libsynctex-dev libgtk-3-dev \
    texlive-full
```
