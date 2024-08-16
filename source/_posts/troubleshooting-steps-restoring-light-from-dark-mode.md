---
title: "Troubleshooting Steps: Restoring Light From Dark Mode"
date: 2024-08-15T15:53:21.126Z
updated: 2024-08-16T15:53:21.126Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Steps: Restoring Light From Dark Mode"
excerpt: "This Article Describes Troubleshooting Steps: Restoring Light From Dark Mode"
keywords: Dark Mode Fix Guide,Light Mode Restore,Reset Display Settings,Switch Off Dark Theme,Revert To Bright Screen,Disable Dark Style,Turn On Light Display
thumbnail: https://thmb.techidaily.com/87f89d3b15c9e03d195fa4c767fb7770437292a210562c1ab5e7ca0ee4b18377.jpg
---

## Troubleshooting Steps: Restoring Light From Dark Mode

 You might often enable dark mode on Windows to reduce eye strain, but it’s quite frustrating when you suddenly can’t switch from dark to normal mode again

 If you’re experiencing this issue, then we’ve got solutions for you. In this article, we’ll explore the five ways to fix your Windows PC when it’s stuck in dark mode.

## 1\. Configure Settings in the Local Group Policy Editor

 The Local Group Policy Editor (LGPE) is a tool that allows you to configure various settings on your device. Interestingly, you can also use the LGPE to troubleshoot various system issues.

 Now, let’s check out how this tool can help you when your device is stuck in dark mode:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing theme** option on the right-hand side pane.

![Using the Local Group Policy Editor to Prevent Others From Changing the Desktop Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-Editor-to-Prevent-Others-From-Changing-the-Desktop-Theme.jpg)

 Next, select the **Not Configured** or **Disabled** option on the pop-up screen. From there, click **Apply** and then click **OK** to disable the **Prevent changing theme** option.

 If the issue persists, navigate to the **Personalization** folder as per the previous steps and then disable the following options:

* Prevent changing color and appearance
* Prevent changing desktop background
* Prevent changing screen saver
* Prevent changing color scheme
* Load a specific theme
* Force specific screen saver
* Force a specific visual style file or force Windows Classic

 Finally, restart your device to save these changes.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Edit the Relevant Registry Files

 Editing some Registry files could also help you tackle the issue at hand. But to be on the safe side, [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before you proceed. This tool is sensitive and could wreak havoc on your PC if you tweak the wrong keys.

 Now, here’s how to fix the “dark mode” problem using the Registry Editor:

1. Press **Win + R** to open the Run command dialog box.
2. Type **regedit** and press **Enter** to open the Registry Editor. Alternatively, check out [the various ways to access the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Type the following command into the address bar:

HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Themes\Personalize

 Next, double-click on the **AppsUseLightTheme** value on the right-hand side pane.

![Clicking the AppsUseLightTheme value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-appsuselighttheme-value.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## No More Getting Stuck in Dark Mode

 There’s no denying that the Windows dark mode option is quite convenient. However, being unable to switch from dark to normal mode is quite unpleasant. If your device is stuck in dark mode, try any of the solutions we’ve covered.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-leading-steps-to-mute-movie-filming/"><u>[New] In 2024, Leading Steps to Mute Movie Filming</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-superior-ff-videograbber-package-easy-and-reliable/"><u>[Updated] 2024 Approved  Superior FF Videograbber Package - Easy and Reliable</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-uncomplicated-approach-for-smooth-iphone-screening/"><u>[Updated] 2024 Approved  Uncomplicated Approach for Smooth Iphone Screening</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-8-mistakes-to-avoid-as-a-new-youtuber/"><u>[Updated] In 2024, 8 Mistakes to Avoid as a New Youtuber</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-zoom-on-xbox-a-step-by-step-guide/"><u>[Updated] Mastering Zoom on Xbox  A Step-by-Step Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-preserving-gh-meetings-live-for-2024/"><u>[Updated] Preserving GH Meetings Live for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-compact-powerhouse-in-flight-dji-sparks-guide-to-aerial-selfies/"><u>[Updated] The Compact Powerhouse in Flight  DJI Spark's Guide to Aerial Selfies</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-the-ultimate-drone-buying-roadmap-pre-purchase-essentials-for-2024/"><u>[Updated] The Ultimate Drone Buying Roadmap  Pre-Purchase Essentials for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transform-your-photos-using-adobes-power/"><u>[Updated] Transform Your Photos Using Adobe's Power</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-vidvault-prodigies-mastering-the-download-of-tweeted-videos-for-2024/"><u>[Updated] VidVault Prodigies  Mastering the Download of Tweeted Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/5-ways-to-fix-the-windows-family-safety-feature-not-working/"><u>5 Ways to Fix the Windows Family Safety Feature Not Working</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-apple-iphone-14-without-a-passcode-drfone-by-drfone-ios/"><u>8 Safe and Effective Methods to Unlock Your Apple iPhone 14 Without a Passcode | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/avoid-distracting-notifications-messages-on-windows-11/"><u>Avoid Distracting Notifications, Messages on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/best-non-procreate-sketch-tools-for-windows-pc/"><u>Best Non-Procreate Sketch Tools for Windows PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comprehensive-insight-into-chatgpt-and-its-versatile-uses-with-generative-ai-technology/"><u>Comprehensive Insight Into ChatGPT and Its Versatile Uses with Generative AI Technology</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723013744708-crusader-kings-ii-wont-start-troubleshooting-solutions-inside/"><u>Crusader Kings II Won't Start? Troubleshooting Solutions Inside!</u></a></li>
<li><a href="https://windows11.techidaily.com/dive-into-dark-display-settings-for-calc-app/"><u>Dive Into Dark Display Settings for Calc App</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-taskbar-windows-11-edition/"><u>Elevate Your Taskbar: Windows 11 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-repeatedly-spotted-edge-buttons/"><u>Fixing Repeatedly Spotted Edge Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-offline-microsoft-onedrive-file-management/"><u>Guide to Offline Microsoft OneDrive File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-fix-keyboard-issues-in-windows-snipper/"><u>How to Quickly Fix Keyboard Issues in Window's Snipper</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlocking-success-optimizing-gaming-videos-via-smart-use-of-hashtags/"><u>In 2024, Unlocking Success  Optimizing Gaming Videos via Smart Use of Hashtags</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-ways-to-initiate-windows-based-software/"><u>Innovative Ways to Initiate Windows-Based Software</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-batch-file-transformation-executable-edition/"><u>Mastering Batch File Transformation: Executable Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-esd-file-conversion-to-iso-on-windows-systems/"><u>Mastering ESD File Conversion to ISO on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-manual-methods-for-malware-detection-on-desktops/"><u>Mastering Manual Methods for Malware Detection on Desktops</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-resource-assignment-in-wsl-android-setup/"><u>Mastering Resource Assignment in WSL-Android Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-sound-settings-9-easy-methods-quickly/"><u>Navigate Through Windows' Sound Settings: 9 Easy Methods, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-connectivity-hurdles-spotify-and-windows-11/"><u>Overcoming Connectivity Hurdles: Spotify & Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-samsung-galaxy-s23-tactical-edition-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Samsung Galaxy S23 Tactical Edition Phone Now with These Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-remote-and-phone-establishing-connections/"><u>PS5 Remote & Phone: Establishing Connections</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-blocked-browsers-by-defender-in-win11/"><u>Quick Fix for Blocked Browsers by Defender in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-reference-guide-to-overcoming-winscombvc-issues/"><u>Quick Reference Guide to Overcoming WinScombVc Issues</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722963389521-rapid-samsung-m2n070fw-driver-setup-download-instantly-now/"><u>Rapid Samsung M2n070Fw Driver Setup - Download Instantly Now!</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaim-your-desktop-win-11-icon-recovery-tips/"><u>Reclaim Your Desktop: Win 11 Icon Recovery Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/regain-stability-the-definitive-net-window-repair-guide-max-156/"><u>Regain Stability: The Definitive .NET Window Repair Guide (Max 156)</u></a></li>
<li><a href="https://techidaily.com/repair-corrupt-pdf-files-on-my-mac-using-tool-stellar-by-stellar-guide/"><u>Repair corrupt PDF files on my Mac using tool | Stellar</u></a></li>
<li><a href="https://windows11.techidaily.com/reprogramming-windows-delete-files-read-lock/"><u>Reprogramming Windows: Delete File's Read Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-slow-windows-apps-ensure-robust-web-linkage/"><u>Revive Slow Windows Apps: Ensure Robust Web Linkage</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-integration-how-to-get-and-run-msibundle-and-appxappxbundles/"><u>Seamless Integration: How to Get & Run MsiBundle & Appx/Appxbundles</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/secure-and-stable-expert-reviews-on-the-most-robust-apc-backup-systems-for-gamers/"><u>Secure and Stable: Expert Reviews on the Most Robust APC Backup Systems for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-taskbar-interaction-enabledisable-ai-on-win-11/"><u>Speed Up Taskbar Interaction: Enable/Disable AI on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-fixing-0x8009030e-on-virt-environments/"><u>Step-by-Step Guide: Fixing 0X8009030E on Virt Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-unlock-your-computers-windows-license/"><u>Techniques to Unlock Your Computer's Windows License</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-the-windows-11-taskbar/"><u>Unlock the Full Potential of the Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-secrets-to-stable-apex-play-on-windows-11/"><u>Unlocking the Secrets to Stable Apex Play on Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-features-of-the-huawei-mediapad-m5-a-masterpiece-for-enthusiasts-in-visual-and-auditory-pleasure/"><u>Unveiling the Features of the Huawei MediaPad M5 - A Masterpiece for Enthusiasts in Visual and Auditory Pleasure</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-2024-approved-10-best-memes-right-now-include-image-gifvideo/"><u>Updated 2024 Approved 10 Best Memes Right Now (Include Image/ GIF/Video)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-cut-to-the-chase-get-direct-access-to-filmora-discount-codes/"><u>Updated 2024 Approved Cut to the Chase Get Direct Access to Filmora Discount Codes</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-unveiling-the-essence-of-sound-pairing-waveforms-with-dynamic-animations-for-adobe-premiere-pro-creatives-for-2024/"><u>Updated Unveiling the Essence of Sound Pairing Waveforms with Dynamic Animations for Adobe Premiere Pro Creatives for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-users-beware-is-yourphoneexe-safe-to-use/"><u>Windows Users Beware: Is YourPhone.exe Safe to Use?</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-sleep-mode-anomalies-why-it-frustrates-users/"><u>Windows' Sleep Mode Anomalies: Why It Frustrates Users</u></a></li>
</ul></div>
