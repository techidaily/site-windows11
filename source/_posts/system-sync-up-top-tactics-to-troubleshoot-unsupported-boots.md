---
title: "System Sync-Up: Top Tactics to Troubleshoot Unsupported Boots"
date: 2024-08-22T21:42:02.669Z
updated: 2024-08-23T21:42:02.669Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes System Sync-Up: Top Tactics to Troubleshoot Unsupported Boots"
excerpt: "This Article Describes System Sync-Up: Top Tactics to Troubleshoot Unsupported Boots"
keywords: Boot Troubleshooting Tips,System Unsupported Fixes,Troubleshoot Boot Issues,Sync-Up Top Techniques,Supported Boots Guide,Sync Systems Quickly,Top Unsupported Boot Solutions
thumbnail: https://thmb.techidaily.com/3fc4ce39cf32e051d437369f1ad4829a21ac17b8d3ad76e322c0705c64d5daa2.png
---

## System Sync-Up: Top Tactics to Troubleshoot Unsupported Boots

 Secure Boot is a security feature that helps to ensure that only trusted applications are installed on the computer. Although this feature is enabled by default on most computers, you will still likely see the "Secure Boot state unsupported" error while installing Windows 11\.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

## What Causes the "Secure Boot State Unsupported" Error?

[Secure Boot](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) is a feature of modern computers that uses a digital signature to verify the authenticity of the system's software, especially the operating system's files. It is one of the minimum requirements to install Windows 11\.

 Although you can easily [bypass Windows 11's minimum requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/), doing so would adversely affect your computer. You could expect your device to slow down or even crash on a frequent basis.

 Some of the common reasons behind the "Secure Boot state unsupported" error are:

1. You'll likely see the error message if TPM is disabled or not installed on your computer.
2. The error message will appear if Secure Boot is disabled in the BIOS.
3. You'll also encounter the error if BIOS mode is set to Legacy instead of UEFI.

 Now, let's dive into fixes that will help you eliminate the problem.

## 1\. Enable Secure Boot in BIOS

 You must enable Secure Boot in BIOS if you want to install Windows 11 on your computer. But before doing that, view Secure Boot's current state. Here's how to do it:

1. Press the **Win + R** hotkey to open the Run dialog box. Then, type **msinfo32,** and press **Enter**. It'll [open the System information window](https://www.makeuseof.com/windows-open-system-information/).
2. Click **System** **Summary** in the left panel.
3. Check the **Secure Boot State** in the right pane.  
![Secure Boot State in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Secure-Boot-State.jpg)

 If the Secure Boot status is **Off**, you'll have to enable it through your BIOS. To do that, follow the instructions:

1. Open the Settings menu by pressing the Win + I hotkey, and navigate to **System** \> **Recovery.**
2. Click **Restart now** next to **Advanced startup.** It'll restart your computer.  
![Restart Now option next to Advanced Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Now-option.jpg)
3. In the Advanced startup mode, choose **Troubleshoot** and then **Advanced options.**
4. Choose **UEFI Firmware Settings** and click **Restart.** I'll boot you straight into Windows UEFI BIOS.
5. Choose **BIOS Setup.**
6. Switch to **Secure Boot.**
7. Check the box before **Secure Boot Enable.**  
![Enable Secure Boot in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Secure-Boot-1.jpg)

 Note that the steps to [enable Secure Boot](https://www.makeuseof.com/how-enable-tpm-secure-boot-before-upgrading-windows-11/) will be different for different manufacturers. You can check out your manufacturer's BIOS page to know how to do it on your computer.

 Once you've enabled Secure Boot, try to install Windows and check if the problem continues. If yes, then try the next solution on the list.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 2\. Check and Enable TPM Support

 You must have the TPM chip installed on your computer to download Windows 11\. If the TPM chip is missing, you can still install Windows 11 by bypassing the minimum requirement, but then the "Secure Boot state unsupported" error will continue to bother you now and then.

 The problem in the discussion can also appear if TPM is disabled on your computer. To enable TPM, follow the below instructions:

1. Open the Run dialog box.
2. In the search bar, type **tpm.msc** and press Enter.
3. In the TPM management window, click **Actions** in the top bar.
4. Choose **Prepare the TPM** from the context menu.  
![Prepare the TPM in TPM Management Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Prepar-the-TPM.jpg)

 Restart your computer and check for the problem.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Choose UEFI as the BIOS' Mode

 Windows supports two BIOS modes–**UEFI** and **Legacy**. The difference between these two modes is in the process that the firmware uses to locate the boot target.

 You must install Windows using the new UEFI mode as it offers more security features than the Legacy BIOS mode.

 To choose UEFI as the BIOS mode, follow the below steps:

1. Open the BIOS page on your computer.
2. Choose **Boot Sequence** from the left panel.
3. Check the **UEFI option** under **Boot List** Options.  
![UEFI Option in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/UEFI-Option.jpg)
4. Save the changes and restart your computer.

 Again, the process will differ for different manufacturers; therefore, you must check your manufacturer's BIOS page to know how to do it on your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## 4\. Convert the Partition Style From MBR to GPT

 In modern computers, the boot mode is set to UEFI and has GPT (GUID Partition Style) partition style. However, if your computer is using Legacy Boot mode and MBR (Master Boot Record) partition style, then you will face the problem at hand.

 The solution, in this case, is to convert the partition style from MBR to GPT. But before doing that, you must check your computer partition style. Here's how:

1. Press **Win + X** to open the **Power menu.**
2. Choose **Disk Management.**
3. In the Disk Management window, right-click on the hard disk drive and choose **Properties** from the context menu.  
![Properties option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/properties-option.jpg)
4. Switch to the **Volumes** tab.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Check the **Partition style.** If it shows Master Boot Record (MBR), then you will have to convert it to GPT.  
![Partition Style in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Partition-Style.jpg)

 To convert the MBR partition style to GPT, follow the below steps:

1. Open the **Start Menu** by pressing the **Windows** key.
2. Type **Command Prompt** in the search bar and click the **Run as administrator** option in right pane.
3. Type **mbr2gpt /validate /allowfullOS** and press Enter. This command will validate the partition.  
![Validate command option in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/validate-command.jpg)
4. Once the validation is complete, type **mbr2gpt /convert /allowfullOS** and press Enter.

 That's it. Windows will start converting the partition style. The process may take some time, depending on the size of your drive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 5\. Perform a Clean Boot

 Are you still facing the "Secure Boot state unsupported" error? If yes, then you will have to perform a clean boot to troubleshoot the issue. Check out our guide on [how to perform a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) for more information.

 In the clean boot state, check if you're facing the error message again or not.

![System configuration window on desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-configuration-window.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If not, then it indicates that one of the services you disabled was causing the problem. To narrow it down, repeat the above process while slowly re-enabling the services until you see the error again.

 Once you find out which service is the culprit, consider downloading its driver update or running an SFC scan if it's a Windows-based service.

## The "Secure Boot State Unsupported" Error, Fixed

 The "Secure Boot state unsupported" error is a very common issue that appears when you try to install Windows 11\. Fortunately, you can quickly troubleshoot this error by following the above fixes.

 But in the worst-case scenario, if none of the above fixes were helpful, then you will have to clean install Windows.

 The error mainly appears when TPM is disabled on your computer. As such, if you're also facing the same problem, follow the fixes below to troubleshoot the problem for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-enhancing-engagement-tweeting-for-fb-exposure/"><u>[New] 2024 Approved  Enhancing Engagement  Tweeting for FB Exposure</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-quick-tips-turning-off-igtv/"><u>[New] 2024 Approved  Quick Tips  Turning Off IGTV</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-render-your-social-media-footage/"><u>[New] In 2024, Render Your Social Media Footage</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-investigating-ffmpeg-for-intact-audio-preservation/"><u>[New] Investigating FFmpeg for Intact Audio Preservation</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-vocal-variety-at-your-fingertips-top-7-speech-modification-apps-reviewed/"><u>[New] Vocal Variety at Your Fingertips  Top 7 Speech Modification Apps Reviewed</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-vegaspro-2019-update-changes-and-impacts/"><u>[Updated] 2024 Approved  VegasPro 2019 Update  Changes & Impacts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-boosting-revenue-the-content-creators-playbook-for-2024/"><u>[Updated] Boosting Revenue  The Content Creator's Playbook for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-elevate-your-discord-statues-with-fun-emoji-add-ons-for-2024/"><u>[Updated] Elevate Your Discord Statues with Fun Emoji Add-Ons for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-instagrams-hidden-details-uncovering-story-viewer-truths/"><u>[Updated] In 2024, Instagram's Hidden Details  Uncovering Story Viewer Truths</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unveiling-the-secrets-of-facebook-lives-dual-display/"><u>[Updated] Unveiling the Secrets of Facebook Live's Dual Display</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-vivo-y78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/3d-paint-speed-expertise-through-shortcuts/"><u>3D Paint Speed Expertise Through Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/9-benefits-adopting-new-outlook-for-windows-users/"><u>9 Benefits: Adopting New Outlook for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-list-of-fixes-for-disappearing-windows-in-windows-11/"><u>A Comprehensive List of Fixes for Disappearing Windows in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-crafting-slideshows-and-fixing-flaws-in-win11s-photos-app/"><u>A Step-by-Step Approach to Crafting Slideshows & Fixing Flaws in Win11's Photos App</u></a></li>
<li><a href="https://tech-haven.techidaily.com/achieve-job-appeal-write-cover-letters-with-chatgpt-tips/"><u>Achieve Job Appeal: Write Cover Letters with ChatGPT Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/add-emulators-to-playnite-a-windows-guide/"><u>Add Emulators to Playnite: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/adobe-validity-warning-fix-instantly-on-pc/"><u>Adobe Validity Warning: Fix Instantly on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-errors-manage-deps-for-virtualbox-on-windows/"><u>Avoid Errors: Manage Deps for VirtualBox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/awakening-windows-11s-digital-storyteller/"><u>Awakening Windows 11'S Digital Storyteller</u></a></li>
<li><a href="https://windows11.techidaily.com/baffling-boot-concealing-power-buttons-on-windows-11/"><u>Baffling Boot: Concealing Power Buttons on Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/beginners-blueprint-zoom-clustered-conferencing-for-2024/"><u>Beginner's Blueprint  Zoom Clustered Conferencing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/brightening-up-dull-desktop-windows-appearance/"><u>Brightening Up Dull Desktop Windows Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-obstacles-downloading-icloud-on-windows/"><u>Bypassing Obstacles: Downloading iCloud on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-slowdowns-in-gpsvc-windows-errors/"><u>Bypassing Slowdowns in GPSVC Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-files-upload-hurdle-heres-how-to-clear-it-on-windows/"><u>Chrome Files Upload Hurdle? Here's How to Clear It on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/classify-your-hdd-or-ssd-with-ease/"><u>Classify Your HDD or SSD with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-filesystem-crashes-in-win11/"><u>Combatting FileSystem Crashes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-kali-with-windows-os-seamlessly/"><u>Combining Kali with Windows OS Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-pc-capacity-concealed-by-slowness/"><u>Compact PC, Capacity Concealed by Slowness</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-windows-security-blunders-with-ease/"><u>Confronting Windows Security Blunders with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-oculus-quest-to-function-in-windows-pc-virtual-reality/"><u>Converting Oculus Quest to Function in Windows PC Virtual Reality</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-share-problems-in-geforce-software-windows/"><u>Correcting Share Problems in GeForce Software (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-clearance-top-techniques-for-latency-free-video-on-pc/"><u>Cutting-Edge Clearance: Top Techniques for Latency-Free Video on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-build-and-version-numbers-in-windows-os/"><u>Decoding Build and Version Numbers in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/download-and-store-linkedin-videos-the-ultimate-list-of-6-essential-apps/"><u>Download & Store LinkedIn Videos  The Ultimate List of 6 Essential Apps</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-your-lol-game-starts-for-good-expert-strategies-to-tackle-launch-problems/"><u>Fix Your LoL Game Starts for Good: Expert Strategies to Tackle Launch Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-music-on-motorola-razr-40-by-fonelab-android-recover-music/"><u>How to restore wiped music on Motorola Razr 40</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-best-hd-video-screen-recorders/"><u>In 2024, Best HD Video Screen Recorders</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-lock-apps-on-samsung-galaxy-m14-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Samsung Galaxy M14 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-2024-how-to-make-your-memoji-talk-get-creative-with-your-messaging/"><u>In 2024, How To Make Your Memoji Talk? Get Creative With Your Messaging</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-tips-for-a-swift-checkup-of-your-youtube-sign-in/"><u>In 2024, Tips for a Swift Checkup of Your YouTube Sign-In</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/picshot-your-go-to-tool-for-hassle-free-collage-crafting/"><u>Picshot  Your Go-To Tool for Hassle-Free Collage Crafting</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/shotsizesavvy-fine-tuning-your-social-media-content-for-instagram/"><u>ShotSizeSavvy  Fine-Tuning Your Social Media Content for Instagram</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-hands-on-approach-to-google-photos-mastery/"><u>The Ultimate Hands-On Approach to Google Photos Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/1719252317464-understanding-and-fixing-the-common-problem-of-wwinplusp-not-working/"><u>Understanding and Fixing the Common Problem of WWin+P Not Working</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>