---
title: Tweaking Taskbar Width in Win11
date: 2024-08-15T16:22:08.158Z
updated: 2024-08-16T16:22:08.158Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tweaking Taskbar Width in Win11
excerpt: This Article Describes Tweaking Taskbar Width in Win11
keywords: Win11 Taskbar Adjustment,Taskbar Resizing Windows 11,Narrowing Windows Bar,Widen Taskbar Control,Set Taskbar Width (Win11),Customize Win11 Bar Size,Modify Window Bar Dimensions
thumbnail: https://thmb.techidaily.com/c88c76635d5e0629581e4fd4108916cee892ed1d438b3013953d19ca906db797.jpg
---

## Tweaking Taskbar Width in Win11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.


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
<li><a href="https://youtube-data.techidaily.com/024-approved-business-beginnings-easier-than-ever-top-10-youtube-channel-ideas/"><u>[New] 2024 Approved  Business Beginnings Easier Than Ever  Top 10 YouTube Channel Ideas</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-4-fastest-lenovo-record-methods/"><u>[New] 2024 Approved  The 4 Fastest Lenovo Record Methods</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-djis-aviation-innovation-meets-gaming-mavic-air-versus-spark/"><u>[New] In 2024, DJI’s Aviation Innovation Meets Gaming  Mavic Air Versus Spark</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-instagram-video-marketing-how-to-plan-your-strategy-with-10-best-ideas-for-2024/"><u>[New] Instagram Video Marketing  How to Plan Your Strategy with 10 Best Ideas for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-flip-side-realities-of-virtual-reality/"><u>[New] The Flip Side  Realities of Virtual Reality</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-ultimate-guide-to-facebook-friendly-xbox-play/"><u>[New] The Ultimate Guide to Facebook-Friendly Xbox Play</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-best-video-transcriber-chrome-os-companion-for-2024/"><u>[Updated] Best Video Transcriber  Chrome OS Companion for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-cross-play-exclusivity-guide-in-apex-legends-games-for-2024/"><u>[Updated] Cross-Play Exclusivity Guide in Apex Legends Games for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-content-creators-preferences-vimeo-or-youtube/"><u>[Updated] In 2024, Content Creators' Preferences  Vimeo or YouTube?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-ultimate-free-fb-photovideo-maker/"><u>[Updated] In 2024, Ultimate Free FB Photo/Video Maker</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-premier-ios-platforms-for-ps2-gaming/"><u>2024 Approved  Premier iOS Platforms for PS2 Gaming</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-ultimate-flashback-2022s-snowboard-x-winners/"><u>2024 Approved  Ultimate Flashback  2022'S Snowboard X Winners</u></a></li>
<li><a href="https://windows11.techidaily.com/5-proven-strategies-for-superior-windows-11-search-performance/"><u>5 Proven Strategies for Superior Windows 11 Search Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-the-application-made-too-many-requests-error-0x80860010-on-windows/"><u>7 Ways to Fix the Application Made Too Many Requests Error (0X80860010) on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-wipeout-ms-audit-reports-on-your-pc/"><u>A Comprehensive Guide to Wipeout MS Audit Reports on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/a-fresh-window-on-computers-after-windows-11/"><u>A Fresh Window on Computers: After Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-uncovering-your-systems-identity-quickly/"><u>A Guide to Uncovering Your System's Identity Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/activating-restoration-features-your-pathway-through-windows-11/"><u>Activating Restoration Features: Your Pathway Through Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-11s-task-manager-launch-interface/"><u>Adjusting Windows 11'S Task Manager Launch Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/adopting-a-context-menu-toolbar-alert-for-routine-update-checks-on-windows-11plus11/"><u>Adopting a Context Menu Toolbar Alert for Routine Update Checks on Windows 11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-uses-of-github-desktop-for-windows-11-enthusiasts/"><u>Advanced Uses of GitHub Desktop for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-login-lockout-interval-after-errors/"><u>Altering Windows Login Lockout Interval After Errors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-vivo-s17-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Vivo S17 Phone and Remove Locked Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-productivity-with-permanent-windows-terminal-admin-entry/"><u>Boost Productivity with Permanent Windows Terminal Admin Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-steam-downloads-enhancing-windows-performance/"><u>Boosting Steam Downloads: Enhancing Windows Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-verification-barrier-when-installing-non-microsoft-apps/"><u>Bypassing Verification Barrier when Installing Non-Microsoft Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-blocked-app-notification-issue/"><u>Clearing Up the Blocked App Notification Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/command-center-changing-your-onedrive-storage-territory-on-windows-10/"><u>Command Center: Changing Your OneDrive Storage Territory on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/compatible-drawing-tools-for-windows-not-procreate/"><u>Compatible Drawing Tools for Windows, Not Procreate</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-windows-screensaver-tactics/"><u>Comprehensive Guide: Windows Screensaver Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-complexity-adding-ease-to-uninstall-in-windows/"><u>Conquering Complexity: Adding Ease to Uninstall in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/correct-windows-11s-no-error-zero-error-flaw-quickly/"><u>Correct Windows 11'S No Error, Zero-Error Flaw Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-gray-out-issue-with-volume-extend-in-win/"><u>Correcting Gray Out Issue with Volume Extend in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/cracking-the-code-unlocking-mac-locations-in-windows-11/"><u>Cracking the Code: Unlocking MAC Locations in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-a-festive-atmosphere-with-creative-windows/"><u>Craft a Festive Atmosphere with Creative Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-taskbar-and-menu-on-windows-1011-easily/"><u>Customize Taskbar & Menu on Windows 10/11 Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/customize-your-clock-region-on-windows-avoiding-automatic-changes/"><u>Customize Your Clock Region on Windows, Avoiding Automatic Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-not-found-on-windows/"><u>Deciphering and Correcting 'Not Found' On Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-and-correcting-irq-glitches/"><u>Deciphering and Correcting IRQ Glitches</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-disruption-in-skyrims-scripting/"><u>Deciphering the Disruption in Skyrim's Scripting</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-win-errors-post-bsod-on-modern-oses/"><u>Deciphering Win Errors Post-BSOD on Modern OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/decode-the-code-of-win11-blue-screen-with-essential-fixes/"><u>Decode the Code of Win11 Blue Screen with Essential Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/direct-route-to-dialing-system-in-win-11/"><u>Direct Route to Dialing System in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disable-untrusted-adobe-pop-up-on-computer/"><u>Disable Untrusted Adobe Pop-Up on Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-inadvertent-launches-of-ms-storeapp/"><u>Disabling Inadvertent Launches of MS StoreApp</u></a></li>
<li><a href="https://windows11.techidaily.com/display-windows-notes-prominently-and-consistently/"><u>Display Windows Notes Prominently and Consistently</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortlessly-enhance-your-pc-with-updated-msi-gpu-drivers-in-windows-11-and-7/"><u>Effortlessly Enhance Your PC with Updated MSI GPU Drivers in Windows 11 & 7</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, Effective Ways To Fix Checkra1n Error 31 On Apple iPhone SE (2020)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-fuse-melodies-into-your-youtube-digital-realm/"><u>In 2024, Fuse Melodies Into Your Youtube Digital Realm</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-lava-blaze-2-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Lava Blaze 2 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pristineai-designs-crafting-visuals-with-ai/"><u>PristineAI Designs  Crafting Visuals with AI</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-12plus-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme 12+ 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/1719359377017-unfreeze-shift-button-on-your-pc/"><u>Unfreeze Shift Button on Your PC</u></a></li>
</ul></div>
