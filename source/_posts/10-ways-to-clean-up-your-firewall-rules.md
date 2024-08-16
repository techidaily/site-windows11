---
title: 10 Ways to Clean Up Your Firewall Rules
date: 2024-08-15T15:23:29.023Z
updated: 2024-08-16T15:23:29.023Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 10 Ways to Clean Up Your Firewall Rules
excerpt: This Article Describes 10 Ways to Clean Up Your Firewall Rules
keywords: Firewall Optimization Tips,Streamlining Firewall Rules,Enhancing Network Security,Firewall Management Strategies,Simplifying Firewall Configurations,Firewall Rule Cleanup Guide,Improving Firewall Efficiency
thumbnail: https://thmb.techidaily.com/4740430244a268b3ae9a4b1e15c683b234a7cf8bdf323c545591ca9aaa0e0818.jpg
---

## 10 Ways to Clean Up Your Firewall Rules

 The Windows Firewall protects your device from malicious threats. But if you don't configure its settings correctly, this tool might prevent you from accessing most of the apps on your device.

 So, what's the solution if you've configured the wrong firewall settings by mistake? It's simple—all you need to do is reset these settings to their defaults.

 Let’s dive in and explore all the solutions.

## 1\. Use the Control Panel

 The Control Panel is an incredible tool that allows you to troubleshoot system issues or tweak PC settings. Now, let’s check out how this tool can help you reset the firewall settings:

1. Type **Control Panel** in the Start menu search bar and select the **Best match**. Alternatively, check out [the various way to access the Control Panel](https://www.makeuseof.com/windows-open-control-panel/).
2. Click the **View by** drop-down menu and select either the **Small icons** or **Large icons** option.
3. Select **Windows Defender Firewall** from the menu items.
4. Click the **Restore defaults** option on the left-hand side and follow the on-screen instructions.

![Clicking the Restore defaults option on the Windows Defender Firewall screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-defaults-option-on-the-windows-defender-firewall-screen.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 2\. Use the Command Prompt

 Ever used the Command Prompt before? It’s an incredible tool that helps you configure system settings, troubleshoot PC issues, and access various apps.

 In fact, you can perform a lot of tasks with this tool as long as you [type in the correct commands](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/).

 Now, let’s check out how to reset the firewall settings using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Type the following command and press **Enter**:

netsh advfirewall reset

 Wait for the process to complete. From there, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

## 4\. Use the Windows Security App

 The Windows Security app is a tool that helps you scan and fix system bugs. Interestingly, you can also use this tool to reset the firewall settings.

 Here are the steps you need to follow:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click the **Restore firewalls to default** option on the next screen.

![Clicking the Restore firewalls to default option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-restore-firewalls-to-default-option.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Use the "Firewall with Advanced Security" Tool

 Still can’t reset the firewall settings? Try one of the options in the “Windows Firewall with Advanced Security” screen.

 As the name suggests, the “Windows Firewall with Advanced Security” tool allows you to configure various advanced settings. So, you can use it later if you want to tweak various firewall settings.

 For now, let’s check out how this tool can help you reset the firewall settings:

1. Press **Win + R** to open the Run command dialog box.
2. Type **wf.msc** and press **Enter** to open the “Windows Defender Firewall with Advanced Security” screen.
3. Navigate to the top-left corner and right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option.
4. Select the **Restore Default Policy** option.

![Selecting the Restore Default Policy option on the Firewall with Advanced Security screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-restore-default-policy-option-on-the-firewall-with-advanced-secutiry-screen.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Restoring the Firewall Settings to Their Default Settings

 It’s quite frustrating when the firewall settings prevent you from accessing the apps on your PC. But the good news is that you can simply resolve such issues by resetting these settings.

 To reset the firewall settings with ease, check out any of the tips we’ve covered. And if you want to reset the Settings app instead, there are solutions for that too!


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-leading-edge-webcams-the-best-on-windows-10/"><u>[New] 2024 Approved  Leading Edge Webcams  The Best on Windows 10</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-maximizing-memories-techniques-for-gameplay-recording/"><u>[New] 2024 Approved  Maximizing Memories  Techniques for Gameplay Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-secure-and-fast-instagram-to-mp4-conversion-for-windowsmac-users/"><u>[New] 2024 Approved  Secure & Fast Instagram to MP4 Conversion for Windows/Mac Users</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-best-practices-for-dynamic-and-dramatic-ae-titles/"><u>[New] In 2024, Best Practices for Dynamic and Dramatic AE Titles</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fresh-face-finds-budget-friendly-platforms-to-purchase/"><u>[New] In 2024, Fresh Face Finds  Budget-Friendly Platforms to Purchase</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-joining-the-digital-dialogue-facebook-basics/"><u>[Updated] Joining the Digital Dialogue (Facebook Basics)</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-step-by-step-guide-to-creating-breathtaking-tile-art-for-2024/"><u>[Updated] Step-by-Step Guide to Creating Breathtaking Tile Art for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamlined-mp4-creation-must-have-tools-on-mac/"><u>[Updated] Streamlined MP4 Creation  Must-Have Tools on Mac</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-ultimate-guide-to-camstudio-recording-and-capturing-for-2024/"><u>[Updated] Ultimate Guide to CamStudio Recording and Capturing for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-efficient-techniques-for-youtube-shorts-revenue/"><u>2024 Approved  Efficient Techniques for YouTube Shorts Revenue</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fabulous-critique-and-diverse-suggestions/"><u>2024 Approved  Fabulous Critique & Diverse Suggestions</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-transform-instagram-videos-into-mp4-with-top-free-online-tools-windowsosx/"><u>2024 Approved  Transform Instagram Videos Into MP4 with Top Free Online Tools [Windows/OSX]</u></a></li>
<li><a href="https://ai-video.techidaily.com/comparative-analysis-of-revenue-projections-amd-sets-higher-target-at-4-billion-while-nvidia-leads-the-race-with-a-40-billion-goal/"><u>Comparative Analysis of Revenue Projections: AMD Sets Higher Target at $4 Billion, While Nvidia Leads the Race with a $40 Billion Goal</u></a></li>
<li><a href="https://windows11.techidaily.com/drive-discretion-in-windows-1011/"><u>Drive Discretion in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/dual-display-designs-selective-screen-splendor-in-win-1011/"><u>Dual-Display Designs: Selective Screen Splendor in Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/easy-steps-to-bypass-renaming-restrictions-on-windows-11/"><u>Easy Steps to Bypass Renaming Restrictions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-data-management-controlling-ntfs-compression/"><u>Efficient Data Management: Controlling NTFS Compression</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-task-management-on-windows-11/"><u>Efficient Task Management on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-managing-frame-rates-to-reduce-delay/"><u>Efficiently Managing Frame Rates to Reduce Delay</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-multisystem-video-processing-on-a-single-windows-setup-with-tdarr/"><u>Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-sound-top-5-apps-for-windows-beyond-maxed-volume/"><u>Elevate Sound: Top 5 Apps for Windows Beyond Maxed Volume</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-account-unlock-admin-potential/"><u>Elevate Your Account - Unlock Admin Potential</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-mouse-interaction-with-clicklock-in-windows/"><u>Elevating Mouse Interaction with ClickLock in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-ssd-speed-in-windows-using-ssd-fresh/"><u>Elevating SSD Speed in Windows Using SSD Fresh</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-vintage-gameplay-experience-with-achievement-boost-via-retroarch/"><u>Elevating Vintage Gameplay Experience with Achievement Boost via Retroarch</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-user-not-valid-error-on-windows-11-and-11/"><u>Eliminating 'User Not Valid' Error on Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-code-0x80300024-from-pc/"><u>Eliminating Error Code: 0X80300024 From PC</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-error-unknown-value-in-windows-systems/"><u>Eliminating Error: Unknown Value in Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-gpu-freeze-fix-code-0x887a0006/"><u>Eliminating GPU Freeze: Fix Code 0X887A0006</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-shutdown-restart-and-sign-out-errors-by-suspicious-apps/"><u>Eliminating Shutdown, Restart, and Sign Out Errors by Suspicious Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/enabledisable-tpm-support-within-virtualbox-70-settings/"><u>Enable/Disable TPM Support Within VirtualBox 7.0 Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-pc-finding-leverage-everywhereapp/"><u>Enhance PC Finding: Leverage EverywhereApp</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-win-gpgpu-capabilities-using-1-6-tools/"><u>Enhance Win GPGPU Capabilities Using #1-#6 Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-typing-speed-via-typingaid-tactics/"><u>Enhance Your Typing Speed via TypingAid Tactics</u></a></li>
<li><a href="https://windows11.techidaily.com/enhanced-docker-functionality-via-optimized-wsl-2-use/"><u>Enhanced Docker Functionality via Optimized WSL 2 Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-alt-code-function-on-windows-46-characters/"><u>Enhancing ALT Code Function on Windows (46 Characters)</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-buffer-free-browsing-chromium-and-youtube/"><u>Enhancing Buffer-Free Browsing: Chromium & YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-discord-performance-on-windows-systems/"><u>Enhancing Discord Performance on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-with-updated-amd-drivers-windows-edition/"><u>Enhancing Graphics with Updated AMD Drivers, Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/enlighten-your-way-to-printer-success-on-windows-11/"><u>Enlighten Your Way to Printer Success on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-clear-audio-a-quick-guide-for-windows-users/"><u>Ensuring Clear Audio: A Quick Guide for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-proper-rights-in-fixing-insufficient-privilege-install-errors/"><u>Ensuring Proper Rights in Fixing Insufficient Privilege Install Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-service-did-not-respond-error-in-windows-os/"><u>Eradicating Service Did Not Respond Error in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/erase-webp-images-from-your-chrome-saved-collection-on-windows/"><u>Erase WebP Images From Your Chrome Saved Collection on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-advice-for-resolving-cc-problems-in-the-latest-os/"><u>Essential Advice for Resolving CC Problems in the Latest OS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exclusive-guide-to-prime-livestream-sites/"><u>Exclusive Guide to Prime Livestream Sites</u></a></li>
<li><a href="https://win-solutions.techidaily.com/game-maintenance-tips-ensuring-a-smooth-run-with-no-more-f1-2e-2021-interruptions-on-desktop-systems/"><u>Game Maintenance Tips: Ensuring a Smooth Run with No More F1 2E 2021 Interruptions on Desktop Systems</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-oneplus-open-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any OnePlus Open Phone Password Using Emergency Call</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-google-pixel-8-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Google Pixel 8 Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-lava-agni-2-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Lava Agni 2 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-is-max-360-superior-to-hero-11-in-video-quality/"><u>In 2024, Is Max 360 Superior to Hero 11 in Video Quality?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/infuse-your-slides-with-clear-voice-communication/"><u>Infuse Your Slides with Clear Voice Communication</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigate-age-confirmation-swiftly-on-tiktok-for-2024/"><u>Navigate Age Confirmation Swiftly on TikTok for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-and-speed-up-printer-f4770n-with-new-driver/"><u>Secure & Speed Up Printer F4770N with New Driver</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-8-editors-tablets-beyond-filmora-havent-you-tried/"><u>Top 8 Editors' Tablets  Beyond Filmora, Haven't You Tried?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-windows-11-error-0x8024401c-during-updates/"><u>Troubleshooting Steps for Windows 11 Error 0X8024401c During Updates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-how-to-solve-opengl32dll-errors-effectively/"><u>Troubleshooting Tips: How To Solve OpenGL32.dll Errors Effectively</u></a></li>
</ul></div>
