---
layout: post
title:  "Don't Install Ubuntu Software Center"
date:   2016-02-17 12:00:00 -0600
author: "ColtonDRG"
---
Hello. It has come to my attention that people are installing Ubuntu Software Center. Please don't. Seriously, just don't do it.

What's wrong with Ubuntu Software Center? Well, for starters, it's a terrible piece of software that interfaces with apt very poorly. I have had Ubuntu Software Center break more systems than I can count on both hands. That's a lot of systems. It crashes and freezes and breaks your system. Also, it has dependencies, and not innocent dependencies. Ubuntu Software Center depends on Software Updater, which is basically a nag tool that runs in the background (and not efficiently) and nags you to update your system. We do believe that update nags are useful in reminding users to keep their system up to date, but this specific one is incredibly inefficient, and it WILL waste your resources. Devices with the Software Updater installed will see high CPU usage when idle, the CPU heating up seemingly for no reason, lag spikes, CPU usage spikes, and many more ill effects. And finally, the icing on the cake is an annoying nag to update to Ubuntu 15.10. If you have the Software Updater installed, it can and WILL nag you to upgrade to Ubuntu 15.10, which WILL completely destroy your GalliumOS install and you'll have to start over should you accept the upgrade.

In conclusion, Ubuntu Software Center should not be installed on any GalliumOS system. Say no to Ubuntu Software Center. If you need an alternative for user friendly software installing and updating, consider Lubuntu Software Center. It's pretty nice.

Update: If you've installed the software center, run the following command to remove it and the other garbage.

`sudo apt-get purge software-center update-manager-core ubuntu-release-upgrader-core`

This has been a GalliumOS user courtesy PSA by ColtonDRG
