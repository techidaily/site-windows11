---
title: Restoring Microsoft Store Programs on Windows 10/11 Systems
date: 2024-06-25T12:04:09.888Z
updated: 2024-06-26T12:04:09.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
excerpt: This Article Describes Restoring Microsoft Store Programs on Windows 10/11 Systems
keywords: Win10 Restore MS Store,Reinstalling MS Store,Fix MS Store Error,Repair MS Store Access,Regain Windows Store Functionality,Update Microsoft Apps,Maintain Microsoft Store Compatibility
thumbnail: https://thmb.techidaily.com/605743c45d46920946cf620896ea214cdef6126e457144d63179eeaf5994b016.jpg
---

## Restoring Microsoft Store Programs on Windows 10/11 Systems

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-a-polished-w11-workspace/"><u>Quick Fixes for a Polished W11 Workspace</u></a></li>
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-application-of-ping-for-optimal-pc-performance/"><u>Strategic Application of Ping for Optimal PC Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-disk-management-in-context-menus-for-win-11/"><u>Visual Disk Management in Context Menus for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-favorites-windows-11-shortcuts-for-uwp-apps/"><u>Fast-Track Favorites: Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-10-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-notepad-on-win11-through-ai-wisdom/"><u>Transform Notepad on Win11 Through AI Wisdom</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-misentered-characters-in-windows-os/"><u>Dealing with Misentered Characters in Windows OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-top-apps-for-instagram-strategy-mastery-and-expansion/"><u>[Updated] In 2024, Top Apps for Instagram Strategy Mastery and Expansion</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-the-art-of-defeating-youtube-short-issues/"><u>In 2024, Mastering the Art of Defeating YouTube Short Issues</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-best-online-photo-and-video-collage-makers/"><u>New 2024 Approved Best Online Photo and Video Collage Makers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-cutting-edge-simulators-for-sonys-playstation-3-games-pc/"><u>2024 Approved  Cutting-Edge Simulators for Sony's PlayStation 3 Games (PC)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-step-by-step-guide-incorporating-tunes-into-instagram-reels/"><u>2024 Approved  Step-by-Step Guide  Incorporating Tunes Into Instagram Reels</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-gionee-f3-pro-lock-screen-password-by-drfone-android/"><u>How to Reset your Gionee F3 Pro Lock Screen Password</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-expert-advice-on-editing-away-backgrounds-for-2024/"><u>[Updated] Expert Advice on Editing Away Backgrounds for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-comedy-in-catchy-notes-best-parody-songs-list/"><u>[Updated] 2024 Approved  Comedy in Catchy Notes  Best Parody Songs List</u></a></li>
</ul></div>
