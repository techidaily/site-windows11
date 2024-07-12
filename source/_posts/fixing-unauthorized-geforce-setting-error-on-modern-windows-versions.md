---
title: Fixing Unauthorized GeForce Setting Error on Modern Windows Versions
date: 2024-07-11T21:51:52.891Z
updated: 2024-07-12T21:51:52.891Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Unauthorized GeForce Setting Error on Modern Windows Versions
excerpt: This Article Describes Fixing Unauthorized GeForce Setting Error on Modern Windows Versions
keywords: Fix GeForce Error,Unauthorized Settings,Nvidia GeForce Fix,Stop Error Messages,Resolve Graphics Conflict,GeForce Update Windows,Remove Error Patches
thumbnail: https://thmb.techidaily.com/74a4a1093c21fbed5ca77d48b3d1459dd3aa5036bc18134bd1752c7ab7f277b6.jpg
---

## Fixing Unauthorized GeForce Setting Error on Modern Windows Versions

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
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-vivo-x100-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-avoid-unsolicited-podcast-recommendations-on-spotify-app/"><u>In 2024, Avoid Unsolicited Podcast Recommendations on Spotify App</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-punchy-prowess-vs-online-influence/"><u>2024 Approved  Punchy Prowess Vs Online Influence</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-gaming-glory-resolve-full-screen-woes-in-sonic-on-windows-11/"><u>Guaranteeing Gaming Glory: Resolve Full-Screen Woes in Sonic on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-discovering-the-leading-9-ai-voice-models-to-transform-your-day/"><u>New 2024 Approved Discovering the Leading 9 AI Voice Models to Transform Your Day</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediinate-and-rectify-the-iomap64-system-freeze-error/"><u>How To Immediinate and Rectify the IOMap64 System Freeze Error</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-hidden-windows-bar-when-browser-frames-are-enlarged/"><u>Fixing Hidden Windows Bar when Browser Frames Are Enlarged</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-calendar-events-iphone-11-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Retrieve Deleted Calendar Events iPhone 11? | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-a-new-search-option-in-windows-11-task-manager/"><u>Introducing a New Search Option in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-electrical-footprint-of-your-windows-device/"><u>Exploring the Electrical Footprint of Your Windows Device</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-top-4-alternatives-to-adobe-premiere-rush/"><u>In 2024, Top 4 Alternatives to Adobe Premiere Rush</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-achievements-to-your-retro-games-with-retroarch/"><u>How to Add Achievements to Your Retro Games With Retroarch</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-optimizing-youtube-content-for-instagram-platforms/"><u>[Updated] Optimizing YouTube Content for Instagram Platforms</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-xiaomi-redmi-note-13-5g-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Xiaomi Redmi Note 13 5G</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-ultimate-fix-for-instagram-video-problems-for-2024/"><u>[Updated] The Ultimate Fix for Instagram Video Problems for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-easier-than-ever-accessing-ifunnys-memetic-delights/"><u>[New] 2024 Approved  Easier Than Ever  Accessing iFunny’s Memetic Delights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unmatched-playwrights-arena/"><u>[Updated] Unmatched Playwright's Arena</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-app-when-it-cant-save-photos-or-videos-in-windows/"><u>How to Fix the Camera App When It Can't Save Photos or Videos in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-wsreset-process-in-windows/"><u>How to Reactivate a Non-Operational WSReset Process in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-path-resetting-windows-preferences-post-reboot/"><u>Instructional Path: Resetting Windows Preferences Post-Reboot</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-vivo-s17e-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Vivo S17e Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-streamlining-your-device-by-clearing-youtube-downloads/"><u>[New] Streamlining Your Device by Clearing YouTube Downloads</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-channel-trailers-that-convert-viewers-into-customers/"><u>[New] 2024 Approved  Channel Trailers that Convert Viewers Into Customers</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-down-elusive-control-panel-options-on-windows-11/"><u>Hunt Down Elusive Control Panel Options on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
</ul></div>
