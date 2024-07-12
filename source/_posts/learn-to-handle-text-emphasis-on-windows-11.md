---
title: Learn to Handle Text Emphasis on Windows 11
date: 2024-07-11T21:53:04.581Z
updated: 2024-07-12T21:53:04.581Z
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

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

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

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

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
<li><a href="https://windows11.techidaily.com/smoothening-playback-speed-in-vlc-for-windows/"><u>Smoothening Playback Speed in VLC for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-no-sync-option-on-steam-library-error/"><u>Tackling the No Sync Option on Steam Library Error</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-top-4-ringtone-cuuter-to-use/"><u>New Top 4 Ringtone Cuuter to Use</u></a></li>
<li><a href="https://windows11.techidaily.com/hidden-behind-pretense-apps-slowdown-your-modern-windows/"><u>Hidden Behind Pretense: Apps Slowdown Your Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-screen-resets-for-windows-users/"><u>Streamlining Screen Resets for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-mobile-software-for-windows-pc-owners-on-android/"><u>Ideal Mobile Software for Windows PC Owners on Android</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-automatic-screenshore-changes-in-win11/"><u>Preventing Automatic Screenshore Changes in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-file-scooping-6-routes-to-data-secrets/"><u>Swift File Scooping: 6 Routes to Data Secrets</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-folders-to-the-context-menu-in-windows-11/"><u>How to Add Folders to the Context Menu in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-virtual-meetings-a-lightweight-approach/"><u>Redefining Virtual Meetings: A Lightweight Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-discord-from-starting-with-windows-boot/"><u>Preventing Discord From Starting with Windows Boot</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-solving-win-1011-ad-ds-printer-problems-efficiently/"><u>Guide to Solving Win 10/11 AD DS Printer Problems Efficiently</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-elevating-creative-content-vimeo-vs-youtubes-approach-for-2024/"><u>[New] Elevating Creative Content  Vimeo vs YouTube's Approach for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-timelapse-magic-with-your-gopro/"><u>[New] Unlocking Timelapse Magic with Your GoPro</u></a></li>
<li><a href="https://windows11.techidaily.com/is-windows-11-running-slow-or-lagging-on-your-computer-7-ways-to-fix-it/"><u>Is Windows 11 Running Slow or Lagging on Your Computer? 7 Ways to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/installing-icloud-is-easy-troubleshoot-issues-on-windows/"><u>Installing iCloud Is Easy: Troubleshoot Issues on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-defaults-resetting-win11-admin-permissions/"><u>The Path to Defaults: Resetting Win11 Admin Permissions</u></a></li>
<li><a href="https://windows11.techidaily.com/interpretation-of-the-red-x-icon-in-file-management/"><u>Interpretation of the Red “X” Icon in File Management</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-on-screen-capture-aid/"><u>[New] In 2024, On-Screen Capture Aid</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-snipping-the-best-moments-of-melodies-building-your-own-caller-id-tunes-for-2024/"><u>New Snipping the Best Moments of Melodies Building Your Own Caller ID Tunes for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-media-error-input-not-recognized-by-vlc/"><u>How to Overcome Media Error: Input Not Recognized by VLC</u></a></li>
<li><a href="https://windows11.techidaily.com/secrets-to-savings-on-windows-10-key-focused-strategies/"><u>Secrets to Savings on Windows 10: Key-Focused Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-key-windows-processes-for-virus-alerts/"><u>Highlighting Key Windows Processes for Virus Alerts</u></a></li>
<li><a href="https://windows11.techidaily.com/pc-files-on-ios-via-smb-share-connection/"><u>PC Files on iOS via SMB Share Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-past-the-activation-hurdle-in-microsoft-office/"><u>Navigating Past the Activation Hurdle in Microsoft Office</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-enhance-video-visibility-using-creator-studio-wisdom/"><u>[Updated] 2024 Approved  Enhance Video Visibility Using Creator Studio Wisdom</u></a></li>
<li><a href="https://extra-resources.techidaily.com/decorate-your-windows-11-photos-app-add-aesthetic-filters-plus-audio-streams/"><u>Decorate Your Windows 11 Photos App  Add Aesthetic Filters + Audio Streams</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-generating-gpo-data-with-gpresult/"><u>The Essential Guide to Generating GPO Data with GPResult</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/make-my-video-perfectly-fit-instagram-for-2024/"><u>Make My Video Perfectly Fit Instagram for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-the-future-ui-design-with-new-folder-integration-in-windows-11/"><u>Navigate the Future UI Design with New Folder Integration in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-must-try-titles-for-tranquil-touchscreen-time/"><u>2024 Approved  Must-Try Titles for Tranquil Touchscreen Time</u></a></li>
<li><a href="https://windows11.techidaily.com/triumph-over-outdated-updates-winning-strategies-revealed/"><u>Triumph Over Outdated Updates: Winning Strategies Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-resolve-high-dpi-screen-problems-on-pc/"><u>Strategies to Resolve High DPI Screen Problems on PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/optimal-offerings-best-devices-for-hd-video-processing-for-2024/"><u>Optimal Offerings  Best Devices for HD Video Processing for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/clear-images-made-easy-picart-backdrop-takedown-technique-for-2024/"><u>Clear Images Made Easy  PicArt Backdrop Takedown Technique for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplify-pc-upgrade-newly-installed-gb-board-drivers/"><u>Simplify PC Upgrade - Newly Installed GB Board Drivers</u></a></li>
<li><a href="https://article-tips.techidaily.com/10plus-video-presentation-ideas-to-inspire-you/"><u>10+ Video Presentation Ideas to Inspire You</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unveiling-the-silent-conversation-of-italian-hands/"><u>Unveiling the Silent Conversation of Italian Hands</u></a></li>
<li><a href="https://windows11.techidaily.com/reestablishing-copy-pasting-efficiency-across-browsers/"><u>Reestablishing Copy-Pasting Efficiency Across Browsers</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-win11-with-powertoys-installation/"><u>Streamlining Win11 with PowerToys Installation</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-ultimate-guide-to-box-enthusiasm/"><u>[Updated] The Ultimate Guide to Box Enthusiasm</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-win11-ghost-cursor-problem/"><u>Fixing Win11 Ghost Cursor Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-file-explorer-opening-tabs-in-windows-11/"><u>Mastery of File Explorer: Opening Tabs in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-direct-your-media-essential-flv-to-youtube-applications-ranked/"><u>[New] Direct Your Media  Essential Flv-to-YouTube Applications Ranked</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ssential-tutorial-for-youtube-studio-editor-use/"><u>The Essential Tutorial for YouTube Studio Editor Use</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-deep-learning-of-ai-video-recognition-guide/"><u>New Deep Learning of AI Video Recognition - Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-start-adding-windows-hello-to-your-pc/"><u>Quick Start: Adding Windows Hello to Your PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-personalized-branding-craft-your-logo-from-free-designs/"><u>2024 Approved  Personalized Branding  Craft Your Logo From Free Designs</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pc-performance-hiccups-in-warhammer-40k-boltgun/"><u>Tackling PC Performance Hiccups in Warhammer 40K Boltgun</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-narzo-60-5g-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Realme Narzo 60 5G Bootloader Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-rejuvenate-a-dysfunctional-search-bar-in-windows-11/"><u>Guide to Rejuvenate a Dysfunctional Search Bar in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-restore-your-desktop-icon-positions-on-windows/"><u>How to Restore Your Desktop Icon Positions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-the-windows-application-net-demand-error/"><u>Resolving the Windows Application .NET Demand Error</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-ps4-live-broadcasting-101-with-obs-recording-tips/"><u>[Updated] In 2024, PS4 Live Broadcasting 101 with OBS Recording Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-for-online-printer-on-windows/"><u>Quick Steps for Online Printer on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-productivity-best-apps-to-turn-your-pcs-clock-into-an-animated-screensaver/"><u>Streamline Productivity: Best Apps to Turn Your PC’s Clock Into an Animated Screensaver</u></a></li>
<li><a href="https://windows11.techidaily.com/initiate-your-narrative-with-a-click-on-windows-11/"><u>Initiate Your Narrative with a Click on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/syncing-speakers-with-slides-a-handbook-on-music-integration-for-2024/"><u>Syncing Speakers with Slides  A Handbook on Music Integration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-art-of-win10-blue-screen-recovery/"><u>Mastering the Art of Win10 Blue Screen Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-activation-error-0x803f700f-fix-guide/"><u>Overcoming Windows Activation Error: 0X803F700F Fix Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-ultimate-10-filter-combos-making-tiktoks-pop-up-for-2024/"><u>[Updated] Ultimate 10 Filter Combos Making TikToks Pop Up for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-infinity-sphere-shooting-accessories/"><u>[New] Infinity Sphere Shooting Accessories</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-elevating-your-ppt-experience-tips-for-gmeet-users-laptopstablets/"><u>[Updated] Elevating Your PPT Experience  Tips for GMeet Users, Laptops/Tablets</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-samsung-galaxy-a14-5g-frp-bypass-by-drfone-android/"><u>About Samsung Galaxy A14 5G FRP Bypass</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-guide-to-podcast-introduction-skills/"><u>In 2024, The Ultimate Guide to Podcast Introduction Skills</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reversion-of-graphics-settings-for-optimal-viewing/"><u>Quick Reversion of Graphics Settings for Optimal Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-auto-detection-of-windows-proxy/"><u>Troubleshooting Failed Auto-Detection of Windows Proxy</u></a></li>
</ul></div>
