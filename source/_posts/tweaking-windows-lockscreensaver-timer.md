---
title: Tweaking Windows Lock/Screensaver Timer
date: 2024-08-31T22:12:26.505Z
updated: 2024-09-01T22:12:26.505Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking Windows Lock/Screensaver Timer
excerpt: This Article Describes Tweaking Windows Lock/Screensaver Timer
keywords: Windows Sleep Timer,Screen Saver Timing,Lock Delay Adjustment,Windows Security Shortcuts,Automatic Display Pause,Advanced Lock Settings,Customize Screen Saver Time
thumbnail: https://thmb.techidaily.com/124b72dbf62c2315133422a27b4166aca8de938c7b4431d8ccd93ecf0eac5efe.png
---

## Tweaking Windows Lock/Screensaver Timer

 The Windows lock screen usually displays images when you power on your device or wake it from sleep mode. By default, the lock screen will only appear for about a minute, and then your screen will go blank.

 Meanwhile, the screen saver is an image or animation that appears when your PC has been inactive for a while. Just like the lock screen, the screen saver will also appear for about one minute.

 Wondering how you can display the lock screen or screen saver for longer?

 This article will show you the various ways to change the Windows lock screen and screen saver timeout settings.

## 1\. How to Change the Lock Screen Timeout Settings

 Let’s first take a look at how you can configure the Windows 10 lock screen timeout settings.

### Use the Windows System Settings

 The Windows system settings always come in handy in various situations. Let’s check out how you can use them to change the Windows 10 screen lock timeout settings:

1. Press **Win + I** to open the system settings.
2. Select the **Personalization** option from the menu items.
3. Click the **Lock screen** option on the left-hand side pane.
4. Scroll down on the right-hand side and select the **Screen timeout settings** option.
5. Click the **On battery power** drop-down menu on the right-hand side pane and select your preferred option.

![Using Windows System Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-Windows-System-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

 Apply the same settings for the **When plugged** in option on the right-hand side pane. From there, close the **system settings** and restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
### Use the Edit Plan Settings (via the Control Panel)

 The Control Panel is a reliable Windows tool that helps you configure various system settings. We’ll show you how you can use it to configure the screen saver timeout settings.

 In this case, we’ll use the Control Panel to navigate to the Edit Plan settings.

 Here are the steps you need to follow:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**.
2. Click the **View by** drop-down menu and select **Small icons**.
3. Select **Power Options** from the menu items.
4. Click the **Change plan settings** option on the right-hand side.
5. Locate the **Turn off the display** option. From there, select your preferred options on the **On battery** and **When plugged in** drop-down menus.
6. Finally, click the **Save changes** button.

![Using the Edit Plan Settings to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Edit-Plan-Settings-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
### Use the Advanced Power Options (via the Control Panel)

 You can also use the Control Panel's advanced power settings to configure the lock screen timeout settings.

 Simply follow these steps:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Control Panel** and then press **OK**.
3. Select **Power Options** from the menu items.
4. Click **Change plan settings**. From there, select the **Change advanced power settings** option on the next screen.
5. Scroll down and click the **Display** option. Next, click the **Turn off display after** option.
6. Select the **On battery** option, and then configure the lock screen timeout settings using the **arrow buttons**. From there, apply the same settings for the **Plugged in** option.

![Using the Advanced Power Options to Change the Lock Screen Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Advanced-Power-Options-to-Change-the-Lock-Screen-Timeout-Settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 When you're done, click **Apply** and then click **OK**. Finally, close the **Control Panel** and then restart your device to save these changes.

### Use the Command Prompt

 The Command Prompt is a reliable tool that can help you [troubleshoot various Windows system issues](https://www.makeuseof.com/how-to-troubleshoot-faulty-windows-pc/). Interestingly, this tool can also help you configure the settings on your device.

 Here’s how to configure the Windows lock screen timeout settings [using the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/):

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Next, type the following commands—one at a time—and press **Enter** in each case:

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOIDLE 60

powercfg.exe /setacvalueindex SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 60

 The "**60**" in the command indicates the duration (seconds) in which the lock screen will be displayed. If you want to increase the lock screen duration, apply the previous steps and change "**60**" to a different value of your choice.

 When you finish, type the following command and press **Enter**:

powercfg.exe /SETACTIVE SCHEME_CURRENT

 Finally, restart your PC to save these changes.

## How to Change the Screen Saver Timeout Settings

 Now, let's explore how you can change the screen saver timeout settings.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
### Use the System Settings

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
 Here's how to change the duration of the screen saver using the system settings:

1. Press **Win + I** to open the system settings.
2. Type **screen saver** in the Settings search bar and select the **Change screen saver** option.

 Bear in mind that you can change the screen saver timeout settings only if the screen saver is enabled. If the screen saver is currently disabled, click the **Screen saver** drop-down menu and select your preferred image.

![Enabling the screensaver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Enabling-the-screensaver-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 From there, follow these steps to configure the screen saver timeout settings:

1. Navigate to the **Wait** option on the Screen Saver Settings window.
2. Click the **arrow buttons** to select the screen saver duration (in minutes).

![Using the System Settings to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-System-Settings-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 Finally, press **Apply** and then press **OK** to save these changes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### Use the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is an incredible tool that makes it easy for you to configure various system settings. Now, here's how you can use this tool to configure the screen saver timeout settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates> Control Panel > Personalization**.
4. Double-click the **Screen saver timeout** option on the right-hand side.

![Using the LGPE to Change the Screen Saver Timeout Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-LGPE-to-Change-the-Screen-Saver-Timeout-Settings.jpg)

 In the next window, select the **Enabled** option. From there, use the **arrow buttons** next to the **Seconds** box to select the duration of the screen saver.

 Press **Apply**, press **OK**, and then close the **LGPE**. Finally, restart your device to save these changes.

 If you want to disable the screen saver settings, here are the steps you need to follow:

1. Navigate to the **Personalization** option on the LGPE as per the previous steps.
2. Double-click the **Screen saver timeout** option and select either the **Disabled** or the **Not Configured** option.
3. Finally, press **Apply**, press **OK**, and then close the **LGPE**.

 Still looking for more tips on how to increase screen time on your laptop? We've got one more solution for you!

### Use the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor can help you tweak the screen-saver timeout settings with ease. But it's quite a sensitive tool, so you should consider [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed.

 Now, here's how to configure the screen-saver timeout settings with the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **OK** to open the Registry Editor.
3. Copy-paste the following command into the address bar:

HKEY_USERS\.DEFAULT\Control Panel\Desktop

 Locate the **ScreenSaveTimeOut** option on the right-hand side.

 If the key is missing, right-click on a blank space on the right and select **New > DWORD (32-bit) Value**. From there, rename the value as **ScreenSaveTimeOut** and press **Enter**.

 Next, double-click the **ScreenSaveTimeOut** value.

![Clicking the "ScreenSaveTimeOut" value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-screensavetimeout-value.jpg)

 Now, type the screen saver timeout duration (in seconds) in the **Value data** box. The default option is usually **900** seconds (15 minutes), but you can enter your desired value. Finally, click **OK** and then restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## Tweak Your Lock Screen Timeout Settings Without a Hassle

 Wondering how to increase laptop screen time? Or do you want to lock your PC and ensure that it doesn’t fully go into sleep mode?

 Try increasing the lock screen and screen saver timeout settings using the solutions we’ve covered. From there, you can explore other cool things, such as how to automatically lock your Windows 11 PC when you’re away.


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
<li><a href="https://youtube-videos.techidaily.com/new-enhance-visibility-a-comprehensive-guide-to-video-tagging/"><u>[New] Enhance Visibility  A Comprehensive Guide to Video Tagging</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-snapedit-essentials-for-beginners-a-visual-journey/"><u>2024 Approved  Snapedit Essentials for Beginners  A Visual Journey</u></a></li>
<li><a href="https://article-tips.techidaily.com/discover-best-watermarking-apps-for-images-for-2024/"><u>Discover Best WaterMarking Apps for Images for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-foreign-speech-hotkey-mastery-for-windows-language-switching/"><u>Expedite Foreign Speech: Hotkey Mastery for Windows Language Switching</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-analysis-of-the-mini-pc-revolutionized-into-a-keyboard-the-raspberry-pi-400-review/"><u>Expert Analysis of the Mini PC Revolutionized Into a Keyboard - The Raspberry Pi 400 Review</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-commands-in-action-uncovering-windows-error-messages-using-command-line-knowledge/"><u>Expert Commands in Action: Uncovering Windows Error Messages Using Command Line Knowledge</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-apex-legends-crashing-on-windows-11/"><u>How to Troubleshoot Apex Legends Crashing on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-upgrade-your-photo-edits-the-ultimate-guide-to-pixlr-power/"><u>In 2024, Upgrade Your Photo Edits  The Ultimate Guide to Pixlr Power</u></a></li>
<li><a href="https://windows11.techidaily.com/leading-alternatives-to-procreate-on-windows-platform/"><u>Leading Alternatives to Procreate on Windows Platform</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mac-screenshot-format-reconfiguration-guide-for-2024/"><u>Mac Screenshot Format Reconfiguration Guide for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/masterclass-creating-alluring-vlogging-storylines-for-2024/"><u>Masterclass  Creating Alluring Vlogging Storylines for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-empty-folder-location-and-deletion-in-windows/"><u>Mastering Empty Folder Location and Deletion in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wi-fi-settings-seamless-action-integration-on-microsoft-devices/"><u>Mastering Wi-Fi Settings: Seamless Action Integration on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-error-code-0x80300024-on-a-pc/"><u>Mitigating Error Code: 0X80300024 on a PC</u></a></li>
<li><a href="https://windows11.techidaily.com/rebooting-to-default-power-management-configurations/"><u>Rebooting to Default Power Management Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-operational-issues-with-windows-tablet-stylus/"><u>Rectifying Operational Issues with Windows Tablet Stylus</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-default-settings-for-system-backups-in-windows/"><u>Restoring Default Settings for System Backups in Windows</u></a></li>
<li><a href="https://media-tips.techidaily.com/revamped-interface-dive-into-amazon-prime-videos-updated-app-design/"><u>Revamped Interface: Dive Into Amazon Prime Video's Updated App Design</u></a></li>
<li><a href="https://fix-guide.techidaily.com/solved-warning-camera-failed-on-motorola-edge-40-neo-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Solved Warning Camera Failed on Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-package-could-not-be-registered-errors-in-windows-photos/"><u>Tackling 'Package Could Not Be Registered' Errors in Windows Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frozen-windows-volume-controls/"><u>Tackling Frozen Windows Volume Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-to-unlock-after-hours/"><u>Tailoring Windows To Unlock After Hours</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-technology-troubles-fixing-absentee-tab-functionality/"><u>Taming Technology Troubles: Fixing Absentee Tab Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-disabling-onedrive-on-windows-11s-explore/"><u>Tips for Disabling OneDrive on Windows 11'S Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-and-correcting-utorrent-installation-errors-in-winos/"><u>Troubleshooting and Correcting uTorrent Installation Errors in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-windows-11-logins/"><u>Understanding & Remedying Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woes-unsticking-opera-installation/"><u>Windows Woes: Unsticking Opera Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-powered-disk-cloning-no-add-ons-needed/"><u>Windows-Powered Disk Cloning, No Add-Ons Needed</u></a></li>
</ul></div>
