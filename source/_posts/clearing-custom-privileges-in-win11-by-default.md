---
title: Clearing Custom Privileges in Win11 by Default
date: 2024-08-08T05:57:33.204Z
updated: 2024-08-09T05:57:33.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Custom Privileges in Win11 by Default
excerpt: This Article Describes Clearing Custom Privileges in Win11 by Default
keywords: Win11 Privilege Management,Clearance Windows 11,Disable Default Permissions,Win11 User Settings,Privilege Reset Win11,Access Control in Win11,Secure Win11 Configurations
thumbnail: https://thmb.techidaily.com/09fee241173a4d75afd314bc2889ac10d1158fd98dc41bc3885e34ece3467540.jpg
---

## Clearing Custom Privileges in Win11 by Default

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
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
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-pure-portrayals-on-platforms-your-guide-to-authentic-snapshots/"><u>[New] 2024 Approved  Pure Portrayals on Platforms  Your Guide to Authentic Snapshots</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-leveraging-social-media-trends-for-fan-growth-on-igtv/"><u>[Updated] 2024 Approved  Leveraging Social Media Trends for Fan Growth on IGTV</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-magical-sound-alteration-apps-for-your-device/"><u>2024 Approved  Magical Sound Alteration Apps for Your Device</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-google-pixel-fold-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Google Pixel Fold to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-chromes-non-downloading-problems-on-windows/"><u>Addressing Chrome's Non-Downloading Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-organization-controlled-errors-in-windows-11-systems/"><u>Addressing Organization-Controlled Errors in Windows 11 Systems</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/best-8k-tvs-detailed-comparison/"><u>Best 8K TVs [Detailed Comparison ]</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-apex-crashes-effective-solutions-for-windows-11-users/"><u>Combat Apex Crashes: Effective Solutions for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-winoss-priority-setting-for-hardware-acceleration/"><u>Controlling WinOS's Priority Setting for Hardware Acceleration</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/descobrindo-o-portugues-saudacoes-para-todos-os-tempos/"><u>Descobrindo O Português: Saudações Para Todos Os Tempos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/drifting-visions-slick-cam-insights/"><u>Drifting Visions  Slick Cam Insights</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/evaluating-the-benefits-of-moving-to-ios-17-what-users-need-to-know/"><u>Evaluating the Benefits of Moving to iOS 17: What Users Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inoperative-drive-not-detected-by-os/"><u>Fixing Inoperative Drive Not Detected by OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-sluggish-excel-experience/"><u>Fixing Windows' Sluggish Excel Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-fixing-nvidia-gui-sharing-glitches/"><u>Guide for Fixing NVIDIA GUI Sharing Glitches</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-c51-by-fonelab-android-recover-music/"><u>How to retrieve erased music from C51</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-a60s-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel A60s to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-apple-iphone-13-mini-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your Apple iPhone 13 mini Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://ai-topics.techidaily.com/in-2024-a-detailed-and-trustworthy-review-of-murfai-ai-text-to-speech-tool/"><u>In 2024, A Detailed and Trustworthy Review of Murf.ai AI Text-to-Speech Tool</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/ios-champions-best-ps2-emulation-programs-for-2024/"><u>IOS Champions  Best PS2 Emulation Programs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-tasks-effortlessly-top-8-pomodoro-timer-reviews-on-pc/"><u>Mastering Tasks Effortlessly - Top 8 Pomodoro Timer Reviews on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-usage-settings-on-windows-11-your-how-to-guide/"><u>Navigating Usage Settings on Windows 11: Your How-To Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-window-management-embrace-adaptive-wmlayouts/"><u>Redefine Window Management: Embrace Adaptive WMLayouts</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-your-window-11-drag-functionality/"><u>Restore Your Window 11 Drag Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-avoiding-frequent-sign-ins-on-ms-teams-platform/"><u>Solutions for Avoiding Frequent Sign-Ins on MS Teams Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-no-device-camera-error-in-win11/"><u>Steps to Solve No Device: Camera Error in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/tailor-your-text-experience-openais-gpt-custom-shops/"><u>Tailor Your Text Experience – OpenAI's GPT Custom Shops</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-user-accounts-to-local-groups-policy-in-windows-11-and-11/"><u>Tailoring User Accounts to Local Groups Policy in Windows 11 & 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-sound-changes-in-ps-console-games/"><u>The Ultimate Guide to Sound Changes in PS Console Games</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-tweaking-mouse-speeds-in-win-1011/"><u>The Ultimate Guide to Tweaking Mouse Speeds in Win 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-poco-x6-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Poco X6 Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-spotify-on-windows-11/"><u>Troubleshooting Unresponsive Spotify on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-activated-mastery-in-windows-11s-accessibility-features/"><u>Voice-Activated Mastery in Windows 11'S Accessibility Features</u></a></li>
<li><a href="https://windows11.techidaily.com/1719346558796-why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software!</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-vigilance-understanding-and-monitoring-device-uptime/"><u>Windows 11 Vigilance: Understanding and Monitoring Device Uptime</u></a></li>
</ul></div>
