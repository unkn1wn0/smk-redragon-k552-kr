# Porting SMK Firmware to Redragon K552-KR

This project documents the process of porting SMK to the Redragon K552-KR, which uses a BYK901 (SinoWealth SH68F90-family) MCU.

> Full documentation (progress, notes, diagrams) [here](https://www.notion.so/Porting-SMK-Small-Mechanical-Keyboard-Firmware-on-the-Redragon-K552-KR-34e109dc4528801fb0e7f88505e2872b?source=copy_link)


## Current Status

* Matrix fully reconstructed (6 × 17)
* Pin mapping aligned with SH68F90 TQFP48 layout
* Partial hardware validation completed
* Firmware bring-up in progress


## Goals

* Achieve working SMK firmware on stock MCU (if possible)
* Otherwise, document full matrix for MCU replacement
* Provide a reproducible workflow for similar keyboards


## Acknowledgements

- [SMK](https://github.com/carlossless/smk)
- [libfx2](https://github.com/whitequark/libfx2)
- [LUFA](https://github.com/abcminiuser/lufa)
- [QMK](https://github.com/qmk/qmk_firmware)
