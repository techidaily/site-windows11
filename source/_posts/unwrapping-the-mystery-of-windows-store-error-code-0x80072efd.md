---
title: Unwrapping the Mystery of Windows Store Error Code 0X80072EFD
date: 2024-08-31T22:10:24.021Z
updated: 2024-09-01T22:10:24.021Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unwrapping the Mystery of Windows Store Error Code 0X80072EFD
excerpt: This Article Describes Unwrapping the Mystery of Windows Store Error Code 0X80072EFD
keywords: Windows Store Error X72EF,0X80072EFD Fix Guide,Unlocking Windows Error Code,Resolving X72EF in Windows,Windows App Install Failure,Troubleshoot Store Error X72EF,Fixing 0X80EC Windows
thumbnail: https://thmb.techidaily.com/6169c8a9aeeb67674aa07a2a9dad06d0ae5fef5e196eb54e46717e8334c8bace.jpg
---

## Unwrapping the Mystery of Windows Store Error Code 0X80072EFD

 Users have reported a 0x80072EFD Microsoft Store error on support forums that can arise in Windows 11 or 10\. Those users see a "server stumbled" or "check your internet connection" message with a 0x80072EFD error code inside MS Store after launching that app. When this error pops up, users can't utilize the Microsoft Store.

 The 0x80072EFD error is often a connection-related one. However, it occurs even when users can surf the web in their browsers. If you need to fix the 0x80072EFD error, try fixing it with these potential resolutions.

## 1\. Run the Windows Store App Troubleshooter

 Running the Windows Store App troubleshooter is a straightforward potential resolution for the 0x80072EFD error to start with. That troubleshooting tool might detect issues and give you a fix. You can open and run the Windows Store App troubleshooter like this:

1. Press**Start** and click the menu shortcut to open Settings.
2. Select the**Troubleshoot** section of Settings.
3. Click on**Other trouble-shooters** to look through the troubleshooting tools.
4. Select Windows Store Apps'**Run** option to bring up that troubleshooting tool.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-list-in-windows-11.jpg)
5. Go through and apply any suggestions the troubleshooter offers.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-store-apps.jpg)

**Internet Connections** is another troubleshooter that may be useful for fixing the Microsoft Store's 0x80072EFD error. So, consider running that troubleshooter if the Windows Store Apps option doesn't help.

 Note that the troubleshooting tools are accessible in the**Update & Security** category in the Settings app if you use Windows 10\. Click the**Troubleshoot** tab and**Additional troubleshooters** option to access them from there. Then press the**Run this troubleshooter** buttons for Windows Store Apps or Internet Connections.

## 2\. Refresh the SoftwareDistribution Folder

 SoftwareDistribution is a folder for temporarily storing Windows update files. Sometimes refreshing that folder by renaming it can resolve error**0x80072EFD** . Rename the SoftwareDistribution folder like this:

1. Hold down the**Windows** key and press**S** to access a search utility.
2. Type in**cmd** to find a Command Prompt app.
3. Open Command Prompt with elevated permissions by clicking its**Run as administrator** option in the search tool.
4. Turn off some services by executing these separate commands:  
`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`
5. To rename SoftwareDistribution, type in the following and hit**Enter** :  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The rename SoftwareDistribution.old folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-softwaredistribution-old-folder.jpg)
6. Also, rename a catroot2 directory with this command:  
`ren C:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-catroot2-command.jpg)
7. Restart the turned-off services by inputting and executing the following commands:  
`net start wuaserv  
net start cryptSvcc  
net start bits  
net start msiserver`
8. Then bring up your Start menu to select**Restart** .

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Reset the Microsoft Store's Cache

 Microsoft store has a cache in which data accumulates. Resetting or clearing that cache's data is a reliable solution to various Microsoft Store issues. So, we recommend users try doing that when troubleshooting the 0x80072EFD error. You can clear that cache in Settings, as covered in our[guide for resetting apps](https://www.makeuseof.com/windows-reset-app/) in Windows 11 and Windows 10.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-button.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
6. Select the Local Area Network window's**OK** option.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
3. Select to turn off the**Set time zone** option there.
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
5. Then press the**Sync now** button.  
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)

 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
6. Select**OK** to exit the Internet Options window.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reregister Microsoft Store

 You can't reinstall Microsoft Store like other apps. However, reregistering it with PowerShell is similar to reinstalling. If other potential solutions don't fix the 0x80072EFD error, reregistering MS Store is worth a try. This is how you can register that app:

1. Activate the**Type here to search** box with that tool's**Windows** +**S** hotkey.
2. Enter**PowerShell** within that tool's search box.
3. Launch Windows PowerShell with elevated permissions by clicking that search result's**Run as administrator** option.
4. Input this command for reregistering MS Store and hit**Return** to execute:  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reregister MS Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reregister-ms-store-command.jpg)
5. Wait until you're sure the command has finished.
6. Then exit PowerShell, and select the**Restart** option.

## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Shopping in Microsoft Store Again

 The 0x80072EFD error isn't always easy to fix, and you may have to try applying quite a few potential resolutions to get it sorted. However, many Microsoft Store users have fixed the 0x80072EFD error with the solutions in this guide. So, maybe one of those potential fixes will also work on your PC.

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
<li><a href="https://fox-hovers.techidaily.com/new-effervescent-emotions-on-iphone-for-2024/"><u>[New] Effervescent Emotions on IPhone for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-elevate-your-video-game-proficient-cropping-and-export-strategies-for-2024/"><u>[New] Elevate Your Video Game  Proficient Cropping & Export Strategies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-full-review-for-gopro-hero4-sliver/"><u>[New] Full Review for GoPro Hero4 Sliver</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-videos-that-speak-volumes-for-marketing-success/"><u>[New] In 2024, Videos That Speak Volumes for Marketing Success</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-maximizing-impact-with-tiktok-video-uploads-from-pcmac-for-2024/"><u>[New] Maximizing Impact with TikTok Video Uploads From PC/Mac for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-preserving-audio-visual-content-itunes-edition-for-2024/"><u>[New] Preserving Audio-Visual Content  ITunes Edition for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-step-by-step-guide-for-cutting-edge-editing-in-gopro-studio/"><u>[New] Step-by-Step Guide for Cutting-Edge Editing in GoPro Studio</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-comparing-social-platforms-facebook-live-vs-youtube-live-and-twitter-periscope/"><u>[Updated] 2024 Approved  Comparing Social Platforms  Facebook LIVE Vs. YouTube Live & Twitter Periscope</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-crafting-an-ideal-speech-translation-experience-in-google/"><u>[Updated] Crafting an Ideal Speech Translation Experience in Google</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ideal-steadicams-to-amplify-your-dslr-cinematic-impact/"><u>[Updated] Ideal Steadicams to Amplify Your DSLR Cinematic Impact</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-from-novice-to-niche-tripling-your-youtube-fans/"><u>[Updated] In 2024, From Novice to Niche  Tripling Your Youtube Fans</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-optimized-protocols-snapshots-of-gotomeetings-made-simple-for-2024/"><u>[Updated] Optimized Protocols  Snapshots of GoToMeetings Made Simple for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-peak-of-digital-preservation-elite-storage-guide/"><u>[Updated] Peak of Digital Preservation  Elite Storage Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snappy-stories-how-to-record-snapchat-mobilely/"><u>2024 Approved  Snappy Stories - How to Record Snapchat Mobilely</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-realme-12-proplus-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Realme 12 Pro+ 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-customizing-windows-11-default-apps/"><u>Essential Guide to Customizing Windows 11 Default Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-filenames-5-windows-utilities-for-date-manipulation/"><u>Fix Filenames: 5 Windows Utilities for Date Manipulation</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-nvidias-geforce-now-error-code-xc0f1103f/"><u>Fixing NVIDIA's GeForce Now Error Code: Xc0f1103f</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-silent-sounds-windows-audio-glitches/"><u>Fixing Silent Sounds: Windows Audio Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-video-playback-issues-with-error-0xc10100bf/"><u>Fixing Video Playback Issues with Error 0XC10100BF</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gopros-deep-sea-capturing-unforgettable-underwater-scenes-for-2024/"><u>GoPro's Deep Sea  Capturing Unforgettable Underwater Scenes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-windows-components-administration-tool/"><u>Guide to Windows Components Administration Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/has-windows-subsystem-shifted-linux-desktops/"><u>Has Windows Subsystem Shifted Linux Desktops?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-this-non-genuine-adobe-app-will-be-disabled-soon-pop-up-on-windows/"><u>How to Fix the “This Non-Genuine Adobe App Will Be Disabled Soon” Pop-Up on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-activation-error-0x803f700f/"><u>How to Fix the Windows Activation Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-windows-network-access/"><u>How To Restore Windows Network Access</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-13-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on Apple iPhone 13</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-overcome-directdraw-errors-in-win1011-environments/"><u>How to Swiftly Overcome DirectDraw Errors in Win10/11 Environments</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-a79-5g-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo A79 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/is-the-windows-aggregatehostexe-system-process-safe-an-analysis/"><u>Is the Windows AggregateHost.exe System Process Safe? An Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-blue-screen-chaos-a-systematic-approach/"><u>Navigating Blue Screen Chaos: A Systematic Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-protection-activating-tpm-and-secure-boot-in-win-11/"><u>Optimal PC Protection: Activating TPM & Secure Boot in Win 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/pro-tips-configuring-stopwatches-in-obs-studio/"><u>Pro Tips  Configuring Stopwatches in OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-enabling-and-customizing-sandbox-in-win-11/"><u>Quick Start: Enabling and Customizing Sandbox in Win 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-functionality-to-window-bar-taskbar/"><u>Reinstating Functionality to Window Bar (Taskbar)</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-for-locating-vanished-registry-management-utility/"><u>Secrets for Locating Vanished Registry Management Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-steps-to-alter-your-cursors-look/"><u>Simplified Steps to Alter Your Cursor's Look</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-disk-errors-on-windows-1011-a-step-by-step-guide/"><u>Tackling Disk Errors on Windows 10/11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-inability-to-run-os-disk-organizer/"><u>Tackling Inability to Run OS Disk Organizer</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pubg-save-settings-breakdown-on-win-oses/"><u>Tackling PUBG Save Settings Breakdown on Win OSes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/tips-of-transferring-messages-from-motorola-defy-2-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Tips of Transferring Messages from Motorola Defy 2 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-elevate-task-prominence-and-reduce-window-chaos-on-win-11/"><u>Tips to Elevate Task Prominence and Reduce Window Chaos on Win 11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-honor-90-gt-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Honor 90 GT Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-windows-not-recognizing-an-interface/"><u>Troubleshoot Windows Not Recognizing an Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-microsofts-error-code-0x8007251d-on-windows/"><u>Troubleshooting Microsoft's Error Code 0X8007251d on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063679712-unlock-full-usb-potential-with-one-step-adb/"><u>Unlock Full USB Potential With One-Step ADB!</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-upgraded-widget-choice-interface-in-win11/"><u>Unlocking Upgraded Widget Choice Interface in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-with-non-admin-steps/"><u>Unlocking Windows 11 With Non-Admin Steps</u></a></li>
<li><a href="https://techidaily.com/vivo-v29e-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Vivo V29e support - Turn Off Screen Lock.</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-next-gen-computing-at-ifa-2023/"><u>Your Guide to Next-Gen Computing at IFA 2023</u></a></li>
</ul></div>
