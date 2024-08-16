---
title: Unraveling the Mystery of Non-Existent MMC Snaps
date: 2024-08-15T15:36:50.869Z
updated: 2024-08-16T15:36:50.869Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Mystery of Non-Existent MMC Snaps
excerpt: This Article Describes Unraveling the Mystery of Non-Existent MMC Snaps
keywords: NoMCSnapMystery,ExistentialMMCSnap,MMCSnapNonExistence,SNAPMysteryReveal,UncoveringMMCFailure,MMCNoSnapPuzzle,ElucidatingMissingSnaps
thumbnail: https://thmb.techidaily.com/309cf08df9ca66a5508e9f2e2ecebe14a1b42826a0f2e3102f8c44796a0894ed.jpg
---

## Unraveling the Mystery of Non-Existent MMC Snaps

 The "MMC could not create the snap-in" error has been around for some time and still seem to bug some users now and then. The error occurs when you try to open an administrative tool such as an Event Viewer, Task Scheduler, and so forth.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.

## 1\. Fix the Broken Registry Configuration for the Snap-In

![delete-registry-key-mmc-snap-in-windows-registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/delete-registry-key-mmc-snap-in-windows-registry.jpg)

 If the registry configuration for the affected snap-in is broken, it may trigger the "MMC could not create the snap-in" error. To fix the issue, you’ll need to delete the corrupt registry entry associated with the snap-in. Here’s how to do it.

 Making incorrect modifications to the Windows Registry involves risk and may cause your system to malfunction. We recommend you [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [make a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) to be on the safe side.

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MMC\SnapIns`
4. The **SnapIns** key consists of multiple sub-keys. You need to locate the sub-key identical to the **CLSID** shown in the error message.
5. For example, if the error occurs when opening Event Viewer, you’ll likely see **CLSID: c7b8fb06-bfe1-4c2e-9217-7a69a95bbac4**, and so on. So, note down the **CLSID** shown in the error screen.

1. In the **Registry Editor**, select the sub-key folder with the same name as the error **CLSID**.
2. Next, right-click on the same sub-key folder and select **Delete**.
3. Click **Yes** to confirm the action.
4. Close the **Registry Editor** and restart your computer.
5. After the restart, open the administrative tool snap-in to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 2\. Enable .NET Framework

![enable net framework 3 5 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-net-framework-3-5-windows-features.jpg)

 You can also fix this error by enabling .NET Framework 3.5\. The idea is that one of the snap-ins on your PC may need .NET Framework 3.5 to work. So, if the feature is disabled, you may encounter an error.

 Fortunately, you can easily enable the .NET Framework feature using the Turn Windows features on or off dialog. Here’s how to do it.

 To enable .NET Framework 3.5:

1. Press the **Win** key and type **Windows features** and click on **Turn Windows features on or off** from the search results.
2. In the **Windows Features** dialog, select the **.NET Framework 3.5 (include .NET 2.0 and 3.0)**.
3. Next, click the **Plus** icon to expand the section and select the options ‘**Windows Communications Foundation HTTP Activation**’ and **‘Windows Communications Foundation Non-HTTP Activation**’.
4. Next, click to **Apply** the changes and install the feature.
5. Once installed, you’ll be prompted to restart the computer. Restart your system, and the MMC snap-in should work now.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check for and Repair Corrupt System Files

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan-health-restore-health-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 If you have one or more corrupt system files, it may cause issues with the system apps. You can run the System File Checker tool to determine if the problem is due to system file issues. It will scan and check the integrity of systems files and automatically repair them to fix the problem.

 Microsoft recommends running its built-in Windows image check and repair utility, Deployment Image Servicing and Management (DISM), before running the System File Checker utility.

 If you're not sure how to run either of these tools, we cover both in our guide on [how to repair corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Remove and Reinstall the Microsoft Visual C++ Redistributable

![repair microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/repair-microsoft-visual-c-plus-plus-distributable-package.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 If the issue persists, try to fix and repair issues with the Visual C++ Redistributable package. If there are any issues with the package, it can cause the MMC snap-ins to stop working.

 To repair the Visual C++ Redistributable package:

1. Press **Win + R** to open Run.
2. Type "control" and click **OK** to open Control Panel.
3. In Control Panel, click on **Uninstall a program** under **Programs**.
4. Locate and select the **Microsoft Visual C++ Redistributable** entry and click **Uninstall**.
5. In the **Modify Setup** dialog, click **Repair**. The repair process may take a few minutes to complete.
6. Once done, restart your computer and check for any improvements.

 If the issue persists, reinstalling the Visual C++ Redistributable package may be required. To reinstall the package:

![uninstall microsoft visual c plus plus distributable package](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/uninstall-microsoft-visual-c-plus-plus-distributable-package.jpg)

1. Select the **Microsoft Visual C++ package** in Control Panel and click on **Uninstall**.
2. Click **Uninstall** in the **Modify Setup** dialog.
3. Click **Finish** to complete uninstallation. Repeat the process for all the Visual C++ Redistributable packages.
4. Once done, head over to the [Microsoft Visual C++ Redistributable package page](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).
5. Download the latest version of the package available on your computer. Depending on your system compatibility, you can select from ARM64, X86, and X64 architecture versions.
6. Run the executable file to install the package and follow the on-screen instructions.
7. Once installed, restart your computer and check if MMC snap-ins are now working.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Fix the MMC Snap-In and Restore Your Administrative Tools on Windows

 This error is triggered when a snap-in malfunctions, which is often a case of broken registry configuration. To fix the issue, you can delete the broken registry sub-key for the affected snap-in. Additionally, enable/re-enable the .NET Framework 3.5\. If not, scan the system for file integrity issues with the DISM and System File Checker utility.

 Alternatively, you can use the Remote Server Administration Tools (RSAT), which has additional features. RSAT is only available on the Pro and Enterprise edition of the Windows OS. However, you can run a PowerShell script to install it on the Windows Home version easily.

 Sometimes, the error may also pop up after a Blue Screen of Death (BSOD), causing one or more apps to crash. This error often occurs if the registry configuration of the snap-in is malfunctioning. Here we show a few ways to fix to help you resolve the "MMC could not create the snap-in" error and restore administrative tools access in Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-elevate-your-editing-with-blend-mode-innovations/"><u>[New] 2024 Approved  Elevate Your Editing with Blend Mode Innovations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-essential-video-editors-for-cutting-edge-webcams/"><u>[New] In 2024, Essential Video Editors for Cutting-Edge Webcams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapstreak-savvy-guidance-to-prevent-interruptions/"><u>[New] Snapstreak Savvy  Guidance to Prevent Interruptions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unlocking-the-secrets-elevating-your-youtube-presence-in-gameplay/"><u>[New] Unlocking the Secrets  Elevating Your YouTube Presence in Gameplay</u></a></li>
<li><a href="https://extra-resources.techidaily.com/10-best-live-streaming-platforms-you-should-know/"><u>10 Best Live Streaming Platforms You Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/6-precise-ways-to-determine-your-windows-hardware-identity/"><u>6 Precise Ways to Determine Your Window's Hardware Identity</u></a></li>
<li><a href="https://windows11.techidaily.com/7-curious-design-choices-that-differ-from-w10/"><u>7 Curious Design Choices That Differ From W10</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-for-correcting-lsassexe-issue/"><u>A Simple Guide for Correcting 'lsass.exe' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-parsing-misstep-code-0xc00ce556/"><u>Addressing Parsing Misstep: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-screen-flickers-on-microsoft-os/"><u>Addressing Screen Flickers on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/arcade-mode-for-window-users-key-fixes-ahead/"><u>Arcade Mode for Window Users: Key Fixes Ahead!</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-scanning-issues-with-your-geforce-experience-on-windows/"><u>Avoid Scanning Issues with Your GeForce Experience on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/backup-your-cortana-data-for-future-reference-windows/"><u>Backup Your Cortana Data for Future Reference (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-these-5-essential-windows-folder-practices/"><u>Boost Productivity with These 5 Essential Windows Folder Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-alerts-instant-battery-charged-notifications-in-win11/"><u>Boosting Alerts: Instant Battery Charged Notifications in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Motorola Razr 40 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-clutter-fixing-windows-error-0x80072014/"><u>Clearing the Clutter: Fixing Windows Error 0X80072014</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-in-win11-start-fresh/"><u>Configuring Terminal in Win11: Start Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-application-spaces-in-windows-task-mgr/"><u>Controlling Application Spaces in Windows Task Mgr</u></a></li>
<li><a href="https://windows11.techidaily.com/custom-menus-on-windows-1111-with-psoft-tools/"><u>Custom Menus on Windows 11/11 with PSoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-for-enhanced-clarity/"><u>Customizing Graphics Output for Enhanced Clarity</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-microsoft-family-safety-functions/"><u>Demystifying Microsoft Family Safety Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-microsoft-store-failure-codes-x800704cf/"><u>Disabling Microsoft Store Failure Codes X800704CF</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-narzo-60-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Realme Narzo 60 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/latest-solutions-to-fix-a-non-responsive-rust-application-tips-and-insights/"><u>Latest Solutions to Fix a Non-Responsive Rust Application: Tips and Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/1719265109241-master-google-chromes-filesync-on-your-windows-device-now/"><u>Master Google Chrome's Filesync on Your Windows Device Now</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-nine-spectacular-platforms-for-accessing-copyright-free-funny-audio-for-2024/"><u>New Nine Spectacular Platforms for Accessing Copyright-Free Funny Audio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719355454943-opera-installer-dilemma-on-windows-solutions-now/"><u>Opera Installer Dilemma on Windows - Solutions Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tying-emotions-to-the-right-soundtrack-in-movies-for-2024/"><u>Tying Emotions to the Right Soundtrack in Movies for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/be-prodigy-vs-creative-hub-beta-edition-for-2024/"><u>YouTube Prodigy Vs. Creative Hub Beta Edition for 2024</u></a></li>
</ul></div>
