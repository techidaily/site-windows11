---
title: "Restoring Lost NVIDIA Configuration: A Guide for WinX Users"
date: 2024-07-11T21:11:17.191Z
updated: 2024-07-12T21:11:17.191Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Restoring Lost NVIDIA Configuration: A Guide for WinX Users"
excerpt: "This Article Describes Restoring Lost NVIDIA Configuration: A Guide for WinX Users"
keywords: WinX Nvidia Settings,Restore Graphics Config,Nvidia Windows Fix,Reinstall Nvidia Driver,WinX Graphics Update,XPedia,Gain Lost NVidia Control
thumbnail: https://thmb.techidaily.com/be34f09b3263dabe58e7e8e9b611840eed5d78451bd041646a395d4031103684.jpg
---

## Restoring Lost NVIDIA Configuration: A Guide for WinX Users

 GeForce Experience is software with which users can usually optimize their games. However, some GeForce Experience users can’t optimize games with that software because of an “unable to retrieve settings” error. Some users see that error message when they click games’ thumbnails in GeForce Experience.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.

## 1\. Run GeForce Experience With Administrative Rights

 A few players have said running GeForce Experience with admin rights resolved the “Unable to retrieve settings” error for them. So, that’s a simple resolution worth trying. To see if that works for you, bring up the Windows search tool and input GeForce Experience. Then right-click the GeForce Experience search result to select **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option4.jpg)

 If that works, set GeForce Experience to always run with elevated user rights. Then you won’t need to select the **Run as administrator** option all the time. Our guide for [always running apps as an administrator on Windows](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) tells you how to set software packages to start with elevated permissions.

## 2\. Remove Scan Locations

 Some GeForce Experience users confirm that removing scan locations and rescanning fixes the “Unable to retrieve settings” error. This is how you can remove scan locations in GeForce Experience:

1. Open the GeForce Experience window.
2. Click the **Settings** button by your user account name.  
![The Settings menu button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/settings-button.jpg)
3. Select the **Games & Apps** tab.
4. Then select a scan location and click **Remove**. Repeat this step to remove all scan locations shown.  
![The Remove button for scan locations](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-button.jpg)
5. Press the **Scan Now** button to rescan.

## 3\. Delete the CefCache Folder

 CefCache is a GeForce Experience folder that stores cached data. GeForce Experience optimization issues can arise when that cache includes corrupted configuration files. You might be able to resolve the “Unable to retrieve settings” error by deleting the CafCache folder like this:

1. Ensure GeForce Experience isn’t already running by closing it on the taskbar and the system tray. Right-click the NVIDIA system tray and select **Exit** to close GeForce Experience there.
2. Open File Explorer (press **Win + E**) and input this path in the folder address bar:  
`C:\Users\<user folder>\AppData\Local\NVIDIA Corporation\NVIDIA GeForce Experience`  
![The CefCache folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/cefcache-folder.jpg)
3. Right-click the **CefCache** folder to select **Delete**.  
![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-button.jpg)
4. Then launch the GeForce Experience software.
5. Input your GeForce Experience account details again and click **Log In**.

## 4\. Restore Default NVIDIA 3D Settings

 Restoring the NVIDIA 3D Settings to default is another potential fix for the “Unable to retrieve settings” error that has worked for some users. Applying this resolution will reset all 3D settings you’ve changed in the NVIDIA Control panel to a default configuration. You can apply this potential resolution as follows:

1. Right-click on the NVIDIA logo inside the system tray area to select **Control Panel**.
2. Next, select **Manage 3D** settings in the NVIDIA Control Panel.
3. Click **Restore** on the **Global Settings** tab.  
![The Restore button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/restore-button.jpg)
4. Select **Yes** to reset the settings.

## 5\. Delete the Steam User Data

 The “Unable to retrieve settings” error can arise for Steam games because of a data conflict with Steam. Players have confirmed erasing data in a Steam userdata subfolder works for fixing this issue. So, that’s a possible resolution recommended for all players who’ve got Steam installed. Clear Steam’s userdata folder like this:

1. Simultaneously press **Win + X** and select the File Explorer shortcut.
2. Input this userdata folder path in Explorer’s address bar:  
`C:\Program Files\Steam\userdata`  
![Steam's userdata folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/userdata-folder.jpg)
3. Right-click a subfolder that doesn’t have any numbers in its name within the userdata folder and select **Delete**.
4. Repeat the previous step to delete all subfolders in userdata with non-numeric titles like anonymous, etc.

## 6\. Perform Some Generic Windows Fixes

 There are a few Windows-based fixes you can try to get rid of this error.

### Erase Temporary Windows Data

 The Temp folder stores temporary files. GeForce Experience users confirm deleting data in that Temp folder can fix the “Unable to retrieve settings” issue. So, try eradicating data in that folder with one of the methods in our guide to [deleting temporary files](https://www.makeuseof.com/windows-11-delete-temporary-files/)[in Windows 11](http://www.makeuseof.com/windows-11-delete-temporary-files/).

![disk-cleanup-tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disk-cleanup-tool.jpg)

### Install the Latest NVIDIA Driver for Your GPU

 Although less likely, corrupted NVIDIA GPU driver files can feasibly cause the “Unable to retrieve settings” error to arise. In this case, installing the latest NVIDIA graphics drivers could be a solution for some users. Uninstall your PC’s current NVIDIA graphics driver and install the latest one by downloading it from the NVIDIA website.

 Follow the instructions in our guide to [installing and cleanly reinstalling GPU drivers](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) to apply this potential fix with the DDU software.

![The NVIDIA driver downloads page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-driver-downloads.jpg)

### Disable Third-Party Antivirus Tools

 If you’ve got third-party antivirus software installed on your Windows PC, that might be blocking GeForce Experience from accessing certain folders and optimizing settings. BitDefender Total Security is one antivirus utility widely confirmed to cause this issue. Those users who've confirmed that needed to disable BitDefender to resolve the issue.

 So, try disabling BitDefender or any other third-party antivirus software to see if that makes a difference. You can disable real-time scanning by right-clicking an antivirus tool in the Windows system tray and selecting to disable or turn it off from the context menu. Select to temporarily disable the antivirus scanning for about an hour or so and then open GeForce Experience.

### Reinstall GeForce Experience

 Reinstalling GeForce Experience might be a necessary potential fix for the “Unable to retrieve files” error if others fail. That will replace any corrupted GeForce Experience files that could be causing glitches. Remove GeForce Experience with a method in this guide to [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/).

![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option3.jpg)

 Restart the PC before reinstalling GeForce Experience. Then head over to this [GeForce Experience](https://www.nvidia.com/en-gb/geforce/geforce-experience/download/) webpage and click **Download Now**. Open the folder your browser usually downloads files to and double-click the GeForce Experience setup wizard. Go through the installer’s steps to reinstall the software.

## Optimize Your Games With GeForce Experience

 Many GeForce Experience users have fixed the “unable to retrieve settings” error in Windows with the resolutions above. You may have to try applying a few of them to get the issue sorted since there are quite a few potential causes for this error. Then you can quickly and fully optimize all your favorite games with GeForce Experience again.

 However, remember that there are numerous ways to optimize Windows games without GeForce Experience. You can optimize gaming by enabling or even disabling certain Windows features and closing background apps. Plus, you can manually adjust the graphical settings in the NVIDIA Control Panel or games to optimize Windows gaming.

 Consequently, users can’t select the Optimize option for games that show the “unable to retrieve settings” error. That’s a bit annoying for players seeking optimal gaming performance. This is how you can fix GeForce Experience’s “unable to retrieve settings” error within Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/essential-tips-how-to-activate-intel-wireless-functionality/"><u>Essential Tips: How to Activate Intel Wireless Functionality</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-10-excellent-free-video-compressors-compatible-with-windows-10/"><u>New 2024 Approved 10 Excellent Free Video Compressors Compatible with Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-rectify-windows-security-faults/"><u>Comprehensive Guide to Rectify Windows Security Faults</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/comprehensive-directory-of-inexpensive-stock-images-for-2024/"><u>Comprehensive Directory of Inexpensive Stock Images for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Life360 Notify When You Log Out On Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-fn-keys-to-maximize-pc-efficiency-in-wins/"><u>Customizing FN Keys to Maximize PC Efficiency in Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-harmony-seamlessly-blending-image-and-zip-archives-win1011/"><u>Hidden Harmony: Seamlessly Blending Image and ZIP Archives WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-timers-fixing-scheduler-errors/"><u>Master Your Timers: Fixing Scheduler Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-make-win11s-canvas-come-alive-the-guide-to-creating-intriguing-ai-images-via-paint-tool-sai/"><u>How to Make Win11's Canvas Come Alive: The Guide to Creating Intriguing AI Images via Paint Tool SAI</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-android-and-lightroom-review-a-full-examination/"><u>[New] Android & Lightroom Review  A Full Examination</u></a></li>
<li><a href="https://windows11.techidaily.com/microsofts-helpers-quick-fixes-for-window-woes/"><u>Microsoft's Helpers: Quick Fixes for Window Woes!</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-5-best-slow-motion-cameras/"><u>[New] 5 Best Slow Motion Cameras</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dream-team-top-windows-apps-for-a-winning-start/"><u>Digital Dream Team: Top Windows Apps for a Winning Start</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-guide-to-the-best-10-websites-for-obtaining-vintage-and-contemporary-montage-sounds-for-2024/"><u>Updated The Ultimate Guide to the Best 10 Websites for Obtaining Vintage and Contemporary Montage Sounds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-energy-waste-without-slowing-down-games/"><u>Cutting Down Energy Waste Without Slowing Down Games</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-combatting-windows-not-found-problem/"><u>Essential Tips: Combatting Windows Not Found Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-the-0x8004def5-onedrive-error-code-on-windows-11/"><u>9 Ways to Fix the 0X8004def5 OneDrive Error Code on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-removing-windows-11s-taskbar-chatter-affects-you-the-user/"><u>How Removing Windows 11'S Taskbar Chatter Affects You, The User?</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-managing-comic-files-in-windows-11/"><u>Comprehensive Guide to Managing Comic Files in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-updates-0x80242016-hurdles/"><u>Avoiding Windows Update's 0X80242016 Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-in-passwords-7-best-free-generation-tools-for-windows/"><u>Get Ahead in Passwords: 7 Best Free Generation Tools for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-desktop-space-win-os-snap-configurations/"><u>Personalize Your Desktop Space: Win OS Snap Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-handle-iomap64sys-failures-in-winos/"><u>How To Correctly Handle IOMap64.sys Failures in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-experience-adding-uninstall-shortcut-in-windows-10/"><u>Optimize Your Experience: Adding Uninstall Shortcut in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-error-code-x80131500-at-store/"><u>Breaking Down Error Code: X80131500 at Store</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-bt-speakers-volume-level-on-windows-11-pcs/"><u>Optimizing BT Speakers Volume Level on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-color-to-extend-volume-option-in-diskmgmt/"><u>Bring Back Color to Extend Volume Option in DiskMgmt</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Vivo S17e | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-using-windows-11s-compatibility-fixer/"><u>Essential Guide to Using Windows 11’S Compatibility Fixer</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-non-admin-privilege-levels-in-windows-os/"><u>Adjusting Non-Admin Privilege Levels in Windows OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-unveiling-the-ultimate-strategy-to-record-your-favorite-streamed-series-hulu/"><u>[Updated] In 2024, Unveiling the Ultimate Strategy to Record Your Favorite Streamed Series (Hulu)</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-diablo-gameplay-enthusiasts/"><u>Essential Tips for Diablo Gameplay Enthusiasts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/deciphering-your-affection-filmoras-top-10-features/"><u>Deciphering Your Affection  Filmora’s Top 10 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-clutter-software-uninstallation-tricks-for-windows-11-106-chars/"><u>Eliminating Clutter: Software Uninstallation Tricks for Windows 11 (106 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-fully-erase-wsl-from-windows-11-systems/"><u>Expert Tips to Fully Erase WSL From Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/a-stepwise-guide-to-banishing-the-onedrive-icon-from-explorer/"><u>A Stepwise Guide to Banishing the OneDrive Icon From Explorer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/refining-images-how-to-use-the-eraser-tool-in-psx-for-2024/"><u>Refining Images  How to Use the Eraser Tool in PSX for 2024</u></a></li>
</ul></div>
