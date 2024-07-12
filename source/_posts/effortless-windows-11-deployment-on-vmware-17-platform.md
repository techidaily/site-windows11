---
title: Effortless Windows 11 Deployment on VMWare 17 Platform
date: 2024-07-11T21:17:57.079Z
updated: 2024-07-12T21:17:57.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Windows 11 Deployment on VMWare 17 Platform
excerpt: This Article Describes Effortless Windows 11 Deployment on VMWare 17 Platform
keywords: Easy Win11 Install,VMware Win11 Setup,Smooth Win11 Virtual,Simple Win11 Virtualization,Quick Win11 Deployment,Hassle-Free Win11 on VMWare,Simplified Win11 Virtualize
thumbnail: https://thmb.techidaily.com/7839baf4c4540572c890f045a91dd3063abe0e7730f720ac972d7ab64101094f.jpg
---

## Effortless Windows 11 Deployment on VMWare 17 Platform

 Have you ever tried installing Windows 11 on VMware Workstation Player? It is not as easy as you expect from a Windows OS installation. Microsoft imposed the TPM requirement and secure boot for installing Windows 11\. Fortunately, Oracle introduced TPM virtualization in October 2022 and VMware also caught up sometime later.

 As such, you don’t have to rely on registry hacks to disable the TPM and secure boot requirements while installing Windows 11\. This post will guide you to create a virtual machine and install Windows 11 on it.

## The Prerequisites for Installing Windows 11 on VMware

 Here’s what you will need to install Windows 11 with TPM support in VMware Workstation 17 Player:

1. A Windows 11 ISO image file. Check our detailed guide on [how to download the Windows 11 ISO file](https://www.makeuseof.com/windows-iso-direct-download/) .
2. A Windows 10 or above operating system with TPM 2.0 and virtualization support.
3. The latest version of VMware Workstation 17 Player must be pre-installed on the host system.
4. Adequate computing resources to run Windows 11 as a virtual machine. The list includes 64 GB disk space, 4 GB RAM, and a dual-core x64 processor.

 Once you have the necessary ISO file and the latest copy of VMware on your system, you can proceed to the virtual machine creation and Windows 11 installation.

## How to Install Windows 11 in VMware Workstation 17 Player

 Firstly, we will create a virtual machine in VMware for Windows 11\. Then, we will install Windows 11 on the virtual machine. Lastly, we will install VMware tools to finish setting up the virtual machine.

### 1\. Create a Windows 11 Virtual Machine

 Here’s how to create a virtual machine for Windows 11 in VMware:

1. Launch VMware Player on your system. On the home page, click on**Create a new virtual machine** option.
2. Select the**I will install the operating system later** radio button and click on the**Next** button.  
![Creating a Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/creating-a-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. Keep the**Guest Operating System** option as**Windows** and then click on the drop-down menu. Pick the**Windows 11 x64** option and click on the**Next** button.
4. Enter an appropriate name for the new Windows 11 virtual machine. Then, click on the**Browse** button to pick a location on the disk drive for virtual disk creation. Click on**Next** .
5. On the Encryption information page, Choose the encryption type as**Only the files needed to support a TPM are encrypted** .  
![Enabling Encryption in Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabling-encryption-in-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
6. You need to create an 8-character password to encrypt the virtual machine. Keep the **Remember the password on this machine in Credential Manager** checkbox enabled. Click on the**Next** button to continue.
7. Now, specify the disk capacity and set the maximum disk size to**64 GB** . Increase the space if you want to install multiple programs in the virtual machine.
8. Select the**Split virtual disk into multiple files** option and click on**Next** .  
![Adjusting Disk Capacity of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/adjusting-disk-capacity-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

 VMware will display a summary of all the settings you picked for the Windows 11 virtual machine. But there’s one thing still missing: you haven’t customized the hardware preferences or added the Windows 11 ISO file to the virtual machine.

![Configuring resources of Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configuring-resources-of-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)

1. Click on the**Customize Hardware** button. Under the memory tab, increase the**RAM** allocation to**6 GB** or more to avoid a sluggish Windows 11 experience.
2. Switch to the**Processors** tab and allocate**4 or more cores** to the Windows virtual machine.
3. Next, move to the**New CD/DVD (SATA)** tab, and click on the**Use ISO image file** option located under the**Connection** section.
4. Click on the**Browse** button and select the Windows 11 ISO image file you previously downloaded. Click on the**Open** button.
5. Now, close the Hardware window and click on the**Finish** button to create the new virtual machine.

### 2\. Install Windows 11 on the Virtual Machine

 Repeat the following steps to install Windows 11 on the newly created virtual machine:

1. Navigate to the left-hand side menu and select the Windows 11 virtual machine. Click on the**Play virtual machine** option.
2. Press any keyboard key to boot from the ISO file. Pick the appropriate language and region and click on the**Next** button. Then, click on the**Install now** button.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
3. In the Windows setup window, click on the**I don’t have a product key** option.
4. Pick the Windows 11 version (Home, Pro, or Education) and click on the**Next** button.
5. Accept the**End User License Agreement** and select the**Custom** installation option.

1. Click on the**Next** button. Setup will begin the Windows 11 installation. The virtual machine will restart a few times.  
![Installing Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
2. After the machine boots up, select the correct region and click on the**Yes** button. Pick the appropriate keyboard layout.
3. Windows 11 will force you to add a Microsoft account. To avoid this, press**Shift + F10** , type the**oobe\\bypassnro** command, and press the**Enter** key.
4. The virtual machine will restart. Click on the**I don’t have internet** option.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player.jpg)
5. Enter a**name** for your Windows PC and assign a**password** . Pick**three security questions** and proceed.  
![Setting Up Windows 11 Virtual Machine In VMware Workstation 17 Player 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/setting-up-windows-11-virtual-machine-in-vmware-workstation-17-player-2.jpg)
6. **Uncheck** all the tracking options on the Privacy settings page and click on the**Accept** button.
7. Wait for the setup to finalize changes and boot to the desktop.

### 3\. Install the VMware Tools

 The Windows 11 virtual machine is up and running in VMware. But it appears cropped and very small. Many useful features won’t activate until you install VMware tools in the Windows 11 virtual machine. Repeat the following steps:

1. Go to the top menu of VMware Player and click on the**Player** button.
2. Select the**Manage** option from the drop-down menu and click on the**Install VMware tools** option. It will mount the VMware tools setup image file in Windows File Explorer.  
![Installing VMware Tools](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools.jpg)
3. Press**Win + E** to [launch the File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and open the mounted ISO file drive.
4. Locate and select the**setup64.exe** file. Press**Ctrl + Shift + Enter** to launch the setup with admin privileges.
5. In the VMware tools installation window, click on the**Next** button and select the**Complete** installation option.  
![Installing VMware Tools 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/installing-vmware-tools-2.jpg)
6. Then click on the**Install** button. After the installation completes, click on the**Finish** button.
7. Lastly, click on the**Yes** button to restart the virtual machine to apply changes.  
![Windows 11 VM in VMware Workstation 17 Player](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-vm-in-vmware-workstation-17-player.jpg)

 The Windows 11 virtual machine is ready to use. You can even run Windows features like Hyper V and Windows MDAG and Sandbox inside this machine.

## Run Windows 11 on VMware Without Any Registry Hacks

 With TMP emulation, there is no need for registry tweaking to disable secure boot and TPM requirements on Windows 11\. All the features work fine, and you don’t need to switch to another hypervisor program. However, Oracle VirtualBox offers the same TPM virtualization and secure boot features.


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
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-the-art-of-speed-learn-to-create-time-lapse-videos-in-minutes-2-methods/"><u>New In 2024, The Art of Speed Learn to Create Time Lapse Videos in Minutes 2 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-credentials-error-loop/"><u>Overcoming Windows Credentials Error Loop</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-enable-or-disable-windows-build-service/"><u>Procedures to Enable or Disable Windows Build Service</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-7-best-green-screen-software-for-beginners-on-mac/"><u>In 2024, 7 Best Green Screen Software for Beginners on Mac</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-rearranged-characters-in-windows-os/"><u>Solutions for Rearranged Characters in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-unsupported-audio-device-windowss/"><u>Remedy for Unsupported Audio Device Windowss</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-actions-to-mend-post-windows-update-issues/"><u>Immediate Actions to Mend Post-Windows Update Issues</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-free-srt-translator-showdown-the-best-eight-in-ranking/"><u>In 2024, Free SRT Translator Showdown  The Best Eight in Ranking</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-reminders-in-every-window-of-your-pc/"><u>Efficient Reminders in Every Window of Your PC</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-re-establish-audible-vids-on-social-sound/"><u>[New] 2024 Approved  Re-Establish Audible Vids on Social Sound</u></a></li>
<li><a href="https://windows11.techidaily.com/freeze-yourself-no-more-9-techniques-for-easing-windows-install-locks/"><u>Freeze Yourself No More: 9 Techniques for Easing Windows Install Locks</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/evaluating-sns-hdrs-value-and-alternatives-for-hdr-editing/"><u>Evaluating SNS HDR's Value & Alternatives for HDR Editing</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-orchestrate-audio-amidst-slides/"><u>In 2024, Orchestrate Audio Amidst Slides</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-store-and-view-onedrive-data-locally/"><u>Securely Store and View OneDrive Data Locally</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-change-default-image-savings-in-os-x/"><u>[Updated] Change Default Image Savings in OS X</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unable-to-open-shares-on-windows-1011s-geforce/"><u>Fixing Unable to Open Shares on Windows 10/11'S GeForce</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-windows-11-theme-treasures-revealed/"><u>Hidden Windows 11 Theme Treasures Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/interpreting-launch-identifiers-for-applications/"><u>Interpreting Launch Identifiers for Applications</u></a></li>
<li><a href="https://extra-tips.techidaily.com/androids-best-in-sky-file-sanctuaries-for-2024/"><u>Android's Best In-Sky File Sanctuaries for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-driver-verifier-in-win11-os/"><u>Launching the Driver Verifier in Win11 OS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/voice-log-export-and-critique-for-2024/"><u>Voice Log Export & Critique for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/did-rav-antivirus-suddenly-appear-on-your-windows-pc-heres-where-it-came-from-and-how-to-uninstall-it/"><u>Did RAV Antivirus Suddenly Appear on Your Windows PC? Here's Where It Came From & How to Uninstall It</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-top-10-affordable-filmmaking-tools-for-indie-creators/"><u>Updated In 2024, Top 10 Affordable Filmmaking Tools for Indie Creators</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-pocketcapture-app-testimonials-and-insights/"><u>In 2024, PocketCapture App Testimonials & Insights</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-ultimate-podcast-recording-playbook-a-seamless-process-for-2024/"><u>Updated The Ultimate Podcast Recording Playbook A Seamless Process for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-connecting-twitter-videos-with-facebook-friends/"><u>[Updated] In 2024, Connecting Twitter Videos with Facebook Friends</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-directx-download-problems-in-os/"><u>Remedying DirectX Download Problems in OS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-harmonious-social-media-incorporating-soundtracks-into-fb-videos/"><u>[Updated] In 2024, Harmonious Social Media  Incorporating Soundtracks Into FB Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-unreal-device-issue-in-win-11/"><u>How to Resolve Unreal Device Issue in Win 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-achieving-youtube-mastery-with-effective-use-of-creator-studio-tools/"><u>[New] In 2024, Achieving YouTube Mastery with Effective Use of Creator Studio Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-legitimate-and-false-positive-login-attempts-on-pcs/"><u>Identifying Legitimate and False-Positive Login Attempts on PCs</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-in-2024-what-is-ai-advertising/"><u>New In 2024, What Is AI Advertising?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-the-filmmakers-handbook-to-superior-voice-overseeing/"><u>In 2024, The Filmmaker's Handbook to Superior Voice Overseeing</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/2024-approved-exhaustive-register-of-podcast-discovery-systems/"><u>2024 Approved Exhaustive Register of Podcast Discovery Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-docx-to-pdf-migration-for-windows-users/"><u>Step-by-Step DOCX to PDF Migration for Windows Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-ultimate-path-for-influencers-in-advertising-and-sponsorships/"><u>[Updated] The Ultimate Path for Influencers in Advertising & Sponsorships</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-internet-options-tweaks-for-windows-11/"><u>Mastery of Internet Options Tweaks for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-for-wordpad-operability/"><u>Exploring Windows for WordPad Operability</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ipad-image-import-issues-in-windows-1111-pro/"><u>Solving iPad Image Import Issues in Windows 11/11 Pro</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-enhance-your-fb-with-iphonesandroids-favorite-tunes/"><u>[Updated] Enhance Your FB with iPhones/Androids' Favorite Tunes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-lock-apps-on-xiaomi-14-ultra-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Xiaomi 14 Ultra to Protect Your Individual Information</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-final-cut-pro-tutorial-reversing-video-clips-made-easy/"><u>Updated In 2024, Final Cut Pro Tutorial Reversing Video Clips Made Easy</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reveal-hidden-sd-card-in-file-explorer/"><u>How to Reveal Hidden SD Card in File Explorer?</u></a></li>
<li><a href="https://network-issues.techidaily.com/swiftly-update-intel-graphics-3000-for-windows-11/"><u>Swiftly Update Intel Graphics 3000 for Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-enhancing-twitter-video-experience-to-fhd/"><u>[Updated] Enhancing Twitter Video Experience to FHD</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-10-essential-methods-to-record-virtual-seminars-at-no-expense/"><u>[New] 10 Essential Methods to Record Virtual Seminars at No Expense</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-youtube-studio-editing-handbook/"><u>2024 Approved  The Ultimate YouTube Studio Editing Handbook</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-and-forge-a-friendly-startup-in-windows-amidst-errors/"><u>Fix and Forge a Friendly Startup in Windows Amidst Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-navigating-aspers-methodology-for-sleep-success/"><u>2024 Approved  Navigating Asper's Methodology for Sleep Success</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-framefinder-top-picks-for-screen-capturing/"><u>[New] In 2024, FrameFinder  Top Picks for Screen Capturing</u></a></li>
<li><a href="https://windows11.techidaily.com/quiet-windows-11-feedback-and-hints/"><u>Quiet Windows 11 Feedback and Hints</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-effortless-techniques-to-craft-professional-time-lapses-on-galaxy/"><u>[New] 2024 Approved  Effortless Techniques to Craft Professional Time-Lapses on Galaxy</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-sound-quality-top-5-free-windows-tools/"><u>Improve Sound Quality: Top 5 Free Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-reestablishing-connection-with-steams-game-servers/"><u>Guidelines for Reestablishing Connection with Steam's Game Servers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-ordinary-snaps-to-captivating-creations-editing-on-snapchat-for-2024/"><u>[Updated] From Ordinary Snaps to Captivating Creations  Editing on Snapchat for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-errors-during-amd-195-installation/"><u>Eliminating Windows Errors During AMD 195 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steam-login-errors-on-windows-via-rust-coding/"><u>Eliminating Steam Login Errors on Windows via Rust Coding</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/seamless-acquisition-of-everyday-online-footage-fb-status-videos/"><u>Seamless Acquisition of Everyday Online Footage  FB Status Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-thx-not-working-in-windows-setup/"><u>Rectifying THX Not Working in Windows Setup</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-list-of-5-youtube-competitor-editors/"><u>In 2024, The Ultimate List of 5 YouTube Competitor Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-tips-install-outlook-preview-in-w10w11/"><u>Easy Tips: Install Outlook Preview in W10/W11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-steady-footing-top-free-video-stabilizers-for-windows-and-mac/"><u>New Steady Footing Top Free Video Stabilizers for Windows and Mac</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-how-to-make-pinterest-slideshow-in-simple-ways/"><u>New 2024 Approved How To Make Pinterest Slideshow in Simple Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
</ul></div>
