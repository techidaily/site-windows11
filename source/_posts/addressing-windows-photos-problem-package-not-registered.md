---
title: Addressing Windows Photos Problem - Package Not Registered
date: 2024-07-03T11:18:06.611Z
updated: 2024-07-04T11:18:06.611Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Photos Problem - Package Not Registered
excerpt: This Article Describes Addressing Windows Photos Problem - Package Not Registered
keywords: Photo Error Fix Windows,Unregistered Photo Issue,Windows Photos Troubleshoot,Resolve Photo Packaging,Correct Photos Package Error,Photo Registration Solve,Fix Photos Not Registering
thumbnail: https://thmb.techidaily.com/6471b67acfe8051c9c2c5b701d3d154a93913c9b510e1febb60299ae780985b8.jpg
---

## Addressing Windows Photos Problem - Package Not Registered

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

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
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

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

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
<li><a href="https://windows11.techidaily.com/a-simple-guide-for-correcting-lsassexe-issue/"><u>A Simple Guide for Correcting 'lsass.exe' Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-offline-microsoft-onedrive-file-management/"><u>Guide to Offline Microsoft OneDrive File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/debunking-myths-the-necessity-and-risks-of-pagefilesys/"><u>Debunking Myths: The Necessity and Risks of Pagefile.sys</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-preparations-for-revitalizing-your-pc-with-windows/"><u>Essential Preparations for Revitalizing Your PC with Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-restoring-the-lost-enhancement-tab-in-windows-11/"><u>Quick Recovery: Restoring the Lost Enhancement Tab in Window's 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-onedrive-errors-on-w11-systems/"><u>Strategies to Overcome OneDrive Errors on W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-grayed-out-delete-feature-for-windows-11-pins/"><u>Breaking Grayed-Out Delete Feature for Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-efficiency-how-copilot-key-shapes-your-windows-11-experience/"><u>Mastering Efficiency: How Copilot Key Shapes Your Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-restarting-windows-update-process/"><u>Essential Tips for Restarting Windows Update Process</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-beat-making-brilliance-music-for-your-instareals/"><u>In 2024, Beat-Making Brilliance  Music for Your InstaReals</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-leading-7-android-apps-to-cut-out-intrusive-ads/"><u>[New] The Leading 7 Android Apps to Cut Out Intrusive Ads</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-if-you-want-to-brighten-up-your-videos-and-make-them-more-colorful-you-should-try-one-of-these-video-brightness-editor-apps-to-ensure-you-have/"><u>2024 Approved If You Want to Brighten up Your Videos and Make Them More Colorful, You Should Try One of These Video Brightness Editor Apps to Ensure You Have the Best Software at Your Disposal</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-focused-adventure-getting-up-close-in-roblox-landscapes/"><u>In 2024, Focused Adventure  Getting Up Close in Roblox Landscapes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-media-the-best-12-tools-to-translate-videos-into-text/"><u>[Updated] Mastering Media  The Best 12 Tools to Translate Videos Into Text</u></a></li>
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-samsung-galaxy-xcover-7-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Samsung Galaxy XCover 7? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pioneering-pedagogy-through-film-in-the-classroom/"><u>Pioneering Pedagogy Through Film in the Classroom</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-best-mac-visual-snapshot-list-limit-156-chars/"><u>[New] In 2024, Best Mac Visual Snapshot List (Limit  156 Chars)</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mediasphere-app-user-experience-report/"><u>In 2024, MediaSphere App User Experience Report</u></a></li>
</ul></div>
