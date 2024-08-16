---
title: "Customize Your Experience: Altering Device Settings in Windows 11"
date: 2024-08-15T16:11:11.406Z
updated: 2024-08-16T16:11:11.406Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Customize Your Experience: Altering Device Settings in Windows 11"
excerpt: "This Article Describes Customize Your Experience: Altering Device Settings in Windows 11"
keywords: Win11 Setup,Custom Window Prefs,Devices Config,Personal Windows,UI Tweaks Windows,Adjust Windows,Tailor Windows Experience
thumbnail: https://thmb.techidaily.com/e703390679e2e9d8302a199135d745cf8f0f1e64473e58f7a002cd7e0675d8bb.jpg
---

## Customize Your Experience: Altering Device Settings in Windows 11

 Windows 11 offers users the flexibility to change their device usage options to suit their own needs. If you skipped the initial Windows setup and want to change your Device Usage settings, read on. The article covers two methods for changing device usage options: using system settings and a reg file.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.

## What Are the Device Usage Options on Windows?

 Device Usage Options allow you to customize your Windows experience by setting preferences for how ads are displayed. Microsoft also provides tips & suggestions and personalizes recommendations for you. Depending on your choice, Windows presents you with different types of information and services.

 Here's how you to use your device to get tips, ads, and Microsoft suggestions.

* **Gaming:** Windows shows tips and suggestions about popular games and upcoming releases.
* **Family:** If you plan on using your device with family members, this feature allows each family member to have their profile. Also, customize safety settings and connect with family members.
* **Creativity:** This option gives tips on how to make videos and photographs that bring ideas to life.
* **School:** Choose this option for the best Windows experience as a student. Windows provides productivity tips, organization tools, and collaboration features for taking notes, writing essays, and collaborating on projects.
* **Entertainment:** This option provides tips about apps and services to watch videos, browse the web, connect on social media, and more.
* **Business:** Do you want to use your device for work? With this option, Windows offers tips on managing your business, tracking expenses, and providing customer service.

 Now that you know what Device Usage Options are, here's how to change them in Windows.

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
## 1\. Using Windows Settings

 Changing Device Usage Options on Windows is easy. There are two ways to do it - using System Settings or through a reg file. First, let's look at how to change Device Usage Options using Windows Settings.

 To get started, press **Win + I** on your keyboard. This will open the System Settings. From the left sidebar, click on the **Personalisation** tab. Scroll down in the right pane and click **Device usage**.

![Change Device Usage on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-device-usage-on-windows-11.jpg)

 On the next page, look for your preferred Device Usage option and toggle it on.

## 2\. Using a REG File

 If you're [unable to open the System Settings window or if it isn't working](https://www.makeuseof.com/fixes-unable-to-open-windows-settings/), use a reg file instead. A reg file is a registry key file that helps you tweak Windows settings.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
### Gaming Device Usage Options

 To create a reg file for your desired Device Usage Options, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and copy-paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Now click the **File** menu and select **Save as** from the options list. Choose **All files** from the **Save as type** drop-down menu and save it with a **.reg** extension to your desktop.

![Change Gaming Device Usage Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-gaming-device-usage-options.jpg)
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply the settings, double-click the reg file. This will turn on the Device usage options for Gaming.

 If you want to turn off this option, create a new reg file and paste the following:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\gaming]  
"Intent"=dword:00000000`

 Now save it with the **.reg** extension as above and double-click to apply.

 To turn on Device usage options for other categories, create separate reg files with the corresponding code then apply them in the same way. Here's a list of each .reg file's contents:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
### Family Device Usage Options

 For the Family option:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\family]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
### Creativity Device Usage Options

 For Creativity:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\creative]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### School Device Usage Options

 For School usage:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\schoolwork]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Entertainment Device Usage Options

 If you want the Entertainment options:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\entertainment]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

### Business Device Usage Options

 And finally, for the Business side of things:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\business]  
"Intent"=dword:00000001  
"Priority"=dword:00000000  
  
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\CloudExperienceHost\Intent\OffDeviceConsent]  
"accepted"=dword:00000001`

 Once you have created the reg file for the Device Usage Option, double-click to apply. Now when you open System **Settings** \> **Personalisation** \> **Device Usage**, you should see the option turned on.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Configure Your Device’s Usage Options in a Flash

 With the right Device Usage Options, Microsoft will show you relevant tips, advertisements, and recommendations. If you're a student, entertainer, or business owner, you now know two methods to change your Device Usage options in Windows 11\.

 Before we dig in, let's see what Device Usage Options are and how they affect your Windows experience.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harmonizing-your-spotify-queue-with-youtube-music-catalogs/"><u>[New] 2024 Approved  Harmonizing Your Spotify Queue with YouTube Music Catalogs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-saving-pc-views-with-a-single-click-win/"><u>[New] 2024 Approved  Saving PC Views with a Single Click (Win)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-the-ultimate-guide-incorporating-facebook-live-into-websites/"><u>[New] 2024 Approved  The Ultimate Guide  Incorporating Facebook LIVE Into Websites</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capturing-every-frame-a-deep-dive-into-apowersoft-for-pcs/"><u>[New] Capturing Every Frame  A Deep Dive Into Apowersoft for PCs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-cultivate-connections-agrigames-to-gather-friends-on-farms/"><u>[New] In 2024, Cultivate Connections  AgriGames to Gather Friends on Farms</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-art-of-blending-music-into-your-ig-visuals/"><u>[New] In 2024, The Art of Blending Music Into Your IG Visuals</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-ultimate-audio-alerts-high-quality-pages/"><u>[New] Ultimate Audio Alerts  High-Quality Pages</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-fraps-screen-recorder-review/"><u>[Updated] Fraps Screen Recorder Review</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-innovative-snapchat-strategies-the-ultimate-list-for-2024/"><u>[Updated] Innovative Snapchat Strategies  The Ultimate List for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-revolutionize-your-tiktok-videos-the-ultimate-filter-list/"><u>[Updated] Revolutionize Your TikTok Videos  The Ultimate Filter List</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-array-of-unique-video-cameras-by-type/"><u>2024 Approved  Array of Unique Video Cameras by Type</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unveiling-youtube-live-an-overview-of-thumbnails/"><u>2024 Approved  Unveiling YouTube Live  An Overview of Thumbnails</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/5-easy-ways-to-record-youtube-videos/"><u>5 Easy Ways to Record YouTube Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/6-expert-windows-programs-for-video-editors/"><u>6 Expert Windows Programs for Video Editors</u></a></li>
<li><a href="https://windows11.techidaily.com/6-underestimated-downsides-of-saving-on-activation-keys/"><u>6 Underestimated Downsides of Saving on Activation Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/a-compreenasian-approach-to-fixing-winget-on-windows-11/"><u>A Compreenasian Approach to Fixing Winget on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-step-by-step-guide-turning-viral-soundtracks-into-personal-ringtones-for-2024/"><u>A Step-by-Step Guide  Turning Viral Soundtracks Into Personal Ringtones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-your-typing-on-win-1011-top-7-tricks-revealed/"><u>Accelerate Your Typing on WIN 10/11: Top 7 Tricks Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-edge-browsing-performance-on-win10win11/"><u>Accelerating Edge Browsing Performance on Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-tools-to-clipboard-access-for-easier-compatibility-fixes/"><u>Adding Tools to Clipboard Access for Easier Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-one-side-output-in-windows-10-headphones/"><u>Addressing One Side Output in Windows 10 Headphones</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-settings-for-visible-sticky-notes/"><u>Adjusting Windows Settings for Visible Sticky Notes</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-locating-ip-and-mac-in-windows-ps/"><u>Advanced Techniques: Locating IP & MAC in Windows PS</u></a></li>
<li><a href="https://windows11.techidaily.com/advancing-text-recall-on-windows-11-through-enhanced-clipping/"><u>Advancing Text Recall on Windows 11 Through Enhanced Clipping</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-motorola-moto-g13-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Motorola Moto G13? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-panic-recover-lost-data-with-these-steps/"><u>Avoid Panic, Recover Lost Data with These Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/becoming-an-admin-in-pc-command-console/"><u>Becoming an Admin in PC Command Console</u></a></li>
<li><a href="https://article-posts.techidaily.com/best-10-apps-to-add-stickers-to-photos-for-iphone-and-android-for-2024/"><u>Best 10 Apps to Add Stickers to Photos for iPhone and Android for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-vivo-v29-pro-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-windows-backups-back-to-basics/"><u>Bringing Windows Backups Back to Basics</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-11-mode-switch-failures/"><u>Bypassing Windows 11 Mode Switch Failures</u></a></li>
<li><a href="https://windows11.techidaily.com/captivating-holiday-vistas-through-designed-panes/"><u>Captivating Holiday Vistas Through Designed Panes</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-motorola-edge-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/character-inspector-easy-steps-for-windows-11/"><u>Character Inspector: Easy Steps for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/chkdsk-sfc-and-dism-windows-tools-unveiled-and-explained/"><u>CHKDSK, SFC & DISM: Windows Tools Unveiled and Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-theme-makeovers-for-windows-11/"><u>Christmas Theme Makeovers for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-storage-alerts-and-errors-on-windows/"><u>Clearing Up Storage Alerts & Errors on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/compulsory-uninstall-guide-for-windows-11-printers/"><u>Compulsory Uninstall Guide for Windows 11 Printers</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-account-lockout-reset-in-successive-login-attempts-windows-1011/"><u>Configuring Account Lockout Reset in Successive Login Attempts Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/confronting-and-overcoming-failed-capture-issues-in-windows/"><u>Confronting and Overcoming Failed Capture Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-win11s-startup-configuration-for-unmatched-performance/"><u>Conquer Win11's Startup Configuration for Unmatched Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-device-disabled-issue-with-error-code-22-on-windows-11/"><u>Correcting Device Disabled Issue with Error Code 22 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-install-access-denied-windows-setup-issue/"><u>Correcting Install Access Denied Windows Setup Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/cursor-on-display-redeeming-darkened-win1011-screens/"><u>Cursor on Display: Redeeming Darkened Win10/11 Screens</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-through-the-frustration-swift-solutions-for-ms-teams-error-80080300-in-win11/"><u>Cut Through the Frustration: Swift Solutions for MS Teams Error 80080300 in Win11</u></a></li>
<li><a href="https://facebook.techidaily.com/cyber-risks-in-casual-social-media-quizzes-analyzed/"><u>Cyber Risks in Casual Social Media Quizzes Analyzed</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-windows-11-editions-matching-home-to-pro-features/"><u>Decoding Windows 11 Editions: Matching Home to Pro Features</u></a></li>
<li><a href="https://windows11.techidaily.com/decreasing-cpu-load-in-setup-hosts/"><u>Decreasing CPU Load in Setup Hosts</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-the-spiritual-command-center-of-windows-11/"><u>Delving Into the Spiritual Command Center of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/desktop-dynamics-shift-unveiling-the-latest-os-features/"><u>Desktop Dynamics Shift: Unveiling the Latest OS Features</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-the-world-of-dxvk-essential-knowledge-for-windows-gamers/"><u>Dive Into the World of DXVK: Essential Knowledge for Windows Gamers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/facebook-videos-made-simple-unified-techniques-for-desktop-and-mobile/"><u>Facebook Videos Made Simple  Unified Techniques for Desktop & Mobile</u></a></li>
<li><a href="https://tech-revival.techidaily.com/hearing-from-ai-how-openai-gave-chatgpt-the-ability-to-vocalize-answers/"><u>Hearing From AI: How OpenAI Gave ChatGPT the Ability to Vocalize Answers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-realme-12-pro-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Realme 12 Pro 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-12-mini-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock Apple iPhone 12 mini Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-12-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-tecno-camon-30-pro-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Tecno Camon 30 Pro 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-extract-focus-from-logitech-cam-feed/"><u>In 2024, Extract Focus From Logitech Cam Feed</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-poco-x5-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Poco X5 Is Unlocked</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-verizon-iphone-14-plus-by-drfone-ios/"><u>In 2024, How to Unlock Verizon iPhone 14 Plus</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-lava-agni-2-5g-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Lava Agni 2 5G Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://fox-that.techidaily.com/master-the-art-of-resetting-your-iphone-techniques-for-immediate-power-off-and-initiating-recovery-settings/"><u>Master the Art of Resetting Your iPhone: Techniques for Immediate Power-Off and Initiating Recovery Settings</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-disk-management-virtual-disk-hiccups/"><u>Rectifying Disk Management Virtual Disk Hiccups</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-90-pro-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor 90 Pro? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Vivo X Flip? | Dr.fone</u></a></li>
</ul></div>
