# frankmuellerxyz dwm build config

ModKey is the Windows Key (Mod4Mask)

## Binds:
+ MODKEY + d 			= dmenu
+ MODKEY + Return 	    = terminal
+ MODKEY + Shift + b 	= browser
+ MODKEY + Shift + i	= browser incognito

+ MODKEY + Shift + q 	= kill window
+ MODKEY + Shift + e 	= exit dwm

+ volume controls with x86 keys (up,down,mute)
+ multimedia controls with x86 keys using playerctl

# Dependencies

```sh
sudo pacman -S alacritty dmenu feh firefox network-manager-applet pamixer picom playerctl ttf-hack xorg
```
## AUR

```sh
thorium-browser-bin
```


## gdm installation

+ Copy gdm/dwm.desktop to /usr/share/xsessions/
+ Copy gdm/dwm-start to   /usr/local/bin/
+ Change permissions to root and dwm-start must be executable
