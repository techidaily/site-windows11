---
title: "Optimize Text Entry: Embedding Keyboard Triggers Into Context Menus"
date: 2024-08-27T16:11:03.677Z
updated: 2024-08-28T16:11:03.677Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Text Entry: Embedding Keyboard Triggers Into Context Menus"
excerpt: "This Article Describes Optimize Text Entry: Embedding Keyboard Triggers Into Context Menus"
keywords: Context Menu Optimization,Keyboard Trigger Integration,Enhanced Text Input,Context Triggers Embedding,Efficient User Entry,Quick Access Commands,Contextual Keyboard UI
thumbnail: https://thmb.techidaily.com/96d460ad778074a93b63a308714d13a6fb98bd643d60a66bb372b318524a5b70.jpg
---

## Optimize Text Entry: Embedding Keyboard Triggers Into Context Menus

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://fox-http.techidaily.com/new-lol-meme-creator-tool/"><u>[New] LOL Meme Creator Tool</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-reviewing-sj7s-4k-action-cam-capturing-life-to-perfection/"><u>[New] Reviewing SJ7’s 4K Action Cam - Capturing Life to Perfection</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-depth-review-of-updated-videoshow-app-for-24-users/"><u>[Updated] In-Depth Review of Updated VideoShow App for '24 Users</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-compact-drone-guide-unraveling-dji-sparks-selfie-prowess/"><u>[Updated] The Ultimate Compact Drone Guide  Unraveling DJI Spark's Selfie Prowess</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-top-tips-understanding-asmr-recordings/"><u>[Updated] Top Tips  Understanding ASMR Recordings</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-enhancing-photo-stability-with-the-right-gimbal/"><u>2024 Approved  Enhancing Photo Stability with the Right Gimbal</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-vivo-x100-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/accelerating-your-creative-process-high-quality-3d-models-tools-for-2024/"><u>Accelerating Your Creative Process  High-Quality 3D Models Tools for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/advanced-tricks-for-quick-webp-to-jpg-conversion/"><u>Advanced Tricks for Quick WebP to JPG Conversion</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-x9a-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor X9a Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722773607345-capturing-excitement-the-pros-and-cons-of-gopro-hero7-black/"><u>Capturing Excitement - The Pros and Cons of GoPro HERO7 Black</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/cookiebot-driven-solutions-enhance-your-sites-personalization/"><u>Cookiebot-Driven Solutions: Enhance Your Site's Personalization</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-overcoming-outlook-crashing-issues/"><u>Essential Guide: Overcoming Outlook Crashing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-variance-in-offline-versus-online-windows-installation-methods/"><u>Exploring Variance in Offline Versus Online Windows Installation Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-winerror-0x8007043c-on-media-creator/"><u>Guide to Resolving WinError 0X8007043C on Media Creator</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-device-driver-loading-in-win11/"><u>How to Enable Device Driver Loading in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-sign-in-option-is-disabled-because-of-failed-sign-in-attempts-on-windows/"><u>How to Fix This Sign-In Option Is Disabled Because of Failed Sign-In Attempts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-past-a-non-starting-battlenet-interface/"><u>How to Get Past a Non-Starting Battle.net Interface</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-samsung-galaxy-a23-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Samsung Galaxy A23 5G</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premium-5-display-picks-for-immersive-gameplay/"><u>In 2024, Premium 5 Display Picks for Immersive Gameplay</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-vivo-s18-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Vivo S18 Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://tech-revival.techidaily.com/introducing-bard-googles-new-ai-contender-against-chatgpt/"><u>Introducing 'Bard': Google's New AI Contender Against ChatGPT</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-prodigy-tips-for-windows-photoshop/"><u>Keyboard Prodigy Tips for Windows Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-regaining-win-folder-entry/"><u>Master the Art of Regaining Win Folder Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-typing-troubles-addressing-zerox-code-0x80049dd3/"><u>Navigating Through Windows 11 Typing Troubles: Addressing Zerox (Code: 0X80049DD3)</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-already-active-issue-on-windows-11/"><u>Overcoming Resource Already Active Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11s-uptime-failure-error-code-0x80246007/"><u>Overcoming Windows 11’S Uptime Failure: Error Code 0X80246007</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-directory-design-mass-folder-formation-strategies-for-windows-1011-users/"><u>Proactive Directory Design: Mass Folder Formation Strategies for Windows 10/11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-audio-preferences-winvolume-issue-resolution/"><u>Reinstate Audio Preferences: WinVolume Issue Resolution</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-solving-the-issue-of-your-pc-not-shutting-down-in-windows-10/"><u>Resolved: Solving the Issue of Your PC Not Shutting Down in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidias-geforce-error-x0001-on-windows-1011/"><u>Resolving Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-rpc-issues-on-windows-key-strategies/"><u>Resolving RPC Issues on Windows: Key Strategies</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-write-operations-error/"><u>Tackling Windows Write Operations Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-11-widget-bar-activation/"><u>The Essential Guide to Windows 11 Widget Bar Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-for-restoring-win11s-5g-link/"><u>Tips and Tricks for Restoring Win11’s 5G Link</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-windows-11-help-app-restoration/"><u>Tips for Windows 11 Help App Restoration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/toggle-the-past-the-twitch-live-trick-for-2024/"><u>Toggle the Past  The Twitch Live Trick for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-programming-file-formats/"><u>Understanding Windows' Programming File Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-control-panel-access-methods/"><u>Unveiling Control Panel Access Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tech-tip-validate-audiovideo-before-participating/"><u>Windows Tech Tip: Validate Audio/Video Before Participating</u></a></li>
</ul></div>
