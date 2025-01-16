---
title: Dealing with FileHistoryFaults in Windows OS
date: 2025-01-13T05:56:55.194Z
updated: 2025-01-16T01:27:56.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dealing with FileHistoryFaults in Windows OS
excerpt: This Article Describes Dealing with FileHistoryFaults in Windows OS
keywords: WinOSFileHistoryIssues,Fixing FileHistoryErrors,Windows FileHistoryTroubleshoot,Resolve WinOSBackupFaults,Correcting Windows SaveError,Addressing OS BackupFailure,Repairing FileHistoryWindows
thumbnail: https://thmb.techidaily.com/a362218194355c666b0860326aa79761dfe27d2518f12f424f4610cd1ffe517b.jpg
---

## Dealing with FileHistoryFaults in Windows OS

 File History is a nifty feature on Windows that allows you to back up your important files and folders to an external drive. Although the feature works as expected most of the time, it can occasionally trouble you with errors like the “We found errors in your File History settings” on Windows.

 Let’s see how you can resolve this error and get the File History feature to work again on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Restart the File History Service

 File History Service is a small program that needs to be running in the background for the File History feature to work. If this service is experiencing any problems, you could run into the "We found errors in your File History settings" error. In most cases, you can fix any temporary issues with File History Service by simply restarting it.

To restart the File History Service in Windows:

1. Right-click on the**Start icon** and select**Run** from the resulting menu.
2. Type**services.msc** in the text box and press**Enter** .
3. In the Services windows, scroll down to locate**File History Service** . Right-click on it and select**Restart** . If the service is not running, select**Start** .  
![Restart File Hisotry Service Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-file-hisotry-service-windows.jpg)

## 2\. Disconnect and Reconnect the Backup Drive

 Connection problems with your external drive can also cause Windows to display the "We found errors in your File History settings" error. If it’s nothing major, you should be able to resolve the error by disconnecting and reconnecting your backup drive.

 While you're at it, try using a different USB port. This will help you determine if there’s a [problem with the USB port](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) you’re using. If you suspect a port is malfunctioning, check out how to diagnose and fix a faulty USB port on Windows.

## 3\. Re-Select the Backup Drive and Restart File History

 Next, you can try re-selecting your backup drive in File History settings and see if that helps. Here are the steps for the same.

1. Press**Win + R** or use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**control** in the box and press**Enter** .
3. Click the**View by** drop-down menu and select**Large icons** .
4. Select**File History** from the Control Panel menu items.
5. Click the**Select drive** option from the left sidebar.
6. Select your preferred drive from the list and click**OK** .  
![Select File History Drive Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/select-file-history-drive-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After selecting your preferred drive, you’ll have to restart the File History feature on Windows. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or use the**Win + S** keyboard shortcut to open the search menu.
2. Type**file history** in the search box and select the first result that appears.
3. In the Control Panel window that opens, click the**Turn off** button.
4. Wait for a few seconds and click the**Turn on** button.  
![Turn On File History in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-file-history-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the error message persists even after this, you can try using a different drive for the File History backup and see if that works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Reset File History

 Finally, if nothing else works, resetting File History may be your only option. You can accomplish this by deleting the File History data files from your computer.

 In order to delete File History data files, you’ll have to ensure that your PC is configured to [show hidden files and folders on Windows](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) . Here’s how to check.

1. Open the Windows search menu.
2. Type**File Explorer Options** in the search box and press**Enter** .
3. Switch to the**View** tab and check the**Show hidden files, folders, and drives** option.
4. Hit**Apply** followed by**OK** .

 Now, delete the File History data from your system by following the steps below.

1. Press**Win + E** to open File Explorer.
2. Type the following path in the File Explorer’s address bar and press**Enter** .  
`%UserProfile%\AppData\Local\Microsoft\Windows\FileHistory`
3. Press**Ctrl + A** to select all the folders and click the**trash icon** at the top to delete them.  
![Delete File Hisotry AppData](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/delete-file-hisotry-appdata.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing File History Errors on Windows

 After you apply the fixes listed above, the File History error should no longer bother you.

 Tired of dealing with File History errors on your Windows device? It might be a good idea to use a cloud storage service or third-party backup software to protect your important data.

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-the-ultimate-roadmap-to-proficiency-in-lut-construction/"><u>[New] 2024 Approved The Ultimate Roadmap to Proficiency in LUT Construction</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-dive-into-fun-snapchats-world-of-cartoon-lenses/"><u>[New] Dive Into Fun Snapchat's World of Cartoon Lenses</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-harmonize-your-listens-the-complete-path-to-youtube-playlist-making-webmobile/"><u>[Updated] 2024 Approved Harmonize Your Listens The Complete Path to YouTube Playlist Making (Web/Mobile)</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-level-strategies-for-mastering-windows-voice-access/"><u>Expert-Level Strategies for Mastering Windows Voice Access</u></a></li>
<li><a href="https://techidaily.com/how-to-erase-apple-iphone-14-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Apple iPhone 14 Data Permanently | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-get-your-counter-strike-global-offensive-microphone-up-and-running-again/"><u>How to Get Your Counter Strike Global Offensive Microphone Up and Running Again!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-recover-from-network-not-found-error-windows/"><u>How to Recover From 'Network Not Found' Error Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-oneplus-ace-2-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on OnePlus Ace 2 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-windows-extender-lowering-cpu-demand/"><u>Minimizing Windows Extender: Lowering CPU Demand</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-dns-cache-a-quick-tutorial-for-windows-users/"><u>Resetting DNS Cache: A Quick Tutorial for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-dormant-wsreset-utility-on-computers/"><u>Restoring Dormant WSReset Utility on Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-monitorscape-crafting-individual-themes-for-each-window-of-win-1011/"><u>Tailored Monitorscape: Crafting Individual Themes for Each Window of Win 10/11</u></a></li>
<li><a href="https://fox-useful.techidaily.com/ultimate-guide-to-cropping-videos-perfectly-for-instagram/"><u>Ultimate Guide to Cropping Videos Perfectly for Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/updating-old-pcs-think-beyond-windows/"><u>Updating Old PCs? Think Beyond Windows</u></a></li>
<li><a href="https://data-wizards.techidaily.com/virtual-offering-guarantee/"><u>Virtual Offering Guarantee</u></a></li>
</ul></div>

