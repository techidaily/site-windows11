---
title: Addressing Print Service Stopped Issue on Windows PC
date: 2024-07-11T21:28:26.894Z
updated: 2024-07-12T21:28:26.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Print Service Stopped Issue on Windows PC
excerpt: This Article Describes Addressing Print Service Stopped Issue on Windows PC
keywords: Stop Printer Errors,Windows Print Fix,PC Print Issue Resolve,End Windows Print Failure,Solve Print Service Crash,Troubleshoot Print on PC,Quick Print Solution Windows
thumbnail: https://thmb.techidaily.com/cf530c2c593b6932cef8db0cdf4cd19063a18ed96567f34da25c1f69a7f2e22f.jpg
---

## Addressing Print Service Stopped Issue on Windows PC

 The Print Spooler is a little application built into your operating system. It allows you to send multiple print jobs to a queue without waiting for the initial print job to complete. If the print spooler service stops working, you’ll encounter the print spooler service is not running error on Windows.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.

## How "The Print Spooler Service Is Not Running” Error Message Appears

 Here are the different types of print spooler errors you can encounter:

* "Windows cannot connect to the printer. The local print spooler service is not running."
* "Operation could not be completed. The print spooler service is not running."

 Whichever error you encounter, the solutions for fixing them are the same.

## 1\. Run the Printer Troubleshooter

 The built-in Printer troubleshooter in Windows 10 and 11 lets you [find and fix printing problems](http://www.makeuseof.com/windows-11-printer-not-working/). The troubleshooter scans the system for common print problems and automatically resolves them. It can check and restart the print spooler service if stopped.

1. Press **Win + I** to open **Settings**.
2. Open the **System** tab in the left pane.
3. In the right pane, scroll down and click on **Troubleshoot**.  
![windows 11 troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-troubleshoot.jpg)
4. Next, click on **Other troubleshooters.**
5. Next, click the **Run** button for the **Printer** option. The troubleshooter will scan the system and try to detect any issues.  
![windows 11 printer troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-printer-troubleshooter.jpg)
6. Select the printer you want to troubleshoot and click **Next**.
7. Wait for the scan to complete and check if it finds any problem. Then, apply the recommended fixes if available.

## 2\. Restart Print Spooler Service

![print spooler service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/print-spooler-service-restart.jpg)

 You can check and rerun the print spooler service in the Services snap-in to fix the print spooler service is not running error. Here's how to do it:

1. Press the **Win** key and type **services**.
2. Click on **Services** to open the snap-in.
3. Next, locate the **Print Spooler** service from the list of services.
4. Right-click on the service, select **Restart** and wait for the process to complete.
5. Give a new print job and check if the error is resolved.

## 3\. Set the Print Spooler Service Startup Type to Automatic

 By default, the print spooler service is set to start automatically when the system reboots. However, if you have set it to start manually, the service can stop working. You can change the startup type for the print spooler service using the Services snap-in.

 To change startup type for print spooler service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. Here, locate the **Print Spooler** service.  
![print spooler service properties services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services.jpg)
4. Right-click on **Print Spooler** and select **Properties**.
5. In the pop-up dialog that opens, click the drop-down for **Startup type** and select **Automatic.**  
![print spooler service properties services startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services-startup-type-automatic.jpg)
6. Click **Apply** and **OK** to save the changes.
7. If it is already set to **Automatic**, then select **Disabled**. Click **Apply** and **OK** to save the changes.
8. Now open the Print Spooler service properties and set the **Startup type** to **Automatic**.
9. Click **OK** and **Apply** to save the changes.
10. Close the Services snap-in and restart your PC. Next, create a print job and check if the error printer spooler service is not running is resolved.

## 4\. Clear the Print Spooler Files

 Too many pending or corrupted print jobs can trigger the print spooler service not running error. To resolve this, you can delete the print spooler files manually and restart the service. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK**.
3. Locate and select the **Print Spooler** service in the Services snap-in.
4. Right-click on **Print Spooler** and select **Stop**.  
![print spooler service stop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-stop.jpg)
5. Next, press **Win + E** to open File Explorer.
6. Navigate to the following location. You can copy and paste the following path in the File Explorer address bar for quick navigation:  
C:\Windows\System32\spool\PRINTERS
7. Here, clear all the files inside the Printers folder. Click **Yes** if prompted by **User Account Control (UAC).** Do Not Delete the **PRINTERS** folder, but only the files inside the folder.  
![delete printer spooler service files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/delete-printer-spooler-service-files.jpg)
8. Close File Explorer and go back to the **Services** snap-in.  
![print spooler service start](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-start.jpg)
9. Select and right-click on the **Print Spooler** service and select **Start**.

 Now create a new print job and check if the error is resolved. If not, disconnect and reconnect the printer to see if that helps.

## 5\. Check Windows Defender Firewall

 If your printer is connected to a network, it is possible that Windows Defender Firewall is preventing the connection resulting in the error. You can confirm this case by [temporarily disabling Windows Defender Firewall](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and creating a new print job.

 To disable Windows Defender Firewall:

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy & security** tab in the left pane.
3. Next, click on **Windows Security.**  
![Open Windows Security Windows 11 Settings 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings-1.jpg)
4. Finally, click on **Open Windows Security.**
5. Open the **Firewall & network protection** tab in the left pane.  
![firewall and network protection windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/firewall-and-network-protection-windows-defender.jpg)
6. Click on your currently active network **(Public / Private).**
7. Toggle the switch under **Microsoft Defender Firewall** to turn off **Firewall**. Click **Yes** if prompted by **UAC**.  
![turn off Microsoft defender firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-Microsoft-defender-firewall.jpg)
8. With the Firewall disabled, create a new print job, and see if it completes successfully.
9. Once done, enable the **Windows Defender Firewall** protection.

 If you use your printer frequently, disabling Windows Defender Firewall is not a feasible solution. You’ll need to investigate the issue further to allow the connection through the Firewall.

## 6\. Update Your Printer Driver

![update drive printer device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/update-drive-printer-device-manager.jpg)

 Outdated or corrupted [computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) can cause your connected device to malfunction. Try updating your printer driver to see if that helps resolve the error. You can update the generic printer driver using the Device Manager. Here’s how to do it.

1. Press **Win + I** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open **Device Manager.**
3. In Device Manager, expand the **Print queues** section.
4. Right-click on your printer and select **Update driver.**
5. Next, select **Search automatically for drivers**. Windows will scan for a new driver update and download and install it if available.

 If no new updates are available, use your printer manufacturer’s website to download the latest driver for your printer model.

## 7\. Uninstall and Reinstall the Printer Driver

 You can also uninstall the printer driver to perform a clean install of your printer. To remove a printer, first, you need to remove the device from the Settings and then remove the driver.

 To uninstall a printer:

1. Press **Win + I** to open **Settings**.
2. In the left pane, click on **Bluetooth & devices.**  
![bluetooth and devices printers scanners](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/bluetooth-and-devices-prnters-scanners.jpg)
3. Next, click on **Printers & scanners.**
4. Now locate and click on your printer.  
![uninstall printer settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/uninstall-printer-settings.jpg)
5. Click the **Remove** button in the top right corner and click **Yes** to confirm the action.

 Once done, restart your PC. After the restart, download the latest drivers for your printer from the manufacturer's website and complete the setup.

## Fixing the "Print Spooler Service Is Not Running" Error

 Often you can fix issues with the print spooler service by restarting the service or deleting the print queue files. However, if the issue persists, investigate your system for new changes, such as Windows updates or system file corruption.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-navigating-mobile-recorders-to-capture-snapchat-moments/"><u>[Updated] 2024 Approved  Navigating Mobile Recorders to Capture Snapchat Moments</u></a></li>
<li><a href="https://extra-tips.techidaily.com/selecting-superior-audio-our-picks-for-the-top-6-live-stream-enhancers/"><u>Selecting Superior Audio  Our Picks for the Top 6 Live-Stream Enhancers</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-for-a-different-youtube-the-top-10-free-video-apps-on-phones-and-tablets/"><u>[New] For a Different YouTube  The Top 10 Free Video Apps on Phones & Tablets</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boost-channels-and-views-through-savvy-youtube-analysis-for-2024/"><u>Boost Channels and Views Through Savvy YouTube Analysis for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-aural-enhancements-with-video-editing-on-win11/"><u>In 2024, Aural Enhancements with Video Editing on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-3d-painting-with-these-tips/"><u>Master the Art of 3D Painting with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-incorrect-parameters-leading-to-loadlibrary-failure/"><u>Fixing Incorrect Parameters Leading to LoadLibrary Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-obs-record-failure-a-comprehensive-guide-for-windows-users/"><u>Addressing OBS Record Failure: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-comprehensive-checklist-for-perfecting-your-reddit-posts/"><u>[New] The Comprehensive Checklist for Perfecting Your Reddit Posts</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-and-found-how-to-find-the-disappeared-enhancements-on-windows-11/"><u>Lost and Found: How to Find the Disappeared Enhancements on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-techniques-for-initiatingexit-focus-in-the-windows-terminal/"><u>Essential Techniques for Initiating/Exit Focus in the Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-blue-screen-5-tactics-for-win11-hybrid-issue-fixes/"><u>Conquer Blue Screen: 5 Tactics for Win11 Hybrid Issue Fixes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-create-stunning-mac-slideshows-a-beginners-guide-to-ezvid/"><u>New 2024 Approved Create Stunning Mac Slideshows A Beginners Guide to Ezvid</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagrams-visual-rhythm-mastering-the-slow-motion-balance-for-2024/"><u>[Updated] Instagram's Visual Rhythm  Mastering the Slow-Motion Balance for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-tips-for-a-seamless-phone-screen-record/"><u>[New] 2024 Approved  Tips for a Seamless Phone Screen Record</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-productivity-with-top-6-windows-apps/"><u>Elevate Your Productivity with Top 6 Windows Apps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-storage-space-used-for-daily-extended-videography/"><u>[New] Storage Space Used for Daily Extended Videography</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Xiaomi 13T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-chains-of-stuck-files-win11-download-guide-2/"><u>Breaking Chains of Stuck Files: WIN11 Download Guide (2)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-broadcast-brilliance-with-cost-effective-templates/"><u>[New] 2024 Approved  Broadcast Brilliance with Cost-Effective Templates</u></a></li>
<li><a href="https://windows11.techidaily.com/linux-vs-windows-a-comprehensive-gamers-guide/"><u>Linux Vs. Windows: A Comprehensive Gamer's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/image-integration-insights-securely-stashing-files-on-windows-11/"><u>Image Integration Insights: Securely Stashing Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-how-to-seamlessly-capture-igtv-5-windows-and-mac-downloading-tips-for-2024/"><u>[Updated] How to Seamlessly Capture IGTV  5 Windows & Mac Downloading Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-win11-outshines-macos-on-key-fronts/"><u>How Win11 Outshines MacOS on Key Fronts</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-find-a-group-policy-on-windows/"><u>3 Ways to Find a Group Policy on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-troubleshooting-for-winscombsvc-error/"><u>Essential Troubleshooting for WinScombSvc Error</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-windows-media-player-in-a-swift-manner/"><u>Activating Windows Media Player in a Swift Manner</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-running-handbrake-on-widows/"><u>Mastering the Art of Running HandBrake on Widows</u></a></li>
<li><a href="https://windows11.techidaily.com/5-reasons-to-steer-clear-from-inexpensive-windows-keys/"><u>5 Reasons to Steer Clear From Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
</ul></div>
