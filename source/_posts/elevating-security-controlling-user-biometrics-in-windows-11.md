---
title: "Elevating Security: Controlling User Biometrics in Windows 11"
date: 2024-07-29T04:23:24.543Z
updated: 2024-07-30T04:23:24.543Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Elevating Security: Controlling User Biometrics in Windows 11"
excerpt: "This Article Describes Elevating Security: Controlling User Biometrics in Windows 11"
keywords: Biometric Security Windows 11,User Identity Management W11,Enhance Windows Biometrics,Safe Access Control W11,Unified Authentication Win11,Advanced Windows Safety,Protective Biometric Windows
thumbnail: https://thmb.techidaily.com/6060180ff020afbbd02ae1895cf9d82d0058a11f9344fe92d8db0b4a31855d9f.JPG
---

## Elevating Security: Controlling User Biometrics in Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-examining-the-income-stream-for-t-series-youtube-channel/"><u>[New] 2024 Approved  Examining the Income Stream for T-Series YouTube Channel</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebook-tutorial-how-to-create-facebook-account/"><u>[New] Facebook Tutorial  How to Create Facebook Account</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-complete-user-manual-how-to-use-screen-recording-on-mac/"><u>[New] In 2024, The Complete User Manual  How To Use Screen Recording on Mac</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-essential-tips-for-youtube-thumbnail-size/"><u>[Updated] In 2024, Essential Tips for YouTube Thumbnail Size</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-quick-tips-for-uploading-content-on-twitter/"><u>[Updated] Quick Tips for Uploading Content on Twitter</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-comprehensive-guide-record-webcam-in-hd-via-vlc/"><u>2024 Approved  Comprehensive Guide  Record Webcam in HD via VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/ace-your-adventures-optimal-full-hd-play-with-scummvm-and-windows-pcs/"><u>Ace Your Adventures: Optimal Full HD Play with ScummVM and Windows PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/action-sequence-alerts-mastering-4-techniques-on-the-xbox-one-for-2024/"><u>Action Sequence Alerts  Mastering 4 Techniques on the Xbox One for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquer-common-issues-essential-windows-10-fixes-for-2024/"><u>Conquer Common Issues  Essential Windows 10 Fixes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-unresponsive-clicks-with-these-fixes/"><u>Conquer Unresponsive Clicks with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-ftdibussys-explaining-its-effect-on-memory-security/"><u>Deciphering ftdibus.sys: Explaining Its Effect on Memory Security</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-diagnostics-a-guide-to-windows-ping-usage/"><u>Enhancing System Diagnostics: A Guide to Windows Ping Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-peaceful-navigation-maintain-stability-in-windows-net/"><u>Ensure Peaceful Navigation: Maintain Stability in Windows Net</u></a></li>
<li><a href="https://windows11.techidaily.com/executing-policies-for-a-single-user-target-in-modern-windows-systems/"><u>Executing Policies for a Single-User Target in Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-safest-windows-free-software-hubs/"><u>Explore Safest Windows Free Software Hubs</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/fostering-self-assurance-against-virtual-hostility-for-2024/"><u>Fostering Self-Assurance Against Virtual Hostility for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-boredom-to-chuckles-generating-funny-memes-for-2024/"><u>From Boredom to Chuckles  Generating Funny Memes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-disabling-windows-surrounders/"><u>Guide to Disabling Windows Surrounders</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-resolving-missing-drivers-alert-on-windows-setup/"><u>Guidelines for Resolving Missing Drivers Alert on Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-multi-user-printer-errors-windows-11-guide/"><u>Handling Multi-User Printer Errors: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-efface-license-end-soon-warning-from-your-pc/"><u>How To Efface License End Soon Warning From Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-extend-the-pin-length-in-windows-11-and-11/"><u>How to Extend the PIN Length in Windows 11 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-oppo-f23-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Oppo F23 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-asus-rog-phone-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-local-security-authority-protection-is-off-security-warning-on-windows/"><u>How to Fix the “Local Security Authority Protection Is Off” Security Warning on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-up-troubleshooter-shortcuts-in-windows-11-and-11/"><u>How to Set Up Troubleshooter Shortcuts in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-snipping-tool-activation-from-pressing-prtscn-in-11/"><u>How to Stop Snipping Tool Activation From Pressing PrtScn in 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-itel-s23plus-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Itel S23+ Location by Number | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-oneplus-nord-n30-5g-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor OnePlus Nord N30 5G Activity | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-vivo-y100i-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Vivo Y100i online without jailbreak</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essence-of-video-editing-filmoras-ten-wonders/"><u>In 2024, The Essence of Video Editing  Filmora's Ten Wonders</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-windows-life-easier-with-proper-installation-steps/"><u>Make Your Windows Life Easier with Proper Installation Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-memory-management-in-new-os/"><u>Mastering Memory Management in New OS</u></a></li>
<li><a href="https://extra-skills.techidaily.com/moto-z2-masterclass-smartphone-smarts-explored-for-2024/"><u>Moto Z2 Masterclass  Smartphone Smarts Explored for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-application-failure-the-notorious-error-the-application-couldnt-start-xc000003e-on-win11-and-11/"><u>Navigating Application Failure: The Notorious Error The Application Couldn’t Start Xc000003e on Win11 & 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/nvidia-gpu-firmware-gtx-1060-upgrade/"><u>Nvidia GPU Firmware - GTX 1060 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-office-suites-strict-safe-mode-on-windows-operations/"><u>Troubleshooting Office Suite's Strict Safe Mode on Windows Operations</u></a></li>
<li><a href="https://youtube-data.techidaily.com/er-the-10-best-makeup-experts-on-youtube-you-cant-ignore/"><u>Uncover the 10 Best Makeup Experts on YouTube You Can't Ignore</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-console-dreams-choose-windows-for-games/"><u>Unlocking Your Console Dreams: Choose Windows for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-photo-wizardry-made-easy-mastering-slideshow-creation-and-spot-repair/"><u>Windows 11'S Photo Wizardry Made Easy: Mastering Slideshow Creation & Spot Repair</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>