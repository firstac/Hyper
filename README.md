# hyprland

Collection of dot config files for [`hyprland`](https://hyprland.org/) with a simple install script for a fresh Arch Linux with [`yay` (or whatever AUR helper you have)](https://wiki.archlinux.org/title/AUR_helpers).

You can grab the config files and install packages by hand with this command:

```sh
yay -S hyprland-bin kitty waybar-hyprland \
    swaybg swaylock-effects wofi wlogout mako thunar \
    ttf-jetbrains-mono-nerd noto-fonts-emoji \
    polkit-gnome python-requests starship \
    swappy grim slurp pamixer brightnessctl gvfs \
    bluez bluez-utils lxappearance xfce4-settings \
    dracula-gtk-theme dracula-icons-git xdg-desktop-portal-hyprland-git
```

Or you can use the attached script "set-hypr" to install everything for you.
