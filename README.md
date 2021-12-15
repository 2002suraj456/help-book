# help-book

## Keyboard conf
```sh
localectl set-x11-keymap us,us pc105 ,colemak_dh grp:ctrls_toggle,ctrl:swapcaps
localectl set-x11-keymap us,us pc105 ,colemak_dh grp:ctrls_toggle,ctrl:swap_lalt_lctl_lwin
localectl set-x11-keymap us,us pc105 ,colemak_dh grp:ctrls_toggle,ctrl:swap_lalt_lctl_lwin,caps:escape
localectl set-x11-keymap us,us pc105 ,colemak_dh grp:ctrls_toggle,ctrl:swap_lwin_lctl,caps:escape_shifted_capslock
```
## KVM
```
sudo pacman -S virt-manager qemu vde2 ebtables dnsmasq bridge-utils openbsd-netcat
```
