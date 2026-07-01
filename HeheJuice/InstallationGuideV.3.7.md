<h1 align="center">
  <img loading="lazy" src="Banner.png"/>
</h1>

## Guides For Installing オーブンUI「OvenUI」 V.3.7 Beta [OneUI 6.1]
### Basic Requirements 
- You should have read the GitHub Page Before Installing
- A Unlocked Bootloader and Patched Vbmeta is REQUIRED
- OrangeFox Recovery Installed on your A03s
- Platforms Tool and Adb Driver
- It's Recommended to have this version of Firmware if you have A037F
     - A037FXXS8CYE1
     - A037M Users SHOULD on A037M OneUI 5.1 Firmware ( Untested
- Brain with skills and basic knowledge

### Installation 
1. Keep these following files in a place where you can access
     - The ROM ZIP on your PC and extracted 
     - The Kernel ZIP and Permissiver ZIP on your SD Card or USB Drive
2. Reboot to recovery and Press reboot to fastboot
3. Connect to your PC and Open Platform Tool
4. Typing the following commands
     - fastboot erase system
     - fastboot erase product
     - fastboot erase system_ext
     - fastboot erase vendor
     - fastboot delete-logical-partition product_a
     - fastboot delete-logical-partition product_b
     - fastboot delete-logical-partition system_ext
     - fastboot flash system [FILE]
     - fastboot flash product [FILE]
     - fastboot flash vendor [FILE]
5. Press reboot to recovery on your phone
6. Flash the following files
     - Kernel
     - Permissiver
7. Factory Reset and Reboot to System
