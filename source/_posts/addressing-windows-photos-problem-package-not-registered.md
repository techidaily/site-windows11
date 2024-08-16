---
title: Addressing Windows Photos Problem - Package Not Registered
date: 2024-08-15T15:14:45.604Z
updated: 2024-08-16T15:14:45.604Z
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

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-determining-a-bespoke-keyword-for-your-tiktok-feed/"><u>[New] In 2024, Determining a Bespoke Keyword for Your TikTok Feed</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-mastering-facebook-video-auto-play/"><u>[New] In 2024, Mastering Facebook Video Auto-Play</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-understanding-and-executing-photo-gender-modification-across-platforms/"><u>[New] Understanding and Executing Photo Gender Modification Across Platforms</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-bursting-laughter-crafting-engaging-reaction-videos-on-youtube-3-methods-for-2024/"><u>[Updated] Bursting Laughter  Crafting Engaging Reaction Videos on YouTube (3 Methods) for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchat-for-mac-quick-installation-tips/"><u>[Updated] Snapchat for MAC  Quick Installation Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagrams-audio-alteration-the-ultimate-guide/"><u>2024 Approved  Instagram's Audio Alteration  The Ultimate Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-twitter-mp4webm-clip-conversion/"><u>2024 Approved  Twitter MP4/WebM Clip Conversion</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/correcting-time-jumps-fixing-obs-studio-problems-for-2024/"><u>Correcting Time Jumps  Fixing OBS Studio Problems for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-win11-defender-firewall-control/"><u>Essential Tips for Win11 Defender Firewall Control</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tactics-to-unite-windows-directories/"><u>Expert Tactics to Unite Windows Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/five-fun-flicks-in-windows-cmd-world/"><u>Five Fun Flicks in Windows' CMD World</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-print-server-not-responding-issue/"><u>Fixing Print Server Not Responding Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/gauge-your-windows-workhorse-power-efficiency-explored/"><u>Gauge Your Window's Workhorse - Power Efficiency Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-the-0x0-0x0-error-code-in-windows-11-heres-how-to-fix-it/"><u>Getting the 0X0 0X0 Error Code in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-abnormal-character-output-windows-wise/"><u>Handling Abnormal Character Output Windows-Wise</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-on-iphone-7-plus-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password On iPhone 7 Plus</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/improve-your-video-editing-with-these-5-obs-solutions-for-2024/"><u>Improve Your Video Editing with These 5 OBS Solutions for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-simplified-webinar-recording-methods-for-windows-and-mac-users/"><u>In 2024, Simplified Webinar Recording Methods for Windows & Mac Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-songsyncing-simplified-your-guide-to-turning-tamil-music-into-alerts/"><u>In 2024, SongSyncing Simplified  Your Guide to Turning Tamil Music Into Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-out-mastering-windows-error-resolution-version-22h2/"><u>Inside Out: Mastering Windows Error Resolution, Version 22H2</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-hardware-space-exploring-disks-in-w10-and-w11/"><u>Mastering Hardware Space: Exploring Disks in W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-restarting-non-starting-windows-drivers/"><u>Mastering the Art of Restarting Non-Starting Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-showhide-system-directories/"><u>Mastering Windows 11: Show/Hide System Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/meet-asuss-latest-rivals-to-rog-ally-in-gaming/"><u>Meet ASUS’s Latest Rivals to ROG Ally in Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/mend-your-meeting-screen-display/"><u>Mend Your Meeting Screen Display</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-reviving-your-windows-11-password/"><u>Methods for Reviving Your Windows 11 Password</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-common-pin-hurdles-in-modern-windows-os-win10win11/"><u>Navigating Common PIN Hurdles in Modern Windows OS (Win10/Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-essential-elements-warning-in-windows-11/"><u>Navigating Through Essential Elements Warning in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-non-detected-proxy-setup/"><u>Navigating Windows Non-Detected Proxy Setup</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Planning to Use a Pokemon Go Joystick on Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/precision-recording-for-instagram-story-enthusiasts-for-2024/"><u>Precision Recording for Instagram Story Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tip-erasing-microsoft-edge-on-windows-11/"><u>Quick Tip: Erasing Microsoft Edge on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-run-windows-past-execution/"><u>Regaining Run Window's Past Execution</u></a></li>
<li><a href="https://techidaily.com/remove-k11x-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove K11x unlock screen</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-a-hidden-shortcoming-an-insightful-review-of-samsung-galaxy-tab-a-2020/"><u>Revealing a Hidden Shortcoming: An Insightful Review of Samsung Galaxy Tab A (2020)</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-chrome-setup-in-windows-11-systems/"><u>Seamless Chrome Setup in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-access-to-repair-solutions-customizing-hotkeys-for-win-1011/"><u>Speedy Access to Repair Solutions: Customizing Hotkeys for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-non-successful-disco-update-windows-errors/"><u>Steps to Address Non-Successful Disco Update Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-successful-v22h2-updater-execution-on-win11/"><u>Strategies for Successful V22H2 Updater Execution on WIN11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-rectify-failed-utorrent-installations-in-windows/"><u>Strategies to Rectify Failed uTorrent Installations in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-driving-experience-with-free-upgrades-for-windows-users/"><u>Streamline Driving Experience with Free Upgrades for Windows Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/supercharge-productivity-discover-the-7-expert-ways-chatgpt-transforms-your-day-to-day-jobs/"><u>Supercharge Productivity: Discover the 7 Expert Ways ChatGPT Transforms Your Day-to-Day Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-not-found-gpeditmsc-in-windows-errors/"><u>Tackling the Not Found: Gpedit.msc in Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-the-forgotten-now-revealed-restoring-your-windows-on-win10win11/"><u>The Hidden, The Forgotten, Now Revealed: Restoring Your Windows on Win10/Win11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-motorola-edge-40-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Motorola Edge 40 Android SIM Unlock APK</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-chaos-organizing-with-windows-11-calendar/"><u>Transforming Chaos: Organizing with Windows 11 Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-old-drives-step-by-step-for-windows-rejuvenation/"><u>Transforming Old Drives: Step-by-Step for Windows Rejuvenation</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-vlc-lag-on-windows-devices/"><u>Troubleshooting VLC Lag on Windows Devices</u></a></li>
<li><a href="https://some-skills.techidaily.com/unique-identity-creation-accessible-logo-base-and-personal-customization-for-no-cost-for-2024/"><u>Unique Identity Creation  Accessible Logo Base & Personal Customization for No-Cost for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-quick-deletion-windows-customization-for-instant-removal/"><u>Unleashing Quick Deletion: Windows Customization for Instant Removal</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-error-code-9999-in-win-based-audacity/"><u>Unraveling the Mystery of Error Code 9999 in Win-Based Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-11s-elevation-failures/"><u>Unraveling the Mystery of Windows 11’S Elevation Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/unrelated-processes-under-microsoft-edge-in-tasks/"><u>Unrelated Processes Under Microsoft Edge in Tasks</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-end-task-control-capabilities-in-windows-11-ui-environment/"><u>Unveiling End Task Control Capabilities in Windows 11 UI Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-rgb-lighting-on-win11-pcs/"><u>Utilizing RGB Lighting on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-establishing-kids-online-boundaries/"><u>Windows 11: Establishing Kids' Online Boundaries</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-watchlist-7-tasks-to-inspect-for-hidden-viruses/"><u>Windows Watchlist: 7 Tasks to Inspect for Hidden Viruses</u></a></li>
</ul></div>
