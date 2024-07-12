---
title: How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
date: 2024-07-11T22:03:40.141Z
updated: 2024-07-12T22:03:40.141Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
keywords: Windows Error Fix Guide,Resolve Windows 11/10 Tokens Error,Stop Reference Token Issue,Solve Windows Token Error,Debugging Windows XP/10/11 Tokens,Correct Windows 10/11 Token Errors,Fixing Windows Token Reference Error
thumbnail: https://thmb.techidaily.com/3dd5b17c533ab88ed9cc0f3b00c7a2aa3b7c864b4f9c2a1611133710cbbaabe1.jpg
---

## How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/making-disabled-overlays-functional-again-on-windows-pc/"><u>Making Disabled Overlays Functional Again on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-for-avoidable-file-explorer-foibles/"><u>Best Practices for Avoidable File Explorer Foibles</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-realme-narzo-60x-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Realme Narzo 60x 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/delving-into-the-heart-of-viva-video-app/"><u>Delving Into the Heart of Viva Video App</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-top-5-low-weight-action-recorders-list/"><u>In 2024, Ultimate Top 5 Low-Weight Action Recorders List</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-uncovering-old-facebook-stories-with-ease/"><u>[New] 2024 Approved  Uncovering Old Facebook Stories with Ease</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reversal-strategies-moving-from-latest-sierra-to-el-capitan/"><u>2024 Approved  Reversal Strategies  Moving From Latest Sierra to El Capitan</u></a></li>
<li><a href="https://windows11.techidaily.com/hunt-down-elusive-control-panel-options-on-windows-11/"><u>Hunt Down Elusive Control Panel Options on Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/join-the-trendsetters-club-with-monthly-1k-followers/"><u>Join the Trendsetters Club with Monthly 1K Followers</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-eradicate-mmc-snap-in-anomalies/"><u>Expert Tips to Eradicate MMC Snap-In Anomalies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-harmonizing-songs-and-visuals-adding-youtube-music-to-videos/"><u>In 2024, Harmonizing Songs and Visuals  Adding YouTube Music to Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mystery-of-continuous-pauses-in-photo-booths/"><u>[Updated] Mystery of Continuous Pauses in Photo Booths</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/expert-advice-how-to-share-your-imovie-videos-on-vimeo-for-2024/"><u>Expert Advice  How to Share Your iMovie Videos on Vimeo for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-restore-error-0x80042306-quickly/"><u>Overcoming Windows Restore Error 0X80042306 Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-non-operational-wsreset-process-in-windows/"><u>How to Reactivate a Non-Operational WSReset Process in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-pcs-performance-dispose-of-bloatware/"><u>Enhance Your PC's Performance: Dispose of Bloatware</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-reno-10-proplus-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo Reno 10 Pro+ 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/ultimate-top-10-tools-for-professional-tiktok-editors-pc-for-2024/"><u>Ultimate Top 10 Tools for Professional TikTok Editors (PC) for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-how-to-be-a-virtual-visitor-in-friendly-tiktok-streams/"><u>In 2024, How to Be a Virtual Visitor in Friendly TikTok Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-a-fresh-pdf-file-reader-for-os-use/"><u>Choosing a Fresh PDF File Reader for OS Use</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-bring-your-pics-to-life-with-easy-text-editing-apps/"><u>2024 Approved  Bring Your Pics to Life with Easy Text Editing Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-zero-noise-videos-how-to-extract-audio-free-mp4mkvavimov-files/"><u>New Zero-Noise Videos How to Extract Audio-Free MP4/MKV/AVI/MOV Files</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-edge-how-pcs-beat-macs-in-9-aspects/"><u>Decoding the Edge: How PCs Beat Macs in 9 Aspects</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-step-by-step-easy-snapchat-videos-with-multiple-snaps/"><u>[Updated] 2024 Approved  Step-by-Step  Easy Snapchat Videos with Multiple Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-hidden-windows-bar-when-browser-frames-are-enlarged/"><u>Fixing Hidden Windows Bar when Browser Frames Are Enlarged</u></a></li>
<li><a href="https://windows11.techidaily.com/guaranteeing-gaming-glory-resolve-full-screen-woes-in-sonic-on-windows-11/"><u>Guaranteeing Gaming Glory: Resolve Full-Screen Woes in Sonic on Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-s18-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-reddit-poster-canvas-ratio/"><u>[Updated] In 2024, Reddit Poster Canvas Ratio</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Tecno Spark 20 Pro+ | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workspace-incorrante-folders-into-context-menu/"><u>Streamline Your Workspace: Incorrante Folders Into Context Menu</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-videotwitteraudio-direct-conversion-for-2024/"><u>[Updated] VideoTwitterAudio  Direct Conversion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-content-disconnected-error-on-windows-using-steam/"><u>Solving Content Disconnected Error on Windows Using Steam</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-the-complete-guide-to-decluttered-image-designs-on-canva/"><u>[Updated] 2024 Approved  The Complete Guide to Decluttered Image Designs on Canva</u></a></li>
<li><a href="https://howto.techidaily.com/fix-xiaomi-redmi-note-12-proplus-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Xiaomi Redmi Note 12 Pro+ 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-access-to-windows-print-services-dashboard/"><u>Demystifying Access to Windows Print Services Dashboard</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-camera-app-when-it-cant-save-photos-or-videos-in-windows/"><u>How to Fix the Camera App When It Can't Save Photos or Videos in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-the-electrical-footprint-of-your-windows-device/"><u>Exploring the Electrical Footprint of Your Windows Device</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exclusive-roundup-best-hdmi-21-tvs-compared-directly/"><u>2024 Approved  Exclusive Roundup  Best HDMI 2.1 TVs Compared Directly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-boost-engagement-with-top-tips-for-captivating-unboxing-videos/"><u>[New] Boost Engagement with Top Tips for Captivating Unboxing Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-the-old-guard-running-windows-11-on-pre-ultimate-pcs-via-to-go-and-rufus/"><u>Revitalizing the Old Guard: Running Windows 11 on Pre-Ultimate PCs via To Go & Rufus</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-windows-activate-derailed-handbrake/"><u>Conquer Windows: Activate Derailed HandBrake</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-efficiently-managing-windows-11-features/"><u>Mastering the Art of Efficiently Managing Windows 11 Features</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-outsmarting-tiktoks-unseen-ban-a-recovery-plan/"><u>In 2024, Outsmarting TikTok's Unseen Ban  A Recovery Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-cross-os-installation-of-kali-linux/"><u>Simplifying Cross-OS Installation of Kali Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-achievements-to-your-retro-games-with-retroarch/"><u>How to Add Achievements to Your Retro Games With Retroarch</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-seeking-speed-identifying-the-top-5-racer-games/"><u>[New] Seeking Speed  Identifying the Top 5 Racer Games</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-a-new-search-option-in-windows-11-task-manager/"><u>Introducing a New Search Option in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/command-guide-win11-starting-high-privilege-powershell/"><u>Command Guide: Win11 - Starting High-Privilege PowerShell</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-infinix-gt-10-pro-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Infinix GT 10 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-window-preferences-on-win11/"><u>Customize Your Window Preferences on Win11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-securing-perfect-images-on-pc-check-out-these-top-5-tools/"><u>[New] Securing Perfect Images on PC? Check Out These Top 5 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-unify-your-cloud-storage-onedrive-plus-microsoft-service/"><u>How to Unify Your Cloud Storage: OneDrive + Microsoft Service</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-for-crafting-personalized-audio-cds-from-your-mp3-collection-windows/"><u>Stepwise Guide for Crafting Personalized Audio CDs From Your MP3 Collection (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediinate-and-rectify-the-iomap64-system-freeze-error/"><u>How To Immediinate and Rectify the IOMap64 System Freeze Error</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-admin-error-for-apps/"><u>Bypassing Windows Admin Error for Apps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-best-hash-tracking-apps-a-comprehensive-review-fbtwitterinsta-for-2024/"><u>The Best Hash Tracking Apps  A Comprehensive Review (FB/Twitter/Insta) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-soundfulness-overcoming-muted-mouses-cry/"><u>Reclaim Soundfulness: Overcoming Muted Mouse's Cry</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-capture-clarity-enjoy-convenience-with-our-top-5-recorder-recommendations/"><u>[Updated] 2024 Approved  Capture Clarity, Enjoy Convenience with Our Top 5 Recorder Recommendations</u></a></li>
<li><a href="https://extra-hints.techidaily.com/visual-learning-tips-for-video-editing-in-schools/"><u>Visual Learning  Tips for Video Editing in Schools</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-update-blockage-error-e/"><u>Mending Windows Update Blockage, Error E</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-np-setting-detection-mishap/"><u>Resolving Windows NP Setting Detection Mishap</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-concealed-video-streaming-background-youtube-watch/"><u>[Updated] 2024 Approved  Concealed Video Streaming  Background YouTube Watch</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/15-top-newsroom-ambiance-tracks-compilation/"><u>15 Top Newsroom Ambiance Tracks Compilation</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-solutions-freeing-up-stuck-windows-11-pins/"><u>Quick Solutions: Freeing Up Stuck Windows 11 PINs</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-user-management-settings-in-windows-11-and-10/"><u>Navigate to User Management Settings in Windows 11 & 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-samsung-galaxy-xcover-6-pro-tactical-edition-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Samsung Galaxy XCover 6 Pro Tactical Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-absent-bluetooth-devices-manager/"><u>Remedy Absent Bluetooth Devices Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-error-0x80d03801-on-microsoft-store-pcs/"><u>Resolving Error 0X80D03801 on Microsoft Store PCs</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-engaging-audiences-with-facebooks-virtual-reality-content/"><u>[Updated] In 2024, Engaging Audiences with Facebook's Virtual Reality Content</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-path-resetting-windows-preferences-post-reboot/"><u>Instructional Path: Resetting Windows Preferences Post-Reboot</u></a></li>
</ul></div>
