---
title: "Troubleshooting Tips: Fixing the 'An Error Has Happened While Solving Problems' On Windows 11 or 10"
date: 2024-08-31T22:02:18.936Z
updated: 2024-09-01T22:02:18.936Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3322edcb2b3700ce4baa5c0677a8f300e23dbf74c5228f8bd6ca0d33294791ed.png
---

## Troubleshooting Tips: Fixing the 'An Error Has Happened While Solving Problems' On Windows 11 or 10

### Key Takeaways

* Try launching the troubleshooter from the Settings app on your Windows 11 or 10 PC.
* Restart the "Background Intelligent Transfer Service" and "Cryptographic Services" services.
* If the issue persists, fix Windows' damaged system files with DSM and SFC, try to use the troubleshooter in safe mode, or reset your Windows PC.

 If you’ve encountered an “An error occurred while troubleshooting” error while launching a troubleshooter, worry not, as fixing this issue is easy in most cases. Here’s how to do that on your Windows 11 or Windows 10 PC.

 After applying each fix, launch your troubleshooter to check if it’s working.

##  Run the Troubleshooter From Settings

 While Windows allows you to [launch the built-in troubleshooters](https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-honor-play-40c-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) from the Run dialog box, we recommend opening those tools from Settings, as this is where the tools are hosted.

 To do that, [open the Settings app](https://facebook-video-footage.techidaily.com/updated-2024-approved-5-easy-ways-to-multiply-your-youtube-follower-base/) by pressing Windows+i. On Windows 11, head into System > Troubleshoot > Other Troubleshooters. On Windows 10, go to Update & Security > Troubleshoot > Additional Troubleshooters.

 Find the troubleshooting tool to launch. On Windows 11, next to the troubleshooter, select "Run."

!['Run' highlighted for multiple troubleshooters in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-troubleshooter-windows-11-settings-1.jpg) 

 On Windows 10, click the troubleshooter and choose "Run the Troubleshooter."

!['Run the Troubleshooter' highlighted for a troubleshooter in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-troubleshooter-windows-10-settings.jpg) 

 The tool will launch.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
##  Restart the Required Windows Services

 The built-in troubleshooters rely on various Windows services to function. These services might not be working correctly, causing an error. Give these services a reboot to fix the problem.

 Open the Run dialog box by pressing Windows+R, then type the following in the box and press Enter:

services.msc

 Find the service named "Background Intelligent Transfer Service." Right-click it and select "Restart."

!['Restart' highlighted for the 'Background Intelligent Transfer Service' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-restart-bits-service.jpg) 

 Similarly, right-click the "Cryptographic Services" service and select "Restart."

!['Restart' highlighted for the 'Cryptographic Services' service.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-restart-cryptographic-services-service.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Services window.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##  Fix Broken Troubleshooters

 It’s possible Windows’ system files are corrupted, causing the troubleshooters to malfunction. In this case, you must [repair the damaged core files](https://some-guidance.techidaily.com/twirl-forge-instruments-for-2024/) using the built-in System File Checker (SFC) tool.

 To do that, open the Start Menu, search for **Command Prompt**, and select "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-open-cmd-as-admin.jpg) 

 In the User Account Control"(UAC) prompt, select "Yes."

 In Command Prompt, type the following command and press Enter. This command will download the files required to fix the broken system files.

DISM.exe /Online /Cleanup-image /Restorehealth

![The DISM command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-run-dism-command-in-cmd.jpg) 

 Next up, run the following command to begin finding and repairing the damaged system files:

sfc /scannow

[Restart your Windows 11](https://screen-video-capture.techidaily.com/updated-in-2024-addressing-mute-problems-in-obs-live-recording/) or [Windows 10](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) PC once it finishes.

##  Launch the Troubleshooter in Safe Mode

[Safe mode on Windows](https://video-capture.techidaily.com/new-essential-scripting-instant-stopwatch-integration-in-obs-for-2024/) lets you check if third-party apps are preventing you from performing your tasks. In safe mode, Windows only loads the essential files to boot the system, letting you check for interference from any third-party programs or drivers.

 To [start your Windows 11 PC in safe mode](https://buynow-marvelous.techidaily.com/unveiling-the-strong-battery-feature-in-moto-g-power-a-tech-review-insight/), go to Settings > System > Recovery. Next to "Advanced Startup," click "Restart Now."

!['Restart Now' highlighted for 'Advanced Startup' in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-advanced-restart-windows-11.jpg) 

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To [boot your Windows 10 PC in safe mode](https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock/), head into Settings > Update & Security > Recovery. In the "Advanced Startup" section, click "Get Started."

!['Get Started' highlighted for 'Advanced Startup' in Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/8-advanced-restart-windows-10.jpg) 

 When your PC reboots, navigate to Troubleshoot > Advanced Options > Startup Settings and select "Restart." Then, choose the number for safe mode to boot into that mode. When your PC enters safe mode, launch the troubleshooter you wanted to use.

 If the tool works, a third-party app is likely the culprit. Review the list of your installed apps and remove any suspicious ones. It’s quick and easy to [uninstall apps on Windows 11](https://youtube-docs.techidaily.com/ed-in-2024-strategies-for-using-youtube-to-boost-classroom-engagement/) and [Windows 10](https://tech-recovery.techidaily.com/top-savings-on-apple-watches-in-april/).

##  Reset Windows

 If nothing else works, you can reset your Windows 11 or Windows 10 PC to the factory defaults. Resetting the system will fix any issues related to settings or corrupted files, but it should only be used as an last resort.

 You’ll lose your installed apps when you reset your PC. You’ll have the option to keep your personal files, though.

 To [reset a Windows 11 PC](https://facebook-video-footage.techidaily.com/new-blueprints-for-breaking-ground-in-edu-video-production-on-youtube-channels-for-2024/), navigate to Settings > System > Recovery. Next to "Reset This PC," click "Reset PC."

!['Reset PC' highlighted in Windows 11 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/9-reset-windows-11-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To [reset a Windows 10 PC](https://instagram-videos.techidaily.com/fast-and-free-strategies-for-authenticity-in-insta-circles-for-2024/), go to Settings > Update & Security > Recovery. In the "Reset This PC" section, click "Get Started."

!['Get Started' highlighted in the 'Reset This PC' section of Windows 10 Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/10-restart-windows-10-pc.jpg) 

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 On the open window, select "Keep My Files" so Windows doesn’t delete your personal files. Then, follow the on-screen instructions to finish resetting your computer.

 Your troubleshooting tool should work once your machine is back to the default settings.

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
<li><a href="https://graphic-issues.techidaily.com/fix-nvidia-driver-crash-resolved-and-operational/"><u>[Fix] Nvidia Driver Crash Resolved & Operational</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-enhancing-collaboration-slack-melded-with-filmoras-video-capabilities/"><u>[New] Enhancing Collaboration  Slack Melded With Filmora’s Video Capabilities</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitters-viral-hit-list-tiktok-edition/"><u>[Updated] 2024 Approved  Twitter's Viral Hit List  TikTok Edition</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-scrutinizing-how-content-makers-get-paid-from-youtube-shorts-videos-for-2024/"><u>[Updated] Scrutinizing How Content Makers Get Paid From YouTube Shorts Videos for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-trimming-techniques-understanding-video-crops-in-imovie/"><u>[Updated] Trimming Techniques  Understanding Video Crops in iMovie</u></a></li>
<li><a href="https://os-tips.techidaily.com/complete-guide-resetting-your-iphoneipad-to-factory-defaults-with-icloud-backup/"><u>Complete Guide: Resetting Your iPhone/iPad to Factory Defaults with iCloud Backup</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-network-issues-with-anydesk-in-win11/"><u>Fixing Network Issues with AnyDesk in WIn11</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-principles-to-consider-in-a-new-os-rollout/"><u>Guiding Principles to Consider in a New OS Rollout</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/harness-efficient-online-strategies-backed-by-cookiebot/"><u>Harness Efficient Online Strategies, Backed by Cookiebot</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-the-usb-attachment-failure-in-virtualbox-instantly/"><u>How to Remedy the USB Attachment Failure in VirtualBox Instantly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-samsung-galaxy-xcover-6-pro-tactical-edition-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Samsung Galaxy XCover 6 Pro Tactical Edition Fingerprint Lock</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expertise-in-hdr-perfecting-dynamic-range-in-photoshop/"><u>In 2024, Expertise in HDR  Perfecting Dynamic Range in Photoshop</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-exploring-different-approaches-to-game-playback/"><u>In 2024, Exploring Different Approaches to Game Playback</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-films-finest-closure-kits-grab-em-without-cost/"><u>In 2024, Film's Finest Closure Kits – Grab 'Em Without Cost</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-8-plus-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pilot-to-perfection-complete-review-of-dji-phantom-4/"><u>In 2024, Pilot to Perfection  Complete Review of DJI Phantom 4</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-best-cameras-for-youtube-from-beginners-to-professionals/"><u>In 2024, The Best Cameras for YouTube From Beginners to Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-charging-notifications-in-modern-windows-os/"><u>Leveraging Charging Notifications in Modern Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-batch-conversion-heic-to-jpeg-in-windows-11/"><u>Mastering the Art of Batch Conversion: Heic to JPEG in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-fixing-install-failed-on-windows-1011/"><u>Mastering the Art of Fixing Install Failed on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-visual-quality-with-w11s-auto-hdr/"><u>Maximizing Visual Quality with W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-purging-onedrive-icon-in-file-explorer/"><u>Methodology: Purging OneDrive Icon in File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-background-run-of-microsoft-edge-on-win11/"><u>Navigating the Background Run of Microsoft Edge on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-fixing-the-termination-denial/"><u>Navigating Windows Errors - Fixing the Termination Denial</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-make-your-videos-pop-the-secret-to-adding-jaw-dropping-effects/"><u>New Make Your Videos Pop The Secret to Adding Jaw-Dropping Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-launch-directly-engage-file-explorer-through-onedrive/"><u>Optimizing Windows Launch: Directly Engage File Explorer Through OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-backspace-failures-in-windows-environments/"><u>Overcoming Backspace Failures in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-game-pass-service-halt-in-win-os/"><u>Overcoming Game Pass Service Halt in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-your-preferred-windows-volume-mixer-state/"><u>Preserving Your Preferred Windows Volume Mixer State</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-guide-for-turning-onoff-windows-key/"><u>Quick & Easy Guide for Turning On/Off Windows Key</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-guide-to-repairing-typical-televisions-faults-and-errors/"><u>Quick Guide to Repairing Typical Televisions Faults and Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/re-initiate-audio-playback-on-frozen-systems/"><u>Re-Initiate Audio Playback on Frozen Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unrealcefsubprocess-power-footprint-on-windows-os/"><u>Reducing UnrealCEFSubprocess Power Footprint on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-wifi-detection-capabilities-in-win11/"><u>Reigniting Your Wifi Detection Capabilities in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-privacy-erasing-ms-defender-logs-in-windows-1011/"><u>Safeguard Privacy: Erasing MS Defender Logs in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/set-up-a-fast-safe-login-windows-hello-basics/"><u>Set Up a Fast, Safe Login: Windows Hello Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed!</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-to-erase-wsl-from-windows-11-operating-system/"><u>Stepwise Strategy to Erase WSL From Windows 11 Operating System</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-keeping-calculator-visible-at-top/"><u>Strategies for Keeping Calculator Visible at Top</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-overcoming-windows-administrative-restriction-on-installers/"><u>Strategies for Overcoming Windows' Administrative Restriction on Installers</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-overcome-onedrives-immediate-folder-addition-error/"><u>Swift Solutions to Overcome OneDrive's Immediate Folder Addition Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-accessing-onedrive-offline-on-windows/"><u>The Insider's Guide: Accessing OneDrive Offline on WINDOWS</u></a></li>
<li><a href="https://windows11.techidaily.com/the-new-era-ai-enhancements-in-windows-platforms/"><u>The New Era: AI Enhancements in Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unsupported-app-packages-on-windows-xp/"><u>Troubleshooting Unsupported App Packages on Windows XP</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-arp-caches-deletion-guide/"><u>Understanding Windows ARP Caches: Deletion Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-outlook-preview-features-on-windows-11-platforms/"><u>Unveiling Outlook Preview Features on Windows 11 Platforms</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-seamless-storytelling-top-10-premiere-pro-transition-effects/"><u>Updated Seamless Storytelling Top 10 Premiere Pro Transition Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-terminal-the-art-of-color-selection/"><u>Windows Terminal: The Art of Color Selection</u></a></li>
</ul></div>
