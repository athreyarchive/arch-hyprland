BASE (during base system install)
- kernel: base linux linux-firmware
- shell: bash/zsh
- bootloader: grub efibootmgr
- text-editor: nano/neovim
- sudo: sudo
- git: git
- network manager: networkmanager

- intel cpu drivers: intel-ucode
- nvidia gpu drivers: nvidia/nvidia-open/mesa nvidia-utils opencl-nvidia libva-nvidia-driver

DESKTOP ENVIRONMENT (window-manager & system utilities)
- aur helper: paru
- window manager: hyprland xdg-desktop-portal-hyprland egl-wayland qt5-wayland qt6-wayland 
- login manager: sddm
- app launcher: wofi
- taskbar: waybar
- terminal: alacritty/kitty
- file manager: thunar gvfs thunar-volman
- image viewer:
- video/audio player: mpv
- screenshot tool: grim+slurp/hyprshot
- screen recorder: obs-studio
- clipboard manager: copyq

- firewall: 
- system monitors: fastfetch, btop, fancontrol-gui
- audio control: pipewire wireplumber pipewire-pulse pipewire-audio pipewire-jack pipewire-alsa
- brightness control: brightnessctl
- media control: 
- authentication daemon: polkit-kde-agent
- notification daemon: mako
- idle daemon: hypridle

UI
- font:
- color schemes: pywall16

PERSONAL APPLICATIONS
- cli stuff: ytdlp, cbonsai, cmatrix, cowsay
- wallpapers: swww+waypaper
- browsers: floorp, chromium
- music player: 
- notes: obsidian
- cloud storage: pcloud-drive
- file sharing: localsend-bin
- vpn: protonvpn
- torrenter: qbittorent
- video editor: davinci-resolve
- audio editor: audacity
- games: steam, heroic-games-launcher-bin, prismlauncher
- peripheral manager: 
