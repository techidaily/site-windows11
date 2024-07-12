---
title: How to Disable Update Notifications on Windows
date: 2024-07-11T21:28:46.734Z
updated: 2024-07-12T21:28:46.734Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Update Notifications on Windows
excerpt: This Article Describes How to Disable Update Notifications on Windows
keywords: Turn Off Windows Updates,Stop Update Alerts WIN,Halt WIN Update Notifies,Stop Update WIN Push,Disable Windows Update Tips,End WIN Update Messages,Quieten Windows Update Alarms
thumbnail: https://thmb.techidaily.com/9333e7c75e292a0b83b1e16b6df5d6742dede6cee3e1ad9fc6da9c95dfc95571.jpg
---

## How to Disable Update Notifications on Windows

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-methods-for-time-loop-illusions/"><u>[Updated] Innovative Methods for Time Loop Illusions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-is-it-time-to-upgrade-to-an-itop-equipped-system/"><u>[New] In 2024, Is It Time to Upgrade to an ITop-Equipped System?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win-11-issue-resolution/"><u>Mastering the Art of WIN 11 Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/howto-unpacking-and-implementing-windows-compressed-archive-cab-files/"><u>Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-analysis-of-srt-unpacking-its-significance/"><u>In 2024, Expert Analysis of SRT  Unpacking Its Significance</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-discover-novel-webcam-functions-today/"><u>[New] 2024 Approved  Discover Novel Webcam Functions Today</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-in-discord-for-windows-os/"><u>Fix 'Installation Failed' In Discord for Windows OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-xiaomi-13-ultra-frp-bypass-by-drfone-android/"><u>About Xiaomi 13 Ultra FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-visuals-perfect-windows-desktop-backdrops/"><u>Elevating Visuals: Perfect Windows Desktop Backdrops</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mirth-makers-zombie-shadowbenders/"><u>In 2024, Mirth Makers  Zombie Shadowbenders</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-ultimate-checklist-for-installing-vrecorder-for-2024/"><u>[New] Ultimate Checklist for Installing VRecorder for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-network-how-to-conceal-on-windows-pc/"><u>Elusive Network: How to Conceal on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sync-errors-in-nvidia-cp-windows-11/"><u>Fixing Sync Errors in NVidia CP Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-precision-audio-leveling-in-three-simple-steps/"><u>New Precision Audio Leveling in Three Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-multi-monitor-setup-selecting-the-best-control-tools/"><u>Illuminating Windows Multi-Monitor Setup: Selecting the Best Control Tools</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-m4r-conversion-fundamentals-what-every-newbie-should-know-for-2024/"><u>Updated M4R Conversion Fundamentals What Every Newbie Should Know for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-package-unopenable-woes/"><u>Navigating Through Windows Package Unopenable Woes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-snapshot-review-vidmas-innovation-on-screen-capturing/"><u>[New] Snapshot Review  Vidma's Innovation on Screen Capturing</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/master-wins-control-in-windows-11-easy-steps/"><u>Master Wins Control in Windows 11: Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-dns-management-in-windows-11/"><u>Masterful DNS Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-event-viewer-glitches-in-win-11/"><u>Methods to Correct Event Viewer Glitches in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-win11-screen-saver-settings/"><u>Personalizing Win11 Screen Saver Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-restarting-windows-update-process/"><u>Essential Tips for Restarting Windows Update Process</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-exploring-the-best-tools-for-mens-voices-adopting-a-female-characteristic/"><u>Updated 2024 Approved Exploring the Best Tools for Mens Voices Adopting a Female Characteristic</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
</ul></div>
