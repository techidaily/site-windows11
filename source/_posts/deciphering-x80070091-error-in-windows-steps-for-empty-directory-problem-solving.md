---
title: Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving
date: 2024-08-08T05:56:02.857Z
updated: 2024-08-09T05:56:02.857Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving
excerpt: This Article Describes Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving
keywords: WinX80070091Error,EmptyDirErrorSolve,FixX80070091Fail,X80070091WindowsFix,OvercomingEmptyDirectory,WindowsX80070091Trouble,ResolveX80070091Error
thumbnail: https://thmb.techidaily.com/6391f80929a44e71d1cec19d1806bcb918554d022df1dd84ca222ff30839f7f0.jpg
---

## Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-videos.techidaily.com/new-best-movie-swaps-top-7-alternate-films/"><u>[New] Best Movie Swaps  Top 7 Alternate Films</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-proven-strategies-for-device-screening/"><u>[New] In 2024, Proven Strategies for Device Screening</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-youtubes-commercial-free-chrome-firefox-android-and-iphone-tips/"><u>[New] In 2024, YouTube's Commercial Free  Chrome, Firefox, Android & iPhone Tips</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-top-30-nicknames-that-leave-a-lasting-impression/"><u>[New] Top 30 Nicknames That Leave a Lasting Impression</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-transform-your-set-design-top-8-sites-providing-free-green-screen-footage-and-backdrop/"><u>[New] Transform Your Set Design  Top 8 Sites Providing Free Green Screen Footage & Backdrop</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-step-by-step-guide-for-easy-macbook-air-recordings/"><u>[Updated] 2024 Approved  Step-by-Step Guide for Easy Macbook Air Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-straightforward-screen-capture-app-win10-edition/"><u>[Updated] 2024 Approved  Straightforward Screen Capture App, Win10 Edition</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-unlock-iphones-full-potential-4-pro-tips-for-brightening-hdr-in-premiere/"><u>[Updated] 2024 Approved  Unlock iPhone's Full Potential  4 Pro Tips for Brightening HDR in Premiere</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-path-to-precision-audio-starting-with-an-adobe-auditions-fade-in/"><u>[Updated] The Path to Precision Audio  Starting with an Adobe Audition's Fade In</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-downloadable-instagram-footage-tech-tips-for-computers-and-macs/"><u>2024 Approved  Downloadable Instagram Footage  Tech Tips for Computers & Macs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-ultimate-obs-tutorial-for-youtube-and-twitch-broadcasts/"><u>2024 Approved  The Ultimate OBS Tutorial for YouTube & Twitch Broadcasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/affordable-action-camera-choices-top-6-under-100-for-2024/"><u>Affordable ACTION Camera Choices – Top 6 Under $100 for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-infinix-smart-7-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Infinix Smart 7? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-explorer-exploration-shun-common-pitfalls/"><u>Efficient Explorer Exploration: Shun Common Pitfalls</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-connectivity-expert-instructions-for-dns-configuration/"><u>Elevate Connectivity: Expert Instructions for DNS Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-execution-shortcuts-for-microsoft-project-success/"><u>Elevate Your Execution: Shortcuts for Microsoft Project Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-language-input-with-customized-keyboard-options-in-win-11/"><u>Elevate Your Language Input with Customized Keyboard Options in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-poorly-performing-ccleaner-in-win11/"><u>Elevating Poorly Performing CCleaner in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-touch-sensitivity-experience-on-a-windows-laptop/"><u>Elevating Your Touch Sensitivity Experience on a Windows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-windows-screenshot-game-with-these-fixes/"><u>Elevating Your Windows Screenshot Game with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-random-shutdowns-on-windows-11-pcs/"><u>Eliminate Random Shutdowns on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-yellow-tint-on-windows-lcd-monitor/"><u>Eliminate Yellow Tint on Windows LCD Monitor</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-barriers-to-successful-printer-use/"><u>Eliminating Barriers to Successful Printer Use</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-functional-behavior-of-ccleaner-in-windows/"><u>Eliminating Non-Functional Behavior of CCleaner in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elite-compilation-prime-windows-systems-for-nds-simulation/"><u>Elite Compilation: Prime Windows Systems for NDS Simulation</u></a></li>
<li><a href="https://windows11.techidaily.com/empowered-scripting-in-windows-mastering-execution-policies/"><u>Empowered Scripting in Windows: Mastering Execution Policies</u></a></li>
<li><a href="https://windows11.techidaily.com/empowering-windows-users-with-access-to-apples-imessage/"><u>Empowering Windows Users with Access to Apple's iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-creativity-ranking-the-best-drawers-for-win-11/"><u>Enhance Creativity: Ranking the Best Drawers for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-taskbar-clarity-separate-groups-on-win-11/"><u>Enhance Taskbar Clarity: Separate Groups on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-experience-selecting-top-free-car-upgraders/"><u>Enhance Windows Experience: Selecting Top Free Car Upgraders</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-efficiency-microsoft-adds-artificial-intelligence-to-windows-11-taskbar/"><u>Enhancing Efficiency: Microsoft Adds Artificial Intelligence to Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-note-visibility-with-windows-tools/"><u>Enhancing Note Visibility with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-with-virtual-memory-on-windows-11/"><u>Enhancing Performance with Virtual Memory on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-pointer-visibility-on-win11/"><u>Enhancing Pointer Visibility on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wi-fi-setup-accuracy-ensuring-complete-actions/"><u>Enhancing Wi-Fi Setup Accuracy: Ensuring Complete Actions</u></a></li>
<li><a href="https://fox-access.techidaily.com/essential-20-anime-opener-anthems-for-2024/"><u>Essential 20 Anime Opener Anthems for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-game-picks-ghost-of-tsushima-rival-edition-for-2024/"><u>Essential Game Picks  Ghost of Tsushima Rival Edition for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expert-tips-for-a-seamless-google-podcast-upload-experience-for-2024/"><u>Expert Tips for a Seamless Google Podcast Upload Experience for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y55s-5g-2023-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y55s 5G (2023) in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-xiaomi-redmi-note-12-4g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Xiaomi Redmi Note 12 4G Is Unlocked</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-your-vivo-y55s-5g-2023-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Vivo Y55s 5G (2023) Lock Screen Password</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-the-modern-gamers-guide-understanding-the-latest-on-bandicam/"><u>In 2024, The Modern Gamer's Guide  Understanding the Latest on Bandicam</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/violating-copyrights-in-video-posting-what-are-the-consequences-in-2024/"><u>Violating Copyrights in Video Posting  What Are the Consequences, In 2024</u></a></li>
</ul></div>
