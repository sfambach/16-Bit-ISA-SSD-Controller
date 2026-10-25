# 16-Bit-ISA-SSD-Controller

**16-Bit ISA SSD-Controller**

16-bit ISA card for 286, 386 and 486 PCs with **SATA ports for SSDs**. Technically it is a **standard AT IDE controller** (1F0h/170h, IRQ 14/15), so the mainboard BIOS, the XT-IDE Universal BIOS (AT build) and standard DOS drivers work with it. Up to four SSDs in two channels.

Sister project of [8-Bit-ISA-SSD-Controller](https://github.com/sfambach/8-Bit-ISA-SSD-Controller) (8-bit, XT-IDE compatible).

**Status: concept.** Nothing has been built or tested yet.

## Features (planned)

- Standard AT IDE, two channels (primary + secondary, master + slave each), PIO
- Up to four SATA ports via plug-on IDE-to-SATA converter boards (JM20330 class)
- Optional ROM socket (28C256) for the XT-IDE Universal BIOS AT build (LBA on old BIOSes)
- Addresses and IRQs by DIP switch / jumper, through-hole parts

Details: [docs/concept.md](docs/concept.md)

## License

- Hardware: [CERN-OHL-S-2.0](LICENSE)
- Documentation: CC BY-SA 4.0
- XT-IDE Universal BIOS (GPL-2) – not included

## AI disclosure

This project is developed with the help of AI (Claude by Anthropic). Design decisions and testing are done by Stefan Fambach.

## Author

Stefan Fambach (SteFam) – https://www.fambach.net
