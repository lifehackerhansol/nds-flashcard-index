---
title: Flashcard Firmwares
---

TWiLight Menu++ is an all-in-one customizable menu for a variety different applications. We'll be setting it up to launch homebrew that cannot directly be launched via your kernel and for emulator usage.
 - For the iPlayer, Games'N'Music and other flashcarts only able to launch homebrew, you can also use the pre-installed B4DS to launch retail ROMs.

## Installation
### Section I -- SD Card Setup

1. Download the latest version of [TWiLight Menu++](https://github.com/DS-Homebrew/TWiLightMenu/releases/latest)
2. Extract the `_nds` folder to the root of your flashcart's microSD card.
  - **Not** the one located in `Flashcard users`
3. Delete `_nds\TWiLightMenu\widescreen`. Cheat codes from `.bin` files aren't applied on B4DS.

### Section II -- Flashcart Specific setups
#### R4iDSN/R4 Ultra/R4i Gold RTS & SuperCard DSTWO

These flashcarts are able to boot Nintendo DS ROMs using their flashcart kernel as opposed to the rather low compatibility of B4DS.

1. Delete `GBARunner2_arm7dldi_3ds.nds`, `GBARunner2_arm7dldi_dsi.nds`, `nds-bootstrap-nightly.nds` & `nds-bootstrap-release.nds` from the `_nds` folder.
2. If there is no `BOOT.NDS` found on the flashcart's microSD card's root, copy it from `Flashcard users`.
3. Extract the `_nds` folder from `Flashcard users` to the root of your flashcart's microSD card.
  - If asked, merge the directories.
4. Download the pack for your flashcard:

- [R4iDSN/R4 Ultra/R4i Gold RTS](https://www.dropbox.com/s/j8nquh073k9y0h7/DS%20Game%20Forwarder%20pack%20%28R4iDSN%2C%20R4i%20Gold%20RTS%29.7z?dl=1)
- [SuperCard DSTWO](https://www.dropbox.com/s/pyyg0vq8b0nmhqd/DS%20Game%20Forwarder%20pack%20%28SC%20DSTWO%29.7z?dl=1)

5. Extract the contents of `For Slot-1 microSD` to the root of the flashcart's microSD card.
6. If you'd like to automatically launch into TWiLight Menu++ when you launch your Slot-1 Flashcart, extract the contents of `Flashcard users/Autoboot/(your card)` to the root of your flashcart's microSD card.
7. Go to the TWiLight Menu++ settings application and set "Use nds-bootstrap" to "No".

#### CycloDS iEvolution

This flashcart is able to use the Nintendo DSi version of nds-bootstrap as opposed to B4DS.

- Extract `BOOT_cyclodsi.nds`, rename it to `BOOT.NDS` and place it at the root of your SD card.

#### Other flashcarts

1. Delete `GBARunner2_arm7dldi_3ds.nds`, `GBARunner2_arm7dldi_dsi.nds`, `nds-bootstrap-nightly.nds` & `nds-bootstrap-release.nds` from the `_nds` folder.
2. If there is no `BOOT.NDS` found on the flashcart's microSD card's root, copy it from `Flashcard users`.
3. Extract the `_nds` folder from `Flashcard users` to the root of your flashcart's microSD card.
  - If asked, merge the directories.

### Section III - Configuration

Most of this boils down to personal preference, so change the configuration per your likings.
The way to access the TWiLight Menu++ settings varies between your configuration.

- DS Classic Menu: Hit the button on the very bottom
- Nintendo DSi/SEGA Saturn/Homebrew Launcher themes using SELECT Menu: Hit SELECT, then launch the Settings Applet (use the D-PAD to highlight options)
- Nintendo DSi/SEGA Saturn/Homebrew Launcher themes not using SELECT Menu: Hitting SELECT will bring you to the DS Classic Menu
- Nintendo 3DS theme: Use the touch screen to touch the wrench
- R4 Original theme: Hit START (if you're in the file browser), then hit SELECT
- Acekard theme: Go out of the file browser (hit B a bunch), then scroll to find and launch the Settings Applet

From there, you will get a few options of things you could do.