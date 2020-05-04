---
title: TimeBombs
---

A time bomb is essentially a piece of code in the kernel (not firmware) that some (most notably in the R4 lineup) flashcards uses that acts as an expiration date for that card. This concept is in place to force people to buy another flashcart whenever they are met with the "expiration" screen (as past that date, the kernel will no longer work).

## Instructions
### Section I - Determining whether you have one.

1. Go to the settings application of your console.
2. Set your date to the latest value possible.
3. Launch the flashcart.

If it shows an expired screen, you have a timebomb on your hands. There are two ways to work around this:

- Setting back the date. This will break any game that uses your system clock.
- Switching to an alternative kernel. This is what we will be doing here. You have two options available for an alternative game loader.
  - [TWiLight Menu++](twilight) with B4DS -- This is useful for that all-in-one menu concept that we setup for emulators before, but you might need a Memory Expansion Pak in order to use it.
  - [YSmenu](https://gbatemp.net/threads/retrogamefan-updates-releases.267243/) -- The menu is quite ugly and only displays `.nds` files, but it has far better game support and does not require a Memory Expansion Pak.