Collection of Commodore 64 (C64) type-in code as found in magazines like Compute! and Compute!'s Gazette.
* Focus here is on **MLX 2** code from December 1985 onwards, and **Automatic Proofreader 2** BASIC code from March 1986 onwards
  * MLX 2 hex format: address + 8 bytes + checksum
  * Automatic Proofreader 2 format: checkum + BASIC line
* First-pass OCR has many misread characters that need correction
  *  OCR is parsed in a custom JavaScript program, using JS versions of the MLX 2 and Automatic Proofreader 2 checksum generators
* Corrected OCR is used in several ways:
  * Orginal version for reference and output variants
  * MLX 2: Hex bytes only version for [disassembly](https://www.masswerk.at/6502/disassembler.html) or conversion to valid .PRG via [C64List](https://www.c64-wiki.com/wiki/C64list)
* Each program folder contains source and final files with load instructions
  * Load .PRG directly in IEC mode; can also wrap it in a .D64 file
    * .PRG extension can be deleted from filename
  * Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
