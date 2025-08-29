# Framework 13 (2.8K display) Grub Theme
A Grub theme created for the Framework 13 laptop (2.8K display), using them Framework logo in the correct position on the screen.

Place the theme in the correct theme folder of your Grub configuration. Probably in: /boot/grub/themes/

Add the following line to the `/etc/default/grub` file and run `sudo grub-mkconfig -o /boot/grub/grub.cfg`:
```
GRUB_THEME="/boot/grub/themes/Framework13-2.8K-Grub-Theme/theme.txt"
GRUB_GFXMODE=2880x1920
```
