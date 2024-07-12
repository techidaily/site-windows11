---
title: Disabling Taskbar Time in Windows 11
date: 2024-07-11T22:28:22.051Z
updated: 2024-07-12T22:28:22.051Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Taskbar Time in Windows 11
excerpt: This Article Describes Disabling Taskbar Time in Windows 11
keywords: Disable Taskbar Time,Turn Off Time Bar,Stop Taskbar Clock,Halt Windows Timeline,Eliminate Time Display,Deactivate Clock UI,Remove Taskbar Time
thumbnail: https://thmb.techidaily.com/01781fffdf7ecc74eaf5b3cf4180716493ded8344db51bb91021cea7376b2f5b.jpg
---

## Disabling Taskbar Time in Windows 11

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://windows11.techidaily.com/comprehensive-overview-how-to-optimize-w11s-auto-hdr/"><u>Comprehensive Overview: How to Optimize W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-11s-data-preservation-capabilities/"><u>Delving Into Windows 11'S Data Preservation Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-directdraw-errors-on-win1011/"><u>Decoding and Resolving DirectDraw Errors on WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/design-dilemma-overcoming-unexpected-screen-shades/"><u>Design Dilemma: Overcoming Unexpected Screen Shades</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unveiling-the-finest-free-online-recorders-top-picks/"><u>[New] Unveiling the Finest Free Online Recorders – Top Picks</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-custom-privileges-in-win11-by-default/"><u>Clearing Custom Privileges in Win11 by Default</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/navigating-the-changing-landscape-of-instagram-stories-for-2024/"><u>Navigating the Changing Landscape of Instagram Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-game-storage-integrating-into-the-windows-photos-space/"><u>Classic Game Storage: Integrating Into the Windows Photos Space</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-discover-the-top-tools-to-record-and-share-classroom-content/"><u>[New] Discover the Top Tools to Record and Share Classroom Content</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-your-internet-gateway-in-win-11/"><u>Configuring Your Internet Gateway in Win 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/create-slide-masking-effect-introfilmora-for-2024/"><u>Create Slide Masking Effect Intro【Filmora】 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/command-the-control-of-windows-accessibility-options/"><u>Command the Control of Windows' Accessibility Options</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-code-repaired-windows-family-security-glitches/"><u>Cracking Code: Repaired Windows Family Security Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-old-wallpaper-a-simple-three-step-plan/"><u>Clearing Old Wallpaper - A Simple Three-Step Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-efficient-automation-to-dot-and-ifttt/"><u>Crafting Efficient Automation: To-Dot & IFTTT</u></a></li>
<li><a href="https://windows11.techidaily.com/cursor-on-display-redeeming-darkened-win1011-screens/"><u>Cursor on Display: Redeeming Darkened Win10/11 Screens</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-tech-enhancement-with-top-srt-tweaks/"><u>Elite Tech Enhancement with Top SRT Tweaks</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-and-flexible-the-top-10-online-video-editors-without-watermark-for-2024/"><u>Free and Flexible The Top 10 Online Video Editors without Watermark for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-guide-for-youtube-video-clips/"><u>[Updated] Essential Guide for YouTube Video Clips</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/essential-auditory-enhancers-eliminating-ambient-sounds-effectively-for-2024/"><u>Essential Auditory Enhancers Eliminating Ambient Sounds Effectively for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-6-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-differences-windows-10-meets-windows-11/"><u>Deciphering the Differences: Windows 10 Meets Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-and-resolve-uninitialized-disk-message-on-pc/"><u>Decode and Resolve Uninitialized Disk Message on PC</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/little-tricks-to-create-canva-slideshow-no-one-is-telling-you-for-2024/"><u>Little Tricks to Create Canva Slideshow No One Is Telling You for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-erratic-movement-7-windows-mouse-solutions/"><u>Conquer Erratic Movement: 7 Windows Mouse Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-and-rectifying-windows-steams-error-e84/"><u>Demystifying and Rectifying Windows Steam's Error E84</u></a></li>
<li><a href="https://windows11.techidaily.com/classify-your-hdd-or-ssd-with-ease/"><u>Classify Your HDD or SSD with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/17-best-background-remover-apps-to-remove-image-background-easily-for-2024/"><u>17 Best Background Remover Apps to Remove Image Background Easily for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-facecam-videography-improving-image-quality-and-clarity/"><u>[New] In 2024, Facecam Videography  Improving Image Quality and Clarity</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-lava-without-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Lava Without Password?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-infinix-smart-8-plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-windows-role-in-memory-reservation/"><u>Comprehending Windows' Role in Memory Reservation</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-rectifying-delayed-folder-upload-in-onedrive-without-hitches/"><u>Comprehensive Guide: Rectifying Delayed Folder Upload in OneDrive without Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-to-admin-initiating-windows-11s-task-manager-with-power/"><u>Command Line to Admin: Initiating Windows 11'S Task Manager with Power</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/best-free-video-shrinking-software-for-windows-10-users-for-2024/"><u>Best Free Video Shrinking Software for Windows 10 Users for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-navigating-the-path-to-customized-sound-audacity-for-voice-modification-for-2024/"><u>Updated Navigating the Path to Customized Sound Audacity for Voice Modification for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-downloading-and-setting-up-msixbundle-and-msix-file-types/"><u>Comprehensive Tutorial: Downloading & Setting Up Msixbundle & MSIX File Types</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/professional-photographers-pick-of-edits-for-2024/"><u>Professional Photographers' Pick of Edits for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-honor-90-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Honor 90 Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-the-top-10-apple-iphone-7-plus-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/"><u>In 2024, The Top 10 Apple iPhone 7 Plus Emualtors for Windows, Mac and Android | Dr.fone</u></a></li>
</ul></div>
