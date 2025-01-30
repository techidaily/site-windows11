---
title: The Essential Guide to Clearing Restrictions via PowerShell
date: 2025-01-24T06:48:05.133Z
updated: 2025-01-29T21:52:44.122Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to Clearing Restrictions via PowerShell
excerpt: This Article Describes The Essential Guide to Clearing Restrictions via PowerShell
keywords: PS Restriction Removal,PowerShell Command Guide,Admin Script for Restrictions,Bypassing Access Controls,Secure PowerShell Commands,Clear Permissions PS,Advanced User Rights
thumbnail: https://thmb.techidaily.com/029b0eb85077c27446243e8d1c815878a76764b760390b18a7b33382115f2d0b.jpg
---

## The Essential Guide to Clearing Restrictions via PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://article-knowledge.techidaily.com/new-mastering-unboxing-expert-tips-and-tricks-for-2024/"><u>[New] Mastering Unboxing Expert Tips and Tricks for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/4k-lg-display-assessment-the-ultimate-31mu97-b/"><u>4K LG Display Assessment The Ultimate 31MU97-B</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/boost-internet-speed-on-mac-the-ultimate-guide-to-flushing-dns-cache/"><u>Boost Internet Speed on Mac: The Ultimate Guide to Flushing DNS Cache</u></a></li>
<li><a href="https://solve-luxury.techidaily.com/easy-methods-for-saving-instagram-footage-to-your-device-windows-mac-iphone-or-android/"><u>Easy Methods for Saving Instagram Footage to Your Device - Windows, Mac, iPhone, or Android</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/expert-iphone-photography-using-hdr-for-2024/"><u>Expert iPhone Photography Using HDR for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-errors-in-windows-discord-query-system/"><u>Fixing Errors in Windows' Discord Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-automatically-shut-down-a-windows-11-and-11-pc-when-its-idle/"><u>How to Automatically Shut Down a Windows 11 and 11 PC When It's Idle</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-htc-u23-pro-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from HTC U23 Pro to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-balancing-act-lowering-audio-levels/"><u>In 2024, Balancing Act Lowering Audio Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-ways-to-generate-numerous-folders-on-modern-windows-pcs/"><u>Innovative Ways to Generate Numerous Folders on Modern Windows PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975347403-lenovo-ideapad-100-find-and-install-the-latest-drivers-for-windows-10-systems-easily/"><u>Lenovo IdeaPad 100 - Find and Install the Latest Drivers for Windows 10 Systems Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-inability-to-add-columns-in-ms-excel-windows/"><u>Troubleshooting: Inability to Add Columns in MS Excel (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-fix-for-error-afc-windows-11-camera-app-crash/"><u>Unveiling Fix for Error AFC: Windows 11 Camera App Crash</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/your-guide-to-building-stylish-snapchat-filters-for-2024/"><u>Your Guide to Building Stylish Snapchat Filters for 2024</u></a></li>
</ul></div>

