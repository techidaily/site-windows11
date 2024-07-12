---
title: Ditching the Default Store on New Windows 11
date: 2024-07-11T22:24:12.113Z
updated: 2024-07-12T22:24:12.113Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ditching the Default Store on New Windows 11
excerpt: This Article Describes Ditching the Default Store on New Windows 11
keywords: Win11 Default Store Removal,Upgraded Windows 11 Shopping Space,Reject Default Marketplace, Embrace Windows 11,New OS,Shunning Built-In Retailers in Win11,Foregoing Original Store on Windows 11,Eliminating Default Shopping From New OS
thumbnail: https://thmb.techidaily.com/700625a34f6d568e2eb348094b74f328e37fece7793c6cce51c25b1680e74f4c.jpg
---

## Ditching the Default Store on New Windows 11

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://windows11.techidaily.com/cyber-armor-top-7-techniques-to-guard-your-os/"><u>Cyber Armor: Top 7 Techniques to Guard Your OS</u></a></li>
<li><a href="https://windows11.techidaily.com/ditch-default-home-port-on-w11-settings-interface/"><u>Ditch Default Home Port on W11 Settings Interface</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fresh-face-finds-budget-friendly-platforms-to-purchase/"><u>[New] In 2024, Fresh Face Finds  Budget-Friendly Platforms to Purchase</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-the-windows-virtualbox-efail-error/"><u>Decoding and Overcoming the Windows Virtualbox E_FAIL Error</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-create-promotional-video/"><u>In 2024, Create Promotional Video</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-ten-step-window-repair-journey/"><u>Decoding the Ten-Step Window Repair Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-windows-screensaver-tactics/"><u>Comprehensive Guide: Windows Screensaver Tactics</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-ditch-windows-10-photos-explore-these-8-amazing-alternatives-for-2024/"><u>Updated Ditch Windows 10 Photos Explore These 8 Amazing Alternatives for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-capturing-instantly-with-iphone-timelapse-techniques/"><u>[New] Capturing Instantly with iPhone Timelapse Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-mastering-audible-content-conversion-into-slide-ready-format-with-powerpoint/"><u>[Updated] Mastering Audible Content Conversion Into Slide-Ready Format with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-windows-pe-file-structure/"><u>Delving Into Windows PE File Structure</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-mastering-fb-free-tools-for-timely-posts/"><u>[New] In 2024, Mastering FB  Free Tools for Timely Posts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-implementing-closed-captions-on-social-video-platforms-snapchat/"><u>[New] 2024 Approved  Implementing Closed Captions on Social Video Platforms (Snapchat)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-detailed-explanation-for-transforming-gender-display-in-instagram-facebook-and-snapchat-pictures-for-2024/"><u>[New] Detailed Explanation for Transforming Gender Display in Instagram, Facebook & Snapchat Pictures for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-perfecting-sound-with-ideal-cam-mics-list/"><u>[New] Perfecting Sound with Ideal Cam Mics List</u></a></li>
<li><a href="https://windows11.techidaily.com/ditching-unnecessary-wallpaper-icon-in-win11/"><u>Ditching Unnecessary Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-auto-triggered-console-crashes-on-windows/"><u>Disabling Auto-Triggered Console Crashes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-costs-not-compromise-top-5-free-media-software/"><u>Cut Costs, Not Compromise: Top 5 Free Media Software</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-vivo-v30-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Vivo V30 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectifying-windows-error-code-0x800704b3/"><u>Comprehensive Guide to Rectifying Windows Error Code 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-windows-11s-no-error-zero-error-flaw-quickly/"><u>Correct Windows 11'S No Error, Zero-Error Flaw Quickly</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unleashing-creativity-secrets-of-unique-yt-short-content/"><u>Unleashing Creativity  Secrets of Unique YT Short Content</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-error-0x80040610-in-microsoft-office-suite/"><u>Decoding and Fixing Error 0X80040610 in Microsoft Office Suite</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-the-ultimate-list-of-windows-movie-maker-alternatives/"><u>2024 Approved The Ultimate List of Windows Movie Maker Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-11-experience-dynamic-wallpapers-guide/"><u>Customize Your Window 11 Experience: Dynamic Wallpapers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/clean-windows-search-interface-no-icons/"><u>Clean Windows Search Interface: No Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-the-top-10-apple-iphone-11-pro-emualtors-for-windows-mac-and-android-drfone-by-drfone-ios/"><u>In 2024, The Top 10 Apple iPhone 11 Pro Emualtors for Windows, Mac and Android | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-aggregatehostexe-its-functionality-and-dangers/"><u>Demystifying Windows' AggregateHost.exe: Its Functionality & Dangers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-unlock-creative-expression-incor-points-on-sharing-gifs-on-snapchat/"><u>[Updated] 2024 Approved  Unlock Creative Expression  Incor Points on Sharing Gifs on Snapchat</u></a></li>
<li><a href="https://windows11.techidaily.com/covertly-masking-taskbars-language-feature-in-win11/"><u>Covertly Masking Taskbar's Language Feature in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/conjoining-android-and-windows-11-tablets-effortlessly/"><u>Conjoining Android and Windows 11 Tablets Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-windows-file-explorer-path-settings/"><u>Customizing Windows File Explorer Path Settings</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/5-inspirational-winter-bgs-to-heat-your-videos-for-2024/"><u>5 Inspirational Winter Bgs to Heat Your Videos for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-answer-to-the-audio-only-chat-space/"><u>Facebook's Answer to the Audio-Only Chat Space</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-starting-out-building-your-youtube-presence-and-earning/"><u>2024 Approved  Starting Out  Building Your YouTube Presence & Earning</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-characteristics-of-exe-and-msi-files/"><u>Distinguishing Characteristics of EXE and MSI Files</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-win11-remote-storage-paths/"><u>Configuring Win11 Remote Storage Paths</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-after-effects-gifs-for-2024/"><u>How to Create After Effects Gifs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-windows-11s-user-identity-framework/"><u>Dissecting Windows 11'S User Identity Framework</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-cutting-edge-pop-playlist-ideal-background-music-for-video-content-creation/"><u>In 2024, Cutting-Edge Pop Playlist Ideal Background Music for Video Content Creation</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-xs-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone XS Max without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-tactics-restoring-windows-11-os-images/"><u>DISM Tactics: Restoring Windows 11 OS Images</u></a></li>
</ul></div>
