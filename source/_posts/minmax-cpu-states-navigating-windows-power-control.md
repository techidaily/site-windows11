---
title: "Min/Max CPU States: Navigating Windows Power Control"
date: 2024-08-15T16:23:28.999Z
updated: 2024-08-16T16:23:28.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Min/Max CPU States: Navigating Windows Power Control"
excerpt: "This Article Describes Min/Max CPU States: Navigating Windows Power Control"
keywords: CPU Min-Max States,CPU State Limits,Windows Power Ctrl,System State Management,Battery Life Optimization,Energy Saving Techniques,Performance Control Windows
thumbnail: https://thmb.techidaily.com/859749633d2fe977555173ddfc42dda3acc4bf2fd5329788d0569c467b1120f3.jpg
---

## Min/Max CPU States: Navigating Windows Power Control

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
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
<li><a href="https://tiktok-clips.techidaily.com/new-2023-how-to-check-tiktok-video-copyright-before-uploading-in-2024/"><u>[New] 2023 | How to Check Tiktok Video Copyright Before Uploading, In 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-complete-razer-kiyo-webcam-review/"><u>[New] In 2024, Complete Razer Kiyo Webcam Review</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/eamless-transformation-top-tools-for-youtube-videos-for-2024/"><u>[New] Seamless Transformation  Top Tools for YouTube Videos for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-hidden-perspectives-what-youre-ignoring-as-a-stories-viewer/"><u>[Updated] 2024 Approved  Hidden Perspectives  What You're Ignoring as a Stories Viewer</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-seamless-transition-cropping-and-exporting-to-instagram-videos/"><u>[Updated] 2024 Approved  Seamless Transition  Cropping & Exporting to Instagram Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-igtv-a-listers-hanging-out-on-snapchat/"><u>[Updated] IGTV A-Listers Hanging Out on Snapchat</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-requesting-for-unrestricted-access-to-shared-visual-and-audio-content/"><u>[Updated] In 2024, Requesting for Unrestricted Access to Shared Visual & Audio Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-incorporate-tunes-into-ppt-slides-for-2024/"><u>[Updated] Incorporate Tunes Into PPT Slides for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-joining-the-twitter-community-from-scratch/"><u>2024 Approved  Joining the Twitter Community From Scratch</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-stabilizing-high-flying-camera-work-a-guide/"><u>2024 Approved  Stabilizing High-Flying Camera Work  A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/5-essential-fixes-for-hybrid-os-hypervisor-faults/"><u>5 Essential Fixes for Hybrid OS Hypervisor Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-apple-images-not-importing-correctly-on-windows/"><u>Addressing Apple Images Not Importing Correctly on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-windows-default-no-spotify-autoplay/"><u>Avoid Windows Default: No Spotify Autoplay</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-enhancement-installation-of-plugins-step-by-step/"><u>ChatGPT Enhancement: Installation of Plugins Step by Step</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-iso-images-from-your-windows-esd-originals/"><u>Crafting ISO Images From Your Windows' ESD Originals</u></a></li>
<li><a href="https://tech-revival.techidaily.com/critical-insights-into-the-top-6-ai-for-effective-note-capture/"><u>Critical Insights Into the Top 6 AI for Effective Note Capture</u></a></li>
<li><a href="https://windows11.techidaily.com/curtailing-spontaneous-console-appearance-triggers/"><u>Curtailing Spontaneous Console Appearance Triggers</u></a></li>
<li><a href="https://windows11.techidaily.com/determining-effective-network-sharing-tools-tech-giants-face-off/"><u>Determining Effective Network Sharing Tools: Tech Giants Face-Off</u></a></li>
<li><a href="https://windows11.techidaily.com/ease-into-accessibility-windows-fundamentals-for-novices/"><u>Ease Into Accessibility: Windows Fundamentals for Novices</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-workflow-in-windows-11-run-command-innovation-guide/"><u>Elevate Your Workflow in Windows 11: Run Command Innovation Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-click-rate-three-methods-for-mouse-double-click-tweaking/"><u>Enhance Click Rate: Three Methods for Mouse Double-Click Tweaking</u></a></li>
<li><a href="https://win-answers.techidaily.com/f1-2021-frame-rate-issues-resolved-enhanced-performance-on-pc/"><u>F1 2021 Frame Rate Issues Resolved: Enhanced Performance on PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-iphone-6s-plus-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On iPhone 6s Plus</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonize-workflow-setting-active-hours-on-windows-11-for-peace-of-mind/"><u>Harmonize Workflow: Setting Active Hours on Windows 11 for Peace of Mind</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-new-submenus-to-windows-11s-desktop-context-menu/"><u>How to Add New Submenus to Windows 11’S Desktop Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-detect-and-dislodge-suddenly-installed-rav-antivirus/"><u>How to Detect & Dislodge Suddenly Installed Rav Antivirus</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-xiaomi-redmi-13c-5g-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Xiaomi Redmi 13C 5G.</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-honor-magic-5-pro-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Honor Magic 5 Pro in Minutes | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-upload-videos-to-igtv-in-2024/"><u>How to Upload Videos to IGTV, In 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-boosting-earnings-with-effective-social-media-video-marketing-techniques/"><u>In 2024, Boosting Earnings with Effective Social Media Video Marketing Techniques</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-tecno-spark-10c-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Tecno Spark 10C Location on Skout | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-masterchefs-visual-guide-filming-kitchen-escapades/"><u>In 2024, MasterChef's Visual Guide  Filming Kitchen Escapades</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-list-for-seeking-no-cost-high-quality-vector-imagery/"><u>In 2024, The Ultimate List for Seeking No-Cost High-Quality Vector Imagery</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unveiling-youtubes-mechanism-post-upload/"><u>In 2024, Unveiling YouTube's Mechanism Post-Upload</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-nokia-c32-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Nokia C32 Phone FRP Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/leveling-web-speeds-for-seamless-experience/"><u>Leveling Web Speeds for Seamless Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/liberating-windows-past-a-set-of-three-tactics/"><u>Liberating Windows Past - A Set of Three Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-write-permissions-correction-on-win/"><u>Mastering File Write Permissions Correction on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-basics-top-settings-to-optimize-on-new-windows-11/"><u>Mastering the Basics: Top Settings to Optimize on New Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-align-your-sticky-notes-accurately/"><u>Navigating Windows 11: Align Your Sticky Notes Accurately</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-no-supported-devices-found-in-windows-11/"><u>Overcoming No Supported Devices Found in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/perfectly-presented-photos-mastering-the-art-of-crafting-captivating-slideshows-in-win11-photos-app/"><u>Perfectly Presented Photos: Mastering the Art of Crafting Captivating Slideshows in Win11 Photos App</u></a></li>
<li><a href="https://windows11.techidaily.com/personalizing-windows-space-adding-this-pc-iconography/"><u>Personalizing Windows Space: Adding 'This PC' Iconography</u></a></li>
<li><a href="https://windows11.techidaily.com/prevent-windows-stop-recurrent-file-explorer-launches/"><u>Prevent Windows: Stop Recurrent File Explorer Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/pushing-boundaries-my-quest-to-overcome-app-guard-censorship/"><u>Pushing Boundaries: My Quest to Overcome App Guard Censorship</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-any-language-hotkeys-for-efficient-translation-in-windows-os/"><u>Quick Access to Any Language: Hotkeys for Efficient Translation in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-a-polished-w11-workspace/"><u>Quick Fixes for a Polished W11 Workspace</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-route-engaging-windows-11s-capture-utility/"><u>Quick Route: Engaging Windows 11'S Capture Utility</u></a></li>
<li><a href="https://windows11.techidaily.com/rectify-windows-error-reestablishing-java-vm/"><u>Rectify Windows Error: Reestablishing Java VM</u></a></li>
<li><a href="https://windows11.techidaily.com/regaining-control-over-your-speakers-settings-in-windows/"><u>Regaining Control over Your Speakers' Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-workspace-malfunctions-essential-tips-for-office-on-winos/"><u>Resolving Workspace Malfunctions: Essential Tips for Office on WINOS</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revive-your-iphone-files-on-mac-advanced-software-to-retrieve-erased-media-and-contact-details/"><u>Revive Your iPhone Files on Mac: Advanced Software to Retrieve Erased Media & Contact Details</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-fixing-windows-office-error-0x80041015/"><u>Solutions for Fixing Windows Office Error 0X80041015</u></a></li>
<li><a href="https://windows11.techidaily.com/sound-struggles-winning-back-noise-from-windows-spacebar/"><u>Sound Struggles: Winning Back Noise From Windows' Spacebar</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-onedrive-destination-on-windows-pc/"><u>Steering OneDrive Destination on Windows PC</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-process-for-ram-recalibration-on-win-11/"><u>Step-by-Step Process for RAM Recalibration on Win 11</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-strategies-unveiled-essential-youtube-video-resources-for-2024/"><u>Stock Strategies Unveiled  Essential YouTube Video Resources for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-interruptexception-in-win11-blue-screen/"><u>Tackle INTERRUPT_EXCEPTION in Win11 Blue Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/the-savvy-buyers-guide-to-finding-windows-11-deals/"><u>The Savvy Buyer's Guide to Finding Windows 11 Deals</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-ultimate-guide-to-audio-integration-on-reels-for-2024/"><u>The Ultimate Guide to Audio Integration on Reels for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-nokia-c22-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Nokia C22 Phone Pattern Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-view-simple-fixes-for-windows-11-screen-haze/"><u>Transform Your View: Simple Fixes for Windows 11 Screen Haze</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-stalled-netflix-app-on-windows/"><u>Troubleshooting Stalled Netflix App on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-windows-operations-formulating-and-scrutinizing-reports/"><u>Understanding Windows Operations: Formulating & Scrutinizing Reports</u></a></li>
<li><a href="https://tech-hub.techidaily.com/using-gpt-right-away-unlocking-real-time-power-of-chatgpts-advanced-model/"><u>Using GPT-Right Away: Unlocking Real-Time Power of ChatGPT's Advanced Model</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/visual-vibes-humor-through-kapwing/"><u>Visual Vibes  Humor Through Kapwing</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-a-keygen-examining-its-impacts-and-cleanup-techniques-for-pcs/"><u>What Is a Keygen? Examining Its Impacts and Cleanup Techniques for PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/why-does-hearthstone-keep-crashing-expert-tips-for-stable-play-on-pc/"><u>Why Does Hearthstone Keep Crashing? Expert Tips for Stable Play on PC</u></a></li>
</ul></div>
