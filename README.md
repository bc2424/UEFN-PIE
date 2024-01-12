# UEFN-PIE
 Play-in-Editor for Unreal Editor for Fortnite

Allows you to go ingame using only UEFN on the Save the World and Battle Royale gamemodes. This is useful as it is incredibly easy to create mods. It's basically the same as Carbon but it's in editor instead. (and the BR map doesn't work bc it's UEFN!)

## How to install

1. Download [Legendary](https://github.com/derrod/legendary) and log into your Epic Games account.
2. Download [24.20 from the manifest](https://github.com/polynite/fn-releases/blob/master/manifests/tmTvOoFm8OIjCeEGcEy5K-JduF6EvA.manifest) using Legendary.
3. Download [24.20 UEFN from this google drive link](https://drive.google.com/file/d/19Tf2c5O0ZAsjAWzwrpQBYgPszo9GQKQn/view?usp=sharing) and extract it to the same location as 24.20 (there will be some duplicate files, just replace them).
4. Download UEFN-PIE's code as a ZIP and extract it to the same location as 24.20 (merging FortniteGame folders).
5. Download [xdelta](https://www.romhacking.net/download/utilities/598/) and set "PIE_2420_v1.xdelta" as the patch and UnrealEditorFortnite-Win64-Shipping.exe in "FortniteGame/Binaries/Win64" as the Source File, make sure the target file is an exe inside the Win64 folder.
6. Download [Fiddler Classic](https://www.telerik.com/download/fiddler), once Fiddler is set up copy the contents FiddlerScript.txt and paste it into the FiddlerScript tab inside Fiddler.
7. Download [LawinServer](https://github.com/Lawin0129/LawinServer), run install_packages.bat, then setup.bat.
8. Open your patched exe from xdelta, click on Edit in the top left, then Editor Preferences..., scroll down to Play Credentials and Enable Logins and add Credentials, User Id will be your username on Lawin.
9. In UEFN Click the three dots next to Platform and scroll down to NetMode, make sure it is set to Play Standalone.

Once everything is set up you just need to have fiddler and lawin open to play PIE! Select a map and set the GameMode override in the world settings to BattleRoyale_Gamemode to load BR, the default gamemode is STW.
Equip items by adding to the Inventory Items to Grant in the Editor Preferences in Save The World Cheats.

## Features
- Battle Royale and Save the World ingame
- Equipping weapons
- Building and editing
- Using any skin in STW (crashes in BR SCP is used there instead)

## To do
- Move to 27.11, requires UI fix but would be optimal as more people have this build
- Weapon sounds
- Look into emoting
- Look into vehicles
- Make equipping skins in BR easier
- Apply styles to STW skins
- Fix funny anim when editing
- other stuff I forgot

## Credits
simonhxd - worked on majority of blueprint functionality for ingame
wiktorwiktor12a - better animations patch for UEFN
sizzyleaks and taijames - inventory
gamerbross - random help
