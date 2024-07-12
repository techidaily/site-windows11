---
title: How to Set Up Troubleshooter Shortcuts in Windows 11 & 11
date: 2024-07-11T21:22:41.289Z
updated: 2024-07-12T21:22:41.289Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Set Up Troubleshooter Shortcuts in Windows 11 & 11
excerpt: This Article Describes How to Set Up Troubleshooter Shortcuts in Windows 11 & 11
keywords: Windows 11 Quick Fixes,W11 Troubleshoot Tips,Windows 11 Accessibility Shortcuts,Windows 11 Easy Repairs,Speed Up Windows 11,Windows 11 Fault Resolution,Customize Windows 11 Fixes
thumbnail: https://thmb.techidaily.com/f0f1add4f06bedd9b4441c0d9e38e221d87204ef26ea2cde0e10ae3ca9b9c9f6.jpg
---

## How to Set Up Troubleshooter Shortcuts in Windows 11 & 11

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
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-online-lyric-video-generators-ranked/"><u>2024 Approved Online Lyric Video Generators Ranked</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-breathe-easy-with-knowledge-of-asmr-advantages/"><u>2024 Approved  Breathe Easy with Knowledge of ASMR Advantages</u></a></li>
<li><a href="https://windows11.techidaily.com/assuring-proper-operation-of-windows-monitor-app/"><u>Assuring Proper Operation of Windows Monitor App</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-streamlined-processes-for-capturing-vimeo-video-files/"><u>[Updated] Streamlined Processes for Capturing Vimeo Video Files</u></a></li>
<li><a href="https://windows11.techidaily.com/best-in-class-window-videomodding-tools-our-top-picks/"><u>Best-in-Class Window Videomodding Tools: Our Top Picks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-social-media-story-scooper/"><u>[New] Social Media Story Scooper</u></a></li>
<li><a href="https://windows11.techidaily.com/calculating-wattage-your-windows-pcs-electricity-needs/"><u>Calculating Wattage: Your Windows PC’s Electricity Needs</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unveil-your-world-in-wide-angle-iosandroid-photo-integration-on-social-media-for-2024/"><u>[Updated] Unveil Your World in Wide Angle  IOS/Android Photo Integration on Social Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-hotspot-offline-error-in-windows-11/"><u>Addressing the Hotspot Offline Error in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-turning-off-your-pc-safely/"><u>Best Practices for Turning Off Your PC Safely</u></a></li>
<li><a href="https://windows11.techidaily.com/briskly-engage-bings-ai-assistant-in-windows-11-search-field/"><u>Briskly Engage Bing's AI Assistant in Windows 11 Search Field</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-iphone-11-pro-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your iPhone 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-license-validity-warning-on-w10-and-w11-systems/"><u>Bypass License Validity Warning on W10 & W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-a-peaceful-state-disable-background-tasks/"><u>Achieving a Peaceful State: Disable Background Tasks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/swing-mastery-kit/"><u>Swing Mastery Kit</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-key-information-on-utilizing-youtubes-sound-bank/"><u>New Key Information on Utilizing YouTubes Sound Bank</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/pioneers-in-online-mastery-meet-up/"><u>Pioneers in Online Mastery Meet-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-alerts-instant-battery-charged-notifications-in-win11/"><u>Boosting Alerts: Instant Battery Charged Notifications in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/6-essential-rotation-tips-for-windows-11-photos/"><u>6 Essential Rotation Tips for Windows 11 Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/a-different-view-unique-changes-to-windows-11s-file-explorer/"><u>A Different View: Unique Changes to Windows 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-windows-technology-for-real-world-use/"><u>Advancing Windows Technology for Real-World Use</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-unstartable-lunar-client-in-windows-issues/"><u>Avoiding Unstartable: Lunar Client in Windows Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-automatic-color-tuning-on-win11-devices/"><u>Activating Automatic Color Tuning on Win11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/5-methods-how-win11-harvests-personal-info/"><u>5 Methods: How Win11 Harvests Personal Info</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-delayed-auditory-feedback-on-pcs/"><u>Addressing Delayed Auditory Feedback on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-vbox-windows-install-with-dependencies/"><u>Boost Your VBox Windows Install with Dependencies</u></a></li>
<li><a href="https://windows11.techidaily.com/bypass-bottlenecks-9-fixes-for-rapid-windows-verification/"><u>Bypass Bottlenecks: 9 Fixes for Rapid Windows Verification</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-service-failed-message-on-windows-disk-management/"><u>Addressing 'Service Failed' Message on Windows Disk Management</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-discover-unlimited-free-emojis-for-your-social-media-chats/"><u>[New] In 2024, Discover Unlimited Free Emojis for Your Social Media Chats</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-pc-utorrent-transfer-rate-windows-edition-guide/"><u>Amplify PC uTorrent Transfer Rate - Windows Edition Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/3-key-fixes-for-sudden-disk-full-situations/"><u>3 Key Fixes for Sudden Disk Full Situations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-achieve-professional-looking-motion-blur-with-just-a-few-steps-in-photoshop/"><u>[New] Achieve Professional-Looking Motion Blur with Just a Few Steps in Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/back-to-basics-windows-11-access-re-establishment-guide/"><u>Back to Basics: Windows 11 Access Re-Establishment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/1719319278608-microsoft-woes-solutions-to-ease-your-way/"><u>Microsoft Woes? Solutions to Ease Your Way</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-windows-file-concordance-with-aoemi-tutorial/"><u>Achieve Windows File Concordance with AOEMi Tutorial</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-mastering-clip-composition-blending-modes-techniques/"><u>2024 Approved  Mastering Clip Composition  Blending Modes Techniques</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-nubia-red-magic-9-pro-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-code-0x887a0006-for-gpu-stalls-windows/"><u>Addressing Code 0X887A0006 for GPU Stalls Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-control-mastering-local-gpo-access-on-windows-11/"><u>Boosting Control: Mastering Local GPO Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adaptive-keystroke-configurations-for-windows-11-users/"><u>Adaptive Keystroke Configurations for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-java-not-installing-a-windows-fixers-manual/"><u>Addressing Java Not Installing: A Windows Fixer's Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-and-grades-essential-study-methods-on-a-windows-pc/"><u>Boost Productivity and Grades: Essential Study Methods on a Windows PC</u></a></li>
</ul></div>
