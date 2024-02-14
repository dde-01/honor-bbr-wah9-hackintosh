## Honor MagicBook X15 BBR-WAH9

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Processor | i5-10210U|
| Memory | Micron 4ATF51264HZ-3G2J1 2400MHz RAM(2x4) |
| SSD | WD Blue SN570|
| Graphics | Intel UHD Graphics 620 |
| Sound | Conexant CX8070 |
| Wireless | Intel Wi-Fi 9560D2W & Intel BT 5.1 |
| Touchpad | I2C HID |

**Notes**

OpenCore 0.9.5 - macOS Sonoma 14.0(updated)

`sudo diskutil mount [disk]`  
`sudo cp -R /Volumes/BDU/EFI/OC/Kexts/VoodooHDA.kext /Library/Extensions`

Almost all functionality works, except: AirDrop & WPA3 Personal.  
Worked in conjunction with an external monitor AOC 24P2Q (Sound is not transmitted via hdmi. There were no problems with fonts)

<hr>

![screenshot-01](/images/screenshot-01.png)