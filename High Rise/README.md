**High Rise** game code from [February 1986 Compute! magazine](https://archive.org/details/1986-02-compute-magazine/page/n50/).
* MLX II hex format: address + 8 bytes + checksum
* Range: C000-CE7F
* Corrected OCR code saved in several formats:
  * **MLX II code.txt**: as seen in the magazine, with addresses and checksums
  * **Hex bytes only.txt**: program code without addresses or checksums
  * **highrise.prg**: Commodore 64 .PRG format
    * LOAD"HIGHRISE.PRG",8,1
    * SYS 49152
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)