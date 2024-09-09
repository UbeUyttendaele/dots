sudo pacman -S --needed base-devel
g
it clone https://aur.archlinux.org/paru.git

makepkg -si

paru -S - < pkglist_aur.txt
