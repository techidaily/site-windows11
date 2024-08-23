---
title: "Secure Your System: Top 5 Ways to Reactivate Defender Threat Detection"
date: 2024-08-22T21:36:40.894Z
updated: 2024-08-23T21:36:40.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Your System: Top 5 Ways to Reactivate Defender Threat Detection"
excerpt: "This Article Describes Secure Your System: Top 5 Ways to Reactivate Defender Threat Detection"
keywords: SecureDefender Revival,ThreatDetection Reactivation,Defender Security Recovery,System Safeguard Methods,Enhance Defender Protection,Improve Threat Alert,Restore Defender Efficiency
thumbnail: https://thmb.techidaily.com/ef69c6cfc05813b51fd415fbeca882846dc473b99199e876bd020898984fe0d1.png
---

## Secure Your System: Top 5 Ways to Reactivate Defender Threat Detection

 Windows Defender is a crucial built-in antivirus software that helps protect your computer from various types of malware and security threats. However, users might encounter a common issue where the Virus & threat protection feature in Windows Defender displays an error message saying "Engine Unavailable" which prevents it from scanning for viruses and leaving your system vulnerable.

 In this article, we will explore the solutions that can help fix this issue and restore the full functionality of this important security feature.

## Why Is the Engine Unavailable in Windows Defender?

 The Virus & Threat Protection engine typically becomes unavailable after a Windows Defender update fails to install in the system. This can happen due to a number of reasons, and we have listed the most common ones below:

* **The r** **elevant services are disabled** \- the essential services required to install the Windows Defender updates might be disabled, preventing the system from updating it.
* **Windows Security's files are corrupt** \- there can be an issue with the Windows Security utility itself. A temporary bug or a corruption error might have infected it, causing it to act up.
* **Conflicting software** \- software offering similar functionalities could be conflicting with Windows Defender and its relevant procedures.
* **Corrupted Windows files or malware** \- the critical system files might be corrupt, which is affecting the update functionality of Windows. Your system might also be infected with malware.

 Regardless of what might be leading to the problem, the solutions we have listed below are sure to help you get the Virus & Threat Protection engine up and running for good. We suggest that before you proceed, restart your computer and retry installing the update. In some cases, a temporary system glitch can lead to the problem and a simple reboot can clear it.

## 1\. Restart the Security Center Service

 The Security Center service in Windows is responsible for managing security-related services, including Windows Defender. If the service is not functioning properly, it can prevent you from updating the Defender or using it at all

 Fortunately, service issues are easy to resolve. Most of the time, restarting the service can get it running properly again.

Here is how you can restart the Security Center Service:

1. Press the**Win + R** keys together to open Run.
2. Type "services.ms" in Run and press**Enter** .
3. In the following dialog, scroll down to locate the Security Center service and right-click on it.
4. Choose**Properties** from the context menu.  
![Launch the properties of Security Center service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/security-center-properties.jpg)
5. Now, click on the**Stop** button, wait for a few seconds, and click**Start** .
6. Expand the dropdown for Startup type and choose**Automatic** .
7. Click**Apply** \>**OK** to save the changes and then close the Services utility.

 You can now retry installing the Defender update and check if restarting the service fixed the issue.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 2\. Edit the Relevant Registry Keys

 You can also enable the Windows Defender services using the Registry Editor. In this method, we will disable the DisableAntiSpyware and DisableAntiVirus values. Then, we will delete any corrupt Registry entries that malware may have introduced in the system.

 However, before we proceed, we recommend[creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Once that is done, proceed with the steps below:

1. Press the**Win + R** keys together to open Run.
2. Type "regedit" in the text field of Run and press**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`HKEY_LOCAL_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender`
5. Move to the right pane and locate the**DisableAntiSpyware** value.

1. Double-click on it and under Value data, type**0** .  
![Change the value data to 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disableantispyware-key.jpg)
2. Do the same with the**DisableAntiVirus** value in the same window.
3. After this, navigate to the following location in the Registry Editor:  
`HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`
4. Here, right-click on the MSASCui.exe, MpCmdRun.exe, and MsMpEng.exe values one by one and choose**Delete** .  
![Delete the Registry entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/delete-the-key.jpg)
5. Finally, close the Registry Editor and restart your computer. Upon reboot check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Manually Install the Update

 If the system cannot install the Windows Defender update automatically, you can also manually install it.

 This can be done by heading over to the[Microsoft security updates](https://www.microsoft.com/en-us/wdsi/defenderupdates) page and finding the required update in the "manually download the update" section. You can then select the appropriate version based on your system and install it.

 You can also use the Powershell utility to install the update manually. We have discussed the[different methods of manually updating Windows Defender](https://www.makeuseof.com/microsoft-defender-manually-update/) , so be sure to check it out.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Reset Windows Security

 As we mentioned earlier, there can be an issue with Windows Security itself. This problem can be resolved by resetting the utility, which will clear all of its settings and configurations, restoring the default state.

Here is how you can reset the Windows Security app:

1. Press the**Win + S** keys together to open the Windows Search utility.
2. Type Powershell in the search bar and click on**Run as administrator** .
3. In the Powershell window, type the command mentioned below and hit**Enter** .  
`Get-AppxPackage Microsoft.SecHealthUI -AllUsers | Reset-AppxPackage`  
![Command to Reset Windows Security in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Command-to-Reset-Windows-Security-.jpg)
4. Once the command is executed, exit Powershell and check if the issue is resolved.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Remove Any Conflicting Software

 In case you have a third party installed on the system, it might be interfering with the processes of Windows Defender, preventing it from updating or functioning properly.

 If this applies to you, we recommend temporarily disabling the security program or uninstalling it. You can do this using the Control Panel or the Settings app. We have a detailed guide that discusses[how to remove programs in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) that you can refer to if you need help.

 If you can successfully update Windows Defender after removing the third-party software, then it implies that the program was indeed the culprit. In this case, you can switch to a better third-party alternative. Here are some[best free antivirus programs](https://www.makeuseof.com/tag/ten-best-antivirus-programs/) that you can consider installing.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Get Windows Defender Up and Running Again

 Issues with the Windows Defender can be frustrating and expose your system to security threats. Hopefully, the solutions we have described above will help you fix the engine unavailable problem and use the security program to its full potential. If the problem occurs repeatedly in the future, you can report the issue to the official Microsoft support team and switch to a third-party solution until an official fix is released.


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
<li><a href="https://some-techniques.techidaily.com/new-explore-virtual-realms-with-top-gadgets-and-peripherals/"><u>[New] Explore Virtual Realms with Top Gadgets and Peripherals</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-optimize-vertical-or-horizontal-vids-on-fb-for-2024/"><u>[New] How To Optimize Vertical or Horizontal Vids On FB for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-best-companions-premium-mac-programs-for-videography/"><u>[New] In 2024, Best Companions  Premium Mac Programs for Videography</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-solving-problems-missing-facebook-video-suggestions/"><u>[Updated] 2024 Approved  Solving Problems  Missing Facebook Video Suggestions</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-dynamic-action-photography-on-your-iphone/"><u>[Updated] In 2024, Dynamic Action Photography on Your iPhone</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-in-class-top-drone-gimbals-compared/"><u>2024 Approved  Best in Class  Top Drone Gimbals Compared</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-capture-and-preserve-snapchat-moments-top-techniques/"><u>2024 Approved  Capture and Preserve Snapchat Moments  Top Techniques</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-comparing-av1-and-vp9-which-is-more-advanced/"><u>2024 Approved  Comparing AV1 & VP9  Which Is More Advanced?</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-windows-compatible-art-tools-alike-procreate/"><u>Essential Windows-Compatible Art Tools Alike Procreate</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-significance-of-versions-in-windows-updates/"><u>Exploring the Significance of Versions in Windows Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-recurrent-disk-filling-on-windows-pcs/"><u>Fixes for Recurrent Disk Filling on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-the-script-revisiting-timeless-pc-games/"><u>Flipping the Script: Revisiting Timeless PC Games</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-hp-deskjet-2600-driver-software-for-win7win8win10-systems/"><u>Get the Latest HP Deskjet 2600 Driver Software for Win7/Win8/Win10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rectify-file-history-fault-in-windows/"><u>Guide to Rectify “File History Fault” In Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-activation-lock-on-ipod-and-iphone-6-the-right-way-by-drfone-ios/"><u>How To Bypass iCloud Activation Lock On iPod and iPhone 6 The Right Way</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-fix-and-eradicate-delays-in-fortnite-video-editing-expert-advice/"><u>How to Fix and Eradicate Delays in Fortnite Video Editing: Expert Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-mbs-service-disconnection-issue-on-windows-11/"><u>How to Remedy MB's Service Disconnection Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-update-windows-offline-with-portable-update/"><u>How to Update Windows Offline With Portable Update</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-nokia-g310-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Nokia G310 to Another | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multitasking-running-windows-11-in-macos-with-parallels/"><u>Mastering Multitasking: Running Windows 11 in MacOS with Parallels</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-snags-seven-strategies-to-connect-in-obs-windows/"><u>Navigating Network Snags: Seven Strategies to Connect in OBS Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/premium-photographic-archives/"><u>Premium Photographic Archives</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-your-invisible-wi-fi-connection-on-windows-11/"><u>Resurrect Your Invisible Wi-Fi Connection on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/shielding-operations-mastering-uac-security-measures/"><u>Shielding Operations: Mastering UAC Security Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-security-glitches-in-windows-1011/"><u>Steps to Address Security Glitches in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-razer-devices-not-detected-by-synapse-on-windows/"><u>Steps to Resolve Razer Devices Not Detected by Synapse on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-windows-11s-observer-mode/"><u>Strategies for Stopping Windows 11'S Observer Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-unresponsive-usb-cases-win-xpvista7810/"><u>Strategies to Fix Unresponsive USB Cases: Win XP/Vista/7/8/10</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721467826524-struggling-with-your-iphones-silence-unveil-vibration-fixes-for-both-ring-and-quiet-settings/"><u>Struggling with Your iPhones Silence? Unveil Vibration Fixes for Both Ring and Quiet Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-windows-11-woes-your-guide-to-fixing-11-issues/"><u>Tackle Windows 11 Woes - Your Guide to Fixing 11 Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-your-own-lock-pattern-in-windows-11/"><u>Tailor Your Own Lock Pattern in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/taking-control-importing-snapchat-snaps-to-your-phones-gallery/"><u>Taking Control  Importing Snapchat Snaps to Your Phone's Gallery</u></a></li>
<li><a href="https://windows11.techidaily.com/the-role-and-significance-of-windows-bt-folders/"><u>The Role and Significance of Windows ~BT Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-embellishing-system-tray-with-a-favorite-weather-symbol-in-windows-11/"><u>The Ultimate Guide to Embellishing System Tray With a Favorite Weather Symbol in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-windows-11-explorer-guide-pinpointing-your-machines-mac/"><u>The Windows 11 Explorer Guide: Pinpointing Your Machine's MAC</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-nubia-red-magic-8s-proplus-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Nubia Red Magic 8S Pro+ Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-trapped-troubleshooting-of-windows-update/"><u>Triumph Over Trapped Troubleshooting of Windows Update</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/uncovering-every-shared-element-in-a-chat-on-messenger/"><u>Uncovering Every Shared Element in a Chat on Messenger</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-auto-hdr-capabilities/"><u>Unveiling Windows 11'S Auto HDR Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-recorder-efficiency-essential-keyboard-shortcuts-in-windows-11/"><u>Voice Recorder Efficiency: Essential Keyboard Shortcuts in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/worth-the-price-tag-a-deep-dive-into-chatgpt-plus-benefits/"><u>Worth the Price Tag: A Deep Dive Into ChatGPT Plus Benefits</u></a></li>
</ul></div>
