# OpenCore 0.9.4 macOS Ventura Hackintosh
A Hackintosh EFI & guide for macOS Ventura & Sonoma: Unveiling Soon! 🚀
 ![Alt text](desktop.png)

Welcome to my Raptor Lake Hackintosh Repository!

Whether you're a seasoned Hackintosh enthusiast or a curious newcomer, this repository offers a meticulously curated guide, drivers, and tools, all rigorously tested and fine-tuned for seamless compatibility, stability, and peak performance. Trust me as your go-to source for maximizing your Raptor Lake-based Hackintosh system's potential!

Stay tuned for an exciting revelation that will transform your computing experience. Sonoma is on the horizon, and it's bringing innovation, power, and style like never before.

Prepare to be amazed! 🔥 #SonomaIsComing

# Screenshots:
About this Mac:
![Alt text](About.png) 

Geekbench 6 Results:

CPU Scores:
<b>13th Gen Intel® Core i9-13900k</b>
![Alt text](geekbench6-score.png)

GPU Scores:
<b>ASRock AMD Radeon RX 6800 XT</b>

Highest GPU Score: <b>223247</b>
![Alt text](geekbench-6-gpu-highestscore.png)
![Alt text](geekbench-6-scores-gpu.png)

> [!WARNING]
> I hereby disclaim any responsibility and liability for any damages that may arise from the use of information provided within this repository.
## Specifications

<table>
  <tbody>
    <tr>
      <td align="left"><br>Hardware<br>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;</span>
      </td>
      <td align="center">Model<br>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;</span>
      </td>
      <td align="center"><br>Status<br>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
        <span>&nbsp;&nbsp;</span>
      </td>
    </tr>
    <tr>
        <td align="left">Motherboard</td>
        <td align="center">ASUS Z790-A GAMING WIFI D4</td>
        <td align="center">	❓ </td>
    </tr>
    <tr>
        <td align="left">CPU</td>
        <td align="center">13th Gen Intel® Core i9-13900k</td>
        <td align="center">	✅ </td>
    </tr>
    <tr>
        <td align="left">RAM</td>
        <td align="center">64 GB ( Corsair DDR4 3600MHz 16GB x 4 )</td>
        <td align="center">	✅ </td>
    </tr>
    <tr>
        <td align="left">GPU</td>
        <td align="center">ASRock AMD Radeon RX 6800 XT ( 16 GB )</td>
        <td align="center">	✅ </td>
    </tr>
    <tr>
        <td align="left">Storage</td>
        <td align="center">Intel SSDPEKNW512GB NVME</td>
        <td align="center">	✅ </td>
    </tr>
    <tr>
        <td align="left">Ethernet</td>
        <td align="center">Intel® Ethernet Contoller I226-V</td>
        <td align="center">	✅ </td>
    </tr>
    <tr>
        <td align="left">Wi-fi</td>
        <td align="center">Intel® Wi-Fi 6E AX211</td>
        <td align="center">	✅ </td>
    </tr>
  </tbody>
</table>

> [!NOTE]
> These specifications are tailored to my unique setup and may not be universally applicable. Your system may require adjustments and customization for optimal performance.

## Kexts：
> [!IMPORTANT]
> Essential kexts crucial for your success.

1. Lili Kext
   - https://github.com/acidanthera/Lilu/releases [^1]
2. VirtualSMC Kexts
   - https://github.com/acidanthera/VirtualSMC/releases [^2]
3. WhateverGreen
   - https://github.com/acidanthera/WhateverGreen/releases [^3]
4. AppleALC
   - https://github.com/acidanthera/AppleALC/releases [^4]
5. Airportitlwm
   - https://github.com/OpenIntelWireless/itlwm/releases [^5]
> [!IMPORTANT]
> Non-essential kexts that, while optional, can enhance system stability.

6. CPUFriend Kext
   - https://github.com/acidanthera/CPUFriend/releases [^6]
7. CpuTopologyRebuild
   - https://github.com/b00t0x/CpuTopologyRebuild/releases [^7]

> [!NOTE]
> For optimal results following any configuration edits, it is recommended to perform an NVRAM reset. [^8]

## Key Considerations:

    Processor Compatibility: The Intel Core i9-13900K is a powerful CPU, and while OpenCore 0.9.4 provides a versatile platform for macOS, it's essential to ensure that all required kexts and configurations are up-to-date and compatible with this CPU model for optimal performance.

    ASUS Z790-A Gaming WiFi D4: This motherboard choice is versatile for Hackintosh setups, but it's crucial to research and select compatible kexts and configurations tailored to this specific motherboard model to ensure stability and functionality.

    macOS Ventura: As macOS Ventura is a relatively new release, staying informed about updates and compatibility with your hardware is vital. OpenCore 0.9.4 may require adjustments and updates to accommodate the latest macOS version.

Best Practices:

    Kext Management: Keep an eye on kext updates and ensure you're using versions compatible with macOS Ventura, i9-13900K, and your ASUS motherboard. Always download kexts from reputable sources.

    Configuration Backups: Regularly back up your OpenCore configuration files to avoid data loss in case of unexpected issues. This practice allows you to revert to a stable configuration if needed.

    Community Support: Leverage online forums and communities dedicated to Hackintosh setups, as they can provide valuable insights, troubleshooting tips, and updates regarding macOS Ventura compatibility.

    Update OpenCore: As new versions of OpenCore are released, consider updating to take advantage of improved features, bug fixes, and better compatibility with the latest macOS updates.

Conclusion:

Utilizing OpenCore 0.9.4 with macOS Ventura on your i9-13900K and ASUS Z790-A Gaming WiFi D4 setup can deliver a high-performance Hackintosh experience. However, staying informed about hardware compatibility, keeping your kexts and configurations up-to-date, and seeking community support when needed are essential steps to ensure a stable and smooth-running system.

Remember that the Hackintosh community is a valuable resource, and with proper research and maintenance, you can enjoy the benefits of macOS Ventura on your unique hardware configuration.
## BIOS：

Adding Info here soon :) Thanks!

## Hackintosh Checklist - Whats Working?：
> [!NOTE]
> If anything does't work for you, report the issue here:<br>
https://github.com/IllSaft/ROG-STRIX-Z790-A-GAMING-WIFI-Intel-i9-13900k-RX-6800-XT-OpenCore-0.9.4/issues
1. OpenCore Booting
    - [x] Correct OS choices shown in OpenCore Menu/GUI
    - [ ] Keyboard shortcuts working (see details below)
        - CMD+V — verbose mode.
    - [x] NVRAM working Verifying if you have working NVRAM
        - Apple -> System Preferences -> Startup Disk (uses NVRAM).
    - [x] Security (especially SIP) use Menu Bar SIP Detector
    - [x] FileVault
    - [x] Multibooting
2. Display
    - [x] Display via HDMI
    - [x] Display via HDMI
    - [x] Display via DisplayPort
    - [x] Display via DVI
    - [x] Resolution
    - [x] Refresh rates
    - [x] Multimonitor displays
3. Graphics Acceleration
    - [x] dGPU dedicated GPU
        - In Terminal: gfxutil -f GFX0 or check in IORegistryExplorer
    - [x] QE/CI (full acceleration requires both Quartz Extreme and Core Image)
        - Check for transparent menu bar and fast smooth UI.
    - [x] VDA (Video Decode Acceleration framework)
        - Hackintool -> System -> System -> VDA Decoder (should show 'fully supported')
    - [x] Metal
        - System Information -> Graphics/sDisplays -> Metal: Supported
        - GLView
        - Geekbench -> Compute -> Metal
4. Audio
    - [x] Audio out (Audio MIDI Setup)
    - [x] Audio in
    - [x] Frontpanel audio connectors
    - [x] Audio over HDMI
    - [x] Audio quality
5. Sleep & Power
    - [x] Manual Sleep (Apple menu -> Sleep)
    - [x] Auto Sleep (System preferences -> Energy Saver)
    - [x] Wake by keyboard
    - [x] Wake by mouse/trackpad
    - [x] Sleep by Press and hold power button for 1.5 seconds
    - [x] Shutdown (from Apple menu)
    - [x] Restart (from Apple menu)
6. CPU
    - [x] CPU Power Management Optimizing Power Management
        - Check with IORegistryExplorer
    - [ ] Temperatures and stability with 100% CPU
        - Use Prime95 Torture Test
7. Disk
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
> To enable trim support, simply open up a Terminal, and type in the following command.<br>
> <b>sudo trimforce enable</b>

8. Keyboard
    - [x] Option/Command correctly mapped in macOS
        - For PC Keyboards swap in: System preferences -> Keyboard -> Modifier Keys
    - [x] Fn keys working
9. USB
    - Use USBMap
    - Test external drives with Blackmagic Disk Speedtest
    - [x] USB 2 ports
    - [x] USB 2 on USB 3 ports
    - [x] USB 3 and 3.1 ports (check transfer speed during copy)
    - [x] USB C ports
    - [x] Camera (Photo Booth, Facetime, Zoom)
10. Ethernet
    - [x] Gigabit LAN (System preferences -> Network -> Ethernet -> Advanced -> Hardware -> Speed should be 1000baseT)
11. Wifi & Bluetooth
    - [x] Wifi transmission speed (Option Click -> Wifi menu bar icon -> check Tx Rate)
    - [x] Bluetooth devices (trackpad, mouse, keyboard, headset)
    - [ ] AirDrop (test with iDevices)
    - [ ] AirPlay to Mac (macOS Monterey or later, test with iOS 14 or later devices)
        - tap the AirPlay icon on your Apple device to share videos to your Hackintosh
    - [ ] Handoff System requirements for Continuity and Use Continuity which requires macOS Catalina & iOS 13+
    - [ ] Sidecar requires macOS Catalina or later and a compatible iPad using iPadOS 13 or later.
> [!IMPORTANT]
> Having issues with AirDrop. Working on a solution. :tada:
12. OS Features
    - [x] iMessage, FaceTime, App Store, iTunes Store
    - [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)


<h6>Footnotes:</h6>

[^1]: An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[^2]: Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[^3]: A Lilu plugin providing patches to select GPUs on macOS. Requires Lilu 1.5.6 or newer.
[^4]: An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications. AppleALCU can be used for systems with digital-only audio.
[^5]: An Intel Wi-Fi Adapter Kernel Extension for macOS, based on the OpenBSD Project.
[^6]: A Lilu plug-in for dynamic power management data injection.
[^7]: An experimental Lilu plugin that optimizes Alder Lake / Raptor Lake's heterogeneous core configuration.
[^8]: When the HideAuxiliary option is Enabled, you need to press the Space Bar Key on your Keyboard to show all the other options in the picker.