---
title: Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs
date: 2024-08-15T15:25:43.317Z
updated: 2024-08-16T15:25:43.317Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs
excerpt: This Article Describes Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs
keywords: Shutdown Extension,Shutdown Lengthening,PC Shutdown Duration,Ongoing Jobs & Restart,Prolonged Sleep Time,Batch Jobs in Idle,Optimize System Restarts
thumbnail: https://thmb.techidaily.com/295eacd64272b4b4a8e96856aef38358e19d3e53299073754d2c1fe5d922072f.png
---

## Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an [app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves [editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and [make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
### 1A. How to Set WaitToKillAppTimeout for Just Your User Account

 Do this to change how long Windows waits for apps when logging off just from your user account.

1. Open the Registry editor. See [how to open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) for more information.
2. Navigate to the following folder in the registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**WaitToKillAppTimeout** .
4. If you don’t see it, you’ll need to create it by right-clicking in any empty space in the pane and selecting**New > String Value** . Rename it**WaitToKillAppTimeout** .
5. Double-click this string to edit its value, which is in milliseconds. (1000 milliseconds equals one second.) By default, the value data is set to 20,000 (or 20 seconds).
6. Increase this value to make Windows wait on running apps longer before shutting down or logging off. (Decreasing its value will log you off more quickly.)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
## Give Apps More Time to Close When Logging Off

 If apps keep interrupting Windows when you shut down or log off, it would be wise to give them a little more time to finish up and close properly. That way, they won’t interrupt the log-off process and have you intervene manually.


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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-improve-your-virtual-engagement-mastering-snap-photography/"><u>[New] 2024 Approved  Improve Your Virtual Engagement  Mastering Snap Photography</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-maximizing-quality-in-ppt-recordings/"><u>[New] In 2024, Maximizing Quality in PPT Recordings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-endgame-for-deactivating-an-instagram-profile-for-2024/"><u>[New] The Endgame for Deactivating an Instagram Profile for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-uncover-the-best-10-online-vectors-collections/"><u>[New] Uncover the Best 10 Online Vectors Collections</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-unmatched-upticks-celebrating-top-10-reddit-discussions-for-2024/"><u>[New] Unmatched Upticks  Celebrating Top 10 Reddit Discussions for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-behind-the-scenes-the-genesis-of-a-mukbang-video-for-2024/"><u>[Updated] Behind the Scenes  The Genesis of a Mukbang Video for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-brand-storytelling-through-imagery-a-podcast-designers-guide/"><u>[Updated] Brand Storytelling Through Imagery  A Podcast Designer's Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-mining-meaningful-conversations-on-youtube/"><u>[Updated] Mining Meaningful Conversations on YouTube</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-tecno-pova-5-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Tecno Pova 5 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-mastering-gameplay-with-best-gadgets/"><u>2024 Approved  Mastering Gameplay with Best Gadgets</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-mediamagic-8-edition/"><u>2024 Approved  MediaMagic 8 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x00000709-in-windows/"><u>Addressing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-techniques-in-windows-photo-editing/"><u>Advanced Techniques in Windows Photo Editing</u></a></li>
<li><a href="https://windows11.techidaily.com/analyzing-how-windows-11-fuels-microsofts-earnings/"><u>Analyzing How Windows 11 Fuels Microsoft's Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-ppt-file-saving-challenges-swift-solutions-in-windows-11/"><u>Conquer PPT File Saving Challenges: Swift Solutions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-digital-experience-process-control-and-thematic-aesthetics-in-w11/"><u>Elevate Your Digital Experience: Process Control & Thematic Aesthetics in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/engagingnotabledarkthemefornotepadwin/"><u>EngagingNotableDarkThemeForNotepadWin</u></a></li>
<li><a href="https://windows11.techidaily.com/ensure-office-applications-open-email-attachments-as-text-only-by-design/"><u>Ensure Office Applications Open Email Attachments as Text Only by Design</u></a></li>
<li><a href="https://fox-info.techidaily.com/evolving-videography-redefining-social-sharing-with-periscope-alternatives-for-2024/"><u>Evolving Videography  Redefining Social Sharing with Periscope Alternatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-worldwide-efficient-mouse-skills-via-powertoys/"><u>Explore Worldwide - Efficient Mouse Skills via PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-ditch-intels-onboard-graphics-in-windows/"><u>How to Ditch Intel's Onboard Graphics in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-optimize-your-browsing-experience-use-defender-aguard-in-win-11-edge/"><u>How to Optimize Your Browsing Experience: Use Defender Aguard in Win 11 Edge</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-laserjet-m127fn-all-in-one-printer-driver-software-download-guide-and-free-installation/"><u>HP LaserJet M127FN All-in-One Printer Driver Software: Download Guide and Free Installation</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-lan-world-play-in-windows-mc-game/"><u>Mastering LAN World Play in Windows MC Game</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-linguistic-landscapes-smoothly-via-keyboard-shortcuts-in-win1011/"><u>Navigate Linguistic Landscapes Smoothly via Keyboard Shortcuts in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-apex-crashes-essential-steps-for-windows-11-gamers/"><u>Overcome Apex Crashes: Essential Steps for Windows 11 Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-chrome-from-saving-webp-images-in-windows/"><u>Prevent Chrome From Saving WebP Images in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/redefine-reviving-with-modern-os-alternatives/"><u>Redefine Reviving with Modern OS Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-clutter-increase-efficiency-one-antivirus-rule/"><u>Reduce Clutter, Increase Efficiency: One Antivirus Rule!</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-windows-activation-flaw-error-0x803f700f/"><u>Remedying Windows Activation Flaw: Error 0X803F700F</u></a></li>
<li><a href="https://windows11.techidaily.com/reverting-back-to-legacy-window-explorer/"><u>Reverting Back to Legacy Window Explorer</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-ui-adding-cli-functionality-to-taskmgr-in-win11/"><u>Revolutionizing UI: Adding CLI Functionality to TaskMgr in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-timeline-microsofts-ui-evolution/"><u>Taskbar Timeline: Microsoft's UI Evolution</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-techniques-boosting-your-virtual-memory-in-windows-11/"><u>The Essential Techniques: Boosting Your Virtual Memory in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shortcut-pathways-for-windows-starters/"><u>The Shortcut Pathways for Windows Starters</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-writing-enhancers-for-your-windows-desktop/"><u>Top 5 Writing Enhancers for Your Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-busy-errors-on-pcs/"><u>Troubleshooting Printer Busy Errors on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-enhancing-pen-device-performance-on-windows/"><u>Troubleshooting: Enhancing Pen Device Performance on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-registry-a-guide-to-its-components/"><u>Unveiling Windows 11'S Registry: A Guide to Its Components</u></a></li>
</ul></div>
