---
title: Technique to Automate Microsoft Word's Attachment Display in Read-Only View
date: 2024-08-08T06:10:13.846Z
updated: 2024-08-09T06:10:13.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Technique to Automate Microsoft Word's Attachment Display in Read-Only View
excerpt: This Article Describes Technique to Automate Microsoft Word's Attachment Display in Read-Only View
keywords: Auto Word Attachments,Read Only Word Display,Email Read Mode,Word Automation Trick,Save As PDF Adjustment,Microsoft Attachment View,Optimize Word Read-Only
thumbnail: https://thmb.techidaily.com/95080ee1192e9ec99602ccecb30de670936b2e86c3bafe48586480f26bd563d2.jpg
---

## Technique to Automate Microsoft Word's Attachment Display in Read-Only View

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

 Once you complete the above steps, Word will open email attachments in reading view by default.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-3-ways-to-record-discord-live-stream-for-2024/"><u>[New] 3 Ways to Record Discord Live Stream for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-cut-through-the-noise-with-these-top-10-yt-short-standout-strategies-for-2024/"><u>[New] Cut Through the Noise with These Top 10 YT Short Standout Strategies for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-the-comprehensive-guide-to-farming-on-ginger-islet/"><u>[New] In 2024, The Comprehensive Guide to Farming on Ginger Islet</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-stunning-photography-10-top-grid-software/"><u>[Updated] 2024 Approved  Stunning Photography  10 Top Grid Software</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-12-top-tier-cameras-that-will-transform-your-vlogging-experience/"><u>[Updated] In 2024, 12 Top-Tier Cameras That Will Transform Your Vlogging Experience</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-quick-method-retain-tweets-video-on-your-android-gadget-for-2024/"><u>[Updated] Quick Method  Retain Tweets' Video on Your Android Gadget for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-v30-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo V30 by Name | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-realme-gt-3-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Realme GT 3 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-firewall-settings-integration-into-windows-11s-ui/"><u>Advanced Firewall Settings Integration Into Windows 11'S UI</u></a></li>
<li><a href="https://windows11.techidaily.com/assessment-of-differences-onsite-vs-cloud-based-windows-downloads/"><u>Assessment of Differences: Onsite vs Cloud-Based Windows Downloads</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-clashes-in-windows-desktop-ordering/"><u>Avoid Clashes in Windows Desktop Ordering</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-classics-seamless-integration-of-achievements-using-retroarch-software/"><u>Boosting Classics: Seamless Integration of Achievements Using Retroarch Software</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/bringing-text-to-life-dynamic-animated-content-on-ig-stories/"><u>Bringing Text to Life  Dynamic Animated Content on IG Stories</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-windows-lsa-disablement-warning/"><u>Bypassing the Windows LSA Disablement Warning</u></a></li>
<li><a href="https://tech-haven.techidaily.com/demystifying-transformers-in-nlp-bert-and-gpt-examined/"><u>Demystifying Transformers in NLP: BERT & GPT Examined</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-for-accessing-windows-11s-policy-editor/"><u>Easy Steps for Accessing Windows 11'S Policy Editor</u></a></li>
<li><a href="https://fox-info.techidaily.com/effortless-photo-tidying-up-top-6-iphone-object-removing-programs-for-2024/"><u>Effortless Photo Tidying Up  Top 6 iPhone Object-Removing Programs for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-system-performance-essential-tips-for-installing-optional-windows-components/"><u>Elevate Your System Performance: Essential Tips for Installing Optional Windows Components</u></a></li>
<li><a href="https://windows11.techidaily.com/esd-to-iso-converting-esd-files-in-windows/"><u>ESD to ISO: Converting ESD Files in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-the-time-windows-11-spends-in-shutdown-with-ongoing-jobs/"><u>Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-11-taskbar-date-and-time-display/"><u>Fine-Tuning Windows 11 Taskbar Date and Time Display</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-custom-snap-layouts-in-windows-with-powertoys/"><u>How to Create Custom Snap Layouts in Windows With PowerToys</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-13-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quiet-browser-alerts-chrome-guide-for-windows/"><u>How to Quiet Browser Alerts: Chrome Guide for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-beats-and-bites-mastering-music-in-instagram-stories/"><u>In 2024, Beats & Bites  Mastering Music in Instagram Stories</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-your-infinix-hot-30i-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Infinix Hot 30i Lock Screen Password</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-selecting-cinematic-slices-top-10-for-editing-mastery/"><u>In 2024, Selecting Cinematic Slices  Top 10 for Editing Mastery</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-every-user-dialogue-a-step-in-chatgpts-evolution/"><u>Is Every User Dialogue a Step in ChatGPT's Evolution?</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-directx-repairs-a-comprehensive-tutorial-for-cod-mw2-players/"><u>Master DirectX Repairs: A Comprehensive Tutorial for CoD MW2 Players</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fixes-for-windows-1011-photography-problems/"><u>Mastering Fixes for Windows 10/11 Photography Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-powertoys-navigating-globally-peering-deeply/"><u>Mastering PowerToys: Navigating Globally, Peering Deeply</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-w11-printer-error-fixes-related-to-ad-ds/"><u>Mastering W11 Printer Error Fixes Related to AD DS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-nuances-of-widget-alerts-in-windows/"><u>Navigating the Nuances of Widget Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-onedrive-error-0x80070194/"><u>Navigating Through Windows' OneDrive Error 0X80070194</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-errors-in-google-nearby-share-app/"><u>Navigating Windows Errors in Google Nearby Share App</u></a></li>
<li><a href="https://windows11.techidaily.com/neutralize-required-condition-red-flags-in-win11/"><u>Neutralize Required Condition Red Flags in Win11</u></a></li>
<li><a href="https://howto.techidaily.com/oppo-find-x7-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo Find X7 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missed-files-in-steam-and-windows-11/"><u>Overcoming Missed Files in Steam & Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xc0f1103f-flaw-with-nvidias-windows-software/"><u>Overcoming XC0F1103F Flaw with Nvidia's Windows Software</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-user-interaction-essential-modifications-for-windows-11s-taskbar/"><u>Perfecting User Interaction: Essential Modifications for Windows 11'S Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-the-already-in-use-local-device-name-mistake-on-pcs/"><u>Remedy the 'Already in Use' Local Device Name Mistake on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/1719349405273-say-no-to-incompatibility-quick-solutions-for-vistawindows-7-users/"><u>Say No to Incompatibility: Quick Solutions for Vista/Windows 7 Users.</u></a></li>
<li><a href="https://windows11.techidaily.com/shine-the-light-how-to-make-your-cursor-more-noticeable-on-win1011/"><u>Shine the Light: How to Make Your Cursor More Noticeable on Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-internal-errors-during-remote-connections-in-windows-11/"><u>Solving Internal Errors During Remote Connections in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-to-update-windows-spotlight-imagery/"><u>Step-by-Step to Update Windows Spotlight Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-resolving-zero-x-error-in-windows-email-app/"><u>Steps for Resolving Zero X Error in Windows Email App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-funny-image-memes/"><u>The Ultimate Guide to Funny Image Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-microsoft-teams-stumbling-block-80080300-on-w11/"><u>Triumph over Microsoft Teams' Stumbling Block #80080300 on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-troubled-windows-credentials/"><u>Triumph over Troubled Windows Credentials</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-offline-setting-up-on-disconnected-pcs/"><u>Win11 Offline: Setting Up on Disconnected PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-preserves-7-ancient-features-for-modern-use/"><u>Windows 11 Preserves 7 Ancient Features for Modern Use</u></a></li>
<li><a href="https://windows11.techidaily.com/winphone-users-decide-between-unison-and-phone-link-apps/"><u>WinPhone Users: Decide Between Unison and Phone Link Apps</u></a></li>
</ul></div>
