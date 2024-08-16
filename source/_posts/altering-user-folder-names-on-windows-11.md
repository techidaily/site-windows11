---
title: Altering User Folder Names on Windows 11
date: 2024-08-15T15:58:45.986Z
updated: 2024-08-16T15:58:45.986Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering User Folder Names on Windows 11
excerpt: This Article Describes Altering User Folder Names on Windows 11
keywords: Win11 Change UserFolderNames,WindowUserFolderRenaming,WindowsUserNameChange,SystemUserFoldersEdit,AlterUserFolderWindows11,FolderNamingWin11Users,RenamingWindowsUserPaths
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Altering User Folder Names on Windows 11

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, click on **I don’t have this person’s sign-in information.**  
![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)

1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the User Profile Folder Name Using the Registry Editor

 You can modify the registry entries associated with your user account to change the user profile folder name in Windows 11\.

 This process involves modifying your registry entries, so we recommend you create a restore point. You can [use the restore point to restore your PC](https://www.makeuseof.com/use-system-restore-windows/) if something goes wrong during the process.

 To change the user profile folder name:

1. Sign out from your current user account and log in with a built-in or newly created administrator account
2. Next, press **Win + R** to open the **Run** dialog.
3. Type **netplwiz** and click **OK** to open the **User Accounts** dialog.
4. Here, select your **user account** and click on **Properties**.  
![User accounts properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-accounts-properties.jpg)
5. In the **User Properties** dialog, you’ll see your **User name** and **Full name.**

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
2. Close the **User Account** dialog and perform a restart.
3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
`wmic useraccount get name,SID`
5. Here, note the **SID** for the user account you want to change the user profile folder name. In this case, the **SID** for the username **tashr** is **S-1-5-21-200486166-247335145-1769094253-1001.**

 Now that we have the SID, we must enter it into the Registry Editor. To do that, follow these steps:

1. Press **Win + R**, type **regedit,** and click **OK** to open **Registry Editor.**
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`
3. Inside the **ProfileList** key, locate and click on the key name identical to the **SID** you noted earlier.
4. In the right pane, right-click on **ProfileImagePath** value and select **Modify**.  
![Modify profile image path in the registry editor.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/modify-profile-image-path-registry-editor.png)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
5. Enter a name you want for the profile folder and click **OK**.  
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://driver-download.techidaily.com/download-intel-cpu-drivers-quickly-and-easily/"><u>[DOWNLOAD] Intel CPU Drivers | Quickly & Easily</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-addressing-missing-thumbnails-in-youtube-shorts-for-2024/"><u>[New] Addressing Missing Thumbnails in YouTube Shorts for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-comparative-overview-of-googles-ar-stickers-and-its-counterparts/"><u>[New] Comparative Overview of Google's AR Stickers & Its Counterparts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-engaging-audiences-through-vimeo-shares/"><u>[New] Engaging Audiences Through Vimeo Shares</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-exciting-quests-selecting-the-top-10-adventure-gaming-treasures-for-2024/"><u>[New] Exciting Quests  Selecting the Top 10 Adventure Gaming Treasures for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-flight-paths-revealed-full-review-of-dji-phantom-4/"><u>[New] Flight Paths Revealed  Full Review of DJI Phantom 4</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-digital-sharpening-from-youtube-shorts-to-mp4/"><u>[New] In 2024, Digital Sharpening  From YouTube Shorts to MP4</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-top-10-best-photo-watermarking-software-you-should-try/"><u>[New] In 2024, Top 10 Best Photo Watermarking Software You Should Try</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-innovative-audio-enhancements-for-youtube-creators/"><u>[New] Innovative Audio Enhancements for YouTube Creators</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-iphoneandroid-screen-capture-for-google-meet-participants/"><u>[New] IPhone/Android Screen Capture for Google Meet Participants</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-unveiling-the-most-effective-internet-tools-for-caption-perfection/"><u>[New] Unveiling the Most Effective Internet Tools for Caption Perfection</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-apex-fusion-hubs-all-in-one-4k-multi-touch-desktops/"><u>[Updated] Apex Fusion Hubs  All-in-One 4K Multi-Touch Desktops</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-engaging-audiences-with-creative-text-features/"><u>[Updated] Engaging Audiences with Creative Text Features</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-zoom-like-a-pro-top-video-gear-for-slow-motion-effects/"><u>[Updated] In 2024, Zoom Like a Pro  Top Video Gear for Slow Motion Effects</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-iphone-screen-recording-made-simple-for-2024/"><u>[Updated] Iphone Screen Recording Made Simple for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-transforming-realities-into-engaging-documentaries-through-scriptwriting-for-2024/"><u>[Updated] Transforming Realities Into Engaging Documentaries Through Scriptwriting for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-navigate-the-excellent-world-of-top-vr-cycling/"><u>2024 Approved  Navigate the Excellent World of Top VR Cycling</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-swiftly-share-your-fb-films-in-whatsapp-messages/"><u>2024 Approved  Swiftly Share Your FB Films in WhatsApp Messages</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-speech-recognition-startup-error-windows/"><u>Addressing 'Failed' Speech Recognition Startup Error Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-asymmetric-windows-headphone-output/"><u>Adjusting Asymmetric Windows Headphone Output</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-email-attachment-openness-ms-word-read-mode-only/"><u>Automate Email Attachment Openness: MS Word Read Mode Only</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-edge-how-pcs-beat-macs-in-9-aspects/"><u>Decoding the Edge: How PCs Beat Macs in 9 Aspects</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-access-to-windows-print-services-dashboard/"><u>Demystifying Access to Windows Print Services Dashboard</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pathways-to-windows-performance-details/"><u>Efficient Pathways to Windows Performance Details</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-electrical-footprint-of-your-windows-device/"><u>Exploring the Electrical Footprint of Your Windows Device</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-achievements-to-your-retro-games-with-retroarch/"><u>How to Add Achievements to Your Retro Games With Retroarch</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediinate-and-rectify-the-iomap64-system-freeze-error/"><u>How To Immediinate and Rectify the IOMap64 System Freeze Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-wsreset-process-in-windows/"><u>How to Reactivate a Non-Operational WSReset Process in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-down-elusive-control-panel-options-on-windows-11/"><u>Hunt Down Elusive Control Panel Options on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-funimate-unlocking-the-secrets-of-easy-downloads/"><u>In 2024, Funimate  Unlocking the Secrets of Easy Downloads</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-fv-downloader-for-social-networking-videos/"><u>In 2024, FV-Downloader for Social Networking Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-path-resetting-windows-preferences-post-reboot/"><u>Instructional Path: Resetting Windows Preferences Post-Reboot</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-a-new-search-option-in-windows-11-task-manager/"><u>Introducing a New Search Option in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pixelpun-factory-for-2024/"><u>PixelPun Factory for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/prime-choices-top-10-best-vectors-websites/"><u>Prime Choices  Top 10 Best Vectors Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-0x80d03801-on-microsoft-store-pcs/"><u>Resolving Error 0X80D03801 on Microsoft Store PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-schedule-your-visit-at-the-apple-stores-genius-bar/"><u>Steps to Schedule Your Visit at the Apple Store's Genius Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workspace-incorrante-folders-into-context-menu/"><u>Streamline Your Workspace: Incorrante Folders Into Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-game-drives-in-xbox-app/"><u>The Ultimate Guide to Game Drives in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-tutorial-for-managing-archive-files-via-cmd/"><u>The Ultimate Tutorial for Managing Archive Files via CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-to-validate-windows-11-activation/"><u>Three Steps to Validate Windows 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-integrating-alternative-antiviruses-with-ms-defender/"><u>Tips for Integrating Alternative Antiviruses with MS Defender</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/0-asmr-youtubers-to-watch/"><u>Top 20 ASMR Youtubers to Watch</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-app-install-in-windows-store/"><u>Troubleshooting Failed App Install in Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-your-potential-7-proven-techniques-to-master-windows-based-studying/"><u>Unlock Your Potential: 7 Proven Techniques to Master Windows-Based Studying</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-archive-file-history-in-windows-11/"><u>Unlocking the Archive: File History in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722890483532-what-to-expect-the-next-gen-google-pixel-timepiece-price-launch-window-and-potential-specs-leaked/"><u>What to Expect: The Next-Gen Google Pixel Timepiece – Price, Launch Window & Potential Specs Leaked</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-second-shuffle-solved/"><u>Windows Second Shuffle Solved</u></a></li>
</ul></div>
