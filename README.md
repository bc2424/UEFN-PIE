# UEFN-PIE
 Play-in-Editor for 24.20 Unreal Editor for Fortnite

Allows you to go ingame using UEFN on Save the World and Battle Royale gamemodes.

tldr it's carbon but in editor instead (and the BR map works if you don't mind bad performance!)

## How to install

1. Download [Legendary](https://cdn.discordapp.com/attachments/1194314410848682004/1195215448984272926/LegendaryCH4.7z?ex=6740aa61&is=673f58e1&hm=ee7ef52dc597d23f679c8fa6edb977a9115a344ec8f65a98590bb458d8dc4d0d&) and log into your Epic Games account.
2. Download [24.20 from the manifest](https://github.com/polynite/fn-releases/blob/master/manifests/tmTvOoFm8OIjCeEGcEy5K-JduF6EvA.manifest) using Legendary.
3. Download [24.20 UEFN from this google drive link](https://drive.google.com/file/d/19Tf2c5O0ZAsjAWzwrpQBYgPszo9GQKQn/view?usp=sharing) and extract it to the same location as 24.20 (there will be some duplicate files, just replace them).
4. Download UEFN-PIE's code as a ZIP and extract it to the same location as 24.20 (merging FortniteGame and Engine folders).
5. Download [xdelta](https://www.romhacking.net/download/utilities/598/) and set "PIE_2420_v3.xdelta" as the patch and UnrealEditorFortnite-Win64-Shipping.exe in "FortniteGame/Binaries/Win64" as the Source File, make sure the target file is an exe inside the Win64 folder.
6. Download [LawinServer](https://github.com/Lawin0129/LawinServer), run install_packages.bat, then launch.bat.
7. Make a shortcut to the patched exe you just created with the arguments "-disableplugins=ValkyrieFortnite -enableplugins=ValkyriePIE".
8. Open the shortcut then click on Edit in the top left, then Editor Preferences..., scroll down to Play Credentials and Enable Logins and add Credentials, User Id will be your username on Lawin, Password doesn't matter but needs to be filled in, Type should be set to epic or exchangecode.
9. In UEFN Click the three dots next to Platform and scroll down to NetMode, make sure it is set to Play Standalone and click play, if it loads into lobby, try again.

Once everything is set up you just need to have lawin open to play PIE! Select a map and set the GameMode override in the world settings to BattleRoyale_Gamemode to load BR, or to SaveTheWorld_Gamemode to load STW, basic Creative can be played by loading the "creative_noapollo_terrain" level in ValkyriePIE.

Equip items by adding to the Inventory Items to Grant in the Editor Preferences in Save The World Cheats or Battle Royale Settings depending on gamemode.

If you would like to have STW maps, you can download the optional pak here:
https://drive.google.com/file/d/1xwQtEQ5-itL8O2_5n1x0oEIPwqsDqc7q/view?usp=drive_link

If you do not feel comfortable using the prebuilt DLL "Engine/Binaries/ThirdParty/NVIDIA/NVaftermath/Win64/UefnPIE-Cobalt-3551.x64.dll" you can build it yourself here "https://github.com/Milxnor/Cobalt"

## Features
- Battle Royale, Creative, and Save the World ingame
- Equipping weapons with wrap support
- Building and editing
- Using any cosmetic
- Vehicles in BR

## To do
- Proper emoting
- Better vehicle patch
- More detailed guide
- Gadgets
- Fix Storm Damage in BR
- Fix Particle FX

## Credits
- simonhxd - worked on majority of blueprint functionality for ingame
- wiktorwiktor12a - better animations patch for UEFN
- sizzyleaks and taijames - inventory help
- milxnor - ssl bypass (memcury and neonite credited in their readme)
- gamerbross - random help
- tkd_kedis - sandbox map
- thecodingpro - random help