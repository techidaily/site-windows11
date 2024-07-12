---
title: Resolving Package Registration Failures on Windows Devices
date: 2024-07-11T21:37:29.877Z
updated: 2024-07-12T21:37:29.877Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Package Registration Failures on Windows Devices
excerpt: This Article Describes Resolving Package Registration Failures on Windows Devices
keywords: Fix Pack RegFail WIN,Resolve Win Device Errors,Stop Package Install Fail,Clearing Win Reg Err,Unlock Device Registration,Correct Windows Registration,Overcome Dev Reg Issues
thumbnail: https://thmb.techidaily.com/bd1f3164b21938808543fb77a181f9a976b01572cf9b49cfe1852edc61f82d53.jpg
---

## Resolving Package Registration Failures on Windows Devices

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
<li><a href="https://windows11.techidaily.com/restore-your-window-11-drag-functionality/"><u>Restore Your Window 11 Drag Functionality</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-offline-errors-for-windows-11s-printer-port/"><u>Resolving Offline Errors for Windows 11'S Printer Port</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-restarting-resistant-spotify-program/"><u>Quick Fix: Restarting Resistant Spotify Program</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-programs-for-faster-startups/"><u>Optimizing Windows 11 Programs for Faster Startups</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, Top 11 Free Apps to Check IMEI on Apple iPhone 12</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-visibility-of-missing-disk-in-win/"><u>Restoring Visibility of Missing Disk in Win</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-5-best-music-visualizers-freeandpaid/"><u>New 5 Best Music Visualizers Free&Paid</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-ad-ds-printing-issues-in-windows-11-pro/"><u>Overcoming AD DS Printing Issues in Windows 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-swiftly-handle-stalled-gpsvc-process/"><u>How to Swiftly Handle Stalled GPSVC Process</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-illuminated-imagery-standing-out-in-the-visual-field/"><u>[New] Illuminated Imagery  Standing Out in the Visual Field</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-google-hangout-techniques-4-ways-to-shine/"><u>[Updated] 2024 Approved  Google Hangout Techniques, #4 Ways to Shine</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-for-fixing-nvidia-gui-sharing-glitches/"><u>Guide for Fixing NVIDIA GUI Sharing Glitches</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-infinix-smart-8-plus-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Infinix Smart 8 Plus</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-15plus-best-iphoneipad-video-editing-tools-in-free-market/"><u>2024 Approved  15+ Best iPhone/iPad Video Editing Tools in Free Market</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-usage-settings-on-windows-11-your-how-to-guide/"><u>Navigating Usage Settings on Windows 11: Your How-To Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-tactical-co-creation-youtube-and-brand-joint-efforts/"><u>2024 Approved  Tactical Co-Creation  YouTube and Brand Joint Efforts</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resurrect-a-dormant-windows-tab-key/"><u>Steps to Resurrect a Dormant Windows Tab Key</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-full-battery-charge-notification-to-windows-11-and-11/"><u>How to Add a Full Battery Charge Notification to Windows 11 & 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/annual-list-highest-rated-free-lut-sources-online-for-2024/"><u>Annual List  Highest Rated FREE LUT Sources Online for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-infinix-zero-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-rectify-win-1011-onedrive-issues/"><u>Steps to Rectify Win 10/11 OneDrive Issues</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-advanced-editing-for-published-youtube-videos/"><u>[Updated] In 2024, Advanced Editing for Published YouTube Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-comprehensive-review-of-slomo-video-capture-tool/"><u>[Updated] 2024 Approved  Comprehensive Review of SloMo Video Capture Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-value-not-found-error-message-in-windows-setups/"><u>Solving 'Value Not Found' Error Message in Windows Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-tasks-effortlessly-top-8-pomodoro-timer-reviews-on-pc/"><u>Mastering Tasks Effortlessly - Top 8 Pomodoro Timer Reviews on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revive-non-starting-adobe-photoshop-on-ws11-and-11/"><u>How to Revive Non-Starting Adobe Photoshop on WS11 & 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-leading-selection-no-cost-outstanding-lut-links/"><u>[Updated] The Leading Selection  No-Cost, Outstanding LUT Links</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-audio-recorder-snag-with-error-9999-solution/"><u>Navigating Windows' Audio Recorder Snag with Error 9999 Solution</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-elevating-your-entertainment-game-on-roku-and-facebook-live/"><u>[Updated] 2024 Approved  Elevating Your Entertainment Game on Roku and Facebook LIVE</u></a></li>
<li><a href="https://windows11.techidaily.com/significance-and-uses-for-vcplusplus-releases/"><u>Significance and Uses for VC++ Releases</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-avoiding-frequent-sign-ins-on-ms-teams-platform/"><u>Solutions for Avoiding Frequent Sign-Ins on MS Teams Platform</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-two-screen-viewing-step-by-step-guide-for-netflix-users/"><u>Mastering Two Screen Viewing - Step By Step Guide For Netflix Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-xiaomi-redmi-12-by-fonelab-android-recover-music/"><u>How To  Restore Missing Music Files from Xiaomi Redmi 12</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-open-adobe-ps-in-w11-after-updates/"><u>Step-by-Step to Open Adobe PS in W11 After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-troubleshooting-overcoming-error-e84-on-steam/"><u>Mastering the Art of Troubleshooting: Overcoming Error E84 on Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-mp3s-into-listenable-audio-cds-using-windows-and-imgburn-techniques/"><u>Optimizing MP3s Into Listenable Audio Cds Using Windows and ImgBurn Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-task-execution-on-windows-adding-an-improved-run-utility/"><u>Optimizing Task Execution on Windows: Adding an Improved Run Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/seamlessly-access-lately-used-documents-in-windows/"><u>Seamlessly Access Lately Used Documents in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-for-mastering-local-user-groups-on-win1110/"><u>Pro Tips for Mastering Local User Groups on Win11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-steam-setup-obstacles-on-windows-11-devices/"><u>Overcoming Steam Setup Obstacles on Windows 11 Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-mastering-the-art-of-oral-explanitations-and-slides/"><u>In 2024, Mastering the Art of Oral Explanitations & Slides</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-nokia-g22-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Nokia G22 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/davinci-resolve-scopes-have-undergone-significant-improvements-find-out-how-to-use-these-scopes-and-improve-your-video-editing-skills/"><u>DaVinci Resolve Scopes Have Undergone Significant Improvements. Find Out How to Use These Scopes and Improve Your Video Editing Skills</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-the-complete-guide-to-video-editors-best-options-for-windows-mac-ios-android-and-linux/"><u>In 2024, The Complete Guide to Video Editors Best Options for Windows, Mac, iOS, Android, and Linux</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-5-fast-framing-homemade-tips-for-pros/"><u>Top 5 Fast-Framing Homemade Tips for Pros</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-destructive-js-error-in-discord-on-win-11-pcs/"><u>How to Mend the Destructive JS Error in Discord on Win 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-window-management-embrace-adaptive-wmlayouts/"><u>Redefine Window Management: Embrace Adaptive WMLayouts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-lava-yuva-2-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Lava Yuva 2 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/from-novice-to-pro-a-guide-to-github-desktop-and-windows-integration/"><u>From Novice to Pro: A Guide to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-common-errors-in-microsoft-office-activation/"><u>Overcoming Common Errors in Microsoft Office Activation</u></a></li>
</ul></div>
