---
title: Mastering Domain User Biometric Control in Windows 11
date: 2024-08-15T15:54:58.970Z
updated: 2024-08-16T15:54:58.970Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Domain User Biometric Control in Windows 11
excerpt: This Article Describes Mastering Domain User Biometric Control in Windows 11
keywords: Windows 11 BioControl,User Biometrics W11,Win11 Security Checks,Digital ID Windows 11,Access Control W11,W11 User Authentication,Biometric Domains W11
thumbnail: https://thmb.techidaily.com/9eaae45a5ae000b67c414e7abf4faf363e86f993286beb6923a862b27612bc1e.jpg
---

## Mastering Domain User Biometric Control in Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-best-streaming-cameras-to-boost-viewer-interaction-on-twitch/"><u>[New] In 2024, The Best Streaming Cameras to Boost Viewer Interaction on Twitch</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unveiling-the-trouble-solving-fb-messengers-video-not-sending-flaw/"><u>[New] Unveiling the Trouble  Solving FB Messenger's Video Not Sending Flaw</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/21-witty-tiktok-joke-and-puzzle-collection-for-2024/"><u>21 Witty TikTok Joke & Puzzle Collection for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-motorola-edge-40-neo-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Motorola Edge 40 Neo without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/displayerror-in-windows-ui-graphic-system-ready-for-resolution/"><u>DisplayError in WIndows UI Graphic System (Ready for Resolution)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/drawdream-in-depth-analysis-and-teaching-guide-2024/"><u>DrawDream In-Depth Analysis & Teaching Guide 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortless-and-swift-update-process-for-acer-in-windows-10/"><u>Effortless & Swift Update Process for Acer in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-controlling-user-profiles-in-windows/"><u>Expert Guide to Controlling User Profiles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-abnormal-display-of-text-on-pcs/"><u>Fixing Abnormal Display of Text on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-clearing-winsec-error-limited-administrator/"><u>Guide to Clearing WinSec Error - 'Limited Administrator'</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-reinvigorate-stuck-desktop-bar/"><u>Guidelines to Reinvigorate Stuck Desktop Bar</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-poco-c65-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Poco C65 Phones with/without a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-guarantee-windows-screensaver-immobility/"><u>How to Guarantee Windows Screensaver Immobility</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-winservicesexe-malfunctions/"><u>How To Tackle WinServices.exe Malfunctions</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-se-2020-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone SE (2020) Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-strategies-top-tips-for-maximizing-wsl-2-performance/"><u>Key Strategies: Top Tips for Maximizing WSL 2 Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-forward-in-workflow-mastering-window-redos-shortcuts/"><u>Leap Forward in Workflow: Mastering Window Redos Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-os-settings-with-confidence/"><u>Mastering OS Settings with Confidence</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-virtualupgrade-virtualbox-70-for-new-windows-11-users/"><u>Navigate the VirtualUpgrade: VirtualBox 7.0 for New Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-servers-problems-quick-and-effective-tips/"><u>Navigating Through Servers Problems: Quick & Effective Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-unresizable-gifs-in-windows-11s-discord-woes/"><u>Navigating Through Unresizable GIFs in Windows 11'S Discord Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-saving-windows-audio-configuration-issue/"><u>Overcoming Non-Saving Window's Audio Configuration Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-net-framework-not-installed-message/"><u>Overcoming Windows' .NET Framework Not Installed Message</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-blue-screen-on-windows-11/"><u>Quick Fix for Blue Screen on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/re7-village-follow-up-solutions-to-overcome-black-screen-hiccups-on-pc/"><u>RE7 Village Follow-Up: Solutions to Overcome Black Screen Hiccups on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-pcs-essential-13-tricks-for-restoring-systems/"><u>Rejuvenating PCs: Essential 13 Tricks for Restoring Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-erased-run-commands-logs/"><u>Reviving Erased Run Commands Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/spruce-up-windows-mail-and-schedule-with-personal-photos/"><u>Spruce Up Windows Mail & Schedule With Personal Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/steer-clear-of-incompatible-feature-stickers-in-win11/"><u>Steer Clear of Incompatible Feature Stickers in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-repairing-windows-fragmented-file-issue/"><u>Steps for Repairing Windows Fragmented File Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/sustaining-operational-diagnostics-in-modern-windows/"><u>Sustaining Operational Diagnostics in Modern Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-12-free-disk-defragmentation-tools-of-july-2024/"><u>Top 12 Free Disk Defragmentation Tools of July 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-error-non-working-windows-11-voice-access/"><u>Troubleshoot Error: Non-Working Windows 11 Voice Access</u></a></li>
<li><a href="https://windows11.techidaily.com/why-does-tasker-show-other-processes/"><u>Why Does Tasker Show Other Processes?</u></a></li>
</ul></div>
