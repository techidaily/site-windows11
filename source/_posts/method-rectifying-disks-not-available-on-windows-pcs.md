---
title: "Method: Rectifying Disks Not Available on Windows PCs"
date: 2024-06-25T12:26:52.652Z
updated: 2024-06-26T12:26:52.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
excerpt: "This Article Describes Method: Rectifying Disks Not Available on Windows PCs"
keywords: Windows Disk Error Fix,Windows No Disk Found,Unavailable Disk in Windows,Solve Missing Disks Issue,Windows PC Disk Repair,Rectify Windows Disk Not Available,Troubleshoot Disk Non-Existence on PC
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Method: Rectifying Disks Not Available on Windows PCs

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/top-8-windows-11-no-nos-common-pitfalls-to-skip/"><u>Top 8 Windows 11 No-Nos: Common Pitfalls to Skip</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-domain-user-biometric-control-in-windows-11/"><u>Mastering Domain User Biometric Control in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-screen-driver-problems-in-windows-11/"><u>How to Mend Screen Driver Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-visual-journey-top-7-windows-10-drawing-tools-unveiled/"><u>A Visual Journey: Top 7 Windows 10 Drawing Tools Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-ping-wisdom-utilizing-tools-for-maximum-efficiency/"><u>Windows Ping Wisdom: Utilizing Tools for Maximum Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-spotify-link-reset-strategies/"><u>Mastering Windows Spotify Link Reset Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-eliminate-startup-disruption-due-to-winscombsvc-errors/"><u>Quick Fix: Eliminate Startup Disruption Due to WinScombSvc Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/faster-apps-better-internet-fixes-for-windows-devices/"><u>Faster Apps, Better Internet: Fixes for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-icon-positioning-in-windows/"><u>Mastering Icon Positioning in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-optimal-performance-self-updating-updated-amd-driver/"><u>Achieve Optimal Performance: Self-Updating, Updated AMD Driver</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-pictures-after-note-30-vip-has-been-deleted-by-fonelab-android-recover-pictures/"><u>Recover your pictures after Note 30 VIP has been deleted.</u></a></li>
<li><a href="https://audio-editing.techidaily.com/compilation-of-the-best-8-rain-styled-sounds-for-digital-acquisition-updated-for-2024/"><u>Compilation of the Best 8 Rain Styled Sounds for Digital Acquisition - Updated for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h265-hevc-video-on-motorola-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Motorola</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-nubia-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Nubia Face Lock?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-building-unique-instagram-profile-thumbnails/"><u>In 2024, Building Unique Instagram Profile Thumbnails</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-explore-unrestricted-stock-content-in-key-4-video-channels/"><u>[New] 2024 Approved  Explore Unrestricted Stock Content in Key 4 Video Channels</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-samsung-galaxy-f15-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Samsung Galaxy F15 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-chuckle-crafting-tool/"><u>[Updated] Chuckle Crafting Tool</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-complete-youtube-editors-toolkit-for-post-publish-adjustments/"><u>[New] The Complete YouTube Editor's Toolkit for Post-Publish Adjustments</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>