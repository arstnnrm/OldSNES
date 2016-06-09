# blargSNES Virtual Console Edition

INSTRUCTIONS:
1. Put your SNES rom on the romfs folder.
2. Rename it rom.smc.
3. Run make.bat.
4. Type in the game's title, publisher, product code (whatever you want) and unique id (whatever you want from 000000 to ffffff).
5. Install the generated CIA file.
6. Enjoy.

MAKING CUSTOM BANNER AND ICON (OPTIONAL):
1. Put a screenshot of the game on the input folder.
2. Rename it banner.png.
3. Put a box art or cartridge label image of the game on the input folder.
4. Rename it label.png.
5. OPTIONAL: If you want your custom banner as much accurate as possible to the oficial VC, search for SCE-PS3-RD-R-LATIN.TTF on google
   and put it on the input folder.
6. Run banner.bat.
7. Type in the game's title and release year.
8. OPTIONAL: set the banner text's font size, number of lines and spacing. Leave it blank to use default values.
8. Navigate to the tools folder and start Ohana3DS.exe.
9. Select the Textures tab then click Open.
10. Navigate to the banner folder and select banner0.bcmdl.
11. Select COMMON1 and click Import.
12. Navigate to the output folder and select COMMON1.png.
13. Repeat steps 11 and 12 with COMMON1_2 and COMMON1_3, selecting COMMON1_2.png and COMMON1_3.png.
14. Save your changes then click Open again.
15. Navigate to the banner folder again, and select the banner file matching your console's region and language.
    banner1.bcmdl = English ~ EUR_EN
    banner2.bcmdl = French ~ EUR_FR
    banner3.bcmdl = German ~ EUR_GE
    banner4.bcmdl = Italian ~ EUR_IT
    banner5.bcmdl = Spanish ~ EUR_SP
    banner6.bcmdl = Dutch ~ EUR_DU
    banner7.bcmdl = Portuguese ~ EUR_PO
    banner8.bcmdl = Russian ~ EUR_RU
    banner9.bcmdl = Japanese ~ JPN_JP
    banner10.bcmdl = English ~ USA_EN
    banner11.bcmdl = French ~ USA_FR
    banner12.bcmdl = Spanish ~ USA_SP
    banner13.bcmdl = Portuguese ~ USA_PO
16. Select the first file and click Import.
17. Navigate to the output folder and select USA_EN2.png.
18. Select the next file and click Import.
19. Select EUR_EN3.png or USA_EN3.png, depending on your 3DS's region.
20. Save your changes then exit Ohana3DS.
21. Now follow the instructions on how to build your CIA.


Credits:
- StapleButter and DiscostewSM for blargSNES.
- Asia81 for the SNES VC banner template.
