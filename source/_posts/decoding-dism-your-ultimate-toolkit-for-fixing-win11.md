---
title: "Decoding DISM: Your Ultimate Toolkit for Fixing Win11"
date: 2024-08-15T15:11:29.714Z
updated: 2024-08-16T15:11:29.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding DISM: Your Ultimate Toolkit for Fixing Win11"
excerpt: "This Article Describes Decoding DISM: Your Ultimate Toolkit for Fixing Win11"
keywords: Win11 Repair Guide,Dism Command Basics,Diagnostic Imaging Windows,System File Checker (SFC),Microsoft Drivers Update,Windows Recovery Options,Patch Management Tools
thumbnail: https://thmb.techidaily.com/6509a41b9c53db282ea10c9960943cd0bc0006742138202a2ce5d3d561a1baf2.jpg
---

## Decoding DISM: Your Ultimate Toolkit for Fixing Win11

 Windows 11, like its predecessor, features the built-in Deployment Image Servicing and Management (DISM), a command-line utility to troubleshoot critical system errors. The DISM commands can help you fix Blue Screen of Death (BSOD) errors, a slow computer due to broken system files, and even repair the Windows Recovery Environment.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.

## How to Use the DISM Command in Windows 11

 The DISM command-line utility is a multi-purpose tool. It allows the system administrator to prepare and service Windows images. In addition, you can use the DISM tool in combination with the System File Checker utility to recover your Windows computer from critical failure.

 While DISM supports multiple specified commands, to repair your Windows computer, you only need to know the DISM CheckHealth, DISM ScanHealth, and DISM RestoreHealth commands.

 If you can boot into Windows 11, you can run the DISM command from an elevated PowerShell console or Command Prompt. If not, you’ll need to [boot into the Windows Recovery Environment](boot%20into%20the%20Windows%20Recovery%20Environment) and launch Command Prompt from **Advanced Options** to run DISM.

## Check Your System Health Using the DISM CheckHealth Command

 You can check for any file corruption using the DISM CheckHealth command. It is a diagnostic tool used to detect system image corruption and report the same. However, it doesn’t perform any repair.

 To run the CheckHealth command:

1. Press the **Win** key and type **cmd**.
2. Right-click on **Command Prompt** and select **Run as administrator**.  
![DISM scan health powershell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-clean-health-powershell-command.jpg)
3. In the Command Prompt window, type the following command and press **Enter**:  
`DISM /Online /Cleanup-Image /CheckHealth`
4. In the above command, the **/Online** parameter specifies the scan must be performed on the currently running operating system. The **/Cleanup-Image** parameter specifies the operation is related to Windows image repair.
5. When executed, the command will show the report as “**The component stored has been corrupted**” or “**No component store corrupted detected.**” depending on whether a component store corruption is found.  
![DISM powershell CheckHealth command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-powershell-checkhealth-command.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. If you use PowerShell, use the following command instead:  
`Repair-WindowsImage -Online -CheckHealth`
7. The PowerShell command will report your image status to indicate whether it is **Healthy**, **Repairable** or **Non-repairable**. A healthy image doesn’t need any further action, and you can proceed to run the SFC tool.

 If the image is repairable, you can use the RestoreHealth command to use Windows Update to fix any corruption. However, for a non-repairable image, you may need to perform a clean install to fix your computer.

## Perform an Advanced System Image Scan with the ScanHealth Command

![DISM scan health command PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/dism-scan-health-command-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->

 You can use the DISM ScanHealth command to perform an advanced scan of your Windows 11 system image. This will check your system for component store corruption and save the report to a log file.

 To run the DISM ScanHealth command:

1. Open **PowerShell** as administrator.
2. Type the following command and press Enter:  
`DISM /Online /Cleanup-Image /ScanHealth`
3. This process may take some time to complete. Once done, it will report any issues with the component store.
4. If an issue is detected, run the DISM RestoreHealth command to repair your Windows image.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Run the DISM RestoreHealth Command to Repair the Windows System Image

![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dism-scan-health-restore-health-command-prompt.jpg)

 The DISM RestoreHealth command uses Windows Update to provide the necessary files to fix file corruption and repair the Windows 11 system image. However, you must be connected to the internet so that the DISM tool can download and restore the files needed to perform a repair.

 To run the DISM RestoreHealth command:

1. Open **Windows PowerShell** as administrator.
2. Next, type the following command and press **Enter**:  
`DISM.exe /Online /Cleanup-image /RestoreHealth`
3. The DISM utility will perform a scan and start repairing the Windows system image. This process may take some time to complete. So, wait till the progress bar reaches 100%.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## Repair System Image Using an Alternate Repair Source

 The DISM RestoreHealth command may not work if your computer is not connected to the internet or if the Windows Update component is corrupt. In this situation, you can use a Windows installation media or a mounted Windows ISO as a local source to repair the system image.

 First, [create a bootable Windows 11 USB drive](https://www.makeuseof.com/windows-11-create-bootable-usb-drive/). Once you have the installation media ready, connect it to your computer and proceed with the below steps.

 To repair your Windows 11 system image using DISM and a local repair source:

1. Press **Win + E** to open **File Explorer**.
2. Open your installation media drive, open the **Sources** folder and make sure the **install.wim** file exists. Also, note the driver letter assigned to your installation media. In this instance, our installation media is assigned the drive letter **(I:)**.  
![install wim file in Windows 11 installation media](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-wim-file-in-windows-11-installation-media.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
3. Next, type the following command to run the **DISM RestoreHealth** command with the installation media as a repair source:  
`DISM /Online /Cleanup-Image /RestoreHealth /Source:I\Sources\install.wim /LimitAccess`
4. In the above command, replace the placeholder **:I** with your installation media drive letter. Also, the **LimitAccess** command is an optional parameter that restricts DISM access to the specified source and prevents it from using **Windows Update** as a repair source.
5. Once the process is complete, you can close Command Prompt and run the **System File Checker** utility to complete the repair process.

## Repair Your Windows Installation Using the System File Checker (SFC) Utility

![run system file checker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/run-system-file-checker.png)

 Once you have successfully repaired your Windows 11 system image using the DISM RestoreHealth command, run the System File Checker (SFC) utility. It will scan your Windows installation for system file corruption and fix them automatically.

 In almost all instances, you must run the System File Checker utility after using the DISM image repair command to complete the repair process. Here’s how to do it:

1. Press **Win + X** to open the **WindowsX** menu.
2. Click **Terminal (Admin)** to launch the **Windows** Terminal app as administrator.
3. In the **Terminal** window, type the following command to run the **System File Checker** utility:  
`sfc /scannow`
4. When you run the above command, the System File Checker utility will start verifying the integrity of system files to detect corruption. If detected, it’ll automatically try to repair by replacing the files with a cached copy located at **%WinDir%\\System32\\dllcache.**

 The SFC process may take some time to complete and often may feel stuck at some stage. If you see no progress for a long time, press the **Enter** key a few times on your keyboard to refresh the Command Prompt window to view real-time progress.

 After the process is complete, restart your computer and check for any improvements. If the issue persists, run the **sfc /scannow** command again to see if that helps fix the problem.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Repair and Recover Your Windows System Image Using DISM and SFC

 DISM makes it easy to repair a corrupt Windows image. It works both online using Windows Update and offline with a WIM file. The steps to use DISM may look complicated at first glance; however, it only takes two commands and an elevated Command Prompt to repair your Windows 11 image and installation.

 In this article, we’ll show you how you can use the DISM and System File Checker utility to repair your damaged Windows 11 image and installation.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/0-viral-exercise-routines-to-keep-your-channel-thriving-for-2024/"><u>[New] 10 Viral Exercise Routines to Keep Your Channel Thriving for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-dissecting-the-full-package-logitechs-4k-webcam-experience/"><u>[New] In 2024, Dissecting the Full Package  Logitech’s 4K Webcam Experience</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-raw-footage-to-engaging-content-streamlining-video-edits-on-windows/"><u>[New] In 2024, From Raw Footage to Engaging Content  Streamlining Video Edits on Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-instant-popularity-boost-for-your-tiktok-fandom-for-2024/"><u>[New] Instant Popularity Boost for Your TikTok Fandom for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-by-step-instructions-for-picking-background-scores-for-vlogs/"><u>[New] Step-by-Step Instructions for Picking Background Scores for Vlogs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-clear-recording-software-for-windows-10-users-for-2024/"><u>[Updated] Clear Recording Software for Windows 10 Users for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-twirl-chill-and-groove-the-ultimate-country-playlist-on-tiktok/"><u>[Updated] In 2024, Twirl, Chill, and Groove  The Ultimate Country Playlist on TikTok</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-field-gear-vs-lgcam-comparison/"><u>2024 Approved  Exploring the Field  Gear vs LGCam Comparison</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-introducing-effortless-age-correction-in-profiles/"><u>2024 Approved  Introducing Effortless Age Correction in Profiles</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-optimal-video-balance-top-stabilizer-brands/"><u>2024 Approved  Optimal Video Balance  Top Stabilizer Brands</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-premier-text-motion-manuals/"><u>2024 Approved  Premier Text Motion Manuals</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-public-domain-soundtracks-downloadable-playing-games/"><u>2024 Approved  Public Domain Soundtracks  Downloadable, Playing Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/crafting-your-perfect-minecraft-shelter-for-2024/"><u>Crafting Your Perfect Minecraft Shelter for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-ais-weak-spot-the-art-of-prompt-injection/"><u>Delving Into AI's Weak Spot: The Art of Prompt Injection</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-best-spots-expert-picks-for-cost-free-pre-k-activities/"><u>Discover the Best Spots: Expert Picks for Cost-Free Pre-K Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-scripts-to-discover-your-computers-ip-and-mac-addresses/"><u>Essential Scripts to Discover Your Computer's IP & MAC Addresses</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-fizzles-yule-time-apps-from-microsofts-hub/"><u>Festive Fizzles: Yule-Time Apps From Microsoft's Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-temp-storage-errors-in-the-latest-win11-version/"><u>Fixing Temp Storage Errors in the Latest Win11 Version</u></a></li>
<li><a href="https://windows11.techidaily.com/guidance-for-overcoming-indexer-service-start-up-issues/"><u>Guidance for Overcoming Indexer Service Start-Up Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/guide-to-resolving-microsoft-edge-freezing-problems-for-windows-11-operating-system/"><u>Guide to Resolving Microsoft Edge Freezing Problems for Windows 11 Operating System</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-some-outdated-your-hardware-drivers-with-windows-device-manager-in-windows-11-and-10-by-drivereasy-guide/"><u>How to identify some outdated your hardware drivers with Windows Device Manager in Windows 11 & 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-lava-blaze-pro-5g-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Lava Blaze Pro 5G</u></a></li>
<li><a href="https://os-tips.techidaily.com/how-to-securely-back-up-your-ipad-methods-including-icloud-macbook-itunes-and-external-drives/"><u>How to Securely Back Up Your iPad: Methods Including iCloud, MacBook, iTunes, and External Drives</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-chrome-saving-images-in-webp-format-on-windows/"><u>How to Stop Chrome Saving Images in WebP Format on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-se-2020-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone SE (2020) Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-fixes-for-the-add-your-folder-now-issue-on-windows-onedrive-drive/"><u>Immediate Fixes for the 'Add Your Folder Now' Issue on Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-python-on-windows-for-optimized-file-transfer/"><u>Implementing PYTHON on Windows for Optimized File Transfer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-audio-transitions-audacity-guide/"><u>In 2024, Mastering Audio Transitions  Audacity Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-perfecting-film-grading-a-deep-dive-into-cg-centrals-look-up-tables/"><u>In 2024, Perfecting Film Grading  A Deep Dive Into CG Central's Look-Up Tables</u></a></li>
<li><a href="https://windows11.techidaily.com/less-is-more-compact-view-strategies-for-windows-11/"><u>Less Is More: Compact View Strategies for Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leveraging-cost-free-text-animation-techniques-for-2024/"><u>Leveraging Cost-Free Text Animation Techniques for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/lg-27uhd68-screen-revolution-understanding-4k-sync-technology/"><u>LG 27UHD68 Screen Revolution  Understanding 4K Sync Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-drag-and-drop-in-w11-folder-moving/"><u>Master the Art of Drag & Drop in W11 Folder Moving</u></a></li>
<li><a href="https://driver-error.techidaily.com/master-the-fix-how-to-properly-configure-devices-and-avoid-error-code-1-issues/"><u>Master the Fix: How to Properly Configure Devices & Avoid Error Code 1 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-high-speed-game-updates-in-battlenet/"><u>Mastering High-Speed Game Updates in Battle.net</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-management-wi-fi-removal-guide/"><u>Mastering Network Management: Wi-Fi Removal Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-isdonedll-isarcextract-crashes-on-w10w11/"><u>Mitigating ISDone.dll (ISArcExtract) Crashes on W10/W11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-world-of-advanced-llms-essential-strategies-for-effective-chatgpt-utilization/"><u>Navigating the World of Advanced LLMs: Essential Strategies for Effective ChatGPT Utilization</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-slow-download-issues-with-ease-win/"><u>Overcoming Slow Download Issues with Ease (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-disrupted-voice-command-functionality-on-win11/"><u>Quick Fixes for Disrupted Voice Command Functionality on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-restoring-sync-in-the-microsoft-to-do-application/"><u>Resetting & Restoring Sync in the Microsoft To-Do Application</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-recovering-lost-steam-icons/"><u>Resetting and Recovering Lost Steam Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-visual-problems-with-windows-graphics-driver/"><u>Resolving Visual Problems with Windows Graphics Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpen-windows-keystrokes-seven-tactics-to-decrease-delay/"><u>Sharpen Windows' Keystrokes: Seven Tactics to Decrease Delay</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-overlapping-icons-on-pc/"><u>Solving Overlapping Icons on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-task-managers-dynamic-display-in-windows-11/"><u>Speed up Task Manager's Dynamic Display in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-disabling-restrictions-and-opening-hidden-outlook-directories/"><u>Stepwise Guide to Disabling Restrictions & Opening Hidden Outlook Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-installation-of-dolby-atmos-audio-on-windows-devices/"><u>Stepwise Installation of Dolby Atmos Audio on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-no-network-signal-on-pc/"><u>Tackling No Network Signal on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-unresponsive-back-space-button/"><u>Techniques to Address Unresponsive Back Space Button</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-digital-domains-star-clusters-for-2024/"><u>The Digital Domain's Star Clusters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-a-fortified-pc-with-windows-11-and-tpmsecure-boot/"><u>The Path to a Fortified PC with Windows 11 & TPM/Secure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-methods-for-accessing-iis-manager/"><u>Top 8 Methods for Accessing IIS Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-how-runtime-brokers-affect-system-performance/"><u>Understanding How Runtime Brokers Affect System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-vm-potential-in-windows-through-these-techniques/"><u>Unleash VM Potential in Windows Through These Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-a-fresh-start-with-these-steam-game-tips/"><u>Unlock a Fresh Start with These Steam Game Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-android-gameplay-on-windows-11-with-googles-platform/"><u>Unlock Android Gameplay on Windows 11 with Google's Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-system-tray-and-concealed-options-on-win11/"><u>Unveiling System Tray & Concealed Options on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-sticky-note-access-code-for-windows-11/"><u>Unveiling the Sticky Note Access Code for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-users-dislike-in-windows-11-most/"><u>What Users Dislike in Windows 11 Most</u></a></li>
</ul></div>
