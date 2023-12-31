# Counter-Strike 1.6 ReGameDLL combined with Zombie Plague Mod

History: Using Zombie Plague 5.0.8 with AMXX 1.8.2 and ReGameDLL installed will lead to a game crash when loading maps.
To resolve this issue, update the AMXX version to 1.10. Once the AMXX version is updated, the game should no longer crash when loading maps.

Compactible versions:
- [AMXX 1.10 Base Pack](https://www.amxmodx.org/amxxdrop/1.10/amxmodx-1.10.0-git5217-base-windows.zip)
- [AMXX 1.10 Counter-Strike Addon](https://www.amxmodx.org/amxxdrop/1.10/amxmodx-1.10.0-git5217-cstrike-windows.zip)
- [Zombie Plague 40 & 50](https://forums.alliedmods.net/showthread.php?t=72505?t=72505)
- [ReGameDLL](https://github.com/s1lentq/ReGameDLL_CS) -> [(5.22.0.593)](https://github.com/s1lentq/ReGameDLL_CS/releases/download/5.22.0.593/regamedll-bin-5.22.0.593.zip)

Additional Componets that I use: 
- [ReAPI 5.22.0.254](https://github.com/s1lentq/reapi/releases/download/5.22.0.254/reapi-bin-5.22.0.254.zip)
- [Metamod-R 1.21p38](https://github.com/theAsmodai/metamod-r/releases/download/1.3.0.138/metamod-bin-1.3.0.138.zip)

Other additions not in pack:
- Client-side enhancements for CS 1.6 and Condition Zero [csldr](https://github.com/mikkokko/csldr). Read instructions on their repo.

# Installation Steps for Pack:
1. Download the All-In-One-Pack.zip file from the releases section.
2. Extract the 'cstrike' folder from the downloaded zip file and place it in your game directory.
3. Open cstrike folder (from game directory, not from the downloaded zip) and make sure that your 'liblist.gam' file in includes the entry:
   gamedll "addons\metamod\dlls\metamod.dll"
   
   More precise: Open file "C:\Program Files (x86)\Steam\steamapps\common\Half-Life\cstrike\liblist.gam" and add: gamedll "addons\metamod\dlls\metamod.dll"
5. Enjoy game!
    
