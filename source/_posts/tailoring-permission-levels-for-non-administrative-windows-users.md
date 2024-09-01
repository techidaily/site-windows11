---
title: Tailoring Permission Levels for Non-Administrative Windows Users
date: 2024-08-31T22:10:01.242Z
updated: 2024-09-01T22:10:01.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailoring Permission Levels for Non-Administrative Windows Users
excerpt: This Article Describes Tailoring Permission Levels for Non-Administrative Windows Users
keywords: User Permissions Windows,Limited Privilege Windows,Non-Admin Access Control,Secure Windows Settings,Customize Window Privileges,Restrictive Windows Users,Safe Windows User Levels
thumbnail: https://thmb.techidaily.com/bbd20210fc5074f713b02b244d2b1993bd6b418eec110dce123959527009d1b5.png
---

## Tailoring Permission Levels for Non-Administrative Windows Users

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/n-2024-streaming-showdown-summary-fb-live-yt-live-and-twitter-spaces/"><u>[New] In 2024, Streaming Showdown Summary  FB LIVE, YT Live & Twitter Spaces</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-unveiling-the-magic-of-vr-environments/"><u>[Updated] In 2024, Unveiling the Magic of VR Environments</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-unlocking-fullscreen-footage-screen-recording-made-simple-for-mac-users/"><u>[Updated] Unlocking Fullscreen Footage  Screen Recording Made Simple for Mac Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-simplify-slide-sharing-at-work-webcam-assisted-tips/"><u>2024 Approved  Simplify Slide Sharing at Work  Webcam-Assisted Tips</u></a></li>
<li><a href="https://facebook.techidaily.com/archive-every-echo-comprehensive-history-collection-on-social-media/"><u>Archive Every Echo: Comprehensive History Collection on Social Media</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/best-look-ups-for-gopro-movies-select-15-luts/"><u>Best Look-Ups for GoPro Movies  Select 15 LUTs</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-steps-for-swiftly-dealing-with-unspecified-obs-recording-problem/"><u>Expert Steps for Swiftly Dealing with Unspecified OBS Recording Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/exposing-the-trojan-terror-defending-your-windows-against-wacatacbml/"><u>Exposing the Trojan Terror: Defending Your Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-pcs-missing-piece-how-to-restore-bluetooth-on-windows-11/"><u>Fix Your PC's Missing Piece: How to Restore Bluetooth on Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-installation-failed-a-step-by-step-guide-to-a-smooth-disco-experience/"><u>Fixing 'Installation Failed': A Step-by-Step Guide to a Smooth Disco Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/from-version-6-to-7-smoothly-upgrading-virtualbox-on-your-win11-device/"><u>From Version 6 to 7: Smoothly Upgrading VirtualBox on Your Win11 Device</u></a></li>
<li><a href="https://windows11.techidaily.com/get-ahead-top-strategies-to-master-the-windows-11-taskbar/"><u>Get Ahead: Top Strategies to Master the Windows 11 Taskbar</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722962857082-get-your-linksys-ae25n-wireless-network-up-and-running-fast-download-the-latest-drivers-here/"><u>Get Your Linksys AE25n Wireless Network Up & Running Fast – Download the Latest Drivers Here</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-privilege-related-setup-hiccups/"><u>Guiding Users Through Privilege-Related Setup Hiccups</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/how-to-find-and-change-your-youtube-channel-url-super-easy-in-2024/"><u>How to Find and Change Your YouTube Channel URL – Super Easy, In 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/how-to-successfully-download-images-from-icloud-on-ios-1211-ultimate-guide-with-7-pro-tips/"><u>How to Successfully Download Images From iCloud on iOS 12/11 – Ultimate Guide with 7 Pro Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-snapping-windows-uac-alerts/"><u>How-To: Snapping Windows UAC Alerts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-accessing-your-favorite-pins-top-5-no-fee-download-tools/"><u>In 2024, Accessing Your Favorite Pins  Top 5 No-Fee Download Tools</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-life360-from-tracking-you-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Stop Life360 from Tracking You On Apple iPhone 12 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/learn-the-hack-no-more-pins-for-windows-11-projecting/"><u>Learn the Hack: No More PINs for WIndows 11 Projecting</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-outlook-preview-in-windows-11-pro/"><u>Mastering Outlook Preview in Windows 11 Pro</u></a></li>
<li><a href="https://driver-install.techidaily.com/razer-gaming-mouse-driver-quick-guide/"><u>Razer Gaming Mouse Driver Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/razer-synapse-issues-step-by-step-troubleshooting-for-w11w10/"><u>Razer Synapse Issues: Step-by-Step Troubleshooting for W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unsuccessful-discord-updates-for-windows-users/"><u>Resolving Unsuccessful Discord Updates for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-printer-service-offline-errors/"><u>Resolving Windows Printer Service Offline Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/rush-your-print-jobs-how-to-spur-a-slow-windows-printer/"><u>Rush Your Print Jobs: How to Spur a Slow Windows Printer</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-background-load-a-windows-guide/"><u>Taming the Background Load: A Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-effective-toolbar-navigation-with-mspcm-on-w11/"><u>The Art of Effective Toolbar Navigation with MSPCM on W11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-mfc42dll-not-found-expert-tips-and-solutions/"><u>Troubleshooting 'mfc42.dll Not Found' - Expert Tips & Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-inputs-in-win11s-sleep-mode/"><u>Troubleshooting Unresponsive Inputs in Win11's Sleep Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-unresponsive-programs-in-windows-os/"><u>Troubleshooting Unresponsive Programs in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-sd-card-windows-explorer-fix-guide/"><u>Unveil SD Card: Windows Explorer Fix Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-reaping-the-digital-rewards-top-10-plugin-essentials-for-streamlined-editing-workflows/"><u>Updated 2024 Approved Reaping the Digital Rewards Top 10 Plugin Essentials for Streamlined Editing Workflows</u></a></li>
<li><a href="https://windows11.techidaily.com/w11-pros-best-offers-save-and-elevate-your-spend/"><u>W11 Pro's Best Offers: Save & Elevate Your Spend</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-mishap-resolution-fix-for-error-code-0x0000011b/"><u>Win11 Mishap Resolution: Fix for Error Code 0X0000011B</u></a></li>
<li><a href="https://windows11.techidaily.com/win11s-ingenious-techniques-for-gathering-info/"><u>Win11's Ingenious Techniques for Gathering Info</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>