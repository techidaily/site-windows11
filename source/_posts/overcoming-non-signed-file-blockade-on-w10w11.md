---
title: Overcoming Non-Signed File Blockade on W10/W11
date: 2024-08-15T15:27:01.891Z
updated: 2024-08-16T15:27:01.891Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Non-Signed File Blockade on W10/W11
excerpt: This Article Describes Overcoming Non-Signed File Blockade on W10/W11
keywords: W10/W11 Unblocking Guide,Signed Files Issue Windows,Overcome Windows W10 Hurdle,Bypass File Block in Win11,Removing Non-Signed Errors,Secure W10 File Access,Trustworthy File Handling
thumbnail: https://thmb.techidaily.com/dd8665fd574b8b8849bc905e8ab75258e662c1b7c7637037d5e86d15b1b9eaa1.png
---

## Overcoming Non-Signed File Blockade on W10/W11

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-enriching-youtube-content-with-improved-sound-quality/"><u>[New] 2024 Approved  Enriching YouTube Content with Improved Sound Quality</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-snapchats-secret-crafting-boomerang-masterpieces/"><u>[New] 2024 Approved  SnapChat's Secret  Crafting Boomerang Masterpieces</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-prime-5-web-based-screening-sessions/"><u>[Updated] 2024 Approved  Prime 5 Web-Based Screening Sessions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/foundations-of-video-editing-in-the-gaming-world-for-2024/"><u>Foundations of Video Editing in the Gaming World for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-a-constant-windows-printer/"><u>Guidelines for a Constant Windows Printer</u></a></li>
<li><a href="https://techidaily.com/hard-reset-motorola-moto-g-5g-2023-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Motorola Moto G 5G (2023) in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-windows-and-wsl-after-a-major-update/"><u>Harmonizing Windows and WSL After a Major Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-automatic-deletion-for-effortless-disk-space-maintainance/"><u>Harnessing Automatic Deletion for Effortless Disk Space Maintainance</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-the-clarity-step-by-step-guide-for-background-blur-in-w11-photos/"><u>Harnessing the Clarity: Step-by-Step Guide for Background Blur in W11 Photos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-12-pro-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 12 Pro Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediuate-switch-text-editor-to-a-dark-scheme-windows-11/"><u>How to Immediuate Switch Text Editor to a Dark Scheme, Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-organize-and-categorize-messages-in-gmail-with-labels/"><u>How to Organize & Categorize Messages in Gmail with Labels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-record-audio-while-screen-recording-in-the-windows-11-snipping-tool/"><u>How to Record Audio While Screen Recording in the Windows 11 Snipping Tool</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-amp-up-illumination-basic-steps-to-lighten-iphone-films/"><u>In 2024, Amp Up Illumination  Basic Steps to Lighten iPhone Films</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-evaluating-macs-leading-snipping-tools-compilation/"><u>In 2024, Evaluating Mac's Leading Snipping Tools Compilation</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-tricks-for-completing-100-windows-update/"><u>Masterful Tricks for Completing 100%% Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-installation-of-the-latest-win11-version-22h2-update/"><u>Mastering Installation of the Latest Win11 Version 22H2 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-way-through-playstation-1-games-in-windows-with-duckstation/"><u>Mastering Your Way Through PlayStation 1 Games in Windows with Duckstation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-11-like-a-pro-essential-search-hacks-revealed/"><u>Navigate Windows 11 Like a Pro: Essential Search Hacks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-native-tools-for-disk-replication/"><u>Navigating Native Tools for Disk Replication</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-system-errors-fixes-for-win11-fs-failures/"><u>Navigating System Errors: Fixes for Win11 FS Failures</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-from-zero-to-hero-top-10-free-and-paid-android-video-editing-apps/"><u>New From Zero to Hero Top 10 Free and Paid Android Video Editing Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/opera-stuck-quick-window-fixes-to-unlock/"><u>Opera Stuck? Quick Window Fixes to Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unwanted-discoloration-clean-your-windows-pc-screen/"><u>Overcoming Unwanted Discoloration: Clean Your Windows Pc Screen</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfect-your-content-with-top-tier-title-tactics-for-2024/"><u>Perfect Your Content with Top-Tier Title Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-your-workspace-ahead-with-w11s-auto-organization-magic/"><u>Propel Your Workspace Ahead with W11's Auto-Organization Magic</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-faster-execution-of-excel-on-windows-pcs/"><u>Reactivating Faster Execution of Excel on Windows PCs</u></a></li>
<li><a href="https://win-forum.techidaily.com/resolving-the-class-not-registered-issue-in-windows-a-step-by-step-guide/"><u>Resolving the 'Class Not Registered' Issue in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/revolutionizing-reality-top-vr-peripherals/"><u>Revolutionizing Reality  Top VR Peripherals</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-to-buy-install-adobe-on-ms-store/"><u>Simplified Guide to Buy, Install Adobe on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-windows-color-control-woes-efficiently/"><u>Solve Window's Color Control Woes Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-audio-recorder-crash-9999-on-windows-platforms/"><u>Solving Audio Recorder Crash 9999 on Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-regaining-router-interface-on-pc/"><u>Strategies for Regaining Router Interface on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-user-experience-with-these-5-tips/"><u>Streamline Your User Experience with These 5 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-boot-sequence-customizing-timeout-window-11/"><u>Streamlining Boot Sequence: Customizing Timeout Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-system-flush-steam-dns-cache-efficiently/"><u>Streamlining Your System: Flush Steam DNS Cache Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-search-highlights-onoff-windows-11-guide/"><u>Switching Search Highlights On/Off: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-files-delete-confirmations/"><u>Tailoring Windows Files' Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/the-experts-guide-to-navigating-with-windows-narrator/"><u>The Expert's Guide to Navigating with Windows Narrator</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-strengths-of-win11-outshining-macos/"><u>Top 6 Strengths of Win11 Outshining MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win-rpc-errors-a-5-step-guide/"><u>Troubleshooting Win RPC Errors - A 5-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-development-power-with-windows-11s-dev-drive-insights/"><u>Uncovering Development Power with Windows 11’S Dev Drive Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/ups-and-downs-on-the-desktop-frontier-comparing-w10-and-w11/"><u>Ups and Downs on the Desktop Frontier: Comparing W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/validate-your-gpus-mettle-using-these-6-tools-on-pc/"><u>Validate Your GPU's Mettle Using These 6 Tools on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-mastery-how-to-install-and-uninstall-optional-add-ons-successfully/"><u>Windows Mastery: How to Install and Uninstall Optional Add-Ons Successfully</u></a></li>
</ul></div>
