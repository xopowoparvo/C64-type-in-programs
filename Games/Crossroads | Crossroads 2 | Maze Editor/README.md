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
* Load instructions:
    * LOAD"CROSSROADS.PRG",8
    * RUN

### Crossroads 2
**Crossroads 2** game code from [Compute!'s Gazette magazine - December 1988](https://archive.org/details/1988-12-computegazette/page/n40/), by Steve Harter.
* Range: 0801-21C0
* Load instructions:
  * LOAD"CROSSROADS2.PRG",8
  * RUN

### Maze Editor for Crossroads 2
**Crossroads 2 - Maze Editor** program code from [Compute!'s Gazette magazine - December 1988](https://archive.org/details/1988-12-computegazette/page/n40/), by Steve Harter.
* Range: C800-CDC7
* Load instructions:
  * LOAD"MAZEEDITOR.PRG",8,1
  * NEW
  * SYS 51200
  * LOAD"CROSSROADS2.PRG",8
  * RUN

### Relevant links
* **Crossroads | Crossroads 2**: [*interview with steve harter, creator of crossroads and crossroads ii*](https://kirk.is/2006/04/13/) - April 13, 2006, by Kirk Israel.
* **Crossroads** review: [*Compute!'s Gazette: Part 5*](https://lparchive.org/Computes-Gazette/Update%2005/) - March 2016, by Chokes McGee.
* **Crossroads 2** review: [*Compute!'s Gazette: Part 12*](https://lparchive.org/Computes-Gazette/Update%2012/) - March 2016, by ManxomeBromide.
* **Crossroads 2** disassembly: [*GitHub repository*](https://github.com/hyphz/crossroads-2-disassembly) - May 2019, by hyphz.
