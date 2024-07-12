---
title: "Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users"
date: 2024-07-11T21:56:23.555Z
updated: 2024-07-12T21:56:23.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users"
excerpt: "This Article Describes Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users"
keywords: Responsive RM Guide,Windows 11 Monitoring,Navigate Non-Responsive,Resource Monitor Steps,Windows 11 RM Tips,Monitor Troubleshooting,Fixing RM Errors
thumbnail: https://thmb.techidaily.com/4718cfe78df90fc96fd0823cd6a47f148478c5d534b3bf1b20e29d9f9fc07b91.jpg
---

## Navigating a Non-Responsive Resource Monitor: Steps for Windows 11 Users

 Resource Monitor is a Windows utility that monitors the use and performance of your computer's hardware resources. Unfortunately, it sometimes stops working or encounters issues, making it difficult to track system performance and manage resource usage.

 So, if you're having trouble getting the Resource Monitor tool working on your computer, check out the steps below to troubleshoot any issues and get it up and running again.

## What Causes the Resource Monitor App to Stop Working?

 Before we dive into solving the problem, let's first check what causes the Resource Monitor app to stop working correctly. There are a few potential causes you should consider.

 The most common cause of Resource Monitor not working is corrupted or outdated drivers. Outdated or incorrect drivers can prevent the software from running properly and cause functionality errors. Additionally, if there are hardware issues with your computer, such as a faulty power supply or RAM, problems with Resource Monitor could also arise.

 Finally, if you have recently installed new antivirus software on your computer, it could block access to the Resource Monitor program.

So, let's move on to the solution and fix this problem.

## 1\. Restart the Computer

![windows restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restart.jpg)

 When troubleshooting software-related issues, a computer restart can often resolve them without resorting to complex solutions. Doing so refreshes all running programs and services while also clearing out any temporary files that might be causing problems.

 In most cases, this can get things back up and running without requiring extra effort. Plus, this solution is usually quick and easy since you only need to shut down your PC and wait for it to boot back up again. If you're having trouble restarting your PC, you can check out our guide on the [different ways you can restart Windows](https://www.makeuseof.com/windows-restart-methods/) .

## 2\. Change the DPI Settings

 Another possible fix for Resource Monitor not working on Windows is to change your DPI settings. Changing the scaling from 100% to 125% or higher on some computers can cause issues with Resource Monitor. Therefore, try adjusting it back to its original setting and check if the tool works again.

To change the DPI scale to its default settings, follow these steps:

1. Press**Win + I** on your keyboard to [open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, select**System** .
3. Then click**Display** on the right.
4. Under the**Scale & layout** section, click the drop-down menu next to the**Scale** option.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
5. Choose the recommended value.

 Once you have made the changes, close the Settings window and run the Resource Monitor app to see if the problem is resolved.

## 3\. Run the System File Checker

 If restarting your computer and changing the DPI settings didn't work, running an SFC scan can often detect and repair any corrupted system files that might be causing problems.

To do this, follow these steps:

1. Right-click on Start and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When the UAC popup appears on the screen, click**Yes** to open Command Prompt with admin access. If you want in-depth information, read our guide on [running the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. Now in the elevated Command Prompt window, type in the command below and press Enter:  
sfc /scannow
5. Wait for the process to complete, then restart your PC.

## 4\. Check for Windows Updates

 It is also possible for an outdated version of Windows to cause this issue, so [manually check for any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and install them.

 Microsoft regularly releases new versions of Windows that fix bugs and improve performance, which makes updating worthwhile. Here's how to do it:

1. Press**Win + I** on your keyboard to launch the System Settings.
2. From the left side of the Settings menu, click**Windows Update** .
3. When Windows Update opens, click the**Check for updates** button.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)

 If there are any updates available, it will download and install them automatically. After the download completes, install the updates and restart your computer. After that, check to see if Resource Monitor is working.

## 5\. Uninstall the Latest Windows Updates

 If you recently updated your OS and there are no newer updates for it, the last update might have caused the issue. So, try uninstalling any recent update you may have installed, which could help resolve conflicts between the updates and existing system files that are causing problems with Resource Monitor.

1. Press**Win + I** on your keyboard to open the Settings menu
2. Select**Windows Update** from the left pane
3. Now go to the right and click on**Update history** .  
![Update history in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-history-in-windows-update.jpg)
4. Scroll down to Related settings and click**Uninstall updates** .  
![Uninstall the latest Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-the-latest-windows-update.jpg)

 Then select any recent updates that you want to uninstall. After that, restart your computer and check if Resource Monitor is now working properly.

## 6\. Create a New User Account

 If you're still having issues, try [creating a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and see if that fixes the issue. This can be helpful if corrupted user profile data or settings cause the problem. To do so, follow the steps below:

1. Open the Settings app on your computer.
2. From the left, select**Accounts** .
3. Click**Other users** under Account settings.
4. Next to Add other users, click**Add account** .  
![Create a New User Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-a-new-user-account.jpg)
5. On the Microsoft account page, click **I don't have this person's sign-in information** .

 Then follow the instructions to add a new user account and then sign in with that account. Now open Resource Monitor and see if it's working properly.

## 7\. Troubleshoot in Clean Boot State

 When all else fails, try starting your computer in safe mode and see if the problem persists. If it does not, then background services and applications are possibly conflicting with startup items and causing this error to occur.

In such a case, you need to perform a clean boot as instructed below:

1. Open the**Run** dialog box.
2. Type**MSConfig** in the text box and hit Enter.
3. Check the**Selective startup** box on the General tab.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. Uncheck the**Load startup items** box.
5. Switch to the**Services** tab and check the**Hide all Microsoft services** box.  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Then click**Disable All** .
7. Go to the Startup tab and click the**Open Task Manager** link
8. Disable any services or programs that are active in Startup apps.

 Once you have done this, close Task Manager, then click**OK** on the MSConfig window to save these changes. Now restart your computer for them to take effect, then try using Resource Monitor to see if they work now.

## Resolve Resource Monitor Issues in Windows 11

 Resource Monitor helps you monitor the performance and usage of your system's resources, including memory, disk, and network activity. If you're having trouble accessing this tool, this guide may help.


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
<li><a href="https://windows11.techidaily.com/adapting-windows-11-multifaceted-monitor-wallpaper-strategy/"><u>Adapting Windows 11: Multifaceted Monitor Wallpaper Strategy</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-ideas-to-make-a-perfect-cafe-vlog-for-2024/"><u>New Ideas to Make A Perfect Café Vlog for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/balance-usage-and-energy-efficiency-with-automatic-rest-mode/"><u>Balance Usage & Energy Efficiency with Automatic Rest Mode</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-skype-learning-logs/"><u>2024 Approved  Skype Learning Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-administrative-status-via-windows-terminal/"><u>Achieve Administrative Status via Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-overload-on-windows-applications-0x80860010/"><u>Bypassing Overload on Windows Applications (0X80860010)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/picture-power-infusing-textual-elements-on-windows-and-mac-photo-canvas/"><u>Picture Power  Infusing Textual Elements on Windows & Mac Photo Canvas</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-top-15-most-popular-tiktokers-that-will-inspire-you/"><u>[New] Top 15 Most Popular TikTokers that Will Inspire You</u></a></li>
<li><a href="https://windows11.techidaily.com/breathe-life-into-dead-wi-fi-connections-on-windows-10-with-this-list/"><u>Breathe Life Into Dead Wi-Fi Connections on Windows 10 with This List</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-efficient-revenue-streams-the-guide-to-making-money-from-youtube-mobile-for-2024/"><u>[Updated] Efficient Revenue Streams  The Guide to Making Money From YouTube Mobile for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/chrome-files-upload-hurdle-heres-how-to-clear-it-on-windows/"><u>Chrome Files Upload Hurdle? Here's How to Clear It on Windows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-you-watch-mov-movies-on-galaxy-m14-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can you watch MOV movies on Galaxy M14 5G ?</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-webcam-hurdles-tackling-error-a00f4289-on-win11/"><u>Bypassing Webcam Hurdles - Tackling Error A00F4289 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/audio-capture-while-screen-recording-with-snipping-tool-max-156/"><u>Audio Capture While Screen Recording with Snipping Tool (Max 156)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-streaming-showdown-obs-versus-twitch-space-for-2024/"><u>[Updated] Streaming Showdown  OBS versus Twitch Space for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-application-support-limitations-on-windows-7/"><u>Addressing Application Support Limitations on Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/accessing-windows-11s-screen-capture-shortcut/"><u>Accessing Windows 11'S Screen Capture Shortcut</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-dissecting-samsungs-photo-enhancing-software-features/"><u>[New] 2024 Approved  Dissecting Samsung's Photo Enhancing Software Features</u></a></li>
<li><a href="https://windows11.techidaily.com/1719306890834-key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-essential-wmp-routine-for-cds-ripping-and-batch-processing/"><u>In 2024, The Essential WMP Routine for CDs Ripping & Batch Processing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/step-by-step-strategies-for-successful-facebook-giving-for-2024/"><u>Step-by-Step Strategies for Successful Facebook Giving for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/nubia-red-magic-8s-pro-video-recovery-recover-deleted-videos-from-nubia-red-magic-8s-pro-by-fonelab-android-recover-video/"><u>Nubia Red Magic 8S Pro Video Recovery - Recover Deleted Videos from Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-appreciation-showcase-outro-themes-for-all-budgets/"><u>In 2024, Appreciation Showcase  Outro Themes for All Budgets</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/streaming-through-vlc-a-comprehensive-guide-to-mp4-and-format-switches/"><u>Streaming Through VLC  A Comprehensive Guide to MP4 & Format Switches</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-lava-blaze-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-linux-ecosystem-within-hyper-v-windows-environment/"><u>Building a Linux Ecosystem Within Hyper-V Windows Environment</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/affordable-audio-capture-software-the-best-of-discords-offers/"><u>Affordable Audio Capture Software  The Best of Discord's Offers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/syncing-images-pc-to-iphone-file-sharing/"><u>Syncing Images  PC-to-iPhone File Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/7-key-steps-to-overcome-google-chrome-profile-faults/"><u>7 Key Steps to Overcome Google Chrome Profile Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/7-essential-fixes-to-tackle-the-http-too-many-requests-issue-in-windows/"><u>7 Essential Fixes to Tackle the HTTP Too Many Requests Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-faulty-alerts-from-windows-10s-shield/"><u>Addressing Faulty Alerts From Windows 10'S Shield</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-live-tv-battle-who-wins-obs-or-twitch-studio/"><u>[Updated] 2024 Approved  Live TV Battle  Who Wins? OBS or Twitch Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/1719311224382-tackle-snip-and-sketch-obstacles-to-perfectly-capture-entire-screen/"><u>Tackle Snip & Sketch Obstacles to Perfectly Capture Entire Screen.</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-a-spectrum-of-screams-the-best-places-to-download-terrifying-tones-online-for-2024/"><u>New A Spectrum of Screams The Best Places to Download Terrifying Tones Online for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/blackview-minipc-expansive-but-sluggish-storage/"><u>Blackview MiniPC: Expansive but Sluggish Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-inaccessible-router-settings-in-windows/"><u>Bypassing Inaccessible Router Settings in Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-replay-retro-thrills-top-5-ps1-game-emulators-reviewed-for-pc/"><u>[Updated] 2024 Approved  Replay Retro Thrills - Top 5 PS1 Game Emulators Reviewed for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/adjust-brightness-slider-look-for-the-brightness-slider-under-system-or-personalization-tabs-in-settings/"><u>Adjust Brightness Slider: Look for the Brightness Slider Under 'System' Or 'Personalization' Tabs in Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/5-creative-routes-to-activate-windows-utilities/"><u>5 Creative Routes to Activate Windows Utilities</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-captioning-faults-in-win-10-systems/"><u>Addressing Captioning Faults in Win 10 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/cep-library-integration/"><u>CEP Library Integration</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-secrets-to-free-hd-video-grabs-from-facebook/"><u>[Updated] 2024 Approved  Secrets to Free HD Video Grabs From Facebook</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-what-wikipedia-cant-tell-you-about-the-10-batman-cartoons/"><u>Updated 2024 Approved What Wikipedia Cant Tell You About the 10 Batman Cartoons</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-exploring-premium-9-digital-mic-capture-tools/"><u>[Updated] In 2024, Exploring Premium 9 Digital Mic Capture Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-motorola-razr-40-ultra-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Motorola Razr 40 Ultra Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-sync-launch-sticky-notes-with-windows-start-up/"><u>Boosting Sync: Launch Sticky Notes with Windows Start-Up</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/cartoonify-your-life-best-mobile-apps-for-fun-photo-editing/"><u>Cartoonify Your Life Best Mobile Apps for Fun Photo Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-printer-issues-a-guide-for-unresponsive-print-commands/"><u>Addressing Windows Printer Issues: A Guide for Unresponsive Print Commands.</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
</ul></div>
