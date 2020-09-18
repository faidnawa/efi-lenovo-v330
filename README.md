# efi-lenovo-v330
Specifications :
- Processor : Intel Core i5 8250U 1.6-3.4GHz
- IGPU : Intel UHD Graphics 620
- RAM : 8GB DDR4 PC19200 (2400Mhz)
- Storage : M2 NVMe Adata SX8200 Pro 256GB + HDD seagate 1TB
- Wifi : Intel NGFF AC 3165 + Bluetooth
- Audio : Realtek ALC256
- Screen Size : 14"
- Resolusi Layar : 1920 x 1080 (Full HD)
- CLover Version : Clover r4674
- Ethernet : RealtekRTL8111
- Touchpad : I2C Interface
- Boot Mode : UEFI GPT
- OS : macOS Mojave 10.14.3 Build 18D42 + Windows 10
 

Work??:
- QE/CI Graphics
- Audio Out and Headphone Out
- Touchpad
- Keyboard
- Brightness
- Battery Indicator
- FN + Brightness Button Up/Down
- All USB Port
- Bluetooth
- Restart,and Shutdown
Not Work???
-Sleep

-fix HDMI port and HDMI audio with https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md
-fix intel wifi card 3165 with itlwm v1.1.0 stable https://openintelwireless.github.io/
and HeliPort v1.0.0 https://github.com/OpenIntelWireless/HeliPort/releases
