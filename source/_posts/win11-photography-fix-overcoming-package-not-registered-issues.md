---
title: "Win11 Photography Fix: Overcoming Package Not Registered Issues"
date: 2024-06-25T12:06:18.509Z
updated: 2024-06-26T12:06:18.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Photography Fix: Overcoming Package Not Registered Issues"
excerpt: "This Article Describes Win11 Photography Fix: Overcoming Package Not Registered Issues"
keywords: Win11 Photo Fix,Win11 Registration Issue,Photoshop Package Error,Win11 Image Updater,Win11 Camera Fix,Win11 Software Update,Win11 Packaging Troubleshooting
thumbnail: https://thmb.techidaily.com/3d4f10ff7575c64862599f681c5c76c2a7860b5686d5a4ad72e83eea7dc08de2.jpg
---

## Win11 Photography Fix: Overcoming Package Not Registered Issues

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
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-restoring-light-from-dark-mode/"><u>Troubleshooting Steps: Restoring Light From Dark Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incorrect-parameters-leading-to-loadlibrary-failure/"><u>Fixing Incorrect Parameters Leading to LoadLibrary Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win-11-issue-resolution/"><u>Mastering the Art of WIN 11 Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-reset-of-windows-icon-positions/"><u>Swift Reset of Windows Icon Positions</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-11-audio-adjustment-tools/"><u>Unveiling the Windows 11 Audio Adjustment Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-vimeo-video-profile-aspect-ratio-specified/"><u>Updated In 2024, Vimeo Video Profile Aspect Ratio Specified</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-from-basics-to-brilliance-the-fb-cover-video-journey/"><u>In 2024, From Basics to Brilliance  The FB Cover Video Journey</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-apples-finest-video-editing-software-for-creative-pros/"><u>New 2024 Approved Apples Finest Video Editing Software for Creative Pros</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-cutting-edge-methods-for-fast-srt-to-text-file-conversion/"><u>[Updated] Cutting-Edge Methods for Fast SRT to Text File Conversion</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-hidefake-snapchat-location-on-your-honor-x9a-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Honor X9a | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-bringing-your-outdoor-experiences-home-gopro-livestreams-on-facebookperiscope-for-2024/"><u>[New] Bringing Your Outdoor Experiences Home  GoPro Livestreams on Facebook/Periscope for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-step-by-step-macootd-tiktok-creation-process-for-2024/"><u>[Updated] Step by Step  MacOOTD TikTok Creation Process for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-a-brief-guide-to-download-install-and-use-ez-grabber-for-2024/"><u>[Updated] A Brief Guide to Download, Install, and Use EZ Grabber for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-tecno-phantom-v-flip-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Tecno Phantom V Flip Location by Number | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-game-on-top-10-gaming-personalities-on-tiktok/"><u>[Updated] Game On  Top 10 Gaming Personalities on TikTok</u></a></li>
</ul></div>
