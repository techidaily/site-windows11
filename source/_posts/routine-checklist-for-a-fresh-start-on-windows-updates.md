---
title: Routine Checklist for a Fresh Start on Windows Updates
date: 2024-09-29T18:41:55.963Z
updated: 2024-10-06T18:23:27.745Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Routine Checklist for a Fresh Start on Windows Updates
excerpt: This Article Describes Routine Checklist for a Fresh Start on Windows Updates
keywords: Update Routine Checklist,Fresh Windows Start List,System Update Guide,Windows Update Schedule,Tech Fix Protocols,Software Update Tips,Security Updates Plan
thumbnail: https://thmb.techidaily.com/b461869fdc65b7a58affdd23329a3336b55cdb42a5e0550c353e9047546c19d2.jpg
---

## Routine Checklist for a Fresh Start on Windows Updates

 When addressing errors and issues associated with a system update, you may need to reset the Windows Update components. You can achieve this by running a few commands in the Command Prompt or by creating and executing a batch file.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

## 1\. How to Reset the Windows Update Components Manually

 The most common method for resetting Windows Update components is through the Command Prompt. Here are the steps you can follow.

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt shows up.
3. Copy and paste the following commands one by one and press **Enter** after each command to stop each service related to Windows Update.  
`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`  
![Reset Windows Update Components Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-command-prompt.jpg)
4. Run the following command to delete the **qmgr\*.dat** files.  
`Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"`
5. Enter **Y** to confirm.

1. Type the following commands and press **Enter** after each to delete all the Windows Update files.  
`rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%\system32\catroot2 /S /Q`
2. Type the following commands and press **Enter** after each to reset the BITS and Windows Update services to their default security descriptors.  
`sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)`
3. Now, run the following command to navigate to the **System32** folder.  
`cd /d %windir%\system32`
4. Copy and paste the following commands individually and press **Enter** after each to re-register all the BITS and Windows Update files.  
`regsvr32.exe /s atl.dll  
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
regsvr32.exe /s wuwebv.dll`
5. Type the following and press **Enter** to reset Winsock (Windows Sockets).  
`netsh winsock reset`
6. Copy and paste the following commands one by one and press **Enter** after each to restart the services related to Windows Update.  
`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Close the Command Prompt window and restart your PC to apply the changes. If you're interested in discovering more useful commands, check our guide on the [best Command Prompt commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) for Windows.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Reset the Windows Update Components Using a Batch File

 Another way to reset Windows Update components is to [create and run a batch file in Windows](https://www.makeuseof.com/tag/write-simple-batch-bat-file/). Here are the steps to make one:

1. Press **Win + S** to open the search menu.
2. Type **Notepad** in the search box and press **Enter**.
3. Copy and paste the following command in the Notepad window.  
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
cd /d %windir% system32  
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
4. Click the **File** menu at the top, then **Save as**.  
![Save a Notepad File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/save-a-notepad-file.jpg)
5. Enter **Reset Windows Components.bat** in the name field and specify your preferred location for saving the file.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click the **Save as type** drop-down menu to select **All files**, then click on **Save**.
7. Locate the saved batch file on your PC. Right-click on it and select **Run as administrator** from the context menu.
8. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Reset Windows Update Components Using a Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-windows-update-components-using-a-batch-file.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you've executed the batch file, feel free to keep it around. That way, the next time you encounter problems with Windows Update, you can run the file again without having to repeat the above steps.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reset the Windows Update Components to Fix Problems

 Downloading and installing Windows updates may not always be smooth. In such cases, resetting the Windows Update components can prove effective. However, if that doesn't work, you may have to try your luck with other Windows Update fixes.

 This guide will provide a detailed walkthrough for both methods, allowing you to effectively reset the Windows Update components.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-quick-click-compilation-top-10-fastest-phone-and-pc-apps/"><u>[New] In 2024, Quick Click Compilation Top 10 Fastest Phone & PC Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-photobooth-lags-steadying-the-playback-journey/"><u>[New] Photobooth Lags Steadying the Playback Journey</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-clear-cut-guide-to-high-definition-twitter-videos-for-2024/"><u>[New] The Clear-Cut Guide to High Definition Twitter Videos for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-decoding-the-science-of-hash-optimization-for-game-streaming/"><u>[Updated] 2024 Approved Decoding the Science of Hash Optimization for Game Streaming</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-expert-picks-top-5-high-performing-android-recorders/"><u>[Updated] In 2024, Expert Picks Top 5 High-Performing Android Recorders</u></a></li>
<li><a href="https://win-blog.techidaily.com/diagnosing-and-repairing-launch-failures-in-the-lost-ark-game-update-of-202n-a-comprehensive-guide/"><u>Diagnosing and Repairing Launch Failures in the 'Lost Ark' Game Update of 202N: A Comprehensive Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-15-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password On your iPhone 15</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevate-stories-vibrancy-via-thoughtful-interactive-qandas-for-2024/"><u>Elevate Stories' Vibrancy via Thoughtful Interactive Q&As for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-the-elegance-of-onsite-data-duplication-a-guide-to-local-backups/"><u>Embracing the Elegance of Onsite Data Duplication: A Guide to Local Backups</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-network-protection-with-microsofts-newly-integrated-zero-trust-dns-technology/"><u>Enhancing Windows Network Protection with Microsoft's Newly Integrated Zero Trust DNS Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-your-windows-navigation-with-superior-file-management/"><u>Enhancing Your Windows Navigation with Superior File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/expanded-access-microsoft-now-supports-more-devices-with-windows-11-upgrade/"><u>Expanded Access: Microsoft Now Supports More Devices with Windows 11 Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11-on-arm-a-comprehensive-guide-and-its-differences-from-traditional-windows-systems/"><u>Exploring Windows 11 on ARM: A Comprehensive Guide & Its Differences From Traditional Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-support-for-individuals-and-businesses/"><u>Financial Support for Individuals and Businesses</u></a></li>
<li><a href="https://windows11.techidaily.com/from-doubts-to-discovery-why-the-old-concerns-of-switching-from-windows-to-linux-have-been-disproven/"><u>From Doubts to Discovery: Why the Old Concerns of Switching From Windows to Linux Have Been Disproven</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-started-with-arm-technology-an-unboxing-and-review-of-the-dell-inspiron-14-plus-7441/"><u>Getting Started with ARM Technology: An Unboxing and Review of the Dell Inspiron 14 Plus (7441)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-cybercriminals-exploit-windows-updates-to-bypass-security-fixes/"><u>How Cybercriminals Exploit Windows Updates to Bypass Security Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-realme-11-proplus-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Realme 11 Pro+ | Dr.fone</u></a></li>
</ul></div>

