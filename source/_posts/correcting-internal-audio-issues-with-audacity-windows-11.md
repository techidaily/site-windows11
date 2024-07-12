---
title: Correcting Internal Audio Issues with Audacity (Windows 11)
date: 2024-07-11T22:26:49.938Z
updated: 2024-07-12T22:26:49.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Internal Audio Issues with Audacity (Windows 11)
excerpt: This Article Describes Correcting Internal Audio Issues with Audacity (Windows 11)
keywords: Fix Audio Windows 11,Audacity Noise Reduction,Clear Windows Sound Issue,Edit Windows Audio,Correct Audio Problems,Remove Background Noise PC,Enhance Windows Sound Quality
thumbnail: https://thmb.techidaily.com/7dd47039b908f15adfac56204ff22ad7becb8a002a35f04201c966ce7066b460.jpg
---

## Correcting Internal Audio Issues with Audacity (Windows 11)

 Audacity is great music editing and recording software when it works. However, some users can’t utilize Audacity because of an Internal PortAudio error that occurs when they launch the software. Instead of launching, Audacity throws up this message: “Could not find any audio devices… Internal PortAudio error.”

 Although the Audacity window opens, users can’t play or record anything with that software when the Internal PortAudio error occurs. Does the same thing happen when you run Audacity? If it does, this is how you can fix the Internal PortAudio error in Windows 11 and 10.

## 1\. Run the Playing Audio Troubleshooter

 Windows has a "Playing Audio" troubleshooter to help users resolve audio playback issues. As the Internal PortAudio error breaks sound playback in Audacity, that troubleshooter could be useful for fixing this issue. You can access the Playing Audio troubleshooter in Windows 10 and 11 via the Control Panel like this:

1. Click a search box or magnifying glass icon on the Windows 11/10 taskbar.
2. Then type in**Control Panel** within the search utility.
3. Select**Control Panel** to open that app’s window.
4. If Control Panel opens in its category view, click**Large icons** on the**View by** menu.
5. Select**Troubleshooting** to access that applet.  
![The Control Panel applets window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-control-panel-items.jpg)

1. Next, select the**View all** navigation link on the left of the Control Panel window.  
![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-applet.jpg)
2. Click Playing Audio to launch that troubleshooter.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-troubleshooting-list.jpg)
3. Select the troubleshooter’s**Next** option to continue.
4. Then select one of the sound output device options to troubleshoot and click**Next** .
5. Apply the resolutions suggested within the Playing Audio troubleshooter.

## 2\. Enable the Windows Audio and Endpoint Builder Services

 Many Audacity users have confirmed enabling and running disabled Windows Audio and Endpoint Builder services can fix the Internal PortAudio error. So, this troubleshooting method will likely work if one of those services is disabled on your PC. This is how you can check and enable those services in Windows 11/10:

1. First, bring up the Windows search box and search for Services. You can also use one of the other [ways to open Services on Windows](https://www.makeuseof.com/windows-11-open-services-app/) .
2. Next, double-click**Windows Audio** to bring up further options for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service.jpg)
3. If the service is disabled, select an**Automatic** startup option on the drop-down menu.  
![The Automatic service option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/automatic-service.jpg)
4. Then select the properties window’s**Start** option to run the service.
5. Click**Apply** and**OK** to save the options and exit the Audio Properties window.
6. Repeat steps four to eight for the Windows Audio Endpoint Builder service.

 If you find the above services to be enabled and running, restarting them could also feasibly fix the issue. To do that, click Stop in their properties windows and select**Yes** to confirm. Then click their**Start** options to restart them.

## 3\. Manually Enable all Playback and Recording Devices

 It could be the case that a disabled audio playback or recording device is causing the PortAudio error to arise. For that reason, it’s recommended to enable all disabled playback and recording devices you can find in the Sound window. You can do that with the following steps:

1. To access the Run dialog, press**Win + R** .
2. Type**mmsys.cpl** in Run’s command box.
3. Click**OK** to bring up the Sound window.
4. Then click the**Playback** tab if necessary.
5. Right-click any disabled playback device and select**Enable** . Repeat this step for all disabled devices listed.  
![The Enable option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-option.jpg)
6. Then select the**Recording** tab to view more devices.  
![The Recording tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/recording-tab.jpg)
7. Click disabled recording devices with the mouse’s right button to select their**Enable** options. Enable all disabled devices listed there.
8. Select the Sound window’s**Apply** option to save settings.
9. Click**OK** on the Sound window to exit, and then restart your Windows 11/10 desktop or laptop.

## 4\. Select the Rescan Audio Devices

 If you’ve made some recent audio device changes on your PC, Audacity might not have detected them. Selecting Audacity’s**Rescan Audio Device** option can feasibly resolve the PortAudio error in such a scenario. This is how you can select that option:

1. Open the Audacity window.
2. Click**Transport** on Audacity’s menu bar.
3. Select the**Rescan Audio Devices** option.  
![The Rescan Audio Devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/rescan-audio-devices-option.jpg)
4. Wait for the rescan to finish, and then restart**Audacity** .

## 5\. Reinstall Audio Device Drivers

 The Internal PortAudio can also occur because of a sound device driver issue. In this case, reinstalling the drivers for all audio devices can fix this issue for some users. Trying reinstalling your PC’s audio device drivers as follows:

1. To open the Power User menu, right-click the Windows 11/10**Start** button.
2. Select**Device Manager** to bring up the window for that tool.
3. Click the arrow beside the**Audio inputs and outputs** category.  
![The Audio inputs and outputs category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/audio-inputs-and-outputs.jpg)
4. Right-click your speaker’s audio device and select**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device.jpg)
5. Select**Uninstall** on the small window that opens.  
![The Uninstall button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-button.jpg)
6. Repeat the last two steps for all sound devices in the**Audio inputs and outputs** category.
7. If you utilize any sound devices with USB ports, double-click the**Universal Serial Bus** category and select to uninstall all host controllers listed there. Users who don’t have sound devices connected via USB can skip this step.
8. Restart your PC for automatic driver reinstallation. If some drivers aren’t reinstalled after the restart, select the**Action** \>**Scan for hardware** changes options in Device Manager.

## 6\. Update the Realtek Audio Codec Driver

 Does your PC have a Realtek audio codec driver? If so, it’s recommended to update that driver for the sake of fixing the Internal PortAudio error. Update that Realtek driver as follows:

1. [Open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/) to access that uninstaller tool.
2. Select Realtek High Definition Audio Driver or Realtek HD Manager.
3. Click**Uninstall** to remove the driver.  
![The Programs and Features applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/programs-and-features.jpg)
4. Then bring up the [Realtek audio driver](https://www.realtek.com/en/component/zoo/category/pc-audio-codecs-high-definition-audio-codecs-software) page.
5. Click the**Download** button for the latest compatible Realtek driver for your PC.
6. Open the folder containing the downloaded Realtek driver package.
7. Double-click the Realtek package to install the latest driver.

## 7\. Reinstall Audacity

 A corrupted Audacity installation is another potential reason for the Internal PortAudio error occurring. Reinstalling the sound editor will likely resolve Audacity installation issues. You can remove Audacity with one of the methods included in our [ways to uninstall Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) post.

 To reinstall the software, open the [Audacity](https://www.audacityteam.org/download/) download page. Click the**Download for Windows** link there to save the setup wizard. Then navigate to the directory your browser downloads to and double-click the**audacity-win-.3.2.5 x64.exe** file to reinstall Audacity.

![The download Audacity option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/download-audacity-options.jpg)

 Some users have said that reinstalling older, not newer, versions of Audacity resolved the Internal PortAudio error on their PCs. Although it’s recommended to install the latest version first, reinstalling an older version is another troubleshooting option worth considering. This [uptodown archives page](https://audacity.en.uptodown.com/windows/versions) includes a good library of older Audacity versions for download.

## Get the Internal PortAudio Error Sorted on Audacity for Windows

 Although there are plenty of audio editor alternatives to Audacity, few others match its sound recording and editing features. However, you probably won’t need to switch to an alternative music editor because of the Internal PortAudio error after applying the potential fixes above. They’re widely cited solutions that have resolved the PortAudio error for many Audacity users.

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
<li><a href="https://facebook-video-files.techidaily.com/updated-the-complete-guide-to-facebook-dominance-business-edition-for-2024/"><u>[Updated] The Complete Guide to Facebook Dominance  Business Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-cannot-calculate-issues-on-windows-platform/"><u>Correcting 'Cannot Calculate' Issues on Windows Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-unlocking-mac-locations-in-windows-11/"><u>Cracking the Code: Unlocking MAC Locations in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-key-to-stellar-zoom-calls-smart-use-of-filters-for-2024/"><u>[Updated] The Key to Stellar Zoom Calls  Smart Use of Filters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/converting-the-modern-windows-11-search-to-an-icon-style/"><u>Converting the Modern Windows 11 Search to an Icon Style</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shift-unveiling-the-latest-os-features/"><u>Desktop Dynamics Shift: Unveiling the Latest OS Features</u></a></li>
<li><a href="https://windows11.techidaily.com/comparing-windows-terminal-with-powershells-different-utilities/"><u>Comparing Windows Terminal with PowerShell's Different Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-loss-of-hard-drive-visibility/"><u>Correcting Loss of Hard Drive Visibility</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-if-you-are-into-gifs-and-want-to-know-a-great-extent-of-information-about-it-then-we-have-got-you-covered-in-this-article-here-is-what-we-have-learn/"><u>In 2024, If You Are Into GIFs and Want to Know a Great Extent of Information About It Then We Have Got You Covered in This Article. Here Is What We Have Learned so Far About It</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-unleash-your-creativity-10-top-rated-android-video-editors-for-2024/"><u>Updated Unleash Your Creativity 10 Top-Rated Android Video Editors for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-and-resolving-0x80072af9-hitches/"><u>Dissecting and Resolving 0X80072AF9 Hitches</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-windows-11s-directive-non-empty-problem-0x80070091/"><u>Clearing Up Windows 11'S Directive Non-Empty Problem #0X80070091</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-revolutionize-your-workflow-with-these-top-10-mac-capture-tools/"><u>[Updated] 2024 Approved  Revolutionize Your Workflow with These Top 10 Mac Capture Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/5-solutions-for-honor-play-40c-unlock-without-password-by-drfone-android/"><u>5 Solutions For Honor Play 40C Unlock Without Password</u></a></li>
<li><a href="https://extra-tips.techidaily.com/gopro-hero-10-secrets-for-flawless-long-exposure-films/"><u>GoPro Hero 10 Secrets for Flawless Long-Exposure Films</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-fixing-windows-pin-failures/"><u>Cracking the Code: Fixing Windows PIN Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-redefined-windows-photo-apps-new-edge/"><u>Deletion Redefined: Windows Photo App's New Edge</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-common-errors-in-windows-11-zoom-app/"><u>Disentangling Common Errors in Windows 11 Zoom App</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-fixing-windows-error-0x800704b3-on-pcslaptops/"><u>Decoding & Fixing Windows Error 0X800704B3 on PCs/Laptops</u></a></li>
<li><a href="https://windows11.techidaily.com/crucial-factors-to-evaluate-before-buying-a-windows-laptop/"><u>Crucial Factors to Evaluate Before Buying a WIndows Laptop</u></a></li>
<li><a href="https://windows11.techidaily.com/context-menu-augmentation-with-disk-space-visualization-tools/"><u>Context Menu Augmentation with Disk Space Visualization Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-runtime-broker-its-essential-role-in-operating-systems/"><u>Decoding Runtime Broker: Its Essential Role in Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/compreranble-windows-11-sticky-features-across-devices/"><u>Compreranble Windows 11 Sticky Features Across Devices</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-xs-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone XS Max without iTunes? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/crossing-the-troubled-seas-of-windows-11-with-xbox-errors/"><u>Crossing the Troubled Seas of Windows 11 with Xbox Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/compatible-drawing-tools-for-windows-not-procreate/"><u>Compatible Drawing Tools for Windows, Not Procreate</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-lava-yuva-2-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Lava Yuva 2 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-permissions-shortfall-on-windows-1011-during-setup/"><u>Correcting Permissions Shortfall on Windows 10/11 During Setup</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-honor-magic-5-lite-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Honor Magic 5 Lite FRP Bypass With Best Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-obstructions-uninstalling-programs-on-win-11/"><u>Clearing Obstructions: Uninstalling Programs on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-dormant-window-control/"><u>Diagnosing and Repairing Dormant Window Control</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-xiaomi-14-ultra-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Xiaomi 14 Ultra FRP</u></a></li>
<li><a href="https://windows11.techidaily.com/display-number-and-caps-lock-status-in-taskbar-tray-win11/"><u>Display Number and Caps Lock Status in Taskbar Tray Win11</u></a></li>
</ul></div>
