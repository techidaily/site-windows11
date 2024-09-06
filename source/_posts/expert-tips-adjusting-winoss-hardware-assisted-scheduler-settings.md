---
title: "Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
date: 2024-09-05T02:08:26.945Z
updated: 2024-09-06T02:08:26.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
excerpt: "This Article Describes Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings"
keywords: WinOS Scheduling Guide,Optimize Windows Performance,Hardware Scheduler Tweaks,Enhance OS Speed Windows,WinOS System Tuning Tips,Advanced Windows Setup,Custom Scheduler Settings
thumbnail: https://thmb.techidaily.com/965071db1f866296dbd6b7c6cdfb4395621995dd58483ee49e8397ad83cab217.jpg
---

## Expert Tips: Adjusting WinOS's Hardware-Assisted Scheduler Settings

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2031472/7443" target="_top" id="2031472">
  <img src="//a.impactradius-go.com/display-ad/7443-2031472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2031472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024351/7443" target="_top" id="2024351">
  <img src="//a.impactradius-go.com/display-ad/7443-2024351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

<!-- affiliate ads begin -->
<span id="1983551">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983551.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983551">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983551.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983551%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983551/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enhancing-winter-vlogs-with-five-heartwarming-backdrops/"><u>[New] 2024 Approved  Enhancing Winter Vlogs with Five Heartwarming Backdrops</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-in-depth-look-at-frozen-delight-recording-software/"><u>[New] 2024 Approved  In-Depth Look at Frozen Delight Recording Software</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-exclusive-review-top-10-budget-friendly-video-meetup-apps-for-companies-and-schools-for-2024/"><u>[New] Exclusive Review  Top 10 Budget-Friendly Video Meetup Apps for Companies & Schools for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-full-scale-funds-assessment-kickstarting-your-podcast-dream/"><u>[New] Full-Scale Funds Assessment  Kickstarting Your Podcast Dream</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-budget-friendly-video-editing-masterclass-on-vimeo/"><u>[New] In 2024, Budget-Friendly Video Editing Masterclass on Vimeo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-optimizing-igtv-video-success-metrics/"><u>[New] Optimizing IGTV Video Success Metrics</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-your-computer-was-unable-to-start/"><u>[Solved] Your Computer Was Unable To Start</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-camera-stabilizers-for-youtube-for-2024/"><u>[Updated] Best Camera Stabilizers for YouTube for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-compelling-choices-macs-excellent-snipping-tools/"><u>[Updated] Compelling Choices  Mac's Excellent Snipping Tools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-comprehensive-guide-to-youtube-content-moderation-rules-for-2024/"><u>[Updated] Comprehensive Guide to YouTube Content Moderation Rules for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-epic-audio-essentials-top-10-for-trending-yt-shorts/"><u>[Updated] Epic Audio Essentials  Top 10 for Trending YT Shorts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-ultimate-hd-capture-top-tier-recorder-titles/"><u>[Updated] In 2024, Ultimate HD Capture  Top-Tier Recorder Titles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-top-16-youtube-starting-points-to-enhance-view-count/"><u>[Updated] Top 16 YouTube Starting Points to Enhance View Count</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-auditory-ambience-finder-for-film-and-video-sets/"><u>2024 Approved  Auditory Ambience Finder  For Film and Video Sets</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-maximizing-accuracy-speech-to-text-via-google-translate/"><u>2024 Approved  Maximizing Accuracy  Speech to Text via Google Translate</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-ranchers-revelry-best-friendly-farming-titles-for-gathering-pals/"><u>2024 Approved  Ranchers' Revelry  Best Friendly Farming Titles for Gathering Pals</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-elite-selection-of-top-12-tycoons-perfect-for-strategic-souls/"><u>2024 Approved  The Elite Selection of Top 12 Tycoons - Perfect for Strategic Souls</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-honor-100-pro-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Honor 100 Pro to Roku | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-github-desktop-usage-for-novice-windows-11-users/"><u>Essential Guide to GitHub Desktop Usage for Novice Windows 11 Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/firecapture-pro-for-ff-for-2024/"><u>FireCapture Pro for FF for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/fix-motorola-razr-40-ultra-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Motorola Razr 40 Ultra Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-responsive-nvidia-control-panel-in-w11/"><u>Fixing Non-Responsive NVidia Control Panel in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-windows-powershell-as-an-administrator-in-windows-11/"><u>How to Open Windows PowerShell as an Administrator in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-windows-no-write-file-saving-problems/"><u>How to Tackle Windows No Write File Saving Problems</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-capture-every-angle-top-360-streaming-devices-reviewed/"><u>In 2024, Capture Every Angle  Top 360° Streaming Devices Reviewed</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-patterned-pixels-looms-guide-to-screen-casting/"><u>In 2024, Patterned Pixels  Loom's Guide to Screen Casting</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-realme-c55-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Realme C55 Device</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-review-of-the-netgear-orbi-range-extender-rb50-y/"><u>In-Depth Review of the Netgear Orbi Range Extender (RB50 Y)</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-unique-lock-patterns-in-windows-11-systems/"><u>Integrating Unique Lock Patterns in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-fatal-error-code-0x800f0831-with-ease/"><u>Navigating Past Fatal Error Code 0X800f0831 with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-wacatacbml-scourge-in-windows-environments/"><u>Navigating Through the Wacatac.B!ml Scourge in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-troubles-in-windows-discord-searches/"><u>Navigating Troubles in Windows Discord Searches</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-are-you-an-apple-user-interested-in-adding-a-slow-mo-to-their-videos-this-article-features-an-exceptional-procedure-for-creating-slow-mo-i/"><u>New 2024 Approved Are You an Apple User Interested in Adding a Slow-Mo to Their Videos? This Article Features an Exceptional Procedure for Creating Slow-Mo in iMovie</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-hidden-network-setup-issue/"><u>Overcoming Windows' Hidden Network Setup Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/preserve-your-tailored-powertoys-environment-at-new-devices/"><u>Preserve Your Tailored PowerToys Environment at New Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/prime-video-picks-most-watched-of-all-time-for-2024/"><u>Prime Video Picks  Most Watched of All Time for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-access-to-windows-router-configuration/"><u>Recover Access to Windows Router Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-conflicts-easy-access-to-your-printer/"><u>Resolving Conflicts: Easy Access to Your Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlined-workflows-with-uwp-app-shortcuts-on-windows-11/"><u>Streamlined Workflows with UWP App Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-ssds-in-windows-mastery-of-ssd-fresh/"><u>Supercharge SSDs in Windows - Mastery of SSD Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-for-stuck-windows-update-fixers/"><u>Swift Solutions for Stuck Windows Update Fixers</u></a></li>
<li><a href="https://windows11.techidaily.com/sync-solutions-for-win1011-users-with-adobe-not-available/"><u>Sync Solutions for Win10/11 Users with Adobe Not Available</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-persistent-ms-teams-authentication-problems/"><u>Tackling Persistent MS Teams Authentication Problems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/tailoring-your-vtubers-tone-best-app-recommendations-unveiled/"><u>Tailoring Your Vtuber's Tone  Best App Recommendations Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-9-reasons-for-transitioning-to-modern-outlook/"><u>The Ultimate List of 9 Reasons for Transitioning to Modern Outlook</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-brightness-tools-for-windows-multi-screen-setups/"><u>Top 6 Brightness Tools for Windows Multi-Screen Setups</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-onedrive-icon-from-the-file-explorer-palette/"><u>Trimming Down OneDrive Icon From the File Explorer Palette</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-guide-solving-virtualboxs-usb-error-on-windows-os/"><u>Troubleshooting Guide: Solving VirtualBox's 'USB Error' On Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unretrievable-graphics-settings-via-geforce-experience-windows-11/"><u>Troubleshooting Unretrievable Graphics Settings via GeForce Experience, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-11-for-5ghz-wi-fi-issues/"><u>Troubleshooting Windows 11 for 5GHz Wi-Fi Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-the-invisible-workers-in-win11/"><u>Uncovering the Invisible Workers in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-potential-for-in-depth-storage-analysis-with-diskusage-on-windows/"><u>Unleashing the Potential for In-Depth Storage Analysis with DiskUsage on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-masters-realm-command-center-admin-panel/"><u>Unlocking The Master's Realm: Command Center Admin Panel</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-potential-from-esd-to-iso-file-transformation/"><u>Unlocking Windows' Potential: From ESD to ISO File Transformation</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-winning-strategies-in-old-chessboard-manager/"><u>Unlocking Winning Strategies in Old Chessboard Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-wacatacbml-mystery-and-removal-guide-for-windows-pcs/"><u>Unveiling: The Wacatac.B!ml Mystery & Removal Guide for Windows PCs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>