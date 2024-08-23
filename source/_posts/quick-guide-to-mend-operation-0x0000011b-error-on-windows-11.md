---
title: Quick Guide to Mend Operation 0X0000011B Error on Windows 11
date: 2024-08-22T21:38:42.258Z
updated: 2024-08-23T21:38:42.258Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Mend Operation 0X0000011B Error on Windows 11
excerpt: This Article Describes Quick Guide to Mend Operation 0X0000011B Error on Windows 11
keywords: Operating System Error Fix,Win11 Mend0X011B Guide,Quick Solve Windows Error,Error Code,0X011B Fix for Win11,Mend Operation on Win11,Windows Error Guide Quickfix
thumbnail: https://thmb.techidaily.com/6c8487e0b404251fb12aeaebde28154ddd618ecb4b5d51b0cd4522eee48c4e1f.jpg
---

## Quick Guide to Mend Operation 0X0000011B Error on Windows 11

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the[print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  
![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  
![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

## 2\. Install All the Pending Windows Updates

![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
<!-- affiliate ads begin -->

<!-- affiliate ads end -->
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Disable the CVE-2021-1678 Registry Fix

 The problematic security update included a security fix to patch the Printer Spooler Spoofing vulnerability dubbed CVE-2021-1678\. However, the new changes seem to have triggered the 0x0000011B operation failed error.

 To fix the error without uninstalling the security update, you’ll need to create a new registry entry to disable the feature. Here’s how to do it.

 Note that modifying your Windows Registry involves risk. We recommend you[back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and[create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

## Fixing the 0x0000011b Printing Error on Windows

 This error has largely affected Windows 10 computers. To fix the issue, try to install all the pending Windows updates that may include a hotfix. You can also add the printer manually to a local port or edit the registry entry to disable the problematic setting. If nothing works, uninstalling the security update may be the last resort. However, doing so can put your computer at risk of print spooler spoofing vulnerability.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-elevate-your-video-game-the-best-of-8-mirrorless-cams-for-2024/"><u>[New] Elevate Your Video Game  The Best of 8 Mirrorless Cams for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-navigating-video-submission-on-facebook-from-your-gadgets/"><u>[New] In 2024, Navigating Video Submission on Facebook From Your Gadgets</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-invigorating-channel-content-best-video-concepts-to-inspire-viewers/"><u>[New] Invigorating Channel Content  Best Video Concepts to Inspire Viewers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1716069486607-updated-2024-approved-best-free-call-apps-on-android-ranks-them/"><u>[Updated] 2024 Approved  Best Free Call Apps on Android, Ranks Them!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-top-8-screen-recording-apps-in-windows-11-revealed/"><u>[Updated] 2024 Approved  Top 8 Screen Recording Apps in Windows 11 Revealed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-youtube-creation-by-merging-media-and-music-for-2024/"><u>[Updated] Elevate Your YouTube Creation by Merging Media and Music for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-streamline-video-capture-macbook-webcam-tips/"><u>[Updated] Streamline Video Capture  MacBook Webcam Tips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-striking-setups-to-impress-online-audiences/"><u>[Updated] Striking Setups to Impress Online Audiences</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-gadget-guidance-getting-into-googles-video-conference/"><u>2024 Approved  Gadget Guidance  Getting Into Google's Video Conference</u></a></li>
<li><a href="https://windows11.techidaily.com/apples-next-gen-marvel-iphone-15-pro-vs-pro-max-showdown/"><u>Apple's Next-Gen Marvel: IPhone 15 Pro Vs. Pro Max Showdown</u></a></li>
<li><a href="https://fox-glue.techidaily.com/best-software-bundles-for-animation-modelers/"><u>Best Software Bundles for Animation Modelers</u></a></li>
<li><a href="https://win-solutions.techidaily.com/black-desert-pc-issues-resolved-no-more-crashes-here/"><u>Black Desert PC Issues Resolved - No More Crashes Here!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-leading-mobile-signal-enhancement-devices-of-2024-expert-reviews-and-comparisons/"><u>Discover the Leading Mobile Signal Enhancement Devices of 2024: Expert Reviews & Comparisons</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-selecting-the-right-os-for-gaming-glory/"><u>Expert Insights: Selecting the Right OS for Gaming Glory</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-strategies-for-windows-activation-failure-0x803f700f/"><u>Expert Strategies for Windows Activation Failure: 0X803F700f</u></a></li>
<li><a href="https://tech-hub.techidaily.com/external-hard-drive-not-showing-up-in-windows-11-solved/"><u>External Hard Drive Not Showing Up in Windows 11 [Solved]</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-glamour-unveiled-in-decorative-windows/"><u>Festive Glamour Unveiled in Decorative Windows</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-lost-access-to-ubisoft-game-launcher/"><u>Fixing Windows Error: Lost Access to Ubisoft Game Launcher</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/guide-for-fixing-common-windows-11-error-code-c1900101/"><u>Guide for Fixing Common Windows 11 Error Code: C1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-the-msvcr110dll-deficit/"><u>Guide to Overcoming the Msvcr110.dll Deficit</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-re-implementing-windows-11s-search-bar-as-an-icon/"><u>Guide: Re-Implementing Windows 11'S Search Bar as an Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-successfully-update-or-repair-realtek-rtl8beusbdriver/"><u>How to Successfully Update or Repair Realtek RTL8_BE_USB_DRIVER</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/ideal-combo-top-10-recommended-tools-for-vimeo-download-for-2024/"><u>Ideal Combo  Top 10 Recommended Tools for Vimeo Download for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-oppo-reno-8t-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Oppo Reno 8T to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-audio-visual-converters-forum/"><u>In 2024, Audio Visual Converters Forum</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-beware-the-web-of-counterfeit-subscriber-networks-online/"><u>In 2024, Beware the Web of Counterfeit Subscriber Networks Online</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-maximizing-your-time-free-countdown-essentials/"><u>In 2024, Maximizing Your Time  Free Countdown Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-synergy-windows-enables-iphone-and-ipad-with-desktop-power/"><u>Innovative Synergy: Windows Enables iPhone & iPad with Desktop Power</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-wordpad-windows-users-handbook/"><u>Launching WordPad: Windows User's Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-manipulation-of-your-identity-name-on-windows-11/"><u>Masterful Manipulation of Your Identity Name on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-github-desktop-on-windows-step-by-step-guide/"><u>Mastering GitHub Desktop on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-context-menu-with-additional-software-icons/"><u>Mastering Windows 11'S Context Menu with Additional Software Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-errors-with-amd-195-setup/"><u>Mastering Windows Errors with AMD 195 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-maintaining-your-note-apps-data/"><u>Mastery Over Maintaining Your Note App's Data</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-muted-powershell-scripts-four-tactics-to-counter-error-message/"><u>Mastery Over Muted PowerShell Scripts: Four Tactics to Counter Error Message</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-family-safety-your-complete-reference/"><u>Microsoft Family Safety: Your Complete Reference</u></a></li>
<li><a href="https://windows11.techidaily.com/minmax-cpu-states-navigating-windows-power-control/"><u>Min/Max CPU States: Navigating Windows Power Control</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-user-interface-manage-filter-key-options-in-windows/"><u>Optimize User Interface: Manage Filter Key Options in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glance-at-recent-files-in-windows/"><u>Quick Glance at Recent Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-windows-updates-a-step-by-step-guide/"><u>Reinitializing Windows Updates: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsupported-boots-a-5-step-windows-guide/"><u>Resolving Unsupported Boots: A 5-Step Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-input-devices-after-sleep-on-win11/"><u>Reviving Input Devices After Sleep on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-disappearing-results-from-windows-1011-search-tool/"><u>Solving Disappearing Results From Windows 10/11 Search Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-valorant-download-fix-for-windows-users/"><u>Speedy Valorant Download Fix for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-method-for-enabling-windows-11-calculator/"><u>Streamlined Method for Enabling Windows 11 Calculator</u></a></li>
<li><a href="https://windows11.techidaily.com/system-resuscitation-modernizing-windows-driver-technology/"><u>System Resuscitation: Modernizing Windows Driver Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/the-smart-way-to-mitigate-pc-cpu-spikes-via-resource-monitor/"><u>The Smart Way to Mitigate PC CPU Spikes via Resource Monitor</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-guide-to-sims-4-gameplay-capture/"><u>The Ultimate Guide to Sims 4 Gameplay Capture</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-xiaomi-14-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Xiaomi 14 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/unearthing-bsod-traces-within-windows-vista2008/"><u>Unearthing BSOD Traces Within Windows Vista/2008</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-power-top-10-must-have-msistore-picks/"><u>Unleash Power: Top 10 Must-Have MSIStore Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-productivity-a-guide-to-making-multiple-directories-at-once-in-windows/"><u>Unleashing Productivity: A Guide to Making Multiple Directories at Once in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11s-tabbed-views/"><u>Unlock the Full Potential of Windows 11'S Tabbed Views</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-poco-x6-pro-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Poco X6 Pro Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-troubleshooting-alternatives-to-rename-folder-functions/"><u>Win 11 Troubleshooting: Alternatives to Rename Folder Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-product-key-our-guide-to-the-top-deals/"><u>Windows 10 Product Key: Our Guide to the Top Deals</u></a></li>
</ul></div>
