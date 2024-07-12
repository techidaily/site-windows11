---
title: Fixing Elevation Problem with Error Code 740 on Windows 11
date: 2024-07-11T21:37:03.531Z
updated: 2024-07-12T21:37:03.531Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Elevation Problem with Error Code 740 on Windows 11
excerpt: This Article Describes Fixing Elevation Problem with Error Code 740 on Windows 11
keywords: Elevation Issue Fix,Windows 11 Error 740,WinErrorCodeResolution,UpdateWindowsFix740,SolveWinElevationError,Error740WindowsTroubleshoot,CorrectingElevationError740
thumbnail: https://thmb.techidaily.com/857cad2a82232e03f92aad9809b4a548e4964a8c9aa59aabf55be668d5e1078d.jpg
---

## Fixing Elevation Problem with Error Code 740 on Windows 11

 Some users have reported in support forum posts that error 740 occurs when they try to run programs or access folders on Windows PCs. The error 740 message says, “The requested operation requires elevation.” Users can’t access software, folders, or files for which error 740 occurs.

 This is how you can fix error 740 within Windows 10 and 11\.

## 1\. Run the Affected Programs With Admin Rights

 The error 740 message mentions the need for operation elevation. That’s a hint to try running affected programs with elevated (administrator) rights. Check out this guide on [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set affected EXE files to run with elevated rights.

![The Run this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-as-an-administrator.jpg)

## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

## 4\. Adjust Folder Permission Settings

 This potential resolution is recommended for users who can’t access specific folders because of error 740\. In that scenario, this error can be a folder permissions issue that selecting the **Replace all child object permission entries** option could feasibly address.

 Try selecting the **Replace all child object permission** setting for an affected folder as follows:

1. Press **Win + E** to bring up File Explorer.
2. Open whatever directory contains the folder for which error 740 occurs.
3. Right-click the affected folder and select that directory’s **Properties** option.
4. Select **Security** on the window’s tab bar.
5. Click **Advanced** to access more security settings.  
![The Security tab and Advanced button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-security-tab3.jpg)
6. Select the **Replace all child object permissions entries with inheritable permission entries from this object** checkbox.  
![The Replace all child object permission entries checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/replace-all-child-objects-option.jpg)
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

## 5\. Modify the Behavior of the UAC Elevation Prompt

 If your Windows PC has the Group Policy Editor, try changing the behavior of UAC’s elevation prompt with that tool. Selecting the **Elevate without prompting** setting for the User Account Control: Behavior policy could fix error 740 for some users.

 You can select that option within Windows Enterprise and Pro editions like this:

1. Open the Local Group Policy Editor. If you need help, check out the [ways to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
2. Next, double-click **Computer Configuration** to expand that sidebar navigation option.
3. Double-click **Windows Settings** and select **Security S** **ettings**.
4. Then go to **Local Policies** and **Security Options** to access User Account Control Policy settings.  
![Security Options within Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/security-options.jpg)
5. Double-click the **User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode** policy.
6. Select the **Elevate without prompting** option on the drop-down menu.  
![The Elevate without prompting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/elevate-without-prompting.jpg)
7. Click **Apply** to set the **Elevate without prompting policy**.
8. Select **OK** to close the policy setting’s window.
9. Then reboot Windows after closing Group Policy Editor.

## 6\. Disable Admin Approval Mode

 Admin Approval Mode prompts administrative users for task permissions when enabled. It’s a strict Group Policy Editor security policy that can potentially cause elevation issues. Follow these steps to turn off Admin Approval Mode.

1. Go to **Security Options** in Group Policy Editor as outlined for steps one to four of resolution five.
2. Double-click the **User Account Control: Admin Approval Mode for the Built-in Administrator account** policy setting.  
![The Admin Approval Mode policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/admin-approval-mode-policy.jpg)
3. Click the **Disabled** radio button if this policy is enabled.  
![the-enabled-radio-button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-enabled-radio-button.jpg)
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

## Get Error 740 Sorted on Windows

 The “requested operation requires elevation” error is an inconvenient admin access privilege issue many users have needed to fix. Users have resolved that issue by applying the potential resolutions in this guide. So, try applying those fixes for the “requested operation requires elevation” error in the order specified to find one that works on your Windows 10 or 11 PC.

 This is how you can fix error 740 within Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-swapping-out-your-daily-youtube-fix/"><u>2024 Approved  The Ultimate Guide to Swapping Out Your Daily YouTube Fix</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-11-identity-new-username-guide/"><u>Altering Windows 11 Identity: New UserName Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-add-folder-now-obstacle-in-windows-onedrive-for-a-smooth-experience/"><u>Bypassing the 'Add Folder Now' Obstacle in Windows OneDrive for a Smooth Experience</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-advanced-hue-adjustment-strategies-for-professionals/"><u>[New] Advanced Hue Adjustment Strategies for Professionals</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-from-audience-to-advocate-strategies-for-powerful-fb-covers-for-2024/"><u>[Updated] From Audience to Advocate  Strategies for Powerful FB Covers for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-xiaomi-11-series-a-visual-journey-through-precision-recording/"><u>[Updated] In 2024, Xiaomi 11 Series  A Visual Journey Through Precision Recording</u></a></li>
<li><a href="https://windows11.techidaily.com/add-compatibility-tool-to-windows-quick-access/"><u>Add Compatibility Tool to Windows' Quick Access</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-increasing-indoor-ambiance-via-sunlight/"><u>In 2024, The Art of Increasing Indoor Ambiance via Sunlight</u></a></li>
<li><a href="https://windows11.techidaily.com/a-closer-look-at-windows-11s-backup-processing-methods/"><u>A Closer Look at Windows 11'S Backup Processing Methods</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-effortless-text-labeling-on-video-in-windows-photos/"><u>[Updated] Effortless Text Labeling on Video in Windows Photos</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-say-goodbye-to-upside-down-videos-16-free-avi-rotators-for-you/"><u>New Say Goodbye to Upside-Down Videos 16 Free AVI Rotators for You</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-capturing-online-seminars/"><u>2024 Approved  Capturing Online Seminars</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-qt-plugin-initialization-failure-error/"><u>Addressing Qt Plugin Initialization Failure Error</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-discover-your-new-favorites-with-our-best-offline-ios-games-list/"><u>[Updated] In 2024, Discover Your New Favorites with Our Best Offline iOS Games List</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-with-top-practices-for-wsl-2-usage-on-pcs/"><u>Boost Efficiency with Top Practices for WSL 2 Usage on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/"><u>Balancing CPU & Memory Use After News Downloads</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-ultimate-guide-to-selecting-a-reliable-youtube-to-mp3-converter/"><u>The Ultimate Guide to Selecting a Reliable YouTube to MP3 Converter</u></a></li>
<li><a href="https://windows11.techidaily.com/9-ways-to-fix-mails-notifications-not-working-on-windows/"><u>9 Ways to Fix Mail's Notifications Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/alternative-pathway-for-opening-file-explorer-through-onedrive/"><u>Alternative Pathway for Opening File Explorer Through OneDrive</u></a></li>
<li><a href="https://windows11.techidaily.com/a-list-of-frustrations-with-windows-11/"><u>A List of Frustrations with Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-elevating-your-content-powerful-tags-to-watch-out-for/"><u>[Updated] 2024 Approved  Elevating Your Content  Powerful Tags to Watch Out For</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-unlocking-the-power-of-viral-marketing-with-tiktok-ads-examples-for-2024/"><u>[New] Unlocking the Power of Viral Marketing with TikTok Ads Examples for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-blockade-fixing-obs-studios-server-error-window/"><u>Bypassing the Blockade: Fixing OBS Studio's Server Error Window</u></a></li>
<li><a href="https://extra-support.techidaily.com/sequence-length-in-seconds-of-20mb-media-for-2024/"><u>Sequence Length in Seconds of 20MB Media for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-storage-solutions-ps5s-top-10-external-units/"><u>[New] Storage Solutions  PS5's Top 10 External Units</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-ultimate-list-of-video-combining-tools-10-easy-video-joiner-alternatives/"><u>Updated The Ultimate List of Video Combining Tools 10 Easy Video Joiner Alternatives</u></a></li>
<li><a href="https://windows11.techidaily.com/bold-windows-11-remove-curved-edges/"><u>Bold Windows 11: Remove Curved Edges</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-windows-11s-task-manager-launch-interface/"><u>Adjusting Windows 11'S Task Manager Launch Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/4-ways-microsoft-is-replacing-cortana-in-windows/"><u>4 Ways Microsoft Is Replacing Cortana in Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-earnings-report-pewdiepies-income-summary/"><u>2024 Approved  Earnings Report  PewDiePie's Income Summary</u></a></li>
<li><a href="https://windows11.techidaily.com/avoidance-of-windows-updates-interruptions/"><u>Avoidance of Windows Updates Interruptions</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-swift-windows-checkup-guide-explanatory/"><u>[Updated] Swift Windows Checkup Guide Explanatory</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-windows-update-alerts-tooltip-menu-entry/"><u>Adding Windows Update Alerts Tooltip Menu Entry</u></a></li>
<li><a href="https://extra-information.techidaily.com/understanding-livestream-technology-explained/"><u>Understanding Livestream Technology Explained</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-unveiling-virtual-background-magic-a-streamers-guide-to-chroma-key/"><u>In 2024, Unveiling Virtual Background Magic  A Streamer's Guide to Chroma Key</u></a></li>
<li><a href="https://windows11.techidaily.com/assessing-usage-windows-hidden-reliability-vs-performance-tools/"><u>Assessing Usage: Windows' Hidden Reliability Vs. Performance Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/1719314513697-combat-snip-and-sketch-failures-a-guide-to-capturing-entire-display/"><u>Combat Snip & Sketch Failures: A Guide to Capturing Entire Display.</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-efficiency-on-pc-best-apps-for-personalized-time-themed-screen-saver-creation/"><u>Boost Efficiency on PC: Best Apps for Personalized Time-Themed Screen Saver Creation</u></a></li>
<li><a href="https://windows11.techidaily.com/batch-heic-to-jpeg-images-in-windows-environment/"><u>Batch Heic to Jpeg Images in Windows Environment</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-get-hooked-easy-ways-to-loop-any-youtube-video/"><u>[New] 2024 Approved  Get Hooked  Easy Ways to Loop Any YouTube Video</u></a></li>
<li><a href="https://change-location.techidaily.com/all-you-need-to-know-about-mega-greninja-for-vivo-s18-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-beyond-advertisements-a-direct-look-at-recordcast/"><u>[New] Beyond Advertisements  A Direct Look at RecordCast</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-with-top-2023-ms-store-winners/"><u>Boost Windows with Top 2023 MS Store Winners</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-navigating-the-snapchat-ecosystem-for-biz-growth-for-2024/"><u>[Updated] Navigating the Snapchat Ecosystem for Biz Growth for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy XCover 6 Pro Tactical Edition to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-down-roblox-error-262s-solutions/"><u>Breaking Down Roblox Error 262'S Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-productivity-with-windows-11-strategies/"><u>Boosting Productivity with Windows 11 Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-perfect-boot-strategies-to-configure-startup-services-in-win11/"><u>Achieving Perfect Boot: Strategies to Configure Startup Services in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-windows-timer-troubles-reclaim-control/"><u>Beat Windows Timer Troubles, Reclaim Control</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/step-by-step-walkthrough-of-instagram-story-screening/"><u>Step-by-Step Walkthrough of Instagram Story Screening</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-depth-app-insights-the-az-reporters-cut/"><u>[New] In-Depth App Insights - The AZ Reporter's Cut</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-windows-files-date-creation-and-modification-adjustments/"><u>Altering Windows Files: Date Creation & Modification Adjustments</u></a></li>
<li><a href="https://windows11.techidaily.com/broken-bitsafe-vault-postpone-the-transition/"><u>Broken BitSafe Vault: Postpone the Transition</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-incorrect-identifier-message-in-windows-11/"><u>Addressing the 'Incorrect Identifier' Message in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/booting-up-windows-sound-service-quick-fix-steps/"><u>Booting Up Windows Sound Service: Quick Fix Steps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/perfection-in-performance-youtubes-ultimate-video-magicians/"><u>Perfection in Performance  YouTube's Ultimate Video Magicians</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-copyright-free-online-collections-for-games/"><u>[New] Copyright-Free Online Collections for Games</u></a></li>
<li><a href="https://windows11.techidaily.com/classic-expanse-a-win-11-explorer-journey/"><u>Classic Expanse: A Win 11 Explorer Journey</u></a></li>
<li><a href="https://windows11.techidaily.com/3d-paint-speed-expertise-through-shortcuts/"><u>3D Paint Speed Expertise Through Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-disk-errors-with-ease-and-expertise/"><u>Addressing Windows Disk Errors with Ease and Expertise</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-boosting-vimeo-videos-accelerating-playback/"><u>[Updated] Boosting Vimeo Videos  Accelerating Playback</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-get-the-most-out-of-windows-11/"><u>7 Ways to Get the Most Out of Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-decibels-on-windows-integrated-bt-audio/"><u>Boosting Decibels on Windows-Integrated BT Audio</u></a></li>
</ul></div>
