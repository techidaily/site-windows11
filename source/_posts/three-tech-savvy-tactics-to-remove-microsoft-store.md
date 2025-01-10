---
title: Three Tech-Savvy Tactics to Remove Microsoft Store
date: 2025-01-06T16:35:57.639Z
updated: 2025-01-10T20:29:00.088Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to[remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-how-to-record-console-gameplay-on-computer/"><u>[New] 2024 Approved How to Record Console Gameplay on Computer</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-the-ultimate-compilation-budget-friendly-editing-tools/"><u>[Updated] The Ultimate Compilation Budget-Friendly Editing Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-bite-sized-video-specialist/"><u>2024 Approved Bite-Sized Video Specialist</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723200038887-easy-fix-to-your-pc-cant-project-to-another-screen-error/"><u>Easy Fix to Your PC Can’t Project to Another Screen Error</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ient-tactics-for-viewing-subscribers-on-yt-for-2024/"><u>Efficient Tactics for Viewing Subscribers on YT for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-break-free-from-frozen-dark-ui-settings/"><u>How to Break Free From Frozen Dark UI Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-mouse-clicklock-to-work-easier-on-windows/"><u>How to Enable Mouse ClickLock to Work Easier on Windows</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-hubs-for-finding-googles-ad-sponsors-on-video/"><u>In 2024, Hubs for Finding Google's Ad Sponsors on Video</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-git-workflows-using-github-desktop-in-windows-11/"><u>Navigating Git Workflows Using GitHub Desktop in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-patches-in-an-offline-world/"><u>Navigating Windows Patches in an Offline World</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-frontier-ai-and-its-role-in-windows-11-development/"><u>The New Frontier: AI and Its Role in Windows 11 Development</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-xiaomi-redmi-note-12t-pro-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Xiaomi Redmi Note 12T Pro Device</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0x80072af9-error-on-windows-pcs/"><u>Troubleshooting 0X80072AF9 Error on Windows PCs</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steps-for-rainbow-six-extractions-no-compatible-driver-error/"><u>Troubleshooting Steps for Rainbow Six Extraction's 'No Compatible Driver Error'</u></a></li>
<li><a href="https://win-able.techidaily.com/ultimate-troubleshooting-stop-fifa-21-from-crashing-on-your-computer/"><u>Ultimate Troubleshooting: Stop FIFA 21 From Crashing on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-sync-issues-with-7-innovative-windows-techniques/"><u>Unlocking Sync Issues with 7 Innovative Windows Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-for-automatic-network-proxy-failure-in-windows/"><u>Workaround for Automatic Network Proxy Failure in Windows</u></a></li>
</ul></div>

