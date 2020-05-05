---
title: Time Bombs
---

A time bomb is an expiration date for the flashcart kernel. It's a tactic used by flashcart manufacturers to force people to buy another flashcart when they see the "expiration" screen. This can be found in most flashcarts where they have a year in the name (such as `R4i SDHC Dual-Core 2018`).

## Instructions
### Section I - Determining whether you have one.

1. Go to the settings application of your console.
2. Set your date to the latest value possible.
3. Launch the flashcart.

If it shows an expired screen, you have a flashcart where the kernel has a time bomb.

### Section II - Working around it
Luckily though, it does not set a flag anywhere and it's only in the kernel and not the flashcart firmware. This gives us two options to work around the time bomb.
- Since it relies on the system clock, you could set back the date. This will break any game that uses your system clock, but it will allow you to use the current kernel.
- Since it relies on the kernel and not the firmware, you could switch to an alternative kernel. There are two options available:
  - [YSmenu](https://gbatemp.net/threads/retrogamefan-updates-releases.267243/) -- The menu is quite ugly and only displays `.nds` files, but it has far better game support, cheat support and no memory pak requirement.
  - [TWiLight Menu++](twilight) with B4DS -- This is useful if you'd like to have all your ROMs in the same menu that you could launch NES, GBA and other console titles too. However, it does require a Memory Expansion Pak for extended game compatibility and does not support cheats.

We recommend YSMenu due to the higher compatibility, cheats and lack of need for a Memory Expansion Pak. If you want to setup YSMenu, DeadSkullzJr has made a [Dropbox repo](https://www.dropbox.com/sh/egadrhxj8gimu5t/AACv2KqWmeXEHkxoYRluobxha?dl=0) with all the primary boot kernels set up for your flashcart. All it requires is a drag and drop to your SD card root and you have completed.
  - You could still lanuch into TWiLight Menu++ for an all-in-one menu for emulators, but you can't launch into YSMenu from TWiLight Menu++.