# Clover Bootloader Configuration

## Specification
 - CPU : Intel Core i5 5200U
 - RAM : 8 GB 1600 Mhz DDR3L
 - iGPU : Intel HD 5500 (Not Work)
 - dGPU : NVIDIA 930M (Not Work Too)

## Whats Work ??
 - All work except that two GPU Because There's no 5th Gen driver

## How to install ???
 - copy this repo with git clone https://github.com/sulthonuladib/a455lf-mavericks
 - Create USB bootable with createinstallmedia method from installer
 - Make sure u boot with UEFI mode
 - copy this file to EFI folder of your ESP. example: /Volumes/ESP/EFI
 - then boot to your USB
