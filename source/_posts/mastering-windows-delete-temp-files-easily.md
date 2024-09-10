---
title: "Mastering Windows: Delete Temp Files Easily"
date: 2024-09-09T11:58:20.775Z
updated: 2024-09-10T11:58:20.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Windows: Delete Temp Files Easily"
excerpt: "This Article Describes Mastering Windows: Delete Temp Files Easily"
keywords: WinTempDelete Guide,TempFiles Remove Quick,CleanWindows Temp,EasyWinTempClean,TempXP File Delete,XP TempFile Erase,Windows Temp Removal
thumbnail: https://thmb.techidaily.com/3f0dd2ba23afb65e6bd0d3f90edabc5ca5d9604be85f232f57f9da3d1c3125e2.jpg
---

## Mastering Windows: Delete Temp Files Easily

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136622/26400" target="_top" id="2136622">
  <img src="//a.impactradius-go.com/display-ad/26400-2136622" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136622/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135352/19272" target="_top" id="2135352">
  <img src="//a.impactradius-go.com/display-ad/19272-2135352" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135352/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-cyberspace-supplement-facebook-story-saver/"><u>[New] 2024 Approved  Cyberspace Supplement  Facebook Story Saver</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-a-comprehensive-look-at-youtuber-snippets-for-2024/"><u>[New] A Comprehensive Look at Youtuber Snippets for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-exploring-social-boundaries-sign-up-for-a-facebook-profile/"><u>[New] Exploring Social Boundaries  Sign Up for a Facebook Profile</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-optimal-free-cam-viewer-with-snatch-feature/"><u>[New] In 2024, Optimal Free Cam Viewer with Snatch Feature</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-viral-video-voyage-twitters-compiled-top-10-tiktoks/"><u>[New] In 2024, Viral Video Voyage  Twitter's Compiled Top 10 TikToks</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-the-ultimate-guide-to-youtube-video-distribution-on-fb-for-2024/"><u>[New] The Ultimate Guide to YouTube Video Distribution on FB for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-side-by-side-display-logging/"><u>[Updated] 2024 Approved  Side-by-Side Display Logging</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-igtvs-potential-5-ways-to-surge-follower-count/"><u>[Updated] 2024 Approved  Unlocking IGTV's Potential  5 Ways to Surge Follower Count</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-broadcasting-vimeo-content-efficiently-for-2024/"><u>[Updated] Broadcasting Vimeo Content Efficiently for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-become-audio-prodigy-installing-vrecorder-made-ahead/"><u>[Updated] In 2024, Become Audio-Prodigy - Installing VRecorder Made Ahead</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-top-tier-iphone-camera-apps-for-amateurs-and-experts-alike/"><u>[Updated] In 2024, Top-Tier iPhone Camera Apps for Amateurs & Experts Alike</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-understanding-instagrams-reels-vs-stories-format/"><u>[Updated] In 2024, Understanding Instagram’s Reels vs Stories Format</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-unleashing-potential-learning-to-race-with-drones-and-best-models/"><u>[Updated] In 2024, Unleashing Potential  Learning to Race with Drones and Best Models</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-secure-your-memories-long-term-webcam-video-storage-in-vlc/"><u>[Updated] Secure Your Memories  Long-Term Webcam Video Storage in VLC</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-right-sound-the-right-mic-top-recommendations-for-diverse-online-presence/"><u>[Updated] The Right Sound, The Right Mic  Top Recommendations for Diverse Online Presence</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-a-closer-look-at-earnings-comparing-dailymotion-and-youtube-revenues/"><u>2024 Approved  A Closer Look at Earnings  Comparing Dailymotion and YouTube Revenues</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-instructions-windows-movie-maker-version-6-installation/"><u>2024 Approved  Instructions  Windows Movie Maker Version 6 Installation</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-complete-srt-file-makers-handbook/"><u>2024 Approved  The Complete SRT File Maker's Handbook</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-to-download-and-update-amd-vega-56-drivers-on-your-pc-windows/"><u>Complete Guide to Download & Update AMD Vega 56 Drivers on Your PC (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-canary-a-guide-for-first-timers/"><u>Exploring Windows Canary: A Guide for First-Timers</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unlisted-device-detected-error-in-win1011/"><u>Fixing Unlisted Device Detected Error in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-lock-down-your-pcs-external-hard-drive-access/"><u>How To Lock Down Your PC's External Hard Drive Access</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-resolve-problems-when-your-discord-voice-chats-wont-connect/"><u>How to Resolve Problems When Your Discord Voice Chats Won't Connect</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-iphone-12-mini-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On iPhone 12 mini - 4 Easy Ways</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-from-apple-iphone-8-plus-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account From Apple iPhone 8 Plus?</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-into-ftdibussys-the-implications-for-windows-memory-safety/"><u>Insights Into ftdibus.sys: The Implications for Windows Memory Safety</u></a></li>
<li><a href="https://buynow-help.techidaily.com/is-applecareplus-the-right-protection-plan-for-your-iphone-or-ipad/"><u>Is AppleCare+ the Right Protection Plan for Your iPhone or iPad?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-gaming-3-methods-for-directory-unlock/"><u>Mastery in Gaming: 3 Methods for Directory Unlock</u></a></li>
<li><a href="https://windows11.techidaily.com/modernize-your-tech-consider-alternatives-to-windows/"><u>Modernize Your Tech: Consider Alternatives to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mute-non-met-requirement-notifications-on-windows/"><u>Mute Non-Met Requirement Notifications on Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/no-more-interruptions-in-battle-the-infamous-overwatch-driver-crash-fixed-for-good/"><u>No More Interruptions in Battle: The Infamous Overwatch Driver Crash Fixed for Good</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/professional-grade-hd-video-editing-software-top-5-recommendations-for-2024/"><u>Professional-Grade HD Video Editing Software Top 5 Recommendations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-and-easy-window-11-app-opener-techniques/"><u>Quick and Easy Window 11 App Opener Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-devices-in-sleep-mode-step-by-step-guide-for-windows-11/"><u>Reactivating Devices in Sleep Mode: Step-by-Step Guide for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/reactive-keys-reclaiming-shift-on-win/"><u>Reactive Keys: Reclaiming Shift on Win.</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-power-consumption-while-maintaining-peak-performance/"><u>Reducing Power Consumption While Maintaining Peak Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-inaudible-audio-on-wireless-devices/"><u>Resolving Inaudible Audio on Wireless Devices</u></a></li>
<li><a href="https://driver-install.techidaily.com/restarting-amd-support-for-latest-windows-oss/"><u>Restarting AMD Support for Latest Windows OSs</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-memory-safety-in-windows-11s-system-settings/"><u>Restoring Memory Safety in Windows 11'S System Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/revamping-your-networks-first-line-of-defense/"><u>Revamping Your Network's First Line of Defense</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-do-not-have-sufficient-privileges-uninstall-on-windows/"><u>Sidestep 'Do Not Have Sufficient Privileges': Uninstall on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-your-inked-woes-a-guide-to-fixing-windows-pen-devices/"><u>Solve Your Inked Woes: A Guide to Fixing Windows Pen Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-silent-setbacks-ccleaner-issues-in-windows-11/"><u>Solving Silent Setbacks: CCleaner Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-w10w11-interruptexception-bsod-a-comprehensible-guide/"><u>Solving W10/W11 INTERRUPT_EXCEPTION BSOD: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-boot-streamlining-your-win11-routines/"><u>Speedy Boot: Streamlining Your Win11 Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-supercharged-vram-on-windows-10-and-11/"><u>Step-by-Step to Supercharged VRAM on Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-steps-launching-your-admin-privileged-powershell-console/"><u>Strategic Steps: Launching Your Admin Privileged PowerShell Console</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-system-call-failures-in-windows/"><u>Strategies to Fix System Call Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-pc-functionality-addressing-11-windows-problems/"><u>Streamlining PC Functionality - Addressing 11 Windows Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-audio-advantage-top-4-programs-for-surpassing-windows-100-limit/"><u>The Audio Advantage: Top 4 Programs for Surpassing Windows' 100%% Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/the-easy-switch-for-classic-gaming-in-the-windows-photo-hub/"><u>The Easy Switch for Classic Gaming in the Windows Photo Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/the-five-fold-windows-11-data-collection/"><u>The Five-Fold Windows 11 Data Collection</u></a></li>
<li><a href="https://windows11.techidaily.com/the-os-metamorphosis-insights-into-w10-and-w11-developments/"><u>The OS Metamorphosis: Insights Into W10 and W11 Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/the-role-and-risks-involved-with-deleting-pagefilesys-files/"><u>The Role & Risks Involved with Deleting Pagefile.sys Files</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-garmin-forerunner/"><u>The Ultimate Guide to Garmin Forerunner</u></a></li>
<li><a href="https://windows11.techidaily.com/the-unseen-consequences-of-cost-saving-windows-activation/"><u>The Unseen Consequences of Cost-Saving Windows Activation</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/top-performance-test-comprehensive-review-of-the-gigabyte-aorus-fo32u2p-ultra-fast-240hz-and-stunning-4k-oled-display-for-gamers/"><u>Top-Performance Test: Comprehensive Review of the Gigabyte Aorus FO32U2P - Ultra-Fast 240Hz and Stunning 4K OLED Display for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-steams-access-issue-for-games-on-win11/"><u>Unblocking Steam's Access Issue for Games on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-compressed-storage-on-windows-11/"><u>Unlocking Compressed Storage on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-ios-calendar-in-your-windows-environment/"><u>Unlocking iOS Calendar in Your Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-successful-remote-steam-connectivity/"><u>Unlocking Successful Remote Steam Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/unravel-the-power-of-windows-redos-using-hotkey-keys/"><u>Unravel the Power of Windows Redos Using Hotkey Keys</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unraveling-rcs-technology-the-future-of-text-and-multimedia-exchange/"><u>Unraveling RCS Technology: The Future of Text and Multimedia Exchange</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-system-restore-issue-0x80042306-in-win10/"><u>Unraveling System Restore Issue 0X80042306 in Win10</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-virtualdub-is-it-still-the-best-video-editor-top-alternatives/"><u>Updated 2024 Approved Virtualdub Is It Still the Best Video Editor? Top Alternatives</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-avs-video-editor-2023-review-a-beginners-guide-to-video-editing-software/"><u>Updated AVS Video Editor 2023 Review A Beginners Guide to Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/win11win10s-unidentified-device-fix-guide/"><u>Win11/Win10's 'Unidentified Device' Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ram-cache-basics-and-cleansing-methods/"><u>Windows RAM Cache Basics and Cleansing Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>