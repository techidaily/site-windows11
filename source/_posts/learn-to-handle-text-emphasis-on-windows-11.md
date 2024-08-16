---
title: Learn to Handle Text Emphasis on Windows 11
date: 2024-08-15T15:39:26.058Z
updated: 2024-08-16T15:39:26.058Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Learn to Handle Text Emphasis on Windows 11
excerpt: This Article Describes Learn to Handle Text Emphasis on Windows 11
keywords: Text Emphasis Basics,WinTextFormatting,Highlighting Text W11,Bold Windows Text,Italicize Win11 Text,Underline Text in W11,Stressed Windows Text
thumbnail: https://thmb.techidaily.com/97b0ddc570e6ff11d98aa739ad9094bf8b6916f3ca7d54eab5f1d4007ba674c0.JPG
---

## Learn to Handle Text Emphasis on Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-finance-frontiers-the-finest-youtube-channels-to-follow/"><u>[New] 2024 Approved  Finance Frontiers  The Finest YouTube Channels to Follow</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-best-youtube-to-mp3-converters-free-download-onlinewinmac/"><u>[Updated] In 2024, Best YouTube to MP3 Converters Free Download [Online/Win/Mac]</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-quintessential-10-fight-royale-games/"><u>[Updated] Quintessential 10 Fight Royale Games</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-tweet-audio-conversion-free-video-downloads/"><u>[Updated] Tweet Audio Conversion  Free Video Downloads</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-venturing-into-virtual-steps-top-treadmill-analysis/"><u>[Updated] Venturing Into Virtual Steps  Top Treadmill Analysis</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-focus-sharpening-a-selective-approach-to-photos/"><u>2024 Approved  Focus Sharpening  A Selective Approach to Photos</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/a-bilingual-mindsets-benefits-countdown-to-6/"><u>A Bilingual Mindset's Benefits Countdown to 6</u></a></li>
<li><a href="https://windows11.techidaily.com/a-systematic-approach-to-fixing-the-zeroxc000003e-issue/"><u>A Systematic Approach to Fixing the ZeroXc000003e Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-audio-dynamics-for-bluetooth-devices/"><u>Balancing Audio Dynamics for Bluetooth Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/becoming-proficient-in-ez-grabber-technology-for-2024/"><u>Becoming Proficient in EZ Grabber Technology for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/combatting-efail-error-code-0x80004005-in-virtualbox/"><u>Combatting E_FAIL (Error Code: 0X80004005) in Virtualbox</u></a></li>
<li><a href="https://windows11.techidaily.com/diminishing-high-cpu-impact-of-tiworkerexe-applications/"><u>Diminishing High CPU Impact of TiWorker.exe Applications</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-strength-and-cost-efficiency-of-the-omoton-t1-tablet-mount-a-thorough-examination/"><u>Discover the Strength and Cost-Efficiency of the Omoton T1 Tablet Mount - A Thorough Examination</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/epic-quests-unveiled-top-games-mirroring-ghost-of-tsushima/"><u>Epic Quests Unveiled  Top Games Mirroring Ghost of Tsushima</u></a></li>
<li><a href="https://network-issues.techidaily.com/eradicating-screen-flicker-on-windows-7/"><u>Eradicating Screen Flicker on Windows 7</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-hacks-for-identifying-windows-age/"><u>Expert Hacks for Identifying Windows Age</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-retrieve-the-missing-windows-product-patch/"><u>Expert Tips to Retrieve the Missing Windows Product Patch</u></a></li>
<li><a href="https://fox-access.techidaily.com/eye-catching-text-top-10-photo-writing-tools-for-smartphones-for-2024/"><u>Eye-Catching Text  Top 10 Photo Writing Tools for Smartphones for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-writing-permission-failure-in-windows-10-and-11/"><u>Fixing Writing Permission Failure in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/flipping-a-non-working-search-bar-in-windows-11s-settings/"><u>Flipping a Non-Working Search Bar in Windows 11’S Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-hidden-items-context-menu-option-in-windows-10-and-11/"><u>How to Add a Hidden Items Context Menu Option in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-network-error-0x800704b3-in-windows-11-and-11/"><u>How to Fix the Network Error 0X800704b3 in Windows 11 & 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-holistic-overview-decoding-google-podcasts-app-features/"><u>In 2024, Holistic Overview  Decoding Google Podcasts App Features</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-stars-quick-visibility-check/"><u>In 2024, Star's Quick Visibility Check</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-changes-accessing-fax-editor-in-the-newest-os/"><u>Initiating Changes: Accessing Fax Editor in the Newest OS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/instant-techniques-to-shuffle-youtube-song-sequences/"><u>Instant Techniques to Shuffle YouTube Song Sequences</u></a></li>
<li><a href="https://youtube-help.techidaily.com/kids-earning-big-the-success-story-of-young-ryan-kaji-for-2024/"><u>Kids Earning Big  The Success Story of Young Ryan Kaji for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-system-rescue-console-easily/"><u>Launching the System Rescue Console Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/leveraging-labels-for-efficient-file-management-on-windows-11/"><u>Leveraging Labels for Efficient File Management on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-the-art-shrink-or-enlarge-apps-using-shortcut-on-win11/"><u>Perfecting the Art: Shrink or Enlarge Apps Using Shortcut on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-tackling-error-1053-unresponsive-windows-services/"><u>Quick Guide to Tackling Error 1053: Unresponsive Windows Services</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivate-quieted-slack-feedback-in-win-11-systems/"><u>Reactivate Quieted Slack Feedback in Win 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/reboot-to-reconnect-reviving-ethernet-net-access/"><u>Reboot to Reconnect: Reviving Ethernet Net Access</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-effortlessly-managing-tabs-in-windows-11/"><u>Seamless Integration: Effortlessly Managing Tabs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-typing-typingaids-expertise/"><u>Speeding Up Typing: TypingAid's Expertise</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-resolving-the-usb-drivers-problem-for-lg-computers-running-windows-10-8-or-n7/"><u>Step-by-Step Guide: Resolving the USB Drivers Problem for LG Computers Running Windows 10, 8 or N7</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-for-full-removal-of-wsl-on-windows-11/"><u>Stepwise Strategy for Full Removal of WSL on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-recovery-overcoming-black-screen-issues-in-wins/"><u>Swift Recovery: Overcoming Black-Screen Issues in Wins</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-experts-list-of-tools-for-accelerating-your-facebook-vids/"><u>The Expert's List of Tools for Accelerating Your Facebook Vids</u></a></li>
<li><a href="https://windows11.techidaily.com/the-hidden-dangers-in-bot-made-win-11-codes/"><u>The Hidden Dangers in Bot-Made Win 11 Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-resolving-unresponsiveness-in-your-windows-downloads-hub/"><u>Tips for Resolving Unresponsiveness in Your Windows Downloads Hub</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-platforms-enhance-your-youtube-presence/"><u>Top Platforms  Enhance Your YouTube Presence</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-the-stalled-windows-system-insight/"><u>Troubleshooting the Stalled Windows System Insight</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-overwatch-game-analysis-thrilling-team-play-experience/"><u>Ultimate Overwatch Game Analysis: Thrilling, Team Play Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategy-enhancing-hard-drive-performance/"><u>Win11 Strategy: Enhancing Hard Drive Performance</u></a></li>
</ul></div>
