# UEFN-PIE
 Play-in-Editor for 24.20 Unreal Editor for Fortnite

Allows you to go ingame using UEFN on Save the World and Battle Royale gamemodes.

tldr it's carbon but in editor instead (and the BR map works if you have a lot of ram!)

## How to install

1. Download [Legendary](https://github.com/derrod/legendary) and log into your Epic Games account.
2. Download [24.20 from the manifest](https://github.com/polynite/fn-releases/blob/master/manifests/tmTvOoFm8OIjCeEGcEy5K-JduF6EvA.manifest) using Legendary.
3. Download [24.20 UEFN from this google drive link](https://drive.google.com/file/d/19Tf2c5O0ZAsjAWzwrpQBYgPszo9GQKQn/view?usp=sharing) and extract it to the same location as 24.20 (there will be some duplicate files, just replace them).
4. Download UEFN-PIE's code as a ZIP and extract it to the same location as 24.20 (merging FortniteGame folders).
5. Download [xdelta](https://www.romhacking.net/download/utilities/598/) and set "PIE_2420_v2.xdelta" as the patch and UnrealEditorFortnite-Win64-Shipping.exe in "FortniteGame/Binaries/Win64" as the Source File, make sure the target file is an exe inside the Win64 folder.
6. Download [Fiddler Classic](https://www.telerik.com/download/fiddler), once Fiddler is set up copy the contents of FiddlerScript.txt and paste it into the FiddlerScript tab inside Fiddler, go into Tools -> Options -> HTTPS and make sure Capture HTTPS CONNECTs, Decrypt HTTPS traffic, Ignore server certificate errors (unsafe) are all checked, then click Actions and Trust Root Certificate clicking yes when prompted.
7. Download [LawinServer](https://github.com/Lawin0129/LawinServer), run install_packages.bat, then launch.bat.
8. Make a shortcut to the patched exe you just created with the arguments "-disableplugins=ValkyrieFortnite -enableplugins=ValkyriePIE", then go to the path "%localappdata%\UnrealEditorFortnite\Saved\Config\WindowsEditor\" copy the Engine.ini to that location, then make it read only by right clicking on the file, -> properties > attributes: read only.
8. Open the shortcut then click on Edit in the top left, then Editor Preferences..., scroll down to Play Credentials and Enable Logins and add Credentials, User Id will be your username on Lawin, Password doesn't matter but needs to be filled in, Type should be set to epic or exchangecode.
9. In UEFN Click the three dots next to Platform and scroll down to NetMode, make sure it is set to Play Standalone and click play, if it loads into lobby, try again.

Once everything is set up you just need to have fiddler and lawin open to play PIE! Select a map and set the GameMode override in the world settings to BattleRoyale_Gamemode to load BR, or to SaveTheWorld_Gamemode to load STW.

Equip items by adding to the Inventory Items to Grant in the Editor Preferences in Save The World Cheats or Battle Royale Settings depending on gamemode.

If you would like to have STW maps, you can download the optional pak here:
https://drive.google.com/file/d/1xwQtEQ5-itL8O2_5n1x0oEIPwqsDqc7q/view?usp=drive_link

## Features
- Battle Royale and Save the World ingame
- Equipping weapons
- Building and editing
- Using any cosmetic
- Vehicles in BR

## To do
- Move to 27.11, requires UI fix but would be optimal as more people have this build
- Patch the exe so fiddler is no longer required
- Firing Weapon Sounds
- Look into emoting
- Make vehicles work in STW
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