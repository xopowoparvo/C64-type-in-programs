**MLX II** program code from [Compute! magazine - December 1985](https://archive.org/details/1985-12-compute-magazine/page/n75/), by Ottis R. Cowper.
* Used to enter code in MLX II hex format: address + 8 bytes + checksum
* Code map:
  * **100-150** Initialize variables, clear SID, clear screen
  * **160-210** Draw title, branding, get start & end addresses, clear memory
  * **220-290** Menu
  * **300-340** Get address input subroutine (start, end, entry)
  * **350-390** Checksum routine
  * **400-600** Input data
  * **610-680** Display data
  * **690-1020** I/O routines (load, save)
    * **690-740** Choose Tape or Disk
    * **750-870** Disk I/O
    * **880-1020** Tape I/O
  * **1030-1050** Check validity of start & end addresses
  * **1060-1090** Sounds
    * **1060** Low buzz = failure
    * **1080** High beep = success
* **mlx2.d64** Typed in and tested on [VICE emulator](https://vice-emu.sourceforge.io/)
  * Mount disk image
  * LOAD"MLX2",8
  * RUN
