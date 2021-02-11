Dotfiles that i use for both my laptop and desktop.
This is currently configured for Arch Linux and uses the dwm window manager with dwmblocks for status bar info.

For a quick Install please install the following packages:

> paru -S firefox neovim ranger dragon-drag-and-drop zsh terminus-font adobe-source-han-sans-jp-fonts ttf-joypixels otf-san-francisco-pro kitty blueman ncmpcpp dunst i3lock-color-git xss-lock ibus ibus-mozc libxft-bgra lxappearance lxrandr maim mpc mpd mpv neofetch throttled nitrogen pcmanfm qbittorrent rofi thunderbird tlp tlpui ueberzug zathura youtube-dl lightdm picom terminus-font-ttf xdg-utils-mimeo feh sxiv code bpytop htop pavucontrol xbacklight

Enable the following services:

> systemctl --user enable mpd

> systemctl --user enable mpd-notification

> systemctl enable tlp

> systemctl enable throttled

> systemctl enable bluetooth

> systemctl enable sshd

> systemctl enable lightdm

