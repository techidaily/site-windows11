---
title: "Decoding Wintools Functions: What Makes CHKDSK Different?"
date: 2024-08-08T05:55:47.175Z
updated: 2024-08-09T05:55:47.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Decoding Wintools Functions: What Makes CHKDSK Different?"
excerpt: "This Article Describes Decoding Wintools Functions: What Makes CHKDSK Different?"
keywords: CHKDSK Overview,Wintool Analysis,CHKDSK Advantages,Data Integrity Check,Disk Utility Features,File System Repair,Error Scan Process
thumbnail: https://thmb.techidaily.com/962100c4bb1cf841eba9a73f110c7891af5a14d4cf3e7d146e6c0272a50f3335.jpg
---

## Decoding Wintools Functions: What Makes CHKDSK Different?

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

## What Is SFC Scannow and When Should You Use It?

 Whereas CHKDSK finds and fixes errors in the file system of your hard drive, **SFC (System File Checker)** specifically scans and repairs Windows system files. If it detects a file has been corrupted or modified, SFC automatically replaces that file with the correct version.

 Knowing when to use SFC is usually more obvious than with CHKDSK, which depends on the hunch that your hard drive isn't behaving correctly. If Windows programs are crashing, you're getting error messages about missing DLL files, or you're experiencing the dreaded Blue Screen of Death, then it's definitely time to run SFC.

[Open an elevated Command Prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), then type the following command and press **Enter** to execute:

`sfc /scannow`

 SFC will perform a full scan of your system and repair and replace any files that are damaged or missing using versions from the Windows component store (read the next section on DISM for more information on this and how SFC and DISM work can work together). The scan can take some time, but make sure you leave the Command Prompt window open until it's complete.

 If you only want to scan but not repair corrupted system files, type:

`sfc /verifyonly command`

 Once SFC has finished scanning, you'll see one of three messages:

* **Windows Resource Protection did not find any integrity violations.** This means that whatever's causing your PC problems isn't related to a system file.
* **Windows Resource Protection found corrupt files and successfully repaired them.** This should hopefully mean that your problems have been solved.
* **Windows Resource Protection found corrupt files but was unable to fix some of them.** This means that system files are to blame, but SFC can't replace them. Try running the tool again in Safe Mode. If you still get the same result, don't despair: it's time to use DISM.

![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is DISM and When Should You Use It?

**DISM (Deployment Image Servicing and Management)** is the most powerful of the three Windows diagnostic tools. Although you shouldn't usually need to use the tools, it's the one to turn to when you're experiencing frequent crashes, freezes, and errors, but SFC either can't repair your system files or is unable to run at all.

 While CHKDSK scans your hard drive and SFC your system files, DISM detects and fixes corrupt files in the component store of the Windows system image so that SFC can work properly. It can also help with Windows updates, driver integration, and boot issues you might be facing.

[Create a backup of your data](https://www.makeuseof.com/tag/ultimate-windows-10-data-backup-guide/) before running DISM, just in case something goes wrong.

 As with CHKDSK and SFC, you'll need to open an elevated Command Prompt (or Administrator Terminal Window on Windows 11) to run DISM. To save you the time and risk of performing repairs unnecessarily, you can first check if the image is corrupted without making any changes. Type the following command and press Enter:

`Dism /Online /Cleanup-Image /CheckHealth`

![windows dism check in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/02/windows-dism-check-in-command-prompt.jpg)

 The scan should only take a few seconds. If no corruption is detected, you can run a more advanced scan to determine if the component store is healthy and repairable, again without making any changes, by typing:

`Dism /Online /Cleanup-Image /ScanHealth`

 If DISM reports that there are problems with the system image, run another advanced scan to repair these issues automatically. DISM will connect to Windows Update to download and replace damaged files as required. Note that the process may take up to 10 minutes and hang for a while at 20 seconds, but this is normal. Type this command:

`Dism /Online /Cleanup-Image /RestoreHealth  
`

![dism scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dism-scan.jpg)

 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-decrease-environmental-noise-in-video-recordings/"><u>[New] Decrease Environmental Noise in Video Recordings</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-enhancing-twitters-visual-capacity-to-fhd-level/"><u>[New] Enhancing Twitter's Visual Capacity to FHD Level</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-silence-to-symphony-enhancing-stories-with-ig-music/"><u>[New] From Silence to Symphony  Enhancing Stories with IG Music</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-audio-addition-for-impactful-instagram-visuals/"><u>[New] Step-by-Step Audio Addition for Impactful Instagram Visuals</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-cross-platform-connections-effortless-insta-facebook-linkup/"><u>[Updated] 2024 Approved  Cross-Platform Connections  Effortless Insta-Facebook Linkup</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-beginners-guide-to-use-lunapic-photo-editor/"><u>[Updated] A Beginner's Guide to Use Lunapic Photo Editor</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-craft-engaging-narratives-for-facebook-reels-for-2024/"><u>[Updated] How to Craft Engaging Narratives for Facebook Reels for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-riding-secure-the-creme-de-la-cam-selection-for-motorcyclists/"><u>[Updated] Riding Secure - The Crème De La Cam Selection for Motorcyclists</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-pc-tasks-swiftly-5-keyboard-cars-expertise/"><u>Drive PC Tasks Swiftly: 5 Keyboard Cars Expertise</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-dns-clearing-on-the-newest-windows-os/"><u>Effective DNS Clearing on the Newest Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-ways-to-erase-defenders-security-chronicles-in-windows/"><u>Efficient Ways to Erase Defender's Security Chronicles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-transform-heic-photos-to-jpeg-via-windows-11/"><u>Efficiently Transform HEIC Photos to JPEG via Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-reminder-placement-on-windows-11-and-10/"><u>Effortless Reminder Placement on Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-windows-updates-switching-to-new-amd-drivers/"><u>Effortless Windows Updates: Switching to New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-ad-ds-errors-impacting-windows-11-printing/"><u>Eliminating AD DS Errors Impacting Windows 11 Printing</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-0x8024a205-in-windows-update/"><u>Eliminating Error 0X8024a205 in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-internal-failure-on-desktop-connections/"><u>Eliminating Internal Failure on Desktop Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-issues-with-windows-alt-key-functions-47-characters/"><u>Eliminating Issues with Windows ALT Key Functions (47 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/embedding-apple-calendar-data-in-windows-desktop-app/"><u>Embedding Apple Calendar Data in Windows Desktop App</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-failed-driver-loading-in-windows-11/"><u>Enabling Failed Driver Loading in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-printer-use-within-windows-11-edge-protection/"><u>Enabling Printer Use Within Windows 11 Edge Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-saga-how-to-smoothly-sync-chromebook-files-in-windows/"><u>End the Saga: How to Smoothly Sync Chromebook Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/energy-efficiency-windows-rest-states-analysis/"><u>Energy Efficiency: Windows' Rest States Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-diagnostics-in-the-latest-windows-versions/"><u>Enhancing Diagnostics in the Latest Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-crafting-shortcuts-next-to-power-on-windows-11/"><u>Enhancing Efficiency: Crafting Shortcuts Next to Power on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-reactivating-silent-notifications/"><u>Enhancing User Experience: Reactivating Silent Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-window-operations-no-more-minimizing/"><u>Enhancing Window Operations: No More Minimizing</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-installation-failed-message-on-discord-for-windows/"><u>Eradicating 'Installation Failed' Message on Discord for Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-steelseries-game-controllers-upgraded-windows-10-compatible-driver-pack-available-now/"><u>Get Your SteelSeries Game Controllers Upgraded: Windows 10 Compatible Driver Pack Available Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-fix-the-iphone-mass-storage-error-with-easy-steps/"><u>How to Fix the iPhone Mass Storage Error with Easy Steps</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-digital-disruptions-a-comprehensive-collection-of-online-sound-effects/"><u>In 2024, Digital Disruptions A Comprehensive Collection of Online Sound Effects</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-nokia-xr21-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Nokia XR21 to PC? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-the-ultimate-tablet-list-for-photographers-going-beyond-filmora/"><u>In 2024, The Ultimate Tablet List for Photographers  Going Beyond Filmora</u></a></li>
<li><a href="https://extra-resources.techidaily.com/shield-identity-in-images-the-most-effective-cropping-tools/"><u>Shield Identity in Images  The Most Effective Cropping Tools</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-oppo-reno-11-pro-5g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Oppo Reno 11 Pro 5G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-blue-badge-breakdown-a-guide-to-social-media-credibility-for-2024/"><u>The Blue Badge Breakdown  A Guide to Social Media Credibility for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Poco F5 Pro 5G | Dr.fone</u></a></li>
</ul></div>