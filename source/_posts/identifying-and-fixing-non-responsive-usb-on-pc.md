---
title: Identifying and Fixing Non-Responsive USB on PC
date: 2024-07-11T21:15:01.136Z
updated: 2024-07-12T21:15:01.136Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Identifying and Fixing Non-Responsive USB on PC
excerpt: This Article Describes Identifying and Fixing Non-Responsive USB on PC
keywords: Responsive USB Check,Fix Non-Responsive USB,USB Troubleshooting Guide,Diagnose USB Errors,Resolve USB Lag Issues,Enhance USB Performance,PC Port Optimization
thumbnail: https://thmb.techidaily.com/cb7e01d77e11396989975642eff6b3a0f5621896796311364cd34b031c122e69.jpg
---

## Identifying and Fixing Non-Responsive USB on PC

 Have your PC or laptop USB ports stopped working? To fix this, you need to diagnose the root of the problem. Here's everything you need to know to quickly get your USB ports working again on any PC or laptop.

## Think Your USB Port Is Not Working? Test It

 Before proceeding, be sure that it is the port that is faulty, rather than the device you're connecting.

 To establish which is the problem, you'll need to know how to troubleshoot the USB port. This means knowing how to test the USB port.

 Start by connecting the device to another USB port. If it works, then the problem is the first port; if the device remains undetected, you have a faulty device. (Note that if you can't [reformat the USB drive](https://www.makeuseof.com/tag/format-usb-drive/), it will need replacing.)

![Have your USB ports stopped working?](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports.jpg)

 If there's a problem with your USB port, you'll notice it thanks to either of these things:

* The connected device fails to be detected
* Your operating system displays an error message relating to the device (removing and replacing the device might solve this)

 Either way, you should investigate the state of the USB port. Has it been damaged in any way? The safest way to find out is to shut down your PC or laptop.

 Next, look at the USB port. Is it clean and dust free? There's a chance that dirt, dust, and general detritus might have become embedded in the port. This can happen with laptop and desktop computers alike.

 Dust will reduce airflow, causing your system to overheat. It is particularly damaging to laptops, where [overheating can reduce performance in seconds](https://www.makeuseof.com/tag/fix-overheating-laptop/). To fix this, clean out the USB port with a can of compressed air. A vacuum cleaner might also prove handy here.

 Finally, grab a USB cable (or flash drive) and gently wiggle it around. If the drive is moving and feels loose---typically this will be up and down---then you have a problem.

## How to Fix a Broken USB Port on PC and Laptop

 We'll look at some software fixes in a moment, but first, what if the USB port is loose?

 USB ports are soldered to a board within your computer. This may be the motherboard but is typically a secondary printed circuit board (PCB). With regular use, ports can become movable, at times completely unattached.

 Often, this is down to the shape of the connected USB devices. While small Wi-Fi, Bluetooth, and even new USB flash memory are unlikely to put any significant strain on the port's physical connection, older "stick" memory drives are a different story. So are USB cables; their size and associated weight act as a sort of lever, contributing to USB ports working loose.

 If you suspect that your motherboard USB ports are not working, replacing them isn't easy. On a desktop computer, you may be able to find a replacement board that can be slotted in without too much effort. Want to know how to fix a USB port on a laptop? It's going to take a soldering iron.

 Of course, you could take this to an expert for repair, but there will be associated costs with this. If you want to do it yourself, make sure you [learn how to solder](http://www.makeuseof.com/tag/learn-solder-simple-tips-projects/). If you're not sure, check out the software fixes first.

## Can Restarting a Computer Fix Broken USB Ports?

 "Have you tried turning it off and back on again?"

 This old tech support standby is well-known for a reason: it works!

 With your unrecognized USB device correctly inserted into the suspect USB port, restart your computer. Once the operating system has rebooted, it should detect the USB device. If not, it's worth looking at the device in the Windows device manager.

## How to Check USB Ports on Windows 10 With Device Manager

 Device Manager is a system tool in Windows that lists devices attached to your computer. They’re grouped into categories, listed alphabetically, which enables you to quickly find the device you’re looking for.

 To check the status of your USB ports in Windows 10 and 11:

1. Right-click **Start** and select **Device Manager**  
![Open Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr.png)
2. **Browse the list for** **Universal Serial Bus controllers**
3. Expand this and look for the **USB Host Controller**(your device may have a longer title, but it will feature those three words)  
![Find the USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller.png)
4. Right-click USB Host Controller (and any duplicates) and select **Uninstall**  
![Uninstall USB Host Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/muo-diy-fix-USB-ports-device-mgr-host-controller-uninstall.png)
5. Restart your computer
6. If no USB Host Controller is listed, click **Scan for hardware changes** on the toolbar

 If you're using a USB mouse and keyboard, it will be disabled while the USB Host Controllers are uninstalled.

## Have Power Settings Stopped Your USB Ports Working?

 If power management settings are overriding your USB controller, this will impact the detection of USB devices. It will appear that USB is not working, but in fact the operating system has put the device to sleep.

 This is particularly relevant if you think your laptop USB port is not working. However, if you're keen to reduce power usage, you might have set your Windows 10 desktop to low power.

**USB Selective Suspend** is a power saving setting that cuts power to the USB device, thereby reducing battery use.

 The feature usually works well, but at times makes it look as if there is a problem with your USB ports.

 Fix this by opening the Windows Control Panel and adjusting the settings.

1. Click **Start** and enter **control panel**
2. Select the corresponding result
3. Go to **Hardware and Sound > Power Options**
4. Here, find the selected plan and click **Change plan settings > Change advanced power settings**
5. Find **USB Settings** and expand to find **USB selecting suspend setting**
6. Change the drop-down menu to **Disabled**  
![Alter USB power settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/muo-windows-dead-usb-suspend-bg-2022.jpg)
7. Click **Apply** and **OK** to confirm
8. Finally, reboot your PC to ensure this change is applied

 You should find that any USB ports that were not working have now been fixed.

## USB Port Still Not Working? Reset the BIOS/UEFI Settings

 Your BIOS/UEFI exists to help provide a low-level interface between the hardware, software, and firmware on your computer. In other words, it helps all the major components of your PC combine and work together. In terms of specific functions, it helps you carry out the boot-up process, hardware initialization, system configuration, firmware updates, and so on.

 It's no wonder, then, that any tampered settings in your BIOS or UEFI will leave a variety of problems in its wake, including a malfunctioning USB port. So if you've reason to believe something has gone wrong with the BIOS/UEFI settings, we suggest resetting its settings.

 Check out [how to enter the BIOS settings on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) for instructions. If it was indeed a faulty BIOS/ UEFI stopping your USB port from working properly, then everything will be back to normal after a reset.

## You've Fixed Your Broken USB Port

 As you can see, you have several options for repairing an unresponsive USB port. In most cases, it won't be dead, and you'll be able to fix it.

 USB ports aren't the only potential weak spots on your computer. Looking after your hardware will reduce potential failures, and you can save a lot of money if you know how to test your PC for failing hardware.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/navigating-network-nuances-7-fixes-for-connectivity-in-obs-studio/"><u>Navigating Network Nuances: 7 Fixes for Connectivity in OBS Studio</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-openers-dive-into-windows-performance-data/"><u>Quick Openers: Dive Into Windows Performance Data</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-successfully-upgrade-to-virtualbox-70-on-windows-11-pcs/"><u>How to Successfully Upgrade to VirtualBox 7.0 on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-the-make-of-your-windows-machine-in-six-steps/"><u>Revealing the Make of Your Windows Machine in Six Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-scheduling-for-improved-resource-allocation-on-android-wsl/"><u>Smart Scheduling for Improved Resource Allocation on Android WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-deadly-c0000022-breakdown-in-windows-10/"><u>Fixing the Deadly C0000022 Breakdown in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/enforcing-originality-windows-screensaver-non-alterability/"><u>Enforcing Originality: Windows Screensaver Non-Alterability</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-popular-pictures-the-backstage-story/"><u>[New] 2024 Approved  Popular Pictures  The Backstage Story</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-banish-silent-tweets-add-volume-to-videos/"><u>[Updated] In 2024, Banish Silent Tweets  Add Volume to Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-11-version-22h2-update-not-installing/"><u>How to Fix the Windows 11 Version 22H2 Update Not Installing</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-online-cartoon-maker-from-photos/"><u>New 2024 Approved Online Cartoon Maker From Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-fixing-exit-code-errors/"><u>Mastering Windows: Fixing Exit Code Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-audio-glitch-in-win1011/"><u>Strategies to Overcome Audio Glitch in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reestablish-connectivity-for-print-devices-on-pcs/"><u>How to Reestablish Connectivity for Print Devices on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-transfer-apps-to-a-new-windows-11-pc/"><u>How to Transfer Apps to a New Windows 11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-recovering-battlenet-login-on-pcs/"><u>Mastering the Art of Recovering Battle.net Login on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-the-application-encountered-an-unrecoverable-error-in-roblox-on-windows/"><u>How to Fix the “The Application Encountered an Unrecoverable Error in Roblox on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-movie-color-correction-through-luts-application/"><u>2024 Approved  Streamlining Movie Color Correction Through Luts Application</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-android-usage-a-windows-11-webcam-setup/"><u>Optimizing Android Usage: A Windows 11 Webcam Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-overcome-onedrive-errors-on-w11-systems/"><u>Strategies to Overcome OneDrive Errors on W11 Systems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-revamp-your-resonance-the-7-premier-voice-recorder-change-android-apps-for-2024/"><u>[Updated] Revamp Your Resonance  The 7 Premier Voice Recorder Change Android Apps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-your-workflow-adding-context-menu-assistance/"><u>Simplify Your Workflow: Adding Context Menu Assistance</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-master-the-use-of-winservicesexe-on-windows/"><u>How to Master the Use of Winservices.exe on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-advanced-techniques-for-embedding-srt-into-mp4-files/"><u>[Updated] Advanced Techniques for Embedding SRT Into MP4 Files</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-update-failures-0x800736cc-issue/"><u>Solving Windows Update Failures: 0X800736CC Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-something-went-wrong-with-outlook-on-pcs/"><u>Decoding Something Went Wrong with Outlook on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/realign-your-windows-clock-through-chrome-settings/"><u>Realign Your Windows Clock Through Chrome Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-troubleshooters-in-windows-11-with-custom-keys/"><u>Quick Access to Troubleshooters in Windows 11 with Custom Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-error-0x80071a90-explained-simply/"><u>Fixing Windows Error 0X80071A90 Explained Simply</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-new-reset-limit-on-account-lockouts-in-windows-1011/"><u>Setting New Reset Limit on Account Lockouts in Windows 10/11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-chuckles-galore-navigate-the-best-15-comedic-youtube-crews/"><u>[New] 2024 Approved  Chuckles Galore  Navigate the Best 15 Comedic YouTube Crews</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-making-intellij-unison-function-in-win11/"><u>Quick Fixes: Making IntelliJ Unison Function in Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-spiritual-soundtracks-finding-and-tuning-for-ringtones/"><u>[Updated] Spiritual Soundtracks  Finding & Tuning for Ringtones</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-absentee-application-association-windows/"><u>How To Restore Absentee Application Association (Windows)</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-explorer-view-for-better-management/"><u>Resetting the Explorer View for Better Management</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-eyesharp-hd-high-definition-chromecasting/"><u>[Updated] 2024 Approved  EyeSharp HD  High Definition Chromecasting</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-to-others-windows-network-concealment/"><u>Invisible to Others: Windows Network Concealment</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-system-reviving-windows-11s-error-detection/"><u>Jumpstart Your System: Reviving Windows 11'S Error Detection</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-channel-building-through-characters-and-plot-twists/"><u>[Updated] Channel-Building Through Characters and Plot Twists</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-second-screen-harmony-windows-plus-android-tablets/"><u>Mastering Second Screen Harmony: Windows + Android Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-intellij-unison-not-working-a-guide-for-users-of-windows-11/"><u>Fixing IntelliJ Unison Not Working: A Guide for Users of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/3-key-steps-for-a-quick-return-to-desktop-in-wins-1011/"><u>3 Key Steps for a Quick Return to Desktop in Wins 10/11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-bridging-visuals-and-audio-instagram-content-to-mp3-magic/"><u>[New] In 2024, Bridging Visuals & Audio  Instagram Content to Mp3 Magic</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtube-versus-dailymention-identifying-key-gaps-for-2024/"><u>[Updated] YouTube Versus DailyMention  Identifying Key Gaps for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/epic-backup-strategies-to-avoid-loss/"><u>Epic Backup Strategies to Avoid Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-isarcextract-error-a-window-11-solution/"><u>Overcoming ISArcExtract Error: A Window 11 Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-windows-11-zoom-malfunction-1132/"><u>Steps to Resolve Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-turn-off-desktop-input-on-your-win-device/"><u>How to Turn Off Desktop Input on Your Win Device</u></a></li>
</ul></div>
