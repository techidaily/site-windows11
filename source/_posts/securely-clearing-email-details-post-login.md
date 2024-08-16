---
title: Securely Clearing Email Details Post-Login
date: 2024-08-15T16:09:49.447Z
updated: 2024-08-16T16:09:49.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Clearing Email Details Post-Login
excerpt: This Article Describes Securely Clearing Email Details Post-Login
keywords: Login Data Wipe,Password Cleared,Secure Logout,Mail Privacy,Email Cleanup,Safe Signoff,Remove Email Info
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## Securely Clearing Email Details Post-Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
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
<li><a href="https://video-capture.techidaily.com/new-in-2024-windows-10-screen-recording-tools-the-ultimate-selection/"><u>[New] In 2024, Windows 10 Screen Recording Tools - The Ultimate Selection</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-key-techniques-boosting-video-reach-across-both-platforms/"><u>[New] Key Techniques  Boosting Video Reach Across Both Platforms</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-spectacular-10-royale-skirmishes-for-2024/"><u>[New] Spectacular 10 Royale Skirmishes for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-avoid-frustration-correct-a-mistaken-tiktok-reset/"><u>[Updated] 2024 Approved  Avoid Frustration – Correct a Mistaken TikTok Reset</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-animators-artistry-archives/"><u>[Updated] Animator's Artistry Archives</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-hero5-review-capturing-extreme-sports/"><u>[Updated] Hero5 Review  Capturing Extreme Sports</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-delving-into-vimeo-your-ultimate-video-partner/"><u>[Updated] In 2024, Delving Into Vimeo  Your Ultimate Video Partner</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-videotwit2mp4-simple-conversion-for-2024/"><u>[Updated] VideoTwit2MP4  Simple Conversion for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-webcam-use-in-professional-settings-for-slide-shows/"><u>[Updated] Webcam Use in Professional Settings for Slide Shows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-craft-unique-logos-with-no-cost-template-modification/"><u>2024 Approved  Craft Unique Logos with No-Cost Template Modification</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fresh-set-of-interview-points-for-captivated-ears/"><u>2024 Approved  Fresh Set of Interview Points for Captivated Ears</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-top-tier-camera-setups-reviewed-for-new-windows-11-users/"><u>2024 Approved  Top-Tier Camera Setups Reviewed for New Windows 11 Users</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-what-is-ai-text-to-video-wondershare-virbo-glossary/"><u>2024 Approved What Is AI Text to Video? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerate-search-results-in-windows-11-with-these-11-fixes/"><u>Accelerate Search Results in Windows 11 with These 11 Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-frozen-overlays-restoring-function-to-discord-ui/"><u>Addressing Frozen Overlays: Restoring Function to Discord UI</u></a></li>
<li><a href="https://windows11.techidaily.com/adjusting-pcs-duration-before-lockdown/"><u>Adjusting PC's Duration Before Lockdown</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/all-you-need-to-know-about-mega-greninja-for-honor-x8b-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Honor X8b | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/cancellation-procedure-for-paramount-plus-users-what-you-need-to-know/"><u>Cancellation Procedure for Paramount Plus Users – What You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-outlooks-glitch-the-path-to-fixed-error-0x80072746/"><u>Conquering Outlook's Glitch: The Path to Fixed Error 0X80072746</u></a></li>
<li><a href="https://windows11.techidaily.com/corrective-measures-for-discord-search-dysfunction/"><u>Corrective Measures for Discord Search Dysfunction</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-compelling-desktop-imagery-on-windows-11/"><u>Crafting Compelling Desktop Imagery on Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/cross-language-chatgpt-usage-simplified/"><u>Cross-Language ChatGPT Usage Simplified</u></a></li>
<li><a href="https://fox-helps.techidaily.com/designing-dramatic-beginnings-in-podcasts/"><u>Designing Dramatic Beginnings in Podcasts</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-the-power-of-wintoys-a-step-by-step-analysis-for-windows-users/"><u>Discovering the Power of WinToys: A Step-by-Step Analysis for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-microsoft-store-error-0x00000000-in-windows-os/"><u>Eliminating Microsoft Store Error 0X00000000 in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-stability-post-windows-update-with-wsl-in-focus/"><u>Enhancing System Stability Post-Windows Update with WSL in Focus</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-compact-icons-arrangement-in-system-interface/"><u>Fixing Compact Icons Arrangement in System Interface</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-oppo-reno-11f-5g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Oppo Reno 11F 5G Devices | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/free-from-marks-acquiring-unmarked-stock-photography-for-2024/"><u>Free From Marks  Acquiring Unmarked Stock Photography for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/get-rid-of-the-standout-wallpaper-icon-in-win11/"><u>Get Rid of the Standout Wallpaper Icon in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-the-task-manager-start-page-in-windows-11/"><u>How to Change the Task Manager Start Page in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Oppo Reno 10 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-restore-windows-photo-viewer-in-windows-10-2-methods/"><u>How to Restore Windows Photo Viewer in Windows 10 (2 Methods)</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tweak-the-mouse-pointer-accessibility-settings-on-windows-11/"><u>How to Tweak the Mouse Pointer Accessibility Settings on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-oneplus-nord-n30-5g-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from OnePlus Nord N30 5G to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-honor-play-40c-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Honor Play 40C Phone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-leveraging-hashtags-and-mentions/"><u>In 2024, Leveraging Hashtags and Mentions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-secure-simplified-recording-of-video-conferencing/"><u>In 2024, Secure, Simplified Recording of Video Conferencing</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovations-in-podcasting-generating-custom-rss-files-for-2024/"><u>Innovations in Podcasting  Generating Custom RSS Files for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/1719377597268-legacy-software-understanding/"><u>Legacy Software Understanding:</u></a></li>
<li><a href="https://windows11.techidaily.com/lost-and-found-how-to-find-the-disappeared-enhancements-on-windows-11/"><u>Lost and Found: How to Find the Disappeared Enhancements on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/meet-your-new-favorites-top-5-video-creators-and-soundtrack-artists/"><u>Meet Your New Favorites  Top 5 Video Creators & Soundtrack Artists</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-inaccessible-game-on-windows-steam/"><u>Navigating Through Inaccessible Game on Windows Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-for-sticky-note-usage/"><u>Navigating Windows 11 for Sticky Note Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-your-pre-win11-system-efficiently/"><u>Optimize Your Pre-Win11 System Efficiently</u></a></li>
<li><a href="https://extra-support.techidaily.com/premier-accessible-stopwatches-for-2024/"><u>Premier Accessible Stopwatches for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-pc-issues-amidst-minimum-specifications-and-intel-graphic-errors/"><u>Rectifying PC Issues Amidst Minimum Specifications and Intel Graphic Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-absence-of-display-in-boot-process/"><u>Remedying Absence of Display in Boot Process</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-entry-techniques-for-your-windows-11-appshouse/"><u>Seamless Entry Techniques for Your Windows 11 AppsHouse</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/square-it-up-your-complete-guide-to-instagram-ready-videos-in-imovie/"><u>Square It Up! Your Complete Guide to Instagram-Ready Videos in iMovie</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-updating-your-hp-officejet-5255-printer-drivers/"><u>Step-by-Step: Updating Your HP OfficeJet 5255 Printer Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-missing-device-alert-in-windows-10/"><u>Steps to Resolve 'Missing' Device Alert in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-restoring-function-of-wsreset-in-windows/"><u>Strategies for Restoring Function of WSReset in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-and-simplify-game-setup-in-xbox-app/"><u>Streamline and Simplify Game Setup in Xbox App</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-essential-folders-tweaks-for-windows-users/"><u>Streamline Tasks: Essential Folders Tweaks for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/surging-past-connectivity-hurdles-in-win-and-ea-games/"><u>Surging Past Connectivity Hurdles in Win and EA Games</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-strategies-nine-fixes-for-wwe-2k23-stability-on-new-os/"><u>Swift Strategies: Nine Fixes for WWE 2K23 Stability on New OS</u></a></li>
<li><a href="https://windows11.techidaily.com/switch-touch-typing-onoff-with-this-windows-tutorial/"><u>Switch Touch Typing On/Off with This Windows Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/swivel-visual-viewpoint-in-windows-os/"><u>Swivel Visual Viewpoint in Windows OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/techniques-for-stronger-video-content-with-b-clips-for-2024/"><u>Techniques for Stronger Video Content with B-Clips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-and-science-of-professional-printing-from-powerpoint-on-a-windows-computer/"><u>The Art and Science of Professional Printing From PowerPoint on a Windows Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-workspace-mastering-w11-taskbar/"><u>Transform Your Workspace: Mastering W11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-iphoneipad-photo-upload-error-on-windows-os-w11-edition/"><u>Troubleshooting iPhone/iPad Photo Upload Error on Windows OS, W11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-windows-11-desktop-widget-tools/"><u>Turning On Windows 11 Desktop Widget Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/tweak-your-pc-reduce-memorycpu-waste-from-apps/"><u>Tweak Your PC: Reduce Memory/CPU Waste From Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-windows-error-0x800704b3/"><u>Understanding and Fixing the Windows Error: 0X800704B3</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-full-potential-of-comic-viewing-in-win11/"><u>Unleash the Full Potential of Comic Viewing in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-visual-power-with-windows-11s-auto-hdr/"><u>Unlocking Visual Power with Windows 11'S Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/unveil-productivity-customize-taskbar-and-tiles-in-win-11/"><u>Unveil Productivity: Customize Taskbar & Tiles in Win 11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/what-is-ai-marketing/"><u>What Is AI Marketing?</u></a></li>
<li><a href="https://techidaily.com/why-stellar-data-recovery-for-iphone-11-pro-max-takes-time-in-scanning-my-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Why Stellar Data Recovery for iPhone 11 Pro Max takes time in scanning my iPhone? | Stellar</u></a></li>
</ul></div>
