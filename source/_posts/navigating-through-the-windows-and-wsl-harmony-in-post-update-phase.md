---
title: Navigating Through The Windows & WSL Harmony in Post-Update Phase
date: 2024-12-18T17:38:01.475Z
updated: 2024-12-25T19:57:12.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through The Windows & WSL Harmony in Post-Update Phase
excerpt: This Article Describes Navigating Through The Windows & WSL Harmony in Post-Update Phase
keywords: WinWSLPostUpdate,WindowsHarmonyLS,UpdateWindowsWsl,WSLSyncUpdate,HWSLPhasePost,PostUpdateWindowsWSL,HarmonyWinWSLUpdate
thumbnail: https://thmb.techidaily.com/35eb7ec70c3d68bdd6223aba9efbf03bc030e84e65b3cf939f3e4c2fcf3f5d40.jpg
---

## Navigating Through The Windows & WSL Harmony in Post-Update Phase

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://fox-friendly.techidaily.com/updated-novice-necessities-your-first-steps-in-gopro-world-for-2024/"><u>[Updated] Novice Necessities - Your First Steps in GoPro World for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-webcam-safety-the-best-cam-cover-picks-for-2024/"><u>[Updated] Webcam Safety The Best Cam Cover Picks for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhance-entertainment-experience-navigating-netflixs-picture-in-picture-functionality/"><u>Enhance Entertainment Experience Navigating Netflix's Picture-in-Picture Functionality</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/free-online-converter-transforming-your-aiff-files-into-mov-format-with-ease/"><u>Free Online Converter: Transforming Your AIFF Files Into MOV Format with Ease</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Motorola Moto G73 5G? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-iphone-12-mini-without-apple-id-password-by-drfone-ios/"><u>How To Erase an iPhone 12 mini Without Apple ID Password?</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-moving-between-focused-and-unfocused-states-within-windows-terminal/"><u>Mastery in Moving Between Focused and Unfocused States Within Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-tasks-like-a-pro-admin-mode-for-task-manager-on-windows-11/"><u>Navigate Tasks Like a Pro: Admin Mode for Task Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-time-windows-11-file-history-essentials/"><u>Navigate Through Time: Windows 11 File History Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-invalid-system-id-issue-on-windows-11/"><u>Solving the Invalid System ID Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-windows-11-assistive-application/"><u>Strategies to Fix Windows 11 Assistive Application</u></a></li>
<li><a href="https://article-posts.techidaily.com/unlocking-hdr-photography-selecting-superior-models/"><u>Unlocking HDR Photography Selecting Superior Models</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-breaks-boundaries-with-iosmacwindows-pc-support/"><u>Windows Breaks Boundaries with iOS/Mac/Windows PC Support</u></a></li>
</ul></div>

