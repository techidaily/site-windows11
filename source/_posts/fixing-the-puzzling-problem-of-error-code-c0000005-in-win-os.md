---
title: Fixing the Puzzling Problem of Error Code C0000005 in Win-OS
date: 2024-09-23T19:57:38.554Z
updated: 2024-09-26T16:58:24.015Z
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now check if the app and your operating system are compatible with each other.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-stream.techidaily.com/new-regular-payment-structures-in-youtuber-economics/"><u>[New] Regular Payment Structures in YouTuber Economics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-become-an-instagram-star-expert-5-strategies-and-illustrative-examples/"><u>[Updated] Become an Instagram Star Expert 5 Strategies and Illustrative Examples</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-discover-the-10-leading-free-video-call-apps-iosandroid-for-2024/"><u>[Updated] Discover The 10 Leading Free Video Call Apps (iOS/Android) for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guiding-you-to-untainted-stock-visuals/"><u>2024 Approved Guiding You to Untainted Stock Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inoperative-drive-not-detected-by-os/"><u>Fixing Inoperative Drive Not Detected by OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-fixing-nvidia-gui-sharing-glitches/"><u>Guide for Fixing NVIDIA GUI Sharing Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-destructive-js-error-in-discord-on-win-11-pcs/"><u>How to Mend the Destructive JS Error in Discord on Win 11 PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Oppo A78 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-quick-file-scan-in-windows/"><u>In 2024, Navigating Quick File Scan in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-setup-obstacles-on-windows-11-devices/"><u>Overcoming Steam Setup Obstacles on Windows 11 Devices</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-connectivity-download-compatible-drivers-for-asus-bt500-bluetooth-50-adapter-on-windows-versions-11-10-and-8/"><u>Seamless Connectivity: Download Compatible Drivers for Asus BT500 Bluetooth 5.0 Adapter on Windows (Versions 11, 10 & 8)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Tecno Pop 7 Pro | Dr.fone</u></a></li>
</ul></div>

