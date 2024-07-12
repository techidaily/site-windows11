---
title: Controlling WinOS's Priority Setting for Hardware Acceleration
date: 2024-07-11T21:19:02.122Z
updated: 2024-07-12T21:19:02.122Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Controlling WinOS's Priority Setting for Hardware Acceleration
excerpt: This Article Describes Controlling WinOS's Priority Setting for Hardware Acceleration
keywords: WinOS Hardware Accel,OS Priority Control,Hardware Set Prio,Hardware Optimization,WinPriority Settings,Device Speed Boost,System Performance Enhance
thumbnail: https://thmb.techidaily.com/5ed909f597267ef924f41dbe3db988e7da363a5d5c3d20cd43f4003c2eedf878.jpg
---

## Controlling WinOS's Priority Setting for Hardware Acceleration

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/masterful-dns-management-in-windows-11/"><u>Masterful DNS Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminating-windows-multi-monitor-setup-selecting-the-best-control-tools/"><u>Illuminating Windows Multi-Monitor Setup: Selecting the Best Control Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/masterful-fb-watching-essential-top-10-players-for-2024/"><u>Masterful FB Watching  Essential Top 10 Players for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-credential-manager-login-issues/"><u>Resolve Credential Manager Login Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-windows-experience-by-fixing-prerequisites-first/"><u>Streamline Windows Experience by Fixing Prerequisites First</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quicker-quests-9-strategies-to-prevent-wwe-2k23-crashes/"><u>Quicker Quests: 9 Strategies to Prevent WWE 2K23 Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win-11-issue-resolution/"><u>Mastering the Art of WIN 11 Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/master-wins-control-in-windows-11-easy-steps/"><u>Master Wins Control in Windows 11: Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/vanishing-acts-concealing-keys-without-notice/"><u>Vanishing Acts: Concealing Keys Without Notice</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-motorola-edgeplus-2023-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Motorola Edge+ (2023) Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/elevating-social-influence-top-techniques-for-facebook-seo-excellence-for-2024/"><u>Elevating Social Influence  Top Techniques for Facebook SEO Excellence for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/revisiting-exe-execution-hurdles-in-windows/"><u>Revisiting EXE Execution Hurdles in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/trimming-down-linux-overheads-in-android-wsl-setup/"><u>Trimming Down Linux Overheads in Android WSL Setup</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-11-5g-by-fonelab-android-recover-photos/"><u>How to recover deleted photos from 11 5G.</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-package-unopenable-woes/"><u>Navigating Through Windows Package Unopenable Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-win11-screen-saver-settings/"><u>Personalizing Win11 Screen Saver Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-adding-speed-meter-to-taskbar/"><u>Quick Guide: Adding Speed Meter to Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-vocalists-choice-the-finest-9-online-mic-recorders-for-2024/"><u>[New] Vocalist's Choice  The Finest 9 Online Mic Recorders for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-scale-up-your-youtube-audience-by-the-hundredfold/"><u>2024 Approved  Scale Up Your YouTube Audience by the Hundredfold</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-win-11s-store-error-x00000000/"><u>Steps to Overcome Win 11'S Store Error X00000000</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-game-pass-connection-errors-in-windows/"><u>Techniques to Address Game Pass Connection Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-direct-access-for-the-curious-explorer-in-windows-11/"><u>A Guide to Direct Access for the Curious Explorer in Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-photographers-list-of-top-10-lenses-for-2024/"><u>The Photographer's List of Top 10 Lenses for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-master-the-art-of-cost-free-discord-video-extraction-for-desktopmobile/"><u>[New] Master the Art of Cost-Free Discord Video Extraction for Desktop/Mobile</u></a></li>
<li><a href="https://windows11.techidaily.com/10-command-prompt-wonders-you-didnt-know/"><u>10 Command Prompt Wonders You Didn’t Know!</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-vdl-pro-recorder-summary-detailed-breakdown/"><u>[Updated] 2024 Approved  VDL Pro Recorder Summary  Detailed Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-application-launches-windows-11s-error-0xc000003e-explained/"><u>Correcting Failed Application Launches: Windows 11'S Error 0XC000003E Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-developers-rejoice-unveiling-microsoft-copilot/"><u>Windows Developers Rejoice: Unveiling Microsoft Copilot</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-5-interesting-voice-changer-to-make-your-call-funny/"><u>Updated In 2024, 5 Interesting Voice Changer to Make Your Call Funny</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-re-imagine-your-igtv-content-the-complete-guide-to-edits/"><u>2024 Approved  Re-Imagine Your IGTV Content  The Complete Guide to Edits</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/iphone-meme-magic/"><u>IPhone Meme Magic</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/navigating-zoom-settings-for-top-notch-audio-capture/"><u>Navigating ZOOM Settings for Top-Notch Audio Capture</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-honor-play-7t-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Honor Play 7T to Apple TV | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-event-viewer-glitches-in-win-11/"><u>Methods to Correct Event Viewer Glitches in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-virtual-fraud-tips-for-discerning-true-windows-apps/"><u>Avoid Virtual Fraud: Tips for Discerning True Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-11s-frustrating-5ghz-link-failures/"><u>Solving Windows 11'S Frustrating 5GHz Link Failures</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-5-best-cellphone-tunes-of-the-year/"><u>New 2024 Approved 5 Best Cellphone Tunes of the Year</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-detailed-review-and-alternatives-of-vocaloid6-voice-generator/"><u>New Detailed Review & Alternatives of VOCALOID6 Voice Generator</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-personalize-the-ultimate-desktop-guide-for-win11-users/"><u>Streamline & Personalize: The Ultimate Desktop Guide for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/howto-unpacking-and-implementing-windows-compressed-archive-cab-files/"><u>Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-common-errors-in-office-app-activation-on-pc/"><u>Resolving Common Errors in Office App Activation on PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-learn-to-crop-images-in-fcpx-a-beginners-guide-for-2024/"><u>New Learn to Crop Images in FCPX A Beginners Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-quieting-geforces-visual-flourishes/"><u>Step-By-Step: Quieting GeForce's Visual Flourishes</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-simplifying-live-broadcasts-with-efficient-obs-tips/"><u>In 2024, Simplifying Live Broadcasts with Efficient OBS Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10-premier-alternative-activities-to-watching-sports/"><u>10 Premier Alternative Activities to Watching Sports</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-non-functional-windows-security-on-win-11/"><u>Troubleshoot Non-Functional Windows Security on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/dissecting-differences-how-exe-files-function-compared-to-msi/"><u>Dissecting Differences: How Exe Files Function Compared to Msi</u></a></li>
</ul></div>
