---
title: "Hide Your Contacts: Delete Email Post Login in Windows"
date: 2024-07-11T21:31:46.512Z
updated: 2024-07-12T21:31:46.512Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hide Your Contacts: Delete Email Post Login in Windows"
excerpt: "This Article Describes Hide Your Contacts: Delete Email Post Login in Windows"
keywords: Hide Contacts Post-Login,Delete Email WIndows,Privacy Settings Mail,Wiindows Email Deletion,Secure Account Details,Logout Remove Addresses,Windows Login Anonymity
thumbnail: https://thmb.techidaily.com/6bec6b49ef7ec1e5a2c1ba4a21123755124d462c63be6599c5bbe4007fea7d1f.jpg
---

## Hide Your Contacts: Delete Email Post Login in Windows

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://windows11.techidaily.com/mending-the-malfunction-of-defrag-in-windows-os/"><u>Mending the Malfunction of Defrag in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-offline-status-of-valve-games-via-steam-desktop-client/"><u>Addressing Offline Status of Valve Games via Steam Desktop Client</u></a></li>
<li><a href="https://windows11.techidaily.com/best-digital-journals-navigate-your-pen-for-windows/"><u>Best Digital Journals: Navigate Your Pen for Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/1717240351461-2024-approved-how-to-use-youtube-analytics-to-grow-your-channel/"><u>2024 Approved  How to Use YouTube Analytics to Grow Your Channel</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-pioneering-techniques-in-youtube-video-recording/"><u>[Updated] 2024 Approved  Pioneering Techniques in YouTube Video Recording</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-vivo-v29-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Vivo V29 FRP</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-gameplay-chronicles-proven-techniques-for-recording-your-sims-epic-saga-in-sims-4/"><u>[Updated] Gameplay Chronicles  Proven Techniques for Recording Your Sim's Epic Saga in Sims 4</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-system-crashes-fix-for-code-0x0000011b-errors/"><u>Ending System Crashes: Fix for Code 0X0000011B Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-default-pdf-reader-on-windows/"><u>How to Change the Default PDF Reader on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-how-to-download-part-of-a-youtube-videos/"><u>[Updated] In 2024, How to Download Part of a YouTube Videos?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-1011-a-workshop-for-custom-pattern-crafting/"><u>Navigating Windows 10/11: A Workshop for Custom Pattern Crafting</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-double-clicking-not-opening-folders-on-windows-1110/"><u>How to Fix Double-Clicking Not Opening Folders on Windows 11/10</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-bypass-enforced-driver-signatures-loading-unverified-drivers/"><u>Methods to Bypass Enforced Driver Signatures, Loading Unverified Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-vmwares-non-boot-windows-11-mistakes/"><u>Preventing VMware's Non-Boot Windows 11 Mistakes</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unopened-sharing-errors-with-geforce-experience/"><u>Correcting Unopened Sharing Errors with GeForce Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-update-issue-with-error-0x8024800c/"><u>Fixing Windows Update Issue with Error 0X8024800C</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-beyond-the-viewfinder-top-6-android-and-ios-video-apps/"><u>[Updated] Beyond the Viewfinder  Top 6 Android and iOS Video Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-mastering-the-loop-a-comprehensive-guide-for-instagram-videographers/"><u>2024 Approved  Mastering the Loop  A Comprehensive Guide for Instagram Videographers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-digital-broadcasting-made-simple-your-essential-guide-to-4-recording-tips/"><u>[New] 2024 Approved  Digital Broadcasting Made Simple  Your Essential Guide to 4 Recording Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-dual-defense-opt-for-single-antivirus-in-windows-systems/"><u>Avoid Dual Defense: Opt for Single Antivirus in Windows Systems</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unlocking-verified-status-essential-strategies-for-increasing-instagram-popularity/"><u>[Updated] In 2024, Unlocking Verified Status  Essential Strategies for Increasing Instagram Popularity</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-5-most-effective-methods-to-unlock-iphone-12-pro-in-lost-mode-by-drfone-ios/"><u>In 2024, 5 Most Effective Methods to Unlock iPhone 12 Pro in Lost Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-dismantle-spotlight-icons-in-win11/"><u>Guide to Dismantle Spotlight Icons in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-non-response-from-printmanagement-msc-errors/"><u>Eliminating Non-Response From 'Printmanagement' MSC Errors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-break-free-from-youtube-with-these-best-27-video-streamers/"><u>[New] Break Free From YouTube with These Best 27 Video Streamers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-reactivating-adobe-on-windows-os/"><u>Mastering the Art of Reactivating Adobe on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proof-computing-with-top-windows-laptop-choices/"><u>Future-Proof Computing with Top Windows Laptop Choices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-real-vs-fake-quick-ways-to-audit-your-insta-circle/"><u>2024 Approved  Real Vs. Fake  Quick Ways to Audit Your Insta Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-user-isolation-for-security-in-win-11/"><u>Mastering User Isolation for Security in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/peeling-back-the-layers-of-runtime-brokers-on-pcs/"><u>Peeling Back the Layers of Runtime Brokers on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-pathway-merging-emulated-game-titles-with-playnite-software/"><u>Guiding Pathway: Merging Emulated Game Titles with Playnite Software</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-tips-for-effective-game-playback-on-microsoft-os/"><u>2024 Approved  Tips for Effective Game Playback on Microsoft OS</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-the-essentials-of-using-tiktok-on-both-macs-and-pcs/"><u>2024 Approved  The Essentials of Using TikTok on Both Macs & PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/rebooted-social-scene-taking-control-of-fb-again-for-2024/"><u>Rebooted Social Scene  Taking Control of Fb Again for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigational-aid-embracing-apple-maps-in-windows-systems/"><u>Navigational Aid: Embracing Apple Maps in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-use-of-toolbars-an-insight-into-mspcm-windows-11/"><u>Mastering the Use of Toolbars: An Insight Into MSPCM, Windows 11</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-honor-x50-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Honor X50? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-restricted-settings-due-to-user-level-administrator-controls/"><u>Eliminating Restricted Settings Due to User-Level Administrator Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/banishing-glitches-fix-windows-11-screen-flash/"><u>Banishing Glitches: Fix Windows 11 Screen Flash</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-switch-off-stuck-theme-on-pc/"><u>Essential Steps to Switch Off Stuck Theme on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/key-to-performance-enhancement-with-windows-lav-filters-use/"><u>Key to Performance Enhancement with Window's LAV Filters Use</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-in-picture-editing-eliminating-backgrounds-effectively/"><u>Precision in Picture Editing: Eliminating Backgrounds Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/defining-windows-corners-straighten-them-out/"><u>Defining Windows' Corners: Straighten Them Out</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-windows-update-pitfalls-0x30017/"><u>Navigating Through Windows Update Pitfalls (0X30017)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/inside-the-arsenal-the-complete-review-of-sj-cam-s6/"><u>Inside the Arsenal  The Complete Review of SJ-CAM S6</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/master-languages-with-mondlys-updated-guide/"><u>Master Languages with Mondly's Updated Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-error-0xc00000f-by-implementing-proper-fixes/"><u>Avoiding Error 0xC00000F by Implementing Proper Fixes</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-track-down-virtual-quest-music-and-effects-for-2024/"><u>Updated Track Down Virtual Quest Music and Effects for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-vivo-s18-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Vivo S18 Pro Devices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-engaging-with-jujutsu-kaisen-fans-through-tiktok-challenges/"><u>[New] 2024 Approved  Engaging with Jujutsu Kaisen Fans Through TikTok Challenges</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-infinix-hot-40i-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Infinix Hot 40i Phone When You Forget the Password</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-8-vr-gaming-accessories/"><u>[Updated] Top 8 VR Gaming Accessories</u></a></li>
<li><a href="https://windows11.techidaily.com/expanding-linux-horizons-through-windows-apps/"><u>Expanding Linux Horizons Through Windows Apps</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-advanced-window-media-editing-techniques-audio-purge-edition/"><u>New 2024 Approved Advanced Window Media Editing Techniques Audio Purge Edition</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-obs-issue-full-screen-bug-fixed-for-2024/"><u>[Updated] Obs Issue  Full-Screen Bug Fixed for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/overcome-error-1-secure-your-minecraft-adventures/"><u>Overcome Error 1: Secure Your Minecraft Adventures</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-balancing-netflix-stream-quality-and-playtime/"><u>[Updated] Balancing Netflix Stream Quality and Playtime</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-mastering-snapchats-highlighted-stories/"><u>2024 Approved  Mastering Snapchat's Highlighted Stories</u></a></li>
</ul></div>
