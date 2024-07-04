---
title: "Shaping Windows 11: Square It Off"
date: 2024-06-25T12:15:12.476Z
updated: 2024-06-26T12:15:12.476Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shaping Windows 11: Square It Off"
excerpt: "This Article Describes Shaping Windows 11: Square It Off"
keywords: Win11Upgrade,UpgradeWindows,NewOSFeatures,SquarifyWin,ModernUIWindows,WindowsSquareLayout,NewWindowsDesign
thumbnail: https://thmb.techidaily.com/212e21d96bc4724d21a24c1110e599b63bc2c397e891bb1e1f9fc06be1f08b00.jpg
---

## Shaping Windows 11: Square It Off

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

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/ensuring-reliable-remote-access-across-windows-networks/"><u>Ensuring Reliable Remote Access Across Windows Networks</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-interruptexception-on-windows-11/"><u>Tackling the INTERRUPT_EXCEPTION on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-security-beyond-bitlocker-top-4-choices/"><u>Windows Security Beyond BitLocker: Top 4 Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-roadblocks-activating-non-functional-scripts-in-windows/"><u>Overcoming Roadblocks: Activating Non-Functional Scripts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/taskers-edge-enigma-hidden-processes/"><u>Tasker's Edge Enigma: Hidden Processes?</u></a></li>
<li><a href="https://windows11.techidaily.com/top-10-uses-for-windows-powertoys-tools/"><u>Top 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-xiaomi-redmi-k70-pro-by-fonelab-android-recover-data/"><u>The way to get back lost data from Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-create-ai-videos-using-synthesia-avatar-and-voices/"><u>New Create AI Videos Using Synthesia Avatar and Voices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-nubia-red-magic-8s-proplus-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Nubia Red Magic 8S Pro+ Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-background-music-compilations-for-2024/"><u>Premium Background Music Compilations for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-samsung-galaxy-m14-4g-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Samsung Galaxy M14 4G.</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/do-you-know-adding-subtitles-can-benefit-video-content-meanwhile-for-adding-subtitles-to-a-video-wondershare-filmora-can-help-you-for-2024/"><u>Do You Know Adding Subtitles Can Benefit Video Content? Meanwhile, for Adding Subtitles to a Video, Wondershare Filmora Can Help You for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-resize-images-online-8-efficient-aspect-ratio-changers-for-2024/"><u>New Resize Images Online 8 Efficient Aspect Ratio Changers for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-unlocking-compressors-full-potential-in-fcpx-for-2024/"><u>New Unlocking Compressors Full Potential in FCPX for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-tecno-phantom-v-flip-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Tecno Phantom V Flip Screen Sharing | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>