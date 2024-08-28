---
title: "Win11 Mishap Resolution: Fix for Error Code 0X0000011B"
date: 2024-08-27T16:01:41.077Z
updated: 2024-08-28T16:01:41.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Mishap Resolution: Fix for Error Code 0X0000011B"
excerpt: "This Article Describes Win11 Mishap Resolution: Fix for Error Code 0X0000011B"
keywords: Win11 Fix Error,Code 0X0000011B Solution,Mishap Resolution Guide,Win11 Error Correction,Error 0X11 B Fix,Win11 Troubleshoot Issue,Error Code X00111B Repair
thumbnail: https://thmb.techidaily.com/6462de374e4f489455f584c5102443a7cb28c7609933729fa2bbdde0fb2df507.jpg
---

## Win11 Mishap Resolution: Fix for Error Code 0X0000011B

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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
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
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hot-tunes-essential-background-scores-for-viral-yt-shorts/"><u>[New] 2024 Approved  Hot Tunes  Essential Background Scores For Viral YT Shorts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-into-the-blueprint-cutting-edge-techniques-for-drones/"><u>[New] Into the Blueprint  Cutting-Edge Techniques for Drones</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-masterful-mp4-transformation-tools-facebook-edition/"><u>[New] Masterful MP4 Transformation Tools (Facebook Edition)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-from-one-world-to-another-connecting-instagram-and-facebook/"><u>[Updated] From One World to Another  Connecting Instagram & Facebook</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unlocking-the-meaning-behind-tiktoks-pfp-emoji/"><u>[Updated] In 2024, Unlocking the Meaning Behind TikTok's PFP Emoji</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-gopro-fixing-fish-eye-effects-in-video/"><u>[Updated] Mastering GoPro  Fixing Fish Eye Effects in Video</u></a></li>
<li><a href="https://fox-links.techidaily.com/beyond-wonders-the-unseen-disadvantages-in-vr-for-2024/"><u>Beyond Wonders  The Unseen Disadvantages in VR for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-twitchy-pointer-in-your-desktop-environment/"><u>Fixing a Twitchy Pointer in Your Desktop Environment</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-iphone-se-2022-by-drfone-ios/"><u>Guide on How To Remove Apple ID From iPhone SE (2022)</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-your-way-with-a-clearer-cursor-in-win-11/"><u>Illuminating Your Way with a Clearer Cursor in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-vivetool-unleashing-upcoming-features-for-windows-users/"><u>Introducing ViVeTool: Unleashing Upcoming Features for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-and-compute-file-sizes-an-in-depth-look-at-powershell/"><u>Navigate and Compute File Sizes: An In-Depth Look at PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-powertoys-to-tailor-snap-layouts/"><u>Navigating PowerToys to Tailor Snap Layouts</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-to-windows-11-on-mac-via-parallels-installer/"><u>Navigating to Windows 11 on Mac via Parallels Installer</u></a></li>
<li><a href="https://windows11.techidaily.com/one-key-to-close-clustered-applications-windows-edition/"><u>One Key to Close Clustered Applications: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-permission-hurdles-in-windows-11-environment/"><u>Overcoming Steam Permission Hurdles in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-window-placement-with-sticknotes/"><u>Perfect Window Placement with StickNotes</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-workspace-adding-an-indicator-of-the-current-weather-on-windows-11-taskbar/"><u>Personalize Your Workspace: Adding an Indicator of the Current Weather on Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/photography-made-hassle-free-troubleshooting-windows-camera/"><u>Photography Made Hassle-Free: Troubleshooting Windows Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-approach-to-prevent-dwarven-woes-on-win/"><u>Proactive Approach to Prevent Dwarven Woes on WIN</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnect-the-unreachable-your-guide-to-fixing-usb-wi-fi-in-windows/"><u>Reconnect the Unreachable: Your Guide to Fixing USB Wi-Fi in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-microsofts-0x800713f-mail-glitch-in-win11/"><u>Remedying Microsoft's 0X800713F Mail Glitch in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-slow-or-inactive-windows-downloads-directory/"><u>Reviving Slow or Inactive Windows Downloads Directory</u></a></li>
<li><a href="https://windows11.techidaily.com/steam-deck-ready-instructions-for-windows-installation/"><u>Steam Deck Ready: Instructions for Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategies-for-re-booting-windows-explorer-11/"><u>Swift Strategies for Re-Booting Windows Explorer 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-proven-method-for-stepsigning-in-steam-titles/"><u>The Proven Method for Stepsigning in Steam Titles</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-samsung-galaxy-s23plus-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Samsung Galaxy S23+ to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workflow-top-7-methods-for-windows-11-excellence-42/"><u>Transform Your Workflow: Top 7 Methods for Windows 11 Excellence (42)</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-wu-and-wuo-sync-mechanisms/"><u>Understanding WU & WUO Sync Mechanisms</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-se-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock iPhone SE With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-techniques-for-launching-repair-tools/"><u>Unveiling Techniques for Launching Repair Tools</u></a></li>
</ul></div>
