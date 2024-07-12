---
title: "Tweak Your PC: Reduce Memory/CPU Waste From Apps"
date: 2024-07-11T21:36:41.369Z
updated: 2024-07-12T21:36:41.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tweak Your PC: Reduce Memory/CPU Waste From Apps"
excerpt: "This Article Describes Tweak Your PC: Reduce Memory/CPU Waste From Apps"
keywords: Optimize PC Performance,Minimize CPU Load,Enhance RAM Efficiency,Cut Unused App Resources,Reduce Memory Consumption,Boost System Speed,Decrease Processor Waste
thumbnail: https://thmb.techidaily.com/dd18e8bc3c9f273d09d135719fd511870ffe57b02ca619c624658544faadfc68.jpg
---

## Tweak Your PC: Reduce Memory/CPU Waste From Apps

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
<li><a href="https://windows11.techidaily.com/win11-offline-setting-up-on-disconnected-pcs/"><u>Win11 Offline: Setting Up on Disconnected PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11-homespace-options/"><u>Accessing Windows 11 Homespace Options</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-beginners-handbook-to-saving-your-conversations-via-google-voice/"><u>The Beginners Handbook to Saving Your Conversations via Google Voice</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-microsoft-teams-stumbling-block-80080300-on-w11/"><u>Triumph over Microsoft Teams' Stumbling Block #80080300 on W11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-optimal-downloaders-your-guide-to-superior-4k-content/"><u>[New] Optimal Downloaders  Your Guide to Superior 4K Content</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-windows-lsa-disablement-warning/"><u>Bypassing the Windows LSA Disablement Warning</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-realme-v30t-easily-by-drfone-android/"><u>In 2024, How To Unlock a Realme V30T Easily?</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-unplayable-file-challenge/"><u>Addressing Windows' Unplayable File Challenge</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-live-tv-saving-made-simple-with-free-software-tools/"><u>[New] In 2024, Live TV Saving Made Simple with Free Software Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-solutions-for-correction-of-network-security-discrepancy-in-windows-11/"><u>Top 5 Solutions for Correction of Network Security Discrepancy in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-list-of-popular-mobile-video-apps-excluding-youtube/"><u>2024 Approved  The Ultimate List of Popular Mobile Video Apps (Excluding YouTube)</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-troubled-windows-credentials/"><u>Triumph over Troubled Windows Credentials</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-easyrecorder-pro-free-gamers-recording-aid/"><u>[New] In 2024, EasyRecorder Pro  Free Gamers' Recording Aid</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-6-ways-to-convert-video-to-audio-for-free/"><u>2024 Approved 6 Ways to Convert Video to Audio for FREE</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-the-ultimate-list-of-gif-speed-changer-apps-and-websites/"><u>Updated 2024 Approved The Ultimate List of GIF Speed Changer Apps and Websites</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-top-11-innovative-sites-for-crafting-impactful-fb-cover-photos-for-2024/"><u>[Updated] Top 11 Innovative Sites for Crafting Impactful FB Cover Photos for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/photographic-albums-with-background-music-for-2024/"><u>Photographic Albums with Background Music for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-vivo-s18-pro-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Vivo S18 Pro Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-zte-axon-40-lite-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on ZTE Axon 40 Lite</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-nvidia-driver-recommendations-entertainment-sector/"><u>Tailored Nvidia Driver Recommendations: Entertainment Sector</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-unable-to-retrieve-settings-issue-with-geforce-experience-on-windows-11/"><u>Curing Unable to Retrieve Settings Issue with GeForce Experience on Windows 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-essential-tips-for-youtube-edits-with-sony-vegas/"><u>[New] Essential Tips for YouTube Edits with Sony Vegas</u></a></li>
<li><a href="https://games-able.techidaily.com/top-budget-budgets-for-white-motherboards/"><u>Top Budget Budgets for White Motherboards</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-boosting-watch-time-and-reducing-churn-on-youtube-the-ultimate-list-of-methods/"><u>[Updated] In 2024, Boosting Watch Time and Reducing Churn on YouTube  The Ultimate List of Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/1719349405273-say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users.</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-scripting-significant-soliloquies/"><u>[New] Scripting Significant Soliloquies</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-hidden-error-code-0xc1900101/"><u>Unveiling Windows 11'S Hidden Error Code #0xC1900101</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-pathways-to-successful-office-activation/"><u>Clearing Pathways to Successful Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/7-crucial-blunders-every-windows-11-novice-must-avoid/"><u>7 Crucial Blunders Every Windows 11 Novice Must Avoid</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/1716465279013-youtube-profile-picture-templates-free-downloads/"><u>YouTube Profile Picture Templates – Free Downloads!</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/innovative-5-websites-eclipsing-twitter-for-2024/"><u>Innovative 5 Websites Eclipsing Twitter for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-the-nuances-zooming-in-on-roblox/"><u>[Updated] Navigating the Nuances  Zooming In on Roblox</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-examining-the-huawei-p10-camera-and-display-capabilities/"><u>[Updated] Examining the Huawei P10 Camera and Display Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-mystery-of-mouse-controls-on-windows-11/"><u>Unlock the Mystery of Mouse Controls on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-non-operational-windows-defrag-tool/"><u>Troubleshooting Non-Operational Windows Defrag Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-power-indicators-set-up-full-charge-notification-in-win11/"><u>Streamlining Power Indicators: Set Up Full Charge Notification in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-0x8007045d-an-effective-resolution-blueprint/"><u>Win11's 0X8007045D: An Effective Resolution Blueprint</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-interruptexception-on-windows-11/"><u>Tackling the INTERRUPT_EXCEPTION on Windows 11</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-discovering-the-best-in-reading-with-these-booktok-choices/"><u>[Updated] In 2024, Discovering the Best in Reading with These BookTok Choices</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-commands-for-keyboard-in-winos/"><u>Tailored Commands for Keyboard in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-command-prompt-gambits-for-a-laugh/"><u>Top 5 Command Prompt Gambits for a Laugh</u></a></li>
<li><a href="https://windows11.techidaily.com/winphone-users-decide-between-unison-and-phone-link-apps/"><u>WinPhone Users: Decide Between Unison and Phone Link Apps</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-first-home-frontier-top-6-beginner-friendly-mc-abodes/"><u>[Updated] First Home Frontier  Top 6 Beginner-Friendly MC Abodes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
</ul></div>
