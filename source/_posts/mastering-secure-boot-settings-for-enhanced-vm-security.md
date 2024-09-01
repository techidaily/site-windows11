---
title: Mastering Secure Boot Settings for Enhanced VM Security
date: 2024-08-31T22:12:35.814Z
updated: 2024-09-01T22:12:35.814Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot Settings for Enhanced VM Security
excerpt: This Article Describes Mastering Secure Boot Settings for Enhanced VM Security
keywords: SecureBootVMSecurity,BoostVMDefense,EnhanceVMSecure,VMBootProtection,AdvancedSecurityBoot,SecurityImmuneSystem,OptimizeVMSafety
thumbnail: https://thmb.techidaily.com/5cbe5314b93a999758b5a00e2527a722031ccfee99834737192b083e09532191.jpg
---

## Mastering Secure Boot Settings for Enhanced VM Security

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-the-novice-writers-guide-to-boosting-brand-visibility-through-content-creation/"><u>[New] 2024 Approved  The Novice' Writers' Guide to Boosting Brand Visibility Through Content Creation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-best-photo-background-blur-apps-for-iphone-and-android-for-2024/"><u>[New] Best Photo Background Blur Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-recorded-talk-extraction-and-study/"><u>[New] Recorded Talk Extraction & Study</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-reviving-camera-victory-over-obs-glitches/"><u>[New] Reviving Camera  Victory Over OBS Glitches</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-ultimate-guide-to-tiktok-income-predictors-for-2024/"><u>[New] The Ultimate Guide to TikTok Income Predictors for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-storytelling-with-epic-videos/"><u>[Updated] In 2024, Instagram Storytelling with Epic Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-ultimate-download-manager-best-youtube-downloader-apps/"><u>[Updated] In 2024, Ultimate Download Manager  Best YouTube Downloader Apps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-integrating-mixer-with-macos-for-smooth-streaming/"><u>[Updated] Integrating Mixer with macOS for Smooth Streaming</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-learn-to-screen-capture-flawlessly-on-mac-using-just-keys-for-2024/"><u>[Updated] Learn to Screen Capture Flawlessly on Mac Using Just Keys for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-acoustic-windows-aficionado-toolkit/"><u>2024 Approved  Acoustic Windows Aficionado Toolkit</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-expert-selection-the-top-11-kid-friendly-waterproof-camcorders/"><u>2024 Approved  Expert Selection  The Top 11 Kid-Friendly, Waterproof Camcorders</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/design-excellence-premier-templates-and-free-2023-plan-guide/"><u>Design Excellence  Premier Templates & Free 2023 Plan Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-restful-nights-with-the-ihome-zenergy-bedside-sleep-enhancer-comprehensive-review/"><u>Discover Restful Nights with the IHome Zenergy Bedside Sleep Enhancer – Comprehensive Review</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-nokia-c300-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Nokia C300</u></a></li>
<li><a href="https://windows11.techidaily.com/explore-and-set-up-your-windows-11-home/"><u>Explore and Set Up Your Windows 11 Home</u></a></li>
<li><a href="https://windows11.techidaily.com/gift-ideas-for-a-christmasy-windows-11-experience/"><u>Gift Ideas for a Christmasy Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-windows-error-0x0000004e-woes/"><u>Guiding Users Through Windows' Error 0X0000004E Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remedy-missing-router-control-center/"><u>How to Remedy Missing Router Control Center</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Samsung Galaxy A25 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-photo-errors-in-windows-devices/"><u>How to Tackle Photo Errors in Windows Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-y02t-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo Y02T to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-ace-2v-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock OnePlus Ace 2V Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://windows11.techidaily.com/ignore-non-essential-feedback-alerts-suggestions-on-windows/"><u>Ignore Non-Essential Feedback Alerts, Suggestions on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/make-the-most-of-older-os-a-guide-beyond-windows-11/"><u>Make the Most of Older OS: A Guide Beyond Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-sign-in-shift-move-from-pin-to-password-effortlessly/"><u>Mastering Windows 11 Sign-In Shift: Move From PIN to Password Effortlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-webcam-fixes-error-a00f4289/"><u>Mastering Windows 11 Webcam Fixes - Error A00F4289</u></a></li>
<li><a href="https://windows11.techidaily.com/nine-steps-to-overcome-0x8004def5-onedrive-error-in-win11/"><u>Nine Steps to Overcome 0X8004Def5 Onedrive Error in Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/no-frills-affordable-camera-selections/"><u>No-Frills, Affordable Camera Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-crash-zeroing-in-on-error-0x800f0831/"><u>Overcoming Windows Crash: Zeroing In on Error 0X800F0831</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-your-snip-tool-text-expertly-on-windows-11/"><u>Perfect Your Snip Tool Text Expertly on Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/record-screen-on-huawei-mate-10-20-p20-and-p10-using-a-built-in-recorder-for-2024/"><u>Record Screen On Huawei Mate 10, 20, P20 and P10 Using a Built-In Recorder for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reduce-cpu-peaks-with-the-help-of-windows-rm-insights/"><u>Reduce CPU Peaks with the Help of Windows RM Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-internet-connectivity-issues-in-windows-11/"><u>Resolving Internet Connectivity Issues in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-nvidia-control-panel-save-issue/"><u>Resolving Nvidia Control Panel Save Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/shielding-windows-key-tactics-for-uac-protection/"><u>Shielding Windows: Key Tactics for UAC Protection</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-with-easy-steps-surface-pcs-version-enhancement-guide/"><u>Smooth Transition with Easy Steps: Surface PCs' Version Enhancement Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-pc-instability-in-city-skylines-2-top-troubleshooting-tips/"><u>Solving PC Instability in City Skylines 2: Top Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/steering-clear-of-xboxs-dead-end-road-error-on-modern-os/"><u>Steering Clear of Xbox's Dead-End Road Error on Modern OS</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-revive-non-launching-obs-on-windows/"><u>Steps to Revive Non-Launching OBS on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-correctly-handle-windows-update-failure-error-0x80070003/"><u>Strategies to Correctly Handle Windows Update Failure (Error 0X80070003)</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-memory-monster-edge-webview2-troubleshooting/"><u>Taming the Memory Monster: Edge WebView2 Troubleshooting</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/transform-free-channel-into-a-profitable-venture-with-500plus-subscribers-for-2024/"><u>Transform Free Channel Into a Profitable Venture - With 500+ Subscribers for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-edges-ongoing-role-in-win11-systems/"><u>Understanding Edge's Ongoing Role in Win11 Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/vivetool-blueprint-engaging-windows-companion/"><u>ViveTool Blueprint: Engaging Windows Companion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-101-tips-for-a-distraction-free-video-backdrop-for-2024/"><u>YouTube 101  Tips for a Distraction-Free Video Backdrop for 2024</u></a></li>
</ul></div>
