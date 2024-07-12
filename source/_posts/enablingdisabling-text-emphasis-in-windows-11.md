---
title: Enabling/Disabling Text Emphasis in Windows 11
date: 2024-07-11T21:35:00.181Z
updated: 2024-07-12T21:35:00.181Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling Text Emphasis in Windows 11
excerpt: This Article Describes Enabling/Disabling Text Emphasis in Windows 11
keywords: Emphasize Text Windows 11,Disable Text Stressing,Enable Highlight Window,Turn Off Bold Text Win,Activate Italics Windows,Deactivate Font Stress,Change Text Emphasis Win11
thumbnail: https://thmb.techidaily.com/5996397f505d52b0f60ffe77c36fd8859621590a57dd0707f44eeaa06c560dbc.jpg
---

## Enabling/Disabling Text Emphasis in Windows 11

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
<li><a href="https://windows11.techidaily.com/essential-steps-for-activating-windows-11s-system-restore-feature/"><u>Essential Steps for Activating Windows 11'S System Restore Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-non-detected-network-proxy-settings-in-windows/"><u>Overcoming Non-Detected Network Proxy Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-file-system-woes-on-windows-11/"><u>Navigating File System Woes on Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-vivo-y27s-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Vivo Y27s FRP Bypass Instantly</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-removing-onedrive-linkage-on-windows-os/"><u>Steps for Removing OneDrive Linkage on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/unfreezing-windows-updates-top-6-strategies-to-resolve-sticking-issues/"><u>Unfreezing Windows Updates: Top 6 Strategies to Resolve Sticking Issues</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-essential-web-pages-free-whoosh-sound-packs/"><u>New Essential Web Pages Free Whoosh Sound Packs</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-correction-techniques/"><u>Mastering Windows Error Correction Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/time-travel-tech-windows-7-product-key-for-11-activation/"><u>Time-Travel Tech: Windows 7 Product Key for 11 Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-photo-capture-file-creation-failed-camera-app-error-on-windows-11-and-11/"><u>How to Fix the “Photo Capture File Creation Failed” Camera App Error on Windows 11 & 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-premium-performance-in-a-package-that-pleases-your-pocket/"><u>[Updated] 2024 Approved  Premium Performance in a Package That Pleases Your Pocket</u></a></li>
<li><a href="https://windows11.techidaily.com/master-the-art-of-troubleshooting-windows-camera/"><u>Master the Art of Troubleshooting Windows Camera</u></a></li>
<li><a href="https://windows11.techidaily.com/simplify-software-management-with-new-context-menu-addition/"><u>Simplify Software Management with New Context Menu Addition</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-desktop-spaces-preset-program-dimensions-on-win11/"><u>Optimizing Desktop Spaces: Preset Program Dimensions on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-secure-questions-a-guide-to-altering-local-account-in-win-11/"><u>Erase Secure Questions: A Guide to Altering Local Account in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-battlenet-access-issues-in-windows-1011/"><u>Overcoming Battle.net Access Issues in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/boost-connectivity-discover-the-best-5-chrome-tools-for-facebook-videos/"><u>Boost Connectivity  Discover the Best 5 Chrome Tools for Facebook Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-instructions-for-software-icons-on-desktop-menu/"><u>Tailored Instructions for Software Icons on Desktop Menu</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/comedic-choreography-producing-funny-mock-films-for-2024/"><u>Comedic Choreography  Producing Funny Mock Films for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-directx-setup-failures-on-pc/"><u>Mending DirectX Setup Failures on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/snap-opera-download-into-action-windows-style/"><u>Snap Opera Download Into Action, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-student-laptop-asus-s15-oled-in-focus/"><u>The Ultimate Student Laptop: ASUS S15 OLED in Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-connection-stability-fixed-windows-lol-issues/"><u>Mastering Connection Stability: Fixed Windows LoL Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-a-disconnected-printer-issue/"><u>Navigating a Disconnected Printer Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionize-how-you-use-the-mouse-worldwide-through-powertoys/"><u>Revolutionize How You Use the Mouse Worldwide Through PowerToys</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-non-responsive-slack-alerts-a-quick-win-for-windows-users/"><u>Fix Non-Responsive Slack Alerts: A Quick Win for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/phase-out-announcement-end-for-windows-781-on-microsoft-platforms/"><u>Phase-Out Announcement: End for Windows 7/8.1 on Microsoft Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unseen-wi-fi-in-windows/"><u>The Art of Unseen Wi-Fi in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-fbm-issues-on-your-pc-screen/"><u>Unblocking FBM Issues on Your PC Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-permission-problems-during-windows-1011-installer-errors/"><u>Remedying Permission Problems During Windows 10/11 Installer Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-windows-pc-boosters-for-speed-and-efficiency/"><u>Top 5 Windows PC Boosters for Speed and Efficiency</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-most-popular-websites-offering-montage-audio-archives-for-2024/"><u>New Most Popular Websites Offering Montage Audio Archives for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-lava-storm-5g-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Lava Storm 5G</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-on-iphone-7-plus-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out On iPhone 7 Plus How to Bypass?</u></a></li>
<li><a href="https://windows11.techidaily.com/slowing-down-windows-10-shutdown-keep-programs-open/"><u>Slowing Down Windows 10 Shutdown: Keep Programs Open</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-skype-call-capture-the-most-effective-free-and-paid-approaches/"><u>In 2024, Skype Call Capture  The Most Effective Free & Paid Approaches</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-overcome-windows-software-initiation-failures/"><u>How to Overcome Windows Software Initiation Failures</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-subtitle-edit-not-meeting-your-needs-here-are-some-powerful-mac-alternatives/"><u>2024 Approved Subtitle Edit Not Meeting Your Needs? Here Are Some Powerful Mac Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win-network-unreachable-issue/"><u>Overcoming WIN Network Unreachable Issue</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-examination-of-samsung-photo-editor-features/"><u>2024 Approved  The Ultimate Examination of Samsung Photo Editor Features</u></a></li>
<li><a href="https://windows11.techidaily.com/rehabbing-windows-1011s-recycle-bin-crisis-a-step-by-step-guide/"><u>Rehabbing Windows 10/11'S Recycle Bin Crisis: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/paramount-top-rated-vr-movies/"><u>Paramount Top-Rated VR Movies</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-from-fragments-to-features-a-guide-to-tiktok-video-construction/"><u>[New] In 2024, From Fragments to Features  A Guide to TikTok Video Construction</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-full-gpu-potential-in-windows-10-and-11-via-vram/"><u>Unleashing Full GPU Potential in Windows 10 & 11 via VRAM</u></a></li>
<li><a href="https://windows11.techidaily.com/the-9-best-features-in-the-windows-11-february-2023-update/"><u>The 9 Best Features in the Windows 11 February 2023 Update</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-auto-shutdown-on-windows-11-for-idleness/"><u>Mastering Auto-Shutdown on Windows 11 for Idleness</u></a></li>
<li><a href="https://windows11.techidaily.com/three-steps-for-ditching-microsofts-store/"><u>Three Steps for Ditching Microsoft's Store</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-the-hover-over-sensitivity-and-visibility-in-windows-11/"><u>Tailoring the Hover Over Sensitivity and Visibility in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-fixing-non-responsive-usb-on-pc/"><u>Identifying and Fixing Non-Responsive USB on PC</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-from-ordinary-to-extraordinary-your-pathway-with-tiktok-templates/"><u>[New] From Ordinary to Extraordinary  Your Pathway with TikTok Templates</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/edit-like-a-pro-top-hd-video-editing-software/"><u>Edit Like a Pro Top HD Video Editing Software</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-steam-content-restricted-on-pc-a-step-by-step-guide/"><u>Solving Steam Content Restricted on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-samsung-galaxy-s24-by-drfone-android/"><u>In 2024, How to Bypass FRP on Samsung Galaxy S24?</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-4-ways-to-stop-pc-update-notifications/"><u>Quick Fixes: 4 Ways to Stop PC Update Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-labyrinth-of-updater-0x800f080a-on-windows/"><u>Navigating Through the Labyrinth of Updater 0X800F080A on Windows</u></a></li>
</ul></div>
