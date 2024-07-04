---
title: Resurrecting Taskbar Notification Banners
date: 2024-06-25T12:19:39.199Z
updated: 2024-06-26T12:19:39.199Z
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

 Unable to find the background app permissions option in the Settings app? Check our guide on[how to restore a missing background apps permission option in Windows](https://www.makeuseof.com/windows-11-restore-background-apps-permissions/) .

## 4\. Restart the Windows Explorer Process

 Temporary issues with the taskbar can also prevent apps from displaying notification badges on Windows. This usually happens when the Windows Explorer process, which is responsible for providing the Graphical User Interface (GUI) for the taskbar, experiences problems.

 If it’s just a minor glitch, restarting the Windows Explorer process should help fix it. If you need help with the same, check our guide on[different ways to restart Windows Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) and follow the steps outlined there.

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

 If the issue remains even after you unpin and re-pin the app, you can try repairing it. This process will allow Windows to identify and resolve any issues with the app without affecting any of the app data. For more information on this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 7\. Enable Taskbar Badges Using the Registry Editor

 Windows may not show notification badges on taskbar apps if the feature has been disabled via the Registry Editor. In that case, you will need to modify the**TaskbarBadges** DWORD using the Registry Editor to bring back notification badges on Windows.

 As you may already know, editing registry files in Windows involves risk. Hence, it’s important to be cautious while using the Registry Editor. If you’re unfamiliar with it, we recommend reading our guide on[what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) .

 Also, it’s a good idea to[back up all the Registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. Once you've done that, use these steps to enable taskbar badges on Windows via the Registry Editor:

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
<li><a href="https://windows11.techidaily.com/top-techniques-to-quell-input-delay-on-windows-11/"><u>Top Techniques to Quell Input Delay on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-visual-coherence-integrating-this-pc-icon/"><u>Enhance Visual Coherence: Integrating 'This PC' Icon</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-remedy-unsupported-audio-device-in-windows-os/"><u>Steps to Remedy Unsupported Audio Device in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-counteract-install-net-core-now-on-pc/"><u>How to Counteract Install .NET Core Now on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-video-drivers-in-win1110/"><u>Correcting Failed Video Drivers in Win11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-developers-rejoice-unveiling-microsoft-copilot/"><u>Windows Developers Rejoice: Unveiling Microsoft Copilot</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-unblocked-access-for-microsoft-store-app-in-win11/"><u>Reinstating Unblocked Access for Microsoft Store App in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-anarchy-how-to-heal-fractured-win11-registry-elements/"><u>Avoiding Anarchy: How to Heal Fractured Win11 Registry Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-install-non-verified-windows-applications/"><u>Steps to Install Non-Verified Windows Applications</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-high-quality-vector-graphics-top-10-sources/"><u>In 2024, High-Quality Vector Graphics  Top 10 Sources</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-easy-screenshot-methods-for-mac-users/"><u>[Updated] 2024 Approved  Easy Screenshot Methods for Mac Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-mobile-video-editing-alternatives-to-powerdirector-top-picks/"><u>2024 Approved Mobile Video Editing Alternatives to PowerDirector Top Picks</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-picks-video-grabbers-on-microsofts-os-for-2024/"><u>Top Picks  Video Grabbers on Microsoft's OS for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-how-to-add-subtitlescaptions-in-final-cut-pro-x/"><u>Updated How to Add Subtitles/Captions in Final Cut Pro X?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-art-of-thumbnail-design-choosing-best-fonts/"><u>2024 Approved  The Art of Thumbnail Design  Choosing Best Fonts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-decoding-successful-tiktok-advertising-plans/"><u>2024 Approved  Decoding Successful TikTok Advertising Plans</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-precision-in-digital-imaging-a-professionals-approach/"><u>In 2024, Precision in Digital Imaging  A Professional's Approach</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-synapse-your-thoughts-on-mematics-platform/"><u>[New] Synapse Your Thoughts on Mematic's Platform</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-mastering-instagram-concealing-tags-efficiently/"><u>[New] Mastering Instagram  Concealing Tags Efficiently</u></a></li>
</ul></div>
