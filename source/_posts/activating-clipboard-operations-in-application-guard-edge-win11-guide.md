---
title: Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
date: 2024-08-15T15:12:41.440Z
updated: 2024-08-16T15:12:41.440Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
excerpt: This Article Describes Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide
keywords: Edge AppGuard Clipboard Activation,Win11 Clipboard Enable,Application Guard Keyboard Use,Windows 11 Security Feature,Edge Operations Guide,Clipboard Management in Edge,Enabling AppGuard Functions
thumbnail: https://thmb.techidaily.com/c2342fb5e25c5a967555cf815791bd2b9698b049e69b2eb389ba72dc308a7ad2.jpeg
---

## Activating Clipboard Operations in Application Guard (Edge) - Win11 Guide

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
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
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-the-ultimate-software-for-mp4-recording/"><u>[New] 2024 Approved  The Ultimate Software for MP4 Recording</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-time-lapse-tips-for-iphoneipad-users/"><u>[New] 2024 Approved  Time-Lapse Tips for iPhone/iPad Users</u></a></li>
<li><a href="https://youtube-web.techidaily.com/inancial-insights-for-vids-how-much-do-youtubers-earn-per-sponsorship/"><u>[New] Financial Insights for Vids  How Much Do YouTubers Earn Per Sponsorship?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-zoom-in-on-zucks-users-rapidly-pinpoint-profiles/"><u>[New] In 2024, Zoom-In on Zuck's Users  Rapidly Pinpoint Profiles</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-enhancing-youtube-presence-creating-professional-thumbnails-from-smartphones/"><u>2024 Approved  Enhancing YouTube Presence  Creating Professional Thumbnails From Smartphones</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-portable-playstation-storage-best-10-hdds-ssds/"><u>2024 Approved  Portable PlayStation Storage  Best 10 HDDs, SSDs</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-access-denied-and-restricted-access-issues-windows-office-solution/"><u>Fixing 'Access Denied' And Restricted Access Issues: Windows Office Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-data-fast-onedrive-without-web-connection/"><u>Get Your Data Fast: OneDrive, Without Web Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-a-linux-virtual-machine-inside-a-windows-virtual-machine-using-hyper-v/"><u>How to Create a Linux Virtual Machine Inside a Windows Virtual Machine Using Hyper-V</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-vivo-y78plus-using-video-repair-utility-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix Corrupt video files of Vivo Y78+ using Video Repair Utility?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Tecno Spark 20C? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-dxgi-error-in-win-11-os/"><u>How to Mend the DXGI Error in Win 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-windows-from-automatically-locking-itself/"><u>How to Stop Windows From Automatically Locking Itself</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-8-drfone-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-password-solutions-7-best-wins-for-windows-users/"><u>Innovative Password Solutions: 7 Best Wins for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/leading-the-pack-best-windows-11-for-fps-tracking/"><u>Leading the Pack: Best Windows 11 for FPS Tracking</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-directdraw-repair-techniques-on-the-latest-version-of-windows/"><u>Mastering DirectDraw Repair Techniques on the Latest Version of Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-technology-the-ultimate-resource-by-toms-hardware-specialists/"><u>Mastering Technology: The Ultimate Resource by Tom's Hardware Specialists</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-windows-elevated-command-window/"><u>Mastery Over Windows: Elevated Command Window</u></a></li>
<li><a href="https://windows11.techidaily.com/outsmart-your-pcs-bluescreen-adopting-win11s-best-practices/"><u>Outsmart Your PC's Bluescreen: Adopting Win11's Best Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-microsoft-store-glitch-0x80073d26-in-win11/"><u>Overcoming Microsoft Store Glitch 0X80073D26 in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-resetting-and-restoring-search-on-windows-11-settings-ui/"><u>Quick Fixes: Resetting and Restoring Search on Windows 11 Settings UI</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-ram-burden-in-cross-device-service-platforms-on-windows/"><u>Reducing RAM Burden in Cross-Device Service Platforms on Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-why-insurgency-sandstorm-game-frequently-encounters-crashes/"><u>Resolved: Why Insurgency: Sandstorm Game Frequently Encounters Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-audacitys-paudio-error-on-w10w11-systems/"><u>Resolving Audacity's PAudio Error on W10/W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/silence-automatic-spotify-launch-in-windows/"><u>Silence Automatic Spotify Launch in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-adjust-standard-user-permissions-in-windows/"><u>Steps to Adjust Standard User Permissions in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/streamlining-your-zoom-recordings-a-comprehensive-workshop/"><u>Streamlining Your Zoom Recordings  A Comprehensive Workshop</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-plan-to-vanquish-wows-deadly-error-132-in-osxwin/"><u>Tactical Plan to Vanquish WoW's Deadly Error #132 in OSX/Win</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-guide-to-windows-11-personalization/"><u>The Complete Guide to Windows 11 Personalization</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-storage-space-with-win11-defrag-guide/"><u>Turbocharge Storage Space with Win11 Defrag Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/update-user-folder-names-with-ease-on-win11/"><u>Update User Folder Names with Ease on Win11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-premier-selection-of-cost-free-online-daw-software-users-for-2024/"><u>Updated The Premier Selection of Cost-Free Online DAW Software Users for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-eliminating-audacity-paudio-faults/"><u>Win10/Win11: Eliminating Audacity PAudio Faults</u></a></li>
</ul></div>
