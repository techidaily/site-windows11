---
title: Complete Approach to Deleting the WSL Subsystem
date: 2024-08-08T05:58:32.993Z
updated: 2024-08-09T05:58:32.993Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Complete Approach to Deleting the WSL Subsystem
excerpt: This Article Describes Complete Approach to Deleting the WSL Subsystem
keywords: WSL Deletion Guide,WSL Uninstall Steps,Subsystem Removal Tips,Remove WSL Windows,Disable WSL Linux,Ending WSL Service,Eliminate WSL Environment
thumbnail: https://thmb.techidaily.com/cc2d4ffbafce624b537835413e18b0d5bee03ddebe9cf76be61f42eab18cd22c.jpg
---

## Complete Approach to Deleting the WSL Subsystem

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-10-essential-vlog-editing-hacks-for-novice-creators-for-2024/"><u>[New] 10 Essential Vlog Editing Hacks for Novice Creators for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-cutting-edge-mac-hd-screen-and-sound-mastery-for-2024/"><u>[New] Cutting-Edge Mac HD Screen and Sound Mastery for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/astering-your-unique-fashion-voice-for-2024/"><u>[New] Mastering Your Unique Fashion Voice for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-simplified-approach-to-nvidia-screen-recording/"><u>2024 Approved  Simplified Approach to NVIDIA Screen Recording</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-apple-iphone-13-pro-max-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off Apple iPhone 13 Pro Max without Password</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-inaccessible-page-errors-for-windows-store-apps/"><u>Addressing Inaccessible Page Errors for Windows Store Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/an-intuitive-guide-to-performing-a-windows-rollback-via-system-restore/"><u>An Intuitive Guide to Performing a Windows Rollback via System Restore</u></a></li>
<li><a href="https://windows11.techidaily.com/decluttering-your-win11-desktop-wallpaper-symbol/"><u>Decluttering Your Win11 Desktop Wallpaper Symbol</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-incompatible-gpu-mystery-wins11-and-win10-edition/"><u>Demystifying the Incompatible GPU Mystery: Wins11 & Win10 Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/disentangling-compact-icons-on-desktop-shelf/"><u>Disentangling Compact Icons on Desktop Shelf</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-motorola-moto-g-5g-2023-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Motorola Moto G 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-sound-for-windows-screencasts-with-powerpoint/"><u>Enabling Sound for Windows Screencasts with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-snipping-tool-keyboard-failures-on-pc/"><u>Fixing Snipping Tool Keyboard Failures on PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/frame-your-moment-iphone-apps-for-efficient-photo-cropping-for-2024/"><u>Frame Your Moment  IPhone Apps for Efficient Photo Cropping for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/from-separate-to-shared-android-pc-harmony-guide/"><u>From Separate to Shared: Android-PC Harmony Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-nubia-red-magic-8s-pro-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Nubia Red Magic 8S Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-speed-up-and-conclude-your-puzzled-updates/"><u>How to Speed Up and Conclude Your Puzzled Updates</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-enhanced-visual-content-incorporate-bb-overlays-in-fb-video-frames/"><u>In 2024, Enhanced Visual Content  Incorporate BB Overlays in FB Video Frames</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-precision-window-photography-in-winoses/"><u>In 2024, Precision Window Photography in WinOSes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-calendar-easily/"><u>Navigating Windows 11 Calendar Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-pc-a-guide-to-alomwares-control-options/"><u>Personalize Your PC: A Guide to AlomWare's Control Options</u></a></li>
<li><a href="https://windows11.techidaily.com/precision-installation-microsoft-works-for-modern-windows/"><u>Precision Installation: Microsoft Works for Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-issues-with-the-epic-games-launcher-for-win-users/"><u>Preventing Issues with the Epic Games Launcher for Win Users</u></a></li>
<li><a href="https://windows11.techidaily.com/reigniting-your-calendars-and-mailboxes-w11-edition/"><u>Reigniting Your Calendars and Mailboxes: W11 Edition</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-common-problems-and-solutions-for-playing-disco-elysium-on-windowspc/"><u>Solved! Common Problems & Solutions for Playing 'Disco Elysium' On Windows/PC</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-snipkey-issues-resetting-windows-keys/"><u>Solving SnipKey Issues: Resetting Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-wild-waters-of-xbox-errors-in-win11/"><u>Taming the Wild Waters of Xbox Errors in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-rectify-unresponsive-windows-key/"><u>Techniques to Rectify Unresponsive Windows Key</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-turning-onoff-windows-10s-smartscreen/"><u>Tips for Turning On/Off Windows 10'S SmartScreen</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-tools-for-timely-subtitle-conversion-win-and-mac-edition-best-8-srtr-creators-from-sub-for-2024/"><u>Top Tools for Timely Subtitle Conversion - Win & Mac Edition  Best 8 SRTR Creators From SUB for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-pen-pad-issues-on-windows-os/"><u>Troubleshooting: Pen Pad Issues on Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/winstorage-revival-guide-with-altwindirstat-insights/"><u>WinStorage Revival Guide with AltWinDirStat Insights</u></a></li>
</ul></div>
