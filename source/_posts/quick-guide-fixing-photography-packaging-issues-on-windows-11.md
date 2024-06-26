---
title: "Quick Guide: Fixing Photography Packaging Issues on Windows 11"
date: 2024-06-25T11:56:00.227Z
updated: 2024-06-26T11:56:00.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Fixing Photography Packaging Issues on Windows 11"
excerpt: "This Article Describes Quick Guide: Fixing Photography Packaging Issues on Windows 11"
keywords: Photo Packaging Troubleshoot,Window 11 Packaging Help,Photography Shipping Tips,Winpack Solutions Guide,W11 Fixing Photog Packs,Quick Windows 11 Fixes,Photo Box Issues
thumbnail: https://thmb.techidaily.com/80d3fa767f44fdaa6b3c03730260a31e590107858e011b7c1ceac58f39d7b6f4.jpg
---

## Quick Guide: Fixing Photography Packaging Issues on Windows 11

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://windows11.techidaily.com/1719278005537-mastery-of-solutions-for-non-operational-wwinplusp-in-pc/"><u>Mastery of Solutions for Non-Operational WWin+P in PC.</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-preserves-7-ancient-features-for-modern-use/"><u>Windows 11 Preserves 7 Ancient Features for Modern Use</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-pixel-panorama-themed-displays-for-each-window-of-win-1011/"><u>Personalized Pixel Panorama: Themed Displays for Each Window of WIN 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/breaching-windows-denied-logins-with-smart-fixes/"><u>Breaching Windows' Denied Logins with Smart Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-speed-and-efficiency-windows-shortcuts-for-uwp/"><u>Unleash Speed and Efficiency: Windows Shortcuts for UWP</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-user-folder-names-on-windows-11/"><u>Altering User Folder Names on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-error-code-0x80300024/"><u>Understanding and Remedying Error Code: 0X80300024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-voice-over-made-easy-final-cut-pro-tips-and-tricks-for-beginners/"><u>2024 Approved Voice Over Made Easy Final Cut Pro Tips and Tricks for Beginners</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-unleash-your-creativity-10-free-whiteboard-animation-tools-for-windows-and-mac/"><u>Updated 2024 Approved Unleash Your Creativity 10 Free Whiteboard Animation Tools for Windows and Mac</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-magic-5-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor Magic 5 Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-gaming-youtubers-you-may-want-to-subscribe/"><u>In 2024, Top 10 Gaming YouTubers You May Want to Subscribe</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-installation-and-registration-for-2024/"><u>New Installation and Registration for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-premium-free-digital-audio-stitching-platforms-compared/"><u>In 2024, Premium Free Digital Audio Stitching Platforms Compared</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-conversational-courtesies-react-and-engage-on-discord-platforms/"><u>[New] 2024 Approved  Conversational Courtesies  React and Engage on Discord Platforms</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-multi-screen-video-streaming-with-microsoft-edges-pip/"><u>[New] Master Multi-Screen Video Streaming with Microsoft Edge's PIP</u></a></li>
</ul></div>
