# linux-fixes
##error: GPGME error: No data
sudo rm -rf /etc/pacman.d/gnupg /var/lib/pacman/sync
sudo pacman-key --init 
sudo pacman -Syyu
