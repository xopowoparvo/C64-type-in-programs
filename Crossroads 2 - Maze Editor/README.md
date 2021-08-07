**Crossroads 2 - Maze Editor** program code from [Compute!'s Gazette magazine - December 1988](https://archive.org/details/1988-12-computegazette/page/n40/), by Steve Harter.
* MLX 2 hex format: address + 8 bytes + checksum
* Range: C800-CDC7
* Corrected OCR code saved in several formats:
  * **MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **Hex bytes only.txt**: program code without addresses or checksums
  * **mazeeditor.prg**: Commodore 64 .PRG format
    * LOAD"MAZEEDITOR.PRG",8,1
    * NEW
    * SYS 51200
    * LOAD"CROSSROADS2",8
    * RUN
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
