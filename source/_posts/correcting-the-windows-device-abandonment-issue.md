---
title: Correcting the Windows Device Abandonment Issue
date: 2024-07-11T22:29:13.623Z
updated: 2024-07-12T22:29:13.623Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting the Windows Device Abandonment Issue
excerpt: This Article Describes Correcting the Windows Device Abandonment Issue
keywords: Fix Device Disposal,End PC Waste,Stop Tech Forgotten,Resolve PC Dump,Cease Computer Loss,Eradicate Screens Gone,Curtail Windows Trash
thumbnail: https://thmb.techidaily.com/c5a835a587cbde63390ec7ae0f646f52f65cc154a66fb89768e9cd878c5a4c7b.jpg
---

## Correcting the Windows Device Abandonment Issue

 The DXGI\_ERROR\_DEVICE\_REMOVED error sometimes occurs when users try to start certain Windows games or when playing them. Players have reported this error to occur for games like FIFA 2022, Prepar3D, Need for Speed Rivals, Apex, and Crysis 3, among others. This DirectX error message says, “DirectX function ‘GetDeviceRemovedReason’ failed with DXGI\_ERROR\_DEVICE\_REMOVED.”

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.

## 1\. Modify the GraphicsDriver Registry Key

 Modifying the GraphicsDriver registry key is the most widely confirmed potential fix for the DXGI\_ERROR\_DEVICE\_REMOVED error. This resolution involves adding a TDR (Timeout Detection and Recovery) DWORD to the GraphicsDrivers key. Setting that DWORD to 0 disables TDR detection. You can apply this registry edit as follows:

1. Press **Win + S**, type **regedit** inside the search tool, and click **Registry Editor**.
2. Next, navigate to the GraphicsDrivers key at this registry location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
3. Right-click on **GraphicsDrivers** and select the context menu’s **New** and **DWORD** options.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-new-key-options.jpg)
4. Type in a **TdrLevel** title for the DWORD.
5. Double-click on **TdrLevel** to activate its **Value** box.
6. The DWORD’s value should already be set to zero by default. However, change that value to **0** if it’s not and click **OK**.  
![The TrdLevel DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/trdlevel-dword.jpg)
7. Now close Registry Editor, click **Start**, and select **Power** \> **Restart**.

 A few users also confirm deleting a TdrDelay QWORD in the same key can also work for fixing the DXGI\_ERROR\_DEVICE\_REMOVED error. If you can see a TdrDelay QWORD in the GraphicsDrivers key, try deleting it as well. To do so, right-click the **TdrDelay** QWORD and select **Delete**. Select **Yes** to confirm the erasure.

## 2\. Disable the Antialiasing Setting

 Antialiasing is a graphic setting that smoothens jagged lines when enabled. However, this graphical effect can sometimes cause crashing issues like the DXGI\_ERROR\_DEVICE\_REMOVED error. This is how you can turn off Antialiasing within the NVIDIA Control Panel:

1. Right-click on the NVIDIA logo in the system tray area and select **NVIDIA Control Panel**.  
![The NVIDIA Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-geforce-experience.jpg)
2. Click the **Manage 3D** settings navigation option within the sidebar.
3. Select NVIDIA Control Panel’s **Global Settings** tab.
4. Next, click the **Antialiasing – Mode** option and select **Off**.  
![The Antialising - Mode setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antialiasing.jpg)
5. Repeat the previous step for the **Antialiasing – Transparency**, **FXAA**, and **Gamma** correction options.
6. Then select **Apply** to set the new graphics options.

 You can also disable Antialiasing for AMD GPUs within the Radeon software. Check out our guide about [tweaking AMD Radeon settings](https://www.makeuseof.com/amd-radeon-settings-gaming-performance-windows/) for further details about how to turn off Antialiasing there.

## 3\. Turn Off the NVIDIA ShadowPlay (Overlay) Feature

 GeForce Experience’s ShadowPlay feature for game recording can place a notable burden on GPUs. So, we recommend that you turn that feature off for the sake of fixing the DXGI\_ERROR\_DEVICE\_REMOVED error if it’s enabled. You can turn off NVIDIA ShadowPlay in GeForce Experience like this:

1. To open GeForce Experience, right-click the NVIDIA system tray icon and select that software on the context menu.
2. Then click on the **cog** (Settings) button to access further options.  
![The Settings button in GeForce Experience.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/settings-button.jpg)
3. Toggle off the **In-Game Overlay** option.  
![The in-game overlay option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/in-game-overlay.jpg)
4. Exit the GeForce Experience software and try playing your games with ShadowPlay disabled.

## 4\. Turn Off the DLSS Graphics Setting

 Some players confirm disabling DLSS graphics settings in games fixes the DXGI\_ERROR\_DEVICE\_REMOVED error. If the affected game doesn’t always crash when you start it, try turning off its **DLSS** option. You can usually find that setting within a game’s video or graphics tab options.

![A DLSS option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dlss-option.jpg)

## 5\. Undo Overclocking

 Have you done any GPU or processor overclocking on your PC? If you have, that overclocking could have caused the DXGI\_ERROR\_DEVICE\_REMOVED error. Undo the overclocking with the software you applied it with. Or you can undo overclocking by [resetting the BIOS](https://www.makeuseof.com/tag/reset-bios-default-settings-computer/) (Basic Input Output System).

![MSI Afterburner homepage](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/msi-afterburner.jpg)

## 6\. Run the DirectX Web Installer

 DXGI\_ERROR\_DEVICE\_REMOVED can occur because of DirectX issues. For example, some required DirectX components might be missing on your PC. You can address that by downloading and running the DirectX Web Installer like this:

1. Open this [DirectX download page](https://www.microsoft.com/en-us/download/details.aspx?id=35).
2. Click on the orange **Download** button to obtain a DirectX setup file.  
![The Download button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-button.jpg)
3. To view File Explorer, hold the **Windows** logo button and press **E**. Then open the folder containing the Microsoft DirectX End-User Runtime package.
4. Double-click **dxwebsetup.exe** to bring up an Installing Microsoft (R) DirectX (R) window.
5. Click **I accept the agreement** and **Next**.  
![I accept the agreement radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/i-accept-the-radio-button.jpg)
6. If you don’t want Bing Bar, uncheck the **Install the Bing Bar** option.
7. Select **Next** to install DirectX components.

## Try Some Generic Windows Fixes

 If nothing has worked yet, here are some generic fixes for GPU issues.

### Update the Graphics Driver for Your GPU

 The DXGI\_ERROR\_DEVICE\_REMOVED error message clearly says that this issue is often the result of a graphics driver crash. It also suggests users update their GPU graphics drivers to remedy the error. You can update your PC’s graphics driver with the methods covered in this guide to [updating a GPU’s driver in Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Cleanly Reinstall the Graphics Driver

 Cleanly reinstalling a graphics driver is a variation of the previous potential resolution for updating it. This involves completely uninstalling the current GPU driver and then installing the latest one. We recommend thoroughly uninstalling the graphics driver with the DDU software before installing the new one. You can apply this solution as covered in our [article about reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/).

![uninstall graphics drivers DDU](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-graphics-drivers-ddu.jpg)

##

### Run a Windows Memory Diagnostic Check

 Some users have said they needed to replace faulty RAM modules to resolve DXGI\_ERROR\_DEVICE\_REMOVED. So, try running a Windows Memory Diagnostic check if other resolutions here don’t work for you. Our guide to [resolving RAM issues with Windows Memory Diagnostic](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) includes full instructions for utilizing that tool.

![The Windows Memory Diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-windows-memory-diagnostic-tool.jpg)

 If that tool detects issues, removing the faulty RAM module from your PC will probably resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. However, you’ll still need enough RAM for the game. If removing RAM leaves insufficient system memory for the game, purchase and add a new RAM module to your PC.

## Enjoy Your Windows Games Again

 The potential fixes above have worked for many players who’ve needed to resolve the DXGI\_ERROR\_DEVICE\_REMOVED error. That doesn’t necessarily mean they’re guaranteed fixes, but one will probably resolve that issue on your PC. Then you can play the Windows 11/10 games that error crashed without further issues.

 If the solutions above don’t resolve the DXGI\_ERROR\_DEVICE\_REMOVED error on your PC, there could be an issue with your graphics card. Persistent GPU crashing is one of the signs that it’s time to upgrade your graphics card.

 Consequently, Windows games either don’t launch at all or crash with regularity because of the DXGI\_ERROR\_DEVICE\_REMOVED error. The error message highlights that something associated with your graphics card has gone wrong. As such, these potential resolutions can fix the DXGI\_ERROR\_DEVICE\_REMOVED error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/learn-and-master-io-screen-recording-today/"><u>Learn and Master IO Screen Recording Today</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-minimummax-cpu-in-power-preferences/"><u>Deciphering Minimum/Max CPU in Power Preferences</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-gopro-video-processing-apps/"><u>Best GoPro Video Processing Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-routes-to-windows-11s-system32/"><u>Direct Routes to Windows 11'S System32</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-meaning-behind-windows-folders-x-marks/"><u>Demystifying: The Meaning Behind Windows' Folders X-Marks</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-guide-on-vhs-technology-and-its-influence-on-video-editing/"><u>New In 2024, Guide on VHS Technology and Its Influence on Video Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/coordinating-connections-dual-net-usage-on-a-single-windows-pc/"><u>Coordinating Connections: Dual Net Usage on a Single Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-slate-optimizing-windowed-file-space/"><u>Clean Slate: Optimizing Windowed File Space</u></a></li>
<li><a href="https://windows11.techidaily.com/cross-language-build-system-setup/"><u>Cross-Language Build System Setup</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-youtube-as-a-learning-tool-insider-advice-for-teachers/"><u>[Updated] YouTube as a Learning Tool  Insider Advice for Teachers</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/detecting-correct-credentials-vs-error-logins-on-your-winpc/"><u>Detecting Correct Credentials vs Error Logins on Your WinPC</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-windows-11-parental-restrictions-guide/"><u>Configuring Windows 11 Parental Restrictions Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-navigating-the-world-of-unfollowed-instagrams/"><u>[Updated] Navigating the World of Unfollowed Instagrams</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-common-errors-in-windows-onedrive/"><u>Correcting Common Errors in Windows' OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-clutter-fixing-windows-error-0x80072014/"><u>Clearing the Clutter: Fixing Windows Error 0X80072014</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-video-tag-management-made-easy-top-editors-for-windows-and-mac/"><u>Updated Video Tag Management Made Easy Top Editors for Windows and Mac</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-perfecting-podcast-intros-a-guide-with-illustrations/"><u>[New] Perfecting Podcast Intros  A Guide with Illustrations</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-sighted-making-your-windows-11-taskbar-glossy/"><u>Clear-Sighted: Making Your Windows 11 Taskbar Glossy</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-pro-audio-advantages-unveiling-the-top-4-video-volume-enhancers-on-the-net/"><u>New Pro Audio Advantages Unveiling the Top 4 Video Volume Enhancers on the Net</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-learning-the-art-of-soundshaping-in-audacity/"><u>[New] Learning the Art of Soundshaping in Audacity</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-mastering-animation-drawing-the-7-best-software-solutions/"><u>Updated In 2024, Mastering Animation Drawing The 7 Best Software Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-inadequate-pcs-fixing-game-bar-errors/"><u>Defeating Inadequate PCs: Fixing Game Bar Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-windows-startup-journey/"><u>Decoding the Windows Startup Journey</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-iphone-6s-plus-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled iPhone 6s Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-pc-capacity-concealed-by-slowness/"><u>Compact PC, Capacity Concealed by Slowness</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevate-your-video-profiles-using-smart-templates/"><u>[Updated] In 2024, Elevate Your Video Profiles Using Smart Templates</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Itel S23+ | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-s23-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel S23 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-the-save-issue-in-microsoft-oses/"><u>Cure the Save Issue in Microsoft OSes</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximize-your-tiktok-experience-with-updated-numbers-for-2024/"><u>Maximize Your TikTok Experience with Updated Numbers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-shortcuts-a-guide-for-winos-users/"><u>Crafting Shortcuts: A Guide for WinOS Users</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tweeting-videos-directly-from-your-phone-no-rt/"><u>[Updated] Tweeting Videos Directly From Your Phone (No RT)</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-heic-photos-to-jpeg-on-windows-1011/"><u>Converting HEIC Photos to JPEG on Windows 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>