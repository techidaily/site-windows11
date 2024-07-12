---
title: Disabling Automatic Shutdown Timer on Windows
date: 2024-07-11T22:25:34.262Z
updated: 2024-07-12T22:25:34.262Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Automatic Shutdown Timer on Windows
excerpt: This Article Describes Disabling Automatic Shutdown Timer on Windows
keywords: Disable Win Shutdown Timer,Stop Auto Windows Shutdown,Turn Off Windows Timed Shutdown,Windows Shutdown Prevention,Automatic Shutdown On Windows Halt,Cease Windows Timeout Feature,Interrupt Windows Sleep Timer
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Disabling Automatic Shutdown Timer on Windows

 If your Windows PC is protected by a password, the computer will auto-lock whenever you restart it or put it into Sleep mode. While this auto-locking behavior is a security measure, it can be annoying on occasion.

 Fortunately, you can keep Windows from automatically locking itself. Here’s how.

## Why Is Windows 10 Automatically Locking Itself?

 Windows automatically locks itself for one simple reason: to protect your privacy.

 Imagine a scenario where you have to leave your computer unattended for an extended period. If there is no auto-lock on Windows, anyone can use your PC for any reason without any repercussions.

 By locking itself automatically once your PC goes into sleep mode, Windows ensures that your data stays private and nobody except you has access to your computer.

## How to Stop Windows From Automatically Locking Itself

You can stop Windows from automatically locking itself by:

* Disabling Windows sign-in.
* Disabling sleep mode and screen saver.
* Editing the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to disable auto-locking.

Now that we know how to do it, let's dive into the steps.

### Disabling Windows Sign-In

 Outright disabling Windows’ sign-in requirement is the most serious step that you can take to disable auto-locking on Windows. To disable the sign-in requirement:

* Hit the Windows keys, type “sign in”, and choose**Sign-in options** .
* In the**Require sign-in** section, select**Never** from the dropdown menu.
* While you are in Sign-in options, make sure to disable Dynamic lock by unchecking the option in the**Dynamic lock** section.

![Disable Windows sign-in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sign-in-2.JPG)

 Dynamic lock automatically locks your PC if a Bluetooth-connected device, for instance, your smartphone, goes out of range. So, disabling this option will ensure that your PC doesn’t lock up when you walk away from it.

### Disabling Sleep Mode and Screen Saver

 Next, because Windows automatically locks itself when in sleep mode, you can effectively disable auto-locking by keeping your computer from entering sleep mode. To do this:

* Hit the Windows key, type “power and sleep”, and choose**Power & sleep settings** .
* In the Power & sleep section, set disable mode by choosing**Never** from both dropdowns under**Sleep** .  
![Disable sleep mode on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-sleep-mode.JPG)

 If you’ve set a screen saver active on your PC, we also recommend turning it off, as it can, sometimes, cause Windows to automatically lock itself. To disable the screen saver:

* Hit the Windows key again, type “screen saver”, and click**Turn screen saver on or off** to open**Screen Saver Settings** .
* In the Screen Saver Settings, set**Screen saver** to**None** and uncheck**On resume, display the logon screen** .

![Disable screen saver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-screen-saver.JPG)

### Editing Windows Registry to Disable Auto-Locking

 Finally, you can also edit Windows Registry to stop Windows from automatically locking itself. Before we show you how to do this, make sure you understand that editing Windows Registry can make your system unstable requiring you to restart or even [perform a fresh Windows install](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) for your PC to work properly again.

So, edit Windows Registry only when nothing else works.

* Hit the Windows keys, type “registry”, right-click on**Registry Editor** , and select**Run as administrator** .
* In Registry Editor, navigate to**HKEY\_LOCAL\_MACHINE** \>**Software** \>**Policies** \>**Microsoft** .
* Next, right-click on**Windows** , select**New** , and choose**Key** to define a new key/create a new folder in Windows Registry. Name the new folder something like “Disable autoLock”.
* Now, right-click on the folder you just created, place the mouse cursor over**New** , and select**DWORD (32-bit) Value** . Change the name of this new element to “NoLockScreen”.
* Open**NoLockScreen** and set the Value data to 1\. Press ok to finish the process.

![Disable auto-lock from Windows Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-auto-lock-registry.JPG)

Finally, restart your computer to see if a lock screen appears.

## Use Windows Hello to Make Windows’ Auto-Locking Bearable

 If your PC or notebook has facial recognition or a fingerprint reader, you can set up Windows Hello to make sign-ins a breeze.

 On supported computers, Windows Hello can instantly recognize your face/fingerprint to log you in, taking the hassle out of typing a password in case of Windows auto-locking itself.


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
<li><a href="https://tiktok-clips.techidaily.com/updated-bridge-to-tiktok-lives-secrets-of-successful-entry-for-2024/"><u>[Updated] Bridge to TikTok Lives  Secrets of Successful Entry for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-discover-variety-50-complimentary-youtube-banners-available/"><u>In 2024, Discover Variety – 50 Complimentary YouTube Banners Available!</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/credential-control-in-win11-quick-ways-to-unlock-passwords/"><u>Credential Control in Win11: Quick Ways to Unlock Passwords</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-win11s-cursor-blackout-quickly/"><u>Clearing Up Win11's Cursor Blackout Quickly</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-tiktok-aspect-ratio-is-a-crucial-element-to-succeeding-in-the-tiktok-algorithm-here-are-some-suggestions-to-improve-video-quality-and-land-on-the-fo/"><u>Updated Tiktok Aspect Ratio Is a Crucial Element to Succeeding in the Tiktok Algorithm. Here Are some Suggestions to Improve Video Quality and Land on the for You Page</u></a></li>
<li><a href="https://windows11.techidaily.com/deletion-directive-for-drives-partitioned-areas-in-windows/"><u>Deletion Directive for Drives' Partitioned Areas in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/decades-of-taskbars-windows-journey-19852023/"><u>Decades of Taskbars: Windows' Journey (1985–2023)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-culinary-connoisseurs-must-watch-food-content/"><u>[New] 2024 Approved  Culinary Connoisseurs  Must-Watch Food Content</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-pinnacle-business-cloud-haven/"><u>[New] In 2024, Pinnacle Business Cloud Haven</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-how-to-do-a-poll-on-instagram-stories-the-only-guide-you-need-to-read/"><u>[Updated] 2024 Approved  How to Do a Poll on Instagram Stories  The Only Guide You Need to Read</u></a></li>
<li><a href="https://windows11.techidaily.com/construct-ai-driven-artistry-with-win11-and-paint-tool-sai-your-ultimate-guide-to-image-creation/"><u>Construct AI-Driven Artistry with Win11 & Paint Tool SAI: Your Ultimate Guide to Image Creation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-vivo-g2-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Vivo G2?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-understanding-enhanced-functionality-in-nero-waveedito-as/"><u>Updated In 2024, Understanding Enhanced Functionality in Nero WaveEdito As</u></a></li>
<li><a href="https://windows11.techidaily.com/dispatching-speed-limits-defeat-windows-100mbps-boundary/"><u>Dispatching Speed Limits: Defeat Windows' 100Mbps Boundary</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-another-users-microsoft-account-on-shared-device/"><u>Disabling Another User's Microsoft Account on Shared Device</u></a></li>
<li><a href="https://windows11.techidaily.com/cleanse-your-screen-history-3-strategies/"><u>Cleanse Your Screen History - 3 Strategies</u></a></li>
<li><a href="https://some-techniques.techidaily.com/industry-standards-selecting-prime-gear-for-ultimate-4k-results-for-2024/"><u>Industry Standards  Selecting Prime Gear for Ultimate 4K Results for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-wintvrecorder-effortless-free-live-tv-saving-software-for-2024/"><u>[Updated] WinTVRecorder  Effortless, FREE Live TV Saving Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-errors-win-os-and-df-conundrums-solved/"><u>Deciphering System Errors: Win OS and DF Conundrums Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-chrome-time-lag-on-windows-devices/"><u>Correcting Chrome Time Lag on Windows Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elite-video-influencers-for-2024/"><u>[New] Elite Video Influencers for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-ultra-clear-gaming-best-21-hdmi-compatible-monitors-ps5/"><u>2024 Approved  Ultra Clear Gaming  Best 2.1 HDMI Compatible Monitors [PS5]</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-hit-the-rhythm-easy-to-learn-top-tiktok-dance-routines/"><u>In 2024, Hit the Rhythm  Easy-to-Learn Top TikTok Dance Routines</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-recording-your-screen-and-videos-on-android/"><u>[New] 2024 Approved  Recording Your Screen & Videos on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/connectivity-problems-windows-solutions/"><u>Connectivity Problems: Windows Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-nubia-red-magic-8s-proplus-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Nubia Red Magic 8S Pro+ Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-convenience-with-windows-task-scheduler/"><u>Command Line Convenience with Windows Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-rectifying-non-functional-batches-in-windows/"><u>Deciphering and Rectifying Non-Functional Batches in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-guide-to-instant-facebook-photo-fusion/"><u>[Updated] Step-by-Step Guide to Instant Facebook Photo Fusion</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-the-oculus-quest-for-windows-vr-use/"><u>Customizing the Oculus Quest for Windows VR Use</u></a></li>
<li><a href="https://windows11.techidaily.com/comparative-overview-of-installation-methods-exe-and-msi-files/"><u>Comparative Overview of Installation Methods: Exe & Msi Files</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-console-connection-joining-win-to-ps3-controller/"><u>Direct Console Connection: Joining Win to PS3 Controller</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-dissecting-youtube-policies-and-creative-commons-licensing-dichotomy/"><u>[New] 2024 Approved  Dissecting YouTube Policies and Creative Commons Licensing Dichotomy</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-15-must-read-books-that-rule-the-social-media-reading-sphere/"><u>[New] In 2024, 15 Must-Read Books that Rule the Social Media Reading Sphere</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-gt-3-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme GT 3 Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/gentlemans-guide-to-glib-guesswork-with-spanish/"><u>Gentleman's Guide to Glib Guesswork with Spanish</u></a></li>
<li><a href="https://windows11.techidaily.com/differentiating-windows-terminal-from-powershell-a-compreayer-study/"><u>Differentiating Windows Terminal From PowerShell: A Compreayer Study</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-quick-gain-your-guide-to-snagging-tiktoks-swiftly/"><u>[Updated] In 2024, Quick Gain  Your Guide to Snagging TikToks Swiftly</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-fixing-printmanagement-error-on-windows-os/"><u>Diagnosing and Fixing 'PrintManagement' Error on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-thumbnail-heights-in-windows-11-ui/"><u>Customize Thumbnail Heights in Windows 11 UI</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-calculating-earnings-the-essence-of-youtube-short-revenue-split/"><u>2024 Approved  Calculating Earnings  The Essence of YouTube Short Revenue Split</u></a></li>
<li><a href="https://windows11.techidaily.com/cracked-codekeepers-stay-secure-in-the-now/"><u>Cracked Codekeepers: Stay Secure in the Now</u></a></li>
<li><a href="https://windows11.techidaily.com/coherent-organization-of-windows-files-max-156/"><u>Coherent Organization of Windows Files (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-user-friendly-guide-for-shortcut-placement-on-desktop/"><u>Crafting a User-Friendly Guide for Shortcut Placement on Desktop</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-your-go-to-list-asmr-on-phone-platforms/"><u>2024 Approved  Your Go-To List  ASMR on Phone Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-for-clarity-windows-terminal-as-main-app/"><u>Customize for Clarity: Windows Terminal As Main App</u></a></li>
</ul></div>
