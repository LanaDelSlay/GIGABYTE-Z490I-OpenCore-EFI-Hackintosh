# GIGABYTE Z490I OpenCore Ventura Hackintosh EFI

OpenCore EFI bootloader used for booting macOS Ventura on custom hardware, 
fast boot time and reliable operation, without crashes.

## Description

### This bootloader was designed for my build which consists of the following:

- GIGABYTE Z490I
- i7-10700K (Comet Lake)
- Radeon RX 580
- 32GB RAM
- 1TB SATA SSD

## What Works?

Everything except continuity, to make that work you require a special wireless card obtainable online. ( I have one it’s just doa)

OnBoard ethernet works too - most likely will require [flashing](https://github.com/5T33Z0/Gigabyte-Z490-Vision-G-Hackintosh-OpenCore/blob/main/I225-V_FIX.md#option-2-flashing-a-custom-firmware) the ethernet port’s firmware.

OnBoard Wi-Fi wasn’t attempted, I will buy another continuity compatible 
lan card for plug and play compatibility eventually. 

## How To Use

If your PC hardware is similar to mine you may be able to create a 
bootable Mac installer using a USB, then mount the EFI partition (Many 
ways to do this on the Mac I used to build the hackintosh, I used 
[this](https://github.com/corpnewt/MountEFI) but you can use anything.), 
and drag and drop the EFI folder into the EFI drive, and that would be it. 

Otherwise, if your hardware is different you may want to start from 
[scratch](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html) 
and share your config or look for one similar to your own specs, then 
modify it according to what the guide above will teach you. 


