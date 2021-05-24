---
title: Flashcard Firmwares
---

{% include toc title="List of Firmwares" %}

If your flashcard does not have a website link on its front sticker, you will need to find your files in [Identifying Flashcard without Website](setup-nolink) instead.
{: .notice--danger}

If the System File listed is YSMenu, you will need to follow the guide for installing [YSMenu](ysmenu).
{: .notice--info}

This page will attempt to provide a comprehensive guide to which firmware, kernel or system files you need to download for your flashcard.
We prioritize updated operating systems over the official and unsupported ones. For example, we would rather direct users to Wood R4 rather than the original R4 system files which haven't been updated for years.

The list should be grouped by brand and sorted alphabetically, all listing the website links. Use the Table of Contents box on the right/above this text to navigate this list. It should be titled "List of Firmwares"

Once you've grabbed your System Files, go to [the TWiLight Menu++ setup page](twilight).
{: .notice-info}

- "Clone" flashcards are copies of original cards. Example: the M3 Simply is a clone of the original R4 DS. Systems that run on the R4 DS run the same way on the M3 Simply.
- A "fake" flashcard is a device that steals the name of an original card, but that is nothing like it. Example: the R4 Upgrade is a fake R4 DS, it is not compatible with any of the system files available for the R4 DS (a fake card uses its own separate system files).
- A card can be both a clone and a fake. Most fake R4 cards are clones of the Acekard 2i and DSTT.
- Keep in mind that every R4 card (except for the original) is indeed a clone/fake, and [that (almost) all R4i-SDHC/R4iSDHC carts are the same.](https://gbatemp.net/threads/proof-that-almost-all-r4i-sdhc-r4isdhc-carts-are-literally-the-same-carts.514539/)

--------------

# Ace3DS (ace3ds.com)
- [Official Website](http://www.ace3ds.com/)

## Ace3DS
<img src="/assets/images/ace3ds.jpg"  width="120" height="120">
- DSi/3DS Compatible: Yes
- System files: [YSMenu](ysmenu)

## Ace3DS+ (Ace3DS X)
<img src="/assets/images/ace3dsplus.jpg"  width="120" height="120">
<img src="/assets/images/ace3dsx.jpg"  width="120" height="120">
- DSi/3DS Compatible: Yes
- System files:[Wood R4](https://github.com/lifehackerhansol/flashcard-archive/blob/master/ace3ds.com/Ace3DS+_Wood_R4_1.62.7z?raw=true)
- NTRBoot compatible (Ace3DS X has a hardware switch to enable NTRBoot)

--------------

# Acekard (acekard.com)
This manufacturer is no longer around. You will no longer get official support from the Acekard team.
- [Official website (archived)](https://web.archive.org/web/20140209172112/http://www.acekard.com/)

## Acekard (Acekard+)
- System files: [akMenu (English)](https://github.com/lifehackerhansol/flashcard-archive/blob/master/acekard.com/AceKard_(Plus)/AceKard_akMenu_4.07.7z?raw=true)
- DSi compatible: No

## Acekard RPG
<img src="/assets/images/acekardrpg.jpg"  width="120" height="120">
- System files:[Wood R4](https://github.com/lifehackerhansol/flashcard-archive/blob/master/AceKard_RPG/AceKard_RPG_Wood_R4_1.62?raw=true)
- DSi compatible: No

## Acekard 2 (2.1)
<img src="/assets/images/acekard21.jpg"  width="120" height="120">
- System files: [AKAIO](https://github.com/lifehackerhansol/flashcard-archive/blob/master/acekard.com/AceKard_2_2.1/AKAIO_1.9.0.7z?raw=true)
- DSi compatible: No

## Acekard 2i
<img src="/assets/images/acekard2i.jpg"  width="120" height="120">
- System files: [AKAIO](https://github.com/lifehackerhansol/flashcard-archive/blob/master/acekard.com/AceKard_2i/AKAIO_1.9.0.7z?raw=true)
- DSi compatible: Up to (and including) v1.4.4
- 3DS compatible: Up to (and including) v4.3.0
- NTRBoot Compatible.
- [Firmware upgrade](https://github.com/lifehackerhansol/flashcard-archive/blob/master/AceKard_2i/AceKard_2i_3DS_Firmware_Update.7z?raw=true)
  - Instructions
    - If you use a DS Lite, copy and run `dsl.nds`.     
    - If you use a DSi under 1.4, copy and run `dsi.nds`.

--------------

# DSTT (ndstt.com) (ndstt.net)
This manufacturer is no longer around. You will no longer get official support from the DSTT team.
- [Official website (archived)](https://web.archive.org/web/20150316073517/http://www.ndstt.net/)

## DSTT/DSTTi
<img src="/assets/images/dstt.jpg"  width="120" height="120">
<img src="/assets/images/dstti.jpg"  width="120" height="120">
- DSi compatible: (DSTTi only, up to 1.4.1)
- 3DS compatible: No
- Only models with [certain flash chips](https://gist.github.com/yuukieve/6b48f1bb8dd15136403c15c39fafdb42) are compatible with ntrboot
- System files: [YSMenu](ysmenu)

--------------

The following are 1:1 (direct) clones of the DSTT or DSTTi.

## DSTT Advance (dstt-adv.com)
- [Official Website (archived)](http://web.archive.org/web/20121014090312/http://www.dstt-adv.com/)
- This is a fake/clone card
- System files: [YSMenu](ysmenu)

## DSTTi Gold (ndstti.cn)
- [Official Website (archived)](http://web.archive.org/web/20111216144004/http://www.ndstti.cn/)
- This is a fake/clone card
- System files: [YSMenu](ysmenu)

<!--
# EZ-Flash (ezflash.cn)

## EZ-Flash V (Plus)
- [Official website](http://www.ezflash.cn/)
- [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/23783-2.0RC20.zip?raw=true)
- DSi compatible: No

## EZ-Flash Vi
- [Official website](http://www.ezflash.cn)
- [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/28259-3.0%20OB8.rar?raw=true)
- [Firmware upgrade](https://github.com/DS-Homebrew/flashcard-archive/blob/master/26992-V108a.rar?raw=true)
- DSi compatible: Yes

# G6 DS
## G6 DS Real (gbalpha.com)
- [Official website](http://web.archive.org/web/20140102193632/http://g6flash.com/)
- [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/23808-G6_M3DS-R_M74.zip?raw=true)
- DSi compatible: No

# iTouch (itouchds.com)
## iTouch2
- [Official website](https://web.archive.org/web/20101007203705/http://www.itouchds.com/)
- [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/18856-iTouch_loader_v3.8e.zip?raw=true)
- DSi compatible: Up to (and including) v1.4.0

-->
--------------

# M3
This manufacturer is no longer around. You will no longer get official support from the M3 team.
- [Official website (archived)](http://web.archive.org/web/20130822202911/http://www.m3adapter.com/)

## M3 DS Real/M3 Perfect (m3adapter.com)
- System files: [YSMenu](ysmenu)
- DSi/3DS compatible: No

## M3i Zero (m3adapter.com)
- System files: [Sakura](https://github.com/lifehackerhansol/flashcard-archive/raw/main/YSMenu/m3adapter.com/M3DS_Sakura_1.49a.7z)
- DSi/3DS compatible: No
- Review: [GBAtemp](https://gbatemp.net/threads/m3i-zero-review.182018/)

## M3 DS Simply (m3adapter.com)
- 1:1 clone of the R4 DS
- [System files](https://github.com/lifehackerhansol/flashcard-archive/blob/master/R4%20(original),%20M3%20Simply/R4DS%20Wood%20R4%201.62.zip?raw=true)
- Review: [GBAtemp](https://gbatemp.net/threads/m3-ds-simply-review.44631/)

<!--
The following are clones of the M3 cards.

## M3 Adaptador (m3adaptador.com)
- System Files: [English](https://github.com/DS-Homebrew/flashcard-archive/blob/master/M3Adaptador_v3.9_English.zip?raw=true)
- Ripoff of the M3

## M3i SDHC (m3isdhc.com)
- [Official website](http://m3isdhc.com/)
- [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/19585-M3iSDHC_v1.4.rar?raw=true)
- DSi Support: Yes

## M3i Upgrade/M3L Upgrade (m3iupgrade.com)
- [Official website](http://m3iupgrade.com/)
- System Files: [English](https://github.com/DS-Homebrew/flashcard-archive/blob/master/19507-m3iupgrade_M3i_v1.45_English.rar?raw=true)

-->
--------------

# R4
The original R4 team went defunct long ago. Because of its high popularity, many manufacturers used its name to make many clones of the same concept.

These are _not_ identical, and they should _not_ be labeled as such. Using kernel files from another R4 may ***brick*** your flashcard.

This is a list of flashcards with a website printed on its label. Any flashcard without a label should be searched for in [Identifying Flashcard without Website](setup-nolink).

<!--
## R4 3DS Upgrade SDHC Dual-Core RTS (2016) (r4-usas.com)
- [Official website (archived)](https://web.archive.org/web/20161008142809/http://www.r4-usas.com/)
- [System files](https://github.com/lifehackerhansol/flashcard-archive/blob/master/r4-usas.com%20R4%203DS%20Upgrade%20SDHC%20Dual-Core%20RTS%20(2016)/R4-usas.com%20R4i%20V3.9b.zip?raw=true)
-->

## R4 III SDHC (r4iiisdhc.com)
- Clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4i DSi XL (r4i-ndsill.com)
- Clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4 King (r4king.com)
- Clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4 Ultra, R4i Ultra (r4ultra.com)
- Clone of the Acekard 2 and 2i
- [Official website](http://www.r4ultra.com) (discontinued)
- [System files](https://github.com/lifehackerhansol/flashcard-archive/raw/main/r4ultra.com/R4_Ultra_AKAIO_1.8.6a.7z)

## R4dsixl3d
- Clone of the DSTT
- [Official Website](https://www.r4dsixl3d.com/)
- System files: [YSMenu](ysmenu)

<!--
## R4i (ndsill.net)
- [Official Website (archived)](https://web.archive.org/web/20141023052404/http://ndsill.net/)
// - Firmwares: \[[English](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_English.rar?raw=true)/[French](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_French.rar?raw=true)/[Spanish](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Spanish.rar?raw=true)/[Dutch](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Dutch.rar?raw=true)/[Italian](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Italian.rar?raw=true)/[Korean](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Korean.rar?raw=true)/[German](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_German.rar?raw=true)/[Japanese](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Japanese.rar?raw=true)/[Simplified Chinese](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Simplified_Chinese.rar?raw=true)/[Traditional Chinese](https://github.com/DS-Homebrew/flashcard-archive/blob/master/ndsill_v1.45_Traditional_Chinese.rar?raw=true)]
- System files: [YSMenu](ysmenu)
- Clone of the DSTT

## R4iSDHC Revolution (r4ita.com)
- [Official website](http://www.r4ita.com/) (discontinued)
// - System files: [English](https://github.com/DS-Homebrew/flashcard-archive/blob/master/21703-r4ita_v2.05_English.rar?raw=true)
- System files: [YSMenu](ysmenu)
-->

## R4i Gold (r4i-gold.eu)
- Timebombed clone of the DSTT
- [Official website](http://r4i-gold.eu)
- System files: [YSMenu](ysmenu)

## R4i Gold 3DS (r4i-gold.cc)
- Clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4i Gold 3DS, R4i Gold 3DS RTS, R4i Gold 3DS Deluxe, R4i Gold 3DS Plus (r4ids.cn)
- [Official Website](http://www.r4ids.cn/)
- [System Files](https://github.com/lifehackerhansol/flashcard-archive/blob/master/R4iDS.cn/R4iDS.cn%20Wood%20R4%201.64.zip?raw=true)

## R4i Gold V1.4.1 (r4i-gold.com)
- Timebombed clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4i Gold V1.4.1 (r4igold.cn)
- Clone of the DSTT
- System files: [YSMenu](ysmenu)

## R4i Pocket
- Clone of the DSTT
- [Official Website](http://www.r4ipocket.com/) (discontinued)
- System files: [YSMenu](ysmenu)

## R4i Redant
- Clone of the DSTT
- [Official Webite](http://www.r4i-redant.com/indexe.html) (discontinued)
- System files: [YSMenu](ysmenu)

<!--
## R4i SDHC (r4i-dshc.com)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT

## R4i SDHC (r4i-sdhc.com.tw)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT
-->

## R4i SDHC 2014-2021 (r4isdhc.com)
- All cards from r4isdhc.com with a year between 2014-2020 are [identical.](https://gbatemp.net/threads/proof-that-almost-all-r4i-sdhc-r4isdhc-carts-are-literally-the-same-carts.514539/).
- Timebombed clone of the DSTT
- [Official website](http://r4isdhc.com)
- System files: [YSMenu](ysmenu)
- ntrboot compatible

<!--
## R4i SDHC Revolution (r4i.cn)
- [Official website](http://www.r4i.cn/) (discontinued)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT

## R4i SDHC Silver RTS Lite (r4isdhc.com)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT

## R4i Upgrade Revolution (r4i-gold.cc)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT

## R4i YES (r4i-yes.com)
- [Official website](http://www.r4i-yes.com) (discontinued)
// - [System files](https://github.com/DS-Homebrew/flashcard-archive/blob/master/25202-r4i-yes.zip?raw=true)
- System files: [YSMenu](ysmenu)
- Purchase: [digitopz.com](http://www.digitopz.com/r4iyes-p-93.html)
- Clone of the DSTT

## R4xDS (r4xds.com)
- [Official website](http://www.r4xds.com/) (discontinued)
// - System Files: [English](https://github.com/DS-Homebrew/flashcard-archive/blob/master/21745-R4X_v2.03_English.rar?raw=true)
- System files: [YSMenu](ysmenu)
- Clone of the DSTT


-->

