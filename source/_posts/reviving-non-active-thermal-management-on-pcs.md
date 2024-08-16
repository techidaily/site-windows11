---
title: Reviving Non-Active Thermal Management on PCs
date: 2024-08-15T16:10:39.217Z
updated: 2024-08-16T16:10:39.217Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reviving Non-Active Thermal Management on PCs
excerpt: This Article Describes Reviving Non-Active Thermal Management on PCs
keywords: Active PC Temp Control,Revive Heat Tech,Thermal Update PC,Hotspot Restoration,PC Cooling Refresh,Non-Active Temp Fix,Rejuvenate PC Thermo
thumbnail: https://thmb.techidaily.com/3c560b5f84950935f235a17f57ab9b2b0c297df9b81f28e15578b876da96606b.jpg
---

## Reviving Non-Active Thermal Management on PCs

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on [what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on [how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically [created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00 [HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.


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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-initiate-social-media-exploration-with-a-new-twitter/"><u>[New] 2024 Approved  Initiate Social Media Exploration with a New Twitter</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-tackling-inaudible-portions-in-partially-muted-fb-media/"><u>[New] 2024 Approved  Tackling Inaudible Portions in Partially Muted FB Media</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-directscreen-a-streamlined-windows-recorder-for-2024/"><u>[New] DirectScreen  A Streamlined Windows Recorder for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-narratives-galore-top-20-storytelling-channels-of-the-year/"><u>[Updated] 2024 Approved  Narratives Galore  Top 20 Storytelling Channels of the Year</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-comprehensively-reviews-easeus-experts-unite-for-2024/"><u>[Updated] Comprehensively Reviews EaseUS, Experts Unite for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-for-srt-enhanced-mp4-files/"><u>[Updated] Expert Tips for SRT-Enhanced MP4 Files</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-step-by-step-io-screen-capture-tutorial/"><u>[Updated] In 2024, Step-by-Step IO Screen Capture Tutorial</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-inside-the-io-recording-process-what-you-must-know/"><u>[Updated] Inside the IO Recording Process  What You Must Know</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-salty-sessions-captured-best-cams-for-surfers/"><u>2024 Approved  Salty Sessions Captured - Best Cams for Surfers</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-script-mastery-online-academy/"><u>2024 Approved  Script Mastery Online Academy</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-guide-to-running-ping-efficiently-on-pcs/"><u>A Practical Guide to Running Ping Efficiently on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-activating-linux-support-in-windows/"><u>Bridging the Gap: Activating Linux Support in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-the-forgotten-floppy-drive-sdds-in-winos/"><u>Bring Forth the Forgotten Floppy Drive, SDDs in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-video-drivers-in-win1110/"><u>Correcting Failed Video Drivers in Win11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-top-9-steps-for-efficient-volume-management-in-windows-11/"><u>Discover Top 9 Steps for Efficient Volume Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-kali-installation-guide-for-windows-users/"><u>Effortless Kali Installation Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-root-of-windows-update-problems-0xc1900101/"><u>Eliminating the Root of Windows Update Problems (0xC1900101)</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-windows-11-arm-with-easy-iso-setup-instructions/"><u>Fast Track to Windows 11 ARM with Easy ISO Setup Instructions</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-iphone-6-by-drfone-ios/"><u>How to Bypass iCloud Lock on iPhone 6</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-reset-count-after-login-failures-a-windows-11-technique/"><u>How to Change Reset Count After Login Failures: A Windows 11 Technique</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-cursor-on-windows/"><u>How to Change Your Cursor on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-out-of-dfu-mode-on-iphone-11-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of DFU Mode on iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-phone-dialer-in-windows-11/"><u>How to Open the Phone Dialer in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x-fold-2-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Vivo X Fold 2 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-infinix-smart-7-hd-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Infinix Smart 7 HD FRP</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-designing-your-perfect-tiktok-end-screen/"><u>In 2024, Designing Your Perfect TikTok End Screen</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-se-2022-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From Apple iPhone SE (2022) If Youve Tried Everything</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-y100i-power-5g-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo Y100i Power 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-hdr-on-windows-11/"><u>Maximizing Visual Quality with HDR on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-non-downloading-on-windows-devices/"><u>Navigating the Maze of Non-Downloading on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-to-locate-windows-10-or-11-keys-efficiently/"><u>Pro Tips to Locate Windows 10 or 11 Keys Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-restoring-windows-defender-threat-shield-functionality/"><u>Quick Fixes: Restoring Windows Defender Threat Shield Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-disappearing-5ghz-network-on-windows-11/"><u>Reintroduce Disappearing 5GHz Network on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-error-disabled-device-code-22-in-windows-11/"><u>Remedying the Error: Disabled Device, Code 22 in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reshaping-administration-workflow-in-the-windows-ecosystem/"><u>Reshaping Administration Workflow in the Windows Ecosystem</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-webcam-dark-screen-issue/"><u>Resolving Windows Webcam Dark Screen Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/reverse-c-drive-data-hoarding-in-windows-systems/"><u>Reverse C: Drive Data Hoarding in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-allot-browser-permission-via-firewall-on-pc/"><u>Steps to Allot Browser Permission via Firewall on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-issues-0xca00a009/"><u>Streamlining Windows Update Issues: 0XCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-net-requirement-issue-in-windows-apps/"><u>Tackling the .NET Requirement Issue in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-troubled-windows-registry-with-effective-solutions/"><u>Tackling Troubled Windows Registry with Effective Solutions</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-animator-marketplace-of-custom-creative-stunts-for-2024/"><u>The Animator' Marketplace of Custom Creative Stunts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-language-of-windows-update-identifiers/"><u>The Hidden Language of Windows Update Identifiers</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-pioneers-guide-to-gopro-and-timelapse-magic/"><u>The Pioneer's Guide to GoPro and Timelapse Magic</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-mute-game-proposals-in-windows-11/"><u>Tips to Mute Game Proposals in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-pc-gaming-with-high-speed-yuzu/"><u>Turbocharge PC Gaming with High-Speed Yuzu</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-honor-90-gt-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Honor 90 GT Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>
