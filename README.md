# UEFN-PIE
 Play-in-Editor for Unreal Editor for Fortnite

Allows you to go ingame using UEFN on Battle Royale gamemode.

tldr it's carbon but in editor instead

## How to install

1. Download [Legendary](https://github.com/derrod/legendary) and log into your Epic Games account.
2. Download [31.40 from the manifest](https://github.com/polynite/fn-releases/raw/refs/heads/master/manifests/4re6ocqjn9AjcRjtC0Sz9SYYmq0I_Q.manifest) using Legendary.
3. Download [31.40 UEFN from the manifest] FIXME FIXME FIXME and extract it to the same location as 31.40.
4. Download UEFN-PIE's code as a ZIP and extract it to the same location as 31.40 (merging FortniteGame folders).
5. Download [xdelta](https://www.romhacking.net/download/utilities/598/) and set "PIE_3140_v1.xdelta" as the patch and UnrealEditorFortnite-Win64-Shipping.exe in "FortniteGame/Binaries/Win64" as the Source File, make sure the target file is an exe inside the Win64 folder.
6. Download [Fiddler Classic](https://www.telerik.com/download/fiddler), once Fiddler is set up copy the contents of FiddlerScript.txt and paste it into the FiddlerScript tab inside Fiddler, go into Tools -> Options -> HTTPS and make sure Capture HTTPS CONNECTs, Decrypt HTTPS traffic, Ignore server certificate errors (unsafe) are all checked, then click Actions and Trust Root Certificate clicking yes when prompted.
7. Download [Neonite](https://github.com/HybridFNBR/Neonite), start the run.bat.
8. Make a shortcut to the patched exe you just created with the arguments "-disableplugins="ValkyrieFortnite,AtomVK", then go to the path "%localappdata%\UnrealEditorFortnite\Saved\Config\WindowsEditor\" and copy the Engine.ini to that location, then make it read only by right clicking on the file, -> properties > attributes: read only.
8. Open the shortcut then click on Edit in the top left, then Editor Preferences..., scroll down to Play Credentials and Enable Logins and add Credentials, User Id will be your username on Neonite, Password doesn't matter but needs to be filled in, Type should be set to epic.
9. In UEFN Click the three dots next to Platform and scroll down to NetMode, make sure it is set to Play Standalone and click play, if it loads into lobby, try again.

Once everything is set up you just need to have fiddler and lawin open to play PIE! Select a map and set the GameMode override in the world settings to BattleRoyale_Gamemode to load BR, or to SaveTheWorld_Gamemode to load STW.

Equip items by adding to the Inventory Items to Grant in the Editor Preferences in Battle Royale Settings.

## Features
- Battle Royale ingame
- Equipping weapons
- Building and editing
- Using any cosmetic

## To do
- Readd Save the World support
- Workaround fiddler so it is no longer required
- Firing Weapon Sounds
- Proper emoting
- Fixed vehicles
- Crouching
- Interact Prompts
- Gadgets
- Fix Storm Damage in BR
- Fix Particle FX

## Credits
- simonhxd - worked on majority of blueprint functionality for ingame
- wiktorwiktor12a - better animations patch for UEFN
- sizzyleaks and taijames - inventory help
- gamerbross - random help
- tkd_kedis - sandbox map
- thecodingpro - random help
