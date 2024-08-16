---
title: Illustrating Maximum & Minimum CPU Stages on Windows
date: 2024-08-15T15:44:29.093Z
updated: 2024-08-16T15:44:29.093Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Illustrating Maximum & Minimum CPU Stages on Windows
excerpt: This Article Describes Illustrating Maximum & Minimum CPU Stages on Windows
keywords: CPU Stage Illustration,Min Max CPU Cycle,CPU Performance Limits,Windows CPU Timing,Optimal CPU Usage,CPU Speed Analysis,Stages in PC CPU
thumbnail: https://thmb.techidaily.com/62d72eb39093270995757df1adc43019ed0e362b73decee245e264928d768a5a.jpg
---

## Illustrating Maximum & Minimum CPU Stages on Windows

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-miniature-homes-japanese-and-chinese-inspirations/"><u>[New] 2024 Approved  Miniature Homes  Japanese & Chinese Inspirations</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-striking-the-perfect-balance-in-profile-videos/"><u>[New] 2024 Approved  Striking the Perfect Balance in Profile Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-joining-the-party-your-guide-to-tiktok-livestreams/"><u>[New] In 2024, Joining the Party  Your Guide to TikTok Livestreams</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-seamless-integration-of-phone-and-pc-timelines-with-zoom-meetings/"><u>[New] Seamless Integration of Phone & PC Timelines with Zoom Meetings</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-taming-audio-volume-peaks-using-fl-studios-mastery/"><u>[New] Taming Audio Volume Peaks Using FL Studio's Mastery</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-transform-your-footage-effective-strategies-for-cropping-and-export-on-instagram/"><u>[New] Transform Your Footage  Effective Strategies for Cropping & Export on Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-unseen-screencapture-mastering-discreet-snaptaking-methods/"><u>[New] Unseen ScreenCapture  Mastering Discreet SnapTaking Methods</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-enhancing-content-discovery-via-thumbnails/"><u>[Updated] Enhancing Content Discovery via Thumbnails</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-full-reveal-on-camstudios-recording-capabilities/"><u>[Updated] In 2024, Full Reveal on CamStudio's Recording Capabilities</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-influencers-utopia-summit/"><u>[Updated] Influencers' Utopia Summit</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/11-must-know-tricks-for-effective-fb-video-seo-and-performance-for-2024/"><u>11 Must-Know Tricks for Effective FB Video SEO and Performance for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reimagined-classrooms-through-vr-technology/"><u>2024 Approved  Reimagined Classrooms Through VR Technology</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-power-of-language-20-words-and-phrases-that-transform-your-marketing/"><u>2024 Approved  The Power of Language  20 Words and Phrases That Transform Your Marketing</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-xiaomi-13t-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Xiaomi 13T Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/breaking-barriers-to-sound-in-twitters-visual-share-for-2024/"><u>Breaking Barriers to Sound in Twitter's Visual Share for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/explore-creative-photos-applying-radial-blur-techniques-ps/"><u>Explore Creative Photos  Applying Radial Blur Techniques PS</u></a></li>
<li><a href="https://extra-information.techidaily.com/framing-the-future-expert-tips-for-picture-perfection/"><u>Framing the Future  Expert Tips for Picture Perfection</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-or-show-clock-secrets-of-the-taskbar/"><u>Hide or Show Clock - Secrets of the Taskbar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-x7b-by-fonelab-android-recover-messages/"><u>How To  Restore Missing Messages Files from X7b</u></a></li>
<li><a href="https://windows11.techidaily.com/ideal-choices-premium-windows-systems-for-switch-gaming/"><u>Ideal Choices: Premium Windows Systems for Switch Gaming</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-realme-11-5g-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Realme 11 5G by Name | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-samsung-galaxy-a15-4g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Samsung Galaxy A15 4G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-masterclass-conquering-one-device-livestream-challenges/"><u>In 2024, Masterclass  Conquering One-Device Livestream Challenges</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transitioning-from-rgb-to-srgb/"><u>In 2024, Transitioning From Rgb to Srgb</u></a></li>
<li><a href="https://tech-revival.techidaily.com/in-depth-analysis-from-truthgpts-introduction-through-police-investigations-of-mullvad-vpn-navigate-the-best-free-gaming-experience-on-pc-and-mastering-mech50/"><u>In-Depth Analysis: From TruthGPT's Introduction Through Police Investigations of Mullvad VPN, Navigate the Best Free Gaming Experience on PC and Mastering Mechanical Keyboard Functionality</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-file-handling-sneaking-zips-into-picture-files-on-windows/"><u>Invisible File Handling: Sneaking Zips Into Picture Files on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/jumpstart-your-outdated-machine-with-windows-11-using-to-go-and-rufus-guide/"><u>Jumpstart Your Outdated Machine with Windows 11, Using To Go & Rufus Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/leap-ahead-in-workflow-management-embrace-flow-launcher-advantage/"><u>Leap Ahead in Workflow Management: Embrace Flow Launcher Advantage</u></a></li>
<li><a href="https://windows11.techidaily.com/manual-antivirus-checks-finding-unseen-threats/"><u>Manual Antivirus Checks: Finding Unseen Threats</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-inter-system-file-transfer-with-nearby-share-protocols/"><u>Mastering Inter-System File Transfer with Nearby Share Protocols</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-xbox-live-service-recovery-steps/"><u>Mastering Xbox Live Service Recovery Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-nat-transition-a-comprehensible-win1110-approach/"><u>Mastery Over NAT Transition: A Comprehensible Win11/10 Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-windows-x709-problems/"><u>Mending Windows X709 Problems</u></a></li>
<li><a href="https://screen-recording.techidaily.com/microphone-data-review-tips-for-2024/"><u>Microphone Data Review Tips for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-noise-sensational-success-in-telegram-marketing-for-2024/"><u>Navigating Noise  Sensational Success in Telegram Marketing for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-windows-and-wsl-harmony-in-post-update-phase/"><u>Navigating Through The Windows & WSL Harmony in Post-Update Phase</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-and-enhance-the-ultimate-guide-to-windows-11s-start-screen/"><u>Optimize and Enhance: The Ultimate Guide to Windows 11’S Start Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-a-slowdown-reviving-stalled-torrents/"><u>Overcoming a Slowdown: Reviving Stalled Torrents</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-closed-folder-woes-on-double-click-in-winxpxo11/"><u>Overcoming Closed Folder Woes on Double-Click in WinXP/XO11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-keys-the-artists-best-friend-in-3d-paint/"><u>Quick-Access Keys: The Artist's Best Friend in 3D Paint</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-the-heat-lowering-cpu-consumption-in-setups/"><u>Reducing the Heat: Lowering CPU Consumption in Setups</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-se-2020-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone SE (2020) | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-no-speaker-or-headphones-detected-problems-on-windows-11-8-and-7/"><u>Resolving 'No Speaker or Headphones Detected' Problems on Windows 11, 8 & 7</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrecting-dull-legacy-boot-options/"><u>Resurrecting Dull Legacy Boot Options</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-windows-speech-recognition-failure-to-initialize/"><u>Stop Windows Speech Recognition Failure to Initialize</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/strategies-for-editing-and-elevating-youtube-profiles/"><u>Strategies for Editing and Elevating YouTube Profiles</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-cut-down-on-ram-usage-by-platforms-connecting-devices/"><u>Strategies to Cut Down on RAM Usage by Platforms Connecting Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-account-associations-between-win-and-microsoft/"><u>Streamlining Account Associations Between WIN and MICROSOFT</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-calls-using-intel-unison-with-windows-11-pcs/"><u>Streamlining Calls: Using Intel Unison with Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-development-essential-wsl-2-tips-for-pcs/"><u>Streamlining Development: Essential WSL 2 Tips for PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/the-blueprint-for-locating-system32-in-win11/"><u>The Blueprint for Locating System32 in Win11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-non-number-registration-guide-for-telegram-and-more/"><u>The Non-Number Registration Guide for Telegram & More</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-portable-music-device-guide-to-2024/"><u>The Ultimate Portable Music Device Guide to 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-gratis-car-performance-enhancers-for-windows-pcs/"><u>Top 5 Gratis Car Performance Enhancers for Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/transforming-file-system-visibility-on-modern-windows-pcs/"><u>Transforming File System Visibility on Modern Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-steams-response-error/"><u>Troubleshooting Steam's Response Error</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-overcoming-key-issues-on-win11/"><u>Understanding and Overcoming Key Issues on Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unleashing-chatgpts-potential-in-video-game-narrative-development/"><u>Unleashing ChatGPT's Potential in Video Game Narrative Development</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-windows-11-by-mastering-component-inclusion/"><u>Unlock the Full Potential of Windows 11 by Mastering Component Inclusion</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-potential-creating-custom-lock-patterns-for-windows-11/"><u>Unlock the Potential: Creating Custom Lock Patterns for Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-ai-potential-insights-into-vector-databases/"><u>Unlocking AI Potential: Insights Into Vector Databases</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-widget-features-quickly/"><u>Unlocking Windows 11 Widget Features Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-not-found-top-fixes-and-strategies/"><u>Unmasking Windows 'Not Found': Top Fixes and Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-in-built-color-tuning-for-win11-applications/"><u>Utilizing In-Built Color Tuning for Win11 Applications</u></a></li>
<li><a href="https://extra-resources.techidaily.com/visualize-better-with-these-leading-sticker-addon-apps-for-phones/"><u>Visualize Better with These Leading Sticker Addon Apps for Phones</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-the-0x0000003b-bsod-in-windows-heres-how-to-fix-it/"><u>What Is the 0X0000003B BSOD in Windows? Here's How to Fix It</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10s-forgotten-ui-elements-now-showing-up/"><u>Win10's Forgotten UI Elements: Now Showing Up</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-storage-explained-c-and-d-distinctions/"><u>Windows Storage Explained: C & D Distinctions</u></a></li>
<li><a href="https://windows11.techidaily.com/zero-user-scope-group-policy-execution-in-windows-10-and-11/"><u>Zero-User Scope Group Policy Execution in Windows 10 & 11</u></a></li>
</ul></div>
