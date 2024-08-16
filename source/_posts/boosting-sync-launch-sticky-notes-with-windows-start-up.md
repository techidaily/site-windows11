---
title: "Boosting Sync: Launch Sticky Notes with Windows Start-Up"
date: 2024-08-15T15:13:57.615Z
updated: 2024-08-16T15:13:57.615Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Sync: Launch Sticky Notes with Windows Start-Up"
excerpt: "This Article Describes Boosting Sync: Launch Sticky Notes with Windows Start-Up"
keywords: Sync Windows Start-Up,Sticky Notes Launch,Boost Startup Speed,Sync Windows Apps,Quick Start Windows,Notebook Launch Tool,Fast System Boot
thumbnail: https://thmb.techidaily.com/468b7a50fb837089e10cec38dd44fa01aaab4078b704b313fd2f69558ac117bb.png
---

## Boosting Sync: Launch Sticky Notes with Windows Start-Up

 Are you tired of opening Sticky Notes every time you turn on your computer? What if it could open automatically each time Windows starts?

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.

## 1\. Keep Sticky Notes Open at Shutdown

 When you're done working with Sticky Notes, make sure not to close the window. Instead, leave it open as you shut down your computer. This will ensure that when you turn on your computer, Sticky Notes opens automatically.

 Although the solution is simple, it may not work, or you may find it difficult to remember to keep it open when you turn off your PC. In that case, there are other alternatives; add Sticky Notes to the startup folder or use Task Scheduler.

## 2\. Add Sticky Notes to the Startup Folder

 If you don't want to keep Sticky Notes open at shutdown, you can add it to the startup folder. The Startup folder is a special directory in File Explorer. It stores applications that launch automatically when Windows starts.

 To add Sticky Notes to the Startup folder, follow these steps.

1. Press **Win + R** and type **shell:startup** in the Run dialog.
2. Click **OK** or press Enter. This opens a folder containing all the applications that launch at startup.
3. Press **Windows** to open the Start menu, then click **All apps**. Now scroll down and find **Sticky Notes** in the list.
4. Drag and drop **Sticky Notes** into the Startup folder.

 After performing these steps, close File Explorer and restart your computer. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use the Task Scheduler

 Task Scheduler is another way to open Sticky Notes at startup. This Windows feature schedules and automates tasks at specific times or conditions.

 To add Sticky Notes using this tool, follow these steps:

1. [Open Task Scheduler](https://www.makeuseof.com/windows-11-open-task-scheduler/).
2. Click **Create Basic Task** from the **Actions** panel on the right. This opens a wizard that guides you through the setup.  
![Create Basic Task in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-in-task-scheduler.jpg)
3. In the first step, give your task a name and click **Next**.  
![Startup Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-sticky-notes.jpg)
4. Now select **When I log on** as the trigger and click **Next** at the bottom.  
![Create Basic Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-basic-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
5. Choose **Start a program** in the Action window and click **Next**.  
![Start a program in Action tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-action-tab.jpg)
6. In the **Program/script** field, type the path below:  
C:\Windows\System32\cmd.exe
7. In the Add arguments (optional) field, copy and paste the following command:  
/c start shell:appsfolder\Microsoft.MicrosoftStickyNotes_8wekyb3d8bbwe!App  
![Start a Program in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-a-program-in-task-scheduler.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
8. Click **Next** and review all the settings.
9. Now click **Finish** to save your work.  
![Finish Task Wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/finish-task-wizard.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Task Scheduler will now run Sticky Notes each time you log in. This way, Sticky Notes launches automatically at startup.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Tweak the Registry Editor

 If you're comfortable editing the Windows registry, you can tweak it to open Sticky Notes at startup. This method requires knowledge of how the Registry Editor works and caution when editing it. If done incorrectly, it can cause serious system errors. It's best to [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing anything.

 To open Sticky Notes at startup using the Registry Editor, follow these steps:

1. [Open Windows Search](https://www.makeuseof.com/windows-search-use-guide/).
2. Type **regedit** in the search bar and click on the Registry Editor option.
3. If the UAC dialog appears, click **Yes** to grant access.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\PenWorkspace\Notes
5. Double-click the **LaunchOnNextUserSession** key on the right.  
![Tweak Registry Editor to Open Sticky Notes at Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tweak-registry-editor-to-open-sticky-notes-at-startup.jpg)
6. Change the Value data from 0 to **1** in the Edit DWORD (32-bit) Value window and click **OK**.  
 If you can't find the **LaunchOnNextUserSession** key, right-click on the **Notes** folder and select **New > DWORD (32-bit) Value**. Name the newly created key “LaunchOnNextUserSession” and assign it the Value data of **1**.
7. Close the Registry Editor and restart your computer to save the changes. Sticky Notes should now open at startup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Windows Now Starts With Sticky Notes Open

 This article outlines several ways to open Sticky Notes at startup in Windows. If you want an easier solution, leave Sticky Notes open when you shut down your computer; it will launch automatically when Windows starts. If not, add Sticky Notes to the startup folder. If you want more control over when Sticky Notes launches, use Task Scheduler or tweak the Registry Editor.

 Well, there's good news for you: Sticky Notes can launch at startup in Windows. This article illustrates how to set up and use Sticky Notes at startup.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-building-a-broad-spectrum-audience-with-multichannel-strategy/"><u>[New] 2024 Approved  Building a Broad-Spectrum Audience with Multichannel Strategy</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-cosmetics-confidentials-building-a-beauty-channel-on-youtube/"><u>[New] 2024 Approved  Cosmetics Confidentials  Building a Beauty Channel on YouTube</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-the-ultimate-blueprint-to-rip-and-burn-cds-with-windows-media-player/"><u>[New] 2024 Approved  The Ultimate Blueprint to Rip & Burn Cds with Windows Media Player</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-comprehensive-guide-to-enhancing-tiktoks-adding-texts-professionally/"><u>[New] In 2024, Comprehensive Guide to Enhancing TikToks  Adding Texts Professionally</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-discover-the-best-11-no-fee-name-crafting-for-channels/"><u>[New] In 2024, Discover the Best 11 No-Fee Name Crafting for Channels</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-screen-recorder-showdown-top-choices-explored/"><u>[New] In 2024, Screen Recorder Showdown  Top Choices Explored</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-2023s-most-captivating-channel-the-ultimate-story-showcase/"><u>[Updated] 2023'S Most Captivating Channel  The Ultimate Story Showcase</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-a-step-by-step-roadmap-for-lasting-tiktok-account-loss-for-2024/"><u>[Updated] A Step-by-Step Roadmap for Lasting TikTok Account Loss for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-ensuring-every-snapchatter-friendly-footage-via-mac/"><u>[Updated] Ensuring Every Snapchatter-Friendly Footage via Mac</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-fidelity-windows-playlists/"><u>[Updated] High-Fidelity Windows Playlists</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-7-comedy-youtube-video-ideas-that-funny-people-can-try/"><u>[Updated] In 2024, 7 Comedy YouTube Video Ideas That Funny People Can Try</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-share-a-world-view-iphone-360-film-techniques/"><u>[Updated] In 2024, Share a World View  IPhone 360 Film Techniques</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-maximize-moments-with-engaging-tasks-while-embracing-your-favorite-talk-shows/"><u>[Updated] Maximize Moments with Engaging Tasks While Embracing Your Favorite Talk Shows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-playback-of-srt-audio-files-in-computers-windowsmacos/"><u>[Updated] Playback of SRT Audio Files in Computers (Windows/macOS)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2023-play-facebook-videos-on-tv/"><u>2023 | Play Facebook Videos on TV?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-advancements-in-quantum-hdr-technology-explained/"><u>2024 Approved  Advancements in Quantum HDR Technology Explained</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-routes-to-collecting-visual-content/"><u>2024 Approved  Best Routes to Collecting Visual Content</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-motorola-moto-g-stylus-5g-2023-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Motorola Moto G Stylus 5G (2023) Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effortless-downloading-of-your-elgato-driver-tools/"><u>Effortless Downloading of Your Elgato Driver Tools</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/expert-advice-yt-clip-sharing-using-your-google-id/"><u>Expert Advice  YT Clip Sharing Using Your Google ID</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-not-reset-issue-in-win-11/"><u>Fixing 'Device Not Reset' Issue in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-store-failure-codes/"><u>Fixing Windows Store Failure Codes</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-self-clearing-windows-recycle-bin/"><u>Guide to Self-Clearing Windows Recycle Bin</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-to-correct-err-87-on-windows-loadlib/"><u>Guidelines to Correct Err 87 on Windows LoadLib</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-no-supported-devices-problem-in-windows-update/"><u>Handling 'No Supported Devices' Problem in Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-full-potential-of-windows-11-task-manager-filters-and-themes-at-your-fingertips/"><u>Harness Full Potential of Windows 11 Task Manager: Filters & Themes at Your Fingertips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-microsoft-store-error-0x80073d26-in-windows-10-and-11/"><u>How to Fix the Microsoft Store Error 0X80073D26 in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-halt-windows-desktop-keys-effectively/"><u>How to Halt Windows Desktop Keys Effectively</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-xiaomi-redmi-note-13-proplus-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Xiaomi Redmi Note 13 Pro+ 5G Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-repair-unable-to-fetch-error-in-nvidia-geforce-experience/"><u>How To Repair 'Unable To Fetch' Error in NVIDIA GeForce Experience</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-huawei-p60-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Huawei P60 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-realme-12-5g-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Realme 12 5G Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-intervention-for-directdraw-fails-in-windows-1011/"><u>Immediate Intervention for DirectDraw Fails in Windows 10/11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-idea-to-hit-solo-podcast-production-tactics/"><u>In 2024, From Idea to Hit  Solo Podcast Production Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-windows-11-app-launch-strategies/"><u>Masterful Windows 11 App Launch Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-development-navigating-dev-drive-in-windows-11/"><u>Mastering Development: Navigating Dev Drive in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-english-spelling-the-top-100-mistakes-to-avoid/"><u>Mastering English Spelling: The Top 100 Mistakes to Avoid</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-repairing-windows-email-failures-error-code-0x800713f/"><u>Mastering the Art of Repairing Windows' Email Failures (Error Code 0X800713F)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-task-scheduler-for-file-batch-execution/"><u>Mastering Windows Task Scheduler for File Batch Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-two-users-shared-ms-login-fails/"><u>Navigating Through Two Users' Shared MS Login Fails</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-command-execution-setting-terminal-preference/"><u>Optimize Command Execution: Setting Terminal Preference</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-connectivity-issues-via-winvpn/"><u>Overcoming Windows Connectivity Issues via WinVPN</u></a></li>
<li><a href="https://review-topics.techidaily.com/poco-m6-pro-5g-messages-recovery-recover-deleted-messages-from-poco-m6-pro-5g-by-fonelab-android-recover-messages/"><u>Poco M6 Pro 5G Messages Recovery - Recover Deleted Messages from Poco M6 Pro 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-tactics-for-heic-to-jpeg-conversion-process-on-windows-11-systems/"><u>Proven Tactics for Heic to JPEG Conversion Process on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-phones-role-in-windows-11-networking/"><u>Redefining Phones' Role in Windows 11 Networking</u></a></li>
<li><a href="https://windows11.techidaily.com/reinvigorate-discolored-volume-settings-in-win/"><u>Reinvigorate Discolored Volume Settings in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-win11-drive-non-destructive-freeing-methods-max-156-chars/"><u>Rejuvenating Win11 Drive: Non-Destructive Freeing Methods (Max 156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguarding-your-os-managing-usb-device-use/"><u>Safeguarding Your OS: Managing USB Device Use</u></a></li>
<li><a href="https://windows11.techidaily.com/secrecy-startup-the-invisible-power-button-guide/"><u>Secrecy Startup: The Invisible Power Button Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-a-static-backdrop-on-modern-windows-11-pcs/"><u>Secure a Static Backdrop on Modern Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/slash-wms-high-graphics-consumption-for-efficient-windows-11/"><u>Slash WM's High Graphics Consumption for Efficient Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-common-disk-errors-on-windows-devices/"><u>Solutions for Common Disk Errors on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-users-clear-of-disconnection-hurdles-from-nvidia/"><u>Steering Users Clear of Disconnection Hurdles From Nvidia</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-entering-windows-11-home-settings/"><u>Step-by-Step: Entering Windows 11 Home Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-prevent-overheating-in-w11-pcs/"><u>Techniques to Prevent Overheating in W11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-rotation-rulebook-six-secrets-to-snap-spins-in-windows-11/"><u>The Rotation Rulebook: Six Secrets to Snap-Spins in Windows 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/tricks-for-reducing-resonance-in-sound-files-step-by-step-approach/"><u>Tricks for Reducing Resonance in Sound Files Step-by-Step Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-steam-downloads-overcoming-frustrating-speed-halts/"><u>Turbo Steam Downloads: Overcoming Frustrating Speed Halts</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-and-correcting-cant-access-mail-errors-in-windows-11-mail-app/"><u>Uncovering and Correcting Can't Access Mail Errors in Windows 11 Mail App</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-transition-phasing-out-old-traits/"><u>Windows Transition: Phasing Out Old Traits</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-windows-timers-for-efficient-pomodoros/"><u>Winning Windows Timers for Efficient Pomodoros</u></a></li>
</ul></div>
