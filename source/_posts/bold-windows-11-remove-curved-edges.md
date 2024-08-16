---
title: "Bold Windows 11: Remove Curved Edges"
date: 2024-08-15T15:15:30.641Z
updated: 2024-08-16T15:15:30.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bold Windows 11: Remove Curved Edges"
excerpt: "This Article Describes Bold Windows 11: Remove Curved Edges"
keywords: Windows Edge Removal,Flat Window Design,Bold Window Edits,Win11 Rectify Corners,Straighten Window Edges,Window Curve Elimination,Uncurved Windows Fix
thumbnail: https://thmb.techidaily.com/8c3061c39eb85dd875af824e1d1149fd13be54628fb79ee748ce5191efb525e2.jpg
---

## Bold Windows 11: Remove Curved Edges

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-seamless-instagram-to-mp4-conversion-on-any-operating-system/"><u>[New] 2024 Approved  Seamless Instagram to MP4 Conversion on Any Operating System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-capture-win10-ranking-the-best-video-grabbers-for-2024/"><u>[New] Capture Win10  Ranking the Best Video Grabbers for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-mastery-of-tasks-with-the-help-of-ez-grabber-for-2024/"><u>[New] Mastery of Tasks with the Help of EZ Grabber for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-enhance-video-appeal-with-filmmaker-friendly-subscribe-button-tutorials-filmora/"><u>[Updated] 2024 Approved  Enhance Video Appeal with Filmmaker-Friendly Subscribe Button Tutorials (Filmora)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-overcoming-the-noise-barrier-twitter-vids-without-sounds/"><u>[Updated] 2024 Approved  Overcoming the Noise Barrier  Twitter Vids Without Sounds</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-skating-stories-from-sochi-2022/"><u>[Updated] Skating Stories From Sochi 2022</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-quick-photovideo-recovery-on-snapchat/"><u>2024 Approved  Quick Photo/Video Recovery on Snapchat</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-solutions-to-hard-reset-htc-u23-pro-phone-using-pc-drfone-by-drfone-reset-android-reset-android/"><u>3 Solutions to Hard Reset HTC U23 Pro Phone Using PC | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-vivo-t2-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Vivo T2 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-fixing-iphone-image-import-issues-in-windows/"><u>Essential Tips for Fixing iPhone Image Import Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-microphone-during-powerpoint-recording/"><u>How to Enable Microphone During PowerPoint Recording</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-huawei-p60-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Huawei P60 to PC? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-pro-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 Pro, Apples New iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/locating-open-tcp-ports-in-windows-os/"><u>Locating Open TCP Ports in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-at-hand-essential-methods-to-decode-qr-codes-on-windows/"><u>Mastery at Hand: Essential Methods to Decode QR Codes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-copy-pasting-like-a-pro-using-powertoys/"><u>Navigate Copy-Pasting Like a Pro Using PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pc-embrace-the-power-of-self-cleaning-files-on-winos/"><u>Optimize Your PC: Embrace the Power of Self-Cleaning Files on WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-your-tech-experience-maintain-win-11-alerts/"><u>Optimizing Your Tech Experience: Maintain Win 11 Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-one-way-outlook-on-safe-windows-mode/"><u>Overcoming One-Way Outlook on Safe Windows Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-challenge-interrupt-exception-in-windows-os/"><u>Overcoming the Challenge: Interrupt Exception in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-how-to-correct-windows-11s-keyboard-type-trouble-code-0x80049dd3/"><u>Quick Guide: How to Correct Windows 11'S Keyboard Type Trouble (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-link-loss-in-winvpn-a-step-by-step-solution/"><u>Restoring Link Loss in WinVPN: A Step-By Step Solution</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/screen-to-air-comparison-who-wins-obs-or-twitch-studio-for-2024/"><u>Screen to Air Comparison  Who Wins, OBS or Twitch Studio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/separate-icons-simplify-win-11-ui/"><u>Separate Icons, Simplify Win 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/shedding-darkness-8-ways-to-lighten-up-windows-desktops/"><u>Shedding Darkness: 8 Ways to Lighten Up Windows Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/skyrocket-above-the-100mbps-ethernet-threshold-in-windows/"><u>Skyrocket Above the 100Mbps Ethernet Threshold in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-erase-office-365-error-30015-26-on-pcs/"><u>Solutions to Erase Office 365 Error 30015-26 on PCs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-mystery-troubleshooting-msxml4dll-file-cannot-be-foundmissing-issue/"><u>Solving the Mystery: Troubleshooting 'Msxml4.dll' File Cannot Be Found/Missing Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-fix-audacitys-device-opens-error-in-windows-1011/"><u>Steps to Fix Audacity’s Device Opens Error in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-your-disconnected-controller/"><u>Steps to Resurrect Your Disconnected Controller</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-preventing-dxgi-errors/"><u>Strategies for Preventing DXGI Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troublesome-windows-programming-issues-7-ways/"><u>Tackling Troublesome Windows Programming Issues (7 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/time-capsule-trick-the-use-of-windows-7-key-for-activating-11/"><u>Time Capsule Trick: The Use of Windows 7 Key for Activating 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-8-criteria-when-expanding-your-4k-setup/"><u>Top 8 Criteria When Expanding Your 4K Setup</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-exercise-monitors/"><u>Top Rated Exercise Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-overcoming-windows-terminal-access-issues/"><u>Troubleshooting: Overcoming Windows Terminal Access Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-navigating-to-windows-11-phone-dialer/"><u>Tutorial: Navigating to Windows 11 Phone Dialer</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-9-steps-for-altering-the-auditory-elements-of-windows-11/"><u>Uncover 9 Steps for Altering the Auditory Elements of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/uncover-the-magic-of-reading-comics-on-windows-11/"><u>Uncover the Magic of Reading Comics on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-windows-roblox-code-403-issue/"><u>Understanding & Fixing Windows Roblox Code 403 Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-advanced-techniques-for-blurry-backgrounds-in-w11-photo-feature/"><u>Unveiling Advanced Techniques for Blurry Backgrounds in W11 Photo Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-illusion-blending-image-and-archive-data-without-notice-win1011/"><u>Visual Illusion: Blending Image and Archive Data without Notice WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-the-essential-manual/"><u>Win11 Offline: The Essential Manual</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-subscriber-chart-the-5-most-subscribed-youtube-channels-for-2024/"><u>YouTube Subscriber Chart - The 5 Most Subscribed YouTube Channels for 2024</u></a></li>
</ul></div>
