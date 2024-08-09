---
title: "Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
date: 2024-08-08T05:55:51.916Z
updated: 2024-08-09T05:55:51.916Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
excerpt: "This Article Describes Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions"
keywords: Windows CHKDSK,System SFC Fix,DISM Diagnostic Tool,CHKDSK Utility,SFC Error Repair,System File Checker,Disable Integrity Failures
thumbnail: https://thmb.techidaily.com/7190f701d24b2bca2702a5bcd803eaeb74415822adafed338c6c5049f6c7aefb.jpg
---

## Delving Into Windows Tools: CHKDSK, SFC & DISM's Functions

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

## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Run CHKDSK From the Command Prompt

 For greater control over the disk-checking process, you should run CHKDSK from an elevated Command Prompt. Follow these steps to continue:

1. Press the **Win** \+ **R** keys to open the Run dialog.
2. Type "cmd" in Run and press the **Ctrl** \+ **Shift** \+ **Enter** keys together to open Command Prompt as an administrator.
3. Click **Yes** in the User Account Control prompt.
4. In the Command Prompt window, type **chkdsk,** then space, followed by the drive letter you want to check. For example, **chkdsk c:** to scan your C: drive.  
![CHKDSK scan in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/chkdsk-scan.jpg)
5. Press **Enter** to scan for errors in read-only mode, which means no changes will be made.

 To make changes, you can use parameters with the CHKDSK command. Here are two you can use to fix problems:

* To make CHKDSK fix the problems it finds, type **chkdsk /f c:** (for your C: drive).
* To scan for bad sectors and errors, type **chkdsk /r c:**

 If you cannot run these commands because "the volume is in use by another process," Command Prompt will offer to schedule the scan for when your PC restarts. This should, however, only happen once. If the tool pops up whenever you boot your PC, you can [stop CHKDSK from running at every startup](https://www.makeuseof.com/tag/stuck-chkdsk-use-fix-right-way/) manually.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of complete sfc scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/screenshot-of-complete-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
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
<li><a href="https://desktop-recording.techidaily.com/new-exclusive-selection-of-elite-race-games/"><u>[New] Exclusive Selection of Elite Race Games</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-temporaryfreeze-immediate-recording-guide/"><u>[New] In 2024, TemporaryFreeze  Immediate Recording Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unveiling-fake-followers-on-instagram-effortlessly-for-2024/"><u>[New] Unveiling Fake Followers on Instagram, Effortlessly for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-boosting-fb-video-engagement-and-audience-reach/"><u>[Updated] In 2024, Boosting FB Video Engagement & Audience Reach</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-a-step-by-step-walkthrough-to-change-profile-pictorials/"><u>2024 Approved  A Step-by-Step Walkthrough to Change Profile Pictorials</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/a-beginners-pathway-to-iphone-audio-memos/"><u>A Beginner's Pathway to iPhone Audio Memos</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-oppo-find-x7-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Oppo Find X7? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-motorola-edge-40-has-native-mkv-support-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Motorola Edge 40 has native MKV support?</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-and-instaling-windows-11-arm-a-streamlined-process/"><u>Downloading & Instaling Windows 11 ARM - A Streamlined Process</u></a></li>
<li><a href="https://windows11.techidaily.com/downloading-woes-fixing-file-transfer-issues-in-windows-11/"><u>Downloading Woes: Fixing File Transfer Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-enlarge-or-decrease-taskbar-in-win11/"><u>Easily Enlarge or Decrease Taskbar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-techniques-for-deactivating-win11s-hyper-v/"><u>Easy Techniques for Deactivating Win11's Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-desktop-organization-fixing-gmails-taskbar-spot/"><u>Effective Desktop Organization: Fixing Gmail's Taskbar Spot</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-hardware-diagnosis-tools/"><u>Effective Hardware Diagnosis Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-restore-functioning-asana-on-windows-machines/"><u>Effective Methods to Restore Functioning Asana on Windows Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-word-lookups-for-newbies-to-win11/"><u>Efficient Word Lookups for Newbies to Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-access-the-microsoft-store/"><u>Effortlessly Access the Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-accessing-windows-mixer-settings/"><u>Effortlessly Accessing Window's Mixer Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-desktop-8-winbubble-methods-for-window-tailoring/"><u>Elevate Your Desktop: 8 WinBubble Methods for Window Tailoring</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-low-sound-levels-for-external-speakers/"><u>Elevating Low Sound Levels for External Speakers</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-error-rebuild-failed-java-virtual-machine/"><u>Eliminate Error: Rebuild Failed Java Virtual Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-boltguns-lags-winning-techniques-for-windows-users/"><u>Eliminating Boltgun's Lags: Winning Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-chrome-profiles-errors-on-your-workstation/"><u>Eliminating Chrome Profiles Errors on Your Workstation</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-faulty-printer-response-in-ad-ds-win-10-and-11/"><u>Eliminating Faulty Printer Response in AD DS, WIN 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-icon-grouping-in-windows-11/"><u>Eliminating Icon Grouping in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-team-error-80080300-in-windows-11/"><u>Eliminating Team Error 80080300 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-win1011-error-0xc0000001/"><u>Eliminating Win10/11 Error 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-notepad-system-breakdowns/"><u>Eliminating Windows Notepad System Breakdowns</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-device-detection-for-razer-gear-in-windows-11/"><u>Enabling Device Detection for Razer Gear in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enablingdisabling-wi-fi-cost-monitor-in-win11/"><u>Enabling/Disabling Wi-Fi Cost Monitor in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-night-vision-with-dark-mode-for-notepad-on-win-11/"><u>Enhance Night Vision with Dark Mode for Notepad on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-master-distributed-transcoding-with-tdarr/"><u>Enhance PC: Master Distributed Transcoding with Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-performance-with-customized-windows-11-configurations/"><u>Enhance Performance with Customized Windows 11 Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-productivity-unleash-potential-via-flow-launcher/"><u>Enhance Productivity: Unleash Potential via Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-speech-recognition-in-windows-pc/"><u>Enhance Speech Recognition in Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-computer-experience-with-worldwide-mouse-expertise-in-powertoys/"><u>Enhance Your Computer Experience with Worldwide Mouse Expertise in PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-identity-management-in-win11-pro/"><u>Enhancing User Identity Management in Win11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-performance-hiccups-a-guide-to-optimizing-warhammer-on-windows/"><u>Eradicate Performance Hiccups: A Guide to Optimizing Warhammer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-overload-in-win-based-software-with-ease/"><u>Eradicating Overload in Win-Based Software with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/error-in-snipper-find-9-steps-for-swift-remedy/"><u>Error in Snipper? Find 9 Steps for Swift Remedy</u></a></li>
<li><a href="https://windows11.techidaily.com/escalate-typing-pace-via-windows-powertoys/"><u>Escalate Typing Pace via Windows' PowerToys</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/exploring-the-best-audio-capture-technology-for-apple-devices-for-2024/"><u>Exploring the Best Audio Capture Technology for Apple Devices for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebook-today-changes-and-what-they-mean-for-you-for-2024/"><u>Facebook Today  Changes and What They Mean for You for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/fifa-highlights-and-trends-charting-on-youtube/"><u>FIFA Highlights & Trends  Charting on YouTube</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-realme-c67-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-ingenious-approaches-to-facebook-video-ad-crafting/"><u>In 2024, Ingenious Approaches to Facebook Video Ad Crafting</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rethink-your-classic-movies-best-swaps-7/"><u>In 2024, Rethink Your Classic Movies - Best Swaps #7</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-best-free-video-splitters-for-mkv-files-updated-2023-for-2024/"><u>New Best Free Video Splitters for MKV Files (Updated 2023) for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/pricing-outline-the-cost-to-film-melodies-visually-for-2024/"><u>Pricing Outline  The Cost to Film Melodies Visually for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/zipping-and-textifying-a-guide-to-crafting-srt-from-zip/"><u>Zipping and Textifying  A Guide to Crafting Srt From Zip</u></a></li>
</ul></div>
