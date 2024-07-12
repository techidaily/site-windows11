---
title: A Stepwise Guide to Banishing the OneDrive Icon From Explorer
date: 2024-07-11T21:25:17.227Z
updated: 2024-07-12T21:25:17.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Stepwise Guide to Banishing the OneDrive Icon From Explorer
excerpt: This Article Describes A Stepwise Guide to Banishing the OneDrive Icon From Explorer
keywords: Banish OneDrive Guide,Eliminate OneDrive Explore,Remove OneDrive Icons,Eradicate OneDrive Visibility,Dismiss OneDrive Icon,Disable OneDrive Explorer,Get Rid of OneDrive
thumbnail: https://thmb.techidaily.com/502b1cdc938497dc65859bd4dea7388cbc83b5388aae8627911832c708fd7626.jpg
---

## A Stepwise Guide to Banishing the OneDrive Icon From Explorer

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

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
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-speech-recognition-startup-error-windows/"><u>Addressing 'Failed' Speech Recognition Startup Error Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-path-resetting-windows-preferences-post-reboot/"><u>Instructional Path: Resetting Windows Preferences Post-Reboot</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-oppo-find-n3-flip-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Oppo Find N3 Flip Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-discover-the-overlooked-insights-on-instagram-story-watching/"><u>[New] 2024 Approved  Discover the Overlooked  Insights on Instagram Story Watching</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-vivo-y02t-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Vivo Y02T 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-wsreset-process-in-windows/"><u>How to Reactivate a Non-Operational WSReset Process in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/how-to-make-discord-video-calls-on-desktop-and-mobile-for-2024/"><u>How to Make Discord Video Calls on Desktop and Mobile for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-slogan-generator-for-virtual-events/"><u>2024 Approved  Best Slogan Generator for Virtual Events</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-retro-yet-current-top-10-songs-from-tiktok-that-never-end/"><u>[Updated] Retro Yet Current  Top 10 Songs From TikTok That Never End</u></a></li>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamitsimple-your-first-guide-to-live-podcasting/"><u>[New] StreamItSimple  Your First Guide to Live Podcasting</u></a></li>
<li><a href="https://windows11.techidaily.com/a-curated-list-of-6-essential-android-apps-for-windows-11-users/"><u>A Curated List of 6 Essential Android Apps for Windows 11 Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-web-add-on-fb-stories-repository-app-for-2024/"><u>[New] Web Add-On  FB Stories Repository App for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-edge-how-pcs-beat-macs-in-9-aspects/"><u>Decoding the Edge: How PCs Beat Macs in 9 Aspects</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-photo-storage-sites/"><u>2024 Approved  Top Photo Storage Sites</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-how-to-speed-up-video-on-instagram/"><u>[New] 2024 Approved  How to Speed Up Video on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-email-attachment-openness-ms-word-read-mode-only/"><u>Automate Email Attachment Openness: MS Word Read Mode Only</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-admin-error-for-apps/"><u>Bypassing Windows Admin Error for Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-gaming-glory-resolve-full-screen-woes-in-sonic-on-windows-11/"><u>Guaranteeing Gaming Glory: Resolve Full-Screen Woes in Sonic on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-how-to-take-advantage-of-itunes-for-video-capture/"><u>2024 Approved  How to Take Advantage of iTunes for Video Capture</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-the-ultimate-selection-8-popular-audio-recording-applications/"><u>Updated In 2024, The Ultimate Selection 8 Popular Audio Recording Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-access-to-windows-print-services-dashboard/"><u>Demystifying Access to Windows Print Services Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-hidden-windows-bar-when-browser-frames-are-enlarged/"><u>Fixing Hidden Windows Bar when Browser Frames Are Enlarged</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-video-editing-made-easy-for-kids-top-free-and-paid-apps-for-2024/"><u>Updated Video Editing Made Easy for Kids Top Free and Paid Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-lava-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Lava</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-zen-of-zoom-talk-top-strategies-for-smooth-virtual-dialogue-for-2024/"><u>[Updated] The Zen of Zoom Talk  Top Strategies for Smooth Virtual Dialogue for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-achievements-to-your-retro-games-with-retroarch/"><u>How to Add Achievements to Your Retro Games With Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-make-every-snap-count-with-these-top-tips-for-2024/"><u>[Updated] Make Every Snap Count with These Top Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-app-when-it-cant-save-photos-or-videos-in-windows/"><u>How to Fix the Camera App When It Can't Save Photos or Videos in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hit-top-rank-firstrow-pursuits-outside-sports/"><u>[New] Hit Top Rank  Firstrow Pursuits Outside Sports</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-a-new-search-option-in-windows-11-task-manager/"><u>Introducing a New Search Option in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/spin-the-story-right-youtube-video-angles-demystified-guide/"><u>Spin the Story Right  YouTube Video Angles Demystified (Guide)</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediinate-and-rectify-the-iomap64-system-freeze-error/"><u>How To Immediinate and Rectify the IOMap64 System Freeze Error</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-asymmetric-windows-headphone-output/"><u>Adjusting Asymmetric Windows Headphone Output</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-parodic-play-writing-and-producing-humor-videos/"><u>In 2024, Parodic Play  Writing and Producing Humor Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-down-elusive-control-panel-options-on-windows-11/"><u>Hunt Down Elusive Control Panel Options on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-honor-90-lite-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Honor 90 Lite to New Phone | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-discover-the-secret-to-effortless-audio-conversion-on-windows-read-this-now/"><u>Updated 2024 Approved Discover the Secret to Effortless Audio Conversion on Windows Read This Now</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-how-to-transcribe-voice-to-written-words/"><u>Updated In 2024, How to Transcribe Voice to Written Words</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-electrical-footprint-of-your-windows-device/"><u>Exploring the Electrical Footprint of Your Windows Device</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/achieving-million-sub-milestone-the-youtube-guide/"><u>Achieving Million-Sub Milestone  The YouTube Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
</ul></div>
