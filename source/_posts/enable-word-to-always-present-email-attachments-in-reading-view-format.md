---
title: Enable Word to Always Present Email Attachments in Reading View Format
date: 2024-08-15T16:10:11.404Z
updated: 2024-08-16T16:10:11.404Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Word to Always Present Email Attachments in Reading View Format
excerpt: This Article Describes Enable Word to Always Present Email Attachments in Reading View Format
keywords: ReadEmailAttachments,WordReadAttachFormat,EnableEmailView,AttachByWord,ReadingEmailFormat,EmailAttachmentInWord,ViewEmailAttachments
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
---

## Enable Word to Always Present Email Attachments in Reading View Format

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

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
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
<li><a href="https://extra-information.techidaily.com/new-artful-humor-chuckledrawings/"><u>[New] Artful Humor  ChuckleDrawings</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-best-video-chatting-tools-for-remote-team-interactions/"><u>[New] In 2024, Best Video Chatting Tools for Remote Team Interactions</u></a></li>
<li><a href="https://youtube-web.techidaily.com/asterful-ad-blocking-select-from-these-top-7-android-apps-for-2024/"><u>[New] Masterful Ad Blocking  Select From These Top 7 Android Apps for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-effortless-mp4-conversion-from-facebook-hd-content-all-for-free/"><u>[Updated] Effortless MP4 Conversion From Facebook HD Content – All For Free</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-from-selfie-snaps-to-skincare-specials-establishing-your-youtube-brand/"><u>[Updated] From Selfie Snaps to Skincare Specials  Establishing Your YouTube Brand</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-holdscreen-rapid-snapshot-manual/"><u>[Updated] HoldScreen  Rapid Snapshot Manual</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-designing-instagrams-ideal-square-video-with-imovie/"><u>[Updated] In 2024, Designing Instagram's Ideal Square Video with iMovie</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-mastering-the-art-of-tweeting-video-uploads-on-instagram/"><u>[Updated] In 2024, Mastering the Art of Tweeting Video Uploads on Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-step-by-step-techniques-for-seamless-youtube-subtitling-and-captions/"><u>[Updated] Step-by-Step Techniques for Seamless YouTube Subtitling & Captions</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-how-to-use-vlc-as-converter-to-convert-mp4-and-other-formats/"><u>2024 Approved  How to Use VLC as Converter to Convert Mp4 and Other Formats</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-picperfect-pro-enhance-your-mobile-images-for-free/"><u>2024 Approved  PicPerfect Pro  Enhance Your Mobile Images for Free</u></a></li>
<li><a href="https://windows11.techidaily.com/7-festive-tweaks-to-personalize-your-windows-11/"><u>7 Festive Tweaks to Personalize Your Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/a-step-by-step-guide-overcoming-stop-error-0x00000124-in-windows-11-and-windows-7-operating-systems/"><u>A Step-by-Step Guide: Overcoming Stop Error 0X00000124 in Windows 11 and Windows 7 Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-wired-internet-beyond-100mbps-in-windows/"><u>Accelerating Wired Internet Beyond 100Mbps in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/apple-iphone-xr-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>Apple iPhone XR Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-abrupt-game-closure-in-roblox-fix-tips-for-pc-users/"><u>Avoiding Abrupt Game Closure in Roblox: Fix Tips for PC Users</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-your-workflow-with-windows-11s-widget-toolbar/"><u>Boost Your Workflow with Windows 11'S Widget Toolbar</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-for-on-the-go-users-a-comprehensive-guide-to-activating-it-on-your-mobile-device/"><u>ChatGPT for On-the-Go Users: A Comprehensive Guide to Activating It on Your Mobile Device</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-audio-error-devices-being-used-by-non-targeted-apps/"><u>Clearing Up Audio Error: Devices Being Used by Non-Targeted Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-alternate-pdf-reader-on-windows/"><u>Configuring Alternate PDF Reader on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-expert-guide-to-using-toolbar-on-w11-winpcm/"><u>Elevate Your Productivity: Expert Guide to Using Toolbar on W11 WinPCM</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-tips-for-widget-notifications-on-win-11/"><u>Essential Tips for Widget Notifications on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-effective-policy-reports-using-gpresult/"><u>Expert Tips for Effective Policy Reports Using GPResult</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ffmpeg-audio-review-can-ffmpeg-extract-audio-in-original-format-for-2024/"><u>FFmpeg Audio Review  Can FFmpeg Extract Audio in Original Format for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reprogram-windows-11s-preferred-programs-effectively/"><u>How to Reprogram Windows 11'S Preferred Programs Effectively</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-note-30i-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Note 30i to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-reno-8t-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo Reno 8T 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-quick-snapchat-lens-creation-two-simple-techniques-for-2024/"><u>Mastering Quick Snapchat Lens Creation  Two Simple Techniques for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mastering-software-development-with-stellars-essential-article-compendium-and-do-it-yourself-hacks/"><u>Mastering Software Development with Stellar's Essential Article Compendium and Do-It-Yourself Hacks</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chrome-challenges-fix-common-web-problems-on-windows-pc/"><u>Navigating Chrome Challenges: Fix Common Web Problems on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-package-unopenable-woes/"><u>Navigating Through Windows Package Unopenable Woes</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-hell-let-loose-pc-instability-and-game-crash-issues/"><u>Overcoming Hell Let Loose PC Instability and Game Crash Issues</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pristineai-designs-crafting-visuals-with-ai-for-2024/"><u>PristineAI Designs  Crafting Visuals with AI for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-path-to-success-top-7-boosting-tools-for-window-11/"><u>Prolific Path to Success: Top 7 Boosting Tools for Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quicker-quests-9-strategies-to-prevent-wwe-2k23-crashes/"><u>Quicker Quests: 9 Strategies to Prevent WWE 2K23 Crashes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-credential-manager-login-issues/"><u>Resolve Credential Manager Login Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-common-errors-in-office-app-activation-on-pc/"><u>Resolving Common Errors in Office App Activation on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-address-game-pass-connection-errors-in-windows/"><u>Techniques to Address Game Pass Connection Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblock-windows-task-scheduler-issues-quickly/"><u>Unblock Windows Task Scheduler Issues Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unbroken-streams-winos-stability-verification-guide/"><u>Unbroken Streams: WinOS Stability Verification Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-solving-microsoft-offices-0x80041015/"><u>Understanding & Solving Microsoft Office's 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-win11-potential-essential-commands-and-tricks-with-nircmd/"><u>Unlock Win11 Potential: Essential Commands & Tricks with NirCmd</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-virtual-potential-hyper-v-for-windows-11-users/"><u>Unlocking Virtual Potential: Hyper-V for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/when-windows-acts-up-reboot-or-reset/"><u>When Windows Acts Up, Reboot or Reset?</u></a></li>
</ul></div>
