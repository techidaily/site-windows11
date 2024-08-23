---
title: Master Email Attachment Handling in Microsoft Word's Read Pane Mode
date: 2024-08-22T21:37:24.592Z
updated: 2024-08-23T21:37:24.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Master Email Attachment Handling in Microsoft Word's Read Pane Mode
excerpt: This Article Describes Master Email Attachment Handling in Microsoft Word's Read Pane Mode
keywords: Word Attachment View,Reading Pane Mail,Handle MS Word Mails,Secure Word Emails,Attach PDF to Word,Save Word Read-Only,Manage Wordmails Efficiently
thumbnail: https://thmb.techidaily.com/c19a308589c95b1ddee27c6a5a356d350b91c656d430e8488c37e77595b9f657.jpg
---

## Master Email Attachment Handling in Microsoft Word's Read Pane Mode

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-decoding-the-science-of-hash-optimization-for-game-streaming/"><u>[New] In 2024, Decoding the Science of Hash Optimization for Game Streaming</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-the-blueprint-to-dominate-social-platforms/"><u>[New] In 2024, The Blueprint to Dominate Social Platforms</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-15-youtube-originals-premium-unboxing-sessions/"><u>[New] Top 15 YouTube Originals  Premium Unboxing Sessions</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-securing-your-pc-gaming-memories-best-techniques/"><u>[Updated] In 2024, Securing Your PC Gaming Memories  Best Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-simplifying-tasks-with-ez-grabber-techniques/"><u>[Updated] Simplifying Tasks with EZ Grabber Techniques</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-your-complete-manual-on-live-streaming-platforms-for-2024/"><u>[Updated] Your Complete Manual on Live Streaming Platforms for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-aesthetic-assembly-android-and-ios-video-sets-for-insta/"><u>2024 Approved  Aesthetic Assembly  Android & iOS Video Sets for Insta</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-surge-to-subscriber-success-with-strategic-tactics/"><u>2024 Approved  Surge to Subscriber Success with Strategic Tactics</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-transform-your-streaming-experience-with-these-9-filter-power-ups/"><u>2024 Approved  Transform Your Streaming Experience with These 9 Filter Power-Ups</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-motorola-moto-g-5g-2023-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Motorola Moto G 5G (2023)</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-unsynchronized-file-uploads-in-chrome-win-edition/"><u>Fix Unsynchronized File Uploads in Chrome, Win Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-teammers-disconnected-screens/"><u>Fix Your Teammers’ Disconnected Screens</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/frohe-weihnachten-german/"><u>Frohe Weihnachten (German)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-zero-to-hero-navigating-youtubes-growth-journey/"><u>From Zero to Hero  Navigating Youtube's Growth Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-to-know-you-your-pc-unveiling-the-brand-and-model/"><u>Getting to Know You (Your PC): Unveiling the Brand and Model</u></a></li>
<li><a href="https://windows11.techidaily.com/handling-unsuccessful-execution-calls-in-malwarebytes-software/"><u>Handling Unsuccessful Execution Calls in Malwarebytes Software</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-carry-out-a-thorough-sfc-scan-in-windows/"><u>How to Carry Out a Thorough SFC Scan in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-identify-hard-drive-specs-on-windows/"><u>How to Identify Hard Drive Specs on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reroute-malwarebytes-database-access-post-error/"><u>How to Reroute Malwarebytes' Database Access Post Error</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-i-transferred-messages-from-oneplus-11r-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How I Transferred Messages from OnePlus 11R to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-apple-iphone-12-drfone-by-drfone-virtual-ios/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Apple iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-enhanced-productivity-integrating-android-and-windows-11-devices/"><u>Journey to Enhanced Productivity: Integrating Android and Windows 11 Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-mouse-drivers-for-efficient-windows-use/"><u>Mastering Mouse Drivers for Efficient Windows Use</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-with-customized-troubleshooters-shortcuts/"><u>Maximizing Efficiency with Customized Troubleshooters Shortcuts</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-tiktok-video-reversal-made-easy-a-beginners-guide-updated-for-2024/"><u>New TikTok Video Reversal Made Easy A Beginners Guide Updated  for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/old-world-new-interface-turning-windows-11-into-98/"><u>Old World, New Interface: Turning Windows 11 Into '98</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-admin-controlled-feature-malfunctions-on-windows-11/"><u>Overcoming Admin Controlled Feature Malfunctions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-obstacles-with-windows-safeguard-issues/"><u>Overcoming Obstacles with Windows Safeguard Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-reviving-access-with-past-login-details/"><u>Overcoming Reviving Access with Past Login Details</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-value-uncertainty-issues-in-windows-10/"><u>Overcoming Value Uncertainty Issues in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/personalized-scheduling-in-outlook-for-windows-enthusiasts/"><u>Personalized Scheduling in Outlook for Windows Enthusiasts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/premium-voice-capture-apps-on-mac-the-best-five-ranked/"><u>Premium Voice Capture Apps on Mac  The Best Five Ranked</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-for-a-functioning-xbox-on-windows/"><u>Quick-Fix Guide for a Functioning Xbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-zero-error-in-the-windows-store/"><u>Remedying Zero-Error in the Windows Store</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-blank-camera-on-device-management-screen/"><u>Revive Your Blank Camera on Device Management Screen</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/share-tweets-whatsapp-video-broadcasting-for-2024/"><u>Share Tweets  WhatsApp Video Broadcasting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/speedy-windows-discord-cutting-down-latency-issues/"><u>Speedy Windows Discord: Cutting Down Latency Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-mending-or-swapping-faulty-nintendo-switches/"><u>Strategies for Mending or Swapping Faulty Nintendo Switches</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-clipchamps-windows-11-setup-obstacles-with-precision/"><u>Tackle ClipChamp's Windows 11 Setup Obstacles with Precision</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-disconnected-secondary-monitor-on-pc/"><u>Tackling Disconnected Secondary Monitor on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-hard-drive-errors-on-windows/"><u>Tackling Hard Drive Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-taskbar-width-in-win11/"><u>Tweaking Taskbar Width in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-global-communication-navigating-languages-with-shortcuts-on-windows/"><u>Unlock Global Communication: Navigating Languages with Shortcuts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-the-definitive-list-of-11-strategies-for-the-credential-manager/"><u>Unlocking Windows: The Definitive List of 11 Strategies for the Credential Manager</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unmatched-8-visual-effects-for-smooth-live-videos-for-2024/"><u>Unmatched 8 Visual Effects for Smooth Live Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-secrets-behind-windows-system-updates/"><u>Unraveling the Secrets Behind Windows System Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/what-does-microsoft-copilot-offer-programmers/"><u>What Does Microsoft Copilot Offer Programmers?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-10-steps-to-rectify-defective-usb-hardware/"><u>Windows 10: Steps to Rectify Defective USB Hardware</u></a></li>
</ul></div>
