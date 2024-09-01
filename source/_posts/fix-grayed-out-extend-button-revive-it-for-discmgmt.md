---
title: Fix Grayed-Out Extend Button, Revive It for DiscMgmt
date: 2024-08-31T22:11:59.758Z
updated: 2024-09-01T22:11:59.758Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Grayed-Out Extend Button, Revive It for DiscMgmt
excerpt: This Article Describes Fix Grayed-Out Extend Button, Revive It for DiscMgmt
keywords: Fix Extend Button Issue,Resurrect Grayed-Out Button,Reverse Button Disability,Reactivate Disabled Button,Restore Extended Controls,Extend Button Functionality,Unlock Grayed-Out Buttons
thumbnail: https://thmb.techidaily.com/2b667f6d425e137d74634d5b5e43d01ba3b3015e34fc38e54ba016f1aa0f02aa.jpg
---

## Fix Grayed-Out Extend Button, Revive It for DiscMgmt

 The "extend volume" option in the Disk Management tool enables you to increase the size of a volume or partition. However, there may be a situation where the extend volume option may be grayed out, preventing you from increasing the volume.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

## Why Is the Extend Volume Option Grayed Out on Windows?

 If you see the extend volume option is grayed out in the Disk Management tool, there are a few possible reasons:

1. The unallocated space is not located directly next to the partition you want to extend.
2. The partition's file system is not supported on Windows.
3. The extend volume option will be grayed out if your drive has no unallocated space.

 Now that you know all the possible culprits behind the issue, let's check out all the solutions that can help fix it.

## 1\. Convert the Partition to an NTFS File System

 Windows only supports certain [file systems](https://www.makeuseof.com/tag/from-fat-to-ntfs-to-zfs-file-systems-demystified-makeuseof-explains/) for partitions. If the partition you want to extend is formatted in a file system incompatible with Windows, you will not be able to extend it.

 To extend the partition, you must format the partition and convert it into an NTFS file system. However, formatting the partition will delete all the data, so make sure to [back up the data on the partition](https://www.makeuseof.com/ways-to-back-up-data/) first.

 To convert the partition to an NTFS file system, follow these steps:

1. Right-click on the partition and select **Format**.
2. Choose **NTFS** from the File system drop-down menu. Then, click **OK**.  
![File system option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/file-system-option.jpg)

 The formatting process may take some time, depending on the amount of data on the partition. Once done, restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 2\. Delete a Partition and Create Unallocated Space

 The "extend volume" option will gray out if there is no unallocated space next to the partition you want to extend. To create unallocated space, you will have to delete a partition that is next to the partition you want to extend.

 If the partition is a normal volume, you can simply right-click on it and select **Delete Volume**. However, if the partition contains data, make sure to back it up before deleting it.

![Delete Volume option in Disk Management tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-volume-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 If the partition is a recovery partition, you cannot delete it using Disk Management. You'll have to delete it using the Command Prompt. Here are the steps to do it:

1. Press the **Win** key to open the Start Menu, type **Command** **Prompt**, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other [ways to launch Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/).
2. Type **DiskPart** and press **Enter**.
3. Type **list disk** and press **Enter**. This command will display all the available disks.  
![list disk command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-disk-command-2.jpg)
4. Select the disk that you want to extend. For example, if you want to extend disk 0, type **select disk 0** and press **Enter**.
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
5. Type **list partition** and press **Enter**. This will list all the partitions on the disk.  
![list partition command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/list-partition.jpg)
6. In the Type column, look for the partition that says **Recovery**. Note the partition number. For example, if the partition number is 4, type **select partition 4** and press **Enter**. This will select the recovery partition.
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. To delete the recovery partition, type **delete partition override** and press **Enter**.  
![delete partition override command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-partition-override.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 You will see the message **DiskPart successfully deleted the selected partition**. This indicates that the recovery partition has been deleted.

![DiskPart successfully deleted the selected partition message in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/diskpart-successfully-deleted-the-selected-partition.jpg)

 Next, open the Disk Management tool, and you will see an unallocated space next to the partition you want to extend. Right-click on the partition, choose **Extend** **Volume**, and then click **Next**.

![Extend partition option in Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/extend-partition-option.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the wizard completes, you will see the partition size has been increased.

## Extend Your Windows Partitions Without Any Further Issues

 If you run out of space on a drive, you can use the unallocated space to increase storage. However, you will not be able to do so if the extend volume option is grayed out in the Disk Management tool. Fortunately, you can quickly troubleshoot this issue using the solutions above.

 If this is happening to you, try the below solutions for a grayed-out "extend volume" option on Windows

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-using-snapchat-in-biz/"><u>[New] 2024 Approved  The Ultimate Guide to Using Snapchat in Biz</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-professional-techniques-for-video-narrative-inclusion-for-2024/"><u>[New] Professional Techniques for Video Narrative Inclusion for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/airborne-cameras-clash-dji-inspire-vs-gopro-max-for-2024/"><u>Airborne Cameras Clash  DJI Inspire vs GoPro MAX for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-poco-m6-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Poco M6 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/click-your-way-to-fun-top-12-pc-titles-of-2021-for-2024/"><u>Click Your Way to Fun  Top 12 PC Titles of 2021 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-microsoft-copilot-in-development/"><u>Essential Guide to Using Microsoft Copilot in Development</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-troubleshooting-missing-steam-controllers/"><u>Essential Tips: Troubleshooting Missing Steam Controllers</u></a></li>
<li><a href="https://buynow-help.techidaily.com/exploring-the-dichotomy-of-cyberpunk-2077-magnificent-but-incomplete/"><u>Exploring the Dichotomy of Cyberpunk 2077: Magnificent but Incomplete</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-slow-internet-matching-mobile-and-desktop-speeds/"><u>Fix Your Slow Internet: Matching Mobile and Desktop Speeds</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-your-unresponsive-xbox-controllers-on-pc/"><u>Fixing Your Unresponsive Xbox Controllers on PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-itel-p55plus-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Itel P55+ Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unlock-pin-related-bluetooth-disconnects-in-win11win10/"><u>How To Unlock PIN-Related Bluetooth Disconnects in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-your-device-top-6-windows-pc-model-names/"><u>Identifying Your Device: Top 6 Windows PC Model Names</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-basics-of-visual-storytelling/"><u>In 2024, Basics of Visual Storytelling</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-motorola-moto-g84-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Motorola Moto G84 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-meaning-of-windows-mbr-error-messages/"><u>Mastering the Meaning of Windows MBR Error Messages</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/maxitouch-all-in-one-4k-screen-plus-desk/"><u>MaxiTouch All-in-One 4K, Screen Plus Desk</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-easily-getting-outlook-preview-on-winoss/"><u>Navigate Easily: Getting Outlook Preview on WinOSs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-text-pasting-in-powertoys-quickly/"><u>Navigating Text Pasting in PowerToys Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-code-0x0000004e-anomalies/"><u>Navigating Through Code 0X0000004E Anomalies</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pioneers-in-the-digital-realm-vr-past-and-future/"><u>Pioneers in the Digital Realm  VR Past and Future</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-lost-boot-prompts-uefi-fixes/"><u>Reclaim Lost Boot Prompts: UEFI Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-forgotten-power-schemes-on-ws-11/"><u>Resetting Forgotten Power Schemes on WS 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-launch-problems-in-stardew-valley-for-a-seamless-gaming-experience/"><u>Resolving Launch Problems in Stardew Valley for a Seamless Gaming Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-lockout-due-to-failed-sign-in-attempts/"><u>Resolving Windows Lockout Due to Failed Sign-In Attempts</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-robustness-of-win11s-cleanup-companion-ccleaner/"><u>Revamping Robustness of Win11's Cleanup Companion, CCleaner</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-hypervisorbsod-in-windows-a-top-ten-approach/"><u>Stop HYPERVISOR_BSOD in Windows: A Top-Ten Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-tasks-top-9-reasons-to-adopt-modernized-outlook/"><u>Streamline Your Tasks: Top 9 Reasons to Adopt Modernized Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-nvidia-connection-failures-in-10-and-11-editions/"><u>Streamlining Nvidia Connection Failures in 10 & 11 Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/the-7-best-photo-organizer-apps-for-windows/"><u>The 7 Best Photo Organizer Apps For Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-fix-guide-stabilizing-ps4-input-link-on-pc/"><u>The Ultimate Fix Guide: Stabilizing PS4 Input Link on PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/twitch-broadcast-excellence-the-ultimate-5-guide-for-2024/"><u>Twitch Broadcast Excellence  The Ultimate 5 Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-potential-understanding-function-fn-key-operations/"><u>Unleash Potential: Understanding Function (Fn) Key Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-how-to-fix-older-user-credential-message/"><u>Unlocking: How to Fix Older User Credential Message</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-directdraw-complexities-in-the-latest-microsoft-oses/"><u>Unraveling DirectDraw Complexities in the Latest Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/win-specific-error-recovery-reinstating-non-functional-software/"><u>Win-Specific Error Recovery: Reinstating Non-Functional Software</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>