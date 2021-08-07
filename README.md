Collection of Commodore 64 (C64) type-in code as found in magazines like Compute! and Compute!'s Gazette.
* Focus here is on MLX 2 code from December 1985 onwards
  * MLX 2 hex format: address + 8 bytes + checksum
* First-pass OCR has many misread characters that need correction
  *  OCR is parsed in a custom JavaScript program, using a JS version of the MLX 2 checksum checker
* Corrected OCR is used in several ways:
  * Orginal version for reference and output variants
  * Hex bytes only version for [disassembly](https://www.masswerk.at/6502/disassembler.html) or conversion to valid .PRG via [C64List](https://www.c64-wiki.com/wiki/C64list)
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
  * Load .PRG directly in IEC mode; could also use it from a .D64 file
    * .PRG extension can be deleted from filename
* Each program folder contains source and final files with load instructions
