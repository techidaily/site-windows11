---
title: Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
date: 2024-08-15T16:18:59.958Z
updated: 2024-08-16T16:18:59.958Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
excerpt: This Article Describes Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition
keywords: Edge AppGuard Clipboard,Edge Security Paste,Windows 11 Safety Feature,AppGuard Copy Protection,W11 Enhanced Clipping,Secure Clipboard Edge,Paste with Application Guard
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Unlocking Copy & Paste Features with Application Guard in Edge, W11 Edition

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


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
<li><a href="https://some-skills.techidaily.com/new-the-fundamentals-of-creating-dynamic-podcast-feeds/"><u>[New] The Fundamentals of Creating Dynamic Podcast Feeds</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-avoid-facebooks-targeted-video-promotions/"><u>[Updated] Avoid Facebook's Targeted Video Promotions</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-securing-youtube-srt-files-a-threefold-procedure-for-2024/"><u>[Updated] Securing YouTube SRT Files  A Threefold Procedure for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-swiftly-delete-autoplayed-podcast-suggestions-on-spotify/"><u>[Updated] Swiftly Delete Autoplayed Podcast Suggestions on Spotify</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-oppo-reno-11-pro-5g-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/5-most-effective-methods-to-unlock-apple-iphone-12-in-lost-mode-by-drfone-ios/"><u>5 Most Effective Methods to Unlock Apple iPhone 12 in Lost Mode</u></a></li>
<li><a href="https://games-able.techidaily.com/8-tips-to-boost-your-framerate-in-counter-strike-global-offensive-for-windows/"><u>8 Tips to Boost Your Framerate in Counter-Strike: Global Offensive for Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/advanced-editor-techniques-from-the-experts-at-canva-for-2024/"><u>Advanced Editor Techniques From the Experts at Canva for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/find-and-apply-latest-firmware-hp-laserjet-m506-printer-drivers-free-download/"><u>Find and Apply Latest Firmware: HP LaserJet M506 Printer Drivers Free Download</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fists-vs-followers-choosing-the-champion-for-2024/"><u>Fists vs Followers  Choosing the Champion for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-windows-and-wsl-after-a-major-update/"><u>Harmonizing Windows and WSL After a Major Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-automatic-deletion-for-effortless-disk-space-maintainance/"><u>Harnessing Automatic Deletion for Effortless Disk Space Maintainance</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-screens-revealed-the-most-effective-6-techniques-to-recover-off-screen-apps-in-win/"><u>Hidden Screens Revealed: The Most Effective 6 Techniques to Recover Off-Screen Apps in Win</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-your-xiaomi-redmi-note-13-proplus-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Xiaomi Redmi Note 13 Pro+ 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Vivo Y78+? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ignore-microsofts-app-verification-warnings/"><u>How to Ignore Microsoft's App Verification Warnings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediuate-switch-text-editor-to-a-dark-scheme-windows-11/"><u>How to Immediuate Switch Text Editor to a Dark Scheme, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resolve-offline-printer-problems-in-os/"><u>How To Resolve Offline Printer Problems in OS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Apple iPhone 12 Pro? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-oppo-f25-pro-5g-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Oppo F25 Pro 5G Device</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-installation-of-the-latest-win11-version-22h2-update/"><u>Mastering Installation of the Latest Win11 Version 22H2 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-way-through-playstation-1-games-in-windows-with-duckstation/"><u>Mastering Your Way Through PlayStation 1 Games in Windows with Duckstation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-native-tools-for-disk-replication/"><u>Navigating Native Tools for Disk Replication</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723211775888-pubg-2024-master-the-art-of-fixing-game-launch-issues-and-start-enjoying-now/"><u>PUBG 2024: Master the Art of Fixing Game Launch Issues and Start Enjoying Now</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-faster-execution-of-excel-on-windows-pcs/"><u>Reactivating Faster Execution of Excel on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-audio-recorder-crash-9999-on-windows-platforms/"><u>Solving Audio Recorder Crash 9999 on Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-failed-page-loading-on-ms-store/"><u>Steps to Resolve Failed Page Loading on MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-regaining-router-interface-on-pc/"><u>Strategies for Regaining Router Interface on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-windows-1110s-nvidia-access-problem/"><u>Strategies to Resolve Windows 11/10'S NVidia Access Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-boot-sequence-customizing-timeout-window-11/"><u>Streamlining Boot Sequence: Customizing Timeout Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-search-highlights-onoff-windows-11-guide/"><u>Switching Search Highlights On/Off: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-files-delete-confirmations/"><u>Tailoring Windows Files' Delete Confirmations</u></a></li>
<li><a href="https://youtube-web.techidaily.com/rt-of-optimizing-your-yt-channel-description-for-2024/"><u>The Art of Optimizing Your YT Channel Description for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-experts-guide-to-navigating-with-windows-narrator/"><u>The Expert's Guide to Navigating with Windows Narrator</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-future-of-audio-srt-in-mp4-video-files-for-2024/"><u>The Future of Audio  SRT in MP4 Video Files for 2024</u></a></li>
<li><a href="https://ai-topics.techidaily.com/toms-tech-insights-expert-computer-and-gadget-reviews/"><u>Tom's Tech Insights: Expert Computer and Gadget Reviews</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-strengths-of-win11-outshining-macos/"><u>Top 6 Strengths of Win11 Outshining MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-development-power-with-windows-11s-dev-drive-insights/"><u>Uncovering Development Power with Windows 11’S Dev Drive Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/ups-and-downs-on-the-desktop-frontier-comparing-w10-and-w11/"><u>Ups and Downs on the Desktop Frontier: Comparing W10 & W11</u></a></li>
</ul></div>
