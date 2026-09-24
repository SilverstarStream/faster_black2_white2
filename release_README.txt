This is a patch for Pokemon Black 2 and White 2 to remove cutscenes across the game.
The hack is designed and tested to be compatible with the ZX fork of the randomizer (https://github.com/Ajarmar/universal-pokemon-randomizer-zx/releases), and tested to be playable on original consoles.

These patches require a clean English ROM for the patch to be applied. Using a non-clean ROM will likely not work.
ROMs for languages other than English are not supported. The English ROM is the same between the US and Europe regions.
Checksums of clean ROMs, verified by no-intro (https://datomatic.no-intro.org/index.php?page=search&s=28)
Black 2:
CRC32: D4427FD1
MD5: 4C65A32989C78B8070751765592B0EA6
White 2:
CRC32: 777EB04F
MD5: 0AFC7974C393265D8CF23379BE232A1C

----------------------------------------------------------------
How to apply the patch:
Using https://www.marcrobledo.com/RomPatcher.js or any xdelta patcher of your preference, select the BW2 ROM file for the clean file.
Then select the matching patch file.
Finally press apply patch to create a new ROM file.
If using this patch with the randomizer, load the patched ROM from above into the randomizer. There will be a warning about the ROM not being clean, which is expected due to the patch. Then randomize like normal.


There are two versions of the patch available:
1. The standard patch skips many cutscenes present the clean game. It removes some of the cutscenes around the mandatory Driftveil Tournament in the Pokemon World Tournament area, and does not remove any battles.
2. The skipPWT patch includes all of the changes from the standard patch, and skips the entirety of the Driftveil Tournament.

Play with whichever patch you feel best fits whichever self-imposed ruleset you are playing with.

Some information about PWT's Driftveil Tournament:
- All opponents' Pokemon are level 25 while the levels of the player's Pokemon are unaltered.
- No Exp points are gained from these battles.
- The tournament takes over 5 minutes to play through.

----------------------------------------------------------------
Credits:
Patch created by SilverstarStream. https://github.com/SilverstarStream/faster_black2_white2
CUE: the Nintendo DS/GBA BLZ (de)compressor, for decompressing the arm9 assembly and its overlays.
Hello007: CTRMap, for general map value referencing.
PlatinumMaster: SwissArmyKnife (Avalonia), for text and script referencing and text editing.
brom: the research into Juniper's "welcome to the world" intro. https://docs.google.com/spreadsheets/d/17_s9_ZaZ6p-292oCnaoVsKOWtDKkDVtVmlYtuxCIl_s
R-YaTian: TinkeDSi, forked from MetLob's TinkeDSi, forked from pleonex's Tinke, for DS ROM repacking.
The people who worked on Gen 5 script command documentation. https://docs.google.com/spreadsheets/d/15n-9xDRZC8IgIILe4fWgREoA6zlIC13K5VhW4ccfM-0
The people in the "Kingdom of DS Hacking" Discord server and those that came before them, for the extensive work done documenting the disassembly.