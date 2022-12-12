# 5600g-6800xt-hackintosh

OpenCore version: 0.8.7 <br>
macOS: 13.0.1 (22A400)

| Hardware |                                        |
| -------- | -------------------------------------- |
| CPU      | AMD Ryzen 5 5600G with Radeon Graphics | 
| GPU      | AMD Radeon RX 6800 XT 16 GB            |
| Motherboard | TUF GAMING B550M-PLUS WIFI II       |
| Audio    | Realtek ALC1200                        |

## Normal
1. GPU Accellerate and DRM
2. AMD CPU in OSX
3. Sleep
4. Audio
5. 1.0/2.5G Cable network
6. NVME and Sata Trim
7. ...

## Install
1. [Create the USB](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/#creating-the-usb)
2. Download the EFI
3. [Generate your SMBIOS data](https://github.com/corpnewt/GenSMBIOS)
4. [AMD BIOS Settings](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#amd-bios-settings) [^1]


## Demonstration
![AMD Power Gadget](https://user-images.githubusercontent.com/32976627/207086575-bebc3c34-e355-48a1-a6f4-3dd1839630c4.jpeg)
![cinebench](https://user-images.githubusercontent.com/32976627/207087084-2ae33825-e8f0-4fef-b182-c07dc5494179.jpeg)
![geekbench5-opencl](https://user-images.githubusercontent.com/32976627/207087211-b487d22f-d600-4829-a15f-7357f5a1ddae.png)
![geelbench5-metal](https://user-images.githubusercontent.com/32976627/207087273-6fb814aa-ae1c-4f3d-8fe1-f05362589461.jpeg)


## Thanks
1. OpenCore Team
2. AMD_Vanilla
3. Dortania Install Guide
4. Other community driven projects

[^1]: Remove `npci=0x3000` from boot-args if you are not on a Gigabyte/Aorus or an AsRock motherboard
