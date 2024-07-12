---
title: Streamlining Your Windows 11 Program Choices
date: 2024-07-11T22:00:52.550Z
updated: 2024-07-12T22:00:52.550Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamlining Your Windows 11 Program Choices
excerpt: This Article Describes Streamlining Your Windows 11 Program Choices
keywords: Win11 Setup Guide,Streamline OS Selection,Optimize Win11 PC,Simplify Win11 Software,Windows 11 Configurations,Efficient Win11 Prep,Choose Win11 Tools
thumbnail: https://thmb.techidaily.com/61dcd74c9ca257bd7a3583ce0e08424eaf979002cdc0aa0e847be271477f189f.jpg
---

## Streamlining Your Windows 11 Program Choices

 If you are not satisfied with any of the default apps assigned by Windows, you can change them to your preferred options. This process was quite simple in Windows 10, but Microsoft has made it a bit complicated for Windows 11 users.

 In this guide, we will discuss the method of changing the default apps in Windows 11 in detail. We have also discussed several troubleshooting methods later in this guide that you can try if the default apps fail to change.

## How to Change the Default Apps in Windows 11

[Changing the default apps in Windows 10](https://www.makeuseof.com/tag/change-default-settings-windows-10/) is quite simple. You can access the**Default Apps** section of the Settings app and replace the current default app with your preferred option.

 In Windows 11, this method is slightly different. You must set a program default for all the registered file types and links relevant to it since there isn’t a**Set default for all** option available.

 Below, we have listed different ways of changing the default apps in Windows 11:

### 1\. Choose the Open With Option

 The easiest method of changing the default apps option is by using the Open with option in the context menu for files.

Here is how you can do that:

1. Right-click on the targeted file. For instance, an image file that you want to open with an app other than the default Photos app.
2. Choose**Open with** \>**Choose another app** from the context menu.  
![Choose another app to open the targeted file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-open-with-choose-another-app.jpg)
3. Now, in the following dialog, choose the app you want to set as the default option. If you cannot find the targeted app in the list, choose**Look for another app on this PC** and then select the app.
4. Click on**Always use this app to open files** and click**OK** . This should set the selected app as the default preference.  
![Set a default app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/set-the-default-app.jpg)

### 2\. Use the Settings App

 The next thing that you can do is access the Default Apps option and choose the preferred app from there.

Follow these steps to proceed:

1. Press the Win + I keys together to open the Windows Settings.
2. Choose**Apps** from the left pane.
3. Click on**Default apps** .  
![Click on the Default apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-settings-apps-default-apps.jpg)
4. Next, choose the app that you want to set as default. You should now see all the file types and link types the app is registered with.
5. If you want to choose a program as the default for all its registered file types and links, you'd need to click each type and choose the desired application in the following dialog.  
![Pick a default file type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/pick-a-default-file-type.jpg)

 This should set the app as the default option for the selected file and link types. However, if you [reset Windows 11 to its default state](https://www.makeuseof.com/windows-11-factory-reset-without-admin-password/) ever, you will lose all these settings.

### 3\. Use File Properties

 You can also change the file properties of the targeted file to open it with a new default app.

To proceed, follow these steps:

1. Right-click on the targeted file and choose**Properties** from the context menu.  
![Access the properties of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties.jpg)
2. Head over to the General tab and click on the**Change** button associated with**Opens with** .  
![Click on the Change button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/image-properties-general-change.jpg)
3. Now, choose the desired app and click**OK** .

## What to Do If You Cannot Change the Default Apps in Windows 11?

 If you are unable to change the default apps in Windows 11 despite trying the different methods mentioned above, it could be due to the following reasons:

* The app that you are trying to set as the default option is dealing with a corruption error or is not installed correctly.
* A group policy setting in the system is preventing you from changing these configurations.
* You do not have sufficient permissions to make changes of this level in the system.
* The app is not compatible with your system.

 In this case,[ensure that your user account has administrative rights](https://www.makeuseof.com/check-windows-account-admin-rights/) and that the app you are trying to set as default is compatible with the system. Here are some more steps you can follow to resolve the problem.

### 1\. Update Windows 11

 If you're running an outdated version of Windows, you may be experiencing problems due to incompatibility issues. Windows 11 needs to be updated to the latest version in this case.

Here is how you can do that:

1. Press the Win + I keys together to open Windows Settings.
2. Choose**Windows Update** from the left pane.
3. Now, click on the**Check for updates** button on the right side.
4. Install all the pending updates one by one by clicking on the**Download & install** button and then restart your PC.  
![Click on the Download & install button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/settings-windows-update-download-and-install.jpg)

 Once this is done, follow one of the steps above to change the default app.

### 2\. Reset the Targeted App

 If the problem is within the app that you are trying to change, you can reset the program to solve the problem.

Follow these steps to proceed:

1. Press Win + S keys together to open Windows Search.
2. Type Powershell and choose**Run as administrator** .
3. Click**Yes** in the User Account Control prompt.
4. In the Powershell window, type the command mentioned below and click Enter. Replace packagename with the name package name of the app that you want to set as default.  
Get-AppxPackage packagename -AllUsers | Reset-AppxPackage
5. For instance, if you want to change the Photos app, execute the following command:  
Get-AppxPackage Microsoft.Windows.Photos -AllUsers | Reset-AppxPackage  
![Reset the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/get-appxpackage-packagename.jpg)
6. Once the command is executed, check if you can change the default app.

### 3\. Reinstall the App

 Lastly, you can try reinstalling the app that you want to set as default. This will eliminate any corruption errors are bugs within the app that are preventing you from setting it as the default option.

Here is how you can proceed:

1. Press the Win + R keys together to open a Run dialog.
2. Type control in Run and click Enter.
3. In the following window, navigate to**Uninstall a program** .  
![Uninstall a program](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/uninstall-a-program.jpg)
4. Locate the targeted app and right-click on it.
5. Choose**Uninstall** and follow the on-screen instructions to proceed.  
![Uninstall the app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/win11-uninstall-program.jpg)

 Once the uninstallation is completed, restart the computer and reinstall the app. Hopefully, this time, you will be able to set it as the default option without any problems.

## Make Your Preferred Apps Default

 The apps set as the default options on Windows are quite user-friendly and efficient. It is possible, however, to change the default preference to a better option if you have found one that suits your system better.

 With the methods listed above, you should be able to change the default apps on your Windows 11 system in no time. Nevertheless, keep in mind that in the event that Windows is reinstalled or reset, these options will return to the default configuration.

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
<li><a href="https://windows11.techidaily.com/augmenting-macos-capabilities-via-windows-applications/"><u>Augmenting macOS Capabilities via Windows Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-crafting-slideshows-and-fixing-flaws-in-win11s-photos-app/"><u>A Step-by-Step Approach to Crafting Slideshows & Fixing Flaws in Win11's Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-win-11-typing-efficiency-8-input-lag-remedies/"><u>Boost Your Win 11 Typing Efficiency: 8 Input Lag Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-problems-with-software-installations-from-windows-store/"><u>Addressing Problems with Software Installations From Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/1719322271213-microsoft-to-do-not-sync-follow-these-steps-now/"><u>Microsoft To-Do Not Sync? Follow These Steps Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-for-windows-partition-consolidation/"><u>Advanced Techniques for Windows Partition Consolidation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-budding-filmmakers-companion-understanding-display-quality-101/"><u>[Updated] The Budding Filmmaker’s Companion  Understanding Display Quality 101</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-how-to-switch-between-normal-and-picture-in-picture-views-in-youtube/"><u>2024 Approved  How to Switch Between Normal and Picture In Picture Views in Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-blank-screen-top-techniques-to-recover-vanished-panes-in-windows-11/"><u>Avoid the Blank Screen: Top Techniques to Recover Vanished Panes in Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-prime-5-hd-webcams-for-seamless-video-conferencing-for-2024/"><u>[New] Prime 5 HD Webcams For Seamless Video Conferencing for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fine-tuning-your-fb-videos-aspect-ratios-decoded/"><u>[Updated] Fine-Tuning Your FB Videos  Aspect Ratios Decoded</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-unleashing-the-full-power-of-apple-podcasts-downloads-for-2024/"><u>[New] Unleashing the Full Power of Apple Podcasts Downloads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/7-top-choices-no-cost-win-compatible-players/"><u>7 Top Choices: No-Cost Win-Compatible Players</u></a></li>
<li><a href="https://windows11.techidaily.com/advance-work-efficiency-with-windows-smart-launcher-tool/"><u>Advance Work Efficiency with Windows' Smart Launcher Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-fix-manual-for-widespread-rainmeter-problems/"><u>A Comprehensive Fix Manual for Widespread Rainmeter Problems</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-sub-to-srt-with-ease-uncover-our-top-8-software-picks-for-desktop-systems/"><u>[Updated] From SUB to SRT with Ease! Uncover Our Top 8 Software Picks for Desktop Systems</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-mastering-video-posts-on-tiktok-your-guide-for-mac-and-pc-users/"><u>[Updated] Mastering Video Posts on TikTok  Your Guide for MAC & PC Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/pump-it-up-the-20-most-energizing-workout-playlists-for-2024/"><u>Pump It Up  The 20 Most Energizing Workout Playlists for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-masterclass-in-elegance-blurring-borders-for-zoom/"><u>[Updated] 2024 Approved  Masterclass in Elegance  Blurring Borders for Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-cycle-of-unresponsive-photoshop-on-windows/"><u>Breaking the Cycle of Unresponsive Photoshop on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bygone-brilliance-reviving-retro-gameplay-with-dosbox-x/"><u>Bygone Brilliance: Reviving Retro Gameplay with DOSBox-X</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-how-you-handle-deleted-items-on-pc/"><u>Adjusting How You Handle Deleted Items on PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-starting-point-auditions-approach-to-soft-volume-increase/"><u>In 2024, Starting Point  Audition's Approach to Soft Volume Increase</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-the-power-of-srt-editing-for-mac-users-for-2024/"><u>Unlocking the Power of SRT Editing for Mac Users for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-insta-gurus-guide-the-essential-hashtags-you-need-today/"><u>[New] 2024 Approved  Insta Gurus Guide  The Essential Hashtags You Need Today</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-ultimate-guide-to-shooting-phenomenal-igtv-with-dslrsmartphone/"><u>The Ultimate Guide to Shooting Phenomenal IGTV with DSLR/Smartphone</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-limitation-threshold-unleash-higher-ethernet-speeds-on-windows/"><u>Breach Limitation Threshold: Unleash Higher Ethernet Speeds on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-soundscape-symphony-crafting-concert-videos-with-these-15-tutorials/"><u>In 2024, Soundscape Symphony  Crafting Concert Videos with These 15 Tutorials</u></a></li>
<li><a href="https://windows11.techidaily.com/calculate-and-track-power-consumption-for-your-pc-windows-edition/"><u>Calculate and Track Power Consumption for Your PC: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/5-clever-cmd-gimmicks-to-spice-up-your-day/"><u>5 Clever CMD Gimmicks to Spice Up Your Day</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/maximize-account-performance-with-these-premier-tiktok-metrics/"><u>Maximize Account Performance with These Premier TikTok Metrics</u></a></li>
<li><a href="https://windows11.techidaily.com/a-journey-into-innovation-windows-11-writes-the-next-chapter/"><u>A Journey Into Innovation - Windows 11’ Writes the Next Chapter</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-optimizing-visuals-aspect-ratio-alteration/"><u>[Updated] Optimizing Visuals  Aspect Ratio Alteration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-pixel-chronicles-mastering-the-art-of-recording-your-minecraft-world/"><u>In 2024, Pixel Chronicles  Mastering the Art of Recording Your Minecraft World</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-graphics-problem-3-for-windows-11-users/"><u>Addressing Graphics Problem #3 for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-your-bandsaw-methods-for-fixing-lost-windows-time/"><u>Bring Back Your Bandsaw: Methods for Fixing Lost Windows Time</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-missed-emojis-activating-the-latest-on-windows-11/"><u>Avoiding Missed Emojis: Activating the Latest on Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-essential-empowerment-packages-top-trending-products-for-todays-entrepreneur/"><u>[Updated] In 2024, Essential Empowerment Packages  Top Trending Products for Today's Entrepreneur</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-approach-to-dotnet-repair-on-pcs-max-156/"><u>A Step-by-Step Approach to DotNet Repair on PCs (Max 156)</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-roblox-code-403-blocks-on-pc/"><u>Addressing Roblox Code 403 Blocks on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/beating-steam-disk-write-failures-on-windows-pc/"><u>Beating Steam Disk Write Failures on Windows PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-becoming-an-srt-creation-virtuoso-a-complete-manual/"><u>[New] Becoming an SRT Creation Virtuoso  A Complete Manual</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-methodically-uncovering-hidden-video-wonders-on-youtube/"><u>[Updated] Methodically Uncovering Hidden Video Wonders on YouTube</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/srt-power-play-transforming-macwindows-experience-for-2024/"><u>SRT Power Play  Transforming Mac/Windows Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/autopilot-off-stopping-chromes-unwanted-tab-openings/"><u>Autopilot Off: Stopping Chrome's Unwanted Tab Openings</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-do-you-often-feel-fascinated-to-try-hands-at-anime-character-design-to-spark-up-your-editing-skills-or-just-for-a-fun-filled-activity-/"><u>Updated 2024 Approved Do You Often Feel Fascinated to Try Hands at Anime Character Design to Spark up Your Editing Skills, or Just for a Fun-Filled Activity? Stay Here for the Best Inspirations You Can Ever Get</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-no-cost-copyright-free-pubg-image-bundles/"><u>[New] No-Cost, Copyright-Free PUBG Image Bundles</u></a></li>
</ul></div>
