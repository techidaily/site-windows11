---
title: Quick Access to Troubleshooters in Windows 11 with Custom Keys
date: 2024-07-11T22:08:05.614Z
updated: 2024-07-12T22:08:05.614Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Access to Troubleshooters in Windows 11 with Custom Keys
excerpt: This Article Describes Quick Access to Troubleshooters in Windows 11 with Custom Keys
keywords: Windows Troubleshoot Tool,Quick Fix Window,Custom Key Troubleshooting,Win11 Access Tools,Easy Windows Repair,Troubleshooters Shortcut,Custom Fix Keys Windows
thumbnail: https://thmb.techidaily.com/b9d202f17312addc4751b6c7718b8073b057f0ff78d7cca6ec165bfb76c8c4ca.jpg
---

## Quick Access to Troubleshooters in Windows 11 with Custom Keys

 Windows 11 and 10 include various troubleshooting tools you can open via Settings and the Control Panel. There are troubleshooters for fixing Bluetooth, internet, Windows Update, audio, hardware, printer, video, and MS Store app-related errors that arise. Those troubleshooters detect issues and either automatically apply or suggest potential fixes to resolve them.

 Adding troubleshooter shortcuts to Windows 11/10 will save you from rummaging through Settings or the Control Panel whenever you need to access them. You can create troubleshooter shortcuts on the Windows 11/10 desktop, taskbar, Start menu, and even context menu with the methods below.

## How to a Set Up a Desktop Shortcut for Opening the Troubleshooting Applet

 Most users probably go through Settings to bring up troubleshooters. However, Control Panel’s Troubleshooting applet includes more troubleshooters than the Settings app. Adding a [desktop shortcut](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for opening the applet will enable you to access all troubleshooters included within it more quickly.

 You can create a Troubleshooting shortcut on the Windows desktop in the following steps:

1. Right-click any part of the desktop area and select**New** .
2. Click the**Shortcut** option on the**New** submenu.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-option.jpg)
3. Input**explorer shell:::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}** inside the location box, and select the Create Shortcut wizard’s**Next** option.  
![The Create Shortcut window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-shortcut-window.jpg)
4. Erase the default shortcut title, and type**Troubleshooting Applet** in the text box.
5. Select**Finish** to add the Troubleshooting Applet desktop shortcut.  
![The Troubleshooting Applet desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooting-applet-shortcut.jpg)

 Double-click the new desktop shortcut you just added to open the Troubleshooting applet. There you can click**Programs** ,**Hardware and Sound** ,**Network and Internet** , or**System and Security** to view and access different categories of troubleshooters. Alternatively, select**View all** open to bring up a full list of troubleshooters. You can click any troubleshooter there to open it.

![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-troubleshooting-applet.jpg)

 The Troubleshooting shortcut will have the same folder library icon as Explorer’s taskbar button. If you would prefer something else, you can change the icon via the shortcut’s properties window. Check out our guide about [how to customize icons on Windows](https://www.makeuseof.com/tag/customize-icon-windows/) for details.

## How to Set Up Taskbar and Start Menu Troubleshooting Shortcuts

 You can easily convert the Troubleshooting Applet desktop shortcut into a taskbar or Start menu one. To do so in Windows 11, click the Troubleshooting Applet shortcut with the right mouse button and select**Show more options** . Select**Pin to taskbar** on the classic menu to stick the same shortcut on the taskbar. Or click**Pin to Start** to have one for opening the Troubleshooting applet from the pinned area of the Start menu.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pin-to-taskbar-option.jpg)

 Then you may as well remove the desktop shortcut if a taskbar or Start menu one is preferred. Right-click Troubleshooting Applet to select**Delete** (the trash bin icon in Windows 11).

## How to Set Up a Troubleshooting Hotkey

 A Troubleshooting desktop shortcut can also become a convenient hotkey in a few quick steps. All you have to do is set a key combination for activating the desktop shortcut. Then you can open the Troubleshooting applet by pressing a**Ctrl** +**Alt** key combo. These are the steps for setting up a hotkey that opens the Troubleshooting applet:

1. Create a desktop shortcut for opening the Troubleshooting applet as outlined in the first method.
2. Right-click the Troubleshooting shortcut and select**Properties** .
3. Click inside the box labeled**Shortcut key** .
4. Press**T** (for troubleshooting) to establish a**Ctrl** +**Alt** +**T** key combination.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-key-option.jpg)
5. Select**Apply** to save your new troubleshooting hotkey.
6. Click**OK** or**X** to close the Shortcut tab and window.

 Now you can access the Troubleshooting applet with a key combo. Press**Ctrl** +**Alt** +**T** to open that applet and access its troubleshooters. That hotkey depends on the desktop shortcut you set it for. So, you’ve got to leave the shortcut on the desktop.

## How to Set Up Shortcuts for Opening Specific Troubleshooters

 You can also set up shortcuts for opening any specific troubleshooters included within the Troubleshooting Control Panel applet. Each troubleshooter there has a pack ID with which you can set up a desktop shortcut for opening it. You can set up a troubleshooter shortcut in such a way via the Create Shortcut wizard with the following command:

`msdt.exe /id <diagnostic_id>`

 The above command must include an actual diagnostic\_id for the troubleshooter. This [MSDT page](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/ee424379%28v=ws.10%29?redirectedfrom=MSDN) has a list of troubleshooting pack IDs you can include in that command. These are the diagnostic ID commands for some of the more useful troubleshooters:

`msdt.exe /id WindowsUpdateDiagnostic  
  
msdt.exe /id SearchDiagnostic  
  
msdt.exe /id DeviceDiagnostic  
  
msdt.exe /id PrinterDiagnostic  
  
msdt.exe /id NetworkDiagnosticsWeb  
  
msdt.exe /id AudioPlaybackDiagnostic`

 You can set up a desktop shortcut for a specific troubleshooter much the same as the Troubleshooting applet. Go through the same steps in this guide’s instructions for setting up a desktop shortcut, but input a troubleshooter diagnostic ID command at step three instead. Enter a different name for the shortcut in step four, and select the**Finish** option.

![The Windows Update troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-command.jpg)

 Double-clicking that desktop shortcut will open whatever troubleshooter you set it to with the diagnostic ID command. Then you can also pin that desktop shortcut to the taskbar or Start menu just the same as the Troubleshooting applet one. Or set up a hotkey for opening the troubleshooting tool as outlined in this guide’s keyboard shortcut instructions.

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-and-shortcut.jpg)

## How to Add a Troubleshooters Submenu to the Context Menu

 The right-click context menu is another place you can add Troubleshooting shortcuts in Windows 11/10\. You can set up a**Troubleshooters** submenu on the Windows 11/10 context menu that includes shortcuts for opening different parts of the Troubleshooting applet. To do that, you only need to download and run a premade registry script like this:

1. Open the [Add Troubleshooters Context Menu Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Add-Troubleshooters-Context-Menu-in-Windows-10.shtml) .
2. Select that registry script’s**Download Now** option.
3. Click the**Secure Download (US)** option.
4. Go into File Explorer (press**Win** +**E** to open), and bring up the directory containing the registry script’s ZIP archive.  
![The Extract Compressed Folders tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extract-compressed-folder-tool.jpg)
5. Select to extract the troubleshooters-context-menu.zip archive. Our guide to [unzipping ZIP files on Windows](https://www.makeuseof.com/unzip-files-windows-10/) includes instructions for extracting these archives.
6. Open the extracted troubleshooters-context-menu folder.
7. Double-click the**Add Troubleshooters To Desktop Context Menu.reg** file.  
![The troubleshooters-context-menu folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-context-menu-folder.jpg)
8. Click**Yes** on the prompt that asks for user confirmation to apply the script.

 You will now see a new**Troubleshooters** submenu on your desktop’s context menu. Right-click any space within the desktop wallpaper area and select**Show more options** on Windows 11’s context menu. Move the cursor over the**Troubleshooters** submenu to view its shortcuts.

![The Troubleshooters submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-option.jpg)

 There you can select**Classic Troubleshooting applet** to bring up the Troubleshooting home screen in the Control Panel. Select**All Categories** to open the full list of troubleshooters. Or click**Programs** ,**Hardware and Sound** ,**Network and Internet** , and**System Security** to view category pages for opening troubleshooters.

 The troubleshooters-context-menu folder also includes a script for removing the Troubleshooters submenu. Double-click**Remove Troubleshooters From Desktop Context Menu.reg** in that folder to run that script. Then select**Yes** to erase the submenu from the context menu.

## Make Some Shortcuts for Accessing Troubleshooters in Windows

 So, now you can create Windows shortcuts for opening the Troubleshooting applet and more specific troubleshooters in various ways. You can create a general Troubleshooting Control Panel desktop, taskbar, keyboard, or context menu shortcut for accessing all troubleshooting tools. Or set up shortcuts that give you more direct access to the specific troubleshooting tools you utilize more regularly.

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
<li><a href="https://windows11.techidaily.com/a-primer-to-installation-of-the-java-sdkjdk-on-windows-11/"><u>A Primer to Installation of the Java SDK/JDK on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Lava Yuva 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-videos-for-twitter-success-expert-convertors-guide/"><u>2024 Approved  Transforming Videos for Twitter Success  Expert Convertors Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/green-screen-mastery-seamless-yt-integration-for-2024/"><u>Green Screen Mastery  Seamless YT Integration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-reconnecting-legrl-after-drops/"><u>Bridging the Gap: Reconnecting LeGRL After Drops</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-soon-to-end-windows-license-issues/"><u>Avoidance of Soon-to-End Windows License Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-firewall-restriction-chrome-connectivity-solution/"><u>Circumventing Firewall Restriction: Chrome Connectivity Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/asus-vivobook-s-15-the-ultimate-blend-of-style-and-functionality/"><u>ASUS Vivobook S 15: The Ultimate Blend of Style & Functionality</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-elevate-video-quality-mastering-fb-1080p-streams/"><u>[Updated] In 2024, Elevate Video Quality  Mastering FB 1080P Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/1719359377017-unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-itel-p55t-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Itel P55T FRP In 3 Different Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/5-secure-operating-system-tactics-when-bitlocker-is-offline/"><u>5 Secure Operating System Tactics When BitLocker Is Offline</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-vivo-t2-5g-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Vivo T2 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/a-fresh-window-on-computers-after-windows-11/"><u>A Fresh Window on Computers: After Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-profit-with-windows-11-pro-capture-best-offers/"><u>Accelerate Profit with Windows 11 Pro: Capture Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-login-blockers-with-these-8-steps/"><u>Bypassing Windows Login Blockers with These 8 Steps</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-rhythm-revolution-top-20-easy-to-learn-dance-beats/"><u>[Updated] 2024 Approved  Rhythm Revolution  Top 20 Easy-to-Learn Dance Beats</u></a></li>
<li><a href="https://windows11.techidaily.com/audible-overdrive-best-5-programs-for-higher-than-100-pc-audio/"><u>Audible Overdrive: Best 5 Programs for Higher-Than-100%% PC Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-why-files-cant-sync-in-steam-library/"><u>Addressing Why Files Can't Sync in Steam Library</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-nubia-red-magic-9-proplus-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Nubia Red Magic 9 Pro+ FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-gpsvc-wait-issue-on-pcs/"><u>Bypassing the GPSVC Wait Issue on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-navigating-file-explorer-tabs-windows-11-style/"><u>A User's Guide to Navigating File Explorer Tabs, Windows 11 Style</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-lava-yuva-3-pro-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Lava Yuva 3 Pro FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-user-not-valid-issues-in-windows-11-and-11/"><u>Bypassing 'User Not Valid' Issues in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/augmenting-your-window-11-with-these-6-pioneering-android-apps/"><u>Augmenting Your Window 11 with These 6 Pioneering Android Apps</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-elite-story-creation-centers-avoiding-the-ordinary-top-8-for-2024/"><u>[Updated] Elite Story Creation Centers – Avoiding the Ordinary (Top 8) for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-apple-iphone-12-pro-max-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>How To Fix Apple iPhone 12 Pro Max Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-black-background-on-windows-calculator/"><u>Adopting a Black Background on Windows Calculator</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fully-functional-laptop-gpu-in-windows-11/"><u>Fully Functional: Laptop GPU in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-spontaneous-windows-11-lockups-and-shuts/"><u>Avoid Spontaneous Windows 11 Lockups & Shuts</u></a></li>
</ul></div>
