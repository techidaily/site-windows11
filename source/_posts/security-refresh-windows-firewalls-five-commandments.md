---
title: "Security Refresh: Windows Firewall's Five Commandments"
date: 2024-08-27T16:13:32.554Z
updated: 2024-08-28T16:13:32.554Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Refresh: Windows Firewall's Five Commandments"
excerpt: "This Article Describes Security Refresh: Windows Firewall's Five Commandments"
keywords: Firewall Fundamentals,Windows Security Update,Digital Safety Commands,Cyber Protection Basics,Secure Networking Essentials,Safe Windows Guard,Commandments of Safety
thumbnail: https://thmb.techidaily.com/964056d5a42fd554adb9e457ea6c862e5065495ad6b360af575e17501ef981e0.png
---

## Security Refresh: Windows Firewall's Five Commandments

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://youtube-zero.techidaily.com/024-approved-launch-your-channel-8-entry-level-digital-course-series/"><u>[New] 2024 Approved  Launch Your Channel  8 Entry-Level Digital Course Series</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-crafting-the-perfect-end-screen-youtube-template-guidebook-for-2024/"><u>[New] Crafting the Perfect End Screen - YouTube Template Guidebook for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-saga-scholars-society-premier-picks/"><u>[New] Saga Scholars Society - Premier Picks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-ace-driving-realism-series-best-5/"><u>[Updated] 2024 Approved  Ace Driving Realism Series (Best 5)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-expert-screencast-wisdom-key-facts-and-strategies/"><u>[Updated] 2024 Approved  Expert Screencast Wisdom  Key Facts and Strategies</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-tricks-for-swift-vimeo-watch/"><u>[Updated] 2024 Approved  Tricks for Swift Vimeo Watch</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-pinnacle-motorsport-replicas-top-5-for-2024/"><u>[Updated] Pinnacle Motorsport Replicas (Top 5) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-invisible-realities-of-stories-a-closer-look-for-viewers/"><u>2024 Approved  Invisible Realities of Stories  A Closer Look for Viewers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/avoiding-pitfalls-spotting-top-5-manipulative-practices-in-automated-conversations/"><u>Avoiding Pitfalls: Spotting Top 5 Manipulative Practices in Automated Conversations</u></a></li>
<li><a href="https://win-answers.techidaily.com/causes-and-solutions-for-repeated-failures-in-cod-modern-warfare/"><u>Causes and Solutions for Repeated Failures in COD: Modern Warfare</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/demystifying-facebooks-blue-image-symbol/"><u>Demystifying Facebook's Blue Image Symbol</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-overcoming-outlook-crashing-issues/"><u>Essential Guide: Overcoming Outlook Crashing Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-variance-in-offline-versus-online-windows-installation-methods/"><u>Exploring Variance in Offline Versus Online Windows Installation Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-resolving-winerror-0x8007043c-on-media-creator/"><u>Guide to Resolving WinError 0X8007043C on Media Creator</u></a></li>
<li><a href="https://windows11.techidaily.com/halting-windows-edge-tab-loads-properly/"><u>Halting Windows Edge Tab Loads Properly</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-window-11-customization-marvels/"><u>Hidden Window 11 Customization Marvels</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correctly-evaluate-processor-load-using-task-manager/"><u>How to Correctly Evaluate Processor Load Using Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-enable-device-driver-loading-in-win11/"><u>How to Enable Device Driver Loading in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-this-sign-in-option-is-disabled-because-of-failed-sign-in-attempts-on-windows/"><u>How to Fix This Sign-In Option Is Disabled Because of Failed Sign-In Attempts on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-get-past-a-non-starting-battlenet-interface/"><u>How to Get Past a Non-Starting Battle.net Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-the-incorrect-token-call-error-on-win11/"><u>How to Rectify the “Incorrect Token Call” Error on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-switch-off-mobility-features-on-win-11/"><u>How To Switch Off Mobility Features on Win 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-realme-11-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Realme 11 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-honor-play-7t-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Honor Play 7T FRP In 3 Different Ways</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-mastering-movies-the-best-of-viral-tiktok-creations-top-10/"><u>In 2024, Mastering Movies  The Best of Viral TikTok Creations (Top 10)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-navigating-instagrams-self-verification-maze/"><u>In 2024, Navigating Instagram's Self-Verification Maze</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-huawei-p60-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Huawei P60 Phone Network-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/keyboard-prodigy-tips-for-windows-photoshop/"><u>Keyboard Prodigy Tips for Windows Photoshop</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-regaining-win-folder-entry/"><u>Master the Art of Regaining Win Folder Entry</u></a></li>
<li><a href="https://windows11.techidaily.com/masterful-cursor-adjustments-on-windows-11-systems/"><u>Masterful Cursor Adjustments on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-heic-jpeg-conversions-on-windows/"><u>Mastering HEIC-JPEG Conversions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-networks-with-precision-windows-ping-mastery/"><u>Navigating Networks with Precision: Windows' Ping Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-11-typing-troubles-addressing-zerox-code-0x80049dd3/"><u>Navigating Through Windows 11 Typing Troubles: Addressing Zerox (Code: 0X80049DD3)</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-launch-issues-with-monster-hunter-stories-2-wings-of-ruin-solutions-and-help/"><u>Overcoming Launch Issues with Monster Hunter Stories 2: Wings of Ruin - Solutions & Help</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-resource-already-active-issue-on-windows-11/"><u>Overcoming Resource Already Active Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11s-uptime-failure-error-code-0x80246007/"><u>Overcoming Windows 11’S Uptime Failure: Error Code 0X80246007</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723010631772-phasmophobia-vr-malfunction-heres-how-you-can-repair-it/"><u>Phasmophobia VR Malfunction? Here's How You Can Repair It</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-directory-design-mass-folder-formation-strategies-for-windows-1011-users/"><u>Proactive Directory Design: Mass Folder Formation Strategies for Windows 10/11 Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/proven-instagram-analysis-apps-enhance-engagement-growth-and-conversion-rates-for-2024/"><u>Proven Instagram Analysis Apps  Enhance Engagement, Growth & Conversion Rates for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-defenders-a-step-by-step-guide-for-five-common-issues/"><u>Reactivating Defenders: A Step-by-Step Guide for Five Common Issues</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-messages-after-oppo-a38-has-been-deleted-by-fonelab-android-recover-messages/"><u>Recover your messages after Oppo A38 has been deleted</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstate-audio-preferences-winvolume-issue-resolution/"><u>Reinstate Audio Preferences: WinVolume Issue Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidias-geforce-error-x0001-on-windows-1011/"><u>Resolving Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-rpc-issues-on-windows-key-strategies/"><u>Resolving RPC Issues on Windows: Key Strategies</u></a></li>
<li><a href="https://extra-resources.techidaily.com/review-ultra-hd-blade-cam-at-full-spectrum/"><u>Review  Ultra HD Blade Cam at Full Spectrum</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/rhythms-of-introduction-10-must-hear-songs-for-podcast-opens-for-2024/"><u>Rhythms of Introduction  10 Must-Hear Songs for Podcast Opens for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-realign-file-history-configurations-in-windows/"><u>Steps to Realign File History Configurations in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-workflow-with-the-ultimate-win-11-guide/"><u>Streamline Your Workflow with the Ultimate Win 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-windows-write-operations-error/"><u>Tackling Windows Write Operations Error</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-windows-11-widget-bar-activation/"><u>The Essential Guide to Windows 11 Widget Bar Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-and-tricks-for-restoring-win11s-5g-link/"><u>Tips and Tricks for Restoring Win11’s 5G Link</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-windows-11-help-app-restoration/"><u>Tips for Windows 11 Help App Restoration</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721466516371-trouble-receiving-late-imessages-discover-9-effective-solutions/"><u>Trouble Receiving Late iMessages? Discover 9 Effective Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-programming-file-formats/"><u>Understanding Windows' Programming File Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-windows-1011-8-innovative-personalization-techniques/"><u>Unlock Windows 10/11: 8 Innovative Personalization Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-control-panel-access-methods/"><u>Unveiling Control Panel Access Methods</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/why-embrace-a-second-language-when-youre-over-50/"><u>Why Embrace a Second Language When You're Over 50?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tech-tip-validate-audiovideo-before-participating/"><u>Windows Tech Tip: Validate Audio/Video Before Participating</u></a></li>
</ul></div>
