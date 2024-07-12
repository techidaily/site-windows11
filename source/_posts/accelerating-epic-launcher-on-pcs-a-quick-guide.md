---
title: "Accelerating Epic Launcher on PCs: A Quick Guide"
date: 2024-07-11T22:11:50.001Z
updated: 2024-07-12T22:11:50.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerating Epic Launcher on PCs: A Quick Guide"
excerpt: "This Article Describes Accelerating Epic Launcher on PCs: A Quick Guide"
keywords: Epic Launch Speed,PC Game Acceleration,Quick Epic Launch Guide,Optimize Gaming Experience,Fast Epic Launcher Tips,Accelerating Games PC,Quick Epic Launch Help
thumbnail: https://thmb.techidaily.com/07d8502ce17333e6cd775d39369b0980ba5462f8a32cd1145e8a4d708fb6bf52.png
---

## Accelerating Epic Launcher on PCs: A Quick Guide

 Does the Epic Games Launcher take a long time to download games? In general, download speeds drop due to other devices or processes hogging network resources, leaving little bandwidth for the Epic Games client to use.

 Besides that, a piled-up launcher cache, a backend issue with Epic Games servers, some Windows-specific issues, or forcing the client to throttle downloads can also slow down download speeds.

 If you want to speed up your downloads on the Epic Games Launcher, here are a few tweaks you may want to check out.

## 1\. Check for Problems With the Backend

 It's possible to get super slow download speeds in Epic Games if there is a backend issue with the client or any other Epic Games service. Therefore, if your download speed has dropped unexpectedly, ensure all Epic Games servers and systems are up and running and the cause of the problem is not there.

 You can check that in several ways, but here's the easiest: go to [Epic Games' status page](https://status.epicgames.com/) and check if everything is up and running, shown as green. If any outages are listed there, represented by a red or yellow color, wait for Epic Games to resolve the backend problem, and the download speed will return to normal.

![All Systems Showing as Operational on the Epic Games Status Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/all-systems-showing-as-operational-on-the-epic-games-status-page.jpg)

 If all systems appear to function correctly, then there's nothing wrong with the backend. In that case, move on to the next fix.

## 2\. Basic Steps to Perform Before Optimizing the Epic Games Launcher

 Once you've confirmed that there are no backend issues impacting download speeds, take the following steps before optimizing the Epic Games Launcher:

* Slow or unstable internet connections can also slow down downloads. Therefore, [use speed checking websites to check the speed of your internet connection](https://www.makeuseof.com/best-free-websites-test-internet-speed/), and if it is slower than usual, take the necessary steps to speed it up.
* Close all processes on your primary device that could be straining your bandwidth resources, and disconnect other devices connected to the same internet connection. Consequently, the Epic Games Launcher will have access to the maximum bandwidth.
* Disable any VPN or proxy server you use to make your browsing more private. Such connections protect our privacy but can seriously slow the download process.

 After performing the above checks and fixes, move on to the main fixes.

## 3\. Disable Downloads Throttling

 The Epic Games client allows users to throttle downloads when playing games or using network resources for something more substantial. This handy setting prevents the launcher from overstressing your bandwidth during a game update or installation.

 When this option is enabled, the Epic Games Launcher will not let the download speed reach its maximum potential, which leads to slower download speeds. As such, you should ensure this feature is not enabled in the client's settings. To check that, follow these steps:

1. Launch the Epic Games Launcher.
2. Click the **profile icon** in the top right corner and select **Settings**.  
![Open Settings in the Epic Games Launcher](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/2-open-settings-in-the-epic-games-launcher.jpg)
3. Make sure that the box beside **Throttle Downloads** isn't checked.
4. If it was checked before, click the box once to uncheck it.  
![Disable the Throttle Downloads Option in the Epic Games Launcher Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/3-disable-the-throttle-downloads-option-in-the-epic-games-launcher-settings.jpg)

## 4\. Prioritize the Epic Games Launcher Over Everything Else

 The Windows operating system prioritizes essential system processes over third-party ones. Consequently, it allocates the most resources to prioritized processes to improve efficiency. As Epic Games processes are also third-party, they are also viewed as low priority. Hence fewer resources are allocated to them.

 To ensure that the system prioritization isn't slowing down the downloads, you should set the launcher's processes as high-priority. This way, the system will allocate maximum bandwidth resources to the Epic Games Launcher, allowing it to download files faster. To make Epic Games processes a priority, follow these steps:

1. Type **"Task Manager"** in Windows Search and open **Task Manager**.
2. Navigate to the **Details** tab of the Task Manager.
3. Locate the **EpicGamesLauncher.exe** process.
4. Right-click on this process, navigate to **Set Priority,** and select **High**.  
![Change the Priority of the Epic Games Launcher Process in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/4-change-the-priority-of-the-epic-games-launcher-process-in-task-manager.jpg)

## 5\. Clear Epic Games Launcher's Cache

 The Epic Games Launcher keeps some data in its cache, which makes it easier for the client to find and load necessary information faster. If not cleared timely, the accumulated cache can lead to unforeseen problems, including slow download speeds. Therefore, it is imperative to clear the cache, especially if it hasn't been cleared in a while.

 To delete the Epic Games Launcher's cache, follow these steps:

1. Press **Win+R**, type **"%appdata%"** and press **Enter**.
2. Navigate to **Local > EpicGamesLauncher > Saved** folders.
3. Delete each **webcache** folder you find.  
![Delete the Webcache Folder in the Epic Games Launcher Installation Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/5-delete-the-webcache-folder-in-the-epic-games-launcher-installation-folder.jpg)

## 6\. Reconfigure the Engine.ini File

 According to Reddit users and numerous YouTubers, modifying the Engine.ini file in the Epic Games installation folder can also make the download process faster. Follow these steps to reconfigure the file:

1. Press **Win+R**, type **"%appdata%"** and press **Enter**.
2. Navigate to **Local > EpicGamesLauncher > Saved > Config > Windows** folders.
3. Here, right-click the **Engine.ini** file and open it with Notepad or any other text editor.  
![Open the Engine.ini File in Notepad From the Epic Games Installation Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/6-open-the-engine-ini-file-in-notepad-from-the-epic-games-installation-folder.jpg)
4. Delete all the content in this file and add the following code instead:  
`[HTTP]  
HttpTimeout=10  
HttpConnectionTimeout=10  
HttpReceiveTimeout=10  
HttpSendTimeout=10  

[Portal.BuildPatch]  
ChunkDownloads=3  
ChunkRetries=20  
RetryTime=0.5`
5. Press **CTRL+S** to save the file. After that, close it.  
![Save the Engine.ini File After Adding Few Commands in It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/7-save-the-engine-ini-file-after-adding-few-commands-in-it-1.jpg)
6. Restart the Epic Games Launcher again.

 If tweaking Engine.ini starts to adversely affect download speed, as some users have reported, you should revert the changes.

## 7\. Perform Some Windows-Specific Changes to Speed Up Downloads

 Here're a few Windows-specific changes that can speed up downloads in the Epic Games Launcher:

* Changing your DNS settings to Google's public DNS is well-known for boosting download speeds for most apps and clients. So, [switch your DNS server](https://www.makeuseof.com/tag/change-dns-increase-internet-speed/) and see whether the download speed improves.
* [Whitelist the Epic Games Launcher from Microsoft Defender](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) and any third-party antivirus you use. This will prevent security suites from restricting or limiting download activity in any way.

## Speed Up the Epic Games Launcher Downloads

 Waiting hours to install a game or update an existing one can ruin our day. Hopefully, the above steps will help you optimize the Epic Games Launcher and speed up downloads. If nothing works and downloads keep lagging, remove the existing launcher installation and reinstall it again from scratch.

 If your internet connection is slow, the above checks may not significantly increase download speed. If this is the case for you, switch to a different service provider or internet package.

 Besides that, a piled-up launcher cache, a backend issue with Epic Games servers, some Windows-specific issues, or forcing the client to throttle downloads can also slow down download speeds.

 If you want to speed up your downloads on the Epic Games Launcher, here are a few tweaks you may want to check out.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/stitch-storytelling-creating-content-that-closes-the-gap/"><u>Stitch Storytelling  Creating Content that Closes the Gap</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-computers-windows-key-settings/"><u>Mastering Your Computer’s Windows Key Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-network-path-with-fixed-ea-server-error-in-os/"><u>Restoring Network Path with Fixed EA Server Error in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-resolving-directdraw-failures-on-windows-1011/"><u>Immediate Actions for Resolving DirectDraw Failures on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-windows-dashboard-incorporate-portable-apps/"><u>Personalize Your Windows Dashboard: Incorporate Portable Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-efficiency-the-5-uptime-test-routines/"><u>Maximizing Windows 11 Efficiency: The 5 Uptime Test Routines</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-easy-ways-to-edit-recorded-video/"><u>Updated 2024 Approved Easy Ways to Edit Recorded Video</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/activatedeactivate-smartscreen-filter-on-windows-11/"><u>Activate/Deactivate SmartScreen Filter on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-from-vid-to-gif-28-expert-approved-conversion-software/"><u>2024 Approved From Vid to GIF 28 Expert-Approved Conversion Software</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-editing-skills-mastering-jumps-and-pastes/"><u>Elevate Editing Skills: Mastering Jumps & Pastes</u></a></li>
<li><a href="https://windows11.techidaily.com/facing-down-rounded-corners-in-windows-11/"><u>Facing Down Rounded Corners in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-effortless-steps-to-blur-distractions-in-google-meets/"><u>2024 Approved  Effortless Steps to Blur Distractions in Google Meets</u></a></li>
<li><a href="https://screen-capture.techidaily.com/advanced-screen-recording-of-facetime-dialogues-for-2024/"><u>Advanced Screen Recording of FaceTime Dialogues for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-14-plus-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>How To Transfer Data from Apple iPhone 14 Plus to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-chromiums-firewall-connection-within-windows-safeguards/"><u>Enabling Chromium's Firewall Connection Within Windows Safeguards</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-video-setup-starter-kit-for-excursion-documentation/"><u>[New] In 2024, Video Setup Starter Kit for Excursion Documentation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-viewers-to-profits-an-authoritative-guide-on-youtube-revenue-and-popularity-analysis-for-2024/"><u>[New] From Viewers to Profits  An Authoritative Guide on YouTube Revenue and Popularity Analysis for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-to-maximize-windows-ram/"><u>Breaking Down Barriers to Maximize Windows' RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/inside-look-how-to-reach-windowsstore-folder/"><u>Inside Look: How To Reach WindowsStore Folder</u></a></li>
<li><a href="https://windows11.techidaily.com/lowering-gameplay-stress-reducing-cpu-load-while-playing/"><u>Lowering Gameplay Stress: Reducing CPU Load While Playing</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-cut-trim-and-edit-top-10-free-mp4-video-editing-solutions/"><u>Updated In 2024, Cut, Trim, and Edit Top 10 Free MP4 Video Editing Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-error-messages-post-installed-application-failure/"><u>Deciphering Error Messages Post Installed Application Failure</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-unleash-your-inner-jellyfish-how-to-apply-clownfish-voice-changes-on-fortnite-and-beyond/"><u>New Unleash Your Inner Jellyfish How to Apply Clownfish Voice Changes on Fortnite and Beyond</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-instagram-video-promotion-mastery-craft-your-winning-market-plan/"><u>2024 Approved  Instagram Video Promotion Mastery  Craft Your Winning Market Plan</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-directdraw-fixes-on-modern-microsoft-oses/"><u>Navigating the Maze of DirectDraw Fixes on Modern Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/quash-insufficient-requirement-notice-windows-11/"><u>Quash Insufficient Requirement Notice Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-landscape-of-android-and-windows-file-sharing/"><u>Navigating the Landscape of Android & Windows File Sharing</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-vivo-v27-pro-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Vivo V27 Pro Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-github-desktop-with-windows-11-os/"><u>Step-by-Step Guide to GitHub Desktop with Windows 11 OS</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-metaverse-mirth-makers-top-tips-for-crafting-hilarious-virtual-images-for-2024/"><u>[New] Metaverse Mirth Makers  Top Tips for Crafting Hilarious Virtual Images for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-innovative-posting-add-youtube-to-your-insta-narratives-for-2024/"><u>[Updated] Innovative Posting  Add YouTube to Your Insta Narratives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-various-windows-techniques-for-program-activation/"><u>Exploring Various Windows Techniques for Program Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-keep-windows-full-screen-without-mobility-features/"><u>How To Keep Windows Full Screen without Mobility Features</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-excessive-ram-allocation-in-connected-devices-interface/"><u>Resolving Excessive RAM Allocation in Connected Devices Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/method-for-icon-position-restoration-in-windows/"><u>Method for Icon Position Restoration in WIndows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/auditory-purity-in-ffmpeg-a-format-friendly-perspective-for-2024/"><u>Auditory Purity in FFmpeg  A Format-Friendly Perspective for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/flip-to-impress-the-instagram-video-guide-for-2024/"><u>Flip to Impress  The Instagram Video Guide for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unseen-underpinnings-of-user-interface-craftsmanship/"><u>Unseen Underpinnings of User Interface Craftsmanship</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-how-windows-sustains-ongoing-optimization/"><u>Deciphering How Windows Sustains Ongoing Optimization</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harness-the-power-of-keywords-top-selection-software-unveiled/"><u>[New] 2024 Approved  Harness the Power of Keywords  Top Selection Software Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-trending-tweet-treasures-1-10-showdown/"><u>[Updated] 2024 Approved  Trending Tweet Treasures  #1-#10 Showdown</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-beginners-guide-going-live-with-ease-on-facebook/"><u>2024 Approved  Beginner’s Guide  Going Live with Ease on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-cannot-link-with-nvidia-in-windows-11/"><u>How to Rectify Cannot Link with NVIDIA in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-frustration-quick-fixes-for-windows-11-woes/"><u>No More Frustration! Quick Fixes for Windows 11 Woes</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-best-rated-android-podcasters/"><u>[New] Best-Rated Android Podcasters</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-14-pro-to-roku-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 14 Pro to Roku? | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/maintaining-monitor-harmony-on-w11-systems/"><u>Maintaining Monitor Harmony on W11 Systems</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-mkv-video-editing-made-easy-top-mac-trimmers-2023/"><u>2024 Approved MKV Video Editing Made Easy Top Mac Trimmers 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-rockalldlldll-not-found-on-windows-devices/"><u>Fix for 'Rockalldll.dll' Not Found on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-windows-file-navigation-a-guide-excluding-ls/"><u>Enhanced Windows File Navigation: A Guide Excluding LS</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-personalize-phone-chimes-a-whatsapp-tone-builders-manual/"><u>In 2024, Personalize Phone Chimes  A WhatsApp Tone Builder's Manual</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-infographic-yearbook-of-2017s-youtube-insights-and-trends-for-2024/"><u>The Infographic Yearbook of 2017'S Youtube Insights & Trends for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-powershell-script-execution-policy-landscape/"><u>Navigating the PowerShell Script Execution Policy Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-screen-disruptions-secure-smooth-play-on-w11-with-sonic-frontiers/"><u>Overcoming Screen Disruptions: Secure Smooth Play on W11 with Sonic Frontiers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-affordable-pc-screen-grabber-selection-list/"><u>In 2024, Affordable PC Screen Grabber Selection List</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pioneering-tools-for-the-future-of-3d-model-and-animation-artistry/"><u>Pioneering Tools for the Future of 3D Model & Animation Artistry</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-dormant-windows-11-control-panel-options/"><u>Bring Forth Dormant Windows 11 Control Panel Options</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-selected-best-5-youtube-script-writing-ai-customized-for-you/"><u>Updated In 2024, Selected Best 5 YouTube Script Writing AI Customized for You</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-and-correcting-windows-security-faults-in-windows-11/"><u>Avoiding and Correcting Windows Security Faults in Windows 11</u></a></li>
</ul></div>
