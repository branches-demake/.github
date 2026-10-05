# The Branches Demake Team

A group of unofficial ports of BFDI: Branches (original game by Team Branches)

## Disclaimer
The Branches Demake Team is not affiliated by Team Branches or Jacknjellify.

The Branches Demake Team will not make profits in any way.

[Watch BFDI by jacknjellify](https://www.youtube.com/@BFDI)

[Play BFDI: Branches by Team Branches](https://bfdibranches.com)

## Anti-vibecode policy
We do not take shortcuts to develop the demakes. Please refrain from using LLM models to make it "quick and easy," as it is unreliable, not to mention, hated by the community.

Vibe-coded pull requests will be declined at our discretion.

Anyone repeatedly caught vibe-coding will result in a permaban.

## To do list
Keep in mind there are hardware limitations for each system.

### Original Hardware (Commodore computers and modern derivatives)
| System                          | RAM                    | CPU                                                           | Video              | Feasibility | 
| ------------------------------- | ---------------------- | ------------------------------------------------------------- | ------------------ | ----------- |
| Commodore 64 / 64c / SX-64      | 64 KB                  | MOS 6510 @ 1 MHz                                              | VIC-II             | Good        |
| Commodore 64 + REU 1764         | 320 KB                 | same as C64                                                   | VIC-II             | Excellent   |
| Commodore 64 + SuperCPU         | up to 16 MB            | MOS 6510 @ 1 MHz + WDC W65C816S @ 20 MHz                      | VIC-II             | Excellent   |
| Commodore 128 / 128D            | 128 KB                 | MOS 8502 @ 1-2 MHz + Zilog Z80 @ 4 MHz                        | VIC-IIe + VDC [^1] | Very good   |
| Commodore 128 + REU 1700        | 256 KB                 | same as C128                                                  | VIC-IIe + VDC [^1] | Excellent   |
| Commodore 128 + REU 1750        | 640 KB                 | same as C128                                                  | VIC-IIe + VDC [^1] | Excellent   |
| Commodore 128 + SuperCPU        | up to 16 MB            | MOS 8502 @ 1-2 MHz + Zilog Z80 @ 4MHz + WDC W65C816S @ 20 MHz | VIC-IIe + VDC [^1] | Excellent   |
| Commodore VIC-20                | 5 KB                   | MOS 6502 @ 1 MHz                                              | VIC [^2]           | Very poor   |
| Commodore VIC-20 32 KB          | 32 KB                  | same as VIC-20                                                | VIC [^2]           | Fair        |
| Commodore Plus/4                | 64 KB                  | MOS 7501/8501 @ 1.78 MHz                                      | TED [^2]           | Decent      |
| Commodore 16/116                | 16 KB                  | same as Plus/4                                                | TED [^2]           | Poor        |
| Commodore Amiga 1000            | up to 8.5 MB           | Motorola 68k @ 7.16 MHz                                       | OCS Chipset        | Perfect     |
| Commander X16                   | 512 KB, up to 2 MB     | WDC 65C02 @ 8 MHz                                             | VERA               | Perfect     |
| Mega65                          | 384 KB fast, 8MB Hyper | GS4510 @ 40 MHz                                               | VIC-IV             | Perfect     |

**I highly recommend using a modern power supply for your C64 or C128!**

I also recommend to use an emulator for testing. [VICE emulator](https://vice-emu.sourceforge.io) to emulate Commodore systems and the official [Commander X16 Emulator](https://github.com/x16community/x16-emulator).

PET unlikely feasible because character sets are stored in ROM, no graphics mode and no hardware sprites on original hardware! Maybe modern hardware can suffice.

[^1]: VDC has it own video RAM but it lacks sprites
[^2]: VIC and TED chips lack the hardware sprites
