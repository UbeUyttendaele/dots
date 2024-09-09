sudo pacman -S --needed base-devel

git clone https://aur.archlinux.org/paru.git

makepkg -si

paru -S - < pkglist_aur.txt
