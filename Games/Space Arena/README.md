**Space Arena** game code from [Compute!'s Gazette magazine - January 1986](https://archive.org/details/1986-01-computegazette/page/n49/), by Bryan Files.
* MLX 2 hex format: address + 8 bytes + checksum
* Range: C000-CFB7
* Corrected OCR code saved in several formats:
  * **Space Arena - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **Space Arena - hex bytes only.txt**: program code without addresses or checksums
  * **spacearena.prg**: Commodore 64 .PRG format
    * LOAD"SPACEARENA.PRG",8,1
    * SYS 49152
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
