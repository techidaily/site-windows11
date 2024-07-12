---
title: "Enhancing Productivity with Cloud Services: Dropbox/Google on C"
date: 2024-07-11T22:12:40.383Z
updated: 2024-07-12T22:12:40.383Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enhancing Productivity with Cloud Services: Dropbox/Google on C"
excerpt: "This Article Describes Enhancing Productivity with Cloud Services: Dropbox/Google on C"
keywords: Cloud-Based Productivity,Google Drive Impact,Dropbox Work Efficiency,C Drive Cloud Solutions,Online File Sharing Pros,Cloud Storage Benefits,C
thumbnail: https://thmb.techidaily.com/18e0761348cb4d28e3480c4ed08a893497db31dc39159b03c85adcc25dd9aaa4.jpg
---

## Enhancing Productivity with Cloud Services: Dropbox/Google on C

 Today, cloud storage solutions are an essential part of our daily life, to the point that all major OSes come with support for such cloud services "baked in".

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!

## Common Cloud Storage Issues You May Encounter on Windows

 Dropbox, Google Drive, and similar cloud storage/sync services are easy to access from a web browser or the OS's default file manager. When you demand more than merely accessing your files, though, you may run into issues.

* Dropbox is accessible from a link in the file manager that brings you to its actual local folder, inside which your files are synced. Alternatively, you can visit that folder yourself. Dropbox cannot be "accessible through a letter" by default.
* Google Drive offers the option to map every account to a drive letter. However, try to access the contents of the virtual drive "behind" its "official" drive letter. Instead of your Google Drive files, you'll find a link to its local folder.
* Other alternatives may be even worse, with some only accessible locally through their custom clients.

 So, is it impossible to have your cloud storage account's "root folder" accessible directly from a drive letter?

 Thankfully, you can use a third-party solution for that. They're usually straightforward and can make your cloud storage "behave" like a normal drive on your computer. Still, you might want to avoid such apps for various reasons.

* Most cost money or are ad-supported.
* You'll be giving access to your data to another third party (on top of the cloud storage provider).
* The more apps and services that have access to your files, the higher the chances they'll fall into the wrong hands after a security breach.
* Extra software and services translate to increased complexity and potential for failure: some files may not sync when you expect them, metadata might get lost, etc.

 The major case against them is that there's no reason to use more software than you need.

## Why Not Just Use Google Drive's Folders?

 Let's see how Google Drive fails to offer proper access to its local folder through a letter.

1. Right-click on **Google Drive's icon** on the tray, click on the **cog icon** on the top right to access its menu and choose **Preferences**. Click on the **cog icon** in Google Drive Preferences window to access your account's settings. Ensure there's a drive letter assigned to your Google Drive.  
![Google Drive Settings Drive Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-settings-drive-letter.jpg)
2. Visit the actual **drive letter** through any file manager and wonder how there's a "My Drive" folder instead of your files.  
![Google Drive Actual Drive Letter Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-actual-drive-letter-contents.jpg)
3. Try "entering" that folder and marvel at how the **path** changes to the true one where Google Drive's folder is stored, potentially breaking some apps.  
![Google Drive True Folder Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/google-drive-true-folder-path.jpg)

 Now, let's fix, or rather "sidestep" this little issue by exploiting how network folders work on Windows.

## How to Set Up Windows Shared Folders

 The first part of the process will be "sharing" the actual folder used by the cloud storage service that we want to access directly from a drive. Don't worry; you won't be sharing anything with anyone (apart from the cloud service provider where you already keep your files).

 For this example, we'll swap cloud services and "do Dropbox", but you can use the same process with any cloud storage service's local folder.

1. Run your favorite file manager and visit the path "directly above" your cloud storage folder (so that you can see it in your file manager).  
![Dropbox Folder In Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-in-windows-explorer.jpg)
2. Right-click on the folder and choose **Properties**.  
![Dropbox Folder Windows Explorer Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties.jpg)
3. Move to the **Sharing** tab and enable sharing for your folder. If you need help, check our guide on [how to access shared folders on Windows](https://www.makeuseof.com/unable-to-access-shared-folder-windows/).  
![Dropbox Folder Windows Explorer Properties Sharing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dropbox-folder-windows-explorer-properties-sharing.jpg)

## How to Assign Letters to “Networked” Cloud Storage Folders

 Your folder should be accessible "as a share" by now, but it still isn't mapped to a letter. For that, we'll use Windows' ability to assign letters to "network drives" for easy access.

 Thankfully, Windows also recognizes the shared folder as "a network drive", even if it's stored locally.

1. Type "**\\\\localhost**" in your file manager's location bar to see all the shared folders on your local PC. Among them should be your newly shared cloud storage folder.  
![Windows Explorer Localhost Shared Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders.jpg)
2. Right-click on it and choose **Map network drive**.  
![Windows Explorer Localhost Shared Folders Menu Map Network Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-localhost-shared-folders-menu-map-network-drive.jpg)
3. Choose the **letter** you want to assign to your cloud storage folder from the drop-down menu next to **Drive**. Click **Finish** to apply the change.  
![Windows Explorer Map Network Drive Letter Selection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-map-network-drive-letter-selection.jpg)
4. Visit your "new drive" using the letter you assigned, and you should have direct access to your cloud storage's contents.  
![Windows Explorer Direct Access To Dropbox Folder From Letter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/windows-explorer-direct-access-to-dropbox-folder-from-letter.jpg)

 The above implies that you'll set up your cloud storage client to fully sync all files and folders/keep them stored locally.

## What About Using Subst?

 You may wonder why we didn't go with subst for this guide. Indeed, subst is so useful that we've made sure to include it on our list of [the essential Windows CMD commands you should know](https://www.makeuseof.com/tag/essential-windows-cmd-commands/). But what is it, how can it help, and how do you use it?

 Open Windows Search with **Win + S**, search for "**Terminal**" or "**PowerShell**", and choose **Run as Administrator**. There, use subst like:

subst DRIVE_LETTER: FULL:\PATH\TO\FOLDER

 For example, to map the folder "c:\\Cloud Drives\\Dropbox" to the letter "Z", the command would be:

subst Z: "C:\Cloud Drives\Dropbox"

 After that, your folder should be accessible from the drive you assigned to it. If the change isn't apparent immediately, log off and back on or restart your PC.

## A Local Folder for Your Cloud Storage on Windows

 Thanks to Microsoft's somewhat square logic of "if it's a shared folder, you can map it, no matter where it is", it's easy to access your cloud storage folders directly from a drive letter. All it takes is to share them with yourself!

 Of course, power users would probably prefer to "subst them" to submission. Strangely, many forget that "subst" can also be used with cloud storage folders. Despite your chosen path, we can probably mark this little annoyance when using cloud storage folders with a "problem solved."

 Cloud storage services are easier than ever to access, they offer free storage, and as a bonus, they can make your life miserable if you want to access anything stored there using a quirky app instead of your web browser.

 That's why you can find extra third-party tools that assist in using cloud storage "as a normal drive". For this article, though, we'll do the same by exploiting Windows' built-in shared folders functionality!



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-locked-out-of-iphone-7-5-ways-to-get-into-a-locked-iphone-7-by-drfone-ios/"><u>In 2024, Locked Out of iPhone 7? 5 Ways to get into a Locked iPhone 7</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-4-simple-methods-for-making-a-high-quality-recap-video/"><u>Updated 4 Simple Methods for Making a High-Quality Recap Video</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-realme-12-pro-5g-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Realme 12 Pro 5G Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-master-the-use-of-winservicesexe-on-windows/"><u>How to Master the Use of Winservices.exe on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-fixing-exit-code-errors/"><u>Mastering Windows: Fixing Exit Code Errors</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-how-to-clear-out-conversations-swiftly-on-your-discord-servers/"><u>[Updated] 2024 Approved  How to Clear Out Conversations Swiftly on Your Discord Servers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-successfully-upgrade-to-virtualbox-70-on-windows-11-pcs/"><u>How to Successfully Upgrade to VirtualBox 7.0 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-nuances-7-fixes-for-connectivity-in-obs-studio/"><u>Navigating Network Nuances: 7 Fixes for Connectivity in OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-second-screen-harmony-windows-plus-android-tablets/"><u>Mastering Second Screen Harmony: Windows + Android Tablets</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-innovative-techniques-for-recording-instagram-story-highlights/"><u>2024 Approved  Innovative Techniques for Recording Instagram Story Highlights</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-recovering-battlenet-login-on-pcs/"><u>Mastering the Art of Recovering Battle.net Login on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-connectivity-for-print-devices-on-pcs/"><u>How to Reestablish Connectivity for Print Devices on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-desktop-input-on-your-win-device/"><u>How to Turn Off Desktop Input on Your Win Device</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastering-instagrams-square-shots-with-imovie/"><u>Mastering Instagram's Square Shots with iMovie</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-absentee-application-association-windows/"><u>How To Restore Absentee Application Association (Windows)</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-transform-youtube-live-with-these-must-know-secrets-for-2024/"><u>Updated Transform YouTube Live with These Must-Know Secrets for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-apps-to-a-new-windows-11-pc/"><u>How to Transfer Apps to a New Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://vp-tips.techidaily.com/expert-recommendations-top-8-free-srt-apps-reviewed/"><u>Expert Recommendations  Top 8 Free SRT Apps Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-system-reviving-windows-11s-error-detection/"><u>Jumpstart Your System: Reviving Windows 11'S Error Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-backupmasters-expert-verdict/"><u>[Updated] In 2024, BackUpMasters Expert Verdict</u></a></li>
</ul></div>
