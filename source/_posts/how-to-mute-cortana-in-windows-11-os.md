---
title: How to Mute Cortana in Windows 11 OS
date: 2024-08-15T15:54:54.685Z
updated: 2024-08-16T15:54:54.685Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Mute Cortana in Windows 11 OS
excerpt: This Article Describes How to Mute Cortana in Windows 11 OS
keywords: Muting Cortana Windows 11,Turn Off Cortana Windows,Disable Cortana Windows 11,Cortana Silence Guide Windows,Stop Cortana in Windows OS,Cortana Suppress Windows,How to Halt Cortana Wins
thumbnail: https://thmb.techidaily.com/897a54d20c0fe274d0937962de97f84511515ba57539d3344fb75e1f209995c6.png
---

## How to Mute Cortana in Windows 11 OS

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ropel-your-youtube-journey-breakthroughs-at-the-500-subscriber-mark/"><u>[New] Propel Your YouTube Journey  Breakthroughs at the 500-Subscriber Mark</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unlock-the-power-of-discord-broadcasts/"><u>[New] Unlock the Power of Discord Broadcasts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-a-step-by-step-roadmap-for-lasting-tiktok-account-loss-for-2024/"><u>[Updated] A Step-by-Step Roadmap for Lasting TikTok Account Loss for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transcription-tech-zero-fee-for-the-user/"><u>[Updated] Transcription Tech, Zero Fee for the User</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-breakdown-of-which-ipad-versions-feature-native-gps-capabilities/"><u>A Breakdown of Which iPad Versions Feature Native GPS Capabilities</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-understanding-leveraging-adobe-cloud-and-finding-alternatives-for-2024/"><u>Comprehensive Understanding  Leveraging Adobe Cloud and Finding Alternatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-ais-weak-spot-the-art-of-prompt-injection/"><u>Delving Into AI's Weak Spot: The Art of Prompt Injection</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-and-install-the-latest-logitech-mk710-keyboard-software/"><u>Download and Install the Latest Logitech MK710 Keyboard Software</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-scripts-to-discover-your-computers-ip-and-mac-addresses/"><u>Essential Scripts to Discover Your Computer's IP & MAC Addresses</u></a></li>
<li><a href="https://windows11.techidaily.com/festive-fizzles-yule-time-apps-from-microsofts-hub/"><u>Festive Fizzles: Yule-Time Apps From Microsoft's Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-temp-storage-errors-in-the-latest-win11-version/"><u>Fixing Temp Storage Errors in the Latest Win11 Version</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-razer-naga-software-updates-for-your-computer-running-windows/"><u>Get the Newest Razer Naga Software Updates for Your Computer Running Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guidance-for-overcoming-indexer-service-start-up-issues/"><u>Guidance for Overcoming Indexer Service Start-Up Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/historical-gems-art-unshackled-by-laws/"><u>Historical Gems  Art Unshackled by Laws</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-chrome-saving-images-in-webp-format-on-windows/"><u>How to Stop Chrome Saving Images in WebP Format on Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y27-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Vivo Y27 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-fixes-for-the-add-your-folder-now-issue-on-windows-onedrive-drive/"><u>Immediate Fixes for the 'Add Your Folder Now' Issue on Windows OneDrive Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/implementing-python-on-windows-for-optimized-file-transfer/"><u>Implementing PYTHON on Windows for Optimized File Transfer</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-google-photos-and-your-creativity-quick-collages-made-simple/"><u>In 2024, Google Photos & Your Creativity  Quick Collages Made Simple</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-samsung-galaxy-s24-ultra-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Samsung Galaxy S24 Ultra Phone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-xiaomi-redmi-12-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Xiaomi Redmi 12</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-10-plugin-power-duo-for-final-cut-pro/"><u>In 2024, The Ultimate 10 Plugin Power Duo for Final Cut Pro</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-hp-laserjet-amo-1320-printer-drivers-compatible-with-windows-os/"><u>Latest HP LaserJet Amo 1320 Printer Drivers - Compatible with Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/less-is-more-compact-view-strategies-for-windows-11/"><u>Less Is More: Compact View Strategies for Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/making-photos-dance-dynamic-distortions-with-ps-for-2024/"><u>Making Photos Dance  Dynamic Distortions with PS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-drag-and-drop-in-w11-folder-moving/"><u>Master the Art of Drag & Drop in W11 Folder Moving</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-high-speed-game-updates-in-battlenet/"><u>Mastering High-Speed Game Updates in Battle.net</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-network-management-wi-fi-removal-guide/"><u>Mastering Network Management: Wi-Fi Removal Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/mini-marvel-comprehensive-echo-dot-3rd-gen-review-unleashing-the-full-power-of-alexa/"><u>Mini Marvel: Comprehensive Echo Dot (3Rd Gen) Review - Unleashing the Full Power of Alexa</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-isdonedll-isarcextract-crashes-on-w10w11/"><u>Mitigating ISDone.dll (ISArcExtract) Crashes on W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-components-settings-in-windows-11/"><u>Navigating Components Settings in Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-transform-your-videos-easy-editing-with-microsoft-video-editor-on-windows-for-2024/"><u>New Transform Your Videos Easy Editing with Microsoft Video Editor on Windows for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-slow-download-issues-with-ease-win/"><u>Overcoming Slow Download Issues with Ease (Win)</u></a></li>
<li><a href="https://media-tips.techidaily.com/quick-and-simple-guide-transform-your-m3u8-playlists-into-high-quality-mp3-tracks-at-home-or-online/"><u>Quick and Simple Guide: Transform Your M3U8 Playlists Into High-Quality MP3 Tracks at Home or Online</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-disrupted-voice-command-functionality-on-win11/"><u>Quick Fixes for Disrupted Voice Command Functionality on Win11</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-realme-narzo-n53-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Realme Narzo N53</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-restoring-sync-in-the-microsoft-to-do-application/"><u>Resetting & Restoring Sync in the Microsoft To-Do Application</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-and-recovering-lost-steam-icons/"><u>Resetting and Recovering Lost Steam Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-visual-problems-with-windows-graphics-driver/"><u>Resolving Visual Problems with Windows Graphics Driver</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/screenplay-sage-answers-for-beginners/"><u>Screenplay Sage  Answers for Beginners</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpen-windows-keystrokes-seven-tactics-to-decrease-delay/"><u>Sharpen Windows' Keystrokes: Seven Tactics to Decrease Delay</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-overlapping-icons-on-pc/"><u>Solving Overlapping Icons on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-task-managers-dynamic-display-in-windows-11/"><u>Speed up Task Manager's Dynamic Display in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/spice-up-your-instagram-feed-incorporate-video-loops-for-2024/"><u>Spice Up Your Instagram Feed  Incorporate Video Loops for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-guide-to-disabling-restrictions-and-opening-hidden-outlook-directories/"><u>Stepwise Guide to Disabling Restrictions & Opening Hidden Outlook Directories</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-installation-of-dolby-atmos-audio-on-windows-devices/"><u>Stepwise Installation of Dolby Atmos Audio on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-fixing-apple-device-image-io-problems-in-w11/"><u>Strategies for Fixing Apple Device Image I/O Problems in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-no-network-signal-on-pc/"><u>Tackling No Network Signal on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-unresponsive-back-space-button/"><u>Techniques to Address Unresponsive Back Space Button</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-a-fortified-pc-with-windows-11-and-tpmsecure-boot/"><u>The Path to a Fortified PC with Windows 11 & TPM/Secure Boot</u></a></li>
<li><a href="https://activate-lock.techidaily.com/top-7-icloud-activation-bypass-tools-for-your-iphone-xs-max-by-drfone-ios/"><u>Top 7 iCloud Activation Bypass Tools For your iPhone XS Max</u></a></li>
<li><a href="https://windows11.techidaily.com/top-8-methods-for-accessing-iis-manager/"><u>Top 8 Methods for Accessing IIS Manager</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-non-working-wireless-charging-iphone-hacks-and-tips/"><u>Troubleshoot Non-Working Wireless Charging: IPhone Hacks & Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-how-runtime-brokers-affect-system-performance/"><u>Understanding How Runtime Brokers Affect System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-vm-potential-in-windows-through-these-techniques/"><u>Unleash VM Potential in Windows Through These Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-a-fresh-start-with-these-steam-game-tips/"><u>Unlock a Fresh Start with These Steam Game Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-android-gameplay-on-windows-11-with-googles-platform/"><u>Unlock Android Gameplay on Windows 11 with Google's Platform</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-system-tray-and-concealed-options-on-win11/"><u>Unveiling System Tray & Concealed Options on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-sticky-note-access-code-for-windows-11/"><u>Unveiling the Sticky Note Access Code for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-users-dislike-in-windows-11-most/"><u>What Users Dislike in Windows 11 Most</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
<li><a href="https://network-issues.techidaily.com/zombie-siege-snagged-in-slowdown/"><u>Zombie Siege Snagged in Slowdown</u></a></li>
</ul></div>
