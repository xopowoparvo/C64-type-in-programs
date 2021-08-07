**High Rise** game code from [Compute! magazine - February 1986](https://archive.org/details/1986-02-compute-magazine/page/n50/), by Charles McGuyer.
* MLX 2 hex format: address + 8 bytes + checksum
* Range: C000-CE7F
* Corrected OCR code saved in several formats:
  * **High Rise - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **High Rise - hex bytes only.txt**: program code without addresses or checksums
  * **highrise.prg**: Commodore 64 .PRG format
    * LOAD"HIGHRISE.PRG",8,1
    * SYS 49152
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
