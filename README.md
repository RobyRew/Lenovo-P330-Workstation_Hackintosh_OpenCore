# Hackintosh Guide for **Lenovo P330 Workstation Tower** aka **30C6S5GV00** model.

**This guide it's updated to OpenCore 0.7.3 and not tested on any device.**
<!-- shields -->
<div>
    <!-- downloads -->
    <a href="https://github.com/RobyRew/Lenovo-P330-Workstation-Tower_Hackintosh_OpenCore/releases">
        <img src="https://img.shields.io/github/downloads/RobyRew/Lenovo-P330-Workstation-Tower_Hackintosh_OpenCore/total" alt="downloads"/>
    </a>
    <!-- version -->
    <a href="https://github.com/RobyRew/Lenovo-P330-Workstation-Tower_Hackintosh_OpenCore/releases/latest">
        <img src="https://img.shields.io/github/release/RobyRew/Lenovo-P330-Workstation-Tower_Hackintosh_OpenCore.svg" alt="latest version"/>
    </a>
    <!-- platform -->
    <a href="https://github.com/RobyRew/Lenovo-P330-Workstation-Tower_Hackintosh_OpenCore">
        <img src="https://img.shields.io/badge/platform-macOS-lightgrey.svg" alt="platform"/>
    </a>
</div>
</br></br>

![Lenovo-P330-Workstation-Tower running macOS Big Sur](/Docs/Images/Lenovo-P330-Workstation-Tower-macOS.png)

[Lenovo Page](https://pcsupport.lenovo.com/id/en/products/workstations/thinkstation-p-series-workstations/thinkstation-p330/30c6/30c6s5gv00?linkTrack=Homepage%3ABody_Search%20Products&searchType=5&keyWordSearch=30C6S5GV00) *This PC is the property of the **INS Baix Camp** institute*


## Specs:
| Component | Name |
|:--- |:---:|
| Motherboard:  | LENOVO 3138 **C246** |
| CPU: | Intel i7-8700 |
| RAM: | 16GB **SK Hyinix** HMA82GU6CJR8N-VK 1333MHz |
| iGPU: | Intel UHD 630 (Desktop) |
| dGPU: | NVIDIA Quadro P4000 (DISABLED) |
| SATA SSD: | WDC PC SA530 SDATB8Y256G1001 |
| HDD: | Seagate ST1000DM003-1SB102 |
| Audio: | RealTek idk |
| Ethernet: | Intel I219-LM |
| Monitor: |  Lenovo T24i-10  |

### Working
- [x] 

### Not working
- dGPU (Any support in Mojave and up).


```bash
```

# INSTALLATION GUIDE

---

## Making the Booteable USB

### From macOS:
[**Link to Apple's Guide**](https://support.apple.com/en-us/HT201372)

**Download installers:** [Monterrey Beta 6](http://swcdn.apple.com/content/downloads/45/34/071-79810-A_PHL4H4X2JM/6mnb23uh2somxqw1jkxm2mos6op8qjcij8/InstallAssistant.pkg)(Execute de .pkg to extract the installer) - [Big Sur](https://itunes.apple.com/us/app/macos-big-sur/id1526878132) - [Catalina](https://itunes.apple.com/us/app/macos-catalina/id1466841314) - [Mojave](https://itunes.apple.com/us/app/macos-mojave/id1398502828) - [High Sierra](https://itunes.apple.com/us/app/macos-high-sierra/id1246284741)

1. Connect a >=16 GB pendrive.
2. Open *Disk Utility* and Erase the USB with the name: *MyVolume*.
3. Open *Terminal* and use the proper commands for your macOS installer:
- Monterrey: `sudo /Applications/Install\ macOS\ 12\ Beta.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Big Sur: `sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Catalina: `sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Mojave: `sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- High Sierra: `sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`

![Terminal](/Docs/Images/Guide/BootableUSB.png)

### From Windows:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)

### From Linux:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html)


---

# BIOS Settings:
- Make Sure you have [Latest BIOS vM1VKT46A](Lenovo-P330-Workstation-Tower)
- After Updating the BIOS, stock configuration works, so don't worry about this part.


# Credits

[Apple](https://apple.com) (macOS)

[OpenCore Team](https://github.com/acidanthera/OpenCorePkg) (Bootloader)

[Dortania](https://dortania.github.io/OpenCore-Install-Guide/config-desktop.plist/coffee-lake.html#starting-point) (Guide)

---

If this guide has been useful for you, don't forget to give me a star ⭐️❤️
