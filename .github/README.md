[**Back to @oreo-zip**](https://github.com/oreo-zip)

<h1 align="center"><img src="logo-rice.svg" width=100><br><img src="https://img.shields.io/badge/LUA-blue?style=for-the-badge&logo=lua">    <img src="https://img.shields.io/badge/OPEN%20SOURCE-purple?style=for-the-badge&logo=git">    <img src="https://img.shields.io/github/stars/oreo-zip/dotfiles?color=yellow&label=STARS&logo=Github&style=for-the-badge">    <img src="https://img.shields.io/github/license/oreo-zip/dotfiles?label=LICENSE&logo=gnu&logoColor=white&style=for-the-badge"></h1>

<p align="center">
  My <b>AwesomeWM and Arch Linux</b> configs!
  <br>
  Heavily inspired by <b><a href="https://github.com/saimoomedits">saimoomedits</a></b> and his <b><a href="https://github.com/saimoomedits/dotfiles">dots</a></b>!
</p>
<div align="center">
  <b>
    <a href="https://github.com/oreo-zip/dotfiles#Setup">Setup</a>
    •
    <a href="https://github.com/oreo-zip/dotfiles/LICENSE">License</a>
    •
    <a href="https://github.com/oreo-zip/dotfiles/issues">Bugs</a>
  </b>
</div>

<br>

## ATTENTION: STILL WIP

## <samp>Hey there</samp> <img src="https://img.shields.io/badge/AWESOME%20WM-gray?style=for-the-badge&logo=awesomewm" align="right"> <img src="https://img.shields.io/badge/ARCHLINUX-blue?style=for-the-badge&logo=archlinux" align="right">
Oh uh, hey? Caught me off guard (I'm prob'ly sleeping)

I heard you were looking for some inspiration for your dots, too! Or maybe just to steal mine.

Btw I won't sue you or anything if you violate this repo's license.

| thing      | software                                                                                  |
|------------|-------------------------------------------------------------------------------------------|
| wm         | ![awesome-git](https://awesomewm.org)                                                     |
| gtk        | ![cutefish-light + awesthetic-dark](https://github.com/saimoomedits/dotfiles/extras/themes) |
| compositor | ![picom-git](https://github.com/yshui/picom)                                              |
| browser    | ![firefox](https://firefox.com)                                                             |
| bar        | ![wibar](https://github.com/awesomeWM/awesome/blob/master/lib/awful/wibar.lua)            |
| music      | ![mpd + ncmpcpp](https://www.musicpd.org/)                                                |
| distro     | ![arch](archlinux.org)                                                                    |

## <samp>Install & Setup</samp>
**⚠ FOR USE ON ARCH-BASED ONLY!!! ⚠**
<br>
**Install `yay` before this**
<br>
**I _reccomend_ you install and configure `doas` before this**

**1. Update; Install packages**
```
yay -Syu
yay -S xorg xorg-server xorg-apps
yay -S awesome-git picom-git firefox mpd mpc ncmpcpp mpdris2 nerd-fonts-git material-icons-git noto-fonts-emoji alacritty thunar thunar-archive-plugin file-roller galculator lxappearance light neovim code font-manager fish starship gimp inkscape obsidian rofi libreoffice reflector pulseaudio cava xdg-desktop-portal-gtk feh
```
**2. Clone this repo and cd into it**
```
cd
git clone https://github.com/oreo-zip/dotfiles.git oreo-dots
cd oreo-dots
```
**3. Backup configs (Optional)**
```
mkdir ~/.backup_config
cp ~/.config/* ~/.backup_config/
cp ~/.mpd ~/.backup_config/
cp ~/.xinitrc ~/.backup_config/
cp ~/.ncmpcpp ~/.backup_config/
```
**4. Make directorys copy files**
```
mkdir ~/.config
mkdir ~/.mpd
mkdir ~/.ncmpcpp
cp config/* ~/.config/
cp extras/mpd/* ~/.mpd/
cp extras/themes/gtk/* ~/.themes
cp extras/xinitrc ~/.xinitrc
```

## <samp>Thanks</samp>
**To all these lovely people:**
- ![Harry](https://github.com/saimoomedits) - for some code ;)
- ![Elena](https://github.com/elenapan) - for some inspiration
- ![Gavin (Me)](https://github.com/oreo-zip) - yes
- ![Linus](https://github.com/torvalds) - for linux

**To all these services**
- ![ChatGPT](https://chat.openai.com) - for some other code
- ![YOU.com](https://you.com) - for code I fed into ChatGPT ;)
- ![GitHub](https://github.com) - what do you think

***And to my Dad, who reviews my work and finds all the pros and cons.***
