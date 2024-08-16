---
title: "Defining Windows' Corners: Straighten Them Out"
date: 2024-08-15T15:30:51.390Z
updated: 2024-08-16T15:30:51.390Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Defining Windows' Corners: Straighten Them Out"
excerpt: "This Article Describes Defining Windows' Corners: Straighten Them Out"
keywords: Straighten Corners Windows,Window Edge Alignment,Corner Shaping Windows,Tailored Window Edges,Perfected Window Corners,Fine-Tune Window Angles,Optimize Window Lines
thumbnail: https://thmb.techidaily.com/ea90fc8c45e04f560568c92780cb489093bd55fc49ac8140b1c1038ab7e89004.jpg
---

## Defining Windows' Corners: Straighten Them Out

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/024-approved-from-zero-to-hero-boosting-youtube-view-count-quickly/"><u>[New] 2024 Approved  From Zero to Hero  Boosting YouTube View Count Quickly</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-brief-tips-on-easy-audiovideo-recording-in-gotomeeting/"><u>[New] Brief Tips on Easy Audio/Video Recording in GoToMeeting</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-master-the-art-of-sharing-gaming-moments-xboxfb-livestream-for-2024/"><u>[New] Master the Art of Sharing Gaming Moments  Xbox/FB Livestream for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-building-your-ultimate-youtube-music-list-step-by-step-guide-webmobile-for-2024/"><u>[Updated] Building Your Ultimate YouTube Music List  Step-by-Step Guide (Web/Mobile) for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-direct-links-sharing-twitch-content-with-friends-on-fb/"><u>[Updated] Direct Links  Sharing Twitch Content with Friends on FB</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-how-to-upload-a-video-on-twitter-for-2024/"><u>[Updated] How to Upload a Video on Twitter for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-a-step-by-step-approach-for-adding-soundtracks-to-youtube-clips/"><u>[Updated] In 2024, A Step-by-Step Approach for Adding Soundtracks to YouTube Clips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-free-windows-and-mac-screen-saver-software-with-full-control/"><u>2024 Approved  Free Windows & Mac Screen Saver Software with Full Control</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tips-and-tricks-for-windows-hdr-video-workflows/"><u>2024 Approved  Tips and Tricks for Windows HDR Video Workflows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoid-disruptions-ensuring-presence-of-xinput13dll/"><u>Avoid Disruptions: Ensuring Presence of XINPUT1_3.dll</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/decoding-youtubes-algorithm-the-role-of-keyword-optimization/"><u>Decoding YouTube's Algorithm  The Role of Keyword Optimization</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-hp-color-laserjet-pro-m452dn-driver/"><u>Download HP Color LaserJet Pro M452dn Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-significance-of-audio-device-isolation-in-windows/"><u>Evaluating the Significance of Audio Device Isolation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-controlling-user-profiles-in-windows/"><u>Expert Guide to Controlling User Profiles in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/expert-tips-for-diagnosing-and-repairing-failed-imessage-delivery-on-iphone/"><u>Expert Tips for Diagnosing and Repairing Failed iMessage Delivery on iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-abnormal-display-of-text-on-pcs/"><u>Fixing Abnormal Display of Text on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cease-built-in-desktop-keyboard-in-windows-os/"><u>Guide to Cease Built-In Desktop Keyboard in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-reinvigorate-stuck-desktop-bar/"><u>Guidelines to Reinvigorate Stuck Desktop Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-guarantee-windows-screensaver-immobility/"><u>How to Guarantee Windows Screensaver Immobility</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-on-your-apple-iphone-xr-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID on Your Apple iPhone XR?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-winservicesexe-malfunctions/"><u>How To Tackle WinServices.exe Malfunctions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-steps-to-ensure-quality-film-with-your-iphone/"><u>In 2024, Steps to Ensure Quality Film with Your iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-strategies-top-tips-for-maximizing-wsl-2-performance/"><u>Key Strategies: Top Tips for Maximizing WSL 2 Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-forward-in-workflow-mastering-window-redos-shortcuts/"><u>Leap Forward in Workflow: Mastering Window Redos Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-winerror-fixes-for-oculus-app-installation/"><u>Mastering WinError Fixes for Oculus App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-servers-problems-quick-and-effective-tips/"><u>Navigating Through Servers Problems: Quick & Effective Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-unresizable-gifs-in-windows-11s-discord-woes/"><u>Navigating Through Unresizable GIFs in Windows 11'S Discord Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-pcs-essential-13-tricks-for-restoring-systems/"><u>Rejuvenating PCs: Essential 13 Tricks for Restoring Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-repairing-windows-fragmented-file-issue/"><u>Steps for Repairing Windows Fragmented File Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203164294-struggling-with-pdf-printer-issues-heres-how-to-overcome-them/"><u>Struggling with PDF Printer Issues? Here's How to Overcome Them!</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-operational-diagnostics-in-modern-windows/"><u>Sustaining Operational Diagnostics in Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-access-controls-with-powertoys-locksmith/"><u>Synchronize Access Controls with PowerToys' Locksmith</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-error-non-working-windows-11-voice-access/"><u>Troubleshoot Error: Non-Working Windows 11 Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-iphone-13-mini-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>Unlock Your iPhone 13 mini in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-tasker-show-other-processes/"><u>Why Does Tasker Show Other Processes?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-update-no-more-video-glitches-or-buffering/"><u>Win10 Update: No More Video Glitches or Buffering</u></a></li>
</ul></div>
