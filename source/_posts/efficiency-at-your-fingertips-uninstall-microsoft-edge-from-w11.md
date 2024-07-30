---
title: "Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11"
date: 2024-07-29T04:25:25.712Z
updated: 2024-07-30T04:25:25.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11"
excerpt: "This Article Describes Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11"
keywords: Uninstall Edge W11,Easy Edge Removal,Disable Edge W11,Optimize Windows Performance,Simplify W11 Setup,Streamline W11 OS,Enhance PC Speed
thumbnail: https://thmb.techidaily.com/f3b5fbbb41ff3e0e15766362f9082ba5609c00b8437978e5e3317dc5d76ea72c.jpg
---

## Efficiency at Your Fingertips: Uninstall Microsoft Edge From W11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://youtube-sure.techidaily.com/-comprehensible-explanation-of-youtubes-viewership-puzzle-for-2024/"><u>[New] A Comprehensible Explanation of YouTube's Viewership Puzzle for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-experience-the-future-of-action-videos-sj7s-star-4k-review-for-2024/"><u>[New] Experience the Future of Action Videos  SJ7's Star 4K Review for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-mastering-multitasking-ideas-with-podcasts/"><u>[New] In 2024, Mastering Multitasking  Ideas with Podcasts</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-ultimate-microphone-choices-for-filmmakers/"><u>[New] Ultimate Microphone Choices for Filmmakers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-cutting-to-the-beat-making-short-films-on-your-iphone-for-2024/"><u>[Updated] Cutting to the Beat  Making Short Films on Your iPhone for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-essential-guide-to-highest-rated-church-livestream-sites/"><u>2024 Approved  Essential Guide to Highest-Rated Church Livestream Sites</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-future-insight-alternate-pathways/"><u>2024 Approved  Future Insight  Alternate Pathways</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-accessibility-tools-on-windows/"><u>A Beginner's Guide to Accessibility Tools on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-for-pcs-memory-tool-issues/"><u>A Comprehensive Guide for PC's Memory Tool Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/a-glimpse-at-future-ready-windows-with-update-22h2s-features/"><u>A Glimpse at Future-Ready Windows with Update #22H2's Features</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-isdonedll-error-in-modern-windows-editions/"><u>Addressing ISDone.dll Error in Modern Windows Editions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/battle-of-the-capture-tools-obs-studio-against-bandicam-for-2024/"><u>Battle of the Capture Tools  OBS Studio Against Bandicam for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-crafting-shortcuts-to-store-uwp-apps-on-windows/"><u>Boosting Productivity: Crafting Shortcuts to Store UWP Apps on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clipchamp-patch-enable-installation-in-windows-11/"><u>ClipChamp Patch: Enable Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/driving-engagement-and-returns-animated-advertising-on-facebook-for-2024/"><u>Driving Engagement and Returns  Animated Advertising on Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-isolating-unfamiliar-users-in-win-11/"><u>Effective Strategies for Isolating Unfamiliar Users in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-11s-online-threat-detection/"><u>Fine-Tuning Windows 11'S Online Threat Detection</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/future-of-storage-top-picks-and-prices-in-clouds-for-2024/"><u>Future of Storage  Top Picks and Prices in Clouds for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/highest-rated-windows-encryption-software-guide-150-chars/"><u>Highest Rated Window's Encryption Software Guide (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-adjust-lockout-frequency-after-incorrect-user-credentials-for-windows-11/"><u>How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-screen-order-in-pc/"><u>How to Change Screen Order in PC</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-unsolicited-openings-of-search-bar-win11/"><u>How to Prevent Unsolicited Openings of Search Bar, Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-a15-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy A15 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-10-best-cost-free-subtitle-grabs-from-youtube/"><u>In 2024, 10 Best Cost-Free Subtitle Grabs From YouTube</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-oppo-a38-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Oppo A38 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-oppo-a18-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Oppo A18 Phones? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-revolutionizing-video-content-analyzing-tiktok-and-snapchats-innovation/"><u>In 2024, Revolutionizing Video Content  Analyzing TikTok and Snapchat’s Innovation</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-step-by-step-instructions-producing-alluring-video-thumbnails-on-youtube/"><u>In 2024, Step-by-Step Instructions  Producing Alluring Video Thumbnails on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-convergence-the-best-6-compatible-android-apps-on-windows-11/"><u>Master the Convergence: The Best 6 Compatible Android Apps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-extended-display-setup-without-performance-hit/"><u>Mastering Extended Display Setup Without Performance Hit</u></a></li>
<li><a href="https://windows11.techidaily.com/monitor-positioning-tactics-in-windows/"><u>Monitor Positioning Tactics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-win-1011-menu-options/"><u>Reviving Your Win 10/11 Menu Options</u></a></li>
<li><a href="https://windows11.techidaily.com/smoothing-out-chrome-profile-hitches-on-windows-systems/"><u>Smoothing Out Chrome Profile Hitches on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-address-aw-snap-in-google-chrome-on-pc/"><u>Steps to Address Aw, Snap! In Google Chrome on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-improve-steam-download-speeds-on-windows/"><u>Strategies to Improve Steam Download Speeds on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategizing-your-path-through-original-diablo/"><u>Strategizing Your Path Through Original Diablo</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-correcting-failed-java-setup-in-windows/"><u>Techniques for Correcting Failed Java Setup in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-serenity-of-silence-premier-asmr-talents/"><u>The Serenity of Silence  Premier ASMR Talents</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/top-secure-cost-free-androidios-apps-for-private-video-conferencing/"><u>Top Secure, Cost-Free Android/iOS Apps for Private Video Conferencing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-list-seamless-no-download-gif-to-video-converters-for-2024/"><u>Ultimate List  Seamless No-Download GIF to Video Converters for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-defaults-permissions-restoration-guide/"><u>Unlocking Defaults: Permissions Restoration Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-ultimate-free-toolset-for-win11-pcs/"><u>Unveiling the Ultimate Free Toolset for Win11 PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/visionary-intros-free-templates-for-inspiration/"><u>Visionary Intros  Free Templates for Inspiration</u></a></li>
<li><a href="https://windows11.techidaily.com/visual-disk-management-in-context-menus-for-win-11/"><u>Visual Disk Management in Context Menus for Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-when-the-audio-services-are-not-responding-on-windows/"><u>What to Do When the Audio Services Are Not Responding on Windows</u></a></li>
</ul></div>
