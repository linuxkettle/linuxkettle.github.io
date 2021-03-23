---
layout: default
title: Fedora 33 - Well worth a try!
description: I didn't like Fedora 32, but this release is great!
---

[linux_kettle](/) / **Fedora 33: Well worth a try!**

You might be surprised that this article was not in any way endorsed by Red Hat or the Fedora community. This is 100% my honest opinion.

Let me get straight into it. In 2020, when looking for a good Ubuntu replacement, I stumbled across Fedora 32. I liked the idea of it, so I put it on a USB and had a good play around with it.

I had a few issues with getting it to boot, I had to edit the grub configuration among other things, and Plymouth was well and truly broken. When the live desktop booted, I opened Firefox and a terminal and went to install some games to see how good the performance was. But when I opened a tab in Firefox, it crashed. So I switched to the terminal and found I couldn't run any commands because of I/O errors. In a nutshell, it didn't work. Also, that release of GNOME was not in my opinion great, and I didn't like the UI/UX side of things either. So I rebooted and tried Linux Mint, and Elementary after that.

Then yesterday (how did it take that long?), I found out about Fedora Silverblue, the immutable OS designed with OSTree and with container use in mind. Unfortunately, the boot process was very hit and miss, and four out of five times it wouldn't boot at all, hanging on the dracut init process. And the installer is not ready for production in my opinion, it's hard to get it to use the EFI partition and `grub2-mkconfig` kept exiting with errors, even though it was fine when I ran it from the console. So I thought about giving Fedora Workstation 33 a try.

I *loved* what I saw. When I booted it, no trouble or anything, it showed the HP logo (I'm still trying to figure out how it does that), with a nice spinning circle. Then when it finished booting, instead of going to a console with the systemd log and sitting there idle for about 10 seconds, the circle went away and there was a nice fade transition into GNOME. The default wallpaper was beautiful, and the installer let me try it out before installing it. I installed [Builder and Glade](/b/21/3/builder) with no trouble, and my games ran smoothly (and this is off a USB on a 5-year-old computer!) And the default selection of apps has something for every task, but isn't bloated and hard to find what you want through (arch was the same, but it was hard to install and I found myself in the console every 20 minutes or so), and no I/O problems the whole time! So, in conclusion, I though "This is a must."

![fedora 33](/assets/fedora.png)

So I installed it. The Anaconda installer was quick and easy to use (even more so than Ubiquity, the Ubuntu one, which is well-known for both), and the post-install setup was a breeze. The GDM transition was still lovely, the whole boot process was smooth and quick, and when I logged in, I still had all of my GNOME extensions and my desktop background (the latter of which I changed to one of the default Fedora ones because I like them), and my apps were all in the same order. Then I opened Software, and to no surprise I saw that I had 52 updates to install (plus all of the OS ones), so I rebooted for that and it was much better than my previous experiences. Instead of needing to open a terminal to update, I just clicked the 'Restart & Update' button in Software, and my computer rebooted, updated, and then rebooted again. And if that's not enough, when updating I saw a progress bar and the HP logo and the Fedora logo, along with a nice message saying 'Installing Updates' in a big font.

Also, if you're a Windows user, you can try the Cinnamon Spin, which has a nice familiar layout that mimics the design of Windows by default, but gives you much more customisation options.

In conclusion, if you haven't tried Fedora 33 yet, you really should. You can get it at <https://getfedora.org>.
