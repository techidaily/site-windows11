---
title: Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11
date: 2024-08-27T16:04:24.351Z
updated: 2024-08-28T16:04:24.351Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11
excerpt: This Article Describes Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11
keywords: Win11 ZeroDrive Fix,Overcoming Def5 Error,OneDrive WinError,Solve Def5 Windows,Quick Win11 Onedrive,Uninstalling Def5,Troubleshoot 0X8004
thumbnail: https://thmb.techidaily.com/20e687e989a89b1dd45743ceb6d6d3c635644bf241cd4154d769e7b945709de7.jpg
---

## Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11

 Microsoft bundles OneDrive with Windows 11 by default. Despite not being the most popular cloud storage service, it's hard to ignore its 5 GB free cloud storage offer. It's less than Google Drive but still lucrative because it's built into Windows.

 However, some users face the infuriating error code 0x8004def5 whenever they try to launch it. The error code indicates a problem in establishing a connection with OneDrive.

 If you face the same error and cannot log in and access your OneDrive account, don't worry. We will list out multiple methods to restore OneDrive to its working state. Let's begin.

## 1\. Terminate OneDrive and Restart the App

 Before trying out any complex fixes, you must terminate all the active instances of OneDrive. After that, restart it to check if it connects with the server. Here's how:

1. Press**Ctrl + Shift + Esc** to[open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) .
2. Go to the top search bar and type**OneDrive** .
3. Switch to the**Details** tab. Right-click on the**OneDrive.exe** process and select the**End process tree** option from the context menu.
4. A popup window will launch. Click on the**End process tree** option.  
![Terminate OneDrive and Restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/terminate-onedrive-and-restart.jpg)
5. Open the Start menu and type OneDrive. Click on the**Open** option and check if the error pops up.

## 2\. Check if OneDrive Servers Are Down

 OneDrive stores all your data in a dedicated cloud server maintained by Microsoft. Despite promising 99% uptime, it is common for cloud services like OneDrive to encounter outages. Or the service could be down due to scheduled maintenance.

 You can visit the[Microsoft Service Health page](https://portal.office.com/servicestatus) to check which services are down. Alternatively, you can use third-party websites like[DownDetector](https://downdetector.com/) . That way, you can know if other users also face the same server outage issue. If that's the case, you have to wait until Microsoft resolves the problem and brings up the OneDrive servers again.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Completely Shut Down and Reboot Your Computer

 Background services are susceptible to glitches and crashes. If one or more such essential services encounter a glitch, it can impede apps that rely on them. However, Windows 11 enables Fast Startup by default which preserves the state of all system and kernel processes for speeding up boot time.

 Even if you shut down the system, it will not close and restart all processes and services. So, you must perform a complete shutdown. Repeat the following steps to do so:

1. Press**Win + R** to open the Run command box. Type**cmd** and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Now, type the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a complete system shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/perform-a-complete-system-shutdown.jpg)
3. A complete shutdown will take longer than usual. Wait for the system to Restart and boot to the desktop.
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Now, launch OneDrive and check if you can access your files.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Switch Network Connections

 It is possible that your current ISP, or the network you are connected to, blocks Microsoft's servers. Many users shared they were able to fix the issue when they switched to another network. You can simply create a wireless hotspot from your phone or use USB tethering to share the internet with your Windows computer.

 After that, relaunch the OneDrive app and check if you can access your files on the network. You can also request your ISP to remove the block on your connection to access the OneDrive servers seamlessly in the future.

## 5\. Clear OneDrive Logs

 You can try clearing OneDrive telemetry log files in the app data folder. Here's how to do it:

1. Press**Win + E** to[open the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) .
2. Go to the address bar, type the following path, and replace the "**UserName** " with your PC's username:  
C:\Users\UserName\AppData\Local\Microsoft\OneDrive\setup\logs
3. Press the enter key to navigate to the OneDrive logs folder.
4. Locate the**userTelemetryCache.otc** file and copy it.**Paste** it to any other disk drive on your system.
5. Return to the logs folder and**delete** the**userTelemetryCache.otc** file.  
![Clear OneDrive Logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-onedrive-logs.jpg)
6. Close the File Explorer and restart your system.
7. Launch OneDrive and then check if it encounters the same error code.

## 6\. Reset OneDrive

 You can reset some Windows apps by accessing their advanced settings. But OneDrive doesn't have an advanced settings option in the Settings app. So, you need to reset it manually using the command prompt. Here's how:

1. Press**Win + R** to open the Run command box. Type**cmd** and press the Enter key to open a new Terminal window.
2. Type the following command and press the enter key:  
%localappdata%\Microsoft\OneDrive\onedrive.exe /reset
3. Wait for the command to reset OneDrive. You will see the OneDrive window popup informing you that the reset is underway.  
![Reset OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-onedrive-1.jpg)
4. Close the app after you see the "Reset completed" message. Restart your system.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Reinstall OneDrive Using Winget

 If resetting the app didn't work, consider a complete reinstall. It will fix any underlying corruption with the app files and install the latest version on your system. Here's how to do it with the Winget tool:

1. Press**Win + R** to open the Run command box. Type**cmd** in the text box and press**Ctrl + Shift + Enter** keys to open the command prompt with administrator privileges.
2. Type the**winget list onedrive** command and press the enter key.**Copy** the**ID** of the OneDrive app.
3. Now, run the**winget uninstall** command with the OneDrive app ID. This is what it will look like:**Winget uninstall Microsoft.OneDrive**
4. Wait for winget to remove OneDrive from your system. To confirm the uninstallation, type the following command:**winget list onedrive**
5. You will see that no package named OneDrive is not present on your system.  
![Reinstall OneDrive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-1.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
1. Type**cls** to clear the command prompt window.
2. Now, input the following command and press the enter key:**winget install Microsoft.OneDrive**  
![Reinstall OneDrive 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reinstall-onedrive-2.jpg)
3. Wait for the tool to download and install OneDrive on your system. You don't need to interact with the installer.
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. **Close** the command prompt window after seeing the "**Successfully installed** " message.
5. Launch OneDrive. You will have to**sign in** with your account.
6. Check if you can connect and browse your files.

## 8\. Rollback Windows Updates

 New Windows updates can sometimes wreck your system and break app compatibility. If OneDrive runs fine before installing a new update,[roll back the Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) . It could take longer if the update file is too big and not all Windows updates can be undone. After that, restart your system and try running the OneDrive app.

## 9\. Restore or Reset the PC

 If you still face the OneDrive error code, it's time to[perform a System Restore or a Windows Reset](https://www.makeuseof.com/windows-reset-system-restore-difference/) . It will help you revert to an old but working system configuration when OneDrive was working fine. Look for the most recent restore point in the wizard and use that.[Perform a factory reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) only if you don't have any Windows Restore points available.

## Make OneDrive Functional Again

 OneDrive can fail to connect with the server for a variety of reasons. Start with basic troubleshooting and check if the OneDrive servers are active. After that, delete the telemetry log files and reset the app. If that has no impact, reinstall the OneDrive app and log in again.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-boosting-revenue-with-youtube-short-videos-a-complete-plan/"><u>[New] 2024 Approved  Boosting Revenue with YouTube Short Videos – A Complete Plan</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-data-to-drama-utilizing-google-trends-in-video-planning/"><u>[New] 2024 Approved  From Data to Drama  Utilizing Google Trends in Video Planning</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-how-to-create-gifs-from-youtube-videos-on-desktop-and-mobile-devices-for-2024/"><u>[New] How to Create GIFs From YouTube Videos on Desktop and Mobile Devices for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-instantaneously-enhance-your-facebook-page-with-songs/"><u>[Updated] 2024 Approved  Instantaneously Enhance Your Facebook Page with Songs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-fixing-obs-screen-blackout-problems/"><u>[Updated] In 2024, Fixing OBS Screen Blackout Problems</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-how-to-write-compelling-podcast-narratives-and-examples-at-no-cost/"><u>[Updated] In 2024, How to Write Compelling Podcast Narratives & Examples at No Cost</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-skyrocket-your-earnings-on-tiktok-discover-the-top-8-ways/"><u>[Updated] In 2024, Skyrocket Your Earnings on TikTok  Discover the Top 8 Ways</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-tune-into-your-instagram-feed-music-integration-essentials/"><u>[Updated] Tune Into Your Instagram Feed  Music Integration Essentials</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-poco-f5-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Poco F5 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/evaluating-the-variability-between-in-store-and-online-windows-reinstallations/"><u>Evaluating the Variability Between In-Store & Online Windows Reinstallations</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expedited-photographic-viewing-in-windows-10-for-2024/"><u>Expedited Photographic Viewing in Windows 10 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-corrupted-files-in-windows-10-and-11/"><u>Fixes for Corrupted Files in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-halt-windows-11-data-harvesting/"><u>Guide to Halt Windows 11 Data Harvesting</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-itel-a60-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Itel A60 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-healthcare-marketing-mastering-fb-ad-strategies/"><u>In 2024, Healthcare Marketing  Mastering FB Ad Strategies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-quick-overview-of-colour-difference-filming/"><u>In 2024, Quick Overview of Colour Difference Filming</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-powershell-to-gauge-file-sizes-in-os/"><u>Leveraging PowerShell to Gauge File Sizes in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-time-transferring-classic-titles-to-photos/"><u>Navigating Through Time: Transferring Classic Titles to Photos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-xiaomi-redmi-13c-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Xiaomi Redmi 13C? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-win-power-the-ultimate-list-of-apps-to-boost-workflow-on-win-11/"><u>Pro-Win Power: The Ultimate List of Apps to Boost Workflow on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-and-reclaim-resetting-ms-store-in-windows-1011/"><u>Reboot and Reclaim: Resetting MS Store in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-administrative-functionality-in-microsoft-tools/"><u>Restoring Administrative Functionality in Microsoft Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-in-windows-services-explorer-with-these-7-steps/"><u>Restoring Functionality in Windows Services Explorer with These 7 Steps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/revamped-interview-inquiries-to-spark-podcast-fans-curiosity/"><u>Revamped Interview Inquiries to Spark Podcast Fans' Curiosity</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/scrutinizing-vivid-visuals-enhanced-by-hd-and-luminance-for-2024/"><u>Scrutinizing Vivid Visuals Enhanced by HD and Luminance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-play-eradicating-xbox-service-block/"><u>Seamless Play: Eradicating Xbox Service Block</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/secrets-to-stellar-youtube-livestreaming-top-cameras-for-2024/"><u>Secrets to Stellar YouTube Livestreaming - Top Cameras for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-windows-backup-defaults/"><u>Steps for Correcting Windows Backup Defaults</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enable-user-sign-in-following-windows-setback/"><u>Steps to Enable User Sign-In Following Windows Setback</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-dealing-with-non-downloading-errors-on-windows/"><u>Strategies for Dealing with Non-Downloading Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-rectifying-c0000005-on-windows-7vista/"><u>Strategies for Rectifying C0000005 on Windows 7/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-troubleshooting-for-flashing-displays-on-windows/"><u>Systematic Troubleshooting for Flashing Displays on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-security-hurdles-with-precision-and-care/"><u>Tackling Windows Security Hurdles with Precision & Care</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-vivo-s18e-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Vivo S18e Device</u></a></li>
<li><a href="https://windows11.techidaily.com/top-ways-to-resolve-black-screens-in-win1111-pro/"><u>Top Ways to Resolve Black Screens in Win11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/transition-to-sudo-windows-next-step/"><u>Transition to Sudo: Windows' Next Step</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-right-menu-options-for-optimal-software-use/"><u>Tweak Right-Menu Options for Optimal Software Use</u></a></li>
<li><a href="https://unlock-android.techidaily.com/universal-unlock-pattern-for-zte-nubia-z60-ultra-by-drfone-android/"><u>Universal Unlock Pattern for ZTE Nubia Z60 Ultra</u></a></li>
<li><a href="https://fox-info.techidaily.com/unlocking-the-potential-of-adobe-and-exploring-others/"><u>Unlocking the Potential of Adobe & Exploring Others</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-of-successful-setup-fixing-discord-install-issues-in-win-1011/"><u>Unlocking the Secrets of Successful Setup: Fixing Discord Install Issues in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-included-in-the-enhanced-windows-11-settings-app/"><u>What's Included in the Enhanced Windows 11 Settings App?</u></a></li>
</ul></div>
