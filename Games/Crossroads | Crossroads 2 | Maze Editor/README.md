## General Info
All 3 programs share these characteristics:
* MLX 2 hex format: address + 8 bytes + checksum
* Corrected OCR code saved in several formats:
  * **[program name] - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **[program name] - hex bytes only.txt**: program code without addresses or checksums
  * **[program name].prg**: Commodore 64 .PRG format
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)

### Crossroads
**Crossroads** game code from [Compute!'s Gazette magazine - December 1987](https://archive.org/details/1987-12-computegazette/page/n37/), by Steve Harter.
* Range: 0801-1F30
* Load instructions
    * LOAD"CROSSROADS.PRG",8
    * RUN

### Crossroads 2
**Crossroads 2** game code from [Compute!'s Gazette magazine - December 1988](https://archive.org/details/1988-12-computegazette/page/n40/), by Steve Harter.
* Range: 0801-21C0
* Load instructions
  * LOAD"CROSSROADS2.PRG",8
  * RUN

### Maze Editor for Crossroads 2
