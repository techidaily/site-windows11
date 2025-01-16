---
title: Detailed Steps for Running SFC in Windows OS
date: 2025-01-13T06:36:34.708Z
updated: 2025-01-15T18:27:34.250Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Detailed Steps for Running SFC in Windows OS
excerpt: This Article Describes Detailed Steps for Running SFC in Windows OS
keywords: SFC Run Guide,SFC Command,OS SFC Execute,Fixing Files Windows,System File Checker Use,Windows Repair Tool,SFC Diagnostics Steps
thumbnail: https://thmb.techidaily.com/d77d95aa486b91c6469c5ee9cc4e937e8d3af5aa50ced6b44ad4148b7b19bd91.jpg
---

## Detailed Steps for Running SFC in Windows OS

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.
4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on [what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our [beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by [creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-boxes.techidaily.com/updated-commercial-ventures-enhanced-by-virtual-engineering-for-2024/"><u>[Updated] Commercial Ventures Enhanced by Virtual Engineering for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-mastering-sierras-icloud-drive-accessibility/"><u>[Updated] Mastering Sierra’s iCloud Drive Accessibility</u></a></li>
<li><a href="https://win-solutions.techidaily.com/banish-the-shadows-how-to-fix-fortnite-display-errors-on-windows-platforms/"><u>Banish the Shadows: How to Fix Fortnite Display Errors on Windows Platforms</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgotten-the-voicemail-password-of-poco-c50-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Poco C50? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-your-printers-access-in-win11/"><u>Guaranteeing Your Printer's Access in Win11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your iPhone 14 Pro Max</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-stealth-concealing-drives-on-windows-11-and-10/"><u>Mastering Stealth: Concealing Drives on Windows 11 & 10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/self-filmed-flair-tips-for-captivating-solo-videos-for-2024/"><u>Self-Filmed Flair Tips for Captivating Solo Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-code-with-jdk-on-windows-11/"><u>Streamlining Your Code with JDK on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/surmounting-ram-barriers-in-the-windows-environment/"><u>Surmounting RAM Barriers in the Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-automatic-downtime-on-windows-11-pcs/"><u>The Ultimate Guide to Automatic Downtime on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-formula-for-stunning-images-and-engaging-slide-shows-on-windows-11s-photo-app/"><u>The Winning Formula for Stunning Images and Engaging Slide Shows on Windows 11'S Photo App</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-snipviewer-non-responsive-shortcuts/"><u>Troubleshooting SnipViewer Non-Responsive Shortcuts</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-honor-90-gt-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Honor 90 GT</u></a></li>
<li><a href="https://windows11.techidaily.com/unzipping-and-zipping-made-easy-windows-command-line-guidebook/"><u>Unzipping & Zipping Made Easy: Windows Command Line Guidebook</u></a></li>
</ul></div>

