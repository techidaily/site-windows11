---
title: "Win 11'S Official App: Three Ways to Erase It"
date: 2024-12-12T23:12:00.246Z
updated: 2024-12-16T20:11:56.588Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11'S Official App: Three Ways to Erase It"
excerpt: "This Article Describes Win 11'S Official App: Three Ways to Erase It"
keywords: Win11EraseApp,UninstallWin11,EliminateWin11,RemoveWin11,DeleteWin11Official,UninstallWin11Installed,DisableWin11App
thumbnail: https://thmb.techidaily.com/0fffdaf6b0345d8277ec9fafebd3429c28f703cd8774f81e39bb2cfd9b5790b4.jpg
---

## Win 11'S Official App: Three Ways to Erase It

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-chromeos-top-free-screen-capture-software/"><u>[New] ChromeOS Top Free Screen Capture Software</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-upgrading-laptop-and-mobile-conferencing-with-background-changes/"><u>[New] Upgrading Laptop & Mobile Conferencing With Background Changes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-elevate-your-ears-10-pro-tips-for-excellent-sound-quality/"><u>2024 Approved Elevate Your Ears 10 Pro Tips for Excellent Sound Quality</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensible-list-best-games-music-found-online-for-2024/"><u>Comprehensible List Best Games’ Music Found Online for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/discovering-the-wow-factors-of-the-apple-watch-10-the-three-traits-that-clinched-its-approval-zdnet-insights/"><u>Discovering the Wow Factors of the Apple Watch 10 - The Three Traits that Clinched Its Approval | ZDNET Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-apples-on-device-ai-system-realm-outshines-microsofts-gpt-4-unveiling-the-details/"><u>How Apple's On-Device AI System, ReaLM, Outshines Microsoft's GPT-4: Unveiling the Details</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-capture-the-inspired-moment-essential-photos-for-ig/"><u>In 2024, Capture the Inspired Moment Essential Photos for IG</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-exploring-tools-to-integrate-special-mask-effects-into-your-content-read-the-following-article-to-master-some-tools-experts-in-mask-tracki/"><u>New 2024 Approved Exploring Tools to Integrate Special Mask Effects Into Your Content. Read the Following Article to Master some Tools Experts in Mask Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-storing-error-during-new-app-installation/"><u>Solutions for Storing Error During New App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-stopping-auto-recommended-game-suggestion/"><u>Steps for Stopping Auto-Recommended Game Suggestion</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-separate-bunched-system-icons/"><u>Strategies to Separate Bunched System Icons</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-persistent-computer-mouse-connection-issues/"><u>Ultimate Guide: Resolving Persistent Computer Mouse Connection Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-ftdibussys-the-impact-on-windows-memory-standards-and-safety/"><u>Unraveling ftdibus.sys: The Impact on Windows' Memory Standards and Safety</u></a></li>
</ul></div>

