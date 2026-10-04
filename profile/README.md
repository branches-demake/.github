# The Branches Demake Team

An group of unofficial ports of BFDI: Branches (original game by Team Branches)

## Disclaimer
Branches Demake Team is not affiliated by Team Branches or Jacknjellify.
[Watch BFDI by jacknjellify](https://www.youtube.com/@BFDI)
[Play BFDI: Branches by Team Branches](https://bfdibranches.com)

## To do list
Keep in mind there are hardware limitations for each system.

### Original Hardware (Commodore computers)
| System                          | RAM          | CPU                                                           | Video              | Feasibility | 
| ------------------------------- | ------------ | ------------------------------------------------------------- | ------------------ | ----------- |
| Commodore 64 / 64c / SX-64      | 64 KB        | MOS 6510 @ 1 MHz                                              | VIC-II             | 75 / 100    |
| Commodore 64 + REU 1764         | 320 KB       | same as C64                                                   | VIC-II             | 95 / 100    |
| Commodore 64 + SuperCPU         | up to 16 MB  | MOS 6510 @ 1 MHz + WDC W65C816S @ 20 MHz                      | VIC-II             | 100 / 100   |
| Commodore 128 / 128D            | 128 KB       | MOS 8502 @ 1-2 MHz + Zilog Z80 @ 4 MHz                        | VIC-IIe + VDC [^1] | 90 / 100    |
| Commodore 128 + REU 1700        | 256 KB       | same as C128                                                  | VIC-IIe + VDC [^1] | 100 / 100   |
| Commodore 128 + REU 1750        | 640 KB       | same as C128                                                  | VIC-IIe + VDC [^1] | 100 / 100   |
| Commodore 128 + SuperCPU        | up to 16 MB  | MOS 8502 @ 1-2 MHz + Zilog Z80 @ 4MHz + WDC W65C816S @ 20 MHz | VIC-IIe + VDC [^1] | 100 / 100   |
| Commodore VIC-20                | 5 KB         | MOS 6502 @ 1 MHz                                              | VIC [^2]           | 0 / 100     |
| Commodore VIC-20 32 KB          | 32 KB        | same as VIC-20                                                | VIC [^2]           | 45 / 100    |
| Commodore Plus/4                | 64 KB        | MOS 7501/8501 @ 1.78 MHz                                      | TED [^2]           | 55 / 100    |
| Commodore 16/116                | 16 KB        | same as Plus/4                                                | TED [^2]           | 15 / 100    |
| Commodore Amiga 1000            | up to 8.5 MB | Motorola 68k @ 7.16 MHz                                       | OCS Chipset        | 100 / 100   |

**I recommend using a modern power supply for your C64 or C128!**

PET unlikely feasible because character sets are stored in ROM, no graphics mode and no hardware sprites on original hardware! Maybe modern hardware can suffice.

[^1]: VDC has it own video RAM but it lacks sprites
[^2]: VIC and TED chips lack the hardware sprites
