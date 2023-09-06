# ROG-STRIX-Z790-A-GAMING-WIFI-Intel-i9-13900k-RX-6800-XT-OpenCore-0.9.4
 
Hackintosh EFI for macOS Ventura & Sonoma (WIP)

## Specifications
> [!WARNING]
> I do not take any responsibility and not liable for any damage caused by use of information through this repository.

> [!NOTE]
> These are my custom specifications and it may not work for you & require tweaking.
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
        <td align="left">Ethernet</td>
        <td align="center">Intel® Wi-Fi 6E AX211</td>
        <td align="center">	✅ </td>
    </tr>
  </tbody>
</table>

## Kexts：
> [!IMPORTANT]
> Crucial information necessary for users to succeed.

1. Lili Kext
   - https://github.com/acidanthera/Lilu/releases [^1]
2. VirtualSMC Kexts
   - https://github.com/acidanthera/VirtualSMC/releases [^2]
3. WhateverGreen
   - https://github.com/acidanthera/WhateverGreen/releases [^3]
4. VirtualSMC Kexts
   - https://github.com/OpenIntelWireless/itlwm/releases [^2]

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:


## BIOS：

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].


<h6>Footnotes:</h6>
[^1]: An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[^2]: Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[^3]: A Lilu plugin providing patches to select GPUs on macOS. Requires Lilu 1.5.6 or newer.
[^4]: An Intel Wi-Fi Adapter Kernel Extension for macOS, based on the OpenBSD Project.