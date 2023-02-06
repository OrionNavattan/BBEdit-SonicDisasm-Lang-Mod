# BBEdit-SonicDisasm-Lang-Mod
 A BBEdit 68K and Z80 codeless language module for use with the SonicRetro disassemblies of Sonic the Hedgehog 1, 2, and 3, as well as Hivebrain's 2022 disassembly of Sonic 1 and OrionNavattan's disassembly of Sonic 2. Should also be usable for general Mega Drive/Genesis and Neo-Geo assembly development.

Based on [J.C. Field's 68K codeless language module](https://gitlab.com/jcfields/bbedit-language-modules). In addition to adding support for Z80 mnemonics and registers, instruction mmnemomics not avaliable on the 68000 and 68010 (including all FPU and MMU instructions) have been removed, support for the pc, vbr, and usp registers as well as several alias (blo and bhs) have been added, and BBLMScansFunctions has been disabled to prevent hangs when working with large files. The module also highlights many of the globally-used macros in all five of the disassemblies, as well as some of the functions used in the AS-targeted ones, and many of the assembler commands and directives of both AS and ASM68K.

To install the module, place it in ~/Library/Application Support/BBEdit/Language Modules directory and relaunch BBEdit.
