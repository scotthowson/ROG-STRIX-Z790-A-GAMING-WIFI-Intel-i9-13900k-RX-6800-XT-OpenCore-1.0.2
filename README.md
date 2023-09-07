# OpenCore 0.9.4 macOS Ventura Hackintosh

A Hackintosh EFI & guide for macOS Ventura & Sonoma: Unveiling Soon! 🚀

![Desktop Screenshot](desktop-blur.png)

Welcome to my Raptor Lake and 13th Gen Intel Hackintosh Repository!

Whether you're a seasoned Hackintosh enthusiast or a curious newcomer, this repository offers a meticulously curated guide, drivers, and tools, all rigorously tested and fine-tuned for seamless compatibility, stability, and peak performance. Trust me as your go-to source for maximizing your Raptor Lake-based Hackintosh system's potential!

Stay tuned for an exciting revelation that will transform your computing experience. Sonoma is on the horizon, and it's bringing innovation, power, and style like never before.

Prepare to be amazed! 🔥 #SonomaIsComing

## Screenshots:

**About This Mac:**
![About This Mac Screenshot](About.png)

**Geekbench 6 Results:**

**CPU Scores:**
- **13th Gen Intel® Core i9-13900k**
![CPU Score Screenshot](geekbench6-score.png)

**GPU Scores:**
- **ASRock AMD Radeon RX 6800 XT**
  - Highest GPU Score: **223247**
![GPU Score Screenshot](geekbench-6-gpu-highestscore.png)
![GPU Scores Screenshot](geekbench-6-scores-gpu.png)

> [!WARNING]
> I hereby disclaim any responsibility and liability for any damages that may arise from the use of information provided within this repository.

## Specifications

**Hardware**|**Model**|**Status**
---|---|---
Motherboard|ASUS ROG STRIX Z790-A GAMING WIFI D4|❓
CPU|13th Gen Intel® Core i9-13900k|✅
RAM|64GB Corsair Vengeance RGB Pro 32GB (4 x 16GB)|✅
GPU|AMD Radeon™ RX 6800 XT Phantom Gaming D (16 GB)|✅
Storage|Intel SSDPEKNW512GB NVME|✅
Ethernet|Intel® Ethernet Controller I226-V|✅
Wi-Fi|Intel® Wi-Fi 6E AX211|✅

> [!NOTE]
> These specifications are tailored to my unique setup and may not be universally applicable. Your system may require adjustments and customization for optimal performance.

**Key Considerations:**

- **Processor Compatibility:** The Intel Core i9-13900K is a powerful CPU, and while OpenCore 0.9.4 provides a versatile platform for macOS, it's essential to ensure that all required kexts and configurations are up-to-date and compatible with this CPU model for optimal performance.

- **ASUS Z790-A Gaming WiFi D4:** This motherboard choice is versatile for Hackintosh setups, but it's crucial to research and select compatible kexts and configurations tailored to this specific motherboard model to ensure stability and functionality.

- **macOS Ventura:** As macOS Ventura is a relatively new release, staying informed about updates and compatibility with your hardware is vital. OpenCore 0.9.4 may require adjustments and updates to accommodate the latest macOS version.

**Best Practices:**

- **Kext Management:** Keep an eye on kext updates and ensure you're using versions compatible with macOS Ventura, i9-13900K, and your ASUS motherboard. Always download kexts from reputable sources.

- **Configuration Backups:** Regularly back up your OpenCore configuration files to avoid data loss in case of unexpected issues. This practice allows you to revert to a stable configuration if needed.

- **Community Support:** Leverage online forums and communities dedicated to Hackintosh setups, as they can provide valuable insights, troubleshooting tips, and updates regarding macOS Ventura compatibility.

- **Update OpenCore:** As new versions of OpenCore are released, consider updating to take advantage of improved features, bug fixes, and better compatibility with the latest macOS updates.

**Conclusion:**

Utilizing OpenCore 0.9.4 with macOS Ventura on your i9-13900K and ASUS Z790-A Gaming WiFi D4 setup can deliver a high-performance Hackintosh experience. However, staying informed about hardware compatibility, keeping your kexts and configurations up-to-date, and seeking community support when needed are essential steps to ensure a stable and smooth-running system.

> [!IMPORTANT]
> <b>Remember that the Hackintosh community is a valuable resource, and with proper research and maintenance, you can enjoy the benefits of macOS Ventura on your unique hardware configuration.</b>

## Hackintosh Community Resources

- **[r/hackintosh (Reddit)](https://www.reddit.com/r/hackintosh/):** A popular subreddit dedicated to Hackintosh discussions, troubleshooting, and community support.

- **[tonymacx86](https://www.tonymacx86.com/):** This website offers Hackintosh guides, tools, and a community forum where users share their experiences and solutions.

- **[InsanelyMac](https://www.insanelymac.com/):** A longstanding Hackintosh forum with a wealth of resources, guides, and a community of Hackintosh enthusiasts.

- **[OpenCore Bootloader](https://dortania.github.io/OpenCore-Install-Guide/):** The official OpenCore documentation is an essential resource for setting up and configuring your Hackintosh.

- **[Hackintosh.com](https://hackintosh.com/):** This site offers various Hackintosh guides, downloads, and a forum for discussions and support.

- **[OSx86 Project](https://www.osx86project.org/):** An older community that still provides useful information and resources for Hackintosh users.

- **GitHub:** Many Hackintosh projects and drivers can be found on GitHub. Search for specific hardware or software-related repositories to find the latest updates and contributions.

- **Hackintosh Discord Servers:** There are several Discord servers dedicated to Hackintosh enthusiasts. You can search for them on Discord or join the tonymacx86 Discord server, which often has active discussions.

## Kexts

> [!IMPORTANT]
> Essential kexts crucial for your success.

1. **Lilu Kext**
   - [Download Lilu](https://github.com/acidanthera/Lilu/releases)

2. **VirtualSMC Kexts**
   - [Download VirtualSMC](https://github.com/acidanthera/VirtualSMC/releases)

3. **WhateverGreen**
   - [Download WhateverGreen](https://github.com/acidanthera/WhateverGreen/releases)

4. **AppleALC**
   - [Download AppleALC](https://github.com/acidanthera/AppleALC/releases)

5. **Airportitlwm**
   - [Download Airportitlwm](https://github.com/OpenIntelWireless/itlwm/releases)

> [!IMPORTANT]
> Non-essential kexts that, while optional, can enhance system stability.

6. **CPUFriend Kext**
   - [Download CPUFriend](https://github.com/acidanthera/CPUFriend/releases)

7. **CpuTopologyRebuild**
   - [Download CpuTopologyRebuild](https://github.com/b00t0x/CpuTopologyRebuild/releases)

> [!NOTE]
> For optimal results following any configuration edits, it is recommended to perform an NVRAM reset.

## BIOS

**Disable:**

- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- VT-d (can be enabled if you set DisableIoMapper to YES)
- Compatibility Support Module (CSM)
- Thunderbolt (For initial install, as Thunderbolt can cause issues if not set up correctly)
- Intel SGX
- Intel Platform Trust
- CFG Lock (MSR 0xE2 write protection)
  - This must be off. If you can't find the option, then ENABLE AppleXcpmCfgLock. Your hack will not boot with CFG-Lock enabled.

**Enable:**

- VT-x
- Above 4G decoding
  - This must be on. If you can't find the option, then add npci=0x2000 to boot-args. Do not have both this option and npci on boot-args enabled at the same time. When enabling Above4G, Resizable BAR Support may become available on some motherboards. Please ensure this is DISABLED instead of set to Auto.
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Windows 8.1/10 UEFI Mode
- SATA Mode: AHCI

## Hackintosh Checklist - What's Working?

> [!NOTE]
> If anything doesn't work for you, report the issue [here](https://github.com/IllSaft/ROG-STRIX-Z790-A-GAMING-WIFI-Intel-i9-13900k-RX-6800-XT-OpenCore-0.9.4/issues).

1. **OpenCore Booting**
    - [x] Correct OS choices shown in OpenCore Menu/GUI
    - [ ] Keyboard shortcuts working (see details below)
        - CMD+V — verbose mode.
    - [x] NVRAM working (Verifying if you have working NVRAM)
        - Apple -> System Preferences -> Startup Disk (uses NVRAM).
    - [x] Security (especially SIP) use Menu Bar SIP Detector
    - [x] FileVault
    - [x] Multibooting

2. **Display**
    - [x] Display via HDMI
    - [x] Display via HDMI
    - [x] Display via DisplayPort
    - [x] Display via DVI
    - [x] Resolution
    - [x] Refresh rates
    - [x] Multimonitor displays

3. **Graphics Acceleration**
    - [x] dGPU dedicated GPU
        - In Terminal: gfxutil -f GFX0 or check in IORegistryExplorer
    - [x] QE/CI (full acceleration requires both Quartz Extreme and Core Image)
        - Check for transparent menu bar and fast smooth UI.
    - [x] VDA (Video Decode Acceleration framework)
        - Hackintool -> System -> System -> VDA Decoder (should show 'fully supported')
    - [x] Metal
        - System Information -> Graphics/Displays -> Metal: Supported
        - GLView
        - Geekbench -> Compute -> Metal

4. **Audio**
    - [x] Audio out (Audio MIDI Setup)
    - [x] Audio in
    - [x] Front panel audio connectors
    - [x] Audio over HDMI
    - [x] Audio quality

5. **Sleep & Power**
    - [x] Manual Sleep (Apple menu -> Sleep)
    - [x] Auto Sleep (System preferences -> Energy Saver)
    - [x] Wake by keyboard
    - [x] Wake by mouse/trackpad
    - [x] Sleep by Press and hold power button for 1.5 seconds
    - [x] Shutdown (from Apple menu)
    - [x] Restart (from Apple menu)

6. **CPU**
    - [x] CPU Power Management (Optimizing Power Management)
        - Check with IORegistryExplorer
    - [ ] Temperatures and stability with 100% CPU
        - Use Prime95 Torture Test

7. **Disk**
    - Test with Blackmagic Disk Speedtest
    - [x] NVMe SSD
        - Write: 878.3 MB/s
        - Read: 1388.5 MB/s
    - [x] SATA SSD
        - Write: 103.4 MB/s
        - Read: 454.1 MB/s
    - [x] TRIM support (System Information -> SATA -> SSD drive)

> [!NOTE]
> Quick Tip: Enabling TRIM support on your Hackintosh:
> To enable trim support, simply open up a Terminal and type in the following command: `sudo trimforce enable`

8. **Keyboard**
    - [x] Option/Command correctly mapped in macOS
        - For PC Keyboards swap in: System preferences -> Keyboard -> Modifier Keys
    - [x] Fn keys working

9. **USB**
    - Use USBMap
    - Test external drives with Blackmagic Disk Speedtest
    - [x] USB 2 ports
    - [x] USB 2 on USB 3 ports
    - [x] USB 3 and 3.1 ports (check transfer speed during copy)
    - [x] USB C ports
    - [x] Camera (Photo Booth, Facetime, Zoom)

10. **Ethernet**
    - [x] Gigabit LAN (System preferences -> Network -> Ethernet -> Advanced -> Hardware -> Speed should be 1000baseT)

11. **Wi-Fi & Bluetooth**
    - [x] Wi-Fi transmission speed (Option Click -> Wifi menu bar icon -> check Tx Rate)
    - [x] Bluetooth devices (trackpad, mouse, keyboard, headset)
    - [ ] AirDrop (test with iDevices)
    - [ ] AirPlay to Mac (macOS Monterey or later, test with iOS 14 or later devices)
        - Tap the AirPlay icon on your Apple device to share videos to your Hackintosh
    - [ ] Handoff (System requirements for Continuity and Use Continuity which requires macOS Catalina & iOS 13+)
    - [ ] Sidecar requires macOS Catalina or later and a compatible iPad using iPadOS 13 or later.

> [!IMPORTANT]
> Having issues with AirDrop. Working on a solution. :tada:

12. **OS Features**
    - [x] iMessage, FaceTime, App Store, iTunes Store
    - [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime, Netflix, and others)

---

**Disclaimer:**

This repository is intended for educational and experimental purposes only. Using macOS on non-Apple hardware, also known as Hackintosh, may violate Apple's End User License Agreement (EULA). The process involves potential risks, including but not limited to data loss or instability. By using the information and resources provided here, you agree that you are solely responsible for any consequences that may arise. Always ensure you have proper backups and proceed at your own risk.

**Thank You:**

I would like to express our gratitude to the Hackintosh community, contributors, and developers who have made this repository possible. Your dedication, support, and shared knowledge have been invaluable in creating a thriving ecosystem for macOS enthusiasts. Together, we continue to explore new horizons and push the boundaries of what's achievable with Hackintosh.

Thank you for being a part of this journey!

<h6>Footnotes:</h6>

[^1]: An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[^2]: Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[^3]: A Lilu plugin providing patches to select GPUs on macOS. Requires Lilu 1.5.6 or newer.
[^4]: An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. AppleALCU can be used for systems with digital-only audio.
[^5]: An Intel Wi-Fi Adapter Kernel Extension for macOS, based on the OpenBSD Project.
[^6]: A Lilu plug-in for dynamic power management data injection.
[^7]: An experimental Lilu plugin that optimizes Alder Lake / Raptor Lake's heterogeneous core configuration.
[^8]: When the HideAuxiliary option is Enabled, you need to press the Space Bar Key on your Keyboard to show all the other options in the picker.
