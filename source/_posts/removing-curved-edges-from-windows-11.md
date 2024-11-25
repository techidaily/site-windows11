---
title: Removing Curved Edges From Windows 11
date: 2024-11-18T19:41:38.159Z
updated: 2024-11-24T20:52:31.322Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Curved Edges From Windows 11
excerpt: This Article Describes Removing Curved Edges From Windows 11
keywords: W11 Edge Smoothening,Window Correction Win11,Rectify Lines in Win11,Fix Curved Windows W11,Eradicate Edges Win11,Flattening W11 Panes,Win11 Edge Sharpness Reduction
thumbnail: https://thmb.techidaily.com/f51042103ff6c3f87c92a84096e29bdaf9eccd433a92cd047a35aea4a9510783.jpg
---

## Removing Curved Edges From Windows 11

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-proactive-copyright-verification-for-your-tiktok-videos/"><u>[New] 2024 Approved Proactive Copyright Verification for Your TikTok Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/iverse-designs-at-your-fingertips-from-these-6-websites-for-2024/"><u>[New] Diverse Designs at Your Fingertips From These 6 Websites for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-unlock-spark-ars-full-potential-with-personalized-lut-implementations/"><u>[New] In 2024, Unlock Spark AR's Full Potential with Personalized LUT Implementations</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-transform-your-gaming-soundscape-ps5-and-ps4-edition-for-2024/"><u>[New] Transform Your Gaming Soundscape PS5 & PS4 Edition for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pioneering-playgrounds-of-action-adventure-classics-top-10/"><u>[Updated] In 2024, Pioneering Playgrounds of Action-Adventure Classics (Top 10)</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-xiaomi-redmi-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/high-res-360-views-gear-vs-lgcam-showdown-for-2024/"><u>High-Res 360 Views Gear vs LGCam Showdown for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-old-machines-skip-the-windows-path/"><u>Resurrecting Old Machines, Skip the Windows Path</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-missing-windows-update-a-step-by-step-guide/"><u>Reviving Missing Windows Update: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-configuration-crashes-with-ease/"><u>Stop Windows Configuration Crashes with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-methods-deleting-saved-wi-fi-in-win-11/"><u>Streamlined Methods: Deleting Saved Wi-Fi in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-systematic-surface-software-updates/"><u>The Essential Guide to Systematic Surface Software Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/the-lost-and-found-getting-windows-10-and-11-back-onscreen/"><u>The Lost and Found: Getting Windows 10 & 11 Back Onscreen</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-authentication-issues-in-windows-os/"><u>Troubleshooting Authentication Issues in Windows OS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-power-and-charm-of-the-apple-imac-215-4k-a-detailed-review/"><u>Unveiling the Power and Charm of the Apple iMac 21.5 4K - A Detailed Review</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-wacatacbml-trojan-how-to-remove-it-from-windows/"><u>What Is the Wacatac.B!ml Trojan? How to Remove It From Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/which-player-enhances-media-experience-more-vlc-vs-mx/"><u>Which Player Enhances Media Experience More? VLC Vs. MX</u></a></li>
</ul></div>

