---
title: "Overcoming Windows Update Error: 0X800736CC Fix Guide"
date: 2024-08-27T16:11:34.505Z
updated: 2024-08-28T16:11:34.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows Update Error: 0X800736CC Fix Guide"
excerpt: "This Article Describes Overcoming Windows Update Error: 0X800736CC Fix Guide"
keywords: Fixing Windows Update Error,0X800736CC Resolution,Overcoming Update Issue,Windows Updater Troubleshoot,XP Error Correction Guide,Stop Windows Update Failure,Remedy XError in WinUpdates
thumbnail: https://thmb.techidaily.com/2e98346ae0ee2e0559c5260d992a7113232d0df75bda10dff9dc91899db94103.jpg
---

## Overcoming Windows Update Error: 0X800736CC Fix Guide

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
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
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-discovering-the-most-shared-twitvideos-of-the-year/"><u>[New] 2024 Approved  Discovering the Most Shared TwitVideos of the Year</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-optimal-video-chat-on-windows-1-8/"><u>[Updated] Optimal Video Chat on Windows  #1-8</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-exploring-profit-sharing-in-youtube-short-creation/"><u>2024 Approved  Exploring Profit Sharing in YouTube Short Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-non-scrolling-issue-unlock-cells-in-excel-windows/"><u>Fix Non-Scrolling Issue: Unlock Cells in Excel (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-failed-steam-remote-links-on-pc/"><u>Fixing Failed Steam Remote Links on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-outlooks-restricted-folder-access-on-desktop-computers/"><u>Fixing Outlook's Restricted Folder Access on Desktop Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-high-contrast-customization-in-windows/"><u>Halt High Contrast Customization in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-realme-12-pro-5g-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Realme 12 Pro 5G to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-apple-iphone-15-pro-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on Apple iPhone 15 Pro</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-apple-iphone-8-plus-device-from-icloud-by-drfone-ios/"><u>How to Remove Apple iPhone 8 Plus Device from iCloud</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-nokia-c300-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Nokia C300 FRP In 3 Different Ways</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-stolen-iphone-15-in-different-conditionsin-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Stolen iPhone 15 In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-science-of-naming-your-podcast-for-success/"><u>In 2024, The Science of Naming Your Podcast for Success</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-earning-cash-online-with-no-skills-needed/"><u>In 2024, The Ultimate Guide to Earning Cash Online with No Skills Needed</u></a></li>
<li><a href="https://hardware-help.techidaily.com/lenovo-thinkpad-t500-quick-and-easy-driver-downloads-and-firmware-update-guide/"><u>Lenovo ThinkPad T500: Quick and Easy Driver Downloads & Firmware Update Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cortana-integration-vivetool-writings/"><u>Mastering Cortana Integration: ViveTool' Writings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-discords-search-tweaks/"><u>Mastering Windowed Discord's Search Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-modify-display-settings/"><u>Method to Modify Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-windows-update-code-error-0x8024800c/"><u>Methods to Fix Windows Update: Code Error 0X8024800C</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-vn-video-editor-for-pc-a-short-and-sweet-review-for-2024/"><u>New VN Video Editor for PC A Short and Sweet Review for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/notable-industry-players-driving-vr-growth-for-2024/"><u>Notable Industry Players Driving VR Growth for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/open-locked-windows-shared-files-now/"><u>Open Locked Windows Shared Files Now</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcome-apex-legends-crashes-and-errors-with-our-proven-solutions/"><u>Overcome Apex Legends Crashes and Errors with Our Proven Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-discrepancy-in-windows-11s-power-life-predictor/"><u>Overcoming Discrepancy in Windows 11'S Power Life Predictor</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-visuals-your-guide-to-leveraging-background-blur-on-windows-11-photos-app/"><u>Perfect Visuals: Your Guide to Leveraging Background Blur on Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-system-status-and-update-information-via-menu-option-in-win11/"><u>Quick Access to System Status & Update Information via Menu Option in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-unconnected-error-with-geforce-experience-on-pc/"><u>Rectifying Unconnected Error with GeForce Experience on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-journey-in-windows-11-the-top-8-slippery-slope/"><u>Safe Journey in Windows 11: The Top 8 Slippery Slope</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift.</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/step-up-your-language-game-with-dark-on-netflix/"><u>Step Up Your Language Game with Dark on Netflix</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-fix-guide-to-replace-msvcr120dll-in-windows/"><u>Step-by-Step Fix Guide to Replace MSVCR120.dll in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-mastery-tips-for-multitasking-windows-11/"><u>Supercharge Your Workday: Mastery Tips for Multitasking Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-windows-11s-protected-mode-graphics/"><u>Supercharging Windows 11'S Protected Mode Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-success-guiding-through-windows-11-renewal/"><u>Systematic Success: Guiding Through Windows 11 Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-managing-windows-users-via-cli/"><u>The Art of Managing Windows Users via CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-compatible-windows-and-android-programs/"><u>Top 8 Compatible Windows and Android Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072efd-on-windows-devices/"><u>Troubleshooting Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/turning-views-into-revenue-mastering-youtubes-financial-landscape/"><u>Turning Views Into Revenue  Mastering YouTube's Financial Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-print-potential-strategies-to-fix-slide-show-problems-on-windows/"><u>Unlocking Your Print Potential: Strategies to Fix Slide Show Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackle-administrative-access-on-pcs/"><u>Unshackle Administrative Access on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-video-quality-from-yesteryears-using-madvr-windows-edition/"><u>Upgrade Video Quality From Yesteryears Using MadVR, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-up-call-reviving-sleeping-pcs-with-inputs-on-1011/"><u>Wake-Up Call: Reviving Sleeping PCs with Inputs on 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-your-disconnected-wi-fi/"><u>Winning Back Your Disconnected Wi-Fi</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-game-of-cutting-top-8-video-edits-for-pc/"><u>Winning the Game of Cutting: Top 8 Video Edits for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-comparison-how-chkdsk-and-sfc-differ-from-dissect/"><u>WinTools Comparison: How CHKDSK and SFC Differ From Dissect</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>