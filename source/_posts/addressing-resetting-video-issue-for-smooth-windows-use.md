---
title: Addressing Resetting Video Issue for Smooth Windows Use
date: 2024-07-11T22:13:23.900Z
updated: 2024-07-12T22:13:23.900Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Resetting Video Issue for Smooth Windows Use
excerpt: This Article Describes Addressing Resetting Video Issue for Smooth Windows Use
keywords: Fix Video Freeze,Smooth Windows Playback,Resolve Screen Pause,Clear Video Glitches,Unlock Windows Videos,Stop Video Resets,Enhance Video Performance
thumbnail: https://thmb.techidaily.com/97b0ddc570e6ff11d98aa739ad9094bf8b6916f3ca7d54eab5f1d4007ba674c0.JPG
---

## Addressing Resetting Video Issue for Smooth Windows Use

 Users have widely reported an error message that says “Video driver crashed and was reset” pops up when playing or trying to start Windows games. This error message crashes games whenever it arises. Players have reported that the issue usually occurs in games like Fortnite, ARK: Survival, Final Fantasy 7, and Sea of Thieves, among others.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.

## 1\. Utilize the Video Playback Troubleshooter

 The Video Playback troubleshooter might be useful for fixing the “Video driver crashed” error when that error affects video playback. That is a troubleshooter for fixing video playback issues, which the “Video driver crashed” error sometimes is. Our [how to run any Windows troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) guide provides instructions for accessing that troubleshooter and others.

 When you start that troubleshooting tool, you’ll have three options. Select the **I want to continue with this troubleshooter** option to initialize the automated video troubleshooting. The troubleshooter might automatically make some system changes or suggest you do something like installing a codec.

![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-video-playback-troubleshooter.jpg)

## 2\. Update Your PC’s Graphics Driver

 Updating graphics drivers is one of the most widely confirmed ways to fix the “Video driver crashed” error. Even the error message itself suggests users update their graphics cards’ drivers. So, it’s quite likely this potential resolution will address the error if your graphics card driver needs updating.

 Our [how to update graphics drivers](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) article covers the different methods for applying this potential resolution on a Windows PC. You could utilize driver updater software, but that won’t necessarily install the very latest driver available for your graphics card.

 Manually updating graphics drivers by downloading them from the NVIDIA, AMD, or Intel sites is a bit slower but will ensure you get the very latest driver package.

![The NVIDIA driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-nvidia-driver-download-options.jpg)

## 3\. Reinstall Your PC’s Graphics Driver

 If your PC’s current graphics driver is the latest one available, it won’t be outdated, but there could still be an issue with that driver. In this case, you might still need to reinstall the driver to resolve this error.

 These are the steps for reinstalling a graphics driver:

1. [Open Device Manager](https://www.makeuseof.com/windows-open-device-manager/), which is accessible on the Power User menu (press **Windows** key + **X** to open).
2. Click the small arrow beside the **Display adapters** category.
3. Right-click your PC’s GPU and select **Uninstall device**.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-device-option.jpg)
4. Select a checkbox option for deleting the driver and click **Uninstall**.  
![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option3.jpg)
5. Click on **Action > Scan for hardware changes** to reinstall the graphics driver.

 If the **Scan for hardware** changes option doesn’t reinstall the GPU’s driver, download the latest driver package for your graphics card from the [Intel](https://www.intel.com/content/www/us/en/download-center/home.html), [AMD](https://www.amd.com/en/support), or [NVIDIA](https://www.nvidia.com/download/index.aspx) websites. Double-click on the downloaded driver package file to open its setup window and select the installation option there.

## 4\. Lower Your Monitor’s Refresh Rate

 Some users have said on forums that lowering the frame rate can resolve the “Video driver crashed” error. So, that might be worth trying if your monitor has a higher maximum refresh rate. You can reduce the frame rate by lowering a monitor’s refresh rate as follows:

1. Open the file search tool (accessible with a **Windows** logo + **S** hotkey).
2. Input **advanced display settings**.
3. Select **View advanced display info** to open that part of Settings.
4. Then, select a lower setting in the **Refresh rate** drop-down menu.  
![The Refresh rate drop-down menu in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/advanced-display-settings.jpg)

 If you can access in-game settings, you might also be able to select a lower frame rate option from there. Look through an affected game’s graphical settings menu to see if it includes an FPS option for selecting lower or higher frame rates.

## 5\. Reduce an Affected Game’s Graphical Quality Settings

 The “Video driver crashed” error can sometimes occur when a game’s graphical settings are set too high. That’s more likely on lower-spec PCs with poorer GPUs that can’t handle higher graphics settings so well.

 A few players have said they fixed the “Video driver crashed” error by lowing in-game graphics options. So, that’s worth trying if you can reach in-game settings.

 There will probably be numerous in-game graphical options you can adjust. Lower the screen, texture, and shadow resolution settings that are included in many games. Then, select to apply the new graphical settings and restart the game.

![A game's Graphics Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/graphics-settings.jpg)

 Alternatively, you can try selecting a lower graphics preset option instead. Most games have three or more graphics presets that generally change graphical settings. Selecting a lower-quality preset will automatically reduce various graphics options.

 Some players have also reported this error occurring after enabling DirectX 12\. So, look for a DirectX setting in the graphics menu. If you can find it, make sure that option is set to DirectX 11\.

## 6\. Set a Higher TDR Delay Value

 TDR delay is the Timeout Detection and Recovery delay period. Setting a higher TDR delay value will give a graphics card more time to respond, which can resolve GPU errors such as the “Video driver crashed” error.

 You can set a higher TDR delay value by tweaking the registry like this:

1. Bring up the tool for finding files and input Registry Editor in its search box.
2. Select **Registry Editor** to view that app’s window.
3. Go to this **GraphicsDrivers** key by entering the following path inside the registry address bar:  
HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\GraphicsDrivers
4. If a **TDRDelay** DWORD already exists, you can skip to step six. If not, right-click **GraphicsDrivers** in Registry Editor’s left sidebar and select the **New** and **DWORD (32-bit) Value** options from the context menu.  
![The DWORD (32-bit) Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-dword-32-bit-value-option.jpg)
5. Input **TDRDelay** for the key’s title.
6. Double-click on the **TDRDelay** registry entry.
7. Delete the current number and enter **8** in the **Value data** box.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-edit-dword-window.jpg)
8. Select **OK** to finish.

 Restart the PC after applying this registry tweak. Then, try playing games or videos to see if this error still occurs.

## Enjoy Your Windows Games and Videos Again

 Those potential resolutions are among the most widely confirmed troubleshooting methods for fixing the “Video driver crashed” error. Many users have discussed how to fix the “Video driver crashed” error on forums and confirmed them to work.

 So, maybe one of them will fix the same issue on your PC, and then you can enjoy all your Windows games or videos again without further crashing.

 Although this issue is mainly reported for games, it can also crash high-resolution videos. It is a recurring error that can make games unplayable or videos unwatchable. This is how you can fix the “Video driver crashed” error on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-video-recordings.techidaily.com/ensuring-thumbnails-show-shorts-video-troubleshooting-for-2024/"><u>Ensuring Thumbnails Show  Shorts Video Troubleshooting for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-aural-adventures-tech-updates/"><u>[Updated] Aural Adventures  Tech Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-in-on-error-0x800f0831-for-windows-repair/"><u>Zeroing in on Error 0X800F0831 for Windows Repair</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-enrolling-in-the-apple-podcast-network/"><u>2024 Approved  Enrolling in the Apple Podcast Network</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-applications-with-wpm-in-windows-11/"><u>Efficiently Managing Applications with WPM in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-if-you-cant-access-your-router-page-or-web-interfaces-on-windows/"><u>What to Do if You Can't Access Your Router Page or Web Interfaces on Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-find-x7-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo Find X7 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-error-0x80070570-a-guide-for-fixed-damaged-files/"><u>Bypassing Error 0X80070570: A Guide for Fixed Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-organization-controlled-errors-in-windows-11-systems/"><u>Addressing Organization-Controlled Errors in Windows 11 Systems</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-audiovisual-mastery-on-a-budget-the-ultimate-list-of-free-audio-mixers-for-2024/"><u>Updated Audiovisual Mastery on a Budget The Ultimate List of Free Audio Mixers for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-magic-6-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor Magic 6? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inoperative-drive-not-detected-by-os/"><u>Fixing Inoperative Drive Not Detected by OS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-virtualbox-0x80004005-failure-on-windows-pcs/"><u>Addressing VirtualBox 0X80004005 Failure on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-new-default-for-reading-pdfs-on-pc/"><u>Defining New Default for Reading PDFs on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-errors-top-10-diagnostic-aids/"><u>Decoding Windows Errors: Top 10 Diagnostic Aids</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-view-facebook-videos-with-apple-remote-for-2024/"><u>[Updated] How to View Facebook Videos with Apple Remote for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-winoss-priority-setting-for-hardware-acceleration/"><u>Controlling WinOS's Priority Setting for Hardware Acceleration</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-nokia-130-music-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Nokia 130 Music Without Power Button | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-explore-the-worlds-top-10-no-cost-image-crafting-stations/"><u>In 2024, Explore the World's Top 10 No-Cost Image Crafting Stations</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/oculus-rift-vs-htc-vive-vs-playstation-vr-whats-the-best-for-gaming-in-2024/"><u>Oculus Rift vs HTC Vive vs PlayStation VR  What’s the Best for Gaming, In 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-chromes-non-downloading-problems-on-windows/"><u>Addressing Chrome's Non-Downloading Problems on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-apex-crashes-effective-solutions-for-windows-11-users/"><u>Combat Apex Crashes: Effective Solutions for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-taskbar-history-from-start-to-now/"><u>Windows Taskbar History: From Start to Now</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fb-videos-made-quick-proximity-tricks-for-instant-uploaddownload/"><u>[Updated] FB Videos Made Quick  Proximity Tricks for Instant Upload/Download</u></a></li>
<li><a href="https://windows11.techidaily.com/cure-for-hidden-second-display-on-w11/"><u>Cure for Hidden Second Display on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719346558796-why-your-pc-needs-only-one-guardian-antivirus-software/"><u>Why Your PC Needs Only One Guardian - Antivirus Software!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-y100-5g-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo Y100 5G Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-in-use-device-naming-5-fixes-for-windows-errors/"><u>Avoiding In-Use Device Naming: 5 Fixes for Windows Errors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chuckle-chipmunks-robotic-jokesters/"><u>[New] Chuckle Chipmunks  Robotic Jokesters</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-insight-into-magix-design-studio/"><u>2024 Approved  Insight Into MAGIX Design Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-clear-pin-lockouts-with-ease/"><u>Windows 11: Clear PIN Lockouts with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-to-flush-the-dns-cache-on-windows-11/"><u>4 Ways to Flush the DNS Cache on Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-discover-engaging-youtube-threads/"><u>[New] In 2024, Discover Engaging YouTube Threads</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-steam-library-folder-editability-in-win-11/"><u>Enabling Steam Library Folder Editability in Win 11</u></a></li>
</ul></div>
