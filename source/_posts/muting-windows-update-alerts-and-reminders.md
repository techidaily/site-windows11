---
title: Muting Windows Update Alerts and Reminders
date: 2024-08-31T22:18:20.796Z
updated: 2024-09-01T22:18:20.796Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Muting Windows Update Alerts and Reminders
excerpt: This Article Describes Muting Windows Update Alerts and Reminders
keywords: Mute Updates Notify,Stop Update Alarms,Halt Windows Ads,Silence System Alerts,Quiet OS Updates,Turn Off Update Reminder,Block Update Prompts
thumbnail: https://thmb.techidaily.com/ad5375273ed5273cf93923e35b6ab94c30b89301141494859d6be3ab7df15629.jpg
---

## Muting Windows Update Alerts and Reminders

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-mastery-techniques-for-embedding-social-media-live-videos/"><u>[New] 2024 Approved  Mastery Techniques for Embedding Social Media Live Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-achieving-professional-editing-without-the-price-tag/"><u>[New] Achieving Professional Editing Without the Price Tag</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-beginning-with-tweets-your-new-twitter-journey-for-2024/"><u>[New] Beginning with Tweets  Your New Twitter Journey for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-convenient-techniques-for-saving-youtube-videos-for-2024/"><u>[New] Convenient Techniques for Saving YouTube Videos for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-saving-pictures-from-videos-in-windows-10-photos/"><u>[New] Saving Pictures From Videos in Windows 10 Photos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-secrets-unveiled-saving-twitter-gifs-for-later-use/"><u>[New] Secrets Unveiled  Saving Twitter GIFs for Later Use</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-innovative-cameras-for-circular-coverage/"><u>[Updated] In 2024, Innovative Cameras for Circular Coverage</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-most-compelling-5-ios-podcast-solutions/"><u>[Updated] In 2024, Most Compelling 5 iOS Podcast Solutions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-macos-11-big-sur-compatibility-guide/"><u>[Updated] MacOS 11 Big Sur Compatibility Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-swiveling-screens-mastering-video-rotation-on-instagram/"><u>2024 Approved  Swiveling Screens  Mastering Video Rotation on Instagram</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162743652-bring-your-childhood-back-ios-and-psp-games/"><u>Bring Your Childhood Back: IOS & PSP Games!</u></a></li>
<li><a href="https://win-able.techidaily.com/destiny-2-troubleshooting-resolving-the-centipede-error/"><u>Destiny 2 Troubleshooting: Resolving the Centipede Error</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-connect-advanced-drives-mapping-on-windows-11/"><u>Explore & Connect: Advanced Drives Mapping on Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y27-4g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y27 4G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-troubleshoot-apex-legends-crashing-on-windows-11/"><u>How to Troubleshoot Apex Legends Crashing on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-inside-windows-10-a-snapshot-of-its-transformation/"><u>In 2024, Inside Windows 10  A Snapshot of Its Transformation</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-analysis-of-samsungs-newest-galaxy-s24-ultra-tech-marvel/"><u>In-Depth Analysis of Samsung's Newest Galaxy S24 Ultra Tech Marvel</u></a></li>
<li><a href="https://windows11.techidaily.com/insight-into-windows-maintenance-framework/"><u>Insight Into Windows Maintenance Framework</u></a></li>
<li><a href="https://windows11.techidaily.com/installation-woes-practical-solutions-for-optional-features-on-windows-11-and-11-pro/"><u>Installation Woes: Practical Solutions for Optional Features on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/live-conversion-of-speech-to-text-using-whisper/"><u>Live Conversion of Speech to Text Using Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/methodology-to-fix-inactive-thumbnails/"><u>Methodology to Fix Inactive Thumbnails</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-windows-11-hidden-folders-reveal/"><u>Optimizing Windows 11: Hidden Folders Reveal</u></a></li>
<li><a href="https://vp-tips.techidaily.com/pioneering-50gbps-high-speed-internet-nokia-and-googles-cutting-edge-testing-initiative/"><u>Pioneering 50Gbps High-Speed Internet: Nokia and Google's Cutting-Edge Testing Initiative</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-methods-to-uncover-system-vulnerabilities/"><u>Proactive Methods to Uncover System Vulnerabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-active-windows-11-taskbar/"><u>Reinstating Active Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/safe-navigation-in-windows-11-the-top-8-to-steer-clear-of/"><u>Safe Navigation in Windows 11: The Top 8 To Steer Clear Of</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-frustrations-with-failed-discord-install-on-windows/"><u>Swiftly Overcoming Frustrations with Failed Discord Install on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-for-clearing-and-refreshing-icons/"><u>The Ultimate Guide for Clearing and Refreshing Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-using-dism-on-windows-11/"><u>The Ultimate Guide to Using DISM on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-rescue-your-zip-extraction-mishaps-on-windows-11/"><u>Tips to Rescue Your ZIP Extraction Mishaps on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-and-correcting-utorrent-installation-errors-in-winos/"><u>Troubleshooting and Correcting uTorrent Installation Errors in WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-adjust-win11-connection-preferences/"><u>Tutorial: Adjust Win11 Connection Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11s-latest-driver-compatibility/"><u>Unlocking Windows 11'S Latest Driver Compatibility</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-hidden-windows-startup-items/"><u>Unveiling Hidden Windows Startup Items</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-display-reclaiming-optimal-performance/"><u>Windows 11 Display: Reclaiming Optimal Performance</u></a></li>
</ul></div>
