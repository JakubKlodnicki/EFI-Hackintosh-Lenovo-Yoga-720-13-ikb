# OpenCore config for installing macOS 11 Big Sur on Lenovo Yoga 720-13IKB

# Credits:
- [OpenCore](https://github.com/acidanthera/OpenCorePkg) Boot
- [Lilu.kext](https://github.com/acidanthera/Lilu/releases/latest)
- [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake.html)

# What is half working:
- Brightness control has a dead zone

# What is working:
- Intel Graphic UHD620
- Realtek ALC236
- Keyboard
- TouchPad and TouchScreen
- Battery and CPU sensor
- Camera and microphone
- Hibernation and wake up
- Intel Dual-Band Wireless-AC 826
- Intel Bluetooth 4.2
- Airdrop and icloud services

# UEFI Setting before install:
- Disable "Intel SGX" (Security -> Intel SGX -> Intel SGX Controller)
- Disable "Secure Boot" (Security -> Secure Boot)
- Switch RAID to AHCI (Configuration -> SATA Controller Mode)
