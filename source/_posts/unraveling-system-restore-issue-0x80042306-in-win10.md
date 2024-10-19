---
title: Unraveling System Restore Issue 0X80042306 in Win10
date: 2024-10-15T00:49:46.934Z
updated: 2024-10-19T03:15:57.670Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling System Restore Issue 0X80042306 in Win10
excerpt: This Article Describes Unraveling System Restore Issue 0X80042306 in Win10
keywords: Win10 Restore Error,0X80042306 Fix,System Recovery Issue,Win10 Backup Failure,OS Restoration Problems,Bootloader Troubleshoot,Data Recovery in Windows
thumbnail: https://thmb.techidaily.com/e576fa6a569d314a929d202ace0124c24bb9f5c7c863ef858ebb7371b469a682.jpg
---

## Unraveling System Restore Issue 0X80042306 in Win10

 The error code 0x80042306 occurs when attempting to create a restore point in Windows. It prevents the creation of new restore points in the system and typically occurs when your system does not have sufficient free space, there is a problem with the Volume Shadow Copy service (VSS), or a background process is conflicting with the restore utility.

 Below, we talk about the different troubleshooting methods you can try to fix the system restore error 0x80042306 in Windows. We recommend booting into the administrator account before you proceed.

## 1\. Make Sure You Have Sufficient Space

 Restore points require free space on the disk they are stored. This amount of space required by a restore point typically depends on on the size and complexity of your system configuration.

 If you do not have sufficient space on the disk, the restore utility is likely to return a 0x80042306 error. This is why, we recommend getting started by making sure that enough free space for the System Restore to function correctly. You can delete unnecessary items to increase the space manually, or[use the Disk Cleanup](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/) utility that is offered by Microsoft by default.

 Alternatively, you can also increase the amount of disk space allocated for System Restore in the System Protection settings. Here is how you can do that:

1. Type "Create a restore point" in the Windows search utility and click**Open** .
2. In the following dialog, head over to the**System Protection** tab.
3. Click on the**Configure** button and use the Max usage to slider to adjust the disk percentage according to your preference.  
![Adjust the Max usage slider](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restore-point-usage.jpg)
4. Click**Apply** \>**OK** to save the changes.

 Once the changes are made, check if you can now create a restore point without any issues.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart the Volume Shadow Copy Service

 You might also be facing the problem if the Volume Shadow Copy service is disabled or simply not functioning properly.

 This service allows the creation of backup copies for files and volumes in Windows. It is used to by the restore utility to create snapshots of the items that are being backed up and if it fails to work due to any reason, you might encounter the problem at hand.

 To ensure this service is working properly, you can restart it using the Services utility. Follow the steps below to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "services.msc" in Run and click**Enter** .
3. In the services window, scroll down to locate the**Volume Shadow Copy** service and right-click on it.  
![Volume Shadow Copy service in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/volume-shadow-copy.jpg)
4. Choose**Properties** from the context menu.
5. Now, click on the**Stop** button, wait for a few seconds, and hit**Start** again.
6. Make sure the Startup type is set to**Automatic** .  
![Start the VSS service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-vss-service.jpg)
7. Finally, click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Do the same for the Windows Backup service and check if the issue is resolved.

## 3\. Re-Register VSS Components

 If restarting the Volume Shadow Copy service did not work, then you can also try re-registering the VSS components via Command Prompt.

Here is how to proceed:

1. Press the**Win** +**R** keys together to open Run.
2. Type "cmd" in Run and press the**Ctrl** +**Shift** +**Enter** keys together to open Command Prompt as an administrator.
3. Click**Yes** in the User Account Control prompt.
4. Now, execute the following commands one by one:  
`cd /d %windir%\system32net stop vssnet stop swprvregsvr32 /s ole32.dllregsvr32 /s oleaut32.dllregsvr32 /s vss_ps.dllvssvc /registerregsvr32 /s /i  

swprv.dllregsvr32 /s /i eventcls.dllregsvr32 /s es.dllregsvr32 /s stdprov.dllregsvr32 /s vssui.dllregsvr32 /s msxml.dllregsvr32 /s  

msxml3.dllregsvr32 /s msxml4.dllvssvc /registernet start swprvnet start vss`
5. Once you have re-registered VSS components, close Command Prompt and try creating a restore point again.

 If an issue within the VSS components was causing the problem, restarting the components should fix it.

## 4\. Create a Restore Point in Safe Mode

 In some cases, a conflicting background process can also prevent the System Restore utility from creating a restore point successfully. The best way to ensure there are no applications or programs in the background interrupting the functionality of System Restore, try creating a restore point in Safe Mode.

 This mode launches Windows with a minimal set of drivers and services, which can help isolate the issue and prevent any conflicts that may be occurring in normal mode.

Here is how you can boot in Safe Mode:

1. Type "System Configuration" in Windows search and click**Open** .
2. Head over to the**Boot** tab and under Boot Options, checkmark the Safe Boot option.
3. Choose**Minimal** and click on**Apply** \>**OK** to save the changes.  
![Minimal mode of Safe Boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-boot-safe-mode-minimal.jpg)

 You can now restart your computer and upon reboot, you should enter the Safe Mode automatically. Try recreating a restore point and check if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Scan the System For Corruption Errors

![Running Sfc scan in CMD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/running-sfc-scan.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The System Restore utility itself might be dealing with a corruption error, which is preventing it from functioning properly.

 To fix any corrupt system files, we suggest using the System File Checker (SFC) and Deployment Image Servicing and Management (DISM) tools. SFC works by scanning the protected system files for underlying problems. If an issue is discovered, it will replace the faulty file with its healthier cached counterpart.

 DISM, on the other hand, works by repairing corrupt system images. We have a guide on[how to use SFC and DISM in Windows](https://www.makeuseof.com/windows-built-in-repair-tools/) which you can refer to, to perform the steps correctly.

## System Restore Back On Track

 The System Restore utility in Windows is a powerful tool that can save you from losing important data in case of unexpected system issues. That said, it can be annoying if you cannot create a restore point easily, especially when you are trying to do it before performing a critical action.

 By following the methods outlined in this guideline, you can diagnose the error and take necessary steps to resolve it. We recommend making sure all the relevant services stay enabled, and your system is up-to-date to avoid any such issues in the future.

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
<li><a href="https://youtube-blog.techidaily.com/ed-elite-streaming-sensations-worlds-most-popular-video-content-makers-for-2024/"><u>[Updated] Elite Streaming Sensations World's Most Popular Video Content Makers for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-innovate-meme-designs-in-adobe-tools/"><u>[Updated] Innovate Meme Designs in Adobe Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-journey-in-sky-high-4k-clarity/"><u>2024 Approved The Ultimate Journey in Sky High 4K Clarity</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-samsung-galaxy-f14-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-motorola-moto-g34-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Motorola Moto G34 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/examining-the-combination-of-robustness-and-affordability-in-fintie-cases-for-macbook-pro-13/"><u>Examining the Combination of Robustness & Affordability in Fintie Cases for MacBook Pro 13</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-system-performance-by-curbing-browser-activity/"><u>Improving System Performance by Curbing Browser Activity</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-stutters-on-motorola-edgeplus-2023-and-stops-randomly-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV stutters on Motorola Edge+ (2023) and stops randomly</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-update-breakdown-overcoming-error-0x80246007-on-win11/"><u>Resolving Update Breakdown: Overcoming Error 0X80246007 on Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-how-to-grab-a-screenshot-using-windows-or-mac/"><u>Step-by-Step Tutorial: How to Grab a Screenshot Using Windows or Mac</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/swagtron-swagboard-t1-a-step-up-for-fitness-enthusiasts-despite-its-premium-price-point/"><u>Swagtron Swagboard T1 - A Step Up for Fitness Enthusiasts, Despite Its Premium Price Point</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-a-fortified-pc-with-windows-11-and-tpmsecure-boot/"><u>The Path to a Fortified PC with Windows 11 & TPM/Secure Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-type-tips-quick-key-input-enhancements-for-win-1011/"><u>Turbo-Type Tips: Quick Key Input Enhancements for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-5ghz-wi-fi-connection-woes-how-to-solve-them/"><u>Win11 5GHz Wi-Fi Connection Woes: How to Solve Them</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-widgets-configuration-the-triad-approach/"><u>Windows 11 Widgets Configuration: The Triad Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
</ul></div>

