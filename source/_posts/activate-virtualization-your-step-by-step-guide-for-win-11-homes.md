---
title: "Activate Virtualization: Your Step by Step Guide for Win 11 Homes"
date: 2024-07-11T21:54:47.797Z
updated: 2024-07-12T21:54:47.797Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Activate Virtualization: Your Step by Step Guide for Win 11 Homes"
excerpt: "This Article Describes Activate Virtualization: Your Step by Step Guide for Win 11 Homes"
keywords: Win 11 Virtualize,Virtual Windows 11,Activate Win 11 Virt,Home Win 11 Virtual,Step Win 11 Guide,Virtualization Homes,Virt Guide for Win 11
thumbnail: https://thmb.techidaily.com/3153de74f0140829de221d87f3024edf0be402597c10c002cec7499f13b2deb2.jpg
---

## Activate Virtualization: Your Step by Step Guide for Win 11 Homes

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-convert-fb-video-to-downloadable-mp3/"><u>2024 Approved  Convert FB Video to Downloadable MP3</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-change-from-mkv-to-mp4-format-with-windows-tools/"><u>Easy Change From MKV to MP4 Format with Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-windows-11-selection-home-edition-or-pro-level-choice/"><u>Tailored Windows 11 Selection: Home Edition or Pro-Level Choice</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-s23plus-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Samsung Galaxy S23+ Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rapid-responsiveness-in-anthem-play/"><u>Rapid Responsiveness in Anthem Play</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-conquer-common-errors-during-windows-11-rollout/"><u>How to Conquer Common Errors During Windows 11 Rollout</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-a-comprehensive-analysis-of-how-to-speed-up-audio-files-on-spotify-safely-for-2024/"><u>[Updated] A Comprehensive Analysis of How to Speed Up Audio Files on Spotify Safely for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-odins-vengeance-realm-awakens/"><u>[Updated] 2024 Approved  Odin’s Vengeance  Realm Awakens</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-workflow-integration-adding-shortcuts-to-the-wordpad-menu-of-windows-11/"><u>Improving Workflow Integration: Adding Shortcuts to the WordPad Menu of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essence-of-personalization-through-ai-at-ms-store/"><u>The Essence of Personalization Through AI at MS Store</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-mastering-minecraft-screen-capture-a-mac-guide/"><u>[New] 2024 Approved  Mastering Minecraft Screen Capture  A Mac Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-registry-edits-in-cmd/"><u>Unveiling the Secrets of Registry Edits in CMD</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-your-contacts-delete-email-post-login-in-windows/"><u>Hide Your Contacts: Delete Email Post Login in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-9-compelling-arguments-for-pc-dominance-over-macs/"><u>Demystifying: 9 Compelling Arguments for PC Dominance over Macs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-0x80070194-winos-onedrive-fixes/"><u>Tackling the 0X80070194: WinOS OneDrive Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-deadly-windows-1011-error-0x8007045d/"><u>Bypassing Deadly Windows 10/11 Error 0X8007045D</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-black-windows-back-with-simple-steps/"><u>Turn Black Windows Back with Simple Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-pinpointing-device-serial-numbers-on-windows/"><u>The Ultimate Guide to Pinpointing Device Serial Numbers on Windows</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-cutting-edge-solution-apple-watch-for-mac-access-for-2024/"><u>[New] Cutting-Edge Solution  Apple Watch for Mac Access for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-boosting-audience-size-a-comprehensive-guide-to-youtube-shorts-success/"><u>[Updated] Boosting Audience Size  A Comprehensive Guide to YouTube Shorts Success</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-from-tiktok-kitchens-15-irresistible-culinary-challenges/"><u>[New] From TikTok Kitchens  15 Irresistible Culinary Challenges</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-step-by-step-blueprint-for-impressive-photographic-mosaics/"><u>In 2024, Step-by-Step Blueprint for Impressive Photographic Mosaics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-in-class-slideshow-maker-xi-to-x-series-iphones/"><u>Best-in-Class Slideshow Maker  XI to X Series iPhones</u></a></li>
<li><a href="https://fox-info.techidaily.com/perfecting-tiktok-videos-efficient-techniques-for-numerical-edits-for-2024/"><u>Perfecting TikTok Videos  Efficient Techniques for Numerical Edits for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-premium-online-audio-solutions-guide/"><u>[New] Premium Online Audio Solutions Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-media-maker-error-x8007043c-fix-guide/"><u>Windows' Media Maker Error X.8007043C Fix Guide</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-exploring-tiktoks-world-dance-music-and-viral-trends/"><u>[Updated] 2024 Approved  Exploring TikTok's World  Dance, Music & Viral Trends</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-loadlibrary-error-87-misconfiguration/"><u>Eliminate LoadLibrary Error 87 Misconfiguration</u></a></li>
<li><a href="https://windows11.techidaily.com/top-solutions-for-windows-pin-access-issues-10plus11/"><u>Top Solutions for Windows PIN Access Issues (10+11)</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-a-beginners-checklist-for-learning-m4r-conversion/"><u>New In 2024, A Beginners Checklist for Learning M4R Conversion</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-easy-guide-how-to-make-talking-head-videos/"><u>2024 Approved Easy Guide How To Make Talking Head Videos</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-oppo-reno-11-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Oppo Reno 11 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-debugs-top-windows-troubleshooting-apps/"><u>Deciphering Debugs: Top Windows Troubleshooting Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-onedrive-errors-on-windows-11-an-experts-fix-list/"><u>Navigating OneDrive Errors on Windows 11: An Expert's Fix List</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-itel-p40plus-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Itel P40+ Without PUK Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-starting-windows-speech-to-text-feature/"><u>Fixing Non-Starting Windows Speech to Text Feature</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-step-in-making-the-most-of-snap-camera-in-microsoft-teams/"><u>[Updated] Step-In  Making the Most of Snap Camera in Microsoft Teams</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-break-through-boundaries-15plus-best-free-video-starters/"><u>[Updated] In 2024, Break Through Boundaries  15+ Best Free Video Starters</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-fixing-0x80071a90-windows-error/"><u>Essential Guide to Fixing 0X80071A90 Windows Error</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-missing-initialization-message-on-windows-pc/"><u>Fixing 'Missing Initialization' Message on Windows PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-essentials-of-blurring-photo-borders/"><u>[New] The Essentials of Blurring Photo Borders</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-steam-data-flow-stopping-frustrating-speed-drops/"><u>Enhance Steam Data Flow: Stopping Frustrating Speed Drops</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-final-step-delete-your-youtube-shorts-link/"><u>[Updated] In 2024, The Final Step  Delete Your YouTube Shorts Link</u></a></li>
<li><a href="https://windows11.techidaily.com/deactivating-file-read-only-mode-in-windows/"><u>Deactivating File Read-Only Mode in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-best-online-gif-to-image-pngjpg-converter/"><u>Updated 2024 Approved Best Online GIF to Image (PNG/JPG) Converter</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-fix-for-0x80072af9-in-windows-os/"><u>Immediate Fix for 0X80072AF9 in Windows OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-itel-p40-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Itel P40 Safely | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-windows-11-prime-fps-monitors-and-trackers/"><u>Top 6 Windows 11: Prime FPS Monitors & Trackers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-the-nuances-of-premieres-fullscreen-mode/"><u>[New] Navigating the Nuances of Premiere's Fullscreen Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-pc-performance-tests/"><u>Optimal PC Performance Tests</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-the-seamless-audio-journey-crafting-subtle-volume-transitions-in-adobe-after-effects/"><u>2024 Approved The Seamless Audio Journey Crafting Subtle Volume Transitions in Adobe After Effects</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-fix-error-code-0xc0000001-on-windows-pcs/"><u>Easy Steps To Fix Error Code 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11-entry-into-the-insider-trials/"><u>Unveiling Windows 11: Entry Into the Insider Trials</u></a></li>
<li><a href="https://windows11.techidaily.com/managing-wlanextexe-to-keep-cpu-cool/"><u>Managing Wlanext.EXE to Keep CPU Cool</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-around-scheduler-setbacks-with-ease/"><u>Turn Around Scheduler Setbacks with Ease</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-pc-safety-introducing-your-unique-window-pin-design/"><u>Elevate PC Safety: Introducing Your Unique Window Pin Design</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-overlapping-security-measures-stick-to-one-windows-antivirus/"><u>Avoid Overlapping Security Measures: Stick to One Windows Antivirus</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-transform-your-mac-interface-with-speech-recognition-software-review/"><u>In 2024, Transform Your Mac Interface with Speech Recognition Software Review</u></a></li>
<li><a href="https://windows11.techidaily.com/legacy-unlocks-employing-a-windows-7-key-in-11-setup/"><u>Legacy Unlocks: Employing a Windows 7 Key in 11 Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-subsystem-best-practices-for-wsl-2-users/"><u>Optimizing Subsystem: Best Practices for WSL 2 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-resetting-rituals-the-ultimate-8/"><u>Windows Resetting Rituals: The Ultimate 8</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-office-activation-woes/"><u>Unlocking Windows Office Activation Woes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/personalizing-every-aspect-of-your-discord-image/"><u>Personalizing Every Aspect of Your Discord Image</u></a></li>
<li><a href="https://windows11.techidaily.com/illuminate-with-joy-magical-holiday-window-decor/"><u>Illuminate with Joy: Magical Holiday Window Decor</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-blueprint-strategies-for-authentic-life-enrichment-videos/"><u>[New] In 2024, Blueprint  Strategies for Authentic Life Enrichment Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-the-finest-free-car-performance-fixes/"><u>The Ultimate Guide to the Finest Free Car Performance Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/crafted-alerts-full-charge-on-your-win-pclaptop/"><u>Crafted Alerts: Full Charge on Your WIN PC/Laptop</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-mastering-video-seo-5-steps-to-surge-in-youtube-popularity/"><u>2024 Approved  Mastering Video SEO  5 Steps to Surge in YouTube Popularity</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-battlenet-speed-a-win-pc-strategy-guide/"><u>Boosting Battle.net Speed: A Win-PC Strategy Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-vs-youtube-dissecting-the-streamers-choices-for-2024/"><u>Vimeo vs YouTube  Dissecting the Streamers' Choices for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-revive-missing-social-media-watch-icon/"><u>In 2024, Revive Missing Social Media Watch Icon</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-complete-how-to-tutorials-of-kapwing-collage-maker/"><u>Updated 2024 Approved Complete How-To Tutorials of Kapwing Collage Maker</u></a></li>
</ul></div>
