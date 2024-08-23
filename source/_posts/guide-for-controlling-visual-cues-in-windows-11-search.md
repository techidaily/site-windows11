---
title: Guide for Controlling Visual Cues in Windows 11 Search
date: 2024-08-22T21:38:16.524Z
updated: 2024-08-23T21:38:16.524Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide for Controlling Visual Cues in Windows 11 Search
excerpt: This Article Describes Guide for Controlling Visual Cues in Windows 11 Search
keywords: Windows 11 Vision Control,Visual Cues Management,11 Search Interface Guide,Windows 11 UI Optimization,PC Search Feature Adjustment,Altering Window 11 Display,Enhancing Search Visibility
thumbnail: https://thmb.techidaily.com/f0dbd5a21adf0257efb4cfc535a5b1745bbe68be5c6511e0bd704dc50cbfa331.jpg
---

## Guide for Controlling Visual Cues in Windows 11 Search

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-information.techidaily.com/new-clipcomposers-journey-thorough-review-of-androvid/"><u>[New] ClipComposer's Journey – Thorough Review of AndroVid</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-mastery-over-your-memories-fetching-facebook-status-videos/"><u>[New] In 2024, Mastery Over Your Memories  Fetching Facebook Status Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-maximizing-viewability-and-engagement-understanding-facebook-video-ratios-for-2024/"><u>[New] Maximizing Viewability & Engagement  Understanding Facebook Video Ratios for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unveiling-the-most-effective-methods-for-your-hp-laptop-recordings-for-2024/"><u>[New] Unveiling the Most Effective Methods for Your HP Laptop Recordings for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-metrics-mastery-gain-more-followers/"><u>2024 Approved  Instagram Metrics Mastery - Gain More Followers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/deciding-the-best-skype-audio-capture-of-2023/"><u>Deciding the Best Skype Audio Capture of 2023</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-empty-sections-of-navigation-view/"><u>Fixing Empty Sections of Navigation View</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/funnygenius-create-and-share-memes-for-2024/"><u>FunnyGenius  Create and Share Memes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-restore-functional-drag-and-drop-in-windows-11/"><u>Guide: Restore Functional Drag-and-Drop in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/harnessing-powertoys-for-seamless-international-mouse-usage/"><u>Harnessing PowerToys for Seamless International Mouse Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-windows-auditory-restart-troubles-on-wake/"><u>How to Rectify Windows Auditory Restart Troubles on Wake</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-spur-microsoft-edge-speed-in-windows-1011/"><u>How to Spur Microsoft Edge Speed in Windows 10/11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/hype-generator-chief-architect-for-2024/"><u>Hype Generator Chief Architect for 2024</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-contacts-from-apple-iphone-xs-to-iphone-quickly-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Contacts from Apple iPhone XS to iPhone Quickly | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-from-apple-iphone-12-mini-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out From Apple iPhone 12 mini How to Bypass?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-financial-incentives-behind-vlogger-rating-videos/"><u>In 2024, Financial Incentives Behind Vlogger Rating Videos?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nokia-c12-pro-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nokia C12 Pro to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-oppo-find-x6-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Oppo Find X6 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-overcoming-windows-activation-fault-error-0x803f700f/"><u>Mastery of Overcoming Windows Activation Fault: Error 0X803F700f</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-enhances-windows-11-with-ai-taskbar-companion-for-effortless-management/"><u>Microsoft Enhances Windows 11 with AI Taskbar Companion for Effortless Management</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-account-lockout-period-post-failed-logon/"><u>Modifying Account Lockout Period Post-Failed Logon</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-0xc00000f-issue-on-your-pc-easily/"><u>Overcoming 0Xc00000f Issue on Your PC Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-printer-connection-glitches-in-windows/"><u>Overcoming Printer Connection Glitches in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tips-selecting-superior-windows-11-drawers/"><u>Pro Tips: Selecting Superior Windows 11 Drawers</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-unnecessary-batch-jobs/"><u>Reducing Unnecessary Batch Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-non-functional-audio-on-win-10/"><u>Remedy for Non-Functional Audio on Win 10</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-system-hiccups-with-these-10-windows-tools/"><u>Resolve System Hiccups with These 10 Windows Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-regedit-absent-on-windows-systems/"><u>Resolving Regedit Absent on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-security-fault-in-1011-edition/"><u>Resolving Windows Security Fault in 10/11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-computer-with-windows-hello-fingerprint/"><u>Securing Your Computer with Windows Hello Fingerprint</u></a></li>
<li><a href="https://windows11.techidaily.com/starting-diagnostics-five-quick-steps-in-windows/"><u>Starting Diagnostics: Five Quick Steps in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/terminal-tactics-pinpointing-your-ip-in-windows/"><u>Terminal Tactics: Pinpointing Your IP in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-twinning-your-tablet-and-pc-in-w11/"><u>The Essential Guide to Twinning Your Tablet and PC in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-eradicate-the-abrupt-termination-error-in-roblox-games/"><u>Tips to Eradicate the Abrupt Termination Error in Roblox Games</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-restrictions-of-secure-boot-and-tpm-using-rufus/"><u>Unlocking the Restrictions of Secure Boot & TPM Using Rufus</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-exploring-the-finest-free-web-integrated-digital-audio-workstations-for-2024/"><u>Updated Exploring the Finest Free, Web-Integrated Digital Audio Workstations for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/why-do-computers-have-a-windows-batch-file/"><u>Why Do Computers Have a Windows Batch File?</u></a></li>
<li><a href="https://windows11.techidaily.com/win-your-way-out-of-secure-boot-stumbles-with-these-fixes/"><u>Win Your Way Out of Secure Boot Stumbles with These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-advancements-what-the-new-update-brings-in/"><u>Windows 11 Advancements: What the New Update Brings In</u></a></li>
<li><a href="https://windows11.techidaily.com/workaround-to-avoid-discord-autostarting-on-pc/"><u>Workaround to Avoid Discord Autostarting on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>