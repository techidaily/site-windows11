---
title: Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11
date: 2024-07-11T21:56:27.811Z
updated: 2024-07-12T21:56:27.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11
excerpt: This Article Describes Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11
keywords: Fixing Win10 Display Issues,Troubleshoot Win10 Screen Errors,Resolving Win10 Displays,Overcoming Windows Display Errors,Correcting Win10 Graphics Faults,Tackling Win10 Display Glitches,Addressing Windows Errors on Screen
thumbnail: https://thmb.techidaily.com/fe142fc722967440c0a67173b1e546447bf0e801339eadf58291eb4451fb4b01.jpg
---

## Overcoming DXGI_ERROR_DEVICE_HUNG in Win10/11

 Many Windows gaming enthusiasts have reported that they're encountering a DXGI\_ERROR\_DEVICE\_HUNG error. This error regularly crashes some players’ games shortly after starting them or when they’re playing. It displays an error message window that includes a 0x887A0006 code and says, “A problem has occurred with your display driver.”

 Microsoft has described the DXGI\_ERROR\_DEVICE\_HUNG error to be a command communication issue between system hardware and games. This error is a big deal when it keeps crashing affected Windows games. However, players have resolved the 0x887A0006 error with these potential fixes.

## 1\. Set Affected Games to Run With Administrator Rights

 Make sure the games that error 0x887A0006 crashes have full system access by running them with administrator rights. You can temporarily select to run a game with admin rights or set it to always run with elevated privileges. This is how you can configure an affected game to run as an administrator:

1. First, bring up Windows 11’s file manager with a method in our [guide for opening Explorer](https://www.makeuseof.com/windows-open-file-explorer/).
2. Then open the installation folder that contains the game’s EXE (application file).
3. Right-click the game’s EXE file and select **Properties**.
4. Click the properties window’s **Compatibility** tab.
5. Select **Run this game as administrator** to give the game elevated privileges.  
![The Run this program as administrator setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab1.jpg)
6. To save the settings, press the **Apply** button.
7. Then try playing your affected game to see if this potential solution makes a difference.

## 2\. Select Debug Mode in the NVIDIA Control Panel

 Some players have fixed the 0x887A0006 error by selecting **Debug Mode** in the NVIDIA Control Panel. That option disables GPU (graphical processing unit) overclocking. If your PC has an NVIDIA graphics card, you can select the **Debug Mode** option as follows:

1. Right-click the desktop area and select **NVIDIA Control Panel**.
2. Click the **Help** menu.  
![The Debug Mode option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-debug-mode-option.jpg)
3. Select **Debug Mode** on the menu.

## 3\. Repair the Files for Any Affected Games

 There’s a possibility that the 0x887A0006 error sometimes occurs because of corrupted game files. So, it’s recommended players verify affected games with their gaming clients. Epic Games, Steam, Origin, and Battle.net all include options for verifying (repairing) games. This is how you can verify affected games in the Epic Game and Steam launchers.

### How to Repair Games on Epic Games

 For Epic Games:

1. Run Epic Games to view its windows.
2. Click the Epic Games Launcher’s **Library** tab.
3. Next, click the ellipses menu button for the game you need to verify.
4. Select **Manage** to bring up some options.  
![The Manage option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-manage-option.jpg)
5. Press the **Verify** button, and wait for the verification process to finish.  
![The Verify button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-verify-files-option-in-epic.jpg)

### How to Repair Games on Steam

 For Steam:

1. Open up Steam’s window.
2. To view your games, select Steam’s **Library** tab.
3. Right-click a game for which you need to verify files and select **Properties**.
4. Click the **Local Files** tab to view more options.  
![The Verify integrity option in Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/steams-verify-option.jpg)
5. Select Steam’s **Verify integrity of game files** option.

## 4\. Check If Your PC Uses the Right GPU for Affected Games

 If you have a PC with two GPUs, make sure your affected games are configured to run with the dedicated high-performance graphics card. Your PC’s integrated graphics card (usually of the Intel variety) might not meet the affected game’s minimum system requirements. You can check and change a game’s GPU setting on the NVIDIA Control Panel like this:

1. Open NVIDIA Control Panel by right-clicking the desktop and selecting it from the context menu.
2. Then select **Manage 3D** **settings** on the left of the panel.
3. Click **Program Settings** to view that tab.
4. Next, click the **Select a program to customize** drop-down menu. If you can't find a game listed, click **Add** and select it.  
![The Select a program to customize drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-select-a-program-drop-down-menu.jpg)
5. Select a game for which you need to fix the 0x887A0006 error.
6. Click the **Select the preferred graphics processor** drop-down menu, and select the **High-performance NVIDIA processor** option.  
![The High-performance NVIDIA processor option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-high-performance-graphics-processor-option.jpg)
7. Select **Apply** to save the new GPU settings.

 If your PC has an AMD graphics card, you’ll need to open the AMD Radeon Settings panel from the desktop’s context menu. Click the System tab in AMD Radeon Settings. Then click the **Switchable Graphics** tab, and select the **High Performance** GPU option for the affected game.

## 5\. Roll Back the Most Recent Graphics Driver Update

 A few players have said they fixed error 0x887A0006 by rolling back graphics drivers. Applying such a resolution will restore the previous graphics driver installed on your PC. If the file for your previous graphics driver remains saved, you can select to roll back the driver via Device Manager. This article about [how to roll back a driver](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes instructions for applying this possible fix.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/roll-back-driver-option.jpg)

## 6\. Update Your GPU’s Driver

 The 0x887A0006 error message explicitly says that an issue has occurred with your PC’s display (graphics) adapter. That could mean there’s an outdated graphics driver on your PC that isn’t compatible with affected games. The probable solution in such a scenario is to update the driver for your PC’s GPU.

 You can update an NVIDIA or AMD driver in a few different ways. Some users utilize driver updater software packages, but some of them don't update graphics drivers to the newest ones available. To ensure you’re installing the very latest driver available for your GPU, download it from the manufacturer’s website.

 Our guide for [updating your graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) provides further details about the various methods.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-nvidia-driver-download-page.jpg)

## 7\. Disable DirectX 12 in Any Affected Games

 DirectX 12 is the more advanced alternative version to DX11 that’s known to generate issues for some games. So, it’s recommended that you disable DX12 by setting DX11 for games where the 0x887A0006 error occurs.

 If you can get to an affected game’s settings screen before it crashes, disable its DirectX 12 graphic option from there. Alternatively, you can set games to start with DX11 in Epic Games like this:

1. First, open Epic Games Launcher.
2. Click the circle button that includes your user initials.
3. Select the **Settings** option on the menu that opens.  
![The Settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-settings-option1.jpg)
4. Then click the game title for which 0x887A0006 arises.
5. Select the **Additional Command Line Arguments** box.  
![The Additional Command Line Arguments checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-d3d11-command-line.jpg)
6. Add **d3d11** in the text box.

## 8\. Switch to the High-Performance Power Plan

 Error 0x887A0006 will more likely arise with the Power saver or Balanced power setting selected. Those power settings reduce PC performance for the sake of saving energy. So, try selecting the high-performance setting to ensure optimal gaming performance as follows:

1. To access the tool for finding files, apps, and folders, press the **Windows** logo + **S** keys simultaneously.
2. Type **powercfg.cpl** in the text box and click the matching search result.
3. Click **Create a power plan** on the left side of the Control Panel applet.  
![The Create a power plan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/high-performance-option.jpg)
4. Select the **High performance** option for the plan.  
![The Create a power plan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/high-performance-radio-button.jpg)
5. Input a plan title in the name box and click **Next**.
6. Click **Create** to add the plan.
7. Select the new high-performance plan in the Power Options Control Panel applet.

## 9\. Don’t Overclock Your PC

 Overclocking GPUs or CPUs (central processors) is one of the more common causes of error 0x887A0006\. Have you overclocked your PC with overclocking software like CPU Tweaker, AMD Ryzan Master, or MSI Afterburner in any way? If so, it’s recommended you disable (undo) any overclocking you’ve applied by restoring default system values with whatever overclock software you utilize.

 You can disable NVIDIA GPU overclocking with the method outlined for resolution two. However, that option won’t be available on PCs with AMD graphics cards. Nor will it be of any use for users who’ve overclocked CPUs.

## 10\. Edit the GraphicsDrivers Registry Key

 Disabling Timeout Detection and Recovery is another potential 0x887A0006 error fix some players have confirmed works. Time Detection and Recovery is a Windows feature that resets an unresponsive graphics driver. You can disable that feature by editing the **GraphicsDrivers** registry key in the following steps:

1. Launch Windows’ Registry Editor app (check out our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) for further instructions.)
2. Navigate to this **GraphicsDrivers** registry key location by entering the following path in the address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
3. Right-click GraphicsDrivers and select that key’s **New** \> **DWORD (32-bit) Value** options.  
![The DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-dword-option.jpg)
4. Type **TdrLevel** inside the DWORD’s text box.
5. Double-click **TdrLevel** to view a **Value data** box for that DWORD.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-edit-dword-value-box.jpg)
6. Enter **0** in TdrLevel’s **Value** box, and select **OK** to save.
7. Close the Regedit app, and then restart your PC.

## 11\. Reinstall the Game That's Crashing

![The Uninstall option in Epic Games](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/uninstall-option-2.jpg)

 Reinstalling an affected game is the last thing to try when all else fails. Applying this potential solution will likely fix corrupted or missing game files that could be causing error 0x887A0006\. Some players may be concerned about losing saved games when reinstalling, but you can [back up game saves](https://www.makeuseof.com/tag/protect-your-game-saves/) in numerous ways.

 You might be able to uninstall an affected game via Programs and Features or Settings. If you can’t see a game listed there, however, you’ll need to uninstall the title within the gaming client software with which you installed it. Then select to install the game in your gaming client.

## Stop the 0x887A0006 Error Spoiling Your Gaming Fun

 It’s likely that one of those Windows 11/10 solutions will fix the 0x887A0006 error for affected games on your PC. There are also other potential resolutions for this issue since it has variable causes. Disabling game overlays, turning off Steam Cloud syncing, and updating Windows and DirectX are additional potential fixes for error 0x887A0006 that might also be worth a try.

 Microsoft has described the DXGI\_ERROR\_DEVICE\_HUNG error to be a command communication issue between system hardware and games. This error is a big deal when it keeps crashing affected Windows games. However, players have resolved the 0x887A0006 error with these potential fixes.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-t-mobile-apple-iphone-11-pro-online-without-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock T-Mobile Apple iPhone 11 Pro online without SIM Card?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-essential-tips-for-using-zoom-with-xbox/"><u>In 2024, Essential Tips for Using Zoom with Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/access-control-microphone-and-camera-via-edge-protection/"><u>Access Control: Microphone and Camera via Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-complete-tiktok-termination-protocol-unveiled-for-2024/"><u>[Updated] Complete TikTok Termination Protocol Unveiled for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-play-40c-phone-without-pin-by-drfone-android/"><u>How to Unlock Honor Play 40C Phone without PIN</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/the-best-cinematic-luts-in-the-market/"><u>The Best Cinematic LUTs in The Market</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-the-best-free-video-watermark-software-for-beginners/"><u>In 2024, The Best Free Video Watermark Software for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-elevate-with-25-customization-tips/"><u>Windows 11: Elevate with 25 Customization Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win1011-system-breakdown-code-0xc0000001/"><u>Addressing Win10/11 System Breakdown: Code 0xC0000001</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-discovering-whistle-acoustics-experience/"><u>New In 2024, Discovering Whistle Acoustics Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-library-synchronization-hitches/"><u>Navigating Through Steam Library Synchronization Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-eliminating-invisible-logins/"><u>Troubleshooting Windows 11: Eliminating Invisible Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-hidden-5ghz-networks-on-windows-11-quick-remedies/"><u>Reveal Hidden 5GHz Networks on Windows 11: Quick Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unlock-full-scale-viewing-on-facebook-for-2024/"><u>[New] Unlock Full-Scale Viewing on Facebook for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-from-raw-recordings-to-professional-vids-webcam-edition/"><u>In 2024, From Raw Recordings to Professional Vids - Webcam Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebooks-free-sound-library-download/"><u>Facebook's Free Sound Library Download</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-delight-in-motion-capturing-irresistible-culinary-shots/"><u>2024 Approved  Delight in Motion  Capturing Irresistible Culinary Shots</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Life360 Notify When You Log Out On Apple iPhone 11 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cured-hyperz-compatibility-fault/"><u>Cured HyperZ Compatibility Fault</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/network-nodes-sites-that-spotlight-youtube-paid-content/"><u>Network Nodes  Sites That Spotlight YouTube Paid Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-nighttime-storyscapes-in-moving-pictures/"><u>[New] Nighttime Storyscapes in Moving Pictures</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-wondering-if-you-can-make-diy-green-screen-video-for-streaming-learn-the-easy-steps-to-setup-diy-green-screen-shoot-the-video-and-edit-it-out-/"><u>2024 Approved Wondering if You Can Make DIY Green Screen Video for Streaming? Learn the Easy Steps to Setup DIY Green Screen, Shoot the Video and Edit It Out to Add Green Screen Effects</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-basics-of-narrative-crafting/"><u>[New] In 2024, Basics of Narrative Crafting</u></a></li>
<li><a href="https://windows11.techidaily.com/best-windows-11-weather-software-compared/"><u>Best Windows 11 Weather Software Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-elevating-notetaking-on-windows/"><u>Master the Art of Elevating Notetaking on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-code-0x0001-complication-in-windows-11/"><u>Unraveling Code 0X0001 Complication in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-oppo-find-x6-pro-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Oppo Find X6 Pro Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-effortless-image-incorrante-on-instagram/"><u>[New] In 2024, Effortless Image Incorrante on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-new-era-of-filesystems-windows-11s-innovations/"><u>Navigating the New Era of Filesystems: Windows 11'S Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resizing-discover-the-top-six-efficient-methods/"><u>Windows 11 Resizing: Discover the Top Six Efficient Methods</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-premium-recording-systems-for-playtime/"><u>2024 Approved  Premium Recording Systems for Playtime</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-winterrals-visual-theme/"><u>Altering WinTerral's Visual Theme</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/360-degree-retail-exploration-tech-for-2024/"><u>360-Degree Retail Exploration Tech for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-firefoxs-best-screen-recorders-roundup/"><u>In 2024, Firefox's Best Screen Recorders Roundup</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-no-audio-output-issue/"><u>Solving Windows: 'No Audio Output' Issue</u></a></li>
</ul></div>
