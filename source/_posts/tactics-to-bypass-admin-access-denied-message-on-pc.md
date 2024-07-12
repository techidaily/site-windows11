---
title: Tactics to Bypass 'Admin Access Denied' Message on PC
date: 2024-07-11T22:09:07.140Z
updated: 2024-07-12T22:09:07.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics to Bypass 'Admin Access Denied' Message on PC
excerpt: This Article Describes Tactics to Bypass 'Admin Access Denied' Message on PC
keywords: Avoid Admin Blocked Error,Circumvent Admin Lockout,Escape Permissions Denied,Skirt Unauthorized Access Alert,Bypass Admin Restriction Message,Sidestep Denial Notice,Evasion of Access Barred Signal
thumbnail: https://thmb.techidaily.com/157145562d322ac42b18debf7cc17b6e328143a79a361dfc0ab65e3b0afbaf26.jpg
---

## Tactics to Bypass 'Admin Access Denied' Message on PC

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to [changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to [open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article [about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)

 Our guide on [creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://extra-skills.techidaily.com/laying-the-groundwork-15-basic-shots-every-director-needs-for-2024/"><u>Laying the Groundwork  15 Basic Shots Every Director Needs for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-step-by-step-approach-to-professional-chromatic-control/"><u>A Step by Step Approach to Professional Chromatic Control</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-code-three-ways-to-access-game-folders/"><u>Unlock the Code: Three Ways to Access Game Folders</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-productivity-customize-taskbar-and-tiles-in-win-11/"><u>Unveil Productivity: Customize Taskbar & Tiles in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/time-to-get-back-on-track-recovering-windows-time-service/"><u>Time to Get Back on Track: Recovering Windows Time Service</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-roblox-abrupt-terminations-on-microsoft-operating-systems/"><u>Tackling Roblox Abrupt Terminations on Microsoft Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-obs-record-failure-a-comprehensive-guide-for-windows-users/"><u>Addressing OBS Record Failure: A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-step-by-step-uploading-videos-to-tiktok-on-macwindows/"><u>2024 Approved  Step-by-Step  Uploading Videos to TikTok on Mac/Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-restoring-function-of-wsreset-in-windows/"><u>Strategies for Restoring Function of WSReset in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-visual-power-with-windows-11s-auto-hdr/"><u>Unlocking Visual Power with Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-invalid-temp-paths-on-w11-systems/"><u>Troubleshooting Invalid Temp Paths on W11 Systems</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ultimate-list-of-androids-gb-compatible-simulators/"><u>Ultimate List of Android's GB-Compatible Simulators</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-basics-of-online-videos-the-easiest-10-ideas-for-beginners-on-youtube/"><u>[New] In 2024, Basics of Online Videos  The Easiest 10 Ideas for Beginners on YouTube</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-online-video-preview-generators-for-2024/"><u>New Online Video Preview Generators for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-tecno-phantom-v-fold-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Tecno Phantom V Fold Without PUK Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-full-potential-of-comic-viewing-in-win11/"><u>Unleash the Full Potential of Comic Viewing in Win11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-digital-storytelling-unlocked-creating-memorable-slideshows-on-fb-for-2024/"><u>[New] Digital Storytelling Unlocked  Creating Memorable Slideshows on FB for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-your-go-to-guide-the-12-best-audio-converters-for-easy-conversion/"><u>2024 Approved Your Go-To Guide The 12 Best Audio Converters for Easy Conversion</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-audio-mastery-configuring-custom-volume-hotkeys/"><u>Win11 Audio Mastery: Configuring Custom Volume Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-zip-files-seamless-compressed-archives-on-windows-pcs/"><u>Conquer ZIP Files: Seamless Compressed Archives on Windows PCs</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhanced-firmware-gtx-1060-model/"><u>Enhanced Firmware: GTX 1060 Model</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-chains-of-stuck-files-win11-download-guide-2/"><u>Breaking Chains of Stuck Files: WIN11 Download Guide (2)</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-blue-screen-5-tactics-for-win11-hybrid-issue-fixes/"><u>Conquer Blue Screen: 5 Tactics for Win11 Hybrid Issue Fixes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-decoding-the-art-of-instagrams-hot-trending-reels/"><u>[New] Decoding the Art of Instagram's Hot Trending Reels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-love-in-motion-youtube-and-vimeos-top-9-premium-marriage-films/"><u>[Updated] Love in Motion  YouTube & Vimeo's Top 9 Premium Marriage Films</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-missing-device-alert-in-windows-10/"><u>Steps to Resolve 'Missing' Device Alert in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-iphoneipad-photo-upload-error-on-windows-os-w11-edition/"><u>Troubleshooting iPhone/iPad Photo Upload Error on Windows OS, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-graphics-troubleshoot-and-restart-for-clear-images/"><u>Windows 11 Graphics: Troubleshoot & Restart for Clear Images</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-knowledge-about-winservicesexe/"><u>Essential Knowledge About WinServices.exe</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-windows-media-player-in-a-swift-manner/"><u>Activating Windows Media Player in a Swift Manner</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/5-reasons-to-steer-clear-from-inexpensive-windows-keys/"><u>5 Reasons to Steer Clear From Inexpensive Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-non-functional-shortcuts-with-windows-snips/"><u>Avoiding Non-Functional Shortcuts with Windows Snips</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-spotting-the-top-10-discreet-instagram-story-followers/"><u>2024 Approved  Spotting the Top 10 Discreet Instagram Story Followers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/convert-photos-on-ios-efficiently-from-jpegpng-to-pdf/"><u>Convert Photos on IOS Efficiently From JPEG/PNG to PDF</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-touch-typing-onoff-with-this-windows-tutorial/"><u>Switch Touch Typing On/Off with This Windows Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-on-retrieving-program-installation-points-in-windows/"><u>Step-by-Step on Retrieving Program Installation Points in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevating-your-youtube-presence-with-effective-tags/"><u>2024 Approved  Elevating Your YouTube Presence with Effective Tags</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-eye-catching-video-summaries-3-neon-border-methods-for-2024/"><u>Crafting Eye-Catching Video Summaries  3 Neon Border Methods for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-enhancing-social-engagement-with-zoom-fb-live-streams/"><u>2024 Approved  Enhancing Social Engagement with Zoom-FB Live Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-4-ways-to-record-internal-android-audio-no-rooting-for-2024/"><u>[Updated] 4 Ways to Record Internal Android Audio (No Rooting) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-windows-11-desktop-widget-tools/"><u>Turning On Windows 11 Desktop Widget Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/swivel-visual-viewpoint-in-windows-os/"><u>Swivel Visual Viewpoint in Windows OS</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-download-instagram-videos-with-audio-as-mp3/"><u>New 2024 Approved Download Instagram Videos with Audio as MP3</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/download-8-best-audio-spectrum-templates-for-video-for-2024/"><u>Download 8 Best Audio Spectrum Templates for Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/3-ways-to-find-a-group-policy-on-windows/"><u>3 Ways to Find a Group Policy on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-ultimate-compilation-offline-ios-games-to-delight-in/"><u>The Ultimate Compilation  Offline iOS Games to Delight In</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-spotting-hdd-vs-ssd-in-windows-operations/"><u>Essential Guide: Spotting HDD vs SSD in Windows Operations</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-channels-selecting-prime-microphones-for-every-content-category-for-2024/"><u>Elevate Your Channels  Selecting Prime Microphones for Every Content Category for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-iphone-12-pro-max-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>In 2024, Unlock iPhone 12 Pro Max With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-and-science-of-professional-printing-from-powerpoint-on-a-windows-computer/"><u>The Art and Science of Professional Printing From PowerPoint on a Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workspace-mastering-w11-taskbar/"><u>Transform Your Workspace: Mastering W11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-impact-of-copilot-key-on-your-windows-11-pc-performance/"><u>Deciphering the Impact of Copilot Key on Your Windows 11 PC Performance</u></a></li>
</ul></div>
