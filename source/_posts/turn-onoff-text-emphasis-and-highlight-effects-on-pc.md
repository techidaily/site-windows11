---
title: Turn On/Off Text Emphasis and Highlight Effects on PC
date: 2024-08-15T16:19:02.062Z
updated: 2024-08-16T16:19:02.062Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn On/Off Text Emphasis and Highlight Effects on PC
excerpt: This Article Describes Turn On/Off Text Emphasis and Highlight Effects on PC
keywords: Text Emphasis Toggle,Highlight Control,Font Style Switch,Bold & Italic Change,Strong Font Application,Underline Text Adjust,Color Text Effects
thumbnail: https://thmb.techidaily.com/8887df92f9a6ef29a9a0f4d11045d6b1c0399eebd3f27cb0d07dfb8b59734a92.jpg
---

## Turn On/Off Text Emphasis and Highlight Effects on PC

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-hasty-methods-for-mixed-up-youtube-playback-sequence-for-2024/"><u>[New] Hasty Methods for Mixed-Up YouTube Playback Sequence for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-fastest-path-to-amazing-iphone-time-lapses/"><u>[New] The Fastest Path to Amazing iPhone Time-Lapses</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-fundamentals-of-hosting-zoom-meetings-for-2024/"><u>[New] The Fundamentals of Hosting Zoom Meetings for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-effortless-lenovo-screen-casting/"><u>[Updated] 2024 Approved  Effortless Lenovo Screen Casting</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-the-insiders-guide-to-professional-grade-editing-in-windows-10/"><u>[Updated] 2024 Approved  The Insider's Guide to Professional-Grade Editing in Windows 10</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-selections-best-virtual-reality-titles-for-cardboard/"><u>[Updated] Exclusive Selections  Best Virtual Reality Titles for Cardboard</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-from-spectator-to-participant-joining-live-tiktok-events/"><u>[Updated] From Spectator to Participant  Joining Live TikTok Events</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-a-detailed-walkthrough-embedding-online-video-into-ms-presentations/"><u>[Updated] In 2024, A Detailed Walkthrough  Embedding Online Video Into MS Presentations</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-techniques-to-amplify-youtube-video-clarity/"><u>[Updated] Techniques to Amplify YouTube Video Clarity</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-ultimate-collection-of-top-ranked-cost-free-youtube-short-video-downloader-apps-for-2024/"><u>[Updated] The Ultimate Collection of Top-Ranked, Cost-Free YouTube Short Video Downloader Apps for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-discover-the-ultimate-metaverse-glasses-selection/"><u>2024 Approved  Discover the Ultimate Metaverse Glasses Selection</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-the-seamless-way-to-capture-your-favorite-pc-games-6-methods/"><u>2024 Approved  The Seamless Way to Capture Your Favorite PC Games (6 Methods)</u></a></li>
<li><a href="https://change-location.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/adventure-coding-roleplaying-games-in-the-gpt-world/"><u>Adventure Coding: Roleplaying Games in the GPT World</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-poco-x6-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Poco X6 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audioarchitects-building-without-dacast/"><u>AudioArchitects  Building Without DaCast</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-for-secure-nddrive-configuration-win11/"><u>Expert Tips for Secure NDDrive Configuration (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-non-detection-of-devices-on-windows-11-system/"><u>Fixing Non-Detection of Devices on Windows 11 System</u></a></li>
<li><a href="https://windows11.techidaily.com/future-ready-portability-top-windows-laptop-selection-guide/"><u>Future-Ready Portability: Top Windows Laptop Selection Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-the-essentials-6-methods-of-boot-safe-mode-in-windows-11/"><u>Get to the Essentials: 6 Methods of Boot Safe Mode in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-on-apple-iphone-11-pro-by-drfone-ios/"><u>How To Create an Apple Developer Account On Apple iPhone 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-windows-cannot-access-the-specified-device-path-or-file-error/"><u>How to Fix the Windows Cannot Access the Specified Device, Path or File Error</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-lag-and-hitching-in-fortnite-on-your-pc/"><u>How to Resolve Lag and Hitching in Fortnite on Your PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-samsung-galaxy-a54-5g-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-can-i-remove-the-apple-watch-activation-lock-by-iphone-14-without-the-previous-owner-by-drfone-ios/"><u>In 2024, Can I Remove the Apple Watch Activation Lock By iPhone 14 without the Previous Owner?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-honor-70-lite-5g-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Honor 70 Lite 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-supercharge-your-channel-with-smart-youtube-collaborations/"><u>In 2024, Supercharge Your Channel with Smart YouTube Collaborations</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-10-and-11-lengthening-your-pin/"><u>Mastering Windows 10 & 11: Lengthening Your Pin</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/maximizing-linkedin-potential-through-a-premium-subscription/"><u>Maximizing LinkedIn Potential Through a Premium Subscription</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-single-user-policy-settings-in-the-latest-windows-11/"><u>Optimizing Single-User Policy Settings in the Latest Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-unwanted-audio-app-utilization-issue-on-windows/"><u>Overcoming Unwanted Audio App Utilization Issue on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pathways-to-perfectly-understand-and-erase-your-windows-logs/"><u>Pathways to Perfectly Understand & Erase Your Windows Logs</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-windows-appearance-with-popular-photographs/"><u>Personalize Windows' Appearance with Popular Photographs</u></a></li>
<li><a href="https://windows11.techidaily.com/pinnacle-of-windows-portability-top-laptop-selections/"><u>Pinnacle of Windows Portability: Top Laptop Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-disabling-techniques-for-office-and-os-updates/"><u>Quick Disabling Techniques for Office and OS Updates</u></a></li>
<li><a href="https://os-tips.techidaily.com/quick-methods-restore-accidentally-deleted-iphone-notes-within-a-few-minutes/"><u>Quick Methods: Restore Accidentally Deleted iPhone Notes Within a Few Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-to-enhance-laptop-efficiency-on-two-displays/"><u>Quick Steps to Enhance Laptop Efficiency on Two Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-dormant-cpu-temp-control-measures/"><u>Reactivating Dormant CPU Temp Control Measures</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/record-and-relive-your-guide-to-capturing-phonescreens-with-snapchat-for-2024/"><u>Record and Relive  Your Guide to Capturing Phonescreens with Snapchat for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-constant-bios-entry-on-windows-pcs/"><u>Resolving Constant BIOS Entry on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-boot-woes-overcome-support-issues-with-top-fixes/"><u>Secure Boot Woes: Overcome Support Issues with Top Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/snip-tool-engagement-in-windows-11-for-immediate-use/"><u>Snip Tool Engagement in Windows 11 for Immediate Use</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Samsung Galaxy A24? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-avoid-demanded-assets-alerts-on-windows-10and11/"><u>Troubleshooting: Avoid Demanded Assets Alerts on Windows 10&11</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-adding-dolby-atmos-to-windows-11/"><u>Tutorial: Adding Dolby Atmos to Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unclogging-peak-time-gpt-service-in-windows/"><u>Unclogging Peak-Time GPT Service in Windows</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/rsal-templates-galore-for-youtube-crafting/"><u>Universal Templates Galore – For YouTube Crafting</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-administrator-status-in-windows/"><u>Unlocking Administrator Status in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-knowledge-finding-software-install-spots/"><u>Unlocking Windows Knowledge: Finding Software Install Spots</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-gpu-driver-issues-in-win1011/"><u>Unraveling GPU Driver Issues in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/why-no-thumbnails-on-windows-11-find-your-fix-here/"><u>Why No Thumbnails on Windows 11? Find Your Fix Here</u></a></li>
<li><a href="https://windows11.techidaily.com/win-10w11-mastery-quick-paste-snippet-techniques/"><u>Win 10/W11 Mastery: Quick Paste Snippet Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-mastery-unveiling-the-best-techniques-for-credential-management/"><u>Win11 Mastery: Unveiling the Best Techniques for Credential Management</u></a></li>
<li><a href="https://windows11.techidaily.com/window-wizardry-redesigning-cursor-sets/"><u>Window Wizardry: Redesigning Cursor Sets</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>