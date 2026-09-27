# Faster Black 2 / White 2
This is a hack for Pokemon Black 2 and White 2 to remove cutscenes across the game.
\
The hack is designed and tested to be compatible with the [ZX fork](https://github.com/Ajarmar/universal-pokemon-randomizer-zx/releases) of the randomizer, and tested to be playable on original consoles.

### Get the patch:
- Select the Resources option from the sidebar on the right side of this page.
- Download `BW2_Faster.zip`.
- Unzip the downloaded zip folder.
- The README included in the download has patching instructions.

### Features
- Professor Juniper's "welcome to the world" introduction is faster.
- The first cutscene after Juniper's introduction has been cut.
- The scenes leading up to the first rival battle have been shortened and cut.
- An NPC that maximizes the friendship of the lead Pokemon has been added outside of the Floccesy Town Pokemon Center.
- The female rancher that heals the player's party at Floccesy Ranch is always present.
- The Pokestar Studios sequence has been made optional.
  - The healing items normally offered by the hiker in the theater can be obtained by visiting the studio and completing the Brycen-Man shoot. The Pokestar Studios area has been reduced to just the soundstage and its connected rooms, and the hiker's items are given by a studio hand directly.
- Castellia Gym no longer has to be approached before entering Castellia Sewers.
- Join Avenue is no longer present.
- Entering the Hidden Grotto on Route 5 has been made optional.
- The Driftveil Tournament PWT sequence has been changed.
  - There are two versions of the patch. One completely cuts out the PWT sequence, the other retains its three battles.
- The Lacunosa Town cutscenes have been cut.
- Dual-screen 3D movies have been cut:
  - the boat trip from Virbank City to Castellia City
  - the plane trip from Mistralton City to Lentimas Town
  - the Plasma Frigate attack on Opelucid City
  - the Plasma Frigate liftoff on Route 21
  - the Kyurem movies in Giant Chasm
- ... and more!

### Build Notes

**Notes on compiled code changes**
\
This applies to the files under the ftc_* directories.
\
Out of an abundance of paranoia, modified code binaries are version-controlled as ips patches instead of the entire file.
\
y9.bin is the entire binary file, no patching is required
\
arm9.ips can be applied directly to a compressed arm9.bin
\
The overlays must first be blz decompressed ([CUE's compressors](https://github.com/PeterLemon/Nintendo_DS_Compressors)), then the ips patches can be applied.

Alternatively, it should be much easier to dump the files from the patched ROM directly using Tinke. arm9.bin is compressed, and the modified overlays are decompressed.
\
\
The output ROMs were assembled using the 2022/09/01 build of [TinkeDSi](https://github.com/R-YaTian/TinkeDSi).
\
(Trimmed) ROMs can also be assembled using [CTRMap](https://github.com/ds-pokemon-hacking/CTRMap-CE/releases) with the [CTRMapV](https://github.com/ds-pokemon-hacking/CTRMapV/releases) plug-in installed.

### Credits
CUE: the Nintendo DS/GBA BLZ (de)compressor, for decompressing the arm9 assembly and its overlays.
\
Hello007: CTRMap with CTRMapV, for general map value referencing.
\
PlatinumMaster: SwissArmyKnife (Avalonia), for text and script referencing and text editing.
\
brom: the research into Juniper's "welcome to the world" intro. https://docs.google.com/spreadsheets/d/17_s9_ZaZ6p-292oCnaoVsKOWtDKkDVtVmlYtuxCIl_s
\
R-YaTian: TinkeDSi, forked from MetLob's TinkeDSi, forked from pleonex's Tinke, for DS ROM repacking.
\
The people who worked on Gen 5 script command documentation. https://docs.google.com/spreadsheets/d/15n-9xDRZC8IgIILe4fWgREoA6zlIC13K5VhW4ccfM-0
\
The people in the "Kingdom of DS Hacking" Discord server and those that came before them, for the extensive work done documenting the disassembly.