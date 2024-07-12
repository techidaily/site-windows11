---
title: "Troubleshooting Guide: VMware Crashes, BSOD on Win11"
date: 2024-07-11T21:20:54.005Z
updated: 2024-07-12T21:20:54.005Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Guide: VMware Crashes, BSOD on Win11"
excerpt: "This Article Describes Troubleshooting Guide: VMware Crashes, BSOD on Win11"
keywords: VMware Crash Fix,Win11 BSOD Solve,Win11 VMware Stability,Troubleshoot VMware Windows,Resolve Win11 Errors,Guided Win11 Recovery,Preventing Win11 Crashes
thumbnail: https://thmb.techidaily.com/772b2b44b0378e57e7141a2aa999a88263926bcf3e3ae208c5af8f61bf24deca.jpg
---

## Troubleshooting Guide: VMware Crashes, BSOD on Win11

 VMware Workstation Player is among the best virtualization software available today. You can create virtual machines and install operating systems on them. Virtual machines save you the trouble of wiping your hard disk to try out an operating system. However, it is not the only use case of third-party hypervisors like VMware.

 And although virtual machines typically run smoothly, you might occasionally experience a BSOD error while launching or using a virtual machine in a VMware workstation player. So, we'll list the potential reasons for BSODs in VMware along with multiple methods to resolve the issue.

## Reasons for VMware BSOD Error on Windows 11

Here are a few possible reasons for the VMware BSOD error on Windows:

1. Native virtualization services like WHP are running alongside VMware.
2. You are using an outdated version of Windows.
3. VMware is conflicting with another application or background service.
4. The virtual machine is eating up more resources than the system can spare.

## How to Fix VMware BSOD Error on Windows 11

 Now, you know the possible reasons for the BSOD error while using VMware. Try out the following methods to fix the issue.

### 1\. Restart VMware

 Before moving on to more complex fixes, restart the VMware program on your Windows 11 computer. Close the program and terminate all its processes from the Task Manager. Now, relaunch VMware and power on a virtual machine. Keep the machine running for some time, and keep an eye out for BSOD errors.

### 2\. Update VMware

 An outdated version of VMware can act finicky with the new system updates. So, you must update it to apply fixes released by developers for newfound bugs. Here's how to do it:

1. Launch VMware on your system.
2. Navigate to the top left section and click on the Player button.
3. Then, go to**Help > Software Updates** .
4. Click on the**Check for Updates** button. Wait for the utility to search for the latest available update, if any.
5. If an update is available, click on the**Download and install** button. Wait for the update to install.  
![Update VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-vmware.jpg)
6. [UAC](https://www.makeuseof.com/tag/user-account-control-windows-10/) will pop up. Click on the**Yes** button to begin the update installation.
7. Close the VMware program. Follow the on-screen prompts to install the update on your system.
8. Click on the**Finish** button after the installation completes successfully.
9. Restart your system. Launch VMware and start a virtual machine. Check if the program produces a BSOD error.

### 3\. Disable Hyper-V and Other Windows Features

 Third-party hypervisors fail to launch or work properly when Hyper-V or other virtualization features such as Windows Hypervisor Platform, Virtual Machine Platform, and more. You must turn off all these features before using VMware on your Windows 11 system.

Repeat the following steps to disable Windows features:

1. Press**Win + R** to launch the Run command box. Type**appwiz.cpl** and press the enter key.
2. Programs and Features utility will launch. Click on the**Turn Windows features on or off** option.
3. Scroll down and uncheck the**Hyper-V** feature in the list. Similarly, uncheck the**Windows Hypervisor Platform** ,**Virtual Machine Platform** , and**Windows Subsystem for Linux** .  
![Disable Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-windows-features.jpg)
4. Windows will uninstall all these features from your system and auto-restart it to apply changes. It will take a while to remove all these features.
5. Sign in and launch VMware again. Now, power on a virtual machine and check if a BSOD error pops up.

### 4\. Reconfigure Virtual Machine Resources

 If your virtual machine crashes and throws a BSOD error, it is likely consuming more resources than your system can spare. Ideally, you should not devote more than 50 percent of any hardware (CPU, RAM, or disk space) to a virtual machine. Always leave enough for the host system to run smoothly and then devote the rest to the virtual machine.

Here's how to reconfigure virtual machine resources in VMware.

1. Launch VMware on your system. Click on any virtual machine in the list and select the**edit virtual machine settings** option.
2. Under the hardware tab, click on the**Memory** option. Adjust the slider to the recommended memory size.
3. Move to the Processors option and expand the**number of processor cores** dropdown list. Select**four** and click on the**OK** button.  
![Reconfigure virtual machine resources](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reconfigure-virtual-machine-resources.jpg)
4. These hardware settings are different for every operating system. Make sure to allocate only the bare minimum resources specified by the operating system developers.
5. Now, power on the virtual machine and use it for some time. If you still encounter a BSOD error, move to the next method.

### 5\. Update Windows

 An outdated version of Windows can contain bugs and may not sit well with new apps and software. So, update your Windows system using the settings app. Repeat the following steps to update Windows:

1. Press**Win + I** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to the top right section and click on the Windows Update icon.
3. Click on the**Check for updates** button. Wait for the utility to search for new updates for your device.  
![Update Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-windows.jpg)
4. Download and install the update.**Restart** your system to apply the update.
5. Launch VMware on your system and start a virtual machine.

### 6\. Perform a Clean Boot

 A background program could be interfering with the nominal working of VMware. You must perform and clean boot to isolate and identify the root cause of trouble. Clean boot will start Windows with basic drivers and programs.

To clean boot your Windows PC, repeat the following steps:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**msconfig** and press the enter key. The system configuration utility will launch.
3. Switch to the**Services** tab and click on the**Hide all Microsoft services** option.
4. Click on the**Disable all** button and then switch to the startup tab. Click on the Open Task Manager option.
5. Task Manager will launch. Right-click on a startup program and select the**Disable** option. Repeat this action for all programs.  
![Perform a Clean Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/perform-a-clean-boot-1.jpg)
6. Close Task Manager and click on the**OK** button.
7. Restart your system and launch VMware. If it runs fine, open System Configuration, enable some services, and try again.
8. Identify and uninstall the troublemaker program or keep its services disabled on startup.

### 7\. Use a Different ISO File

 A corrupt ISO file can also cause a BSOD error while installing the operating system on a virtual machine. If you are using an old ISO file that is possibly corrupt, download its most recent version and add it to the virtual machine.

 Start the virtual machine and boot from that ISO file using the boot menu options. Begin the installation process and check if the process completes without an issue.

### 8\. Use a Different Hypervisor

 The last resort is to use a different hypervisor program for the time being. Try a level-1 hypervisor like Hyper-V or use level-2 hypervisors like VirtualBox or QEMU. Report the issue to the VMware developers and wait for them to release a bug fix for the BSOD issue.

 VirtualBox had a similar issue when it wasn't compatible with Windows 11\. It took Oracle some time to release a compatible version, forcing users to find a temporary alternative while waiting for the fix.

## VMware BSOD Error Won't Bother You Anymore

 VMware can easily run all the popular operating systems inside a virtual machine. But the BSOD error renders the program unusable. Try out the basic troubleshooting methods and update VMware and Windows. After that, disable Windows Hyper-V and other virtualization features and reconfigure the virtual machine resources.


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
<li><a href="https://screen-video-capture.techidaily.com/new-tycoon-titanics-unveil-the-best-12-for-your-ultimate-business-triumph/"><u>[New] Tycoon Titanics  Unveil the Best 12 for Your Ultimate Business Triumph</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-advanced-techniques-for-smartphone-screenshots/"><u>[Updated] Advanced Techniques for Smartphone Screenshots</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-a54-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/method-to-recalibrate-windows-energy-plan/"><u>Method to Recalibrate Window's Energy Plan</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-elevate-your-online-presence-a-guide-to-thriving-youtube-branding/"><u>[New] Elevate Your Online Presence  A Guide to Thriving YouTube Branding</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-the-path-to-popularity-secrets-of-successful-tiktok-unboxers/"><u>2024 Approved  Navigating the Path to Popularity  Secrets of Successful TikTok Unboxers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-12-proplus-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme 12 Pro+ 5G Phones with/without a PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-free-online-video-capture-leaders-top-10-edition/"><u>2024 Approved  Free Online Video Capture Leaders – Top 10 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unverified-adobe-in-windows/"><u>Troubleshooting Unverified Adobe in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-error-code-xc0f1103f-with-nvidias-geforce-now/"><u>Eradicating Error Code Xc0f1103f with NVIDIA's GeForce Now</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-innovative-naming-strategies-elevating-your-filmora-channels-identity/"><u>In 2024, Innovative Naming Strategies  Elevating Your Filmora Channels' Identity</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-leap-into-a-bigger-view-the-new-full-screen-fb-video-trend/"><u>[Updated] Leap Into a Bigger View  The New Full-Screen FB Video Trend</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-morning-routine-launching-windows-and-sticky-notes/"><u>Mastering Morning Routine: Launching Windows & Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/brain-benefits-and-heartbeats-the-joint-impact-of-mindfulness/"><u>Brain Benefits and Heartbeats: The Joint Impact of Mindfulness</u></a></li>
<li><a href="https://video-capture.techidaily.com/inside-the-world-of-digital-screen-recording/"><u>Inside the World of Digital Screen Recording</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-streamlining-short-form-content-leading-edits-for-iosandroid/"><u>[New] Streamlining Short-Form Content  Leading Edits for iOS/Android</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-netconfigs-windows-11-edition/"><u>Tweaking NetConfigs: Windows 11 Edition</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-motorola-edgeplus-2023-has-native-hevc-support-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Does Motorola Edge+ (2023) has native HEVC support?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-get-zoom-on-tv-easy-solutions/"><u>New 2024 Approved How to Get Zoom on TV Easy Solutions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-turn-your-iphone-images-upside-down-with-precision-for-2024/"><u>[Updated] Turn Your iPhone Images Upside Down with Precision for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-premier-open-source-windowsmac-screenshots-and-recorders/"><u>[New] In 2024, Premier Open-Source Windows/Mac Screenshots & Recorders</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/achieve-crystal-clear-slack-discussions-with-these-10-tools-for-2024/"><u>Achieve Crystal Clear Slack Discussions with These 10 Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-geforce-experiences-unable-to-retrieve-settings-error-in-windows-11-and-11/"><u>How to Fix GeForce Experience’s “Unable to Retrieve Settings” Error in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-launch-hacks-opening-windows-11-apps-faster/"><u>Quick Launch Hacks: Opening Windows 11 Apps Faster</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/a-personalized-approach-developing-an-individualistic-tiktok-keyword-for-2024/"><u>A Personalized Approach  Developing an Individualistic TikTok Keyword for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-honor-magic-5-lite-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Honor Magic 5 Lite Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-audio-interpretation-software-zero-cost-version/"><u>[New] Audio Interpretation Software – Zero Cost Version</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-complication-windows-11-plus-nvidia-x0001/"><u>Rectifying Complication: Windows 11 + Nvidia X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-fingerprint-login-for-windows-11-users/"><u>Configuring Fingerprint Login for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-lockout-overcoming-windows-11-device-error-code-22/"><u>Bypassing Lockout: Overcoming Windows 11 Device Error Code 22</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-settings-for-effortless-administration/"><u>Mastering Windows 11 Settings for Effortless Administration</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-a-profile-error-occured-in-google-chrome-for-windows/"><u>7 Ways to Fix A Profile Error Occured in Google Chrome for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-advanced-windows-startup-techniques/"><u>Exploring Advanced Windows Startup Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-premier-video-communication-tools-the-top-10-for-ios-and-android-for-2024/"><u>[Updated] Premier Video Communication Tools  The Top 10 for iOS & Android for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-iphone-15-pro-maxipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on iPhone 15 Pro Max/iPad/iPod</u></a></li>
<li><a href="https://windows11.techidaily.com/infuse-personalized-style-in-windows-email-calendar/"><u>Infuse Personalized Style in Windows Email, Calendar</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-establishing-whatsapp-meeting-rooms-efficiently-for-2024/"><u>[New] Establishing WhatsApp Meeting Rooms Efficiently for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-oppo-a78-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-insight-essential-steps-for-gauging-network-bandwidth/"><u>Windows Insight: Essential Steps for Gauging Network Bandwidth</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-mastering-the-art-of-obs-and-fb-live/"><u>[New] In 2024, Mastering the Art of OBS and FB Live</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-for-non-displayed-windows-sign-ins/"><u>Immediate Actions for Non-Displayed Windows Sign-Ins</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-motorola-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Motorola Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://windows11.techidaily.com/matchmaking-the-ideal-nvidia-driver-with-entertainment-goals/"><u>Matchmaking The Ideal Nvidia Driver With Entertainment Goals</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-edges-continuous-desktop-appearance/"><u>Resolving Edges' Continuous Desktop Appearance</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-camera-error-code-0xa00f425d/"><u>Overcoming Windows Camera Error Code: 0XA00F425D</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-power-drain-addressing-vanguard-ums-overuse-on-pcs/"><u>Minimizing Power Drain: Addressing Vanguard UMS Overuse on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-folders-tricks-for-enhanced-efficiency/"><u>Top 5 Windows Folders Tricks for Enhanced Efficiency</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-no-sound-during-system-tests/"><u>Remedy for No Sound During System Tests</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-methods-to-convert-word-documents-to-pdf-on-windows-11/"><u>Cutting-Edge Methods to Convert Word Documents to PDF on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/larger-than-life-boosting-taskbar-icons-in-w11/"><u>Larger-than-Life: Boosting Taskbar Icons in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-for-fixing-inoperative-ccleaner-on-windows-os/"><u>Procedures for Fixing Inoperative CCleaner on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-exit-point-not-found-errors/"><u>Clearing Up Exit Point Not Found Errors</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-guide-to-discord-live-broadcasts/"><u>[New] The Ultimate Guide to Discord Live Broadcasts</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-best-premiere-pro-transition-plugins-expert-picks/"><u>In 2024, Best Premiere Pro Transition Plugins Expert Picks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktok-basics-for-macwindows-computers-explained/"><u>TikTok Basics for Mac/Windows Computers Explained</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-take-your-linkedin-videos-to-the-next-level-custom-thumbnail-tutorial/"><u>New In 2024, Take Your LinkedIn Videos to the Next Level Custom Thumbnail Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-and-folder-integration-in-windows-1011/"><u>Mastering File & Folder Integration in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-window-11-email-app-error-code-0x800713f/"><u>Overcoming Window 11 Email App Error Code 0X800713F</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-the-future-of-game-logging-exciting-alternatives-to-fbx-centric-apps/"><u>[New] In 2024, The Future of Game Logging  Exciting Alternatives to FBX-Centric Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-sweep-away-delayed-input-fasten-your-fingers-for-windows-11/"><u>How to Sweep Away Delayed Input: Fasten Your Fingers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-to-solutions-faster-configuring-shortcuts-for-win-1011-tools/"><u>Navigate to Solutions Faster: Configuring Shortcuts for Win 10/11 Tools</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/become-a-whatsapp-pro-with-these-tricks-and-tips-for-2024/"><u>Become a WhatsApp Pro with These Tricks and Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reinventing-tech-windows-leap-from-version-11/"><u>Reinventing Tech: Windows' Leap From Version 11</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/finding-out-your-internets-public-ip-with-win-cli/"><u>Finding Out Your Internet's Public IP with Win CLI</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-eliminate-startup-disruption-due-to-winscombsvc-errors/"><u>Quick Fix: Eliminate Startup Disruption Due to WinScombSvc Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/from-desktop-to-deep-dive-installing-kali-linux-on-windows/"><u>From Desktop to Deep-Dive: Installing Kali Linux on Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-freeze-entire-browser-display/"><u>2024 Approved  Freeze Entire Browser Display</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-c67-5g-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme C67 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-11s-compatibility-diagnostic-tool/"><u>Decoding Windows 11'S Compatibility Diagnostic Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-challenge-0x80072af9-errors/"><u>Conquering the Challenge: 0X80072AF9 Errors</u></a></li>
</ul></div>
