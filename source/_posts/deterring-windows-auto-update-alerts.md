---
title: Deterring Windows Auto-Update Alerts
date: 2024-08-08T05:59:20.925Z
updated: 2024-08-09T05:59:20.925Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deterring Windows Auto-Update Alerts
excerpt: This Article Describes Deterring Windows Auto-Update Alerts
keywords: Stop Auto-Windows Updates,Prevent Update Notifications,Halt Windows Update Alert,Disable Update Prompts,Avoid Windows Update Messages,Turn Off Auto-Update Warnings,Block Window's Auto Update
thumbnail: https://thmb.techidaily.com/54fd3e003b786647a6f1d7a89a0a9ff3e56e44f972b8ef6e36ebd7fc54a18cb3.jpg
---

## Deterring Windows Auto-Update Alerts

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Restart the Computer From Settings

 If restarting your computer with the power button does not work, do it via the Settings Menu. This trick has worked for many users who encountered the same issue. Try it and see if that helps.

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click **Windows Update** in the left sidebar.
3. Under Windows Update, you will find the **Restart now** option.
4. Select this option to restart your computer and install the pending updates.

## 2\. Install Pending Updates

 If your computer keeps reminding you to update and shuts down, check for pending updates. It is possible that the updates were not installed properly and Windows is now asking you to complete them.

 To check for pending updates, follow these steps.

1. Press **Win + I** on your keyboard to open the Settings menu.
2. From the left sidebar, click on the **Windows Update** tab.
3. Select the **Check for updates** option from the right pane.

 This will search for available updates and install them if there are any. If you see no updates, continue to the next solution.

## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the instructions on the screen to let Windows Update Troubleshooter detect and fix problems. After running the troubleshooter, restart your computer and check if it solves the issue.

## 4\. Clear the Software Distribution Folder

 The Software Distribution folder contains downloaded updates and installation files. If these files become corrupted, it could lead to this issue. To fix it, clear the Software Distribution directory and check if that solves the problem.

1. Open the Start menu and type CMD in the search bar.
2. Press **Ctrl + Shift + Enter** on your keyboard. This will open the Command Prompt as an administrator.
3. If a User Account Control window appears, click **Yes** to grant administrative privileges.
4. In the command prompt window, type the following commands in the order given and press Enter after each command:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After that, open File Explorer and navigate to this path:  
`C:\Windows\SoftwareDistribution`
6. In the SoftwareDistribution folder, select all the files and delete them permanently.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

## 6\. Reset the Windows Update Components

 If none of the solutions above work, reset Windows Update components. It deletes all the temporary download files and resets the registry keys containing information about Windows Update. This process also clears any corrupted files associated with updates and allows Windows to download the updates again.

 To reset the Windows Update components, follow these steps:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy the following commands and paste them into the Notepad window.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
3. Click **File** and select **Save as** from the menu list.
4. In the dialog box, select **All Files** from the **Save as type** drop-down menu.
5. Save the file as **ResetWindowsUpdate.bat** and close Notepad.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

## Resolving Incorrect Notifications for Updates and Restarts

 Now that you know how to fix incorrect notifications for updates and restarts, you can avoid this issue in the future. Make sure Windows Update is configured correctly and reset components. Also, keep your computer updated with the latest security patches. Doing this will also ensure smooth system operation.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-exquisite-couple-clips-the-best-weddings-online-8-picks-for-2024/"><u>[New] Exquisite Couple Clips  The Best Weddings Online (8 Picks) for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-hide-and-seek-top-5-for-secret-story-lovers/"><u>[New] In 2024, Hide & Seek  Top 5 For Secret Story Lovers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/aximize-visuals-in-youtubespace-with-effective-tools/"><u>[New] Maximize Visuals in YouTubespace with Effective Tools</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-yt-highlights-year-end-spotlight-on-top-music-reactions/"><u>[Updated] 2024 Approved  YT Highlights  Year-End Spotlight on Top Music Reactions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-build-a-fortified-mc-base-plan-6-10/"><u>[Updated] In 2024, Build a Fortified MC Base  Plan #6-10</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-unveiling-the-best-fb-movie-grabs-8-edition/"><u>[Updated] In 2024, Unveiling the Best FB Movie Grabs  #8 Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-history-on-your-flip-watching-old-fb-stories/"><u>2024 Approved  History on Your Flip  Watching Old FB Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-fix-minecrafts-exit-code-1-on-windows/"><u>6 Ways to Fix Minecraft's Exit Code: 1 on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/7-top-choices-no-cost-win-compatible-players/"><u>7 Top Choices: No-Cost Win-Compatible Players</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-fix-manual-for-widespread-rainmeter-problems/"><u>A Comprehensive Fix Manual for Widespread Rainmeter Problems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/a-detailed-look-into-chatgpts-impact-on-innovative-composition-benefits-and-drawbacks/"><u>A Detailed Look Into ChatGPT's Impact on Innovative Composition: Benefits and Drawbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/a-journey-into-innovation-windows-11-writes-the-next-chapter/"><u>A Journey Into Innovation - Windows 11’ Writes the Next Chapter</u></a></li>
<li><a href="https://windows11.techidaily.com/a-simple-guide-to-resolving-windows-error-0xc0000001/"><u>A Simple Guide to Resolving Windows Error 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-control-panel-with-ease-on-pcs/"><u>Accessing Control Panel with Ease on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-graphics-problem-3-for-windows-11-users/"><u>Addressing Graphics Problem #3 for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-high-cpu-consumption-on-host-systems/"><u>Addressing High CPU Consumption on Host Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-vagrant-boot-failures-on-win11plusvmware/"><u>Addressing Vagrant Boot Failures on Win11+VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-store-failure-code-0x800704cf/"><u>Addressing Windows Store Failure Code 0X800704CF</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-strategies-for-overcoming-win11-installer-challenges/"><u>Advanced Strategies for Overcoming Win11 Installer Challenges</u></a></li>
<li><a href="https://extra-hints.techidaily.com/animatedapp-full-guide-24-edition/"><u>AnimatedApp Full Guide '24 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/"><u>Balancing CPU & Memory Use After News Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-how-to-fix-your-disconnected-ps4-remote-control-on-windows/"><u>Breaking the Cycle: How to Fix Your Disconnected PS4 Remote Control on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-license-validity-time-out-alerts-on-win10w11/"><u>Bypassing License Validity Time-Out Alerts on Win10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-communication-test-your-mic-on-pc/"><u>Clear Communication: Test Your Mic on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/connected-scribbles-using-stickies-across-all-devices-in-win11/"><u>Connected Scribbles: Using Stickies Across All Devices in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-computing-10-non-windows-app-favorites/"><u>Cutting-Edge Computing: 10 Non-Windows App Favorites</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-vintage-of-a-windows-pc/"><u>Deciphering Vintage of a Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-process-aggregatorhostexe-use-and-risks/"><u>Deciphering Windows Process AggregatorHost.exe: Use and Risks</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphring-and-diagnosing-predominant-windows-anydesk-problems/"><u>Deciphring and Diagnosing Predominant Windows AnyDesk Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-frequent-rainmeter-anomalies-in-windows-environment/"><u>Decoding Frequent Rainmeter Anomalies in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-high-cpu-usage-in-wmi/"><u>Decreasing High Cpu Usage in WMI</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-defunct-windows-security-hurdles-in-win-11/"><u>Defeating Defunct Windows Security Hurdles in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-windows-11-browser-configuration/"><u>Discovering Windows 11 Browser Configuration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My OnePlus Ace 3? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-huawei-nova-y71-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Huawei Nova Y71 Phones with/without a PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pinnacle-photo-the-leading-6-4k-dslr-cameras-of-the-year/"><u>In 2024, Pinnacle Photo  The Leading 6 4K DSLR Cameras of the Year</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-12-pro-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone 12 Pro</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-ultimate-guide-to-instagrams-magnifying-functions/"><u>In 2024, The Ultimate Guide to Instagram's Magnifying Functions</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-adobe-cloud-essentials-and-top-alternatives-for-2024/"><u>Mastering Adobe Cloud  Essentials & Top Alternatives for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-vivo-y27s-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Vivo Y27s Device</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-unrestricted-video-editing-top-10-free-online-tools-with-no-watermark-for-2024/"><u>New Unrestricted Video Editing Top 10 Free Online Tools with No Watermark for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/quick-clip-art-creator-seamless-image-to-cartoon-conversion/"><u>Quick Clip-Art Creator  Seamless Image-to-Cartoon Conversion</u></a></li>
</ul></div>
