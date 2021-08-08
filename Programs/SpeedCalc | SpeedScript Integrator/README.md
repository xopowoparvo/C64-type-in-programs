## General Info
**SpeedCalc** and **SpeedScript Integrator** program code from [Compute! magazine - January 1986](https://archive.org/details/1986-01-compute-magazine/page/n67/), by Kevin Martin.
* MLX 2 hex format: address + 8 bytes + checksum
* Corrected OCR code saved in several formats:
  * **[program name] - MLX 2 code.txt**: as seen in the magazine, with addresses and checksums
  * **[program name] - hex bytes only.txt**: program code without addresses or checksums
  * **[program name].prg**: Commodore 64 .PRG format
* Tested on [VICE emulator](https://vice-emu.sourceforge.io/)

### SpeedCalc
* Spreadsheet program
* Range: 0801-2680
* Load instructions:
  * LOAD"SPEEDCALC.PRG",8
  * RUN

### SpeedScript Integrator
* Convert SpeedCalc spreadsheet to importable SpeedScript file for print formatting
* Range: 0801-0948
* Load instructions:
   * LOAD"INTEGRATOR.PRG",8
   * RUN
