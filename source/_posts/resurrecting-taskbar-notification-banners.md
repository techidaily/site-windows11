---
title: Resurrecting Taskbar Notification Banners
date: 2024-07-11T21:39:33.425Z
updated: 2024-07-12T21:39:33.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resurrecting Taskbar Notification Banners
excerpt: This Article Describes Resurrecting Taskbar Notification Banners
keywords: Revive Taskbar Alerts,Notification Bar Revival,Taskbar Icon Update,Restore Windows Tip,NotifyBar Relaunch,Icon Banner Resurrect,System Tips Reactivation
thumbnail: https://thmb.techidaily.com/56db2abce12454619eb56aa29719b3ba982081a7573c4ec93a0c358d91bb966c.jpg
---

## Resurrecting Taskbar Notification Banners

 Typically, apps that are pinned to the taskbar or running on your computer display notification badges on their icons to provide a visual cue for new or unread notifications. Occasionally, however, you might find that Windows won't show notification badges for some or all the taskbar icons on your computer.

 If you are troubled by this issue, don't fret. We have some quick and easy fixes that will get Windows to display notification badges once again.

## 1\. Modify the Taskbar Behavior

 To start, you need to ensure that the taskbar is configured to show notification badges on your computer. Here are the steps for doing the same.

1. Right-click on the**Start icon** and select**Settings** from the list.
2. Select**Personalization** from the left sidebar.
3. Click on**Taskbar** .
4. Click on**Taskbar behaviors** to expand it.
5. Tick the checkbox that reads**Show badges on taskbar apps** .  
![Enable Badges on Taskbar Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-badges-on-taskbar-apps-on-windows.jpg)

 Following this, apps should display notification badges on the taskbar.

## 2\. Make Sure App Notifications Are Enabled

 Another reason why badges may not appear on taskbar apps is if you have turned off notifications on Windows. If you are unsure, use these steps to check if notifications are enabled on your computer.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. In the**System** tab, click on**Notifications** .
3. Enable the toggle next to**Notifications** , if it isn’t already.
4. Scroll down to the**Notifications from apps and other senders** section and ensure that your favorite apps are allowed to display notifications on Windows.  
![Enable Notifications for Apps on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-notifications-for-apps-on-windows.jpg)

## 3\. Allow Apps to Run in the Background

 If your apps do not have the necessary permission to run in the background, they will fail to fetch new data and display any notifications. This may lead you to believe that notification badges are not working for the taskbar apps. To avoid this, you should ensure that your apps are allowed to run in the background on Windows by following the steps below.

1. Right-click on the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Installed apps** from the list.
3. Scroll through the list or use the search bar at the top to locate the problematic app.
4. Click the**three-dot menu icon** next to the app and select**Advanced options** .
5. Use the drop-down menu under**Background apps permissions** to select**Always** .  
![Allow Xbox to Run in the Background on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/allow-xbox-to-run-in-the-background-on-windows.jpg)

 Unable to find the background app permissions option in the Settings app? Check our guide on [how to restore a missing background apps permission option in Windows](https://www.makeuseof.com/windows-11-restore-background-apps-permissions/) .

## 4\. Restart the Windows Explorer Process

 Temporary issues with the taskbar can also prevent apps from displaying notification badges on Windows. This usually happens when the Windows Explorer process, which is responsible for providing the Graphical User Interface (GUI) for the taskbar, experiences problems.

 If it’s just a minor glitch, restarting the Windows Explorer process should help fix it. If you need help with the same, check our guide on [different ways to restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) and follow the steps outlined there.

 Note that your taskbar will disappear for a brief moment when you restart the Windows Explorer process. After that, check if notification badges appear on the taskbar apps.

## 5\. Unpin the Apps From the Taskbar and Pin Them Again

 If Windows is failing to display notification badges for only one or two apps, you can try to unpin the affected apps from the taskbar and pin them back again. To do so, use these steps:

1. Right-click on the problematic app icon and select**Unpin from taskbar** .
2. Press**Win + S** to open the search menu.
3. Type the name of the app in the search box.
4. Select**Pin to taskbar** from the right pane.  
![Unpin App From Windows Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/unpin-app-from-windows-taskbar.jpg)

 Repeat the above steps for all the apps that are not displaying badges on the taskbar.

## 6\. Repair the Problematic App

 If the issue remains even after you unpin and re-pin the app, you can try repairing it. This process will allow Windows to identify and resolve any issues with the app without affecting any of the app data. For more information on this, check our guide on [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 7\. Enable Taskbar Badges Using the Registry Editor

 Windows may not show notification badges on taskbar apps if the feature has been disabled via the Registry Editor. In that case, you will need to modify the**TaskbarBadges** DWORD using the Registry Editor to bring back notification badges on Windows.

 As you may already know, editing registry files in Windows involves risk. Hence, it’s important to be cautious while using the Registry Editor. If you’re unfamiliar with it, we recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 Also, it’s a good idea to [back up all the Registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. Once you've done that, use these steps to enable taskbar badges on Windows via the Registry Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > Advanced** .
5. In the right pane, locate the**TaskbarBadges** entry. If you can’t find it, right-click on the**Advanced** key, and select**New > DWORD (32-bit) Value** . Rename the DWORD to**TaskbarBadges** .
6. Double-click on the**TaskbarBadges** DWORD to edit it.
7. In the**Value data** field, enter**1** .
8. Click**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-dword-in-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. After that, notification badges should appear on taskbar apps.

## Stay on Top of App Alerts With Notification Badges

 Taskbar notification badges are useful as they inform you about apps and programs awaiting your attention. Hopefully, one of the above fixes has helped you resolve the underlying issue and Windows is now showing notification badges for taskbar apps.

 Finding it hard to notice the taskbar notification badges because of their small size? You can always enlarge the Windows taskbar to make the notification badges more visible.


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
<li><a href="https://windows11.techidaily.com/a-new-look-for-you-top-methods-to-alter-windows-11-themes/"><u>A New Look for You: Top Methods to Alter Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/best-data-shields-on-windows-encryption-apps-analysis-150-chars/"><u>Best Data Shields on Windows: Encryption Apps Analysis (150 Chars)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-special-features-virtual-location-on-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Motorola Moto G13? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/apple-music-for-dynamic-video-enhancement/"><u>Apple Music for Dynamic Video Enhancement</u></a></li>
<li><a href="https://windows11.techidaily.com/1719361633854-enhance-your-pcs-screen-glow-with-these-fixes/"><u>Enhance Your PC's Screen Glow with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-changing-printer-behavior-on-windows/"><u>Avoiding Changing Printer Behavior on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-start-page-in-windows-11-task-manager/"><u>Altering Start Page in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-practices-choosing-the-right-win-video-codec/"><u>Best Practices: Choosing the Right Win Video Codec</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-excellent-ai-bots-for-social-spheres/"><u>[Updated] In 2024, Excellent AI Bots for Social Spheres</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-photopea-guide-to-clean-image-canvases/"><u>2024 Approved  Photopea Guide to Clean Image Canvases</u></a></li>
<li><a href="https://windows11.techidaily.com/access-androids-gaming-joy-on-pc-from-phone-to-window-11-via-google-linkup/"><u>Access Android's Gaming Joy on PC: From Phone to Window 11 via Google Linkup</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-golden-nuggets-revealing-the-hottest-reddit-topics-10/"><u>2024 Approved  Golden Nuggets  Revealing the Hottest Reddit Topics (10)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-cant-see-cursor-only-sony-a6400-glitch-for-2024/"><u>[New] Can't See, Cursor Only - Sony A6400 Glitch for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-blurry-screen-issues-on-windows-11/"><u>9 Ways to Fix Blurry Screen Issues on Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-unleashing-your-gaming-potential-with-win10-recordings/"><u>2024 Approved  Unleashing Your Gaming Potential with Win10 Recordings</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-foremost-innovative-logos-for-social-platforms-animations/"><u>[New] Foremost Innovative Logos for Social Platforms' Animations</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-30-psd-text-files-unrestricted-zero-price/"><u>[New] Top 30 PSD Text Files  Unrestricted, Zero Price</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-essential-gif-creation-best-tools-reviewed-and-compared/"><u>2024 Approved  Essential GIF Creation  Best Tools Reviewed & Compared</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/a-harmonious-symphony-taming-your-computers-audio-irqs/"><u>A Harmonious Symphony: Taming Your Computer’s Audio IRQs</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/overcoming-airborne-vibration-phenomenon-for-2024/"><u>Overcoming Airborne Vibration Phenomenon for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-mastering-audio-editing-a-step-by-step-approach-for-isolating-vocals-with-audacity/"><u>Updated In 2024, Mastering Audio Editing A Step-by-Step Approach for Isolating Vocals with Audacity</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-rpc-calls-top-tips-for-windows-users/"><u>Addressing Failed RPC Calls: Top Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-forbidden-page-in-windows-setup/"><u>Addressing Forbidden Page in Windows Setup</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-ultimate-fcpx-skin-smoother-a-comprehensive-guide/"><u>The Ultimate FCPX Skin Smoother A Comprehensive Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-breaking-down-augmented-realitys-mysteries/"><u>[New] Breaking Down Augmented Reality's Mysteries</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-navigating-recording-options-virtual-office-meetings-desktop/"><u>[Updated] 2024 Approved  Navigating Recording Options  Virtual Office Meetings (Desktop)</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-10-upgrade-fault-code-0xc004f050/"><u>Bypassing Windows 10 Upgrade Fault: Code 0XC004F050</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-customizable-rgb-in-windows-11-os/"><u>Activating Customizable RGB in Windows 11 OS</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-soundcloud-to-mp3-conversion-made-easy-top-tips-and-tricks/"><u>2024 Approved Soundcloud to MP3 Conversion Made Easy Top Tips and Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/briefly-explain-what-cultural-relativism-means-in-your-own-words/"><u>Briefly Explain What Cultural Relativism Means in Your Own Words.</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-enhance-video-visibility-using-creator-studio-wisdom/"><u>[New] Enhance Video Visibility Using Creator Studio Wisdom</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-mastering-video-editing-a-guide-for-sony-camcorder-footage/"><u>New Mastering Video Editing A Guide for Sony Camcorder Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/breathe-life-into-dead-wi-fi-connections-on-windows-10-with-this-list/"><u>Breathe Life Into Dead Wi-Fi Connections on Windows 10 with This List</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-comprehensive-guide-advanced-avs-sound-editing-tools-and-comparative-analysis/"><u>Updated 2024 Approved Comprehensive Guide Advanced AVS Sound Editing Tools and Comparative Analysis</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-motorola-edge-40-neo-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Motorola Edge 40 Neo Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/antiquated-tech-awakened-atlasos-upgrade/"><u>Antiquated Tech Awakened: AtlasOS Upgrade</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-screencapture-pro-laptop-tips-and-tricks/"><u>2024 Approved  ScreenCapture Pro  Laptop Tips & Tricks</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-maximize-video-clarity-with-obs-tweaks-for-2024/"><u>[Updated] Maximize Video Clarity with OBS Tweaks for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/amplify-your-pcs-wi-fi-with-8-effective-fixes-for-windows-11/"><u>Amplify Your PC's Wi-Fi with 8 Effective Fixes for Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-capture-win10-ranking-the-best-video-grabbers-for-2024/"><u>[New] Capture Win10  Ranking the Best Video Grabbers for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-essential-guide-to-asmr-for-sleep-enthusiasts/"><u>2024 Approved  The Essential Guide to ASMR for Sleep Enthusiasts</u></a></li>
</ul></div>
