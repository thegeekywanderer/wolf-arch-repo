# wolf-arch-repo
This is a repository for some Arch packages maintained by me. I plan to continue adding more packages to it as I venture deeper into the linux world.

## Add the repository [Installation]
To add this repository in pacman you need to add the following lines in the pacman.conf file. Location - `/etc/pacman.conf`
```
[wolf-arch-repo]
SigLevel = Optional DatabaseOptional
Server = https://github.com/wolf-hash/$repo/raw/master/$arch
```

Sync the repositories and update system - 
```sudo pacman -Syyu```

To install any package - 
```
sudo pacman -S package-name
```

Current Packages in this Repository -
- kwincorners-git
