---
title: Leveraging Execution Descriptor Labels in Software
date: 2024-08-15T15:44:32.761Z
updated: 2024-08-16T15:44:32.761Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Leveraging Execution Descriptor Labels in Software
excerpt: This Article Describes Leveraging Execution Descriptor Labels in Software
keywords: Exec Desc Labeling,Software SDL Efficiency,Label-Driven Dev Enhance,Improve Code Maintenance,Label Optimization Software,ExecDesk Acceleration Tech,SDL Application Advance
thumbnail: https://thmb.techidaily.com/888d11958fd59cee20dd0880994e49d2be75696460e14e09acd5a7ef9a37fabd.jpg
---

## Leveraging Execution Descriptor Labels in Software

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://youtube-videos.techidaily.com/new-essential-errors-to-dodge-beginner-youtubers-guide/"><u>[New] Essential Errors to Dodge  Beginner YouTuber's Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-decoding-the-process-behind-gopro-burst-recordings/"><u>2024 Approved  Decoding the Process Behind GoPro Burst Recordings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-tips-and-tricks-for-easy-and-effective-xbox-gameplay-capture/"><u>2024 Approved  Tips & Tricks for Easy and Effective Xbox Gameplay Capture</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsoft-copilot-ai-driven-coding-assistant-explained/"><u>Exploring Microsoft Copilot: AI-Driven Coding Assistant Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/fixed-low-frame-rate-issue-with-asus-usb-cam-in-win11/"><u>Fixed Low Frame Rate Issue with Asus USB Cam in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-onedrive-cloud-connection-issues-in-win-1011/"><u>Fixing OneDrive Cloud Connection Issues in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-xbox-game-pass-0x800700e9-error-in-windows-11-os/"><u>Fixing Xbox Game Pass 0X800700E9 Error in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reduce-overhead-from-real-time-scanners/"><u>How to Reduce Overhead From Real-Time Scanners</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-set-or-reset-the-default-terminal-app-on-windows/"><u>How to Set or Reset the Default Terminal App on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-slideshow-and-spot-fix-in-the-windows-11-photos-app/"><u>How to Use Slideshow and Spot Fix in the Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/how-windows-blue-screen-data-assists-diagnosis/"><u>How Windows Blue Screen Data Assists Diagnosis</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-3-easy-steps-for-masterful-image-grading/"><u>In 2024, 3 Easy Steps for Masterful Image Grading</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-15-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On Apple iPhone 15 Online</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-synthesizing-waterway-content-with-impact/"><u>In 2024, Synthesizing Waterway Content with Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-insights-into-activating-windows-11s-wireless-feature/"><u>Instructional Insights Into Activating Windows 11'S Wireless Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/make-your-file-explorer-reliable-fixes-that-work-in-windows-11/"><u>Make Your File Explorer Reliable: Fixes That Work in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/making-oculus-q2-a-compatible-windows-vr-headset/"><u>Making Oculus Q2 a Compatible Windows VR Headset</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-startup-fixes-for-frozen-windows-obs-studio/"><u>Mastering Startup Fixes for Frozen Windows OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-smartly-minimizing-applications-using-ctrlplustab/"><u>Navigate Smartly: Minimizing Applications Using Ctrl+Tab</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-wintoys-essentials-of-a-versatile-windows-utility/"><u>Navigating 'WinToys': Essentials of a Versatile Windows Utility</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-smartwatch-purchases-the-ultimate-5-point-checklist-to-ensure-satisfaction/"><u>Navigating Smartwatch Purchases: The Ultimate 5 Point Checklist to Ensure Satisfaction</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-connectivity-challenges-steam-w11-edition/"><u>Overcoming Connectivity Challenges: Steam W11 Edition</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/l-your-youtube-presence-upwards-by-thousands-for-2024/"><u>Propel Your YouTube Presence Upwards by Thousands for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-system-how-to-reinitialize-windows-11-programs/"><u>Resetting the System: How to Reinitialize Windows 11 Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-smooth-operation-to-windows-timer-tasks/"><u>Restore Smooth Operation to Windows Timer Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-window-cookie-expiry-post-login-errors/"><u>Setting Window' Cookie Expiry Post-Login Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-stopping-bsod-events-with-vmware-on-win11/"><u>Solutions for Stopping BSOD Events with VMware on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-10s-caption-error-correction/"><u>Streamlining Windows 10'S Caption Error Correction</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-off-search-highlight-features-in-windows-11/"><u>Switching Off Search Highlight Features in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-interface-not-recognized-a-win-to-success-guide/"><u>Troubleshoot 'Interface Not Recognized': A Win to Success Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bsod-guide-to-handle-exceptions/"><u>Win11 BSOD Guide to Handle Exceptions</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-speedy-epic-games-installations/"><u>Winning at Speedy Epic Games Installations</u></a></li>
<li><a href="https://windows11.techidaily.com/your-guide-to-developing-an-automatic-voice-to-text-application-for-windows/"><u>Your Guide to Developing an Automatic Voice-to-Text Application for Windows</u></a></li>
</ul></div>
