---
title: "WinTools Insight: Exploring Differences in CHKDSK and SFC's Use"
date: 2024-09-05T02:08:03.965Z
updated: 2024-09-06T02:08:03.965Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes WinTools Insight: Exploring Differences in CHKDSK and SFC's Use"
excerpt: "This Article Describes WinTools Insight: Exploring Differences in CHKDSK and SFC's Use"
keywords: CHKDSK vs SFC Analysis,Disk Error Tools Comparison,CHKDSK Functionality Insight,SFC Differences Overview,Windows System Check Tools,Data Integrity Tool Evaluation,Chkdsk and Sfc Use Discrepancy
thumbnail: https://thmb.techidaily.com/7cbb37a561d23a9200d8d1b515569d43214c3157eaf7507ac4a1589610732acc.jpg
---

## WinTools Insight: Exploring Differences in CHKDSK and SFC's Use

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
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is CHKDSK and When Should You Use It?

 CHKDSK (Check Disk) is the first Windows diagnostic tool you should try if your PC starts acting strangely. For example, if it hangs while shutting down or becomes frustratingly slow.

 CHKDSK scans your entire hard drive to find and fix errors in files and the file system itself. It also checks your drive for bad sectors (clusters of data that cannot be read), and either tries to repair them or tells your system not to use them.

 Windows may run CHKDSK on startup if it detects a problem with your hard drive, sometimes for innocuous reasons such as improper shutdown, but also more serious ones, including malware infection and impending drive failure. However, it won't actually fix any issues until instructed to do so.

 To prevent future errors and potential data loss, it's worth running CHKDSK manually as part of your PC maintenance routine. You can use one of the following methods:

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Run CHKDSK Through File Explorer

 You can run CHKDSK from the command prompt. If you're uncomfortable using the Command Prompt, open **File Explorer**, click **This PC**, right-click the drive you want to check and select **Properties**.

 Select the **Tools** tab and then select **Check** in the **Error-checking** section.

![Launch the Check Disk tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-error-checking.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If Windows determines that everything is running smoothly, it will suggest that you don't need to scan the drive. To run CHKDSK anyway, select **Scan drive**.

 The scan may take anywhere from a few minutes to half an hour, depending on the size and state of your drive. Once complete, CHKDSK will either tell you that no errors were found, or if it does find any, it will suggest you fix them.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the scan and repairs are complete, restart your PC and run SFC again to replace your corrupt or missing system files.

## What Order Should You Run CHKDSK, SFC, and DISM In?

 Now that you understand what CHKDSK, SFC, and DISM do, running one or more of these Windows troubleshooting tools will hopefully help you fix your PC.

 However, a common question concerns the order in which you should run these system tests. Should you always run CHKDSK first? Or how about always running DISM before SFC?

 There is no specific order to CHKDSK, SFC, and DISM, as why you run each tool depends on the issue you're experiencing. However, if you run SFC and it finds corrupt files and other issues, you should then run DISM to fix the Component Store and then run SFC again to fix any broken files.

 If you're still having trouble, perform a System Restore. This will restore your system files, settings, and programs to a time when they worked properly. If your system wasn't damaged when the restore point was created, it may solve your corruption problems.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-transformative-beauty-practices/"><u>[New] 2024 Approved  Transformative Beauty Practices</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-camera-editing-showdown-hero-vs-cubes-battle-of-the-screens/"><u>[New] Camera Editing Showdown  Hero Vs. Cube's Battle of the Screens</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-highest-qp-for-gradual-video-playback/"><u>[New] Highest QP for Gradual Video Playback</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-the-ultimate-breakdown-decoding-comprehensiveness-of-xvideo-hub-review/"><u>[New] In 2024, The Ultimate Breakdown  Decoding Comprehensiveness of XVideo Hub Review</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-taking-the-leap-essential-video-gatherings-post-vidcon/"><u>[New] Taking the Leap  Essential Video Gatherings (Post-VidCon)</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-tips-for-producing-high-quality-hdr-photographs-with-lightroom/"><u>[New] Tips for Producing High-Quality HDR Photographs with Lightroom</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-perfecting-podcast-production-an-ultimate-tutorial-for-high-quality-zoom-recordings-for-2024/"><u>[Updated] Perfecting Podcast Production  An Ultimate Tutorial for High-Quality Zoom Recordings for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-uniting-platforms-the-seamless-addition-of-linktree-to-tiktok/"><u>2024 Approved  Uniting Platforms  The Seamless Addition of Linktree to TikTok</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-editing-at-hand-with-powertoys-tools/"><u>Expert Editing at Hand with PowerToys Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-microsoft-store-blockage-on-windows-11/"><u>Fixing Microsoft Store Blockage on Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722975869820-get-your-hands-on-thrustmaster-t150-racing-rapid-download-of-high-quality-drivers/"><u>Get Your Hands on Thrustmaster T150 Racing: Rapid Download of High-Quality Drivers!</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-implementing-rgb-in-windows-11/"><u>Guide to Implementing RGB in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turning-msi-on-or-off-through-group-policy/"><u>Guide to Turning MSI On or Off Through Group Policy</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-honor-70-lite-5g-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Honor 70 Lite 5G</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-apple-iphone-15-plus-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your Apple iPhone 15 Plus?</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-your-cpus-gen-in-windows-top-8-techniques/"><u>Identifying Your CPU's Gen in Windows: Top 8 Techniques</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-oppo-reno-9a-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Oppo Reno 9A Devices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/jump-starting-windows-setup-with-nine-troubleshooting-steps/"><u>Jump-Starting Windows Setup with Nine Troubleshooting Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/leverage-ifttt-to-optimize-to-do-usage/"><u>Leverage IFTTT to Optimize To-Do Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/master-snippet-pasting-windows-shortcuts-for-speed/"><u>Master Snippet Pasting: Windows Shortcuts for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-icloud-setup-tips-for-windows-os/"><u>Masterful iCloud Setup Tips for Windows OS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-visual-enhancements-with-polarrs-platform/"><u>Mastering Visual Enhancements with Polarr's Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-woes-solutions-to-ease-your-way/"><u>Microsoft Woes? Solutions to Ease Your Way!</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-stability-in-windows-1011/"><u>Navigating Network Stability in Windows 10/11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/netgear-orbi-review-the-best-mesh-router-you-can-buy-today/"><u>Netgear Orbi Review: The Best Mesh Router You Can Buy Today</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-optimizing-auditory-experience-windows-edition-with-adobe-premiere-pro-techniques/"><u>New Optimizing Auditory Experience Windows Edition with Adobe Premiere Pro Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/no-charge-fb-visual-storyteller-pro-software/"><u>No-Charge FB Visual Storyteller Pro Software</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-line-interface-use-set-as-primary-app/"><u>Optimize Command Line Interface Use: Set As Primary App</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-file-history-error-in-windows-os/"><u>Overcoming the File History Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-color-calibration-challenges/"><u>Overcoming Windows Color Calibration Challenges</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/rapid-conversion-guide-turning-x265-into-mp4-quickly-and-efficiently/"><u>Rapid Conversion Guide: Turning X265 Into MP4 Quickly and Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/reignite-non-operational-usb-connections-microsoft-os/"><u>Reignite Non-Operational USB Connections, Microsoft OS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-frozen-windows-update-steps-to-fix-when-its-stuck-at-0/"><u>Resolving Frozen Windows Update: Steps to Fix When It's Stuck at 0%%</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-0x80004005-problem-in-windows-virtualbox/"><u>Resolving the 0X80004005 Problem in Windows Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11-invalid-computer-identifier/"><u>Resolving Windows 11: Invalid Computer Identifier</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11s-filesystem-anomalies/"><u>Resolving Windows 11'S Filesystem Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-graphics-connectivity-dxgi-fix-methods/"><u>Restoring Graphics Connectivity: DXGI Fix Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-resolution-riddles-making-windows-monitor-work/"><u>Revealing Resolution Riddles: Making Windows Monitor Work</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-and-streamlining-user-and-group-management-on-win1110-home/"><u>Securing & Streamlining User and Group Management on WIN11/10 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-correcting-windows-xps-c0000005-error/"><u>Steps to Correcting Windows XP's C0000005 Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-methods-to-transform-your-windows-11-initiation/"><u>Streamlined Methods to Transform Your Windows 11 Initiation</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-and-simplifying-docker-operations-on-windows/"><u>Streamlining and Simplifying Docker Operations on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-delve-into-windows-system-statistics/"><u>Swiftly Delve Into Windows System Statistics</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-black-screen-phenomenon-post-boot/"><u>Tackling Black Screen Phenomenon Post-Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-reinforce-stability-and-persistence-of-nvidia-cp-saves/"><u>Tactics to Reinforce Stability and Persistence of Nvidia CP Saves</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-stopping-unwanted-terminal-surface/"><u>Techniques for Stopping Unwanted Terminal Surface</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-the-windows-activation-problem-0x803f700f/"><u>Techniques to Rectify the Windows Activation Problem: 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-regain-access-to-mb-services-on-win11-systems/"><u>Tips to Regain Access to MB Services on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-microsoft-syncs-for-android-from-a-windows-pc/"><u>Top 8 Microsoft Syncs for Android From a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-pc-failure-at-windows-11-upgrade/"><u>Troubleshooting PC Failure at Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-full-potential-of-emojis-in-windows-11/"><u>Unleash Full Potential of Emojis in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-secrets-of-your-system-quick-guide-for-model-names/"><u>Unlock the Secrets of Your System: Quick Guide for Model Names</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-4-secrets-how-to-delete-a-disks-division-in-windows/"><u>Unveiling 4 Secrets: How to Delete a Disk's Division in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-poco-c51-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Poco C51 Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-driver-upgrade-modernizing-audio-compatibility/"><u>Windows Driver Upgrade: Modernizing Audio Compatibility</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>