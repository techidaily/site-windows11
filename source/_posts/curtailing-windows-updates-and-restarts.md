---
title: Curtailing Windows Updates and Restarts
date: 2024-08-08T05:56:10.541Z
updated: 2024-08-09T05:56:10.541Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Curtailing Windows Updates and Restarts
excerpt: This Article Describes Curtailing Windows Updates and Restarts
keywords: Delay Windows Updates,Reduce System Reboots,Postpone Update Intervals,Minimize PC Restart Frequency,Control Windows Patch Schedule,Limit OS Update Duration,Ease Update & Restart Cycles
thumbnail: https://thmb.techidaily.com/d108669ab03559524bb77121c4032c30df350e077c8698244c3203b72aed2547.jpg
---

## Curtailing Windows Updates and Restarts

 Microsoft regularly releases patch updates to enhance your device's performance and security. When you download this update, Windows often replaces the usual Shut Down and Restart buttons with “Update and shut down” to remind you not to miss the update.

 However, you may sometimes encounter the same message prompting even after performing these actions. Read this guide to resolve this issue and stop getting such annoying notifications.

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

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 3\. Run the Windows Update Troubleshooter

 Windows operating system comes with troubleshooting tools specific to each problem. To solve update-related issues, use the Windows Update troubleshooter. This tool detects corrupted, or faulty files associated with updates and fixes them automatically.

 To run the Windows Update Troubleshooter, follow these steps:

1. Right-click on **Start** and select **Settings** from the menu list.
2. Select **Windows Update** in the left sidebar, then click **Troubleshoot**.
3. On the next page, click **Other trouble-shooters**.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Look for **Windows Update** and click **Run** next to it.  
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
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
7. When a permissions pop-up appears, select the checkbox and click **Continue**.
8. After you delete the Software Distribution folder, you must restart the services you stopped. To do so, go back to the Command Prompt window and run the following command:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Now exit the Command Prompt window and restart your computer. After running these commands, check if the issue is solved.

 ​​​​

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
## 5\. Disable Windows Update

 If you keep encountering the issue, disable the Windows Update service. This will stop Windows from automatically downloading updates and showing the message.

 To disable Windows Update, follow these steps:

1. Press **Win + R** on your keyboard to open the Run command window.
2. Type **services.msc** in the dialog box and press Enter. This will open the Services console.
3. Search for **Windows Update**, right-click on it, and select **Stop**.  
![Stop Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/stop-windows-update-service.jpg)
4. Now double-click on **Windows Update** to open the Properties window.
5. On the **General** tab, click the **Startup type** drop-down and select **Disabled**.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![Disable Windows Update Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-windows-update-service.jpg)
6. Click **Apply** \> **OK** to save the changes.
7. Now close the window and restart your computer.

 Sometimes you may not see the Restart option in the Start menu. In that case, [run the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). Now type **shutdown -s -t 0** in the command prompt and hit Enter. This will restart your computer immediately.

 Here **0** is the time in seconds. If you want to delay the restart, use a higher number. For example, shutdown -s -t 10 will delay the restart by 10 seconds.

 ​​​​​After restarting, you should no longer see the “Update and Restart” or “Update and Shut Down” message.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
6. Now right-click on the .bat file and select **Run as administrator**.
7. When the UAC window appears, select **Yes** to continue.

 The script will start resetting the Windows Update components and may take a few minutes to complete. Once done, restart your computer and this should solve the issue.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-streamline-social-sharing-integrate-your-fb-story/"><u>[New] 2024 Approved  Streamline Social Sharing  Integrate Your FB Story</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-commanders-canvas-painting-victory-in-the-top-7-total-wars-for-2024/"><u>[New] Commanders' Canvas  Painting Victory in the Top 7 Total Wars for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-freemacos-the-ultimate-screen-logger/"><u>[New] In 2024, FreeMacOS  The Ultimate Screen Logger</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-lg-redefines-reality-with-its-latest-virtual-gaming-device/"><u>[New] LG Redefines Reality with Its Latest Virtual Gaming Device</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-precision-recording-a-stepwise-plan-for-pc-ios-macbooks-for-2024/"><u>[New] Precision Recording  A Stepwise Plan for PC, iOS, MacBooks for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-comprehensive-tutorial-inserting-text-into-photographs-on-oses/"><u>[Updated] 2024 Approved  Comprehensive Tutorial  Inserting Text Into Photographs on OSes</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-network-neutralizer-overcoming-facebook-intrusion/"><u>[Updated] 2024 Approved  Network Neutralizer  Overcoming Facebook Intrusion</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-maximize-networking-with-fb-link-downloader-tools-for-2024/"><u>[Updated] Maximize Networking with FB Link Downloader Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-superlative-picture-based-adventure-builder/"><u>[Updated] Superlative Picture-Based Adventure Builder</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-charting-the-financial-pathway-of-tseries-within-youtube-market-space/"><u>2024 Approved  Charting the Financial Pathway of TSeries Within YouTube Market Space</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-realme-12plus-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Realme 12+ 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/comparing-titans-in-digital-audio-workstations-is-magix-samplitude-at-the-pinnacle/"><u>Comparing Titans in Digital Audio Workstations Is MAGIX Samplitude at the Pinnacle?</u></a></li>
<li><a href="https://vp-tips.techidaily.com/delving-into-the-world-of-samsung-image-processor-2023/"><u>Delving Into the World of Samsung Image Processor, 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/dodgy-deals-understanding-the-threats-of-low-price-windows-licenses/"><u>Dodgy Deals: Understanding the Threats of Low-Price Windows Licenses</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-dynamics-streamlining-storage-space-in-win11/"><u>Drive Dynamics: Streamlining Storage Space in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-reactivate-printing-services/"><u>Easily Reactivate Printing Services</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-command-line-master-20-key-cmd-commands/"><u>Efficient Command Line: Master 20 Key CMD Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-windows-partition-integration-strategies/"><u>Efficient Windows Partition Integration Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-workstation-toggling-with-advanced-rdp-windows/"><u>Effortless Workstation Toggling with Advanced RDP Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-internet-safety-in-windows-11-trusted-site-listing/"><u>Elevate Internet Safety in Windows 11: Trusted Site Listing</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-usability-and-style-for-windows-1011-in-8-ways/"><u>Elevate Usability and Style for Windows 10/11 in 8 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-window-management-crafting-unique-snapping-patterns/"><u>Elevate Window Management: Crafting Unique Snapping Patterns</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-game-amplifying-graphics-power-in-windows-1011/"><u>Elevate Your Game: Amplifying Graphics Power in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-device-safety-with-custom-lock-patterns-in-windows-11/"><u>Elevating Device Safety with Custom Lock Patterns in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-hyper-v-bsod-steps-to-restore-windows/"><u>Eliminate Hyper-V BSOD: Steps to Restore Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-we-encountered-an-error-oculus-w11w10-guide/"><u>Eliminating We Encountered an Error: Oculus W11/W10 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-11-taskbar-chat-implications-unveiled/"><u>Eliminating Window's 11 Taskbar Chat: Implications Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/embark-on-cross-platform-development-via-windows-subsystem/"><u>Embark on Cross-Platform Development via Windows Subsystem</u></a></li>
<li><a href="https://windows11.techidaily.com/embarking-on-a-journey-with-ai-copilot-in-windows-11/"><u>Embarking on a Journey with AI Copilot in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-convenience-using-googles-nearby-share/"><u>Embracing Convenience: Using Google's Nearby Share</u></a></li>
<li><a href="https://windows11.techidaily.com/emergency-printer-deletion-in-windows-os-a-step-by-step-approach/"><u>Emergency Printer Deletion in Windows OS: A Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-11-android-phone-webcam-utilization/"><u>Empowering Windows 11: Android Phone Webcam Utilization</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-gaming-with-streamlined-directx-maintenance/"><u>Enhance PC Gaming with Streamlined DirectX Maintenance</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-photos-step-by-step-background-elimination/"><u>Enhancing Photos: Step-by-Step Background Elimination</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-qbittorrent-performance-after-a-halt/"><u>Enhancing qBittorrent Performance After a Halt</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-folder-management-custom-move-and-copy-commands-in-windows/"><u>Enriching Folder Management: Custom Move and Copy Commands in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-macos-with-windows-powered-innovations/"><u>Enriching macOS with Windows-Powered Innovations</u></a></li>
<li><a href="https://windows11.techidaily.com/enriching-windows-taskmanager-with-cli-tab-feature/"><u>Enriching Windows TaskManager with CLI Tab Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-black-screen-on-win11-top-easy-fixes/"><u>Eradicate Black Screen on Win11: Top Easy Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-glitch-windows-edition-geforce-x0001/"><u>Eradicating Glitch: Windows Edition, GeForce X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-6-tools-gpu-load-check-in-windows-environment/"><u>Essential 6 Tools: GPU Load Check in Windows Environment</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-realme-c55-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Realme C55 FRP Locks</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-play-8t-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Honor Play 8T Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>How to Fake Snapchat Location without Jailbreak On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-note-30-5g-phone-without-pin-by-drfone-android/"><u>How to Unlock Infinix Note 30 5G Phone without PIN</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-create-an-apple-developer-account-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, How To Create an Apple Developer Account On Apple iPhone 12</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-huawei-p60-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Huawei P60 Phones</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-rotate-your-mov-files-for-free-top-5-options/"><u>New 2024 Approved Rotate Your MOV Files for Free Top 5 Options</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-free-8-best-tools-to-make-animated-photo-easily-for-2024/"><u>New FREE 8 Best Tools to Make Animated Photo Easily for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-ubisoft-connect-errors-effectively-the-ultimate-guide-users/"><u>Resolving Ubisoft Connect Errors Effectively - The Ultimate Guide Users</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamless-viewing-guide-how-to-connect-apple-tv-plus-content-on-chromecast/"><u>Seamless Viewing Guide: How to Connect Apple TV Plus Content on Chromecast</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-samsung-galaxy-xcover-6-pro-tactical-edition-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Samsung Galaxy XCover 6 Pro Tactical Edition for Streaming | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-paramount-practices-in-gathering-your-precious-collection-of-high-fidelity-youtube-audio/"><u>Updated 2024 Approved Paramount Practices in Gathering Your Precious Collection of High-Fidelity YouTube Audio</u></a></li>
</ul></div>
