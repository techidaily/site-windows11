---
title: Unlocking Power Settings for CPU State Insights
date: 2024-07-11T21:50:26.381Z
updated: 2024-07-12T21:50:26.381Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Power Settings for CPU State Insights
excerpt: This Article Describes Unlocking Power Settings for CPU State Insights
keywords: CPU Performance Tuning,Advanced CPU States,Energy Efficient CPUs,Power Management Techniques,CPU Insight Analysis,Temperature Control Systems,Optimize CPU State
thumbnail: https://thmb.techidaily.com/65fba9a952c6564fd879ce858daef732be8f2531c9874f65aafa43e482841322.jpg
---

## Unlocking Power Settings for CPU State Insights

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
<li><a href="https://ai-driven-video-production.techidaily.com/new-make-your-whatsapp-status-stand-out-with-these-video-maker-tools-for-2024/"><u>New Make Your WhatsApp Status Stand Out with These Video Maker Tools for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-10-most-affordable-cloud-vendors-listed/"><u>2024 Approved  Top 10 Most Affordable Cloud Vendors Listed</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-ultimate-guide-to-downloading-instagram-mp3s/"><u>Updated The Ultimate Guide to Downloading Instagram MP3s</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-breakdown-using-toolbar-in-mspcm-on-windows-11/"><u>Comprehensive Breakdown: Using Toolbar in MSPCM on Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/beginners-guide-to-io-screen-video/"><u>Beginner's Guide to IO Screen Video</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-sony-xperia-5-v-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Sony Xperia 5 V to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-mastering-aspect-ratios-in-final-cut-pro-the-ultimate-guide-2023-edition/"><u>New 2024 Approved Mastering Aspect Ratios in Final Cut Pro The Ultimate Guide (2023 Edition)</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-wired-internet-beyond-100mbps-in-windows/"><u>Accelerating Wired Internet Beyond 100Mbps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-restarting-windows-update-process/"><u>Essential Tips for Restarting Windows Update Process</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-free-online-gif-loop-generators-2023-edition/"><u>New Best Free Online GIF Loop Generators 2023 Edition</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-streamlining-your-video-creation-ootd-on-a-mac/"><u>[New] In 2024, Streamlining Your Video Creation  OOTD on a Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-network-how-to-conceal-on-windows-pc/"><u>Elusive Network: How to Conceal on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-versatility-top-10-innovative-ways-to-use-powertoys-tools/"><u>Discover Versatility: Top 10 Innovative Ways to Use PowerToys Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-vivo-s18-pro-easily-by-drfone-android/"><u>How To Unlock a Vivo S18 Pro Easily?</u></a></li>
<li><a href="https://windows11.techidaily.com/7-festive-tweaks-to-personalize-your-windows-11/"><u>7 Festive Tweaks to Personalize Your Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-an-elaborate-review-unveiling-lgs-ultrafine-4k-wonders/"><u>[Updated] An Elaborate Review  Unveiling LG's UltraFine 4K Wonders</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-expert-guide-to-using-toolbar-on-w11-winpcm/"><u>Elevate Your Productivity: Expert Guide to Using Toolbar on W11 WinPCM</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-cyber-safety-trustable-domains-on-windows-11/"><u>Enhance Cyber Safety: Trustable Domains on Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-ultimate-audio-library-organizer-windows-and-mac-edition-2024/"><u>New Ultimate Audio Library Organizer Windows & Mac Edition 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/flawlessly-merged-the-linkage-of-instagram-and-tiktok/"><u>Flawlessly Merged  The Linkage of Instagram & TikTok</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-essential-elements-for-implementing-channel-banners-in-games/"><u>In 2024, Essential Elements for Implementing Channel Banners in Games</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-multi-monitor-setup-selecting-the-best-control-tools/"><u>Illuminating Windows Multi-Monitor Setup: Selecting the Best Control Tools</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-discovering-the-essence-of-excellent-screen-capture-with-recmeister/"><u>2024 Approved  Discovering the Essence of Excellent Screen Capture with Recmeister</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-55-best-tiktok-comedy-joke-threads/"><u>[Updated] 55 Best TikTok Comedy Joke Threads</u></a></li>
<li><a href="https://windows11.techidaily.com/your-missing-flight-tech-copilot-in-new-os/"><u>Your Missing Flight Tech (Copilot) in New OS?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-art-of-adding-podcasts-in-instagram-stories/"><u>[New] The Art of Adding Podcasts in Instagram Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-hidden-chronicle-view-clean-up/"><u>Unmasking Windows' Hidden Chronicle - View, Clean Up!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unlock-full-scale-viewing-on-facebook/"><u>In 2024, Unlock Full-Scale Viewing on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-in-discord-for-windows-os/"><u>Fix 'Installation Failed' In Discord for Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-vivo-y78t-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Vivo Y78t</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tackle-icons-not-aligned/"><u>Win 11: Tackle Icons Not Aligned</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-the-symphony-of-visualization-presenting-audible-patterns-with-waveforms-and-enlivening-them-through-animation-using-blackmagic-design-fusion-/"><u>2024 Approved The Symphony of Visualization Presenting Audible Patterns with Waveforms & Enlivening Them Through Animation Using Blackmagic Design Fusion Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-oppo-a79-5g-easily-by-drfone-android/"><u>In 2024, How To Unlock a Oppo A79 5G Easily?</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-the-impact-of-high-cpu-tiworkerexe-applications/"><u>Decreasing the Impact of High-CPU TiWorker.exe Applications</u></a></li>
<li><a href="https://windows11.techidaily.com/detailed-guide-extracting-device-ids-on-windows-pcs/"><u>Detailed Guide: Extracting Device IDs on Windows PCs</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-top-10-video-merger-software-options/"><u>In 2024, Top 10 Video Merger Software Options</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tab-issue-solutions-for-non-responsive-keys/"><u>Windows Tab Issue: Solutions for Non-Responsive Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-shortcut-for-character-viewing/"><u>Windows 11 Shortcut for Character Viewing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-premium-choices-in-video-capture-tools-for-websites/"><u>[New] Premium Choices in Video Capture Tools for Websites</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-blueprint-of-visual-communication-instavideo-marketing-mastery/"><u>In 2024, The Blueprint of Visual Communication  InstaVideo Marketing Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-visuals-perfect-windows-desktop-backdrops/"><u>Elevating Visuals: Perfect Windows Desktop Backdrops</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-old-user-credentials-issue-on-win-11-os/"><u>Clearing Up 'Old User Credentials' Issue on Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/enhancing-facebook-nostalgia-video-tweaks-for-2024/"><u>Enhancing Facebook Nostalgia  Video Tweaks for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-secret-to-social-success-innovative-square-videography-tactics-for-2024/"><u>[Updated] The Secret to Social Success  Innovative Square Videography Tactics for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-envisioning-your-fb-video-showcase/"><u>[Updated] 2024 Approved  Envisioning Your FB Video Showcase</u></a></li>
<li><a href="https://windows11.techidaily.com/howto-unpacking-and-implementing-windows-compressed-archive-cab-files/"><u>Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files</u></a></li>
<li><a href="https://windows11.techidaily.com/dismantling-tpm-in-win11-using-the-power-of-rufus/"><u>Dismantling TPM in Win11 Using the Power of Rufus</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-adding-shake-effects-to-your-video-with-alight-motion-for-2024/"><u>Updated Adding Shake Effects to Your Video With Alight Motion for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-samsung-galaxy-a05s-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Samsung Galaxy A05s</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-maximize-impact-tweeting-with-videos/"><u>[Updated] In 2024, Maximize Impact  Tweeting with Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sync-errors-in-nvidia-cp-windows-11/"><u>Fixing Sync Errors in NVidia CP Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/breathing-life-into-winget-a-windows-11-solution/"><u>Breathing Life Into Winget: A Windows 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
</ul></div>
