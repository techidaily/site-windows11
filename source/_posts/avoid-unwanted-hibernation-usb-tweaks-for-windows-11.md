---
title: Avoid Unwanted Hibernation - USB Tweaks for Windows 11
date: 2024-08-15T15:49:29.319Z
updated: 2024-08-16T15:49:29.319Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Avoid Unwanted Hibernation - USB Tweaks for Windows 11
excerpt: This Article Describes Avoid Unwanted Hibernation - USB Tweaks for Windows 11
keywords: Hibernation Prevention,USB Settings Update,Optimize Windows 11,Enhance Power Saving,Tweaks for W11 Efficiency,Disable Hibernation Feature,Improve System Performance
thumbnail: https://thmb.techidaily.com/8fb2d0d577922e31978350cb180e7bc0e8d3ea4b5792db82388ad0c79872b3d3.jpg
---

## Avoid Unwanted Hibernation - USB Tweaks for Windows 11

 Windows' USB selective suspend feature puts USB devices in a low-power state when not in use. While this can enhance battery life, it may cause problems with peripherals that require constant power.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.

## Why You Might Want to Disable USB Selective Suspend

 Windows has various features to [prolong your laptop's battery life](https://www.makeuseof.com/windows-11-improve-battery-life/), one of which is USB selective suspend. While this feature is great, below are a few situations where you should disable it:

* If Windows fails to recognize a USB device, try turning off USB selective suspend and check if it makes any difference.
* USB selective suspend sometimes adds a small amount of latency, especially in gaming peripherals. So, you can turn it off to get immediate and responsive input from your gaming device.
* USB selective suspend might occasionally conflict with other power management settings, potentially leading to computer instability. If you've been experiencing power-related problems, disabling USB selective suspend could help.

 Now that you know the reason, let’s check out different ways to disable USB selective suspend on Windows 11\.

## 1\. Using the Device Manager

 The Device Manager on Windows is the go-to place to manage USB devices connected to your system. You can use it to [update outdated drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/), uninstall devices, and much more. It can also help you turn off the USB selective suspend feature.

 Follow these steps to disable USB selective suspend via the Device Manager:

1. Press the **Win + X** hotkey and choose **Device Manager** from the context menu.
2. Double-click on the **Universal Serial Bus controllers** node.  
![Universal Serial Bus controllers node in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/universal-serial-bus-controllers-node.jpg)
3. Right-click on any **Generic USB Hub** or **USB Root Hub** drivers and choose **Properties**.  
![USB Root Hub driver in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-root-hub.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
4. Switch to the **Power** **Management** tab and uncheck the **Allow the computer to turn off this device to save power** option. Then, click **OK** to save the changes.  
![Allow the computer to turn off this device to save power option in the Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-the-computer-to-turn-off-this-device-to-save-power-option.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, repeat the above steps for all the USB drivers for which you want to disable USB selective suspend.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
## 2\. Using the Control Panel

 The Control Panel serves as the central hub of a Windows operating system, allowing users to perform a wide range of tasks. From simple actions like [changing your desktop wallpaper](https://www.makeuseof.com/windows-11-change-desktop-wallpaper/) to more complex operations like managing user accounts, you can do it all by accessing the Control Panel.

 Follow these steps to disable USB selective suspend via the Control Panel:

1. Press the **Win** key to open the **Start** **Menu**, type **Control** **Panel** in the search bar, and press Enter.
2. Navigate to **System and Security** \> **Power** **Options** \> **Change** **plan** **settings**.
3. Click the **Change** **advanced** **power settings** option.  
![Change advanced power settings option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-advanced-power-settings-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
4. Double-click on the **USB settings** option and then expand **USB selective suspend setting**.  
![USB selective suspend setting in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/usb-selective-suspend-setting.jpg)
5. Choose **Disabled** for both the **On battery** and **Plugged in** options.  
![Disabled option in Power Option window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disabled-option.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **Apply** \> **OK** to save the changes.

 The USB selective suspend feature is now disabled. Let's look at one more way to do so.

## 3\. Using Command Prompt

 Follow these steps to disable USB selective suspend via the Command Prompt:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane.
2. Type the following command in the elevated Command Prompt window and press Enter.  
`powercfg /SETACVALUEINDEX SCHEME_CURRENT 2a737441-1930-4402-8d77-b2bebba308a3 48e6b7a6-50f5-4782-a5d4-53bb8f07e226 0`  
![Disable USB Selective Suspend command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-usb-selective-suspend.jpg)

 And you're done! The USB selective suspend feature is now disabled on your Windows computer. If you wish, you can easily turn it back on using the same navigation as shown above.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## USB Selective Suspend Is Good, but Not Perfect

 We've taken a look at how and when to disable USB selective suspend. As mentioned earlier, it can occasionally lead to system instability, introduce latency, or even cause your computer to fail to recognize the USB device. Therefore, disabling it might be preferable when power efficiency isn't a top priority for your system.

 However, if disabling USB selective suspend doesn't resolve the issue, there are various other troubleshooting steps you can take when Windows fails to recognize a USB device.

 If you encounter issues with USB devices on your Windows 11 computer, consider disabling the USB selective suspend feature. Here’s how to do so on Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-perfect-your-stories-top-6-apps-for-android-and-iphone-snap-editing/"><u>[New] 2024 Approved  Perfect Your Stories  Top 6 Apps for Android and iPhone Snap Editing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-top-essential-fluid-dynamics-gaming-experiences/"><u>[New] 2024 Approved  Top Essential Fluid Dynamics Gaming Experiences</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-childs-drone-pick-top-five-suggestions/"><u>[New] Child's Drone Pick  Top Five Suggestions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-inventory-guide-to-videography-devices/"><u>[New] In 2024, Inventory Guide to Videography Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-comparative-analysis-of-top-screen-recorders-with-a-spotlight-on-apeaksoft/"><u>[Updated] 2024 Approved  Comparative Analysis of Top Screen Recorders with a Spotlight on Apeaksoft</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-experience-engaged-youtube-exchanges-for-2024/"><u>[Updated] Experience Engaged YouTube Exchanges for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-premium-selection-top-8-tripods-for-clear-4k-videos/"><u>[Updated] Premium Selection  Top 8 Tripods for Clear 4K Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-digital-room-for-screen-dance-duels/"><u>2024 Approved  Digital Room for Screen Dance Duels</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-essential-strategies-to-save-instagram-stories/"><u>2024 Approved  Essential Strategies to Save Instagram Stories</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-hidden-truths-about-youtube-earnings/"><u>2024 Approved  The Hidden Truths About YouTube Earnings</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-the-endless-void-fixing-xbox-app-errors-in-win11/"><u>Avoiding the Endless Void: Fixing Xbox App Errors in Win11</u></a></li>
<li><a href="https://article-tips.techidaily.com/breaking-down-virtual-realitys-mechanics/"><u>Breaking Down Virtual Reality's Mechanics</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-for-inaccessible-administrative-mode/"><u>Comprehensive Solution for Inaccessible Administrative Mode</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-grayed-screen-savers-quick-fixes-for-windows-users/"><u>Curing Grayed Screen Savers: Quick Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-stale-boot-option-imagery/"><u>Curing Stale BOOT Option Imagery</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-crashes-sifting-through-win-files/"><u>Deciphering System Crashes: Sifting Through Win Files</u></a></li>
<li><a href="https://windows11.techidaily.com/enhance-windows-videography-leverage-advanced-distributive-transcoding-by-tdarr/"><u>Enhance Window's Videography: Leverage Advanced Distributive Transcoding by Tdarr</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-productivity-choosing-terminal-as-primary-command-line-interface/"><u>Enhancing Productivity: Choosing Terminal as Primary Command Line Interface</u></a></li>
<li><a href="https://windows11.techidaily.com/experience-true-tech-fusion-windows-android-via-samsung/"><u>Experience True Tech Fusion – Windows, Android via Samsung</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-y100a-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo Y100A Quickly | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-asus-touchpad-driver-for-windows-natively-swift-download-methods/"><u>Get the Latest ASUS Touchpad Driver for Windows Natively | Swift Download Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/getting-a-sneak-peek-of-windows-new-features-via-vivetool/"><u>Getting a Sneak Peek of Windows' New Features via ViVeTool</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-address-0x800f0845-failure/"><u>How to Address 0X800f0845 Failure</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-bypass-ms-defenders-blockage-on-third-party-av/"><u>How to Bypass MS Defender's Blockage on Third-Party AV</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-xiaomi-14-ultra-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Xiaomi 14 Ultra Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-vivo-y200-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Vivo Y200 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-game-changing-tips-master-the-art-of-minecraft-capture-on-a-mac/"><u>In 2024, Game-Changing Tips  Master the Art of Minecraft Capture on a Mac</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-improve-your-virtual-engagement-mastering-snap-photography/"><u>In 2024, Improve Your Virtual Engagement  Mastering Snap Photography</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-approaches-to-elevate-handp-facebook-campaigns/"><u>In 2024, Key Approaches to Elevate H&P Facebook Campaigns</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-smooth-recording-techniques-for-gears-5s-battlegrounds/"><u>In 2024, Smooth Recording Techniques for Gears 5'S Battlegrounds</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-poco-x6-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Poco X6 FRP Bypass</u></a></li>
<li><a href="https://windows11.techidaily.com/least-ram-and-cpu-hungry-browsers-on-triple-operating-systems/"><u>Least RAM and CPU-Hungry Browsers on Triple Operating Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/maintaining-calculator-prominence-in-windows-os/"><u>Maintaining Calculator Prominence in Windows OS</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-360-degree-videos-secure-youtube-uploads-for-2024/"><u>Mastering 360-Degree Videos  Secure YouTube Uploads for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-multi-monitor-setup-changes/"><u>Mastering Multi-Monitor Setup Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-obs-troubleshooting-techniques-for-win-11-users/"><u>Mastering OBS Troubleshooting Techniques for Win 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-constant-calculator-positioning-on-pcs/"><u>Optimizing Constant Calculator Positioning on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-google-chromes-sudden-closure-on-winos/"><u>Quick Fix for Google Chrome’s Sudden Closure on WinOS</u></a></li>
<li><a href="https://windows11.techidaily.com/quickfix-sniping-tool-problems-top-tips-revealed/"><u>QuickFix Sniping Tool Problems: Top Tips Revealed</u></a></li>
<li><a href="https://games-able.techidaily.com/reclaim-your-control-over-noncooperative-steam-software/"><u>Reclaim Your Control Over Noncooperative Steam Software</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-empty-folder-notifications/"><u>Remedying Empty Folder Notifications</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-pc-steps-to-uncover-and-use-lost-features-in-windows-11/"><u>Revive Your PC: Steps to Uncover and Use Lost Features in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/rewind-to-file-explorer-classics-in-w11/"><u>Rewind to File Explorer Classics in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-wows-abrupt-server-quit-error-132-in-win11/"><u>Solutions for WoW's Abrupt Server Quit (Error 132) in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-policy-settings-with-proven-gpo-update-methods/"><u>Streamlining Policy Settings with Proven GPO Update Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/syncing-sound-levels-across-windows-and-bt-audio-gear/"><u>Syncing Sound Levels Across Windows and BT Audio Gear</u></a></li>
<li><a href="https://windows11.techidaily.com/tactical-aid-for-windows-issues-in-googles-nearby-share-app/"><u>Tactical Aid for Windows Issues in Google's Nearby Share App</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-unlock-software-for-oppo-find-n3-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>The Best Android Unlock Software For Oppo Find N3 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://windows11.techidaily.com/the-simple-trick-to-finding-your-installed-application-home/"><u>The Simple Trick to Finding Your Installed Application Home</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-restoring-icon-clarity-on-your-pcs-desktop/"><u>Tips for Restoring Icon Clarity on Your PC's Desktop</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/ultimate-mp4-to-social-media-focus-on-facebook-for-2024/"><u>Ultimate MP4 to Social Media  Focus on Facebook for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-shortcut-for-character-viewing/"><u>Windows 11 Shortcut for Character Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-tab-issue-solutions-for-non-responsive-keys/"><u>Windows Tab Issue: Solutions for Non-Responsive Keys</u></a></li>
</ul></div>
