---
title: Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
date: 2024-07-11T22:30:09.575Z
updated: 2024-07-12T22:30:09.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
excerpt: This Article Describes Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11
keywords: Windows Lockout Policy,Login Retry Limit,Secure Passwords,Reset Account Lockouts,Access Control Enhancements,Password Management Windows 10/11,User Security Settings Update,Lockout Policy Window,Retry Limit Security,Strong Passwords Essential,Reset User Lockouts,Access Control Windows,Password Settings Windows,Update Security Settings
thumbnail: https://thmb.techidaily.com/c01f488742f525379e15c90538d56863d279883606cc35ff29b3863a4d78b16e.jpg
---

## Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/combatting-sound-malfunction-fixing-error-code-xc00d36b4/"><u>Combatting Sound Malfunction: Fixing Error Code Xc00d36b4</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/getting-to-know-more-about-the-video-editing-interface-of-wondershare-filmora/"><u>Getting To Know More About the Video Editing Interface of Wondershare Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-windows-layout-fancywm-power-up/"><u>Customize Windows Layout: FancyWM Power Up</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-deeper-game-experience-incorporating-achievements-in-vintage-titles-through-retroarch/"><u>Dive Into Deeper Game Experience: Incorporating Achievements in Vintage Titles Through Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-down-complications-opt-for-simplicity-in-win11/"><u>Cut Down Complications: Opt for Simplicity in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-y17s-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Vivo Y17s</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-perfecting-the-art-of-whatsapp-call-logging/"><u>[New] In 2024, Perfecting the Art of WhatsApp Call Logging</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-samsung-galaxy-f14-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Samsung Galaxy F14 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-sculpting-your-online-presence-with-top-niche-creators-for-2024/"><u>[New] Sculpting Your Online Presence with Top Niche Creators for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/viral-instagram-videos-essential-tricks-for-attention/"><u>Viral Instagram Videos  Essential Tricks for Attention</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-quick-access-to-start-from-onedrive/"><u>Customizing Quick Access to Start From OneDrive</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-essential-tech-recording-movies-in-win-11-for-2024/"><u>[New] Essential Tech  Recording Movies in Win 11 for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-access-issues-enabling-windows-logins-post-fail/"><u>Clearing Access Issues: Enabling Windows Logins Post-Fail</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-elements-post-sleep-for-optimal-use/"><u>Controlling Elements Post-Sleep for Optimal Use</u></a></li>
<li><a href="https://windows11.techidaily.com/counteracting-dxgierrordeviceremoved-in-win-1011/"><u>Counteracting DXGI_ERROR_DEVICE_REMOVED in Win 10/11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-titles-superior-blu-ray-players-for-free-and-paid-users/"><u>2024 Approved  Ideal Titles  Superior Blu-Ray Players for Free and Paid Users</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-perfecting-ultimate-canon-sequence-crafts/"><u>[Updated] Perfecting Ultimate Canon Sequence Crafts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-a-comprehensive-guide-to-achieving-smooth-color-keying/"><u>[Updated] A Comprehensive Guide to Achieving Smooth Color-Keying</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-essentials-of-sharing-music-compilations-online/"><u>In 2024, The Essentials of Sharing Music Compilations Online</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bsod-0x0000003b-and-resolution-steps-in-windows-os/"><u>Decoding BSOD -0X0000003B & Resolution Steps in Windows OS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-connectivity-at-its-peak-usb-c-and-the-hp-envy-27-monitor/"><u>[New] Connectivity at Its Peak  USB-C & the HP Envy 27 Monitor</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premium-selection-of-apple-and-android-camera-slow-motion-apps-for-2024/"><u>Premium Selection of Apple & Android Camera Slow-Motion Apps for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-comprehensible-guide-downloading-safe-free-vlc-on-macos/"><u>[Updated] The Comprehensible Guide  Downloading Safe, Free VLC on macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/compilation-of-best-windows-11-art-software/"><u>Compilation of Best Windows 11 Art Software</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-windows-11s-application-could-not-be-started-error-xc000003e/"><u>Combatting Windows 11'S Application Could Not Be Started Error Xc000003e</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevate-brand-recognition-optimizing-facebook-with-keywords-and-links-for-2024/"><u>Elevate Brand Recognition  Optimizing Facebook with Keywords and Links for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/unchaining-the-cadence-online-methods-for-detecting-and-isolating-musics-pulse-for-2024/"><u>Unchaining the Cadence Online Methods for Detecting and Isolating Musics Pulse for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-absence-of-drive-letters-problems-and-cures-for-win-users/"><u>Decoding the Absence of Drive Letters: Problems & Cures for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/countering-compromised-windows-defender-on-win-11/"><u>Countering Compromised Windows Defender on Win 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-search-of-greatness-top-15-timeless-stop-motion-films/"><u>[Updated] In Search of Greatness  Top 15 Timeless Stop Motion Films</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-public-ip-with-system-commands-windows/"><u>Determining Public IP with System Commands, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-resource-unavailable-situations-on-windows-149-chars/"><u>Correcting 'Resource Unavailable' Situations on Windows (149 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-x80070091-error-in-windows-steps-for-empty-directory-problem-solving/"><u>Deciphering X80070091 Error in Windows - Steps for 'Empty Directory' Problem Solving</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-fixing-device-path-errors/"><u>Comprehensive Guide to Fixing Device Path Errors</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-procedure-call-failures-in-malwarebytes-for-windows-os/"><u>Combatting Procedure Call Failures in Malwarebytes for Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-windows-updates-and-restarts/"><u>Curtailing Windows Updates and Restarts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>