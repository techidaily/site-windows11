---
title: "Revitalizing Network Safety: 5 Firewall Tips"
date: 2024-08-15T16:24:04.292Z
updated: 2024-08-16T16:24:04.292Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revitalizing Network Safety: 5 Firewall Tips"
excerpt: "This Article Describes Revitalizing Network Safety: 5 Firewall Tips"
keywords: Firewall Essentials,Secure Networking,Network Defense,Firewall Protection,Cybersecurity Strategies,Safeguard Systems,Firewall Optimization
thumbnail: https://thmb.techidaily.com/0c5d42c4dd20613a1c9b759dc5acc559eb281ce843e00a8afd9a49d32774540a.jpg
---

## Revitalizing Network Safety: 5 Firewall Tips

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
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
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

## 3\. Use Windows PowerShell

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Struggling to reset the firewall settings using the Command Prompt? If so, then try [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/).

 Here’s how to reset the firewall settings using PowerShell:

1. Type **Windows PowerShell** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as Administrator**.
3. Copy-paste the following command into PowerShell and press **Enter**:

(New-Object -ComObject HNetCfg.FwPolicy2).RestoreLocalFirewallDefaults()

 Wait for the process to complete, and then restart your device.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Can’t access the “Windows Defender Firewall with Advanced Security” screen using the steps we’ve covered? Try these methods:

1. Press **Win + I** to access the system settings.
2. Select the **Update & Security** option.
3. Click the **Windows Security** option on the left-hand side.
4. Select the **Firewall & network protection** tool in the middle pane.
5. Click **Advanced settings** in the middle pane.

 From there, right-click on the **Windows Defender Firewall with Advanced Security on Local Computer** option and select the **Restore Default Policy** option.

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
<li><a href="https://some-techniques.techidaily.com/new-from-monotonous-to-magical-techniques-for-animate-text-in-insta-stories/"><u>[New] From Monotonous to Magical  Techniques for Animate Text in Insta Stories</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-cutting-edge-techniques-for-captivating-online-advertising/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques for Captivating Online Advertising</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-decode-your-youtube-preferences-with-these-6-fan-favorite-questionnaires/"><u>[Updated] Decode Your YouTube Preferences with These 6 Fan-Favorite Questionnaires</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-evaluating-cybernetic-screen-recorder-functionality-for-2024/"><u>[Updated] Evaluating Cybernetic Screen Recorder Functionality for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-complete-review-of-movavi-video-editor-plus-users/"><u>[Updated] The Complete Review of Movavi Video Editor Plus Users</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-the-right-move-copyright-validation-before-posting-on-tiktok/"><u>[Updated] The Right Move  Copyright Validation Before Posting on TikTok</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-8-best-video-conferencing-software-for-small-business-safe-and-stable/"><u>2024 Approved  8 Best Video Conferencing Software for Small Business (Safe and Stable)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-fbx-filming-made-simple-a-step-by-step-approach/"><u>2024 Approved  FBX Filming Made Simple  A Step-by-Step Approach</u></a></li>
<li><a href="https://technical-tips.techidaily.com/a-buyers-guide-5-important-aspects-when-selecting-a-rebuilt-personal-computer/"><u>A Buyer's Guide: 5 Important Aspects When Selecting a Rebuilt Personal Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/a-comprehensive-guide-to-hyper-v-installation-in-win-11-home/"><u>A Comprehensive Guide to Hyper-V Installation in Win 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-operational-optimization-top-windows-pct-strategies/"><u>Achieve Operational Optimization: Top Windows PCT Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-the-oculus-quest-2-for-windows-os-virtual-reality/"><u>Adapting the Oculus Quest 2 for Windows OS Virtual Reality</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-edge-windows-gadgets-2024s-must-haves-list/"><u>Cutting-Edge Windows Gadgets - 2024'S Must-Haves List</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-your-global-ip-on-win-os-via-cli/"><u>Demystifying Your Global IP on WIN OS via CLI</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-c33-2023-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme C33 2023 Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/efficient-launch-navigating-video-talks-in-instagram/"><u>Efficient Launch  Navigating Video Talks in Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-your-gameplay-overcoming-lags-in-warfare/"><u>Elevating Your Gameplay: Overcoming Lags in Warfare</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-newest-driver-update-for-your-hp-officejet-4655-easy-guide-and-download-links/"><u>Get the Newest Driver Update for Your HP OfficeJet 4655 - Easy Guide & Download Links</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-controlling-windows-11s-content-filter/"><u>Guide: Controlling Windows 11’S Content Filter</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-deactivate-amdnvidia-vr-boosting/"><u>Guide: How to Deactivate AMD/Nvidia VR Boosting</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-can-you-tell-if-youre-actually-hearing-dolby-atmos-surround-sound/"><u>How Can You Tell If You're Actually Hearing Dolby Atmos Surround Sound?</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-and-upgrade-your-canon-mg490-windows-printing-software/"><u>How to Obtain and Upgrade Your Canon MG490 Windows Printing Software</u></a></li>
<li><a href="https://extra-resources.techidaily.com/implementing-visual-learning-strategies-in-classrooms/"><u>Implementing Visual Learning Strategies in Classrooms</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-novice-to-niche-tripling-your-youtube-fans/"><u>In 2024, From Novice to Niche  Tripling Your Youtube Fans</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-vivo-y17s-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Vivo Y17s Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-m14-4g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy M14 4G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-restoration-top-8-techniques-for-windows/"><u>Mastering File Restoration: Top 8 Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-device-id-extraction-techniques-for-windows-users/"><u>Mastery of Device ID Extraction Techniques for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-freeze-flaws-in-adobes-pc-artist-suite/"><u>Mending Freeze Flaws in Adobe's PC Artist Suite</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-nitpicking-colors-8-tips-for-a-neutral-desktop/"><u>Navigating Nitpicking Colors: 8 Tips for a Neutral Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-setup-google-play-on-windows-11/"><u>Quick Setup: Google Play on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/recover-hidden-5ghz-link-in-windows-11-using-these-fixes/"><u>Recover Hidden 5GHz Link in Windows 11 Using These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-language-input-change-keyboard-layouts-in-win-11/"><u>Simplifying Language Input: Change Keyboard Layouts in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-solve-missing-dll-rockalldlldll-error/"><u>Steps to Solve Missing DLL: Rockalldll.dll Error</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-update-fixes-for-error-0x800736cc/"><u>Streamlining Windows Update Fixes for Error 0X800736CC</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugged-no-more-six-methods-to-restore-functioning-network-hardware-on-your-pc/"><u>Unplugged No More: Six Methods to Restore Functioning Network Hardware on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/utilizing-windows-widgets-for-real-time-resource-tracking/"><u>Utilizing Windows Widgets for Real-Time Resource Tracking</u></a></li>
</ul></div>
