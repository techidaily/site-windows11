---
title: Three Tech-Savvy Tactics to Remove Microsoft Store
date: 2025-01-26T06:50:25.423Z
updated: 2025-01-29T19:29:28.644Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-the-ultimate-guide-to-earning-through-youtubing-enabling-monetization-on-mobile-devices/"><u>[Updated] 2024 Approved The Ultimate Guide to Earning Through YouTubing Enabling Monetization on Mobile Devices</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-discovering-top-notch-hdr-cameras-an-expedition/"><u>[Updated] Discovering Top-Notch HDR Cameras An Expedition</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-how-to-make-a-fortune-on-reddit-without-experience-top-13-methods/"><u>[Updated] In 2024, How to Make a Fortune on Reddit Without Experience - Top 13 Methods</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-role-of-workspace-dynamics-in-employee-output/"><u>[Updated] In 2024, The Role of Workspace Dynamics in Employee Output</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-masterful-tools-for-youtube-text-extraction-online-for-2024/"><u>[Updated] Masterful Tools for YouTube Text Extraction Online for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/all-you-need-to-know-about-the-upcoming-samsung-galaxy-z-flip-6-cost-and-exclusive-specs/"><u>All You Need to Know About the Upcoming Samsung Galaxy Z Flip 6: Cost and Exclusive Specs!</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortless-huion-h420-functionality-on-windows-os/"><u>Effortless Huion H420 Functionality on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-smartscreen-on-modern-windows-systems/"><u>How to Manage SmartScreen on Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revert-customized-windows-settings-after-reboot/"><u>How to Revert Customized Windows Settings After Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-weather-utilities-for-w10w11/"><u>Ideal Weather Utilities for W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-asana-load-times-on-your-pc/"><u>Improving Asana Load Times on Your PC</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/iphone-guide-to-achieving-stunning-hdr-photos-for-2024/"><u>IPhone Guide to Achieving Stunning HDR Photos for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/lifecast-your-show-a-basic-podcast-streaming-strategy-for-2024/"><u>Lifecast Your Show A Basic Podcast Streaming Strategy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/lifting-the-curtain-on-windows-11s-secret-spotlight/"><u>Lifting the Curtain on Windows 11'S Secret Spotlight</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-pcs-performance-hurdles-for-excel/"><u>Overcome PC's Performance Hurdles for Excel</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-hdcp-limitations-on-your-display-unit-a-guide-to-enhanced-performance/"><u>Overcoming HDCP Limitations on Your Display Unit - A Guide to Enhanced Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/smarter-batch-jobs-utilizing-windows-task-scheduler/"><u>Smarter Batch Jobs: Utilizing Windows Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/the-7-best-note-taking-apps-for-windows-pen-tablet-users/"><u>The 7 Best Note-Taking Apps for Windows Pen Tablet Users</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-experience-top-alternatives-to-default-software/"><u>Upgrade Your Experience: Top Alternatives to Default Software</u></a></li>
</ul></div>

