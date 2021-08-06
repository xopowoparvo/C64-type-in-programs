**Balloon Crazy** game code from [December 1985 Compute! magazine](https://archive.org/details/1985-12-compute-magazine/page/n43/).
* MLX II hex format: address + 8 bytes + checksum
* Range: C000-C81F
* Corrected OCR code saved in several formats:
  * **MLX II code.txt**: as seen in the magazine, with addresses and checksums
  * **Hex bytes only.txt**: program code without addresses or checksums
  * **ballooncrazy.prg**: Commodore 64 .PRG format
    * LOAD"BALLOONCRAZY.PRG",8,1
    * SYS 49152
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
