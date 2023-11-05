# ultrakill-grub

Simple Ultrakill GRUB theme

# Install process (requires root privileges):

1. Copy repo containing folder to `/boot/grub2/themes` with:
    `cp /path/to/repo/ultrakill-grub/uk-theme-folder /boot/grub2/themes/uk-theme-folder -r`
2. In textual file `/etc/default/grub` append next line:
    `GRUB_THEME="boot/grub2/themes/uk-theme-folder/theme.txt"`
3. Depending on your operating system write next:
    Fedora (UEFI): `sudo grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg`
    Others: check out wikis for your OS

> Note: Check if `GRUB_DEFAULT` is set to `saved`, `GRUB_SAVEDEFAULT` to `true`, `GRUB_TIMEOUT_STYLE` to `"menu"`, `GRUB_ENABLE_BLSCFG` to `true`, `GRUB_TERMINAL_OUTPUT` commented out and `GRUB_GFXMODE` set to preffered resolution using `(width)x(height)` (without brackets).

# License

Free to use, edit, or share with friends, but not commercialize because I have no rights to use original art (it's just downloaded from Google Images).
