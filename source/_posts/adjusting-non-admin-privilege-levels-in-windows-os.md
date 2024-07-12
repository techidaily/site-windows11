---
title: Adjusting Non-Admin Privilege Levels in Windows OS
date: 2024-07-11T21:25:19.407Z
updated: 2024-07-12T21:25:19.407Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Non-Admin Privilege Levels in Windows OS
excerpt: This Article Describes Adjusting Non-Admin Privilege Levels in Windows OS
keywords: Windows Privileges Control,Admin Rights Management,User Permissions Edit,Privacy Settings Adjust,Secure OS Access Levels,Non-Admin Privilege Fix,Increase Security, Decrease Risk
thumbnail: https://thmb.techidaily.com/1fd97819f96aea4d97e8ac4ff57edab197b6c14d91b0c90b63f17b606d1e7ada.jpg
---

## Adjusting Non-Admin Privilege Levels in Windows OS

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

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/from-spoken-voice-to-textual-output-in-seconds-whispers-guide/"><u>From Spoken Voice to Textual Output in Seconds - Whisper's Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-steam-install-errors-on-windows-11/"><u>Navigating Through Steam Install Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-pc-hardware-requirement-errors/"><u>Fixing Windows PC Hardware Requirement Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/boldly-block-wi-fi-signals-in-windows/"><u>Boldly Block Wi-Fi Signals in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reviving-your-win-1011-menu-options/"><u>Reviving Your Win 10/11 Menu Options</u></a></li>
<li><a href="https://windows11.techidaily.com/cease-windows-tally-of-new-software-activities/"><u>Cease Windows' Tally of New Software Activities</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-time-management-on-pc-choose-from-these-5-exciting-windows-clock-saver-apps/"><u>Maximize Time Management on PC: Choose From These 5 Exciting Windows Clock Saver Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/decisive-actions-for-dictating-a-successful-window-update/"><u>Decisive Actions for Dictating a Successful Window Update</u></a></li>
<li><a href="https://windows11.techidaily.com/fine-tuning-windows-11s-online-threat-detection/"><u>Fine-Tuning Windows 11'S Online Threat Detection</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/irecast-techniques-for-effective-youtube-streams-for-2024/"><u>[New] WireCast Techniques for Effective Youtube Streams for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/fcpx-optimization-tips-and-tricks-to-reclaim-disk-space/"><u>FCPX Optimization Tips and Tricks to Reclaim Disk Space</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-vivo-y100i-power-5g-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Vivo Y100i Power 5G</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-mastering-discord-live-a-step-by-step-playbook/"><u>2024 Approved  Mastering Discord Live  A Step-by-Step Playbook</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-performance-monitor-not-working-on-windows/"><u>How to Fix the Performance Monitor Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-achieve-unified-fileset-in-two-windows-pcs-via-aoemi/"><u>How to Achieve Unified Fileset in Two Windows PCs via AOEMi</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-crafting-shortcuts-to-store-uwp-apps-on-windows/"><u>Boosting Productivity: Crafting Shortcuts to Store UWP Apps on Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-step-by-step-on-finding-and-crafting-spiritual-ringtones/"><u>[Updated] Step-by-Step on Finding and Crafting Spiritual Ringtones</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-audio-visual-mastery-top-video-editors-with-music-support/"><u>New 2024 Approved Audio-Visual Mastery Top Video Editors with Music Support</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-complete-tutorial-to-turn-gifs-to-stickers-discordwhatsapptelegram/"><u>In 2024, Complete Tutorial to Turn GIFs to Stickers [Discord/WhatsApp/Telegram]</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-adjust-lockout-frequency-after-incorrect-user-credentials-for-windows-11/"><u>How to Adjust Lockout Frequency After Incorrect User Credentials for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-extended-display-setup-without-performance-hit/"><u>Mastering Extended Display Setup Without Performance Hit</u></a></li>
<li><a href="https://windows11.techidaily.com/choosing-between-windows-11-home-and-pro-your-ideal-edition/"><u>Choosing Between Windows 11 Home & Pro: Your Ideal Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/highest-rated-windows-encryption-software-guide-150-chars/"><u>Highest Rated Window's Encryption Software Guide (150 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-masterful-windows-shortcuts-guide/"><u>Boosting Productivity: Masterful Windows Shortcuts Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-isdonedll-error-in-modern-windows-editions/"><u>Addressing ISDone.dll Error in Modern Windows Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-resolving-your-sound-cards-irq-mess/"><u>Decoding and Resolving Your Sound Card's IRQ Mess</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-unsolicited-openings-of-search-bar-win11/"><u>How to Prevent Unsolicited Openings of Search Bar, Win11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-crafting-unique-pfp-ideas-for-distinctive-tiktok-profiles/"><u>[New] 2024 Approved  Crafting Unique PFP Ideas for Distinctive TikTok Profiles</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-quick-setup-installing-snapchat-on-your-mac/"><u>[Updated] In 2024, Quick Setup  Installing Snapchat on Your Mac</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-navigating-two-worlds-a-practical-guide-to-multistream-on-youtube-and-twitch/"><u>2024 Approved  Navigating Two Worlds  A Practical Guide to Multistream on Youtube and Twitch</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-is-itops-feature-set-enough-to-justify-usage-in-2024/"><u>[New] Is ITop's Feature Set Enough to Justify Usage, In 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-heres-a-step-by-step-guide-for-the-powerdirector-color-match-process-also-check-out-the-professional-and-quick-powerdirector-alternati/"><u>Updated 2024 Approved Heres a Step-by-Step Guide for the PowerDirector Color Match Process! Also, Check Out the Professional and Quick PowerDirector Alternative if You Find It a Bit Time-Consuming and Manual</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-your-devices-from-dozing-off-in-windows-11/"><u>How to Prevent Your Devices From Dozing Off in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y36-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-uncovering-the-missing-taskbar-in-full-screen/"><u>Guide to Uncovering the Missing Taskbar in Full Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/maximize-output-win-based-time-management-apps-reviewed/"><u>Maximize Output: Win-Based Time Management Apps Reviewed</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-passcode-alterations-effortlessly/"><u>Navigating Windows Passcode Alterations Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-screen-order-in-pc/"><u>How to Change Screen Order in PC</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-from-beginner-to-pro-10-free-video-editors-for-ubuntu-users/"><u>2024 Approved From Beginner to Pro 10 Free Video Editors for Ubuntu Users</u></a></li>
<li><a href="https://windows11.techidaily.com/a-glimpse-at-future-ready-windows-with-update-22h2s-features/"><u>A Glimpse at Future-Ready Windows with Update #22H2's Features</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-laptops-screen-with-yellowish-discoloration/"><u>Correcting Laptop's Screen with Yellowish Discoloration</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-propel-participation-through-tailored-story-inquiry-designs/"><u>[Updated] 2024 Approved  Propel Participation Through Tailored Story Inquiry Designs</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-convergence-the-best-6-compatible-android-apps-on-windows-11/"><u>Master the Convergence: The Best 6 Compatible Android Apps on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/essential-10-royale-confrontations-for-2024/"><u>Essential 10 Royale Confrontations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/introducing-the-widget-toolbar-features-for-win11-users/"><u>Introducing the Widget Toolbar Features for Win11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/clipchamp-patch-enable-installation-in-windows-11/"><u>ClipChamp Patch: Enable Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/monitor-positioning-tactics-in-windows/"><u>Monitor Positioning Tactics in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-innovate-how-you-connect-with-tech-best-text-interpretation-tools-on-mac/"><u>2024 Approved  Innovate How You Connect with Tech  Best Text Interpretation Tools on Mac</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-deep-dive-into-the-features-of-lgs-ultrafine-4k-display-for-2024/"><u>[Updated] Deep Dive Into the Features of LG's UltraFine 4K Display for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-adding-words-to-pictures-easy-photo-text-editing-tips/"><u>[Updated] Adding Words to Pictures  Easy Photo Text Editing Tips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-keep-unwanted-content-away-from-your-computer-and-phone/"><u>[New] In 2024, How to Keep Unwanted Content Away From Your Computer and Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehending-the-safeguarded-state-of-windows-11/"><u>Comprehending the Safeguarded State of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/longer-is-stronger-securing-devices-with-extended-windows-11-pins/"><u>Longer Is Stronger: Securing Devices with Extended Windows 11 Pins</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-strategies-for-isolating-unfamiliar-users-in-win-11/"><u>Effective Strategies for Isolating Unfamiliar Users in Win 11</u></a></li>
</ul></div>
