---
title: "Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
date: 2024-08-15T15:56:15.129Z
updated: 2024-08-16T15:56:15.129Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
excerpt: "This Article Describes Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11"
keywords: Win11 Directory Error Prevention,Empty Folder Fix Error 0X80070091,Stop Non-Empty Dir Alert in Windows,Error Code 0X80070091 Solutions,Avoiding Win11 Directory Failure,Correcting Empty Folder Issue,Preventing Directory Errors Windows 11
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Preventing Non-Empty Directory Alert (Error Code: 0X80070091) in Windows 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://youtube-web.techidaily.com/024-approved-master-class-the-7-cutting-edge-apps-for-youtube-live-on-iphonesandroid-os/"><u>[New] 2024 Approved  Master Class  The 7 Cutting-Edge Apps for YouTube LIVE on iPhones/Android OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-breaking-barriers-with-brightness-the-comprehensive-guide-to-the-lg-31mu97-b-screen/"><u>[New] Breaking Barriers with Brightness – The Comprehensive Guide to the LG 31MU97-B Screen</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-discreet-route-to-disengage-from-discord-networks/"><u>[New] The Discreet Route to Disengage From Discord Networks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-youtube-equipment-for-beginners-ultimate-guide/"><u>[Updated] 2024 Approved  YouTube Equipment for Beginners [Ultimate Guide]</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unveiling-the-ultimate-iphone-selfie-sticks-8/"><u>2024 Approved  Unveiling the Ultimate IPhone Selfie Sticks (#8)</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-win11-taskbar-icon-dimensions/"><u>Adjusting Win11 Taskbar Icon Dimensions</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-finding-out-charge-status-win-1011/"><u>Advanced Techniques: Finding Out Charge Status (Win 10/11)</u></a></li>
<li><a href="https://windows11.techidaily.com/battle-of-the-packagers-chocolatey-or-wm-on-windows-pcs/"><u>Battle of the Packagers: Chocolatey or WM on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-grayed-screen-savers-quick-fixes-for-windows-users/"><u>Curing Grayed Screen Savers: Quick Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723017000966-effortless-audio-inspection-the-definitive-method-to-test-microphones-on-the-go/"><u>Effortless Audio Inspection: The Definitive Method to Test Microphones on the Go</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-0x800f0845-failure/"><u>How to Address 0X800f0845 Failure</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-13-mini-to-android-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 13 mini To Android devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oppo-find-x7-ultra-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Oppo Find X7 Ultra</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Vivo</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-finest-5-android-image-boosters/"><u>In 2024, The Finest 5 Android Image Boosters</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-storage-with-onedrive-rearrange-for-win-11/"><u>Managing Storage with OneDrive – Rearrange for Win 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/mastering-widgets-the-fast-fixes-you-need-to-know-for-iphone-and-ipad-woes/"><u>Mastering Widgets: The Fast Fixes You Need to Know for iPhone & iPad Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-solo-sound-output-in-windows-audio-device/"><u>Mending Solo Sound Output in Windows Audio Device</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-windows-update-notifications/"><u>Muting Windows Update Notifications</u></a></li>
<li><a href="https://extra-information.techidaily.com/navigating-camera-settings-for-optimal-gopro-timelapse-results/"><u>Navigating Camera Settings for Optimal GoPro Timelapse Results</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-computer-no-need-for-windows-11-upgrades/"><u>Optimize Your Computer: No Need for Windows 11 Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-chromes-file-uploading-frustrations-on-a-pc/"><u>Overcome Chrome's File Uploading Frustrations on a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-and-fixing-lost-steam-games-symbols/"><u>Preventing and Fixing Lost Steam Games Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-connection-issues-with-googles-nearby-sharing/"><u>Resolving Connection Issues with Google's Nearby Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-microsofts-phone-tethering-for-windows-11-users/"><u>Revisiting Microsoft's Phone Tethering for Windows 11 Users</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/software-requirements-defied-installing-intell-graphics/"><u>Software Requirements Defied: Installing Intell Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-wows-abrupt-server-quit-error-132-in-win11/"><u>Solutions for WoW's Abrupt Server Quit (Error 132) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-common-issues-with-windows-shared-printers/"><u>Solving Common Issues with Windows Shared Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/stealth-mode-disabling-windows-wi-fi-broadcast/"><u>Stealth Mode: Disabling Windows Wi-Fi Broadcast</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-correcting-malwarebytes-call-failure-in-win11win10/"><u>Steps for Correcting Malwarebytes Call Failure in Win11/Win10</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-absent-app-in-windows-filesystem/"><u>Strategies to Fix Absent App in Windows Filesystem</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-the-setup-of-new-non-operational-store-programs/"><u>Streamlining the Setup of New, Non-Operational Store Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-aid-for-windows-issues-in-googles-nearby-share-app/"><u>Tactical Aid for Windows Issues in Google's Nearby Share App</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/trustworthy-tactics-growing-your-youtube-channel-by-a-million-steps-for-2024/"><u>Trustworthy Tactics  Growing Your YouTube Channel by a Million Steps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-nearby-share-for-file-transfers/"><u>Understanding Nearby Share for File Transfers</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-for-optimal-clipchamp-functionality/"><u>Unlocking Windows 11 for Optimal ClipChamp Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://change-location.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Samsung Galaxy A54 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/your-pathway-to-instagram-stardom-top-video-strategies-for-2024/"><u>Your Pathway to Instagram Stardom  Top Video Strategies for 2024</u></a></li>
</ul></div>
