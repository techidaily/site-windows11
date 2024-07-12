---
title: Combat Unknown OBS Record Error on Windows 11 PC
date: 2024-07-11T22:20:58.830Z
updated: 2024-07-12T22:20:58.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combat Unknown OBS Record Error on Windows 11 PC
excerpt: This Article Describes Combat Unknown OBS Record Error on Windows 11 PC
keywords: Fix OBS Windows Errors,Resolve OBS Glitches,Stop OBS Recording Failures,Correct OBS Crash in W11,Tackle OBS Issue on PC,Troubleshoot OBS Recordings,OBS Fix Unknown Errors
thumbnail: https://thmb.techidaily.com/75f2f8c580c180a2b2853a51a56b59840e62a47f848cf8becd199a47e930b0cb.jpg
---

## Combat Unknown OBS Record Error on Windows 11 PC

 OBS Studio is a great program to record and stream online. However, some users can't utilize OBS Studio because of a recording error that occurs when they try to record their screens. Instead of recording, OBS Studio throws up this message: "An unspecified error occurred while recording."

 The error usually appears when an important DLL file is missing, or there's corruption in the OBS Studio installation directory. As such, if you also see the same error, then try the below solutions to eliminate the problem for good.

## 1\. Restart OBS Studio

![Closing the OBS Studio Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/end-task.jpg)

 Whether you're [seeing a black screen](https://www.makeuseof.com/windows-11-obs-black-screen-fix/) or getting the "An unspecified error occurred while recording" error, the best way to fix any OBS Studio issue is to restart it. Restarting OBS Studio will clear the system resources and kill any temporary bugs or glitches that might be causing the error.

 To restart OBS Studio, open the**Task Manager** (see how to [open the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on OBS Studio, and choose**End Task.** Then, search for OBS Studio in the**Start Menu** and choose**Open** from the right pane.

## 2\. Temporarily Disable Your Graphics Driver

 The error is likely to occur if there's corruption in the GPU log file that is used by the OBS Studio. To remove the corruption, you'll have to disable the graphics driver before launching the OBS Studio. Doing this will force the program to create a new GPU log.

Here's what you need to do:

1. Open the**Power User Menu** by pressing the**Win + X** hotkey and choose**Device Manager** from the context menu.
2. In the Device Manager, double-click on the**Display adapters** node to expand it.
3. Right-click on the dedicated graphics driver and choose**Disable device.**  
![Disable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-device-option-1.jpg)
4. Click**Yes** to the prompt that appears.

 Your screen might flicker after disabling the dedicated graphics driver. But worry not; it'll become normal after the generic driver is started.

 Now, launch the OBS Studio and open your project. Then, open the Device Manager again > access the Display adapters node > right-click on the dedicated graphics driver and choose**Enable device.**

![Enable Device option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-device.jpg)

 That's it! Return to OBS Studio and check if you are able to record.

## 3\. Allow OBS Studio Through Your Firewall

 OBS Studio might fail to record and throw the error at hand if it's blocked under Windows Firewall. To fix this, you'll have to whitelist OBS Studio from the Windows Firewall blocked app list. Here's how to do that:

1. Press the**Win** key to open the**Start Menu.**
2. Type**Windows Firewall** in the search bar and press Enter.
3. Choose **Allow an app or feature through Windows Defender Firewall** option from the left sidebar.  
![Allow an app or feature through Windows Defender Firewall option in Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/allow-an-app-or-feature-through-windows-defender-firewall-option.jpg)
4. Click the**Change settings** button.
5. Click on**Allow another app** and then choose**Browse** from the**Add an app** prompt.  
![Add an app prompt in the Windows Firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-app.jpg)
6. Navigate to the location where you have installed the OBS Studio.
7. Select the**obs-ffmpeg-mux** executable file and click**Open.**  
![obs-ffmpeg-mux file in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/obs-ffmpeg-mux-file.jpg)
8. Click**Add.**
9. Check both the**Private** and**Public** boxes for**obs-ffmpeg-mux** and click**OK** to save the settings.  
![Private and Public boxes for OBS File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/private-and-public-boxes.jpg)

Restart your computer and check if the problem continues.

## 4\. Fix the Missing DLL Files

[Dynamic Link Libraries](https://www.makeuseof.com/what-are-dll-files-on-windows/) , aka DLL files, are special implementations of system libraries that contain various functions and variables that programs use when needed. If an important DLL file required by OBS Studio goes missing, you will see the "An unspecified error occurred while recording" error.

 To fix that, you will have to re-acquire the required DLL file. Here's how:

1. Navigate to the place where you have installed the OBS Studio.
2. Double-click on the obs-ffmpeg-mux file, and note down which of the following DLL file is missing.  
`avcodec-57.dll  
avformat-57.dll  
avutil-55.dll  
swresample-2.dll`
3. Follow our guide on [how to fix DLL files missing on Windows](https://www.makeuseof.com/tag/dll-files-missing-errors/) to repair the missing file.

Restart your computer and check for the issue.

## 5\. Edit the OBS-Ffmpeg-Mux Installation Folder

 If you're still facing the issue even after downloading the missing DLL file, then it indicates that OBS Studio is unable to find the required DLL. The solution, in this case, is to edit the Path environment so that OBS Studio finds the required DLL files.

You can do that by following the below instructions:

1. Press the**Win + I** key to open the**Settings** **app.**
2. In the System tab, choose the**About** option in the left pane.
3. Click the**Advanced system settings** option.  
![Advanced system settings option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-system-settings.jpg)
4. Click the**Environment Variables** button.  
![Environment Variables option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enviroment-variables.jpg)
5. Select**Path** under the**System Variables** section, and click the**Edit** button.
6. Paste the following path in the**Variable value** text box and click**OK.**  
`C:\Program Files (x86)\obs-studio\bin\32bit;`  
![Edit Variable in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-variable.jpg)

 That's it! Now, start recording in OBS Studio and check if the problem persists.

## 6\. Check for Corrupted or Missing Files

 Sometimes, OBS Studio might fail to record due to corruption in its installation folder. The problem can also occur if an important file is missing.

 In either case, you can use the "Check File Integrity" feature to scan the OBS installation for corruption and redownload broken/ missing files. Here's how to use that feature:

1. Launch OBS Studio, click the**Help** option at the top, and choose the**Check File Integrity** option from the context menu.  
![Check File Integrity option in OBS Studio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-file-integrity-option.jpg)
2. Click**Yes** to confirm your selection.

 OBS Studio will compare the available files with those on its server and download any missing or broken files.

 While you're at the OBS Studio home screen, check for and download any available updates. To do that, click**Help** and choose**Check for Updates** .

## 7\. Reinstall OBS Studio

 If you're still getting the error message, you're left with no option other than reinstalling OBS Studio. To do that, first [uninstall OBS Studio from Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) .

 Then, visit the [OBS Studio official website](https://obsproject.com/) , and download and install the latest version on your computer.

## Enjoy Seamless Recording With OBS Studio

 OBS Studio makes it a cakewalk to record anything and upload it online. However, due to corruption in its installation folder or missing DLL files, it might throw the "An unspecified error occurred while recording" error. Fortunately, you can quickly get rid of this error by applying the above fixes.


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
<li><a href="https://windows11.techidaily.com/deciphering-and-remedying-wins-error-messages/"><u>Deciphering & Remedying WINS Error Messages</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/things-you-must-know-for-screen-mirroring-apple-iphone-14-pro-max-drfone-by-drfone-ios/"><u>Things You Must Know for Screen Mirroring Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-paths-opening-system-information-at-your-fingertips/"><u>Direct Paths: Opening System Information at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-audio-wizards-handbook-navigating-complex-editing-tasks-with-sony-vegas-pro/"><u>New The Audio Wizards Handbook Navigating Complex Editing Tasks with Sony Vegas Pro</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/transform-ordinary-thumbnails-into-effervescent-designs/"><u>Transform Ordinary Thumbnails Into Effervescent Designs</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-perfecting-images-slideshow-and-fix-in-windows-11-photos-app/"><u>Guide to Perfecting Images: Slideshow & Fix in Windows 11 Photos App</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-the-comprehensive-obs-playbook-for-ps4-gamers/"><u>In 2024, The Comprehensive OBS Playbook for PS4 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-always-entering-cmos-mode-at-start-up/"><u>How to Stop Windows From Always Entering CMOS Mode at Start-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-notes-pop-in-win-1011-os/"><u>Making Your Notes Pop in Win 10/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-your-android-into-windows-11-webstreaming/"><u>Integrating Your Android Into Windows 11 Webstreaming</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-slack-notifications-fixes-for-windows-11/"><u>Reclaim Your Slack Notifications: Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-frequent-anydesk-windows-complications/"><u>Conquering Frequent AnyDesk Windows Complications</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowsapps-access-a-step-by-step-guide/"><u>Mastering WindowsApps Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-kali-with-windows-os-seamlessly/"><u>Combining Kali with Windows OS Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-keyboard-latency-in-win-os-with-top-7-hacks/"><u>Reduce Keyboard Latency in Win OS with Top 7 Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-update-notifications-on-windows/"><u>How to Disable Update Notifications on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/cloaked-observer-of-facebook-snapshots/"><u>Cloaked Observer of Facebook Snapshots</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-overlay-techniques-for-video-and-image-enhancement-with-windows-10/"><u>In 2024, Mastering Overlay Techniques for Video and Image Enhancement with Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-troubleshooters-not-working-in-windows-10-and-11/"><u>How to Fix the Troubleshooters Not Working in Windows 10 & 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-affordable-mic-picks-for-aspiring-yt-bands/"><u>2024 Approved  Affordable Mic Picks for Aspiring YT Bands</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-enable-a-search-bar-on-win11s-taskbar/"><u>Elevate Your Productivity: Enable a Search Bar on Win11's Taskbar</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-vs-paid-the-best-android-video-editors-for-every-budget/"><u>Updated Free vs Paid The Best Android Video Editors for Every Budget</u></a></li>
<li><a href="https://windows11.techidaily.com/must-use-3d-paint-shortcuts-compiled/"><u>Must-Use 3D Paint Shortcuts Compiled</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-essential-guide-to-metaverse-brand-strategies/"><u>[New] The Essential Guide to Metaverse Brand Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-rpc-failure-essential-steps-for-win-users/"><u>Overcoming RPC Failure: Essential Steps for Win Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-how-to-use-discord-text-to-speech/"><u>[Updated] How to Use Discord Text-To-Speech?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-share-permission-hurdles-in-win-os/"><u>Navigate Past Share Permission Hurdles in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-unique-windows-11-search-interface/"><u>Crafting a Unique Windows 11 Search Interface</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-game-on-with-updated-windows-11-gems/"><u>[Updated] Game On with Updated Windows 11 Gems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-narzo-60x-5g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme Narzo 60x 5G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-samsung-galaxy-f34-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Samsung Galaxy F34 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/a-deep-dive-into-zdsoft-recorder-features/"><u>A Deep Dive Into ZDSoft Recorder Features</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-essential-techniques-for-successful-desktop-tiktok-videos-for-2024/"><u>[New] Essential Techniques for Successful Desktop TikTok Videos for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/total-gaze-field-vr-device-overview/"><u>Total Gaze Field VR Device Overview</u></a></li>
<li><a href="https://windows11.techidaily.com/new-horizons-in-customizing-win11-ui/"><u>New Horizons in Customizing Win11 UI</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/highest-paid-youtuber-in-the-world/"><u>Highest Paid YouTuber in the World</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-nuances-of-windows-maintenance-and-update-scheduling/"><u>Navigate the Nuances of Windows Maintenance & Update Scheduling</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-best-screen-recording-software-top-10-list/"><u>[New] Best Screen Recording Software  Top 10 List</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-steams-server-disconnection-on-windows-machines/"><u>How to Rectify Steam's Server Disconnection on Windows Machines</u></a></li>
<li><a href="https://windows11.techidaily.com/new-dawn-for-old-gameshells-atlasos/"><u>New Dawn For Old Gameshells - AtlasOS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-ranking-the-finest-windows-11-video-grabbers-for-2024/"><u>[New] Ranking the Finest Windows 11 Video Grabbers for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-ultimate-combination-discover-5-advanced-webcams-for-clear-sound/"><u>[Updated] Ultimate Combination  Discover 5 Advanced Webcams for Clear Sound</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-m6-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Poco M6 5G Phone Without Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-stability-issues-with-vscode-on-w11/"><u>Preventing Stability Issues with VSCode on W11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-memorize-mastery-galaxy-phone-gameplay-archive/"><u>[New] 2024 Approved  Memorize Mastery  Galaxy Phone Gameplay Archive</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-oppo-find-x6-pro-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Oppo Find X6 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-creative-mc-survival-habitat-concepts-for-2024/"><u>[New] Creative MC Survival Habitat Concepts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/from-edge-to-frontline-quick-fixes-for-lost-off-screen-windows/"><u>From Edge to Frontline: Quick Fixes for Lost Off-Screen Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-purpose-behind-windows-11-s-mode-feature/"><u>Deciphering the Purpose Behind Windows 11 S Mode Feature</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/affectionate-articulations-venetian-verbal-flirtations/"><u>Affectionate Articulations: Venetian Verbal Flirtations</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-google-meet-entry-on-computersmobile-phones/"><u>[New] In 2024, Google Meet Entry  On Computers/Mobile Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstalling-favorite-apps-on-new-windows-11-devices/"><u>Guide to Reinstalling Favorite Apps on New Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-error-x-on-windows-a-guide-to-email-repair/"><u>Decoding Error X on Windows: A Guide to Email Repair</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/steps-for-incorporating-musical-elements-into-windows-compatible-gifs-for-2024/"><u>Steps for Incorporating Musical Elements Into Windows-Compatible GIFs for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/top-rated-vegas-pro-alternatives-for-mac-free-paid-and-premium-options-for-2024/"><u>Top-Rated Vegas Pro Alternatives for Mac Free, Paid, and Premium Options for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/simple-quick-and-free-make-your-own-discord-symbols-for-2024/"><u>Simple, Quick, and FREE - Make Your Own Discord Symbols for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-the-best-techniques-to-streamline-your-windows-folder-system/"><u>Explore the Best Techniques to Streamline Your Windows Folder System</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premium-4k-tvs-the-ultimate-list/"><u>Premium 4K TVs – The Ultimate List</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reinstating-original-size-for-win-11-icons/"><u>Guide to Reinstating Original Size for Win 11 Icons</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-step-by-step-to-free-digital-sound-logging-the-audacity-way-for-2024/"><u>New Step-by-Step to Free Digital Sound Logging The Audacity Way for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-hurdle-of-non-responding-email-alerts-on-pcs/"><u>Overcoming the Hurdle of Non-Responding Email Alerts on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/inspect-font-characters-windows-11-route/"><u>Inspect Font Characters: Windows 11 Route</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-financial-forecasting-in-the-world-of-youtube-snippet-creation/"><u>[New] 2024 Approved  Financial Forecasting in the World of YouTube Snippet Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-individual-user-settings-on-group-policy-level/"><u>Delving Into Individual User Settings on Group Policy Level</u></a></li>
<li><a href="https://extra-information.techidaily.com/pro-cloud-storage-guide-optimal-options-highlighted/"><u>Pro-Cloud Storage Guide  Optimal Options Highlighted</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-apex-servers-on-pc-7-ways-to-fix-no-server-errors-(156-chars/"><u>Mastering Apex Servers on PC: 7 Ways to Fix 'No Server' Errors (<156 Chars)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-honor-magic-vs-2-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Honor Magic Vs 2 Phones? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
</ul></div>
