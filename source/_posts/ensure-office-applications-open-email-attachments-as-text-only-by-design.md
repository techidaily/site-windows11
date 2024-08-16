---
title: Ensure Office Applications Open Email Attachments as Text Only by Design
date: 2024-08-15T15:33:57.001Z
updated: 2024-08-16T15:33:57.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensure Office Applications Open Email Attachments as Text Only by Design
excerpt: This Article Describes Ensure Office Applications Open Email Attachments as Text Only by Design
keywords: Email Text-Only Settings,Outlook Readability,Prevent Spam Attachment,Email Attachment Safety,Secure Office Mailing,Avoid Malware in Attachments,Filter Email Content
thumbnail: https://thmb.techidaily.com/08702778e13a63a51dde09a4b23ab862a68808a42d3ab8c5759ae25bd6bbada4.jpg
---

## Ensure Office Applications Open Email Attachments as Text Only by Design

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
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
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-alternative-video-editor-tips-beyond-youtube/"><u>[New] 2024 Approved  Alternative Video Editor Tips  Beyond YouTube</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-regaining-exclusive-snap-privacy/"><u>[New] Regaining Exclusive Snap Privacy</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-a-simple-path-to-enhanced-youtube-sign-ups-create-animated-subscription-bar-using-filmora/"><u>[Updated] 2024 Approved  A Simple Path to Enhanced YouTube Sign-Ups - Create Animated Subscription Bar Using Filmora</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-crafting-the-perfect-tiktok-image-with-simple-hacks/"><u>[Updated] 2024 Approved  Crafting the Perfect TikTok Image with Simple Hacks</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-fb-to-mp3-online-tools-for-video-to-music-conversion/"><u>[Updated] In 2024, FB to MP3  Online Tools for Video to Music Conversion</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-learn-the-art-of-virality-infuse-insta-reels-with-tiktok-charm/"><u>2024 Approved  Learn the Art of Virality  Infuse Insta Reels With TikTok Charm</u></a></li>
<li><a href="https://win11-tips.techidaily.com/a-guidetosettingupdarkinterfaceonwinnotepad/"><u>A GuideToSettingUpDarkInterfaceOnWinNotepad</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/boost-performance-geforce-210-update-for-w11/"><u>Boost Performance: GeForce 210 Update for W11</u></a></li>
<li><a href="https://win-dash.techidaily.com/compatible-drivers-enhancing-your-gaming-experience-with-an-updated-amd-radeon-hd-7870-on-windows-11/"><u>Compatible Drivers: Enhancing Your Gaming Experience with an Updated AMD Radeon HD 7870 on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-meizu-21-pro-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Meizu 21 Pro</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/essential-tutorial-how-to-install-snapchat-on-macos-for-2024/"><u>Essential Tutorial  How to Install Snapchat on macOS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-fatigued-performance-in-win10plusedge-browser/"><u>Fixing Fatigued Performance in Win10+Edge Browser</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-a-constant-windows-printer/"><u>Guidelines for a Constant Windows Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonizing-windows-and-wsl-after-a-major-update/"><u>Harmonizing Windows and WSL After a Major Update</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-automatic-deletion-for-effortless-disk-space-maintainance/"><u>Harnessing Automatic Deletion for Effortless Disk Space Maintainance</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-immediuate-switch-text-editor-to-a-dark-scheme-windows-11/"><u>How to Immediuate Switch Text Editor to a Dark Scheme, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reactivate-a-unresponsive-windows-start-button/"><u>How to Reactivate a Unresponsive Window's Start Button</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-motorola-edge-40-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Motorola Edge 40 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-infinix-note-30-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Infinix Note 30 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-enhancing-zoom-talks-with-advanced-filter-techniques/"><u>In 2024, Enhancing Zoom Talks with Advanced Filter Techniques</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-outro-crafting-made-easy-the-best-free-guide-top-6/"><u>In 2024, Outro Crafting Made Easy - The Best Free Guide (Top 6)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Realme 11 Pro+? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-encore-list-top-pick-for-digital-music-tones/"><u>In 2024, The Encore List  Top Pick for Digital Music Tones</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-fingerprint-lock-apps-to-lock-your-poco-f5-5g-phone-by-drfone-android/"><u>In 2024, Top 10 Fingerprint Lock Apps to Lock Your Poco F5 5G Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-tricks-for-completing-100-windows-update/"><u>Masterful Tricks for Completing 100%% Windows Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-installation-of-the-latest-win11-version-22h2-update/"><u>Mastering Installation of the Latest Win11 Version 22H2 Update</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/mastering-social-media-tweeting-videos-to-facebook-for-2024/"><u>Mastering Social Media  Tweeting Videos to Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-your-way-through-playstation-1-games-in-windows-with-duckstation/"><u>Mastering Your Way Through PlayStation 1 Games in Windows with Duckstation</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-reinstate-working-utorrent-installer-in-various-windows-versions/"><u>Methods to Reinstate Working uTorrent Installer in Various Windows Versions</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-windows-11-like-a-pro-essential-search-hacks-revealed/"><u>Navigate Windows 11 Like a Pro: Essential Search Hacks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-native-tools-for-disk-replication/"><u>Navigating Native Tools for Disk Replication</u></a></li>
<li><a href="https://fox-blue.techidaily.com/navigating-the-world-of-audio-editing-with-garageband/"><u>Navigating the World of Audio Editing with GarageBand</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-setbacks-due-to-recent-windows-installation/"><u>Overcoming Setbacks Due to Recent Windows Installation</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/quick-twitterscape-snag-gifs-with-these-tips-for-2024/"><u>Quick Twitterscape  Snag Gifs with These Tips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-faster-execution-of-excel-on-windows-pcs/"><u>Reactivating Faster Execution of Excel on Windows PCs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolving-d3dx933dll-file-not-found-a-step-by-step-guide/"><u>Resolving d3dx9_33.dll File Not Found: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-updates-error-xcode-0x80246007/"><u>Solutions for Fixing Windows Updates Error – XCode 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-file-transfer-problems-on-windows-1011/"><u>Solutions to File Transfer Problems on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-audio-recorder-crash-9999-on-windows-platforms/"><u>Solving Audio Recorder Crash 9999 on Windows Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-regaining-router-interface-on-pc/"><u>Strategies for Regaining Router Interface on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-boot-sequence-customizing-timeout-window-11/"><u>Streamlining Boot Sequence: Customizing Timeout Window 11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-system-flush-steam-dns-cache-efficiently/"><u>Streamlining Your System: Flush Steam DNS Cache Efficiently</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-search-highlights-onoff-windows-11-guide/"><u>Switching Search Highlights On/Off: Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-windows-files-delete-confirmations/"><u>Tailoring Windows Files' Delete Confirmations</u></a></li>
<li><a href="https://windows11.techidaily.com/the-experts-guide-to-navigating-with-windows-narrator/"><u>The Expert's Guide to Navigating with Windows Narrator</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-c300-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from C300.</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-10-youtube-video-editing-tips-for-beginner-editors/"><u>Top 10 YouTube Video Editing Tips for Beginner Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/top-6-strengths-of-win11-outshining-macos/"><u>Top 6 Strengths of Win11 Outshining MacOS</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-win-rpc-errors-a-5-step-guide/"><u>Troubleshooting Win RPC Errors - A 5-Step Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ultimate-guide-to-m-mookka-1000a-the-18000mah-vehicle-booster-a-comprehensive-review/"><u>Ultimate Guide to M MOOKKA 1000A - The 18000mAh Vehicle Booster: A Comprehensive Review</u></a></li>
<li><a href="https://windows11.techidaily.com/unchained-gpt-on-your-machine-using-freedomgpt/"><u>Unchained GPT on Your Machine: Using FreedomGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-development-power-with-windows-11s-dev-drive-insights/"><u>Uncovering Development Power with Windows 11’S Dev Drive Insights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-lightroom-for-android-a-complete-guide-for-2024/"><u>Unveiling Lightroom for Android  A Complete Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/ups-and-downs-on-the-desktop-frontier-comparing-w10-and-w11/"><u>Ups and Downs on the Desktop Frontier: Comparing W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/validate-your-gpus-mettle-using-these-6-tools-on-pc/"><u>Validate Your GPU's Mettle Using These 6 Tools on PC</u></a></li>
</ul></div>
