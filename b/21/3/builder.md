---
layout: default
title: GNOME Builder is better than I thought!
description: Jump the hoops to Linux GTK development with Builder.
---

[linux_kettle](/) / **GNOME Builder is better than I thought!**

# What is GNOME Builder?
GNOME Builder, or just Builder, is an IDE (integrated development environment) for Linux and other Unix-y OSes, that specialises in the field of GTK development. It is a great platform for beginners and pros alike to make nice apps, and unlike many of its alternatives has a lot of features to save you time.

# What am I comparing this to?
I used to use Visual Studio for programming back in my Windows days. It did what I needed it to, but it was complicating to use and very s       l      o     w. Then, when I transferred to Linux (a move I don't regret), I used VS Code with C# for a while, but it doesn't work great with Linux, and my options for graphical apps were very limited. Then when I switched from Ubuntu to Arch Linux in December, I decided to try out Qt Creator. Qt Creator was great, it worked with Python, which is a language I came to be quite familiar with, and the built-in Designer is awesome. The only trouble was this: portability. Building an app in Qt Creator resulted in a bunch of files that had to be kept together, and all sorts of problems with dependencies on Python libraries. It worked though, and that was great.

# Then there's Builder.

When I re-installed Arch in January, I switched from Cinnamon to GNOME as my desktop environment. And I took a look at two apps, Glade and Builder, that I liked the look of. So I installed them (I'd say you can probably see why I re-install Linux on a monthly basis now), and I opened Builder. I noticed a programming language in the list that I (somehow) hadn't come across before called Vala. I decided to create a blank project, and I liked what I saw. Builder had done all of the licence stuff for me (not so significant for me as I code for a hobby, but still nice), and made a working Hello World GTK app.

*If you're curious, you can see [what I turned it into](/randomwords.tar.xz). The tarball is a bit of a mess.*

Anyway, the combination of Glade and Builder and the advantages of GTK (faster startup, less dependency hell, one small file, Vala compiles to C which is dominant in the Linux world) meant that I could spend more time doing the whole design aspect of things and it looks better. Qt Creator gets about 7 points out of ten for presentation, Builder gets 10. Unless you're on KDE, then it's the opposite.

# How to get Builder

If you don't have Flatpak installed, you really should get it - you're missing out on so much fun.

If you do, Builder is [here](https://flathub.org/apps/details/org.gnome.Builder) and Glade is [here](https://flathub.org/apps/details/org.gnome.Glade).



Thanks for reading my article, and have a good week!