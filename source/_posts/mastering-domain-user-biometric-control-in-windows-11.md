---
title: Mastering Domain User Biometric Control in Windows 11
date: 2024-07-11T21:37:12.189Z
updated: 2024-07-12T21:37:12.189Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Domain User Biometric Control in Windows 11
excerpt: This Article Describes Mastering Domain User Biometric Control in Windows 11
keywords: Windows 11 BioControl,User Biometrics W11,Win11 Security Checks,Digital ID Windows 11,Access Control W11,W11 User Authentication,Biometric Domains W11
thumbnail: https://thmb.techidaily.com/9eaae45a5ae000b67c414e7abf4faf363e86f993286beb6923a862b27612bc1e.jpg
---

## Mastering Domain User Biometric Control in Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/split-screen-style-selecting-separate-themes-for-each-windows-display/"><u>Split Screen Style: Selecting Separate Themes for Each Windows Display</u></a></li>
<li><a href="https://windows11.techidaily.com/silencing-the-cacophony-soundcard-irq-fixes/"><u>Silencing the Cacophony: Soundcard IRQ Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-enhancement-building-engaging-slideshows-and-fixing-windows-11-photo-flaws/"><u>The Art of Image Enhancement: Building Engaging Slideshows & Fixing Windows 11 Photo Flaws</u></a></li>
<li><a href="https://windows11.techidaily.com/refinement-of-your-touchpad-settings-for-optimal-interaction/"><u>Refinement of Your Touchpad Settings for Optimal Interaction</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-save-and-access-onedrive-around-clients/"><u>Tricks: Save & Access OneDrive Around Clients</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-tips-for-optimizing-wsl-2-on-modern-windows/"><u>Top 5 Tips for Optimizing WSL 2 on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-user-biometric-use-by-domains/"><u>Enabling/Disabling User Biometric Use by Domains</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-cataloging-fb-video-ratios/"><u>[Updated] 2024 Approved  Cataloging FB Video Ratios</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-closed-folder-issues-via-double-clicks-in-w10w11/"><u>Resolving Closed Folder Issues via Double-Clicks in W10/W11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-techniques-for-fisheye-sphere-capture/"><u>2024 Approved  Innovative Techniques for Fisheye Sphere Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-your-security-crafting-unique-lock-patterns-for-windows-11/"><u>Revolutionize Your Security: Crafting Unique Lock Patterns for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-nvidia-configuration-a-guide-for-winx-users/"><u>Restoring Lost NVIDIA Configuration: A Guide for WinX Users</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-adjusting-touchpad-sensitivity-in-windows/"><u>The Ultimate Guide to Adjusting Touchpad Sensitivity in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-mastering-audio-find-and-test-your-best-free-online-editor-options-in-these-top-6-selections-for-2024/"><u>Updated Mastering Audio Find and Test Your Best Free Online Editor Options in These Top 6 Selections for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-gamers-manual-to-winning-with-windows/"><u>The Complete Gamers' Manual to Winning With Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamlined-templates-the-essential-ae-text-list-for-2024/"><u>Streamlined Templates  The Essential AE Text List for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reveal-hidden-5ghz-networks-on-windows-11-quick-remedies/"><u>Reveal Hidden 5GHz Networks on Windows 11: Quick Remedies</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-future-of-editing-decoded-powerdirector-app-24-reviewed-and-explained/"><u>[Updated] The Future of Editing Decoded  PowerDirector App '24 Reviewed & Explained</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-navigating-the-nuances-of-social-interactions-update-in-discord/"><u>[Updated] In 2024, Navigating the Nuances of Social Interactions  Update in Discord</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-conversion-mastery-tips-and-tricks-from-the-best-ogg-tools-for-2024/"><u>Updated Conversion Mastery Tips and Tricks From the Best OGG Tools for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-search-bar-autonomy-in-windows-11-interface/"><u>Preventing Search Bar Autonomy in Windows 11 Interface</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-honor-v-purse-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Honor V Purse to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-best-free-video-editors-with-no-watermark/"><u>New 2024 Approved Best Free Video Editors with No Watermark</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-getting-started-on-discord-a-comprehensive-guide-to-broadcasting-for-2024/"><u>[New] Getting Started on Discord  A Comprehensive Guide to Broadcasting for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windowed-discord-for-flawless-search-experience/"><u>Optimizing Windowed Discord for Flawless Search Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalizing-fall-guys-gaming-experience-after-disconnections-on-windows/"><u>Revitalizing Fall Guys Gaming Experience After Disconnections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-permanent-delete-toolbar-in-windows-1011s-trash/"><u>Setting Up a Permanent Delete Toolbar in Windows 10/11'S Trash</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-expert-guide-to-snagging-twitter-gifs-pc/"><u>[New] Expert Guide to Snagging Twitter GIFs (PC)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-ultimate-drone-list-to-maximize-gopro-video-quality-for-2024/"><u>[Updated] Ultimate Drone List to Maximize GoPro Video Quality for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-windows-no-audio-output-issue/"><u>Solving Windows: 'No Audio Output' Issue</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-samsung-galaxy-s23plus-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Samsung Galaxy S23+ Location on Skout | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagrams-hottest-meme-accounts-laughter-and-sorrow-sideshow/"><u>[Updated] In 2024, Instagram's Hottest Meme Accounts  Laughter & Sorrow Sideshow</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/virtual-venue-face-off-assessing-obs-and-twitch-studios-for-2024/"><u>Virtual Venue Face-Off  Assessing OBS & Twitch Studios for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-turning-beauty-blogging-into-cash/"><u>In 2024, Turning Beauty Blogging Into Cash</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-developing-eye-catching-podcast-previews/"><u>[New] In 2024, Developing Eye-Catching Podcast Previews</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-list-of-6-performance-monitor-apps-for-pcs/"><u>The Ultimate List of 6 Performance Monitor Apps For PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/reconciling-windows-game-bar-with-inferior-hardware/"><u>Reconciling Windows Game Bar with Inferior Hardware</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-screen-recording-101-using-filmora-scrn-to-capture-your-desktop/"><u>2024 Approved Screen Recording 101 Using Filmora Scrn to Capture Your Desktop</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elite-7-dslr-options-superior-for-professional-videography/"><u>[Updated] In 2024, Elite 7 DSLR Options Superior for Professional Videography</u></a></li>
</ul></div>
