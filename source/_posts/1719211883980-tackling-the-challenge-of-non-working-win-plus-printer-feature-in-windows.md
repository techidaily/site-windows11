---
title: Tackling the Challenge of Non-Working Win + Printer Feature in Windows
date: 2024-08-15T15:23:23.624Z
updated: 2024-08-16T15:23:23.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Challenge of Non-Working Win + Printer Feature in Windows
excerpt: This Article Describes Tackling the Challenge of Non-Working Win + Printer Feature in Windows
keywords: WinPrinterFeatureChallenge,NonWorkingWinPrintSolution,EnhanceWindowsNonWorking,FixNonWorkingPrinterWin,PrinterFeaturesInWinOS,ResolveWinPlusPrinterIssue,OptimizeNonWorkingPrinter
thumbnail: https://thmb.techidaily.com/795b74ea54cc5678eb54323c8f0f4911a2d522641c62a676cf0d7c5aa1dfbffa.jpg
---

## Tackling the Challenge of Non-Working Win + Printer Feature in Windows

 When you press **Win + P** on Windows, you should see a flyout appear that contains options to switch your display. But, sometimes, when you press this shortcut, nothing happens, leaving you unable to change displays easily and quickly. Luckily, we're going to show you some fixes you can try to get the **Win + P** shortcut to work again.

## 1\. Troubleshoot the Keyboard

 Before we get to the other fixes, we highly recommend you try [troubleshooting the keyboard](https://www.makeuseof.com/fix-keyboard-keys-not-working-windows/). This includes checking if the keys are damaged, running the Keyboard Troubleshooter, and updating and reinstalling the keyboard driver.

 For the **Win + P** shortcut in particular, if updating and reinstalling the keyboard driver doesn't work, we recommend doing the same to the display driver as well.

 Another generic fix you can try is [performing an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to find and replace any corrupted or damaged system files on your PC that can cause **Win** \+ **P** to not work. Also, if you managed to [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) when the shortcut was working, you can revert your PC's settings to that restore point to potentially fix the issue.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Turn Off Game Mode

 Game Mode on Windows is a feature that turns off programs and tasks running in the background. That way, your PC has more resources to dedicate toward a smooth gaming experience. However, this feature is known to cause conflicts with the keyboard, and you can fix this by turning it off.

 To do that, press **Win** \+ **S** to bring up Windows Search, type **game mode settings** in the text box, and then click on **Game Mode settings** when it appears in the results.

![Game Mode settings in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/game-mode-settings-windows-search.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the **Game Mode** toggle is **On**, click on it to set it to the **Off** position.

![Turn Off the Game Mode From Game Mode Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/1-turn-off-the-game-mode-from-game-mode-settings-in-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, try the **Win + P** shortcut again to see if the display switch options will show up.

## 3\. Make Sure the Action Center Is Working

 If the Action Center (Quick Settings on Windows 11) isn't working, it can cause the **Win + P** shortcut to not work. Try clicking on the Action Center and see if it will come up. If it doesn't, you can learn [how to fix the Action Center](https://www.makeuseof.com/windows-11-action-center-not-opening/)[when it is not opening](http://www.makeuseof.com/windows-11-action-center-not-opening/).

 Usually, it could just be that you, someone else, or a virus has somehow disabled the Action Center. In that case, you just need to re-enable it to get the shortcut to work again. If the reason is a virus, fire up your antivirus and scan your PC.

## 4\. Try a Different User Account

 If your user account on Windows is corrupted, it can cause certain things to not work, including the **Win + P** shortcut. To verify whether your account is the problem or not, sign out and sign in to a different user account on your PC. Then, try the shortcut on the other user account, and if it works, you can use that one when you need to bring up the display switch options.

 Don't have another user account on your Windows computer? If that's the case, you can learn how to [create a local account on Windows 10](https://www.makeuseof.com/ways-to-create-local-user-account-windows/) or [create a local account on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/). Afterward, you can test if the shortcut is working on the user account you just created.

## 5\. Create a Display Switch Shortcut

 If nothing you've done so far has worked, it might be time to use a workaround. One thing you can do is create a display switch shortcut that you can use to switch the display on your Windows PC.

 To do that, right-click an empty part of your Desktop and select **New > Shortcut**.

![The New and Shortcut options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/new-shortcut-options.jpg)

 The table below shows the locations of the various shortcuts for the display options:

| Display Option     | Shortcut Location                               |
| ------------------ | ----------------------------------------------- |
| PC screen only     | %windir%\\System32\\DisplaySwitch.exe /internal |
| Duplicate          | %windir%\\System32\\DisplaySwitch.exe /clone    |
| Extend             | %windir%\\System32\\DisplaySwitch.exe /extend   |
| Second screen only | %windir%\\System32\\DisplaySwitch.exe /external |

 Depending on the option you want to use, enter the appropriate shortcut location in the text box of the Create Shortcut wizard and click **Next**.

![entering the shortcut path for display switch in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-shortcut-display-switch-shortcut.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 Give the display switch shortcut a name and click **Finish**.

![naming the display switch shortcut in the Create Shortcut wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/naming-display-switch-shortcut.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 You will find the display switch shortcut on the desktop, and when you double-click it, it will switch to the desired display option. You can create display switches for each option if you want.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## Get Win + P Working Again on Windows

 When you want to switch displays on Windows, the **Win + P** shortcut comes in handy. If it's not working, you can try the fixes above to get it to work. And if nothing helps, try creating a display switch shortcut as we've shown you.

 If you don't want to use the display switch shortcut, and you're sure there's nothing wrong with your keyboard, you can try the nuclear option: resetting your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-peaceful-rhythm-the-best-chill-country-music-for-relaxing-dance-parties-on-tiktok/"><u>[New] 2024 Approved  Peaceful Rhythm  The Best Chill Country Music for Relaxing Dance Parties on TikTok</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-blue-enigma-whats-behind-the-symbol-on-facebook-messenger/"><u>[New] 2024 Approved  The Blue Enigma  What's Behind the Symbol on Facebook Messenger?</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-web-based-gag-generator/"><u>[New] In 2024, Web-Based Gag Generator</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-play-your-old-games-anywhere-anytime-choosing-the-best-gba-emulators-for-windows-pcs/"><u>[New] Play Your Old Games Anywhere, Anytime  Choosing the Best GBA Emulators for Windows PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-quick-intro-to-instagram-video-chat/"><u>[Updated] 2024 Approved  Quick Intro to Instagram Video Chat</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-most-viewed-vids-worldwide-roundup/"><u>[Updated] In 2024, Most Viewed Vids Worldwide Roundup</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-quickcapture-stopping-and-saving-screen-moments/"><u>[Updated] In 2024, QuickCapture  Stopping & Saving Screen Moments</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-the-step-by-step-approach-to-twitter-archive-usage/"><u>[Updated] In 2024, The Step-by-Step Approach to Twitter Archive Usage</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-unleash-power-in-social-media-10-advanced-tactics-for-fb-optimization/"><u>[Updated] In 2024, Unleash Power in Social Media  10 Advanced Tactics for FB Optimization</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-insider-secrets-mastering-unseen-social-media-features-for-2024/"><u>[Updated] Insider Secrets  Mastering Unseen Social Media Features for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-key-technique-to-integrate-gopro-content-within-cohesive-spherical-videography/"><u>[Updated] Key Technique to Integrate GoPro Content Within Cohesive Spherical Videography</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-step-by-step-tutorial-for-transforming-profile-photographs-on-social-networks-for-2024/"><u>[Updated] Step-by-Step Tutorial for Transforming Profile Photographs on Social Networks for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-artists-playground-the-prime-6-platforms-for-nft-creation/"><u>2024 Approved  Artists' Playground  The Prime 6 Platforms for NFT Creation</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-and-paid-iphone-photo-experience-top-app-lineup/"><u>2024 Approved  Free & Paid iPhone Photo Experience - Top App Lineup</u></a></li>
<li><a href="https://windows11.techidaily.com/double-click-magic-apks-in-windows-11/"><u>Double-Click Magic: APKs in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effective-approaches-reviving-your-windows-11-search-feature/"><u>Effective Approaches: Reviving Your Windows 11 Search Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-use-of-notes-on-modern-windows-systems/"><u>Efficient Use of Notes on Modern Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-arrow-navigation-post-fixes/"><u>Effortless Arrow Navigation Post-Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-entry-to-sticky-notes-in-windows-11/"><u>Effortless Entry to Sticky Notes in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-experience-multiple-languages-on-windows-os/"><u>Effortlessly Experience Multiple Languages on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-pc-experience-with-smart-windows-app-restarts/"><u>Elevate Your PC Experience with Smart Windows App Restarts</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminate-the-shrinkage-your-guide-to-a-stable-window/"><u>Eliminate the Shrinkage: Your Guide to a Stable Window</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-disk-read-errors-on-windows-os/"><u>Eliminating Disk Read Errors on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-effortless-cross-platform-file-exchange/"><u>Enabling Effortless Cross-Platform File Exchange</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-local-storage-for-onedrive-windows-guide/"><u>Enabling Local Storage for OneDrive - Windows Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-images-on-windows-11-six-proven-scaling-strategies/"><u>Enhance Images on Windows 11: Six Proven Scaling Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-typing-speed-mastering-windows-powertools/"><u>Enhance Typing Speed: Mastering Windows' PowerTools</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-system-navigating-the-smooth-windows-11-upgrade-process/"><u>Enhance Your System: Navigating the Smooth Windows 11 Upgrade Process</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-your-workflow-with-a-customized-windows-outlook-schedule/"><u>Enhance Your Workflow with a Customized Windows Outlook Schedule</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-gameplay-selecting-the-ideal-install-drives/"><u>Enhancing Gameplay: Selecting the Ideal Install Drives</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-underperforming-systems-with-intel-gpu-fixes/"><u>Enhancing Underperforming Systems with Intel GPU Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-experience-finding-your-missing-system-tab/"><u>Enhancing Window's Experience: Finding Your Missing System Tab</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-wsl2-android-resource-management/"><u>Enhancing WSL2: Android Resource Management</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-complete-screen-images-with-snip-and-sketch-tips/"><u>Ensuring Complete Screen Images with Snip & Sketch Tips.</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-seamless-remote-device-connectivity-on-windows/"><u>Ensuring Seamless Remote Device Connectivity on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-directory-not-empty-fault-in-win11-os/"><u>Eradicating Directory Not Empty Fault in Win11 OS</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixed-unsuccessful-gdx-creation-on-vistawin/"><u>Fixed Unsuccessful GDX Creation on VistaWin</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/free-and-easy-top-8-fb-link-exporters-for-23-online/"><u>Free and Easy  Top 8 FB Link Exporters for '23 Online</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-hardware-limitations-for-driver-install/"><u>Overcoming Hardware Limitations for Driver Install</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-music-back-from-motorola-moto-g84-5g-by-fonelab-android-recover-music/"><u>Simple ways to get lost music back from Motorola Moto G84 5G</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/stepwise-process-for-high-quality-screen-captures-from-dell-for-2024/"><u>Stepwise Process for High-Quality Screen Captures From Dell for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/syncing-images-android-iphone-file-transfer-guide-for-2024/"><u>Syncing Images  Android-iPhone File Transfer Guide for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/the-art-of-video-transmission-within-discords-realm-for-2024/"><u>The Art of Video Transmission Within Discord's Realm for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-lava-yuva-2-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Lava Yuva 2 without Him Knowing | Dr.fone</u></a></li>
</ul></div>
