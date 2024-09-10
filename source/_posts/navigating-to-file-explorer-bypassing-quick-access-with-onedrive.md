---
title: Navigating to File Explorer Bypassing Quick Access with OneDrive
date: 2024-09-09T11:58:15.935Z
updated: 2024-09-10T11:58:15.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating to File Explorer Bypassing Quick Access with OneDrive
excerpt: This Article Describes Navigating to File Explorer Bypassing Quick Access with OneDrive
keywords: Quick Access Bypass,Direct File Explorer,Onedrive Navigation,Fast Explorer Open,Skip Quick Access,OneDrive Explorer,Bypass Quick Access
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Navigating to File Explorer Bypassing Quick Access with OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115940/19272" target="_top" id="2115940">
  <img src="//a.impactradius-go.com/display-ad/19272-2115940" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-enjoy-uninterrupted-viewing-top-20-youtube-download-apps/"><u>[New] 2024 Approved  Enjoy Uninterrupted Viewing  Top 20 YouTube Download Apps</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-transfer-tactics-for-seamless-online-video-sharing/"><u>[New] 2024 Approved  Transfer Tactics for Seamless Online Video Sharing</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-capturing-movement-with-clarity-implementing-motion-blur-on-peoples-photos-with-picsart/"><u>[New] Capturing Movement with Clarity  Implementing Motion Blur on People's Photos with Picsart</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-complete-look-into-razers-streaming-hardware/"><u>[New] In 2024, Complete Look Into Razer's Streaming Hardware</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-visual-virtuosity-mastering-motivation-on-instagram-for-2024/"><u>[New] Visual Virtuosity  Mastering Motivation on Instagram for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-google-meetings-mastered-best-practices-4/"><u>[Updated] In 2024, Google Meetings Mastered  Best Practices #4</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-the-inverted-illusion-guide-transforming-visual-content-through-angled-spins/"><u>[Updated] In 2024, The Inverted Illusion Guide  Transforming Visual Content Through Angled Spins</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-watch-9-free-full-length-christmas-movies-on-youtube/"><u>[Updated] In 2024, Watch 9 Free Full Length Christmas Movies On YouTube</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-captivating-audiences-on-a-shoestring-budget-youtube-shorts-success-tips/"><u>2024 Approved  Captivating Audiences on a Shoestring Budget – YouTube Shorts Success Tips</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-skyline-redefined-q500-typhoon-reviewed/"><u>2024 Approved  Skyline Redefined  Q500 Typhoon Reviewed</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/breakdown-easy-to-follow-steps-to-using-a-whiteboard-on-zoom-devices-for-2024/"><u>Breakdown  Easy-to-Follow Steps to Using a Whiteboard on Zoom Devices for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/convenience-at-your-fingertips-enable-autoplay-of-youtube-videos-on-fb-for-2024/"><u>Convenience at Your Fingertips  Enable Autoplay of YouTube Videos on FB for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-unattainable-package-error-on-windows-10-11/"><u>Fixing the Unattainable Package Error on Windows 10, 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-ios-to-windows-mastering-the-use-of-imessage/"><u>From iOS to Windows: Mastering the Use of iMessage</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-restoring-malwarebytes-database-connection-on-win-oses/"><u>Guide to Restoring Malwarebytes Database Connection on WIN OSes</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-an-unresponsive-aoc-display-on-windows-10-quick-guide/"><u>How to Fix an Unresponsive AOC Display on Windows 10 - Quick Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-iphone-14-pro-max-drfone-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-unable-to-find-the-ubisoft-game-launcher-error/"><u>How to Fix the “Unable to Find the Ubisoft Game Launcher” Error</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-shutdown-box-opening-by-itself-in-windows-11/"><u>How to Fix the Shutdown Box Opening By Itself in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-error-403-in-roblox-windows/"><u>How to Overcome Error 403 in Roblox (Windows)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-honor-100-pro-lock-screen-password-by-drfone-android/"><u>How to Reset your Honor 100 Pro Lock Screen Password</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-play-7t-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Honor Play 7T Phone without Any Data Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-user-specific-windows-11-volume-keys/"><u>Implementing User-Specific Windows 11 Volume Keys</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-lava-yuva-3-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Lava Yuva 3 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-comprehensive-examination-editrite-pro-suite-the-final-word-2023/"><u>In 2024, Comprehensive Examination  EditRite Pro Suite – The Final Word, 2023</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-tecno-pova-6-pro-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Tecno Pova 6 Pro 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-simplified-techniques-for-crafting-captions-on-fb-videos/"><u>In 2024, Simplified Techniques for Crafting Captions on FB Videos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-zte-axon-40-lite-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent ZTE Axon 40 Lite Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-windows-11-desktop-widgets/"><u>Mastering the Use of Windows 11 Desktop Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-microsoft-store-app-not-installed-issue/"><u>Navigating Microsoft Store App Not Installed Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-network-setbacks-in-obs-studio-windows-edition-7-ways/"><u>Navigating Network Setbacks in OBS Studio, Windows Edition (7 Ways)</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-app-guard-for-cammic/"><u>Navigating Windows 11’S App Guard for Cam/Mic</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-nine-spectacular-platforms-for-accessing-copyright-free-funny-audio-for-2024/"><u>New Nine Spectacular Platforms for Accessing Copyright-Free Funny Audio for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-routine-nircmds-win-commands-for-speed/"><u>Optimize Your Routine: NirCmd's Win Commands for Speed</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-cc-woes-a-handy-guide-for-win-10-users/"><u>Overcome CC Woes: A Handy Guide for Win 10 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-deadly-script-error-a-win-11-discord-fix-guide/"><u>Overcoming the Deadly Script Error: A Win 11 Discord Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-the-deadly-windows-error-c0000022-breakdown/"><u>Overcoming the Deadly Window's Error C0000022 Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/painting-a-picture-sketching-on-windows-11-devices/"><u>Painting a Picture: Sketching on Windows 11 Devices</u></a></li>
<li><a href="https://win-answers.techidaily.com/pathfinder-wrath-of-the-righteous-overcoming-constant-crashes-and-game-stability/"><u>Pathfinder: Wrath of the Righteous - Overcoming Constant Crashes & Game Stability</u></a></li>
<li><a href="https://unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-infinix-hot-40-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Infinix Hot 40 Phone Now with These Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-images-at-fingertips-top-4-webp-viewer-windows/"><u>Perfect Images at Fingertips: Top 4 WebP Viewer Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-voice-recognition-program-for-windows-whisper-and-autohotkey-methods/"><u>Personalized Voice Recognition Program for Windows: Whisper & AutoHotkey Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-failed-attachment-of-usb-device-to-virtualbox/"><u>Quick Fixes for Failed Attachment of USB Device to VirtualBox</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-ensuring-equal-web-pace-on-your-devices/"><u>Quick Fixes: Ensuring Equal Web Pace on Your Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/refine-outdated-media-mastering-the-madvr-technique-for-windows/"><u>Refine Outdated Media: Mastering the MadVR Technique for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-11-sign-in-issues-quickly/"><u>Resolving Windows 11 Sign-In Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-sync-immediate-notebook-access-after-boot-up/"><u>Seamless Sync: Immediate Notebook Access After Boot-Up</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-a-stuck-windows-11-taskbar/"><u>Solutions for a Stuck Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-windows-apps-implement-effective-web-linking-strategies/"><u>Speed Up Windows Apps: Implement Effective Web Linking Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/start-with-style-not-sponsorship-in-w11/"><u>Start with Style, Not Sponsorship in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-stop-windows-task-moving-apps/"><u>Strategies to Stop Windows Task Moving Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/supercharge-windows-5-top-auto-click-wizards/"><u>Supercharge Windows: 5 Top Auto Click Wizards</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-network-link-lost-on-windows/"><u>Tackling Network Link Lost on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-8-best-pomodoro-timers-for-windows/"><u>The 8 Best Pomodoro Timers for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-trouble-free-win11-with-ccleaner/"><u>Tips for a Trouble-Free Win11 with CCleaner</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-review-of-the-durable-and-handy-kensun-mobile-tire-inflator/"><u>Top Review of the Durable and Handy Kensun Mobile Tire Inflator</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-strategies-to-overcome-steam-login-stalls-rustwindows-approach/"><u>Unveiling Strategies to Overcome Steam Login Stalls: Rust/Windows Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-adding-movescopies-context-menu-commands/"><u>Win 11: Adding Moves/Copies Context Menu Commands</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-bluescreen-woes-here-are-11-quick-fix-tips-to-try/"><u>Win11 Bluescreen Woes? Here Are 11 Quick Fix Tips to Try</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-decision-guide-home-features-vs-pro-benefits/"><u>Windows 11 Decision Guide: Home Features Vs. Pro Benefits</u></a></li>
<li><a href="https://youtube-web.techidaily.com/be-growth-secrets-masterful-narration-techniques-for-2024/"><u>YouTube Growth Secrets  Masterful Narration Techniques for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>