---
title: Redirect to File Explorer Using the OneDrive Shortcut
date: 2024-08-15T15:35:32.995Z
updated: 2024-08-16T15:35:32.995Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redirect to File Explorer Using the OneDrive Shortcut
excerpt: This Article Describes Redirect to File Explorer Using the OneDrive Shortcut
keywords: Redirect File Explorer,OneDrive Explorer,Office Explorer Shortcut,Quick OneDrive Access,Drive File Linking,Direct File Explorer,Share Folder Link
thumbnail: https://thmb.techidaily.com/850c193e7db5e5c0dafad83a501e0d012a7f8ab4be61e59f0459fea3e866d702.png
---

## Redirect to File Explorer Using the OneDrive Shortcut

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

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
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
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://blue-screen-error.techidaily.com/fixed-bsod-error-0x00000133-on-windows-11/"><u>[Fixed] BSOD Error 0X00000133 on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-insta-reversal-unlock-the-power-of-video-rotation/"><u>[New] 2024 Approved  Insta-Reversal  Unlock the Power of Video Rotation</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-the-ultimate-guide-to-vsdc-and-its-rivals/"><u>[Updated] 2024 Approved  The Ultimate Guide to VSDC and Its Rivals</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-game-on-recording-off-nvidia-magic/"><u>[Updated] In 2024, Game On, Recording Off! - NVIDIA Magic</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-your-must-listen-tiktok-rap-playlist/"><u>[Updated] In 2024, Your Must-Listen TikTok Rap Playlist</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-big-catch-bigger-views-top-5-aquatic-cameras/"><u>2024 Approved  Big Catch, Bigger Views - Top 5 Aquatic Cameras</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-enhancing-user-experience-with-timecodes-in-videos/"><u>2024 Approved  Enhancing User Experience with Timecodes in Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pinnacle-photo-narrative-directors-set/"><u>2024 Approved  Pinnacle Photo Narrative Director's Set</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-realme-c53-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Realme C53 by Name | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-windows-11-system-anomalies-analysis/"><u>A User’s Guide to Windows 11 System Anomalies Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-workflow-efficiency-mastering-flow-launcher/"><u>Boost Workflow Efficiency: Mastering Flow Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-barriers-to-maximize-windows-ram/"><u>Breaking Down Barriers to Maximize Windows' RAM</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-dormant-windows-11-control-panel-options/"><u>Bring Forth Dormant Windows 11 Control Panel Options</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-interface-reclamation-tips/"><u>Classic Interface Reclamation Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-how-windows-sustains-ongoing-optimization/"><u>Deciphering How Windows Sustains Ongoing Optimization</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-modern-standbys-drawbacks/"><u>Decoding Windows Modern Standby's Drawbacks</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-wow-start-up-issues-after-updates/"><u>Easing WoW Start-Up Issues After Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-editing-skills-mastering-jumps-and-pastes/"><u>Elevate Editing Skills: Mastering Jumps & Pastes</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-chromiums-firewall-connection-within-windows-safeguards/"><u>Enabling Chromium's Firewall Connection Within Windows Safeguards</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-windows-file-navigation-a-guide-excluding-ls/"><u>Enhanced Windows File Navigation: A Guide Excluding LS</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-various-windows-techniques-for-program-activation/"><u>Exploring Various Windows Techniques for Program Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/facing-down-rounded-corners-in-windows-11/"><u>Facing Down Rounded Corners in Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/how-to-discover-the-powershell-release-running-under-windows-a-detailed-guide/"><u>How to Discover the PowerShell Release Running Under Windows #: A Detailed Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-vivo-s17t-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Vivo S17t to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-broadcast-your-curated-playlist-with-ease/"><u>In 2024, Broadcast Your Curated Playlist with Ease</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-itel-a05s-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Itel A05s? Fixed | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-itop-screen-recorder-review-should-you-install-it/"><u>In 2024, ITop Screen Recorder Review  Should You Install It?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-honor-x50-gt-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Honor X50 GT FRP Bypass</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-iphone-14-pro-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>In 2024, Unlock Your iPhone 14 Pro in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/lowering-gameplay-stress-reducing-cpu-load-while-playing/"><u>Lowering Gameplay Stress: Reducing CPU Load While Playing</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-windows-11-efficiency-the-5-uptime-test-routines/"><u>Maximizing Windows 11 Efficiency: The 5 Uptime Test Routines</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-landscape-of-android-and-windows-file-sharing/"><u>Navigating the Landscape of Android & Windows File Sharing</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-directdraw-fixes-on-modern-microsoft-oses/"><u>Navigating the Maze of DirectDraw Fixes on Modern Microsoft OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-powershell-script-execution-policy-landscape/"><u>Navigating the PowerShell Script Execution Policy Landscape</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-frustration-quick-fixes-for-windows-11-woes/"><u>No More Frustration! Quick Fixes for Windows 11 Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-windows-dashboard-incorporate-portable-apps/"><u>Personalize Your Windows Dashboard: Incorporate Portable Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/quash-insufficient-requirement-notice-windows-11/"><u>Quash Insufficient Requirement Notice Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-fixing-microsoft-store-problems-on-win-11/"><u>Quickly Fixing Microsoft Store Problems on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-excessive-ram-allocation-in-connected-devices-interface/"><u>Resolving Excessive RAM Allocation in Connected Devices Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-network-path-with-fixed-ea-server-error-in-os/"><u>Restoring Network Path with Fixed EA Server Error in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-github-desktop-with-windows-11-os/"><u>Step-by-Step Guide to GitHub Desktop with Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-reclaiming-standard-windows-11-search-preferences/"><u>Step-by-Step: Reclaiming Standard Windows 11 Search Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-fn-key-brighness-in-windows-11/"><u>Steps to Restore Fn Key Brighness in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-counteract-d3d11-hardware-failures-in-w11w10/"><u>Strategies to Counteract D3D11 Hardware Failures in W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-walls-of-windows-icons/"><u>Taming the Walls of Windows Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-top-9-truths-about-why-pc-computers-win-over-macos-9/"><u>The Top 9 Truths About Why PC Computers Win over MacOS (#9)</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-bypassing-icloud-activation-lock-from-apple-iphone-xr-by-drfone-ios/"><u>The Ultimate Guide to Bypassing iCloud Activation Lock from Apple iPhone XR</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-windows-11-screens-with-custom-wallpaper-panes/"><u>Transform Windows 11 Screens with Custom Wallpaper Panes</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steps-delete-email-after-signing-in/"><u>Troubleshooting Steps: Delete Email After Signing In</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unleash-creativity-with-youtube-clips-make-animation-gifs-easily/"><u>Unleash Creativity with YouTube Clips - Make Animation GIFs Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-optimal-sleep-cycles-for-windows-devices/"><u>Unlocking Optimal Sleep Cycles for Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-your-smartphone-writescreen-functionality-for-windows-11/"><u>Unlocking Your Smartphone' Writescreen Functionality for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/voice-your-ideas-type-them-out-with-openais-whisper/"><u>Voice Your Ideas, Type Them Out With OpenAI’s Whisper</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-samsung-galaxy-s23-ultra-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Samsung Galaxy S23 Ultra Phones</u></a></li>
</ul></div>
