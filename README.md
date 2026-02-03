# HDZero Goggles Firmware mod
This is a QoL modification for the HDZero Goggles Firmware. This fork is a port of my patches from old BoxPro repo to the new goggles monorepo.

Current list of added features:
- RSSI label and number next to the analog RSSI bar
- Scan analog page just like the original "Scan now" for HDZero. Scans all analog channels and allows you to see which is active
- A software rate limit for scroll wheel to prevent glitching (jumping around randomly)

NOTES:
- Use the right side button after analog scanning to go to the next band, and use the roller to select a frequency
- If no active frequencies were detect, scrolling will move to the next page (that is intentional)
- NOT TESTED ON GOGGLES2! I only have the BoxPro, so I only test my changes against it, but the code should run at least.

## How to install
### Temp install
Do this if you just want to try it out.
1. Go to releases and download the `tryit-platform.zip`
2. Inside should be a `develop.sh` and a `HDZGOGGLE`
3. Move those two files to the root directory of your sd card
4. Plug the sd card into the goggles and then turn it on
5. Removing these two files from your sd card will cause the goggle to go back to the original firmware
### Permanent install
Note you can always go back to the original firmware by downloading it from the offical website and flashing it. You don't need the sd card plugged in for this.
1. Download the `HDZERO_xxxx-x.x.x.bin` from releases for your platform
2. Put it in the root directory of your sd card
3. Boot it up, and go to the firmware tab and click update
4. Follow instructions on screen, don't power off!

## Pictures
Note these are taken in the emulator, but I verified it looks the same in the goggles.