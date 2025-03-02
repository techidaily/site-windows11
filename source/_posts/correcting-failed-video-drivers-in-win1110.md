---
title: Correcting Failed Video Drivers in Win11/10
date: 2025-02-23T09:13:29.321Z
updated: 2025-03-01T22:33:49.882Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Video Drivers in Win11/10
excerpt: This Article Describes Correcting Failed Video Drivers in Win11/10
keywords: Fix Video Driver Win11,Win10 Video Driver Troubleshoot,Resolve Video Issues Win10,Correcting Win11 Video Errors,Update Failed Video Drivers Windows,Fix Windows 10 Video Glitches,Diagnose Win10/Win11 Video Problems
thumbnail: https://thmb.techidaily.com/738b7371069538e959521966db00e5f006e9b11d983f215b33d6c4263c894748.png
---

## Correcting Failed Video Drivers in Win11/10

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
<li><a href="https://fox-direct.techidaily.com/new-bring-your-video-to-life-from-standard-to-hdri-excellence-for-2024/"><u>[New] Bring Your Video to Life From Standard to HDRI Excellence for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-elevate-your-igtv-presence-strategies-for-perfecting-video-lengths-and-widths/"><u>[New] In 2024, Elevate Your IGTV Presence Strategies for Perfecting Video Lengths and Widths</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-premium-top-11-list-audio-recording-essentials-for-2024/"><u>[New] Premium Top 11 List - Audio Recording Essentials for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-quake-mode-in-windows-terminal/"><u>How to Enable Quake Mode in Windows Terminal</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-infinix-note-30-vip-racing-edition-with-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Infinix Note 30 VIP Racing Edition with Video Repair Utility on Windows?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-tecno-spark-10c-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-file-history-setting-glitch-in-windows-os/"><u>Mending File History Setting Glitch in Windows OS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/no-cost-media-transformer-convert-audio-from-mp3aac-and-use-opus-format-moveave/"><u>No Cost Media Transformer: Convert Audio From Mp3/Aac and Use Opus Format - Moveave</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-itel-a05s-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Itel A05s? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-diagnosis-navigating-through-windows-error-messages-with-command-line-skills/"><u>Precision in Diagnosis: Navigating Through Windows Error Messages with Command Line Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-lost-5ghz-lan-link-in-windows-11-heres-how/"><u>Reclaim Your Lost 5GHz LAN Link in Windows 11 Here's How</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-power-a-windows-guide-to-net-repair-max-156/"><u>Regaining Power: A Windows Guide to .NET Repair (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-and-restore-key-applications-for-changing-createdmodified-dates/"><u>Rewind and Restore: Key Applications for Changing Created/Modified Dates</u></a></li>
<li><a href="https://win-blog.techidaily.com/rocket-league-not-working-heres-what-you-can-do-next/"><u>Rocket League Not Working? Here's What You Can Do Next</u></a></li>
<li><a href="https://win-howtos.techidaily.com/simple-fixes-for-the-anti-cheating-bug-in-apex-legends/"><u>Simple Fixes for the Anti-Cheating Bug in Apex Legends</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-guide-for-converting-bat-files-into-exes/"><u>Simplified Guide for Converting .bat Files Into EXEs</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-made-window-ordering-powertoy-guide-to-win-os-snaps/"><u>Tailor-Made Window Ordering: PowerToy Guide to Win OS Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-shortcut-compendium-windows-narrators-command-guide/"><u>The Ultimate Shortcut Compendium: Windows Narrator's Command Guide</u></a></li>
</ul></div>

