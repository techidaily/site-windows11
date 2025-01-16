---
title: Ditching the Default Store on New Windows 11
date: 2025-01-14T17:53:57.919Z
updated: 2025-01-16T11:21:53.341Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-information.techidaily.com/new-acoustic-architects-leading-sites-to-buy-skype-tones/"><u>[New] Acoustic Architects Leading Sites to Buy Skype Tones</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-hourly-video-consumption-total-daily-gb-amount/"><u>[New] Hourly Video Consumption Total Daily GB Amount</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-from-content-creator-to-brand-ambassador-unlocking-instagram-sponsorship/"><u>[New] In 2024, From Content Creator to Brand Ambassador Unlocking Instagram Sponsorship</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-seamless-youtube-experience-facebooks-autoplay-solution/"><u>[New] Seamless YouTube Experience Facebook's Autoplay Solution</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-joke-jamboree-twitters-10-best-comedy-threads/"><u>[Updated] Joke Jamboree Twitter's 10 Best Comedy Threads</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-routine-for-large-files-journey-from-iphones-to-macs/"><u>2024 Approved The Ultimate Routine for Large Files' Journey From iPhones to Macs</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/automated-marketing-with-cutting-edge-cookiebot-technology/"><u>Automated Marketing with Cutting-Edge Cookiebot Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-flow-effective-win11-disk-management/"><u>Mastering File Flow: Effective Win11 Disk Management</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-friend-connect-fixes-for-win11s-steam/"><u>Mastering Friend Connect Fixes for Win11's Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-volume-mixer-windows-11-sounds-configuration-steps/"><u>Mastering the Volume Mixer: Windows 11 Sounds Configuration Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-file-archives-cli-mastery-in-windows/"><u>Navigating File Archives: CLI Mastery in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-defaults-in-win11-command-prompt/"><u>Reclaiming Defaults in Win11 Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-windows-task-execution-via-enhanced-run-toolkit-implementation/"><u>Reimagine Windows Task Execution via Enhanced Run Toolkit Implementation</u></a></li>
</ul></div>

