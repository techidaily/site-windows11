---
title: Stop Windows From Notifying You of Updates
date: 2024-08-15T16:08:47.621Z
updated: 2024-08-16T16:08:47.621Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Windows From Notifying You of Updates
excerpt: This Article Describes Stop Windows From Notifying You of Updates
keywords: Unblock Update Alerts,Stop Windows Update Prompts,Avoid Windows Update Notifications,Disable Windows Update Interruptions,Prevent Windows Update Toggles,Turn Off Windows Update Alerts,Halt Windows Notification Updates
thumbnail: https://thmb.techidaily.com/7771a2b06b1c9409671f87688822caf9758687ec74141e34200890076f60dc1f.jpg
---

## Stop Windows From Notifying You of Updates

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in [how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on [how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on [how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

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
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-hints.techidaily.com/new-best-script-innovation-place/"><u>[New] Best Script Innovation Place</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-breakthroughs-in-non-fbx-gameplay-documentation/"><u>[New] Breakthroughs in Non-FBX Gameplay Documentation</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-cross-promotion-savvy-integrating-youtube-with-fb/"><u>[New] Cross-Promotion Savvy  Integrating YouTube with FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-no-cost-windowsmac-solutions-for-movie-lovers/"><u>[New] No-Cost Windows/Mac Solutions for Movie Lovers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-captivating-call-to-action-designing-a-dynamic-subscribe-buttons-with-filmora/"><u>[Updated] 2024 Approved  Captivating Call-to-Action  Designing a Dynamic Subscribe Buttons with Filmora</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-quick-insights-into-simplified-ipad-and-iphone-recording/"><u>[Updated] Quick Insights Into Simplified iPad & iPhone Recording</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-step-by-step-guide-to-revamping-youtube-inspired-thumbnails-on-twitter/"><u>2024 Approved  Step-by-Step Guide to Revamping YouTube-Inspired Thumbnails on Twitter</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/creative-collection-of-swaying-text-styles-for-2024/"><u>Creative Collection of Swaying Text Styles for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/double-clicking-away-how-to-instantly-load-apk-files-on-windows-11/"><u>Double-Clicking Away: How to Instantly Load APK Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-java-installation-errors-on-pc/"><u>Guide to Overcoming Java Installation Errors on PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-effortlessly-obtain-and-implement-your-usb-camera-drivers-now/"><u>How to Effortlessly Obtain & Implement Your USB Camera Drivers Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-maintain-notebook-visibility-on-win-1011/"><u>How to Maintain Notebook Visibility on Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-return-to-original-windows-setup-settings/"><u>How to Return to Original Windows Setup Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/improving-system-performance-by-curbing-browser-activity/"><u>Improving System Performance by Curbing Browser Activity</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-bringing-your-sony-camcorder-videos-to-life-advanced-editing-techniques/"><u>In 2024, Bringing Your Sony Camcorder Videos to Life Advanced Editing Techniques</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-poco-m6-5g-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Poco M6 5G Face Lock?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-15-pro-max-keeps-asking-for-outlook-password-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone 15 Pro Max Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://windows11.techidaily.com/launch-successfully-guiding-through-startup-services-in-windows-11/"><u>Launch Successfully: Guiding Through Startup Services in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/lol-library-top-picks-for-outstanding-meme-creators-for-2024/"><u>LOL Library  Top Picks for Outstanding Meme Creators for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/maintain-full-size-icons-on-your-windows-11-machine/"><u>Maintain Full-Size Icons on Your Windows 11 Machine</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wake-on-lid-closure-in-windows-devices/"><u>Mastering Wake on Lid Closure in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mythos-makers-circle-top-ten-tales-for-2024/"><u>Mythos Makers Circle – Top Ten Tales for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-hurdle-of-windows-11-stalled-updates-expert-solutions/"><u>Overcoming the Hurdle of Windows 11 Stalled Updates: Expert Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-speakers-unresponsiveness/"><u>Overcoming Windows Speakers Unresponsiveness</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-disabling-audio-playback-errors/"><u>Quick Fix for Disabling Audio Playback Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-update-breakdown-overcoming-error-0x80246007-on-win11/"><u>Resolving Update Breakdown: Overcoming Error 0X80246007 on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-wi-fi-blocking-networks-on-windows-pc/"><u>Secure Your Wi-Fi: Blocking Networks on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-restore-active-window-defense-system/"><u>Strategies to Restore Active Window Defense System</u></a></li>
<li><a href="https://windows11.techidaily.com/success-tips-reviving-your-intel-unison-app/"><u>Success Tips: Reviving Your Intel Unison App</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-reinstate-lost-mcuicnt-file-in-windows/"><u>Techniques to Reinstate Lost McUICnt File in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-switching-offon-windows-11s-smartscreen/"><u>Tips for Switching Off/On Windows 11'S SmartScreen</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-blackwhite-windows-store-errors/"><u>Troubleshooting Black/White Windows Store Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/turbo-type-tips-quick-key-input-enhancements-for-win-1011/"><u>Turbo-Type Tips: Quick Key Input Enhancements for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-5ghz-wi-fi-connection-woes-how-to-solve-them/"><u>Win11 5GHz Wi-Fi Connection Woes: How to Solve Them</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-widgets-configuration-the-triad-approach/"><u>Windows 11 Widgets Configuration: The Triad Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-photos-clever-trick-for-image-renewal/"><u>Windows Photos' Clever Trick for Image Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woos-resolve-opera-download-hitch/"><u>Windows Woos: Resolve Opera Download Hitch</u></a></li>
<li><a href="https://windows11.techidaily.com/winfix-guide-reviving-dormant-wsreset-service-process/"><u>Winfix Guide: Reviving Dormant WSReset Service Process</u></a></li>
</ul></div>
