---
title: Strategies for Disabling OneDrive Icon on Windows 11 Explore
date: 2024-07-29T04:19:27.713Z
updated: 2024-07-30T04:19:27.713Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Disabling OneDrive Icon on Windows 11 Explore
excerpt: This Article Describes Strategies for Disabling OneDrive Icon on Windows 11 Explore
keywords: Win11 Stop OneDrive,Turn Off Drivе Icon,OneDrive Removal Steps,Disable OneDrive Windows,Hide OneDrive Icon W11,Stop OneDrive on PC,OneDrive Icon Control
thumbnail: https://thmb.techidaily.com/21bab4f1638ef86b0e7d7d0a727f5b3a087b8ff6581d699ffea02276f1c5717e.jpg
---

## Strategies for Disabling OneDrive Icon on Windows 11 Explore

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on [removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you [create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## How to Show the OneDrive Icon Again in File Explorer

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-complying-with-aspect-ratios-in-tweets/"><u>[New] 2024 Approved  Complying with Aspect Ratios in Tweets</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-mac-efficiency-for-academics-audio-record-of-classroom-learning/"><u>[New] 2024 Approved  Mac Efficiency for Academics  Audio Record of Classroom Learning</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-bringing-imagery-elements-into-harmony/"><u>[New] Bringing Imagery Elements Into Harmony</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-free-ways-to-liven-up-static-video-texts/"><u>[New] In 2024, FREE Ways to Liven Up Static Video Texts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-web-supplement-fb-stories-downloader/"><u>[New] Web Supplement  FB Stories Downloader</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-10plus-preferred-no-pay-webm-player-options-for-2024/"><u>[Updated] 10+ Preferred No-Pay WebM Player Options for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-beautys-brightest-stars-youtube-personalities-to-follow/"><u>[Updated] 2024 Approved  Beauty's Brightest Stars  YouTube Personalities to Follow</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-comprehensive-guide-to-focusing-on-your-iphone-camera/"><u>[Updated] A Comprehensive Guide to Focusing on Your iPhone Camera</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-everything-you-need-to-know-about-io-screen-recorder-for-2024/"><u>[Updated] Everything You Need to Know About IO Screen Recorder for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-innovative-brainstroming-techniques-for-channels-names/"><u>[Updated] Innovative Brainstroming Techniques for Channels' Names</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-revamp-your-instagram-showcase-with-top-10-insights-for-2024/"><u>[Updated] Revamp Your Instagram Showcase with Top 10 Insights for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-top-4-strategies-for-success-in-instagram-loop-creation-for-2024/"><u>[Updated] Top 4 Strategies for Success in Instagram Loop Creation for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-crafting-a-captivated-audience-with-strategic-voiceovers/"><u>2024 Approved  Crafting a Captivated Audience with Strategic Voiceovers</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/7th-anniversary-mondly-a-global-language-leader/"><u>7Th Anniversary: Mondly, A Global Language Leader</u></a></li>
<li><a href="https://windows11.techidaily.com/8-ways-to-fix-the-windows-desktop-when-it-turns-pink-or-purple/"><u>8 Ways to Fix the Windows Desktop When It Turns Pink or Purple</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-the-voice-recorder-keyboard-shortcuts-on-windows-11/"><u>A Guide to the Voice Recorder Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boot-up-solutions-navigating-4-pct-routes/"><u>Boot-Up Solutions: Navigating 4 PCT Routes</u></a></li>
<li><a href="https://windows11.techidaily.com/bringing-business-efficiency-installing-ms-works-on-windows/"><u>Bringing Business Efficiency: Installing MS Works on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/building-a-personalized-voice-transcription-tool-on-windows-using-ahk/"><u>Building a Personalized Voice Transcription Tool on Windows Using AHK</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-package-registration-errors-a-guide-to-photography-on-windows-11/"><u>Correcting Package Registration Errors: A Guide to Photography on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/craft-compelling-youtube-titles-faster-than-ever-for-2024/"><u>Craft Compelling YouTube Titles Faster Than Ever for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-a-unique-windows-11-search-interface/"><u>Crafting a Unique Windows 11 Search Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-productivity-enable-a-search-bar-on-win11s-taskbar/"><u>Elevate Your Productivity: Enable a Search Bar on Win11's Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-fixing-pubg-saving-issues-win/"><u>Expert Tips for Fixing PUBG Saving Issues (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-on-windows-platform/"><u>Fixing Inaccessible Files on Windows Platform</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-motorola-edge-40-neo-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Motorola Edge 40 Neo Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-non-empty-directory-error-code-0x80070091-in-win11/"><u>How to Correct Non-Empty Directory Error (Code: 0X80070091) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-update-notifications-on-windows/"><u>How to Disable Update Notifications on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-itel-p55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/iconic-youtube-recognition-click-counter-awards/"><u>Iconic YouTube Recognition - Click Counter Awards</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-can-life360-track-you-when-your-nubia-red-magic-9-proplus-is-off-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track You When Your Nubia Red Magic 9 Pro+ is off? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-itel-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Itel Devices</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-vivo-v29-pro-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Vivo V29 Pro Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://facebook.techidaily.com/invisible-interactions-friendlist-coverage/"><u>Invisible Interactions: Friendlist Coverage</u></a></li>
<li><a href="https://windows11.techidaily.com/making-your-notes-pop-in-win-1011-os/"><u>Making Your Notes Pop in Win 10/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-apex-servers-on-pc-7-ways-to-fix-no-server-errors-(156-chars/"><u>Mastering Apex Servers on PC: 7 Ways to Fix 'No Server' Errors (<156 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windowsapps-access-a-step-by-step-guide/"><u>Mastering WindowsApps Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/must-use-3d-paint-shortcuts-compiled/"><u>Must-Use 3D Paint Shortcuts Compiled</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-past-share-permission-hurdles-in-win-os/"><u>Navigate Past Share Permission Hurdles in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-transition-from-ical-to-windows-calendar/"><u>Navigating the Transition: From iCal to Windows Calendar</u></a></li>
<li><a href="https://windows11.techidaily.com/new-dawn-for-old-gameshells-atlasos/"><u>New Dawn For Old Gameshells - AtlasOS</u></a></li>
<li><a href="https://windows11.techidaily.com/new-horizons-in-customizing-win11-ui/"><u>New Horizons in Customizing Win11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-rpc-failure-essential-steps-for-win-users/"><u>Overcoming RPC Failure: Essential Steps for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-stability-issues-with-vscode-on-w11/"><u>Preventing Stability Issues with VSCode on W11</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-slack-notifications-fixes-for-windows-11/"><u>Reclaim Your Slack Notifications: Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-a-muted-windows-taskbar/"><u>Remedying a Muted Windows Taskbar</u></a></li>
<li><a href="https://techidaily.com/repair-broken-or-corrupt-video-files-of-redmi-note-12t-pro-by-stellar-video-repair-mobile-video-repair/"><u>Repair broken or corrupt video files of Redmi Note 12T Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-disabled-windows-shadow-copies/"><u>Resolving Disabled Windows Shadow Copies</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-vintage-directx-apps-using-modernized-dxvk-features/"><u>Revitalizing Vintage DirectX Apps Using Modernized DXVK Features</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-system-integration-enable-windows-subsystem-for-linux/"><u>Seamless System Integration: Enable Windows Subsystem for Linux</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-workflows-automate-using-to-dot-plus-ifttt/"><u>Simplify Workflows: Automate Using To-Dot + IFTTT</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/soundscapes-free-from-restrictions-for-2024/"><u>Soundscapes Free From Restrictions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-keep-windows-notepad-running-without-interruptions/"><u>Strategies to Keep Windows Notepad Running without Interruptions</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-day-best-to-do-lists-on-pc/"><u>Streamlining Your Day: Best To-Do Lists on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-creating-sequences-of-directories-simultaneously-in-windows/"><u>The Art of Creating Sequences of Directories Simultaneously in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-hd-strategy-for-classics-gaming-on-windows-via-scummvm/"><u>The Ultimate HD Strategy for Classics Gaming on Windows via ScummVM</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/top-10-google-cardboards-most-stunning-vr-games-for-2024/"><u>Top 10  Google Cardboard's Most Stunning VR Games for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-folders-tricks-for-enhanced-efficiency/"><u>Top 5 Windows Folders Tricks for Enhanced Efficiency</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-samsung-galaxy-a25-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Samsung Galaxy A25 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/windows-movie-maker-6-download-and-install-in-minutes/"><u>Windows Movie Maker 6  Download and Install in Minutes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/youtuber-in-training-mobile-livestream-without-1000plus-subs/"><u>YouTuber in Training  Mobile Livestream WITHOUT 1000+ Subs</u></a></li>
</ul></div>
