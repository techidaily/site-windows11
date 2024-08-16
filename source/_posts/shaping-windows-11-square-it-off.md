---
title: "Shaping Windows 11: Square It Off"
date: 2024-08-15T15:58:28.849Z
updated: 2024-08-16T15:58:28.849Z
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

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-most-popular-tiktok-items-now-available-on-amazon/"><u>[New] In 2024, The Most Popular TikTok Items Now Available on Amazon</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/iew-count-rewards-on-youtube-per-million/"><u>[New] View Count Rewards on YouTube – Per Million?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-invigorate-clips-with-top-winter-backdrop-choices-for-2024/"><u>[Updated] Invigorate Clips with Top Winter Backdrop Choices for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigate-effortlessly-how-to-clear-your-browsers-youtube-cache/"><u>[Updated] Navigate Effortlessly  How to Clear Your Browser's YouTube Cache</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-complete-mac-powered-guide-to-ootd-videography-for-2024/"><u>[Updated] The Complete Mac-Powered Guide to OOTD Videography for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-21-pioneering-metaverse-ventures-for-insightful-discussion/"><u>2024 Approved  21 Pioneering Metaverse Ventures for Insightful Discussion</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-significance-of-audio-device-isolation-in-windows/"><u>Evaluating the Significance of Audio Device Isolation in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/examining-why-drive-letters-are-missing-from-windows-systems/"><u>Examining Why Drive Letters Are Missing From Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-ignore-or-prevent-expiry-errors/"><u>Fixing Windows 11: Ignore or Prevent 'Expiry' Errors?</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-cease-built-in-desktop-keyboard-in-windows-os/"><u>Guide to Cease Built-In Desktop Keyboard in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-quick-guide-to-oneplus-ace-2v-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to OnePlus Ace 2V FRP Bypass Instantly</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-how-to-use-video-titles-and-youtube-tags/"><u>In 2024, How to Use Video Titles and YouTube Tags?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-top-8-screen-capture-programs-for-linux-experts/"><u>In 2024, Top 8 Screen Capture Programs for Linux Experts</u></a></li>
<li><a href="https://extra-information.techidaily.com/inside-the-directors-domain-comprehensive-guide-to-2024/"><u>Inside the Director's Domain  Comprehensive Guide to 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/interactive-insights-microsofts-innovative-ai-hub/"><u>Interactive Insights: Microsoft's Innovative AI Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-winerror-fixes-for-oculus-app-installation/"><u>Mastering WinError Fixes for Oculus App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unsupported-device-for-windows-hello-login/"><u>Solving 'Unsupported Device' For Windows Hello Login</u></a></li>
<li><a href="https://windows11.techidaily.com/sustained-prominence-of-win-calculator-display/"><u>Sustained Prominence of Win Calculator Display</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-access-controls-with-powertoys-locksmith/"><u>Synchronize Access Controls with PowerToys' Locksmith</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-crafting-a-better-windows-11/"><u>The Art of Crafting a Better Windows 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-analysis-through-infographics/"><u>Trend Analysis Through Infographics</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-shift-in-windows/"><u>Troubleshoot Non-Functional Shift in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-onedrive-windows-methods-to-reclaim-file-storage/"><u>Unblock OneDrive: Windows Methods to Reclaim File Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-component-services-in-windows-11/"><u>Unlocking the Power of Component Services in Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-the-ultimate-guide-to-creating-a-ken-burns-effect-in-software/"><u>Updated In 2024, The Ultimate Guide to Creating a Ken Burns Effect in Software</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-lock-woes-keyboard-mouse-in-win11/"><u>Wake Lock Woes: Keyboard, Mouse in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/waking-up-off-screen-windows-mastering-6-strategies-in-win11/"><u>Waking Up Off-Screen Windows: Mastering 6 Strategies in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11s-official-app-three-ways-to-erase-it/"><u>Win 11'S Official App: Three Ways to Erase It</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-adjusting-your-personalized-fn-keys/"><u>Windows 11: Adjusting Your Personalized FN Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-paper-management-reboot-steps/"><u>Windows Paper Management Reboot Steps</u></a></li>
</ul></div>
