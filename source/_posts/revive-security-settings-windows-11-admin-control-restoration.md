---
title: "Revive Security Settings: Windows 11 Admin Control Restoration"
date: 2024-08-22T21:40:07.261Z
updated: 2024-08-23T21:40:07.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Security Settings: Windows 11 Admin Control Restoration"
excerpt: "This Article Describes Revive Security Settings: Windows 11 Admin Control Restoration"
keywords: Win11 Security Revival,Admin Control Recovery,Windows Setup Reset,Security Restore Proc,Admin Settings Fix,System Guard Reinstate,Windows Safeguard Refresh
thumbnail: https://thmb.techidaily.com/1734faea8dc6fb99b0356fb7510aa58c46806122f440ead1dafd4f608890d169.png
---

## Revive Security Settings: Windows 11 Admin Control Restoration

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-detailed-insights-into-instagrams-video-time-policy/"><u>[New] 2024 Approved  Detailed Insights Into Instagram’s Video Time Policy</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-essential-techniques-for-mac-based-ootd-tiktok-videos/"><u>[New] Essential Techniques for Mac-Based OOTD TikTok Videos</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-bring-your-vision-to-life-youtube-trailers-using-filmoras-magic/"><u>[New] In 2024, Bring Your Vision to Life  YouTube Trailers Using Filmora's Magic</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-user-friendly-instructions-installing-snapchat-on-macos/"><u>[New] In 2024, User-Friendly Instructions  Installing Snapchat on macOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-leading-edge-approaches-in-spotifys-advertising-realm/"><u>[New] Leading Edge Approaches in Spotify's Advertising Realm</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-snap-edit-share-your-initial-guide-to-lunapic/"><u>[Updated] 2024 Approved  Snap, Edit, Share  Your Initial Guide to LunaPic</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-how-to-transcribe-live-broadcasts-into-digital-format/"><u>2024 Approved  How to Transcribe Live Broadcasts Into Digital Format</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/assessing-the-pros-and-cons-of-lgs-usb-type-c-monitors-for-2024/"><u>Assessing the Pros and Cons of LG's USB Type-C Monitors for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/discover-the-power-of-personalized-vocal-effects-in-tiktok-videos/"><u>Discover the Power of Personalized Vocal Effects in TikTok Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/eight-outstanding-choices-for-private-video-communication/"><u>Eight Outstanding Choices for Private Video Communication</u></a></li>
<li><a href="https://win-blog.techidaily.com/eliminate-pc-game-crashes-in-cult-of-the-lamb-with-these-easy-repairs/"><u>Eliminate PC Game Crashes in Cult of The Lamb with These Easy Repairs</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-missing-sd-card-resolution-guide/"><u>File Explorer Missing SD Card: Resolution Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-voice-typing-malfunction-error-code-0x80049dd3-on-windows-11/"><u>Fixing Voice Typing Malfunction (Error Code: 0X80049DD3) on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-cr2-to-jpg-on-windows-a-comprehensive-conversion-guide/"><u>From CR2 to JPG on Windows: A Comprehensive Conversion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-showhide-directories-on-modern-windows-11-pcs/"><u>Guide to Show/Hide Directories on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-error-code-0xc00000f-with-ease-on-pcs/"><u>Handling Error Code 0xC00000F with Ease on PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-itel-p55plus-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Itel P55+? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-plain-out-windows-edges/"><u>How to Plain Out Windows Edges</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-a78-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Oppo A78 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/1716169029054-in-2024-how-to-get-more-instagram-video-views/"><u>In 2024, How to Get More Instagram Video Views?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-honor-x50iplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Honor X50i+? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-imageryinfluence-mastering-size-settings-on-instagram/"><u>In 2024, ImageryInfluence  Mastering Size Settings on Instagram</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-instant-sticker-transformation-your-guide-to-making-gifs-pop-in-telegram-and-more/"><u>In 2024, Instant Sticker Transformation  Your Guide to Making GIFs Pop in Telegram & More</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-gioneefrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your GioneeFRP Lock</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-the-ultimate-list-of-the-best-video-call-recording-equipment/"><u>In 2024, The Ultimate List of the Best Video Call Recording Equipment</u></a></li>
<li><a href="https://win-answers.techidaily.com/instantly-improve-your-slow-chrome-browser-with-simple-tweaks/"><u>Instantly Improve Your Slow Chrome Browser with Simple Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-dns-client-service-in-windows-11-with-precision/"><u>Integrating DNS Client Service in Windows 11 with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/iphoneandroid-your-smartphone-as-a-windows-microphone/"><u>IPhone/Android: Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-image-spin-6-tactics-for-windows-11/"><u>Mastering Image Spin: 6 Tactics for Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/mastering-light-and-shadow-with-iphone-xs-new-lens-technology-for-2024/"><u>Mastering Light & Shadow with iPhone X's New Lens Technology for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-quick-start-for-rdc-on-windows-11/"><u>Mastering the Art of Quick Start for RDC on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-to-inspecting-windows-11-history/"><u>Mastery Guide to Inspecting Windows 11 History</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-file-history-setting-glitch-in-windows-os/"><u>Mending File History Setting Glitch in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-local-gpo-on-windows-with-ease/"><u>Navigating Local GPO on Windows with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-diagnosis-navigating-through-windows-error-messages-with-command-line-skills/"><u>Precision in Diagnosis: Navigating Through Windows Error Messages with Command Line Skills</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/premium-mac-capture-software-substitutes-for-bandicam-for-2024/"><u>Premium Mac Capture Software Substitutes for Bandicam for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-error-x8019-on-windows-xp/"><u>Preventing Error X8019 on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-discords-loading-failures-in-windows/"><u>Resolving Discord's Loading Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-functional-activation-in-os-11/"><u>Resolving Non-Functional Activation in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-and-restore-key-applications-for-changing-createdmodified-dates/"><u>Rewind and Restore: Key Applications for Changing Created/Modified Dates</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-win11s-notepad-with-astute-mentor/"><u>Supercharge Win11's Notepad with Astute Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-non-registered-hdds/"><u>Techniques to Rectify Non-Registered HDDs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-for-proper-thx-surround-sound/"><u>Troubleshooting Windows for Proper THX Surround Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-windows-key-like-a-pro/"><u>Turn On/Off Windows Key Like a Pro</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/uncover-tech-secrets-the-ultimate-guide-by-toms-hardware/"><u>Uncover Tech Secrets: The Ultimate Guide by Tom's Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-7-key-windows-11-widgets-for-enhanced-productivity/"><u>Unveiling 7 Key Windows 11 Widgets for Enhanced Productivity</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-the-best-ps5-and-xbox-gaming-monitors-for-2024/"><u>Unveiling the Best PS5 & Xbox Gaming Monitors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/visualizing-disks-wisely-the-windows-methodology/"><u>Visualizing Disks Wisely: The Windows Methodology</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-winservicesexe-insights-for-windows-users/"><u>What Is WinServices.exe? Insights for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/wingetui-masterclass-enhancing-windows-11s-application-handling/"><u>WingetUI Masterclass: Enhancing Windows 11'S Application Handling</u></a></li>
</ul></div>
