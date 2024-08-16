---
title: Navigate Through Fingertip Writing Options in Windows System
date: 2024-08-15T15:39:28.127Z
updated: 2024-08-16T15:39:28.127Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Through Fingertip Writing Options in Windows System
excerpt: This Article Describes Navigate Through Fingertip Writing Options in Windows System
keywords: Fingertip Typing Windows,Touch Keyboard Windows,Windows Gesture Control,Tap Input Windows,Direct Keys Windows,Swipe Writing Windows,On-Screen Mouse Windows
thumbnail: https://thmb.techidaily.com/98351be0d04e2b45fd40ed227ba896a84193b786b4aa1a37bd43c93403b74a19.png
---

## Navigate Through Fingertip Writing Options in Windows System

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also [convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
7. Click**Apply** \>**OK** to save the changes.

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.


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
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-avoid-frustration-correct-a-mistaken-tiktok-reset/"><u>[New] 2024 Approved  Avoid Frustration – Correct a Mistaken TikTok Reset</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-unveiling-allure-comprehensive-beauty-how-tos-on-youtube/"><u>[New] 2024 Approved  Unveiling Allure  Comprehensive Beauty How-Tos on Youtube</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-guide-shutting-down-igtv/"><u>[New] In 2024, Guide  Shutting Down IGTV</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-prime-video-the-twitterspheres-favorite-shows-of-23/"><u>[New] In 2024, Prime Video  The Twittersphere's #Favorite Shows of '23</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-step-by-step-from-vimeo-to-engaging-animated-content/"><u>[New] In 2024, Step-by-Step  From Vimeo to Engaging Animated Content</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-macs-best-gif-maker-tool-for-2024/"><u>[New] Mac's Best Gif Maker Tool for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-use-periscope-the-complete-guide/"><u>[Updated] How to Use Periscope  The Complete Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-examining-video-comments-on-youtube/"><u>[Updated] In 2024, Examining Video Comments on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-free-game-recording-software-of-2024/"><u>[Updated] The Free Game Recording Software of 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-sound-step-down-strategy-a-pro-guide-to-fading-audio/"><u>2024 Approved  Sound Step-Down Strategy  A Pro Guide to Fading Audio</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-treasure-trove-of-budget-friendly-digital-artistry-tools/"><u>A Treasure Trove of Budget-Friendly Digital Artistry Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x00000709-in-windows/"><u>Addressing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-windows-update-issue-the-0x800736cc-method/"><u>Bypassing Windows Update Issue: The 0X800736CC Method</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-failed-video-drivers-in-win1110/"><u>Correcting Failed Video Drivers in Win11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-bluescreenviews-purpose/"><u>Decoding BlueScreenView's Purpose</u></a></li>
<li><a href="https://tech-revival.techidaily.com/detecting-fake-chatgpt-scams-actions-for-safe-online-interaction/"><u>Detecting Fake ChatGPT Scams: Actions for Safe Online Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-forgotten-windows-add-ons-and-utilities-in-7-ways/"><u>Enabling Forgotten Windows Add-Ons and Utilities in 7 Ways</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-appearance-with-custom-pointer-design/"><u>Enhancing System Appearance with Custom Pointer Design</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/guidelines-for-legally-reposting-on-insta-for-2024/"><u>Guidelines for Legally Reposting on Insta for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-power-using-lav-filters-on-microsoft-windows/"><u>Harnessing Power: Using LAV Filters on Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-open-the-phone-dialer-in-windows-11/"><u>How to Open the Phone Dialer in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-xiaomi-redmi-note-13-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Xiaomi Redmi Note 13 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-on-vivo-t2x-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP on Vivo T2x 5G?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-uniting-social-media-and-television-with-fb-live/"><u>In 2024, Uniting Social Media & Television with FB Live</u></a></li>
<li><a href="https://windows11.techidaily.com/journey-to-mastery-original-diablo-basics-explained/"><u>Journey to Mastery: Original Diablo Basics Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-installation-of-intel-wi-fi-drivers/"><u>Navigating the Installation of Intel Wi-Fi Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011s-auto-restart-settings/"><u>Navigating Windows 10/11'S Auto-Restart Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/office-design-evolution-trends-and-practices-for-maximum-output/"><u>Office Design Evolution  Trends and Practices for Maximum Output</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-to-locate-windows-10-or-11-keys-efficiently/"><u>Pro Tips to Locate Windows 10 or 11 Keys Efficiently</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/professional-guide-ensuring-imovie-content-shines-on-vimeo/"><u>Professional Guide  Ensuring iMovie Content Shines on Vimeo</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-accessing-power-user-terminal/"><u>Securely Accessing Power-User Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-the-nullzero-error-fixes-for-new-users-on-win11/"><u>Stop the Null/Zero Error: Fixes for New Users on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-installing-unverified-windows-drivers/"><u>Tactics for Installing Unverified Windows Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/turbocharge-pc-gaming-with-high-speed-yuzu/"><u>Turbocharge PC Gaming with High-Speed Yuzu</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-folders-and-files-converge-in-win-11/"><u>Unlocking Efficiency: Folders & Files Converge in Win 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unlocking-top-tier-gif-utilities-on-ios-devices/"><u>Unlocking Top-Tier GIF Utilities on iOS Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-quick-access-shortcuts-adjacent-to-power-in-win11/"><u>Unveiling Quick Access: Shortcuts Adjacent to Power in Win11</u></a></li>
</ul></div>
