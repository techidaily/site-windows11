---
title: Tips for Disabling OneDrive on Windows 11'S Explore
date: 2024-08-27T16:14:17.760Z
updated: 2024-08-28T16:14:17.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips for Disabling OneDrive on Windows 11'S Explore
excerpt: This Article Describes Tips for Disabling OneDrive on Windows 11'S Explore
keywords: Win11 Disable OneDrive,Turn Off OneDrive Windows,Stop OneDrive Windows 11,OneDrive Shutdown Tips,Deactivate OneDrive Windows,OneDrive OFF Windows Guide,Disable OneDrive in Win11
thumbnail: https://thmb.techidaily.com/dd1b377f0a177d81939c2e9879a9449aa15d2816c9d71de8279c052980247986.jpg
---

## Tips for Disabling OneDrive on Windows 11'S Explore

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://tiktok-videos.techidaily.com/new-cutting-edge-anime-ideas-dominating-social-media-screens/"><u>[New] Cutting-Edge Anime Ideas Dominating Social Media Screens</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-experts-choice-of-commercial-free-recording/"><u>[New] In 2024, Expert's Choice of Commercial-Free Recording</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-shine-a-light-on-your-content-creation/"><u>[New] In 2024, Shine a Light on Your Content Creation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nspiration-boost-with-leading-hr-tapes-for-2024/"><u>[New] Inspiration Boost with Leading HR Tapes for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-mastering-editing-skills-for-professional-facebook-reels-for-2024/"><u>[New] Mastering Editing Skills for Professional Facebook Reels for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unlocking-facebook-video-success-key-strategies-revealed-for-2024/"><u>[New] Unlocking Facebook Video Success  Key Strategies Revealed for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-wave-goodbye-to-dullness-the-ultimate-list-of-funny-youtubers/"><u>[New] Wave Goodbye to Dullness  The Ultimate List of Funny YouTubers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-mov-file-preservation-securing-and-organizing-on-windows-systems/"><u>[Updated] .mov File Preservation  Securing & Organizing on Windows Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-exclusive-guide-to-the-best-20-incarceration-moments-that-spark-smiles-online/"><u>[Updated] 2024 Approved  Exclusive Guide to the Best 20 Incarceration Moments that Spark Smiles Online</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-efficient-tactics-for-viewing-subscribers-on-yt-for-2024/"><u>[Updated] Efficient Tactics for Viewing Subscribers on YT for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-channel-up-the-essential-guide-to-computer-and-mobile-video-upload/"><u>[Updated] In 2024, Channel Up  The Essential Guide to Computer & Mobile Video Upload</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-reviving-the-reluctant-connection-of-your-obs-capture-device/"><u>[Updated] In 2024, Reviving the Reluctant Connection of Your OBS Capture Device</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-comprehensive-blueprint-for-capturing-whatsapp-calls/"><u>[Updated] In 2024, The Comprehensive Blueprint for Capturing WhatsApp Calls</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfect-iphone-images-abide-by-these-10-rules/"><u>[Updated] Perfect iPhone Images  Abide by These 10 Rules</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-harnessing-real-time-trends-for-visionary-video-ideas/"><u>2024 Approved  Harnessing Real-Time Trends for Visionary Video Ideas</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-leading-5-digital-videography-devices/"><u>2024 Approved  Leading 5 Digital Videography Devices</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-melodic-gateways-a-list-of-top-tunes-to-open-your-podcasts/"><u>2024 Approved  Melodic Gateways  A List of Top Tunes to Open Your Podcasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-pivotal-moments-top-20-anime-themes/"><u>2024 Approved  Pivotal Moments  Top 20 Anime Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/expedite-data-access-seamless-entry-into-windows-11-disk-editor/"><u>Expedite Data Access: Seamless Entry Into Windows 11 Disk Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-how-to-reset-win11-search-default-configurations/"><u>Expert Advice: How to Reset Win11 Search Default Configurations</u></a></li>
<li><a href="https://windows11.techidaily.com/fast-track-to-enabling-telnet-in-win11-pcs/"><u>Fast Track to Enabling Telnet in Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-roblox-on-screen-stop-issues-on-windows-systems/"><u>Fixing Roblox On-Screen Stop Issues on Windows Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/from-silent-screens-to-captivating-media-instantly-create-captions-on-fb-for-2024/"><u>From Silent Screens to Captivating Media  Instantly Create Captions on FB for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-turn-off-windows-from-starting-spotify/"><u>Guide to Turn Off Windows From Starting Spotify</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-portable-software-menu-to-windows-10-and-11/"><u>How to Add a Portable Software Menu to Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-copy-and-paste-not-working-in-windows-11/"><u>How to Fix Copy and Paste Not Working in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-irq-problems-with-your-soundcard-on-windows/"><u>How to Fix IRQ Problems With Your Soundcard on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-unmovable-scrolling-in-excel-windows/"><u>How to Rectify Unmovable Scrolling in Excel (Windows)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-huawei-nova-y91-lock-screen-password-by-drfone-android/"><u>How to Reset your Huawei Nova Y91 Lock Screen Password</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-salvage-your-failed-zip-extraction-in-windows-11/"><u>How To Salvage Your Failed ZIP Extraction in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-oppo-f25-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-choosing-between-podcast-and-youtube-for-content-consumption/"><u>In 2024, Choosing Between Podcast and YouTube for Content Consumption</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exploring-the-extents-of-vr-technology/"><u>In 2024, Exploring the Extents of VR Technology</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-must-know-definition-of-digital-storytelling/"><u>In 2024, Must-Know Definition of Digital Storytelling</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-monitors-choosing-personalized-themes-in-win-1011/"><u>Maximizing Monitors: Choosing Personalized Themes in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-disconnected-spotify-sessions-in-w10w11/"><u>Mending Disconnected Spotify Sessions in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/modify-your-windows-personalized-spotlight-image/"><u>Modify Your Windows Personalized Spotlight Image</u></a></li>
<li><a href="https://windows11.techidaily.com/muting-mayhem-reverse-sound-suppression-in-windows/"><u>Muting Mayhem? Reverse Sound Suppression in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-understanding-how-to-use-imessage-on-your-computer/"><u>Navigating and Understanding How to Use iMessage on Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-11-registry-for-obscured-themes/"><u>Navigating the Windows 11 Registry for Obscured Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/peering-into-major-complaints-about-windows-11-launch/"><u>Peering Into Major Complaints About Windows 11 Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/pioneering-retro-upgrades-atlasos-transformation/"><u>Pioneering Retro Upgrades: AtlasOS Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-recovery-reviving-a-vanished-windows-update/"><u>Quick Recovery: Reviving a Vanished Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-lost-audio-output-in-non-responsive-os/"><u>Recover Lost Audio Output in Non-Responsive OS</u></a></li>
<li><a href="https://windows11.techidaily.com/redesigned-navigation-top-7-updates-to-window-11s-file-explorer/"><u>Redesigned Navigation: Top 7 Updates to Window 11'S File Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-game-launch-hurdles-with-epic-logins/"><u>Reversing Game Launch Hurdles with Epic Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-browsing-at-fingertips-activating-gestures-in-microsoft-edge-win-11-edition/"><u>Seamless Browsing at Fingertips: Activating Gestures in Microsoft Edge, Win 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-mystery-of-error-0x0000004e-on-windows/"><u>Solving the Mystery of Error 0X0000004E on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/spotting-the-green-light-and-red-alert-windows-login-status/"><u>Spotting the Green Light & Red Alert: Windows Login Status</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-shutdown-auto-restart-guide-for-windows-pcs/"><u>Stealthy Shutdown: Auto-Restart Guide for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/stopping-missteps-in-mouse-travel-with-simple-fixes/"><u>Stopping Missteps in Mouse Travel with Simple Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-voice-input-in-windows-11-with-shortcuts-guide/"><u>Streamlining Voice Input in Windows 11 with Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-workspace-integrating-directories-into-taskbar-menu/"><u>Streamlining Your Workspace: Integrating Directories Into Taskbar Menu</u></a></li>
<li><a href="https://some-guidance.techidaily.com/synergy-strategies-for-ig-and-tiktok-for-2024/"><u>Synergy Strategies for IG & TikTok for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-working-shift-with-simple-tweaks/"><u>Tackle Non-Working Shift with Simple Tweaks</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-first-load-webpage-on-win11/"><u>Tailoring Your First Load Webpage on Win11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/teenyscreenmugger-evaluation-insights-for-2024/"><u>TeenyScreenMugger Evaluation Insights for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-vision-enhancers-guide-top-9-remedies-for-blurry-displays/"><u>The Vision Enhancers' Guide: Top 9 Remedies for Blurry Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/the-winning-package-tool-for-you-a-choco-vs-wm-quest/"><u>The Winning Package Tool for You: A Choco VS. WM Quest</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-realme-11-pro-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Realme 11 Pro Location | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-samsung-galaxy-m14-4g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Samsung Galaxy M14 4G FRP Bypass</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-guide-securing-fresh-updates-and-downloads-for-your-amd-ati-radeon-hd-3450/"><u>Ultimate Guide: Securing Fresh Updates & Downloads for Your AMD ATI Radeon HD 3450</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-airpods-windows-symbiosis/"><u>Unlocking AirPods-Windows Symbiosis</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721467225950-why-is-my-iphone-running-slow-discover-6-key-factors-and-quick-fixes/"><u>Why Is My iPhone Running Slow? - Discover 6 Key Factors & Quick Fixes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/windows-11-unveiling-the-real-speed-of-your-systems-ram-a-comprehensive-guide/"><u>Windows 11: Unveiling the Real Speed of Your System's RAM – A Comprehensive Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-against-windowss-notorious-pink-screens/"><u>Winning Against Windows's Notorious Pink Screens</u></a></li>
</ul></div>
