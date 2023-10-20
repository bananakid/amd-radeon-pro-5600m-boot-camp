# AMD Software: Boot Camp Edition

This repository contains both AMD Software editions that **exclusively** support **AMD Radeon Pro 5600M** `Navi12` `RDNA1` GPU (typically found in **2020 16-inch MacBook Pro**, also known as **MacBookPro16,4**) in Windows 10 & 11.

#### AMD Software: Adrenalin Edition 23.9.1 WHQL for AMD Radeon Pro 5600M

<details>
  <summary>Version details</summary>
  
    Driver Version:                 23.10.31.01
    Windows Driver Store Version:	31.0.21031.1005 | 30.0.21030.1003 (Kernel Mode Driver 22.6.1)
    Release Date:                   24.08.2023      | 17.07.2022      (Kernel Mode Driver 22.6.1)
    Release Notes:                  https://www.amd.com/en/support/kb/release-notes/rn-rad-win-23-9-1
                                    https://www.amd.com/en/support/kb/release-notes/rn-rad-win-22-6-1
  
</details>

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

#### AMD Software: PRO Edition 23.Q3.1 WHQL for AMD Radeon Pro 5600M

<details>
  <summary>Version details</summary>
  
    Driver Version:                 23.10.18.06
    Windows Driver Store Version:	31.0.21018.6011 | 30.0.21030.1003 (Kernel Mode Driver 22.6.1)
    Release Date:                   24.08.2023      | 17.07.2022      (Kernel Mode Driver 22.6.1)
    Release Notes:                  https://www.amd.com/en/support/kb/release-notes/rn-pro-win-23-q3-1
                                    https://www.amd.com/en/support/kb/release-notes/rn-rad-win-22-6-1
  
</details>

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

## FAQ

> [!IMPORTANT]
> 1. AMD Software packages are stripped-down and include only GPU driver, AMD Software control panel and ReLive (which states for DVR, digital video recording).
> 2. AMD Software is configured to disable driver updates and notifications. Other options that are not supported by AMD Radeon Pro 5600M are disabled as well.

<details>
<summary>Which edition do I choose?</summary>
    
> There's no noticeable performance difference between **Adrenalin Edition** ([YouTube promo](https://www.youtube.com/watch?v=EsvLsnQaYeE)) and **PRO Edition** ([YouTube promo](https://www.youtube.com/watch?v=lLCYjjBgDns)).

> However AMD Software features are very different: **Adrenalin Edition** allows forcing "AMD FidelityFX Super Resolution" (FSR 1.0) to any game or fullscreen program, while **PRO Edition** allows using "Radeon PRO Viewport Boost" (movement based dynamic resolution), "Radeon PRO In-Viewport Image Boost" (forces higher than native resolution for viewport of design software only for supersampling the viewport contents, keep in mind not all software is supported) and "Radeon PRO Image Boost" (forces higher than native resolution for supersampling of entire screen, so all windowed programs are supersampled while Windows UI is scaled) features that may be useful in CAD, BIM and 3D design programs. I attach screenshots of AMD Software for both editions in spoilers so you can have a look at the differences yourself.

> According to ads the only other difference is stability where **PRO Edition** is advertised as enterprise-grade solution, thus more stable. However I didn't experience any stability issues of **Adrenalin Edition** under moderate load. All in all I recommend using **Adrenalin Edition** unless you absolutely need "Radeon PRO Image Boost" or "Radeon PRO In-Viewport Image Boost".
  
</details>

<details>
<summary>Which parts of the driver were modified?</summary>
    
> No binaries of the driver were modified in any way (hex-editing, etc.). The hardware compatibility was achieved by:
> - replacing AMD's `amdkmdag.sys` kernel mode driver (that comes with the packages downloaded from AMD website) with AMD's latest `amdkmdag.sys` that supports this GPU (both files contain valid digital signarures by AMD, Inc. and Microsoft)
> - updating package `JSON` setup configuration files
> - updating driver file structure
> - updating driver `INF` file

> Driver `INF` file includes a couple of OpenGL and Direct3D-related tweaks found in `Navi10` drivers by [BootCampDrivers.com](https://www.bootcampdrivers.com/), though I didn't find it affects performance of this particular GPU in any manner. Driver `INF` also features usage of full `DXNAVI` instead of regular `DX9` and `DX11` as it was recently approved for `RDNA1` (this update may have improved DirectX 9 and DirectX 11 performance slightly).
  
</details>

<details>
<summary>Is this just an old driver version hack with a new AMD Software version?</summary>
    
> No, `amdkmdag.sys` kernel mode driver acts like "hub" hub for all the driver parts to "guide" their usage. Since all other parts of the driver (typically `DLL` files) are "new" and fit in file structure supported by "older" `amdkmdag.sys`, the actual GPU performance is "new" as well. The versions of `Direct3D`, `Vulkan`, `OpenGL`, `OpenCL` drivers in use can be checked in AMD Software control panel (in Hardware & Details) or in GPU-Z. Performance testing was done to make sure this is correct.
  
</details>

<details>
<summary>Can I use this driver to play online with anti-cheat?</summary>
    
> Though kernel mode driver that is used is WHQL-certified, it is likely that anti-cheat systems of games won't allow playing online with this driver because package digital signature is incomplete.

> However **AMD Software: Adrenalin Edition 23.9.1** driver package was kindly signed with a valid digital certificate by the team of [BootCampDrivers.com](https://www.bootcampdrivers.com/) and is no more limited for online gaming. Please follow **Note** in the [Installation](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp#installation) section for details. **AMD Software: PRO Edition 23.Q3.1** driver package hasn't been signed.

> There're no known limitations for games in offline modes, even if game features anti-cheat for online mode (it will work just fine offline, just as well as any regular single-player game).
  
</details>

<details>
<summary>Can I get rid of ReLive in AMD Software?</summary>
    
> Yes, you can use [Radeon Software Slimmer](https://github.com/GSDragoon/RadeonSoftwareSlimmer) to remove ReLive (DVR, digital video recording which states for screen recording) from instalation package before starting `Setup.exe`. However note that Overlay won't function if ReLive/DVR package wasn't installed!
  
</details>

<details>
<summary>Why FreeSync option is missing AMD Software?</summary>
 
> Global FreeSync option is disabled in `AMD Software` → `Gaming` → `Display`, though this feature still can be used with external display that supports it. You can enable it for specific programs and games via per-application settings and use it with an appropriate external display. If you really need the global setting you can edit line 718 of `INF` file prior to installation: just change `HKR,,freesync_runtime_component_na,%REG_SZ%,true` to `HKR,,freesync_runtime_component_na,%REG_SZ%,false`.
  
</details>

<details>
<summary>Can I use this driver with eGPU?</summary>
    
> Yes, both for NVIDIA and AMD eGPU. However if you're planning to use the driver with AMD eGPU side-by-side you should do one of the following things:
> - if you don't need additional AMD Software settings (except AMD ReLive), you should first install this package and then download and install eGPU driver of the same version (23.9.1) in `Minimal Install` mode (or via Device Manager)
> - if you need additional AMD Software settings fuctions (like AMD Link), you should first download and install eGPU driver of the same version (23.9.1) in any mode and then install this package in `Minimal Install` mode (or via Device Manager), then make sure to disable any automatic driver updates
  
</details>

## Installation

> [!NOTE]
> **AMD Software: Adrenalin Edition 23.9.1** driver package was kindly signed with a valid digital certificate by the team of [BootCampDrivers.com](https://www.bootcampdrivers.com/). If you play online games with anti-cheat systems, consider downloading 2 signed files distributed in a separate package and then overwriting 2 files in `...\23.10.31.01_WHQL_Radeon_Pro_5600M\Packages\Drivers\Display\WT6A_INF` prior to installation. Keep in mind you don't have to follow installation steps `7` & `8` in this case, simply restart the computer after step `6`. If done correctly, you won't need step `11` too as you won't see a `Windows can't verify the publisher of this driver software` warning as shown in setup sequence below. Please consider donating to [BootCampDrivers.com](https://www.bootcampdrivers.com/) if you need online gaming with anti-cheat system support. **You can safely use the unsigned WHQL-certified driver if you only play games in offline mode (even if there's support for online mode).**

1. Choose which edition you want to use and download corresponding 7Z file
2. Extract downloaded 7Z file using [7-Zip](https://www.7-zip.org/) or any other program
3. Download [Display Driver Uninstaller 18.0.6.8](https://www.wagnardsoft.com/forums/viewforum.php?f=5) (or higher)
4. Launch Command Prompt as Administrator and execute comand `bcdedit /set onetimeadvancedoptions on`
5. Restart computer and press 4 on startup to enter `4) Safe Mode`
6. Launch [Display Driver Uninstaller](https://www.wagnardsoft.com/forums/viewforum.php?f=5), select device type `GPU` and click `Clean and do NOT restart`
7. Launch Command Prompt as Administrator and execute comand `bcdedit /set onetimeadvancedoptions on`
8. Restart computer and press 7 on startup to `7) Disable driver signature enforcement`
9. Launch `Setup.exe` from the location where you extracted downloaded 7Z file
    <details>
      <summary>Screenshot for AMD Software: Adrenalin Edition 23.9.1</summary>

      
      ![001](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/ed7044c0-5bf4-4625-b15a-6d50a0aae802)

    </details>
    <details>
      <summary>Screenshot for AMD Software: PRO Edition 23.Q3.1</summary>

      
      ![001](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/2b74d610-14be-4571-ae88-909decc99388)

    </details>
10. Select `Install Type` `Full Install` if you need both the GPU driver and AMD software with display recording software or `Minimal Install` if you only need GPU driver
    <details>
      <summary>Screenshot for AMD Software: Adrenalin Edition 23.9.1</summary>

      
      ![002](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/3404f06f-8c65-4caf-8ab7-ecf599bd4ea3)

    </details>
    <details>
      <summary>Screenshot for AMD Software: PRO Edition 23.Q3.1</summary>

      
      ![002](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/cda5b5b1-b543-442e-957c-e93ee8304aa4)

    </details>
11. Click `Install this driver software anyway` when `Windows can't verify the published of this driver software` dialog appears
    <details>
      <summary>Screenshot for AMD Software: Adrenalin Edition 23.9.1</summary>

      
      ![003](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/ccd06773-cb8e-4a5c-90ce-0df17ed03c37)

    </details>
    <details>
      <summary>Screenshot for AMD Software: PRO Edition 23.Q3.1</summary>

      
      ![003](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/66afeb5c-718e-4673-a507-c68a0884d850)

    </details>
12. Click `Close` when installation finishes and you see message `Oops! Something went wrong. Error 205 - AMD Software installation completed successfuly but Windows Update may have reverted your driver version during the process`
    <details>
      <summary>AMD Software: Adrenalin Edition 23.9.1 setup sequence (unsigned WHQL-certified driver)</summary>

      
      ![004](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/a64bae4c-e2a8-46cc-b7dc-00ec6bc3130d)

    </details>
    <details>
      <summary>AMD Software: PRO Edition 23.Q3.1 setup sequence (unsigned WHQL-certified driver)</summary>

      
      ![004](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/assets/17095595/0bb488bf-05f8-4499-b24e-073b852922d0)

    </details>
13. Optionally, launch `Cleanup.bat` as administrator
> [!WARNING]  
> `Cleanup.bat` will remove AMD Bug Report Tool, remove UI languages (except US English) of AMD Software, remove web service integration for ReLive/DVR (support to upload to YouTube, Twitch, etc.), remove AMD Software context menu item (when you right-click Desktop), disable automatic startup of AMD settings and ReLive/DVR. Double-check you don't need any of this before executing `Cleanup.bat`. You can manually edit the file if you need to keep some of the options.
14. Restart computer
15. Launch AMD Software from Start

## Download

[GitHub releases: 23.9.1 · 23.Q3.1](https://github.com/bananakid/amd-radeon-pro-5600m-boot-camp/releases/tag/release)

## Legal Notes

This project is licensed under the terms of the [MIT License](https://opensource.org/license/mit/).

All binaries are courtesy and property of Advanced Micro Devices, Inc.
