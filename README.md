# macOS-Thinkpad-T430-OC
EFI folder for hackintosh development with OpenCore. Work in progress.
Made with OC 0.6.5
- Remember to generate SMBIOS values! See https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html#starting-point for full info.

# Working:
- wifi
- power on/off
- USB (all 4!)
- iServices
- Audio (through replacing AppleALC.kext with VoodooHDA.kext in post-install)
- Microphone (on/off button not working)
- Mouse (working OK, scrolling function only on Firefox for trackpoint)

# Not working:
- Sleep (only display off)
- Battery Readout 
- App Store (recently stopped, worked with this setup)
- Bluetooth (unusure, not present on this system)
- Airdrop

# Specs:
- Lenovo Thinkpad T430
- Intel i5-3320m Ivy Bridge 
- Intel HD 4000, 1600x900
- Audio codec: ALC269
- MacOS on CD drive SSD (with caddy)

Tested to boot with MacOS High Sierra and Mojave. This will be updated as progress is made. Credit to OpenCore team, tonymacx86, r/hackintosh, corpnewt and Rehabman for resources.
