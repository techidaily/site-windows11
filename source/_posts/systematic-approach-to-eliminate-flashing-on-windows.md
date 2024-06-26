---
title: Systematic Approach to Eliminate Flashing on Windows
date: 2024-06-25T11:57:03.577Z
updated: 2024-06-26T11:57:03.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Systematic Approach to Eliminate Flashing on Windows
excerpt: This Article Describes Systematic Approach to Eliminate Flashing on Windows
keywords: Flash Elimination Guide,Stop Flashy Windows,Windows Glitch Fix,Avoid Screen Flicker,Tackle Screen Shimmer,Eradicate Display Flashes,Remove Window Flashing Issues
thumbnail: https://thmb.techidaily.com/288c4a8a533b0f1094aca3a28c5db0188ea8b5a3c3aca95005c1c84fe62729c2.jpg
---

## Systematic Approach to Eliminate Flashing on Windows

 If your Windows 10 or Windows 11 screen is constantly flickering, it's likely because you have a troublesome application installed or an unsuitable display driver. It's time for you to resolve that annoying screen flash.

 The problem often begins when upgrading to Windows 10/11 from a previous version of the operating system, but it can occur at any time. We're going to show you various methods to fix a Windows 10 or Windows 11 flashing screen.

## Perform This Screen Flickering Test First

 First, you need to establish what might be causing the flickering screen. To do this,[open Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) by pressing**Ctrl + Shift + Esc** simultaneously.

 Alternatively, on Windows 10 you can**right-click** your taskbar and select**Task Manager** . You don't actually need to use Task Manager, but you do need it open.

![windows 11 desktop with task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-desktop-with-task-manager.jpg)

 Now, watch your screen to see if Task Manager flickers. If it does, along with everything else on the screen, the problem is likely caused by your hardware or a faulty display driver. On the other hand, if everything except Task Manager flickers, the issue is likely due to an application.

 If it's the former, follow the instructions below in order. If it's the latter, skip to step five. That said, if the advice there doesn't work, check the advice in the other sections too.

## 1\. Check Your Monitor and Cables

 If you have a flashing screen, the first thing to rule out is the hardware. Check all the cable connections from the monitor to the computer—take them out and plug them back in to ensure the cables are secure.

 If you have a spare monitor cable, try using it instead. Or buy a replacement online, since it's an inexpensive purchase. Cables can degrade over time, or maybe a pet has had a sneaky chew. Either way, switch the cable and see if it stops the screen flickering.

 If you can, try a different monitor. If this resolves the problem, you know it's your monitor that's the issue. At that point, contact the manufacturer for support or to raise a warranty claim.

## 2\. Set the Correct Refresh Rate

 A monitor's refresh rate is the speed at which the screen updates the image per second, measured in hertz (Hz). Basic monitors can usually only handle a 60Hz refresh rate, while more advanced ones—typically aimed at gamers—can go to 360Hz and beyond.

 It's important that you[set a suitable refresh rate for your monitor](https://www.makeuseof.com/tag/60hz-vs-144hz/) . Sometimes a monitor manufacturer will support an overclocked refresh rate, but this can cause screen flickering.

To adjust your refresh rate:

![windows 11 advanced display](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-advanced-display.jpg)

1. Press**Windows key + I** to open Settings.
2. Click**System** \>**Display** .
3. Click**Advanced display settings** (Windows 10) or**Advanced display** (Windows 11).
4. Use the**Refresh rate** dropdown and incrementally select lower rates until the screen flashing stops. If the flashing continues, revert to your monitor's recommended refresh rate.

## 3\. Reset Your Display Driver

 The screen flashing could be caused by your display driver. You might have an old driver or a faulty new one. Let's make sure you are running the right version for your system.

### Step 1: Remove the Driver

 First,[boot Windows in safe mode](https://www.makeuseof.com/windows-11-boot-safe-mode/ "How to Boot Into Windows 10 Safe Mode") :

![windows 11 recovery](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-recovery.jpg)

1. Press**Windows key + I** to open Settings.
2. Select**Update & Security >** **Recovery** (Windows 10) or**System > Recovery** (Windows 11).
3. Underneath**Advanced start-up** , click**Restart now** .
4. When your system restarts, select **Troubleshoot > Advanced options > Startup settings > Restart** .
5. Again, once restarted, select option five to launch your PC into**Safe Mode with Networking** .

Next, use Device Manager to uninstall the display driver:

![uninstall display device drivers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/uninstall-display-device-drivers.png)

1. Press**Windows key + X** and click**Device Manager** .
2. **Double-click** on**Display adapters** to expand the category.
3. **Right-click** your graphics card, click**Uninstall device** , check**Delete the driver software for this device** and then click**OK** .
4. Restart your system again.

 Alternatively, you can use third-party software[Display Driver Uninstaller](https://www.guru3d.com/files-details/display-driver-uninstaller-download.html) , which will completely wipe any traces of the driver from your system.

### Step 2: Install a New Driver

 You now want to[install the latest driver](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) for your system. Windows Update will provide the driver it thinks is compatible with your system. To do this:

1. Press**Windows Key + I** to open Settings.
2. Click**Update & Security** (Windows 10) or**Windows Update** (Windows 11).
3. Click**Check for updates** .

 Alternatively, you can go to your graphics card manufacturer's website (likely[AMD](https://www.amd.com/en/support) ,[NVIDIA](https://www.nvidia.com/Download/Find.aspx) , or[Intel](https://downloadcenter.intel.com/product/80939/Graphics) ) and manually download the driver from there.

 Download the driver, install it, and see if the screen flashing problem has ceased.

### Roll Back to an Older Driver

 If the problem continues, it might be that the newest driver hasn't patched the problem. If the screen flickering occurred after a driver update, try rolling back to an older version.

 Follow the steps above to uninstall the driver, then head to the old driver page for either[AMD](https://www.amd.com/en/support) ,[NVIDIA](https://www.nvidia.com/Download/Find.aspx) , or[Intel](https://downloadcenter.intel.com/product/80939/Graphics) . This might be a bit of trial and error, but try selecting one released when your screen wasn't flickering.

## 4\. Reseat Your Graphics Card

 If the problem isn't with your display driver, it doesn't mean your graphics card isn't to blame. If your graphics card isn't seated correctly in your motherboard, it can cause your monitor display to flicker on and off.

 You can easily check this if your motherboard has inbuilt graphics. Remove the monitor cable from your graphics card and plug it into the motherboard's display slot instead. If the flashing stops, you know the graphics card is the problem.

[Power off your PC](https://www.makeuseof.com/windows-11-how-to-shut-down/) , unplug everything, open the case, and remove your graphics card from the motherboard. Then carefully reseat it, ensuring the card firmly clips into the motherboard. Of course, don't do this if you're not comfortable working inside a computer because you might make things worse.

 If this doesn't fix it,[your graphics card might be faulty or dying](https://www.makeuseof.com/signs-graphics-card-is-dying/) . Contact the manufacturer for support or to claim on the warranty.

## 5\. Uninstall Problematic Applications

 Some apps are incompatible with Windows 10/11 and can cause screen flickering. Think about whether you installed any new software before the screen flashing began or if an app recently updated. In the past, three problematic apps have been Norton Antivirus, iCloud, and IDT Audio.

 Across all your applications, make sure you're running the latest versions. Either update within the app itself or head to the respective official websites and download the most up-to-date release. Alternatively, check the developer's support page for recently updated apps to see if screen flashing is known as a recent bug.

![windows 11 apps and features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-apps-and-features.jpg)

If this doesn't work, uninstall the program. To do so:

1. Press**Windows Key + I** to open Settings.
2. Click**Apps** \>**Apps & features** .
3. Click**Sort by** and choose**Installation date** .
4. Click the offending app and click**Uninstall** . You may need to restart your system for the changes to take full effect.

## 6\. Create a New Windows User Profile

 How do you stop your laptop or computer screen from flickering? Well, many Windows 10 and Windows 11 problems can often be solved by[creating a new user profile](https://www.makeuseof.com/windows-11-create-local-user-account/) . Screen flickering is one of them.

![windows 11 family and other users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/windows-11-family-and-other-users.jpg)

To create a new account:

1. Press**Windows Key + I** to open Settings.
2. Go to**Accounts > Family & other users** .
3. Click**Add someone else to this PC** (Windows 10) or**Add account** (Windows 11) and follow the wizard.

## Windows Screen Flickers... No More

 As with most Windows 10/11 issues, no single fix will work for everyone. Hopefully, one of the steps above has solved your Windows 10 or Windows 11 screen flashing problem.

 If it is time for a new monitor, there are plenty of productive and fun things you can do with the old one. Otherwise, take it off for recycling so it can rest in monitor heaven.


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
<li><a href="https://windows11.techidaily.com/configuring-windows-index-settings/"><u>Configuring Windows Index Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/the-premier-selection-of-cost-free-high-efficiency-driver-utilities/"><u>The Premier Selection of Cost-Free, High-Efficiency Driver Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-edges-continuous-desktop-appearance/"><u>Resolving Edges' Continuous Desktop Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-webp-images-top-4-viewer-tools-on-windows-os/"><u>Elevate WebP Images: Top 4 Viewer Tools on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/find-your-windows-11-backdrops-saving-spot/"><u>Find Your Windows 11 Backdrop's Saving Spot</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11s-functionality-top-strategies-for-widget-upgrades/"><u>Enhancing Windows 11'S Functionality: Top Strategies for Widget Upgrades</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-11-performance-tweak-ntfs-file-compression/"><u>Enhance Windows 11 Performance: Tweak NTFS File Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-profit-making-mechanisms-for-w11-at-microsoft/"><u>Unmasking Profit Making Mechanisms for W11 at Microsoft</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/multilocaudiolink-seamless-sound-alignment-for-multiple-projects-with-premiere-pro/"><u>MultilocAudioLink Seamless Sound Alignment for Multiple Projects with Premiere Pro</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-samsung-galaxy-m34-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Samsung Galaxy M34?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-create-vintage-film-effect-1920s/"><u>New In 2024, How to Create Vintage Film Effect 1920S</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-grasp-a-wider-audience-by-multistreaming-on-youtube-and-twitch-for-2024/"><u>How to Grasp a Wider Audience by Multistreaming on Youtube and Twitch for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-easy-video-editor-for-mac-mkvtoolnix-review-for-2024/"><u>New Easy Video Editor for Mac MKVtoolnix Review for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-infinite-jest-joyride-top-kids-game-lineup/"><u>[New] Infinite Jest Joyride - Top Kids' Game Lineup</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-capture-the-essence-your-free-screen-recording-solution-on-mac-and-pc/"><u>[New] 2024 Approved  Capture the Essence - Your FREE Screen Recording Solution on Mac & PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-key-strategies-in-livestreaming-major-sporting-contests/"><u>[Updated] Key Strategies in Livestreaming Major Sporting Contests</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-asus-rog-phone-7-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Asus ROG Phone 7 Location by Number | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-comprehensive-guide-to-ios-screenshotting/"><u>In 2024, Comprehensive Guide to iOS Screenshotting</u></a></li>
</ul></div>
