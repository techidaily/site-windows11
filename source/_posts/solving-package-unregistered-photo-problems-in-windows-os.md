---
title: Solving 'Package Unregistered' Photo Problems in Windows OS
date: 2024-08-27T16:05:05.659Z
updated: 2024-08-28T16:05:05.659Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving 'Package Unregistered' Photo Problems in Windows OS
excerpt: This Article Describes Solving 'Package Unregistered' Photo Problems in Windows OS
keywords: Fix Unregistered Packages Error,Windows Photo Issue Resolution,Removing Package Error,Solve Package Installation,Windows Photo Fix Guide,Unregistered Packages Troubleshoot,Windows OS Photo Problems
thumbnail: https://thmb.techidaily.com/f9a5463fbd0c790fcad5c9ca24a63fabc5c5b34da6ae2629a7d19232172ec8eb.jpg
---

## Solving 'Package Unregistered' Photo Problems in Windows OS

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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-leverage-youtube-metrics-for-enhanced-visibility/"><u>[New] 2024 Approved  Leverage YouTube Metrics for Enhanced Visibility</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-reestablishing-communication-with-a-non-responsive-obs-cam/"><u>[New] 2024 Approved  Reestablishing Communication with a Non-Responsive OBS Cam</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-a-compreenasion-of-siri-integration-into-tiktok-filmmaking/"><u>[New] A Compreenasion of Siri Integration Into TikTok Filmmaking</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-banner-bliss-get-a-peek-at-our-library-of-50-free-youtube-banners-for-2024/"><u>[New] Banner Bliss  Get a Peek at Our Library of 50 Free YouTube Banners for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-behind-the-curtain-detailed-guide-to-import-tasks-w11/"><u>[New] Behind the Curtain  Detailed Guide to Import Tasks W11</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-evaluating-visual-dynamics-the-power-of-luminances-hdr/"><u>[New] Evaluating Visual Dynamics  The Power of Luminance's HDR</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-mastering-alias-transformation-on-google-meet-platforms/"><u>[New] In 2024, Mastering Alias Transformation on Google Meet Platforms</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-premium-psd-aesthetic-optimization/"><u>[New] Premium PSD Aesthetic Optimization</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-secrets-to-affordable-gopro-acquisitions/"><u>[New] Secrets to Affordable GoPro Acquisitions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-smile-with-these-top-funny-tiktok-videos-and-jokes/"><u>[New] Smile with These  Top Funny TikTok Videos and Jokes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-time-lapse-tips-for-iphoneipad-users/"><u>[New] Time-Lapse Tips for iPhone/iPad Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-ultimate-list-best-asmr-on-smartphones/"><u>[New] Ultimate List  Best ASMR on Smartphones</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-easy-steps-for-posting-videos-on-facebook-from-devices/"><u>[Updated] In 2024, Easy Steps for Posting Videos on Facebook From Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-exclusive-resource-hub-downloadable-templates-for-youtubers/"><u>[Updated] In 2024, Exclusive Resource Hub - Downloadable Templates for YouTubers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-social-media-sensation-top-eight-videos/"><u>[Updated] In 2024, Social Media Sensation  Top Eight Videos</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-optimizing-video-playback-sizes-on-youtube-for-2024/"><u>[Updated] Optimizing Video Playback Sizes on YouTube for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-build-haha-images/"><u>2024 Approved  Build Haha Images</u></a></li>
<li><a href="https://fox-glue.techidaily.com/dark-screenwork-in-premiere-pro-for-2024/"><u>Dark Screenwork in Premiere Pro for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-driver-installation-grab-your-usb-camera-software-today/"><u>Effortless Driver Installation: Grab Your USB Camera Software Today</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-non-scrolling-issue-unlock-cells-in-excel-windows/"><u>Fix Non-Scrolling Issue: Unlock Cells in Excel (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-failed-steam-remote-links-on-pc/"><u>Fixing Failed Steam Remote Links on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-outlooks-restricted-folder-access-on-desktop-computers/"><u>Fixing Outlook's Restricted Folder Access on Desktop Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-high-contrast-customization-in-windows/"><u>Halt High Contrast Customization in Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-steelseries-arctis-7-mic-not-working/"><u>How to Fix SteelSeries Arctis 7 Mic Not Working</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-narzo-60-5g-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Narzo 60 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-poco-x5-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Poco X5 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On OnePlus 11R? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-prime-voice-activated-transcription-tools/"><u>In 2024, Prime Voice-Activated Transcription Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-apk-files-made-convenient-win-11s-guide-to-easy-setups/"><u>Installing APK Files Made Convenient: Win 11'S Guide to Easy Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cortana-integration-vivetool-writings/"><u>Mastering Cortana Integration: ViveTool' Writings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowed-discords-search-tweaks/"><u>Mastering Windowed Discord's Search Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-taskbar-functionality/"><u>Maximizing Windows 11 Taskbar Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-modify-display-settings/"><u>Method to Modify Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-fix-windows-update-code-error-0x8024800c/"><u>Methods to Fix Windows Update: Code Error 0X8024800C</u></a></li>
<li><a href="https://windows11.techidaily.com/open-locked-windows-shared-files-now/"><u>Open Locked Windows Shared Files Now</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/optimize-your-time-pick-the-fastest-5-chrome-addons-for-facebook-vids/"><u>Optimize Your Time  Pick the Fastest 5 Chrome Addons for Facebook Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-discrepancy-in-windows-11s-power-life-predictor/"><u>Overcoming Discrepancy in Windows 11'S Power Life Predictor</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-visuals-your-guide-to-leveraging-background-blur-on-windows-11-photos-app/"><u>Perfect Visuals: Your Guide to Leveraging Background Blur on Windows 11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-system-status-and-update-information-via-menu-option-in-win11/"><u>Quick Access to System Status & Update Information via Menu Option in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-unconnected-error-with-geforce-experience-on-pc/"><u>Rectifying Unconnected Error with GeForce Experience on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reimagine-your-workspace-with-direct-desktop-drawings-in-windows-11/"><u>Reimagine Your Workspace with Direct Desktop Drawings in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-journey-in-windows-11-the-top-8-slippery-slope/"><u>Safe Journey in Windows 11: The Top 8 Slippery Slope</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-your-desktops-background-from-changes/"><u>Safeguard Your Desktop's Background From Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-non-responsive-windows-shift/"><u>Solutions for Non-Responsive Windows Shift.</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-your-workday-mastery-tips-for-multitasking-windows-11/"><u>Supercharge Your Workday: Mastery Tips for Multitasking Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharging-windows-11s-protected-mode-graphics/"><u>Supercharging Windows 11'S Protected Mode Graphics</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-success-guiding-through-windows-11-renewal/"><u>Systematic Success: Guiding Through Windows 11 Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-cpu-drain-by-tiworkerexe/"><u>Tackling High CPU Drain by TiWorker.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-managing-windows-users-via-cli/"><u>The Art of Managing Windows Users via CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-compatible-windows-and-android-programs/"><u>Top 8 Compatible Windows and Android Programs</u></a></li>
<li><a href="https://some-skills.techidaily.com/transform-your-media-projects-uploading-images-to-youtube-for-2024/"><u>Transform Your Media Projects  Uploading Images to YouTube for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072efd-on-windows-devices/"><u>Troubleshooting Error 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steam-ui-dll-failure-on-windows/"><u>Troubleshooting Steam UI DLL Failure on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unite-cloud-storage-onedrive-meets-microsoft-live-id/"><u>Unite Cloud Storage: OneDrive Meets Microsoft Live ID</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-print-potential-strategies-to-fix-slide-show-problems-on-windows/"><u>Unlocking Your Print Potential: Strategies to Fix Slide Show Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unshackle-administrative-access-on-pcs/"><u>Unshackle Administrative Access on PCs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-hdr-photography-how-to-use-hdr-mode-on-your-android-devices/"><u>Updated HDR Photography How to Use HDR Mode on Your Android Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-video-quality-from-yesteryears-using-madvr-windows-edition/"><u>Upgrade Video Quality From Yesteryears Using MadVR, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/wake-up-call-reviving-sleeping-pcs-with-inputs-on-1011/"><u>Wake-Up Call: Reviving Sleeping PCs with Inputs on 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-back-your-disconnected-wi-fi/"><u>Winning Back Your Disconnected Wi-Fi</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-game-of-cutting-top-8-video-edits-for-pc/"><u>Winning the Game of Cutting: Top 8 Video Edits for PC</u></a></li>
</ul></div>
