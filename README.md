Collection of Commodore 64 (C64) type-in code as found in magazines like Compute! and Compute!'s Gazette.
* Focus here is on MLX II code from December 1985 onwards
  * MLX II hex format: address + 8 bytes + checksum
* First-pass OCR has many misread characters that need correction
  *  Parse the raw OCR in a custom JavaScript program
* Corrected OCR is used in several ways:
  * Orginal version for reference
  * Hex bytes only version for [disassembly](https://www.masswerk.at/6502/disassembler.html) or conversion to valid .PRG via [C64List](https://www.c64-wiki.com/wiki/C64list)
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
  * Load .PRG directly in IEC mode; could also use it from a .D64 file
