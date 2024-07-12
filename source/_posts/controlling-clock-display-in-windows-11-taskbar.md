---
title: Controlling Clock Display in Windows 11 Taskbar
date: 2024-07-11T22:21:34.597Z
updated: 2024-07-12T22:21:34.597Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling Clock Display in Windows 11 Taskbar
excerpt: This Article Describes Controlling Clock Display in Windows 11 Taskbar
keywords: Win11 Time Bar Control,Taskbar Clock Management,Clock Setting Windows 11,Adjusting Windows 11 Clock,Windows 11 Display Time,Set Taskbar Clock Windows,Manage Windows Clock
thumbnail: https://thmb.techidaily.com/1b2195440e349b5f0884d1401c71f047053f6f52811a1360983fce9511380f91.jpg
---

## Controlling Clock Display in Windows 11 Taskbar

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to [access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The [Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://instagram-videos.techidaily.com/updated-debating-on-the-significance-of-truthfulness-in-selfies-for-2024/"><u>[Updated] Debating on the Significance of Truthfulness in Selfies for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-resource-locks-in-windows-11-environments/"><u>Disabling Resource Locks in Windows 11 Environments</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-comprehensive-adobe-storage-manual-and-beyond-options/"><u>2024 Approved  Comprehensive Adobe Storage Manual & Beyond Options</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-craft-a-sonic-whatsapp-update/"><u>[Updated] Craft a Sonic WhatsApp Update</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-make-your-shorts-image-visible-again-for-2024/"><u>How to Make Your Shorts' Image Visible Again for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-camera-access-overlap-in-windows-apps/"><u>Correcting Camera Access Overlap in Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/control-windows-11s-emphasis-and-search-highlight/"><u>Control Windows 11'S Emphasis and Search Highlight</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-panoramic-capture-9-techniques-to-perfection/"><u>[New] The Art of Panoramic Capture  9 Techniques to Perfection</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-xc0f1103f-geforce-not-working/"><u>Correcting Windows' XC0F1103F GeForce Not Working</u></a></li>
<li><a href="https://windows11.techidaily.com/compre-written-guide-to-repair-xbox-live-glitches/"><u>Compre Written Guide To Repair Xbox Live Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-html-display-issues-in-windows-11-email-client/"><u>Correcting HTML Display Issues in Windows 11 Email Client</u></a></li>
<li><a href="https://windows11.techidaily.com/darkeningwindowsnotepaddisplaysettings/"><u>DarkeningWindowsNotepadDisplaySettings</u></a></li>
<li><a href="https://windows11.techidaily.com/disarming-error-dism-0x800f082f-on-microsoft-os/"><u>Disarming Error: DISM 0X800F082F on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-your-digital-identity-how-to-find-out-what-computer-you-have/"><u>Decode Your Digital Identity: How to Find Out What Computer You Have</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-how-to-climb-the-social-ladder-a-guide-to-higher-facebook-page-ranks/"><u>[Updated] In 2024, How to Climb the Social Ladder  A Guide to Higher Facebook Page Ranks</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-trailblazing-through-time-era-images-explore-3-inverse-techniques-on-facebook/"><u>[Updated] In 2024, Trailblazing Through Time-Era Images  Explore 3 Inverse Techniques on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-down-display-flicker-in-windows-11-devices/"><u>Dial Down Display Flicker in Windows 11 Devices</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/overview-of-best-luts-for-vlog/"><u>Overview of Best LUTs for Vlog</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-9-live-game-streaming-platform-you-should-know/"><u>Top 9 Live Game Streaming Platform You Should Know</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-clock-divergence-chrome-vs-windows/"><u>Correcting Clock Divergence: Chrome vs Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/defeating-defunct-windows-security-hurdles-in-win-11/"><u>Defeating Defunct Windows Security Hurdles in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/directive-for-disabling-onedrive-symbol-in-windows-11s-filesystem-viewer/"><u>Directive for Disabling OneDrive Symbol in Windows 11’S Filesystem Viewer</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-craft-the-perfect-stream-a-comprehensive-guide-to-youtubes-full-rotation-videos/"><u>[New] Craft the Perfect Stream  A Comprehensive Guide to YouTube’s Full-Rotation Videos</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-total-circles-capture-systems/"><u>In 2024, Total Circles Capture Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-crafting-musical-content-on-instagram/"><u>[New] Crafting Musical Content on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-sound-misstep-solving-xc00d36b4-on-windows/"><u>Decoding Sound Misstep: Solving XC00D36B4 on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-no-longer-a-mystery-shorts-now-showing-up/"><u>2024 Approved  No Longer a Mystery  Shorts Now Showing Up</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-error-code-zero-on-your-gaming-machine/"><u>Disabling Error Code Zero on Your Gaming Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/command-prompt-mastery-the-fundamental-20-cmd-commands-to-know/"><u>Command Prompt Mastery: The Fundamental 20 CMD Commands to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-code-of-high-quality-visuals-with-windows-11-hdr/"><u>Deciphering the Code of High-Quality Visuals with Windows 11 HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-unfreezing-window-taskbar/"><u>Comprehensive Guide to Unfreezing Window TaskBar</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://windows11.techidaily.com/dial-back-the-dread-of-an-unresponsive-esc-button-in-windows/"><u>Dial Back the Dread of an Unresponsive Esc Button in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-list-of-supported-whatsapp-video-format-you-may-want-to-know/"><u>In 2024, List of Supported Whatsapp Video Format You May Want to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/consistent-experience-migrating-powertoys-on-new-pcs/"><u>Consistent Experience: Migrating PowerToys on New PCs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-efficiently-clear-out-discord-conversations-in-batches/"><u>[Updated] Efficiently Clear Out Discord Conversations in Batches</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-windows-security-hiccups-in-win-11-system/"><u>Curing Windows Security Hiccups in Win 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-path-to-app-removal-tackling-do-not-have-access-errors/"><u>Clear Path to App Removal: Tackling Do Not Have Access Errors</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/best-in-class-audio-editing-software-for-music-and-post-production/"><u>Best-in-Class Audio Editing Software for Music and Post-Production</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-the-hurdle-of-ms-teams-error-80080300-with-actionable-steps/"><u>Clear the Hurdle of MS Teams Error 80080300 with Actionable Steps</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-y100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo Y100? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-capturing-every-moment-unveiling-5-exceptional-streamer-webcams/"><u>[New] Capturing Every Moment  Unveiling 5 Exceptional Streamer Webcams</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-auto-updates-in-windows-and-office-instantly/"><u>Disable Auto-Updates in Windows & Office Instantly</u></a></li>
<li><a href="https://screen-recording.techidaily.com/essential-list-free-costless-desktop-and-web-screening-solutions-for-2024/"><u>Essential List  Free, Costless Desktop & Web Screening Solutions for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-oppo-reno-11-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Oppo Reno 11 5G</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-honor-magic-6-pro-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Honor Magic 6 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-windows-error-code-31-and-network-adapter-issues/"><u>Demystifying Windows Error Code 31 and Network Adapter Issues</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-make-a-video-a-live-photo-2023/"><u>New 2024 Approved How to Make a Video a Live Photo 2023</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-quest-for-codec-perfection-is-av1-surpassing-vp9/"><u>The Quest for Codec Perfection  Is AV1 Surpassing VP9?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-harmonyhook-tracker-extracting-sound-and-insights/"><u>[Updated] In 2024, HarmonyHook Tracker  Extracting Sound & Insights</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-full-review-of-lgs-high-definition-monitoring-experience/"><u>[New] The Full Review of LG's High Definition Monitoring Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-discord-setup-woes-on-windows-11/"><u>Correcting Discord Setup Woes on Windows 11</u></a></li>
</ul></div>
