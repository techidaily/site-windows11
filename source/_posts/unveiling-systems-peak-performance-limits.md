---
title: Unveiling System's Peak Performance Limits
date: 2024-07-29T04:21:54.557Z
updated: 2024-07-30T04:21:54.557Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling System's Peak Performance Limits
excerpt: This Article Describes Unveiling System's Peak Performance Limits
keywords: Peak Performance Analysis,Max Performance Boundaries,System Optimization Thresholds,Efficiency Growth Points,Operational Limit Exploration,Productivity Cap Assessment,Output Maximization Study
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## Unveiling System's Peak Performance Limits

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/2024-approved-power-play-essential-10-motivational-films/"><u>2024 Approved  Power Play  Essential 10 Motivational Films</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-transform-your-streaming-enabling-av1-technology-in-youtube/"><u>2024 Approved  Transform Your Streaming  Enabling AV1 Technology in YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-win11-taskbar-icon-dimensions/"><u>Adjusting Win11 Taskbar Icon Dimensions</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-finding-out-charge-status-win-1011/"><u>Advanced Techniques: Finding Out Charge Status (Win 10/11)</u></a></li>
<li><a href="https://windows11.techidaily.com/battle-of-the-packagers-chocolatey-or-wm-on-windows-pcs/"><u>Battle of the Packagers: Chocolatey or WM on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-grayed-screen-savers-quick-fixes-for-windows-users/"><u>Curing Grayed Screen Savers: Quick Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-motorola-frp-by-drfone-android/"><u>Full Guide to Bypass Motorola FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-0x800f0845-failure/"><u>How to Address 0X800f0845 Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-ms-defenders-blockage-on-third-party-av/"><u>How to Bypass MS Defender's Blockage on Third-Party AV</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-wordpad-in-windows/"><u>How to Open WordPad in Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-instagrams-newest-filters-how-to-use-them-for-impact/"><u>In 2024, Instagram's Newest Filters  How to Use Them for Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-storage-with-onedrive-rearrange-for-win-11/"><u>Managing Storage with OneDrive – Rearrange for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-solo-sound-output-in-windows-audio-device/"><u>Mending Solo Sound Output in Windows Audio Device</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-notifications/"><u>Muting Windows Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-computer-no-need-for-windows-11-upgrades/"><u>Optimize Your Computer: No Need for Windows 11 Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-constant-calculator-positioning-on-pcs/"><u>Optimizing Constant Calculator Positioning on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-chromes-file-uploading-frustrations-on-a-pc/"><u>Overcome Chrome's File Uploading Frustrations on a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-lost-steam-games-symbols/"><u>Preventing and Fixing Lost Steam Games Symbols</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/prime-imagery-for-virtual-sessions-tips-and-tricks-for-2024/"><u>Prime Imagery for Virtual Sessions  Tips & Tricks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-empty-folder-notifications/"><u>Remedying Empty Folder Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-connection-issues-with-googles-nearby-sharing/"><u>Resolving Connection Issues with Google's Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-microsofts-phone-tethering-for-windows-11-users/"><u>Revisiting Microsoft's Phone Tethering for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-wows-abrupt-server-quit-error-132-in-win11/"><u>Solutions for WoW's Abrupt Server Quit (Error 132) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-disabling-windows-wi-fi-broadcast/"><u>Stealth Mode: Disabling Windows Wi-Fi Broadcast</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-absent-app-in-windows-filesystem/"><u>Strategies to Fix Absent App in Windows Filesystem</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-prevent-and-fix-windows-error-code-0xc00000f/"><u>Strategies to Prevent & Fix Windows Error Code 0Xc00000f</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-aid-for-windows-issues-in-googles-nearby-share-app/"><u>Tactical Aid for Windows Issues in Google's Nearby Share App</u></a></li>
<li><a href="https://techidaily.com/the-5-best-methods-to-track-a-lost-or-stolen-iphone-11-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>The 5 Best Methods to Track a Lost or Stolen iPhone 11 | Stellar</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/top-10-memes-blending-hilarity-and-emotional-depth-on-insta/"><u>Top 10 Memes Blending Hilarity and Emotional Depth on Insta</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-10-password-cracking-tools-for-vivo-y100a-by-drfone-android/"><u>Top 10 Password Cracking Tools For Vivo Y100A</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-guide-premier-live-streaming-plus-local-channels-2024/"><u>Ultimate Guide  Premier Live Streaming + Local Channels 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-for-optimal-clipchamp-functionality/"><u>Unlocking Windows 11 for Optimal ClipChamp Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tab-issue-solutions-for-non-responsive-keys/"><u>Windows Tab Issue: Solutions for Non-Responsive Keys</u></a></li>
</ul></div>
