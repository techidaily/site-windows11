---
title: Troubleshooting Techniques to Fix Win11 System Call Errors
date: 2025-01-13T21:10:45.545Z
updated: 2025-01-15T17:47:28.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Techniques to Fix Win11 System Call Errors
excerpt: This Article Describes Troubleshooting Techniques to Fix Win11 System Call Errors
keywords: Win11 Troubleshoot Guide,System Call Fix in Win11,Win11 Error Resolution,Win11 System Repair Steps,Solve Win11 System Calls,Win11 Fault Diagnosis Tips,Correcting Win11 Failures
thumbnail: https://thmb.techidaily.com/8d4f635de6f8288e79a21d2dcf9027cad8747323c88b4f310acedbe966d2fadc.jpg
---

## Troubleshooting Techniques to Fix Win11 System Call Errors

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-uncovering-8-superior-online-srt-translation-tools/"><u>[New] 2024 Approved Uncovering 8 Superior Online SRT Translation Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-superior-viewing-experience-essentials-of-4k-downloading/"><u>[Updated] Superior Viewing Experience Essentials of 4K Downloading</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/apples-next-big-thing-cutting-edge-ar-glasses-and-budget-friendly-headsets-on-the-horizon-according-to-zdnet/"><u>Apple's Next Big Thing: Cutting-Edge AR Glasses and Budget-Friendly Headsets on the Horizon, According to ZDNET</u></a></li>
<li><a href="https://windows11.techidaily.com/beginners-manual-discovering-windows-aids-and-assists/"><u>Beginner's Manual: Discovering Windows Aids and Assists</u></a></li>
<li><a href="https://windows11.techidaily.com/brushstrokes-begin-accessing-microsoft-paint-in-windows-11/"><u>Brushstrokes Begin: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-lava-agni-2-5g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Lava Agni 2 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-smooth-os-operation-autoupdate-and-change-amd-drivers/"><u>Ensure Smooth OS Operation: Autoupdate & Change AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-strategies-for-overcoming-windows-error-code-0x80040610/"><u>Essential Strategies for Overcoming Windows Error Code 0X80040610</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-forgot-locked-iphone-6s-plus-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone 6s Plus Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://fox-http.techidaily.com/mastering-video-capture-on-periscope-a-comprehensive-manual/"><u>Mastering Video Capture on Periscope A Comprehensive Manual</u></a></li>
<li><a href="https://tech-haven.techidaily.com/overcoming-chatgpt-authentication-hiccups-fixing-logon-errors-effectively/"><u>Overcoming ChatGPT Authentication Hiccups: Fixing Logon Errors Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-default-usb-suspension-on-windows-11/"><u>Overcoming Default USB Suspension on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-failed-jvm-launch-windows-guide/"><u>Remedying Failed JVM Launch: Windows Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-technical-difficulties-during-helldivers-2-playthroughs-on-pc/"><u>Resolving Technical Difficulties During Helldivers 2 Playthroughs on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/supporting-the-unsupported-life-after-windows-781/"><u>Supporting the Unsupported: Life After Windows 7/8.1</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-the-ultimate-list-of-free-malware-detectors-ranked-1-5/"><u>Unveiling the Ultimate List of Free Malware Detectors Ranked #1 - 5</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-step-by-step-process-disabling-video-sound-in-latest-mkv-format-mkv-2023/"><u>Updated In 2024, Step-by-Step Process Disabling Video Sound in Latest MKV Format (MKV-2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-how-to-stop-game-proposals/"><u>Win11: How To Stop Game Proposals</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-battle-against-windows-software-problems-7-ways/"><u>Winning the Battle Against Windows Software Problems (7 Ways)</u></a></li>
</ul></div>

