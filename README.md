## Thinkpad X270 6genCore EFI for 10.13/10.14.x


|Motherboard|Lenovo ThinkPad X270|

|OS|macOS Mojave 18A389/macOS High Sierra 10.13.6 17G2208|

|CPU|Intel(R) Core(TM) i5-6200U CPU @ 2.30GHz|

|MEM|8 GB  2133MHz|

|DISK|TOSHIBA NVMe 128g SSD|

|Graphics|intel HD Graphics 520 |

|Monitor|1366x768 (12.5 inch)|

|Audio|ALC298 (layout-id:29)|

|WLAN|Bcm94352z|

## DMG
DMG from ：[【daliansky】macOS Mojave 10.14(18A389) with Clover 4670 image](https://blog.daliansky.net/macOS-Mojave-10.14-18A389-Release-with-Clover-4670-original-mirror.html)

## Drivers Working
1. Audio：ALC298，inject ID：29，via AppleALC，hotpatch(fixed@20200310)；
2. Wlan：DW1560/DW1830 Working；
3. Graphics：Intel HD Graphics 520 Working，Platform-id=0x19160002，Patch DVMT；Devices-Properties method；HDMI working；miniDP not tested；
4. Bluetooth working；Sleep/Wake working, fixed led blink after wak, hotpatch(fixed@20200315)；
5. Dual Battery working(if you dont have dual battery, just buy one^_^), Fan RPM working, hotpatch(fixed@20200315);
6. Trackpad working；
7. USB port => SSDT-UIAC.aml working；
8. PCI not modified；
9. Brightness adjust working：`fn+F5`&`fn+F6`

- 3-15-2020

  - fix batt&fan&ptswak 

- 3-10-2020

  - fix alc298 inject 

- 3-9-2020

  - EFI first commit

## Special thanks：
- [daliansky](https://github.com/daliansky) 
