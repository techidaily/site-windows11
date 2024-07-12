---
title: Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
date: 2024-07-11T21:42:06.930Z
updated: 2024-07-12T21:42:06.930Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
excerpt: This Article Describes Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts
keywords: Sign-In Limits Adjustment,Account Lockout Reduce,Failed Login Policy Changes,Reset Counter Post-Sign In,Managing User Lockouts,Password Attempt Limit Update,Preventing Account Blocks
thumbnail: https://thmb.techidaily.com/90e284fb29c37a4c0c2a2e6970ee3fa6b56745fa434982e234c62e6bb83237e0.jpg
---

## Adjusting Reset Account Lockout Counter Post-Failed Sign-In Attempts

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
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-a14-5g-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy A14 5G Device</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-capture-the-best-moments-select-6-top-ranked-short-video-download-tools/"><u>[Updated] In 2024, Capture the Best Moments  Select 6 Top-Ranked Short Video Download Tools</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-essential-guide-to-capturing-vr-gaming-sessions/"><u>[Updated] 2024 Approved  Essential Guide to Capturing VR Gaming Sessions</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-best-options-top-live-streaming-platforms-according-to-types/"><u>In 2024, Best Options Top Live Streaming Platforms According to Types</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-insufficient-spec-on-game-captures/"><u>Troubleshooting Insufficient Spec on Game Captures</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/capture-save-and-share-mastering-playstation-4-recordings/"><u>Capture, Save & Share  Mastering PlayStation 4 Recordings</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-verdict-on-actives-place-among-best-recorders-for-2024/"><u>[Updated] The Verdict on Active's Place Among Best Recorders for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premier-video-tools-from-image-source/"><u>Premier Video Tools From Image Source</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-oppo-a2-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Oppo A2? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-turning-voice-into-text-mastering-microsoft-words-speech-toolkit/"><u>2024 Approved  Turning Voice Into Text  Mastering Microsoft Word's Speech Toolkit</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-how-to-do-perfect-match-paint-100-the-easy-way/"><u>Updated In 2024, How to Do Perfect Match Paint 100 the Easy Way</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-a-more-effective-and-reliable-windows-11/"><u>The Blueprint for a More Effective and Reliable Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-discover-vintage-luts-premiere-pro-free-and-paid-options-available/"><u>New In 2024, Discover Vintage LUTs Premiere Pro Free and Paid Options Available</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-approach-to-eliminate-flashing-on-windows/"><u>Systematic Approach to Eliminate Flashing on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-the-ultimate-stream-software-showdown-obs-vs-shadowplay-for-2024/"><u>[New] The Ultimate Stream Software Showdown  OBS vs ShadowPlay for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-surface-computing-firmware-upgrade-manual/"><u>The Complete Surface Computing Firmware Upgrade Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-unnecessary-filler-heres-how-to-tackle-it/"><u>Win11's Unnecessary Filler? Here’s How To Tackle It</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-brightening-the-windows-11-pointer/"><u>The Essential Guide to Brightening the Windows 11 Pointer</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-no-audio-devices-in-windows/"><u>Addressing 'No Audio Devices' In Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-comical-couture-innovative-trends-in-tiktok-comedy/"><u>[Updated] Comical Couture  Innovative Trends in TikTok Comedy</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-photo-vid-mosaic-designer-slideshows-for-sierra/"><u>[New] 2024 Approved  Photo-Vid Mosaic  Designer Slideshows for Sierra</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-easiest-way-to-edit-flv-videos-on-windows-8/"><u>Updated The Easiest Way to Edit FLV Videos on Windows 8</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-winscomrssvrdll-anomaly-during-boot-up/"><u>Tackling the Winscomrssvr.dll Anomaly During Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-exploration-of-windows-narrators-legacy-keys/"><u>Comprehensive Exploration of Windows Narrator's Legacy Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/unwrapping-the-mystery-of-monitor-miscalibration/"><u>Unwrapping the Mystery of Monitor Miscalibration</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/step-by-step-securely-saving-device-interactions-on-android-for-2024/"><u>Step by Step  Securely Saving Device Interactions on Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/freeze-yourself-no-more-9-techniques-for-easing-windows-install-locks/"><u>Freeze Yourself No More: 9 Techniques for Easing Windows Install Locks</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-comprehensive-guide-to-subtitle-sharing-on-tumblr-and-discord/"><u>In 2024, A Comprehensive Guide to Subtitle Sharing on Tumblr and Discord</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-a-thorough-insight-into-obs-recording-technology/"><u>[Updated] In 2024, A Thorough Insight Into OBS Recording Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-xiaomi-redmi-13c-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Xiaomi Redmi 13C 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-get-kinemaster-for-mac-easy-download-and-setup-instructions-for-2024/"><u>Updated Get KineMaster for Mac Easy Download and Setup Instructions for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-crafting-photos-into-engaging-videos-in-pixiz/"><u>Step-by-Step  Crafting Photos Into Engaging Videos in Pixiz</u></a></li>
<li><a href="https://windows11.techidaily.com/clear-and-constructive-icon-arrangement-ideas/"><u>Clear and Constructive Icon Arrangement Ideas</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-nokia-c02-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Nokia C02</u></a></li>
<li><a href="https://windows11.techidaily.com/blocking-windows-update-prompts/"><u>Blocking Windows Update Prompts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/overcome-artificial-watches-for-natural-views/"><u>Overcome Artificial Watches for Natural Views</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-safe-mode-an-easy-six-step-plan/"><u>Unlocking Windows 11 Safe Mode: An Easy Six-Step Plan</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-shadow-elimination-for-dark-iphone-footage/"><u>2024 Approved  Shadow Elimination for Dark iPhone Footage</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-undelete-lost-messages-from-nubia-by-fonelab-android-recover-messages/"><u>Best Android Data Recovery - Undelete Lost Messages from Nubia</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-bringing-your-vision-alive-transferring-vids-from-premiere/"><u>[New] 2024 Approved  Bringing Your Vision Alive  Transferring Vids From Premiere</u></a></li>
<li><a href="https://windows11.techidaily.com/cherishing-the-slumber-of-your-computer/"><u>Cherishing the Slumber of Your Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/tactile-hover-over-customizing-your-click-experience-in-win11/"><u>Tactile Hover Over: Customizing Your Click Experience in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-capabilities-of-docker-in-wsl-2-windows/"><u>Unleashing the Full Capabilities of Docker in WSL 2 Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-edit-wmv-files-for-free-top-5-video-editor-options/"><u>Updated In 2024, Edit WMV Files for Free Top 5 Video Editor Options</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-0xa00f4243-overlapping-camera-usage-in-apps/"><u>Troubleshooting 0xA00F4243: Overlapping Camera Usage in Apps</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-unlock-your-video-editing-potential-with-wondershare-filmora-for-2024/"><u>New Unlock Your Video Editing Potential With Wondershare Filmora for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://windows11.techidaily.com/top-essential-gratis-tools-for-windows-11-enthusiasts/"><u>Top Essential Gratis Tools for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/the-magic-behind-the-scenes-in-photo-app-delete/"><u>The Magic Behind the Scenes in Photo App Delete</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
</ul></div>
