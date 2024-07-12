---
title: Reducing Heavy Resource Use by News Apps in Windows OS
date: 2024-07-11T21:46:57.641Z
updated: 2024-07-12T21:46:57.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reducing Heavy Resource Use by News Apps in Windows OS
excerpt: This Article Describes Reducing Heavy Resource Use by News Apps in Windows OS
keywords: Reduce Resource In Windows News,Minimize Heavy Windows News Apps,Low-Impact News Windows Apps,Efficient Windows News Utilization,Optimal Windows News Consumption,Cut Down Resources, Windows News,Streamlined News Use in Windows
thumbnail: https://thmb.techidaily.com/c6fb0c53f67d408b9f1a8e71dd93d74b8d8f511c12090374117c9c8e1782192a.jpg
---

## Reducing Heavy Resource Use by News Apps in Windows OS

 News and Interests is a Windows 11 and 10 widget on your taskbar to show weather, sports, and news events at a glance. While it seems like a harmlessly unwanted feature, it can sometimes cause high memory usage on your computer.

 This News and Interests issue occurs due to a potential memory leak and can make your computer run slow. So, if you want to make your computer run fast again, follow these steps to fix the News and Interests high memory usage problem.

## 1\. Install Windows Update Hotfix

![windows 11 update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-update.jpg)

 Reportedly, the problem occurs due to a Windows bug. To fix the problem, Microsoft released cumulative update KB5010415 for Windows 11 and 10\. So, check if you have any pending updates for your computer and install them to see if that helps resolve the error.

To install a Windows 11 update:

1. Press**Win + I** to open**Settings** .
2. Open the**Windows Update** tab in the left pane. Check if a new update is available. If not, click on**Check for updates** .
3. Windows will scan the Microsoft servers for newer updates. If available, click on**Download & install** . Once installed, restart your computer and check for any improvements.

 You can also learn how to [manage Windows 10 updates](https://www.makeuseof.com/tag/manage-windows-update-windows-10/) to ensure your computer is constantly updated. However, if you can find this specific update on your computer, go to [Microsoft Update Catalog](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and search for the update. If available, download the update and run the installer to install it manually.

## 2\. Turn Off News and Interests

 If you don't really use the News and Interests feature, you're better off turning it off. That way, you can save on hardware resources and help your computer run faster.

### Turn Off News and Interests on Windows 10

 If you don't use News and Interests, you can turn off the feature from the Taskbar on Windows 10\. To turn off News and Interests on Windows 10:

1. Right-click on the**Taskbar** to open the context menu.  
![turn off news and interests](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interestsjpg.jpg)
2. Next, go to**News and Interests** and select**Turn Off** .

 That's it. With the**News and Interests** feature disabled, your memory usage should return to its normal range.

### Disable News and Interests on Windows 11

![disable widgets Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/disable-widgets-windows-11.jpg)

 Unfortunately, News and Interests is a core feature of Windows 11 widgets. If the lack of Widgets isn't a concern, you can [disable the Windows 11 Widget app](https://www.makeuseof.com/windows-11-disable-widgets/) to get rid of the resource-hog news feed on your computer. However, if you find the widgets useful, you must endure the News and Interests feature.

 The easiest way to disable Widgets is from the Taskbar settings. If that does not work or if your Windows 11 isn't activated, you can use Registry Editor to disable the Widgets icon from the taskbar.

 If the issue persists even after disabling News and Interest, try to [perform a Windows 11 repair reinstall](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) . During a repair reinstall, Windows will reinstall the operating system without removing your personal files and apps.

## 3\. Disable News and Interests Using the Group Policy Editor

 On Windows 11, you can configure News and Interests on the taskbar policy to disable the feature and prevent high memory usage. Group Policy Editor (GPEdit) is a Windows component and is not only available on the OS's Pro, Enterprise, and Education editions.

 If you are on Windows 11 Home, follow these steps to [enable gpedit on Windows Home](https://www.catalog.update.microsoft.com/) and then proceed with the steps below:

1. Press**Win + R** to open**Run** .
2. Type**gpedit.msc** and click**OK** to open**Group Policy Editor** .
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration > Administrative Templates > Windows Components > News and Interests`
4. In the right pane, right-click on**Enable News and Interests** **on the taskbar** policy and select**Edit** .  
![turn off news and interest disabled 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled-1.jpg)
5. Select**Disabled** and click**Apply** and**OK** to save the changes.  
![turn off news and interest disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/turn-off-news-and-interest-disabled.jpg)
6. Close Group Policy Editor and restart your computer.

 After restarting your computer, the News and Interests feature should no longer appear. Launch the task manager and check for improvements in your PC's CPU and memory usage.

## 4\. Disable News and Interests Using the Registry Editor on Windows 10

 You can disable the feed feature using the Windows Registry if you don't have Group Policy Editor. For this, you'll need to create an EnableFeeds value and set it to 0 to disable it.

 Incorrect modifications to the Windows Registry can cause your system to malfunction. We recommend [creating a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before making any changes to the registry entries.

To disable the news feed feature using Windows Registry:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .  
![registry editor new key Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows.jpg)
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quicker navigation:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows`
4. Right-click on the**Windows** key in the left pane.
5. Select**New > Key** . Rename the key as**Windows Feeds** .  
![registry editor new key Windows new DWORd value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value.jpg)

1. Next, right-click the**Windows Feeds** key and select**New > DWORD (32-bit) Value** .
2. Rename the new value as**EnableFeeds** .
3. Double-click on the**EnableFeeds** value to edit it.  
![registry editor new key Windows new DWORd value 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/registry-editor-new-key-windows-new-dword-value-0.jpg)
4. Type**0** in the**Value data** field and click**OK** to save the changes.
5. Close the Registry Editor and restart your computer to apply the changes.

## 5\. Add and Disable EnableFeeds Using PowerShell

![powershell add registry key value Windows feeds Enable feeds](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/powershell-add-registry-key-value-windows-feeds-enable-feeds.jpg)

 You can also add and modify the EnableFeeds value in the Windows Registry using PowerShell. To do this:

1. Press the**Win** key and type**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell terminal, copy and paste the following entry and press Enter:  
`REG ADD "HKLM\SOFTWARE\Policies\Microsoft\Windows\Windows Feeds" /v "EnableFeeds" /t REG_DWORD /d 0 /f`
4. The above command will create a new**Windows Feeds** subkey and contain the value**EnableFeeds** set to disabled.
5. If there are no errors, type**exit** and press**Enter** to close PowerShell. Restart your Computer and check for any improvements.

## Fix the News and Interests Feature's High Memory Usage on Windows

 Memory leakage is a common cause for the News and Interests high memory usage issue. While a hotfix is available, you'll need to disable the News and Interests widget item to resolve the problem if the issue persists.


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
<li><a href="https://windows11.techidaily.com/prioritizing-page-notes-on-pc-windows/"><u>Prioritizing Page Notes on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-on-coexisting-wi-fi-and-ethernet-in-a-single-windows-pc/"><u>Expert Tips on Coexisting Wi-Fi & Ethernet in a Single Windows PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/techniques-for-incremental-volume-reduction-in-pro-video-editing-for-2024/"><u>Techniques for Incremental Volume Reduction in Pro Video Editing for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensive-guide-to-adding-srt-track-to-mp4-media-for-2024/"><u>Comprehensive Guide to Adding SRT Track to MP4 Media for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/outdated-pcs-upgraded-to-modern-windows-11-standards/"><u>Outdated PCs Upgraded to Modern Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-freeze-fixes-in-win-photoshop-setup/"><u>Navigating Freeze Fixes in Win-Photoshop Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/quickly-repair-damaged-pdf-v16-files-by-stellar-guide/"><u>Quickly Repair Damaged PDF v1.6 Files</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unveiling-the-secrets-to-audio-visual-cohesion-on-facebook/"><u>2024 Approved  Unveiling the Secrets to Audio-Visual Cohesion on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-how-to-disable-win-11s-elevation-error-740/"><u>Expert Advice: How to Disable Win 11'S Elevation Error #740</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-in-explore-reintroducing-your-sd-card/"><u>Lost in Explore: Reintroducing Your SD Card</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-net-error-0x800704b3-on-windows-devices/"><u>Navigating Through Net Error 0X800704B3 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-pathway-to-activating-windows-media-player/"><u>Easy Pathway to Activating Windows Media Player</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-problem-of-unrecognized-drivers-during-windows-startup/"><u>Fixing the Problem of Unrecognized Drivers During Windows Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-dark-modes-on-win-11-notepad/"><u>Navigate to Dark Modes on Win 11 Notepad</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-expert-video-grabbing-kit-perfect-for-firefox-browser-users/"><u>In 2024, Expert Video Grabbing Kit  Perfect for FireFox Browser Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-self-shutdowns-steps-for-windows-11-users/"><u>Fix Self-Shutdowns: Steps for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-error-messages-related-to-virtual-disks/"><u>Overcoming Error Messages Related to Virtual Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-task-manager-not-working-in-windows/"><u>How to Fix the Task Manager Not Working in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-perfecting-your-punchline-kinemasters-way/"><u>[New] Perfecting Your Punchline  KineMaster's Way</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-essential-list-identifying-the-top-8-ios-daw-apps-for-tablets-and-phones/"><u>New The Essential List Identifying the Top 8 iOS DAW Apps for Tablets & Phones</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-unlocking-the-full-power-of-tiktok-with-apples-voice-commands-integration/"><u>[Updated] 2024 Approved  Unlocking the Full Power of TikTok with Apple's Voice Commands Integration</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-stardews-guide-ginger-isle-essentials-for-2024/"><u>[New] Stardew's Guide  Ginger Isle Essentials for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/methodologies-for-clearing-windows-11s-f429f-app-crashes/"><u>Methodologies for Clearing Windows 11’S F429F APP Crashes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-integrating-whatsapp-into-your-twitter-video-sharing-routine/"><u>[New] In 2024, Integrating WhatsApp Into Your Twitter Video Sharing Routine</u></a></li>
<li><a href="https://windows11.techidaily.com/dism-mastery-in-windows-11-system-image-repair/"><u>Dism Mastery in Windows 11 System Image Repair</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-superior-mac-hd-recorders-with-in-built-sound-capture/"><u>[New] 2024 Approved  Superior Mac HD Recorders with In-Built Sound Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-ways-to-revert-personalized-settings-on-windows-11s-search/"><u>Easy Ways to Revert Personalized Settings on Windows 11'S Search</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatch-dull-drums-resetting-spacebar-audio-feature/"><u>Dispatch Dull Drums: Resetting Spacebar Audio Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-sluggishness-valorant-on-windows/"><u>Overcome Sluggishness: Valorant on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sophisticated-screen-capture-3-top-tier-techniques-for-zoom-conversion/"><u>In 2024, Sophisticated Screen Capture  3 Top-Tier Techniques for Zoom Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-manage-restricted-access-and-hidden-directories-in-outlook/"><u>How to Manage Restricted Access and Hidden Directories in Outlook</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-12-mini-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone 12 mini with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-securing-students-learning-mac-based-lecture-recording/"><u>[New] In 2024, Securing Students' Learning  Mac-Based Lecture Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-process-of-disabling-windows-apps/"><u>Navigating Through the Process of Disabling Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-volume-mixer-in-windows-11/"><u>How to Open the Volume Mixer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-continuous-credential-entry-alerts-in-os/"><u>Overcoming Continuous Credential Entry Alerts in OS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-top-10-globally-acclaimed-video-sensations-on-youtube/"><u>[Updated] Top 10 Globally Acclaimed Video Sensations on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-video-speed-in-vlc-to-minimize-delay/"><u>Fine-Tuning Video Speed in VLC to Minimize Delay</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-biz-vault-services-for-data-for-2024/"><u>Prime Biz Vault Services for Data for 2024</u></a></li>
</ul></div>
