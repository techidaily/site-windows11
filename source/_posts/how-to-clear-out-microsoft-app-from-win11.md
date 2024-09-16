---
title: How to Clear Out Microsoft App From Win11
date: 2024-09-11T17:28:16.527Z
updated: 2024-09-15T19:29:17.108Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Clear Out Microsoft App From Win11
excerpt: This Article Describes How to Clear Out Microsoft App From Win11
keywords: Windows 11 Remove MSFT Apps,Uninstall Microsoft Apps Win11,Remove Microsoft Software Win11,Get Rid of MS Office Win11,Eliminate MS Office From Win11,Delete Microsoft Windows 11 Apps,Clear Windows 11 MSFT Programs
thumbnail: https://thmb.techidaily.com/5a6b81e19407a604be22bf69df443b0f8b7b5bc4d3841b542775d6677ac13b8e.jpg
---

## How to Clear Out Microsoft App From Win11

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-friendly.techidaily.com/new-mirthful-mastery-no-monetary-boundaries-for-2024/"><u>[New] Mirthful Mastery, No Monetary Boundaries for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-pioneering-the-digital-universe-the-present-and-future-landscape/"><u>[New] Pioneering the Digital Universe The Present & Future Landscape</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-best-online-no-download-gif-conversion-services-reviewed/"><u>2024 Approved Best Online No-Download GIF Conversion Services Reviewed</u></a></li>
<li><a href="https://solve-popular.techidaily.com/abbeyy-news-update-viele-europaer-verbringen-die-meiste-zeit-mit-abgelehnten-tatigkeiten-im-arbeitsalltag-eine-weite-sichtbarkeit/"><u>ABBEYY News Update: Viele Europäer Verbringen Die Meiste Zeit Mit Abgelehnten Tätigkeiten Im Arbeitsalltag - Eine Weite Sichtbarkeit</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-on-your-iphone-15-plus-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID On your iPhone 15 Plus without Security Questions?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-into-productivity-windows-11s-multiple-folder-creation-tricks/"><u>Leap Into Productivity: Windows 11'S Multiple Folder Creation Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-barriers-to-installing-games-from-the-microsoft-hub/"><u>Overcoming Barriers to Installing Games From the Microsoft Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/pinpointing-your-pcs-drive-type-with-windows/"><u>Pinpointing Your PC's Drive Type with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresponsive-windows-11-activation-codes/"><u>Resolving Unresponsive Windows 11 Activation Codes</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Xiaomi Mix Fold 3? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/symbolizing-sound-designing-a-captivating-podcast-image/"><u>Symbolizing Sound Designing a Captivating Podcast Image</u></a></li>
<li><a href="https://windows11.techidaily.com/the-artisans-guide-enteringleaving-focus-state-in-the-window-terminal/"><u>The Artisan's Guide: Entering/Leaving Focus State in the Window Terminal</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-10-historical-youtube-hubs-essential-viewing-for-students-and-enthusiasts/"><u>Top 10 Historical YouTube Hubs Essential Viewing For Students & Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-permissions-violation-during-setup/"><u>Troubleshooting Windows Permissions Violation During Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-resurrecting-old-folder-tools/"><u>Windows 11: Resurrecting Old Folder Tools</u></a></li>
</ul></div>

