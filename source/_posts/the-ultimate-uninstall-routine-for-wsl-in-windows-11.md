---
title: The Ultimate Uninstall Routine for WSL in Windows 11
date: 2024-10-08T19:56:03.793Z
updated: 2024-10-13T02:49:52.160Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Ultimate Uninstall Routine for WSL in Windows 11
excerpt: This Article Describes The Ultimate Uninstall Routine for WSL in Windows 11
keywords: WSL Uninstall Guide,Uninstall WSL Step-by-Step,Remove WSL Windows 11,WSL Deactivation Methods,Simplified WSL Uninstall,Effective WSL Removal Tips,Streamline WSL Uninstalling
thumbnail: https://thmb.techidaily.com/bd8185a9d59d7e33d1cc856ce7e147e5a0c37bc7679792239ca349164c0b304f.jpg
---

## The Ultimate Uninstall Routine for WSL in Windows 11

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129741/7443" target="_top" id="2129741">
  <img src="//a.impactradius-go.com/display-ad/7443-2129741" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129741/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151858/7443" target="_top" id="2151858">
  <img src="//a.impactradius-go.com/display-ad/7443-2151858" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151858/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151871/7443" target="_top" id="2151871">
  <img src="//a.impactradius-go.com/display-ad/7443-2151871" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-bridging-the-web-with-instagram-a-url-tutorial/"><u>[New] 2024 Approved Bridging the Web with Instagram A URL Tutorial</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-imagepurityplus-professional-photo-editing-suite-for-2024/"><u>[New] ImagePurityPlus Professional Photo Editing Suite for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-tactics-to-maximize-engagement-with-every-reddit-post/"><u>[New] Tactics to Maximize Engagement with Every Reddit Post</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-ways-to-erase-iphone-6-plus-when-its-locked-within-seconds-by-drfone-ios/"><u>3 Ways to Erase iPhone 6 Plus When Its Locked Within Seconds</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-y78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/adding-comprehensive-firewall-tools-to-windows-11s-menu-bar/"><u>Adding Comprehensive Firewall Tools to Windows 11’S Menu Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-security-automating-passwords-in-windows-texts/"><u>Advanced Security: Automating Passwords in Windows Texts</u></a></li>
<li><a href="https://windows11.techidaily.com/archiving-acumen-covertly-concealing-zip-in-photos-win11/"><u>Archiving Acumen: Covertly Concealing ZIP in Photos (Win11)</u></a></li>
<li><a href="https://windows11.techidaily.com/blue-screen-decoded-understanding-and-fixing-0x0000003b-in-win-os/"><u>Blue Screen Decoded: Understanding and Fixing 0X0000003B in Win OS</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-compatibility-issues-windows-troubleshooting-blueprint/"><u>Conquer Compatibility Issues: Windows Troubleshooting Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/cool-off-cycles-in-the-world-of-computers/"><u>Cool-Off Cycles in the World of Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/cutting-down-the-memory-usage-of-your-security-app/"><u>Cutting Down the Memory Usage of Your Security App</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-system-errors-win-os-and-df-conundrums-solved/"><u>Deciphering System Errors: Win OS and DF Conundrums Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-and-repairing-dormant-window-control/"><u>Diagnosing and Repairing Dormant Window Control</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/experience-the-nokia-71-superior-pixels-and-lens-combo-without-breaking-the-bank/"><u>Experience the Nokia 7.1: Superior Pixels & Lens Combo without Breaking the Bank</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-vivo-y27s-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Vivo Y27s If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-a6400-absent-actors-where-are-the-videos/"><u>In 2024, A6400 Absent Actors Where Are the Videos?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ios-15-guide-effortlessly-managing-and-ending-itunes-and-app-store-subscriptions-from-your-iphone/"><u>IOS 15 Guide: Effortlessly Managing and Ending iTunes & App Store Subscriptions From Your iPhone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-10-video-rotation-tools-for-a-dynamic-online-presence/"><u>New 2024 Approved Top 10 Video Rotation Tools for a Dynamic Online Presence</u></a></li>
</ul></div>

