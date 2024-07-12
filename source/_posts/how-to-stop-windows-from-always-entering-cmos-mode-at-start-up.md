---
title: How to Stop Windows From Always Entering CMOS Mode at Start-Up
date: 2024-07-11T21:28:49.952Z
updated: 2024-07-12T21:28:49.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Stop Windows From Always Entering CMOS Mode at Start-Up
excerpt: This Article Describes How to Stop Windows From Always Entering CMOS Mode at Start-Up
keywords: Stopping CMOS Boot,Windows Startup Issue,Avoid CMOS Default,CMOS Mode Fix,Prevent CMOS Entry,Stop Automatic CMOS,Bypass CMOS Setup
thumbnail: https://thmb.techidaily.com/19c73d13dc30898f49d32d8c5d0e6badbf2d50aea1c634709fd828dcee42d79c.jpg
---

## How to Stop Windows From Always Entering CMOS Mode at Start-Up

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

 When this button is pressed, Windows will boot into BIOS instead of the operating system following a turn-on. So, if your device is automatically booting into BIOS, it is possible that this key got stuck while pressed down on the keyboard, telling your PC to boot into BIOS.

 Therefore, make sure the boot key on your keyboard isn't pressed. If there are any dust particles on it, wipe them off and press the key several times to ensure nothing is stuck.

## 4\. Ensure the Drive Containing the Operating System Is Plugged In

 Your device can also boot into BIOS if it does not find a bootable drive containing your operating system. Typically, it happens when your PC's hard drive disconnects or is no longer detected by your device due to a hardware issue.

 Thus, you must ensure that your drive is connected and detectable by your system and that it isn't causing your device to boot into BIOS. Since the BIOS interfaces of most laptops differ between manufacturers, the process to check that varies.

 Users facing this issue on a Dell device should navigate to the **System Information** tab in BIOS and look under **Device Information**.

![Checking the Device Information in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-the-device-information-in-bios-1.jpg)

 If you don't see the drive with your OS installed, ensure it's connected properly. If your drive is connected but not detectable by your device, you should have it inspected to see if there is a hardware problem. However, if the drive containing your operating system is listed there, move on to the next step.

## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

## 8\. Replace or Reinsert the CMOS Battery

![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

## Don’t Let Your Windows PC Boot to BIOS

 Seeing your device boot directly into BIOS rather than Windows can be extremely frustrating. We hope the above fixes will help you successfully resolve the issue and boot to Windows. If the above fixes don't work, repair or reinstall Windows. If that doesn't work either, the laptop could have a hardware problem, so take it to a technician for inspection.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/why-choosing-windows-11-is-a-wise-decision-over-macos/"><u>Why Choosing Windows 11 Is a Wise Decision over MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-driver-checks-in-windows-no-signatures-any-installation/"><u>Circumventing Driver Checks in Windows: No Signatures, Any Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-edge-building-snaps-with-powertoys/"><u>The Insider's Edge: Building Snaps with PowerToys</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-samsung-galaxy-s23-fe-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Samsung Galaxy S23 FE FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-guide-to-image-spin-on-your-windows-11-pc/"><u>The Complete Guide to Image Spin on Your Windows 11 PC</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/secure-and-safe-interactions-a-list-of-trustworthy-chat-services-for-strangers-for-2024/"><u>Secure and Safe Interactions A List of Trustworthy Chat Services for Strangers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-selectable-text-in-windows-based-pdf-documents-easily/"><u>Tackle Non-Selectable Text in Windows-Based PDF Documents Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-selection-of-cost-free-storage-solutions-for-windows-users/"><u>The Ultimate Selection of Cost-Free Storage Solutions for Windows Users</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>Additional Tips About Sinnoh Stone For Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-compre-points-for-a-smooth-and-compliant-4k-youtube-file-transfer/"><u>[New] Compre Points for a Smooth and Compliant 4K Youtube File Transfer</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-fb-video-hacks-instant-mp4-downloads/"><u>[New] In 2024, FB Video Hacks  Instant MP4 Downloads</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-iphone-guide-to-achieving-stunning-hdr-photos/"><u>2024 Approved  IPhone Guide to Achieving Stunning HDR Photos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unlocking-cash-on-the-snapchat-grid-for-2024/"><u>[New] Unlocking Cash on the Snapchat Grid for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-efficient-live-gaming-broadcasting-on-xbox/"><u>In 2024, Efficient Live Gaming Broadcasting on Xbox</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-completely-removing-wsl-in-win-11/"><u>Step-by-Step: Completely Removing WSL in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-performance-reducing-background-processes/"><u>Enhancing Performance: Reducing Background Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-tutorial-to-launch-w11s-administrator-powershell/"><u>The Complete Tutorial to Launch W11's Administrator PowerShell</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/overview-of-perfect-moody-luts-for-vn-editor/"><u>Overview of Perfect Moody LUTs for VN Editor</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-speed-up-secrets-eliminating-unwanted-sound-waves-for-2024/"><u>Updated Speed-Up Secrets Eliminating Unwanted Sound Waves for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-start-driver-verifier-manager/"><u>Steps to Start Driver Verifier Manager</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-earn-big-on-tiktok-unveiling-the-top-8-profitable-approaches/"><u>[Updated] 2024 Approved  Earn Big on TikTok  Unveiling the Top 8 Profitable Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-operation-elevation-woes-on-windows-11-and-11/"><u>Breaking Down Operation Elevation Woes on Windows 11 & 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/he-complete-checklist-for-youtube-metrics-mastery-views-and-dollars-for-2024/"><u>[New] The Complete Checklist for YouTube Metrics Mastery  Views & Dollars for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/crystal-clear-in-minutes-mastering-fuzzy-window-fixes/"><u>Crystal Clear in Minutes: Mastering Fuzzy Window Fixes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-maximizing-android-video-brilliance-simple-steps/"><u>In 2024, Maximizing Android Video Brilliance  Simple Steps</u></a></li>
<li><a href="https://extra-support.techidaily.com/srt-files-unveiled-creating-and-optimizing-guide-for-2024/"><u>SRT Files Unveiled  Creating and Optimizing Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/thawing-the-frozen-menus-6-windows-remedies-explored/"><u>Thawing the Frozen Menus: 6 Windows Remedies Explored</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-from-concept-to-click-an-in-depth-look-at-gif-memes/"><u>In 2024, From Concept to Click  An In-Depth Look at GIF Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-the-default-software-on-win11-pcs/"><u>Uninstalling the Default Software on Win11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/system-saviors-the-10-best-windows-diagnostic-apps/"><u>System Saviors: The 10 Best Windows Diagnostic Apps</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-speedy-cam-and-commentary-recorder-software/"><u>[New] Speedy Cam & Commentary Recorder Software</u></a></li>
<li><a href="https://extra-information.techidaily.com/effortless-coordination-streamlining-zoom-and-gmail-collaboration-techniques/"><u>Effortless Coordination  Streamlining Zoom & Gmail Collaboration Techniques</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/automated-file-handling-via-task-scheduler/"><u>Automated File Handling via Task Scheduler</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-productivity-essential-windows-11-and-cmd-commands/"><u>Achieve Peak Productivity: Essential Windows 11 & Cmd Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-memory-consumption-in-edges-webview2/"><u>Tackling High Memory Consumption in Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/controlling-registry-tools-access-on-windows-11/"><u>Controlling Registry Tools Access on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-unveiling-the-techniques-for-autoplay-youtube-videos-on-fb/"><u>[Updated] 2024 Approved  Unveiling the Techniques for Autoplay YouTube Videos on FB</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-stopping-self-activating-store-app/"><u>Strategies for Stopping Self-Activating Store App</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-xiaomi-redmi-k70e-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Xiaomi Redmi K70E Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/an-insight-into-windows-audio-channel-separation/"><u>An Insight Into Windows' Audio Channel Separation</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-sticky-note-opening-on-windows-11/"><u>Breaking Down Sticky Note Opening on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-windows-11-editions-home-or-pro-advantage/"><u>Deciphering Windows 11 Editions: Home or Pro Advantage</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-chromes-dark-window/"><u>Clearing Up Chrome's Dark Window</u></a></li>
</ul></div>
