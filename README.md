# Z370-ITX-AC-macOS
This is a working EFI/Clover configuration complete with config.plist and applicable kexts for macOS 10.13.4.

PC Part Picker build: https://pcpartpicker.com/b/8zFtt6

## macOS version
`10.13.4 (17E202)`

**NOTE:** For *best graphical performance*, you should *connect all displays to
the NVIDIA card*. If you also use the Intel 630 UHD graphics, you will experience
lagging - likely due to macOS's inability to correctly provision rendering
duties to each GPU at the appropriate times.

## System Specs
* ASRock Z370M-ITX/ac
* Intel i7-8700K 3.7GHz
* G.Skill Ripjaws V Series 16GB (2 x 8GB) DDR4-2400 Memory
* Crucial MX300 275GB M.2-2280 Solid State Drive
* Gigabyte GeForce GTX 1050Ti
* Corsair SF 450W 80+ Gold Certified Fully-Modular SFX Power Supply
* IOGEAR Bluetooth 4.0 USB Micro Adapter, GBU521

## Post-install
* Audio install script: https://github.com/toleda/audio_CloverALC/blob/master/audio_cloverALC-130.command.zip
* NVIDIA web drivers: Latest (387.10.10.10.30.107)
* SmUUID and Serial Number generation for iMessage. Search the forums!

## Working
* Displayport Dual 4k monitors
* APFS
* Sleep
* Audio
* FileVault (with UsbKbDxe, included)

The motherboard's built-in Bluetooth and WiFi module does NOT work with macOS.
You will need to get a compatible module for the M.2 slot, or use a USB
Bluetooth dongle (listed above).
