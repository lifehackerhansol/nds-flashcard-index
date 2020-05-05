---
title: "Dumping Cartridges"
---

This is an add-on section for dumping cartridges using WoodDumper, either via a Slot 2 flashcart (DS Phat/Lite only) or WiFi.

Using a Nintendo DSi or Nintendo 3DS? There are easier ways to dump your cartridge instead if you have installed Custom Firmware.

- Nintendo DSi: [GodMode9i](https://dsi.cfw.guide/dump-cart) can dump Slot-1 cartridges, including Nintendo DSi Exclusive/Enhanced Cartridges.
- Nintendo 3DS: [GodMode9](https://3ds.hacks.guide/godmode9-usage#dumping-a-game-cartridge) can dump Slot-1 cartridges, including Nintendo DSi Exclusive/Enhanced & Nintendo 3DS Catridges.

<button class="tablinks btn btn--large btn--success" id="defaultOpen" onclick="openTab(event, 'memoryPitInstructions')">WiFi</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'flipnoteLennyInstructions')">Slot-2 Flashcart (DS Phat/Lite only)</button>

{% capture memoryPitInstructions %}
## WiFi

### Requirements
- Either WEP or open WiFi security setup on your Nintendo DS
  - Hotspots work as well, so you do not need to compromise the security of your router.
  - You could setup WiFi by launching a game with Nintendo WiFi connection (such as Mario Kart DS), from either your flashcart or an actual game cartridge
- An FTP client
  - Windows Users could use Windows Explorer (type `ftp://(ip)` on the breadcrumb bar when the time comes).
  - Google Chrome users could use the built in FTP client (which has been undeprecated due to the pandemic).
  - PC users not in the above category could use [FileZilla](https://filezilla-project.org/download.php?type=client).
  - If you're on Android, we recommend [ES File Explorer](https://www.amazon.com/ES-File-Explorer-Manager/dp/B008K6HN8I).
- A way to launch homebrew on your console.
  - Slot-1 Flashcart
  - HaxxStation compatible devices (Wii (U)/Other DS that can boot homebrew) to send WoodDumper over DS Download Play

### Instructions
#### Section I - Setting up Wood Dumper
1. Download the latest version of [Wood Dumper](https://gbatemp.net/download/wooddumper.33406/)
2. Extract `wooddumper.nds` and place it anywhere on the microSD card.
3. On your Nintendo DS console, launch `wooddumper.nds` from your flashcart (which means having the microSD card inserted).
4. When it says "Set a target card", eject your flashcart and insert the cartridge that you'd like to dump. Then, press A.
5. Wait for the IP address to be shown on the top screen, then take note of it.

#### Section II - Downloading your ROM

1. Launch your FTP client.
2. Connect your FTP client to the IP address you used above.
3. Download the `.nds` and `.sav` files to your PC.
4. Wait until it says `-> 226 Transfer Complete` on your Nintendo DS.

{% endcapture %}

{% capture flipnoteLennyInstructions %}
## Slot-2 Flashcart (DS Phat/Lite only)
{% endcapture %}

<div id="memoryPitInstructions" class="tabcontent">{{ memoryPitInstructions | markdownify }}</div>
<div id="flipnoteLennyInstructions" class="tabcontent">{{ flipnoteLennyInstructions | markdownify }}</div>

Congratulations, you have now dumped your Nintendo DS game. This dump is useful for loading the game on emulators, preservation purposes and maintaining a local backup you could use if your cartridge goes haywire. You also need this if you'd like to get into ROM hacking.

<script>
	let tabcontent = document.getElementsByClassName("tabcontent");
	let tablinks = document.getElementsByClassName("tablinks");

	function openTab(evt, tabName) {
		let element;

		for (element of tabcontent) {
			element.style.display = "none";
		}

		for (element of tablinks) {
			element.className = element.className.replace("btn--success", "btn--info");
			if (!element.className.includes('btn--info'))
				element.className += " btn--info";
		}

		document.getElementById(tabName).style.display = "block";
		evt.currentTarget.className = evt.currentTarget.className.replace("btn--info", "btn--success");
	}

	// Get the element with id="defaultOpen" and click on it
	document.getElementById("defaultOpen").click();
</script>