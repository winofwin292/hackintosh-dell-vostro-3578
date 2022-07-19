Dell Vostro 3578
My Specs:
    - CPU: Intel Core i5-8250U
    - GPU: Intel UHD 620 + AMD Radeon 520
    - Memory: 16GB DDR4
    - Wireless/BT: Intel AC3165

What's working:
    - macOS Base
    - Display (1920x1080) with QE/CI
    ! : AMD Radeon 520 is DISABLED via SSDT!
    - Brightness (Can be controlled by pressing Fn + F11/F12)
    - Battery Indicator
    - Sleep 
    - Trackpad (I2C, HID)
    - HDMI with 60Hz or higher with audio
    - VGA Port
    - Camera
    - Headphones, Microphone (Onboard)
    - Internet with cable
    - USB
    - Secure Digital Card (SDCard)

What should I do after installed macOS?:
    - Put EFI Folder to EFS Partition by using Clover Configuration
    - Re-generate SMBIOS: Serial Number, SMUUID, Board-ID and Broad Serial Number
    - Fix USB, HDD-Box, Secure Digital Card (SD Card),... not ejected properly: https://github.com/syscl/Fix-usb-sleep
    - Add your Wifi/Bluetooth kext and snapshot without changing kext's list in config.plist before you install macOS
