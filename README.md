# Arch:
FONTS: 
``` 
sudo pacman -S gsfonts sdl_ttf ttf-bitstream-vera ttf-dejavu ttf-liberation xorg-fonts-type1
```
```
sudo pacman -S ttf-fira-code ttf-fira-sans ttf-fira-mono ttf-font-awesome ttf-joypixels ttf-nerd-fonts-symbols ttf-nerd-fonts-symbols-common noto-fonts noto-fonts-cjk
```
Window Manager:
```
sudo pacman -S i3 alacritty polybar lxappearance materia-gtk-theme lxsession thunar nitrogen sxiv python-psutil papirus-icon-theme arandr dunst picom rofi
```
Python CPU script: 
```
pipx install pustil
```
Nvidia Driver:
```
sudo pacman -S nvidia-dkms nvidia-utils lib32-nvidia-utils nvidia-settings vulkan-icd-loader lib32-vulkan-icd-loader
```
AMD Driver:
```
sudo pacman -S xf86-video-amdgpu vulkan-radeon libva-mesa-driver mesa-vdpau lib32-vulkan-radeon vulkan-icd-loader lib32-vulkan-icd-loader
```
AUR: 
```
yay -S autotiling catppuccin-gtk-theme-frappe mcmojave-cursors matcha-gtk-theme
```
```
paru -S autotiling catppuccin-gtk-theme-frappe mcmojave-cursors matcha-gtk-theme
```

# Fedora: 
RPM FUSION: 
```
sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
```
FONTS: 
```
sudo dnf install fontawesome-fonts-all urw-base35-fonts SDL_ttf bitstream-vera-fonts-all dejavu-fonts-all liberation-fonts xorg-x11-fonts-Type1 mozilla-fira-mono-fonts mozilla-fira-fonts-common mozilla-fira-sans-fonts fira-code-fonts google-noto-cjk-fonts google-noto-fonts-common google-noto-sans-cjk-vf-fonts google-noto-serif-cjk-vf-fonts
```
WINDOW MANAGER: 
```
sudo dnf install XXX (coming soon) 
```
Python CPU:
```
pip3 install psutil
```
AMD DRIVER: 
```
sudo dnf install XXX (coming soon)
```
NVIDIA DRIVER
```
sudo dnf install XXX (coming soon)
```
