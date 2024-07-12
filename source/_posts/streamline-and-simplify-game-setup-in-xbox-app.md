---
title: Streamline and Simplify Game Setup in Xbox App
date: 2024-07-11T21:36:30.503Z
updated: 2024-07-12T21:36:30.503Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Streamline and Simplify Game Setup in Xbox App
excerpt: This Article Describes Streamline and Simplify Game Setup in Xbox App
keywords: Xbox Quick Setup,Streamlined Gaming,Easy Xbox Access,Xbox App Simplicity,Speed Up Game Start,Xbox Configurations,Faster Xbox Play
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Streamline and Simplify Game Setup in Xbox App

 The Xbox app lets you purchase and install games on any of your system drives. Usually, this process works well, but sometimes, the Xbox app won't let you install games in any location other than the default directory. This can be problematic, especially when you want to install a big-size game, but the default directory doesn't have enough space.

 Such situations usually arise due to corruption in the Xbox app or misconfigured registry settings. Fortunately, it's very easy to troubleshoot this problem. Here are some fixes to try when you can't choose a drive to install games on the Xbox app.

## 1\. Restart the Computer

![Restart option in Power menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart.jpg)

 You might fail to change the installation drive in the Xbox app due to a temporary system glitch or bug. Luckily, you can quickly eliminate such bugs and glitches by restarting your computer.

 To restart, press the**Alt + F4** hotkeys to open the Shut Down Windows prompt, click the drop-down icon, choose**Restart** from the context menu, and then click**OK.** After restart, launch the Xbox app and check if you can choose a different drive to install games. If not, then it's time to dive into the advanced troubleshooting methods.

## 2\. Change the Installation Directory in the Xbox App Settings

 There are two places from where you can change the installation drive on the Xbox app. One is while installing the game, whereas the other is the Xbox settings menu.

 If the first method is not working, you can use the second method to change the installation drive in the Xbox app. So, here's how to edit the Xbox app settings to change its default download location.

1. Launch the Xbox app, click on your profile in the top left corner, and choose**Settings** from the context menu.
2. Choose**General** from the left sidebar.
3. Click the**Change folder** option under**Change where this app installs games by default** .  
![Change Folder in Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-folder.jpg)
4. Choose the location where you want to install the game and then click the**Select Folder** option.

## 3\. Customize the System Settings

 If editing the Xbox app settings wasn't helpful, you can edit the system settings and check if it makes a difference. Here's what you need to do:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Choose**System** from the left sidebar and then click on the**Storage** option in the right pane.
3. Click the drop-down icon next to**Advanced storage settings** and choose**Where new content** **is saved** option from the context menu.  
![Where new content is saved option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/where-new-content-is-saved.png)
4. Click the drop-down icon under the**New** **apps** **will save to** section, choose the drive where you want to install the game, and then click**Apply.**  
![New apps will save to section in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-apps-will-save-to-section.jpg)

 That's it! Restart your computer and check if the problem continues.

## 4\. Restart Important Xbox Services

![Restart Service option in Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-service.jpg)

 There are certain Xbox services that must be running for you to use the Xbox app properly. If any of these services fail to start properly, you might face the problem at hand.

 To fix that, restart each service manually. Here's how to do that:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. Type**services.msc** in the search bar and click OK.
3. In the Services window, locate and right-click on the following services and choose**Restart** from the context menu.  
`Xbox Accessory Management  
Xbox Live Game Save  
Xbox Live Auth Manager  
Xbox Live Networking Service`

## 5\. Reinstall the Gaming Services App

 The Gaming Services app allows you to seamlessly download apps and games from the Microsoft Store and the Xbox app. But if the app gets corrupt, you might face various issues, including the one in question.

 The solution, in this case, is to reinstall the Gaming Services app on your computer. You can do that by following the below instructions:

 Editing the registry can be dangerous, as one wrong edit can make your system unstable. To ensure that your data is secure even if something goes wrong,[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

1. Open the Run dialog box, type**regedit,** and click OK.
2. In the Registry Editor, navigate to the below location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
3. Right-click on the**GamingServices** folder in the left sidebar and choose**Delete** from the context menu.  
![Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-option.jpg)
4. Click**Yes** to confirm your selection.
5. Next, delete the**GamingServicesNet** folder as well in the left sidebar.

 Now, open the elevated PowerShell window (see how to [open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/) ), type the following command, and press**Enter** .

`Get-AppxPackage *gamingservices* -allusers | remove-appxpackage -allusers`

![Remove Gaming Services command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-gaming-services.jpg)

 After uninstalling the Gaming Services app, restart your computer. Then, open the Microsoft Store, search for and [download the Gaming Services](https://apps.microsoft.com/store/detail/gaming-services/9MWPM2CQNLHN?hl=en-us&gl=us) app again.

## 6\. Repair the Xbox App

 It's very common for the Xbox app to get corrupt and throw various issues. The best way to remove corruption from the UWP apps like the Xbox app is to use the Windows repair feature.

 Check out [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) for information on how to do this.

## 7\. Update the Xbox App

 If repairing the Xbox app doesn't remove the corruption, consider updating the app. Downloading the latest update of the Xbox app will not only remove the corruption but also introduce new features.

To update the Xbox app, follow the below steps:

1. Open the Microsoft Store and click the**Library** option in the left sidebar.
2. Click the**Get updates** button to allow the Microsoft Store to search for available updates of the installed apps.

 The Microsoft Store will now automatically download updates for installed apps, including the Xbox app.

 While you're at installing updates, we'd also recommend [downloading any available Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . To do so, launch the Settings app, choose**Windows Update** from the left sidebar, and then click the**Check for Updates** button to install any available update on your computer. Following this, you will be able to choose a drive to install games on the Xbox app.

## Change the Download Location of the Xbox App

 The Xbox app is a great place to download your favorite games. However, the app might fail to change the installation location of games. Fortunately, you can quickly eliminate this issue by following the above fixes.

 Meanwhile, you might be interested to know how to increase downloading speed of the Xbox app.


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
<li><a href="https://windows11.techidaily.com/reprogramming-windows-delete-files-read-lock/"><u>Reprogramming Windows: Delete File's Read Lock</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-assessing-mr-beasts-monetary-trajectory/"><u>[New] 2024 Approved  Assessing Mr. Beast’s Monetary Trajectory</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-filmora-on-a-budget-how-to-get-it-without-breaking-the-bank-or-the-law/"><u>Updated 2024 Approved Filmora on a Budget How to Get It Without Breaking the Bank or the Law</u></a></li>
<li><a href="https://extra-information.techidaily.com/accelerated-methods-for-forming-macs-picture-tapestry/"><u>Accelerated Methods for Forming Mac's Picture Tapestry</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-how-to-enable-audio-in-avidemux-quick-troubleshooting-for-2024/"><u>Updated How to Enable Audio in Avidemux Quick Troubleshooting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-stability-the-definitive-net-window-repair-guide-max-156/"><u>Regain Stability: The Definitive .NET Window Repair Guide (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sleep-mode-anomalies-why-it-frustrates-users/"><u>Windows' Sleep Mode Anomalies: Why It Frustrates Users</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-performance-conquering-windows-lag-issues/"><u>Supercharge Performance: Conquering Windows Lag Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-fixing-0x8009030e-on-virt-environments/"><u>Step-by-Step Guide: Fixing 0X8009030E on Virt Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-how-to-get-and-run-msibundle-and-appxappxbundles/"><u>Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-slow-windows-apps-ensure-robust-web-linkage/"><u>Revive Slow Windows Apps: Ensure Robust Web Linkage</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-iphone-and-androids-alternative-to-youtube-experience/"><u>2024 Approved  IPhone & Android's Alternative to YouTube Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-support-functionality-in-windows-11-help/"><u>Restoring Support Functionality in Windows 11 Help</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-elevate-your-clicking-skills-with-these-top-12-pc-titles/"><u>[Updated] In 2024, Elevate Your Clicking Skills with These Top 12 PC Titles</u></a></li>
<li><a href="https://windows11.techidaily.com/5-key-fixes-to-stop-rpc-failures-in-windows/"><u>5 Key Fixes to Stop RPC Failures in Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/did-your-iphone-14-pro-max-passcode-change-itself-unlock-it-now-drfone-by-drfone-ios/"><u>Did Your iPhone 14 Pro Max Passcode Change Itself? Unlock It Now | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-gionee-f3-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Gionee F3 Pro</u></a></li>
<li><a href="https://youtube-data.techidaily.com/hart-your-course-to-youtube-riches-the-essential-500-threshold-for-2024/"><u>[New] Chart Your Course to Youtube Riches  The Essential 500 Threshold for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-login-audit-success-or-no-go-indicators/"><u>Windows Login Audit: Success or No-Go Indicators</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-here-are-the-top-10-free-and-paid-whiteboard-animation-software-options-available-now-check-it-to-find-which-free-whiteboard-animation-sof/"><u>New 2024 Approved Here Are the Top 10 Free and Paid Whiteboard Animation Software Options Available Now. Check It to Find Which Free Whiteboard Animation Software You Want to Use</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/insta-story-hack-for-stealthy-tech-users/"><u>Insta Story Hack for Stealthy Tech Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-can-you-respect-intellectual-property-while-screenrecording-youtube/"><u>[New] Can You Respect Intellectual Property While ScreenRecording YouTube?</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-different-ways-to-restart-your-windows-computer/"><u>The 8 Different Ways to Restart Your Windows Computer</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-combine-power-tweeting-and-snapping-with-snapchat/"><u>2024 Approved  Combine Power  Tweeting and Snapping with Snapchat</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-cooldown-chart-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-windows-sluggish-discord-overlay-performance/"><u>Reviving Windows' Sluggish Discord Overlay Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/reset-windows-strategies-8-techniques-unveiled/"><u>Reset Windows Strategies: 8 Techniques Unveiled</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-poco-x6-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Poco X6 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/address-common-printer-glitches-in-windows-11/"><u>Address Common Printer Glitches in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-optimal-choices-in-monitors-for-ps5-gamers/"><u>In 2024, Optimal Choices in Monitors for PS5 Gamers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-thumbnail-scaling-techniques-for-youtube/"><u>[Updated] Thumbnail Scaling Techniques for YouTube</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-elevate-your-social-media-impact-with-these-top-5-youtube-marketing-techniques/"><u>2024 Approved  Elevate Your Social Media Impact with These Top 5 YouTube Marketing Techniques</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-easy-steps-for-arranging-a-google-meeting/"><u>[Updated] Easy Steps for Arranging a Google Meeting</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-stable-apex-play-on-windows-11/"><u>Unlocking the Secrets to Stable Apex Play on Windows 11</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-top-photography-choices-for-sharpest-4k-reflections/"><u>2024 Approved  Top Photography Choices for Sharpest 4K Reflections</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unlock-your-computers-windows-license/"><u>Techniques to Unlock Your Computer's Windows License</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-right-click-customization-compatibility-tool-inclusion/"><u>Windows Right-Click Customization: Compatibility Tool Inclusion</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-transcoding-approaches-to-boost-zoom-videos-for-2024/"><u>Top Transcoding Approaches to Boost Zoom Videos for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-precision-shooting-leading-10-gimbals-ranked/"><u>In 2024, Precision Shooting  Leading 10 Gimbals Ranked</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-video-lag-during-steam-livestreams/"><u>Overcoming Video Lag During Steam Livestreams</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-steps-to-add-subtitles-in-canva/"><u>2024 Approved Steps to Add Subtitles in Canva</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/enhancing-engagement-on-facebook-a-beginners-roadmap-for-2024/"><u>Enhancing Engagement on Facebook  A Beginner’s Roadmap for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-in-windows-11-with-a-customized-run-command-setup/"><u>Streamline Tasks in Windows 11 with a Customized Run Command Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-to-troubleshoot-loaded-lol-screens/"><u>Tactics to Troubleshoot Loaded LOL Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-the-high-life-excess-in-windowed-worlds/"><u>Slowing Down the High Life Excess in Windowed Worlds</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-apex-of-narrative-content-youtubes-finest-in-23/"><u>[New] The Apex of Narrative Content  YouTube’s Finest in '23</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-blocked-browsers-by-defender-in-win11/"><u>Quick Fix for Blocked Browsers by Defender in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-silent-sounds-on-windows-devices/"><u>Troubleshooting Silent Sounds on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-the-windows-11-taskbar/"><u>Unlock the Full Potential of the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-desktop-win-11-icon-recovery-tips/"><u>Reclaim Your Desktop: Win 11 Icon Recovery Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/software-selection-showdown-on-windows-choc-vs-wm/"><u>Software Selection Showdown on Windows: Choc vs WM</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-next-level-windows-experience/"><u>2024 Approved  The Next-Level Windows Experience</u></a></li>
<li><a href="https://fox-helps.techidaily.com/smooth-sailing-through-sequences-with-kinemaster-for-2024/"><u>Smooth Sailing Through Sequences with Kinemaster for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-windows-11-program-choices/"><u>Streamlining Your Windows 11 Program Choices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-echoes-of-innovation-uncovering-the-top-8-digital-hubs-for-comprehensive-free-sound-effect-collections-for-todays-creators-for-2024/"><u>Updated Echoes of Innovation Uncovering the Top 8 Digital Hubs for Comprehensive Free Sound Effect Collections (For Todays Creators) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reference-guide-to-overcoming-winscombvc-issues/"><u>Quick Reference Guide to Overcoming WinScombVc Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/6-methods-for-reviving-windows-command-line-interface/"><u>6 Methods for Reviving Windows' Command Line Interface</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-movavi-screen-recorder-11/"><u>2024 Approved  Movavi Screen Recorder 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-a-guide-to-free-you-from-youtubes-extra-bar-width/"><u>[New] In 2024, A Guide to Free You From YouTube's Extra Bar Width</u></a></li>
<li><a href="https://windows11.techidaily.com/additional-updates-available-in-windows-11s-latest-release/"><u>Additional Updates Available in Windows 11'S Latest Release</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-users-beware-is-yourphoneexe-safe-to-use/"><u>Windows Users Beware: Is YourPhone.exe Safe to Use?</u></a></li>
</ul></div>
