**Off-Screen Trace** program code from [Compute!'s Gazette magazine - January 1986](https://archive.org/details/1986-01-computegazette/page/n116/), by Brent Dubach.
* Utility to trace BASIC program execution, line by line
* MLX 2 hex format: address + 8 bytes + checksum
* Range: 8800-8AFF
* Corrected OCR code saved in several formats:
  * **Off-Screen Trace - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **Off-Screen Trace - hex bytes only.txt**: program code without addresses or checksums
  * **ostrace.prg**: Commodore 64 .PRG format
    * LOAD"OSTRACE.PRG",8,1
    * SYS 34816
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
