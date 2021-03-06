**MLX 2** program code from [Compute!'s Gazette magazine - June 1990](https://archive.org/details/1990-06-computegazette/page/n58/), by Ottis R. Cowper.
* Used to enter code in MLX 2 hex format: address + 8 bytes + checksum
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
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)
  * LOAD"MLX2.PRG",8
  * RUN
* Relevant links
  * [*Compute!'s Gazette*](https://lparchive.org/Computes-Gazette/) - March 1, 2016, by Chokes McGee.
  * [*How Did Compute!’s Gazette’s MLX Program Work?*](https://nebusresearch.wordpress.com/2021/01/13/how-did-computes-gazettes-mlx-program-work/) - January 13, 2021, by Joseph Nebus.
  * [*How did Compute!’s and Compute!’s Gazette’s New MLX Work?*](https://nebusresearch.wordpress.com/2021/06/16/how-did-computes-and-computes-gazettes-new-mlx-work/) - June 16, 2021, by Joseph Nebus.

