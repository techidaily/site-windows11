---
title: Steps to Unraveling 'Failed System Call' Issues in Win10/11
date: 2024-07-11T22:05:05.733Z
updated: 2024-07-12T22:05:05.733Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Unraveling 'Failed System Call' Issues in Win10/11
excerpt: This Article Describes Steps to Unraveling 'Failed System Call' Issues in Win10/11
keywords: Windows Failure Logs,Debugging OS Errors,Kernel Exception Handling,Syscalls Troubleshooting,Win10/Win11 Call Issues,System Calls Resolution,Operating Systems Fixes
thumbnail: https://thmb.techidaily.com/43a1f72d8140b4852b3ec1b168bf1a5fdf9e93b16a9fa8da6c72d7e20d694e32.jpg
---

## Steps to Unraveling 'Failed System Call' Issues in Win10/11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-driven-video-production.techidaily.com/new-how-different-youtube-aspect-ratio-affect-your-video-style-for-2024/"><u>New How Different YouTube Aspect Ratio Affect Your Video Style for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-knots-unraveling-win10-functional-issues/"><u>Keyboard Knots: Unraveling WIN10 Functional Issues</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-ultimate-guide-the-finest-gratis-audio-editor-software-on-windowsmac/"><u>In 2024, Ultimate Guide The Finest Gratis Audio Editor Software on Windows/Mac</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-capturing-facetime-best-practices-unveiled/"><u>2024 Approved  Capturing FaceTime  Best Practices Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-digital-experience-process-control-and-thematic-aesthetics-in-w11/"><u>Elevate Your Digital Experience: Process Control & Thematic Aesthetics in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-hacks-for-identifying-windows-age/"><u>Expert Hacks for Identifying Windows Age</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-list-of-free-video-compressors-for-windows-10/"><u>Updated The Ultimate List of Free Video Compressors for Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-11-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 11 & 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-unleash-the-power-of-your-mi-11s-screen-recording-features/"><u>[Updated] In 2024, Unleash the Power of Your Mi 11'S Screen Recording Features</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-virtual-teamwork-made-simple-on-facebook-live-for-2024/"><u>[New] Virtual Teamwork Made Simple on Facebook Live for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-system-rescue-console-easily/"><u>Launching the System Rescue Console Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhance-your-fb-with-iphonesandroids-favorite-tunes/"><u>Enhance Your FB with iPhones/Androids' Favorite Tunes</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-a-non-working-search-bar-in-windows-11s-settings/"><u>Flipping a Non-Working Search Bar in Windows 11’S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-audio-dynamics-for-bluetooth-devices/"><u>Balancing Audio Dynamics for Bluetooth Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-in-windows-photo-editing/"><u>Advanced Techniques in Windows Photo Editing</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-maximizing-communication-mastering-the-discovoice-on-discord/"><u>New Maximizing Communication Mastering the DiscoVoice on Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/from-backup-bin-to-picture-panel-guiding-games-on-pcs-with-w11/"><u>From Backup Bin to Picture Panel: Guiding Games on PCs with W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/top-10-social-media-live-streaming-platforms-for-2024/"><u>Top 10 Social Media Live Streaming Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-slow-motion-videos-are-taking-over-social-media-and-becoming-a-new-trend-read-this-article-if-you-want-to-learn-how-to-slow-down-video-in-afte/"><u>2024 Approved Slow Motion Videos Are Taking over Social Media and Becoming a New Trend. Read This Article if You Want to Learn How to Slow Down Video in After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-changes-accessing-fax-editor-in-the-newest-os/"><u>Initiating Changes: Accessing Fax Editor in the Newest OS</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-office-applications-open-email-attachments-as-text-only-by-design/"><u>Ensure Office Applications Open Email Attachments as Text Only by Design</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-digital-makeup-mastering-youtubes-chromatic-alignment-for-2024/"><u>[Updated] Digital Makeup  Mastering Youtube's Chromatic Alignment for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-writing-permission-failure-in-windows-10-and-11/"><u>Fixing Writing Permission Failure in Windows 10 & 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-breathe-life-into-tweets-animating-insta-story-texts/"><u>In 2024, Breathe Life Into Tweets  Animating Insta Story Texts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-expressive-youtube-aesthetics-at-no-cost/"><u>[Updated] In 2024, Expressive YouTube Aesthetics at No Cost</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-hidden-items-context-menu-option-in-windows-10-and-11/"><u>How to Add a Hidden Items Context Menu Option in Windows 10 & 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-screen-recording-simplified-top-techniques-unveiled-for-2024/"><u>[Updated] Screen Recording Simplified  Top Techniques Unveiled for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-efail-error-code-0x80004005-in-virtualbox/"><u>Combatting E_FAIL (Error Code: 0X80004005) in Virtualbox</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-overcoming-delayed-or-non-sending-videos-in-facebooks-popular-chat-application-for-mobile-users/"><u>[Updated] In 2024, Overcoming Delayed or Non-Sending Videos in Facebook's Popular Chat Application for Mobile Users</u></a></li>
<li><a href="https://windows11.techidaily.com/a-systematic-approach-to-fixing-the-zeroxc000003e-issue/"><u>A Systematic Approach to Fixing the ZeroXc000003e Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-security-beyond-bitlocker-top-4-choices/"><u>Windows Security Beyond BitLocker: Top 4 Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-worldwide-efficient-mouse-skills-via-powertoys/"><u>Explore Worldwide - Efficient Mouse Skills via PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
</ul></div>
