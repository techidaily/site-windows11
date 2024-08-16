---
title: How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
date: 2024-08-15T15:28:59.411Z
updated: 2024-08-16T15:28:59.411Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
excerpt: This Article Describes How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10
keywords: Windows Error Fix Guide,Resolve Windows 11/10 Tokens Error,Stop Reference Token Issue,Solve Windows Token Error,Debugging Windows XP/10/11 Tokens,Correct Windows 10/11 Token Errors,Fixing Windows Token Reference Error
thumbnail: https://thmb.techidaily.com/3dd5b17c533ab88ed9cc0f3b00c7a2aa3b7c864b4f9c2a1611133710cbbaabe1.jpg
---

## How to Fix the “An Attempt Was Made to Reference a Token” Error in Windows 11/10

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
5. Wait for the command to finish reregistering DLLs.
6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-rapidpace-timefreeze-film/"><u>[New] 2024 Approved  RapidPace TimeFreeze Film</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-first-steps-toward-monetary-success-on-youtube-for-2024/"><u>[New] First Steps Toward Monetary Success on YouTube for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-streamlined-mac-package-audio-plus-video-capture-for-2024/"><u>[New] Streamlined Mac Package  Audio + Video Capture for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-audiences-choice-bandicam-or-camtasia-for-screen-capture/"><u>[Updated] 2024 Approved  Audience's Choice? Bandicam or Camtasia for Screen Capture</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-expert-insights-into-youtube-thumbnail-design/"><u>[Updated] Expert Insights Into YouTube Thumbnail Design</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-comprehensive-guide-to-video-editing-with-filmora/"><u>2024 Approved  The Comprehensive Guide to Video Editing with Filmora</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprerant-users-resourceful-approach-to-processes-and-themes-in-windows-11/"><u>A Compreran't User's Resourceful Approach to Processes and Themes in Windows 11</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/boost-digital-presence-using-cookiebot-software-features/"><u>Boost Digital Presence Using Cookiebot Software Features</u></a></li>
<li><a href="https://windows11.techidaily.com/breaking-the-mold-unleashing-dormant-windows-11-powers/"><u>Breaking the Mold: Unleashing Dormant Windows 11 Powers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-play-mkv-movies-on-redmi-12-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can I play MKV movies on Redmi 12 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/configure-ideal-window-space-for-your-apps-in-win11/"><u>Configure Ideal Window Space for Your Apps in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/creative-walls-for-your-pc-windows-1011-guide/"><u>Creative Walls for Your PC: Windows 10/11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/device-dialogue-diplomacy-android-plus-pc-sync-guide/"><u>Device Dialogue Diplomacy: Android + PC Sync Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-email-management-gmail-in-outlook-windows-edition/"><u>Effortless Email Management: Gmail in Outlook, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-ride-on-windows-discover-top-5-budget-enhancers/"><u>Elevate Your Ride on Windows: Discover Top 5 Budget Enhancers</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-output-amplitude-for-external-windows-11-audio/"><u>Elevating Output Amplitude for External Windows 11 Audio</u></a></li>
<li><a href="https://windows11.techidaily.com/end-the-ebb-and-flow-top-strategies-for-smooth-windows-streaming/"><u>End the Ebb and Flow: Top Strategies for Smooth Windows Streaming</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-your-black-screen-and-clear-cursor-issues-in-win11/"><u>Erase Your Black Screen & Clear Cursor Issues in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-how-to-erase-past-safety-checks-on-windows/"><u>Expert Tips: How to Erase Past Safety Checks on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/gpresult-command-guide-for-policy-reporting/"><u>GPResult Command Guide for Policy Reporting</u></a></li>
<li><a href="https://windows11.techidaily.com/harmonious-hardware-connections-android-pc-junctions/"><u>Harmonious Hardware Connections: Android-PC Junctions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-batch-convert-heic-images-to-jpeg-format-in-windows-10-and-11/"><u>How to Batch Convert HEIC Images to JPEG Format in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-change-your-username-in-windows-11/"><u>How to Change Your Username in Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-fix-a-blue-screen-of-death-bsod-error-in-windows-10/"><u>How to Fix a Blue Screen of Death (BSOD) Error in Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-nvidia-control-panel-not-opening-in-windows-11/"><u>How to Fix the NVIDIA Control Panel Not Opening in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-14-plus-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 14 Plus to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-x-apples-new-iphone-drfone-by-drfone-ios/"><u>How to Unlock iPhone X, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-5-best-sites-for-quick-templates-on-youtube/"><u>In 2024, 5 Best Sites for Quick Templates on YouTube</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-lava-agni-2-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Lava Agni 2 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-poco-c65-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Poco C65 to New Android? | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-visual-dialogue-maker/"><u>In 2024, Visual Dialogue Maker</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-where-the-magic-of-video-editing-begins-on-youtube/"><u>In 2024, Where the Magic of Video Editing Begins on YouTube</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ring-your-youtube-pinpointing-a-specialized-audience-for-2024/"><u>Mastering Your YouTube  Pinpointing a Specialized Audience for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-gap-enabling-smooth-steam-connection/"><u>Mending the Gap: Enabling Smooth Steam Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/need-windows-help-find-support-tips-and-solutions/"><u>Need Windows Help? Find Support Tips & Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/no-more-erratic-arrows-fixes-for-the-frustrated/"><u>No More Erratic Arrows: Fixes for the Frustrated</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-error-0x80070570-fixing-damaged-files/"><u>Overcoming Windows 11 Error 0X80070570: Fixing Damaged Files</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-11-zoom-malfunction-1132/"><u>Overcoming Windows 11 Zoom Malfunction #1132</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-pc-performance-hurdles-with-intel-graphics-updates/"><u>Remedying PC Performance Hurdles with Intel Graphics Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-system-crash-code-0xc0000001/"><u>Remedying System Crash Code 0xC0000001</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-and-streamline-with-win11s-hard-drive-defrag/"><u>Secure & Streamline with Win11's Hard Drive Defrag</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-storing-error-during-new-app-installation/"><u>Solutions for Storing Error During New App Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-separate-bunched-system-icons/"><u>Strategies to Separate Bunched System Icons</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-unmasking-user-ids-a-guide-to-sids-in-windows-11/"><u>The Art of Unmasking User IDs: A Guide to SIDs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-comprehensive-manual-for-component-settings-in-w11/"><u>The Comprehensive Manual for Component Settings in W11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-choosing-a-screen-for-superior-4k-video-for-2024/"><u>The Ultimate Guide to Choosing a Screen for Superior 4K Video for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-quicken-windows-edge-on-w10-and-w11/"><u>Tips to Quicken Windows Edge on W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-self-contained-internet-station/"><u>Turn Your Windows 11 PC Into a Self-Contained Internet Station</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/understanding-enhanced-functionality-in-nero-waveedito-as/"><u>Understanding Enhanced Functionality in Nero WaveEdito As</u></a></li>
<li><a href="https://windows11.techidaily.com/unexpected-rav-guard-find-its-source-and-quit-methods/"><u>Unexpected Rav Guard? Find Its Source & Quit Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-full-potential-adding-portable-apps-to-w11/"><u>Unlock Full Potential: Adding Portable Apps to W11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-prospects-and-limitations-within-samsungs-2023-image-editor-for-2024/"><u>Unveiling Prospects and Limitations Within Samsung's 2023 Image Editor for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-of-a-smoother-click-lock-in-windows/"><u>Unveiling the Secrets of a Smoother Click Lock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-layers-impact-on-linux-dominance/"><u>Windows Layer's Impact on Linux Dominance</u></a></li>
</ul></div>
