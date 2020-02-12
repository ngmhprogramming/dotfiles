# Steps to take after reinstalling Manjaro for like, the tenth time
## 1. Install Packages (packages.md)
## 2. GET SOUND BACK
```
/etc/modprobe.d/alsa-base.conf
options snd_pch index=0
options snd_hda_intel index=1
```
## 3. Update pacman
```
sudo pacman-mirrors -f0
sudo pacman -Syyuu
```

## 4. Fix Time
```
sudo pacman -S ntp
sudo timedatectl set-ntp true
```
## 5. Terminal Changes
```
compton smth
```
## 6. Warnings
### DO NOT INSTALL SUBLIME UNLESS YOU WANT TO DIE
