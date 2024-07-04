---
title: "Accelerating Epic Launcher on PCs: A Quick Guide"
date: 2024-07-03T11:12:00.156Z
updated: 2024-07-04T11:12:00.156Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/infuse-personalized-style-in-windows-email-calendar/"><u>Infuse Personalized Style in Windows Email, Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/shine-the-light-how-to-make-your-cursor-more-noticeable-on-win1011/"><u>Shine the Light: How to Make Your Cursor More Noticeable on Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/snipping-tool-or-printscreen-best-windows-capture-strategy/"><u>Snipping Tool or Printscreen? Best Windows Capture Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/solve-no-errors-on-win11-quick-fix-guide/"><u>Solve No Errors on Win11 - Quick Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-normalcy-in-windows-11-user-access/"><u>Regaining Normalcy in Windows 11 User Access</u></a></li>
<li><a href="https://windows11.techidaily.com/enabledarkinterfacefornotepad/"><u>EnableDarkInterfaceForNotepad</u></a></li>
<li><a href="https://windows11.techidaily.com/shedding-windows-history-lightly-with-these-triads/"><u>Shedding Windows History Lightly with These Triads</u></a></li>
<li><a href="https://windows11.techidaily.com/rewiring-success-restoring-troubleshooters-in-windows-11/"><u>Rewiring Success: Restoring Troubleshooters in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-powertoys-worldwide-mouse-capabilities/"><u>Unlock PowerToy's Worldwide Mouse Capabilities</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-transform-your-youtube-routine-control-over-video-delivery-speeds/"><u>[Updated] Transform Your YouTube Routine  Control Over Video Delivery Speeds</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-vivo-y55s-5g-2023-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Vivo Y55s 5G (2023) Face Lock?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-aerial-imaging-face-off-dji-fpv-vs-gopro-max-x/"><u>[New] Aerial Imaging Face-Off  DJi FPV vs GoPro Max X</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-platforms-elevating-youtube-success-for-2024/"><u>Prime Platforms  Elevating YouTube Success for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-this-article-discusses-what-is-adobe-premiere-pro-how-to-download-install-and-use-it-and-its-key-features-it-further-discusses-its-alternative-for-e/"><u>Updated This Article Discusses What Is Adobe Premiere Pro, How to Download, Install and Use It, and Its Key Features. It Further Discusses Its Alternative for Editing Your Videos and More. Check Out Now</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-iphone-11-pro-max-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock iPhone 11 Pro Max with iTunes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-labyrinth-luminaries-top-10-roguelike-highlights/"><u>[Updated] In 2024, Labyrinth Luminaries  Top 10 Roguelike Highlights</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-deciphering-your-youtube-viewership-stats/"><u>In 2024, Deciphering Your YouTube Viewership Stats</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-dark-screens-on-mobile-devices/"><u>Correcting Dark Screens on Mobile Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-swiftly-tweak-your-stories-frame-rates-on-instagram/"><u>2024 Approved  Swiftly Tweak Your Stories' Frame Rates on Instagram</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>