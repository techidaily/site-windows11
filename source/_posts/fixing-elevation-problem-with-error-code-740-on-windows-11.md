---
title: Fixing Elevation Problem with Error Code 740 on Windows 11
date: 2024-08-15T15:54:50.339Z
updated: 2024-08-16T15:54:50.339Z
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Set Programs to Run in Compatibility Mode

 It’s also recommended to set older programs to run in compatibility mode. Doing so might address a compatibility issue causing error 740\. You can set an affected program to run in compatibility mode like this:

1. Open the affected software’s installation within File Explorer.
2. Right-click an affected program’s EXE (application file) and select **Properties** \> **Compatibility**.
3. Select **Run this program in compatibility mode for** and choose Windows 8 or an older platform on the drop-down menu. It’s best to select the Windows platform for which the publisher originally released the software.  
![The Run this program in compatibility mode drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/run-this-program-in-compatibility-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
4. Press the **Apply** \> **OK** buttons to set the compatibility mode setting.

## 3\. Turn Off the User Account Control Feature

 User Account Control is the security feature that throws up notifications when programs try to make changes. UAC could be a potential cause of error 740 when it’s set very high. So, try turning off UAC before running affected apps. Our [guide to disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) tells you how to turn off that feature.

![The User Account Control Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/user-account-control-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
7. Click **Apply** on the Advanced Security Settings window.
8. Select **Yes** when asked to continue.
9. Exit the folder’s properties window and restart your PC.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
4. Select **Apply** to turn off Admin Approval Mode.
5. To close the policy window, select the **OK** option.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 7\. Disable Third-Party Antivirus Software Packages

 Have you installed a third-party antivirus or security app on your PC? If you have, your third-party security software could be causing error 740 by blocking the EXE file you’re trying to run. This can happen when the antivirus software flags the application file as malicious.

 The potential solution, in this case, is to temporarily disable third-party antivirus software before trying to run affected programs. Look for and select an option that turns off the antivirus shield by right-clicking on the antivirus software’s system tray icon. If there are time options available, select to turn the real-time protection off for about an hour or so.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 If disabling the security software works, you don’t necessarily have to turn the security software off whenever you want to run the application file. Your antivirus software will probably include an exclusion list to which you can add trustworthy program file exceptions. Add the affected EXE file there to exclude it from the antivirus protection.

## 8\. Migrate to a New Admin User Account

 If the “requested operation requires elevation” error persists after trying other resolutions, your user account might be corrupted. Then you might need to create and utilize a new admin account to resolve this issue. You can migrate to that account by copying files from your old user account into the new one.

![The Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/add-account-option.jpg)

 To apply this troubleshooting method for the “requested operation requires elevation” error, follow the instructions within this article about [how to fix Windows issues by creating new user accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/). First, you’ll need to set up and sign in to the new admin account to see if the error occurs there. If not, transfer user files into the new account as covered there.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-elevate-images-with-simple-color-tweaks/"><u>[New] 2024 Approved  Elevate Images with Simple Color Tweaks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-aesthetic-enigma-the-ultimate-backdrop-collection-for-video-thumbnails/"><u>[New] In 2024, Aesthetic Enigma  The Ultimate Backdrop Collection for Video Thumbnails</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-the-ultimate-guide-to-combining-zoom-and-fb-live/"><u>[New] In 2024, The Ultimate Guide to Combining ZOOM & FB Live</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-triumph-over-triviality-amass-a-million-ish-followers-on-ig/"><u>[New] In 2024, Triumph Over Triviality  Amass a Million-Ish Followers on IG</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-10-webcam-covers-that-keep-you-safe-online-for-2024/"><u>[Updated] 10 Webcam Covers That Keep You Safe Online for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2023-complete-guide-twitter-reaction-videos/"><u>[Updated] 2023 Complete Guide | Twitter Reaction Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-snap-edit-and-assemble-a-rapid-google-collage-how-to/"><u>2024 Approved  Snap, Edit & Assemble  A Rapid Google Collage How-To</u></a></li>
<li><a href="https://extra-hints.techidaily.com/digital-horizons-meta-to-omni-contrast/"><u>Digital Horizons  Meta to Omni Contrast</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/discovering-the-best-10-online-tools-for-vimeo-videos/"><u>Discovering the Best  10 Online Tools for Vimeo Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/exiting-others-user-sessions-on-win-11/"><u>Exiting Others' User Sessions on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-your-digital-footprints-in-windows-11/"><u>Exploring Your Digital Footprints in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-xbox-game-pass-0x800700e9-error-in-windows-11-os/"><u>Fixing Xbox Game Pass 0X800700E9 Error in Windows 11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-reversing-customized-search-in-windows-11/"><u>Guide to Reversing Customized Search in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/harmony-and-hype-perfecting-film-teaser-tunes/"><u>Harmony and Hype  Perfecting Film Teaser Tunes</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-from-iphone-11-pro-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working From iPhone 11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-visual-studio-code-crashing-on-windows-11/"><u>How to Fix Visual Studio Code Crashing on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-y02t-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo Y02T to PC? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-stop-the-license-will-expire-warning-in-win11/"><u>How to Stop the License Will Expire Warning in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-use-slideshow-and-spot-fix-in-the-windows-11-photos-app/"><u>How to Use Slideshow and Spot Fix in the Windows 11 Photos App</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-on-iphone-14-plus-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working On iPhone 14 Plus</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Oppo Reno 11 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-and-economical-selecting-the-top-free-webm-playback-options/"><u>In 2024, Optimal and Economical  Selecting the Top Free WebM Playback Options</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-notify-shutdown-in-windows-11/"><u>Instant Notify Shutdown in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-iphone-14-pro-max-5-ways-to-get-into-a-locked-iphone-14-pro-max-by-drfone-ios/"><u>Locked Out of iPhone 14 Pro Max? 5 Ways to get into a Locked iPhone 14 Pro Max</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-fixes-for-hardware-detection-faults/"><u>Mastering Fixes for Hardware Detection Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-resolving-process-termination-failure-on-pcs/"><u>Methods for Resolving 'Process Termination Failure' On PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-retrieve-unseen-razer-devices-on-windows-11/"><u>Methods to Retrieve Unseen Razer Devices on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-your-workspace-on-pc-themes-from-the-microsoft-store/"><u>Personalizing Your Workspace on PC: Themes From the Microsoft Store</u></a></li>
<li><a href="https://windows11.techidaily.com/priority-accessibility-attach-google-mail-taskbar-ready/"><u>Priority Accessibility: Attach Google Mail Taskbar-Ready</u></a></li>
<li><a href="https://windows11.techidaily.com/propel-workflow-speed-with-windows-smart-launcher/"><u>Propel Workflow Speed with Windows' Smart Launcher</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-steps-to-resolve-steams-internet-connectivity/"><u>Quick Steps to Resolve Steam's Internet Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/reflect-on-one-misconception-about-cultural-relativism-mentioned-in-class-then-describe-how-you-would-address-this-misunderstanding-with-someone-from-a-diff21/"><u>Reflect on One Misconception About Cultural Relativism Mentioned in Class, Then Describe How You Would Address This Misunderstanding with Someone From a Different Culture</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-the-system-how-to-reinitialize-windows-11-programs/"><u>Resetting the System: How to Reinitialize Windows 11 Programs</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-unresizable-gif-error-tips-for-discord-on-windows-11/"><u>Resolving Unresizable GIF Error: Tips for Discord on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-expanding-windows-volume-no-deletion-compatible/"><u>Securely Expanding Windows Volume, No Deletion Compatible</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/seizing-screen-time-with-hd-downloads-from-fb-sources/"><u>Seizing Screen Time with HD Downloads From FB Sources</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-to-reduce-cpu-consumption-fixing-dropbox-on-windows/"><u>Solutions to Reduce CPU Consumption: Fixing Dropbox on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/speeding-up-android-studio-tasks-on-windows-os/"><u>Speeding Up Android Studio Tasks on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-windows-media-player-launch/"><u>Step-by-Step Guide to Windows Media Player Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-methodology-for-full-uninstallation-of-wsl/"><u>Step-by-Step Methodology for Full Uninstallation of WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/system-snooze-button-unlocking-windows-top-8-resets/"><u>System Snooze Button: Unlocking Windows' Top 8 Resets</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-pin-verification-hurdles-for-windows-1011-systems/"><u>Tackling PIN Verification Hurdles for Windows 10/11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/the-edge-dilemma-ethical-choices-amidst-societal-controls/"><u>The Edge Dilemma: Ethical Choices Amidst Societal Controls</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-photo-arrangers-for-a-clutter-free-pc-desktop/"><u>Top 7 Photo Arrangers for a Clutter-Free PC Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-interface-not-recognized-a-win-to-success-guide/"><u>Troubleshoot 'Interface Not Recognized': A Win to Success Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-missing-camera-in-device-manager/"><u>Troubleshoot Missing Camera In Device Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-winservicesexe-on-your-pc/"><u>Troubleshooting Winservices.exe on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-internet-security-features-for-win-1011/"><u>Tweaking Internet Security Features for Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-blocked-functionality-of-ccleaner-on-win11/"><u>Unblocking Blocked Functionality of CCleaner on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-peak-performance-why-choose-windows-for-gaming/"><u>Unleashing Peak Performance: Why Choose Windows for Gaming</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-potential-extending-your-pin-on-windows-11/"><u>Unlocking the Potential: Extending Your PIN on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-windows-odbc-command-center/"><u>Unveiling the Windows ODBC Command Center</u></a></li>
<li><a href="https://windows11.techidaily.com/win10win11-diagnostics-tackling-0x0000004e-faults/"><u>Win10/Win11 Diagnostics: Tackling 0X0000004E Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-speedy-epic-games-installations/"><u>Winning at Speedy Epic Games Installations</u></a></li>
</ul></div>
