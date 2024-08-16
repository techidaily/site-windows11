---
title: "Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
date: 2024-08-15T15:57:49.775Z
updated: 2024-08-16T15:57:49.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
excerpt: "This Article Describes Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11"
keywords: Win11 Error Fixing,Windows XP Error Resolution,DirNotFound Error Win11,Empty Folder Alert Win11,Directory Not Found Fix,0X80070091 Error Solution,Win11 File Error Correction
thumbnail: https://thmb.techidaily.com/8c3b13a3ac83a5d3d00093c2a17a7909556b01cc18d6b9abd17e301fcbcbc6e6.jpg
---

## Conquering the Not an Empty Directory Alert (Error Code: 0X80070091) in Win11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-breaking-down-the-secrets-of-impactful-asmr-video-creation/"><u>[New] 2024 Approved  Breaking Down the Secrets of Impactful ASMR Video Creation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-a-journey-through-the-digital-landscape-six-engaging-quizzes-for-every-vlogger-admirer-for-2024/"><u>[New] A Journey Through the Digital Landscape  Six Engaging Quizzes for Every Vlogger Admirer for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-strategies-to-avoid-copyright-strikes-on-youtube-videos/"><u>[New] Strategies to Avoid Copyright Strikes on YouTube Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-fringe-to-mainstream-highlighting-top-10-gender-balanced-youtubers/"><u>[Updated] From Fringe to Mainstream  Highlighting Top 10 Gender-Balanced YouTubers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-insearchofimprovedcameratech-beyond-mycam/"><u>[Updated] In 2024, InSearchOfImprovedCameraTech Beyond MyCam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-uniting-live-stream-tech-a-step-by-step-obs-and-zoom/"><u>[Updated] In 2024, Uniting Live Stream Tech  A Step-by-Step OBS & Zoom</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-adaptive-sharing-techniques-for-igtv-on-fb/"><u>2024 Approved  Adaptive Sharing Techniques for IGTV on FB</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-confronting-cameras-the-face-id-face-unlock-duel/"><u>2024 Approved  Confronting Cameras  The Face ID-Face Unlock Duel</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-inside-out-of-t5-ultimate-sports-and-adventures-recorder/"><u>2024 Approved  Inside Out of T5  Ultimate Sports and Adventures Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-insufficient-access-errors-during-software-removal/"><u>Avoiding Insufficient Access Errors During Software Removal</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-handbook-for-proficient-periscope-use/"><u>Comprehensive Handbook for Proficient Periscope Use</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-secret-to-smoothly-controlling-your-touchpad-in-windows-11/"><u>Discover the Secret to Smoothly Controlling Your Touchpad in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-resolve-bluetooth-pairing-failures-on-windows-1011/"><u>Easily Resolve Bluetooth Pairing Failures on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-out-of-the-eclipse-ending-dark-mode-anomaly/"><u>Easing Out of the Eclipse: Ending Dark Mode Anomaly</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-way-installing-google-play-on-win11/"><u>Easy Way: Installing Google Play on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-methods-to-rename-microsoft-account-on-win11-systems/"><u>Effective Methods to Rename Microsoft Account on Win11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-boost-for-winwms-excessive-graphics-use/"><u>Efficiency Boost for WinWM's Excessive Graphics Use</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-method-to-engagedisengage-bings-taskbar-assist/"><u>Efficient Method to Engage/Disengage Bing's Taskbar Assist</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-ways-to-handle-lunar-client-not-starting-on-pc/"><u>Efficient Ways To Handle Lunar Client Not Starting on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-navigate-your-workflow-essential-command-tips-for-win11/"><u>Efficiently Navigate Your Workflow: Essential Command Tips for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-tailor-dns-settings-for-your-win11-system/"><u>Efficiently Tailor DNS Settings for Your Win11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-usb-prep-for-upgrading-to-windows-11-3-tried-and-true-methods/"><u>Effortless USB Prep for Upgrading to Windows 11: 3 Tried-and-True Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-productivity-the-best-tech-tools-for-success/"><u>Elevate Windows Productivity: The Best Tech Tools for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-visual-experience-increasing-vram-capacity/"><u>Elevate Your Visual Experience: Increasing VRAM Capacity</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-security-controlling-user-biometrics-in-windows-11/"><u>Elevating Security: Controlling User Biometrics in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-overscan-maximizing-screen-real-estate-in-windows/"><u>Eliminate Overscan: Maximizing Screen Real Estate in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-blackout-phenomenon-in-windows-titles/"><u>Eliminating Blackout Phenomenon in Windows Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-common-windows-installer-problems/"><u>Eliminating Common Windows Installer Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-genuineness-errors-in-adobe-windows/"><u>Eliminating Genuineness Errors in Adobe Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steams-content-server-unreachable-problem-in-windows/"><u>Eliminating Steam's Content Server Unreachable Problem in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-voice-typing-glitches-in-windows-11-error-code-0x80049dd3/"><u>Eliminating Voice Typing Glitches in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0xc00000f-in-minutes/"><u>Eliminating Windows Error 0Xc00000f in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0x80072f8f-0x20000/"><u>Eliminating Windows Error: 0X80072f8f-0x20000</u></a></li>
<li><a href="https://windows11.techidaily.com/eluding-eyes-the-art-of-concealing-buttons/"><u>Eluding Eyes: The Art of Concealing Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/embellishing-windows-tray-adding-number-lock-symbols/"><u>Embellishing Windows Tray: Adding Number Lock Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-linguistic-diversity-with-windows-fonts/"><u>Embracing Linguistic Diversity with Windows Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-subnet-configuration-in-win11/"><u>Enhance Your Subnet Configuration in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-memory-capability-for-hogwarts-virtual-learning-experience/"><u>Enhancing Graphics Memory Capability for Hogwarts Virtual Learning Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-analysis-widgets-for-hardware-monitoring/"><u>Enhancing System Analysis: Widgets for Hardware Monitoring</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-in-windows-11/"><u>Enhancing User Experience in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visibility-notifications-for-win11-webcam-use/"><u>Enhancing Visibility: Notifications for Win11 WebCam Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windowed-discords-query-system/"><u>Enhancing Windowed Discord's Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicate-the-windows-1011-requires-privilege-issue-error-0x80070522/"><u>Eradicate the Windows 10/11 Requires Privilege Issue (Error 0X80070522)</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-screen-annoyances-in-sonic-frontiers-on-windows-11/"><u>Eradicating Screen Annoyances in Sonic Frontiers on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/error-busters-for-windows-top-10-must-haves/"><u>Error Busters for Windows: Top 10 Must-Haves</u></a></li>
<li><a href="https://windows11.techidaily.com/error-e8024002e-fixes-for-updated-windows/"><u>Error E:8024002E Fixes for Updated Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-nokia-c12-pro-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Nokia C12 Pro Devices | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-laugh-and-learn-with-animated-youtubers-top-picks-for-today/"><u>In 2024, Laugh and Learn with Animated YouTubers - Top Picks for Today</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-motorola-g24-power-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Motorola G24 Power Phone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-transform-your-pubg-presence-with-new-sounds/"><u>In 2024, Transform Your PUBG Presence with New Sounds</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-role-of-gaming-in-e-commerce-for-2024/"><u>The Role of Gaming in E-Commerce for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-top-8-live-selling-platforms-beginners-tool-tip-for-2024/"><u>Updated Top 8 Live Selling Platforms Beginners Tool Tip for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-motorola-moto-g84-5g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Motorola Moto G84 5G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/win-customer-trust-incorporating-these-20-marketing-expressions/"><u>Win Customer Trust  Incorporating These 20 Marketing Expressions</u></a></li>
</ul></div>
