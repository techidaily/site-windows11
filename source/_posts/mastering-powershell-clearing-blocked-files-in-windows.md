---
title: "Mastering PowerShell: Clearing Blocked Files in Windows"
date: 2025-01-16T16:09:02.337Z
updated: 2025-01-22T18:41:23.863Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering PowerShell: Clearing Blocked Files in Windows"
excerpt: "This Article Describes Mastering PowerShell: Clearing Blocked Files in Windows"
keywords: PowerShell File Cleanup,Unblock Windows Files,Windows Script Optimization,Remove Restrictions in PS,Mastering System Admin Tools,Clear Obstructed Files PSC,Enhancing Windows File Access
thumbnail: https://thmb.techidaily.com/3bbe537e8e6d43ee38a009c5ba9253564dbe37ab479840f5e7760ebe6f9d088b.jpg
---

## Mastering PowerShell: Clearing Blocked Files in Windows

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-innovative-approaches-to-keeping-your-snaps-connected/"><u>2024 Approved Innovative Approaches to Keeping Your Snaps Connected</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-youtube-money-mastery-from-clicks-to-checkbook-balance/"><u>2024 Approved YouTube Money Mastery From Clicks to Checkbook Balance</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-nonworking-diagnostics-for-win10win11/"><u>Improving Nonworking Diagnostics for Win10/Win11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-flipping-currencies-through-cosmetics-content/"><u>In 2024, Flipping Currencies Through Cosmetics Content</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-ace-2v-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Ace 2V to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-store-fix-guide-for-error-0x80131500/"><u>Microsoft Store Fix Guide for Error 0X80131500</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-and-picker-engaging-checkbox-for-files-in-win11/"><u>Navigate and Picker: Engaging Checkbox for Files in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-wsl-issues-post-windows-11-upgrade/"><u>Resolving WSL Issues Post-Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-restoring-data-flow-from-faulty-usb-on-windows/"><u>Steps for Restoring Data Flow From Faulty USB On Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-5-highly-reliable-encrypted-email-providers/"><u>Top 5 Highly Reliable Encrypted Email Providers</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-code-windows-10s-0x0000004e/"><u>Troubleshooting Error Code: Windows 10'S 0X0000004E</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-tips-to-exit-sea-of-thieves-endless-launch-sequence/"><u>Troubleshooting Tips to Exit Sea of Thieves Endless Launch Sequence</u></a></li>
</ul></div>

