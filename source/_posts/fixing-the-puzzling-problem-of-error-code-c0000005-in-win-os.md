---
title: Fixing the Puzzling Problem of Error Code C0000005 in Win-OS
date: 2024-09-11T16:57:29.272Z
updated: 2024-09-15T19:03:03.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing the Puzzling Problem of Error Code C0000005 in Win-OS
excerpt: This Article Describes Fixing the Puzzling Problem of Error Code C0000005 in Win-OS
keywords: WinErrorCodeC0000005,OSErrorSolution,WindowsC0000005,FixWinErrorCode,C0000005ErrorFix,WinOSC0000005,ErrorC0000005WinOS
thumbnail: https://thmb.techidaily.com/f3ddbfc1319d06192a1f603baf76c1f6dea1578ed46bf0e0e3227f2988d719a1.jpg
---

## Fixing the Puzzling Problem of Error Code C0000005 in Win-OS

 The Windows error code 0xc0000005 is a particularly debilitating error that can break your workflow unless properly fixed. Although the precise cause of this error can vary wildly, it's generally caused by a problem in your memory or a general failure to process the app's settings by your operating system. There are many methods you can try to rescue your PC from this bug.

 We have rounded up a variety of methods you can try your luck with. Let's look at how you can fix the error Code 0xc0000005 on Windows for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Deactivate Data Execution Prevention (DEP)

[Data Execution Prevention](https://www.makeuseof.com/data-execution-prevention-explained/) is a security feature on Windows that prevents damage to your PC from malware and other malicious attacks on your PC. It does this by blocking out specific memory regions so that code cannot be executed from those locations, which in the absence of DEP, would be used for buffer attacks.

 However, the only problem is that it can sometimes prevent the smooth functioning of some programs as well. While we don't recommend this as a solution for the long-term, see if you can get rid of the Error Code 0xc0000005 on your Windows by turning off the DEP for a while.

Here's how you can get started:

* Head to the**Start menu** search bar, type in 'cmd,' and run the command prompt as an administrator.
* Type in the following command in the cmd and hit**Enter** :  
bcdedit.exe /set {current} nx AlwaysOff

 Note that if you have UEFI secure boot enabled, then you might encounter an error like this:

![cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cmd.jpg)

 In this case, you will first have to[disable the Windows secure boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) , and then repeat the above steps again.

 That's it—the DEP will be disabled from here on. Now, give your PC a quick reboot and see if the error 0xc0000005 persists.

## 2\. Check Your App's and PC Version and Compatibility

 One of the more common reasons for getting hit with the 0xc0000005 error is when your computer cannot process the files or settings necessary to your PC. While the causes of this can vary, a common one is that you've been using an outdated version of the app.

 In fact, if you're using the app for the first time, the tool might be completely incompatible with your operating system.

Here's how you can check your PC's version:

* Press the**Win + I** shortcut to launch Settings.
* Click on**About** .

 As soon as you do this, the Windows**Device specification** will be launched.

Similarly, to check the app's version, follow the steps below:

* Head to the**Settings** menu, and select**Apps > Installed Apps** .
* To check the app's version, click on any specific app.
* If it's a Microsoft app, click on the Settings option (three dots) next to it and select**Advanced options** .

![installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/installed-apps.jpg)

 Now check if the app and your operating system are compatible with each other.

## 3\. Apply Some Generic Fixes for Fixing Errors on Windows

 While the methods we have discussed have targeted the error code 0xc0000005 in particular, there are some quick fixes that come recommended for pretty much all Windows errors. Note that it's not the case that these solutions are bound to fix any particular error you are facing at a point in time, but if you have tried all the different methods from above, then the below methods are definitely worth a go.

Let's go over all of them one by one.

1. [Run an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) : An SFC scan looks for and fixes any files that have, for a variety of reasons, become damaged on your PC.
2. [Use the Memory Diagnostic Tool](https://www.makeuseof.com/windows-memory-diagnostic-tool-guide/) : You can encounter the 0xc0000005 error on your PC if your PC has memory problems. Fortunately, the Memory Diagnostic tool is a built-in way to fix any issues with your memory.
3. [Run the Program Compatibility Troubleshooter](https://www.makeuseof.com/program-compatibility-troubleshooter-windows-11-guide/) : It's possible to face errors when running an app if it's incompatible with your PC, especially if it's older. Fortunately, the Program Compatibility Troubleshooter can help it run properly.
4. [Repair your app:](https://www.makeuseof.com/windows-repair-apps-programs/) It's possible that the app's files you're trying to run have become damaged and, as a result, your PC throws the 0xc0000005 error code. A quick app repair is a good possible solution in this scenario.
5. [Run a malware scan:](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) A malware scan can break or create malfunctions for otherwise normal processes on your PC; run and see if that's the case in this error as well.
6. [Perform a Factory Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) : A Factory reset is, as I sometimes like to call it, the "all pulverizer" all Windows problems. It removes your operating system and reinstalls it so you can start again with a clean slate. It's a drastic measure, but sometimes it's the only way to get a Windows error fixed.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing the Error Code 0xc0000005 on a Windows PC

 Like most abrupt Windows errors, the 0xc0000005 error code can cause a sharp break in your workflow. Hopefully, using one of the methods from above, you managed to get rid of the Windows error for good.

 However, it's a fact that Windows gets plagued by many such simple errors from time to time, that more often than not, can be fixed with little to no effort. So, make sure you keep tabs on all such errors, along with their solutions.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-viewsense-capture-report-summary/"><u>[New] ViewSense Capture Report Summary</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-obs-essentials-optimizing-your-skype-call-recording-quality/"><u>[Updated] In 2024, OBS Essentials Optimizing Your Skype Call Recording Quality</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-oppo-reno-11-5g-easily-by-drfone-android/"><u>How To Unlock a Oppo Reno 11 5G Easily?</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-songsyncing-simplified-your-guide-to-turning-tamil-music-into-alerts/"><u>In 2024, SongSyncing Simplified Your Guide to Turning Tamil Music Into Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/master-organization-to-do-and-ifttt-alliance/"><u>Master Organization: To-Do & IFTTT Alliance</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-final-cut-pro-sound-design-how-to-source-free-sound-effects-online/"><u>New 2024 Approved Final Cut Pro Sound Design How to Source Free Sound Effects Online</u></a></li>
<li><a href="https://screen-recording.techidaily.com/nocturnal-notes-expert-advice-on-low-light-photos/"><u>Nocturnal Notes Expert Advice on Low Light Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-of-getting-adobe-reader-on-ms-store/"><u>Simplifying the Process of Getting Adobe Reader on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-process-for-distro-and-catroot2-fixes-in-ws11/"><u>The Ultimate Process for Distro & Catroot2 Fixes in WS11</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-black-desktop-backgrounds-on-pcs/"><u>Transforming Black Desktop Backgrounds on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-proxies-a-practical-guide-to-enhanced-privacy/"><u>Win 11 Proxies: A Practical Guide to Enhanced Privacy</u></a></li>
</ul></div>
