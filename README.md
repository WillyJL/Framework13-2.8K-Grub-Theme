# Framework 13 Grub Theme
A Grub theme created for the Framework 13 laptop, using them Framework logo in the correct position on the screen.

Place the theme in the correct theme folder of your Grub configuration. Probably in: /boot/grub/themes/

Add the following line to the /etc/default/grub file and run update-grub as root:
```
GRUB_THEME="/boot/grub/themes/framework_black/theme.txt"
GRUB_GFXMODE=2256x1504
```
