---
title: 6 Fixes for Windows Gone Dark and Unresponsive
date: 2024-08-15T15:18:42.969Z
updated: 2024-08-16T15:18:42.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 6 Fixes for Windows Gone Dark and Unresponsive
excerpt: This Article Describes 6 Fixes for Windows Gone Dark and Unresponsive
keywords: Rescue Windows Blackout,Revive Non-Responsive WinXP,Troubleshoot Dark Windows XP,Fix Windows Unreactive Errors,Recover Disabled Windows PC,Rectify Windows Freeze Issue,Solve Windows Dark Mode Glitch
thumbnail: https://thmb.techidaily.com/f0eb15dbd4d3bc9550ae7ac5d466cfd7136ebba5996edeb6f057c08fddaa5f37.jpg
---

## 6 Fixes for Windows Gone Dark and Unresponsive

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

## 2\. Tweak the Contrast Theme Settings

 You might be stuck in dark mode simply because you’ve enabled the "High contrast" option on Windows. So, let’s check out how you can resolve this problem:

1. Press **Win + I** to open the system settings.
2. Select **Ease of Access** from the options.
3. Click **High contrast** on the left.
4. **Turn off** the button below the **Turn on high contrast** option and check if this resolves the issue.

![Turning off the button below the Turn on high contrast option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/turning-off-the-button-below-the-turn-on-high-contrast-option.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

 Type **0** in the **Value data** box and then click **OK**.

 From there, set the **Value data** as **0** for the **ColorPrevalence**, **EnableTransparency**, and **SystemUsesLightTheme** values. When you finish, restart your device and check if this resolves the problem.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Disable Third-Party Apps Like the Auto Dark Mode Tool

 Apps like the [Microsoft Auto Dark Mode](https://apps.microsoft.com/store/detail/auto-dark-mode/XP8JK4HZBVF435) tool switch between dark and light modes at scheduled times. If you’ve configured its settings unknowingly, then it might end up enabling the dark mode feature unexpectedly.

 To resolve the issue, the best solution would be to disable this tool (and any other similar third-party app). Alternatively, you can configure the tool’s settings to your liking. That way, your device will only go into dark mode when you want it to.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
## 5\. Perform Some Generic Windows-Based Fixes

 Still struggling to resolve the issue? Perhaps the error is caused by corrupted system files. In this case, the best solution is to [repair corrupted Windows files using its built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

 And if all else fails, [update your Windows device](https://www.makeuseof.com/update-windows-manually/) and see if that helps.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
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
<li><a href="https://youtube-webster.techidaily.com/0-best-travel-youtube-channels-you-may-want-to-follow-for-2024/"><u>[New] 10 Best Travel Youtube Channels You May Want to Follow for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-best-practices-for-documenting-youtube-live-videos/"><u>[New] 2024 Approved  Best Practices for Documenting Youtube LIVE Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-elite-rankings-top-10-apps-to-watch-football-and-volleyball-in-the-moment/"><u>[New] 2024 Approved  Elite Rankings  Top 10 Apps to Watch Football & Volleyball in the Moment</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-character-voiceovers-and-personas-for-dynamic-tiktok-content/"><u>[New] Character Voiceovers and Personas for Dynamic TikTok Content</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-elevate-gameplay-memories-overwatchs-recording-hacks-for-2024/"><u>[New] Elevate Gameplay Memories - Overwatch's Recording Hacks for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-enhance-audio-visual-fidelity-use-av1-on-youtube/"><u>[New] In 2024, Enhance Audio-Visual Fidelity  Use AV1 on YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-master-video-cropping-for-unique-instagram-visuals/"><u>[New] Master Video Cropping for Unique Instagram Visuals</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-transforming-drones-into-cinematic-experiences-with-editing/"><u>[New] Transforming Drones Into Cinematic Experiences with Editing</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-streamline-vimeo-video-publicity-tactics/"><u>[Updated] 2024 Approved  Streamline Vimeo Video Publicity Tactics</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-6-video-translators-to-translate-video/"><u>[Updated] Best 6 Video Translators to Translate Video</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-imovie-hacks-for-unique-and-memorable-youtube-openers/"><u>2024 Approved  IMovie Hacks for Unique and Memorable YouTube Openers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-the-ultimate-screencapture-hackbook-for-techies/"><u>2024 Approved  The Ultimate ScreenCapture Hackbook for Techies</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-conversion-made-simple-learn-how-without-spending-a-dime/"><u>2024 Approved  YouTube Conversion Made Simple – Learn How Without Spending a Dime</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-peaceful-rest-for-your-windows-11-desktop/"><u>Automate Peaceful Rest for Your Windows 11 Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/breach-ethernet-speed-barriers-past-windows-100mbps-ceiling/"><u>Breach Ethernet Speed Barriers: Past Windows' 100Mbps Ceiling</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-home-screen-settings-without-start-menu/"><u>Changing Home Screen Settings Without Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/discovering-distinctive-decor-for-each-monitor-in-windows-11/"><u>Discovering Distinctive Decor for Each Monitor in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/from-oops-to-on-point-8-fixes-for-pink-desktop-displays/"><u>From Oops to On Point: 8 Fixes for Pink Desktop Displays</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-tecno-spark-go-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-itel-a05s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Itel A05s | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-motorola-edge-40-by-fonelab-android-recover-music/"><u>How to recover old music from your Motorola Edge 40</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-and-reset-face-id-on-apple-iphone-15-by-drfone-ios/"><u>How to Remove and Reset Face ID on Apple iPhone 15</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-achieving-flawless-audio-to-text-translation-using-google/"><u>In 2024, Achieving Flawless Audio to Text Translation Using Google</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-battle-of-the-cameras-hero5-black-vs-hero4-silver-showdown/"><u>In 2024, Battle of the Cameras  HERO5 Black vs HERO4 Silver Showdown</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-crafting-an-affordable-diy-google-vr-system-at-home/"><u>In 2024, Crafting an Affordable DIY Google VR System at Home</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-sony-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Sony Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-x0001-error-on-w10w11-systems/"><u>Overcoming GeForce X0001 Error on W10/W11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-store-error-code-0x80073cf3/"><u>Overcoming Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-notetaking-companions-the-7-finest-for-pen-tech/"><u>Perfect Notetaking Companions: The 7 Finest for Pen Tech</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pro-tips-for-slow-motion-videos-on-gopro-hero-10/"><u>Pro Tips for Slow Motion Videos on GoPro Hero 10</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-code-0x0001-failures-for-nvidia-ge-in-w10w11/"><u>Rectifying Code 0X0001 Failures for Nvidia GE in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/redefining-user-experience-the-changing-landsinas-of-w10-and-w11/"><u>Redefining User Experience: The Changing Landsinas of W10 & W11</u></a></li>
<li><a href="https://windows11.techidaily.com/redirect-to-file-explorer-using-the-onedrive-shortcut/"><u>Redirect to File Explorer Using the OneDrive Shortcut</u></a></li>
<li><a href="https://windows11.techidaily.com/sculpting-digital-art-the-most-impressive-new-additions-to-paint/"><u>Sculpting Digital Art: The Most Impressive New Additions to Paint</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-windows-11-surveillance-measures/"><u>Sidestep Windows 11 Surveillance Measures</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/simple-steps-for-successfully-binding-your-samsung-universal-remote-control-to-your-tv-model/"><u>Simple Steps for Successfully Binding Your Samsung Universal Remote Control to Your TV Model</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-windows-memory-errors/"><u>Steps to Overcome Windows Memory Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-eliminate-windows-unknown-value-warning/"><u>Strategies to Eliminate Windows Unknown Value Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-solve-drop-problems-in-win11/"><u>Swiftly Solve Drop Problems in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-unreachable-error-with-spotify-in-windows-1011/"><u>Tackling the Unreachable Error with Spotify in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-to-turn-on-or-off-windows-installation-service/"><u>Tips to Turn On or Off Windows Installation Service</u></a></li>
<li><a href="https://windows11.techidaily.com/top-5-virtual-environments-ideal-for-windows-11-systems/"><u>Top 5 Virtual Environments Ideal for Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/top-7-tabs-notes-that-complement-pen-tech/"><u>Top 7 Tabs: Notes That Complement Pen Tech</u></a></li>
<li><a href="https://windows11.techidaily.com/whats-wrong-with-windows-modern-standby/"><u>What's Wrong with Windows Modern Standby?</u></a></li>
</ul></div>
