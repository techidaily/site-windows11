---
title: Three Steps for Ditching Microsoft's Store
date: 2024-06-25T11:58:51.982Z
updated: 2024-06-26T11:58:51.982Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Steps for Ditching Microsoft's Store
excerpt: This Article Describes Three Steps for Ditching Microsoft's Store
keywords: Eject Microsoft Store,Quit Windows Shop,Escape MS Marketplace,Leave Microsoft Outlet,Drop Microsoft Hub,Steer Clear MSCore,Avoid Microsoft Apps
thumbnail: https://thmb.techidaily.com/81ce373281fd9aff14dae5d82f0fff51572cdd8c291988609733f2ca1401739f.jpg
---

## Three Steps for Ditching Microsoft's Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

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
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-google-chrome-to-full-color-in-windows/"><u>Restoring Google Chrome to Full Color in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-windows-update-failure-at-error-0xca00a009/"><u>Remedy for Windows Update Failure at Error 0xCA00A009</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-different-ways-to-restart-your-windows-computer/"><u>The 8 Different Ways to Restart Your Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-xbox-mic-issues-on-windows-1111-pro/"><u>Resolving Xbox Mic Issues on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/biometric-betrayal-how-secure-is-your-windows-hello-lock/"><u>Biometric Betrayal: How Secure Is Your Windows Hello Lock?</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-your-window-11-drag-functionality/"><u>Restore Your Window 11 Drag Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-multi-task-abilities-efficiently/"><u>Navigating Windows 11'S Multi-Task Abilities Efficiently</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-apex-legends-mastery-exploring-single-platform-potential-for-2024/"><u>[Updated] Apex Legends Mastery  Exploring Single Platform Potential for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/rewind-to-glory-with-top-5-pc-ps1-emulation-tools/"><u>Rewind to Glory with Top 5 PC PS1 Emulation Tools</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-huawei-nova-y71-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Huawei Nova Y71 Device</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-digital-diaries-blending-visuals-with-audio-threads/"><u>[New] In 2024, Digital Diaries  Blending Visuals with Audio Threads</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-exploring-instagrams-max-video-length/"><u>[Updated] In 2024, Exploring Instagram's Max Video Length</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-propel-your-productivity-mastering-marketing-in-the-telegram-world/"><u>[New] Propel Your Productivity  Mastering Marketing in the Telegram World</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-how-to-use-luts-to-color-grade-on-your-iphone/"><u>2024 Approved How to Use LUTS to Color Grade on Your iPhone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-analyzing-lack-of-interaction-is-it-a-block/"><u>[New] 2024 Approved  Analyzing Lack of Interaction  Is It a Block?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-facebook-video-cover-design-secrets-for-maximum-impact/"><u>New 2024 Approved Facebook Video Cover Design Secrets for Maximum Impact</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-how-to-stream-on-twitch-the-ultimate-guide/"><u>Updated In 2024, How to Stream on Twitch The Ultimate Guide</u></a></li>
</ul></div>
