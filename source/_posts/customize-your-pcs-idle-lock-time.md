---
title: Customize Your PC's Idle Lock Time
date: 2024-08-08T05:59:50.243Z
updated: 2024-08-09T05:59:50.243Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Your PC's Idle Lock Time
excerpt: This Article Describes Customize Your PC's Idle Lock Time
keywords: PC Idle Time Customization,PC Sleep Lock Adjust,Set PC Standby Delay,Customizable PC Idle,Tailor PC Downtime,Modify PC Sleep Timer,Personalize Pc Rest State
thumbnail: https://thmb.techidaily.com/eb0b88fc8ea01a6f57ac593062a230bcd4f411a04c405e68f58f5857acd450ec.jpg
---

## Customize Your PC's Idle Lock Time

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-art-of-online-podcast-filming/"><u>[New] 2024 Approved  The Art of Online Podcast Filming</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/mplify-your-youtubes-interaction-with-emojis/"><u>[New] Amplify Your Youtubes' Interaction with Emojis</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-downloading-facebook-videos-ultimate-5-list-ranked/"><u>[Updated] In 2024, Downloading Facebook Videos  Ultimate 5 List Ranked</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-iphones-automatic-replay-feature/"><u>2024 Approved  Navigating iPhone's Automatic Replay Feature</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-omnipresent-iptv-networking-model/"><u>2024 Approved  Omnipresent IPTV Networking Model</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-realme-narzo-n55-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from Realme Narzo N55 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/accessing-disguised-user-responses-on-yt/"><u>Accessing Disguised User Responses on YT</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-excessive-load-alert-for-gpt-window-use/"><u>Easing Excessive Load Alert for GPT Window Use</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-activating-outlook-preview-in-windows-11-os/"><u>Easy Steps for Activating Outlook Preview in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-playback-of-laggard-videos/"><u>Efficient Playback of Laggard Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-altering-windows-account-pin-code/"><u>Efficiently Altering Windows Account Pin Code</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-run-windows-11-news-and-video-sites-without-strain/"><u>Efficiently Run Windows 11 News & Video Sites without Strain</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-telnet-configuration-for-win11-users/"><u>Effortless Telnet Configuration for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-performance-top-tools-to-tune-up-windows-pcs/"><u>Elevate Performance: Top Tools to Tune Up Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-workflow-select-7-most-powerful-w11-widgets/"><u>Elevate Workflow: Select 7 Most Powerful W11 Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-application-display-enable-windows-11s-autocolor/"><u>Elevate Your Application Display - Enable Windows 11'S AutoColor</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-with-god-mode-add-on/"><u>Elevate Your Workflow with God Mode Add-On</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-workflow-on-windows-11-for-professionals/"><u>Elevating Workflow on Windows 11 for Professionals</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-app-setup-game-with-winstall-on-windows-11/"><u>Elevating Your App Setup Game with Winstall on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-the-error-unable-to-terminate-process-phenomenon/"><u>Eliminating the 'Error: Unable to Terminate Process' Phenomenon</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-unexpected-closure-notifications-from-roblox-games/"><u>Eliminating Unexpected Closure Notifications From Roblox Games</u></a></li>
<li><a href="https://windows11.techidaily.com/elusive-archive-tucked-away-zip-and-images-on-windows-11/"><u>Elusive Archive Tucked Away: ZIP & Images on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/emulate-macos-style-5-methods-to-revamp-windows/"><u>Emulate macOS Style: 5 Methods to Revamp Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/enable-sd-card-view-in-file-explorer-puzzle-solved/"><u>Enable SD Card View in File Explorer Puzzle Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-application-guard-printing-for-windows-11-users/"><u>Enabling Application Guard Printing for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-epic-launcher-performance-a-how-to/"><u>Enhancing Epic Launcher Performance: A How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-mouse-cursor-prominence-in-windows-os/"><u>Enhancing Mouse Cursor Prominence in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-event-viewer-functionality/"><u>Enhancing Windows Event Viewer Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-single-user-printer-operation-on-windows-11/"><u>Ensuring Single-User Printer Operation on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Vivo Y27s? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-12-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi 12 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/leading-laser-cutting-systems-in-2e24-buyers-guide/"><u>Leading Laser Cutting Systems in 2E24 - Buyer's Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/make-your-own-vr-gear-diy-guide-for-google-cardboard-viewers-for-2024/"><u>Make Your Own VR Gear  DIY Guide for Google Cardboard Viewers for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/navigating-the-starscape-a-guide-to-influencers-for-your-needs/"><u>Navigating the Starscape  A Guide to Influencers for Your Needs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/planting-depth-and-spacing/"><u>Planting Depth and Spacing</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/quality-audio-awaits-with-these-premium-asmr-mics-for-2024/"><u>Quality Audio Awaits with These Premium ASMR Mics for 2024</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-persistent-zoom-issues-on-windows-1110-expert-tips-for-a-smooth-meeting-experience/"><u>Troubleshooting Persistent Zoom Issues on Windows 11/10 - Expert Tips for a Smooth Meeting Experience</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unlocking-the-potential-of-valorant-thumbnails-for-online-success/"><u>Unlocking the Potential of Valorant Thumbnails for Online Success</u></a></li>
</ul></div>
