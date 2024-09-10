---
title: Navigate to File Explorer Through OneDrive in Windows
date: 2024-09-09T12:15:43.147Z
updated: 2024-09-10T12:15:43.147Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to File Explorer Through OneDrive in Windows
excerpt: This Article Describes Navigate to File Explorer Through OneDrive in Windows
keywords: Navigate to DFexplorer,OneDrive Explore Files,File Explorer Access,Windows OneDrive View,Direct Explorer Opening,Quick OneDrive Explorer,OneDrive Navigate Explorer
thumbnail: https://thmb.techidaily.com/9ad9147e4fbb8c24ccda197a0486be5c1d9c044a46c11534bd2a1352ab33e591.png
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115920/19272" target="_top" id="2115920">
  <img src="//a.impactradius-go.com/display-ad/19272-2115920" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115920/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Navigate to File Explorer Through OneDrive in Windows

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
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
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139123/17108" target="_top" id="2139123">
  <img src="//a.impactradius-go.com/display-ad/17108-2139123" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139123/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-top-3-nintendo-switch-emulators-free-to-download/"><u>[New] In 2024, Top 3 Nintendo Switch Emulators Free to Download</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-rapidly-finding-friends-on-facebooks-network/"><u>[New] Rapidly Finding Friends on Facebook's Network</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-from-casual-follower-to-dedicated-subscriber-inspirational-journey/"><u>[Updated] From Casual Follower to Dedicated Subscriber Inspirational Journey</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-breaking-news-working-obs-cam/"><u>[Updated] In 2024, Breaking News Working OBS Cam</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-precision-editing-embedding-times-in-video-posts/"><u>[Updated] In 2024, Precision Editing Embedding Times in Video Posts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-recode-video-files-to-audio-outputs-for-2024/"><u>[Updated] Recode Video Files to Audio Outputs for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-sow-and-reap-rivalries-farming-games-to-remember-for-2024/"><u>[Updated] Sow & Reap Rivalries Farming Games to Remember for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-ultimate-connectivity-handbook-for-insta-and-tik/"><u>2024 Approved The Ultimate Connectivity Handbook for Insta & Tik</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-top-5-mkv-player-picks-for-macos-enthusiasts/"><u>2024 Approved Top 5 MKV Player Picks for macOS Enthusiasts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-unveiling-the-secrets-of-youtube-video-dimensions-and-resolution/"><u>2024 Approved Unveiling the Secrets of YouTube Video Dimensions & Resolution</u></a></li>
<li><a href="https://extra-information.techidaily.com/5-best-toy-drones/"><u>5 Best Toy Drones</u></a></li>
<li><a href="https://media-tips.techidaily.com/a-comprehensive-guide-discover-the-ins-and-outs-of-entertaining-animated-memes-and-gifs/"><u>A Comprehensive Guide: Discover the Ins and Outs of Entertaining Animated Memes & GIFs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boost-your-visual-language-with-premium-affects-extensions/"><u>Boost Your Visual Language with Premium Affects Extensions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/can-multiple-individuals-use-spotify-together-in-real-time/"><u>Can Multiple Individuals Use Spotify Together in Real-Time?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-honor-magic-6-pro-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Honor Magic 6 Pro</u></a></li>
<li><a href="https://fox-helps.techidaily.com/dreamy-documentaries-bedtime-stories-reviewed/"><u>Dreamy Documentaries Bedtime Stories Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/establishing-kids-internet-freedom-boundaries-on-windows-11/"><u>Establishing Kids' Internet Freedom Boundaries on Windows 11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/experiencing-connectivity-problems-with-xbox-live-common-fixes-and-solutions/"><u>Experiencing Connectivity Problems with Xbox Live – Common Fixes and Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-insights-into-the-world-of-hdr-technology-for-windows-11/"><u>Expert Insights Into the World of HDR Technology for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/file-organization-made-easy-configuring-win11s-auto-delete/"><u>File Organization Made Easy: Configuring Win11's Auto Delete</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-empty-directory-problem-microsofts-0x80070091-error-explained/"><u>Fixing 'Empty Directory' Problem - Microsoft's 0X80070091 Error Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-disconnections-in-external-display-setup-on-windows/"><u>Fixing Disconnections in External Display Setup on Windows</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-the-problem-of-non-responsive-davinci-resolve-on-your-windows-computer/"><u>Fixing the Problem of Non-Responsive DaVinci Resolve on Your Windows Computer</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-running-windows-11-on-ineligible-cpus-a-comprehensive-tutorial/"><u>Guide to Running Windows 11 on Ineligible CPUs - A Comprehensive Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-your-win-key-with-microsoft-profile-access/"><u>Harmonizing Your WIN Key with Microsoft Profile Access</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-elevate-windows-11-audio-capabilities-dolby-atmos/"><u>How to Elevate Windows 11 Audio Capabilities - Dolby Atmos</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-eliminate-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>How to Eliminate 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-make-sure-your-temp-folder-is-valid-error-in-windows-11/"><u>How to Fix the Make Sure Your Temp Folder Is Valid Error in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-zte-blade-a73-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a ZTE Blade A73 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-did-your-iphone-15-pro-max-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>In 2024, Did Your iPhone 15 Pro Max Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-how-big-should-a-good-thumbnail-be-youtubes-ultimate-guide/"><u>In 2024, How Big Should a Good Thumbnail Be? YouTube's Ultimate Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-oppo-reno-8t-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Oppo Reno 8T 5G to Another | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-taming-high-quality-streams-obs/"><u>In 2024, Taming High-Quality Streams (OBS)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-gionee-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Gionee Device</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-the-invisible-recorder-how-to-save-online-music-streams/"><u>In 2024, The Invisible Recorder How to Save Online Music Streams</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-windows-prime-video-communication-tools-1-8/"><u>In 2024, Windows' Prime Video Communication Tools, #1-8</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-subsystem-pivotal-for-linux-desktops/"><u>Is Windows Subsystem Pivotal for Linux Desktops?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/master-the-art-of-console-game-recording-with-computer-assistance-for-2024/"><u>Master the Art of Console Game Recording with Computer Assistance for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-application-dependency-resolution-with-wpm/"><u>Mastering Application Dependency Resolution with WPM</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-access-enabling-telnet-on-win-10-and-11/"><u>Mastering Network Access: Enabling Telnet on Win 10 and 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-default-programs-configuration/"><u>Mastering Windows 11 Default Programs Configuration</u></a></li>
<li><a href="https://windows11.techidaily.com/open-windows-11s-memory-lane-file-history-guide/"><u>Open Windows 11'S Memory Lane - File History Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pcs-auditory-experience-with-updated-drivers-guide/"><u>Optimize Your PC's Auditory Experience with Updated Drivers Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/outsmarting-your-os-glitch-effective-script-solutions-for-windows/"><u>Outsmarting Your OS Glitch: Effective Script Solutions for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/powershell-mastery-for-windows-administrators/"><u>PowerShell Mastery for Windows Administrators</u></a></li>
<li><a href="https://extra-tips.techidaily.com/premier-5-iphones-for-podcast-aficionados/"><u>Premier 5 iPhones for Podcast Aficionados</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-auto-opens-of-windows-11s-search-bar/"><u>Preventing Auto-Opens of Windows 11'S Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-measures-to-increase-virtual-memory-in-windows-11-operations/"><u>Proactive Measures to Increase Virtual Memory in Windows 11 Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-glance-uncovering-graphics-card-version-win11/"><u>Quick Glance: Uncovering Graphics Card Version, Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/reactive-steps-for-faulty-windows-performance-tracking-tool/"><u>Reactive Steps for Faulty Windows Performance Tracking Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-redoing-reactivating-ms-store-for-windows-users/"><u>Resetting and Redoing: Reactivating MS Store for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-functionality-of-your-windows-11-key/"><u>Restoring Functionality of Your Windows 11 Key</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-xiaomi-14-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Xiaomi 14</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-os-operation-via-pct-steps/"><u>Securing Smooth OS Operation via PCT Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-unacceptable-connections-in-microsoft-os/"><u>Solving Unacceptable Connections in Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-purchases-on-microsofts-digital-shelf/"><u>Speeding Up Purchases on Microsoft's Digital Shelf</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-windows-defense-plan-7-methods/"><u>The Ultimate Windows Defense Plan (7 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-speedy-windows-11-boot-turn-on-quick-startup/"><u>Tips for Speedy Windows 11 Boot: Turn on Quick Startup</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-system-calls-failure-on-win1011/"><u>Troubleshooting System Calls Failure on Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-wow-update-windows-troubleshooting-guide/"><u>Unfreezing WoW Update: Windows Troubleshooting Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugging-and-plugging-in-your-wireless-mouse-quick-fixes/"><u>Unplugging and Plugging In Your Wireless Mouse - Quick Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-windows-11-writability-creating-self-extractables/"><u>Unraveling Windows 11' Writability: Creating Self-Extractables</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-system32-location-in-windows-11/"><u>Unveiling System32 Location in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/win1011-recycle-troubleshooting-restoring-corruption-error/"><u>Win10/11 Recycle Troubleshooting: Restoring Corruption Error</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-streamline-your-screens-with-a-three-column-board-setup/"><u>Windows 11: Streamline Your Screens with a Three-Column Board Setup</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>