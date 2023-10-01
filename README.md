# AMD Software: Boot Camp Edition

This repository contains both AMD Software editions that **exclusively** support **AMD Radeon Pro 5600M** `Navi12` `RDNA1` GPU (typically found in **2020 16-inch MacBook Pro**, also known as **MacBookPro16,4**) in Windows 10 & 11. The hardware compatibility was achieved via the following modifications:
- injecting latest `amdkmdag.sys` that supports this GPU (obtained via Windows Update) to packages downloaded from AMD website
- updating package `JSON` setup configuration files
- updating driver file structure
- updating driver `INF` file

> [!WARNING]  
> Only **AMD Radeon Pro 5600M** GPU model in single-GPU configuration is supported.

> [!NOTE]
> 1. `Update!` **AMD Software: Adrenalin Edition 23.9.1** driver package was kindly signed with a valid digital certificate by the team of [BootCampDrivers.com](https://www.bootcampdrivers.com/) and is no more limited for online gaming. Please follow **Note** in the [Installation](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp#installation) section for details. **AMD Software: PRO Edition 23.Q3.1** driver package hasn't been signed.
> 2. Though kernel mode driver that is used is WHQL-certified, it is likely that anti-cheat systems of games won't allow playing online with this driver because package digital signature is incomplete. There're no known limitations for games in offline modes, even if game features anti-cheat for online mode (it will work just fine offline, just as well as any regular single-player game).
> 3. Both original AMD Software packages are stripped-down and include only AMD Software settings and ReLive (DVR, digital video recording) packages. This means there's no AMD Link and other bloatware as well as audio drivers and enhancers, etc.
> 4. AMD settings is configured to disable driver updates and notifications, the options that are not supported by AMD Radeon Pro 5600M are disabled as well.
> 5. Global FreeSync option is disabled too, though this feature can be used with external display that supports it. You can enable it for specific programs and games via per-application settings and use it with an appropriate external display.

> Driver `INF` file includes a couple of OpenGL and Direct3D-related tweaks found in `Navi10` drivers by [BootCampDrivers.com](https://www.bootcampdrivers.com/), though I didn't find it affects performance of this particular GPU in any manner. Driver `INF` also features usage of full `DXNAVI` instead of regular `DX9` and `DX11` as it was recently approved for `RDNA1` (this update may have improved DirectX 9 and DirectX 11 performance slightly).

### AMD Software: Adrenalin Edition 23.9.1 WHQL for AMD Radeon Pro 5600M

    Driver Version:                 23.10.31.01
    Windows Driver Store Version:	31.0.21031.1005 | 30.0.21030.1003 (Kernel Mode Driver 22.6.1)
    Release Date:                   24.08.2023      | 17.07.2022      (Kernel Mode Driver 22.6.1)
    Release Notes:                  https://www.amd.com/en/support/kb/release-notes/rn-rad-win-23-9-1
                                    https://www.amd.com/en/support/kb/release-notes/rn-rad-win-22-6-1

<details>
  <summary>Driver details</summary>
  
  ![AMD Software: Adrenalin Edition 23.9.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/cb6ffada-1912-4dac-890a-5e9c4a2601eb)

</details>

<details>
  <summary>Software features</summary>
  
  ![AMD Software: Adrenalin Edition 23.9.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/b814e492-30e0-48af-8e2c-9cfe4964844f)
  ![AMD Software: Adrenalin Edition 23.9.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/d4e19b0d-fe90-49ef-9ce6-a568b863ae82)
  ![AMD Software: Adrenalin Edition 23.9.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/ffe115ec-d297-4ffe-aa61-f9b8c7a849a2)
  ![AMD Software: Adrenalin Edition 23.9.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/bdd99fb2-2936-4ad8-af97-d1c746c18cd5)
↑ Note all those options can be configured separately for any game in AMD Software: Adrenalin Edition 23.9.1.

</details>

### AMD Software: PRO Edition 23.Q3.1 WHQL for AMD Radeon Pro 5600M

    Driver Version:                 23.10.18.06
    Windows Driver Store Version:	31.0.21018.6011 | 30.0.21030.1003 (Kernel Mode Driver 22.6.1)
    Release Date:                   24.08.2023      | 17.07.2022      (Kernel Mode Driver 22.6.1)
    Release Notes:                  https://www.amd.com/en/support/kb/release-notes/rn-pro-win-23-q3-1
                                    https://www.amd.com/en/support/kb/release-notes/rn-rad-win-22-6-1

<details>
  <summary>Driver details</summary>
  
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/77bc0f8c-c2ab-4763-8d01-4cec2223b5df)

</details>

<details>
  <summary>Software features</summary>

  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/6d92b7d0-4ed8-4cd1-bfb5-c798e8f901f8)
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/a0c852f4-0eb2-41a4-a9c7-04871e68ca07)
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/6b639a95-f5db-4725-bb73-52f4e15c678f)
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/1919b34e-60db-4680-93ae-e14a0961f0aa)
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/b480ff32-256a-4ae3-906e-232d64cda9d1)
  ![AMD Software: PRO Edition 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/80896c13-31af-4551-bf42-c14c69a3a290)
↑ Note there're almost no options for configuring game in AMD Software: PRO Edition 23.Q3.1, however viewport-related options do appear when configuring programs.

</details>

## Which edition do I choose?

> There's no noticeable performance dirrefence between **Adrenalin Edition** ([YouTube promo](https://www.youtube.com/watch?v=EsvLsnQaYeE)) and **PRO Edition** ([YouTube promo](https://www.youtube.com/watch?v=lLCYjjBgDns)). However AMD Software features are very different: **Adrenalin Edition** allows forcing "AMD FidelityFX Super Resolution" (FSR 1.0) to any game or fullscreen program, while **PRO Edition** allows using "Radeon PRO Viewport Boost" (movement based dynamic resolution), "Radeon PRO In-Viewport Image Boost" (forces higher than native resolution for viewport of design software only for supersampling the viewport contents, keep in mind not all software is supported) and "Radeon PRO Image Boost" (forces higher than native resolution for supersampling of entire screen, so all windowed programs are supersampled while Windows UI is scaled) features that may be useful in CAD, BIM and 3D design programs.

> I attach screenshots of AMD Software for both editions in spoilers so you can have a look at the differences yourself. According to ads the only other difference is stability where **PRO Edition** is advertised as enterprise-grade solution, thus more stable. However I didn't experience any stability issues of **Adrenalin Edition** under moderate load.

> All in all I recommend using **Adrenalin Edition** unless you absolutely need "Radeon PRO Image Boost" or "Radeon PRO In-Viewport Image Boost".

## Installation

> [!NOTE]
> **AMD Software: Adrenalin Edition 23.9.1** driver package was kindly signed with a valid digital certificate by the team of [BootCampDrivers.com](https://www.bootcampdrivers.com/). This makes drivers suitable for online games with anti-cheat systems. If you need online gaming, please consider downloading signed `U0000000.inf` & `U0000000.cat` files distributed in a separate package at the releases section and then overwriting 2 original unsigned files in `...\23.10.31.01_WHQL_Radeon_Pro_5600M\Packages\Drivers\Display\WT6A_INF` prior to installation step `9`. You also don't have to follow installation steps `7` & `8` in this case, simply restart the computer after step `6`. If done correctly, you won't need step `11` as you won't see a `Windows can't verify the publisher of this driver software` warning as shown in setup sequence below. If you struggle replace the files you can also [download a package redistibution by BootCampDrivers.com](https://nc2.tomas-g.de/index.php/s/sMc6T5jEAtnsbia) `766 MB`. Please consider donating to [BootCampDrivers.com](https://www.bootcampdrivers.com/) if you need online gaming with anti-cheat system support. *You can safely use the unsigned WHQL-certified driver if you only play games in offline mode (even if there's support for online mode).*

<details>
  <summary>AMD Software: Adrenalin Edition 23.9.1 setup sequence (for reference, unsigned WHQL-certified driver)</summary>

  ![001](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/ed7044c0-5bf4-4625-b15a-6d50a0aae802)
  ![002](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/3404f06f-8c65-4caf-8ab7-ecf599bd4ea3)
  ![003](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/ccd06773-cb8e-4a5c-90ce-0df17ed03c37)
  ![004](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/a64bae4c-e2a8-46cc-b7dc-00ec6bc3130d)

</details>

<details>
  <summary>AMD Software: PRO Edition 23.Q3.1 setup sequence (for reference, unsigned WHQL-certified driver)</summary>
  
  ![001](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/2b74d610-14be-4571-ae88-909decc99388)
  ![002](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/cda5b5b1-b543-442e-957c-e93ee8304aa4)
  ![003](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/66afeb5c-718e-4673-a507-c68a0884d850)
  ![004](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/0bb488bf-05f8-4499-b24e-073b852922d0)
  
</details>

1. Choose which edition you want to use and download corresponding 7Z file
2. Extract downloaded 7Z file using [7-Zip](https://www.7-zip.org/) or any other program
3. Download [Display Driver Uninstaller 18.0.6.8](https://www.wagnardsoft.com/forums/viewforum.php?f=5) (or higher)
4. Launch Command Prompt as Administrator and execute comand `bcdedit /set onetimeadvancedoptions on`
5. Restart computer and press 4 on startup to enter `4) Safe Mode`
6. Launch [Display Driver Uninstaller](https://www.wagnardsoft.com/forums/viewforum.php?f=5), select device type `GPU` and click `Clean and do NOT restart`
8. Launch Command Prompt as Administrator and execute comand `bcdedit /set onetimeadvancedoptions on`
9. Restart computer and press 7 on startup to `7) Disable driver signature enforcement`
> [!NOTE]  
> You can pause here and use [Radeon Software Slimmer](https://github.com/GSDragoon/RadeonSoftwareSlimmer) to remove ReLive/DVR from instalation package (if you don't need it), however note that Overlay won't function if ReLive/DVR package wasn't installed!
9. Launch `Setup.exe` from the location where you extracted downloaded 7Z file
10. Select `Install Type` `Full Install` if you need both the GPU driver and AMD software with display recording software or `Minimal Install` if you only need GPU driver
11. Click `Install this driver software anyway` when `Windows can't verify the published of this driver software` dialog appears
12. Click `Close` when installation finishes and you see message `Oops! Something went wrong. Error 205 - AMD Software installation completed successfuly but Windows Update may have reverted your driver version during the process`
13. Optionally, launch `Cleanup.bat` as administrator
> [!IMPORTANT]  
> `Cleanup.bat` will remove AMD Bug Report Tool, remove UI languages (except US English) of AMD Software, remove web service integration for ReLive/DVR (support to upload to YouTube, Twitch, etc.), remove AMD Software context menu item (when you right-click Desktop), disable automatic startup of AMD settings and ReLive/DVR. Double-check you don't need any of this before executing `Cleanup.bat`.
14. Restart computer
15. Launch AMD Software from Start

## Download

`Primary`

[GitHub releases: 23.9.1 · 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/releases/tag/release)

`Secondary`

> Alternative links outside of GitHub are provided below in case GitHub is blocked in your country. Note that website virus warning occures because of the `BAT` file that is included in the archive, so it's false alarm.

- [AMD Software: Adrenalin Edition 23.9.1 WHQL for AMD Radeon Pro 5600M](https://disk.yandex.com/d/X1OaUQDxy2CmEQ) `475 MB` `498,236,207 bytes`
- [AMD Software: PRO Edition 23.Q3.1 WHQL for AMD Radeon Pro 5600M](https://disk.yandex.com/d/_XyzOZ7Yr5elgg) `474 MB` `497,954,309 bytes`

**Before you download or install, please double-check [AMD's official Boot Camp page](https://www.amd.com/en/support/kb/release-notes/apple-boot-camp) for a newer version.**

## Legal Notes

I'm not responsible for any damage this software can cause to your computer or data. No binaries were modified via hex editing or any other means. All binaries are courtesy and property of Advanced Micro Devices, Inc.
