---
title: "Quick Start: Enabling and Customizing Sandbox in Win 11"
date: 2024-08-27T16:12:13.856Z
updated: 2024-08-28T16:12:13.856Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Start: Enabling and Customizing Sandbox in Win 11"
excerpt: "This Article Describes Quick Start: Enabling and Customizing Sandbox in Win 11"
keywords: Win 11 Sandbox Setup,Win 11 Sandbox Config,Sandbox Customization Win,Quick Sandbox Enablement,Windows Sandbox Tutorial,Win 11 Sandbox Use,Win 11 Secure Playground
thumbnail: https://thmb.techidaily.com/eb4342f3aa6f1684d24f86318d0e954640b0c7c9aedf2dd2ccacfdac421d6e8a.jpg
---

## Quick Start: Enabling and Customizing Sandbox in Win 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

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
 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-slicephoto-inspection/"><u>[New] 2024 Approved  SlicePhoto Inspection</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-advanced-hue-adjustment-strategies-for-professionals/"><u>[New] Advanced Hue Adjustment Strategies for Professionals</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pioneering-collage-apps-for-an-android-aesthetic/"><u>[New] Pioneering Collage Apps for an Android Aesthetic</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-step-by-step-techniques-for-convincing-reddit-readers-for-2024/"><u>[New] Step-By-Step Techniques for Convincing Reddit Readers for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-essential-steps-to-design-impressive-facebook-slideshows/"><u>[Updated] 2024 Approved  Essential Steps to Design Impressive Facebook Slideshows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-a-quick-guide-downloading-fb-videos-on-multiple-oses/"><u>[Updated] In 2024, A Quick Guide  Downloading FB Videos on Multiple OSes</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-the-comprehensive-guide-to-youtube-playlists-creation/"><u>[Updated] In 2024, The Comprehensive Guide to YouTube Playlists Creation</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-youtube-comeback-kid-jake-pauls-story/"><u>[Updated] The YouTube Comeback Kid  Jake Paul’s Story</u></a></li>
<li><a href="https://solve-helper.techidaily.com/1-digitale-transformation-mit-von-fraunhofer-und-abbeyy-geheime-schritte-in-das-neue-norm/"><u>1. Digitale Transformation Mit Von Fraunhofer Und ABBEYY - Geheime Schritte in Das Neue 'Norm'</u></a></li>
<li><a href="https://windows11.techidaily.com/affordable-studiolight-kit-for-creatives/"><u>Affordable StudioLight Kit for Creatives</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/be-the-trendsetter-with-these-exclusive-tiktok-fonts-for-2024/"><u>Be the Trendsetter with These Exclusive TikTok Fonts for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-hot-40i-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Hot 40i</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhancing-your-creative-vision-iphones-new-camera-tools/"><u>Enhancing Your Creative Vision  IPhone's New Camera Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://video-capture.techidaily.com/essential-guide-to-preserving-screen-chats-for-2024/"><u>Essential Guide to Preserving Screen Chats for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-avoid-auto-snip-from-prtscreen-keypress-in-11-windows/"><u>How to Avoid Auto-Snip From PrtScreen Keypress in 11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-execute-the-windows-startup-check/"><u>How to Execute the Windows Startup Check</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-problems-caused-by-a-windows-update/"><u>How to Fix Problems Caused by a Windows Update</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-reno-9a-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Oppo Reno 9A Phone with Broken Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-y27-4g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo Y27 4G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y27-4g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y27 4G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-nord-n30-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock OnePlus Nord N30 5G Phone Without Password?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-the-iphone-8-plus-sim-lock-4-easy-methods-by-drfone-ios/"><u>In 2024, How To Unlock The iPhone 8 Plus SIM Lock 4 Easy Methods</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-xiaomi-redmi-note-12-4g-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Xiaomi Redmi Note 12 4G Phones</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/insightful-analysis-the-dji-inspire-2-story-for-2024/"><u>Insightful Analysis - The DJI Inspire 2 Story for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ring-quick-subtitleclosed-caption-integration-on-youtube-for-2024/"><u>Mastering Quick Subtitle/Closed Caption Integration on YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-irreversible-deletion-setting-up-your-windows-desktop-trash/"><u>Mastering the Art of Irreversible Deletion: Setting up Your Windows Desktop Trash</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-art-of-document-conversion-from-word-docs-to-win-11-pdf/"><u>Navigating the Art of Document Conversion From Word Docs to Win 11 PDF</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-netstat-to-monitor-tcpip-activity/"><u>Navigating Windows 11 Netstat to Monitor TCP/IP Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/offline-mode-mastery-for-windows-users-on-onedrive/"><u>Offline Mode Mastery for Windows Users on OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win11s-installer-lacks-permissions-issue/"><u>Overcoming Win11's Installer Lacks Permissions Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-battery-status-enabling-full-charge-alerts-in-windows-11/"><u>Proactive Battery Status: Enabling Full Charge Alerts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-onedrive-x-error-code-sign-in-woes-on-windows-11/"><u>Quick Fixes for OneDrive X-Error Code: Sign In Woes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-non-responsive-spotify-error-on-pcs-with-windows/"><u>Rectifying Non-Responsive Spotify Error on PCs with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normalcy-notepad-on-windows-recovery/"><u>Restoring Normalcy: Notepad on Windows Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-workflow-management-microsofts-ai-companion-on-windows-11-taskbar/"><u>Revolutionizing Workflow Management: Microsoft's AI Companion on Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/scripting-folder-actions-for-modern-windows-users/"><u>Scripting Folder Actions for Modern Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-denied-login-issues-in-windows-with-easy-fixes/"><u>Sidestep Denied Login Issues in Windows with Easy Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/sony-s6500-review-latest-improvements-for-2024/"><u>Sony S6500 Review  Latest Improvements for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-reconnecting-disconnected-printer-on-windows/"><u>Steps for Reconnecting Disconnected Printer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthening-windows-11-enhanced-mobile-accessibility/"><u>Strengthening Windows 11: Enhanced Mobile Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-steps-to-pinpoint-your-pcs-graphics-model-in-win11/"><u>Swift Steps to Pinpoint Your PC's Graphics Model in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-in-use-status-on-network-resources-in-windows-11/"><u>Tackling 'In-Use' Status on Network Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-usb-non-attachment-problems-in-virtualbox-on-your-pc/"><u>Tackling USB Non-Attachment Problems in VirtualBox on Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-essentials-of-rectifying-page-not-found-404-online-issues/"><u>The Essentials of Rectifying 'Page Not Found' (404) Online Issues</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/tips-for-posting-wide-angle-photos-to-facebook-from-smartphones/"><u>Tips for Posting Wide Angle Photos to Facebook From Smartphones</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshoot-and-fix-nba-2k23-pc-crashes-top-7-reliable-methods-uncovered/"><u>Troubleshoot and Fix NBA 2K23 PC Crashes - Top 7 Reliable Methods Uncovered!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/troubleshooting-a-nonfunctional-bluetooth-mouse-in-arch-after-updating-to-windows-10-creators-edition/"><u>Troubleshooting a Nonfunctional Bluetooth Mouse in Arch After Updating to Windows 10 Creators Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winerror-0x8009030e-in-hyper-v-setup/"><u>Troubleshooting WinError 0X8009030E in Hyper-V Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-task-mastery-administrative-run-in-task-manager-on-win11/"><u>Unlocking Full Task Mastery: Administrative Run in Task Manager on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-hides-in-ftdibussys-windows-memory-integrity-disruption/"><u>What Hides in ftdibus.sys: Windows' Memory Integrity Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-guide-nullify-local-account-security-prompts/"><u>Win 11 Guide: Nullify Local Account Security Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tips-disabling-unwanted-mouse-speed-boosting/"><u>Win 11 Tips: Disabling Unwanted Mouse Speed Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-10-home-enabling-administrator-access/"><u>Win11 & 10 Home: Enabling Administrator Access</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/winheadset-mic-malfunctions-resolution-steps/"><u>WinHeadset Mic Malfunctions: Resolution Steps</u></a></li>
</ul></div>
