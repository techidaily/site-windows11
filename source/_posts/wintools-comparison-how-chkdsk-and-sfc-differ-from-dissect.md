---
title: "WinTools Comparison: How CHKDSK and SFC Differ From Dissect"
date: 2024-08-22T21:40:21.802Z
updated: 2024-08-23T21:40:21.802Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinTools Comparison: How CHKDSK and SFC Differ From Dissect"
excerpt: "This Article Describes WinTools Comparison: How CHKDSK and SFC Differ From Dissect"
keywords: WinCheckSysToolComparison,ChkdskVsSfcDiff,SystemScanDissectTools,CHKDSKvsSFCAnalysis,DissectCHKSysCompare,SFCvsChkDskScanning,WinToolsSystemCheckComp
thumbnail: https://thmb.techidaily.com/3a3db1628b8f2814d2040ecfe00634d164ea4b5f3058a85b825026993cb96502.jpg
---

## WinTools Comparison: How CHKDSK and SFC Differ From Dissect

### Quick Links

* [What Is CHKDSK and When Should You Use It?](#what-is-chkdsk-and-when-should-you-use-it)
* [What Is SFC Scannow and When Should You Use It?](#what-is-sfc-scannow-and-when-should-you-use-it)
* [What Is DISM and When Should You Use It?](#what-is-dism-and-when-should-you-use-it)
* [What Order Should You Run CHKDSK, SFC, and DISM In?](#what-order-should-you-run-chkdsk-sfc-and-dism-in)

### Key Takeaways

* CHKDSK scans your hard drive for errors and bad sectors, and you should run it if your computer isn't booting properly.
* SFC scans and repairs Windows system files, so run it when you experience program crashes or missing DLL errors.
* DISM is the most powerful tool and fixes corrupt files in the Windows system image, use it when SFC can't repair files.

 When your PC starts reporting errors, slowing down, or misbehaving, you can use Windows's built-in diagnostic tools to try and fix the problem. CHKDSK, SFC, and DISM check the health of your hard drive and repair corrupt files, but the three tools work in different ways and target different areas of your system.

 CHKDSK, SFC, and DISM are system tools, and you can run all three. However, this can be time-consuming and unnecessary for your specific problem, so it's best to know when and how to use this trio of troubleshooting tools.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-pixiepalette-complete-review-and-instruction-set-2024/"><u>[New] PixiePalette Complete Review & Instruction Set 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweet-snaps-triumph-videos-dominating-discussions/"><u>[New] Tweet-Snaps Triumph  Videos Dominating Discussions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-easyscreen-videotaker-analysis-plus-other-apps/"><u>[Updated] EasyScreen Videotaker Analysis + Other Apps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-snap-income-trends-in-making-money-on-social-media/"><u>[Updated] In 2024, Snap Income  Trends in Making Money on Social Media</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-watch-in-style-top-8-best-mobile-movies-for-iphones/"><u>2024 Approved  Watch in Style  Top 8 Best Mobile Movies for iPhones</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-ways-to-lock-apps-on-iphone-8-and-ipad-securely-drfone-by-drfone-ios/"><u>7 Ways to Lock Apps on iPhone 8 and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-group-of-16-couch-game-pairings-for-xbox-series/"><u>Elite Group of 16 Couch Game Pairings for XBox Series</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-to-tackle-ms-store-hurdle-win1011s-error-0x0/"><u>Expert Advice to Tackle MS Store Hurdle: Win10/11's Error 0X0</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-indexing-service/"><u>Fixing Non-Starting Windows Indexing Service</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-adjust-smartscreen-settings-for-win11-users/"><u>Guide: Adjust SmartScreen Settings for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-windows-powers-for-linux-enhancement/"><u>Harnessing Windows Powers for Linux Enhancement</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-nokia-c12-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Nokia C12 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-infinix-note-30-vip-racing-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Infinix Note 30 VIP Racing Edition? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-adventure-joining-win-11-insiders/"><u>Initiate Your Adventure: Joining Win 11 Insiders</u></a></li>
<li><a href="https://windows11.techidaily.com/instantaneous-access-to-the-calculator-in-windows-11-os/"><u>Instantaneous Access to the Calculator in Windows 11 OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/into-the-metaverse-top-8-vr-wearables-listed-for-2024/"><u>Into the Metaverse  Top 8 VR Wearables Listed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-quick-finds-in-illustrator-a-complete-guide-using-copernic/"><u>Mastering Quick Finds in Illustrator: A Complete Guide Using Copernic</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-address-failed-boot-up-display-driver/"><u>Methods to Address Failed Boot-Up Display Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-flawless-file-handling-discover-copernics-software-secrets-for-maximum-efficiency/"><u>Navigating Flawless File Handling: Discover Copernic's Software Secrets for Maximum Efficiency</u></a></li>
<li><a href="https://fox-info.techidaily.com/pioneering-the-future-workplace-through-virtual-tech-for-2024/"><u>Pioneering the Future Workplace Through Virtual Tech for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagining-your-windows-11-search-experience/"><u>Reimagining Your Windows 11 Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-folder-management-selective-move-on-windows-11/"><u>Revolutionize Folder Management: Selective Move on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-business-data-retrieval-with-advanced-copernic-search-tech-explained/"><u>Revolutionizing Business Data Retrieval with Advanced Copernic Search Tech Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/santa-skims-but-you-need-depth-discover-how-copernic-transforms-your-data-check-with-precision-and-ease/"><u>Santa Skims, But You Need Depth - Discover How Copernic Transforms Your Data Check with Precision and Ease!</u></a></li>
<li><a href="https://windows11.techidaily.com/the-snapshot-navigating-newly-active-windows-items/"><u>The Snapshot: Navigating Newly Active Windows Items</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-ways-copernic-enhances-your-work-from-home-experience/"><u>Top 5 Ways Copernic Enhances Your Work-From-Home Experience</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tracing-the-blue-screen-footsteps-in-windows-xp7/"><u>Tracing the Blue Screen Footsteps in Windows XP/7</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-system-potential-mastery-of-win-registry-cli-edits/"><u>Unlocking System Potential: Mastery of Win Registry CLI Edits</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-gpo-details-using-gpresult/"><u>Unveiling GPO Details Using GPResult</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-tiktok-video-magic-how-to-reverse-speed-up-and-slow-down-your-clips/"><u>Updated 2024 Approved TikTok Video Magic How to Reverse, Speed Up, and Slow Down Your Clips</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-configurations-simplified/"><u>Windows 11 Configurations Simplified</u></a></li>
<li><a href="https://extra-tips.techidaily.com/zombie-sketch-specialist/"><u>Zombie Sketch Specialist</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>