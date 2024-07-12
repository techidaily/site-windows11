---
title: Setting New Reset Limit on Account Lockouts in Windows 10/11
date: 2024-07-11T22:08:11.848Z
updated: 2024-07-12T22:08:11.848Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
excerpt: This Article Describes Setting New Reset Limit on Account Lockouts in Windows 10/11
keywords: WinLockResetLimit,ResetWindowsLock,PCAccountLockNew,UpdateWindowsLocks,ChangeLockTimeWin,SetLockTimeoutWin,AdjustPCLockPeriod
thumbnail: https://thmb.techidaily.com/971a75711e8320cab50ce3d6d3f20ecd50a3ca9874f23293eacb87d6417f00bb.jpg
---

## Setting New Reset Limit on Account Lockouts in Windows 10/11

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/asus-challenges-rog-ally-with-innovative-designs/"><u>ASUS Challenges ROG Ally with Innovative Designs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-60-5g-bootloader-easily-by-drfone-android/"><u>How to Unlock Realme Narzo 60 5G Bootloader Easily</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-a-quick-guide-to-pinpointing-recent-fb-views/"><u>[New] A Quick Guide to Pinpointing Recent FB Views</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-lost-extra-screen-in-w11/"><u>Addressing Lost Extra Screen in W11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-sculpting-an-impactful-tiktok-conclusion-for-2024/"><u>[New] Sculpting an Impactful TikTok Conclusion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-11-key-inactivity-issues/"><u>Addressing Windows 11 Key Inactivity Issues</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-top-ranked-windows-screen-recorder/"><u>In 2024, Top-Ranked Windows Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-inaccessible-router-settings-in-windows/"><u>Bypassing Inaccessible Router Settings in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-honor-80-pro-straight-screen-edition-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Honor 80 Pro Straight Screen Edition Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-5-best-adobe-animate-courses-and-classes/"><u>2024 Approved 5 Best Adobe Animate Courses & Classes</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-erase-iphone-12-pro-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Erase iPhone 12 Pro When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-oppo-a1-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Oppo A1 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-top-5-psone-emulators-perfect-play-on-your-pc/"><u>In 2024, Top 5 PsOne Emulators  Perfect Play on Your PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-blending-youtube-soundtracks-into-video-essence/"><u>In 2024, Blending YouTube Soundtracks Into Video Essence</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-dive-into-your-newly-watched-facebook-videos-2023-style/"><u>[New] Dive Into Your Newly Watched Facebook Videos, 2023 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-elevating-engagement-a-comprehensive-guide-to-insta-vids/"><u>[New] In 2024, Elevating Engagement  A Comprehensive Guide to Insta Vids</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-oppo-a78-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Oppo A78 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-infinix-smart-8-pro-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Infinix Smart 8 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-step-by-step-guide-to-top-notch-webcam-filming/"><u>2024 Approved  Step-by-Step Guide to Top-Notch Webcam Filming</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-craft-a-captivating-story-integrating-images-on-instagram/"><u>2024 Approved  Craft a Captivating Story  Integrating Images on Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-sync-launch-sticky-notes-with-windows-start-up/"><u>Boosting Sync: Launch Sticky Notes with Windows Start-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-captioning-faults-in-win-10-systems/"><u>Addressing Captioning Faults in Win 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-overhauling-the-settings-app-in-win11/"><u>A Guide to Overhauling the Settings App in Win11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-stepping-into-the-dynamic-universe-of-tiktoks-anime-culture-music-dancing-and-memes/"><u>[Updated] In 2024, Stepping Into the Dynamic Universe of TikTok’s Anime Culture  Music, Dancing & Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-masterful-methods-to-log-lol-bouts/"><u>[Updated] Masterful Methods to Log LOL Bouts</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-failed-rpc-calls-top-tips-for-windows-users/"><u>Addressing Failed RPC Calls: Top Tips for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/1719311224382-tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen.</u></a></li>
<li><a href="https://windows11.techidaily.com/5-creative-routes-to-activate-windows-utilities/"><u>5 Creative Routes to Activate Windows Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-frozen-wow-post-update-phases/"><u>Bypassing Frozen WoW Post-Update Phases</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-files-upload-hurdle-heres-how-to-clear-it-on-windows/"><u>Chrome Files Upload Hurdle? Here's How to Clear It on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-application-support-limitations-on-windows-7/"><u>Addressing Application Support Limitations on Windows 7</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-windows-10-photos-not-your-cup-of-tea-try-these-8-alternatives-instead/"><u>Updated 2024 Approved Windows 10 Photos Not Your Cup of Tea? Try These 8 Alternatives Instead</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-webcam-hurdles-tackling-error-a00f4289-on-win11/"><u>Bypassing Webcam Hurdles - Tackling Error A00F4289 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-edge-guards-camera-and-mic-use/"><u>Activating Edge Guards: Camera & Mic Use</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capture-flawless-underwater-images-easily-in-7-steps-for-2024/"><u>Capture Flawless Underwater Images Easily in 7 Steps for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-best-8-private-video-downloaders/"><u>[Updated] 2024 Approved  Best 8 Private Video Downloaders</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-youtube-gold-secrets-5-proven-marketing-strategies-revealed/"><u>[Updated] 2024 Approved  YouTube Gold Secrets  5 Proven Marketing Strategies Revealed</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-keep-a-permanent-record-fbm-calls-full-recording-for-2024/"><u>[New] Keep a Permanent Record  FBM Calls Full Recording for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://windows11.techidaily.com/breathe-life-into-dead-wi-fi-connections-on-windows-10-with-this-list/"><u>Breathe Life Into Dead Wi-Fi Connections on Windows 10 with This List</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-overload-on-windows-applications-0x80860010/"><u>Bypassing Overload on Windows Applications (0X80860010)</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands.</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-enhancing-visibility-and-discoverability-via-targeted-tags/"><u>[Updated] In 2024, Enhancing Visibility and Discoverability via Targeted Tags</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
</ul></div>
