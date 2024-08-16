---
title: How to Unlock and Edit Files on Win PC
date: 2024-08-15T16:19:17.079Z
updated: 2024-08-16T16:19:17.079Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unlock and Edit Files on Win PC
excerpt: This Article Describes How to Unlock and Edit Files on Win PC
keywords: File Unlock Windows,Edit Win Files,Unlocking PC Files,Editing Win PC Files,Access Locked Windows,Modify Windows Files,Open Windows Edits
thumbnail: https://thmb.techidaily.com/06b7f9bb308a2f230442ff554dbb6dddbc8b32cf4318fa7b79eedb41360cb388.jpg
---

## How to Unlock and Edit Files on Win PC

 When a file is marked as read-only on Windows, you can only view it and not change it in any way. This essentially protects important files from unauthorized changes.

 On Windows, you can set or remove the read-only attribute for a file by modifying its properties. Alternatively, you can also run a command in Command Prompt or Windows PowerShell to do the same. In this article, we take a look at all of them.

## 1\. How to Change the Read-Only Attribute for Files by Modifying Properties

 The easiest way to set or remove the read-only attribute for a file on Windows is by modifying its properties. Here’s how you can go about it.

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to the file for which you want to change the read-only attribute.
2. Right-click on your file and select**Properties** .
3. Under the**General** tab, check or uncheck the**Read-only** box.
4. Click**Apply** followed by**OK** .  
![Change Read-Only Attribute by Modifying Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-by-Modifying-Properties.jpg)

 Note that Windows may prevent you from changing the read-only attribute of a file if you don’t have the necessary permissions to modify the folder in which the file is located. In that case, you must take ownership of the folder first. If you need help, check our guide on[how to take ownership of folders on Windows](<http://How> to Take Ownership of Folders in Windows 10 & 11) .

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Change the Read-Only Attribute for Files Using the Command Prompt

 Command Prompt is one of two command-line tools available on Windows. You can use it to run batch files, troubleshoot errors, and perform various other tasks. It also lets you change a file's read-only attribute with a single command. Here are the steps you need to follow.

1. Right-click on the file for which you want to modify the read-only attribute and select**Copy as path** .
2. Press**Win + X** to open the Power User menu.
3. Select**Terminal (Admin)** from the list.
4. Select**Yes** when the User Account Control (UAC) prompt appears.
5. In the console, type the following command and press**Enter** to set your file as read-only.  
`attrib +r "FilePath"`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-Command-Prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you run the above command, the file will be set as read-only. Likewise, if you want to remove the read-only attribute for a file, use this command:

`attrib -r "FilePath"`

 Once you remove the read-only attribute for a file, you should be able to edit or modify it.

 Like using Command Prompt? Check our guide to learn[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Change the Read-Only Attribute for Files Using Windows PowerShell

 You can also run a command in[Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) to change the read-only attribute for a file.

To change the read-only attribute using PowerShell:

1. Right-click on the file for which you want to change the read-only attribute and select**Copy as path** .
2. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
3. Type**Windows PowerShell** and select**Run as Administrator** .
4. Select**Yes** when the User Account Control (UAC) prompt shows up.
5. Paste the following command and press**Enter** to set your file as read-only.  
`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $True`

 Replace**FilePath** in the above command with the actual path of the file copied earlier.

![Change Read-Only Attribute With PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Change-Read-Only-Attribute-With-PowerShell.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 Alternatively, if you want to remove the read-only attribute for a file, use this command:

`Set-ItemProperty -Path "FilePath" -Name IsReadOnly -Value $False`

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Modifying the Read-Only Attribute for Files on Windows

 It’s worth noting that most system files on Windows will have the read-only attribute by default. So, make sure you don't modify them by mistake. For your other files, you can pick any of the above methods listed above to set or unset their read-only attribute.

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
<li><a href="https://youtube-docs.techidaily.com/ssential-info-on-crafting-engaging-yt-shorts-for-2024/"><u>[New] Essential Info on Crafting Engaging YT Shorts for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-the-right-approach-to-uploading-photos-from-your-device-to-snapchat/"><u>[New] The Right Approach to Uploading Photos From Your Device to Snapchat</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-capture-your-gameplay-essential-webcams-for-twitch-enthusiasts/"><u>[Updated] 2024 Approved  Capture Your Gameplay  Essential Webcams For Twitch Enthusiasts</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-next-gen-consumer-engagement-strategies/"><u>[Updated] 2024 Approved  Next-Gen Consumer Engagement Strategies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unveiling-anonymous-access-to-instagram-story-content-on-desktopstablets-and-smartphones-no-cost/"><u>[Updated] 2024 Approved  Unveiling  Anonymous Access to Instagram Story Content on Desktops/Tablets & Smartphones (No Cost)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-undo-macos-sierras-os-x-transition/"><u>[Updated] How to Undo MacOS Sierra's OS X Transition</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-exploring-ways-to-share-youtube-videos-on-social-media-platforms-fb/"><u>[Updated] In 2024, Exploring Ways to Share YouTube Videos on Social Media Platforms (FB)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-break-down-barriers-to-sound-convert-srt-with-ease-and-precision/"><u>2024 Approved  Break Down Barriers to Sound  Convert SRT with Ease and Precision</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastery-over-supplementary-film-sequences-b-roll/"><u>2024 Approved  Mastery Over Supplementary Film Sequences (B-Roll)</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-seamless-video-to-photo-conversion-for-windows-users/"><u>2024 Approved  Seamless Video-to-Photo Conversion for Windows Users</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-top-pfr-rate-for-sluggish-film-speed/"><u>2024 Approved  Top PFR Rate for Sluggish Film Speed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/backpack-essentials-for-filming-tours/"><u>Backpack Essentials for Filming Tours</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/chorus-cache-secure-and-inspect-audio-recordings/"><u>Chorus Cache  Secure & Inspect Audio Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-sync-apps-for-microsoft-office-holders/"><u>Essential Sync Apps for Microsoft Office Holders</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-sleep-issues-on-windows-11-keys-and-mice/"><u>Fixing Sleep Issues on Windows 11: Keys & Mice</u></a></li>
<li><a href="https://windows11.techidaily.com/fortify-your-files-embrace-weekly-windows-data-saves/"><u>Fortify Your Files: Embrace Weekly Windows Data Saves</u></a></li>
<li><a href="https://windows11.techidaily.com/gameplay-improvement-less-lag-more-frames-in-roblox/"><u>Gameplay Improvement: Less Lag, More Frames in Roblox</u></a></li>
<li><a href="https://windows11.techidaily.com/graphics-correction-in-windows-11-and-11-systems/"><u>Graphics Correction in Windows 11 & 11 Systems</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-windows-inbuilt-display-hardware/"><u>How To Disable Window's Inbuilt Display Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-unreachable-error-connecting-to-game-servers-on-windows/"><u>How to Fix Unreachable Error: Connecting to Game Servers on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xs-to-other-iphone-12-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XS To Other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-top-10-premium-free-iosandroid-live-video-platforms/"><u>In 2024, Explore Top 10 Premium-Free iOS/Android Live Video Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-oppo-find-x7-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Oppo Find X7 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/leveraging-imovie-content-on-the-vimeo-network/"><u>Leveraging iMovie Content on the Vimeo Network</u></a></li>
<li><a href="https://windows11.techidaily.com/lowering-cpuram-in-windows-w11-news-apps/"><u>Lowering CPU/RAM in Windows W11 News Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/mapmyride-reviewed-a-detailed-breakdown/"><u>MapMyRide Reviewed: A Detailed Breakdown</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-awaits-conquering-windows-11-with-group-software-updates-via-winstall/"><u>Mastery Awaits: Conquering Windows 11 with Group Software Updates via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-efficiency-shortcut-placement-in-win11-menu-bar/"><u>Maximizing Efficiency: Shortcut Placement in Win11 Menu Bar</u></a></li>
<li><a href="https://howto.techidaily.com/motorola-moto-g04-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola Moto G04 Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-intrusive-windows-store-operations/"><u>Overcoming Intrusive Windows Store Operations</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo Y78+ (T1) Edition | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-setup-integrating-latest-network-drivers-from-intel-in-fedora/"><u>Precision Setup: Integrating Latest Network Drivers From Intel in Fedora</u></a></li>
<li><a href="https://windows11.techidaily.com/prodigious-windows-11-tools-the-ultimate-7-productivity-list/"><u>Prodigious Windows 11 Tools: The Ultimate 7 Productivity List</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-12-pro-max-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 12 Pro Max Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-audio-transmission-phones-and-windows-integration/"><u>Seamless Audio Transmission: Phones & Windows Integration</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-calc-spotlighting-in-windows-environment/"><u>Securing Calc Spotlighting in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/strategic-approach-to-dispatch-microsoft-store-failure-code-0x0/"><u>Strategic Approach to Dispatch Microsoft Store Failure: Code 0X0</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-reestablishing-functionality-after-failed-ccleaner-on-windows-1011/"><u>Strategies for Reestablishing Functionality After Failed CCleaner on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-track-down-where-your-windows-programs-live/"><u>Strategies to Track Down Where Your Windows Programs Live</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-windows-11-task-manager-interface-elements/"><u>Tailor Windows 11 Task Manager Interface Elements</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-the-start-page-for-task-manager-windows-11/"><u>Tailoring the Start Page for Task Manager (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/title-tweaking-desktop-icons-separation-in-winxiplus10/"><u>Title: Tweaking Desktop Icons' Separation in WinXI+10</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-power-of-taskbar-icon-size-in-w11/"><u>Unlock the Power of Taskbar Icon Size in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-gpu-potentials-on-pc-the-ultimate-6-windows-apps/"><u>Unlocking GPU Potentials on PC: The Ultimate 6 Windows Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-ultimate-gameplay-with-dxvk-in-windows-environment/"><u>Unlocking Ultimate Gameplay with DXVK in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-steps-to-alleviate-server-stumble-on-windows-store/"><u>Unveiling Steps to Alleviate Server Stumble on Windows Store</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-kya-aap-video-call-kar-sakty-ho-translate-any-hindi-video-into-english/"><u>Updated 2024 Approved Kya Aap Video Call Kar Sakty Ho Translate Any Hindi Video Into English</u></a></li>
<li><a href="https://article-helps.techidaily.com/utilizing-zoom-services-directly-from-your-inbox-gmail-edition-for-2024/"><u>Utilizing Zoom Services Directly From Your Inbox - Gmail Edition for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-preservation-moving-old-games-into-windows-11-folder/"><u>Winning at Preservation: Moving Old Games Into Windows 11 Folder</u></a></li>
</ul></div>
