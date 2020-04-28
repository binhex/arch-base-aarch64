**Application**

[Arch Linux](https://www.archlinux.org/)

**Description**

Arch Linux is an independently developed, i686/x86-64 general purpose GNU/Linux distribution versatile enough to suit any role. Development focuses on simplicity, minimalism, and code elegance.

**Build notes**

Arch Linux ARM 64 bit base image built from "scratch". This image is set to a snapshot by using the http://tardis.tiny-vps.com website for package updates, this is required to reduce image size by preventing rolling updates to packages.

**Notes**

This image includes Tini (https://github.com/krallin/tini) to ensure a clean shutdown and to correctly reap processes, Supervisor (http://supervisord.org/) is also installed to help monitor and run child processes.

If you appreciate my work, then please consider buying me a beer  :D

[![PayPal donation](https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MM5E27UX6AUU4)

[Documentation](https://github.com/binhex/documentation) | [Support Forum](http://lime-technology.com/forum/index.php?topic=45811.0)