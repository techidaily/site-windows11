---
title: Winning Over Windows' Missing Files Issue
date: 2024-07-11T21:41:01.522Z
updated: 2024-07-12T21:41:01.522Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Winning Over Windows' Missing Files Issue
excerpt: This Article Describes Winning Over Windows' Missing Files Issue
keywords: Fix Windows File Loss,Resolve Win Files Gone,Solve Missing Win Folder,Address Window File Absence,Recover Lost Windows Data,Uncover Hidden Windows Files,Rectify Missing Windows Items
thumbnail: https://thmb.techidaily.com/d5e8491d3f34992956d5390f8a8c8192037db1bb4f39254b71c759c472e8e33a.jpg
---

## Winning Over Windows' Missing Files Issue

 Out of all the errors, glitches, and problems you might encounter while using Windows, few generate as much fear as the dreaded "Operating system not found" screen. Visions of losing your entire media collection, your work, and your precious photos all flash before your eyes.

 Stop. Take a deep breath. Your data is still there—and just as importantly, you can fix the problem. Let's take a look at how to fix the "operating system not found" error on Windows 10 or Windows 11.

## 1\. Force Restart Your Windows

 Plenty of Windows troubles such as freezing up or programs malfunctions can be taken care of by a simple restart. In this case, since you are unable to boot your operating system, the only option left is to restart your PC straight from the power button of your computer.

 If this was a random one-time glitch, the quick reboot will fix the "Operating System not found" error is no time.

## 2\. Check the BIOS

 You need to check for two things in the BIOS. Firstly, you need to ensure your machine recognizes your hard drive. Secondly, you need to make sure the drive on which you installed Windows is listed as the preferred boot drive.

 The method for entering the BIOS changes from manufacturer to manufacturer. Typically, you'll need to press**Escape** ,**Delete** , or one of the**Function keys** during the boot-up process, before Windows loads. You should see an onscreen message advising you which is the correct key during the boot process.

[The BIOS menu](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) itself also varies between devices. Broadly speaking, you need to locate the**Boot** tab at the top of the screen. Unfortunately, you can only use your keyboard to navigate the BIOS menu, so keep an eye out for a list of controls on the BIOS screen.

 Within the Boot tab, highlight**Hard Drive** and press**Enter** . Make sure**Hard Drive** is listed above**USB Storage** ,**CD\\DVD\\BD-ROM** ,**Removable Devices** , and**Network Boot** . You can adjust the order using the**+** and**–** keys.

![boot order windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/boot-order-windows.jpg)

 If everything in your BIOS menu looked fine, jump to step three. If you didn't see the hard drive listed, go to step two.

## 3\. Reset the BIOS

 If your machine is not recognizing your hard drive, there are lots of possible causes. For non-tech-savvy users, the only easy solution is to try resetting the entire BIOS menu to its default values.

 At the bottom of the BIOS menu, you should see a key for**Setup Defaults** or**Reset BIOS** . On some machines it's**F9** , but it might be different on yours. Confirm your decision when prompted and restart your machine.

 If the operating system is still not found, you can stop reading this article. Unless you know a lot about building computers, you'll need to take your machine to a computer repair shop.

## 4\. Fix the Boot Records

 Microsoft Windows primarily relies on three records to boot your machine. They are the**Master Boot Record** (MBR),**DOS Boot Record** (DBR), and the**Boot Configuration Database** (BCD).

 If any of the three records becomes damaged or corrupted, there's a high chance you'll encounter the "Operating system not found" message.

 Thankfully, fixing these records is not as complicated as you might think. You just need a removable Windows installation drive. Use Microsoft's [Media Creation Tool](https://www.microsoft.com/en-gb/software-download/windows10) to create some Windows installation media.

![windows media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-media-creation-tool.jpg)

 When your tool is ready, you need to use it to boot your machine. Depending on your device, you might only need to press a single key during the boot process, or you might have to change the boot order in the BIOS menu.

 Eventually, you will see the Windows Setup screen. Enter your preferred language, keyboard, and time format, and click**Next** . On the next screen, select**Repair your computer** .

 Next, navigate to**Troubleshoot > Advanced Options > Command Prompt** . When Command Prompt loads, type the following three commands. Press**Enter** after each of them:

* **bootrec.exe /fixmbr**
* **bootrec.exe /fixboot**
* **bootrec.exe /rebuildbcd**

 Each command might take several minutes to complete. Once all the processes are finished, restart your PC and see if it boots successfully.

## 5\. Enable or Disable UEFI Secure Boot

 The [Windows operating system has come a long way](https://www.makeuseof.com/windows-brief-history/) . However, one thing remains the same. Almost every Windows machine is shipped with UEFI firmware and Secure Boot enabled. However, in some cases, it might not work. For example, if Windows is installed on a GUID Partition Table, it can only boot in UEFI mode. Conversely, if Windows is running on an MBR disk, it cannot boot in UEFI mode.

 As such, it's prudent to either enable or disable UEFI Secure Boot and see if it makes a difference. You make the adjustments in the BIOS menu. Usually, the option will be called**Secure Boot** and can be found in the**Security** tab.

![secure boot configuration windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/secure-boot-configuration-windows.jpg)

## 6\. Activate the Windows Partition

![disk part](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/disk-part.jpg)

 It's possible that the Windows partition is disabled. If that's the case, then it's possible to encounter the 'operating system not found' error in your PC. You can fix this using Windows' native diskpart tool. To work through the following steps, you will once again need a Windows installation media USB.

 Turn on your machine and boot from the tool. As in step three, you'll need to enter your language preferences, etc., click**Next** , select**Repair your computer** , and go to**Troubleshoot > Advanced Options > Command Prompt** .

 In Command Prompt, type**diskpart** and press**Enter** , then type**list disk** and press**Enter** . You will see a list of all the disks attached to your machine. Make a note of the disk number you need. Typically, it's the largest one.

 Next, type**select disk \[number\]** , replacing \[number\] with the aforementioned number. Press**Enter** .

 Now type**list volume** and press**Enter** . It will show you all the partitions on the disk you selected. Establish which partition Windows is installed on and make a note of the number, then type**select volume \[number\]** , again replacing \[number\] with the number you just noted.

 Finally, type**active** and press**Enter** . To see if the process was successful, restart your machine.

## 7\. Use Easy Recovery Essentials

 Easy Recovery Essentials is a third-party app that specializes in fixing boot issues. If none of the previous five steps have worked, it's worth trying.

 In addition to fixing the "Operating system not found" message, it can also solve other common startup error messages. They include:

* INACCESSIBLE\_BOOT\_DEVICE.
* INACCESSIBLE\_BOOT\_VOLUME.
* UNMOUNTABLE\_BOOT\_VOLUME.
* BOOTMGR is missing.
* The Boot Configuration Data for your PC is missing or contains errors.
* An error occurred while attempting to read the boot configuration data.
* Boot.ini not found.
* ... and more.

 Just download the app, burn the ISO to a CD, and use the CD to boot your machine. The app's wizard guides you through the repair process.

**Download:** [Easy Recovery Essentials](https://neosmart.net/EasyRE/) ($40, free for Windows 11)

## 8\. Reinstall Windows

 If none of the methods above have worked so far, then perhaps a complete reinstallation is in order. Don't worry, you won't lose any of your data though. Now, since you can't launch your PC, you will have to reinstall your Windows straight from a USB drive, as [laid out by Microsoft](http://docs.microsoft.com/en-us/windows-hardware/manufacture/desktop/install-windows-from-a-usb-flash-drive?view=windows-11) .

 So plug in your bootable USB drive and boot your PC from the USB. If you don't have a bootable USB yet, you can check out our guide on [creating a bootable USB from scratch](https://www.makeuseof.com/tag/10-tools-make-bootable-usb-iso-file/) and get your work started. If your Windows doesn't boot, you might first have to change the booting order so that the OS can load boot up through your USB. To do that, press the**Esc/F10/F12** or the relevant key to boot into the boot-selection device. Once you're there, change the booting order to boot from your USB.

 The process is fairly straightforward from there. Just follow the on-screen instructions, launch the installation wizard and wait while it installs a new copy of Windows.

## Last Resort: Head to the Shops

 Our tips should help you fix the operating system not found error on Windows in all but the direst of circumstances. Unfortunately, however, it's just one of many error messages that you're likely to encounter while using Microsoft's operating system.

 If you can't work out what is wrong with your machine, it makes little sense to keep fiddling. If you are not tech-savvy, you might do more harm than good. As a last resort, head to your local PC repair shop, and they should be able to get you up and running again in no time.

## Fixing the "Operating System Not Found" Error on Windows PC

 Regardless of if you fix the problem yourself, or you need professional help, you'll hopefully get a PC that remembers it has an operating system again. Best of all, your files should all be safe and sound!

 Microsoft Windows, by itself, is full of potential errors, and its official Store is no different. However, there are ways you can fix any issues you come across with the Microsoft Store.

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
<li><a href="https://windows11.techidaily.com/effortless-data-handling-navigate-4-steps-to-open-disk-management-in-windows-11/"><u>Effortless Data Handling: Navigate 4 Steps to Open Disk Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win10-blue-screen-recovery/"><u>Mastering the Art of Win10 Blue Screen Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/interpretation-of-the-red-x-icon-in-file-management/"><u>Interpretation of the Red “X” Icon in File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rejuvenate-a-dysfunctional-search-bar-in-windows-11/"><u>Guide to Rejuvenate a Dysfunctional Search Bar in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-vidas-interface-and-features-for-seamless-creation-experience-for-2024/"><u>[New] Vida’s Interface and Features for Seamless Creation Experience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-microsofts-enhancements-in-februarys-win11-patch/"><u>Exploring Microsoft's Enhancements in February's Win11 Patch</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-your-desktop-icon-positions-on-windows/"><u>How to Restore Your Desktop Icon Positions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-user-interface-fastest-uninstall-actions-with-context/"><u>Elevate User Interface: Fastest Uninstall Actions with Context</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-optimal-performance-self-updating-updated-amd-driver/"><u>Achieve Optimal Performance: Self-Updating, Updated AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-automatic-screenshore-changes-in-win11/"><u>Preventing Automatic Screenshore Changes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-future-ui-design-with-new-folder-integration-in-windows-11/"><u>Navigate the Future UI Design with New Folder Integration in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/automatic-windows-tweak-transition-to-latest-amd-driver/"><u>Automatic Windows Tweak: Transition to Latest AMD Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guide-to-amplifying-your-video-presence-with-seo-tips/"><u>[New] In 2024, Guide to Amplifying Your Video Presence with SEO Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/pc-files-on-ios-via-smb-share-connection/"><u>PC Files on iOS via SMB Share Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reversion-of-graphics-settings-for-optimal-viewing/"><u>Quick Reversion of Graphics Settings for Optimal Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/curate-your-own-win11-screen-saver/"><u>Curate Your Own Win11 Screen Saver</u></a></li>
<li><a href="https://windows11.techidaily.com/circumventing-windows-security-controlled-by-domain-admins/"><u>Circumventing Windows Security Controlled by Domain Admins</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-running-slow-or-lagging-on-your-computer-7-ways-to-fix-it/"><u>Is Windows 11 Running Slow or Lagging on Your Computer? 7 Ways to Fix It</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-replay-movies-in-android-a-step-by-step-guide/"><u>In 2024, Replay Movies in Android  A Step-by-Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-simplified-mac-solution-audioplusscreen-capture/"><u>2024 Approved  Simplified Mac Solution  Audio+Screen Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-vanquish-your-pcs-win11-blue-screen/"><u>Expert Tips to Vanquish Your PC's Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-file-explorer-opening-tabs-in-windows-11/"><u>Mastery of File Explorer: Opening Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-the-power-of-background-blur-a-windows-11-photo-guide/"><u>Discover the Power of Background Blur: A Windows 11 Photo Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-icloud-is-easy-troubleshoot-issues-on-windows/"><u>Installing iCloud Is Easy: Troubleshoot Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-activation-error-0x803f700f-fix-guide/"><u>Overcoming Windows Activation Error: 0X803F700F Fix Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-elevate-your-social-storytelling-with-added-musicality/"><u>[Updated] Elevate Your Social Storytelling with Added Musicality</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-adding-windows-hello-to-your-pc/"><u>Quick Start: Adding Windows Hello to Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-narrative-with-a-click-on-windows-11/"><u>Initiate Your Narrative with a Click on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-starting-with-windows-boot/"><u>Preventing Discord From Starting with Windows Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-desktop-aesthetics-best-pc-time-saver-apps-listed/"><u>Boost Desktop Aesthetics – Best PC Time Saver Apps Listed</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-harmonizepropc-seamless-integration-for-video-and-music/"><u>2024 Approved  HarmonizeProPC  Seamless Integration for Video & Music</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-lava-blaze-2-5g-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Lava Blaze 2 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-file-selection-adding-directories-to-context-menu/"><u>Enhancing File Selection: Adding Directories to Context Menu</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-securing-perfect-images-on-pc-check-out-these-top-5-tools/"><u>[Updated] 2024 Approved  Securing Perfect Images on PC? Check Out These Top 5 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-the-activation-hurdle-in-microsoft-office/"><u>Navigating Past the Activation Hurdle in Microsoft Office</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-boosting-your-yt-subs-a-complete-strategy-guide/"><u>[Updated] Boosting Your YT Subs  A Complete Strategy Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-elite-multiplatform-recorder-for-pcs/"><u>[Updated] In 2024, Elite Multiplatform Recorder for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-folders-to-the-context-menu-in-windows-11/"><u>How to Add Folders to the Context Menu in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-overcoming-unidentified-obs-recording-issue-on-win-11/"><u>Decoding and Overcoming Unidentified OBS Recording Issue on Win 11</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/bes-centralized-digital-media-command-center-for-2024/"><u>YouTube's Centralized Digital Media Command Center for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/future-screens-innovating-beyond-windows-11/"><u>Future Screens: Innovating Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correction-of-inaccessible-device-path-issue-in-win/"><u>Correction of Inaccessible Device Path Issue in Win</u></a></li>
</ul></div>
