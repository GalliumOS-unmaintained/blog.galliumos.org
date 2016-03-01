---
layout: post
title:  "GalliumOS 1.0beta2 Announcement"
date:   2016-02-09 12:00:00 -0600
author: "reynhout"
---
GalliumOS is a fast and lightweight Linux distro made for Chromebooks and Chromeboxes. GalliumOS delivers a complete Linux environment with full hardware support, a carefully tuned kernel, and a full-featured and attractive desktop.

Release 1.0beta2 is ready for testing. Thank you for your support and reports on our last release, we look forward to more of your feedback!

## What's New Since Beta1?

- Full support for Bay Trail Chromebooks
- Updated kernel, including bugfixes
- Touchpad improvements
  - Fix for not being able to move certain windows (e.g., Chrome, Steam)
  - Smoother and faster motion
- External mouse improvements
- Audio improvements
- Wifi performance/reliability improvements
- Battery life improvements
- New login manager: LXDM is more flexible and actively developed
- New keyboard mappings: choose media keys or F-keys, and how to switch
- Added support for keyboard backlight control on equipped models
- New packages
  - GDebi package installer
  - HexChat IRC client
- Improved application defaults
- Bugfixes and tying up of loose ends

**Thank You!** to the donors who made it possible for us to purchase a Bay Trail Chromebook for testing! [https://galliumos.org/donate.html](https://galliumos.org/donate.html)

## Installing

GalliumOS installation images can be downloaded from [https://galliumos.org/download.html](https://galliumos.org/download.html). You can preview GalliumOS in a "live boot" from the same image without installing. The GalliumOS wiki has full instructions: [https://wiki.galliumos.org/Installing](https://wiki.galliumos.org/Installing).

GalliumOS can also be installed in a dual-boot configuration alongside ChromeOS using chrx: [https://chrx.org/](https://chrx.org/).

## Upgrading

If you already have an earlier version of GalliumOS installed, you should update now.

From the command line:

```
sudo apt-get update
sudo apt-get dist-upgrade
sudo reboot
```

You can ignore warnings about packages being downgraded. We changed the way we construct version strings, so this warning should not appear in future upgrades.

You might get an option to select between "SLiM" and "LXDM". Choose "LXDM".

We are investigating lightweight graphical software updater options for inclusion in future releases.

## Known Issues

- Bay Trail audio occasionally does not restart after sleep: [https://github.com/GalliumOS/galliumos-distro/issues/110](https://github.com/GalliumOS/galliumos-distro/issues/110)
- Google Pixel 2015 (SAMUS) audio in/out not working: [https://github.com/GalliumOS/galliumos-distro/issues/100](https://github.com/GalliumOS/galliumos-distro/issues/100)
- HDMI audio not auto-switching on Acer C720: [https://github.com/GalliumOS/galliumos-distro/issues/101](https://github.com/GalliumOS/galliumos-distro/issues/101)
- UI elements not scaled for very HiDPI Google Pixel displays: [https://github.com/GalliumOS/galliumos-distro/issues/44](https://github.com/GalliumOS/galliumos-distro/issues/44)

## Resources

- Chromebook/Chromebox model support: [https://wiki.galliumos.org/Hardware_Compatibility](https://wiki.galliumos.org/Hardware_Compatibility)
- Downloads: [https://galliumos.org/download.html](https://galliumos.org/download.html)
- Installation instructions: [https://wiki.galliumos.org/Installing](https://wiki.galliumos.org/Installing)
- FAQ: [https://wiki.galliumos.org/FAQ](https://wiki.galliumos.org/Installing)
- Reddit forum: [https://www.reddit.com/r/GalliumOS/](https://www.reddit.com/r/GalliumOS/)
- IRC: [https://kiwiirc.com/client/irc.freenode.net#galliumos](https://kiwiirc.com/client/irc.freenode.net#galliumos)
- Bug reports and feature requests: [https://github.com/GalliumOS/galliumos-distro/issues](https://github.com/GalliumOS/galliumos-distro/issues)
