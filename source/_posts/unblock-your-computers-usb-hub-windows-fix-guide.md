---
title: "Unblock Your Computer's USB Hub: Windows Fix Guide"
date: 2024-07-11T21:16:37.837Z
updated: 2024-07-12T21:16:37.837Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unblock Your Computer's USB Hub: Windows Fix Guide"
excerpt: "This Article Describes Unblock Your Computer's USB Hub: Windows Fix Guide"
keywords: USB Hub Unlocking,Windows USB Fix,Clear USB Port,Device Error Fix,Optimize USB Hub,Free USB Solution,Hub Performance Enhance
thumbnail: https://thmb.techidaily.com/04c62b2f290b2c5f1899e5598ab465be77832cb08688d450e39f1038f772602c.png
---

## Unblock Your Computer's USB Hub: Windows Fix Guide

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
<li><a href="https://windows11.techidaily.com/illuminating-windows-multi-monitor-setup-selecting-the-best-control-tools/"><u>Illuminating Windows Multi-Monitor Setup: Selecting the Best Control Tools</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-vivo-y100t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-version-numbers-post-update/"><u>Exploring Windows Version Numbers Post-Update</u></a></li>
<li><a href="https://windows11.techidaily.com/howto-unpacking-and-implementing-windows-compressed-archive-cab-files/"><u>Howto: Unpacking & Implementing Windows' Compressed Archive (CAB) Files</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-audiophiles-guide-to-mp3-mastery-expert-software-for-metadata-management-on-both-windows-and-mac-os-2024-edition/"><u>Updated Audiophiles Guide to MP3 Mastery Expert Software for Metadata Management on Both Windows and Mac OS, 2024 Edition</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-ultimate-video-recording-guide-s-best-camcorder/"><u>[New] In 2024, Ultimate Video Recording Guide 'S Best Camcorder</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-10-most-popular-beauty-gurus-on-youtube/"><u>In 2024, 10 Most Popular Beauty Gurus on YouTube</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-nubia-red-magic-9-pro-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Nubia Red Magic 9 Pro to iPod | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-easy-ways-to-translate-tiktok-videos/"><u>Updated 2024 Approved Easy Ways to Translate TikTok Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sync-errors-in-nvidia-cp-windows-11/"><u>Fixing Sync Errors in NVidia CP Windows 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-resize-crop-and-optimize-mastering-linkedin-video-thumbnails/"><u>Updated In 2024, Resize, Crop, and Optimize Mastering LinkedIn Video Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-dns-management-in-windows-11/"><u>Masterful DNS Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/clear-screen-techniques-focus-on-your-message-not-the-ambiance-for-2024/"><u>Clear Screen Techniques  Focus on Your Message, Not the Ambiance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-want-to-learn-how-to-make-gaming-montage-videos-you-have-come-to-the-right-place-this-guide-will-teach-you-all-you-need-to-know-to-create-mont/"><u>2024 Approved Want to Learn How to Make Gaming Montage Videos? You Have Come to the Right Place. This Guide Will Teach You All You Need to Know to Create Montages of Video Games and Share Them with Other Players</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-fatal-discord-errors-on-windows-1011-a-comprehensible-guide/"><u>Handling Fatal Discord Errors on Windows 10/11: A Comprehensible Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-2024-windows-devices-you-cant-miss/"><u>Innovative 2024 Windows Devices You Can't Miss</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-adding-speed-meter-to-taskbar/"><u>Quick Guide: Adding Speed Meter to Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win-11-issue-resolution/"><u>Mastering the Art of WIN 11 Issue Resolution</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-pcmacphone-step-by-step-guide-to-movie-capture/"><u>2024 Approved  PC/Mac/Phone  Step-by-Step Guide to Movie Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/loop-it-live-watch-youtube-in-sequential-sweetness/"><u>Loop It Live  Watch YouTube in Sequential Sweetness</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-win11-screen-saver-settings/"><u>Personalizing Win11 Screen Saver Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-package-unopenable-woes/"><u>Navigating Through Windows Package Unopenable Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-event-viewer-glitches-in-win-11/"><u>Methods to Correct Event Viewer Glitches in Win 11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-bring-your-logo-to-life-top-10-free-animated-logo-makers-for-2024/"><u>New Bring Your Logo to Life Top 10 Free Animated Logo Makers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-installation-failed-in-discord-for-windows-os/"><u>Fix 'Installation Failed' In Discord for Windows OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-the-ultimate-laptop-and-mobile-roadmap-for-old-facebook-stories/"><u>[New] 2024 Approved  The Ultimate Laptop & Mobile Roadmap for Old Facebook Stories</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-liberating-laughter-through-limitations-funniest-facebook-detainment-tales/"><u>[Updated] Liberating Laughter Through Limitations  Funniest Facebook Detainment Tales</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/master-wins-control-in-windows-11-easy-steps/"><u>Master Wins Control in Windows 11: Easy Steps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-the-fins-of-conversation-mastering-the-technique-of-clownfish-inspired-sound-effects-on-online-platforms/"><u>Updated In 2024, The Fins of Conversation Mastering the Technique of Clownfish-Inspired Sound Effects on Online Platforms</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-enhance-live-stream-performance-with-these-5-pro-tips/"><u>In 2024, Enhance Live Stream Performance with These 5 Pro Tips</u></a></li>
</ul></div>
