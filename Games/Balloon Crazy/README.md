**Balloon Crazy** game code from [Compute! magazine - December 1985](https://archive.org/details/1985-12-compute-magazine/page/n43/), by Joseph Russ.
* MLX 2 hex format: address + 8 bytes + checksum
* Range: C000-C81F
* Corrected OCR code saved in several formats:
  * **Balloon Crazy - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **Balloon Crazy - hex bytes only.txt**: program code without addresses or checksums
  * **ballooncrazy.prg**: Commodore 64 .PRG format
    * LOAD"BALLOONCRAZY.PRG",8,1
    * SYS 49152
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
