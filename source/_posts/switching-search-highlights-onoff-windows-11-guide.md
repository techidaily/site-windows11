---
title: "Switching Search Highlights On/Off: Windows 11 Guide"
date: 2024-08-08T06:02:41.518Z
updated: 2024-08-09T06:02:41.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Switching Search Highlights On/Off: Windows 11 Guide"
excerpt: "This Article Describes Switching Search Highlights On/Off: Windows 11 Guide"
keywords: Win11 Highlight Control,Turn Off Search Highlighters,Enable Windows Search Markup,Disable Search Annotations,On/Off Search Indicators,Adjust Text Highlights W11,Manage Search Markup WS11
thumbnail: https://thmb.techidaily.com/405adc45ebf84824c8425ce7d2ecb9e77863385d350fb3dba3386c181908ce4e.jpg
---

## Switching Search Highlights On/Off: Windows 11 Guide

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-dominating-the-youtube-sphere-key-strategies-for-top-tier-presence/"><u>[New] 2024 Approved  Dominating the YouTube Sphere  Key Strategies for Top-Tier Presence</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-flame-the-fire-enhancing-your-snapstreak-game/"><u>[New] 2024 Approved  Flame the Fire  Enhancing Your Snapstreak Game</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-creating-captivating-tiktok-outro-sequences/"><u>[New] Creating Captivating TikTok Outro Sequences</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-dissecting-instagrams-maximum-video-duration-rule-for-2024/"><u>[Updated] Dissecting Instagram's Maximum Video Duration Rule for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-future-together-top-vr-gear/"><u>[Updated] Exploring the Future Together  Top VR Gear</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-creation-to-consumption-igtv-vs-youtube-explained-for-you-for-2024/"><u>[Updated] From Creation to Consumption  IGTV Vs. YouTube Explained for You for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elevating-content-strategy-with-effective-youtube-partnerships/"><u>[Updated] In 2024, Elevating Content Strategy with Effective YouTube Partnerships</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-best-start-streamlined-tools-for-novice-game-editors-for-2024/"><u>[Updated] The Best Start  Streamlined Tools for Novice Game Editors for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-wealth-wave-of-the-philanthropic-maverick-mr-beast/"><u>[Updated] The Wealth Wave of the Philanthropic Maverick, Mr. Beast</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-gradient-goes-night-premieres-trick/"><u>2024 Approved  Gradient Goes Night  Premiere's Trick</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-quick-shake-reduction-companion-for-cams/"><u>2024 Approved  Quick Shake Reduction Companion for Cams</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ving-profitability-on-youtube-average-view-count-for-success/"><u>Achieving Profitability on YouTube  Average View Count for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-windows-11-performance-run-command-upgrade-guide/"><u>Boosting Windows 11 Performance: Run Command Upgrade Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win-path-unavailability-issue/"><u>Clearing Up WIN Path Unavailability Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/convenient-methods-for-local-policies-on-windows-11/"><u>Convenient Methods for Local Policies on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/craft-compelling-content-with-these-windows-tools/"><u>Craft Compelling Content with These Window's Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-create-a-personalized-windows-text-recognition-program/"><u>Easy Steps to Create a Personalized Windows Text Recognition Program</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-poco-c65-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Poco C65</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-switching-files-between-formats-in-windows/"><u>Effortlessly Switching Files Between Formats in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-development-workflow-navigating-windows-11s-dev-drive/"><u>Elevate Development Workflow: Navigating Windows 11'S Dev Drive</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-driver-enforcement-loading-unsigned-on-windows-108/"><u>Eliminating Driver Enforcement: Loading Unsigned On Windows 10/8</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-faulty-devices-from-system-logs-windows-1011/"><u>Eliminating Faulty Devices From System Logs: Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-read-only-files-a-guide-for-windows-11-users/"><u>Eliminating Read-Only Files: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/embrace-world-typography-on-windows-font-guide/"><u>Embrace World Typography on Windows - Font Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-touchscreen-accuracy-windows-11-tutorial/"><u>Enhancing Touchscreen Accuracy: Windows 11 Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-digital-security-best-windows-cryptography-picks-148-chars/"><u>Ensuring Digital Security: Best Window's Cryptography Picks (148 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-app-list-for-seamless-os-transition-from-apple-to-windows/"><u>Essential App List for Seamless OS Transition From Apple to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/halt-spotifys-autoplay-behavior-on-pc/"><u>Halt Spotify's Autoplay Behavior on PC</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-from-apple-iphone-xs-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password From Apple iPhone XS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-direct-stream-from-youtube-to-facebook-without-pauses-or-holds/"><u>In 2024, Direct Stream From YouTube to Facebook without Pauses or Holds</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/navigating-video-editor-landscape-choose-filmora-or-democracy-creator/"><u>Navigating Video Editor Landscape  Choose Filmora or Democracy Creator?</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-samsung-galaxy-a24-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Samsung Galaxy A24 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/social-media-mastery-incorporating-polls-in-stories-for-2024/"><u>Social Media Mastery  Incorporating Polls in Stories for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-complete-instagram-analytics-companion-transforming-metrics-into-strategy-for-2024/"><u>The Complete Instagram Analytics Companion  Transforming Metrics Into Strategy for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-apple-iphone-se-2022-without-passcode-easily-drfone-by-drfone-ios/"><u>Unlock Apple iPhone SE (2022) Without Passcode Easily | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>