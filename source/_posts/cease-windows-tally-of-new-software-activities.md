---
title: Cease Windows' Tally of New Software Activities
date: 2024-06-25T12:00:04.780Z
updated: 2024-06-26T12:00:04.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cease Windows' Tally of New Software Activities
excerpt: This Article Describes Cease Windows' Tally of New Software Activities
keywords: Stop Windows Update Tracking,End Windows Activation Logging,Prevent Windows Install Monitor,Halt Windows Deactivation Counts,Disable Windows Software Alerts,Cease Windows License Tracking,Block Windows Activation Tracker
thumbnail: https://thmb.techidaily.com/983f31d4ff46a88bf34dd06f49261024f8d7c362e39532f6eee2990ca747e49a.jpg
---

## Cease Windows' Tally of New Software Activities

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.
6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/unlock-secrets-for-mastering-volume-control-in-windows-11/"><u>Unlock Secrets for Mastering Volume Control in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-starting-up-mspaint-windows-11-edition/"><u>Step-by-Step Guide: Starting up MSPaint, Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-bsod-errors-tackling-interrupt-exceptions-on-windows-11/"><u>Fixing BSOD Errors: Tackling Interrupt Exceptions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-creating-sequences-of-directories-simultaneously-in-windows/"><u>The Art of Creating Sequences of Directories Simultaneously in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microphone-errors-in-xbox-app-on-windows-11-systems/"><u>Navigating Microphone Errors in Xbox App on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-how-to-deal-with-non-terminatable-errors/"><u>Bypassing Windows: How to Deal with Non-Terminatable Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-windows-subsystem-for-androids-resource-usage/"><u>How to Change the Windows Subsystem for Android's Resource Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-chatting-feature-in-windows-11-user-implications/"><u>Taskbar Chatting Feature in Windows 11: User Implications</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/decoding-instagrams-trends-reels-and-stories-comparison-for-2024/"><u>Decoding Instagram's Trends  Reels & Stories Comparison for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-watermark-free-video-editing-software-the-top-14-free-options/"><u>Updated In 2024, Watermark-Free Video Editing Software The Top 14 Free Options</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-discover-the-best-pc-intro-creators-free-and-paid-options/"><u>Updated In 2024, Discover the Best PC Intro Creators Free and Paid Options</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-xs-max-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone XS Max to other iPhone 11 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-15-crucial-strategies-for-accessing-international-sport-events/"><u>[New] 15 Crucial Strategies for Accessing International Sport Events</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-oppo-reno-10-proplus-5g-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Oppo Reno 10 Pro+ 5G with Video Repair Utility on Mac?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-editors-toolkit-enhancing-audio-effectiveness-through-keyframe-manipulation-in-final-cut-pro-x/"><u>The Editors Toolkit Enhancing Audio Effectiveness Through Keyframe Manipulation in Final Cut Pro X</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-fbx-for-gamers-expert-tips-on-recording-playthroughs/"><u>[New] In 2024, FBX for Gamers  Expert Tips on Recording Playthroughs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/turbocharge-your-instagram-videos-online-tactics/"><u>Turbocharge Your Instagram Videos  Online Tactics</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>