## General Info
**Sprint** and **64 Doodler Demo** program code from [Compute!'s Gazette magazine - January 1986](https://archive.org/details/1986-01-computegazette/page/n73/), by Robert A. Stoerrle.
* **Sprint** is a utility to compile BASIC programs for faster execution; **64 Doodler Demo** is a simple draw program that is very slow in BASIC and much faster after being compiled by **Sprint**
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
  * Unable to compile the included **64 Doodler Demo** - maybe an issue of using emulation versus actual hardware?

### Sprint
* MLX 2 hex format: address + 8 bytes + checksum
* Range: 8000-9737
* Corrected OCR code saved in several formats:
  * **Sprint - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **Sprint - hex bytes only.txt**: program code without addresses or checksums
  * **sprint.prg**: Commodore 64 .PRG format
    * LOAD"SPRINT.PRG",8,1
    * SYS 32768

### 64 Doodler Demo
LOAD"64DOODLER.PRG",8
RUN
