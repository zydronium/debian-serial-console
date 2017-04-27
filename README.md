debian-serial-console
=====================

Install:

use "isolinux/isolinux.cfg" instead of default shipped

When installing debian, use custom boot command with "console=ttyS0,9600n8" added to it after VGA

=====================

after install:

use: "/etc/default/grub" instead of default shipped

then execute: update-grub