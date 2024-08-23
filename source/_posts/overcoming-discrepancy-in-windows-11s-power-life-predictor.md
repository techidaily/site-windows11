---
title: Overcoming Discrepancy in Windows 11'S Power Life Predictor
date: 2024-08-22T21:40:28.627Z
updated: 2024-08-23T21:40:28.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Discrepancy in Windows 11'S Power Life Predictor
excerpt: This Article Describes Overcoming Discrepancy in Windows 11'S Power Life Predictor
keywords: WinPowerLifePredict,WinLifeDiscrepancy,Windows11Lifecorrrect,PredictorPowerIssue,PowerLifeWindowsTips,LifespanCorrectionWin,LifePredictErrorSolve
thumbnail: https://thmb.techidaily.com/4661968631eef5e118e434f91c87fd30d0c4ad99eff2c33463bfeb19637f99d3.jpg
---

## Overcoming Discrepancy in Windows 11'S Power Life Predictor

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


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
<li><a href="https://win-able.techidaily.com/1723005574195-black-ops-cold-war-crack-the-mystery-behind-errorcode-0xc0000005-and-play-smoothly/"><u>'Black Ops Cold War': Crack the Mystery Behind ERROR_CODE 0xC0000005 and Play Smoothly</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hololens-review-pioneering-virtual-spacecraft/"><u>[New] HoloLens Review  Pioneering Virtual Spacecraft</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-critical-review-of-vlcs-capture-tools/"><u>[New] In 2024, Critical Review of VLC's Capture Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-mastering-skype-meetings-windowsos-x-record/"><u>[New] In 2024, Mastering Skype Meetings  Windows/OS X Record</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-top-11-video-cameras-under-500-a-frugal-filmmakers-list/"><u>[New] In 2024, Top 11 Video Cameras Under $500  A Frugal Filmmaker's List</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-night-of-the-living-dead-games-an-epic-selection/"><u>[New] Night of the Living Dead Games  An Epic Selection</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-of-podcast-storytelling-writing-tips-and-example-guides/"><u>[Updated] The Art of Podcast Storytelling  Writing Tips & Example Guides</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-uncovering-the-appeal-filmora-editors-most-attractive-features/"><u>[Updated] Uncovering the Appeal  Filmora Editor's Most Attractive Features</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hyper-resolution-hub-top-8k-cameras-decoded/"><u>2024 Approved  Hyper-Resolution Hub  Top 8K Cameras Decoded</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-stealthy-sound-suppression-techniques-for-fade-out/"><u>2024 Approved  Stealthy Sound Suppression  Techniques for Fade-Out</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/ace-the-art-of-speech-top-9-language-fluency-hints/"><u>Ace the Art of Speech: Top 9 Language Fluency Hints</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-honor-x50i-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Honor X50i</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/discover-cutting-edge-computing-at-toms-hardware-review-hub/"><u>Discover Cutting-Edge Computing at Tom's Hardware Review Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-guide-to-device-tweaks-in-the-latest-windows-version/"><u>Expert Guide to Device Tweaks in the Latest Windows Version</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/file-explorer-missing-sd-card-resolution-guide/"><u>File Explorer Missing SD Card: Resolution Guide</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-samsung-galaxy-a14-4g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Samsung Galaxy A14 4G Quickly | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-utorrent-connectivity-problems-on-pcs/"><u>Fixing uTorrent Connectivity Problems on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-voice-typing-malfunction-error-code-0x80049dd3-on-windows-11/"><u>Fixing Voice Typing Malfunction (Error Code: 0X80049DD3) on Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/free-tips-embedding-moving-images-in-written-content-for-2024/"><u>Free Tips  Embedding Moving Images in Written Content for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/from-viewer-to-victor-step-by-step-windows-pc-guide-for-high-quality-live-recording/"><u>From Viewer to Victor  Step-by-Step Windows PC Guide for High-Quality Live Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-error-code-0xc00000f-with-ease-on-pcs/"><u>Handling Error Code 0xC00000F with Ease on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-missing-tabs-in-windows-11-file-explorer/"><u>How to Fix Missing Tabs in Windows 11 File Explorer</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-11-proplus-phone-without-password-by-drfone-android/"><u>How To Unlock Realme 11 Pro+ Phone Without Password?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-nokia-c12-pro-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Nokia C12 Pro</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-poco-x5-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Poco X5 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/integrating-dns-client-service-in-windows-11-with-precision/"><u>Integrating DNS Client Service in Windows 11 with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-top-4-windows-programs-for-webp-image-viewer/"><u>Introducing Top 4 Windows Programs for WebP Image Viewer</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-pc-fresh-implementing-auto-file-cleanup-in-winos/"><u>Keep Your PC Fresh: Implementing Auto-File Cleanup in WINOS</u></a></li>
<li><a href="https://windows11.techidaily.com/key-collectors-rejoice-get-the-perfect-pair-of-keys-and-essential-windows-11-612lifetime/"><u>Key Collectors Rejoice – Get the Perfect Pair of Keys & Essential Windows 11, $6.12/Lifetime!</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-guide-to-inspecting-windows-11-history/"><u>Mastery Guide to Inspecting Windows 11 History</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-distractions-with-wins-management-on-win-11/"><u>Minimizing Distractions with Wins Management on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-windows-terminal-lockup/"><u>Navigating Past Windows Terminal Lockup</u></a></li>
<li><a href="https://windows11.techidaily.com/old-meets-new-a-windows-11-transformation-into-98-style/"><u>Old Meets New: A Windows 11 Transformation Into 98 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/purge-your-pcs-defender-footprint-with-easy-steps/"><u>Purge Your PC’s Defender Footprint with Easy Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-loading-issues-on-discord-software/"><u>Quick Fixes for Loading Issues on Discord Software</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-linguistic-leap-translating-words-via-windows-1011-hotkeys/"><u>Quick Linguistic Leap: Translating Words via Windows 10/11 Hotkeys</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-reactivate-your-calendar-and-mail-on-w11/"><u>Quick Tips: Reactivate Your Calendar & Mail on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-discords-loading-failures-in-windows/"><u>Resolving Discord's Loading Failures in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-non-functional-activation-in-os-11/"><u>Resolving Non-Functional Activation in OS 11</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-note-taking-tips-for-windows-11-users/"><u>Seamless Note-Taking Tips for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-windows-7-techniques-against-uac-intrusions/"><u>Securing Windows: 7 Techniques Against UAC Intrusions</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-epic-games-installation-windows-wise/"><u>Speeding Up Epic Games Installation Windows-Wise</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-non-registered-hdds/"><u>Techniques to Rectify Non-Registered HDDs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-insightful-guide-to-facebooks-birthplace-appeal-reasons-and-core-elements/"><u>The Insightful Guide to Facebook's Birthplace, Appeal Reasons, and Core Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-spotify-link-failures-on-pcs-windows/"><u>Troubleshooting Spotify Link Failures on PCs (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-text-emphasis-and-highlight-effects-on-pc/"><u>Turn On/Off Text Emphasis and Highlight Effects on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-onoff-windows-key-like-a-pro/"><u>Turn On/Off Windows Key Like a Pro</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/understanding-the-role-of-dimensions-in-youtubes-viewer-engagement-for-2024/"><u>Understanding the Role of Dimensions in YOUTUBE's Viewer Engagement for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-copy-and-paste-features-with-application-guard-in-edge-w11-edition/"><u>Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-7-key-windows-11-widgets-for-enhanced-productivity/"><u>Unveiling 7 Key Windows 11 Widgets for Enhanced Productivity</u></a></li>
<li><a href="https://windows11.techidaily.com/visualizing-disks-wisely-the-windows-methodology/"><u>Visualizing Disks Wisely: The Windows Methodology</u></a></li>
</ul></div>
