---
title: Three Tech-Savvy Tactics to Remove Microsoft Store
date: 2024-10-14T23:22:03.252Z
updated: 2024-10-18T23:54:23.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Three Tech-Savvy Tactics to Remove Microsoft Store
excerpt: This Article Describes Three Tech-Savvy Tactics to Remove Microsoft Store
keywords: Microsoft Store Removal,Tech Tips,MSIStore Deletion Guide,Quick Fixes for MS Store Exit,Get Rid of Microsoft Store,Tactics to Uninstall MS Apps,Eliminate MS From PC
thumbnail: https://thmb.techidaily.com/87eef5cf587ac33a0581d68baadab4d33ca4c311a823a65d146f4fbbcbf04745.jpg
---

## Three Tech-Savvy Tactics to Remove Microsoft Store

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902324/19272" target="_top" id="1902324">
  <img src="//a.impactradius-go.com/display-ad/19272-1902324" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902324/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-enhancing-your-instagram-presence-with-long-videos/"><u>[New] In 2024, Enhancing Your Instagram Presence with Long Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-guide-to-whatsapp-audio-chat/"><u>[New] The Ultimate Guide to WhatsApp Audio Chat</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-trimming-footage-for-insta-on-macos/"><u>[Updated] In 2024, Trimming Footage for Insta on macOS</u></a></li>
<li><a href="https://win-blog.techidaily.com/2024-solutions-resolving-cityskylines-game-crashes-effectively/"><u>2024 Solutions: Resolving CitySkylines Game Crashes Effectively</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-updated-broadcom-bluetooth-software-on-windows-versions-11-8-and-7/"><u>How to Install Updated Broadcom Bluetooth Software on Windows Versions 11, 8 and 7</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-error-x80780119-in-windows-image-id/"><u>How To Resolve Error X80780119 in Windows Image ID</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sportswomens-scorecard-poker-analysis/"><u>In 2024, SPORTSWOMEN'S SCORECARD Poker Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-rectifying-windows-11-search-box-malfunctions/"><u>Methods for Rectifying Windows 11 Search Box Malfunctions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-changing-your-windows-11-login-password/"><u>Quick Tips for Changing Your Windows 11 Login Password</u></a></li>
<li><a href="https://windows11.techidaily.com/removing-automatic-system-restarts-in-windows-11/"><u>Removing Automatic System Restarts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/savor-ultimate-digital-windows-world/"><u>Savor Ultimate Digital Windows World</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-roblox-code-403-problem/"><u>Troubleshooting Windows Roblox Code 403 Problem</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-guide-to-overcoming-h100i-v2-driver-conflicts-in-windows-computers/"><u>Ultimate Guide to Overcoming H100i V2 Driver Conflicts in Windows Computers</u></a></li>
</ul></div>

