# ultrakill-grub

Simple Ultrakill GRUB theme

# Install process:

1. Copy repo containing folder to `/boot/grub2/themes`
2. In textual file `/etc/default/grub` append next line:
    `GRUB_THEME="boot/grub2/themes/uk-theme-folder/theme.txt"`
3. Depending on your operating system write next:
    Fedora: `sudo grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg`
    Others: check out wikis for your OS
