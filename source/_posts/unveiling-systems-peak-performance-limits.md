---
title: Unveiling System's Peak Performance Limits
date: 2024-07-11T21:14:39.172Z
updated: 2024-07-12T21:14:39.172Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling System's Peak Performance Limits
excerpt: This Article Describes Unveiling System's Peak Performance Limits
keywords: Peak Performance Analysis,Max Performance Boundaries,System Optimization Thresholds,Efficiency Growth Points,Operational Limit Exploration,Productivity Cap Assessment,Output Maximization Study
thumbnail: https://thmb.techidaily.com/b291d1186c17a0e27af028a28ffb312d4304bf88d64275a707a4eb2f0cc766f8.jpg
---

## Unveiling System's Peak Performance Limits

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://windows11.techidaily.com/winning-back-chrome-color-loss/"><u>Winning Back Chrome Color Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-drop-problems-in-win11/"><u>Swiftly Solve Drop Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-turning-secure-boot-and-tpm-onoff-in-vbox/"><u>Detailed Guide: Turning Secure Boot and TPM On/Off in VBox</u></a></li>
<li><a href="https://windows11.techidaily.com/approaches-to-fix-failed-launch-of-lunar-client-in-windows/"><u>Approaches to Fix Failed Launch of Lunar Client in Windows</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-samsung-galaxy-s24-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-the-start-up-sequence-of-windows-os/"><u>Decoding the Start-Up Sequence of Windows OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-transformative-versat-cookies-creative-edition/"><u>[New] Transformative Versat Cookies  Creative Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-deactivated-sliders-for-volume-control/"><u>Troubleshooting Deactivated Sliders for Volume Control</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharging-windows-solid-state-drives-utilizing-fresh-tools/"><u>Turbocharging Windows' Solid State Drives - Utilizing Fresh Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-secrets-for-mastering-volume-control-in-windows-11/"><u>Unlock Secrets for Mastering Volume Control in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-razer-kiyo-webcam-review/"><u>[New] Razer Kiyo Webcam Review</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-captivate-and-enchant-explore-the-best-creative-reactions-on-yt/"><u>[Updated] In 2024, Captivate and Enchant  Explore the Best Creative Reactions on YT</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-techniques-for-realistic-photo-motions-in-illustrator/"><u>In 2024, Techniques for Realistic Photo Motions in Illustrator</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-personalization-transforming-ordinary-into-extraordinary/"><u>Windows 11 Personalization: Transforming Ordinary Into Extraordinary</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-turn-on-or-off-windows-installation-service/"><u>Tips to Turn On or Off Windows Installation Service</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-infinix-hot-40i-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Infinix Hot 40i</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-achieve-stable-gameplay-and-fps-boost-in-roblox/"><u>Strategies to Achieve Stable Gameplay & FPS Boost in Roblox</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-eliminate-windows-unknown-value-warning/"><u>Strategies to Eliminate Windows Unknown Value Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-put-iphone-7-plus-or-ipad-on-recovery-mode-step-by-step-tutorial-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Put iPhone 7 Plus or iPad on Recovery mode? (Step by Step Tutorial) | Stellar</u></a></li>
<li><a href="https://facebook.techidaily.com/reviving-erased-social-media-statuses-on-facebook/"><u>Reviving Erased Social Media Statuses on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-to-enable-windows-11s-search-feature-in-task-manager/"><u>Simple Steps to Enable Windows 11'S Search Feature in Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-windows-memory-errors/"><u>Steps to Overcome Windows Memory Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-file-management-through-explores-sidebar/"><u>Streamlining File Management Through Explore's Sidebar</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-11-techniques-building-hotkeys-for-text-snapping/"><u>Cutting Edge Windows 11 Techniques: Building Hotkeys for Text Snapping</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-the-wow-breakdown-cure-windows-error-code-132/"><u>Avoid the WoW Breakdown: Cure Windows Error Code 132</u></a></li>
<li><a href="https://windows11.techidaily.com/ai-driven-evolution-in-windows-software-design/"><u>AI-Driven Evolution in Windows Software Design</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-through-qbittorrent-lag-a-windows-guide/"><u>Breaking Through qBittorrent Lag: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-unreachable-error-with-spotify-in-windows-1011/"><u>Tackling the Unreachable Error with Spotify in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-installation-issues-fixing-zero-error-on-win11/"><u>Avoid Installation Issues: Fixing Zero Error on Win11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-seamlessly-turning-tiktok-videos-into-gifs-with-best-tools/"><u>In 2024, Seamlessly Turning TikTok Videos Into GIFs with Best Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-how-to-screen-record-on-mac-with-shortcuts/"><u>[Updated] How to Screen Record on Mac with Shortcuts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-no-charge-frame-by-frame-youtube-tutorial/"><u>In 2024, The Ultimate No-Charge, Frame-by-Frame YouTube Tutorial</u></a></li>
</ul></div>
