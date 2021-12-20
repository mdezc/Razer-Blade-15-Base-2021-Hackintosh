# Razer-Blade-15-Base-2021-Hackintosh
Configuration for getting macOS Monterey to run on a Razer Blade 15 2021 using OpenCore

### Note
Note that the SSD drive that came with the Razer didn't work for me. Even with the correct EFI and config.plist my Big Sur installer kept freezin halfway through the install proess. It was only after trying a different drive (Samsung 970 EVO) that I was able to complete the installation.

## What's working
- WiFi
- Battery
- Trackpad
- Keyboard backlight
- Sleep/wake
- Sound
- Display 144hz
- iServices
- Bluetooth

## What's not working
- Thunderbolt port for display
- HDMI
- AirDrop
- Fan speed sensor

## Not tested
- Handoff
- Filevault

# Credits
- Mostly a fork from https://github.com/Narcoroni/Razer-Blade-2021-Hackintosh with minor changes.
- Thanks to Lacks_Sense_Of_Humor on reddit for the trackpad SSDT: https://www.reddit.com/r/hackintosh/comments/olfvdf/succesfull_install_macos_bigsur_114_on_an/ 

